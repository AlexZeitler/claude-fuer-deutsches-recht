# Normenkontrolle Bauleitplanung — § 47 VwGO

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`normenkontrolle-bauleitplanung`) | [`normenkontrolle-bauleitplanung.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/normenkontrolle-bauleitplanung.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **Akte — Bebauungsplan Augsburg-Bahnhofsareal** (`bebauungsplan-augsburg-bahnhofsareal`) | [Gesamt-PDF lesen](../testakten/bebauungsplan-augsburg-bahnhofsareal/gesamt-pdf/bebauungsplan-augsburg-bahnhofsareal_gesamt.pdf) | [`testakte-bebauungsplan-augsburg-bahnhofsareal.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-bebauungsplan-augsburg-bahnhofsareal.zip) |
| **Normenkontrolle B-Plan XV-43d „Spreepark Friedrichshain" — Bürgerinitiative Tannengarten gegen Land Berlin** (`normenkontrolle-bplan-spreepark-friedrichshain-buergerinitiative-tannengarten`) | [Gesamt-PDF lesen](../testakten/normenkontrolle-bplan-spreepark-friedrichshain-buergerinitiative-tannengarten/gesamt-pdf/normenkontrolle-bplan-spreepark-friedrichshain-buergerinitiative-tannengarten_gesamt.pdf) | [`testakte-normenkontrolle-bplan-spreepark-friedrichshain-buergerinitiative-tannengarten.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-normenkontrolle-bplan-spreepark-friedrichshain-buergerinitiative-tannengarten.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

<!-- BEGIN TESTAKTEN-SECTION (auto-generated) -->

## Testakte

Zu diesem Plugin existiert eine vollständige Beispielakte: **— Bebauungsplan Augsburg-Bahnhofsareal** ([`testakten/bebauungsplan-augsburg-bahnhofsareal/`](../testakten/bebauungsplan-augsburg-bahnhofsareal/)).

Direkt-Download als ZIP: [testakte-bebauungsplan-augsburg-bahnhofsareal.zip](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-bebauungsplan-augsburg-bahnhofsareal.zip)

Die Akte ist absichtlich unordentlich, widersprüchlich und ungefiltert. Sie eignet sich für End-to-End-Tests, Demos und zum Üben.

<!-- END TESTAKTEN-SECTION (auto-generated) -->

Freistehendes Plugin für die Prüfung und gerichtliche Anfechtung von **Bebauungsplänen, Flächennutzungsplänen und örtlichen Bauvorschriften** im Normenkontrollverfahren nach § 47 VwGO vor dem **Bayerischen Verwaltungsgerichtshof (BayVGH)** und anderen Oberverwaltungsgerichten.

## Installation

1. Claude Code oder Claude Desktop/Cowork öffnen.
2. **Customize Plugins** bzw. **Personal plugins** wählen.
3. **Install from .zip** und `normenkontrolle-bauleitplanung.zip` hochladen.
4. Mit einem konkreten Auftrag starten, zum Beispiel: `Prüfe diesen Bebauungsplan auf formelle und materielle Fehler.`

Alternativ via Marketplace:

```
/plugin marketplace add Klotzkette/claude-fuer-deutsches-recht
/plugin install normenkontrolle-bauleitplanung@claude-fuer-deutsches-recht
```

Nicht das komplette Repository-ZIP hochladen. Das Plugin-ZIP muss im Root direkt `.claude-plugin/plugin.json` und `skills/` enthalten.

## Normenkontrolle außerhalb der Bauleitplanung

Das Plugin ist nicht nur für Bebauungspläne gedacht. § 47 VwGO kann auch kommunale Satzungen und landesrechtliche Rechtsverordnungen erfassen, soweit das jeweilige Landesrecht die Normenkontrolle eröffnet. Deshalb prüft das Plugin nun ausdrücklich auch Kommunalabgaben-, Beitrags-, Benutzungs-, Friedhofs-, Kita-, Polizei-/Gefahrenabwehr- und sonstige Satzungen sowie die Abgrenzung zur bloßen Inzidentkontrolle im Verfahren gegen einen Einzelbescheid.

