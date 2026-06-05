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
| `anschluss-router` | Nutze dies, wenn Allgemein, Workflow Anschluss Skills Router, Workflow Chronologie Und Belegmatrix im Plugin Nachbarschaftsstreit Prüfer konkret bearbeitet werden soll. Auslöser: Bitte Allgemein, Workflow Anschluss Skills Router, Workflo... |
| `anspruchslandkarte-bgb-aufforderungsschreiben` | Nutze dies, wenn Anspruchslandkarte Bgb Nachbarrecht, Aufforderungsschreiben Nachbar, Beweissicherung Ortstermin Fotos im Plugin Nachbarschaftsstreit Prüfer konkret bearbeitet werden soll. Auslöser: Bitte Anspruchslandkarte Bgb Nachbarre... |
| `aufforderung-beweise-red-grenzbaum` | Nutze dies, wenn Spezial Aufforderung Mandantenkommunikation Entscheidungsvorlage, Spezial Beweise Red Team Und Qualitaetskontrolle, Spezial Grenzbaum Schriftsatz Brief Und Memo Bausteine im Plugin Nachbarschaftsstreit Prüfer konkret bea... |
| `dokumente-intake` | Nutze dies, wenn Dokumentenintake im Plugin Nachbarschaftsstreit Prüfer konkret bearbeitet werden soll. Auslöser: Ich lade Unterlagen hoch.; Was fehlt noch?; Bitte Dokumente sortieren.. |
| `drohender-einsturz-einfriedung-zaun` | Nutze dies, wenn Drohender Einsturz Gefahranlage, Einfriedung Zaun Mauer Hecke, Einstweilige Verfuegung Und Klage im Plugin Nachbarschaftsstreit Prüfer konkret bearbeitet werden soll. Auslöser: Bitte Drohender Einsturz Gefahranlage, Einf... |
| `einstieg-routing` | Nutze dies, wenn Einstieg und Routing im Plugin Nachbarschaftsstreit Prüfer konkret bearbeitet werden soll. Auslöser: Ich habe ein neues Thema im Bereich Nachbarschaftsstreit Prüfer.; Welche Unterlagen brauchen Sie?; Welcher Spezialskill... |
| `fristen-risikoampel-mandantenkommunikation` | Nutze dies, wenn Workflow Fristen Und Risikoampel, Workflow Mandantenkommunikation, Workflow Redteam Qualitygate im Plugin Nachbarschaftsstreit Prüfer konkret bearbeitet werden soll. Auslöser: Was kann hier schiefgehen?; Bitte red-team p... |
| `fristennotiz-naechster-ueberbau-akten` | Nutze dies, wenn Spezial Prüfer Fristennotiz Und Naechster Schritt, Spezial Ueberbau Fristen Form Und Zustaendigkeit, Akten Und Grundstuecksaufnahme im Plugin Nachbarschaftsstreit Prüfer konkret bearbeitet werden soll. Auslöser: Bitte Sp... |
| `grenzbaum-grenzanlage-hammerschlags` | Nutze dies, wenn Grenzbaum Und Grenzanlage, Hammerschlags Und Leiterrecht, Horrorfall Aktenauswertung im Plugin Nachbarschaftsstreit Prüfer konkret bearbeitet werden soll. Auslöser: Bitte Grenzbaum Und Grenzanlage, Hammerschlags Und Leit... |
| `hammerschlagsrecht-hecke-immissionen` | Nutze dies, wenn Spezial Hammerschlagsrecht Formular Portal Und Einreichung, Spezial Hecke Zahlen Schwellen Und Berechnung, Spezial Immissionen Compliance Dokumentation Und Akte im Plugin Nachbarschaftsstreit Prüfer konkret bearbeitet we... |
| `immissionen-laerm-landesnachbarrecht` | Nutze dies, wenn Immissionen Laerm Geruch Rauch Licht, Landesnachbarrecht Router, Nach Grenzbebauung Ueberhang Spezial im Plugin Nachbarschaftsstreit Prüfer konkret bearbeitet werden soll. Auslöser: Bitte Immissionen Laerm Geruch Rauch L... |
| `kaltstart-abschlussprodukt-und-uebergabe` | Nutze dies, wenn Kaltstart: Abschlussprodukt und Übergabe im Plugin Nachbarschaftsstreit Prüfer konkret bearbeitet werden soll. Auslöser: Ich habe ein neues Thema im Bereich Nachbarschaftsstreit Prüfer.; Welche Unterlagen brauchen Sie?;... |
| `klage-beweislast-nachbarrecht` | Nutze dies, wenn Spezial Klage Beweislast Und Darlegungslast, Spezial Nachbarrecht Erstpruefung Und Mandatsziel, Spezial Nachbarschaftsstreit Tatbestand Beweis Und Belege im Plugin Nachbarschaftsstreit Prüfer konkret bearbeitet werden so... |
| `laermimmissionen-mediation-vorrang` | Nutze dies, wenn Nach Laermimmissionen Spezial, Nach Mediation Vorrang Leitfaden, Nach Nachbarrechtsuebersicht Bauleiter im Plugin Nachbarschaftsstreit Prüfer konkret bearbeitet werden soll. Auslöser: Bitte Nach Laermimmissionen Spezial,... |
| `mauer-quellenkarte` | Nutze dies, wenn Mauer Quellenkarte im Plugin Nachbarschaftsstreit Prüfer konkret bearbeitet werden soll. Auslöser: Welche amtliche Quelle prüfe ich zuerst?; Gibt es aktuelle Rechtsprechung?; Bitte Fundstellen verifizieren.. |
| `nachbarrecht-kaltstart-triage` | Erstaufnahme eines Nachbarrechtsfalls: Beteiligte, Grundstücke, Bundesland, Grenze, Streitgegenstand, Gefahr, Fristen, Beweise, bisherige Eskalation und Ziel klären; danach in die passenden Spezialskills routen. |
| `notweg-ueberhang-sonderfall-edge` | Nutze dies, wenn Spezial Notweg Internationaler Bezug Und Schnittstellen, Spezial Ueberhang Dokumentenmatrix Und Lueckenliste, Spezial Vergleich Sonderfall Und Edge Case im Plugin Nachbarschaftsstreit Prüfer konkret bearbeitet werden sol... |
| `notweg-zufahrt-selbsthilfe-eskalationsgrenzen` | Nutze dies, wenn Notweg Zufahrt Wegerecht, Selbsthilfe Und Eskalationsgrenzen, Spezial Aeste Risikoampel Und Gegenargumente im Plugin Nachbarschaftsstreit Prüfer konkret bearbeitet werden soll. Auslöser: Bitte Notweg Zufahrt Wegerecht, S... |
| `output-waehlen` | Nutze dies, wenn Output wählen im Plugin Nachbarschaftsstreit Prüfer konkret bearbeitet werden soll. Auslöser: Bitte Output wählen prüfen.; Erstelle eine Arbeitsfassung zu Output wählen.; Welche Normen und Nachweise brauche ich?. |
| `quellen-livecheck` | Nutze dies, wenn Rechtsquellen-Livecheck im Plugin Nachbarschaftsstreit Prüfer konkret bearbeitet werden soll. Auslöser: Welche amtliche Quelle prüfe ich zuerst?; Gibt es aktuelle Rechtsprechung?; Bitte Fundstellen verifizieren.. |
| `ueberbau-ueberhang-aeste-mediation` | Nutze dies, wenn Ueberbau Prüfung, Ueberhang Aeste Wurzeln, Vergleich Mediation Nachbarschaftsfrieden im Plugin Nachbarschaftsstreit Prüfer konkret bearbeitet werden soll. Auslöser: Bitte Ueberbau Prüfung, Ueberhang Aeste Wurzeln, Vergle... |
| `unterlagen-luecken` | Nutze dies, wenn Unterlagen und Lücken im Plugin Nachbarschaftsstreit Prüfer konkret bearbeitet werden soll. Auslöser: Ich lade Unterlagen hoch.; Was fehlt noch?; Bitte Dokumente sortieren.. |
| `vertiefung-baugrube` | Nutze dies, wenn Vertiefung Baugrube Stuetzverlust im Plugin Nachbarschaftsstreit Prüfer konkret bearbeitet werden soll. Auslöser: Bitte Vertiefung Baugrube Stuetzverlust prüfen.; Erstelle eine Arbeitsfassung zu Vertiefung Baugrube Stuet... |
| `vertiefung-interessen-wurzeln-zaun` | Nutze dies, wenn Spezial Vertiefung Mehrparteien Konflikt Und Interessen, Spezial Wurzeln Behörden Gericht Und Registerweg, Spezial Zaun Verhandlung Vergleich Und Eskalation im Plugin Nachbarschaftsstreit Prüfer konkret bearbeitet werden... |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
