# VerkehrsOWi-Verteidiger

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`verkehrsowi-verteidiger`) | [`verkehrsowi-verteidiger.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/verkehrsowi-verteidiger.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **Norderhof-Tannenmoor — Abstandsverstoß Section Control BAB 7 Bispingen, Bußgeld und Fahrverbot** (`verkehrsowi-abstand-section-control-bab-7-bispingen-bussgeld-und-fahrverbot-norderhof`) | [Gesamt-PDF lesen](../testakten/verkehrsowi-abstand-section-control-bab-7-bispingen-bussgeld-und-fahrverbot-norderhof/gesamt-pdf/verkehrsowi-abstand-section-control-bab-7-bispingen-bussgeld-und-fahrverbot-norderhof_gesamt.pdf) | [`testakte-verkehrsowi-abstand-section-control-bab-7-bispingen-bussgeld-und-fahrverbot-norderhof.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-verkehrsowi-abstand-section-control-bab-7-bispingen-bussgeld-und-fahrverbot-norderhof.zip) |
| **VerkehrsOWi – Qualifizierter Rotlichtverstoß, Tempoüberschreitung und Fahrverbot** (`verkehrsowi-rotlicht-tempo`) | [Gesamt-PDF lesen](../testakten/verkehrsowi-rotlicht-tempo/gesamt-pdf/verkehrsowi-rotlicht-tempo_gesamt.pdf) | [`testakte-verkehrsowi-rotlicht-tempo.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-verkehrsowi-rotlicht-tempo.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

Ein freistehender Verteidigungsassistent für Verkehrsordnungswidrigkeiten: vom Anhörungsbogen über Einspruch, Akteneinsicht, Messakte und Punkte bis zur Amtsgerichtsverhandlung.

Dieses Plugin ist **vollständig freistehend**. Es erwartet keine anderen Plugins, keine externen Agenten und keine besonderen Repo-Dateien außerhalb seines eigenen Ordners. Wenn Register, Kanzleisoftware, beA, E-Mail, Datenraum oder Aktenexport fehlen, arbeitet es mit manuellen Uploads oder mit einem klar gekennzeichneten Simulationsmodus.

## Schnellstart

1. Plugin aktivieren oder die ZIP aus dem Release installieren.
2. Mit `verkehrsowi-kommandocenter` starten.
3. Frist, Zustellung, Aktenzeichen, vorhandene Unterlagen und Mandantenziel nennen.
4. Fehlende Unterlagen nicht raten lassen, sondern mit der passenden Vorlage nachfordern oder Simulation ausdrücklich aktivieren.
5. Vor Versand oder Termin immer das Qualitätstor laufen lassen.

## Enthaltene Skills

- `verkehrsowi-kommandocenter` - VerkehrsOWi-Kommandocenter
- `verkehrsowi-aktenanlage` - Aktenanlage und Dokumentenregister
- `verkehrsowi-anhoerung-bussgeldbescheid` - Anhörung und Bußgeldbescheid prüfen
- `verkehrsowi-fristen-einspruch` - Fristen und Einspruch
- `verkehrsowi-verjaehrung-zustellung` - Verjährung und Zustellung
- `verkehrsowi-akteneinsicht-messakte` - Akteneinsicht und Messakte
- `verkehrsowi-messverfahren-geschwindigkeit` - Geschwindigkeitsmessung
- `verkehrsowi-rotlicht-abstand-handy` - Rotlicht, Abstand und Handy
- `verkehrsowi-alkohol-drogen-24a` - Alkohol und Drogen nach § 24a StVG
- `verkehrsowi-fahreridentifizierung` - Fahreridentifizierung
- `verkehrsowi-punkte-fahrverbot-flensburg` - Punkte, Fahrverbot und Flensburg
- `verkehrsowi-haertefall-fahrverbot` - Härtefall beim Fahrverbot
- `verkehrsowi-beweisverwertung-standardisiert` - Beweisverwertung und Standardisierung
- `verkehrsowi-zeugen-polizei-strategie` - Zeugen- und Polizeibefragung
- `verkehrsowi-hauptverhandlung-amtsgericht` - Hauptverhandlung vor dem Amtsgericht
- `verkehrsowi-rechtsbeschwerde` - Rechtsbeschwerde
- `verkehrsowi-rechtsprechungsrecherche` - Rechtsprechungsrecherche
- `verkehrsowi-mandantenkommunikation` - Mandantenkommunikation
- `verkehrsowi-simulation-training` - Simulation und Training
- `verkehrsowi-quality-gate` - Qualitätstor

## Vorlagen

- `assets/templates/verkehrsowi-mandatskarte.md` - VerkehrsOWi-Mandatskarte
- `assets/templates/frist-und-verjaehrung.md` - Fristen- und Verjährungsblatt
- `assets/templates/anhoerungsbogen-check.md` - Anhörungsbogen-Check
- `assets/templates/bussgeldbescheid-pruefung.md` - Bußgeldbescheid-Prüfung
- `assets/templates/einspruch-owig-67.md` - Einspruch nach § 67 OWiG
- `assets/templates/akteneinsicht-messakte.md` - Akteneinsicht und Messakte
- `assets/templates/messverfahren-checkliste.md` - Messverfahren-Checkliste
- `assets/templates/fahreridentifizierung.md` - Fahreridentifizierung
- `assets/templates/punkte-fahrverbot-matrix.md` - Punkte- und Fahrverbotsmatrix
- `assets/templates/haertefall-fahrverbot.md` - Härtefallpaket Fahrverbot
- `assets/templates/zeugen-polizei-fragenkatalog.md` - Zeugen- und Polizeifragen
- `assets/templates/hauptverhandlung-amtsgericht.md` - Hauptverhandlung Amtsgericht
- `assets/templates/rechtsbeschwerde-check.md` - Rechtsbeschwerde-Check
- `assets/templates/rechtsprechungsrecherche.md` - Rechtsprechungsrecherche
- `assets/templates/mandantenanschreiben.md` - Mandantenanschreiben
- `assets/templates/quality-gate.md` - Qualitätstor

## Freistehende Leitplanken

- Keine stillen Verweise auf andere Plugins.
- Keine produktive Rechtsberatung ohne anwaltliche Prüfung.
- Keine echten Mandatsgeheimnisse in ungeprüfte Cloud- oder KI-Umgebungen.
- Keine erfundenen Fundstellen, Aktenzeichen oder Rechtsprechung.
- Fristen, Rechtsmittel, Aussageverhalten und Nebenfolgen werden sichtbar geprüft.
- Jede Ausgabe muss so gestaltet sein, dass eine Berufsträgerin oder ein Berufsträger sie sofort prüfen, kürzen, freigeben oder verwerfen kann.

## Arbeitsakte

Zum Arbeiten liegt die Akte unter `testakten/verkehrsowi-rotlicht-tempo`. Sie wird im Release als `testakte-verkehrsowi-rotlicht-tempo.zip` bereitgestellt und ist kein Bestandteil des Plugin-ZIPs.

<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 24 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `kompendium-01-allgemein-bis-workflow-fristen-und` | verkehrsowi-verteidiger: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Allgemein, Chronologie Und Belegmatrix, Fristen Und Risikoampel; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätsc... |
| `kompendium-02-workflow-mandantenko-bis-verkehrsowi-rechtspr` | verkehrsowi-verteidiger: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Mandantenkommunikation, Redteam Qualitygate, Verkehrsowi Rechtsprechungsrecherche; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmus... |
| `kompendium-03-spezial-anhoerung-fr-bis-verkehrsowi-messverf` | verkehrsowi-verteidiger: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Anhoerung Fristen Form Und Zustaendigkeit, Verkehrsowi Fristen Einspruch, Verkehrsowi Messverfahren Geschwindigkeit; mit Intake, Prüfroutine, Normen-/Qu... |
| `kompendium-04-vowi-tempomessverfah-bis-verkehrsowi-anhoerun` | verkehrsowi-verteidiger: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Vowi Tempomessverfahren Fehlerquellen Spezial, Bussgeldbescheid Tatbestand Beweis Und Belege, Verkehrsowi Anhoerung Bussgeldbescheid; mit Intake, Prüfro... |
| `kompendium-05-vowi-bussgeldbeschei-bis-verkehrsowi-quality` | verkehrsowi-verteidiger: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Vowi Bussgeldbescheid Pruefung Bauleiter, Verkehrsowi Kommandocenter, Verkehrsowi Quality Gate; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislog... |
| `kompendium-06-vowi-handyverstoss-s-bis-spezial-alkohol-comp` | verkehrsowi-verteidiger: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Vowi Handyverstoss Spezial, Akteneinsicht Internationaler Bezug Und Schnittstellen, Alkohol Compliance Dokumentation Und Akte; mit Intake, Prüfroutine,... |
| `kompendium-07-spezial-amtsgericht-bis-spezial-einspruch-do` | verkehrsowi-verteidiger: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Amtsgericht Mandantenkommunikation Entscheidungsvorlage, Drogen Mehrparteien Konflikt Und Interessen, Einspruch Dokumentenmatrix Und Lueckenliste; mit I... |
| `kompendium-08-spezial-fahrverbot-b-bis-spezial-handy-zahlen` | verkehrsowi-verteidiger: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Fahrverbot Behoerden Gericht Und Registerweg, Geschwindigkeit Verhandlung Vergleich Und Eskalation, Handy Zahlen Schwellen Und Berechnung; mit Intake, P... |
| `kompendium-09-spezial-hauptverhand-bis-spezial-messung-fahr` | verkehrsowi-verteidiger: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Hauptverhandlung Sonderfall Und Edge Case, Messakte Formular Portal Und Einreichung, Messung Fahrverbot Punkte; mit Intake, Prüfroutine, Normen-/Quellen... |
| `kompendium-10-spezial-punkte-risik-bis-spezial-verkehrsowi` | verkehrsowi-verteidiger: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Punkte Risikoampel Und Gegenargumente, Rotlicht Schriftsatz Brief Und Memo Bausteine, Verkehrsowi Erstpruefung Und Mandatsziel; mit Intake, Prüfroutine,... |
| `kompendium-11-spezial-verteidiger-bis-verkehrsowi-aktenein` | verkehrsowi-verteidiger: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Verteidiger Beweislast Und Darlegungslast, Verkehrsowi Aktenanlage, Verkehrsowi Akteneinsicht Messakte; mit Intake, Prüfroutine, Normen-/Quellenradar, B... |
| `kompendium-12-verkehrsowi-alkohol-bis-verkehrsowi-fahrerid` | verkehrsowi-verteidiger: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Verkehrsowi Alkohol Drogen 24a, Verkehrsowi Beweisverwertung Standardisiert, Verkehrsowi Fahreridentifizierung; mit Intake, Prüfroutine, Normen-/Quellen... |
| `kompendium-13-verkehrsowi-haertefa-bis-verkehrsowi-mandante` | verkehrsowi-verteidiger: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Verkehrsowi Haertefall Fahrverbot, Verkehrsowi Hauptverhandlung Amtsgericht, Verkehrsowi Mandantenkommunikation; mit Intake, Prüfroutine, Normen-/Quelle... |
| `kompendium-14-verkehrsowi-punkte-f-bis-verkehrsowi-rotlicht` | verkehrsowi-verteidiger: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Verkehrsowi Punkte Fahrverbot Flensburg, Verkehrsowi Rechtsbeschwerde, Verkehrsowi Rotlicht Abstand Handy; mit Intake, Prüfroutine, Normen-/Quellenradar... |
| `kompendium-15-verkehrsowi-simulati-bis-verkehrsowi-zeugen-p` | verkehrsowi-verteidiger: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Verkehrsowi Simulation Training, Verkehrsowi Verjaehrung Zustellung, Verkehrsowi Zeugen Polizei Strategie; mit Intake, Prüfroutine, Normen-/Quellenradar... |
| `kompendium-16-vowi-akteneinsicht-r-bis-vowi-akteneinsicht-r` | verkehrsowi-verteidiger: eigenständiger Arbeits-Skill zu Vowi Akteneinsicht Rohmessdaten Leitfaden; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck. |
| `spezial-abstand-livequellen-und-rechtsprechungscheck` | Abstand: Livequellen- und Rechtsprechungscheck im Plugin verkehrsowi verteidiger; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Standardprüfung. |
| `spezial-zeugenstrategie-red-team-und-qualitaetskontrolle` | Zeugenstrategie: Red-Team und Qualitätskontrolle im Plugin verkehrsowi verteidiger; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Standardprüfung. |
| `workflow-anschluss-skills-router` | Anschluss-Skills Router im Plugin verkehrsowi-verteidiger: schlägt nach der ersten Prüfung die passenden Spezialskills aus demselben Plugin vor. |
| `workflow-dokumentenintake` | Dokumentenintake im Plugin verkehrsowi-verteidiger: liest Uploads, sortiert Dokumentarten, markiert Fristen und baut eine knappe Arbeitsakte. |
| `workflow-kaltstart-und-routing` | Kaltstart und Routing im Plugin verkehrsowi-verteidiger: führt vom ersten Satz oder Dokument in den passenden Arbeitsweg, erkennt Rolle, Ziel, Risiko und Anschluss-Skills. |
| `workflow-output-waehlen` | Output wählen im Plugin verkehrsowi-verteidiger: entscheidet zwischen Memo, Schriftsatz, Tabelle, Brief, Checkliste, Vermerk, Redline oder Mandantenübersetzung. |
| `workflow-rechtsquellen-livecheck` | Rechtsquellen-Livecheck im Plugin verkehrsowi-verteidiger: zwingt vor tragenden Aussagen zum aktuellen Quellencheck bei Gesetzen, Behörden, Gerichten und Formularen. |
| `workflow-unterlagen-lueckenliste` | Unterlagen- und Lückenliste im Plugin verkehrsowi-verteidiger: erstellt eine präzise Nachforderungsliste statt allgemeiner Fragebögen. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
