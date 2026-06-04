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
| `gefahrenprognose-redteam` | Zerlegt die behördliche Gefahrenprognose und baut eine eigene, realistische Sicherheitslage auf. |
| `kompendium-01-frist-48-stunden-bek-bis-kosten-haftung-und-v` | versammlungsrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Frist 48 Stunden Bekanntgabe, Kosten Haftung Und Versicherung; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck. |
| `kompendium-02-anwaltlicher-brief-a-bis-anzeige-unter-freiem` | versammlungsrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Anwaltlicher Brief An Behoerde, Anzeige Unter Freiem Himmel; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck. |
| `kompendium-03-auflagen-pruefen-bis-auflagenverstoss-und` | versammlungsrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Auflagen Pruefen, Auflagenverstoss Und Owi; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck. |
| `kompendium-04-bannmeile-schutzbere-bis-barrierefreiheit-und` | versammlungsrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Bannmeile Schutzbereiche, Barrierefreiheit Und Inklusion; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck. |
| `kompendium-05-behoerdenkommunikati-bis-bekanntgabe-social-m` | versammlungsrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Behoerdenkommunikation, Bekanntgabe Social Media; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck. |
| `kompendium-06-bescheid-lesen-bis-beweissicherung-am-v` | versammlungsrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Bescheid Lesen, Beweissicherung Am Versammlungstag; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck. |
| `kompendium-07-blockade-sitzblockad-bis-bundeslaender-synops` | versammlungsrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Blockade Sitzblockade Friedlichkeit, Bundeslaender Synopse; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck. |
| `kompendium-08-camp-dauerversammlun-bis-datenschutz-fotos-li` | versammlungsrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Camp Dauerversammlung, Datenschutz Fotos Livestream; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck. |
| `kompendium-09-dritte-anwohner-laer-bis-eilversammlung` | versammlungsrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Dritte Anwohner Laerm Geschaeft, Eilversammlung; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck. |
| `kompendium-10-eingangsbestaetigung-bis-falscher-tag-falsche` | versammlungsrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Eingangsbestaetigung Und Aktenzeichen, Falscher Tag Falscher Ort Einwand; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitä... |
| `kompendium-11-gegenveranstaltung-u-bis-infostand-mahnwache` | versammlungsrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Gegenveranstaltung Und Trennung, Infostand Mahnwache Kleinstversammlung; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualität... |
| `kompendium-12-innenraum-versammlun-bis-kooperationsgespraec` | versammlungsrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Innenraum Versammlung Abgrenzen, Kooperationsgespraech; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck. |
| `kompendium-13-kundgebung-stationae-bis-landesrecht-und-beho` | versammlungsrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Kundgebung Stationaer Platzwahl, Landesrecht Und Behoerde Finden; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck. |
| `kompendium-14-leiter-verantwortung-bis-mildere-mittel-matri` | versammlungsrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Leiter Verantwortung, Mildere Mittel Matrix; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck. |
| `kompendium-15-muster-anzeige-gener-bis-muster-eilantrag` | versammlungsrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Muster Anzeige Generator, Muster Eilantrag; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck. |
| `kompendium-16-nachbereitung-und-ak-bis-notfallkarte-versamm` | versammlungsrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Nachbereitung Und Aktenvermerk, Notfallkarte Versammlungstag; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck. |
| `kompendium-17-offizielle-quellen-l-bis-ordner-auswahl` | versammlungsrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Offizielle Quellen Livecheck, Ordner Auswahl; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck. |
| `kompendium-18-ordnerliste-und-mitt-bis-partei-gewerkschaft` | versammlungsrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Ordnerliste Und Mitteilung, Partei Gewerkschaft Verein Veranstalter; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck. |
| `kompendium-19-polizei-vor-ort-dees-bis-polizeifilmerei-bewe` | versammlungsrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Polizei Vor Ort Deeskalation, Polizeifilmerei Beweissicherung Kug 201 Stgb; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Quali... |
| `kompendium-20-presse-und-oeffentli-bis-privat-oeffentlich-a` | versammlungsrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Presse Und Oeffentlichkeitsarbeit, Privat Oeffentlich Abgrenzen; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck. |
| `kompendium-21-qualitaetsgate-vor-b-bis-route-aufzug-und-str` | versammlungsrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Qualitaetsgate Vor Bekanntgabe, Route Aufzug Und Streckenplanung; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck. |
| `kompendium-22-schule-universitaet-bis-schutz-vor-vorauseil` | versammlungsrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Schule Universitaet Jugendliche, Schutz Vor Vorauseilendem Gehorsam; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck. |
| `kompendium-23-spontanversammlung-bis-strafrecht-versg-ris` | versammlungsrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Spontanversammlung, Strafrecht Versg Risiken; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck. |
| `kompendium-24-technik-lautsprecher-bis-untatigkeit-und-schw` | versammlungsrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Technik Lautsprecher Musik, Untatigkeit Und Schweigen; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck. |
| `kompendium-25-verbot-und-beschraen-bis-verkehr-rettungswege` | versammlungsrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Verbot Und Beschraenkung Abwehren, Verkehr Rettungswege Oepnv; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck. |
| `kompendium-26-versammlungskonzept-bis-wahlkampf-und-politi` | versammlungsrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Versammlungskonzept, Wahlkampf Und Politische Kundgebung; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck. |
| `kompendium-27-widerspruch-klage-ei-bis-widerspruch-klage-ei` | versammlungsrecht: eigenständiger Arbeits-Skill zu Widerspruch Klage Eilrechtsschutz; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