## Mandatsperspektive

Anwältin der Antragstellerseite — Eigentümer, Nachbarn, anerkannte Naturschutzverbände, Gemeinden gegen übergeordnete Planung. Schwerpunkt: aus der angegriffenen Satzung die formellen und materiellen Fehler herausarbeiten und vor dem OVG/VGH zur Unwirksamkeitserklärung bringen.

## Aufbau

Der Lebenszyklus eines Normenkontroll-Mandats läuft in vier Phasen:

```
Phase A — Mandat und Zulässigkeit
  └─ Erstgespräch → Statthaftigkeit → Antragsbefugnis → Jahresfrist

Phase B — Verfahrensfehler-Audit (formell)
  └─ Aufstellungsbeschluss → Beteiligungen → Bürgerversammlung
     → Umweltbericht → Planerhaltung §§ 214/215 BauGB

Phase C — Materielle Fehler
  └─ Erforderlichkeit § 1 Abs. 3 → Abwägungsgebot § 1 Abs. 7
     → Stellplätze → Lärm/Immissionsschutz → Artenschutz
     → Anpassung Flächennutzungsplan

Phase D — Verfahren BayVGH/OVG
  └─ Normenkontrollantrag → Eilantrag § 47 Abs. 6 VwGO
     → Mündliche Verhandlung
```

## Enthaltene Skills

### Phase A — Mandat und Zulässigkeit (4 Skills)

| Slug | Beschreibung |
|---|---|
| `mandat-erstgespraech-normenkontrolle` | Erstgespräch, Mandantenbetroffenheit, Erfolgsaussichten-Prognose, Kosten |
| `statthaftigkeit-47-vwgo` | Antragsgegenstand B-Plan/FNP/örtliche Bauvorschrift, Landesrecht im Rang unter Landesgesetz |
| `antragsbefugnis-eigentuemer-nachbar` | § 47 Abs. 2 VwGO Möglichkeitstheorie, Eigentum, abwägungserheblicher Belang, Verbandsklage |
| `jahresfrist-47-abs-2-vwgo` | Fristlauf ab Bekanntmachung, Wiedereinsetzung, Heilung durch ergänzendes Verfahren |

### Phase B — Verfahrensfehler-Audit (5 Skills)

| Slug | Beschreibung |
|---|---|
| `aufstellungsbeschluss-bekanntmachung` | § 2 Abs. 1, § 10 Abs. 3 BauGB Verfahrenskette, Anstoßfunktion |
| `beteiligung-frueh-foermlich` | §§ 3 Abs. 1, 3 Abs. 2, 4 Abs. 1, 4 Abs. 2 BauGB Behörden- und Öffentlichkeitsbeteiligung |
| `buergerversammlung-protokoll-audit` | Erörterungstermin, Behandlung Einwendungen, Vorfestlegungsverbot |
| `umweltbericht-umweltpruefung` | § 2 Abs. 4 BauGB, § 2a BauGB, UVPG-Verzahnung, FFH-Vorprüfung |
| `planerhaltung-214-215-baugb` | Beachtlichkeit, Rügefrist 1 Jahr, ergänzendes Verfahren § 214 Abs. 4 BauGB |

### Phase C — Materielle Fehler (9 Skills)

