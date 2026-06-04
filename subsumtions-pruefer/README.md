# Subsumtions-Prüfer

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`subsumtions-pruefer`) | [`subsumtions-pruefer.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/subsumtions-pruefer.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **Subsumtionskontrolle / Klausurkorrektur — Übung für Fortgeschrittene BGB, Uni Bielefeld, Lehrstuhl Pohlmann-Wittfeldt, SS 2026** (`subsumtions-klausurkorrekt-bgb-fall-fortgeschrittene-uni-bielefeld-pohlmann-eichmann`) | [Gesamt-PDF lesen](../testakten/subsumtions-klausurkorrekt-bgb-fall-fortgeschrittene-uni-bielefeld-pohlmann-eichmann/gesamt-pdf/subsumtions-klausurkorrekt-bgb-fall-fortgeschrittene-uni-bielefeld-pohlmann-eichmann_gesamt.pdf) | [`testakte-subsumtions-klausurkorrekt-bgb-fall-fortgeschrittene-uni-bielefeld-pohlmann-eichmann.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-subsumtions-klausurkorrekt-bgb-fall-fortgeschrittene-uni-bielefeld-pohlmann-eichmann.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

Interaktiver Mechanik-Workflow für die juristische Subsumtion nach deutschem Recht und Europarecht. Das Plugin zerlegt Normen in Tatbestandsmerkmale, führt das Vier-Schritt-Schema (Obersatz – Definition – Untersatz – Ergebnis) durch, erfasst Beweisbedarf und erzeugt Ausgabedokumente in verschiedenen Formaten.

**Dieses Plugin ist keine Rechtsberatung.** Es prüft mechanisch eine vom Nutzer behauptete Norm anhand vom Nutzer behaupteter Tatsachen. Die Auswahl der richtigen Norm, die vollständige Sachverhaltsdarstellung und die Bewertung des Ergebnisses bleiben in der Verantwortung des Nutzers und eines zugelassenen Rechtsanwalts.

## Für wen ist dieses Plugin

| Rolle | Primäre Anwendungsfälle |
|---|---|
| Privatpersonen | Verstehen, ob ein Anspruch dem Grunde nach bestehen könnte |
| Paralegal / Rechtsfachwirt | Strukturierte Erstsichtung vor anwaltlicher Prüfung |
| Jurastudent / Referendar | Subsumtionsübung ohne Musterlösung |
| Unternehmensjurist | Schnelle Erstprüfung einer Norm vor Mandatserteilung |
| Behördenmitarbeiter | Strukturiertes Durchprüfen von Tatbestandsvoraussetzungen |

## Abgedeckte Rechtsgebiete

- **Deutsches Recht:** BGB (Schuld-, Sachen-, Familien-, Erbrecht), HGB, StGB, StPO, ZPO, VwGO, VwVfG, GG, AO, SGB, KSchG, AGG, GWB, UWG und Nebengesetze
- **BGB AT:** Für Vertragsschluss, Willenserklärung, Zugang, Geschäftsfähigkeit, Form, Anfechtung, Stellvertretung, Fristen und Verjährung sollte `bgb-at-pruefer` vor oder neben diesem generischen Subsumtions-Plugin geladen werden.
- **Europarecht:** AEUV, EUV, GRCh (Primärrecht); DSGVO, KI-VO, Produkthaftungsrichtlinie, Verbraucherrechterichtlinie, Vergaberichtlinien u. a. (Sekundärrecht); EuGH-Judikatur

## Workflow-Überblick

```
Einstieg
│
├─ triage-rechtsfrage-oder-norm
│   Sachverhalt / Rechtsfrage / Norm erfassen
│
├─ ziel-und-rechtsweg-bestimmung
│   Was will der Nutzer? Welches Gericht?
│
├─ falsche-wiese-warnung
│   Fehlverortungen erkennen
│
├─ de-eu-recht-abgrenzung
│   Welches Recht gilt?
│
Normbestimmung
│
├─ einschlaegige-normen-vorschlagen-de / -eu
├─ norm-historie-und-aenderungen
├─ rechtsprechung-recherche-strategie
│
Subsumtion
│
├─ norm-zerlegen-in-tatbestandsmerkmale
├─ ungeschriebene-merkmale-judikatur
├─ generalklauseln-pruefen
├─ unbestimmte-rechtsbegriffe-pruefen
├─ subsumtion-obersatz-definition-untersatz-ergebnis
├─ beweisbedarf-und-belege-erfassen
├─ darlegungs-und-beweislast-verteilen
├─ gegen-tbm-und-einreden-pruefen
│
Rechtsfolgen
│
├─ rechtsfolge-bestimmen
├─ konkurrenzen-anspruchsgrundlagen
├─ verjaehrung-fristen-pruefen
├─ verfahrensart-bestimmen
├─ eu-vorabentscheidung-pruefen
├─ grundrechte-pruefung-de-und-grch
│
Ausgabe (wählbar)
│
├─ output-juristisch-gestochen-de
├─ output-alltagssprache-de
├─ output-fremdsprachig-en-fr
├─ output-antrag-beschwerde-klageschrift
├─ output-memo-und-mandantenbrief
└─ output-pruefungsdokument-mit-warnhinweisen
```

## Wichtige Warnhinweise

Das System warnt aktiv in folgenden Situationen:

- **Falsche Norm:** Sachverhalt passt nicht zur gewählten Norm (`falsche-wiese-warnung`)
- **Komplexitätsgrenze:** Sachverhalt zu komplex für mechanische Prüfung (`mandatsabbruch-empfehlung-an-fachanwalt`)
- **Generalklauseln:** Kein mechanisch abschließbares Ergebnis möglich (`generalklauseln-pruefen`)
- **Unbestimmte Rechtsbegriffe:** Nur Indiziensammlung, keine Subsumtion (`unbestimmte-rechtsbegriffe-pruefen`)
- **Offene TBM:** Fehlende Belege gefährden das Ergebnis (`beweisbedarf-und-belege-erfassen`)

## Skills (31)

### A. Triage / Workflow-Einstieg

| Skill | Funktion |
|---|---|
| `triage-rechtsfrage-oder-norm` | Interaktive Erfassung der Nutzereingabe |
| `ziel-und-rechtsweg-bestimmung` | Ziel und Rechtsweg ermitteln |
| `falsche-wiese-warnung` | Typische Fehlverortungen erkennen |
| `de-eu-recht-abgrenzung` | Nationales vs. Unionsrecht abgrenzen |
| `mandatsabbruch-empfehlung-an-fachanwalt` | Komplexitätsgrenze erkennen, Fachanwalt empfehlen |

### B. Normbestimmung und Recherche

| Skill | Funktion |
|---|---|
| `einschlaegige-normen-vorschlagen-de` | Deutsche Normen anhand Sachverhalt vorschlagen |
| `einschlaegige-normen-vorschlagen-eu` | EU-Normen anhand Sachverhalt vorschlagen |
| `rechtsprechung-recherche-strategie` | Recherche-Strategie und Fundstellen |
| `norm-historie-und-aenderungen` | Geltende Fassung und Übergangsrecht |
| `kommentar-und-literatur-hinweis` | Standardkommentare und Literaturhinweise |

### C. Tatbestandsmerkmale und Subsumtion

| Skill | Funktion |
|---|---|
| `norm-zerlegen-in-tatbestandsmerkmale` | TBM-Liste mit Definitionen |
| `ungeschriebene-merkmale-judikatur` | Richterrechtlich entwickelte Merkmale |
| `generalklauseln-pruefen` | Generalklauseln — Indizien und Fallgruppen |
| `unbestimmte-rechtsbegriffe-pruefen` | Auslegungsmaßstäbe für unbestimmte Begriffe |
| `subsumtion-obersatz-definition-untersatz-ergebnis` | Vier-Schritt-Schema je TBM |
| `beweisbedarf-und-belege-erfassen` | Beweismittel-Katalog und Tracking |
| `darlegungs-und-beweislast-verteilen` | Beweislast pro TBM |
| `gegen-tbm-und-einreden-pruefen` | Einwendungen und Einreden |

### D. Rechtsfolgen, Konkurrenzen, Verfahren

| Skill | Funktion |
|---|---|
| `rechtsfolge-bestimmen` | Anspruchsinhalt, Höhe, Nebenansprüche |
| `konkurrenzen-anspruchsgrundlagen` | Normkonkurrenzen und Spezialität |
| `verjaehrung-fristen-pruefen` | Verjährung, Hemmung, Neubeginn |
| `verfahrensart-bestimmen` | Passende Verfahrensart und Zuständigkeit |
| `eu-vorabentscheidung-pruefen` | Art. 267 AEUV — Voraussetzungen |
| `grundrechte-pruefung-de-und-grch` | GG und GRCh — Drei-Schritt-Schema |

### E. Output-Erzeugung

| Skill | Funktion |
|---|---|
| `output-juristisch-gestochen-de` | Schriftsatzstil, Rubrum, Tenor |
| `output-alltagssprache-de` | Verständliche Sprache für Betroffene |
| `output-fremdsprachig-en-fr` | Englisch und Französisch (nicht-amtlich) |
| `output-antrag-beschwerde-klageschrift` | Formale Dokument-Bausteine |
| `output-memo-und-mandantenbrief` | Aktennotiz und Mandantenbrief |
| `output-pruefungsdokument-mit-warnhinweisen` | Vollständiges Dokument mit allen Warnhinweisen |

## Lizenz

Apache-2.0 OR MIT — siehe LICENSE im Repository-Root.


<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 53 Skills in diesem Plugin. Beschreibungen stehen in der jeweiligen SKILL.md; diese Kurzliste dient als schneller Slug-Index.

| Skill | Beschreibung |
| --- | --- |
| `allgemein` | Fachskill in diesem Plugin; Details in `skills/allgemein/SKILL.md`. |
| `beweisbedarf-und-belege-erfassen` | Fachskill in diesem Plugin; Details in `skills/beweisbedarf-und-belege-erfassen/SKILL.md`. |
| `darlegungs-und-beweislast-verteilen` | Fachskill in diesem Plugin; Details in `skills/darlegungs-und-beweislast-verteilen/SKILL.md`. |
| `de-eu-recht-abgrenzung` | Fachskill in diesem Plugin; Details in `skills/de-eu-recht-abgrenzung/SKILL.md`. |
| `einschlaegige-normen-vorschlagen-de` | Fachskill in diesem Plugin; Details in `skills/einschlaegige-normen-vorschlagen-de/SKILL.md`. |
| `einschlaegige-normen-vorschlagen-eu` | Fachskill in diesem Plugin; Details in `skills/einschlaegige-normen-vorschlagen-eu/SKILL.md`. |
| `eu-vorabentscheidung-pruefen` | Fachskill in diesem Plugin; Details in `skills/eu-vorabentscheidung-pruefen/SKILL.md`. |
| `falsche-wiese-warnung` | Fachskill in diesem Plugin; Details in `skills/falsche-wiese-warnung/SKILL.md`. |
| `fehlerklasse-bgb-at-training` | Fachskill in diesem Plugin; Details in `skills/fehlerklasse-bgb-at-training/SKILL.md`. |
| `gegen-tbm-und-einreden-pruefen` | Fachskill in diesem Plugin; Details in `skills/gegen-tbm-und-einreden-pruefen/SKILL.md`. |
| `generalklauseln-pruefen` | Fachskill in diesem Plugin; Details in `skills/generalklauseln-pruefen/SKILL.md`. |
| `grundrechte-pruefung-de-und-grch` | Fachskill in diesem Plugin; Details in `skills/grundrechte-pruefung-de-und-grch/SKILL.md`. |
| `kandidatenloesung-subsumtion-pruefen` | Fachskill in diesem Plugin; Details in `skills/kandidatenloesung-subsumtion-pruefen/SKILL.md`. |
| `kommentar-und-literatur-hinweis` | Fachskill in diesem Plugin; Details in `skills/kommentar-und-literatur-hinweis/SKILL.md`. |
| `konkurrenzen-anspruchsgrundlagen` | Fachskill in diesem Plugin; Details in `skills/konkurrenzen-anspruchsgrundlagen/SKILL.md`. |
| `mandatsabbruch-empfehlung-an-fachanwalt` | Fachskill in diesem Plugin; Details in `skills/mandatsabbruch-empfehlung-an-fachanwalt/SKILL.md`. |
| `norm-historie-und-aenderungen` | Fachskill in diesem Plugin; Details in `skills/norm-historie-und-aenderungen/SKILL.md`. |
| `norm-zerlegen-in-tatbestandsmerkmale` | Fachskill in diesem Plugin; Details in `skills/norm-zerlegen-in-tatbestandsmerkmale/SKILL.md`. |
| `output-alltagssprache-de` | Fachskill in diesem Plugin; Details in `skills/output-alltagssprache-de/SKILL.md`. |
| `output-antrag-beschwerde-klageschrift` | Fachskill in diesem Plugin; Details in `skills/output-antrag-beschwerde-klageschrift/SKILL.md`. |
| `output-fremdsprachig-en-fr` | Fachskill in diesem Plugin; Details in `skills/output-fremdsprachig-en-fr/SKILL.md`. |
| `output-juristisch-gestochen-de` | Fachskill in diesem Plugin; Details in `skills/output-juristisch-gestochen-de/SKILL.md`. |
| `output-memo-und-mandantenbrief` | Fachskill in diesem Plugin; Details in `skills/output-memo-und-mandantenbrief/SKILL.md`. |
| `output-pruefungsdokument-mit-warnhinweisen` | Fachskill in diesem Plugin; Details in `skills/output-pruefungsdokument-mit-warnhinweisen/SKILL.md`. |
| `rechtsfolge-bestimmen` | Fachskill in diesem Plugin; Details in `skills/rechtsfolge-bestimmen/SKILL.md`. |
| `rechtsprechung-recherche-strategie` | Fachskill in diesem Plugin; Details in `skills/rechtsprechung-recherche-strategie/SKILL.md`. |
| `spezial-anwenden-livequellen-und-rechtsprechungscheck` | Fachskill in diesem Plugin; Details in `skills/spezial-anwenden-livequellen-und-rechtsprechungscheck/SKILL.md`. |
| `spezial-einreden-compliance-dokumentation-und-akte` | Fachskill in diesem Plugin; Details in `skills/spezial-einreden-compliance-dokumentation-und-akte/SKILL.md`. |
| `spezial-europarecht-fristen-form-und-zustaendigkeit` | Fachskill in diesem Plugin; Details in `skills/spezial-europarecht-fristen-form-und-zustaendigkeit/SKILL.md`. |
| `spezial-interaktiver-erstpruefung-und-mandatsziel` | Fachskill in diesem Plugin; Details in `skills/spezial-interaktiver-erstpruefung-und-mandatsziel/SKILL.md`. |
| `spezial-pruefen-mehrparteien-konflikt-und-interessen` | Fachskill in diesem Plugin; Details in `skills/spezial-pruefen-mehrparteien-konflikt-und-interessen/SKILL.md`. |
| `spezial-rechtsberatung-internationaler-bezug-und-schnittstellen` | Fachskill in diesem Plugin; Details in `skills/spezial-rechtsberatung-internationaler-bezug-und-schnittstellen/SKILL.md`. |
| `spezial-rechtsfolgen-zahlen-schwellen-und-berechnung` | Fachskill in diesem Plugin; Details in `skills/spezial-rechtsfolgen-zahlen-schwellen-und-berechnung/SKILL.md`. |
| `spezial-schema-verhandlung-vergleich-und-eskalation` | Fachskill in diesem Plugin; Details in `skills/spezial-schema-verhandlung-vergleich-und-eskalation/SKILL.md`. |
| `spezial-schritt-schriftsatz-brief-und-memo-bausteine` | Fachskill in diesem Plugin; Details in `skills/spezial-schritt-schriftsatz-brief-und-memo-bausteine/SKILL.md`. |
| `spezial-subsumtions-tatbestand-beweis-und-belege` | Fachskill in diesem Plugin; Details in `skills/spezial-subsumtions-tatbestand-beweis-und-belege/SKILL.md`. |
| `spezial-tatbestandsmerkmale-dokumentenmatrix-und-lueckenliste` | Fachskill in diesem Plugin; Details in `skills/spezial-tatbestandsmerkmale-dokumentenmatrix-und-lueckenliste/SKILL.md`. |
| `spezial-vier-behoerden-gericht-und-registerweg` | Fachskill in diesem Plugin; Details in `skills/spezial-vier-behoerden-gericht-und-registerweg/SKILL.md`. |
| `spezial-zerlegen-risikoampel-und-gegenargumente` | Fachskill in diesem Plugin; Details in `skills/spezial-zerlegen-risikoampel-und-gegenargumente/SKILL.md`. |
| `subsumtion-obersatz-definition-untersatz-ergebnis` | Fachskill in diesem Plugin; Details in `skills/subsumtion-obersatz-definition-untersatz-ergebnis/SKILL.md`. |
| `subsumtions-rewrite-klausurton` | Fachskill in diesem Plugin; Details in `skills/subsumtions-rewrite-klausurton/SKILL.md`. |
| `triage-rechtsfrage-oder-norm` | Fachskill in diesem Plugin; Details in `skills/triage-rechtsfrage-oder-norm/SKILL.md`. |
| `unbestimmte-rechtsbegriffe-pruefen` | Fachskill in diesem Plugin; Details in `skills/unbestimmte-rechtsbegriffe-pruefen/SKILL.md`. |
| `ungeschriebene-merkmale-judikatur` | Fachskill in diesem Plugin; Details in `skills/ungeschriebene-merkmale-judikatur/SKILL.md`. |
| `verfahrensart-bestimmen` | Fachskill in diesem Plugin; Details in `skills/verfahrensart-bestimmen/SKILL.md`. |
| `verjaehrung-fristen-pruefen` | Fachskill in diesem Plugin; Details in `skills/verjaehrung-fristen-pruefen/SKILL.md`. |
| `workflow-chronologie-und-belegmatrix` | Fachskill in diesem Plugin; Details in `skills/workflow-chronologie-und-belegmatrix/SKILL.md`. |
| `workflow-dokumentenintake` | Fachskill in diesem Plugin; Details in `skills/workflow-dokumentenintake/SKILL.md`. |
| `workflow-fristen-und-risikoampel` | Fachskill in diesem Plugin; Details in `skills/workflow-fristen-und-risikoampel/SKILL.md`. |
| `workflow-kaltstart-und-routing` | Fachskill in diesem Plugin; Details in `skills/workflow-kaltstart-und-routing/SKILL.md`. |
| `workflow-output-waehlen` | Fachskill in diesem Plugin; Details in `skills/workflow-output-waehlen/SKILL.md`. |
| `workflow-unterlagen-lueckenliste` | Fachskill in diesem Plugin; Details in `skills/workflow-unterlagen-lueckenliste/SKILL.md`. |
| `ziel-und-rechtsweg-bestimmung` | Fachskill in diesem Plugin; Details in `skills/ziel-und-rechtsweg-bestimmung/SKILL.md`. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
