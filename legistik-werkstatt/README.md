# Legistik-Werkstatt

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`legistik-werkstatt`) | [`legistik-werkstatt.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/legistik-werkstatt.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **Elektronisches Pflichtpostfach** (`legistik-pflichtpostfach`) | [Gesamt-PDF lesen](../testakten/legistik-pflichtpostfach/gesamt-pdf/legistik-pflichtpostfach_gesamt.pdf) | [`testakte-legistik-pflichtpostfach.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-legistik-pflichtpostfach.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

Vollständige Werkstatt für Legistinnen und Legisten in Bundesministerien, Bundestag, Fraktionen, Oppositionsarbeit, Landesministerien, Landtagen sowie kommunalen und kammerlichen Normgebern. Vom politischen Auftrag über Startbahn, Normhierarchie, Kompetenzprüfung, Normenkartierung und Terminologie zu Referentenentwurf, Kabinettsmappe, Gesetzentwurf aus der Mitte des Bundestages oder Landtages, Änderungsantrag, Entschließungsantrag, Antrag, Formulierungshilfe, Rechtsverordnung und Satzung. Mit Querschnittsprüfungen Verfassungsrecht Europarecht Folgenabschätzung Goldplating Bestimmtheit Zirkelschluss. Erzeugt am Ende ein DOCX und PDF im passenden offiziellen Layout - ministerieller Referentenentwurf-Stil, BT-/Landtagsdrucksachen-Stil oder Arbeitsfassung für Fraktion, Ausschuss und Normgeber.

## Installation in Claude Code

1. ZIP herunterladen (Link oben).
2. Claude Code → **Customize Plugins** → **Install from .zip** → Datei wählen.
3. Fertig. Skills sind sofort verfügbar.

> **Hinweis:** Für den ZIP-Upload muss das Archiv direkt `.claude-plugin/plugin.json`, `skills/`, `assets/` im ZIP-Root enthalten. **Nicht** das komplette Repository-ZIP aus "Code → Download ZIP" verwenden.

## Was kann das Plugin?

Das Plugin deckt **alle Normebenen** ab:

- Bundesgesetz (Stammgesetz, Mantelgesetz, Änderungsgesetz)
- Landesgesetz
- Rechtsverordnung des Bundes und der Länder (Art. 80 GG, Landesverfassungen)
- Satzungen von Kommunen, Kammern und Hochschulen (Art. 28 Abs. 2 GG, Selbstverwaltung)
- Sekundärrechtsdurchführung und Notifizierung
- parlamentarischer Antrag, Entschließungsantrag, Änderungsantrag und Gesetzentwurf aus der Mitte des Bundestages oder Landtages

Das Plugin arbeitet mit **fünf Startbahnen**:

- Bundesressort / Bundesregierung: Referentenentwurf, Ressortabstimmung, NKR, Kabinett, Bundesrat, Bundestag
- Bundestag / Fraktion / Abgeordnete: Gesetzentwurf aus der Mitte, Änderungsantrag, Antrag, Entschließungsantrag, Ausschussfassung
- Landesressort / Landesregierung: Landesreferentenentwurf, Landesverordnung, Kabinetts- und Landtagsweg
- Landtag / Landtagsfraktion: landesspezifischer Gesetzentwurf, Änderungsantrag, Antrag, Entschließungsantrag
- sonstiger Normgeber: kommunale Satzung, Kammerrecht, Hochschulsatzung, Beschlussvorlage, Bekanntmachung

Das Plugin prüft **immer**:

- Verfassungsrecht (GG, Landesverfassungen, BVerfG-Rechtsprechung)
- Europarecht (Primärrecht, Sekundärrecht, Notifizierung 2015/1535)
- Folgen (Erfüllungsaufwand, Bürokratiekosten, Nachhaltigkeit, KMU-Test)
- Goldplating und Wesentlichkeit
- Bestimmtheit, Terminologie und Zirkelschluss

Am Ende erzeugt es ein **lieferfertiges DOCX und PDF** im offiziellen Layout:

- **Referentenentwurf** (Arial 11pt, Bearbeitungsstand-Kopf, A-F-Vorblatt)
- **BT-Drucksache** (Times New Roman 11pt, Drucksachennummer + Wahlperiode in der Kopfzeile, Sperrsatz für Hauptüberschriften, Anschreiben des Bundeskanzlers)
- **Formulierungshilfe / parlamentarische Vorlage** (für Koalition, Opposition, Ausschuss oder Ministerialzulieferung)
- **Antrag / Entschließungsantrag** (beschlussreif, mit Begründung und Kurzvermerk)
- **Synopse** (dreispaltig)
- **Lesefassung** (konsolidiert nach Inkrafttreten)
- **Kabinettsmappe** (Deckblatt + Anlagenverzeichnis)

## Skill-Tabelle

| Phase | Skill | Zweck |
| --- | --- | --- |
| Auftrag | `legistik-auftragsaufnahme` | Startbahn, Institution, formalen Initiator und Regelungsauftrag übersetzen |
| Normhierarchie | `normhierarchie-routing` | Regierung vs Parlament; Gesetz vs Verordnung vs Satzung vs Antrag; Bund vs Land |
| Kompetenz | `gesetzgebungskompetenz-pruefen` | Art. 70 bis 74 GG, Erforderlichkeit |
| Kompetenz | `verordnungsermaechtigung-art80` | Inhalt Zweck Ausmass nach Art. 80 GG |
| Kompetenz | `satzungskompetenz-pruefen` | Art. 28 Abs. 2 GG, Kammern, Hochschulen |
| Mapping | `normenkartierung` | Verweisnetz und Änderungsstellen |
| Sprache | `terminologie-konsistenz` | Begriffsbrüche aufspüren |
| Sprache | `zirkelschluss-pruefen` | Verweisgraf zykelfrei |
| Entwurf | `referentenentwurf-bauen` | Vollformat des Bundes- oder Landes-Referentenentwurfs |
| Entwurf | `formulierungshilfe-bauen` | Formulierungshilfe, Änderungsantrag, Gesetzentwurf aus der Mitte, Antrag oder Entschließungsantrag |
| Entwurf | `gesetzesentwurf-kabinett` | Kabinettsmappe |
| Entwurf | `begruendung-allgemein-und-besonders` | Teil A I-VII und Teil B |
| Entwurf | `synopse-erstellen` | Dreispaltige Synopse |
| Entwurf | `lesefassung-konsolidiert` | Konsolidierte Fassung nach Inkrafttreten |
| Entwurf | `xml-paralleldarstellung` | LegalDocML.de und eNorm |
| Prüfung | `europarechtskonformitaet` | Primärrecht Sekundärrecht Notifizierung |
| Prüfung | `goldplating-vermeiden` | Überschießende Umsetzung von Unionsrecht |
| Prüfung | `verfassungsmaessigkeit-quercheck` | Grundrechte Verhältnismäßigkeit Bestimmtheit |
| Folgen | `folgenabschaetzung-erfuellungsaufwand` | Erfüllungsaufwand quantifizieren |
| Folgen | `folgenabschaetzung-nachhaltigkeit` | SDGs Klima Generationengerechtigkeit |
| Inkrafttreten | `inkrafttreten-uebergangsrecht` | Zeitpunkt Übergang Verkündung |
| Beteiligung | `verbaendeanhoerung-ressortabstimmung` | Anhörung und Abstimmung |
| Beteiligung | `normenkontrollrat-kmu-check` | NKR-Stellungnahme einholen |
| Lieferung | `dokumente-rendern-docx-pdf` | DOCX und PDF im offiziellen Layout |
| Schulung | `schulung-legistik` | Trainerleitfaden für Schulungen |

Insgesamt **26 Skills**.

## Beispielprojekt - Pflichtpostfachgesetz

Das Repository enthält eine vollständige Arbeitsakte unter `testakten/legistik-pflichtpostfach/`. Sie simuliert den Weg von der politischen Vorgabe (Koalitionsvertrag) zum lieferfertigen Referentenentwurf eines neuen Stammgesetzes über das elektronische Pflichtpostfach für HReg-Gesellschaften und sehr große Online-Plattformen.

So erzeugen Sie die fertigen Dokumente:

```bash
cd claude-fuer-deutsches-recht
python3 legistik-werkstatt/skills/dokumente-rendern-docx-pdf/assets/render.py \
  --format referentenentwurf \
  --eingabe testakten/legistik-pflichtpostfach/eingang \
  --ausgabe testakten/legistik-pflichtpostfach/output

python3 legistik-werkstatt/skills/dokumente-rendern-docx-pdf/assets/render.py \
  --format bt-drucksache \
  --eingabe testakten/legistik-pflichtpostfach/eingang \
  --ausgabe testakten/legistik-pflichtpostfach/output
```

Voraussetzung: `pip install python-docx pyyaml`. Für die PDF-Konvertierung zusätzlich LibreOffice (`soffice`).

## Disclaimer

Dieses Plugin ist ein Werkzeug zur Beschleunigung legistischer Arbeit. Es ersetzt nicht die juristische Prüfung durch verantwortliche Fachreferentinnen und Fachreferenten und nicht die Prüfung durch die Ressortleitung und das Bundesministerium der Justiz im Rahmen der Rechtsförmlichkeitsprüfung.

<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 35 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `dokumente-rendern-docx-pdf` | Legistische Dokumente als DOCX oder PDF im offiziellen Erscheinungsbild der Bundesregierung, des Bundestages, eines Landes oder eines Landtags rendern. Anwendungsfall fertiger Entwurf soll als lieferfähiges Dokument nach Handbuch der Rec... |
| `komp-01-teil-02-legw-aa-eu-grundlagen-und-ratsverfahren` | legistik-werkstatt: eigenständiger Arbeits-Skill für sachlich zusammengehörige Arbeitsmodule zu Legw Aa Eu Grundlagen Und Ratsverfahren, Legw Bmi Verwaltungsverfahren Und Bundesverwaltung, Legw Gesetzgebungsverfahren Bauleiter, Spezial B... |
| `komp-03-teil-02-folgenabschaetzung-erfuellungsaufwand` | legistik-werkstatt: eigenständiger Arbeits-Skill für sachlich zusammengehörige Arbeitsmodule zu Folgenabschaetzung Erfuellungsaufwand, Folgenabschaetzung Nachhaltigkeit, Formulierungshilfe Bauen, Gesetzgebungskompetenz Pruefen; mit Intak... |
| `komp-04-teil-02-legw-aa-konsular-und-passrecht` | legistik-werkstatt: eigenständiger Arbeits-Skill für sachlich zusammengehörige Arbeitsmodule zu Legw Aa Konsular Und Passrecht, Legw Bmas Arbeitsrecht Und Arbeitsschutz, Legw Bmas Arbeitsschutz Und Arbeitssicherheit, Legw Bmas Sozialvers... |
| `komp-19-teil-02-schulung-legistik` | legistik-werkstatt: eigenständiger Arbeits-Skill für sachlich zusammengehörige Arbeitsmodule zu Schulung Legistik, Spezial Aenderungs Formular Portal Und Einreichung, Spezial Fraktionen Dokumentenmatrix Und Lueckenliste, Spezial Kabinett... |
| `komp-21-teil-02-verfassungsmaessigkeit-quercheck` | legistik-werkstatt: eigenständiger Arbeits-Skill für sachlich zusammengehörige Arbeitsmodule zu Verfassungsmaessigkeit Quercheck, Verordnungsermaechtigung Art80, Xml Paralleldarstellung, Zirkelschluss Pruefen; mit Intake, Prüfroutine, No... |
| `kompendium-01-allgemein-bis-spezial-bundestag-fr` | legistik-werkstatt: eigenständiger Arbeits-Skill für sachlich zusammengehörige Arbeitsmodule zu Allgemein, Workflow Chronologie Und Belegmatrix, Workflow Fristen Und Risikoampel, Legw Bmleh Oekolandbau Und Pflanzenschutzrecht; mit Intake... |
| `kompendium-02-gesetzesentwurf-kabi-bis-legw-bmf-zoll-und-au` | legistik-werkstatt: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Gesetzesentwurf Kabinett, Legw Aa Voelkerrecht Und Vertragsgesetzgebung, Referentenentwurf Bauen, Legw Aa Sanktionsumsetzung Und Internationale Abkommen und... |
| `kompendium-03-legw-ressort-bmf-bis-gesetzgebungskompete` | legistik-werkstatt: eigenständiger Arbeits-Skill für sachlich zusammengehörige Arbeitsmodule zu Legw Ressort Bmf, Verbaendeanhoerung Ressortabstimmung, Begruendung Allgemein Und Besonders, Europarechtskonformitaet; mit Intake, Prüfroutin... |
| `kompendium-04-goldplating-vermeide-bis-legw-bmas-sozialvers` | legistik-werkstatt: eigenständiger Arbeits-Skill für sachlich zusammengehörige Arbeitsmodule zu Goldplating Vermeiden, Inkrafttreten Uebergangsrecht, Legistik Auftragsaufnahme, Legw Aa Ausfuhrkontrolle Und Aussenwirtschaftsdimension; mit... |
| `kompendium-05-legw-bmas-teilhabe-u-bis-legw-bmds-digitale-v` | legistik-werkstatt: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Legw Bmas Teilhabe Und Schwerbehindertenrecht Sgb Ix, Legw Bmbfsfj Familien Und Elterngeldrecht, Legw Bmbfsfj Gleichstellungs Und Antidiskriminierungsrecht,... |
| `kompendium-06-legw-bmds-it-sicherh-bis-legw-bmftr-hochschul` | legistik-werkstatt: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Legw Bmds It Sicherheit Und Bsig, Legw Bmds Ki Verordnung Und Aufsichtsstruktur, Legw Bmds Verwaltungsdigitalisierung Und Registermodernisierung, Legw Bmf Fi... |
| `kompendium-07-legw-bmftr-kuenstlic-bis-legw-bmi-auslaender` | legistik-werkstatt: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Legw Bmftr Kuenstliche Intelligenz Und Technikregulierung, Legw Bmftr Raumfahrt Und Weltraumrecht Wrgg, Legw Bmg Arzneimittel Und Medizinprodukterecht, Legw... |
| `kompendium-08-legw-bmi-bevoelkerun-bis-legw-bmjv-zivilrecht` | legistik-werkstatt: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Legw Bmi Bevoelkerungsschutz Und Katastrophenrecht, Legw Bmi Oeffentlicher Dienst Und Beamtenrecht, Legw Bmi Sicherheits Und Polizeirecht, Legw Bmjv Gerichts... |
| `kompendium-09-legw-bmleh-agrar-und-bis-legw-bmukn-naturschu` | legistik-werkstatt: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Legw Bmleh Agrar Und Foerderungsrecht Gak Gap, Legw Bmleh Forst Und Jagdrecht, Legw Bmleh Lebensmittelrecht Und Futtermittelrecht, Legw Bmleh Tierschutz Und... |
| `kompendium-10-legw-bmukn-wasser-un-bis-legw-bmvg-nato-und-s` | legistik-werkstatt: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Legw Bmukn Wasser Und Bodenschutzrecht, Legw Bmv Luft Und Luftverkehrsrecht, Legw Bmv Mobilitaets Und Fuehrerscheinrecht, Legw Bmv Schienen Und Bahnregulieru... |
| `kompendium-11-legw-bmvg-reserviste-bis-legw-bmwe-wettbewerb` | legistik-werkstatt: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Legw Bmvg Reservisten Und Zivilschutzrecht, Legw Bmvg Verteidigungstechnologie Export, Legw Bmvg Wehrrecht Und Soldatenstatus, Legw Bmwe Aussenwirtschaft Und... |
| `kompendium-12-legw-bmwsb-bau-und-p-bis-legw-bmz-internation` | legistik-werkstatt: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Legw Bmwsb Bau Und Planungsrecht Baugb Baunvo, Legw Bmwsb Bauproduktenrecht Und Technische Normen, Legw Bmwsb Energetische Sanierung Und Geg, Legw Bmwsb Miet... |
| `kompendium-13-legw-bmz-menschenrec-bis-legw-ressort-bmbfsfj` | legistik-werkstatt: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Legw Bmz Menschenrechte In Lieferketten Lksg, Legw Bmz Multilaterale Zusammenarbeit Und Eu, Legw Eu Richtlinienumsetzung Spezial, Legw Rechtsbereinigung Spez... |
| `kompendium-14-legw-ressort-bmds-bis-legw-ressort-bmv` | legistik-werkstatt: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Legw Ressort Bmds, Legw Ressort Bmftr, Legw Ressort Bmg, Legw Ressort Bmi und 4 weitere Arbeitsmodule; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweisl... |
| `kompendium-15-legw-ressort-bmvg-bis-legw-ressortaufgaben` | legistik-werkstatt: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Legw Ressort Bmvg, Legw Ressort Bmwe, Legw Ressort Bmwsb, Legw Ressort Bmz und 4 weitere Arbeitsmodule; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweis... |
| `kompendium-16-legw-ressortaufgaben-bis-legw-ressortaufgaben` | legistik-werkstatt: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Legw Ressortaufgaben Bmds, Legw Ressortaufgaben Bmf, Legw Ressortaufgaben Bmftr, Legw Ressortaufgaben Bmg und 4 weitere Arbeitsmodule; mit Intake, Prüfroutin... |
| `kompendium-17-legw-ressortaufgaben-bis-legw-rmap-entscheidu` | legistik-werkstatt: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Legw Ressortaufgaben Bmv, Legw Ressortaufgaben Bmvg, Legw Ressortaufgaben Bmwe, Legw Ressortaufgaben Bmwsb und 4 weitere Arbeitsmodule; mit Intake, Prüfrouti... |
| `kompendium-18-legw-rmap-evaluierun-bis-lesefassung-konsolid` | legistik-werkstatt: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Legw Rmap Evaluierung Und Aenderung, Legw Rmap Export Und Systemintegration, Legw Rmap Grundlagen, Legw Rmap Norm Zu Rulemap und 4 weitere Arbeitsmodule; mit... |
| `kompendium-19-normenkartierung-bis-spezial-kabinettsent` | legistik-werkstatt: eigenständiger Arbeits-Skill für sachlich zusammengehörige Arbeitsmodule zu Normenkartierung, Normenkontrollrat Kmu Check, Normhierarchie Routing, Satzungskompetenz Pruefen; mit Intake, Prüfroutine, Normen-/Quellenrad... |
| `kompendium-20-spezial-laender-beho-bis-spezial-opposition-r` | legistik-werkstatt: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Laender Behoerden Gericht Und Registerweg, Landtage Schriftsatz Brief Und Memo Bausteine, Legistik Erstpruefung Und Mandatsziel, Ministerien Tatbestand Bewei... |
| `kompendium-21-spezial-referenten-z-bis-zirkelschluss-pruefe` | legistik-werkstatt: eigenständiger Arbeits-Skill für sachlich zusammengehörige Arbeitsmodule zu Spezial Referenten Zahlen Schwellen Und Berechnung, Spezial Vorlagen Mehrparteien Konflikt Und Interessen, Synopse Erstellen, Terminologie Ko... |
| `spezial-baut-livequellen-und-rechtsprechungscheck` | Baut: Livequellen- und Rechtsprechungscheck im Plugin legistik werkstatt; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Standardprüfung. |
| `spezial-entschliessungsantraege-red-team-und-qualitaetskontrolle` | Entschliessungsantraege: Red-Team und Qualitätskontrolle im Plugin legistik werkstatt; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Standardprüfung. |
| `workflow-anschluss-skills-router` | Anschluss-Skills Router im Plugin legistik-werkstatt: schlägt nach der ersten Prüfung die passenden Spezialskills aus demselben Plugin vor. |
| `workflow-dokumentenintake` | Dokumentenintake im Plugin legistik-werkstatt: liest Uploads, sortiert Dokumentarten, markiert Fristen und baut eine knappe Arbeitsakte. |
| `workflow-kaltstart-und-routing` | Kaltstart und Routing im Plugin legistik-werkstatt: führt vom ersten Satz oder Dokument in den passenden Arbeitsweg, erkennt Rolle, Ziel, Risiko und Anschluss-Skills. |
| `workflow-output-waehlen` | Output wählen im Plugin legistik-werkstatt: entscheidet zwischen Memo, Schriftsatz, Tabelle, Brief, Checkliste, Vermerk, Redline oder Mandantenübersetzung. |
| `workflow-rechtsquellen-livecheck` | Rechtsquellen-Livecheck im Plugin legistik-werkstatt: zwingt vor tragenden Aussagen zum aktuellen Quellencheck bei Gesetzen, Behörden, Gerichten und Formularen. |
| `workflow-unterlagen-lueckenliste` | Unterlagen- und Lückenliste im Plugin legistik-werkstatt: erstellt eine präzise Nachforderungsliste statt allgemeiner Fragebögen. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
