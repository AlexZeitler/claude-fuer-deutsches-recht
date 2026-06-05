# BGB AT Prüfer

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`bgb-at-pruefer`) | [`bgb-at-pruefer.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/bgb-at-pruefer.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **Anfechtung / Irrtum — Restaurant-Kette Pohlmann-Ofenkaess, Erbenstraße Leipzig** (`anfechtung-irrtum-restaurant-kette-pohlmann-erbenstrasse-leipzig`) | [Gesamt-PDF lesen](../testakten/anfechtung-irrtum-restaurant-kette-pohlmann-erbenstrasse-leipzig/gesamt-pdf/anfechtung-irrtum-restaurant-kette-pohlmann-erbenstrasse-leipzig_gesamt.pdf) | [`testakte-anfechtung-irrtum-restaurant-kette-pohlmann-erbenstrasse-leipzig.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-anfechtung-irrtum-restaurant-kette-pohlmann-erbenstrasse-leipzig.zip) |
| **Akte BGB AT: Altfränkische Werkstatt** (`bgb-at-altfraenkische-werkstatt`) | [Gesamt-PDF lesen](../testakten/bgb-at-altfraenkische-werkstatt/gesamt-pdf/bgb-at-altfraenkische-werkstatt_gesamt.pdf) | [`testakte-bgb-at-altfraenkische-werkstatt.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-bgb-at-altfraenkische-werkstatt.zip) |
| **BGB BT — Holzofen, Lieferkette, Bürgschaft, GoA und Brandschaden** (`bgb-bt-holzofen-lieferkette-buergschaft-goa-delikt`) | [Gesamt-PDF lesen](../testakten/bgb-bt-holzofen-lieferkette-buergschaft-goa-delikt/gesamt-pdf/bgb-bt-holzofen-lieferkette-buergschaft-goa-delikt_gesamt.pdf) | [`testakte-bgb-bt-holzofen-lieferkette-buergschaft-goa-delikt.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-bgb-bt-holzofen-lieferkette-buergschaft-goa-delikt.zip) |
| **BGB BT — Smart-Kühlschrank, digitale Elemente und Reparaturblockade** (`bgb-bt-smart-kuehlschrank-digital-repair-koeln`) | [Gesamt-PDF lesen](../testakten/bgb-bt-smart-kuehlschrank-digital-repair-koeln/gesamt-pdf/bgb-bt-smart-kuehlschrank-digital-repair-koeln_gesamt.pdf) | [`testakte-bgb-bt-smart-kuehlschrank-digital-repair-koeln.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-bgb-bt-smart-kuehlschrank-digital-repair-koeln.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

<!-- BEGIN TESTAKTEN-SECTION (auto-generated) -->

## Testakte

Zu diesem Plugin existiert eine vollständige Beispielakte: **BGB AT: Altfränkische Werkstatt** ([`testakten/bgb-at-altfraenkische-werkstatt/`](../testakten/bgb-at-altfraenkische-werkstatt/)).

Direkt-Download als ZIP: [testakte-bgb-at-altfraenkische-werkstatt.zip](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-bgb-at-altfraenkische-werkstatt.zip)

Die Akte ist absichtlich unordentlich, widersprüchlich und ungefiltert. Sie eignet sich für End-to-End-Tests, Demos und zum Üben.

<!-- END TESTAKTEN-SECTION (auto-generated) -->

Großes Prüfplugin zum BGB Allgemeiner Teil. Es führt durch Vertragsschluss, Willenserklärungen, Zugang, Auslegung, Geschäftsfähigkeit, Form, Nichtigkeit, Anfechtung, Stellvertretung, Bedingungen, Fristen und Verjährung. Der Formteil ist mit qES, beA, § 130e ZPO und § 46h ArbGG verschaltet. Neu verschaltet sind digitale Elemente, Updatehinweise, App-/Portalzugang, Reparaturverlangen und Right-to-Repair-Fragen als allgemeinzivilrechtlicher Router in BGB-BT, AGB-Recht und Produktrecht. Ziel ist ein schöner, schneller und trotzdem präziser Workflow für Klausur, Ausbildung, Kanzleivermerk und Mandatsarbeit.

Experimentelles Werkzeug. Keine Rechtsberatung, keine Gewähr. Gesetzestext und Rechtsprechung müssen im konkreten Fall geprüft werden. Literatur- oder Kommentarstellen dürfen nur genutzt werden, wenn sie vom Nutzer bereitgestellt wurden oder über eine lizenzierte Quelle live verifiziert sind.

## Schnellstart

/plugin install bgb-at-pruefer@claude-fuer-deutsches-recht

Starte mit dem Skill [allgemein](./skills/allgemein/SKILL.md). Der Einstieg fragt den Fall in einer kompakten Reihenfolge ab, baut eine Themenkarte und schlägt danach die passenden Spezial-Skills vor.

## Was das Plugin besonders gut kann

- aus einem unsortierten BGB-AT-Sachverhalt einen Anspruchsbaum bauen
- Angebot, Annahme, Zugang, Fristen und digitale Erklärungsketten auseinanderziehen
- Minderjährigenfälle mit §§ 104-113 BGB sauber prüfen
- Anfechtung mit Auslegung, Frist, Gegner und Folgen prüfen
- Stellvertretung, Vollmacht, Rechtsschein und § 181 BGB trennen
- Form, Nichtigkeit, Gesetzesverbot, Sittenwidrigkeit und Bedingung als Wirksamkeitsfragen einordnen
- elektronische Form, qES-Zugang, beA-Einreichung und prozessuale Formfiktion auseinanderhalten
- Waren mit digitalen Elementen, Updatehinweise, AGB-Abweichungen und Reparaturverlangen in die richtigen Spezial-Skills routen
- aus dem Ergebnis Gutachten, Mandatsmemo, Schriftsatzbaustein, Rückfragenbrief oder Trainingsfall machen

## Empfohlener Workflow

1. Fallfrage festnageln: Wer will was von wem, und auf welcher Anspruchsebene liegt das Problem?
2. Erklärungskette bauen: Jede Erklärung mit Datum, Kanal, Absender, Empfänger, Zugang und Inhalt erfassen.
3. BGB-AT-Themenkarte erstellen: Geschäftsfähigkeit, Willenserklärung, Vertragsschluss, Auslegung, Form, Nichtigkeit, Anfechtung, Stellvertretung, Bedingung, Fristen.
4. Spezial-Skills laden: Der Allgemein-Skill schlägt zwei bis fünf passende Folge-Skills vor.
5. Arbeitsprodukt wählen: Klausurlösung, Memo, Schriftsatzbaustein, Fristenvermerk oder Training.

## Skill-Auswahl

Die früher sehr lange Einzelskill-Tabelle ist in verdichtete Kompendium-Skills überführt. Nutze für die Auswahl die automatisch gepflegte Übersicht unten; die Kompendien enthalten die früheren Einzelthemen als Unterabschnitte mit ihren Prüfprogrammen, Normankern und Ausgabeformaten.

## Quellen- und Aktualitätsanker

- Aktueller BGB-Gesetzestext: https://www.gesetze-im-internet.de/bgb/
- Interne Struktur: [references/bgb-at-pruefprogramm.md](./references/bgb-at-pruefprogramm.md)
- Rechtsstandsregel: [references/rechtsstand-und-quellen.md](./references/rechtsstand-und-quellen.md)

## Gute Begleiter

- [methodenlehre-buergerliches-recht](../methodenlehre-buergerliches-recht) für Auslegung, Gutachtenstil und Anspruchsdenken.
- [subsumtions-pruefer](../subsumtions-pruefer) für generische Tatbestandsarbeit.
- [schriftform-und-textform-bgb](../schriftform-und-textform-bgb) für tiefe Form-, Textform- und Zugangskonstellationen.
- [bereicherungs-und-anfechtungsrecht-pruefer](../bereicherungs-und-anfechtungsrecht-pruefer) für Rückabwicklung nach unwirksamem Vertrag.

<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 23 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `agb-einbeziehung-amtlicher-zpo-anfechtung-routing` | Agb Einbeziehung Schnittstelle Paragraphen 305 310, Amtlicher Bgb Zpo Normcheck, Anfechtung Routing: Agb Einbeziehung Schnittstelle Paragraphen 305 310; Amtlicher Bgb Zpo Normcheck; Anfechtung Routing. Führt Intake, Prüfroutine, Normen-/... |
| `allgemein` | Einstieg, Schnelltriage und Workflow-Routing im BGB-AT-Prüfer. Fragt Fallfrage, Rolle, Anspruchsziel, Tatsachen, Fristen, Erklärungen, Beteiligte und Wunsch-Output ab, baut einen schönen Arbeitsplan und schlägt passende Spezial-Skills au... |
| `anfechtungsfolgen-paragraphen-anspruchsaufbau-zivilrecht` | Anfechtungsfolgen Paragraphen 142 122, Anspruchsaufbau Zivilrecht Bgb At, Auslegung Paragraphen 133 157: Anfechtungsfolgen Paragraphen 142 122; Anspruchsaufbau Zivilrecht Bgb At; Auslegung Paragraphen 133 157. Führt Intake, Prüfroutine,... |
| `anfechtungsfrist-erklaerung-annahmefrist-verspaetung-bedingung` | Anfechtungsfrist Erklaerung Bestaetigung, Annahmefrist Verspaetung Paragraphen 147 149, Bedingung Befristung Paragraphen 158 163: Anfechtungsfrist Erklaerung Bestaetigung; Annahmefrist Verspaetung Paragraphen 147 149; Bedingung Befristun... |
| `auslegung-sachverhalt-bgb-at-erklaerungskette-tableau` | Auslegung Sachverhalt Und Fallfrage, Bgb At Anfechtung Vor Auslegung, Bgb At Erklaerungskette Tableau: Auslegung Sachverhalt Und Fallfrage; Bgb At Anfechtung Vor Auslegung; Bgb At Erklaerungskette Tableau. Führt Intake, Prüfroutine, Norm... |
| `bgb-at-output-gutachten-memo-schriftsatz` | Output-Skill für BGB-AT-Ergebnisse: Klausurlösung im Gutachtenstil, praxisnahes Mandatsmemo, Subsumtionsraster und Schriftsatzbaustein — abhängig vom Arbeitsziel und Mandantenkontext strukturiert aufbereitet. |
| `bgb-at-rechtsschein-redteam` | Red-Team-Skill für Rechtsschein-Argumentation im BGB AT: Vollmachtsrechtsschein, Duldungs- und Anscheinsvollmacht nach BGH-Rechtsprechung, Entgegenstehende Argumente prüfen, schwache Rechtsschein-Positionen identifizieren. |
| `eigenschaftsirrtum-paragraph-einseitige-geschaefte-einwilligung` | Eigenschaftsirrtum Paragraph 119 2, Einseitige Geschaefte Minderjaehrige Paragraph 111, Einwilligung Genehmigung Paragraphen 107 Bis 109: Eigenschaftsirrtum Paragraph 119 2; Einseitige Geschaefte Minderjaehrige Paragraph 111; Einwilligun... |
| `elektronische-bea-elektronischer-zugang-erklaerungsbewusstsein` | Elektronische Form Bea Qes Formfiktion, Elektronischer Zugang Und Plattformen, Erklaerungsbewusstsein Und Potentielles Bewusstsein: Elektronische Form Bea Qes Formfiktion; Elektronischer Zugang Und Plattformen; Erklaerungsbewusstsein Und... |
| `erwerbsgeschaeft-dienst-formnichtigkeit-paragraphen` | Erwerbsgeschaeft Dienst Arbeit Paragraphen 112 113, Formnichtigkeit Paragraphen 125 129, Geschaeftsfaehigkeit Paragraphen 104 Bis 106: Erwerbsgeschaeft Dienst Arbeit Paragraphen 112 113; Formnichtigkeit Paragraphen 125 129; Geschaeftsfae... |
| `fallaufnahme-pruefprogramm-prozessform-minderjaehrige` | Bgb At Fallaufnahme Und Pruefprogramm, Bgb At Form Und Prozessform, Bgb At Minderjaehrige Fehlsubsumtion: Bgb At Fallaufnahme Und Pruefprogramm; Bgb At Form Und Prozessform; Bgb At Minderjaehrige Fehlsubsumtion. Führt Intake, Prüfroutine... |
| `gesetzesverbot-sittenwidrigkeit-gutachtenstil-klausurtechnik` | Gesetzesverbot Sittenwidrigkeit Paragraphen 134 138, Gutachtenstil Und Klausurtechnik, Handeln Im Fremden Namen Offenkundigkeit: Gesetzesverbot Sittenwidrigkeit Paragraphen 134 138; Gutachtenstil Und Klausurtechnik; Handeln Im Fremden Na... |
| `insichgeschaeft-paragraph-irrtumsanfechtung-paragraph-kauf` | Insichgeschaeft Paragraph 181, Irrtumsanfechtung Paragraph 119 1, Kauf Im Internet Und Auktionen: Insichgeschaeft Paragraph 181; Irrtumsanfechtung Paragraph 119 1; Kauf Im Internet Und Auktionen. Führt Intake, Prüfroutine, Normen-/Quelle... |
| `klausurloesungen-fehlerdiagnose-konsens-dissens-missbrauch` | Klausurloesungen Fehlerdiagnose, Konsens Dissens Paragraphen 154 155, Missbrauch Vertretungsmacht: Klausurloesungen Fehlerdiagnose; Konsens Dissens Paragraphen 154 155; Missbrauch Vertretungsmacht. Führt Intake, Prüfroutine, Normen-/Quel... |
| `paragraphen-cic-vorvertragliche-ergaenzende-vertragsauslegung` | Fristen Berechnung Paragraphen 186 193, Cic Vorvertragliche Pflichten Schnittstelle, Ergaenzende Vertragsauslegung: Fristen Berechnung Paragraphen 186 193; Cic Vorvertragliche Pflichten Schnittstelle; Ergaenzende Vertragsauslegung. Führt... |
| `personen-rechtsfaehigkeit-privatautonomie-trennungs-rechtlich` | Personen Rechtsfaehigkeit Und Handlungsfaehigkeit, Privatautonomie Trennungs Abstraktionsprinzip, Rechtlich Vorteilhaft Paragraph 107: Personen Rechtsfaehigkeit Und Handlungsfaehigkeit; Privatautonomie Trennungs Abstraktionsprinzip; Rech... |
| `schweigen-erklaerungswert-stellvertretung-routing-taeuschung` | Schweigen Und Erklaerungswert, Stellvertretung Routing Paragraphen 164 181, Taeuschung Drohung Paragraph 123: Schweigen Und Erklaerungswert; Stellvertretung Routing Paragraphen 164 181; Taeuschung Drohung Paragraph 123. Führt Intake, Prü... |
| `taschengeld-paragraph-uebermittlungsirrtum-verfuegung` | Taschengeld Paragraph 110, Uebermittlungsirrtum Paragraph 120, Verfuegung Nichtberechtigter Paragraph 185: Taschengeld Paragraph 110; Uebermittlungsirrtum Paragraph 120; Verfuegung Nichtberechtigter Paragraph 185. Führt Intake, Prüfrouti... |
| `training-fallvarianten-digitale-elemente-duldungs` | Bgb At Training Fallvarianten, Digitale Elemente Reparaturrecht Router, Duldungs Anscheinsvollmacht: Bgb At Training Fallvarianten; Digitale Elemente Reparaturrecht Router; Duldungs Anscheinsvollmacht. Führt Intake, Prüfroutine, Normen-/... |
| `verjaehrung-grundschema-vertreter-ohne-vollmacht-erteilung` | Verjaehrung Grundschema Paragraphen 194 218, Vertreter Ohne Vertretungsmacht Paragraphen 177 179, Vollmacht Erteilung Umfang Erloeschen: Verjaehrung Grundschema Paragraphen 194 218; Vertreter Ohne Vertretungsmacht Paragraphen 177 179; Vo... |
| `vertragsschluss-antrag-abgabe-willenserklaerung-invitatio-ad` | Vertragsschluss Antrag Annahme, Abgabe Willenserklaerung, Invitatio Ad Offerendum Und Werbung: Vertragsschluss Antrag Annahme; Abgabe Willenserklaerung; Invitatio Ad Offerendum Und Werbung. Führt Intake, Prüfroutine, Normen-/Quellenradar... |
| `willenserklaerung-wucher-ausbeutung-zugang-paragraph` | Willenserklaerung Tatbestand, Wucher Und Ausbeutung Paragraph 138 2, Zugang Paragraph 130: Willenserklaerung Tatbestand; Wucher Und Ausbeutung Paragraph 138 2; Zugang Paragraph 130. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweis... |
| `zugangsvereitelung-annahmeverweigerung` | Zugangsvereitelung Und Annahmeverweigerung: Zugangsvereitelung Und Annahmeverweigerung. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zusammen. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
