---
name: er-bess-epc-fca-agnes-finanzierung-bankability-kapazitaetsmarkt
description: "Er Bess Epc O And M Vertraege, Er Bess Fca Agnes Bnetza, Er Bess Finanzierung Bankability, Er Bess Kapazitaetsmarkt Grundlast: Er Bess Epc O And M Vertraege; Er Bess Fca Agnes Bnetza; Er Bess Finanzierung Bankability; Er Bess Kapazitaetsmarkt Grundlast. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zusammen."
---

# Er Bess Epc O And M Vertraege, Er Bess Fca Agnes Bnetza, Er Bess Finanzierung Bankability, Er Bess Kapazitaetsmarkt Grundlast

## Zweck

Dieser Skill ist ein eigenständiger Arbeitsbereich. Er verbindet mehrere sachlich benachbarte Arbeitsmodule. Wähle anhand des Sachverhalts das passende Modul, arbeite dessen Prüfroutine vollständig ab und kombiniere Module nur, wenn der Fall tatsächlich mehrere Themen berührt.

## Arbeitsmodule

| Arbeitsmodul | Fokus |
| --- | --- |
| `er-bess-epc-o-and-m-vertraege` | Prüft Bau-/Liefervertrag, O&M, Garantien, Degradation, Availability, LDs, Ersatzteile und Cyberpflichten. |
| `er-bess-fca-agnes-bnetza` | Prüft Netzanschlussdokumente nach BNetzA/Festlegungslogik und markiert, was im konkreten Vertrag fehlt. |
| `er-bess-finanzierung-bankability` | Prüft Projektfinanzierung, Sicherheiten, Erlösmodell, Netzanschlussrisiko, Bau-/Betriebsrisiko und Insurance DD. |
| `er-bess-kapazitaetsmarkt-grundlast` | Ordnet Aussagen zu Grundlast, gesicherter Leistung, Kapazitätsmarkt, Gaskraftwerken und Speicherfunktion rechtlich ein. |

## Arbeitsregel

1. Zuerst das passende Arbeitsmodul oder Sachthema auswählen.
2. Danach die dortige Prüfroutine, Normen-/Quellenanker, Beweislogik und Output-Vorgabe vollständig anwenden.
3. Bei mehreren passenden Arbeitsmodulen eine kurze Synopse bilden, Überschneidungen offen markieren und nichts vermischen, was getrennte Fristen, Zuständigkeiten, Anspruchsgrundlagen oder Beweislasten hat.
4. Rechtsprechung, Literatur, Behördenpraxis und Tagesrecht nur mit überprüfbarer Quelle oder Nutzerquelle ausgeben.

## Arbeitsmodule im Detail

## 1. `er-bess-epc-o-and-m-vertraege`

**Fokus:** Prüft Bau-/Liefervertrag, O&M, Garantien, Degradation, Availability, LDs, Ersatzteile und Cyberpflichten.

# EPC, O&M und Herstellerverträge

## Wofür dieser Skill da ist

Fokus auf Batteriespeicher-spezifische Vertragsrisiken.

## Rechts- und Praxisanker

BGB Werk-/Kaufrecht, Produktsicherheit, Garantie, Datenschutz/Cyber, Exportkontrolle.

## Workflow

1. Projektrolle und gewünschtes Ergebnis festlegen: Betreiber, Investor, Kommune, Netzbetreiber, Nachbar, Bank oder Behörde.
2. Standort, Technik, Netzebene, Leistung, Kapazität, Betriebsmodell und Dokumentenstand erfassen.
3. Genehmigungs-, Netz-, Sicherheits-, Markt- und Vertragsfragen in getrennte Spuren legen.
4. Rote Punkte mit Belegen, zuständiger Stelle, Frist und konkretem nächsten Dokument ausgeben.

## Output

- Risikomatrix
- Unterlagen- und Behördenliste
- Mandantenmemo oder Board-Paper-Baustein

## Qualitätsgate

- Keine Blindzitate: Rechtsprechung, Behördenpraxis und Schwellenwerte vor tragender Aussage live anhand amtlicher oder frei zugänglicher Quellen prüfen.
- Keine LMA-, Banken- oder Fondsformularsprache nacherzählen: Nutzer soll das aktuelle Dokument hochladen; der Skill arbeitet dann am konkreten Text.
- Jede Annahme sichtbar markieren, insbesondere Zahlen, Fristen, regulatorische Rollen, Genehmigungsstand und Parteiperspektive.

## 2. `er-bess-fca-agnes-bnetza`

**Fokus:** Prüft Netzanschlussdokumente nach BNetzA/Festlegungslogik und markiert, was im konkreten Vertrag fehlt.

# FCA/AgNes: Netzanschluss-Regelwerk lesen

## Wofür dieser Skill da ist

Der Skill arbeitet mit hochgeladenem Netzanschlussvertrag oder Entwurf und erzeugt eine Red-Flag-Liste.

## Rechts- und Praxisanker

BNetzA-Festlegungen, EnWG, Netzanschlussbedingungen, keine Vertragsstandards ohne Upload.

