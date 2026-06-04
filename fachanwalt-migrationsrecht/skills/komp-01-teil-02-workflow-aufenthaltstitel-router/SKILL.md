---
name: komp-01-teil-02-workflow-aufenthaltstitel-router
description: "fachanwalt-migrationsrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Aufenthaltstitel Router, Ausweisung Start, Behoerdenkommunikation, Bescheid Verstehen und 1 weitere Arbeitsmodule; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck."
---

# Arbeitsbereich - Aufenthaltstitel Router bis Blaue Karte Start

## Zweck

Dieser Skill ist ein eigenständiger Arbeitsbereich. Er verbindet mehrere sachlich benachbarte Arbeitsmodule. Wähle anhand des Sachverhalts das passende Modul, arbeite dessen Prüfroutine vollständig ab und kombiniere Module nur, wenn der Fall tatsächlich mehrere Themen berührt.

## Arbeitsmodule

| Arbeitsmodul | Fokus |
| --- | --- |
| `workflow-aufenthaltstitel-router` | Aufenthaltstitel-Router: Workflow-Skill für Migrationsrecht; wählt Visum, Aufenthaltserlaubnis, Blaue Karte, ICT, Chancenkarte, NE, Daueraufenthalt; mit Statusmatrix, Fristenrettung, Staatenbezug, Quellencheck und nutzbarem Output. |
| `workflow-ausweisung-start` | Ausweisung Start: Workflow-Skill für Migrationsrecht; prüft Ausweisungsinteresse, Bleibeinteresse, Verhältnismäßigkeit und EMRK; mit Statusmatrix, Fristenrettung, Staatenbezug, Quellencheck und nutzbarem Output. |
| `workflow-behoerdenkommunikation` | Behördenkommunikation: Workflow-Skill für Migrationsrecht; formuliert knappe Schreiben an ABH, BAMF, Botschaft oder Gericht; mit Statusmatrix, Fristenrettung, Staatenbezug, Quellencheck und nutzbarem Output. |
| `workflow-bescheid-verstehen` | Bescheid verstehen: Workflow-Skill für Migrationsrecht; erkennt aus Bescheid, Rechtsbehelfsbelehrung und Zustellung die nächsten Schritte; mit Statusmatrix, Fristenrettung, Staatenbezug, Quellencheck und nutzbarem Output. |
| `workflow-blaue-karte-start` | Blaue Karte EU Start: Workflow-Skill für Migrationsrecht; prüft Gehalt, Abschluss, Beruf, Arbeitgeber, Mobilität und Familiennachzug; mit Statusmatrix, Fristenrettung, Staatenbezug, Quellencheck und nutzbarem Output. |

## Arbeitsregel

1. Zuerst das passende Arbeitsmodul oder Sachthema auswählen.
2. Danach die dortige Prüfroutine, Normen-/Quellenanker, Beweislogik und Output-Vorgabe vollständig anwenden.
3. Bei mehreren passenden Arbeitsmodulen eine kurze Synopse bilden, Überschneidungen offen markieren und nichts vermischen, was getrennte Fristen, Zuständigkeiten, Anspruchsgrundlagen oder Beweislasten hat.
4. Rechtsprechung, Literatur, Behördenpraxis und Tagesrecht nur mit überprüfbarer Quelle oder Nutzerquelle ausgeben.

## Arbeitsmodule im Detail

## 1. `workflow-aufenthaltstitel-router`

**Fokus:** Aufenthaltstitel-Router: Workflow-Skill für Migrationsrecht; wählt Visum, Aufenthaltserlaubnis, Blaue Karte, ICT, Chancenkarte, NE, Daueraufenthalt; mit Statusmatrix, Fristenrettung, Staatenbezug, Quellencheck und nutzbarem Output.

# Aufenthaltstitel-Router

## Aufgabe
Workflow-Skill im Plugin `fachanwalt-migrationsrecht`. Schwerpunkt: wählt Visum, Aufenthaltserlaubnis, Blaue Karte, ICT, Chancenkarte, NE, Daueraufenthalt.

