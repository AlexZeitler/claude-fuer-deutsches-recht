# Grundbuchamt Praxis

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`grundbuchamt-praxis`) | [`grundbuchamt-praxis.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/grundbuchamt-praxis.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **Haus Altenau - verlorener Grundschuldbrief, Wegerecht und Kaufpreisfälligkeit** (`grundbuchamt-briefgrundschuld-wegerecht-altenau-2026`) | [Gesamt-PDF lesen](../testakten/grundbuchamt-briefgrundschuld-wegerecht-altenau-2026/gesamt-pdf/grundbuchamt-briefgrundschuld-wegerecht-altenau-2026_gesamt.pdf) | [`testakte-grundbuchamt-briefgrundschuld-wegerecht-altenau-2026.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-grundbuchamt-briefgrundschuld-wegerecht-altenau-2026.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

Ein Grundbuch-Cockpit für alle, die Auszüge lesen, Urkunden grundbuchtauglich nachweisen, Zwischenverfügungen verstehen und Grundbuchvollzug sauber betreiben müssen. Schwerpunkt ist die praktische Leseführung durch Abteilung I, II und III, damit keine Dienstbarkeit, Vormerkung, Rangstelle oder Briefgrundschuld übersehen wird.

## Wofür dieses Plugin da ist

Dieses Plugin ist ein Praxiswerkzeug. Es fragt zuerst die Lage ab, baut dann eine Dokumenten- und Vollzugsmatrix und erzeugt schließlich das konkrete Arbeitsprodukt: Nachreichung, Beanstandungsantwort, Beschwerdegerüst, Mandantenbrief, Checkliste, Fristenlog oder Vertrags-/Urkundenreview. Es ersetzt keine Berufsträgerentscheidung, aber es verhindert, dass ein formeller Nachweis, ein Rang, eine Abteilung-II-Belastung oder eine Registerfolge in der Hektik untergeht.

## Kaltstart

Starte mit dem allgemeinen Skill `grundbuchamt-allgemeiner-kaltstart`. Lade danach möglichst den aktuellen Register- oder Grundbuchauszug, das Gerichtsschreiben, die Anmeldung/Bewilligung, den Vertragsentwurf und vorhandene Anlagen hoch. Das Plugin sortiert erst, dann prüft es.

## Quellen- und Halluzinationsschutz

- Normen werden als Prüfanker verwendet, nicht als Schmuck.
- Rechtsprechung wird nur ausgegeben, wenn Gericht, Datum, Aktenzeichen und ein frei zugänglicher Fundlink geprüft sind.
- Unsichere Register-/Grundbuchstände werden nicht geraten; das Plugin fordert aktuelle Auszüge oder Nachweise an.

## Amtliche Startquellen

- [GBO](https://www.gesetze-im-internet.de/gbo/)
- [GBV](https://www.gesetze-im-internet.de/gbvfg/)
- [FamFG Aufgebotsverfahren](https://www.gesetze-im-internet.de/famfg/)
- [BGB Grundstücksrechte](https://www.gesetze-im-internet.de/bgb/)
- [Justizportal des Bundes und der Länder](https://justiz.de/)

## Typische Ergebnisse

- Prüfmatrix und Vollzugsfahrplan
- Entwurf für Nachreichung oder Antwort an das Gericht/Amt
- Mandantenbrief in normalem Deutsch
- Fristen- und Ranglog
- Beschwerde- oder Eilrechtsschutz-Skizze
- Liste fehlender Originale, Nachweise und Formmängel

<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 23 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `grundbuch-qualitygate-vor-vollzug` | Prüft Antrag, Bewilligung, Rang, Nachweise, Anlagen, Genehmigungen, Urkundenform und Zahlungslogik. |
| `grundbuchamt-allgemeiner-kaltstart` | Führt durch Eigentum, Belastungen, Vollzugsziel, Grundbuchbezirk, Urkundentyp, Nachweise, Rang, Fristdruck und Kommunikationsweg mit dem Grundbuchamt. |
| `kompendium-01-rechtsprechung-grund-bis-auflassungsvormerkun` | grundbuchamt-praxis: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Rechtsprechung Grundbuch Live Verifizieren, Aufgebotsverfahren Famfg, Auflassungsvormerkung Kaufvertrag; mit Intake, Prüfroutine, Normen-/Quellenradar, Bewe... |
| `kompendium-02-grundbuchamt-nichtig-bis-amtshaftung-und-voll` | grundbuchamt-praxis: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Grundbuchamt Nichtigkeitsrisiko Kaufvertrag, Kaufvertrags Check Grundbuch, Amtshaftung Und Vollzugsfehler; mit Intake, Prüfroutine, Normen-/Quellenradar, Be... |
| `kompendium-03-grundbuchamt-maengel-bis-abteilung-i-eigentum` | grundbuchamt-praxis: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Grundbuchamt Maengelmatrix, Notariat Vollzugsauftrag Grundbuch, Abteilung I Eigentum Und Erwerbsgrund; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweis... |
| `kompendium-04-abteilung-ii-dienstb-bis-auflassung-und-eigen` | grundbuchamt-praxis: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Abteilung Ii Dienstbarkeit Vormerkung Beschraenkung, Abteilung Iii Grundschuld Hypothek Rang, Auflassung Und Eigentumsumschreibung; mit Intake, Prüfroutine,... |
| `kompendium-05-auslandsurkunden-apo-bis-beschwerde-grundbuch` | grundbuchamt-praxis: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Auslandsurkunden Apostille Grundbuch, Baulast Ist Nicht Grundbuch, Beschwerde Grundbuchsache; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Ou... |
| `kompendium-06-bestandsverzeichnis-bis-dienstbarkeit-wegere` | grundbuchamt-praxis: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Bestandsverzeichnis Flurstueck Und Zuschreibung, Briefrecht Abtretung Und Loeschung, Dienstbarkeit Wegerecht Pruefen; mit Intake, Prüfroutine, Normen-/Quell... |
| `kompendium-07-elektronischer-recht-bis-finanzierung-und-ran` | grundbuchamt-praxis: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Elektronischer Rechtsverkehr Grundbuch, Familiengerichtliche Genehmigung Grundbuch, Finanzierung Und Rangstelle; mit Intake, Prüfroutine, Normen-/Quellenrad... |
| `kompendium-08-gbo-antrag-bewilligu-bis-genehmigungen-landwi` | grundbuchamt-praxis: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Gbo Antrag Bewilligung Eintragung, Gbr Egbr Grundbuch, Genehmigungen Landwirtschaft Verkehrswert; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik... |
| `kompendium-09-grundbuch-vollzugslo-bis-grundbuchamt-brief-v` | grundbuchamt-praxis: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Grundbuch Vollzugslog, Grundbuchamt Amtswiderspruch Und Richtigstellung, Grundbuchamt Brief Vs Buchrecht Erklaerung; mit Intake, Prüfroutine, Normen-/Quelle... |
| `kompendium-10-grundbuchamt-eilfall-bis-grundbuchamt-flurber` | grundbuchamt-praxis: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Grundbuchamt Eilfall Rangverlust, Grundbuchamt Erbbaurecht Schnittstelle, Grundbuchamt Flurbereinigung Und Umlegung; mit Intake, Prüfroutine, Normen-/Quelle... |
| `kompendium-11-grundbuchamt-gesamtg-bis-grundbuchamt-insolve` | grundbuchamt-praxis: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Grundbuchamt Gesamtgrundschuld Und Mithaft, Grundbuchamt Gesellschaftsrechtliche Vertretung, Grundbuchamt Insolvenz Auslaendischer Trustee; mit Intake, Prüf... |
| `kompendium-12-grundbuchamt-kommuni-bis-grundbuchamt-teilloe` | grundbuchamt-praxis: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Grundbuchamt Kommunikation, Grundbuchamt Konkurrierende Antraege Rangkonflikt, Grundbuchamt Teilloesung Rangfreigabe; mit Intake, Prüfroutine, Normen-/Quell... |
| `kompendium-13-grundbuchamt-verlore-bis-grundbuchamt-vollstr` | grundbuchamt-praxis: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Grundbuchamt Verlorene Genehmigung Und Ersatznachweis, Grundbuchamt Verwalterzustimmung Weg, Grundbuchamt Vollstreckungsunterwerfung; mit Intake, Prüfroutin... |
| `kompendium-14-grundbuchauszug-fuer-bis-grundbuchberichtigun` | grundbuchamt-praxis: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Grundbuchauszug Fuer Due Diligence, Grundbuchauszug Lesen Abteilung I Ii Iii, Grundbuchberichtigung Erbfall; mit Intake, Prüfroutine, Normen-/Quellenradar,... |
| `kompendium-15-grunderwerbsteuer-un-bis-grundschuldbrief-ver` | grundbuchamt-praxis: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Grunderwerbsteuer Unbedenklichkeitsbescheinigung, Grundschuld Bestellung Buchgrundschuld, Grundschuldbrief Verlust Aufgebot; mit Intake, Prüfroutine, Normen... |
| `kompendium-16-insolvenzvermerk-zwa-bis-leitungsrecht-und-en` | grundbuchamt-praxis: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Insolvenzvermerk Zwangsversteigerung, Kataster Liegenschaftskarte Abgleich, Leitungsrecht Und Energieanlagen; mit Intake, Prüfroutine, Normen-/Quellenradar,... |
| `kompendium-17-loeschungsbewilligun-bis-niessbrauch-wohnungs` | grundbuchamt-praxis: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Loeschungsbewilligung Bank, Nacherbenvermerk Und Verfuegungsbeschraenkung, Niessbrauch Wohnungsrecht; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweisl... |
| `kompendium-18-paragraph-29-gbo-for-bis-rangprinzip-und-rang` | grundbuchamt-praxis: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Paragraph 29 Gbo Formnachweis, Prioritaetsmitteilung Und Rangbescheinigung, Rangprinzip Und Rangvorbehalt; mit Intake, Prüfroutine, Normen-/Quellenradar, Be... |
| `kompendium-19-reallast-und-erbbauz-bis-teilflaechenkauf-und` | grundbuchamt-praxis: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Reallast Und Erbbauzins, Sanierungsvermerk Und Vorkaufsrechte Kommune, Teilflaechenkauf Und Vermessung; mit Intake, Prüfroutine, Normen-/Quellenradar, Bewei... |
| `kompendium-20-testamentsvollstreck-bis-vorkaufsrecht-wieder` | grundbuchamt-praxis: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Testamentsvollstrecker Grundbuch, Vollmacht Vorsorgevollmacht Grundbuch, Vorkaufsrecht Wiederkaufsrecht; mit Intake, Prüfroutine, Normen-/Quellenradar, Bewe... |
| `kompendium-21-weg-teilungsgrundbuc-bis-zwischenverfuegung-p` | grundbuchamt-praxis: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Weg Teilungsgrundbuch, Zwischenverfuegung Paragraph 18 Gbo; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
