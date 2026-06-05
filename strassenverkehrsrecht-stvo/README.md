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
| `stv-001-kaltstart-stvo-fall` | Straßenverkehrsrecht StVO: Kaltstart StVO-Fall. Kaltstart StVO-Fall im Fachgebiet Straßenverkehrsrecht StVO als geführten Arbeitsgang mit Fragen, Dokumentenlogik und Ausgabeformat bearbeiten. |
| `stv-bewohnerparken-eilrechtsschutz-behoerde-anschreiben-karte` | Stv 067 Bewohnerparken Eilrechtsschutz Planen, Stv 068 Bewohnerparken Behörde Anschreiben, Stv 069 Bewohnerparken Karte Bauen, Stv 070 Bewohnerparken Risiko Erklaeren: Stv 067 Bewohnerparken Eilrechtsschutz Planen; Stv 068 Bewohnerparken... |
| `stv-bewohnerparken-zeichen-anordnung-angreifen-antrag-schreiben` | Stv 062 Bewohnerparken Zeichen Auslegen, Stv 063 Bewohnerparken Anordnung Angreifen, Stv 064 Bewohnerparken Antrag Schreiben, Stv 065 Bewohnerparken Beweis Sichern: Stv 062 Bewohnerparken Zeichen Auslegen; Stv 063 Bewohnerparken Anordnun... |
| `stv-bussgeldschnittstelle-stv-haltverbot-stv-tempo-stv` | Stv 017 Bussgeldschnittstelle Owig, Stv 026 Haltverbot Bussgeld Abgrenzen, Stv 036 Tempo 30 Bussgeld Abgrenzen, Stv 046 Fahrradstrasse Bussgeld Abgrenzen: Stv 017 Bussgeldschnittstelle Owig; Stv 026 Haltverbot Bussgeld Abgrenzen; Stv 036... |
| `stv-busspur-anordnung-antrag-schreiben-sichern-eilrechtsschutz` | Stv 053 Busspur Anordnung Angreifen, Stv 054 Busspur Antrag Schreiben, Stv 055 Busspur Beweis Sichern, Stv 057 Busspur Eilrechtsschutz Planen: Stv 053 Busspur Anordnung Angreifen; Stv 054 Busspur Antrag Schreiben; Stv 055 Busspur Beweis... |
| `stv-busspur-behoerde-karte-bauen-risiko-erklaeren-bewohnerparken` | Stv 058 Busspur Behörde Anschreiben, Stv 059 Busspur Karte Bauen, Stv 060 Busspur Risiko Erklaeren, Stv 061 Bewohnerparken Regel Prüfen: Stv 058 Busspur Behörde Anschreiben; Stv 059 Busspur Karte Bauen; Stv 060 Busspur Risiko Erklaeren;... |
| `stv-busspur-stv-bewohnerparken-stv-lieferzone-stv-ladezone` | Stv 056 Busspur Bussgeld Abgrenzen, Stv 066 Bewohnerparken Bussgeld Abgrenzen, Stv 076 Lieferzone Bussgeld Abgrenzen, Stv 086 Ladezone Bussgeld Abgrenzen: Stv 056 Busspur Bussgeld Abgrenzen; Stv 066 Bewohnerparken Bussgeld Abgrenzen; Stv... |
| `stv-fahrradstrasse-antrag-sichern-eilrechtsschutz-planen` | Stv 044 Fahrradstrasse Antrag Schreiben, Stv 045 Fahrradstrasse Beweis Sichern, Stv 047 Fahrradstrasse Eilrechtsschutz Planen, Stv 048 Fahrradstrasse Behörde Anschreiben: Stv 044 Fahrradstrasse Antrag Schreiben; Stv 045 Fahrradstrasse Be... |
| `stv-fahrradstrasse-karte-risiko-erklaeren-busspur-regel-zeichen` | Stv 049 Fahrradstrasse Karte Bauen, Stv 050 Fahrradstrasse Risiko Erklaeren, Stv 051 Busspur Regel Prüfen, Stv 052 Busspur Zeichen Auslegen: Stv 049 Fahrradstrasse Karte Bauen; Stv 050 Fahrradstrasse Risiko Erklaeren; Stv 051 Busspur Reg... |
| `stv-gefahrenstelle-melden-schulweg-verkehrsberuhigung-blaulicht` | Stv 013 Gefahrenstelle Melden, Stv 014 Schulweg Und Verkehrsberuhigung, Stv 015 Baustellenverkehrsrecht, Stv 016 Blaulicht Und Sonderrechte: Stv 013 Gefahrenstelle Melden; Stv 014 Schulweg Und Verkehrsberuhigung; Stv 015 Baustellenverkeh... |
| `stv-haltverbot-eilrechtsschutz-behoerde-anschreiben-karte-bauen` | Stv 027 Haltverbot Eilrechtsschutz Planen, Stv 028 Haltverbot Behörde Anschreiben, Stv 029 Haltverbot Karte Bauen, Stv 030 Haltverbot Risiko Erklaeren: Stv 027 Haltverbot Eilrechtsschutz Planen; Stv 028 Haltverbot Behörde Anschreiben; St... |
| `stv-haltverbot-zeichen-anordnung-angreifen-antrag-schreiben` | Stv 022 Haltverbot Zeichen Auslegen, Stv 023 Haltverbot Anordnung Angreifen, Stv 024 Haltverbot Antrag Schreiben, Stv 025 Haltverbot Beweis Sichern: Stv 022 Haltverbot Zeichen Auslegen; Stv 023 Haltverbot Anordnung Angreifen; Stv 024 Hal... |
| `stv-ladezone-antrag-sichern-eilrechtsschutz-planen-behoerde` | Stv 084 Ladezone Antrag Schreiben, Stv 085 Ladezone Beweis Sichern, Stv 087 Ladezone Eilrechtsschutz Planen, Stv 088 Ladezone Behörde Anschreiben: Stv 084 Ladezone Antrag Schreiben; Stv 085 Ladezone Beweis Sichern; Stv 087 Ladezone Eilre... |
| `stv-ladezone-karte-risiko-erklaeren-schulstrasse-regel-zeichen` | Stv 089 Ladezone Karte Bauen, Stv 090 Ladezone Risiko Erklaeren, Stv 091 Schulstrasse Regel Prüfen, Stv 092 Schulstrasse Zeichen Auslegen: Stv 089 Ladezone Karte Bauen; Stv 090 Ladezone Risiko Erklaeren; Stv 091 Schulstrasse Regel Prüfen... |
| `stv-lieferzone-regel-zeichen-auslegen-anordnung-angreifen-antrag` | Stv 071 Lieferzone Regel Prüfen, Stv 072 Lieferzone Zeichen Auslegen, Stv 073 Lieferzone Anordnung Angreifen, Stv 074 Lieferzone Antrag Schreiben: Stv 071 Lieferzone Regel Prüfen; Stv 072 Lieferzone Zeichen Auslegen; Stv 073 Lieferzone A... |
| `stv-lieferzone-risiko-ladezone-regel-zeichen-auslegen-anordnung` | Stv 080 Lieferzone Risiko Erklaeren, Stv 081 Ladezone Regel Prüfen, Stv 082 Ladezone Zeichen Auslegen, Stv 083 Ladezone Anordnung Angreifen: Stv 080 Lieferzone Risiko Erklaeren; Stv 081 Ladezone Regel Prüfen; Stv 082 Ladezone Zeichen Aus... |
| `stv-lieferzone-sichern-eilrechtsschutz-planen-behoerde-karte` | Stv 075 Lieferzone Beweis Sichern, Stv 077 Lieferzone Eilrechtsschutz Planen, Stv 078 Lieferzone Behörde Anschreiben, Stv 079 Lieferzone Karte Bauen: Stv 075 Lieferzone Beweis Sichern; Stv 077 Lieferzone Eilrechtsschutz Planen; Stv 078 L... |
| `stv-parken-stv-ausnahmegenehmigung-stv-radverkehr-stv-e` | Stv 005 Parken Halten Abschleppen, Stv 006 Ausnahmegenehmigung Beantragen, Stv 007 Radverkehr Und Schutzstreifen, Stv 008 E Scooter Und Mikromobilitaet: Stv 005 Parken Halten Abschleppen; Stv 006 Ausnahmegenehmigung Beantragen; Stv 007 R... |
| `stv-schulstrasse-anordnung-antrag-schreiben-sichern` | Stv 093 Schulstrasse Anordnung Angreifen, Stv 094 Schulstrasse Antrag Schreiben, Stv 095 Schulstrasse Beweis Sichern, Stv 097 Schulstrasse Eilrechtsschutz Planen: Stv 093 Schulstrasse Anordnung Angreifen; Stv 094 Schulstrasse Antrag Schr... |
| `stv-schulstrasse-bussgeld-verkehrszeichen-lesen-tempozone` | Stv 096 Schulstrasse Bussgeld Abgrenzen, Stv 002 Verkehrszeichen Lesen, Stv 003 Verkehrsrechtliche Anordnung Prüfen, Stv 004 Tempozone Und Beschilderung: Stv 096 Schulstrasse Bussgeld Abgrenzen; Stv 002 Verkehrszeichen Lesen; Stv 003 Ver... |
| `stv-schulstrasse-stv-schulstrasse` | Stv 098 Schulstrasse Behörde Anschreiben, Stv 099 Schulstrasse Karte Bauen: Stv 098 Schulstrasse Behörde Anschreiben; Stv 099 Schulstrasse Karte Bauen. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualit... |
| `stv-schwertransport-stv-fahrerlaubnis-stv-mpu-stv` | Stv 009 Schwertransport Und Erlaubnis, Stv 010 Fahrerlaubnis Schnittstelle, Stv 011 Mpu Und Fahreignung, Stv 012 Fahrtenbuchauflage: Stv 009 Schwertransport Und Erlaubnis; Stv 010 Fahrerlaubnis Schnittstelle; Stv 011 Mpu Und Fahreignung;... |
| `stv-tempo-regel-zeichen-auslegen-anordnung-angreifen-antrag` | Stv 031 Tempo 30 Regel Prüfen, Stv 032 Tempo 30 Zeichen Auslegen, Stv 033 Tempo 30 Anordnung Angreifen, Stv 034 Tempo 30 Antrag Schreiben: Stv 031 Tempo 30 Regel Prüfen; Stv 032 Tempo 30 Zeichen Auslegen; Stv 033 Tempo 30 Anordnung Angre... |
| `stv-tempo-sichern-eilrechtsschutz-planen-behoerde-anschreiben` | Stv 035 Tempo 30 Beweis Sichern, Stv 037 Tempo 30 Eilrechtsschutz Planen, Stv 038 Tempo 30 Behörde Anschreiben, Stv 039 Tempo 30 Karte Bauen: Stv 035 Tempo 30 Beweis Sichern; Stv 037 Tempo 30 Eilrechtsschutz Planen; Stv 038 Tempo 30 Behö... |
| `stv-tempo-stv-fahrradstrasse-stv-fahrradstrasse-stv` | Stv 040 Tempo 30 Risiko Erklaeren, Stv 041 Fahrradstrasse Regel Prüfen, Stv 042 Fahrradstrasse Zeichen Auslegen, Stv 043 Fahrradstrasse Anordnung Angreifen: Stv 040 Tempo 30 Risiko Erklaeren; Stv 041 Fahrradstrasse Regel Prüfen; Stv 042... |
| `stv-widerspruch-stv-eilrechtsschutz-stv-kommunikation-stv` | Stv 018 Widerspruch Gegen Verkehrszeichen, Stv 019 Eilrechtsschutz Verkehrszeichen, Stv 020 Kommunikation Mit Strassenverkehrsbeho, Stv 021 Haltverbot Regel Prüfen: Stv 018 Widerspruch Gegen Verkehrszeichen; Stv 019 Eilrechtsschutz Verke... |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
