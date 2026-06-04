# Kommunalrecht der Länder

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`kommunalrecht-laender`) | [`kommunalrecht-laender.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/kommunalrecht-laender.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **Kommunalakte Morgenfurt** (`kommunalrecht-rathaus-morgenfurt-buergerentscheid-haushalt`) | [Gesamt-PDF lesen](../testakten/kommunalrecht-rathaus-morgenfurt-buergerentscheid-haushalt/gesamt-pdf/kommunalrecht-rathaus-morgenfurt-buergerentscheid-haushalt_gesamt.pdf) | [`testakte-kommunalrecht-rathaus-morgenfurt-buergerentscheid-haushalt.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-kommunalrecht-rathaus-morgenfurt-buergerentscheid-haushalt.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

Dieses Plugin ist die Werkbank für kommunale Selbstverwaltung: Rat, Bürgermeister, Landkreis, Satzung, Gebühren, Haushalt, Bürgerbegehren, Kommunalaufsicht, kommunale Unternehmen und Landesrecht.

## Start

Beginne mit `allgemein`. Das Plugin fragt zuerst nach Rolle, Ziel, Frist, Behörde/Gericht/Register, vorhandenen Unterlagen und gewünschtem Output. Danach schlägt es die passenden Spezialskills aus diesem Plugin vor.

## Arbeitsweise

- Es arbeitet mit Akten- und Fristenlogik statt mit Bauchgefühl.
- Es trennt Rechtsgrundlage, Verfahren, Beweis, Kosten, Kommunikation und Eskalation.
- Es soll Nutzerinnen und Nutzer befähigen: verständliche Erklärung, präzise Rückfragen, dann belastbarer Entwurf.
- Rechtsprechung und Gesetzesstände werden nicht halluziniert, sondern als Live-Check über amtliche oder frei zugängliche Quellen markiert.

## Typische Outputs

- Kaltstart-Interview und Aktenlandkarte
- Behörden-, Gerichts- oder Gegneranschreiben
- Widerspruchs-/Klage-/Eilantragsbausteine
- Kosten-, Fristen- und Zuständigkeitsmatrix
- Dashboard/Tracker für laufende Vorgänge
- Kurzfassung für Mandant, Vorstand, Verband, Redaktion oder Bürgerin

## Quellenhygiene

Siehe [`references/QUELLEN.md`](./references/QUELLEN.md). Dieses Plugin gibt keine endgültige Rechtsberatung, sondern robuste Arbeitsfassungen, Prüfpfade und Dokumentationshilfen.

## Lizenz

Apache-2.0 OR MIT — Auswahl beim Empfänger.

<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 29 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `allgemein` | Kommunalrecht der Länder: Kaltstart, Aktenlandkarte, Rollenklärung, Fristen, Quellenprüfung, Spezialskill-Routing und erste Ausgabe. |
| `kom-001-kaltstart-kommunalrechtsfall` | Kommunalrecht der Länder: Kaltstart Kommunalrechtsfall. Kaltstart Kommunalrechtsfall im Fachgebiet Kommunalrecht der Länder als geführten Arbeitsgang mit Fragen, Dokumentenlogik und Ausgabeformat bearbeiten. |
| `kompendium-01-kom-003-organ-und-zu-bis-kom-078-landrat-zust` | kommunalrecht-laender: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Kom 003 Organ Und Zustaendigkeit Pruefen, Kom 038 Gemeinderat Zustaendigkeit Pruefen, Kom 048 Stadtrat Zustaendigkeit Pruefen, Kom 058 Kreistag Zustaendig... |
| `kompendium-02-kom-088-ausschuss-zu-bis-kom-138-kita-satzung` | kommunalrecht-laender: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Kom 088 Ausschuss Zustaendigkeit Pruefen, Kom 098 Ortschaftsrat Zustaendigkeit Pruefen, Kom 108 Kommunalaufsicht Zustaendigkeit Pruefe, Kom 118 Kommunalab... |
| `kompendium-03-kom-148-schultraeger-bis-kom-120-kommunalabga` | kommunalrecht-laender: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Kom 148 Schultraeger Zustaendigkeit Pruefen, Kom 158 Feuerwehr Zustaendigkeit Pruefen, Kom 010 Kommunalabgaben Pruefen, Kom 117 Kommunalabgabe Landesrecht... |
| `kompendium-04-kom-121-kommunalabga-bis-kom-126-kommunalabga` | kommunalrecht-laender: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Kom 121 Kommunalabgabe Gebuehr Kalkulieren, Kom 122 Kommunalabgabe Aufsichtsbeschwerde Sch, Kom 123 Kommunalabgabe Eilantrag Vorbereiten, Kom 124 Kommunal... |
| `kompendium-05-kom-002-gemeinde-sta-bis-kom-008-buergerbegeh` | kommunalrecht-laender: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Kom 002 Gemeinde Stadt Landkreis Zuordnen, Kom 004 Ratssitzung Und Tagesordnung, Kom 005 Beschluss Und Befangenheit, Kom 006 Satzung Entwerfen Und Pruefen... |
| `kompendium-06-kom-009-einwohnerant-bis-kom-015-sondernutzun` | kommunalrecht-laender: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Kom 009 Einwohnerantrag Und Petition, Kom 011 Haushalt Und Haushaltssicherung, Kom 012 Kommunales Unternehmen, Kom 013 Oeffentliche Einrichtung und 2 weit... |
| `kompendium-07-kom-016-kommunaler-f-bis-kom-021-kommunalrech` | kommunalrecht-laender: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Kom 016 Kommunaler Finanzausgleich, Kom 017 Interkommunale Zusammenarbeit, Kom 018 Informationsrechte Ratsmitglied, Kom 019 Eilrechtsschutz Kommunalstreit... |
| `kompendium-08-kom-022-kommunalrech-bis-kom-027-kommunalrech` | kommunalrecht-laender: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Kom 022 Kommunalrecht Bayern Routen, Kom 023 Kommunalrecht Berlin Routen, Kom 024 Kommunalrecht Brandenburg Routen, Kom 025 Kommunalrecht Bremen Routen un... |
| `kompendium-09-kom-028-kommunalrech-bis-kom-033-kommunalrech` | kommunalrecht-laender: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Kom 028 Kommunalrecht Mecklenburg Vorpommern R, Kom 029 Kommunalrecht Niedersachsen Routen, Kom 030 Kommunalrecht Nordrhein Westfalen Rout, Kom 031 Kommun... |
| `kompendium-10-kom-034-kommunalrech-bis-kom-040-gemeinderat` | kommunalrecht-laender: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Kom 034 Kommunalrecht Sachsen Anhalt Routen, Kom 035 Kommunalrecht Schleswig Holstein Route, Kom 036 Kommunalrecht Thueringen Routen, Kom 037 Gemeinderat... |
| `kompendium-11-kom-041-gemeinderat-bis-kom-046-gemeinderat` | kommunalrecht-laender: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Kom 041 Gemeinderat Gebuehr Kalkulieren, Kom 042 Gemeinderat Aufsichtsbeschwerde Schrei, Kom 043 Gemeinderat Eilantrag Vorbereiten, Kom 044 Gemeinderat Fi... |
| `kompendium-12-kom-047-stadtrat-lan-bis-kom-053-stadtrat-eil` | kommunalrecht-laender: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Kom 047 Stadtrat Landesrecht Routen, Kom 049 Stadtrat Beschluss Bauen, Kom 050 Stadtrat Satzung Redlinen, Kom 051 Stadtrat Gebuehr Kalkulieren und 2 weite... |
| `kompendium-13-kom-054-stadtrat-fin-bis-kom-060-kreistag-sat` | kommunalrecht-laender: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Kom 054 Stadtrat Finanzierung Erklaeren, Kom 055 Stadtrat Dashboard Bauen, Kom 056 Stadtrat Beteiligung Planen, Kom 057 Kreistag Landesrecht Routen und 2... |
| `kompendium-14-kom-061-kreistag-geb-bis-kom-066-kreistag-bet` | kommunalrecht-laender: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Kom 061 Kreistag Gebuehr Kalkulieren, Kom 062 Kreistag Aufsichtsbeschwerde Schreiben, Kom 063 Kreistag Eilantrag Vorbereiten, Kom 064 Kreistag Finanzierun... |
| `kompendium-15-kom-067-buergermeist-bis-kom-073-buergermeist` | kommunalrecht-laender: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Kom 067 Buergermeister Landesrecht Routen, Kom 069 Buergermeister Beschluss Bauen, Kom 070 Buergermeister Satzung Redlinen, Kom 071 Buergermeister Gebuehr... |
| `kompendium-16-kom-074-buergermeist-bis-kom-080-landrat-satz` | kommunalrecht-laender: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Kom 074 Buergermeister Finanzierung Erklaeren, Kom 075 Buergermeister Dashboard Bauen, Kom 076 Buergermeister Beteiligung Planen, Kom 077 Landrat Landesre... |
| `kompendium-17-kom-081-landrat-gebu-bis-kom-086-landrat-bete` | kommunalrecht-laender: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Kom 081 Landrat Gebuehr Kalkulieren, Kom 082 Landrat Aufsichtsbeschwerde Schreiben, Kom 083 Landrat Eilantrag Vorbereiten, Kom 084 Landrat Finanzierung Er... |
| `kompendium-18-kom-087-ausschuss-la-bis-kom-093-ausschuss-ei` | kommunalrecht-laender: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Kom 087 Ausschuss Landesrecht Routen, Kom 089 Ausschuss Beschluss Bauen, Kom 090 Ausschuss Satzung Redlinen, Kom 091 Ausschuss Gebuehr Kalkulieren und 2 w... |
| `kompendium-19-kom-094-ausschuss-fi-bis-kom-100-ortschaftsra` | kommunalrecht-laender: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Kom 094 Ausschuss Finanzierung Erklaeren, Kom 095 Ausschuss Dashboard Bauen, Kom 096 Ausschuss Beteiligung Planen, Kom 097 Ortschaftsrat Landesrecht Route... |
| `kompendium-20-kom-101-ortschaftsra-bis-kom-106-ortschaftsra` | kommunalrecht-laender: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Kom 101 Ortschaftsrat Gebuehr Kalkulieren, Kom 102 Ortschaftsrat Aufsichtsbeschwerde Schr, Kom 103 Ortschaftsrat Eilantrag Vorbereiten, Kom 104 Ortschafts... |
| `kompendium-21-kom-107-kommunalaufs-bis-kom-113-kommunalaufs` | kommunalrecht-laender: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Kom 107 Kommunalaufsicht Landesrecht Routen, Kom 109 Kommunalaufsicht Beschluss Bauen, Kom 110 Kommunalaufsicht Satzung Redlinen, Kom 111 Kommunalaufsicht... |
| `kompendium-22-kom-114-kommunalaufs-bis-kom-130-strassenrein` | kommunalrecht-laender: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Kom 114 Kommunalaufsicht Finanzierung Erklaere, Kom 115 Kommunalaufsicht Dashboard Bauen, Kom 116 Kommunalaufsicht Beteiligung Planen, Kom 127 Strassenrei... |
| `kompendium-23-kom-131-strassenrein-bis-kom-136-strassenrein` | kommunalrecht-laender: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Kom 131 Strassenreinigung Gebuehr Kalkulieren, Kom 132 Strassenreinigung Aufsichtsbeschwerde, Kom 133 Strassenreinigung Eilantrag Vorbereite, Kom 134 Stra... |
| `kompendium-24-kom-137-kita-satzung-bis-kom-143-kita-satzung` | kommunalrecht-laender: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Kom 137 Kita Satzung Landesrecht Routen, Kom 139 Kita Satzung Beschluss Bauen, Kom 140 Kita Satzung Satzung Redlinen, Kom 141 Kita Satzung Gebuehr Kalkuli... |
| `kompendium-25-kom-144-kita-satzung-bis-kom-150-schultraeger` | kommunalrecht-laender: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Kom 144 Kita Satzung Finanzierung Erklaeren, Kom 145 Kita Satzung Dashboard Bauen, Kom 146 Kita Satzung Beteiligung Planen, Kom 147 Schultraeger Landesrec... |
| `kompendium-26-kom-151-schultraeger-bis-kom-156-schultraeger` | kommunalrecht-laender: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Kom 151 Schultraeger Gebuehr Kalkulieren, Kom 152 Schultraeger Aufsichtsbeschwerde Schre, Kom 153 Schultraeger Eilantrag Vorbereiten, Kom 154 Schultraeger... |
| `kompendium-27-kom-157-feuerwehr-la-bis-kom-159-feuerwehr-be` | kommunalrecht-laender: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Kom 157 Feuerwehr Landesrecht Routen, Kom 159 Feuerwehr Beschluss Bauen; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qual... |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
