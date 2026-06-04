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
| `allgemein` | Einstieg, Schnelltriage und Workflow-Routing im Meinungsprüfer. Fragt Wortlaut, Kontext, Medium, Publikum, Tatsachenkern, Belege, betroffene Person, Anlass, Vorgeschichte, gewünschtes Ziel und Risiko ab; schlägt passende Spezial-Skills z... |
| `kompendium-01-workflow-chronologie-bis-workflow-fristen-und` | meinungspruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Chronologie Und Belegmatrix, Fristen Und Risikoampel; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck. |
| `kompendium-02-egmr-art-10-rechtspr-bis-eugh-grch-art-11-rec` | meinungspruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Egmr Art 10 Rechtsprechung, Eugh Grch Art 11 Rechtsprechung; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck. |
| `kompendium-03-olg-kg-praxis-rechts-bis-rechtsprechungsbank` | meinungspruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Olg Kg Praxis Rechtsprechung, Rechtsprechungsbank Verifiziert; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck. |
| `kompendium-04-spezial-meinung-fris-bis-strafantrag-194-und` | meinungspruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Meinung Fristen Form Und Zustaendigkeit, Strafantrag 194 Und Verfahren; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätsch... |
| `kompendium-05-zivilrecht-unterlass-bis-abmahnung-strafanzei` | meinungspruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Zivilrecht Unterlassung Widerruf Schadensersatz, Abmahnung Strafanzeige Reaktion; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Q... |
| `kompendium-06-abwaegung-art-5-gg-bis-arbeitgeber-betrieb` | meinungspruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Abwaegung Art 5 Gg, Arbeitgeber Betrieb Kantine; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck. |
| `kompendium-07-beleglage-tatsachenb-bis-beweissicherung-scre` | meinungspruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Beleglage Tatsachenbehauptung, Beweissicherung Screenshots; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck. |
| `kompendium-08-europarecht-emrk-grc-bis-gegendarstellung-ent` | meinungspruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Europarecht Emrk Grch, Gegendarstellung Entschuldigung Deeskalation; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck. |
| `kompendium-09-kommunalrecht-buerge-bis-machtkritik-amtstrae` | meinungspruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Kommunalrecht Buergermeister, Machtkritik Amtstraeger; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck. |
| `kompendium-10-mehrdeutigkeit-sinne-bis-meinung-tatsache-abg` | meinungspruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Mehrdeutigkeit Sinnermittlung, Meinung Tatsache Abgrenzung; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck. |
| `kompendium-11-personen-politisches-bis-presserecht-plattfor` | meinungspruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Personen Politisches Leben 188, Presserecht Plattformen Loeschung Dsa; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck. |
| `kompendium-12-rechtsvergleich-usa-bis-risikomatrix-ampel` | meinungspruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Rechtsvergleich Usa Supreme Court, Risikomatrix Ampel; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck. |
| `kompendium-13-satire-ironisierung-bis-schimpfwort-lackaffe` | meinungspruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Satire Ironisierung Pinocchio, Schimpfwort Lackaffe Und Spott; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck. |
| `kompendium-14-schmaehkritik-formal-bis-schnelltriage-aeusse` | meinungspruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Schmaehkritik Formalbeleidigung Menschenwuerde, Schnelltriage Aeusserung; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitäts... |
| `kompendium-15-schriftsatz-stellung-bis-schule-elternchat` | meinungspruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Schriftsatz Stellungnahme Verteidigung, Schule Elternchat; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck. |
| `kompendium-16-soziale-medien-x-lin-bis-spezial-aeusserungsr` | meinungspruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Soziale Medien X Linkedin, Aeusserungsrecht Tatbestand Beweis Und Belege; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitäts... |
| `kompendium-17-spezial-beleidigung-bis-spezial-meinungsprue` | meinungspruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Beleidigung Risikoampel Und Gegenargumente, Meinungspruefer Erstpruefung Und Mandatsziel; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmust... |
| `kompendium-18-spezial-nachrede-sch-bis-spezial-tatsache-dok` | meinungspruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Nachrede Schriftsatz Brief Und Memo Bausteine, Tatsache Dokumentenmatrix Und Lueckenliste; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmus... |
| `kompendium-19-spezial-ueble-behoer-bis-spezial-verleumdung` | meinungspruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Ueble Behoerden Gericht Und Registerweg, Verleumdung Verhandlung Vergleich Und Eskalation; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmus... |
| `kompendium-20-strafrecht-185-belei-bis-testakte-auswertung` | meinungspruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Strafrecht 185 Beleidigung, Testakte Auswertung; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck. |
| `kompendium-21-ueble-nachrede-186-bis-verleumdung-187` | meinungspruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Ueble Nachrede 186, Verleumdung 187; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck. |
| `kompendium-22-wahrnehmung-berechti-bis-zitat-und-kontextauf` | meinungspruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Wahrnehmung Berechtigter Interessen 193, Zitat Und Kontextaufnahme; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck. |
| `output-memo-pruefvermerk` | Erzeugt den finalen Prüfvermerk zum Meinungsfall mit Sachverhalt, Wortlaut, Kontext, Normen, Rechtsprechung, Subsumtion, Risikoampel, Belegliste, Alternativformulierungen und Handlungsempfehlung. |
| `spezial-stgb-livequellen-und-rechtsprechungscheck` | Stgb: Livequellen- und Rechtsprechungscheck im Plugin meinungspruefer; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Standardprüfung. |
| `workflow-dokumentenintake` | Dokumentenintake im Plugin meinungspruefer: liest Uploads, sortiert Dokumentarten, markiert Fristen und baut eine knappe Arbeitsakte. |
| `workflow-kaltstart-und-routing` | Kaltstart und Routing im Plugin meinungspruefer: führt vom ersten Satz oder Dokument in den passenden Arbeitsweg, erkennt Rolle, Ziel, Risiko und Anschluss-Skills. |
| `workflow-unterlagen-lueckenliste` | Unterlagen- und Lückenliste im Plugin meinungspruefer: erstellt eine präzise Nachforderungsliste statt allgemeiner Fragebögen. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
