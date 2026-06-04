# Luftrecht und Flughafenrecht

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`luftrecht-flughafenrecht`) | [`luftrecht-flughafenrecht.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/luftrecht-flughafenrecht.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **Luftrechtsakte** (`luftrecht-airline-insolvenz-flugzeugpfand-flughafen`) | [Gesamt-PDF lesen](../testakten/luftrecht-airline-insolvenz-flugzeugpfand-flughafen/gesamt-pdf/luftrecht-airline-insolvenz-flugzeugpfand-flughafen_gesamt.pdf) | [`testakte-luftrecht-airline-insolvenz-flugzeugpfand-flughafen.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-luftrecht-airline-insolvenz-flugzeugpfand-flughafen.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

Dieses Plugin deckt ziviles und öffentliches Luftrecht ab: Luftfahrzeug, Flughafen, Betriebsgenehmigung, LBA, Luftsicherheit, Slots, Flugzeugfinanzierung, Registerpfandrechte, Pfändung, Airline-Krise und internationale Bezüge.

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

Automatisch generierte Komplett-Liste aller 26 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `allgemein` | Luftrecht und Flughafenrecht: Kaltstart, Aktenlandkarte, Rollenklärung, Fristen, Quellenprüfung, Spezialskill-Routing und erste Ausgabe. |
| `kompendium-01-luft-003-lba-zustaen-bis-luft-051-registerpfa` | luftrecht-flughafenrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Luft 003 Lba Zustaendigkeit Pruefen, Luft 021 Airline Zustaendigkeit Pruefen, Luft 031 Flughafen Zustaendigkeit Pruefen, Luft 041 Flugzeugleasing Zusta... |
| `kompendium-02-luft-061-ersatzteill-bis-luft-101-slot-zustae` | luftrecht-flughafenrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Luft 061 Ersatzteillager Zustaendigkeit Pruefen, Luft 071 Drohne Zustaendigkeit Pruefen, Luft 081 Luftfracht Zustaendigkeit Pruefen, Luft 091 Acc3 Zust... |
| `kompendium-03-luft-111-bodenabfert-bis-luft-006-pfaendung-f` | luftrecht-flughafenrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Luft 111 Bodenabfertigung Zustaendigkeit Pruefe, Luft 002 Luftvg Anwendungsbereich, Luft 004 Flugzeugrolle Und Register, Luft 005 Luftfahrzeugpfandrech... |
| `kompendium-04-luft-007-aircraft-ar-bis-luft-011-slots-und-k` | luftrecht-flughafenrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Luft 007 Aircraft Arrest International, Luft 008 Airline Finanzielle Leistungsfaehigkei, Luft 009 Betriebsgenehmigung Airline, Luft 010 Flughafen Planf... |
| `kompendium-05-luft-012-luftsicherh-bis-luft-016-passagierre` | luftrecht-flughafenrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Luft 012 Luftsicherheit Luftsig, Luft 013 Zuverlaessigkeitsueberpruefung, Luft 014 Drohnen Uas Betrieb, Luft 015 Gefahrgut Luftfracht und 1 weitere Arb... |
| `kompendium-06-luft-017-fluglaerm-u-bis-luft-022-airline-reg` | luftrecht-flughafenrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Luft 017 Fluglaerm Und Anwohner, Luft 018 Insolvenz Fluggesellschaft, Luft 019 Leasing Und Cape Town Bezuege, Luft 020 Aviation Dashboard und 1 weitere... |
| `kompendium-07-luft-023-airline-pfa-bis-luft-027-airline-ins` | luftrecht-flughafenrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Luft 023 Airline Pfandrecht Vorbereiten, Luft 024 Airline Pfaendung Planen, Luft 025 Airline Genehmigung Pruefen, Luft 026 Airline Sicherheitsauflage B... |
| `kompendium-08-luft-028-airline-loc-bis-luft-033-flughafen-p` | luftrecht-flughafenrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Luft 028 Airline Local Counsel Briefen, Luft 029 Airline Dashboard Bauen, Luft 030 Airline Mandantenmemo Schreiben, Luft 032 Flughafen Register Auswert... |
| `kompendium-09-luft-034-flughafen-p-bis-luft-038-flughafen-l` | luftrecht-flughafenrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Luft 034 Flughafen Pfaendung Planen, Luft 035 Flughafen Genehmigung Pruefen, Luft 036 Flughafen Sicherheitsauflage Bewerten, Luft 037 Flughafen Insolve... |
| `kompendium-10-luft-039-flughafen-d-bis-luft-044-flugzeuglea` | luftrecht-flughafenrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Luft 039 Flughafen Dashboard Bauen, Luft 040 Flughafen Mandantenmemo Schreiben, Luft 042 Flugzeugleasing Register Auswerten, Luft 043 Flugzeugleasing P... |
| `kompendium-11-luft-045-flugzeuglea-bis-luft-049-flugzeuglea` | luftrecht-flughafenrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Luft 045 Flugzeugleasing Genehmigung Pruefen, Luft 046 Flugzeugleasing Sicherheitsauflage Bew, Luft 047 Flugzeugleasing Insolvenzrisiko Markie, Luft 04... |
| `kompendium-12-luft-050-flugzeuglea-bis-luft-055-registerpfa` | luftrecht-flughafenrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Luft 050 Flugzeugleasing Mandantenmemo Schreibe, Luft 052 Registerpfandrecht Register Auswerten, Luft 053 Registerpfandrecht Pfandrecht Vorberei, Luft... |
| `kompendium-13-luft-056-registerpfa-bis-luft-060-registerpfa` | luftrecht-flughafenrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Luft 056 Registerpfandrecht Sicherheitsauflage, Luft 057 Registerpfandrecht Insolvenzrisiko Mar, Luft 058 Registerpfandrecht Local Counsel Brief, Luft... |
| `kompendium-14-luft-062-ersatzteill-bis-luft-066-ersatzteill` | luftrecht-flughafenrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Luft 062 Ersatzteillager Register Auswerten, Luft 063 Ersatzteillager Pfandrecht Vorbereiten, Luft 064 Ersatzteillager Pfaendung Planen, Luft 065 Ersat... |
| `kompendium-15-luft-067-ersatzteill-bis-luft-072-drohne-regi` | luftrecht-flughafenrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Luft 067 Ersatzteillager Insolvenzrisiko Markie, Luft 068 Ersatzteillager Local Counsel Briefen, Luft 069 Ersatzteillager Dashboard Bauen, Luft 070 Ers... |
| `kompendium-16-luft-073-drohne-pfan-bis-luft-077-drohne-inso` | luftrecht-flughafenrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Luft 073 Drohne Pfandrecht Vorbereiten, Luft 074 Drohne Pfaendung Planen, Luft 075 Drohne Genehmigung Pruefen, Luft 076 Drohne Sicherheitsauflage Bewer... |
| `kompendium-17-luft-078-drohne-loca-bis-luft-083-luftfracht` | luftrecht-flughafenrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Luft 078 Drohne Local Counsel Briefen, Luft 079 Drohne Dashboard Bauen, Luft 080 Drohne Mandantenmemo Schreiben, Luft 082 Luftfracht Register Auswerten... |
| `kompendium-18-luft-084-luftfracht-bis-luft-088-luftfracht` | luftrecht-flughafenrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Luft 084 Luftfracht Pfaendung Planen, Luft 085 Luftfracht Genehmigung Pruefen, Luft 086 Luftfracht Sicherheitsauflage Bewerten, Luft 087 Luftfracht Ins... |
| `kompendium-19-luft-089-luftfracht-bis-luft-094-acc3-pfaend` | luftrecht-flughafenrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Luft 089 Luftfracht Dashboard Bauen, Luft 090 Luftfracht Mandantenmemo Schreiben, Luft 092 Acc3 Register Auswerten, Luft 093 Acc3 Pfandrecht Vorbereite... |
| `kompendium-20-luft-095-acc3-genehm-bis-luft-099-acc3-dashbo` | luftrecht-flughafenrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Luft 095 Acc3 Genehmigung Pruefen, Luft 096 Acc3 Sicherheitsauflage Bewerten, Luft 097 Acc3 Insolvenzrisiko Markieren, Luft 098 Acc3 Local Counsel Brie... |
| `kompendium-21-luft-100-acc3-mandan-bis-luft-105-slot-genehm` | luftrecht-flughafenrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Luft 100 Acc3 Mandantenmemo Schreiben, Luft 102 Slot Register Auswerten, Luft 103 Slot Pfandrecht Vorbereiten, Luft 104 Slot Pfaendung Planen und 1 wei... |
| `kompendium-22-luft-106-slot-sicher-bis-luft-110-slot-mandan` | luftrecht-flughafenrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Luft 106 Slot Sicherheitsauflage Bewerten, Luft 107 Slot Insolvenzrisiko Markieren, Luft 108 Slot Local Counsel Briefen, Luft 109 Slot Dashboard Bauen... |
| `kompendium-23-luft-112-bodenabfert-bis-luft-116-bodenabfert` | luftrecht-flughafenrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Luft 112 Bodenabfertigung Register Auswerten, Luft 113 Bodenabfertigung Pfandrecht Vorbereite, Luft 114 Bodenabfertigung Pfaendung Planen, Luft 115 Bod... |
| `kompendium-24-luft-117-bodenabfert-bis-luft-119-bodenabfert` | luftrecht-flughafenrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Luft 117 Bodenabfertigung Insolvenzrisiko Marki, Luft 118 Bodenabfertigung Local Counsel Briefen, Luft 119 Bodenabfertigung Dashboard Bauen; mit Intake... |
| `luft-001-kaltstart-luftrechtsmandat` | 'Mandant erscheint erstmals mit Luftrechtsfall: Airline-Insolvenz Flugzeugbeschlagnahme Slot-Verlust oder Planfeststellungsklage. Klaert Zustaendigkeit LBA vs. Landesbehoerde vs. Gericht sichert Fristen LuftVG §§ 20 ff. und EU-Recht und... |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
