# patentrecht

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`patentrecht`) | [`patentrecht.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/patentrecht.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **Schnellverschluss S-14: Sensorhalter, Gebrauchsmusterabzweigung und Messeoffenbarung** (`gebrauchsmusterrecht-schnellverschluss-sensorhalter`) | [Gesamt-PDF lesen](../testakten/gebrauchsmusterrecht-schnellverschluss-sensorhalter/gesamt-pdf/gebrauchsmusterrecht-schnellverschluss-sensorhalter_gesamt.pdf) | [`testakte-gebrauchsmusterrecht-schnellverschluss-sensorhalter.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-gebrauchsmusterrecht-schnellverschluss-sensorhalter.zip) |
| **Patentrecht — Erfindungsakten Ravenstein & Moll** (`patentrecht-erfindungsakten-ravenstein-moll`) | [Gesamt-PDF lesen](../testakten/patentrecht-erfindungsakten-ravenstein-moll/gesamt-pdf/patentrecht-erfindungsakten-ravenstein-moll_gesamt.pdf) | [`testakte-patentrecht-erfindungsakten-ravenstein-moll.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-patentrecht-erfindungsakten-ravenstein-moll.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

> Großes Arbeitsplugin für Patentanwältinnen, Rechtsanwälte, Patentabteilungen und technische Gründerteams. Es führt vom rohen Erfindungsgedanken über Anspruchsentwurf, Recherche, Anmeldung, Prüfung, Freedom-to-Operate, Abmahnung, Lizenzvertrag, Einspruch und Nichtigkeit bis zur belastbaren Mandantenkommunikation.

## Wofür dieses Plugin gedacht ist

Das Plugin ist nicht nur eine Recherchehilfe. Es ist der Mandatsarbeitsplatz für Patentrecht:

- **Erfindung aufnehmen:** technische Lehre, Problem, Lösung, Ausführungsformen, Offenbarungsrisiken und fehlende Zeichnungen sauber einsammeln.
- **Anmeldung vorbereiten:** Anspruch 1, Unteransprüche, Beschreibung, Bezugszeichenliste, Figurenlogik, Alternativausführungen und Rückfragen strukturieren.
- **Patentfähigkeit prüfen:** Neuheit und erfinderische Tätigkeit nach PatG und EPÜ mit Merkmalsgliederung, nächstliegendem Stand der Technik und Aufgaben-Lösungs-Ansatz.
- **Recherche steuern:** gezielte Übergabe an das Spezialplugin [`patentrecherche`](../patentrecherche) für Espacenet, DPMAregister, DEPATISnet, EPO Register, WIPO PATENTSCOPE und weitere Datenbanken.
- **Verletzung und FTO prüfen:** Schutzbereich, wortsinngemäße Verwirklichung, Äquivalenz, Registerstand, Territory, Rechtsbestand und Design-around.
- **Abmahnung verteidigen:** Fristen, Unterlassung, Auskunft, Rückruf, Schadensersatz, negative Feststellung, Schutzschrift, Vergleichsfenster.
- **Verträge prüfen:** Patentlizenz, Exclusivity, Territory, Field of Use, Sublicensing, Improvements, Know-how, Royalties, Audit, Termination und DE/EN-Klauselrisiken.
- **Bestand angreifen oder verteidigen:** EPA-Einspruch, deutsche Nichtigkeitsklage, Beschränkung, Hilfsanträge, Fristen und Beweismittel.

## Arbeitsstil

Der Einstiegsskill fragt nicht lehrbuchartig alles ab, sondern sortiert den Fall sofort nach Dringlichkeit, Materiallage und Ziel. Bei Dokumentenupload ohne Begleittext erkennt er Fristen, Aktenart und Primärpfad. Danach schlägt er die passenden Spezialskills vor oder arbeitet direkt weiter.

## Quellen- und Zitierhygiene

- Normen und Behördeninformationen werden bevorzugt aus offiziellen Quellen geprüft: Patentgesetz auf Gesetze-im-Internet, DPMA-Informationen, DPMAregister/DEPATISnet, EPO/EPA Legal Texts, EPO Register, Espacenet, WIPO PATENTSCOPE und amtliche Gerichtsquellen.
- Rechtsprechung wird nur ausgegeben, wenn Gericht, Entscheidungsdatum, Aktenzeichen und eine frei zugängliche oder amtliche Fundstelle verifiziert sind.
- Keine BeckRS-/juris-/Paywall-Fundstellen erfinden oder als eigene Quelle verwenden.
- Wenn eine Bewertung von aktueller Amts- oder Registerlage abhängt, muss live nachgesehen werden.

## Verhältnis zu anderen Plugins

- [`patentrecherche`](../patentrecherche): tiefe Datenbankrecherche, CPC/IPC, Patentfamilien, Registerstand, Recherchebericht.
- [`gewerblicher-rechtsschutz`](../gewerblicher-rechtsschutz) und [`fachanwalt-gewerblicher-rechtsschutz`](../fachanwalt-gewerblicher-rechtsschutz): Marken, Designs, UWG, Verletzungsprozess und IP-Kollisionslagen.
- [`zitierweise-deutsches-recht`](../zitierweise-deutsches-recht): saubere Nachweise und Rechtsprechungszitate.
- [`word-legal-ai-plugin-and-skill-for-german-lawyers`](../word-legal-ai-plugin-and-skill-for-german-lawyers): Schriftsatz-, Gutachten-, Vertrags- und Mandantenbriefstil.

## Kern-Workflow

1. **Material erfassen:** Upload, Fristen, Beteiligte, Schutzrechte, Produkt/Verfahren, Technikfeld, Zielterritorien.
2. **Primärfrage festlegen:** Anmeldung, Recherche, FTO, Verletzung, Lizenz, Prüfungsbescheid, Einspruch/Nichtigkeit.
3. **Technische Lehre zerlegen:** Merkmale, Varianten, Wirkungen, Problem, Lösung, Zeichnungen, Bezugszeichen.
4. **Rechts- und Registerlage sichern:** Anmeldetag, Priorität, Veröffentlichung, Erteilung, Einspruch, Jahresgebühren, Validierungen, Rechtsstand.
5. **Spezialskill starten:** passende Skills aus diesem Plugin und bei Recherchebedarf aus `patentrecherche`.
6. **Output bauen:** Claim Draft, Merkmalsgliederung, Rechercheauftrag, Claim Chart, Risikomemo, Antwortentwurf, Lizenz-Redline oder Fristenplan.
7. **Red Team:** offene Tatsachen, technische Unschärfen, Fristen, Quellen, Gegenargumente, Mandantenrückfragen.

## Kernskills und neue internationale Module

Die folgende Tabelle nennt die ursprünglichen Kernskills. Die vollständige, automatisch generierte Liste steht direkt darunter und enthält jetzt auch UPC, PCT, USA, Kanada, Japan, Schweiz, UK, Türkei, Israel sowie Patentprozess/Eilrechtsschutz/Revocation.

| Skill | Funktion |
| --- | --- |
| `allgemein` | Einstieg, Triage und Workflow-Routing für jedes Patentrechtsmandat |
| `patentrecht-kaltstart-interview` | kurzes Mandatsprofil und wiederverwendbare Fallarchitektur |
| `erfindungsmeldung-aufnahme-und-rueckfragen` | rohe Erfindung, Offenbarung, technische Lehre und Rückfragen erfassen |
| `patentanmeldung-anspruchsentwurf` | Anspruch 1, Unteransprüche und Varianten vorbereiten |
| `beschreibung-und-zeichnungen-pruefen` | Beschreibung, Figuren, Bezugszeichen und Offenbarungsstütze prüfen |
| `neuheit-und-erfinderische-taetigkeit` | Merkmalsanalyse, Einzeldokumentprüfung, Aufgaben-Lösungs-Ansatz |
| `stand-der-technik-recherche-workflow` | Rechercheauftrag und Übergabe an `patentrecherche` |
| `gebrauchsmuster-oder-patent-route` | Patent, Gebrauchsmuster, EP/PCT, Geheimhaltung oder defensive Veröffentlichung abwägen |
| `pruefungsbescheid-dpma-epa-erwiderung` | Beanstandungen zerlegen und Erwiderung vorbereiten |
| `freedom-to-operate-und-schutzbereich` | FTO, Schutzbereich, Rechtsstand und Design-around |
| `abmahnung-patentverletzung-verteidigung` | Abmahnung, Fristen, Unterlassung, Schutzschrift, Vergleich |
| `patentverletzung-claim-chart` | claim chart für Verletzung oder Nichtverletzung |
| `vorbenutzungsrecht-paragraph-12-patg` | Vorbenutzungsrecht, Beweisführung und Risikostrategie |
| `patentlizenzvertrag-review` | Lizenzvertragsprüfung, Red Flags und Verhandlungspositionen |
| `patentlizenzvertrag-de-en-drafting` | zweisprachige Lizenzklauseln und Term-Sheet-Umsetzung |
| `erfinderbenennung-und-arbeitnehmererfindung` | Erfinderstatus, Arbeitnehmererfindung und Vergütungsschnittstellen |
| `einspruch-epa-und-nichtigkeit-bpatg` | EPA-Einspruch und Nichtigkeitsklage strategisch vorbereiten |
| `rechtsstand-register-und-fristen` | Register, Fristen, Jahresgebühren, Validierung, Einspruchs- und Klagefenster |
| `patentportfolio-und-technikstrategie` | Portfolio, Schutzzaun, Wettbewerbsmonitoring und Produktroadmap |
| `patentrecht-redteam-qualitygate` | Qualitätskontrolle für alle patentrechtlichen Outputs |

## Internationaler und prozessualer Ausbau

Neu hinzugekommen sind Skills für internationale Patentstrategie und Patentstreitigkeiten: UPC-Verletzung und Revocation, UPC-Eilverfahren, EPO-Einspruch/Beschwerde, PCT-Nationalphasen, US/UK/Kanada/Japan/Schweiz/Türkei/Israel, globale Rechtsbestandsangriffe, Schutzschrift/Protective Letter, Besichtigung, Auskunft/Rechnungslegung, Claim Construction DE/EN, Patentvergleich/Cross-License, Expertenarbeit und Prozessbudget.

Jeder dieser Skills arbeitet mit derselben Grundregel: Registerstand und lokale Verfahrensfragen live prüfen; ausländisches Recht als Arbeitsstruktur und Counsel-Briefing behandeln, nicht als scheinbar endgültige lokale Rechtsauskunft.

## Pflicht-Disclaimer im Output

Jedes externe Ergebnis enthält knapp: KI-gestützte Vorprüfung; keine amtliche Recherche; Register- und Rechtsstand sind live zu verifizieren; technische Bewertung setzt vollständige Unterlagen voraus.

## Lizenz

Apache-2.0 OR MIT. Siehe Repository-Stammverzeichnis.

<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 23 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `allgemein` | Einstieg, Schnelltriage und Workflow-Routing im Patentrecht-Plugin. Erkennt Patentanmeldung, Erfindungsmeldung, Recherche, FTO, Abmahnung, Lizenz, Einspruch, Nichtigkeit, Register- und Fristenfragen; schlägt passende Spezialskills aus di... |
| `kompendium-01-stand-der-technik-re-bis-rechtsabteilung-upc` | patentrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Stand Der Technik Recherche Workflow, Patr2 Anmeldeverfahren Bauleiter, Upc Eilverfahren Und Deutsche Parallelstrategie; mit Intake, Prüfroutine, Normen-/Quellenrad... |
| `kompendium-02-rechtsstand-register-bis-patentanmeldung-ansp` | patentrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Rechtsstand Register Und Fristen, Patentanmeldung Fristen Form Und Zustaendigkeit, Patentanmeldung Anspruchsentwurf; mit Intake, Prüfroutine, Normen-/Quellenradar,... |
| `kompendium-03-patentlizenzvertrag-bis-spezial-anspruchsent` | patentrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Patentlizenzvertrag De En Drafting, Patentlizenzvertrag Review, Anspruchsentwurf Dokumentenmatrix Und Lueckenliste; mit Intake, Prüfroutine, Normen-/Quellenradar, B... |
| `kompendium-04-patentprozess-auskun-bis-abmahnung-patentverl` | patentrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Patentprozess Auskunft Rechnungslegung Schadensersatz, Patentportfolio Und Technikstrategie, Abmahnung Patentverletzung Verteidigung; mit Intake, Prüfroutine, Norme... |
| `kompendium-05-beschreibung-und-zei-bis-epo-epue-einspruch-b` | patentrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Beschreibung Und Zeichnungen Pruefen, Einspruch Epa Und Nichtigkeit Bpatg, Epo Epue Einspruch Beschwerde Beschraenkung; mit Intake, Prüfroutine, Normen-/Quellenrada... |
| `kompendium-06-erfinderbenennung-un-bis-freedom-to-operate-u` | patentrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Erfinderbenennung Und Arbeitnehmererfindung, Erfindungsmeldung Aufnahme Und Rueckfragen, Freedom To Operate Und Schutzbereich; mit Intake, Prüfroutine, Normen-/Quel... |
| `kompendium-07-gebrauchsmuster-oder-bis-israel-patentrecht-i` | patentrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Gebrauchsmuster Oder Patent Route, Internationaler Patentrechts Und Laendercheck, Israel Patentrecht Ilpo Opposition Revocation; mit Intake, Prüfroutine, Normen-/Qu... |
| `kompendium-08-japan-patentrecht-jp-bis-loeschung-widerruf-n` | patentrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Japan Patentrecht Jpo Ip High Court, Kanada Patentrecht Cipo Federal Court, Loeschung Widerruf Nichtigkeit Global Route; mit Intake, Prüfroutine, Normen-/Quellenrad... |
| `kompendium-09-neuheit-und-erfinder-bis-patentprozess-claim` | patentrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Neuheit Und Erfinderische Taetigkeit, Patentprozess Besichtigung Beweissicherung, Patentprozess Claim Construction De En; mit Intake, Prüfroutine, Normen-/Quellenra... |
| `kompendium-10-patentprozess-einstw-bis-patentprozess-kosten` | patentrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Patentprozess Einstweilige Verfuegung De Upc, Patentprozess Experten Und Sachverstaendige, Patentprozess Kostensicherheit Und Budget; mit Intake, Prüfroutine, Norme... |
| `kompendium-11-patentprozess-negati-bis-patentsettlement-und` | patentrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Patentprozess Negative Feststellungsklage, Patentprozess Schutzschrift Und Caveat, Patentsettlement Und Cross License Litigation; mit Intake, Prüfroutine, Normen-/Q... |
| `kompendium-12-patentverletzung-cla-bis-patr2-patentverletzu` | patentrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Patentverletzung Claim Chart, Patr2 Arbeitnehmererfindung Leitfaden, Patr2 Patentverletzungsklage Spezial; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogi... |
| `kompendium-13-patr2-zwangslizenz-s-bis-pruefungsbescheid-dp` | patentrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Patr2 Zwangslizenz Spezial, Pct Laenderstrategie Und Nationalphasen, Pruefungsbescheid Dpma Epa Erwiderung; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislog... |
| `kompendium-14-rechtsabteilung-empl-bis-rechtsabteilung-free` | patentrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Employee Invention Im Konzernprojekt, Frand Verteidigung Bei Sep Abmahnung, Freedom To Operate Vor Product Launch; mit Intake, Prüfroutine, Normen-/Quellenradar, Be... |
| `kompendium-15-rechtsabteilung-prop-bis-spezial-erfindungsau` | patentrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Proportionalitaet Der Unterlassung 139 Patg, Schweiz Patentrecht Bundespatentgericht, Erfindungsaufnahme Tatbestand Beweis Und Belege; mit Intake, Prüfroutine, Norm... |
| `kompendium-16-spezial-patentrechts-bis-uk-patentrecht-paten` | patentrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Patentrechts Erstpruefung Und Mandatsziel, Tuerkei Patentrecht Turkpatent Ip Courts, Uk Patentrecht Patents Court Ipec Ukipo; mit Intake, Prüfroutine, Normen-/Quell... |
| `kompendium-17-upc-einstweilige-mas-bis-upc-widerruf-und-wid` | patentrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Upc Einstweilige Massnahmen, Upc Verletzung Und Rechtsbestand, Upc Widerruf Und Widerklage Revocation; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, O... |
| `kompendium-18-us-patent-law-pto-pt-bis-vorbenutzungsrecht-p` | patentrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Us Patent Law Pto Ptab, Us Patent Litigation District Court Itc, Vorbenutzungsrecht Paragraph 12 Patg; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, O... |
| `patentrecht-kaltstart-interview` | Kaltstart-Interview für Patentrechtsmandate. Erstellt ein kurzes Profil zu Mandant, Technik, Ziel, Territorien, Fristen, Dokumentenlage, Risiko und gewünschtem Output; speichert keine Geheimnisse, sondern strukturiert die nächsten Skills. |
| `patentrecht-redteam-qualitygate` | Red-Team- und Qualitätsgate für patentrechtliche Outputs: prüft Fristen, Registerstand, Anspruchsfassung, technische Annahmen, Quellen, Beweise, Zitierhygiene, offene Tatsachen und Mandantenrisiken. |
| `workflow-dokumentenintake` | Dokumentenintake im Plugin patentrecht: liest Uploads, sortiert Dokumentarten, markiert Fristen und baut eine knappe Arbeitsakte. |
| `workflow-kaltstart-und-routing` | Kaltstart und Routing im Plugin patentrecht: führt vom ersten Satz oder Dokument in den passenden Arbeitsweg, erkennt Rolle, Ziel, Risiko und Anschluss-Skills. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
