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
| `abwaegung-art-arbeitgeber-betrieb` | Nutze dies, wenn Abwaegung Art 5 Gg, Arbeitgeber Betrieb Kantine im Plugin Meinungspruefer konkret bearbeitet werden soll. Auslöser: Bitte Abwaegung Art 5 Gg, Arbeitgeber Betrieb Kantine prüfen.; Erstelle eine Arbeitsfassung zu Abwaegung... |
| `allgemein` | Einstieg, Schnelltriage und Workflow-Routing im Meinungsprüfer. Fragt Wortlaut, Kontext, Medium, Publikum, Tatsachenkern, Belege, betroffene Person, Anlass, Vorgeschichte, gewünschtes Ziel und Risiko ab; schlägt passende Spezial-Skills z... |
| `beleglage-tatsachenbehauptung-beweissicherung` | Nutze dies, wenn Beleglage Tatsachenbehauptung, Beweissicherung Screenshots im Plugin Meinungspruefer konkret bearbeitet werden soll. Auslöser: Bitte Beleglage Tatsachenbehauptung, Beweissicherung Screenshots prüfen.; Erstelle eine Arbei... |
| `beleidigung-meinungspruefer` | Nutze dies, wenn Spezial Beleidigung Risikoampel Und Gegenargumente, Spezial Meinungspruefer Erstpruefung Und Mandatsziel im Plugin Meinungspruefer konkret bearbeitet werden soll. Auslöser: Bitte Spezial Beleidigung Risikoampel Und Gegen... |
| `chronologie-fristen` | Nutze dies, wenn Workflow Chronologie Und Belegmatrix, Workflow Fristen Und Risikoampel im Plugin Meinungspruefer konkret bearbeitet werden soll. Auslöser: Bitte Workflow Chronologie Und Belegmatrix, Workflow Fristen Und Risikoampel prüf... |
| `dokumente-intake` | Nutze dies, wenn Dokumentenintake im Plugin Meinungspruefer konkret bearbeitet werden soll. Auslöser: Ich lade Unterlagen hoch.; Was fehlt noch?; Bitte Dokumente sortieren.. |
| `egmr-art-eugh-grch` | Nutze dies, wenn Egmr Art 10 Rechtsprechung, Eugh Grch Art 11 Rechtsprechung im Plugin Meinungspruefer konkret bearbeitet werden soll. Auslöser: Bitte Egmr Art 10 Rechtsprechung, Eugh Grch Art 11 Rechtsprechung prüfen.; Erstelle eine Arb... |
| `einstieg-routing` | Nutze dies, wenn Einstieg und Routing im Plugin Meinungspruefer konkret bearbeitet werden soll. Auslöser: Ich habe ein neues Thema im Bereich Meinungspruefer.; Welche Unterlagen brauchen Sie?; Welcher Spezialskill passt?. |
| `europarecht-emrk-gegendarstellung` | Nutze dies, wenn Europarecht Emrk Grch, Gegendarstellung Entschuldigung Deeskalation im Plugin Meinungspruefer konkret bearbeitet werden soll. Auslöser: Bitte Europarecht Emrk Grch, Gegendarstellung Entschuldigung Deeskalation prüfen.; E... |
| `kommunalrecht-buergermeister-machtkritik` | Nutze dies, wenn Kommunalrecht Buergermeister, Machtkritik Amtstraeger im Plugin Meinungspruefer konkret bearbeitet werden soll. Auslöser: Bitte Kommunalrecht Buergermeister, Machtkritik Amtstraeger prüfen.; Erstelle eine Arbeitsfassung... |
| `mehrdeutigkeit-sinnermittlung-meinung` | Nutze dies, wenn Mehrdeutigkeit Sinnermittlung, Meinung Tatsache Abgrenzung im Plugin Meinungspruefer konkret bearbeitet werden soll. Auslöser: Bitte Mehrdeutigkeit Sinnermittlung, Meinung Tatsache Abgrenzung prüfen.; Erstelle eine Arbei... |
| `meinung-strafantrag-verfahren` | Nutze dies, wenn Spezial Meinung Fristen Form Und Zustaendigkeit, Strafantrag 194 Und Verfahren im Plugin Meinungspruefer konkret bearbeitet werden soll. Auslöser: Bitte Spezial Meinung Fristen Form Und Zustaendigkeit, Strafantrag 194 Un... |
| `nachrede-tatsache` | Nutze dies, wenn Spezial Nachrede Schriftsatz Brief Und Memo Bausteine, Spezial Tatsache Dokumentenmatrix Und Lueckenliste im Plugin Meinungspruefer konkret bearbeitet werden soll. Auslöser: Was kann hier schiefgehen?; Bitte red-team prü... |
| `olg-kg-rechtsprechungsbank-verifiziert` | Nutze dies, wenn Olg Kg Praxis Rechtsprechung, Rechtsprechungsbank Verifiziert im Plugin Meinungspruefer konkret bearbeitet werden soll. Auslöser: Bitte Olg Kg Praxis Rechtsprechung, Rechtsprechungsbank Verifiziert prüfen.; Erstelle eine... |
| `output-memo-pruefvermerk` | Erzeugt den finalen Prüfvermerk zum Meinungsfall mit Sachverhalt, Wortlaut, Kontext, Normen, Rechtsprechung, Subsumtion, Risikoampel, Belegliste, Alternativformulierungen und Handlungsempfehlung. |
| `personen-politisches-presserecht-plattformen` | Nutze dies, wenn Personen Politisches Leben 188, Presserecht Plattformen Löschung Dsa im Plugin Meinungspruefer konkret bearbeitet werden soll. Auslöser: Bitte Personen Politisches Leben 188, Presserecht Plattformen Löschung Dsa prüfen.;... |
| `rechtsvergleich-usa-risikomatrix-ampel` | Nutze dies, wenn Rechtsvergleich Usa Supreme Court, Risikomatrix Ampel im Plugin Meinungspruefer konkret bearbeitet werden soll. Auslöser: Bitte Rechtsvergleich Usa Supreme Court, Risikomatrix Ampel prüfen.; Erstelle eine Arbeitsfassung... |
| `satire-ironisierung-schimpfwort-lackaffe` | Nutze dies, wenn Satire Ironisierung Pinocchio, Schimpfwort Lackaffe Und Spott im Plugin Meinungspruefer konkret bearbeitet werden soll. Auslöser: Bitte Satire Ironisierung Pinocchio, Schimpfwort Lackaffe Und Spott prüfen.; Erstelle eine... |
| `schmaehkritik-formalbeleidigung-schnelltriage` | Nutze dies, wenn Schmaehkritik Formalbeleidigung Menschenwuerde, Schnelltriage Aeusserung im Plugin Meinungspruefer konkret bearbeitet werden soll. Auslöser: Bitte Schmaehkritik Formalbeleidigung Menschenwuerde, Schnelltriage Aeusserung... |
| `soziale-medien-aeusserungsrecht` | Nutze dies, wenn Soziale Medien X Linkedin, Spezial Aeusserungsrecht Tatbestand Beweis Und Belege im Plugin Meinungspruefer konkret bearbeitet werden soll. Auslöser: Bitte Soziale Medien X Linkedin, Spezial Aeusserungsrecht Tatbestand Be... |
| `stellungnahme-verteidigung-schule-elternchat` | Nutze dies, wenn Schriftsatz Stellungnahme Verteidigung, Schule Elternchat im Plugin Meinungspruefer konkret bearbeitet werden soll. Auslöser: Bitte Schriftsatz Stellungnahme Verteidigung, Schule Elternchat prüfen.; Erstelle eine Arbeits... |
| `stgb-quellenkarte` | Nutze dies, wenn Stgb Quellenkarte im Plugin Meinungspruefer konkret bearbeitet werden soll. Auslöser: Welche amtliche Quelle prüfe ich zuerst?; Gibt es aktuelle Rechtsprechung?; Bitte Fundstellen verifizieren.. |
| `strafrecht-beleidigung-testakte-auswertung` | Nutze dies, wenn Strafrecht 185 Beleidigung, Testakte Auswertung im Plugin Meinungspruefer konkret bearbeitet werden soll. Auslöser: Bitte Strafrecht 185 Beleidigung, Testakte Auswertung prüfen.; Erstelle eine Arbeitsfassung zu Strafrech... |
| `ueble-nachrede-verleumdung` | Nutze dies, wenn Ueble Nachrede 186, Verleumdung 187 im Plugin Meinungspruefer konkret bearbeitet werden soll. Auslöser: Was kann hier schiefgehen?; Bitte red-team prüfen.; Welche Frist oder Beweislast übersehe ich?. |
| `ueble-verleumdung` | Nutze dies, wenn Spezial Ueble Behörden Gericht Und Registerweg, Spezial Verleumdung Verhandlung Vergleich Und Eskalation im Plugin Meinungspruefer konkret bearbeitet werden soll. Auslöser: Bitte Spezial Ueble Behörden Gericht Und Regist... |
| `unterlagen-luecken` | Nutze dies, wenn Unterlagen und Lücken im Plugin Meinungspruefer konkret bearbeitet werden soll. Auslöser: Ich lade Unterlagen hoch.; Was fehlt noch?; Bitte Dokumente sortieren.. |
| `wahrnehmung-berechtigter-zitat` | Nutze dies, wenn Wahrnehmung Berechtigter Interessen 193, Zitat Und Kontextaufnahme im Plugin Meinungspruefer konkret bearbeitet werden soll. Auslöser: Bitte Wahrnehmung Berechtigter Interessen 193, Zitat Und Kontextaufnahme prüfen.; Ers... |
| `zivilrecht-unterlassung-abmahnung` | Nutze dies, wenn Zivilrecht Unterlassung Widerruf Schadensersatz, Abmahnung Strafanzeige Reaktion im Plugin Meinungspruefer konkret bearbeitet werden soll. Auslöser: Bitte Zivilrecht Unterlassung Widerruf Schadensersatz, Abmahnung Strafa... |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
