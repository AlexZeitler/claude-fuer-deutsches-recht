# Fachanwalt Bank Kapitalmarktrecht

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`fachanwalt-bank-kapitalmarktrecht`) | [`fachanwalt-bank-kapitalmarktrecht.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/fachanwalt-bank-kapitalmarktrecht.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **Cybertrading-Anlagebetrug Wittfeldt – Bremen** (`cybertrading-anlagebetrug-wittfeldt-bremen`) | [Gesamt-PDF lesen](../testakten/cybertrading-anlagebetrug-wittfeldt-bremen/gesamt-pdf/cybertrading-anlagebetrug-wittfeldt-bremen_gesamt.pdf) | [`testakte-cybertrading-anlagebetrug-wittfeldt-bremen.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-cybertrading-anlagebetrug-wittfeldt-bremen.zip) |
| **Projekt Nachtfalter — Private Equity Buyout, Schuldschein und NPL-Portfolio** (`private-equity-buyout-schuldschein-npl-heidelberg`) | [Gesamt-PDF lesen](../testakten/private-equity-buyout-schuldschein-npl-heidelberg/gesamt-pdf/private-equity-buyout-schuldschein-npl-heidelberg_gesamt.pdf) | [`testakte-private-equity-buyout-schuldschein-npl-heidelberg.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-private-equity-buyout-schuldschein-npl-heidelberg.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

Plugin Fachanwalt für Bank- und Kapitalmarktrecht. Orientierung KWG ZAG WpHG WpIG MiFID-II MAR Marktmissbrauch MiCAR Verbraucherkredit Vermögensanlage Beratungshaftung. Schnittstellen gesellschaftsrecht und regulatorisches-recht.

Der bankrechtliche Teil deckt nun ausdrücklich auch die klassischen Sicherungs- und Liquiditätsinstrumente ab: Bürgschaft, kaufmännische Bürgschaft, Aval, Kautionsaval, Bankgarantie, Bürgschaft auf erstes Anfordern, Akkreditiv, Standby Letter of Credit, Dokumentenstreit, Abruf, Eilrechtsschutz und Regress. Das ist der praktische Kern vieler Mandate: Die Bank sichert den Geschäftsverkehr ab, verschafft Liquidität, und im Streit entscheidet die genaue Formulierung des Sicherungsmittels.

Beginne bei solchen Mandaten mit `bankrecht-buergschaft-aval-garantie-routing`; der Skill ordnet Rolle, Dokumenttyp, Frist, Einwendung und nächsten Output.

## Installation in Claude Code

1. ZIP herunterladen (Link oben).
2. Claude Code → **Customize Plugins** → **Install from .zip** → Datei wählen.
3. Fertig. Skills sind sofort verfügbar.

> **Hinweis:** Für den ZIP-Upload muss das Archiv direkt `.claude-plugin/plugin.json`, `skills/`, `assets/` und `references/` im ZIP-Root enthalten. **Nicht** das komplette Repository-ZIP aus "Code → Download ZIP" verwenden.

## Enthaltene Skills

| Skill | Zweck |
| --- | --- |
| `fachanwalt-bank-kapitalmarktrecht-orientierung` | Orientierung im Bank- und Kapitalmarktrecht — FAO Voraussetzungen Normen typische Mandate Quellenprüfung. KWG (Kreditwesengesetz) ZAG (Zahlungsdiensteaufsichtsgesetz) WpHG (Wertpapierhandelsgesetz) WpIG (Wertpapier… |

## Lizenz

Apache-2.0 OR MIT — Auswahl beim Empfänger.


<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 26 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `kompendium-01-allgemein-bis-workflow-chronologie` | fachanwalt-bank-kapitalmarktrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Allgemein, Bk Bafin Beschwerdeverfahren Workflow, Chronologie Und Belegmatrix; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Out... |
| `kompendium-02-workflow-fristen-und-bis-workflow-redteam-qua` | fachanwalt-bank-kapitalmarktrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Fristen Und Risikoampel, Mandantenkommunikation, Redteam Qualitygate; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster... |
| `kompendium-03-spezial-fehlerhaft-f-bis-bk-emissionsprospekt` | fachanwalt-bank-kapitalmarktrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Fehlerhaft Fristennotiz Und Naechster Schritt, Kapitalmarktrecht Fristen Form Und Zustaendigkeit, Bk Emissionsprospekt Haftung Spezial; mit In... |
| `kompendium-04-spezial-beratungshaf-bis-bk-cum-ex-mandant-st` | fachanwalt-bank-kapitalmarktrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Beratungshaftung Zahlen Schwellen Und Berechnung, Haftung Beweislast Und Darlegungslast, Bk Cum Ex Mandant Strafrecht Spezial; mit Intake, Prü... |
| `kompendium-05-anlageberatungsfehle-bis-bankrecht-buergschaf` | fachanwalt-bank-kapitalmarktrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Anlageberatungsfehler Pruefen, Bankrecht Akkreditiv Standby Lc Dokumentenstreit, Bankrecht Buergschaft Auf Erste Anforderung; mit Intake, Prüf... |
| `kompendium-06-bankrecht-buergschaf-bis-bankrecht-kaufmaenni` | fachanwalt-bank-kapitalmarktrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Bankrecht Buergschaft Aval Garantie Routing, Bankrecht Garantieabruf Eilrechtsschutz, Bankrecht Kaufmaennische Buergschaft Hgb 349 350; mit In... |
| `kompendium-07-bankrecht-privatbuer-bis-bk-aufsicht-zag-dora` | fachanwalt-bank-kapitalmarktrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Bankrecht Privatbuergschaft Sittenwidrigkeit, Bankrecht Regress Nach Avalzahlung, Bk Aufsicht Zag Dora Inhkontrolle Crr Arbeitskern; mit Intak... |
| `kompendium-08-bk-bankenfehlberatun-bis-bk-mandantenrouting` | fachanwalt-bank-kapitalmarktrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Bk Bankenfehlberatung Grundzuege, Bk Einfuehrung Aufsichtsstruktur, Bk Mandantenrouting Anlegeranspruch; mit Intake, Prüfroutine, Normen-/Quel... |
| `kompendium-09-bk-mifid-suitability-bis-erstgespraech-mandat` | fachanwalt-bank-kapitalmarktrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Bk Mifid Suitability Spezial, Bk Prip Kid Fehlerhaft Spezial, Erstgespraech Mandatsannahme; mit Intake, Prüfroutine, Normen-/Quellenradar, Bew... |
| `kompendium-10-fachanwalt-bank-kapi-bis-fachanwalt-bank-kapi` | fachanwalt-bank-kapitalmarktrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Bank Kapitalmarktrecht Anlageberatung Fehlerhaft, Bank Kapitalmarktrecht Cybertrading Anlagebetrug, Bank Kapitalmarktrecht Kreditkuendigung; m... |
| `kompendium-11-fachanwalt-bank-kapi-bis-fachanwalt-bank-kapi` | fachanwalt-bank-kapitalmarktrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Bank Kapitalmarktrecht Kreditkuendigung 490 Bgb, Bank Kapitalmarktrecht Mica Stablecoin Art 16 Bafin, Bank Kapitalmarktrecht Ombudsmann Bafin... |
| `kompendium-12-fachanwalt-bank-kapi-bis-fachanwalt-bank-kapi` | fachanwalt-bank-kapitalmarktrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Bank Kapitalmarktrecht Orientierung, Bank Kapitalmarktrecht Schufa Eintrag, Bank Kapitalmarktrecht Schufa Loeschungsanspruch; mit Intake, Prüf... |
| `kompendium-13-mandat-triage-bank-k-bis-spezial-bank-tatbest` | fachanwalt-bank-kapitalmarktrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Mandat Triage Bank Kapitalmarktrecht, Schriftsatzkern Substantiierung, Bank Tatbestand Beweis Und Belege; mit Intake, Prüfroutine, Normen-/Que... |
| `kompendium-14-spezial-bankaufsicht-bis-spezial-fachanwalt-e` | fachanwalt-bank-kapitalmarktrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Bankaufsicht Erlaubnis Und Vertrieb, Emissionsprospekt Mandantenentscheidung, Fachanwalt Erstpruefung Und Mandatsziel; mit Intake, Prüfroutine... |
| `kompendium-15-spezial-gesellschaft-bis-spezial-mifid-behoer` | fachanwalt-bank-kapitalmarktrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Gesellschaftsrecht Mehrparteien Konflikt Und Interessen, Micar Schriftsatz Brief Und Memo Bausteine, Mifid Behoerden Gericht Und Registerweg;... |
| `kompendium-16-spezial-prip-sonderf-bis-spezial-schnittstell` | fachanwalt-bank-kapitalmarktrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Prip Sonderfall Und Edge Case, Regulatorisches Internationaler Bezug Und Schnittstellen, Schnittstellen Compliance Dokumentation Und Akte; mit... |
| `kompendium-17-spezial-verbraucherk-bis-spezial-wphg-dokumen` | fachanwalt-bank-kapitalmarktrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Verbraucherkredit Verhandlung Vergleich Und Eskalation, Widerrufsjoker Formular Portal Und Einreichung, Wphg Dokumentenmatrix Und Lueckenliste... |
| `kompendium-18-spezial-wpig-risikoa-bis-widerrufsjoker-immob` | fachanwalt-bank-kapitalmarktrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Wpig Risikoampel Und Gegenargumente, Vergleichsverhandlung Strategie, Widerrufsjoker Immobiliendarlehen; mit Intake, Prüfroutine, Normen-/Quel... |
| `spezial-immobiliendarlehen-red-team-und-qualitaetskontrolle` | Immobiliendarlehen: Red-Team und Qualitätskontrolle im Plugin fachanwalt bank kapitalmarktrecht; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Standardprüfung. |
| `spezial-vermoegensanlage-livequellen-und-rechtsprechungscheck` | Vermoegensanlage: Livequellen- und Rechtsprechungscheck im Plugin fachanwalt bank kapitalmarktrecht; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Standardprüfung. |
| `workflow-anschluss-skills-router` | Anschluss-Skills Router im Plugin fachanwalt-bank-kapitalmarktrecht: schlägt nach der ersten Prüfung die passenden Spezialskills aus demselben Plugin vor. |
| `workflow-dokumentenintake` | Dokumentenintake im Plugin fachanwalt-bank-kapitalmarktrecht: liest Uploads, sortiert Dokumentarten, markiert Fristen und baut eine knappe Arbeitsakte. |
| `workflow-kaltstart-und-routing` | Kaltstart und Routing im Plugin fachanwalt-bank-kapitalmarktrecht: führt vom ersten Satz oder Dokument in den passenden Arbeitsweg, erkennt Rolle, Ziel, Risiko und Anschluss-Skills. |
| `workflow-output-waehlen` | Output wählen im Plugin fachanwalt-bank-kapitalmarktrecht: entscheidet zwischen Memo, Schriftsatz, Tabelle, Brief, Checkliste, Vermerk, Redline oder Mandantenübersetzung. |
| `workflow-rechtsquellen-livecheck` | Rechtsquellen-Livecheck im Plugin fachanwalt-bank-kapitalmarktrecht: zwingt vor tragenden Aussagen zum aktuellen Quellencheck bei Gesetzen, Behörden, Gerichten und Formularen. |
| `workflow-unterlagen-lueckenliste` | Unterlagen- und Lückenliste im Plugin fachanwalt-bank-kapitalmarktrecht: erstellt eine präzise Nachforderungsliste statt allgemeiner Fragebögen. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
