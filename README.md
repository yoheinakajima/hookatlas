# The Hook Atlas

A field guide to **49 engagement mechanics** traced across games, business, and belief —
what fires in the brain, what binds the group, where each one earns loyalty, and where it
curdles into a dark pattern.

**Open [`index.html`](index.html)** — a single self-contained file with no external
scripts, fonts, tracking or network calls.

## What's inside

- **Atlas map** — every mechanic plotted on two editorial axes: *me ⟷ we* (does it work
  on a private mind or a group?) and *carrot ⟷ stick* (does it pull with desire or push
  with fear of loss?). Hazardous mechanics wear a dashed halo; hover shows a crosshair
  with coordinates, tap opens the dossier.
- **Dossiers** — each specimen gets *What it is*, *In the brain*, *In the group*, field
  **sightings** across four habitats (▲ worked, ▼ backfired, ◆ contested), a founder's
  **BUILD / AVOID playbook**, principles at work, and adjacent mechanics.
- **Library** — the full drawer grouped by nine families, with multi-select family and
  risk filters (BENIGN / DUAL-USE / HAZARD) and full-text search across dossiers,
  sightings and principles.
- **Deal me one** — a random specimen from whatever is currently filtered.

Extras: deep-link any mechanic (`index.html#m=streaks`), **Copy founder brief** turns a
dossier into a plain-text prompt for your notes or an AI chat, press `/` to search.

## Design notes

- System sans-serif stack for body text (mono accents via `ui-monospace`) — no serif,
  no webfont downloads.
- Mobile-first: the dossier opens as a bottom sheet on small screens, map dots get
  enlarged touch targets, filters scroll horizontally.
- The nine family colors are tuned for colorblind safety (validated CVD separation and
  ≥3:1 contrast on the felt surface) while keeping each family's original hue.

## Files

| File | Description |
|---|---|
| `index.html` | The Hook Atlas |
| `mechanic_atlas_founders.html` | Earlier companion prototype (120-term mechanic atlas), kept for reference |