## Kaltstart
Wenn Unterlagen vorhanden sind, zuerst auswerten. Frage nur, was die nächste Weiche verändert:
1. Rolle, Ziel und gewünschte Sprache der Erklärung.
2. Staatsangehörigkeit, Herkunfts-/Transitstaaten, aktueller Aufenthaltsort und Status.
3. Frist, Zustellung, Termin, Ablaufdatum oder Abschiebungsrisiko.
4. Vorhandene Dokumente und fehlende Nachweise.
5. Gewünschter Output: einfache Erklärung, spanische Zusammenfassung, Antrag, Klage/Eilantrag, Behördenmail, Arbeitgebermemo oder Dokumentenliste.

## Arbeitsworkflow
1. **Statusmatrix:** Person, Staat/Gebiet, Dokumente, Aufenthaltsort, aktueller Status, Zielstatus.
2. **Frist sichern:** Klage/Eilantrag, Dublin/GEAS, Fiktionswirkung, Visumtermin, Ausreisefrist, Abschiebung.
3. **Rechtsgrundlage:** AufenthG, AsylG, StAG, FreizügG/EU, EU-Recht, GFK/EMRK und Verwaltungspraxis live prüfen.
4. **Staatenbezug:** Bei Herkunfts-, Transit- oder Zielstaat passenden `staat-...-migrationscheck` ergänzen.
5. **Belege:** Dokumente, Urkunden, Übersetzungen, Atteste, Arbeitsvertrag, Abschluss, Behördenpost in eine Lückenliste bringen.
6. **Output:** Risikoampel, nächste Schritte, Entwurf und Anschluss-Skills.

## Spanisch bei Bedarf
Erkläre zusätzlich auf Spanisch: `Situación`, `Plazo`, `Riesgo`, `Documentos necesarios`, `Próximo paso`. Normen bleiben deutsch mit kurzer Erklärung.

## Quellen- und Sicherheitsregel
- Vor tragenden Aussagen den aktuellen Normtext und die aktuelle Behörden-/Gerichtspraxis prüfen; keine Scheingenauigkeit aus Modellwissen.
- Rechtsprechung nur mit Gericht, Entscheidungsform, Datum, Aktenzeichen und frei prüfbarer Quelle ausgeben.
- Keine BeckRS-, juris-, Kommentar-, Handbuch- oder Aufsatz-Blindzitate aus Modellwissen.
- Annahmen, fehlende Unterlagen, Beweisrisiken und Fristen ausdrücklich markieren.

## 2. `workflow-ausweisung-start`

**Fokus:** Ausweisung Start: Workflow-Skill für Migrationsrecht; prüft Ausweisungsinteresse, Bleibeinteresse, Verhältnismäßigkeit und EMRK; mit Statusmatrix, Fristenrettung, Staatenbezug, Quellencheck und nutzbarem Output.

# Ausweisung Start

## Aufgabe
Workflow-Skill im Plugin `fachanwalt-migrationsrecht`. Schwerpunkt: prüft Ausweisungsinteresse, Bleibeinteresse, Verhältnismäßigkeit und EMRK.

## Kaltstart
Wenn Unterlagen vorhanden sind, zuerst auswerten. Frage nur, was die nächste Weiche verändert:
1. Rolle, Ziel und gewünschte Sprache der Erklärung.
2. Staatsangehörigkeit, Herkunfts-/Transitstaaten, aktueller Aufenthaltsort und Status.
3. Frist, Zustellung, Termin, Ablaufdatum oder Abschiebungsrisiko.
4. Vorhandene Dokumente und fehlende Nachweise.
5. Gewünschter Output: einfache Erklärung, spanische Zusammenfassung, Antrag, Klage/Eilantrag, Behördenmail, Arbeitgebermemo oder Dokumentenliste.

