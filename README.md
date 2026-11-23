# Familien-Dashboard

Anzeige fürs iPad: Abfahrten (Bus 217/220 ab Goerdelerstraße, S3 Holzkirchen/Mammendorf) und Vertretungsplan.

- Abfahrten kommen direkt von der MVV-Fahrplanauskunft (JSONP, kein Server).
- Den Vertretungsplan liefert ein iOS-Kurzbefehl auf dem iPad über den Link-Teil `#vp=…`. Dieser Teil wird nie an GitHub geschickt; die Seite speichert die Daten nur im Browser des iPads.
- Diese Seite enthält keine persönlichen Daten oder Zugangsdaten.

Test mit Beispieldaten: `index.html?demo=1`
