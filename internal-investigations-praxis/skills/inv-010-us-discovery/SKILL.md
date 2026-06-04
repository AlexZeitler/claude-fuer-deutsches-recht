---
name: inv-010-us-discovery
description: "Steuert das US-Discovery-Risiko bei Internal Investigations – FRCP, Attorney-Client Privilege, Work Product, Litigation Hold."
---

# US-Discovery in Cross-Border Investigations

## Rechtlicher Rahmen

US-amerikanische Discovery-Pflichten nach den Federal Rules of Civil Procedure (FRCP, insb. Rules 26, 34, 37) und in behördlichen Verfahren (DOJ, SEC) können alle Dokumente einer internen Untersuchung erfassen, die in den USA produziert oder dort gehostet wurden – unabhängig davon, ob das Unternehmen seinen Sitz in Deutschland hat. Das Attorney-Client Privilege und die Work-Product-Doctrine (Hickman v. Taylor, 329 U.S. 495 (1947)) sind die wichtigsten Schutzinstrumente, haben aber Grenzen, die im Konflikt mit deutschen Geheimhaltungsinteressen stehen.

## Ziel dieses Skills

Dieser Skill analysiert das US-Discovery-Risiko für laufende Internal Investigations, leitet Schutzmaßnahmen ab und klärt, welche Dokumente trotz Privilege-Anspruch offengelegt werden müssen.

## Arbeitsprogramm

### 1. Trigger für US-Discovery-Risiko
- US-Tochtergesellschaft als Partei in einem US-Verfahren.
- DOJ/SEC-Ermittlung wegen FCPA (Foreign Corrupt Practices Act, 15 U.S.C. § 78dd-1 ff.) oder Sanktionsverstößen.
- US-Gerichtsverfahren mit Bezug zu Unternehmenshandlungen.
- Hague Evidence Convention (HKUE) – Rechtshilfeersuchen aus den USA an deutsche Gerichte.

### 2. Litigation Hold nach FRCP 37(e)
- Ab „reasonable anticipation of litigation": alle relevanten Dokumente sichern (Electronically Stored Information, ESI).
- Failure to preserve = Spoliation; Sanktionen: adverse inference instruction, dismissal, monetary sanctions.
- Custodian-Liste und Hold-Notice nach US-Standard (ähnlich deutschem Legal Hold, aber ausdrücklich auf ESI ausgerichtet).
- Cloud-Dienste: US-CLOUD-Act (18 U.S.C. § 2713) erlaubt US-Behörden Zugriff auf Daten bei US-Providern weltweit.

### 3. Attorney-Client Privilege
- Schützt vertrauliche Kommunikation zwischen Anwalt und Mandant (hier: Unternehmen als Mandant).
- Upjohn Co. v. United States (449 U.S. 383, 1981): Privilege erfasst auch Kommunikation mit Mitarbeitern, wenn Anwalt sie im Rahmen der Rechtsberatung befragt hat.
- Waiver (Verzicht): freiwillige Offenlegung gegenüber Dritten (inkl. Behörden) kann Privilege aufheben; Selective Waiver in den USA nicht allgemein anerkannt.
- Crime-Fraud Exception: Privilege entfällt, wenn Kommunikation zur Begehung einer Straftat diente.

### 4. Work-Product Doctrine
- Hickman v. Taylor: schützt Anwaltsmaterialien, die in Erwartung eines Rechtsstreits erstellt wurden (mental impressions, conclusions, opinions).
- Stärkerer Schutz als Privilege für „opinion work product" (rechtliche Bewertungen des Anwalts).
- Schwächerer Schutz für „fact work product" (Tatsachenzusammenfassungen); kann bei substantial need überwindbar sein.
- Praktische Konsequenz: Anwalt sollte eigene rechtliche Bewertungen strikt von reinen Fakten-Summaries trennen.

### 5. Konflikt mit deutschem Datenschutzrecht
- Herausgabe personenbezogener Daten an US-Behörden: DSGVO Art. 49 Abs. 1 lit. e (Strafverfolgung) oder Standard Contractual Clauses.
- EU-Blocking-Statutes: einige EU-Länder verbieten Herausgabe bestimmter Daten; Deutschland hat kein allgemeines Blocking-Statute, aber DSGVO-Verpflichtungen gelten.
- Abstimmung mit deutsch-amerikanischen Doppelberatern zwingend.

### 6. DOJ/SEC-Kooperationsanreize und Discovery-Risiko
- DOJ Corporate Enforcement Policy: Selbstoffenbarung und Kooperation kann Ermessen bei Strafverfolgung beeinflussen.
- SEC Whistleblower Program: Hinweisgeber können direkt bei der SEC melden; Unternehmen kann nicht verhindern, dass interne Ermittlungsergebnisse bei SEC landen.
- Privilege Review vor jeder freiwilligen Herausgabe an US-Behörden.

### 7. eDiscovery-Prozess
- EDRM (Electronic Discovery Reference Model): Identification → Preservation → Collection → Processing → Review → Production.
- Keyword-Suche und Technologiegestützte Überprüfung (Technology-Assisted Review, TAR) für große Datenmengen.
- Privilege-Log: für alle zurückgehaltenen Dokumente (FRCP Rule 26(b)(5)); Anforderungen an Format und Inhalt.
- Redaktion (Schwärzung) sensibler Drittdaten vor Produktion.

## Red-Team-Fragen

- Gibt es US-Bezüge (Tochtergesellschaft, US-Cloud, FCPA-Risiko), die ein US-Discovery-Risiko begründen?
- Wurde ein Litigation Hold nach US-Standard ausgelöst, sobald ein US-Verfahren absehbar war?
- Ist jedes Dokument, das als „privileged" zurückgehalten wird, im Privilege-Log erfasst?
- Hat die freiwillige Herausgabe von Teilen des Berichts an das DOJ zu einem Subject-Matter-Waiver geführt?
- Wurden alle US-Cloud-Dienste auf CLOUD-Act-Risiken geprüft?
- Sind die deutschen und US-amerikanischen Anwälte koordiniert – insbesondere bei widersprüchlichen Pflichten?

## Normenregister

| Norm | Inhalt | Quelle |
|---|---|---|
| FRCP Rule 26 | General Discovery Obligations | US Federal Courts |
| FRCP Rule 37(e) | Spoliation Sanctions | US Federal Courts |
| 15 U.S.C. § 78dd-1 | FCPA Anti-Bribery | US Government |
| 18 U.S.C. § 2713 | US CLOUD Act | US Government |
| Art. 49 DSGVO | Drittstaaten-Transfer | [eur-lex.europa.eu](https://eur-lex.europa.eu/legal-content/DE/TXT/?uri=CELEX%3A32016R0679) |
| EuGH C-550/07 P | Akzo Nobel / Inhouse Privilege | [curia.europa.eu](https://curia.europa.eu/juris/document/document.jsf?docid=83458&doclang=DE) |

## Ausgabeformate

- **US-Discovery-Risikoampel** (Trigger × Privilegeschutz × Handlungsbedarf)
- **Litigation-Hold-Notice** nach US-Standard
- **Privilege-Log-Vorlage** (FRCP Rule 26(b)(5))
- **DSGVO-/US-Discovery-Konfliktanalyse**
- **DOJ-Kooperationsstrategie**

Rechtsprechungszitate nur mit Gericht, Datum, Aktenzeichen und frei prüfbarer Quelle.
