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
| `beurkundungspruefung-quellenkarte-check` | Nutze dies, wenn Beurkundungspruefung Quellenkarte Check im Plugin Wandeldarlehen Lebenszyklus konkret bearbeitet werden soll. Auslöser: Welche amtliche Quelle prüfe ich zuerst?; Gibt es aktuelle Rechtsprechung?; Bitte Fundstellen verifi... |
| `bilingual-einsprachig` | Nutze dies, wenn Spezial Bilingual Schriftsatz Brief Und Memo Bausteine, Spezial Einsprachig Verhandlung Vergleich Und Eskalation im Plugin Wandeldarlehen Lebenszyklus konkret bearbeitet werden soll. Auslöser: Bitte Spezial Bilingual Sch... |
| `cap-table-darlehenshoehe-konditionen` | Nutze dies, wenn Cap Table Update Pre Post, Darlehenshoehe Konditionen im Plugin Wandeldarlehen Lebenszyklus konkret bearbeitet werden soll. Auslöser: Bitte Cap Table Update Pre Post, Darlehenshoehe Konditionen prüfen.; Erstelle eine Arb... |
| `chronologie-fristen` | Nutze dies, wenn Workflow Chronologie Und Belegmatrix, Workflow Fristen Und Risikoampel im Plugin Wandeldarlehen Lebenszyklus konkret bearbeitet werden soll. Auslöser: Bitte Workflow Chronologie Und Belegmatrix, Workflow Fristen Und Risi... |
| `dokumente-intake` | Nutze dies, wenn Dokumentenintake im Plugin Wandeldarlehen Lebenszyklus konkret bearbeitet werden soll. Auslöser: Ich lade Unterlagen hoch.; Was fehlt noch?; Bitte Dokumente sortieren.. |
| `dokumenten-upload-formfehler-heilungs` | Nutze dies, wenn Dokumenten Upload Extraktion, Formfehler Heilungs Timeline im Plugin Wandeldarlehen Lebenszyklus konkret bearbeitet werden soll. Auslöser: Was kann hier schiefgehen?; Bitte red-team prüfen.; Welche Frist oder Beweislast... |
| `einsprachige-vertragsfassung` | Nutze dies, wenn Einsprachige Vertragsfassung De, Spezial Vertragserstellung Behörden Gericht Und Registerweg im Plugin Wandeldarlehen Lebenszyklus konkret bearbeitet werden soll. Auslöser: Bitte Einsprachige Vertragsfassung De, Spezial... |
| `einstieg-routing` | Nutze dies, wenn Einstieg und Routing im Plugin Wandeldarlehen Lebenszyklus konkret bearbeitet werden soll. Auslöser: Ich habe ein neues Thema im Bereich Wandeldarlehen Lebenszyklus.; Welche Unterlagen brauchen Sie?; Welcher Spezialskill... |
| `gesellschafterbeschluss-kapitalerhoehung` | Nutze dies, wenn Gesellschafterbeschluss Kapitalerhoehung, Gesellschafterbeschluss Vorbereiten im Plugin Wandeldarlehen Lebenszyklus konkret bearbeitet werden soll. Auslöser: Bitte Gesellschafterbeschluss Kapitalerhoehung, Gesellschafter... |
| `gesellschafterliste-aktualisieren` | Nutze dies, wenn Gesellschafterliste Aktualisieren, Gesellschafterversammlung Einberufen im Plugin Wandeldarlehen Lebenszyklus konkret bearbeitet werden soll. Auslöser: Bitte Gesellschafterliste Aktualisieren, Gesellschafterversammlung E... |
| `gmbh-vollstaendigen` | Nutze dies, wenn Spezial Gmbh Risikoampel Und Gegenargumente, Spezial Vollstaendigen Tatbestand Beweis Und Belege im Plugin Wandeldarlehen Lebenszyklus konkret bearbeitet werden soll. Auslöser: Bitte Spezial Gmbh Risikoampel Und Gegenarg... |
| `handelsregisteranmeldung-kapitalerhoehung-kyc` | Nutze dies, wenn Handelsregisteranmeldung Kapitalerhoehung, Kyc Aml Geldwaesche im Plugin Wandeldarlehen Lebenszyklus konkret bearbeitet werden soll. Auslöser: Bitte Handelsregisteranmeldung Kapitalerhoehung, Kyc Aml Geldwaesche prüfen.;... |
| `lebenszyklus-bilinguale-vertragserstellung` | Nutze dies, wenn Spezial Lebenszyklus Fristen Form Und Zustaendigkeit, Bilinguale Vertragserstellung im Plugin Wandeldarlehen Lebenszyklus konkret bearbeitet werden soll. Auslöser: Bitte Spezial Lebenszyklus Fristen Form Und Zustaendigke... |
| `mandat-triage-mehrere-parallel` | Nutze dies, wenn Mandat Triage Wandeldarlehen, Mehrere Wandeldarlehen Parallel im Plugin Wandeldarlehen Lebenszyklus konkret bearbeitet werden soll. Auslöser: Bitte Mandat Triage Wandeldarlehen, Mehrere Wandeldarlehen Parallel prüfen.; E... |
| `notar-paket-parteien-erfassen` | Nutze dies, wenn Notar Paket Uebermittlung, Parteien Erfassen im Plugin Wandeldarlehen Lebenszyklus konkret bearbeitet werden soll. Auslöser: Bitte Notar Paket Uebermittlung, Parteien Erfassen prüfen.; Erstelle eine Arbeitsfassung zu Not... |
| `output-waehlen` | Nutze dies, wenn Output wählen im Plugin Wandeldarlehen Lebenszyklus konkret bearbeitet werden soll. Auslöser: Bitte Output wählen prüfen.; Erstelle eine Arbeitsfassung zu Output wählen.; Welche Normen und Nachweise brauche ich?. |
| `post-eintragung-rangruecktritt-formulieren` | Nutze dies, wenn Post Eintragung Checkliste, Rangruecktritt Formulieren im Plugin Wandeldarlehen Lebenszyklus konkret bearbeitet werden soll. Auslöser: Bitte Post Eintragung Checkliste, Rangruecktritt Formulieren prüfen.; Erstelle eine A... |
| `sacheinlagebericht-werthaltigkeit-begleitet` | Nutze dies, wenn Sacheinlagebericht Werthaltigkeit, Spezial Begleitet Erstpruefung Und Mandatsziel im Plugin Wandeldarlehen Lebenszyklus konkret bearbeitet werden soll. Auslöser: Bitte Sacheinlagebericht Werthaltigkeit, Spezial Begleitet... |
| `unterlagen-luecken` | Nutze dies, wenn Unterlagen und Lücken im Plugin Wandeldarlehen Lebenszyklus konkret bearbeitet werden soll. Auslöser: Ich lade Unterlagen hoch.; Was fehlt noch?; Bitte Dokumente sortieren.. |
| `unterzeichnung-elektronisch-wandelereignis` | Nutze dies, wenn Unterzeichnung Elektronisch Docusign, Wandelereignis Eingang im Plugin Wandeldarlehen Lebenszyklus konkret bearbeitet werden soll. Auslöser: Bitte Unterzeichnung Elektronisch Docusign, Wandelereignis Eingang prüfen.; Ers... |
| `vertraulichkeit-sprachklausel` | Nutze dies, wenn Vertraulichkeit Und Sprachklausel, Beurkundungserfordernis Prüfung im Plugin Wandeldarlehen Lebenszyklus konkret bearbeitet werden soll. Auslöser: Bitte Vertraulichkeit Und Sprachklausel, Beurkundungserfordernis Prüfung... |
| `wandeldarlehens-wandelereignisse` | Nutze dies, wenn Spezial Wandeldarlehens Dokumentenmatrix Und Lueckenliste, Spezial Wandelereignisse Zahlen Schwellen Und Berechnung im Plugin Wandeldarlehen Lebenszyklus konkret bearbeitet werden soll. Auslöser: Bitte Spezial Wandeldarl... |
| `wandelereignis-trigger-wandlung-kommunikation` | Nutze dies, wenn Wandelereignis Trigger Dispatcher, Wandlung Kommunikation Paketverteilung im Plugin Wandeldarlehen Lebenszyklus konkret bearbeitet werden soll. Auslöser: Bitte Wandelereignis Trigger Dispatcher, Wandlung Kommunikation Pa... |
| `wandlungsausloeser-cap-textform-vs` | Nutze dies, wenn Spezial Wandlungsausloeser Cap Und Discount, Textform Vs Schriftform Vs Notariell im Plugin Wandeldarlehen Lebenszyklus konkret bearbeitet werden soll. Auslöser: Bitte Spezial Wandlungsausloeser Cap Und Discount, Textfor... |
| `wandlungsausschluss-wandlungsmechanik` | Nutze dies, wenn Wandlungsausschluss Prüfung, Wandlungsmechanik Konzipieren im Plugin Wandeldarlehen Lebenszyklus konkret bearbeitet werden soll. Auslöser: Bitte Wandlungsausschluss Prüfung, Wandlungsmechanik Konzipieren prüfen.; Erstell... |
| `wandlungspreis-wandlungspruefung-trigger` | Nutze dies, wenn Wandlungspreis Berechnung, Wandlungspruefung Trigger Liquidation im Plugin Wandeldarlehen Lebenszyklus konkret bearbeitet werden soll. Auslöser: Bitte Wandlungspreis Berechnung, Wandlungspruefung Trigger Liquidation prüf... |
| `wandlungspruefung-trigger` | Nutze dies, wenn Wandlungspruefung Trigger Maturity, Wandlungspruefung Trigger Qualified Financing im Plugin Wandeldarlehen Lebenszyklus konkret bearbeitet werden soll. Auslöser: Bitte Wandlungspruefung Trigger Maturity, Wandlungspruefun... |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
