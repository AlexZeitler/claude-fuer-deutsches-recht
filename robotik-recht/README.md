# robotik-recht

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`robotik-recht`) | [`robotik-recht.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/robotik-recht.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **Akte Vellbruck Robotics GmbH — Roboterflotte AtlasCare / LumaMove / Werkbank C7** (`robotikrecht-roboterflotte-vellbruck-muenchen`) | [Gesamt-PDF lesen](../testakten/robotikrecht-roboterflotte-vellbruck-muenchen/gesamt-pdf/robotikrecht-roboterflotte-vellbruck-muenchen_gesamt.pdf) | [`testakte-robotikrecht-roboterflotte-vellbruck-muenchen.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-robotikrecht-roboterflotte-vellbruck-muenchen.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

> Großes Robotik-Rechtsplugin für Deutschland und EU. Es führt von der ersten Produktbeschreibung über Rollenklärung, Maschinenverordnung, KI-VO, Produkthaftung, Datenschutz, Cybersecurity, Data Act, Marktüberwachung, Rückruf, Verträge und Streitfall bis zur verwertbaren anwaltlichen Ausgabe.

## Wofür dieses Plugin gedacht ist

Robotikrecht ist keine einzelne Norm. Ein physischer Roboter verbindet Maschine, Software, KI, Sensorik, Cloud, Daten, Arbeitsschutz, Produkthaftung und Vertrag. Dieses Plugin soll genau diesen Knoten lösen: schnell genug für den Kaltstart, tief genug für Produktfreigabe, Behördenkontakt und Haftungsstreit.

Typische Fälle:

- kollaborierende Roboter in Produktion und Lager,
- mobile AMR-/AGV-Flotten in Logistik und Krankenhaus,
- Service-, Pflege-, Haushalts- und Sozialroboter,
- Medizin-, Reha- und OP-Robotik,
- Roboter mit Kamera, Mikrofon, Lidar, Biometrie, Telemetrie oder Cloudsteuerung,
- Robot-as-a-Service, Wartung, Updates, Lieferkette und Rückruf,
- Unfall, Beinaheunfall, Cybervorfall, Datenschutzbeschwerde oder Marktüberwachung.

## Arbeitsstil

Der Einstiegsskill `allgemein` fragt nicht abstrakt nach allem, sondern baut sofort eine Arbeitskarte:

1. Rolle und Produkt.
2. Zweckbestimmung und tatsächliche Nutzung.
3. physisches Sicherheitsrisiko.
4. KI- und Softwarefunktion.
5. Daten- und Cyberlage.
6. Fristen, Behörden, Unfall oder Rückruf.
7. Zieloutput.

Danach werden die passenden Spezialskills vorgeschlagen. Das Plugin ist bewusst erweiternd: Es hilft Ingenieurinnen, Inhouse-Teams und Anwältinnen, die richtige Tiefe zu finden, ohne sie in ein starres Formular zu sperren.

## Quellenhygiene

- Normen werden aus amtlichen oder frei zugänglichen Quellen geprüft: EUR-Lex, Gesetze im Internet, Recht.Bund, BAuA, EU-Kommission und Gerichtsseiten.
- Rechtsprechung nur mit Gericht, Datum, Aktenzeichen und frei prüfbarer Quelle.
- Keine BeckRS-/juris-/Kommentar-Blindzitate.
- Technische Normen und harmonisierte Standards werden nicht geraten; Fundstelle, Fassung und Anwendbarkeit live prüfen.

## Kernmodule

- **Einstieg und Workflow:** Kaltstart, Rollenmatrix, Dokumentenintake, Rechtsregime-Matrix, Fristen, Outputwahl, Red-Team.
- **Produktsicherheit:** Maschinenverordnung, MaschinenDG, ProdSG/GPSR, CE, technische Dokumentation, Anleitung, Normen, Marktüberwachung.
- **KI-VO:** Art. 3, Art. 5, Art. 6, Anhang III, Sicherheitskomponenten, Provider-/Deployerpflichten, Human Oversight, Logging, Robustheit.
- **Produkthaftung:** ProdHaftG, neue EU-Produkthaftungsrichtlinie, Fehlerbegriff, Beweislast, Updates, digitale Dienste, Betreiber-Mitverschulden.
- **Datenschutz und Cyber:** Sensorik, DSFA, Beschäftigte, Biometrie, Data Act, CRA, SBOM, Schwachstellenmeldungen, NIS2-Schnittstellen.
- **Sektoren:** Industrie, Logistik, Pflege, Medizin, Haushalt, Kinder, Agrar, Bau, Sicherheit, öffentlicher Raum, Drohnen und Dual-Use.
- **Vertrag und Streit:** RaaS, Wartung, SLA, Lieferkette, Indemnity, Versicherung, Sachverständige, Besichtigung, Rückruf, Vergleich.

## Demonstrationsakte

Die Akte `robotikrecht-roboterflotte-vellbruck-muenchen` zeigt eine verdichtete Robotiklage: Vellbruck Robotics GmbH bringt eine Cobot-/AMR-Flotte, einen Pflegepiloten und eine Cloudsteuerung in den Markt. Es gibt Unfall, Softwareupdate, Marktüberwachung, Datenschutzbeschwerde, Cyber-Schwachstelle, MDR-Nähe, Betreiberfehler, Lieferantenstreit und Versicherungsdruck. Die Akte ist als unordentlicher Datenraum angelegt und hat zusätzlich ein Gesamt-PDF.

## Pflichtdisclaimer für externe Outputs

Jede externe Ausgabe soll knapp klarstellen: KI-gestützte Vorprüfung; keine amtliche Konformitätsbewertung; technische und regulatorische Bewertung hängen von vollständigen Unterlagen, aktuellem Normenstand und Live-Quellenprüfung ab.

## Lizenz

Apache-2.0 OR MIT. Siehe Repository-Stammverzeichnis.


<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 46 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `allgemein` | Robotik-Recht-Kompass für Deutschland und EU: Einstieg, Rollenklärung, Produktklassifizierung, Maschinenverordnung, KI-VO, Produkthaftung, Datenschutz, Cybersecurity, Marktüberwachung und passende Spezialskills. |
| `komp-06-teil-02-wartungs-und-servicevertrag-robotik` | robotik-recht: eigenständiger Arbeits-Skill für sachlich zusammengehörige Arbeitsmodule zu Wartungs Und Servicevertrag Robotik, Beweislast Und Offenlegung Produkthaftung; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Output... |
| `komp-07-teil-02-cra-produkt-mit-digitalen-elementen` | robotik-recht: eigenständiger Arbeits-Skill für sachlich zusammengehörige Arbeitsmodule zu Cra Produkt Mit Digitalen Elementen, Lager Und Intralogistikflotte; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Q... |
| `komp-08-teil-02-arbeitsschutz-betrsichv-robotik` | robotik-recht: eigenständiger Arbeits-Skill für sachlich zusammengehörige Arbeitsmodule zu Arbeitsschutz Betrsichv Robotik, Autonome Lieferroboter Oeffentlicher Raum; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmust... |
| `komp-09-teil-02-betreiber-mitverschulden-und-fehlbedienung` | robotik-recht: eigenständiger Arbeits-Skill für sachlich zusammengehörige Arbeitsmodule zu Betreiber Mitverschulden Und Fehlbedienung, Betriebsanleitung Sprache Und Warnhinweise; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik... |
| `komp-10-teil-02-datenminimierung-edge-cloud` | robotik-recht: eigenständiger Arbeits-Skill für sachlich zusammengehörige Arbeitsmodule zu Datenminimierung Edge Cloud, Datensatzqualitaet Und Bias Hri; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitä... |
| `komp-11-teil-02-dual-use-und-militaerische-robotik` | robotik-recht: eigenständiger Arbeits-Skill für sachlich zusammengehörige Arbeitsmodule zu Dual Use Und Militaerische Robotik, Eu De Umsetzung Und Rechtsstand Livecheck; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputm... |
| `komp-12-teil-02-geschaeftsgeheimnisse-und-logdaten` | robotik-recht: eigenständiger Arbeits-Skill für sachlich zusammengehörige Arbeitsmodule zu Geschaeftsgeheimnisse Und Logdaten, Grundrechte Und Psychische Belastung; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster... |
| `komp-13-teil-02-ki-vo-anhang-iii-robotik-usecases` | robotik-recht: eigenständiger Arbeits-Skill für sachlich zusammengehörige Arbeitsmodule zu Ki Vo Anhang Iii Robotik Usecases, Ki Vo Artikel 3 Ki System Robotik; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und... |
| `komp-15-teil-02-lieferantenqualifizierung-sensor-cloud` | robotik-recht: eigenständiger Arbeits-Skill für sachlich zusammengehörige Arbeitsmodule zu Lieferantenqualifizierung Sensor Cloud, Lieferantenregress Und Indemnity; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster... |
| `komp-16-teil-02-medizinprodukt-software-ki-roboter` | robotik-recht: eigenständiger Arbeits-Skill für sachlich zusammengehörige Arbeitsmodule zu Medizinprodukt Software Ki Roboter, Mitbestimmung Betriebsrat Robotik; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster un... |
| `komp-17-teil-02-pilotbetrieb-und-beta-robotik` | robotik-recht: eigenständiger Arbeits-Skill für sachlich zusammengehörige Arbeitsmodule zu Pilotbetrieb Und Beta Robotik, Prodhaftg Und Neue Pld Vergleich; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qual... |
| `komp-18-teil-02-produktsicherheitsrechtliche-werbung` | robotik-recht: eigenständiger Arbeits-Skill für sachlich zusammengehörige Arbeitsmodule zu Produktsicherheitsrechtliche Werbung, Quasihersteller Private Label Robotik; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmus... |
| `komp-19-teil-02-rueckrufpflicht-und-safety-gate` | robotik-recht: eigenständiger Arbeits-Skill für sachlich zusammengehörige Arbeitsmodule zu Rueckrufpflicht Und Safety Gate, Safety Gate Und Oeffentliche Warnung; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster un... |
| `komp-20-teil-02-smart-factory-und-industrie-4-0` | robotik-recht: eigenständiger Arbeits-Skill für sachlich zusammengehörige Arbeitsmodule zu Smart Factory Und Industrie 4 0, Softwareupdate Als Produktbezogener Dienst; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmus... |
| `komp-21-teil-02-technische-besichtigung-und-geheimnisschutz` | robotik-recht: eigenständiger Arbeits-Skill für sachlich zusammengehörige Arbeitsmodule zu Technische Besichtigung Und Geheimnisschutz, Testdaten Und Validierung Vor Marktstart; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik,... |
| `komp-22-teil-02-vernunftigerweise-vorhersehbarer-gebrauch` | robotik-recht: eigenständiger Arbeits-Skill für sachlich zusammengehörige Arbeitsmodule zu Vernunftigerweise Vorhersehbarer Gebrauch, Versicherungsdeckung Robotik; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster... |
| `kompendium-01-workflow-arbeitswelt-bis-workflow-ce-akte-und` | robotik-recht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Arbeitswelt Cobot Check, Beschaffung Oeffentlich Privat, Betreiberpflichten Und Training, Beweismatrix Und Logauswertung und 2 weitere Arbeitsmodule; mit Intake,... |
| `kompendium-02-workflow-datenschutz-bis-workflow-internation` | robotik-recht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Datenschutz Cyber Intake, First Year Associate Robotik, Fristen Und Uebergangsrecht, Haftungsampel und 2 weitere Arbeitsmodule; mit Intake, Prüfroutine, Normen-/Q... |
| `kompendium-03-workflow-ki-vo-integ-bis-workflow-normen-und` | robotik-recht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Ki Vo Integrationscheck, Laienmodus Robotikrecht, Litigation Vorbereitung, Marktueberwachung Dialog und 2 weitere Arbeitsmodule; mit Intake, Prüfroutine, Normen-/... |
| `kompendium-04-workflow-open-source-bis-workflow-rechtsregim` | robotik-recht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Open Source Und Sbom, Post Market Monitoring, Presse Und Krisenkommunikation, Privacy By Design Sprint und 2 weitere Arbeitsmodule; mit Intake, Prüfroutine, Norme... |
| `kompendium-05-workflow-risikoklass-bis-workflow-update-und` | robotik-recht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Risikoklassifizierung Schnelltest, Rueckruf Und Field Action, Sachverstaendigenbriefing, Security By Design Sprint und 2 weitere Arbeitsmodule; mit Intake, Prüfro... |
| `kompendium-06-workflow-versicherun-bis-beweislast-und-offen` | robotik-recht: eigenständiger Arbeits-Skill für sachlich zusammengehörige Arbeitsmodule zu Workflow Versicherungs Und Regressakte, Workflow Vertrags Und Lieferkettenintake, Workflow Zweckbestimmung Und Usecase, Robot As A Service Vertrag... |
| `kompendium-07-datenverlust-und-dig-bis-lager-und-intralogis` | robotik-recht: eigenständiger Arbeits-Skill für sachlich zusammengehörige Arbeitsmodule zu Datenverlust Und Digitaler Schaden, Deliktische Haftung Paragraph 823 Bgb, Haftung Arzt Klinik Hersteller, Schadensberechnung Produktionsausfall;... |
| `kompendium-08-qualitaetsmanagement-bis-autonome-lieferrobot` | robotik-recht: eigenständiger Arbeits-Skill für sachlich zusammengehörige Arbeitsmodule zu Qualitaetsmanagement Robotikhersteller, Accuracy Robustness Cybersecurity Ai, Agile Entwicklung Und Compliance Gates, Anwaltliche Quellenhygiene R... |
| `kompendium-09-barrierefreiheit-und-bis-betriebsanleitung-sp` | robotik-recht: eigenständiger Arbeits-Skill für sachlich zusammengehörige Arbeitsmodule zu Barrierefreiheit Und Inklusion Robotik, Batterie Ladeinfrastruktur Und Brandschutz, Bau Und Inspektionsroboter, Beschaeftigtendatenschutz Cobot; m... |
| `kompendium-10-biometrie-emotion-un-bis-datensatzqualitaet-u` | robotik-recht: eigenständiger Arbeits-Skill für sachlich zusammengehörige Arbeitsmodule zu Biometrie Emotion Und Personenerkennung, Ce Zeichen Fehlgebrauch Und Abmahnung, Chirurgie Und Op Robotik, Data Act Roboterdaten; mit Intake, Prüfr... |
| `kompendium-11-datenschutz-kameras-bis-eu-de-umsetzung-und` | robotik-recht: eigenständiger Arbeits-Skill für sachlich zusammengehörige Arbeitsmodule zu Datenschutz Kameras Und Sensorik, Digitaler Zwilling Und Simulation, Dronen Und Robotik Schnittstelle, Dsfa Fuer Robotik; mit Intake, Prüfroutine,... |
| `kompendium-12-eu-konformitaetserkl-bis-grundrechte-und-psyc` | robotik-recht: eigenständiger Arbeits-Skill für sachlich zusammengehörige Arbeitsmodule zu Eu Konformitaetserklaerung Und Einbauerklaerung, Foss Und Open Source Komponenten, Foundation Model Und Gpai Im Roboter, Funkanlagen Und Konnektiv... |
| `kompendium-13-harmonisierte-normen-bis-ki-vo-artikel-3-ki-s` | robotik-recht: eigenständiger Arbeits-Skill für sachlich zusammengehörige Arbeitsmodule zu Harmonisierte Normen Iso Ts 15066, Human Oversight In Physischer Robotik, Importeur Haendler Fulfilment Robotik, Ki Training Mit Roboterdaten; mit... |
| `kompendium-14-ki-vo-artikel-6-hoch-bis-kollaborierende-robo` | robotik-recht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Ki Vo Artikel 6 Hochrisiko Robotik, Ki Vo Deployer Pflichten Robotik, Ki Vo Provider Qms Und Risk Management, Ki Vo Verbotene Praktiken Robotik und 2 weitere Arbe... |
| `kompendium-15-kommunal-und-behoerd-bis-lieferantenregress-u` | robotik-recht: eigenständiger Arbeits-Skill für sachlich zusammengehörige Arbeitsmodule zu Kommunal Und Behoerdenrobotik, Konformitaetsbescheinigung Robotik Ki, Konformitaetsbewertung Modulwahl, Landwirtschaftsroboter Und Autonome Feldte... |
| `kompendium-16-logging-und-traceabi-bis-mitbestimmung-betrie` | robotik-recht: eigenständiger Arbeits-Skill für sachlich zusammengehörige Arbeitsmodule zu Logging Und Traceability Robotik, Marktueberwachung Unterlagenvorlage, Maschine Oder Unvollstaendige Maschine, Maschinenverordnung Annex Iii Hochr... |
| `kompendium-17-mobile-roboter-amr-a-bis-prodhaftg-und-neue-p` | robotik-recht: eigenständiger Arbeits-Skill für sachlich zusammengehörige Arbeitsmodule zu Mobile Roboter Amr Agv, Nis2 Betreiber Kritische Sektoren, Patientenaufklaerung Robotik, Pflege Und Assistenzroboter; mit Intake, Prüfroutine, Nor... |
| `kompendium-18-produktakte-gap-anal-bis-quasihersteller-priv` | robotik-recht: eigenständiger Arbeits-Skill für sachlich zusammengehörige Arbeitsmodule zu Produktakte Gap Analyse, Produktbeobachtung Und Field Data, Produktfehler Verbrauchererwartung Robotik, Produktsicherheit Vs Betriebssicherheit; m... |
| `kompendium-19-rehabilitations-und-bis-safety-gate-und-oeff` | robotik-recht: eigenständiger Arbeits-Skill für sachlich zusammengehörige Arbeitsmodule zu Rehabilitations Und Exoskelett Robotik, Remote Update Und Secure Channel, Risikobeurteilung En Iso 12100, Rollen Hersteller Anbieter Integrator; m... |
| `kompendium-20-sbom-und-cyber-dokum-bis-softwareupdate-als-p` | robotik-recht: eigenständiger Arbeits-Skill für sachlich zusammengehörige Arbeitsmodule zu Sbom Und Cyber Dokumentation, Serviceroboter Haushalt Gpsr, Sicherheits Und Ueberwachungsroboter, Sicherheitskomponente Mit Ki; mit Intake, Prüfro... |
| `kompendium-21-sozialer-humanoider-bis-testdaten-und-validi` | robotik-recht: eigenständiger Arbeits-Skill für sachlich zusammengehörige Arbeitsmodule zu Sozialer Humanoider Roboter, Spielzeug Und Kinderroboter, Strom Emv Und Niederspannung, Systemintegrator Als Hersteller; mit Intake, Prüfroutine,... |
| `kompendium-22-transparenz-und-nutz-bis-versicherungsdeckung` | robotik-recht: eigenständiger Arbeits-Skill für sachlich zusammengehörige Arbeitsmodule zu Transparenz Und Nutzerinformation, Unfallanalyse Chain Of Custody, Vergaberecht Robotik Beschaffung, Vergleich Und Sanierung Nach Incident; mit In... |
| `kompendium-23-vigilanz-medizinrobo-bis-zweckbestimmung-enge` | robotik-recht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Vigilanz Medizinrobotik, Vulnerability Disclosure Und Reporting, Wesentliche Veraenderung Digital, Zweckbestimmung Enge Nutzungsbedingungen; mit Intake, Prüfrouti... |
| `workflow-abschlussqualitaet-und-redteam` | Red-Team-Check für jedes Ergebnis: Normenstand, Quellen, fehlende Tatsachen, Gegenargumente, technische Annahmen, Datenschutz und Haftungsfolgen. |
| `workflow-anschluss-skills-router` | Schlägt nach jeder Robotikprüfung passende Anschlussplugins vor: KI-VO, Datenschutz, IT-Recht, Arbeitsrecht, Medizinrecht, Produkthaftung, Vertragsrecht und Prozess. |
| `workflow-dokumentenintake-datenraum` | Liest Robotik-Datenräume mit Anleitungen, CE-Unterlagen, Risikobeurteilung, Logs, Verträgen, Incident Reports und ordnet die nächsten Prüfschritte. |
| `workflow-gutachten-memo-output` | Wählt den passenden Output: Kurzvermerk, Vorstandsvorlage, Gutachten, Behördenantwort, Rückrufplan, Vertragsredline, Klageskizze oder Counsel-Briefing. |
| `workflow-human-robot-interaction-redteam` | Prüft besondere Mensch-Roboter-Interaktion: Nähe, Vertrauen, Manipulation, psychische Belastung, vulnerable Nutzer und klare Grenzen. |
| `workflow-kaltstart-und-routing` | Kaltstart für jedes Robotikmandat: sortiert Produkt, Rolle, Ziel, Frist, Risiko, Rechtsregime und schlägt sofort die passenden Skills im Robotik-Recht-Plugin vor. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
