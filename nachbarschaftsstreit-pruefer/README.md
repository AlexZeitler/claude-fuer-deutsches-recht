# Nachbarschaftsstreit-Prüfer

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`nachbarschaftsstreit-pruefer`) | [`nachbarschaftsstreit-pruefer.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/nachbarschaftsstreit-pruefer.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **Nachbarschaftsstreit Rosengartenstraße** (`nachbarschaftsstreit-horrorfall-rosengarten`) | [Gesamt-PDF lesen](../testakten/nachbarschaftsstreit-horrorfall-rosengarten/gesamt-pdf/nachbarschaftsstreit-horrorfall-rosengarten_gesamt.pdf) | [`testakte-nachbarschaftsstreit-horrorfall-rosengarten.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-nachbarschaftsstreit-horrorfall-rosengarten.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

Freistehendes Plugin für Nachbarrecht und eskalierte Grundstückskonflikte: Überbau, Überhang, Äste und Wurzeln, Grenzbäume, Einfriedung, Zaun, Mauer, Hecke, Immissionen, Vertiefung, drohender Einsturz, Notweg, Hammerschlags- und Leiterrecht, Beweissicherung, Aufforderungsschreiben, einstweilige Verfügung, Klage und Vergleich.

**Keine Rechtsberatung.** Das Plugin erzeugt strukturierte Prüfungen, Entwürfe und Workflows zur anwaltlichen Kontrolle. Landesnachbarrecht, Baumschutzsatzungen, Bebauungspläne und örtliche Satzungen müssen im konkreten Fall geprüft werden.

## Start

```
/nachbarschaftsstreit-pruefer:allgemein
```

Der Einstieg fragt in kurzer Zeit ab: Grundstücke, Grenze, Bundesland, Streitgegenstand, Gefahr, Beweislage, bisherige Schreiben, gewünschter Ton und Ziel. Danach routet er zu den Spezialskills.

## Skills (20)

| Skill | Zweck |
|---|---|
| `allgemein` | Schöner Einstieg, Fristen-/Gefahrenscan, Routing und Arbeitsplan |
| `nachbarrecht-kaltstart-triage` | Erstaufnahme des Konflikts mit Bundesland, Grundstück, Beteiligten und Risiko |
| `akten-und-grundstuecksaufnahme` | Grundbuch, Liegenschaftskarte, Baulast, Dienstbarkeit, Fotos und Chronologie erfassen |
| `anspruchslandkarte-bgb-nachbarrecht` | Anspruchsgrundlagen nach BGB und Landesrecht sortieren |
| `ueberbau-pruefung` | Überbau nach §§ 912-916 BGB, Widerspruch, Duldung, Rente, Abkauf |
| `ueberhang-aeste-wurzeln` | Überhängende Äste, Wurzeln, Fristsetzung, Selbsthilfe nach § 910 BGB |
| `grenzbaum-und-grenzanlage` | Grenzbaum, Grenzsträucher und gemeinschaftliche Grenzanlagen §§ 921-923 BGB |
| `einfriedung-zaun-mauer-hecke` | Zaun, Mauer, Hecke, Kosten, Standort, Ortsüblichkeit und Landesrecht |
| `immissionen-laerm-geruch-rauch-licht` | Geräusche, Gerüche, Rauch, Licht, Erschütterungen, § 906 BGB |
| `vertiefung-baugrube-stuetzverlust` | Baugrube, Unterfangung, Stütze des Nachbargrundstücks, § 909 BGB |
| `drohender-einsturz-gefahranlage` | Gefährliche Anlagen und Einsturzrisiken, §§ 907, 908 BGB |
| `notweg-zufahrt-wegerecht` | Notweg, Zufahrt, Grunddienstbarkeit, Baulast, §§ 917, 918 BGB |
| `hammerschlags-und-leiterrecht` | Betreten des Nachbargrundstücks für Bau-/Instandhaltungsarbeiten nach Landesrecht |
| `landesnachbarrecht-router` | Bundesland auswählen und landesrechtliche Prüfmodule planen |
| `beweissicherung-ortstermin-fotos` | Ortstermin, Fotoplan, Messpunkte, Sachverständige und selbständiges Beweisverfahren |
| `selbsthilfe-und-eskalationsgrenzen` | Was darf man selbst tun, was nicht, und wann drohen Besitz-/Eigentumsverletzungen? |
| `aufforderungsschreiben-nachbar` | Sachliches, druckvolles Anspruchs- und Fristsetzungsschreiben |
| `einstweilige-verfuegung-und-klage` | Eilrechtsschutz, Unterlassung, Beseitigung, Duldung, Feststellung, Streitwert |
| `vergleich-mediation-nachbarschaftsfrieden` | Vergleich, Nutzungsregelung, Rückschnittplan, Kosten- und Zugangslösung |
| `horrorfall-aktenauswertung` | Große unordentliche Nachbarschaftsakte auswerten und in Arbeitsstränge zerlegen |

## Quellenstand

Stand: 05/2026. Kernnormen: BGB §§ 903, 906-923, 823, 862, 1004; Landesnachbarrechtsgesetze und kommunale Satzungen nach Bundesland/Gemeinde.

<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 24 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `allgemein-anschluss-router-workflow-chronologie` | Allgemein, Workflow Anschluss Skills Router, Workflow Chronologie Und Belegmatrix: Allgemein; Workflow Anschluss Skills Router; Workflow Chronologie Und Belegmatrix. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmus... |
| `anspruchslandkarte-bgb-aufforderungsschreiben-nachbar` | Anspruchslandkarte Bgb Nachbarrecht, Aufforderungsschreiben Nachbar, Beweissicherung Ortstermin Fotos: Anspruchslandkarte Bgb Nachbarrecht; Aufforderungsschreiben Nachbar; Beweissicherung Ortstermin Fotos. Führt Intake, Prüfroutine, Norm... |
| `aufforderung-beweise-red-grenzbaum` | Spezial Aufforderung Mandantenkommunikation Entscheidungsvorlage, Spezial Beweise Red Team Und Qualitaetskontrolle, Spezial Grenzbaum Schriftsatz Brief Und Memo Bausteine: Spezial Aufforderung Mandantenkommunikation Entscheidungsvorlage;... |
| `drohender-einsturz-einfriedung-zaun-einstweilige-verfuegung` | Drohender Einsturz Gefahranlage, Einfriedung Zaun Mauer Hecke, Einstweilige Verfuegung Und Klage: Drohender Einsturz Gefahranlage; Einfriedung Zaun Mauer Hecke; Einstweilige Verfuegung Und Klage. Führt Intake, Prüfroutine, Normen-/Quelle... |
| `fristennotiz-naechster-ueberbau-akten-grundstuecksaufnahme` | Spezial Prüfer Fristennotiz Und Naechster Schritt, Spezial Ueberbau Fristen Form Und Zustaendigkeit, Akten Und Grundstuecksaufnahme: Spezial Prüfer Fristennotiz Und Naechster Schritt; Spezial Ueberbau Fristen Form Und Zustaendigkeit; Akt... |
| `grenzbaum-grenzanlage-hammerschlags-leiterrecht-horrorfall` | Grenzbaum Und Grenzanlage, Hammerschlags Und Leiterrecht, Horrorfall Aktenauswertung: Grenzbaum Und Grenzanlage; Hammerschlags Und Leiterrecht; Horrorfall Aktenauswertung. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Out... |
| `hammerschlagsrecht-hecke-immissionen` | Spezial Hammerschlagsrecht Formular Portal Und Einreichung, Spezial Hecke Zahlen Schwellen Und Berechnung, Spezial Immissionen Compliance Dokumentation Und Akte: Spezial Hammerschlagsrecht Formular Portal Und Einreichung; Spezial Hecke Z... |
| `immissionen-laerm-landesnachbarrecht-nach-grenzbebauung` | Immissionen Laerm Geruch Rauch Licht, Landesnachbarrecht Router, Nach Grenzbebauung Ueberhang Spezial: Immissionen Laerm Geruch Rauch Licht; Landesnachbarrecht Router; Nach Grenzbebauung Ueberhang Spezial. Führt Intake, Prüfroutine, Norm... |
| `klage-beweislast-nachbarrecht-nachbarschaftsstreit` | Spezial Klage Beweislast Und Darlegungslast, Spezial Nachbarrecht Erstpruefung Und Mandatsziel, Spezial Nachbarschaftsstreit Tatbestand Beweis Und Belege: Spezial Klage Beweislast Und Darlegungslast; Spezial Nachbarrecht Erstpruefung Und... |
| `nach-laermimmissionen-mediation-vorrang-nachbarrechtsuebersicht` | Nach Laermimmissionen Spezial, Nach Mediation Vorrang Leitfaden, Nach Nachbarrechtsuebersicht Bauleiter: Nach Laermimmissionen Spezial; Nach Mediation Vorrang Leitfaden; Nach Nachbarrechtsuebersicht Bauleiter. Führt Intake, Prüfroutine,... |
| `nachbarrecht-kaltstart-triage` | Erstaufnahme eines Nachbarrechtsfalls: Beteiligte, Grundstücke, Bundesland, Grenze, Streitgegenstand, Gefahr, Fristen, Beweise, bisherige Eskalation und Ziel klären; danach in die passenden Spezialskills routen. |
| `notweg-ueberhang-sonderfall-edge` | Spezial Notweg Internationaler Bezug Und Schnittstellen, Spezial Ueberhang Dokumentenmatrix Und Lueckenliste, Spezial Vergleich Sonderfall Und Edge Case: Spezial Notweg Internationaler Bezug Und Schnittstellen; Spezial Ueberhang Dokument... |
| `notweg-zufahrt-selbsthilfe-eskalationsgrenzen-aeste` | Notweg Zufahrt Wegerecht, Selbsthilfe Und Eskalationsgrenzen, Spezial Aeste Risikoampel Und Gegenargumente: Notweg Zufahrt Wegerecht; Selbsthilfe Und Eskalationsgrenzen; Spezial Aeste Risikoampel Und Gegenargumente. Führt Intake, Prüfrou... |
| `spezial-kaltstart-abschlussprodukt-und-uebergabe` | Kaltstart: Abschlussprodukt und Übergabe im Plugin nachbarschaftsstreit pruefer; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Standardprüfung. |
| `spezial-mauer-livequellen-und-rechtsprechungscheck` | Mauer: Livequellen- und Rechtsprechungscheck im Plugin nachbarschaftsstreit pruefer; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Standardprüfung. |
| `ueberbau-ueberhang-aeste-mediation-nachbarschaftsfrieden` | Ueberbau Prüfung, Ueberhang Aeste Wurzeln, Vergleich Mediation Nachbarschaftsfrieden: Ueberbau Prüfung; Ueberhang Aeste Wurzeln; Vergleich Mediation Nachbarschaftsfrieden. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Out... |
| `vertiefung-baugrube` | Vertiefung Baugrube Stuetzverlust: Vertiefung Baugrube Stuetzverlust. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zusammen. |
| `vertiefung-interessen-wurzeln-zaun` | Spezial Vertiefung Mehrparteien Konflikt Und Interessen, Spezial Wurzeln Behörden Gericht Und Registerweg, Spezial Zaun Verhandlung Vergleich Und Eskalation: Spezial Vertiefung Mehrparteien Konflikt Und Interessen; Spezial Wurzeln Behörd... |
| `workflow-dokumentenintake` | Dokumentenintake im Plugin nachbarschaftsstreit-pruefer: liest Uploads, sortiert Dokumentarten, markiert Fristen und baut eine knappe Arbeitsakte. |
| `workflow-fristen-risikoampel-mandantenkommunikation-redteam` | Workflow Fristen Und Risikoampel, Workflow Mandantenkommunikation, Workflow Redteam Qualitygate: Workflow Fristen Und Risikoampel; Workflow Mandantenkommunikation; Workflow Redteam Qualitygate. Führt Intake, Prüfroutine, Normen-/Quellenr... |
| `workflow-kaltstart-und-routing` | Kaltstart und Routing im Plugin nachbarschaftsstreit-pruefer: führt vom ersten Satz oder Dokument in den passenden Arbeitsweg, erkennt Rolle, Ziel, Risiko und Anschluss-Skills. |
| `workflow-output-waehlen` | Output wählen im Plugin nachbarschaftsstreit-pruefer: entscheidet zwischen Memo, Schriftsatz, Tabelle, Brief, Checkliste, Vermerk, Redline oder Mandantenübersetzung. |
| `workflow-rechtsquellen-livecheck` | Rechtsquellen-Livecheck im Plugin nachbarschaftsstreit-pruefer: zwingt vor tragenden Aussagen zum aktuellen Quellencheck bei Gesetzen, Behörden, Gerichten und Formularen. |
| `workflow-unterlagen-lueckenliste` | Unterlagen- und Lückenliste im Plugin nachbarschaftsstreit-pruefer: erstellt eine präzise Nachforderungsliste statt allgemeiner Fragebögen. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
