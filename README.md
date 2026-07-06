# 🚴 GPX Temperature Forecast

Colour any cycling route by hourly temperature forecast — animate across 16 days, see sun/moon arcs, and explore elevation profiles.

Check the online version at: https://sebington.github.io/gpx-forecast/

## Quick Start

```bash
uv run server.py
# → http://localhost:8000
```

No build step, no API keys, no dependencies to install.

## Features

- **Open any `.gpx` file** — drag & drop or click the button. All parsing happens in your browser.
- **16-day hourly forecast** — free [Open-Meteo](https://open-meteo.com) API, cached locally
- **Live colouring** — route segments coloured by temperature, animatable hour by hour
- **Sun & moon arc** — sky panel shows the sun position for any forecast hour
- **Elevation profile** — interactive chart, hover to see elevation at any point
- **Temperature labels** — 10 evenly spaced labels on the route, colour-coded and live
- **Keyboard shortcuts** — `Space` to play/pause, `←` / `→` to step

## Project Layout

```
index.html          ← everything (single-file app)
prepare_data.py     ← pre-compute route_data.json from GPX
route_data.json     ← default route (Melun → Nîmes, 829 km)
tourmagne.gpx       ← source GPX
server.py           ← dev server
AGENT.md            ← detailed technical documentation
```

## Tech

Leaflet · OpenStreetMap · Open-Meteo · vanilla JS · zero build tools
