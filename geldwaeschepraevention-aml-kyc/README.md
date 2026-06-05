# Geldwäscheprävention, AML und KYC

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`geldwaeschepraevention-aml-kyc`) | [`geldwaeschepraevention-aml-kyc.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/geldwaeschepraevention-aml-kyc.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **Kanzlei Sandhof & Partner — AML/KYC-Versäumnisse Amrum — Strafverteidigung** (`aml-kyc-immobilienkanzlei-sandhof-amrum-russisches-vermoegen`) | [Gesamt-PDF lesen](../testakten/aml-kyc-immobilienkanzlei-sandhof-amrum-russisches-vermoegen/gesamt-pdf/aml-kyc-immobilienkanzlei-sandhof-amrum-russisches-vermoegen_gesamt.pdf) | [`testakte-aml-kyc-immobilienkanzlei-sandhof-amrum-russisches-vermoegen.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-aml-kyc-immobilienkanzlei-sandhof-amrum-russisches-vermoegen.zip) |
| **Akte Geldwäscheprävention, AML und KYC: Musterholding GmbH** (`geldwaesche-aml-kyc-musterholding`) | [Gesamt-PDF lesen](../testakten/geldwaesche-aml-kyc-musterholding/gesamt-pdf/geldwaesche-aml-kyc-musterholding_gesamt.pdf) | [`testakte-geldwaesche-aml-kyc-musterholding.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-geldwaesche-aml-kyc-musterholding.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

Großes, freistehendes Plugin für Geldwäscheprävention, AML/CFT, KYC, GwG-Risikomanagement, wirtschaftlich Berechtigte, PEP, Sanktionsscreening, Verdachtsmeldungen, Transparenzregister, interne Sicherungsmaßnahmen, Schulung, Audit, Behördenverfahren, Bußgeld und Reputationskrisen.

Dieses Plugin ist **vollständig freistehend**. Es benötigt keine anderen Plugins, keine externen Agenten und keine besondere Kanzlei- oder Compliance-Software. Wenn kein KYC-Tool, Screening-Tool, goAML-Zugang, Transparenzregisterzugang, CRM, ERP oder DMS angeschlossen ist, arbeitet es mit manuellen Uploads oder einem ausdrücklich markierten Simulationsmodus.

#

## Schnellstart

1. Plugin aktivieren oder ZIP aus dem Release installieren.
2. Neue Sache mit `geldwaesche-kommandocenter` starten.
3. Branche, Mandantenrolle, Kunde, Produkt, Länderbezug und Transaktion beschreiben.
4. KYC-Unterlagen, Registerdaten, Screening-Treffer, Transaktionsdaten oder Richtlinien hochladen oder simulieren.
5. Am Ende immer das Qualitätstor verlangen: Quellenstand, KYC/UBO/PEP/Sanktionen, Risikoampel, Freigabe, Stop/Freeze/Exit, Verdachtsmeldung, Aufbewahrung und nächste Schritte.

## Enthaltene Skills

- `geldwaesche-kommandocenter` - AML/KYC-Kommandocenter
- `geldwaesche-verpflichteten-check` - Verpflichtetenstatus nach GwG
- `geldwaesche-risikoanalyse-unternehmen` - Unternehmensweite Risikoanalyse
- `geldwaesche-sicherungsmassnahmen-icp` - Interne Sicherungsmaßnahmen und ICP
- `geldwaesche-kyc-onboarding` - KYC-Onboarding und Kundenprüfung
- `geldwaesche-ubo-wirtschaftlich-berechtigte` - Wirtschaftlich Berechtigte und UBO
- `geldwaesche-pep-hochrisikoland` - PEP, Hochrisikoland und verstärkte Sorgfalt
- `geldwaesche-sanktionsscreening` - Sanktionslistenprüfung und Embargoabgleich
- `geldwaesche-transaktionsmonitoring` - Transaktionsmonitoring und Red Flags
- `geldwaesche-verdachtsmeldung-fiu-goaml` - Verdachtsmeldung an FIU/goAML
- `geldwaesche-transaktionsstopp-freeze` - Transaktionsstopp, Freeze und Exit
- `geldwaesche-transparenzregister` - Transparenzregister und Unstimmigkeitsmeldung
- `geldwaesche-immobilien-gueterhaendler` - Immobilien, Güterhandel und Nichtfinanzsektor
- `geldwaesche-krypto-zahlungsdienstleister` - Krypto, Zahlungsdienste und FinTech
- `geldwaesche-gruppenweite-compliance` - Gruppenweite Compliance und Outsourcing
- `geldwaesche-schulung-awareness` - Schulung und Awareness
- `geldwaesche-audit-internal-revision` - Audit und interne Revision
- `geldwaesche-behoerdenverfahren` - Aufsicht, Prüfung und Behördenverfahren
- `geldwaesche-bussgeld-reputation` - Bußgeld, Haftung und Reputation
- `geldwaesche-datenqualitaet-register` - Datenqualität, Register und Screening-Tools
- `geldwaesche-simulation-testlauf` - AML/KYC-Simulationsmodus

## Vorlagen

- `assets/templates/aml-kyc-mandatskarte.md` - AML/KYC-Mandatskarte
- `assets/templates/verpflichtetenstatus-check.md` - Verpflichtetenstatus-Check
- `assets/templates/unternehmens-risikoanalyse.md` - Unternehmensweite Risikoanalyse
- `assets/templates/risiko-scoring-modell.md` - Risikoscoring-Modell
- `assets/templates/kyc-onboardingbogen.md` - KYC-Onboardingbogen
- `assets/templates/ubo-ermittlungslog.md` - UBO-Ermittlungslog
- `assets/templates/pep-hochrisikoland-check.md` - PEP- und Hochrisikoland-Check
- `assets/templates/sanktionslisten-trefferlog.md` - Sanktionslisten-Trefferlog
- `assets/templates/enhanced-due-diligence-plan.md` - Enhanced-Due-Diligence-Plan
- `assets/templates/transaktionsmonitoring-alert.md` - Transaktionsmonitoring-Alertkarte
- `assets/templates/verdachtsmeldung-goaml-entwurf.md` - Verdachtsmeldung-goAML-Entwurf
- `assets/templates/transaktionsstopp-freeze-plan.md` - Transaktionsstopp- und Freeze-Plan
- `assets/templates/transparenzregister-unstimmigkeit.md` - Transparenzregister- und Unstimmigkeitslog
- `assets/templates/interne-sicherungsmassnahmen-icp.md` - Interne Sicherungsmaßnahmen und ICP
- `assets/templates/geldwaeschebeauftragter-rollenkarte.md` - Geldwäschebeauftragter-Rollenkarte
- `assets/templates/schulungsplan-awareness.md` - Schulungs- und Awarenessplan
- `assets/templates/audit-testplan.md` - Audit- und Stichprobenplan
- `assets/templates/behoerdenverfahren-fristen.md` - Behördenverfahren- und Fristenplan
- `assets/templates/bussgeld-remediation-plan.md` - Bußgeld- und Remediationplan
- `assets/templates/presse-qanda-reputation.md` - Presse-Q&A und Reputationskarte
- `assets/templates/datenqualitaet-registerabgleich.md` - Datenqualitäts- und Registerabgleich
- `assets/templates/simulatormodus-tageslauf.md` - AML/KYC-Simulationstag

## Offizielle Startquellen

- [GwG auf gesetze-im-internet](https://www.gesetze-im-internet.de/gwg_2017/)
- [GwG § 5 Risikoanalyse](https://www.gesetze-im-internet.de/gwg_2017/__5.html)
- [GwG § 10 Allgemeine Sorgfaltspflichten](https://www.gesetze-im-internet.de/gwg_2017/__10.html)
- [GwG § 43 Meldepflicht](https://www.gesetze-im-internet.de/gwg_2017/__43.html)
- [BaFin Geldwäscheprävention und AuA](https://www.bafin.de/DE/Aufsicht/Geldwaeschepraevention/Rechtsquellen/BaFin_Vorgaben/BaFin_Vorgaben_node.html)
- [FIU goAML Portal](https://goaml.fiu.bund.de/home)
- [Zoll/FIU Verdachtsmeldungen](https://www.zoll.de/DE/FIU/Fachliche-Informationen/Verdachtsmeldungen/verdachtsmeldungen_node.html)
- [Transparenzregister](https://www.transparenzregister.de/treg/ueberuns)
- [EU-Sanktionsressourcen](https://finance.ec.europa.eu/eu-and-world/sanctions-restrictive-measures/overview-sanctions-and-related-resources_en)
- [AMLA](https://www.amla.europa.eu/about-amla_en)
- [FATF Risk-Based Approach](https://www.fatf-gafi.org/en/publications/Fatfrecommendations/Risk-based-approach-banking-sector.html)

## Freistehende Leitplanken

- Keine KYC-Freigabe ohne dokumentierte Identifizierung, wirtschaftlich Berechtigte, Zweck, Risiko und offene Nachweise.
- Keine Sanktionsfreigabe ohne aktuelle Quellenprüfung, Alias-, Eigentums- und Kontrollprüfung.
- Keine Verdachtsmeldung ohne Sachverhaltskern, Belegliste, interne Freigabe und Dokumentation der Entscheidungsgründe.
- Keine Fortführung einer Transaktion, wenn Mittelherkunft, Sanktionshit oder Verdachtslage ungeklärt bleibt.
- Keine starren Rechtsannahmen: GwG, BaFin-/Länderhinweise, FIU/goAML, Transparenzregister, EU-Sanktionen, AMLA und FATF werden mit Abrufdatum geführt.
- Keine echten Mandats- oder Kundendaten in ungeprüfte Cloud- oder KI-Umgebungen.

<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 24 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `allgemein-workflow-chronologie-workflow-fristen` | Allgemein, Workflow Chronologie Und Belegmatrix, Workflow Fristen Und Risikoampel: Allgemein; Workflow Chronologie Und Belegmatrix; Workflow Fristen Und Risikoampel. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmus... |
| `geldwaesche-audit-internal-datenqualitaet-register-immobilien` | Geldwaesche Audit Internal Revision, Geldwaesche Datenqualitaet Register, Geldwaesche Immobilien Gueterhaendler: Geldwaesche Audit Internal Revision; Geldwaesche Datenqualitaet Register; Geldwaesche Immobilien Gueterhaendler. Führt Intak... |
| `geldwaesche-krypto-zahlungsdienstleister-kyc-onboarding` | Geldwaesche Kommandocenter, Geldwaesche Krypto Zahlungsdienstleister, Geldwaesche Kyc Onboarding: Geldwaesche Kommandocenter; Geldwaesche Krypto Zahlungsdienstleister; Geldwaesche Kyc Onboarding. Führt Intake, Prüfroutine, Normen-/Quelle... |
| `geldwaesche-pep-hochrisikoland-risikoanalyse-unternehmen` | Geldwaesche Pep Hochrisikoland, Geldwaesche Risikoanalyse Unternehmen, Geldwaesche Schulung Awareness: Geldwaesche Pep Hochrisikoland; Geldwaesche Risikoanalyse Unternehmen; Geldwaesche Schulung Awareness. Führt Intake, Prüfroutine, Norm... |
| `geldwaesche-sicherungsmassnahmen-geldwaesche-simulation` | Geldwaesche Sicherungsmassnahmen Icp, Geldwaesche Simulation Testlauf, Geldwaesche Transaktionsmonitoring: Geldwaesche Sicherungsmassnahmen Icp; Geldwaesche Simulation Testlauf; Geldwaesche Transaktionsmonitoring. Führt Intake, Prüfrouti... |
| `geldwaesche-transaktionsstopp-freeze-transparenzregister-ubo` | Geldwaesche Transaktionsstopp Freeze, Geldwaesche Transparenzregister, Geldwaesche Ubo Wirtschaftlich Berechtigte: Geldwaesche Transaktionsstopp Freeze; Geldwaesche Transparenzregister; Geldwaesche Ubo Wirtschaftlich Berechtigte. Führt I... |
| `geldwaesche-verdachtsmeldung-geldwaesche-verpflichteten` | Geldwaesche Verdachtsmeldung Fiu Goaml, Geldwaesche Verpflichteten Check, Spezial Awareness Zahlen Schwellen Und Berechnung: Geldwaesche Verdachtsmeldung Fiu Goaml; Geldwaesche Verpflichteten Check; Spezial Awareness Zahlen Schwellen Und... |
| `goaml-gwg-spezial-kommandocenter` | Spezial Goaml Risikoampel Und Gegenargumente, Spezial Gwg Tatbestand Beweis Und Belege, Spezial Kommandocenter Compliance Dokumentation Und Akte: Spezial Goaml Risikoampel Und Gegenargumente; Spezial Gwg Tatbestand Beweis Und Belege; Spe... |
| `livecheck-red-risikoanalyse-verdachtsmeldeweiche-simulation` | Spezial Livecheck Red Team Und Qualitaetskontrolle, Spezial Risikoanalyse Und Verdachtsmeldeweiche, Spezial Simulation Mandantenkommunikation Entscheidungsvorlage: Spezial Livecheck Red Team Und Qualitaetskontrolle; Spezial Risikoanalyse... |
| `onboarding-bauleiter-trade-based-verdachtsmeldung-fiu` | Aml Kyc Onboarding Bauleiter, Aml Trade Based Money Laundering Spezial, Aml Verdachtsmeldung Fiu Leitfaden: Aml Kyc Onboarding Bauleiter; Aml Trade Based Money Laundering Spezial; Aml Verdachtsmeldung Fiu Leitfaden. Führt Intake, Prüfrou... |
| `risikoanalyse-geldwaesche-bussgeld-geldwaesche` | Spezial Risikoanalyse Fristen Form Und Zustaendigkeit, Geldwaesche Bussgeld Reputation, Geldwaesche Sanktionsscreening: Spezial Risikoanalyse Fristen Form Und Zustaendigkeit; Geldwaesche Bussgeld Reputation; Geldwaesche Sanktionsscreenin... |
| `sanktionen-geldwaesche-gruppenweite-aml-kryptotransaktionen` | Spezial Sanktionen Dokumentenmatrix Und Lueckenliste, Geldwaesche Gruppenweite Compliance, Aml Kryptotransaktionen Mica Spezial: Spezial Sanktionen Dokumentenmatrix Und Lueckenliste; Geldwaesche Gruppenweite Compliance; Aml Kryptotransak... |
| `sonderfall-edge-geldwaesche-geldwaeschepraevention` | Spezial Chronologie Sonderfall Und Edge Case, Spezial Geldwaesche Verhandlung Vergleich Und Eskalation, Spezial Geldwaeschepraevention Erstpruefung Und Mandatsziel: Spezial Chronologie Sonderfall Und Edge Case; Spezial Geldwaesche Verhan... |
| `spezial-rechtsquellen-formular-portal-und-einreichung` | Rechtsquellen: Formular, Portal und Einreichungslogik im Plugin geldwaeschepraevention aml kyc; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Standardprüfung. |
| `spezial-schulung-livequellen-und-rechtsprechungscheck` | Schulung: Livequellen- und Rechtsprechungscheck im Plugin geldwaeschepraevention aml kyc; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Standardprüfung. |
| `testlauf-beweislast-transaktionsmonitoring-international` | Spezial Testlauf Beweislast Und Darlegungslast, Spezial Transaktionsmonitoring International Schnittstellen, Spezial Transparenzregister Behörden Gericht Und Registerweg: Spezial Testlauf Beweislast Und Darlegungslast; Spezial Transaktio... |
| `verdachtsmeldung-interessen` | Spezial Verdachtsmeldung Mehrparteien Konflikt Und Interessen: Spezial Verdachtsmeldung Mehrparteien Konflikt Und Interessen. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zusammen. |
| `workflow-anschluss-skills-router` | Anschluss-Skills Router im Plugin geldwaeschepraevention-aml-kyc: schlägt nach der ersten Prüfung die passenden Spezialskills aus demselben Plugin vor. |
| `workflow-dokumentenintake` | Dokumentenintake im Plugin geldwaeschepraevention-aml-kyc: liest Uploads, sortiert Dokumentarten, markiert Fristen und baut eine knappe Arbeitsakte. |
| `workflow-kaltstart-und-routing` | Kaltstart und Routing im Plugin geldwaeschepraevention-aml-kyc: führt vom ersten Satz oder Dokument in den passenden Arbeitsweg, erkennt Rolle, Ziel, Risiko und Anschluss-Skills. |
| `workflow-output-waehlen` | Output wählen im Plugin geldwaeschepraevention-aml-kyc: entscheidet zwischen Memo, Schriftsatz, Tabelle, Brief, Checkliste, Vermerk, Redline oder Mandantenübersetzung. |
| `workflow-rechtsquellen-livecheck` | Rechtsquellen-Livecheck im Plugin geldwaeschepraevention-aml-kyc: zwingt vor tragenden Aussagen zum aktuellen Quellencheck bei Gesetzen, Behörden, Gerichten und Formularen. |
| `workflow-redteam-geldwaesche-behoerdenverfahren` | Workflow Redteam Qualitygate, Geldwaesche Behoerdenverfahren, Spezial Behoerdenverfahren Schriftsatz Brief Und Memo Bausteine: Workflow Redteam Qualitygate; Geldwaesche Behoerdenverfahren; Spezial Behoerdenverfahren Schriftsatz Brief Und... |
| `workflow-unterlagen-lueckenliste` | Unterlagen- und Lückenliste im Plugin geldwaeschepraevention-aml-kyc: erstellt eine präzise Nachforderungsliste statt allgemeiner Fragebögen. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
