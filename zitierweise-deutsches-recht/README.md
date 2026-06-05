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

Automatisch generierte Komplett-Liste aller 24 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `allgemein-workflow-chronologie-workflow-fristen` | Allgemein, Workflow Chronologie Und Belegmatrix, Workflow Fristen Und Risikoampel: Allgemein; Workflow Chronologie Und Belegmatrix; Workflow Fristen Und Risikoampel. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmus... |
| `aufsatz-interessen-beckrs-blindzitate` | Spezial Aufsatz Mehrparteien Konflikt Und Interessen, Spezial Beckrs Zahlen Schwellen Und Berechnung, Spezial Blindzitate Internationaler Bezug Und Schnittstellen: Spezial Aufsatz Mehrparteien Konflikt Und Interessen; Spezial Beckrs Zahl... |
| `datum-entscheidungsform-spezial-gericht` | Spezial Datum Behörden Gericht Und Registerweg, Spezial Entscheidungsform Risikoampel Und Gegenargumente, Spezial Gericht Dokumentenmatrix Und Lueckenliste: Spezial Datum Behörden Gericht Und Registerweg; Spezial Entscheidungsform Risiko... |
| `hauszitierweise-juristische-kommentar` | Spezial Hauszitierweise Tatbestand Beweis Und Belege, Spezial Juristische Erstpruefung Und Mandatsziel, Spezial Kommentar Compliance Dokumentation Und Akte: Spezial Hauszitierweise Tatbestand Beweis Und Belege; Spezial Juristische Erstpr... |
| `literatur-live-beweislast-lizenziertem` | Spezial Literatur Formular Portal Und Einreichung, Spezial Live Beweislast Und Darlegungslast, Spezial Lizenziertem Mandantenkommunikation Entscheidungsvorlage: Spezial Literatur Formular Portal Und Einreichung; Spezial Live Beweislast U... |
| `rechtsprechung-zit-rechtsprechungszitierung-zitat-eugh` | Spezial Rechtsprechung Fristen Form Und Zustaendigkeit, Zit Rechtsprechungszitierung Leitfaden, Zitat Eugh Rechtsprechung: Spezial Rechtsprechung Fristen Form Und Zustaendigkeit; Zit Rechtsprechungszitierung Leitfaden; Zitat Eugh Rechtsp... |
| `spezial-nutzerquelle-red-team-und-qualitaetskontrolle` | Nutzerquelle: Red-Team und Qualitätskontrolle im Plugin zitierweise deutsches recht; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Standardprüfung. |
| `spezial-quelle-livequellen-und-rechtsprechungscheck` | Quelle: Livequellen- und Rechtsprechungscheck im Plugin zitierweise deutsches recht; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Standardprüfung. |
| `verifizierbarer-zugriff-sonderfall-zit-gesetzeszitierung` | Spezial Verifizierbarer Verhandlung Vergleich Und Eskalation, Spezial Zugriff Sonderfall Und Edge Case, Zit Gesetzeszitierung Bauleiter: Spezial Verifizierbarer Verhandlung Vergleich Und Eskalation; Spezial Zugriff Sonderfall Und Edge Ca... |
| `workflow-anschluss-skills-router` | Anschluss-Skills Router im Plugin zitierweise-deutsches-recht: schlägt nach der ersten Prüfung die passenden Spezialskills aus demselben Plugin vor. |
| `workflow-dokumentenintake` | Dokumentenintake im Plugin zitierweise-deutsches-recht: liest Uploads, sortiert Dokumentarten, markiert Fristen und baut eine knappe Arbeitsakte. |
| `workflow-kaltstart-und-routing` | Kaltstart und Routing im Plugin zitierweise-deutsches-recht: führt vom ersten Satz oder Dokument in den passenden Arbeitsweg, erkennt Rolle, Ziel, Risiko und Anschluss-Skills. |
| `workflow-mandantenkommunikation-redteam-qualitygate-paywallfreie` | Workflow Mandantenkommunikation, Workflow Redteam Qualitygate, Spezial Paywallfreie Rechtsprechungsbelege: Workflow Mandantenkommunikation; Workflow Redteam Qualitygate; Spezial Paywallfreie Rechtsprechungsbelege. Führt Intake, Prüfrouti... |
| `workflow-output-waehlen` | Output wählen im Plugin zitierweise-deutsches-recht: entscheidet zwischen Memo, Schriftsatz, Tabelle, Brief, Checkliste, Vermerk, Redline oder Mandantenübersetzung. |
| `workflow-rechtsquellen-livecheck` | Rechtsquellen-Livecheck im Plugin zitierweise-deutsches-recht: zwingt vor tragenden Aussagen zum aktuellen Quellencheck bei Gesetzen, Behörden, Gerichten und Formularen. |
| `workflow-unterlagen-lueckenliste` | Unterlagen- und Lückenliste im Plugin zitierweise-deutsches-recht: erstellt eine präzise Nachforderungsliste statt allgemeiner Fragebögen. |
| `zit-internationale-zit-kommentar-zitat-amtliche` | Zit Internationale Urteile Spezial, Zit Kommentar Aufsatzzitierung Spezial, Zitat Amtliche Sammlung Vs Zeitschrift: Zit Internationale Urteile Spezial; Zit Kommentar Aufsatzzitierung Spezial; Zitat Amtliche Sammlung Vs Zeitschrift. Führt... |
| `zitat-archivierungspflicht-aufsatz-zeitschrift-bag-bfh` | Zitat Archivierungspflicht, Zitat Aufsatz Zeitschrift, Zitat Bag Bfh Bsg Bag: Zitat Archivierungspflicht; Zitat Aufsatz Zeitschrift; Zitat Bag Bfh Bsg Bag. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qu... |
| `zitat-bgh-entscheidung-bverfg-gesetz-verordnung` | Zitat Bgh Entscheidung, Zitat Bverfg Entscheidung, Zitat Gesetz Verordnung: Zitat Bgh Entscheidung; Zitat Bverfg Entscheidung; Zitat Gesetz Verordnung. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualit... |
| `zitat-haus-zitierregel-instanzgerichte-strategisch` | Zitat Haus Zitierregel Anpassen, Zitat Instanzgerichte Strategisch, Zitat Internationale Quellen: Zitat Haus Zitierregel Anpassen; Zitat Instanzgerichte Strategisch; Zitat Internationale Quellen. Führt Intake, Prüfroutine, Normen-/Quelle... |
| `zitat-internet-quellen-kommentar-randnummer-leitsatzentscheidung` | Zitat Internet Quellen, Zitat Kommentar Randnummer, Zitat Leitsatzentscheidung: Zitat Internet Quellen; Zitat Kommentar Randnummer; Zitat Leitsatzentscheidung. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster un... |
| `zitat-monografie-handbuch-streitstand-darstellen-verboten` | Zitat Monografie Handbuch, Zitat Streitstand Darstellen, Zitat Verboten Anwalt24 Beckrs: Zitat Monografie Handbuch; Zitat Streitstand Darstellen; Zitat Verboten Anwalt24 Beckrs. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogi... |
| `zitat-rechtsprechung-fristennotiz-naechster-aktenzeichen` | Zitat Rechtsprechung Ohne Fundstelle, Spezial Zitierweise Fristennotiz Und Naechster Schritt, Spezial Aktenzeichen Schriftsatz Brief Und Memo Bausteine: Zitat Rechtsprechung Ohne Fundstelle; Spezial Zitierweise Fristennotiz Und Naechster... |
| `zitierweise` | Zitierweise Anwenden: Zitierweise Anwenden. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zusammen. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
