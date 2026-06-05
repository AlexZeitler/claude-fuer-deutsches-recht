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
| `allgemein-workflow-chronologie-workflow-fristen-legw-bmleh` | Allgemein, Workflow Chronologie Und Belegmatrix, Workflow Fristen Und Risikoampel, Legw Bmleh Oekolandbau Und Pflanzenschutzrecht: Allgemein; Workflow Chronologie Und Belegmatrix; Workflow Fristen Und Risikoampel; Legw Bmleh Oekolandbau... |
| `dokumente-rendern-docx-pdf` | Legistische Dokumente als DOCX oder PDF im offiziellen Erscheinungsbild der Bundesregierung, des Bundestages, eines Landes oder eines Landtags rendern. Anwendungsfall fertiger Entwurf soll als lieferfähiges Dokument nach Handbuch der Rec... |
| `folgenabschaetzung-erfuellungsaufwand-folgenabschaetzung` | Folgenabschaetzung Erfuellungsaufwand, Folgenabschaetzung Nachhaltigkeit, Formulierungshilfe Bauen, Gesetzgebungskompetenz Prüfen: Folgenabschaetzung Erfuellungsaufwand; Folgenabschaetzung Nachhaltigkeit; Formulierungshilfe Bauen; Gesetz... |
| `goldplating-vermeiden-inkrafttreten-uebergangsrecht-legistik` | Goldplating Vermeiden, Inkrafttreten Uebergangsrecht, Legistik Auftragsaufnahme, Legw Aa Ausfuhrkontrolle Und Aussenwirtschaftsdimension: Goldplating Vermeiden; Inkrafttreten Uebergangsrecht; Legistik Auftragsaufnahme; Legw Aa Ausfuhrkon... |
| `laender-landtage-legistik-ministerien-opposition` | Spezial Länder Behörden Gericht Und Registerweg, Spezial Landtage Schriftsatz Brief Und Memo Bausteine, Spezial Legistik Erstpruefung Und Mandatsziel, Spezial Ministerien Tatbestand Beweis Und Belege, Spezial Mitte Internationaler Bezug... |
| `legw-aa-eu-bmi-verwaltungsverfahren-gesetzgebungsverfahren` | Legw Aa Eu Grundlagen Und Ratsverfahren, Legw Bmi Verwaltungsverfahren Und Bundesverwaltung, Legw Gesetzgebungsverfahren Bauleiter, Spezial Bundestag Fristen Form Und Zustaendigkeit: Legw Aa Eu Grundlagen Und Ratsverfahren; Legw Bmi Verw... |
| `legw-aa-konsular-bmas-arbeitsrecht-arbeitsschutz` | Legw Aa Konsular Und Passrecht, Legw Bmas Arbeitsrecht Und Arbeitsschutz, Legw Bmas Arbeitsschutz Und Arbeitssicherheit, Legw Bmas Sozialversicherungsrecht Sgb: Legw Aa Konsular Und Passrecht; Legw Bmas Arbeitsrecht Und Arbeitsschutz; Le... |
| `legw-bmas-teilhabe-bmbfsfj-familien-gleichstellungs-kinder` | Legw Bmas Teilhabe Und Schwerbehindertenrecht Sgb Ix, Legw Bmbfsfj Familien Und Elterngeldrecht, Legw Bmbfsfj Gleichstellungs Und Antidiskriminierungsrecht, Legw Bmbfsfj Kinder Und Jugendhilferecht Sgb Viii, Legw Bmbfsfj Schul Und Berufs... |
| `legw-bmds-it-ki-verordnung-verwaltungsdigitalisierung-bmf-bmftr` | Legw Bmds It Sicherheit Und Bsig, Legw Bmds Ki Verordnung Und Aufsichtsstruktur, Legw Bmds Verwaltungsdigitalisierung Und Registermodernisierung, Legw Bmf Finanzmarktaufsicht Bafin Kwg Wpig, Legw Bmf Haushalts Und Zuwendungsrecht und 3 w... |
| `legw-bmftr-kuenstliche-raumfahrt-weltraumrecht-bmg-arzneimittel` | Legw Bmftr Kuenstliche Intelligenz Und Technikregulierung, Legw Bmftr Raumfahrt Und Weltraumrecht Wrgg, Legw Bmg Arzneimittel Und Medizinprodukterecht, Legw Bmg Berufsrecht Heilberufe Und Approbation, Legw Bmg Infektionsschutz Und Pandem... |
| `legw-bmi-bevoelkerungsschutz-oeffentlicher-dienst-sicherheits` | Legw Bmi Bevoelkerungsschutz Und Katastrophenrecht, Legw Bmi Oeffentlicher Dienst Und Beamtenrecht, Legw Bmi Sicherheits Und Polizeirecht, Legw Bmjv Gerichtsverfassungs Und Prozessrecht, Legw Bmjv Rechtsstaatlichkeit Und Grundrechte Quer... |
| `legw-bmleh-agrar-forst-jagdrecht-lebensmittelrecht-tierschutz` | Legw Bmleh Agrar Und Foerderungsrecht Gak Gap, Legw Bmleh Forst Und Jagdrecht, Legw Bmleh Lebensmittelrecht Und Futtermittelrecht, Legw Bmleh Tierschutz Und Tiergesundheitsrecht, Legw Bmukn Abfall Und Kreislaufwirtschaftsrecht und 3 weit... |
| `legw-bmukn-wasser-bmv-luft-mobilitaets-fuehrerscheinrecht-bmvg` | Legw Bmukn Wasser Und Bodenschutzrecht, Legw Bmv Luft Und Luftverkehrsrecht, Legw Bmv Mobilitaets Und Fuehrerscheinrecht, Legw Bmv Schienen Und Bahnregulierung Aeg, Legw Bmv Schifffahrts Und Seeverkehrsrecht und 3 weitere Themen: Legw Bm... |
| `legw-bmvg-reservisten-verteidigungstechnologie-export-wehrrecht` | Legw Bmvg Reservisten Und Zivilschutzrecht, Legw Bmvg Verteidigungstechnologie Export, Legw Bmvg Wehrrecht Und Soldatenstatus, Legw Bmwe Aussenwirtschaft Und Investitionspruefung, Legw Bmwe Energie Und Netzregulierung Enwg und 3 weitere... |
| `legw-bmwsb-bau-bauproduktenrecht-technische-energetische-bmz` | Legw Bmwsb Bau Und Planungsrecht Baugb Baunvo, Legw Bmwsb Bauproduktenrecht Und Technische Normen, Legw Bmwsb Energetische Sanierung Und Geg, Legw Bmwsb Mietrecht Und Wohnungspolitik, Legw Bmwsb Stadtentwicklung Und Foerderprogramme und... |
| `legw-bmz-menschenrechte-multilaterale-zusammenarbeit-eu-ressort` | Legw Bmz Menschenrechte In Lieferketten Lksg, Legw Bmz Multilaterale Zusammenarbeit Und Eu, Legw Eu Richtlinienumsetzung Spezial, Legw Rechtsbereinigung Spezial, Legw Rechtsfolgenabschaetzung Leitfaden und 3 weitere Themen: Legw Bmz Mens... |
| `legw-gesetzesentwurf-kabinett-aa-voelkerrecht-referentenentwurf` | Gesetzesentwurf Kabinett, Legw Aa Voelkerrecht Und Vertragsgesetzgebung, Referentenentwurf Bauen, Legw Aa Sanktionsumsetzung Und Internationale Abkommen, Legw Bmf Geldwaesche Und Sanktionsrecht und 3 weitere Themen: Gesetzesentwurf Kabin... |
| `legw-ressort-bmds-bmftr-bmg-bmi-bmjv-bmv` | Legw Ressort Bmds, Legw Ressort Bmftr, Legw Ressort Bmg, Legw Ressort Bmi, Legw Ressort Bmjv und 3 weitere Themen: Legw Ressort Bmds; Legw Ressort Bmftr; Legw Ressort Bmg; Legw Ressort Bmi; Legw Ressort Bmjv; ...; Legw Ressort Bmv. Führt... |
| `legw-ressort-bmvg-bmwe-bmwsb-bmz-ressortaufgaben-bmbfsfj` | Legw Ressort Bmvg, Legw Ressort Bmwe, Legw Ressort Bmwsb, Legw Ressort Bmz, Legw Ressort Router und 3 weitere Themen: Legw Ressort Bmvg; Legw Ressort Bmwe; Legw Ressort Bmwsb; Legw Ressort Bmz; Legw Ressort Router; ...; Legw Ressortaufga... |
| `legw-ressort-verbaendeanhoerung-ressortabstimmung-begruendung` | Legw Ressort Bmf, Verbaendeanhoerung Ressortabstimmung, Begründung Allgemein Und Besonders, Europarechtskonformitaet: Legw Ressort Bmf; Verbaendeanhoerung Ressortabstimmung; Begründung Allgemein Und Besonders; Europarechtskonformitaet. F... |
| `legw-ressortaufgaben-bmds-bmf-bmftr-bmg-bmi-bmukn` | Legw Ressortaufgaben Bmds, Legw Ressortaufgaben Bmf, Legw Ressortaufgaben Bmftr, Legw Ressortaufgaben Bmg, Legw Ressortaufgaben Bmi und 3 weitere Themen: Legw Ressortaufgaben Bmds; Legw Ressortaufgaben Bmf; Legw Ressortaufgaben Bmftr; Le... |
| `legw-ressortaufgaben-bmv-bmvg-bmwe-bmwsb-bmz-rmap` | Legw Ressortaufgaben Bmv, Legw Ressortaufgaben Bmvg, Legw Ressortaufgaben Bmwe, Legw Ressortaufgaben Bmwsb, Legw Ressortaufgaben Bmz und 3 weitere Themen: Legw Ressortaufgaben Bmv; Legw Ressortaufgaben Bmvg; Legw Ressortaufgaben Bmwe; Le... |
| `legw-rmap-evaluierung-export-systemintegration-grundlagen-norm` | Legw Rmap Evaluierung Und Aenderung, Legw Rmap Export Und Systemintegration, Legw Rmap Grundlagen, Legw Rmap Norm Zu Rulemap, Legw Rmap Tatbestand Und Rechtsfolge und 3 weitere Themen: Legw Rmap Evaluierung Und Aenderung; Legw Rmap Expor... |
| `normenkartierung-normenkontrollrat-kmu-normhierarchie-routing` | Normenkartierung, Normenkontrollrat Kmu Check, Normhierarchie Routing, Satzungskompetenz Prüfen: Normenkartierung; Normenkontrollrat Kmu Check; Normhierarchie Routing; Satzungskompetenz Prüfen. Führt Intake, Prüfroutine, Normen-/Quellenr... |
| `referenten-vorlagen-interessen-synopse-erstellen-terminologie` | Spezial Referenten Zahlen Schwellen Und Berechnung, Spezial Vorlagen Mehrparteien Konflikt Und Interessen, Synopse Erstellen, Terminologie Konsistenz: Spezial Referenten Zahlen Schwellen Und Berechnung; Spezial Vorlagen Mehrparteien Konf... |
| `schulung-legistik-aenderungs-fraktionen-kabinettsentwuerfe` | Schulung Legistik, Spezial Aenderungs Formular Portal Und Einreichung, Spezial Fraktionen Dokumentenmatrix Und Lueckenliste, Spezial Kabinettsentwuerfe Compliance Dokumentation Und Akte: Schulung Legistik; Spezial Aenderungs Formular Por... |
| `spezial-baut-livequellen-und-rechtsprechungscheck` | Baut: Livequellen- und Rechtsprechungscheck im Plugin legistik werkstatt; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Standardprüfung. |
| `spezial-entschliessungsantraege-red-team-und-qualitaetskontrolle` | Entschliessungsantraege: Red-Team und Qualitätskontrolle im Plugin legistik werkstatt; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Standardprüfung. |
| `verfassungsmaessigkeit-quercheck-verordnungsermaechtigung-art80` | Verfassungsmaessigkeit Quercheck, Verordnungsermaechtigung Art80, Xml Paralleldarstellung, Zirkelschluss Prüfen: Verfassungsmaessigkeit Quercheck; Verordnungsermaechtigung Art80; Xml Paralleldarstellung; Zirkelschluss Prüfen. Führt Intak... |
| `workflow-anschluss-skills-router` | Anschluss-Skills Router im Plugin legistik-werkstatt: schlägt nach der ersten Prüfung die passenden Spezialskills aus demselben Plugin vor. |
| `workflow-dokumentenintake` | Dokumentenintake im Plugin legistik-werkstatt: liest Uploads, sortiert Dokumentarten, markiert Fristen und baut eine knappe Arbeitsakte. |
| `workflow-kaltstart-und-routing` | Kaltstart und Routing im Plugin legistik-werkstatt: führt vom ersten Satz oder Dokument in den passenden Arbeitsweg, erkennt Rolle, Ziel, Risiko und Anschluss-Skills. |
| `workflow-output-waehlen` | Output wählen im Plugin legistik-werkstatt: entscheidet zwischen Memo, Schriftsatz, Tabelle, Brief, Checkliste, Vermerk, Redline oder Mandantenübersetzung. |
| `workflow-rechtsquellen-livecheck` | Rechtsquellen-Livecheck im Plugin legistik-werkstatt: zwingt vor tragenden Aussagen zum aktuellen Quellencheck bei Gesetzen, Behörden, Gerichten und Formularen. |
| `workflow-unterlagen-lueckenliste` | Unterlagen- und Lückenliste im Plugin legistik-werkstatt: erstellt eine präzise Nachforderungsliste statt allgemeiner Fragebögen. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
