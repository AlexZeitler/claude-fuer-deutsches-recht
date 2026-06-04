# Energierecht

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`energierecht`) | [`energierecht.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/energierecht.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **Märkische Reserve Süd — Batteriespeicher Brandenburg/Berlin** (`batteriespeicher-brandenburg-berlin-resilienz`) | [Gesamt-PDF lesen](../testakten/batteriespeicher-brandenburg-berlin-resilienz/gesamt-pdf/batteriespeicher-brandenburg-berlin-resilienz_gesamt.pdf) | [`testakte-batteriespeicher-brandenburg-berlin-resilienz.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-batteriespeicher-brandenburg-berlin-resilienz.zip) |
| **Akte Energierecht: Stadtwerke Klotzkette AG – Quartier Hafenbogen** (`energierecht-stadtwerke-quartier`) | [Gesamt-PDF lesen](../testakten/energierecht-stadtwerke-quartier/gesamt-pdf/energierecht-stadtwerke-quartier_gesamt.pdf) | [`testakte-energierecht-stadtwerke-quartier.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-energierecht-stadtwerke-quartier.zip) |
| **Projekt Isarlicht — Kernfusion und Transrapid am Starnberger See** (`kernfusion-transrapid-starnberger-see`) | [Gesamt-PDF lesen](../testakten/kernfusion-transrapid-starnberger-see/gesamt-pdf/kernfusion-transrapid-starnberger-see_gesamt.pdf) | [`testakte-kernfusion-transrapid-starnberger-see.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-kernfusion-transrapid-starnberger-see.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

Vollständiger Energierechts-Assistent für Stadtwerke, Energieversorger, Wärmewirtschaft, energieintensive Unternehmen, Immobilienwirtschaft, Infrastrukturbetreiber, Contracting, Wasserstoff, E-Mobility, Transaktionen und Projektfinanzierung.

Dieses Plugin ist **vollständig freistehend**. Es erwartet keine anderen Plugins, keine externen Agenten und keine besonderen Repo-Dateien außerhalb seines eigenen Ordners. Wenn ein Anschluss an Register, Behördenportale, E-Mail, beA, Datenraum, Bank, GIS, Tabellen oder Kanzleisoftware fehlt, arbeitet es mit manuellen Uploads oder mit einem gekennzeichneten Simulationsmodus.

## Schnellstart

1. Plugin aktivieren oder die ZIP aus dem Release installieren.
2. Eine neue Sache mit `energierecht-kommandocenter` starten.
3. Mandant, Ziel, Frist, Dokumente und gewünschtes Ergebnis nennen.
4. Bei fehlenden Systemanschlüssen `Simulation` sagen; das Plugin erzeugt dann realistische Testdaten und erklärt, welche echte Schnittstelle später ersetzt werden müsste.
5. Am Ende immer das Qualitätstor ausgeben lassen: offene Annahmen, Fristen, Rechenprüfung, Anlagen, Zuständigkeiten und nächste Schritte.

## Enthaltene Skills

- `energierecht-kommandocenter` - Energierecht-Kommandocenter
- `energierecht-infrastrukturprojekte` - Energieinfrastrukturprojekte
- `energierecht-netz-speicher-zugang` - Netz-, Speicher- und Anschlussregulierung
- `energierecht-energievertraege` - Energieverträge
- `energierecht-vertrieb-marktrollen` - Energievertrieb und Marktrollen
- `energierecht-industriekunden` - Industriekunden und Kostenoptimierung
- `energierecht-eeg-kwkg-erzeugung` - EEG, KWKG und Erzeugung
- `energierecht-waerme-quartier` - Wärme, Quartier und Fernwärme
- `energierecht-emobility-wasserstoff` - E-Mobility, Wasserstoff und Power-to-Gas
- `energierecht-wettbewerb` - Energie und Wettbewerb
- `energierecht-verfahren` - Verwaltungs- und Gerichtsverfahren Energie
- `energierecht-transaktionen-dd` - Energierechtliche Transaktions-Due-Diligence
- `energierecht-projektfinanzierung` - Erneuerbare-Energien-Projektfinanzierung

## Vorlagen

- `assets/templates/energie-mandatskarte.md` - Energierecht-Mandatskarte
- `assets/templates/energie-projektphasenplan.md` - Projektphasenplan Energieinfrastruktur
- `assets/templates/netzanschluss-zugangsmatrix.md` - Netzanschluss- und Zugangsmatrix
- `assets/templates/energieliefervertrag-check.md` - Energieliefervertrag-Check
- `assets/templates/waerme-quartier-playbook.md` - Wärme- und Quartiers-Playbook
- `assets/templates/industrie-umlagen-check.md` - Industrie-Umlagen- und Entlastungscheck
- `assets/templates/eeg-kwkg-foerdermatrix.md` - EEG/KWKG-Fördermatrix
- `assets/templates/vertrieb-marktrollen-map.md` - Vertrieb- und Marktrollenkarte
- `assets/templates/transaktions-dd-energielaw.md` - Energierechtliche DD-Matrix
- `assets/templates/verwaltungsverfahren-energie.md` - Energie-Verfahrensplan
- `assets/templates/wasserstoff-ptg-check.md` - Wasserstoff- und Power-to-Gas-Check
- `assets/templates/energie-wettbewerb-uwg-kartell.md` - Energie-Wettbewerbscheck

## Freistehende Leitplanken

- Keine stillen Verweise auf andere Plugins.
- Keine produktive Rechtsberatung ohne anwaltliche Prüfung.
- Keine echten Mandatsgeheimnisse in ungeprüfte Cloud- oder KI-Umgebungen.
- Keine erfundenen Fundstellen; unsichere Normen und Rechtsprechung werden als Prüfbedarf markiert.
- Zahlen, Fristen, Schwellenwerte und Zuständigkeiten werden sichtbar hergeleitet oder als Annahme gekennzeichnet.
- Ausgabe immer so, dass eine Berufsträgerin oder ein Berufsträger sie sofort prüfen, kürzen, freigeben oder verwerfen kann.

<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 29 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `er-bess-kaltstart-projektaufnahme` | Batteriespeicherprojekt aufnehmen: Projektgröße, Standort, Netzebene, Betreiberrolle, Fristen, Unterlagen und Zieloutput. |
| `er-fusion-kaltstart-regulierungsweg` | Ordnet Fusionsreaktor-Projekt zwischen Atomrecht, Strahlenschutz, Baurecht, Immissionsschutz und Forschungsförderung. |
| `kompendium-01-allgemein-bis-workflow-fristen-und` | energierecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Allgemein, Anschluss Skills Router, Chronologie Und Belegmatrix, Fristen Und Risikoampel; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster... |
| `kompendium-02-workflow-mandantenko-bis-energierecht-verfahr` | energierecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Mandantenkommunikation, Output Waehlen, Redteam Qualitygate, Energierecht Verfahren; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Q... |
| `kompendium-03-spezial-livecheck-fr-bis-ppa-cppa-vertragsspe` | energierecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Livecheck Fristennotiz Und Naechster Schritt, Versorger Fristen Form Und Zustaendigkeit, Ladeinfrastruktur Spezial Vertragskette, Ppa Cppa Vertragsspezialitaeten;... |
| `kompendium-04-er-bess-produktsiche-bis-energierecht-eeg-kwk` | energierecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Er Bess Produktsicherheit Haftung, Er Bess Versicherung Und Schadenfall, Er Stakeholder Mapping Energie, Energierecht Eeg Kwkg Erzeugung; mit Intake, Prüfroutine,... |
| `kompendium-05-energierecht-emobili-bis-energierecht-infrast` | energierecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Energierecht Emobility Wasserstoff, Energierecht Energievertraege, Energierecht Industriekunden, Energierecht Infrastrukturprojekte; mit Intake, Prüfroutine, Norme... |
| `kompendium-06-energierecht-kommand-bis-energierecht-transak` | energierecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Energierecht Kommandocenter, Energierecht Netz Speicher Zugang, Energierecht Projektfinanzierung, Energierecht Transaktionen Dd; mit Intake, Prüfroutine, Normen-/Q... |
| `kompendium-07-energierecht-vertrie-bis-er-bess-abfall-recyc` | energierecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Energierecht Vertrieb Marktrollen, Energierecht Waerme Quartier, Energierecht Wettbewerb, Er Bess Abfall Recycling Rueckbau; mit Intake, Prüfroutine, Normen-/Quell... |
| `kompendium-08-er-bess-abstandsflae-bis-er-bess-bimschg-und` | energierecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Er Bess Abstandsflaechen Und Layout, Er Bess Baurecht Brandenburg, Er Bess Behoerdenstrategie, Er Bess Bimschg Und 4 Bimschv; mit Intake, Prüfroutine, Normen-/Quel... |
| `kompendium-09-er-bess-brandschutz-bis-er-bess-dieselgenera` | energierecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Er Bess Brandschutz Lithium Ionen, Er Bess Co Location Pv Wind, Er Bess Datenschutz Video Leitwarte, Er Bess Dieselgenerator Notstrom; mit Intake, Prüfroutine, Nor... |
| `kompendium-10-er-bess-epc-o-and-m-bis-er-bess-kapazitaetsm` | energierecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Er Bess Epc O And M Vertraege, Er Bess Fca Agnes Bnetza, Er Bess Finanzierung Bankability, Er Bess Kapazitaetsmarkt Grundlast; mit Intake, Prüfroutine, Normen-/Que... |
| `kompendium-11-er-bess-kritis-nis2-bis-er-bess-netzanschlus` | energierecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Er Bess Kritis Nis2 Cyber, Er Bess Marktrollen Bilanzkreis, Er Bess Naturschutz Artenschutz, Er Bess Netzanschluss Hoehe Spannung; mit Intake, Prüfroutine, Normen-... |
| `kompendium-12-er-bess-netzentgelte-bis-er-bess-power-qualit` | energierecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Er Bess Netzentgelte Und Abgaben, Er Bess Output Board Paper, Er Bess Physische Sicherheit Terror, Er Bess Power Quality Emv; mit Intake, Prüfroutine, Normen-/Quel... |
| `kompendium-13-er-bess-ppa-und-merc-bis-er-bess-regelenergie` | energierecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Er Bess Ppa Und Merchant Risk, Er Bess Projektakte Qualitygate, Er Bess Rechtsmittel Und Nachbarabwehr, Er Bess Regelenergie Systemdienstleistung; mit Intake, Prüf... |
| `kompendium-14-er-bess-vergabe-komm-bis-er-fusion-bauleitpla` | energierecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Er Bess Vergabe Kommunale Stadtwerke, Er Bess Wasser Awsv Und Boden, Er Einfuehrung System, Er Fusion Bauleitplanung Starnberger See; mit Intake, Prüfroutine, Norm... |
| `kompendium-15-er-fusion-buergerbet-bis-er-fusion-sicherheit` | energierecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Er Fusion Buergerbeteiligung Und Politik, Er Fusion Foerderung Beihilfe, Er Fusion Netzanschluss Und Systemnutzen, Er Fusion Sicherheitsnachweis; mit Intake, Prüfr... |
| `kompendium-16-er-fusion-strahlensc-bis-er-netzanschluss-pra` | energierecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Er Fusion Strahlenschutz Neutronen, Er Fusion Transrapid Anbindung, Er H2 Electrolyseur Foerderung, Er Netzanschluss Praesumtion Spezial; mit Intake, Prüfroutine,... |
| `kompendium-17-er-netzentgelte-rech-bis-spezial-anfrage-mehr` | energierecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Er Netzentgelte Rechtsfragen, Er Redispatch 3 0 Spezial, Er Typ Anfrage Mandanten Routing, Anfrage Mehrparteien Konflikt Und Interessen; mit Intake, Prüfroutine, N... |
| `kompendium-18-spezial-einfuehrung-bis-spezial-industrie-sc` | energierecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Einfuehrung Mandantenkommunikation Entscheidungsvorlage, Energieprojekt Intake Und Regulierungsweiche, Energierecht Erstpruefung Und Mandatsziel, Industrie Schrift... |
| `kompendium-19-spezial-kwkg-verhand-bis-spezial-praesumtion` | energierecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Kwkg Verhandlung Vergleich Und Eskalation, Netzanschluss Formular Portal Und Einreichung, Netze Risikoampel Und Gegenargumente, Praesumtion Red Team Und Qualitaets... |
| `kompendium-20-spezial-projektfinan-bis-spezial-system-bewei` | energierecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Projektfinanzierung Compliance Dokumentation Und Akte, Routing Internationaler Bezug Und Schnittstellen, Stadtwerke Tatbestand Beweis Und Belege, System Beweislast... |
| `kompendium-21-spezial-transaktione-bis-strompreisbremse-und` | energierecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Transaktionen Zahlen Schwellen Und Berechnung, Vertrieb Behoerden Gericht Und Registerweg, Waerme Dokumentenmatrix Und Lueckenliste, Strompreisbremse Und Extras; m... |
| `spezial-rechtsquellen-sonderfall-und-edge-case` | Rechtsquellen: Sonderfall und Edge-Case-Prüfung im Plugin energierecht; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Standardprüfung. |
| `spezial-verfahren-livequellen-und-rechtsprechungscheck` | Verfahren: Livequellen- und Rechtsprechungscheck im Plugin energierecht; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Standardprüfung. |
| `workflow-dokumentenintake` | Dokumentenintake im Plugin energierecht: liest Uploads, sortiert Dokumentarten, markiert Fristen und baut eine knappe Arbeitsakte. |
| `workflow-kaltstart-und-routing` | Kaltstart und Routing im Plugin energierecht: führt vom ersten Satz oder Dokument in den passenden Arbeitsweg, erkennt Rolle, Ziel, Risiko und Anschluss-Skills. |
| `workflow-rechtsquellen-livecheck` | Rechtsquellen-Livecheck im Plugin energierecht: zwingt vor tragenden Aussagen zum aktuellen Quellencheck bei Gesetzen, Behörden, Gerichten und Formularen. |
| `workflow-unterlagen-lueckenliste` | Unterlagen- und Lückenliste im Plugin energierecht: erstellt eine präzise Nachforderungsliste statt allgemeiner Fragebögen. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
