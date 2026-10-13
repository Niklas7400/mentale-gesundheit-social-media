# Mentale Gesundheit & Social Media

Einseitige Informationswebsite für Jugendliche und junge Erwachsene darüber, wie Social Media die psychische Gesundheit beeinflussen kann. Entstanden als **Teamprojekt** im Sommersemester 2025 im Rahmen einer universitären Übung.

> **Hinweis:** Die Website ist ein Studienprojekt und ersetzt keine medizinische oder psychologische Beratung.

**Demo:** <https://niklas7400.github.io/mentale-gesundheit-social-media/>

## Inhalt der Website

Fünf Abschnitte, die über ein Menü per Anker (`#start`, `#wissen`, `#tipps`, `#ressourcen`, `#ueberuns`) umgeschaltet werden:

- Willkommen
- Wissenswertes
- Tipps für einen gesunden Umgang
- Hilfreiche Ressourcen (Links zu Beratungsangeboten)
- Über uns

Dazu eine Seitenleiste mit Infoboxen, ein umschaltbarer Dark Mode und ein responsives Layout (mobil und Desktop).

## Tech-Stack

Reines HTML, CSS und JavaScript, ohne Framework, Build-Schritt oder Abhängigkeiten. Schriftart: [Inter](https://fonts.google.com/specimen/Inter) über Google Fonts.

## Lokal starten

```bash
cd docs
python3 -m http.server 8000
```

Dann <http://localhost:8000> im Browser öffnen. (`docs/index.html` lässt sich auch direkt im Browser öffnen.)

## Projektstruktur

```
docs/
├── index.html          # Seite mit allen Abschnitten
└── include/
    ├── css/style.css   # Styling inkl. Dark Mode und Layout
    └── js/script.js    # Dark-Mode-Umschalter
```

Der Ordner heißt `docs`, damit die Seite direkt über GitHub Pages ausgeliefert werden kann.

## Bildquelle

Das Titelbild wird von [Unsplash](https://unsplash.com/photos/1503676260728-1c00da094a0b) eingebunden (Unsplash-Lizenz).
