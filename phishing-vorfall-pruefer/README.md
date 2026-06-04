# Phishing-Vorfall-Prüfer

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`phishing-vorfall-pruefer`) | [`phishing-vorfall-pruefer.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/phishing-vorfall-pruefer.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **Akte Phishing-Vorfall Mayer ./. Sparkasse Berlin** (`phishing-vorfall-mayer-sparkasse-berlin`) | [Gesamt-PDF lesen](../testakten/phishing-vorfall-mayer-sparkasse-berlin/gesamt-pdf/phishing-vorfall-mayer-sparkasse-berlin_gesamt.pdf) | [`testakte-phishing-vorfall-mayer-sparkasse-berlin.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-phishing-vorfall-mayer-sparkasse-berlin.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

Freistehendes Plugin für anwaltliche Prüfung von Online-Banking-Phishing, pushTAN-/photoTAN-Vorfällen, Call-ID-Spoofing, gefälschten Bankhotlines, Social Engineering und streitigen Erstattungsansprüchen gegen Zahlungsdienstleister.

Das Plugin arbeitet entlang des typischen Mandats:

1. Intake: Konto, Zahlungsinstrument, Schaden, Autorisierung, Sperr- und Anzeigeverlauf.
2. Rechtsrahmen: § 675u BGB, § 675v BGB, § 675w BGB, § 675l BGB, § 676b BGB und § 55 ZAG.
3. Beweisprüfung: TAN-Dialog, App-Screens, Banklogs, IP-Adressen, Device-Binding, SCA, Transaktionsmonitoring, Warnhinweise.
4. Risikomatrix: nicht autorisierter Zahlungsvorgang, grobe Fahrlässigkeit, Bankpflichtverletzung, Mitverschulden/Quotelung, Ombudsmann oder Klage.
5. Output: Erstbewertung, Bankaufforderung, Ombudsmann-Antrag, Klagegerüst, Beweisantritts- und Log-Anforderung.

## Inhalt

- `skills/phishing-vorfall-pruefen/SKILL.md` - geführter Hauptworkflow.
- `references/rechtsrahmen.md` - Arbeitsrahmen mit amtlichen Normlinks.
- `assets/checklisten/` - Intake, Beweis- und Logmatrix, grobe-Fahrlässigkeit-Ampel.
- `assets/vorlagen/` - Bankaufforderung, Ombudsmann-Antrag, Klagegerüst.
- `scripts/phishing_case_gate.py` - kleines Offline-Gate für strukturierte Fallbewertung.

## Arbeitsprinzip

Das Plugin entscheidet keinen Fall automatisch. Es zwingt zur sauberen Trennung:

- Hat der Kunde den konkreten Zahlungsvorgang autorisiert?
- Liegt ein Einwand aus § 675v BGB vor?
- Was ist bewiesen, was nur behauptet?
- Welche Banklogs müssen verlangt werden?
- Ist Schlichtung, Teilvergleich oder Klage der bessere nächste Schritt?

Alle rechtlichen Bewertungen sind Arbeitsentwürfe und müssen durch eine qualifizierte Person geprüft werden.

<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 24 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `kompendium-01-allgemein-bis-workflow-fristen-und` | phishing-vorfall-pruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Allgemein, Chronologie Und Belegmatrix, Fristen Und Risikoampel; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitäts... |
| `kompendium-02-workflow-mandantenko-bis-phishing-tan-verfahr` | phishing-vorfall-pruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Mandantenkommunikation, Redteam Qualitygate, Phishing Tan Verfahren Vergleich; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster... |
| `kompendium-03-spezial-klage-friste-bis-phish-banking-trojan` | phishing-vorfall-pruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Klage Fristennotiz Und Naechster Schritt, Vorfall Fristen Form Und Zustaendigkeit, Phish Banking Trojaner Haftung Spezial; mit Intake, Prüfroutine, Nor... |
| `kompendium-04-phishing-arbeitnehme-bis-phish-ceo-fraud-konz` | phishing-vorfall-pruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Phishing Arbeitnehmer Haftung, Phishing Bgb 675u Haftung, Phish Ceo Fraud Konzern Spezial; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik,... |
| `kompendium-05-phish-incident-triag-bis-phishing-arten-erken` | phishing-vorfall-pruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Phish Incident Triage Bauleiter, Phish Meldepflichten Leitfaden, Phishing Arten Erkennen; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, O... |
| `kompendium-06-phishing-aufsicht-ba-bis-phishing-banking-app` | phishing-vorfall-pruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Phishing Aufsicht Bafin, Phishing Bank Strategie, Phishing Banking App Malware; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuste... |
| `kompendium-07-phishing-bea-notfall-bis-phishing-erstkontakt` | phishing-vorfall-pruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Phishing Bea Notfall Anwalt, Phishing Bgb 675v Grobfahrlaessig, Phishing Erstkontakt Mandant; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogi... |
| `kompendium-08-phishing-faelle-rent-bis-phishing-mit-geschae` | phishing-vorfall-pruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Phishing Faelle Rentner, Phishing Kryptowaehrung Recovery, Phishing Mit Geschaeftskonto; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Ou... |
| `kompendium-09-phishing-praevention-bis-phishing-supply-chai` | phishing-vorfall-pruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Phishing Praeventionscheckliste, Phishing Strafanzeige Vorbereiten, Phishing Supply Chain Bec; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislog... |
| `kompendium-10-phishing-versicherer-bis-phishing-zivilklage` | phishing-vorfall-pruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Phishing Versicherer Cyber, Phishing Vorfall Pruefen, Phishing Zivilklage Bank; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuste... |
| `kompendium-11-spezial-675u-verhand-bis-spezial-banking-beho` | phishing-vorfall-pruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu 675u Verhandlung Vergleich Und Eskalation, 675w Zahlen Schwellen Und Berechnung, Banking Behoerden Gericht Und Registerweg; mit Intake, Prüfroutine, No... |
| `kompendium-12-spezial-bankpflichte-bis-spezial-bgb-schrifts` | phishing-vorfall-pruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Bankpflichten Beweislast Und Darlegungslast, Beweislast Mandantenkommunikation Entscheidungsvorlage, Bgb Schriftsatz Brief Und Memo Bausteine; mit Inta... |
| `kompendium-13-spezial-call-mehrpar-bis-spezial-freistehende` | phishing-vorfall-pruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Call Mehrparteien Konflikt Und Interessen, Faelle Abschlussprodukt Und Uebergabe, Freistehender Erstpruefung Und Mandatsziel; mit Intake, Prüfroutine,... |
| `kompendium-14-spezial-grobe-formul-bis-spezial-phishing-tat` | phishing-vorfall-pruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Grobe Formular Portal Und Einreichung, Online Risikoampel Und Gegenargumente, Phishing Tatbestand Beweis Und Belege; mit Intake, Prüfroutine, Normen-/Q... |
| `kompendium-15-spezial-pruefer-doku-bis-spezial-schlichtung` | phishing-vorfall-pruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Pruefer Dokumentenmatrix Und Lueckenliste, Pushtan Compliance Dokumentation Und Akte, Schlichtung Sonderfall Und Edge Case; mit Intake, Prüfroutine, No... |
| `kompendium-16-spezial-spoofing-int-bis-spezial-spoofing-int` | phishing-vorfall-pruefer: eigenständiger Arbeits-Skill zu Spoofing Internationaler Bezug Und Schnittstellen; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck. |
| `spezial-675v-livequellen-und-rechtsprechungscheck` | 675V: Livequellen- und Rechtsprechungscheck im Plugin phishing vorfall pruefer; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Standardprüfung. |
| `spezial-fahrlaessigkeit-red-team-und-qualitaetskontrolle` | Fahrlaessigkeit: Red-Team und Qualitätskontrolle im Plugin phishing vorfall pruefer; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Standardprüfung. |
| `workflow-anschluss-skills-router` | Anschluss-Skills Router im Plugin phishing-vorfall-pruefer: schlägt nach der ersten Prüfung die passenden Spezialskills aus demselben Plugin vor. |
| `workflow-dokumentenintake` | Dokumentenintake im Plugin phishing-vorfall-pruefer: liest Uploads, sortiert Dokumentarten, markiert Fristen und baut eine knappe Arbeitsakte. |
| `workflow-kaltstart-und-routing` | Kaltstart und Routing im Plugin phishing-vorfall-pruefer: führt vom ersten Satz oder Dokument in den passenden Arbeitsweg, erkennt Rolle, Ziel, Risiko und Anschluss-Skills. |
| `workflow-output-waehlen` | Output wählen im Plugin phishing-vorfall-pruefer: entscheidet zwischen Memo, Schriftsatz, Tabelle, Brief, Checkliste, Vermerk, Redline oder Mandantenübersetzung. |
| `workflow-rechtsquellen-livecheck` | Rechtsquellen-Livecheck im Plugin phishing-vorfall-pruefer: zwingt vor tragenden Aussagen zum aktuellen Quellencheck bei Gesetzen, Behörden, Gerichten und Formularen. |
| `workflow-unterlagen-lueckenliste` | Unterlagen- und Lückenliste im Plugin phishing-vorfall-pruefer: erstellt eine präzise Nachforderungsliste statt allgemeiner Fragebögen. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
