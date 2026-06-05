# Ordnungswidrigkeitenrecht

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`ordnungswidrigkeitenrecht`) | [`ordnungswidrigkeitenrecht.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/ordnungswidrigkeitenrecht.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **OWiG-Akte** (`ordnungswidrigkeitenrecht-bussgeldmix-gewerbe-datenschutz-tier`) | [Gesamt-PDF lesen](../testakten/ordnungswidrigkeitenrecht-bussgeldmix-gewerbe-datenschutz-tier/gesamt-pdf/ordnungswidrigkeitenrecht-bussgeldmix-gewerbe-datenschutz-tier_gesamt.pdf) | [`testakte-ordnungswidrigkeitenrecht-bussgeldmix-gewerbe-datenschutz-tier.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-ordnungswidrigkeitenrecht-bussgeldmix-gewerbe-datenschutz-tier.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

Dieses Plugin ist das allgemeine Betriebssystem für Bußgeldsachen, nicht nur Verkehr: OWiG-Verfahren, Fachordnungswidrigkeiten, Anhörung, Bußgeldbescheid, Einspruch, Akteneinsicht, Amtsgericht und Rechtsbeschwerde.

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
| `allgemein` | Ordnungswidrigkeitenrecht: Kaltstart, Aktenlandkarte, Rollenklärung, Fristen, Quellenprüfung, Spezialskill-Routing und erste Ausgabe. |
| `owi-001-kaltstart-bussgeldverfahren` | Ordnungswidrigkeitenrecht: Kaltstart Bußgeldverfahren. Kaltstart Bußgeldverfahren im Fachgebiet Ordnungswidrigkeitenrecht als geführten Arbeitsgang mit Fragen, Dokumentenlogik und Ausgabeformat bearbeiten. |
| `owi-akteneinsicht-owi-verjaehrung-owi-zustaendige-owi` | Owi 006 Akteneinsicht Beantragen, Owi 007 Verjaehrung Und Unterbrechung, Owi 008 Zustaendige Verwaltungsbehoerde, Owi 009 Opportunitaet Und Einstellung: Owi 006 Akteneinsicht Beantragen; Owi 007 Verjaehrung Und Unterbrechung; Owi 008 Zus... |
| `owi-amtsgericht-hauptverhandlung-rechtsbeschwerde-owig-einfacher` | Owi 015 Amtsgericht Hauptverhandlung, Owi 017 Rechtsbeschwerde Prüfen, Owi 018 Kostenentscheidung Angreifen, Owi 020 Owig In Einfacher Sprache: Owi 015 Amtsgericht Hauptverhandlung; Owi 017 Rechtsbeschwerde Prüfen; Owi 018 Kostenentschei... |
| `owi-aussenwirtschaft-einspruch-einstellung-anregen-ruegen` | Owi 094 Aussenwirtschaft Einspruch Begruenden, Owi 095 Aussenwirtschaft Einstellung Anregen, Owi 096 Aussenwirtschaft Beweis Ruegen, Owi 097 Aussenwirtschaft Verjaehrung Berechnen: Owi 094 Aussenwirtschaft Einspruch Begruenden; Owi 095 A... |
| `owi-aussenwirtschaft-owi-aussenwirtschaft` | Owi 098 Aussenwirtschaft Gerichtstermin Vorber, Owi 099 Aussenwirtschaft Rechtsbeschwerde Prue: Owi 098 Aussenwirtschaft Gerichtstermin Vorber; Owi 099 Aussenwirtschaft Rechtsbeschwerde Prue. Führt Intake, Prüfroutine, Normen-/Quellenrad... |
| `owi-baurecht-owi-strassenverkehr-owi-aussenwirtschaft-owi` | Owi 072 Baurecht Frist Prüfen, Owi 082 Strassenverkehr Frist Prüfen, Owi 092 Aussenwirtschaft Frist Prüfen, Owi 004 Bussgeldbescheid Prüfen: Owi 072 Baurecht Frist Prüfen; Owi 082 Strassenverkehr Frist Prüfen; Owi 092 Aussenwirtschaft Fr... |
| `owi-baurecht-owi-strassenverkehr-owi-strassenverkehr-owi` | Owi 080 Baurecht Mandantenbrief Schreiben, Owi 081 Strassenverkehr Tatbestand Zerlegen, Owi 083 Strassenverkehr Akteneinsicht Schreibe, Owi 084 Strassenverkehr Einspruch Begruenden: Owi 080 Baurecht Mandantenbrief Schreiben; Owi 081 Stra... |
| `owi-baurecht-ruegen-verjaehrung-berechnen-gerichtstermin` | Owi 076 Baurecht Beweis Ruegen, Owi 077 Baurecht Verjaehrung Berechnen, Owi 078 Baurecht Gerichtstermin Vorbereiten, Owi 079 Baurecht Rechtsbeschwerde Prüfen: Owi 076 Baurecht Beweis Ruegen; Owi 077 Baurecht Verjaehrung Berechnen; Owi 07... |
| `owi-baurecht-zerlegen-akteneinsicht-schreiben-einspruch` | Owi 071 Baurecht Tatbestand Zerlegen, Owi 073 Baurecht Akteneinsicht Schreiben, Owi 074 Baurecht Einspruch Begruenden, Owi 075 Baurecht Einstellung Anregen: Owi 071 Baurecht Tatbestand Zerlegen; Owi 073 Baurecht Akteneinsicht Schreiben;... |
| `owi-datenschutzbussgeld-mandantenbrief-abgabe-an-fachgesetz` | Owi 030 Datenschutzbussgeld Mandantenbrief Sch, Owi 014 Abgabe An Staatsanwaltschaft, Owi 002 Tatbestand Fachgesetz Finden, Owi 003 Anhoerung Richtig Behandeln: Owi 030 Datenschutzbussgeld Mandantenbrief Sch; Owi 014 Abgabe An Staatsanwa... |
| `owi-datenschutzbussgeld-owi-datenschutzbussgeld-owi` | Owi 021 Datenschutzbussgeld Tatbestand Zerlege, Owi 023 Datenschutzbussgeld Akteneinsicht Schr, Owi 024 Datenschutzbussgeld Einspruch Begruend, Owi 025 Datenschutzbussgeld Einstellung Anrege: Owi 021 Datenschutzbussgeld Tatbestand Zerleg... |
| `owi-datenschutzbussgeld-owi-datenschutzbussgeld-owi-02` | Owi 026 Datenschutzbussgeld Beweis Ruegen, Owi 027 Datenschutzbussgeld Verjaehrung Berech, Owi 028 Datenschutzbussgeld Gerichtstermin Vor, Owi 029 Datenschutzbussgeld Rechtsbeschwerde P: Owi 026 Datenschutzbussgeld Beweis Ruegen; Owi 027... |
| `owi-einspruch-owi-beschlussverfahren-owi-jugendliche-owi` | Owi 005 Einspruch Fristgerecht Einlegen, Owi 016 Beschlussverfahren 72 Owig, Owi 019 Jugendliche Im Owi Verfahren, Owi 022 Datenschutzbussgeld Frist Prüfen: Owi 005 Einspruch Fristgerecht Einlegen; Owi 016 Beschlussverfahren 72 Owig; Owi... |
| `owi-gewerberecht-frist-umwelt-lebensmittelrecht-tierschutz` | Owi 032 Gewerberecht Frist Prüfen, Owi 042 Umwelt Owi Frist Prüfen, Owi 052 Lebensmittelrecht Frist Prüfen, Owi 062 Tierschutz Owi Frist Prüfen: Owi 032 Gewerberecht Frist Prüfen; Owi 042 Umwelt Owi Frist Prüfen; Owi 052 Lebensmittelrech... |
| `owi-gewerberecht-mandantenbrief-umwelt-zerlegen-akteneinsicht` | Owi 040 Gewerberecht Mandantenbrief Schreiben, Owi 041 Umwelt Owi Tatbestand Zerlegen, Owi 043 Umwelt Owi Akteneinsicht Schreiben, Owi 044 Umwelt Owi Einspruch Begruenden: Owi 040 Gewerberecht Mandantenbrief Schreiben; Owi 041 Umwelt Owi... |
| `owi-gewerberecht-ruegen-verjaehrung-berechnen-gerichtstermin` | Owi 036 Gewerberecht Beweis Ruegen, Owi 037 Gewerberecht Verjaehrung Berechnen, Owi 038 Gewerberecht Gerichtstermin Vorbereite, Owi 039 Gewerberecht Rechtsbeschwerde Prüfen: Owi 036 Gewerberecht Beweis Ruegen; Owi 037 Gewerberecht Verjae... |
| `owi-gewerberecht-zerlegen-akteneinsicht-schreiben-einspruch` | Owi 031 Gewerberecht Tatbestand Zerlegen, Owi 033 Gewerberecht Akteneinsicht Schreiben, Owi 034 Gewerberecht Einspruch Begruenden, Owi 035 Gewerberecht Einstellung Anregen: Owi 031 Gewerberecht Tatbestand Zerlegen; Owi 033 Gewerberecht A... |
| `owi-lebensmittelrecht-owi-lebensmittelrecht-owi` | Owi 054 Lebensmittelrecht Einspruch Begruenden, Owi 055 Lebensmittelrecht Einstellung Anregen, Owi 056 Lebensmittelrecht Beweis Ruegen, Owi 057 Lebensmittelrecht Verjaehrung Berechne: Owi 054 Lebensmittelrecht Einspruch Begruenden; Owi 0... |
| `owi-lebensmittelrecht-owi-lebensmittelrecht-owi-02` | Owi 058 Lebensmittelrecht Gerichtstermin Vorbe, Owi 059 Lebensmittelrecht Rechtsbeschwerde Pru, Owi 060 Lebensmittelrecht Mandantenbrief Schre, Owi 061 Tierschutz Owi Tatbestand Zerlegen: Owi 058 Lebensmittelrecht Gerichtstermin Vorbe; O... |
| `owi-strassenverkehr-einstellung-ruegen-verjaehrung-berechnen` | Owi 085 Strassenverkehr Einstellung Anregen, Owi 086 Strassenverkehr Beweis Ruegen, Owi 087 Strassenverkehr Verjaehrung Berechnen, Owi 088 Strassenverkehr Gerichtstermin Vorbere: Owi 085 Strassenverkehr Einstellung Anregen; Owi 086 Stras... |
| `owi-strassenverkehr-rechtsbeschwerde-mandantenbrief-schreib` | Owi 089 Strassenverkehr Rechtsbeschwerde Pruef, Owi 090 Strassenverkehr Mandantenbrief Schreib, Owi 091 Aussenwirtschaft Tatbestand Zerlegen, Owi 093 Aussenwirtschaft Akteneinsicht Schreib: Owi 089 Strassenverkehr Rechtsbeschwerde Pruef;... |
| `owi-tierschutz-akteneinsicht-einspruch-begruenden-einstellung` | Owi 063 Tierschutz Owi Akteneinsicht Schreiben, Owi 064 Tierschutz Owi Einspruch Begruenden, Owi 065 Tierschutz Owi Einstellung Anregen, Owi 066 Tierschutz Owi Beweis Ruegen: Owi 063 Tierschutz Owi Akteneinsicht Schreiben; Owi 064 Tiersc... |
| `owi-tierschutz-verjaehrung-gerichtstermin-vorberei` | Owi 067 Tierschutz Owi Verjaehrung Berechnen, Owi 068 Tierschutz Owi Gerichtstermin Vorberei, Owi 069 Tierschutz Owi Rechtsbeschwerde Pruefe, Owi 070 Tierschutz Owi Mandantenbrief Schreibe: Owi 067 Tierschutz Owi Verjaehrung Berechnen; O... |
| `owi-umwelt-einstellung-ruegen-verjaehrung-berechnen` | Owi 045 Umwelt Owi Einstellung Anregen, Owi 046 Umwelt Owi Beweis Ruegen, Owi 047 Umwelt Owi Verjaehrung Berechnen, Owi 048 Umwelt Owi Gerichtstermin Vorbereiten: Owi 045 Umwelt Owi Einstellung Anregen; Owi 046 Umwelt Owi Beweis Ruegen;... |
| `owi-umwelt-owi-umwelt-owi-lebensmittelrecht-owi` | Owi 049 Umwelt Owi Rechtsbeschwerde Prüfen, Owi 050 Umwelt Owi Mandantenbrief Schreiben, Owi 051 Lebensmittelrecht Tatbestand Zerlegen, Owi 053 Lebensmittelrecht Akteneinsicht Schrei: Owi 049 Umwelt Owi Rechtsbeschwerde Prüfen; Owi 050 U... |
| `owi-unternehmen-verbandsgeldbusse-aufsichtspflichtverletzung` | Owi 010 Unternehmen Und Verbandsgeldbusse, Owi 011 Aufsichtspflichtverletzung 130 Owig, Owi 012 Einziehung Und Verfall Prüfen, Owi 013 Nebenfolgen Und Register: Owi 010 Unternehmen Und Verbandsgeldbusse; Owi 011 Aufsichtspflichtverletzun... |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
