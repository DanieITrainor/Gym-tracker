# ReComp — 16-Week Tracker

A Progressive Web App (PWA) for tracking your 16-week body recomposition program.

## How to Install

### Option A: Host on GitHub Pages (Recommended — Free)
1. Create a free GitHub account at github.com
2. Create a new repository called `recomp-tracker`
3. Upload all 5 files: `index.html`, `manifest.json`, `sw.js`, `icon-192.png`, `icon-512.png`
4. Go to Settings → Pages → Source: `main branch`
5. Visit your URL (e.g. `https://yourname.github.io/recomp-tracker`)
6. On iOS: tap Share → "Add to Home Screen"
7. On Android: tap the install banner or Menu → "Add to Home Screen"

### Option B: Host on Netlify (Also Free)
1. Go to netlify.com → New site from drag & drop
2. Drag the entire folder onto the page
3. Install from the generated URL

### Option C: Local network (no internet hosting needed)
1. Install Python on your computer
2. Put files in a folder and run: `python3 -m http.server 8080`
3. Find your local IP (e.g. 192.168.1.100)
4. On your phone visit: `http://192.168.1.100:8080`
5. Add to home screen

## Features
- ✅ Fully offline capable once installed
- ✅ Data saved to your device (localStorage)
- ✅ Rest timer with vibration feedback
- ✅ Track weight & reps per set
- ✅ JSON backup & restore
- ✅ 16 weeks × 7 days × full exercise list
- ✅ Progress tracking per week

## Files
- `index.html` — Main app
- `manifest.json` — PWA config
- `sw.js` — Service worker (offline support)
- `icon-192.png` — App icon
- `icon-512.png` — App icon (large)
