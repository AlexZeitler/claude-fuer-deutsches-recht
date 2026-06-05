---
name: versorgungswerk-befreiung-rentenantrag
description: "Nutze dies, wenn Versorgungswerk Befreiung 6 Sgb Vi, Versorgungswerk Rentenantrag im Plugin Rentenpruefer konkret bearbeitet werden soll. Auslöser: Bitte Versorgungswerk Befreiung 6 Sgb Vi, Versorgungswerk Rentenantrag prüfen.; Erstelle eine Arbeitsfassung zu Versorgungswerk Befreiung 6 Sgb Vi, Versorgungswerk Rentenantrag.; Welche Normen und Nachweise brauche ich?."
---

# Versorgungswerk Befreiung 6 Sgb Vi, Versorgungswerk Rentenantrag

## Zweck

Dieser Skill ist ein eigenständiger Arbeitsbereich. Er verbindet mehrere sachlich benachbarte Arbeitsmodule. Wähle anhand des Sachverhalts das passende Modul, arbeite dessen Prüfroutine vollständig ab und kombiniere Module nur, wenn der Fall tatsächlich mehrere Themen berührt.

## Arbeitsmodule

| Arbeitsmodul | Fokus |
| --- | --- |
| `versorgungswerk-befreiung-6-sgb-vi` | Befreiung von der gesetzlichen Rentenversicherungspflicht zugunsten eines berufsständischen Versorgungswerks nach § 6 SGB VI. |
| `versorgungswerk-rentenantrag` | Rentenantrag beim Versorgungswerk: Satzung, Altersrente, Berufsunfähigkeitsrente, Hinterbliebenenversorgung, Beiträge und Nachweise. |

## Arbeitsweg

Für **Versorgungswerk Befreiung 6 Sgb Vi, Versorgungswerk Rentenantrag** zuerst das Arbeitsmodul wählen, dessen Tatsachen im konkreten Fall wirklich angelegt sind. Im Plugin `rentenpruefer` bleiben Rollen, Fristen, Zuständigkeit, Anspruchs- oder Verfahrensgrundlage, Beweislast und gewünschter Output getrennt; Module nur kombinieren, wenn dieselbe Akte mehrere dieser Punkte trägt. Tragende Normen und Fundstellen nach `references/quellenhygiene.md` verifizieren.


## Arbeitsmodule im Detail

## 1. `versorgungswerk-befreiung-6-sgb-vi`

**Fokus:** Befreiung von der gesetzlichen Rentenversicherungspflicht zugunsten eines berufsständischen Versorgungswerks nach § 6 SGB VI.

# versorgungswerk-befreiung-6-sgb-vi

## Aufgabe

Prüft Rechtsanwälte, Ärzte, Apotheker, Architekten und andere Kammerberufe mit Beschäftigungsbezug.

## Pflichtfragen

- Welches Rentensystem oder welcher Träger ist betroffen: DRV, Knappschaft, Versorgungswerk, Zusatzversorgung, ausländischer Träger oder Mischfall?
- Gibt es einen Bescheid, eine Renteninformation, eine Rentenauskunft, einen Versicherungsverlauf oder nur Einzelunterlagen?
- Welche Frist, welches Datum, welcher Zeitraum und welches konkrete Ziel sind entscheidend?
- Welche Unterlagen liegen bereits vor und welche Nachweise fehlen noch?

## Spezifischer Intake

Beruf, Kammer, Versorgungswerk, Beschäftigung, Tätigkeitsbeschreibung, Antrag, Frist, Wechsel.

## Prüfprogramm

