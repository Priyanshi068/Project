# 🪺 TripNest

A budget-first trip planner that runs entirely in the browser. No backend, no build step, no dependencies.

**Live demo:** `https://<your-username>.github.io/tripnest/`

## What it does

- **Budget-First Search**: enter budget, days, starting city and mood, and get up to 5 destinations that fit.
- **Compare**: transport (train, bus, flight, cab) and hotel tiers side by side, with a "Best Value" badge.
- **Hidden Cost Calculator**: shows the real trip total, including local cabs, entry fees, tips and porters.
- **Smart Itinerary**: groups nearby places, builds a day-wise plan by pace, and lets you reorder stops by drag-and-drop or ▲ ▼ buttons.
- Dark mode, responsive layout, and progress saved in `localStorage`.

## Tech

Plain HTML, CSS and JavaScript: `index.html`, `style.css`, `script.js`. Prices are mock estimates.

## Run locally

Open `index.html` in any browser.

## Deploy (GitHub Pages)

1. Push this repo to GitHub.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, branch `main`, folder `/ (root)`, then Save.
4. After about a minute the site is live at the link above.

## Roadmap

- Real pricing APIs
- Maps view
- Shareable trip links

## License

MIT
