---
name: inv-027-bribery-red-flags
description: "Identifiziert Bestechungs-Red-Flags in Transaktionen, Zahlungen, Vergabeverfahren und Drittparteienbeziehungen – FCPA, UK Bribery Act, § 299 StGB."
---

# Bestechungs-Red-Flags und Korruptionsermittlung

## Rechtlicher Rahmen

Bestechung im geschäftlichen Verkehr ist nach §§ 299–301 StGB strafbar ([gesetze-im-internet.de](https://www.gesetze-im-internet.de/stgb/__299.html)), Bestechung ausländischer Amtsträger nach § 335a StGB und der OECD-Konvention. US-Unternehmen und international tätige deutsche Konzerne unterliegen dem Foreign Corrupt Practices Act (FCPA, 15 U.S.C. § 78dd-1) und dem UK Bribery Act 2010. Für Unternehmen, die in internationalen Märkten tätig sind, ist das Risiko allgegenwärtig. § 30 OWiG und § 130 OWiG begründen die Unternehmensbußgeldhaftung ([gesetze-im-internet.de](https://www.gesetze-im-internet.de/owig/__30.html)).

## Ziel dieses Skills

Dieser Skill identifiziert Bestechungs-Red-Flags in Transaktionsdaten, Drittparteienbeziehungen und Vergabeverfahren und leitet daraus begründete Untersuchungsschritte ab.

## Arbeitsprogramm

### 1. Red-Flag-Kategorien (Transaktionen)
- **Ungewöhnliche Zahlungen**: Zahlungen ohne klaren Geschäftszweck, an unbekannte Empfänger, in runde Beträge, kurz vor Vertragsschluss oder Genehmigungen.
- **Drittparteien**: Agenten, Berater, Intermediäre mit hohen Provisionen ohne nachweisbare Gegenleistung; Domizilgesellschaften in Hochrisikoländern.
- **Spesenabrechnungen**: Unterhaltung, Geschenke, Reisen zugunsten von Entscheidungsträgern beim Kunden oder bei Behörden.
- **Cash-Zahlungen**: Barzahlungen außerhalb regulärer Zahlungswege; keine Quittungen.
- **Split Transactions**: Aufteilung größerer Zahlungen, um interne Genehmigungsgrenzen zu umgehen.

### 2. Red-Flag-Kategorien (Drittparteien)
- Agent hat familiäre oder politische Verbindungen zu relevanten Entscheidungsträgern.
- Vertrag wurde ohne Due-Diligence-Prüfung abgeschlossen.
- Agent fordert Zahlungen auf ein Konto in einem Drittland, das nichts mit seiner Tätigkeit zu tun hat.
- Leistungen des Agenten sind nicht dokumentiert oder nachweisbar.
- Rechnungen ohne Aufschlüsselung; pauschale „Beratungsleistungen".

### 3. Red-Flag-Kategorien (Vergabeverfahren)
- Spezifikationen wurden so formuliert, dass nur ein bestimmter Lieferant gewinnen konnte.
- Entscheidungsträger hat unmittelbar nach dem Auftrag die Stelle gewechselt und beim Auftragnehmer angeheuert.
- Öffentliche Ausschreibung wurde kurz ausgehängt oder gar nicht publiziert.
- Preis liegt erheblich unter dem Marktwert; Qualitätsmängel wurden toleriert.

### 4. Analytische Methoden
- **Datenbankanalyse**: alle Zahlungen an Agenten/Berater über definierten Zeitraum und Betragsgrenzen.
- **Netzwerkanalyse**: Verbindungen zwischen Mitarbeitern, Agenten und Entscheidungsträgern beim Kunden.
- **Geographical risk scoring**: TRACE Bribery Risk Matrix, Transparency International CPI.
- **Benford's Law**: Ziffernverteilung in Zahlenreihen als Indiz für Manipulation.

### 5. FCPA und UK Bribery Act
- **FCPA**: verbietet Zahlungen an ausländische Amtsträger zwecks Erlangung oder Halten von Geschäften; auch indirekte Zahlungen über Dritte.
- **UK Bribery Act**: weiter als FCPA – erfasst auch private Bestechung, kein Ausnahme für facilitation payments.
- **Adequate Procedures** (UK Bribery Act Section 7): Unternehmen vermeidet Haftung, wenn es angemessene Anti-Bestechungsmaßnahmen hatte.
- DOJ-Leitlinien (FCPA Resource Guide, 2020): Faktoren für Strafverfolgung und Kooperation.

### 6. Interne Forensik
- Buchhaltungsforensik: Zahlungen außerhalb normaler Buchungsroutinen; Ausnahme-Buchungen durch leitende Mitarbeiter.
- Vertragsanalyse: Agenten- und Beraterverträge auf Red Flags prüfen.
- Reisekostenabrechnungen: systematische Auswertung auf Zahlungen an öffentliche Funktionsträger.
- Emails: Suche nach Begriffen wie „commission", „consulting fee", „gift", Namen von verdächtigen Empfängern.

### 7. Selbstanzeige an DOJ/BaFin
- FCPA Voluntary Disclosure: DOJ-Kooperationsbonus bei proaktiver Selbstanzeige.
- BaFin: keine formelle Selbstanzeige-Regelung, aber proaktive Kooperation fließt in Ermessen ein.
- Regulatorische Strafe vs. Reputationsschaden: Abwägung vor Selbstanzeige.

## Red-Team-Fragen

- Wurden alle Zahlungen an Drittparteien (Agenten, Berater) mit angemessener Due-Diligence überprüft?
- Gibt es systematische Muster in den Red Flags (z. B. immer dieselbe Region, immer vor Genehmigungsentscheidungen)?
- Wurden die FCPA- und UK-Bribery-Act-Anforderungen für alle relevanten Märkte geprüft?
- Hat das Unternehmen Adequate Procedures dokumentiert (UK Bribery Act Section 7)?
- Sind die Interviewpartner mit den Transaktions-Red-Flags konfrontiert worden?
- Wurde eine Selbstanzeige an das DOJ in Betracht gezogen und die Entscheidung dokumentiert?

## Normenregister

| Norm | Inhalt | Quelle |
|---|---|---|
| § 299 StGB | Bestechung im Geschäftsverkehr | [gesetze-im-internet.de](https://www.gesetze-im-internet.de/stgb/__299.html) |
| § 335a StGB | Bestechung ausländischer Amtsträger | [gesetze-im-internet.de](https://www.gesetze-im-internet.de/stgb/__335a.html) |
| § 30 OWiG | Verbandsgeldbuße | [gesetze-im-internet.de](https://www.gesetze-im-internet.de/owig/__30.html) |
| 15 U.S.C. § 78dd-1 | FCPA Anti-Bribery | US Government |
| UK Bribery Act 2010 | Bestechungsverbot UK | UK Government |

## Ausgabeformate

- **Red-Flag-Checkliste** (Transaktionen, Drittparteien, Vergabe)
- **Zahlungsanalyse-Template** (SQL/Excel: Beträge, Empfänger, Zeitraum)
- **Geografische Risikoklassifizierung** (TI CPI, TRACE Index)
- **FCPA/UK-Bribery-Act-Compliance-Mapping**
- **DOJ-Kooperationsstrategie-Memo**

Rechtsprechungszitate nur mit Gericht, Datum, Aktenzeichen und frei prüfbarer Quelle.
