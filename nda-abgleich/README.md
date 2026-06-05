# NDA-Abgleich

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`nda-abgleich`) | [`nda-abgleich.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/nda-abgleich.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **Akte Waldkrone HealthTech GmbH - NDA, Meldekanal und Lieferantenhinweis** (`hinweisgeberschutz-nda-meldekanal-waldkrone`) | [Gesamt-PDF lesen](../testakten/hinweisgeberschutz-nda-meldekanal-waldkrone/gesamt-pdf/hinweisgeberschutz-nda-meldekanal-waldkrone_gesamt.pdf) | [`testakte-hinweisgeberschutz-nda-meldekanal-waldkrone.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-hinweisgeberschutz-nda-meldekanal-waldkrone.zip) |
| **NDA-Vertragsabgleich Windsysteme Norderhof AG / Eickmann Wirtschaftspartner Pte. Ltd. — Joint Venture, GeschGehG, Exportkontrolle** (`nda-vertragsabgleich-jointventure-windsysteme-eickmann-wirtschaft`) | [Gesamt-PDF lesen](../testakten/nda-vertragsabgleich-jointventure-windsysteme-eickmann-wirtschaft/gesamt-pdf/nda-vertragsabgleich-jointventure-windsysteme-eickmann-wirtschaft_gesamt.pdf) | [`testakte-nda-vertragsabgleich-jointventure-windsysteme-eickmann-wirtschaft.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-nda-vertragsabgleich-jointventure-windsysteme-eickmann-wirtschaft.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

NDA-Verhandlungshilfe für die empfangende Seite. Akzeptiert den Entwurf der Gegenseite und setzt den eigenen Standard chirurgisch durch. Ampelmatrix ROT/GELB/GRUEN. Ausgabe .docx mit echten Word-Tracked-Changes. Keine Absatzlöschungen, keine Klausel-Neufassungen.

## Installation in Claude Code

1. ZIP herunterladen (Link oben).
2. Claude Code → **Customize Plugins** → **Install from .zip** → Datei wählen.
3. Fertig. Skills sind sofort verfügbar.

> **Hinweis:** Für den ZIP-Upload muss das Archiv direkt `.claude-plugin/plugin.json`, `skills/`, `assets/` und `references/` im ZIP-Root enthalten. **Nicht** das komplette Repository-ZIP aus "Code → Download ZIP" verwenden.

## Enthaltene Skills

| Skill | Zweck |
| --- | --- |
| `nda-abgleich` | NDA-Verhandlungshilfe für die empfangende Seite. Zwei Modi: (A) Standard-Destillation aus 1 bis n eigenen NDAs und frei beschreibbarer Erfahrung in einen konsolidierten Haltelinien-Standard mit Ampelmatrix ROT/GELB/G… |

## Lizenz

Apache-2.0 OR MIT — Auswahl beim Empfänger.

## Quellen-Disclaimer

Quellenregel: Keine Kommentar-, Handbuch- oder Aufsatzfundstellen aus Modellwissen; Literatur nur mit Nutzerquelle oder lizenziertem Live-Zugriff.


<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 24 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `allgemein-workflow-chronologie-workflow-fristen` | Allgemein, Workflow Chronologie Und Belegmatrix, Workflow Fristen Und Risikoampel: Allgemein; Workflow Chronologie Und Belegmatrix; Workflow Fristen Und Risikoampel. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmus... |
| `ausgabe-changes-docx-beweislast` | Spezial Ausgabe Mandantenkommunikation Entscheidungsvorlage, Spezial Changes Abschlussprodukt Und Übergabe, Spezial Docx Beweislast Und Darlegungslast: Spezial Ausgabe Mandantenkommunikation Entscheidungsvorlage; Spezial Changes Abschlus... |
| `durch-interessen-echten-sonderfall-eigenen` | Spezial Durch Mehrparteien Konflikt Und Interessen, Spezial Echten Sonderfall Und Edge Case, Spezial Eigenen Risikoampel Und Gegenargumente: Spezial Durch Mehrparteien Konflikt Und Interessen; Spezial Echten Sonderfall Und Edge Case; Spe... |
| `gegen-gelb-gleicht` | Spezial Gegen Dokumentenmatrix Und Lueckenliste, Spezial Gelb Formular Portal Und Einreichung, Spezial Gleicht Erstpruefung Und Mandatsziel: Spezial Gegen Dokumentenmatrix Und Lueckenliste; Spezial Gelb Formular Portal Und Einreichung; S... |
| `gegenseite-tracked-fristennotiz-nda-definitionsklausel` | Spezial Gegenseite Fristen Form Und Zustaendigkeit, Spezial Tracked Fristennotiz Und Naechster Schritt, Nda Definitionsklausel Abgleichen: Spezial Gegenseite Fristen Form Und Zustaendigkeit; Spezial Tracked Fristennotiz Und Naechster Sch... |
| `geschaeftsgeheimnis-geschgehg-kartellsensitiven-daten` | Nda Mit Geschaeftsgeheimnis Geschgehg, Nda Mit Kartellsensitiven Daten, Nda Mit Personenbezogenen Daten: Nda Mit Geschaeftsgeheimnis Geschgehg; Nda Mit Kartellsensitiven Daten; Nda Mit Personenbezogenen Daten. Führt Intake, Prüfroutine,... |
| `haltelinien-setzt-standard` | Spezial Haltelinien Verhandlung Vergleich Und Eskalation, Spezial Setzt Schriftsatz Brief Und Memo Bausteine, Spezial Standard Behörden Gericht Und Registerweg: Spezial Haltelinien Verhandlung Vergleich Und Eskalation; Spezial Setzt Schr... |
| `it-saas-laufzeit-survival-m-a` | Nda It Saas Vendor, Nda Laufzeit Und Survival, Nda M Und A Clean Team Spezial: Nda It Saas Vendor; Nda Laufzeit Und Survival; Nda M Und A Clean Team Spezial. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und... |
| `m-a-aenderungsmodus-ampelmatrix` | Nda Vor M A Data Room, Spezial Aenderungsmodus Compliance Dokumentation Und Akte, Spezial Ampelmatrix Internationaler Bezug Und Schnittstellen: Nda Vor M A Data Room; Spezial Aenderungsmodus Compliance Dokumentation Und Akte; Spezial Amp... |
| `mitarbeiter-need-non-solicit-permitted-disclosure` | Nda Mitarbeiter Need To Know, Nda Non Solicit Kartellrechtlich, Nda Permitted Disclosure: Nda Mitarbeiter Need To Know; Nda Non Solicit Kartellrechtlich; Nda Permitted Disclosure. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislo... |
| `nda-abgleich-arbeitnehmer-kuendigung-bewerbungen-pitches` | Nda Abgleich, Nda Bei Arbeitnehmer Kündigung, Nda Bei Bewerbungen Pitches: Nda Abgleich; Nda Bei Arbeitnehmer Kündigung; Nda Bei Bewerbungen Pitches. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualität... |
| `r-d-nda-grundstruktur-international-arbitration` | Nda Bei R D Kooperation, Nda Grundstruktur Prüfen, Nda International Arbitration Spezial: Nda Bei R D Kooperation; Nda Grundstruktur Prüfen; Nda International Arbitration Spezial. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislo... |
| `rueckgabe-vernichtung-nda-typen-vergleichsmatrix-leitfaden` | Nda Rueckgabe Vernichtung, Nda Typen Vergleich, Nda Vergleichsmatrix Leitfaden: Nda Rueckgabe Vernichtung; Nda Typen Vergleich; Nda Vergleichsmatrix Leitfaden. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster un... |
| `spezial-chirurgisch-livequellen-und-rechtsprechungscheck` | Chirurgisch: Livequellen- und Rechtsprechungscheck im Plugin nda abgleich; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Standardprüfung. |
| `spezial-gruen-red-team-und-qualitaetskontrolle` | Gruen: Red-Team und Qualitätskontrolle im Plugin nda abgleich; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Standardprüfung. |
| `standardklauseln-bauleiter-nda-vertragsstrafe-entwurf` | Nda Standardklauseln Bauleiter, Nda Vertragsstrafe Prüfen, Spezial Entwurf Tatbestand Beweis Und Belege: Nda Standardklauseln Bauleiter; Nda Vertragsstrafe Prüfen; Spezial Entwurf Tatbestand Beweis Und Belege. Führt Intake, Prüfroutine,... |
| `word` | Spezial Word Zahlen Schwellen Und Berechnung: Spezial Word Zahlen Schwellen Und Berechnung. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zusammen. |
| `workflow-anschluss-skills-router` | Anschluss-Skills Router im Plugin nda-abgleich: schlägt nach der ersten Prüfung die passenden Spezialskills aus demselben Plugin vor. |
| `workflow-dokumentenintake` | Dokumentenintake im Plugin nda-abgleich: liest Uploads, sortiert Dokumentarten, markiert Fristen und baut eine knappe Arbeitsakte. |
| `workflow-kaltstart-und-routing` | Kaltstart und Routing im Plugin nda-abgleich: führt vom ersten Satz oder Dokument in den passenden Arbeitsweg, erkennt Rolle, Ziel, Risiko und Anschluss-Skills. |
| `workflow-mandantenkommunikation-redteam-qualitygate-nda` | Workflow Mandantenkommunikation, Workflow Redteam Qualitygate, Nda Anwendbares Recht Gerichtsstand: Workflow Mandantenkommunikation; Workflow Redteam Qualitygate; Nda Anwendbares Recht Gerichtsstand. Führt Intake, Prüfroutine, Normen-/Qu... |
| `workflow-output-waehlen` | Output wählen im Plugin nda-abgleich: entscheidet zwischen Memo, Schriftsatz, Tabelle, Brief, Checkliste, Vermerk, Redline oder Mandantenübersetzung. |
| `workflow-rechtsquellen-livecheck` | Rechtsquellen-Livecheck im Plugin nda-abgleich: zwingt vor tragenden Aussagen zum aktuellen Quellencheck bei Gesetzen, Behörden, Gerichten und Formularen. |
| `workflow-unterlagen-lueckenliste` | Unterlagen- und Lückenliste im Plugin nda-abgleich: erstellt eine präzise Nachforderungsliste statt allgemeiner Fragebögen. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
