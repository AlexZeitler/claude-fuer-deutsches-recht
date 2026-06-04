# AGB-Recht-Prüfer

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`agb-recht-pruefer`) | [`agb-recht-pruefer.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/agb-recht-pruefer.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **BGB BT — Smart-Kühlschrank, digitale Elemente und Reparaturblockade** (`bgb-bt-smart-kuehlschrank-digital-repair-koeln`) | [Gesamt-PDF lesen](../testakten/bgb-bt-smart-kuehlschrank-digital-repair-koeln/gesamt-pdf/bgb-bt-smart-kuehlschrank-digital-repair-koeln_gesamt.pdf) | [`testakte-bgb-bt-smart-kuehlschrank-digital-repair-koeln.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-bgb-bt-smart-kuehlschrank-digital-repair-koeln.zip) |
| **Akte Nordstern MedTech Vertrieb - Provision, Buchauszug und Ausgleich** (`handelsvertreterrecht-provisionsausgleich-nordstern-medtech`) | [Gesamt-PDF lesen](../testakten/handelsvertreterrecht-provisionsausgleich-nordstern-medtech/gesamt-pdf/handelsvertreterrecht-provisionsausgleich-nordstern-medtech_gesamt.pdf) | [`testakte-handelsvertreterrecht-provisionsausgleich-nordstern-medtech.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-handelsvertreterrecht-provisionsausgleich-nordstern-medtech.zip) |
| **Akte Vellbruck Robotics GmbH — Roboterflotte AtlasCare / LumaMove / Werkbank C7** (`robotikrecht-roboterflotte-vellbruck-muenchen`) | [Gesamt-PDF lesen](../testakten/robotikrecht-roboterflotte-vellbruck-muenchen/gesamt-pdf/robotikrecht-roboterflotte-vellbruck-muenchen_gesamt.pdf) | [`testakte-robotikrecht-roboterflotte-vellbruck-muenchen.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-robotikrecht-roboterflotte-vellbruck-muenchen.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

Gigantisches Plugin für deutsches AGB-Recht: Prüfen, Entwerfen, Redlinen, Verhandeln, Rollout und Streitverteidigung von Allgemeinen Geschäftsbedingungen in allen praktischen Varianten.

Das Plugin ist bewusst zweigleisig gebaut:

- **AGB prüfen:** Klauseln zerlegen, Einbeziehung und Transparenz prüfen, §§ 305 bis 310 BGB sauber anwenden, Risiko bewerten, bessere Fassung vorschlagen.
- **AGB entwerfen:** Geschäftsmodell verstehen, Klauselfamilien auswählen, sichere oder bewusst risikobehaftete Fassungen erzeugen, Rollout und Nachweisfähigkeit mitdenken.

## Start

```text
/agb-recht-prüfer:allgemein
```

Der Einstieg fragt zürst nicht zwanzig Dinge ab, sondern klärt die wichtigste Weiche: **prüfen oder entwerfen?** Danach routet er in passende Spezialskills, etwa Verbraucher-AGB, B2B-AGB, Online-Checkout, Preisanpassung, Haftung, Laufzeit, UKlaG, Redline oder konkrete Branchenbedingungen.

## Arbeitsweise

1. Klausel und Vertragstyp erfassen.
2. AGB-Eigenschaft und Einbeziehung prüfen.
3. Überraschung, Mehrdeutigkeit und Transparenz klären.
4. Inhaltskontrolle nach §§ 307 bis 309 BGB und Besonderheiten nach § 310 BGB.
5. Rechtsfolge, Rückabwicklung, UKlaG-/Prozessrisiko prüfen.
6. Bessere Klausel entwerfen: sicher, balanced oder aggressiv mit Warnlabel.
7. Rollout, Versionierung, Nachweisbarkeit und Fachbereichskommunikation erledigen.

## Live-Quellen

Das Plugin soll bei tragenden Aussagen immer die aktülle amtliche Fassung auf **Gesetze im Internet** prüfen, insbesondere BGB §§ 305 bis 310 und UKlaG. Siehe [`references/QUELLEN.md`](./references/QUELLEN.md).

## Typische Ergebnisse

| Bedarf | Ergebnis |
| --- | --- |
| Fremde AGB schnell prüfen | Klauselampel, Risikobegründung, Redline-Kommentar |
| Eigene AGB neu entwerfen | Klauselarchitektur, sichere Fassungen, Fallbacks |
| B2C-Rollout vorbereiten | Checkout-/Einbeziehungscheck, Versionierung, Kundenkommunikation |
| B2B-Verhandlung führen | Playbook mit Must-have, Fallback, No-Go und Argumenten |
| Abmahnung erhalten | Fristenscan, UKlaG-Risiko, modifizierte Unterlassungserklärung |
| Management informieren | kurze Legal Note mit Risiko, Optionen und Empfehlung |

## Enthaltene Skills

Die vollständige Skill-Liste wird automatisch am Ende dieser README aktualisiert.

## Lizenz

Apache-2.0 OR MIT — Auswahl beim Empfänger.


<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 54 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `agb-entwurf-kaltstart` | Einstiegs- und Workflow-Skill für AGB Entwurf Kaltstart: sortiert Ziel, Rolle, Dokumente, Normenstand, AGB-Risiko und nächsten Output schnell und anfängertauglich. |
| `agb-pruefung-kaltstart` | Einstiegs- und Workflow-Skill für AGB Prüfung Kaltstart: sortiert Ziel, Rolle, Dokumente, Normenstand, AGB-Risiko und nächsten Output schnell und anfängertauglich. |
| `allgemein` | Einstiegs- und Workflow-Skill für Allgemein: sortiert Ziel, Rolle, Dokumente, Normenstand, AGB-Risiko und nächsten Output schnell und anfängertauglich. |
| `ki-output-nutzung` | Klausel-Spezialskill für KI Output Nutzung: prüft, redlined und entwirft die Klausel mit Risikoampel, Verbraucher-/B2B-Unterscheidung und praxistauglicher Ersatzfassung. |
| `komp-01-teil-02-kurzfristige-preiserhoehung-309` | agb-recht-pruefer: eigenständiger Arbeits-Skill für sachlich zusammengehörige Arbeitsmodule zu Kurzfristige Preiserhoehung 309, Lieferfrist Teillieferung, Agb Anwaltsvertrag Und Allg Mandatsbedingungen, Agb Im Arbeitsvertrag 310 Abs 4 Ve... |
| `komp-01-teil-03-agb-im-bankvertrag-sparkassen-und-banken` | agb-recht-pruefer: eigenständiger Arbeits-Skill für sachlich zusammengehörige Arbeitsmodule zu Agb Im Bankvertrag Sparkassen Und Banken, Agb Im Bauvertrag Vob B 2024; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmust... |
| `komp-02-teil-02-formulararbeitsvertrag` | agb-recht-pruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Formulararbeitsvertrag, Haendlervertrag Agb, Inhaltskontrolle 307 Generalklausel, Klausel Checkliste Self Service und 1 weitere Arbeitsmodule; mit Intake, Prü... |
| `komp-03-teil-02-klauselverbote-308-systematik` | agb-recht-pruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Klauselverbote 308 Systematik, Klauselverbote 309 Systematik, Konzernklausel, Msa Rahmenvertrag und 1 weitere Arbeitsmodule; mit Intake, Prüfroutine, Normen-/... |
| `komp-04-teil-02-vergaberechtliche-vertragsbedingungen` | agb-recht-pruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Vergaberechtliche Vertragsbedingungen, Vertragsstrafe 309, Vertraulichkeit Klausel, Agb Fuer Vereinsausschluss Und Haftung und 1 weitere Arbeitsmodule; mit In... |
| `komp-05-teil-02-massenschaden-datenmodell` | agb-recht-pruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Massenschaden Datenmodell, Haftungsdeckel Fuer Daten Und Ki Schaeden, Schadenspauschale 309, Abmahnung Reagieren und 1 weitere Arbeitsmodule; mit Intake, Prüf... |
| `komp-06-teil-02-agb-begriff-vorformuliert-305` | agb-recht-pruefer: eigenständiger Arbeits-Skill für sachlich zusammengehörige Arbeitsmodule zu Agb Begriff Vorformuliert 305, Agb Bei Digitalen Produkten 327F Update, Agb Bei Iso Vertraegen International, Agb Bei Kreditvertraegen Verbrau... |
| `komp-06-teil-03-agb-bei-plattformnutzung-app-stores` | agb-recht-pruefer: eigenständiger Arbeits-Skill für sachlich zusammengehörige Arbeitsmodule zu Agb Bei Plattformnutzung App Stores, Agb Bei Vereinen Und Verbaenden; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster... |
| `komp-07-teil-02-agb-rechtswahl-schweizer-recht-rom-i` | agb-recht-pruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Agb Rechtswahl Schweizer Recht Rom I, Agb Risikoklassifizierung Ampel, Agb Transparenzgebot 307 Abs 1 Satz 2, Agb Und 242 Bgb Eingriffsnorm und 1 weitere Arbe... |
| `komp-08-teil-02-arbeitsrecht-agb-310-abs4` | agb-recht-pruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Arbeitsrecht Agb 310 Abs4, Architekten Ingenieur Agb, Auditrechte, Aufrechnung Zurueckbehaltung 309 und 1 weitere Arbeitsmodule; mit Intake, Prüfroutine, Norm... |
| `komp-09-teil-02-battle-of-forms-agb-kollision` | agb-recht-pruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Battle Of Forms Agb Kollision, Bau Vob Agb, Beweislast Und Zugang 309, Bewertung Rezensionen und 1 weitere Arbeitsmodule; mit Intake, Prüfroutine, Normen-/Que... |
| `komp-10-teil-02-change-request` | agb-recht-pruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Change Request, Clickwrap Beweisakte, Cloud Hosting Agb, Consulting Agb und 1 weitere Arbeitsmodule; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogi... |
| `komp-11-teil-02-deutsch-englisch-agb` | agb-recht-pruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Deutsch Englisch Agb, Digitale Inhalte Services, Dokumentation Handbuch, Dokumentenfamilie Rangfolge und 1 weitere Arbeitsmodule; mit Intake, Prüfroutine, Nor... |
| `komp-12-teil-02-energieversorgung-agb` | agb-recht-pruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Energieversorgung Agb, Entgelt Nebenkosten Service Fees, Exklusivitaet, Factoring Agb und 1 weitere Arbeitsmodule; mit Intake, Prüfroutine, Normen-/Quellenrad... |
| `komp-13-teil-02-franchise-agb` | agb-recht-pruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Franchise Agb, Gaming Agb, Garantie Beschaffenheit, Gerichtsstand und 1 weitere Arbeitsmodule; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Out... |
| `komp-14-teil-02-individualabrede-305b` | agb-recht-pruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Individualabrede 305b, Individualklage Verteidigung, Insolvenzverkauf Agb, Ip Nutzungsrechte und 1 weitere Arbeitsmodule; mit Intake, Prüfroutine, Normen-/Que... |
| `komp-15-teil-02-lagerbedingungen` | agb-recht-pruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Lagerbedingungen, Laufzeit Verlaengerung 309, Leasing Agb, Leistungsaenderung Produktupdate und 1 weitere Arbeitsmodule; mit Intake, Prüfroutine, Normen-/Quel... |
| `komp-16-teil-02-marketplace-agb` | agb-recht-pruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Marketplace Agb, Mediation Escalation, Medizinische Leistungen Agb, Mehrdeutigkeit 305c2 und 1 weitere Arbeitsmodule; mit Intake, Prüfroutine, Normen-/Quellen... |
| `komp-17-teil-02-non-solicitation` | agb-recht-pruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Non Solicitation, Norm Live Check Gesetze Im Internet, Open Source Komponenten, Parking Mobility Agb und 1 weitere Arbeitsmodule; mit Intake, Prüfroutine, Nor... |
| `komp-18-teil-02-rechtsfolge-306-kein-blue-pencil` | agb-recht-pruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Rechtsfolge 306 Kein Blue Pencil, Rechtsfolgen Rueckabwicklung Agb, Rechtswahl, Redline Kommentar Agb und 1 weitere Arbeitsmodule; mit Intake, Prüfroutine, No... |
| `komp-19-teil-02-ruegeobliegenheit` | agb-recht-pruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Ruegeobliegenheit, Saas Agb, Schiedsgericht, Schriftform Textform und 1 weitere Arbeitsmodule; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Out... |
| `komp-20-teil-02-steuern-umsatzsteuer` | agb-recht-pruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Steuern Umsatzsteuer, Stummer Upload Agb Dokumente, Subscription Abonnement, Subscription Box Agb und 1 weitere Arbeitsmodule; mit Intake, Prüfroutine, Normen... |
| `komp-21-teil-02-unternehmerverkehr-310-abs1` | agb-recht-pruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Unternehmerverkehr 310 Abs1, Unternehmerverkehr Schnellcheck, User Content Moderation, Vdug Abhilfeklage Agb Schnittstelle und 1 weitere Arbeitsmodule; mit In... |
| `komp-22-teil-02-verjaehrungsverkuerzung` | agb-recht-pruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Verjaehrungsverkuerzung, Verkaufsbedingungen B2b, Versicherung Avb, Versionsdiff Agb und 1 weitere Arbeitsmodule; mit Intake, Prüfroutine, Normen-/Quellenrada... |
| `komp-23-teil-02-wohnraummiete-agb` | agb-recht-pruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Wohnraummiete Agb, Zahlungsdienste Agb, Zahlungsmittel Chargeback, Zahlungsverzug Mahnkosten; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outp... |
| `kompendium-01-product-counsel-work-bis-agb-im-bauvertrag-vo` | agb-recht-pruefer: eigenständiger Arbeits-Skill für sachlich zusammengehörige Arbeitsmodule zu Product Counsel Workflow, Feedback Rechte, Annahmefrist Leistungsfrist 308, Kuendigungsfiktion Und Nachfrist 308; mit Intake, Prüfroutine, Nor... |
| `kompendium-02-agb-im-leasingvertra-bis-klausel-entwerfen-ag` | agb-recht-pruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Agb Im Leasingvertrag Fortwirkung, Agb Schiedsklausel Opt Out Deutsches Recht, Agb Vertragsstrafe 309 Nr 6, Ergaenzende Vertragsauslegung Bei Agb Luecken und... |
| `kompendium-03-klausel-entwerfen-ba-bis-preisanpassung-klaus` | agb-recht-pruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Klausel Entwerfen Balanced, Klausel Entwerfen Low Risk, Klauselbibliothek Aufbau, Klauselinventar Und Scope und 1 weitere Arbeitsmodule; mit Intake, Prüfrouti... |
| `kompendium-04-rechtsabteilung-chan-bis-agb-haftung-erfuellu` | agb-recht-pruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Change Control Klauseln Im Konzernvertrag, Vertragsstrafe In Einheitspreis Und Liefervertra, Salvatorische Klausel, Salvatorische Klausel Grenzen Rspr und 1 w... |
| `kompendium-05-compliance-sanktione-bis-abnahme-testing` | agb-recht-pruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Compliance Sanktionen, Haftung Grobe Fahrlaessigkeit Vorsatz, Haftung Indirekte Schaeden, Haftung Leben Koerper Gesundheit 309 und 1 weitere Arbeitsmodule; mi... |
| `kompendium-06-abtretung-bis-agb-bei-vereinen-und` | agb-recht-pruefer: eigenständiger Arbeits-Skill für sachlich zusammengehörige Arbeitsmodule zu Abtretung, Adversarial Test Agb, Aenderungsvorbehalt 308, Agb Arbeitnehmerueberlassung Aueg; mit Intake, Prüfroutine, Normen-/Quellenradar, Be... |
| `kompendium-07-agb-bei-versicherung-bis-agb-und-cookie-einwi` | agb-recht-pruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Agb Bei Versicherungsvertraegen Vvg, Agb Im Konzernverbund, Agb Im Mietrecht Wohnraum Vs Gewerbe, Agb In Kapitalanlagen Effektenhandel und 1 weitere Arbeitsmo... |
| `kompendium-08-agb-und-ipr-art-6-ro-bis-automatische-verlaen` | agb-recht-pruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Agb Und Ipr Art 6 Rom I Verbraucher, Agb Versionierung Aenderungshistorie, Agb Werkleistung Vob B Aktuell, Agentur Marketing Agb und 1 weitere Arbeitsmodule;... |
| `kompendium-09-avv-und-agb-schnitts-bis-bildungs-kurs-agb` | agb-recht-pruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Avv Und Agb Schnittstelle, B2b Harte Fassung, B2c B2b B2b2c Rollencheck, Backup Datenverlust und 1 weitere Arbeitsmodule; mit Intake, Prüfroutine, Normen-/Que... |
| `kompendium-10-blue-pencil-und-gelt-bis-crowdfunding-agb` | agb-recht-pruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Blue Pencil Und Geltungserhaltende Reduktion, Board Brief Agb, Bonitaetspruefung, Bonus Rabatt und 1 weitere Arbeitsmodule; mit Intake, Prüfroutine, Normen-/Q... |
| `kompendium-11-crypto-exchange-agb-bis-ecommerce-shop-agb` | agb-recht-pruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Crypto Exchange Agb, Darlehen Finanzierung Agb, Datenexport Portabilitaet, Datenschutzverweise Agb und 1 weitere Arbeitsmodule; mit Intake, Prüfroutine, Norme... |
| `kompendium-12-eigentumsvorbehalt-bis-fiktive-erklaerung-z` | agb-recht-pruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Eigentumsvorbehalt, Einbeziehung Hinweis Kenntnisnahme 305, Einbeziehung Online Clickwrap Browsewrap, Einkaufsbedingungen B2b und 1 weitere Arbeitsmodule; mit... |
| `kompendium-13-fitnessstudio-agb-bis-gesellschaftsrechtli` | agb-recht-pruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Fitnessstudio Agb, Force Majeure Hoehere Gewalt, Formvorgaben Anzeigen Erklaerungen 309, Forschung Entwicklung Agb und 1 weitere Arbeitsmodule; mit Intake, Pr... |
| `kompendium-14-gesetzliches-leitbil-bis-kardinalpflichten` | agb-recht-pruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Gesetzliches Leitbild Abweichung 307, Gewahrleistung Ausschluss, Gewerbemiete Agb, Handelsvertreter Agb und 1 weitere Arbeitsmodule; mit Intake, Prüfroutine,... |
| `kompendium-15-ki-service-agb-bis-liquidated-damages` | agb-recht-pruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Ki Service Agb, Kollisionsrecht Ipr Agb, Konto Kuendigung Sperre, Kuendigung Aus Wichtigem Grund und 1 weitere Arbeitsmodule; mit Intake, Prüfroutine, Normen-... |
| `kompendium-16-logistik-spedition-a-bis-mehrsprachige-agb-ch` | agb-recht-pruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Logistik Spedition Agb, Maengelrechte 309, Mahngebuehren Und Zinsanpassung Agb, Mandanteninterview Agb und 1 weitere Arbeitsmodule; mit Intake, Prüfroutine, N... |
| `kompendium-17-mindestabnahme-bis-plain-language-polit` | agb-recht-pruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Mindestabnahme, Mitwirkungspflichten, Nacherfuellung Vorrang, Nda Standardbedingungen und 1 weitere Arbeitsmodule; mit Intake, Prüfroutine, Normen-/Quellenrad... |
| `kompendium-18-plattform-und-online-bis-referenznennung` | agb-recht-pruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Plattform Und Online Checkout, Quality Gate Vor Rollout, Rangfolge Sprache, Preisanpassung Bei Dauervertraegen Nach Energiek und 1 weitere Arbeitsmodule; mit... |
| `kompendium-19-reisebedingungen-bis-security-incidents` | agb-recht-pruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Reisebedingungen, Reseller Agb, Risk Acceptance Memo, Rollout Mail Bestandskunden und 1 weitere Arbeitsmodule; mit Intake, Prüfroutine, Normen-/Quellenradar,... |
| `kompendium-20-sicherungsrechte-bis-subunternehmer` | agb-recht-pruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Sicherungsrechte, Sla Service Credits, Social Media Agb, Softwarelizenz Agb und 1 weitere Arbeitsmodule; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweis... |
| `kompendium-21-support-response-tim-bis-verbraucherbesonderh` | agb-recht-pruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Support Response Times, Telekommunikation Agb, Transparenzgebot 307, Uklag Unterlassung Verbandsklage und 1 weitere Arbeitsmodule; mit Intake, Prüfroutine, No... |
| `kompendium-22-verbraucherfreundlic-bis-vollmacht-vertretung` | agb-recht-pruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Verbraucherfreundliche Fassung, Verbraucherschutz Schnellcheck, Vereinsbedingungen, Verfuegbarkeit Wartungsfenster und 1 weitere Arbeitsmodule; mit Intake, Pr... |
| `kompendium-23-vorkasse-abschlag-si-bis-zahlungsverzug-mahnk` | agb-recht-pruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Vorkasse Abschlag Sicherheit, Wartung Maintenance, Website Update Check, Wesentliche Rechte Pflichten 307 und 1 weitere Arbeitsmodule; mit Intake, Prüfroutine... |
| `legal-note-redline-output` | Einstiegs- und Workflow-Skill für Legal Note Redline Output: sortiert Ziel, Rolle, Dokumente, Normenstand, AGB-Risiko und nächsten Output schnell und anfängertauglich. |
| `red-team-gegneransicht-agb` | Einstiegs- und Workflow-Skill für Red Team Gegneransicht AGB: sortiert Ziel, Rolle, Dokumente, Normenstand, AGB-Risiko und nächsten Output schnell und anfängertauglich. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
