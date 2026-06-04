# Informationsfreiheit und Presseauskunft

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`informationsfreiheit-presseauskunft`) | [`informationsfreiheit-presseauskunft.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/informationsfreiheit-presseauskunft.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **IFG-/Presseauskunftsakte Hafenstadt** (`informationsfreiheit-presseauskunft-klinikdaten-hafenstadt`) | [Gesamt-PDF lesen](../testakten/informationsfreiheit-presseauskunft-klinikdaten-hafenstadt/gesamt-pdf/informationsfreiheit-presseauskunft-klinikdaten-hafenstadt_gesamt.pdf) | [`testakte-informationsfreiheit-presseauskunft-klinikdaten-hafenstadt.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-informationsfreiheit-presseauskunft-klinikdaten-hafenstadt.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

Dieses Plugin ist das Cockpit für Menschen, Journalistinnen, Kanzleien, NGOs und Unternehmen, die amtliche Informationen bekommen wollen, ohne an Zuständigkeitsnebel, Gebührenbescheiden oder Ausweichantworten hängen zu bleiben.

## Start

Beginne mit `allgemein`. Das Plugin fragt zuerst nach Rolle, Ziel, Frist, Behörde/Gericht/Register, vorhandenen Unterlagen und gewünschtem Output. Danach schlägt es die passenden Spezialskills aus diesem Plugin vor.

## Arbeitsweise

- Es arbeitet mit Akten- und Fristenlogik statt mit Bauchgefühl.
- Es trennt Rechtsgrundlage, Verfahren, Beweis, Kosten, Kommunikation und Eskalation.
- Es soll Nutzerinnen und Nutzer befähigen: verständliche Erklärung, präzise Rückfragen, dann belastbarer Entwurf.
- Rechtsprechung und Gesetzesstände werden nicht halluziniert, sondern als Live-Check über amtliche oder frei zugängliche Quellen markiert.

## Typische Outputs

- Kaltstart-Interview und Aktenlandkarte
- Behörden-, Gerichts- oder Gegneranschreiben
- Widerspruchs-/Klage-/Eilantragsbausteine
- Kosten-, Fristen- und Zuständigkeitsmatrix
- Dashboard/Tracker für laufende Vorgänge
- Kurzfassung für Mandant, Vorstand, Verband, Redaktion oder Bürgerin

## Quellenhygiene

Siehe [`references/QUELLEN.md`](./references/QUELLEN.md). Dieses Plugin gibt keine endgültige Rechtsberatung, sondern robuste Arbeitsfassungen, Prüfpfade und Dokumentationshilfen.

## Lizenz

Apache-2.0 OR MIT — Auswahl beim Empfänger.

<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 27 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `allgemein` | Informationsfreiheit und Presseauskunft: Kaltstart, Aktenlandkarte, Rollenklärung, Fristen, Quellenprüfung, Spezialskill-Routing und erste Ausgabe. |
| `ifg-001-kaltstart-informationsbegehren-sortier` | Informationsfreiheit und Presseauskunft: Kaltstart Informationsbegehren sortieren. Kaltstart Informationsbegehren sortieren im Fachgebiet Informationsfreiheit und Presseauskunft als geführten Arbeitsgang mit Fragen, Dokumentenlogik und A... |
| `kompendium-01-ifg-006-fristenkalen-bis-ifg-048-ifggebv-gebu` | informationsfreiheit-presseauskunft: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Ifg 006 Fristenkalender Und Untaetigkeitstrack, Ifg 038 Ifg Bund Zustaendigkeit Pruefen, Ifg 039 Ifg Bund Frist Setzen, Ifg 048 Ifggebv Gebu... |
| `kompendium-02-ifg-049-ifggebv-gebu-bis-ifg-069-vig-lebensmi` | informationsfreiheit-presseauskunft: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Ifg 049 Ifggebv Gebuehren Frist Setzen, Ifg 058 Uig Umweltinformation Zustaendigkeit P, Ifg 059 Uig Umweltinformation Frist Setzen, Ifg 069... |
| `kompendium-03-ifg-078-landespresse-bis-ifg-089-transparenzg` | informationsfreiheit-presseauskunft: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Ifg 078 Landespressegesetz Zustaendigkeit Prue, Ifg 079 Landespressegesetz Frist Setzen, Ifg 088 Transparenzgesetz Zustaendigkeit Pruef, Ifg... |
| `kompendium-04-ifg-098-archivrecht-bis-ifg-003-bundesbehoer` | informationsfreiheit-presseauskunft: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Ifg 098 Archivrecht Zustaendigkeit Pruefen, Ifg 099 Archivrecht Frist Setzen, Ifg 002 Ifg Oder Presseauskunft Richtig Routen, Ifg 003 Bundes... |
| `kompendium-05-ifg-004-kein-ifg-im-bis-ifg-008-personenbezo` | informationsfreiheit-presseauskunft: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Ifg 004 Kein Ifg Im Land Ersatzwege Finden, Ifg 005 Kostenrisiko Und Gebuehrenankuendigung, Ifg 007 Drittbeteiligung Bei Betriebsgeheimnis,... |
| `kompendium-06-ifg-009-uig-und-umwe-bis-ifg-012-presseanfrag` | informationsfreiheit-presseauskunft: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Ifg 009 Uig Und Umweltinformationen Abgrenzen, Ifg 010 Vig Und Verbraucherinformationen Nutze, Ifg 011 Akteneinsicht Oder Auskunft Oder Kopi... |
| `kompendium-07-ifg-013-ablehnungsbe-bis-ifg-016-gebuehrenbes` | informationsfreiheit-presseauskunft: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Ifg 013 Ablehnungsbescheid In Angriffspunkte Z, Ifg 014 Widerspruch Gegen Ifg Ablehnung, Ifg 015 Verpflichtungsklage Und Eilrechtsschut, Ifg... |
| `kompendium-08-ifg-017-informations-bis-ifg-020-veroeffentli` | informationsfreiheit-presseauskunft: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Ifg 017 Informationszugang Bei Beliehenen Priv, Ifg 018 Parlaments Und Rechnungshofgrenzen, Ifg 019 Sicherheitsinteressen Und Geheimschutz,... |
| `kompendium-09-ifg-021-informations-bis-ifg-024-informations` | informationsfreiheit-presseauskunft: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Ifg 021 Informationszugang Baden Wuerttemberg, Ifg 022 Informationszugang Bayern Livecheck, Ifg 023 Informationszugang Berlin Livecheck, Ifg... |
| `kompendium-10-ifg-025-informations-bis-ifg-028-informations` | informationsfreiheit-presseauskunft: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Ifg 025 Informationszugang Bremen Livecheck, Ifg 026 Informationszugang Hamburg Livecheck, Ifg 027 Informationszugang Hessen Livecheck, Ifg... |
| `kompendium-11-ifg-029-informations-bis-ifg-032-informations` | informationsfreiheit-presseauskunft: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Ifg 029 Informationszugang Niedersachsen Livec, Ifg 030 Informationszugang Nordrhein Westfalen, Ifg 031 Informationszugang Rheinland Pfalz L... |
| `kompendium-12-ifg-033-informations-bis-ifg-036-informations` | informationsfreiheit-presseauskunft: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Ifg 033 Informationszugang Sachsen Livecheck, Ifg 034 Informationszugang Sachsen Anhalt Live, Ifg 035 Informationszugang Schleswig Holstein,... |
| `kompendium-13-ifg-037-ifg-bund-ant-bis-ifg-042-ifg-bund-dri` | informationsfreiheit-presseauskunft: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Ifg 037 Ifg Bund Antrag Formulieren, Ifg 040 Ifg Bund Kosten Deckeln, Ifg 041 Ifg Bund Schwaerzung Angreifen, Ifg 042 Ifg Bund Drittanhoerun... |
| `kompendium-14-ifg-043-ifg-bund-wid-bis-ifg-046-ifg-bund-tra` | informationsfreiheit-presseauskunft: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Ifg 043 Ifg Bund Widerspruch Bauen, Ifg 044 Ifg Bund Klage Vorbereiten, Ifg 045 Ifg Bund Presseantwort Nachfassen, Ifg 046 Ifg Bund Tracking... |
| `kompendium-15-ifg-047-ifggebv-gebu-bis-ifg-052-ifggebv-gebu` | informationsfreiheit-presseauskunft: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Ifg 047 Ifggebv Gebuehren Antrag Formulieren, Ifg 050 Ifggebv Gebuehren Kosten Deckeln, Ifg 051 Ifggebv Gebuehren Schwaerzung Angreife, Ifg... |
| `kompendium-16-ifg-053-ifggebv-gebu-bis-ifg-056-ifggebv-gebu` | informationsfreiheit-presseauskunft: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Ifg 053 Ifggebv Gebuehren Widerspruch Bauen, Ifg 054 Ifggebv Gebuehren Klage Vorbereiten, Ifg 055 Ifggebv Gebuehren Presseantwort Nachfa, If... |
| `kompendium-17-ifg-057-uig-umweltin-bis-ifg-062-uig-umweltin` | informationsfreiheit-presseauskunft: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Ifg 057 Uig Umweltinformation Antrag Formulier, Ifg 060 Uig Umweltinformation Kosten Deckeln, Ifg 061 Uig Umweltinformation Schwaerzung Angr... |
| `kompendium-18-ifg-063-uig-umweltin-bis-ifg-066-uig-umweltin` | informationsfreiheit-presseauskunft: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Ifg 063 Uig Umweltinformation Widerspruch Baue, Ifg 064 Uig Umweltinformation Klage Vorbereite, Ifg 065 Uig Umweltinformation Presseantwort... |
| `kompendium-19-ifg-067-vig-lebensmi-bis-ifg-071-vig-lebensmi` | informationsfreiheit-presseauskunft: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Ifg 067 Vig Lebensmittel Und Produkte Antrag F, Ifg 068 Vig Lebensmittel Und Produkte Zustaend, Ifg 070 Vig Lebensmittel Und Produkte Kosten... |
| `kompendium-20-ifg-072-vig-lebensmi-bis-ifg-075-vig-lebensmi` | informationsfreiheit-presseauskunft: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Ifg 072 Vig Lebensmittel Und Produkte Drittanh, Ifg 073 Vig Lebensmittel Und Produkte Widerspr, Ifg 074 Vig Lebensmittel Und Produkte Klage... |
| `kompendium-21-ifg-076-vig-lebensmi-bis-ifg-081-landespresse` | informationsfreiheit-presseauskunft: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Ifg 076 Vig Lebensmittel Und Produkte Tracking, Ifg 077 Landespressegesetz Antrag Formulieren, Ifg 080 Landespressegesetz Kosten Deckeln, If... |
| `kompendium-22-ifg-082-landespresse-bis-ifg-085-landespresse` | informationsfreiheit-presseauskunft: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Ifg 082 Landespressegesetz Drittanhoerung Begl, Ifg 083 Landespressegesetz Widerspruch Bauen, Ifg 084 Landespressegesetz Klage Vorbereiten,... |
| `kompendium-23-ifg-086-landespresse-bis-ifg-091-transparenzg` | informationsfreiheit-presseauskunft: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Ifg 086 Landespressegesetz Tracking Aktualisie, Ifg 087 Transparenzgesetz Antrag Formulieren, Ifg 090 Transparenzgesetz Kosten Deckeln, Ifg... |
| `kompendium-24-ifg-092-transparenzg-bis-ifg-095-transparenzg` | informationsfreiheit-presseauskunft: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Ifg 092 Transparenzgesetz Drittanhoerung Begle, Ifg 093 Transparenzgesetz Widerspruch Bauen, Ifg 094 Transparenzgesetz Klage Vorbereiten, If... |
| `kompendium-25-ifg-096-transparenzg-bis-ifg-097-archivrecht` | informationsfreiheit-presseauskunft: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Ifg 096 Transparenzgesetz Tracking Aktualisier, Ifg 097 Archivrecht Antrag Formulieren; mit Intake, Prüfroutine, Normen-/Quellenradar, Bewei... |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
