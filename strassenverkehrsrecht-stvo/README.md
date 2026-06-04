# Straßenverkehrsrecht StVO

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`strassenverkehrsrecht-stvo`) | [`strassenverkehrsrecht-stvo.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/strassenverkehrsrecht-stvo.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **StVO-Akte Schulstraße/Lieferzone** (`strassenverkehrsrecht-stvo-schulstrasse-lieferzone`) | [Gesamt-PDF lesen](../testakten/strassenverkehrsrecht-stvo-schulstrasse-lieferzone/gesamt-pdf/strassenverkehrsrecht-stvo-schulstrasse-lieferzone_gesamt.pdf) | [`testakte-strassenverkehrsrecht-stvo-schulstrasse-lieferzone.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-strassenverkehrsrecht-stvo-schulstrasse-lieferzone.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

Dieses Plugin erklärt und prüft das Verhalten im Straßenverkehr und die behördliche Verkehrssteuerung: StVO, StVG, FeV, Zeichen, Anordnungen, Sondernutzungsschnittstellen, Ausnahmegenehmigung und Rechtsschutz.

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
| `allgemein` | Straßenverkehrsrecht StVO: Kaltstart, Aktenlandkarte, Rollenklärung, Fristen, Quellenprüfung, Spezialskill-Routing und erste Ausgabe. |
| `kompendium-01-stv-017-bussgeldschn-bis-stv-046-fahrradstras` | strassenverkehrsrecht-stvo: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Stv 017 Bussgeldschnittstelle Owig, Stv 026 Haltverbot Bussgeld Abgrenzen, Stv 036 Tempo 30 Bussgeld Abgrenzen, Stv 046 Fahrradstrasse Bussgeld Abgre... |
| `kompendium-02-stv-056-busspur-buss-bis-stv-086-ladezone-bus` | strassenverkehrsrecht-stvo: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Stv 056 Busspur Bussgeld Abgrenzen, Stv 066 Bewohnerparken Bussgeld Abgrenzen, Stv 076 Lieferzone Bussgeld Abgrenzen, Stv 086 Ladezone Bussgeld Abgre... |
| `kompendium-03-stv-096-schulstrasse-bis-stv-004-tempozone-un` | strassenverkehrsrecht-stvo: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Stv 096 Schulstrasse Bussgeld Abgrenzen, Stv 002 Verkehrszeichen Lesen, Stv 003 Verkehrsrechtliche Anordnung Pruefen, Stv 004 Tempozone Und Beschilde... |
| `kompendium-04-stv-005-parken-halte-bis-stv-008-e-scooter-un` | strassenverkehrsrecht-stvo: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Stv 005 Parken Halten Abschleppen, Stv 006 Ausnahmegenehmigung Beantragen, Stv 007 Radverkehr Und Schutzstreifen, Stv 008 E Scooter Und Mikromobilita... |
| `kompendium-05-stv-009-schwertransp-bis-stv-012-fahrtenbucha` | strassenverkehrsrecht-stvo: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Stv 009 Schwertransport Und Erlaubnis, Stv 010 Fahrerlaubnis Schnittstelle, Stv 011 Mpu Und Fahreignung, Stv 012 Fahrtenbuchauflage; mit Intake, Prüf... |
| `kompendium-06-stv-013-gefahrenstel-bis-stv-016-blaulicht-un` | strassenverkehrsrecht-stvo: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Stv 013 Gefahrenstelle Melden, Stv 014 Schulweg Und Verkehrsberuhigung, Stv 015 Baustellenverkehrsrecht, Stv 016 Blaulicht Und Sonderrechte; mit Inta... |
| `kompendium-07-stv-018-widerspruch-bis-stv-021-haltverbot-r` | strassenverkehrsrecht-stvo: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Stv 018 Widerspruch Gegen Verkehrszeichen, Stv 019 Eilrechtsschutz Verkehrszeichen, Stv 020 Kommunikation Mit Strassenverkehrsbeho, Stv 021 Haltverbo... |
| `kompendium-08-stv-022-haltverbot-z-bis-stv-025-haltverbot-b` | strassenverkehrsrecht-stvo: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Stv 022 Haltverbot Zeichen Auslegen, Stv 023 Haltverbot Anordnung Angreifen, Stv 024 Haltverbot Antrag Schreiben, Stv 025 Haltverbot Beweis Sichern;... |
| `kompendium-09-stv-027-haltverbot-e-bis-stv-030-haltverbot-r` | strassenverkehrsrecht-stvo: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Stv 027 Haltverbot Eilrechtsschutz Planen, Stv 028 Haltverbot Behoerde Anschreiben, Stv 029 Haltverbot Karte Bauen, Stv 030 Haltverbot Risiko Erklaer... |
| `kompendium-10-stv-031-tempo-30-reg-bis-stv-034-tempo-30-ant` | strassenverkehrsrecht-stvo: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Stv 031 Tempo 30 Regel Pruefen, Stv 032 Tempo 30 Zeichen Auslegen, Stv 033 Tempo 30 Anordnung Angreifen, Stv 034 Tempo 30 Antrag Schreiben; mit Intak... |
| `kompendium-11-stv-035-tempo-30-bew-bis-stv-039-tempo-30-kar` | strassenverkehrsrecht-stvo: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Stv 035 Tempo 30 Beweis Sichern, Stv 037 Tempo 30 Eilrechtsschutz Planen, Stv 038 Tempo 30 Behoerde Anschreiben, Stv 039 Tempo 30 Karte Bauen; mit In... |
| `kompendium-12-stv-040-tempo-30-ris-bis-stv-043-fahrradstras` | strassenverkehrsrecht-stvo: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Stv 040 Tempo 30 Risiko Erklaeren, Stv 041 Fahrradstrasse Regel Pruefen, Stv 042 Fahrradstrasse Zeichen Auslegen, Stv 043 Fahrradstrasse Anordnung An... |
| `kompendium-13-stv-044-fahrradstras-bis-stv-048-fahrradstras` | strassenverkehrsrecht-stvo: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Stv 044 Fahrradstrasse Antrag Schreiben, Stv 045 Fahrradstrasse Beweis Sichern, Stv 047 Fahrradstrasse Eilrechtsschutz Planen, Stv 048 Fahrradstrasse... |
| `kompendium-14-stv-049-fahrradstras-bis-stv-052-busspur-zeic` | strassenverkehrsrecht-stvo: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Stv 049 Fahrradstrasse Karte Bauen, Stv 050 Fahrradstrasse Risiko Erklaeren, Stv 051 Busspur Regel Pruefen, Stv 052 Busspur Zeichen Auslegen; mit Int... |
| `kompendium-15-stv-053-busspur-anor-bis-stv-057-busspur-eilr` | strassenverkehrsrecht-stvo: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Stv 053 Busspur Anordnung Angreifen, Stv 054 Busspur Antrag Schreiben, Stv 055 Busspur Beweis Sichern, Stv 057 Busspur Eilrechtsschutz Planen; mit In... |
| `kompendium-16-stv-058-busspur-beho-bis-stv-061-bewohnerpark` | strassenverkehrsrecht-stvo: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Stv 058 Busspur Behoerde Anschreiben, Stv 059 Busspur Karte Bauen, Stv 060 Busspur Risiko Erklaeren, Stv 061 Bewohnerparken Regel Pruefen; mit Intake... |
| `kompendium-17-stv-062-bewohnerpark-bis-stv-065-bewohnerpark` | strassenverkehrsrecht-stvo: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Stv 062 Bewohnerparken Zeichen Auslegen, Stv 063 Bewohnerparken Anordnung Angreifen, Stv 064 Bewohnerparken Antrag Schreiben, Stv 065 Bewohnerparken... |
| `kompendium-18-stv-067-bewohnerpark-bis-stv-070-bewohnerpark` | strassenverkehrsrecht-stvo: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Stv 067 Bewohnerparken Eilrechtsschutz Planen, Stv 068 Bewohnerparken Behoerde Anschreiben, Stv 069 Bewohnerparken Karte Bauen, Stv 070 Bewohnerparke... |
| `kompendium-19-stv-071-lieferzone-r-bis-stv-074-lieferzone-a` | strassenverkehrsrecht-stvo: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Stv 071 Lieferzone Regel Pruefen, Stv 072 Lieferzone Zeichen Auslegen, Stv 073 Lieferzone Anordnung Angreifen, Stv 074 Lieferzone Antrag Schreiben; m... |
| `kompendium-20-stv-075-lieferzone-b-bis-stv-079-lieferzone-k` | strassenverkehrsrecht-stvo: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Stv 075 Lieferzone Beweis Sichern, Stv 077 Lieferzone Eilrechtsschutz Planen, Stv 078 Lieferzone Behoerde Anschreiben, Stv 079 Lieferzone Karte Bauen... |
| `kompendium-21-stv-080-lieferzone-r-bis-stv-083-ladezone-ano` | strassenverkehrsrecht-stvo: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Stv 080 Lieferzone Risiko Erklaeren, Stv 081 Ladezone Regel Pruefen, Stv 082 Ladezone Zeichen Auslegen, Stv 083 Ladezone Anordnung Angreifen; mit Int... |
| `kompendium-22-stv-084-ladezone-ant-bis-stv-088-ladezone-beh` | strassenverkehrsrecht-stvo: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Stv 084 Ladezone Antrag Schreiben, Stv 085 Ladezone Beweis Sichern, Stv 087 Ladezone Eilrechtsschutz Planen, Stv 088 Ladezone Behoerde Anschreiben; m... |
| `kompendium-23-stv-089-ladezone-kar-bis-stv-092-schulstrasse` | strassenverkehrsrecht-stvo: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Stv 089 Ladezone Karte Bauen, Stv 090 Ladezone Risiko Erklaeren, Stv 091 Schulstrasse Regel Pruefen, Stv 092 Schulstrasse Zeichen Auslegen; mit Intak... |
| `kompendium-24-stv-093-schulstrasse-bis-stv-097-schulstrasse` | strassenverkehrsrecht-stvo: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Stv 093 Schulstrasse Anordnung Angreifen, Stv 094 Schulstrasse Antrag Schreiben, Stv 095 Schulstrasse Beweis Sichern, Stv 097 Schulstrasse Eilrechtss... |
| `kompendium-25-stv-098-schulstrasse-bis-stv-099-schulstrasse` | strassenverkehrsrecht-stvo: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Stv 098 Schulstrasse Behoerde Anschreiben, Stv 099 Schulstrasse Karte Bauen; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster... |
| `stv-001-kaltstart-stvo-fall` | Straßenverkehrsrecht StVO: Kaltstart StVO-Fall. Kaltstart StVO-Fall im Fachgebiet Straßenverkehrsrecht StVO als geführten Arbeitsgang mit Fragen, Dokumentenlogik und Ausgabeformat bearbeiten. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
