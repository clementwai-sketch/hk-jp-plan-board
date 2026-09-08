# HK + JP plan board

Free static site for the desk React HTML dashboard.

**Live:** https://clementwai-sketch.github.io/hk-jp-plan-board/

- HK+JP homepage: `index.html` — JP midday 8 Sep 2026 (lunch). Morning: `archive/hk-jp-2026-09-08-morning.html`
- US: [us.html](https://clementwai-sketch.github.io/hk-jp-plan-board/us.html) — Tue 8 Sep 2026 PRE_MARKET. Archive: `archive/us-2026-09-08.html`

## What this is

Standalone HTML. React + Tailwind from CDN. No server, no API keys, no build step.

Not investment advice. Holdings / Portfolio Watch, share counts, and account IDs are not in this public copy.

## Update the board

Replace `index.html` with the latest HK+JP React board after stripping Portfolio / MTM / qty / CBBC / local paths. Do **not** overwrite `index.html` with a US board — US goes to `us.html` with the same strip.

Then push `main`. GitHub Pages rebuilds in about a minute.

## Pages

GitHub Actions workflow `.github/workflows/pages.yml` deploys on every push to `main`.
