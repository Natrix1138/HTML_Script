Grafische Darstellung:
┌───────────────────────────────────────────┐
│                   WEBBROWSER               │
│                                       │
│   ┌───────────────────────────┐       │
│   │   DIGITALE UHR (DIV)      │       │
│   │                           │       │
│   │   14:35:42                │       │
│   │   (aktuelle Uhrzeit)      │       │
│   │                           │       │
│   └───────────────────────────┘       │
│                                       │
│   - Schrift: **Fett**                │
│   - Schriftgröße: **40px**           │
│   - Aktualisiert **jede Sekunde**     │
│                                       │
└───────────────────────────────────────────┘

Funktionsweise:

JavaScript (<script>):

Wird ausgeführt, sobald die Seite geladen ist (window.onload).
Holt die aktuelle Uhrzeit (new Date()) und zeigt sie im Format Stunden:Minuten:Sekunden an.
Aktualisiert die Uhrzeit alle 1000 Millisekunden (1 Sekunde) mit setInterval.


HTML (<div id="clock">):

Ein leeres div-Element mit der ID clock, das die Uhrzeit anzeigt.
Stil:
Fettgedruckt (font-weight: bold).
Schriftgröße 40px (font-size: 40px).






Beispiel-Ausgabe im Browser:
14:35:42





Graphical representation:
┌───────────────────────────────────────────┐
│                   WEB BROWSER               │
│                                       │
│   ┌───────────────────────────┐       │
│   │   DIGITAL CLOCK (DIV)      │       │
│   │                           │       │
│   │   14:35:42                │       │
│   │   (current time)      │       │
│   │                           │       │
│   └───────────────────────────┘       │
│                                       │
│   - Font: **Bold**                │
│   - Font size: **40px**           │
│   - Updated **every second**     │
│                                       │
└───────────────────────────────────────────┘

How it works:

JavaScript (<script>):

Executes as soon as the page is loaded (window.onload).
Retrieves the current time (new Date()) and displays it in hours:minutes:seconds format.
Updates the time every 1000 milliseconds (1 second) with setInterval.


HTML (<div id="clock">):

An empty div element with the ID clock that displays the time.
Style:
Bold (font-weight: bold).
Font size 40px (font-size: 40px).






Example output in the browser:
14:35:42

Translated with DeepL.com (free version)
