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
| `erbbaurecht-allgemeiner-kaltstart` | Führt durch Grundstück, Erbbauberechtigte, Eigentümer, Laufzeit, Bauwerk, Erbbauzins, Heimfall, Finanzierung, Zustimmung und Grundbuchvollzug. |
| `erbbaurecht-qualitygate-vertrag` | Checkt, ob ein Entwurf investierbar, vollziehbar, finanzierbar und konfliktfest ist. |
| `kompendium-01-rechtsprechung-erbba-bis-erbbaurecht-fristen` | erbbaurecht-praxis: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Rechtsprechung Erbbaurecht Live Verifizieren, Erbbaurecht Fristen Und Reminder; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und... |
| `kompendium-02-heimfall-gruende-und-bis-erbbaurecht-indexkla` | erbbaurecht-praxis: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Heimfall Gruende Und Verfahren, Erbbaurecht Indexklausel Inflation; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck. |
| `kompendium-03-erbbaurecht-verkauf-bis-erbbaurechtsvertrag` | erbbaurecht-praxis: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Erbbaurecht Verkauf Spa Klauseln, Erbbaurechtsvertrag Pflichtinhalt; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätsch... |
| `kompendium-04-erbbaurecht-steuern-bis-entschaedigung-bei-h` | erbbaurecht-praxis: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Erbbaurecht Steuern Und Grunderwerbsteuer, Entschaedigung Bei Heimfall Und Ablauf; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster u... |
| `kompendium-05-erbbau-beschwerde-gr-bis-erbbaugrundbuch-lese` | erbbaurecht-praxis: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Erbbau Beschwerde Grundbuchamt, Erbbaugrundbuch Lesen; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck. |
| `kompendium-06-erbbaurecht-ablauf-l-bis-erbbaurecht-aktenstr` | erbbaurecht-praxis: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Erbbaurecht Ablauf Laufzeitende Exitplan, Erbbaurecht Aktenstruktur; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätsch... |
| `kompendium-07-erbbaurecht-altlaste-bis-erbbaurecht-betreibe` | erbbaurecht-praxis: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Erbbaurecht Altlasten Und Rueckbau, Erbbaurecht Betreiberwechsel; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck. |
| `kompendium-08-erbbaurecht-change-o-bis-erbbaurecht-dinglich` | erbbaurecht-praxis: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Erbbaurecht Change Of Control Bei Erbbauberechtigtem, Erbbaurecht Dingliche Vorkaufsrechte; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outpu... |
| `kompendium-09-erbbaurecht-erbbauzi-bis-erbbaurecht-gewerbep` | erbbaurecht-praxis: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Erbbaurecht Erbbauzinsrang Vor Finanzierungsbank, Erbbaurecht Gewerbepark; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Quali... |
| `kompendium-10-erbbaurecht-instandh-bis-erbbaurecht-investor` | erbbaurecht-praxis: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Erbbaurecht Instandhaltung Versicherung Betriebspflichten, Erbbaurecht Investoren Q And A; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Output... |
| `kompendium-11-erbbaurecht-kauf-und-bis-erbbaurecht-kita-soz` | erbbaurecht-praxis: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Erbbaurecht Kauf Und Due Diligence, Erbbaurecht Kita Sozialimmobilie; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätsc... |
| `kompendium-12-erbbaurecht-kommunal-bis-erbbaurecht-mandante` | erbbaurecht-praxis: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Erbbaurecht Kommunale Beschlussvorlage, Erbbaurecht Mandantenbrief; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck. |
| `kompendium-13-erbbaurecht-nachhalt-bis-erbbaurecht-notar-un` | erbbaurecht-praxis: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Erbbaurecht Nachhaltigkeit Und Baupflicht, Erbbaurecht Notar Und Grundbuchkosten; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster un... |
| `kompendium-14-erbbaurecht-nutzungs-bis-erbbaurecht-rangruec` | erbbaurecht-praxis: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Erbbaurecht Nutzungszweckwechsel Wohnen Gewerbe Sozial, Erbbaurecht Rangruecktritt Bank; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmu... |
| `kompendium-15-erbbaurecht-rueckbau-bis-erbbaurecht-schieds` | erbbaurecht-praxis: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Erbbaurecht Rueckbau Am Laufzeitende, Erbbaurecht Schieds Und Gerichtsstand; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qua... |
| `kompendium-16-erbbaurecht-sicherhe-bis-erbbaurecht-teilerbb` | erbbaurecht-praxis: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Erbbaurecht Sicherheiten Buergschaft Depot Lastschrift, Erbbaurecht Teilerbbaurecht Und Aufteilung; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogi... |
| `kompendium-17-erbbaurecht-und-phot-bis-erbbaurecht-untererb` | erbbaurecht-praxis: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Erbbaurecht Und Photovoltaik, Erbbaurecht Untererbbaurecht Und Weitergabe; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Quali... |
| `kompendium-18-erbbaurecht-verjaehr-bis-erbbaurecht-vorlage` | erbbaurecht-praxis: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Erbbaurecht Verjaehrung Verwirkung Duldung, Erbbaurecht Vorlage Zustimmungsantrag; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster u... |
| `kompendium-19-erbbaurecht-vs-eigen-bis-erbbauzins-rueckstan` | erbbaurecht-praxis: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Erbbaurecht Vs Eigentum Vs Miete, Erbbauzins Rueckstand Mahnung; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck. |
| `kompendium-20-erbbauzins-struktur-bis-erbbauzinsanpassung` | erbbaurecht-praxis: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Erbbauzins Struktur Und Reallast, Erbbauzinsanpassung Paragraph 9a; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck. |
| `kompendium-21-finanzierung-erbbaur-bis-gemeinde-kirche-stif` | erbbaurecht-praxis: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Finanzierung Erbbaurecht Bankfaehigkeit, Gemeinde Kirche Stiftung Als Eigentuemer; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster u... |
| `kompendium-22-heimfall-verteidigun-bis-insolvenz-erbbaubere` | erbbaurecht-praxis: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Heimfall Verteidigung, Insolvenz Erbbauberechtigter; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck. |
| `kompendium-23-laufzeit-verlaengeru-bis-wohnungs-erbbaurecht` | erbbaurecht-praxis: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Laufzeit Verlaengerung Und Neubestellung, Wohnungs Erbbaurecht Und Weg; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualität... |
| `kompendium-24-zustimmung-veraeusse-bis-zwangsversteigerung` | erbbaurecht-praxis: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Zustimmung Veraeusserung Belastung, Zwangsversteigerung Erbbaurecht; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätsch... |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
