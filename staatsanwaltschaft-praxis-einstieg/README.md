# Staatsanwaltschaft Praxis-Einstieg

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`staatsanwaltschaft-praxis-einstieg`) | [`staatsanwaltschaft-praxis-einstieg.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/staatsanwaltschaft-praxis-einstieg.zip) |

Dieses Plugin hat (bewusst) keine eigene Demonstrations-Akte.

<!-- END plugin-sofort-download-section (autogen) -->

Praxisplugin für neue Staatsanwältinnen, Staatsanwälte und Sitzungsdienst: Ermittlungsverfahren, Polizei, RiStBV, Vermerke, Beschlagnahme, digitale Beweise, Anklage, Strafbefehl, Hauptverhandlung, Plädoyer, Rechtsmittel und gerichtliche Bußgeldverfahren nach OWiG.

## Worum es geht

Dieses Plugin ist ein experimentelles Arbeits- und Lernwerkzeug. Es soll keine echten Amts-, Mandats-, Steuer-, Prüfungs- oder Berufsgeheimnisse aufnehmen, solange die technische und rechtliche Umgebung dafür nicht ausdrücklich freigegeben ist. Es arbeitet am besten mit anonymisierten, abstrahierten oder synthetischen Fällen und mit Dokumenten, die vor der Nutzung datenschutz- und geheimnisschutzrechtlich geprüft wurden.

## Arbeitsweise

Der Allgemein-Skill startet kurz, sortiert Rolle, Verfahrensstand, Frist, Unterlagen und gewünschtes Arbeitsprodukt und routet dann in die passenden Spezial-Skills. Jeder Skill verlangt Quellenhygiene: Normen, Behördenhinweise, Formulare und Rechtsprechung werden vor tragenden Aussagen live aus amtlichen oder frei zugänglichen Quellen geprüft; keine BeckRS-, juris-, Kommentar- oder Aufsatz-Blindzitate.

## Typische Outputs

- Kurzvermerk und Risikoampel
- Checkliste für den nächsten Arbeitstag
- Fragenliste an Behörde, Gericht, Kammer, Mandant, Partei oder Zeugen
- Entwurf für Verfügung, Vermerk, Schriftsatz, Antrag, E-Mail oder Gesprächsleitfaden
- Red-Team-Check gegen Fristenfehler, Zuständigkeitsfehler und Scheingenauigkeit

## OWiG- und Bußgeldspur

Für Ordnungswidrigkeiten arbeitet das Plugin bewusst mit anderer Sprache: kein Anklagesatz, kein Strafbefehl, sondern Bußgeldbescheid, Einspruch, Zwischenverfahren, Vorlage über die Staatsanwaltschaft, gerichtliches Bußgeldverfahren, Beschlussverfahren, Hauptverhandlung und Rechtsbeschwerde. Die neuen `owi-*`-Skills helfen insbesondere bei Datenschutzbußgeldern, Verkehrs-OWi, Unternehmensgeldbußen, Aufsichtspflichtverletzungen, Umwelt-/Arbeitsschutz-/Produktsicherheits-OWi und der Frage, wann die Staatsanwaltschaft am Termin nach § 75 OWiG teilnehmen sollte.

## Installation

ZIP aus dem aktuellen Release laden und in Claude Code oder Cowork über Customize Plugins installieren.

## Lizenz

Apache-2.0 OR MIT — Auswahl beim Empfänger.


<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 27 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `allgemein-kaltstart-und-routing` | Allgemeiner Kaltstart und Routing: Praxis-Skill für neue Staatsanwälte zu führt vom ersten Satz oder Dokument in den richtigen Arbeitsmodus; mit Datenschutz-/Aktengeheimniswarnung, RiStBV-/StPO-Quellencheck, Verfügungsvorschlag und nächs... |
| `arbeitsstrafrecht-266a-aufsichtsbeschwerde-dienstweg` | Arbeitsstrafrecht 266A Und Mindestlohn, Aufsichtsbeschwerde Und Dienstweg, Befangenheit Richter Antrag Sta, Befangenheit Richter Schoeffen, Bekaempfung Organisierte Kriminalitaet: Arbeitsstrafrecht 266A Und Mindestlohn; Aufsichtsbeschwer... |
| `berufung-sta-beweisantraege-stpo-beweisverwertungsverbote-btmg` | Berufung Sta Einlegen Und Begrenzen, Beweisantraege 244 Stpo Reagieren, Beweisverwertungsverbote Sta, Btmg Kcang Mischfaelle, Btmg Kcang Sitzungsdienst: Berufung Sta Einlegen Und Begrenzen; Beweisantraege 244 Stpo Reagieren; Beweisverwer... |
| `cybercrime-logfiles-daten-plattformen-deal-verstaendigung` | Cybercrime Logfiles Und Chain Of Custody, Daten Von Plattformen Bestandsdaten, Deal Verstaendigung 257C Stpo Sta, Digitale Durchsuchung Daten Sicherung, Digitale Spuren Mobiltelefon Cloud: Cybercrime Logfiles Und Chain Of Custody; Daten... |
| `dokumentenintake-und-aktenlog` | Dokumentenintake und Aktenlog: Praxis-Skill für neue Staatsanwälte zu ordnet Uploads, Eingangspost, Aktenbestandteile und fehlende Unterlagen; mit Datenschutz-/Aktengeheimniswarnung, RiStBV-/StPO-Quellencheck, Verfügungsvorschlag und näc... |
| `durchsuchung-beschlagnahme-kanzlei-arzt-einstellung-153a-stpo` | Durchsuchung Beschlagnahme Antrag, Durchsuchung Kanzlei Arzt Redaktion, Einstellung 153 153A Auflagen, Einstellung 153 153A Stpo, Einziehung Drittbetroffene Anhoerung: Durchsuchung Beschlagnahme Antrag; Durchsuchung Kanzlei Arzt Redaktio... |
| `encrochat-anom-encrochat-sky-entscheidungsvorlage` | Encrochat Anom Sky Ecc Krypto, Encrochat Sky Ecc Anom Beweiswert, Entscheidungsvorlage, Ermittlungsvermerk Schreiben, Europaeischer Haftbefehl Sta Praxis: Encrochat Anom Sky Ecc Krypto; Encrochat Sky Ecc Anom Beweiswert; Entscheidungsvor... |
| `geldwaesche-krypto-haeusliche-gewalt-haftbefehl-u` | Geldwaesche Krypto Und Kontoarrest, Haeusliche Gewalt Opferschutz Und Beweis, Haftbefehl Und U Haft Antrag, Hasskriminalitaet Online Und Plattformdaten, Hauptverhandlung Sta Vorbereitung: Geldwaesche Krypto Und Kontoarrest; Haeusliche Ge... |
| `insolvenzverschleppung-bankrott-beweisimport-verwertung` | Insolvenzverschleppung Und Bankrott, Internationaler Beweisimport Verwertung, Jugendstrafrecht Erziehungsziel, Jugendstrafrecht Sta, Koerperverletzung Strafantrag 230: Insolvenzverschleppung Und Bankrott; Internationaler Beweisimport Ver... |
| `konfliktverteidigung-sitzung-souveraen-korruptionsdelikte-opfer` | Konfliktverteidigung Sitzung Ordnung, Konfliktverteidigung Souveraen, Korruptionsdelikte Amtstraeger Und Healthcare, Mandanten Oder Beteiligtenkommunikation, Opfer Und Nebenklage Kommunikation: Konfliktverteidigung Sitzung Ordnung; Konfl... |
| `owi-bussgeldbescheid-owi-umwelt-beschuldigtenvernehmung` | Owi Bussgeldbescheid Inhalt Und Fehler, Owi Umwelt Arbeitsschutz Produkt Bussgeld, Beschuldigtenvernehmung Anhoerung, Polizei Ermittlungsauftrag Nachsteuerung, Rechtsmittel Sta Berufung Revision: Owi Bussgeldbescheid Inhalt Und Fehler; O... |
| `owi-kaltstart-bussgeldverfahren-sta-rolle` | OWiG-Kaltstart: Strafsache oder Ordnungswidrigkeit, Verwaltungsbehörde, Staatsanwaltschaft, Gericht und richtige Verfahrenssprache trennen: OWiG-Praxis-Skill für junge Staatsanwältinnen und Staatsanwälte mit Zuständigkeitscheck, Bußgeldb... |
| `owi-ki-deepfake-mehrfachverfahren-verbindung-beschlussverfahren` | Ki Und Deepfake Beweise Strafverfahren, Mehrfachverfahren Verbindung Trennung, Owi Beschlussverfahren 72 Und Widerspruch, Owi Datenschutz Bussgeld Lg Zustaendigkeit, Owi Einspruch Und Zwischenverfahren 69: Ki Und Deepfake Beweise Strafve... |
| `owi-kosten-owi-opportunitaet-owi-rechtsbeschwerde-owi` | Owi Kosten Vollstreckung Und Rücknahme, Owi Opportunitaet Einstellung 47, Owi Rechtsbeschwerde 79 80, Owi Verbandsgeldbusse 30 130, Owi Verjaehrung Verfolgungsverjaehrung: Owi Kosten Vollstreckung Und Rücknahme; Owi Opportunitaet Einstel... |
| `owi-opferrechte-nebenklage-abwesenheit-betroffener-kommunikation` | Opferrechte Nebenklage Adhaesion, Owi Abwesenheit Betroffener 73 74, Owi Beweisaufnahme 77 Und Beweisantraege, Owi Hauptverhandlung Sitzungsdienst Sta, Owi Kommunikation Mit Verwaltungsbehoerde: Opferrechte Nebenklage Adhaesion; Owi Abwe... |
| `owi-uebergang-revision-sta-sicherungsverfahren-stpo` | Owi Uebergang Strafverfahren 81 82, Revision Sta Verfahrensruegen Vorpruefung, Sicherungsverfahren 413 Stpo, Wirtschaftsstrafverfahren Datenraum Aktenplan, Betrug Onlinehandel Beweis Und Schaden: Owi Uebergang Strafverfahren 81 82; Revis... |
| `owi-verkehrsowi-vorlage-an-pflichtverteidigung-sta-plaedoyer` | Owi Verkehrsowi Fahrverbot Punkte, Owi Vorlage An Amtsgericht Sta Check, Pflichtverteidigung Aus Sta Sicht, Plaedoyer Beweiswuerdigung Strafmass, Plaedoyer Staatsanwaltschaft: Owi Verkehrsowi Fahrverbot Punkte; Owi Vorlage An Amtsgericht... |
| `polizei-zusammenarbeit-presse-oeffentlichkeit-presseauskunft` | Polizei Zusammenarbeit Ermittlungsauftrag, Presse Und Oeffentlichkeit, Presseauskunft Und Oeffentlichkeit, Protokoll Und Nachbereitung, Rechtshilfe Europaeische Ermittlungsanordnung: Polizei Zusammenarbeit Ermittlungsauftrag; Presse Und... |
| `quellen-rechtsprechungscheck-anfangsverdacht` | Quellen Und Rechtsprechungscheck, Anfangsverdacht Und Verfahrenseinleitung, Beschleunigtes Verfahren 418 Stpo, Frist Und Zustaendigkeit Cockpit, Fristenkalender Staatsanwaltschaft: Quellen Und Rechtsprechungscheck; Anfangsverdacht Und Ve... |
| `rechtshilfe-international-ristbv-finden-ristbv` | Rechtshilfe International, Ristbv Finden Anwenden, Ristbv Verfuegungstechnik Standard, Sachverstaendige Beauftragen Und Befragen, Schoeffen Befangenheit Und Mitwirkung: Rechtshilfe International; Ristbv Finden Anwenden; Ristbv Verfuegung... |
| `red-team-qualitygate` | Red-Team-Qualitygate: Praxis-Skill für neue Staatsanwälte zu prüft Ergebnis auf Fristenfehler, Zuständigkeitsfehler, Scheinpräzision und Ton; mit Datenschutz-/Aktengeheimniswarnung, RiStBV-/StPO-Quellencheck, Verfügungsvorschlag und näch... |
| `staatsanwalt-rolle-staatsanwaltschaft-zwischen-stalking-stgb` | Staatsanwalt Rolle Legalitaet Objektivitaet, Staatsanwaltschaft Übergabe Zwischen Dezernaten, Stalking 238 Stgb Gewschg Schnittstelle, Strafbefehl Beantragen, Strafbefehl Tagessaetze Und Nebenfolgen: Staatsanwalt Rolle Legalitaet Objekti... |
| `steuerstrafrecht-kooperation-abschlussverfuegung-anfaengerfehler` | Steuerstrafrecht Kooperation Finanzamt, Abschlussverfuegung Anfaengerfehler, Aktengeheimnis Und Ki Nutzung Sta, Anklageschrift Aufbau, Anklageschrift Grosse Wirtschaftsstrafkammer: Steuerstrafrecht Kooperation Finanzamt; Abschlussverfueg... |
| `u-haft-umweltstrafrecht-behoerdenakten-untreue-geschaeftsfuehrer` | U Haft Fluchtgefahr Verhaeltnismaessigkeit, Umweltstrafrecht Behoerdenakten, Untreue Geschaeftsfuehrer Kontoanalyse, Urheber Und Markenstrafrecht Praxis, Verkehrsstrafrecht Blutprobe Fahrerlaubnis: U Haft Fluchtgefahr Verhaeltnismaessigk... |
| `verkehrsstrafrecht-strafbefehl-vermoegensarrest-einziehung` | Verkehrsstrafrecht Strafbefehl, Vermoegensarrest Einziehung, Vermoegensarrest Einziehung Schnellcheck, Vollstreckung Und Gnadenschnittstelle, Waffenrecht Und Sprengstoff Nebenstrafrecht: Verkehrsstrafrecht Strafbefehl; Vermoegensarrest E... |
| `vermerk-mustertext-sexualdelikte-aussage-sitzungs` | Schriftsatz Vermerk Und Mustertext, Sexualdelikte Aussage Gegen Aussage, Sitzungs Und Terminvorbereitung, Sitzungsdienst Amtsgericht, Sitzungsdienst Referendar Notfallkarte: Schriftsatz Vermerk Und Mustertext; Sexualdelikte Aussage Gegen... |
| `wirtschaftsstrafsachen-sachleitung-wohnungsdurchsuchung-gefahr` | Wirtschaftsstrafsachen Sachleitung, Wohnungsdurchsuchung Gefahr Im Verzug, Zeugenmanagement Und Ladungsrisiken, Zeugenvernehmung Zeugenrechte: Wirtschaftsstrafsachen Sachleitung; Wohnungsdurchsuchung Gefahr Im Verzug; Zeugenmanagement Un... |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
