# gesellschaftsgründer — Gründungsassistent für deutsche Gesellschaften

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`gesellschaftsgruender`) | [`gesellschaftsgruender.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/gesellschaftsgruender.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **NeuroChain Labs — Gründung eines KI/Krypto-Startups in Berlin, Musterprotokoll vs. individuelle Satzung** (`gesellschaftsgruender-ki-krypto-startup-berlin-musterprotokoll`) | [Gesamt-PDF lesen](../testakten/gesellschaftsgruender-ki-krypto-startup-berlin-musterprotokoll/gesamt-pdf/gesellschaftsgruender-ki-krypto-startup-berlin-musterprotokoll_gesamt.pdf) | [`testakte-gesellschaftsgruender-ki-krypto-startup-berlin-musterprotokoll.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-gesellschaftsgruender-ki-krypto-startup-berlin-musterprotokoll.zip) |
| **Roeschen Tech GmbH — Gründung, Series A, B-Shares und Streit-Eskalation** (`gesellschaftsgruender-streit-roeschen-tech`) | [Gesamt-PDF lesen](../testakten/gesellschaftsgruender-streit-roeschen-tech/gesamt-pdf/gesellschaftsgruender-streit-roeschen-tech_gesamt.pdf) | [`testakte-gesellschaftsgruender-streit-roeschen-tech.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-gesellschaftsgruender-streit-roeschen-tech.zip) |
| **Handelsrecht HGB — Elbwerft Solar: eGbR, OHG-Statuswechsel, KG und Handelskauf** (`handelsrecht-hgb-kommanditgesellschaft-egbr-statuswechsel-altona`) | [Gesamt-PDF lesen](../testakten/handelsrecht-hgb-kommanditgesellschaft-egbr-statuswechsel-altona/gesamt-pdf/handelsrecht-hgb-kommanditgesellschaft-egbr-statuswechsel-altona_gesamt.pdf) | [`testakte-handelsrecht-hgb-kommanditgesellschaft-egbr-statuswechsel-altona.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-handelsrecht-hgb-kommanditgesellschaft-egbr-statuswechsel-altona.zip) |
| **Nebelstern Ventures - Berliner VC-Pipeline, Wandeldarlehen und Follow-on-Chaos** (`venture-capital-geber-nebelstern-portfolio-berlin`) | [Gesamt-PDF lesen](../testakten/venture-capital-geber-nebelstern-portfolio-berlin/gesamt-pdf/venture-capital-geber-nebelstern-portfolio-berlin_gesamt.pdf) | [`testakte-venture-capital-geber-nebelstern-portfolio-berlin.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-venture-capital-geber-nebelstern-portfolio-berlin.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

Freistehendes, anfängerfreundliches und zugleich professionelles Plugin für die Gründung und frühe Führung deutscher Gesellschaften. Es hilft beim ersten Sortieren ebenso wie bei einem fast fertigen Gründungspaket: Rechtsformwahl, Rollen der Gründerinnen und Gründer, Satzung, Gesellschaftervereinbarung, Cap Table, Notar, Handelsregister, Bank/KYC, Behörden, Steuerstart, IP, Datenschutz, erste 100 Tage und Streitprävention.

## Installation

1. Claude Code oder Claude Desktop/Cowork öffnen.
2. **Customize Plugins** bzw. **Personal plugins** wählen.
3. **Install from .zip** und `gesellschaftsgruender.zip` hochladen.
4. Mit einem konkreten Auftrag starten, zum Beispiel: `Starte die Gesellschaftsgründung. Ich habe drei Gründer, eine GmbH-Idee und noch keine Satzung.`

Alternativ via Marketplace:

```text
/plugin marketplace add Klotzkette/claude-fuer-deutsches-recht
/plugin install gesellschaftsgruender@claude-fuer-deutsches-recht
```

Nicht das komplette Repository-ZIP hochladen. Das Plugin-ZIP muss im Root direkt `.claude-plugin/plugin.json` und das Verzeichnis `skills/` enthalten.

## So Startet Es

Der `allgemein`-Skill beginnt bewusst leicht. Er fragt nicht sofort nach allen juristischen Details, sondern sortiert zuerst:

1. **Wer gründet?** Personen, Rollen, Wohnsitz, Auslandsbezug, Minderjährige, Treuhand, Familien- oder Investorensituation.
2. **Was soll die Gesellschaft tun?** Geschäftszweck, reguliertes Geschäft, IP, Daten, KI, Produkt, Finanzierung, Personal.
3. **Welche Rechtsform liegt nahe?** GmbH, UG, eGbR, OHG, KG, GmbH & Co. KG, PartG mbB, gGmbH, eG, AG, Holding oder Sonderstruktur.
4. **Was muss jetzt zuerst passieren?** Notarbriefing, Gesellschaftsvertrag, Bankkonto, Transparenzregister, Steuererfassung, Gewerbe, IHK/BG, Versicherungen.
5. **Wo brennt es?** Registerbeanstandung, Gründerstreit, KYC-Blockade, IP-Lücke, Sacheinlage, Stammkapitalverlust, Liquiditätsproblem.

Das Plugin schlägt danach aktiv die passenden Anschluss-Skills vor, statt die Nutzerin oder den Nutzer mit einer langen Skillliste allein zu lassen.

## Arbeitsphasen

| Phase | Ziel | Typische Outputs |
| --- | --- | --- |
| **0 Intake** | Idee, Beteiligte, Geld, Risiko und Zeitplan verstehen | One-Page-Roadmap, Rückfragenliste, Risikoampel |
| **1 Rechtsform** | passende Struktur auswählen und falsche Abzweigungen vermeiden | Rechtsformmatrix, Entscheidungsvorlage, Stoppschilder |
| **2 Dokumente** | Gründungspaket bauen | Satzung, SHA, Geschäftsführerunterlagen, Gesellschafterliste, Notarbriefing |
| **3 Vollzug** | Notar, Register, Bank, Behörden und Steuerstart koordinieren | Closing-Checkliste, KYC-Paket, ELSTER-/Gewerbe-/BG-Liste |
| **4 Betrieb** | erste 100 Tage sauber organisieren | Board Pack, Beschlussvorlagen, Versicherungs- und Compliance-Check |
| **5 Konflikt** | Streit früh erkennen und kontrolliert eskalieren | Deadlock-Matrix, Mediationsplan, Eilmaßnahmen-Check, Registerstrategie |

## Skillgruppen

- **Einstieg und Anfängerführung:** Kaltstart, einfache Sprache, One-Page-Roadmap, Gründerrollen, Mandantenbrief, Checkliste vor Unterschrift.
- **Rechtsformen:** GmbH, UG, eGbR, OHG, KG, GmbH & Co. KG, PartG mbB, gGmbH, eG, AG, SE und Holdingmodelle.
- **Dokumente und Vollzug:** Satzung, Gesellschaftervereinbarung, Geschäftsführervertrag, Geschäftsordnung, Gesellschafterliste, Notarbriefing, Registerbeanstandung.
- **Finanzierung und Beteiligung:** Cap Table, Seed-Runde, Wandeldarlehen, Founder Vesting, Leaver, ESOP/VSOP, Vinkulierung, Drag/Tag, Bezugsrechte.
- **Risikothemen:** Auslandsgründer, KYC, Sanktionen, Transparenzregister, Sacheinlagen, IP-Übertragung, Open Source, Datenschutz/KI, regulierte Geschäftsmodelle.
- **Operativer Start:** Bankkonto, Steuerliche Erfassung, Umsatzsteuer, Payroll, Mietvertrag, Kundenstart, Produkthaftung, Versicherungen, Cash Burn und Insolvenzfrühwarnung.

## Demonstrationsakte

Die Akte `gesellschaftsgruender-streit-roeschen-tech` zeigt eine Gründung, die nicht lehrbuchartig glatt läuft: drei Gründer, ein technisches Produkt, IP-Fragen, Series-A-Druck, B-Shares, Bezugsrechtsstreit, KYC-Rückfragen, Registerlogik, Gründer-Vesting, Leaver-Risiken, Datenschutz-/KI-Fragen und ein Konflikt, der parallel über Notar, Bank, Investorin, Beirat und Registergericht läuft.

Sie enthält unter anderem Satzungsentwurf, Gesellschaftervereinbarung, Cap-Table-Varianten, E-Mails, Register-/Notarvermerke, KYC-Nachfragen, IP-/Open-Source-Notizen, Vesting-Matrix, Board Pack, Cash-Burn-Übersicht, Compliance-Startliste, CSV-Tabellen und ein Gesamt-PDF.

## Stoppschilder

- **Notar:** Beurkundung, Handelsregisteranmeldung und bestimmte Vollmachten müssen notariell laufen.
- **Steuer:** Rechtsform, Holding, Sacheinlage, ESOP/VSOP, USt und Verrechnungspreise gehören früh in steuerkundige Hände.
- **Aufsicht und Erlaubnis:** Finanzen, Versicherung, Kryptowerte, Zahlungsdienste, Medizin, Bewachung, Handwerk, Lebensmittel, Transport und ähnliche Modelle brauchen einen Erlaubnischeck vor dem Start.
- **Krise:** Bei Zahlungsunfähigkeit, Überschuldung, hälftigem Stammkapitalverlust oder Liquiditätslücke geht es nicht mehr nur um Gründung, sondern um Organhaftung und Insolvenzrecht.
- **Streit:** Bei Gesellschafterstreit, Registerblockade oder Investorendruck braucht es eine Beweis-, Fristen- und Eskalationsstrategie.

## Quellenhygiene

Gesetzesstände, Registervorgaben, Formularwege und Behördenpraxis sind vor produktiver Verwendung live zu prüfen. Rechtsprechung wird nicht aus Modellwissen zitiert; sie muss vor Ausgabe mit Gericht, Entscheidungsform, Datum, Aktenzeichen und freier oder amtlicher Quelle verifiziert werden.

Wichtige Startanker sind insbesondere BGB §§ 705 ff., HGB §§ 105 ff. und §§ 161 ff., GmbHG, AktG, PartGG, GenG, GwG/Transparenzregister, GewO, AO/UStG, SGB IV/SGB VII, InsO § 15a und die Register-/Notarvorgaben nach BeurkG und HRegV.

<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 27 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `allgemein` | Einstieg, Schnelltriage und Workflow-Routing für das Gesellschaftsgründer-Plugin; besonders anfängerfreundlich, mit Rollenklärung, Dokumentenintake, Rechtsformwahl und Anschluss-Skills. |
| `egbr-mopeg-gesellschaftsgruender-familiengesellschaft` | Gesellschaftsgründer Egbr Mopeg, Gesellschaftsgründer Familiengesellschaft, Gesellschaftsgründer Finanzierungsrunde Seed, Gesellschaftsgründer Firmenname Prüfung, Gesellschaftsgründer Founder Vesting: Gesellschaftsgründer Egbr Mopeg; Ges... |
| `geschaeftsordnung-gf-gesellschafterstreit-eilantraege` | Gesellschaftsgründer Geschaeftsordnung Gf, Gesellschaftsgründer Gesellschafterstreit Eilantraege, Gesellschaftsgründer Gesellschaftervereinbarung, Gesellschaftsgründer Gf Meeting Templates, Gesellschaftsgründer Ggmbh Gemeinnuetzigkeit: G... |
| `gesellschaftsgruender-anfaenger-kaltstart` | Führt absolute Anfänger durch die ersten Entscheidungen einer Gesellschaftsgründung ohne Fachsprachenfalle. |
| `gesellschaftsgruender-bankkonto-kyc-beirat-advisory-bilinguale` | Gesellschaftsgründer Bankkonto Kyc Paket, Gesellschaftsgründer Beirat Advisory Board, Gesellschaftsgründer Bilinguale Dokumente, Gesellschaftsgründer Board Pack Erste 100 Tage, Gesellschaftsgründer Cap Table: Gesellschaftsgründer Bankkon... |
| `gesellschaftsgruender-cashburn-insolvenzfruehwarnung-checkliste` | Gesellschaftsgründer Cashburn Insolvenzfruehwarnung, Gesellschaftsgründer Checkliste Vor Unterschrift, Gesellschaftsgründer Daten Und Ki Compliance Start, Gesellschaftsgründer Deadlock Und Mediation, Gesellschaftsgründer Egbr Grundstueck... |
| `gesellschaftsgruender-freiberufler-partg-gbr-ohg-genehmigtes` | Gesellschaftsgründer Freiberufler Partg Mbb, Gesellschaftsgründer Gbr Zu Ohg Statuswechsel, Gesellschaftsgründer Genehmigtes Kapital, Gesellschaftsgründer Genossenschaft Eg, Gesellschaftsgründer Geschaeftsfuehrer Pflichten Startphase: Ge... |
| `gesellschaftsgruender-gesellschafterliste-qualitygate` | Prüft Gesellschafterliste, Nennbeträge, Nummerierung, Prozentangaben und Veränderungsspalten. |
| `gesellschaftsgruender-gmbh-vorbereitung-golden-share-gv` | Gesellschaftsgründer Gmbh Vorbereitung, Gesellschaftsgründer Golden Share Und Vetorechte, Gesellschaftsgründer Gruenderrollen Konfliktcheck, Gesellschaftsgründer Gv Einladung Tagesordnung, Gesellschaftsgründer Gv Protokoll Und Versammlun... |
| `gesellschaftsgruender-handelsregister-anmeldung-ihk-investor-dd` | Gesellschaftsgründer Handelsregister Anmeldung, Gesellschaftsgründer Ihk Und Berufsgenossenschaft, Gesellschaftsgründer Investor Dd Vorbereiten, Gesellschaftsgründer Ip Einbringung, Gesellschaftsgründer Kapitalerhoehung Bezugsrecht: Gese... |
| `gesellschaftsgruender-lizenz-vertriebsstart-lohn-payroll` | Gesellschaftsgründer Kommandocenter, Gesellschaftsgründer Lizenz Und Vertriebsstart, Gesellschaftsgründer Lohn Payroll Start, Gesellschaftsgründer Mandantenbrief Naechste Schritte, Gesellschaftsgründer Minderjaehrige Gesellschafter: Gese... |
| `gesellschaftsgruender-musterprotokoll-vs-notar-vorbereitung` | Gesellschaftsgründer Musterprotokoll Vs Satzung, Gesellschaftsgründer Notar Vorbereitung, Gesellschaftsgründer Notarbriefing Onepager, Gesellschaftsgründer One Page Roadmap, Gesellschaftsgründer Online Gruendung Dirug: Gesellschaftsgründ... |
| `gesellschaftsgruender-open-source-plain-language-reguliertes` | Gesellschaftsgründer Open Source Startup, Gesellschaftsgründer Plain Language Modus, Gesellschaftsgründer Registerbeanstandung Beantworten, Gesellschaftsgründer Reguliertes Geschaeftsmodell, Gesellschaftsgründer Sacheinlage Und Verdeckte... |
| `gesellschaftsgruender-redteam-gruendungspaket` | Prüft das gesamte Gründungspaket auf typische Fehler, Streitbomben und Register-/Bankhindernisse. |
| `gesellschaftsgruender-steuerliche-erfassung-treuhand-nominee` | Gesellschaftsgründer Steuerliche Erfassung Elster, Gesellschaftsgründer Treuhand Und Nominee, Gesellschaftsgründer Ag Kleine Ag, Gesellschaftsgründer Aufloesung Liquidation Start, Gesellschaftsgründer Auslandsgesellschafter Kyc: Gesellsc... |
| `gesellschaftsgruender-transparenzregister-update-ug-vorbereitung` | Gesellschaftsgründer Transparenzregister Update, Gesellschaftsgründer Ug Vorbereitung, Gesellschaftsgründer Umsatzsteuer Start, Gesellschaftsgründer Versicherungen Start, Gesellschaftsgründer Vinkulierung Und Transfer: Gesellschaftsgründ... |
| `gesellschaftsgruender-wandeldarlehen-gesellschaften-ggmbh-partg` | Gesellschaftsgründer Wandeldarlehen Safe, Spezial Gesellschaften Tatbestand Beweis Und Belege, Spezial Ggmbh Risikoampel Und Gegenargumente, Spezial Gruendungsassistent Erstpruefung Und Mandatsziel, Spezial Partg Dokumentenmatrix Und Lue... |
| `intake-decision-kg-gmbhcokg-mitarbeiterbeteiligung-esop` | Gesellschaftsgründer Intake Decision Tree, Gesellschaftsgründer Kg Und Gmbhcokg, Gesellschaftsgründer Mitarbeiterbeteiligung Esop Vsop, Gesellschaftsgründer Rechtsformwahl, Gesellschaftsgründer Share Classes A B C: Gesellschaftsgründer I... |
| `leaver-klauseln-mietvertrag-buero-mitarbeiter-gf` | Gesellschaftsgründer Leaver Klauseln, Gesellschaftsgründer Mietvertrag Buero Labor, Gesellschaftsgründer Mitarbeiter Gf Arbeitsvertrag, Spezial Gesellschaftsvertrag Vergleich Eskalation, Gesellschaftsgründer Produkt Und Produkthaftung St... |
| `rechtsformwahl-ueber` | Spezial Rechtsformwahl Behörden Gericht Und Registerweg, Spezial Ueber Schriftsatz Brief Und Memo Bausteine: Spezial Rechtsformwahl Behörden Gericht Und Registerweg; Spezial Ueber Schriftsatz Brief Und Memo Bausteine. Führt Intake, Prüfr... |
| `sanktionen-investorcheck-gewerbeanmeldung-finanzamt-gf` | Gesellschaftsgründer Sanktionen Investorcheck, Gesellschaftsgründer Gewerbeanmeldung Finanzamt, Gesellschaftsgründer Gf Sozialversicherungs Status, Gesellschaftsgründer Gruender Intake, Gesellschaftsgründer Holdingmodell: Gesellschaftsgr... |
| `se-crossborder-sha-satzung-stammkapital-einzahlung` | Gesellschaftsgründer Se Und Crossborder, Gesellschaftsgründer Sha Satzung Stimmverpflichtung, Gesellschaftsgründer Stammkapital Einzahlung, Gesellschaftsgründer Stammkapitalverlust Paragraf 49 Gmbhg, Gesellschaftsgründer Transparenzregis... |
| `spezial-geschaeftsfuehrervertrag-livequellen-check` | Geschaeftsfuehrervertrag: Livequellen- und Rechtsprechungscheck im Gesellschaftsgründung: fachlich vertiefter Spezialskill mit Normenradar (GmbHG/MoPeG/Registerrecht), Tatbestands-/Beweislastmatrix, Fristen- und Formcheck, Gegenargumente... |
| `workflow-dokumentenintake` | Dokumentenintake im Plugin gesellschaftsgruender: liest Uploads, sortiert Dokumentarten, markiert Fristen und baut eine knappe Arbeitsakte. |
| `workflow-fristen-gmbh-gesellschaftsgruender` | Workflow Fristen Und Risikoampel, Spezial Gmbh Fristen Form Und Zustaendigkeit, Gesellschaftsgründer Geschaeftsfuehrervertrag, Gesellschaftsgründer Gesellschaftsvertrag Gmbh, Gesellschaftsgründer Klauselkatalog Bilingual: Workflow Friste... |
| `workflow-kaltstart-und-routing` | Kaltstart und Routing im Plugin gesellschaftsgruender: führt vom ersten Satz oder Dokument in den passenden Arbeitsweg, erkennt Rolle, Ziel, Risiko und Anschluss-Skills. |
| `workflow-unterlagen-lueckenliste` | Unterlagen- und Lückenliste im Plugin gesellschaftsgruender: erstellt eine präzise Nachforderungsliste statt allgemeiner Fragebögen. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
