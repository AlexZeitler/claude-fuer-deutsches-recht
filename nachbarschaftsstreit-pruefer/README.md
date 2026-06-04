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
| `kompendium-01-allgemein-bis-workflow-chronologie` | nachbarschaftsstreit-pruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Allgemein, Anschluss Skills Router, Chronologie Und Belegmatrix; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Quali... |
| `kompendium-02-workflow-fristen-und-bis-workflow-redteam-qua` | nachbarschaftsstreit-pruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Fristen Und Risikoampel, Mandantenkommunikation, Redteam Qualitygate; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und... |
| `kompendium-03-spezial-pruefer-fris-bis-akten-und-grundstuec` | nachbarschaftsstreit-pruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Pruefer Fristennotiz Und Naechster Schritt, Ueberbau Fristen Form Und Zustaendigkeit, Akten Und Grundstuecksaufnahme; mit Intake, Prüfroutine, Norm... |
| `kompendium-04-anspruchslandkarte-b-bis-beweissicherung-orts` | nachbarschaftsstreit-pruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Anspruchslandkarte Bgb Nachbarrecht, Aufforderungsschreiben Nachbar, Beweissicherung Ortstermin Fotos; mit Intake, Prüfroutine, Normen-/Quellenrada... |
| `kompendium-05-drohender-einsturz-g-bis-einstweilige-verfueg` | nachbarschaftsstreit-pruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Drohender Einsturz Gefahranlage, Einfriedung Zaun Mauer Hecke, Einstweilige Verfuegung Und Klage; mit Intake, Prüfroutine, Normen-/Quellenradar, Be... |
| `kompendium-06-grenzbaum-und-grenza-bis-horrorfall-aktenausw` | nachbarschaftsstreit-pruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Grenzbaum Und Grenzanlage, Hammerschlags Und Leiterrecht, Horrorfall Aktenauswertung; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, O... |
| `kompendium-07-immissionen-laerm-ge-bis-nach-grenzbebauung-u` | nachbarschaftsstreit-pruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Immissionen Laerm Geruch Rauch Licht, Landesnachbarrecht Router, Nach Grenzbebauung Ueberhang Spezial; mit Intake, Prüfroutine, Normen-/Quellenrada... |
| `kompendium-08-nach-laermimmissione-bis-nach-nachbarrechtsue` | nachbarschaftsstreit-pruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Nach Laermimmissionen Spezial, Nach Mediation Vorrang Leitfaden, Nach Nachbarrechtsuebersicht Bauleiter; mit Intake, Prüfroutine, Normen-/Quellenra... |
| `kompendium-09-notweg-zufahrt-weger-bis-spezial-aeste-risiko` | nachbarschaftsstreit-pruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Notweg Zufahrt Wegerecht, Selbsthilfe Und Eskalationsgrenzen, Aeste Risikoampel Und Gegenargumente; mit Intake, Prüfroutine, Normen-/Quellenradar,... |
| `kompendium-10-spezial-aufforderung-bis-spezial-grenzbaum-sc` | nachbarschaftsstreit-pruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Aufforderung Mandantenkommunikation Entscheidungsvorlage, Beweise Red Team Und Qualitaetskontrolle, Grenzbaum Schriftsatz Brief Und Memo Bausteine;... |
| `kompendium-11-spezial-hammerschlag-bis-spezial-immissionen` | nachbarschaftsstreit-pruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Hammerschlagsrecht Formular Portal Und Einreichung, Hecke Zahlen Schwellen Und Berechnung, Immissionen Compliance Dokumentation Und Akte; mit Intak... |
| `kompendium-12-spezial-klage-beweis-bis-spezial-nachbarschaf` | nachbarschaftsstreit-pruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Klage Beweislast Und Darlegungslast, Nachbarrecht Erstpruefung Und Mandatsziel, Nachbarschaftsstreit Tatbestand Beweis Und Belege; mit Intake, Prüf... |
| `kompendium-13-spezial-notweg-inter-bis-spezial-vergleich-so` | nachbarschaftsstreit-pruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Notweg Internationaler Bezug Und Schnittstellen, Ueberhang Dokumentenmatrix Und Lueckenliste, Vergleich Sonderfall Und Edge Case; mit Intake, Prüfr... |
| `kompendium-14-spezial-vertiefung-m-bis-spezial-zaun-verhand` | nachbarschaftsstreit-pruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Vertiefung Mehrparteien Konflikt Und Interessen, Wurzeln Behoerden Gericht Und Registerweg, Zaun Verhandlung Vergleich Und Eskalation; mit Intake,... |
| `kompendium-15-ueberbau-pruefung-bis-vergleich-mediation` | nachbarschaftsstreit-pruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Ueberbau Pruefung, Ueberhang Aeste Wurzeln, Vergleich Mediation Nachbarschaftsfrieden; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik,... |
| `kompendium-16-vertiefung-baugrube-bis-vertiefung-baugrube` | nachbarschaftsstreit-pruefer: eigenständiger Arbeits-Skill zu Vertiefung Baugrube Stuetzverlust; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck. |
| `nachbarrecht-kaltstart-triage` | Erstaufnahme eines Nachbarrechtsfalls: Beteiligte, Grundstücke, Bundesland, Grenze, Streitgegenstand, Gefahr, Fristen, Beweise, bisherige Eskalation und Ziel klären; danach in die passenden Spezialskills routen. |
| `spezial-kaltstart-abschlussprodukt-und-uebergabe` | Kaltstart: Abschlussprodukt und Übergabe im Plugin nachbarschaftsstreit pruefer; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Standardprüfung. |
| `spezial-mauer-livequellen-und-rechtsprechungscheck` | Mauer: Livequellen- und Rechtsprechungscheck im Plugin nachbarschaftsstreit pruefer; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Standardprüfung. |
| `workflow-dokumentenintake` | Dokumentenintake im Plugin nachbarschaftsstreit-pruefer: liest Uploads, sortiert Dokumentarten, markiert Fristen und baut eine knappe Arbeitsakte. |
| `workflow-kaltstart-und-routing` | Kaltstart und Routing im Plugin nachbarschaftsstreit-pruefer: führt vom ersten Satz oder Dokument in den passenden Arbeitsweg, erkennt Rolle, Ziel, Risiko und Anschluss-Skills. |
| `workflow-output-waehlen` | Output wählen im Plugin nachbarschaftsstreit-pruefer: entscheidet zwischen Memo, Schriftsatz, Tabelle, Brief, Checkliste, Vermerk, Redline oder Mandantenübersetzung. |
| `workflow-rechtsquellen-livecheck` | Rechtsquellen-Livecheck im Plugin nachbarschaftsstreit-pruefer: zwingt vor tragenden Aussagen zum aktuellen Quellencheck bei Gesetzen, Behörden, Gerichten und Formularen. |
| `workflow-unterlagen-lueckenliste` | Unterlagen- und Lückenliste im Plugin nachbarschaftsstreit-pruefer: erstellt eine präzise Nachforderungsliste statt allgemeiner Fragebögen. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
