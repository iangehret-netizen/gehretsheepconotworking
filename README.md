# Gehret Sheep Co — Deploy to GitHub Pages

This folder is a ready-to-publish static website. No coding, npm, or command line needed — just upload it to GitHub and flip one setting.

## Step 1 — Create the repository
1. Go to **github.com** and sign in (or create a free account if you don't have one).
2. Click the **+** in the top right → **New repository**.
3. Name it something like `gehret-sheep-co` (name doesn't matter).
4. Set it to **Public** (required for free GitHub Pages).
5. Leave everything else unchecked, click **Create repository**.

## Step 2 — Upload these files
1. On your new repo's page, click **uploading an existing file** (or **Add file → Upload files**).
2. Drag in **all the files** from this folder: `index.html`, `bundle.js`, `manifest.json`, `apple-touch-icon.png`, `icon-192.png`, `icon-512.png`, `favicon-32.png`, `favicon-16.png`, and this `README.md`.
3. Scroll down, click **Commit changes**.

## Step 3 — Turn on GitHub Pages
1. In your repo, click **Settings** (top tab).
2. In the left sidebar, click **Pages**.
3. Under "Build and deployment" → **Source**, choose **Deploy from a branch**.
4. Under **Branch**, choose `main` and folder `/ (root)`, then **Save**.
5. Wait about a minute, then refresh — GitHub will show your live URL, something like:
   `https://YOUR-USERNAME.github.io/gehret-sheep-co/`

That's it — the app is live and shareable.

## Adding it to your iPhone home screen
1. Open your live link in **Safari** on your iPhone (must be Safari, not Chrome, for this to work).
2. Tap the **Share** button (square with an arrow pointing up).
3. Scroll down and tap **Add to Home Screen**.
4. You'll see the Gehret Sheep Co logo as the icon — tap **Add**.

It'll now sit on your home screen with your logo and open full-screen like a real app, no browser bar.

## Important note about data storage
This version stores all your records in your **browser's local storage** on whatever device/browser you're using it from — it is not synced to the cloud or shared between devices. Records made on your phone won't automatically appear on your laptop. If you clear your browser's site data, the records will be lost, so use the **Generate PDF** / **Generate Excel** buttons regularly to keep backups.

If down the road you want real cross-device sync, that would need a small backend (e.g. a free Supabase or Firebase database) — just ask and it can be added.
