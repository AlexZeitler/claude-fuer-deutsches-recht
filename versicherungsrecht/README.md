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
| `bu-berufsbild-bu-nachpruefung-datenschutz-schweigepflicht` | Bu Berufsbild 50 Prozent Substantiierung, Bu Nachpruefung Anerkenntnis Leistungseinstellung, Datenschutz Schweigepflicht Gesundheitsdaten: Bu Berufsbild 50 Prozent Substantiierung; Bu Nachpruefung Anerkenntnis Leistungseinstellung; Daten... |
| `cyberversicherung-ransomware-d-o-elementarschaden-starkregen` | Cyberversicherung Ransomware Sanktionsrecht, D O Claims Made Innenhaftung 43 Gmbhg, Elementarschaden Starkregen Ueberschwemmung: Cyberversicherung Ransomware Sanktionsrecht; D O Claims Made Innenhaftung 43 Gmbhg; Elementarschaden Starkre... |
| `deckungsprozess-vvg-rechtsabteilung-rechtsschutzversicherung` | Deckungsprozess Zustaendigkeit 215 Vvg, Rechtsabteilung Rechtsschutzversicherung Im Massenverfahren, Sachverstaendigenverfahren Versicherung: Deckungsprozess Zustaendigkeit 215 Vvg; Rechtsabteilung Rechtsschutzversicherung Im Massenverfa... |
| `direktanspruch-pflichtversicherung-eiopa-grenzueberschreitender` | Direktanspruch Pflichtversicherung 115 Vvg, Eiopa Grenzueberschreitender Vertrieb, Gewerbe Betriebsschliessung Infektionsschutz: Direktanspruch Pflichtversicherung 115 Vvg; Eiopa Grenzueberschreitender Vertrieb; Gewerbe Betriebsschliessu... |
| `dora-cyber-abfindung-entschaedigungsquittung-bu-abstrakte` | Dora Cyber Ikt Versicherer, Vergleich Abfindung Entschaedigungsquittung, Bu Abstrakte Konkrete Verweisung: Dora Cyber Ikt Versicherer; Vergleich Abfindung Entschaedigungsquittung; Bu Abstrakte Konkrete Verweisung. Führt Intake, Prüfrouti... |
| `hausrat-einbruchdiebstahl-idd-vertrieb-internationales` | Hausrat Einbruchdiebstahl Entschaedigungsgrenze, Idd Vertrieb Beratung Dokumentation, Internationales Versicherungsprogramm Master Local Policy: Hausrat Einbruchdiebstahl Entschaedigungsgrenze; Idd Vertrieb Beratung Dokumentation; Intern... |
| `kfz-haftpflicht-kasko-grobe-krankentagegeld-berufsunfaehigkeit` | Kfz Haftpflicht Regress Alkohol Flucht, Kfz Kasko Grobe Fahrlaessigkeit Entwendung, Krankentagegeld Berufsunfaehigkeit Abgrenzung: Kfz Haftpflicht Regress Alkohol Flucht; Kfz Kasko Grobe Fahrlaessigkeit Entwendung; Krankentagegeld Berufs... |
| `kreditausfallversicherung-warenkredit-kreditversicherung` | Kreditausfallversicherung Warenkredit Forderungsausfall, Kreditversicherung Obliegenheiten Limit Prüfung, Lebensversicherung Bezugsrecht Widerruf Aenderung: Kreditausfallversicherung Warenkredit Forderungsausfall; Kreditversicherung Obli... |
| `lebensversicherung-rueckkaufswert-lebensversicherung` | Lebensversicherung Rueckkaufswert Abschlusskosten Widerspruch, Lebensversicherung Ueberschussbeteiligung Bewertungsreserven, Nachhaltigkeit Taxonomie Sfdr Versicherungsprodukt: Lebensversicherung Rueckkaufswert Abschlusskosten Widerspruc... |
| `pkv-kostenerstattung-private-krankenversicherung` | Pkv Kostenerstattung Medizinische Notwendigkeit, Private Krankenversicherung Beitragsanpassung Treuhaender, Produkthaftpflicht Rueckrufkosten: Pkv Kostenerstattung Medizinische Notwendigkeit; Private Krankenversicherung Beitragsanpassung... |
| `rechtsabteilung-betriebsunterbrechung-rechtsabteilung` | Rechtsabteilung Betriebsunterbrechung Und Lieferkettenausfall, Rechtsabteilung Cyberversicherung Nach Ransomware, Rechtsabteilung Idd Vertrieb Und Provisionskonflikt: Rechtsabteilung Betriebsunterbrechung Und Lieferkettenausfall; Rechtsa... |
| `rechtsabteilung-d-umwelthaftpflicht-umweltschadenversicherung` | Rechtsabteilung D O Deckung Bei Organhaftung, Umwelthaftpflicht Umweltschadenversicherung, Versicherungsmakler Haftung Deckungsluecke: Rechtsabteilung D O Deckung Bei Organhaftung; Umwelthaftpflicht Umweltschadenversicherung; Versicherun... |
| `rechtsschutz-deckungszusage-rechtsschutz-erfolgsaussicht` | Rechtsschutz Deckungszusage Stichentscheid, Rechtsschutz Erfolgsaussicht Mutwilligkeit, Reiseversicherung Rücktritt Abbruch Krankheit: Rechtsschutz Deckungszusage Stichentscheid; Rechtsschutz Erfolgsaussicht Mutwilligkeit; Reiseversicher... |
| `restschuldversicherung-widerruf-rueckversicherung-cut-solvency` | Restschuldversicherung Widerruf Kopplung Verbraucherdarlehen, Rueckversicherung Cut Through Und Fronting, Solvency Ii Scr Orsa Aufsichtsrecht: Restschuldversicherung Widerruf Kopplung Verbraucherdarlehen; Rueckversicherung Cut Through Un... |
| `subrogation-regress-transportversicherung-ware-vag-bafin` | Subrogation Regress 86 Vvg, Transportversicherung Ware Lagerung, Vag Bafin Aufsicht Beschwerde Missstand: Subrogation Regress 86 Vvg; Transportversicherung Ware Lagerung; Vag Bafin Aufsicht Beschwerde Missstand. Führt Intake, Prüfroutine... |
| `unfallversicherung-invaliditaet-vers-verjaehrung-rechtsschutz` | Unfallversicherung Invaliditaet Fristen Gliedertaxe, Vers Fristen Verjaehrung Klagefrist Fallkalender, Rechtsschutz Vorvertraglichkeit Schadenereignis: Unfallversicherung Invaliditaet Fristen Gliedertaxe; Vers Fristen Verjaehrung Klagefr... |
| `vers-allgemeiner-kaltstart` | Allgemeiner Einstieg ins Versicherungsrecht: Police, Bedingungen, Schadenereignis, Ablehnung, Fristen, Aufsicht, Ombudsmann und Klageweg strukturiert erfassen und passende Spezial-Skills vorschlagen. |
| `vers-deckungsablehnung-redteam` | Deckungsablehnung des Versicherers zerlegen: Risikoausschluss, Obliegenheit, Kausalität, grobe Fahrlässigkeit, Arglist, Beweislast und Vergleichsfenster systematisch prüfen. |
| `vers-dokumentenintake-police-avb-nachtraege` | Dokumentenintake für Versicherungsakten: Versicherungsschein, AVB, Nachträge, Beratungsdokumentation, Schadenanzeige, Gutachten, Korrespondenz und Ablehnung in eine Aktenmatrix überführen. |
| `vers-ombudsmann-versicherungsbetrug-verdachtsfall` | Vers Ombudsmann Bafin Beschwerde Klageweg, Versicherungsbetrug Verdachtsfall Kooperation Strafrecht, Versicherungssumme Unterversicherung Taxwert: Vers Ombudsmann Bafin Beschwerde Klageweg; Versicherungsbetrug Verdachtsfall Kooperation S... |
| `versicherungsprodukt-agb-betriebshaftpflicht-versicherungsfall` | Versicherungsprodukt Agb Klauselkontrolle, Betriebshaftpflicht Versicherungsfall Serienschaden, Betriebsunterbrechung Sachschaden Trigger: Versicherungsprodukt Agb Klauselkontrolle; Betriebshaftpflicht Versicherungsfall Serienschaden; Be... |
| `vvg-anzeigepflicht-vvg-arglist-vvg-falligkeit` | Vvg Anzeigepflicht 19 Rücktritt Kündigung Anpassung, Vvg Arglist Taeuschung Anfechtung, Vvg Falligkeit 14 Abschlagszahlung: Vvg Anzeigepflicht 19 Rücktritt Kündigung Anpassung; Vvg Arglist Taeuschung Anfechtung; Vvg Falligkeit 14 Abschla... |
| `vvg-gefahrerhoehung-mehrfachversicherung-obliegenheit-quotelung` | Vvg Gefahrerhoehung 23 27, Vvg Mehrfachversicherung 78, Vvg Obliegenheit 28 Quotelung Kausalitaet: Vvg Gefahrerhoehung 23 27; Vvg Mehrfachversicherung 78; Vvg Obliegenheit 28 Quotelung Kausalitaet. Führt Intake, Prüfroutine, Normen-/Quel... |
| `vvg-versicherung-wohngebaeude-leitungswasser` | Vvg Versicherung Für Fremde 43 48, Wohngebaeude Leitungswasser Sturm Hagel Brand: Vvg Versicherung Für Fremde 43 48; Wohngebaeude Leitungswasser Sturm Hagel Brand. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuste... |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
