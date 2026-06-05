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
| `allgemein-workflow-chronologie-fristen` | Nutze dies, wenn Allgemein, Workflow Chronologie Und Belegmatrix, Workflow Fristen Und Risikoampel im Plugin Barrierefreiheit Web Checker konkret bearbeitet werden soll. Auslöser: Bitte Allgemein, Workflow Chronologie Und Belegmatrix, Wo... |
| `anschluss-routing` | Nutze dies, wenn Anschluss-Routing im Plugin Barrierefreiheit Web Checker konkret bearbeitet werden soll. Auslöser: Ich habe ein neues Thema im Bereich Barrierefreiheit Web Checker.; Welche Unterlagen brauchen Sie?; Welcher Spezialskill... |
| `audit-barrierefreiheits-bfsg` | Nutze dies, wenn Spezial Audit Schriftsatz Brief Und Memo Bausteine, Spezial Barrierefreiheits Erstpruefung Und Mandatsziel, Spezial Bfsg Tatbestand Beweis Und Belege im Plugin Barrierefreiheit Web Checker konkret bearbeitet werden soll.... |
| `barrierefreiheit-fehlerkatalog` | Nutze dies, wenn Barrierefreiheit Fehlerkatalog im Plugin Barrierefreiheit Web Checker konkret bearbeitet werden soll. Auslöser: Was kann hier schiefgehen?; Bitte red-team prüfen.; Welche Frist oder Beweislast übersehe ich?. |
| `bf-kiosk-bf-mediendienste-bf-pdf` | Nutze dies, wenn Bf Kiosk Und Selbstbedienung Spezial, Bf Mediendienste Untertitel Spezial, Bf Pdf Schriftsaetze Versand im Plugin Barrierefreiheit Web Checker konkret bearbeitet werden soll. Auslöser: Bitte Bf Kiosk Und Selbstbedienung... |
| `bfsg-zeitleiste-ecommerce-checkout-en301549` | Nutze dies, wenn Bfsg Zeitleiste Und Pflichten, Ecommerce Checkout Prüfung Spezial, En301549 Wcag Pruefplan im Plugin Barrierefreiheit Web Checker konkret bearbeitet werden soll. Auslöser: Bitte Bfsg Zeitleiste Und Pflichten, Ecommerce C... |
| `bfsgv-schulung-fristennotiz-agentur-abnahme` | Nutze dies, wenn Spezial Bfsgv Fristen Form Und Zustaendigkeit, Spezial Schulung Fristennotiz Und Naechster Schritt, Agentur Abnahme Vergabe im Plugin Barrierefreiheit Web Checker konkret bearbeitet werden soll. Auslöser: Bitte Spezial B... |
| `bitv-checkout-beweislast-ecommerce` | Nutze dies, wenn Spezial Bitv Dokumentenmatrix Und Lueckenliste, Spezial Checkout Beweislast Und Darlegungslast, Spezial Ecommerce Mandantenkommunikation Entscheidungsvorlage im Plugin Barrierefreiheit Web Checker konkret bearbeitet werd... |
| `dokumente-intake` | Nutze dies, wenn Dokumentenintake im Plugin Barrierefreiheit Web Checker konkret bearbeitet werden soll. Auslöser: Ich lade Unterlagen hoch.; Was fehlt noch?; Bitte Dokumente sortieren.. |
| `einstieg-routing` | Nutze dies, wenn Einstieg und Routing im Plugin Barrierefreiheit Web Checker konkret bearbeitet werden soll. Auslöser: Ich habe ein neues Thema im Bereich Barrierefreiheit Web Checker.; Welche Unterlagen brauchen Sie?; Welcher Spezialski... |
| `erklaerung` | Nutze dies, wenn Workflow Mandantenkommunikation, Workflow Redteam Qualitygate, Erklaerung Feedback Durchsetzung im Plugin Barrierefreiheit Web Checker konkret bearbeitet werden soll. Auslöser: Was kann hier schiefgehen?; Bitte red-team... |
| `erklaerung-interessen-formulare-pdfs` | Nutze dies, wenn Spezial Erklaerung Mehrparteien Konflikt Und Interessen, Spezial Formulare Zahlen Schwellen Und Berechnung, Spezial Pdfs Compliance Dokumentation Und Akte im Plugin Barrierefreiheit Web Checker konkret bearbeitet werden... |
| `formulare-checkout-kontrast-farbe-native-apps` | Nutze dies, wenn Formulare Checkout Ecommerce, Kontrast Farbe Motion Responsive, Native Apps Ios Android Prüfung im Plugin Barrierefreiheit Web Checker konkret bearbeitet werden soll. Auslöser: Bitte Formulare Checkout Ecommerce, Kontras... |
| `output-waehlen` | Nutze dies, wenn Output wählen im Plugin Barrierefreiheit Web Checker konkret bearbeitet werden soll. Auslöser: Bitte Output wählen prüfen.; Erstelle eine Arbeitsfassung zu Output wählen.; Welche Normen und Nachweise brauche ich?. |
| `pdf-downloads-remediation-roadmap-schulung` | Nutze dies, wenn Pdf Downloads Dokumente, Remediation Roadmap Dokumentation, Schulung Und Rolle Accessibility Champion im Plugin Barrierefreiheit Web Checker konkret bearbeitet werden soll. Auslöser: Bitte Pdf Downloads Dokumente, Remedi... |
| `pdf-formulare-automatisierter-audit-bf` | Nutze dies, wenn Pdf Formulare Und Formulare Barrierefrei, Automatisierter Audit Axe Lighthouse, Bf Kanzleiwebsite Konkret im Plugin Barrierefreiheit Web Checker konkret bearbeitet werden soll. Auslöser: Bitte Pdf Formulare Und Formulare... |
| `quellen-livecheck` | Nutze dies, wenn Rechtsquellen-Livecheck im Plugin Barrierefreiheit Web Checker konkret bearbeitet werden soll. Auslöser: Welche amtliche Quelle prüfe ich zuerst?; Gibt es aktuelle Rechtsprechung?; Bitte Fundstellen verifizieren.. |
| `scope-bfsg-screenreader-semantik-abnahme` | Nutze dies, wenn Scope Bfsg Bitv Wad, Screenreader Semantik Aria, Spezial Abnahme Formular Portal Und Einreichung im Plugin Barrierefreiheit Web Checker konkret bearbeitet werden soll. Auslöser: Bitte Scope Bfsg Bitv Wad, Screenreader Se... |
| `scope-tastatur-wcag` | Nutze dies, wenn Spezial Scope Behörden Gericht Und Registerweg, Spezial Tastatur Verhandlung Vergleich Und Eskalation, Spezial Wcag Risikoampel Und Gegenargumente im Plugin Barrierefreiheit Web Checker konkret bearbeitet werden soll. Au... |
| `screenreader-quellenkarte` | Nutze dies, wenn Screenreader Quellenkarte im Plugin Barrierefreiheit Web Checker konkret bearbeitet werden soll. Auslöser: Welche amtliche Quelle prüfe ich zuerst?; Gibt es aktuelle Rechtsprechung?; Bitte Fundstellen verifizieren.. |
| `sonderfall-edge-roadmap-rolle` | Nutze dies, wenn Spezial Prüfung Sonderfall Und Edge Case, Spezial Roadmap Internationaler Bezug Und Schnittstellen, Spezial Rolle Abschlussprodukt Und Übergabe im Plugin Barrierefreiheit Web Checker konkret bearbeitet werden soll. Auslö... |
| `tastatur-fokus-ueberwachungsstelle` | Nutze dies, wenn Tastatur Fokus Navigation, Ueberwachungsstelle Und Rechtsfolgen, Usability Test Mit Betroffenen im Plugin Barrierefreiheit Web Checker konkret bearbeitet werden soll. Auslöser: Bitte Tastatur Fokus Navigation, Ueberwachu... |
| `unterlagen-luecken` | Nutze dies, wenn Unterlagen und Lücken im Plugin Barrierefreiheit Web Checker konkret bearbeitet werden soll. Auslöser: Ich lade Unterlagen hoch.; Was fehlt noch?; Bitte Dokumente sortieren.. |
| `wcag-vs` | Nutze dies, wenn Wcag Vs En 301 549 Mapping im Plugin Barrierefreiheit Web Checker konkret bearbeitet werden soll. Auslöser: Bitte Wcag Vs En 301 549 Mapping prüfen.; Erstelle eine Arbeitsfassung zu Wcag Vs En 301 549 Mapping.; Welche No... |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
