# Zitierweise deutsches Recht (v4.1)

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`zitierweise-deutsches-recht`) | [`zitierweise-deutsches-recht.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/zitierweise-deutsches-recht.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **Dr. Ottilie Mondsee und die verschwundene R-Besoldung** (`beamtenrecht-richterlaufbahn-besoldung-mondsee`) | [Gesamt-PDF lesen](../testakten/beamtenrecht-richterlaufbahn-besoldung-mondsee/gesamt-pdf/beamtenrecht-richterlaufbahn-besoldung-mondsee_gesamt.pdf) | [`testakte-beamtenrecht-richterlaufbahn-besoldung-mondsee.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-beamtenrecht-richterlaufbahn-besoldung-mondsee.zip) |
| **Zitierweise-Pruefkorpus — Kanzlei Roosendaal Birkenhainer Partners mbB — Kanzleihandbuch v4 mit 100 Fundstellen und Pruefvermerken** (`zitierweise-pruefkorpus-roosendaal-kanzleihandbuch-mit-100-fundstellen-und-pruefvermerken`) | [Gesamt-PDF lesen](../testakten/zitierweise-pruefkorpus-roosendaal-kanzleihandbuch-mit-100-fundstellen-und-pruefvermerken/gesamt-pdf/zitierweise-pruefkorpus-roosendaal-kanzleihandbuch-mit-100-fundstellen-und-pruefvermerken_gesamt.pdf) | [`testakte-zitierweise-pruefkorpus-roosendaal-kanzleihandbuch-mit-100-fundstellen-und-pruefvermerken.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-zitierweise-pruefkorpus-roosendaal-kanzleihandbuch-mit-100-fundstellen-und-pruefvermerken.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

Deutsche juristische Hauszitierweise als zuschaltbares Plugin. Fokus: belastbare, überprüfbare Quellen statt schöner, aber nicht verifizierbarer Fundstellen.

## Was ist neu in v4.1

1. **BeckRS-Sperre:** BeckRS-Fundstellen werden nicht mehr aus Modellwissen erzeugt. Sie dürfen nur übernommen werden, wenn der Nutzer sie liefert oder ein lizenzierter Live-Zugriff sie verifiziert.
2. **Literatur-Sperre:** Kommentare, Handbücher, Monographien und Aufsätze werden nicht blind zitiert. Literatur nur mit Nutzerquelle oder lizenziertem Live-Zugriff.
3. **Rechtsprechungs-Mindeststandard:** Gericht, Entscheidungsform, Datum und Aktenzeichen sind Pflicht. Wo möglich kommt eine amtliche oder frei zugängliche Quelle dazu.
4. **Keine Palandt-/Pahlen-Aktualzitate:** Der frühere Palandt heißt seit 2022 Grüneberg; historische Altauflagen nur bei konkreter Nutzerquelle.
5. **Prüfvermerk statt Halluzination:** Unverifizierte Entscheidungen werden markiert oder weggelassen, nicht ausgeschmückt.

## Installation in Claude Code

1. ZIP herunterladen.
2. Claude Code → **Customize Plugins** → **Install from .zip** → Datei wählen.
3. Fertig. Skills sind sofort verfügbar.

Für den ZIP-Upload muss das Archiv direkt `.claude-plugin/plugin.json`, `skills/` und `references/` im ZIP-Root enthalten. Nicht das komplette Repository-ZIP aus "Code → Download ZIP" verwenden.

## Enthaltene Skills

| Skill | Zweck |
| --- | --- |
| `allgemein` | Einstieg, Schnelltriage und Routing: klärt, ob ein Text Zitate erzeugen, glätten, prüfen oder sperren soll. |
| `zitierweise-anwenden` | Wendet die Quellenregel v4.1 an: Rechtsprechung nur mit Datum, Aktenzeichen und verifizierbarer Quelle; keine BeckRS-, Kommentar- oder Aufsatz-Blindzitate. |

## Kurzregel

Norm zuerst. Dann verifizierte Rechtsprechung. Literatur nur bei bereitgestellter oder live verifizierter Quelle. Keine BeckRS-, Kommentar- oder Aufsatz-Blindzitate.

## Lizenz

Apache-2.0 OR MIT — Auswahl beim Empfänger.


<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 70 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `aktenzeichen` | Nutze dies, wenn Aktenzeichen: Schriftsatz-, Brief- und Memo-Bausteine im Plugin Zitierweise Deutsches Recht konkret bearbeitet werden soll. Auslöser: Bitte Aktenzeichen: Schriftsatz-, Brief- und Memo-Bausteine prüfen.; Erstelle eine Arb... |
| `allgemein` | Einstieg, Schnelltriage und Workflow-Routing im Zitierweise Deutsches Recht-Plugin. Setzt v4.1 durch: Rechtsprechung nur mit Datum, Aktenzeichen und verifizierbarer Quelle; keine BeckRS-, Kommentar- oder Aufsatz-Blindzitate. Fragt Ziel,... |
| `allgemein-workflow-chronologie-fristen` | Nutze dies, wenn Allgemein, Workflow Chronologie Und Belegmatrix, Workflow Fristen Und Risikoampel im Plugin Zitierweise Deutsches Recht konkret bearbeitet werden soll. Auslöser: Bitte Allgemein, Workflow Chronologie Und Belegmatrix, Wor... |
| `anschluss-routing` | Nutze dies, wenn Anschluss-Routing im Plugin Zitierweise Deutsches Recht konkret bearbeitet werden soll. Auslöser: Ich habe ein neues Thema im Bereich Zitierweise Deutsches Recht.; Welche Unterlagen brauchen Sie?; Welcher Spezialskill pa... |
| `aufsatz-interessen` | Nutze dies, wenn Aufsatz: Mehrparteienkonflikt und Interessenmatrix im Plugin Zitierweise Deutsches Recht konkret bearbeitet werden soll. Auslöser: Bitte Aufsatz: Mehrparteienkonflikt und Interessenmatrix prüfen.; Erstelle eine Arbeitsfa... |
| `aufsatz-interessen-beckrs-blindzitate` | Nutze dies, wenn Spezial Aufsatz Mehrparteien Konflikt Und Interessen, Spezial Beckrs Zahlen Schwellen Und Berechnung, Spezial Blindzitate Internationaler Bezug Und Schnittstellen im Plugin Zitierweise Deutsches Recht konkret bearbeitet... |
| `beckrs` | Nutze dies, wenn Beckrs: Zahlen, Schwellenwerte und Berechnung im Plugin Zitierweise Deutsches Recht konkret bearbeitet werden soll. Auslöser: Bitte Beckrs: Zahlen, Schwellenwerte und Berechnung prüfen.; Erstelle eine Arbeitsfassung zu B... |
| `blindzitate` | Nutze dies, wenn Blindzitate: Internationaler Bezug und Schnittstellen im Plugin Zitierweise Deutsches Recht konkret bearbeitet werden soll. Auslöser: Bitte Blindzitate: Internationaler Bezug und Schnittstellen prüfen.; Erstelle eine Arb... |
| `chronologie-und-belegmatrix` | Nutze dies, wenn Chronologie und Belegmatrix im Plugin Zitierweise Deutsches Recht konkret bearbeitet werden soll. Auslöser: Bitte Chronologie und Belegmatrix prüfen.; Erstelle eine Arbeitsfassung zu Chronologie und Belegmatrix.; Welche... |
| `datum` | Nutze dies, wenn Datum: Behörden-, Gerichts- oder Registerweg im Plugin Zitierweise Deutsches Recht konkret bearbeitet werden soll. Auslöser: Bitte Datum: Behörden-, Gerichts- oder Registerweg prüfen.; Erstelle eine Arbeitsfassung zu Dat... |
| `datum-entscheidungsform-spezial-gericht` | Nutze dies, wenn Spezial Datum Behörden Gericht Und Registerweg, Spezial Entscheidungsform Risikoampel Und Gegenargumente, Spezial Gericht Dokumentenmatrix Und Lueckenliste im Plugin Zitierweise Deutsches Recht konkret bearbeitet werden... |
| `dokumente-intake` | Nutze dies, wenn Dokumentenintake im Plugin Zitierweise Deutsches Recht konkret bearbeitet werden soll. Auslöser: Ich lade Unterlagen hoch.; Was fehlt noch?; Bitte Dokumente sortieren.. |
| `einstieg-routing` | Nutze dies, wenn Einstieg und Routing im Plugin Zitierweise Deutsches Recht konkret bearbeitet werden soll. Auslöser: Ich habe ein neues Thema im Bereich Zitierweise Deutsches Recht.; Welche Unterlagen brauchen Sie?; Welcher Spezialskill... |
| `entscheidungsform` | Nutze dies, wenn Entscheidungsform: Risikoampel, Gegenargumente und Verteidigungslinien im Plugin Zitierweise Deutsches Recht konkret bearbeitet werden soll. Auslöser: Bitte Entscheidungsform: Risikoampel, Gegenargumente und Verteidigung... |
| `fristen-und-risikoampel` | Nutze dies, wenn Fristen- und Risikoampel im Plugin Zitierweise Deutsches Recht konkret bearbeitet werden soll. Auslöser: Bitte Fristen- und Risikoampel prüfen.; Erstelle eine Arbeitsfassung zu Fristen- und Risikoampel.; Welche Normen un... |
| `gericht-dokumentenmatrix-und-lueckenliste` | Nutze dies, wenn Gericht: Dokumentenmatrix, Lückenliste und Nachforderung im Plugin Zitierweise Deutsches Recht konkret bearbeitet werden soll. Auslöser: Ich lade Unterlagen hoch.; Was fehlt noch?; Bitte Dokumente sortieren.. |
| `hauszitierweise` | Nutze dies, wenn Hauszitierweise: Tatbestandsmerkmale, Beweisfragen und Beleglage im Plugin Zitierweise Deutsches Recht konkret bearbeitet werden soll. Auslöser: Bitte Hauszitierweise: Tatbestandsmerkmale, Beweisfragen und Beleglage prüf... |
| `hauszitierweise-juristische-kommentar` | Nutze dies, wenn Spezial Hauszitierweise Tatbestand Beweis Und Belege, Spezial Juristische Erstpruefung Und Mandatsziel, Spezial Kommentar Compliance Dokumentation Und Akte im Plugin Zitierweise Deutsches Recht konkret bearbeitet werden... |
| `juristische` | Nutze dies, wenn Juristische: Erstprüfung, Rollenklärung und Mandatsziel im Plugin Zitierweise Deutsches Recht konkret bearbeitet werden soll. Auslöser: Bitte Juristische: Erstprüfung, Rollenklärung und Mandatsziel prüfen.; Erstelle eine... |
| `kommentar` | Nutze dies, wenn Kommentar: Compliance-Dokumentation und Aktenvermerk im Plugin Zitierweise Deutsches Recht konkret bearbeitet werden soll. Auslöser: Ich lade Unterlagen hoch.; Was fehlt noch?; Bitte Dokumente sortieren.. |
| `literatur` | Nutze dies, wenn Literatur: Formular, Portal und Einreichungslogik im Plugin Zitierweise Deutsches Recht konkret bearbeitet werden soll. Auslöser: Bitte Literatur: Formular, Portal und Einreichungslogik prüfen.; Erstelle eine Arbeitsfass... |
| `literatur-live-beweislast-lizenziertem` | Nutze dies, wenn Spezial Literatur Formular Portal Und Einreichung, Spezial Live Beweislast Und Darlegungslast, Spezial Lizenziertem Mandantenkommunikation Entscheidungsvorlage im Plugin Zitierweise Deutsches Recht konkret bearbeitet wer... |
| `live-beweislast-darlegungslast` | Nutze dies, wenn Live: Beweislast, Darlegungslast und Substantiierung im Plugin Zitierweise Deutsches Recht konkret bearbeitet werden soll. Auslöser: Bitte Live: Beweislast, Darlegungslast und Substantiierung prüfen.; Erstelle eine Arbei... |
| `lizenziertem` | Nutze dies, wenn Lizenziertem: Mandantenkommunikation und Entscheidungsvorlage im Plugin Zitierweise Deutsches Recht konkret bearbeitet werden soll. Auslöser: Bitte Lizenziertem: Mandantenkommunikation und Entscheidungsvorlage prüfen.; E... |
| `mandantenkommunikation` | Nutze dies, wenn Mandantenkommunikation im Plugin Zitierweise Deutsches Recht konkret bearbeitet werden soll. Auslöser: Bitte Mandantenkommunikation prüfen.; Erstelle eine Arbeitsfassung zu Mandantenkommunikation.; Welche Normen und Nach... |
| `nutzerquelle-fehlerkatalog` | Nutze dies, wenn Nutzerquelle Fehlerkatalog im Plugin Zitierweise Deutsches Recht konkret bearbeitet werden soll. Auslöser: Was kann hier schiefgehen?; Bitte red-team prüfen.; Welche Frist oder Beweislast übersehe ich?. |
| `output-waehlen` | Nutze dies, wenn Output wählen im Plugin Zitierweise Deutsches Recht konkret bearbeitet werden soll. Auslöser: Bitte Output wählen prüfen.; Erstelle eine Arbeitsfassung zu Output wählen.; Welche Normen und Nachweise brauche ich?. |
| `paywallfreie` | Nutze dies, wenn Workflow Mandantenkommunikation, Workflow Redteam Qualitygate, Spezial Paywallfreie Rechtsprechungsbelege im Plugin Zitierweise Deutsches Recht konkret bearbeitet werden soll. Auslöser: Was kann hier schiefgehen?; Bitte... |
| `paywallfreie-rechtsprechungsbelege` | Paywallfreie, prüfbare Rechtsprechungsbelege ohne Blindzitate: führt schnell durch Sachverhalt, Rechtsgrundlagen, Belege, Risiken und erzeugt einen verwertbaren nächsten Output. |
| `quelle-quellenkarte` | Nutze dies, wenn Quelle Quellenkarte im Plugin Zitierweise Deutsches Recht konkret bearbeitet werden soll. Auslöser: Welche amtliche Quelle prüfe ich zuerst?; Gibt es aktuelle Rechtsprechung?; Bitte Fundstellen verifizieren.. |
| `quellen-livecheck` | Nutze dies, wenn Rechtsquellen-Livecheck im Plugin Zitierweise Deutsches Recht konkret bearbeitet werden soll. Auslöser: Welche amtliche Quelle prüfe ich zuerst?; Gibt es aktuelle Rechtsprechung?; Bitte Fundstellen verifizieren.. |
| `rechtsprechung` | Nutze dies, wenn Rechtsprechung: Fristen, Form, Zuständigkeit und Rechtsweg im Plugin Zitierweise Deutsches Recht konkret bearbeitet werden soll. Auslöser: Bitte Rechtsprechung: Fristen, Form, Zuständigkeit und Rechtsweg prüfen.; Erstell... |
| `rechtsprechung-zit-rechtsprechungszitierung` | Nutze dies, wenn Spezial Rechtsprechung Fristen Form Und Zustaendigkeit, Zit Rechtsprechungszitierung Leitfaden, Zitat Eugh Rechtsprechung im Plugin Zitierweise Deutsches Recht konkret bearbeitet werden soll. Auslöser: Bitte Spezial Rech... |
| `redteam-qualitygate` | Nutze dies, wenn Red-Team Qualitygate im Plugin Zitierweise Deutsches Recht konkret bearbeitet werden soll. Auslöser: Was kann hier schiefgehen?; Bitte red-team prüfen.; Welche Frist oder Beweislast übersehe ich?. |
| `unterlagen-luecken` | Nutze dies, wenn Unterlagen und Lücken im Plugin Zitierweise Deutsches Recht konkret bearbeitet werden soll. Auslöser: Ich lade Unterlagen hoch.; Was fehlt noch?; Bitte Dokumente sortieren.. |
| `verifizierbarer` | Nutze dies, wenn Verifizierbarer: Verhandlung, Vergleich und Eskalation im Plugin Zitierweise Deutsches Recht konkret bearbeitet werden soll. Auslöser: Bitte Verifizierbarer: Verhandlung, Vergleich und Eskalation prüfen.; Erstelle eine A... |
| `verifizierbarer-zugriff-sonderfall-zit` | Nutze dies, wenn Spezial Verifizierbarer Verhandlung Vergleich Und Eskalation, Spezial Zugriff Sonderfall Und Edge Case, Zit Gesetzeszitierung Bauleiter im Plugin Zitierweise Deutsches Recht konkret bearbeitet werden soll. Auslöser: Bitt... |
| `zit-gesetzeszitierung-bauleiter` | Bauleiter Gesetzeszitierung in Schriftsatz und Memo: Norm, Absatz, Satz, Halbsatz, Nummer, Buchstabe. Pruefraster fuer einheitliche Schreibweise. |
| `zit-internationale-urteile-spezial` | Spezialfall Zitierung internationaler Urteile EuGH EGMR sowie Common-Law-Urteile: ECLI, Neutral Citation, Public Domain. Pruefraster fuer internationale Mandate. |
| `zit-internationale-zit-kommentar-zitat` | Nutze dies, wenn Zit Internationale Urteile Spezial, Zit Kommentar Aufsatzzitierung Spezial, Zitat Amtliche Sammlung Vs Zeitschrift im Plugin Zitierweise Deutsches Recht konkret bearbeitet werden soll. Auslöser: Bitte Zit Internationale... |
| `zit-kommentar-aufsatzzitierung-spezial` | Spezialfall Kommentar- und Aufsatzzitierung: Bearbeiter, Randnummer, Auflagenjahr, Zeitschrift, Heft, Seite. Pruefraster fuer wissenschaftliches Schreiben. |
| `zit-rechtsprechungszitierung-leitfaden` | Leitfaden Rechtsprechungszitierung BGH BVerfG EuGH: Gericht, Entscheidungsform, Datum, Aktenzeichen, frei pruefbarer Link dejure.org / openjur.de. Pruefraster fuer Memos. |
| `zitat-amtliche-sammlung-vs-zeitschrift` | Amtliche Sammlung vs. Zeitschrift: Reihenfolge der Fundstellen. Amtliche Sammlung (BGHZ, BVerfGE) hat Vorrang, dann Parallelfundstelle Zeitschrift (NJW, JZ, ZIP). Beispiel BGHZ 240 S. 1 = NJW 2024 S. 1832. |
| `zitat-archivierungspflicht` | Archivierungspflicht der zitierten Quelle: Screenshot mit Datum, PDF-Abruf, archive.org-Backup. Wichtig bei Schriftsaetzen, weil Online-Quellen veraendert werden. Empfehlung Kanzleiprozess. |
| `zitat-archivierungspflicht-aufsatz` | Nutze dies, wenn Zitat Archivierungspflicht, Zitat Aufsatz Zeitschrift, Zitat Bag Bfh Bsg Bag im Plugin Zitierweise Deutsches Recht konkret bearbeitet werden soll. Auslöser: Bitte Zitat Archivierungspflicht, Zitat Aufsatz Zeitschrift, Zi... |
| `zitat-aufsatz-zeitschrift` | Aufsatz in juristischer Zeitschrift nur bei vorliegendem Beitrag zitieren: Verfasser, Titel, Zeitschrift, Jahr, Heft/Seite und Pinpoint aus Nutzerquelle oder Live-Zugriff übernehmen. Keine Aufsatzfundstellen aus Modellwissen. |
| `zitat-bag-bfh-bsg-bag` | Fachgerichtsbarkeit zitieren: BAG, BFH, BSG, BVerwG, BGH. Format Senat, Datum, Aktenzeichen, amtliche Sammlung sowie Parallel-Fundstelle. Beispiel BAG, Urt. v. 12.09.2023 9 AZR 372 aus 22, BAGE 178 S. 199 = NZA 2023 S. 1521. |
| `zitat-bgh-entscheidung` | BGH-Entscheidung korrekt zitieren: Senat, Datum, Aktenzeichen, Fundstelle. Beispiel BGH, Urt. v. 11.04.2024 III ZR 168 aus 23, BGHZ 240 S. 1 = NJW 2024 S. 1832. Bei wichtiger Linie: Vor- und Folgeentscheidungen ergaenzen. |
| `zitat-bgh-entscheidung-bverfg-gesetz` | Nutze dies, wenn Zitat Bgh Entscheidung, Zitat Bverfg Entscheidung, Zitat Gesetz Verordnung im Plugin Zitierweise Deutsches Recht konkret bearbeitet werden soll. Auslöser: Bitte Zitat Bgh Entscheidung, Zitat Bverfg Entscheidung, Zitat Ge... |
| `zitat-bverfg-entscheidung` | BVerfG-Entscheidung zitieren: Senatsnummer, Datum, Aktenzeichen, BVerfGE, ggf. Kammerbeschluss. Beispiel BVerfG, Urt. v. 17.01.2024 1 BvR 1841 aus 23, BVerfGE 167 S. 1. Kammerentscheidung BVerfG (K), Beschl. v. ... mit Hinweis 'Nichtanna... |
| `zitat-eugh-rechtsprechung` | EuGH-Rechtsprechung zitieren: Urt./Beschl., Datum, Rs. C-Nummer, Parteinamen, ECLI. Beispiel EuGH, Urt. v. 04.07.2019 - C-377/17, Kommission/Deutschland, ECLI:EU:C:2019:562. Bei Generalanwalts-Schlussantraegen: GA-Anfang. |
| `zitat-gesetz-verordnung` | Gesetz/Verordnung zitieren: Norm-Bezeichnung, ggf. § und Absatz. Beispiel § 17 InsO, § 311 Abs. 2 BGB, Art. 26 DSGVO. Bei zeitlicher Bezugnahme: § X i. d. F. v. JJJJ. |
| `zitat-haus-zitierregel-anpassen` | Kanzlei-Hauszitierweise anpassen: Excel-Vorlage Beck/NJW vs. Hartung/Roemermann v4. Empfehlung: konsistente Regel pro Kanzlei, in den Schriftsatz-Templates verankern. Output: Hauszitierregel-Dokument. |
| `zitat-haus-zitierregel-instanzgerichte` | Nutze dies, wenn Zitat Haus Zitierregel Anpassen, Zitat Instanzgerichte Strategisch, Zitat Internationale Quellen im Plugin Zitierweise Deutsches Recht konkret bearbeitet werden soll. Auslöser: Bitte Zitat Haus Zitierregel Anpassen, Zita... |
| `zitat-instanzgerichte-strategisch` | Instanzgerichts-Entscheidungen strategisch zitieren: OLG-Entscheidungen, LG-Entscheidungen. Wann sinnvoll: Tendenzen, Lokal-Linien, Fehlen BGH-Rechtsprechung. Vermeiden: AG-Entscheidungen ausser bei sehr engen Fragen. |
| `zitat-internationale-quellen` | Internationale Quellen: EuGH, EGMR, Common-Law-Faelle (in IPR-Kontext). Format mit ECLI bzw. Neutral Citation. Beispiel EGMR, Urt. v. 23.01.2024 - Nr. 12345/22, ECLI:CE:ECHR:2024:0123JUD001234522. |
| `zitat-internet-quellen` | Internet-Quellen zitieren: Stand, URL, Abrufdatum. Bevorzugt: dejure.org, openjur.de, bundesgerichtshof.de, bundesverfassungsgericht.de, eur-lex. Vermeiden: anwalt24.de, BeckRS allein als einzige Fundstelle. |
| `zitat-internet-quellen-kommentar-randnummer` | Nutze dies, wenn Zitat Internet Quellen, Zitat Kommentar Randnummer, Zitat Leitsatzentscheidung im Plugin Zitierweise Deutsches Recht konkret bearbeitet werden soll. Auslöser: Welche amtliche Quelle prüfe ich zuerst?; Gibt es aktuelle Re... |
| `zitat-kommentar-randnummer` | Kommentar mit Bearbeiter und Randnummer nur bei vorliegender Nutzerquelle oder lizenziertem Live-Zugriff zitieren: Bearbeiter, Werk, aktuelle Auflage/Stand, Norm, Randnummer. Keine Kommentar-Rn. aus Modellwissen. |
| `zitat-leitsatzentscheidung` | Leitsatz-Entscheidung mit Leitsatz zitieren: BGH, Urt. ..., Leitsatz 1 lautet: ... Original-Leitsatz im Wortlaut, dann Begruendung mit Rn. Format fuer Schriftsatz und Memo. |
| `zitat-monografie-handbuch` | Monografie oder Handbuch nur bei vorliegender Quelle zitieren: Verfasser/Bearbeiter, Titel, Auflage/Stand, Jahr, Kapitel/Norm, Seite/Rn. Keine Handbuchfundstellen aus Modellwissen. |
| `zitat-monografie-handbuch-streitstand` | Nutze dies, wenn Zitat Monografie Handbuch, Zitat Streitstand Darstellen, Zitat Verboten Anwalt24 Beckrs im Plugin Zitierweise Deutsches Recht konkret bearbeitet werden soll. Auslöser: Bitte Zitat Monografie Handbuch, Zitat Streitstand D... |
| `zitat-rechtsprechung-fristennotiz-naechster` | Nutze dies, wenn Zitat Rechtsprechung Ohne Fundstelle, Spezial Zitierweise Fristennotiz Und Naechster Schritt, Spezial Aktenzeichen Schriftsatz Brief Und Memo Bausteine im Plugin Zitierweise Deutsches Recht konkret bearbeitet werden soll... |
| `zitat-rechtsprechung-ohne-fundstelle` | Rechtsprechung ohne amtliche/freie Fundstelle behandeln: Gericht Datum Aktenzeichen sichern, freie Quelle suchen, Datenbanknummern nur als Nutzerquelle/Lizenzfund vermerken und nicht als tragenden Ersatz verwenden. |
| `zitat-streitstand-darstellen` | Streitstand in Memo/Schriftsatz darstellen: h. M. (Rechtsprechung BGH + ueberwiegende Literatur), Gegenmeinung (Verfasser + Stellenangabe), eigene Loesung. Format mit klarer Position. |
| `zitat-verboten-anwalt24-beckrs` | Verbotene Zitate vermeiden: anwalt24.de (kein primaerer Rechtsstand), BeckRS allein (interne Beck-Online-ID), 'lawblog'-Eintraege. Speziell bei Schriftsaetzen: Gericht prueft Originalquelle. Empfehlung: immer dejure.org oder Originalents... |
| `zitierweise` | Nutze dies, wenn Zitierweise Anwenden im Plugin Zitierweise Deutsches Recht konkret bearbeitet werden soll. Auslöser: Bitte Zitierweise Anwenden prüfen.; Erstelle eine Arbeitsfassung zu Zitierweise Anwenden.; Welche Normen und Nachweise... |
| `zitierweise-anwenden` | Wende deutsche juristische Hauszitierweise v4.1 an. Rechtsprechung nur mit Gericht Entscheidungsform Datum Az. Aktenzeichen und verifizierbarer Quelle. Keine BeckRS-, juris-, Kommentar- oder Aufsatz-Blindzitate. Literatur nur bei Nutzerq... |
| `zitierweise-fristennotiz-naechster-schritt` | Nutze dies, wenn Zitierweise: Fristennotiz und nächster Schritt im Plugin Zitierweise Deutsches Recht konkret bearbeitet werden soll. Auslöser: Bitte Zitierweise: Fristennotiz und nächster Schritt prüfen.; Erstelle eine Arbeitsfassung zu... |
| `zugriff-sonderfall-edge-case` | Nutze dies, wenn Zugriff: Sonderfall und Edge-Case-Prüfung im Plugin Zitierweise Deutsches Recht konkret bearbeitet werden soll. Auslöser: Bitte Zugriff: Sonderfall und Edge-Case-Prüfung prüfen.; Erstelle eine Arbeitsfassung zu Zugriff:... |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
