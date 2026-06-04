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
| `allgemein` | Einstieg, Schnelltriage und Workflow-Routing im BGB-AT-Prüfer. Fragt Fallfrage, Rolle, Anspruchsziel, Tatsachen, Fristen, Erklärungen, Beteiligte und Wunsch-Output ab, baut einen schönen Arbeitsplan und schlägt passende Spezial-Skills au... |
| `bgb-at-output-gutachten-memo-schriftsatz` | Output-Skill für BGB-AT-Ergebnisse: Klausurlösung im Gutachtenstil, praxisnahes Mandatsmemo, Subsumtionsraster und Schriftsatzbaustein — abhängig vom Arbeitsziel und Mandantenkontext strukturiert aufbereitet. |
| `bgb-at-rechtsschein-redteam` | Red-Team-Skill für Rechtsschein-Argumentation im BGB AT: Vollmachtsrechtsschein, Duldungs- und Anscheinsvollmacht nach BGH-Rechtsprechung, Entgegenstehende Argumente prüfen, schwache Rechtsschein-Positionen identifizieren. |
| `kompendium-01-anfechtungsfrist-erk-bis-bedingung-befristung` | bgb-at-pruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Anfechtungsfrist Erklaerung Bestaetigung, Annahmefrist Verspaetung Paragraphen 147 149, Bedingung Befristung Paragraphen 158 163; mit Intake, Prüfroutine, Normen... |
| `kompendium-02-fristen-berechnung-p-bis-ergaenzende-vertrags` | bgb-at-pruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Fristen Berechnung Paragraphen 186 193, Cic Vorvertragliche Pflichten Schnittstelle, Ergaenzende Vertragsauslegung; mit Intake, Prüfroutine, Normen-/Quellenradar... |
| `kompendium-03-vertragsschluss-antr-bis-invitatio-ad-offeren` | bgb-at-pruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Vertragsschluss Antrag Annahme, Abgabe Willenserklaerung, Invitatio Ad Offerendum Und Werbung; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Output... |
| `kompendium-04-agb-einbeziehung-sch-bis-anfechtung-routing` | bgb-at-pruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Agb Einbeziehung Schnittstelle Paragraphen 305 310, Amtlicher Bgb Zpo Normcheck, Anfechtung Routing; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik,... |
| `kompendium-05-anfechtungsfolgen-pa-bis-auslegung-paragraphe` | bgb-at-pruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Anfechtungsfolgen Paragraphen 142 122, Anspruchsaufbau Zivilrecht Bgb At, Auslegung Paragraphen 133 157; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislog... |
| `kompendium-06-auslegung-sachverhal-bis-bgb-at-erklaerungske` | bgb-at-pruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Auslegung Sachverhalt Und Fallfrage, Bgb At Anfechtung Vor Auslegung, Bgb At Erklaerungskette Tableau; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik... |
| `kompendium-07-bgb-at-fallaufnahme-bis-bgb-at-minderjaehrig` | bgb-at-pruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Bgb At Fallaufnahme Und Pruefprogramm, Bgb At Form Und Prozessform, Bgb At Minderjaehrige Fehlsubsumtion; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislo... |
| `kompendium-08-bgb-at-training-fall-bis-duldungs-anscheinsvo` | bgb-at-pruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Bgb At Training Fallvarianten, Digitale Elemente Reparaturrecht Router, Duldungs Anscheinsvollmacht; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik,... |
| `kompendium-09-eigenschaftsirrtum-p-bis-einwilligung-genehmi` | bgb-at-pruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Eigenschaftsirrtum Paragraph 119 2, Einseitige Geschaefte Minderjaehrige Paragraph 111, Einwilligung Genehmigung Paragraphen 107 Bis 109; mit Intake, Prüfroutine... |
| `kompendium-10-elektronische-form-b-bis-erklaerungsbewusstse` | bgb-at-pruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Elektronische Form Bea Qes Formfiktion, Elektronischer Zugang Und Plattformen, Erklaerungsbewusstsein Und Potentielles Bewusstsein; mit Intake, Prüfroutine, Norm... |
| `kompendium-11-erwerbsgeschaeft-die-bis-geschaeftsfaehigkeit` | bgb-at-pruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Erwerbsgeschaeft Dienst Arbeit Paragraphen 112 113, Formnichtigkeit Paragraphen 125 129, Geschaeftsfaehigkeit Paragraphen 104 Bis 106; mit Intake, Prüfroutine, N... |
| `kompendium-12-gesetzesverbot-sitte-bis-handeln-im-fremden-n` | bgb-at-pruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Gesetzesverbot Sittenwidrigkeit Paragraphen 134 138, Gutachtenstil Und Klausurtechnik, Handeln Im Fremden Namen Offenkundigkeit; mit Intake, Prüfroutine, Normen-... |
| `kompendium-13-insichgeschaeft-para-bis-kauf-im-internet-und` | bgb-at-pruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Insichgeschaeft Paragraph 181, Irrtumsanfechtung Paragraph 119 1, Kauf Im Internet Und Auktionen; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Out... |
| `kompendium-14-klausurloesungen-feh-bis-missbrauch-vertretun` | bgb-at-pruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Klausurloesungen Fehlerdiagnose, Konsens Dissens Paragraphen 154 155, Missbrauch Vertretungsmacht; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Ou... |
| `kompendium-15-personen-rechtsfaehi-bis-rechtlich-vorteilhaf` | bgb-at-pruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Personen Rechtsfaehigkeit Und Handlungsfaehigkeit, Privatautonomie Trennungs Abstraktionsprinzip, Rechtlich Vorteilhaft Paragraph 107; mit Intake, Prüfroutine, N... |
| `kompendium-16-schweigen-und-erklae-bis-taeuschung-drohung-p` | bgb-at-pruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Schweigen Und Erklaerungswert, Stellvertretung Routing Paragraphen 164 181, Taeuschung Drohung Paragraph 123; mit Intake, Prüfroutine, Normen-/Quellenradar, Bewe... |
| `kompendium-17-taschengeld-paragrap-bis-verfuegung-nichtbere` | bgb-at-pruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Taschengeld Paragraph 110, Uebermittlungsirrtum Paragraph 120, Verfuegung Nichtberechtigter Paragraph 185; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweisl... |
| `kompendium-18-verjaehrung-grundsch-bis-vollmacht-erteilung` | bgb-at-pruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Verjaehrung Grundschema Paragraphen 194 218, Vertreter Ohne Vertretungsmacht Paragraphen 177 179, Vollmacht Erteilung Umfang Erloeschen; mit Intake, Prüfroutine,... |
| `kompendium-19-willenserklaerung-ta-bis-zugang-paragraph-130` | bgb-at-pruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Willenserklaerung Tatbestand, Wucher Und Ausbeutung Paragraph 138 2, Zugang Paragraph 130; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmust... |
| `kompendium-20-zugangsvereitelung-u-bis-zugangsvereitelung-u` | bgb-at-pruefer: eigenständiger Arbeits-Skill zu Zugangsvereitelung Und Annahmeverweigerung; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
