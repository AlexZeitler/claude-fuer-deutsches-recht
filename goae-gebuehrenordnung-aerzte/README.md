# GOÄ Gebührenordnung für Ärzte

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`goae-gebuehrenordnung-aerzte`) | [`goae-gebuehrenordnung-aerzte.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/goae-gebuehrenordnung-aerzte.zip) |

Dieses Plugin hat (bewusst) keine eigene Demonstrations-Akte.

<!-- END plugin-sofort-download-section (autogen) -->

Super-Plugin zur GOÄ: private Arztrechnungen prüfen, erstellen, begründen, beanstanden und prozessual verwerten.

## Wofür dieses Plugin da ist
Gebührenordnung für Ärzte mit Schwellenwerten, Steigerungssätzen, Analogabrechnung, Zielleistungsprinzip, Auslagen, Wahlleistungen, PKV/Beihilfe und Honorarstreit.

Das Plugin ist als Arbeitswerkzeug gedacht: Es startet mit einem Kaltstart-Interview, sortiert Unterlagen, prüft Fristen und routet dann in Spezial-Skills. Es soll Anfänger an die Hand nehmen und Profis schnell zu belastbaren Outputs bringen.

## Typischer Workflow
1. **Allgemein-Skill starten:** Rolle, Ziel, Frist, Unterlagen und gewünschtes Ergebnis klären.
2. **Dokumente einlesen:** Verträge, Bescheide, Rechnungen, Tabellen, Registerdaten, Behördenpost oder Screenshots strukturieren.
3. **Spezial-Skill wählen:** Das Plugin schlägt den passenden Skill vor und erklärt, welches Ergebnis damit entsteht.
4. **Live-Quellen prüfen:** Normtext, Behördenseite, EU-Text, Formular oder frei zugängliche Rechtsprechung aktualisieren.
5. **Output erzeugen:** Memo, Antrag, Stellungnahme, Vertragsklausel, Berechnung, Checkliste oder Mandantenbrief.
6. **Red-Team:** Fristen, Zuständigkeit, Zahlen, Quellen und Gegenargumente kontrollieren.

## Quellenanker
- Amtliche Gesetzestexte: gesetze-im-internet.de.
- EU-Recht: EUR-Lex und amtliche Kommissionsseiten.
- Behördenpraxis: zuständige Bundes-/Landesbehörden, Bundesnetzagentur, BaFin, BfArM, G-BA, BKartA oder Länderstellen je nach Thema.
- Rechtsprechung nur mit Gericht, Datum, Aktenzeichen und frei/amtlich prüfbarer Quelle.

## Skill-Schwerpunkte
| Gruppe | Inhalt |
| --- | --- |
| Einstieg und Workflow | Kaltstart, Dokumentenintake, Fristen, Quellencheck, Output-Wahl, Red-Team |
| Materielle Prüfung | Tatbestände, Ausnahmen, Schwellen, Beweislast, Berechnungen, Rechtsfolgen |
| Verfahren und Kommunikation | Anträge, Anhörungen, Beschwerden, Schriftsätze, Behördenkontakt, Mandantenkommunikation |
| Spezialthemen | Branchen-, Vertrags-, Gebühren-, Aufsichts-, EU- und Edge-Case-Prüfungen |

## Quellen- und Halluzinationsschutz
Dieses Plugin soll keine nicht prüfbaren Fundstellen produzieren. Bei unsicherer oder dynamischer Rechtslage wird der Live-Quellencheck ausdrücklich vorgeschaltet.

## Lizenz
Apache-2.0 OR MIT — Auswahl beim Empfänger.


<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 24 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `allgemein` | Einstieg, Schnelltriage und Workflow-Routing im GOÄ Gebührenordnung für Ärzte-Plugin. Fragt Rolle, Ziel, Fristen, Unterlagen, Risiken und Wunsch-Output ab, erkennt stumme Uploads und schlägt passende Spezial-Skills aus diesem Plugin vor. |
| `kaltstart-goae-rechnung-pruefen` | Workflow zur strukturierten Aufnahme, Priorisierung und Ausgabe im Thema Kaltstart GOÄ Rechnung prüfen. |
| `kompendium-01-analoge-bewertung-ne-bis-abschnitt-a-beratung` | goae-gebuehrenordnung-aerzte: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Analoge Bewertung Neue Verfahren Innovation, Abrechnung Telemedizin Videosprechstunde Goae, Abschnitt A Beratungen Und Untersuchungen; mit Intake,... |
| `kompendium-02-abschnitt-b-grundlei-bis-abtretung-factoring` | goae-gebuehrenordnung-aerzte: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Abschnitt B Grundleistungen Zuschlaege, Abschnitt C Nichtgebietsbezogene Sonderleistungen, Abtretung Factoring Arzthonorar Datenschutz; mit Intake,... |
| `kompendium-03-analogabrechnung-int-bis-arztbrief-begruendun` | goae-gebuehrenordnung-aerzte: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Analogabrechnung Intake 6 Goae, Arbeitsunfaehigkeitsbescheinigung Privatpatient, Arztbrief Begruendung Nachfordern; mit Intake, Prüfroutine, Normen... |
| `kompendium-04-arzthonorarprozess-d-bis-begruendung-ueber-sc` | goae-gebuehrenordnung-aerzte: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Arzthonorarprozess Dokumentenplan, Auslandsbehandlung Deutsche Goae Anwendung, Begruendung Ueber Schwellenwert Redigieren; mit Intake, Prüfroutine,... |
| `kompendium-05-beihilfe-einwendunge-bis-berufsrecht-ueberhoe` | goae-gebuehrenordnung-aerzte: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Beihilfe Einwendungen Und Differenzbetrag, Belegarzt Und Konsiliararzt Abrechnung, Berufsrecht Ueberhoehte Liquidation; mit Intake, Prüfroutine, No... |
| `kompendium-06-erstattung-pkv-vs-ho-bis-gebuehrenrahmen-schw` | goae-gebuehrenordnung-aerzte: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Erstattung Pkv Vs Honoraranspruch Patient, Faelligkeit Verzug Mahnung Honorarklage, Gebuehrenrahmen Schwellenwert Ampel; mit Intake, Prüfroutine, N... |
| `kompendium-07-goae-1-anwendungsber-bis-goae-3-verguetungen` | goae-gebuehrenordnung-aerzte: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Goae 1 Anwendungsbereich Berufliche Leistungen, Goae 2 Abweichende Vereinbarung Honorarvereinbarung, Goae 3 Verguetungen Gebuehren Entschaedigungen... |
| `kompendium-08-goae-4-selbstaendige-bis-goae-5a-bemessung-im` | goae-gebuehrenordnung-aerzte: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Goae 4 Selbstaendige Aerztliche Leistung Zielleistungsprinzip, Goae 5 Bemessung Gebuehrenrahmen 2 3 1 8 1 15 Schwelle, Goae 5a Bemessung Im Basista... |
| `kompendium-09-goae-5b-standardtari-bis-goae-6a-stationaere` | goae-gebuehrenordnung-aerzte: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Goae 5b Standardtarif Pkv, Goae 6 Gebuehren Fuer Andere Leistungen Analogbewertung, Goae 6a Stationaere Minderung 25 Prozent 15 Prozent; mit Intake... |
| `kompendium-10-goae-7-entschaedigun-bis-goae-9-reiseentschae` | goae-gebuehrenordnung-aerzte: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Goae 7 Entschaedigungen, Goae 8 Wegegeld, Goae 9 Reiseentschaedigung; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und... |
| `kompendium-11-goae-10-ersatz-von-a-bis-goae-14-zahlung-durc` | goae-gebuehrenordnung-aerzte: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Goae 10 Ersatz Von Auslagen, Goae 12 Faelligkeit Und Rechnungspflicht, Goae 14 Zahlung Durch Oeffentliche Leistungstraeger; mit Intake, Prüfroutine... |
| `kompendium-12-goae-rechnung-aus-pd-bis-gutachten-atteste-be` | goae-gebuehrenordnung-aerzte: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Goae Rechnung Aus Pdf Extrahieren, Goae Reform Referentenentwuerfe Beobachten, Gutachten Atteste Bescheinigungen; mit Intake, Prüfroutine, Normen-/... |
| `kompendium-13-igel-aufklaerung-kos-bis-kosmetische-leistung` | goae-gebuehrenordnung-aerzte: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Igel Aufklaerung Kosteninformation, Klageerwiderung Honorarprozess, Kosmetische Leistungen Medizinische Indikation; mit Intake, Prüfroutine, Normen... |
| `kompendium-14-laborleistungen-und-bis-livecheck-goae-text` | goae-gebuehrenordnung-aerzte: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Laborleistungen Und Hoechstsatz Besonderheiten, Leistungskette Zielleistung Keine Aufspaltung, Livecheck Goae Text Und Reformstand; mit Intake, Prü... |
| `kompendium-15-m-iii-m-iv-labor-del-bis-materialkosten-ausla` | goae-gebuehrenordnung-aerzte: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu M Iii M Iv Labor Delegation Speziallabor, Mandantenmail Patient Freundlich Klar, Materialkosten Auslagen Abgrenzung 10 Goae; mit Intake, Prüfroutin... |
| `kompendium-16-mehrfachansatz-aussc-bis-notfall-behandlung-a` | goae-gebuehrenordnung-aerzte: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Mehrfachansatz Ausschluesse Nebeneinanderberechnung, Minderjaehrige Einwilligung Rechnung Schuldner, Notfall Behandlung Ausserhalb Sprechstunde; mi... |
| `kompendium-17-op-komplexe-narkose-bis-plausibilitaetscheck` | goae-gebuehrenordnung-aerzte: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Op Komplexe Narkose Assistenz Zuschlaege, Patientenbrief Und Einwendung Formulieren, Plausibilitaetscheck Rechnung Mathematisch; mit Intake, Prüfro... |
| `kompendium-18-psychotherapie-psych-bis-sachverstaendigenfra` | goae-gebuehrenordnung-aerzte: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Psychotherapie Psychiatrie Gespraechsleistungen, Radiologie Schnittbild Zielleistung, Sachverstaendigenfragen Goae Streit; mit Intake, Prüfroutine,... |
| `kompendium-19-schlichtungsstelle-a-bis-steigerungssatz-begr` | goae-gebuehrenordnung-aerzte: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Schlichtungsstelle Aerztekammer Honorarstreit, Stationaere Privataerztliche Liquidation, Steigerungssatz Begruendung Individuell Patientenbezogen;... |
| `kompendium-20-tabellenexport-goae-bis-wahlleistungsvereinb` | goae-gebuehrenordnung-aerzte: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Tabellenexport Goae Pruefliste, Verjaehrung Aerztlicher Honoraranspruch, Wahlleistungsvereinbarung Krankenhaus Goae; mit Intake, Prüfroutine, Norme... |
| `kompendium-21-wegegeld-besuch-mehr-bis-zahnaerztliche-schni` | goae-gebuehrenordnung-aerzte: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Wegegeld Besuch Mehrere Patienten, Zahnaerztliche Schnittstelle Goz Goae; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster... |
| `red-team-goae-rechnung-halluzinationscheck` | Red-Team GOÄ Rechnung Halluzinationscheck: prüft die einschlägigen Voraussetzungen, Dokumente, Risiken und Ausnahmen. Norm-/Quellenanker: GOÄ §§ 1-14 und Anlage, BGB Behandlungsvertrag §§ 630a ff., PKV/Beihilfe-Regelungen, Berufsrecht, a... |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
