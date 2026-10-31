# Kraftzirkel

Krafttraining zu Hause, zweimal pro Woche. Eine Seite fürs Handy, im Stil von [Tagesgeld](https://github.com/AlbrechtBuehler/tagesgeld).

Sechs Übungen ohne Geräte, jede Runde wird abgehakt. Oben steht, wie viele Einheiten diese Woche erledigt sind (Ziel: zwei), unten der Verlauf der letzten sechs Wochen.

- **Woche** zählt ab dem Tag der ersten Einheit. In Woche 1 und 2 schlägt die App zwei Runden vor, ab Woche 3 drei; umstellen lässt es sich jeden Tag von Hand.
- **Eine Einheit gilt als erledigt**, wenn alle Übungen in allen Runden abgehakt sind. Angefangene Einheiten erscheinen im Verlauf gestreift.
- Der Unterarmstütz hat eine Stoppuhr, die am Ende vibriert, wo das Handy es kann.

## Daten

Nur auf dem Gerät (`localStorage`). In dieses Repo gehört nie eine echte Zahl.

«Heute zurücksetzen» löscht die Häkchen des Tages, «Alles zurücksetzen» nach einer Rückfrage alle Einheiten und den Startpunkt.

## Dateien

| Datei | Was |
| --- | --- |
| `index.html` | die App, Schrift Jost eingebettet |
| `sw.js` | hält die App für den Start ohne Netz; bei jeder neuen Fassung `FASSUNG` hochzählen |
| `manifest.webmanifest`, `icon-*.png` | Installation auf dem Startbildschirm |
