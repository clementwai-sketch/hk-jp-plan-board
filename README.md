# HK · JP · US desk board

One public site. Chips **HK · JP · US · All** (hash `#HK` `#JP` `#US` `#ALL`).

**Live:** https://clementwai-sketch.github.io/hk-jp-plan-board/

Latest plug: **Thu 10 Sep 2026** — HK+JP morning (US overnight). JSX is frozen; only `window.__DATA__` / `data.json` changes.

- Home: `index.html`
- US deep-link: [us.html](https://clementwai-sketch.github.io/hk-jp-plan-board/us.html) → `#US`
- Payload: `data.json`
- Prior boards: `archive/`

## What this is

Standalone HTML. React + Tailwind from CDN. No server, no API keys, no build step.

Not investment advice. Holdings / Portfolio Watch, share counts, and account IDs are not in this public copy. HK, JP, and US stay in separate lists.

## Plug next session (desk)

Edit `data.json` (or `vcp-scanner/Dashboard/desk_board_data.json`), then:

```bash
python3 scripts/plug_desk_board.py \
  --data Dashboard/desk_board_data.json \
  --out Dashboard/Desk_Board_React_YYYY-MM-DD.html
```

Copy the plugged HTML over `index.html` and push `main`. Do not put Portfolio / qty / cost / CBBC / `IN BOOK` / `/Users/` paths in the JSON.

## Pages

GitHub Actions workflow `.github/workflows/pages.yml` deploys on every push to `main`.
