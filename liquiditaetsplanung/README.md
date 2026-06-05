# Liquiditätsplanung — Power-Plugin

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`liquiditaetsplanung`) | [`liquiditaetsplanung.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/liquiditaetsplanung.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **Edelholz Manufaktur Berlin GmbH — Liquiditäts- und Steuerakte** (`beispielakte-edelholz-berlin`) | [Gesamt-PDF lesen](../testakten/beispielakte-edelholz-berlin/gesamt-pdf/beispielakte-edelholz-berlin_gesamt.pdf) | [`testakte-beispielakte-edelholz-berlin.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-beispielakte-edelholz-berlin.zip) |
| **Forschungszulage Riedblick Sensorik GmbH** (`forschungszulage-sensorik-startup-taunus`) | [Gesamt-PDF lesen](../testakten/forschungszulage-sensorik-startup-taunus/gesamt-pdf/forschungszulage-sensorik-startup-taunus_gesamt.pdf) | [`testakte-forschungszulage-sensorik-startup-taunus.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-forschungszulage-sensorik-startup-taunus.zip) |
| **Fortbestehensprognose Paragrafix GmbH** (`fortbestehensprognose-paragrafix-gmbh`) | [Gesamt-PDF lesen](../testakten/fortbestehensprognose-paragrafix-gmbh/gesamt-pdf/fortbestehensprognose-paragrafix-gmbh_gesamt.pdf) | [`testakte-fortbestehensprognose-paragrafix-gmbh.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-fortbestehensprognose-paragrafix-gmbh.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

**Eigenständiges Power-Plugin** für wochenaktuelle Liquiditätsvorschauen nach deutschem Recht (§§ 17, 18, 19 InsO; § 1 StaRUG; BGH-Schema Passiva II). Funktioniert allein. Ergänzt sich optional mit `insolvenzrecht` und `steuerrecht-anwalt-und-berater`, hängt aber nicht von ihnen ab.

---

## Was ist drin

Vier Fachskills plus Allgemein-Skill, alle fachlich autark:

| Skill | Zweck | Horizont |
| --- | --- | --- |
| `idw-s6-integrierte-sanierungsplanung` | Brücke von Liquiditätsvorschau zu Sanierungskonzept: GuV, Planbilanz, Maßnahmenlog, Annahmenregister, Sensitivitäten und Sanierungsfähigkeits-Ampel. | 12-24 Monate |
| `liquiditaetsvorschau-3wochen` | Wochenaktuelle Vorprüfung § 17 InsO (Freitag-Stichtag), Verhältnis zu offenen Forderungen, Ampel. | 3 Wochen |
| `liquiditaetsvorschau-3-6-12-monate` | Rollierende Planung mit Sensitivität (Best/Base/Worst), Fortbestehensprognose nach § 19 InsO und Übergabe in die Sanierungsplanung. | 13 / 26 / 52 Wochen |
| `liquiditaetsvorschau-insolvenzrechtlich` | Gerichtsfeste Liquiditätsbilanz nach BGH-Schema (Passiva II zwingend, Volumeneffekt der Quote, titulierte Forderungen mit Nennwert). | Stichtagsbezogen |

## Ergebnisformate

Jeder Skill liefert standardmäßig eine **Excel-Tabelle** nach der hinterlegten Vorlage (`assets/excel/Liquiditaetsplan-Wochenbasis.xlsx`, KW-Spalten × Kategorien-Zeilen, Freitag als Wochenstichtag). Zusätzlich auf Wahl:

- **Interaktives HTML-Padlet** (`assets/padlet/liquiditaets-padlet.html`) — single-file, autark, rechnet die Ampel live nach BGH-Schema, speichert in `localStorage`, exportiert/importiert JSON.
- **Markdown-Artefakt** (`assets/markdown/liquiditaets-artefakt-vorlage.md`) — Tabellen, Indizienliste, Kurzfazit; wird bei jeder Folgemeldung neu geschrieben.
- **Memo** im Gutachtenstil (DOCX oder Markdown) — **nur auf ausdrückliche Anfrage**.

Die Skills fragen einmal am Anfang nach Format und merken sich die Antwort.

## Banking

Jeder Skill fragt einmal nach der Datenquelle:

1. **Manuell** im Padlet/Artefakt/Chat.
2. **Datei-Import** — CAMT.053, MT940, CSV-Bankexport, DATEV-OPOS.
3. **Connector** — PSD2/FinTS oder verfügbare Anbieter (per `list_external_tools`).

Mandatsgeheimnis (§§ 203/204 StGB, § 43e BRAO) und Drittlandtransfer (DSGVO Art. 44 ff.) werden adressiert.

## BGH-Schema (Passiva II)

```
Aktiva I   = Bank + Kasse + freier zugesagter Kontokorrent (Stichtag)
Aktiva II  = Σ Einzahlungen KW t..t+2
Passiva I  = am Stichtag fällig, eingefordert, nicht echt gestundet
Passiva II = binnen 3 Wochen fällig (KW t+1 + KW t+2)

Lücke abs. = max(0, (Passiva I + Passiva II) − (Aktiva I + Aktiva II))
Quote      = Lücke abs. ÷ (Passiva I + Passiva II)   (Volumeneffekt
             Rechtsprechung live prüfen: Keine Entscheidung aus Modellwissen zitieren; vor Ausgabe über amtliche oder frei zugängliche Quelle mit Gericht, Entscheidungsform, Datum, Aktenzeichen und tragender Aussage verifizieren.
```

**Ampel**: 🟢 Quote < 10 % und Liquidität KW t+2 ≥ 0 und < 2 Indizien. 🟡 Quote ≥ 10 %, KW t+2 ≥ 0, < 2 Indizien (schließbar). 🔴 sonst — § 17 InsO indiziert.

## Leitentscheidungen (Volltexte: `references/rechtsprechung/`)

1. Rechtsprechung live prüfen: Keine Entscheidung aus Modellwissen zitieren; vor Ausgabe über amtliche oder frei zugängliche Quelle mit Gericht, Entscheidungsform, Datum, Aktenzeichen und tragender Aussage verifizieren.
1. Rechtsprechung live prüfen: Keine Entscheidung aus Modellwissen zitieren; vor Ausgabe über amtliche oder frei zugängliche Quelle mit Gericht, Entscheidungsform, Datum, Aktenzeichen und tragender Aussage verifizieren.
1. Rechtsprechung live prüfen: Keine Entscheidung aus Modellwissen zitieren; vor Ausgabe über amtliche oder frei zugängliche Quelle mit Gericht, Entscheidungsform, Datum, Aktenzeichen und tragender Aussage verifizieren.
1. Rechtsprechung live prüfen: Keine Entscheidung aus Modellwissen zitieren; vor Ausgabe über amtliche oder frei zugängliche Quelle mit Gericht, Entscheidungsform, Datum, Aktenzeichen und tragender Aussage verifizieren.
1. Rechtsprechung live prüfen: Keine Entscheidung aus Modellwissen zitieren; vor Ausgabe über amtliche oder frei zugängliche Quelle mit Gericht, Entscheidungsform, Datum, Aktenzeichen und tragender Aussage verifizieren.
1. Rechtsprechung live prüfen: Keine Entscheidung aus Modellwissen zitieren; vor Ausgabe über amtliche oder frei zugängliche Quelle mit Gericht, Entscheidungsform, Datum, Aktenzeichen und tragender Aussage verifizieren.
1. Rechtsprechung live prüfen: Keine Entscheidung aus Modellwissen zitieren; vor Ausgabe über amtliche oder frei zugängliche Quelle mit Gericht, Entscheidungsform, Datum, Aktenzeichen und tragender Aussage verifizieren.

Berufsständischer Hintergrund: Methodenrahmen zu Insolvenzeröffnungsgründen und Sanierungskonzepten; nicht als Ersatz für Gesetz, Rechtsprechung und konkrete Subsumtion zitieren.

## Lizenz

Apache-2.0 OR MIT — Auswahl beim Empfänger.

## Quellen-Disclaimer

Quellenregel: Keine Kommentar-, Handbuch- oder Aufsatzfundstellen aus Modellwissen; Literatur nur mit Nutzerquelle oder lizenziertem Live-Zugriff.


<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 26 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `allgemein-workflow-chronologie-workflow-fristen` | Allgemein, Workflow Chronologie Und Belegmatrix, Workflow Fristen Und Risikoampel: Allgemein; Workflow Chronologie Und Belegmatrix; Workflow Fristen Und Risikoampel. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmus... |
| `deutschem-dokumentationspaket-excel` | Spezial Deutschem Tatbestand Beweis Und Belege, Spezial Dokumentationspaket Compliance Dokumentation Und Akte, Spezial Excel Behörden Gericht Und Registerweg: Spezial Deutschem Tatbestand Beweis Und Belege; Spezial Dokumentationspaket Co... |
| `export-forecast-fortbestehensprognose-international` | Spezial Export Schriftsatz Brief Und Memo Bausteine, Spezial Forecast Risikoampel Und Gegenargumente, Spezial Fortbestehensprognose International Schnittstellen: Spezial Export Schriftsatz Brief Und Memo Bausteine; Spezial Forecast Risik... |
| `insolvenzrecht-liqui-sonderfall-liquiditaetsplanung` | Spezial Insolvenzrecht Formular Portal Und Einreichung, Spezial Liqui Sonderfall Und Edge Case, Spezial Liquiditaetsplanung Erstpruefung Und Mandatsziel: Spezial Insolvenzrecht Formular Portal Und Einreichung; Spezial Liqui Sonderfall Un... |
| `interessen-verifikation-beweislast-vorschau` | Spezial Schnittstellen Mehrparteien Konflikt Und Interessen, Spezial Verifikation Beweislast Und Darlegungslast, Spezial Vorschau Dokumentenmatrix Und Lueckenliste: Spezial Schnittstellen Mehrparteien Konflikt Und Interessen; Spezial Ver... |
| `liqp-liquiditaetspool-cash-rollende-13wochen-warenkredit-skonto` | Liqp Liquiditaetspool Cash Pooling Spezial, Liqp Rollende 13Wochen Bauleiter, Liqp Warenkredit Skonto Szenarien Spezial: Liqp Liquiditaetspool Cash Pooling Spezial; Liqp Rollende 13Wochen Bauleiter; Liqp Warenkredit Skonto Szenarien Spez... |
| `liqui-drohender-zahlungsunfaehigkeit-eingetretener-bankgespraech` | Liqui Bei Drohender Zahlungsunfaehigkeit, Liqui Bei Eingetretener Zahlungsunfaehigkeit, Liqui Für Bankgespraech: Liqui Bei Drohender Zahlungsunfaehigkeit; Liqui Bei Eingetretener Zahlungsunfaehigkeit; Liqui Für Bankgespraech. Führt Intak... |
| `liqui-eingangsdaten-idw-s6-liqp-bankenreporting` | Liqui Eingangsdaten Checkliste, Idw S6 Integrierte Sanierungsplanung, Liqp Bankenreporting Leitfaden: Liqui Eingangsdaten Checkliste; Idw S6 Integrierte Sanierungsplanung; Liqp Bankenreporting Leitfaden. Führt Intake, Prüfroutine, Normen... |
| `liqui-grundbegriffe-cashflow-kreditlinien-mahnstufen-debitoren` | Liqui Grundbegriffe Cashflow, Liqui Kreditlinien Prüfen, Liqui Mahnstufen Debitoren: Liqui Grundbegriffe Cashflow; Liqui Kreditlinien Prüfen; Liqui Mahnstufen Debitoren. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outpu... |
| `liqui-leasing-lp-restrukturierungsplan-starug-saisonalitaet` | Liqui Mit Leasing Und Lp, Liqui Restrukturierungsplan Starug, Liqui Saisonalitaet Erkennen: Liqui Mit Leasing Und Lp; Liqui Restrukturierungsplan Starug; Liqui Saisonalitaet Erkennen. Führt Intake, Prüfroutine, Normen-/Quellenradar, Bewe... |
| `liqui-sondereffekt-grossauftrag-stundungs-strategie-szenarien` | Liqui Sondereffekt Grossauftrag, Liqui Stundungs Strategie, Liqui Szenarien Aufbauen: Liqui Sondereffekt Grossauftrag; Liqui Stundungs Strategie; Liqui Szenarien Aufbauen. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Out... |
| `liquiditaetsstatus-quellenbelege-live-quote` | Spezial Liquiditaetsstatus Quellenbelege, Spezial Live Mandantenkommunikation Entscheidungsvorlage, Spezial Quote Verhandlung Vergleich Und Eskalation: Spezial Liquiditaetsstatus Quellenbelege; Spezial Live Mandantenkommunikation Entsche... |
| `liquiditaetsvorschau-3-6-12-monate` | Rollierende Liquiditaetsvorschau fuer 3/6/12 Monate mit Fortfuehrungsprognose, Wochenraster, Excel-Export und Quellenhygiene. Rechtsprechung nur nach Live-Pruefung. |
| `liquiditaetsvorschau-3wochen` | Drei-Wochen-Liquiditaetsvorschau nach § 17 InsO mit Wochenraster, Excel-Export, Quote/Luecken-Ampel und Dokumentation. Rechtsprechung nur nach Live-Pruefung. |
| `liquiditaetsvorschau-3wochen-liquiditaetsvorschau` | Liquiditaetsvorschau 3Wochen, Liquiditaetsvorschau Insolvenzrechtlich, Spezial Ampel Zahlen Schwellen Und Berechnung: Liquiditaetsvorschau 3Wochen; Liquiditaetsvorschau Insolvenzrechtlich; Spezial Ampel Zahlen Schwellen Und Berechnung. F... |
| `liquiditaetsvorschau-insolvenzrechtlich` | Workflow-Skill zu liquiditaetsvorschau insolvenzrechtlich. Nutzt Normtext, Nutzerangaben und verifizierte Quellen; Rechtsprechung nur nach Live-Pruefung mit Gericht, Datum und Aktenzeichen. |
| `spezial-luecken-livequellen-und-rechtsprechungscheck` | Luecken: Livequellen- und Rechtsprechungscheck im Plugin liquiditaetsplanung; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Standardprüfung. |
| `spezial-rechtsprechung-red-team-und-qualitaetskontrolle` | Rechtsprechung: Red-Team und Qualitätskontrolle im Plugin liquiditaetsplanung; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Standardprüfung. |
| `wochen-liqui-ausgabengruppen-liqui-cash` | Spezial Wochen Fristen Form Und Zustaendigkeit, Liqui Ausgabengruppen Systematik, Liqui Cash Pooling Konzern: Spezial Wochen Fristen Form Und Zustaendigkeit; Liqui Ausgabengruppen Systematik; Liqui Cash Pooling Konzern. Führt Intake, Prü... |
| `workflow-anschluss-skills-router` | Anschluss-Skills Router im Plugin liquiditaetsplanung: schlägt nach der ersten Prüfung die passenden Spezialskills aus demselben Plugin vor. |
| `workflow-dokumentenintake` | Dokumentenintake im Plugin liquiditaetsplanung: liest Uploads, sortiert Dokumentarten, markiert Fristen und baut eine knappe Arbeitsakte. |
| `workflow-kaltstart-und-routing` | Kaltstart und Routing im Plugin liquiditaetsplanung: führt vom ersten Satz oder Dokument in den passenden Arbeitsweg, erkennt Rolle, Ziel, Risiko und Anschluss-Skills. |
| `workflow-mandantenkommunikation-redteam-qualitygate` | Workflow Mandantenkommunikation, Workflow Redteam Qualitygate, Spezial Ausgabengruppen Fristennotiz Und Naechster Schritt: Workflow Mandantenkommunikation; Workflow Redteam Qualitygate; Spezial Ausgabengruppen Fristennotiz Und Naechster... |
| `workflow-output-waehlen` | Output wählen im Plugin liquiditaetsplanung: entscheidet zwischen Memo, Schriftsatz, Tabelle, Brief, Checkliste, Vermerk, Redline oder Mandantenübersetzung. |
| `workflow-rechtsquellen-livecheck` | Rechtsquellen-Livecheck im Plugin liquiditaetsplanung: zwingt vor tragenden Aussagen zum aktuellen Quellencheck bei Gesetzen, Behörden, Gerichten und Formularen. |
| `workflow-unterlagen-lueckenliste` | Unterlagen- und Lückenliste im Plugin liquiditaetsplanung: erstellt eine präzise Nachforderungsliste statt allgemeiner Fragebögen. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
