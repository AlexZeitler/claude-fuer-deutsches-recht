# Verbraucherschutzverband Durchsetzung

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`verbraucherschutzverband-durchsetzung`) | [`verbraucherschutzverband-durchsetzung.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/verbraucherschutzverband-durchsetzung.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **Verbandsakte Abo-Falle** (`verbraucherschutzverband-abo-falle-sammelklage`) | [Gesamt-PDF lesen](../testakten/verbraucherschutzverband-abo-falle-sammelklage/gesamt-pdf/verbraucherschutzverband-abo-falle-sammelklage_gesamt.pdf) | [`testakte-verbraucherschutzverband-abo-falle-sammelklage.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-verbraucherschutzverband-abo-falle-sammelklage.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

Dieses Plugin arbeitet aus Sicht einer klageberechtigten Stelle: es sortiert Massenphänomene, Betroffenendaten, Anspruchsgruppen, Klageart, Finanzierung, Registerkommunikation, Vergleich und Umsetzung.

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

Automatisch generierte Komplett-Liste aller 28 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `allgemein` | Verbraucherschutzverband Durchsetzung: Kaltstart, Aktenlandkarte, Rollenklärung, Fristen, Quellenprüfung, Spezialskill-Routing und erste Ausgabe. |
| `kompendium-01-vdg-014-umsetzungsve-bis-vdg-033-telekommunik` | verbraucherschutzverband-durchsetzung: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Vdg 014 Umsetzungsverfahren Planen, Vdg 031 Telekommunikationsklausel Sammelfaehig, Vdg 032 Telekommunikationsklausel Klageschrift, Vdg 03... |
| `kompendium-02-vdg-034-telekommunik-bis-vdg-037-telekommunik` | verbraucherschutzverband-durchsetzung: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Vdg 034 Telekommunikationsklausel Registertext, Vdg 035 Telekommunikationsklausel Betroffenenf, Vdg 036 Telekommunikationsklausel Beweispl... |
| `kompendium-03-vdg-038-telekommunik-bis-vdg-106-diesel-diffe` | verbraucherschutzverband-durchsetzung: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Vdg 038 Telekommunikationsklausel Umsetzung Ue, Vdg 039 Telekommunikationsklausel Kommunikatio, Vdg 040 Telekommunikationsklausel Risiko R... |
| `kompendium-04-vdg-029-bankentgelte-bis-vdg-069-abo-modell-k` | verbraucherschutzverband-durchsetzung: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Vdg 029 Bankentgelte Kommunikation Steuern, Vdg 049 Energiepreiserhoehung Kommunikation St, Vdg 059 Plattform Sperre Kommunikation Steuern... |
| `kompendium-05-vdg-079-fitnessstudi-bis-vdg-002-klageberecht` | verbraucherschutzverband-durchsetzung: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Vdg 079 Fitnessstudio Kommunikation Steuern, Vdg 089 Reiseveranstalter Kommunikation Steuer, Vdg 099 Flugportal Kommunikation Steuern, Vdg... |
| `kompendium-06-vdg-003-abhilfeklage-bis-vdg-006-quorum-und-b` | verbraucherschutzverband-durchsetzung: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Vdg 003 Abhilfeklage Oder Musterfeststellung W, Vdg 004 Uklag Unterlassung Gegen Agb, Vdg 005 Uwg Verbraucherinteressen Pruefen, Vdg 006 Q... |
| `kompendium-07-vdg-007-finanzierung-bis-vdg-010-lebenssachve` | verbraucherschutzverband-durchsetzung: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Vdg 007 Finanzierung Und Interessenkonflikte, Vdg 008 Verbandsklageregister Vorbereiten, Vdg 009 Klageziele Praezise Schneiden, Vdg 010 Le... |
| `kompendium-08-vdg-011-beweismittel-bis-vdg-015-sachwalterfr` | verbraucherschutzverband-durchsetzung: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Vdg 011 Beweismittel Offenlegung Nutzen, Vdg 012 Kommunikation An Verbraucher, Vdg 013 Vergleich Und Austritt Pruefen, Vdg 015 Sachwalterf... |
| `kompendium-09-vdg-016-individualkl-bis-vdg-019-kosten-und-p` | verbraucherschutzverband-durchsetzung: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Vdg 016 Individualklagen Koordinieren, Vdg 017 Presse Und Kampagnenrisiko, Vdg 018 Datenschutz Im Betroffenenpool, Vdg 019 Kosten Und Proz... |
| `kompendium-10-vdg-020-erfolgsmonit-bis-vdg-023-bankentgelte` | verbraucherschutzverband-durchsetzung: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Vdg 020 Erfolgsmonitoring, Vdg 021 Bankentgelte Sammelfaehigkeit Pruefen, Vdg 022 Bankentgelte Klageschrift Strukturiere, Vdg 023 Bankentg... |
| `kompendium-11-vdg-024-bankentgelte-bis-vdg-027-bankentgelte` | verbraucherschutzverband-durchsetzung: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Vdg 024 Bankentgelte Registertext Schreiben, Vdg 025 Bankentgelte Betroffenenformular Bauen, Vdg 026 Bankentgelte Beweisplan Erstellen, Vd... |
| `kompendium-12-vdg-028-bankentgelte-bis-vdg-042-energiepreis` | verbraucherschutzverband-durchsetzung: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Vdg 028 Bankentgelte Umsetzung Ueberwachen, Vdg 030 Bankentgelte Risiko Rot Markieren, Vdg 041 Energiepreiserhoehung Sammelfaehigkeit, Vdg... |
| `kompendium-13-vdg-043-energiepreis-bis-vdg-046-energiepreis` | verbraucherschutzverband-durchsetzung: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Vdg 043 Energiepreiserhoehung Anspruchsgruppen, Vdg 044 Energiepreiserhoehung Registertext Sch, Vdg 045 Energiepreiserhoehung Betroffenenf... |
| `kompendium-14-vdg-047-energiepreis-bis-vdg-051-plattform-sp` | verbraucherschutzverband-durchsetzung: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Vdg 047 Energiepreiserhoehung Vergleich Pruefe, Vdg 048 Energiepreiserhoehung Umsetzung Ueberw, Vdg 050 Energiepreiserhoehung Risiko Rot M... |
| `kompendium-15-vdg-052-plattform-sp-bis-vdg-055-plattform-sp` | verbraucherschutzverband-durchsetzung: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Vdg 052 Plattform Sperre Klageschrift Struktur, Vdg 053 Plattform Sperre Anspruchsgruppen Bild, Vdg 054 Plattform Sperre Registertext Schr... |
| `kompendium-16-vdg-056-plattform-sp-bis-vdg-060-plattform-sp` | verbraucherschutzverband-durchsetzung: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Vdg 056 Plattform Sperre Beweisplan Erstellen, Vdg 057 Plattform Sperre Vergleich Pruefen, Vdg 058 Plattform Sperre Umsetzung Ueberwachen,... |
| `kompendium-17-vdg-061-abo-modell-s-bis-vdg-064-abo-modell-r` | verbraucherschutzverband-durchsetzung: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Vdg 061 Abo Modell Sammelfaehigkeit Pruefen, Vdg 062 Abo Modell Klageschrift Strukturieren, Vdg 063 Abo Modell Anspruchsgruppen Bilden, Vd... |
| `kompendium-18-vdg-065-abo-modell-b-bis-vdg-068-abo-modell-u` | verbraucherschutzverband-durchsetzung: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Vdg 065 Abo Modell Betroffenenformular Bauen, Vdg 066 Abo Modell Beweisplan Erstellen, Vdg 067 Abo Modell Vergleich Pruefen, Vdg 068 Abo M... |
| `kompendium-19-vdg-070-abo-modell-r-bis-vdg-073-fitnessstudi` | verbraucherschutzverband-durchsetzung: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Vdg 070 Abo Modell Risiko Rot Markieren, Vdg 071 Fitnessstudio Sammelfaehigkeit Pruefen, Vdg 072 Fitnessstudio Klageschrift Strukturier, V... |
| `kompendium-20-vdg-074-fitnessstudi-bis-vdg-077-fitnessstudi` | verbraucherschutzverband-durchsetzung: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Vdg 074 Fitnessstudio Registertext Schreiben, Vdg 075 Fitnessstudio Betroffenenformular Baue, Vdg 076 Fitnessstudio Beweisplan Erstellen,... |
| `kompendium-21-vdg-078-fitnessstudi-bis-vdg-082-reiseveranst` | verbraucherschutzverband-durchsetzung: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Vdg 078 Fitnessstudio Umsetzung Ueberwachen, Vdg 080 Fitnessstudio Risiko Rot Markieren, Vdg 081 Reiseveranstalter Sammelfaehigkeit Pru, V... |
| `kompendium-22-vdg-083-reiseveranst-bis-vdg-086-reiseveranst` | verbraucherschutzverband-durchsetzung: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Vdg 083 Reiseveranstalter Anspruchsgruppen Bil, Vdg 084 Reiseveranstalter Registertext Schreib, Vdg 085 Reiseveranstalter Betroffenenformu... |
| `kompendium-23-vdg-087-reiseveranst-bis-vdg-091-flugportal-s` | verbraucherschutzverband-durchsetzung: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Vdg 087 Reiseveranstalter Vergleich Pruefen, Vdg 088 Reiseveranstalter Umsetzung Ueberwache, Vdg 090 Reiseveranstalter Risiko Rot Markiere... |
| `kompendium-24-vdg-092-flugportal-k-bis-vdg-095-flugportal-b` | verbraucherschutzverband-durchsetzung: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Vdg 092 Flugportal Klageschrift Strukturieren, Vdg 093 Flugportal Anspruchsgruppen Bilden, Vdg 094 Flugportal Registertext Schreiben, Vdg... |
| `kompendium-25-vdg-096-flugportal-b-bis-vdg-101-bankentgelte` | verbraucherschutzverband-durchsetzung: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Vdg 096 Flugportal Beweisplan Erstellen, Vdg 097 Flugportal Vergleich Pruefen, Vdg 098 Flugportal Umsetzung Ueberwachen, Vdg 101 Bankentge... |
| `kompendium-26-vdg-102-inkasso-konz-bis-vdg-105-schufa-scori` | verbraucherschutzverband-durchsetzung: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Vdg 102 Inkasso Konzerninkasso Musterfeststellung, Vdg 103 Bestellbutton Uklag Uwg Abmahnung, Vdg 104 Probeabo Widerruf Verbandsstrategie,... |
| `vdg-001-kaltstart-verbandsfall-aufnehmen` | Verbraucherschutzverband Durchsetzung: Kaltstart Verbandsfall aufnehmen. Kaltstart Verbandsfall aufnehmen im Fachgebiet Verbraucherschutzverband Durchsetzung als geführten Arbeitsgang mit Fragen, Dokumentenlogik und Ausgabeformat bearbei... |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
