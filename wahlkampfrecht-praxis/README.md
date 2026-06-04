# Wahlkampfrecht Praxis

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`wahlkampfrecht-praxis`) | [`wahlkampfrecht-praxis.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/wahlkampfrecht-praxis.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **Wahlkampfakte Morgenstadt 2026 - Landesliste, Plakatierung und digitale Lage** (`wahlkampfrecht-landtagswahl-morgenstadt-2026`) | [Gesamt-PDF lesen](../testakten/wahlkampfrecht-landtagswahl-morgenstadt-2026/gesamt-pdf/wahlkampfrecht-landtagswahl-morgenstadt-2026_gesamt.pdf) | [`testakte-wahlkampfrecht-landtagswahl-morgenstadt-2026.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-wahlkampfrecht-landtagswahl-morgenstadt-2026.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

Ein großes Arbeitsplugin für demokratische Wahlkampfteams, Parteien, Kandidierende, Wahlkampfmanagerinnen, Kreisverbände, Landesgeschäftsstellen, Bundeswahlkampfstäbe, Kampagnenagenturen und anwaltliche Berater. Es verbindet Recht, Strategie und tägliche Durchführung: Plakatierung, Infostände, Veranstaltungen, Social Media, Daten, Spenden, Kandidatentraining, Krisenkommunikation, Desinformation, Wahltag und Nachbereitung.

Das Plugin soll Kampagnen handlungsfähiger machen, ohne sie zu verrohen. Es hilft bei klarer Message, schneller Lagearbeit und robustem Ground Game. Gleichzeitig zieht es rote Linien: keine Plakat-Sabotage, keine verdeckte Finanzierung, keine rechtswidrige Datennutzung, keine Desinformation, keine fingierten Accounts, keine Irreführung über Wahlverfahren und keine Nutzung staatlicher Ressourcen für Parteizwecke.

## Kaltstart

Starte mit `wahlkampf-allgemeiner-kaltstart` oder `wahlkampf-ebenen-und-wahlart-router`. Das Plugin fragt zuerst:

1. Welche Wahl: Bundestag, Europawahl, Landtag, Kommunalwahl, Bürgermeister-/Landratswahl, innerparteiliche Vorwahl oder Sonderfall?
2. Welche Rolle: Bundesstrategie, Landeswahlkampf, Kreisverband, Kandidatenteam, Agentur, Rechtsabteilung, Schatzmeisterei, Social-Media-Team oder Ehrenamtliche vor Ort?
3. Was ist der Druck: Plakatgenehmigung, Podium, Social-Media-Krise, Spende, Datenschutz, Desinformation, Schulveranstaltung, Wahltag, Behördenbrief oder Strategieplan?
4. Welche Rechtsordnung: Bund, Land, Kommune, Plattform, Datenschutz, Parteienfinanzierung, Strafrecht, Medienrecht, Versammlungsrecht?
5. Welcher Output: Schlachtplan, Freigabecheck, Behördenbrief, Briefing, Risikoampel, Presse-Q&A, Volunteer-Skript, Fristenkalender oder Incident-Log?

## Leitgedanken

- **Demokratisch kampfstark:** klare Strategie, aber keine Manipulation des Wahlverfahrens und keine organisierte Unwahrheit.
- **Recht und Taktik zusammen:** Ein Plakatstandort ist zugleich Sondernutzung, Verkehrssicherheit, Sichtbarkeit, Ehrenamtslogistik und Konfliktrisiko.
- **Resilienz vor Empörung:** Desinformation wird dokumentiert, priorisiert, entkräftet und bei Plattformen/Behörden sauber eskaliert.
- **Authentische Kandidierende:** Nicht alle Menschen sind Medienprofis. Das Plugin trainiert Verhalten unter Kamera, ohne Persönlichkeiten glattzubügeln.
- **Keine falsche Neutralität:** Amtsträger, öffentliche Einrichtungen, Schulen, Verwaltungen und Wahlorgane werden rechtlich sauber getrennt.

## Typische Workflows

| Lage | Einstiegsskills | Ergebnis |
| --- | --- | --- |
| Bundes- oder Landeswahlkampf planen | `wahlkampf-bundesstrategie-architektur`, `wahlkampf-landeswahlkampf-lagekarte`, `wahlkampf-schlachtenplan-ethik-und-taktik` | Strategiepapier, Phasenplan, Risiko-Board |
| Kreisverband muss Plakate hängen | `wahlkampf-plakatierung-genehmigung`, `wahlkampf-plakatstandorte-matrix`, `wahlkampf-fremdplakate-nicht-anruehren` | Standortliste, Teambriefing, Ordnungsamtsmail |
| Social-Media-Krise | `wahlkampf-rapid-response-room`, `wahlkampf-viraler-clip-notfall`, `wahlkampf-faktencheck-gegenrede` | Krisenlog, Q&A, Antwortleiter |
| Politische Online-Werbung | `wahlkampf-eu-2024-900-politische-werbung`, `wahlkampf-targeting-dsgvo`, `wahlkampf-ad-library-transparenz` | Transparenznotiz, Freigabevermerk, Targeting-Ampel |
| Podium mit problematischem Gegner | `wahlkampf-podium-teilnahmeentscheidung`, `wahlkampf-keine-buehne-aber-nicht-fehlen`, `wahlkampf-kandidatenbriefing-kamera` | Teilnahmevermerk, Sprechzettel, Schutzplan |
| Schulen, Jugend, öffentliche Einrichtungen | `wahlkampf-schulen-und-jugendformate`, `wahlkampf-staatliche-neutralitaet`, `wahlkampf-amtstraeger-ressourcen` | Einladungsschreiben, Neutralitätsprüfung, Rollenabgrenzung |
| Wahltag und Wahlraum | `wahlkampf-wahlraum-propagandaverbot`, `wahlkampf-wahlbeobachtung-und-wahltag`, `wahlkampf-briefwahlkommunikation` | Wahltagskarte, Beobachterbriefing, Eskalationspfad |

## Amtliche und frei prüfbare Startquellen

- [Grundgesetz](https://www.gesetze-im-internet.de/gg/) - insbesondere Art. 5, Art. 21 und Wahlrechtsgrundsätze.
- [Bundeswahlgesetz](https://www.gesetze-im-internet.de/bwahlg/) und [Bundeswahlordnung](https://www.gesetze-im-internet.de/bwo_1985/) für Bundestagswahlen.
- [Europawahlgesetz](https://www.gesetze-im-internet.de/euwg/) und [Europawahlordnung](https://www.gesetze-im-internet.de/euwo_1988/) für Europawahlen.
- [Parteiengesetz](https://www.gesetze-im-internet.de/partg/) für Parteienfinanzierung, Spenden, Rechenschaft und Parteiorganisation.
- [Strafgesetzbuch](https://www.gesetze-im-internet.de/stgb/) zu Wahlstraftaten, Nötigung, Beleidigung, Sachbeschädigung und Urkundenthemen.
- [Wahlprüfungsgesetz](https://www.gesetze-im-internet.de/wahlprg/) für Wahlprüfung nach Bundestagswahlen.
- [Bundeswahlleiterin: Wahlwerbung](https://www.bundeswahlleiterin.de/service/glossar/w/wahlwerbung.html), [unzulässige Wahlpropaganda](https://www.bundeswahlleiterin.de/service/glossar/w/wahlpropaganda-unzulaessige.html) und [Fakten gegen Desinformation](https://www.bundeswahlleiterin.de/bundestagswahlen/2025/fakten-desinformation.html).
- [Deutscher Bundestag: Parteienfinanzierung](https://www.bundestag.de/parlament/praesidium/parteienfinanzierung) und [Parteispenden über 35.000 EUR](https://www.bundestag.de/parteispenden).
- [EU-Kommission: Transparency and targeting of political advertising](https://commission.europa.eu/strategy-and-policy/policies/justice-and-fundamental-rights/democracy-eu-citizenship-anti-corruption/democracy-and-electoral-rights/transparency-and-targeting-political-advertising_en) zur Verordnung (EU) 2024/900, die seit 10. Oktober 2025 voll gilt.
- [DSGVO](https://eur-lex.europa.eu/eli/reg/2016/679/oj) und [BDSG](https://www.gesetze-im-internet.de/bdsg_2018/) für Datenverarbeitung im Wahlkampf.
- Lokale Plakatierungs-, Sondernutzungs- und Veranstaltungsregeln der jeweiligen Gemeinde; diese müssen immer aktuell am konkreten Ort geprüft werden.

## Quellenhygiene

Rechtsprechung nur mit Gericht, Entscheidungsform, Datum, Aktenzeichen und frei zugänglicher Quelle. Keine BeckRS-, juris-, Kommentar- oder Aufsatzfundstellen aus Modellwissen. Bei Landeswahlrecht, Plakatierungsfristen, Sondernutzung, Schulen und Kommunalrecht zwingend die konkrete Gemeinde und das Bundesland live prüfen.

## Datenschutz und Kampagnensicherheit

Keine echten Wählerdaten, Mitgliederdaten, Spenderlisten, Social-Media-Profile, Gesundheitsdaten, politische Meinungsdaten oder internen Kampagnengeheimnisse in ungeprüfte Systeme laden. Das Plugin ist ein Arbeits- und Demonstrationsrahmen; produktiver Einsatz braucht Datenschutz-, Berufsrechts-, Parteienfinanzierungs- und IT-Sicherheitsprüfung.

## Lizenz

Apache-2.0 OR MIT. Siehe Repository-Stammverzeichnis.

<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 25 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `kompendium-01-wahlkampf-wahlverfah-bis-wahlkampf-ad-library` | wahlkampfrecht-praxis: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Wahlkampf Wahlverfahren Falschinfo, Wahlkampf Wahlvorschlaege Fristen, Wahlkampf Agenturvertrag Compliance, Wahlkampf 72 Stunden Sprint und 1 weitere Arbe... |
| `kompendium-02-wahlkampf-aktenplan-bis-wahlkampf-archivieru` | wahlkampfrecht-praxis: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Wahlkampf Aktenplan Und Beweisarchiv, Wahlkampf Amtstraeger Ressourcen, Wahlkampf Angriff Auf Wahlleitung Vermeiden, Wahlkampf Arbeitsrecht Kampagnenteam... |
| `kompendium-03-wahlkampf-asymmetris-bis-wahlkampf-briefkaste` | wahlkampfrecht-praxis: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Wahlkampf Asymmetrische Demobilisierung, Wahlkampf Barrierefreie Und Mehrsprachige Information, Wahlkampf Barrierefreiheit Und Inklusion, Wahlkampf Bots U... |
| `kompendium-04-wahlkampf-briefwahlk-bis-wahlkampf-compliance` | wahlkampfrecht-praxis: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Wahlkampf Briefwahlkommunikation, Wahlkampf Buergerdialog Schwierige Fragen, Wahlkampf Bundesstrategie Architektur, Wahlkampf Community Management und 1 w... |
| `kompendium-05-wahlkampf-cybersiche-bis-wahlkampf-desinforma` | wahlkampfrecht-praxis: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Wahlkampf Cybersicherheit Kampagne, Wahlkampf Datenschutz Folgenabschaetzung Politische Daten, Wahlkampf Debattenvorbereitung, Wahlkampf Deepfake Und Ki K... |
| `kompendium-06-wahlkampf-ebenen-und-bis-wahlkampf-flooding-g` | wahlkampfrecht-praxis: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Wahlkampf Ebenen Und Wahlart Router, Wahlkampf Ehrenamtliche Schulen, Wahlkampf Eu 2024 900 Politische Werbung, Wahlkampf Faktencheck Gegenrede und 1 weit... |
| `kompendium-07-wahlkampf-foreign-in-bis-wahlkampf-fremdplaka` | wahlkampfrecht-praxis: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Wahlkampf Foreign Interference Lage, Wahlkampf Foto Im Wahlraum Und Stimmzettel, Wahlkampf Fraktion Partei Trennung, Wahlkampf Freiwillige Und Aufwandsers... |
| `kompendium-08-wahlkampf-gegnerkrit-bis-wahlkampf-hausrecht` | wahlkampfrecht-praxis: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Wahlkampf Gegnerkritik Meinungsfreiheit, Wahlkampf Gewerkschaften Verbaende Kirchen, Wahlkampf Giveaways Waehlerbestechung, Wahlkampf Grossspenden Sofortm... |
| `kompendium-09-wahlkampf-haustuerwa-bis-wahlkampf-kandidaten` | wahlkampfrecht-praxis: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Wahlkampf Haustuerwahlkampf, Wahlkampf Influencer Und Unterstuetzer, Wahlkampf Infostand Sondernutzung, Wahlkampf Interne Chatdisziplin und 1 weitere Arbe... |
| `kompendium-10-wahlkampf-kandidaten-bis-wahlkampf-keine-bueh` | wahlkampfrecht-praxis: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Wahlkampf Kandidatenbriefing Kamera, Wahlkampf Kandidatenteam Intake, Wahlkampf Kandidierenden Fuersorge, Wahlkampf Kassenpruefung Kreisverband und 1 weit... |
| `kompendium-11-wahlkampf-koalitions-bis-wahlkampf-lagebild-m` | wahlkampfrecht-praxis: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Wahlkampf Koalitionssignale Und Rote Linien, Wahlkampf Kommunalwahlkampf Groundgame, Wahlkampf Kostenversprechen Und Finanzierbarkeit, Wahlkampf Krisensta... |
| `kompendium-12-wahlkampf-landeslist-bis-wahlkampf-leak-und-h` | wahlkampfrecht-praxis: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Wahlkampf Landeslisten Und Direktkandidaten, Wahlkampf Landesrecht Plakatierung Livecheck, Wahlkampf Landeswahlkampf Lagekarte, Wahlkampf Lautsprecher Fah... |
| `kompendium-13-wahlkampf-lokale-bue-bis-wahlkampf-minderjaeh` | wahlkampfrecht-praxis: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Wahlkampf Lokale Buendnisse Und Listen, Wahlkampf Marken Und Fremdlogos, Wahlkampf Memes Satire Risiko, Wahlkampf Message House Authentizitaet und 1 weite... |
| `kompendium-14-wahlkampf-nachwahl-e-bis-wahlkampf-opposition` | wahlkampfrecht-praxis: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Wahlkampf Nachwahl Evaluation, Wahlkampf Negative Campaigning Grenzen, Wahlkampf Newsletter Messenger Sms, Wahlkampf Oeffentliche Einrichtungen Nutzung un... |
| `kompendium-15-wahlkampf-ordner-und-bis-wahlkampf-plakatstan` | wahlkampfrecht-praxis: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Wahlkampf Ordner Und Sicherheit, Wahlkampf Parteieigenschaft Bundeswahlausschuss, Wahlkampf Plakat Vandalismus Beweissicherung, Wahlkampf Plakatierung Gen... |
| `kompendium-16-wahlkampf-plattformm-bis-wahlkampf-presserech` | wahlkampfrecht-praxis: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Wahlkampf Plattformmeldung Dsa, Wahlkampf Podium Teilnahmeentscheidung, Wahlkampf Polizei Und Ordnungsamt Kommunikation, Wahlkampf Presseanfrage Antwortle... |
| `kompendium-17-wahlkampf-rapid-resp-bis-wahlkampf-rumor-cont` | wahlkampfrecht-praxis: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Wahlkampf Rapid Response Room, Wahlkampf Rechenschaftsbericht Vorbereitung, Wahlkampf Rechtsfreigabe Gate, Wahlkampf Risiko Register und 1 weitere Arbeits... |
| `kompendium-18-wahlkampf-satelliten-bis-wahlkampf-social-med` | wahlkampfrecht-praxis: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Wahlkampf Satellitenkampagne Durch Verein, Wahlkampf Schlachtenplan Ethik Und Taktik, Wahlkampf Schulen Und Jugendformate, Wahlkampf Sicherheitslage Kandi... |
| `kompendium-19-wahlkampf-spendenann-bis-wahlkampf-taegliches` | wahlkampfrecht-praxis: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Wahlkampf Spendenannahme Pruefung, Wahlkampf Sponsoring Parteienrecht, Wahlkampf Sprachregelung Schnellkarte, Wahlkampf Staatliche Neutralitaet und 1 weit... |
| `kompendium-20-wahlkampf-targeting-bis-wahlkampf-umgang-mit` | wahlkampfrecht-praxis: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Wahlkampf Targeting Dsgvo, Wahlkampf Tracking Pixel Cookies, Wahlkampf Ueberkleben Sachbeschaedigung, Wahlkampf Umfragen Und Prognosen und 1 weitere Arbei... |
| `kompendium-21-wahlkampf-unterstuet-bis-wahlkampf-versammlun` | wahlkampfrecht-praxis: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Wahlkampf Unterstuetzungsunterschriften, Wahlkampf Urheberrecht Musik Bilder Clips, Wahlkampf Veranstaltungslogistik, Wahlkampf Vereine Unterstuetzer Drit... |
| `kompendium-22-wahlkampf-viraler-cl-bis-wahlkampf-wahlkampf` | wahlkampfrecht-praxis: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Wahlkampf Viraler Clip Notfall, Wahlkampf Waehlerdaten Und Listen, Wahlkampf Wahl O Mat Und Thesen, Wahlkampf Wahlbeobachtung Und Wahltag und 1 weitere Ar... |
| `kompendium-23-wahlkampf-wahlkampfk-bis-wahlkampf-wahlstraft` | wahlkampfrecht-praxis: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Wahlkampf Wahlkampfkosten Budget, Wahlkampf Wahlprogramm Und Faktencheck, Wahlkampf Wahlpruefung Nachwahl, Wahlkampf Wahlraum Propagandaverbot und 1 weite... |
| `kompendium-24-wahlkampf-wahltag-kr-bis-wahlkampf-war-room-b` | wahlkampfrecht-praxis: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Wahlkampf Wahltag Krisenkarte, Wahlkampf War Room Betriebsmodell; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätsch... |
| `wahlkampf-allgemeiner-kaltstart` | Wahlkampfrecht Praxis: Kaltstart fuer jede Wahlkampflage mit Routing zu Recht, Strategie, Digital, Plakatierung, Finanzen oder Krise. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
