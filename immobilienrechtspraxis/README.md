# Immobilienrechtspraxis

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`immobilienrechtspraxis`) | [`immobilienrechtspraxis.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/immobilienrechtspraxis.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **Grundstückskauf / Baulast / Mehrfamilienhaus Rosenmündl — Stuttgart-Ost** (`grundstueckskauf-baulast-mehrfamilienhaus-rosenmuendl-stuttgart-ost`) | [Gesamt-PDF lesen](../testakten/grundstueckskauf-baulast-mehrfamilienhaus-rosenmuendl-stuttgart-ost/gesamt-pdf/grundstueckskauf-baulast-mehrfamilienhaus-rosenmuendl-stuttgart-ost_gesamt.pdf) | [`testakte-grundstueckskauf-baulast-mehrfamilienhaus-rosenmuendl-stuttgart-ost.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-grundstueckskauf-baulast-mehrfamilienhaus-rosenmuendl-stuttgart-ost.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

Werkzeuge für immobilienrechtliche Rechtsabteilungen — musterbasierte Vertragserstellung mit Klauselschutz; Vertragsprüfung gegen Playbook; Grundbuchanalyse; Sachverhaltsermittlung; Mieteranfragen mit BGH-Verankerung; Case Management; projektbasierte Arbeitsweise mit AVV-Prüfung.

## Installation in Claude Code

1. ZIP herunterladen (Link oben).
2. Claude Code → **Customize Plugins** → **Install from .zip** → Datei wählen.
3. Fertig. Skills sind sofort verfügbar.

> **Hinweis:** Für den ZIP-Upload muss das Archiv direkt `.claude-plugin/plugin.json`, `skills/`, `assets/` und `references/` im ZIP-Root enthalten. **Nicht** das komplette Repository-ZIP aus "Code → Download ZIP" verwenden.

## Enthaltene Skills

| Skill | Zweck |
| --- | --- |
| `case-management` | KI-gestütztes Case Management für immobilienrechtliche Vorgänge. Pro Fall werden Akte Korrespondenz Verträge Schriftsätze und Fristen strukturiert dokumentiert und fortgeschrieben. Erzeugt Fallübersicht in Markd… |
| `grundbuchanalyse` | Strukturierte Auswertung großer Mengen Grundbuchdaten — Grundbuchauszüge Flurkarten Baulastenverzeichnis Altlastenkataster. Extrahiert pro Objekt Eigentümerkette Belastungen in Abteilung II und III Rang Löschungse… |
| `mieteranfragen-bearbeitung` | Bearbeitet eingehende mietrechtliche Anfragen — Mietmängelanzeigen Kündigungen Mieterhöhungsverlangen Widersprüche nach § 574 BGB Betriebskosten-Einwendungen Untervermietungsanfragen — und erstellt fundierte Antwo… |
| `projekt-arbeitsweise` | Strukturierte Projekt- und Ordnerarbeit für immobilienrechtliche Rechtsabteilungen statt freihändigem Prompting. Pro Mandat oder Objekt entsteht ein Projekt-Ordner mit fixierten Vorgaben — Playbook Musterverträge K… |
| `sachverhaltsermittlung` | Unterstützt Inhouse-Juristen bei der zeitraubendsten Phase eines Vorgangs — der Sachverhaltsermittlung. Statt sofort den vollen Sachverhalt zu fordern, führt der Skill einen strukturierten Frageprozess in mehreren S… |
| `vertragserstellung-musterbasiert` | Erstellt immobilienrechtliche Verträge strikt auf Basis hausinterner Musterverträge und Term Sheets. Kernregel ist Klauselschutz — vorgegebene Musterklauseln werden NICHT umformuliert. KI füllt nur markierte Platzh… |
| `vertragspruefung-playbook` | Prüft externe Immobilienverträge gegen das hauseigene Playbook der Rechtsabteilung. Drei Ausgaben — Ampelmatrix nach Klauselkatalog, Redline-Empfehlung als chirurgische Tracked Changes und Business-Memo für das Ass… |

## Lizenz

Apache-2.0 OR MIT — Auswahl beim Empfänger.

## Quellen-Disclaimer

Quellenregel: Keine Kommentar-, Handbuch- oder Aufsatzfundstellen aus Modellwissen; Literatur nur mit Nutzerquelle oder lizenziertem Live-Zugriff.


<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 25 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `kompendium-01-allgemein-bis-workflow-fristen-und` | immobilienrechtspraxis: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Allgemein, Chronologie Und Belegmatrix, Fristen Und Risikoampel; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätsch... |
| `kompendium-02-workflow-mandantenko-bis-spezial-rechtsprechu` | immobilienrechtspraxis: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Mandantenkommunikation, Redteam Qualitygate, Rechtsprechung Mandantenentscheidung; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmust... |
| `kompendium-03-immo-zwangsversteige-bis-spezial-rechtsabteil` | immobilienrechtspraxis: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Immo Zwangsversteigerung Verfahren, Immobilienrechtspraxis Frist Naechster Schritt, Rechtsabteilungen Fristen Form Und Zustaendigkeit; mit Intake, Prüfro... |
| `kompendium-04-immo-bauvertrag-vob-bis-immo-mietkaufvertrag` | immobilienrechtspraxis: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Immo Bauvertrag Vob B, Immo Kaufvertrag Grundstueck, Immo Mietkaufvertrag; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Q... |
| `kompendium-05-immor-bauvertrag-vob-bis-immor-grundstueckska` | immobilienrechtspraxis: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Immor Bauvertrag Vob Bgb Leitfaden, Immor Erbbaurecht Vertrag Spezial, Immor Grundstueckskaufvertrag Bauleiter; mit Intake, Prüfroutine, Normen-/Quellenr... |
| `kompendium-06-spezial-klauselschut-bis-spezial-vertragsprue` | immobilienrechtspraxis: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Klauselschutz Behoerden Gericht Und Registerweg, Vertragserstellung Risikoampel Und Gegenargumente, Vertragspruefung Schriftsatz Brief Und Memo Bausteine... |
| `kompendium-07-vertragserstellung-m-bis-immo-share-deal-grun` | immobilienrechtspraxis: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Vertragserstellung Musterbasiert, Vertragspruefung Playbook, Immo Share Deal Grunderwerbsteuer; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogi... |
| `kompendium-08-immor-bodenrichtwert-bis-betriebskostenabrech` | immobilienrechtspraxis: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Immor Bodenrichtwert Bewertung Spezial, Betriebskostenabrechnung Erstellen Asset Management, Betriebskostenabrechnung Pruefen Asset Management; mit Intak... |
| `kompendium-09-case-management-bis-immo-aufteilungsplan` | immobilienrechtspraxis: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Case Management, Grundbuchanalyse, Immo Aufteilungsplan Weg; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck. |
| `kompendium-10-immo-bauliche-veraen-bis-immo-gewerbliche-mie` | immobilienrechtspraxis: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Immo Bauliche Veraenderung Weg, Immo Energieausweis, Immo Gewerbliche Mieter Konkurs; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputm... |
| `kompendium-11-immo-grundschuld-bes-bis-immo-wohnungseigentu` | immobilienrechtspraxis: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Immo Grundschuld Bestellung, Immo Makler Honorar, Immo Wohnungseigentum Grundlagen; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmus... |
| `kompendium-12-mieteranfragen-bearb-bis-sachverhaltsermittlu` | immobilienrechtspraxis: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Mieteranfragen Bearbeitung, Projekt Arbeitsweise, Sachverhaltsermittlung; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qu... |
| `kompendium-13-spezial-case-interna-bis-spezial-grundbuchana` | immobilienrechtspraxis: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Case Internationaler Bezug Und Schnittstellen, Gegen Verhandlung Vergleich Und Eskalation, Grundbuchanalyse Zahlen Schwellen Und Berechnung; mit Intake,... |
| `kompendium-14-spezial-immo-abschlu-bis-spezial-live-beweisl` | immobilienrechtspraxis: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Immo Abschlussprodukt Und Uebergabe, Immobilienrechtliche Tatbestand Beweis Und Belege, Live Beweislast Und Darlegungslast; mit Intake, Prüfroutine, Norm... |
| `kompendium-15-spezial-management-f-bis-spezial-musterbasier` | immobilienrechtspraxis: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Management Formular Portal Und Einreichung, Mieteranfragen Mehrparteien Konflikt Und Interessen, Musterbasierte Dokumentenmatrix Und Lueckenliste; mit In... |
| `kompendium-16-spezial-sachverhalts-bis-spezial-werkzeuge-er` | immobilienrechtspraxis: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Sachverhaltsermittlung Compliance Dokumentation Und Akte, Verifikation Sonderfall Und Edge Case, Werkzeuge Erstpruefung Und Mandatsziel; mit Intake, Prüf... |
| `kompendium-17-weg-abrechnung-miete-bis-weg-abrechnung-miete` | immobilienrechtspraxis: eigenständiger Arbeits-Skill zu Weg Abrechnung Mieterschnittstelle Datenpaket; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck. |
| `spezial-playbook-livequellen-und-rechtsprechungscheck` | Playbook: Livequellen- und Rechtsprechungscheck im Plugin immobilienrechtspraxis; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Standardprüfung. |
| `spezial-pruefung-red-team-und-qualitaetskontrolle` | Pruefung: Red-Team und Qualitätskontrolle im Plugin immobilienrechtspraxis; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Standardprüfung. |
| `workflow-anschluss-skills-router` | Anschluss-Skills Router im Plugin immobilienrechtspraxis: schlägt nach der ersten Prüfung die passenden Spezialskills aus demselben Plugin vor. |
| `workflow-dokumentenintake` | Dokumentenintake im Plugin immobilienrechtspraxis: liest Uploads, sortiert Dokumentarten, markiert Fristen und baut eine knappe Arbeitsakte. |
| `workflow-kaltstart-und-routing` | Kaltstart und Routing im Plugin immobilienrechtspraxis: führt vom ersten Satz oder Dokument in den passenden Arbeitsweg, erkennt Rolle, Ziel, Risiko und Anschluss-Skills. |
| `workflow-output-waehlen` | Output wählen im Plugin immobilienrechtspraxis: entscheidet zwischen Memo, Schriftsatz, Tabelle, Brief, Checkliste, Vermerk, Redline oder Mandantenübersetzung. |
| `workflow-rechtsquellen-livecheck` | Rechtsquellen-Livecheck im Plugin immobilienrechtspraxis: zwingt vor tragenden Aussagen zum aktuellen Quellencheck bei Gesetzen, Behörden, Gerichten und Formularen. |
| `workflow-unterlagen-lueckenliste` | Unterlagen- und Lückenliste im Plugin immobilienrechtspraxis: erstellt eine präzise Nachforderungsliste statt allgemeiner Fragebögen. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
