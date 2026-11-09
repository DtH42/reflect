# Reflect

A private check-in journal that runs on an iPhone like an app. Entries are stored **only on the phone** — nothing is sent anywhere.

## Put it online (GitHub Pages, free)

1. On github.com, create a **new repository** (any name, e.g. `reflect`).
   - Free GitHub Pages needs the repo to be **Public**. That's fine here: the repo only holds the app's code, never her entries.
2. Click **Add file → Upload files**, drag in every file from this folder, then **Commit changes**.
3. Go to **Settings → Pages**. Under *Build and deployment*, set Source to **Deploy from a branch**, Branch **main**, folder **/ (root)**, then **Save**.
4. After a minute or two the page shows the address, like `https://YOUR-USERNAME.github.io/reflect/`.

## Install on her iPhone

1. Open that address in **Safari** (must be Safari).
2. Tap the **Share** button → **Add to Home Screen** → **Add**.
3. Open it from the new Reflect icon from then on. It works offline.

## Good to know

- **Backups:** Entries live in Safari's storage on that phone. If she deletes the app icon or clears Safari website data, they're gone. Use **Share → Save backup** now and then (save to Files / iCloud Drive). The Share tab shows a red dot when a backup is overdue.
- **For therapy:** **Share → Create summary** builds a readable report for a date range she can share, copy, or print to PDF. **Download CSV** gives a spreadsheet.
- **Privacy:** Her phone's passcode / Face ID is the lock. The app name and icon are deliberately neutral.
- **Updating the app:** Edit the files, bump `VERSION` in `sw.js` (e.g. `reflect-v2`), and upload again. Her entries are untouched by updates.
