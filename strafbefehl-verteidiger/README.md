# Strafbefehl-Verteidiger

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`strafbefehl-verteidiger`) | [`strafbefehl-verteidiger.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/strafbefehl-verteidiger.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **LUMEN Studios GmbH — Insolvenz- und Wirtschaftsstrafverfahren** (`lumen-studios-insolvenz-strafverfahren`) | [Gesamt-PDF lesen](../testakten/lumen-studios-insolvenz-strafverfahren/gesamt-pdf/lumen-studios-insolvenz-strafverfahren_gesamt.pdf) | [`testakte-lumen-studios-insolvenz-strafverfahren.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-lumen-studios-insolvenz-strafverfahren.zip) |
| **Strafbefehl – Ladendiebstahl und Fahrerflucht** (`strafbefehl-ladendiebstahl-fahrerflucht`) | [Gesamt-PDF lesen](../testakten/strafbefehl-ladendiebstahl-fahrerflucht/gesamt-pdf/strafbefehl-ladendiebstahl-fahrerflucht_gesamt.pdf) | [`testakte-strafbefehl-ladendiebstahl-fahrerflucht.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-strafbefehl-ladendiebstahl-fahrerflucht.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

Ein freistehender Strafbefehls-Assistent für Kanzleien: vom Fristnotruf über Akteneinsicht und Einspruch bis zur beschränkten Rechtsfolgenstrategie oder Hauptverhandlung.

Dieses Plugin ist **vollständig freistehend**. Es erwartet keine anderen Plugins, keine externen Agenten und keine besonderen Repo-Dateien außerhalb seines eigenen Ordners. Wenn Register, Kanzleisoftware, beA, E-Mail, Datenraum oder Aktenexport fehlen, arbeitet es mit manuellen Uploads oder mit einem klar gekennzeichneten Simulationsmodus.

## Schnellstart

1. Plugin aktivieren oder die ZIP aus dem Release installieren.
2. Mit `strafbefehl-kommandocenter` starten.
3. Frist, Zustellung, Aktenzeichen, vorhandene Unterlagen und Mandantenziel nennen.
4. Fehlende Unterlagen nicht raten lassen, sondern mit der passenden Vorlage nachfordern oder Simulation ausdrücklich aktivieren.
5. Vor Versand oder Termin immer das Qualitätstor laufen lassen.

## Enthaltene Skills

- `strafbefehl-kommandocenter` - Strafbefehl-Kommandocenter
- `strafbefehl-aktenanlage` - Aktenanlage Strafbefehl
- `strafbefehl-fristen-einspruch` - Frist und Einspruch nach § 410 StPO
- `strafbefehl-akteneinsicht-147` - Akteneinsicht
- `strafbefehl-zulaessigkeit-407` - Zulässigkeit des Strafbefehls
- `strafbefehl-inhalt-409-pruefung` - Inhaltsprüfung nach § 409 StPO
- `strafbefehl-einspruch-beschraenkung` - Einspruch beschränken oder nicht
- `strafbefehl-wiedereinsetzung` - Wiedereinsetzung
- `strafbefehl-pflichtverteidiger` - Pflichtverteidigung
- `strafbefehl-polizeifilmerei-201-kug` - Film-, Foto- und Tonaufnahmen von Polizeieinsätzen
- `strafbefehl-tagessaetze-geldstrafe` - Tagessätze und Geldstrafe
- `strafbefehl-nebenfolgen-fahrerlaubnis` - Nebenfolgen
- `strafbefehl-beweis-und-einlassung` - Beweis und Einlassung
- `strafbefehl-zeugen-befragungsstrategie` - Zeugenbefragung
- `strafbefehl-hauptverhandlung-vorbereitung` - Hauptverhandlung vorbereiten
- `strafbefehl-abwesenheit-vertretung` - Abwesenheit und Vertretung
- `strafbefehl-einstellung-153-153a-170` - Einstellung und Verständigung
- `strafbefehl-deal-verstaendigung` - Gesprächsstrategie mit Gericht und Staatsanwaltschaft
- `strafbefehl-rechtsmittel-nach-urteil` - Rechtsmittel nach Urteil
- `strafbefehl-rechtsprechungsrecherche` - Rechtsprechungsrecherche
- `strafbefehl-quality-gate` - Qualitätstor

## Vorlagen

- `assets/templates/strafbefehl-mandatskarte.md` - Strafbefehl-Mandatskarte
- `assets/templates/frist-einspruch-410.md` - Frist und Einspruch nach § 410 StPO
- `assets/templates/akteneinsicht-147.md` - Akteneinsicht nach § 147 StPO
- `assets/templates/strafbefehl-inhaltspruefung.md` - Inhaltsprüfung Strafbefehl
- `assets/templates/einspruch-unbeschraenkt.md` - Unbeschränkter Einspruch
- `assets/templates/einspruch-beschraenkt.md` - Beschränkter Einspruch
- `assets/templates/wiedereinsetzung.md` - Wiedereinsetzung
- `assets/templates/pflichtverteidiger-check.md` - Pflichtverteidiger-Check
- `assets/templates/tagessaetze.md` - Tagessatzprüfung
- `assets/templates/einlassungsstrategie.md` - Einlassungsstrategie
- `assets/templates/zeugen-fragenkatalog.md` - Zeugenfragen
- `assets/templates/hauptverhandlung-plan.md` - Hauptverhandlung
- `assets/templates/einstellung-153-153a.md` - Einstellung nach §§ 153, 153a StPO
- `assets/templates/nebenfolgen-fahrerlaubnis.md` - Nebenfolgen
- `assets/templates/rechtsmittel-nach-urteil.md` - Rechtsmittel nach Urteil
- `assets/templates/quality-gate.md` - Qualitätstor

## Freistehende Leitplanken

- Keine stillen Verweise auf andere Plugins.
- Keine produktive Rechtsberatung ohne anwaltliche Prüfung.
- Keine echten Mandatsgeheimnisse in ungeprüfte Cloud- oder KI-Umgebungen.
- Keine erfundenen Fundstellen, Aktenzeichen oder Rechtsprechung.
- Fristen, Rechtsmittel, Aussageverhalten und Nebenfolgen werden sichtbar geprüft.
- Jede Ausgabe muss so gestaltet sein, dass eine Berufsträgerin oder ein Berufsträger sie sofort prüfen, kürzen, freigeben oder verwerfen kann.

<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 24 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `kompendium-01-allgemein-bis-workflow-fristen-und` | strafbefehl-verteidiger: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Allgemein, Chronologie Und Belegmatrix, Fristen Und Risikoampel; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätsc... |
| `kompendium-02-workflow-mandantenko-bis-strafbefehl-rechtspr` | strafbefehl-verteidiger: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Mandantenkommunikation, Redteam Qualitygate, Strafbefehl Rechtsprechungsrecherche; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmus... |
| `kompendium-03-spezial-gegen-friste-bis-strafbefehl-aktenanl` | strafbefehl-verteidiger: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Gegen Fristen Form Und Zustaendigkeit, Strafbefehl Fristen Einspruch, Strafbefehl Aktenanlage; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogi... |
| `kompendium-04-strafbefehl-kommando-bis-spezial-akteneinsich` | strafbefehl-verteidiger: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Strafbefehl Kommandocenter, Strafbefehl Quality Gate, Akteneinsicht Behoerden Gericht Und Registerweg; mit Intake, Prüfroutine, Normen-/Quellenradar, Be... |
| `kompendium-05-spezial-deal-beweisl-bis-spezial-einspruchsen` | strafbefehl-verteidiger: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Deal Beweislast Und Darlegungslast, Einspruch Risikoampel Und Gegenargumente, Einspruchsentscheidung Und Folgen; mit Intake, Prüfroutine, Normen-/Quelle... |
| `kompendium-06-spezial-einstellung-bis-spezial-hauptverhand` | strafbefehl-verteidiger: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Einstellung Compliance Dokumentation Und Akte, Fahrerlaubnis Mandantenentscheidung, Hauptverhandlung International Schnittstellen; mit Intake, Prüfrouti... |
| `kompendium-07-spezial-nebenfolgen-bis-spezial-strafbefehls` | strafbefehl-verteidiger: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Nebenfolgen Verhandlung Vergleich Und Eskalation, Strafbefehl Dokumentenmatrix Und Lueckenliste, Strafbefehls Erstpruefung Und Mandatsziel; mit Intake,... |
| `kompendium-08-spezial-tagessaetze-bis-spezial-verteidiger` | strafbefehl-verteidiger: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Tagessaetze Schriftsatz Brief Und Memo Bausteine, Verstaendigung Sonderfall Und Edge Case, Verteidiger Formular Portal Und Einreichung; mit Intake, Prüf... |
| `kompendium-09-spezial-verteidigung-bis-spezial-zeugenstrate` | strafbefehl-verteidiger: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Verteidigung Tatbestand Beweis Und Belege, Wiedereinsetzung Zahlen Schwellen Und Berechnung, Zeugenstrategie Mehrparteien Konflikt Und Interessen; mit I... |
| `kompendium-10-stbv-einspruch-straf-bis-stbv-strafbefehl-aus` | strafbefehl-verteidiger: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Stbv Einspruch Strafbefehl Leitfaden, Stbv Fahrerlaubnis Bei Strafbefehl Spezial, Stbv Strafbefehl Auslaendischer Mandant Spezial; mit Intake, Prüfrouti... |
| `kompendium-11-stbv-strafbefehl-pru-bis-strafbefehl-aktenein` | strafbefehl-verteidiger: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Stbv Strafbefehl Pruefung Bauleiter, Strafbefehl Abwesenheit Vertretung, Strafbefehl Akteneinsicht 147; mit Intake, Prüfroutine, Normen-/Quellenradar, B... |
| `kompendium-12-strafbefehl-beweis-u-bis-strafbefehl-einspruc` | strafbefehl-verteidiger: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Strafbefehl Beweis Und Einlassung, Strafbefehl Deal Verstaendigung, Strafbefehl Einspruch Beschraenkung; mit Intake, Prüfroutine, Normen-/Quellenradar,... |
| `kompendium-13-strafbefehl-einstell-bis-strafbefehl-inhalt-4` | strafbefehl-verteidiger: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Strafbefehl Einstellung 153 153a 170, Strafbefehl Hauptverhandlung Vorbereitung, Strafbefehl Inhalt 409 Pruefung; mit Intake, Prüfroutine, Normen-/Quell... |
| `kompendium-14-strafbefehl-nebenfol-bis-strafbefehl-polizeif` | strafbefehl-verteidiger: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Strafbefehl Nebenfolgen Fahrerlaubnis, Strafbefehl Pflichtverteidiger, Strafbefehl Polizeifilmerei 201 Kug; mit Intake, Prüfroutine, Normen-/Quellenrada... |
| `kompendium-15-strafbefehl-rechtsmi-bis-strafbefehl-wiederei` | strafbefehl-verteidiger: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Strafbefehl Rechtsmittel Nach Urteil, Strafbefehl Tagessaetze Geldstrafe, Strafbefehl Wiedereinsetzung; mit Intake, Prüfroutine, Normen-/Quellenradar, B... |
| `kompendium-16-strafbefehl-zeugen-b-bis-strafbefehl-zulaessi` | strafbefehl-verteidiger: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Strafbefehl Zeugen Befragungsstrategie, Strafbefehl Zulaessigkeit 407; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qual... |
| `spezial-aktenanlage-red-team-und-qualitaetskontrolle` | Aktenanlage: Red-Team und Qualitätskontrolle im Plugin strafbefehl verteidiger; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Standardprüfung. |
| `spezial-pflichtverteidigung-livequellen-und-rechtsprechungscheck` | Pflichtverteidigung: Livequellen- und Rechtsprechungscheck im Plugin strafbefehl verteidiger; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Standardprüfung. |
| `workflow-anschluss-skills-router` | Anschluss-Skills Router im Plugin strafbefehl-verteidiger: schlägt nach der ersten Prüfung die passenden Spezialskills aus demselben Plugin vor. |
| `workflow-dokumentenintake` | Dokumentenintake im Plugin strafbefehl-verteidiger: liest Uploads, sortiert Dokumentarten, markiert Fristen und baut eine knappe Arbeitsakte. |
| `workflow-kaltstart-und-routing` | Kaltstart und Routing im Plugin strafbefehl-verteidiger: führt vom ersten Satz oder Dokument in den passenden Arbeitsweg, erkennt Rolle, Ziel, Risiko und Anschluss-Skills. |
| `workflow-output-waehlen` | Output wählen im Plugin strafbefehl-verteidiger: entscheidet zwischen Memo, Schriftsatz, Tabelle, Brief, Checkliste, Vermerk, Redline oder Mandantenübersetzung. |
| `workflow-rechtsquellen-livecheck` | Rechtsquellen-Livecheck im Plugin strafbefehl-verteidiger: zwingt vor tragenden Aussagen zum aktuellen Quellencheck bei Gesetzen, Behörden, Gerichten und Formularen. |
| `workflow-unterlagen-lueckenliste` | Unterlagen- und Lückenliste im Plugin strafbefehl-verteidiger: erstellt eine präzise Nachforderungsliste statt allgemeiner Fragebögen. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
