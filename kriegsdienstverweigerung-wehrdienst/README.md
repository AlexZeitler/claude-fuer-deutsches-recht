# Kriegsdienstverweigerung und Wehrdienst

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`kriegsdienstverweigerung-wehrdienst`) | [`kriegsdienstverweigerung-wehrdienst.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/kriegsdienstverweigerung-wehrdienst.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **KDV-Verfahren Malte Eberhard Rabenow / Berlin-Köln 2026** (`kriegsdienstverweigerung-gewissensantrag-berlin-2026`) | [Gesamt-PDF lesen](../testakten/kriegsdienstverweigerung-gewissensantrag-berlin-2026/gesamt-pdf/kriegsdienstverweigerung-gewissensantrag-berlin-2026_gesamt.pdf) | [`testakte-kriegsdienstverweigerung-gewissensantrag-berlin-2026.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-kriegsdienstverweigerung-gewissensantrag-berlin-2026.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

Praxisplugin für Kriegsdienstverweigerung aus Gewissensgründen nach Art. 4 Abs. 3 GG und KDVG. Es ist ausdrücklich kein Plugin für Totalverweigerung, Dienstflucht, Befehlsboykott oder politische Leistungsverweigerung. Es behandelt die verfassungsrechtlich loyale Inanspruchnahme eines Grundrechts: Wer nicht gegen sein Gewissen Kriegsdienst mit der Waffe leisten kann, stellt sich nicht außerhalb der Ordnung, sondern beruft sich auf eine ihrer zentralen Gewissensgarantien.

Das Plugin führt von der ersten inneren Klärung über den Antrag beim Bundesamt für das Personalmanagement der Bundeswehr bis zur BAFzA-Entscheidung, Anhörung, Nachreichung, Anerkennung, Ablehnung, Widerspruch, Untätigkeitsklage und Eilrechtsschutz. Es berücksichtigt den Stand 2026 nach dem Wehrdienstmodernisierungsgesetz, insbesondere § 13 KDVG n. F. für ungediente Wehrpflichtige, die vor dem 01.01.2010 geboren wurden.

## Kaltstart

1. **Status klären:** ungedient, wehrpflichtig, vor/nach 01.01.2010 geboren, gemustert, einberufen, Reservist, FWDL, Soldat auf Zeit, Berufssoldat, Soldatin, frühere Soldatin/früherer Soldat?
2. **Ziel klären:** Antrag stellen, Begründung ordnen, Unterlagen vervollständigen, Sachstand erzwingen, Anhörung vorbereiten, Ablehnung angreifen, laufenden Dienstkonflikt entschärfen?
3. **Gewissen klären:** Geht es wirklich um Kriegsdienst mit der Waffe als solcher oder nur um einen bestimmten Krieg, eine politische Lage, Angst, Karriere, Gesundheit oder Totalverweigerung?
4. **Verfahren klären:** Antrag läuft über BAPersBw; BAFzA entscheidet inhaltlich nach Zuleitung. Direkte Übersendung an das BAFzA ist nicht der gesetzliche Standardweg.
5. **Rechtsschutz klären:** Sachstand, Nachreichung, Widerspruch, § 75 VwGO, § 80 VwGO oder § 123 VwGO nur nach Lage und Frist.

## Leitgedanke

Das Plugin soll nicht fertige Gewissensformeln produzieren. Es hilft, eine echte persönliche Entscheidung so zu strukturieren, dass sie rechtlich verständlich wird: Lebensweg, innere Entwicklung, Auslöser, Stabilität, Konsequenzen, Abgrenzung zu bloßer Politik und Plausibilität. Allgemeine Mustersätze sind gefährlich; eine persönliche, wahrhaftige und prüffähige Darstellung ist stärker.

## Typische Outputs

| Situation | Skills | Ergebnis |
| --- | --- | --- |
| Erster Antrag | `allgemein`, `status-routing`, `antrag-bapersbw-form`, `gewissensbegruendung-werkstatt` | Antragspaket mit Lebenslauf- und Begründungsplan |
| Antrag liegt, nichts passiert | `eingang-und-pk-nachweis`, `sachstandsanfrage-und-frist`, `untaetigkeitsklage-vwgo-75` | Sachstandsschreiben, Fristenmatrix, Eskalationsplan |
| Soldat oder Soldatin im Dienst | `aktive-soldaten-prioritaet`, `entlassung-berufssoldat-sg-46`, `entlassung-saz-sg-55`, `dienstpflichten-waehrend-verfahren` | Statusstrategie ohne unnötiges Disziplinarrisiko |
| Anhörung oder Zweifel | `schriftliche-anhoerung-kdvg-6`, `muendliche-anhoerung-vorbereitung`, `zweifel-ausraeumen-gesamtvorbringen` | Antwortentwurf, Anhörungsleitfaden, Belegliste |
| Ablehnung | `ablehnungsbescheid-analyse`, `widerspruch-kdvg-9`, `verwaltungsgericht-kdvg-10` | Rechtsbehelfsplan und Klagegerüst |
| 2026-Sonderfall | `wdmodg-2026-uebergang`, `kdvg-13-neun-monate`, `ungedient-vor-2010` | Prüfung der neuen Sonderregeln |

## Keine Totalverweigerung

Dieses Plugin erklärt bei Bedarf die Abgrenzung, unterstützt aber nicht beim bewussten Bruch mit allen Dienst- und Ersatzdienstpflichten. Der Fokus liegt auf der rechtmäßigen, offenen und dokumentierten Berufung auf das Gewissen gegen den Kriegsdienst mit der Waffe.

## Quellenstrategie

- **Amtlich zuerst:** GG, KDVG, WPflG, SG, VwGO, BAFzA-Hinweise, BAPersBw/Bundeswehr-Hinweise.
- **Rechtsprechung verifiziert:** BVerwG und BVerfG nur mit Datum, Aktenzeichen und freiem Link.
- **Aktualität 2026:** Vor Ausgabe immer prüfen, ob Wehrdienstmodernisierung, Bedarfswehrpflicht oder Verwaltungspraxis geändert wurden.
- **Keine Blindzitate:** keine BeckRS-, juris-, Kommentar- oder Aufsatzfundstellen aus Modellwissen.

## Datenschutz und Sicherheit

Gewissensbegründungen, Gesundheitsdaten, Personalakten, Musterungsunterlagen und Soldatenakten sind hochsensibel. In produktiven Verfahren nur in einem dafür freigegebenen, datenschutz- und berufsrechtskonformen System arbeiten.

## Lizenz

Apache-2.0 OR MIT. Siehe Repository-Stammverzeichnis.


<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 29 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `akteneinsicht-kdv-aktenvernichtung-kdvg-aktive-soldaten-aktuelle` | Akteneinsicht Kdv, Aktenvernichtung Kdvg 12, Aktive Soldaten Prioritaet, Aktuelle Lage 2026, Anerkennung Und Dienstfolgen: Akteneinsicht Kdv; Aktenvernichtung Kdvg 12; Aktive Soldaten Prioritaet; Aktuelle Lage 2026; Anerkennung Und Diens... |
| `allgemein` | Kaltstart für Kriegsdienstverweigerung aus Gewissensgründen: Status, Verfahrenslage, Gewissenskern, Antragspfad, Fristen, Rechtsschutz und passende Spezialskills auswählen. |
| `anerkennung-voraussetzungen-anerkennungsbescheid-gueltigkeit` | Anerkennung Voraussetzungen Kdvg 5, Anerkennungsbescheid Gueltigkeit, Angst Karriere Gesundheit Abgrenzen, Anhoerungsprotokoll Und Korrektur, Anlagenverzeichnis Kdv: Anerkennung Voraussetzungen Kdvg 5; Anerkennungsbescheid Gueltigkeit; A... |
| `anschreiben-kurz-antrag-bapersbw-antrag-niederschrift` | Anschreiben Kurz Und Wuerdig, Antrag Bapersbw Form, Antrag Zur Niederschrift, Anwaltlicher Brief Bafza, Anwaltlicher Brief Bapersbw: Anschreiben Kurz Und Wuerdig; Antrag Bapersbw Form; Antrag Zur Niederschrift; Anwaltlicher Brief Bafza;... |
| `arbeitgeber-fehlzeit-argumente-nicht-aufschiebende-wirkung` | Arbeitgeber Und Fehlzeit, Argumente Die Nicht Tragen, Aufschiebende Wirkung Kdvg 3, Ausbildungskosten Rueckforderung, Auslaendischer Wehrdienst Und Asyl: Arbeitgeber Und Fehlzeit; Argumente Die Nicht Tragen; Aufschiebende Wirkung Kdvg 3;... |
| `ausland-aufenthalt-bafza-entscheidungspfad-bedarfswehrpflicht` | Ausland Aufenthalt Wehrpflicht, Bafza Entscheidungspfad, Bedarfswehrpflicht Wpflg 2A, Befehl Und Gewissenskonflikt, Begründung Für Aktive Soldaten: Ausland Aufenthalt Wehrpflicht; Bafza Entscheidungspfad; Bedarfswehrpflicht Wpflg 2A; Bef... |
| `begruendung-ehemalige-anerkannte-reservisten-ungediente-beistand` | Begründung Für Ehemalige Anerkannte, Begründung Für Reservisten, Begründung Für Ungediente, Begründung Redaktion Ohne Schablone, Beistand Kirchen Beratung: Begründung Für Ehemalige Anerkannte; Begründung Für Reservisten; Begründung Für U... |
| `berufliche-folgen-berufssoldaten-kdv-bescheid-archivieren` | Berufliche Folgen Zivil, Berufssoldaten Kdv, Bescheid Archivieren, Beweislast Und Ueberzeugungsbildung, Bverwg 2005 Pfaff Befehl: Berufliche Folgen Zivil; Berufssoldaten Kdv; Bescheid Archivieren; Beweislast Und Ueberzeugungsbildung; Bve... |
| `bverwg-sanitaetsdienst-innere-umkehr-parteivernehmung-checkliste` | Bverwg 2012 Sanitaetsdienst, Bverwg 2018 Innere Umkehr, Bverwg 2021 Parteivernehmung, Checkliste Nach Antrag, Checkliste Vor Antrag: Bverwg 2012 Sanitaetsdienst; Bverwg 2018 Innere Umkehr; Bverwg 2021 Parteivernehmung; Checkliste Nach An... |
| `datenschutz-gewissensakte-dienststelle-kommunikation` | Datenschutz Gewissensakte, Dienststelle Kommunikation, Disziplinarrisiken Soldaten, Disziplinarvorgesetzter Stellungnahme, Doppelte Staatsangehörigkeit: Datenschutz Gewissensakte; Dienststelle Kommunikation; Disziplinarrisiken Soldaten;... |
| `eidesstattliche-versicherung-eilrechtsschutz-drohende` | Eidesstattliche Versicherung, Eilrechtsschutz Drohende Einberufung, Einberufung Nach Antrag, Eingang Und Pk Nachweis, Einstweilige Anordnung Vwgo 123: Eidesstattliche Versicherung; Eilrechtsschutz Drohende Einberufung; Einberufung Nach A... |
| `europa-menschenrechte-familie-partnerschaft-fehlende` | Europa Menschenrechte Kdv, Familie Partnerschaft Gesellschaftsdruck, Fehlende Rechtsschutzbelehrung, Formularmythen Social Media, Fruehere Soldaten Und Erneute Heranziehung: Europa Menschenrechte Kdv; Familie Partnerschaft Gesellschaftsd... |
| `frueherer-abgelehnter-fuehrungszeugnis-zweifel-fwdl-probezeit` | Frueherer Abgelehnter Antrag, Fuehrungszeugnis Zweifel, Fwdl Probezeit Und Kdv, Gesetzliche Vertreter Rechtsbehelfe, Gewissensbegruendung Werkstatt: Frueherer Abgelehnter Antrag; Fuehrungszeugnis Zweifel; Fwdl Probezeit Und Kdv; Gesetzli... |
| `gewissensentscheidung-massstab-glossar-kdv-grundrecht-art` | Gewissensentscheidung Massstab, Glossar Kdv, Grundrecht Art 4 Abs 3, Humanistische Pazifistische Gruende, Innere Umkehr Gediente: Gewissensentscheidung Massstab; Glossar Kdv; Grundrecht Art 4 Abs 3; Humanistische Pazifistische Gruende; I... |
| `karrierecenter-bapersbw-kdvg-neun-kein-totalverweigerungs-ki` | Karrierecenter Und Bapersbw, Kdvg 13 Neun Monate, Kein Totalverweigerungs Tool, Ki Nutzung Gewissensbegruendung, Klage Ohne Berufung: Karrierecenter Und Bapersbw; Kdvg 13 Neun Monate; Kein Totalverweigerungs Tool; Ki Nutzung Gewissensbeg... |
| `kommunikation-familie-kosten-auslagen-lebensfuehrung` | Kommunikation Mit Familie, Kosten Und Auslagen Anhoerung, Lebensfuehrung Und Plausibilitaet, Lebenslauf Luecken Und Widersprueche, Mehrsprachige Orientierung: Kommunikation Mit Familie; Kosten Und Auslagen Anhoerung; Lebensfuehrung Und P... |
| `minderjaehrige-antragstellung-muendliche-anhoerung-musterung` | Minderjaehrige Antragstellung, Muendliche Anhoerung Vorbereitung, Musterung Verweigert Ablehnung, Musterungen Und Eignung, Musterungsbescheid Bestandskraft: Minderjaehrige Antragstellung; Muendliche Anhoerung Vorbereitung; Musterung Verw... |
| `nachreichung-fehlender-unterlagen` | Formuliert fristwahrende Nachreichungen nach behördlicher Aufforderung. |
| `notfallplan-dienstantritt-parteivernehmung-vorbereiten` | Notfallplan Vor Dienstantritt, Parteivernehmung Vorbereiten, Personalakte Und Datenschutz Soldaten, Personenkennziffer Und Grundakte, Politische Motive Abgrenzen: Notfallplan Vor Dienstantritt; Parteivernehmung Vorbereiten; Personalakte... |
| `presseanfragen-kdv-psychische-belastung-qualitaetsgate-ausgabe` | Presseanfragen Und Kdv, Psychische Belastung Und Beratung, Qualitaetsgate Vor Ausgabe, Recht Auf Entscheidung Mein Gewissen Schlaeft Nicht, Rechtsanwaltliche Vollmacht: Presseanfragen Und Kdv; Psychische Belastung Und Beratung; Qualitaet... |
| `rechtsprechung-livecheck-dienstpflichten-waehrend-frist` | Rechtsprechung Livecheck, Dienstpflichten Waehrend Verfahren, Frist Bei Nachforderung Ein Monat, Fristenkalender Kdv, Sachstandsanfrage Und Frist: Rechtsprechung Livecheck; Dienstpflichten Waehrend Verfahren; Frist Bei Nachforderung Ein... |
| `rechtsschutzbeduerfnis-religioese-weltanschauliche-reservisten` | Rechtsschutzbeduerfnis Prüfen, Religioese Weltanschauliche Gruende, Reservisten Heranziehung, Rücknahme Oder Verzicht, Sanitaetsdienst Und Waffenloser Dienst: Rechtsschutzbeduerfnis Prüfen; Religioese Weltanschauliche Gruende; Reserviste... |
| `schluesselerlebnis-wandel-schriftliche-anhoerung` | Schluesselerlebnis Oder Wandel, Schriftliche Anhoerung Kdvg 6, Sicherheitsueberpruefung Und Extremismus, Social Media Und Oeffentlichkeit, Sofortvollzug Und Anordnung: Schluesselerlebnis Oder Wandel; Schriftliche Anhoerung Kdvg 6; Sicher... |
| `soldat-zeit-soldatinnen-kdv-spannungs-verteidigungsfall-sprache` | Soldat Auf Zeit Kdv, Soldatinnen Und Kdv, Spannungs Verteidigungsfall, Sprache Der Loyalitaet, Sprachlich Einfache Erklaerung: Soldat Auf Zeit Kdv; Soldatinnen Und Kdv; Spannungs Verteidigungsfall; Sprache Der Loyalitaet; Sprachlich Einf... |
| `status-routing-stellungnahmen-dritter-ungedient-ab` | Status Routing, Stellungnahmen Dritter, Ungedient Ab 2010, Ungedient Vor 2010, Untaetigkeitsklage Vwgo 75: Status Routing; Stellungnahmen Dritter; Ungedient Ab 2010; Ungedient Vor 2010; Untaetigkeitsklage Vwgo 75. Führt Intake, Prüfrouti... |
| `unterlagenmappe-kdv-verwaltungsakt-informelles` | Unterlagenmappe Kdv, Verwaltungsakt Oder Informelles Schreiben, Verwaltungsgericht Kdvg 10, Vollstaendiger Lebenslauf, Vollstaendigkeit Kdvg 2: Unterlagenmappe Kdv; Verwaltungsakt Oder Informelles Schreiben; Verwaltungsgericht Kdvg 10; V... |
| `waffenbesitz-jagd-wahrheitspflicht-authentizitaet-wehrpflicht` | Waffenbesitz Jagd Schuetzenverein, Wahrheitspflicht Und Authentizitaet, Wehrpflicht Ruht Ausland, Widerspruch Kdvg 9, Zeugenauswahl Und Aussage: Waffenbesitz Jagd Schuetzenverein; Wahrheitspflicht Und Authentizitaet; Wehrpflicht Ruht Aus... |
| `widerspruch-sonderlagen-ablehnungsbescheid-analyse` | Widerspruch Fristen Sonderlagen, Ablehnungsbescheid Analyse, Ablehnungsgruende Kdvg 7, Adressat Und Versandwege, Akte Für Gericht Aufbauen: Widerspruch Fristen Sonderlagen; Ablehnungsbescheid Analyse; Ablehnungsgruende Kdvg 7; Adressat U... |
| `zivildienst-altfaelle-ziviler-ersatzdienst-zweifel-ausraeumen` | Zivildienst Altfaelle, Ziviler Ersatzdienst Art 12A, Zweifel Ausraeumen Gesamtvorbringen, Zweitbescheid Bescheinigung: Zivildienst Altfaelle; Ziviler Ersatzdienst Art 12A; Zweifel Ausraeumen Gesamtvorbringen; Zweitbescheid Bescheinigung.... |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
