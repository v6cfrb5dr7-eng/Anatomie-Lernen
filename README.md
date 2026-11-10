# Muskel-Lernseite – Anatomie I

Statische Webseite (nur `index.html`, kein Build nötig) mit Muskel-Übersicht, Suchfunktionen und Quiz.

## Veröffentlichen mit GitHub Pages

1. Auf github.com ein Konto anlegen bzw. anmelden und oben rechts **+ → New repository** wählen (Name z. B. `muskel-lernseite`).
2. Im neuen Repository **uploading an existing file** wählen und den **Inhalt** des entpackten Ordners hochladen: `index.html`, `.nojekyll`, `README.md` und den Ordner `images`.
   Der Browser-Upload nimmt höchstens 100 Dateien pro Vorgang an. Mit Bildern ist das knapp, am besten `index.html`, `.nojekyll` und `README.md` zuerst hochladen und `images` danach in einem zweiten Upload. Alternativ GitHub Desktop oder `git push` nutzen.
3. **Settings → Pages**: Unter *Build and deployment* die Quelle **Deploy from a branch** wählen, Branch **main** und Ordner **/ (root)**, dann **Save**.
4. Nach ein bis zwei Minuten ist die Seite erreichbar unter `https://DEIN-NAME.github.io/muskel-lernseite/`.

## Wichtig: Bilder und Urheberrecht

Die Abbildungen im Ordner `images` stammen aus den Skripten (Prometheus-Atlas, Thieme, und den Folien der Dozentin). GitHub Pages ist bei kostenlosen Konten öffentlich. Lade den Ordner `images` deshalb nur hoch, wenn die Seite nicht öffentlich auffindbar sein soll oder du die Rechte geklärt hast. Ohne den Ordner funktioniert die Seite weiter, statt der Bilder steht dann der Verweis auf Teil und Folie im Skript.

## Hinweise

- Der Quiz-Fortschritt wird im Browser (localStorage) gespeichert und gilt pro Gerät und Browser.
- Änderungen: Datei im Repository ersetzen, nach kurzer Zeit ist die Seite aktualisiert.
