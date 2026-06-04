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
| `ips-kaltstart-interview` | Insolvenzplan- oder StaRUG-Mandat durch strukturiertes Erstgespraech aufgleisen wenn Unterlagen fehlen. §§ 13 15a InsO §§ 29 42 StaRUG Antragspflichten. Prüfraster: Basisdaten Krisenursachen Gläubigerlandschaft Liquiditaetslage Sanierung... |
| `kompendium-01-allgemein-bis-workflow-fristen-und` | insolvenzplan-starug-planwerkstatt: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Allgemein, Chronologie Und Belegmatrix, Fristen Und Risikoampel; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und... |
| `kompendium-02-ips-verfahrenswahl-bis-ips-darstellender-te` | insolvenzplan-starug-planwerkstatt: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Ips Verfahrenswahl, Restrukturierungsplan Fristen Form Und Zustaendigkeit, Ips Darstellender Teil; mit Intake, Prüfroutine, Normen-/Quellenra... |
| `kompendium-03-ips-gerichtliche-sch-bis-ips-steuern-bilanz-f` | insolvenzplan-starug-planwerkstatt: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Ips Gerichtliche Schritte, Ips Kommandocenter, Ips Steuern Bilanz Folgen; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputm... |
| `kompendium-04-ips-abstimmung-mehrh-bis-ips-asset-deals-im-p` | insolvenzplan-starug-planwerkstatt: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Ips Abstimmung Mehrheiten, Ips Anlagenpaket, Ips Asset Deals Im Plan Grundstuecke Marken Kundendaten; mit Intake, Prüfroutine, Normen-/Quelle... |
| `kompendium-05-ips-cramdown-obstruk-bis-ips-gestaltender-tei` | insolvenzplan-starug-planwerkstatt: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Ips Cramdown Obstruktion, Ips Datenraum Register, Ips Gestaltender Teil; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmu... |
| `kompendium-06-ips-gruppen-klassenb-bis-ips-integrierte-plan` | insolvenzplan-starug-planwerkstatt: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Ips Gruppen Klassenbildung, Ips Insolvenzplan Architektur, Ips Integrierte Planung; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogi... |
| `kompendium-07-ips-minderheitenschu-bis-ips-planvollzug-moni` | insolvenzplan-starug-planwerkstatt: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Ips Minderheitenschutz, Ips Planbetroffene Auswahl, Ips Planvollzug Monitoring; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, O... |
| `kompendium-08-ips-redteam-qualityg-bis-ips-sicherheiten-dri` | insolvenzplan-starug-planwerkstatt: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Ips Redteam Qualitygate, Ips Sanierungskonzept, Ips Sicherheiten Drittsicherheiten; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogi... |
| `kompendium-09-ips-stabilisierung-s-bis-ips-starug-plan-arch` | insolvenzplan-starug-planwerkstatt: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Ips Stabilisierung Starug, Ips Stakeholder Kommunikation, Ips Starug Plan Architektur; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweisl... |
| `kompendium-10-ips-vergleichsrechnu-bis-ipsplan-gruppenbildu` | insolvenzplan-starug-planwerkstatt: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Ips Vergleichsrechnung, Ipsplan Cram Down Spezial, Ipsplan Gruppenbildung Leitfaden; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislog... |
| `kompendium-11-ipsplan-planstruktur-bis-sanierungsmoderation` | insolvenzplan-starug-planwerkstatt: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Ipsplan Planstruktur Bauleiter, Ipsplan Prepack Plan Spezial, Sanierungsmoderation 94 Starug; mit Intake, Prüfroutine, Normen-/Quellenradar,... |
| `kompendium-12-spezial-abstimmung-i-bis-spezial-cram-formula` | insolvenzplan-starug-planwerkstatt: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Abstimmung Internationaler Bezug Und Schnittstellen, Anlagen Mehrparteien Konflikt Und Interessen, Cram Formular Portal Und Einreichung; mit... |
| `kompendium-13-spezial-down-red-tea-bis-spezial-gruppen-schr` | insolvenzplan-starug-planwerkstatt: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Down Red Team Und Qualitaetskontrolle, Gestaltender Zahlen Schwellen Und Berechnung, Gruppen Schriftsatz Brief Und Memo Bausteine; mit Intake... |
| `kompendium-14-spezial-insolvenzpla-bis-spezial-klassen-verh` | insolvenzplan-starug-planwerkstatt: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Insolvenzplan Erstpruefung Und Mandatsziel, Intake Dokumentenmatrix Und Lueckenliste, Klassen Verhandlung Vergleich Und Eskalation; mit Intak... |
| `kompendium-15-spezial-sanierungsko-bis-spezial-teil-complia` | insolvenzplan-starug-planwerkstatt: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Sanierungskonzept Risikoampel Und Gegenargumente, Starug Tatbestand Beweis Und Belege, Teil Compliance Dokumentation Und Akte; mit Intake, Pr... |
| `kompendium-16-spezial-vergleichsre-bis-spezial-vergleichsre` | insolvenzplan-starug-planwerkstatt: eigenständiger Arbeits-Skill zu Vergleichsrechnung Behoerden Gericht Und Registerweg; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck. |
| `spezial-darstellender-livequellen-und-rechtsprechungscheck` | Darstellender: Livequellen- und Rechtsprechungscheck im Insolvenzplan und StaRUG: fachlich vertiefter Spezialskill mit Normenradar (InsO/StaRUG/Planrecht), Tatbestands-/Beweislastmatrix, Fristen- und Formcheck, Gegenargumenten, Fehlerbre... |
| `workflow-anschluss-skills-router` | Anschluss-Skills Router im Plugin insolvenzplan-starug-planwerkstatt: schlägt nach der ersten Prüfung die passenden Spezialskills aus demselben Plugin vor. |
| `workflow-dokumentenintake` | Dokumentenintake im Plugin insolvenzplan-starug-planwerkstatt: liest Uploads, sortiert Dokumentarten, markiert Fristen und baut eine knappe Arbeitsakte. |
| `workflow-kaltstart-und-routing` | Kaltstart und Routing im Plugin insolvenzplan-starug-planwerkstatt: führt vom ersten Satz oder Dokument in den passenden Arbeitsweg, erkennt Rolle, Ziel, Risiko und Anschluss-Skills. |
| `workflow-output-waehlen` | Output wählen im Plugin insolvenzplan-starug-planwerkstatt: entscheidet zwischen Memo, Schriftsatz, Tabelle, Brief, Checkliste, Vermerk, Redline oder Mandantenübersetzung. |
| `workflow-rechtsquellen-livecheck` | Rechtsquellen-Livecheck im Plugin insolvenzplan-starug-planwerkstatt: zwingt vor tragenden Aussagen zum aktuellen Quellencheck bei Gesetzen, Behörden, Gerichten und Formularen. |
| `workflow-unterlagen-lueckenliste` | Unterlagen- und Lückenliste im Plugin insolvenzplan-starug-planwerkstatt: erstellt eine präzise Nachforderungsliste statt allgemeiner Fragebögen. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
