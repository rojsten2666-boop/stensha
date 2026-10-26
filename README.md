# Currency Pulse Pro Analysis Tool

A static web app for analyzing live Deriv synthetic market digit data in the browser.

## Features
- WebSocket connection to Deriv public market data
- Dynamic market selection
- Historical tick loading and live tick feed
- Digit frequency analysis
- Match / Differ / Over / Under / Odd / Even evaluation modes
- Scan counter, signal status, and recent history
- CSV export and optional browser notifications
- Responsive layout for desktop and mobile

## Run locally
Open `index.html` directly in a browser, or serve it locally:

```bash
cd project-folder
python3 -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## GitHub Pages
1. Push this repo to GitHub.
2. Open the repo in GitHub.
3. Go to Settings → Pages.
4. Set Build and deployment:
   - Source: Deploy from a branch
   - Branch: `main`
   - Folder: `/root`
5. Save.
6. Wait for GitHub to publish the site.

Your page will be available at:

```text
https://rojsten2666-boop.github.io/stensha/
```

## Notes
- This app is analysis-only and does not log in to Deriv or trade.
- Browser sound/notification requests are optional and may require permission.
- Public market availability depends on the Deriv API and network conditions.
