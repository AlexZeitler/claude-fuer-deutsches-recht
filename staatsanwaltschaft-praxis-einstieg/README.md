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
| `dokumentenintake-und-aktenlog` | Dokumentenintake und Aktenlog: Praxis-Skill für neue Staatsanwälte zu ordnet Uploads, Eingangspost, Aktenbestandteile und fehlende Unterlagen; mit Datenschutz-/Aktengeheimniswarnung, RiStBV-/StPO-Quellencheck, Verfügungsvorschlag und näc... |
| `kompendium-01-quellen-und-rechtspr-bis-fristenkalender-staa` | staatsanwaltschaft-praxis-einstieg: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Quellen Und Rechtsprechungscheck, Anfangsverdacht Und Verfahrenseinleitung, Beschleunigtes Verfahren 418 Stpo, Frist Und Zustaendigkeit Cockp... |
| `kompendium-02-ki-und-deepfake-bewe-bis-owi-einspruch-und-zw` | staatsanwaltschaft-praxis-einstieg: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Ki Und Deepfake Beweise Strafverfahren, Mehrfachverfahren Verbindung Trennung, Owi Beschlussverfahren 72 Und Widerspruch, Owi Datenschutz Bus... |
| `kompendium-03-owi-uebergang-strafv-bis-betrug-onlinehandel` | staatsanwaltschaft-praxis-einstieg: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Owi Uebergang Strafverfahren 81 82, Revision Sta Verfahrensruegen Vorpruefung, Sicherungsverfahren 413 Stpo, Wirtschaftsstrafverfahren Datenr... |
| `kompendium-04-owi-bussgeldbescheid-bis-rechtsmittel-sta-ber` | staatsanwaltschaft-praxis-einstieg: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Owi Bussgeldbescheid Inhalt Und Fehler, Owi Umwelt Arbeitsschutz Produkt Bussgeld, Beschuldigtenvernehmung Anhoerung, Polizei Ermittlungsauft... |
| `kompendium-05-steuerstrafrecht-koo-bis-anklageschrift-gross` | staatsanwaltschaft-praxis-einstieg: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Steuerstrafrecht Kooperation Finanzamt, Abschlussverfuegung Anfaengerfehler, Aktengeheimnis Und Ki Nutzung Sta, Anklageschrift Aufbau und 1 w... |
| `kompendium-06-arbeitsstrafrecht-26-bis-bekaempfung-organisi` | staatsanwaltschaft-praxis-einstieg: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Arbeitsstrafrecht 266a Und Mindestlohn, Aufsichtsbeschwerde Und Dienstweg, Befangenheit Richter Antrag Sta, Befangenheit Richter Schoeffen un... |
| `kompendium-07-berufung-sta-einlege-bis-btmg-kcang-sitzungsd` | staatsanwaltschaft-praxis-einstieg: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Berufung Sta Einlegen Und Begrenzen, Beweisantraege 244 Stpo Reagieren, Beweisverwertungsverbote Sta, Btmg Kcang Mischfaelle und 1 weitere Ar... |
| `kompendium-08-cybercrime-logfiles-bis-digitale-spuren-mobi` | staatsanwaltschaft-praxis-einstieg: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Cybercrime Logfiles Und Chain Of Custody, Daten Von Plattformen Bestandsdaten, Deal Verstaendigung 257c Stpo Sta, Digitale Durchsuchung Daten... |
| `kompendium-09-durchsuchung-beschla-bis-einziehung-drittbetr` | staatsanwaltschaft-praxis-einstieg: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Durchsuchung Beschlagnahme Antrag, Durchsuchung Kanzlei Arzt Redaktion, Einstellung 153 153a Auflagen, Einstellung 153 153a Stpo und 1 weiter... |
| `kompendium-10-encrochat-anom-sky-e-bis-europaeischer-haftbe` | staatsanwaltschaft-praxis-einstieg: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Encrochat Anom Sky Ecc Krypto, Encrochat Sky Ecc Anom Beweiswert, Entscheidungsvorlage, Ermittlungsvermerk Schreiben und 1 weitere Arbeitsmod... |
| `kompendium-11-geldwaesche-krypto-u-bis-hauptverhandlung-sta` | staatsanwaltschaft-praxis-einstieg: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Geldwaesche Krypto Und Kontoarrest, Haeusliche Gewalt Opferschutz Und Beweis, Haftbefehl Und U Haft Antrag, Hasskriminalitaet Online Und Plat... |
| `kompendium-12-insolvenzverschleppu-bis-koerperverletzung-st` | staatsanwaltschaft-praxis-einstieg: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Insolvenzverschleppung Und Bankrott, Internationaler Beweisimport Verwertung, Jugendstrafrecht Erziehungsziel, Jugendstrafrecht Sta und 1 wei... |
| `kompendium-13-konfliktverteidigung-bis-opfer-und-nebenklage` | staatsanwaltschaft-praxis-einstieg: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Konfliktverteidigung Sitzung Ordnung, Konfliktverteidigung Souveraen, Korruptionsdelikte Amtstraeger Und Healthcare, Mandanten Oder Beteiligt... |
| `kompendium-14-opferrechte-nebenkla-bis-owi-kommunikation-mi` | staatsanwaltschaft-praxis-einstieg: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Opferrechte Nebenklage Adhaesion, Owi Abwesenheit Betroffener 73 74, Owi Beweisaufnahme 77 Und Beweisantraege, Owi Hauptverhandlung Sitzungsd... |
| `kompendium-15-owi-kosten-vollstrec-bis-owi-verjaehrung-verf` | staatsanwaltschaft-praxis-einstieg: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Owi Kosten Vollstreckung Und Ruecknahme, Owi Opportunitaet Einstellung 47, Owi Rechtsbeschwerde 79 80, Owi Verbandsgeldbusse 30 130 und 1 wei... |
| `kompendium-16-owi-verkehrsowi-fahr-bis-plaedoyer-staatsanwa` | staatsanwaltschaft-praxis-einstieg: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Owi Verkehrsowi Fahrverbot Punkte, Owi Vorlage An Amtsgericht Sta Check, Pflichtverteidigung Aus Sta Sicht, Plaedoyer Beweiswuerdigung Strafm... |
| `kompendium-17-polizei-zusammenarbe-bis-rechtshilfe-europaei` | staatsanwaltschaft-praxis-einstieg: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Polizei Zusammenarbeit Ermittlungsauftrag, Presse Und Oeffentlichkeit, Presseauskunft Und Oeffentlichkeit, Protokoll Und Nachbereitung und 1... |
| `kompendium-18-rechtshilfe-internat-bis-schoeffen-befangenhe` | staatsanwaltschaft-praxis-einstieg: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Rechtshilfe International, Ristbv Finden Anwenden, Ristbv Verfuegungstechnik Standard, Sachverstaendige Beauftragen Und Befragen und 1 weiter... |
| `kompendium-19-schriftsatz-vermerk-bis-sitzungsdienst-refer` | staatsanwaltschaft-praxis-einstieg: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Schriftsatz Vermerk Und Mustertext, Sexualdelikte Aussage Gegen Aussage, Sitzungs Und Terminvorbereitung, Sitzungsdienst Amtsgericht und 1 we... |
| `kompendium-20-staatsanwalt-rolle-l-bis-strafbefehl-tagessae` | staatsanwaltschaft-praxis-einstieg: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Staatsanwalt Rolle Legalitaet Objektivitaet, Staatsanwaltschaft Uebergabe Zwischen Dezernaten, Stalking 238 Stgb Gewschg Schnittstelle, Straf... |
| `kompendium-21-u-haft-fluchtgefahr-bis-verkehrsstrafrecht-b` | staatsanwaltschaft-praxis-einstieg: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu U Haft Fluchtgefahr Verhaeltnismaessigkeit, Umweltstrafrecht Behoerdenakten, Untreue Geschaeftsfuehrer Kontoanalyse, Urheber Und Markenstrafr... |
| `kompendium-22-verkehrsstrafrecht-s-bis-waffenrecht-und-spre` | staatsanwaltschaft-praxis-einstieg: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Verkehrsstrafrecht Strafbefehl, Vermoegensarrest Einziehung, Vermoegensarrest Einziehung Schnellcheck, Vollstreckung Und Gnadenschnittstelle... |
| `kompendium-23-wirtschaftsstrafsach-bis-zeugenvernehmung-zeu` | staatsanwaltschaft-praxis-einstieg: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Wirtschaftsstrafsachen Sachleitung, Wohnungsdurchsuchung Gefahr Im Verzug, Zeugenmanagement Und Ladungsrisiken, Zeugenvernehmung Zeugenrechte... |
| `owi-kaltstart-bussgeldverfahren-sta-rolle` | OWiG-Kaltstart: Strafsache oder Ordnungswidrigkeit, Verwaltungsbehörde, Staatsanwaltschaft, Gericht und richtige Verfahrenssprache trennen: OWiG-Praxis-Skill für junge Staatsanwältinnen und Staatsanwälte mit Zuständigkeitscheck, Bußgeldb... |
| `red-team-qualitygate` | Red-Team-Qualitygate: Praxis-Skill für neue Staatsanwälte zu prüft Ergebnis auf Fristenfehler, Zuständigkeitsfehler, Scheinpräzision und Ton; mit Datenschutz-/Aktengeheimniswarnung, RiStBV-/StPO-Quellencheck, Verfügungsvorschlag und näch... |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
