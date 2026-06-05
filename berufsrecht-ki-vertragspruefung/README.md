# berufsrecht-ki-vertragspruefung

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`berufsrecht-ki-vertragspruefung`) | [`berufsrecht-ki-vertragspruefung.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/berufsrecht-ki-vertragspruefung.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **Berufsrecht / KI-Vertragsprüfung — Rügeverfahren RAK Köln und Haftungsklage Habernau** (`berufsrecht-ki-rugekomitee-anwaltskammer-koeln-mandant-richtl-dr-rotbruch`) | [Gesamt-PDF lesen](../testakten/berufsrecht-ki-rugekomitee-anwaltskammer-koeln-mandant-richtl-dr-rotbruch/gesamt-pdf/berufsrecht-ki-rugekomitee-anwaltskammer-koeln-mandant-richtl-dr-rotbruch_gesamt.pdf) | [`testakte-berufsrecht-ki-rugekomitee-anwaltskammer-koeln-mandant-richtl-dr-rotbruch.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-berufsrecht-ki-rugekomitee-anwaltskammer-koeln-mandant-richtl-dr-rotbruch.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

> Hinweis: Inhaltlich verantwortlich ist Klotzkette. Die rechtlichen Bezugspunkte sind auf bestmöglichem Stand recherchiert; gleichwohl ersetzt keine Skill dieses Plugins die Prüfung durch einen spezialisierten Rechtsanwalt.

## Worum es geht

Kanzleien, Steuerberatungen, Wirtschaftsprüfungsgesellschaften, Patentanwaltskanzleien und Notariate setzen zunehmend Legal-KI-Tools privater Anbieter ein (Recherche mit Sprachmodellen, Dokumentenanalyse, Vertragsgeneratoren, Chatbots). Sobald solche Tools mit Mandats- oder Beteiligtendaten gefüttert werden, betreten wir berufsrechtliches und strafrechtliches Terrain. Datenschutzrecht läuft daneben, ersetzt aber die Prüfung des Berufsgeheimnisses nicht.

Dieses Plugin liefert eine **berufsrechtliche und strafrechtliche Vorprüfung** des Anbietervertrags. Es ist keine vollwertige juristische Begutachtung. Es ist ein strukturierter Argumentationsapparat, mit dem die Kanzlei dem Anbieter sagen kann: "So, wie macht ihr das eigentlich? Wie gewährleistet ihr die Anforderungen aus § 43e BRAO Absatz 3? Wo ist eure ISO-27001-Zertifizierung? Wo steht 'no training' im Vertrag?".

## Maßstab

Maßgeblich sind zuerst die geltenden Normen: § 43e BRAO, § 43a Abs. 2 BRAO, § 2 BORA, § 203 StGB, die Parallelnormen der anderen Berufsgeheimnisträger, DSGVO und KI-Verordnung. Die berufsrechtliche KI-Debatte wird als Auslegungshilfe verarbeitet, aber nicht als Ersatz für Gesetz, Rechtsprechung, Kammerpraxis oder eine konkrete Vertragsprüfung behandelt.

Arbeitslinie: KI-Outsourcing kann berufsrechtlich möglich sein, wenn der Dienstleister bewusst einbezogen, sorgfältig ausgewählt, in Textform verpflichtet, technisch-organisatorisch kontrolliert und in der Nutzung auf den erforderlichen Zugriff beschränkt wird. Public- oder Consumer-Tools ohne solche Bindung bleiben für Mandatsgeheimnisse tabu, solange nicht anonymisiert oder abstrahiert gearbeitet wird. Zur strafrechtlichen Absicherung dient § 203 StGB als verbindendes Element für alle fünf Berufsgruppen.

## Berufsgruppen

| Beruf | Verschwiegenheit | Dienstleisterregelung | § 203 StGB |
|---|---|---|---|
| Rechtsanwalt | § 43a Abs. 2 BRAO | § 43e BRAO | Abs. 1 Nr. 3 |
| Steuerberater | § 57 Abs. 1 StBerG | § 62a StBerG | Abs. 1 Nr. 3 |
| Wirtschaftsprüfer | § 43 WPO | § 50a WPO (§ 59c bei BG) | Abs. 1 Nr. 3 |
| Patentanwalt | § 39a Abs. 2 PAO | § 39c PAO | Abs. 1 Nr. 3 |
| Notar | § 18 BNotO | § 26a BNotO | Abs. 1 Nr. 1 |

Die Dienstleisterregelungen sind nahezu wortgleich aufgebaut. Das Plugin abstrahiert die gemeinsame Prüfung und stellt pro Beruf eine Norm-Adapter-Tabelle bereit.

## Skills

| Skill | Zweck |
|---|---|
| `berufsrecht-ki-vertragspruefung-kaltstart-interview` | Beruf, Anbieter, Datenarten, Vertragstyp erfassen |
| `consumer-ki-vs-43e-dienstleister` | Public Tool, Enterprise Tool, Kanzleisoftware, §-43e-Dienstleister und Einzelmandats-Tool trennen |
| `erforderlichkeit-dokumentieren` | Erforderlichkeit der Offenlegung (Abs. 1) — unternehmerischer Beurteilungsspielraum nach DAV |
| `ki-erforderlichkeit-ex-ante-vermerk` | Kanzlei-Vermerk zur Erforderlichkeit, Datenminimierung, Zweckbindung und Freigabeentscheidung |
| `verschwiegenheitsklausel-pruefen` | Textform, jedermann, zeitlich unbegrenzt, alle Berufsgeheimnisse |
| `strafrechtliche-belehrung-pruefen` | Belehrung über §§ 203, 204 StGB; Anlage Normtext |
| `subunternehmer-regelung-pruefen` | Zustimmungsvorbehalt, Weiterverpflichtung in Textform |
| `strafprozessuale-regelung-pruefen` | §§ 53a, 97 StPO — Widerspruchsrecht des Dienstleisters, Beschlagnahmefreiheit |
| `avv-grenzpruefung-datenschutz` | Schnittstelle zu Art. 28 DS-GVO — explizit andere Prüfung |
| `tom-und-zertifizierungen-pruefen` | TOM nach Art. 32 DS-GVO, ISO 27001, BSI C5, "no training", Zero-Retention |
| `ki-no-training-modellverbesserung-telemetrie` | Training, Produktverbesserung, Logs, Supportzugriffe, Telemetrie und Retention prüfen |
| `cloud-act-und-drittstaat-pruefen` | Auslandsregelung Abs. 4; CLOUD Act; Professional Secrecy Addendum |
| `schatten-ki-governance-und-sanktionslogik` | Private Tools, Schatten-KI, Freigabeliste, Incident Response und Team-Schulung organisieren |
| `ai-act-rollen-kanzlei-provider-deployer-api` | KI-VO-Rollen der Kanzlei als Betreiberin, Anbieterin oder API-Orchestratorin prüfen |
| `art-50-ki-vo-schriftsatz-marketing-chatbot` | Transparenzpflichten bei Mandantenchatbot, Website, Marketing, Legal Update und Schriftsatz abgrenzen |
| `rechtspolitische-unsicherheit-43e-brao-dokumentieren` | offene Auslegungsfragen, Reformmonitor und vertretbare Safe-Harbor-Argumente dokumentieren |
| `parallelnormen-andere-berufe` | Norm-Adapter pro Beruf — Mapping-Referenz |
| `gutachten-erstellen` | Zusammenfassendes Vorprüfungs-Gutachten |
| `rueckfragebrief-an-anbieter` | Strukturierter Brief mit präzisen Anbieterfragen |
| `klauselvorschlaege` | Mustertexte für nachverhandelbare Klauseln |

## Outputs

- **Vorprüfungs-Gutachten** mit Ampelbewertung (grün/gelb/rot) je Prüfpunkt
- **Rückfragebrief an den Anbieter** zur Klärung offener Versprechen
- **Klauselvorschläge** als Verhandlungsmaterial (Verschwiegenheit, "no training", Subunternehmerliste, EU/EWR-Beschränkung, Professional Secrecy Addendum)
- **Zertifizierungs- und Sicherheits-Checkliste** (ISO 27001, BSI C5, TOM Art. 32)
- **KI-Governance-Vermerk** für Toolfreigabe, Schatten-KI, Art.-4-KI-Kompetenz, Art.-50-Transparenz und anwaltliche Endkontrolle

## Wichtiger Hinweis (mehrfach)

**Diese Vorprüfung ist ausdrücklich keine Rechtsberatung.** Sie ist eine strukturierte Argumentationshilfe für das Anbietergespräch. Die berufsrechtliche und strafrechtliche Beurteilung des konkreten Einzelfalls bleibt der nutzenden Kanzlei (interne Compliance) bzw. einer beauftragten Spezialkanzlei vorbehalten.

## Quellenpolitik

- Gesetze zuerst: § 43e BRAO, § 43a Abs. 2 BRAO, § 2 BORA, § 203 StGB, Parallelnormen der anderen Berufsgeheimnisträger, DSGVO, KI-Verordnung
- BT-Drs. 18/12940 für die Genese der Dienstleisterregelungen
- Berufsrechtliche KI-Stellungnahmen, Kammerhinweise und Fachdebatte nur als Auslegungshilfe, nicht als verbindlicher Ersatzmaßstab
- BGH-Pinpoint mit Aktenzeichen und Randnummer
- Quellenregel: Literatur nur mit Nutzerquelle oder lizenziertem Live-Zugriff; keine Kommentar-, Handbuch- oder Aufsatzfundstellen aus Modellwissen.


<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 26 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `allgemein-brki-rollout-workflow-chronologie` | Allgemein, Brki Rollout Trainings Workflow, Workflow Chronologie Und Belegmatrix: Allgemein; Brki Rollout Trainings Workflow; Workflow Chronologie Und Belegmatrix. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuste... |
| `anbietern-belehrung-sonderfall-edge` | Spezial Anbietern Schriftsatz Brief Und Memo Bausteine, Spezial Belehrung Abschlussprodukt Und Übergabe, Spezial Berufsrecht Sonderfall Und Edge Case: Spezial Anbietern Schriftsatz Brief Und Memo Bausteine; Spezial Belehrung Abschlusspro... |
| `avv-grenzpruefung-brki-anbieter-brki-eu` | Avv Grenzpruefung Datenschutz, Brki Anbieter Due Diligence, Brki Eu Us Dpf Transferpruefung: Avv Grenzpruefung Datenschutz; Brki Anbieter Due Diligence; Brki Eu Us Dpf Transferpruefung. Führt Intake, Prüfroutine, Normen-/Quellenradar, Be... |
| `berufsrecht-ki-vertragspruefung-kaltstart-interview` | Erfasse Beruf des Auftraggebers (Rechtsanwalt Steuerberater Wirtschaftsprüfer Patentanwalt Notar) Anbieter Produktname Vertragsdokument Datenarten Verarbeitungszweck Hostingland und Subunternehmerstruktur. Bilde daraus den Norm-Adapter (... |
| `berufsrechtliche-bnoto-interessen-brao` | Spezial Berufsrechtliche Erstpruefung Und Mandatsziel, Spezial Bnoto Mehrparteien Konflikt Und Interessen, Spezial Brao Zahlen Schwellen Und Berechnung: Spezial Berufsrechtliche Erstpruefung Und Mandatsziel; Spezial Bnoto Mehrparteien Ko... |
| `brki-rag-bro-grundlagen-cloud-act` | Brki Rag Vertraulichkeit Spezial, Bro Grundlagen Ki Einsatz, Cloud Act Und Drittstaat Prüfen: Brki Rag Vertraulichkeit Spezial; Bro Grundlagen Ki Einsatz; Cloud Act Und Drittstaat Prüfen. Führt Intake, Prüfroutine, Normen-/Quellenradar,... |
| `consumer-ki-datentransfer-eu-erforderlichkeit-dokumentieren` | Consumer Ki Vs 43E Dienstleister, Datentransfer Eu Drittstaat, Erforderlichkeit Dokumentieren: Consumer Ki Vs 43E Dienstleister; Datentransfer Eu Drittstaat; Erforderlichkeit Dokumentieren. Führt Intake, Prüfroutine, Normen-/Quellenradar... |
| `forensische-prompt-gutachten-erstellen-kanzleisoftware` | Forensische Prüfung Prompt Injection, Gutachten Erstellen, Kanzleisoftware Spezial Mandantendaten: Forensische Prüfung Prompt Injection; Gutachten Erstellen; Kanzleisoftware Spezial Mandantendaten. Führt Intake, Prüfroutine, Normen-/Quel... |
| `fristennotiz-naechster-vorpruefung-klauselvorschlaege` | Spezial Vertragspruefung Fristennotiz Und Naechster Schritt, Spezial Vorpruefung Fristen Form Und Zustaendigkeit, Klauselvorschlaege: Spezial Vertragspruefung Fristennotiz Und Naechster Schritt; Spezial Vorpruefung Fristen Form Und Zusta... |
| `gutachten-red-legal-patentanwaelte` | Spezial Gutachten Red Team Und Qualitaetskontrolle, Spezial Legal Behörden Gericht Und Registerweg, Spezial Patentanwaelte Verhandlung Vergleich Und Eskalation: Spezial Gutachten Red Team Und Qualitaetskontrolle; Spezial Legal Behörden G... |
| `ki-erforderlichkeit-no-training-mandanten-aufklaerungspflicht` | Ki Erforderlichkeit Ex Ante Vermerk, Ki No Training Modellverbesserung Telemetrie, Mandanten Aufklaerungspflicht Ki: Ki Erforderlichkeit Ex Ante Vermerk; Ki No Training Modellverbesserung Telemetrie; Mandanten Aufklaerungspflicht Ki. Füh... |
| `klauseln-beweislast-verschwiegenheitsklausel-schatten-ki` | Spezial Klauseln Beweislast Und Darlegungslast, Verschwiegenheitsklausel Prüfen, Schatten Ki Governance Und Sanktionslogik: Spezial Klauseln Beweislast Und Darlegungslast; Verschwiegenheitsklausel Prüfen; Schatten Ki Governance Und Sankt... |
| `parallelnormen-andere-ai-act-art-vo` | Parallelnormen Andere Berufe, Ai Act Rollen Kanzlei Provider Deployer Api, Art 50 Ki Vo Schriftsatz Marketing Chatbot: Parallelnormen Andere Berufe; Ai Act Rollen Kanzlei Provider Deployer Api; Art 50 Ki Vo Schriftsatz Marketing Chatbot.... |
| `privaten-rueckfragebrief-mandantenentscheidung-stberg` | Spezial Privaten Risikoampel Und Gegenargumente, Spezial Rueckfragebrief Mandantenentscheidung, Spezial Stberg Compliance Dokumentation Und Akte: Spezial Privaten Risikoampel Und Gegenargumente; Spezial Rueckfragebrief Mandantenentscheid... |
| `rechtspolitische-unsicherheit-rueckfragebrief-an-schwarmpruefung` | Rechtspolitische Unsicherheit 43E Brao Dokumentieren, Rueckfragebrief An Anbieter, Schwarmpruefung Mehrere Tools: Rechtspolitische Unsicherheit 43E Brao Dokumentieren; Rueckfragebrief An Anbieter; Schwarmpruefung Mehrere Tools. Führt Int... |
| `spezial-notare-livequellen-und-rechtsprechungscheck` | Notare: Livequellen- und Rechtsprechungscheck im Plugin berufsrecht ki vertragspruefung; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Standardprüfung. |
| `stellungnahme-stgb-strafrechtliche` | Spezial Stellungnahme Formular Portal Und Einreichung, Spezial Stgb Internationaler Bezug Und Schnittstellen, Spezial Strafrechtliche Tatbestand Beweis Und Belege: Spezial Stellungnahme Formular Portal Und Einreichung; Spezial Stgb Inter... |
| `subunternehmer-regelung-tom-zertifizierungen` | Subunternehmer Regelung Prüfen, Tom Und Zertifizierungen Prüfen: Subunternehmer Regelung Prüfen; Tom Und Zertifizierungen Prüfen. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zusammen. |
| `vertraegen-strafprozessuale-regelung-strafrechtliche-belehrung` | Spezial Vertraegen Dokumentenmatrix Und Lueckenliste, Strafprozessuale Regelung Prüfen, Strafrechtliche Belehrung Prüfen: Spezial Vertraegen Dokumentenmatrix Und Lueckenliste; Strafprozessuale Regelung Prüfen; Strafrechtliche Belehrung P... |
| `workflow-anschluss-skills-router` | Anschluss-Skills Router im Plugin berufsrecht-ki-vertragspruefung: schlägt nach der ersten Prüfung die passenden Spezialskills aus demselben Plugin vor. |
| `workflow-dokumentenintake` | Dokumentenintake im Plugin berufsrecht-ki-vertragspruefung: liest Uploads, sortiert Dokumentarten, markiert Fristen und baut eine knappe Arbeitsakte. |
| `workflow-fristen-risikoampel-mandantenkommunikation-redteam` | Workflow Fristen Und Risikoampel, Workflow Mandantenkommunikation, Workflow Redteam Qualitygate: Workflow Fristen Und Risikoampel; Workflow Mandantenkommunikation; Workflow Redteam Qualitygate. Führt Intake, Prüfroutine, Normen-/Quellenr... |
| `workflow-kaltstart-und-routing` | Kaltstart und Routing im Plugin berufsrecht-ki-vertragspruefung: führt vom ersten Satz oder Dokument in den passenden Arbeitsweg, erkennt Rolle, Ziel, Risiko und Anschluss-Skills. |
| `workflow-output-waehlen` | Output wählen im Plugin berufsrecht-ki-vertragspruefung: entscheidet zwischen Memo, Schriftsatz, Tabelle, Brief, Checkliste, Vermerk, Redline oder Mandantenübersetzung. |
| `workflow-rechtsquellen-livecheck` | Rechtsquellen-Livecheck im Plugin berufsrecht-ki-vertragspruefung: zwingt vor tragenden Aussagen zum aktuellen Quellencheck bei Gesetzen, Behörden, Gerichten und Formularen. |
| `workflow-unterlagen-lueckenliste` | Unterlagen- und Lückenliste im Plugin berufsrecht-ki-vertragspruefung: erstellt eine präzise Nachforderungsliste statt allgemeiner Fragebögen. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
