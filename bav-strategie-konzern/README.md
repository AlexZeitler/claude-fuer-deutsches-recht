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
| `allgemein-design-workflow-chronologie` | Nutze dies, wenn Allgemein, Bav Konzern Design Workflow, Workflow Chronologie Und Belegmatrix im Plugin Bav Strategie Konzern konkret bearbeitet werden soll. Auslöser: Bitte Allgemein, Bav Konzern Design Workflow, Workflow Chronologie Un... |
| `altersversorgung-boutique-fristennotiz-psv` | Nutze dies, wenn Spezial Altersversorgung Fristen Form Und Zustaendigkeit, Spezial Boutique Fristennotiz Und Naechster Schritt, Psv Pensionssicherungsverein Und Haftungsketten im Plugin Bav Strategie Konzern konkret bearbeitet werden sol... |
| `anschluss-routing` | Nutze dies, wenn Anschluss-Routing im Plugin Bav Strategie Konzern konkret bearbeitet werden soll. Auslöser: Ich habe ein neues Thema im Bereich Bav Strategie Konzern.; Welche Unterlagen brauchen Sie?; Welcher Spezialskill passt?. |
| `betrieblichen-drei-duesseldorfer-sonderfall` | Nutze dies, wenn Spezial Betrieblichen Tatbestand Beweis Und Belege, Spezial Drei Zahlen Schwellen Und Berechnung, Spezial Duesseldorfer Sonderfall Und Edge Case im Plugin Bav Strategie Konzern konkret bearbeitet werden soll. Auslöser: B... |
| `buyout-ma-country-by-cta-contractual` | Nutze dies, wenn Buyout Im Ma Deal Asset Vs Share, Country By Country Benefits Matrix Konzern, Cta Contractual Trust Arrangement Strukturierung im Plugin Bav Strategie Konzern konkret bearbeitet werden soll. Auslöser: Bitte Buyout Im Ma... |
| `buyouts-quellenkarte` | Nutze dies, wenn Buyouts Quellenkarte im Plugin Bav Strategie Konzern konkret bearbeitet werden soll. Auslöser: Welche amtliche Quelle prüfe ich zuerst?; Gibt es aktuelle Rechtsprechung?; Bitte Fundstellen verifizieren.. |
| `dokumente-intake` | Nutze dies, wenn Dokumentenintake im Plugin Bav Strategie Konzern konkret bearbeitet werden soll. Auslöser: Ich lade Unterlagen hoch.; Was fehlt noch?; Bitte Dokumente sortieren.. |
| `drei-stufen-expatriate-pensionsplanung` | Nutze dies, wenn Drei Stufen Theorie Eingriffsanalyse, Expatriate Pensionsplanung Und Totalization, Governance Und Anpassungsmechanismen im Plugin Bav Strategie Konzern konkret bearbeitet werden soll. Auslöser: Bitte Drei Stufen Theorie... |
| `durchfuehrungswege-fuenf-harmonisierung` | Nutze dies, wenn Spezial Durchfuehrungswege Schriftsatz Brief Und Memo Bausteine, Spezial Fuenf Behörden Gericht Und Registerweg, Spezial Harmonisierung Formular Portal Und Einreichung im Plugin Bav Strategie Konzern konkret bearbeitet w... |
| `einfuehrung-durchfuehrungswege-erstattung` | Nutze dies, wenn Bav Einfuehrung Durchfuehrungswege, Bav Erstattung Fuenftelregelung, Bav Grenzueberschreitend Mobil Spezial im Plugin Bav Strategie Konzern konkret bearbeitet werden soll. Auslöser: Bitte Bav Einfuehrung Durchfuehrungswe... |
| `einstieg-routing` | Nutze dies, wenn Einstieg und Routing im Plugin Bav Strategie Konzern konkret bearbeitet werden soll. Auslöser: Ich habe ein neues Thema im Bereich Bav Strategie Konzern.; Welche Unterlagen brauchen Sie?; Welcher Spezialskill passt?. |
| `fristen-risikoampel-mandantenkommunikation` | Nutze dies, wenn Workflow Fristen Und Risikoampel, Workflow Mandantenkommunikation, Workflow Redteam Qualitygate im Plugin Bav Strategie Konzern konkret bearbeitet werden soll. Auslöser: Was kann hier schiefgehen?; Bitte red-team prüfen.... |
| `harmonisierung-migration-historisch` | Nutze dies, wenn Harmonisierung Und Migration Rechtssicher, Historisch Gewachsene Altsysteme Due Diligence, Internationale Buyout Datenflows Und Datenschutz im Plugin Bav Strategie Konzern konkret bearbeitet werden soll. Auslöser: Bitte... |
| `internationale-fehlerkatalog` | Nutze dies, wenn Internationale Fehlerkatalog im Plugin Bav Strategie Konzern konkret bearbeitet werden soll. Auslöser: Was kann hier schiefgehen?; Bitte red-team prüfen.; Welche Frist oder Beweislast übersehe ich?. |
| `internationale-harmonisierung-japan-corporate` | Nutze dies, wenn Internationale Harmonisierung Konzern Bav, Japan Bav Und Corporate Pension Iorp, Kollektivrechtliche Loesungen Und Sozialplan im Plugin Bav Strategie Konzern konkret bearbeitet werden soll. Auslöser: Bitte Internationale... |
| `konzernen-pension-pensionsmodelle` | Nutze dies, wenn Spezial Konzernen Dokumentenmatrix Und Lueckenliste, Spezial Pension Verhandlung Vergleich Und Eskalation, Spezial Pensionsmodelle Risikoampel Und Gegenargumente im Plugin Bav Strategie Konzern konkret bearbeitet werden... |
| `mitbestimmung-betriebsrat-pension-buyout` | Nutze dies, wenn Mitbestimmung Betriebsrat Einigungsstelle Bav, Pension Buyout Strukturierung Und De Risking, Spezial Benefits Mandantenkommunikation Entscheidungsvorlage im Plugin Bav Strategie Konzern konkret bearbeitet werden soll. Au... |
| `output-waehlen` | Nutze dies, wenn Output wählen im Plugin Bav Strategie Konzern konkret bearbeitet werden soll. Auslöser: Bitte Output wählen prüfen.; Erstelle eine Arbeitsfassung zu Output wählen.; Welche Normen und Nachweise brauche ich?. |
| `pensionsmodelle-fuenf-bav-cta-pensionsfond` | Nutze dies, wenn Pensionsmodelle Fuenf Durchfuehrungswege, Bav Cta Treuhand Spezial, Bav Pensionsfond Rueckdeckung Spezial im Plugin Bav Strategie Konzern konkret bearbeitet werden soll. Auslöser: Bitte Pensionsmodelle Fuenf Durchfuehrun... |
| `quellen-livecheck` | Nutze dies, wenn Rechtsquellen-Livecheck im Plugin Bav Strategie Konzern konkret bearbeitet werden soll. Auslöser: Welche amtliche Quelle prüfe ich zuerst?; Gibt es aktuelle Rechtsprechung?; Bitte Fundstellen verifizieren.. |
| `restrukturierung-beweislast-stil-strategische` | Nutze dies, wenn Spezial Restrukturierung Beweislast Und Darlegungslast, Spezial Stil Abschlussprodukt Und Übergabe, Spezial Strategische Erstpruefung Und Mandatsziel im Plugin Bav Strategie Konzern konkret bearbeitet werden soll. Auslös... |
| `stufen-theorie-interessen-versorgungssystem` | Nutze dies, wenn Spezial Stufen Compliance Dokumentation Und Akte, Spezial Theorie Mehrparteien Konflikt Und Interessen, Spezial Versorgungssystem International Schnittstellen im Plugin Bav Strategie Konzern konkret bearbeitet werden sol... |
| `unterlagen-luecken` | Nutze dies, wenn Unterlagen und Lücken im Plugin Bav Strategie Konzern konkret bearbeitet werden soll. Auslöser: Ich lade Unterlagen hoch.; Was fehlt noch?; Bitte Dokumente sortieren.. |
| `versorgungsordnung-betriebsvereinbarung` | Nutze dies, wenn Versorgungsordnung Und Betriebsvereinbarung Drafting im Plugin Bav Strategie Konzern konkret bearbeitet werden soll. Auslöser: Bitte Versorgungsordnung Und Betriebsvereinbarung Drafting prüfen.; Erstelle eine Arbeitsfass... |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
