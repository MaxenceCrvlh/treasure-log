# Treasure Log

A card-vendor app for tracking One Piece TCG inventory (English and Japanese), lots, grading submissions, sales, card shows, side items and supplies.

**Your data is not in this repository.** Everything you log is saved only on your own device (in the browser's storage). This repository only holds the empty app.

## Install on iPhone
1. Open the site in **Safari**.
2. Tap **Share**, then **Add to Home Screen**.
3. Open Treasure Log from its new icon. It runs full-screen and works offline.

## Backups
Your log lives only on your phone. In the app, go to **Tools → Backup & restore**, tap **Create backup**, then **Save backup file** and choose **Save to Files → iCloud Drive**. Do this about once a week. To move to a new phone, install the app there and use **Restore from a file**.

## Optional: Claude features
Reading card photos and pasted comps with Claude needs your own Anthropic API key, entered in **Tools**. The key is stored only on your device.

## Files
- `index.html`: the whole app
- `sw.js`: lets it work offline and pick up updates
- `manifest.webmanifest` and the icons: home-screen install
