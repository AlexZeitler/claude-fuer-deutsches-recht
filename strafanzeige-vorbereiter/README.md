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
| `anzeige-anfangsverdacht-anzeige-anlagenverzeichnis` | Anzeige Anfangsverdacht 152 160 Stpo, Anzeige Anlagenverzeichnis Hashlog: Anzeige Anfangsverdacht 152 160 Stpo; Anzeige Anlagenverzeichnis Hashlog. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätsc... |
| `anzeige-antragsdelikte-anzeige-strafantrag` | Anzeige Antragsdelikte 77B Frist, Anzeige Strafantrag Form Frist: Anzeige Antragsdelikte 77B Frist; Anzeige Strafantrag Form Frist. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zusammen. |
| `anzeige-anwalt-anzeige-arbeitsplatz` | Anzeige Anwalt Einschalten Schwelle, Anzeige Arbeitsplatz Sexuelle Belaestigung: Anzeige Anwalt Einschalten Schwelle; Anzeige Arbeitsplatz Sexuelle Belaestigung. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster... |
| `anzeige-bankrott-anzeige-bedrohung` | Anzeige Bankrott 283, Anzeige Bedrohung 241: Anzeige Bankrott 283; Anzeige Bedrohung 241. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zusammen. |
| `anzeige-beleidigung-anzeige-betrug` | Anzeige Beleidigung 185 194, Anzeige Betrug 263: Anzeige Beleidigung 185 194; Anzeige Betrug 263. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zusammen. |
| `anzeige-beweismatrix-anzeige-chatverlaeufe` | Anzeige Beweismatrix Tatsachen Meinungen, Anzeige Chatverlaeufe Emails Header: Anzeige Beweismatrix Tatsachen Meinungen; Anzeige Chatverlaeufe Emails Header. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und... |
| `anzeige-datenstraftaten-anzeige-diebstahl` | Anzeige Datenstraftaten 202A 303A, Anzeige Diebstahl Unterschlagung: Anzeige Datenstraftaten 202A 303A; Anzeige Diebstahl Unterschlagung. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zusam... |
| `anzeige-druckmittel-anzeige-falsche` | Anzeige Druckmittel Verbot Noetigung, Anzeige Falsche Verdaechtigung 164: Anzeige Druckmittel Verbot Noetigung; Anzeige Falsche Verdaechtigung 164. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätsc... |
| `anzeige-gegenanzeige-anzeige-geldwaesche` | Anzeige Gegenanzeige Risiko, Anzeige Geldwaesche 261: Anzeige Gegenanzeige Risiko; Anzeige Geldwaesche 261. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zusammen. |
| `anzeige-geschgehg-anzeige-haeusliche` | Anzeige Geschgehg 23 Geheimnisverrat, Anzeige Haeusliche Gewalt Gewschg: Anzeige Geschgehg 23 Geheimnisverrat; Anzeige Haeusliche Gewalt Gewschg. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätsche... |
| `anzeige-hausfriedensbruch-anzeige-insolvenzverschleppung` | Anzeige Hausfriedensbruch 123, Anzeige Insolvenzverschleppung 15A: Anzeige Hausfriedensbruch 123; Anzeige Insolvenzverschleppung 15A. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zusammen. |
| `anzeige-international-anzeige-klageerzwingung` | Anzeige International Eu 158 3, Anzeige Klageerzwingung 172 Stpo: Anzeige International Eu 158 3; Anzeige Klageerzwingung 172 Stpo. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zusammen. |
| `anzeige-koerperverletzung-anzeige-korruption` | Anzeige Koerperverletzung 223 230, Anzeige Korruption 299 331Ff: Anzeige Koerperverletzung 223 230; Anzeige Korruption 299 331Ff. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zusammen. |
| `anzeige-kreditgefaehrdung-anzeige-minderjaehrige` | Anzeige Kreditgefaehrdung 824 Bgb, Anzeige Minderjaehrige Schule: Anzeige Kreditgefaehrdung 824 Bgb; Anzeige Minderjaehrige Schule. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zusammen. |
| `anzeige-muster-anzeige-noetigung` | Anzeige Muster Strafanzeige Generator, Anzeige Noetigung 240: Anzeige Muster Strafanzeige Generator; Anzeige Noetigung 240. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zusammen. |
| `anzeige-nicht-anzeigen-redteam` | Red-Team prüft, ob eine Strafanzeige unnötig, riskant, zivilrechtlich kontraproduktiv oder straf-/haftungsrechtlich gefährlich wäre. |
| `anzeige-notruf-anzeige-online` | Anzeige Notruf Akut Gefahr, Anzeige Online Plattform Screenshots: Anzeige Notruf Akut Gefahr; Anzeige Online Plattform Screenshots. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zusammen. |
| `anzeige-onlinewache-anzeige-opferschutz` | Anzeige Onlinewache Vs Staatsanwaltschaft, Anzeige Opferschutz Nebenklage: Anzeige Onlinewache Vs Staatsanwaltschaft; Anzeige Opferschutz Nebenklage. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualität... |
| `anzeige-rechtsfolgen-anzeige-ruecknahme` | Anzeige Rechtsfolgen Und Zivilstrategie, Anzeige Rücknahme Einstellung 170 153: Anzeige Rechtsfolgen Und Zivilstrategie; Anzeige Rücknahme Einstellung 170 153. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster un... |
| `anzeige-sachbeschaedigung-anzeige-sachverhalt` | Anzeige Sachbeschaedigung 303, Anzeige Sachverhalt Ohne Adjektive: Anzeige Sachbeschaedigung 303; Anzeige Sachverhalt Ohne Adjektive. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zusammen. |
| `anzeige-stalking-anzeige-vs` | Anzeige Stalking 238, Anzeige Strafanzeige Vs Strafantrag 158: Anzeige Stalking 238; Anzeige Strafanzeige Vs Strafantrag 158. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zusammen. |
| `anzeige-steuerhinterziehung-anzeige-akteneinsicht` | Anzeige Steuerhinterziehung 370 Ao, Anzeige Akteneinsicht Verletzter 406E: Anzeige Steuerhinterziehung 370 Ao; Anzeige Akteneinsicht Verletzter 406E. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualität... |
| `anzeige-tierschutz-anzeige-ueblerede` | Anzeige Tierschutz 17, Anzeige Ueblerede Verleumdung 186 187: Anzeige Tierschutz 17; Anzeige Ueblerede Verleumdung 186 187. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zusammen. |
| `anzeige-umweltstraftaten-anzeige-unternehmen` | Anzeige Umweltstraftaten 324Ff, Anzeige Unternehmen Internal Investigation: Anzeige Umweltstraftaten 324Ff; Anzeige Unternehmen Internal Investigation. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualit... |
| `anzeige-untreue-anzeige-urheberrecht` | Anzeige Untreue 266, Anzeige Urheberrecht Markenrecht: Anzeige Untreue 266; Anzeige Urheberrecht Markenrecht. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zusammen. |
| `anzeige-verkehrsunfall-anzeige-video` | Anzeige Verkehrsunfall Flucht 142, Anzeige Video Audio Kug 201: Anzeige Verkehrsunfall Flucht 142; Anzeige Video Audio Kug 201. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zusammen. |
| `anzeige-wer-anzeige-zeugenliste` | Anzeige Wer Was Wann Wo Wie, Anzeige Zeugenliste Kontakt: Anzeige Wer Was Wann Wo Wie; Anzeige Zeugenliste Kontakt. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zusammen. |
| `anzeige-whistleblower-anzeige-computerbetrug` | Anzeige Compliance Whistleblower Hinschg, Anzeige Computerbetrug Phishing: Anzeige Compliance Whistleblower Hinschg; Anzeige Computerbetrug Phishing. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualität... |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
