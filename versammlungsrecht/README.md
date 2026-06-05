# Versammlungsrecht

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`versammlungsrecht`) | [`versammlungsrecht.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/versammlungsrecht.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **Verfassungsbeschwerde Klimacamp Initiative Saarbruecken — Art. 8 GG / Versammlungsfreiheit / Bannmeile Landtag** (`verfassungsbeschwerde-versammlungsfreiheit-klimacamp-saarbruecken-art-8-gg-tannenberg`) | [Gesamt-PDF lesen](../testakten/verfassungsbeschwerde-versammlungsfreiheit-klimacamp-saarbruecken-art-8-gg-tannenberg/gesamt-pdf/verfassungsbeschwerde-versammlungsfreiheit-klimacamp-saarbruecken-art-8-gg-tannenberg_gesamt.pdf) | [`testakte-verfassungsbeschwerde-versammlungsfreiheit-klimacamp-saarbruecken-art-8-gg-tannenberg.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-verfassungsbeschwerde-versammlungsfreiheit-klimacamp-saarbruecken-art-8-gg-tannenberg.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

Praxisplugin für Menschen, Organisationen und anwaltliche Teams, die eine Versammlung unter freiem Himmel, einen Aufzug, eine Mahnwache, ein Camp oder eine konfliktträchtige Kundgebung rechtlich sauber anzeigen, durchführen oder gegen Behördeneingriffe verteidigen wollen.

Das Plugin denkt Versammlungsrecht nicht als Bittgang zur Behörde. Es startet bei Art. 8 GG: friedlich, ohne Waffen, grundsätzlich ohne Erlaubnis. Zugleich nimmt es ernst, dass Versammlungen im öffentlichen Raum geplant werden müssen: richtige Behörde, richtige Frist, klare Leitung, Ordner, Route, Technik, Rettungswege, Kooperationsgespräch, Auflagenprüfung und Eilrechtsschutz, wenn die Behörde ausweicht oder überzieht.

## Kaltstart

1. **Wo?** Bundesland, Stadt, Route, Platz, Bannmeile, mehrere Behördenbezirke?
2. **Was?** Außenversammlung, Aufzug, Innenversammlung, private Runde, Mahnwache, Infostand, Camp, Gegenversammlung?
3. **Wann?** Termin, Bekanntgabezeitpunkt, Einladung, Social-Media-Post, Eil- oder Spontanversammlung?
4. **Wer?** Veranstalter, Leitung, Stellvertretung, Ordner, Organisation, Kontaktkanal?
5. **Wofür?** Anzeige erstellen, Behördenfragen beantworten, Auflagen prüfen, Verbot abwehren, Eilrechtsschutz, Tag-der-Versammlung-Plan?

## Leitgedanke

- **Anzeige statt Genehmigung:** Öffentliche Versammlungen unter freiem Himmel werden angezeigt; die Behörde soll planen und schützen, nicht politisch vorsortieren.
- **Landesrecht zuerst:** Viele Länder haben eigene Versammlungsgesetze. Das Plugin fragt deshalb immer nach Ort und Bundesland.
- **Kooperation ohne Selbstzensur:** Behördenbelange werden ernst genommen, aber Ort, Zeit, Thema und Ausdrucksform bleiben Teil der grundrechtlich geschützten Versammlung.
- **Konkrete Gefahr statt Behördenbauchgefühl:** Auflagen und Verbote müssen tatsachenbasiert und verhältnismäßig sein.
- **Schnelle Outputs:** Anzeige, Ordnerliste, Kooperationsagenda, Behördenbrief, Eilantrag, Notfallkarte und Nachbereitungsvermerk.

## Typische Outputs

| Situation | Passende Skills | Ergebnis |
| --- | --- | --- |
| Versammlung normal planen | `allgemein`, `landesrecht-und-behoerde-finden`, `anzeige-unter-freiem-himmel`, `muster-anzeige-generator` | Anzeige, Fristplan, Behördenkontakt |
| Einladung soll heute raus | `frist-48-stunden-bekanntgabe`, `bekanntgabe-social-media`, `qualitaetsgate-vor-bekanntgabe` | Kommunikationskalender und Go/No-Go |
| Spontane oder eilige Demo | `spontanversammlung`, `eilversammlung`, `behoerdenkommunikation` | Kurzmeldung, Aktenvermerk, Polizeisprechzettel |
| Behörde will verlegen oder verbieten | `auflagen-pruefen`, `falscher-tag-falscher-ort-einwand`, `verbot-und-beschraenkung-abwehren`, `muster-eilantrag` | Gegenbrief und Eilrechtsschutz-Gerüst |
| Ordner und Tag selbst | `ordner-auswahl`, `ordnerliste-und-mitteilung`, `polizei-vor-ort-deeskalation`, `notfallkarte-versammlungstag` | Briefing, Liste, Notfallkarte |
| Camp, Technik, Verkehr | `camp-dauerversammlung`, `technik-lautsprecher-musik`, `verkehr-rettungswege-oepnv` | Konzept und mildere Mittel |

## Quellenstrategie

- **Bundesrecht:** Art. 8 GG, Versammlungsgesetz, VwGO.
- **Landesrecht:** jeweiliges Landesversammlungsgesetz und Zuständigkeitsregel.
- **Behördenpraxis:** offizielle Onlineformulare und Hinweise der konkreten Versammlungsbehörde.
- **Rechtsprechung:** nur mit Gericht, Datum, Aktenzeichen und frei überprüfbarem Link.
- **Keine Blindzitate:** keine BeckRS-, juris-, Kommentar- oder Aufsatzfundstellen aus Modellwissen.

## Berufs- und Datenschutzhinweis

Bei echten Mandaten keine sensiblen personenbezogenen Daten, politischen Mitgliedschaften, Teilnehmerlisten oder Behördenakten in ungeprüfte Systeme laden. Ordnerlisten, Minderjährigendaten, Gesundheitsdaten und Polizeikommunikation sind datensensibel. Für produktiven Kanzleieinsatz ist das jeweils eigene Datenschutz-, Berufsrechts- und Hosting-Setup maßgeblich.

## Lizenz

Apache-2.0 OR MIT. Siehe Repository-Stammverzeichnis.


<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 29 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `allgemein` | Allgemeiner Kaltstart im Versammlungsrecht: Land und Ort, Art der Versammlung, Frist, Behörde, Risiko und Ziel klären, dann passende Spezialskills und nächsten Output auswählen. |
| `anwaltlicher-an-anzeige-unter` | Anwaltlicher Brief An Behörde, Anzeige Unter Freiem Himmel: Anwaltlicher Brief An Behörde; Anzeige Unter Freiem Himmel. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zusammen. |
| `auflagen-auflagenverstoss-owi` | Auflagen Prüfen, Auflagenverstoss Und Owi: Auflagen Prüfen; Auflagenverstoss Und Owi. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zusammen. |
| `bannmeile-schutzbereiche-barrierefreiheit-inklusion` | Bannmeile Schutzbereiche, Barrierefreiheit Und Inklusion: Bannmeile Schutzbereiche; Barrierefreiheit Und Inklusion. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zusammen. |
| `behoerdenkommunikation-bekanntgabe-social` | Behoerdenkommunikation, Bekanntgabe Social Media: Behoerdenkommunikation; Bekanntgabe Social Media. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zusammen. |
| `bescheid-lesen-beweissicherung-am` | Bescheid Lesen, Beweissicherung Am Versammlungstag: Bescheid Lesen; Beweissicherung Am Versammlungstag. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zusammen. |
| `blockade-sitzblockade-bundeslaender-synopse` | Blockade Sitzblockade Friedlichkeit, Bundeslaender Synopse: Blockade Sitzblockade Friedlichkeit; Bundeslaender Synopse. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zusammen. |
| `camp-dauerversammlung-datenschutz-fotos` | Camp Dauerversammlung, Datenschutz Fotos Livestream: Camp Dauerversammlung; Datenschutz Fotos Livestream. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zusammen. |
| `dritte-anwohner-eilversammlung` | Dritte Anwohner Laerm Geschaeft, Eilversammlung: Dritte Anwohner Laerm Geschaeft; Eilversammlung. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zusammen. |
| `eingangsbestaetigung-aktenzeichen-falscher-tag` | Eingangsbestaetigung Und Aktenzeichen, Falscher Tag Falscher Ort Einwand: Eingangsbestaetigung Und Aktenzeichen; Falscher Tag Falscher Ort Einwand. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätsc... |
| `frist-stunden-kosten-haftung` | Frist 48 Stunden Bekanntgabe, Kosten Haftung Und Versicherung: Frist 48 Stunden Bekanntgabe; Kosten Haftung Und Versicherung. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zusammen. |
| `gefahrenprognose-redteam` | Zerlegt die behördliche Gefahrenprognose und baut eine eigene, realistische Sicherheitslage auf. |
| `gegenveranstaltung-trennung-infostand-mahnwache` | Gegenveranstaltung Und Trennung, Infostand Mahnwache Kleinstversammlung: Gegenveranstaltung Und Trennung; Infostand Mahnwache Kleinstversammlung. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätsche... |
| `innenraum-versammlung-kooperationsgespraech` | Innenraum Versammlung Abgrenzen, Kooperationsgespraech: Innenraum Versammlung Abgrenzen; Kooperationsgespraech. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zusammen. |
| `kundgebung-stationaer-landesrecht-behoerde` | Kundgebung Stationaer Platzwahl, Landesrecht Und Behörde Finden: Kundgebung Stationaer Platzwahl; Landesrecht Und Behörde Finden. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zusammen. |
| `leiter-verantwortung-mildere-mittel` | Leiter Verantwortung, Mildere Mittel Matrix: Leiter Verantwortung; Mildere Mittel Matrix. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zusammen. |
| `muster-anzeige-muster-eilantrag` | Muster Anzeige Generator, Muster Eilantrag: Muster Anzeige Generator; Muster Eilantrag. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zusammen. |
| `nachbereitung-aktenvermerk-notfallkarte-versammlungstag` | Nachbereitung Und Aktenvermerk, Notfallkarte Versammlungstag: Nachbereitung Und Aktenvermerk; Notfallkarte Versammlungstag. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zusammen. |
| `offizielle-quellen-ordner-auswahl` | Offizielle Quellen Livecheck, Ordner Auswahl: Offizielle Quellen Livecheck; Ordner Auswahl. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zusammen. |
| `ordnerliste-mitteilung-partei-gewerkschaft` | Ordnerliste Und Mitteilung, Partei Gewerkschaft Verein Veranstalter: Ordnerliste Und Mitteilung; Partei Gewerkschaft Verein Veranstalter. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zusam... |
| `polizei-ort-polizeifilmerei-beweissicherung` | Polizei Vor Ort Deeskalation, Polizeifilmerei Beweissicherung Kug 201 Stgb: Polizei Vor Ort Deeskalation; Polizeifilmerei Beweissicherung Kug 201 Stgb. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualit... |
| `presse-oeffentlichkeitsarbeit-privat-oeffentlich` | Presse Und Oeffentlichkeitsarbeit, Privat Öffentlich Abgrenzen: Presse Und Oeffentlichkeitsarbeit; Privat Öffentlich Abgrenzen. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zusammen. |
| `qualitaetsgate-bekanntgabe-route-aufzug` | Qualitaetsgate Vor Bekanntgabe, Route Aufzug Und Streckenplanung: Qualitaetsgate Vor Bekanntgabe; Route Aufzug Und Streckenplanung. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zusammen. |
| `schule-universitaet-schutz-vorauseilendem` | Schule Universitaet Jugendliche, Schutz Vor Vorauseilendem Gehorsam: Schule Universitaet Jugendliche; Schutz Vor Vorauseilendem Gehorsam. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zusam... |
| `spontanversammlung-strafrecht-versg` | Spontanversammlung, Strafrecht Versg Risiken: Spontanversammlung; Strafrecht Versg Risiken. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zusammen. |
| `technik-lautsprecher-untatigkeit-schweigen` | Technik Lautsprecher Musik, Untatigkeit Und Schweigen: Technik Lautsprecher Musik; Untatigkeit Und Schweigen. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zusammen. |
| `verbot-beschraenkung-verkehr-rettungswege` | Verbot Und Beschraenkung Abwehren, Verkehr Rettungswege Oepnv: Verbot Und Beschraenkung Abwehren; Verkehr Rettungswege Oepnv. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zusammen. |
| `versammlungskonzept-wahlkampf-politische` | Versammlungskonzept, Wahlkampf Und Politische Kundgebung: Versammlungskonzept; Wahlkampf Und Politische Kundgebung. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zusammen. |
| `widerspruch-klage` | Widerspruch Klage Eilrechtsschutz: Widerspruch Klage Eilrechtsschutz. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zusammen. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
