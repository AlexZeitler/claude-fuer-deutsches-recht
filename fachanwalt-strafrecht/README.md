# Fachanwalt Strafrecht

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`fachanwalt-strafrecht`) | [`fachanwalt-strafrecht.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/fachanwalt-strafrecht.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **BtM-Akte** (`betaeubungsmittelrecht-apotheke-substitution-festival`) | [Gesamt-PDF lesen](../testakten/betaeubungsmittelrecht-apotheke-substitution-festival/gesamt-pdf/betaeubungsmittelrecht-apotheke-substitution-festival_gesamt.pdf) | [`testakte-betaeubungsmittelrecht-apotheke-substitution-festival.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-betaeubungsmittelrecht-apotheke-substitution-festival.zip) |
| **Grossbankrott und Zeugenstreit — Mehrere Deliktszweige, Pellbach Logistik & Spedition GmbH, LG Koeln** (`grossbankrott-und-zeugenstreit-mehrere-deliktszweige-vellbruck-koeln`) | [Gesamt-PDF lesen](../testakten/grossbankrott-und-zeugenstreit-mehrere-deliktszweige-vellbruck-koeln/gesamt-pdf/grossbankrott-und-zeugenstreit-mehrere-deliktszweige-vellbruck-koeln_gesamt.pdf) | [`testakte-grossbankrott-und-zeugenstreit-mehrere-deliktszweige-vellbruck-koeln.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-grossbankrott-und-zeugenstreit-mehrere-deliktszweige-vellbruck-koeln.zip) |
| **Wirtschaftsstrafsache Bankert — U-Haft, Betrug, Steuerhinterziehung, LG Frankfurt** (`wirtschaftsstrafsache-uhaft-bankert-frankfurt`) | [Gesamt-PDF lesen](../testakten/wirtschaftsstrafsache-uhaft-bankert-frankfurt/gesamt-pdf/wirtschaftsstrafsache-uhaft-bankert-frankfurt_gesamt.pdf) | [`testakte-wirtschaftsstrafsache-uhaft-bankert-frankfurt.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-wirtschaftsstrafsache-uhaft-bankert-frankfurt.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

## Was dieses Plugin im Strafprozess leistet

Dieses Plugin ist als Arbeitscockpit für Strafverteidigung gedacht: nicht nur für die große Strategie, sondern für die täglichen Schritte einer laufenden Strafakte. Es ordnet Eingänge, markiert Fristen, baut Aktenlog und Wiedervorlagen, steuert Akteneinsicht, U-Haft, Pflichtverteidigung, Hauptverhandlung, Antragslog, Mandanteninstruktionen, Rechtsmittel und Vollstreckungsnachlauf.

Der Kaltstart soll sofort praktisch werden: Was ist heute gefährlich, welche Frist läuft, welcher Schriftsatz oder Anruf muss raus, welche Aktenbestandteile fehlen, was darf der Mandant keinesfalls ohne Rücksprache tun? Danach schlägt das Plugin die passenden Strafprozess-Skills aus diesem Plugin vor und hält das Ergebnis als Checkliste, Matrix, Memo, Mandantenbrief oder Schriftsatzbaustein fest.

Neu aufgenommen ist ein vertiefter Prüfpfad für digitale Ermittlungsmaßnahmen: biometrischer Internetabgleich, KI-gestützte Trefferlisten, verfahrensübergreifende Analyseplattformen, Akteneinsicht in technische Protokolle, Löschung, Benachrichtigung, KI-VO-Konformität und Verwertungsangriffe. Der Skill behandelt solche Maßnahmen ausdrücklich als rechtsstandsabhängig: Entwurf, Inkrafttreten und aktueller Wortlaut sind vor jeder tragenden Aussage live zu prüfen.

Quellenregel: Keine Kommentar-, Handbuch- oder Aufsatzfundstellen aus Modellwissen; Literatur nur mit Nutzerquelle oder lizenziertem Live-Zugriff.

## Installation in Claude Code

1. ZIP herunterladen (Link oben).
2. Claude Code → **Customize Plugins** → **Install from .zip** → Datei wählen.
3. Fertig. Skills sind sofort verfügbar.

> **Hinweis:** Für den ZIP-Upload muss das Archiv direkt `.claude-plugin/plugin.json`, `skills/`, `assets/` und `references/` im ZIP-Root enthalten. **Nicht** das komplette Repository-ZIP aus "Code → Download ZIP" verwenden.

## Enthaltene Skills

| Skill | Zweck |
| --- | --- |
| `strafprozess-cockpit-taegliche-kanzleifuehrung` | Laufendes Verteidigungs-Cockpit mit Verfahrensstand, Fristen, Haftlage, Akteneinsicht, offenen Anträgen, Terminen und nächstem Schritt. |
| `strafprozess-aktenlog-fristen-und-wiedervorlagen` | Macht aus beA-/EGVP-Eingängen, Beschlüssen, Ladungen, Strafbefehlen, Urteilen und Nachlieferungen ein belastbares Fristen- und Aufgabenlog. |
| `strafprozess-haft-und-besuchsmanagement` | Organisiert U-Haft, Haftprüfung, Haftbeschwerde, Haftverschonung, Akteneinsicht, Besuch, Telefon, Familie, Arbeitgeber und Beschleunigungskontrolle. |
| `strafprozess-hv-tagesmappe-und-sitzungsplan` | Baut für jeden Sitzungstag eine Hauptverhandlungs-Tagesmappe mit Zeugenprogramm, Fragelisten, Einlassungsfenster, Antragsentwürfen und Nachbereitung. |
| `strafprozess-sitzungsprotokoll-und-revisionssicherung` | Sichert Protokollierung, Anträge, Belehrungen, Verständigung, letztes Wort und mögliche Revisionsrügen während und nach der Hauptverhandlung. |
| `fachanwalt-strafrecht-orientierung` | Orientierung im Strafrecht — FAO-Voraussetzungen Normen typische Mandate Notfristen Quellenprüfung. Plugin für schnelle Verortung. Strafverteidigung im Ermittlungsverfahren (Akteneinsicht § 147 StPO) H… |

## Lizenz

Apache-2.0 OR MIT — Auswahl beim Empfänger.


<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 37 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `aussagepsychologie-staatsanwaltschaft-aussagepsychologie` | Strafrecht Spezial Aussagepsychologie Staatsanwaltschaft Replik, Strafrecht Spezial Aussagepsychologie Vernehmungslehre Praxis, Strafrecht Spezial Aussetzung 221 Stgb, Strafrecht Spezial Bandenbetrug 263 Stgb, Strafrecht Spezial Bankrott... |
| `chatcontrol-csam-einlassung-vorbereiten-hauptverhandlung` | Fachanwalt Strafrecht Chatcontrol Csam Anwaltsgeheimnis 53 Stpo, Fachanwalt Strafrecht Einlassung Vorbereiten, Fachanwalt Strafrecht Hauptverhandlung Vorbereiten, Fachanwalt Strafrecht Insolvenzantrag Staatsanwaltschaft, Fachanwalt Straf... |
| `ergaenzt-fachanwalt-insolvenzantrag-red-kanzlei-sonderfall` | Spezial Ergaenzt Mandantenkommunikation Entscheidungsvorlage, Spezial Fachanwalt Erstpruefung Und Mandatsziel, Spezial Insolvenzantrag Red Team Und Qualitaetskontrolle, Spezial Kanzlei Sonderfall Und Edge Case, Spezial Livecheck Abschlus... |
| `fachanwalt-strafrecht-orientierung-untersuchungshaft` | Fachanwalt Strafrecht Orientierung, Fachanwalt Strafrecht Untersuchungshaft Haftpruefung, Fachanwalt Strafrecht Verstaendigung 257C Toa 46A, Fachanwalt Strafrecht Wahlverteidiger Mandat, Fachanwalt Strafrecht Zeugenbeistand: Fachanwalt S... |
| `koerperverletzung-stgb-koerperverletzung-todesfolge` | Strafrecht Spezial Koerperverletzung 223 Stgb Grund, Strafrecht Spezial Koerperverletzung Mit Todesfolge 227 Stgb, Strafrecht Spezial Konkursrechtliche Anfechtungsbezuege, Strafrecht Spezial Kreditbetrug 265B Stgb, Strafrecht Spezial Kri... |
| `mandat-triage-plaedoyer-vorbereitung-schriftsatzkern` | Mandat Triage Strafrecht, Plaedoyer Vorbereitung Strafverteidigung, Schriftsatzkern Substantiierung, Spezial Adhaesion Formular Portal Und Einreichung, Spezial Aktenaufbereiter Beweislast Und Darlegungslast: Mandat Triage Strafrecht; Pla... |
| `nebenklage-nebenstrafrecht-opfervertretung-interessen-revision` | Spezial Nebenklage Compliance Dokumentation Und Akte, Spezial Nebenstrafrecht Behörden Gericht Und Registerweg, Spezial Opfervertretung Mehrparteien Konflikt Und Interessen, Spezial Revision Zahlen Schwellen Und Berechnung, Spezial Stgb... |
| `raub-stgb-raub-todesfolge-rechtsbeugung-stgb` | Strafrecht Spezial Raub 249 Stgb, Strafrecht Spezial Raub Mit Todesfolge 251 Stgb, Strafrecht Spezial Rechtsbeugung 339 Stgb, Strafrecht Spezial Schuldnerbeguenstigung 283D Stgb, Strafrecht Spezial Schwere Koerperverletzung 226 Stgb und... |
| `spezial-hauptverhandlung-livequellen-und-rechtsprechungscheck` | Hauptverhandlung: Livequellen- und Rechtsprechungscheck im Plugin fachanwalt strafrecht; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Standardprüfung. |
| `spezial-rechtsquellen-fristennotiz-und-naechster-schritt` | Rechtsquellen: Fristennotiz und nächster Schritt im Plugin fachanwalt strafrecht; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Standardprüfung. |
| `steuerstrafrecht-ao-akteneinsicht-auswerten-erstgespraech` | Strafrecht Spezial Steuerstrafrecht 371 Ao Selbstanzeige, Akteneinsicht Strafrecht Auswerten, Erstgespraech Mandatsannahme, Fachanwalt Strafrecht Akteneinsicht Beantragen, Fachanwalt Strafrecht Anklage Reaktion: Strafrecht Spezial Steuer... |
| `stpo-strafrecht-strafverteidigung-zeugenbeistand-strafprozess` | Spezial Stpo Dokumentenmatrix Und Lueckenliste, Spezial Strafrecht Tatbestand Beweis Und Belege, Spezial Strafverteidigung Schriftsatz Brief Und Memo Bausteine, Spezial Zeugenbeistand Internationaler Bezug Und Schnittstellen, Strafprozes... |
| `strafprozess-antragslog-beweisantraege-biometrischer-cockpit` | Strafprozess Antragslog Beweisantraege Und Widerspruch, Strafprozess Biometrischer Internetabgleich 98D Stpo E, Strafprozess Cockpit Taegliche Kanzleifuehrung, Strafprozess Haft Und Besuchsmanagement, Strafprozess Hv Tagesmappe Und Sitzu... |
| `strafprozess-instruktionen-pflichtverteidigung-beiordnung-strafr` | Strafprozess Mandantenkommunikation Und Instruktionen, Strafprozess Pflichtverteidigung Beiordnung Und Wechsel, Strafprozess Sitzungsprotokoll Und Revisionssicherung, Strafprozess Verhandlungslog Sta Gericht Nebenklage, Strafr Dysfunk An... |
| `strafr-dysfunk-befangenheitsantrag-beistandsleistung-stpo` | Strafr Dysfunk Befangenheitsantrag Zielgenau, Strafr Dysfunk Beistandsleistung 137 Stpo, Strafr Dysfunk Beweisantrag Fundament, Strafr Dysfunk Beweisantragsstrategie, Strafr Dysfunk Contempt Of Court Debatte 177A: Strafr Dysfunk Befangen... |
| `strafr-dysfunk-darlegungslast-empirie-nutzen-erklaerungsrecht` | Strafr Dysfunk Darlegungslast Umkehren, Strafr Dysfunk Empirie Nutzen, Strafr Dysfunk Erklaerungsrecht 257 Stpo, Strafr Dysfunk Hinweis Auf Heilbaren Fehler, Strafr Dysfunk Institutsmissbrauch Kritik und 5 weitere Themen: Strafr Dysfunk... |
| `strafr-dysfunk-sitzungspolizei-verschleppungsabsicht-abgrenzen` | Strafr Dysfunk Sitzungspolizei Ordnungsmittel, Strafr Dysfunk Verschleppungsabsicht Abgrenzen, Strafr Dysfunk Vorwurf Einordnen, Strafr Dysfunk Wahlverteidigerausschluss 138A, Strafr Revision Prüfung Spezial: Strafr Dysfunk Sitzungspoliz... |
| `strafr-vermoegensabschoepfung-strafr-wirtschaftsstrafrecht` | Strafr Vermoegensabschoepfung Spezial, Strafr Wirtschaftsstrafrecht Leitfaden, Strafrecht Polizeifilmerei 201 Stgb Kug Verteidigung, Strafrecht Spezial 188 Stgb Anklage Und Strafbefehl, Strafrecht Spezial 188 Stgb Art5 Schrift Und Hv: St... |
| `strafrecht-aussagepsy-suggestion-tuechtigkeit-bereitschaft` | Strafrecht Spezial Aussagepsy Suggestion Falscherinnerung, Strafrecht Spezial Aussagepsy Tuechtigkeit Bereitschaft, Strafrecht Spezial Aussagepsy Vernehmungsfehler Falschgestand, Strafrecht Spezial Aussagepsychologie Bgh Grundsaetze, Str... |
| `strafrecht-betrug-stgb-btmg-grundtatbestand-29a-nicht-30a` | Strafrecht Spezial Betrug 263 Stgb Grundtatbestand, Strafrecht Spezial Btmg 29 Grundtatbestand, Strafrecht Spezial Btmg 29A Nicht Geringe Menge, Strafrecht Spezial Btmg 30 Handeltreiben, Strafrecht Spezial Btmg 30A Schwerer Bandenhandel... |
| `strafrecht-computerbetrug-263a-design-designg-erpresserischer` | Strafrecht Spezial Computerbetrug 263A Stgb, Strafrecht Spezial Design Strafrecht 51 Designg, Strafrecht Spezial Erpresserischer Menschenraub 239A 239B Stgb, Strafrecht Spezial Faktische Geschaeftsfuehrer, Strafrecht Spezial Falschbeurku... |
| `strafrecht-gmbh-verletzung-insiderhandel-wphg-ip-verteidigung` | Strafrecht Spezial Gmbh Verletzung Anzeigepflicht 84 Gmbhg, Strafrecht Spezial Insiderhandel 119 Wphg, Strafrecht Spezial Insolvenzverschleppung 15A Inso, Strafrecht Spezial Ip Strafrecht Grenzbeschlagnahme, Strafrecht Spezial Ip Strafre... |
| `strafrecht-markenrecht-143a-marktmanipulation-wphg-mietwucher` | Strafrecht Spezial Markenrecht 143A Markeng Bandenmaessig, Strafrecht Spezial Marktmanipulation 120 Wphg, Strafrecht Spezial Mietwucher 5 Wistg, Strafrecht Spezial Minder Schwerer Fall 213 Stgb, Strafrecht Spezial Misshandlung Schutzbefo... |
| `strafrecht-stgb-easy-social-media-amtsdelikte-koerperverletzung` | Strafrecht Spezial 188 Stgb Easy Verteidigung, Strafrecht Spezial 188 Stgb Social Media Beweise, Strafrecht Spezial Amtsdelikte 340 Stgb Koerperverletzung Im Amt, Strafrecht Spezial Amtstraegerbestechung 332 334 Stgb, Strafrecht Spezial... |
| `strafrecht-strafprozess-ermittlungsverfahren-rechtsmittel-btmg` | Strafprozess Ermittlungsverfahren Sofortmassnahmen, Strafprozess Rechtsmittel Und Notfristencockpit, Strafrecht Spezial Btmg Strafverfahren Praxis, Strafrecht Spezial Haeusliche Gewalt Im Strafverfahren, Strafrecht Spezial Markenrecht 14... |
| `strafrecht-untreue-schaden-verbandssanktionengesetz-stand-370a` | Strafrecht Spezial Untreue Schaden Und Bezifferbarkeit, Strafrecht Spezial Verbandssanktionengesetz Stand 2026, Strafprozess Akteneinsicht Nachlieferungen Und Sonderbaende, Strafrecht Spezial Steuerstrafrecht 370 Ao Steuerhinterziehung,... |
| `strafrecht-urheberrecht-urhg-108a-gewerblich-108b-tpm-verletzung` | Strafrecht Spezial Urheberrecht 108 Urhg Unerlaubte Eingriffe, Strafrecht Spezial Urheberrecht 108A Urhg Gewerblich, Strafrecht Spezial Urheberrecht 108B Urhg Tpm, Strafrecht Spezial Vergewaltigung 177 Stgb, Strafrecht Spezial Verkehrsst... |
| `subventionsbetrug-stgb-toetung-verlangen-totschlag-stgb` | Strafrecht Spezial Subventionsbetrug 264 Stgb, Strafrecht Spezial Toetung Auf Verlangen 216 Stgb, Strafrecht Spezial Totschlag 212 Stgb, Strafrecht Spezial Umweltstrafrecht 324 Stgb Gewaesser, Strafrecht Spezial Umweltstrafrecht 326 Stgb... |
| `versicherungsbetrug-stgb-vorenthalten-arbeitgeberanteile` | Strafrecht Spezial Versicherungsbetrug 265 Stgb, Strafrecht Spezial Vorenthalten Arbeitgeberanteile 266A Stgb, Strafrecht Spezial Vorteilsannahme Gewaehrung 331 333 Stgb, Strafrecht Spezial Waffg Strafvorschriften 51 52, Strafrecht Spezi... |
| `workflow-allgemein-strafr-haftpruefung-chronologie-belegmatrix` | Allgemein, Strafr Haftpruefung Haftbeschwerde Workflow, Workflow Chronologie Und Belegmatrix, Workflow Fristen Und Risikoampel, Workflow Mandantenkommunikation: Allgemein; Strafr Haftpruefung Haftbeschwerde Workflow; Workflow Chronologie... |
| `workflow-anschluss-skills-router` | Anschluss-Skills Router im Plugin fachanwalt-strafrecht: schlägt nach der ersten Prüfung die passenden Spezialskills aus demselben Plugin vor. |
| `workflow-dokumentenintake` | Dokumentenintake im Plugin fachanwalt-strafrecht: liest Uploads, sortiert Dokumentarten, markiert Fristen, erkennt U-Haft-, Akteneinsichts-, Rechtsmittel- und Hauptverhandlungsrisiken und baut eine knappe Arbeitsakte mit Anschluss-Skills. |
| `workflow-kaltstart-und-routing` | Kaltstart und Routing im Plugin fachanwalt-strafrecht: führt vom ersten Satz oder Dokument in den passenden Arbeitsweg, erkennt Rolle, Ziel, Risiko und Anschluss-Skills. |
| `workflow-output-waehlen` | Output wählen im Plugin fachanwalt-strafrecht: entscheidet zwischen Memo, Schriftsatz, Tabelle, Brief, Checkliste, Vermerk, Redline oder Mandantenübersetzung. |
| `workflow-rechtsquellen-livecheck` | Rechtsquellen-Livecheck im Plugin fachanwalt-strafrecht: zwingt vor tragenden Aussagen zum aktuellen Quellencheck bei Gesetzen, Behörden, Gerichten und Formularen. |
| `workflow-redteam-adhaesionsverfahren-ermittlungsverfahren` | Workflow Redteam Qualitygate, Fachanwalt Strafrecht Adhaesionsverfahren, Spezial Ermittlungsverfahren Vergleich Eskalation, Spezial Orientierung Fristen Form Und Zustaendigkeit, Strafprozess Aktenlog Fristen Und Wiedervorlagen: Workflow... |
| `workflow-unterlagen-lueckenliste` | Unterlagen- und Lückenliste im Plugin fachanwalt-strafrecht: erstellt eine präzise Nachforderungsliste statt allgemeiner Fragebögen. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
