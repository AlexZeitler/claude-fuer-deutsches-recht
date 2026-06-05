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
| `abgrenzung-adaptiver-antrag` | Spezial Abgrenzung Compliance Dokumentation Und Akte, Spezial Adaptiver Dokumentenmatrix Und Lueckenliste, Spezial Antrag Zahlen Schwellen Und Berechnung: Spezial Abgrenzung Compliance Dokumentation Und Akte; Spezial Adaptiver Dokumenten... |
| `allgemein-workflow-chronologie-workflow-fristen` | Allgemein, Workflow Chronologie Und Belegmatrix, Workflow Fristen Und Risikoampel: Allgemein; Workflow Chronologie Und Belegmatrix; Workflow Fristen Und Risikoampel. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmus... |
| `antragstellung-auszahlung-beihilfen-beweislast` | Spezial Antragstellung Tatbestand Beweis Und Belege, Spezial Auszahlung Internationaler Bezug Und Schnittstellen, Spezial Beihilfen Beweislast Und Darlegungslast: Spezial Antragstellung Tatbestand Beweis Und Belege; Spezial Auszahlung In... |
| `bemessungsgrundlage-interessen-bsfz-definition` | Spezial Bemessungsgrundlage Mehrparteien Konflikt Und Interessen, Spezial Bsfz Behörden Gericht Und Registerweg, Spezial Definition Abschlussprodukt Und Übergabe: Spezial Bemessungsgrundlage Mehrparteien Konflikt Und Interessen; Spezial... |
| `forsch-stundenaufzeichnung-fz-ablehnung-bemessungsgrundlage` | Forsch Stundenaufzeichnung Leitfaden, Fz Ablehnung Nachbesserung Einspruch, Fz Bemessungsgrundlage 2026: Forsch Stundenaufzeichnung Leitfaden; Fz Ablehnung Nachbesserung Einspruch; Fz Bemessungsgrundlage 2026. Führt Intake, Prüfroutine,... |
| `forschungszulage-insolvenzlage-red-portaltexte` | Spezial Forschungszulage Erstpruefung Und Mandatsziel, Spezial Insolvenzlage Red Team Und Qualitaetskontrolle, Spezial Portaltexte Schriftsatz Brief Und Memo Bausteine: Spezial Forschungszulage Erstpruefung Und Mandatsziel; Spezial Insol... |
| `fz-bescheidung-fz-bsfz-fz-dokumentationspaket` | Fz Bescheidung Rechtsmittel, Fz Bsfz Bescheinigung Projektbeschreibung, Fz Dokumentationspaket Betriebspruefung: Fz Bescheidung Rechtsmittel; Fz Bsfz Bescheinigung Projektbeschreibung; Fz Dokumentationspaket Betriebspruefung. Führt Intak... |
| `fz-betriebspruefung-fz-finanzamt-fz-historie` | Fz Betriebspruefung Strategie, Fz Finanzamt Festsetzung Auszahlung, Fz Historie Und Rechtsgrundlagen: Fz Betriebspruefung Strategie; Fz Finanzamt Festsetzung Auszahlung; Fz Historie Und Rechtsgrundlagen. Führt Intake, Prüfroutine, Normen... |
| `fz-foerdercheck-kaltstart` | Schneller Fördercheck Forschungszulage in zehn Minuten: Anspruchsberechtigung, FuE-Kategorie nach Frascati, KMU-Status, Personalkosten-Schwelle, Projektjahre, Kostenarten, BSFZ-/Finanzamt-Status, Kumulierung, Ausschlussrisiken und realis... |
| `fz-fue-fz-fue-fz-konzern` | Fz Fue Abgrenzung Grenzfaelle, Fz Fue Definition Frascati Abgrenzung, Fz Konzern Und Organschaft Spezial: Fz Fue Abgrenzung Grenzfaelle; Fz Fue Definition Frascati Abgrenzung; Fz Konzern Und Organschaft Spezial. Führt Intake, Prüfroutine... |
| `fz-insolvenz-forsch-konzernverbund-projektbeschreibung-bauleiter` | Fz Insolvenz Verlust Liquiditaet, Forsch Konzernverbund Forschung Spezial, Forsch Projektbeschreibung Bauleiter: Fz Insolvenz Verlust Liquiditaet; Forsch Konzernverbund Forschung Spezial; Forsch Projektbeschreibung Bauleiter. Führt Intak... |
| `fz-koordinierung-fz-kumulierung-fz-personalkosten` | Fz Koordinierung Zwei Foerderwege, Fz Kumulierung Beihilfen Agvo, Fz Personalkosten Und Stundennachweis: Fz Koordinierung Zwei Foerderwege; Fz Kumulierung Beihilfen Agvo; Fz Personalkosten Und Stundennachweis. Führt Intake, Prüfroutine,... |
| `fz-plaedoyer-fz-roadmap-fz-start` | Fz Plaedoyer Begründung Und Verteidigung, Fz Roadmap Mehrjahresantrag, Fz Start Up Und Personengesellschaft: Fz Plaedoyer Begründung Und Verteidigung; Fz Roadmap Mehrjahresantrag; Fz Start Up Und Personengesellschaft. Führt Intake, Prüfr... |
| `mandantenentscheidung-einspruch-sonderfall-foerdercheck` | Spezial Dokumentation Mandantenentscheidung, Spezial Einspruch Sonderfall Und Edge Case, Spezial Foerdercheck Risikoampel Und Gegenargumente: Spezial Dokumentation Mandantenentscheidung; Spezial Einspruch Sonderfall Und Edge Case; Spezia... |
| `mehrjahresroadmap-fristennotiz-fz-auftragsforschung-forsch-bsfz` | Spezial Mehrjahresroadmap Fristennotiz Und Naechster Schritt, Fz Auftragsforschung Vertragsgestaltung, Forsch Bsfz Prüfung Spezial: Spezial Mehrjahresroadmap Fristennotiz Und Naechster Schritt; Fz Auftragsforschung Vertragsgestaltung; Fo... |
| `spezial-finanzamt-livequellen-und-rechtsprechungscheck` | Finanzamt: Livequellen- und Rechtsprechungscheck im Plugin forschungszulage antragstellung; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Standardprüfung. |
| `verlust-zeichenbudgets` | Spezial Verlust Formular Portal Und Einreichung, Spezial Zeichenbudgets Verhandlung Vergleich Und Eskalation: Spezial Verlust Formular Portal Und Einreichung; Spezial Zeichenbudgets Verhandlung Vergleich Und Eskalation. Führt Intake, Prü... |
| `workflow-anschluss-skills-router` | Anschluss-Skills Router im Plugin forschungszulage-antragstellung: schlägt nach der ersten Prüfung die passenden Spezialskills aus demselben Plugin vor. |
| `workflow-dokumentenintake` | Dokumentenintake im Plugin forschungszulage-antragstellung: liest Uploads, sortiert Dokumentarten, markiert Fristen und baut eine knappe Arbeitsakte. |
| `workflow-kaltstart-und-routing` | Kaltstart und Routing im Plugin forschungszulage-antragstellung: führt vom ersten Satz oder Dokument in den passenden Arbeitsweg, erkennt Rolle, Ziel, Risiko und Anschluss-Skills. |
| `workflow-mandantenkommunikation-workflow-redteam-fzulg` | Workflow Mandantenkommunikation, Workflow Redteam Qualitygate, Spezial Fzulg Fristen Form Und Zustaendigkeit: Workflow Mandantenkommunikation; Workflow Redteam Qualitygate; Spezial Fzulg Fristen Form Und Zustaendigkeit. Führt Intake, Prü... |
| `workflow-output-waehlen` | Output wählen im Plugin forschungszulage-antragstellung: entscheidet zwischen Memo, Schriftsatz, Tabelle, Brief, Checkliste, Vermerk, Redline oder Mandantenübersetzung. |
| `workflow-rechtsquellen-livecheck` | Rechtsquellen-Livecheck im Plugin forschungszulage-antragstellung: zwingt vor tragenden Aussagen zum aktuellen Quellencheck bei Gesetzen, Behörden, Gerichten und Formularen. |
| `workflow-unterlagen-lueckenliste` | Unterlagen- und Lückenliste im Plugin forschungszulage-antragstellung: erstellt eine präzise Nachforderungsliste statt allgemeiner Fragebögen. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
