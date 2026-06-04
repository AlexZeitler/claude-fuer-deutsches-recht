# Verkehrs- und Infrastrukturrecht

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`verkehr-infrastrukturrecht`) | [`verkehr-infrastrukturrecht.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/verkehr-infrastrukturrecht.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **Märkische Reserve Süd — Batteriespeicher Brandenburg/Berlin** (`batteriespeicher-brandenburg-berlin-resilienz`) | [Gesamt-PDF lesen](../testakten/batteriespeicher-brandenburg-berlin-resilienz/gesamt-pdf/batteriespeicher-brandenburg-berlin-resilienz_gesamt.pdf) | [`testakte-batteriespeicher-brandenburg-berlin-resilienz.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-batteriespeicher-brandenburg-berlin-resilienz.zip) |
| **Projekt Isarlicht — Kernfusion und Transrapid am Starnberger See** (`kernfusion-transrapid-starnberger-see`) | [Gesamt-PDF lesen](../testakten/kernfusion-transrapid-starnberger-see/gesamt-pdf/kernfusion-transrapid-starnberger-see_gesamt.pdf) | [`testakte-kernfusion-transrapid-starnberger-see.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-kernfusion-transrapid-starnberger-see.zip) |
| **Akte Verkehrs- und Infrastrukturrecht: Straßenbahn Linie 7, Ladezonen und Schulwegsicherheit** (`verkehr-infrastrukturrecht-strassenbahn-ladezonen`) | [Gesamt-PDF lesen](../testakten/verkehr-infrastrukturrecht-strassenbahn-ladezonen/gesamt-pdf/verkehr-infrastrukturrecht-strassenbahn-ladezonen_gesamt.pdf) | [`testakte-verkehr-infrastrukturrecht-strassenbahn-ladezonen.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-verkehr-infrastrukturrecht-strassenbahn-ladezonen.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

Vollständiger Assistent für Verkehrsplanung, Infrastrukturprojekte, Elektromobilität, Straßenbahn, Sondernutzung, Parkraumbewirtschaftung, Liefer- und Ladezonen, Verkehrswende, Schulwegsicherheit, Fördermittel und Vergabe.

Dieses Plugin ist **vollständig freistehend**. Es erwartet keine anderen Plugins, keine externen Agenten und keine besonderen Repo-Dateien außerhalb seines eigenen Ordners. Wenn ein Anschluss an Register, Behördenportale, E-Mail, beA, Datenraum, Bank, GIS, Tabellen oder Kanzleisoftware fehlt, arbeitet es mit manuellen Uploads oder mit einem gekennzeichneten Simulationsmodus.

## Schnellstart

1. Plugin aktivieren oder die ZIP aus dem Release installieren.
2. Eine neue Sache mit `verkehr-infrastrukturrecht-kommandocenter` starten.
3. Mandant, Ziel, Frist, Dokumente und gewünschtes Ergebnis nennen.
4. Bei fehlenden Systemanschlüssen `Simulation` sagen; das Plugin erzeugt dann realistische Testdaten und erklärt, welche echte Schnittstelle später ersetzt werden müsste.
5. Am Ende immer das Qualitätstor ausgeben lassen: offene Annahmen, Fristen, Rechenprüfung, Anlagen, Zuständigkeiten und nächste Schritte.

## Enthaltene Skills

- `verkehr-infrastrukturrecht-kommandocenter` - Verkehrs- und Infrastruktur-Kommandocenter
- `verkehr-infrastrukturrecht-verkehrsplanung` - Verkehrsplanung und Projektstrategie
- `verkehr-infrastrukturrecht-planfeststellung` - Planfeststellung und Abwägung
- `verkehr-infrastrukturrecht-strassenbahn` - Straßenbahn- und ÖPNV-Projekte
- `verkehr-infrastrukturrecht-ladeinfrastruktur` - Ladeinfrastruktur und Elektromobilität
- `verkehr-infrastrukturrecht-sondernutzung` - Sondernutzung, Widmung und Straßenrecht
- `verkehr-infrastrukturrecht-parkraumbewirtschaftung` - Parkraumbewirtschaftung
- `verkehr-infrastrukturrecht-wirtschaftsverkehr` - Wirtschaftsverkehr, Liefer- und Ladezonen
- `verkehr-infrastrukturrecht-verkehrswende` - Verkehrswende und Verkehrsberuhigung
- `verkehr-infrastrukturrecht-schulwegsicherheit` - Schulwegsicherheit
- `verkehr-infrastrukturrecht-verfahren` - Verkehrsrechtliche Verfahren und Streit
- `verkehr-infrastrukturrecht-foerderung-vergabe` - Förderung und Vergabe Infrastruktur

## Vorlagen

- `assets/templates/verkehr-mandatskarte.md` - Verkehrs- und Infrastruktur-Mandatskarte
- `assets/templates/infrastruktur-projektfahrplan.md` - Infrastruktur-Projektfahrplan
- `assets/templates/planfeststellung-abwaegungsmatrix.md` - Planfeststellungs- und Abwägungsmatrix
- `assets/templates/strassenbahn-workstream-plan.md` - Straßenbahn-Workstream-Plan
- `assets/templates/ladeinfrastruktur-check.md` - Ladeinfrastruktur-Check
- `assets/templates/sondernutzung-erlaubnis.md` - Sondernutzung und Straßenrecht
- `assets/templates/parkraumkonzept.md` - Parkraumbewirtschaftungskonzept
- `assets/templates/liefer-ladeflaechen-konzept.md` - Liefer- und Ladeflächenkonzept
- `assets/templates/verkehrswende-massnahmenplan.md` - Verkehrswende-Maßnahmenplan
- `assets/templates/schulwegsicherheit-check.md` - Schulwegsicherheitscheck
- `assets/templates/verkehrsverfahren-fristen.md` - Verkehrs-Verfahrens- und Fristenplan
- `assets/templates/foerderung-vergabe-matrix.md` - Förder- und Vergabematrix

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
| `kompendium-01-allgemein-bis-workflow-chronologie` | verkehr-infrastrukturrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Allgemein, Anschluss Skills Router, Chronologie Und Belegmatrix; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitä... |
| `kompendium-02-workflow-fristen-und-bis-workflow-redteam-qua` | verkehr-infrastrukturrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Fristen Und Risikoampel, Mandantenkommunikation, Redteam Qualitygate; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qu... |
| `kompendium-03-spezial-verkehrsplan-bis-vertragsmodell-stras` | verkehr-infrastrukturrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Verkehrsplanung Fristen Form Und Zustaendigkeit, Verkehr Infrastrukturrecht Verfahren, Vertragsmodell Strasse App Spezial; mit Intake, Prüfroutine, N... |
| `kompendium-04-spezial-parkraumbewi-bis-spezial-planfeststel` | verkehr-infrastrukturrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Parkraumbewirtschaftung Formular Portal Und Einreichung, Verkehr Infrastrukturrecht Parkraumbewirtschaftung, Planfeststellung Grossprojekt; mit Intak... |
| `kompendium-05-verkehr-infrastruktu-bis-buergerentscheid-str` | verkehr-infrastrukturrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Verkehr Infrastrukturrecht Kommandocenter, Autonomous Driving Strassenrecht, Buergerentscheid Strassenbahn Spezial; mit Intake, Prüfroutine, Normen-/... |
| `kompendium-06-infrastruktur-foerde-bis-planfeststellung-gru` | verkehr-infrastrukturrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Infrastruktur Foerderung Uebersicht, Nachhaltige Bahninfrastruktur Emissionen, Planfeststellung Grundzuege; mit Intake, Prüfroutine, Normen-/Quellenr... |
| `kompendium-07-spezial-autonomous-c-bis-spezial-grossprojekt` | verkehr-infrastrukturrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Autonomous Compliance Dokumentation Und Akte, Driving Mehrparteien Konflikt Und Interessen, Grossprojekt Zahlen Schwellen Und Berechnung; mit Intake,... |
| `kompendium-08-spezial-infrastruktu-bis-spezial-ladeinfrastr` | verkehr-infrastrukturrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Infrastrukturrecht Tatbestand Beweis Und Belege, Intake Mandantenkommunikation Entscheidungsvorlage, Ladeinfrastruktur Behoerden Gericht Und Register... |
| `kompendium-09-spezial-livecheck-so-bis-spezial-mobilitaetsp` | verkehr-infrastrukturrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Livecheck Sonderfall Und Edge Case, Mobilitaetsprojekt Intake, Mobilitaetsprojekt Red Team Und Qualitaetskontrolle; mit Intake, Prüfroutine, Normen-/... |
| `kompendium-10-spezial-parkraum-sch-bis-spezial-strassenbahn` | verkehr-infrastrukturrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Parkraum Schriftsatz Brief Und Memo Bausteine, Planfeststellung Dokumentenmatrix Und Lueckenliste, Strassenbahn Risikoampel Und Gegenargumente; mit I... |
| `kompendium-11-spezial-strassenrech-bis-spezial-verkehrswend` | verkehr-infrastrukturrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Strassenrecht Internationaler Bezug Und Schnittstellen, Verkehrs Erstpruefung Und Mandatsziel, Verkehrswende Verhandlung Vergleich Und Eskalation; mi... |
| `kompendium-12-verkehr-infrastruktu-bis-verkehr-infrastruktu` | verkehr-infrastrukturrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Verkehr Infrastrukturrecht Foerderung Vergabe, Verkehr Infrastrukturrecht Ladeinfrastruktur, Verkehr Infrastrukturrecht Planfeststellung; mit Intake,... |
| `kompendium-13-verkehr-infrastruktu-bis-verkehr-infrastruktu` | verkehr-infrastrukturrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Verkehr Infrastrukturrecht Schulwegsicherheit, Verkehr Infrastrukturrecht Sondernutzung, Verkehr Infrastrukturrecht Strassenbahn; mit Intake, Prüfrou... |
| `kompendium-14-verkehr-infrastruktu-bis-verkehr-infrastruktu` | verkehr-infrastrukturrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Verkehr Infrastrukturrecht Verkehrsplanung, Verkehr Infrastrukturrecht Verkehrswende, Verkehr Infrastrukturrecht Wirtschaftsverkehr; mit Intake, Prüf... |
| `kompendium-15-vifr-aeg-bahnrecht-l-bis-vifr-luftverkehrsrec` | verkehr-infrastrukturrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Vifr Aeg Bahnrecht Leitfaden, Vifr Deutschlandticket Tarifrecht Spezial, Vifr Luftverkehrsrecht Flughafen Spezial; mit Intake, Prüfroutine, Normen-/Q... |
| `kompendium-16-vifr-planfeststellun-bis-vifr-planfeststellun` | verkehr-infrastrukturrecht: eigenständiger Arbeits-Skill zu Vifr Planfeststellung Strasse Bauleiter; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck. |
| `spezial-rechtsquellen-beweislast-und-darlegungslast` | Rechtsquellen: Beweislast, Darlegungslast und Substantiierung im Plugin verkehr infrastrukturrecht; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Standardprüfung. |
| `spezial-verkehr-livequellen-und-rechtsprechungscheck` | Verkehr: Livequellen- und Rechtsprechungscheck im Plugin verkehr infrastrukturrecht; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Standardprüfung. |
| `vi-rechtsquellen-uebersicht` | Rechtsquellen Verkehrs- und Infrastrukturrecht: BFStrG, PBefG, AEG, EnWG-Trasse, BImSchG, BNatSchG, WHG, VwVfG, UVPG. Pro Norm: Anwendungsbereich, Verfahrensart, Aufsicht. Entscheidungstabelle fuer ein konkretes Infrastrukturvorhaben. |
| `workflow-dokumentenintake` | Dokumentenintake im Plugin verkehr-infrastrukturrecht: liest Uploads, sortiert Dokumentarten, markiert Fristen und baut eine knappe Arbeitsakte. |
| `workflow-kaltstart-und-routing` | Kaltstart und Routing im Plugin verkehr-infrastrukturrecht: führt vom ersten Satz oder Dokument in den passenden Arbeitsweg, erkennt Rolle, Ziel, Risiko und Anschluss-Skills. |
| `workflow-output-waehlen` | Output wählen im Plugin verkehr-infrastrukturrecht: entscheidet zwischen Memo, Schriftsatz, Tabelle, Brief, Checkliste, Vermerk, Redline oder Mandantenübersetzung. |
| `workflow-rechtsquellen-livecheck` | Rechtsquellen-Livecheck im Plugin verkehr-infrastrukturrecht: zwingt vor tragenden Aussagen zum aktuellen Quellencheck bei Gesetzen, Behörden, Gerichten und Formularen. |
| `workflow-unterlagen-lueckenliste` | Unterlagen- und Lückenliste im Plugin verkehr-infrastrukturrecht: erstellt eine präzise Nachforderungsliste statt allgemeiner Fragebögen. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
