---
name: renteninformation-rentenauskunft
description: "Nutze dies, wenn Renteninformation Rentenauskunft Verstehen, Rentenluecken Matrix im Plugin Rentenpruefer konkret bearbeitet werden soll. Auslöser: Bitte Renteninformation Rentenauskunft Verstehen, Rentenluecken Matrix prüfen.; Erstelle eine Arbeitsfassung zu Renteninformation Rentenauskunft Verstehen, Rentenluecken Matrix.; Welche Normen und Nachweise brauche ich?."
---

# Renteninformation Rentenauskunft Verstehen, Rentenluecken Matrix

## Zweck

Dieser Skill ist ein eigenständiger Arbeitsbereich. Er verbindet mehrere sachlich benachbarte Arbeitsmodule. Wähle anhand des Sachverhalts das passende Modul, arbeite dessen Prüfroutine vollständig ab und kombiniere Module nur, wenn der Fall tatsächlich mehrere Themen berührt.

## Arbeitsmodule

| Arbeitsmodul | Fokus |
| --- | --- |
| `renteninformation-rentenauskunft-verstehen` | Renteninformation und Rentenauskunft verständlich auswerten: Prognose, Versicherungsverlauf, Wartezeiten, Abschläge, Grundannahmen und Unsicherheiten. |
| `rentenluecken-matrix` | Rentenlücken-Matrix für ganze Erwerbsbiografien: Monatsraster, Belegstatus, Trägerzuständigkeit, Priorität und Erledigung. |

## Arbeitsweg

Für **Renteninformation Rentenauskunft Verstehen, Rentenluecken Matrix** zuerst das Arbeitsmodul wählen, dessen Tatsachen im konkreten Fall wirklich angelegt sind. Im Plugin `rentenpruefer` bleiben Rollen, Fristen, Zuständigkeit, Anspruchs- oder Verfahrensgrundlage, Beweislast und gewünschter Output getrennt; Module nur kombinieren, wenn dieselbe Akte mehrere dieser Punkte trägt. Tragende Normen und Fundstellen nach `references/quellenhygiene.md` verifizieren.


## Arbeitsmodule im Detail

## 1. `renteninformation-rentenauskunft-verstehen`

**Fokus:** Renteninformation und Rentenauskunft verständlich auswerten: Prognose, Versicherungsverlauf, Wartezeiten, Abschläge, Grundannahmen und Unsicherheiten.

# renteninformation-rentenauskunft-verstehen

## Aufgabe

Erklärt, was der jährliche Brief wirklich sagt und was er noch nicht sagt.

## Pflichtfragen

- Welches Rentensystem oder welcher Träger ist betroffen: DRV, Knappschaft, Versorgungswerk, Zusatzversorgung, ausländischer Träger oder Mischfall?
- Gibt es einen Bescheid, eine Renteninformation, eine Rentenauskunft, einen Versicherungsverlauf oder nur Einzelunterlagen?
- Welche Frist, welches Datum, welcher Zeitraum und welches konkrete Ziel sind entscheidend?
- Welche Unterlagen liegen bereits vor und welche Nachweise fehlen noch?

## Spezifischer Intake

Datum der Auskunft, Versicherungsverlauf, prognostizierte Rente, Lücken, Wartezeiten, Steuer/KV-Hinweise.

## Prüfprogramm

1. **Systemroute klären:** gesetzliche Rente, Versorgungswerk, Ausland, Nachversicherung oder Rechtsbehelf trennen.
2. **Tatsachen sichern:** Zeiträume monatsgenau, Träger, Bescheide, Nachweise, Übersetzungen und Zustellungen erfassen.
3. **Norm- und Quellencheck:** SGB VI, SGB X, SGG, FRG, DRV-Informationen, Sozialversicherungsabkommen oder konkrete Satzung live prüfen.
4. **Beweiswert bewerten:** Original, beglaubigte Kopie, ausländische Urkunde, Arbeitsbuch, Zeuge, Arbeitgeberarchiv, Behördenauskunft.
5. **Handlung ableiten:** Antrag, Kontenklärung, Nachreichung, Widerspruch, Klage, Vergleich, Nachfassschreiben oder Mandantenbrief.

## Output

Mandantenbrief mit Klartext, Prüfhinweisen und nächster Aktion.

## Qualitäts-Hardening

- Keine nicht überprüfbaren Fundstellen, keine privaten Datenbankzitate, keine Kommentar- oder Aufsatzblindzitate.
- Bei ausländischen Zeiten nie pauschal anerkennen: EU/EWR/Schweiz, Abkommensstaat, vertragsloser Drittstaat und FRG strikt trennen.
- Bei Versorgungswerken immer Beruf, Kammer, Bundesland und aktuelle Satzung verlangen.
- Zahlen, Fristen und Altersgrenzen nur mit aktueller Quelle oder als ausdrücklich zu prüfenden Punkt ausgeben.

## 2. `rentenluecken-matrix`

**Fokus:** Rentenlücken-Matrix für ganze Erwerbsbiografien: Monatsraster, Belegstatus, Trägerzuständigkeit, Priorität und Erledigung.

# rentenluecken-matrix

## Aufgabe

Erzeugt ein Arbeitsinstrument, das man mit Mandanten wirklich abarbeiten kann.

## Pflichtfragen

- Welches Rentensystem oder welcher Träger ist betroffen: DRV, Knappschaft, Versorgungswerk, Zusatzversorgung, ausländischer Träger oder Mischfall?
- Gibt es einen Bescheid, eine Renteninformation, eine Rentenauskunft, einen Versicherungsverlauf oder nur Einzelunterlagen?
- Welche Frist, welches Datum, welcher Zeitraum und welches konkrete Ziel sind entscheidend?
- Welche Unterlagen liegen bereits vor und welche Nachweise fehlen noch?

## Spezifischer Intake

Alle bekannten Zeiten, Dokumente, Lücken, Träger, Fristen, Beweisstatus.

## Prüfprogramm

1. **Systemroute klären:** gesetzliche Rente, Versorgungswerk, Ausland, Nachversicherung oder Rechtsbehelf trennen.
2. **Tatsachen sichern:** Zeiträume monatsgenau, Träger, Bescheide, Nachweise, Übersetzungen und Zustellungen erfassen.
3. **Norm- und Quellencheck:** SGB VI, SGB X, SGG, FRG, DRV-Informationen, Sozialversicherungsabkommen oder konkrete Satzung live prüfen.
4. **Beweiswert bewerten:** Original, beglaubigte Kopie, ausländische Urkunde, Arbeitsbuch, Zeuge, Arbeitgeberarchiv, Behördenauskunft.
5. **Handlung ableiten:** Antrag, Kontenklärung, Nachreichung, Widerspruch, Klage, Vergleich, Nachfassschreiben oder Mandantenbrief.

## Output

Tabellarische Lückenmatrix mit Ampel.

## Qualitäts-Hardening

- Keine nicht überprüfbaren Fundstellen, keine privaten Datenbankzitate, keine Kommentar- oder Aufsatzblindzitate.
- Bei ausländischen Zeiten nie pauschal anerkennen: EU/EWR/Schweiz, Abkommensstaat, vertragsloser Drittstaat und FRG strikt trennen.
- Bei Versorgungswerken immer Beruf, Kammer, Bundesland und aktuelle Satzung verlangen.
- Zahlen, Fristen und Altersgrenzen nur mit aktueller Quelle oder als ausdrücklich zu prüfenden Punkt ausgeben.
