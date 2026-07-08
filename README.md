# The Hook Atlas

A field guide to **94 engagement mechanics** traced across games, business, and belief —
what fires in the brain, what binds the group, where each one earns loyalty, and where it
curdles into a dark pattern.

**Open [`index.html`](index.html)** — a single self-contained file with no external
scripts, fonts, or tracking, and no network calls unless you bring your own API key.

## What's inside

- **Atlas map with three lenses** — every mechanic plotted, re-plottable on three axis
  systems:
  - *Psychology* — **me ⟷ we** (does it work on a private mind or a group?) ×
    **carrot ⟷ stick** (does it pull with desire or push with fear of loss?)
  - *Tempo* — **instant ⟷ slow burn** (how fast it hooks) × **compounds ⟷ decays**
    (what happens when you stop feeding it)
  - *Builder's* — **weekend ⟷ quarter** (effort to ship) × **nudge ⟷ industrial**
    (how hard it grabs once live)

  Hazardous mechanics wear a dashed halo; hover shows a crosshair with coordinates, tap
  opens the dossier. All coordinates are editorial judgments — argue with them.
- **Dossiers** — each specimen gets *What it is*, *In the brain*, *In the group*, field
  **sightings** across four habitats (▲ worked, ▼ backfired, ◆ contested), a founder's
  **BUILD / AVOID playbook**, principles at work, and adjacent mechanics. 376 sightings
  and counting.
- **Library** — the full drawer grouped by ten families, with multi-select family and
  risk filters (BENIGN / DUAL-USE / HAZARD) and full-text search across dossiers,
  sightings and principles.

## Field tools

- **Deal me one** — a random specimen from whatever is currently filtered.
- **Splice lab** — deals two mechanics and asks what product their crossbreed would be.
  Copy a ready-made prompt for any AI chat, or generate five hybrids in place if you've
  added a key.
- **Field exam** — ten real-world sightings, four suspects each; can you name the
  mechanic? Ends with a Wordle-style shareable score (🟩🟩🟥…).
- **Your hook stack** — add specimens to a stack from any dossier and assemble your
  product's engagement architecture. Copy the whole stack as one founder brief, share it
  with a `#stack=` link, or (with a key) get it critiqued: synergies, conflicts, missing
  pieces, dark-pattern drift.
- **Specimen share cards** — every dossier exports a 1200×630 PNG card with the mechanic
  plotted on the mini-map, ready to post.
- **Today's specimen** — a date-seeded pick on the masthead, same for everyone, changes
  daily.

## Bring your own brain (optional)

Open **⚙ settings**, add an **Anthropic or OpenAI API key**, pick a model power (Haiku /
Sonnet / Opus, or GPT-5 mini / GPT-5.1 / GPT-5.1 high reasoning — plus a custom escape
hatch), and describe your company. Every dossier then grows an **⚡ Apply to my company**
button: eight divergent ways that mechanic could work for your business — bad ideas
included on purpose, with honest dark-pattern warnings per idea.

Each generation is a **run**: it keeps going if you close the dossier or switch tabs, and
pings you when it's done. All runs collect on the **My company** tab — one card per run,
with **★ favorites** pinned by default and the rest behind a per-run *show all* toggle
(so you can star new keepers from the full list later). Star from the dossier or from the
runs page; they stay in sync. The key, description, runs, and favorites live only in your
browser's localStorage; requests go directly from your browser to the provider you chose
(the site has no server).

Extras: deep-link any mechanic (`index.html#m=streaks`), share a stack
(`index.html#stack=streaks,loss-aversion,guilds`), **Copy founder brief** turns a dossier
into a plain-text prompt for your notes or an AI chat, press `/` to search.

## Lineage

The collection draws on the classic **SCVNGR Game Dynamics Playdeck** (every playdeck
concept is in the atlas — search "SCVNGR" to see the set), the behavioral-design
literature (Skinner, Kahneman, Deci, Csikszentmihalyi, McGonigal, Schell), and modern
game-design vocabulary translated for founders — core loops, rubber banding, battle
passes, skill ceilings, sinks & faucets.

## Design notes

- System sans-serif stack for body text (mono accents via `ui-monospace`) — no serif,
  no webfont downloads.
- Mobile-first: the dossier opens as a bottom sheet on small screens, map dots get
  enlarged touch targets, filters scroll horizontally, the stack tray respects safe
  areas.
- The ten family colors are tuned for colorblind safety (validated CVD separation and
  ≥3:1 contrast on the felt surface).
- The site practices what it catalogs, on purpose: a daily specimen (appointment
  mechanic), a shareable exam score (status display), a stack you assemble (ownership &
  the IKEA effect). Consider that part of the field work.
