# Versicherungsrecht

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`versicherungsrecht`) | [`versicherungsrecht.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/versicherungsrecht.zip) |

### Demonstrations-Akten

Dieses Plugin hat derzeit keine eigene Demonstrations-Akte. Es arbeitet mit hochgeladenen Policen, Bescheiden, Verträgen, Messprotokollen, Behördenbriefen und Aktenauszügen.

<!-- END plugin-sofort-download-section (autogen) -->

Großes, praxisnahes Versicherungsrecht-Plugin für Deckung, Ablehnung, Vertragsgestaltung, Aufsicht und Prozess. Es ist bewusst nicht nur ein Fachanwalts-Lernplugin, sondern ein Arbeitswerkzeug für Kanzlei, Rechtsabteilung, Versicherungsnehmer, Vermittler und Versicherer.

## Was dieses Plugin gut kann

- Deckungsablehnungen und Leistungsprüfung nach VVG zerlegen.
- Lebensversicherung, BU, PKV, Unfall, Rechtsschutz, Kreditversicherung, D&O, Cyber und Sachversicherung mit eigenen Spezial-Skills prüfen.
- BaFin, Ombudsmann, Klage und Vergleich taktisch voneinander trennen.
- Europäische Aufsicht, IDD, Solvency II, DORA und grenzüberschreitenden Vertrieb einordnen.

## Startlogik

Beginne mit dem allgemeinen Skill. Er fragt Rolle, Ziel, Fristen, Unterlagen, Eskalationsniveau und gewünschten Output ab. Danach schlägt er nur die Spezial-Skills vor, die zum Fall passen.

## Quellenhygiene

Normtexte werden aus amtlichen Quellen geprüft. Rechtsprechung wird nur mit Gericht, Datum, Aktenzeichen und frei prüfbarer Quelle verwendet. Keine BeckRS-, juris-, Kommentar- oder Aufsatz-Blindzitate.

## Installation in Claude Code

1. ZIP herunterladen (Link oben).
2. Claude Code → **Customize Plugins** → **Install from .zip** → Datei wählen.
3. Fertig. Skills sind sofort verfügbar.

> **Hinweis:** Für den ZIP-Upload muss das Archiv direkt `.claude-plugin/plugin.json`, `skills/`, `assets/` und `references/` im ZIP-Root enthalten. Nicht das komplette Repository-ZIP aus "Code → Download ZIP" verwenden.

<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 24 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `kompendium-01-deckungsprozess-zust-bis-sachverstaendigenver` | versicherungsrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Deckungsprozess Zustaendigkeit 215 Vvg, Rechtsschutzversicherung Im Massenverfahren, Sachverstaendigenverfahren Versicherung; mit Intake, Prüfroutine, Normen... |
| `kompendium-02-unfallversicherung-i-bis-rechtsschutz-vorvert` | versicherungsrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Unfallversicherung Invaliditaet Fristen Gliedertaxe, Vers Fristen Verjaehrung Klagefrist Fallkalender, Rechtsschutz Vorvertraglichkeit Schadenereignis; mit I... |
| `kompendium-03-versicherungsprodukt-bis-betriebsunterbrechun` | versicherungsrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Versicherungsprodukt Agb Klauselkontrolle, Betriebshaftpflicht Versicherungsfall Serienschaden, Betriebsunterbrechung Sachschaden Trigger; mit Intake, Prüfro... |
| `kompendium-04-cyberversicherung-ra-bis-elementarschaden-sta` | versicherungsrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Cyberversicherung Ransomware Sanktionsrecht, D O Claims Made Innenhaftung 43 Gmbhg, Elementarschaden Starkregen Ueberschwemmung; mit Intake, Prüfroutine, Nor... |
| `kompendium-05-rechtsabteilung-d-o-bis-versicherungsmakler` | versicherungsrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu D O Deckung Bei Organhaftung, Umwelthaftpflicht Umweltschadenversicherung, Versicherungsmakler Haftung Deckungsluecke; mit Intake, Prüfroutine, Normen-/Quell... |
| `kompendium-06-dora-cyber-ikt-versi-bis-bu-abstrakte-konkret` | versicherungsrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Dora Cyber Ikt Versicherer, Vergleich Abfindung Entschaedigungsquittung, Bu Abstrakte Konkrete Verweisung; mit Intake, Prüfroutine, Normen-/Quellenradar, Bew... |
| `kompendium-07-bu-berufsbild-50-pro-bis-datenschutz-schweige` | versicherungsrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Bu Berufsbild 50 Prozent Substantiierung, Bu Nachpruefung Anerkenntnis Leistungseinstellung, Datenschutz Schweigepflicht Gesundheitsdaten; mit Intake, Prüfro... |
| `kompendium-08-direktanspruch-pflic-bis-gewerbe-betriebsschl` | versicherungsrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Direktanspruch Pflichtversicherung 115 Vvg, Eiopa Grenzueberschreitender Vertrieb, Gewerbe Betriebsschliessung Infektionsschutz; mit Intake, Prüfroutine, Nor... |
| `kompendium-09-hausrat-einbruchdieb-bis-internationales-vers` | versicherungsrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Hausrat Einbruchdiebstahl Entschaedigungsgrenze, Idd Vertrieb Beratung Dokumentation, Internationales Versicherungsprogramm Master Local Policy; mit Intake,... |
| `kompendium-10-kfz-haftpflicht-regr-bis-krankentagegeld-beru` | versicherungsrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Kfz Haftpflicht Regress Alkohol Flucht, Kfz Kasko Grobe Fahrlaessigkeit Entwendung, Krankentagegeld Berufsunfaehigkeit Abgrenzung; mit Intake, Prüfroutine, N... |
| `kompendium-11-kreditausfallversich-bis-lebensversicherung-b` | versicherungsrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Kreditausfallversicherung Warenkredit Forderungsausfall, Kreditversicherung Obliegenheiten Limit Pruefung, Lebensversicherung Bezugsrecht Widerruf Aenderung;... |
| `kompendium-12-lebensversicherung-r-bis-nachhaltigkeit-taxon` | versicherungsrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Lebensversicherung Rueckkaufswert Abschlusskosten Widerspruch, Lebensversicherung Ueberschussbeteiligung Bewertungsreserven, Nachhaltigkeit Taxonomie Sfdr Ve... |
| `kompendium-13-pkv-kostenerstattung-bis-produkthaftpflicht-r` | versicherungsrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Pkv Kostenerstattung Medizinische Notwendigkeit, Private Krankenversicherung Beitragsanpassung Treuhaender, Produkthaftpflicht Rueckrufkosten; mit Intake, Pr... |
| `kompendium-14-rechtsabteilung-betr-bis-rechtsabteilung-idd` | versicherungsrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Betriebsunterbrechung Und Lieferkettenausfall, Cyberversicherung Nach Ransomware, Idd Vertrieb Und Provisionskonflikt; mit Intake, Prüfroutine, Normen-/Quell... |
| `kompendium-15-rechtsschutz-deckung-bis-reiseversicherung-ru` | versicherungsrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Rechtsschutz Deckungszusage Stichentscheid, Rechtsschutz Erfolgsaussicht Mutwilligkeit, Reiseversicherung Ruecktritt Abbruch Krankheit; mit Intake, Prüfrouti... |
| `kompendium-16-restschuldversicheru-bis-solvency-ii-scr-orsa` | versicherungsrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Restschuldversicherung Widerruf Kopplung Verbraucherdarlehen, Rueckversicherung Cut Through Und Fronting, Solvency Ii Scr Orsa Aufsichtsrecht; mit Intake, Pr... |
| `kompendium-17-subrogation-regress-bis-vag-bafin-aufsicht-b` | versicherungsrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Subrogation Regress 86 Vvg, Transportversicherung Ware Lagerung, Vag Bafin Aufsicht Beschwerde Missstand; mit Intake, Prüfroutine, Normen-/Quellenradar, Bewe... |
| `kompendium-18-vers-ombudsmann-bafi-bis-versicherungssumme-u` | versicherungsrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Vers Ombudsmann Bafin Beschwerde Klageweg, Versicherungsbetrug Verdachtsfall Kooperation Strafrecht, Versicherungssumme Unterversicherung Taxwert; mit Intake... |
| `kompendium-19-vvg-anzeigepflicht-1-bis-vvg-falligkeit-14-ab` | versicherungsrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Vvg Anzeigepflicht 19 Ruecktritt Kuendigung Anpassung, Vvg Arglist Taeuschung Anfechtung, Vvg Falligkeit 14 Abschlagszahlung; mit Intake, Prüfroutine, Normen... |
| `kompendium-20-vvg-gefahrerhoehung-bis-vvg-obliegenheit-28` | versicherungsrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Vvg Gefahrerhoehung 23 27, Vvg Mehrfachversicherung 78, Vvg Obliegenheit 28 Quotelung Kausalitaet; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik... |
| `kompendium-21-vvg-versicherung-fue-bis-wohngebaeude-leitung` | versicherungsrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Vvg Versicherung Fuer Fremde 43 48, Wohngebaeude Leitungswasser Sturm Hagel Brand; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster u... |
| `vers-allgemeiner-kaltstart` | Allgemeiner Einstieg ins Versicherungsrecht: Police, Bedingungen, Schadenereignis, Ablehnung, Fristen, Aufsicht, Ombudsmann und Klageweg strukturiert erfassen und passende Spezial-Skills vorschlagen. |
| `vers-deckungsablehnung-redteam` | Deckungsablehnung des Versicherers zerlegen: Risikoausschluss, Obliegenheit, Kausalität, grobe Fahrlässigkeit, Arglist, Beweislast und Vergleichsfenster systematisch prüfen. |
| `vers-dokumentenintake-police-avb-nachtraege` | Dokumentenintake für Versicherungsakten: Versicherungsschein, AVB, Nachträge, Beratungsdokumentation, Schadenanzeige, Gutachten, Korrespondenz und Ablehnung in eine Aktenmatrix überführen. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
