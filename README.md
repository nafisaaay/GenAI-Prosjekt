## Aktivitet på hele PC-en

For at kaninene skal merke aktivitet utenfor sitt eget vindu (i andre faner og programmer), må du bruke Chrome eller Edge og kjøre siden via en lokal server:

1. Åpne en terminal i mappa der `fokuskaniner.html` ligger, og kjør:
   python -m http.server 8000
2. Gå til http://localhost:8000/fokuskaniner.html i nettleseren.
3. Trykk «Følg hele PC-en» og godta tillatelsen.

Tillatelsen virker bare når siden kjøres fra en trygg adresse som `localhost`. Åpner du fila direkte (`file:///...`), virker den ikke. Grensen for inaktivitet er minst 1 minutt.
