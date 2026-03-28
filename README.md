# Crate Pilot Landing Page

Static marketing site for Crate Pilot, ready for GitHub Pages hosting.

## Files
- `landing/index.html`
- `landing/styles.css`
- `landing/config.js`
- `landing/.nojekyll`
- `landing/assets/*`

## Configure the Windows download link (GitHub Releases)
Edit `landing/config.js` and set:

`window.CRATE_PILOT_DOWNLOAD_URL = "https://github.com/<owner>/<repo>/releases/download/<tag>/Crate-Pilot-Setup.exe";`

You can also keep a latest-link pattern:

`https://github.com/<owner>/<repo>/releases/latest/download/Crate-Pilot-Setup.exe`

All `Download` buttons on the page use this single value.

## Publish on GitHub Pages
1. Push this repository to GitHub.
2. In GitHub: `Settings` -> `Pages`.
3. Set source to `Deploy from a branch`.
4. Choose your branch (usually `main`) and folder `/landing` (or `/docs` if you move files there).
5. Save and wait for Pages to publish.

## Local preview
Open `landing/index.html` directly, or serve the folder with any static server.
