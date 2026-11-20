# PrismRSS — Colorful In-App Summary Reader (PWA)

**PrismRSS** is a lightweight, zero-backend Progressive Web App (PWA) designed for reading distraction-free RSS, stock, and keyword summaries directly inside the app without opening external websites.

## Repository Files
- `index.html` — Complete single-page application UI, reader, settings, and client-side RSS/Atom aggregator.
- `manifest.json` — Web App Manifest enabling standalone installation on Android, iOS, Windows, and macOS.
- `sw.js` — Service Worker caching the app shell and assets for offline startup.
- `icon.svg` — Scalable vector app icon used for favicons, home screen shortcuts, and maskable splash icons.

## How to Host & Install from GitHub Pages

1. **Create a GitHub Repository**
   - Create a new repository on GitHub (e.g., `prism-rss`) and upload `index.html`, `manifest.json`, `sw.js`, `icon.svg`, and `README.md` to the root folder.

2. **Enable GitHub Pages**
   - Go to **Settings → Pages** in your GitHub repository.
   - Under **Build and deployment**, set **Source** to **Deploy from a branch**.
   - Select your `main` branch and `/ (root)` folder, then click **Save**.
   - Wait ~1 minute for GitHub to publish your live HTTPS link (`https://<your-username>.github.io/<repo-name>/`).

3. **Install as a Native-Style App**
   - **Android (Chrome / Edge / Brave):** Open your GitHub Pages URL and tap the **Install App** button in the top header (or tap browser menu **⋮ → Install app**).
   - **iPhone / iPad (Safari):** Open your GitHub Pages URL, tap the **Share** icon, and choose **Add to Home Screen**.
   - **Desktop (Chrome / Edge):** Click the **Install** icon in the address bar or the **Install App** button in the header.