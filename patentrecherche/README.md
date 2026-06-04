# patentrecherche

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`patentrecherche`) | [`patentrecherche.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/patentrecherche.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **FTO-Recherche Rotorblattheizung — Windsysteme Norderhof AG vs. Vellbruck Energietechnik / EP 3 218 922 B1** (`fto-recherche-windkraft-rotorblattheizung-windsysteme-norderhof-eppendorfer-stadter`) | [Gesamt-PDF lesen](../testakten/fto-recherche-windkraft-rotorblattheizung-windsysteme-norderhof-eppendorfer-stadter/gesamt-pdf/fto-recherche-windkraft-rotorblattheizung-windsysteme-norderhof-eppendorfer-stadter_gesamt.pdf) | [`testakte-fto-recherche-windkraft-rotorblattheizung-windsysteme-norderhof-eppendorfer-stadter.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-fto-recherche-windkraft-rotorblattheizung-windsysteme-norderhof-eppendorfer-stadter.zip) |
| **Patentrecht — Erfindungsakten Ravenstein & Moll** (`patentrecht-erfindungsakten-ravenstein-moll`) | [Gesamt-PDF lesen](../testakten/patentrecht-erfindungsakten-ravenstein-moll/gesamt-pdf/patentrecht-erfindungsakten-ravenstein-moll_gesamt.pdf) | [`testakte-patentrecht-erfindungsakten-ravenstein-moll.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-patentrecht-erfindungsakten-ravenstein-moll.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

> Plugin für **Patentanwältinnen und Patentanwälte**, das Claude Cowork agentisch durch die klassischen Patentdatenbanken führt — Espacenet, Google Patents, DPMAregister, DEPATISnet, EPO Register, WIPO PATENTSCOPE, USPTO. Vorrecherche, **keine amtliche Recherche**.

## Hinweis vorab

Dieses Plugin ist **Vorrecherche-Werkzeug** für die Patentanwaltspraxis. Es ersetzt nicht die amtliche Recherche durch DPMA oder EPA und nicht die finale Bewertung durch die Patentanwältin. Treffer können unvollständig sein, falsch klassifiziert sein, in nicht maschinenlesbaren Volltexten verborgen sein oder durch Patentfamilien-Verbindungen verfehlt werden. Die abschließende Recherche muss durch eigene Nachrecherche oder durch Überprüfung der Treffer abgesichert werden.

Das Plugin ist Teil des Repositories [`claude-fuer-deutsches-recht`](../) und wurde mit Hilfe eines KI-Code-Assistenten erstellt; die inhaltliche Verantwortung trägt der Autor (Klotzkette).

## Inhalt

14 Skills, 3 References. Die methodische Grundlage stammt aus den Querschnitts-Plugins [`methodenlehre-buergerliches-recht`](../methodenlehre-buergerliches-recht) und [`zitierweise-deutsches-recht`](../zitierweise-deutsches-recht), die parallel aktiviert sein sollten.

### Skills

| Skill | Funktion |
| --- | --- |
| `patentrecherche-kaltstart-interview` | Setup: Patentanwältin, Mandant, Erfindung, Recherchezweck, Rechtsraum |
| `klassifikation-cpc-ipc` | CPC- und IPC-Klassen für die Recherche bestimmen |
| `agentische-datenbank-recherche` | Master-Skill: agentische Bedienung von Espacenet, Google Patents, DPMAregister, DEPATISnet, EPO Register, WIPO PATENTSCOPE, USPTO |
| `stand-der-technik-recherche` | Vorrecherche für Neuheitsbewertung vor eigener Anmeldung |
| `neuheit-pruefen` | § 3 PatG / Art. 54 EPÜ — Einzeldokument-Vorwegnahme aller Merkmale |
| `erfinderische-taetigkeit-pruefen` | § 4 PatG / Art. 56 EPÜ — Problem-Solution-Approach (EPA-Beschwerdekammern) |
| `freedom-to-operate-recherche` | FTO — Patentverletzungsrisiko aus Drittpatenten vor Markteintritt |
| `patentfamilien-analyse` | INPADOC-Familie — weltweite Patente mit gleichem Prioritätstag |
| `rechtsstand-pruefen` | Anmeldetag, Erteilung, Erlöschen, Einspruch, Nichtigkeit |
| `ueberwachung-konkurrenten` | Monitoring neuer Anmeldungen bestimmter Anmelder oder Klassen |
| `pruefungsbescheid-vorbereiten` | EPA- oder DPMA-Bescheid systematisch entgegnen, Stand-der-Technik-Entgegenhaltungen einordnen |
| `recherchebericht-erstellen` | Formaler Output mit Treffern, Bewertung, Disclaimer |
| `rueckfragen-mandant` | Erfindungsabgrenzung klären — Was ist der wesentliche Lösungsbeitrag |

### References

- `cpc-ipc-klassen-uebersicht.md` — CPC- und IPC-Hauptsektionen, Querverweis-Logik
- `patentdatenbanken-quellen.md` — Datenbanken im Detail (URL, Abdeckung, Stärken, Schwächen, agentische Bedienung)
- `bpatg-und-epa-rspr-leitentscheidungen.md` — Leitentscheidungen Patentanwaltspraxis (BGH X. Senat, BPatG, EPA G-Entscheidungen)

## Setup

Nach Aktivierung des Plugins wird beim ersten Lauf von `patentrecherche-kaltstart-interview` ein Profil unter `~/.claude/plugins/config/claude-fuer-deutsches-recht/patentrecherche/CLAUDE.md` angelegt (Kanzlei, Patentanwält:innen, Schwerpunktklassen, typische Mandantenstruktur).

## Pflichtdisclaimer

Jedes Recherche-Ergebnis enthält am Anfang den Disclaimer "**Hinweis zur Recherche** — KI-gestützte Vorrecherche, keine amtliche Recherche, finale Bewertung muss eigenständig abgesichert werden". Skills lassen den Disclaimer nicht weg.

## Verhältnis zum Berufsrecht

Patentanwältinnen sind Berufsgeheimnisträger nach § 203 Abs. 1 Nr. 3 StGB; § 39a PAO regelt die Verschwiegenheit, § 39c PAO regelt die Inanspruchnahme von Dienstleistern. Vor produktivem Einsatz eines KI-Dienstleisters: berufsrechtliche Vorprüfung mit dem Schwester-Plugin [`berufsrecht-ki-vertragspruefung`](../berufsrecht-ki-vertragspruefung) durchführen.

## Lizenz

Apache-2.0 OR MIT. Siehe Repository-Stammverzeichnis.


<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 24 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `kompendium-01-allgemein-bis-workflow-fristen-und` | patentrecherche: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Allgemein, Chronologie Und Belegmatrix, Fristen Und Risikoampel; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck. |
| `kompendium-02-workflow-mandantenko-bis-spezial-agentisch-fr` | patentrecherche: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Mandantenkommunikation, Redteam Qualitygate, Agentisch Fristen Form Und Zustaendigkeit; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster... |
| `kompendium-03-spezial-taetigkeit-f-bis-epo-opposition-strat` | patentrecherche: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Taetigkeit Fristennotiz Und Naechster Schritt, Agentische Datenbank Recherche, Epo Opposition Strategie; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislo... |
| `kompendium-04-erfinderische-taetig-bis-ki-und-patent-strate` | patentrecherche: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Erfinderische Taetigkeit Pruefen, Freedom To Operate Recherche, Ki Und Patent Strategie; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuste... |
| `kompendium-05-klassifikation-cpc-i-bis-patentfamilien-analy` | patentrecherche: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Klassifikation Cpc Ipc, Neuheit Pruefen, Patentfamilien Analyse; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck. |
| `kompendium-06-patr-fto-bericht-lei-bis-patr-recherchestrate` | patentrecherche: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Patr Fto Bericht Leitfaden, Patr Patentfamilie Priodatum Spezial, Patr Recherchestrategie Bauleiter; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik,... |
| `kompendium-07-patr-software-ki-pat-bis-pruefungsbescheid-vo` | patentrecherche: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Patr Software Ki Patentierbarkeit Spezial, Pr Einfuehrung Recherchearten, Pruefungsbescheid Vorbereiten; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislo... |
| `kompendium-08-recherche-strategie-bis-recherchebericht-ers` | patentrecherche: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Recherche Strategie Keywords Und Klassen, Recherche Tools Marktuebersicht, Recherchebericht Erstellen; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogi... |
| `kompendium-09-rechtsstand-pruefen-bis-spezial-depatisnet-v` | patentrecherche: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Rechtsstand Pruefen, Rueckfragen Mandant, Depatisnet Verhandlung Vergleich Und Eskalation; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmus... |
| `kompendium-10-spezial-dpmaregister-bis-spezial-erfinderisch` | patentrecherche: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Dpmaregister Schriftsatz Brief Und Memo Bausteine, Epue Beweislast Und Darlegungslast, Erfinderische Sonderfall Und Edge Case; mit Intake, Prüfroutine, Normen-/... |
| `kompendium-11-spezial-espacenet-do-bis-spezial-neuheit-red` | patentrecherche: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Espacenet Dokumentenmatrix Und Lueckenliste, Google Risikoampel Und Gegenargumente, Neuheit Red Team Und Qualitaetskontrolle; mit Intake, Prüfroutine, Normen-/Q... |
| `kompendium-12-spezial-patentanwael-bis-spezial-patents-beho` | patentrecherche: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Patentanwaelte Tatbestand Beweis Und Belege, Patentrecherche Erstpruefung Und Mandatsziel, Patents Behoerden Gericht Und Registerweg; mit Intake, Prüfroutine, N... |
| `kompendium-13-spezial-patg-mandant-bis-spezial-register-zah` | patentrecherche: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Patg Mandantenkommunikation Entscheidungsvorlage, Problem Abschlussprodukt Und Uebergabe, Register Zahlen Schwellen Und Berechnung; mit Intake, Prüfroutine, Nor... |
| `kompendium-14-spezial-stand-intern-bis-spezial-uspto-mehrpa` | patentrecherche: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Stand Internationaler Bezug Und Schnittstellen, Technik Formular Portal Und Einreichung, Uspto Mehrparteien Konflikt Und Interessen; mit Intake, Prüfroutine, No... |
| `kompendium-15-spezial-wipo-complia-bis-ueberwachung-konkurr` | patentrecherche: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Wipo Compliance Dokumentation Und Akte, Stand Der Technik Recherche, Ueberwachung Konkurrenten; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outp... |
| `kompendium-16-upc-unified-patent-c-bis-upc-unified-patent-c` | patentrecherche: eigenständiger Arbeits-Skill zu Upc Unified Patent Court Spezial; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck. |
| `patentrecherche-kaltstart-interview` | Kaltstart-Interview für das Patentrecherche-Plugin. Stellt fest wer recherchiert (Patentanwaeltin Patentanwalt Patentassessor Patentingenieur Recherchekraft) welche Kanzlei und welche Technikgebiete (Mechanik Elektrotechnik Chemie Biotec... |
| `spezial-epo-livequellen-und-rechtsprechungscheck` | EPO: Livequellen- und Rechtsprechungscheck im Plugin patentrecherche; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Standardprüfung. |
| `workflow-anschluss-skills-router` | Anschluss-Skills Router im Plugin patentrecherche: schlägt nach der ersten Prüfung die passenden Spezialskills aus demselben Plugin vor. |
| `workflow-dokumentenintake` | Dokumentenintake im Plugin patentrecherche: liest Uploads, sortiert Dokumentarten, markiert Fristen und baut eine knappe Arbeitsakte. |
| `workflow-kaltstart-und-routing` | Kaltstart und Routing im Plugin patentrecherche: führt vom ersten Satz oder Dokument in den passenden Arbeitsweg, erkennt Rolle, Ziel, Risiko und Anschluss-Skills. |
| `workflow-output-waehlen` | Output wählen im Plugin patentrecherche: entscheidet zwischen Memo, Schriftsatz, Tabelle, Brief, Checkliste, Vermerk, Redline oder Mandantenübersetzung. |
| `workflow-rechtsquellen-livecheck` | Rechtsquellen-Livecheck im Plugin patentrecherche: zwingt vor tragenden Aussagen zum aktuellen Quellencheck bei Gesetzen, Behörden, Gerichten und Formularen. |
| `workflow-unterlagen-lueckenliste` | Unterlagen- und Lückenliste im Plugin patentrecherche: erstellt eine präzise Nachforderungsliste statt allgemeiner Fragebögen. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
