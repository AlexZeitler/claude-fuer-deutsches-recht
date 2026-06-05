# Forderungsmanagement — Klagewerkstatt

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`forderungsmanagement-klagewerkstatt`) | [`forderungsmanagement-klagewerkstatt.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/forderungsmanagement-klagewerkstatt.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **Akte Inkasso-Zahlungsklage ModeFuchs** (`inkasso-zahlungsklage-modefuchs`) | [Gesamt-PDF lesen](../testakten/inkasso-zahlungsklage-modefuchs/gesamt-pdf/inkasso-zahlungsklage-modefuchs_gesamt.pdf) | [`testakte-inkasso-zahlungsklage-modefuchs.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-inkasso-zahlungsklage-modefuchs.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

**Generalisierter Klage-Assistent für Inkasso- und Forderungsmanagement-Klagen mit eigenem Plugin-Generator.** Aus eigenen Mustern eine hauseigene Standardvorlage destillieren, online die Zuständigkeit prüfen, die Klage erzeugen und als sofort installierbares Mini-Plugin verpacken. Neu hinzu kommt ein direkter Inkasso-Zahlungsklage-Ersteller mit Mahnvorlauf, Anspruchs-Gatekeeper und der harten Regel: nur klare, fällige und belegte Ansprüche einklagen.

---

---

## Was ist drin

Drei Skills, gedacht als Lernlauf-+-Laufzeit-Paar plus direkter Inkasso-Klageassistent:

| Skill | Zweck |
| --- | --- |
| `klagevorlage-aus-eigenen-mustern` | **Lernlauf**: frisst eigene Klagemuster, Urteile, Kommentare, Aufsätze, Formatvorlagen; destilliert die hauseigene Standardklage-Vorlage; sammelt den Sachverhalt; **prüft online die Zuständigkeit** (justizadressen.nrw.de, justiz.de); liefert die Klage und erzeugt zusätzlich ein eigenes installierbares **Mini-Plugin als ZIP**. |
| `klage-aus-eigenem-skill` | **Laufzeit**: setzt voraus, dass das im Lernlauf erzeugte Mini-Plugin installiert ist. Nimmt nur noch Sachverhalt und Beklagtenadresse, prüft erneut online die Zuständigkeit, befüllt die Hausvorlage. Keine erneute Extraktion. |
| `inkasso-zahlungsklage-ersteller` | **Direktlauf**: liest Forderungsakte, Mahnungen, Abtretung, Inkassoschreiben, Teilzahlungen, Mahnbescheid/Widerspruch und vorhandene Klagen; erstellt Mahnchronologie, Anspruchsmatrix und Gerichtsortprüfung; nimmt nur grüne Positionen in den Klageentwurf. Bezahlte Hauptforderungen werden rot geblockt. |

Alle Klage-Skills führen **bei jedem Lauf** die Online-Zuständigkeitsprüfung über [justizadressen.nrw.de](https://www.justizadressen.nrw.de/de/justiz/suche) und das [bundesweite Justizportal](https://www.justiz.de/onlinedienste/gerichtsverzeichnis_und_orga/index.php) durch.

## Inkasso-Zahlungsklage-Ersteller

Der neue Direktlauf ist für Fälle gedacht, in denen eine Forderungsakte schon einen Mahn- oder Inkassoverlauf enthält. Er prüft vor der Klage:

- Rechnung, Fälligkeit, Lieferung/Leistung und Abtretung.
- Mahnvorlauf mit Zugang, Fristen und Beträgen.
- Zahlungseingänge, Teilzahlungen, Erfüllung und interne Kenntnis.
- Mahnkosten, Verzugszinsen, Inkassokosten und Mahnverfahrenskosten einzeln.
- Gerichtsort mit aktueller ladungsfähiger Anschrift.

Die ModeFuchs-Testakte unter [`testakten/inkasso-zahlungsklage-modefuchs/`](../testakten/inkasso-zahlungsklage-modefuchs/) ist der Referenzfall: Hauptforderung 698,00 EUR bezahlt vor Klageeinreichung, Nebenforderungen 99,84 EUR streitig. Erwartung: Hauptforderung rot, Nebenforderungen gelb, keine automatische Klage über 797,84 EUR. Direktdownload siehe Sofort-Download-Sektion oben.

## Plugin-Generator

Aus den extrahierten Hausregeln und der Standardvorlage packt der Skill ein eigenes, in Claude Code direkt installierbares ZIP:

```bash
python scripts/plugin_aus_hausregeln.py \
  --kanzlei "Kanzlei Mustermann" \
  --vorlage assets/vorlagen-leer/standardklage.md \
  --regeln  /pfad/hausregeln.json \
  --ziel    /pfad/klagewerkstatt-mustermann.zip
```

Layout des erzeugten Plugins:

```
klagewerkstatt-<slug>/
  .claude-plugin/plugin.json
  skills/klage-erstellen/SKILL.md
  assets/vorlage/standardklage.md
  references/hausregeln.json
  references/belegmuster.md
  references/anlagenliste.md
  references/zustaendigkeit-quellen.md
  README.md
```

Der erzeugte Skill enthält die Hausregeln fest verdrahtet und führt weiterhin die **Online-Zuständigkeitsprüfung** als Pflichtschritt aus.

## Ergebnisformate

- **DOCX** über `office/docx` (`Klage-<Beklagte>-<YYYYMMDD>.docx`) und **Markdown-Spiegel**.
- **Anlage Zuständigkeitsprüfung** mit Online-Quelle und Abrufdatum.
- **HTML-Padlet** (`assets/padlet/klage-padlet.html`) — single-file, autark, Live-Vorschau, speichert in `localStorage`, exportiert/importiert JSON.
- **Memo** im Gutachtenstil — nur auf ausdrückliche Anfrage.

## Online-Zuständigkeit (Pflicht in jedem Lauf)

1. **Sachlich** rechnerisch: ≤ 10.000 EUR → AG (§ 23 Nr. 1 GVG i. d. F. seit 1.1.2026); > 10.000 EUR → LG (§ 71 GVG); Sondertatbestände beachten (insbes. Wohnraummietsachen AG ohne Streitwertgrenze, § 23 Nr. 2a GVG).
2. **Örtlich** rechtlich: §§ 12, 13 ZPO Allgemeiner Gerichtsstand, § 29 ZPO Erfüllungsort, § 29c ZPO Verbraucherverträge, § 38 ZPO Gerichtsstandsvereinbarung; grenzüberschreitend Brüssel Ia VO 1215/2012.
3. **Online-Adressrecherche**: `justizadressen.nrw.de` (PLZ/Ort) und bundesweit `justiz.de`; Quelle und Abrufdatum dokumentieren.
4. BeA-SAFE-ID: aus dem beA-Adressbuch zu ergänzen.

## Leitentscheidungen (Auswahl, siehe `references/rechtsprechung/INDEX.md`)

- Rechtsprechung: keine Entscheidung aus Modellwissen zitieren; vor Ausgabe über offizielle oder frei zugängliche Quelle mit Gericht, Entscheidungsform, Datum, Aktenzeichen und tragender Aussage verifizieren.

## Lizenz

Apache-2.0 OR MIT — Auswahl beim Empfänger.

## Quellen-Disclaimer

Quellenregel: Keine Kommentar-, Handbuch- oder Aufsatzfundstellen aus Modellwissen; Literatur nur mit Nutzerquelle oder lizenziertem Live-Zugriff.

<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 25 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `allgemein-workflow-chronologie-workflow-fristen` | Allgemein, Workflow Chronologie Und Belegmatrix, Workflow Fristen Und Risikoampel: Allgemein; Workflow Chronologie Und Belegmatrix; Workflow Fristen Und Risikoampel. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmus... |
| `belegte-faellige-fmkw` | Spezial Belegte Compliance Dokumentation Und Akte, Spezial Faellige Zahlen Schwellen Und Berechnung, Spezial Fmkw Mandantenkommunikation Entscheidungsvorlage: Spezial Belegte Compliance Dokumentation Und Akte; Spezial Faellige Zahlen Sch... |
| `bgb-zpo-fmkw-saumselig-fmkw-titulierung` | Bgb Zpo Forderungsnormcheck, Fmkw Saumselig Streitig Erfahrung Spezial, Fmkw Titulierung Streckung Leitfaden: Bgb Zpo Forderungsnormcheck; Fmkw Saumselig Streitig Erfahrung Spezial; Fmkw Titulierung Streckung Leitfaden. Führt Intake, Prü... |
| `fmkw-verbraucherklage-forderung-anwaltshonorar-forderung` | Fmkw Verbraucherklage Cookies Rdg Spezial, Forderung Anwaltshonorar Rvg, Forderung Arzthonorar Goae: Fmkw Verbraucherklage Cookies Rdg Spezial; Forderung Anwaltshonorar Rvg; Forderung Arzthonorar Goae. Führt Intake, Prüfroutine, Normen-/... |
| `forderung-gegen-gesellschafter-insolventen-schuldner-ausland` | Forderung Gegen Gesellschafter 13 Gmbhg, Forderung Gegen Insolventen Schuldner, Forderung Im Ausland Vollstrecken: Forderung Gegen Gesellschafter 13 Gmbhg; Forderung Gegen Insolventen Schuldner; Forderung Im Ausland Vollstrecken. Führt I... |
| `forderung-mietruckstand-zahlungsklage-verbraucher` | Forderung Mietruckstand Zahlungsklage, Forderung Verbraucher Erleichterungen, Forderung Zwangsvollstreckung Ueberblick: Forderung Mietruckstand Zahlungsklage; Forderung Verbraucher Erleichterungen; Forderung Zwangsvollstreckung Ueberblic... |
| `forderungen-interessen-forderungsmanagement-gatekeeper` | Spezial Forderungen Mehrparteien Konflikt Und Interessen, Spezial Forderungsmanagement Tatbestand Beweis Und Belege, Spezial Gatekeeper Verhandlung Vergleich Und Eskalation: Spezial Forderungen Mehrparteien Konflikt Und Interessen; Spezi... |
| `forderungsmanagement-aufnahme-inkasso-zahlungsklage-klagevorlage` | Forderungsmanagement Aufnahme, Inkasso Zahlungsklage Ersteller, Klagevorlage Aus Eigenen Mustern: Forderungsmanagement Aufnahme; Inkasso Zahlungsklage Ersteller; Klagevorlage Aus Eigenen Mustern. Führt Intake, Prüfroutine, Normen-/Quelle... |
| `inkasso-klage-klagefreigabe-belegte` | Spezial Inkasso Risikoampel Und Gegenargumente, Spezial Klage Formular Portal Und Einreichung, Spezial Klagefreigabe Belegte Forderung: Spezial Inkasso Risikoampel Und Gegenargumente; Spezial Klage Formular Portal Und Einreichung; Spezia... |
| `klage-aus-eigenem-skill` | Kanzlei hat hauseigenes Klage-Plugin (klagewerkstatt-kanzlei) installiert und will damit Klagen aus eigenem Sachverhalt erstellen. Laufzeit-Variante Klagewerkstatt. Prüfraster: Sachverhalt Beklagtenadresse Zuständigkeit §§ 12 13 29 29c Z... |
| `klagewerkstatt-mahnvorlauf-saumselig-sonderfall` | Spezial Klagewerkstatt Erstpruefung Und Mandatsziel, Spezial Mahnvorlauf Dokumentenmatrix Und Lueckenliste, Spezial Saumselig Sonderfall Und Edge Case: Spezial Klagewerkstatt Erstpruefung Und Mandatsziel; Spezial Mahnvorlauf Dokumentenma... |
| `mahnbescheid-online-mahnung-aussergerichtlich-anspruchs` | Mahnbescheid Online Mb, Mahnung Aussergerichtlich Stufenmodell, Spezial Anspruchs Schriftsatz Brief Und Memo Bausteine: Mahnbescheid Online Mb; Mahnung Aussergerichtlich Stufenmodell; Spezial Anspruchs Schriftsatz Brief Und Memo Baustein... |
| `mahnverfahren-beweislast-zustaendigkeitspruefung-forderung` | Spezial Mahnverfahren Beweislast Und Darlegungslast, Spezial Zustaendigkeitspruefung Fristen Form Und Zustaendigkeit, Forderung Aus Werkvertrag Bgb Bau: Spezial Mahnverfahren Beweislast Und Darlegungslast; Spezial Zustaendigkeitspruefung... |
| `spezial-freigegeben-red-team-und-qualitaetskontrolle` | Freigegeben: Red-Team und Qualitätskontrolle im Plugin forderungsmanagement klagewerkstatt; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Standardprüfung. |
| `spezial-klare-livequellen-und-rechtsprechungscheck` | Klare: Livequellen- und Rechtsprechungscheck im Plugin forderungsmanagement klagewerkstatt; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Standardprüfung. |
| `verjaehrung-vollstreckungsbescheid-folgen-zahlungsklage` | Verjaehrung Prüfen, Vollstreckungsbescheid Und Folgen, Zahlungsklage Erstellen: Verjaehrung Prüfen; Vollstreckungsbescheid Und Folgen; Zahlungsklage Erstellen. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster un... |
| `werden-zahlungsklage-urkundenprozess` | Spezial Werden Internationaler Bezug Und Schnittstellen, Spezial Zahlungsklage Behörden Gericht Und Registerweg, Urkundenprozess Prüfen: Spezial Werden Internationaler Bezug Und Schnittstellen; Spezial Zahlungsklage Behörden Gericht Und... |
| `workflow-anschluss-skills-router` | Anschluss-Skills Router im Plugin forderungsmanagement-klagewerkstatt: schlägt nach der ersten Prüfung die passenden Spezialskills aus demselben Plugin vor. |
| `workflow-dokumentenintake` | Dokumentenintake im Plugin forderungsmanagement-klagewerkstatt: liest Uploads, sortiert Dokumentarten, markiert Fristen und baut eine knappe Arbeitsakte. |
| `workflow-kaltstart-und-routing` | Kaltstart und Routing im Plugin forderungsmanagement-klagewerkstatt: führt vom ersten Satz oder Dokument in den passenden Arbeitsweg, erkennt Rolle, Ziel, Risiko und Anschluss-Skills. |
| `workflow-mandantenkommunikation-workflow-redteam-fmkw` | Workflow Mandantenkommunikation, Workflow Redteam Qualitygate, Fmkw Mahnverfahren Bauleiter: Workflow Mandantenkommunikation; Workflow Redteam Qualitygate; Fmkw Mahnverfahren Bauleiter. Führt Intake, Prüfroutine, Normen-/Quellenradar, Be... |
| `workflow-output-waehlen` | Output wählen im Plugin forderungsmanagement-klagewerkstatt: entscheidet zwischen Memo, Schriftsatz, Tabelle, Brief, Checkliste, Vermerk, Redline oder Mandantenübersetzung. |
| `workflow-rechtsquellen-livecheck` | Rechtsquellen-Livecheck im Plugin forderungsmanagement-klagewerkstatt: zwingt vor tragenden Aussagen zum aktuellen Quellencheck bei Gesetzen, Behörden, Gerichten und Formularen. |
| `workflow-unterlagen-lueckenliste` | Unterlagen- und Lückenliste im Plugin forderungsmanagement-klagewerkstatt: erstellt eine präzise Nachforderungsliste statt allgemeiner Fragebögen. |
| `zinsberechnung-bgb` | Zinsberechnung 288 Bgb: Zinsberechnung 288 Bgb. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zusammen. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
