# Fachanwalt Strafrecht

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`fachanwalt-strafrecht`) | [`fachanwalt-strafrecht.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/fachanwalt-strafrecht.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **BtM-Akte** (`betaeubungsmittelrecht-apotheke-substitution-festival`) | [Gesamt-PDF lesen](../testakten/betaeubungsmittelrecht-apotheke-substitution-festival/gesamt-pdf/betaeubungsmittelrecht-apotheke-substitution-festival_gesamt.pdf) | [`testakte-betaeubungsmittelrecht-apotheke-substitution-festival.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-betaeubungsmittelrecht-apotheke-substitution-festival.zip) |
| **Grossbankrott und Zeugenstreit — Mehrere Deliktszweige, Pellbach Logistik & Spedition GmbH, LG Koeln** (`grossbankrott-und-zeugenstreit-mehrere-deliktszweige-vellbruck-koeln`) | [Gesamt-PDF lesen](../testakten/grossbankrott-und-zeugenstreit-mehrere-deliktszweige-vellbruck-koeln/gesamt-pdf/grossbankrott-und-zeugenstreit-mehrere-deliktszweige-vellbruck-koeln_gesamt.pdf) | [`testakte-grossbankrott-und-zeugenstreit-mehrere-deliktszweige-vellbruck-koeln.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-grossbankrott-und-zeugenstreit-mehrere-deliktszweige-vellbruck-koeln.zip) |
| **Wirtschaftsstrafsache Bankert — U-Haft, Betrug, Steuerhinterziehung, LG Frankfurt** (`wirtschaftsstrafsache-uhaft-bankert-frankfurt`) | [Gesamt-PDF lesen](../testakten/wirtschaftsstrafsache-uhaft-bankert-frankfurt/gesamt-pdf/wirtschaftsstrafsache-uhaft-bankert-frankfurt_gesamt.pdf) | [`testakte-wirtschaftsstrafsache-uhaft-bankert-frankfurt.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-wirtschaftsstrafsache-uhaft-bankert-frankfurt.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

## Was dieses Plugin im Strafprozess leistet

Dieses Plugin ist als Arbeitscockpit für Strafverteidigung gedacht: nicht nur für die große Strategie, sondern für die täglichen Schritte einer laufenden Strafakte. Es ordnet Eingänge, markiert Fristen, baut Aktenlog und Wiedervorlagen, steuert Akteneinsicht, U-Haft, Pflichtverteidigung, Hauptverhandlung, Antragslog, Mandanteninstruktionen, Rechtsmittel und Vollstreckungsnachlauf.

Der Kaltstart soll sofort praktisch werden: Was ist heute gefährlich, welche Frist läuft, welcher Schriftsatz oder Anruf muss raus, welche Aktenbestandteile fehlen, was darf der Mandant keinesfalls ohne Rücksprache tun? Danach schlägt das Plugin die passenden Strafprozess-Skills aus diesem Plugin vor und hält das Ergebnis als Checkliste, Matrix, Memo, Mandantenbrief oder Schriftsatzbaustein fest.

Neu aufgenommen ist ein vertiefter Prüfpfad für digitale Ermittlungsmaßnahmen: biometrischer Internetabgleich, KI-gestützte Trefferlisten, verfahrensübergreifende Analyseplattformen, Akteneinsicht in technische Protokolle, Löschung, Benachrichtigung, KI-VO-Konformität und Verwertungsangriffe. Der Skill behandelt solche Maßnahmen ausdrücklich als rechtsstandsabhängig: Entwurf, Inkrafttreten und aktueller Wortlaut sind vor jeder tragenden Aussage live zu prüfen.

Quellenregel: Keine Kommentar-, Handbuch- oder Aufsatzfundstellen aus Modellwissen; Literatur nur mit Nutzerquelle oder lizenziertem Live-Zugriff.

## Installation in Claude Code

1. ZIP herunterladen (Link oben).
2. Claude Code → **Customize Plugins** → **Install from .zip** → Datei wählen.
3. Fertig. Skills sind sofort verfügbar.

> **Hinweis:** Für den ZIP-Upload muss das Archiv direkt `.claude-plugin/plugin.json`, `skills/`, `assets/` und `references/` im ZIP-Root enthalten. **Nicht** das komplette Repository-ZIP aus "Code → Download ZIP" verwenden.

## Enthaltene Skills

| Skill | Zweck |
| --- | --- |
| `strafprozess-cockpit-taegliche-kanzleifuehrung` | Laufendes Verteidigungs-Cockpit mit Verfahrensstand, Fristen, Haftlage, Akteneinsicht, offenen Anträgen, Terminen und nächstem Schritt. |
| `strafprozess-aktenlog-fristen-und-wiedervorlagen` | Macht aus beA-/EGVP-Eingängen, Beschlüssen, Ladungen, Strafbefehlen, Urteilen und Nachlieferungen ein belastbares Fristen- und Aufgabenlog. |
| `strafprozess-haft-und-besuchsmanagement` | Organisiert U-Haft, Haftprüfung, Haftbeschwerde, Haftverschonung, Akteneinsicht, Besuch, Telefon, Familie, Arbeitgeber und Beschleunigungskontrolle. |
| `strafprozess-hv-tagesmappe-und-sitzungsplan` | Baut für jeden Sitzungstag eine Hauptverhandlungs-Tagesmappe mit Zeugenprogramm, Fragelisten, Einlassungsfenster, Antragsentwürfen und Nachbereitung. |
| `strafprozess-sitzungsprotokoll-und-revisionssicherung` | Sichert Protokollierung, Anträge, Belehrungen, Verständigung, letztes Wort und mögliche Revisionsrügen während und nach der Hauptverhandlung. |
| `fachanwalt-strafrecht-orientierung` | Orientierung im Strafrecht — FAO-Voraussetzungen Normen typische Mandate Notfristen Quellenprüfung. Plugin für schnelle Verortung. Strafverteidigung im Ermittlungsverfahren (Akteneinsicht § 147 StPO) H… |

## Lizenz

Apache-2.0 OR MIT — Auswahl beim Empfänger.


<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 37 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `komp-01-teil-02-workflow-redteam-qualitygate` | fachanwalt-strafrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Redteam Qualitygate, Strafrecht Adhaesionsverfahren, Ermittlungsverfahren Vergleich Eskalation, Orientierung Fristen Form Und Zustaendigkeit und 1 weitere... |
| `komp-02-teil-02-strafrecht-spezial-untreue-schaden-und-bez` | fachanwalt-strafrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Strafrecht Spezial Untreue Schaden Und Bezifferbarkeit, Strafrecht Spezial Verbandssanktionengesetz Stand 2026, Strafprozess Akteneinsicht Nachlieferungen... |
| `komp-03-teil-02-fachanwalt-strafrecht-chatcontrol-csam-anw` | fachanwalt-strafrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Strafrecht Chatcontrol Csam Anwaltsgeheimnis 53 Stpo, Strafrecht Einlassung Vorbereiten, Strafrecht Hauptverhandlung Vorbereiten, Strafrecht Insolvenzantr... |
| `komp-04-teil-02-mandat-triage-strafrecht` | fachanwalt-strafrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Mandat Triage Strafrecht, Plaedoyer Vorbereitung Strafverteidigung, Schriftsatzkern Substantiierung, Adhaesion Formular Portal Und Einreichung und 1 weite... |
| `komp-05-teil-02-spezial-nebenklage-compliance-dokumentatio` | fachanwalt-strafrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Nebenklage Compliance Dokumentation Und Akte, Nebenstrafrecht Behoerden Gericht Und Registerweg, Opfervertretung Mehrparteien Konflikt Und Interessen, Rev... |
| `komp-06-teil-02-strafprozess-antragslog-beweisantraege-und` | fachanwalt-strafrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Strafprozess Antragslog Beweisantraege Und Widerspruch, Strafprozess Biometrischer Internetabgleich 98d Stpo E, Strafprozess Cockpit Taegliche Kanzleifueh... |
| `komp-07-teil-02-strafr-dysfunk-befangenheitsantrag-zielgen` | fachanwalt-strafrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Strafr Dysfunk Befangenheitsantrag Zielgenau, Strafr Dysfunk Beistandsleistung 137 Stpo, Strafr Dysfunk Beweisantrag Fundament, Strafr Dysfunk Beweisantra... |
| `komp-09-teil-02-strafr-vermoegensabschoepfung-spezial` | fachanwalt-strafrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Strafr Vermoegensabschoepfung Spezial, Strafr Wirtschaftsstrafrecht Leitfaden, Strafrecht Polizeifilmerei 201 Stgb Kug Verteidigung, Strafrecht Spezial 18... |
| `kompendium-01-allgemein-bis-strafprozess-aktenlo` | fachanwalt-strafrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Allgemein, Strafr Haftpruefung Haftbeschwerde Workflow, Chronologie Und Belegmatrix, Fristen Und Risikoampel und 1 weitere Arbeitsmodule; mit Intake, Prüf... |
| `kompendium-02-strafprozess-ermittl-bis-strafrecht-spezial-s` | fachanwalt-strafrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Strafprozess Ermittlungsverfahren Sofortmassnahmen, Strafprozess Rechtsmittel Und Notfristencockpit, Strafrecht Spezial Btmg Strafverfahren Praxis, Strafr... |
| `kompendium-03-strafrecht-spezial-s-bis-fachanwalt-strafrech` | fachanwalt-strafrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Strafrecht Spezial Steuerstrafrecht 371 Ao Selbstanzeige, Akteneinsicht Strafrecht Auswerten, Erstgespraech Mandatsannahme, Strafrecht Akteneinsicht Beant... |
| `kompendium-04-fachanwalt-strafrech-bis-spezial-aktenaufbere` | fachanwalt-strafrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Strafrecht Orientierung, Strafrecht Untersuchungshaft Haftpruefung, Strafrecht Verstaendigung 257c Toa 46a, Strafrecht Wahlverteidiger Mandat und 1 weiter... |
| `kompendium-05-spezial-ergaenzt-man-bis-spezial-stgb-risikoa` | fachanwalt-strafrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Ergaenzt Mandantenkommunikation Entscheidungsvorlage, Fachanwalt Erstpruefung Und Mandatsziel, Insolvenzantrag Red Team Und Qualitaetskontrolle, Kanzlei S... |
| `kompendium-06-spezial-stpo-dokumen-bis-strafprozess-hv-tage` | fachanwalt-strafrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Stpo Dokumentenmatrix Und Lueckenliste, Strafrecht Tatbestand Beweis Und Belege, Strafverteidigung Schriftsatz Brief Und Memo Bausteine, Zeugenbeistand In... |
| `kompendium-07-strafprozess-mandant-bis-strafr-dysfunk-conte` | fachanwalt-strafrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Strafprozess Mandantenkommunikation Und Instruktionen, Strafprozess Pflichtverteidigung Beiordnung Und Wechsel, Strafprozess Sitzungsprotokoll Und Revisio... |
| `kompendium-08-strafr-dysfunk-darle-bis-strafr-dysfunk-senat` | fachanwalt-strafrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Strafr Dysfunk Darlegungslast Umkehren, Strafr Dysfunk Empirie Nutzen, Strafr Dysfunk Erklaerungsrecht 257 Stpo, Strafr Dysfunk Hinweis Auf Heilbaren Fehl... |
| `kompendium-09-strafr-dysfunk-sitzu-bis-strafrecht-spezial-1` | fachanwalt-strafrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Strafr Dysfunk Sitzungspolizei Ordnungsmittel, Strafr Dysfunk Verschleppungsabsicht Abgrenzen, Strafr Dysfunk Vorwurf Einordnen, Strafr Dysfunk Wahlvertei... |
| `kompendium-10-strafrecht-spezial-1-bis-strafrecht-spezial-a` | fachanwalt-strafrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Strafrecht Spezial 188 Stgb Easy Verteidigung, Strafrecht Spezial 188 Stgb Social Media Beweise, Strafrecht Spezial Amtsdelikte 340 Stgb Koerperverletzung... |
| `kompendium-11-strafrecht-spezial-a-bis-strafrecht-spezial-a` | fachanwalt-strafrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Strafrecht Spezial Aussagepsy Suggestion Falscherinnerung, Strafrecht Spezial Aussagepsy Tuechtigkeit Bereitschaft, Strafrecht Spezial Aussagepsy Vernehmu... |
| `kompendium-12-strafrecht-spezial-a-bis-strafrecht-spezial-b` | fachanwalt-strafrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Strafrecht Spezial Aussagepsychologie Staatsanwaltschaft Replik, Strafrecht Spezial Aussagepsychologie Vernehmungslehre Praxis, Strafrecht Spezial Aussetz... |
| `kompendium-13-strafrecht-spezial-b-bis-strafrecht-spezial-c` | fachanwalt-strafrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Strafrecht Spezial Betrug 263 Stgb Grundtatbestand, Strafrecht Spezial Btmg 29 Grundtatbestand, Strafrecht Spezial Btmg 29a Nicht Geringe Menge, Strafrech... |
| `kompendium-14-strafrecht-spezial-c-bis-strafrecht-spezial-g` | fachanwalt-strafrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Strafrecht Spezial Computerbetrug 263a Stgb, Strafrecht Spezial Design Strafrecht 51 Designg, Strafrecht Spezial Erpresserischer Menschenraub 239a 239b St... |
| `kompendium-15-strafrecht-spezial-g-bis-strafrecht-spezial-k` | fachanwalt-strafrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Strafrecht Spezial Gmbh Verletzung Anzeigepflicht 84 Gmbhg, Strafrecht Spezial Insiderhandel 119 Wphg, Strafrecht Spezial Insolvenzverschleppung 15a Inso,... |
| `kompendium-16-strafrecht-spezial-k-bis-strafrecht-spezial-m` | fachanwalt-strafrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Strafrecht Spezial Koerperverletzung 223 Stgb Grund, Strafrecht Spezial Koerperverletzung Mit Todesfolge 227 Stgb, Strafrecht Spezial Konkursrechtliche An... |
| `kompendium-17-strafrecht-spezial-m-bis-strafrecht-spezial-r` | fachanwalt-strafrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Strafrecht Spezial Markenrecht 143a Markeng Bandenmaessig, Strafrecht Spezial Marktmanipulation 120 Wphg, Strafrecht Spezial Mietwucher 5 Wistg, Strafrech... |
| `kompendium-18-strafrecht-spezial-r-bis-strafrecht-spezial-s` | fachanwalt-strafrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Strafrecht Spezial Raub 249 Stgb, Strafrecht Spezial Raub Mit Todesfolge 251 Stgb, Strafrecht Spezial Rechtsbeugung 339 Stgb, Strafrecht Spezial Schuldner... |
| `kompendium-19-strafrecht-spezial-s-bis-strafrecht-spezial-u` | fachanwalt-strafrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Strafrecht Spezial Subventionsbetrug 264 Stgb, Strafrecht Spezial Toetung Auf Verlangen 216 Stgb, Strafrecht Spezial Totschlag 212 Stgb, Strafrecht Spezia... |
| `kompendium-20-strafrecht-spezial-u-bis-strafrecht-spezial-v` | fachanwalt-strafrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Strafrecht Spezial Urheberrecht 108 Urhg Unerlaubte Eingriffe, Strafrecht Spezial Urheberrecht 108a Urhg Gewerblich, Strafrecht Spezial Urheberrecht 108b... |
| `kompendium-21-strafrecht-spezial-v-bis-vergleichsverhandlun` | fachanwalt-strafrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Strafrecht Spezial Versicherungsbetrug 265 Stgb, Strafrecht Spezial Vorenthalten Arbeitgeberanteile 266a Stgb, Strafrecht Spezial Vorteilsannahme Gewaehru... |
| `spezial-hauptverhandlung-livequellen-und-rechtsprechungscheck` | Hauptverhandlung: Livequellen- und Rechtsprechungscheck im Plugin fachanwalt strafrecht; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Standardprüfung. |
| `spezial-rechtsquellen-fristennotiz-und-naechster-schritt` | Rechtsquellen: Fristennotiz und nächster Schritt im Plugin fachanwalt strafrecht; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Standardprüfung. |
| `workflow-anschluss-skills-router` | Anschluss-Skills Router im Plugin fachanwalt-strafrecht: schlägt nach der ersten Prüfung die passenden Spezialskills aus demselben Plugin vor. |
| `workflow-dokumentenintake` | Dokumentenintake im Plugin fachanwalt-strafrecht: liest Uploads, sortiert Dokumentarten, markiert Fristen, erkennt U-Haft-, Akteneinsichts-, Rechtsmittel- und Hauptverhandlungsrisiken und baut eine knappe Arbeitsakte mit Anschluss-Skills. |
| `workflow-kaltstart-und-routing` | Kaltstart und Routing im Plugin fachanwalt-strafrecht: führt vom ersten Satz oder Dokument in den passenden Arbeitsweg, erkennt Rolle, Ziel, Risiko und Anschluss-Skills. |
| `workflow-output-waehlen` | Output wählen im Plugin fachanwalt-strafrecht: entscheidet zwischen Memo, Schriftsatz, Tabelle, Brief, Checkliste, Vermerk, Redline oder Mandantenübersetzung. |
| `workflow-rechtsquellen-livecheck` | Rechtsquellen-Livecheck im Plugin fachanwalt-strafrecht: zwingt vor tragenden Aussagen zum aktuellen Quellencheck bei Gesetzen, Behörden, Gerichten und Formularen. |
| `workflow-unterlagen-lueckenliste` | Unterlagen- und Lückenliste im Plugin fachanwalt-strafrecht: erstellt eine präzise Nachforderungsliste statt allgemeiner Fragebögen. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
