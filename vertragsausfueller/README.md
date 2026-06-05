# Vertragsausfüller

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`vertragsausfueller`) | [`vertragsausfueller.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/vertragsausfueller.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **Akte Vertragsausfueller - BSAG Kiosk Huckelriede** (`vertragsausfueller-bsag-kiosk-huckelriede`) | [Gesamt-PDF lesen](../testakten/vertragsausfueller-bsag-kiosk-huckelriede/gesamt-pdf/vertragsausfueller-bsag-kiosk-huckelriede_gesamt.pdf) | [`testakte-vertragsausfueller-bsag-kiosk-huckelriede.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-vertragsausfueller-bsag-kiosk-huckelriede.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

Freistehendes Cowork-Plugin für workflowgestütztes Ausfüllen von Vertragsvorlagen und Altverträgen. Ein Nutzer lädt eine Word-Vorlage, einen alten Vertrag, ein Term Sheet oder Freitextdaten hoch. Das Plugin strippt das Dokument, erkennt Felder und Klauseln, fragt fehlende Daten ab, mappt Term-Sheet-Daten auf Vertragsfelder und erstellt daraus einen neuen Vertragsentwurf.

Der BSAG-Mietvertrag und das Term Sheet Kiosk Huckelriede sind als Beispielakte eingebunden.

## Installation

1. Claude Code oder Claude Desktop/Cowork öffnen.
2. **Customize Plugins** bzw. **Personal plugins** wählen.
3. **Install from .zip** und `vertragsausfueller.zip` hochladen.
4. Mit einem konkreten Auftrag starten, zum Beispiel: `Fülle diesen Mietvertrag mit den Daten aus dem Term Sheet aus.`

Alternativ via Marketplace:

```
/plugin marketplace add Klotzkette/claude-fuer-deutsches-recht
/plugin install vertragsausfueller@claude-fuer-deutsches-recht
```

Nicht das komplette Repository-ZIP hochladen. Das Plugin-ZIP muss im Root direkt `.claude-plugin/plugin.json`, `skills/` und `assets/` enthalten.

## Workflow

1. Vorlage oder alten Vertrag hochladen.
2. Dokument strippen: Absätze, Tabellen, Platzhalter, Klauseln, Anlagen und Signaturen erkennen.
3. Term Sheet, E-Mail oder Freitextdaten danebenlegen.
4. Feldinventar und Mapping erzeugen.
5. Fehlende Daten freundlich abfragen oder als offene Platzhalter markieren.
6. Clean-Vertrag erstellen.
7. Nur auf ausdrückliche Nachfrage zusätzlich Track Changes oder Redline vorbereiten.

## Enthaltene Skills

| Skill | Zweck |
| --- | --- |
| vaf-kommandocenter | steuert den gesamten Workflow von Upload bis neuem Vertragsentwurf. |
| vaf-docx-stripper | macht aus Word-Dokumenten ein bearbeitbares Vertragsmodell. |
| vaf-template-erkennung | klassifiziert den Vertrag und trennt Fixtext von Variablen. |
| vaf-feldinventar | baut die zentrale Datenmatrix für den Vertrag. |
| vaf-termsheet-mapping | überführt wirtschaftliche Eckdaten in Vertragsklauseln. |
| vaf-rueckfrageninterview | füllt Datenlücken ohne den Nutzer zu überfordern. |
| vaf-bsag-mietvertrag | setzt den Huckelriede-Term-Sheet-Fall in die BSAG-Vorlage um. |
| vaf-klauselentscheidung | verhindert stilles Auswählen riskanter Optionen. |
| vaf-plausibilitaetscheck | härtet den Entwurf vor Versand oder Verhandlung. |
| vaf-clean-output | liefert den ersten belastbaren Vertragsentwurf. |
| vaf-track-changes-nur-nach-frage | setzt die ausdrückliche Nachfragepflicht durch. |
| vaf-redline-qa | kontrolliert Änderungsfassungen vor Herausgabe. |
| vaf-altvertrag-nachziehen | macht aus alten Verträgen neue Entwürfe. |
| vaf-quality-gate | ist die letzte Schleuse vor Vertragserzeugung. |

## BSAG-Beispiel

Die Beispielakte enthält die Word-Vorlage `BSAG-Mietvertrag-Vorlage.docx` und das Term Sheet `BSAG-TermSheet-Kiosk-Huckelriede - Kopie.docx`. Der Spezialskill `vaf-bsag-mietvertrag` mappt daraus insbesondere Mieter, Mietobjekt, Nutzung, Fläche, Miete, Nebenkosten, Kaution, Mietbeginn, Laufzeit, Optionen, Indexierung, Umsatzsteuer, Öffnungszeiten, Konkurrenzschutz, Sortiment, Fettabscheider, Werbung und Versicherung.

## Track-Changes-Regel

Das Plugin erzeugt keine Track-Changes- oder Redline-Fassung stillschweigend. Es fragt immer ausdrücklich: Soll zusätzlich eine Track-Changes- oder Redline-Fassung erstellt werden? Ohne Bestätigung bleibt es bei Clean-Entwurf, Änderungslog und Ausfüllprotokoll.

<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 24 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `allgemein-workflow-chronologie-workflow-fristen` | Allgemein, Workflow Chronologie Und Belegmatrix, Workflow Fristen Und Risikoampel: Allgemein; Workflow Chronologie Und Belegmatrix; Workflow Fristen Und Risikoampel. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmus... |
| `changes-beweislast-docx-erkennen` | Spezial Changes Beweislast Und Darlegungslast, Spezial Docx Tatbestand Beweis Und Belege, Spezial Erkennen Schriftsatz Brief Und Memo Bausteine: Spezial Changes Beweislast Und Darlegungslast; Spezial Docx Tatbestand Beweis Und Belege; Sp... |
| `erzeugen-red-fassungen-sonderfall-felder` | Spezial Erzeugen Red Team Und Qualitaetskontrolle, Spezial Fassungen Sonderfall Und Edge Case, Spezial Felder Behörden Gericht Und Registerweg: Spezial Erzeugen Red Team Und Qualitaetskontrolle; Spezial Fassungen Sonderfall Und Edge Case... |
| `fuehren-interessen-mappen-nachfrage` | Spezial Fuehren Mehrparteien Konflikt Und Interessen, Spezial Mappen Zahlen Schwellen Und Berechnung, Spezial Nachfrage Abschlussprodukt Und Übergabe: Spezial Fuehren Mehrparteien Konflikt Und Interessen; Spezial Mappen Zahlen Schwellen... |
| `spezial-neue-rueckfragen-strippen` | Spezial Neue Internationaler Bezug Und Schnittstellen, Spezial Rueckfragen Compliance Dokumentation Und Akte, Spezial Strippen Risikoampel Und Gegenargumente: Spezial Neue Internationaler Bezug Und Schnittstellen; Spezial Rueckfragen Com... |
| `spezial-sheets-livequellen-und-rechtsprechungscheck` | Sheets: Livequellen- und Rechtsprechungscheck im Plugin vertragsausfueller; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Standardprüfung. |
| `term-track-vertraege` | Spezial Term Verhandlung Vergleich Und Eskalation, Spezial Track Mandantenkommunikation Entscheidungsvorlage, Spezial Vertraege Formular Portal Und Einreichung: Spezial Term Verhandlung Vergleich Und Eskalation; Spezial Track Mandantenko... |
| `vaf-batch-vaf-docx-vaf-einfuehrung` | Vaf Batch Modus Konzern, Vaf Docx Stripper, Vaf Einfuehrung Prozess: Vaf Batch Modus Konzern; Vaf Docx Stripper; Vaf Einfuehrung Prozess. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zusam... |
| `vaf-bsag-vaf-klauselentscheidung-vaf-konzern` | Vaf Bsag Mietvertrag, Vaf Klauselentscheidung, Vaf Konzern Rahmenvertrag Anpassen: Vaf Bsag Mietvertrag; Vaf Klauselentscheidung; Vaf Konzern Rahmenvertrag Anpassen. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmus... |
| `vaf-clean-output` | Sauberen finalen Vertragsentwurf mit Ausfüllprotokoll erstellen: Anwendungsfall alle Felder sind ausgefüllt und Quality Gate hat grüne Ampel ergeben; nun wird bereinigte Clean-Version für Unterschrift oder Versand erstellt. §§ 125 ff. BG... |
| `vaf-feldinventar-vaf-fragebogen-vaf-fremdsprachige` | Vaf Feldinventar, Vaf Fragebogen Input Leitfaden, Vaf Fremdsprachige Vertraege Bilingual: Vaf Feldinventar; Vaf Fragebogen Input Leitfaden; Vaf Fremdsprachige Vertraege Bilingual. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislo... |
| `vaf-plausibilitaetscheck-vaf-termsheet-altvertraege` | Vaf Plausibilitaetscheck, Vaf Termsheet Mapping, Spezial Altvertraege Dokumentenmatrix Und Lueckenliste: Vaf Plausibilitaetscheck; Vaf Termsheet Mapping; Spezial Altvertraege Dokumentenmatrix Und Lueckenliste. Führt Intake, Prüfroutine,... |
| `vaf-quality-vaf-redline-vaf-rueckfrageninterview` | Vaf Quality Gate, Vaf Redline Qa, Vaf Rueckfrageninterview: Vaf Quality Gate; Vaf Redline Qa; Vaf Rueckfrageninterview. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zusammen. |
| `vaf-template-vaf-template-vaf-track` | Vaf Template Erkennung, Vaf Template Format Und Source, Vaf Track Changes Nur Nach Frage: Vaf Template Erkennung; Vaf Template Format Und Source; Vaf Track Changes Nur Nach Frage. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislo... |
| `vaf-vaf-mehrsprachige-vaf-platzhalterlogik` | Vaf Kommandocenter, Vaf Mehrsprachige Vertraege Spezial, Vaf Platzhalterlogik Bauleiter: Vaf Kommandocenter; Vaf Mehrsprachige Vertraege Spezial; Vaf Platzhalterlogik Bauleiter. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogi... |
| `vaf-versionierung` | Vaf Versionierung Aenderungsverfolgung Spezial: Vaf Versionierung Aenderungsverfolgung Spezial. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zusammen. |
| `vorlagen-vertragsausfueller-vaf-altvertrag` | Spezial Vorlagen Fristen Form Und Zustaendigkeit, Spezial Vertragsausfueller Erstpruefung Und Mandatsziel, Vaf Altvertrag Nachziehen: Spezial Vorlagen Fristen Form Und Zustaendigkeit; Spezial Vertragsausfueller Erstpruefung Und Mandatszi... |
| `workflow-anschluss-skills-router` | Anschluss-Skills Router im Plugin vertragsausfueller: schlägt nach der ersten Prüfung die passenden Spezialskills aus demselben Plugin vor. |
| `workflow-dokumentenintake` | Dokumentenintake im Plugin vertragsausfueller: liest Uploads, sortiert Dokumentarten, markiert Fristen und baut eine knappe Arbeitsakte. |
| `workflow-kaltstart-und-routing` | Kaltstart und Routing im Plugin vertragsausfueller: führt vom ersten Satz oder Dokument in den passenden Arbeitsweg, erkennt Rolle, Ziel, Risiko und Anschluss-Skills. |
| `workflow-mandantenkommunikation-redteam-qualitygate` | Workflow Mandantenkommunikation, Workflow Redteam Qualitygate, Spezial Ausdruecklicher Fristennotiz Und Naechster Schritt: Workflow Mandantenkommunikation; Workflow Redteam Qualitygate; Spezial Ausdruecklicher Fristennotiz Und Naechster... |
| `workflow-output-waehlen` | Output wählen im Plugin vertragsausfueller: entscheidet zwischen Memo, Schriftsatz, Tabelle, Brief, Checkliste, Vermerk, Redline oder Mandantenübersetzung. |
| `workflow-rechtsquellen-livecheck` | Rechtsquellen-Livecheck im Plugin vertragsausfueller: zwingt vor tragenden Aussagen zum aktuellen Quellencheck bei Gesetzen, Behörden, Gerichten und Formularen. |
| `workflow-unterlagen-lueckenliste` | Unterlagen- und Lückenliste im Plugin vertragsausfueller: erstellt eine präzise Nachforderungsliste statt allgemeiner Fragebögen. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
