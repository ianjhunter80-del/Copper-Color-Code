# 25-Pair Color Code — PWA

Translates copper pair numbers to 25-pair color codes and back. Works offline on Android as an installable app.

---

## Files

```
index.html    ← The entire app
manifest.json ← Makes it installable as a PWA
sw.js         ← Service worker (enables offline use)
icon-192.png  ← App icon (you need to create this)
icon-512.png  ← App icon large (you need to create this)
```

---

## Deploy to GitHub Pages (free, ~10 minutes)

1. Go to https://github.com and create a free account if you don't have one
2. Click **New repository** → name it `25pair` → set to **Public** → click Create
3. Click **Add file → Upload files** and drag in all 4 files (index.html, manifest.json, sw.js, and your icons)
4. Commit the files
5. Go to **Settings → Pages → Source** → select `main` branch → click Save
6. Your app will be live at: `https://YOUR-USERNAME.github.io/25pair`

### Install on Android
1. Open the URL above in **Chrome on Android**
2. Tap the three-dot menu (top right)
3. Tap **"Add to Home screen"**
4. It installs like a real app — works offline too!

---

## Icons

You need two PNG icon files. Quick options:
- Use a free tool like https://realfavicongenerator.net
- Or just make a simple colored square in any image editor and export as:
  - `icon-192.png` — 192×192 pixels
  - `icon-512.png` — 512×512 pixels

A simple dark blue square (#1a1a2e) with "25P" text in white works great.

---

## Google Play Store (optional, later)

Once your PWA is live on GitHub Pages:
1. Go to https://www.pwabuilder.com
2. Enter your GitHub Pages URL
3. Click **Build My PWA → Android**
4. It generates an APK and Android Studio project
5. Create a $25 Google Play Developer account at play.google.com/console
6. Submit the APK

The app works great as a PWA home screen install without needing the Play Store.
