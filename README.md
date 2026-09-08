# HK + JP plan board

Free static site for the desk React HTML dashboard.

**Live:** https://clementwai-sketch.github.io/hk-jp-plan-board/

## What this is

One standalone HTML file (`index.html`). React + Tailwind load from CDN. No server, no API keys, no build step.

Not investment advice. Share counts and account IDs are not in this public copy.

## Update the board

Replace `index.html` with the latest `HK_JP_Trading_Plan_React_YYYY-MM-DD.html` (strip local paths / qty / paper acc first), then push `main`. GitHub Pages rebuilds in about a minute.

## Pages

GitHub Actions workflow `.github/workflows/pages.yml` deploys on every push to `main`.
