# OptiFlow Logistics

Premium B2B logistics platform — single-page web app with interactive supply chain simulator, waybill tracker, and bilingual UI (EN/VI).

**Creator:** Truong The Bach

## Live Demo (GitHub Pages)

After enabling Pages, your site will be available at:

```
https://<your-username>.github.io/optiflow-logistics/
```

## Features

- Interactive Supply Chain Simulator (map route builder, optimize, undo, presets)
- Waybill lookup (`DV-YYYY-NNNNN`) with hub network map
- Chart.js analytics, Monte Carlo simulation
- Bilingual EN / VI toggle
- Creator section & enterprise UI

## Project Structure

```
optiflow-logistics/
├── index.html      # Full app (HTML + CSS + JS inline)
├── README.md
├── .nojekyll       # Required for GitHub Pages static hosting
└── .gitignore
```

## Upload to GitHub

### Option A — Git CLI (recommended)

```bash
cd optiflow-logistics
git init
git add .
git commit -m "Initial commit: OptiFlow Logistics"
git branch -M main
git remote add origin https://github.com/<your-username>/optiflow-logistics.git
git push -u origin main
```

### Option B — GitHub website

1. Create a new repository named `optiflow-logistics` on GitHub (Public).
2. Upload all files from the `optiflow-logistics` folder (or use the included `.zip`).
3. Do **not** skip `index.html`, `.nojekyll`, or `README.md`.

## Enable GitHub Pages

1. Open repo → **Settings** → **Pages**
2. **Source:** Deploy from branch
3. **Branch:** `main` → folder `/ (root)` → **Save**
4. Wait 1–3 minutes, then open the Pages URL.

## Local Preview

Open `index.html` in a browser, or run:

```bash
npx serve .
```

## Demo Data

| Waybill        | Route                          |
|----------------|--------------------------------|
| DV-2026-88421  | Shanghai → Singapore → HCMC    |
| DV-2026-77102  | Rotterdam → Dubai → HCMC       |
| DV-2026-55988  | HCMC → Singapore → LA          |
| DV-2026-33219  | Hanoi → Singapore → Shanghai   |

## Tech Stack

- Tailwind CSS (CDN)
- Chart.js, Leaflet.js
- Vanilla JavaScript (no build step)

## License

Demo project for portfolio / educational use.