1. **Systemroute klären:** gesetzliche Rente, Versorgungswerk, Ausland, Nachversicherung oder Rechtsbehelf trennen.
2. **Tatsachen sichern:** Zeiträume monatsgenau, Träger, Bescheide, Nachweise, Übersetzungen und Zustellungen erfassen.
3. **Norm- und Quellencheck:** SGB VI, SGB X, SGG, FRG, DRV-Informationen, Sozialversicherungsabkommen oder konkrete Satzung live prüfen.
4. **Beweiswert bewerten:** Original, beglaubigte Kopie, ausländische Urkunde, Arbeitsbuch, Zeuge, Arbeitgeberarchiv, Behördenauskunft.
5. **Handlung ableiten:** Antrag, Kontenklärung, Nachreichung, Widerspruch, Klage, Vergleich, Nachfassschreiben oder Mandantenbrief.

## Output

Befreiungsmatrix und Tätigkeitsbegründung.

## Qualitäts-Hardening

- Keine nicht überprüfbaren Fundstellen, keine privaten Datenbankzitate, keine Kommentar- oder Aufsatzblindzitate.
- Bei ausländischen Zeiten nie pauschal anerkennen: EU/EWR/Schweiz, Abkommensstaat, vertragsloser Drittstaat und FRG strikt trennen.
- Bei Versorgungswerken immer Beruf, Kammer, Bundesland und aktuelle Satzung verlangen.
- Zahlen, Fristen und Altersgrenzen nur mit aktueller Quelle oder als ausdrücklich zu prüfenden Punkt ausgeben.

## 2. `versorgungswerk-rentenantrag`

**Fokus:** Rentenantrag beim Versorgungswerk: Satzung, Altersrente, Berufsunfähigkeitsrente, Hinterbliebenenversorgung, Beiträge und Nachweise.

# versorgungswerk-rentenantrag

## Aufgabe

Führt Mitglieder durch das jeweilige Versorgungswerk statt DRV-Regeln blind zu übertragen.

## Pflichtfragen

- Welches Rentensystem oder welcher Träger ist betroffen: DRV, Knappschaft, Versorgungswerk, Zusatzversorgung, ausländischer Träger oder Mischfall?
- Gibt es einen Bescheid, eine Renteninformation, eine Rentenauskunft, einen Versicherungsverlauf oder nur Einzelunterlagen?
- Welche Frist, welches Datum, welcher Zeitraum und welches konkrete Ziel sind entscheidend?
- Welche Unterlagen liegen bereits vor und welche Nachweise fehlen noch?

## Spezifischer Intake

Versorgungswerk, Satzung, Mitgliedschaft, Beitragszeiten, Rentenart, Bescheide, Beruf.

## Prüfprogramm

1. **Systemroute klären:** gesetzliche Rente, Versorgungswerk, Ausland, Nachversicherung oder Rechtsbehelf trennen.
2. **Tatsachen sichern:** Zeiträume monatsgenau, Träger, Bescheide, Nachweise, Übersetzungen und Zustellungen erfassen.
3. **Norm- und Quellencheck:** SGB VI, SGB X, SGG, FRG, DRV-Informationen, Sozialversicherungsabkommen oder konkrete Satzung live prüfen.
4. **Beweiswert bewerten:** Original, beglaubigte Kopie, ausländische Urkunde, Arbeitsbuch, Zeuge, Arbeitgeberarchiv, Behördenauskunft.
5. **Handlung ableiten:** Antrag, Kontenklärung, Nachreichung, Widerspruch, Klage, Vergleich, Nachfassschreiben oder Mandantenbrief.

## Output

Satzungscheck, Dokumentenliste und Antragsskizze.

## Qualitäts-Hardening

- Keine nicht überprüfbaren Fundstellen, keine privaten Datenbankzitate, keine Kommentar- oder Aufsatzblindzitate.
- Bei ausländischen Zeiten nie pauschal anerkennen: EU/EWR/Schweiz, Abkommensstaat, vertragsloser Drittstaat und FRG strikt trennen.
- Bei Versorgungswerken immer Beruf, Kammer, Bundesland und aktuelle Satzung verlangen.
- Zahlen, Fristen und Altersgrenzen nur mit aktueller Quelle oder als ausdrücklich zu prüfenden Punkt ausgeben.
