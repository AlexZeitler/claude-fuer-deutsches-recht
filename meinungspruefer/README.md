# Meinungsprüfer

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`meinungspruefer`) | [`meinungspruefer.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/meinungspruefer.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **Meinungsprüfer - Grenzfälle im Alltag** (`meinungspruefer-grenzfaelle-alltag`) | [Gesamt-PDF lesen](../testakten/meinungspruefer-grenzfaelle-alltag/gesamt-pdf/meinungspruefer-grenzfaelle-alltag_gesamt.pdf) | [`testakte-meinungspruefer-grenzfaelle-alltag.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-meinungspruefer-grenzfaelle-alltag.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

Freistehendes Plugin für die Prüfung von Äußerungen nach einfachem Recht, Verfassungsrecht, Europarecht und Rechtsvergleich: Meinung oder Tatsachenbehauptung, Beleidigung, üble Nachrede, Verleumdung, Personen des politischen Lebens, Wahrnehmung berechtigter Interessen, zivilrechtliche Unterlassung, Widerruf, Geldentschädigung, Plattform- und Social-Media-Kontext, EGMR/EuGH/GRCh, OLG-/KG-Praxis und US-Supreme-Court-Vergleich.

**Keine Rechtsberatung.** Das Plugin erzeugt eine strukturierte Vorprüfung und dokumentierbare Arbeitsprodukte zur anwaltlichen Kontrolle. Rechtsprechung wird nur mit Gericht, Datum, Aktenzeichen und frei prüfbarer Quelle verwendet.

## Start

```
/meinungspruefer:allgemein
```

Der Einstieg fragt schnell ab: exakter Wortlaut, Medium, Publikum, Anlass, Vorgeschichte, Betroffene, Tatsachenkern, Belege, Wiederholungsgefahr, gewünschter Output und Risikotoleranz. Danach routet er zu den passenden Spezialskills.

## Skills (36)

| Skill | Zweck |
|---|---|
| `allgemein` | Schöner Einstieg, Schnelltriage, Quellenhygiene und Routing |
| `schnelltriage-aeusserung` | Erste Ampel für Strafrecht, Zivilrecht, Plattform und arbeits-/schulbezogene Risiken |
| `zitat-und-kontextaufnahme` | Wortlaut, Kontext, Adressatenkreis, Medium und Vorgeschichte sauber erfassen |
| `meinung-tatsache-abgrenzung` | Meinung, Tatsache, gemischte Äußerung und Tatsachenkern trennen |
| `mehrdeutigkeit-sinnermittlung` | Sinnermittlung, Durchschnittspublikum und nicht ehrverletzende Deutungen |
| `beleglage-tatsachenbehauptung` | Belegmatrix für Tatsachen, Verdachtsäußerung und erwiesen unwahre Behauptung |
| `strafrecht-185-beleidigung` | § 185 StGB mit Art.-5-GG-Abwägung |
| `ueble-nachrede-186` | § 186 StGB, Nichterweislichkeit und Tatsachenkern |
| `verleumdung-187` | § 187 StGB, Wissen um Unwahrheit und Belegprüfung |
| `personen-politisches-leben-188` | § 188 StGB, Person des politischen Lebens, Öffentlichkeit und Erschwerung des Wirkens |
| `wahrnehmung-berechtigter-interessen-193` | § 193 StGB, Beschwerde, Bewertung, Mandats-/Arbeits-/Bürgerkontext |
| `strafantrag-194-und-verfahren` | Strafantrag, Antragsberechtigte, Fristen, Privatklage, Einstellungsoptionen |
| `schmaehkritik-formalbeleidigung-menschenwuerde` | Enge Ausnahmen ohne Normalabwägung |
| `abwaegung-art-5-gg` | Verfassungsrechtlicher Abwägungskern nach Art. 5 GG |
| `machtkritik-amtstraeger` | Amtsträger, Behörden, Bürgermeister, Schule, Justiz und Machtkritik |
| `arbeitgeber-betrieb-kantine` | Arbeitsplatz, Kantine, Kollegium, Betriebsrat, arbeitsrechtliche Nebenfolgen |
| `schule-elternchat` | Schule, Elternchat, Lehrkräfte, Schulleitung und pädagogischer Konflikt |
| `soziale-medien-x-linkedin` | X, LinkedIn, Kommentarspalten, Sichtbarkeit, Prangerwirkung, Screenshots |
| `kommunalrecht-buergermeister` | Kommunale Debatte, Bauprojekt, Ratssitzung, Amts- und Privatrolle |
| `satire-ironisierung-pinocchio` | Satire, Überzeichnung, Pinocchio-Vergleich, Lügenvorwurf als Wertung oder Tatsache |
| `schimpfwort-lackaffe-und-spott` | Spottbegriffe wie Lackaffe im Kontext prüfen |
| `zivilrecht-unterlassung-widerruf-schadensersatz` | APR, §§ 823, 1004 BGB analog, § 824 BGB und Beseitigungsansprüche |
| `presserecht-plattformen-loeschung-dsa` | Medien, Plattformmeldungen, Löschung, Sperrung und DSA-Schnittstellen |
| `europarecht-emrk-grch` | Art. 10 EMRK, Art. 11 GRCh, unions- und konventionsfreundliche Lesart |
| `egmr-art-10-rechtsprechung` | EGMR-Leitlinien zu öffentlicher Debatte, Werturteil, Tatsachengrundlage, Art.-8-/Art.-10-Abwägung, Hyperlinks und Drittkommentaren |
| `eugh-grch-art-11-rechtsprechung` | EuGH/GRCh bei Plattformen, Suchmaschinen, Datenschutz, Uploadfiltern, De-Referenzierung und journalistischen Zwecken |
| `olg-kg-praxis-rechtsprechung` | Obergerichtliche Praxis zu Unterlassung, Sinnermittlung, Social Media, Verdachtsäußerung, Plattformlabel und Tenorrisiko |
| `rechtsvergleich-usa-supreme-court` | US-Supreme-Court-Vergleich zu First Amendment, actual malice, public concern, opinion, parody, threats und incitement |
| `beweissicherung-screenshots` | Screenshots, Metadaten, Zeugen, URLs, Löschungen, Chatverläufe |
| `risikomatrix-ampel` | Ergebnis als Grün/Gelb/Rot mit Unsicherheiten und nächstem Schritt |
| `gegendarstellung-entschuldigung-deeskalation` | Reaktionsoptionen ohne unnötige Eskalation |
| `abmahnung-strafanzeige-reaktion` | Eingang von Abmahnung, Strafanzeige, Anhörung oder Plattformmeldung bearbeiten |
| `schriftsatz-stellungnahme-verteidigung` | Verteidigungs- und Erwiderungsbausteine |
| `output-memo-pruefvermerk` | Dokumentierter Prüfvermerk mit Zitat, Kontext, Normen und Ergebnis |
| `testakte-auswertung` | Die Testakte strukturiert auswerten |
| `rechtsprechungsbank-verifiziert` | Verifizierte Rechtsprechung mit Datum, Aktenzeichen und freier Quelle |

## Quellenstand

Stand: 05/2026. Kernnormen: Art. 5 GG, Art. 10 EMRK, Art. 11 GRCh, §§ 185-188, 192-194 StGB, §§ 823, 824, 1004 BGB analog, § 22 KUG bei Bildern und DSA-Schnittstellen bei Plattformen. Leitentscheidungen sind im Skill `rechtsprechungsbank-verifiziert` dokumentiert; der USA-Vergleich ist ausdrücklich nur Vergleich, kein Import amerikanischer Standards in die deutsche Prüfung.

<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 28 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `abwaegung-art-arbeitgeber-betrieb` | Abwaegung Art 5 Gg, Arbeitgeber Betrieb Kantine: Abwaegung Art 5 Gg; Arbeitgeber Betrieb Kantine. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zusammen. |
| `allgemein` | Einstieg, Schnelltriage und Workflow-Routing im Meinungsprüfer. Fragt Wortlaut, Kontext, Medium, Publikum, Tatsachenkern, Belege, betroffene Person, Anlass, Vorgeschichte, gewünschtes Ziel und Risiko ab; schlägt passende Spezial-Skills z... |
| `beleglage-tatsachenbehauptung-beweissicherung-screenshots` | Beleglage Tatsachenbehauptung, Beweissicherung Screenshots: Beleglage Tatsachenbehauptung; Beweissicherung Screenshots. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zusammen. |
| `beleidigung-meinungspruefer` | Spezial Beleidigung Risikoampel Und Gegenargumente, Spezial Meinungspruefer Erstpruefung Und Mandatsziel: Spezial Beleidigung Risikoampel Und Gegenargumente; Spezial Meinungspruefer Erstpruefung Und Mandatsziel. Führt Intake, Prüfroutine... |
| `egmr-art-eugh-grch` | Egmr Art 10 Rechtsprechung, Eugh Grch Art 11 Rechtsprechung: Egmr Art 10 Rechtsprechung; Eugh Grch Art 11 Rechtsprechung. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zusammen. |
| `europarecht-emrk-gegendarstellung-entschuldigung` | Europarecht Emrk Grch, Gegendarstellung Entschuldigung Deeskalation: Europarecht Emrk Grch; Gegendarstellung Entschuldigung Deeskalation. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zusam... |
| `kommunalrecht-buergermeister-machtkritik-amtstraeger` | Kommunalrecht Buergermeister, Machtkritik Amtstraeger: Kommunalrecht Buergermeister; Machtkritik Amtstraeger. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zusammen. |
| `mehrdeutigkeit-sinnermittlung-meinung-tatsache` | Mehrdeutigkeit Sinnermittlung, Meinung Tatsache Abgrenzung: Mehrdeutigkeit Sinnermittlung; Meinung Tatsache Abgrenzung. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zusammen. |
| `meinung-strafantrag-verfahren` | Spezial Meinung Fristen Form Und Zustaendigkeit, Strafantrag 194 Und Verfahren: Spezial Meinung Fristen Form Und Zustaendigkeit; Strafantrag 194 Und Verfahren. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster un... |
| `nachrede-tatsache` | Spezial Nachrede Schriftsatz Brief Und Memo Bausteine, Spezial Tatsache Dokumentenmatrix Und Lueckenliste: Spezial Nachrede Schriftsatz Brief Und Memo Bausteine; Spezial Tatsache Dokumentenmatrix Und Lueckenliste. Führt Intake, Prüfrouti... |
| `olg-kg-rechtsprechungsbank-verifiziert` | Olg Kg Praxis Rechtsprechung, Rechtsprechungsbank Verifiziert: Olg Kg Praxis Rechtsprechung; Rechtsprechungsbank Verifiziert. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zusammen. |
| `output-memo-pruefvermerk` | Erzeugt den finalen Prüfvermerk zum Meinungsfall mit Sachverhalt, Wortlaut, Kontext, Normen, Rechtsprechung, Subsumtion, Risikoampel, Belegliste, Alternativformulierungen und Handlungsempfehlung. |
| `personen-politisches-presserecht-plattformen` | Personen Politisches Leben 188, Presserecht Plattformen Löschung Dsa: Personen Politisches Leben 188; Presserecht Plattformen Löschung Dsa. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zus... |
| `rechtsvergleich-usa-risikomatrix-ampel` | Rechtsvergleich Usa Supreme Court, Risikomatrix Ampel: Rechtsvergleich Usa Supreme Court; Risikomatrix Ampel. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zusammen. |
| `satire-ironisierung-schimpfwort-lackaffe` | Satire Ironisierung Pinocchio, Schimpfwort Lackaffe Und Spott: Satire Ironisierung Pinocchio; Schimpfwort Lackaffe Und Spott. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zusammen. |
| `schmaehkritik-formalbeleidigung-schnelltriage-aeusserung` | Schmaehkritik Formalbeleidigung Menschenwuerde, Schnelltriage Aeusserung: Schmaehkritik Formalbeleidigung Menschenwuerde; Schnelltriage Aeusserung. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätsc... |
| `soziale-medien-aeusserungsrecht` | Soziale Medien X Linkedin, Spezial Aeusserungsrecht Tatbestand Beweis Und Belege: Soziale Medien X Linkedin; Spezial Aeusserungsrecht Tatbestand Beweis Und Belege. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuste... |
| `spezial-stgb-livequellen-und-rechtsprechungscheck` | Stgb: Livequellen- und Rechtsprechungscheck im Plugin meinungspruefer; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Standardprüfung. |
| `stellungnahme-verteidigung-schule-elternchat` | Schriftsatz Stellungnahme Verteidigung, Schule Elternchat: Schriftsatz Stellungnahme Verteidigung; Schule Elternchat. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zusammen. |
| `strafrecht-beleidigung-testakte-auswertung` | Strafrecht 185 Beleidigung, Testakte Auswertung: Strafrecht 185 Beleidigung; Testakte Auswertung. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zusammen. |
| `ueble-nachrede-verleumdung` | Ueble Nachrede 186, Verleumdung 187: Ueble Nachrede 186; Verleumdung 187. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zusammen. |
| `ueble-verleumdung` | Spezial Ueble Behörden Gericht Und Registerweg, Spezial Verleumdung Verhandlung Vergleich Und Eskalation: Spezial Ueble Behörden Gericht Und Registerweg; Spezial Verleumdung Verhandlung Vergleich Und Eskalation. Führt Intake, Prüfroutine... |
| `wahrnehmung-berechtigter-zitat-kontextaufnahme` | Wahrnehmung Berechtigter Interessen 193, Zitat Und Kontextaufnahme: Wahrnehmung Berechtigter Interessen 193; Zitat Und Kontextaufnahme. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zusammen. |
| `workflow-chronologie-workflow-fristen` | Workflow Chronologie Und Belegmatrix, Workflow Fristen Und Risikoampel: Workflow Chronologie Und Belegmatrix; Workflow Fristen Und Risikoampel. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck... |
| `workflow-dokumentenintake` | Dokumentenintake im Plugin meinungspruefer: liest Uploads, sortiert Dokumentarten, markiert Fristen und baut eine knappe Arbeitsakte. |
| `workflow-kaltstart-und-routing` | Kaltstart und Routing im Plugin meinungspruefer: führt vom ersten Satz oder Dokument in den passenden Arbeitsweg, erkennt Rolle, Ziel, Risiko und Anschluss-Skills. |
| `workflow-unterlagen-lueckenliste` | Unterlagen- und Lückenliste im Plugin meinungspruefer: erstellt eine präzise Nachforderungsliste statt allgemeiner Fragebögen. |
| `zivilrecht-unterlassung-abmahnung-strafanzeige` | Zivilrecht Unterlassung Widerruf Schadensersatz, Abmahnung Strafanzeige Reaktion: Zivilrecht Unterlassung Widerruf Schadensersatz; Abmahnung Strafanzeige Reaktion. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuste... |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
