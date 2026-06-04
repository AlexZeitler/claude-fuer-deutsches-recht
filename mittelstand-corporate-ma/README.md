# Mittelständische Kanzlei – Corporate/M&A-Plugin

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`mittelstand-corporate-ma`) | [`mittelstand-corporate-ma.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/mittelstand-corporate-ma.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **Share Deal Pellbach Werkzeugbau GmbH & Co. KG — Familiennachfolge mit PE-Beteiligung, Earn-Out, MAC** (`share-deal-familienunternehmen-pellbach-werkzeugbau-passau-nachfolge`) | [Gesamt-PDF lesen](../testakten/share-deal-familienunternehmen-pellbach-werkzeugbau-passau-nachfolge/gesamt-pdf/share-deal-familienunternehmen-pellbach-werkzeugbau-passau-nachfolge_gesamt.pdf) | [`testakte-share-deal-familienunternehmen-pellbach-werkzeugbau-passau-nachfolge.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-share-deal-familienunternehmen-pellbach-werkzeugbau-passau-nachfolge.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

Technischer Plugin-Name: `mittelstand-corporate-ma`.

Dies ist das freistehende Corporate/M&A-Plugin für mittelständische Kanzleien für den gesamten Transaktionslebenszyklus: Intake, Aktenanlage, Konflikt-/GwG-/Sanktionscheck, Datenraum, Due Diligence, Tabellenreview, Liquiditätsvorschau, Insolvenzreife, Q&A, SPA/APA, Disclosure Schedules, Signing, Closing, W&I, Public M&A, Fusionskontrolle, Investitionskontrolle, Umwandlungsrecht, Umwandlungssteuerrecht, KG/GmbH & Co. KG, StaRUG, Insolvenzplan, Distressed M&A, Board Paper, PMI, Deal-PMO, Billing, XRechnung/ZUGFeRD-Vorbereitung, GoBD-Protokoll und Closing Bible.

**Wichtig:** Dieses Plugin funktioniert vollständig allein. Alle Kernabläufe, Hilfstabellen, Prüfungsschablonen und Workflows liegen im Plugin selbst; für die hier beschriebenen M&A-Workflows ist keine Zusatzinstallation nötig.

## Installation

1. ZIP herunterladen.
2. Claude Code oder Claude Desktop/Cowork öffnen.
3. **Customize Plugins** bzw. **Personal plugins** öffnen.
4. **Install from .zip** wählen und `mittelstand-corporate-ma.zip` hochladen.
5. Mit einem konkreten Deal-Auftrag starten, zum Beispiel: `Starte das Corporate-M&A-Kommandocenter für diesen Datenraum.`

Nicht das komplette Repository-ZIP hochladen. Das Plugin-ZIP muss im Root direkt `.claude-plugin/plugin.json`, `skills/`, `assets/` und `references/` enthalten.

## Freistehende Kernmodule

| Modul | Enthaltene Funktion |
| --- | --- |
| Aktenanlage | Deal-Akte, Aktenzeichen, Parteienregister, Ordnerplan, Datenraumspiegel, Closing-Bible-Grundgerüst. |
| Tabellenreview | Interner Review-Würfel für Dokumente, Datenpunkte, Tabellen, Formeln und Perspektiven. |
| Liquiditätsvorschau | 3-Wochen-Prüfung, 13-Wochen-Cash-Bridge, Runway, OPOS, Bankdaten, Distressed-M&A-Ampel. |
| Insolvenzreife | § 17, § 18, § 19 InsO, § 15a InsO, StaRUG-Frühwarnung, Deal-Auswirkungen und Senior-Review-Gate. |
| Fristen/CP | Signing, Closing, Q&A, Regulatory, Register, Board, Ordinary Course, Long Stop Date und PMI. |
| Billing/E-Rechnung | Narratives, Workstream-Rechnung, GoBD-Protokoll, XRechnung-Datenblock, ZUGFeRD-Prüfpaket. |
| Schreibcanvas | Freundlicher Qualitätsbegleiter für SPA, DD-Report, Board Paper, Registertext und Mandatskommunikation. |

## Skill-Landkarte

| Skill | Zweck |
| --- | --- |
| `mittelstand-corporate-ma-automation-monitoring` | Automationen und Monitoring: Entwirft Monitore für Datenraum-Neuzugänge, Q&A, CP-Deadlines, Registerupdates, News, MAR-Signale und PMI-Aufgaben. |
| `mittelstand-corporate-ma-billing-narratives` | Mittelstandsmandat Billing Narratives: erstellt deal-taugliche Time Narratives, Phasenbudgets, Workstream-Rechnungen, Cap/Success-Fee-Hinweise und Matter-Controlling. |
| `mittelstand-corporate-ma-board-paper-business-judgment` | Board Paper und Business Judgment: Erstellt Entscheidungsunterlagen für Vorstand/Geschäftsführung/Aufsichtsrat mit Informationsgrundlage, Alternativen, Risiken und KI-Einsatztransparenz. |
| `mittelstand-corporate-ma-closing-bible-archiv` | Closing Bible und Archiv: Erstellt Closing Bible, Versionierung, Signaturketten, Registerbelege und Deal-Archiv. |
| `mittelstand-corporate-ma-conflict-gwg-sanctions` | Konflikt-, GwG- und Sanktionscheck: Führt Annahmeprüfung für Corporate/M&A: Interessenkonflikte, wirtschaftlich Berechtigte, Sanktionen, PEP, Mittelherkunft, Sektor- und Länder-Risiken. |
| `mittelstand-corporate-ma-datenqualitaet-xai-qualitaetskontrolle` | Datenqualität und XAI-Qualitätskontrolle: Sichert KI-gestützte M&A-Arbeit gegen Halluzination, Bias, Black-Box-Probleme und schlechte Datenqualität ab. |
| `mittelstand-corporate-ma-datenraum-aufbau` | Datenraum-Aufbau: Strukturiert und bestückt virtuelle Datenräume für Private M&A, Public M&A, Carve-out und Distressed-Prozesse. |
| `mittelstand-corporate-ma-datenraum-gap-clean-room` | Datenraum-Gap-Analyse und Clean Room: Prüft Datenraum, Teaser, IM, IRL und Disclosure-Konzept auf Lücken, Widersprüche, Dubletten und Clean-Room-Bedarf. |
| `mittelstand-corporate-ma-deal-intake` | Deal-Intake: Strukturiert neue Transaktionsmandate aus E-Mail, Teaser, NDA, Term Sheet, Teams-Message, Screenshot oder Datenraum-Einladung. |
| `mittelstand-corporate-ma-deal-team-staffing` | Deal-Team und Staffing: Plant Workstreams, Rollen, Kapazitäten, Review-Level und Eskalationswege für große Transaktionen. |
| `mittelstand-corporate-ma-disclosure-schedules` | Disclosure Schedules: Leitet Disclosure Schedules aus Datenraum, DD-Findings, Q&A und SPA-Garantien ab. |
| `mittelstand-corporate-ma-distressed-ma` | Distressed M&A: führt Unternehmenskauf in Krise, vorläufiger Insolvenz, StaRUG, Insolvenzplan oder Asset Deal aus der Insolvenz mit Liquiditäts- und Closing-Fokus. |
| `mittelstand-corporate-ma-due-diligence-commercial-contracts` | Kommerzielle Vertrags-DD: Prüft Kunden-, Lieferanten-, Händler-, SaaS-, Lizenz- und Materialverträge auf Change of Control, Kündigung, Exklusivität, Haftung, IP und Preisrisiken. |
| `mittelstand-corporate-ma-due-diligence-legal` | Legal Due Diligence: Führt standardisierte Legal Due Diligence mit Findings, Materiality, Quellenbelegen, Human-in-the-loop und Red-Flag-Report. |
| `mittelstand-corporate-ma-due-diligence-reporting` | DD Reporting und Legal Fact Book: Erstellt Red-Flag-Report, Full DD Report, Legal Fact Book, Executive Summary und Issues-to-SPA-Mapping. |
| `mittelstand-corporate-ma-expert-calls-transkripte` | Expert Calls und Transkripte: Bereitet Management Presentations, Expert Calls und Transkripte für DD und SPA-Verhandlung auf. |
| `mittelstand-corporate-ma-fair-disclosure-knowledge` | Fair Disclosure und Knowledge: Prüft Wissens-, Kenntnis-, Fair-Disclosure- und Aktenwissen-Klauseln im Lichte von KI-gestützter Datenraumprüfung. |
| `mittelstand-corporate-ma-freundlicher-copilot` | Freundlicher Deal-Copilot: Führt junge Anwender verzeihend durch große Transaktionen, erkennt unausgesprochene Absichten und meldet sich kurz mit hilfreichen Hinweisen. |
| `mittelstand-corporate-ma-gesellschaftsrecht-register` | Corporate Housekeeping und Register: Prüft HRB/HRA, Gesellschafterlisten, Satzungen, Beschlüsse, Vollmachten, Organstellung, Transparenzregister und Corporate Approvals. |
| `mittelstand-corporate-ma-handelsregisterabruf` | Handelsregister- und Registerabruf: Führt offizielle Registerabrufe für Zielgesellschaft, Verkäufer, Erwerber, Beteiligungsketten, KG und Organstellung. |
| `mittelstand-corporate-ma-kaltstart` | Deal-Kaltstart: Nimmt Kanzlei- und Mandantenpräferenzen für Corporate/M&A auf: Dealtypen, Playbooks, Materiality, Reporting, Abrechnung, KI-Governance und Sicherheitsregeln. |
| `mittelstand-corporate-ma-kg-personengesellschaften` | KG und Personengesellschaften: Spezialworkflow für KG, GmbH & Co. KG, Fondsvehikel, Kommanditistenwechsel, Einlagen, Haftsumme und Register. |
| `mittelstand-corporate-ma-ki-governance-berufsrecht` | KI-Governance und Berufsrecht: Prüft KI-Einsatz im Transaktionsmandat unter Mandatsgeheimnis, Need-to-know, Datenschutz, KI-VO, Dienstleistereinsatz und Mandantenfreigabe. |
| `mittelstand-corporate-ma-kommandocenter` | Deal-Kommandocenter: Schnellstart für Corporate/M&A-Mandate. Erkennt aus einem Satz, Datenraum, Term Sheet oder Markup den passenden Deal-Workflow und erzeugt Deal-Karte, Ampel, Rollen und nächste Aktion. |
| `mittelstand-corporate-ma-look-and-feel` | Corporate-Cowork-Look: Definiert die sichtbare Oberfläche: sehr ruhig, edel, bläulich-silbern mit warmem Orange für Entscheidungspunkte, dichte Deal-Information statt Marketing. |
| `mittelstand-corporate-ma-matter-file` | Deal-Akte: Legt die Transaktionsakte als Matter Workspace an: Struktur, Workstreams, Datenraumspiegel, Register, Q&A, SPA, Signing, Closing und PMI. |
| `mittelstand-corporate-ma-output-versand-signing` | Output, Signing und Versand: Bereitet Transaktionsoutput vor: Markups, Issues Lists, Reports, Board Papers, Signing Packs, Closing Deliverables, beA/Notar/Email-Versand. |
| `mittelstand-corporate-ma-outside-in-target-screening` | Outside-in Target Screening: Erstellt frühe Zielobjekt- und Pipeline-Analysen aus öffentlichen Informationen, Nachrichten, Registern, Finanzdaten und Branchenhinweisen. |
| `mittelstand-corporate-ma-post-closing-integration` | Post-Closing Integration: Übersetzt DD-Findings, SPA-Pflichten und Synergieannahmen in einen PMI-Plan. |
| `mittelstand-corporate-ma-public-ma-kapitalmarkt-mar` | Public M&A, Kapitalmarkt und MAR: Begleitet börsennotierte Transaktionen: WpUEG-Unterlagen, Ad-hoc-Prüfung, Insiderlisten, Stellungnahmen und Marktgerüchte. |
| `mittelstand-corporate-ma-qa-information-requests` | Q&A und Information Requests: Erzeugt und verwaltet Q&A-Prozess, Information Request Lists, Follow-ups und Antwortqualität. |
| `mittelstand-corporate-ma-rechtsprechungsrecherche` | Corporate-Rechtsprechungsrecherche: Sucht Rechtsprechung und amtliche Quellen für Corporate/M&A, Umwandlung, Organpflichten, Kapitalmarkt, Insolvenz und Restrukturierung. |
| `mittelstand-corporate-ma-regulatory-fdi-merger-control` | Fusionskontrolle und Investitionskontrolle: Erstellt Freigabe-Landkarte für Kartellrecht, Fusionskontrolle, AWV/FDI, Sektorregulierung und Multi-Jurisdiction-Filings. |
| `mittelstand-corporate-ma-restructuring-starug-insolvenzplan` | StaRUG und Insolvenzplan: unterstützt Restrukturierungsfälle mit Planoptionen, Gläubigerklassen, Liquiditätsprüfung, Antragspflichten, Distressed M&A und Zeitplan. |
| `mittelstand-corporate-ma-signing-closing-conditions` | Signing, Closing und CPs: Führt Signing-to-Closing: Conditions Precedent, Ordinary Course, Bring-down, Closing Deliverables, Funds Flow und Closing Bible. |
| `mittelstand-corporate-ma-simulation-bidder-process` | Bieterprozess-Simulation: Simuliert einen beschleunigten achtstündigen Seller-side oder Buy-side M&A-Tag mit Datenraum, Q&A, Markup, CPs und Board Call. |
| `mittelstand-corporate-ma-spa-apa-entwurf` | SPA/APA-Entwurf: Erstellt und strukturiert Kaufvertragsentwürfe für Share Deal und Asset Deal aus Term Sheet, DD-Findings und Transaktionsstruktur. |
| `mittelstand-corporate-ma-steps-plan-pmo` | Deal-PMO und Steps Plan: Extrahiert aus Verträgen, DD und Gremienunterlagen konkrete Steps Plans für Pre-Signing, Signing-to-Closing und Post-Closing. |
| `mittelstand-corporate-ma-tabellenreview-3d-datenraum` | 3D-Tabellenreview im Datenraum: verbindet M&A-Datenraumprüfung mit interner Review-Matrix für Dokumente, Datenpunkte und Perspektiven Recht/Steuer/Wirtschaft. |
| `mittelstand-corporate-ma-teaser-im-processdocs` | Teaser, IM und Prozessdokumente: Unterstützt Seller-side bei Investment Teaser, Information Memorandum, NDA, Process Letter und Bieterkommunikation. |
| `mittelstand-corporate-ma-transaktionsstruktur` | Transaktionsstrukturierung: Entwickelt Strukturvarianten für Share Deal, Asset Deal, Carve-out, Joint Venture, Verschmelzung, Spaltung, Formwechsel, Roll-over und Managementbeteiligung. |
| `mittelstand-corporate-ma-translations-multijurisdictional` | Multi-Jurisdiction und Übersetzungen: Koordiniert lokale Kanzleien, Übersetzungen, Rechtsvergleich und Multi-Jurisdiction-Matrizen. |
| `mittelstand-corporate-ma-umwandlungsrecht` | Umwandlungsrecht: Bearbeitet Verschmelzung, Spaltung, Ausgliederung, Formwechsel, Einbringung und Vorfeld-Carve-outs nach Umwandlungsrecht. |
| `mittelstand-corporate-ma-umwandlungssteuerrecht` | Umwandlungssteuerrecht: Erfasst umwandlungssteuerliche Strukturfragen als Arbeitsmatrix für Steuerteam und Corporate-Team. |
| `mittelstand-corporate-ma-vertragsmarkup-key-issues` | Markup und Key Issues: Analysiert SPA/APA/NDA/Process-Letter-Markups, erstellt Key Issues Lists und Gegenmarkup-Vorschläge nach Parteiperspektive. |
| `mittelstand-corporate-ma-wi-insurance` | W&I-Versicherung: Bereitet W&I-Prozess, Underwriting, DD-Berichte, KI-DD-Transparenz und Deckungsausschlüsse vor. |
| `mittelstand-ma-aktenanlage` | Freistehende M&A-Aktenanlage: eröffnet Deal-Akte, Aktenzeichen, Parteienregister, Ordnerstruktur, Datenraumspiegel, Vertraulichkeitsstufen und Closing-Bible-Grundgerüst mit vollständig interner Arbeitslogik. |
| `mittelstand-ma-erechnung-gobd` | Freistehender Billing-, GoBD- und E-Rechnungsworkflow für M&A-Mandate: erzeugt Narratives, Workstream-Abrechnung, XRechnung-XML, ZUGFeRD-Prüfpaket und revisionssicheren Buchungsnachweis. |
| `mittelstand-ma-fristen-cp-kalender` | Freistehender Deal-Fristen- und CP-Kalender: führt Signing-, Closing-, Q&A-, Regulatory-, Register-, Board-, Ordinary-Course- und Restrukturierungsfristen im M&A-Mandat. |
| `mittelstand-ma-insolvenzreife` | Freistehender Insolvenzreife- und StaRUG-Schwellencheck für M&A: prüft Zahlungsunfähigkeit, drohende Zahlungsunfähigkeit, Überschuldung, Antragspflichten und Deal-Auswirkungen intern. |
| `mittelstand-ma-liquiditaetsvorschau` | Freistehende Liquiditätsvorschau für Corporate/M&A und Distressed M&A: prüft 3-Wochen-Liquidität, 13-Wochen-Cash-Bridge, Runway, OPOS, Bankdaten und Insolvenzschwellen intern. |
| `mittelstand-ma-schreibcanvas` | Freistehender Corporate-Schreibcanvas: begleitet SPA, Replik, Board Paper, Mandatsvereinbarung, DD-Report und Registertext mit freundlichen substanz- und belegorientierten Hinweisen. |
| `mittelstand-ma-tabellenreview` | Freistehender Tabellenreview für Corporate/M&A: prüft Dokumente, Datenpunkte, Tabellen, Formeln und Perspektiven als interne Review-Matrix mit vollständig interner Review-Logik. |

## Typische Workflows

- Buy-side: Target Screening -> NDA -> Aktenanlage -> Datenraum -> Tabellenreview -> Legal DD -> Q&A -> SPA-Markup -> Signing/Closing -> PMI.
- Sell-side: Teaser/IM -> Datenraumaufbau -> Vendor DD/Fact Book -> Bieter-Q&A -> Disclosure Schedules -> Vertragsverhandlung.
- Public M&A: Insider-/MAR-Prüfung -> Angebotsunterlage/Stellungnahme -> Kapitalmarktkommunikation -> Closing-Auflagen.
- Restrukturierung: Liquiditätsvorschau -> Insolvenzreifecheck -> StaRUG/Insolvenzplan -> Distressed M&A -> Gerichtsschritte -> Closing.
- Corporate Reorganisation: Umwandlung -> Umwandlungssteuerrecht -> Register/Notar -> Carve-out -> Closing.
- Billing: Zeitnachweise -> Narratives -> Workstream-Rechnung -> XRechnung/ZUGFeRD-Prüfpaket -> GoBD-Protokoll.

## Sicherheitsleitplanken

- Keine echte Transaktionsberatung ohne menschliche Letztprüfung.
- Keine Mandatsgeheimnisse, Insiderinformationen, Datenraumzugangsdaten oder Clean-Room-Daten in nicht freigegebene Systeme.
- KI-DD immer als `KI-gestützt`, `stichprobenvalidiert` oder `voll menschlich validiert` kennzeichnen.
- Register-, Rechtsprechungs-, Gesetzes- und Datenraumbelege müssen verifizierbar sein.
- Public M&A, MAR, WpÜG, Kartellrecht, Investitionskontrolle, Sanktionen, StaRUG, Zahlungsunfähigkeit und Überschuldung sind rote Schwellen.


<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 29 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `allgemein` | Einstieg, Schnelltriage und Workflow-Routing im Mittelstand Corporate Ma-Plugin. Fragt Rolle, Ziel, Fristen, Unterlagen, Risiken und Wunsch-Output ab, schlägt passende Spezial-Skills aus diesem Plugin vor und führt in einen klaren Arbeit... |
| `beirat-kaltstart-und-zielbild` | GmbH-Beirat im Plugin mittelstand-corporate-ma: Beirat Kaltstart Und Zielbild; konkretisierter Spezial-Workflow mit Prüfachsen, Red Flags, Varianten, Quellenhygiene und verwertbarem Output. |
| `beirat-red-team-satzung` | GmbH-Beirat im Plugin mittelstand-corporate-ma: Beirat Red Team Satzung; konkretisierter Spezial-Workflow mit Prüfachsen, Red Flags, Varianten, Quellenhygiene und verwertbarem Output. |
| `kompendium-01-mittelstand-corporat-bis-mittelstand-corporat` | mittelstand-corporate-ma: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Mittelstand Corporate Ma Rechtsprechungsrecherche, Mittelstand Ma Fristen Cp Kalender, Beirat Musterklauseln, Mittelstand Corporate Ma Spa Apa Entwurf;... |
| `kompendium-02-mittelstand-corporat-bis-mittelstand-corporat` | mittelstand-corporate-ma: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Mittelstand Corporate Ma Vertragsmarkup Key Issues, Beirat Haftung, Mittelstand Corporate Ma Billing Narratives, Mittelstand Corporate Ma Tabellenrevie... |
| `kompendium-03-mittelstand-corporat-bis-beirat-abgrenzung-au` | mittelstand-corporate-ma: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Mittelstand Corporate Ma Umwandlungssteuerrecht, Mittelstand Ma Tabellenreview, Earn Out Bei Mittelstandsverkauf, Beirat Abgrenzung Aufsichtsrat; mit I... |
| `kompendium-04-beirat-amtszeit-und-bis-beirat-beschlussfass` | mittelstand-corporate-ma: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Beirat Amtszeit Und Rotation, Beirat Bank Und Sanierung, Beirat Beratungsfunktion, Beirat Beschlussfassung; mit Intake, Prüfroutine, Normen-/Quellenrad... |
| `kompendium-05-beirat-beschlussmaen-bis-beirat-compliance-un` | mittelstand-corporate-ma: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Beirat Beschlussmaengel, Beirat Bestellung Und Abberufung, Beirat Budget Und Businessplan, Beirat Compliance Und Internal Investigation; mit Intake, Pr... |
| `kompendium-06-beirat-datenschutz-u-bis-beirat-fakultativer` | mittelstand-corporate-ma: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Beirat Datenschutz Und Ki, Beirat Deadlock Mechanik, Beirat Entscheidungsbefugnisse, Beirat Fakultativer Aufsichtsrat 52 Gmbhg; mit Intake, Prüfroutine... |
| `kompendium-07-beirat-familiengesel-bis-beirat-geschaeftsord` | mittelstand-corporate-ma: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Beirat Familiengesellschaft, Beirat Geschaeftsfuehrerabberufung, Beirat Geschaeftsfuehrerbestellung, Beirat Geschaeftsordnung; mit Intake, Prüfroutine,... |
| `kompendium-08-beirat-immobilien-un-bis-beirat-interessenkon` | mittelstand-corporate-ma: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Beirat Immobilien Und Investitionen, Beirat Informationsrechte, Beirat Insolvenznaehe, Beirat Interessenkonflikte; mit Intake, Prüfroutine, Normen-/Que... |
| `kompendium-09-beirat-katalog-wesen-bis-beirat-nachfolge` | mittelstand-corporate-ma: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Beirat Katalog Wesentlicher Geschaefte, Beirat Kontrollfunktion, Beirat Mitbestimmung Abgrenzung, Beirat Nachfolge; mit Intake, Prüfroutine, Normen-/Qu... |
| `kompendium-10-beirat-private-equit-bis-beirat-sitzung-und-p` | mittelstand-corporate-ma: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Beirat Private Equity Investor, Beirat Register Und Notar, Beirat Satzungsgrundlage, Beirat Sitzung Und Protokoll; mit Intake, Prüfroutine, Normen-/Que... |
| `kompendium-11-beirat-startup-inves-bis-beirat-verguetung` | mittelstand-corporate-ma: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Beirat Startup Investor Director, Beirat Streit Gesellschafter, Beirat Transaktionen Ma, Beirat Verguetung; mit Intake, Prüfroutine, Normen-/Quellenrad... |
| `kompendium-12-beirat-verschwiegenh-bis-mittelstand-corporat` | mittelstand-corporate-ma: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Beirat Verschwiegenheit, Beirat Veto Rechte, Beirat Zustimmungsvorbehalte, Mittelstand Corporate Ma Automation Monitoring; mit Intake, Prüfroutine, Nor... |
| `kompendium-13-mittelstand-corporat-bis-mittelstand-corporat` | mittelstand-corporate-ma: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Mittelstand Corporate Ma Board Paper Business Judgment, Mittelstand Corporate Ma Closing Bible Archiv, Mittelstand Corporate Ma Conflict Gwg Sanctions,... |
| `kompendium-14-mittelstand-corporat-bis-mittelstand-corporat` | mittelstand-corporate-ma: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Mittelstand Corporate Ma Datenraum Aufbau, Mittelstand Corporate Ma Datenraum Gap Clean Room, Mittelstand Corporate Ma Deal Intake, Mittelstand Corpora... |
| `kompendium-15-mittelstand-corporat-bis-mittelstand-corporat` | mittelstand-corporate-ma: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Mittelstand Corporate Ma Disclosure Schedules, Mittelstand Corporate Ma Distressed Ma, Mittelstand Corporate Ma Due Diligence Commercial Contracts, Mit... |
| `kompendium-16-mittelstand-corporat-bis-mittelstand-corporat` | mittelstand-corporate-ma: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Mittelstand Corporate Ma Due Diligence Reporting, Mittelstand Corporate Ma Expert Calls Transkripte, Mittelstand Corporate Ma Fair Disclosure Knowledge... |
| `kompendium-17-mittelstand-corporat-bis-mittelstand-corporat` | mittelstand-corporate-ma: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Mittelstand Corporate Ma Gesellschaftsrecht Register, Mittelstand Corporate Ma Handelsregisterabruf, Mittelstand Corporate Ma Kg Personengesellschaften... |
| `kompendium-18-mittelstand-corporat-bis-mittelstand-corporat` | mittelstand-corporate-ma: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Mittelstand Corporate Ma Kommandocenter, Mittelstand Corporate Ma Look And Feel, Mittelstand Corporate Ma Matter File, Mittelstand Corporate Ma Outside... |
| `kompendium-19-mittelstand-corporat-bis-mittelstand-corporat` | mittelstand-corporate-ma: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Mittelstand Corporate Ma Post Closing Integration, Mittelstand Corporate Ma Public Ma Kapitalmarkt Mar, Mittelstand Corporate Ma Qa Information Request... |
| `kompendium-20-mittelstand-corporat-bis-mittelstand-corporat` | mittelstand-corporate-ma: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Mittelstand Corporate Ma Restructuring Starug Insolvenzplan, Mittelstand Corporate Ma Signing Closing Conditions, Mittelstand Corporate Ma Simulation B... |
| `kompendium-21-mittelstand-corporat-bis-mittelstand-corporat` | mittelstand-corporate-ma: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Mittelstand Corporate Ma Teaser Im Processdocs, Mittelstand Corporate Ma Transaktionsstruktur, Mittelstand Corporate Ma Translations Multijurisdictiona... |
| `kompendium-22-mittelstand-corporat-bis-mittelstand-ma-insol` | mittelstand-corporate-ma: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Mittelstand Corporate Ma Wi Insurance, Mittelstand Ma Aktenanlage, Mittelstand Ma Erechnung Gobd, Mittelstand Ma Insolvenzreife; mit Intake, Prüfroutin... |
| `kompendium-23-mittelstand-ma-liqui-bis-rechtsabteilung-fami` | mittelstand-corporate-ma: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Mittelstand Ma Liquiditaetsvorschau, Mittelstand Ma Schreibcanvas, Betriebsuebergang Im Asset Deal, Familiengesellschafter Und Zustimmungsketten; mit I... |
| `kompendium-24-rechtsabteilung-gara-bis-v90-beirat-gmbh-zust` | mittelstand-corporate-ma: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Garantiekatalog Ohne Grosskanzlei Overkill, Vendor Due Diligence Fuer Versteckte Altlasten, V90 Beirat Gmbh Zustimmungskatalog Und Konfliktmatrix; mit... |
| `mittelstand-corporate-ma-kaltstart` | Deal-Kaltstart: Nimmt Kanzlei- und Mandantenpraeferenzen für Corporate/M&A auf: Dealtypen, Playbooks, Materiality, Reporting, Abrechnung, KI-Governance und Sicherheitsregeln. |
| `mittelstand-corporate-ma-output-versand-signing` | Output, Signing und Versand: Bereitet Transaktionsoutput vor: Markups, Issues Lists, Reports, Board Papers, Signing Packs, Closing Deliverables, beA/Notar/Email-Versand. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
