# Wandeldarlehen-Lebenszyklus

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`wandeldarlehen-lebenszyklus`) | [`wandeldarlehen-lebenszyklus.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/wandeldarlehen-lebenszyklus.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **Nebelstern Ventures - Berliner VC-Pipeline, Wandeldarlehen und Follow-on-Chaos** (`venture-capital-geber-nebelstern-portfolio-berlin`) | [Gesamt-PDF lesen](../testakten/venture-capital-geber-nebelstern-portfolio-berlin/gesamt-pdf/venture-capital-geber-nebelstern-portfolio-berlin_gesamt.pdf) | [`testakte-venture-capital-geber-nebelstern-portfolio-berlin.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-venture-capital-geber-nebelstern-portfolio-berlin.zip) |
| **Wandeldarlehen-Lebenszyklus (Sonnenglas Solartechnologie UG)** (`wandeldarlehen-beispielcase`) | [Gesamt-PDF lesen](../testakten/wandeldarlehen-beispielcase/gesamt-pdf/wandeldarlehen-beispielcase_gesamt.pdf) | [`testakte-wandeldarlehen-beispielcase.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-wandeldarlehen-beispielcase.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

Vollständiger Workflow-Assistent für den Lebenszyklus eines Wandeldarlehens bei GmbH und UG (haftungsbeschränkt) — von der ersten Mandatsbesprechung über Vertragsgestaltung (bilingual DE/EN oder einsprachig DE), Beurkundungsprüfung, Wandelereignisse und Wandlungsberechnung bis zum Cap-Table-Update, Gesellschafterbeschluss und Handelsregisteranmeldung durch den Notar.

## Lebenszyklus-Visualisierung

```
Phase A — Erstellung
  └─ Mandat-Triage → Parteien erfassen → Konditionen → Wandlungsmechanik
     → Rangrücktritt → Vertragserstellung (bilingual / einsprachig)
     → Vertraulichkeit und Sprachklausel

Phase B — Beurkundung und Unterzeichnung
  └─ Beurkundungserfordernis → Form (Textform/Schriftform/Notariell)
     → Formfehler-Heilungs-Timeline → DocuSign-Unterzeichnung
     → Gesellschafterbeschluss (Absicht) → KYC/AML

Phase C — Wandelereignisse und Wandlungsberechnung
  └─ Eingang Wandlungserklärung → Trigger-Dispatcher → Trigger-Prüfung
     (Qualified Financing / Maturity / Liquidation) → Wandlungspreis-Berechnung
     → Cap-Table Pre/Post → Dokumente-Extraktion
     → Ausschluss-Prüfung → Mehrere WD → Kommunikation

Phase D — Gesellschafterbeschluss und Notar
  └─ Gesellschafterversammlung einberufen → Beschluss Kapitalerhöhung
     → Sacheinlagebericht → Notar-Paket → Gesellschafterliste
     → HR-Anmeldung → Post-Eintragung-Checkliste
```

## Skills nach Phasen

### Phase A — Erstellung (8 Skills)

| Slug | Beschreibung |
|---|---|
| `mandat-triage-wandeldarlehen` | Erstgespräch: Rechtsform, Beteiligte, Wandelereignisse, Sprachen-Stack |
| `parteien-erfassen` | Gesellschaft, Gesellschafterinnen, Darlehensgeber, KYC, Vertretungsmacht |
| `darlehenshoehe-konditionen` | Darlehensbetrag, Laufzeit, Zinssatz, Auszahlung, Bankverbindung |
| `wandlungsmechanik-konzipieren` | Cap, Discount, Trigger-Logik, Wandlungsformel, MFN, Pro-rata |
| Rechtsprechung live prüfen | keine Entscheidung aus Modellwissen; Quelle vor Ausgabe protokollieren |
| `bilinguale-vertragserstellung` | Vollständiger Vertrag DE/EN zweispaltig, Sprachklausel |
| `einsprachige-vertragsfassung-de` | Einsprachige DE-Fassung, identischer materieller Inhalt |
| `vertraulichkeit-und-sprachklausel` | § 8 Vertraulichkeit, Sprachklausel, DIS-Schiedsklausel, salvatorische Klausel |

### Phase B — Beurkundung und Unterzeichnung (6 Skills)

| Slug | Beschreibung |
|---|---|
| Rechtsprechung live prüfen | keine Entscheidung aus Modellwissen; Quelle vor Ausgabe protokollieren |
| `textform-vs-schriftform-vs-notariell` | § 126b/§ 126/§ 128 BGB, Formstufen, DocuSign-Praxis |
| `formfehler-heilungs-timeline` | Form-Stufen § 126b/§ 126/§ 128 BGB, Heilung durch nachfolgende Beurkundung § 15 Abs. 4 S. 2 GmbHG, Insolvenz-Risiko-Fenster |
| `unterzeichnung-elektronisch-docusign` | Authentifizierung, Audit Trail, zehn Jahre Archivierung § 147 AO |
| `gesellschafterbeschluss-vorbereiten` | Grundsatzbeschluss Kapitalerhöhungsbereitschaft, § 51 GmbHG |
| `kyc-aml-geldwaesche` | GwG KYC, wirtschaftlich Berechtigte, PEP, Sanktionslisten EU/OFAC/UN |

### Phase C — Wandelereignisse und Wandlungsberechnung (11 Skills)

| Slug | Beschreibung |
|---|---|
| `wandelereignis-eingang` | Eingang Wandlungserklärung, Vier-Augen-Prüfung, Eingangsbestätigung |
| `wandelereignis-trigger-dispatcher` | Master-Logik bei parallelen Triggern, Prioritäts-Regelung, Cap-Table-Simulation, MFN-Kaskade |
| `wandlungspruefung-trigger-qualified-financing` | Schwellentest, MIN-Methode Cap/Discount/Rundenpreis |
| `wandlungspruefung-trigger-maturity` | Laufzeitablauf, Fall-back-Bewertung, Wahlrecht Lender |
| `wandlungspruefung-trigger-liquidation` | Exit/Trade Sale/IPO, Liquidationspräferenz, Wahlrecht |
| `wandlungspreis-berechnung` | Vollständige Formel, Aufrundung § 5 GmbHG, Kapitalrücklage § 272 HGB |
| `cap-table-update-pre-post` | Pre-Money und Post-Money Cap-Table, Verwässerungsdarstellung |
| `dokumenten-upload-extraktion` | Term Sheet, SPA, IRA: relevante Zahlen extrahieren |
| `wandlungsausschluss-pruefung` | Verfristung, Verjährung, Verwirkung, Verzicht |
| `mehrere-wandeldarlehen-parallel` | Stack-Order, MFN, gleichzeitige Wandlung, kombinierter Cap-Table |
| `wandlung-kommunikation-paketverteilung` | Lender, Gesellschaft, Steuerberater, Buchhaltung informieren |

### Phase D — Gesellschafterbeschluss und Notar (7 Skills)

| Slug | Beschreibung |
|---|---|
| `gesellschafterversammlung-einberufen` | Einberufung, § 51 GmbHG, Ladungsfristen, Vollmacht, Notartermin |
| `gesellschafterbeschluss-kapitalerhoehung` | Beschluss Kapitalerhöhung gegen Sacheinlage, § 53 Abs. 2 GmbHG |
| `sacheinlagebericht-werthaltigkeit` | Werthaltigkeit Forderung, Differenzhaftung § 9 GmbHG, IDW RS HFA 42 |
| `notar-paket-uebermittlung` | Vollständigkeitscheckliste, Notar-Briefing, § 57 GmbHG-Anmeldung |
| `gesellschafterliste-aktualisieren` | § 40 GmbHG, Gutglaubenswirkung § 16 GmbHG, Transparenzregister |
| `handelsregisteranmeldung-kapitalerhoehung` | § 57 GmbHG, Bearbeitungsdauer, Beanstandungsgründe, § 19 GwG |
| `post-eintragung-checkliste` | Bestätigung, Steuer (§ 20 UmwStG), Sperrfrist § 22 UmwStG, Abschluss-Memo |

## Rechtsgrundlagen

| Bereich | Normen |
|---|---|
| GmbH-Gesellschaftsrecht | GmbHG §§ 1, 5, 5a, 15, 40, 46, 49–51, 53–57, 78 |
| Insolvenzrecht | InsO §§ 17, 19, 38, 39, 44, 15a, 15b |
| Zivilrecht / Form | BGB §§ 126, 126b, 128, 130, 194 ff., 311, 314, 397, 398, 488 ff. |
| Geldwäscherecht | GwG §§ 1–3, 10–13, 19, 43, 47, 56 |
| Handelsrecht | Normtext, Register-/Gesetzesquellen, bereitgestellte Materialien |
| Steuerrecht | UmwStG §§ 20, 22; EStG § 17; AO § 147 |
| Elektronische Signatur | eIDAS-VO 910/2014; Art. 26 ff. |
| Schiedsgerichtsbarkeit | DIS-Schiedsordnung 2018 |

## Verwendungsbeispiel

**Einstiegs-Prompt:**

> "Ich möchte ein Wandeldarlehen aufsetzen — was brauchst du von mir?"

Das Plugin startet mit `mandat-triage-wandeldarlehen` und führt durch:
1. Rechtsform und Parteien klären
2. Konditionen und Wandlungsmechanik festlegen
3. Vertrag erstellen (bilingual DE/EN oder nur DE)
4. Beurkundungserfordernis prüfen
5. DocuSign-Unterzeichnung koordinieren
6. Bei Wandlungsereignis: Trigger prüfen, Preis berechnen, Cap-Table aktualisieren
7. Gesellschafterbeschluss und Notarpaket erstellen
8. Handelsregisteranmeldung begleiten

## Wichtiger Hinweis

Alle Texte dienen als Arbeitshilfe für die anwaltliche Praxis. Sie ersetzen keine rechtliche Beratung im Einzelfall. Jeder Skill verweist auf die maßgebliche Rechtsprechung (BGH/OLG mit Aktenzeichen und Datum). Änderungen in GmbHG, InsO, UmwStG oder GwG sind einzuarbeiten (Stand: 05/2026).

<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 28 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `allgemein` | Einstieg, Schnelltriage und Workflow-Routing im Wandeldarlehen Lebenszyklus-Plugin. Fragt Rolle, Ziel, Fristen, Unterlagen, Risiken und Wunsch-Output ab, schlägt passende Spezial-Skills aus diesem Plugin vor und führt in einen klaren Arb... |
| `bilingual-einsprachig` | Spezial Bilingual Schriftsatz Brief Und Memo Bausteine, Spezial Einsprachig Verhandlung Vergleich Und Eskalation: Spezial Bilingual Schriftsatz Brief Und Memo Bausteine; Spezial Einsprachig Verhandlung Vergleich Und Eskalation. Führt Int... |
| `cap-table-darlehenshoehe-konditionen` | Cap Table Update Pre Post, Darlehenshoehe Konditionen: Cap Table Update Pre Post; Darlehenshoehe Konditionen. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zusammen. |
| `dokumenten-upload-formfehler-heilungs` | Dokumenten Upload Extraktion, Formfehler Heilungs Timeline: Dokumenten Upload Extraktion; Formfehler Heilungs Timeline. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zusammen. |
| `einsprachige-vertragsfassung-vertragserstellung` | Einsprachige Vertragsfassung De, Spezial Vertragserstellung Behörden Gericht Und Registerweg: Einsprachige Vertragsfassung De; Spezial Vertragserstellung Behörden Gericht Und Registerweg. Führt Intake, Prüfroutine, Normen-/Quellenradar,... |
| `gesellschafterbeschluss-kapitalerhoehung-vorbereiten` | Gesellschafterbeschluss Kapitalerhoehung, Gesellschafterbeschluss Vorbereiten: Gesellschafterbeschluss Kapitalerhoehung; Gesellschafterbeschluss Vorbereiten. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und... |
| `gesellschafterliste-aktualisieren-gesellschafterversammlung` | Gesellschafterliste Aktualisieren, Gesellschafterversammlung Einberufen: Gesellschafterliste Aktualisieren; Gesellschafterversammlung Einberufen. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätsche... |
| `gmbh-vollstaendigen` | Spezial Gmbh Risikoampel Und Gegenargumente, Spezial Vollstaendigen Tatbestand Beweis Und Belege: Spezial Gmbh Risikoampel Und Gegenargumente; Spezial Vollstaendigen Tatbestand Beweis Und Belege. Führt Intake, Prüfroutine, Normen-/Quelle... |
| `handelsregisteranmeldung-kapitalerhoehung-kyc-aml` | Handelsregisteranmeldung Kapitalerhoehung, Kyc Aml Geldwaesche: Handelsregisteranmeldung Kapitalerhoehung; Kyc Aml Geldwaesche. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zusammen. |
| `lebenszyklus-bilinguale-vertragserstellung` | Spezial Lebenszyklus Fristen Form Und Zustaendigkeit, Bilinguale Vertragserstellung: Spezial Lebenszyklus Fristen Form Und Zustaendigkeit; Bilinguale Vertragserstellung. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outpu... |
| `mandat-triage-mehrere-parallel` | Mandat Triage Wandeldarlehen, Mehrere Wandeldarlehen Parallel: Mandat Triage Wandeldarlehen; Mehrere Wandeldarlehen Parallel. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zusammen. |
| `notar-paket-parteien-erfassen` | Notar Paket Uebermittlung, Parteien Erfassen: Notar Paket Uebermittlung; Parteien Erfassen. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zusammen. |
| `post-eintragung-rangruecktritt-formulieren` | Post Eintragung Checkliste, Rangruecktritt Formulieren: Post Eintragung Checkliste; Rangruecktritt Formulieren. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zusammen. |
| `sacheinlagebericht-werthaltigkeit-begleitet` | Sacheinlagebericht Werthaltigkeit, Spezial Begleitet Erstpruefung Und Mandatsziel: Sacheinlagebericht Werthaltigkeit; Spezial Begleitet Erstpruefung Und Mandatsziel. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmus... |
| `spezial-beurkundungspruefung-livequellen-check` | Beurkundungspruefung: Livequellen- und Rechtsprechungscheck im Plugin wandeldarlehen lebenszyklus; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Standardprüfung. |
| `unterzeichnung-elektronisch-wandelereignis-eingang` | Unterzeichnung Elektronisch Docusign, Wandelereignis Eingang: Unterzeichnung Elektronisch Docusign; Wandelereignis Eingang. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zusammen. |
| `vertraulichkeit-sprachklausel-beurkundungserfordernis` | Vertraulichkeit Und Sprachklausel, Beurkundungserfordernis Prüfung: Vertraulichkeit Und Sprachklausel; Beurkundungserfordernis Prüfung. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zusammen. |
| `wandeldarlehens-wandelereignisse` | Spezial Wandeldarlehens Dokumentenmatrix Und Lueckenliste, Spezial Wandelereignisse Zahlen Schwellen Und Berechnung: Spezial Wandeldarlehens Dokumentenmatrix Und Lueckenliste; Spezial Wandelereignisse Zahlen Schwellen Und Berechnung. Füh... |
| `wandelereignis-trigger-wandlung-kommunikation` | Wandelereignis Trigger Dispatcher, Wandlung Kommunikation Paketverteilung: Wandelereignis Trigger Dispatcher; Wandlung Kommunikation Paketverteilung. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualität... |
| `wandlungsausloeser-cap-textform-vs` | Spezial Wandlungsausloeser Cap Und Discount, Textform Vs Schriftform Vs Notariell: Spezial Wandlungsausloeser Cap Und Discount; Textform Vs Schriftform Vs Notariell. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmus... |
| `wandlungsausschluss-wandlungsmechanik-konzipieren` | Wandlungsausschluss Prüfung, Wandlungsmechanik Konzipieren: Wandlungsausschluss Prüfung; Wandlungsmechanik Konzipieren. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zusammen. |
| `wandlungspreis-wandlungspruefung-trigger` | Wandlungspreis Berechnung, Wandlungspruefung Trigger Liquidation: Wandlungspreis Berechnung; Wandlungspruefung Trigger Liquidation. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zusammen. |
| `wandlungspruefung-trigger-wandlungspruefung-trigger` | Wandlungspruefung Trigger Maturity, Wandlungspruefung Trigger Qualified Financing: Wandlungspruefung Trigger Maturity; Wandlungspruefung Trigger Qualified Financing. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmus... |
| `workflow-chronologie-workflow-fristen` | Workflow Chronologie Und Belegmatrix, Workflow Fristen Und Risikoampel: Workflow Chronologie Und Belegmatrix; Workflow Fristen Und Risikoampel. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck... |
| `workflow-dokumentenintake` | Dokumentenintake im Plugin wandeldarlehen-lebenszyklus: liest Uploads, sortiert Dokumentarten, markiert Fristen und baut eine knappe Arbeitsakte. |
| `workflow-kaltstart-und-routing` | Kaltstart und Routing im Plugin wandeldarlehen-lebenszyklus: führt vom ersten Satz oder Dokument in den passenden Arbeitsweg, erkennt Rolle, Ziel, Risiko und Anschluss-Skills. |
| `workflow-output-waehlen` | Output wählen im Plugin wandeldarlehen-lebenszyklus: entscheidet zwischen Memo, Schriftsatz, Tabelle, Brief, Checkliste, Vermerk, Redline oder Mandantenübersetzung. |
| `workflow-unterlagen-lueckenliste` | Unterlagen- und Lückenliste im Plugin wandeldarlehen-lebenszyklus: erstellt eine präzise Nachforderungsliste statt allgemeiner Fragebögen. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
