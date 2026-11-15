# Field Shift — Satellite Agriculture Intelligence

An interactive, bilingual (**English & Urdu**) Progressive Web App (PWA) for agricultural decision-making across all **36 districts of Punjab**, powered by **NASA POWER** climate data, **NASA SMAP L4** soil moisture telemetry, and **Punjab Crop Reporting Service (2024–25)** yield statistics.

## Features
- **36-District Punjab Geospatial Map**: Interactive SVG map with the five rivers and live district telemetry.
- **Crop Rotation Engine**: Compares 7 crop rotations scored out of 100 based on water savings, soil organic carbon, nitrogen fixation, and climate resilience.
- **12-Month Sow & Harvest Gantt Calendar**: Visual schedule for Kharif, Rabi, and Zaid crops.
- **District Yields & PKR Profit Calculator**: Real-time harvest and net margin calculator in Pakistani Rupees.
- **Soil & NASA Labs**: Clay/Sand/Silt composition, soil pH scale, and organic carbon indicators.
- **Installable Progressive Web App (PWA)**: Works offline and can be installed directly onto Android, iOS, Windows, and macOS devices.

## Deploying to GitHub Pages
1. Create a new repository on GitHub (e.g., `field-shift-app`).
2. Upload all files from this repository (`index.html`, `manifest.json`, `sw.js`, `icon.svg`, `README.md`, and `.nojekyll`) to the root of your `main` branch.
3. Go to **Settings → Pages** in your GitHub repository.
4. Under **Build and deployment**, select **Deploy from a branch**, choose `main` and `/ (root)`, and click **Save**.
5. Your live web app will be published at `https://<your-username>.github.io/<repo-name>/` and can be installed as an app from any browser.
