# JVEG-Kostenprüfer

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`jveg-kostenpruefer`) | [`jveg-kostenpruefer.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/jveg-kostenpruefer.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **Akte JVEG Zeugenentschädigung – Dr. Sophia Berger / LG Tübingen** (`jveg-zeugin-berger-lg-tuebingen`) | [Gesamt-PDF lesen](../testakten/jveg-zeugin-berger-lg-tuebingen/gesamt-pdf/jveg-zeugin-berger-lg-tuebingen_gesamt.pdf) | [`testakte-jveg-zeugin-berger-lg-tuebingen.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-jveg-zeugin-berger-lg-tuebingen.zip) |
| **Akte LG Regensburg — Sieglinger gegen Burgwald Energietechnik GmbH** (`sachverstaendigengutachten-ki-vorwurf-lg-regensburg-sieglinger`) | [Gesamt-PDF lesen](../testakten/sachverstaendigengutachten-ki-vorwurf-lg-regensburg-sieglinger/gesamt-pdf/sachverstaendigengutachten-ki-vorwurf-lg-regensburg-sieglinger_gesamt.pdf) | [`testakte-sachverstaendigengutachten-ki-vorwurf-lg-regensburg-sieglinger.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-sachverstaendigengutachten-ki-vorwurf-lg-regensburg-sieglinger.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

Freistehendes Cowork-Plugin zur Prüfung von Kosten, Vorschüssen, Entschädigungen und Vergütungen nach dem Justizvergütungs- und -entschädigungsgesetz. Es ist auf echte Aktenarbeit zugeschnitten: Unterlagen strippen, Anspruchsart erkennen, JVEG-Positionen rechnen, Belege prüfen, Gerichtsschreiben angreifen oder bestätigen und am Ende ein belastbares Schreiben samt Rechenprotokoll erzeugen.

Die Beispielakte enthält den Fall der Zeugin Sophia Berger vor dem Landgericht Tübingen, Az. 7 O 118/23, mit Vorschussantrag, Gerichtsschreiben, anwaltlichem Schriftsatz und Word-Abschrift.

## Was das Plugin prüft

- Vorschuss nach § 3 JVEG
- Geltendmachung, Erlöschen, Wiedereinsetzung und Verjährung
- Fahrtkosten nach § 5 JVEG
- Tagegeld und Übernachtung nach § 6 JVEG
- sonstige notwendige Aufwendungen nach § 7 JVEG
- Zeugenentschädigung nach §§ 19 bis 22 JVEG
- Sachverständigen-, Dolmetscher- und Übersetzervergütung
- Kürzungs- und Wegfallrisiken nach § 8a JVEG
- Festsetzungs-, Beschwerde- und Ergänzungsschreiben

## Grundworkflow

1. Akte hochladen: Ladung, Antrag, Gerichtsschreiben, Belege, Rechnung oder Schriftsatz.
2. Rolle bestimmen: Zeuge, Sachverständiger, Dolmetscher, Übersetzer, Dritter oder ehrenamtlicher Richter.
3. Frist und Belehrung prüfen.
4. Jede Kostenposition mit Norm, Beleg und Rechenweg erfassen.
5. Kappungen und Doppelposten prüfen.
6. Beleglücken freundlich als Rückfragen ausgeben.
7. Rechenblatt, Prüfbericht und passendes Gerichtsschreiben erzeugen.

## Enthaltene Skills

| Skill | Zweck |
| --- | --- |
| jveg-kommandocenter | Startet die JVEG-Kostenprüfung, trennt Rolle, Anspruchsart, Frist, Belege, Rechenweg und gewünschten Output. |
| jveg-aktenstripper | Liest Gerichtsschreiben, Anträge, Rechnungen, Belege und Kostenfestsetzungsunterlagen in eine prüfbare JVEG-Datenmatrix aus. |
| jveg-anspruchsberechtigung | Kläert, ob Zeuge, Dritter, Sachverständiger, Dolmetscher, Übersetzer, Protokollperson oder ehrenamtlicher Richter betroffen ist. |
| jveg-fristen-erloeschen | Prüft Geltendmachung, Drei-Monats-Frist, Belehrung, Wiedereinsetzung, Verjährung und sichere Fristennotizen. |
| jveg-vorschuss | Prüft Vorschussanträge nach § 3 JVEG mit Schwerpunkt erhebliche Fahrtkosten, Übernachtung und Teilleistungen. |
| jveg-zeugenentschaedigung | Rechnet und plausibilisiert Zeugenentschädigung nach §§ 19 bis 22 JVEG. |
| jveg-fahrtkosten | Prüft Bahn, Flug, eigenes Kfz, Kilometerpauschale, Parkkosten, Auslandsanreise und Wirtschaftlichkeit. |
| jveg-uebernachtung-aufwand | Prüft Tagegeld, notwendige Übernachtung, BRKG-Anknüpfung, Belege und gerichtliche Obergrenzen. |
| jveg-verdienstausfall-haushalt-zeit | Trennt Verdienstausfall, Haushaltsführungsnachteile und Zeitversäumnis, damit keine Doppelberechnung entsteht. |
| jveg-sonstige-aufwendungen-belege | Prüft sonstige notwendige bare Auslagen, Begleitpersonen, Vertretung, Kopien, Dateien und Belegfähigkeit. |
| jveg-sachverstaendigenrechnung | Prüft Sachverständigenvergütung: Honorargruppe, erforderliche Zeit, Reisezeit, Nebenkosten, § 8a-Risiken und Vorschussüberlauf. |
| jveg-dolmetscher-uebersetzer | Prüft Dolmetscher- und Übersetzervergütung, Stundensatz, Zeilen-/Textumfang, Reisezeiten und Sprach-/Terminlogik. |
| jveg-kuerzung-wegfall-8a | Findet Kürzungs- und Wegfallrisiken: Verwertbarkeit, Hinweisobliegenheit, Befangenheit, Vorschussüberschreitung und Mängel. |
| jveg-gerichtsschreiben-pruefung | Prüft Gerichtsschreiben und Kostenbeamtenargumente auf Tatbestandsfehler, Ermessensfehler, Beleganforderungen und Antwortbedarf. |
| jveg-rechenblatt | Erstellt ein prüfbares Rechenblatt mit Norm, Eingabewert, Kappung, Beleg, Rechenschritt und Ergebnis. |
| jveg-antragsgenerator | Erzeugt Vorschuss-, Nachzahlungs-, Festsetzungs- und Ergänzungsschreiben mit Anlagen- und Belegliste. |
| jveg-festsetzung-beschwerde | Führt durch gerichtliche Festsetzung, Erinnerung/Beschwerdeprüfung, Beschwer, Frist und knappe Angriffsmittel. |
| jveg-quality-gate | Letzte Prüfung vor Versand: Normstand, Mathematik, Belege, keine Doppelposten, Fristen, Ton und eindeutiger Antrag. |

## Beispiel Berger

Die Beispielakte bildet einen realistisch aussehenden Vorschussstreit ab: Barcelona nach Tübingen, 2.500 km Hin- und Rückfahrt, zwei Übernachtungen, geltend gemachter Verdienstausfall und gerichtliche Ablehnung des Vorschusses wegen angeblich fehlender Bedürftigkeit. Das Plugin markiert insbesondere, dass § 3 JVEG bei erheblichen Fahrtkosten und sonstigen Aufwendungen ansetzt und die Kostenpositionen getrennt nach Erstattungsfähigkeit, Vorschussfähigkeit und Belegstatus geprüft werden müssen.

<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 24 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `kompendium-01-allgemein-bis-workflow-fristen-und` | jveg-kostenpruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Allgemein, Chronologie Und Belegmatrix, Fristen Und Risikoampel; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck. |
| `kompendium-02-workflow-mandantenko-bis-jveg-fristen-erloesc` | jveg-kostenpruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Mandantenkommunikation, Redteam Qualitygate, Jveg Fristen Erloeschen; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätsc... |
| `kompendium-03-spezial-fristen-comp-bis-spezial-kostenpruefe` | jveg-kostenpruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Fristen Compliance Dokumentation Und Akte, Kostenfestsetzung Belege Und Fristen, Kostenpruefer Fristen Form Und Zustaendigkeit; mit Intake, Prüfroutine, Norm... |
| `kompendium-04-spezial-uebersetzer-bis-jveg-aktenstripper` | jveg-kostenpruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Uebersetzer Fristennotiz Und Naechster Schritt, Jveg Sachverstaendigenrechnung Bauleiter, Jveg Aktenstripper; mit Intake, Prüfroutine, Normen-/Quellenradar,... |
| `kompendium-05-jveg-anspruchsberech-bis-jveg-dolmetscher-ueb` | jveg-kostenpruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Jveg Anspruchsberechtigung, Jveg Antragsgenerator, Jveg Dolmetscher Uebersetzer; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und... |
| `kompendium-06-jveg-dolmetscher-ueb-bis-jveg-festsetzung-bes` | jveg-kostenpruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Jveg Dolmetscher Uebersetzer Spezial, Jveg Fahrtkosten, Jveg Festsetzung Beschwerde; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster... |
| `kompendium-07-jveg-gerichtsschreib-bis-jveg-kuerzung-wegfal` | jveg-kostenpruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Jveg Gerichtsschreiben Pruefung, Jveg Kommandocenter, Jveg Kuerzung Wegfall 8a; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und... |
| `kompendium-08-jveg-quality-gate-bis-jveg-sachverstaendig` | jveg-kostenpruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Jveg Quality Gate, Jveg Rechenblatt, Jveg Sachverstaendigenrechnung; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätsch... |
| `kompendium-09-jveg-sonstige-aufwen-bis-jveg-verdienstausfal` | jveg-kostenpruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Jveg Sonstige Aufwendungen Belege, Jveg Uebernachtung Aufwand, Jveg Verdienstausfall Haushalt Zeit; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogi... |
| `kompendium-10-jveg-vorschuss-bis-jveg-zeugenentschaed` | jveg-kostenpruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Jveg Vorschuss, Jveg Vorschuss Kostenrisiko Spezial, Jveg Zeugenentschaedigung; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und... |
| `kompendium-11-jveg-zeugenentschaed-bis-spezial-belegfeste-f` | jveg-kostenpruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Jveg Zeugenentschaedigung Checkliste, Pruefung Sachverstaendigengutachten Ki Deklaration, Belegfeste Formular Portal Und Einreichung; mit Intake, Prüfroutine... |
| `kompendium-12-spezial-beschwerde-i-bis-spezial-dolmetscherk` | jveg-kostenpruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Beschwerde Internationaler Bezug Und Schnittstellen, Dolmetscher Sonderfall Und Edge Case, Dolmetscherkosten Zahlen Schwellen Und Berechnung; mit Intake, Prü... |
| `kompendium-13-spezial-fahrtkosten-bis-spezial-freistehende` | jveg-kostenpruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Fahrtkosten Behoerden Gericht Und Registerweg, Festsetzung Mehrparteien Konflikt Und Interessen, Freistehender Erstpruefung Und Mandatsziel; mit Intake, Prüf... |
| `kompendium-14-spezial-gate-beweisl-bis-spezial-quality-mand` | jveg-kostenpruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Gate Beweislast Und Darlegungslast, Jveg Tatbestand Beweis Und Belege, Quality Mandantenkommunikation Entscheidungsvorlage; mit Intake, Prüfroutine, Normen-/... |
| `kompendium-15-spezial-uebernachtun-bis-spezial-vorschuss-ri` | jveg-kostenpruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Uebernachtung Schriftsatz Brief Und Memo Bausteine, Verdienstausfall Verhandlung Vergleich Und Eskalation, Vorschuss Risikoampel Und Gegenargumente; mit Inta... |
| `kompendium-16-spezial-zeugenentsch-bis-spezial-zeugenentsch` | jveg-kostenpruefer: eigenständiger Arbeits-Skill zu Zeugenentschaedigung Dokumentenmatrix Und Lueckenliste; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck. |
| `spezial-rechenprotokolle-red-team-und-qualitaetskontrolle` | Rechenprotokolle: Red-Team und Qualitätskontrolle im Plugin jveg kostenpruefer; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Standardprüfung. |
| `spezial-sachverstaendigen-livequellen-und-rechtsprechungscheck` | Sachverstaendigen: Livequellen- und Rechtsprechungscheck im Plugin jveg kostenpruefer; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Standardprüfung. |
| `workflow-anschluss-skills-router` | Anschluss-Skills Router im Plugin jveg-kostenpruefer: schlägt nach der ersten Prüfung die passenden Spezialskills aus demselben Plugin vor. |
| `workflow-dokumentenintake` | Dokumentenintake im Plugin jveg-kostenpruefer: liest Uploads, sortiert Dokumentarten, markiert Fristen und baut eine knappe Arbeitsakte. |
| `workflow-kaltstart-und-routing` | Kaltstart und Routing im Plugin jveg-kostenpruefer: führt vom ersten Satz oder Dokument in den passenden Arbeitsweg, erkennt Rolle, Ziel, Risiko und Anschluss-Skills. |
| `workflow-output-waehlen` | Output wählen im Plugin jveg-kostenpruefer: entscheidet zwischen Memo, Schriftsatz, Tabelle, Brief, Checkliste, Vermerk, Redline oder Mandantenübersetzung. |
| `workflow-rechtsquellen-livecheck` | Rechtsquellen-Livecheck im Plugin jveg-kostenpruefer: zwingt vor tragenden Aussagen zum aktuellen Quellencheck bei Gesetzen, Behörden, Gerichten und Formularen. |
| `workflow-unterlagen-lueckenliste` | Unterlagen- und Lückenliste im Plugin jveg-kostenpruefer: erstellt eine präzise Nachforderungsliste statt allgemeiner Fragebögen. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
