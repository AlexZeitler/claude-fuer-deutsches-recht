# Strafanzeige-Vorbereiter

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`strafanzeige-vorbereiter`) | [`strafanzeige-vorbereiter.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/strafanzeige-vorbereiter.zip) |

### Demonstrations-Akten

Dieses Plugin hat derzeit keine eigene Demonstrations-Akte. Es arbeitet mit Sachverhaltsnotizen, Chats, E-Mails, EML-Dateien, Screenshots, Fotos, Videos, Zeugenlisten, Belegen, ärztlichen Unterlagen, Verträgen und vorhandenen Anzeigeentwürfen.

<!-- END plugin-sofort-download-section (autogen) -->

Dieses Plugin ist ausdrücklich keine Strafanzeigenkanone. Es soll Gerichte und Staatsanwaltschaften nicht mit wütenden, unbelegten Anzeigen fluten und niemanden durch haltlose Vorwürfe unter Druck setzen. Wenn eine Strafanzeige aber nötig ist, führt es zu einem sauberen, nüchternen, beweisnahen Entwurf.

## Leitplanke

Wehe, es werden Dinge behauptet, die nicht stimmen. Das Plugin zwingt zur Trennung von eigener Wahrnehmung, Dokument, Zeuge, Vermutung und rechtlicher Bewertung. Bei eigener Beteiligung, Unternehmensfällen, schweren Gewalt-/Sexualdelikten, Wirtschaftsstrafsachen oder Berufsgeheimnissen: anwaltliche Hilfe einschalten.

## Was dieses Plugin gut kann

- Trennt Strafanzeige, Strafantrag, zivilrechtliche Alternativen und bloße Beschwerde.
- Prüft vorab § 164 StGB, §§ 186/187 StGB, § 824 BGB und Druckmittelrisiken.
- Baut Sachverhalt, Beweismatrix, Anlagenverzeichnis und Strafantragsfristen auf.
- Erzeugt erst am Ende einen Anzeigeentwurf, wenn die Tatsachenbasis trägt.

## Startlogik

Beginne mit dem allgemeinen Kaltstart-Skill. Er fragt Rolle, Ziel, Frist, Unterlagen, Risiken und gewünschten Output ab. Danach werden nur passende Spezial-Skills vorgeschlagen.

## Quellenhygiene

Normtexte werden aus amtlichen Quellen geprüft. Rechtsprechung wird nur mit Gericht, Datum, Aktenzeichen und frei zugänglicher Quelle verwendet. Keine BeckRS-, juris-, Kommentar- oder Aufsatz-Blindzitate.

<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 29 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `anzeige-allgemeiner-kaltstart` | Geführter Einstieg für Strafanzeigen: Sachverhalt, Beweise, Straftatverdacht, Strafantrag, Risiken falscher Verdächtigung, Alternativen und anwaltliche Eskalationsschwelle. |
| `anzeige-nicht-anzeigen-redteam` | Red-Team prüft, ob eine Strafanzeige unnötig, riskant, zivilrechtlich kontraproduktiv oder straf-/haftungsrechtlich gefährlich wäre. |
| `kompendium-01-anzeige-antragsdelik-bis-anzeige-strafantrag` | strafanzeige-vorbereiter: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Anzeige Antragsdelikte 77b Frist, Anzeige Strafantrag Form Frist; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualität... |
| `kompendium-02-anzeige-steuerhinter-bis-anzeige-akteneinsich` | strafanzeige-vorbereiter: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Anzeige Steuerhinterziehung 370 Ao, Anzeige Akteneinsicht Verletzter 406e; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und... |
| `kompendium-03-anzeige-anfangsverda-bis-anzeige-anlagenverze` | strafanzeige-vorbereiter: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Anzeige Anfangsverdacht 152 160 Stpo, Anzeige Anlagenverzeichnis Hashlog; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und... |
| `kompendium-04-anzeige-anwalt-einsc-bis-anzeige-arbeitsplatz` | strafanzeige-vorbereiter: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Anzeige Anwalt Einschalten Schwelle, Anzeige Arbeitsplatz Sexuelle Belaestigung; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmust... |
| `kompendium-05-anzeige-bankrott-283-bis-anzeige-bedrohung-24` | strafanzeige-vorbereiter: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Anzeige Bankrott 283, Anzeige Bedrohung 241; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck. |
| `kompendium-06-anzeige-beleidigung-bis-anzeige-betrug-263` | strafanzeige-vorbereiter: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Anzeige Beleidigung 185 194, Anzeige Betrug 263; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck. |
| `kompendium-07-anzeige-beweismatrix-bis-anzeige-chatverlaeuf` | strafanzeige-vorbereiter: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Anzeige Beweismatrix Tatsachen Meinungen, Anzeige Chatverlaeufe Emails Header; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster... |
| `kompendium-08-anzeige-compliance-w-bis-anzeige-computerbetr` | strafanzeige-vorbereiter: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Anzeige Compliance Whistleblower Hinschg, Anzeige Computerbetrug Phishing; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und... |
| `kompendium-09-anzeige-datenstrafta-bis-anzeige-diebstahl-un` | strafanzeige-vorbereiter: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Anzeige Datenstraftaten 202a 303a, Anzeige Diebstahl Unterschlagung; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Quali... |
| `kompendium-10-anzeige-druckmittel-bis-anzeige-falsche-verd` | strafanzeige-vorbereiter: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Anzeige Druckmittel Verbot Noetigung, Anzeige Falsche Verdaechtigung 164; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und... |
| `kompendium-11-anzeige-gegenanzeige-bis-anzeige-geldwaesche` | strafanzeige-vorbereiter: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Anzeige Gegenanzeige Risiko, Anzeige Geldwaesche 261; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck. |
| `kompendium-12-anzeige-geschgehg-23-bis-anzeige-haeusliche-g` | strafanzeige-vorbereiter: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Anzeige Geschgehg 23 Geheimnisverrat, Anzeige Haeusliche Gewalt Gewschg; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Q... |
| `kompendium-13-anzeige-hausfriedens-bis-anzeige-insolvenzver` | strafanzeige-vorbereiter: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Anzeige Hausfriedensbruch 123, Anzeige Insolvenzverschleppung 15a; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitä... |
| `kompendium-14-anzeige-internationa-bis-anzeige-klageerzwing` | strafanzeige-vorbereiter: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Anzeige International Eu 158 3, Anzeige Klageerzwingung 172 Stpo; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualität... |
| `kompendium-15-anzeige-koerperverle-bis-anzeige-korruption-2` | strafanzeige-vorbereiter: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Anzeige Koerperverletzung 223 230, Anzeige Korruption 299 331ff; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitäts... |
| `kompendium-16-anzeige-kreditgefaeh-bis-anzeige-minderjaehri` | strafanzeige-vorbereiter: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Anzeige Kreditgefaehrdung 824 Bgb, Anzeige Minderjaehrige Schule; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualität... |
| `kompendium-17-anzeige-muster-straf-bis-anzeige-noetigung-24` | strafanzeige-vorbereiter: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Anzeige Muster Strafanzeige Generator, Anzeige Noetigung 240; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck. |
| `kompendium-18-anzeige-notruf-akut-bis-anzeige-online-platt` | strafanzeige-vorbereiter: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Anzeige Notruf Akut Gefahr, Anzeige Online Plattform Screenshots; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualität... |
| `kompendium-19-anzeige-onlinewache-bis-anzeige-opferschutz` | strafanzeige-vorbereiter: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Anzeige Onlinewache Vs Staatsanwaltschaft, Anzeige Opferschutz Nebenklage; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und... |
| `kompendium-20-anzeige-rechtsfolgen-bis-anzeige-ruecknahme-e` | strafanzeige-vorbereiter: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Anzeige Rechtsfolgen Und Zivilstrategie, Anzeige Ruecknahme Einstellung 170 153; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmust... |
| `kompendium-21-anzeige-sachbeschaed-bis-anzeige-sachverhalt` | strafanzeige-vorbereiter: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Anzeige Sachbeschaedigung 303, Anzeige Sachverhalt Ohne Adjektive; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitä... |
| `kompendium-22-anzeige-stalking-238-bis-anzeige-strafanzeige` | strafanzeige-vorbereiter: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Anzeige Stalking 238, Anzeige Strafanzeige Vs Strafantrag 158; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätsch... |
| `kompendium-23-anzeige-tierschutz-1-bis-anzeige-ueblerede-ve` | strafanzeige-vorbereiter: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Anzeige Tierschutz 17, Anzeige Ueblerede Verleumdung 186 187; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck. |
| `kompendium-24-anzeige-umweltstraft-bis-anzeige-unternehmen` | strafanzeige-vorbereiter: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Anzeige Umweltstraftaten 324ff, Anzeige Unternehmen Internal Investigation; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster un... |
| `kompendium-25-anzeige-untreue-266-bis-anzeige-urheberrecht` | strafanzeige-vorbereiter: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Anzeige Untreue 266, Anzeige Urheberrecht Markenrecht; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck. |
| `kompendium-26-anzeige-verkehrsunfa-bis-anzeige-video-audio` | strafanzeige-vorbereiter: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Anzeige Verkehrsunfall Flucht 142, Anzeige Video Audio Kug 201; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätsc... |
| `kompendium-27-anzeige-wer-was-wann-bis-anzeige-zeugenliste` | strafanzeige-vorbereiter: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Anzeige Wer Was Wann Wo Wie, Anzeige Zeugenliste Kontakt; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
