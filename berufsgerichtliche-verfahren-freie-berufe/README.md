# Berufsgerichtliche Verfahren Freie Berufe

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`berufsgerichtliche-verfahren-freie-berufe`) | [`berufsgerichtliche-verfahren-freie-berufe.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/berufsgerichtliche-verfahren-freie-berufe.zip) |

Dieses Plugin hat (bewusst) keine eigene Demonstrations-Akte.

<!-- END plugin-sofort-download-section (autogen) -->

Plugin für anwaltsgerichtliche und berufsgerichtliche Verfahren gegen Anwälte, Patentanwälte, Steuerberater, Wirtschaftsprüfer und Notare: Kammeraufsicht, Rüge, Disziplinarverfahren, Zulassung, Vermögensverfall, beA, Werbung, Sachlichkeit und Rechtsmittel.

## Worum es geht

Dieses Plugin ist ein experimentelles Arbeits- und Lernwerkzeug. Es soll keine echten Amts-, Mandats-, Steuer-, Prüfungs- oder Berufsgeheimnisse aufnehmen, solange die technische und rechtliche Umgebung dafür nicht ausdrücklich freigegeben ist. Es arbeitet am besten mit anonymisierten, abstrahierten oder synthetischen Fällen und mit Dokumenten, die vor der Nutzung datenschutz- und geheimnisschutzrechtlich geprüft wurden.

## Arbeitsweise

Der Allgemein-Skill startet kurz, sortiert Rolle, Verfahrensstand, Frist, Unterlagen und gewünschtes Arbeitsprodukt und routet dann in die passenden Spezial-Skills. Jeder Skill verlangt Quellenhygiene: Normen, Behördenhinweise, Formulare und Rechtsprechung werden vor tragenden Aussagen live aus amtlichen oder frei zugänglichen Quellen geprüft; keine BeckRS-, juris-, Kommentar- oder Aufsatz-Blindzitate.

## Typische Outputs

- Kurzvermerk und Risikoampel
- Checkliste für den nächsten Arbeitstag
- Fragenliste an Behörde, Gericht, Kammer, Mandant, Partei oder Zeugen
- Entwurf für Verfügung, Vermerk, Schriftsatz, Antrag, E-Mail oder Gesprächsleitfaden
- Red-Team-Check gegen Fristenfehler, Zuständigkeitsfehler und Scheingenauigkeit

## Installation

ZIP aus dem aktuellen Release laden und in Claude Code oder Cowork über Customize Plugins installieren.

## Lizenz

Apache-2.0 OR MIT — Auswahl beim Empfänger.


<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 28 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `allgemein-kaltstart-und-routing` | Allgemeiner Kaltstart und Routing: prüft führt vom ersten Satz oder Dokument in den richtigen Arbeitsmodus in berufsgerichtlichen Verfahren freier Berufe; mit Normencheck, Aktenlog, Verteidigungslinie, Verhältnismäßigkeit und Rechtsmitte... |
| `dokumentenintake-und-aktenlog` | Dokumentenintake und Aktenlog: prüft ordnet Uploads, Eingangspost, Aktenbestandteile und fehlende Unterlagen in berufsgerichtlichen Verfahren freier Berufe; mit Normencheck, Aktenlog, Verteidigungslinie, Verhältnismäßigkeit und Rechtsmit... |
| `kompendium-01-quellen-und-rechtspr-bis-haftpflichtdeckung-b` | berufsgerichtliche-verfahren-freie-berufe: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Quellen Und Rechtsprechungscheck, Frist Und Zustaendigkeit Cockpit, Haftpflichtdeckung Berufsverfahren Praevention, Haftpflichtdeckung... |
| `kompendium-02-kammeranhoerung-fris-bis-patentanwalt-fristen` | berufsgerichtliche-verfahren-freie-berufe: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Kammeranhoerung Fristverlaengerung Praevention, Kammeranhoerung Fristverlaengerung Verteidigung, Patentanwalt Fristenversaeumnis Epo D... |
| `kompendium-03-sanktionen-mandatsan-bis-aktenherausgabe-zuru` | berufsgerichtliche-verfahren-freie-berufe: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Sanktionen Mandatsannahme Praevention, Sanktionen Mandatsannahme Verteidigung, Aktenherausgabe Zurueckbehaltungsrecht Praevention, Akt... |
| `kompendium-04-bea-nicht-in-betrieb-bis-berufsgericht-anschu` | berufsgerichtliche-verfahren-freie-berufe: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Bea Nicht In Betrieb Praevention, Bea Nicht In Betrieb Verteidigung, Berufsgericht Anschuldigungsschrift Praevention, Berufsgericht An... |
| `kompendium-05-berufsgericht-beweis-bis-berufsgesellschaft-c` | berufsgerichtliche-verfahren-freie-berufe: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Berufsgericht Beweisaufnahme Praevention, Berufsgericht Beweisaufnahme Verteidigung, Berufsgesellschaft Compliance Praevention, Berufs... |
| `kompendium-06-berufspflicht-und-ve-bis-berufsrecht-ki-nutzu` | berufsgerichtliche-verfahren-freie-berufe: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Berufspflicht Und Verhaeltnismaessigkeit Praevention, Berufspflicht Und Verhaeltnismaessigkeit Verteidigung, Berufsrecht Ki Nutzung Pr... |
| `kompendium-07-berufsverbot-und-sof-bis-datenpanne-berufstra` | berufsgerichtliche-verfahren-freie-berufe: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Berufsverbot Und Sofortvollzug Praevention, Berufsverbot Und Sofortvollzug Verteidigung, Datenpanne Berufstraeger Praevention, Datenpa... |
| `kompendium-08-dienstaufsicht-notar-bis-fremdgeld-anderkonto` | berufsgerichtliche-verfahren-freie-berufe: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Dienstaufsicht Notar Beschwerde Praevention, Dienstaufsicht Notar Beschwerde Verteidigung, Fremdgeld Anderkonto Pflicht Praevention, F... |
| `kompendium-09-geldwaeschepflicht-k-bis-honorarvereinbarung` | berufsgerichtliche-verfahren-freie-berufe: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Geldwaeschepflicht Kanzlei Praevention, Geldwaeschepflicht Kanzlei Verteidigung, Honorarvereinbarung Erfolgshonorar Praevention, Honor... |
| `kompendium-10-interessenkollision-bis-kanzleisitz-und-erre` | berufsgerichtliche-verfahren-freie-berufe: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Interessenkollision Mehrfachvertretung Praevention, Interessenkollision Mehrfachvertretung Verteidigung, Kanzleisitz Und Erreichbarkei... |
| `kompendium-11-kollegenbeleidigung-bis-mandatskuendigung-zu` | berufsgerichtliche-verfahren-freie-berufe: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Kollegenbeleidigung Und Strafbarkeit Praevention, Kollegenbeleidigung Und Strafbarkeit Verteidigung, Mandatskuendigung Zur Unzeit Prae... |
| `kompendium-12-notar-anderkonto-aus-bis-notar-geldwaesche-im` | berufsgerichtliche-verfahren-freie-berufe: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Notar Anderkonto Auszahlungsreife Praevention, Notar Anderkonto Auszahlungsreife Verteidigung, Notar Geldwaesche Immobilie Praevention... |
| `kompendium-13-notar-gesellschafter-bis-notar-unparteilichke` | berufsgerichtliche-verfahren-freie-berufe: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Notar Gesellschafterliste Fehler Praevention, Notar Gesellschafterliste Fehler Verteidigung, Notar Unparteilichkeit Familiengesellscha... |
| `kompendium-14-patentanwalt-erfinde-bis-patentanwalt-vertret` | berufsgerichtliche-verfahren-freie-berufe: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Patentanwalt Erfinderkonflikt Praevention, Patentanwalt Erfinderkonflikt Verteidigung, Patentanwalt Vertretungsbefugnis Grenze Praeven... |
| `kompendium-15-rak-ruege-unsachlich-bis-rechtsmittel-berufsg` | berufsgerichtliche-verfahren-freie-berufe: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Rak Ruege Unsachlichkeit Praevention, Rak Ruege Unsachlichkeit Verteidigung, Rechtsmittel Berufsgericht Praevention, Rechtsmittel Beru... |
| `kompendium-16-social-media-berufsr-bis-steuerberater-153-ao` | berufsgerichtliche-verfahren-freie-berufe: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Social Media Berufsrecht Praevention, Social Media Berufsrecht Verteidigung, Steuerberater 153 Ao Berichtigung Praevention, Steuerbera... |
| `kompendium-17-steuerberater-berufs-bis-steuerberater-vorbeh` | berufsgerichtliche-verfahren-freie-berufe: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Steuerberater Berufsgericht Stberg, Steuerberater Unterlagenherausgabe Praevention, Steuerberater Unterlagenherausgabe Verteidigung, S... |
| `kompendium-18-steuerberater-vorbeh-bis-vermoegensverfall-zu` | berufsgerichtliche-verfahren-freie-berufe: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Steuerberater Vorbehaltsaufgabe Verteidigung, Vergleich Mit Kammer Praevention, Vergleich Mit Kammer Verteidigung, Vermoegensverfall Z... |
| `kompendium-19-vermoegensverfall-zu-bis-werbung-robe-kanzlei` | berufsgerichtliche-verfahren-freie-berufe: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Vermoegensverfall Zulassungswiderruf Verteidigung, Verschwiegenheit Cloud Dienstleister Praevention, Verschwiegenheit Cloud Dienstleis... |
| `kompendium-20-werbung-robe-kanzlei-bis-wirtschaftspruefer-t` | berufsgerichtliche-verfahren-freie-berufe: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Werbung Robe Kanzleimarketing Verteidigung, Wirtschaftspruefer Qualitaetskontrolle Praevention, Wirtschaftspruefer Qualitaetskontrolle... |
| `kompendium-21-wirtschaftspruefer-t-bis-anwaltsgericht-brao` | berufsgerichtliche-verfahren-freie-berufe: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Wirtschaftspruefer Testat Widerruf Verteidigung, Wirtschaftspruefer Unabhaengigkeit Praevention, Wirtschaftspruefer Unabhaengigkeit Ve... |
| `kompendium-22-bea-nutzungspflichte-bis-kollegenbeleidigung` | berufsgerichtliche-verfahren-freie-berufe: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Bea Nutzungspflichten, Entscheidungsvorlage, Kanzleisitz Und Zustellbarkeit, Kollegenbeleidigung Unsachlichkeit; mit Intake, Prüfrouti... |
| `kompendium-23-mandanten-oder-betei-bis-protokoll-und-nachbe` | berufsgerichtliche-verfahren-freie-berufe: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Mandanten Oder Beteiligtenkommunikation, Notar Disziplinar Bnoto, Patentanwalt Berufsgericht Pao, Protokoll Und Nachbereitung; mit Int... |
| `kompendium-24-robe-werbung-sachlic-bis-vermoegensverfall-zu` | berufsgerichtliche-verfahren-freie-berufe: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Robe Werbung Sachlichkeit, Schriftsatz Vermerk Und Mustertext, Sitzungs Und Terminvorbereitung, Vermoegensverfall Zulassungswiderruf;... |
| `kompendium-25-wirtschaftspruefer-b-bis-wirtschaftspruefer-b` | berufsgerichtliche-verfahren-freie-berufe: eigenständiger Arbeits-Skill zu Wirtschaftspruefer Berufsaufsicht Wpo; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck. |
| `red-team-qualitygate` | Red-Team-Qualitygate: prüft prüft Ergebnis auf Fristenfehler, Zuständigkeitsfehler, Scheinpräzision und Ton in berufsgerichtlichen Verfahren freier Berufe; mit Normencheck, Aktenlog, Verteidigungslinie, Verhältnismäßigkeit und Rechtsmitt... |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
