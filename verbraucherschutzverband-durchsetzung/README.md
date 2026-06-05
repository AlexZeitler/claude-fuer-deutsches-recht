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
| `vdg-001-kaltstart-verbandsfall-aufnehmen` | Verbraucherschutzverband Durchsetzung: Kaltstart Verbandsfall aufnehmen. Kaltstart Verbandsfall aufnehmen im Fachgebiet Verbraucherschutzverband Durchsetzung als geführten Arbeitsgang mit Fragen, Dokumentenlogik und Ausgabeformat bearbei... |
| `vdg-abhilfeklage-vdg-uklag-vdg-uwg-vdg-quorum` | Vdg 003 Abhilfeklage Oder Musterfeststellung W, Vdg 004 Uklag Unterlassung Gegen Agb, Vdg 005 Uwg Verbraucherinteressen Prüfen, Vdg 006 Quorum Und Betroffenengruppe: Vdg 003 Abhilfeklage Oder Musterfeststellung W; Vdg 004 Uklag Unterlass... |
| `vdg-abo-modell-fitnessstudio-sammelfaehigkeit-klageschrift` | Vdg 070 Abo Modell Risiko Rot Markieren, Vdg 071 Fitnessstudio Sammelfaehigkeit Prüfen, Vdg 072 Fitnessstudio Klageschrift Strukturier, Vdg 073 Fitnessstudio Anspruchsgruppen Bilden: Vdg 070 Abo Modell Risiko Rot Markieren; Vdg 071 Fitne... |
| `vdg-abo-vdg-abo-vdg-abo-vdg-abo` | Vdg 061 Abo Modell Sammelfaehigkeit Prüfen, Vdg 062 Abo Modell Klageschrift Strukturieren, Vdg 063 Abo Modell Anspruchsgruppen Bilden, Vdg 064 Abo Modell Registertext Schreiben: Vdg 061 Abo Modell Sammelfaehigkeit Prüfen; Vdg 062 Abo Mod... |
| `vdg-abo-vdg-abo-vdg-abo-vdg-abo-02` | Vdg 065 Abo Modell Betroffenenformular Bauen, Vdg 066 Abo Modell Beweisplan Erstellen, Vdg 067 Abo Modell Vergleich Prüfen, Vdg 068 Abo Modell Umsetzung Ueberwachen: Vdg 065 Abo Modell Betroffenenformular Bauen; Vdg 066 Abo Modell Beweis... |
| `vdg-bankentgelte-kommunikation-energiepreiserhoehung-st-abo` | Vdg 029 Bankentgelte Kommunikation Steuern, Vdg 049 Energiepreiserhoehung Kommunikation St, Vdg 059 Plattform Sperre Kommunikation Steuern, Vdg 069 Abo Modell Kommunikation Steuern: Vdg 029 Bankentgelte Kommunikation Steuern; Vdg 049 Ene... |
| `vdg-bankentgelte-registertext-betroffenenformular-bauen` | Vdg 024 Bankentgelte Registertext Schreiben, Vdg 025 Bankentgelte Betroffenenformular Bauen, Vdg 026 Bankentgelte Beweisplan Erstellen, Vdg 027 Bankentgelte Vergleich Prüfen: Vdg 024 Bankentgelte Registertext Schreiben; Vdg 025 Bankentge... |
| `vdg-bankentgelte-umsetzung-risiko-rot-energiepreiserhoehung` | Vdg 028 Bankentgelte Umsetzung Ueberwachen, Vdg 030 Bankentgelte Risiko Rot Markieren, Vdg 041 Energiepreiserhoehung Sammelfaehigkeit, Vdg 042 Energiepreiserhoehung Klageschrift Str: Vdg 028 Bankentgelte Umsetzung Ueberwachen; Vdg 030 Ba... |
| `vdg-beweismittel-vdg-kommunikation-vdg-austritt-vdg` | Vdg 011 Beweismittel Offenlegung Nutzen, Vdg 012 Kommunikation An Verbraucher, Vdg 013 Vergleich Und Austritt Prüfen, Vdg 015 Sachwalterfragen Vorbereiten: Vdg 011 Beweismittel Offenlegung Nutzen; Vdg 012 Kommunikation An Verbraucher; Vd... |
| `vdg-energiepreiserhoehung-vdg-energiepreiserhoehung-vdg` | Vdg 043 Energiepreiserhoehung Anspruchsgruppen, Vdg 044 Energiepreiserhoehung Registertext Sch, Vdg 045 Energiepreiserhoehung Betroffenenformu, Vdg 046 Energiepreiserhoehung Beweisplan Erste: Vdg 043 Energiepreiserhoehung Anspruchsgruppe... |
| `vdg-energiepreiserhoehung-vdg-energiepreiserhoehung-vdg-02` | Vdg 047 Energiepreiserhoehung Vergleich Pruefe, Vdg 048 Energiepreiserhoehung Umsetzung Ueberw, Vdg 050 Energiepreiserhoehung Risiko Rot Marki, Vdg 051 Plattform Sperre Sammelfaehigkeit Prue: Vdg 047 Energiepreiserhoehung Vergleich Pruef... |
| `vdg-erfolgsmonitoring-bankentgelte-sammelfaehigkeit-klageschrift` | Vdg 020 Erfolgsmonitoring, Vdg 021 Bankentgelte Sammelfaehigkeit Prüfen, Vdg 022 Bankentgelte Klageschrift Strukturiere, Vdg 023 Bankentgelte Anspruchsgruppen Bilden: Vdg 020 Erfolgsmonitoring; Vdg 021 Bankentgelte Sammelfaehigkeit Prüfe... |
| `vdg-finanzierung-interessenkonflikte-verbandsklageregister` | Vdg 007 Finanzierung Und Interessenkonflikte, Vdg 008 Verbandsklageregister Vorbereiten, Vdg 009 Klageziele Praezise Schneiden, Vdg 010 Lebenssachverhalt Buendeln: Vdg 007 Finanzierung Und Interessenkonflikte; Vdg 008 Verbandsklageregist... |
| `vdg-fitnessstudio-registertext-betroffenenformular-baue` | Vdg 074 Fitnessstudio Registertext Schreiben, Vdg 075 Fitnessstudio Betroffenenformular Baue, Vdg 076 Fitnessstudio Beweisplan Erstellen, Vdg 077 Fitnessstudio Vergleich Prüfen: Vdg 074 Fitnessstudio Registertext Schreiben; Vdg 075 Fitne... |
| `vdg-fitnessstudio-umsetzung-risiko-rot-reiseveranstalter` | Vdg 078 Fitnessstudio Umsetzung Ueberwachen, Vdg 080 Fitnessstudio Risiko Rot Markieren, Vdg 081 Reiseveranstalter Sammelfaehigkeit Pru, Vdg 082 Reiseveranstalter Klageschrift Struktu: Vdg 078 Fitnessstudio Umsetzung Ueberwachen; Vdg 080... |
| `vdg-fitnessstudio-vdg-reiseveranstalter-vdg-flugportal-vdg` | Vdg 079 Fitnessstudio Kommunikation Steuern, Vdg 089 Reiseveranstalter Kommunikation Steuer, Vdg 099 Flugportal Kommunikation Steuern, Vdg 002 Klageberechtigung Der Stelle Prüfen: Vdg 079 Fitnessstudio Kommunikation Steuern; Vdg 089 Reis... |
| `vdg-flugportal-beweisplan-umsetzung-ueberwachen` | Vdg 096 Flugportal Beweisplan Erstellen, Vdg 097 Flugportal Vergleich Prüfen, Vdg 098 Flugportal Umsetzung Ueberwachen, Vdg 101 Bankentgelte Zustimmungsfiktion Serie: Vdg 096 Flugportal Beweisplan Erstellen; Vdg 097 Flugportal Vergleich... |
| `vdg-flugportal-klageschrift-anspruchsgruppen-bilden-registertext` | Vdg 092 Flugportal Klageschrift Strukturieren, Vdg 093 Flugportal Anspruchsgruppen Bilden, Vdg 094 Flugportal Registertext Schreiben, Vdg 095 Flugportal Betroffenenformular Bauen: Vdg 092 Flugportal Klageschrift Strukturieren; Vdg 093 Fl... |
| `vdg-individualklagen-vdg-presse-vdg-datenschutz-vdg-kosten` | Vdg 016 Individualklagen Koordinieren, Vdg 017 Presse Und Kampagnenrisiko, Vdg 018 Datenschutz Im Betroffenenpool, Vdg 019 Kosten Und Prozessrisiko: Vdg 016 Individualklagen Koordinieren; Vdg 017 Presse Und Kampagnenrisiko; Vdg 018 Daten... |
| `vdg-inkasso-vdg-bestellbutton-vdg-probeabo-vdg-schufa` | Vdg 102 Inkasso Konzerninkasso Musterfeststellung, Vdg 103 Bestellbutton Uklag Uwg Abmahnung, Vdg 104 Probeabo Widerruf Verbandsstrategie, Vdg 105 Schufa Scoring Dsgvo Verbandsfall: Vdg 102 Inkasso Konzerninkasso Musterfeststellung; Vdg... |
| `vdg-plattform-sperre-anspruchsgruppen-bild-registertext-schreibe` | Vdg 052 Plattform Sperre Klageschrift Struktur, Vdg 053 Plattform Sperre Anspruchsgruppen Bild, Vdg 054 Plattform Sperre Registertext Schreibe, Vdg 055 Plattform Sperre Betroffenenformular B: Vdg 052 Plattform Sperre Klageschrift Struktu... |
| `vdg-plattform-sperre-umsetzung-ueberwachen-risiko-rot` | Vdg 056 Plattform Sperre Beweisplan Erstellen, Vdg 057 Plattform Sperre Vergleich Prüfen, Vdg 058 Plattform Sperre Umsetzung Ueberwachen, Vdg 060 Plattform Sperre Risiko Rot Markieren: Vdg 056 Plattform Sperre Beweisplan Erstellen; Vdg 0... |
| `vdg-reiseveranstalter-vdg-reiseveranstalter-vdg` | Vdg 083 Reiseveranstalter Anspruchsgruppen Bil, Vdg 084 Reiseveranstalter Registertext Schreib, Vdg 085 Reiseveranstalter Betroffenenformular, Vdg 086 Reiseveranstalter Beweisplan Erstellen: Vdg 083 Reiseveranstalter Anspruchsgruppen Bil... |
| `vdg-reiseveranstalter-vdg-reiseveranstalter-vdg-02` | Vdg 087 Reiseveranstalter Vergleich Prüfen, Vdg 088 Reiseveranstalter Umsetzung Ueberwache, Vdg 090 Reiseveranstalter Risiko Rot Markieren, Vdg 091 Flugportal Sammelfaehigkeit Prüfen: Vdg 087 Reiseveranstalter Vergleich Prüfen; Vdg 088 R... |
| `vdg-telekommunikationsklausel-registertext-betroffenenf-pr` | Vdg 034 Telekommunikationsklausel Registertext, Vdg 035 Telekommunikationsklausel Betroffenenf, Vdg 036 Telekommunikationsklausel Beweisplan E, Vdg 037 Telekommunikationsklausel Vergleich Pr: Vdg 034 Telekommunikationsklausel Registertex... |
| `vdg-telekommunikationsklausel-umsetzung-kommunikatio-risiko-rot` | Vdg 038 Telekommunikationsklausel Umsetzung Ue, Vdg 039 Telekommunikationsklausel Kommunikatio, Vdg 040 Telekommunikationsklausel Risiko Rot M, Vdg 106 Diesel Differenzschaden Serienfall: Vdg 038 Telekommunikationsklausel Umsetzung Ue; V... |
| `vdg-umsetzungsverfahren-vdg-telekommunikationsklausel-vdg` | Vdg 014 Umsetzungsverfahren Planen, Vdg 031 Telekommunikationsklausel Sammelfaehig, Vdg 032 Telekommunikationsklausel Klageschrift, Vdg 033 Telekommunikationsklausel Anspruchsgru: Vdg 014 Umsetzungsverfahren Planen; Vdg 031 Telekommunika... |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
