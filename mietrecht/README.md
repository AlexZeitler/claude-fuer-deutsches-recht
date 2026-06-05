# Mietrecht

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`mietrecht`) | [`mietrecht.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/mietrecht.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **Mietstreit Tannenkamp / Strassburger Immobilien GmbH — Altbau Leipzig-Plagwitz, Modernisierung und Mietminderung** (`mietstreit-altbau-rosenbluete-leipzig-modernisierung-und-minderung-tannenkamp`) | [Gesamt-PDF lesen](../testakten/mietstreit-altbau-rosenbluete-leipzig-modernisierung-und-minderung-tannenkamp/gesamt-pdf/mietstreit-altbau-rosenbluete-leipzig-modernisierung-und-minderung-tannenkamp_gesamt.pdf) | [`testakte-mietstreit-altbau-rosenbluete-leipzig-modernisierung-und-minderung-tannenkamp.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-mietstreit-altbau-rosenbluete-leipzig-modernisierung-und-minderung-tannenkamp.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

Mietrecht für Mieter und Vermieter sowie Wohnungseigentumsrecht mit ausschließlich amtlichen Mietspiegel-Quellen pro Bundesland und für Top- und Universitätsstädte. Workflows für Datenerhebung, Mieterhöhungs-Widerspruch, Mietsenkungsverlangen, Nebenkostenprüfung, Mieteranfragen, Kündigung, Kaution, WEG-Beschlussklage und Klageentwurf Amtsgericht.

## Rechtsstand und Quellen-Gate

Für aktuelle Mietrechts- und WEG-Fragen zuerst `/mietrecht:rechtsstand-mai-2026-faktenbank` laden. Der Skill enthält geprüfte freie Anker zu Mietpreisbremse, Modernisierung, Steckersolargeräten, virtueller Eigentümerversammlung, Verwalterabberufung, WEG-baulichen Veränderungen und Störerhaftung.

Keine BeckRS-, juris-, Kommentar- oder Aufsatzzitate aus Modellwissen. Rechtsprechung nur mit Gericht, Entscheidungsform, Datum, Aktenzeichen und freier Quelle; Mietspiegel nur aus amtlicher kommunaler Quelle oder der mitgelieferten Mietspiegel-Referenz.

## Installation in Claude Code

1. ZIP herunterladen (Link oben).
2. Claude Code → **Customize Plugins** → **Install from .zip** → Datei wählen.
3. Fertig. Skills sind sofort verfügbar.

> **Hinweis:** Für den ZIP-Upload muss das Archiv direkt `.claude-plugin/plugin.json`, `skills/`, `assets/` und `references/` im ZIP-Root enthalten. **Nicht** das komplette Repository-ZIP aus "Code → Download ZIP" verwenden.

## Enthaltene Skills

| Skill | Zweck |
| --- | --- |
| `allgemein` | Einstieg, Triage und Workflow-Routing im Plugin. Fragt Rolle (Vermieter/Mieter/WEG/Verwalter), Ziel, Fristen, Unterlagen und Risiken ab und schlägt passende Spezial-Skills vor. Bei stummem Upload reagiert der Skill eigenständig: ordnet das Material, prüft Eil- und Fristenhinweise, schlägt den passenden Spezial-Skill vor oder stellt genau eine gezielte Rückfrage. |
| `eigenbedarfskuendigung-erstellen` | Vermietersicht — entwerfe eine ordentliche Kündigung wegen Eigenbedarfs nach § 573 Abs. 2 Nr. 2 BGB. Prüfroutine deckt berechtigtes Interesse (Eigennutzung Familienangehörige Haushaltsangehörige) konkrete Begründ… |
| `klageentwurf-amtsgericht` | Beide Rollen — entwirf eine Klageschrift zum Amtsgericht in einer Mietsache. Sachliche Zuständigkeit für Wohnraummietsachen nach § 23 Nr. 2a GVG ohne Rücksicht auf den Streitwert; bei Geschäftsraummiete allgemeine… |
| `lage-und-ausstattung-erheben` | Strukturierte Datenerhebung für die Einordnung in den Mietspiegel — Adresse Baujahr Wohnfläche Bad Küche Heizung Wohnungsausstattung Gebäudeausstattung. Erfasst alle Merkmale die in qualifizierten Mietspiegeln als… |
| `mahnung-zahlungsverzug-mieter` | Vermietersicht — verfasse Mahnung und ggf. fristlose Kündigung bei Zahlungsverzug des Mieters. Prüfroutine deckt Verzug nach § 286 BGB Fälligkeit der Miete (§ 556b Abs. 1 BGB) Mahnschreiben Aufrechnungsverbot frist… |
| `mandat-triage-mietrecht` | Strukturierte Eingangs-Abfrage für mietrechtliche Mandate. Klärt Mandantenrolle (Vermieter/Mieter/WEG-Eigentümer/Verwalter), Gegenstand (Wohnraum/Gewerbe/WEG) und Sachgebiet (Kündigung, Mieterhöhung, Mietminderung, Modernisierung, Nebenkosten, Mietkaution, Eigenbedarf, Räumung, WEG-Beschluss, WEG-Hausgeld). Fristen-Sofort-Check (§ 573c BGB, § 721 ZPO, § 45 WEG, § 558b BGB). Eskalations-Pfad bei laufenden Fristen. |
| `mieteranfragen-beantworten` | Vermieter- und Hausverwaltungssicht — beantworte Mieteranfragen sachlich und ehrlich. Deckt typische Themen ab (Mietminderung Mangelanzeige Modernisierungsankündigung Schönheitsreparaturen Hausordnung Kaution Eigenb… |
| `mieterhoehung-pruefen-widersprechen` | Mietersicht — prüfe ein Mieterhöhungsverlangen nach ortsüblicher Vergleichsmiete (§§ 558 ff. BGB) auf Form Frist Kappungsgrenze Begründung und entwirf bei Bedarf eine Zustimmungsverweigerung oder Teilzustimmung. P… |
| `mieterhoehungsverlangen-erstellen` | Vermietersicht — verfasse ein Mieterhöhungsverlangen auf ortsübliche Vergleichsmiete (§ 558a BGB) in Textform mit ordnungsgemäßer Begründung (Mietspiegel Sachverständigengutachten oder drei Vergleichswohnungen).… |
| `mietkaution-rueckforderung` | Mietersicht — Workflow zur Rückforderung der Mietkaution nach Beendigung des Mietverhältnisses. Nutzt Normtext, Nutzerangaben und verifizierte Quellen; Rechtsprechung nur nach Live-Prüfung mit Gericht, Datum und Aktenzeichen. |
| `mietpreisueberhoehung-wistrg-1954-mietwucher` | Dreistufige Prüfung überhöhter Wohnraummiete: Mietpreisbremse, § 5 WiStrG 1954 als Ordnungswidrigkeit und § 291 StGB als Straftat; mit Mietspiegel-, Beweis-, Rückforderungs- und Behördenpfad. |
| `mietsenkungsverlangen` | Mietersicht — prüfe eine laufende oder bei Vertragsschluss vereinbarte Miete auf Mietpreisbremse (§§ 556d ff. BGB), § 5 WiStrG 1954 (Mietpreisüberhöhung) und § 291 StGB (Mietwucher). Erzeugt ein… |
| `mietspiegel-quellen` | Verweist auf die mitgelieferte Referenz references/mietspiegel-quellen.md mit ausschließlich amtlichen Mietspiegel-Quellen (Bundesländer Top-Städte Universitätsstädte). Nutze diese Referenz immer wenn die ortsüb… |
| `nebenkostenabrechnung-erstellen` | Vermieter- und Hausverwaltungssicht — Workflow für rechtssichere Betriebskostenabrechnungen nach § 556 BGB und BetrKV. Deckt Abrechnungszeitraum Zugangsfrist (zwölf Monate) Umlagefähigkeit Verteilerschlüssel Heizk… |
| `nebenkostenabrechnung-pruefen` | Mietersicht — prüfe eine Betriebskostenabrechnung auf Form (§ 556 Abs. 3 BGB) Frist (Zugang innerhalb von zwölf Monaten nach Abrechnungszeitraum) Umlagefähigkeit nach BetrKV Verteilerschlüssel rechnerische Richtig… |
| `rechtsstand-mai-2026-faktenbank` | Quellen-Gate: Mietpreisbremse, Modernisierung, Steckersolargeräte, virtuelle Eigentümerversammlung, Verwalterabberufung, WEG-bauliche Veränderung und freie BGH-/Normquellen |
| `weg-beschluss-anfechten` | WEG-Sicht — Prüfraster für die Beschlussanfechtung in der Wohnungseigentümergemeinschaft nach §§ 44 ff. WEG (Reform 2020). Beschluss-, Anfechtungs-, Nichtigkeits- und Feststellungsklage. Prüft formelle Mängel (Ladung, Tagesordnung, Beschlussfähigkeit, Mehrheit, Stimmrechtsausschluss) und materielle Mängel (ordnungsmäßige Verwaltung, Treu und Glauben). Klagefrist ein Monat ab Beschluss (§ 45 WEG). |

## Lizenz

Apache-2.0 OR MIT — Auswahl beim Empfänger.

## Quellen-Disclaimer

Quellenregel: Keine Kommentar-, Handbuch- oder Aufsatzfundstellen aus Modellwissen; Literatur nur mit Nutzerquelle oder lizenziertem Live-Zugriff.


<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 24 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `allgemein-workflow-chronologie-workflow-fristen` | Allgemein, Workflow Chronologie Und Belegmatrix, Workflow Fristen Und Risikoampel: Allgemein; Workflow Chronologie Und Belegmatrix; Workflow Fristen Und Risikoampel. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmus... |
| `amtlichen-amtsgericht-sonderfall-ausschliesslich` | Spezial Amtlichen Risikoampel Und Gegenargumente, Spezial Amtsgericht Sonderfall Und Edge Case, Spezial Ausschliesslich Dokumentenmatrix Und Lueckenliste: Spezial Amtlichen Risikoampel Und Gegenargumente; Spezial Amtsgericht Sonderfall U... |
| `bundesland-datenerhebung-grossstadt-mietspiegel` | Spezial Bundesland Verhandlung Vergleich Und Eskalation, Spezial Datenerhebung Zahlen Schwellen Und Berechnung, Spezial Grossstadt Mietspiegel Und Kappung: Spezial Bundesland Verhandlung Vergleich Und Eskalation; Spezial Datenerhebung Za... |
| `klageentwurf-amtsgericht-miet-gewerbemiete-mietvertrag-bauleiter` | Klageentwurf Amtsgericht, Miet Gewerbemiete Vertragsklauseln Spezial, Miet Mietvertrag Bauleiter: Klageentwurf Amtsgericht; Miet Gewerbemiete Vertragsklauseln Spezial; Miet Mietvertrag Bauleiter. Führt Intake, Prüfroutine, Normen-/Quelle... |
| `lage-ausstattung-mahnung-zahlungsverzug-mandat-triage` | Lage Und Ausstattung Erheben, Mahnung Zahlungsverzug Mieter, Mandat Triage Mietrecht: Lage Und Ausstattung Erheben; Mahnung Zahlungsverzug Mieter; Mandat Triage Mietrecht. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Out... |
| `miet-kuendigungsschutz-miet-mietminderung-mieteranfragen` | Miet Kuendigungsschutz Checkliste, Miet Mietminderung Mangel Spezial, Mieteranfragen Beantworten: Miet Kuendigungsschutz Checkliste; Miet Mietminderung Mangel Spezial; Mieteranfragen Beantworten. Führt Intake, Prüfroutine, Normen-/Quelle... |
| `mieter-mieteranfragen-mandantenentscheidung-mieterhoehungs` | Spezial Mieter Tatbestand Beweis Und Belege, Spezial Mieteranfragen Mandantenentscheidung, Spezial Mieterhoehungs Compliance Dokumentation Und Akte: Spezial Mieter Tatbestand Beweis Und Belege; Spezial Mieteranfragen Mandantenentscheidun... |
| `mieterhoehung-widersprechen-mieterhoehungsverlangen-erstellen` | Mieterhoehung Prüfen Widersprechen, Mieterhoehungsverlangen Erstellen, Mietkaution Rueckforderung: Mieterhoehung Prüfen Widersprechen; Mieterhoehungsverlangen Erstellen; Mietkaution Rueckforderung. Führt Intake, Prüfroutine, Normen-/Quel... |
| `mietpreisueberhoehung-wistrg-mietsenkungsverlangen-mietspiegel` | Mietpreisueberhoehung Wistrg 1954 Mietwucher, Mietsenkungsverlangen, Mietspiegel Quellen: Mietpreisueberhoehung Wistrg 1954 Mietwucher; Mietsenkungsverlangen; Mietspiegel Quellen. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislo... |
| `mietrecht-mietsenkungsverlangen-international-mietspiegel` | Spezial Mietrecht Erstpruefung Und Mandatsziel, Spezial Mietsenkungsverlangen International Schnittstellen, Spezial Mietspiegel Behörden Gericht Und Registerweg: Spezial Mietrecht Erstpruefung Und Mandatsziel; Spezial Mietsenkungsverlang... |
| `mr-betriebskostenabrechnung-mr-kuendigungsschutz-mr` | Mr Betriebskostenabrechnung Fehler Spezial, Mr Kuendigungsschutz Praxis, Mr Modernisierung Und Rolling Rent Spezial: Mr Betriebskostenabrechnung Fehler Spezial; Mr Kuendigungsschutz Praxis; Mr Modernisierung Und Rolling Rent Spezial. Füh... |
| `mr-einfuehrung-klageentwurf-beweislast-eigenbedarfskuendigung` | Mr Einfuehrung Vertragstypen, Spezial Klageentwurf Beweislast Und Darlegungslast, Eigenbedarfskuendigung Erstellen: Mr Einfuehrung Vertragstypen; Spezial Klageentwurf Beweislast Und Darlegungslast; Eigenbedarfskuendigung Erstellen. Führt... |
| `nebenkostenabrechnung-erstellen-faktenbank` | Nebenkostenabrechnung Erstellen, Nebenkostenabrechnung Prüfen, Rechtsstand Mai 2026 Faktenbank: Nebenkostenabrechnung Erstellen; Nebenkostenabrechnung Prüfen; Rechtsstand Mai 2026 Faktenbank. Führt Intake, Prüfroutine, Normen-/Quellenrad... |
| `nebenkostenpruefung-prozessstrategie-mieterhoehung-quellen` | Spezial Nebenkostenpruefung Formular Portal Und Einreichung, Spezial Prozessstrategie Mieterhoehung, Spezial Quellen Schriftsatz Brief Und Memo Bausteine: Spezial Nebenkostenpruefung Formular Portal Und Einreichung; Spezial Prozessstrate... |
| `spezial-erstellung-red-team-und-qualitaetskontrolle` | Erstellung: Red-Team und Qualitätskontrolle im Mietrecht: fachlich vertiefter Spezialskill mit Normenradar (BGB/BetrKV/HeizkostenV), Tatbestands-/Beweislastmatrix, Fristen- und Formcheck, Gegenargumenten, Fehlerbremse und direkt nutzbare... |
| `spezial-universitaetsstaedte-livequellen-check` | Universitaetsstaedte: Livequellen- und Rechtsprechungscheck im Mietrecht: fachlich vertiefter Spezialskill mit Normenradar (BGB/BetrKV/HeizkostenV), Tatbestands-/Beweislastmatrix, Fristen- und Formcheck, Gegenargumenten, Fehlerbremse und... |
| `widerspruch-interessen-betriebskostenabrechnung-formelpruefer` | Spezial Widerspruch Mehrparteien Konflikt Und Interessen, Betriebskostenabrechnung Belege Und Formelpruefer, Weg Beschluss Anfechten: Spezial Widerspruch Mehrparteien Konflikt Und Interessen; Betriebskostenabrechnung Belege Und Formelpru... |
| `workflow-anschluss-skills-router` | Anschluss-Skills Router im Plugin mietrecht: schlägt nach der ersten Prüfung die passenden Spezialskills aus demselben Plugin vor. |
| `workflow-dokumentenintake` | Dokumentenintake im Plugin mietrecht: liest Uploads, sortiert Dokumentarten, markiert Fristen und baut eine knappe Arbeitsakte. |
| `workflow-kaltstart-und-routing` | Kaltstart und Routing im Plugin mietrecht: führt vom ersten Satz oder Dokument in den passenden Arbeitsweg, erkennt Rolle, Ziel, Risiko und Anschluss-Skills. |
| `workflow-mandantenkommunikation-workflow-redteam-vermieter` | Workflow Mandantenkommunikation, Workflow Redteam Qualitygate, Spezial Vermieter Fristen Form Und Zustaendigkeit: Workflow Mandantenkommunikation; Workflow Redteam Qualitygate; Spezial Vermieter Fristen Form Und Zustaendigkeit. Führt Int... |
| `workflow-output-waehlen` | Output wählen im Plugin mietrecht: entscheidet zwischen Memo, Schriftsatz, Tabelle, Brief, Checkliste, Vermerk, Redline oder Mandantenübersetzung. |
| `workflow-rechtsquellen-livecheck` | Rechtsquellen-Livecheck im Plugin mietrecht: zwingt vor tragenden Aussagen zum aktuellen Quellencheck bei Gesetzen, Behörden, Gerichten und Formularen. |
| `workflow-unterlagen-lueckenliste` | Unterlagen- und Lückenliste im Plugin mietrecht: erstellt eine präzise Nachforderungsliste statt allgemeiner Fragebögen. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
