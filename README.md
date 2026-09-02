# JU English Grade Calculator | حاسبة علامة اللغة الإنجليزية

A bilingual (Arabic/English) single-page calculator for estimating the final
percentage grade and letter grade for the University of Jordan's English
Level 1, 2, and 3 courses, based on the Equivalent English Exam regulation
and placement exam results.

## How it works

The final percentage grade is calculated from:

- **Initial placement exam** — 20% of the grade
- **Level 1 / Level 2 / Level 3 course grades** — 15% each (up to 45% total)
- **Final placement exam** — 35% of the grade
- **Main-level progression bonus** — +5 points per main level advanced
  between the initial and final exam (A1→A2→B1→B2→C1), with a special
  exception of +8 points for advancing specifically from B2 to C1

The total is then converted to a letter grade (F through A) using the
university's official conversion table.

> This is an unofficial estimation tool. Please confirm your official grade
> with the Language Center or the Faculty of Foreign Languages.

## Usage

This is a single self-contained HTML file (`index.html`) — no build step,
no dependencies to install. Just open it in a browser, or host it anywhere
that serves static files.

## Hosting

- **GitHub Pages**: enable Pages on this repo (Settings → Pages → deploy
  from `main` branch) and it will be live at
  `https://<your-username>.github.io/<repo-name>/`
- **Netlify / Vercel / Cloudflare Pages**: connect this repo and deploy
  with zero configuration.

## Credit

Made by Teya Ibrahim Abumushref.
