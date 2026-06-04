# BAV Strategie Konzern — Treuenfels Yamamoto Rechtsanwälte Partnerschaft mbB

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`bav-strategie-konzern`) | [`bav-strategie-konzern.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/bav-strategie-konzern.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **Betriebliche Altersversorgung – MEISSNER RHEINWERK AG** (`bav-strategie-konzern-meissner-rheinwerk-ag`) | [Gesamt-PDF lesen](../testakten/bav-strategie-konzern-meissner-rheinwerk-ag/gesamt-pdf/bav-strategie-konzern-meissner-rheinwerk-ag_gesamt.pdf) | [`testakte-bav-strategie-konzern-meissner-rheinwerk-ag.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-bav-strategie-konzern-meissner-rheinwerk-ag.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

Dieses Plugin stellt 21 spezialisierte Skills für die strategische Beratung zur betrieblichen Altersversorgung (BAV) in Konzernen bereit. Es spiegelt den Beratungsansatz der Boutique-Großkanzlei **Treuenfels Yamamoto Rechtsanwälte Partnerschaft mbB**, Königsallee 92, 40212 Düsseldorf (Zweigbüro: Gion-Higashi, Shijō-dōri, Kyoto).

**Namens-Partner:**
- Dr. Dr. Hartwig Treuenfels-Ostermann, LL.M. (Cambridge), Of Counsel, Honorarprofessor Düsseldorf für Arbeits- und Vergütungsrecht
- Yuki Yamamoto-Brennecke, bengoshi + Rechtsanwältin (Tokyo Bar), Leiterin Kyoto-Büro

**Federführender Partner BAV/Versorgung:**
Prof. Dr. Adalbert von Sompeh-Ostermann, LL.M. (Oxford), Versorgungs- und Transaktionsspezialist

---

## Installation

1. ZIP aus dem Release herunterladen.
2. Claude Code oder Claude Desktop/Cowork öffnen.
3. **Customize Plugins** bzw. **Personal plugins** öffnen.
4. **Install from .zip** wählen und `bav-strategie-konzern.zip` hochladen.
5. Mit einem konkreten Auftrag starten, zum Beispiel: `Prüfe unsere Konzern-Versorgungsordnung und schlage eine Harmonisierungsstrategie vor.`

Nicht das komplette Repository-ZIP hochladen. Das Plugin-ZIP muss im Root direkt `.claude-plugin/plugin.json` und `skills/` enthalten.

## Block A — Pensionsmodelle & Versorgungsarchitektur

| # | Skill-Name | Kurzbeschreibung |
|---|-----------|-----------------|
| 1 | `pensionsmodelle-fuenf-durchfuehrungswege` | Direktzusage vs. Unterstützungskasse vs. Pensionskasse vs. Pensionsfonds vs. Direktversicherung; Entscheidungsmatrix, Bilanz- und Risiko-Tradeoffs, IFRS/HGB |
| 2 | `versorgungsordnung-und-betriebsvereinbarung-drafting` | Volltext-Templates Versorgungsordnung und Betriebsvereinbarung (Düsseldorfer Schule), Anpassungsklauseln § 16 BetrAVG, Spätehenklauseln, Hinterbliebenenversorgung |
| 3 | `governance-und-anpassungsmechanismen` | Pension Committee Charter, Trustee-Boards, Anpassungsentscheidungen § 16 BetrAVG, sachlich-billige Ermessensausübung |
| Rechtsprechung live prüfen | Live-Verifikation erforderlich | keine Entscheidung aus Modellwissen; Quelle vor Ausgabe protokollieren |
| 5 | `internationale-harmonisierung-konzern-bav` | Konzernweite Plan-Inventory, Country-by-Country Matrix DE/UK/USA/FR/SG/JP, Global Benefits Policy, Local-vs-Group Governance |

## Block B — Pension Buyouts

| # | Skill-Name | Kurzbeschreibung |
|---|-----------|-----------------|
| 6 | `pension-buyout-strukturierung-und-de-risking` | Buy-in vs. Buy-out vs. Longevity Swap, Versichererauswahl, Term Sheets, BaFin-Genehmigung |
| Rechtsprechung live prüfen | Live-Verifikation erforderlich | keine Entscheidung aus Modellwissen; Quelle vor Ausgabe protokollieren |
| Rechtsprechung live prüfen | Live-Verifikation erforderlich | keine Entscheidung aus Modellwissen; Quelle vor Ausgabe protokollieren |
| 9 | `buyout-im-ma-deal-asset-vs-share` | Pension Liabilities in Carve-outs, § 613a BGB, ABC-Klauseln, Garantien/Indemnities, W&I-Versicherung |
| 10 | `internationale-buyout-datenflows-und-datenschutz` | Art. 9 DSGVO, Drittlandtransfer Art. 46 SCC, APPI/PIPC Japan, Schrems II Workaround |

## Block C — Komplexe Versorgungssysteme

| # | Skill-Name | Kurzbeschreibung |
|---|-----------|-----------------|
| 11 | `historisch-gewachsene-altsysteme-due-diligence` | Inventory-Methodik, Altzusagen 1970er/1980er, Versorgungstarifverträge, Sonderzusagen Führungskräfte, Risk Map |
| Rechtsprechung live prüfen | Live-Verifikation erforderlich | keine Entscheidung aus Modellwissen; Quelle vor Ausgabe protokollieren |
| 13 | `mitbestimmung-betriebsrat-einigungsstelle-bav` | § 87 Abs. 1 Nr. 8/10 BetrVG, Initiativrecht, Einigungsstellenverfahren, Spruch-Templates |
| 14 | `kollektivrechtliche-loesungen-und-sozialplan` | § 112 BetrVG, pensionsspezifische Sozialplanbestandteile, Abfindungsmodelle vs. Versorgungserhalt |

## Block D — Internationale Benefits-Strukturen

| # | Skill-Name | Kurzbeschreibung |
|---|-----------|-----------------|
| 15 | `country-by-country-benefits-matrix-konzern` | Standardisierte Tabelle DE/UK/US/FR/SG/JP/NL/CH, lokale zwingende Vorschriften, Expat-Behandlung |
| 16 | `expatriate-pensionsplanung-und-totalization` | Sozialversicherungsabkommen, A1-Bescheinigung, Doppelbesteuerungsabkommen, Stranded Pensions |
| 17 | `japan-bav-und-corporate-pension-iorp` | Kakutei-kyuufu kigyou nenkin, Tax-Qualified Pension Plan Sunset, japanische DC-Pläne, Düsseldorf-Kyoto-Kollaboration |
| 18 | `post-merger-bav-integration-global` | HR-Transformation, Global-Mobility-Bezug, Reward-Harmonisierung, Day-1/Day-100/Day-365-Plan |

## Block E — Restrukturierungen & Kanzlei-Werkzeuge

| # | Skill-Name | Kurzbeschreibung |
|---|-----------|-----------------|
| 19 | `db-zu-dc-umstellung-mit-besitzstand` | DB-Schließung mit Past-Service-Schutz und Future-Service-DC, BAG-konforme Umstellung |
| 20 | `anpassungspruefung-paragraph-16-betravg` | Drei-Jahres-Rhythmus, wirtschaftliche Lage des Arbeitgebers, Reallohn-Bezugsgrößen-Verfahren |
| 21 | `mandantenkorrespondenz-bav-grosskanzlei-stil` | Briefkopf-Templates Treuenfels Yamamoto (deutsch/japanisch/englisch), Engagement Letter mit Stundensätzen, KYC |

---

*Alle Mandantennamen und Beratungsbeispiele in den Skills sind fiktiv. Die zitierten Gerichtsentscheidungen und Gesetze sind reale Quellen.*

<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 24 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `kompendium-01-allgemein-bis-workflow-chronologie` | bav-strategie-konzern: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Allgemein, Bav Konzern Design Workflow, Chronologie Und Belegmatrix; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualität... |
| `kompendium-02-workflow-fristen-und-bis-workflow-redteam-qua` | bav-strategie-konzern: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Fristen Und Risikoampel, Mandantenkommunikation, Redteam Qualitygate; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitä... |
| `kompendium-03-spezial-altersversor-bis-psv-pensionssicherun` | bav-strategie-konzern: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Altersversorgung Fristen Form Und Zustaendigkeit, Boutique Fristennotiz Und Naechster Schritt, Psv Pensionssicherungsverein Und Haftungsketten; mit Intake... |
| `kompendium-04-bav-einfuehrung-durc-bis-bav-grenzueberschrei` | bav-strategie-konzern: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Bav Einfuehrung Durchfuehrungswege, Bav Erstattung Fuenftelregelung, Bav Grenzueberschreitend Mobil Spezial; mit Intake, Prüfroutine, Normen-/Quellenradar... |
| `kompendium-05-pensionsmodelle-fuen-bis-bav-pensionsfond-rue` | bav-strategie-konzern: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Pensionsmodelle Fuenf Durchfuehrungswege, Bav Cta Treuhand Spezial, Bav Pensionsfond Rueckdeckung Spezial; mit Intake, Prüfroutine, Normen-/Quellenradar,... |
| `kompendium-06-buyout-im-ma-deal-as-bis-cta-contractual-trus` | bav-strategie-konzern: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Buyout Im Ma Deal Asset Vs Share, Country By Country Benefits Matrix Konzern, Cta Contractual Trust Arrangement Strukturierung; mit Intake, Prüfroutine, N... |
| `kompendium-07-drei-stufen-theorie-bis-governance-und-anpas` | bav-strategie-konzern: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Drei Stufen Theorie Eingriffsanalyse, Expatriate Pensionsplanung Und Totalization, Governance Und Anpassungsmechanismen; mit Intake, Prüfroutine, Normen-/... |
| `kompendium-08-harmonisierung-und-m-bis-internationale-buyou` | bav-strategie-konzern: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Harmonisierung Und Migration Rechtssicher, Historisch Gewachsene Altsysteme Due Diligence, Internationale Buyout Datenflows Und Datenschutz; mit Intake, P... |
| `kompendium-09-internationale-harmo-bis-kollektivrechtliche` | bav-strategie-konzern: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Internationale Harmonisierung Konzern Bav, Japan Bav Und Corporate Pension Iorp, Kollektivrechtliche Loesungen Und Sozialplan; mit Intake, Prüfroutine, No... |
| `kompendium-10-mitbestimmung-betrie-bis-spezial-benefits-man` | bav-strategie-konzern: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Mitbestimmung Betriebsrat Einigungsstelle Bav, Pension Buyout Strukturierung Und De Risking, Benefits Mandantenkommunikation Entscheidungsvorlage; mit Int... |
| `kompendium-11-spezial-betriebliche-bis-spezial-duesseldorfe` | bav-strategie-konzern: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Betrieblichen Tatbestand Beweis Und Belege, Drei Zahlen Schwellen Und Berechnung, Duesseldorfer Sonderfall Und Edge Case; mit Intake, Prüfroutine, Normen-... |
| `kompendium-12-spezial-durchfuehrun-bis-spezial-harmonisieru` | bav-strategie-konzern: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Durchfuehrungswege Schriftsatz Brief Und Memo Bausteine, Fuenf Behoerden Gericht Und Registerweg, Harmonisierung Formular Portal Und Einreichung; mit Inta... |
| `kompendium-13-spezial-konzernen-do-bis-spezial-pensionsmode` | bav-strategie-konzern: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Konzernen Dokumentenmatrix Und Lueckenliste, Pension Verhandlung Vergleich Und Eskalation, Pensionsmodelle Risikoampel Und Gegenargumente; mit Intake, Prü... |
| `kompendium-14-spezial-restrukturie-bis-spezial-strategische` | bav-strategie-konzern: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Restrukturierung Beweislast Und Darlegungslast, Stil Abschlussprodukt Und Uebergabe, Strategische Erstpruefung Und Mandatsziel; mit Intake, Prüfroutine, N... |
| `kompendium-15-spezial-stufen-compl-bis-spezial-versorgungss` | bav-strategie-konzern: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Stufen Compliance Dokumentation Und Akte, Theorie Mehrparteien Konflikt Und Interessen, Versorgungssystem International Schnittstellen; mit Intake, Prüfro... |
| `kompendium-16-versorgungsordnung-u-bis-versorgungsordnung-u` | bav-strategie-konzern: eigenständiger Arbeits-Skill zu Versorgungsordnung Und Betriebsvereinbarung Drafting; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck. |
| `spezial-buyouts-livequellen-und-rechtsprechungscheck` | Buyouts: Livequellen- und Rechtsprechungscheck im Plugin bav strategie konzern; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Standardprüfung. |
| `spezial-internationale-red-team-und-qualitaetskontrolle` | Internationale: Red-Team und Qualitätskontrolle im Plugin bav strategie konzern; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Standardprüfung. |
| `workflow-anschluss-skills-router` | Anschluss-Skills Router im Plugin bav-strategie-konzern: schlägt nach der ersten Prüfung die passenden Spezialskills aus demselben Plugin vor. |
| `workflow-dokumentenintake` | Dokumentenintake im Plugin bav-strategie-konzern: liest Uploads, sortiert Dokumentarten, markiert Fristen und baut eine knappe Arbeitsakte. |
| `workflow-kaltstart-und-routing` | Kaltstart und Routing im Plugin bav-strategie-konzern: führt vom ersten Satz oder Dokument in den passenden Arbeitsweg, erkennt Rolle, Ziel, Risiko und Anschluss-Skills. |
| `workflow-output-waehlen` | Output wählen im Plugin bav-strategie-konzern: entscheidet zwischen Memo, Schriftsatz, Tabelle, Brief, Checkliste, Vermerk, Redline oder Mandantenübersetzung. |
| `workflow-rechtsquellen-livecheck` | Rechtsquellen-Livecheck im Plugin bav-strategie-konzern: zwingt vor tragenden Aussagen zum aktuellen Quellencheck bei Gesetzen, Behörden, Gerichten und Formularen. |
| `workflow-unterlagen-lueckenliste` | Unterlagen- und Lückenliste im Plugin bav-strategie-konzern: erstellt eine präzise Nachforderungsliste statt allgemeiner Fragebögen. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
