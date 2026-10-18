# ČUDA ZEMLJE

Wertungsblock für den Spieleabend: bis zu 7 Spieler, Städte mit Tag- und Nachtseite, verdeckte Summen mit Kartenverkündung und eine Statistik über alle Partien.

## Online stellen mit GitHub Pages

1. Auf github.com anmelden und oben rechts **+ → New repository** wählen.
2. Name: `cuda-zemlje`, Sichtbarkeit **Public**, dann **Create repository**.
3. Auf der leeren Seite auf **uploading an existing file** klicken.
4. Den **Inhalt** dieses Ordners hineinziehen: `index.html`, `manifest.webmanifest`, `sw.js`, `README.md` und den Ordner `icons`. Dann **Commit changes**.
5. Im Repository auf **Settings → Pages** gehen. Unter *Branch* `main` und `/ (root)` wählen und **Save** drücken.
6. Nach ein bis zwei Minuten läuft die App unter `https://DEIN-NAME.github.io/cuda-zemlje/`.

## Auf dem Handy installieren

- **Android (Chrome):** Link öffnen, dann im Menü ⋮ auf **App installieren** oder **Zum Startbildschirm hinzufügen** tippen.
- **iPhone (Safari):** Link öffnen, auf das Teilen-Symbol tippen, dann **Zum Home-Bildschirm**.

Danach startet die App mit eigenem Icon, ohne Browserleiste und auch ohne Internet.

## Updates

Eine neue `index.html` hochladen und in `sw.js` die Versionsnummer erhöhen, also `cz-v1` auf `cz-v2`. Beim nächsten Öffnen mit Internet holen sich alle Handys die neue Version.

## Daten

Spieler und Statistik werden auf dem jeweiligen Gerät gespeichert. Zum Umziehen auf ein anderes Gerät dient in der Statistik ganz unten **Daten kopieren** bzw. **Daten laden**.

## Optional: echte APK

Auf pwabuilder.com die Adresse der App eingeben und **Package for stores → Android** wählen. Die erzeugte APK kann unter *Releases* im Repository abgelegt werden. Für die Installation muss auf Android „Unbekannte Quellen“ erlaubt werden.
