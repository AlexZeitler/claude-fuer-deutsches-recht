# Erbbaurecht Praxis

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`erbbaurecht-praxis`) | [`erbbaurecht-praxis.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/erbbaurecht-praxis.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **Lindenwerder Erbbaurecht - Erbbauzins, Heimfall und Kita-Finanzierung** (`erbbaurecht-erbbauzins-heimfall-lindenwerder-2026`) | [Gesamt-PDF lesen](../testakten/erbbaurecht-erbbauzins-heimfall-lindenwerder-2026/gesamt-pdf/erbbaurecht-erbbauzins-heimfall-lindenwerder-2026_gesamt.pdf) | [`testakte-erbbaurecht-erbbauzins-heimfall-lindenwerder-2026.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-erbbaurecht-erbbauzins-heimfall-lindenwerder-2026.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

Ein Spezialplugin für das Recht des Erbbaurechts: vom ersten Vertragsentwurf über Erbbauzins und Heimfall bis zu Finanzierung, Zustimmung, Versteigerung und Erbbaugrundbuch. Es erklärt die Sache auch für Menschen, die sonst nur Eigentum oder Miete kennen.

## Wofür dieses Plugin da ist

Dieses Plugin ist ein Praxiswerkzeug. Es fragt zuerst die Lage ab, baut dann eine Dokumenten- und Vollzugsmatrix und erzeugt schließlich das konkrete Arbeitsprodukt: Nachreichung, Beanstandungsantwort, Beschwerdegerüst, Mandantenbrief, Checkliste, Fristenlog oder Vertrags-/Urkundenreview. Es ersetzt keine Berufsträgerentscheidung, aber es verhindert, dass ein formeller Nachweis, ein Rang, eine Abteilung-II-Belastung oder eine Registerfolge in der Hektik untergeht.

## Kaltstart

Starte mit dem allgemeinen Skill `erbbaurecht-allgemeiner-kaltstart`. Lade danach möglichst den aktuellen Register- oder Grundbuchauszug, das Gerichtsschreiben, die Anmeldung/Bewilligung, den Vertragsentwurf und vorhandene Anlagen hoch. Das Plugin sortiert erst, dann prüft es.

## Quellen- und Halluzinationsschutz

- Normen werden als Prüfanker verwendet, nicht als Schmuck.
- Rechtsprechung wird nur ausgegeben, wenn Gericht, Datum, Aktenzeichen und ein frei zugänglicher Fundlink geprüft sind.
- Unsichere Register-/Grundbuchstände werden nicht geraten; das Plugin fordert aktuelle Auszüge oder Nachweise an.

## Amtliche Startquellen

- [ErbbauRG](https://www.gesetze-im-internet.de/erbbauv/)
- [GBO](https://www.gesetze-im-internet.de/gbo/)
- [GBV](https://www.gesetze-im-internet.de/gbvfg/)
- [BGB Sachenrecht](https://www.gesetze-im-internet.de/bgb/)
- [FamFG](https://www.gesetze-im-internet.de/famfg/)

## Typische Ergebnisse

- Prüfmatrix und Vollzugsfahrplan
- Entwurf für Nachreichung oder Antwort an das Gericht/Amt
- Mandantenbrief in normalem Deutsch
- Fristen- und Ranglog
- Beschwerde- oder Eilrechtsschutz-Skizze
- Liste fehlender Originale, Nachweise und Formmängel

<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 26 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `ablauf-laufzeitende-erbbaurecht-aktenstruktur` | Erbbaurecht Ablauf Laufzeitende Exitplan, Erbbaurecht Aktenstruktur: Erbbaurecht Ablauf Laufzeitende Exitplan; Erbbaurecht Aktenstruktur. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zusam... |
| `altlasten-rueckbau-erbbaurecht-betreiberwechsel` | Erbbaurecht Altlasten Und Rueckbau, Erbbaurecht Betreiberwechsel: Erbbaurecht Altlasten Und Rueckbau; Erbbaurecht Betreiberwechsel. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zusammen. |
| `change-control-dingliche-vorkaufsrechte` | Erbbaurecht Change Of Control Bei Erbbauberechtigtem, Erbbaurecht Dingliche Vorkaufsrechte: Erbbaurecht Change Of Control Bei Erbbauberechtigtem; Erbbaurecht Dingliche Vorkaufsrechte. Führt Intake, Prüfroutine, Normen-/Quellenradar, Bewe... |
| `erbbau-beschwerde-erbbaugrundbuch-lesen` | Erbbau Beschwerde Grundbuchamt, Erbbaugrundbuch Lesen: Erbbau Beschwerde Grundbuchamt; Erbbaugrundbuch Lesen. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zusammen. |
| `erbbaurecht-allgemeiner-kaltstart` | Führt durch Grundstück, Erbbauberechtigte, Eigentümer, Laufzeit, Bauwerk, Erbbauzins, Heimfall, Finanzierung, Zustimmung und Grundbuchvollzug. |
| `erbbaurecht-photovoltaik-untererbbaurecht-weitergabe` | Erbbaurecht Und Photovoltaik, Erbbaurecht Untererbbaurecht Und Weitergabe: Erbbaurecht Und Photovoltaik; Erbbaurecht Untererbbaurecht Und Weitergabe. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualität... |
| `erbbaurecht-qualitygate-vertrag` | Checkt, ob ein Entwurf investierbar, vollziehbar, finanzierbar und konfliktfest ist. |
| `erbbauzins-struktur-erbbauzinsanpassung-paragraph` | Erbbauzins Struktur Und Reallast, Erbbauzinsanpassung Paragraph 9A: Erbbauzins Struktur Und Reallast; Erbbauzinsanpassung Paragraph 9A. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zusammen. |
| `erbbauzinsrang-finanzierungsbank-erbbaurecht-gewerbepark` | Erbbaurecht Erbbauzinsrang Vor Finanzierungsbank, Erbbaurecht Gewerbepark: Erbbaurecht Erbbauzinsrang Vor Finanzierungsbank; Erbbaurecht Gewerbepark. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualität... |
| `finanzierung-bankfaehigkeit-gemeinde-kirche` | Finanzierung Erbbaurecht Bankfaehigkeit, Gemeinde Kirche Stiftung Als Eigentuemer: Finanzierung Erbbaurecht Bankfaehigkeit; Gemeinde Kirche Stiftung Als Eigentuemer. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmus... |
| `heimfall-gruende-indexklausel-inflation` | Heimfall Gruende Und Verfahren, Erbbaurecht Indexklausel Inflation: Heimfall Gruende Und Verfahren; Erbbaurecht Indexklausel Inflation. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zusammen. |
| `heimfall-verteidigung-insolvenz-erbbauberechtigter` | Heimfall Verteidigung, Insolvenz Erbbauberechtigter: Heimfall Verteidigung; Insolvenz Erbbauberechtigter. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zusammen. |
| `instandhaltung-versicherung-investoren-q` | Erbbaurecht Instandhaltung Versicherung Betriebspflichten, Erbbaurecht Investoren Q And A: Erbbaurecht Instandhaltung Versicherung Betriebspflichten; Erbbaurecht Investoren Q And A. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweis... |
| `kauf-due-kita-sozialimmobilie` | Erbbaurecht Kauf Und Due Diligence, Erbbaurecht Kita Sozialimmobilie: Erbbaurecht Kauf Und Due Diligence; Erbbaurecht Kita Sozialimmobilie. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zus... |
| `kommunale-beschlussvorlage-erbbaurecht-mandantenbrief` | Erbbaurecht Kommunale Beschlussvorlage, Erbbaurecht Mandantenbrief: Erbbaurecht Kommunale Beschlussvorlage; Erbbaurecht Mandantenbrief. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zusammen. |
| `laufzeit-verlaengerung-wohnungs-weg` | Laufzeit Verlaengerung Und Neubestellung, Wohnungs Erbbaurecht Und Weg: Laufzeit Verlaengerung Und Neubestellung; Wohnungs Erbbaurecht Und Weg. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck... |
| `nachhaltigkeit-baupflicht-notar-grundbuchkosten` | Erbbaurecht Nachhaltigkeit Und Baupflicht, Erbbaurecht Notar Und Grundbuchkosten: Erbbaurecht Nachhaltigkeit Und Baupflicht; Erbbaurecht Notar Und Grundbuchkosten. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuste... |
| `nutzungszweckwechsel-wohnen-rangruecktritt-bank` | Erbbaurecht Nutzungszweckwechsel Wohnen Gewerbe Sozial, Erbbaurecht Rangruecktritt Bank: Erbbaurecht Nutzungszweckwechsel Wohnen Gewerbe Sozial; Erbbaurecht Rangruecktritt Bank. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogi... |
| `rechtsprechung-live-erbbaurecht-reminder` | Rechtsprechung Erbbaurecht Live Verifizieren, Erbbaurecht Fristen Und Reminder: Rechtsprechung Erbbaurecht Live Verifizieren; Erbbaurecht Fristen Und Reminder. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster un... |
| `rueckbau-am-schieds-gerichtsstand` | Erbbaurecht Rueckbau Am Laufzeitende, Erbbaurecht Schieds Und Gerichtsstand: Erbbaurecht Rueckbau Am Laufzeitende; Erbbaurecht Schieds Und Gerichtsstand. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qual... |
| `sicherheiten-buergschaft-teilerbbaurecht-aufteilung` | Erbbaurecht Sicherheiten Buergschaft Depot Lastschrift, Erbbaurecht Teilerbbaurecht Und Aufteilung: Erbbaurecht Sicherheiten Buergschaft Depot Lastschrift; Erbbaurecht Teilerbbaurecht Und Aufteilung. Führt Intake, Prüfroutine, Normen-/Qu... |
| `steuern-grunderwerbsteuer-entschaedigung-heimfall` | Erbbaurecht Steuern Und Grunderwerbsteuer, Entschaedigung Bei Heimfall Und Ablauf: Erbbaurecht Steuern Und Grunderwerbsteuer; Entschaedigung Bei Heimfall Und Ablauf. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmus... |
| `verjaehrung-verwirkung-vorlage-zustimmungsantrag` | Erbbaurecht Verjaehrung Verwirkung Duldung, Erbbaurecht Vorlage Zustimmungsantrag: Erbbaurecht Verjaehrung Verwirkung Duldung; Erbbaurecht Vorlage Zustimmungsantrag. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmus... |
| `verkauf-spa-erbbaurechtsvertrag-pflichtinhalt` | Erbbaurecht Verkauf Spa Klauseln, Erbbaurechtsvertrag Pflichtinhalt: Erbbaurecht Verkauf Spa Klauseln; Erbbaurechtsvertrag Pflichtinhalt. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zusam... |
| `vs-eigentum-erbbauzins-rueckstand` | Erbbaurecht Vs Eigentum Vs Miete, Erbbauzins Rueckstand Mahnung: Erbbaurecht Vs Eigentum Vs Miete; Erbbauzins Rueckstand Mahnung. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zusammen. |
| `zustimmung-veraeusserung-zwangsversteigerung-erbbaurecht` | Zustimmung Veraeusserung Belastung, Zwangsversteigerung Erbbaurecht: Zustimmung Veraeusserung Belastung; Zwangsversteigerung Erbbaurecht. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zusam... |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
