# Umweltrecht

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`umweltrecht`) | [`umweltrecht.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/umweltrecht.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **Märkische Reserve Süd — Batteriespeicher Brandenburg/Berlin** (`batteriespeicher-brandenburg-berlin-resilienz`) | [Gesamt-PDF lesen](../testakten/batteriespeicher-brandenburg-berlin-resilienz/gesamt-pdf/batteriespeicher-brandenburg-berlin-resilienz_gesamt.pdf) | [`testakte-batteriespeicher-brandenburg-berlin-resilienz.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-batteriespeicher-brandenburg-berlin-resilienz.zip) |
| **Projekt Isarlicht — Kernfusion und Transrapid am Starnberger See** (`kernfusion-transrapid-starnberger-see`) | [Gesamt-PDF lesen](../testakten/kernfusion-transrapid-starnberger-see/gesamt-pdf/kernfusion-transrapid-starnberger-see_gesamt.pdf) | [`testakte-kernfusion-transrapid-starnberger-see.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-kernfusion-transrapid-starnberger-see.zip) |
| **Akte Umweltrecht: Industrieanlage — Genehmigung, Emissionshandel, Altlast und Transaktion** (`umweltrecht-industrieanlage-genehmigung`) | [Gesamt-PDF lesen](../testakten/umweltrecht-industrieanlage-genehmigung/gesamt-pdf/umweltrecht-industrieanlage-genehmigung_gesamt.pdf) | [`testakte-umweltrecht-industrieanlage-genehmigung.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-umweltrecht-industrieanlage-genehmigung.zip) |
| **Umweltverbandsakte Moorbach** (`umweltschutzverband-windpark-moorbach-umwrg`) | [Gesamt-PDF lesen](../testakten/umweltschutzverband-windpark-moorbach-umwrg/gesamt-pdf/umweltschutzverband-windpark-moorbach-umwrg_gesamt.pdf) | [`testakte-umweltschutzverband-windpark-moorbach-umwrg.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-umweltschutzverband-windpark-moorbach-umwrg.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

Vollständiger Umweltrechts-Assistent für Anlagenbetreiber, Verbände, Investoren, Kommunen und öffentliche Hand: Emissionshandel, Immissionsschutz, Abfall, Wasser, Boden, Naturschutz, Umweltinformation, Verfahren, Sanktionen und Transaktionen.

Dieses Plugin ist **vollständig freistehend**. Es erwartet keine anderen Plugins, keine externen Agenten und keine besonderen Repo-Dateien außerhalb seines eigenen Ordners. Wenn ein Anschluss an Register, Behördenportale, E-Mail, beA, Datenraum, Bank, GIS, Tabellen oder Kanzleisoftware fehlt, arbeitet es mit manuellen Uploads oder mit einem gekennzeichneten Simulationsmodus.

## Schnellstart

1. Plugin aktivieren oder die ZIP aus dem Release installieren.
2. Eine neue Sache mit `umweltrecht-kommandocenter` starten.
3. Mandant, Ziel, Frist, Dokumente und gewünschtes Ergebnis nennen.
4. Bei fehlenden Systemanschlüssen `Simulation` sagen; das Plugin erzeugt dann realistische Testdaten und erklärt, welche echte Schnittstelle später ersetzt werden müsste.
5. Am Ende immer das Qualitätstor ausgeben lassen: offene Annahmen, Fristen, Rechenprüfung, Anlagen, Zuständigkeiten und nächste Schritte.

## Enthaltene Skills

- `umweltrecht-kommandocenter` - Umweltrecht-Kommandocenter
- `umweltrecht-emissionshandel-tehg` - Emissionshandel und TEHG
- `umweltrecht-immissionsschutz-bimschg` - Immissionsschutz und BImSchG
- `umweltrecht-stoerfall-anlagen` - Störfall, Anlagenbetrieb und Betreiberpflichten
- `umweltrecht-abfall-circular-economy` - Abfallrecht und Circular Economy
- `umweltrecht-wasser-bodenschutz` - Wasser- und Bodenschutzrecht
- `umweltrecht-naturschutz-artenschutz` - Naturschutz und Artenschutz
- `umweltrecht-umweltinformation-uig-ifg` - Umweltinformation nach UIG und IFG
- `umweltrecht-verfahren` - Umweltrechtliche Verwaltungs- und Gerichtsverfahren
- `umweltrecht-bussgeld-sanktionen` - Bußgeld, Sanktionen und Anhörung
- `umweltrecht-transaktionen-dd` - Umweltrechtliche Transaktions-Due-Diligence
- `umweltrecht-compliance-schulung` - Compliance, Beauftragte und Schulung
- `klimaklagen-verbandsklage-umwrg` - Klimaklagen, Verbandsklage UmwRG, EGMR Klima-Seniorinnen
- `lksg-csddd-lieferkettensorgfalt` - Lieferkettensorgfalt LkSG und CSDDD-Richtlinie (EU) 2024/1760
- `esg-greenwashing-csrd` - ESG-Greenwashing, CSRD-Umsetzung, ESRS, UWG-Werbung

## Vorlagen

- `assets/templates/umwelt-mandatskarte.md` - Umweltrecht-Mandatskarte
- `assets/templates/tehg-zuteilung-check.md` - TEHG-Zuteilungs- und Sanktionscheck
- `assets/templates/bimschg-genehmigungsfahrplan.md` - BImSchG-Genehmigungsfahrplan
- `assets/templates/stoerfall-anlagenmatrix.md` - Störfall- und Anlagenpflichtenmatrix
- `assets/templates/abfall-circular-matrix.md` - Abfall- und Circular-Economy-Matrix
- `assets/templates/wasser-boden-pruefplan.md` - Wasser- und Boden-Prüfplan
- `assets/templates/naturschutz-artenschutz-check.md` - Naturschutz- und Artenschutzcheck
- `assets/templates/uig-ifg-verfahren.md` - UIG/IFG-Verfahrenskarte
- `assets/templates/umweltverfahren-fristen.md` - Umwelt-Verfahrens- und Fristenplan
- `assets/templates/bussgeld-verteidigungsplan.md` - Bußgeld-Verteidigungsplan Umwelt
- `assets/templates/umwelt-dd-grid.md` - Umwelt-DD-Grid
- `assets/templates/schulung-beauftragte-plan.md` - Schulungs- und Beauftragtenplan

## Freistehende Leitplanken

- Keine stillen Verweise auf andere Plugins.
- Keine produktive Rechtsberatung ohne anwaltliche Prüfung.
- Keine echten Mandatsgeheimnisse in ungeprüfte Cloud- oder KI-Umgebungen.
- Keine erfundenen Fundstellen; unsichere Normen und Rechtsprechung werden als Prüfbedarf markiert.
- Zahlen, Fristen, Schwellenwerte und Zuständigkeiten werden sichtbar hergeleitet oder als Annahme gekennzeichnet.
- Ausgabe immer so, dass eine Berufsträgerin oder ein Berufsträger sie sofort prüfen, kürzen, freigeben oder verwerfen kann.

<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 24 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `abfall-anlagen-bimschg` | Spezial Abfall Dokumentenmatrix Und Lueckenliste, Spezial Anlagen Abschlussprodukt Und Übergabe, Spezial Bimschg Tatbestand Beweis Und Belege: Spezial Abfall Dokumentenmatrix Und Lueckenliste; Spezial Anlagen Abschlussprodukt Und Übergab... |
| `allgemein-workflow-chronologie-workflow-fristen` | Allgemein, Workflow Chronologie Und Belegmatrix, Workflow Fristen Und Risikoampel: Allgemein; Workflow Chronologie Und Belegmatrix; Workflow Fristen Und Risikoampel. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmus... |
| `boden-csddd-csrd-sonderfall` | Spezial Boden Behörden Gericht Und Registerweg, Spezial Csddd Mandantenkommunikation Entscheidungsvorlage, Spezial Csrd Sonderfall Und Edge Case: Spezial Boden Behörden Gericht Und Registerweg; Spezial Csddd Mandantenkommunikation Entsch... |
| `diligence-greenwashing-beweislast-klimaklagen-interessen` | Spezial Diligence Compliance Dokumentation Und Akte, Spezial Greenwashing Beweislast Und Darlegungslast, Spezial Klimaklagen Mehrparteien Konflikt Und Interessen: Spezial Diligence Compliance Dokumentation Und Akte; Spezial Greenwashing... |
| `esg-greenwashing-klimaklagen-verbandsklage-lksg-csddd` | Esg Greenwashing Csrd, Klimaklagen Verbandsklage Umwrg, Lksg Csddd Lieferkettensorgfalt: Esg Greenwashing Csrd; Klimaklagen Verbandsklage Umwrg; Lksg Csddd Lieferkettensorgfalt. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogi... |
| `lieferkettensorgfalt-lksg-red-naturschutz` | Spezial Lieferkettensorgfalt Formular Portal Und Einreichung, Spezial Lksg Red Team Und Qualitaetskontrolle, Spezial Naturschutz Schriftsatz Brief Und Memo Bausteine: Spezial Lieferkettensorgfalt Formular Portal Und Einreichung; Spezial... |
| `spezial-bussgeld-livequellen-und-rechtsprechungscheck` | Bussgeld: Livequellen- und Rechtsprechungscheck im Plugin umweltrecht; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Standardprüfung. |
| `stoerfall-anlagen-transaktionen-dd-umweltinformation-uig` | Umweltrecht Stoerfall Anlagen, Umweltrecht Transaktionen Dd, Umweltrecht Umweltinformation Uig Ifg: Umweltrecht Stoerfall Anlagen; Umweltrecht Transaktionen Dd; Umweltrecht Umweltinformation Uig Ifg. Führt Intake, Prüfroutine, Normen-/Qu... |
| `tehg-verfahren-umweltrecht-verfahren` | Spezial Tehg Fristen Form Und Zustaendigkeit, Spezial Verfahren Verhandlung Vergleich Und Eskalation, Umweltrecht Verfahren: Spezial Tehg Fristen Form Und Zustaendigkeit; Spezial Verfahren Verhandlung Vergleich Und Eskalation; Umweltrech... |
| `umwelt-umweltrecht-umwrg` | Spezial Umwelt Zahlen Schwellen Und Berechnung, Spezial Umweltrecht Erstpruefung Und Mandatsziel, Spezial Umwrg Internationaler Bezug Und Schnittstellen: Spezial Umwelt Zahlen Schwellen Und Berechnung; Spezial Umweltrecht Erstpruefung Un... |
| `umweltrecht-bussgeld-emissionshandel-tehg-uwr-ets` | Umweltrecht Bussgeld Sanktionen, Umweltrecht Emissionshandel Tehg, Uwr Emissionshandel Ets Spezial: Umweltrecht Bussgeld Sanktionen; Umweltrecht Emissionshandel Tehg; Uwr Emissionshandel Ets Spezial. Führt Intake, Prüfroutine, Normen-/Qu... |
| `umweltrecht-immissionsschutz-bimschg-naturschutz-artenschutz` | Umweltrecht Immissionsschutz Bimschg, Umweltrecht Kommandocenter, Umweltrecht Naturschutz Artenschutz: Umweltrecht Immissionsschutz Bimschg; Umweltrecht Kommandocenter; Umweltrecht Naturschutz Artenschutz. Führt Intake, Prüfroutine, Norm... |
| `uwr-bundesnaturschutzgesetz-uwr-co2-uwr-immissionsschutz` | Uwr Bundesnaturschutzgesetz Eingriff Spezial, Uwr Co2 Emissionshandel Spezial, Uwr Immissionsschutz Praxis: Uwr Bundesnaturschutzgesetz Eingriff Spezial; Uwr Co2 Emissionshandel Spezial; Uwr Immissionsschutz Praxis. Führt Intake, Prüfrou... |
| `uwr-einfuehrung-rechtsquellen` | Umweltrecht einfuehrend: BImSchG, BNatSchG, WHG, KrWG, BBodSchG, USchadG, EU-IED, REACH. Pro Norm Anwendungsbereich, Aufsicht, typische Mandantenfragen. Entscheidungstabelle. |
| `uwr-wasserrechtliche` | Uwr Wasserrechtliche Erlaubnis Leitfaden: Uwr Wasserrechtliche Erlaubnis Leitfaden. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zusammen. |
| `wasser-abfall-circular-umweltrecht-schulung` | Spezial Wasser Risikoampel Und Gegenargumente, Umweltrecht Abfall Circular Economy, Umweltrecht Compliance Schulung: Spezial Wasser Risikoampel Und Gegenargumente; Umweltrecht Abfall Circular Economy; Umweltrecht Compliance Schulung. Füh... |
| `wasser-bodenschutz-uwr-altlasten-uwr-bimschg` | Umweltrecht Wasser Bodenschutz, Uwr Altlasten Prüfung Spezial, Uwr Bimschg Genehmigung Bauleiter: Umweltrecht Wasser Bodenschutz; Uwr Altlasten Prüfung Spezial; Uwr Bimschg Genehmigung Bauleiter. Führt Intake, Prüfroutine, Normen-/Quelle... |
| `workflow-anschluss-skills-router` | Anschluss-Skills Router im Plugin umweltrecht: schlägt nach der ersten Prüfung die passenden Spezialskills aus demselben Plugin vor. |
| `workflow-dokumentenintake` | Dokumentenintake im Plugin umweltrecht: liest Uploads, sortiert Dokumentarten, markiert Fristen und baut eine knappe Arbeitsakte. |
| `workflow-kaltstart-und-routing` | Kaltstart und Routing im Plugin umweltrecht: führt vom ersten Satz oder Dokument in den passenden Arbeitsweg, erkennt Rolle, Ziel, Risiko und Anschluss-Skills. |
| `workflow-mandantenkommunikation-workflow-redteam-stoerfall` | Workflow Mandantenkommunikation, Workflow Redteam Qualitygate, Spezial Stoerfall Fristennotiz Und Naechster Schritt: Workflow Mandantenkommunikation; Workflow Redteam Qualitygate; Spezial Stoerfall Fristennotiz Und Naechster Schritt. Füh... |
| `workflow-output-waehlen` | Output wählen im Plugin umweltrecht: entscheidet zwischen Memo, Schriftsatz, Tabelle, Brief, Checkliste, Vermerk, Redline oder Mandantenübersetzung. |
| `workflow-rechtsquellen-livecheck` | Rechtsquellen-Livecheck im Plugin umweltrecht: zwingt vor tragenden Aussagen zum aktuellen Quellencheck bei Gesetzen, Behörden, Gerichten und Formularen. |
| `workflow-unterlagen-lueckenliste` | Unterlagen- und Lückenliste im Plugin umweltrecht: erstellt eine präzise Nachforderungsliste statt allgemeiner Fragebögen. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
