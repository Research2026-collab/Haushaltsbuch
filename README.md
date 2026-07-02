# Mein Haushaltsbuch

Eine installierbare Web-App (PWA) in einfacher Sprache. Menschen tragen ihre Einnahmen und Ausgaben ein und sehen auf einen Blick, was übrig bleibt. Alle Daten bleiben auf dem jeweiligen Gerät, gespeichert im `localStorage` des Browsers. Es gibt keinen Server und keine Anmeldung.

## Dateien

| Datei | Zweck |
| --- | --- |
| `index.html` | Die App selbst: Formular, Übersicht, Diagramme, Export |
| `manifest.json` | Beschreibt die App fürs Betriebssystem, macht sie installierbar |
| `sw.js` | Service Worker, sorgt für Offline-Nutzung |
| `icons/` | App-Icons in den benötigten Größen |

## Veröffentlichung auf GitHub Pages

Lege in deinem Repository einen Ordner an, zum Beispiel `haushaltsbuch`, und lade alle Dateien aus diesem Paket dort hinein, inklusive des Ordners `icons`. Öffne danach in den Repository-Einstellungen den Punkt „Pages“. Wähle als Quelle den Branch, in dem die Dateien liegen, und als Ordner entweder `/root` oder `/haushaltsbuch`, je nachdem, wo die Datei `index.html` liegt. GitHub zeigt danach eine Adresse an, unter der die Seite erreichbar ist, etwa `https://dein-name.github.io/dein-repo/haushaltsbuch/`.

Wichtig ist, dass `index.html`, `manifest.json`, `sw.js` und der Ordner `icons` im selben Verzeichnis liegen, weil die App-Datei mit relativen Pfaden auf sie verweist.

## Installation auf dem Handy, ohne App Store

Auf einem Android-Gerät öffnet man die Adresse im Chrome-Browser. Nach kurzer Zeit erscheint innerhalb der App ein Hinweisfeld mit der Schaltfläche „App installieren“. Alternativ lässt sich das Menü rechts oben im Browser öffnen und dort „App installieren“ oder „Zum Startbildschirm hinzufügen“ auswählen.

Auf einem iPhone oder iPad öffnet man die Adresse in Safari. Dort zeigt die App automatisch einen Hinweis, dass man auf das Teilen-Symbol tippen und dann „Zum Home-Bildschirm“ wählen soll. Der App Store wird in beiden Fällen nicht benötigt.

## Funktionen im Überblick

Einnahmen und Ausgaben lassen sich einzeln mit Betrag, Bereich, Datum und einer kurzen Notiz eintragen. Die Startseite zeigt für den gewählten Monat die Summe der Einnahmen, der Ausgaben und den Betrag, der übrig bleibt. Ein Balkendiagramm vergleicht die letzten sechs Monate, ein Kreisdiagramm zeigt, wofür im aktuellen Monat Geld ausgegeben wurde. Über die Monatspfeile lässt sich zwischen den Monaten wechseln, auch für vergangene Einträge.

Für die eigene Ablage lassen sich die Einträge eines Monats als CSV-Tabelle herunterladen, die sich in Excel oder LibreOffice öffnen lässt, oder als PDF über die Druckfunktion des Browsers sichern.

## Änderungen und Weiterentwicklung

Farben, Schrift und Aufbau orientieren sich am bestehenden MoTiF-Design mit Navy und Petrol als Leitfarben. Neue Kategorien lassen sich im Abschnitt `CATEGORIES` in `index.html` ergänzen, neue Symbole im Abschnitt `ICON` direkt darüber. Beide Abschnitte stehen am Anfang des `<script>`-Bereichs.
