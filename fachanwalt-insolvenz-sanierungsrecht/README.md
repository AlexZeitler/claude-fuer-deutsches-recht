# Fachanwalt Insolvenz- und Sanierungsrecht

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`fachanwalt-insolvenz-sanierungsrecht`) | [`fachanwalt-insolvenz-sanierungsrecht.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/fachanwalt-insolvenz-sanierungsrecht.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **Großbach Druckguss & Präzision GmbH & Co. KG — Schutzschirm und StaRUG-Optionen** (`starug-schutzschirm-grossbach-druckguss-erfurt`) | [Gesamt-PDF lesen](../testakten/starug-schutzschirm-grossbach-druckguss-erfurt/gesamt-pdf/starug-schutzschirm-grossbach-druckguss-erfurt_gesamt.pdf) | [`testakte-starug-schutzschirm-grossbach-druckguss-erfurt.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-starug-schutzschirm-grossbach-druckguss-erfurt.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

Plugin Fachanwalt für Insolvenz- und Sanierungsrecht nach FAO § 14 (idF nach Aufnahme StaRUG-Bereiche). Orientierung, Gläubigerantrag, Restrukturierungsplan StaRUG, Insolvenzanfechtung. Schnittstellen zum Plugin `insolvenzrecht` (operativ) und `steuerrecht-anwalt-und-berater`.

## InsO-Paragraphen-Navigator

Dieses Plugin enthält nun zu jedem aktuell im amtlichen InsO-Wortlaut geführten Paragraphen einen eigenen `inso-p...`-Skill. Der Navigator ist für die tägliche Fachanwaltsarbeit gedacht: Er führt nicht abstrakt durch die Insolvenzordnung, sondern fragt pro Norm nach Rolle, Verfahrensstand, Belegen, Fristen, Rechtsfolge, Gegenargumenten und dem nächsten verwertbaren Arbeitsergebnis.

Besonders hilfreich ist das bei Akten, in denen viele Ebenen gleichzeitig laufen: Eröffnungsantrag, Sicherungsmaßnahmen, Massezuordnung, Anfechtung, Forderungsprüfung, Insolvenzplan, Eigenverwaltung, Verbraucherinsolvenz, Nachlassinsolvenz oder internationales Insolvenzrecht. Weggefallene Vorschriften sind bewusst als Altfassungs- und Übergangsrechtsanker enthalten, damit alte Akten und ältere Rechtsprechung nicht versehentlich auf heutige Fälle übertragen werden.

Vor verbindlichen Aussagen prüft der jeweilige Skill den aktuellen Gesetzeswortlaut und verlangt für Rechtsprechung Gericht, Datum, Aktenzeichen und möglichst eine frei zugängliche amtliche oder gerichtliche Quelle. Literatur- und Datenbankfundstellen werden nicht aus Modellwissen behauptet.

## Installation in Claude Code

1. ZIP herunterladen (Link oben).
2. Claude Code → **Customize Plugins** → **Install from .zip** → Datei wählen.
3. Fertig.

## Enthaltene Skills

| Skill | Zweck |
| --- | --- |
| `fachanwalt-insolvenz-sanierungsrecht-orientierung` | FAO § 14, InsO, StaRUG, EuInsVO, Quellenprüfung. |
| `fachanwalt-insolvenz-sanierungsrecht-glaeubigerantrag` | Gläubigerantrag § 14 InsO, Forderungs- und Insolvenzgrundsglaubhaftmachung. |
| `fachanwalt-insolvenz-sanierungsrecht-restrukturierungsplan` | Restrukturierungsplan StaRUG, Gruppenbildung, gerichtliche Planbestätigung. |
| `fachanwalt-insolvenz-sanierungsrecht-insolvenzanfechtung` | Anfechtungstatbestände §§ 129 ff. InsO (Schenkungs-, Vorsatz-, Deckungsanfechtung). |
| `inso-p001-...` bis `inso-p359-...` | Paragraphen-Navigator zur aktuellen Insolvenzordnung: pro InsO-Norm ein eigener Workflow mit Beleg-, Fristen-, Risiko- und Quellenprüfung. |

## Lizenz

Apache-2.0 OR MIT — Auswahl beim Empfänger.


<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 45 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `eroeffnung-fachanwalt-fao-glaeubigerantrag-inso` | Spezial Eroeffnung Behörden Gericht Und Registerweg, Spezial Fachanwalt Erstpruefung Und Mandatsziel, Spezial Fao Dokumentenmatrix Und Lueckenliste, Spezial Glaeubigerantrag Verhandlung Vergleich Und Eskalation, Spezial Inso Risikoampel... |
| `fa-schuldschein` | Fa Insolvenz Schuldschein Und Lma: Fa Insolvenz Schuldschein Und Lma. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zusammen. |
| `glaeubigerantrag-insolvenzanfechtung-orientierung` | Fachanwalt Insolvenz Sanierungsrecht Glaeubigerantrag, Fachanwalt Insolvenz Sanierungsrecht Insolvenzanfechtung, Fachanwalt Insolvenz Sanierungsrecht Orientierung, Fachanwalt Insolvenz Sanierungsrecht Restrukturierungsplan, Insanw Anfech... |
| `glaeubigerverhandlung-sanierung-idw-s6-krypto-verwertung` | Fachanwalt Insolvenz Glaeubigerverhandlung Sanierung, Fachanwalt Insolvenz Idw S6 Sanierungskonzept, Fachanwalt Insolvenz Krypto Verwertung, Fachanwalt Insolvenz Sanierung Starug Plan, Fachanwalt Insolvenz Sanierungsrecht Anfechtungsklag... |
| `inso-insanw-eigenverwaltung-konzerninsolvenz-koordination` | Insanw Eigenverwaltung Schutzschirm Spezial, Insanw Konzerninsolvenz Koordination Spezial, Inso Anfechtung Zahlungsstrom Banken, Inso Arbeitnehmer Und Betriebsuebergang, Inso Grenzueberschreitend Eu Eir: Insanw Eigenverwaltung Schutzschi... |
| `inso-kommunikation-glaeubiger-p002-amtsgericht-p003-ortliche` | Inso Kommunikation Glaeubiger, Inso P002 Amtsgericht Als Insolvenzgericht, Inso P003 Ortliche Zustandigkeit, Inso P003A Gruppen Gerichtsstand, Inso P003B Fortbestehen Des Gruppen Gerichtsstands: Inso Kommunikation Glaeubiger; Inso P002 A... |
| `inso-livecheck-fristennotiz-sanierungsrecht-p104-fixgeschafte` | Spezial Livecheck Fristennotiz Und Naechster Schritt, Spezial Sanierungsrecht Fristen Form Und Zustaendigkeit, Inso P104 Fixgeschafte Finanzleistungen Vertragliches Liquidatio, Inso P116 Erloschen Von Geschaftsbesorgungsvertragen, Inso P... |
| `inso-p001-ziele-p003c-zustandigkeit-p004a-stundung-p005-p011` | Inso P001 Ziele Des Insolvenzverfahrens, Inso P003C Zustandigkeit Fur Gruppen Folgeverfahren, Inso P004A Stundung Der Kosten Des Insolvenzverfahrens, Inso P005 Verfahrensgrundsatze, Inso P011 Zulassigkeit Des Insolvenzverfahrens: Inso P0... |
| `inso-p003d` | Inso P003D Verweisung An Den Gruppen Gerichtsstand: Inso P003D Verweisung An Den Gruppen Gerichtsstand. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zusammen. |
| `inso-p003e-unternehmensgruppe-p004b-ruckzahlung-p004c-aufhebung` | Inso P003E Unternehmensgruppe, Inso P004B Ruckzahlung Und Anpassung Der Gestundeten Betrage, Inso P004C Aufhebung Der Stundung, Inso P004D Rechtsmittel, Inso P006 Sofortige Beschwerde und 16 weitere Themen: Inso P003E Unternehmensgruppe;... |
| `inso-p020-auskunfts-p021-anordnung-p022-rechtsstellung-p022a` | Inso P020 Auskunfts Und Mitwirkungspflicht Im Eroffnungsverfahre, Inso P021 Anordnung Vorlaufiger Massnahmen, Inso P022 Rechtsstellung Des Vorlaufigen Insolvenzverwalters, Inso P022A Bestellung Eines Vorlaufigen Glaubigerausschusses, Ins... |
| `inso-p040-unterhaltsanspruche-p041-nicht-p042-auflosend-p044` | Inso P040 Unterhaltsanspruche, Inso P041 Nicht Fallige Forderungen, Inso P042 Auflosend Bedingte Forderungen, Inso P044 Rechte Der Gesamtschuldner Und Burgen, Inso P044A Gesicherte Darlehen und 16 weitere Themen: Inso P040 Unterhaltsansp... |
| `inso-p054-kosten-p088-vollstreckung-p095-eintritt-p121-p124` | Inso P054 Kosten Des Insolvenzverfahrens, Inso P088 Vollstreckung Vor Verfahrenseroffnung, Inso P095 Eintritt Der Aufrechnungslage Im Verfahren, Inso P121 Betriebsanderungen Und Vermittlungsverfahren, Inso P124 Sozialplan Vor Verfahrense... |
| `inso-p061-nichterfullung-p062-verjahrung-p063-vergutung-p064` | Inso P061 Nichterfullung Von Masseverbindlichkeiten, Inso P062 Verjahrung, Inso P063 Vergutung Des Insolvenzverwalters, Inso P064 Festsetzung Durch Das Gericht, Inso P065 Verordnungsermachtigung und 16 weitere Themen: Inso P061 Nichterfu... |
| `inso-p083-erbschaft-p084-auseinandersetzung-p085-aufnahme-p086` | Inso P083 Erbschaft Fortgesetzte Gutergemeinschaft, Inso P084 Auseinandersetzung Einer Gesellschaft Oder Gemeinschaf, Inso P085 Aufnahme Von Aktivprozessen, Inso P086 Aufnahme Bestimmter Passivprozesse, Inso P087 Forderungen Der Insolven... |
| `inso-p092-gesamtschaden-p093-personliche-p227-haftung-p280` | Inso P092 Gesamtschaden, Inso P093 Personliche Haftung Der Gesellschafter, Inso P227 Haftung Des Schuldners, Inso P280 Haftung Insolvenzanfechtung, Inso P334 Personliche Haftung Der Ehegatten: Inso P092 Gesamtschaden; Inso P093 Personlic... |
| `inso-p109-schuldner-p110-als-p111-verausserung-p112-p113-p133` | Inso P109 Schuldner Als Mieter Oder Pachter, Inso P110 Schuldner Als Vermieter Oder Verpachter, Inso P111 Verausserung Des Miet Oder Pachtobjekts, Inso P112 Kundigungssperre, Inso P113 Kundigung Eines Dienstverhaltnisses und 16 weitere T... |
| `inso-p126` | Inso P126 Beschlussverfahren Zum Kundigungsschutz: Inso P126 Beschlussverfahren Zum Kundigungsschutz. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zusammen. |
| `inso-p134-unentgeltliche-p135-gesellschafterdarlehen-p136-stille` | Inso P134 Unentgeltliche Leistung, Inso P135 Gesellschafterdarlehen, Inso P136 Stille Gesellschaft, Inso P137 Wechsel Und Scheckzahlungen, Inso P138 Nahestehende Personen und 16 weitere Themen: Inso P134 Unentgeltliche Leistung; Inso P13... |
| `inso-p139-eroffnungsantrag-p147-rechtshandlungen-p157-p200` | Inso P139 Berechnung Der Fristen Vor Dem Eroffnungsantrag, Inso P147 Rechtshandlungen Nach Verfahrenseroffnung, Inso P157 Entscheidung Uber Den Fortgang Des Verfahrens, Inso P200 Aufhebung Des Insolvenzverfahrens, Inso P201 Rechte Der In... |
| `inso-p155-steuerrecht-erstgespraech-mandatsannahme-fa-insolvenz` | Inso P155 Handels Und Steuerrechtliche Rechnungslegung, Spezial Steuerrecht Formular Portal Und Einreichung, Erstgespraech Mandatsannahme, Fa Inso Drittstaaten Anerkennung Registervollzug, Fa Insolvenz Npl Und Distressed Debt: Inso P155... |
| `inso-p159-verwertung-p160-besonders-p161-vorlaufige-p162-p163` | Inso P159 Verwertung Der Insolvenzmasse, Inso P160 Besonders Bedeutsame Rechtshandlungen, Inso P161 Vorlaufige Untersagung Der Rechtshandlung, Inso P162 Betriebsverausserung An Besonders Interessierte, Inso P163 Betriebsverausserung Unte... |
| `inso-p180-zustandigkeit-p181-umfang-p182-streitwert-p183-wirkung` | Inso P180 Zustandigkeit Fur Die Feststellung, Inso P181 Umfang Der Feststellung, Inso P182 Streitwert, Inso P183 Wirkung Der Entscheidung, Inso P184 Klage Gegen Einen Widerspruch Des Schuldners und 16 weitere Themen: Inso P180 Zustandigk... |
| `inso-p203-anordnung-p204-rechtsmittel-p205-vollzug-p206-p207` | Inso P203 Anordnung Der Nachtragsverteilung, Inso P204 Rechtsmittel, Inso P205 Vollzug Der Nachtragsverteilung, Inso P206 Ausschluss Von Masseglaubigern, Inso P207 Einstellung Mangels Masse und 16 weitere Themen: Inso P203 Anordnung Der... |
| `inso-p223a-gruppeninterne-p224-rechte-p225-nachrangigen-p225a` | Inso P223A Gruppeninterne Drittsicherheiten, Inso P224 Rechte Der Insolvenzglaubiger, Inso P225 Rechte Der Nachrangigen Insolvenzglaubiger, Inso P225A Rechte Der Anteilsinhaber, Inso P226 Gleichbehandlung Der Beteiligten und 16 weitere T... |
| `inso-p242-schriftliche-p243-abstimmung-p244-erforderliche-p245` | Inso P242 Schriftliche Abstimmung, Inso P243 Abstimmung In Gruppen, Inso P244 Erforderliche Mehrheiten, Inso P245 Obstruktionsverbot, Inso P245A Schlechterstellung Bei Naturlichen Personen und 16 weitere Themen: Inso P242 Schriftliche Ab... |
| `inso-p260-uberwachung-p261-aufgaben-p262-anzeigepflicht-p263` | Inso P260 Uberwachung Der Planerfullung, Inso P261 Aufgaben Und Befugnisse Des Insolvenzverwalters, Inso P262 Anzeigepflicht Des Insolvenzverwalters, Inso P263 Zustimmungsbedurftige Geschafte, Inso P264 Kreditrahmen und 16 weitere Themen... |
| `inso-p270f-anordnung-p270g-eigenverwaltung-p271-nachtragliche` | Inso P270F Anordnung Der Eigenverwaltung, Inso P270G Eigenverwaltung Bei Gruppenangehorigen Schuldnern, Inso P271 Nachtragliche Anordnung, Inso P272 Aufhebung Der Anordnung, Inso P273 Offentliche Bekanntmachung und 16 weitere Themen: Ins... |
| `inso-p279-gegenseitige-p336-vertrag-p043-haftung-p060-p071` | Inso P279 Gegenseitige Vertrage, Inso P336 Vertrag Uber Einen Unbeweglichen Gegenstand, Inso P043 Haftung Mehrerer Personen, Inso P060 Haftung Des Insolvenzverwalters, Inso P071 Haftung Der Mitglieder Des Glaubigerausschusses: Inso P279... |
| `inso-p290-versagung-p291-weggefallen-p292-rechtsstellung-p293` | Inso P290 Versagung Der Restschuldbefreiung, Inso P291 Weggefallen, Inso P292 Rechtsstellung Des Treuhanders, Inso P293 Vergutung Des Treuhanders, Inso P294 Gleichbehandlung Der Glaubiger und 16 weitere Themen: Inso P290 Versagung Der Re... |
| `inso-p308-annahme-p309-ersetzung-p310-kosten-p312bis314-p315` | Inso P308 Annahme Des Schuldenbereinigungsplans, Inso P309 Ersetzung Der Zustimmung, Inso P310 Kosten, Inso P312Bis314 Weggefallen, Inso P315 Ortliche Zustandigkeit und 16 weitere Themen: Inso P308 Annahme Des Schuldenbereinigungsplans;... |
| `inso-p335-grundsatz-p337-arbeitsverhaltnis-p338-aufrechnung` | Inso P335 Grundsatz, Inso P337 Arbeitsverhaltnis, Inso P338 Aufrechnung, Inso P339 Insolvenzanfechtung, Inso P340 Organisierte Markte Pensionsgeschafte und 16 weitere Themen: Inso P335 Grundsatz; Inso P337 Arbeitsverhaltnis; Inso P338 Au... |
| `inso-p359-schriftsatzkern-substantiierung-antragspflicht-berater` | Inso P359 Verweisung Auf Das Einfuhrungsgesetz, Schriftsatzkern Substantiierung, Spezial Antragspflicht Schriftsatz Brief Und Memo Bausteine, Spezial Berater Red Team Und Qualitaetskontrolle, Spezial Chronologie Abschlussprodukt Und Über... |
| `inso-workflow-redteam-p004-anwendbarkeit-p036-unpfandbare` | Workflow Redteam Qualitygate, Inso P004 Anwendbarkeit Der Zivilprozessordnung, Inso P036 Unpfandbare Gegenstande, Fachanwalt Insolvenz Sanierungsrecht Schutzschirmverfahren, Inso Grundzuege Verfahrenstypen: Workflow Redteam Qualitygate;... |
| `insolvenz-insolvenzanfechtung-insolvenzrecht-krypto` | Spezial Insolvenz Tatbestand Beweis Und Belege, Spezial Insolvenzanfechtung Compliance Dokumentation Und Akte, Spezial Insolvenzrecht Internationaler Bezug Und Schnittstellen, Spezial Krypto Mandantenkommunikation Entscheidungsvorlage, S... |
| `interessen-verwertung-beweislast-starug-restrukturierungsplan` | Spezial Schnittstellen Mehrparteien Konflikt Und Interessen, Spezial Verwertung Beweislast Und Darlegungslast, Starug Spezial Restrukturierungsplan, Insolvenzanfechtung 129 Bis 147 Verteidigungsradar, Vergleichsverhandlung Strategie: Spe... |
| `spezial-rechtsquellen-sonderfall-und-edge-case` | Rechtsquellen: Sonderfall und Edge-Case-Prüfung im Insolvenz- und Sanierungsrecht: fachlich vertiefter Spezialskill mit Normenradar (InsO/StaRUG/IDW-S6), Tatbestands-/Beweislastmatrix, Fristen- und Formcheck, Gegenargumenten, Fehlerbrems... |
| `spezial-starug-livequellen-und-rechtsprechungscheck` | StaRUG: Livequellen- und Rechtsprechungscheck im Insolvenz- und Sanierungsrecht: fachlich vertiefter Spezialskill mit Normenradar (InsO/StaRUG/IDW-S6), Tatbestands-/Beweislastmatrix, Fristen- und Formcheck, Gegenargumenten, Fehlerbremse... |
| `workflow-allgemein-insanw-fortbestehensprognose-chronologie` | Allgemein, Insanw Fortbestehensprognose Workflow, Workflow Chronologie Und Belegmatrix, Workflow Fristen Und Risikoampel, Workflow Mandantenkommunikation: Allgemein; Insanw Fortbestehensprognose Workflow; Workflow Chronologie Und Belegma... |
| `workflow-anschluss-skills-router` | Anschluss-Skills Router im Plugin fachanwalt-insolvenz-sanierungsrecht: schlägt nach der ersten Prüfung die passenden Spezialskills aus demselben Plugin vor. |
| `workflow-dokumentenintake` | Dokumentenintake im Plugin fachanwalt-insolvenz-sanierungsrecht: liest Uploads, sortiert Dokumentarten, markiert Fristen und baut eine knappe Arbeitsakte. |
| `workflow-kaltstart-und-routing` | Kaltstart und Routing im Plugin fachanwalt-insolvenz-sanierungsrecht: führt vom ersten Satz oder Dokument in den passenden Arbeitsweg, erkennt Rolle, Ziel, Risiko und Anschluss-Skills. |
| `workflow-output-waehlen` | Output wählen im Plugin fachanwalt-insolvenz-sanierungsrecht: entscheidet zwischen Memo, Schriftsatz, Tabelle, Brief, Checkliste, Vermerk, Redline oder Mandantenübersetzung. |
| `workflow-rechtsquellen-livecheck` | Rechtsquellen-Livecheck im Plugin fachanwalt-insolvenz-sanierungsrecht: zwingt vor tragenden Aussagen zum aktuellen Quellencheck bei Gesetzen, Behörden, Gerichten und Formularen. |
| `workflow-unterlagen-lueckenliste` | Unterlagen- und Lückenliste im Plugin fachanwalt-insolvenz-sanierungsrecht: erstellt eine präzise Nachforderungsliste statt allgemeiner Fragebögen. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
