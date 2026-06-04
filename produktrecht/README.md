# Produkthaftung und Produktrecht (Plugin `produktrecht`)

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`produktrecht`) | [`produktrecht.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/produktrecht.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **BGB BT — Smart-Kühlschrank, digitale Elemente und Reparaturblockade** (`bgb-bt-smart-kuehlschrank-digital-repair-koeln`) | [Gesamt-PDF lesen](../testakten/bgb-bt-smart-kuehlschrank-digital-repair-koeln/gesamt-pdf/bgb-bt-smart-kuehlschrank-digital-repair-koeln_gesamt.pdf) | [`testakte-bgb-bt-smart-kuehlschrank-digital-repair-koeln.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-bgb-bt-smart-kuehlschrank-digital-repair-koeln.zip) |
| **Projekt Isarlicht — Kernfusion und Transrapid am Starnberger See** (`kernfusion-transrapid-starnberger-see`) | [Gesamt-PDF lesen](../testakten/kernfusion-transrapid-starnberger-see/gesamt-pdf/kernfusion-transrapid-starnberger-see_gesamt.pdf) | [`testakte-kernfusion-transrapid-starnberger-see.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-kernfusion-transrapid-starnberger-see.zip) |
| **Produkthaftung Frischwind Mobility GmbH — Akku-Brände E-Bike Wind-X7, Produktrückruf, Strafverfahren** (`produkthaftung-akku-brand-e-bike-frischwind-mobility-erfurt`) | [Gesamt-PDF lesen](../testakten/produkthaftung-akku-brand-e-bike-frischwind-mobility-erfurt/gesamt-pdf/produkthaftung-akku-brand-e-bike-frischwind-mobility-erfurt_gesamt.pdf) | [`testakte-produkthaftung-akku-brand-e-bike-frischwind-mobility-erfurt.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-produkthaftung-akku-brand-e-bike-frischwind-mobility-erfurt.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

Rechtliche Abläufe für Produktteams, Hersteller, Händler und Kanzleien: Produktsicherheit, Produkthaftung, Produktbeobachtung, Rückruf, Marktüberwachung, Software-/OTA-Updates, Right to Repair und Launch-Review. Der Ordner heißt weiter `produktrecht`, damit bestehende Links stabil bleiben; inhaltlich ist das Plugin jetzt ausdrücklich auch ein Produkthaftungs- und Produktlebenszyklus-Plugin.

Es trennt sauber zwischen Produktsicherheit/Behördenpflichten, verschuldensunabhängiger Produkthaftung, deliktischer Produzentenhaftung, vertraglicher Gewährleistung, digitalem Kaufrecht und künftigen Reparaturpflichten. Gerade bei vernetzten Waren wird nicht mehr gefragt “Hardware oder App?”, sondern: Welche Funktion hängt an Firmware, Cloud, Konto, Sensorik, Update oder Reparaturzugang?

**Alle Ausgaben sind Entwürfe zur anwaltlichen Prüfung – zitiert, markiert und abgesichert – keine rechtlichen Schlussfolgerungen.** Das Plugin erledigt die Arbeit: liest Dokumente, wendet Ihr Playbook an, findet Probleme, erstellt das Memo. Ein Anwalt prüft, verifiziert und entscheidet. Zitate sind nach Quelle gekennzeichnet. Berufsrechtliche Verschwiegenheitspflichten (§ 43a Abs. 2 BRAO, § 203 StGB) werden konservativ angewendet. Folgenreiche Maßnahmen – Abmahnungen, Einreichungen, Vertragsunterzeichnungen – sind durch explizite Bestätigung gesichert.

## Für wen ist dieses Plugin?

| Rolle | Hauptworkflows |
|---|---|
| **Produktjurist / Syndikusanwalt** | Launch-Review, Produktsicherheit, GPSR, Rückruf, Repair-/Update-Policy |
| **Produkthaftungsanwalt** | ProdHaftG, § 823 BGB, Produzentenhaftung, Beweisakte, Serienfehler, Regress |
| **Produktmanager / Engineering** | "Ist-das-ein-Problem?"-Triage, Software-/OTA-Änderungen, Repair-by-design |
| **Marketing / Brand** | Werbeaussagen-Prüfung vor Veröffentlichung |
| **GC / Leiter Rechtsabteilung** | Eskalierte Produktfälle, Marktüberwachung, Behördenkommunikation, Krisenstab |

## Erster Start: das Kaltstart-Interview

Verbindet sich mit Ihrem Launch-Tracker (Jira/Linear), liest zehn vergangene Launch-Reviews, lernt was Sie tatsächlich blockieren vs. durchwinken. Erstellt eine Risikokalibrierungstabelle, auf die jeder andere Skill zurückgreift.

Ihre Konfiguration wird unter `~/.claude/plugins/config/claude-fuer-deutsches-recht/produktrecht/CLAUDE.md` gespeichert und überlebt Plugin-Updates.

```
/produktrecht:produktrecht-kaltstart-interview
```

## Befehle

| Befehl | Funktion |
|---|---|
| `/produktrecht:produktrecht-kaltstart-interview` | Kaltstart-Interview |
| `/produktrecht:launch-pruefung [PRD oder Ticket]` | Vollständiger Launch-Review gegen Ihr Framework |
| `/produktrecht:werbeaussagen-pruefung [Text]` | Werbeaussagen-Prüfung |
| `/produktrecht:ist-das-ein-problem [Frage]` | Schnelle "Ist-das-ein-Problem?"-Antwort |
| `/produktrecht:feature-risikobewertung [Feature]` | Tiefgehende Feature-Risikobewertung |
| `/produktrecht:impressum-pflicht` | Impressumspflichten prüfen (DDG, MStV) |
| `/produktrecht:preisangaben` | Preisangabenpflichten prüfen (PAngV) |
| `/produktrecht:produktrecht-mandat-arbeitsbereich` | Mandate verwalten (nur Multi-Mandanten-Praxis) |

## Skills

| Skill | Zweck |
|---|---|
| **kaltstart-interview** | Erstellt `~/.claude/plugins/config/claude-fuer-deutsches-recht/produktrecht/CLAUDE.md` aus Interview + vergangenen Launch-Reviews |
| **launch-pruefung** | Kategorie-für-Kategorie-Review, kalibriert auf Ihr Unternehmen (Sieben-Kategorien-Framework: Werberecht, Datenschutz, Produktsicherheit, AGB, Verbraucherrechte, Geistiges Eigentum, Aufsichtsrecht) |
| **werbeaussagen-pruefung** | Werbeaussagen-Taxonomie: Marktschreierische Anpreisung / Tatsachenbehauptung / Vergleich / implizierte Aussage / absolute Aussage; Prüfung nach §§ 5, 5a, 5b UWG und PAngV |
| **feature-risikobewertung** | Tiefgehende Analyse eines einzelnen Features (UWG, DSGVO, DSA, KI-VO, Verbraucherschutz BGB) |
| **ist-das-ein-problem** | Gleich-Minuten-Triage für die schnelle Slack-Frage |
| **impressum-pflicht** | Anbieterkennzeichnung §§ 5, 6 DDG (vormals TMG), § 18 MStV |
| **preisangaben** | PAngV-Prüfung: Gesamtpreis, Grundpreis, Streichpreise, Versandkosten |
| **mandat-arbeitsbereich** | Mandate anlegen, auflisten, wechseln und schließen für Multi-Mandanten-Praxis; isoliert Mandanten/Mandate so dass kein Kontext leckt |

## Interaktive Befehle vs. geplante Agenten

Die obigen Befehle laufen bei Aufruf – für laufende Arbeit an einem Mandat. Die Agenten unten laufen auf einem Zeitplan – für das, was sich bewegt während Sie nicht hinschauen:

| Agent | Was wird überwacht | Standard-Takt |
|---|---|---|
| **markteinführungs-monitor** | Launch-Tracker (Jira/Linear) auf bevorstehende Launches die wahrscheinlich rechtliche Prüfung benötigen; filtert Tickets mit Launch-Terminen in den nächsten 30 Tagen per Kalibrierungstabelle | Täglich |

## Integrationen

**Verbinden Sie zuerst ein Recherche-Tool – die Zitatschranken hängen davon ab.** Ohne eines wird jede Quellenangabe als `[prüfen]` markiert und der Prüfvermerk über jeder Ausgabe hält fest, dass Quellen nicht verifiziert wurden. Skills arbeiten beides; ein Recherche-Tool verschiebt Verifikationsarbeit von Ihrer Schulter.

Ausgeliefert mit in `.mcp.json` konfigurierten Konnektoren:

- **Slack** – Nachrichten suchen, Kanäle lesen, Diskussionen finden
- **Google Drive** – Dokumente suchen, lesen und abrufen
- **Linear** – Issue-Tracking und Projektmanagement
- **Atlassian** – Jira-Issues und Confluence-Seiten
- **Asana** – Aufgaben und Projekt-Tracking

Mit verbundenem Tracker: Kaltstart liest Launch-Historie, launch-pruefung liest Ticket-Kontext, markteinführungs-monitor-Agent überwacht den Kalender.

## Schnellstart

```
/produktrecht:produktrecht-kaltstart-interview
```

Dann:

```
/produktrecht:ist-das-ein-problem "Können wir den Preis auf der Preisseite A/B-testen?"
```

→ Antwort in einer Minute, kalibriert auf Ihre Risikotabelle.

```
/produktrecht:launch-pruefung PROJ-1234
```

→ Vollständiger Review, Kategorie für Kategorie, mit Aufgabenliste.

## Wie das Plugin lernt

Ihr Praxisprofil unter `~/.claude/plugins/config/claude-fuer-deutsches-recht/produktrecht/CLAUDE.md` ist nicht statisch – es verbessert sich durch Nutzung. Skills zeigen an, wenn eine Ausgabe eine Standard-Einstellung verwendet hat, die Sie anpassen sollten. Sie können das Setup erneut ausführen, die Datei direkt bearbeiten oder einem Skill mitteilen, eine neue Position zu erfassen.

## Wichtige Normen dieses Plugins

- **UWG** (§§ 3, 5, 5a, 5b, 7 – unlautere Werbung, Irreführung, Belästigung)
- **PAngV 2022** (Preisangabenpflichten, Grundpreis § 4, Streichpreise § 11)
- **BGB §§ 305 ff.** (AGB-Kontrolle, Einbeziehung, Inhaltskontrolle)
- **DDG** (vormals TMG – Impressumspflicht §§ 5, 6, Haftung §§ 7 ff.)
- **TDDDG** (Cookie-Einwilligung, § 25 TDDDG)
- **ProdHaftG / § 823 BGB** (verschuldensunabhängige Produkthaftung und deliktische Produzentenhaftung)
- **ProdSG / GPSR VO (EU) 2023/988** (Produktsicherheit, Marktüberwachung, Rückverfolgbarkeit, Safety Business Gateway)
- **BGB §§ 327 ff., 434, 475b, 475c, 475e, 476, 477** (digitale Produkte, Waren mit digitalen Elementen, Updatepflichten, Beweislast, Verjährung)
- **Richtlinie (EU) 2024/1799** (Recht auf Reparatur; Umsetzungsstand jeweils live prüfen)
- **Richtlinie (EU) 2024/2853** (neue Produkthaftungsrichtlinie; Umsetzung und zeitliche Anwendbarkeit live prüfen)
- **MarkenG** (Markenverletzung, Benutzungsmarken, Verwechslungsgefahr)
- **AGG** (Diskriminierungsverbot, Benachteiligung)
- **EU-Verordnungen:** DSA, DMA, KI-VO (AI Act, EU 2024/1689)

## Hinweise

- Die Kalibrierungstabelle ist das Herzstück. Wenn sie falsch ist, ist jeder Review falsch. Neu ausführen wenn sich Ihre Risikoposition ändert (neues Regulierungsumfeld, neuer GC, neue Bußgeld-Entscheidung).
- `ist-das-ein-problem` ist so konzipiert, dass PMs es eigenständig nutzen können. Es antwortet schnell und leitet zu einer echten Prüfung weiter, wenn nötig.
- Feature-Risikobewertung ist für die 10% der Launches, die Tiefe benötigen. Die meisten tun es nicht – keine unnötige Dokumentenpflege.
- GPSR ist VO (EU) 2023/988. Die BatterieVO ist VO (EU) 2023/1542 und nur bei Batterie-/Akkubezug einschlägig.
- Right to Repair und neue Produkthaftungsrichtlinie sind in Übergang und Umsetzung zu behandeln. Tragende Aussagen zum deutschen Umsetzungsstand immer live verifizieren.

## Voraussetzungen

Einige Features referenzieren externe Integrationen (Dokumentenmanagementsystem, Launch-Tracker, Fallmanagementsystem, Regulierungs-Feeds). Diese sind nicht mitgeliefert – wenn Sie einen MCP-Server dafür in Ihrer Umgebung haben, verwenden ihn die relevanten Features. Ohne einen fällt das Plugin auf Datei-Upload und manuelle Abläufe zurück. Führen Sie `/produktrecht:produktrecht-kaltstart-interview --check-integrations` aus um zu sehen, was in Ihrer Umgebung verfügbar ist.

## Konfiguration

Ihre Konfiguration wird unter `~/.claude/plugins/config/claude-fuer-deutsches-recht/produktrecht/CLAUDE.md` gespeichert und überlebt Plugin-Updates – Sie führen das Setup nur einmal aus.


<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 28 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `kompendium-01-allgemein-bis-workflow-chronologie` | produktrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Allgemein, Anschluss Skills Router, Chronologie Und Belegmatrix; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck. |
| `kompendium-02-workflow-fristen-und-bis-workflow-redteam-qua` | produktrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Fristen Und Risikoampel, Mandantenkommunikation, Redteam Qualitygate; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck. |
| `kompendium-03-spezial-review-frist-bis-produkthaftung-digit` | produktrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Review Fristen Form Und Zustaendigkeit, Prodr Produkthaftung Bauleiter, Produkthaftung Digital Software Pld 2024 2853; mit Intake, Prüfroutine, Normen-/Quellenrada... |
| `kompendium-04-produkthaftung-grund-bis-produkthaftung-repar` | produktrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Produkthaftung Grundlagen, Produkthaftung Produktsicherheit Gpsr Korrektur, Produkthaftung Reparatur Update Und Lifecycle; mit Intake, Prüfroutine, Normen-/Quellen... |
| `kompendium-05-rechtsabteilung-neue-bis-dual-use-produktrech` | produktrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Neue Produkthaftungsrichtlinie Und Softwareprodu, Ce Kennzeichnung Routenplan, Dual Use Produktrecht; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, O... |
| `kompendium-06-eu-produktsicherheit-bis-impressum-pflicht` | produktrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Eu Produktsicherheitsverordnung Gpsr, Feature Risikobewertung, Impressum Pflicht; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qual... |
| `kompendium-07-ist-das-ein-problem-bis-marktueberwachung-ko` | produktrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Ist Das Ein Problem, Ki Act Produktintegration, Marktueberwachung Kommunikation; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Quali... |
| `kompendium-08-nachhaltigkeitsklage-bis-prodr-gpsr-cra-fitne` | produktrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Nachhaltigkeitsklage Werbeaussagen, Preisangaben, Prodr Gpsr Cra Fitness Spezial; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qual... |
| `kompendium-09-prodr-machinery-regu-bis-produktbeobachtung-f` | produktrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Prodr Machinery Regulation Spezial, Prodr Produktrueckruf Leitfaden, Produktbeobachtung Feldueberwachung; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogi... |
| `kompendium-10-produktbeobachtung-s-bis-produktrecht-mandat` | produktrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Produktbeobachtung Software Ota, Produktrecht Anpassen, Produktrecht Mandat Arbeitsbereich; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuste... |
| `kompendium-11-rechtsabteilung-cybe-bis-rechtsabteilung-righ` | produktrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Cybersecurity Als Produktsicherheitsmerkmal, Digitale Elemente Im Kaufrecht, Right To Repair Im Geraetevertrieb; mit Intake, Prüfroutine, Normen-/Quellenradar, Bew... |
| `kompendium-12-rechtsabteilung-ruec-bis-reparaturpflicht-her` | produktrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Rueckrufmanagement Mit Rapex Safety Gate, Repair By Design Software Locks Ersatzteile, Reparaturpflicht Hersteller Nach Gewaehrleistung; mit Intake, Prüfroutine, N... |
| `kompendium-13-right-to-repair-prod-bis-spezial-belegmatrix` | produktrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Right To Repair Produktrecht 2024 1799, Rueckruf Strategie Konzern, Belegmatrix Mandantenkommunikation Entscheidungsvorlage; mit Intake, Prüfroutine, Normen-/Quell... |
| `kompendium-14-spezial-bewertungen-bis-spezial-impressumspf` | produktrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Bewertungen Behoerden Gericht Und Registerweg, Chronologie Red Team Und Qualitaetskontrolle, Impressumspflicht Dokumentenmatrix Und Lueckenliste; mit Intake, Prüfr... |
| `kompendium-15-spezial-launch-tatbe-bis-spezial-machinery-co` | produktrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Launch Tatbestand Beweis Und Belege, Livecheck Formular Portal Und Einreichung, Machinery Compliance Dokumentation Und Akte; mit Intake, Prüfroutine, Normen-/Quell... |
| `kompendium-16-spezial-pangv-risiko-bis-spezial-produktbeoba` | produktrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Pangv Risikoampel Und Gegenargumente, Prodr Zahlen Schwellen Und Berechnung, Produktbeobachtung Verhandlung Vergleich Und Eskalation; mit Intake, Prüfroutine, Norm... |
| `kompendium-17-spezial-produktlaunc-bis-spezial-produktnutzu` | produktrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Produktlaunch Beweislast Und Darlegungslast, Produktlaunch Rechtscheck, Produktnutzung Und Claimcheck; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik,... |
| `kompendium-18-spezial-produktrecht-bis-spezial-rechtscheck` | produktrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Produktrecht Schriftsatz Brief Und Memo Bausteine, Produktrechtliche Erstpruefung Und Mandatsziel, Rechtscheck Sonderfall Und Edge Case; mit Intake, Prüfroutine, N... |
| `kompendium-19-spezial-regulation-m-bis-werbeaussagen-pruefu` | produktrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Regulation Mehrparteien Konflikt Und Interessen, Werbeaussagen Pruefung; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck. |
| `launch-pruefung` | Produktmanager oder Rechtsabteilung will vor dem Launch prüfen, ob das Produkt oder Feature produktrechtlich freigegeben werden kann. Vollständige rechtliche Freigabeprüfung gegen konfiguriertes Prüfrahmenwerk und Risikokalibrierung. Nor... |
| `produktrecht-kaltstart-interview` | Produktrecht-Plugin erstmalig einrichten und Launch-Tracker verbinden sowie Risikokalibrierung der Rechtsabteilung erfassen. Verbindet Launch-Tracker liest vergangene Reviews lernt Risikokalibrierung. Normen ProdSG MarktueberwG CE-Kennze... |
| `spezial-rechtsquellen-internationaler-bezug-und-schnittstellen` | Rechtsquellen: Internationaler Bezug und Schnittstellen im Plugin produktrecht; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Standardprüfung. |
| `spezial-software-livequellen-und-rechtsprechungscheck` | Software: Livequellen- und Rechtsprechungscheck im Plugin produktrecht; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Standardprüfung. |
| `workflow-dokumentenintake` | Dokumentenintake im Plugin produktrecht: liest Uploads, sortiert Dokumentarten, markiert Fristen und baut eine knappe Arbeitsakte. |
| `workflow-kaltstart-und-routing` | Kaltstart und Routing im Plugin produktrecht: führt vom ersten Satz oder Dokument in den passenden Arbeitsweg, erkennt Rolle, Ziel, Risiko und Anschluss-Skills. |
| `workflow-output-waehlen` | Output wählen im Plugin produktrecht: entscheidet zwischen Memo, Schriftsatz, Tabelle, Brief, Checkliste, Vermerk, Redline oder Mandantenübersetzung. |
| `workflow-rechtsquellen-livecheck` | Rechtsquellen-Livecheck im Plugin produktrecht: zwingt vor tragenden Aussagen zum aktuellen Quellencheck bei Gesetzen, Behörden, Gerichten und Formularen. |
| `workflow-unterlagen-lueckenliste` | Unterlagen- und Lückenliste im Plugin produktrecht: erstellt eine präzise Nachforderungsliste statt allgemeiner Fragebögen. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
