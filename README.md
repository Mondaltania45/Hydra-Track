# HydraTrack — Personal Hydration Dashboard

HydraTrack is a responsive, browser-based hydration habit tracker. It supports daily fluid goals, quick and custom intake logging, daily timelines, 7/14/30-day intake charts, local browser storage, CSV export, and an educational heat/activity awareness panel.

## Deploy on GitHub Pages

1. Create a new GitHub repository (for example, `hydratrack`).
2. Upload `index.html` and `README.md` to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and `/ (root)`, then save.
6. Wait for GitHub Pages to publish the site and open the URL shown in Settings → Pages.

No server, Python runtime, database, account, or API key is needed. Chart.js is loaded from a public CDN, so an internet connection is needed for the chart library; intake logging and the rest of the interface run in the browser.

## Privacy and limitations

- Intake history and the daily target are stored in this browser's `localStorage`; they are not uploaded to a server by this app.
- Export CSV periodically if you want a backup. Clearing browser site data or changing devices may remove or hide local records.
- The heat/activity panel is an educational awareness prompt. It does not measure hydration status, diagnose dehydration, or prescribe a safe fluid amount.
- Hydration needs vary by individual, workload, environment, and health conditions. Follow clinician advice and workplace heat-stress procedures, especially if fluid intake is medically restricted.
