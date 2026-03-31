# Trenz Landing Page

This project is a static e-commerce landing page for **Trenz** built with plain HTML, CSS, and JavaScript.

## Project Analysis

- **Type:** Static frontend website (no backend runtime required)
- **Main entry file:** `Landing_page.html`
- **Styling:** `Landing_page.css`
- **Behavior:** `script.js` (auto image slideshow)
- **Assets:** `img/` folder

## Current Features

- Brand header and category navigation
- Product and brand showcase sections
- Auto-rotating slideshow using vanilla JavaScript
- Informational footer blocks

## Local Run

You can open `Landing_page.html` directly in a browser, or serve it with any static server.

Example with Python:

```bash
python3 -m http.server 5500
```

Then open:

```text
http://localhost:5500/Landing_page.html
```

## Vercel Deployment

This repository includes:

- `vercel.json` to map `/` to `Landing_page.html`
- `deploy-vercel.sh` helper script for production deployment via Vercel CLI

### One-time setup

1. Install Node.js (if not installed).
2. Login to Vercel:

```bash
npx vercel login
```

### Deploy

Run:

```bash
bash deploy-vercel.sh
```

This executes:

```bash
npx vercel --prod
```

## Notes

- The existing root `README` file is kept as-is for compatibility.
- If you want cleaner URLs and default index behavior, rename `Landing_page.html` to `index.html` in a future update.