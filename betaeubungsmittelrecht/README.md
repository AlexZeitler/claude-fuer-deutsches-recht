# Betäubungsmittelrecht

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`betaeubungsmittelrecht`) | [`betaeubungsmittelrecht.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/betaeubungsmittelrecht.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **BtM-Akte** (`betaeubungsmittelrecht-apotheke-substitution-festival`) | [Gesamt-PDF lesen](../testakten/betaeubungsmittelrecht-apotheke-substitution-festival/gesamt-pdf/betaeubungsmittelrecht-apotheke-substitution-festival_gesamt.pdf) | [`testakte-betaeubungsmittelrecht-apotheke-substitution-festival.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-betaeubungsmittelrecht-apotheke-substitution-festival.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

Dieses Plugin behandelt BtM nicht nur strafrechtlich: Verkehrsfähigkeit, Verschreibung, Apotheke, ärztliche Praxis, Erlaubnis, Strafverteidigung, Therapie, Cannabis-Schnittstelle und Compliance werden getrennt geführt.

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
| `allgemein` | Betäubungsmittelrecht: Kaltstart, Aktenlandkarte, Rollenklärung, Fristen, Quellenprüfung, Spezialskill-Routing und erste Ausgabe. |
| `btm-001-kaltstart-btm-fall` | Betäubungsmittelrecht: Kaltstart BtM-Fall. Kaltstart BtM-Fall im Fachgebiet Betäubungsmittelrecht als geführten Arbeitsgang mit Fragen, Dokumentenlogik und Ausgabeformat bearbeiten. |
| `kompendium-01-btm-002-stoff-und-an-bis-btm-005-einfuhr-ausf` | betaeubungsmittelrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Btm 002 Stoff Und Anlage Pruefen, Btm 003 Nicht Geringe Menge Livecheck, Btm 004 Handeltreiben Oder Besitz, Btm 005 Einfuhr Ausfuhr Durchfuhr; mit Intake... |
| `kompendium-02-btm-006-btm-rezept-u-bis-btm-009-therapie-sta` | betaeubungsmittelrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Btm 006 Btm Rezept Und Btmvv, Btm 007 Arztpraxis Compliance, Btm 008 Apotheke Btm Dokumentation, Btm 009 Therapie Statt Strafe; mit Intake, Prüfroutine,... |
| `kompendium-03-btm-010-aufklaerungs-bis-btm-013-durchsuchung` | betaeubungsmittelrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Btm 010 Aufklaerungshilfe 31 Btmg, Btm 011 Kcang Und Medcang Abgrenzen, Btm 012 Neue Psychoaktive Stoffe, Btm 013 Durchsuchung Und Beschlagnahme; mit Int... |
| `kompendium-04-btm-014-u-haft-in-bt-bis-btm-017-fahrerlaubni` | betaeubungsmittelrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Btm 014 U Haft In Btm Sache, Btm 015 Einziehung Und Wertersatz, Btm 016 Jugendliche Und Btm, Btm 017 Fahrerlaubnis Und Btm; mit Intake, Prüfroutine, Norm... |
| `kompendium-05-btm-018-internationa-bis-btm-021-cannabis-sto` | betaeubungsmittelrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Btm 018 Internationaler Versand, Btm 019 Betriebspruefung Apotheke, Btm 020 Btm In Einfacher Sprache, Btm 021 Cannabis Stoff Pruefen; mit Intake, Prüfrou... |
| `kompendium-06-btm-022-cannabis-men-bis-btm-025-cannabis-ein` | betaeubungsmittelrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Btm 022 Cannabis Menge Einordnen, Btm 023 Cannabis Strafrahmen Routen, Btm 024 Cannabis Beweis Sichern, Btm 025 Cannabis Einlassung Planen; mit Intake, P... |
| `kompendium-07-btm-026-cannabis-the-bis-btm-029-cannabis-akt` | betaeubungsmittelrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Btm 026 Cannabis Therapiepfad Pruefen, Btm 027 Cannabis Erlaubnis Pruefen, Btm 028 Cannabis Compliance Bauen, Btm 029 Cannabis Akteneinsicht Vorbereiten;... |
| `kompendium-08-btm-030-cannabis-man-bis-btm-033-kokain-straf` | betaeubungsmittelrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Btm 030 Cannabis Mandantenbrief Schreiben, Btm 031 Kokain Stoff Pruefen, Btm 032 Kokain Menge Einordnen, Btm 033 Kokain Strafrahmen Routen; mit Intake, P... |
| `kompendium-09-btm-034-kokain-bewei-bis-btm-037-kokain-erlau` | betaeubungsmittelrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Btm 034 Kokain Beweis Sichern, Btm 035 Kokain Einlassung Planen, Btm 036 Kokain Therapiepfad Pruefen, Btm 037 Kokain Erlaubnis Pruefen; mit Intake, Prüfr... |
| `kompendium-10-btm-038-kokain-compl-bis-btm-041-heroin-stoff` | betaeubungsmittelrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Btm 038 Kokain Compliance Bauen, Btm 039 Kokain Akteneinsicht Vorbereiten, Btm 040 Kokain Mandantenbrief Schreiben, Btm 041 Heroin Stoff Pruefen; mit Int... |
| `kompendium-11-btm-042-heroin-menge-bis-btm-045-heroin-einla` | betaeubungsmittelrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Btm 042 Heroin Menge Einordnen, Btm 043 Heroin Strafrahmen Routen, Btm 044 Heroin Beweis Sichern, Btm 045 Heroin Einlassung Planen; mit Intake, Prüfrouti... |
| `kompendium-12-btm-046-heroin-thera-bis-btm-049-heroin-akten` | betaeubungsmittelrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Btm 046 Heroin Therapiepfad Pruefen, Btm 047 Heroin Erlaubnis Pruefen, Btm 048 Heroin Compliance Bauen, Btm 049 Heroin Akteneinsicht Vorbereiten; mit Int... |
| `kompendium-13-btm-050-heroin-manda-bis-btm-053-amphetamin-s` | betaeubungsmittelrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Btm 050 Heroin Mandantenbrief Schreiben, Btm 051 Amphetamin Stoff Pruefen, Btm 052 Amphetamin Menge Einordnen, Btm 053 Amphetamin Strafrahmen Routen; mit... |
| `kompendium-14-btm-054-amphetamin-b-bis-btm-057-amphetamin-e` | betaeubungsmittelrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Btm 054 Amphetamin Beweis Sichern, Btm 055 Amphetamin Einlassung Planen, Btm 056 Amphetamin Therapiepfad Pruefen, Btm 057 Amphetamin Erlaubnis Pruefen; m... |
| `kompendium-15-btm-058-amphetamin-c-bis-btm-061-mdma-stoff-p` | betaeubungsmittelrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Btm 058 Amphetamin Compliance Bauen, Btm 059 Amphetamin Akteneinsicht Vorbereiten, Btm 060 Amphetamin Mandantenbrief Schreiben, Btm 061 Mdma Stoff Pruefe... |
| `kompendium-16-btm-062-mdma-menge-e-bis-btm-065-mdma-einlass` | betaeubungsmittelrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Btm 062 Mdma Menge Einordnen, Btm 063 Mdma Strafrahmen Routen, Btm 064 Mdma Beweis Sichern, Btm 065 Mdma Einlassung Planen; mit Intake, Prüfroutine, Norm... |
| `kompendium-17-btm-066-mdma-therapi-bis-btm-069-mdma-aktenei` | betaeubungsmittelrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Btm 066 Mdma Therapiepfad Pruefen, Btm 067 Mdma Erlaubnis Pruefen, Btm 068 Mdma Compliance Bauen, Btm 069 Mdma Akteneinsicht Vorbereiten; mit Intake, Prü... |
| `kompendium-18-btm-070-mdma-mandant-bis-btm-073-fentanyl-str` | betaeubungsmittelrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Btm 070 Mdma Mandantenbrief Schreiben, Btm 071 Fentanyl Stoff Pruefen, Btm 072 Fentanyl Menge Einordnen, Btm 073 Fentanyl Strafrahmen Routen; mit Intake,... |
| `kompendium-19-btm-074-fentanyl-bew-bis-btm-077-fentanyl-erl` | betaeubungsmittelrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Btm 074 Fentanyl Beweis Sichern, Btm 075 Fentanyl Einlassung Planen, Btm 076 Fentanyl Therapiepfad Pruefen, Btm 077 Fentanyl Erlaubnis Pruefen; mit Intak... |
| `kompendium-20-btm-078-fentanyl-com-bis-btm-081-methadon-sto` | betaeubungsmittelrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Btm 078 Fentanyl Compliance Bauen, Btm 079 Fentanyl Akteneinsicht Vorbereiten, Btm 080 Fentanyl Mandantenbrief Schreiben, Btm 081 Methadon Stoff Pruefen;... |
| `kompendium-21-btm-082-methadon-men-bis-btm-085-methadon-ein` | betaeubungsmittelrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Btm 082 Methadon Menge Einordnen, Btm 083 Methadon Strafrahmen Routen, Btm 084 Methadon Beweis Sichern, Btm 085 Methadon Einlassung Planen; mit Intake, P... |
| `kompendium-22-btm-086-methadon-the-bis-btm-089-methadon-akt` | betaeubungsmittelrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Btm 086 Methadon Therapiepfad Pruefen, Btm 087 Methadon Erlaubnis Pruefen, Btm 088 Methadon Compliance Bauen, Btm 089 Methadon Akteneinsicht Vorbereiten;... |
| `kompendium-23-btm-090-methadon-man-bis-btm-093-medizinalcan` | betaeubungsmittelrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Btm 090 Methadon Mandantenbrief Schreiben, Btm 091 Medizinalcannabis Stoff Pruefen, Btm 092 Medizinalcannabis Menge Einordnen, Btm 093 Medizinalcannabis... |
| `kompendium-24-btm-094-medizinalcan-bis-btm-097-medizinalcan` | betaeubungsmittelrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Btm 094 Medizinalcannabis Beweis Sichern, Btm 095 Medizinalcannabis Einlassung Planen, Btm 096 Medizinalcannabis Therapiepfad Pruefen, Btm 097 Medizinalc... |
| `kompendium-25-btm-098-medizinalcan-bis-btm-099-medizinalcan` | betaeubungsmittelrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Btm 098 Medizinalcannabis Compliance Bauen, Btm 099 Medizinalcannabis Akteneinsicht Vorber; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, O... |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
