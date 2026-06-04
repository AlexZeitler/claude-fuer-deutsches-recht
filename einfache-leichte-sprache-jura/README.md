# Einfache und Leichte Sprache für juristische Texte

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`einfache-leichte-sprache-jura`) | [`einfache-leichte-sprache-jura.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/einfache-leichte-sprache-jura.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **Juristischer Mandantenbrief in Einfacher und Leichter Sprache** (`einfache-leichte-sprache-jura-mandantenbrief`) | [Gesamt-PDF lesen](../testakten/einfache-leichte-sprache-jura-mandantenbrief/gesamt-pdf/einfache-leichte-sprache-jura-mandantenbrief_gesamt.pdf) | [`testakte-einfache-leichte-sprache-jura-mandantenbrief.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-einfache-leichte-sprache-jura-mandantenbrief.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

Freistehendes Plugin für die Übertragung juristischer Texte in **Einfache
Sprache** oder **Leichte Sprache**. Es richtet sich an Kanzleien, Behörden,
Beratungsstellen, Legal-Design-Teams und alle, die rechtliche Informationen
verständlich, respektvoll und rechtlich belastbar erklären müssen.

## Showcase-Hinweis

Dieses Plugin ist ein Experiment und ein Showcase. Es ist ein Versuch, sich der
Ergebnisrichtung von Einfacher Sprache und Leichter Sprache anzunähern, ohne
eine Standardprüfung oder Konformitätsaussage zu behaupten. Make of this what
you will, dear users: Ihr müsst selbst beurteilen, ob Verfahren, Sprache und
Ergebnis für eure Zielgruppe, euer Medium und euren Rechtstext passen. You are
on your own.

## Zwei Modi

| Modus | Ziel |
| --- | --- |
| Einfache Sprache | Standardsprache bleibt erkennbar. Fachsprache wird erklärt. Der Text wird klarer, kürzer, besser gegliedert und zielgruppenorientiert. |
| Leichte Sprache | Deutlich stärkere Vereinfachung. Kurze Sätze, klare Zeilen, viel Orientierung, erklärtes Fachwort, möglichst eine Aussage pro Satz. Eine Prüfung durch Personen aus der Zielgruppe wird empfohlen. |

## Workflow

1. Ausgangstext hochladen oder einfügen.
2. Zielgruppe, Anlass, Medium und gewünschte Tiefe klären.
3. Juristische Bedeutungen sichern: Rechte, Pflichten, Fristen, Beträge,
   Rechtsfolgen, Zuständigkeiten und Handlungsoptionen.
4. Modus wählen: Einfache Sprache oder Leichte Sprache.
5. Übertragung erstellen.
6. Glossar und Warnhinweise ergänzen.
7. Qualitätsgate laufen lassen.
8. Bei Leichter Sprache: Nutzerprüfung als offenen Schritt markieren, wenn sie
   nicht tatsächlich erfolgt ist.

## Enthaltene Skills

| Skill | Zweck |
| --- | --- |
| `elsj-kommandocenter` | steuert Intake, Moduswahl, Zielgruppe, Rechtsinhalt und Ausgabeformat |
| `elsj-einfache-sprache` | überträgt juristische Texte in Einfache Sprache |
| `elsj-leichte-sprache` | überträgt juristische Texte in Leichte Sprache |
| `elsj-juristische-sicherung` | verhindert Bedeutungsverlust bei Rechten, Pflichten, Fristen und Rechtsfolgen |
| `elsj-qualitaetsgate` | prüft Verständlichkeit, Struktur, Glossar, Ton und rechtliche Vollständigkeit |

## Hilfsskript

```bash
python einfache-leichte-sprache-jura/scripts/verstaendlichkeitscheck.py \
  testakten/einfache-leichte-sprache-jura-mandantenbrief/02_einfache_sprache.md \
  --mode einfache
```

Das Skript ist kein Normprüfer. Es findet typische Warnsignale:
lange Sätze, sehr lange Wörter, Passiv-Kandidaten, Nominalstil und fehlende
Orientierungselemente.

<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 24 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `kompendium-01-allgemein-bis-workflow-chronologie` | einfache-leichte-sprache-jura: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Allgemein, Ls Bescheid Uebersetzen Workflow, Chronologie Und Belegmatrix; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster... |
| `kompendium-02-workflow-fristen-und-bis-workflow-redteam-qua` | einfache-leichte-sprache-jura: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Fristen Und Risikoampel, Mandantenkommunikation, Redteam Qualitygate; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und... |
| `kompendium-03-elsj-sozialgerichtsv-bis-spezial-bauen-friste` | einfache-leichte-sprache-jura: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Elsj Sozialgerichtsverfahren, Elsj Strafverfahren Beschuldigter, Bauen Fristennotiz Und Naechster Schritt; mit Intake, Prüfroutine, Normen-/Quelle... |
| `kompendium-04-spezial-einfache-fri-bis-elsj-kommandocenter` | einfache-leichte-sprache-jura: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Einfache Fristen Form Und Zustaendigkeit, Elsj Bescheidmodus, Elsj Kommandocenter; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Out... |
| `kompendium-05-elsj-aufenthaltsrech-bis-elsj-einfache-sprach` | einfache-leichte-sprache-jura: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Elsj Aufenthaltsrecht Mandant, Elsj Betreuung Vormundschaft, Elsj Einfache Sprache; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Ou... |
| `kompendium-06-elsj-familienrecht-e-bis-elsj-kommunikation-m` | einfache-leichte-sprache-jura: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Elsj Familienrecht Erstgespraech, Elsj Juristische Sicherung, Elsj Kommunikation Mandant; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislog... |
| `kompendium-07-elsj-leichte-sprache-bis-elsj-pruefkriterien` | einfache-leichte-sprache-jura: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Elsj Leichte Sprache, Elsj Mietrecht Kuendigungserklaerung, Elsj Pruefkriterien Fuer Qualitaet; mit Intake, Prüfroutine, Normen-/Quellenradar, Bew... |
| `kompendium-08-elsj-qualitaetsgate-bis-elsj-satzbau-regeln` | einfache-leichte-sprache-jura: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Elsj Qualitaetsgate, Elsj Rechtsnormen Einfach, Elsj Satzbau Regeln; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und... |
| `kompendium-09-elsj-uebersetzungsab-bis-elsj-zielgruppen-erk` | einfache-leichte-sprache-jura: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Elsj Uebersetzungsablauf, Elsj Wortebene Haus Glossar, Elsj Zielgruppen Erkennen; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outp... |
| `kompendium-10-ls-juristisches-glos-bis-ls-strafprozess-rech` | einfache-leichte-sprache-jura: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Ls Juristisches Glossar Bauen, Ls Justizportal Pruefen Spezial, Ls Strafprozess Rechte Erklaeren Spezial; mit Intake, Prüfroutine, Normen-/Quellen... |
| `kompendium-11-spezial-experimentel-bis-spezial-jura-mandant` | einfache-leichte-sprache-jura: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Experimentelle Schriftsatz Brief Und Memo Bausteine, Glossar Sonderfall Und Edge Case, Jura Mandantenkommunikation Entscheidungsvorlage; mit Intak... |
| `kompendium-12-spezial-juristische-bis-spezial-klaeren-comp` | einfache-leichte-sprache-jura: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Juristische Erstpruefung Und Mandatsziel, Juristisches Beweislast Und Darlegungslast, Klaeren Compliance Dokumentation Und Akte; mit Intake, Prüfr... |
| `kompendium-13-spezial-leichte-risi-bis-spezial-rechtsinhalt` | einfache-leichte-sprache-jura: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Leichte Risikoampel Und Gegenargumente, Qualitaetsgate Formular Portal Und Einreichung, Rechtsinhalt Mehrparteien Konflikt Und Interessen; mit Int... |
| `kompendium-14-spezial-sichern-inte-bis-spezial-standard-ver` | einfache-leichte-sprache-jura: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Sichern Internationaler Bezug Und Schnittstellen, Sprache Dokumentenmatrix Und Lueckenliste, Standard Verhandlung Vergleich Und Eskalation; mit In... |
| `kompendium-15-spezial-texte-tatbes-bis-spezial-zielgruppe-s` | einfache-leichte-sprache-jura: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Texte Tatbestand Beweis Und Belege, Uebertragen Behoerden Gericht Und Registerweg, Zielgruppe Sprachniveau Rechtsinhalt; mit Intake, Prüfroutine,... |
| `kompendium-16-spezial-zielgruppe-z-bis-spezial-zielgruppe-z` | einfache-leichte-sprache-jura: eigenständiger Arbeits-Skill zu Zielgruppe Zahlen Schwellen Und Berechnung; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck. |
| `spezial-annaeherung-livequellen-und-rechtsprechungscheck` | Annaeherung: Livequellen- und Rechtsprechungscheck im Plugin einfache leichte sprache jura; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Standardprüfung. |
| `spezial-nutzen-red-team-und-qualitaetskontrolle` | Nutzen: Red-Team und Qualitätskontrolle im Plugin einfache leichte sprache jura; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Standardprüfung. |
| `workflow-anschluss-skills-router` | Anschluss-Skills Router im Plugin einfache-leichte-sprache-jura: schlägt nach der ersten Prüfung die passenden Spezialskills aus demselben Plugin vor. |
| `workflow-dokumentenintake` | Dokumentenintake im Plugin einfache-leichte-sprache-jura: liest Uploads, sortiert Dokumentarten, markiert Fristen und baut eine knappe Arbeitsakte. |
| `workflow-kaltstart-und-routing` | Kaltstart und Routing im Plugin einfache-leichte-sprache-jura: führt vom ersten Satz oder Dokument in den passenden Arbeitsweg, erkennt Rolle, Ziel, Risiko und Anschluss-Skills. |
| `workflow-output-waehlen` | Output wählen im Plugin einfache-leichte-sprache-jura: entscheidet zwischen Memo, Schriftsatz, Tabelle, Brief, Checkliste, Vermerk, Redline oder Mandantenübersetzung. |
| `workflow-rechtsquellen-livecheck` | Rechtsquellen-Livecheck im Plugin einfache-leichte-sprache-jura: zwingt vor tragenden Aussagen zum aktuellen Quellencheck bei Gesetzen, Behörden, Gerichten und Formularen. |
| `workflow-unterlagen-lueckenliste` | Unterlagen- und Lückenliste im Plugin einfache-leichte-sprache-jura: erstellt eine präzise Nachforderungsliste statt allgemeiner Fragebögen. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
