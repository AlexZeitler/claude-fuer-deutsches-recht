---
name: kompendium-17-weg-abrechnung-miete-bis-weg-abrechnung-miete
description: "immobilienrechtspraxis: eigenständiger Arbeits-Skill zu Weg Abrechnung Mieterschnittstelle Datenpaket; mit Intake, Prüfroutine, Normen-/Quellenradar, Beweislogik, Outputmuster und Qualitätscheck."
---

# Arbeitsbereich - Weg Abrechnung Mieterschnittstelle Datenpaket

## Zweck

Dieser Skill ist ein eigenständiger Arbeitsbereich. Er verbindet mehrere sachlich benachbarte Arbeitsmodule, Wähle anhand des Sachverhalts das passende Modul, arbeite dessen Prüfroutine vollständig ab und kombiniere Module nur, wenn der Fall tatsächlich mehrere Themen berührt.

## Arbeitsmodule

| Arbeitsmodul | Fokus |
| --- | --- |
| `weg-abrechnung-mieterschnittstelle-datenpaket` | Datenpaket WEG-Abrechnung zu Mietern: übersetzt Jahresabrechnung, Einzelabrechnung, Wirtschaftsplan, Heizkosten, CO2-Daten und Belege in eine mietrechtlich brauchbare Betriebskostenabrechnung; mit Abrechnungsspitze, nicht umlagefähigen Positionen und Eigentümerkommunikation. |

## Arbeitsregel

1. Zuerst das passende Arbeitsmodul oder Sachthema auswählen.
2. Danach die dortige Prüfroutine, Normen-/Quellenanker, Beweislogik und Output-Vorgabe vollständig anwenden.
3. Bei mehreren passenden Arbeitsmodulen eine kurze Synopse bilden, Überschneidungen offen markieren und nichts vermischen, was getrennte Fristen, Zuständigkeiten, Anspruchsgrundlagen oder Beweislasten hat.
4. Rechtsprechung, Literatur, Behördenpraxis und Tagesrecht nur mit überprüfbarer Quelle oder Nutzerquelle ausgeben.

## Arbeitsmodule im Detail

## 1. `weg-abrechnung-mieterschnittstelle-datenpaket`

**Fokus:** Datenpaket WEG-Abrechnung zu Mietern: übersetzt Jahresabrechnung, Einzelabrechnung, Wirtschaftsplan, Heizkosten, CO2-Daten und Belege in eine mietrechtlich brauchbare Betriebskostenabrechnung; mit Abrechnungsspitze, nicht umlagefähigen Positionen und Eigentümerkommunikation.

# WEG-Abrechnung als Mieterdatenpaket

## Fachkern: WEG-Abrechnung als Mieterdatenpaket
- **Spezialgegenstand:** WEG-Abrechnung als Mieterdatenpaket wird als eigener Falltyp behandelt; der Skill muss ein konkretes Ergebnis liefern, nicht nur Einstieg und Routing.
- **Normen-/Quellenanker:** BGB, GBO, WEG, BauGB, ErbbauRG, MaBV, Mietrecht, Grundpfandrechte, Notar-/Registervollzug und öffentlich-rechtliche Lasten.
- **Entscheidende Weiche:** Trenne Eigentum, Besitz, Grundbuchabteilung, Belastung, Fälligkeit, Vollzug, Mängel, Miet-/Nutzungsverhältnis und Finanzierung.
- **Lösungsoutput:** Erzeuge eine fallbezogene Matrix `Norm / Tatbestand / Beleg / Risiko / Gegenargument / nächster Schritt` und benenne passende Anschluss-Skills nur, wenn sie wirklich eine Vertiefung lösen.


## Aufgabe

Dieser Skill hilft, wenn ein vermietender Wohnungseigentümer seine WEG-Unterlagen bekommt und daraus eine Betriebskostenabrechnung für den Mieter erstellen muss. Er verhindert, dass interne WEG-Kosten unbesehen in das Mietverhältnis rutschen.

## Trennung

- **GdWE/Eigentümer**: Nachschüsse und Vorschussanpassungen aus § 28 Abs. 2 WEG.
- **Vermieter/Mieter**: Betriebskosten nach Mietvertrag, BetrKV, HeizkostenV, CO2KostAufG und § 556 BGB.
- **Hausverwaltung**: Datenlieferantin, nicht automatisch mietrechtliche Abrechnungsstelle.

## Datenanforderung an WEG-Verwaltung

1. Gesamt- und Einzelabrechnung.
2. Verteilungsschlüssel je Kostenart.
3. Rechnungen und Zahlungsbelege.
4. Heizkostenabrechnung mit Nutzerwechseln.
5. CO2-Daten aus Brennstoffrechnung.
6. Tätigkeits-/Stundenlisten für Hausmeister.
7. Liste nicht umlagefähiger Kosten: Verwalter, Rücklage, Reparaturen, Prozesskosten, Bank-/Finanzierungskosten.

## Übersetzungstabelle

| WEG-Unterlage | Mietrechtliche Nutzung | Risiko |
| --- | --- | --- |
| Einzelabrechnung | Ausgangsdaten | enthält nicht umlagefähige Positionen |
| Wirtschaftsplan | Vorauszahlungsprognose | keine Jahresabrechnung |
| Beschluss § 28 WEG | Zahlungspflicht Eigentümer | nicht Zahlungspflicht Mieter |
| Vermögensbericht | Transparenz WEG | nicht in Betriebskostenabrechnung |
| Heizkostenanlage | Mieterabrechnung | HeizkostenV/CO2 prüfen |

## Output

- Datenpaket-Checkliste für Verwaltung.
- Mietrechtliche Übernahmematrix.
- Entwurf Betriebskostenabrechnung aus WEG-Daten.
- Schreiben an Eigentümer: welche Positionen nicht umgelegt werden dürfen.

## Quellenregel

§ 28 WEG, § 556 BGB, BetrKV, HeizkostenV und CO2KostAufG aktuell prüfen. WEG-Rechtsprechung zu Abrechnungsspitzen nur mit Gericht, Datum, Aktenzeichen und frei prüfbarer Quelle nennen.