## Arbeitsworkflow
1. **Statusmatrix:** Person, Staat/Gebiet, Dokumente, Aufenthaltsort, aktueller Status, Zielstatus.
2. **Frist sichern:** Klage/Eilantrag, Dublin/GEAS, Fiktionswirkung, Visumtermin, Ausreisefrist, Abschiebung.
3. **Rechtsgrundlage:** AufenthG, AsylG, StAG, FreizügG/EU, EU-Recht, GFK/EMRK und Verwaltungspraxis live prüfen.
4. **Staatenbezug:** Bei Herkunfts-, Transit- oder Zielstaat passenden `staat-...-migrationscheck` ergänzen.
5. **Belege:** Dokumente, Urkunden, Übersetzungen, Atteste, Arbeitsvertrag, Abschluss, Behördenpost in eine Lückenliste bringen.
6. **Output:** Risikoampel, nächste Schritte, Entwurf und Anschluss-Skills.

## Spanisch bei Bedarf
Erkläre zusätzlich auf Spanisch: `Situación`, `Plazo`, `Riesgo`, `Documentos necesarios`, `Próximo paso`. Normen bleiben deutsch mit kurzer Erklärung.

## Quellen- und Sicherheitsregel
- Vor tragenden Aussagen den aktuellen Normtext und die aktuelle Behörden-/Gerichtspraxis prüfen; keine Scheingenauigkeit aus Modellwissen.
- Rechtsprechung nur mit Gericht, Entscheidungsform, Datum, Aktenzeichen und frei prüfbarer Quelle ausgeben.
- Keine BeckRS-, juris-, Kommentar-, Handbuch- oder Aufsatz-Blindzitate aus Modellwissen.
- Annahmen, fehlende Unterlagen, Beweisrisiken und Fristen ausdrücklich markieren.

## 3. `workflow-behoerdenkommunikation`

**Fokus:** Behördenkommunikation: Workflow-Skill für Migrationsrecht; formuliert knappe Schreiben an ABH, BAMF, Botschaft oder Gericht; mit Statusmatrix, Fristenrettung, Staatenbezug, Quellencheck und nutzbarem Output.

# Behördenkommunikation

## Aufgabe
Workflow-Skill im Plugin `fachanwalt-migrationsrecht`. Schwerpunkt: formuliert knappe Schreiben an ABH, BAMF, Botschaft oder Gericht.

## Kaltstart
Wenn Unterlagen vorhanden sind, zuerst auswerten. Frage nur, was die nächste Weiche verändert:
1. Rolle, Ziel und gewünschte Sprache der Erklärung.
2. Staatsangehörigkeit, Herkunfts-/Transitstaaten, aktueller Aufenthaltsort und Status.
3. Frist, Zustellung, Termin, Ablaufdatum oder Abschiebungsrisiko.
4. Vorhandene Dokumente und fehlende Nachweise.
5. Gewünschter Output: einfache Erklärung, spanische Zusammenfassung, Antrag, Klage/Eilantrag, Behördenmail, Arbeitgebermemo oder Dokumentenliste.

## Arbeitsworkflow
1. **Statusmatrix:** Person, Staat/Gebiet, Dokumente, Aufenthaltsort, aktueller Status, Zielstatus.
2. **Frist sichern:** Klage/Eilantrag, Dublin/GEAS, Fiktionswirkung, Visumtermin, Ausreisefrist, Abschiebung.
3. **Rechtsgrundlage:** AufenthG, AsylG, StAG, FreizügG/EU, EU-Recht, GFK/EMRK und Verwaltungspraxis live prüfen.
4. **Staatenbezug:** Bei Herkunfts-, Transit- oder Zielstaat passenden `staat-...-migrationscheck` ergänzen.
5. **Belege:** Dokumente, Urkunden, Übersetzungen, Atteste, Arbeitsvertrag, Abschluss, Behördenpost in eine Lückenliste bringen.
6. **Output:** Risikoampel, nächste Schritte, Entwurf und Anschluss-Skills.

## Spanisch bei Bedarf
Erkläre zusätzlich auf Spanisch: `Situación`, `Plazo`, `Riesgo`, `Documentos necesarios`, `Próximo paso`. Normen bleiben deutsch mit kurzer Erklärung.

