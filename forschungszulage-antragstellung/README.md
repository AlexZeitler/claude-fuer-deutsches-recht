# Forschungszulage-Antragstellung

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`forschungszulage-antragstellung`) | [`forschungszulage-antragstellung.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/forschungszulage-antragstellung.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **Forschungszulage Riedblick Sensorik GmbH** (`forschungszulage-sensorik-startup-taunus`) | [Gesamt-PDF lesen](../testakten/forschungszulage-sensorik-startup-taunus/gesamt-pdf/forschungszulage-sensorik-startup-taunus_gesamt.pdf) | [`testakte-forschungszulage-sensorik-startup-taunus.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-forschungszulage-sensorik-startup-taunus.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

Plugin für die steuerliche Forschungsförderung nach dem Forschungszulagengesetz: Fördercheck, BSFZ-Bescheinigung, Projektbeschreibung, FuE-Abgrenzung, Bemessungsgrundlage, Finanzamt-Antrag, Auszahlung, Verlust-/Krisenlage, Dokumentation für Außenprüfung, Kumulierung und Nachbesserung.

Das Plugin ist für Unternehmen, Start-ups, Mittelstand, Steuerberaterinnen, Rechtsanwälte, CFOs und Produkt-/Entwicklungsteams gebaut. Es übersetzt technische Entwicklung in die Sprache, die BSFZ und Finanzamt brauchen: Neuheit, Risiko, systematisches Vorgehen, förderfähige Aufwendungen und saubere Belege. Es kann bewusst zwei Geschwindigkeiten: geführter Modus für Einsteiger und harter Ampel-/Cashflow-Modus für Profis.

## Quellen-Gate

Vor jeder belastbaren Ausgabe live prüfen:

- Forschungszulagengesetz auf `gesetze-im-internet.de`, insbesondere §§ 1 bis 7 und § 10 FZulG.
- BSFZ-Antragsverfahren: zweistufig, erst FuE-Bescheinigung bei der BSFZ, dann Antrag beim Finanzamt.
- BMF-Forschungszulage und BMF-Schreiben vom 07.02.2023, soweit noch nicht durch ein neues finales Schreiben ersetzt.
- Änderungen ab 2026: Bemessungsgrundlagenhöchstbetrag 12 Mio. Euro, 20-%-Pauschale für Gemein- und Betriebskosten bei nach dem 31.12.2025 begonnenen Vorhaben, Eigenleistung 100 Euro pro Stunde bis max. 40 Stunden/Woche.

## Skill-Matrix

| Skill | Wofür? |
| --- | --- |
| `allgemein` | Einstieg, Triage, Förderroute und Projektaufnahme |
| `fz-foerdercheck-kaltstart` | Anspruchsberechtigung, Projektart, Jahre, Risiken, Sofortpotenzial |
| `fz-bsfz-bescheinigung-projektbeschreibung` | BSFZ-Antrag, Vorhabenbeschreibung, technische Neuheit, Risiko |
| `fz-plaedoyer-begruendung-und-verteidigung` | Plädoyer, Begründung und Verteidigung gegenüber BSFZ, Finanzamt, Geschäftsführung, Insolvenzverwaltung oder Einspruchsstelle |
| `fz-fue-definition-frascati-abgrenzung` | Grundlagenforschung, industrielle Forschung, experimentelle Entwicklung |
| `fz-bemessungsgrundlage-2026` | Personal, Eigenleistung, Auftragsforschung, Wirtschaftsgüter, 12-Mio.-Grenze |
| `fz-finanzamt-festsetzung-auszahlung` | Antrag beim Finanzamt, Anrechnung, Auszahlung, Vorauszahlungssenkung |
| `fz-insolvenz-verlust-liquiditaet` | Krise, Verlustjahr, Insolvenz, Forderungs-/Masseblick, Liquidität |
| `fz-dokumentationspaket-betriebspruefung` | Stundenzettel, Projektakte, Kostenbelege, Prüferpaket |
| `fz-kumulierung-beihilfen-agvo` | Doppelförderung, AGVO, andere Zuschüsse, EU/EWR-Auftragsforschung |
| `fz-ablehnung-nachbesserung-einspruch` | BSFZ-Nachforderung, Ablehnung, Finanzamt-Einspruch, Reparatur |
| `fz-roadmap-mehrjahresantrag` | Mehrjahresstrategie, rückwirkende Jahre, Jahreswechsel, Portfolio |

## Typische Startpunkte

| Situation | Start |
| --- | --- |
| "Wir wissen nicht, ob unser Vorhaben FuE ist" | `allgemein` → `fz-foerdercheck-kaltstart` |
| "Wir müssen den BSFZ-Antrag schreiben" | `fz-fue-definition-frascati-abgrenzung` → `fz-bsfz-bescheinigung-projektbeschreibung` |
| "Wir brauchen ein überzeugendes Plädoyer / eine Begründung" | `fz-plaedoyer-begruendung-und-verteidigung` |
| "Wir wollen wissen, wie viel Geld kommt" | `fz-bemessungsgrundlage-2026` → `fz-finanzamt-festsetzung-auszahlung` |
| "Wir sind im Verlust / in der Krise" | `fz-insolvenz-verlust-liquiditaet` |
| "BSFZ fragt nach oder lehnt ab" | `fz-ablehnung-nachbesserung-einspruch` |

<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 24 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `fz-foerdercheck-kaltstart` | Schneller Fördercheck Forschungszulage in zehn Minuten: Anspruchsberechtigung, FuE-Kategorie nach Frascati, KMU-Status, Personalkosten-Schwelle, Projektjahre, Kostenarten, BSFZ-/Finanzamt-Status, Kumulierung, Ausschlussrisiken und realis... |
| `kompendium-01-allgemein-bis-workflow-fristen-und` | forschungszulage-antragstellung: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Allgemein, Chronologie Und Belegmatrix, Fristen Und Risikoampel; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qu... |
| `kompendium-02-workflow-mandantenko-bis-spezial-fzulg-friste` | forschungszulage-antragstellung: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Mandantenkommunikation, Redteam Qualitygate, Fzulg Fristen Form Und Zustaendigkeit; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik,... |
| `kompendium-03-spezial-mehrjahresro-bis-forsch-bsfz-pruefung` | forschungszulage-antragstellung: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Mehrjahresroadmap Fristennotiz Und Naechster Schritt, Fz Auftragsforschung Vertragsgestaltung, Forsch Bsfz Pruefung Spezial; mit Intake, Prüfrou... |
| `kompendium-04-fz-betriebspruefung-bis-fz-historie-und-rech` | forschungszulage-antragstellung: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Fz Betriebspruefung Strategie, Fz Finanzamt Festsetzung Auszahlung, Fz Historie Und Rechtsgrundlagen; mit Intake, Prüfroutine, Normen-/Quellenra... |
| `kompendium-05-fz-insolvenz-verlust-bis-forsch-projektbeschr` | forschungszulage-antragstellung: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Fz Insolvenz Verlust Liquiditaet, Forsch Konzernverbund Forschung Spezial, Forsch Projektbeschreibung Bauleiter; mit Intake, Prüfroutine, Normen... |
| `kompendium-06-forsch-stundenaufzei-bis-fz-bemessungsgrundla` | forschungszulage-antragstellung: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Forsch Stundenaufzeichnung Leitfaden, Fz Ablehnung Nachbesserung Einspruch, Fz Bemessungsgrundlage 2026; mit Intake, Prüfroutine, Normen-/Quelle... |
| `kompendium-07-fz-bescheidung-recht-bis-fz-dokumentationspak` | forschungszulage-antragstellung: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Fz Bescheidung Rechtsmittel, Fz Bsfz Bescheinigung Projektbeschreibung, Fz Dokumentationspaket Betriebspruefung; mit Intake, Prüfroutine, Normen... |
| `kompendium-08-fz-fue-abgrenzung-gr-bis-fz-konzern-und-organ` | forschungszulage-antragstellung: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Fz Fue Abgrenzung Grenzfaelle, Fz Fue Definition Frascati Abgrenzung, Fz Konzern Und Organschaft Spezial; mit Intake, Prüfroutine, Normen-/Quell... |
| `kompendium-09-fz-koordinierung-zwe-bis-fz-personalkosten-un` | forschungszulage-antragstellung: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Fz Koordinierung Zwei Foerderwege, Fz Kumulierung Beihilfen Agvo, Fz Personalkosten Und Stundennachweis; mit Intake, Prüfroutine, Normen-/Quelle... |
| `kompendium-10-fz-plaedoyer-begruen-bis-fz-start-up-und-pers` | forschungszulage-antragstellung: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Fz Plaedoyer Begruendung Und Verteidigung, Fz Roadmap Mehrjahresantrag, Fz Start Up Und Personengesellschaft; mit Intake, Prüfroutine, Normen-/Q... |
| `kompendium-11-spezial-abgrenzung-c-bis-spezial-antrag-zahle` | forschungszulage-antragstellung: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Abgrenzung Compliance Dokumentation Und Akte, Adaptiver Dokumentenmatrix Und Lueckenliste, Antrag Zahlen Schwellen Und Berechnung; mit Intake, P... |
| `kompendium-12-spezial-antragstellu-bis-spezial-beihilfen-be` | forschungszulage-antragstellung: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Antragstellung Tatbestand Beweis Und Belege, Auszahlung Internationaler Bezug Und Schnittstellen, Beihilfen Beweislast Und Darlegungslast; mit I... |
| `kompendium-13-spezial-bemessungsgr-bis-spezial-definition-a` | forschungszulage-antragstellung: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Bemessungsgrundlage Mehrparteien Konflikt Und Interessen, Bsfz Behoerden Gericht Und Registerweg, Definition Abschlussprodukt Und Uebergabe; mit... |
| `kompendium-14-spezial-dokumentatio-bis-spezial-foerdercheck` | forschungszulage-antragstellung: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Dokumentation Mandantenentscheidung, Einspruch Sonderfall Und Edge Case, Foerdercheck Risikoampel Und Gegenargumente; mit Intake, Prüfroutine, N... |
| `kompendium-15-spezial-forschungszu-bis-spezial-portaltexte` | forschungszulage-antragstellung: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Forschungszulage Erstpruefung Und Mandatsziel, Insolvenzlage Red Team Und Qualitaetskontrolle, Portaltexte Schriftsatz Brief Und Memo Bausteine;... |
| `kompendium-16-spezial-verlust-form-bis-spezial-zeichenbudge` | forschungszulage-antragstellung: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Verlust Formular Portal Und Einreichung, Zeichenbudgets Verhandlung Vergleich Und Eskalation; mit Intake, Prüfroutine, Normen-/Quellenradar, Bew... |
| `spezial-finanzamt-livequellen-und-rechtsprechungscheck` | Finanzamt: Livequellen- und Rechtsprechungscheck im Plugin forschungszulage antragstellung; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Standardprüfung. |
| `workflow-anschluss-skills-router` | Anschluss-Skills Router im Plugin forschungszulage-antragstellung: schlägt nach der ersten Prüfung die passenden Spezialskills aus demselben Plugin vor. |
| `workflow-dokumentenintake` | Dokumentenintake im Plugin forschungszulage-antragstellung: liest Uploads, sortiert Dokumentarten, markiert Fristen und baut eine knappe Arbeitsakte. |
| `workflow-kaltstart-und-routing` | Kaltstart und Routing im Plugin forschungszulage-antragstellung: führt vom ersten Satz oder Dokument in den passenden Arbeitsweg, erkennt Rolle, Ziel, Risiko und Anschluss-Skills. |
| `workflow-output-waehlen` | Output wählen im Plugin forschungszulage-antragstellung: entscheidet zwischen Memo, Schriftsatz, Tabelle, Brief, Checkliste, Vermerk, Redline oder Mandantenübersetzung. |
| `workflow-rechtsquellen-livecheck` | Rechtsquellen-Livecheck im Plugin forschungszulage-antragstellung: zwingt vor tragenden Aussagen zum aktuellen Quellencheck bei Gesetzen, Behörden, Gerichten und Formularen. |
| `workflow-unterlagen-lueckenliste` | Unterlagen- und Lückenliste im Plugin forschungszulage-antragstellung: erstellt eine präzise Nachforderungsliste statt allgemeiner Fragebögen. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
