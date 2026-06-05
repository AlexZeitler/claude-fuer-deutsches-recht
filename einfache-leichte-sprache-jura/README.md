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
| `allgemein-ls-bescheid-workflow-chronologie` | Allgemein, Ls Bescheid Uebersetzen Workflow, Workflow Chronologie Und Belegmatrix: Allgemein; Ls Bescheid Uebersetzen Workflow; Workflow Chronologie Und Belegmatrix. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmus... |
| `einfache-elsj-bescheidmodus-elsj` | Spezial Einfache Fristen Form Und Zustaendigkeit, Elsj Bescheidmodus, Elsj Kommandocenter: Spezial Einfache Fristen Form Und Zustaendigkeit; Elsj Bescheidmodus; Elsj Kommandocenter. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweis... |
| `elsj-aufenthaltsrecht-mandant-betreuung-vormundschaft-einfache` | Elsj Aufenthaltsrecht Mandant, Elsj Betreuung Vormundschaft, Elsj Einfache Sprache: Elsj Aufenthaltsrecht Mandant; Elsj Betreuung Vormundschaft; Elsj Einfache Sprache. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputm... |
| `elsj-familienrecht-erstgespraech-juristische-sicherung` | Elsj Familienrecht Erstgespraech, Elsj Juristische Sicherung, Elsj Kommunikation Mandant: Elsj Familienrecht Erstgespraech; Elsj Juristische Sicherung; Elsj Kommunikation Mandant. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislo... |
| `elsj-leichte-sprache-mietrecht-kuendigungserklaerung` | Elsj Leichte Sprache, Elsj Mietrecht Kuendigungserklaerung, Elsj Pruefkriterien Für Qualitaet: Elsj Leichte Sprache; Elsj Mietrecht Kuendigungserklaerung; Elsj Pruefkriterien Für Qualitaet. Führt Intake, Prüfroutine, Normen-/Quellenradar... |
| `elsj-qualitaetsgate-rechtsnormen-einfach-satzbau-regeln` | Elsj Qualitaetsgate, Elsj Rechtsnormen Einfach, Elsj Satzbau Regeln: Elsj Qualitaetsgate; Elsj Rechtsnormen Einfach; Elsj Satzbau Regeln. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zusam... |
| `elsj-sozialgerichtsverfahren-elsj-strafverfahren-bauen` | Elsj Sozialgerichtsverfahren, Elsj Strafverfahren Beschuldigter, Spezial Bauen Fristennotiz Und Naechster Schritt: Elsj Sozialgerichtsverfahren; Elsj Strafverfahren Beschuldigter; Spezial Bauen Fristennotiz Und Naechster Schritt. Führt I... |
| `elsj-uebersetzungsablauf-wortebene-haus-zielgruppen-erkennen` | Elsj Uebersetzungsablauf, Elsj Wortebene Haus Glossar, Elsj Zielgruppen Erkennen: Elsj Uebersetzungsablauf; Elsj Wortebene Haus Glossar; Elsj Zielgruppen Erkennen. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuste... |
| `experimentelle-glossar-sonderfall-jura` | Spezial Experimentelle Schriftsatz Brief Und Memo Bausteine, Spezial Glossar Sonderfall Und Edge Case, Spezial Jura Mandantenkommunikation Entscheidungsvorlage: Spezial Experimentelle Schriftsatz Brief Und Memo Bausteine; Spezial Glossar... |
| `juristische-juristisches-beweislast-klaeren` | Spezial Juristische Erstpruefung Und Mandatsziel, Spezial Juristisches Beweislast Und Darlegungslast, Spezial Klaeren Compliance Dokumentation Und Akte: Spezial Juristische Erstpruefung Und Mandatsziel; Spezial Juristisches Beweislast Un... |
| `leichte-qualitaetsgate-rechtsinhalt-interessen` | Spezial Leichte Risikoampel Und Gegenargumente, Spezial Qualitaetsgate Formular Portal Und Einreichung, Spezial Rechtsinhalt Mehrparteien Konflikt Und Interessen: Spezial Leichte Risikoampel Und Gegenargumente; Spezial Qualitaetsgate For... |
| `ls-juristisches-ls-justizportal-ls-strafprozess` | Ls Juristisches Glossar Bauen, Ls Justizportal Prüfen Spezial, Ls Strafprozess Rechte Erklaeren Spezial: Ls Juristisches Glossar Bauen; Ls Justizportal Prüfen Spezial; Ls Strafprozess Rechte Erklaeren Spezial. Führt Intake, Prüfroutine,... |
| `sichern-sprache-standard` | Spezial Sichern Internationaler Bezug Und Schnittstellen, Spezial Sprache Dokumentenmatrix Und Lueckenliste, Spezial Standard Verhandlung Vergleich Und Eskalation: Spezial Sichern Internationaler Bezug Und Schnittstellen; Spezial Sprache... |
| `spezial-annaeherung-livequellen-und-rechtsprechungscheck` | Annaeherung: Livequellen- und Rechtsprechungscheck im Plugin einfache leichte sprache jura; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Standardprüfung. |
| `spezial-nutzen-red-team-und-qualitaetskontrolle` | Nutzen: Red-Team und Qualitätskontrolle im Plugin einfache leichte sprache jura; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Standardprüfung. |
| `texte-uebertragen-zielgruppe-sprachniveau` | Spezial Texte Tatbestand Beweis Und Belege, Spezial Uebertragen Behörden Gericht Und Registerweg, Spezial Zielgruppe Sprachniveau Rechtsinhalt: Spezial Texte Tatbestand Beweis Und Belege; Spezial Uebertragen Behörden Gericht Und Register... |
| `workflow-anschluss-skills-router` | Anschluss-Skills Router im Plugin einfache-leichte-sprache-jura: schlägt nach der ersten Prüfung die passenden Spezialskills aus demselben Plugin vor. |
| `workflow-dokumentenintake` | Dokumentenintake im Plugin einfache-leichte-sprache-jura: liest Uploads, sortiert Dokumentarten, markiert Fristen und baut eine knappe Arbeitsakte. |
| `workflow-fristen-risikoampel-mandantenkommunikation-redteam` | Workflow Fristen Und Risikoampel, Workflow Mandantenkommunikation, Workflow Redteam Qualitygate: Workflow Fristen Und Risikoampel; Workflow Mandantenkommunikation; Workflow Redteam Qualitygate. Führt Intake, Prüfroutine, Normen-/Quellenr... |
| `workflow-kaltstart-und-routing` | Kaltstart und Routing im Plugin einfache-leichte-sprache-jura: führt vom ersten Satz oder Dokument in den passenden Arbeitsweg, erkennt Rolle, Ziel, Risiko und Anschluss-Skills. |
| `workflow-output-waehlen` | Output wählen im Plugin einfache-leichte-sprache-jura: entscheidet zwischen Memo, Schriftsatz, Tabelle, Brief, Checkliste, Vermerk, Redline oder Mandantenübersetzung. |
| `workflow-rechtsquellen-livecheck` | Rechtsquellen-Livecheck im Plugin einfache-leichte-sprache-jura: zwingt vor tragenden Aussagen zum aktuellen Quellencheck bei Gesetzen, Behörden, Gerichten und Formularen. |
| `workflow-unterlagen-lueckenliste` | Unterlagen- und Lückenliste im Plugin einfache-leichte-sprache-jura: erstellt eine präzise Nachforderungsliste statt allgemeiner Fragebögen. |
| `zielgruppe` | Spezial Zielgruppe Zahlen Schwellen Und Berechnung: Spezial Zielgruppe Zahlen Schwellen Und Berechnung. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zusammen. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
