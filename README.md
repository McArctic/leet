# LeetCode Daily Grind

A daily LeetCode queue with hidden patterns, a timer, and spaced retesting.
Installs on your phone like an app, works offline, and saves progress on the device.

## Host it free on GitHub Pages (about 5 minutes)

1. Create a new **public** repo on GitHub, for example `grind`.
2. Upload everything in this folder to the repo root (drag and drop on github.com works, or `git push`).
3. In the repo, go to **Settings → Pages**. Under "Build and deployment", pick **Deploy from a branch**, branch `main`, folder `/ (root)`, and save.
4. Wait a minute. Your app is live at `https://<your-username>.github.io/grind/`.

## Install it on your phone

- **iPhone:** open the link in **Safari** → Share button → **Add to Home Screen**.
- **Android:** open the link in **Chrome** → menu → **Install app** (or "Add to Home screen").

It opens full-screen with its own icon and works without internet.

## Where your progress lives

Progress is saved in that browser on that device. Your phone and laptop keep separate progress.
Use **Settings → Export backup** to save a file, and **Import backup** on another device to move it over.

On iPhone, use the home-screen app rather than a Safari tab. iOS can clear data for
websites you haven't opened in a while, but installed home-screen apps are kept.

## Updating the app

After you change `index.html`, bump `CACHE = "grind-v1"` in `sw.js` to `grind-v2` so phones pick up the new version.
