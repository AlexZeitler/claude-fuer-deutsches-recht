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
| `675u-675w-banking` | Spezial 675U Verhandlung Vergleich Und Eskalation, Spezial 675W Zahlen Schwellen Und Berechnung, Spezial Banking Behörden Gericht Und Registerweg: Spezial 675U Verhandlung Vergleich Und Eskalation; Spezial 675W Zahlen Schwellen Und Berec... |
| `allgemein-workflow-chronologie-workflow-fristen` | Allgemein, Workflow Chronologie Und Belegmatrix, Workflow Fristen Und Risikoampel: Allgemein; Workflow Chronologie Und Belegmatrix; Workflow Fristen Und Risikoampel. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmus... |
| `arbeitnehmer-haftung-bgb-675u-phish-ceo` | Phishing Arbeitnehmer Haftung, Phishing Bgb 675U Haftung, Phish Ceo Fraud Konzern Spezial: Phishing Arbeitnehmer Haftung; Phishing Bgb 675U Haftung; Phish Ceo Fraud Konzern Spezial. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweis... |
| `aufsicht-bafin-bank-strategie-banking-app` | Phishing Aufsicht Bafin, Phishing Bank Strategie, Phishing Banking App Malware: Phishing Aufsicht Bafin; Phishing Bank Strategie; Phishing Banking App Malware. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster un... |
| `bankpflichten-beweislast-beweislast-bgb` | Spezial Bankpflichten Beweislast Und Darlegungslast, Spezial Beweislast Mandantenkommunikation Entscheidungsvorlage, Spezial Bgb Schriftsatz Brief Und Memo Bausteine: Spezial Bankpflichten Beweislast Und Darlegungslast; Spezial Beweislas... |
| `bea-notfall-bgb-675v-erstkontakt-mandant` | Phishing Bea Notfall Anwalt, Phishing Bgb 675V Grobfahrlaessig, Phishing Erstkontakt Mandant: Phishing Bea Notfall Anwalt; Phishing Bgb 675V Grobfahrlaessig; Phishing Erstkontakt Mandant. Führt Intake, Prüfroutine, Normen-/Quellenradar,... |
| `call-interessen-faelle-freistehender` | Spezial Call Mehrparteien Konflikt Und Interessen, Spezial Faelle Abschlussprodukt Und Übergabe, Spezial Freistehender Erstpruefung Und Mandatsziel: Spezial Call Mehrparteien Konflikt Und Interessen; Spezial Faelle Abschlussprodukt Und Ü... |
| `grobe-online-phishing` | Spezial Grobe Formular Portal Und Einreichung, Spezial Online Risikoampel Und Gegenargumente, Spezial Phishing Tatbestand Beweis Und Belege: Spezial Grobe Formular Portal Und Einreichung; Spezial Online Risikoampel Und Gegenargumente; Sp... |
| `klage-fristennotiz-vorfall-phish-banking` | Spezial Klage Fristennotiz Und Naechster Schritt, Spezial Vorfall Fristen Form Und Zustaendigkeit, Phish Banking Trojaner Haftung Spezial: Spezial Klage Fristennotiz Und Naechster Schritt; Spezial Vorfall Fristen Form Und Zustaendigkeit;... |
| `phish-incident-phish-meldepflichten-arten-erkennen` | Phish Incident Triage Bauleiter, Phish Meldepflichten Leitfaden, Phishing Arten Erkennen: Phish Incident Triage Bauleiter; Phish Meldepflichten Leitfaden; Phishing Arten Erkennen. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislo... |
| `phishing-faelle-rentner-kryptowaehrung-recovery-geschaeftskonto` | Phishing Faelle Rentner, Phishing Kryptowaehrung Recovery, Phishing Mit Geschaeftskonto: Phishing Faelle Rentner; Phishing Kryptowaehrung Recovery; Phishing Mit Geschaeftskonto. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogi... |
| `phishing-praeventionscheckliste-strafanzeige-vorbereiten-supply` | Phishing Praeventionscheckliste, Phishing Strafanzeige Vorbereiten, Phishing Supply Chain Bec: Phishing Praeventionscheckliste; Phishing Strafanzeige Vorbereiten; Phishing Supply Chain Bec. Führt Intake, Prüfroutine, Normen-/Quellenradar... |
| `spezial-675v-livequellen-und-rechtsprechungscheck` | 675V: Livequellen- und Rechtsprechungscheck im Plugin phishing vorfall pruefer; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Standardprüfung. |
| `spezial-dokumentenmatrix-pushtan-schlichtung-sonderfall` | Spezial Prüfer Dokumentenmatrix Und Lueckenliste, Spezial Pushtan Compliance Dokumentation Und Akte, Spezial Schlichtung Sonderfall Und Edge Case: Spezial Prüfer Dokumentenmatrix Und Lueckenliste; Spezial Pushtan Compliance Dokumentation... |
| `spezial-fahrlaessigkeit-red-team-und-qualitaetskontrolle` | Fahrlaessigkeit: Red-Team und Qualitätskontrolle im Plugin phishing vorfall pruefer; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Standardprüfung. |
| `spoofing` | Spezial Spoofing Internationaler Bezug Und Schnittstellen: Spezial Spoofing Internationaler Bezug Und Schnittstellen. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zusammen. |
| `versicherer-cyber-phishing-vorfall-zivilklage-bank` | Phishing Versicherer Cyber, Phishing Vorfall Prüfen, Phishing Zivilklage Bank: Phishing Versicherer Cyber; Phishing Vorfall Prüfen; Phishing Zivilklage Bank. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und... |
| `workflow-anschluss-skills-router` | Anschluss-Skills Router im Plugin phishing-vorfall-pruefer: schlägt nach der ersten Prüfung die passenden Spezialskills aus demselben Plugin vor. |
| `workflow-dokumentenintake` | Dokumentenintake im Plugin phishing-vorfall-pruefer: liest Uploads, sortiert Dokumentarten, markiert Fristen und baut eine knappe Arbeitsakte. |
| `workflow-kaltstart-und-routing` | Kaltstart und Routing im Plugin phishing-vorfall-pruefer: führt vom ersten Satz oder Dokument in den passenden Arbeitsweg, erkennt Rolle, Ziel, Risiko und Anschluss-Skills. |
| `workflow-mandantenkommunikation-redteam-qualitygate-phishing-tan` | Workflow Mandantenkommunikation, Workflow Redteam Qualitygate, Phishing Tan Verfahren Vergleich: Workflow Mandantenkommunikation; Workflow Redteam Qualitygate; Phishing Tan Verfahren Vergleich. Führt Intake, Prüfroutine, Normen-/Quellenr... |
| `workflow-output-waehlen` | Output wählen im Plugin phishing-vorfall-pruefer: entscheidet zwischen Memo, Schriftsatz, Tabelle, Brief, Checkliste, Vermerk, Redline oder Mandantenübersetzung. |
| `workflow-rechtsquellen-livecheck` | Rechtsquellen-Livecheck im Plugin phishing-vorfall-pruefer: zwingt vor tragenden Aussagen zum aktuellen Quellencheck bei Gesetzen, Behörden, Gerichten und Formularen. |
| `workflow-unterlagen-lueckenliste` | Unterlagen- und Lückenliste im Plugin phishing-vorfall-pruefer: erstellt eine präzise Nachforderungsliste statt allgemeiner Fragebögen. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
