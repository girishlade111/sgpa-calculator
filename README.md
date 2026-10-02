# SGPA Calculator

A simple, free, no-login SGPA (Semester Grade Point Average) calculator for students. Open the page, enter your subjects, grades, and credits, and get your semester GPA instantly — all computed client-side in the browser.

## Features

- Add/remove subjects with name, grade, and credit values
- Instant SGPA calculation as you type
- Clean, single-page UI — works offline after the first load
- 100% client-side: no server, no tracking, no data leaves your device

## Tech Stack

- HTML + vanilla CSS + vanilla JavaScript (single file: `sgpa-calculator.html`)
- No dependencies, no build step

## Quick Start

Just open `sgpa-calculator.html` in any browser — that's it.

To serve locally:

```bash
npx serve .
# or
python3 -m http.server 8000
```

Then open http://localhost:8000/sgpa-calculator.html.

## Project Structure

```text
.
├── sgpa-calculator.html   # The entire app — markup, styles, logic
├── LICENSE                # License
└── README.md              # This file
```

## Deploy Notes

Static site with zero build step. Hosted via GitHub Pages. Also deployable anywhere (Netlify, Cloudflare Pages, Vercel) — just serve the repo root.

## About the Author

**Built by Girish Lade** — [ladestack.in](https://ladestack.in)
