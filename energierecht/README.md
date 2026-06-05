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
| `einfuehrung-energieprojekt-intake-energierecht-industrie` | Spezial Einfuehrung Mandantenkommunikation Entscheidungsvorlage, Spezial Energieprojekt Intake Und Regulierungsweiche, Spezial Energierecht Erstpruefung Und Mandatsziel, Spezial Industrie Schriftsatz Brief Und Memo Bausteine: Spezial Ein... |
| `energierecht-emobility-wasserstoff-energievertraege` | Energierecht Emobility Wasserstoff, Energierecht Energievertraege, Energierecht Industriekunden, Energierecht Infrastrukturprojekte: Energierecht Emobility Wasserstoff; Energierecht Energievertraege; Energierecht Industriekunden; Energie... |
| `energierecht-netz-speicher-projektfinanzierung-transaktionen-dd` | Energierecht Kommandocenter, Energierecht Netz Speicher Zugang, Energierecht Projektfinanzierung, Energierecht Transaktionen Dd: Energierecht Kommandocenter; Energierecht Netz Speicher Zugang; Energierecht Projektfinanzierung; Energierec... |
| `energierecht-vertrieb-marktrollen-waerme-quartier-wettbewerb` | Energierecht Vertrieb Marktrollen, Energierecht Waerme Quartier, Energierecht Wettbewerb, Er Bess Abfall Recycling Rueckbau: Energierecht Vertrieb Marktrollen; Energierecht Waerme Quartier; Energierecht Wettbewerb; Er Bess Abfall Recycli... |
| `er-bess-abstandsflaechen-baurecht-brandenburg-behoerdenstrategie` | Er Bess Abstandsflaechen Und Layout, Er Bess Baurecht Brandenburg, Er Bess Behoerdenstrategie, Er Bess Bimschg Und 4 Bimschv: Er Bess Abstandsflaechen Und Layout; Er Bess Baurecht Brandenburg; Er Bess Behoerdenstrategie; Er Bess Bimschg... |
| `er-bess-brandschutz-co-location-datenschutz-video` | Er Bess Brandschutz Lithium Ionen, Er Bess Co Location Pv Wind, Er Bess Datenschutz Video Leitwarte, Er Bess Dieselgenerator Notstrom: Er Bess Brandschutz Lithium Ionen; Er Bess Co Location Pv Wind; Er Bess Datenschutz Video Leitwarte; E... |
| `er-bess-epc-fca-agnes-finanzierung-bankability-kapazitaetsmarkt` | Er Bess Epc O And M Vertraege, Er Bess Fca Agnes Bnetza, Er Bess Finanzierung Bankability, Er Bess Kapazitaetsmarkt Grundlast: Er Bess Epc O And M Vertraege; Er Bess Fca Agnes Bnetza; Er Bess Finanzierung Bankability; Er Bess Kapazitaets... |
| `er-bess-er-bess-er-einfuehrung-er-fusion` | Er Bess Vergabe Kommunale Stadtwerke, Er Bess Wasser Awsv Und Boden, Er Einfuehrung System, Er Fusion Bauleitplanung Starnberger See: Er Bess Vergabe Kommunale Stadtwerke; Er Bess Wasser Awsv Und Boden; Er Einfuehrung System; Er Fusion B... |
| `er-bess-er-bess-er-stakeholder-eeg-kwkg` | Er Bess Produktsicherheit Haftung, Er Bess Versicherung Und Schadenfall, Er Stakeholder Mapping Energie, Energierecht Eeg Kwkg Erzeugung: Er Bess Produktsicherheit Haftung; Er Bess Versicherung Und Schadenfall; Er Stakeholder Mapping Ene... |
| `er-bess-kaltstart-projektaufnahme` | Batteriespeicherprojekt aufnehmen: Projektgröße, Standort, Netzebene, Betreiberrolle, Fristen, Unterlagen und Zieloutput. |
| `er-bess-kritis-marktrollen-bilanzkreis-naturschutz-artenschutz` | Er Bess Kritis Nis2 Cyber, Er Bess Marktrollen Bilanzkreis, Er Bess Naturschutz Artenschutz, Er Bess Netzanschluss Hoehe Spannung: Er Bess Kritis Nis2 Cyber; Er Bess Marktrollen Bilanzkreis; Er Bess Naturschutz Artenschutz; Er Bess Netza... |
| `er-bess-netzentgelte-output-board-physische-sicherheit-power-emv` | Er Bess Netzentgelte Und Abgaben, Er Bess Output Board Paper, Er Bess Physische Sicherheit Terror, Er Bess Power Quality Emv: Er Bess Netzentgelte Und Abgaben; Er Bess Output Board Paper; Er Bess Physische Sicherheit Terror; Er Bess Powe... |
| `er-bess-ppa-projektakte-rechtsmittel-nachbarabwehr-regelenergie` | Er Bess Ppa Und Merchant Risk, Er Bess Projektakte Qualitygate, Er Bess Rechtsmittel Und Nachbarabwehr, Er Bess Regelenergie Systemdienstleistung: Er Bess Ppa Und Merchant Risk; Er Bess Projektakte Qualitygate; Er Bess Rechtsmittel Und N... |
| `er-fusion-buergerbeteiligung-foerderung-beihilfe-netzanschluss` | Er Fusion Buergerbeteiligung Und Politik, Er Fusion Foerderung Beihilfe, Er Fusion Netzanschluss Und Systemnutzen, Er Fusion Sicherheitsnachweis: Er Fusion Buergerbeteiligung Und Politik; Er Fusion Foerderung Beihilfe; Er Fusion Netzansc... |
| `er-fusion-er-fusion-er-h2-er-netzanschluss` | Er Fusion Strahlenschutz Neutronen, Er Fusion Transrapid Anbindung, Er H2 Electrolyseur Foerderung, Er Netzanschluss Praesumtion Spezial: Er Fusion Strahlenschutz Neutronen; Er Fusion Transrapid Anbindung; Er H2 Electrolyseur Foerderung;... |
| `er-fusion-kaltstart-regulierungsweg` | Ordnet Fusionsreaktor-Projekt zwischen Atomrecht, Strahlenschutz, Baurecht, Immissionsschutz und Forschungsförderung. |
| `er-netzentgelte-er-redispatch-er-typ-anfrage-interessen` | Er Netzentgelte Rechtsfragen, Er Redispatch 3 0 Spezial, Er Typ Anfrage Mandanten Routing, Spezial Anfrage Mehrparteien Konflikt Und Interessen: Er Netzentgelte Rechtsfragen; Er Redispatch 3 0 Spezial; Er Typ Anfrage Mandanten Routing; S... |
| `kwkg-netzanschluss-netze-praesumtion-red` | Spezial Kwkg Verhandlung Vergleich Und Eskalation, Spezial Netzanschluss Formular Portal Und Einreichung, Spezial Netze Risikoampel Und Gegenargumente, Spezial Praesumtion Red Team Und Qualitaetskontrolle: Spezial Kwkg Verhandlung Vergle... |
| `livecheck-fristennotiz-versorger-ladeinfrastruktur-vertragskette` | Spezial Livecheck Fristennotiz Und Naechster Schritt, Spezial Versorger Fristen Form Und Zustaendigkeit, Ladeinfrastruktur Spezial Vertragskette, Ppa Cppa Vertragsspezialitaeten: Spezial Livecheck Fristennotiz Und Naechster Schritt; Spez... |
| `projektfinanzierung-routing-stadtwerke-system-beweislast` | Spezial Projektfinanzierung Compliance Dokumentation Und Akte, Spezial Routing Internationaler Bezug Und Schnittstellen, Spezial Stadtwerke Tatbestand Beweis Und Belege, Spezial System Beweislast Und Darlegungslast: Spezial Projektfinanz... |
| `spezial-rechtsquellen-sonderfall-und-edge-case` | Rechtsquellen: Sonderfall und Edge-Case-Prüfung im Plugin energierecht; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Standardprüfung. |
| `spezial-verfahren-livequellen-und-rechtsprechungscheck` | Verfahren: Livequellen- und Rechtsprechungscheck im Plugin energierecht; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Standardprüfung. |
| `transaktionen-vertrieb-waerme-strompreisbremse-extras` | Spezial Transaktionen Zahlen Schwellen Und Berechnung, Spezial Vertrieb Behörden Gericht Und Registerweg, Spezial Waerme Dokumentenmatrix Und Lueckenliste, Strompreisbremse Und Extras: Spezial Transaktionen Zahlen Schwellen Und Berechnun... |
| `workflow-allgemein-anschluss-skills-chronologie-belegmatrix` | Allgemein, Workflow Anschluss Skills Router, Workflow Chronologie Und Belegmatrix, Workflow Fristen Und Risikoampel: Allgemein; Workflow Anschluss Skills Router; Workflow Chronologie Und Belegmatrix; Workflow Fristen Und Risikoampel. Füh... |
| `workflow-dokumentenintake` | Dokumentenintake im Plugin energierecht: liest Uploads, sortiert Dokumentarten, markiert Fristen und baut eine knappe Arbeitsakte. |
| `workflow-kaltstart-und-routing` | Kaltstart und Routing im Plugin energierecht: führt vom ersten Satz oder Dokument in den passenden Arbeitsweg, erkennt Rolle, Ziel, Risiko und Anschluss-Skills. |
| `workflow-mandantenkommunikation-output-waehlen-redteam` | Workflow Mandantenkommunikation, Workflow Output Waehlen, Workflow Redteam Qualitygate, Energierecht Verfahren: Workflow Mandantenkommunikation; Workflow Output Waehlen; Workflow Redteam Qualitygate; Energierecht Verfahren. Führt Intake,... |
| `workflow-rechtsquellen-livecheck` | Rechtsquellen-Livecheck im Plugin energierecht: zwingt vor tragenden Aussagen zum aktuellen Quellencheck bei Gesetzen, Behörden, Gerichten und Formularen. |
| `workflow-unterlagen-lueckenliste` | Unterlagen- und Lückenliste im Plugin energierecht: erstellt eine präzise Nachforderungsliste statt allgemeiner Fragebögen. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
