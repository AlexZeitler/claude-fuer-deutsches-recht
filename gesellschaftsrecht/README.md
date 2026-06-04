# Gesellschaftsrecht-Plugin

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`gesellschaftsrecht`) | [`gesellschaftsrecht.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/gesellschaftsrecht.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **NeuroChain Labs — Gründung eines KI/Krypto-Startups in Berlin, Musterprotokoll vs. individuelle Satzung** (`gesellschaftsgruender-ki-krypto-startup-berlin-musterprotokoll`) | [Gesamt-PDF lesen](../testakten/gesellschaftsgruender-ki-krypto-startup-berlin-musterprotokoll/gesamt-pdf/gesellschaftsgruender-ki-krypto-startup-berlin-musterprotokoll_gesamt.pdf) | [`testakte-gesellschaftsgruender-ki-krypto-startup-berlin-musterprotokoll.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-gesellschaftsgruender-ki-krypto-startup-berlin-musterprotokoll.zip) |
| **Roeschen Tech GmbH — Gründung, Series A, B-Shares und Streit-Eskalation** (`gesellschaftsgruender-streit-roeschen-tech`) | [Gesamt-PDF lesen](../testakten/gesellschaftsgruender-streit-roeschen-tech/gesamt-pdf/gesellschaftsgruender-streit-roeschen-tech_gesamt.pdf) | [`testakte-gesellschaftsgruender-streit-roeschen-tech.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-gesellschaftsgruender-streit-roeschen-tech.zip) |
| **Akte Kometenfalter Systems GmbH — Series A Project Comet Moth** (`gesellschaftsrecht-legal-english-frankfurt-startup`) | [Gesamt-PDF lesen](../testakten/gesellschaftsrecht-legal-english-frankfurt-startup/gesamt-pdf/gesellschaftsrecht-legal-english-frankfurt-startup_gesamt.pdf) | [`testakte-gesellschaftsrecht-legal-english-frankfurt-startup.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-gesellschaftsrecht-legal-english-frankfurt-startup.zip) |
| **Handelsrecht HGB — Elbwerft Solar: eGbR, OHG-Statuswechsel, KG und Handelskauf** (`handelsrecht-hgb-kommanditgesellschaft-egbr-statuswechsel-altona`) | [Gesamt-PDF lesen](../testakten/handelsrecht-hgb-kommanditgesellschaft-egbr-statuswechsel-altona/gesamt-pdf/handelsrecht-hgb-kommanditgesellschaft-egbr-statuswechsel-altona_gesamt.pdf) | [`testakte-handelsrecht-hgb-kommanditgesellschaft-egbr-statuswechsel-altona.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-handelsrecht-hgb-kommanditgesellschaft-egbr-statuswechsel-altona.zip) |
| **Mandatsbeziehung Nordstern BioTherapeutics — Kanzlei Falkenried** (`mandatsbeziehung-kanzlei-rechtsabteilung-nordstern-biotech`) | [Gesamt-PDF lesen](../testakten/mandatsbeziehung-kanzlei-rechtsabteilung-nordstern-biotech/gesamt-pdf/mandatsbeziehung-kanzlei-rechtsabteilung-nordstern-biotech_gesamt.pdf) | [`testakte-mandatsbeziehung-kanzlei-rechtsabteilung-nordstern-biotech.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-mandatsbeziehung-kanzlei-rechtsabteilung-nordstern-biotech.zip) |
| **Codeforst / Sonnenklee - RouteLuchs** (`softwarerecht-saas-ki-lizenzstreit-codeforst-muenchen`) | [Gesamt-PDF lesen](../testakten/softwarerecht-saas-ki-lizenzstreit-codeforst-muenchen/gesamt-pdf/softwarerecht-saas-ki-lizenzstreit-codeforst-muenchen_gesamt.pdf) | [`testakte-softwarerecht-saas-ki-lizenzstreit-codeforst-muenchen.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-softwarerecht-saas-ki-lizenzstreit-codeforst-muenchen.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

Abläufe für gesellschaftsrechtliche Mandate in deutschen Kanzleien und Rechtsabteilungen: M&A-Transaktionen, Organe und Protokollwesen, Gesellschafts-Compliance und Unternehmensführung. Aktiviere nur die Module, die für deine Praxis relevant sind. Das Kaltstart-Interview ist modular – es stellt gezielte Fragen je aktivem Bereich und schreibt nur die entsprechenden Abschnitte in dein Praxisprofil.

**Jedes Ergebnis ist ein Entwurf zur anwaltlichen Überprüfung – zitiert, markiert und gesperrt – kein Rechtsgutachten.** Das Plugin übernimmt die Arbeit: liest Dokumente, wendet dein Playbook an, findet die Issues, erstellt den Bericht. Ein Rechtsanwalt prüft, verifiziert und entscheidet. Zitate sind mit Quellen gekennzeichnet, damit klar ist, welche aus einem Recherchetool stammen und welche noch zu prüfen sind. Mandantengeheimnis (§ 43a Abs. 2 BRAO, § 203 StGB) wird konservativ gewahrt. Folgenreiche Handlungen – Einreichung, Versendung, Beurkundung – werden durch ausdrückliche Bestätigung gesperrt.


## Für wen

| Rolle | Aktive Module |
|---|---|
| **M&A-Anwalt (Kanzlei oder Inhouse)** | M&A |
| **Gesellschaftssekretär / Corporate Secretary** | Organe & Protokoll |
| **General Counsel, Aktiengesellschaft** | M&A + Börse/Kapitalmarkt + Organe & Protokoll |
| **General Counsel, GmbH** | M&A + Organe & Protokoll + Gesellschafts-Compliance |
| **Legal Ops / Solo-GC** | Nach Bedarf – beliebige Kombination |

## Erster Start

```
/gesellschaftsrecht:gesellschaftsrecht-kaltstart-interview
```

Führt durch die Modulauswahl und ein kurzes Zielinterview je aktivem Bereich. Schreibt ein modulares Praxisprofil nach:
`~/.claude/plugins/config/claude-fuer-deutsches-recht/gesellschaftsrecht/CLAUDE.md`

Deine Konfiguration bleibt dort und übersteht Plugin-Updates.

Dealspezifisches Setup (nur M&A-Modul):

```
/gesellschaftsrecht:gesellschaftsrecht-kaltstart-interview --neues-mandat
```

## Befehle

| Befehl | Funktion |
|---|---|
| `/gesellschaftsrecht:gesellschaftsrecht-kaltstart-interview` | Modulares Kaltstart oder `--neues-mandat` / `--modul [m&a \| organe \| boerse \| compliance]` |
| `/gesellschaftsrecht:dd-findings-extraktion [ordner]` | Datenraum-Dokumente lesen, Issues im Hauskatalog extrahieren |
| `/gesellschaftsrecht:tabellenpruefung` | Tabellarisches Review – eine Zeile pro Dokument, eine Spalte pro Datenpunkt, jede Zelle mit Fundstelle, Excel-Ausgabe |
| `/gesellschaftsrecht:wesentliche-vertraege-anlage` | Wesentliche-Verträge-Anlage (Disclosure Schedule) aus DD-Findings |
| `/gesellschaftsrecht:vollzugs-checkliste` | Vollzugscheckliste – was blockiert den Closing, kritischer Pfad |
| `/gesellschaftsrecht:gesellschafterbeschluss` | Gesellschafterbeschluss im schriftlichen Verfahren § 48 II GmbHG, Muster mit Unterzeichner-Tracker |
| `/gesellschaftsrecht:gesellschafts-compliance` | Gesellschafts-Compliance-Tracker – init, Bericht, Update, Audit, Export |
| `/gesellschaftsrecht:integrations-management` | Post-Closing-Integrationsplan, Zustimmungsregister, Vertragsübertragung, Statusberichte |
| `/gesellschaftsrecht:gesellschaftsrecht-mandat-arbeitsbereich` | Mandatsarbeitsbereiche verwalten (Mehrmandat-Kanzleien) – neu, liste, wechsel, schließ, keins |
| `/gesellschaftsrecht:gmbh-gruendung` | GmbH-Gründung Schritt-für-Schritt: Gesellschaftsvertrag, Notar, Handelsregister |
| `/gesellschaftsrecht:handelsregisteranmeldung` | Handelsregisteranmeldungen: HRB/HRA, Änderungen, Kapitalmaßnahmen |

## Voraussetzungen

Mehrere Funktionen verweisen auf Slack, Google Drive, SharePoint, Box, Datasite- oder VDR-Integrationen. Diese erfordern MCP-Server in deiner Umgebung – sie sind **nicht im Plugin enthalten**. Ohne sie greift das Plugin auf lokale Dateiausgabe zurück (Entwürfe lokal gespeichert statt in einen Kanal gepostet, Tracker-Dateien auf Festplatte statt in einem verbundenen Repository).

MCP-Server konfigurieren unter `.mcp.json` auf Repo- oder Benutzerebene. Skills und Agenten erkennen zur Laufzeit, was verfügbar ist, und passen ihr Verhalten an.

## Skills

| Skill | Modul | Zweck |
|---|---|---|
| **kaltstart-interview** | Alle | Modulares Interview – aktiviert nur relevante Abschnitte |
| **dd-findings-extraktion** | M&A | Datenraum-Dokumente → Issues im Hauskatalog, nach Kategorie |
| **tabellarisches-review** | M&A | Dokumentensatz gegen typisiertes Spaltenformat prüfen; Zellen mit Fundstelle; `.xlsx` / `.csv` / Markdown; speist wesentliche-vertraege-anlage |
| **dealteam-zusammenfassung** | M&A | Stufenbriefings: Geschäftsführung / Deal-Lead / Arbeitsteam |
| **wesentliche-vertraege-anlage** | M&A | Disclosure Schedule gemäß SPA-Definition |
| **vollzugs-checkliste** | M&A | Selbstaktualisierend: nimmt Einträge aus DD und Schedule-Builds auf |
| **ki-werkzeug-uebergabe** | M&A | Luminance/Kira-Integration – Massenextraktion + QA-Schicht |
| **aufsichtsrat-protokoll** | Organe & Protokoll | Kalendererkennung für Sitzungen → Protokollentwurf im Hausformat (AG: § 107 AktG; GmbH: § 48 GmbHG) |
| **gesellschafterbeschluss** | Organe & Protokoll | Beschlüsse im schriftlichen Verfahren § 48 II GmbHG mit Mustersuche aus dem Beschluss-Repository; Hinweis bei wesentlichen Einzelmaßnahmen |
| **gesellschafts-compliance** | Gesellschafts-Compliance | Compliance-Kalender-Tracker (YAML); Einreichungsfristen nach Rechtsträger; Bilanzpublizität § 325 HGB; Transparenzregister § 20 GwG; Gesundheitsaudit; CSV-Export |
| **post-merger-integration** | M&A | Post-Closing-Integrationsplan; phasenweiser Arbeitsplan (Tag 1/30/90/180); Zustimmungsregister mit SPA-Fristen; Vertragsübertragung; Wochenstatusberichte |
| **mandat-arbeitsbereich** | Alle | Mandatsarbeitsbereiche erstellen, auflisten, wechseln und schließen für Mehrmandat-Kanzleien; isoliert jeden Mandanten/Auftrag, damit Kontext nicht übergreift |
| **gmbh-gruendung** | Compliance | GmbH-Gründung: Gesellschaftsvertrag, Stammkapital, Notar, Handelsregister, IHK, Gewerbe |
| **gesellschafterbeschluss-vorlagen** | Organe | Beschlussvorlagen GmbH/AG, Beschlussfähigkeit, Mehrheiten, Anfechtungsklage |
| **handelsregisteranmeldung** | Compliance | HRB/HRA-Anmeldungen, Änderungen, Kapitalmaßnahmen, notarielle Form |

## Interaktive Befehle vs. geplante Agenten

Die Befehle oben laufen, wenn du sie aufrufst – für das aktive Mandat. Die Agenten unten laufen nach Zeitplan – für das, was sich bewegt, während du nicht hinschaust:

| Agent | Modul | Was er beobachtet | Standard-Rhythmus |
|---|---|---|---|
| **datenraum-monitor** | M&A | VDR auf neue Dokumenten-Uploads; markiert Uploads, die zu Hochprioritätskategorien passen; aktualisiert Vollzugschecklisten-Status | Wöchentlich |

## Integrationen

**Verbinde zuerst ein Recherchetool – die Zitier-Absicherung hängt davon ab.** Ohne eines wird jedes Zitat mit `[prüfen]` markiert und der Prüfer-Hinweis über jedem Ergebnis vermerkt, dass Quellen nicht verifiziert wurden. Skills funktionieren in beiden Fällen; ein Recherchetool (amtliche oder frei zugängliche Quellen; lizenzierte Datenbanken nur bei vorhandenem Zugang, Westlaw DE) verlagert Verifikationsarbeit aus deiner Hand.

Mitgeliefert wird:

- **Slack** – Nachrichten suchen, Kanäle lesen, Diskussionen finden
- **Google Drive** – Dokumente suchen, lesen und abrufen
- **Box** – Datenraum und Dokumentenverwaltung

Datasite, Intralinks und weitere VDR-Connectoren können in `.mcp.json` ergänzt werden, wenn Partner-URLs verfügbar sind.

## Recht und Quellen

Maßgebliche Gesetze dieses Plugins:

- **GmbHG** – Gesetz betreffend die Gesellschaften mit beschränkter Haftung
- **AktG** – Aktiengesetz
- **HGB** – Handelsgesetzbuch (§§ 238 ff. Buchführung, §§ 290 ff. Konzernabschluss, § 325 Bilanzpublizität)
- **UmwG** – Umwandlungsgesetz (Verschmelzung, Spaltung, Formwechsel)
- **WpÜG** – Wertpapiererwerbs- und Übernahmegesetz (öffentliche Übernahmen, Pflichtangebote)
- **MoPeG** – Gesetz zur Modernisierung des Personengesellschaftsrechts (GbR-Reform 2024)
- **WEG** – Wohnungseigentumsgesetz (soweit gesellschaftsrechtlich relevant)
- **GwG** – Geldwäschegesetz (Transparenzregister § 20 GwG)

Zitierweise nach `../references/zitierweise.md` (BGH-Stil).

## Lernen

Dein Praxisprofil unter `~/.claude/plugins/config/claude-fuer-deutsches-recht/gesellschaftsrecht/CLAUDE.md` ist nicht statisch – es verbessert sich mit der Nutzung des Plugins. Skills informieren dich, wenn ein Ergebnis einen Standard verwendet, den du anpassen solltest. Du kannst das Setup erneut ausführen, die Datei direkt bearbeiten oder einem Skill mitteilen, eine neue Position zu speichern.

## M&A-Hinweise

- Die Issue-Extraktion wendet Wesentlichkeitsschwellen an – nicht jedes Dokument wird gelesen, wenn die Schwelle Top-N nach Wert vorschreibt.
- Käufer- und Verkäuferseite werden beide unterstützt. Das Praxisprofil erfasst, welche Seite für dieses Mandat gilt; Skills passen ihre Haltung entsprechend an.
- **Due Diligence:** DD läuft über Q&A-Prozess, Datenraum (VDR), Disclosure Letter und gesetzliche Auskunftsansprüche (§§ 242, 259, 666 BGB; Art. 15 DSGVO). Auskunftsansprüche im Streitfall: §§ 142, 144 ZPO; § 254 ZPO (Stufenklage).
- KI-Tool-Übergabe (Luminance/Kira) ist optional. Wenn das Praxisprofil kein Tool angibt, läuft alle Extraktion über den direkten Skill.
- Die Vollzugscheckliste wird aus dem SPA initialisiert und aktualisiert sich selbst, wenn die DD Zustimmungserfordernisse aufdeckt.


<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 28 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `beirat-kaltstart-und-zielbild` | GmbH-Beirat im Plugin gesellschaftsrecht: Beirat Kaltstart Und Zielbild; konkretisierter Spezial-Workflow mit Prüfachsen, Red Flags, Varianten, Quellenhygiene und verwertbarem Output. |
| `gesellschaftsrecht-kaltstart-interview` | Ersteinrichtungs-Interview für das gesellschaftsrechtliche Praxisprofil — erfasst Tätigkeitsbereiche (M&A, Gesellschafterversammlung/Aufsichtsrat, Kapitalmarkt, Gesellschaftsverwaltung), Wesentlichkeitsschwellen, Hausstil und Eskalations... |
| `kompendium-01-allgemein-bis-workflow-mandantenko` | gesellschaftsrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Allgemein, Anschluss Skills Router, Chronologie Und Belegmatrix, Fristen Und Risikoampel und 1 weitere Arbeitsmodule; mit Intake, Prüfroutine, Normen-/Quelle... |
| `kompendium-02-workflow-output-waeh-bis-spezial-personengese` | gesellschaftsrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Output Waehlen, Redteam Qualitygate, Fristen Mehrparteien Konflikt Und Interessen, Handelsregisteranmeldung Frist Naechster Schritt und 1 weitere Arbeitsmodu... |
| `kompendium-03-beirat-musterklausel-bis-agio-und-kapitalruec` | gesellschaftsrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Beirat Musterklauseln, Beirat Haftung, Geschaeftsfuehrer Haftung 43 Gmbhg, Geschaeftsfuehrerhaftung Fuer Compliance Versage und 1 weitere Arbeitsmodule; mit... |
| `kompendium-04-gesr-gesellschaftsfo-bis-beirat-bank-und-sani` | gesellschaftsrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Gesr Gesellschaftsformwahl Bauleiter, Aufsichtsrat Protokoll, Beirat Abgrenzung Aufsichtsrat, Beirat Amtszeit Und Rotation und 1 weitere Arbeitsmodule; mit I... |
| `kompendium-05-beirat-beratungsfunk-bis-beirat-budget-und-bu` | gesellschaftsrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Beirat Beratungsfunktion, Beirat Beschlussfassung, Beirat Beschlussmaengel, Beirat Bestellung Und Abberufung und 1 weitere Arbeitsmodule; mit Intake, Prüfrou... |
| `kompendium-06-beirat-compliance-un-bis-beirat-fakultativer` | gesellschaftsrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Beirat Compliance Und Internal Investigation, Beirat Datenschutz Und Ki, Beirat Deadlock Mechanik, Beirat Entscheidungsbefugnisse und 1 weitere Arbeitsmodule... |
| `kompendium-07-beirat-familiengesel-bis-beirat-immobilien-un` | gesellschaftsrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Beirat Familiengesellschaft, Beirat Geschaeftsfuehrerabberufung, Beirat Geschaeftsfuehrerbestellung, Beirat Geschaeftsordnung und 1 weitere Arbeitsmodule; mi... |
| `kompendium-08-beirat-informationsr-bis-beirat-kontrollfunkt` | gesellschaftsrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Beirat Informationsrechte, Beirat Insolvenznaehe, Beirat Interessenkonflikte, Beirat Katalog Wesentlicher Geschaefte und 1 weitere Arbeitsmodule; mit Intake,... |
| `kompendium-09-beirat-mitbestimmung-bis-beirat-register-und` | gesellschaftsrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Beirat Mitbestimmung Abgrenzung, Beirat Nachfolge, Beirat Private Equity Investor, Beirat Red Team Satzung und 1 weitere Arbeitsmodule; mit Intake, Prüfrouti... |
| `kompendium-10-beirat-satzungsgrund-bis-beirat-transaktionen` | gesellschaftsrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Beirat Satzungsgrundlage, Beirat Sitzung Und Protokoll, Beirat Startup Investor Director, Beirat Streit Gesellschafter und 1 weitere Arbeitsmodule; mit Intak... |
| `kompendium-11-beirat-verguetung-bis-dd-findings-extrakti` | gesellschaftsrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Beirat Verguetung, Beirat Verschwiegenheit, Beirat Veto Rechte, Beirat Zustimmungsvorbehalte und 1 weitere Arbeitsmodule; mit Intake, Prüfroutine, Normen-/Qu... |
| `kompendium-12-dealteam-zusammenfas-bis-gesellschaftsrecht-a` | gesellschaftsrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Dealteam Zusammenfassung, Gesellschafterbeschluss, Gesellschafterstreit Loesungsstrategie, Gesellschafts Compliance und 1 weitere Arbeitsmodule; mit Intake,... |
| `kompendium-13-gesellschaftsrecht-m-bis-gmbh-gruendung` | gesellschaftsrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Gesellschaftsrecht Mandat Arbeitsbereich, Gesr Corporate Governance Kodex Spezial, Gesr Gesellschafterversammlung Protokoll Leitfaden, Gesr Kgaa Und Se Spezi... |
| `kompendium-14-handelsregisteranmel-bis-rechtsabteilung-beir` | gesellschaftsrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Handelsregisteranmeldung, Integrations Management, Ki Werkzeug Uebergabe, Mandat Triage Gesellschaftsrecht und 1 weitere Arbeitsmodule; mit Intake, Prüfrouti... |
| `kompendium-15-rechtsabteilung-gese-bis-spezial-anmeldungen` | gesellschaftsrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Gesellschafterliste Und Registerstreit, Kapitalerhoehung Mit Bezugsrechtsausschluss, Stimmbindung Und Beschlussmangel Nach Hannover 9, Schriftliche Beschluss... |
| `kompendium-16-spezial-arbeitsberei-bis-spezial-diligence-do` | gesellschaftsrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Arbeitsbereich Mandantenentscheidung, Checklists Zahlen Schwellen Und Berechnung, Compliance Compliance Dokumentation Und Akte, Datenraum Behoerden Gericht U... |
| `kompendium-17-spezial-discovery-ri-bis-spezial-gmbh-tatbest` | gesellschaftsrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Discovery Risikoampel Und Gegenargumente, Gesellschafterbeschluesse Textbausteine, Gesellschafterstreit International Schnittstellen, Gesellschaftsrecht Erst... |
| `kompendium-18-spezial-livecheck-so-bis-vollzugs-checkliste` | gesellschaftsrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Livecheck Sonderfall Und Edge Case, Loesungsstrategie Formular Portal Und Einreichung, Mandat Red Team Und Qualitaetskontrolle, V90 Gesellschafterliste Regis... |
| `kompendium-19-wesentliche-vertraeg-bis-wesentliche-vertraeg` | gesellschaftsrecht: eigenständiger Arbeits-Skill zu Wesentliche Vertraege Anlage; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck. |
| `spezial-closing-livequellen-und-rechtsprechungscheck` | Closing: Livequellen- und Rechtsprechungscheck im Gesellschaftsrecht: fachlich vertiefter Spezialskill mit Normenradar (GmbHG/AktG/HGB/UmwG), Tatbestands-/Beweislastmatrix, Fristen- und Formcheck, Gegenargumenten, Fehlerbremse und direkt... |
| `spezial-rechtsquellen-beweislast-und-darlegungslast` | Rechtsquellen: Beweislast, Darlegungslast und Substantiierung im Gesellschaftsrecht: fachlich vertiefter Spezialskill mit Normenradar (GmbHG/AktG/HGB/UmwG), Tatbestands-/Beweislastmatrix, Fristen- und Formcheck, Gegenargumenten, Fehlerbr... |
| `tabellenpruefung` | 'Tabellarisches Vertragsreview als Prompt-Matrix — pro Spalte ein Extraktionsprompt (was wird gefragt), pro Zeile ein dokumentspezifischer Prompt (wie wird dieses Dokument behandelt). Eine Zeile pro Dokument, eine Spalte pro Datenpunkt,... |
| `workflow-dokumentenintake` | Dokumentenintake im Plugin gesellschaftsrecht: liest Uploads, sortiert Dokumentarten, markiert Fristen und baut eine knappe Arbeitsakte. |
| `workflow-kaltstart-und-routing` | Kaltstart und Routing im Plugin gesellschaftsrecht: führt vom ersten Satz oder Dokument in den passenden Arbeitsweg, erkennt Rolle, Ziel, Risiko und Anschluss-Skills. |
| `workflow-rechtsquellen-livecheck` | Rechtsquellen-Livecheck im Plugin gesellschaftsrecht: zwingt vor tragenden Aussagen zum aktuellen Quellencheck bei Gesetzen, Behörden, Gerichten und Formularen. |
| `workflow-unterlagen-lueckenliste` | Unterlagen- und Lückenliste im Plugin gesellschaftsrecht: erstellt eine präzise Nachforderungsliste statt allgemeiner Fragebögen. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
