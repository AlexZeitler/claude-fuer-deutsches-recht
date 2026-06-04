# Verbraucherschutzrecht Prüfer

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`verbraucherschutzrecht-pruefer`) | [`verbraucherschutzrecht-pruefer.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/verbraucherschutzrecht-pruefer.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **Verbraucherakte SmartMeter-Abo** (`verbraucherschutzrecht-smartmeter-abo-plattform`) | [Gesamt-PDF lesen](../testakten/verbraucherschutzrecht-smartmeter-abo-plattform/gesamt-pdf/verbraucherschutzrecht-smartmeter-abo-plattform_gesamt.pdf) | [`testakte-verbraucherschutzrecht-smartmeter-abo-plattform.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-verbraucherschutzrecht-smartmeter-abo-plattform.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

<!-- BEGIN TESTAKTEN-SECTION (auto-generated) -->

## Testakte

Zu diesem Plugin existiert eine vollständige Beispielakte: **Verbraucherakte SmartMeter-Abo** ([`testakten/verbraucherschutzrecht-smartmeter-abo-plattform/`](../testakten/verbraucherschutzrecht-smartmeter-abo-plattform/)).

Direkt-Download als ZIP: [testakte-verbraucherschutzrecht-smartmeter-abo-plattform.zip](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-verbraucherschutzrecht-smartmeter-abo-plattform.zip)

Die Akte ist absichtlich unordentlich, widersprüchlich und ungefiltert. Sie eignet sich für End-to-End-Tests, Demos und zum Üben.

<!-- END TESTAKTEN-SECTION (auto-generated) -->

Dieses Plugin prüft verbraucherschützende Vorschriften nicht als lose Sammlung, sondern als Schutzarchitektur: Informationspflicht, Widerruf, AGB-Kontrolle, Gewährleistung, Lauterkeit, Streitbeilegung, Plattform und Durchsetzung.

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

Automatisch generierte Komplett-Liste aller 30 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `allgemein` | Verbraucherschutzrecht Prüfer: Kaltstart, Aktenlandkarte, Rollenklärung, Fristen, Quellenprüfung, Spezialskill-Routing und erste Ausgabe. |
| `kompendium-01-vbr-023-haustuergesc-bis-vbr-053-marketplace` | verbraucherschutzrecht-pruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Vbr 023 Haustuergeschaeft Frist Berechnen, Vbr 033 Fernabsatz Frist Berechnen, Vbr 043 Online Shop Frist Berechnen, Vbr 053 Marketplace Frist Ber... |
| `kompendium-02-vbr-063-abo-falle-fr-bis-vbr-093-smart-device` | verbraucherschutzrecht-pruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Vbr 063 Abo Falle Frist Berechnen, Vbr 073 Digitale Inhalte Frist Berechnen, Vbr 083 Saas Fuer Verbraucher Frist Berechnen, Vbr 093 Smart Device... |
| `kompendium-03-vbr-006-agb-klausel-bis-vbr-002-verbraucher` | verbraucherschutzrecht-pruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Vbr 006 Agb Klausel Im Verbrauchervertrag Prue, Vbr 016 Energievertrag Und Abschlag, Vbr 019 Gesundheit Und Pflegevertrag, Vbr 002 Verbraucher Od... |
| `kompendium-04-vbr-003-unternehmerr-bis-vbr-007-digitale-pro` | verbraucherschutzrecht-pruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Vbr 003 Unternehmerrolle Und Plattformrolle Pr, Vbr 004 Informationspflichten Matrix Bauen, Vbr 005 Widerrufsrecht Und Erloeschen Pruefen, Vbr 00... |
| `kompendium-05-vbr-008-waren-mit-di-bis-vbr-011-schlichtung` | verbraucherschutzrecht-pruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Vbr 008 Waren Mit Digitalen Elementen, Vbr 009 Preisangaben Und Dark Patterns, Vbr 010 Uwg Irrefuehrung Verbraucherbezug, Vbr 011 Schlichtung Und... |
| `kompendium-06-vbr-012-inkasso-und-bis-vbr-015-reise-und-fl` | verbraucherschutzrecht-pruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Vbr 012 Inkasso Und Mahnung Einordnen, Vbr 013 Gewaehrleistung Und Garantie Trennen, Vbr 014 Kaufrecht Reparatur Und Right To Repai, Vbr 015 Reis... |
| `kompendium-07-vbr-017-telekommunik-bis-vbr-021-haustuergesc` | verbraucherschutzrecht-pruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Vbr 017 Telekommunikation Und Laufzeit, Vbr 018 Finanzdienstleistung Fernabsatz, Vbr 020 Verbraucherbericht Erzeugen, Vbr 021 Haustuergeschaeft A... |
| `kompendium-08-vbr-022-haustuergesc-bis-vbr-026-haustuergesc` | verbraucherschutzrecht-pruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Vbr 022 Haustuergeschaeft Widerruf Formulieren, Vbr 024 Haustuergeschaeft Beweise Sichern, Vbr 025 Haustuergeschaeft Agb Redlinen, Vbr 026 Haustu... |
| `kompendium-09-vbr-027-haustuergesc-bis-vbr-030-haustuergesc` | verbraucherschutzrecht-pruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Vbr 027 Haustuergeschaeft Schlichtung Waehlen, Vbr 028 Haustuergeschaeft Klagepfad Skizzieren, Vbr 029 Haustuergeschaeft Vergleich Vorschlage, Vb... |
| `kompendium-10-vbr-031-fernabsatz-a-bis-vbr-035-fernabsatz-a` | verbraucherschutzrecht-pruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Vbr 031 Fernabsatz Anspruch Pruefen, Vbr 032 Fernabsatz Widerruf Formulieren, Vbr 034 Fernabsatz Beweise Sichern, Vbr 035 Fernabsatz Agb Redlinen... |
| `kompendium-11-vbr-036-fernabsatz-b-bis-vbr-039-fernabsatz-v` | verbraucherschutzrecht-pruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Vbr 036 Fernabsatz Beschwerde Schreiben, Vbr 037 Fernabsatz Schlichtung Waehlen, Vbr 038 Fernabsatz Klagepfad Skizzieren, Vbr 039 Fernabsatz Verg... |
| `kompendium-12-vbr-040-fernabsatz-b-bis-vbr-044-online-shop` | verbraucherschutzrecht-pruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Vbr 040 Fernabsatz Behoerdenmeldung Pruefen, Vbr 041 Online Shop Anspruch Pruefen, Vbr 042 Online Shop Widerruf Formulieren, Vbr 044 Online Shop... |
| `kompendium-13-vbr-045-online-shop-bis-vbr-048-online-shop` | verbraucherschutzrecht-pruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Vbr 045 Online Shop Agb Redlinen, Vbr 046 Online Shop Beschwerde Schreiben, Vbr 047 Online Shop Schlichtung Waehlen, Vbr 048 Online Shop Klagepfa... |
| `kompendium-14-vbr-049-online-shop-bis-vbr-052-marketplace` | verbraucherschutzrecht-pruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Vbr 049 Online Shop Vergleich Vorschlagen, Vbr 050 Online Shop Behoerdenmeldung Pruefen, Vbr 051 Marketplace Anspruch Pruefen, Vbr 052 Marketplac... |
| `kompendium-15-vbr-054-marketplace-bis-vbr-057-marketplace` | verbraucherschutzrecht-pruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Vbr 054 Marketplace Beweise Sichern, Vbr 055 Marketplace Agb Redlinen, Vbr 056 Marketplace Beschwerde Schreiben, Vbr 057 Marketplace Schlichtung... |
| `kompendium-16-vbr-058-marketplace-bis-vbr-061-abo-falle-an` | verbraucherschutzrecht-pruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Vbr 058 Marketplace Klagepfad Skizzieren, Vbr 059 Marketplace Vergleich Vorschlagen, Vbr 060 Marketplace Behoerdenmeldung Pruefen, Vbr 061 Abo Fa... |
| `kompendium-17-vbr-062-abo-falle-wi-bis-vbr-066-abo-falle-be` | verbraucherschutzrecht-pruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Vbr 062 Abo Falle Widerruf Formulieren, Vbr 064 Abo Falle Beweise Sichern, Vbr 065 Abo Falle Agb Redlinen, Vbr 066 Abo Falle Beschwerde Schreiben... |
| `kompendium-18-vbr-067-abo-falle-sc-bis-vbr-070-abo-falle-be` | verbraucherschutzrecht-pruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Vbr 067 Abo Falle Schlichtung Waehlen, Vbr 068 Abo Falle Klagepfad Skizzieren, Vbr 069 Abo Falle Vergleich Vorschlagen, Vbr 070 Abo Falle Behoerd... |
| `kompendium-19-vbr-071-digitale-inh-bis-vbr-075-digitale-inh` | verbraucherschutzrecht-pruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Vbr 071 Digitale Inhalte Anspruch Pruefen, Vbr 072 Digitale Inhalte Widerruf Formulieren, Vbr 074 Digitale Inhalte Beweise Sichern, Vbr 075 Digit... |
| `kompendium-20-vbr-076-digitale-inh-bis-vbr-079-digitale-inh` | verbraucherschutzrecht-pruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Vbr 076 Digitale Inhalte Beschwerde Schreiben, Vbr 077 Digitale Inhalte Schlichtung Waehlen, Vbr 078 Digitale Inhalte Klagepfad Skizzieren, Vbr 0... |
| `kompendium-21-vbr-080-digitale-inh-bis-vbr-084-saas-fuer-ve` | verbraucherschutzrecht-pruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Vbr 080 Digitale Inhalte Behoerdenmeldung Prue, Vbr 081 Saas Fuer Verbraucher Anspruch Pruefen, Vbr 082 Saas Fuer Verbraucher Widerruf Formuli, V... |
| `kompendium-22-vbr-085-saas-fuer-ve-bis-vbr-088-saas-fuer-ve` | verbraucherschutzrecht-pruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Vbr 085 Saas Fuer Verbraucher Agb Redlinen, Vbr 086 Saas Fuer Verbraucher Beschwerde Schre, Vbr 087 Saas Fuer Verbraucher Schlichtung Waeh, Vbr 0... |
| `kompendium-23-vbr-089-saas-fuer-ve-bis-vbr-092-smart-device` | verbraucherschutzrecht-pruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Vbr 089 Saas Fuer Verbraucher Vergleich Vorsch, Vbr 090 Saas Fuer Verbraucher Behoerdenmeldung, Vbr 091 Smart Device Anspruch Pruefen, Vbr 092 Sm... |
| `kompendium-24-vbr-094-smart-device-bis-vbr-097-smart-device` | verbraucherschutzrecht-pruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Vbr 094 Smart Device Beweise Sichern, Vbr 095 Smart Device Agb Redlinen, Vbr 096 Smart Device Beschwerde Schreiben, Vbr 097 Smart Device Schlicht... |
| `kompendium-25-vbr-098-smart-device-bis-verbraucherrecht-beh` | verbraucherschutzrecht-pruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Vbr 098 Smart Device Klagepfad Skizzieren, Vbr 099 Smart Device Vergleich Vorschlagen, Verbraucherrecht Abo Kuendigung Button, Verbraucherrecht B... |
| `kompendium-26-verbraucherrecht-dig-bis-verbraucherrecht-pla` | verbraucherschutzrecht-pruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Verbraucherrecht Digitale Produkte 327 Bgb, Verbraucherrecht Energie Smartmeter Waerme, Verbraucherrecht Finanzdienstleistung Online, Verbraucher... |
| `kompendium-27-verbraucherrecht-pre-bis-verbraucherrecht-ver` | verbraucherschutzrecht-pruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Verbraucherrecht Preisangaben Und Dark Patterns, Verbraucherrecht Reise Flug Pauschal, Verbraucherrecht Right To Repair, Verbraucherrecht Verband... |
| `kompendium-28-verbraucherrecht-war-bis-verbraucherrecht-wid` | verbraucherschutzrecht-pruefer: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Verbraucherrecht Waren Mit Digitalen Elementen, Verbraucherrecht Widerruf Fernabsatz; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik,... |
| `vbr-001-kaltstart-verbraucherfall-sortieren` | Verbraucherschutzrecht Prüfer: Kaltstart Verbraucherfall sortieren. Kaltstart Verbraucherfall sortieren im Fachgebiet Verbraucherschutzrecht Prüfer als geführten Arbeitsgang mit Fragen, Dokumentenlogik und Ausgabeformat bearbeiten. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
