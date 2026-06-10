# HUB Operations Dashboard

Static browser dashboard for HUB QC files. It runs directly from `index.html` and uses the bundled libraries in `vendor/`, so GitHub Pages can serve it without a backend.

## Upload to GitHub

Upload these files/folders:

- `index.html`
- `vendor/xlsx.full.min.js`
- `vendor/jszip.min.js`
- `.gitignore`
- `README.md`

Do not upload local data files or temporary files:

- `DriverPassKey.xlsx`
- `driverpasskey_embed.js`
- `driverpasskey_embed.json`
- `needreturn_sample.xlsx`
- `QCbyHUB.html`
- `tmp_inline_check.js`

## GitHub Pages

1. Push this repository to GitHub.
2. Open the repo settings.
3. Go to `Pages`.
4. Set source to the main branch and root folder.
5. Open the generated Pages URL.

The page no longer loads or compares against DriverPassKey data. Users can open the link, upload their operation files in the browser, and use the dashboard locally in their browser session.
