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
| `alternativen-keine-aufgabe-kompetenz` | Nkr Alternativen Prüfung Keine Regelung Soft Law, Nkr Aufgabe Und Kompetenz Nkrg: Nkr Alternativen Prüfung Keine Regelung Soft Law; Nkr Aufgabe Und Kompetenz Nkrg. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuste... |
| `buerokratieabbau-katalog-buerokratiekosten-vs` | Nkr Buerokratieabbau Katalog Konkrete Vorschlaege, Nkr Buerokratiekosten Vs Erfuellungsaufwand: Nkr Buerokratieabbau Katalog Konkrete Vorschlaege; Nkr Buerokratiekosten Vs Erfuellungsaufwand. Führt Intake, Prüfroutine, Normen-/Quellenrad... |
| `einmalig-vs-erforderlichkeitspruefung-warum` | Nkr Einmalig Vs Jaehrlich Laufend, Nkr Erforderlichkeitspruefung Warum Ueberhaupt Regeln: Nkr Einmalig Vs Jaehrlich Laufend; Nkr Erforderlichkeitspruefung Warum Ueberhaupt Regeln. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislo... |
| `erfuellungsaufwand-buerger-erfuellungsaufwand-grundbegriff` | Nkr Erfuellungsaufwand Buerger Wirtschaft Verwaltung, Nkr Erfuellungsaufwand Grundbegriff: Nkr Erfuellungsaufwand Buerger Wirtschaft Verwaltung; Nkr Erfuellungsaufwand Grundbegriff. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweis... |
| `eu-ebene-eu-richtlinien` | Nkr Eu Ebene Und Better Regulation, Nkr Eu Richtlinien Umsetzung Und Goldplating: Nkr Eu Ebene Und Better Regulation; Nkr Eu Richtlinien Umsetzung Und Goldplating. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuste... |
| `evaluation-jahresbericht-fallzahlen-schaetzung` | Nkr Evaluation Und Jahresbericht, Nkr Fallzahlen Schaetzung Bandbreiten: Nkr Evaluation Und Jahresbericht; Nkr Fallzahlen Schaetzung Bandbreiten. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätsche... |
| `evaluierung-befristung-verfahrensgang-referentenentwurf` | Nkr Evaluierung Befristung Sunset Klausel, Nkr Verfahrensgang Referentenentwurf Bis Bundestag: Nkr Evaluierung Befristung Sunset Klausel; Nkr Verfahrensgang Referentenentwurf Bis Bundestag. Führt Intake, Prüfroutine, Normen-/Quellenradar... |
| `gleichstellungs-gendercheck-handelsregister-elektronische` | Nkr Gleichstellungs Und Gendercheck, Nkr Handelsregister Und Elektronische Zustellung: Nkr Gleichstellungs Und Gendercheck; Nkr Handelsregister Und Elektronische Zustellung. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, O... |
| `leitfaden-ermittlung-mittelstandsfreundlichkeit-kmu` | Nkr Leitfaden Ermittlung Und Darstellung, Nkr Mittelstandsfreundlichkeit Kmu Test: Nkr Leitfaden Ermittlung Und Darstellung; Nkr Mittelstandsfreundlichkeit Kmu Test. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmus... |
| `nachhaltigkeit-klimacheck-one-one` | Nkr Nachhaltigkeit Klimacheck Und Vereinbarkeit, Nkr One In One Out Bilanz Und Buchung: Nkr Nachhaltigkeit Klimacheck Und Vereinbarkeit; Nkr One In One Out Bilanz Und Buchung. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik,... |
| `nkr-digital-anschlussfaehigkeit-digitalcheck-onlinezugangsgesetz` | Nkr Digital Anschlussfaehigkeit Tauglich, Nkr Digitalcheck Und Onlinezugangsgesetz Ozg: Nkr Digital Anschlussfaehigkeit Tauglich; Nkr Digitalcheck Und Onlinezugangsgesetz Ozg. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik,... |
| `nkr-stellungnahme-grundsatzfeststellung-mahnender-charakter` | Nkr Stellungnahme Grundsatzfeststellung, Nkr Stellungnahme Mahnender Charakter Grenzen: Nkr Stellungnahme Grundsatzfeststellung; Nkr Stellungnahme Mahnender Charakter Grenzen. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik,... |
| `orientierung-mandatsaufnahme-praktikabilitaet-vollzug` | Nkr Orientierung Und Mandatsaufnahme, Nkr Praktikabilitaet Vollzug Test: Nkr Orientierung Und Mandatsaufnahme; Nkr Praktikabilitaet Vollzug Test. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätsche... |
| `pruefumfang-was-standardkostenmodell-skm` | Nkr Pruefumfang Was Prueft Der Nkr Nicht, Nkr Standardkostenmodell Skm: Nkr Pruefumfang Was Prueft Der Nkr Nicht; Nkr Standardkostenmodell Skm. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck... |
| `stellungnahme-aufbau-stellungnahme-ergebnis` | Nkr Stellungnahme Aufbau Und Format, Nkr Stellungnahme Ergebnis Und Empfehlung: Nkr Stellungnahme Aufbau Und Format; Nkr Stellungnahme Ergebnis Und Empfehlung. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster un... |
| `stellungnahme-evaluationsklausel-stellungnahme` | Nkr Stellungnahme Evaluationsklausel Vorschlag, Nkr Stellungnahme Formulierungshilfe Vs Referentenentwurf: Nkr Stellungnahme Evaluationsklausel Vorschlag; Nkr Stellungnahme Formulierungshilfe Vs Referentenentwurf. Führt Intake, Prüfrouti... |
| `stellungnahme-pressepolitik-stellungnahme-bundestag` | Nkr Stellungnahme Pressepolitik Und Jahresbericht, Nkr Stellungnahme Zum Bundestag Anhoerung: Nkr Stellungnahme Pressepolitik Und Jahresbericht; Nkr Stellungnahme Zum Bundestag Anhoerung. Führt Intake, Prüfroutine, Normen-/Quellenradar,... |
| `verhaeltnismaessigkeit-sicht-zeitwerttabelle-fallzahlen` | Nkr Verhaeltnismaessigkeit Aus Nkr Sicht, Nkr Zeitwerttabelle Und Fallzahlen: Nkr Verhaeltnismaessigkeit Aus Nkr Sicht; Nkr Zeitwerttabelle Und Fallzahlen. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qu... |
| `zusammenarbeit-bundesregierung` | Nkr Zusammenarbeit Mit Bundesregierung Und Ressorts: Nkr Zusammenarbeit Mit Bundesregierung Und Ressorts. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zusammen. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
