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
| `arbeitsschutz-betrsichv-autonome-lieferroboter` | Arbeitsschutz Betrsichv Robotik, Autonome Lieferroboter Oeffentlicher Raum: Arbeitsschutz Betrsichv Robotik; Autonome Lieferroboter Oeffentlicher Raum. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualit... |
| `arbeitswelt-cobot-beschaffung-oeffentlich-betreiberpflichten` | Workflow Arbeitswelt Cobot Check, Workflow Beschaffung Öffentlich Privat, Workflow Betreiberpflichten Und Training, Workflow Beweismatrix Und Logauswertung, Workflow Board Und C Level Briefing und 1 weitere Themen: Workflow Arbeitswelt C... |
| `barrierefreiheit-inklusion-batterie-ladeinfrastruktur-bau` | Barrierefreiheit Und Inklusion Robotik, Batterie Ladeinfrastruktur Und Brandschutz, Bau Und Inspektionsroboter, Beschaeftigtendatenschutz Cobot: Barrierefreiheit Und Inklusion Robotik; Batterie Ladeinfrastruktur Und Brandschutz; Bau Und... |
| `betreiber-mitverschulden-betriebsanleitung-sprache` | Betreiber Mitverschulden Und Fehlbedienung, Betriebsanleitung Sprache Und Warnhinweise: Betreiber Mitverschulden Und Fehlbedienung; Betriebsanleitung Sprache Und Warnhinweise. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik,... |
| `biometrie-emotion-ce-zeichen-chirurgie-op-data-act` | Biometrie Emotion Und Personenerkennung, Ce Zeichen Fehlgebrauch Und Abmahnung, Chirurgie Und Op Robotik, Data Act Roboterdaten: Biometrie Emotion Und Personenerkennung; Ce Zeichen Fehlgebrauch Und Abmahnung; Chirurgie Und Op Robotik; Da... |
| `cra-produkt-lager-intralogistikflotte` | Cra Produkt Mit Digitalen Elementen, Lager Und Intralogistikflotte: Cra Produkt Mit Digitalen Elementen; Lager Und Intralogistikflotte. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zusammen. |
| `datenminimierung-edge-datensatzqualitaet-bias` | Datenminimierung Edge Cloud, Datensatzqualitaet Und Bias Hri: Datenminimierung Edge Cloud; Datensatzqualitaet Und Bias Hri. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zusammen. |
| `datenschutz-cyber-first-year-uebergangsrecht-haftungsampel` | Workflow Datenschutz Cyber Intake, Workflow First Year Associate Robotik, Workflow Fristen Und Uebergangsrecht, Workflow Haftungsampel, Workflow Ingenieur Rueckfragenliste und 1 weitere Themen: Workflow Datenschutz Cyber Intake; Workflow... |
| `datenschutz-kameras-digitaler-zwilling-dronen-robotik-dsfa` | Datenschutz Kameras Und Sensorik, Digitaler Zwilling Und Simulation, Dronen Und Robotik Schnittstelle, Dsfa Für Robotik: Datenschutz Kameras Und Sensorik; Digitaler Zwilling Und Simulation; Dronen Und Robotik Schnittstelle; Dsfa Für Robo... |
| `datenverlust-digitaler-deliktische-haftung-haftung-arzt` | Datenverlust Und Digitaler Schaden, Deliktische Haftung Paragraph 823 Bgb, Haftung Arzt Klinik Hersteller, Schadensberechnung Produktionsausfall: Datenverlust Und Digitaler Schaden; Deliktische Haftung Paragraph 823 Bgb; Haftung Arzt Kli... |
| `dual-use-eu-umsetzung` | Dual Use Und Militaerische Robotik, Eu De Umsetzung Und Rechtsstand Livecheck: Dual Use Und Militaerische Robotik; Eu De Umsetzung Und Rechtsstand Livecheck. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und... |
| `eu-konformitaetserklaerung-foss-open-foundation-model` | Eu Konformitaetserklaerung Und Einbauerklaerung, Foss Und Open Source Komponenten, Foundation Model Und Gpai Im Roboter, Funkanlagen Und Konnektivitaet: Eu Konformitaetserklaerung Und Einbauerklaerung; Foss Und Open Source Komponenten; F... |
| `geschaeftsgeheimnisse-logdaten-grundrechte-psychische` | Geschaeftsgeheimnisse Und Logdaten, Grundrechte Und Psychische Belastung: Geschaeftsgeheimnisse Und Logdaten; Grundrechte Und Psychische Belastung. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätsc... |
| `harmonisierte-normen-human-oversight-importeur-haendler-ki` | Harmonisierte Normen Iso Ts 15066, Human Oversight In Physischer Robotik, Importeur Haendler Fulfilment Robotik, Ki Training Mit Roboterdaten: Harmonisierte Normen Iso Ts 15066; Human Oversight In Physischer Robotik; Importeur Haendler F... |
| `ki-vo-ki-vo` | Ki Vo Anhang Iii Robotik Usecases, Ki Vo Artikel 3 Ki System Robotik: Ki Vo Anhang Iii Robotik Usecases; Ki Vo Artikel 3 Ki System Robotik. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zus... |
| `ki-vo-ki-vo-ki-vo-ki-vo-kollaborierende-roboter` | Ki Vo Artikel 6 Hochrisiko Robotik, Ki Vo Deployer Pflichten Robotik, Ki Vo Provider Qms Und Risk Management, Ki Vo Verbotene Praktiken Robotik, Klinische Bewertung Robotik und 1 weitere Themen: Ki Vo Artikel 6 Hochrisiko Robotik; Ki Vo... |
| `ki-vo-laienmodus-robotikrecht-litigation-vorbereitung` | Workflow Ki Vo Integrationscheck, Workflow Laienmodus Robotikrecht, Workflow Litigation Vorbereitung, Workflow Marktueberwachung Dialog, Workflow Mdr Und Gesundheitsrobotik und 1 weitere Themen: Workflow Ki Vo Integrationscheck; Workflow... |
| `kommunal-behoerdenrobotik-konformitaetsbescheinigung-ki` | Kommunal Und Behoerdenrobotik, Konformitaetsbescheinigung Robotik Ki, Konformitaetsbewertung Modulwahl, Landwirtschaftsroboter Und Autonome Feldtechnik: Kommunal Und Behoerdenrobotik; Konformitaetsbescheinigung Robotik Ki; Konformitaetsb... |
| `lieferantenqualifizierung-sensor-lieferantenregress-indemnity` | Lieferantenqualifizierung Sensor Cloud, Lieferantenregress Und Indemnity: Lieferantenqualifizierung Sensor Cloud; Lieferantenregress Und Indemnity. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätsc... |
| `logging-traceability-marktueberwachung-unterlagenvorlage` | Logging Und Traceability Robotik, Marktueberwachung Unterlagenvorlage, Maschine Oder Unvollstaendige Maschine, Maschinenverordnung Annex Iii Hochrisiko: Logging Und Traceability Robotik; Marktueberwachung Unterlagenvorlage; Maschine Oder... |
| `medizinprodukt-software-mitbestimmung-betriebsrat` | Medizinprodukt Software Ki Roboter, Mitbestimmung Betriebsrat Robotik: Medizinprodukt Software Ki Roboter; Mitbestimmung Betriebsrat Robotik. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck z... |
| `mobile-roboter-nis2-betreiber-patientenaufklaerung-robotik` | Mobile Roboter Amr Agv, Nis2 Betreiber Kritische Sektoren, Patientenaufklaerung Robotik, Pflege Und Assistenzroboter: Mobile Roboter Amr Agv; Nis2 Betreiber Kritische Sektoren; Patientenaufklaerung Robotik; Pflege Und Assistenzroboter. F... |
| `open-source-post-market-presse-krisenkommunikation-privacy-by` | Workflow Open Source Und Sbom, Workflow Post Market Monitoring, Workflow Presse Und Krisenkommunikation, Workflow Privacy By Design Sprint, Workflow Produkt Und Rollenprofil und 1 weitere Themen: Workflow Open Source Und Sbom; Workflow P... |
| `pilotbetrieb-beta-prodhaftg-pld` | Pilotbetrieb Und Beta Robotik, Prodhaftg Und Neue Pld Vergleich: Pilotbetrieb Und Beta Robotik; Prodhaftg Und Neue Pld Vergleich. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zusammen. |
| `produktakte-gap-produktbeobachtung-field-produktfehler` | Produktakte Gap Analyse, Produktbeobachtung Und Field Data, Produktfehler Verbrauchererwartung Robotik, Produktsicherheit Vs Betriebssicherheit: Produktakte Gap Analyse; Produktbeobachtung Und Field Data; Produktfehler Verbrauchererwartu... |
| `produktsicherheitsrechtliche-werbung-quasihersteller-private` | Produktsicherheitsrechtliche Werbung, Quasihersteller Private Label Robotik: Produktsicherheitsrechtliche Werbung; Quasihersteller Private Label Robotik. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qual... |
| `qualitaetsmanagement-robotikhersteller-accuracy-robustness` | Qualitaetsmanagement Robotikhersteller, Accuracy Robustness Cybersecurity Ai, Agile Entwicklung Und Compliance Gates, Anwaltliche Quellenhygiene Robotik: Qualitaetsmanagement Robotikhersteller; Accuracy Robustness Cybersecurity Ai; Agile... |
| `rehabilitations-exoskelett-remote-update-risikobeurteilung-iso` | Rehabilitations Und Exoskelett Robotik, Remote Update Und Secure Channel, Risikobeurteilung En Iso 12100, Rollen Hersteller Anbieter Integrator: Rehabilitations Und Exoskelett Robotik; Remote Update Und Secure Channel; Risikobeurteilung... |
| `risikoklassifizierung-schnelltest-rueckruf-field` | Workflow Risikoklassifizierung Schnelltest, Workflow Rueckruf Und Field Action, Workflow Sachverstaendigenbriefing, Workflow Security By Design Sprint, Workflow Unfall Incident Response und 1 weitere Themen: Workflow Risikoklassifizierun... |
| `rueckrufpflicht-safety-safety-gate` | Rueckrufpflicht Und Safety Gate, Safety Gate Und Oeffentliche Warnung: Rueckrufpflicht Und Safety Gate; Safety Gate Und Oeffentliche Warnung. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck z... |
| `sbom-cyber-serviceroboter-haushalt-sicherheits` | Sbom Und Cyber Dokumentation, Serviceroboter Haushalt Gpsr, Sicherheits Und Ueberwachungsroboter, Sicherheitskomponente Mit Ki: Sbom Und Cyber Dokumentation; Serviceroboter Haushalt Gpsr; Sicherheits Und Ueberwachungsroboter; Sicherheits... |
| `smart-factory-softwareupdate-als` | Smart Factory Und Industrie 4 0, Softwareupdate Als Produktbezogener Dienst: Smart Factory Und Industrie 4 0; Softwareupdate Als Produktbezogener Dienst. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qual... |
| `sozialer-humanoider-spielzeug-kinderroboter-strom-emv` | Sozialer Humanoider Roboter, Spielzeug Und Kinderroboter, Strom Emv Und Niederspannung, Systemintegrator Als Hersteller: Sozialer Humanoider Roboter; Spielzeug Und Kinderroboter; Strom Emv Und Niederspannung; Systemintegrator Als Herstel... |
| `technische-besichtigung-testdaten-validierung` | Technische Besichtigung Und Geheimnisschutz, Testdaten Und Validierung Vor Marktstart: Technische Besichtigung Und Geheimnisschutz; Testdaten Und Validierung Vor Marktstart. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, O... |
| `transparenz-nutzerinformation-unfallanalyse-chain-vergaberecht` | Transparenz Und Nutzerinformation, Unfallanalyse Chain Of Custody, Vergaberecht Robotik Beschaffung, Vergleich Und Sanierung Nach Incident: Transparenz Und Nutzerinformation; Unfallanalyse Chain Of Custody; Vergaberecht Robotik Beschaffu... |
| `vernunftigerweise-vorhersehbarer-versicherungsdeckung-robotik` | Vernunftigerweise Vorhersehbarer Gebrauch, Versicherungsdeckung Robotik: Vernunftigerweise Vorhersehbarer Gebrauch; Versicherungsdeckung Robotik. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätsche... |
| `versicherungs-regressakte-vertrags-lieferkettenintake` | Workflow Versicherungs Und Regressakte, Workflow Vertrags Und Lieferkettenintake, Workflow Zweckbestimmung Und Usecase, Robot As A Service Vertrag: Workflow Versicherungs Und Regressakte; Workflow Vertrags Und Lieferkettenintake; Workflo... |
| `vigilanz-medizinrobotik-vulnerability-disclosure-wesentliche` | Vigilanz Medizinrobotik, Vulnerability Disclosure Und Reporting, Wesentliche Veraenderung Digital, Zweckbestimmung Enge Nutzungsbedingungen: Vigilanz Medizinrobotik; Vulnerability Disclosure Und Reporting; Wesentliche Veraenderung Digita... |
| `wartungs-servicevertrag-beweislast-offenlegung` | Wartungs Und Servicevertrag Robotik, Beweislast Und Offenlegung Produkthaftung: Wartungs Und Servicevertrag Robotik; Beweislast Und Offenlegung Produkthaftung. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster un... |
| `workflow-abschlussqualitaet-und-redteam` | Red-Team-Check für jedes Ergebnis: Normenstand, Quellen, fehlende Tatsachen, Gegenargumente, technische Annahmen, Datenschutz und Haftungsfolgen. |
| `workflow-anschluss-skills-router` | Schlägt nach jeder Robotikprüfung passende Anschlussplugins vor: KI-VO, Datenschutz, IT-Recht, Arbeitsrecht, Medizinrecht, Produkthaftung, Vertragsrecht und Prozess. |
| `workflow-dokumentenintake-datenraum` | Liest Robotik-Datenräume mit Anleitungen, CE-Unterlagen, Risikobeurteilung, Logs, Verträgen, Incident Reports und ordnet die nächsten Prüfschritte. |
| `workflow-gutachten-memo-output` | Wählt den passenden Output: Kurzvermerk, Vorstandsvorlage, Gutachten, Behördenantwort, Rückrufplan, Vertragsredline, Klageskizze oder Counsel-Briefing. |
| `workflow-human-robot-interaction-redteam` | Prüft besondere Mensch-Roboter-Interaktion: Nähe, Vertrauen, Manipulation, psychische Belastung, vulnerable Nutzer und klare Grenzen. |
| `workflow-kaltstart-und-routing` | Kaltstart für jedes Robotikmandat: sortiert Produkt, Rolle, Ziel, Frist, Risiko, Rechtsregime und schlägt sofort die passenden Skills im Robotik-Recht-Plugin vor. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
