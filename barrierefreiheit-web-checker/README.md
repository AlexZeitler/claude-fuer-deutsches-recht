# Barrierefreiheit Web Checker

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`barrierefreiheit-web-checker`) | [`barrierefreiheit-web-checker.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/barrierefreiheit-web-checker.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **BFSG-Verstoß Tannenkamp Mode-Versand GmbH — Online-Shop Barrierefreiheit Osnabrück** (`bfsg-online-shop-tannenkamp-mode-versand-osnabrueck`) | [Gesamt-PDF lesen](../testakten/bfsg-online-shop-tannenkamp-mode-versand-osnabrueck/gesamt-pdf/bfsg-online-shop-tannenkamp-mode-versand-osnabrueck_gesamt.pdf) | [`testakte-bfsg-online-shop-tannenkamp-mode-versand-osnabrueck.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-bfsg-online-shop-tannenkamp-mode-versand-osnabrueck.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

Prüf- und Dokumentationsplugin für digitale Barrierefreiheit von Websites, Webshops, Portalen, Apps und eingebetteten Dokumenten. Es verbindet den rechtlichen Scope-Check mit praktischer Webprüfung: BFSG/BFSGV, BITV 2.0, Web Accessibility Directive, European Accessibility Act, EN 301 549, WCAG, Tastaturbedienung, Screenreader, Formulare, Checkout, PDFs, Barrierefreiheitserklärung und Remediation-Roadmap.

## Was das Plugin gut kann

- Ermitteln, ob eine Website öffentlich-rechtlich, BFSG-relevant, rein intern oder freiwillig zu prüfen ist.
- Einen Audit nach EN 301 549/WCAG-Prüflogik vorbereiten und dokumentieren.
- Tastatur, Fokus, Semantik, Screenreader, Kontrast, Formulare, Checkout und Downloads prüfen.
- Barrierefreiheitserklärung, Feedbackmechanismus und Maßnahmenplan formulieren.
- Agenturen, Entwicklerteams und Compliance-Verantwortliche mit klaren Abnahmekriterien führen.

## Enthaltene Skills

| Skill | Zweck |
| --- | --- |
| `allgemein` | Kaltstart, Scope, Ziel, Rolle, Prüfobjekt und Workflow-Routing. |
| `scope-bfsg-bitv-wad` | Prüft, welcher Rechtsrahmen einschlägig ist: BFSG/BFSGV, BITV 2.0, EU-WAD, freiwilliger Standard. |
| `en301549-wcag-pruefplan` | Baut einen Prüfkatalog nach EN 301 549 und WCAG mit A/AA-Prioritäten. |
| `automatisierter-audit-axe-lighthouse` | Ordnet automatisierte Checks ein und warnt vor falscher Sicherheit. |
| `tastatur-fokus-navigation` | Prüft Tastaturbedienbarkeit, Fokusreihenfolge, Skiplinks, Menüs, Modale und Overlays. |
| `screenreader-semantik-aria` | Prüft Struktur, HTML-Semantik, Labels, ARIA, Überschriften, Live-Regionen und Fehlermeldungen. |
| `kontrast-farbe-motion-responsive` | Prüft Kontrast, Farbe ohne Farbcodierung, Reflow, Zoom, Animationen und Bewegung. |
| `formulare-checkout-ecommerce` | Prüft Webshop, Login, Warenkorb, Checkout, Fehlertexte, Zahlung und elektronische Verträge. |
| `pdf-downloads-dokumente` | Prüft PDFs, Downloads, eingebettete Dokumente und Alternativen. |
| `erklaerung-feedback-durchsetzung` | Erstellt Barrierefreiheitserklärung, Feedbackweg und Behörden-/Marktüberwachungsreaktion. |
| `remediation-roadmap-dokumentation` | Baut Maßnahmenplan, Priorisierung, Nachweise, Risikoampel und Re-Test-Protokoll. |
| `agentur-abnahme-vergabe` | Formuliert Lastenheft, Abnahmekriterien und Nachbesserungsanforderungen an Agenturen. |

## Quellenstand

Stand: Mai 2026. Rechtsprechung und Behördenpraxis werden nicht aus Modellwissen zitiert. Technische Standards ändern sich; insbesondere ist zwischen fachlich sinnvoller WCAG-2.2-Prüfung und rechtlich harmonisierten EN-301-549-Anforderungen zu unterscheiden.

## Lizenz

Apache-2.0 OR MIT — Auswahl beim Empfänger.


<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 24 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `allgemein-workflow-chronologie-workflow-fristen` | Allgemein, Workflow Chronologie Und Belegmatrix, Workflow Fristen Und Risikoampel: Allgemein; Workflow Chronologie Und Belegmatrix; Workflow Fristen Und Risikoampel. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmus... |
| `audit-barrierefreiheits-bfsg` | Spezial Audit Schriftsatz Brief Und Memo Bausteine, Spezial Barrierefreiheits Erstpruefung Und Mandatsziel, Spezial Bfsg Tatbestand Beweis Und Belege: Spezial Audit Schriftsatz Brief Und Memo Bausteine; Spezial Barrierefreiheits Erstprue... |
| `bf-kiosk-bf-mediendienste-bf-pdf` | Bf Kiosk Und Selbstbedienung Spezial, Bf Mediendienste Untertitel Spezial, Bf Pdf Schriftsaetze Versand: Bf Kiosk Und Selbstbedienung Spezial; Bf Mediendienste Untertitel Spezial; Bf Pdf Schriftsaetze Versand. Führt Intake, Prüfroutine,... |
| `bfsg-zeitleiste-ecommerce-checkout-en301549-wcag` | Bfsg Zeitleiste Und Pflichten, Ecommerce Checkout Prüfung Spezial, En301549 Wcag Pruefplan: Bfsg Zeitleiste Und Pflichten; Ecommerce Checkout Prüfung Spezial; En301549 Wcag Pruefplan. Führt Intake, Prüfroutine, Normen-/Quellenradar, Bewe... |
| `bfsgv-schulung-fristennotiz-agentur-abnahme` | Spezial Bfsgv Fristen Form Und Zustaendigkeit, Spezial Schulung Fristennotiz Und Naechster Schritt, Agentur Abnahme Vergabe: Spezial Bfsgv Fristen Form Und Zustaendigkeit; Spezial Schulung Fristennotiz Und Naechster Schritt; Agentur Abna... |
| `bitv-checkout-beweislast-ecommerce` | Spezial Bitv Dokumentenmatrix Und Lueckenliste, Spezial Checkout Beweislast Und Darlegungslast, Spezial Ecommerce Mandantenkommunikation Entscheidungsvorlage: Spezial Bitv Dokumentenmatrix Und Lueckenliste; Spezial Checkout Beweislast Un... |
| `erklaerung-interessen-formulare-pdfs` | Spezial Erklaerung Mehrparteien Konflikt Und Interessen, Spezial Formulare Zahlen Schwellen Und Berechnung, Spezial Pdfs Compliance Dokumentation Und Akte: Spezial Erklaerung Mehrparteien Konflikt Und Interessen; Spezial Formulare Zahlen... |
| `formulare-checkout-kontrast-farbe-native-apps` | Formulare Checkout Ecommerce, Kontrast Farbe Motion Responsive, Native Apps Ios Android Prüfung: Formulare Checkout Ecommerce; Kontrast Farbe Motion Responsive; Native Apps Ios Android Prüfung. Führt Intake, Prüfroutine, Normen-/Quellenr... |
| `pdf-downloads-remediation-roadmap-schulung-rolle` | Pdf Downloads Dokumente, Remediation Roadmap Dokumentation, Schulung Und Rolle Accessibility Champion: Pdf Downloads Dokumente; Remediation Roadmap Dokumentation; Schulung Und Rolle Accessibility Champion. Führt Intake, Prüfroutine, Norm... |
| `pdf-formulare-automatisierter-audit-bf-kanzleiwebsite` | Pdf Formulare Und Formulare Barrierefrei, Automatisierter Audit Axe Lighthouse, Bf Kanzleiwebsite Konkret: Pdf Formulare Und Formulare Barrierefrei; Automatisierter Audit Axe Lighthouse; Bf Kanzleiwebsite Konkret. Führt Intake, Prüfrouti... |
| `scope-bfsg-screenreader-semantik-abnahme` | Scope Bfsg Bitv Wad, Screenreader Semantik Aria, Spezial Abnahme Formular Portal Und Einreichung: Scope Bfsg Bitv Wad; Screenreader Semantik Aria; Spezial Abnahme Formular Portal Und Einreichung. Führt Intake, Prüfroutine, Normen-/Quelle... |
| `scope-tastatur-wcag` | Spezial Scope Behörden Gericht Und Registerweg, Spezial Tastatur Verhandlung Vergleich Und Eskalation, Spezial Wcag Risikoampel Und Gegenargumente: Spezial Scope Behörden Gericht Und Registerweg; Spezial Tastatur Verhandlung Vergleich Un... |
| `sonderfall-edge-roadmap-rolle` | Spezial Prüfung Sonderfall Und Edge Case, Spezial Roadmap Internationaler Bezug Und Schnittstellen, Spezial Rolle Abschlussprodukt Und Übergabe: Spezial Prüfung Sonderfall Und Edge Case; Spezial Roadmap Internationaler Bezug Und Schnitts... |
| `spezial-barrierefreiheit-red-team-und-qualitaetskontrolle` | Barrierefreiheit: Red-Team und Qualitätskontrolle im Plugin barrierefreiheit web checker; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Standardprüfung. |
| `spezial-screenreader-livequellen-und-rechtsprechungscheck` | Screenreader: Livequellen- und Rechtsprechungscheck im Plugin barrierefreiheit web checker; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Standardprüfung. |
| `tastatur-fokus-ueberwachungsstelle-rechtsfolgen-usability-test` | Tastatur Fokus Navigation, Ueberwachungsstelle Und Rechtsfolgen, Usability Test Mit Betroffenen: Tastatur Fokus Navigation; Ueberwachungsstelle Und Rechtsfolgen; Usability Test Mit Betroffenen. Führt Intake, Prüfroutine, Normen-/Quellenr... |
| `wcag-vs` | Wcag Vs En 301 549 Mapping: Wcag Vs En 301 549 Mapping. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zusammen. |
| `workflow-anschluss-skills-router` | Anschluss-Skills Router im Plugin barrierefreiheit-web-checker: schlägt nach der ersten Prüfung die passenden Spezialskills aus demselben Plugin vor. |
| `workflow-dokumentenintake` | Dokumentenintake im Plugin barrierefreiheit-web-checker: liest Uploads, sortiert Dokumentarten, markiert Fristen und baut eine knappe Arbeitsakte. |
| `workflow-kaltstart-und-routing` | Kaltstart und Routing im Plugin barrierefreiheit-web-checker: führt vom ersten Satz oder Dokument in den passenden Arbeitsweg, erkennt Rolle, Ziel, Risiko und Anschluss-Skills. |
| `workflow-mandantenkommunikation-redteam-qualitygate-erklaerung` | Workflow Mandantenkommunikation, Workflow Redteam Qualitygate, Erklaerung Feedback Durchsetzung: Workflow Mandantenkommunikation; Workflow Redteam Qualitygate; Erklaerung Feedback Durchsetzung. Führt Intake, Prüfroutine, Normen-/Quellenr... |
| `workflow-output-waehlen` | Output wählen im Plugin barrierefreiheit-web-checker: entscheidet zwischen Memo, Schriftsatz, Tabelle, Brief, Checkliste, Vermerk, Redline oder Mandantenübersetzung. |
| `workflow-rechtsquellen-livecheck` | Rechtsquellen-Livecheck im Plugin barrierefreiheit-web-checker: zwingt vor tragenden Aussagen zum aktuellen Quellencheck bei Gesetzen, Behörden, Gerichten und Formularen. |
| `workflow-unterlagen-lueckenliste` | Unterlagen- und Lückenliste im Plugin barrierefreiheit-web-checker: erstellt eine präzise Nachforderungsliste statt allgemeiner Fragebögen. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
