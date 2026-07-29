# MLB Power Rankings — Card Prototype

A self-contained HTML/CSS/JS prototype of an MLB Power Rankings module for
The Athletic app's home feed. No build step — plain HTML, viewable directly
in a browser.

## What's in here

- **`power-ranking-card-prototype.html`** — the whole prototype (swipeable
  card carousel, a compact list view, and an interactive "make my own power
  rankings" drag-to-reorder tool with a shareable export).
- **`Assets/Fonts/`** — the Athletic Sans/Serif/Slab type superfamily used
  throughout.
- **`Assets/team-logos/`** — local copies of the 30 MLB team logos (used by
  the shareable-image export, which needs same-origin images to render to a
  canvas).
- **`Assets/iOS/`** — The Athletic's wordmark asset.

## Run it locally

No build step required.

```bash
python3 -m http.server 8000
```

Then open **http://localhost:8000/power-ranking-card-prototype.html**.

## Note

This is a design prototype, not production code. Team names, records, and
rankings shown are illustrative sample data.
