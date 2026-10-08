# Quantenkryptografie (Lernlabor)

Veröffentlicht mit GitHub Pages unter https://discoverylabs-uibk.github.io/quantumcrypto/

## Texte ändern

Alle Texte stehen als einfache Markdown-Dateien im Ordner **`website/`**.

1. Auf github.com die Datei öffnen, zum Beispiel `website/index.md`.
2. Oben rechts auf das **Stift-Symbol** (Edit) klicken.
3. Text ändern, unten **Commit changes** wählen.

Nach ein bis zwei Minuten ist die Änderung auf der Seite sichtbar. (Den Fortschritt sieht man im Reiter *Actions*.)
Auf der veröffentlichten Seite führt der Stift oben rechts neben dem Seitentitel direkt zur richtigen Datei.

## Aussehen ändern

Farben stehen in `website/stylesheets/extra.css`, Seitenname und Einstellungen in `mkdocs.yml`.
Diese Dateien muss man für Textänderungen nicht anfassen.

## Inhalt

| Ort | Inhalt |
|---|---|
| `website/index.md` | Übersichtsseite des Lernlabors (Text bearbeiten) |
| `website/rsa-rechner/index.html` | RSA-Rechner: eigenständige HTML-Seite mit eigenem Aussehen, wird unverändert veröffentlicht |

## Ein neues Werkzeug hinzufügen

Ordner mit `index.html` unter `website/` anlegen und in `website/index.md` einen Eintrag unter `<div class="grid cards">` ergänzen.

## Wichtige Einstellung

Unter **Settings → Pages** muss die Quelle auf **GitHub Actions** stehen (nicht „Deploy from a branch").

## Lokal ansehen (optional)

```
pip install -r requirements.txt
mkdocs serve
```

Nur Inhalte ablegen, die öffentlich sein dürfen (keine Lösungen für Lehrkräfte, keine urheberrechtlich geschützten Dokumente).
