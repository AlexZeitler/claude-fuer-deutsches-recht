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
| `kompendium-01-allgemein-bis-workflow-fristen-und` | normenkontrolle-bauleitplanung: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Allgemein, Chronologie Und Belegmatrix, Fristen Und Risikoampel; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qua... |
| `kompendium-02-workflow-redteam-qua-bis-nkbl-normenkontrolle` | normenkontrolle-bauleitplanung: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Redteam Qualitygate, Jahresfrist 47 Abs 2 Vwgo, Nkbl Normenkontrolle Verfahren Leitfaden; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislo... |
| `kompendium-03-spezial-bebauungspla-bis-abwaegungsgebot-1-ab` | normenkontrolle-bauleitplanung: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Bebauungsplaenen Fristen Form Und Zustaendigkeit, Kommunalabgaben Und Beitragssatzungen, Abwaegungsgebot 1 Abs 7 Baugb; mit Intake, Prüfroutine,... |
| `kompendium-04-allgemeine-satzungsn-bis-antragsbefugnis-eige` | normenkontrolle-bauleitplanung: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Allgemeine Satzungsnormenkontrolle 47 Vwgo, Anpassungsgebot Flaechennutzungsplan, Antragsbefugnis Eigentuemer Nachbar; mit Intake, Prüfroutine, N... |
| `kompendium-05-artenschutz-natursch-bis-benutzungssatzung-ko` | normenkontrolle-bauleitplanung: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Artenschutz Naturschutz Planung, Aufstellungsbeschluss Bekanntmachung, Benutzungssatzung Kommunale Einrichtung; mit Intake, Prüfroutine, Normen-/... |
| `kompendium-06-beteiligung-frueh-fo-bis-eilantrag-47-abs-6-a` | normenkontrolle-bauleitplanung: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Beteiligung Frueh Foermlich, Buergerversammlung Protokoll Audit, Eilantrag 47 Abs 6 Ausserhalb Baurecht; mit Intake, Prüfroutine, Normen-/Quellen... |
| `kompendium-07-einstweilige-anordnu-bis-festsetzungskatalog` | normenkontrolle-bauleitplanung: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Einstweilige Anordnung 47 Abs 6 Vwgo, Erforderlichkeit 1 Abs 3 Baugb, Festsetzungskatalog 9 Baugb Baunvo; mit Intake, Prüfroutine, Normen-/Quelle... |
| `kompendium-08-immissionsschutz-lae-bis-muendliche-verhandlu` | normenkontrolle-bauleitplanung: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Immissionsschutz Laerm Bauleitplanung, Mandat Erstgespraech Normenkontrolle, Muendliche Verhandlung Vgh Strategie; mit Intake, Prüfroutine, Norme... |
| `kompendium-09-nkbl-abwaegungsfehle-bis-nkbl-buergerentschei` | normenkontrolle-bauleitplanung: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Nkbl Abwaegungsfehler Spezial, Nkbl Bauleitplanung Bauleiter, Nkbl Buergerentscheid Buergerbegehren Spezial; mit Intake, Prüfroutine, Normen-/Que... |
| `kompendium-10-normenkontrollantrag-bis-planerhaltung-214-21` | normenkontrolle-bauleitplanung: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Normenkontrollantrag Schriftsatz, Normenkontrolle Oder Inzidentkontrolle, Planerhaltung 214 215 Baugb; mit Intake, Prüfroutine, Normen-/Quellenra... |
| `kompendium-11-polizeiverordnung-un-bis-spezial-abwaegung-fo` | normenkontrolle-bauleitplanung: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Polizeiverordnung Und Gefahrenabwehrsatzung, Rechtsfolge Unwirksamkeit Und Bekanntmachung, Abwaegung Formular Portal Und Einreichung; mit Intake,... |
| `kompendium-12-spezial-anfechtung-t-bis-spezial-antragstelle` | normenkontrolle-bauleitplanung: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Anfechtung Tatbestand Beweis Und Belege, Antragsbefugnis Red Team Und Qualitaetskontrolle, Antragstellervertretung Zahlen Schwellen Und Berechnun... |
| `kompendium-13-spezial-aufstellungs-bis-spezial-bauvorschrif` | normenkontrolle-bauleitplanung: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Aufstellungsbeschluss Mandantenentscheidung, Bauleitplanung Mehrparteien Konflikt Und Interessen, Bauvorschriften Behoerden Gericht Und Registerw... |
| `kompendium-14-spezial-bayvgh-verha-bis-spezial-eilantrag-47` | normenkontrolle-bauleitplanung: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Bayvgh Verhandlung Vergleich Und Eskalation, Bekanntmachung Beweislast Und Darlegungslast, Eilantrag 47 Abs 6 Vwgo; mit Intake, Prüfroutine, Norm... |
| `kompendium-15-spezial-flaechennutz-bis-spezial-oertlichen-r` | normenkontrolle-bauleitplanung: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Flaechennutzungsplaenen Dokumentenmatrix, Normenkontrolle Compliance Dokumentation Und Akte, Oertlichen Risikoampel Und Gegenargumente; mit Intak... |
| `kompendium-16-spezial-planerhaltun-bis-spezial-pruefung-ers` | normenkontrolle-bauleitplanung: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Planerhaltung Abwaegung Antragsbefugnis, Planerhaltung Internationaler Bezug Und Schnittstellen, Pruefung Erstpruefung Und Mandatsziel; mit Intak... |
| `kompendium-17-spezial-vwgo-schrift-bis-stellplatzsatzung-ba` | normenkontrolle-bauleitplanung: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Vwgo Schriftsatz Brief Und Memo Bausteine, Statthaftigkeit 47 Vwgo, Stellplatzsatzung Bay Bauordnung; mit Intake, Prüfroutine, Normen-/Quellenrad... |
| `kompendium-18-umweltbericht-umwelt-bis-vorhabenbezogener-be` | normenkontrolle-bauleitplanung: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Umweltbericht Umweltpruefung, Veraenderungssperre Zurueckstellung 14 15 Baugb, Vorhabenbezogener Bebauungsplan 12 Baugb; mit Intake, Prüfroutine,... |
| `red-team-satzung-jenseits-baugb` | Red-Team Satzung jenseits BauGB: Ermächtigungsgrundlage, Zuständigkeit, Verfahren, Bekanntmachung, Bestimmtheit, Gleichheit, Verhältnismäßigkeit.; Normanker: VwGO § 47; Kommunalrecht; Art. 3 und 12 und 14 GG; macht § 47 VwGO als allgemei... |
| `spezial-mandatsperspektive-livequellen-und-rechtsprechungscheck` | Mandatsperspektive: Livequellen- und Rechtsprechungscheck im Plugin normenkontrolle bauleitplanung; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Standardprüfung. |
| `workflow-anschluss-skills-router` | Anschluss-Skills Router im Plugin normenkontrolle-bauleitplanung: schlägt nach der ersten Prüfung die passenden Spezialskills aus demselben Plugin vor. |
| `workflow-dokumentenintake` | Dokumentenintake im Plugin normenkontrolle-bauleitplanung: liest Uploads, sortiert Dokumentarten, markiert Fristen und baut eine knappe Arbeitsakte. |
| `workflow-kaltstart-und-routing` | Kaltstart und Routing im Plugin normenkontrolle-bauleitplanung: führt vom ersten Satz oder Dokument in den passenden Arbeitsweg, erkennt Rolle, Ziel, Risiko und Anschluss-Skills. |
| `workflow-output-waehlen` | Output wählen im Plugin normenkontrolle-bauleitplanung: entscheidet zwischen Memo, Schriftsatz, Tabelle, Brief, Checkliste, Vermerk, Redline oder Mandantenübersetzung. |
| `workflow-rechtsquellen-livecheck` | Rechtsquellen-Livecheck im Plugin normenkontrolle-bauleitplanung: zwingt vor tragenden Aussagen zum aktuellen Quellencheck bei Gesetzen, Behörden, Gerichten und Formularen. |
| `workflow-unterlagen-lueckenliste` | Unterlagen- und Lückenliste im Plugin normenkontrolle-bauleitplanung: erstellt eine präzise Nachforderungsliste statt allgemeiner Fragebögen. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
