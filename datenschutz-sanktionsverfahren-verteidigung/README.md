# Datenschutz-Sanktionsverfahren und Verteidigung

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`datenschutz-sanktionsverfahren-verteidigung`) | [`datenschutz-sanktionsverfahren-verteidigung.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/datenschutz-sanktionsverfahren-verteidigung.zip) |

Dieses Plugin hat (bewusst) keine eigene Demonstrations-Akte.

<!-- END plugin-sofort-download-section (autogen) -->

Dieses Plugin ist die Spezialwerkstatt für Mandate, in denen Datenschutzaufsicht nicht mehr nur Beratung ist, sondern Druck macht: Anhörung, Auskunftsverlangen, Art.-58-Anordnung, Bußgeldbescheid, Einspruch, Hauptverhandlung, Rechtsbeschwerde, Verwaltungsgericht und EuGH-Frage. Es ergänzt `datenschutzrecht`, ist aber bewusst eigenständig, weil solche Verfahren prozessual anders funktionieren als AVV, DSFA oder Datenschutzerklärung.

## Wofür es gedacht ist

- Verteidigung gegen DSGVO-Geldbußen nach Art. 83 DSGVO.
- Vertretung im OWiG-Verfahren nach § 41 BDSG, einschließlich Akteneinsicht, Einspruch, Zwischenverfahren, gerichtlicher Hauptverhandlung, Beschlussverfahren und Rechtsbeschwerde.
- Abwehr oder Verhandlung von Aufsichtsmaßnahmen nach Art. 58 Abs. 2 DSGVO: Verwarnung, Anordnung, Löschung, Verarbeitungsstopp, Drittlandtransfer-Stopp, Zwangsmittel und Veröffentlichungsrisiken.
- Verwaltungsgerichtlicher Rechtsschutz nach Art. 78 DSGVO und § 20 BDSG, wenn es nicht um die Geldbuße selbst geht.
- Koordination mit Datenpanne, Art.-82-Schadensersatz, Strafrecht, Geschäftsführung, D&O, Presse und internationalem One-Stop-Shop.

## Der wichtigste erste Satz im Mandat

Nicht sofort "kooperativ" alles erzählen. Erst verstehen, welche Spur läuft. Datenschutzrechtliche Mitwirkung, OWiG-Verteidigung und verwaltungsgerichtlicher Rechtsschutz haben unterschiedliche Regeln. Das Plugin fragt deshalb zuerst:

1. Liegt nur ein Auskunftsverlangen, eine Anhörung, ein Bußgeldbescheid oder eine Art.-58-Anordnung vor?
2. Wer ist Adressat und welche Behörde ist zuständig: Landesaufsicht, BfDI, kirchliche Datenschutzaufsicht oder federführende EU-Aufsicht?
3. Welche Frist läuft und wie wurde zugestellt?
4. Geht es um Geldbuße, Maßnahme, beides oder Folgerisiken?
5. Was ist belegt und was behauptet die Behörde nur?

## Zwei Hauptspuren

| Spur | Typischer Rechtsweg | Typische Arbeit |
| --- | --- | --- |
| **Bußgeld** | Art. 83 DSGVO, § 41 BDSG, OWiG/StPO sinngemäß; Einspruch nach § 67 OWiG; Zuständigkeit nach § 68 OWiG, modifiziert durch § 41 BDSG | Anhörung, Akteneinsicht, Bußgeldbescheid, Einspruch, Zwischenverfahren, Hauptverhandlung, Beschlussverfahren, Rechtsbeschwerde |
| **Aufsichtsmaßnahme** | Art. 58/78 DSGVO, § 20 BDSG, VwGO | Anordnung prüfen, Bestimmtheit/Ermessen/Verhältnismäßigkeit, Anfechtungsklage, Eilrechtsschutz, Umsetzung/Verhandlung |

## Leitentscheidungen und Stand

Stand: Juni 2026. Besonders wichtig sind EuGH, Urteil vom 05.12.2023, C-807/21 (Deutsche Wohnen), und EuGH, Urteil vom 05.12.2023, C-683/21 (Nacionalinis visuomenės sveikatos centras). Die Linie ist: Ein Unternehmen kann unmittelbar Adressat einer DSGVO-Geldbuße sein; die Aufsicht muss nicht zuerst eine natürliche Person identifizieren. Zugleich bleibt Vorsatz oder Fahrlässigkeit erforderlich. Das Plugin behandelt diese Linie als Prüfprogramm, nicht als Freibrief für schematische Unternehmenshaftung.

## Quellenhygiene

Keine BeckRS-, juris-, Kommentar- oder Aufsatz-Blindzitate. Normen und Rechtsprechung werden vor Ausgabe mit amtlichen oder frei zugänglichen Quellen geprüft, insbesondere:

- DSGVO über EUR-Lex.
- BDSG und OWiG über gesetze-im-internet.de.
- EuGH über CURIA/EUR-Lex.
- EDPB Guidelines 04/2022 über edpb.europa.eu.
- Deutsche Gerichtsentscheidungen nur mit Gericht, Entscheidungsform, Datum, Aktenzeichen und freier/amtlicher Quelle.

## Typische Outputs

- Behördenpost-Analyse: Was ist das, was droht, welche Frist läuft?
- Akteneinsichtsantrag und fristwahrender Einspruch.
- Stellungnahme vor Bußgeldbescheid.
- Art.-83-Bemessungsgegenrechnung nach EDPB 04/2022.
- Verschuldens- und Organisationsmemo nach EuGH C-807/21/C-683/21.
- Klage-/Eilantragsgerüst gegen Art.-58-Anordnung.
- Terminsmappe für Hauptverhandlung im Bußgeldverfahren.
- Management-Briefing für Vorstand/Geschäftsführung.
- Schlussmemo mit Remediation, Wiedervorlagen und Lessons Learned.

## Gute Startbefehle

```text
/datenschutz-sanktionsverfahren-verteidigung:kaltstart-verfahrensstand-und-mandatsziel
/datenschutz-sanktionsverfahren-verteidigung:bescheid-oder-anhoerung-richtig-lesen
/datenschutz-sanktionsverfahren-verteidigung:akteneinsicht-49-owig-147-stpo
/datenschutz-sanktionsverfahren-verteidigung:zustaendigkeit-amtsgericht-landgericht-41-bdsg
/datenschutz-sanktionsverfahren-verteidigung:art-58-anordnung-verwaltungsakt
/datenschutz-sanktionsverfahren-verteidigung:edpb-04-2022-bemessungsmethodik
```

## Skill-Logik

Die 100 Skills sind nicht als lose Liste gedacht, sondern als Verteidigungsmaschine: Kaltstart, Behördenvorfeld, Bußgeld/OWiG, Art.-83-Bemessung, Verwaltungsgericht, EU-One-Stop-Shop, Beweise/Forensik und Output. Jeder Skill soll die Mandantin handlungsfähiger machen und nicht bloß Normen aufsagen.


<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 27 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `kaltstart-verfahrensstand-und-mandatsziel` | Kaltstart Verfahrensstand und Mandatsziel: Anhörung, Bußgeldbescheid, Art.-58-Anordnung, Verwaltungsstreit und Gerichtsphase in zehn Minuten trennen. Normanker: DSGVO Art. 58 und 77-84; BDSG § 41; OWiG §§ 46 und 55 und 66-72; StPO über §... |
| `kompendium-01-arbeitnehmerdaten-un-bis-einspruch-67-owig-fr` | datenschutz-sanktionsverfahren-verteidigung: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Arbeitnehmerdaten Und Betriebsrat Im Sanktionsverfahren, Beschlussverfahren 72 Owig, Beschwerde Betroffener Behoerdenverfahren, Eins... |
| `kompendium-02-fristenzentrale-zust-bis-ki-tools-im-sanktion` | datenschutz-sanktionsverfahren-verteidigung: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Fristenzentrale Zustellung Und Wiedervorlage, Fristverlaengerung Behoerde Ohne Nachteile, Grch Verfahrensgrundrechte, Ki Tools Im Sa... |
| `kompendium-03-parallelverfahren-ar-bis-sachverstaendige-it` | datenschutz-sanktionsverfahren-verteidigung: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Parallelverfahren Art 82 Massenklagen, Parallelverfahren Strafrecht 42 Bdsg, Rechtsweg Router Bussgeld Verwaltungsgericht Zivilverfa... |
| `kompendium-04-wiedereinsetzung-nac-bis-aufsichtliche-anordn` | datenschutz-sanktionsverfahren-verteidigung: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Wiedereinsetzung Nach Fristversaeumnis, Zustaendigkeit Amtsgericht Landgericht 41 Bdsg, Zwischenverfahren 69 Owig, Aufsichtliche Ano... |
| `kompendium-05-bussgeldbescheid-65-bis-fruehstellungnahme-v` | datenschutz-sanktionsverfahren-verteidigung: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Bussgeldbescheid 65 Owig Analyse, Bussgeldreduzierung Verhandlungspaket, Datenpanne Vor Bussgeld Selbstmeldung, Fruehstellungnahme V... |
| `kompendium-06-kirchliche-datenschu-bis-sanktionsmandat-schl` | datenschutz-sanktionsverfahren-verteidigung: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Kirchliche Datenschutzaufsicht Sanktionen, Massnahmenplan Als Sanktionsminderung, Oeffentliche Stellen Bussgeldprivilegien, Sanktion... |
| `kompendium-07-veroeffentlichung-vo-bis-akteneinsicht-49-owi` | datenschutz-sanktionsverfahren-verteidigung: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Veroeffentlichung Von Bussgeldentscheidungen, Anwesenheit 73 Owig Vertretung, One Stop Shop Art 56 60, Akteneinsicht 49 Owig 147 Stp... |
| `kompendium-08-anhoerung-55-owig-bis-art-83-abs-2-kriteri` | datenschutz-sanktionsverfahren-verteidigung: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Anhoerung 55 Owig, Art 58 Anordnung Verwaltungsakt, Art 78 Rechtsschutz Und Betroffenenbeschwerde, Art 83 Abs 2 Kriterien Einzeln; m... |
| `kompendium-09-aufsicht-in-regulier-bis-auslaendische-mutter` | datenschutz-sanktionsverfahren-verteidigung: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Aufsicht In Regulierten Branchen, Aufsichtsbehoerden Antwortschreiben, Aufsichtsbehoerden Auskunftsverlangen Art 58 1, Auslaendische... |
| `kompendium-10-behoerdenkommunikati-bis-behoerdenvergleich-e` | datenschutz-sanktionsverfahren-verteidigung: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Behoerdenkommunikation Reputationsschutz, Behoerdenstrategie Kooperation Oder Schweigen, Behoerdenuntaetigkeit Und Beschwerdegegner,... |
| `kompendium-11-bescheid-oder-anhoer-bis-beweisrecht-stpo-im` | datenschutz-sanktionsverfahren-verteidigung: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Bescheid Oder Anhoerung Richtig Lesen, Besondere Datenkategorien Art 9, Bestimmtheit Und Ermessen Art 58, Beweisrecht Stpo Im Owig D... |
| `kompendium-12-bfdi-vs-landesaufsic-bis-durchsuchung-beschla` | datenschutz-sanktionsverfahren-verteidigung: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Bfdi Vs Landesaufsicht, Datenloeschung Vs Beweissicherung, Dokumentenmatrix Akteneinsicht Vorlage Und Luecken, Durchsuchung Beschlag... |
| `kompendium-13-edpb-04-2022-bemessu-bis-einstellung-anregen` | datenschutz-sanktionsverfahren-verteidigung: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Edpb 04 2022 Bemessungsmethodik, Edpb Art 65 Streitbeilegung, Edsa Und Dsk Praxis Livecheck, Einstellung Anregen Vor Bescheid; mit I... |
| `kompendium-14-einstweilige-anordnu-bis-gewinnabschoepfung-u` | datenschutz-sanktionsverfahren-verteidigung: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Einstweilige Anordnung 123 Vwgo Datenschutz, Eugh Vorlage Art 267, Gerichtstermin Sprechzettel, Gewinnabschoepfung Und Finanzieller... |
| `kompendium-15-hauptverhandlung-71-bis-irische-dpc-und-deut` | datenschutz-sanktionsverfahren-verteidigung: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Hauptverhandlung 71 Owig, Internationale Datenpanne Und Multi Notification, Interne Untersuchung Legal Hold, Irische Dpc Und Deutsch... |
| `kompendium-16-kinder-und-schutzbed-bis-loeschkonzept-und-au` | datenschutz-sanktionsverfahren-verteidigung: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Kinder Und Schutzbeduerftige Betroffene, Kosten Auslagen Und D Und O Risiko, Lieferanten Und Auftragsverarbeiter Regress, Loeschkonz... |
| `kompendium-17-loeschungsanordnung-bis-mandantenreport-regu` | datenschutz-sanktionsverfahren-verteidigung: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Loeschungsanordnung Und Datenbestand, Logfiles Und Technische Beweise, Mandanteninterview Ohne Selbstbelastung, Mandantenreport Regu... |
| `kompendium-18-mehrere-verstoesse-u-bis-normenkollision-gehe` | datenschutz-sanktionsverfahren-verteidigung: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Mehrere Verstoesse Und Art 83 3, Milderung Durch Compliance Vor Dem Vorfall, Milderung Durch Remediation Nach Dem Vorfall, Normenkol... |
| `kompendium-19-organisationsverschu-bis-public-sector-und-ve` | datenschutz-sanktionsverfahren-verteidigung: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Organisationsverschulden Ersteinschaetzung, Privilege Und Mandatsgeheimnis, Profiling Und Automatisierte Entscheidungen, Public Sect... |
| `kompendium-20-rechtsbeschwerde-79-bis-selbstbelastungsfrei` | datenschutz-sanktionsverfahren-verteidigung: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Rechtsbeschwerde 79 Owig, Schlussmemo Und Lessons Learned, Scope Cut Behoerdenfragen Einhegen, Selbstbelastungsfreiheit Und Mitwirku... |
| `kompendium-21-staatsanwaltschaft-i-bis-umsatz-und-wirtschaf` | datenschutz-sanktionsverfahren-verteidigung: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Staatsanwaltschaft Im Dsgvo Owig, Tracking Cookies Und Ttddg Schnittstelle, Transferstopp Drittland Art 58, Umsatz Und Wirtschaftlic... |
| `kompendium-22-unternehmensgruppe-u-bis-verhaeltnismaessigke` | datenschutz-sanktionsverfahren-verteidigung: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Unternehmensgruppe Und Federfuehrende Aufsicht, Untersagung Und Verarbeitungsstopp, Unverhaeltnismaessigkeit Und Existenzgefahr, Ver... |
| `kompendium-23-verteidigerrolle-dsb-bis-vg-eilrechtsschutz-8` | datenschutz-sanktionsverfahren-verteidigung: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Verteidigerrolle Dsb Gf Und Externe Berater, Verwarnung Art 58 2 B, Vg Anfechtungsklage 20 Bdsg, Vg Eilrechtsschutz 80 5 Vwgo; mit I... |
| `kompendium-24-videoueberwachung-un-bis-vorstands-und-gf-bri` | datenschutz-sanktionsverfahren-verteidigung: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Videoueberwachung Und Biometrie, Vorbelastungen Und Wiederholungstaeter, Vorsatz Fahrlaessigkeit Unternehmen, Vorstands Und Gf Brief... |
| `kompendium-25-zeugeninterviews-mit-bis-zwangsgeld-und-volls` | datenschutz-sanktionsverfahren-verteidigung: eigenständiger Arbeits-Skill für verwandte Arbeitsmodule zu Zeugeninterviews Mitarbeiter, Zwangsgeld Und Vollstreckung Aufsicht; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Out... |
| `red-team-vor-jeder-einreichung` | Red Team vor jeder Einreichung: Stellungnahme, Klage und Einspruchsbegründung auf Selbstwidersprüche, Blindzitate und Beweisrisiken prüfen. Normanker: DSGVO Art. 58 und 77-84; BDSG § 41; OWiG §§ 46 und 55 und 66-72; StPO über § 46 OWiG;... |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
