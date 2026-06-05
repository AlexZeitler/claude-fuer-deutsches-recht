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
| `allgemein-workflow-chronologie-workflow-fristen` | Allgemein, Workflow Chronologie Und Belegmatrix, Workflow Fristen Und Risikoampel: Allgemein; Workflow Chronologie Und Belegmatrix; Workflow Fristen Und Risikoampel. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmus... |
| `beschwerde-dolmetscher-sonderfall-dolmetscherkosten` | Spezial Beschwerde Internationaler Bezug Und Schnittstellen, Spezial Dolmetscher Sonderfall Und Edge Case, Spezial Dolmetscherkosten Zahlen Schwellen Und Berechnung: Spezial Beschwerde Internationaler Bezug Und Schnittstellen; Spezial Do... |
| `fahrtkosten-festsetzung-interessen-freistehender` | Spezial Fahrtkosten Behörden Gericht Und Registerweg, Spezial Festsetzung Mehrparteien Konflikt Und Interessen, Spezial Freistehender Erstpruefung Und Mandatsziel: Spezial Fahrtkosten Behörden Gericht Und Registerweg; Spezial Festsetzung... |
| `gate-beweislast-jveg-quality` | Spezial Gate Beweislast Und Darlegungslast, Spezial Jveg Tatbestand Beweis Und Belege, Spezial Quality Mandantenkommunikation Entscheidungsvorlage: Spezial Gate Beweislast Und Darlegungslast; Spezial Jveg Tatbestand Beweis Und Belege; Sp... |
| `jveg-anspruchsberechtigung-antragsgenerator-dolmetscher` | Jveg Anspruchsberechtigung, Jveg Antragsgenerator, Jveg Dolmetscher Uebersetzer: Jveg Anspruchsberechtigung; Jveg Antragsgenerator; Jveg Dolmetscher Uebersetzer. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster... |
| `jveg-dolmetscher-uebersetzer-fahrtkosten-festsetzung-beschwerde` | Jveg Dolmetscher Uebersetzer Spezial, Jveg Fahrtkosten, Jveg Festsetzung Beschwerde: Jveg Dolmetscher Uebersetzer Spezial; Jveg Fahrtkosten; Jveg Festsetzung Beschwerde. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outpu... |
| `jveg-gate-rechenblatt-sachverstaendigenrechnung` | Jveg Quality Gate, Jveg Rechenblatt, Jveg Sachverstaendigenrechnung: Jveg Quality Gate; Jveg Rechenblatt; Jveg Sachverstaendigenrechnung. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zusam... |
| `jveg-gerichtsschreiben-jveg-kuerzung-wegfall` | Jveg Gerichtsschreiben Prüfung, Jveg Kommandocenter, Jveg Kuerzung Wegfall 8A: Jveg Gerichtsschreiben Prüfung; Jveg Kommandocenter; Jveg Kuerzung Wegfall 8A. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und... |
| `jveg-sonstige-aufwendungen-uebernachtung-aufwand` | Jveg Sonstige Aufwendungen Belege, Jveg Uebernachtung Aufwand, Jveg Verdienstausfall Haushalt Zeit: Jveg Sonstige Aufwendungen Belege; Jveg Uebernachtung Aufwand; Jveg Verdienstausfall Haushalt Zeit. Führt Intake, Prüfroutine, Normen-/Qu... |
| `jveg-vorschuss-kostenrisiko-zeugenentschaedigung` | Jveg Vorschuss, Jveg Vorschuss Kostenrisiko Spezial, Jveg Zeugenentschaedigung: Jveg Vorschuss; Jveg Vorschuss Kostenrisiko Spezial; Jveg Zeugenentschaedigung. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster un... |
| `jveg-zeugenentschaedigung-sachverstaendigengutachten-ki` | Jveg Zeugenentschaedigung Checkliste, Prüfung Sachverstaendigengutachten Ki Deklaration, Spezial Belegfeste Formular Portal Und Einreichung: Jveg Zeugenentschaedigung Checkliste; Prüfung Sachverstaendigengutachten Ki Deklaration; Spezial... |
| `spezial-fristen-kostenfestsetzung-kostenpruefer` | Spezial Fristen Compliance Dokumentation Und Akte, Spezial Kostenfestsetzung Belege Und Fristen, Spezial Kostenpruefer Fristen Form Und Zustaendigkeit: Spezial Fristen Compliance Dokumentation Und Akte; Spezial Kostenfestsetzung Belege U... |
| `spezial-rechenprotokolle-red-team-und-qualitaetskontrolle` | Rechenprotokolle: Red-Team und Qualitätskontrolle im Plugin jveg kostenpruefer; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Standardprüfung. |
| `spezial-sachverstaendigen-livequellen-und-rechtsprechungscheck` | Sachverstaendigen: Livequellen- und Rechtsprechungscheck im Plugin jveg kostenpruefer; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Standardprüfung. |
| `uebernachtung-verdienstausfall-vorschuss` | Spezial Uebernachtung Schriftsatz Brief Und Memo Bausteine, Spezial Verdienstausfall Verhandlung Vergleich Und Eskalation, Spezial Vorschuss Risikoampel Und Gegenargumente: Spezial Uebernachtung Schriftsatz Brief Und Memo Bausteine; Spez... |
| `uebersetzer-fristennotiz-jveg-sachverstaendigenrechnung` | Spezial Uebersetzer Fristennotiz Und Naechster Schritt, Jveg Sachverstaendigenrechnung Bauleiter, Jveg Aktenstripper: Spezial Uebersetzer Fristennotiz Und Naechster Schritt; Jveg Sachverstaendigenrechnung Bauleiter; Jveg Aktenstripper. F... |
| `workflow-anschluss-skills-router` | Anschluss-Skills Router im Plugin jveg-kostenpruefer: schlägt nach der ersten Prüfung die passenden Spezialskills aus demselben Plugin vor. |
| `workflow-dokumentenintake` | Dokumentenintake im Plugin jveg-kostenpruefer: liest Uploads, sortiert Dokumentarten, markiert Fristen und baut eine knappe Arbeitsakte. |
| `workflow-kaltstart-und-routing` | Kaltstart und Routing im Plugin jveg-kostenpruefer: führt vom ersten Satz oder Dokument in den passenden Arbeitsweg, erkennt Rolle, Ziel, Risiko und Anschluss-Skills. |
| `workflow-mandantenkommunikation-redteam-qualitygate-jveg` | Workflow Mandantenkommunikation, Workflow Redteam Qualitygate, Jveg Fristen Erloeschen: Workflow Mandantenkommunikation; Workflow Redteam Qualitygate; Jveg Fristen Erloeschen. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik,... |
| `workflow-output-waehlen` | Output wählen im Plugin jveg-kostenpruefer: entscheidet zwischen Memo, Schriftsatz, Tabelle, Brief, Checkliste, Vermerk, Redline oder Mandantenübersetzung. |
| `workflow-rechtsquellen-livecheck` | Rechtsquellen-Livecheck im Plugin jveg-kostenpruefer: zwingt vor tragenden Aussagen zum aktuellen Quellencheck bei Gesetzen, Behörden, Gerichten und Formularen. |
| `workflow-unterlagen-lueckenliste` | Unterlagen- und Lückenliste im Plugin jveg-kostenpruefer: erstellt eine präzise Nachforderungsliste statt allgemeiner Fragebögen. |
| `zeugenentschaedigung` | Spezial Zeugenentschaedigung Dokumentenmatrix Und Lueckenliste: Spezial Zeugenentschaedigung Dokumentenmatrix Und Lueckenliste. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zusammen. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
