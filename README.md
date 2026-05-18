# Munich Trip Planner

Personal packing assistant for monthly Munich office trips. Built as a PWA — installs on iPhone home screen, works offline.

## What it does

- Enter departure and return dates
- Fetches live Munich weather forecast
- Generates a packing list scaled to your trip length (clothing quantities based on nights)
- Toggles for gym bag, toiletry restock, and private laptop
- Weather-adaptive clothing recommendations (rain jacket, warm coat, etc.)
- Tap items to check them off with a progress bar
- Add custom items to any section

## Deploy to GitHub Pages (5 minutes)

### Step 1 — Create the repo

1. Go to [github.com/new](https://github.com/new)
2. Name it **`munich-packer`**
3. Set to **Public** (required for free GitHub Pages)
4. Click **Create repository**

### Step 2 — Upload the files

Option A — GitHub web UI (easiest):
1. In your new repo, click **Add file → Upload files**
2. Drag in everything: `index.html`, `manifest.json`, `sw.js`, and the `icons/` folder
3. Commit to `main`

Option B — Git CLI:
```bash
git clone https://github.com/YOUR_USERNAME/munich-packer
cp -r /path/to/files/* munich-packer/
cd munich-packer
git add .
git commit -m "Initial deploy"
git push
```

### Step 3 — Enable GitHub Pages

1. Go to your repo → **Settings** → **Pages** (left sidebar)
2. Under **Source**, select **Deploy from a branch**
3. Branch: **main**, folder: **/ (root)**
4. Click **Save**

GitHub will show: *"Your site is being deployed"* — takes about 60 seconds.

Your URL will be: `https://YOUR_USERNAME.github.io/munich-packer/`

### Step 4 — Install on iPhone

1. Open Safari on your iPhone (must be Safari, not Chrome)
2. Go to `https://YOUR_USERNAME.github.io/munich-packer/`
3. Tap the **Share** button (box with arrow)
4. Scroll down and tap **Add to Home Screen**
5. Tap **Add**

Done. It now lives on your home screen like a native app — full screen, no browser chrome, works offline.

## Updating the app

Edit `index.html`, commit and push. GitHub Pages redeploys automatically within ~60 seconds.
