---
name: oeffentlicher-dienst-pflegezeiten
description: "Nutze dies, wenn Oeffentlicher Dienst Vbl Und Zusatzversorgung, Pflegezeiten Rentenpunkte im Plugin Rentenpruefer konkret bearbeitet werden soll. Auslöser: Bitte Oeffentlicher Dienst Vbl Und Zusatzversorgung, Pflegezeiten Rentenpunkte prüfen.; Erstelle eine Arbeitsfassung zu Oeffentlicher Dienst Vbl Und Zusatzversorgung, Pflegezeiten Rentenpunkte.; Welche Normen und Nachweise brauche ich?."
---

# Oeffentlicher Dienst Vbl Und Zusatzversorgung, Pflegezeiten Rentenpunkte

## Zweck

Dieser Skill ist ein eigenständiger Arbeitsbereich. Er verbindet mehrere sachlich benachbarte Arbeitsmodule. Wähle anhand des Sachverhalts das passende Modul, arbeite dessen Prüfroutine vollständig ab und kombiniere Module nur, wenn der Fall tatsächlich mehrere Themen berührt.

## Arbeitsmodule

| Arbeitsmodul | Fokus |
| --- | --- |
| `oeffentlicher-dienst-vbl-und-zusatzversorgung` | Zusatzversorgung öffentlicher Dienst, VBL und kommunale Kassen: Pflichtversicherung, Startgutschrift, Rentenbescheid und Schnittstelle zur DRV. |
| `pflegezeiten-rentenpunkte` | Rentenpunkte durch Pflege: Pflegegrad, Pflegeumfang, Erwerbstätigkeit, Pflegekasse und Beitragsmeldung. |

## Arbeitsweg

Für **Oeffentlicher Dienst Vbl Und Zusatzversorgung, Pflegezeiten Rentenpunkte** zuerst das Arbeitsmodul wählen, dessen Tatsachen im konkreten Fall wirklich angelegt sind. Im Plugin `rentenpruefer` bleiben Rollen, Fristen, Zuständigkeit, Anspruchs- oder Verfahrensgrundlage, Beweislast und gewünschter Output getrennt; Module nur kombinieren, wenn dieselbe Akte mehrere dieser Punkte trägt. Tragende Normen und Fundstellen nach `references/quellenhygiene.md` verifizieren.


## Arbeitsmodule im Detail

## 1. `oeffentlicher-dienst-vbl-und-zusatzversorgung`

**Fokus:** Zusatzversorgung öffentlicher Dienst, VBL und kommunale Kassen: Pflichtversicherung, Startgutschrift, Rentenbescheid und Schnittstelle zur DRV.

# oeffentlicher-dienst-vbl-und-zusatzversorgung

## Aufgabe

Ordnet Zusatzversorgung neben gesetzlicher Rente und Beamtenversorgung ein.

## Pflichtfragen

- Welches Rentensystem oder welcher Träger ist betroffen: DRV, Knappschaft, Versorgungswerk, Zusatzversorgung, ausländischer Träger oder Mischfall?
- Gibt es einen Bescheid, eine Renteninformation, eine Rentenauskunft, einen Versicherungsverlauf oder nur Einzelunterlagen?
- Welche Frist, welches Datum, welcher Zeitraum und welches konkrete Ziel sind entscheidend?
- Welche Unterlagen liegen bereits vor und welche Nachweise fehlen noch?

## Spezifischer Intake

Arbeitgeber öffentlicher Dienst, VBL-Auskunft, Versicherungsverlauf, Wechsel, Bescheid.

## Prüfprogramm

