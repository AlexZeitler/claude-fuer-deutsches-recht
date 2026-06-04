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
| `kompendium-01-allgemein-bis-workflow-fristen-und` | geldwaeschepraevention-aml-kyc: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Allgemein, Chronologie Und Belegmatrix, Fristen Und Risikoampel; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qua... |
| `kompendium-02-workflow-redteam-qua-bis-spezial-behoerdenver` | geldwaeschepraevention-aml-kyc: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Redteam Qualitygate, Geldwaesche Behoerdenverfahren, Behoerdenverfahren Schriftsatz Brief Und Memo Bausteine; mit Intake, Prüfroutine, Normen-/Qu... |
| `kompendium-03-spezial-risikoanalys-bis-geldwaesche-sanktion` | geldwaeschepraevention-aml-kyc: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Risikoanalyse Fristen Form Und Zustaendigkeit, Geldwaesche Bussgeld Reputation, Geldwaesche Sanktionsscreening; mit Intake, Prüfroutine, Normen-/... |
| `kompendium-04-spezial-sanktionen-d-bis-aml-kryptotransaktio` | geldwaeschepraevention-aml-kyc: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Sanktionen Dokumentenmatrix Und Lueckenliste, Geldwaesche Gruppenweite Compliance, Aml Kryptotransaktionen Mica Spezial; mit Intake, Prüfroutine,... |
| `kompendium-05-aml-kyc-onboarding-b-bis-aml-verdachtsmeldung` | geldwaeschepraevention-aml-kyc: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Aml Kyc Onboarding Bauleiter, Aml Trade Based Money Laundering Spezial, Aml Verdachtsmeldung Fiu Leitfaden; mit Intake, Prüfroutine, Normen-/Quel... |
| `kompendium-06-geldwaesche-audit-in-bis-geldwaesche-immobili` | geldwaeschepraevention-aml-kyc: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Geldwaesche Audit Internal Revision, Geldwaesche Datenqualitaet Register, Geldwaesche Immobilien Gueterhaendler; mit Intake, Prüfroutine, Normen-... |
| `kompendium-07-geldwaesche-kommando-bis-geldwaesche-kyc-onbo` | geldwaeschepraevention-aml-kyc: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Geldwaesche Kommandocenter, Geldwaesche Krypto Zahlungsdienstleister, Geldwaesche Kyc Onboarding; mit Intake, Prüfroutine, Normen-/Quellenradar,... |
| `kompendium-08-geldwaesche-pep-hoch-bis-geldwaesche-schulung` | geldwaeschepraevention-aml-kyc: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Geldwaesche Pep Hochrisikoland, Geldwaesche Risikoanalyse Unternehmen, Geldwaesche Schulung Awareness; mit Intake, Prüfroutine, Normen-/Quellenra... |
| `kompendium-09-geldwaesche-sicherun-bis-geldwaesche-transakt` | geldwaeschepraevention-aml-kyc: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Geldwaesche Sicherungsmassnahmen Icp, Geldwaesche Simulation Testlauf, Geldwaesche Transaktionsmonitoring; mit Intake, Prüfroutine, Normen-/Quell... |
| `kompendium-10-geldwaesche-transakt-bis-geldwaesche-ubo-wirt` | geldwaeschepraevention-aml-kyc: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Geldwaesche Transaktionsstopp Freeze, Geldwaesche Transparenzregister, Geldwaesche Ubo Wirtschaftlich Berechtigte; mit Intake, Prüfroutine, Norme... |
| `kompendium-11-geldwaesche-verdacht-bis-spezial-awareness-za` | geldwaeschepraevention-aml-kyc: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Geldwaesche Verdachtsmeldung Fiu Goaml, Geldwaesche Verpflichteten Check, Awareness Zahlen Schwellen Und Berechnung; mit Intake, Prüfroutine, Nor... |
| `kompendium-12-spezial-chronologie-bis-spezial-geldwaeschep` | geldwaeschepraevention-aml-kyc: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Chronologie Sonderfall Und Edge Case, Geldwaesche Verhandlung Vergleich Und Eskalation, Geldwaeschepraevention Erstpruefung Und Mandatsziel; mit... |
| `kompendium-13-spezial-goaml-risiko-bis-spezial-kommandocent` | geldwaeschepraevention-aml-kyc: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Goaml Risikoampel Und Gegenargumente, Gwg Tatbestand Beweis Und Belege, Kommandocenter Compliance Dokumentation Und Akte; mit Intake, Prüfroutine... |
| `kompendium-14-spezial-livecheck-re-bis-spezial-simulation-m` | geldwaeschepraevention-aml-kyc: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Livecheck Red Team Und Qualitaetskontrolle, Risikoanalyse Und Verdachtsmeldeweiche, Simulation Mandantenkommunikation Entscheidungsvorlage; mit I... |
| `kompendium-15-spezial-testlauf-bew-bis-spezial-transparenzr` | geldwaeschepraevention-aml-kyc: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Testlauf Beweislast Und Darlegungslast, Transaktionsmonitoring International Schnittstellen, Transparenzregister Behoerden Gericht Und Registerwe... |
| `kompendium-16-spezial-verdachtsmel-bis-spezial-verdachtsmel` | geldwaeschepraevention-aml-kyc: eigenständiger Arbeits-Skill zu Verdachtsmeldung Mehrparteien Konflikt Und Interessen; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck. |
| `spezial-rechtsquellen-formular-portal-und-einreichung` | Rechtsquellen: Formular, Portal und Einreichungslogik im Plugin geldwaeschepraevention aml kyc; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Standardprüfung. |
| `spezial-schulung-livequellen-und-rechtsprechungscheck` | Schulung: Livequellen- und Rechtsprechungscheck im Plugin geldwaeschepraevention aml kyc; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Standardprüfung. |
| `workflow-anschluss-skills-router` | Anschluss-Skills Router im Plugin geldwaeschepraevention-aml-kyc: schlägt nach der ersten Prüfung die passenden Spezialskills aus demselben Plugin vor. |
| `workflow-dokumentenintake` | Dokumentenintake im Plugin geldwaeschepraevention-aml-kyc: liest Uploads, sortiert Dokumentarten, markiert Fristen und baut eine knappe Arbeitsakte. |
| `workflow-kaltstart-und-routing` | Kaltstart und Routing im Plugin geldwaeschepraevention-aml-kyc: führt vom ersten Satz oder Dokument in den passenden Arbeitsweg, erkennt Rolle, Ziel, Risiko und Anschluss-Skills. |
| `workflow-output-waehlen` | Output wählen im Plugin geldwaeschepraevention-aml-kyc: entscheidet zwischen Memo, Schriftsatz, Tabelle, Brief, Checkliste, Vermerk, Redline oder Mandantenübersetzung. |
| `workflow-rechtsquellen-livecheck` | Rechtsquellen-Livecheck im Plugin geldwaeschepraevention-aml-kyc: zwingt vor tragenden Aussagen zum aktuellen Quellencheck bei Gesetzen, Behörden, Gerichten und Formularen. |
| `workflow-unterlagen-lueckenliste` | Unterlagen- und Lückenliste im Plugin geldwaeschepraevention-aml-kyc: erstellt eine präzise Nachforderungsliste statt allgemeiner Fragebögen. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
