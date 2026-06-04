# Urteilsbauer und Relationsmacher

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`urteilsbauer-relationsmacher`) | [`urteilsbauer-relationsmacher.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/urteilsbauer-relationsmacher.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **Solis Vision X Smartglasses** (`solis-vision-x-smartglasses`) | [Gesamt-PDF lesen](../testakten/solis-vision-x-smartglasses/gesamt-pdf/solis-vision-x-smartglasses_gesamt.pdf) | [`testakte-solis-vision-x-smartglasses.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-solis-vision-x-smartglasses.zip) |
| **Werklohnklage Radarwarner GmbH ./. Schreinmoor Bauträger AG — Rohbaumängel Wohnanlage Spreebogen Plagwitz, Hilfsaufrechnung, Beweiswürdigung SV-Gutachten, Urteil § 313 ZPO** (`urteilsbau-zivilkammer-leipzig-werklohn-radarwarner-relation-mit-beweiswuerdigung-und-urteil`) | [Gesamt-PDF lesen](../testakten/urteilsbau-zivilkammer-leipzig-werklohn-radarwarner-relation-mit-beweiswuerdigung-und-urteil/gesamt-pdf/urteilsbau-zivilkammer-leipzig-werklohn-radarwarner-relation-mit-beweiswuerdigung-und-urteil_gesamt.pdf) | [`testakte-urteilsbau-zivilkammer-leipzig-werklohn-radarwarner-relation-mit-beweiswuerdigung-und-urteil.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-urteilsbau-zivilkammer-leipzig-werklohn-radarwarner-relation-mit-beweiswuerdigung-und-urteil.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

Technischer Plugin-Name: `urteilsbauer-relationsmacher`.

Freistehendes Plugin für **Amts-, Land- und Familienrichter sowie Rechtspfleger**. Begleitet von der Aktenintake über die Relation und die Beweiswürdigung mit Richter-Input bis zum fertigen Urteil oder Beschluss inklusive Tenor, Tatbestand, Entscheidungsgründen, Kosten- und Rechtsmittelbelehrung. Erzeugt am Ende ein DOCX nach § 313 ZPO.

## Installation

1. Claude Code oder Claude Desktop/Cowork öffnen.
2. **Customize Plugins** bzw. **Personal plugins** wählen.
3. **Install from .zip** und `urteilsbauer-relationsmacher.zip` hochladen.
4. Mit einem konkreten Auftrag starten, zum Beispiel: `Starte die Relation fuer eine Werklohnklage. Akte liegt vor.`

Alternativ via Marketplace:

```
/plugin marketplace add Klotzkette/claude-fuer-deutsches-recht
/plugin install urteilsbauer-relationsmacher@claude-fuer-deutsches-recht
```

Nicht das komplette Repository-ZIP hochladen. Das Plugin-ZIP muss im Root direkt `.claude-plugin/plugin.json` und `skills/` enthalten.

## Skill-Landkarte

| Skill | Zweck |
| --- | --- |
| `aktenintake-zivil` | Erfasst Parteien, Anträge, Sachverhalt, Streitwert, Anlagen und Lage. |
| `zulaessigkeit-pruefen` | Pruft Statthaftigkeit, Zuständigkeit, Partei- und Prozessfähigkeit, Rechtsschutzbedürfnis. |
| `relation-zivil` | Baut Relation aus Klagegrund und Verteidigung mit Streitstand und Beweislage. |
| `vollrelation-langfassung` | Liefert die ausführliche Vollrelation mit Hilfserwaegungen und Eventualbegründung. |
| `anspruchsgrundlagen-pruefen` | Identifiziert und subsumiert die einschlaegigen Anspruchsgrundlagen. |
| `kollidierende-agb-pruefen` | Loest AGB-Konflikt nach Restguelitgkeits- und Knock-out-Doktrin. |
| `cisg-pruefen` | Pruft CISG-Anwendbarkeit, Anspruechs- und Aufrechnungslage. |
| `internationales-privatrecht` | Klärt anwendbares Recht nach Rom I/II und nationalem IPR. |
| `incoterms-und-gefahruebergang` | Wendet Incoterms 2020 auf Gefahrübergang und Transportkosten an. |
| `dsgvo-rechtswidriges-produkt` | Beurteilt DSGVO-Verstöße durch Produkte mit Datenverarbeitung. |
| `familienrichter-spezifika` | Familienrechtliche Besonderheiten: FamFG-Verfahren, Anhörungspflicht, Vergleichsdruck. |
| `beweisbeschluss-vorbereiten` | Formuliert Beweisthemen, Beweismittel und Beweisanordnung. |
| `beweiswuerdigung-mit-richter-input` | Holt Richter-Input zu Glaubwürdigkeit ein und baut Beweiswürdigung. |
| `tatbestand-zivil-schreiben` | Verfasst Tatbestand mit unstreitigem und streitigem Sachverhalt und Anträgen. |
| `entscheidungsgruende-zivil-schreiben` | Baut Entscheidungsgründe mit Subsumtion und juristischer Begründung. |
| `tenor-bauen-zivil` | Erstellt Tenor mit Hauptsache, Kosten, vorläufiger Vollstreckbarkeit. |
| `kostenentscheidung-bauen` | Berechnet Kostenquote nach §§ 91 ff. ZPO inklusive Vergleichswerten. |
| `vorlaeufige-vollstreckbarkeit` | Setzt Sicherheitsleistung und Abwendungsbefugnis nach §§ 708 ff. ZPO. |
| `rechtsmittelbelehrung-zivil` | Erzeugt korrekte Rechtsmittelbelehrung für Berufung, Beschwerde, Revision. |
| `beschluss-bauen-zpo` | Baut Beschlüsse statt Urteilen, etwa bei einstweiligem Rechtsschutz oder Streitwertfestsetzung. |
| `berufungsfest-pruefen` | Pruft das Urteil auf Berufungsfestigkeit und typische Aufhebungsgründe. |
| `revisionsfest-pruefen` | Pruft Urteil auf revisionsrechtliche Schwachstellen. |
| `dokumente-rendern-urteil-docx` | Rendert das fertige Urteil als DOCX nach § 313 ZPO. |
| `schulung-urteilsbauer` | Trainingsskill zur Einarbeitung neuer Richter und Rechtspfleger. |

## Typische Workflows

- Aktenintake -> Zulässigkeit -> Relation -> Anspruchsgrundlagen -> Beweisbeschluss.
- Beweiswürdigung mit Richter-Input -> Tatbestand -> Entscheidungsgründe -> Tenor.
- Kostenentscheidung -> Vorläufige Vollstreckbarkeit -> Rechtsmittelbelehrung.
- Berufungs-/Revisionsfestigkeit -> DOCX-Rendering nach § 313 ZPO.

## Haftung

Dieses Plugin ist ein Arbeitswerkzeug für die richterliche Praxis. Es ersetzt keine eigene rechtliche Prüfung und keine Beratung durch zugelassene Rechtsanwälte. Die Verantwortung für Tenor, Tatbestand und Entscheidungsgründe bleibt beim Spruchkoerper.

<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 24 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `dokumente-rendern-urteil-docx` | Zivilurteil als DOCX im offiziellen Gerichtslayout rendern: Richter oder Referendar will fertiges Urteil als Dokument ausgeben. Normen: § 313 ZPO (Urteilsinhalt und -form). Prüfraster: Gerichtslayout (Aktenzeichen, Gerichtsbezeichnung, I... |
| `kompendium-01-allgemein-bis-workflow-fristen-und` | urteilsbauer-relationsmacher: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Allgemein, Chronologie Und Belegmatrix, Fristen Und Risikoampel; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Quali... |
| `kompendium-02-spezial-amts-fristen-bis-anspruchsgrundlagen` | urteilsbauer-relationsmacher: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Amts Fristen Form Und Zustaendigkeit, Aktenintake Zivil, Anspruchsgrundlagen Pruefen; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, O... |
| `kompendium-03-berufungsfest-pruefe-bis-beweisbeschluss-vorb` | urteilsbauer-relationsmacher: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Berufungsfest Pruefen, Beschluss Bauen Zpo, Beweisbeschluss Vorbereiten; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster u... |
| `kompendium-04-beweiswuerdigung-mit-bis-dsgvo-rechtswidriges` | urteilsbauer-relationsmacher: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Beweiswuerdigung Mit Richter Input, Cisg Pruefen, Dsgvo Rechtswidriges Produkt; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputm... |
| `kompendium-05-entscheidungsgruende-bis-incoterms-und-gefahr` | urteilsbauer-relationsmacher: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Entscheidungsgruende Zivil Schreiben, Familienrichter Spezifika, Incoterms Und Gefahruebergang; mit Intake, Prüfroutine, Normen-/Quellenradar, Bewe... |
| `kompendium-06-internationales-priv-bis-kostenentscheidung-b` | urteilsbauer-relationsmacher: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Internationales Privatrecht, Kollidierende Agb Pruefen, Kostenentscheidung Bauen; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outpu... |
| `kompendium-07-rechtsmittelbelehrun-bis-revisionsfest-pruefe` | urteilsbauer-relationsmacher: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Rechtsmittelbelehrung Zivil, Relation Zivil, Revisionsfest Pruefen; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qu... |
| `kompendium-08-schulung-urteilsbaue-bis-spezial-beschluss-ta` | urteilsbauer-relationsmacher: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Schulung Urteilsbauer, Aktenintake Schriftsatz Brief Und Memo Bausteine, Beschluss Tatbestand Beweis Und Belege; mit Intake, Prüfroutine, Normen-/Q... |
| `kompendium-09-spezial-entscheidung-bis-spezial-input-compli` | urteilsbauer-relationsmacher: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Entscheidungsgruende Redaktion, Familienrichter Risikoampel Und Gegenargumente, Input Compliance Dokumentation Und Akte; mit Intake, Prüfroutine, N... |
| `kompendium-10-spezial-land-dokumen-bis-spezial-relation-ver` | urteilsbauer-relationsmacher: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Land Dokumentenmatrix Und Lueckenliste, Rechtspfleger Behoerden Gericht Und Registerweg, Relation Verhandlung Vergleich Und Eskalation; mit Intake,... |
| `kompendium-11-spezial-richter-zahl-bis-spezial-tatbestand-f` | urteilsbauer-relationsmacher: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Richter Zahlen Schwellen Und Berechnung, Richterlicher Hinweis Und Aufklaerung, Tatbestand Formular Portal Und Einreichung; mit Intake, Prüfroutine... |
| `kompendium-12-spezial-tatbestandsm-bis-spezial-urteils-erst` | urteilsbauer-relationsmacher: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Tatbestandsmerkmale Mehrparteien Konflikt Und Interessen, Tenor Internationaler Bezug Und Schnittstellen, Urteils Erstpruefung Und Mandatsziel; mit... |
| `kompendium-13-tatbestand-zivil-sch-bis-urb-mehrere-streitge` | urteilsbauer-relationsmacher: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Tatbestand Zivil Schreiben, Tenor Bauen Zivil, Urb Mehrere Streitgegenstaende Spezial; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik,... |
| `kompendium-14-urb-relationstechnik-bis-urb-versaeumnisurtei` | urteilsbauer-relationsmacher: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Urb Relationstechnik Bauleiter, Urb Tatbestand Entscheidungsgruende Leitfaden, Urb Versaeumnisurteil Einspruch Spezial; mit Intake, Prüfroutine, No... |
| `kompendium-15-vollrelation-langfas-bis-zulaessigkeit-pruefe` | urteilsbauer-relationsmacher: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Vollrelation Langfassung, Vorlaeufige Vollstreckbarkeit, Zulaessigkeit Pruefen; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputm... |
| `spezial-beweiswuerdigung-livequellen-und-rechtsprechungscheck` | Beweiswuerdigung: Livequellen- und Rechtsprechungscheck im Plugin urteilsbauer relationsmacher; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Standardprüfung. |
| `spezial-entscheidungsgruende-red-team-und-qualitaetskontrolle` | Entscheidungsgruende: Red-Team und Qualitätskontrolle im Plugin urteilsbauer relationsmacher; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Standardprüfung. |
| `workflow-anschluss-skills-router` | Anschluss-Skills Router im Plugin urteilsbauer-relationsmacher: schlägt nach der ersten Prüfung die passenden Spezialskills aus demselben Plugin vor. |
| `workflow-dokumentenintake` | Dokumentenintake im Plugin urteilsbauer-relationsmacher: liest Uploads, sortiert Dokumentarten, markiert Fristen und baut eine knappe Arbeitsakte. |
| `workflow-kaltstart-und-routing` | Kaltstart und Routing im Plugin urteilsbauer-relationsmacher: führt vom ersten Satz oder Dokument in den passenden Arbeitsweg, erkennt Rolle, Ziel, Risiko und Anschluss-Skills. |
| `workflow-output-waehlen` | Output wählen im Plugin urteilsbauer-relationsmacher: entscheidet zwischen Memo, Schriftsatz, Tabelle, Brief, Checkliste, Vermerk, Redline oder Mandantenübersetzung. |
| `workflow-rechtsquellen-livecheck` | Rechtsquellen-Livecheck im Plugin urteilsbauer-relationsmacher: zwingt vor tragenden Aussagen zum aktuellen Quellencheck bei Gesetzen, Behörden, Gerichten und Formularen. |
| `workflow-unterlagen-lueckenliste` | Unterlagen- und Lückenliste im Plugin urteilsbauer-relationsmacher: erstellt eine präzise Nachforderungsliste statt allgemeiner Fragebögen. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
