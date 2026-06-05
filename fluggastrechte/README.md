# Fluggastrechte

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`fluggastrechte`) | [`fluggastrechte.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/fluggastrechte.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **Fluggastrechte – Familie Bräutigam-Zaytuna** (`fluggastrechte-familie-braeutigam`) | [Gesamt-PDF lesen](../testakten/fluggastrechte-familie-braeutigam/gesamt-pdf/fluggastrechte-familie-braeutigam_gesamt.pdf) | [`testakte-fluggastrechte-familie-braeutigam.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-fluggastrechte-familie-braeutigam.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

Fluggastrechte selber geltend machen — VO (EG) Nr. 261/2004 plus EuGH-Rspr. Tickets erfassen Annullierung vs Verspätung prüfen außergewöhnliche Umstände Distanz und Ausgleich Forderungsschreiben Mahnung Klage Amtsgericht. Vollmacht Familie. Katalog Airline-Standardausreden.

## Installation in Claude Code

1. ZIP herunterladen (Link oben).
2. Claude Code → **Customize Plugins** → **Install from .zip** → Datei wählen.
3. Fertig. Skills sind sofort verfügbar.

> **Hinweis:** Für den ZIP-Upload muss das Archiv direkt `.claude-plugin/plugin.json`, `skills/`, `assets/` und `references/` im ZIP-Root enthalten. **Nicht** das komplette Repository-ZIP aus "Code → Download ZIP" verwenden.

## Enthaltene Skills

| Skill | Zweck |
| --- | --- |
| `airline-standardausreden-pruefen` | Katalog typischer Standardausreden der Fluggesellschaften mit Gegenargumenten und Pinpoint auf EuGH-Rechtsprechung. Behandelt technischer Defekt wilder Streik Streik der Gewerkschaft Crew-Engpass verdeckter Konstrukti… |
| Rechtsprechung live prüfen | Keine Entscheidung aus Modellwissen zitieren; vor Ausgabe über amtliche oder frei zugängliche Quelle mit Gericht, Entscheidungsform, Datum, Aktenzeichen und tragender Aussage verifizieren. |
| Rechtsprechung live prüfen | keine Entscheidung aus Modellwissen; Quelle vor Ausgabe protokollieren |
| `ausnahmen-aussergewoehnliche-umstaende-pruefen` | Prüft die Einrede außergewöhnliche Umstände nach Art. 5 Abs. 3 VO 261/2004. Differenziert zwischen Wetter Vulkanasche Vogelschlag Streik Flugsicherung Streik der eigenen Mitarbeiter wilder Streik technischem Defek… |
| `distanz-und-ausgleich-berechnen` | Berechnet die Ausgleichszahlung nach Art. 7 VO 261/2004. Distanzbestimmung nach Großkreisrechnung zwischen Abflug- und Zielflughafen. Drei Stufen 250 EUR bis 1500 km / 400 EUR mehr als 1500 km innergemeinschaftlich o… |
| `forderungsschreiben-erste-stufe` | Erstes Forderungsschreiben an die Airline. Erfasst Anspruchsteller (alle Passagiere mit Vollmachten) Anspruchsgrundlage Art. 7 VO 261/2004 konkrete Berechnung Frist zur Zahlung (typisch zwei Wochen) Bankverbindung. In… |
| `forderungsschreiben-mahnung` | Zweite Stufe nach Ablauf der Frist aus dem ersten Forderungsschreiben oder nach erfolgloser Reaktion der Airline. Setzt Nachfrist (typisch zehn Tage) bezieht sich auf die erste Forderung weist Verzugszinsen aus und dr… |
| `fluggastrechte-kaltstart-interview` | Kaltstart-Interview für das Fluggastrechte-Plugin. Klärt Anwendungsrolle (eigener Fluggastrechte-Anspruch / Vertretung Familie / Mitreisende). Erfasst Buchungsstammdaten Vertragspartner (Airline IATA-Code) und Reise… |
| `klage-amtsgericht-fluggast` | Klageentwurf zum Amtsgericht in Fluggastrechtsangelegenheiten. Sachliche Zuständigkeit § 23 Nr. 1 GVG bei Streitwert bis zehntausend Euro (i. d. F. seit 01.01.2026). Örtlich wahlweise Abflughafen oder Zielflughafen … |
| `ticket-und-fluginformationen-erfassen` | Erfasst die Falldaten aus hochgeladenen Tickets Buchungsbestätigungen Boardingpässe PDF-Scans Foto-Belegen. Extrahiert Buchungscode (PNR) Flugnummer Datum Abflughafen Zielflughafen geplante Abflugzeit geplante Ankun… |
| `vollmacht-familienmitglieder` | Erzeugt Vollmachten für Mitreisende (Familienmitglieder Freunde) damit der Hauptansprechpartner deren Fluggastrechtsanspruch im Schriftverkehr und im gerichtlichen Verfahren mitvertreten kann. Pro Person eigene Vollm… |

## Lizenz

Apache-2.0 OR MIT — Auswahl beim Empfänger.

## Quellen-Disclaimer

Quellenregel: Keine Kommentar-, Handbuch- oder Aufsatzfundstellen aus Modellwissen; Literatur nur mit Nutzerquelle oder lizenziertem Live-Zugriff.

<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 24 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `airline-standardausreden-annullierung-verspaetung-anschlussflug` | Airline Standardausreden Prüfen, Annullierung Oder Verspaetung Einordnen, Anschlussflug Und Reiseplan: Airline Standardausreden Prüfen; Annullierung Oder Verspaetung Einordnen; Anschlussflug Und Reiseplan. Führt Intake, Prüfroutine, Norm... |
| `allgemein-anschluss-router-workflow-chronologie` | Allgemein, Workflow Anschluss Skills Router, Workflow Chronologie Und Belegmatrix: Allgemein; Workflow Anschluss Skills Router; Workflow Chronologie Und Belegmatrix. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmus... |
| `ausnahmen-aussergewoehnliche-aussergewoehnliche-umstaende` | Ausnahmen Aussergewoehnliche Umstaende Prüfen, Aussergewoehnliche Umstaende Strikt, Distanz Und Ausgleich Berechnen: Ausnahmen Aussergewoehnliche Umstaende Prüfen; Aussergewoehnliche Umstaende Strikt; Distanz Und Ausgleich Berechnen. Füh... |
| `aussergewoehnliche-distanz-interessen-erfassen` | Spezial Aussergewoehnliche Zahlen Schwellen Und Berechnung, Spezial Distanz Mehrparteien Konflikt Und Interessen, Spezial Erfassen Behörden Gericht Und Registerweg: Spezial Aussergewoehnliche Zahlen Schwellen Und Berechnung; Spezial Dist... |
| `flug-anschlussflug-codeshare-anspruch-uebersicht` | Flug Anschlussflug Codeshare Spezial, Flug Anspruch Uebersicht, Flug Ausserordentlicher Umstand Leitfaden: Flug Anschlussflug Codeshare Spezial; Flug Anspruch Uebersicht; Flug Ausserordentlicher Umstand Leitfaden. Führt Intake, Prüfrouti... |
| `flug-massenklage-einfuehrung-vo-forderungsschreiben-erste` | Flug Massenklage Prozessfinanzierung Spezial, Fluggastrechte Einfuehrung Vo 261, Forderungsschreiben Erste Stufe: Flug Massenklage Prozessfinanzierung Spezial; Fluggastrechte Einfuehrung Vo 261; Forderungsschreiben Erste Stufe. Führt Int... |
| `fluggastrechte-anlagen-bauen` | Baut aus den Belegen eines Fluggastrechte-Mandats ein beA-konformes Anlagenkonvolut. Verwendet zum bestehenden Schriftsatz (Forderungsschreiben Mahnung Klage) die Belege Buchungsbestätigung Boardingpass Annullierungsbestätigung E-Mail-Ve... |
| `fluggastrechte-forderungsschreiben-klage` | Spezial Fluggastrechte Erstpruefung Und Mandatsziel, Spezial Forderungsschreiben Formular Portal Und Einreichung, Spezial Klage Mandantenkommunikation Entscheidungsvorlage: Spezial Fluggastrechte Erstpruefung Und Mandatsziel; Spezial For... |
| `fluggastrechte-kaltstart-interview` | Kaltstart-Interview für das Fluggastrechte-Plugin. Klaert Anwendungsrolle (eigener Fluggastrechte-Anspruch / Vertretung Familie / Mitreisende). Erfasst Buchungsstammdaten Vertragspartner (Airline IATA-Code) und Reiseplan-Konvention. Schr... |
| `forderungsschreiben-mahnung-klage-amtsgericht-pauschalreise` | Forderungsschreiben Mahnung, Klage Amtsgericht Fluggast, Pauschalreise Statt Flug Prüfen: Forderungsschreiben Mahnung; Klage Amtsgericht Fluggast; Pauschalreise Statt Flug Prüfen. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislo... |
| `live-sonderfall-machen-mahnung-red` | Spezial Live Sonderfall Und Edge Case, Spezial Machen Dokumentenmatrix Und Lueckenliste, Spezial Mahnung Red Team Und Qualitaetskontrolle: Spezial Live Sonderfall Und Edge Case; Spezial Machen Dokumentenmatrix Und Lueckenliste; Spezial M... |
| `rechtsprechung-beweislast-vorverlegung-flug-geltend` | Spezial Rechtsprechung Beweislast Und Darlegungslast, Vorverlegung Flug Rechtsprechung, Spezial Geltend Fristen Form Und Zustaendigkeit: Spezial Rechtsprechung Beweislast Und Darlegungslast; Vorverlegung Flug Rechtsprechung; Spezial Gelt... |
| `rechtsweg-gerichtsstand-annullierung-ausgleich` | Rechtsweg Und Gerichtsstand Fluggast, Spezial Annullierung Schriftsatz Brief Und Memo Bausteine, Spezial Ausgleich Internationaler Bezug Und Schnittstellen: Rechtsweg Und Gerichtsstand Fluggast; Spezial Annullierung Schriftsatz Brief Und... |
| `selber-tickets-umstaende` | Spezial Selber Tatbestand Beweis Und Belege, Spezial Tickets Risikoampel Und Gegenargumente, Spezial Umstaende Compliance Dokumentation Und Akte: Spezial Selber Tatbestand Beweis Und Belege; Spezial Tickets Risikoampel Und Gegenargumente... |
| `spezial-kaltstart-abschlussprodukt-und-uebergabe` | Kaltstart: Abschlussprodukt und Übergabe im Plugin fluggastrechte; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Standardprüfung. |
| `spezial-pruefen-livequellen-und-rechtsprechungscheck` | Pruefen: Livequellen- und Rechtsprechungscheck im Plugin fluggastrechte; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Standardprüfung. |
| `verifikation-fristennotiz-abtretung-an-airline-bonitaet` | Spezial Verifikation Fristennotiz Und Naechster Schritt, Abtretung An Fluggastportal Spezial, Airline Bonitaet Und Vollstreckung: Spezial Verifikation Fristennotiz Und Naechster Schritt; Abtretung An Fluggastportal Spezial; Airline Bonit... |
| `verspaetung-ticket-fluginformationen-vollmacht` | Spezial Verspaetung Verhandlung Vergleich Und Eskalation, Ticket Und Fluginformationen Erfassen, Vollmacht Familienmitglieder: Spezial Verspaetung Verhandlung Vergleich Und Eskalation; Ticket Und Fluginformationen Erfassen; Vollmacht Fam... |
| `workflow-dokumentenintake` | Dokumentenintake im Plugin fluggastrechte: liest Uploads, sortiert Dokumentarten, markiert Fristen und baut eine knappe Arbeitsakte. |
| `workflow-fristen-risikoampel-mandantenkommunikation-redteam` | Workflow Fristen Und Risikoampel, Workflow Mandantenkommunikation, Workflow Redteam Qualitygate: Workflow Fristen Und Risikoampel; Workflow Mandantenkommunikation; Workflow Redteam Qualitygate. Führt Intake, Prüfroutine, Normen-/Quellenr... |
| `workflow-kaltstart-und-routing` | Kaltstart und Routing im Plugin fluggastrechte: führt vom ersten Satz oder Dokument in den passenden Arbeitsweg, erkennt Rolle, Ziel, Risiko und Anschluss-Skills. |
| `workflow-output-waehlen` | Output wählen im Plugin fluggastrechte: entscheidet zwischen Memo, Schriftsatz, Tabelle, Brief, Checkliste, Vermerk, Redline oder Mandantenübersetzung. |
| `workflow-rechtsquellen-livecheck` | Rechtsquellen-Livecheck im Plugin fluggastrechte: zwingt vor tragenden Aussagen zum aktuellen Quellencheck bei Gesetzen, Behörden, Gerichten und Formularen. |
| `workflow-unterlagen-lueckenliste` | Unterlagen- und Lückenliste im Plugin fluggastrechte: erstellt eine präzise Nachforderungsliste statt allgemeiner Fragebögen. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
