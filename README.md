# Wellness Wheel

A daily check-in for the eight dimensions of wellness: Emotional, Environmental, Financial, Intellectual, Occupational, Physical, Social and Spiritual. Rate each one from 1 to 10, add an optional reason, and see your week's balance on the wheel.

Based on the Six Dimensions of Wellness Model by Dr. Bill Hettler (National Wellness Institute) and the Eight Dimensions of Wellness by Dr. Margaret Swarbrick.

## Files

| File | What it does |
|---|---|
| `index.html` | The whole app |
| `manifest.webmanifest` | Name, colors and icons for "Add to Home Screen" |
| `sw.js` | Lets the app open offline |
| `icons/` | App icons |

## Publish on GitHub Pages

1. Sign in at github.com (or create a free account).
2. Click **+** (top right) → **New repository**. Name it `wellness-wheel`, set it to **Public**, and click **Create repository**.
3. On the new repo page, click **uploading an existing file**.
4. Unzip `wellness-wheel-app.zip`, then drag everything *inside* the folder (`index.html`, `manifest.webmanifest`, `sw.js`, `README.md`, and the `icons` folder) into the upload area. Click **Commit changes**.
5. Go to **Settings** → **Pages**. Under *Build and deployment*, set Source to **Deploy from a branch**, Branch to **main**, folder **/ (root)**, and click **Save**.
6. Wait a minute or two, then refresh the Pages settings. Your link appears at the top: `https://YOUR-USERNAME.github.io/wellness-wheel/`

GitHub Pages sites on free accounts must be public repos. The page's address is public, but your scores never leave your device.

## Install it on your phone

- **iPhone (Safari):** open your link → Share button → **Add to Home Screen**.
- **Android (Chrome):** open your link → ⋮ menu → **Install app** (or **Add to Home screen**).

After that it opens full-screen with its own icon, and works without internet.

## Your data

Scores are saved in the browser on each device (localStorage). They don't sync between devices, and clearing your browser's site data erases them. Use **Download backup** at the bottom of the app now and then, and **Restore from backup** to move your history to another device.

## Making changes later

Edit a file on GitHub (open it → pencil icon → **Commit changes**). If you change anything, also open `sw.js` and bump `VERSION` (e.g. `ww-v1` → `ww-v2`) so installed copies pick up the update.
