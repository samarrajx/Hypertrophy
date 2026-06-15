# 16-Day Hypertrophy Tracker — PWA

## Deploy to GitHub Pages

1. Create a new GitHub repo (e.g. `hypertrophy-tracker`)
2. Upload all files keeping this exact structure:
   ```
   hypertrophy-tracker/
   ├── index.html
   ├── manifest.json
   ├── sw.js
   └── icons/
       ├── icon-192.png
       ├── icon-512.png
       └── apple-touch-icon.png
   ```
3. Go to repo **Settings → Pages → Branch: main → Folder: / (root)** → Save
4. Your app will be live at: `https://yourusername.github.io/hypertrophy-tracker/`

## Features

- ✅ Reset button — clears all progress with confirmation dialog
- ✅ PWA — works offline after first load
- ✅ Installable — "Install App" button appears on Android/Chrome automatically
- ✅ iOS — tap Share → Add to Home Screen in Safari
- ✅ GitHub Pages compatible — all paths are relative (`./`)

## Notes

- Progress is saved in the browser's `localStorage`
- Reset only clears progress data, not the app itself
- Service worker caches the app for full offline use
