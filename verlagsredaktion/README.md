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
| `eingangskorb-heftplanung-interessen-juristische-manuskript` | Spezial Eingangskorb Risikoampel Und Gegenargumente, Spezial Heftplanung Mehrparteien Konflikt Und Interessen, Spezial Juristische Tatbestand Beweis Und Belege, Spezial Manuskript Behörden Gericht Und Registerweg, Spezial Rechtecheck Ver... |
| `eingangskorb-triage-entscheidungsmonitor-fremdtext-plagiat` | Eingangskorb Triage, Entscheidungsmonitor Rechtsstand, Fremdtext Plagiat Uebernahmecheck, Knowledge Base Faq Kundenservice, Kommentar Aktualisierung Randnummern: Eingangskorb Triage; Entscheidungsmonitor Rechtsstand; Fremdtext Plagiat Ue... |
| `lektorat-struktur-manuskriptaufnahme-materialinventar-marketing` | Lektorat Struktur Redaktion, Manuskriptaufnahme Materialinventar, Marketing Presse Social, Metadaten Seo Klappentext, Produktionsuebergabe Checkliste: Lektorat Struktur Redaktion; Manuskriptaufnahme Materialinventar; Marketing Presse Soc... |
| `qualitaetsgate-verlag-quellen-zitate-rechtecheck-urhg` | Qualitaetsgate Verlag, Quellen Zitate Fundstellencheck, Rechtecheck Urhg Verlg, Rohmanuskript Anschubhilfe, Sachbearbeiterinnen Cockpit: Qualitaetsgate Verlag; Quellen Zitate Fundstellencheck; Rechtecheck Urhg Verlg; Rohmanuskript Anschu... |
| `redaktion-satzfahnen-verlage-verlagsdesk-sprachlektorat-stil` | Spezial Redaktion Schriftsatz Brief Und Memo Bausteine, Spezial Satzfahnen Formular Portal Und Einreichung, Spezial Verlage Dokumentenmatrix Und Lueckenliste, Spezial Verlagsdesk Erstpruefung Und Mandatsziel, Sprachlektorat Stil Tonalita... |
| `sales-katalog-satzfahne-korrekturlauf-autorenkommunikation` | Sales Katalog Vlb Buchhandel, Satzfahne Korrekturlauf, Spezial Autorenkommunikation Compliance Dokumentation Und Akte, Spezial Bildrechte Zahlen Schwellen Und Berechnung, Spezial Buchprojekte Internationaler Bezug Und Schnittstellen: Sal... |
| `spezial-metadaten-red-team-und-qualitaetskontrolle` | Metadaten: Red-Team und Qualitätskontrolle im Plugin verlagsredaktion; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Standardprüfung. |
| `spezial-zitate-livequellen-und-rechtsprechungscheck` | Zitate: Livequellen- und Rechtsprechungscheck im Plugin verlagsredaktion; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Standardprüfung. |
| `verl-abstimmung-lektorat-produktion-satz-rechtsabteilung-audio` | Verl Abstimmung Mit Lektorat Format, Verl Abstimmung Mit Produktion Satz Druck, Verl Abstimmung Mit Rechtsabteilung Prüfung, Verl Abstimmung Mit Vertrieb Marketing, Verl Audio Transkript Zu Fachbeitrag: Verl Abstimmung Mit Lektorat Forma... |
| `verl-aussagensicherheit-buchprojekt-bauleiter-email-konvolute` | Verl Aussagensicherheit Prüfung, Verl Buchprojekt Bauleiter, Verl Email Konvolute Zu Fachbeitrag, Verl Eskalation Bei Deadline Konflikt, Verl Formatvorlage Check Autor Manuskript: Verl Aussagensicherheit Prüfung; Verl Buchprojekt Bauleit... |
| `verl-fussnoten-quellen-glossar-konsistenz-grammatik-handschrift` | Verl Fussnoten Quellen Konsolidierung, Verl Glossar Konsistenz Prüfung, Verl Grammatik Konsistenzcheck, Verl Handschrift Und Altdoc Digitalisieren, Verl Honorarrechnung Erstellen Prüfen: Verl Fussnoten Quellen Konsolidierung; Verl Glossa... |
| `verl-ideenpool-priorisierung-impressum-pflicht-interview-roh` | Verl Ideenpool Und Priorisierung, Verl Impressum Pflicht Und Prüfung, Verl Interview Roh Zu Magazinbeitrag, Verl Jourfix Vorbereiten Protokoll, Verl Konferenzmitschnitt Zu Tagungsbericht: Verl Ideenpool Und Priorisierung; Verl Impressum... |
| `verl-loeschpflicht-archivierung-loseblattwerk-manuskript-online` | Verl Loeschpflicht Und Archivierung Fachzs, Verl Loseblattwerk Spezial, Verl Manuskript Merkwuerdige Formate Rettung, Verl Newsletter Redaktion Jur, Verl Online Kommentar Update Spezial: Verl Loeschpflicht Und Archivierung Fachzs; Verl L... |
| `verl-mahnung-an-honorar-vertrag-honorarvertrag-templates` | Verl Mahnung An Autor Zahlung Frist, Honorar Vertrag Royalties Triage, Verl Honorarvertrag Templates Und Abweichungen, Verl Haftungsfreistellung Autor Verlag, Buchprojekt Kapitelkoordination: Verl Mahnung An Autor Zahlung Frist; Honorar... |
| `verl-podcast-zeitschriftenbeitrag-powerpoint-verwurstung` | Verl Podcast Zu Zeitschriftenbeitrag, Verl Powerpoint Verwurstung Zu Text, Verl Pressetext Rechtsthemen, Verl Rechtschreibung Amtlich Aktuell, Verl Redaktionelle Rueckmeldung Formulieren: Verl Podcast Zu Zeitschriftenbeitrag; Verl Powerp... |
| `verl-redaktionsmemo-jahresplanung-redaktionssitzung-vorbereiten` | Verl Redaktionsmemo Jahresplanung, Verl Redaktionssitzung Vorbereiten, Verl Relationslinien Prüfung Im Aufsatz, Verl Richtigstellung Online Print, Verl Roh Research Zu Essay: Verl Redaktionsmemo Jahresplanung; Verl Redaktionssitzung Vorb... |
| `verl-rueckruf-fehlerbeitrag-screenshot-pdf-social-media` | Verl Rueckruf Fehlerbeitrag Spaet Erkannt, Verl Screenshot Pdf Ocr Redaktion, Verl Social Media Rechtsfachzeitschrift, Verl Statusbericht An Verlagsleitung, Verl Stilbruch Stilcheck Fachzeitschrift: Verl Rueckruf Fehlerbeitrag Spaet Erka... |
| `verl-tantieme-abrechnung-themenscout-rechtsentwicklung-trend` | Verl Tantieme Abrechnung Jaehrlich, Verl Themenscout Rechtsentwicklung, Verl Trend Radar Rechtsgebiete, Verl Vergleichsverhandlung Mit Autor, Verl Vlb Katalog Pflege Jur: Verl Tantieme Abrechnung Jaehrlich; Verl Themenscout Rechtsentwick... |
| `verl-vorschuss-ai-einsatz-autorenkommunikation-email` | Verl Vorschuss Prüfung Buecher, Ai Einsatz Transparenz Datenschutz, Autorenkommunikation Email, Barrierefreiheit Epub Pdf, Bildrechte Grafiken Tabellen: Verl Vorschuss Prüfung Buecher; Ai Einsatz Transparenz Datenschutz; Autorenkommunika... |
| `verl-webinar-vorbereitung-zeitschriftenartikel-leitfaden` | Verl Webinar Vorbereitung Fachbeitrag, Verl Zeitschriftenartikel Leitfaden, Verl Zitierweise Prüfung Zeitschrift Jus Njw, Verl Zweitverwertungsrechte Pauschal, Verlagsredaktion: Verl Webinar Vorbereitung Fachbeitrag; Verl Zeitschriftenar... |
| `workflow-chronologie-workflow-fristen-verl-abstimmung` | Workflow Chronologie Und Belegmatrix, Workflow Fristen Und Risikoampel, Verl Abstimmung Mit Autor Feedback Kanal, Projektplan Fristen Heftplanung, Spezial Fachliche Fristen Form Und Zustaendigkeit: Workflow Chronologie Und Belegmatrix; W... |
| `workflow-dokumentenintake` | Dokumentenintake im Plugin verlagsredaktion: liest Uploads, sortiert Dokumentarten, markiert Fristen und baut eine knappe Arbeitsakte. |
| `workflow-kaltstart-und-routing` | Kaltstart und Routing im Plugin verlagsredaktion: führt vom ersten Satz oder Dokument in den passenden Arbeitsweg, erkennt Rolle, Ziel, Risiko und Anschluss-Skills. |
| `workflow-output-waehlen` | Output wählen im Plugin verlagsredaktion: entscheidet zwischen Memo, Schriftsatz, Tabelle, Brief, Checkliste, Vermerk, Redline oder Mandantenübersetzung. |
| `workflow-rechtsquellen-livecheck` | Rechtsquellen-Livecheck im Plugin verlagsredaktion: zwingt vor tragenden Aussagen zum aktuellen Quellencheck bei Gesetzen, Behörden, Gerichten und Formularen. |
| `workflow-unterlagen-lueckenliste` | Unterlagen- und Lückenliste im Plugin verlagsredaktion: erstellt eine präzise Nachforderungsliste statt allgemeiner Fragebögen. |
| `zeitschriften-heftplanung` | Zeitschriften Heftplanung: Zeitschriften Heftplanung. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zusammen. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
