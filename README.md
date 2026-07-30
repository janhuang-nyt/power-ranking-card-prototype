# Power Rankings — Card Prototypes

Self-contained HTML/CSS/JS prototypes of Power Rankings modules for The
Athletic app's home feed — one team-level, one player-level. No build step —
plain HTML, viewable directly in a browser.

## What's in here

- **`teams-power-ranking-card-prototype.html`** — team-level rankings
  (swipeable card carousel, a compact list view, and an interactive "make my
  own power rankings" drag-to-reorder tool with a shareable export). Sample
  data: MLB.
- **`players-power-ranking-prototype.html`** — player-level rankings
  (swipeable card carousel with a metallic tier-shield badge, a compact list
  view, and a shareable "by tier" / "full list" graphic export). Sample
  data: NFL QB Tiers.
- **`Assets/Fonts/`** — the Athletic Sans/Serif/Slab type superfamily used
  throughout.
- **`Assets/team-logos/`** — local copies of the 30 MLB team logos (used by
  the teams prototype's shareable-image export, which needs same-origin
  images to render to a canvas).
- **`Assets/iOS/`** — The Athletic's wordmark asset.
- **`iOS/assets/icons/leagues/`** — league pill icons (MLB, NFL).

## Run it locally

No build step required.

```bash
python3 -m http.server 8000
```

Then open **http://localhost:8000/teams-power-ranking-card-prototype.html**
or **http://localhost:8000/players-power-ranking-prototype.html**.

## Note

This is a design prototype, not production code. Team names, records, and
rankings shown are illustrative sample data.
