# WEG- und Hausverwaltung

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`weg-hausverwaltung`) | [`weg-hausverwaltung.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/weg-hausverwaltung.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **WEG Hohenzollernhof — Hausverwaltung unter Druck** (`weg-hausverwaltung-hohenzollernhof`) | [Gesamt-PDF lesen](../testakten/weg-hausverwaltung-hohenzollernhof/gesamt-pdf/weg-hausverwaltung-hohenzollernhof_gesamt.pdf) | [`testakte-weg-hausverwaltung-hohenzollernhof.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-weg-hausverwaltung-hohenzollernhof.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

Operatives Plugin für Wohnungseigentümergemeinschaften, Hausverwaltungen, Verwaltungsbeiräte und anwaltliche Begleitung. Der Schwerpunkt liegt nicht auf abstrakter Dogmatik, sondern auf den täglichen Vorgängen: Eigentümerversammlung vorbereiten, Beschlussvorlagen schreiben, Beschlüsse protokollieren, Beschlusssammlung pflegen, Wirtschaftsplan und Jahresabrechnung prüfen, Hausgeld und Sonderumlagen verfolgen, Betriebskosten/Nebenkosten kontrollieren, Handwerker beauftragen, Erhaltungsmaßnahmen steuern, Restaurant- und Hausordnungskonflikte sortieren, E-Mobilität/Steckersolar/PV beschlussreif machen und rechtliche Eskalationen rechtzeitig erkennen.

Das Plugin arbeitet paralegal-praktisch: Es erstellt keine "Rechtsberatung aus dem Nichts", sondern strukturiert Akten, formuliert Beschluss- und Anschreibenentwürfe, baut Prüfmatrizen, markiert Fristen, trennt kaufmännische Verwaltung von Rechtsfragen und schlägt bei Risiko den passenden Anwalts- oder Gerichtspfad vor.

## Installation in Claude Code

1. ZIP herunterladen.
2. Claude Code -> **Customize Plugins** -> **Install from .zip** -> Datei wählen.
3. Fertig. Skills sind sofort verfügbar.

> Für den ZIP-Upload muss das Archiv direkt `.claude-plugin/plugin.json`, `skills/` und `references/` im ZIP-Root enthalten. Nicht das komplette Repository-ZIP aus "Code -> Download ZIP" verwenden.

## Quellen- und Rollenregel

- Rechtsprechung nur mit Gericht, Entscheidungsform, Datum, Aktenzeichen und frei prüfbarer Quelle.
- Keine BeckRS-, juris-, Kommentar-, Handbuch- oder Aufsatzfundstellen aus Modellwissen.
- Bei streitigen Beschlüssen, Verjährung, Anfechtung, Schadensersatz, Verwalterhaftung oder gerichtlichen Schritten immer anwaltliche Eskalation markieren.
- Verwaltungspraxis, kaufmännische Kontrolle und juristische Bewertung werden sichtbar getrennt.

## Enthaltene Skills

| Skill | Zweck |
| --- | --- |
| `allgemein` | Einstieg, Triage, Upload-Erkennung und Workflow-Routing im WEG-/Hausverwaltungsalltag. |
| `rechtsstand-mai-2026-faktenbank` | Quellen-Gate mit WEG/BGB/BetrKV-Ankern und frei verifizierten BGH-Linien. |
| `mandat-objekt-triage` | Objekt, Gemeinschaft, Rollen, Verwaltervertrag, Teilungserklärung, Fristen und Aktenlage erfassen. |
| `grossakte-konfliktlandkarte` | Große unübersichtliche Verwaltungsakten clustern, priorisieren und in passende Spezial-Skills routen. |
| `eigentuemerversammlung-vorbereiten` | Versammlung vom Themenstapel bis zur Beschlussreife planen. |
| `einladung-tagesordnung-fristen` | Einladung, Tagesordnung, Ladungsfristen und Vollmachten prüfen. |
| `beschlussvorlagen-erstellen` | Rechtssichere und verständliche Beschlussvorlagen mit Alternativen formulieren. |
| `protokollwerkstatt-top-marathon` | Lange Eigentümerversammlungen mit vielen TOPs protokollfähig strukturieren. |
| `beschlusssammlung-protokoll` | Protokoll, Beschlusssammlung, Verkündung, Anlagen und Nachversand strukturieren. |
| `beschlussanfechtung-risiko` | Anfechtungs- und Nichtigkeitsrisiken nach §§ 44 und 45 WEG erkennen. |
| `wirtschaftsplan-jahresabrechnung-28-weg` | Wirtschaftsplan, Jahresabrechnung, Vermögensbericht, Nachschüsse und Vorschüsse prüfen. |
| `abrechnung-ist-plan-mieterschnittstelle` | Ist-/Plan-Kosten, Verteilerschlüssel, Betriebskosten und vermietende Eigentümer zusammenführen. |
| `hausgeld-sonderumlage-liquiditaet` | Hausgeldrückstände, Sonderumlagen, Liquidität, Mahnung und Klagepfad ordnen. |
| `betriebskosten-nebenkostenabrechnung` | Betriebskosten/Nebenkosten nach BetrKV, Mietvertrag und WEG-Abrechnung kontrollieren. |
| `handwerker-beauftragung-vergabe` | Angebote einholen, vergleichen, beauftragen, Nachträge prüfen und Dokumentation sichern. |
| `erhaltung-modernisierung-baumaengel` | Erhaltung, Modernisierung, Mängel, Gewährleistung und Bauüberwachung verwalten. |
| `heizung-schaden-versicherung-notmassnahme` | Heizungsstörung, Wasserschaden, Versicherung, Sofortmaßnahme und Beschlussnachlauf ordnen. |
| `bauliche-veraenderungen-20-weg` | Bauliche Veränderungen nach §§ 20 und 21 WEG beschlussfähig vorbereiten. |
| `steckersolar-wallbox-barrierefreiheit` | Privilegierte Maßnahmen: Steckersolar, E-Mobilität, Einbruchsschutz, Glasfaser, Barrierefreiheit. |
| `e-mobilitaet-steckersolar-kellerstrom` | Wallbox, Ladeinfrastruktur, Dach-PV, Steckersolar und riskante Kellerstrom-Provisorien prüfen. |
| `verwalterpflichten-26-27-weg` | Bestellung, Abberufung, Vertretungsmacht, Maßnahmenkatalog, Verwaltervertrag. |
| `eigentuemerkommunikation-beschwerde` | Eigentümerkommunikation, Beschwerden, Eskalationsmails und transparente Antwortbausteine. |
| `stoerung-hausordnung-mieter-eigentuemer` | Lärm, Müll, Feuchtigkeit, Gemeinschaftsflächen, Mieter als Störer, Hausordnung. |
| `gewerbe-restaurant-geruch-laerm-hof` | Restaurant-/Gewerbekonflikte mit Geruch, Lärm, Müll, Lieferverkehr, Hofnutzung und Betreiberrollen. |
| `hausordnung-tauben-fahrrad-kinder-weihnachtsbaum` | Alltagssachen sauber sortieren: Tauben, Fahrraddiebstahl, Kinder, Weihnachtsbaum, Fluchtwege. |
| `beirat-controlling-verwalter` | Verwaltungsbeirat: Rechnungsprüfung, Angebotskontrolle, Protokollcheck, Eskalationsnotiz. |
| `datenschutz-dokumentenfreigabe` | DSGVO, Eigentümerlisten, Belegeinsicht, Schwärzungen, Cloud-Freigaben. |
| `eskalation-anwalt-amtsgericht` | Wann Anwalt, Amtsgericht, Beschlussklage, Hausgeldklage oder einstweiliger Rechtsschutz nötig wird. |

## Typische Workflows

**Eigentümerversammlung:** `grossakte-konfliktlandkarte` -> `eigentuemerversammlung-vorbereiten` -> `einladung-tagesordnung-fristen` -> `beschlussvorlagen-erstellen` -> `protokollwerkstatt-top-marathon` -> `beschlussanfechtung-risiko`.

**Jahresabrechnung:** `wirtschaftsplan-jahresabrechnung-28-weg` -> `abrechnung-ist-plan-mieterschnittstelle` -> `beirat-controlling-verwalter` -> `hausgeld-sonderumlage-liquiditaet` -> bei vermieteten Wohnungen zusätzlich `betriebskosten-nebenkostenabrechnung`.

**Handwerkermaßnahme:** `erhaltung-modernisierung-baumaengel` -> `handwerker-beauftragung-vergabe` -> `beschlussvorlagen-erstellen` -> `eigentuemerkommunikation-beschwerde` -> bei Streit `eskalation-anwalt-amtsgericht`.

**Alltagskonflikt:** `grossakte-konfliktlandkarte` -> `hausordnung-tauben-fahrrad-kinder-weihnachtsbaum` oder `gewerbe-restaurant-geruch-laerm-hof` -> `eigentuemerkommunikation-beschwerde` -> bei hartem Konflikt `eskalation-anwalt-amtsgericht`.

## Grenzen

Das Plugin ersetzt keine anwaltliche Beratung, keine WEG-Spezialkanzlei, keine Steuerberatung und keine technische Bauleitung. Es hilft, die Verwaltung so zu dokumentieren, dass Anwälte, Beiräte, Verwalter und Eigentümer sauber weiterarbeiten können.

<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 27 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `allgemein` | Einstieg, Schnelltriage und Workflow-Routing im WEG- und Hausverwaltungs-Plugin (Stand 05/2026). Ordnet Uploads, erkennt Fristen und Risiken, fragt Rolle und Objekt ab und schlägt passende Skills für Beschlüsse, Eigentümerversammlung, Ab... |
| `anwalt-amtsgericht-gewerbe-restaurant-grossakte` | Eskalation Anwalt Amtsgericht, Gewerbe Restaurant Geruch Laerm Hof, Grossakte Konfliktlandkarte: Eskalation Anwalt Amtsgericht; Gewerbe Restaurant Geruch Laerm Hof; Grossakte Konfliktlandkarte. Führt Intake, Prüfroutine, Normen-/Quellenr... |
| `bad-umbau-barrierefreie-einladung-bauliche-veraenderung` | Bad Umbau Bodengleiche Dusche Sondereigentum Gemeinschaft, Barrierefreie Einladung Protokoll Versammlung, Bauliche Veraenderung Aufzug Treppenlift 20 Abs 2 Weg: Bad Umbau Bodengleiche Dusche Sondereigentum Gemeinschaft; Barrierefreie Ein... |
| `bauliche-veraenderungen-beirat-controlling-beschlussanfechtung` | Bauliche Veraenderungen 20 Weg, Beirat Controlling Verwalter, Beschlussanfechtung Risiko: Bauliche Veraenderungen 20 Weg; Beirat Controlling Verwalter; Beschlussanfechtung Risiko. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislo... |
| `beschlusssammlung-betriebskosten-interessen` | Spezial Beschlusssammlung Schriftsatz Brief Und Memo Bausteine, Spezial Betriebskosten Mehrparteien Konflikt Und Interessen, Spezial Eigentuemerversammlung Risikoampel Und Gegenargumente: Spezial Beschlusssammlung Schriftsatz Brief Und M... |
| `beschlusssammlung-protokoll-beschlussvorlagen-erstellen` | Beschlusssammlung Protokoll, Beschlussvorlagen Erstellen, Betriebskosten Nebenkostenabrechnung: Beschlusssammlung Protokoll; Beschlussvorlagen Erstellen; Betriebskosten Nebenkostenabrechnung. Führt Intake, Prüfroutine, Normen-/Quellenrad... |
| `bfsg-hausverwalter-datenschutz-betroffenenrechte-datenpanne` | Bfsg Hausverwalter Website Portal 2025, Datenschutz Betroffenenrechte Auskunft Löschung Weg, Datenschutz Datenpanne Meldung 72H: Bfsg Hausverwalter Website Portal 2025; Datenschutz Betroffenenrechte Auskunft Löschung Weg; Datenschutz Dat... |
| `datenschutz-dokumentenfreigabe-datenschutz-vvt-digitale` | Datenschutz Dokumentenfreigabe, Datenschutz Vvt Tom Avv Hausverwaltung, Digitale Versammlung Screenreader Untertitel: Datenschutz Dokumentenfreigabe; Datenschutz Vvt Tom Avv Hausverwaltung; Digitale Versammlung Screenreader Untertitel. F... |
| `e-mobilitaet-eigentuemerkommunikation-beschwerde` | E Mobilitaet Steckersolar Kellerstrom, Eigentuemerkommunikation Beschwerde, Eigentuemerversammlung Vorbereiten: E Mobilitaet Steckersolar Kellerstrom; Eigentuemerkommunikation Beschwerde; Eigentuemerversammlung Vorbereiten. Führt Intake,... |
| `erhaltung-modernisierung-kfw-foerderung-abrechnung-ist` | Erhaltung Modernisierung Baumaengel, Kfw Foerderung Pflegekasse Bafa Barriere Koordination, Abrechnung Ist Plan Mieterschnittstelle: Erhaltung Modernisierung Baumaengel; Kfw Foerderung Pflegekasse Bafa Barriere Koordination; Abrechnung I... |
| `faktenbank-bauliche-beschluesse` | Rechtsstand Mai 2026 Faktenbank, Spezial Bauliche Formular Portal Und Einreichung, Spezial Beschluesse Dokumentenmatrix Und Lueckenliste: Rechtsstand Mai 2026 Faktenbank; Spezial Bauliche Formular Portal Und Einreichung; Spezial Beschlue... |
| `handwerker-beauftragung-hausgeld-sonderumlage-hausordnung-tauben` | Handwerker Beauftragung Vergabe, Hausgeld Sonderumlage Liquiditaet, Hausordnung Tauben Fahrrad Kinder Weihnachtsbaum: Handwerker Beauftragung Vergabe; Hausgeld Sonderumlage Liquiditaet; Hausordnung Tauben Fahrrad Kinder Weihnachtsbaum. F... |
| `handwerker-hausgeld-operatives` | Spezial Handwerker Internationaler Bezug Und Schnittstellen, Spezial Hausgeld Zahlen Schwellen Und Berechnung, Spezial Operatives Erstpruefung Und Mandatsziel: Spezial Handwerker Internationaler Bezug Und Schnittstellen; Spezial Hausgeld... |
| `hausverwaltungs-heizung-schaden-wegh-verwalterhaftung` | Spezial Hausverwaltungs Fristen Form Und Zustaendigkeit, Heizung Schaden Versicherung Notmassnahme, Wegh Verwalterhaftung Spezial: Spezial Hausverwaltungs Fristen Form Und Zustaendigkeit; Heizung Schaden Versicherung Notmassnahme; Wegh V... |
| `mandat-objekt-marketing-akquise-marketing-newsletter` | Mandat Objekt Triage, Marketing Akquise Neue Weg Mandate, Marketing Newsletter Eigentuemerkommunikation: Mandat Objekt Triage; Marketing Akquise Neue Weg Mandate; Marketing Newsletter Eigentuemerkommunikation. Führt Intake, Prüfroutine,... |
| `marketing-website-protokollwerkstatt-top-rampe-handlauf` | Marketing Website Impressum Tmg Und Bewertungen, Protokollwerkstatt Top Marathon, Rampe Handlauf Tuerverbreiterung Gemeinschaftsbereich: Marketing Website Impressum Tmg Und Bewertungen; Protokollwerkstatt Top Marathon; Rampe Handlauf Tue... |
| `protokoll-sonderumlage-weg` | Spezial Protokoll Behörden Gericht Und Registerweg, Spezial Sonderumlage Compliance Dokumentation Und Akte, Spezial Weg Tatbestand Beweis Und Belege: Spezial Protokoll Behörden Gericht Und Registerweg; Spezial Sonderumlage Compliance Dok... |
| `spezial-jahresabrechnung-livequellen-und-rechtsprechungscheck` | Jahresabrechnung: Livequellen- und Rechtsprechungscheck im WEG- und Hausverwaltungsrecht: fachlich vertiefter Spezialskill mit Normenradar (WEG/BGB/BetrKV), Tatbestands-/Beweislastmatrix, Fristen- und Formcheck, Gegenargumenten, Fehlerbr... |
| `top-generator-verwalterpflichten-weg-wegh-bauliche` | Top Generator Emotion Zu Beschluss, Verwalterpflichten 26 27 Weg, Wegh Bauliche Veraenderung Beschluss Spezial: Top Generator Emotion Zu Beschluss; Verwalterpflichten 26 27 Weg; Wegh Bauliche Veraenderung Beschluss Spezial. Führt Intake,... |
| `wegh-eigentuemerversammlung-wirtschaftsplan-jahresabrechnung` | Wegh Eigentuemerversammlung Bauleiter, Wegh Wirtschaftsplan Jahresabrechnung Leitfaden, Wirtschaftsplan Jahresabrechnung 28 Weg: Wegh Eigentuemerversammlung Bauleiter; Wegh Wirtschaftsplan Jahresabrechnung Leitfaden; Wirtschaftsplan Jahr... |
| `wirtschaftsplan-steckersolar-wallbox-stoerung-hausordnung` | Spezial Wirtschaftsplan Verhandlung Vergleich Und Eskalation, Steckersolar Wallbox Barrierefreiheit, Stoerung Hausordnung Mieter Eigentuemer: Spezial Wirtschaftsplan Verhandlung Vergleich Und Eskalation; Steckersolar Wallbox Barrierefrei... |
| `workflow-chronologie-fristen-risikoampel-einladung-tagesordnung` | Workflow Chronologie Und Belegmatrix, Workflow Fristen Und Risikoampel, Einladung Tagesordnung Fristen: Workflow Chronologie Und Belegmatrix; Workflow Fristen Und Risikoampel; Einladung Tagesordnung Fristen. Führt Intake, Prüfroutine, No... |
| `workflow-dokumentenintake` | Dokumentenintake im Plugin weg-hausverwaltung: liest Uploads, sortiert Dokumentarten, markiert Fristen und baut eine knappe Arbeitsakte. |
| `workflow-kaltstart-und-routing` | Kaltstart und Routing im Plugin weg-hausverwaltung: führt vom ersten Satz oder Dokument in den passenden Arbeitsweg, erkennt Rolle, Ziel, Risiko und Anschluss-Skills. |
| `workflow-output-waehlen` | Output wählen im Plugin weg-hausverwaltung: entscheidet zwischen Memo, Schriftsatz, Tabelle, Brief, Checkliste, Vermerk, Redline oder Mandantenübersetzung. |
| `workflow-rechtsquellen-livecheck` | Rechtsquellen-Livecheck im Plugin weg-hausverwaltung: zwingt vor tragenden Aussagen zum aktuellen Quellencheck bei Gesetzen, Behörden, Gerichten und Formularen. |
| `workflow-unterlagen-lueckenliste` | Unterlagen- und Lückenliste im Plugin weg-hausverwaltung: erstellt eine präzise Nachforderungsliste statt allgemeiner Fragebögen. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
