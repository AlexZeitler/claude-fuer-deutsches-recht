# NDA-Abgleich

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`nda-abgleich`) | [`nda-abgleich.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/nda-abgleich.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **Akte Waldkrone HealthTech GmbH - NDA, Meldekanal und Lieferantenhinweis** (`hinweisgeberschutz-nda-meldekanal-waldkrone`) | [Gesamt-PDF lesen](../testakten/hinweisgeberschutz-nda-meldekanal-waldkrone/gesamt-pdf/hinweisgeberschutz-nda-meldekanal-waldkrone_gesamt.pdf) | [`testakte-hinweisgeberschutz-nda-meldekanal-waldkrone.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-hinweisgeberschutz-nda-meldekanal-waldkrone.zip) |
| **NDA-Vertragsabgleich Windsysteme Norderhof AG / Eickmann Wirtschaftspartner Pte. Ltd. — Joint Venture, GeschGehG, Exportkontrolle** (`nda-vertragsabgleich-jointventure-windsysteme-eickmann-wirtschaft`) | [Gesamt-PDF lesen](../testakten/nda-vertragsabgleich-jointventure-windsysteme-eickmann-wirtschaft/gesamt-pdf/nda-vertragsabgleich-jointventure-windsysteme-eickmann-wirtschaft_gesamt.pdf) | [`testakte-nda-vertragsabgleich-jointventure-windsysteme-eickmann-wirtschaft.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-nda-vertragsabgleich-jointventure-windsysteme-eickmann-wirtschaft.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

NDA-Verhandlungshilfe für die empfangende Seite. Akzeptiert den Entwurf der Gegenseite und setzt den eigenen Standard chirurgisch durch. Ampelmatrix ROT/GELB/GRUEN. Ausgabe .docx mit echten Word-Tracked-Changes. Keine Absatzlöschungen, keine Klausel-Neufassungen.

## Installation in Claude Code

1. ZIP herunterladen (Link oben).
2. Claude Code → **Customize Plugins** → **Install from .zip** → Datei wählen.
3. Fertig. Skills sind sofort verfügbar.

> **Hinweis:** Für den ZIP-Upload muss das Archiv direkt `.claude-plugin/plugin.json`, `skills/`, `assets/` und `references/` im ZIP-Root enthalten. **Nicht** das komplette Repository-ZIP aus "Code → Download ZIP" verwenden.

## Enthaltene Skills

| Skill | Zweck |
| --- | --- |
| `nda-abgleich` | NDA-Verhandlungshilfe für die empfangende Seite. Zwei Modi: (A) Standard-Destillation aus 1 bis n eigenen NDAs und frei beschreibbarer Erfahrung in einen konsolidierten Haltelinien-Standard mit Ampelmatrix ROT/GELB/G… |

## Lizenz

Apache-2.0 OR MIT — Auswahl beim Empfänger.

## Quellen-Disclaimer

Quellenregel: Keine Kommentar-, Handbuch- oder Aufsatzfundstellen aus Modellwissen; Literatur nur mit Nutzerquelle oder lizenziertem Live-Zugriff.


<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 70 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `aenderungsmodus` | Nutze dies, wenn Aenderungsmodus: Compliance-Dokumentation und Aktenvermerk im Plugin Nda Abgleich konkret bearbeitet werden soll. Auslöser: Ich lade Unterlagen hoch.; Was fehlt noch?; Bitte Dokumente sortieren.. |
| `allgemein` | Einstieg, Schnelltriage und Workflow-Routing im NDA Abgleich-Plugin. Fragt Rolle, Ziel, Fristen, Unterlagen, Risiken und Wunsch-Output ab, schlägt passende Spezial-Skills aus diesem Plugin vor und führt in einen klaren Arbeitsplan. Bei D... |
| `allgemein-workflow-chronologie-fristen` | Nutze dies, wenn Allgemein, Workflow Chronologie Und Belegmatrix, Workflow Fristen Und Risikoampel im Plugin Nda Abgleich konkret bearbeitet werden soll. Auslöser: Bitte Allgemein, Workflow Chronologie Und Belegmatrix, Workflow Fristen U... |
| `ampelmatrix` | Nutze dies, wenn Ampelmatrix: Internationaler Bezug und Schnittstellen im Plugin Nda Abgleich konkret bearbeitet werden soll. Auslöser: Bitte Ampelmatrix: Internationaler Bezug und Schnittstellen prüfen.; Erstelle eine Arbeitsfassung zu... |
| `anschluss-routing` | Nutze dies, wenn Anschluss-Routing im Plugin Nda Abgleich konkret bearbeitet werden soll. Auslöser: Ich habe ein neues Thema im Bereich Nda Abgleich.; Welche Unterlagen brauchen Sie?; Welcher Spezialskill passt?. |
| `ausgabe` | Nutze dies, wenn Ausgabe: Mandantenkommunikation und Entscheidungsvorlage im Plugin Nda Abgleich konkret bearbeitet werden soll. Auslöser: Bitte Ausgabe: Mandantenkommunikation und Entscheidungsvorlage prüfen.; Erstelle eine Arbeitsfassu... |
| `ausgabe-changes-docx-beweislast` | Nutze dies, wenn Spezial Ausgabe Mandantenkommunikation Entscheidungsvorlage, Spezial Changes Abschlussprodukt Und Übergabe, Spezial Docx Beweislast Und Darlegungslast im Plugin Nda Abgleich konkret bearbeitet werden soll. Auslöser: Bitt... |
| `changes` | Nutze dies, wenn Changes: Abschlussprodukt und Übergabe im Plugin Nda Abgleich konkret bearbeitet werden soll. Auslöser: Bitte Changes: Abschlussprodukt und Übergabe prüfen.; Erstelle eine Arbeitsfassung zu Changes: Abschlussprodukt und... |
| `chirurgisch-quellenkarte` | Nutze dies, wenn Chirurgisch Quellenkarte im Plugin Nda Abgleich konkret bearbeitet werden soll. Auslöser: Welche amtliche Quelle prüfe ich zuerst?; Gibt es aktuelle Rechtsprechung?; Bitte Fundstellen verifizieren.. |
| `chronologie-und-belegmatrix` | Nutze dies, wenn Chronologie und Belegmatrix im Plugin Nda Abgleich konkret bearbeitet werden soll. Auslöser: Bitte Chronologie und Belegmatrix prüfen.; Erstelle eine Arbeitsfassung zu Chronologie und Belegmatrix.; Welche Normen und Nach... |
| `docx-beweislast-darlegungslast` | Nutze dies, wenn Docx: Beweislast, Darlegungslast und Substantiierung im Plugin Nda Abgleich konkret bearbeitet werden soll. Auslöser: Bitte Docx: Beweislast, Darlegungslast und Substantiierung prüfen.; Erstelle eine Arbeitsfassung zu Do... |
| `dokumente-intake` | Nutze dies, wenn Dokumentenintake im Plugin Nda Abgleich konkret bearbeitet werden soll. Auslöser: Ich lade Unterlagen hoch.; Was fehlt noch?; Bitte Dokumente sortieren.. |
| `durch-interessen` | Nutze dies, wenn Durch: Mehrparteienkonflikt und Interessenmatrix im Plugin Nda Abgleich konkret bearbeitet werden soll. Auslöser: Bitte Durch: Mehrparteienkonflikt und Interessenmatrix prüfen.; Erstelle eine Arbeitsfassung zu Durch: Meh... |
| `durch-interessen-echten-sonderfall-eigenen` | Nutze dies, wenn Spezial Durch Mehrparteien Konflikt Und Interessen, Spezial Echten Sonderfall Und Edge Case, Spezial Eigenen Risikoampel Und Gegenargumente im Plugin Nda Abgleich konkret bearbeitet werden soll. Auslöser: Bitte Spezial D... |
| `echten-sonderfall-edge-case` | Nutze dies, wenn Echten: Sonderfall und Edge-Case-Prüfung im Plugin Nda Abgleich konkret bearbeitet werden soll. Auslöser: Bitte Echten: Sonderfall und Edge-Case-Prüfung prüfen.; Erstelle eine Arbeitsfassung zu Echten: Sonderfall und Edg... |
| `eigenen` | Nutze dies, wenn Eigenen: Risikoampel, Gegenargumente und Verteidigungslinien im Plugin Nda Abgleich konkret bearbeitet werden soll. Auslöser: Bitte Eigenen: Risikoampel, Gegenargumente und Verteidigungslinien prüfen.; Erstelle eine Arbe... |
| `einstieg-routing` | Nutze dies, wenn Einstieg und Routing im Plugin Nda Abgleich konkret bearbeitet werden soll. Auslöser: Ich habe ein neues Thema im Bereich Nda Abgleich.; Welche Unterlagen brauchen Sie?; Welcher Spezialskill passt?. |
| `entwurf` | Nutze dies, wenn Entwurf: Tatbestandsmerkmale, Beweisfragen und Beleglage im Plugin Nda Abgleich konkret bearbeitet werden soll. Auslöser: Bitte Entwurf: Tatbestandsmerkmale, Beweisfragen und Beleglage prüfen.; Erstelle eine Arbeitsfassu... |
| `fristen-und-risikoampel` | Nutze dies, wenn Fristen- und Risikoampel im Plugin Nda Abgleich konkret bearbeitet werden soll. Auslöser: Bitte Fristen- und Risikoampel prüfen.; Erstelle eine Arbeitsfassung zu Fristen- und Risikoampel.; Welche Normen und Nachweise bra... |
| `gegen-dokumentenmatrix-und-lueckenliste` | Nutze dies, wenn Gegen: Dokumentenmatrix, Lückenliste und Nachforderung im Plugin Nda Abgleich konkret bearbeitet werden soll. Auslöser: Ich lade Unterlagen hoch.; Was fehlt noch?; Bitte Dokumente sortieren.. |
| `gegen-gelb-gleicht` | Nutze dies, wenn Spezial Gegen Dokumentenmatrix Und Lueckenliste, Spezial Gelb Formular Portal Und Einreichung, Spezial Gleicht Erstpruefung Und Mandatsziel im Plugin Nda Abgleich konkret bearbeitet werden soll. Auslöser: Bitte Spezial G... |
| `gegenseite` | Nutze dies, wenn Gegenseite: Fristen, Form, Zuständigkeit und Rechtsweg im Plugin Nda Abgleich konkret bearbeitet werden soll. Auslöser: Bitte Gegenseite: Fristen, Form, Zuständigkeit und Rechtsweg prüfen.; Erstelle eine Arbeitsfassung z... |
| `gegenseite-tracked-fristennotiz-nda` | Nutze dies, wenn Spezial Gegenseite Fristen Form Und Zustaendigkeit, Spezial Tracked Fristennotiz Und Naechster Schritt, Nda Definitionsklausel Abgleichen im Plugin Nda Abgleich konkret bearbeitet werden soll. Auslöser: Bitte Spezial Geg... |
| `gelb` | Nutze dies, wenn Gelb: Formular, Portal und Einreichungslogik im Plugin Nda Abgleich konkret bearbeitet werden soll. Auslöser: Bitte Gelb: Formular, Portal und Einreichungslogik prüfen.; Erstelle eine Arbeitsfassung zu Gelb: Formular, Po... |
| `geschaeftsgeheimnis-geschgehg` | Nutze dies, wenn Nda Mit Geschaeftsgeheimnis Geschgehg, Nda Mit Kartellsensitiven Daten, Nda Mit Personenbezogenen Daten im Plugin Nda Abgleich konkret bearbeitet werden soll. Auslöser: Bitte Nda Mit Geschaeftsgeheimnis Geschgehg, Nda Mi... |
| `gleicht` | Nutze dies, wenn Gleicht: Erstprüfung, Rollenklärung und Mandatsziel im Plugin Nda Abgleich konkret bearbeitet werden soll. Auslöser: Bitte Gleicht: Erstprüfung, Rollenklärung und Mandatsziel prüfen.; Erstelle eine Arbeitsfassung zu Glei... |
| `gruen-fehlerkatalog` | Nutze dies, wenn Gruen Fehlerkatalog im Plugin Nda Abgleich konkret bearbeitet werden soll. Auslöser: Was kann hier schiefgehen?; Bitte red-team prüfen.; Welche Frist oder Beweislast übersehe ich?. |
| `haltelinien` | Nutze dies, wenn Haltelinien: Verhandlung, Vergleich und Eskalation im Plugin Nda Abgleich konkret bearbeitet werden soll. Auslöser: Bitte Haltelinien: Verhandlung, Vergleich und Eskalation prüfen.; Erstelle eine Arbeitsfassung zu Haltel... |
| `haltelinien-setzt-standard` | Nutze dies, wenn Spezial Haltelinien Verhandlung Vergleich Und Eskalation, Spezial Setzt Schriftsatz Brief Und Memo Bausteine, Spezial Standard Behörden Gericht Und Registerweg im Plugin Nda Abgleich konkret bearbeitet werden soll. Auslö... |
| `it-saas-laufzeit-survival-m-a` | Nutze dies, wenn Nda It Saas Vendor, Nda Laufzeit Und Survival, Nda M Und A Clean Team Spezial im Plugin Nda Abgleich konkret bearbeitet werden soll. Auslöser: Bitte Nda It Saas Vendor, Nda Laufzeit Und Survival, Nda M Und A Clean Team S... |
| `m-a-aenderungsmodus-ampelmatrix` | Nutze dies, wenn Nda Vor M A Data Room, Spezial Aenderungsmodus Compliance Dokumentation Und Akte, Spezial Ampelmatrix Internationaler Bezug Und Schnittstellen im Plugin Nda Abgleich konkret bearbeitet werden soll. Auslöser: Bitte Nda Vo... |
| `mandantenkommunikation` | Nutze dies, wenn Mandantenkommunikation im Plugin Nda Abgleich konkret bearbeitet werden soll. Auslöser: Bitte Mandantenkommunikation prüfen.; Erstelle eine Arbeitsfassung zu Mandantenkommunikation.; Welche Normen und Nachweise brauche i... |
| `mitarbeiter-need-non-solicit-permitted` | Nutze dies, wenn Nda Mitarbeiter Need To Know, Nda Non Solicit Kartellrechtlich, Nda Permitted Disclosure im Plugin Nda Abgleich konkret bearbeitet werden soll. Auslöser: Bitte Nda Mitarbeiter Need To Know, Nda Non Solicit Kartellrechtli... |
| `nda` | Nutze dies, wenn Workflow Mandantenkommunikation, Workflow Redteam Qualitygate, Nda Anwendbares Recht Gerichtsstand im Plugin Nda Abgleich konkret bearbeitet werden soll. Auslöser: Was kann hier schiefgehen?; Bitte red-team prüfen.; Welc... |
| `nda-abgleich` | Empfangende Seite soll NDA der Gegenseite prüfen und verhandeln oder Kanzlei will aus mehreren NDAs einen eigenen Standard destillieren. NDA-Verhandlungshilfe. Modus A Destillation: 1 bis n eigene NDAs in konsolidierten Haltelinien-Stand... |
| `nda-abgleich-arbeitnehmer-kuendigung` | Nutze dies, wenn Nda Abgleich, Nda Bei Arbeitnehmer Kündigung, Nda Bei Bewerbungen Pitches im Plugin Nda Abgleich konkret bearbeitet werden soll. Auslöser: Bitte Nda Abgleich, Nda Bei Arbeitnehmer Kündigung, Nda Bei Bewerbungen Pitches p... |
| `nda-anwendbares-recht-gerichtsstand` | Anwendbares Recht und Gerichtsstand bei NDA: Empfehlung deutsches Recht + LG Sitz des Discloser; Schiedsklausel (DIS Regeln) ab hoeherer Bedeutung. Pruefraster: internationale NDAs vs. nationale, Verbraucherbeteiligung. |
| `nda-bei-arbeitnehmer-kuendigung` | Post-Termination-NDA bei Arbeitnehmer-Kuendigung: Wirksamkeit, Karenzentschaedigung § 74 HGB analog, Reichweite (keine generelle Wettbewerbssperre). Schnittstelle Arbeitsrecht. Empfehlung: nur ergaenzend zu nachvertraglichem Wettbewerbsv... |
| `nda-bei-bewerbungen-pitches` | NDA bei Bewerbungen/Pitches/Investorengespraechen: Investor-NDAs sind ungewoehnlich; ueblich nur enge Mutual-NDAs fuer fortgeschrittene Stage. Empfehlung: nicht beleidigt sein, wenn VC unterschreibt nicht; Verhandlungsstrategie. |
| `nda-bei-r-d-kooperation` | NDA bei F&E-Kooperation: Background-IP / Foreground-IP-Trennung, IP-Zuordnung bei gemeinsamer Erfindung, Foerderrechtshinweise (BMBF/EU). Empfehlung: NDA + Pre-LoI mit IP-Grundsaetzen. |
| `nda-definitionsklausel-abgleichen` | Definitionsklausel 'Vertrauliche Information' abgleichen: weiter Begriff (alle Informationen) vs. eng definiert (nur als vertraulich markiert). Empfehlung je nach Rolle: Discloser will weit, Recipient will eng. Wortlautempfehlungen. |
| `nda-grundstruktur-pruefen` | NDA-Grundstruktur pruefen: Parteien, Zweck der Offenlegung, Definition Vertrauliche Information, Pflichten, Laufzeit, Aufbewahrung/Rueckgabe, Vertragsstrafe, Geheimhaltungsdauer nach Vertragsende, Jurisdiction. Pruefraster gegen marktueb... |
| `nda-international-arbitration-spezial` | Spezialfall internationale NDAs und Schiedsklauseln: Rechtswahl, Schiedsort, einstweiliger Rechtsschutz, Common-Law-Begriffe Equity. Pruefraster fuer Cross-Border-Mandat. |
| `nda-it-saas-vendor` | NDA fuer SaaS-/IT-Vendor-Pitches: Cloud-Hosting, Datentrennung, Subprozessoren, Audit-Rechte, Penetration-Testing-Erlaubnis. Empfehlung: nicht-exklusive Lizenz fuer Test-Daten, klare Loeschpflicht nach Pitch. |
| `nda-laufzeit-und-survival` | Laufzeit und Survival der Geheimhaltungspflicht: Festlaufzeit, automatische Verlaengerung, Survival 2/3/5 Jahre nach Vertragsende. Bei Geschaeftsgeheimnissen i. S. GeschGehG ist Survival 'so lange die Information Geschaeftsgeheimnis ist'... |
| `nda-m-und-a-clean-team-spezial` | Spezialfall NDA fuer M-and-A und Clean-Team-Arrangements: Datenraum, Sondervertraulichkeit Wettbewerbsdaten, Kartellrecht. Pruefraster fuer Antitrust-Counsel. |
| `nda-mit-geschaeftsgeheimnis-geschgehg` | NDA als angemessene Geheimhaltungsmassnahme i. S. § 2 Nr. 1 b GeschGehG: NDA allein reicht nicht, technisch-organisatorische Massnahmen erforderlich (Zugangsschutz, Klassifizierung, Logging). Pruefraster. |
| `nda-mit-kartellsensitiven-daten` | NDA mit kartellsensitiven Daten (Preise, Mengen, Kunden): Clean Team Agreement, Aggregation, externe Berater zwischen den Parteien. Empfehlung: Vorabklaerung ob Daten ueberhaupt ausgetauscht werden duerfen. |
| `nda-mit-personenbezogenen-daten` | NDA mit personenbezogenen Daten: ggf. AV-Vertrag § 28 BDSG / Art. 28 DSGVO erforderlich, gemeinsame Verantwortlichkeit Art. 26 DSGVO pruefen. NDA ersetzt AV nicht. Empfehlung: separater AVV anlagengeb. |
| `nda-mitarbeiter-need-to-know` | Mitarbeiter und Need-to-Know: NDA verpflichtet Mitarbeiter ueber Arbeitsvertrag, externe Berater nur ueber separate NDA oder Backup-Klausel. Empfehlung: Liste freigegebener Personen, Bestaetigung Mitarbeiter-NDA, kein Datenraum-Zugriff o... |
| `nda-non-solicit-kartellrechtlich` | Non-Solicit in NDA kartellrechtlich pruefen: zeitlich begrenzt (12-24 Monate), sachlich begrenzt (nur fuer NDA-Zweck involvierte Mitarbeiter), keine generelle Bewerbungs-Sperre. Andernfalls Risiko § 1 GWB / Art. 101 AEUV. |
| `nda-permitted-disclosure` | Permitted Disclosure: Konzern, Beraterklausel, gesetzliche Offenlegungspflichten (Aufsicht, Strafverfolgung, Gericht). Standard-Wortlaut und typische Fallstricke (z. B. Konzernbegriff zu eng). |
| `nda-rueckgabe-vernichtung` | Rueckgabe und Vernichtung Vertraulicher Information: Pflicht, Bestaetigung, Backup-Ausnahme (technisch unmoeglich zu loeschende Backups). Bei Daten in Cloud: Loeschbestaetigung Vendor erforderlich. Wortlautempfehlungen. |
| `nda-standardklauseln-bauleiter` | Bauleiter NDA-Standardklauseln: Vertraulichkeitsumfang, Empfaengerkreis, Laufzeit, Rechtsfolgen, Schriftform. Pruefraster fuer mutual und one-way NDA. |
| `nda-typen-vergleich` | NDA-Typen vergleichen: einseitig (unilateral), gegenseitig (mutual), mehrparteiig. Empfehlung pro Situation: Verkaeufer in M&A unilateral; gemeinsame Entwicklung mutual; Konsortium mehrparteiig. Praxisanker fuer Templates. |
| `nda-vergleichsmatrix-leitfaden` | Leitfaden NDA-Vergleichsmatrix: relevante Klauseln vergleichen, Markup, Risikoampel, Wechselwirkungen mit Geschaeftsgeheimnisgesetz. Pruefraster fuer Reviewteam. |
| `nda-vertragsstrafe-pruefen` | Vertragsstrafe pruefen: Hoehe, AGB-Kontrolle §§ 305 ff. BGB, Bestimmtheitsgrundsatz, Schadensersatzkumulation oder Anrechnung. Bei Verbraucher-NDA strengere Grenzen. Bei B2B-Standard: ueblich 5000-25000 EUR pro Vorfall, Kumulation moeglich. |
| `nda-vor-m-a-data-room` | NDA vor M&A-Data-Room: enge Zweckbindung (Pruefung Transaktion), Standstill-Klausel, Non-Solicit, Verbot Reverse-Engineering. Empfehlung: separater Clean Team Agreement fuer Kartell-/Wettbewerbsdaten. |
| `output-waehlen` | Nutze dies, wenn Output wählen im Plugin Nda Abgleich konkret bearbeitet werden soll. Auslöser: Bitte Output wählen prüfen.; Erstelle eine Arbeitsfassung zu Output wählen.; Welche Normen und Nachweise brauche ich?. |
| `quellen-livecheck` | Nutze dies, wenn Rechtsquellen-Livecheck im Plugin Nda Abgleich konkret bearbeitet werden soll. Auslöser: Welche amtliche Quelle prüfe ich zuerst?; Gibt es aktuelle Rechtsprechung?; Bitte Fundstellen verifizieren.. |
| `r-d-nda-grundstruktur-international` | Nutze dies, wenn Nda Bei R D Kooperation, Nda Grundstruktur Prüfen, Nda International Arbitration Spezial im Plugin Nda Abgleich konkret bearbeitet werden soll. Auslöser: Bitte Nda Bei R D Kooperation, Nda Grundstruktur Prüfen, Nda Inter... |
| `redteam-qualitygate` | Nutze dies, wenn Red-Team Qualitygate im Plugin Nda Abgleich konkret bearbeitet werden soll. Auslöser: Was kann hier schiefgehen?; Bitte red-team prüfen.; Welche Frist oder Beweislast übersehe ich?. |
| `rueckgabe-vernichtung-nda-typen` | Nutze dies, wenn Nda Rueckgabe Vernichtung, Nda Typen Vergleich, Nda Vergleichsmatrix Leitfaden im Plugin Nda Abgleich konkret bearbeitet werden soll. Auslöser: Bitte Nda Rueckgabe Vernichtung, Nda Typen Vergleich, Nda Vergleichsmatrix L... |
| `setzt` | Nutze dies, wenn Setzt: Schriftsatz-, Brief- und Memo-Bausteine im Plugin Nda Abgleich konkret bearbeitet werden soll. Auslöser: Bitte Setzt: Schriftsatz-, Brief- und Memo-Bausteine prüfen.; Erstelle eine Arbeitsfassung zu Setzt: Schrift... |
| `standard` | Nutze dies, wenn Standard: Behörden-, Gerichts- oder Registerweg im Plugin Nda Abgleich konkret bearbeitet werden soll. Auslöser: Bitte Standard: Behörden-, Gerichts- oder Registerweg prüfen.; Erstelle eine Arbeitsfassung zu Standard: Be... |
| `standardklauseln-bauleiter-nda-vertragsstrafe` | Nutze dies, wenn Nda Standardklauseln Bauleiter, Nda Vertragsstrafe Prüfen, Spezial Entwurf Tatbestand Beweis Und Belege im Plugin Nda Abgleich konkret bearbeitet werden soll. Auslöser: Bitte Nda Standardklauseln Bauleiter, Nda Vertragss... |
| `tracked-fristennotiz-naechster-schritt` | Nutze dies, wenn Tracked: Fristennotiz und nächster Schritt im Plugin Nda Abgleich konkret bearbeitet werden soll. Auslöser: Bitte Tracked: Fristennotiz und nächster Schritt prüfen.; Erstelle eine Arbeitsfassung zu Tracked: Fristennotiz... |
| `unterlagen-luecken` | Nutze dies, wenn Unterlagen und Lücken im Plugin Nda Abgleich konkret bearbeitet werden soll. Auslöser: Ich lade Unterlagen hoch.; Was fehlt noch?; Bitte Dokumente sortieren.. |
| `word` | Nutze dies, wenn Spezial Word Zahlen Schwellen Und Berechnung im Plugin Nda Abgleich konkret bearbeitet werden soll. Auslöser: Bitte Spezial Word Zahlen Schwellen Und Berechnung prüfen.; Erstelle eine Arbeitsfassung zu Spezial Word Zahle... |
| `word-02` | Nutze dies, wenn Word: Zahlen, Schwellenwerte und Berechnung im Plugin Nda Abgleich konkret bearbeitet werden soll. Auslöser: Bitte Word: Zahlen, Schwellenwerte und Berechnung prüfen.; Erstelle eine Arbeitsfassung zu Word: Zahlen, Schwel... |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
