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
| `wahlkampf-aktenplan-beweisarchiv-amtstraeger` | Nutze dies, wenn Wahlkampf Aktenplan Und Beweisarchiv, Wahlkampf Amtstraeger Ressourcen, Wahlkampf Angriff Auf Wahlleitung Vermeiden, Wahlkampf Arbeitsrecht Kampagnenteam, Wahlkampf Archivierung Screenshots im Plugin Wahlkampfrecht Praxi... |
| `wahlkampf-allgemeiner-kaltstart` | Wahlkampfrecht Praxis: Kaltstart fuer jede Wahlkampflage mit Routing zu Recht, Strategie, Digital, Plakatierung, Finanzen oder Krise. |
| `wahlkampf-asymmetrische-demobilisierung` | Nutze dies, wenn Wahlkampf Asymmetrische Demobilisierung, Wahlkampf Barrierefreie Und Mehrsprachige Information, Wahlkampf Barrierefreiheit Und Inklusion, Wahlkampf Bots Und Inauthentisches Verhalten, Wahlkampf Briefkasten Flyer im Plugi... |
| `wahlkampf-briefwahlkommunikation` | Nutze dies, wenn Wahlkampf Briefwahlkommunikation, Wahlkampf Buergerdialog Schwierige Fragen, Wahlkampf Bundesstrategie Architektur, Wahlkampf Community Management, Wahlkampf Compliance Schulung Vorstand im Plugin Wahlkampfrecht Praxis k... |
| `wahlkampf-cybersicherheit-kampagne` | Nutze dies, wenn Wahlkampf Cybersicherheit Kampagne, Wahlkampf Datenschutz Folgenabschaetzung Politische Daten, Wahlkampf Debattenvorbereitung, Wahlkampf Deepfake Und Ki Kennzeichnung, Wahlkampf Desinformation Monitoring im Plugin Wahlka... |
| `wahlkampf-ebenen-wahlart-ehrenamtliche` | Nutze dies, wenn Wahlkampf Ebenen Und Wahlart Router, Wahlkampf Ehrenamtliche Schulen, Wahlkampf Eu 2024 900 Politische Werbung, Wahlkampf Faktencheck Gegenrede, Wahlkampf Flooding Gegenrede Statt Muell im Plugin Wahlkampfrecht Praxis ko... |
| `wahlkampf-foreign-interference-foto-wahlraum` | Nutze dies, wenn Wahlkampf Foreign Interference Lage, Wahlkampf Foto Im Wahlraum Und Stimmzettel, Wahlkampf Fraktion Partei Trennung, Wahlkampf Freiwillige Und Aufwandsersatz, Wahlkampf Fremdplakate Nicht Anruehren im Plugin Wahlkampfrec... |
| `wahlkampf-gegnerkritik-meinungsfreiheit` | Nutze dies, wenn Wahlkampf Gegnerkritik Meinungsfreiheit, Wahlkampf Gewerkschaften Verbaende Kirchen, Wahlkampf Giveaways Waehlerbestechung, Wahlkampf Grossspenden Sofortmeldung, Wahlkampf Hausrecht Privatraeume im Plugin Wahlkampfrecht... |
| `wahlkampf-haustuerwahlkampf-influencer` | Nutze dies, wenn Wahlkampf Haustuerwahlkampf, Wahlkampf Influencer Und Unterstuetzer, Wahlkampf Infostand Sondernutzung, Wahlkampf Interne Chatdisziplin, Wahlkampf Kandidaten Altposts Screening im Plugin Wahlkampfrecht Praxis konkret bea... |
| `wahlkampf-kandidatenbriefing-kamera` | Nutze dies, wenn Wahlkampf Kandidatenbriefing Kamera, Wahlkampf Kandidatenteam Intake, Wahlkampf Kandidierenden Fuersorge, Wahlkampf Kassenpruefung Kreisverband, Wahlkampf Keine Buehne Aber Nicht Fehlen im Plugin Wahlkampfrecht Praxis ko... |
| `wahlkampf-koalitionssignale-kommunalwahlkampf` | Nutze dies, wenn Wahlkampf Koalitionssignale Und Rote Linien, Wahlkampf Kommunalwahlkampf Groundgame, Wahlkampf Kostenversprechen Und Finanzierbarkeit, Wahlkampf Krisenstatement Fehler Eigener Leute, Wahlkampf Lagebild Medienresonanz im... |
| `wahlkampf-landeslisten-direktkandidaten` | Nutze dies, wenn Wahlkampf Landeslisten Und Direktkandidaten, Wahlkampf Landesrecht Plakatierung Livecheck, Wahlkampf Landeswahlkampf Lagekarte, Wahlkampf Lautsprecher Fahrzeug, Wahlkampf Leak Und Hack Notfall im Plugin Wahlkampfrecht Pr... |
| `wahlkampf-lokale-buendnisse-marken-fremdlogos` | Nutze dies, wenn Wahlkampf Lokale Buendnisse Und Listen, Wahlkampf Marken Und Fremdlogos, Wahlkampf Memes Satire Risiko, Wahlkampf Message House Authentizitaet, Wahlkampf Minderjaehrige Und Fotos im Plugin Wahlkampfrecht Praxis konkret b... |
| `wahlkampf-nachwahl-evaluation-negative` | Nutze dies, wenn Wahlkampf Nachwahl Evaluation, Wahlkampf Negative Campaigning Grenzen, Wahlkampf Newsletter Messenger Sms, Wahlkampf Oeffentliche Einrichtungen Nutzung, Wahlkampf Opposition Research Compliance im Plugin Wahlkampfrecht P... |
| `wahlkampf-ordner-sicherheit-parteieigenschaft` | Nutze dies, wenn Wahlkampf Ordner Und Sicherheit, Wahlkampf Parteieigenschaft Bundeswahlausschuss, Wahlkampf Plakat Vandalismus Beweissicherung, Wahlkampf Plakatierung Genehmigung, Wahlkampf Plakatstandorte Matrix im Plugin Wahlkampfrech... |
| `wahlkampf-plattformmeldung-dsa-podium` | Nutze dies, wenn Wahlkampf Plattformmeldung Dsa, Wahlkampf Podium Teilnahmeentscheidung, Wahlkampf Polizei Und Ordnungsamt Kommunikation, Wahlkampf Presseanfrage Antwortleiter, Wahlkampf Presserecht Richtigstellung im Plugin Wahlkampfrec... |
| `wahlkampf-rapid-response-rechenschaftsbericht` | Nutze dies, wenn Wahlkampf Rapid Response Room, Wahlkampf Rechenschaftsbericht Vorbereitung, Wahlkampf Rechtsfreigabe Gate, Wahlkampf Risiko Register, Wahlkampf Rumor Control Center im Plugin Wahlkampfrecht Praxis konkret bearbeitet werd... |
| `wahlkampf-satellitenkampagne-durch` | Nutze dies, wenn Wahlkampf Satellitenkampagne Durch Verein, Wahlkampf Schlachtenplan Ethik Und Taktik, Wahlkampf Schulen Und Jugendformate, Wahlkampf Sicherheitslage Kandidierende, Wahlkampf Social Media Redaktionsplan im Plugin Wahlkamp... |
| `wahlkampf-spendenannahme-sponsoring` | Nutze dies, wenn Wahlkampf Spendenannahme Prüfung, Wahlkampf Sponsoring Parteienrecht, Wahlkampf Sprachregelung Schnellkarte, Wahlkampf Staatliche Neutralitaet, Wahlkampf Taegliches Briefing im Plugin Wahlkampfrecht Praxis konkret bearbe... |
| `wahlkampf-targeting-dsgvo-tracking-pixel` | Nutze dies, wenn Wahlkampf Targeting Dsgvo, Wahlkampf Tracking Pixel Cookies, Wahlkampf Ueberkleben Sachbeschaedigung, Wahlkampf Umfragen Und Prognosen, Wahlkampf Umgang Mit Provokateuren im Plugin Wahlkampfrecht Praxis konkret bearbeite... |
| `wahlkampf-unterstuetzungsunterschriften` | Nutze dies, wenn Wahlkampf Unterstuetzungsunterschriften, Wahlkampf Urheberrecht Musik Bilder Clips, Wahlkampf Veranstaltungslogistik, Wahlkampf Vereine Unterstuetzer Dritte, Wahlkampf Versammlungsrecht Schnittstelle im Plugin Wahlkampfr... |
| `wahlkampf-viraler-clip-waehlerdaten-listen` | Nutze dies, wenn Wahlkampf Viraler Clip Notfall, Wahlkampf Waehlerdaten Und Listen, Wahlkampf Wahl O Mat Und Thesen, Wahlkampf Wahlbeobachtung Und Wahltag, Wahlkampf Wahlkampf In Vereinen Und Betrieben im Plugin Wahlkampfrecht Praxis kon... |
| `wahlkampf-wahlkampfkosten-budget-wahlprogramm` | Nutze dies, wenn Wahlkampf Wahlkampfkosten Budget, Wahlkampf Wahlprogramm Und Faktencheck, Wahlkampf Wahlpruefung Nachwahl, Wahlkampf Wahlraum Propagandaverbot, Wahlkampf Wahlstraftaten Stgb im Plugin Wahlkampfrecht Praxis konkret bearbe... |
| `wahlkampf-wahltag-wahlkampf-war` | Nutze dies, wenn Wahlkampf Wahltag Krisenkarte, Wahlkampf War Room Betriebsmodell im Plugin Wahlkampfrecht Praxis konkret bearbeitet werden soll. Auslöser: Bitte Wahlkampf Wahltag Krisenkarte, Wahlkampf War Room Betriebsmodell prüfen.; E... |
| `wahlkampf-wahlverfahren-falschinfo` | Nutze dies, wenn Wahlkampf Wahlverfahren Falschinfo, Wahlkampf Wahlvorschlaege Fristen, Wahlkampf Agenturvertrag Compliance, Wahlkampf 72 Stunden Sprint, Wahlkampf Ad Library Transparenz im Plugin Wahlkampfrecht Praxis konkret bearbeitet... |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
