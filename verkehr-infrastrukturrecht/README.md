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
| `allgemein-anschluss-router-workflow-chronologie` | Allgemein, Workflow Anschluss Skills Router, Workflow Chronologie Und Belegmatrix: Allgemein; Workflow Anschluss Skills Router; Workflow Chronologie Und Belegmatrix. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmus... |
| `autonomous-driving-interessen-grossprojekt` | Spezial Autonomous Compliance Dokumentation Und Akte, Spezial Driving Mehrparteien Konflikt Und Interessen, Spezial Grossprojekt Zahlen Schwellen Und Berechnung: Spezial Autonomous Compliance Dokumentation Und Akte; Spezial Driving Mehrp... |
| `foerderung-vergabe-ladeinfrastruktur-planfeststellung` | Verkehr Infrastrukturrecht Foerderung Vergabe, Verkehr Infrastrukturrecht Ladeinfrastruktur, Verkehr Infrastrukturrecht Planfeststellung: Verkehr Infrastrukturrecht Foerderung Vergabe; Verkehr Infrastrukturrecht Ladeinfrastruktur; Verkeh... |
| `infrastruktur-foerderung-nachhaltige-bahninfrastruktur` | Infrastruktur Foerderung Uebersicht, Nachhaltige Bahninfrastruktur Emissionen, Planfeststellung Grundzuege: Infrastruktur Foerderung Uebersicht; Nachhaltige Bahninfrastruktur Emissionen; Planfeststellung Grundzuege. Führt Intake, Prüfrou... |
| `infrastrukturrecht-intake-ladeinfrastruktur` | Spezial Infrastrukturrecht Tatbestand Beweis Und Belege, Spezial Intake Mandantenkommunikation Entscheidungsvorlage, Spezial Ladeinfrastruktur Behörden Gericht Und Registerweg: Spezial Infrastrukturrecht Tatbestand Beweis Und Belege; Spe... |
| `livecheck-sonderfall-mobilitaetsprojekt-intake` | Spezial Livecheck Sonderfall Und Edge Case, Spezial Mobilitaetsprojekt Intake, Spezial Mobilitaetsprojekt Red Team Und Qualitaetskontrolle: Spezial Livecheck Sonderfall Und Edge Case; Spezial Mobilitaetsprojekt Intake; Spezial Mobilitaet... |
| `parkraum-planfeststellung-strassenbahn` | Spezial Parkraum Schriftsatz Brief Und Memo Bausteine, Spezial Planfeststellung Dokumentenmatrix Und Lueckenliste, Spezial Strassenbahn Risikoampel Und Gegenargumente: Spezial Parkraum Schriftsatz Brief Und Memo Bausteine; Spezial Planfe... |
| `parkraumbewirtschaftung-verkehr-infrastrukturrecht` | Spezial Parkraumbewirtschaftung Formular Portal Und Einreichung, Verkehr Infrastrukturrecht Parkraumbewirtschaftung, Spezial Planfeststellung Grossprojekt: Spezial Parkraumbewirtschaftung Formular Portal Und Einreichung; Verkehr Infrastr... |
| `schulwegsicherheit-sondernutzung-strassenbahn` | Verkehr Infrastrukturrecht Schulwegsicherheit, Verkehr Infrastrukturrecht Sondernutzung, Verkehr Infrastrukturrecht Strassenbahn: Verkehr Infrastrukturrecht Schulwegsicherheit; Verkehr Infrastrukturrecht Sondernutzung; Verkehr Infrastruk... |
| `spezial-rechtsquellen-beweislast-und-darlegungslast` | Rechtsquellen: Beweislast, Darlegungslast und Substantiierung im Plugin verkehr infrastrukturrecht; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Standardprüfung. |
| `spezial-verkehr-livequellen-und-rechtsprechungscheck` | Verkehr: Livequellen- und Rechtsprechungscheck im Plugin verkehr infrastrukturrecht; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Standardprüfung. |
| `strassenrecht-verkehrs-verkehrswende` | Spezial Strassenrecht Internationaler Bezug Und Schnittstellen, Spezial Verkehrs Erstpruefung Und Mandatsziel, Spezial Verkehrswende Verhandlung Vergleich Und Eskalation: Spezial Strassenrecht Internationaler Bezug Und Schnittstellen; Sp... |
| `verkehr-infrastrukturrecht-autonomous-driving-buergerentscheid` | Verkehr Infrastrukturrecht Kommandocenter, Autonomous Driving Strassenrecht, Buergerentscheid Strassenbahn Spezial: Verkehr Infrastrukturrecht Kommandocenter; Autonomous Driving Strassenrecht; Buergerentscheid Strassenbahn Spezial. Führt... |
| `verkehrsplanung-verfahren-vertragsmodell-strasse` | Spezial Verkehrsplanung Fristen Form Und Zustaendigkeit, Verkehr Infrastrukturrecht Verfahren, Vertragsmodell Strasse App Spezial: Spezial Verkehrsplanung Fristen Form Und Zustaendigkeit; Verkehr Infrastrukturrecht Verfahren; Vertragsmod... |
| `verkehrsplanung-verkehrswende-wirtschaftsverkehr` | Verkehr Infrastrukturrecht Verkehrsplanung, Verkehr Infrastrukturrecht Verkehrswende, Verkehr Infrastrukturrecht Wirtschaftsverkehr: Verkehr Infrastrukturrecht Verkehrsplanung; Verkehr Infrastrukturrecht Verkehrswende; Verkehr Infrastruk... |
| `vi-rechtsquellen-uebersicht` | Rechtsquellen Verkehrs- und Infrastrukturrecht: BFStrG, PBefG, AEG, EnWG-Trasse, BImSchG, BNatSchG, WHG, VwVfG, UVPG. Pro Norm: Anwendungsbereich, Verfahrensart, Aufsicht. Entscheidungstabelle fuer ein konkretes Infrastrukturvorhaben. |
| `vifr-aeg-bahnrecht-deutschlandticket-tarifrecht` | Vifr Aeg Bahnrecht Leitfaden, Vifr Deutschlandticket Tarifrecht Spezial, Vifr Luftverkehrsrecht Flughafen Spezial: Vifr Aeg Bahnrecht Leitfaden; Vifr Deutschlandticket Tarifrecht Spezial; Vifr Luftverkehrsrecht Flughafen Spezial. Führt I... |
| `vifr-planfeststellung` | Vifr Planfeststellung Strasse Bauleiter: Vifr Planfeststellung Strasse Bauleiter. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zusammen. |
| `workflow-dokumentenintake` | Dokumentenintake im Plugin verkehr-infrastrukturrecht: liest Uploads, sortiert Dokumentarten, markiert Fristen und baut eine knappe Arbeitsakte. |
| `workflow-fristen-risikoampel-mandantenkommunikation-redteam` | Workflow Fristen Und Risikoampel, Workflow Mandantenkommunikation, Workflow Redteam Qualitygate: Workflow Fristen Und Risikoampel; Workflow Mandantenkommunikation; Workflow Redteam Qualitygate. Führt Intake, Prüfroutine, Normen-/Quellenr... |
| `workflow-kaltstart-und-routing` | Kaltstart und Routing im Plugin verkehr-infrastrukturrecht: führt vom ersten Satz oder Dokument in den passenden Arbeitsweg, erkennt Rolle, Ziel, Risiko und Anschluss-Skills. |
| `workflow-output-waehlen` | Output wählen im Plugin verkehr-infrastrukturrecht: entscheidet zwischen Memo, Schriftsatz, Tabelle, Brief, Checkliste, Vermerk, Redline oder Mandantenübersetzung. |
| `workflow-rechtsquellen-livecheck` | Rechtsquellen-Livecheck im Plugin verkehr-infrastrukturrecht: zwingt vor tragenden Aussagen zum aktuellen Quellencheck bei Gesetzen, Behörden, Gerichten und Formularen. |
| `workflow-unterlagen-lueckenliste` | Unterlagen- und Lückenliste im Plugin verkehr-infrastrukturrecht: erstellt eine präzise Nachforderungsliste statt allgemeiner Fragebögen. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
