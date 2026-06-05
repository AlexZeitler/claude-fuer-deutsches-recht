---
name: dublin-ueberstellung
description: "Nutze dies, wenn Spezial Dublin Fristen Ueberstellung im Plugin Fachanwalt Migrationsrecht konkret bearbeitet werden soll. Auslöser: Bitte Spezial Dublin Fristen Ueberstellung prüfen.; Erstelle eine Arbeitsfassung zu Spezial Dublin Fristen Ueberstellung.; Welche Normen und Nachweise brauche ich?."
---

# Spezial Dublin Fristen Ueberstellung

## Zweck

Dieser Skill ist ein eigenständiger Arbeitsbereich. Er verbindet sachlich benachbarte Arbeitsmodule, die gemeinsam in einem Fall auftreten können. Wähle anhand des Sachverhalts das passende Modul, arbeite dessen Prüfroutine vollständig ab und kombiniere Module nur, wenn der Fall tatsächlich mehrere Themen berührt.

## Arbeitsmodule

| Arbeitsmodul | Fokus |
| --- | --- |
| `spezial-dublin-fristen-ueberstellung` | Dublin-Fristen/Überstellung: Spezial-Skill im Migrationsrecht; prüft Aufnahme-/Wiederaufnahme, Überstellungsfrist, Kirchenasyl, Aussetzung; mit deutschem Recht, EU/EMRK/GFK, Belegen, Fristen und Quellencheck. |

## Arbeitsweg

Für **Spezial Dublin Fristen Ueberstellung** zuerst das Arbeitsmodul wählen, dessen Tatsachen im konkreten Fall wirklich angelegt sind. Im Plugin `fachanwalt-migrationsrecht` bleiben Rollen, Fristen, Zuständigkeit, Anspruchs- oder Verfahrensgrundlage, Beweislast und gewünschter Output getrennt; Module nur kombinieren, wenn dieselbe Akte mehrere dieser Punkte trägt. Tragende Normen und Fundstellen nach `references/quellenhygiene.md` verifizieren.


## Arbeitsmodule im Detail

## 1. `spezial-dublin-fristen-ueberstellung`

**Fokus:** Dublin-Fristen/Überstellung: Spezial-Skill im Migrationsrecht; prüft Aufnahme-/Wiederaufnahme, Überstellungsfrist, Kirchenasyl, Aussetzung; mit deutschem Recht, EU/EMRK/GFK, Belegen, Fristen und Quellencheck.


# Dublin-Fristen/Überstellung

## Aufgabe
Spezialskill im Plugin `fachanwalt-migrationsrecht`. Er bearbeitet: prüft Aufnahme-/Wiederaufnahme, Überstellungsfrist, Kirchenasyl, Aussetzung.

## Kaltstart
1. Wer ist betroffen, wer fragt, und welches konkrete Ziel besteht?
2. Welche Staatsangehörigkeit/Gebietszuordnung, welcher Aufenthaltsort und welcher aktuelle Status liegen vor?
3. Welche Frist oder welches Eilrisiko entscheidet den Fall?
4. Welche Unterlagen beweisen Identität, Status, Familie, Arbeit, Ausbildung, Schutzgrund oder Gesundheit?
5. Soll das Ergebnis auf Deutsch, in einfacher Sprache oder zusätzlich auf Spanisch ausgegeben werden?

## Prüfraster
1. **Status und Ziel:** Ist der passende Titel/Schutz-/Rechtsbehelfspfad richtig gewählt?
2. **Tatbestand:** Normmerkmale, Ausnahmen, Ermessen, Versagungsgründe und Gegenargumente.
3. **EU/EMRK/GFK:** Unionsrechtliche oder menschenrechtliche Ebene prüfen, wenn sie den Fall tragen kann.
4. **Staatenbezug:** Herkunfts-, Transit- und Zielstaat nur mit aktuellen Quellen bewerten; keine statischen Sicherheitsannahmen.
5. **Beweis:** Dokumente, Urkunden, Übersetzungen, Atteste, Länderquellen und digitale Belege sauber trennen.
6. **Taktik:** Antrag, Nachreichung, Fristverlängerung, Eilantrag, Klage, Vergleich, Behördenkommunikation.

## Output
- Kurzlage und Risikoampel.
- Prüfmatrix: Norm/Quelle, Tatsache, Beleg, Bewertung, To-do.
- Direkt nutzbarer Textbaustein für Behörde, Gericht, Arbeitgeber oder Mandant.
- Anschluss-Skills innerhalb dieses Plugins.

## Quellen- und Sicherheitsregel
- Vor tragenden Aussagen den aktuellen Normtext und die aktuelle Behörden-/Gerichtspraxis prüfen; keine Scheingenauigkeit aus Modellwissen.
- Rechtsprechung nur mit Gericht, Entscheidungsform, Datum, Aktenzeichen und frei prüfbarer Quelle ausgeben.
- Keine BeckRS-, juris-, Kommentar-, Handbuch- oder Aufsatz-Blindzitate aus Modellwissen.
- Annahmen, fehlende Unterlagen, Beweisrisiken und Fristen ausdrücklich markieren.
