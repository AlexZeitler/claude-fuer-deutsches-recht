# aktenauszug-gerichtsverfahren

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`aktenauszug-gerichtsverfahren`) | [`aktenauszug-gerichtsverfahren.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/aktenauszug-gerichtsverfahren.zip) |

Dieses Plugin hat (bewusst) keine eigene Demonstrations-Akte.

<!-- END plugin-sofort-download-section (autogen) -->

**Version:** 3.2.1
**Autor:** Klotzkette

---

## Installation in Claude Code

1. ZIP herunterladen (Link oben).
2. Claude Code → **Customize Plugins** → **Install from .zip** → Datei wählen.
3. Plugin erscheint in der Plugin-Liste; alle 21 Skills sind sofort verfügbar.
4. Für Updates: neues ZIP herunterladen und Plugin ersetzen.
5. Hinweis: Das Plugin-ZIP muss direkt `.claude-plugin/plugin.json`, `skills/` und `references/` im ZIP-Root enthalten — nicht das komplette Repository-ZIP aus "Code → Download ZIP" verwenden.

## Überblick

Das Plugin `aktenauszug-gerichtsverfahren` generiert strukturierte Aktenauszüge für deutsche Gerichtsverfahren. Es richtet sich an Rechtsanwältinnen und Rechtsanwälte, die sich schnell in ein neues oder übernommenes Mandat einarbeiten müssen.

**Einsatzgebiete:**

- Mandatswechsel und Übernahme von laufenden Verfahren
- Einarbeitung neuer Sachbearbeiter in komplexe Akten
- Vorbereitung auf mündliche Verhandlungen
- Strukturierung umfangreicher Akten vor Beratungsgesprächen
- Erstellung von Mandantenberichten zum Verfahrensstand

**Verfahrensarten:**

- Zivilverfahren (ZPO) inkl. Berufung, Revision, einstweilige Verfügung
- Strafverfahren (StPO) inkl. Revision und Wiederaufnahme
- Verwaltungsverfahren (VwGO) inkl. Berufung und Revision
- Arbeitsgerichtsverfahren (ArbGG) inkl. Urteilsverfahren und Beschlussverfahren
- Sozialgerichtsverfahren (SGG) inkl. Berufung und Eilrechtsschutz

## Skills-Übersicht

| Skill | Zweck |
| --- | --- |
| `aktenauszug-erstellen` | Hauptworkflow: erzeugt alle sechs Bausteine des strukturierten Aktenauszugs aus PDFs und Schriftsätzen |
| `verfahrensidentifikation` | Extrahiert Gericht Kammer Aktenzeichen Streitwert Parteien Instanz und Verfahrensart |
| `einleitungssatz-generator` | Verfasst einen prägnanten ein- bis zweiSatz-Kern des Rechtsstreits mit Hauptnorm |
| `verfahrenszusammenfassung-absatz` | Schreibt zusammenfassenden Absatz mit acht bis zehn Sätzen zu Hintergrund Streitstand prozessualer Lage und nächsten Schritten |
| `sachverhaltschronologie` | Chronologische Bullet-Liste aller wesentlichen außerprozessualen Tatsachen mit Datum und Fundstelle |
| `verfahrenschronologie` | Chronologische Bullet-Liste aller prozessualen Schritte mit hervorgehobenen Fristen |
| `parteivortrag-gegenueberstellung` | Tabelle mit Kläger- und Beklagtenposition zu jedem Streitpunkt |
| `beweismittel-gegenueberstellung` | Tabelle aller Beweisangebote (Zeugen Urkunden Sachverständige) nach Partei und Beweisthema |
| `rechtsargumente-gegenueberstellung` | Tabelle der Rechtsargumente beider Parteien mit Anspruchsgrundlagen Einwendungen Einreden und Rechtsprechungsnachweisen |
| `fristen-und-terminkalender` | Identifiziert und hebt alle prozessrelevanten Fristen und Termine hervor |
| `anlagenverzeichnis-extrakt` | Vollständiges Anlagenverzeichnis aller K-/B-Anlagen mit Inhalt und Fundstelle |
| `schwerpunktthemen-identifikation` | Identifiziert drei bis fünf zentrale Rechtsfragen ohne Erfolgsprognose |
| `neutralitaetspruefung` | Prüft den Aktenauszug auf unzulässige Wertungen und Prognosen und schlägt Korrekturen vor |
| `aktenauszug-strukturpruefung` | Vollständigkeitsprüfung aller sechs Bausteine und Qualitätsgrundsätze |
| `zivilprozess-modus` | ZPO-spezifische Einstellungen für ordentliche Klage Berufung Revision und einstweilige Verfügung |
| `strafprozess-modus` | StPO-spezifische Einstellungen für Anklageverfahren Hauptverhandlung und Revision |
| `verwaltungsprozess-modus` | VwGO-spezifische Einstellungen mit Vorverfahren aufschiebender Wirkung und Berufungszulassung |
| `arbeitsgerichtsverfahren-modus` | ArbGG-spezifische Einstellungen mit Gütetermin KSchG-Dreiwochenfrist und Beschlussverfahren |
| `sozialgerichtsverfahren-modus` | SGG-spezifische Einstellungen mit Widerspruchsverfahren Amtsermittlung und Eilrechtsschutz |
| `anwaltsschriftsatz-stilrichtlinie` | Verbindliche Stilregeln für Sprache Gliederung Nomenklatur und Markdown-Formatierung |

## Methodik

Ausführliche Erläuterung der Methodik unter [references/methodik.md](references/methodik.md).

- Quellenregel: Literatur nur mit Nutzerquelle oder lizenziertem Live-Zugriff; keine Kommentar-, Handbuch- oder Aufsatzfundstellen aus Modellwissen.

## Beispielprompt

```
Erstelle einen strukturierten Aktenauszug für das anhängende Verfahren vor dem Landgericht Frankfurt am Main (Az. 3 O 456/23). Die Akte enthält Klageschrift, Klageerwiderung und den Beweisbeschluss vom 15.09.2023. Verwende den Zivilprozess-Modus.
```

## Disclaimer

Dieses Plugin erstellt keine Rechtsberatung und gibt keine Erfolgsprognose ab. Die erstellten Aktenauszüge sind Arbeitsinstrumente, die der Prüfung und Freigabe durch den zuständigen Rechtsanwalt bedürfen. Das Plugin ersetzt nicht die eigene Aktenlektüre.

## Lizenz

Apache-2.0 OR MIT — Auswahl beim Empfänger.


<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 24 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `aktenauszug-strukturpruefung-akzg-bauleiter-vertraulichkeit` | Aktenauszug Strukturpruefung, Akzg Aktenauszug Bauleiter, Akzg Vertraulichkeit Redaction Spezial: Aktenauszug Strukturpruefung; Akzg Aktenauszug Bauleiter; Akzg Vertraulichkeit Redaction Spezial. Führt Intake, Prüfroutine, Normen-/Quelle... |
| `akzg-zeitstrahl-anlagenverzeichnis-extrakt-anwaltsschriftsatz` | Akzg Zeitstrahl Checkliste, Anlagenverzeichnis Extrakt, Anwaltsschriftsatz Stilrichtlinie: Akzg Zeitstrahl Checkliste; Anlagenverzeichnis Extrakt; Anwaltsschriftsatz Stilrichtlinie. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweis... |
| `allgemein-workflow-chronologie-workflow-fristen` | Allgemein, Workflow Chronologie Und Belegmatrix, Workflow Fristen Und Risikoampel: Allgemein; Workflow Chronologie Und Belegmatrix; Workflow Fristen Und Risikoampel. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmus... |
| `anwaltsschriftsatz-beweislast-beweismittel-interessen` | Spezial Anwaltsschriftsatz Beweislast Und Darlegungslast, Spezial Beweismittel Mehrparteien Konflikt Und Interessen, Spezial Einleitungssatz Risikoampel Und Gegenargumente: Spezial Anwaltsschriftsatz Beweislast Und Darlegungslast; Spezia... |
| `arbeitsgerichtsverfahren-modus-terminkalender` | Arbeitsgerichtsverfahren Modus, Fristen Und Terminkalender, Sozialgerichtsverfahren Modus: Arbeitsgerichtsverfahren Modus; Fristen Und Terminkalender; Sozialgerichtsverfahren Modus. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweis... |
| `beweismittel-gegenueberstellung-einleitungssatz-generator` | Beweismittel Gegenueberstellung, Einleitungssatz Generator, Neutralitaetspruefung: Beweismittel Gegenueberstellung; Einleitungssatz Generator; Neutralitaetspruefung. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmus... |
| `erstellen-fristennotiz-gerichtsverfahren-verfahrensgeschichte` | Spezial Erstellen Fristennotiz Und Naechster Schritt, Spezial Gerichtsverfahren Fristen Form Und Zustaendigkeit, Spezial Verfahrensgeschichte Vergleich Eskalation: Spezial Erstellen Fristennotiz Und Naechster Schritt; Spezial Gerichtsver... |
| `gegenueberstellung-parteivortraege-rechtsargumente` | Spezial Gegenueberstellung Zahlen Schwellen Und Berechnung, Spezial Parteivortraege Compliance Dokumentation Und Akte, Spezial Rechtsargumente Internationaler Bezug Und Schnittstellen: Spezial Gegenueberstellung Zahlen Schwellen Und Bere... |
| `parteivortrag-gegenueberstellung-rechtsargumente` | Parteivortrag Gegenueberstellung, Rechtsargumente Gegenueberstellung, Sachverhaltschronologie: Parteivortrag Gegenueberstellung; Rechtsargumente Gegenueberstellung; Sachverhaltschronologie. Führt Intake, Prüfroutine, Normen-/Quellenradar... |
| `sachverhaltschronologie-textbausteine-schnelle-stilrichtlinie` | Spezial Sachverhaltschronologie Textbausteine, Spezial Schnelle Formular Portal Und Einreichung, Spezial Stilrichtlinie Sonderfall Und Edge Case: Spezial Sachverhaltschronologie Textbausteine; Spezial Schnelle Formular Portal Und Einreic... |
| `schwerpunktthemen-identifikation-akten-aktenauszug` | Schwerpunktthemen Identifikation, Spezial Akten Mandantenkommunikation Entscheidungsvorlage, Spezial Aktenauszug Tatbestand Beweis Und Belege: Schwerpunktthemen Identifikation; Spezial Akten Mandantenkommunikation Entscheidungsvorlage; S... |
| `spezial-einarbeitung-red-team-und-qualitaetskontrolle` | Einarbeitung: Red-Team und Qualitätskontrolle im Plugin aktenauszug gerichtsverfahren; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Standardprüfung. |
| `spezial-tabellarische-livequellen-und-rechtsprechungscheck` | Tabellarische: Livequellen- und Rechtsprechungscheck im Plugin aktenauszug gerichtsverfahren; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Standardprüfung. |
| `strukturierter-strafprozess-modus-verwaltungsprozess-modus` | Spezial Strukturierter Erstpruefung Und Mandatsziel, Strafprozess Modus, Verwaltungsprozess Modus: Spezial Strukturierter Erstpruefung Und Mandatsziel; Strafprozess Modus; Verwaltungsprozess Modus. Führt Intake, Prüfroutine, Normen-/Quel... |
| `verfahrensidentifikation-verfahrenszusammenfassung-absatz` | Verfahrensidentifikation, Verfahrenszusammenfassung Absatz, Aktenauszug Erstellen: Verfahrensidentifikation; Verfahrenszusammenfassung Absatz; Aktenauszug Erstellen. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmus... |
| `verfahrensidentifikation-verfahrenszusammenfassung-rechtsweg` | Spezial Verfahrensidentifikation Dokumentenmatrix, Spezial Verfahrenszusammenfassung Rechtsweg Register, Verfahrenschronologie: Spezial Verfahrensidentifikation Dokumentenmatrix; Spezial Verfahrenszusammenfassung Rechtsweg Register; Verf... |
| `workflow-anschluss-skills-router` | Anschluss-Skills Router im Plugin aktenauszug-gerichtsverfahren: schlägt nach der ersten Prüfung die passenden Spezialskills aus demselben Plugin vor. |
| `workflow-dokumentenintake` | Dokumentenintake im Plugin aktenauszug-gerichtsverfahren: liest Uploads, sortiert Dokumentarten, markiert Fristen und baut eine knappe Arbeitsakte. |
| `workflow-kaltstart-und-routing` | Kaltstart und Routing im Plugin aktenauszug-gerichtsverfahren: führt vom ersten Satz oder Dokument in den passenden Arbeitsweg, erkennt Rolle, Ziel, Risiko und Anschluss-Skills. |
| `workflow-mandantenkommunikation-workflow-redteam-akzg` | Workflow Mandantenkommunikation, Workflow Redteam Qualitygate, Akzg Multiparteienverfahren Konsolidierung Spezial: Workflow Mandantenkommunikation; Workflow Redteam Qualitygate; Akzg Multiparteienverfahren Konsolidierung Spezial. Führt I... |
| `workflow-output-waehlen` | Output wählen im Plugin aktenauszug-gerichtsverfahren: entscheidet zwischen Memo, Schriftsatz, Tabelle, Brief, Checkliste, Vermerk, Redline oder Mandantenübersetzung. |
| `workflow-rechtsquellen-livecheck` | Rechtsquellen-Livecheck im Plugin aktenauszug-gerichtsverfahren: zwingt vor tragenden Aussagen zum aktuellen Quellencheck bei Gesetzen, Behörden, Gerichten und Formularen. |
| `workflow-unterlagen-lueckenliste` | Unterlagen- und Lückenliste im Plugin aktenauszug-gerichtsverfahren: erstellt eine präzise Nachforderungsliste statt allgemeiner Fragebögen. |
| `zivilprozess-modus` | Zivilprozess Modus: Zivilprozess Modus. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zusammen. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
