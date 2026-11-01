# Kraftzirkel

Bewegung zu Hause und unterwegs: Gehen jeden Tag, Krafttraining dreimal pro Woche, Atmen zum Runterkommen. Eine Seite fürs Handy, im Stil von [Tagesgeld](https://github.com/AlbrechtBuehler/tagesgeld).

Oben steht, wie viele Vorhaben heute erledigt sind, darunter die Woche: Krafteinheiten (Ziel drei), Wege (18) und Minuten Atmen. Unten der Verlauf der letzten sechs Wochen.

## Gehen

Jeden Tag ein paar Häkchen, je nach Wochentag:

| Tage | Wege |
| --- | --- |
| Montag bis Freitag | Zum Bahnhof, Vom Bahnhof, Abendspaziergang |
| Samstag | Haushalt, Spaziergang |
| Sonntag | Langer Spaziergang |

## Krafttraining

Sechs Übungen ohne Geräte, jede Runde wird abgehakt. Die Figuren zeigen Bewegung und Tempo, Antippen vergrössert sie.

- **Geplant Montag, Mittwoch, Freitag.** Fällt ein Tag aus, schlägt die App vor, ihn später in derselben Woche nachzuholen.
- **Ruhetag:** Wer gestern trainiert hat, bekommt heute den Hinweis auf den Ruhetag. Die Übungen lassen sich trotzdem öffnen.
- **Woche** zählt ab dem Tag der ersten Einheit. In Woche 1 und 2 schlägt die App zwei Runden vor, ab Woche 3 drei; umstellen lässt es sich jeden Tag von Hand.
- **Eine Einheit gilt als erledigt**, wenn alle Übungen in allen Runden abgehakt sind. Angefangene Einheiten erscheinen im Verlauf gestreift.
- Der Unterarmstütz hat eine Stoppuhr, die am Ende vibriert, wo das Handy es kann.

## Atmen

Vier geführte Übungen: ein Kreis wächst beim Einatmen und schrumpft beim Ausatmen, dazu Wort und Sekunden.

| Übung | Ablauf | Dauer |
| --- | --- | --- |
| Ruhig 5–5 | 5 Sek. ein, 5 Sek. aus | 3, 5 oder 10 Min. |
| Lang aus 4–6 | 4 Sek. ein, 6 Sek. aus | 3, 5 oder 10 Min. |
| Doppelt ein | ein, kurz nachziehen, lang aus | 1, 2 oder 3 Min. |
| Box 4–4–4–4 | ein, halten, aus, halten | 2, 3 oder 5 Min. |

Bewusst nur ruhige Übungen, kein langes Luftanhalten und kein schnelles, kräftiges Atmen. Aufgehört wird am Ende eines ganzen Atemzugs; gezählt werden ganze Minuten. Der Bildschirm bleibt während der Übung an, wo das Handy es zulässt.

## Daten

Nur auf dem Gerät (`localStorage`). In dieses Repo gehört nie eine echte Zahl.

«Heute zurücksetzen» löscht die Häkchen und Atemminuten des Tages, «Alles zurücksetzen» nach einer Rückfrage alles samt Startpunkt.

## Dateien

| Datei | Was |
| --- | --- |
| `index.html` | die App, Schrift Jost eingebettet |
| `sw.js` | hält die App für den Start ohne Netz; bei jeder neuen Fassung `FASSUNG` hochzählen |
| `manifest.webmanifest`, `icon-*.png` | Installation auf dem Startbildschirm |
