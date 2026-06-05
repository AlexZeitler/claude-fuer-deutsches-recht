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
| `allgemein-workflow-chronologie-fristen` | Nutze dies, wenn Allgemein, Workflow Chronologie Und Belegmatrix, Workflow Fristen Und Risikoampel im Plugin Mietrecht konkret bearbeitet werden soll. Auslöser: Bitte Allgemein, Workflow Chronologie Und Belegmatrix, Workflow Fristen Und... |
| `amtlichen-amtsgericht-sonderfall` | Nutze dies, wenn Spezial Amtlichen Risikoampel Und Gegenargumente, Spezial Amtsgericht Sonderfall Und Edge Case, Spezial Ausschliesslich Dokumentenmatrix Und Lueckenliste im Plugin Mietrecht konkret bearbeitet werden soll. Auslöser: Bitt... |
| `anschluss-routing` | Nutze dies, wenn Anschluss-Routing im Plugin Mietrecht konkret bearbeitet werden soll. Auslöser: Ich habe ein neues Thema im Bereich Mietrecht.; Welche Unterlagen brauchen Sie?; Welcher Spezialskill passt?. |
| `bundesland-datenerhebung-grossstadt` | Nutze dies, wenn Spezial Bundesland Verhandlung Vergleich Und Eskalation, Spezial Datenerhebung Zahlen Schwellen Und Berechnung, Spezial Grossstadt Mietspiegel Und Kappung im Plugin Mietrecht konkret bearbeitet werden soll. Auslöser: Bit... |
| `dokumente-intake` | Nutze dies, wenn Dokumentenintake im Plugin Mietrecht konkret bearbeitet werden soll. Auslöser: Ich lade Unterlagen hoch.; Was fehlt noch?; Bitte Dokumente sortieren.. |
| `einstieg-routing` | Nutze dies, wenn Einstieg und Routing im Plugin Mietrecht konkret bearbeitet werden soll. Auslöser: Ich habe ein neues Thema im Bereich Mietrecht.; Welche Unterlagen brauchen Sie?; Welcher Spezialskill passt?. |
| `erstellung-fehlerkatalog` | Nutze dies, wenn Erstellung Fehlerkatalog im Plugin Mietrecht konkret bearbeitet werden soll. Auslöser: Was kann hier schiefgehen?; Bitte red-team prüfen.; Welche Frist oder Beweislast übersehe ich?. |
| `klageentwurf-amtsgericht-miet-gewerbemiete` | Nutze dies, wenn Klageentwurf Amtsgericht, Miet Gewerbemiete Vertragsklauseln Spezial, Miet Mietvertrag Bauleiter im Plugin Mietrecht konkret bearbeitet werden soll. Auslöser: Bitte Klageentwurf Amtsgericht, Miet Gewerbemiete Vertragskla... |
| `lage-ausstattung-mahnung-zahlungsverzug` | Nutze dies, wenn Lage Und Ausstattung Erheben, Mahnung Zahlungsverzug Mieter, Mandat Triage Mietrecht im Plugin Mietrecht konkret bearbeitet werden soll. Auslöser: Bitte Lage Und Ausstattung Erheben, Mahnung Zahlungsverzug Mieter, Mandat... |
| `miet-kuendigungsschutz-mietminderung` | Nutze dies, wenn Miet Kuendigungsschutz Checkliste, Miet Mietminderung Mangel Spezial, Mieteranfragen Beantworten im Plugin Mietrecht konkret bearbeitet werden soll. Auslöser: Bitte Miet Kuendigungsschutz Checkliste, Miet Mietminderung M... |
| `mieter-mieteranfragen-mandantenentscheidung` | Nutze dies, wenn Spezial Mieter Tatbestand Beweis Und Belege, Spezial Mieteranfragen Mandantenentscheidung, Spezial Mieterhoehungs Compliance Dokumentation Und Akte im Plugin Mietrecht konkret bearbeitet werden soll. Auslöser: Bitte Spez... |
| `mieterhoehung-widersprechen` | Nutze dies, wenn Mieterhoehung Prüfen Widersprechen, Mieterhoehungsverlangen Erstellen, Mietkaution Rueckforderung im Plugin Mietrecht konkret bearbeitet werden soll. Auslöser: Bitte Mieterhoehung Prüfen Widersprechen, Mieterhoehungsverl... |
| `mietpreisueberhoehung-wistrg` | Nutze dies, wenn Mietpreisueberhoehung Wistrg 1954 Mietwucher, Mietsenkungsverlangen, Mietspiegel Quellen im Plugin Mietrecht konkret bearbeitet werden soll. Auslöser: Bitte Mietpreisueberhoehung Wistrg 1954 Mietwucher, Mietsenkungsverla... |
| `mietrecht-mietsenkungsverlangen-international` | Nutze dies, wenn Spezial Mietrecht Erstpruefung Und Mandatsziel, Spezial Mietsenkungsverlangen International Schnittstellen, Spezial Mietspiegel Behörden Gericht Und Registerweg im Plugin Mietrecht konkret bearbeitet werden soll. Auslöse... |
| `mr-betriebskostenabrechnung-mr` | Nutze dies, wenn Mr Betriebskostenabrechnung Fehler Spezial, Mr Kuendigungsschutz Praxis, Mr Modernisierung Und Rolling Rent Spezial im Plugin Mietrecht konkret bearbeitet werden soll. Auslöser: Bitte Mr Betriebskostenabrechnung Fehler S... |
| `mr-einfuehrung-klageentwurf-beweislast` | Nutze dies, wenn Mr Einfuehrung Vertragstypen, Spezial Klageentwurf Beweislast Und Darlegungslast, Eigenbedarfskuendigung Erstellen im Plugin Mietrecht konkret bearbeitet werden soll. Auslöser: Bitte Mr Einfuehrung Vertragstypen, Spezial... |
| `nebenkostenabrechnung-erstellen-faktenbank` | Nutze dies, wenn Nebenkostenabrechnung Erstellen, Nebenkostenabrechnung Prüfen, Rechtsstand Mai 2026 Faktenbank im Plugin Mietrecht konkret bearbeitet werden soll. Auslöser: Bitte Nebenkostenabrechnung Erstellen, Nebenkostenabrechnung Pr... |
| `nebenkostenpruefung-prozessstrategie` | Nutze dies, wenn Spezial Nebenkostenpruefung Formular Portal Und Einreichung, Spezial Prozessstrategie Mieterhoehung, Spezial Quellen Schriftsatz Brief Und Memo Bausteine im Plugin Mietrecht konkret bearbeitet werden soll. Auslöser: Welc... |
| `output-waehlen` | Nutze dies, wenn Output wählen im Plugin Mietrecht konkret bearbeitet werden soll. Auslöser: Bitte Output wählen prüfen.; Erstelle eine Arbeitsfassung zu Output wählen.; Welche Normen und Nachweise brauche ich?. |
| `quellen-livecheck` | Nutze dies, wenn Rechtsquellen-Livecheck im Plugin Mietrecht konkret bearbeitet werden soll. Auslöser: Welche amtliche Quelle prüfe ich zuerst?; Gibt es aktuelle Rechtsprechung?; Bitte Fundstellen verifizieren.. |
| `universitaetsstaedte-quellenkarte-check` | Nutze dies, wenn Universitaetsstaedte Quellenkarte Check im Plugin Mietrecht konkret bearbeitet werden soll. Auslöser: Welche amtliche Quelle prüfe ich zuerst?; Gibt es aktuelle Rechtsprechung?; Bitte Fundstellen verifizieren.. |
| `unterlagen-luecken` | Nutze dies, wenn Unterlagen und Lücken im Plugin Mietrecht konkret bearbeitet werden soll. Auslöser: Ich lade Unterlagen hoch.; Was fehlt noch?; Bitte Dokumente sortieren.. |
| `vermieter` | Nutze dies, wenn Workflow Mandantenkommunikation, Workflow Redteam Qualitygate, Spezial Vermieter Fristen Form Und Zustaendigkeit im Plugin Mietrecht konkret bearbeitet werden soll. Auslöser: Was kann hier schiefgehen?; Bitte red-team pr... |
| `widerspruch-interessen` | Nutze dies, wenn Spezial Widerspruch Mehrparteien Konflikt Und Interessen, Betriebskostenabrechnung Belege Und Formelpruefer, Weg Beschluss Anfechten im Plugin Mietrecht konkret bearbeitet werden soll. Auslöser: Bitte Spezial Widerspruch... |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