| Slug | Beschreibung |
|---|---|
| `erforderlichkeit-1-abs-3-baugb` | Planrechtfertigung, städtebauliches Konzept, Gefälligkeitsplanung |
| `abwaegungsgebot-1-abs-7-baugb` | Abwägungsausfall, Abwägungsdefizit, Fehlgewichtung, Disproportionalität |
| `stellplatzsatzung-bay-bauordnung` | Art. 47 BayBO Stellplatzpflicht, Reduzierung durch Satzung, Mobilitätskonzept |
| `immissionsschutz-laerm-bauleitplanung` | DIN 18005, TA Lärm, Trennungsgebot § 50 BImSchG, Schallschutzgutachten-Prüfung |
| `artenschutz-naturschutz-planung` | § 44 BNatSchG saP, FFH-Vorprüfung, Eingriffsregelung § 1a BauGB |
| `anpassungsgebot-flaechennutzungsplan` | § 8 Abs. 2 BauGB Entwicklungsgebot, Parallelverfahren, FNP-Berichtigung |
| Rechtsprechung live prüfen | keine Entscheidung aus Modellwissen; Quelle vor Ausgabe protokollieren |
| `festsetzungskatalog-9-baugb-baunvo` | Abschließender § 9-Katalog, BauNVO-Höchstgrenzen, dynamische Verweisungen, Bahnflächen § 38 BauGB |
| `veraenderungssperre-zurueckstellung-14-15-baugb` | § 14 Sperre, § 15 Zurückstellung, Entschädigung § 18, vertraglich-faktische Sperre |

### Phase D — Verfahren BayVGH/OVG (3 Skills)

| Slug | Beschreibung |
|---|---|
| `normenkontrollantrag-schriftsatz` | Aufbau, Antragsformulierung, Begründungsstruktur, Streitwert |
| `einstweilige-anordnung-47-abs-6-vwgo` | Vollzugsfolgenabwägung, Eilbedürftigkeit, Antragsbefugnis im Eilverfahren |
| `muendliche-verhandlung-vgh-strategie` | Vorbereitung, Beweisanträge, Plädoyer, Wirkungsausspruch |

## Vorlagen

- `assets/templates/normenkontrolle-mandatskarte.md` — Übersichtskarte für jedes Normenkontroll-Mandat
- `assets/templates/fehleraudit-checkliste.md` — Systematische Prüfreihenfolge formell vor materiell

## Bedienungshinweis

Das Plugin ist freistehend nutzbar und benötigt keine anderen Plugins des Marketplaces. Für umweltrechtliche Querfragen (FFH, saP, UVP) kann das Plugin `umweltrecht` ergänzend geladen werden, für allgemeine Verwaltungsverfahrensfragen das Plugin `verwaltungsrecht`.

