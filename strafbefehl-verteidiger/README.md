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
| `allgemein-workflow-chronologie-workflow-fristen` | Allgemein, Workflow Chronologie Und Belegmatrix, Workflow Fristen Und Risikoampel: Allgemein; Workflow Chronologie Und Belegmatrix; Workflow Fristen Und Risikoampel. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmus... |
| `deal-beweislast-einspruch-einspruchsentscheidung-folgen` | Spezial Deal Beweislast Und Darlegungslast, Spezial Einspruch Risikoampel Und Gegenargumente, Spezial Einspruchsentscheidung Und Folgen: Spezial Deal Beweislast Und Darlegungslast; Spezial Einspruch Risikoampel Und Gegenargumente; Spezia... |
| `einstellung-153a-hauptverhandlung-vorbereitung-strafbefehl` | Strafbefehl Einstellung 153 153A 170, Strafbefehl Hauptverhandlung Vorbereitung, Strafbefehl Inhalt 409 Prüfung: Strafbefehl Einstellung 153 153A 170; Strafbefehl Hauptverhandlung Vorbereitung; Strafbefehl Inhalt 409 Prüfung. Führt Intak... |
| `einstellung-fahrerlaubnis-mandantenentscheidung-hauptverhandlung` | Spezial Einstellung Compliance Dokumentation Und Akte, Spezial Fahrerlaubnis Mandantenentscheidung, Spezial Hauptverhandlung International Schnittstellen: Spezial Einstellung Compliance Dokumentation Und Akte; Spezial Fahrerlaubnis Manda... |
| `gegen-strafbefehl-einspruch-strafbefehl-aktenanlage` | Spezial Gegen Fristen Form Und Zustaendigkeit, Strafbefehl Fristen Einspruch, Strafbefehl Aktenanlage: Spezial Gegen Fristen Form Und Zustaendigkeit; Strafbefehl Fristen Einspruch; Strafbefehl Aktenanlage. Führt Intake, Prüfroutine, Norm... |
| `nebenfolgen-fahrerlaubnis-strafbefehl-pflichtverteidiger` | Strafbefehl Nebenfolgen Fahrerlaubnis, Strafbefehl Pflichtverteidiger, Strafbefehl Polizeifilmerei 201 Kug: Strafbefehl Nebenfolgen Fahrerlaubnis; Strafbefehl Pflichtverteidiger; Strafbefehl Polizeifilmerei 201 Kug. Führt Intake, Prüfrou... |
| `nebenfolgen-strafbefehl-strafbefehls` | Spezial Nebenfolgen Verhandlung Vergleich Und Eskalation, Spezial Strafbefehl Dokumentenmatrix Und Lueckenliste, Spezial Strafbefehls Erstpruefung Und Mandatsziel: Spezial Nebenfolgen Verhandlung Vergleich Und Eskalation; Spezial Strafbe... |
| `rechtsmittel-nach-tagessaetze-geldstrafe-strafbefehl` | Strafbefehl Rechtsmittel Nach Urteil, Strafbefehl Tagessaetze Geldstrafe, Strafbefehl Wiedereinsetzung: Strafbefehl Rechtsmittel Nach Urteil; Strafbefehl Tagessaetze Geldstrafe; Strafbefehl Wiedereinsetzung. Führt Intake, Prüfroutine, No... |
| `spezial-aktenanlage-red-team-und-qualitaetskontrolle` | Aktenanlage: Red-Team und Qualitätskontrolle im Plugin strafbefehl verteidiger; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Standardprüfung. |
| `spezial-pflichtverteidigung-livequellen-und-rechtsprechungscheck` | Pflichtverteidigung: Livequellen- und Rechtsprechungscheck im Plugin strafbefehl verteidiger; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Standardprüfung. |
| `stbv-einspruch-strafbefehl-fahrerlaubnis-auslaendischer-mandant` | Stbv Einspruch Strafbefehl Leitfaden, Stbv Fahrerlaubnis Bei Strafbefehl Spezial, Stbv Strafbefehl Auslaendischer Mandant Spezial: Stbv Einspruch Strafbefehl Leitfaden; Stbv Fahrerlaubnis Bei Strafbefehl Spezial; Stbv Strafbefehl Auslaen... |
| `stbv-strafbefehl-abwesenheit-vertretung-akteneinsicht` | Stbv Strafbefehl Prüfung Bauleiter, Strafbefehl Abwesenheit Vertretung, Strafbefehl Akteneinsicht 147: Stbv Strafbefehl Prüfung Bauleiter; Strafbefehl Abwesenheit Vertretung; Strafbefehl Akteneinsicht 147. Führt Intake, Prüfroutine, Norm... |
| `strafbefehl-einlassung-deal-verstaendigung-einspruch` | Strafbefehl Beweis Und Einlassung, Strafbefehl Deal Verstaendigung, Strafbefehl Einspruch Beschraenkung: Strafbefehl Beweis Und Einlassung; Strafbefehl Deal Verstaendigung; Strafbefehl Einspruch Beschraenkung. Führt Intake, Prüfroutine,... |
| `strafbefehl-quality-gate-akteneinsicht` | Strafbefehl Kommandocenter, Strafbefehl Quality Gate, Spezial Akteneinsicht Behörden Gericht Und Registerweg: Strafbefehl Kommandocenter; Strafbefehl Quality Gate; Spezial Akteneinsicht Behörden Gericht Und Registerweg. Führt Intake, Prü... |
| `tagessaetze-verstaendigung-sonderfall-verteidiger` | Spezial Tagessaetze Schriftsatz Brief Und Memo Bausteine, Spezial Verstaendigung Sonderfall Und Edge Case, Spezial Verteidiger Formular Portal Und Einreichung: Spezial Tagessaetze Schriftsatz Brief Und Memo Bausteine; Spezial Verstaendig... |
| `verteidigung-wiedereinsetzung-zeugenstrategie-interessen` | Spezial Verteidigung Tatbestand Beweis Und Belege, Spezial Wiedereinsetzung Zahlen Schwellen Und Berechnung, Spezial Zeugenstrategie Mehrparteien Konflikt Und Interessen: Spezial Verteidigung Tatbestand Beweis Und Belege; Spezial Wiedere... |
| `workflow-anschluss-skills-router` | Anschluss-Skills Router im Plugin strafbefehl-verteidiger: schlägt nach der ersten Prüfung die passenden Spezialskills aus demselben Plugin vor. |
| `workflow-dokumentenintake` | Dokumentenintake im Plugin strafbefehl-verteidiger: liest Uploads, sortiert Dokumentarten, markiert Fristen und baut eine knappe Arbeitsakte. |
| `workflow-kaltstart-und-routing` | Kaltstart und Routing im Plugin strafbefehl-verteidiger: führt vom ersten Satz oder Dokument in den passenden Arbeitsweg, erkennt Rolle, Ziel, Risiko und Anschluss-Skills. |
| `workflow-mandantenkommunikation-redteam-qualitygate-strafbefehl` | Workflow Mandantenkommunikation, Workflow Redteam Qualitygate, Strafbefehl Rechtsprechungsrecherche: Workflow Mandantenkommunikation; Workflow Redteam Qualitygate; Strafbefehl Rechtsprechungsrecherche. Führt Intake, Prüfroutine, Normen-/... |
| `workflow-output-waehlen` | Output wählen im Plugin strafbefehl-verteidiger: entscheidet zwischen Memo, Schriftsatz, Tabelle, Brief, Checkliste, Vermerk, Redline oder Mandantenübersetzung. |
| `workflow-rechtsquellen-livecheck` | Rechtsquellen-Livecheck im Plugin strafbefehl-verteidiger: zwingt vor tragenden Aussagen zum aktuellen Quellencheck bei Gesetzen, Behörden, Gerichten und Formularen. |
| `workflow-unterlagen-lueckenliste` | Unterlagen- und Lückenliste im Plugin strafbefehl-verteidiger: erstellt eine präzise Nachforderungsliste statt allgemeiner Fragebögen. |
| `zeugen-befragungsstrategie-strafbefehl-zulaessigkeit` | Strafbefehl Zeugen Befragungsstrategie, Strafbefehl Zulässigkeit 407: Strafbefehl Zeugen Befragungsstrategie; Strafbefehl Zulässigkeit 407. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zus... |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
