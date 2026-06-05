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
| `abteilung-ii-iii-grundschuld-auflassung-eigentumsumschreibung` | Abteilung Ii Dienstbarkeit Vormerkung Beschraenkung, Abteilung Iii Grundschuld Hypothek Rang, Auflassung Und Eigentumsumschreibung: Abteilung Ii Dienstbarkeit Vormerkung Beschraenkung; Abteilung Iii Grundschuld Hypothek Rang; Auflassung... |
| `auslandsurkunden-apostille-baulast-ist-beschwerde-grundbuchsache` | Auslandsurkunden Apostille Grundbuch, Baulast Ist Nicht Grundbuch, Beschwerde Grundbuchsache: Auslandsurkunden Apostille Grundbuch; Baulast Ist Nicht Grundbuch; Beschwerde Grundbuchsache. Führt Intake, Prüfroutine, Normen-/Quellenradar,... |
| `bestandsverzeichnis-flurstueck-briefrecht-abtretung` | Bestandsverzeichnis Flurstueck Und Zuschreibung, Briefrecht Abtretung Und Löschung, Dienstbarkeit Wegerecht Prüfen: Bestandsverzeichnis Flurstueck Und Zuschreibung; Briefrecht Abtretung Und Löschung; Dienstbarkeit Wegerecht Prüfen. Führt... |
| `elektronischer-rechtsverkehr-familiengerichtliche-genehmigung` | Elektronischer Rechtsverkehr Grundbuch, Familiengerichtliche Genehmigung Grundbuch, Finanzierung Und Rangstelle: Elektronischer Rechtsverkehr Grundbuch; Familiengerichtliche Genehmigung Grundbuch; Finanzierung Und Rangstelle. Führt Intak... |
| `gbo-antrag-gbr-egbr-genehmigungen-landwirtschaft` | Gbo Antrag Bewilligung Eintragung, Gbr Egbr Grundbuch, Genehmigungen Landwirtschaft Verkehrswert: Gbo Antrag Bewilligung Eintragung; Gbr Egbr Grundbuch; Genehmigungen Landwirtschaft Verkehrswert. Führt Intake, Prüfroutine, Normen-/Quelle... |
| `grundbuch-qualitygate-vor-vollzug` | Prüft Antrag, Bewilligung, Rang, Nachweise, Anlagen, Genehmigungen, Urkundenform und Zahlungslogik. |
| `grundbuch-vollzugslog-amtswiderspruch-richtigstellung-vs` | Grundbuch Vollzugslog, Grundbuchamt Amtswiderspruch Und Richtigstellung, Grundbuchamt Brief Vs Buchrecht Erklaerung: Grundbuch Vollzugslog; Grundbuchamt Amtswiderspruch Und Richtigstellung; Grundbuchamt Brief Vs Buchrecht Erklaerung. Füh... |
| `grundbuchamt-allgemeiner-kaltstart` | Führt durch Eigentum, Belastungen, Vollzugsziel, Grundbuchbezirk, Urkundentyp, Nachweise, Rang, Fristdruck und Kommunikationsweg mit dem Grundbuchamt. |
| `grundbuchamt-eilfall-rangverlust-erbbaurecht-schnittstelle` | Grundbuchamt Eilfall Rangverlust, Grundbuchamt Erbbaurecht Schnittstelle, Grundbuchamt Flurbereinigung Und Umlegung: Grundbuchamt Eilfall Rangverlust; Grundbuchamt Erbbaurecht Schnittstelle; Grundbuchamt Flurbereinigung Und Umlegung. Füh... |
| `grundbuchamt-gesamtgrundschuld-mithaft-gesellschaftsrechtliche` | Grundbuchamt Gesamtgrundschuld Und Mithaft, Grundbuchamt Gesellschaftsrechtliche Vertretung, Grundbuchamt Insolvenz Auslaendischer Trustee: Grundbuchamt Gesamtgrundschuld Und Mithaft; Grundbuchamt Gesellschaftsrechtliche Vertretung; Grun... |
| `grundbuchamt-kommunikation-konkurrierende-antraege-teilloesung` | Grundbuchamt Kommunikation, Grundbuchamt Konkurrierende Antraege Rangkonflikt, Grundbuchamt Teilloesung Rangfreigabe: Grundbuchamt Kommunikation; Grundbuchamt Konkurrierende Antraege Rangkonflikt; Grundbuchamt Teilloesung Rangfreigabe. F... |
| `grundbuchamt-maengelmatrix-notariat-vollzugsauftrag-abteilung-i` | Grundbuchamt Maengelmatrix, Notariat Vollzugsauftrag Grundbuch, Abteilung I Eigentum Und Erwerbsgrund: Grundbuchamt Maengelmatrix; Notariat Vollzugsauftrag Grundbuch; Abteilung I Eigentum Und Erwerbsgrund. Führt Intake, Prüfroutine, Norm... |
| `grundbuchamt-nichtigkeitsrisiko-kaufvertrags-check-amtshaftung` | Grundbuchamt Nichtigkeitsrisiko Kaufvertrag, Kaufvertrags Check Grundbuch, Amtshaftung Und Vollzugsfehler: Grundbuchamt Nichtigkeitsrisiko Kaufvertrag; Kaufvertrags Check Grundbuch; Amtshaftung Und Vollzugsfehler. Führt Intake, Prüfrouti... |
| `grundbuchauszug-due-lesen-abteilung-grundbuchberichtigung` | Grundbuchauszug Für Due Diligence, Grundbuchauszug Lesen Abteilung I Ii Iii, Grundbuchberichtigung Erbfall: Grundbuchauszug Für Due Diligence; Grundbuchauszug Lesen Abteilung I Ii Iii; Grundbuchberichtigung Erbfall. Führt Intake, Prüfrou... |
| `grunderwerbsteuer-unbedenklichkeitsbescheinigung-grundschuld` | Grunderwerbsteuer Unbedenklichkeitsbescheinigung, Grundschuld Bestellung Buchgrundschuld, Grundschuldbrief Verlust Aufgebot: Grunderwerbsteuer Unbedenklichkeitsbescheinigung; Grundschuld Bestellung Buchgrundschuld; Grundschuldbrief Verlu... |
| `insolvenzvermerk-zwangsversteigerung-kataster-liegenschaftskarte` | Insolvenzvermerk Zwangsversteigerung, Kataster Liegenschaftskarte Abgleich, Leitungsrecht Und Energieanlagen: Insolvenzvermerk Zwangsversteigerung; Kataster Liegenschaftskarte Abgleich; Leitungsrecht Und Energieanlagen. Führt Intake, Prü... |
| `loeschungsbewilligung-bank-nacherbenvermerk` | Loeschungsbewilligung Bank, Nacherbenvermerk Und Verfuegungsbeschraenkung, Niessbrauch Wohnungsrecht: Loeschungsbewilligung Bank; Nacherbenvermerk Und Verfuegungsbeschraenkung; Niessbrauch Wohnungsrecht. Führt Intake, Prüfroutine, Normen... |
| `paragraph-gbo-prioritaetsmitteilung-rangbescheinigung` | Paragraph 29 Gbo Formnachweis, Prioritaetsmitteilung Und Rangbescheinigung, Rangprinzip Und Rangvorbehalt: Paragraph 29 Gbo Formnachweis; Prioritaetsmitteilung Und Rangbescheinigung; Rangprinzip Und Rangvorbehalt. Führt Intake, Prüfrouti... |
| `reallast-erbbauzins-sanierungsvermerk-vorkaufsrechte` | Reallast Und Erbbauzins, Sanierungsvermerk Und Vorkaufsrechte Kommune, Teilflaechenkauf Und Vermessung: Reallast Und Erbbauzins; Sanierungsvermerk Und Vorkaufsrechte Kommune; Teilflaechenkauf Und Vermessung. Führt Intake, Prüfroutine, No... |
| `rechtsprechung-grundbuch-aufgebotsverfahren-famfg` | Rechtsprechung Grundbuch Live Verifizieren, Aufgebotsverfahren Famfg, Auflassungsvormerkung Kaufvertrag: Rechtsprechung Grundbuch Live Verifizieren; Aufgebotsverfahren Famfg; Auflassungsvormerkung Kaufvertrag. Führt Intake, Prüfroutine,... |
| `testamentsvollstrecker-grundbuch-vollmacht-vorsorgevollmacht` | Testamentsvollstrecker Grundbuch, Vollmacht Vorsorgevollmacht Grundbuch, Vorkaufsrecht Wiederkaufsrecht: Testamentsvollstrecker Grundbuch; Vollmacht Vorsorgevollmacht Grundbuch; Vorkaufsrecht Wiederkaufsrecht. Führt Intake, Prüfroutine,... |
| `verlorene-genehmigung-verwalterzustimmung-weg-grundbuchamt` | Grundbuchamt Verlorene Genehmigung Und Ersatznachweis, Grundbuchamt Verwalterzustimmung Weg, Grundbuchamt Vollstreckungsunterwerfung: Grundbuchamt Verlorene Genehmigung Und Ersatznachweis; Grundbuchamt Verwalterzustimmung Weg; Grundbucha... |
| `weg-teilungsgrundbuch-zwischenverfuegung-paragraph` | Weg Teilungsgrundbuch, Zwischenverfuegung Paragraph 18 Gbo: Weg Teilungsgrundbuch; Zwischenverfuegung Paragraph 18 Gbo. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zusammen. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
