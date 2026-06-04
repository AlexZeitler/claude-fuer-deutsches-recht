# Tierschutzrecht

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`tierschutzrecht`) | [`tierschutzrecht.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/tierschutzrecht.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **Tierschutzakte Pferdehof Auenwiese** (`tierschutzrecht-veterinaeramt-pferdehof-auenwiese`) | [Gesamt-PDF lesen](../testakten/tierschutzrecht-veterinaeramt-pferdehof-auenwiese/gesamt-pdf/tierschutzrecht-veterinaeramt-pferdehof-auenwiese_gesamt.pdf) | [`testakte-tierschutzrecht-veterinaeramt-pferdehof-auenwiese.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-tierschutzrecht-veterinaeramt-pferdehof-auenwiese.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

Dieses Plugin nimmt Tiere rechtlich ernst: § 90a BGB als Ausgangspunkt, TierSchG als öffentlich-rechtliches und strafrechtliches Schutzregime, dazu Zivilrecht, Behördenaufsicht, Veterinäramt und Vollzug.

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
| `allgemein` | Tierschutzrecht: Kaltstart, Aktenlandkarte, Rollenklärung, Fristen, Quellenprüfung, Spezialskill-Routing und erste Ausgabe. |
| `kompendium-01-tier-004-veterinaera-bis-tier-026-hundehaltun` | tierschutzrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Tier 004 Veterinaeramt Zustaendigkeit, Tier 008 Bussgeldverfahren Tierschg, Tier 014 Tierheimvertrag Und Kosten, Tier 026 Hundehaltung Bussgeld Verteidigen; mit... |
| `kompendium-02-tier-036-katzenkolon-bis-tier-066-schweinehal` | tierschutzrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Tier 036 Katzenkolonie Bussgeld Verteidigen, Tier 046 Pferdestall Bussgeld Verteidigen, Tier 056 Rinderbetrieb Bussgeld Verteidigen, Tier 066 Schweinehaltung Bu... |
| `kompendium-03-tier-076-gefluegelma-bis-tier-002-90a-bgb-ric` | tierschutzrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Tier 076 Gefluegelmast Bussgeld Verteidigen, Tier 086 Tiertransport Bussgeld Verteidigen, Tier 096 Schlachthof Bussgeld Verteidigen, Tier 002 90a Bgb Richtig Ei... |
| `kompendium-04-tier-003-tierschg-gr-bis-tier-007-tierschutz` | tierschutzrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Tier 003 Tierschg Grundsatz Und Leiden Pruefen, Tier 005 Haltung Und Betreuung Dokumentieren, Tier 006 Anordnung Und Wegnahme Pruefen, Tier 007 Tierschutz Straf... |
| `kompendium-05-tier-009-eilrechtssc-bis-tier-012-fundtier-un` | tierschutzrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Tier 009 Eilrechtsschutz Gegen Haltungsverbot, Tier 010 Tierhalter Zivilrechtlich Beraten, Tier 011 Tierarzt Und Behandlungsfehler, Tier 012 Fundtier Und Eigent... |
| `kompendium-06-tier-013-gefaehrlich-bis-tier-017-tierversuch` | tierschutzrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Tier 013 Gefaehrlicher Hund Landesrecht, Tier 015 Zucht Und Qualzucht, Tier 016 Tiertransport Pruefen, Tier 017 Tierversuch Genehmigung; mit Intake, Prüfroutine... |
| `kompendium-07-tier-018-nutztierhal-bis-tier-021-hundehaltun` | tierschutzrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Tier 018 Nutztierhaltung Kontrolle, Tier 019 Tierschutzverein Handlungsoptionen, Tier 020 Beweisfotos Und Datenschutz, Tier 021 Hundehaltung Schutzbedarf Pruefe... |
| `kompendium-08-tier-022-hundehaltun-bis-tier-025-hundehaltun` | tierschutzrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Tier 022 Hundehaltung Behoerdenantrag Schreiben, Tier 023 Hundehaltung Anordnung Angreifen, Tier 024 Hundehaltung Beweise Sichern, Tier 025 Hundehaltung Strafri... |
| `kompendium-09-tier-027-hundehaltun-bis-tier-030-hundehaltun` | tierschutzrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Tier 027 Hundehaltung Kosten Klaeren, Tier 028 Hundehaltung Halterpflichten Erklaeren, Tier 029 Hundehaltung Eilantrag Bauen, Tier 030 Hundehaltung Vergleich Su... |
| `kompendium-10-tier-031-katzenkolon-bis-tier-034-katzenkolon` | tierschutzrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Tier 031 Katzenkolonie Schutzbedarf Pruefen, Tier 032 Katzenkolonie Behoerdenantrag Schreibe, Tier 033 Katzenkolonie Anordnung Angreifen, Tier 034 Katzenkolonie... |
| `kompendium-11-tier-035-katzenkolon-bis-tier-039-katzenkolon` | tierschutzrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Tier 035 Katzenkolonie Strafrisiko Bewerten, Tier 037 Katzenkolonie Kosten Klaeren, Tier 038 Katzenkolonie Halterpflichten Erklaere, Tier 039 Katzenkolonie Eila... |
| `kompendium-12-tier-040-katzenkolon-bis-tier-043-pferdestall` | tierschutzrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Tier 040 Katzenkolonie Vergleich Suchen, Tier 041 Pferdestall Schutzbedarf Pruefen, Tier 042 Pferdestall Behoerdenantrag Schreiben, Tier 043 Pferdestall Anordnu... |
| `kompendium-13-tier-044-pferdestall-bis-tier-048-pferdestall` | tierschutzrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Tier 044 Pferdestall Beweise Sichern, Tier 045 Pferdestall Strafrisiko Bewerten, Tier 047 Pferdestall Kosten Klaeren, Tier 048 Pferdestall Halterpflichten Erkla... |
| `kompendium-14-tier-049-pferdestall-bis-tier-052-rinderbetri` | tierschutzrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Tier 049 Pferdestall Eilantrag Bauen, Tier 050 Pferdestall Vergleich Suchen, Tier 051 Rinderbetrieb Schutzbedarf Pruefen, Tier 052 Rinderbetrieb Behoerdenantrag... |
| `kompendium-15-tier-053-rinderbetri-bis-tier-057-rinderbetri` | tierschutzrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Tier 053 Rinderbetrieb Anordnung Angreifen, Tier 054 Rinderbetrieb Beweise Sichern, Tier 055 Rinderbetrieb Strafrisiko Bewerten, Tier 057 Rinderbetrieb Kosten K... |
| `kompendium-16-tier-058-rinderbetri-bis-tier-061-schweinehal` | tierschutzrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Tier 058 Rinderbetrieb Halterpflichten Erklaere, Tier 059 Rinderbetrieb Eilantrag Bauen, Tier 060 Rinderbetrieb Vergleich Suchen, Tier 061 Schweinehaltung Schut... |
| `kompendium-17-tier-062-schweinehal-bis-tier-065-schweinehal` | tierschutzrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Tier 062 Schweinehaltung Behoerdenantrag Schrei, Tier 063 Schweinehaltung Anordnung Angreifen, Tier 064 Schweinehaltung Beweise Sichern, Tier 065 Schweinehaltun... |
| `kompendium-18-tier-067-schweinehal-bis-tier-070-schweinehal` | tierschutzrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Tier 067 Schweinehaltung Kosten Klaeren, Tier 068 Schweinehaltung Halterpflichten Erklae, Tier 069 Schweinehaltung Eilantrag Bauen, Tier 070 Schweinehaltung Ver... |
| `kompendium-19-tier-071-gefluegelma-bis-tier-074-gefluegelma` | tierschutzrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Tier 071 Gefluegelmast Schutzbedarf Pruefen, Tier 072 Gefluegelmast Behoerdenantrag Schreibe, Tier 073 Gefluegelmast Anordnung Angreifen, Tier 074 Gefluegelmast... |
| `kompendium-20-tier-075-gefluegelma-bis-tier-079-gefluegelma` | tierschutzrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Tier 075 Gefluegelmast Strafrisiko Bewerten, Tier 077 Gefluegelmast Kosten Klaeren, Tier 078 Gefluegelmast Halterpflichten Erklaere, Tier 079 Gefluegelmast Eila... |
| `kompendium-21-tier-080-gefluegelma-bis-tier-083-tiertranspo` | tierschutzrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Tier 080 Gefluegelmast Vergleich Suchen, Tier 081 Tiertransport Schutzbedarf Pruefen, Tier 082 Tiertransport Behoerdenantrag Schreibe, Tier 083 Tiertransport An... |
| `kompendium-22-tier-084-tiertranspo-bis-tier-088-tiertranspo` | tierschutzrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Tier 084 Tiertransport Beweise Sichern, Tier 085 Tiertransport Strafrisiko Bewerten, Tier 087 Tiertransport Kosten Klaeren, Tier 088 Tiertransport Halterpflicht... |
| `kompendium-23-tier-089-tiertranspo-bis-tier-092-schlachthof` | tierschutzrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Tier 089 Tiertransport Eilantrag Bauen, Tier 090 Tiertransport Vergleich Suchen, Tier 091 Schlachthof Schutzbedarf Pruefen, Tier 092 Schlachthof Behoerdenantrag... |
| `kompendium-24-tier-093-schlachthof-bis-tier-097-schlachthof` | tierschutzrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Tier 093 Schlachthof Anordnung Angreifen, Tier 094 Schlachthof Beweise Sichern, Tier 095 Schlachthof Strafrisiko Bewerten, Tier 097 Schlachthof Kosten Klaeren;... |
| `kompendium-25-tier-098-schlachthof-bis-tier-099-schlachthof` | tierschutzrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Tier 098 Schlachthof Halterpflichten Erklaeren, Tier 099 Schlachthof Eilantrag Bauen; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster u... |
| `tier-001-kaltstart-tierschutzfall` | Tierschutzrecht: Kaltstart Tierschutzfall. Kaltstart Tierschutzfall im Fachgebiet Tierschutzrecht als geführten Arbeitsgang mit Fragen, Dokumentenlogik und Ausgabeformat bearbeiten. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
