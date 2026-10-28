# Relic

A daily history puzzle. Each day shows one real object from The Met's Open Access collection as a tight close-up. Work out **where** it was made, **when**, and **what** it is, spending from a 100-point Insight budget.

Play: https://elliotesmith18.github.io/relic/

- `index.html`: the whole game (HTML, CSS and JS in one file)
- `puzzles.json`: the daily puzzles, one per start date. The game shows the newest one whose date has arrived in the player's time zone, and switches at local midnight.
- `relics/` and `relic.jpg`: artifact images (public domain, The Metropolitan Museum of Art)
- `countries-110m.json`: world map data from [world-atlas](https://github.com/topojson/world-atlas) (Natural Earth, public domain)
- `og-image.jpg`: share preview image (a tight crop, so it does not spoil the answer)
- `relic.html`: the same game in the format used for the Claude artifact version

Run locally: `python3 -m http.server` in this folder, then open http://localhost:8000. Add `?date=2026-11-01` to preview another day (local server only).
