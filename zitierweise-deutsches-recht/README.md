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
| `kompendium-01-allgemein-bis-workflow-fristen-und` | zitierweise-deutsches-recht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Allgemein, Chronologie Und Belegmatrix, Fristen Und Risikoampel; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualit... |
| `kompendium-02-workflow-mandantenko-bis-spezial-paywallfreie` | zitierweise-deutsches-recht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Mandantenkommunikation, Redteam Qualitygate, Paywallfreie Rechtsprechungsbelege; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputm... |
| `kompendium-03-spezial-rechtsprechu-bis-zitat-eugh-rechtspre` | zitierweise-deutsches-recht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Rechtsprechung Fristen Form Und Zustaendigkeit, Zit Rechtsprechungszitierung Leitfaden, Zitat Eugh Rechtsprechung; mit Intake, Prüfroutine, Normen-/... |
| `kompendium-04-zitat-rechtsprechung-bis-spezial-aktenzeichen` | zitierweise-deutsches-recht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Zitat Rechtsprechung Ohne Fundstelle, Zitierweise Fristennotiz Und Naechster Schritt, Aktenzeichen Schriftsatz Brief Und Memo Bausteine; mit Intake,... |
| `kompendium-05-spezial-aufsatz-mehr-bis-spezial-blindzitate` | zitierweise-deutsches-recht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Aufsatz Mehrparteien Konflikt Und Interessen, Beckrs Zahlen Schwellen Und Berechnung, Blindzitate Internationaler Bezug Und Schnittstellen; mit Inta... |
| `kompendium-06-spezial-datum-behoer-bis-spezial-gericht-doku` | zitierweise-deutsches-recht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Datum Behoerden Gericht Und Registerweg, Entscheidungsform Risikoampel Und Gegenargumente, Gericht Dokumentenmatrix Und Lueckenliste; mit Intake, Pr... |
| `kompendium-07-spezial-hauszitierwe-bis-spezial-kommentar-co` | zitierweise-deutsches-recht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Hauszitierweise Tatbestand Beweis Und Belege, Juristische Erstpruefung Und Mandatsziel, Kommentar Compliance Dokumentation Und Akte; mit Intake, Prü... |
| `kompendium-08-spezial-literatur-fo-bis-spezial-lizenziertem` | zitierweise-deutsches-recht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Literatur Formular Portal Und Einreichung, Live Beweislast Und Darlegungslast, Lizenziertem Mandantenkommunikation Entscheidungsvorlage; mit Intake,... |
| `kompendium-09-spezial-verifizierba-bis-zit-gesetzeszitierun` | zitierweise-deutsches-recht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Verifizierbarer Verhandlung Vergleich Und Eskalation, Zugriff Sonderfall Und Edge Case, Zit Gesetzeszitierung Bauleiter; mit Intake, Prüfroutine, No... |
| `kompendium-10-zit-internationale-u-bis-zitat-amtliche-samml` | zitierweise-deutsches-recht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Zit Internationale Urteile Spezial, Zit Kommentar Aufsatzzitierung Spezial, Zitat Amtliche Sammlung Vs Zeitschrift; mit Intake, Prüfroutine, Normen-... |
| `kompendium-11-zitat-archivierungsp-bis-zitat-bag-bfh-bsg-ba` | zitierweise-deutsches-recht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Zitat Archivierungspflicht, Zitat Aufsatz Zeitschrift, Zitat Bag Bfh Bsg Bag; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmust... |
| `kompendium-12-zitat-bgh-entscheidu-bis-zitat-gesetz-verordn` | zitierweise-deutsches-recht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Zitat Bgh Entscheidung, Zitat Bverfg Entscheidung, Zitat Gesetz Verordnung; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster... |
| `kompendium-13-zitat-haus-zitierreg-bis-zitat-internationale` | zitierweise-deutsches-recht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Zitat Haus Zitierregel Anpassen, Zitat Instanzgerichte Strategisch, Zitat Internationale Quellen; mit Intake, Prüfroutine, Normen-/Quellenradar, Bew... |
| `kompendium-14-zitat-internet-quell-bis-zitat-leitsatzentsch` | zitierweise-deutsches-recht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Zitat Internet Quellen, Zitat Kommentar Randnummer, Zitat Leitsatzentscheidung; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmu... |
| `kompendium-15-zitat-monografie-han-bis-zitat-verboten-anwal` | zitierweise-deutsches-recht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Zitat Monografie Handbuch, Zitat Streitstand Darstellen, Zitat Verboten Anwalt24 Beckrs; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik,... |
| `kompendium-16-zitierweise-anwenden-bis-zitierweise-anwenden` | zitierweise-deutsches-recht: eigenständiger Arbeits-Skill zu Zitierweise Anwenden; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck. |
| `spezial-nutzerquelle-red-team-und-qualitaetskontrolle` | Nutzerquelle: Red-Team und Qualitätskontrolle im Plugin zitierweise deutsches recht; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Standardprüfung. |
| `spezial-quelle-livequellen-und-rechtsprechungscheck` | Quelle: Livequellen- und Rechtsprechungscheck im Plugin zitierweise deutsches recht; schärft Rollen, Belege, Fachnormen, Risiken, Gegenargumente und nächsten verwertbaren Schritt statt austauschbarer Standardprüfung. |
| `workflow-anschluss-skills-router` | Anschluss-Skills Router im Plugin zitierweise-deutsches-recht: schlägt nach der ersten Prüfung die passenden Spezialskills aus demselben Plugin vor. |
| `workflow-dokumentenintake` | Dokumentenintake im Plugin zitierweise-deutsches-recht: liest Uploads, sortiert Dokumentarten, markiert Fristen und baut eine knappe Arbeitsakte. |
| `workflow-kaltstart-und-routing` | Kaltstart und Routing im Plugin zitierweise-deutsches-recht: führt vom ersten Satz oder Dokument in den passenden Arbeitsweg, erkennt Rolle, Ziel, Risiko und Anschluss-Skills. |
| `workflow-output-waehlen` | Output wählen im Plugin zitierweise-deutsches-recht: entscheidet zwischen Memo, Schriftsatz, Tabelle, Brief, Checkliste, Vermerk, Redline oder Mandantenübersetzung. |
| `workflow-rechtsquellen-livecheck` | Rechtsquellen-Livecheck im Plugin zitierweise-deutsches-recht: zwingt vor tragenden Aussagen zum aktuellen Quellencheck bei Gesetzen, Behörden, Gerichten und Formularen. |
| `workflow-unterlagen-lueckenliste` | Unterlagen- und Lückenliste im Plugin zitierweise-deutsches-recht: erstellt eine präzise Nachforderungsliste statt allgemeiner Fragebögen. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
