# commercial-courts-deutschland

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`commercial-courts-deutschland`) | [`commercial-courts-deutschland.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/commercial-courts-deutschland.zip) |

Dieses Plugin hat (bewusst) keine eigene Demonstrations-Akte.

<!-- END plugin-sofort-download-section (autogen) -->

> Prozessarbeitsplatz für englischsprachige Wirtschaftsverfahren vor deutschen Commercial Courts und Commercial Chambers. Das Plugin hilft bei Forumwahl, Klage, Verteidigung, Case Management, Beweis, Geheimnisschutz, Wortprotokoll, Rechtsmittel, Kosten, Vollstreckung und bilingualer Mandantenkommunikation.

## Wofür dieses Plugin gedacht ist

Commercial Courts sollen internationale Wirtschaftsverfahren in Deutschland attraktiver machen. Dieses Plugin macht daraus einen geführten Arbeitsablauf: nicht Common Law spielen, sondern deutsches Prozessrecht in englischer Arbeitssprache präzise beherrschen.

Es unterstützt insbesondere:

- englische oder zweisprachige Schriftsatzentwürfe,
- Forum- und Klauselprüfung,
- Zuständigkeits- und Sprachwahlprüfung,
- Case-Management-Termin und Timetable,
- Beweis- und Anlagenorganisation,
- Geheimnisschutz und vertrauliche Anlagen,
- Wortprotokoll/verbatim transcript,
- Rechtsmittel und BGH-Fortsetzung,
- Board- und Mandantenbriefings in DE/EN.

## Kaltstart

Der Einstieg fragt zuerst:

1. Deutsch, Englisch oder zweisprachig?
2. Commercial Court, Commercial Chamber, Schiedsgericht oder anderes Forum?
3. Welche Klausel und welcher Streitwert?
4. Was ist die nächste Prozesshandlung?
5. Welche Anlagen und Fristen liegen vor?

Danach routet er in die passenden Spezialskills.

## Typische Outputs

- English Statement of Claim / Statement of Defence
- Case Management Conference Pack
- Procedural Timetable
- Evidence Map und Exhibit Index
- Confidentiality Application
- Verbatim Transcript Request Strategy
- Hearing Script
- Settlement Term Sheet
- Appeal/Revision Memo
- Board Briefing DE/EN

## Quellenhygiene

Vor produktiver Verwendung müssen Bundesrecht, Landesrecht und Gerichtsseite live geprüft werden. Dieses Plugin nennt keine erfundenen Commercial-Court-Standorte und keine Paywall-Fundstellen. Rechtsprechung wird nur mit Gericht, Datum, Aktenzeichen und frei prüfbarer Quelle ausgegeben.

## Verhältnis zu anderen Plugins

- `prozessrecht`: allgemeine ZPO-Mechanik.
- `word-legal-ai-plugin-and-skill-for-german-lawyers`: Schriftsatz- und Stilfinish.
- `gesellschaftsrecht-legal-english`: Transaktionsenglisch und Corporate-Begriffe.
- `common-law-kompass`: falsche Freunde bei Common-Law-Erwartungen.
- `zitierweise-deutsches-recht`: Quellen- und Zitierhygiene.

## Skills

| Skill | Funktion |
| --- | --- |
| `allgemein` | Einstieg, Schnelltriage und Workflow-Routing für Commercial-Courts-Verfahren in Deutschland; erkennt Forum, Sprache, Streitwert, Parteivereinbarung, Case Management, Geheimnisschutz, Beweis, Transcript, Rechtsmittel und englischen Outputbedarf. |
| `commercial-court-kaltstart-interview` | Kaltstart-Interview für neue Commercial-Court-Mandate: Parteien, Streitgegenstand, Streitwert, Gerichtsstands-/Sprachklausel, gewünschte Sprache, Unterlagen, Fristen, Output. |
| `zustandigkeit-119b-gvg-check` | Prüft, ob Commercial Court oder Commercial Chamber eröffnet ist: Wirtschaftsstreitigkeit, Streitwert, Parteivereinbarung, Landesrecht, OLG/LG, internationale Zuständigkeit und Rügefragen. |
| `commercial-chamber-vs-commercial-court` | Vergleicht Commercial Chamber beim Landgericht und Commercial Court beim Oberlandesgericht: Instanz, Zuständigkeit, Streitwert, Verfahrenssprache, Tempo, Rechtsmittel und Mandantenstrategie. |
| `forumwahl-commercial-court-vs-schiedsgericht` | Vergleicht Commercial Court, ordentliche Kammer, Schiedsgericht, DIS/ICC/LCIA und Gerichtsstandsvereinbarung; Output ist eine Vorstandsvorlage mit Empfehlung. |
| `englische-verfahrenssprache-184a-gvg` | Prüft und gestaltet die englische Verfahrenssprache: Parteivereinbarung, Schriftsätze, Anlagen, mündliche Verhandlung, Protokoll, Urteil, Übersetzungen und BGH-Fortsetzung. |
| `jurisdiction-clause-drafting-de-en` | Entwirft deutsch-englische Commercial-Court-Gerichtsstands- und Sprachklauseln für Verträge, AGB-nahe Konstellationen und M&A/Finance-Deals. |
| `pre-litigation-notice-and-standstill` | Bereitet Pre-Action Letter, Standstill Agreement und Verjährungshemmung vor, wenn ein Commercial-Court-Verfahren droht. |
| `claim-intake-fakten-und-exhibits` | Macht aus unordentlichen Deal-Unterlagen ein Claim Intake: Parteien, Vertrag, Breach, Damages, Exhibits, Timeline und Streitwert. |
| `klageschrift-english-statement-of-claim` | Erstellt eine englische Commercial-Court-Klageschrift mit deutschem ZPO-Unterbau: parties, jurisdiction, facts, causes of action, relief sought, evidence und exhibits. |
| `defence-answer-and-jurisdiction-objections` | Bereitet Klageerwiderung/Statement of Defence vor: Zuständigkeitsrügen, Sprachrügen, Bestreiten, Einwendungen, Counterclaim, Set-off und Beweise. |
| `ruegelose-einlassung-und-sprache` | Warnt vor rügeloser Einlassung: Zuständigkeit, Sprache, Einlassungsfrist, Verteidigungsanzeige, Prozessstrategie und Mandantenfreigabe. |
| `case-management-conference` | Bereitet Case-Management-Termin vor: issues list, timetable, evidence, confidentiality, settlement, transcript, language and hearing logistics. |
| `procedural-calendar-timetable-order` | Erstellt einen prozessualen Verfahrenskalender mit Schriftsatzfristen, Anlagen, Übersetzungen, Witness Statements, Sachverständigen und Hearing Date. |
| `issues-list-and-roadmap` | Formuliert eine Issues List für Commercial-Court-Verfahren: legal issues, factual issues, evidence issues, quantum, jurisdiction and language. |
| `evidence-map-zpo-vs-common-law` | Erklärt Mandanten den Unterschied zwischen deutscher Beweisaufnahme und Common-Law-Erwartungen; erstellt Evidence Map ohne Discovery-Fantasien. |
| `document-production-142-zpo` | Prüft Urkundenvorlage und Dokumentenherausgabe nach deutschem Prozessrecht im Commercial-Court-Kontext: § 142 ZPO, Substantiierung, Geheimnisse, proportionality. |
| `exhibits-translation-608-zpo` | Plant Anlagen, Übersetzungen und Sprache: welche Dokumente englisch bleiben können, wann Übersetzung nötig ist, wie Exhibit Index und Bundle aussehen. |
| `third-party-notice-607-zpo` | Prüft Streitverkündung, Nebenintervention und Drittbeteiligung bei englischsprachigen Commercial-Court-Verfahren. |
| `confidentiality-trade-secrets-273a-zpo` | Schützt Geschäftsgeheimnisse: Geheimhaltungsantrag, abgestufter Zugang, redacted exhibits, in camera concerns, Trade Secrets Act und Prozessstrategie. |
| `public-hearing-and-press` | Steuert Öffentlichkeit, Presse, Public Relations und sensitive Unternehmenskommunikation bei hochkarätigen Commercial-Court-Verfahren. |
| `video-hearing-128a-284-zpo` | Prüft Videoverhandlung, hybride Beweisaufnahme, ausländische Zeugen, Techniktest und Protokollierung. |
| `verbatim-transcript-613-zpo` | Plant das Wortprotokoll/verbatim transcript: Antrag, Kosten, Verhandlungsstrategie, Korrektur, Zitierfähigkeit und Nutzung im Rechtsmittel. |
| `hearing-script-english-advocacy` | Erstellt englische Hearing Scripts für deutsche Anwälte: opening, issue roadmap, witness questions, judicial questions, closing and settlement signals. |
| `witness-preparation-english-zpo` | Bereitet Zeugen in englischsprachigen deutschen Verfahren vor: Wahrheitspflicht, keine Coaching-Grenzüberschreitung, Sprachsicherheit, Dokumente, Ablauf. |
| `expert-evidence-german-court-expert` | Plant Sachverständigenbeweis: Privatgutachten, gerichtlicher Sachverständiger, Fragenkatalog, technische Anlagen, Parteigutachten und Anhörung. |
| `interim-relief-arrest-injunction` | Prüft einstweilige Verfügung, Arrest und interim relief im Commercial-Court-Umfeld, einschließlich Eilbedürftigkeit, Sicherheitsleistung und Vollziehung. |
| `settlement-court-recorded-settlement` | Bereitet gerichtlichen Vergleich, settlement agreement, consent order, Vollstreckbarkeit und mehrsprachige Vergleichsdokumentation vor. |
| `enforcement-and-translation` | Prüft Vollstreckung aus Commercial-Court-Urteilen/Vergleichen: Titel, Klausel, Zustellung, Übersetzung, EU-/Auslandsbezug und assets. |
| `appeal-and-revision-614-zpo` | Prüft Rechtsmittel und Revision/BGH-Pfad nach Commercial-Court-Verfahren: Zulassung, Sprache, Transcript, Tatbestand, Rechtsfehler und Strategie. |
| `bgh-english-proceedings-184b-gvg` | Routet englischsprachige Fortführung vor dem Bundesgerichtshof: Voraussetzungen, Übersetzungen, Revisionsbegründung, Tenor und Mandantenkommunikation. |
| `costs-court-fees-risk-budget` | Erstellt Kosten- und Risikobudget: Gerichtskosten, Anwaltskosten, Übersetzung, Transcript, Sachverständige, Security, Settlement und Enforcement. |
| `service-abroad-hague-eu` | Plant Zustellung ins Ausland: EuZVO, Haager Zustellungsübereinkommen, Übersetzung, service agents, Fristen und Nachweis. |
| `cross-border-jurisdiction-brussels-ia` | Prüft internationale Zuständigkeit, Gerichtsstandsvereinbarung, Brüssel Ia, Lugano-Bezug, Drittstaaten und Anti-suit-/lis-pendens-Risiken. |
| `governing-law-rome-i-ii` | Prüft anwendbares Recht: Rom I/Rom II, Rechtswahl, Eingriffsnormen, UN-Kaufrecht, Beweis fremden Rechts und Übersetzung der Normbegriffe. |
| `post-ma-warranty-claim` | Bearbeitet Post-M&A Warranty Claims vor Commercial Courts: notice, knowledge qualifiers, baskets, caps, leakage, earn-out, accounts and expert determination. |
| `earn-out-accounting-dispute` | Strukturiert Earn-out- und Kaufpreisanpassungsstreitigkeiten: accounting principles, expert determination, disclosure, damages and procedural tactics. |
| `shareholder-board-dispute` | Bearbeitet Gesellschafter-, Organ- und Joint-Venture-Streitigkeiten mit englischen Vertragsunterlagen vor deutschen Commercial Courts. |
| `director-officer-liability-dispute` | Prüft D&O-/Organhaftungsstreitigkeiten im Commercial-Court-Kontext: business judgment, damages, insurance, privilege-like concerns and evidence. |
| `supply-chain-international-sale-dispute` | Routet Lieferketten-, Vertrieb- und CISG-nahe Streitigkeiten: delivery, defects, force majeure, limitation, governing law and evidence. |
| `finance-banking-dispute` | Bearbeitet Finance-, Banking- und Capital-Markets-Streitigkeiten mit englischen Dokumenten: facility agreement, covenants, events of default, security, notices. |
| `contract-interpretation-de-en` | Erklärt und prüft englische Vertragsbegriffe unter deutschem Recht: reasonable efforts, best endeavours, indemnity, warranty, termination, material adverse change. |
| `english-legal-writing-for-german-courts` | Verbessert englische Schriftsätze für deutsche Gerichte: klar, zpo-tauglich, ohne US-Discovery-Duktus, mit sauberem Tatsachenvortrag und Beweisangebot. |
| `bilingual-client-board-briefing` | Erstellt bilinguale Board- und Mandantenbriefings zu Commercial-Court-Verfahren: risk, timeline, budget, settlement range, next decisions. |
| `bundle-index-electronic-filing` | Organisiert elektronisches Bundle, Anlagenindex, beA/ERV-Dateinamen, PDF/A, Lesezeichen, Übersetzungen und Exhibit References. |
| `bea-erv-english-pleadings` | Prüft beA/ERV-Einreichung englischer Schriftsätze: Dateiformat, Signatur, Anlagen, Fristen, Empfangsbekenntnis und Kanzlei-Workflow. |
| `protective-measures-confidential-exhibits` | Plant Schutzmaßnahmen für vertrauliche Anlagen: redactions, confidentiality club, restricted access, sealed bundles und Verhandlungsorganisation. |
| `mediation-settlement-window` | Findet Vergleichsfenster, Mediation, judicial settlement signals und Prozessvergleichsstrategie in Commercial-Court-Verfahren. |
| `arbitration-clause-conflict-check` | Prüft Konflikte zwischen Schieds-, Gerichtsstands-, Escalation- und Commercial-Court-Klauseln. |
| `limitation-and-tolling-check` | Prüft Verjährung, Hemmung, Standstill, Klageerhebung, Zustellung demnächst und internationale Limitation Issues. |
| `counterclaim-setoff-claim-amendment` | Plant Widerklage, Hilfswiderklage, Aufrechnung, Klageänderung und amendment strategy in englischsprachigen Wirtschaftsprozessen. |
| `default-judgment-and-nonappearance` | Prüft Versäumnis, Anerkenntnis, Säumnisfolgen, Einspruch und taktische Nichtteilnahme in Commercial-Court-Verfahren. |
| `late-submissions-296-zpo` | Steuert verspätetes Vorbringen, Präklusion, Fristverlängerung, gerichtliche Hinweise und Schriftsatznachlass. |
| `local-rules-and-court-guidelines` | Erstellt Live-Check zu Landesrecht, Geschäftsverteilung, Commercial-Court-Guidelines und Gerichts-Webseite vor jeder Einreichung. |
| `redteam-commercial-court-qualitygate` | Red-Team-Gate für alle Commercial-Court-Outputs: Zuständigkeit, Sprache, Fristen, Beweise, Übersetzungen, Geheimnisschutz, Kosten, Rechtsmittel. |
| `glossary-commercial-court-de-en` | Erstellt ein DE/EN-Glossar für Commercial-Court-Mandate: ZPO-Begriffe, Anträge, Beweis, Tenor, Vergleich, Rechtsmittel und falsche Freunde. |
| `judgment-publication-and-anonymisation` | Prüft Urteil, Veröffentlichung, Anonymisierung, Geheimnisschutz, Übersetzungsbedarf und externe Kommunikation nach Entscheidung. |

## Lizenz

Apache-2.0 OR MIT. Siehe Repository-Stammverzeichnis.


<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 30 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `allgemein` | Einstieg, Schnelltriage und Workflow-Routing für Commercial-Courts-Verfahren in Deutschland; erkennt Forum, Sprache, Streitwert, Parteivereinbarung, Case Management, Geheimnisschutz, Beweis, Transcript, Rechtsmittel und englischen Output... |
| `arbitration-clause-bea-erv` | Arbitration Clause Conflict Check, Bea Erv English Pleadings: Arbitration Clause Conflict Check; Bea Erv English Pleadings. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zusammen. |
| `bgh-english-bilingual-client` | Bgh English Proceedings 184B Gvg, Bilingual Client Board Briefing: Bgh English Proceedings 184B Gvg; Bilingual Client Board Briefing. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zusammen. |
| `bundle-index-case-management` | Bundle Index Electronic Filing, Case Management Conference: Bundle Index Electronic Filing; Case Management Conference. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zusammen. |
| `claim-intake-chamber-vs` | Claim Intake Fakten Und Exhibits, Commercial Chamber Vs Commercial Court: Claim Intake Fakten Und Exhibits; Commercial Chamber Vs Commercial Court. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätsc... |
| `commercial-court-kaltstart-interview` | Kaltstart-Interview für neue Commercial-Court-Mandate: Parteien, Streitgegenstand, Streitwert, Gerichtsstands-/Sprachklausel, gewünschte Sprache, Unterlagen, Fristen, Output. |
| `confidentiality-trade-contract-interpretation` | Confidentiality Trade Secrets 273A Zpo, Contract Interpretation De En: Confidentiality Trade Secrets 273A Zpo; Contract Interpretation De En. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck z... |
| `costs-court-counterclaim-setoff` | Costs Court Fees Risk Budget, Counterclaim Setoff Claim Amendment: Costs Court Fees Risk Budget; Counterclaim Setoff Claim Amendment. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zusammen. |
| `cross-border-default-judgment` | Cross Border Jurisdiction Brussels Ia, Default Judgment And Nonappearance: Cross Border Jurisdiction Brussels Ia; Default Judgment And Nonappearance. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualität... |
| `defence-answer-director-officer` | Defence Answer And Jurisdiction Objections, Director Officer Liability Dispute: Defence Answer And Jurisdiction Objections; Director Officer Liability Dispute. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster un... |
| `document-production-earn-out` | Document Production 142 Zpo, Earn Out Accounting Dispute: Document Production 142 Zpo; Earn Out Accounting Dispute. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zusammen. |
| `enforcement-translation-english-legal` | Enforcement And Translation, English Legal Writing For German Courts: Enforcement And Translation; English Legal Writing For German Courts. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zus... |
| `englische-verfahrenssprache-late-submissions` | Englische Verfahrenssprache 184A Gvg, Late Submissions 296 Zpo: Englische Verfahrenssprache 184A Gvg; Late Submissions 296 Zpo. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zusammen. |
| `evidence-map-exhibits-translation` | Evidence Map Zpo Vs Common Law, Exhibits Translation 608 Zpo: Evidence Map Zpo Vs Common Law; Exhibits Translation 608 Zpo. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zusammen. |
| `expert-evidence-finance-banking` | Expert Evidence German Court Expert, Finance Banking Dispute: Expert Evidence German Court Expert; Finance Banking Dispute. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zusammen. |
| `forumwahl-court-glossary-court` | Forumwahl Commercial Court Vs Schiedsgericht, Glossary Commercial Court De En: Forumwahl Commercial Court Vs Schiedsgericht; Glossary Commercial Court De En. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und... |
| `governing-law-hearing-script` | Governing Law Rome I Ii, Hearing Script English Advocacy: Governing Law Rome I Ii; Hearing Script English Advocacy. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zusammen. |
| `interim-relief-issues-list` | Interim Relief Arrest Injunction, Issues List And Roadmap: Interim Relief Arrest Injunction; Issues List And Roadmap. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zusammen. |
| `judgment-publication-jurisdiction-clause` | Judgment Publication And Anonymisation, Jurisdiction Clause Drafting De En: Judgment Publication And Anonymisation; Jurisdiction Clause Drafting De En. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualit... |
| `klageschrift-english-limitation-tolling` | Klageschrift English Statement Of Claim, Limitation And Tolling Check: Klageschrift English Statement Of Claim; Limitation And Tolling Check. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck z... |
| `local-rules-mediation-settlement` | Local Rules And Court Guidelines, Mediation Settlement Window: Local Rules And Court Guidelines; Mediation Settlement Window. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zusammen. |
| `post-ma-pre-litigation` | Post Ma Warranty Claim, Pre Litigation Notice And Standstill: Post Ma Warranty Claim; Pre Litigation Notice And Standstill. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zusammen. |
| `procedural-calendar-protective-measures` | Procedural Calendar Timetable Order, Protective Measures Confidential Exhibits: Procedural Calendar Timetable Order; Protective Measures Confidential Exhibits. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster un... |
| `public-hearing-appeal-revision` | Public Hearing And Press, Appeal And Revision 614 Zpo: Public Hearing And Press; Appeal And Revision 614 Zpo. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zusammen. |
| `redteam-commercial-court-qualitygate` | Red-Team-Gate für alle Commercial-Court-Outputs: Zuständigkeit, Sprache, Fristen, Beweise, Übersetzungen, Geheimnisschutz, Kosten, Rechtsmittel. |
| `ruegelose-einlassung-service-abroad` | Ruegelose Einlassung Und Sprache, Service Abroad Hague Eu: Ruegelose Einlassung Und Sprache; Service Abroad Hague Eu. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zusammen. |
| `settlement-court-shareholder-board` | Settlement Court Recorded Settlement, Shareholder Board Dispute: Settlement Court Recorded Settlement; Shareholder Board Dispute. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zusammen. |
| `supply-chain-third-party` | Supply Chain International Sale Dispute, Third Party Notice 607 Zpo: Supply Chain International Sale Dispute; Third Party Notice 607 Zpo. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zusam... |
| `verbatim-transcript-video-hearing` | Verbatim Transcript 613 Zpo, Video Hearing 128A 284 Zpo: Verbatim Transcript 613 Zpo; Video Hearing 128A 284 Zpo. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zusammen. |
| `witness-preparation-zustandigkeit-119b` | Witness Preparation English Zpo, Zustandigkeit 119B Gvg Check: Witness Preparation English Zpo; Zustandigkeit 119B Gvg Check. Führt Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck zusammen. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
