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
| `allgemein` | Kaltstart für Kriegsdienstverweigerung aus Gewissensgründen: Status, Verfahrenslage, Gewissenskern, Antragspfad, Fristen, Rechtsschutz und passende Spezialskills auswählen. |
| `kompendium-01-rechtsprechung-livec-bis-sachstandsanfrage-un` | kriegsdienstverweigerung-wehrdienst: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Rechtsprechung Livecheck, Dienstpflichten Waehrend Verfahren, Frist Bei Nachforderung Ein Monat, Fristenkalender Kdv und 1 weitere Arbeitsmo... |
| `kompendium-02-widerspruch-fristen-bis-akte-fuer-gericht-au` | kriegsdienstverweigerung-wehrdienst: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Widerspruch Fristen Sonderlagen, Ablehnungsbescheid Analyse, Ablehnungsgruende Kdvg 7, Adressat Und Versandwege und 1 weitere Arbeitsmodule;... |
| `kompendium-03-akteneinsicht-kdv-bis-anerkennung-und-dien` | kriegsdienstverweigerung-wehrdienst: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Akteneinsicht Kdv, Aktenvernichtung Kdvg 12, Aktive Soldaten Prioritaet, Aktuelle Lage 2026 und 1 weitere Arbeitsmodule; mit Intake, Prüfrou... |
| `kompendium-04-anerkennung-vorausse-bis-anlagenverzeichnis-k` | kriegsdienstverweigerung-wehrdienst: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Anerkennung Voraussetzungen Kdvg 5, Anerkennungsbescheid Gueltigkeit, Angst Karriere Gesundheit Abgrenzen, Anhoerungsprotokoll Und Korrektur... |
| `kompendium-05-anschreiben-kurz-und-bis-anwaltlicher-brief-b` | kriegsdienstverweigerung-wehrdienst: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Anschreiben Kurz Und Wuerdig, Antrag Bapersbw Form, Antrag Zur Niederschrift, Anwaltlicher Brief Bafza und 1 weitere Arbeitsmodule; mit Inta... |
| `kompendium-06-arbeitgeber-und-fehl-bis-auslaendischer-wehrd` | kriegsdienstverweigerung-wehrdienst: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Arbeitgeber Und Fehlzeit, Argumente Die Nicht Tragen, Aufschiebende Wirkung Kdvg 3, Ausbildungskosten Rueckforderung und 1 weitere Arbeitsmo... |
| `kompendium-07-ausland-aufenthalt-w-bis-begruendung-fuer-akt` | kriegsdienstverweigerung-wehrdienst: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Ausland Aufenthalt Wehrpflicht, Bafza Entscheidungspfad, Bedarfswehrpflicht Wpflg 2a, Befehl Und Gewissenskonflikt und 1 weitere Arbeitsmodu... |
| `kompendium-08-begruendung-fuer-ehe-bis-beistand-kirchen-ber` | kriegsdienstverweigerung-wehrdienst: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Begruendung Fuer Ehemalige Anerkannte, Begruendung Fuer Reservisten, Begruendung Fuer Ungediente, Begruendung Redaktion Ohne Schablone und 1... |
| `kompendium-09-berufliche-folgen-zi-bis-bverwg-2005-pfaff-be` | kriegsdienstverweigerung-wehrdienst: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Berufliche Folgen Zivil, Berufssoldaten Kdv, Bescheid Archivieren, Beweislast Und Ueberzeugungsbildung und 1 weitere Arbeitsmodule; mit Inta... |
| `kompendium-10-bverwg-2012-sanitaet-bis-checkliste-vor-antra` | kriegsdienstverweigerung-wehrdienst: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Bverwg 2012 Sanitaetsdienst, Bverwg 2018 Innere Umkehr, Bverwg 2021 Parteivernehmung, Checkliste Nach Antrag und 1 weitere Arbeitsmodule; mi... |
| `kompendium-11-datenschutz-gewissen-bis-doppelte-staatsangeh` | kriegsdienstverweigerung-wehrdienst: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Datenschutz Gewissensakte, Dienststelle Kommunikation, Disziplinarrisiken Soldaten, Disziplinarvorgesetzter Stellungnahme und 1 weitere Arbe... |
| `kompendium-12-eidesstattliche-vers-bis-einstweilige-anordnu` | kriegsdienstverweigerung-wehrdienst: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Eidesstattliche Versicherung, Eilrechtsschutz Drohende Einberufung, Einberufung Nach Antrag, Eingang Und Pk Nachweis und 1 weitere Arbeitsmo... |
| `kompendium-13-europa-menschenrecht-bis-fruehere-soldaten-un` | kriegsdienstverweigerung-wehrdienst: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Europa Menschenrechte Kdv, Familie Partnerschaft Gesellschaftsdruck, Fehlende Rechtsschutzbelehrung, Formularmythen Social Media und 1 weite... |
| `kompendium-14-frueherer-abgelehnte-bis-gewissensbegruendung` | kriegsdienstverweigerung-wehrdienst: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Frueherer Abgelehnter Antrag, Fuehrungszeugnis Zweifel, Fwdl Probezeit Und Kdv, Gesetzliche Vertreter Rechtsbehelfe und 1 weitere Arbeitsmod... |
| `kompendium-15-gewissensentscheidun-bis-innere-umkehr-gedien` | kriegsdienstverweigerung-wehrdienst: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Gewissensentscheidung Massstab, Glossar Kdv, Grundrecht Art 4 Abs 3, Humanistische Pazifistische Gruende und 1 weitere Arbeitsmodule; mit In... |
| `kompendium-16-karrierecenter-und-b-bis-klage-ohne-berufung` | kriegsdienstverweigerung-wehrdienst: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Karrierecenter Und Bapersbw, Kdvg 13 Neun Monate, Kein Totalverweigerungs Tool, Ki Nutzung Gewissensbegruendung und 1 weitere Arbeitsmodule;... |
| `kompendium-17-kommunikation-mit-fa-bis-mehrsprachige-orient` | kriegsdienstverweigerung-wehrdienst: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Kommunikation Mit Familie, Kosten Und Auslagen Anhoerung, Lebensfuehrung Und Plausibilitaet, Lebenslauf Luecken Und Widersprueche und 1 weit... |
| `kompendium-18-minderjaehrige-antra-bis-musterungsbescheid-b` | kriegsdienstverweigerung-wehrdienst: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Minderjaehrige Antragstellung, Muendliche Anhoerung Vorbereitung, Musterung Verweigert Ablehnung, Musterungen Und Eignung und 1 weitere Arbe... |
| `kompendium-19-notfallplan-vor-dien-bis-politische-motive-ab` | kriegsdienstverweigerung-wehrdienst: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Notfallplan Vor Dienstantritt, Parteivernehmung Vorbereiten, Personalakte Und Datenschutz Soldaten, Personenkennziffer Und Grundakte und 1 w... |
| `kompendium-20-presseanfragen-und-k-bis-rechtsanwaltliche-vo` | kriegsdienstverweigerung-wehrdienst: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Presseanfragen Und Kdv, Psychische Belastung Und Beratung, Qualitaetsgate Vor Ausgabe, Recht Auf Entscheidung Mein Gewissen Schlaeft Nicht u... |
| `kompendium-21-rechtsschutzbeduerfn-bis-sanitaetsdienst-und` | kriegsdienstverweigerung-wehrdienst: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Rechtsschutzbeduerfnis Pruefen, Religioese Weltanschauliche Gruende, Reservisten Heranziehung, Ruecknahme Oder Verzicht und 1 weitere Arbeit... |
| `kompendium-22-schluesselerlebnis-o-bis-sofortvollzug-und-an` | kriegsdienstverweigerung-wehrdienst: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Schluesselerlebnis Oder Wandel, Schriftliche Anhoerung Kdvg 6, Sicherheitsueberpruefung Und Extremismus, Social Media Und Oeffentlichkeit un... |
| `kompendium-23-soldat-auf-zeit-kdv-bis-sprachlich-einfache` | kriegsdienstverweigerung-wehrdienst: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Soldat Auf Zeit Kdv, Soldatinnen Und Kdv, Spannungs Verteidigungsfall, Sprache Der Loyalitaet und 1 weitere Arbeitsmodule; mit Intake, Prüfr... |
| `kompendium-24-status-routing-bis-untaetigkeitsklage-v` | kriegsdienstverweigerung-wehrdienst: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Status Routing, Stellungnahmen Dritter, Ungedient Ab 2010, Ungedient Vor 2010 und 1 weitere Arbeitsmodule; mit Intake, Prüfroutine, Normen-/... |
| `kompendium-25-unterlagenmappe-kdv-bis-vollstaendigkeit-kdv` | kriegsdienstverweigerung-wehrdienst: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Unterlagenmappe Kdv, Verwaltungsakt Oder Informelles Schreiben, Verwaltungsgericht Kdvg 10, Vollstaendiger Lebenslauf und 1 weitere Arbeitsm... |
| `kompendium-26-waffenbesitz-jagd-sc-bis-zeugenauswahl-und-au` | kriegsdienstverweigerung-wehrdienst: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Waffenbesitz Jagd Schuetzenverein, Wahrheitspflicht Und Authentizitaet, Wehrpflicht Ruht Ausland, Widerspruch Kdvg 9 und 1 weitere Arbeitsmo... |
| `kompendium-27-zivildienst-altfaell-bis-zweitbescheid-besche` | kriegsdienstverweigerung-wehrdienst: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Zivildienst Altfaelle, Ziviler Ersatzdienst Art 12a, Zweifel Ausraeumen Gesamtvorbringen, Zweitbescheid Bescheinigung; mit Intake, Prüfrouti... |
| `nachreichung-fehlender-unterlagen` | Formuliert fristwahrende Nachreichungen nach behördlicher Aufforderung. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