## Quellen- und Sicherheitsregel
- Vor tragenden Aussagen den aktuellen Normtext und die aktuelle Behörden-/Gerichtspraxis prüfen; keine Scheingenauigkeit aus Modellwissen.
- Rechtsprechung nur mit Gericht, Entscheidungsform, Datum, Aktenzeichen und frei prüfbarer Quelle ausgeben.
- Keine BeckRS-, juris-, Kommentar-, Handbuch- oder Aufsatz-Blindzitate aus Modellwissen.
- Annahmen, fehlende Unterlagen, Beweisrisiken und Fristen ausdrücklich markieren.

## 4. `workflow-bescheid-verstehen`

**Fokus:** Bescheid verstehen: Workflow-Skill für Migrationsrecht; erkennt aus Bescheid, Rechtsbehelfsbelehrung und Zustellung die nächsten Schritte; mit Statusmatrix, Fristenrettung, Staatenbezug, Quellencheck und nutzbarem Output.

# Bescheid verstehen

## Aufgabe
Workflow-Skill im Plugin `fachanwalt-migrationsrecht`. Schwerpunkt: erkennt aus Bescheid, Rechtsbehelfsbelehrung und Zustellung die nächsten Schritte.

## Kaltstart
Wenn Unterlagen vorhanden sind, zuerst auswerten. Frage nur, was die nächste Weiche verändert:
1. Rolle, Ziel und gewünschte Sprache der Erklärung.
2. Staatsangehörigkeit, Herkunfts-/Transitstaaten, aktueller Aufenthaltsort und Status.
3. Frist, Zustellung, Termin, Ablaufdatum oder Abschiebungsrisiko.
4. Vorhandene Dokumente und fehlende Nachweise.
5. Gewünschter Output: einfache Erklärung, spanische Zusammenfassung, Antrag, Klage/Eilantrag, Behördenmail, Arbeitgebermemo oder Dokumentenliste.

## Arbeitsworkflow
1. **Statusmatrix:** Person, Staat/Gebiet, Dokumente, Aufenthaltsort, aktueller Status, Zielstatus.
2. **Frist sichern:** Klage/Eilantrag, Dublin/GEAS, Fiktionswirkung, Visumtermin, Ausreisefrist, Abschiebung.
3. **Rechtsgrundlage:** AufenthG, AsylG, StAG, FreizügG/EU, EU-Recht, GFK/EMRK und Verwaltungspraxis live prüfen.
4. **Staatenbezug:** Bei Herkunfts-, Transit- oder Zielstaat passenden `staat-...-migrationscheck` ergänzen.
5. **Belege:** Dokumente, Urkunden, Übersetzungen, Atteste, Arbeitsvertrag, Abschluss, Behördenpost in eine Lückenliste bringen.
6. **Output:** Risikoampel, nächste Schritte, Entwurf und Anschluss-Skills.

## Bescheid-Anatomie Migrationsrecht

- **Bezeichnung:** BAMF-Bescheid (Asyl), Ausländerbehörde (Aufenthalt), Botschaft (Visum), Bundesverwaltungsamt (Einbürgerung).
- **Tenor:** Ablehnung gesondert prüfen — als offensichtlich unbegründet (§ 30 AsylG) löst Wochen-Frist aus (§ 36 AsylG); als einfach unbegründet 2-Wochen-Frist (§ 74 AsylG).
- **Rechtsbehelfsbelehrung:** Fehler oder fehlende RBB → 1-Jahres-Frist (§ 58 Abs. 2 VwGO); ABER Asyl-Sondervorschriften haben oft kürzere Fristen unabhängig (§ 74 AsylG, § 36 AsylG).
- **Zustellung:** Datum maßgeblich nicht Bescheiddatum; Postzustellungsurkunde bzw. Zustellung an Bevollmächtigten (Vollmacht!) prüfen — § 41 VwVfG/§ 31 AsylG, § 7 VwZG.
- **Abschiebungsandrohung:** Im Asylbescheid regelmäßig mit Ausreisefrist (i. d. R. 30 Tage, bei offensichtlich unbegründet 1 Woche, § 36 AsylG).
- **Sofortvollzug § 80 Abs. 2 VwGO:** Bei Asyl-Bescheiden kraft Gesetzes; Eilantrag § 80 Abs. 5 VwGO i. V. m. § 36 Abs. 3 AsylG bzw. § 34a Abs. 2 AsylG.
- **Einreise- und Aufenthaltsverbot § 11 AufenthG:** Befristung beachten — Antrag auf Verkürzung möglich.

