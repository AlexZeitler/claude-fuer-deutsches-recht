# Bundeswehrrecht und Wehrrecht

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`bundeswehrrecht-wehrrecht`) | [`bundeswehrrecht-wehrrecht.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/bundeswehrrecht-wehrrecht.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **KDV-Verfahren Malte Eberhard Rabenow / Berlin-Köln 2026** (`kriegsdienstverweigerung-gewissensantrag-berlin-2026`) | [Gesamt-PDF lesen](../testakten/kriegsdienstverweigerung-gewissensantrag-berlin-2026/gesamt-pdf/kriegsdienstverweigerung-gewissensantrag-berlin-2026_gesamt.pdf) | [`testakte-kriegsdienstverweigerung-gewissensantrag-berlin-2026.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-kriegsdienstverweigerung-gewissensantrag-berlin-2026.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

Super-Plugin für Soldatenrecht, Wehrbeschwerde, Disziplinarrecht, Wehrpflicht, Reservisten, Versorgung und Bundeswehrverwaltung.

## Wofür dieses Plugin da ist
Bundeswehrrecht mit Soldatengesetz, Wehrbeschwerdeordnung, Wehrdisziplinarordnung, Wehrpflichtgesetz, Reservistenrecht, Soldatenversorgung, Befehlsrecht, Fürsorge und Rechtsschutz.

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

Automatisch generierte Komplett-Liste aller 30 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `allgemein` | Einstieg, Schnelltriage und Workflow-Routing im Bundeswehrrecht und Wehrrecht-Plugin. Fragt Rolle, Ziel, Fristen, Unterlagen, Risiken und Wunsch-Output ab, erkennt stumme Uploads und schlägt passende Spezial-Skills aus diesem Plugin vor. |
| `kaltstart-bundeswehrrecht` | Kaltstart Bundeswehrrecht: schneller Einstieg und Routing zu den richtigen Spezial-Skills bei unbekanntem Sachverhalt. Norm-/Quellenanker: SG, WBO, WDO, SVG. |
| `kompendium-01-beschwerde-fristen-s-bis-disziplinarverfahren` | bundeswehrrecht-wehrrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Beschwerde Fristen Sofortcheck, Bwbes Neu 010 Besoldungswiderspruch Soldat Und Fristen, Disziplinarverfahren Intake; mit Intake, Prüfroutine, Normen-/... |
| `kompendium-02-eilverfahren-konkurr-bis-gerichtliches-diszip` | bundeswehrrecht-wehrrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Eilverfahren Konkurrentenstreit Wehrdienstsenat, Fristenkalender Bundeswehrrecht, Gerichtliches Disziplinarverfahren Soldat; mit Intake, Prüfroutine,... |
| `kompendium-03-kriegsdienstverweige-bis-truppendienstgericht` | bundeswehrrecht-wehrrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Kriegsdienstverweigerung Verfahren, Rechtsbeistand Im Disziplinarverfahren, Truppendienstgericht Zustaendigkeit Verfahren; mit Intake, Prüfroutine, No... |
| `kompendium-04-wehrbeschwerdeordnun-bis-aerztliche-begutacht` | bundeswehrrecht-wehrrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Wehrbeschwerdeordnung Beschwerde Frist Form, Schadenersatz Regress Dienstunfall Material, Aerztliche Begutachtung Dienstfaehigkeit; mit Intake, Prüfro... |
| `kompendium-05-akteneinsicht-wbo-wd-bis-ausbildung-studium-b` | bundeswehrrecht-wehrrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Akteneinsicht Wbo Wdo, Arbeitsrecht Zivile Bundeswehrbeschaeftigte, Ausbildung Studium Bundeswehr Rueckforderung Ausbildungskosten; mit Intake, Prüfro... |
| `kompendium-06-auslandseinsatz-mand-bis-befehl-verweigern-ge` | bundeswehrrecht-wehrrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Auslandseinsatz Mandat Einsatzregeln, Beamtenrecht Bundeswehrverwaltung Abgrenzung, Befehl Verweigern Gewissensnot Rechtswidrigkeit; mit Intake, Prüfr... |
| `kompendium-07-beschwerde-gegen-beu-bis-beurteilung-konkurre` | bundeswehrrecht-wehrrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Beschwerde Gegen Beurteilung Und Laufbahnentscheidung, Besoldung Zulagen Auslandsverwendungszuschlag, Beurteilung Konkurrentenstreit Auswahlentscheidu... |
| `kompendium-08-bundesverwaltungsger-bis-bwbes-neu-002-wehrso` | bundeswehrrecht-wehrrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Bundesverwaltungsgericht Wehrdienstsenate, Bwbes Neu 001 Soldatenbesoldung Grundgehalt Und Dienstgrad, Bwbes Neu 002 Wehrsold Freiwilliger Wehrdienst... |
| `kompendium-09-bwbes-neu-003-auslan-bis-bwbes-neu-005-erschw` | bundeswehrrecht-wehrrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Bwbes Neu 003 Auslandsverwendungszuschlag Und Einsatzversorgung, Bwbes Neu 004 Trennungsgeld Umzugskosten Reisebeihilfe, Bwbes Neu 005 Erschwerniszula... |
| `kompendium-10-bwbes-neu-006-dienst-bis-bwbes-neu-008-heilfu` | bundeswehrrecht-wehrrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Bwbes Neu 006 Dienstzeitversorgung Berufsfoerderungsdienst, Bwbes Neu 007 Soldatenversorgung Dienstunfall Wehrdienstbeschaed, Bwbes Neu 008 Heilfuerso... |
| `kompendium-11-bwbes-neu-009-besold-bis-bwbes-neu-012-diszip` | bundeswehrrecht-wehrrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Bwbes Neu 009 Besoldung Reservist Wehruebung Und Arbeitgeberausg, Bwbes Neu 011 Kdv Und Besoldungsfolgen Bei Statuswechsel, Bwbes Neu 012 Disziplinarb... |
| `kompendium-12-bwbes-neu-013-verwen-bis-bwbes-neu-015-ruhens` | bundeswehrrecht-wehrrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Bwbes Neu 013 Verwendungsfaehigkeit Tauglichkeit Und Finanzielle, Bwbes Neu 014 Auslandseinsatz Anerkennung Und Nachweise, Bwbes Neu 015 Ruhensregelun... |
| `kompendium-13-dienstunfaehigkeit-e-bis-einsatz-unfall-verso` | bundeswehrrecht-wehrrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Dienstunfaehigkeit Entlassung Zurruhesetzung, Dienstzeit Soldat Auf Zeit Berufssoldat Fwdl, Einsatz Unfall Versorgung Dokumentenplan; mit Intake, Prüf... |
| `kompendium-14-einsatzunfall-wehrdi-bis-ernennung-dienstgrad` | bundeswehrrecht-wehrrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Einsatzunfall Wehrdienstbeschaedigung, Entlassung Auf Eigenen Antrag, Ernennung Dienstgrad Laufbahnrecht; mit Intake, Prüfroutine, Normen-/Quellenrada... |
| `kompendium-15-extremismus-verdacht-bis-gehorsam-befehl-und` | bundeswehrrecht-wehrrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Extremismus Verdachtsfall Sicherheitsrecht, Geheimschutz Sicherheitsueberpruefung Sueg, Gehorsam Befehl Und Rechtswidriger Befehl; mit Intake, Prüfrou... |
| `kompendium-16-gleichstellung-diskr-bis-kameradschaft-achtun` | bundeswehrrecht-wehrrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Gleichstellung Diskriminierung Soldatinnen Soldaten, Impfpflicht Tauglichkeit Musterung, Kameradschaft Achtungs Und Vertrauenspflicht; mit Intake, Prü... |
| `kompendium-17-livecheck-sg-wbo-wdo-bis-mobbing-fuersorgepfl` | bundeswehrrecht-wehrrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Livecheck Sg Wbo Wdo Wpflg Svg, Mandantenbrief Soldat Verstaendlich, Mobbing Fuersorgepflicht Bundeswehr; mit Intake, Prüfroutine, Normen-/Quellenrada... |
| `kompendium-18-nebentaetigkeit-gesc-bis-personalvertretung-z` | bundeswehrrecht-wehrrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Nebentaetigkeit Geschenkannahme Compliance, Personalakte Einsicht Datenschutz, Personalvertretung Zivile Beschaeftigte Schnittstelle; mit Intake, Prüf... |
| `kompendium-19-pflicht-zum-treuen-d-bis-presseaeusserung-mei` | bundeswehrrecht-wehrrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Pflicht Zum Treuen Dienen 7 Sg, Politische Betaetigung Maessigung Neutralitaet, Presseaeusserung Meinungsfreiheit Soldat; mit Intake, Prüfroutine, Nor... |
| `kompendium-20-ptbs-einsatzfolge-be-bis-sanitaetsdienst-heil` | bundeswehrrecht-wehrrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Ptbs Einsatzfolge Beweisfuehrung, Reservistendienst Dienstleistungspflicht, Sanitaetsdienst Heilfuersorge; mit Intake, Prüfroutine, Normen-/Quellenrad... |
| `kompendium-21-sexuelle-belaestigun-bis-soldatenbeteiligung` | bundeswehrrecht-wehrrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Sexuelle Belaestigung Beschwerde Schutzpflicht, Social Media Soldat Dienstpflichten, Soldatenbeteiligung Vertrauensperson Sbg; mit Intake, Prüfroutine... |
| `kompendium-22-soldatengesetz-recht-bis-status-soldat-beamte` | bundeswehrrecht-wehrrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Soldatengesetz Rechtsstellung Grundpflichten, Soldatenversorgungsgesetz Beschaedigtenversorgung, Status Soldat Beamter Zivilbeschaeftigter Klaeren; mi... |
| `kompendium-23-statusrechte-im-eins-bis-unterhaltssicherung` | bundeswehrrecht-wehrrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Statusrechte Im Einsatz Urlaub Betreuung, Trennungsgeld Umzugskosten Reisekosten, Unterhaltssicherung Reservisten; mit Intake, Prüfroutine, Normen-/Qu... |
| `kompendium-24-versetzung-kommandie-bis-wehrdisziplinarordnu` | bundeswehrrecht-wehrrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Versetzung Kommandierung Abordnung, Vorlaeufige Dienstenthebung Einbehaltung Bezuege, Wehrdisziplinarordnung Einfache Disziplinarmassnahme; mit Intake... |
| `kompendium-25-wehrpflicht-wehrdien-bis-wehrstrafrecht-fahne` | bundeswehrrecht-wehrrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Wehrpflicht Wehrdienst Reservist Routing, Wehrpflichtgesetz Spannungs Und Verteidigungsfall, Wehrstrafrecht Fahnenflucht Gehorsamsverweigerung Schnitt... |
| `kompendium-26-wehruebungen-heranzi-bis-widerruf-ernennung-a` | bundeswehrrecht-wehrrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Wehruebungen Heranziehungsbescheid, Weitere Beschwerde Und Gerichtlicher Antrag Wehrdienstgericht, Widerruf Ernennung Arglistige Taeuschung; mit Intak... |
| `output-beschwerde-antrag-stellungnahme` | Output Beschwerde, Antrag, Stellungnahme: erstellt strukturierte Schriftstücke nach WBO, WDO und VwGO. Norm-/Quellenanker: WBO §§ 6–11, WDO, VwGO. |
| `red-team-bundeswehr-beschwerde` | Red-Team Bundeswehr-Beschwerde: kritische Gegenprüfung einer Beschwerde auf Schwachstellen, Gegenargumente und Verbesserungen. Norm-/Quellenanker: WBO, WDO, VwGO. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
