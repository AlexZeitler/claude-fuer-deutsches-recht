# Straßenrecht und Infrastruktur

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`strassenrecht-infrastruktur`) | [`strassenrecht-infrastruktur.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/strassenrecht-infrastruktur.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **Straßenrechtsakte Auenfeld** (`strassenrecht-ortsdurchfahrt-bruecke-auenfeld`) | [Gesamt-PDF lesen](../testakten/strassenrecht-ortsdurchfahrt-bruecke-auenfeld/gesamt-pdf/strassenrecht-ortsdurchfahrt-bruecke-auenfeld_gesamt.pdf) | [`testakte-strassenrecht-ortsdurchfahrt-bruecke-auenfeld.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-strassenrecht-ortsdurchfahrt-bruecke-auenfeld.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

Dieses Plugin trennt Straßenrecht von Straßenverkehrsrecht: Bau, Widmung, Baulast, Unterhaltung, Sondernutzung, Planfeststellung, Anliegerrechte, Kreuzungen, Umstufung und Straßeninfrastruktur.

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

Automatisch generierte Komplett-Liste aller 27 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `allgemein` | Straßenrecht und Infrastruktur: Kaltstart, Aktenlandkarte, Rollenklärung, Fristen, Quellenprüfung, Spezialskill-Routing und erste Ausgabe. |
| `kompendium-01-str-002-bundesfernst-bis-str-005-umstufung-un` | strassenrecht-infrastruktur: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Str 002 Bundesfernstrasse Oder Landesstrasse, Str 003 Strassenbaulasttraeger Bestimmen, Str 004 Widmung Und Einziehung Pruefen, Str 005 Umstufung Un... |
| `kompendium-02-str-006-planfeststel-bis-str-009-sondernutzun` | strassenrecht-infrastruktur: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Str 006 Planfeststellung Strasse, Str 007 Plangenehmigung Und Uvp, Str 008 Anliegergebrauch Abgrenzen, Str 009 Sondernutzungserlaubnis; mit Intake,... |
| `kompendium-03-str-010-baustelle-un-bis-str-013-rastanlage-u` | strassenrecht-infrastruktur: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Str 010 Baustelle Und Verkehrsfuehrung, Str 011 Strassenentwaesserung, Str 012 Bruecke Und Tunnel, Str 013 Rastanlage Und Nebenbetrieb; mit Intake,... |
| `kompendium-04-str-014-kreuzungsrec-bis-str-017-schaeden-dur` | strassenrecht-infrastruktur: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Str 014 Kreuzungsrecht Bahn Wasser Strasse, Str 015 Strassenausbaubeitrag Pruefen, Str 016 Unterhaltungspflicht Und Winterdienst, Str 017 Schaeden D... |
| `kompendium-05-str-018-eilrechtssch-bis-str-021-autobahn-bau` | strassenrecht-infrastruktur: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Str 018 Eilrechtsschutz Gegen Bau, Str 019 Aktenplan Infrastruktur, Str 020 Landesstrassengesetz Livecheck, Str 021 Autobahn Baulast Pruefen; mit In... |
| `kompendium-06-str-022-autobahn-wid-bis-str-025-autobahn-ein` | strassenrecht-infrastruktur: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Str 022 Autobahn Widmung Lesen, Str 023 Autobahn Planrecht Pruefen, Str 024 Autobahn Sondernutzung Formulieren, Str 025 Autobahn Einwendung Bauen; m... |
| `kompendium-07-str-026-autobahn-eil-bis-str-029-autobahn-dok` | strassenrecht-infrastruktur: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Str 026 Autobahn Eilantrag Skizzieren, Str 027 Autobahn Kostenlast Pruefen, Str 028 Autobahn Unterhaltung Ruegen, Str 029 Autobahn Dokumente Sortier... |
| `kompendium-08-str-030-autobahn-das-bis-str-033-bundesstrass` | strassenrecht-infrastruktur: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Str 030 Autobahn Dashboard Erstellen, Str 031 Bundesstrasse Baulast Pruefen, Str 032 Bundesstrasse Widmung Lesen, Str 033 Bundesstrasse Planrecht Pr... |
| `kompendium-09-str-034-bundesstrass-bis-str-037-bundesstrass` | strassenrecht-infrastruktur: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Str 034 Bundesstrasse Sondernutzung Formuliere, Str 035 Bundesstrasse Einwendung Bauen, Str 036 Bundesstrasse Eilantrag Skizzieren, Str 037 Bundesst... |
| `kompendium-10-str-038-bundesstrass-bis-str-041-landesstrass` | strassenrecht-infrastruktur: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Str 038 Bundesstrasse Unterhaltung Ruegen, Str 039 Bundesstrasse Dokumente Sortieren, Str 040 Bundesstrasse Dashboard Erstellen, Str 041 Landesstras... |
| `kompendium-11-str-042-landesstrass-bis-str-045-landesstrass` | strassenrecht-infrastruktur: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Str 042 Landesstrasse Widmung Lesen, Str 043 Landesstrasse Planrecht Pruefen, Str 044 Landesstrasse Sondernutzung Formuliere, Str 045 Landesstrasse... |
| `kompendium-12-str-046-landesstrass-bis-str-049-landesstrass` | strassenrecht-infrastruktur: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Str 046 Landesstrasse Eilantrag Skizzieren, Str 047 Landesstrasse Kostenlast Pruefen, Str 048 Landesstrasse Unterhaltung Ruegen, Str 049 Landesstras... |
| `kompendium-13-str-050-landesstrass-bis-str-053-kreisstrasse` | strassenrecht-infrastruktur: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Str 050 Landesstrasse Dashboard Erstellen, Str 051 Kreisstrasse Baulast Pruefen, Str 052 Kreisstrasse Widmung Lesen, Str 053 Kreisstrasse Planrecht... |
| `kompendium-14-str-054-kreisstrasse-bis-str-057-kreisstrasse` | strassenrecht-infrastruktur: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Str 054 Kreisstrasse Sondernutzung Formulieren, Str 055 Kreisstrasse Einwendung Bauen, Str 056 Kreisstrasse Eilantrag Skizzieren, Str 057 Kreisstras... |
| `kompendium-15-str-058-kreisstrasse-bis-str-061-gemeindestra` | strassenrecht-infrastruktur: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Str 058 Kreisstrasse Unterhaltung Ruegen, Str 059 Kreisstrasse Dokumente Sortieren, Str 060 Kreisstrasse Dashboard Erstellen, Str 061 Gemeindestrass... |
| `kompendium-16-str-062-gemeindestra-bis-str-065-gemeindestra` | strassenrecht-infrastruktur: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Str 062 Gemeindestrasse Widmung Lesen, Str 063 Gemeindestrasse Planrecht Pruefen, Str 064 Gemeindestrasse Sondernutzung Formulie, Str 065 Gemeindest... |
| `kompendium-17-str-066-gemeindestra-bis-str-069-gemeindestra` | strassenrecht-infrastruktur: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Str 066 Gemeindestrasse Eilantrag Skizzieren, Str 067 Gemeindestrasse Kostenlast Pruefen, Str 068 Gemeindestrasse Unterhaltung Ruegen, Str 069 Gemei... |
| `kompendium-18-str-070-gemeindestra-bis-str-073-ortsdurchfah` | strassenrecht-infrastruktur: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Str 070 Gemeindestrasse Dashboard Erstellen, Str 071 Ortsdurchfahrt Baulast Pruefen, Str 072 Ortsdurchfahrt Widmung Lesen, Str 073 Ortsdurchfahrt Pl... |
| `kompendium-19-str-074-ortsdurchfah-bis-str-077-ortsdurchfah` | strassenrecht-infrastruktur: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Str 074 Ortsdurchfahrt Sondernutzung Formulier, Str 075 Ortsdurchfahrt Einwendung Bauen, Str 076 Ortsdurchfahrt Eilantrag Skizzieren, Str 077 Ortsdu... |
| `kompendium-20-str-078-ortsdurchfah-bis-str-081-bruecke-baul` | strassenrecht-infrastruktur: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Str 078 Ortsdurchfahrt Unterhaltung Ruegen, Str 079 Ortsdurchfahrt Dokumente Sortieren, Str 080 Ortsdurchfahrt Dashboard Erstellen, Str 081 Bruecke... |
| `kompendium-21-str-082-bruecke-widm-bis-str-085-bruecke-einw` | strassenrecht-infrastruktur: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Str 082 Bruecke Widmung Lesen, Str 083 Bruecke Planrecht Pruefen, Str 084 Bruecke Sondernutzung Formulieren, Str 085 Bruecke Einwendung Bauen; mit I... |
| `kompendium-22-str-086-bruecke-eila-bis-str-089-bruecke-doku` | strassenrecht-infrastruktur: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Str 086 Bruecke Eilantrag Skizzieren, Str 087 Bruecke Kostenlast Pruefen, Str 088 Bruecke Unterhaltung Ruegen, Str 089 Bruecke Dokumente Sortieren;... |
| `kompendium-23-str-090-bruecke-dash-bis-str-093-tunnel-planr` | strassenrecht-infrastruktur: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Str 090 Bruecke Dashboard Erstellen, Str 091 Tunnel Baulast Pruefen, Str 092 Tunnel Widmung Lesen, Str 093 Tunnel Planrecht Pruefen; mit Intake, Prü... |
| `kompendium-24-str-094-tunnel-sonde-bis-str-097-tunnel-koste` | strassenrecht-infrastruktur: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Str 094 Tunnel Sondernutzung Formulieren, Str 095 Tunnel Einwendung Bauen, Str 096 Tunnel Eilantrag Skizzieren, Str 097 Tunnel Kostenlast Pruefen; m... |
| `kompendium-25-str-098-tunnel-unter-bis-str-099-tunnel-dokum` | strassenrecht-infrastruktur: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Str 098 Tunnel Unterhaltung Ruegen, Str 099 Tunnel Dokumente Sortieren; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und... |
| `str-001-kaltstart-strassenrechtsfall` | Straßenrecht und Infrastruktur: Kaltstart Straßenrechtsfall. Kaltstart Straßenrechtsfall im Fachgebiet Straßenrecht und Infrastruktur als geführten Arbeitsgang mit Fragen, Dokumentenlogik und Ausgabeformat bearbeiten. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