## Spanisch bei Bedarf
Erkläre zusätzlich auf Spanisch: `Situación`, `Plazo`, `Riesgo`, `Documentos necesarios`, `Próximo paso`. Normen bleiben deutsch mit kurzer Erklärung.

## Quellen- und Sicherheitsregel
- Vor tragenden Aussagen den aktuellen Normtext und die aktuelle Behörden-/Gerichtspraxis prüfen; keine Scheingenauigkeit aus Modellwissen.
- Rechtsprechung nur mit Gericht, Entscheidungsform, Datum, Aktenzeichen und frei prüfbarer Quelle ausgeben.
- Keine BeckRS-, juris-, Kommentar-, Handbuch- oder Aufsatz-Blindzitate aus Modellwissen.
- Annahmen, fehlende Unterlagen, Beweisrisiken und Fristen ausdrücklich markieren.

## 5. `workflow-blaue-karte-start`

**Fokus:** Blaue Karte EU Start: Workflow-Skill für Migrationsrecht; prüft Gehalt, Abschluss, Beruf, Arbeitgeber, Mobilität und Familiennachzug; mit Statusmatrix, Fristenrettung, Staatenbezug, Quellencheck und nutzbarem Output.

# Blaue Karte EU Start

## Aufgabe
Workflow-Skill im Plugin `fachanwalt-migrationsrecht`. Schwerpunkt: prüft Gehalt, Abschluss, Beruf, Arbeitgeber, Mobilität und Familiennachzug.

## Kaltstart
Wenn Unterlagen vorhanden sind, zuerst auswerten. Frage nur, was die nächste Weiche verändert:
1. Rolle, Ziel und gewünschte Sprache der Erklärung.
2. Staatsangehörigkeit, Herkunfts-/Transitstaaten, aktueller Aufenthaltsort und Status.
3. Frist, Zustellung, Termin, Ablaufdatum oder Abschiebungsrisiko.
4. Vorhandene Dokumente und fehlende Nachweise.
5. Gewünschter Output: einfache Erklärung, spanische Zusammenfassung, Antrag, Klage/Eilantrag, Behördenmail, Arbeitgebermemo oder Dokumentenliste.

## Arbeitsworkflow
1. **Statusmatrix:** Person, Staat/Gebiet, Dokumente, Aufenthaltsort, aktueller Status, Zielstatus.
2. **Frist sichern:** Klage/Eilantrag, Dublin/GEAS, Fiktionswirkung, Visumtermin, Ausreisefrist, Abschiebung.
3. **Rechtsgrundlage:** AufenthG, AsylG, StAG, FreizügG/EU, EU-Recht, GFK/EMRK und Verwaltungspraxis live prüfen.
4. **Staatenbezug:** Bei Herkunfts-, Transit- oder Zielstaat passenden `staat-...-migrationscheck` ergänzen.
5. **Belege:** Dokumente, Urkunden, Übersetzungen, Atteste, Arbeitsvertrag, Abschluss, Behördenpost in eine Lückenliste bringen.
6. **Output:** Risikoampel, nächste Schritte, Entwurf und Anschluss-Skills.

## Spanisch bei Bedarf
Erkläre zusätzlich auf Spanisch: `Situación`, `Plazo`, `Riesgo`, `Documentos necesarios`, `Próximo paso`. Normen bleiben deutsch mit kurzer Erklärung.

## Quellen- und Sicherheitsregel
- Vor tragenden Aussagen den aktuellen Normtext und die aktuelle Behörden-/Gerichtspraxis prüfen; keine Scheingenauigkeit aus Modellwissen.
- Rechtsprechung nur mit Gericht, Entscheidungsform, Datum, Aktenzeichen und frei prüfbarer Quelle ausgeben.
- Keine BeckRS-, juris-, Kommentar-, Handbuch- oder Aufsatz-Blindzitate aus Modellwissen.
- Annahmen, fehlende Unterlagen, Beweisrisiken und Fristen ausdrücklich markieren.
