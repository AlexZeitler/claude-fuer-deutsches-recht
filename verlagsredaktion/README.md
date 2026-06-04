# Verlagsredaktion

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`verlagsredaktion`) | [`verlagsredaktion.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/verlagsredaktion.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **Akte Auerbach Soundworks / Nordlicht in Beton** (`urheberrecht-musik-ki-songstreit-auerbach`) | [Gesamt-PDF lesen](../testakten/urheberrecht-musik-ki-songstreit-auerbach/gesamt-pdf/urheberrecht-musik-ki-songstreit-auerbach_gesamt.pdf) | [`testakte-urheberrecht-musik-ki-songstreit-auerbach.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-urheberrecht-musik-ki-songstreit-auerbach.zip) |
| **Verlagsredaktion Morgenlage Fachverlag** (`verlagsredaktion-morgenlage-fachverlag`) | [Gesamt-PDF lesen](../testakten/verlagsredaktion-morgenlage-fachverlag/gesamt-pdf/verlagsredaktion-morgenlage-fachverlag_gesamt.pdf) | [`testakte-verlagsredaktion-morgenlage-fachverlag.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-verlagsredaktion-morgenlage-fachverlag.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

Ein Verlagsdesk für juristische und fachliche Verlage: Eingangskorb, Manuskriptaufnahme, Redaktion, Rechtecheck, Zitat- und Fundstellenkontrolle, Autor:innenkommunikation, Heftplanung, Buchprojektsteuerung, Satzfahnen, Metadaten, Marketingtexte, Produktionsübergabe und Qualitätstor.

Der erste Bildschirm soll sich für eine Sachbearbeiterin so anfühlen: Alles liegt durcheinander im Postfach, aber das Plugin macht daraus sofort eine Morgenlage, eine Prioritätenliste und den nächsten verwendbaren Arbeitsschritt.

## Installation

1. ZIP herunterladen.
2. Claude Code oder Claude Desktop/Cowork öffnen.
3. **Customize Plugins** bzw. **Personal plugins** öffnen.
4. **Install from .zip** wählen und `verlagsredaktion.zip` hochladen.

Nicht das komplette Repository-ZIP hochladen. Das Plugin-ZIP muss im Root direkt `.claude-plugin/plugin.json`, `skills/` und `references/` enthalten.

## Was das Plugin gut können soll

- Aus einer unordentlichen Inbox eine Tagesübersicht machen.
- Manuskripte, Diktate, Folien, Screenshots, Tabellen und Autor:innenmails inventarisieren.
- Rohmanuskripte als Anschubhilfe erstellen, ohne fremde Texte zu kopieren.
- Vorhandene Texte strukturieren, kürzen, glätten und auf Widersprüche prüfen.
- Zitate, Fundstellen, Randnummern und Quellenstatus transparent markieren.
- Rechtefragen zu UrhG, Verlagsgesetz, Bildrechten, Tabellen und Fremdmaterialien als Ampel vorbereiten.
- Autor:innen freundlich, knapp und verbindlich anschreiben.
- Heft-, Buch- und Online-First-Workflows in Aufgaben und Fristen übersetzen.
- Klappentexte, Vorschauen, Metadaten und Marketingtexte aus dem Manuskript ableiten.
- Satzfahnen und Korrekturläufe steuern.
- KI-Einsatz, Datenschutz und Vertraulichkeit konservativ dokumentieren.

## Enthaltene Skills

| Skill | Zweck |
| --- | --- |
| `allgemein` | Cooler Einstieg, stummer Upload, Morgenlage und Skill-Routing. |
| `sachbearbeiterinnen-cockpit` | Persönliches Arbeitscockpit für Sachbearbeitung, Redaktion und Herstellung. |
| `eingangskorb-triage` | Mails, Dateien, Screenshots und Fristen in Prioritäten verwandeln. |
| `projektplan-fristen-heftplanung` | Projektplan für Heft, Online-Beitrag, Buchkapitel oder Kommentarupdate. |
| `manuskriptaufnahme-materialinventar` | Materialinventar mit Herkunft, Nutzbarkeit, Lücken und Rechteampel. |
| `verlagsredaktion` | Klassischer Rohmanuskript-/Editionsassistent. |
| `rohmanuskript-anschubhilfe` | Aus Material ein erstes, klar markiertes Rohmanuskript bauen. |
| `lektorat-struktur-redaktion` | Gliederung, Dramaturgie, Kürzung, Redundanz- und Widerspruchsprüfung. |
| `sprachlektorat-stil-tonalitaet` | Ton, Satzbau, Lesbarkeit, Verlagssprache, Zielgruppe. |
| `quellen-zitate-fundstellencheck` | Zitat- und Quellenhygiene ohne erfundene Literatur. |
| `rechtecheck-urhg-verlg` | Urheberrecht, Verlagsgesetz, Nutzungsrechte, Zitatrecht und Zweitveröffentlichung. |
| `bildrechte-grafiken-tabellen` | Bilder, Screenshots, Tabellen, Grafiken, Diagramme und Credits prüfen. |
| `fremdtext-plagiat-uebernahmecheck` | Fremdtext, KI-Text, Copy-Paste und Paraphrase-Risiken markieren. |
| `autorenkommunikation-email` | Autor:innenmails, Erinnerungen, Freigaben, Nachforderungen. |
| `honorar-vertrag-royalties-triage` | Vertrags-/Honorar-/Royalty-Fragen für redaktionelle Vorprüfung. |
| `metadaten-seo-klappentext` | Titel, Untertitel, Abstract, Schlagworte, VLB-/Web-Metadaten, Klappentext. |
| `zeitschriften-heftplanung` | Hefte, Rubriken, Deadlines, Online-first, Fahnen und Umbruch koordinieren. |
| `buchprojekt-kapitelkoordination` | Kapitel, Autor:innen, Register, Abbildungen, Vorwort und Produktionsstand. |
| `kommentar-aktualisierung-randnummern` | Kommentarupdates, Randnummern, Nachweise, Rechtsstandsvermerk. |
| `entscheidungsmonitor-rechtsstand` | Entscheidungen und Gesetzesänderungen als Aktualisierungsanlass erfassen. |
| `satzfahne-korrekturlauf` | Fahnenprüfung, Korrekturzeichen, Umbruch, Freigabe und letzte Checks. |
| `barrierefreiheit-epub-pdf` | Alt-Texte, Überschriftenlogik, Tabellenzugänglichkeit, EPUB/PDF-Check. |
| `marketing-presse-social` | Vorschau, Newsletter, Social Copy, Presseinfo und Nutzenargumente. |
| `sales-katalog-vlb-buchhandel` | Vertriebskurztext, Katalogdaten, Buchhandelsargumente, Zielgruppen. |
| `knowledge-base-faq-kundenservice` | FAQ und interne Wissensbasis für Vertrieb, Support und Redaktion. |
| `ai-einsatz-transparenz-datenschutz` | KI-Einsatz, Vertraulichkeit, DSGVO, Rechte und Freigabe dokumentieren. |
| `produktionsuebergabe-checkliste` | Übergabe an Herstellung, Satz, Online, Marketing, Vertrieb und Archiv. |
| `qualitaetsgate-verlag` | Schlussprüfung vor Autor:innenversand, Satz, Onlinegang oder Druck. |

## Quellenregel

- Keine Kommentar-, Handbuch-, Aufsatz- oder Datenbankfundstellen aus Modellwissen.
- Literatur nur aus Nutzerquelle, frei zugänglicher Quelle oder lizenziertem Live-Zugriff.
- Rechtsprechung nur mit Gericht, Entscheidungsform, Datum, Aktenzeichen und frei prüfbarer Quelle.
- Fremdtexte niemals wörtlich übernehmen, außer der Nutzer verlangt ein zulässiges kurzes Zitat mit sauberer Quellenangabe und Zweck.
- Bei Verlagstexten immer trennen: Autor:innenmaterial, Redaktionstext, Fremdquelle, KI-Vorschlag und offene Lücke.

<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 28 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `allgemein` | Cooler Einstieg fuer das Verlagsredaktion-Plugin: stummer Upload, Morgenlage, Eingangskorb, Fristen, Rechteampel, Manuskriptstatus und Routing zu den Verlagsdesk-Skills. |
| `kompendium-01-workflow-chronologie-bis-spezial-fachliche-fr` | verlagsredaktion: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Chronologie Und Belegmatrix, Fristen Und Risikoampel, Verl Abstimmung Mit Autor Feedback Kanal, Projektplan Fristen Heftplanung und 1 weitere Arbeitsmodule; mi... |
| `kompendium-02-verl-mahnung-an-auto-bis-buchprojekt-kapitelk` | verlagsredaktion: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Verl Mahnung An Autor Zahlung Frist, Honorar Vertrag Royalties Triage, Verl Honorarvertrag Templates Und Abweichungen, Verl Haftungsfreistellung Autor Verlag u... |
| `kompendium-03-verl-vorschuss-pruef-bis-bildrechte-grafiken` | verlagsredaktion: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Verl Vorschuss Pruefung Buecher, Ai Einsatz Transparenz Datenschutz, Autorenkommunikation Email, Barrierefreiheit Epub Pdf und 1 weitere Arbeitsmodule; mit Int... |
| `kompendium-04-eingangskorb-triage-bis-kommentar-aktualisie` | verlagsredaktion: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Eingangskorb Triage, Entscheidungsmonitor Rechtsstand, Fremdtext Plagiat Uebernahmecheck, Knowledge Base Faq Kundenservice und 1 weitere Arbeitsmodule; mit Int... |
| `kompendium-05-lektorat-struktur-re-bis-produktionsuebergabe` | verlagsredaktion: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Lektorat Struktur Redaktion, Manuskriptaufnahme Materialinventar, Marketing Presse Social, Metadaten Seo Klappentext und 1 weitere Arbeitsmodule; mit Intake, P... |
| `kompendium-06-qualitaetsgate-verla-bis-sachbearbeiterinnen` | verlagsredaktion: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Qualitaetsgate Verlag, Quellen Zitate Fundstellencheck, Rechtecheck Urhg Verlg, Rohmanuskript Anschubhilfe und 1 weitere Arbeitsmodule; mit Intake, Prüfroutine... |
| `kompendium-07-sales-katalog-vlb-bu-bis-spezial-buchprojekte` | verlagsredaktion: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Sales Katalog Vlb Buchhandel, Satzfahne Korrekturlauf, Autorenkommunikation Compliance Dokumentation Und Akte, Bildrechte Zahlen Schwellen Und Berechnung und 1... |
| `kompendium-08-spezial-eingangskorb-bis-spezial-rechtecheck` | verlagsredaktion: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Eingangskorb Risikoampel Und Gegenargumente, Heftplanung Mehrparteien Konflikt Und Interessen, Juristische Tatbestand Beweis Und Belege, Manuskript Behoerden G... |
| `kompendium-09-spezial-redaktion-sc-bis-sprachlektorat-stil` | verlagsredaktion: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Redaktion Schriftsatz Brief Und Memo Bausteine, Satzfahnen Formular Portal Und Einreichung, Verlage Dokumentenmatrix Und Lueckenliste, Verlagsdesk Erstpruefung... |
| `kompendium-10-verl-abstimmung-mit-bis-verl-audio-transkrip` | verlagsredaktion: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Verl Abstimmung Mit Lektorat Format, Verl Abstimmung Mit Produktion Satz Druck, Verl Abstimmung Mit Rechtsabteilung Pruefung, Verl Abstimmung Mit Vertrieb Mark... |
| `kompendium-11-verl-aussagensicherh-bis-verl-formatvorlage-c` | verlagsredaktion: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Verl Aussagensicherheit Pruefung, Verl Buchprojekt Bauleiter, Verl Email Konvolute Zu Fachbeitrag, Verl Eskalation Bei Deadline Konflikt und 1 weitere Arbeitsm... |
| `kompendium-12-verl-fussnoten-quell-bis-verl-honorarrechnung` | verlagsredaktion: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Verl Fussnoten Quellen Konsolidierung, Verl Glossar Konsistenz Pruefung, Verl Grammatik Konsistenzcheck, Verl Handschrift Und Altdoc Digitalisieren und 1 weite... |
| `kompendium-13-verl-ideenpool-und-p-bis-verl-konferenzmitsch` | verlagsredaktion: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Verl Ideenpool Und Priorisierung, Verl Impressum Pflicht Und Pruefung, Verl Interview Roh Zu Magazinbeitrag, Verl Jourfix Vorbereiten Protokoll und 1 weitere A... |
| `kompendium-14-verl-loeschpflicht-u-bis-verl-online-kommenta` | verlagsredaktion: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Verl Loeschpflicht Und Archivierung Fachzs, Verl Loseblattwerk Spezial, Verl Manuskript Merkwuerdige Formate Rettung, Verl Newsletter Redaktion Jur und 1 weite... |
| `kompendium-15-verl-podcast-zu-zeit-bis-verl-redaktionelle-r` | verlagsredaktion: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Verl Podcast Zu Zeitschriftenbeitrag, Verl Powerpoint Verwurstung Zu Text, Verl Pressetext Rechtsthemen, Verl Rechtschreibung Amtlich Aktuell und 1 weitere Arb... |
| `kompendium-16-verl-redaktionsmemo-bis-verl-roh-research-zu` | verlagsredaktion: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Verl Redaktionsmemo Jahresplanung, Verl Redaktionssitzung Vorbereiten, Verl Relationslinien Pruefung Im Aufsatz, Verl Richtigstellung Online Print und 1 weiter... |
| `kompendium-17-verl-rueckruf-fehler-bis-verl-stilbruch-stilc` | verlagsredaktion: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Verl Rueckruf Fehlerbeitrag Spaet Erkannt, Verl Screenshot Pdf Ocr Redaktion, Verl Social Media Rechtsfachzeitschrift, Verl Statusbericht An Verlagsleitung und... |
| `kompendium-18-verl-tantieme-abrech-bis-verl-vlb-katalog-pfl` | verlagsredaktion: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Verl Tantieme Abrechnung Jaehrlich, Verl Themenscout Rechtsentwicklung, Verl Trend Radar Rechtsgebiete, Verl Vergleichsverhandlung Mit Autor und 1 weitere Arbe... |
| `kompendium-19-verl-webinar-vorbere-bis-verlagsredaktion` | verlagsredaktion: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Verl Webinar Vorbereitung Fachbeitrag, Verl Zeitschriftenartikel Leitfaden, Verl Zitierweise Pruefung Zeitschrift Jus Njw, Verl Zweitverwertungsrechte Pauschal... |
| `kompendium-20-zeitschriften-heftpl-bis-zeitschriften-heftpl` | verlagsredaktion: eigenständiger Arbeits-Skill zu Zeitschriften Heftplanung; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck. |
| `spezial-metadaten-red-team-und-qualitaetskontrolle` | Metadaten: Red-Team und Qualitätskontrolle im Plugin verlagsredaktion; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Standardprüfung. |
| `spezial-zitate-livequellen-und-rechtsprechungscheck` | Zitate: Livequellen- und Rechtsprechungscheck im Plugin verlagsredaktion; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Standardprüfung. |
| `workflow-dokumentenintake` | Dokumentenintake im Plugin verlagsredaktion: liest Uploads, sortiert Dokumentarten, markiert Fristen und baut eine knappe Arbeitsakte. |
| `workflow-kaltstart-und-routing` | Kaltstart und Routing im Plugin verlagsredaktion: führt vom ersten Satz oder Dokument in den passenden Arbeitsweg, erkennt Rolle, Ziel, Risiko und Anschluss-Skills. |
| `workflow-output-waehlen` | Output wählen im Plugin verlagsredaktion: entscheidet zwischen Memo, Schriftsatz, Tabelle, Brief, Checkliste, Vermerk, Redline oder Mandantenübersetzung. |
| `workflow-rechtsquellen-livecheck` | Rechtsquellen-Livecheck im Plugin verlagsredaktion: zwingt vor tragenden Aussagen zum aktuellen Quellencheck bei Gesetzen, Behörden, Gerichten und Formularen. |
| `workflow-unterlagen-lueckenliste` | Unterlagen- und Lückenliste im Plugin verlagsredaktion: erstellt eine präzise Nachforderungsliste statt allgemeiner Fragebögen. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
