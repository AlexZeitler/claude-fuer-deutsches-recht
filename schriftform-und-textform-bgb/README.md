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
| `kompendium-01-allgemein-bis-workflow-fristen-und` | schriftform-und-textform-bgb: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Allgemein, Chronologie Und Belegmatrix, Fristen Und Risikoampel; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Quali... |
| `kompendium-02-workflow-redteam-qua-bis-spezial-rechtsprechu` | schriftform-und-textform-bgb: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Redteam Qualitygate, Befristungsabrede Qes Rechtsprechung Stand 2026, Rechtsprechung Livecheck Formfragen; mit Intake, Prüfroutine, Normen-/Quellen... |
| `kompendium-03-arbeitsrecht-befrist-bis-form-checker-fuer-ve` | schriftform-und-textform-bgb: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Arbeitsrecht Befristung Und Aufhebung Paragraph 14 Tzbfg 623 Bgb, Schriftform Fristen Form Und Zustaendigkeit, Form Checker Fuer Vertrag Oder Wille... |
| `kompendium-04-klauselgenerator-for-bis-amtlicher-formkern-b` | schriftform-und-textform-bgb: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Klauselgenerator Formvorbehalt Und Aenderungsvorbehalt, Maklervertrag Paragraph 656a Bgb Textform Bgh I Zr 202 25, Amtlicher Formkern Bgb Zpo Check... |
| `kompendium-05-anspruchsformulierun-bis-dokumentations-und-b` | schriftform-und-textform-bgb: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Anspruchsformulierungen Bei Formverstoss, Buergschaft Verbraucherdarlehen Und Andere Strenge Formen, Dokumentations Und Beweisarchitektur; mit Inta... |
| `kompendium-06-elektronische-form-p-bis-gewerberaummiete-par` | schriftform-und-textform-bgb: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Elektronische Form Paragraph 126a Bgb Qes, Formerfordernisse Im Bgb Ueberblick, Gewerberaummiete Paragraph 550 Bgb Langzeitform; mit Intake, Prüfro... |
| `kompendium-07-kuendigung-per-schri-bis-mandantenwarnung-qes` | schriftform-und-textform-bgb: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Kuendigung Per Schriftsatz Zustellung Formfragen, Mandantenkorrespondenz Form Und Zugang Templates, Mandantenwarnung Qes Per Email Whatsapp Und Zug... |
| `kompendium-08-notarielle-beurkundu-bis-schriftform-paragrap` | schriftform-und-textform-bgb: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Notarielle Beurkundung Und Oeffentliche Beglaubigung, Prozessablauf Papier Vs Elektronisch, Schriftform Paragraph 126 Bgb Eigenhaendige Unterschrif... |
| `kompendium-09-sftf-arbeitsvertraeg-bis-sftf-elektronische-s` | schriftform-und-textform-bgb: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Sftf Arbeitsvertraege Nachweisgesetz Spezial, Sftf Doppelschriftform Aufhebung Spezial, Sftf Elektronische Signatur Leitfaden; mit Intake, Prüfrout... |
| `kompendium-10-sftf-formvorgaben-ba-bis-spezial-checklisten` | schriftform-und-textform-bgb: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Sftf Formvorgaben Bauleiter, Bgb Mehrparteien Konflikt Und Interessen, Checklisten Schriftsatz Brief Und Memo Bausteine; mit Intake, Prüfroutine, N... |
| `kompendium-11-spezial-dokumentatio-bis-spezial-formerforder` | schriftform-und-textform-bgb: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Dokumentation Verhandlung Vergleich Und Eskalation, Empfangsbeduerftiger International Schnittstellen, Formerfordernisse Erstpruefung Und Mandatszi... |
| `kompendium-12-spezial-formwahl-zug-bis-spezial-prozessablau` | schriftform-und-textform-bgb: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Formwahl Zugang Und Beweis, Live Zahlen Schwellen Und Berechnung, Prozessablauf Mandantenentscheidung; mit Intake, Prüfroutine, Normen-/Quellenrada... |
| `kompendium-13-spezial-prozessordnu-bis-spezial-verifikation` | schriftform-und-textform-bgb: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Prozessordnungen Behoerden Gericht Und Registerweg, Textform Dokumentenmatrix Und Lueckenliste, Verifikation Compliance Dokumentation Und Akte; mit... |
| `kompendium-14-spezial-willenserkla-bis-spezial-zugang-risik` | schriftform-und-textform-bgb: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Willenserklaerung Formular Portal Und Einreichung, Zivilrecht Tatbestand Beweis Und Belege, Zugang Risikoampel Und Gegenargumente; mit Intake, Prüf... |
| `kompendium-15-textform-paragraph-1-bis-wohnraummiete-kuendi` | schriftform-und-textform-bgb: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Textform Paragraph 126b Bgb Dauerhafter Datentraeger, Verteidigungsstrategie Bei Formangriff, Wohnraummiete Kuendigung Paragraph 568 Bgb; mit Intak... |
| `kompendium-16-zugang-empfangsbedue-bis-zugang-formgerechter` | schriftform-und-textform-bgb: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Zugang Empfangsbeduerftiger Willenserklaerung Paragraph 130 Bgb, Zugang Formgerechter Erklaerung Bgh Viii Zr 159 23; mit Intake, Prüfroutine, Norme... |
| `spezial-paragraph-red-team-und-qualitaetskontrolle` | Paragraph: Red-Team und Qualitätskontrolle im Plugin schriftform und textform bgb; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Standardprüfung. |
| `spezial-rechtsprechung-livequellen-und-rechtsprechungscheck` | Rechtsprechung: Livequellen- und Rechtsprechungscheck im Plugin schriftform und textform bgb; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Standardprüfung. |
| `workflow-anschluss-skills-router` | Anschluss-Skills Router im Plugin schriftform-und-textform-bgb: schlägt nach der ersten Prüfung die passenden Spezialskills aus demselben Plugin vor. |
| `workflow-dokumentenintake` | Dokumentenintake im Plugin schriftform-und-textform-bgb: liest Uploads, sortiert Dokumentarten, markiert Fristen und baut eine knappe Arbeitsakte. |
| `workflow-kaltstart-und-routing` | Kaltstart und Routing im Plugin schriftform-und-textform-bgb: führt vom ersten Satz oder Dokument in den passenden Arbeitsweg, erkennt Rolle, Ziel, Risiko und Anschluss-Skills. |
| `workflow-output-waehlen` | Output wählen im Plugin schriftform-und-textform-bgb: entscheidet zwischen Memo, Schriftsatz, Tabelle, Brief, Checkliste, Vermerk, Redline oder Mandantenübersetzung. |
| `workflow-rechtsquellen-livecheck` | Rechtsquellen-Livecheck im Plugin schriftform-und-textform-bgb: zwingt vor tragenden Aussagen zum aktuellen Quellencheck bei Gesetzen, Behörden, Gerichten und Formularen. |
| `workflow-unterlagen-lueckenliste` | Unterlagen- und Lückenliste im Plugin schriftform-und-textform-bgb: erstellt eine präzise Nachforderungsliste statt allgemeiner Fragebögen. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
