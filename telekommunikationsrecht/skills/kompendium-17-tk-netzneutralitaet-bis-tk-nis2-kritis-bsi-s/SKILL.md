---
name: kompendium-17-tk-netzneutralitaet-bis-tk-nis2-kritis-bsi-s
description: "telekommunikationsrecht: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Tk Netzneutralitaet Zero Rating Throttling, Tk Nis2 Kritis Bsi Schnittstelle; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck."
---

# Arbeitsbereich - Tk Netzneutralitaet Zero Rating Throttling, Tk Nis2 Kritis Bsi Schnittstelle

## Zweck

Dieser Skill ist ein eigenständiger Arbeitsbereich. Er verbindet mehrere sachlich benachbarte Arbeitsmodule, Wähle anhand des Sachverhalts das passende Modul, arbeite dessen Prüfroutine vollständig ab und kombiniere Module nur, wenn der Fall tatsächlich mehrere Themen berührt.

## Arbeitsmodule

| Arbeitsmodul | Fokus |
| --- | --- |
| `tk-netzneutralitaet-zero-rating-throttling` | Netzneutralität: Zero-Rating, Priorisierung, Drosselung, Spezialdienste, Traffic Management und Beschwerde-/Abmahnrisiken. |
| `tk-nis2-kritis-bsi-schnittstelle` | NIS2/KRITIS/BSI-Anforderungen für TK-Unternehmen, Rechenzentren, Managed Services und kritische Kommunikation. |

## Arbeitsregel

1. Zuerst das passende Arbeitsmodul oder Sachthema auswählen.
2. Danach die dortige Prüfroutine, Normen-/Quellenanker, Beweislogik und Output-Vorgabe vollständig anwenden.
3. Bei mehreren passenden Arbeitsmodulen eine kurze Synopse bilden, Überschneidungen offen markieren und nichts vermischen, was getrennte Fristen, Zuständigkeiten, Anspruchsgrundlagen oder Beweislasten hat.
4. Rechtsprechung, Literatur, Behördenpraxis und Tagesrecht nur mit überprüfbarer Quelle oder Nutzerquelle ausgeben.

## Arbeitsmodule im Detail

## 1. `tk-netzneutralitaet-zero-rating-throttling`

**Fokus:** Netzneutralität: Zero-Rating, Priorisierung, Drosselung, Spezialdienste, Traffic Management und Beschwerde-/Abmahnrisiken.

# Netzneutralität, Zero-Rating und Drosselung

## Einsatz

Für Anbieterprodukte und Beschwerden, wenn Datenverkehr unterschiedlich behandelt wird.

## Norm- und Quellenanker

EU-Verordnung 2015/2120; TKG; BEREC-Leitlinien live prüfen; UWG/GWB-Schnittstelle.

## Arbeitsfragen

1. Welche Verkehrsbehandlung unterscheidet wen oder was?
2. Ist sie technisch notwendig, diskriminierend oder tariflich gesteuert?
3. Gibt es Spezialdienst oder Netzmanagement?
4. Welche BNetzA-/BEREC-Linie ist live zu prüfen?

## Output

Netzneutralitätsprüfung, Produkt-Redline, BNetzA-Risiko und Kundenkommunikation.

## Red Flags

- Marketingtarif vor Rechtsprüfung
- Drosselung nach App-Kategorie
- Spezialdienst ohne Kapazitätsnachweis
- BEREC-Leitlinien nicht geprüft

## Anschluss-Skills

- tk-eu-eecc-router
- tk-missbrauchsaufsicht-sonderkartellrecht

## Qualitätsregel

Keine Rechtsweg- oder Normbehauptung aus dem Bauch heraus. Bei Streit mit der Bundesnetzagentur immer Bescheid, Norm, Tenor, Nebenbestimmungen und Rechtsbehelfsbelehrung lesen; bei Verbraucherfällen Vertrag, Leistungsbeschreibung, Messprotokoll und Anbieterkommunikation trennen.

## 2. `tk-nis2-kritis-bsi-schnittstelle`

**Fokus:** NIS2/KRITIS/BSI-Anforderungen für TK-Unternehmen, Rechenzentren, Managed Services und kritische Kommunikation.

# NIS2, KRITIS und BSI-Schnittstelle

## Einsatz

Für Unternehmen, die TK- oder digitale Infrastruktur betreiben.

## Norm- und Quellenanker

NIS2; BSI-Gesetz; TKG; DORA bei Finanzkunden.

## Arbeitsfragen

1. Ist die Einheit erfasst?
2. Welche technischen und organisatorischen Maßnahmen?
3. Welche Leitungsorganpflichten?

## Output

NIS2-Gap-Analyse und Maßnahmenplan.

## Red Flags

- Schwellenwerte ungeprüft
- Geschäftsführung nicht eingebunden
- Lieferkette vergessen

## Anschluss-Skills

- Starte wieder mit `tk-allgemeiner-kaltstart`, wenn Rechtsweg, Rolle oder Bescheid noch unklar sind.

## Qualitätsregel

Keine Rechtsweg- oder Normbehauptung aus dem Bauch heraus. Bei Streit mit der Bundesnetzagentur immer Bescheid, Norm, Tenor, Nebenbestimmungen und Rechtsbehelfsbelehrung lesen; bei Verbraucherfällen Vertrag, Leistungsbeschreibung, Messprotokoll und Anbieterkommunikation trennen.
