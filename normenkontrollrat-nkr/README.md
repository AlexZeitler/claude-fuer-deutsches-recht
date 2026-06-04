# Normenkontrollrat (NKR) — Pruefung von Gesetzentwuerfen

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`normenkontrollrat-nkr`) | [`normenkontrollrat-nkr.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/normenkontrollrat-nkr.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **Testakte NKR: Elektronische Erreichbarkeit von Handelsregister-Gesellschaften (ElErrHandRegG 2026)** (`nkr-elektronische-erreichbarkeit-handelsregister-gesellschaften-2026`) | [Gesamt-PDF lesen](../testakten/nkr-elektronische-erreichbarkeit-handelsregister-gesellschaften-2026/gesamt-pdf/nkr-elektronische-erreichbarkeit-handelsregister-gesellschaften-2026_gesamt.pdf) | [`testakte-nkr-elektronische-erreichbarkeit-handelsregister-gesellschaften-2026.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-nkr-elektronische-erreichbarkeit-handelsregister-gesellschaften-2026.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

Freistehendes Plugin fuer die Arbeit eines **Mitglieds oder Referenten / einer Referentin des Nationalen Normenkontrollrats (NKR)** nach dem Gesetz ueber die Einsetzung eines Nationalen Normenkontrollrats (**NKRG vom 14.08.2006, BGBl. I S. 1866**) in der jeweils geltenden Fassung.

Es bildet den vollstaendigen Pruefzyklus eines Vorhabens ab: von der **Eingangstriage** eines Referentenentwurfs ueber die **Erfuellungsaufwand-Berechnung** nach Standardkostenmodell (SKM) und die **Pruefraster** des NKR bis zur **Stellungnahme** nach § 6 NKRG.

## Mandatsperspektive

Das Plugin schreibt aus der Sicht des **NKR-Pruefers**, nicht aus Ressortsicht. Es geht **nicht** darum, einen Entwurf zu verteidigen, sondern darum, ihn nach den NKR-Kriterien zu pruefen und ggf. **kritisch zu kommentieren**.

Leitsatz: *"Wenn nicht noetig, dann nicht regeln; wenn noetig, dann so einfach, so digital, so mittelstandsfreundlich und so evaluationsfest wie moeglich."*

## Aufbau

Das Plugin enthaelt 37 Skills in fuenf Clustern:

```
A — Grundlagen, Verfahren, Mandat (7 Skills)
   nkr-orientierung-und-mandatsaufnahme
   nkr-aufgabe-und-kompetenz-nkrg
   nkr-pruefumfang-was-prueft-der-nkr-nicht
   nkr-verfahrensgang-referentenentwurf-bis-bundestag
   nkr-zusammenarbeit-mit-bundesregierung-und-ressorts
   nkr-eu-ebene-und-better-regulation
   nkr-evaluation-und-jahresbericht

B — Erfuellungsaufwand-Methodik (8 Skills)
   nkr-erfuellungsaufwand-grundbegriff
   nkr-erfuellungsaufwand-buerger-wirtschaft-verwaltung
   nkr-standardkostenmodell-skm
   nkr-zeitwerttabelle-und-fallzahlen
   nkr-einmalig-vs-jaehrlich-laufend
   nkr-buerokratiekosten-vs-erfuellungsaufwand
   nkr-fallzahlen-schaetzung-bandbreiten
   nkr-leitfaden-ermittlung-und-darstellung

C — Pruefraster (8 Skills)
   nkr-erforderlichkeitspruefung-warum-ueberhaupt-regeln
   nkr-alternativen-pruefung-keine-regelung-soft-law
   nkr-verhaeltnismaessigkeit-aus-nkr-sicht
   nkr-mittelstandsfreundlichkeit-kmu-test
   nkr-praktikabilitaet-vollzug-test
   nkr-evaluierung-befristung-sunset-klausel
   nkr-digital-anschlussfaehigkeit-tauglich
   nkr-one-in-one-out-bilanz-und-buchung

D — Stellungnahme-Drafting (8 Skills)
   nkr-stellungnahme-aufbau-und-format
   nkr-stellungnahme-grundsatzfeststellung
   nkr-stellungnahme-ergebnis-und-empfehlung
   nkr-stellungnahme-formulierungshilfe-vs-referentenentwurf
   nkr-stellungnahme-zum-bundestag-anhoerung
   nkr-stellungnahme-evaluationsklausel-vorschlag
   nkr-stellungnahme-mahnender-charakter-grenzen
   nkr-stellungnahme-pressepolitik-und-jahresbericht

E — Spezialfaelle / komplexe Themen (6 Skills)
   nkr-digitalcheck-und-onlinezugangsgesetz-ozg
   nkr-eu-richtlinien-umsetzung-und-goldplating
   nkr-handelsregister-und-elektronische-zustellung
   nkr-nachhaltigkeit-klimacheck-und-vereinbarkeit
   nkr-gleichstellungs-und-gendercheck
   nkr-buerokratieabbau-katalog-konkrete-vorschlaege
```

## Methodische Grundlagen (Pflicht-Bezugnahmen)

- **NKRG** vom 14.08.2006 (BGBl. I S. 1866) in der jeweils geltenden Fassung
- **GGO** insbesondere § 44 (Pruefung der Gesetzesfolgen) und § 45 (Erfuellungsaufwand-Darstellung)
- **Handbuch der Rechtsfoermlichkeit (HdR)** als Drafting-Grundlage
- **Leitfaden zur Ermittlung und Darstellung des Erfuellungsaufwands** (BMI / NKR)
- **Standardkostenmodell (SKM)** als NKR-Methodik
- **One-in-one-out-Regel** (Beschluss der Bundesregierung 2015)
- **Digitalcheck** (seit 2022)
- **OZG** und OZG-Folgeregulierung (Stand vom Anwender zu verifizieren)
- **EU Better Regulation** der EU-Kommission

## Testakte

Zu diesem Plugin existiert eine vollstaendige Beispielakte unter [`testakten/nkr-elektronische-erreichbarkeit-handelsregister-gesellschaften-2026/`](../testakten/nkr-elektronische-erreichbarkeit-handelsregister-gesellschaften-2026/).

**Sachverhalt**: Referentenentwurf des BMJ vom 14.04.2026 zur Verbesserung der elektronischen Erreichbarkeit im Handelsregister eingetragener Gesellschaften (**ElErrHandRegG**). NKR-Pruefung ergibt: Regelung ist erforderlich, Ausgestaltung jedoch zu komplex; geschaetzter Erfuellungsaufwand 320 Mio EUR jaehrlich fuer die Wirtschaft. Stellungnahme weist die Notwendigkeit positiv aus, kritisiert die konkrete Ausgestaltung und schlaegt eine zentrale Loesung vor.

Die Akte zeigt sowohl die **mahnende** als auch die **konstruktive** Funktion des NKR.

## Quellenhygiene

- Keine erfundenen NKR-Stellungnahme-Aktenzeichen oder Berichte aus Modellwissen.
- NKRG und methodische Grundlagen werden mit Norm und Stand zitiert; NKR-Jahresberichte allgemein als "NKR-Jahresbericht <Jahr>".
- Vor Ausgabe stets Live-Quellen pruefen: [www.normenkontrollrat.bund.de](https://www.normenkontrollrat.bund.de), BMI-Leitfaden, Bundesanzeiger.

## Installation

```
/plugin marketplace add Klotzkette/claude-fuer-deutsches-recht
/plugin install normenkontrollrat-nkr@claude-fuer-deutsches-recht
```

## Konversationsstil

Erste Antwort knapp. Maximal eine gezielte Rueckfrage zur Mandatsaufnahme. Sofort in den Pruefraster-Modus uebergehen und einen ersten Stellungnahme-Entwurf liefern, sobald Eckdaten vorliegen. Subsumtion und ausfuehrliche Begruendung nur dort, wo der Skill dies ausdruecklich vorsieht (Erforderlichkeit, Verhaeltnismaessigkeit, Alternativenpruefung).

## Verwandte Plugins

- [`legistik-werkstatt`](../legistik-werkstatt/) — Drafting-Werkstatt fuer Referenten- und Kabinettsentwuerfe (Ressortsicht; NKR ist der Pruefer dieser Entwuerfe).
- [`normenkontrolle-bauleitplanung`](../normenkontrolle-bauleitplanung/) — Anfechtung von Bauleitplaenen nach § 47 VwGO (begriffliche Verwandtschaft, nicht inhaltlich).
- [`buerokratieversteher-entbuerokratisierer`](../buerokratieversteher-entbuerokratisierer/) — operative Entbuerokratisierung in einzelnen Verfahren.


<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 19 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `kompendium-01-nkr-evaluierung-befr-bis-nkr-verfahrensgang-r` | normenkontrollrat-nkr: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Nkr Evaluierung Befristung Sunset Klausel, Nkr Verfahrensgang Referentenentwurf Bis Bundestag; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik,... |
| `kompendium-02-nkr-stellungnahme-ev-bis-nkr-stellungnahme-fo` | normenkontrollrat-nkr: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Nkr Stellungnahme Evaluationsklausel Vorschlag, Nkr Stellungnahme Formulierungshilfe Vs Referentenentwurf; mit Intake, Prüfroutine, Normen-/Quellenradar,... |
| `kompendium-03-nkr-alternativen-pru-bis-nkr-aufgabe-und-komp` | normenkontrollrat-nkr: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Nkr Alternativen Pruefung Keine Regelung Soft Law, Nkr Aufgabe Und Kompetenz Nkrg; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuste... |
| `kompendium-04-nkr-buerokratieabbau-bis-nkr-buerokratiekoste` | normenkontrollrat-nkr: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Nkr Buerokratieabbau Katalog Konkrete Vorschlaege, Nkr Buerokratiekosten Vs Erfuellungsaufwand; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik... |
| `kompendium-05-nkr-digital-anschlus-bis-nkr-digitalcheck-und` | normenkontrollrat-nkr: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Nkr Digital Anschlussfaehigkeit Tauglich, Nkr Digitalcheck Und Onlinezugangsgesetz Ozg; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Output... |
| `kompendium-06-nkr-einmalig-vs-jaeh-bis-nkr-erforderlichkeit` | normenkontrollrat-nkr: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Nkr Einmalig Vs Jaehrlich Laufend, Nkr Erforderlichkeitspruefung Warum Ueberhaupt Regeln; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outp... |
| `kompendium-07-nkr-erfuellungsaufwa-bis-nkr-erfuellungsaufwa` | normenkontrollrat-nkr: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Nkr Erfuellungsaufwand Buerger Wirtschaft Verwaltung, Nkr Erfuellungsaufwand Grundbegriff; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Out... |
| `kompendium-08-nkr-eu-ebene-und-bet-bis-nkr-eu-richtlinien-u` | normenkontrollrat-nkr: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Nkr Eu Ebene Und Better Regulation, Nkr Eu Richtlinien Umsetzung Und Goldplating; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster... |
| `kompendium-09-nkr-evaluation-und-j-bis-nkr-fallzahlen-schae` | normenkontrollrat-nkr: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Nkr Evaluation Und Jahresbericht, Nkr Fallzahlen Schaetzung Bandbreiten; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qual... |
| `kompendium-10-nkr-gleichstellungs-bis-nkr-handelsregister` | normenkontrollrat-nkr: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Nkr Gleichstellungs Und Gendercheck, Nkr Handelsregister Und Elektronische Zustellung; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputm... |
| `kompendium-11-nkr-leitfaden-ermitt-bis-nkr-mittelstandsfreu` | normenkontrollrat-nkr: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Nkr Leitfaden Ermittlung Und Darstellung, Nkr Mittelstandsfreundlichkeit Kmu Test; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuste... |
| `kompendium-12-nkr-nachhaltigkeit-k-bis-nkr-one-in-one-out-b` | normenkontrollrat-nkr: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Nkr Nachhaltigkeit Klimacheck Und Vereinbarkeit, Nkr One In One Out Bilanz Und Buchung; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Output... |
| `kompendium-13-nkr-orientierung-und-bis-nkr-praktikabilitaet` | normenkontrollrat-nkr: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Nkr Orientierung Und Mandatsaufnahme, Nkr Praktikabilitaet Vollzug Test; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qual... |
| `kompendium-14-nkr-pruefumfang-was-bis-nkr-standardkostenmo` | normenkontrollrat-nkr: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Nkr Pruefumfang Was Prueft Der Nkr Nicht, Nkr Standardkostenmodell Skm; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Quali... |
| `kompendium-15-nkr-stellungnahme-au-bis-nkr-stellungnahme-er` | normenkontrollrat-nkr: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Nkr Stellungnahme Aufbau Und Format, Nkr Stellungnahme Ergebnis Und Empfehlung; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster u... |
| `kompendium-16-nkr-stellungnahme-gr-bis-nkr-stellungnahme-ma` | normenkontrollrat-nkr: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Nkr Stellungnahme Grundsatzfeststellung, Nkr Stellungnahme Mahnender Charakter Grenzen; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Output... |
| `kompendium-17-nkr-stellungnahme-pr-bis-nkr-stellungnahme-zu` | normenkontrollrat-nkr: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Nkr Stellungnahme Pressepolitik Und Jahresbericht, Nkr Stellungnahme Zum Bundestag Anhoerung; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik,... |
| `kompendium-18-nkr-verhaeltnismaess-bis-nkr-zeitwerttabelle` | normenkontrollrat-nkr: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Nkr Verhaeltnismaessigkeit Aus Nkr Sicht, Nkr Zeitwerttabelle Und Fallzahlen; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und... |
| `kompendium-19-nkr-zusammenarbeit-m-bis-nkr-zusammenarbeit-m` | normenkontrollrat-nkr: eigenständiger Arbeits-Skill zu Nkr Zusammenarbeit Mit Bundesregierung Und Ressorts; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
