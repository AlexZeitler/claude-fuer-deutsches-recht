# Kartellrecht — Marktabgrenzungsprüfung

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`kartellrecht-marktabgrenzung-pruefung`) | [`kartellrecht-marktabgrenzung-pruefung.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/kartellrecht-marktabgrenzung-pruefung.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **Akte Nordstern MedTech Vertrieb - Provision, Buchauszug und Ausgleich** (`handelsvertreterrecht-provisionsausgleich-nordstern-medtech`) | [Gesamt-PDF lesen](../testakten/handelsvertreterrecht-provisionsausgleich-nordstern-medtech/gesamt-pdf/handelsvertreterrecht-provisionsausgleich-nordstern-medtech_gesamt.pdf) | [`testakte-handelsvertreterrecht-provisionsausgleich-nordstern-medtech.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-handelsvertreterrecht-provisionsausgleich-nordstern-medtech.zip) |
| **Zusammenschlusskontrolle GBW / Tannenheim — Bahnbetonschwellen, Bußgeld, ECN+** (`kartell-zusammenschlusskontrolle-bahnbetonschwellen-grosskopf-westfalen`) | [Gesamt-PDF lesen](../testakten/kartell-zusammenschlusskontrolle-bahnbetonschwellen-grosskopf-westfalen/gesamt-pdf/kartell-zusammenschlusskontrolle-bahnbetonschwellen-grosskopf-westfalen_gesamt.pdf) | [`testakte-kartell-zusammenschlusskontrolle-bahnbetonschwellen-grosskopf-westfalen.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-kartell-zusammenschlusskontrolle-bahnbetonschwellen-grosskopf-westfalen.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

Globales Kartellrechts- und Competition-Law-Plugin mit Marktabgrenzung als harter Kernachse: GWB, Art. 101 und Art. 102 AEUV, EU-Fusionskontrolle, Bundeskartellamt, DG Competition, FTC/DOJ, Dawn Raids, Leniency, Private Enforcement, sektorale Deep Dives und vorsichtige Jurisdiktionschecks weltweit.

## Installation in Claude Code

1. ZIP herunterladen (Link oben).
2. Claude Code → **Customize Plugins** → **Install from .zip** → Datei wählen.
3. Fertig. Skills sind sofort verfügbar.

> **Hinweis:** Für den ZIP-Upload muss das Archiv direkt `.claude-plugin/plugin.json`, `skills/`, `assets/` und `references/` im ZIP-Root enthalten. **Nicht** das komplette Repository-ZIP aus "Code → Download ZIP" verwenden.

## Zweck

Dieses Prüfwerkzeug analysiert kartellrechtliche Fälle auf juristischer, ökonomischer und methodischer Ebene. Es unterstützt bei:

- **Fusionskontrolle:** FKVO-Verfahren Phase I/II, BKartA-Verfahren, SIEC-Test.
- **Missbrauchsverfahren:** Art. 102 AEUV / §§ 19–20 GWB; Marktbeherrschungsnachweis.
- **Kartellverbot:** Art. 101 AEUV / § 1 GWB; Spürbarkeit, Bagatell-Ausnahme.
- **Globalen Behördenverfahren:** BKartA, Europäische Kommission, FTC/DOJ und nationale Wettbewerbsbehörden mit Local-Counsel-Fragen.
- **Sektorfällen:** Cloud, KI-Foundation-Models, App Stores, AdTech, Pharma, Energie, Telekom, Zahlungsverkehr, Automotive, Logistik, Sport und öffentliche Beschaffung.
- **Behördliche Stellungnahmen:** Stellungnahmen in BKartA- und Kommissionsverfahren.
- **Parteigutachten:** Kritische Würdigung gegnerischer Marktdefinitionen.

## Referenzen

| Datei | Inhalt |
| --- | --- |
| `references/methodik-marktdefinition.md` | Umfassende Darstellung der Marktdefinitions-Methodik (SSNIP, Elastizitäten, Supply-Side, räumlicher Markt, Evidenz) |
| `references/eugh-leitentscheidungen.md` | Chronologische Entscheidungssammlung EuGH/EuG/BGH/BKartA mit Kernsätzen zur Marktdefinition |

## Lizenz

Apache-2.0 OR MIT — Auswahl beim Empfänger.

## Quellen-Disclaimer

Tragende Aussagen müssen vor der Ausgabe anhand amtlicher Normfassungen, Behördenquellen oder frei zugänglicher Rechtsprechung geprüft werden. Das Prüfwerkzeug ersetzt keine eigene anwaltliche Prüfung im Einzelfall. Kartellrechtliche Marktdefinitionen und Behördenzuständigkeiten sind fallabhängig und können sich nach Markt, Transaktionsstruktur und Jurisdiktion ändern.


<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 59 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `competition-global-kaltstart` | Global Competition Kaltstart: Spezialskill für großes Kartellrecht mit BKartA, DG Competition, FTC/DOJ und internationalen Behörden; prüft welche Jurisdiktionen, Produkte, Märkte, Umsätze, Behörden, Deadlines und Verfahrensarten sofort r... |
| `kartellrecht-kaltstart-mandat-neu` | Workflow zur strukturierten Aufnahme, Priorisierung und Ausgabe im Thema Kartellrecht Kaltstart Mandat neu. |
| `komp-01-teil-02-eugh-rechtsprechung-leitentscheidungen` | kartellrecht-marktabgrenzung-pruefung: eigenständiger Arbeits-Skill für sachlich zusammengehörige Arbeitsmodule zu Eugh Rechtsprechung Leitentscheidungen, Spezial Rechtsprechung Beweislast Und Darlegungslast, Jurisdiktion Aegypten Compet... |
| `komp-01-teil-03-jurisdiktion-algerien-competition-authority` | kartellrecht-marktabgrenzung-pruefung: eigenständiger Arbeits-Skill für sachlich zusammengehörige Arbeitsmodule zu Jurisdiktion Algerien Competition Authority, Jurisdiktion Andorra Competition Authority, Jurisdiktion Angola Competition A... |
| `komp-01-teil-04-jurisdiktion-armenien-competition-authority` | kartellrecht-marktabgrenzung-pruefung: eigenständiger Arbeits-Skill für sachlich zusammengehörige Arbeitsmodule zu Jurisdiktion Armenien Competition Authority, Jurisdiktion Aserbaidschan Competition Authority; mit Intake, Prüfroutine, No... |
| `komp-10-teil-02-jurisdiktion-venezuela-competition-authority` | kartellrecht-marktabgrenzung-pruefung: eigenständiger Arbeits-Skill für sachlich zusammengehörige Arbeitsmodule zu Jurisdiktion Venezuela Competition Authority, Jurisdiktion Vereinigte Arabische Emirate Competition Authorit, Jurisdiktion... |
| `komp-10-teil-03-jurisdiktion-zimbabwe-competition-authority` | kartellrecht-marktabgrenzung-pruefung: eigenständiger Arbeits-Skill für sachlich zusammengehörige Arbeitsmodule zu Jurisdiktion Zimbabwe Competition Authority, Jurisdiktion Zypern Competition Authority, Eu Fusionskontrolle Fkvo Zustaendi... |
| `komp-10-teil-04-spezial-pruefinstanz-fristen-form-und-zustaendig` | kartellrecht-marktabgrenzung-pruefung: eigenständiger Arbeits-Skill für sachlich zusammengehörige Arbeitsmodule zu Spezial Pruefinstanz Fristen Form Und Zustaendigkeit, Franchise Vertrag Kartellrecht; mit Intake, Prüfroutine, Normen-/Que... |
| `komp-11-teil-02-private-enforcement-schadensersatz-intake` | kartellrecht-marktabgrenzung-pruefung: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Private Enforcement Schadensersatz Intake, Kartellschadenersatz Nach Behoerdenentscheidung, Sammelklagen Abtretungsmodelle Kartellschaden,... |
| `komp-11-teil-03-cross-border-evidence-sharing` | kartellrecht-marktabgrenzung-pruefung: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Cross Border Evidence Sharing, Dawn Raid Global War Room, 1 Gwb Kartellverbot Nationale Pruefung, 19 Gwb Behinderungs Ausbeutungsmissbrauc... |
| `komp-12-teil-02-alleinvertrieb-kundengruppen-gebietsschutz` | kartellrecht-marktabgrenzung-pruefung: eigenständiger Arbeits-Skill für sachlich zusammengehörige Arbeitsmodule zu Alleinvertrieb Kundengruppen Gebietsschutz, Alternative Marktdefinition Eng, Alternative Marktdefinition Weit, Anmeldepfli... |
| `komp-12-teil-03-arbeitsmarkt-no-poach-wage-fixing` | kartellrecht-marktabgrenzung-pruefung: eigenständiger Arbeits-Skill für sachlich zusammengehörige Arbeitsmodule zu Arbeitsmarkt No Poach Wage Fixing, Art 101 Aeuv Kooperationspruefung Einstieg, Art 101 Aeuv Tatbestand Vereinbarung Beschl... |
| `komp-12-teil-04-art-102-aeuv-missbrauchspruefung-einstieg` | kartellrecht-marktabgrenzung-pruefung: eigenständiger Arbeits-Skill für sachlich zusammengehörige Arbeitsmodule zu Art 102 Aeuv Missbrauchspruefung Einstieg, Auswirkungen Marktanteile Marktbeherrschung; mit Intake, Prüfroutine, Normen-/Q... |
| `komp-13-teil-02-competition-litigation-strategy` | kartellrecht-marktabgrenzung-pruefung: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Competition Litigation Strategy, Compliance Programm Kartellrecht Mittelstand, Compliance Schulung Kartellrisiken, Datenzugang Und Interop... |
| `komp-13-teil-03-de-minimis-inlandsauswirkung-fusionskontro` | kartellrecht-marktabgrenzung-pruefung: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu De Minimis Inlandsauswirkung Fusionskontrolle, Digital Platforms Self Preferencing, Disclosure 33g Gwb Akteneinsicht, Dma Schnittstelle Ka... |
| `komp-14-teil-02-essential-facilities-refusal-to-deal` | kartellrecht-marktabgrenzung-pruefung: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Essential Facilities Refusal To Deal, Eu Bekanntmachung Marktdefinition 2024, Evidenz Qualitaet Bewertung, Exklusivitaetsrabatte Treueraba... |
| `komp-14-teil-03-foreign-direct-investment-antitrust-schnit` | kartellrecht-marktabgrenzung-pruefung: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Foreign Direct Investment Antitrust Schnittstelle, Freistellung Art 101 Abs 3 Aeuv Effizienz Verbraucheranteil, Fusionskontrolle Anmeldung... |
| `komp-15-teil-02-healthcare-kartellrecht-kooperation-klinik` | kartellrecht-marktabgrenzung-pruefung: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Healthcare Kartellrecht Kooperation Kliniken, Horizontal Gvo Forschung Und Entwicklung, Horizontal Gvo Spezialisierung, Hub And Spoke Cart... |
| `komp-15-teil-03-information-exchange-safe-harbor` | kartellrecht-marktabgrenzung-pruefung: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Information Exchange Safe Harbor, Informationsaustausch Wettbewerber, Innovations Und Technologiemaerkte, Joint Venture Full Function; mit... |
| `komp-16-teil-02-ki-preisgestaltung-kartellrecht` | kartellrecht-marktabgrenzung-pruefung: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Ki Preisgestaltung Kartellrecht, Konsistenzpruefung Marktdefinition, Kronzeugenprogramm Bonusregelung, Labor Antitrust No Poach Global und... |
| `komp-16-teil-03-leniency-marker-global` | kartellrecht-marktabgrenzung-pruefung: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Leniency Marker Global, Margin Squeeze Predation, Margin Squeeze Telekom Energie Plattform, Market Definition 2024 Eu Notice; mit Intake,... |
| `komp-17-teil-02-missbrauchsverbot-modus` | kartellrecht-marktabgrenzung-pruefung: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Missbrauchsverbot Modus, Nachhaltigkeitskooperation Wettbewerbsrecht, Nicht Horizontale Fusion Vertikal Konglomerat, Paragraf 18 Gwb Pruef... |
| `komp-17-teil-03-predatory-pricing-kampfpreise` | kartellrecht-marktabgrenzung-pruefung: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Predatory Pricing Kampfpreise, Preisalgorithmen Kollusives Risiko, Preisbindung Der Zweiten Hand Rpm, Presseverlage Plattformen Leistungss... |
| `komp-18-teil-02-rechtsabteilung-gun-jumping-im-signing-to-c` | kartellrecht-marktabgrenzung-pruefung: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Gun Jumping Im Signing To Closing Fenster, Informationsaustausch Im Branchenverband, Meta Plattformdaten Als Kartell Und Datenschutzs, Rpm... |
| `komp-18-teil-03-refusal-to-supply-essential-facilities` | kartellrecht-marktabgrenzung-pruefung: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Refusal To Supply Essential Facilities, Remedies Zusagen Veraeusserung Zugang, Section 19a Gwb Big Tech, Sektor Adtech Und Digitale Werbun... |
| `komp-19-teil-02-sektor-krankenhaus-und-gesundheitsplattfor` | kartellrecht-marktabgrenzung-pruefung: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Sektor Krankenhaus Und Gesundheitsplattformen, Sektor Lebensmittelhandel Einkaufsallianzen, Sektor Logistik Haefen Schiene Luftfracht, Sek... |
| `komp-19-teil-03-sektor-sportligen-medienrechte-ticketing` | kartellrecht-marktabgrenzung-pruefung: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Sektor Sportligen Medienrechte Ticketing, Sektor Telekommunikation Infrastruktur Sharing, Sektor Zahlungsverkehr Card Schemes Fintech, Sel... |
| `komp-20-teil-02-spezial-angebotsumstellung-zahlen-schwelle` | kartellrecht-marktabgrenzung-pruefung: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Angebotsumstellung Zahlen Schwellen Und Berechnung, Evidenz Internationaler Bezug Und Schnittstellen, Flags Red Team Und Qualitaetskontrol... |
| `komp-20-teil-03-spezial-kritische-erstpruefung-und-mandats` | kartellrecht-marktabgrenzung-pruefung: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Kritische Erstpruefung Und Mandatsziel, Markt Mehrparteien Konflikt Und Interessen, Marktabgrenzungen Dokumentenmatrix Und Lueckenliste, M... |
| `komp-21-teil-02-spuerbarkeit-und-zwischenstaatlichkeit` | kartellrecht-marktabgrenzung-pruefung: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Spuerbarkeit Und Zwischenstaatlichkeit, Ssnip Test Anwendung, State Aid Eu Interface, Trade Association Antitrust und 1 weitere Arbeitsmod... |
| `komp-21-teil-03-verbandsarbeit-informationsaustausch-grenz` | kartellrecht-marktabgrenzung-pruefung: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Verbandsarbeit Informationsaustausch Grenzen, Vergleichsvereinbarung Patent Settlement Pay For Delay, Vertical Restraints Vber Global, Ver... |
| `kompendium-01-allgemein-bis-jurisdiktion-aserbai` | kartellrecht-marktabgrenzung-pruefung: eigenständiger Arbeits-Skill für sachlich zusammengehörige Arbeitsmodule zu Allgemein, Workflow Anschluss Skills Router, Workflow Chronologie Und Belegmatrix, Workflow Fristen Und Risikoampel; mit I... |
| `kompendium-02-jurisdiktion-austral-bis-jurisdiktion-china-c` | kartellrecht-marktabgrenzung-pruefung: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Australien Competition Authority, Bahrain Competition Authority, Bangladesch Competition Authority, Barbados Competition Authority und 10... |
| `kompendium-03-jurisdiktion-costa-r-bis-jurisdiktion-grieche` | kartellrecht-marktabgrenzung-pruefung: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Costa Rica Competition Authority, Daenemark Competition Authority, Deutschland Competition Authority, Dominikanische Republik Competition... |
| `kompendium-04-jurisdiktion-guatema-bis-jurisdiktion-kanada` | kartellrecht-marktabgrenzung-pruefung: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Guatemala Competition Authority, Honduras Competition Authority, Hongkong Competition Authority, Indien Competition Authority und 10 weite... |
| `kompendium-05-jurisdiktion-kasachs-bis-jurisdiktion-litauen` | kartellrecht-marktabgrenzung-pruefung: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Kasachstan Competition Authority, Katar Competition Authority, Kenia Competition Authority, Kirgisistan Competition Authority und 10 weite... |
| `kompendium-06-jurisdiktion-luxembu-bis-jurisdiktion-namibia` | kartellrecht-marktabgrenzung-pruefung: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Luxemburg Competition Authority, Macau Competition Authority, Madagaskar Competition Authority, Malawi Competition Authority und 10 weiter... |
| `kompendium-07-jurisdiktion-nepal-c-bis-jurisdiktion-paragua` | kartellrecht-marktabgrenzung-pruefung: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Nepal Competition Authority, Neuseeland Competition Authority, Nicaragua Competition Authority, Niederlande Competition Authority und 10 w... |
| `kompendium-08-jurisdiktion-peru-co-bis-jurisdiktion-singapu` | kartellrecht-marktabgrenzung-pruefung: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Peru Competition Authority, Philippinen Competition Authority, Polen Competition Authority, Portugal Competition Authority und 10 weitere... |
| `kompendium-09-jurisdiktion-slowake-bis-jurisdiktion-ukraine` | kartellrecht-marktabgrenzung-pruefung: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Slowakei Competition Authority, Slowenien Competition Authority, Spanien Competition Authority, Sri Lanka Competition Authority und 10 wei... |
| `kompendium-10-jurisdiktion-ungarn-bis-franchise-vertrag-ka` | kartellrecht-marktabgrenzung-pruefung: eigenständiger Arbeits-Skill für sachlich zusammengehörige Arbeitsmodule zu Jurisdiktion Ungarn Competition Authority, Jurisdiktion Uruguay Competition Authority, Jurisdiktion Usa Competition Author... |
| `kompendium-11-kartellrechtliche-ve-bis-19-gwb-behinderungs` | kartellrecht-marktabgrenzung-pruefung: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Kartellrechtliche Vertragsklausel Redline, Bussgeldbemessung Unternehmen Verband, Geschaeftsleiterhaftung Kartellverstoss, Kartellschadens... |
| `kompendium-12-19a-gwb-ueberragende-bis-auswirkungen-marktan` | kartellrecht-marktabgrenzung-pruefung: eigenständiger Arbeits-Skill für sachlich zusammengehörige Arbeitsmodule zu 19A Gwb Ueberragende Marktuebergreifende Bedeutung, 20 Gwb Relative Marktmacht, Abuse Of Economic Dependence, Algorithmic... |
| `kompendium-13-bietergemeinschaft-v-bis-dma-schnittstelle-ka` | kartellrecht-marktabgrenzung-pruefung: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Bietergemeinschaft Vergabekartellrecht, Bka Dgcomp Ftc Doj Routing, Cartel Settlement Procedure, Competition Board Liability und 1 weitere... |
| `kompendium-14-dma-und-gatekeeper-m-bis-fusionskontrolle-gwb` | kartellrecht-marktabgrenzung-pruefung: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Dma Und Gatekeeper Markt, Einkaufskooperation Nachfragemacht, Einstweiliger Rechtsschutz Kartellrecht, Elastizitaeten Diversion Ratios und... |
| `kompendium-15-fusionskontrolle-mod-bis-joint-venture-full-f` | kartellrecht-marktabgrenzung-pruefung: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Fusionskontrolle Modus, Geoblocking Und Kartellrecht Schnittstelle, Gesamtbewertung Tragfaehigkeit, Gun Jumping Global und 1 weitere Arbei... |
| `kompendium-16-kart-innovationswett-bis-market-definition-20` | kartellrecht-marktabgrenzung-pruefung: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Kart Innovationswettbewerb Spezial, Kart Marktanteilsanalyse Leitfaden, Kart Marktdefinition Bauleiter, Kart Zweiseitige Plattformen Spezi... |
| `kompendium-17-marktabgrenzung-kont-bis-presseverlage-plattf` | kartellrecht-marktabgrenzung-pruefung: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Marktabgrenzung Kontextanalyse, Mehrseitige Maerkte Plattformen, Merger Remedies Global, Ministererlaubnis 42 Gwb und 1 weitere Arbeitsmod... |
| `kompendium-18-private-enforcement-bis-sektor-adtech-und-di` | kartellrecht-marktabgrenzung-pruefung: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Private Enforcement Damages Global, Produktmarkt Angebotsumstellung, Produktmarkt Nachfragesubstitution, Public Procurement Bid Rigging un... |
| `kompendium-19-sektor-app-stores-mo-bis-selektivvertrieb-lux` | kartellrecht-marktabgrenzung-pruefung: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Sektor App Stores Mobile Oekosysteme, Sektor Automotive Zulieferketten Und Oem, Sektor Cloud Infrastruktur Hyperscaler, Sektor Energie Spe... |
| `kompendium-20-self-preferencing-pl-bis-spezial-marktbeherrs` | kartellrecht-marktabgrenzung-pruefung: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Self Preferencing Plattformen, Sep Frand Kartellrecht, Siec Test Eu Merger Control, Siec Test Horizontale Fusion und 1 weitere Arbeitsmodu... |
| `kompendium-21-spezial-paragraf-ris-bis-vertikal-gvo-2022-72` | kartellrecht-marktabgrenzung-pruefung: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Paragraf Risikoampel Und Gegenargumente, Raeumlicher Compliance Dokumentation Und Akte, Ssnip Schriftsatz Brief Und Memo Bausteine, Test V... |
| `kompendium-22-vertikale-leitlinien-bis-vollzugsverbot-gun-j` | kartellrecht-marktabgrenzung-pruefung: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Vertikale Leitlinien Eu Selektiver Vertrieb Plattformverbote, Verweisung Art 4 9 22 Fkvo, Vollzugsverbot Gun Jumping; mit Intake, Prüfrout... |
| `spezial-nachfrage-livequellen-und-rechtsprechungscheck` | Nachfrage: Livequellen- und Rechtsprechungscheck im Plugin kartellrecht marktabgrenzung pruefung; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Standardprüfung. |
| `workflow-dokumentenintake` | Dokumentenintake im Plugin kartellrecht-marktabgrenzung-pruefung: liest Uploads, sortiert Dokumentarten, markiert Fristen und baut eine knappe Arbeitsakte. |
| `workflow-kaltstart-und-routing` | Kaltstart und Routing im Plugin kartellrecht-marktabgrenzung-pruefung: führt vom ersten Satz oder Dokument in den passenden Arbeitsweg, erkennt Rolle, Ziel, Risiko und Anschluss-Skills. |
| `workflow-output-waehlen` | Output wählen im Plugin kartellrecht-marktabgrenzung-pruefung: entscheidet zwischen Memo, Schriftsatz, Tabelle, Brief, Checkliste, Vermerk, Redline oder Mandantenübersetzung. |
| `workflow-rechtsquellen-livecheck` | Rechtsquellen-Livecheck im Plugin kartellrecht-marktabgrenzung-pruefung: zwingt vor tragenden Aussagen zum aktuellen Quellencheck bei Gesetzen, Behörden, Gerichten und Formularen. |
| `workflow-unterlagen-lueckenliste` | Unterlagen- und Lückenliste im Plugin kartellrecht-marktabgrenzung-pruefung: erstellt eine präzise Nachforderungsliste statt allgemeiner Fragebögen. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
