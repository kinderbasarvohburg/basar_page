# Kinderbasar Vohburg a.d. Donau

Eine kleine, rein statische Website. Sie benötigt weder Backend noch Datenbank, Build-Schritt, JavaScript oder externe Bibliotheken und kann daher auf einem statischen Webhost betrieben werden.

## Seiten

- `index.html`: Startseite mit nächstem Basartermin
- `besucher.html`: Öffnungszeiten, Ort und Hinweise
- `verkaeufer.html`: Teilnahme und Ablauf für Verkäufer
- `helfer.html`: Informationen für Helferinnen und Helfer
- `faq.html`: Häufige Fragen
- `kontakt.html`: Kontakt zum Organisationsteam
- `impressum.html` und `datenschutz.html`: rechtliche Informationsseiten

## Inhalte anpassen

Ersetze vor der Veröffentlichung alle Angaben in eckigen Klammern. Impressum und Datenschutzhinweise sind ausdrücklich nur Platzhalter und müssen an Betreiber, Hosting und tatsächliche Nutzung angepasst werden.

## Lokal ansehen

`index.html` direkt im Browser öffnen. Zum Testen über einen lokalen Webserver kann zum Beispiel Python verwendet werden:

```powershell
python -m http.server 8000
```

Danach `http://localhost:8000` im Browser aufrufen.

## Hosting

Die Dateien können unverändert auf einen statischen Webhost geladen werden, zum Beispiel GitHub Pages oder einen Anbieter mit kostenlosem Static-Hosting-Tarif. Es gibt keine Serveranwendung und keine laufenden Backend-Kosten. Eine eigene Domain ist optional und wird üblicherweise separat bezahlt. Vor der Wahl des Hosters Datenschutz, Verfügbarkeit und Bedingungen des jeweiligen Tarifs prüfen.
