# Wrap Calculator

An offline-capable calculator for film-production wrap reports. It combines worked-time totals with optional page, runtime, and setup additions.

## Use it

- **Pages:** Enter whole pages and optional eighths. `/8` is static, so only digits are entered. Blank entries count as zero. Totals show as `3 5/8` or `1/8`.
- **Minutes:** Enter minutes and seconds in separate boxes. The colon is static. Extra seconds carry into minutes and the total shows as `MM:SS`.
- **Setups:** Enter up to three optional whole numbers. The total shows with at least two digits, such as `07`.
- Click any result in the Wrap Report section to copy it; it briefly says **Copied!**.
- For working time, enter Crew Call, Lunch In, Lunch Out, and Wrap Time as four digits, e.g. `0930`, `1530`, `1612`, `2121`. Overnight shifts work too. Click a calculation to copy it.

All editable fields accept digits only. The `/8`, `:`, and `+` symbols cannot be typed because they are fixed parts of the layout.

## Update GitHub Pages

1. Download and unzip the project.
2. Open your existing Wrap Calculator repository on GitHub.
3. Select **Add file** → **Upload files**.
4. Open the unzipped `wrap-calculator-expanded` folder and upload its contents: `index.html`, `style.css`, `script.js`, `manifest.json`, `sw.js`, `README.md`, and the `icons` folder. Do not upload the outer folder itself.
5. Commit with a message such as `Add wrap report totals`.
6. Wait one or two minutes for GitHub Pages, then reload. If you see the old app once, press **Ctrl + F5**; this release includes a fresh offline cache.

If GitHub Pages is not already enabled, open **Settings** → **Pages**, choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
