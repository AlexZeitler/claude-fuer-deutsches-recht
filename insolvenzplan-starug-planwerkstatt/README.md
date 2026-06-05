# Insolvenzplan- und StaRUG-Planwerkstatt

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`insolvenzplan-starug-planwerkstatt`) | [`insolvenzplan-starug-planwerkstatt.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/insolvenzplan-starug-planwerkstatt.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **Metallbau Hansa GmbH – Insolvenzplan und StaRUG-Restrukturierung** (`insolvenzplan-starug-planwerkstatt-metallbau-hansa`) | [Gesamt-PDF lesen](../testakten/insolvenzplan-starug-planwerkstatt-metallbau-hansa/gesamt-pdf/insolvenzplan-starug-planwerkstatt-metallbau-hansa_gesamt.pdf) | [`testakte-insolvenzplan-starug-planwerkstatt-metallbau-hansa.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-insolvenzplan-starug-planwerkstatt-metallbau-hansa.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

Freistehendes Cowork-Plugin für die Erstellung, Prüfung und Härtung von Insolvenzplänen und StaRUG-Restrukturierungsplänen. Es führt vom Kaltstart über Datenraum, Sanierungskonzept, integrierte Planung, Vergleichsrechnung, Gruppen- und Klassenbildung, darstellenden und gestaltenden Teil, Anlagen, Abstimmung, Cram-down, Minderheitenschutz, gerichtliche Schritte und Planvollzug bis zum Monitoring.

## Wofür das Plugin gedacht ist

- Insolvenzplan im Regelverfahren, in Eigenverwaltung und im Schutzschirm.
- StaRUG-Restrukturierungsplan mit Auswahl der Planbetroffenen, Gruppen, Abstimmung, gerichtlichen Instrumenten und Stabilisierung.
- Vergleichsrechnung als zentrales Entscheidungselement mit Planfall, Fortführung ohne Plan, Liquidation, Sicherheiten, Sonderaktiva und Planmehrwert.
- Sanierungskonzept, integrierte Ertrags-, Finanz- und Liquiditätsplanung sowie Maßnahmenprogramm.
- Gerichtsfeste Entwurfsarbeit mit Anlagen, Red-Team-Prüfung, Freigabeampel und Planvollzug.

## Leitprinzip

Das Plugin ist verzeihend im Intake und streng im Ergebnis. Es darf mit chaotischen Tabellen, unvollständigen OPOS-Listen, widersprüchlichen Sicherheitenangaben und unfertigen Managementannahmen starten. Es macht daraus aber keinen scheinbar fertigen Plan. Jede Annahme bleibt sichtbar, jede Zahl bekommt eine Quelle oder Warnung, jede Rechtswirkung wird auf Bestimmtheit, Vergleichsrechnung und Minderheitenschutz zurückgeführt.

## Typischer Ablauf

1. Kaltstart: Rolle, Route, Schuldnerdaten, Krise, Zielbild, Gericht, Fristen und verfügbare Unterlagen erfassen.
2. Datenraum: Jahresabschlüsse, BWA, SuSa, OPOS, Liquidität, Verträge, Sicherheiten, Personal, Steuern und Organunterlagen sortieren.
3. Sanierung: Krisenursachen, Maßnahmen, Fortführungsfähigkeit, Stakeholderbeiträge und integrierte Planung erarbeiten.
4. Vergleich: Planfall, Ohne-Plan-Szenario, Sicherheitenwerte, Sonderaktiva, Kosten, Quoten und Planmehrwert berechnen.
5. Plan bauen: Darstellender Teil, gestaltender Teil, Gruppen oder Klassen, Anlagen, Abstimmung und gerichtliche Route entwerfen.
6. Härtung: Cram-down, Minderheitenschutz, Bestätigungsrisiken, Einwände und Vollzug red-teamen.

## Enthaltene Skills

| Skill | Zweck |
| --- | --- |
| ips-kommandocenter | Route, Material, Risiken und nächste Ausgaben steuern. |
| ips-verfahrenswahl | Den passenden Sanierungsrahmen auswählen. |
| ips-kaltstart-interview | Aus wenigen Angaben eine belastbare Arbeitsakte machen. |
| ips-datenraum-register | Alle Planbausteine belegbar machen. |
| ips-sanierungskonzept | Das wirtschaftliche Fundament des Plans herstellen. |
| ips-integrierte-planung | Zahlen konsistent, nachvollziehbar und gerichtsfähig machen. |
| ips-vergleichsrechnung | Herzstück des Plans rechnen und erklären. |
| ips-insolvenzplan-architektur | Einen vollständigen InsO-Plan strukturieren. |
| ips-starug-plan-architektur | Einen vollständigen Restrukturierungsplan strukturieren. |
| ips-darstellender-teil | Die Entscheidungsgrundlage vollständig machen. |
| ips-gestaltender-teil | Rechtswirkungen bestimmt und vollziehbar formulieren. |
| ips-gruppen-klassenbildung | Abstimmungsarchitektur belastbar machen. |
| ips-sicherheiten-drittsicherheiten | Besicherte Positionen planfest und wertklar behandeln. |
| ips-planbetroffene-auswahl | StaRUG-Eingriffe fokussiert und begründet halten. |
| ips-abstimmung-mehrheiten | Mehrheiten vor dem Termin realistisch prüfen. |
| ips-cramdown-obstruktion | Ablehnende Gruppen gerichtsfest einordnen. |
| ips-minderheitenschutz | Opposition ernst nehmen und Planangriff vermeiden. |
| ips-anlagenpaket | Nichts einreichen, was Anlagenlücken hat. |
| ips-gerichtliche-schritte | Verfahren und Gerichtskommunikation steuern. |
| ips-stabilisierung-starug | Zeit kaufen, ohne die Planroute zu beschädigen. |
| ips-planvollzug-monitoring | Nach Bestätigung die Umsetzung führen. |
| ips-steuern-bilanz-folgen | Planwirkungen nicht an Nebenfolgen scheitern lassen. |
| ips-stakeholder-kommunikation | Akzeptanz für den Plan organisieren. |
| ips-redteam-qualitygate | Den Plan vor Gegnern und Gericht hart prüfen. |

## Grenzen

Das Plugin ersetzt keine anwaltliche, steuerliche oder betriebswirtschaftliche Endprüfung. Es ist ein Arbeits-, Strukturierungs- und Qualitätssicherungswerkzeug. Bei Planbestätigung, gerichtlicher Einreichung, steuerlichen Folgen, Organpflichten, Sicherheitenwerten, Drittsicherheiten und streitigen Gläubigerrechten verlangt es menschliche Freigabe.

<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 24 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `abstimmung-anlagen-interessen-cram` | Spezial Abstimmung Internationaler Bezug Und Schnittstellen, Spezial Anlagen Mehrparteien Konflikt Und Interessen, Spezial Cram Formular Portal Und Einreichung: Spezial Abstimmung Internationaler Bezug Und Schnittstellen; Spezial Anlagen... |
| `allgemein-workflow-chronologie-workflow-fristen` | Allgemein, Workflow Chronologie Und Belegmatrix, Workflow Fristen Und Risikoampel: Allgemein; Workflow Chronologie Und Belegmatrix; Workflow Fristen Und Risikoampel. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmus... |
| `down-red-gestaltender-gruppen` | Spezial Down Red Team Und Qualitaetskontrolle, Spezial Gestaltender Zahlen Schwellen Und Berechnung, Spezial Gruppen Schriftsatz Brief Und Memo Bausteine: Spezial Down Red Team Und Qualitaetskontrolle; Spezial Gestaltender Zahlen Schwell... |
| `insolvenzplan-intake-klassen` | Spezial Insolvenzplan Erstpruefung Und Mandatsziel, Spezial Intake Dokumentenmatrix Und Lueckenliste, Spezial Klassen Verhandlung Vergleich Und Eskalation: Spezial Insolvenzplan Erstpruefung Und Mandatsziel; Spezial Intake Dokumentenmatr... |
| `ips-abstimmung-ips-anlagenpaket-ips-asset` | Ips Abstimmung Mehrheiten, Ips Anlagenpaket, Ips Asset Deals Im Plan Grundstuecke Marken Kundendaten: Ips Abstimmung Mehrheiten; Ips Anlagenpaket; Ips Asset Deals Im Plan Grundstuecke Marken Kundendaten. Führt Intake, Prüfroutine, Normen... |
| `ips-cramdown-ips-datenraum-ips-gestaltender` | Ips Cramdown Obstruktion, Ips Datenraum Register, Ips Gestaltender Teil: Ips Cramdown Obstruktion; Ips Datenraum Register; Ips Gestaltender Teil. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätsche... |
| `ips-gerichtliche-ips-ips-steuern` | Ips Gerichtliche Schritte, Ips Kommandocenter, Ips Steuern Bilanz Folgen: Ips Gerichtliche Schritte; Ips Kommandocenter; Ips Steuern Bilanz Folgen. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätsc... |
| `ips-gruppen-ips-architektur-ips-integrierte` | Ips Gruppen Klassenbildung, Ips Insolvenzplan Architektur, Ips Integrierte Planung: Ips Gruppen Klassenbildung; Ips Insolvenzplan Architektur; Ips Integrierte Planung. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputm... |
| `ips-ips-sanierungskonzept-ips-sicherheiten` | Ips Redteam Qualitygate, Ips Sanierungskonzept, Ips Sicherheiten Drittsicherheiten: Ips Redteam Qualitygate; Ips Sanierungskonzept; Ips Sicherheiten Drittsicherheiten. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputm... |
| `ips-kaltstart-interview` | Insolvenzplan- oder StaRUG-Mandat durch strukturiertes Erstgespraech aufgleisen wenn Unterlagen fehlen. §§ 13 15a InsO §§ 29 42 StaRUG Antragspflichten. Prüfraster: Basisdaten Krisenursachen Gläubigerlandschaft Liquiditaetslage Sanierung... |
| `ips-minderheitenschutz-ips-planbetroffene-ips-planvollzug` | Ips Minderheitenschutz, Ips Planbetroffene Auswahl, Ips Planvollzug Monitoring: Ips Minderheitenschutz; Ips Planbetroffene Auswahl; Ips Planvollzug Monitoring. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster un... |
| `ips-stabilisierung-ips-stakeholder-ips-plan` | Ips Stabilisierung Starug, Ips Stakeholder Kommunikation, Ips Starug Plan Architektur: Ips Stabilisierung Starug; Ips Stakeholder Kommunikation; Ips Starug Plan Architektur. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, O... |
| `ips-verfahrenswahl-restrukturierungsplan-ips-darstellender` | Ips Verfahrenswahl, Spezial Restrukturierungsplan Fristen Form Und Zustaendigkeit, Ips Darstellender Teil: Ips Verfahrenswahl; Spezial Restrukturierungsplan Fristen Form Und Zustaendigkeit; Ips Darstellender Teil. Führt Intake, Prüfrouti... |
| `ips-vergleichsrechnung-ipsplan-cram-ipsplan-gruppenbildung` | Ips Vergleichsrechnung, Ipsplan Cram Down Spezial, Ipsplan Gruppenbildung Leitfaden: Ips Vergleichsrechnung; Ipsplan Cram Down Spezial; Ipsplan Gruppenbildung Leitfaden. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outpu... |
| `ipsplan-planstruktur-prepack-plan-sanierungsmoderation-starug` | Ipsplan Planstruktur Bauleiter, Ipsplan Prepack Plan Spezial, Sanierungsmoderation 94 Starug: Ipsplan Planstruktur Bauleiter; Ipsplan Prepack Plan Spezial; Sanierungsmoderation 94 Starug. Führt Intake, Prüfroutine, Normen-/Quellenradar,... |
| `sanierungskonzept-starug-spezial-teil` | Spezial Sanierungskonzept Risikoampel Und Gegenargumente, Spezial Starug Tatbestand Beweis Und Belege, Spezial Teil Compliance Dokumentation Und Akte: Spezial Sanierungskonzept Risikoampel Und Gegenargumente; Spezial Starug Tatbestand Be... |
| `spezial-darstellender-livequellen-und-rechtsprechungscheck` | Darstellender: Livequellen- und Rechtsprechungscheck im Insolvenzplan und StaRUG: fachlich vertiefter Spezialskill mit Normenradar (InsO/StaRUG/Planrecht), Tatbestands-/Beweislastmatrix, Fristen- und Formcheck, Gegenargumenten, Fehlerbre... |
| `vergleichsrechnung` | Spezial Vergleichsrechnung Behörden Gericht Und Registerweg: Spezial Vergleichsrechnung Behörden Gericht Und Registerweg. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zusammen. |
| `workflow-anschluss-skills-router` | Anschluss-Skills Router im Plugin insolvenzplan-starug-planwerkstatt: schlägt nach der ersten Prüfung die passenden Spezialskills aus demselben Plugin vor. |
| `workflow-dokumentenintake` | Dokumentenintake im Plugin insolvenzplan-starug-planwerkstatt: liest Uploads, sortiert Dokumentarten, markiert Fristen und baut eine knappe Arbeitsakte. |
| `workflow-kaltstart-und-routing` | Kaltstart und Routing im Plugin insolvenzplan-starug-planwerkstatt: führt vom ersten Satz oder Dokument in den passenden Arbeitsweg, erkennt Rolle, Ziel, Risiko und Anschluss-Skills. |
| `workflow-output-waehlen` | Output wählen im Plugin insolvenzplan-starug-planwerkstatt: entscheidet zwischen Memo, Schriftsatz, Tabelle, Brief, Checkliste, Vermerk, Redline oder Mandantenübersetzung. |
| `workflow-rechtsquellen-livecheck` | Rechtsquellen-Livecheck im Plugin insolvenzplan-starug-planwerkstatt: zwingt vor tragenden Aussagen zum aktuellen Quellencheck bei Gesetzen, Behörden, Gerichten und Formularen. |
| `workflow-unterlagen-lueckenliste` | Unterlagen- und Lückenliste im Plugin insolvenzplan-starug-planwerkstatt: erstellt eine präzise Nachforderungsliste statt allgemeiner Fragebögen. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
