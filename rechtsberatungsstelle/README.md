# Plugin für die studentische Rechtsberatungsstelle

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`rechtsberatungsstelle`) | [`rechtsberatungsstelle.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/rechtsberatungsstelle.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **Rechtsberatungsstelle Köln-Kalk — Monatsmix August 2026, Dr. Pellbach-Tannenfels** (`rechtsberatungsstelle-koeln-quartier-kalk-q3-2026-monatsmix-pellbach`) | [Gesamt-PDF lesen](../testakten/rechtsberatungsstelle-koeln-quartier-kalk-q3-2026-monatsmix-pellbach/gesamt-pdf/rechtsberatungsstelle-koeln-quartier-kalk-q3-2026-monatsmix-pellbach_gesamt.pdf) | [`testakte-rechtsberatungsstelle-koeln-quartier-kalk-q3-2026-monatsmix-pellbach.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-rechtsberatungsstelle-koeln-quartier-kalk-q3-2026-monatsmix-pellbach.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

*KI-gestützte Unterstützung für universitäre Refugee Law Clinics, studentische Rechtsberatungen und Pro-Bono-Initiativen – mit klaren RDG-Grenzen.*

Ein Plugin für Einrichtungen, in denen Studierende – unter Anleitung zur Anleitung berechtigter Volljuristen – unentgeltliche Rechtsberatung für Menschen leisten, die sich anwaltliche Hilfe nicht leisten können oder keinen Zugang dazu haben: Aufenthalts- und Asylrecht, Sozialrecht (SGB II/XII, SGB IX), Mietrecht, Verbraucherrecht, Familienrecht.

**Jede Ausgabe ist ein Entwurf für die Analyse durch Studierende und die Freigabe durch den anleitenden Volljuristen – gekennzeichnet, gestuft und protokolliert. Das Plugin gibt Struktur; die Studierenden denken juristisch; der Anleiter prüft und gibt frei. Nichts verlässt die Beratungsstelle ohne Durchlaufen dieses Aufsichtsmodells.**

---

## Wichtiger Hinweis: Rechtliche Grenzen nach dem RDG

> **Diese Beratungsstelle erbringt Rechtsdienstleistungen ausschließlich im Rahmen von § 6 Abs. 2 Nr. 2 RDG (unentgeltliche Rechtsdienstleistungen durch Volljuristen anleitungsberechtigt) oder § 8 RDG (Verbraucherzentralen, Sozialberatung). Jede entgeltliche Rechtsdienstleistung durch Nicht-Zugelassene ist nach § 3 RDG untersagt und nach § 20 RDG bußgeldbewehrt.**

**Für Studierende gilt:**
- Rechtliche Auskünfte dürfen nur unter Anleitung und Aufsicht eines zur Anleitung berechtigten Volljuristen erteilt werden (§ 6 Abs. 2 Nr. 2 RDG).
- Schriftsätze, Stellungnahmen und Widersprüche sind **Entwürfe** – keine fertigen, abzusendenden Dokumente.
- Jede strategische Entscheidung (Klage ja/nein, Rücknahme, Vergleich) liegt beim anleitenden Anwalt.
- Das Mandat liegt formal beim Anleiter, nicht beim Studierenden.
- Verschwiegenheit nach § 43a Abs. 2 BRAO analog, § 203 StGB – auch nach Semesterende.

---

## Das Problem, das dieses Plugin löst

Beratungsstellen sind strukturell kapazitätsbeschränkt. Ein anleitender Jurist betreut 5–12 Studierende. Jede Studierende trägt eine Handvoll Mandate, während sie gleichzeitig Lehrveranstaltungen besucht. Studierende wechseln jedes Semester. Verwaltungsaufgaben – Intake-Protokoll, Erstentwürfe, Rechercheansätze, Statusberichte, Semesterübergaben – verschlingen Stunden, die besser in die juristische Analyse investiert wären. Das Ergebnis: lange Wartelisten, begrenzte Fallzahlen, Ratsuchende, die aufgeben.

Dieses Plugin senkt die Zeitkosten für alles **rund um die Rechtsarbeit**, damit dieselben Studierenden und ihr Anleiter deutlich mehr Mandanten sinnvoll betreuen können – und die Studierenden mehr Zeit für Analyse und Strategie haben, die das Kernanliegen studentischer Rechtsbildung ausmacht.

**Es beschleunigt die nicht-lehrenden Teile. Es bewahrt die analytische Arbeit.** Das ist das Gestaltungsprinzip.

---

## Wer nutzt das Plugin?

| Rolle | Startet | Erhält |
|---|---|---|
| **Anleitender Volljurist** | `/kaltstart-interview` (einmalig), `/anleiter-pruefwarteschlange` (wenn formelle Prüfung aktiviert) | Konfigurierter Beratungsstellenkontext, Prüfung studentischer Arbeit |
| **Studierende** | `/einarbeitung` (Semesterbeginn), dann `/mandant-aufnahme`, `/entwurf`, `/memo`, `/recherche-start`, `/status`, `/mandantenbrief` | Strukturierte Arbeitshilfen, Entwürfe, Rechercheeinstiege |
| **Mandant** | – | Empfängt fertig geprüfte Briefe (Studierender + Anleiter haben freigegeben) |

---

## Schnellstart

```
/rechtsberatungsstelle:rechtsberatungsstelle-kaltstart-interview   # Anleiter: Beratungsstelle konfigurieren
/rechtsberatungsstelle:einarbeitung                   # Studierender: Einarbeitung zum Semesterbeginn
/rechtsberatungsstelle:mandant-aufnahme          # Neues Mandat aufnehmen
/rechtsberatungsstelle:memo                   # Gutachtenstil-Memo erstellen
/rechtsberatungsstelle:entwurf                  # Schriftsatz entwerfen
/rechtsberatungsstelle:fristen              # Fristen prüfen
/rechtsberatungsstelle:mandantenbrief          # Mandantenbrief in einfacher Sprache
/rechtsberatungsstelle:semester-uebergabe       # Semesterübergabe vorbereiten
```

---

## Beratungsstellentypen, die dieses Plugin unterstützt

### Universitäre Refugee Law Clinics (RLC)

Hochschulverankerte Kliniken wie die **Refugee Law Clinic Berlin** (HU Berlin/FU Berlin), die **Refugee Law Clinic Bremen** (Universität Bremen) oder die **Refugee Law Clinic Köln** (Universität zu Köln) beraten Asylsuchende und Geduldete zu Fragen des AsylG, AufenthG und SGB II. Besonderheiten:
- Kurze Fristen (§§ 36, 74 AsylG): Klagen gegen BAMF-Bescheide oft binnen 1–2 Wochen nach Zustellung.
- Sprachbarrieren: Dolmetscher-Koordination ist Teil des Intakes.
- Schnittstellen zu § 76b SGB IX (Eingliederungshilfe für Geflüchtete).

### Studentische Rechtsberatung nach § 6 Abs. 2 Nr. 2 RDG

Allgemeine studentische Beratungsstellen an Universitäten (oft "JuRI", "Jura hilft" o. ä.). Fokus: SGB II (Bürgergeld), Mietrecht, Verbraucherrecht, Familienrecht. Betrieb ausschließlich unter Aufsicht zugelassener Anwälte oder habilitierter Volljuristen.

### AnwVer/DAV Pro-Bono-Initiativen

Anwaltsverein-getragene Pro-Bono-Programme (z. B. **Pro Bono Berlin e. V.**, **DAV Pro Bono**): hier beraten zugelassene Anwälte direkt, die Plugin-Komponenten `entwurf`, `memo` und `recherche-start` unterstützen die Mandatsarbeit.

### Verbraucherzentralen (§ 8 RDG)

Verbraucherzentralen besitzen eine Sondererlaubnis nach § 8 Abs. 1 Nr. 4 RDG. Das Plugin unterstützt Standardfälle: Mieterhöhung, Kündigung, AGB-Kontrolle (§§ 305 ff. BGB), Energiekosten-Nachforderungen.

### Sozialberatung

Anerkannte Beratungsträger (AWO, Caritas, Diakonie, DRK, Paritätischer) arbeiten nach § 8 Abs. 1 Nr. 4 RDG. Schwerpunkte: SGB II, SGB XII, SGB IX, Rentenrecht (§ 109 SGB VI), Pflegegeld (§ 76b SGB IX).

---

## Beispiele: Pro-Bono-Initiativen in Berlin und Bremen

| Initiative | Ort | Schwerpunkt | Rechtsgrundlage |
|---|---|---|---|
| Refugee Law Clinic Berlin (HU/FU) | Berlin | AsylG, AufenthG, SGB II | § 6 II Nr. 2 RDG |
| Pro Bono Berlin e. V. | Berlin | Zivilrecht, Mietrecht, Familienrecht | Zugelassene Anwälte |
| Berliner Mieterverein – Rechtsberatung | Berlin | Mietrecht | § 8 I Nr. 3 RDG (Verband) |
| Refugee Law Clinic Bremen | Bremen | AsylG, AufenthG | § 6 II Nr. 2 RDG |
| Verbraucherzentrale Bremen | Bremen | Verbraucherrecht, Mietrecht | § 8 I Nr. 4 RDG |
| JuRI – Juristische Interessenvertretung (Uni Bremen) | Bremen | SGB II, allg. Zivilrecht | § 6 II Nr. 2 RDG |
| Caritas Berlin – Migrationsberatung | Berlin | AufenthG, SGB II | § 8 I Nr. 4 RDG |

---

## Fachbereiche und Skills

| Skill | Zweck | Primäre Normen |
|---|---|---|
| `leitfaden-erstellen` | Leitfaden zum Aufbau einer Beratungsstelle | RDG, BRAO |
| `mandanten-kommunikations-log` | Mandantenkommunikations-Logbuch | § 43a BRAO, § 203 StGB |
| `mandant-aufnahme` | Intake mit RDG-Konfliktprüfung | § 6 II Nr. 2 RDG |
| `mandantenbrief` | Mandantenbrief in einfacher Sprache | BORA |
| `rechtsberatungsstelle-kaltstart-interview` | Ersteinrichtung der Beratungsstelle | RDG, BRAO |
| `rechtsberatungsstelle-anpassen` | Beratungsstellenprofil anpassen | – |
| `fristen` | Fristenkontrolle | § 84 SGG, § 74 VwGO, §§ 36, 74 AsylG |
| `entwurf` | Schriftsatzentwurf | ZPO, VwGO, SGG |
| `formular-erzeugung` | Formularerstellung (PKH, BerHG, KSchG) | §§ 114 ff. ZPO, BerHG |
| `memo` | Memo im Gutachtenstil | – |
| `einfache-sprache-briefe` | Einfache Sprache | BORA |
| `einarbeitung` | Einarbeitung Studierende | § 6 II Nr. 2 RDG |
| `recherche-start` | Rechercheeinstieg | juris, Beck-Online, gesetze-im-internet.de |
| `semester-uebergabe` | Semesterübergabe | – |
| `status` | Statusbericht | – |
| `anleiter-pruefwarteschlange` | Aufsichts-Reviewqueue | § 6 II Nr. 2 RDG, § 43a BRAO |

---

## Qualitätssicherung

Alle studentischen Outputs tragen den Vermerk:

> **[KI-GESTÜTZTER ENTWURF – Analyse durch Studierende und Freigabe durch anleitenden Volljuristen erforderlich. Kein Versand ohne Prüfung.]**

Nur der anleitende Jurist kann diesen Vermerk entfernen. Dokumente, die diesen Vermerk tragen, dürfen nicht unmittelbar an Mandanten oder Behörden gesendet werden.

---

## Zitierweise

Alle juristischen Quellen folgen `../references/zitierweise.md`. Beispiele:
- Rechtsprechung: keine Entscheidung aus Modellwissen zitieren; vor Ausgabe über offizielle oder frei zugängliche Quelle mit Gericht, Entscheidungsform, Datum, Aktenzeichen und tragender Aussage verifizieren.
- Krenzler, in: Krenzler (Hrsg.), RDG, 2. Aufl. 2021, § 6 Rn. 45.


<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 25 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `anlaufstellen-beweislast-anleiter-bono` | Nutze dies, wenn Spezial Anlaufstellen Beweislast Und Darlegungslast, Spezial Anleiter Formular Portal Und Einreichung, Spezial Bono Erstpruefung Und Mandatsziel im Plugin Rechtsberatungsstelle konkret bearbeitet werden soll. Auslöser: B... |
| `anleiter-pruefwarteschlange` | 'Supervisoren-Prüfwarteschlange — studentische Arbeitsergebnisse warten hier auf die Supervisoren-Freigabe, bevor sie an Mandanten oder Gerichte gehen. Nur aktiv, wenn das Supervisionsmodell 'formelle Prüfwarteschlange' gewählt wurde; an... |
| `anschluss-router` | Nutze dies, wenn Allgemein, Workflow Anschluss Skills Router, Workflow Chronologie Und Belegmatrix im Plugin Rechtsberatungsstelle konkret bearbeitet werden soll. Auslöser: Bitte Allgemein, Workflow Anschluss Skills Router, Workflow Chro... |
| `briefe-erstberatung-rdg-konform` | Nutze dies, wenn Spezial Briefe Zahlen Schwellen Und Berechnung, Spezial Erstberatung Rdg Grenzen Und Triage, Spezial Konform Dokumentenmatrix Und Lueckenliste im Plugin Rechtsberatungsstelle konkret bearbeitet werden soll. Auslöser: Bit... |
| `dokumente-intake` | Nutze dies, wenn Dokumentenintake im Plugin Rechtsberatungsstelle konkret bearbeitet werden soll. Auslöser: Ich lade Unterlagen hoch.; Was fehlt noch?; Bitte Dokumente sortieren.. |
| `einstieg-routing` | Nutze dies, wenn Einstieg und Routing im Plugin Rechtsberatungsstelle konkret bearbeitet werden soll. Auslöser: Ich habe ein neues Thema im Bereich Rechtsberatungsstelle.; Welche Unterlagen brauchen Sie?; Welcher Spezialskill passt?. |
| `entwurf-einarbeitung-einfache-sprache` | Nutze dies, wenn Entwurf, Einarbeitung, Einfache Sprache Briefe im Plugin Rechtsberatungsstelle konkret bearbeitet werden soll. Auslöser: Bitte Entwurf, Einarbeitung, Einfache Sprache Briefe prüfen.; Erstelle eine Arbeitsfassung zu Entwu... |
| `erzeugung-leitfaden-erstellen-mandanten` | Nutze dies, wenn Formular Erzeugung, Leitfaden Erstellen, Mandanten Kommunikations Log im Plugin Rechtsberatungsstelle konkret bearbeitet werden soll. Auslöser: Bitte Formular Erzeugung, Leitfaden Erstellen, Mandanten Kommunikations Log... |
| `fristen-fristenkontrolle-rdg` | Nutze dies, wenn Fristen, Spezial Fristenkontrolle Behörden Gericht Und Registerweg, Spezial Rdg Fristen Form Und Zustaendigkeit im Plugin Rechtsberatungsstelle konkret bearbeitet werden soll. Auslöser: Bitte Fristen, Spezial Fristenkont... |
| `fristen-risikoampel-mandantenkommunikation` | Nutze dies, wenn Workflow Fristen Und Risikoampel, Workflow Mandantenkommunikation, Workflow Redteam Qualitygate im Plugin Rechtsberatungsstelle konkret bearbeitet werden soll. Auslöser: Was kann hier schiefgehen?; Bitte red-team prüfen.... |
| `mandant-aufnahme` | Mandantenaufnahme in der Rechtsberatungsstelle strukturieren: Anwendungsfall Student nimmt erstmals Mandanten auf und muss Sachverhalt strukturiert erfassen Rechtsgebiet einordnen und naechste Schritte bestimmen. BeratungsHiG § 2 Beratun... |
| `mandantenbrief-memo-rbs-beratungshilfe` | Nutze dies, wenn Mandantenbrief, Memo, Rbs Beratungshilfe Und Pkh Praxis im Plugin Rechtsberatungsstelle konkret bearbeitet werden soll. Auslöser: Bitte Mandantenbrief, Memo, Rbs Beratungshilfe Und Pkh Praxis prüfen.; Erstelle eine Arbei... |
| `mandantenfreundliche-quellenkarte-check` | Nutze dies, wenn Mandantenfreundliche Quellenkarte Check im Plugin Rechtsberatungsstelle konkret bearbeitet werden soll. Auslöser: Welche amtliche Quelle prüfe ich zuerst?; Gibt es aktuelle Rechtsprechung?; Bitte Fundstellen verifizieren.. |
| `mandantenintake-mandatsuebergabe` | Nutze dies, wenn Spezial Mandantenintake Risikoampel Und Gegenargumente, Spezial Mandatsuebergabe International Schnittstellen, Spezial Pro Bono Mandatsuebergabe im Plugin Rechtsberatungsstelle konkret bearbeitet werden soll. Auslöser: I... |
| `output-waehlen` | Nutze dies, wenn Output wählen im Plugin Rechtsberatungsstelle konkret bearbeitet werden soll. Auslöser: Bitte Output wählen prüfen.; Erstelle eine Arbeitsfassung zu Output wählen.; Welche Normen und Nachweise brauche ich?. |
| `pruefwarteschlange-red-rbst-recherche` | Nutze dies, wenn Spezial Pruefwarteschlange Red Team Und Qualitaetskontrolle, Spezial Rbst Mandantenkommunikation Entscheidungsvorlage, Spezial Recherche Mehrparteien Konflikt Und Interessen im Plugin Rechtsberatungsstelle konkret bearbe... |
| `quellen-livecheck` | Nutze dies, wenn Rechtsquellen-Livecheck im Plugin Rechtsberatungsstelle konkret bearbeitet werden soll. Auslöser: Welche amtliche Quelle prüfe ich zuerst?; Gibt es aktuelle Rechtsprechung?; Bitte Fundstellen verifizieren.. |
| `rbs-einfuehrung-rbs-rdg-rbst-anlaufstellen` | Nutze dies, wenn Rbs Einfuehrung Themen, Rbs Rdg Grenzen Spezial, Rbst Anlaufstellen Bauleiter im Plugin Rechtsberatungsstelle konkret bearbeitet werden soll. Auslöser: Bitte Rbs Einfuehrung Themen, Rbs Rdg Grenzen Spezial, Rbst Anlaufst... |
| `rbst-beratungshilfe-prozesskostenhilfe` | Nutze dies, wenn Rbst Beratungshilfe Prozesskostenhilfe Leitfaden, Rbst Niedrigschwellige Onlineberatung Spezial, Rbst Rdg Grenzen Spezial im Plugin Rechtsberatungsstelle konkret bearbeitet werden soll. Auslöser: Bitte Rbst Beratungshilf... |
| `recherche-start-rechtsberatungsstelle` | Nutze dies, wenn Recherche Start, Rechtsberatungsstelle Anpassen, Semester Übergabe im Plugin Rechtsberatungsstelle konkret bearbeitet werden soll. Auslöser: Bitte Recherche Start, Rechtsberatungsstelle Anpassen, Semester Übergabe prüfen... |
| `rechtsberatungsstelle-kaltstart-interview` | Rechtsberatungsstelle Kaltstart und Erst-Konfiguration: Anwendungsfall neue Rechtsberatungsstelle oder neues Semester startet und Plugin muss mit Rechtsgebieten Hochschule Anleiter und Beratungsregeln eingerichtet werden. BeratungsHiG §... |
| `rechtsberatungsstelle-rechtsberatungsstellen` | Nutze dies, wenn Spezial Rechtsberatungsstelle Compliance Dokumentation Und Akte, Spezial Rechtsberatungsstellen Tatbestand Beweis Und Belege, Spezial Semesterende Verhandlung Vergleich Und Eskalation im Plugin Rechtsberatungsstelle konk... |
| `sonderfall-edge-case` | Nutze dies, wenn Kaltstart: Sonderfall und Edge-Case-Prüfung im Plugin Rechtsberatungsstelle konkret bearbeitet werden soll. Auslöser: Ich habe ein neues Thema im Bereich Rechtsberatungsstelle.; Welche Unterlagen brauchen Sie?; Welcher S... |
| `status` | Nutze dies, wenn Spezial Übergabe Schriftsatz Brief Und Memo Bausteine, Status im Plugin Rechtsberatungsstelle konkret bearbeitet werden soll. Auslöser: Bitte Spezial Übergabe Schriftsatz Brief Und Memo Bausteine, Status prüfen.; Erstell... |
| `unterlagen-luecken` | Nutze dies, wenn Unterlagen und Lücken im Plugin Rechtsberatungsstelle konkret bearbeitet werden soll. Auslöser: Ich lade Unterlagen hoch.; Was fehlt noch?; Bitte Dokumente sortieren.. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
