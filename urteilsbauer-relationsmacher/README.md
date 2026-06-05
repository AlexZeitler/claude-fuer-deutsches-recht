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
| `allgemein-workflow-chronologie-workflow-fristen` | Allgemein, Workflow Chronologie Und Belegmatrix, Workflow Fristen Und Risikoampel: Allgemein; Workflow Chronologie Und Belegmatrix; Workflow Fristen Und Risikoampel. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmus... |
| `amts-aktenintake-zivil-anspruchsgrundlagen` | Spezial Amts Fristen Form Und Zustaendigkeit, Aktenintake Zivil, Anspruchsgrundlagen Prüfen: Spezial Amts Fristen Form Und Zustaendigkeit; Aktenintake Zivil; Anspruchsgrundlagen Prüfen. Führt Intake, Prüfroutine, Normen-/Quellenradar, Be... |
| `berufungsfest-beschluss-bauen-beweisbeschluss-vorbereiten` | Berufungsfest Prüfen, Beschluss Bauen Zpo, Beweisbeschluss Vorbereiten: Berufungsfest Prüfen; Beschluss Bauen Zpo; Beweisbeschluss Vorbereiten. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck... |
| `beweiswuerdigung-richter-cisg-dsgvo-rechtswidriges` | Beweiswuerdigung Mit Richter Input, Cisg Prüfen, Dsgvo Rechtswidriges Produkt: Beweiswuerdigung Mit Richter Input; Cisg Prüfen; Dsgvo Rechtswidriges Produkt. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und... |
| `dokumente-rendern-urteil-docx` | Zivilurteil als DOCX im offiziellen Gerichtslayout rendern: Richter oder Referendar will fertiges Urteil als Dokument ausgeben. Normen: § 313 ZPO (Urteilsinhalt und -form). Prüfraster: Gerichtslayout (Aktenzeichen, Gerichtsbezeichnung, I... |
| `entscheidungsgruende-redaktion-familienrichter-input` | Spezial Entscheidungsgruende Redaktion, Spezial Familienrichter Risikoampel Und Gegenargumente, Spezial Input Compliance Dokumentation Und Akte: Spezial Entscheidungsgruende Redaktion; Spezial Familienrichter Risikoampel Und Gegenargumen... |
| `entscheidungsgruende-zivil-familienrichter-spezifika-incoterms` | Entscheidungsgruende Zivil Schreiben, Familienrichter Spezifika, Incoterms Und Gefahruebergang: Entscheidungsgruende Zivil Schreiben; Familienrichter Spezifika; Incoterms Und Gefahruebergang. Führt Intake, Prüfroutine, Normen-/Quellenrad... |
| `internationales-privatrecht-kollidierende-agb-kostenentscheidung` | Internationales Privatrecht, Kollidierende Agb Prüfen, Kostenentscheidung Bauen: Internationales Privatrecht; Kollidierende Agb Prüfen; Kostenentscheidung Bauen. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster... |
| `land-rechtspfleger-relation` | Spezial Land Dokumentenmatrix Und Lueckenliste, Spezial Rechtspfleger Behörden Gericht Und Registerweg, Spezial Relation Verhandlung Vergleich Und Eskalation: Spezial Land Dokumentenmatrix Und Lueckenliste; Spezial Rechtspfleger Behörden... |
| `rechtsmittelbelehrung-zivil-relation-zivil-revisionsfest` | Rechtsmittelbelehrung Zivil, Relation Zivil, Revisionsfest Prüfen: Rechtsmittelbelehrung Zivil; Relation Zivil; Revisionsfest Prüfen. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zusammen. |
| `richter-richterlicher-hinweis-spezial-tatbestand` | Spezial Richter Zahlen Schwellen Und Berechnung, Spezial Richterlicher Hinweis Und Aufklaerung, Spezial Tatbestand Formular Portal Und Einreichung: Spezial Richter Zahlen Schwellen Und Berechnung; Spezial Richterlicher Hinweis Und Aufkla... |
| `schulung-urteilsbauer-aktenintake-beschluss` | Schulung Urteilsbauer, Spezial Aktenintake Schriftsatz Brief Und Memo Bausteine, Spezial Beschluss Tatbestand Beweis Und Belege: Schulung Urteilsbauer; Spezial Aktenintake Schriftsatz Brief Und Memo Bausteine; Spezial Beschluss Tatbestan... |
| `spezial-beweiswuerdigung-livequellen-und-rechtsprechungscheck` | Beweiswuerdigung: Livequellen- und Rechtsprechungscheck im Plugin urteilsbauer relationsmacher; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Standardprüfung. |
| `spezial-entscheidungsgruende-red-team-und-qualitaetskontrolle` | Entscheidungsgruende: Red-Team und Qualitätskontrolle im Plugin urteilsbauer relationsmacher; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Standardprüfung. |
| `tatbestandsmerkmale-interessen-tenor-urteils` | Spezial Tatbestandsmerkmale Mehrparteien Konflikt Und Interessen, Spezial Tenor Internationaler Bezug Und Schnittstellen, Spezial Urteils Erstpruefung Und Mandatsziel: Spezial Tatbestandsmerkmale Mehrparteien Konflikt Und Interessen; Spe... |
| `urb-relationstechnik-urb-entscheidungsgruende-urb` | Urb Relationstechnik Bauleiter, Urb Tatbestand Entscheidungsgruende Leitfaden, Urb Versaeumnisurteil Einspruch Spezial: Urb Relationstechnik Bauleiter; Urb Tatbestand Entscheidungsgruende Leitfaden; Urb Versaeumnisurteil Einspruch Spezia... |
| `vollrelation-langfassung-vorlaeufige-vollstreckbarkeit` | Vollrelation Langfassung, Vorlaeufige Vollstreckbarkeit, Zulässigkeit Prüfen: Vollrelation Langfassung; Vorlaeufige Vollstreckbarkeit; Zulässigkeit Prüfen. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qu... |
| `workflow-anschluss-skills-router` | Anschluss-Skills Router im Plugin urteilsbauer-relationsmacher: schlägt nach der ersten Prüfung die passenden Spezialskills aus demselben Plugin vor. |
| `workflow-dokumentenintake` | Dokumentenintake im Plugin urteilsbauer-relationsmacher: liest Uploads, sortiert Dokumentarten, markiert Fristen und baut eine knappe Arbeitsakte. |
| `workflow-kaltstart-und-routing` | Kaltstart und Routing im Plugin urteilsbauer-relationsmacher: führt vom ersten Satz oder Dokument in den passenden Arbeitsweg, erkennt Rolle, Ziel, Risiko und Anschluss-Skills. |
| `workflow-output-waehlen` | Output wählen im Plugin urteilsbauer-relationsmacher: entscheidet zwischen Memo, Schriftsatz, Tabelle, Brief, Checkliste, Vermerk, Redline oder Mandantenübersetzung. |
| `workflow-rechtsquellen-livecheck` | Rechtsquellen-Livecheck im Plugin urteilsbauer-relationsmacher: zwingt vor tragenden Aussagen zum aktuellen Quellencheck bei Gesetzen, Behörden, Gerichten und Formularen. |
| `workflow-unterlagen-lueckenliste` | Unterlagen- und Lückenliste im Plugin urteilsbauer-relationsmacher: erstellt eine präzise Nachforderungsliste statt allgemeiner Fragebögen. |
| `zivil-schreiben-tenor-bauen-urb-mehrere` | Tatbestand Zivil Schreiben, Tenor Bauen Zivil, Urb Mehrere Streitgegenstaende Spezial: Tatbestand Zivil Schreiben; Tenor Bauen Zivil; Urb Mehrere Streitgegenstaende Spezial. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, O... |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