<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 26 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `allgemein-workflow-chronologie-workflow-fristen` | Allgemein, Workflow Chronologie Und Belegmatrix, Workflow Fristen Und Risikoampel: Allgemein; Workflow Chronologie Und Belegmatrix; Workflow Fristen Und Risikoampel. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmus... |
| `allgemeine-satzungsnormenkontrolle-anpassungsgebot` | Allgemeine Satzungsnormenkontrolle 47 Vwgo, Anpassungsgebot Flaechennutzungsplan, Antragsbefugnis Eigentuemer Nachbar: Allgemeine Satzungsnormenkontrolle 47 Vwgo; Anpassungsgebot Flaechennutzungsplan; Antragsbefugnis Eigentuemer Nachbar.... |
| `anfechtung-antragsbefugnis-red-antragstellervertretung` | Spezial Anfechtung Tatbestand Beweis Und Belege, Spezial Antragsbefugnis Red Team Und Qualitaetskontrolle, Spezial Antragstellervertretung Zahlen Schwellen Und Berechnung: Spezial Anfechtung Tatbestand Beweis Und Belege; Spezial Antragsb... |
| `artenschutz-naturschutz-aufstellungsbeschluss-bekanntmachung` | Artenschutz Naturschutz Planung, Aufstellungsbeschluss Bekanntmachung, Benutzungssatzung Kommunale Einrichtung: Artenschutz Naturschutz Planung; Aufstellungsbeschluss Bekanntmachung; Benutzungssatzung Kommunale Einrichtung. Führt Intake,... |
| `aufstellungsbeschluss-mandantenentscheidung-bauleitplanung` | Spezial Aufstellungsbeschluss Mandantenentscheidung, Spezial Bauleitplanung Mehrparteien Konflikt Und Interessen, Spezial Bauvorschriften Behörden Gericht Und Registerweg: Spezial Aufstellungsbeschluss Mandantenentscheidung; Spezial Baul... |
| `bayvgh-bekanntmachung-beweislast-eilantrag-abs` | Spezial Bayvgh Verhandlung Vergleich Und Eskalation, Spezial Bekanntmachung Beweislast Und Darlegungslast, Spezial Eilantrag 47 Abs 6 Vwgo: Spezial Bayvgh Verhandlung Vergleich Und Eskalation; Spezial Bekanntmachung Beweislast Und Darleg... |
| `bebauungsplaenen-kommunalabgaben-beitragssatzungen` | Spezial Bebauungsplaenen Fristen Form Und Zustaendigkeit, Kommunalabgaben Und Beitragssatzungen, Abwaegungsgebot 1 Abs 7 Baugb: Spezial Bebauungsplaenen Fristen Form Und Zustaendigkeit; Kommunalabgaben Und Beitragssatzungen; Abwaegungsge... |
| `beteiligung-frueh-buergerversammlung-protokoll-eilantrag-abs` | Beteiligung Früh Foermlich, Buergerversammlung Protokoll Audit, Eilantrag 47 Abs 6 Ausserhalb Baurecht: Beteiligung Früh Foermlich; Buergerversammlung Protokoll Audit; Eilantrag 47 Abs 6 Ausserhalb Baurecht. Führt Intake, Prüfroutine, No... |
| `einstweilige-anordnung-erforderlichkeit-abs-festsetzungskatalog` | Einstweilige Anordnung 47 Abs 6 Vwgo, Erforderlichkeit 1 Abs 3 Baugb, Festsetzungskatalog 9 Baugb Baunvo: Einstweilige Anordnung 47 Abs 6 Vwgo; Erforderlichkeit 1 Abs 3 Baugb; Festsetzungskatalog 9 Baugb Baunvo. Führt Intake, Prüfroutine... |
| `flaechennutzungsplaenen-normenkontrolle-oertlichen` | Spezial Flaechennutzungsplaenen Dokumentenmatrix, Spezial Normenkontrolle Compliance Dokumentation Und Akte, Spezial Oertlichen Risikoampel Und Gegenargumente: Spezial Flaechennutzungsplaenen Dokumentenmatrix; Spezial Normenkontrolle Com... |
| `immissionsschutz-laerm-mandat-erstgespraech-muendliche-vgh` | Immissionsschutz Laerm Bauleitplanung, Mandat Erstgespraech Normenkontrolle, Muendliche Verhandlung Vgh Strategie: Immissionsschutz Laerm Bauleitplanung; Mandat Erstgespraech Normenkontrolle; Muendliche Verhandlung Vgh Strategie. Führt I... |
| `nkbl-abwaegungsfehler-bauleitplanung-bauleiter-buergerentscheid` | Nkbl Abwaegungsfehler Spezial, Nkbl Bauleitplanung Bauleiter, Nkbl Buergerentscheid Buergerbegehren Spezial: Nkbl Abwaegungsfehler Spezial; Nkbl Bauleitplanung Bauleiter; Nkbl Buergerentscheid Buergerbegehren Spezial. Führt Intake, Prüfr... |
| `normenkontrollantrag-normenkontrolle-inzidentkontrolle` | Normenkontrollantrag Schriftsatz, Normenkontrolle Oder Inzidentkontrolle, Planerhaltung 214 215 Baugb: Normenkontrollantrag Schriftsatz; Normenkontrolle Oder Inzidentkontrolle; Planerhaltung 214 215 Baugb. Führt Intake, Prüfroutine, Norm... |
| `planerhaltung-abwaegung-planerhaltung-spezial-pruefung` | Spezial Planerhaltung Abwaegung Antragsbefugnis, Spezial Planerhaltung Internationaler Bezug Und Schnittstellen, Spezial Prüfung Erstpruefung Und Mandatsziel: Spezial Planerhaltung Abwaegung Antragsbefugnis; Spezial Planerhaltung Interna... |
| `polizeiverordnung-gefahrenabwehrsatzung-rechtsfolge` | Polizeiverordnung Und Gefahrenabwehrsatzung, Rechtsfolge Unwirksamkeit Und Bekanntmachung, Spezial Abwaegung Formular Portal Und Einreichung: Polizeiverordnung Und Gefahrenabwehrsatzung; Rechtsfolge Unwirksamkeit Und Bekanntmachung; Spez... |
| `red-team-satzung-jenseits-baugb` | Red-Team Satzung jenseits BauGB: Ermächtigungsgrundlage, Zuständigkeit, Verfahren, Bekanntmachung, Bestimmtheit, Gleichheit, Verhältnismäßigkeit.; Normanker: VwGO § 47; Kommunalrecht; Art. 3 und 12 und 14 GG; macht § 47 VwGO als allgemei... |
| `spezial-mandatsperspektive-livequellen-und-rechtsprechungscheck` | Mandatsperspektive: Livequellen- und Rechtsprechungscheck im Plugin normenkontrolle bauleitplanung; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Standardprüfung. |
| `umweltbericht-umweltpruefung-veraenderungssperre-zurueckstellung` | Umweltbericht Umweltpruefung, Veraenderungssperre Zurueckstellung 14 15 Baugb, Vorhabenbezogener Bebauungsplan 12 Baugb: Umweltbericht Umweltpruefung; Veraenderungssperre Zurueckstellung 14 15 Baugb; Vorhabenbezogener Bebauungsplan 12 Ba... |
| `vwgo-statthaftigkeit-vwgo-stellplatzsatzung-bay` | Spezial Vwgo Schriftsatz Brief Und Memo Bausteine, Statthaftigkeit 47 Vwgo, Stellplatzsatzung Bay Bauordnung: Spezial Vwgo Schriftsatz Brief Und Memo Bausteine; Statthaftigkeit 47 Vwgo; Stellplatzsatzung Bay Bauordnung. Führt Intake, Prü... |
| `workflow-anschluss-skills-router` | Anschluss-Skills Router im Plugin normenkontrolle-bauleitplanung: schlägt nach der ersten Prüfung die passenden Spezialskills aus demselben Plugin vor. |
| `workflow-dokumentenintake` | Dokumentenintake im Plugin normenkontrolle-bauleitplanung: liest Uploads, sortiert Dokumentarten, markiert Fristen und baut eine knappe Arbeitsakte. |
| `workflow-kaltstart-und-routing` | Kaltstart und Routing im Plugin normenkontrolle-bauleitplanung: führt vom ersten Satz oder Dokument in den passenden Arbeitsweg, erkennt Rolle, Ziel, Risiko und Anschluss-Skills. |
| `workflow-output-waehlen` | Output wählen im Plugin normenkontrolle-bauleitplanung: entscheidet zwischen Memo, Schriftsatz, Tabelle, Brief, Checkliste, Vermerk, Redline oder Mandantenübersetzung. |
| `workflow-rechtsquellen-livecheck` | Rechtsquellen-Livecheck im Plugin normenkontrolle-bauleitplanung: zwingt vor tragenden Aussagen zum aktuellen Quellencheck bei Gesetzen, Behörden, Gerichten und Formularen. |
| `workflow-redteam-jahresfrist-abs-nkbl-verfahren` | Workflow Redteam Qualitygate, Jahresfrist 47 Abs 2 Vwgo, Nkbl Normenkontrolle Verfahren Leitfaden: Workflow Redteam Qualitygate; Jahresfrist 47 Abs 2 Vwgo; Nkbl Normenkontrolle Verfahren Leitfaden. Führt Intake, Prüfroutine, Normen-/Quel... |
| `workflow-unterlagen-lueckenliste` | Unterlagen- und Lückenliste im Plugin normenkontrolle-bauleitplanung: erstellt eine präzise Nachforderungsliste statt allgemeiner Fragebögen. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