1. **Systemroute klären:** gesetzliche Rente, Versorgungswerk, Ausland, Nachversicherung oder Rechtsbehelf trennen.
2. **Tatsachen sichern:** Zeiträume monatsgenau, Träger, Bescheide, Nachweise, Übersetzungen und Zustellungen erfassen.
3. **Norm- und Quellencheck:** SGB VI, SGB X, SGG, FRG, DRV-Informationen, Sozialversicherungsabkommen oder konkrete Satzung live prüfen.
4. **Beweiswert bewerten:** Original, beglaubigte Kopie, ausländische Urkunde, Arbeitsbuch, Zeuge, Arbeitgeberarchiv, Behördenauskunft.
5. **Handlung ableiten:** Antrag, Kontenklärung, Nachreichung, Widerspruch, Klage, Vergleich, Nachfassschreiben oder Mandantenbrief.

## Output

Zusatzversorgungscheck.

## Qualitäts-Hardening

- Keine nicht überprüfbaren Fundstellen, keine privaten Datenbankzitate, keine Kommentar- oder Aufsatzblindzitate.
- Bei ausländischen Zeiten nie pauschal anerkennen: EU/EWR/Schweiz, Abkommensstaat, vertragsloser Drittstaat und FRG strikt trennen.
- Bei Versorgungswerken immer Beruf, Kammer, Bundesland und aktuelle Satzung verlangen.
- Zahlen, Fristen und Altersgrenzen nur mit aktueller Quelle oder als ausdrücklich zu prüfenden Punkt ausgeben.

## 2. `pflegezeiten-rentenpunkte`

**Fokus:** Rentenpunkte durch Pflege: Pflegegrad, Pflegeumfang, Erwerbstätigkeit, Pflegekasse und Beitragsmeldung.

# pflegezeiten-rentenpunkte

## Aufgabe

Prüft, ob häusliche Pflege rentenrechtlich verwertet wurde.

## Pflichtfragen

- Welches Rentensystem oder welcher Träger ist betroffen: DRV, Knappschaft, Versorgungswerk, Zusatzversorgung, ausländischer Träger oder Mischfall?
- Gibt es einen Bescheid, eine Renteninformation, eine Rentenauskunft, einen Versicherungsverlauf oder nur Einzelunterlagen?
- Welche Frist, welches Datum, welcher Zeitraum und welches konkrete Ziel sind entscheidend?
- Welche Unterlagen liegen bereits vor und welche Nachweise fehlen noch?

## Spezifischer Intake

Pflegeperson, gepflegte Person, Pflegegrad, Stunden, Erwerbstätigkeit, Kassenmeldung.

## Prüfprogramm

1. **Systemroute klären:** gesetzliche Rente, Versorgungswerk, Ausland, Nachversicherung oder Rechtsbehelf trennen.
2. **Tatsachen sichern:** Zeiträume monatsgenau, Träger, Bescheide, Nachweise, Übersetzungen und Zustellungen erfassen.
3. **Norm- und Quellencheck:** SGB VI, SGB X, SGG, FRG, DRV-Informationen, Sozialversicherungsabkommen oder konkrete Satzung live prüfen.
4. **Beweiswert bewerten:** Original, beglaubigte Kopie, ausländische Urkunde, Arbeitsbuch, Zeuge, Arbeitgeberarchiv, Behördenauskunft.
5. **Handlung ableiten:** Antrag, Kontenklärung, Nachreichung, Widerspruch, Klage, Vergleich, Nachfassschreiben oder Mandantenbrief.

## Output

Pflegezeitencheck und Anfrage an Pflegekasse/DRV.

## Qualitäts-Hardening

- Keine nicht überprüfbaren Fundstellen, keine privaten Datenbankzitate, keine Kommentar- oder Aufsatzblindzitate.
- Bei ausländischen Zeiten nie pauschal anerkennen: EU/EWR/Schweiz, Abkommensstaat, vertragsloser Drittstaat und FRG strikt trennen.
- Bei Versorgungswerken immer Beruf, Kammer, Bundesland und aktuelle Satzung verlangen.
- Zahlen, Fristen und Altersgrenzen nur mit aktueller Quelle oder als ausdrücklich zu prüfenden Punkt ausgeben.
