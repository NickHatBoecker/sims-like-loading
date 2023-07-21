# Sims-like Loading Screen

![Vorschau des Loading Screens](simslikeloading.gif)

Wer erinnert sich noch an den Ladebildschirm vom ersten Sims Spiel?<br>
Witzige Sprüche, die angeblich geladen/justiert/angezogen/whatever wurden.

Mit dieser kleinen HTML-Datei kriegst du das Feeling jetzt auch in deinen Stream.

## Verwendung

1. Lade die `index.html` Datei herunter.
1. Lege in OBS (oder eine Streaming Anwendung deiner Wahl) eine neue Browser-Quelle an
1. Hake die Checkbox "Lokale Datei" an und wähle die heruntergeladene `index.html` im Feld *"Lokale Datei"* aus
1. Stelle die Breite und Höhe auf deine Stream-Größe an (bspw. 1920x1080)

## Optionen

Sucher in der `index.html` nach dem Text "OPTIONS".
Dort findest du mehrere Variablen.

### Phrases

Hier kannst du die Texte eintragen, die in deinem Stream auftauchen sollen. Die Texte werden von oben nach unten durchlaufen. Danach fängt es oben wieder an. Kopiere einfach eine der Standard-Zeilen und ersetze den Text.

### animationDurationInSeconds

Diese Zahl bestimmt wie viele Sekunden die einzelnen Texte sichtbar sind. Der Standard beträgt 8 Sekunden.

### fontSize

Die Textgröße. Belege sie mit einem px oder rem Wert.

### fontColor

Die Textfarbe. Passe sie an dein Stream-Layout an. Belege sie mit einem Farbnamen oder einem HEX-Code.

### backgroundColor

Die Hintergrundfarbe der Seite. In den meisten Fällen sollte sie auf `transparent` stehen. So kannst du die Quelle in deiner Streaming-Software über jeden beliebigen Hintergrund legen. Alternativ kannst du sie mit einem HEX-Code belegen.
