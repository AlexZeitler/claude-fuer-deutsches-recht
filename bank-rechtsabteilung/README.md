# Bank-Rechtsabteilung


<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`bank-rechtsabteilung`) | [`bank-rechtsabteilung.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/bank-rechtsabteilung.zip) |

Dieses Plugin hat (bewusst) keine eigene Demonstrations-Akte.

<!-- END plugin-sofort-download-section (autogen) -->

Rechtsabteilungs-Plugin für eine mittelgroße deutsche Bank: schnell genug für den internen Ticketkanal, sorgfältig genug für Vorstand, Aufsichtsrat, BaFin, Bundesbank, externe Kanzleien und späteren Aktenrückblick.

Es ist als Inhouse-Cockpit gedacht: nicht nur Bankrecht im engeren Sinn, sondern der ganze Alltag einer Bank-Rechtsabteilung. Aufsichtsrecht, Kredit, Sanierung, Auslagerung, DORA, Geldwäsche, AGB, Handelsvertreter, Vertrieb, Beschwerden, Organvorlagen, Hauptversammlung, Beteiligungen, Datenschutz, Kanzleisteuerung und Rechnungsreview werden in einen einzigen Routing-Workflow gebracht.

## Für wen

| Rolle | Typische Nutzung |
| --- | --- |
| General Counsel / Chefjustiziar | Vorstandsvorlagen, Aufsichtsrat, Eskalation, Kanzleisteuerung |
| Syndikus in Legal | Gutachten, Vertragscheck, Fachbereichsberatung, BaFin-Antworten |
| Compliance / AML / Datenschutz | GwG, Sanktionen, DORA, Richtlinien, Meldungen, Findings |
| Marktfolge / Risk / Workout | Weiterfinanzierung, Stundung, Sanierungsgutachten, Sicherheiten |
| Vorstandsreferat | Beschlussvorschläge, Q&A, HV- und Ausschussunterlagen |

## Kaltstart

Beginne mit:

```text
/bank-rechtsabteilung:allgemein
```

Der Einstieg fragt nicht erst einen langen Fragebogen ab, sondern sortiert sofort:

- Was liegt vor?
- Wer braucht das Ergebnis?
- Gibt es eine Frist oder Aufsichtsdruck?
- Ist es Kredit, Aufsicht, Vertrieb, Organ, Vertrag, Datenschutz, Litigation oder Dienstleistersteuerung?
- Welcher Spezial-Skill passt jetzt wirklich?

Wenn nur ein Dokument hochgeladen wird, behandelt der Allgemein-Skill das als Arbeitsauftrag: Fristen erkennen, Material klassifizieren, Risikoampel bauen, passenden Spezial-Skill vorschlagen oder direkt einen ersten verwertbaren Entwurf schreiben.

## Normen- und Quellenhygiene

Das Plugin ist bewusst quellenstrikt. Es soll keine BeckRS-, Juris-, Kommentar- oder Aufsatz-Blindzitate produzieren. Für tragende Aussagen sind Live-Checks gegen amtliche oder frei zugängliche Quellen vorgesehen, insbesondere:

- Gesetze im Internet: KWG, ZAG, WpHG, GwG, HGB, BGB, AktG.
- BaFin: MaRisk, DORA-Informationen, Merkblätter, Rundschreiben und Aufsichtsmitteilungen.
- Bundesbank, EZB/SSM, EBA und EUR-Lex für europäische Aufsichtsakte und Leitlinien.
- Gerichtsentscheidungen nur mit Gericht, Entscheidungsform, Datum, Aktenzeichen und freier oder amtlicher Quelle.

Siehe auch [`references/QUELLEN.md`](./references/QUELLEN.md).

## Typische Workflows

| Workflow | Start-Skill | Ergebnis |
| --- | --- | --- |
| BaFin-Schreiben liegt vor | `bafin-kommunikation-und-anhoerung` | Antwortarchitektur, Tatsachenmatrix, Freigabekette |
| Cloud-Vertrag soll freigegeben werden | `dora-ict-vertraege-vorfall` | DORA-/Auslagerungscheck, Klausellücken, Exit-Fragen |
| Kreditnehmer braucht Stundung | `stundung-standstill-waiver` | Term Sheet, Conditions, Sicherheiten- und Anfechtungsampel |
| Sanierungsgutachten kommt rein | `sanierungsgutachten-idw-s6-bewertung` | Plausibilitätsreview, Red Flags, Nachforderungsliste |
| Vorstand braucht Vorlage | `vorstandsvorlage-gutachten` | Executive Summary, Optionen, Beschlussvorschlag |
| Kanzleirechnung ist zu hoch | `anwaltliche-rechnungen-review` | Rechnungsprüfung, Rückfragen, Kürzungsvorschlag |
| Handelsvertreter kündigt | `handelsvertreter-vertriebsrecht-bank` | Statusanalyse, Ausgleichsrisiko, Verhandlungsposition |
| AGB sollen geändert werden | `agb-bankrecht-klauselkontrolle` | Klauselampel, bessere Fassung, Rollout-Hinweise |

## Direkt-Download

| Plugin | Direkt-Download |
| --- | --- |
| Bank-Rechtsabteilung (`bank-rechtsabteilung`) | [bank-rechtsabteilung.zip](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/bank-rechtsabteilung.zip) |

Die URL zeigt immer auf das aktuelle Release-Asset.

## Installation in Claude Code / Cowork

1. ZIP aus dem Release herunterladen.
2. In Claude Code / Cowork unter **Customize Plugins** das ZIP installieren.
3. `bank-rechtsabteilung` aktivieren und mit `/bank-rechtsabteilung:allgemein` starten.

> Für den ZIP-Upload muss das Archiv direkt `.claude-plugin/plugin.json`, `skills/` und `references/` im ZIP-Root enthalten. Nicht das komplette Repository-ZIP aus GitHub verwenden.

## Enthaltene Skills

Die vollständige Skill-Liste wird automatisch am Ende dieser README aktualisiert.

## Lizenz

Apache-2.0 OR MIT — Auswahl beim Empfänger.


<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 50 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `agb-bankrecht-klauselkontrolle` | AGB-Recht für Banken: Klauseln nach §§ 305 bis 310 BGB, Preisänderungen, Zustimmungsmechanismen, Kündigung, Entgelte, Aufrechnung, Haftung und Verbrauchertransparenz prüfen. |
| `allgemein` | Einstieg und Chefjustiziar-Workflow für die Rechtsabteilung einer mittelgroßen deutschen Bank. Fragt Rolle, Ziel, Fristen, Dokumente, Aufsichtsrisiko, Kreditrisiko, Organbedarf und gewünschten Output ab und routet in passende Bank-Skills. |
| `anwaltliche-rechnungen-review` | Anwaltliche Rechnungen und Kanzlei-Budgets reviewen: Scope-Abgleich, RVG oder Honorarvereinbarung, Zeitpositionen, Auslagen, USt, Doppelarbeit, Erfolg, Billing Guidelines und Kürzungsvorschlag. |
| `aufsichtsrat-vorlage-bank` | Aufsichtsrats- und Ausschussvorlagen einer Bank vorbereiten: Informationspflicht, Beschlusskompetenz, Risikoausschuss, Prüfungsausschuss, Vertraulichkeit, Protokollfestigkeit und Follow-up. |
| `bafin-kommunikation-und-anhoerung` | BaFin-Kommunikation und Anhörung: Antwortstrategie, Tonfall, Tatsachenklärung, Fristen, Vollständigkeit, Anerkenntnisrisiken, Aufsichtsdialog und Vorstandsinformation für Banken strukturieren. |
| `bafin-pruefung-vor-ort-management` | Vor-Ort-Prüfung, Sonderprüfung oder Aufsichtsprüfung in der Bank vorbereiten: Datenraum, Interviewliste, Kommunikationsregeln, Prüfungslog, Legal Privilege, Nachlieferungen und Abschlussbericht managen. |
| `bankaufsichtsrecht-kwg-marisk-triage` | Bankaufsichtsrechtliche Ersttriage nach KWG und MaRisk: Geschäftsorganisation, Risikomanagement, Compliance, Revision, Risikocontrolling, Leitungsbefassung und Dokumentationsbedarf für interne Vermerke prüfen. |
| `bankgeheimnis-auskunftsersuchen` | Auskunftsersuchen an Banken prüfen: Polizei, Staatsanwaltschaft, Gericht, Finanzamt, Insolvenzverwalter, Betreuer, Erben, Anwälte und Privatpersonen sicher auseinanderhalten. |
| `bankrechtsabteilung-kaltstart-routing` | Kaltstart-Routing für neue Inhouse-Anfragen in einer Bank: Sachgebiet erkennen, Eilbedarf markieren, BaFin-, Vorstand-, Kredit-, Vertrieb-, AGB-, Datenschutz- oder Prozesspfad wählen und genau die nächsten Unterlagen anfordern. |
| `beteiligungserwerb-bank-ma` | Beteiligungserwerb, M&A und strategische Kooperation einer Bank prüfen: Erlaubnisse, Inhaberkontrolle, Beteiligungsgrenzen, Due Diligence, Kartell, Datenschutz, Sanierung und Gremien. |
| `betriebsrat-change-projekte` | Betriebsrat und arbeitsrechtliche Schnittstellen bei Bankprojekten: Restrukturierung, IT-Einführung, Monitoring, variable Vergütung, Auslagerung, Filialschließung und Betriebsänderung prüfen. |
| `crr-crd-eigenmittel-large-exposure` | CRR-, CRD- und Großkredit-Schnittstelle für Juristen: Eigenmittelbegriffe, Large Exposure, Organkredite, Beteiligungen, Limitüberschreitungen und Governance-Freigaben verständlich prüfen. |
| `darlehensrecht-verbraucher-unternehmer` | Darlehensrecht für Banken: Verbraucher- und Unternehmenskredit, Pflichtangaben, Widerruf, Kündigung, Sicherheiten, Zahlungsverzug, Vorfälligkeitsfragen und Prozessrisiko prüfen. |
| `datenraum-bank-transaktion` | Datenraum für Bank-Transaktionen oder Aufsichtsprüfungen strukturieren: Dokumentenindex, Berechtigungen, Schwärzungen, Bankgeheimnis, Datenschutz, Q&A und Audit Trail. |
| `datenschutz-bankgeheimnis` | Datenschutz, Bankgeheimnis und Mandatsgeheimnis in der Bank: Datenbasis, Offenlegung, Dienstleister, Auskunft, Löschung, Behördenzugriff, KI-Nutzung und Geheimnisschutz prüfen. |
| `dora-ict-vertraege-vorfall` | DORA-IKT-Verträge und IKT-Vorfälle: Pflichtklauseln, Register, Exit, Überwachungsrechte, Suboutsourcing, Incident-Klassifizierung, Meldewege und Managementbericht prüfen. |
| `einlagensicherung-kundenhinweise` | Einlagensicherung und Kundenhinweise: gesetzliche und institutsspezifische Sicherung, Informationsbogen, Produktabgrenzung, Markenauftritt, Filialhinweise und Beschwerdekommunikation prüfen. |
| `esg-sustainable-finance` | ESG und Sustainable Finance in der Bank: Offenlegung, Taxonomie, Green Claims, Kreditpolitik, Anlageprodukte, Reputationsrisiko und Vorstandskommunikation prüfen. |
| `externe-anwaelte-steuerung` | Externe Anwälte und Kanzleien steuern: Mandatsbrief, Scope, Budget, Reporting, Privilege, Interessenkonflikte, Rechtsmeinungen, Second Opinion und internes Wissen sichern. |
| `fit-proper-organe-mitarbeiter` | Fit-and-Proper für Geschäftsleiter, Aufsichtsrat und Schlüsselfunktionen: Sachkunde, Zuverlässigkeit, Zeitbudget, Interessenkonflikte, Anzeigen und Nachweise vorbereiten. |
| `forbearance-npe-risikoklassifizierung` | Forbearance, NPE und Risikoklassifizierung juristisch begleiten: Zugeständnisse, Ausfallnähe, Melde- und Dokumentationsfolgen, Kreditakte und Kommunikation mit Risk sauber halten. |
| `gwg-aml-kyc-verdachtsmeldung` | GwG-, AML- und KYC-Prüfung für Banken: Risikoanalyse, wirtschaftlich Berechtigte, PEP, Sanktionen, Transaktionsmonitoring, Verdachtsmeldung und Dokumentation ohne unnötige Selbstbelastung strukturieren. |
| `handelsvertreter-vertriebsrecht-bank` | Handelsvertreter- und Vertriebsrecht für Banken: § 84 HGB, Ausgleich § 89b HGB, Vermittlerstatus, Tippgeber, Ausschließlichkeit, Provision, Kündigung und Compliance prüfen. |
| `hauptversammlung-bank-aktg` | Hauptversammlung einer Bank rechtlich vorbereiten: Tagesordnung, Beschlussvorschläge, Vorstand/Aufsichtsrat, Vergütung, Kapitalmaßnahmen, Satzung, Gegenanträge und Stimmrechtsfragen. |
| `insolvenz-anfechtung-bank` | Insolvenzanfechtung gegen Banken vorbeugen und verteidigen: Sicherheitenbestellung, Rückführung, Kontokorrent, inkongruente Deckung, Kenntnis, Bargeschäft und Anfechtungsgegner-Argumente prüfen. |
| `interne-richtlinie-policy-drafting` | Interne Richtlinien und Policies für Banken entwerfen: Normenbasis, Zielgruppe, Rollen, Kontrollen, Eskalation, Dokumentation, Versionierung, Schulung und Vorstandsbeschluss. |
| `it-sicherheit-cloud-vertraege` | IT-Sicherheit und Cloud-Verträge einer Bank prüfen: DORA, NIS2-Schnittstelle, Datenschutz, Audit-Rechte, Exit, Verschlüsselung, Incident Response, Subdienstleister und Bankaufsicht. |
| `kontokuendigung-sperre-basiskonto` | Kontokündigung, Kontosperre und Basiskonto prüfen: Vertragsrecht, AGB, GwG, Sanktionen, Pfändung, Diskriminierungsrisiko, Sozialleistungen und Kundenkommunikation ausbalancieren. |
| `kreditentscheidung-weiterfinanzierung` | Kreditentscheidung und Weiterfinanzierung: neue Auszahlung, Prolongation, Covenant-Bruch, Sanierungsphase, Risikovotum, Organpflichten und Dokumentation der Bankentscheidung prüfen. |
| `kreditsicherheiten-bestellung-verwertung` | Kreditsicherheiten bestellen, prüfen und verwerten: Grundschuld, Bürgschaft, Garantie, Globalzession, Sicherungsübereignung, Pfandrechte, Rang, Freigabe und Verwertungsschritte. |
| `kreditwesengesetz-erlaubnis-inhaberkontrolle` | KWG-Erlaubnis, Erlaubniserweiterung, Inhaberkontrolle und qualifizierte Beteiligung prüfen: Geschäftsmodell, Schwellen, Anzeige, Fit-and-Proper und BaFin-Erwartungen strukturieren. |
| `kundenbeschwerde-ombudsmann-bafin` | Kundenbeschwerden, Ombudsmann, BaFin-Beschwerde und Eskalation: Sachverhalt, Anspruch, Kulanz, Reputationsrisiko, Fristen, Ton und interne Learnings für Banken steuern. |
| `litigation-schlichtung-prozess` | Litigation, Schlichtung und Prozessführung einer Bank: Anspruch, Beweise, Kosten, Vergleich, Musterverfahren, Ombudsmann, externe Kanzlei und Vorstandsinformation steuern. |
| `ma-risk-compliance-funktion` | MaRisk-Compliance-Funktion und zweite Verteidigungslinie prüfen: Aufgaben, Unabhängigkeit, Compliance-Plan, Monitoring, Findings, Berichtslinie und Verhältnis zu Recht, Risk und Revision. |
| `marisk-auslagerungen-at9-dora` | MaRisk-Auslagerung und DORA-Schnittstelle: AT 9, § 25b KWG, Auslagerungsregister, Risikoanalyse, wesentliche Auslagerung, IKT-Drittanbieter und Exit-Plan zusammen prüfen. |
| `mifid-wphg-anlageberatung` | WpHG- und MiFID-II-Pflichten bei Anlageberatung und Vertrieb: Geeignetheit, Angemessenheit, Zielmarkt, Kosteninformation, Zuwendungen, ESG-Präferenzen und Dokumentation prüfen. |
| `notfallplan-krisenkommunikation` | Notfallplan und Krisenkommunikation für Bank-Legal: Cyberangriff, Bank Run, BaFin-Maßnahme, Medienanfrage, Whistleblowing, Großschaden oder Vorstandskrise strukturieren. |
| `organhaftung-business-judgment` | Organhaftung und Business Judgment Rule in der Bank: Vorstand, Aufsichtsrat, Ausschüsse, Informationsgrundlage, Interessenkonflikte, Dokumentation und D&O-Risiken prüfen. |
| `outsourcing-externe-dienstleister` | Externe Dienstleister außerhalb reiner IKT prüfen: Auslagerung, sonstiger Fremdbezug, Datenschutz, Bankgeheimnis, SLA, Prüfungsrechte, Kündigung, Business Continuity und Registerpflege. |
| `produktfreigabe-new-product-process` | New Product Process einer Bank: Produktidee, Zielmarkt, Recht, Aufsicht, Steuern, IT, Datenschutz, Vertrieb, Risiko, Operations und Vorstandfreigabe in einen sauberen NPP bringen. |
| `provisionsmodelle-vertrieb-compliance` | Provisionsmodelle und Vertriebscompliance prüfen: Zuwendungen, Interessenkonflikte, MiFID, Verbraucherschutz, Vergütungsrichtlinien, Zielvorgaben und Vorstandsvorlage für Produktvertrieb. |
| `rechtsmonitoring-bank` | Rechtsmonitoring für Banken einrichten: BaFin, Bundesbank, EBA, EZB, EU, Bundesgesetzblatt, Rechtsprechung, Verbände, Relevanzfilter und Umsetzungslog dokumentieren. |
| `restrukturierung-kreditengagement` | Restrukturierung eines Kreditengagements steuern: Strategie, Sicherheiten, Pool, StaRUG-/InsO-Schnittstelle, Sanierungsbeiträge, Kommunikation und interne Kreditakte ordnen. |
| `sanierungsgutachten-idw-s6-bewertung` | Eingehende Sanierungsgutachten nach IDW S 6 aus Bankperspektive bewerten: Krisenstadien, Fortbestehen, Leitbild, Maßnahmen, integrierte Planung, Plausibilität und Kreditentscheidung. |
| `sanktionsscreening-embargo-bank` | Sanktionsscreening und Embargo in der Bank: Treffer, False Positive, EU-Sanktionen, OFAC-Berührung, Zahlungsstopp, Kontosperre, Freigabeprozess und Kundenkommunikation steuern. |
| `ssm-bundesbank-aufsichtsbrief` | SSM-, EZB- und Bundesbank-Aufsichtsbriefe für Institute einordnen: Zuständigkeit, JST-Kommunikation, nationale Umsetzung, Fristen, Management Letter, Follow-up und Board-Package vorbereiten. |
| `stundung-standstill-waiver` | Stundung, Standstill, Waiver und Covenant-Reset entwerfen und prüfen: Bankinteressen, Sicherheiten, Sanierungspfad, Gleichbehandlung, Kündigungsrechte und Dokumentationsschutz. |
| `vorstandsvorlage-gutachten` | Vorstandsvorlage und juristisches Gutachten für eine Bank erstellen: Entscheidungssatz, Risikoampel, Handlungsoptionen, Beschlussvorschlag, Annahmen, Quellen und Anlagenverzeichnis. |
| `wpig-wertpapierinstitut-schnittstelle` | WpIG-Schnittstellen prüfen, wenn Bankgruppe, Wertpapierinstitut, Vermittler oder Tochtergesellschaft beteiligt sind: Rollen, Erlaubnis, Eigenmittel, Auslagerung und Governance abgrenzen. |
| `zahlungsdienste-zag-psd3-psr` | Zahlungsdienste nach ZAG, PSD2-Folgefragen, PSD3- und PSR-Entwicklungen prüfen: Rollen, Erlaubnis, starke Kundenauthentifizierung, Haftung, Betrugsfälle und Beschwerdeantworten. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
