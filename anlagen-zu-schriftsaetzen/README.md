# Anlagen zu Schriftsätzen

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`anlagen-zu-schriftsaetzen`) | [`anlagen-zu-schriftsaetzen.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/anlagen-zu-schriftsaetzen.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **Werkmann ./. K+B — Werklohnklage Lackieranlage Eschweiler — Anlagenkonvolut-Verfahren** (`anlagen-zu-schriftsaetzen-konzernumstellung-baudaten-werkmann-baesweiler`) | [Gesamt-PDF lesen](../testakten/anlagen-zu-schriftsaetzen-konzernumstellung-baudaten-werkmann-baesweiler/gesamt-pdf/anlagen-zu-schriftsaetzen-konzernumstellung-baudaten-werkmann-baesweiler_gesamt.pdf) | [`testakte-anlagen-zu-schriftsaetzen-konzernumstellung-baudaten-werkmann-baesweiler.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-anlagen-zu-schriftsaetzen-konzernumstellung-baudaten-werkmann-baesweiler.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

Dieses Plugin ist die Anlagenkanzlei im Kleinen: Es nimmt einen Schriftsatz, einen chaotischen Mandantenordner oder ein schon halb nummeriertes Anlagenpaket und macht daraus eine nachvollziehbare, gerichtstaugliche Anlagenstruktur.

Es hilft besonders dann, wenn nicht einfach „Anlage K1 bis K12“ vorliegt, sondern wenn eine echte Akte lebt: E-Mails mit Anhängen, Scans ohne OCR, Excel-Tabellen, Fotos, Chat-Screenshots, mehrere Vertragsfassungen, fremdsprachige Unterlagen, doppelte Dateien, geschwärzte Drittunterlagen, beA-Grenzen, Verfahrenswechsel und Richterhinweise. Das Plugin führt dann nicht nur eine Nummerierung aus, sondern baut eine Arbeitslogik: Welche Tatsache soll durch welche Anlage belegt werden? Welche Datei gehört wirklich zu K1? Welche Unterlagen sind nur Konvolutbestandteil? Welche Anlage ist zu groß, unleserlich, falsch benannt, doppelt oder im Schriftsatz nicht eingeführt?

## Wofür es gedacht ist

| Situation | Was das Plugin macht | Ergebnis |
| --- | --- | --- |
| Klage/Replik liegt vor, Anlagen sind noch ungeordnet | Schriftsatz lesen, Beweisanker erkennen, K-Nummern vorschlagen, Dateien zuordnen | K1/K2/K3-Reihenfolge, Anlagenverzeichnis, Lückenliste |
| Anlagen sind schon nummeriert, aber niemand traut dem Paket | Prüfmodus: Nummern, Zitate, Dateien, Stempel, Namen, Lesbarkeit und beA-Fähigkeit prüfen | Fehlerprotokoll mit Korrekturplan |
| Mandant liefert Datenraum/ZIP/USB-Stick | Duplikate, Fassungen, Hashes, Dateitypen, Zeitfolge und Relevanz sortieren | Belegmatrix und Nachforderungsliste |
| Eine Anlage ist ein Konvolut | Deckblatt, Untergliederung, interne Seiten-/Dokumentlogik, kurze Erläuterung für Gericht | `Anlage K1` mit `K1.1`, `K1.2`, `K1.3` |
| Elektronische Einreichung steht bevor | Dateinamen, PDF/OCR, Paketgrößen, Anlagenverzeichnis, Prüfvermerk | beA-/ERV-taugliches Versandpaket |

## Der K1-Gedanke

Die erste Anlage ist fast nie nur eine Datei. In großen Verfahren ist `K1` häufig der Orientierungspunkt für das Gericht: Vertrag, Auftrag, Rahmenvereinbarung, Nachtrag, Bestätigungsmail, Protokoll oder Dokumentenfamilie. Das Plugin behandelt `K1` deshalb als Sortierproblem:

1. **Was soll K1 beweisen?** Nicht „alles zum Vertrag“, sondern eine konkrete Tatsache.
2. **Ist K1 Einzelanlage oder Konvolut?** Bei Konvolut: Deckblatt, Reihenfolge, interne Kurzbezeichnungen.
3. **Welche Fassungen gibt es?** Entwurf, unterschriebene Fassung, Scan, OCR-PDF, E-Mail-Anhang, spätere Ergänzung.
4. **Welche Datei ist die gerichtliche Fassung?** Die anderen Fassungen wandern in den internen Hash-/Versionenlog.
5. **Wie wird K1 im Schriftsatz eingeführt?** Der Schriftsatz muss den Tatsachenkern selbst tragen; die Anlage belegt ihn nur.

## Drei Arbeitsmodi

**Auto-Benennung:** Der Schriftsatz enthält noch keine Nummern. Das Plugin liest die Beweisstellen und schlägt die Reihenfolge vor.

**Schriftsatz folgt:** Der Schriftsatz enthält bereits `Anlage K...`-Verweise. Das Plugin sucht die passenden Dateien, erkennt Lücken und meldet Überschüsse.

**Prüfmodus:** Ein fertiges Anlagenpaket wird gegengeprüft: `K7` fehlt, `K12` ist doppelt, `K18` wird im Schriftsatz nie erwähnt, `K23` hat keinen OCR-Text, `K31` enthält ungeschwärzte Drittinformationen.

## Typische Outputs

- Anlagenverzeichnis für Gericht und Kanzleiakte.
- K/B/AST/AG-Nummerierung mit eindeutiger Dateinamenkonvention.
- Konvolutdeckblätter für Sammelanlagen.
- Belegmatrix: Tatsachenbehauptung ↔ Schriftsatzstelle ↔ Anlage ↔ Datei ↔ Status.
- Hash-/Duplikat-/Fassungslog für interne Kontrolle.
- beA-Versandliste mit Paketgrößen, Dateinamen und letzten Prüfpunkten.
- Nachforderungsliste an Mandant oder Sachbearbeitung.
- Berichtigungs- oder Nachreichungsplan nach gerichtlichem Hinweis.

## Wichtig

Anlagen ersetzen keinen Tatsachenvortrag. Wenn eine Behauptung entscheidungserheblich ist, muss sie im Schriftsatz stehen. Die Anlage belegt, erläutert oder vertieft; sie darf nicht der Ort sein, an dem der eigentliche Vortrag versteckt wird.

## Installation in Claude Code

1. ZIP herunterladen (Link oben).
2. Claude Code → **Customize Plugins** → **Install from .zip** → Datei wählen.
3. Fertig. Skills sind sofort verfügbar.

> **Hinweis:** Für den ZIP-Upload muss das Archiv direkt `.claude-plugin/plugin.json`, `skills/`, `assets/` und `references/` im ZIP-Root enthalten. **Nicht** das komplette Repository-ZIP aus "Code → Download ZIP" verwenden.

## Besonders wichtige Skills

| Skill | Zweck |
| --- | --- |
| `allgemein` | Kaltstart, Triage, Nummernkreis, Ziel-Schriftsatz, K1-Frage und Routing in die passenden Spezial-Skills. |
| `anlagen-zu-schriftsaetzen` | Hauptworkflow für Auto-Benennung, Schriftsatz-folgt-Modus, Prüfmodus und Reparatur nach Hinweis. |
| `k1-sortierwerkstatt` | Baut aus Vertrag, Nachtrag, Mail, Scan und OCR-Fassung eine klare Leit-Anlage `K1` oder ein K1-Konvolut. |
| `schriftsatz-anlagen-mapping` | Verknüpft Tatsachenvortrag, Schriftsatzstelle, Beweisangebot, Anlage und Datei in einer Belegmatrix. |
| `anlagen-duplikate-versionen-hashlog` | Erkennt Dubletten, Versionen, OCR-Kopien und die maßgebliche gerichtliche Fassung. |
| `bea-paketierung-groessen-und-versandplan` | Plant Dateinamen, Paketgrößen, Teilpakete, Begleitvermerk und Eingangskontrolle. |
| `anlagen-qualitygate-finalcheck` | Letzter strenger Check vor Versand: Nummern, Zitate, Dateien, OCR, Schwärzung, Stempel, Paket. |

## Lizenz

Apache-2.0 OR MIT — Auswahl beim Empfänger.


<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 27 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `anlagen-qualitygate-finalcheck` | Finaler Red-Team-Check vor Einreichung: Nummern, Schriftsatzverweise, Dateien, Stempel, OCR, Schwärzung, Dateinamen, beA-Paket, Lücken und Begleitvermerk. |
| `anlagen-zu-schriftsaetzen` | Anwalt hat Schriftsatz fertig und muss Anlagen korrekt benennen nummerieren und als PDF-Konvolut aufbereiten. Anlagemanagement gerichtliche Schriftsaetze. Prüfraster: Schriftsatz lesen Beweisstuecke erkennen sortieren beA-konforme Benenn... |
| `kompendium-01-allgemein-bis-workflow-mandantenko` | anlagen-zu-schriftsaetzen: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Allgemein, Chronologie Und Belegmatrix, Fristen Und Risikoampel, Mandantenkommunikation; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, O... |
| `kompendium-02-workflow-redteam-qua-bis-spezial-gerichtliche` | anlagen-zu-schriftsaetzen: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Redteam Qualitygate, Frist Und Eilversand Anlagenpaket, Schiedsverfahren Anlagenband Und Datentraeger, Gerichtlichen Fristen Form Und Zustaendigkeit;... |
| `kompendium-03-spezial-pruefmodus-f-bis-anlagen-aus-mandante` | anlagen-zu-schriftsaetzen: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Pruefmodus Fristennotiz Und Naechster Schritt, Anlagen Aus Datenraum Und Sharepoint, Anlagen Aus Edv Systemen, Anlagen Aus Mandantenmaterial; mit Inta... |
| `kompendium-04-anlagen-bei-berufung-bis-anlagen-duplikate-ve` | anlagen-zu-schriftsaetzen: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Anlagen Bei Berufung Revision, Anlagen Bei Eilantrag Eu Arrest, Anlagen Bilder Screenshots, Anlagen Duplikate Versionen Hashlog; mit Intake, Prüfrouti... |
| `kompendium-05-anlagen-elektronisch-bis-anlagen-fuer-glaubha` | anlagen-zu-schriftsaetzen: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Anlagen Elektronische Dokumente Spezial, Anlagen Format Und Dateinamen, Anlagen Fuer Bea Versand, Anlagen Fuer Glaubhaftmachung; mit Intake, Prüfrouti... |
| `kompendium-06-anlagen-haftpflicht-bis-anlagen-prozessual-p` | anlagen-zu-schriftsaetzen: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Anlagen Haftpflicht Versicherer, Anlagen Konvention K B Erlaeutert, Anlagen Konvention Mandantenfreundlich, Anlagen Prozessual Pruefung Spezial; mit I... |
| `kompendium-07-anlagen-quality-chec-bis-anlagen-stempel-und` | anlagen-zu-schriftsaetzen: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Anlagen Quality Check Vor Zustellung, Anlagen Redaktion Dsgvo Geschgehg, Anlagen Schwaerzen Anonymisieren, Anlagen Stempel Und Deckblattlogik; mit Int... |
| `kompendium-08-anlagen-uebergabe-an-bis-anlagen-zur-substant` | anlagen-zu-schriftsaetzen: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Anlagen Uebergabe An Assistenz Und Legal Tech, Anlagen Uebersetzungspflicht, Anlagen Vorlagepflicht 141 Zpo, Anlagen Zur Substantiierung Pflicht; mit... |
| `kompendium-09-anlagenband-struktur-bis-anlagenmatrix-csv-xl` | anlagen-zu-schriftsaetzen: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Anlagenband Strukturieren, Anlagenbezug Im Schriftsatz, Anlagenkonvolut Konsolidieren, Anlagenmatrix Csv Xlsx Aufbau; mit Intake, Prüfroutine, Normen-... |
| `kompendium-10-anlagenverzeichnis-g-bis-berufung-beschwerde` | anlagen-zu-schriftsaetzen: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Anlagenverzeichnis Gericht Kanzlei Und Intern, Anlagenverzeichnis Grundaufbau, Bea Paketierung Groessen Und Versandplan, Berufung Beschwerde Und Neue... |
| `kompendium-11-beweisangebot-anlage-bis-fremdsprachige-anlag` | anlagen-zu-schriftsaetzen: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Beweisangebot Anlage Zeugen, Emails Chats Screenshots Als Anlagen, Excel Tabellen Und Zahlenbeweis, Fremdsprachige Anlagen Uebersetzung; mit Intake, P... |
| `kompendium-12-k1-anlagenpaket-aus-bis-mehrparteien-rollen` | anlagen-zu-schriftsaetzen: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu K1 Anlagenpaket Aus Chaosordner, K1 Sortierwerkstatt, Massenanlagen Sampling Und Repraesentativitaet, Mehrparteien Rollen Und Praefixe; mit Intake, Pr... |
| `kompendium-13-nachreichung-bericht-bis-schriftsatz-anlagen` | anlagen-zu-schriftsaetzen: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Nachreichung Berichtigung Und Gerichtshinweis, Ocr Scan Lesbarkeit Und Beweiswert, Original Abschrift Kopie Und Elektronische Fassung, Schriftsatz Anl... |
| `kompendium-14-spezial-anlage-red-t-bis-spezial-arial-mandan` | anlagen-zu-schriftsaetzen: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Anlage Red Team Und Qualitaetskontrolle, Anlagen Tatbestand Beweis Und Belege, Anlagenkonvolut Sonderfall Und Edge Case, Arial Mandantenkommunikation... |
| `kompendium-15-spezial-baut-beweisl-bis-spezial-excel-schrif` | anlagen-zu-schriftsaetzen: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Baut Beweislast Und Darlegungslast, Benennt Compliance Dokumentation Und Akte, Bereits Abschlussprodukt Und Uebergabe, Excel Schriftsatz Brief Und Mem... |
| `kompendium-16-spezial-konform-mehr-bis-spezial-schriftsaetz` | anlagen-zu-schriftsaetzen: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Konform Mehrparteien Konflikt Und Interessen, Konvertiert Zahlen Schwellen Und Berechnung, Oben Formular Portal Und Einreichung, Schriftsaetzen Dokume... |
| `kompendium-17-spezial-schriftsatz-bis-spezial-word-behoerd` | anlagen-zu-schriftsaetzen: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Schriftsatz Verhandlung Vergleich Und Eskalation, Sortiert Risikoampel Und Gegenargumente, Stempelt Internationaler Bezug Und Schnittstellen, Word Beh... |
| `kompendium-18-spezial-zuordnung-er-bis-zeitleiste-und-beleg` | anlagen-zu-schriftsaetzen: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Zuordnung Erstpruefung Und Mandatsziel, Zeitleiste Und Belegkette; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualit... |
| `spezial-logik-livequellen-und-rechtsprechungscheck` | Logik: Livequellen- und Rechtsprechungscheck im Plugin anlagen zu schriftsaetzen; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Standardprüfung. |
| `workflow-anschluss-skills-router` | Anschluss-Skills Router im Plugin anlagen-zu-schriftsaetzen: schlägt nach der ersten Prüfung die passenden Spezialskills aus demselben Plugin vor. |
| `workflow-dokumentenintake` | Dokumentenintake im Plugin anlagen-zu-schriftsaetzen: liest Uploads, sortiert Dokumentarten, markiert Fristen und baut eine knappe Arbeitsakte. |
| `workflow-kaltstart-und-routing` | Kaltstart und Routing im Plugin anlagen-zu-schriftsaetzen: führt vom ersten Satz oder Dokument in den passenden Arbeitsweg, erkennt Rolle, Ziel, Risiko und Anschluss-Skills. |
| `workflow-output-waehlen` | Output wählen im Plugin anlagen-zu-schriftsaetzen: entscheidet zwischen Memo, Schriftsatz, Tabelle, Brief, Checkliste, Vermerk, Redline oder Mandantenübersetzung. |
| `workflow-rechtsquellen-livecheck` | Rechtsquellen-Livecheck im Plugin anlagen-zu-schriftsaetzen: zwingt vor tragenden Aussagen zum aktuellen Quellencheck bei Gesetzen, Behörden, Gerichten und Formularen. |
| `workflow-unterlagen-lueckenliste` | Unterlagen- und Lückenliste im Plugin anlagen-zu-schriftsaetzen: erstellt eine präzise Nachforderungsliste statt allgemeiner Fragebögen. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
