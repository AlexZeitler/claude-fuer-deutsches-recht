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
| `adhaesionsverfahren-ermittlungsverfahren` | Nutze dies, wenn Workflow Redteam Qualitygate, Fachanwalt Strafrecht Adhaesionsverfahren, Spezial Ermittlungsverfahren Vergleich Eskalation, Spezial Orientierung Fristen Form Und Zustaendigkeit, Strafprozess Aktenlog Fristen Und Wiedervo... |
| `anschluss-routing` | Nutze dies, wenn Anschluss-Routing im Plugin Fachanwalt Strafrecht konkret bearbeitet werden soll. Auslöser: Ich habe ein neues Thema im Bereich Fachanwalt Strafrecht.; Welche Unterlagen brauchen Sie?; Welcher Spezialskill passt?. |
| `aussagepsychologie-staatsanwaltschaft` | Nutze dies, wenn Strafrecht Spezial Aussagepsychologie Staatsanwaltschaft Replik, Strafrecht Spezial Aussagepsychologie Vernehmungslehre Praxis, Strafrecht Spezial Aussetzung 221 Stgb, Strafrecht Spezial Bandenbetrug 263 Stgb, Strafrecht... |
| `chatcontrol-csam-einlassung-vorbereiten` | Nutze dies, wenn Fachanwalt Strafrecht Chatcontrol Csam Anwaltsgeheimnis 53 Stpo, Fachanwalt Strafrecht Einlassung Vorbereiten, Fachanwalt Strafrecht Hauptverhandlung Vorbereiten, Fachanwalt Strafrecht Insolvenzantrag Staatsanwaltschaft,... |
| `dokumente-intake` | Nutze dies, wenn Dokumentenintake im Plugin Fachanwalt Strafrecht konkret bearbeitet werden soll. Auslöser: Ich lade Unterlagen hoch.; Was fehlt noch?; Bitte Dokumente sortieren.. |
| `einstieg-routing` | Nutze dies, wenn Einstieg und Routing im Plugin Fachanwalt Strafrecht konkret bearbeitet werden soll. Auslöser: Ich habe ein neues Thema im Bereich Fachanwalt Strafrecht.; Welche Unterlagen brauchen Sie?; Welcher Spezialskill passt?. |
| `ergaenzt-fachanwalt-insolvenzantrag-red` | Nutze dies, wenn Spezial Ergaenzt Mandantenkommunikation Entscheidungsvorlage, Spezial Fachanwalt Erstpruefung Und Mandatsziel, Spezial Insolvenzantrag Red Team Und Qualitaetskontrolle, Spezial Kanzlei Sonderfall Und Edge Case, Spezial L... |
| `fachanwalt-strafrecht-orientierung` | Nutze dies, wenn Fachanwalt Strafrecht Orientierung, Fachanwalt Strafrecht Untersuchungshaft Haftpruefung, Fachanwalt Strafrecht Verstaendigung 257C Toa 46A, Fachanwalt Strafrecht Wahlverteidiger Mandat, Fachanwalt Strafrecht Zeugenbeist... |
| `hauptverhandlung-quellenkarte` | Nutze dies, wenn Hauptverhandlung Quellenkarte im Plugin Fachanwalt Strafrecht konkret bearbeitet werden soll. Auslöser: Welche amtliche Quelle prüfe ich zuerst?; Gibt es aktuelle Rechtsprechung?; Bitte Fundstellen verifizieren.. |
| `koerperverletzung-stgb-todesfolge` | Nutze dies, wenn Strafrecht Spezial Koerperverletzung 223 Stgb Grund, Strafrecht Spezial Koerperverletzung Mit Todesfolge 227 Stgb, Strafrecht Spezial Konkursrechtliche Anfechtungsbezuege, Strafrecht Spezial Kreditbetrug 265B Stgb, Straf... |
| `mandat-triage-plaedoyer-vorbereitung` | Nutze dies, wenn Mandat Triage Strafrecht, Plaedoyer Vorbereitung Strafverteidigung, Schriftsatzkern Substantiierung, Spezial Adhaesion Formular Portal Und Einreichung, Spezial Aktenaufbereiter Beweislast Und Darlegungslast im Plugin Fac... |
| `nebenklage-nebenstrafrecht-opfervertretung` | Nutze dies, wenn Spezial Nebenklage Compliance Dokumentation Und Akte, Spezial Nebenstrafrecht Behörden Gericht Und Registerweg, Spezial Opfervertretung Mehrparteien Konflikt Und Interessen, Spezial Revision Zahlen Schwellen Und Berechnu... |
| `output-waehlen` | Nutze dies, wenn Output wählen im Plugin Fachanwalt Strafrecht konkret bearbeitet werden soll. Auslöser: Bitte Output wählen prüfen.; Erstelle eine Arbeitsfassung zu Output wählen.; Welche Normen und Nachweise brauche ich?. |
| `quellen-livecheck` | Nutze dies, wenn Rechtsquellen-Livecheck im Plugin Fachanwalt Strafrecht konkret bearbeitet werden soll. Auslöser: Welche amtliche Quelle prüfe ich zuerst?; Gibt es aktuelle Rechtsprechung?; Bitte Fundstellen verifizieren.. |
| `raub-stgb-raub-todesfolge-rechtsbeugung-stgb` | Nutze dies, wenn Strafrecht Spezial Raub 249 Stgb, Strafrecht Spezial Raub Mit Todesfolge 251 Stgb, Strafrecht Spezial Rechtsbeugung 339 Stgb, Strafrecht Spezial Schuldnerbeguenstigung 283D Stgb, Strafrecht Spezial Schwere Koerperverletz... |
| `rechtsquellen-fristennotiz-naechster-schritt` | Nutze dies, wenn Rechtsquellen: Fristennotiz und nächster Schritt im Plugin Fachanwalt Strafrecht konkret bearbeitet werden soll. Auslöser: Welche amtliche Quelle prüfe ich zuerst?; Gibt es aktuelle Rechtsprechung?; Bitte Fundstellen ver... |
| `steuerstrafrecht-ao-akteneinsicht-auswerten` | Nutze dies, wenn Strafrecht Spezial Steuerstrafrecht 371 Ao Selbstanzeige, Akteneinsicht Strafrecht Auswerten, Erstgespraech Mandatsannahme, Fachanwalt Strafrecht Akteneinsicht Beantragen, Fachanwalt Strafrecht Anklage Reaktion im Plugin... |
| `stpo-strafrecht-strafverteidigung` | Nutze dies, wenn Spezial Stpo Dokumentenmatrix Und Lueckenliste, Spezial Strafrecht Tatbestand Beweis Und Belege, Spezial Strafverteidigung Schriftsatz Brief Und Memo Bausteine, Spezial Zeugenbeistand Internationaler Bezug Und Schnittste... |
| `strafprozess-antragslog-beweisantraege` | Nutze dies, wenn Strafprozess Antragslog Beweisantraege Und Widerspruch, Strafprozess Biometrischer Internetabgleich 98D Stpo E, Strafprozess Cockpit Taegliche Kanzleifuehrung, Strafprozess Haft Und Besuchsmanagement, Strafprozess Hv Tag... |
| `strafprozess-instruktionen` | Nutze dies, wenn Strafprozess Mandantenkommunikation Und Instruktionen, Strafprozess Pflichtverteidigung Beiordnung Und Wechsel, Strafprozess Sitzungsprotokoll Und Revisionssicherung, Strafprozess Verhandlungslog Sta Gericht Nebenklage,... |
| `strafr-dysfunk-befangenheitsantrag` | Nutze dies, wenn Strafr Dysfunk Befangenheitsantrag Zielgenau, Strafr Dysfunk Beistandsleistung 137 Stpo, Strafr Dysfunk Beweisantrag Fundament, Strafr Dysfunk Beweisantragsstrategie, Strafr Dysfunk Contempt Of Court Debatte 177A im Plug... |
| `strafr-dysfunk-darlegungslast-empirie-nutzen` | Nutze dies, wenn Strafr Dysfunk Darlegungslast Umkehren, Strafr Dysfunk Empirie Nutzen, Strafr Dysfunk Erklaerungsrecht 257 Stpo, Strafr Dysfunk Hinweis Auf Heilbaren Fehler, Strafr Dysfunk Institutsmissbrauch Kritik und 5 weitere Themen... |
| `strafr-dysfunk-sitzungspolizei` | Nutze dies, wenn Strafr Dysfunk Sitzungspolizei Ordnungsmittel, Strafr Dysfunk Verschleppungsabsicht Abgrenzen, Strafr Dysfunk Vorwurf Einordnen, Strafr Dysfunk Wahlverteidigerausschluss 138A, Strafr Revision Prüfung Spezial im Plugin Fa... |
| `strafr-haftpruefung` | Nutze dies, wenn Allgemein, Strafr Haftpruefung Haftbeschwerde Workflow, Workflow Chronologie Und Belegmatrix, Workflow Fristen Und Risikoampel, Workflow Mandantenkommunikation im Plugin Fachanwalt Strafrecht konkret bearbeitet werden so... |
| `strafr-vermoegensabschoepfung` | Nutze dies, wenn Strafr Vermoegensabschoepfung Spezial, Strafr Wirtschaftsstrafrecht Leitfaden, Strafrecht Polizeifilmerei 201 Stgb Kug Verteidigung, Strafrecht Spezial 188 Stgb Anklage Und Strafbefehl, Strafrecht Spezial 188 Stgb Art5 S... |
| `strafrecht-aussagepsy-suggestion-tuechtigkeit` | Nutze dies, wenn Strafrecht Spezial Aussagepsy Suggestion Falscherinnerung, Strafrecht Spezial Aussagepsy Tuechtigkeit Bereitschaft, Strafrecht Spezial Aussagepsy Vernehmungsfehler Falschgestand, Strafrecht Spezial Aussagepsychologie Bgh... |
| `strafrecht-betrug-stgb-btmg-grundtatbestand` | Nutze dies, wenn Strafrecht Spezial Betrug 263 Stgb Grundtatbestand, Strafrecht Spezial Btmg 29 Grundtatbestand, Strafrecht Spezial Btmg 29A Nicht Geringe Menge, Strafrecht Spezial Btmg 30 Handeltreiben, Strafrecht Spezial Btmg 30A Schwe... |
| `strafrecht-computerbetrug-263a-design-designg` | Nutze dies, wenn Strafrecht Spezial Computerbetrug 263A Stgb, Strafrecht Spezial Design Strafrecht 51 Designg, Strafrecht Spezial Erpresserischer Menschenraub 239A 239B Stgb, Strafrecht Spezial Faktische Geschaeftsfuehrer, Strafrecht Spe... |
| `strafrecht-gmbh-verletzung-insiderhandel-wphg` | Nutze dies, wenn Strafrecht Spezial Gmbh Verletzung Anzeigepflicht 84 Gmbhg, Strafrecht Spezial Insiderhandel 119 Wphg, Strafrecht Spezial Insolvenzverschleppung 15A Inso, Strafrecht Spezial Ip Strafrecht Grenzbeschlagnahme, Strafrecht S... |
| `strafrecht-markenrecht-143a-marktmanipulation` | Nutze dies, wenn Strafrecht Spezial Markenrecht 143A Markeng Bandenmaessig, Strafrecht Spezial Marktmanipulation 120 Wphg, Strafrecht Spezial Mietwucher 5 Wistg, Strafrecht Spezial Minder Schwerer Fall 213 Stgb, Strafrecht Spezial Missha... |
| `strafrecht-stgb-easy-social-media-amtsdelikte` | Nutze dies, wenn Strafrecht Spezial 188 Stgb Easy Verteidigung, Strafrecht Spezial 188 Stgb Social Media Beweise, Strafrecht Spezial Amtsdelikte 340 Stgb Koerperverletzung Im Amt, Strafrecht Spezial Amtstraegerbestechung 332 334 Stgb, St... |
| `strafrecht-strafprozess-ermittlungsverfahren` | Nutze dies, wenn Strafprozess Ermittlungsverfahren Sofortmassnahmen, Strafprozess Rechtsmittel Und Notfristencockpit, Strafrecht Spezial Btmg Strafverfahren Praxis, Strafrecht Spezial Haeusliche Gewalt Im Strafverfahren, Strafrecht Spezi... |
| `strafrecht-untreue-schaden` | Nutze dies, wenn Strafrecht Spezial Untreue Schaden Und Bezifferbarkeit, Strafrecht Spezial Verbandssanktionengesetz Stand 2026, Strafprozess Akteneinsicht Nachlieferungen Und Sonderbaende, Strafrecht Spezial Steuerstrafrecht 370 Ao Steu... |
| `strafrecht-urheberrecht-urhg-108a-gewerblich` | Nutze dies, wenn Strafrecht Spezial Urheberrecht 108 Urhg Unerlaubte Eingriffe, Strafrecht Spezial Urheberrecht 108A Urhg Gewerblich, Strafrecht Spezial Urheberrecht 108B Urhg Tpm, Strafrecht Spezial Vergewaltigung 177 Stgb, Strafrecht S... |
| `subventionsbetrug-stgb-toetung-verlangen` | Nutze dies, wenn Strafrecht Spezial Subventionsbetrug 264 Stgb, Strafrecht Spezial Toetung Auf Verlangen 216 Stgb, Strafrecht Spezial Totschlag 212 Stgb, Strafrecht Spezial Umweltstrafrecht 324 Stgb Gewaesser, Strafrecht Spezial Umweltst... |
| `unterlagen-luecken` | Nutze dies, wenn Unterlagen und Lücken im Plugin Fachanwalt Strafrecht konkret bearbeitet werden soll. Auslöser: Ich lade Unterlagen hoch.; Was fehlt noch?; Bitte Dokumente sortieren.. |
| `versicherungsbetrug-stgb-vorenthalten` | Nutze dies, wenn Strafrecht Spezial Versicherungsbetrug 265 Stgb, Strafrecht Spezial Vorenthalten Arbeitgeberanteile 266A Stgb, Strafrecht Spezial Vorteilsannahme Gewaehrung 331 333 Stgb, Strafrecht Spezial Waffg Strafvorschriften 51 52,... |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
