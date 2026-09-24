# Allergen-Poster

Allergen-Deklaration für Take-aways, Beizen, Food-Trucks, Vereinsfeste und Kantinen:
Gerichte eintragen, die 14 Allergene antippen, Poster drucken. **Nichts wird gesendet.**

Live: **https://richardcervenka111-create.github.io/allergen-poster/**

## Warum

Die LIV (Verordnung des EDI betreffend die Information über Lebensmittel) verlangt die
Deklaration der 14 Allergene aus Anhang 6 auch für offen angebotene Speisen (Art. 5).
Grosse Betriebe haben dafür Software; der Kebab-Stand, der Food-Truck und das Vereinsfest
haben ein Blatt Papier oder nichts. Für Menschen mit einer Allergie ist das Blatt an der Wand
der Unterschied zwischen einem sicheren Essen und dem Notruf 144.

## Was es macht

- Formular DE / FR / IT / EN, Poster in der gewählten Sprache, Legende optional zweisprachig.
- Die 14 Allergene in der gesetzlichen Reihenfolge mit Beispielen (Glutenhaltiges Getreide,
  Krebstiere, Eier, Fische, Erdnüsse, Soja, Milch, Schalenfrüchte, Sellerie, Senf, Sesam,
  Sulfite, Lupinen, Weichtiere).
- Karte als Liste einfügen (eine Zeile pro Gericht), pro Gericht Bemerkung («auch glutenfrei»).
- Hinweise wählbar: Spuren, mündliche Auskunft mit Ansprechperson, eigener Zusatz.
- A4 hoch oder quer, Druck über den Browser, A3 per Skalierung. Datum «Stand» auf dem Poster.
- Entwurf bleibt auf Wunsch im Browser («Auf diesem Gerät merken», standardmässig an, weil es
  eine Speisekarte ist und keine Gesundheitsdaten). «Alles löschen» mit Doppel-Tipp.
- Ohne Eingaben zeigt die Vorschau ein Beispiel («Restaurant Sonne») mit Wasserzeichen.

## Verantwortung

Die Seite ordnet nur an, was der Betrieb ankreuzt. Richtig ist die Deklaration, wenn Rezeptur
und Zutaten-Etiketten geprüft wurden. Bei Unsicherheit hilft das kantonale
Lebensmittelinspektorat; für den Kanton Bern das Amt für Veterinärwesen (Lebensmittelkontrolle).

## Technik

Eine Datei, keine Skripte von Dritten, kein `fetch`, kein Server; der Deploy-Workflow bricht ab,
wenn ein Netzwerkaufruf im Code auftaucht. Einzige externe Ressource: Schrift von Google Fonts
mit System-Fallback. Lizenz CC0.

## Verwandt

[Bärn hilft](https://github.com/richardcervenka111-create/baern-hilft) ·
[Notfallblatt](https://github.com/richardcervenka111-create/notfallblatt)
