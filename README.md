# HK + JP plan board

Free static site for the desk React HTML dashboard.

**Live:** https://clementwai-sketch.github.io/hk-jp-plan-board/

## What this is

One standalone HTML file (`index.html`). React + Tailwind load from CDN. No server, no API keys, no build step.

Not investment advice. Holdings / Portfolio Watch, share counts, and account IDs are not in this public copy.

## Update the board

Replace `index.html` with the latest `HK_JP_Trading_Plan_React_YYYY-MM-DD.html` after stripping:

- Portfolio tab / `portfolio` rows / MTM / open P&L / qty / CBBC Dist-to-Kill
- “IN BOOK” / “held in book”
- local paths, share counts, paper NAV, account ids, CBBC codes

Then push `main`. GitHub Pages rebuilds in about a minute. Do not overwrite `index.html` with a US board.

## Pages

GitHub Actions workflow `.github/workflows/pages.yml` deploys on every push to `main`.
