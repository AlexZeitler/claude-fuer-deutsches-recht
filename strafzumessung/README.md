# Strafzumessung

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`strafzumessung`) | [`strafzumessung.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/strafzumessung.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **Strafzumessung Bankert — Untreue, LG Frankfurt / BGH Revision** (`strafzumessung-vermoegensdelikt-bankert-frankfurt-untreue-haupt-und-revisionsverhandlung`) | [Gesamt-PDF lesen](../testakten/strafzumessung-vermoegensdelikt-bankert-frankfurt-untreue-haupt-und-revisionsverhandlung/gesamt-pdf/strafzumessung-vermoegensdelikt-bankert-frankfurt-untreue-haupt-und-revisionsverhandlung_gesamt.pdf) | [`testakte-strafzumessung-vermoegensdelikt-bankert-frankfurt-untreue-haupt-und-revisionsverhandlung.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-strafzumessung-vermoegensdelikt-bankert-frankfurt-untreue-haupt-und-revisionsverhandlung.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

Plugin für die **Strafzumessung nach deutschem Strafrecht** — vom Strafbefehl bis zur großen Strafkammer. Adressaten: Strafverteidiger und Staatsanwaltschaft.

## Worum geht es?

Strafzumessung ist die zentrale richterliche Aufgabe nach Schuldspruch: Bestimmung von Strafart und Strafhoehe innerhalb des gesetzlichen Strafrahmens auf Grundlage der **Schuld** (§ 46 Abs. 1 Satz 1 StGB), unter Beruecksichtigung der **praeventiven Wirkungen** (§ 46 Abs. 1 Satz 2 StGB), nach den **Strafzumessungstatsachen** des § 46 Abs. 2 StGB und unter Beachtung des **Doppelverwertungsverbots** (§ 46 Abs. 3 StGB).

Das Plugin deckt die Strafzumessung vom Strafbefehlsverfahren ueber die Hauptverhandlung bis zur Vollstreckung ab, inklusive Bewaehrung, Strafmilderung, Regelbeispielen, Gesamtstrafenbildung, Verstaendigung und Jugendstrafrecht.

## Schnellstart

1. Mit `orientierung-strafzumessung-triage` einsteigen.
2. Rolle (Strafverteidigung, Staatsanwaltschaft) und Verfahrensstadium (Strafbefehl, Anklage, Hauptverhandlung, Urteil, Berufung, nachtraegliche Gesamtstrafe) angeben.
3. Den vom Triage-Skill empfohlenen Spezial-Skill aktivieren.
4. Bei Bedarf parallel mit den Plugins `strafbefehl-verteidiger` oder `fachanwalt-strafrecht` arbeiten.

## Enthaltene Skills

### Block A — Orientierung und Grundlagen
- `orientierung-strafzumessung-triage` — Einstieg, Triage, Spezial-Skill-Routing.
- `paragraph-46-stgb-grundsatz-strafzumessung` — § 46 StGB, Schuld als Grundlage.
- `strafzumessungs-tatsachen-46-ii-stgb` — Katalog § 46 Abs. 2 StGB.
- `strafrahmen-und-strafzumessungsstufen` — Strafrahmen-Logik vor jeder Zumessung.

### Block B — Geldstrafe
- `geldstrafe-tagessatzanzahl-bestimmen` — § 40 Abs. 1 StGB, Tagessatzanzahl als Schuldgroesse.
- `tagessatzhoehe-40-ii-stgb-nettotagesverdienst` — § 40 Abs. 2 StGB, Nettoeinkommen / 30.
- `geldstrafe-vs-freiheitsstrafe-47-stgb` — Vorrang Geldstrafe; § 47 StGB.

### Block C — Freiheitsstrafe und Bewaehrung
- `freiheitsstrafe-strafmass-pruefen` — Konkrete Zumessung im Strafrahmen.
- `bewaehrung-56-stgb-positive-sozialprognose` — § 56 StGB.
- `bewaehrung-auflagen-und-weisungen-56b-c-stgb` — §§ 56b, 56c StGB.
- `bewaehrungswiderruf-56f-stgb` — § 56f StGB.
- `freiheitsstrafe-ohne-bewaehrung-vollstreckung` — U-Haft-Anrechnung § 51 StGB, Reststrafenaussetzung § 57 StGB.

### Block D — Strafmilderung und Schaerfung
- `strafmilderung-49-stgb-zwingend-fakultativ` — § 49 StGB.
- `minder-schwerer-fall-und-besonders-schwerer-fall` — Strafrahmen-Modifikation.
- `regelbeispiele-rechtsprechung` — § 243 StGB, § 263 Abs. 3 StGB u.a.
- `taeter-opfer-ausgleich-46a-stgb-und-schadenswiedergutmachung` — § 46a StGB; BGH 4 StR 232/25.

### Block E — Strafbefehl und kleine Verfahren
- `strafbefehl-strafzumessung-407-stpo` — Strafzumessung im Strafbefehl.
- `153a-stpo-einstellung-gegen-auflage` — Einstellung mit Auflage.

### Block F — Hauptverhandlung und Verstaendigung
- `verstaendigung-257c-stpo-strafzumessung` — § 257c StPO; BVerfG 2 BvR 2628/10; BGH 1 StR 525/11.
- `gestaendnis-und-strafmilderung` — Gestaendnis als Strafmilderungsgrund.
- `267-iii-stpo-begruendungsanforderungen-strafurteil` — Strafurteil-Begruendung.

### Block G — Gesamtstrafenbildung
- `gesamtstrafenbildung-53-54-stgb-erste-instanz` — §§ 53, 54 StGB.
- `nachtraegliche-gesamtstrafenbildung-55-stgb` — § 55 StGB, Zaesurwirkung, § 460 StPO.
- `haerteausgleich-bei-nachtraeglicher-gesamtstrafenbildung` — BGH-staendige Linie.

### Block H — Sonderfaelle
- `jgg-strafzumessung-jugendstrafe-erziehungsmassregeln` — JGG; § 105 JGG Heranwachsende.

## Querverweise zu anderen Plugins

- `strafbefehl-verteidiger` — Spezial-Plugin Strafbefehlsverfahren.
- `fachanwalt-strafrecht` — Strafrechts-Gesamtverteidigung, Plaedoyer, Revision.
- `verkehrsowi-verteidiger` — Verkehrs-OWi-Strafzumessung.
- `urteilsbauer-relationsmacher` — Urteilsverfassung.
- `subsumtions-pruefer` — vor Schuldspruch.

## Hinweise zur Anwendung

- **Quellenregel beachten**: Keine Kommentar-, Handbuch- oder Aufsatzfundstellen aus Modellwissen. Aktenzeichen vor Zitat in **dejure.org** oder **openjur.de** verifizieren. Lizenzierte Datenbanken nur bei vorhandenem Zugang.
- **Keine Praejudizienbindung** (Ausnahme § 31 BVerfGG). BGH-Linien sind argumentationsstuetzend, nicht bindend.
- **Mandantengeheimnis** wahren (§ 43a Abs. 2 BRAO; § 203 StGB).
- **Frueher BGH-Beschluss** zum TOA: BGH, Beschluss vom 20.11.2025 — 4 StR 232/25 (friedensstiftender kommunikativer Prozess).
- **BVerfG zur Verstaendigung**: 2 BvR 2628/10 vom 19.03.2013.
- **BGH-Belehrungspflicht**: 1 StR 525/11 vom 07.02.2012.

## Stand

- 05/2026.
- §§ 38 ff. StGB, §§ 407 ff. StPO, JGG, BtMG.
- Aktualitaetspruefung jaehrlich empfohlen.

## Lizenz

Apache-2.0 OR MIT (siehe Plugin-Root).


<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 24 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `153a-stpo-iii-stpo-bewaehrung-stgb` | 153A Stpo Einstellung Gegen Auflage, 267 Iii Stpo Begruendungsanforderungen Strafurteil, Bewaehrung 56 Stgb Positive Sozialprognose: 153A Stpo Einstellung Gegen Auflage; 267 Iii Stpo Begruendungsanforderungen Strafurteil; Bewaehrung 56 S... |
| `bewaehrung-auflagen-bewaehrungswiderruf-56f-freiheitsstrafe-ohne` | Bewaehrung Auflagen Und Weisungen 56B C Stgb, Bewaehrungswiderruf 56F Stgb, Freiheitsstrafe Ohne Bewaehrung Vollstreckung: Bewaehrung Auflagen Und Weisungen 56B C Stgb; Bewaehrungswiderruf 56F Stgb; Freiheitsstrafe Ohne Bewaehrung Vollst... |
| `bewaehrung-interessen-deutschem-freiheitsstrafe` | Spezial Bewaehrung Mehrparteien Konflikt Und Interessen, Spezial Deutschem Tatbestand Beweis Und Belege, Spezial Freiheitsstrafe Compliance Dokumentation Und Akte: Spezial Bewaehrung Mehrparteien Konflikt Und Interessen; Spezial Deutsche... |
| `freiheitsstrafe-strafmass-geldstrafe-tagessatzanzahl-vs-stgb` | Freiheitsstrafe Strafmass Prüfen, Geldstrafe Tagessatzanzahl Bestimmen, Geldstrafe Vs Freiheitsstrafe 47 Stgb: Freiheitsstrafe Strafmass Prüfen; Geldstrafe Tagessatzanzahl Bestimmen; Geldstrafe Vs Freiheitsstrafe 47 Stgb. Führt Intake, P... |
| `geldstrafe-grossen-rechtsmittel-gesamtstrafenfolgen` | Spezial Geldstrafe Zahlen Schwellen Und Berechnung, Spezial Grossen Risikoampel Und Gegenargumente, Spezial Rechtsmittel Und Gesamtstrafenfolgen: Spezial Geldstrafe Zahlen Schwellen Und Berechnung; Spezial Grossen Risikoampel Und Gegenar... |
| `gesamtstrafenbildung-stgb-gestaendnis-strafmilderung` | Gesamtstrafenbildung 53 54 Stgb Erste Instanz, Gestaendnis Und Strafmilderung, Haerteausgleich Bei Nachtraeglicher Gesamtstrafenbildung: Gesamtstrafenbildung 53 54 Stgb Erste Instanz; Gestaendnis Und Strafmilderung; Haerteausgleich Bei N... |
| `jgg-jugendstrafe-minder-schwerer-nachtraegliche` | Jgg Strafzumessung Jugendstrafe Erziehungsmassregeln, Minder Schwerer Fall Und Besonders Schwerer Fall, Nachtraegliche Gesamtstrafenbildung 55 Stgb: Jgg Strafzumessung Jugendstrafe Erziehungsmassregeln; Minder Schwerer Fall Und Besonders... |
| `orientierung-triage-paragraph-stgb-besonders` | Orientierung Strafzumessung Triage, Paragraph 46 Stgb Grundsatz Strafzumessung, Spezial Besonders Formular Portal Und Einreichung: Orientierung Strafzumessung Triage; Paragraph 46 Stgb Grundsatz Strafzumessung; Spezial Besonders Formular... |
| `regelbeispiele-stgb-strafbefehl` | Spezial Regelbeispiele Internationaler Bezug Und Schnittstellen, Spezial Stgb Schriftsatz Brief Und Memo Bausteine, Spezial Strafbefehl Dokumentenmatrix Und Lueckenliste: Spezial Regelbeispiele Internationaler Bezug Und Schnittstellen; S... |
| `spezial-schwerer-red-team-und-qualitaetskontrolle` | Schwerer: Red-Team und Qualitätskontrolle im Plugin strafzumessung; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Standardprüfung. |
| `spezial-tagessatz-livequellen-und-rechtsprechungscheck` | Tagessatz: Livequellen- und Rechtsprechungscheck im Plugin strafzumessung; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Standardprüfung. |
| `strafbefehl-stpo-strafmilderung-stgb-strafrahmen` | Strafbefehl Strafzumessung 407 Stpo, Strafmilderung 49 Stgb Zwingend Fakultativ, Strafrahmen Und Strafzumessungsstufen: Strafbefehl Strafzumessung 407 Stpo; Strafmilderung 49 Stgb Zwingend Fakultativ; Strafrahmen Und Strafzumessungsstufe... |
| `strafkammer-strafzumessung-strafzumessungstatsachen` | Spezial Strafkammer Behörden Gericht Und Registerweg, Spezial Strafzumessung Erstpruefung Und Mandatsziel, Spezial Strafzumessungstatsachen Vergleich Eskalation: Spezial Strafkammer Behörden Gericht Und Registerweg; Spezial Strafzumessun... |
| `strafrecht-verfahrensstadium-strafbefehl-taeter-opfer` | Spezial Strafrecht Fristen Form Und Zustaendigkeit, Spezial Verfahrensstadium Strafbefehl Bis Kammer, Taeter Opfer Ausgleich 46A Stgb Und Schadenswiedergutmachung: Spezial Strafrecht Fristen Form Und Zustaendigkeit; Spezial Verfahrenssta... |
| `strafz-aufklaerungshilfe-kronzeuge-sicherungsverwahrung` | Strafz Aufklaerungshilfe Kronzeuge Spezial, Strafz Sicherungsverwahrung Spezial, Strafz Strafrahmenmilderung Leitfaden: Strafz Aufklaerungshilfe Kronzeuge Spezial; Strafz Sicherungsverwahrung Spezial; Strafz Strafrahmenmilderung Leitfade... |
| `strafz-strafzumessungstatsachen-strafzumessungs-tatsachen` | Strafz Strafzumessungstatsachen Bauleiter, Strafzumessungs Tatsachen 46 Ii Stgb, Tagessatzhoehe 40 Ii Stgb Nettotagesverdienst: Strafz Strafzumessungstatsachen Bauleiter; Strafzumessungs Tatsachen 46 Ii Stgb; Tagessatzhoehe 40 Ii Stgb Ne... |
| `verstaendigung-257c` | Verstaendigung 257C Stpo Strafzumessung: Verstaendigung 257C Stpo Strafzumessung. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zusammen. |
| `workflow-anschluss-skills-router` | Anschluss-Skills Router im Plugin strafzumessung: schlägt nach der ersten Prüfung die passenden Spezialskills aus demselben Plugin vor. |
| `workflow-chronologie-workflow-fristen-regelbeispiele` | Workflow Chronologie Und Belegmatrix, Workflow Fristen Und Risikoampel, Regelbeispiele Rechtsprechung: Workflow Chronologie Und Belegmatrix; Workflow Fristen Und Risikoampel; Regelbeispiele Rechtsprechung. Führt Intake, Prüfroutine, Norm... |
| `workflow-dokumentenintake` | Dokumentenintake im Plugin strafzumessung: liest Uploads, sortiert Dokumentarten, markiert Fristen und baut eine knappe Arbeitsakte. |
| `workflow-kaltstart-und-routing` | Kaltstart und Routing im Plugin strafzumessung: führt vom ersten Satz oder Dokument in den passenden Arbeitsweg, erkennt Rolle, Ziel, Risiko und Anschluss-Skills. |
| `workflow-output-waehlen` | Output wählen im Plugin strafzumessung: entscheidet zwischen Memo, Schriftsatz, Tabelle, Brief, Checkliste, Vermerk, Redline oder Mandantenübersetzung. |
| `workflow-rechtsquellen-livecheck` | Rechtsquellen-Livecheck im Plugin strafzumessung: zwingt vor tragenden Aussagen zum aktuellen Quellencheck bei Gesetzen, Behörden, Gerichten und Formularen. |
| `workflow-unterlagen-lueckenliste` | Unterlagen- und Lückenliste im Plugin strafzumessung: erstellt eine präzise Nachforderungsliste statt allgemeiner Fragebögen. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