## Workflow

1. Projektrolle und gewünschtes Ergebnis festlegen: Betreiber, Investor, Kommune, Netzbetreiber, Nachbar, Bank oder Behörde.
2. Standort, Technik, Netzebene, Leistung, Kapazität, Betriebsmodell und Dokumentenstand erfassen.
3. Genehmigungs-, Netz-, Sicherheits-, Markt- und Vertragsfragen in getrennte Spuren legen.
4. Rote Punkte mit Belegen, zuständiger Stelle, Frist und konkretem nächsten Dokument ausgeben.

## Output

- Risikomatrix
- Unterlagen- und Behördenliste
- Mandantenmemo oder Board-Paper-Baustein

## Qualitätsgate

- Keine Blindzitate: Rechtsprechung, Behördenpraxis und Schwellenwerte vor tragender Aussage live anhand amtlicher oder frei zugänglicher Quellen prüfen.
- Keine LMA-, Banken- oder Fondsformularsprache nacherzählen: Nutzer soll das aktuelle Dokument hochladen; der Skill arbeitet dann am konkreten Text.
- Jede Annahme sichtbar markieren, insbesondere Zahlen, Fristen, regulatorische Rollen, Genehmigungsstand und Parteiperspektive.

## 3. `er-bess-finanzierung-bankability`

**Fokus:** Prüft Projektfinanzierung, Sicherheiten, Erlösmodell, Netzanschlussrisiko, Bau-/Betriebsrisiko und Insurance DD.

# Finanzierung und Bankability

## Wofür dieser Skill da ist

Der Skill erzeugt Bank-DD-Fragen und Lender-Risk-Matrix.

## Rechts- und Praxisanker

BGB, Sicherheitenrecht, EnWG/EEG, Versicherungen, Bauvertrag, Finanzierungsvertrag.

## Workflow

1. Projektrolle und gewünschtes Ergebnis festlegen: Betreiber, Investor, Kommune, Netzbetreiber, Nachbar, Bank oder Behörde.
2. Standort, Technik, Netzebene, Leistung, Kapazität, Betriebsmodell und Dokumentenstand erfassen.
3. Genehmigungs-, Netz-, Sicherheits-, Markt- und Vertragsfragen in getrennte Spuren legen.
4. Rote Punkte mit Belegen, zuständiger Stelle, Frist und konkretem nächsten Dokument ausgeben.

## Output

- Risikomatrix
- Unterlagen- und Behördenliste
- Mandantenmemo oder Board-Paper-Baustein

## Qualitätsgate

- Keine Blindzitate: Rechtsprechung, Behördenpraxis und Schwellenwerte vor tragender Aussage live anhand amtlicher oder frei zugänglicher Quellen prüfen.
- Keine LMA-, Banken- oder Fondsformularsprache nacherzählen: Nutzer soll das aktuelle Dokument hochladen; der Skill arbeitet dann am konkreten Text.
- Jede Annahme sichtbar markieren, insbesondere Zahlen, Fristen, regulatorische Rollen, Genehmigungsstand und Parteiperspektive.

## 4. `er-bess-kapazitaetsmarkt-grundlast`

**Fokus:** Ordnet Aussagen zu Grundlast, gesicherter Leistung, Kapazitätsmarkt, Gaskraftwerken und Speicherfunktion rechtlich ein.

# Kapazitätsmechanismen, Grundlast und politische Aussagen

## Wofür dieser Skill da ist

Der Skill erklärt, warum Batteriespeicher nicht automatisch Grundlastkraftwerk sind, aber systemdienliche Flexibilität liefern können.

## Rechts- und Praxisanker

EnWG, Strommarktdesign, BMWK/BNetzA-Dokumente live prüfen, keine politische Parole als Rechtsnorm.

## Workflow

1. Projektrolle und gewünschtes Ergebnis festlegen: Betreiber, Investor, Kommune, Netzbetreiber, Nachbar, Bank oder Behörde.
2. Standort, Technik, Netzebene, Leistung, Kapazität, Betriebsmodell und Dokumentenstand erfassen.
3. Genehmigungs-, Netz-, Sicherheits-, Markt- und Vertragsfragen in getrennte Spuren legen.
4. Rote Punkte mit Belegen, zuständiger Stelle, Frist und konkretem nächsten Dokument ausgeben.

## Output

- Risikomatrix
- Unterlagen- und Behördenliste
- Mandantenmemo oder Board-Paper-Baustein

## Qualitätsgate

- Keine Blindzitate: Rechtsprechung, Behördenpraxis und Schwellenwerte vor tragender Aussage live anhand amtlicher oder frei zugänglicher Quellen prüfen.
- Keine LMA-, Banken- oder Fondsformularsprache nacherzählen: Nutzer soll das aktuelle Dokument hochladen; der Skill arbeitet dann am konkreten Text.
- Jede Annahme sichtbar markieren, insbesondere Zahlen, Fristen, regulatorische Rollen, Genehmigungsstand und Parteiperspektive.
