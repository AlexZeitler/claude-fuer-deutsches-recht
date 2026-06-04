# Tabellenreview 3D

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`tabellenreview-3d`) | [`tabellenreview-3d.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/tabellenreview-3d.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **Tabellenreview Paragrafix GmbH — Fortbestehensprognose v23, IDW S 11** (`tabellenreview-finanzplanung-fortbestehensprognose-paragrafix-fortsetzung-vellbruck`) | [Gesamt-PDF lesen](../testakten/tabellenreview-finanzplanung-fortbestehensprognose-paragrafix-fortsetzung-vellbruck/gesamt-pdf/tabellenreview-finanzplanung-fortbestehensprognose-paragrafix-fortsetzung-vellbruck_gesamt.pdf) | [`testakte-tabellenreview-finanzplanung-fortbestehensprognose-paragrafix-fortsetzung-vellbruck.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-tabellenreview-finanzplanung-fortbestehensprognose-paragrafix-fortsetzung-vellbruck.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

3D-Tabellenreview als Würfel: Spaltenprompts pro Datenpunkt x Zeilenprompts pro Dokument x Arbeitsblatt-Perspektiven (Recht / Steuer / Wirtschaft) gestapelt. Massenprüfung Vertragsstapel M&A-DD Immobilien Vendor-Onboarding mit Excel-Mehrblatt Kreuzblatt-Konsistenz Audit-Trail Belegkette.

## Installation in Claude Code

1. ZIP herunterladen (Link oben).
2. Claude Code → **Customize Plugins** → **Install from .zip** → Datei wählen.
3. Fertig. Skills sind sofort verfügbar.

> **Hinweis:** Für den ZIP-Upload muss das Archiv direkt `.claude-plugin/plugin.json`, `skills/`, `assets/` und `references/` im ZIP-Root enthalten. **Nicht** das komplette Repository-ZIP aus "Code → Download ZIP" verwenden.

## Enthaltene Skills

| Skill | Zweck |
| --- | --- |
| `arbeitsblatt-perspektiven-definieren` | Definiert die dritte Würfel-Achse — Arbeitsblätter als Perspektiven die über denselben Dokumentenstapel laufen aber jeweils eine andere Brille aufsetzen. Typische Perspektiven: Recht (Anwalt) Steuer (Steuerberater)… |
| `audit-trail-protokoll` | Führt das Audit-Trail-Protokoll des Würfels — jeder Reviewlauf jede Prompt-Änderung jede Prüfer-Abnahme jeder Cache-Treffer jede Hash-Prüfung wird unveränderlich protokolliert. Spalten pro Eintrag: Zeitstempel A… |
| `belegkette-rueckverfolgung` | Sichert die Belegkette jeder Zelle des Würfels — von der Antwort über das wörtliche Zitat bis zur Originalstelle im Quelldokument mit Seite Absatz und Datei-Hash. Erkennt Belegkette-Brüche (Datei-Hash weicht ab / … |
| `caching-und-teil-rerun` | Caching der Würfelzellen und gezielter Teil-Rerun bei Änderungen — vermeidet die voll Neuberechnung von tausenden Zellen wenn nur ein Spaltenprompt eine Zeile oder ein Arbeitsblatt geändert wurde. Cache-Key pro Zel… |
| `dokumentstapel-aufnehmen` | Nimmt einen Dokumentenstapel als Zeilenachse des Würfels auf. Quellen: VDR-Export (Datasite Intralinks Box) lokaler Ordner SharePoint-Bibliothek E-Mail-Anhang-Sammlung gescannte PDF mit OCR-Pipeline. Erzeugt pro Doku… |
| `excel-multi-sheet-export` | Exportiert den dreidimensionalen Würfel in eine einzige Excel-Datei mit mehreren Tabellenblättern — ein Reiter pro Arbeitsblatt-Perspektive (Recht / Steuer / Wirtschaft / Datenschutz / IT / Betrieb / Compliance). Je… |
| `tabellenreview-3d-kaltstart-interview` | Kaltstart-Interview für das tabellenreview-3d-Plugin. Erfragt typische Anwendungsfälle (M&A-DD / Immobilienportfolio / Vendor-Onboarding / Arbeitsverträge / Mietverträge / Anlagedokumente / freie Eigenwuerfel), St… |
| `kreuzblatt-konsistenzpruefung` | Prüft die dritte Würfel-Dimension auf innere Konsistenz — läuft NACH `review-durchfuehren` über alle Arbeitsblätter und sucht Widersprüche zwischen Perspektiven (z. B. ein Vertrag rechtlich grün aber datenschut… |
| `pdf-bericht-erzeugen` | Erstellt einen prüfbaren PDF-Bericht aus dem 3D-Würfel. Struktur: Deckblatt mit Projekt Mandant Stichtag Würfel-Ampel; Management-Summary mit Hotspots und blockierenden Roten; pro Arbeitsblatt-Perspektive ein Absch… |
| `prompt-versionierung` | Versioniert alle Spalten- und Zeilenprompts mit semantischer Versions-ID — patch für Wortlautfeinheiten minor für geänderte Antworttypen oder Ampelregeln major für geänderte Pruefdimension. Jede Zelle im Würfel … |
| `pruefer-uebergabe-paket` | Schnuert das vollständige Prüfer-Paket nach Abschluss eines Würfellaufs — Excel-Würfel-Datei aus Skill `excel-multi-sheet-export` PDF-Bericht aus `pdf-bericht-erzeugen` Belegketten-CSV aus `belegkette-rueckverfolg… |
| `review-durchfuehren` | Führt den eigentlichen Reviewlauf über den Würfel durch — Anzahl Zellen = Spalten x Zeilen x Arbeitsblätter. Pro Zelle: Spaltenprompt + Zeilenprompt + Arbeitsblatt-Perspektive zusammenführen, Antwort aus dem Doku… |
| `risikoampel-aggregation` | Konsolidiert die Ampel-Wertungen entlang aller drei Würfelachsen — pro Zelle (atomisch) pro Zeile (Dokument-Gesamtampel) pro Spalte (Datenpunkt-Hotspots) pro Arbeitsblatt (Perspektiven-Gesamtampel) und pro Gesamtwuer… |
| `spaltenprompts-definieren` | Definiert die Spaltenprompts der ersten Würfel-Achse — jede Spalte ist eine einzige praezise Frage die für ALLE Dokumente identisch gestellt wird damit Vergleichbarkeit über den Stapel entsteht. Enthält eine Bibli… |
| `vorlage-arbeitsvertrag-portfolio` | Würfelvorlage für Massenprüfung von Arbeitsverträgen — 15 Spalten (Vertragsdatum Probezeit Befristung-mit-oder-ohne-Sachgrund Wochenarbeitszeit Kündigungsfrist Tarifbindung Bruttogehalt Sonderzahlung Verschwiegen… |
| `vorlage-immobilien-portfolio` | Würfelvorlage für Immobilien-Portfolioanalyse — 16 Spalten (Gemarkung / Flur / Flurstück / Wirtschaftsart / Größe / Eigentümerkette / Abteilung-II-Lasten / Abteilung-III-Grundpfandrechte / Rang / Löschungserlei… |
| `vorlage-ma-due-diligence` | Fertige Würfelvorlage für M&A-Due-Diligence — 18 Spalten (Vertragsart Laufzeit Kündigungsfrist Change-of-Control MAC-Klausel Abtretungsverbot Haftungsbegrenzung Garantien Vertragsstrafe SLA Datenschutz Geheimhaltun… |
| `vorlage-vendor-onboarding-3d` | Würfelvorlage für Vendor- und Lieferanten-Onboarding — 17 Spalten (Vendor-Stammdaten Branche AVV-Pflicht AVV-vorhanden SLA-Reaktionszeit SLA-Verfügbarkeit Exit-Klausel Datenherausgabe Verschlüsselung Subunternehme… |
| `wuerfel-aufbauen` | Baut die dreidimensionale Würfel-Struktur für ein neues Pruefprojekt auf — drei Achsen: Spalten (Datenpunkte als Spaltenprompts) Zeilen (Dokumente mit optionalen Zeilenprompts) Arbeitsblätter (Perspektiven wie Rech… |
| `zeilenprompts-definieren` | Definiert die Zeilenprompts der zweiten Würfel-Achse — pro Dokument eine optionale Sonderanweisung die das Lesen genau dieses Dokuments steuert. Beispiele: 'Konzernvertrag — AktG Paragraph 311 zusätzlich prüfen' / … |

## Lizenz

Apache-2.0 OR MIT — Auswahl beim Empfänger.


<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 24 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `kompendium-01-allgemein-bis-workflow-fristen-und` | tabellenreview-3d: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Allgemein, Chronologie Und Belegmatrix, Fristen Und Risikoampel; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck. |
| `kompendium-02-workflow-mandantenko-bis-spezial-spaltenpromp` | tabellenreview-3d: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Mandantenkommunikation, Redteam Qualitygate, Spaltenprompts Fristen Form Und Zustaendigkeit; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outpu... |
| `kompendium-03-spezial-vertragsstap-bis-vorlage-immobilien-p` | tabellenreview-3d: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Vertragsstapel Internationaler Bezug Und Schnittstellen, Vorlage Arbeitsvertrag Portfolio, Vorlage Immobilien Portfolio; mit Intake, Prüfroutine, Normen-/Quel... |
| `kompendium-04-vorlage-ma-due-dilig-bis-audit-trail-protokol` | tabellenreview-3d: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Vorlage Ma Due Diligence, Arbeitsblatt Perspektiven Definieren, Audit Trail Protokoll; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuste... |
| `kompendium-05-belegkette-rueckverf-bis-dokumentstapel-aufne` | tabellenreview-3d: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Belegkette Rueckverfolgung, Caching Und Teil Rerun, Dokumentstapel Aufnehmen; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qua... |
| `kompendium-06-excel-multi-sheet-ex-bis-pdf-bericht-erzeugen` | tabellenreview-3d: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Excel Multi Sheet Export, Kreuzblatt Konsistenzpruefung, Pdf Bericht Erzeugen; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qu... |
| `kompendium-07-prompt-versionierung-bis-review-durchfuehren` | tabellenreview-3d: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Prompt Versionierung, Pruefer Uebergabe Paket, Review Durchfuehren; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck. |
| `kompendium-08-risikoampel-aggregat-bis-spezial-arbeitsblatt` | tabellenreview-3d: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Risikoampel Aggregation, Spaltenprompts Definieren, Arbeitsblatt Schriftsatz Brief Und Memo Bausteine; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislo... |
| `kompendium-09-spezial-datenpunkt-d-bis-spezial-excel-beweis` | tabellenreview-3d: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Datenpunkt Dokumentenmatrix Und Lueckenliste, Dokument Behoerden Gericht Und Registerweg, Excel Beweislast Und Darlegungslast; mit Intake, Prüfroutine, Normen... |
| `kompendium-10-spezial-gestapelt-co-bis-spezial-massenpruefu` | tabellenreview-3d: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Gestapelt Compliance Dokumentation Und Akte, Immobilien Formular Portal Und Einreichung, Massenpruefung Mehrparteien Konflikt Und Interessen; mit Intake, Prüf... |
| `kompendium-11-spezial-mehrblatt-so-bis-spezial-perspektiven` | tabellenreview-3d: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Mehrblatt Sonderfall Und Edge Case, Onboarding Mandantenkommunikation Entscheidungsvorlage, Perspektiven Verhandlung Vergleich Und Eskalation; mit Intake, Prü... |
| `kompendium-12-spezial-professional-bis-spezial-vendor-red-t` | tabellenreview-3d: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Professional Review Sheet, Tabellenreview Erstpruefung Und Mandatsziel, Vendor Red Team Und Qualitaetskontrolle; mit Intake, Prüfroutine, Normen-/Quellenradar... |
| `kompendium-13-spezial-wirtschaft-z-bis-spezial-zeilenprompt` | tabellenreview-3d: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Wirtschaft Zahlen Schwellen Und Berechnung, Wuerfel Tatbestand Beweis Und Belege, Zeilenprompts Risikoampel Und Gegenargumente; mit Intake, Prüfroutine, Norme... |
| `kompendium-14-tr3d-bestreitensgrue-bis-tr3d-massearmut-tabe` | tabellenreview-3d: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Tr3d Bestreitensgruende Leitfaden, Tr3d Feststellungsklage Tabellenfeststellung Spezial, Tr3d Massearmut Tabelle Spezial; mit Intake, Prüfroutine, Normen-/Que... |
| `kompendium-15-tr3d-pruefkategorien-bis-wuerfel-aufbauen` | tabellenreview-3d: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Tr3d Pruefkategorien Bauleiter, Vorlage Vendor Onboarding 3d, Wuerfel Aufbauen; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Q... |
| `kompendium-16-zeilenprompts-defini-bis-zeilenprompts-defini` | tabellenreview-3d: eigenständiger Arbeits-Skill zu Zeilenprompts Definieren; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck. |
| `spezial-steuer-livequellen-und-rechtsprechungscheck` | Steuer: Livequellen- und Rechtsprechungscheck im Plugin tabellenreview 3d; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Standardprüfung. |
| `tabellenreview-3d-kaltstart-interview` | Kaltstart-Interview für den 3D-Tabellenreview: Fallkategorie, Tabellengrösse, Prüfzweck erfassen. Normen: §§ 174 ff. InsO, HGB. Prüfraster: Zweck, Datenlage, Perspektivenwahl, Exportformat. Output: Konfigurationsdokument für 3D-Review-St... |
| `workflow-anschluss-skills-router` | Anschluss-Skills Router im Plugin tabellenreview-3d: schlägt nach der ersten Prüfung die passenden Spezialskills aus demselben Plugin vor. |
| `workflow-dokumentenintake` | Dokumentenintake im Plugin tabellenreview-3d: liest Uploads, sortiert Dokumentarten, markiert Fristen und baut eine knappe Arbeitsakte. |
| `workflow-kaltstart-und-routing` | Kaltstart und Routing im Plugin tabellenreview-3d: führt vom ersten Satz oder Dokument in den passenden Arbeitsweg, erkennt Rolle, Ziel, Risiko und Anschluss-Skills. |
| `workflow-output-waehlen` | Output wählen im Plugin tabellenreview-3d: entscheidet zwischen Memo, Schriftsatz, Tabelle, Brief, Checkliste, Vermerk, Redline oder Mandantenübersetzung. |
| `workflow-rechtsquellen-livecheck` | Rechtsquellen-Livecheck im Plugin tabellenreview-3d: zwingt vor tragenden Aussagen zum aktuellen Quellencheck bei Gesetzen, Behörden, Gerichten und Formularen. |
| `workflow-unterlagen-lueckenliste` | Unterlagen- und Lückenliste im Plugin tabellenreview-3d: erstellt eine präzise Nachforderungsliste statt allgemeiner Fragebögen. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
