# selbstvertreter-amtsgericht

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`selbstvertreter-amtsgericht`) | [`selbstvertreter-amtsgericht.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/selbstvertreter-amtsgericht.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **Akte Selbstvertreter Amtsgericht — Küchentisch Kaufpreis** (`selbstvertreter-amtsgericht-kuechentisch-kaufpreis`) | [Gesamt-PDF lesen](../testakten/selbstvertreter-amtsgericht-kuechentisch-kaufpreis/gesamt-pdf/selbstvertreter-amtsgericht-kuechentisch-kaufpreis_gesamt.pdf) | [`testakte-selbstvertreter-amtsgericht-kuechentisch-kaufpreis.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-selbstvertreter-amtsgericht-kuechentisch-kaufpreis.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

## Für wen?

- Sie wollen eine Geldforderung bis zur Wertgrenze des § 23 Nr. 1 GVG einklagen (seit 01.01.2026: **10.000 EUR**, Anhebung von 5.000 EUR durch das Justizstandort-Stärkungsgesetz).
- Sie sind verklagt worden und wollen sich selbst verteidigen.
- Sie wollen Mietsachen, Reisemängel, Familienunterhalt oder andere AG-typische Streitigkeiten betreiben.
- Sie wollen vor einer möglichen Mandatierung verstehen, was rechtlich passiert.

## Was kann das Plugin?

Es liefert Skills zu:

- **Anfänger-Workflow**: geführter Modus mit kleinen Schritten, einfacher Sprache, Frist zuerst und klarer nächster Handlung.
- **Sanity-Check**: letzte Ampelprüfung vor Klage, Klageerwiderung, Replik, Termin, Vergleich oder Rechtsmittel.
- **Rechtsprechungschat**: Rechtsprechung finden, verstehen, nicht überdehnen und gerichtstauglich zitieren.
- **Zulassungsgrenzen-Check**: AG/LG-Zuständigkeit, § 23 GVG, § 495a ZPO, § 511 ZPO, Berufung und Anwaltszwang.
- **Zuständigkeit**: Sachlich (§ 23 GVG, § 23a-c GVG), örtlich (§§ 12 ff. ZPO), Verbrauchergerichtsstand (§ 29c ZPO).
- **Vor-Klage-Vorbereitung**: Erfolgsaussichten-Check, Anspruchsgrundlage finden, Verjährung prüfen, außergerichtliche Mahnung, Mahnverfahren, Beweismittel sammeln, Kostenrisiko berechnen.
- **Klageschrift erstellen**: Pflichtbestandteile, bestimmter Antrag, Tatsachenvortrag, Beweisangebote, Anlagen, Streitwert, vereinfachtes Verfahren § 495a ZPO.
- **Einreichung**: Mein Justizpostfach (MJP), § 130a ZPO elektronisch, Papierform, Fax-Grenzen, Rechtsantragsstelle, Versand durch Dritte (Risiko!), Gerichtskostenvorschuss.
- **PKH und Beratungshilfe**: Antrag, Ablehnung, Ratenzahlung, Beratungshilfe vor Klage.
- **Klageerwiderung**: Fristen, Checkliste, substantiiertes Bestreiten, Einreden, Widerklage, Säumnis vermeiden.
- **Replik, Duplik, Hinweise nach § 139 ZPO**, nachgereichter Schriftsatz, Wiedereinsetzung.
- **Beweis**: Beweislast, Zeuge, Urkunde, Sachverständiger, Augenschein, Parteivernehmung, eidesstattliche Versicherung, Folgen fehlenden Beweises.
- **Termin**: Ladung, Vorbereitung, Säumnis im Termin, Verhalten im Saal, Vergleich nach § 278 II ZPO.
- **Fristen**: Berechnung, eigenes Fristenbuch, Zustellung als Fristbeginn, Fristverlängerung.
- **Urteil und Rechtsmittel**: Verkündung, Urteilsprüfung, Berufung zum LG (Wertgrenze § 511 ZPO), Zulassung bei niedrigem Streitwert, Rechtsmittelfrist.
- **Vollstreckung-Querverweise**: Rechtskraft, Vollstreckungsklausel, Verweis auf separaten Substitutionsagenten für die Zwangsvollstreckung.
- **Spezielles**: Video-Verhandlung § 128a ZPO, Dolmetscher § 185 GVG, Kostenfestsetzung, typische Laien-Fehler, wann es sich lohnt, doch einen Anwalt einzuschalten.

## Sprache und Ton

- Sie-Form. Einfache, klare Sätze. Fachbegriffe werden beim ersten Vorkommen in einer Skill in 1-2 Sätzen erklärt.
- Direkte Schritt-fuer-Schritt-Anleitungen.
- Ehrlicher Hinweis, wo verifiziert werden muss (Reform-Lage, Aktenzeichen, Fundstellen).

## Was das Plugin **nicht** macht

- Keine Garantie, dass Sie gewinnen.
- Keine anwaltliche Mandatsführung. Bei komplexen Fällen, hohem Risiko, Landgericht, Familiengericht, Berufung oder unklarer Zustellung empfiehlt das Plugin deutlich Rechtsantragsstelle, Beratungshilfe, PKH oder Anwalt — siehe Skill `wann-doch-anwalt-grenzfaelle`.
- Keine Zwangsvollstreckung. Dafür existiert ein separater Substitutionsagent.

## Einstieg

Starten Sie mit `anfaenger-workflow-amtsgericht`, wenn Sie geführt werden möchten. Nutzen Sie `orientierung-selbstvertreter-amtsgericht`, wenn Sie nur eine schnelle Triage wollen, und `sanity-check-selbstvertretung-amtsgericht`, bevor etwas an das Gericht geht.

<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 30 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `allgemein` | Einstieg, Schnelltriage und Workflow-Routing im Selbstvertreter-Amtsgericht-Plugin. Fragt Erfahrungslevel, Rolle, Ziel, Fristen, Streitwert, Gericht, Unterlagen, Risiken und Wunsch-Output ab, schlägt passende Spezial-Skills aus diesem Pl... |
| `kompendium-01-anfaenger-workflow-a-bis-fristbeginn-zustellu` | selbstvertreter-amtsgericht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Anfaenger Workflow Amtsgericht, Rechtsprechungschat Amtsgericht, Fristbeginn Zustellung Protokollieren; mit Intake, Prüfroutine, Normen-/Quellenrada... |
| `kompendium-02-fristen-berechnen-18-bis-fristverlaengerung-a` | selbstvertreter-amtsgericht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Fristen Berechnen 187 188 Bgb, Fristen Buch Fuehren Laien, Fristverlaengerung Antrag 225 Zpo; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweisl... |
| `kompendium-03-klage-vereinfachtes-bis-mahnverfahren-688-ff` | selbstvertreter-amtsgericht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Klage Vereinfachtes Verfahren 495a Zpo, Klageerwiderung Fristen 274 Zpo, Mahnverfahren 688 Ff Zpo Vor Klage; mit Intake, Prüfroutine, Normen-/Quelle... |
| `kompendium-04-oertliche-zustaendig-bis-rechtsmittelfrist-51` | selbstvertreter-amtsgericht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Oertliche Zustaendigkeit 12 37 Zpo, Online Verfahren 11 Buch Zpo Experimentell, Rechtsmittelfrist 517 Zpo; mit Intake, Prüfroutine, Normen-/Quellenr... |
| `kompendium-05-sachliche-zustaendig-bis-wiedereinsetzung-fri` | selbstvertreter-amtsgericht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Sachliche Zustaendigkeit Amtsgericht 23 Gvg, Verjaehrungsfrist Pruefen 195 Bgb, Wiedereinsetzung Frist 233 Zpo; mit Intake, Prüfroutine, Normen-/Que... |
| `kompendium-06-vollstreckungsklause-bis-anlagen-formatieren` | selbstvertreter-amtsgericht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Vollstreckungsklausel 724 Zpo, Einreichung Papierform Mit Abschriften, Anlagen Formatieren K1 K2 Pdf Amtsgericht; mit Intake, Prüfroutine, Normen-/Q... |
| `kompendium-07-anspruchsgrundlage-f-bis-augenscheinsbeweis-3` | selbstvertreter-amtsgericht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Anspruchsgrundlage Finden Laienhilfe, Anwaltszwang Pruefen 78 Zpo, Augenscheinsbeweis 371 Zpo; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweis... |
| `kompendium-08-ausnahmen-streitwert-bis-beratungshilfe-ausse` | selbstvertreter-amtsgericht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Ausnahmen Streitwertgrenze 23 Nr 2 Gvg, Aussergerichtliche Mahnung 286 Bgb, Beratungshilfe Aussergerichtlich Brh; mit Intake, Prüfroutine, Normen-/Q... |
| `kompendium-09-berufung-amtsgericht-bis-beweislast-grundrege` | selbstvertreter-amtsgericht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Berufung Amtsgericht 511 Zpo, Berufungs Zulassung Niedrig Streitwert, Beweislast Grundregel Wer Was; mit Intake, Prüfroutine, Normen-/Quellenradar,... |
| `kompendium-10-beweismittel-vorab-s-bis-dolmetscher-185-gvg` | selbstvertreter-amtsgericht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Beweismittel Vorab Sammeln Checkliste, Dokumenten Erzeugung Pdf Laien Amtsgericht, Dolmetscher 185 Gvg; mit Intake, Prüfroutine, Normen-/Quellenrada... |
| `kompendium-11-duplik-nach-replik-bis-einreden-aktiv-gelte` | selbstvertreter-amtsgericht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Duplik Nach Replik, Eidesstattliche Versicherung 294 Zpo, Einreden Aktiv Geltend Machen; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik,... |
| `kompendium-12-einreichung-130a-zpo-bis-einreichung-mein-jus` | selbstvertreter-amtsgericht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Einreichung 130a Zpo Elektronisch Buerger, Einreichung Fax Und Grenzen, Einreichung Mein Justizpostfach Mjp 2024; mit Intake, Prüfroutine, Normen-/Q... |
| `kompendium-13-einreichung-rechtsan-bis-gerichtskostenvorsch` | selbstvertreter-amtsgericht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Einreichung Rechtsantragsstelle Selbst, Gegnerische Vollstreckung Abwehr, Gerichtskostenvorschuss 12 Gkg; mit Intake, Prüfroutine, Normen-/Quellenra... |
| `kompendium-14-kein-beweis-folgen-l-bis-klage-zusammenstelle` | selbstvertreter-amtsgericht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Kein Beweis Folgen Laienwarnung, Klage Streitwert Angabe 3 Zpo, Klage Zusammenstellen Komplettes Bundle Amtsgericht; mit Intake, Prüfroutine, Normen... |
| `kompendium-15-klageerwiderung-chec-bis-klageschrift-anlagen` | selbstvertreter-amtsgericht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Klageerwiderung Checkliste Alle Punkte, Klageerwiderung Replik Anlagen B1 B2 Fortlaufend, Klageschrift Anlagen Bezeichnen; mit Intake, Prüfroutine,... |
| `kompendium-16-klageschrift-anschre-bis-klageschrift-beweisa` | selbstvertreter-amtsgericht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Klageschrift Anschreiben An Gericht Laien, Klageschrift Antrag Bestimmt Formulieren, Klageschrift Beweisangebote Einbauen 373 Zpo; mit Intake, Prüfr... |
| `kompendium-17-klageschrift-pflicht-bis-kostenfestsetzung-10` | selbstvertreter-amtsgericht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Klageschrift Pflichtbestandteile 253 Zpo, Klageschrift Tatsachenvortrag Strukturieren, Kostenfestsetzung 103 104 Zpo; mit Intake, Prüfroutine, Norme... |
| `kompendium-18-kostenrisiko-streitw-bis-muendliche-verhandlu` | selbstvertreter-amtsgericht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Kostenrisiko Streitwert Berechnen Gkg, Ladung Termin 216 Zpo, Muendliche Verhandlung Akten Griffbereit; mit Intake, Prüfroutine, Normen-/Quellenrada... |
| `kompendium-19-nachgereichter-schri-bis-parteivernehmung-445` | selbstvertreter-amtsgericht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Nachgereichter Schriftsatz 296a Zpo, Orientierung Selbstvertreter Amtsgericht, Parteivernehmung 445 Ff Zpo; mit Intake, Prüfroutine, Normen-/Quellen... |
| `kompendium-20-pkh-bewilligung-able-bis-prozesskostenhilfe-p` | selbstvertreter-amtsgericht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Pkh Bewilligung Ablehnung Folgen, Pkh Ratenzahlung Bewilligung, Prozesskostenhilfe Pkh 114 Zpo; mit Intake, Prüfroutine, Normen-/Quellenradar, Bewei... |
| `kompendium-21-replik-auf-klageerwi-bis-sachverstaendigenbew` | selbstvertreter-amtsgericht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Replik Auf Klageerwiderung Systematik, Richterlicher Hinweis 139 Zpo Reaktion, Sachverstaendigenbeweis 402 Zpo; mit Intake, Prüfroutine, Normen-/Que... |
| `kompendium-22-saeumnis-im-termin-3-bis-sanity-check-selbstv` | selbstvertreter-amtsgericht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Saeumnis Im Termin 330 Zpo, Saeumnis Vermeiden 330 Ff Zpo, Sanity Check Selbstvertretung Amtsgericht; mit Intake, Prüfroutine, Normen-/Quellenradar,... |
| `kompendium-23-substantiiertes-best-bis-terminvorbereitung-c` | selbstvertreter-amtsgericht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Substantiiertes Bestreiten 138 Iv Zpo, Tatbestand Zerlegen Anspruchspruefung Laien, Terminvorbereitung Checkliste; mit Intake, Prüfroutine, Normen-/... |
| `kompendium-24-typische-laien-fehle-bis-urteil-pruefen-313-z` | selbstvertreter-amtsgericht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Typische Laien Fehler, Urkundenbeweis 415 Ff Zpo, Urteil Pruefen 313 Zpo; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster u... |
| `kompendium-25-urteil-rechtskraft-7-bis-verbrauchergerichtss` | selbstvertreter-amtsgericht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Urteil Rechtskraft 705 Zpo, Urteilsverkuendung 310 Zpo, Verbrauchergerichtsstand 29c Zpo; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik... |
| `kompendium-26-vergleich-richtervor-bis-video-verhandlung-12` | selbstvertreter-amtsgericht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Vergleich Richtervorschlag 278 Ii Zpo, Verhalten Gerichtssaal Laienleitfaden, Video Verhandlung 128a Zpo; mit Intake, Prüfroutine, Normen-/Quellenra... |
| `kompendium-27-vorabklaerung-erfolg-bis-widerklage-33-zpo` | selbstvertreter-amtsgericht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Vorabklaerung Erfolgsaussichten Selbstcheck, Wann Doch Anwalt Grenzfaelle, Widerklage 33 Zpo; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweisl... |
| `kompendium-28-zeugenbeweis-373-ff-bis-zurechnungsproblem-v` | selbstvertreter-amtsgericht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Zeugenbeweis 373 Ff Zpo, Zulassungsgrenzen Check Amtsgericht, Zurechnungsproblem Versand Durch Dritte; mit Intake, Prüfroutine, Normen-/Quellenradar... |
| `kompendium-29-zwangsvollstreckung-bis-zwangsvollstreckung` | selbstvertreter-amtsgericht: eigenständiger Arbeits-Skill zu Zwangsvollstreckung Querverweis Substitutionsagent; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
