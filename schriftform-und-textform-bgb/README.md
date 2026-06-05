# Schriftform und Textform im BGB

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`schriftform-und-textform-bgb`) | [`schriftform-und-textform-bgb.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/schriftform-und-textform-bgb.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **Schriftform-Maklervertrag – Eheleute Haspelbeck-Türkenfeld** (`schriftform-maklervertrag-muenchen-eheleute-haspelbeck`) | [Gesamt-PDF lesen](../testakten/schriftform-maklervertrag-muenchen-eheleute-haspelbeck/gesamt-pdf/schriftform-maklervertrag-muenchen-eheleute-haspelbeck_gesamt.pdf) | [`testakte-schriftform-maklervertrag-muenchen-eheleute-haspelbeck.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-schriftform-maklervertrag-muenchen-eheleute-haspelbeck.zip) |
| **Schriftform der Wohnraumkündigung — Pferdedrescher-Riesenstein ./. Eberhart-Wolframshausen** (`schriftform-mietkuendigung-bielefeld-online-pferdedrescher`) | [Gesamt-PDF lesen](../testakten/schriftform-mietkuendigung-bielefeld-online-pferdedrescher/gesamt-pdf/schriftform-mietkuendigung-bielefeld-online-pferdedrescher_gesamt.pdf) | [`testakte-schriftform-mietkuendigung-bielefeld-online-pferdedrescher.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-schriftform-mietkuendigung-bielefeld-online-pferdedrescher.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

**Plugin-Slug:** `schriftform-und-textform-bgb`
**Version:** 3.2.1
**Autor:** Klotzkette

## Installation

1. ZIP aus dem Release herunterladen.
2. Claude Code oder Claude Desktop/Cowork öffnen.
3. **Customize Plugins** bzw. **Personal plugins** öffnen.
4. **Install from .zip** wählen und `schriftform-und-textform-bgb.zip` hochladen.
5. Mit einem konkreten Auftrag starten, zum Beispiel: `Prüfe ob unser Maklervertrag der Textform § 126b BGB genügt.`

Nicht das komplette Repository-ZIP hochladen. Das Plugin-ZIP muss im Root direkt `.claude-plugin/plugin.json` und `skills/` enthalten.

## Überblick

Umfassender Workflow-Organisator für Schriftform- und Textform-Erfordernisse im deutschen Zivilrecht. Das Plugin trennt Papierform, qES, Textform, beA/ERV, gerichtliche Zustellung und prozessuale Formfiktion und bietet kanzleitaugliche Orientierung für alle wesentlichen Formerfordernisse des BGB.

### Leitentscheidungen

- Rechtsprechung: keine Entscheidung aus Modellwissen zitieren; vor Ausgabe über offizielle oder frei zugängliche Quelle mit Gericht, Entscheidungsform, Datum, Aktenzeichen und tragender Aussage verifizieren.
- **§ 130e ZPO und § 46h ArbGG seit 17.07.2024** — Formfiktion für klar erkennbare Willenserklärungen in elektronischen vorbereitenden Schriftsätzen, auch wenn elektronische Form materiell eigentlich ausgeschlossen ist.

## Skill-Verzeichnis

### Block A — Formvorschriften-Grundlagen

| Skill | Inhalt |
|-------|--------|
| `formerfordernisse-im-bgb-ueberblick` | Systematik §§ 125-129 BGB, Nichtigkeit § 125 BGB, Heilung |
| `schriftform-paragraph-126-bgb-eigenhaendige-unterschrift` | Originalunterschrift, Namenszeichnung, Faksimile, BGH-Linie |
| `elektronische-form-paragraph-126a-bgb-qes` | qES, eIDAS, Zertifikatskette, Zugang, beA-Abgrenzung, § 130e ZPO und § 46h ArbGG |
| `textform-paragraph-126b-bgb-dauerhafter-datentraeger` | E-Mail, WhatsApp, SMS, PDF als dauerhafter Datenträger |
| `notarielle-beurkundung-und-oeffentliche-beglaubigung` | § 128, § 129 BGB, BeurkG, GmbH, Grundstück, Erbvertrag |

### Block B — Zugang der formgerechten Erklärung

| Skill | Inhalt |
|-------|--------|
| `zugang-empfangsbeduerftiger-willenserklaerung-paragraph-130-bgb` | Zugangslehre, Machtbereich, Annahmeverweigerung |
| `zugang-formgerechter-erklaerung-bgh-viii-zr-159-23` | qES-Zugang, Transfervermerk § 298 Abs. 3 ZPO, Lehrsatz |
| `kuendigung-per-schriftsatz-zustellung-formfragen` | beA, qES, § 130a ZPO, § 130e ZPO, § 46h ArbGG, Zustellung, Vollmacht und § 174 BGB |
| `mandantenwarnung-qes-per-email-whatsapp-und-zugang` | Mandantenmemo: Mail-Anhänge prüfen, IT-Hinweise |

### Block C — Spezielle Formerfordernisse

| Skill | Inhalt |
|-------|--------|
| `maklervertrag-paragraph-656a-bgb-textform-bgh-i-zr-202-25` | § 656a BGB: E-Mail, Signaturhinweis, Textform und Verifizierungspflicht |
| `wohnraummiete-kuendigung-paragraph-568-bgb` | § 568, qES-Zugang, Begründungspflicht, Praxisempfehlung |
| `gewerberaummiete-paragraph-550-bgb-langzeitform` | Langzeitform, Heilung, ordentliche Kündigung bei Verstoß |
| `buergschaft-verbraucherdarlehen-und-andere-strenge-formen` | § 766, § 492, § 311b BGB, strenge Formen |
| `arbeitsrecht-befristung-und-aufhebung-paragraph-14-tzbfg-623-bgb` | § 14 Abs. 4 TzBfG, § 623 BGB, Aufhebungsvertrag |

### Block D — Workflow-Organisator

| Skill | Inhalt |
|-------|--------|
| `form-checker-fuer-vertrag-oder-willenserklaerung` | Entscheidungsbaum, Konsequenzen, Klausel-Vorschlag |
| `klauselgenerator-formvorbehalt-und-aenderungsvorbehalt` | Schriftformklausel, doppelte Schriftformklausel, AGB-Falle |
| `prozessablauf-papier-vs-elektronisch` | Workflow-Schritte: Papier, qES-Direktversand, beA-Schriftsatz mit Formfiktion und Textform |
| `dokumentations-und-beweisarchitektur` | Zugangsnachweis, qES-Validierung, TR-RESISCAN |

### Block E — Anspruchsgrundlagen-Modul

| Skill | Inhalt |
|-------|--------|
| `anspruchsformulierungen-bei-formverstoss` | § 812 BGB, Räumungsklage, Feststellungsklage, c.i.c. |
| `verteidigungsstrategie-bei-formangriff` | Heilung, § 242 BGB, Beweislast, Treuwidrigkeit |
| `mandantenkorrespondenz-form-und-zugang-templates` | Mandantenbriefe, Checklisten, Warnmemos |

## Hinweis

Alle Skills sind kanzleitauglich formuliert und enthalten vollständige Klauseltexte, Mandantenmemos und Querverweise auf aktuelle BGH-Rechtsprechung. Das Plugin ersetzt keine individuelle Rechtsberatung.

<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 24 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `allgemein-workflow-chronologie-workflow-fristen` | Allgemein, Workflow Chronologie Und Belegmatrix, Workflow Fristen Und Risikoampel: Allgemein; Workflow Chronologie Und Belegmatrix; Workflow Fristen Und Risikoampel. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmus... |
| `anspruchsformulierungen-formverstoss-buergschaft` | Anspruchsformulierungen Bei Formverstoss, Buergschaft Verbraucherdarlehen Und Andere Strenge Formen, Dokumentations Und Beweisarchitektur: Anspruchsformulierungen Bei Formverstoss; Buergschaft Verbraucherdarlehen Und Andere Strenge Forme... |
| `arbeitsrecht-befristung-schriftform-checker-vertrag` | Arbeitsrecht Befristung Und Aufhebung Paragraph 14 Tzbfg 623 Bgb, Spezial Schriftform Fristen Form Und Zustaendigkeit, Form Checker Für Vertrag Oder Willenserklaerung: Arbeitsrecht Befristung Und Aufhebung Paragraph 14 Tzbfg 623 Bgb; Spe... |
| `elektronische-paragraph-formerfordernisse-ueberblick` | Elektronische Form Paragraph 126A Bgb Qes, Formerfordernisse Im Bgb Ueberblick, Gewerberaummiete Paragraph 550 Bgb Langzeitform: Elektronische Form Paragraph 126A Bgb Qes; Formerfordernisse Im Bgb Ueberblick; Gewerberaummiete Paragraph 5... |
| `formwahl-zugang-live-prozessablauf-mandantenentscheidung` | Spezial Formwahl Zugang Und Beweis, Spezial Live Zahlen Schwellen Und Berechnung, Spezial Prozessablauf Mandantenentscheidung: Spezial Formwahl Zugang Und Beweis; Spezial Live Zahlen Schwellen Und Berechnung; Spezial Prozessablauf Mandan... |
| `klauselgenerator-formvorbehalt-maklervertrag-paragraph-amtlicher` | Klauselgenerator Formvorbehalt Und Aenderungsvorbehalt, Maklervertrag Paragraph 656A Bgb Textform Bgh I Zr 202 25, Amtlicher Formkern Bgb Zpo Check: Klauselgenerator Formvorbehalt Und Aenderungsvorbehalt; Maklervertrag Paragraph 656A Bgb... |
| `kuendigung-per-mandantenkorrespondenz-zugang-mandantenwarnung` | Kündigung Per Schriftsatz Zustellung Formfragen, Mandantenkorrespondenz Form Und Zugang Templates, Mandantenwarnung Qes Per Email Whatsapp Und Zugang: Kündigung Per Schriftsatz Zustellung Formfragen; Mandantenkorrespondenz Form Und Zugan... |
| `notarielle-beurkundung-prozessablauf-papier-paragraph` | Notarielle Beurkundung Und Oeffentliche Beglaubigung, Prozessablauf Papier Vs Elektronisch, Schriftform Paragraph 126 Bgb Eigenhaendige Unterschrift: Notarielle Beurkundung Und Oeffentliche Beglaubigung; Prozessablauf Papier Vs Elektroni... |
| `prozessordnungen-textform-verifikation` | Spezial Prozessordnungen Behörden Gericht Und Registerweg, Spezial Textform Dokumentenmatrix Und Lueckenliste, Spezial Verifikation Compliance Dokumentation Und Akte: Spezial Prozessordnungen Behörden Gericht Und Registerweg; Spezial Tex... |
| `sftf-arbeitsvertraege-nachweisgesetz-doppelschriftform-aufhebung` | Sftf Arbeitsvertraege Nachweisgesetz Spezial, Sftf Doppelschriftform Aufhebung Spezial, Sftf Elektronische Signatur Leitfaden: Sftf Arbeitsvertraege Nachweisgesetz Spezial; Sftf Doppelschriftform Aufhebung Spezial; Sftf Elektronische Sig... |
| `sftf-formvorgaben-bgb-interessen-checklisten` | Sftf Formvorgaben Bauleiter, Spezial Bgb Mehrparteien Konflikt Und Interessen, Spezial Checklisten Schriftsatz Brief Und Memo Bausteine: Sftf Formvorgaben Bauleiter; Spezial Bgb Mehrparteien Konflikt Und Interessen; Spezial Checklisten S... |
| `spezial-dokumentation-empfangsbeduerftiger-international` | Spezial Dokumentation Verhandlung Vergleich Und Eskalation, Spezial Empfangsbeduerftiger International Schnittstellen, Spezial Formerfordernisse Erstpruefung Und Mandatsziel: Spezial Dokumentation Verhandlung Vergleich Und Eskalation; Sp... |
| `spezial-paragraph-red-team-und-qualitaetskontrolle` | Paragraph: Red-Team und Qualitätskontrolle im Plugin schriftform und textform bgb; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Standardprüfung. |
| `spezial-rechtsprechung-livequellen-und-rechtsprechungscheck` | Rechtsprechung: Livequellen- und Rechtsprechungscheck im Plugin schriftform und textform bgb; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Standardprüfung. |
| `textform-paragraph-verteidigungsstrategie-formangriff` | Textform Paragraph 126B Bgb Dauerhafter Datentraeger, Verteidigungsstrategie Bei Formangriff, Wohnraummiete Kündigung Paragraph 568 Bgb: Textform Paragraph 126B Bgb Dauerhafter Datentraeger; Verteidigungsstrategie Bei Formangriff; Wohnra... |
| `willenserklaerung-zivilrecht-zugang` | Spezial Willenserklaerung Formular Portal Und Einreichung, Spezial Zivilrecht Tatbestand Beweis Und Belege, Spezial Zugang Risikoampel Und Gegenargumente: Spezial Willenserklaerung Formular Portal Und Einreichung; Spezial Zivilrecht Tatb... |
| `workflow-anschluss-skills-router` | Anschluss-Skills Router im Plugin schriftform-und-textform-bgb: schlägt nach der ersten Prüfung die passenden Spezialskills aus demselben Plugin vor. |
| `workflow-dokumentenintake` | Dokumentenintake im Plugin schriftform-und-textform-bgb: liest Uploads, sortiert Dokumentarten, markiert Fristen und baut eine knappe Arbeitsakte. |
| `workflow-kaltstart-und-routing` | Kaltstart und Routing im Plugin schriftform-und-textform-bgb: führt vom ersten Satz oder Dokument in den passenden Arbeitsweg, erkennt Rolle, Ziel, Risiko und Anschluss-Skills. |
| `workflow-output-waehlen` | Output wählen im Plugin schriftform-und-textform-bgb: entscheidet zwischen Memo, Schriftsatz, Tabelle, Brief, Checkliste, Vermerk, Redline oder Mandantenübersetzung. |
| `workflow-rechtsquellen-livecheck` | Rechtsquellen-Livecheck im Plugin schriftform-und-textform-bgb: zwingt vor tragenden Aussagen zum aktuellen Quellencheck bei Gesetzen, Behörden, Gerichten und Formularen. |
| `workflow-redteam-befristungsabrede-qes-rechtsprechung-livecheck` | Workflow Redteam Qualitygate, Befristungsabrede Qes Rechtsprechung Stand 2026, Spezial Rechtsprechung Livecheck Formfragen: Workflow Redteam Qualitygate; Befristungsabrede Qes Rechtsprechung Stand 2026; Spezial Rechtsprechung Livecheck F... |
| `workflow-unterlagen-lueckenliste` | Unterlagen- und Lückenliste im Plugin schriftform-und-textform-bgb: erstellt eine präzise Nachforderungsliste statt allgemeiner Fragebögen. |
| `zugang-empfangsbeduerftiger-zugang-formgerechter` | Zugang Empfangsbeduerftiger Willenserklaerung Paragraph 130 Bgb, Zugang Formgerechter Erklaerung Bgh Viii Zr 159 23: Zugang Empfangsbeduerftiger Willenserklaerung Paragraph 130 Bgb; Zugang Formgerechter Erklaerung Bgh Viii Zr 159 23. Füh... |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
