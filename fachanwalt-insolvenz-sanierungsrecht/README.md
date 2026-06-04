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
| `komp-01-teil-02-workflow-redteam-qualitygate` | fachanwalt-insolvenz-sanierungsrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Redteam Qualitygate, Inso P004 Anwendbarkeit Der Zivilprozessordnung, Inso P036 Unpfandbare Gegenstande, Insolvenz Sanierungsrecht Schutzsc... |
| `komp-01-teil-03-inso-p001-ziele-des-insolvenzverfahrens` | fachanwalt-insolvenz-sanierungsrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Inso P001 Ziele Des Insolvenzverfahrens, Inso P003c Zustandigkeit Fur Gruppen Folgeverfahren, Inso P004a Stundung Der Kosten Des Insolvenzv... |
| `komp-01-teil-04-inso-p054-kosten-des-insolvenzverfahrens` | fachanwalt-insolvenz-sanierungsrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Inso P054 Kosten Des Insolvenzverfahrens, Inso P088 Vollstreckung Vor Verfahrenseroffnung, Inso P095 Eintritt Der Aufrechnungslage Im Verfa... |
| `komp-01-teil-05-inso-p126-beschlussverfahren-zum-kundigungsschut` | fachanwalt-insolvenz-sanierungsrecht: eigenständiger Arbeits-Skill zu Inso P126 Beschlussverfahren Zum Kundigungsschutz; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck. |
| `komp-03-teil-02-inso-p279-gegenseitige-vertrage` | fachanwalt-insolvenz-sanierungsrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Inso P279 Gegenseitige Vertrage, Inso P336 Vertrag Uber Einen Unbeweglichen Gegenstand, Inso P043 Haftung Mehrerer Personen, Inso P060 Haft... |
| `komp-03-teil-03-inso-p092-gesamtschaden` | fachanwalt-insolvenz-sanierungsrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Inso P092 Gesamtschaden, Inso P093 Personliche Haftung Der Gesellschafter, Inso P227 Haftung Des Schuldners, Inso P280 Haftung Insolvenzanf... |
| `komp-03-teil-04-inso-p155-handels-und-steuerrechtliche-rec` | fachanwalt-insolvenz-sanierungsrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Inso P155 Handels Und Steuerrechtliche Rechnungslegung, Steuerrecht Formular Portal Und Einreichung, Erstgespraech Mandatsannahme, Fa Inso... |
| `komp-03-teil-05-fa-insolvenz-schuldschein-und-lma` | fachanwalt-insolvenz-sanierungsrecht: eigenständiger Arbeits-Skill zu Fa Insolvenz Schuldschein Und Lma; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck. |
| `komp-04-teil-02-fachanwalt-insolvenz-sanierungsrecht-glaeu` | fachanwalt-insolvenz-sanierungsrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Insolvenz Sanierungsrecht Glaeubigerantrag, Insolvenz Sanierungsrecht Insolvenzanfechtung, Insolvenz Sanierungsrecht Orientierung, Insolven... |
| `komp-04-teil-03-insanw-eigenverwaltung-schutzschirm-spezia` | fachanwalt-insolvenz-sanierungsrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Insanw Eigenverwaltung Schutzschirm Spezial, Insanw Konzerninsolvenz Koordination Spezial, Inso Anfechtung Zahlungsstrom Banken, Inso Arbei... |
| `komp-04-teil-04-inso-kommunikation-glaeubiger` | fachanwalt-insolvenz-sanierungsrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Inso Kommunikation Glaeubiger, Inso P002 Amtsgericht Als Insolvenzgericht, Inso P003 Ortliche Zustandigkeit, Inso P003a Gruppen Gerichtssta... |
| `komp-04-teil-05-inso-p003d-verweisung-an-den-gruppen-geric` | fachanwalt-insolvenz-sanierungsrecht: eigenständiger Arbeits-Skill zu Inso P003d Verweisung An Den Gruppen Gerichtsstand; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck. |
| `komp-22-teil-02-spezial-eroeffnung-behoerden-gericht-und-r` | fachanwalt-insolvenz-sanierungsrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Eroeffnung Behoerden Gericht Und Registerweg, Fachanwalt Erstpruefung Und Mandatsziel, Fao Dokumentenmatrix Und Lueckenliste, Glaeubigerant... |
| `komp-22-teil-03-spezial-insolvenz-tatbestand-beweis-und-be` | fachanwalt-insolvenz-sanierungsrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Insolvenz Tatbestand Beweis Und Belege, Insolvenzanfechtung Compliance Dokumentation Und Akte, Insolvenzrecht Internationaler Bezug Und Sch... |
| `komp-22-teil-04-spezial-schnittstellen-mehrparteien-konfli` | fachanwalt-insolvenz-sanierungsrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Schnittstellen Mehrparteien Konflikt Und Interessen, Verwertung Beweislast Und Darlegungslast, Starug Spezial Restrukturierungsplan, V90 In... |
| `kompendium-01-allgemein-bis-inso-p126-beschlussv` | fachanwalt-insolvenz-sanierungsrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Allgemein, Insanw Fortbestehensprognose Workflow, Chronologie Und Belegmatrix, Fristen Und Risikoampel und 1 weitere Arbeitsmodule; mit Int... |
| `kompendium-02-inso-p139-berechnung-bis-inso-p356-sekundarin` | fachanwalt-insolvenz-sanierungsrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Inso P139 Berechnung Der Fristen Vor Dem Eroffnungsantrag, Inso P147 Rechtshandlungen Nach Verfahrenseroffnung, Inso P157 Entscheidung Uber... |
| `kompendium-03-spezial-livecheck-fr-bis-fa-insolvenz-schulds` | fachanwalt-insolvenz-sanierungsrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Livecheck Fristennotiz Und Naechster Schritt, Sanierungsrecht Fristen Form Und Zustaendigkeit, Inso P104 Fixgeschafte Finanzleistungen Vert... |
| `kompendium-04-fachanwalt-insolvenz-bis-inso-p003d-verweisun` | fachanwalt-insolvenz-sanierungsrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Insolvenz Glaeubigerverhandlung Sanierung, Insolvenz Idw S6 Sanierungskonzept, Insolvenz Krypto Verwertung, Insolvenz Sanierung Starug Plan... |
| `kompendium-05-inso-p003e-unternehm-bis-inso-p019-uberschuld` | fachanwalt-insolvenz-sanierungsrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Inso P003e Unternehmensgruppe, Inso P004b Ruckzahlung Und Anpassung Der Gestundeten Betrage, Inso P004c Aufhebung Der Stundung, Inso P004d... |
| `kompendium-06-inso-p020-auskunfts-bis-inso-p039-nachrangig` | fachanwalt-insolvenz-sanierungsrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Inso P020 Auskunfts Und Mitwirkungspflicht Im Eroffnungsverfahre, Inso P021 Anordnung Vorlaufiger Massnahmen, Inso P022 Rechtsstellung Des... |
| `kompendium-07-inso-p040-unterhalts-bis-inso-p059-entlassung` | fachanwalt-insolvenz-sanierungsrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Inso P040 Unterhaltsanspruche, Inso P041 Nicht Fallige Forderungen, Inso P042 Auflosend Bedingte Forderungen, Inso P044 Rechte Der Gesamtsc... |
| `kompendium-08-inso-p061-nichterful-bis-inso-p082-leistungen` | fachanwalt-insolvenz-sanierungsrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Inso P061 Nichterfullung Von Masseverbindlichkeiten, Inso P062 Verjahrung, Inso P063 Vergutung Des Insolvenzverwalters, Inso P064 Festsetzu... |
| `kompendium-09-inso-p083-erbschaft-bis-inso-p108-fortbesteh` | fachanwalt-insolvenz-sanierungsrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Inso P083 Erbschaft Fortgesetzte Gutergemeinschaft, Inso P084 Auseinandersetzung Einer Gesellschaft Oder Gemeinschaf, Inso P085 Aufnahme Vo... |
| `kompendium-10-inso-p109-schuldner-bis-inso-p133-vorsatzlic` | fachanwalt-insolvenz-sanierungsrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Inso P109 Schuldner Als Mieter Oder Pachter, Inso P110 Schuldner Als Vermieter Oder Verpachter, Inso P111 Verausserung Des Miet Oder Pachto... |
| `kompendium-11-inso-p134-unentgeltl-bis-inso-p158-massnahmen` | fachanwalt-insolvenz-sanierungsrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Inso P134 Unentgeltliche Leistung, Inso P135 Gesellschafterdarlehen, Inso P136 Stille Gesellschaft, Inso P137 Wechsel Und Scheckzahlungen u... |
| `kompendium-12-inso-p159-verwertung-bis-inso-p179-streitige` | fachanwalt-insolvenz-sanierungsrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Inso P159 Verwertung Der Insolvenzmasse, Inso P160 Besonders Bedeutsame Rechtshandlungen, Inso P161 Vorlaufige Untersagung Der Rechtshandlu... |
| `kompendium-13-inso-p180-zustandigk-bis-inso-p202-zustandigk` | fachanwalt-insolvenz-sanierungsrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Inso P180 Zustandigkeit Fur Die Feststellung, Inso P181 Umfang Der Feststellung, Inso P182 Streitwert, Inso P183 Wirkung Der Entscheidung u... |
| `kompendium-14-inso-p203-anordnung-bis-inso-p223-rechte-der` | fachanwalt-insolvenz-sanierungsrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Inso P203 Anordnung Der Nachtragsverteilung, Inso P204 Rechtsmittel, Inso P205 Vollzug Der Nachtragsverteilung, Inso P206 Ausschluss Von Ma... |
| `kompendium-15-inso-p223a-gruppenin-bis-inso-p241-gesonderte` | fachanwalt-insolvenz-sanierungsrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Inso P223a Gruppeninterne Drittsicherheiten, Inso P224 Rechte Der Insolvenzglaubiger, Inso P225 Rechte Der Nachrangigen Insolvenzglaubiger,... |
| `kompendium-16-inso-p242-schriftlic-bis-inso-p259a-vollstrec` | fachanwalt-insolvenz-sanierungsrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Inso P242 Schriftliche Abstimmung, Inso P243 Abstimmung In Gruppen, Inso P244 Erforderliche Mehrheiten, Inso P245 Obstruktionsverbot und 17... |
| `kompendium-17-inso-p260-uberwachun-bis-inso-p270e-aufhebung` | fachanwalt-insolvenz-sanierungsrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Inso P260 Uberwachung Der Planerfullung, Inso P261 Aufgaben Und Befugnisse Des Insolvenzverwalters, Inso P262 Anzeigepflicht Des Insolvenzv... |
| `kompendium-18-inso-p270f-anordnung-bis-inso-p288-bestimmung` | fachanwalt-insolvenz-sanierungsrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Inso P270f Anordnung Der Eigenverwaltung, Inso P270g Eigenverwaltung Bei Gruppenangehorigen Schuldnern, Inso P271 Nachtragliche Anordnung,... |
| `kompendium-19-inso-p290-versagung-bis-inso-p307-zustellung` | fachanwalt-insolvenz-sanierungsrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Inso P290 Versagung Der Restschuldbefreiung, Inso P291 Weggefallen, Inso P292 Rechtsstellung Des Treuhanders, Inso P293 Vergutung Des Treuh... |
| `kompendium-20-inso-p308-annahme-de-bis-inso-p333-antragsrec` | fachanwalt-insolvenz-sanierungsrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Inso P308 Annahme Des Schuldenbereinigungsplans, Inso P309 Ersetzung Der Zustimmung, Inso P310 Kosten, Inso P312bis314 Weggefallen und 17 w... |
| `kompendium-21-inso-p335-grundsatz-bis-inso-p358-uberschuss` | fachanwalt-insolvenz-sanierungsrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Inso P335 Grundsatz, Inso P337 Arbeitsverhaltnis, Inso P338 Aufrechnung, Inso P339 Insolvenzanfechtung und 17 weitere Arbeitsmodule; mit In... |
| `kompendium-22-inso-p359-verweisung-bis-vergleichsverhandlun` | fachanwalt-insolvenz-sanierungsrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Inso P359 Verweisung Auf Das Einfuhrungsgesetz, Schriftsatzkern Substantiierung, Antragspflicht Schriftsatz Brief Und Memo Bausteine, Berat... |
| `spezial-rechtsquellen-sonderfall-und-edge-case` | Rechtsquellen: Sonderfall und Edge-Case-Prüfung im Insolvenz- und Sanierungsrecht: fachlich vertiefter Spezialskill mit Normenradar (InsO/StaRUG/IDW-S6), Tatbestands-/Beweislastmatrix, Fristen- und Formcheck, Gegenargumenten, Fehlerbrems... |
| `spezial-starug-livequellen-und-rechtsprechungscheck` | StaRUG: Livequellen- und Rechtsprechungscheck im Insolvenz- und Sanierungsrecht: fachlich vertiefter Spezialskill mit Normenradar (InsO/StaRUG/IDW-S6), Tatbestands-/Beweislastmatrix, Fristen- und Formcheck, Gegenargumenten, Fehlerbremse... |
| `workflow-anschluss-skills-router` | Anschluss-Skills Router im Plugin fachanwalt-insolvenz-sanierungsrecht: schlägt nach der ersten Prüfung die passenden Spezialskills aus demselben Plugin vor. |
| `workflow-dokumentenintake` | Dokumentenintake im Plugin fachanwalt-insolvenz-sanierungsrecht: liest Uploads, sortiert Dokumentarten, markiert Fristen und baut eine knappe Arbeitsakte. |
| `workflow-kaltstart-und-routing` | Kaltstart und Routing im Plugin fachanwalt-insolvenz-sanierungsrecht: führt vom ersten Satz oder Dokument in den passenden Arbeitsweg, erkennt Rolle, Ziel, Risiko und Anschluss-Skills. |
| `workflow-output-waehlen` | Output wählen im Plugin fachanwalt-insolvenz-sanierungsrecht: entscheidet zwischen Memo, Schriftsatz, Tabelle, Brief, Checkliste, Vermerk, Redline oder Mandantenübersetzung. |
| `workflow-rechtsquellen-livecheck` | Rechtsquellen-Livecheck im Plugin fachanwalt-insolvenz-sanierungsrecht: zwingt vor tragenden Aussagen zum aktuellen Quellencheck bei Gesetzen, Behörden, Gerichten und Formularen. |
| `workflow-unterlagen-lueckenliste` | Unterlagen- und Lückenliste im Plugin fachanwalt-insolvenz-sanierungsrecht: erstellt eine präzise Nachforderungsliste statt allgemeiner Fragebögen. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
