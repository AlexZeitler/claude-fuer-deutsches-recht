# Anlagen zu Schriftsätzen

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`anlagen-zu-schriftsaetzen`) | [`anlagen-zu-schriftsaetzen.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/anlagen-zu-schriftsaetzen.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **Werkmann ./. K+B — Werklohnklage Lackieranlage Eschweiler — Anlagenkonvolut-Verfahren** (`anlagen-zu-schriftsaetzen-konzernumstellung-baudaten-werkmann-baesweiler`) | [Gesamt-PDF lesen](../testakten/anlagen-zu-schriftsaetzen-konzernumstellung-baudaten-werkmann-baesweiler/gesamt-pdf/anlagen-zu-schriftsaetzen-konzernumstellung-baudaten-werkmann-baesweiler_gesamt.pdf) | [`testakte-anlagen-zu-schriftsaetzen-konzernumstellung-baudaten-werkmann-baesweiler.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-anlagen-zu-schriftsaetzen-konzernumstellung-baudaten-werkmann-baesweiler.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

Dieses Plugin ist die Anlagenkanzlei im Kleinen: Es nimmt einen Schriftsatz, einen chaotischen Mandantenordner oder ein schon halb nummeriertes Anlagenpaket und macht daraus eine nachvollziehbare, gerichtstaugliche Anlagenstruktur.

Es hilft besonders dann, wenn nicht einfach „Anlage K1 bis K12“ vorliegt, sondern wenn eine echte Akte lebt: E-Mails mit Anhängen, Scans ohne OCR, Excel-Tabellen, Fotos, Chat-Screenshots, mehrere Vertragsfassungen, fremdsprachige Unterlagen, doppelte Dateien, geschwärzte Drittunterlagen, beA-Grenzen, Verfahrenswechsel und Richterhinweise. Das Plugin führt dann nicht nur eine Nummerierung aus, sondern baut eine Arbeitslogik: Welche Tatsache soll durch welche Anlage belegt werden? Welche Datei gehört wirklich zu K1? Welche Unterlagen sind nur Konvolutbestandteil? Welche Anlage ist zu groß, unleserlich, falsch benannt, doppelt oder im Schriftsatz nicht eingeführt?

## Wofür es gedacht ist

| Situation | Was das Plugin macht | Ergebnis |
| --- | --- | --- |
| Klage/Replik liegt vor, Anlagen sind noch ungeordnet | Schriftsatz lesen, Beweisanker erkennen, K-Nummern vorschlagen, Dateien zuordnen | K1/K2/K3-Reihenfolge, Anlagenverzeichnis, Lückenliste |
| Anlagen sind schon nummeriert, aber niemand traut dem Paket | Prüfmodus: Nummern, Zitate, Dateien, Stempel, Namen, Lesbarkeit und beA-Fähigkeit prüfen | Fehlerprotokoll mit Korrekturplan |
| Mandant liefert Datenraum/ZIP/USB-Stick | Duplikate, Fassungen, Hashes, Dateitypen, Zeitfolge und Relevanz sortieren | Belegmatrix und Nachforderungsliste |
| Eine Anlage ist ein Konvolut | Deckblatt, Untergliederung, interne Seiten-/Dokumentlogik, kurze Erläuterung für Gericht | `Anlage K1` mit `K1.1`, `K1.2`, `K1.3` |
| Elektronische Einreichung steht bevor | Dateinamen, PDF/OCR, Paketgrößen, Anlagenverzeichnis, Prüfvermerk | beA-/ERV-taugliches Versandpaket |

## Der K1-Gedanke

Die erste Anlage ist fast nie nur eine Datei. In großen Verfahren ist `K1` häufig der Orientierungspunkt für das Gericht: Vertrag, Auftrag, Rahmenvereinbarung, Nachtrag, Bestätigungsmail, Protokoll oder Dokumentenfamilie. Das Plugin behandelt `K1` deshalb als Sortierproblem:

1. **Was soll K1 beweisen?** Nicht „alles zum Vertrag“, sondern eine konkrete Tatsache.
2. **Ist K1 Einzelanlage oder Konvolut?** Bei Konvolut: Deckblatt, Reihenfolge, interne Kurzbezeichnungen.
3. **Welche Fassungen gibt es?** Entwurf, unterschriebene Fassung, Scan, OCR-PDF, E-Mail-Anhang, spätere Ergänzung.
4. **Welche Datei ist die gerichtliche Fassung?** Die anderen Fassungen wandern in den internen Hash-/Versionenlog.
5. **Wie wird K1 im Schriftsatz eingeführt?** Der Schriftsatz muss den Tatsachenkern selbst tragen; die Anlage belegt ihn nur.

## Drei Arbeitsmodi

**Auto-Benennung:** Der Schriftsatz enthält noch keine Nummern. Das Plugin liest die Beweisstellen und schlägt die Reihenfolge vor.

**Schriftsatz folgt:** Der Schriftsatz enthält bereits `Anlage K...`-Verweise. Das Plugin sucht die passenden Dateien, erkennt Lücken und meldet Überschüsse.

**Prüfmodus:** Ein fertiges Anlagenpaket wird gegengeprüft: `K7` fehlt, `K12` ist doppelt, `K18` wird im Schriftsatz nie erwähnt, `K23` hat keinen OCR-Text, `K31` enthält ungeschwärzte Drittinformationen.

## Typische Outputs

- Anlagenverzeichnis für Gericht und Kanzleiakte.
- K/B/AST/AG-Nummerierung mit eindeutiger Dateinamenkonvention.
- Konvolutdeckblätter für Sammelanlagen.
- Belegmatrix: Tatsachenbehauptung ↔ Schriftsatzstelle ↔ Anlage ↔ Datei ↔ Status.
- Hash-/Duplikat-/Fassungslog für interne Kontrolle.
- beA-Versandliste mit Paketgrößen, Dateinamen und letzten Prüfpunkten.
- Nachforderungsliste an Mandant oder Sachbearbeitung.
- Berichtigungs- oder Nachreichungsplan nach gerichtlichem Hinweis.

## Wichtig

Anlagen ersetzen keinen Tatsachenvortrag. Wenn eine Behauptung entscheidungserheblich ist, muss sie im Schriftsatz stehen. Die Anlage belegt, erläutert oder vertieft; sie darf nicht der Ort sein, an dem der eigentliche Vortrag versteckt wird.

## Installation in Claude Code

1. ZIP herunterladen (Link oben).
2. Claude Code → **Customize Plugins** → **Install from .zip** → Datei wählen.
3. Fertig. Skills sind sofort verfügbar.

> **Hinweis:** Für den ZIP-Upload muss das Archiv direkt `.claude-plugin/plugin.json`, `skills/`, `assets/` und `references/` im ZIP-Root enthalten. **Nicht** das komplette Repository-ZIP aus "Code → Download ZIP" verwenden.

## Besonders wichtige Skills

| Skill | Zweck |
| --- | --- |
| `allgemein` | Kaltstart, Triage, Nummernkreis, Ziel-Schriftsatz, K1-Frage und Routing in die passenden Spezial-Skills. |
| `anlagen-zu-schriftsaetzen` | Hauptworkflow für Auto-Benennung, Schriftsatz-folgt-Modus, Prüfmodus und Reparatur nach Hinweis. |
| `k1-sortierwerkstatt` | Baut aus Vertrag, Nachtrag, Mail, Scan und OCR-Fassung eine klare Leit-Anlage `K1` oder ein K1-Konvolut. |
| `schriftsatz-anlagen-mapping` | Verknüpft Tatsachenvortrag, Schriftsatzstelle, Beweisangebot, Anlage und Datei in einer Belegmatrix. |
| `anlagen-duplikate-versionen-hashlog` | Erkennt Dubletten, Versionen, OCR-Kopien und die maßgebliche gerichtliche Fassung. |
| `bea-paketierung-groessen-und-versandplan` | Plant Dateinamen, Paketgrößen, Teilpakete, Begleitvermerk und Eingangskontrolle. |
| `anlagen-qualitygate-finalcheck` | Letzter strenger Check vor Versand: Nummern, Zitate, Dateien, OCR, Schwärzung, Stempel, Paket. |

## Lizenz

Apache-2.0 OR MIT — Auswahl beim Empfänger.


<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 27 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `anlage-red-anlagen-anlagenkonvolut-sonderfall-arial` | Spezial Anlage Red Team Und Qualitaetskontrolle, Spezial Anlagen Tatbestand Beweis Und Belege, Spezial Anlagenkonvolut Sonderfall Und Edge Case, Spezial Arial Mandantenkommunikation Entscheidungsvorlage: Spezial Anlage Red Team Und Quali... |
| `anlagen-an-assistenz-uebersetzungspflicht-vorlagepflicht-zpo` | Anlagen Übergabe An Assistenz Und Legal Tech, Anlagen Uebersetzungspflicht, Anlagen Vorlagepflicht 141 Zpo, Anlagen Zur Substantiierung Pflicht: Anlagen Übergabe An Assistenz Und Legal Tech; Anlagen Uebersetzungspflicht; Anlagen Vorlagep... |
| `anlagen-berufung-revision-eilantrag-eu-bilder-screenshots` | Anlagen Bei Berufung Revision, Anlagen Bei Eilantrag Eu Arrest, Anlagen Bilder Screenshots, Anlagen Duplikate Versionen Hashlog: Anlagen Bei Berufung Revision; Anlagen Bei Eilantrag Eu Arrest; Anlagen Bilder Screenshots; Anlagen Duplikat... |
| `anlagen-check-zustellung-redaktion-dsgvo-schwaerzen-stempel` | Anlagen Quality Check Vor Zustellung, Anlagen Redaktion Dsgvo Geschgehg, Anlagen Schwaerzen Anonymisieren, Anlagen Stempel Und Deckblattlogik: Anlagen Quality Check Vor Zustellung; Anlagen Redaktion Dsgvo Geschgehg; Anlagen Schwaerzen An... |
| `anlagen-elektronische-dokumente-format-dateinamen-bea-versand` | Anlagen Elektronische Dokumente Spezial, Anlagen Format Und Dateinamen, Anlagen Für Bea Versand, Anlagen Für Glaubhaftmachung: Anlagen Elektronische Dokumente Spezial; Anlagen Format Und Dateinamen; Anlagen Für Bea Versand; Anlagen Für G... |
| `anlagen-qualitygate-finalcheck` | Finaler Red-Team-Check vor Einreichung: Nummern, Schriftsatzverweise, Dateien, Stempel, OCR, Schwärzung, Dateinamen, beA-Paket, Lücken und Begleitvermerk. |
| `anlagen-zu-schriftsaetzen` | Anwalt hat Schriftsatz fertig und muss Anlagen korrekt benennen nummerieren und als PDF-Konvolut aufbereiten. Anlagemanagement gerichtliche Schriftsaetze. Prüfraster: Schriftsatz lesen Beweisstuecke erkennen sortieren beA-konforme Benenn... |
| `anlagenband-strukturieren-anlagenbezug-anlagenkonvolut` | Anlagenband Strukturieren, Anlagenbezug Im Schriftsatz, Anlagenkonvolut Konsolidieren, Anlagenmatrix Csv Xlsx Aufbau: Anlagenband Strukturieren; Anlagenbezug Im Schriftsatz; Anlagenkonvolut Konsolidieren; Anlagenmatrix Csv Xlsx Aufbau. F... |
| `anlagenverzeichnis-kanzlei-grundaufbau-bea-paketierung-berufung` | Anlagenverzeichnis Gericht Kanzlei Und Intern, Anlagenverzeichnis Grundaufbau, Bea Paketierung Groessen Und Versandplan, Berufung Beschwerde Und Neue Anlagen: Anlagenverzeichnis Gericht Kanzlei Und Intern; Anlagenverzeichnis Grundaufbau;... |
| `baut-beweislast-benennt-bereits-excel` | Spezial Baut Beweislast Und Darlegungslast, Spezial Benennt Compliance Dokumentation Und Akte, Spezial Bereits Abschlussprodukt Und Übergabe, Spezial Excel Schriftsatz Brief Und Memo Bausteine: Spezial Baut Beweislast Und Darlegungslast;... |
| `beweisangebot-anlage-emails-chats-excel-tabellen-fremdsprachige` | Beweisangebot Anlage Zeugen, Emails Chats Screenshots Als Anlagen, Excel Tabellen Und Zahlenbeweis, Fremdsprachige Anlagen Uebersetzung: Beweisangebot Anlage Zeugen; Emails Chats Screenshots Als Anlagen; Excel Tabellen Und Zahlenbeweis;... |
| `haftpflicht-versicherer-konvention-k-konvention` | Anlagen Haftpflicht Versicherer, Anlagen Konvention K B Erlaeutert, Anlagen Konvention Mandantenfreundlich, Anlagen Prozessual Prüfung Spezial: Anlagen Haftpflicht Versicherer; Anlagen Konvention K B Erlaeutert; Anlagen Konvention Mandan... |
| `k1-anlagenpaket-k1-sortierwerkstatt-massenanlagen-sampling` | K1 Anlagenpaket Aus Chaosordner, K1 Sortierwerkstatt, Massenanlagen Sampling Und Repraesentativitaet, Mehrparteien Rollen Und Praefixe: K1 Anlagenpaket Aus Chaosordner; K1 Sortierwerkstatt; Massenanlagen Sampling Und Repraesentativitaet;... |
| `konform-interessen-konvertiert-oben-schriftsaetzen` | Spezial Konform Mehrparteien Konflikt Und Interessen, Spezial Konvertiert Zahlen Schwellen Und Berechnung, Spezial Oben Formular Portal Und Einreichung, Spezial Schriftsaetzen Dokumentenmatrix Und Lueckenliste: Spezial Konform Mehrpartei... |
| `nachreichung-berichtigung-ocr-scan-original-abschrift-anlagen` | Nachreichung Berichtigung Und Gerichtshinweis, Ocr Scan Lesbarkeit Und Beweiswert, Original Abschrift Kopie Und Elektronische Fassung, Schriftsatz Anlagen Mapping: Nachreichung Berichtigung Und Gerichtshinweis; Ocr Scan Lesbarkeit Und Be... |
| `pruefmodus-fristennotiz-datenraum-sharepoint-edv-systemen` | Spezial Pruefmodus Fristennotiz Und Naechster Schritt, Anlagen Aus Datenraum Und Sharepoint, Anlagen Aus Edv Systemen, Anlagen Aus Mandantenmaterial: Spezial Pruefmodus Fristennotiz Und Naechster Schritt; Anlagen Aus Datenraum Und Sharep... |
| `spezial-logik-livequellen-und-rechtsprechungscheck` | Logik: Livequellen- und Rechtsprechungscheck im Plugin anlagen zu schriftsaetzen; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Standardprüfung. |
| `spezial-schriftsatz-sortiert-stempelt-word` | Spezial Schriftsatz Verhandlung Vergleich Und Eskalation, Spezial Sortiert Risikoampel Und Gegenargumente, Spezial Stempelt Internationaler Bezug Und Schnittstellen, Spezial Word Behörden Gericht Und Registerweg: Spezial Schriftsatz Verh... |
| `workflow-allgemein-chronologie-belegmatrix-fristen-risikoampel` | Allgemein, Workflow Chronologie Und Belegmatrix, Workflow Fristen Und Risikoampel, Workflow Mandantenkommunikation: Allgemein; Workflow Chronologie Und Belegmatrix; Workflow Fristen Und Risikoampel; Workflow Mandantenkommunikation. Führt... |
| `workflow-anschluss-skills-router` | Anschluss-Skills Router im Plugin anlagen-zu-schriftsaetzen: schlägt nach der ersten Prüfung die passenden Spezialskills aus demselben Plugin vor. |
| `workflow-dokumentenintake` | Dokumentenintake im Plugin anlagen-zu-schriftsaetzen: liest Uploads, sortiert Dokumentarten, markiert Fristen und baut eine knappe Arbeitsakte. |
| `workflow-kaltstart-und-routing` | Kaltstart und Routing im Plugin anlagen-zu-schriftsaetzen: führt vom ersten Satz oder Dokument in den passenden Arbeitsweg, erkennt Rolle, Ziel, Risiko und Anschluss-Skills. |
| `workflow-output-waehlen` | Output wählen im Plugin anlagen-zu-schriftsaetzen: entscheidet zwischen Memo, Schriftsatz, Tabelle, Brief, Checkliste, Vermerk, Redline oder Mandantenübersetzung. |
| `workflow-rechtsquellen-livecheck` | Rechtsquellen-Livecheck im Plugin anlagen-zu-schriftsaetzen: zwingt vor tragenden Aussagen zum aktuellen Quellencheck bei Gesetzen, Behörden, Gerichten und Formularen. |
| `workflow-redteam-frist-eilversand-schiedsverfahren-anlagenband` | Workflow Redteam Qualitygate, Frist Und Eilversand Anlagenpaket, Schiedsverfahren Anlagenband Und Datentraeger, Spezial Gerichtlichen Fristen Form Und Zustaendigkeit: Workflow Redteam Qualitygate; Frist Und Eilversand Anlagenpaket; Schie... |
| `workflow-unterlagen-lueckenliste` | Unterlagen- und Lückenliste im Plugin anlagen-zu-schriftsaetzen: erstellt eine präzise Nachforderungsliste statt allgemeiner Fragebögen. |
| `zuordnung-zeitleiste-belegkette` | Spezial Zuordnung Erstpruefung Und Mandatsziel, Zeitleiste Und Belegkette: Spezial Zuordnung Erstpruefung Und Mandatsziel; Zeitleiste Und Belegkette. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualität... |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
