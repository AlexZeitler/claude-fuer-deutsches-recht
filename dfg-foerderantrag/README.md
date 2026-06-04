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
| `dfg-reviewer-red-team` | DFG-Antrag aus Gutachterperspektive red-teamen: Originalität, Machbarkeit, Arbeitsprogramm, Qualifikation, Umfeld, Bias-Risiken, Kürzungsargumente, Ablehnungsrisiken und Verbesserungsplan. |
| `kompendium-01-allgemein-bis-workflow-fristen-und` | dfg-foerderantrag: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Allgemein, Chronologie Und Belegmatrix, Fristen Und Risikoampel; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck. |
| `kompendium-02-workflow-mandantenko-bis-spezial-forschungsda` | dfg-foerderantrag: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Mandantenkommunikation, Redteam Qualitygate, Forschungsdaten Fristennotiz Und Naechster Schritt; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, O... |
| `kompendium-03-spezial-sachbeihilfe-bis-dfg-eigenanteil-und` | dfg-foerderantrag: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Sachbeihilfe Fristen Form Und Zustaendigkeit, Dfg Bis 200k Begutachtung Light, Dfg Eigenanteil Und Grundausstattung; mit Intake, Prüfroutine, Normen-/Quellenr... |
| `kompendium-04-dfg-eigene-vorarbeit-bis-dfg-finanzplan-modul` | dfg-foerderantrag: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Dfg Eigene Vorarbeiten Darstellen, Dfg Erstantragsteller Besondere Checks, Dfg Finanzplan Module Personal Geraete; mit Intake, Prüfroutine, Normen-/Quellenrad... |
| `kompendium-05-dfg-foerderstrategie-bis-dfg-grundsystem-foer` | dfg-foerderantrag: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Dfg Foerderstrategie Schnell Oder Gross, Dfg Grossgeraete Und Cluster Antrag, Dfg Grundsystem Foerderlinien; mit Intake, Prüfroutine, Normen-/Quellenradar, Be... |
| `kompendium-06-dfg-internationale-k-bis-dfg-kollegen-review` | dfg-foerderantrag: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Dfg Internationale Kooperation Aufbau, Dfg Ki Ethik Forschungsdaten, Dfg Kollegen Review Organisieren; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislo... |
| `kompendium-07-dfg-koselleck-500k-1-bis-dfg-projektbeschreib` | dfg-foerderantrag: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Dfg Koselleck 500k 125m, Dfg Praeregistrierung Replication Studies, Dfg Projektbeschreibung Arbeitsprogramm; mit Intake, Prüfroutine, Normen-/Quellenradar, Be... |
| `kompendium-08-dfg-publikationsstra-bis-dfg-sachbeihilfe-ela` | dfg-foerderantrag: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Dfg Publikationsstrategie Projekt, Dfg Replikationskrise Statistik Spezial, Dfg Sachbeihilfe Elan Formalia; mit Intake, Prüfroutine, Normen-/Quellenradar, Bew... |
| `kompendium-09-dfg-software-veroeff-bis-dfg-wiedereinreichun` | dfg-foerderantrag: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Dfg Software Veroeffentlichung Spezial, Dfg Tieforschung Ethik Pflichten, Dfg Wiedereinreichung Nach Ablehnung; mit Intake, Prüfroutine, Normen-/Quellenradar,... |
| `kompendium-10-dfg-zeitplan-und-mei-bis-spezial-adaptive-dok` | dfg-foerderantrag: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Dfg Zeitplan Und Meilensteine, Dfg Zwischen Und Abschlussbericht, Adaptive Dokumentenmatrix Und Lueckenliste; mit Intake, Prüfroutine, Normen-/Quellenradar, B... |
| `kompendium-11-spezial-anfaenger-ri-bis-spezial-dfg-erstprue` | dfg-foerderantrag: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Anfaenger Risikoampel Und Gegenargumente, Antraege Zahlen Schwellen Und Berechnung, Dfg Erstpruefung Und Mandatsziel; mit Intake, Prüfroutine, Normen-/Quellen... |
| `kompendium-12-spezial-elan-formula-bis-spezial-finanzplan-m` | dfg-foerderantrag: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Elan Formular Portal Und Einreichung, Ethik Abschlussprodukt Und Uebergabe, Finanzplan Mandantenkommunikation Entscheidungsvorlage; mit Intake, Prüfroutine, N... |
| `kompendium-13-spezial-foerderantra-bis-spezial-fuehrung-sch` | dfg-foerderantrag: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Foerderantragssteller Tatbestand Beweis Und Belege, Formalia Red Team Und Qualitaetskontrolle, Fuehrung Schriftsatz Brief Und Memo Bausteine; mit Intake, Prüf... |
| `kompendium-14-spezial-grosse-compl-bis-spezial-koselleck-me` | dfg-foerderantrag: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Grosse Compliance Dokumentation Und Akte, Kleine Verhandlung Vergleich Und Eskalation, Koselleck Mehrparteien Konflikt Und Interessen; mit Intake, Prüfroutine... |
| `kompendium-15-spezial-profi-behoer-bis-spezial-strategien-i` | dfg-foerderantrag: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Profi Behoerden Gericht Und Registerweg, Reviewer Beweislast Und Darlegungslast, Strategien Internationaler Bezug Und Schnittstellen; mit Intake, Prüfroutine,... |
| `kompendium-16-spezial-team-sonderf-bis-spezial-team-sonderf` | dfg-foerderantrag: eigenständiger Arbeits-Skill zu Team Sonderfall Und Edge Case; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck. |
| `spezial-schnelle-livequellen-und-rechtsprechungscheck` | Schnelle: Livequellen- und Rechtsprechungscheck im Plugin dfg foerderantrag; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Standardprüfung. |
| `workflow-anschluss-skills-router` | Anschluss-Skills Router im Plugin dfg-foerderantrag: schlägt nach der ersten Prüfung die passenden Spezialskills aus demselben Plugin vor. |
| `workflow-dokumentenintake` | Dokumentenintake im Plugin dfg-foerderantrag: liest Uploads, sortiert Dokumentarten, markiert Fristen und baut eine knappe Arbeitsakte. |
| `workflow-kaltstart-und-routing` | Kaltstart und Routing im Plugin dfg-foerderantrag: führt vom ersten Satz oder Dokument in den passenden Arbeitsweg, erkennt Rolle, Ziel, Risiko und Anschluss-Skills. |
| `workflow-output-waehlen` | Output wählen im Plugin dfg-foerderantrag: entscheidet zwischen Memo, Schriftsatz, Tabelle, Brief, Checkliste, Vermerk, Redline oder Mandantenübersetzung. |
| `workflow-rechtsquellen-livecheck` | Rechtsquellen-Livecheck im Plugin dfg-foerderantrag: zwingt vor tragenden Aussagen zum aktuellen Quellencheck bei Gesetzen, Behörden, Gerichten und Formularen. |
| `workflow-unterlagen-lueckenliste` | Unterlagen- und Lückenliste im Plugin dfg-foerderantrag: erstellt eine präzise Nachforderungsliste statt allgemeiner Fragebögen. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
