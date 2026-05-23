# Our Story — Private Gallery

A Netflix-style private photo gallery powered by Google Drive.

## Files
- `index.html` — the full gallery app
- `manifest.json` — PWA manifest (makes it installable as an app)
- `sw.js` — service worker (offline support)

## Deploy to GitHub Pages (free, private URL)

### Step 1 — Create a GitHub account
Go to github.com and sign up (free).

### Step 2 — Create a new repository
1. Click the **+** icon → **New repository**
2. Name it: `our-story` (or anything you like)
3. Set it to **Public** (required for free GitHub Pages)
4. Click **Create repository**

### Step 3 — Upload the files
1. Click **Add file** → **Upload files**
2. Drag all 3 files: `index.html`, `manifest.json`, `sw.js`
3. Click **Commit changes**

### Step 4 — Enable GitHub Pages
1. Go to **Settings** → **Pages** (left sidebar)
2. Under **Source**: select **Deploy from a branch**
3. Branch: **main** / folder: **/ (root)**
4. Click **Save**

### Step 5 — Get your URL
After ~2 minutes your site is live at:
`https://YOUR-USERNAME.github.io/our-story`

Share this URL with your wife (and set a password inside the app for security).

## Features
- 🔐 Password lock screen
- 📂 Google Drive sync (auto-loads your photos)
- ⬆️ Upload directly to Drive from the gallery
- 🎬 Slideshow with Ken Burns effect
- ❤️ Favourites
- 🗓 On This Day memories
- 📁 Subfolder albums (each subfolder = its own Netflix row)
- 📊 Progress bars (Netflix-style view tracking)
- ▶ Continue Watching row
- ↗ Share individual photos
- ⚙️ Full settings panel (rename everything, change colours)
- 📱 Installable as an app on your phone (PWA)

## Install as phone app
On iPhone: open in Safari → Share → **Add to Home Screen**
On Android: open in Chrome → menu → **Add to Home Screen**

## Google Drive Setup
1. Create a folder named **"Our Gallery"** in Google Drive
2. Add photos and videos inside it
3. Create subfolders for albums (e.g. "Holidays", "Wedding", "2024")
4. Open the gallery → click Sync
