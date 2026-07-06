# 🚴 GPX Temperature Forecast

Permet de visualiser les températures prévues le long d'un itinéraire (vélo par exemple) à partir d'un fichier GPX.

Les prévisions sont données pour les 16 jours à venir.

Voir la version en ligne : https://sebington.github.io/gpx-forecast/

## Features

- **Open any `.gpx` file** — drag & drop or click the button. All parsing happens in your browser.
- **16-day hourly forecast** — free [Open-Meteo](https://open-meteo.com) API, cached locally
- **Live colouring** — route segments coloured by temperature, animatable hour by hour
- **Day and night** — sky panel shows the sun position for any forecast hour
- **Elevation profile** — interactive chart, hover to see elevation at any point
- **Temperature labels** — 10 evenly spaced labels on the route, colour-coded and live
- **Keyboard shortcuts** — `Space` to play/pause, `←` / `→` to step

## Tech

Leaflet · OpenStreetMap · Open-Meteo · vanilla JS · zero build tools
