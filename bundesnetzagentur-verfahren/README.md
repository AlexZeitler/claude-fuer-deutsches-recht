# Bundesnetzagentur-Verfahren

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`bundesnetzagentur-verfahren`) | [`bundesnetzagentur-verfahren.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/bundesnetzagentur-verfahren.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **Märkische Reserve Süd — Batteriespeicher Brandenburg/Berlin** (`batteriespeicher-brandenburg-berlin-resilienz`) | [Gesamt-PDF lesen](../testakten/batteriespeicher-brandenburg-berlin-resilienz/gesamt-pdf/batteriespeicher-brandenburg-berlin-resilienz_gesamt.pdf) | [`testakte-batteriespeicher-brandenburg-berlin-resilienz.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-batteriespeicher-brandenburg-berlin-resilienz.zip) |
| **Projekt Isarlicht — Kernfusion und Transrapid am Starnberger See** (`kernfusion-transrapid-starnberger-see`) | [Gesamt-PDF lesen](../testakten/kernfusion-transrapid-starnberger-see/gesamt-pdf/kernfusion-transrapid-starnberger-see_gesamt.pdf) | [`testakte-kernfusion-transrapid-starnberger-see.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-kernfusion-transrapid-starnberger-see.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

Großes Regulierungs-Plugin für anwaltliche Arbeit mit der Bundesnetzagentur in Energie, Telekommunikation, Post, Eisenbahn und Digital Services.

## Wofür dieses Plugin da ist
Anwaltliche Verfahren mit der Bundesnetzagentur: Zuständigkeit, Beschlusskammern, Konsultationen, Auskünfte, Bußgelder, Beschwerden, Energie-, TK-, Post-, Eisenbahn- und DSA-Regulierung.

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

Automatisch generierte Komplett-Liste aller 32 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `allgemein` | Einstieg, Schnelltriage und Workflow-Routing im Bundesnetzagentur-Verfahren-Plugin. Fragt Rolle, Ziel, Fristen, Unterlagen, Risiken und Wunsch-Output ab, erkennt stumme Uploads und schlägt passende Spezial-Skills aus diesem Plugin vor. |
| `kaltstart-bundesnetzagentur-mandat` | Workflow zur strukturierten Aufnahme, Priorisierung und Ausgabe im Thema Kaltstart Bundesnetzagentur-Mandat. |
| `komp-01-teil-02-energie-regulierungsakte-bilanzkreis-gas-fristen` | bundesnetzagentur-verfahren: eigenständiger Arbeits-Skill für sachlich zusammengehörige Arbeitsmodule zu Energie Regulierungsakte Bilanzkreis Gas Fristen Und Bescheidana, Energie Regulierungsakte Bilanzkreis Strom Fristen Und Bescheida,... |
| `komp-07-teil-02-tk-regulierungsakte-nummernverwaltung-stellungna` | bundesnetzagentur-verfahren: eigenständiger Arbeits-Skill für sachlich zusammengehörige Arbeitsmodule zu Tk Regulierungsakte Nummernverwaltung Stellungnahme Entwurf, Tk Regulierungsakte Rufnummernmissbrauch Stellungnahme Entwurf, Aktenzu... |
| `kompendium-01-anhoerung-auskunftsb-bis-energie-regulierungs` | bundesnetzagentur-verfahren: eigenständiger Arbeits-Skill für sachlich zusammengehörige Arbeitsmodule zu Anhoerung Auskunftsbeschluss Fristenplan, Digital Services Melde Und Abhilfeverfahren Notice And Action, Eilverfahren Verwaltungsger... |
| `kompendium-02-energie-regulierungs-bis-energie-regulierungs` | bundesnetzagentur-verfahren: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Energie Regulierungsakte Kwkg Zuschlaege Fristen Und Bescheidana, Energie Regulierungsakte Ladesaeulen Elektromobilitaet Fristen U, Energie Regulier... |
| `kompendium-03-energie-regulierungs-bis-tk-regulierungsakte` | bundesnetzagentur-verfahren: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Energie Regulierungsakte Redispatch 2 0 Fristen Und Bescheidanal, Energie Regulierungsakte Regelenergie Fristen Und Bescheidanalys, Energie Regulier... |
| `kompendium-04-tk-regulierungsakte-bis-verfahren-durchsuchu` | bundesnetzagentur-verfahren: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Tk Regulierungsakte Nummernverwaltung Fristen Und Bescheidanalys, Tk Regulierungsakte Rufnummernmissbrauch Fristen Und Bescheidana, Verfahren Aktene... |
| `kompendium-05-verfahren-eilrechtss-bis-verfahren-verpflicht` | bundesnetzagentur-verfahren: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Verfahren Eilrechtsschutz 80 Vwgo, Verfahren Festlegungsverfahren Beschlusskammer, Verfahren Gebuehren Kosten Bnetza, Verfahren Geschaeftsgeheimniss... |
| `kompendium-06-verfahren-vorstandsv-bis-energie-regulierungs` | bundesnetzagentur-verfahren: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Verfahren Vorstandsvorlage Regulierungsrisiko, Verfahren Widerspruch Klage Verwaltungsgericht, Zustaendigkeitsradar Energie Telekom Post Eisenbahn D... |
| `kompendium-07-energie-regulierungs-bis-beschwerde-verbrauch` | bundesnetzagentur-verfahren: eigenständiger Arbeits-Skill für sachlich zusammengehörige Arbeitsmodule zu Energie Regulierungsakte Redispatch 2 0 Stellungnahme Entwurf, Energie Regulierungsakte Regelenergie Stellungnahme Entwurf, Tk Regul... |
| `kompendium-08-digital-services-alg-bis-digital-services-onl` | bundesnetzagentur-verfahren: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Digital Services Algorithmen Empfehlungssysteme Dsa, Digital Services Aussergerichtliche Streitbeilegungsstelle Dsa, Digital Services Dark Patterns... |
| `kompendium-09-digital-services-tra-bis-eisenbahn-entgeltreg` | bundesnetzagentur-verfahren: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Digital Services Transparenzberichte Online Plattformen, Digital Services Trusted Flagger Anerkennung, Digital Services Vlop Vlose Koordination Eu K... |
| `kompendium-10-eisenbahn-kapazitaet-bis-energie-anreizreguli` | bundesnetzagentur-verfahren: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Eisenbahn Kapazitaetskonflikt Fahrplan, Eisenbahn Netznutzungsbedingungen, Eisenbahn Regulierungsvereinbarung Db Netz Infrago, Eisenbahn Serviceeinr... |
| `kompendium-11-energie-bbplg-leitun-bis-energie-grundversorg` | bundesnetzagentur-verfahren: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Energie Bbplg Leitungsvorhaben, Energie Bilanzkreis Gas, Energie Bilanzkreis Strom, Energie Eeg Netzanschluss Einspeisemanagement und 4 weitere Arbe... |
| `kompendium-12-energie-kapazitaetsv-bis-energie-netzanschlus` | bundesnetzagentur-verfahren: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Energie Kapazitaetsvergabe Gas, Energie Kwkg Zuschlaege, Energie Ladesaeulen Elektromobilitaet, Energie Lieferantenwechsel Energie und 4 weitere Arb... |
| `kompendium-13-energie-netzentgelte-bis-energie-regulierungs` | bundesnetzagentur-verfahren: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Energie Netzentgelte Gas, Energie Netzentgelte Strom, Energie Offshore Netzanbindung, Energie Redispatch 2 0 und 4 weitere Arbeitsmodule; mit Intake... |
| `kompendium-14-energie-regulierungs-bis-energie-regulierungs` | bundesnetzagentur-verfahren: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Energie Regulierungsakte Anreizregulierung Erloesobergrenze Unte, Energie Regulierungsakte Bbplg Leitungsvorhaben Rechtsmittel Che, Energie Regulier... |
| `kompendium-15-energie-regulierungs-bis-energie-regulierungs` | bundesnetzagentur-verfahren: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Energie Regulierungsakte Eeg Netzanschluss Einspeisemanagement F, Energie Regulierungsakte Eeg Netzanschluss Einspeisemanagement R, Energie Regulier... |
| `kompendium-16-energie-regulierungs-bis-energie-regulierungs` | bundesnetzagentur-verfahren: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Energie Regulierungsakte Kapazitaetsvergabe Gas Stellungnahme En, Energie Regulierungsakte Kapazitaetsvergabe Gas Unterlagenanford, Energie Regulier... |
| `kompendium-17-energie-regulierungs-bis-energie-regulierungs` | bundesnetzagentur-verfahren: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Energie Regulierungsakte Messstellenbetrieb Msbg Smart Meter Rec, Energie Regulierungsakte Messstellenbetrieb Msbg Smart Meter Ste, Energie Regulier... |
| `kompendium-18-energie-regulierungs-bis-energie-regulierungs` | bundesnetzagentur-verfahren: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Energie Regulierungsakte Netzanschluss Strom Rechtsmittel Check, Energie Regulierungsakte Netzanschluss Strom Stellungnahme Entwu, Energie Regulieru... |
| `kompendium-19-energie-regulierungs-bis-energie-regulierungs` | bundesnetzagentur-verfahren: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Energie Regulierungsakte Offshore Netzanbindung Rechtsmittel Che, Energie Regulierungsakte Offshore Netzanbindung Stellungnahme En, Energie Regulier... |
| `kompendium-20-energie-regulierungs-bis-energie-regulierungs` | bundesnetzagentur-verfahren: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Energie Regulierungsakte Remit Marktmissbrauch Energie Stellungn, Energie Regulierungsakte Remit Marktmissbrauch Energie Unterlage, Energie Regulier... |
| `kompendium-21-energie-regulierungs-bis-livecheck-bnetza-kon` | bundesnetzagentur-verfahren: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Energie Regulierungsakte Wasserstoffnetz Regulierung Rechtsmitte, Energie Regulierungsakte Wasserstoffnetz Regulierung Stellungnah, Energie Regulier... |
| `kompendium-22-post-arbeitsbedingun-bis-post-postgeheimnis` | bundesnetzagentur-verfahren: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Post Arbeitsbedingungen Postmarkt Schnittstelle, Post Beschwerde Brief Paket, Post Grenzueberschreitende Paketzustellung, Post Laufzeitmessung Quali... |
| `kompendium-23-post-postlizenz-anze-bis-telekommunikation-en` | bundesnetzagentur-verfahren: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Post Postlizenz Anzeige, Post Postmarktregulierung, Post Postuniversaldienst, Post Zugang Postfachanlage und 4 weitere Arbeitsmodule; mit Intake, Pr... |
| `kompendium-24-telekommunikation-fr-bis-telekommunikation-no` | bundesnetzagentur-verfahren: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Telekommunikation Frequenzauktion, Telekommunikation Frequenzzuteilung, Telekommunikation Glasfaserausbau Mitnutzung, Telekommunikation Inhouse Verk... |
| `kompendium-25-telekommunikation-nu-bis-telekommunikation-sp` | bundesnetzagentur-verfahren: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Telekommunikation Nummernverwaltung, Telekommunikation Providerwechsel Minderungsrecht, Telekommunikation Roaming Eu Schnittstelle, Telekommunikatio... |
| `kompendium-26-telekommunikation-st-bis-tk-regulierungsakte` | bundesnetzagentur-verfahren: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Telekommunikation Stoerung Entstoerung Verbraucherrechte, Telekommunikation Telekommunikationsgeheimnis, Telekommunikation Tk Verbraucherschlichtung... |
| `kompendium-27-tk-regulierungsakte-bis-tk-regulierungsakte` | bundesnetzagentur-verfahren: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Tk Regulierungsakte Frequenzauktion Unterlagenanforderung, Tk Regulierungsakte Frequenzzuteilung Rechtsmittel Check, Tk Regulierungsakte Frequenzzut... |
| `kompendium-28-tk-regulierungsakte-bis-tk-regulierungsakte` | bundesnetzagentur-verfahren: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Tk Regulierungsakte Tkg Marktregulierung Betraechtliche Marktm 3, Tk Regulierungsakte Tkg Marktregulierung Betraechtliche Marktm 4, Tk Regulierungsa... |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
