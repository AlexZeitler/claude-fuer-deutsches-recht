# Handelsregister Praxis

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`handelsregister-praxis`) | [`handelsregister-praxis.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/handelsregister-praxis.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **Rabenhof Sensorik GmbH - Registergericht Charlottenburg, HRB 246810 B** (`handelsregister-registergericht-rabenhof-gmbh-2026`) | [Gesamt-PDF lesen](../testakten/handelsregister-registergericht-rabenhof-gmbh-2026/gesamt-pdf/handelsregister-registergericht-rabenhof-gmbh-2026_gesamt.pdf) | [`testakte-handelsregister-registergericht-rabenhof-gmbh-2026.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-handelsregister-registergericht-rabenhof-gmbh-2026.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

Ein Registergerichts-Cockpit für Gesellschaftsrechtler, Notariate, Kanzleien und Rechtsabteilungen. Es ordnet, was eingetragen werden soll, welche Urkunden nötig sind, wer beim Registergericht entscheidet, wie man Beanstandungen beantwortet und wann Beschwerde oder Eilrechtsschutz Sinn ergeben.

## Wofür dieses Plugin da ist

Dieses Plugin ist ein Praxiswerkzeug. Es fragt zuerst die Lage ab, baut dann eine Dokumenten- und Vollzugsmatrix und erzeugt schließlich das konkrete Arbeitsprodukt: Nachreichung, Beanstandungsantwort, Beschwerdegerüst, Mandantenbrief, Checkliste, Fristenlog oder Vertrags-/Urkundenreview. Es ersetzt keine Berufsträgerentscheidung, aber es verhindert, dass ein formeller Nachweis, ein Rang, eine Abteilung-II-Belastung oder eine Registerfolge in der Hektik untergeht.

## Kaltstart

Starte mit dem allgemeinen Skill `handelsregister-allgemeiner-kaltstart`. Lade danach möglichst den aktuellen Register- oder Grundbuchauszug, das Gerichtsschreiben, die Anmeldung/Bewilligung, den Vertragsentwurf und vorhandene Anlagen hoch. Das Plugin sortiert erst, dann prüft es.

## Quellen- und Halluzinationsschutz

- Normen werden als Prüfanker verwendet, nicht als Schmuck.
- Rechtsprechung wird nur ausgegeben, wenn Gericht, Datum, Aktenzeichen und ein frei zugänglicher Fundlink geprüft sind.
- Unsichere Register-/Grundbuchstände werden nicht geraten; das Plugin fordert aktuelle Auszüge oder Nachweise an.

## Amtliche Startquellen

- [HGB §§ 8 ff., § 15](https://www.gesetze-im-internet.de/hgb/)
- [FamFG Registersachen und Beschwerde](https://www.gesetze-im-internet.de/famfg/)
- [GmbHG Anmeldung, Gesellschafterliste, Kapitalmaßnahmen](https://www.gesetze-im-internet.de/gmbhg/)
- [Registerportal der Länder](https://www.handelsregister.de/)
- [Unternehmensregister](https://www.unternehmensregister.de/)

## Typische Ergebnisse

- Prüfmatrix und Vollzugsfahrplan
- Entwurf für Nachreichung oder Antwort an das Gericht/Amt
- Mandantenbrief in normalem Deutsch
- Fristen- und Ranglog
- Beschwerde- oder Eilrechtsschutz-Skizze
- Liste fehlender Originale, Nachweise und Formmängel

<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 27 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `beanstandung-zwischenverfuegung-bekanntmachungen-monitoring` | Beanstandung Zwischenverfuegung Antwort, Bekanntmachungen Monitoring, Chronologischer Registerauszug: Beanstandung Zwischenverfuegung Antwort; Bekanntmachungen Monitoring; Chronologischer Registerauszug. Führt Intake, Prüfroutine, Normen... |
| `closing-handelregister-einstweiliger-rechtsschutz-eintragung` | Closing Handelregister Vollzug, Einstweiliger Rechtsschutz Registerstreit, Eintragung Prozessvergleich Registerfolge: Closing Handelregister Vollzug; Einstweiliger Rechtsschutz Registerstreit; Eintragung Prozessvergleich Registerfolge. F... |
| `erlaubnispflichtige-taetigkeit-famfg-beschwerde-fehlerhafte` | Erlaubnispflichtige Taetigkeit Register, Famfg Beschwerde Registersache, Fehlerhafte Eintragung Berichtigung: Erlaubnispflichtige Taetigkeit Register; Famfg Beschwerde Registersache; Fehlerhafte Eintragung Berichtigung. Führt Intake, Prü... |
| `firma-firmenbildung-formwechsel-registercheck-genossenschaft` | Firma Firmenbildung Und Irrefuehrung, Formwechsel Registercheck, Genossenschaft Registerschnittstelle: Firma Firmenbildung Und Irrefuehrung; Formwechsel Registercheck; Genossenschaft Registerschnittstelle. Führt Intake, Prüfroutine, Norm... |
| `gesellschafterlistenstreit-eilstrategie-gmbh-co-gmbh` | Gesellschafterlistenstreit Eilstrategie, Gmbh Co Kg Registerdoppelvollzug, Gmbh Geschaeftsfuehrerbestellung Abberufung: Gesellschafterlistenstreit Eilstrategie; Gmbh Co Kg Registerdoppelvollzug; Gmbh Geschaeftsfuehrerbestellung Abberufun... |
| `gmbh-gesellschafterliste-paragraph-gruendung-erstanmeldung` | Gmbh Gesellschafterliste Paragraph 40, Gmbh Gruendung Erstanmeldung, Gmbh Kapitalerhoehung Bareinlage: Gmbh Gesellschafterliste Paragraph 40; Gmbh Gruendung Erstanmeldung; Gmbh Kapitalerhoehung Bareinlage. Führt Intake, Prüfroutine, Norm... |
| `gmbh-kapitalerhoehung-sacheinlage-kapitalherabsetzung-schutzjahr` | Gmbh Kapitalerhoehung Sacheinlage, Gmbh Kapitalherabsetzung Und Schutzjahr, Gmbh Liquidation Und Löschung: Gmbh Kapitalerhoehung Sacheinlage; Gmbh Kapitalherabsetzung Und Schutzjahr; Gmbh Liquidation Und Löschung. Führt Intake, Prüfrouti... |
| `gmbh-satzungsaenderung-handelsvollmacht-nicht-hgb-publizitaet` | Gmbh Satzungsaenderung Und Neufassung, Handelsvollmacht Nicht Eintragungsfaehig, Hgb Publizitaet Paragraph 15: Gmbh Satzungsaenderung Und Neufassung; Handelsvollmacht Nicht Eintragungsfaehig; Hgb Publizitaet Paragraph 15. Führt Intake, P... |
| `handelsregister-allgemeiner-kaltstart` | Führt durch das erste Registerproblem: Wer meldet was an, welche Gesellschaft, welches Registerblatt, welches Ziel, welcher Fristdruck, welche Urkunden, welche Entscheidungsperson und welches Eskalationsniveau. |
| `insolvenzvermerk-registereintrag-registervergleich-kg` | Insolvenzvermerk Und Registereintrag, Internationaler Registervergleich, Kg Kommanditist Eintritt Austritt Haftsumme: Insolvenzvermerk Und Registereintrag; Internationaler Registervergleich; Kg Kommanditist Eintritt Austritt Haftsumme. F... |
| `ki-registerakte-nachlass-testamentsvollstrecker-notar` | Ki Registerakte Halluzinationsschutz, Nachlass Und Testamentsvollstrecker Register, Notar Registergericht Kommunikation: Ki Registerakte Halluzinationsschutz; Nachlass Und Testamentsvollstrecker Register; Notar Registergericht Kommunikat... |
| `ohg-kg-online-abruf-partg-partgmbb` | Ohg Kg Egbr Mopeg Statuswechsel, Online Abruf Registerportal Unternehmensregister, Partg Partgmbb Register: Ohg Kg Egbr Mopeg Statuswechsel; Online Abruf Registerportal Unternehmensregister; Partg Partgmbb Register. Führt Intake, Prüfrou... |
| `prokura-eintragung-rechtsabteilung-geschaeftsfuehrerbestellung` | Prokura Eintragung Und Widerruf, Rechtsabteilung Geschaeftsfuehrerbestellung Mit Auslandsbezug, Rechtsabteilung Gesellschafterliste Nach Streit Und Ev: Prokura Eintragung Und Widerruf; Rechtsabteilung Geschaeftsfuehrerbestellung Mit Ausl... |
| `rechtsabteilung-insolvenzvermerk-rechtsabteilung` | Rechtsabteilung Insolvenzvermerk Und Auslaendischer Trustee, Rechtsabteilung Kapitalerhoehung Und Zwischenverfuegung, Rechtsabteilung Mopeg Gesellschaftsregister Und Ohg Sprung: Rechtsabteilung Insolvenzvermerk Und Auslaendischer Trustee... |
| `rechtsprechung-register-frist-vollzugslog-registerrecht` | Rechtsprechung Register Live Verifizieren, Frist Und Vollzugslog Register, Registerrecht Mandatsannahme Notarferne: Rechtsprechung Register Live Verifizieren; Frist Und Vollzugslog Register; Registerrecht Mandatsannahme Notarferne. Führt... |
| `rechtsschein-innenstreit-register-mandantenbrief-register` | Rechtsschein Und Innenstreit, Register Mandantenbrief, Register Qualitaetsgate Vor Einreichung: Rechtsschein Und Innenstreit; Register Mandantenbrief; Register Qualitaetsgate Vor Einreichung. Führt Intake, Prüfroutine, Normen-/Quellenrad... |
| `registerakte-schnellscan-registerauszug-lesen-registerbeweis` | Registerakte Schnellscan Und Vollzugskarte, Registerauszug Lesen, Registerbeweis Im Prozess: Registerakte Schnellscan Und Vollzugskarte; Registerauszug Lesen; Registerbeweis Im Prozess. Führt Intake, Prüfroutine, Normen-/Quellenradar, Be... |
| `registergericht-rollen-registergericht-datenschutz` | Registergericht Rollen Rechtspfleger Registerrichter, Registergericht Und Datenschutz, Registerkosten Und Notarkosten: Registergericht Rollen Rechtspfleger Registerrichter; Registergericht Und Datenschutz; Registerkosten Und Notarkosten.... |
| `registerrecht-aktiengesellschaft-vorstand-beschlussmaengel` | Registerrecht Aktiengesellschaft Vorstand Aufsichtsrat, Registerrecht Beschlussmaengel Und Registervollzug, Registerrecht Digitalgruendung: Registerrecht Aktiengesellschaft Vorstand Aufsichtsrat; Registerrecht Beschlussmaengel Und Regist... |
| `registerrecht-fehlende-einzahlung-fehlerhafte` | Registerrecht Fehlende Einzahlung, Registerrecht Fehlerhafte Geschaeftsfuehreradresse, Registerrecht Kapitalgesellschaft Co Kg Komplementaerwechsel: Registerrecht Fehlende Einzahlung; Registerrecht Fehlerhafte Geschaeftsfuehreradresse; R... |
| `registerrecht-niederlassung-registerrecht-registergericht` | Registerrecht Niederlassung Filiale, Registerrecht Registergericht Telefonat Protokoll, Registerrecht Registerzeichen Und Aktenzeichen: Registerrecht Niederlassung Filiale; Registerrecht Registergericht Telefonat Protokoll; Registerrecht... |
| `registerrecht-scheinloeschung-nachtragsliquidation-se` | Registerrecht Scheinloeschung Und Nachtragsliquidation, Registerrecht Se Und Europaeische Gesellschaft, Registerrecht Umbenennung Rebranding: Registerrecht Scheinloeschung Und Nachtragsliquidation; Registerrecht Se Und Europaeische Gesel... |
| `registersperre-closing-sitz-inlandsanschrift-todesfall` | Registersperre Und Closing Risiko, Sitz Inlandsanschrift Und Geschaeftsanschrift, Todesfall Gesellschafter Register: Registersperre Und Closing Risiko; Sitz Inlandsanschrift Und Geschaeftsanschrift; Todesfall Gesellschafter Register. Füh... |
| `transparenzregister-schnittstelle-umwandlung-registervollzug` | Transparenzregister Schnittstelle, Umwandlung Registervollzug, Unternehmensgegenstand Beanstandung: Transparenzregister Schnittstelle; Umwandlung Registervollzug; Unternehmensgegenstand Beanstandung. Führt Intake, Prüfroutine, Normen-/Qu... |
| `umzug-registerbezirk-amtsloeschung-familienloeschung` | Umzug Registerbezirk, Amtsloeschung Familienloeschung Registerblatt, Auslandsurkunden Apostille Legalisation Uebersetzung: Umzug Registerbezirk; Amtsloeschung Familienloeschung Registerblatt; Auslandsurkunden Apostille Legalisation Ueber... |
| `verein-registerschnittstelle-verschmelzung-gmbh-vollmacht` | Verein Registerschnittstelle, Verschmelzung Gmbh Registercheck, Vollmacht Und Anmeldung Oeffentliche Beglaubigung: Verein Registerschnittstelle; Verschmelzung Gmbh Registercheck; Vollmacht Und Anmeldung Oeffentliche Beglaubigung. Führt I... |
| `zweigniederlassung-auslaendische` | Zweigniederlassung Auslaendische Gesellschaft: Zweigniederlassung Auslaendische Gesellschaft. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zusammen. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
