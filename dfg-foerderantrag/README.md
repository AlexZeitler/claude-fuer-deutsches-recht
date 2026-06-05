# DFG-Förderantrag

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`dfg-foerderantrag`) | [`dfg-foerderantrag.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/dfg-foerderantrag.zip) |

Dieses Plugin hat (bewusst) keine eigene Demonstrations-Akte.

<!-- END plugin-sofort-download-section (autogen) -->

Plugin für die praktische Antragstellung bei der Deutschen Forschungsgemeinschaft: Sachbeihilfe, elan-Formalia, Projektbeschreibung, Finanzplan, Forschungsdaten, Ethik-/KI-Check, Reviewer-Perspektive, Wiedereinreichung und strategische Entscheidung zwischen kleinem schnellen Antrag und großem Prestigeprojekt.

Der Stil ist bewusst nicht bürokratisch. Das Plugin fragt zuerst: Was ist wissenschaftlich stark, was ist realistisch förderbar, was kann schneller entschieden werden und wo ist der große Antrag zwar verführerisch, aber prozessual zäher? Es arbeitet adaptiv: Anfänger bekommen eine geführte Mini-Roadmap; erfahrene Antragsteller bekommen direkt Red-Team, Kürzungsrisiko und Programmstrategie.

## Quellen-Gate

Vor jeder belastbaren Ausgabe aktuelle DFG-Seiten prüfen:

- DFG Sachbeihilfe: themenoffene Einzelförderung, Neuanträge jederzeit, Fortsetzungsanträge spätestens 6 Monate vor Mittelverbrauch.
- DFG Begutachtung: grundsätzlich zwei Gutachten; bei Anträgen bis 200.000 Euro kann ausnahmsweise ein aussagekräftiges externes Gutachten reichen.
- Reinhart-Koselleck-Projekte: 500.000 bis 1,25 Mio. Euro für fünf Jahre in Stufen von 250.000 Euro; nur für herausragende, besonders innovative oder risikobehaftete Projekte, die nicht in normale Verfahren passen.
- DFG-Merkblätter, elan-Vorlagen, fachzuständige Ansprechpersonen und aktuelle Vordruckstände immer live gegen `dfg.de` prüfen.

## Schnellstart

```text
/dfg-foerderantrag:allgemein
```

Der Allgemein-Skill führt in 60 Sekunden durch: Forschungsfrage, Förderprogramm, Summe, Tempo, Zielgruppe der Begutachtung, Vorarbeiten, Risiken, Daten-/Ethikthemen und gewünschtes Ergebnis.

Typische Startpunkte:

| Situation | Start |
| --- | --- |
| "Ich habe nur eine Forschungsidee" | `allgemein` → Mini-Roadmap und Minimalprojekt |
| "Sachbeihilfe oder größer?" | `dfg-foerderstrategie-schnell-oder-gross` |
| "Entwurf liegt vor" | `dfg-reviewer-red-team` → danach Text- und Finanzskills |
| "Ablehnung liegt vor" | `dfg-wiedereinreichung-nach-ablehnung` |

## Skill-Matrix

| Skill | Wofür? |
| --- | --- |
| `allgemein` | Einstieg, Triage, Programmroute und erster Arbeitsplan |
| `dfg-foerderstrategie-schnell-oder-gross` | Entscheidung: kleiner schneller Antrag, normale Sachbeihilfe, Koselleck oder anderes Programm |
| `dfg-sachbeihilfe-elan-formalia` | Sachbeihilfe, elan, Anlagen, Vordrucklogik, formales Gate |
| `dfg-bis-200k-begutachtung-light` | Kleine/mittlere Anträge so bauen, dass sie schnell, klar und begutachtbar sind |
| `dfg-koselleck-500k-125m` | Koselleck-Check: 500.000 bis 1,25 Mio. Euro, Risiko, Profil, Vertrauensvorschuss |
| `dfg-projektbeschreibung-arbeitsprogramm` | Forschungsfrage, Stand der Forschung, Ziele, Arbeitspakete, Meilensteine |
| `dfg-finanzplan-module-personal-geraete` | Personal, Geräte, Reisen, Workshops, Mercator Fellow, Chancengleichheit, Budgetbegründung |
| `dfg-reviewer-red-team` | Gutachterperspektive, Angriffsflächen, Kürzungsrisiken, Ablehnungsgründe |
| `dfg-wiedereinreichung-nach-ablehnung` | Ablehnung auswerten, Gutachten ernst nehmen, Neuaufstellung |
| `dfg-ki-ethik-forschungsdaten` | KI-Nutzung, Vertraulichkeit, Forschungsdatenmanagement, Ethik und Datenschutz |

<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 24 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `allgemein-workflow-chronologie-workflow-fristen` | Allgemein, Workflow Chronologie Und Belegmatrix, Workflow Fristen Und Risikoampel: Allgemein; Workflow Chronologie Und Belegmatrix; Workflow Fristen Und Risikoampel. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmus... |
| `anfaenger-antraege-dfg` | Spezial Anfaenger Risikoampel Und Gegenargumente, Spezial Antraege Zahlen Schwellen Und Berechnung, Spezial Dfg Erstpruefung Und Mandatsziel: Spezial Anfaenger Risikoampel Und Gegenargumente; Spezial Antraege Zahlen Schwellen Und Berechn... |
| `dfg-koselleck-500k-praeregistrierung-replication` | Dfg Koselleck 500K 125M, Dfg Praeregistrierung Replication Studies, Dfg Projektbeschreibung Arbeitsprogramm: Dfg Koselleck 500K 125M; Dfg Praeregistrierung Replication Studies; Dfg Projektbeschreibung Arbeitsprogramm. Führt Intake, Prüfr... |
| `dfg-reviewer-red-team` | DFG-Antrag aus Gutachterperspektive red-teamen: Originalität, Machbarkeit, Arbeitsprogramm, Qualifikation, Umfeld, Bias-Risiken, Kürzungsargumente, Ablehnungsrisiken und Verbesserungsplan. |
| `dfg-software-veroeffentlichung-tieforschung-ethik` | Dfg Software Veroeffentlichung Spezial, Dfg Tieforschung Ethik Pflichten, Dfg Wiedereinreichung Nach Ablehnung: Dfg Software Veroeffentlichung Spezial; Dfg Tieforschung Ethik Pflichten; Dfg Wiedereinreichung Nach Ablehnung. Führt Intake,... |
| `eigene-vorarbeiten-erstantragsteller-besondere-finanzplan` | Dfg Eigene Vorarbeiten Darstellen, Dfg Erstantragsteller Besondere Checks, Dfg Finanzplan Module Personal Geraete: Dfg Eigene Vorarbeiten Darstellen; Dfg Erstantragsteller Besondere Checks; Dfg Finanzplan Module Personal Geraete. Führt I... |
| `elan-ethik-finanzplan` | Spezial Elan Formular Portal Und Einreichung, Spezial Ethik Abschlussprodukt Und Übergabe, Spezial Finanzplan Mandantenkommunikation Entscheidungsvorlage: Spezial Elan Formular Portal Und Einreichung; Spezial Ethik Abschlussprodukt Und Ü... |
| `foerderantragssteller-formalia-red-fuehrung` | Spezial Foerderantragssteller Tatbestand Beweis Und Belege, Spezial Formalia Red Team Und Qualitaetskontrolle, Spezial Fuehrung Schriftsatz Brief Und Memo Bausteine: Spezial Foerderantragssteller Tatbestand Beweis Und Belege; Spezial For... |
| `foerderstrategie-schnell-grossgeraete-cluster-grundsystem` | Dfg Foerderstrategie Schnell Oder Gross, Dfg Grossgeraete Und Cluster Antrag, Dfg Grundsystem Foerderlinien: Dfg Foerderstrategie Schnell Oder Gross; Dfg Grossgeraete Und Cluster Antrag; Dfg Grundsystem Foerderlinien. Führt Intake, Prüfr... |
| `grosse-kleine-koselleck-interessen` | Spezial Grosse Compliance Dokumentation Und Akte, Spezial Kleine Verhandlung Vergleich Und Eskalation, Spezial Koselleck Mehrparteien Konflikt Und Interessen: Spezial Grosse Compliance Dokumentation Und Akte; Spezial Kleine Verhandlung V... |
| `internationale-kooperation-ki-ethik-kollegen-review` | Dfg Internationale Kooperation Aufbau, Dfg Ki Ethik Forschungsdaten, Dfg Kollegen Review Organisieren: Dfg Internationale Kooperation Aufbau; Dfg Ki Ethik Forschungsdaten; Dfg Kollegen Review Organisieren. Führt Intake, Prüfroutine, Norm... |
| `profi-reviewer-beweislast-strategien` | Spezial Profi Behörden Gericht Und Registerweg, Spezial Reviewer Beweislast Und Darlegungslast, Spezial Strategien Internationaler Bezug Und Schnittstellen: Spezial Profi Behörden Gericht Und Registerweg; Spezial Reviewer Beweislast Und... |
| `publikationsstrategie-projekt-replikationskrise-statistik` | Dfg Publikationsstrategie Projekt, Dfg Replikationskrise Statistik Spezial, Dfg Sachbeihilfe Elan Formalia: Dfg Publikationsstrategie Projekt; Dfg Replikationskrise Statistik Spezial; Dfg Sachbeihilfe Elan Formalia. Führt Intake, Prüfrou... |
| `sachbeihilfe-bis-200k-eigenanteil-grundausstattung` | Spezial Sachbeihilfe Fristen Form Und Zustaendigkeit, Dfg Bis 200K Begutachtung Light, Dfg Eigenanteil Und Grundausstattung: Spezial Sachbeihilfe Fristen Form Und Zustaendigkeit; Dfg Bis 200K Begutachtung Light; Dfg Eigenanteil Und Grund... |
| `spezial-schnelle-livequellen-und-rechtsprechungscheck` | Schnelle: Livequellen- und Rechtsprechungscheck im Plugin dfg foerderantrag; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Standardprüfung. |
| `team-sonderfall` | Spezial Team Sonderfall Und Edge Case: Spezial Team Sonderfall Und Edge Case. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zusammen. |
| `workflow-anschluss-skills-router` | Anschluss-Skills Router im Plugin dfg-foerderantrag: schlägt nach der ersten Prüfung die passenden Spezialskills aus demselben Plugin vor. |
| `workflow-dokumentenintake` | Dokumentenintake im Plugin dfg-foerderantrag: liest Uploads, sortiert Dokumentarten, markiert Fristen und baut eine knappe Arbeitsakte. |
| `workflow-kaltstart-und-routing` | Kaltstart und Routing im Plugin dfg-foerderantrag: führt vom ersten Satz oder Dokument in den passenden Arbeitsweg, erkennt Rolle, Ziel, Risiko und Anschluss-Skills. |
| `workflow-mandantenkommunikation-redteam-qualitygate` | Workflow Mandantenkommunikation, Workflow Redteam Qualitygate, Spezial Forschungsdaten Fristennotiz Und Naechster Schritt: Workflow Mandantenkommunikation; Workflow Redteam Qualitygate; Spezial Forschungsdaten Fristennotiz Und Naechster... |
| `workflow-output-waehlen` | Output wählen im Plugin dfg-foerderantrag: entscheidet zwischen Memo, Schriftsatz, Tabelle, Brief, Checkliste, Vermerk, Redline oder Mandantenübersetzung. |
| `workflow-rechtsquellen-livecheck` | Rechtsquellen-Livecheck im Plugin dfg-foerderantrag: zwingt vor tragenden Aussagen zum aktuellen Quellencheck bei Gesetzen, Behörden, Gerichten und Formularen. |
| `workflow-unterlagen-lueckenliste` | Unterlagen- und Lückenliste im Plugin dfg-foerderantrag: erstellt eine präzise Nachforderungsliste statt allgemeiner Fragebögen. |
| `zeitplan-meilensteine-zwischen-abschlussbericht-adaptive` | Dfg Zeitplan Und Meilensteine, Dfg Zwischen Und Abschlussbericht, Spezial Adaptive Dokumentenmatrix Und Lueckenliste: Dfg Zeitplan Und Meilensteine; Dfg Zwischen Und Abschlussbericht; Spezial Adaptive Dokumentenmatrix Und Lueckenliste. F... |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
