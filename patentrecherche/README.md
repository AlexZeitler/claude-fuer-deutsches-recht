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
| `allgemein-workflow-chronologie-workflow-fristen` | Allgemein, Workflow Chronologie Und Belegmatrix, Workflow Fristen Und Risikoampel: Allgemein; Workflow Chronologie Und Belegmatrix; Workflow Fristen Und Risikoampel. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmus... |
| `dpmaregister-epue-beweislast-erfinderische-sonderfall` | Spezial Dpmaregister Schriftsatz Brief Und Memo Bausteine, Spezial Epue Beweislast Und Darlegungslast, Spezial Erfinderische Sonderfall Und Edge Case: Spezial Dpmaregister Schriftsatz Brief Und Memo Bausteine; Spezial Epue Beweislast Und... |
| `erfinderische-taetigkeit-freedom-to-ki-patent` | Erfinderische Taetigkeit Prüfen, Freedom To Operate Recherche, Ki Und Patent Strategie: Erfinderische Taetigkeit Prüfen; Freedom To Operate Recherche; Ki Und Patent Strategie. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik,... |
| `espacenet-google-neuheit-red` | Spezial Espacenet Dokumentenmatrix Und Lueckenliste, Spezial Google Risikoampel Und Gegenargumente, Spezial Neuheit Red Team Und Qualitaetskontrolle: Spezial Espacenet Dokumentenmatrix Und Lueckenliste; Spezial Google Risikoampel Und Geg... |
| `klassifikation-cpc-neuheit-patentfamilien-analyse` | Klassifikation Cpc Ipc, Neuheit Prüfen, Patentfamilien Analyse: Klassifikation Cpc Ipc; Neuheit Prüfen; Patentfamilien Analyse. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zusammen. |
| `patentanwaelte-patentrecherche-patents` | Spezial Patentanwaelte Tatbestand Beweis Und Belege, Spezial Patentrecherche Erstpruefung Und Mandatsziel, Spezial Patents Behörden Gericht Und Registerweg: Spezial Patentanwaelte Tatbestand Beweis Und Belege; Spezial Patentrecherche Ers... |
| `patentrecherche-kaltstart-interview` | Kaltstart-Interview für das Patentrecherche-Plugin. Stellt fest wer recherchiert (Patentanwaeltin Patentanwalt Patentassessor Patentingenieur Recherchekraft) welche Kanzlei und welche Technikgebiete (Mechanik Elektrotechnik Chemie Biotec... |
| `patg-problem-register` | Spezial Patg Mandantenkommunikation Entscheidungsvorlage, Spezial Problem Abschlussprodukt Und Übergabe, Spezial Register Zahlen Schwellen Und Berechnung: Spezial Patg Mandantenkommunikation Entscheidungsvorlage; Spezial Problem Abschlus... |
| `patr-fto-bericht-patentfamilie-priodatum-recherchestrategie` | Patr Fto Bericht Leitfaden, Patr Patentfamilie Priodatum Spezial, Patr Recherchestrategie Bauleiter: Patr Fto Bericht Leitfaden; Patr Patentfamilie Priodatum Spezial; Patr Recherchestrategie Bauleiter. Führt Intake, Prüfroutine, Normen-/... |
| `patr-software-pr-einfuehrung-pruefungsbescheid-vorbereiten` | Patr Software Ki Patentierbarkeit Spezial, Pr Einfuehrung Recherchearten, Pruefungsbescheid Vorbereiten: Patr Software Ki Patentierbarkeit Spezial; Pr Einfuehrung Recherchearten; Pruefungsbescheid Vorbereiten. Führt Intake, Prüfroutine,... |
| `recherche-strategie-tools-marktuebersicht-recherchebericht` | Recherche Strategie Keywords Und Klassen, Recherche Tools Marktuebersicht, Recherchebericht Erstellen: Recherche Strategie Keywords Und Klassen; Recherche Tools Marktuebersicht; Recherchebericht Erstellen. Führt Intake, Prüfroutine, Norm... |
| `rechtsstand-pruefen-rueckfragen-mandant-depatisnet` | Rechtsstand Prüfen, Rueckfragen Mandant, Spezial Depatisnet Verhandlung Vergleich Und Eskalation: Rechtsstand Prüfen; Rueckfragen Mandant; Spezial Depatisnet Verhandlung Vergleich Und Eskalation. Führt Intake, Prüfroutine, Normen-/Quelle... |
| `spezial-epo-livequellen-und-rechtsprechungscheck` | EPO: Livequellen- und Rechtsprechungscheck im Plugin patentrecherche; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Standardprüfung. |
| `stand-technik-uspto-interessen` | Spezial Stand Internationaler Bezug Und Schnittstellen, Spezial Technik Formular Portal Und Einreichung, Spezial Uspto Mehrparteien Konflikt Und Interessen: Spezial Stand Internationaler Bezug Und Schnittstellen; Spezial Technik Formular... |
| `taetigkeit-fristennotiz-agentische-datenbank-epo-opposition` | Spezial Taetigkeit Fristennotiz Und Naechster Schritt, Agentische Datenbank Recherche, Epo Opposition Strategie: Spezial Taetigkeit Fristennotiz Und Naechster Schritt; Agentische Datenbank Recherche; Epo Opposition Strategie. Führt Intak... |
| `upc-unified` | Upc Unified Patent Court Spezial: Upc Unified Patent Court Spezial. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zusammen. |
| `wipo-stand-technik-ueberwachung-konkurrenten` | Spezial Wipo Compliance Dokumentation Und Akte, Stand Der Technik Recherche, Ueberwachung Konkurrenten: Spezial Wipo Compliance Dokumentation Und Akte; Stand Der Technik Recherche; Ueberwachung Konkurrenten. Führt Intake, Prüfroutine, No... |
| `workflow-anschluss-skills-router` | Anschluss-Skills Router im Plugin patentrecherche: schlägt nach der ersten Prüfung die passenden Spezialskills aus demselben Plugin vor. |
| `workflow-dokumentenintake` | Dokumentenintake im Plugin patentrecherche: liest Uploads, sortiert Dokumentarten, markiert Fristen und baut eine knappe Arbeitsakte. |
| `workflow-kaltstart-und-routing` | Kaltstart und Routing im Plugin patentrecherche: führt vom ersten Satz oder Dokument in den passenden Arbeitsweg, erkennt Rolle, Ziel, Risiko und Anschluss-Skills. |
| `workflow-mandantenkommunikation-workflow-redteam-agentisch` | Workflow Mandantenkommunikation, Workflow Redteam Qualitygate, Spezial Agentisch Fristen Form Und Zustaendigkeit: Workflow Mandantenkommunikation; Workflow Redteam Qualitygate; Spezial Agentisch Fristen Form Und Zustaendigkeit. Führt Int... |
| `workflow-output-waehlen` | Output wählen im Plugin patentrecherche: entscheidet zwischen Memo, Schriftsatz, Tabelle, Brief, Checkliste, Vermerk, Redline oder Mandantenübersetzung. |
| `workflow-rechtsquellen-livecheck` | Rechtsquellen-Livecheck im Plugin patentrecherche: zwingt vor tragenden Aussagen zum aktuellen Quellencheck bei Gesetzen, Behörden, Gerichten und Formularen. |
| `workflow-unterlagen-lueckenliste` | Unterlagen- und Lückenliste im Plugin patentrecherche: erstellt eine präzise Nachforderungsliste statt allgemeiner Fragebögen. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
