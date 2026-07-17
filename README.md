# TLC Base

The TLC Base platform — a single front door that opens into six hubs.
Each hub is an independent, on-brand site that "bolts on" via its own folder.

## Structure

| Path | Hub | Status |
|------|-----|--------|
| `/index.html` | **TLC Base** — threshold / launcher | Live |
| `/team/` | 01 · Staff base | Placeholder |
| `/knowledge/` | 02 · Knowledge hub | Placeholder |
| `/admin/` | 03 · Admin hub | Placeholder |
| `/quality/` | 04 · Quality hub | Placeholder |
| `/safeguarding/` | 05 · 360 Safeguarding | Placeholder |
| `/impact/` | 06 · Impact | Placeholder |

## How to add a finished hub

1. Build the hub as its own site (any number of files).
2. Put its files inside the matching folder — the hub's home page **must** be
   named `index.html` (e.g. `team/index.html`).
3. Commit. The button on the Base front door already points to the folder,
   so it "just works" — no change to the Base page needed.

Pieces can be built anywhere (any session or login) and assembled here.
GitHub is the single source of truth.

## Hosting

Static site — deploys as-is on GitHub Pages (Settings → Pages → Branch: main → /root).
`.nojekyll` is included so every folder is served without Jekyll processing.

## Brand

Navy `#29445F` · Sage `#83C097` · Signal Blue `#3085C6` · Cream `#F5F2EC`.
Type: Inter + Cormorant Garamond italic (the sans + italic-serif mix).
