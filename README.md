# Reel Empire — Fishing Tycoon

A colorful, pixel-art automatic fishing game. Start on a tiny dock with a basic rod and bluegill, then grow into private lakes, deep-sea charters, tournament wins, and a complete rare-fish collection. A fish is caught automatically every three seconds while the game is open. The fishing-specific navigation includes Tycoon, Rods, Bait Shop, Anglers, Trips, and Fishdex.

The game saves automatically in the player's browser. It has no dependencies, accounts, or server, so it works free on GitHub Pages.

When the site opens, players see a pixel-art welcome screen and enter with **Play as Guest**. No account or Apple sign-in is used.

For testing, the small **DEV** button in the top HUD toggles Developer Mode. While active, coins display as `∞` and purchases cost nothing. Turning it off restores the exact coin balance saved when Developer Mode was enabled.

## Put the game on GitHub (step by step)

### 1. Download and unzip the project

Download `reel-empire.zip` from Codex and unzip it. Inside you should see:

- `index.html` — the whole game
- `icon.svg` — the browser/app icon
- `lake-background.png` — the pixel-art lake scene
- `fish-bass.png` — animated lake bass sprite
- `fish-trout.png` — animated lake trout sprite
- `fish-bluegill.png` — animated lake bluegill sprite
- `README.md` — this guide

### 2. Make a GitHub account

Go to [github.com](https://github.com), select **Sign up**, and follow the prompts. If you already have an account, sign in.

### 3. Create the repository

1. Select the **+** button in the top-right corner.
2. Select **New repository**.
3. Enter `reel-empire` for the repository name.
4. Choose **Public**.
5. Leave “Add a README file” unchecked because this project already has one.
6. Select **Create repository**.

### 4. Upload the game files

1. On the empty repository page, select **uploading an existing file**.
2. Drag `index.html`, `icon.svg`, `lake-background.png`, `fish-bass.png`, `fish-trout.png`, `fish-bluegill.png`, and `README.md` into the upload box. Upload the files themselves—not the outer folder or ZIP file.
3. In the “Commit changes” box, type `Add Reel Empire game`.
4. Select **Commit changes**.

### 5. Turn on the live website

1. Open the repository's **Settings** tab.
2. In the left menu, select **Pages**.
3. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
4. Set the branch to **main**, keep the folder as **/(root)**, then select **Save**.
5. Wait one or two minutes, then refresh the Pages settings screen.

GitHub will show the live address. It normally looks like:

`https://YOUR-USERNAME.github.io/reel-empire/`

Open that address on a phone or computer and share it with anyone.

## Update the game later

1. Open the repository on GitHub.
2. Select **Add file**, then **Upload files**.
3. Upload the changed `index.html` and allow GitHub to replace it.
4. Select **Commit changes**.
5. The public game updates automatically after a minute or two.

## Test before uploading

Double-click `index.html` to play locally. Progress is stored separately for each browser and website address. Clearing browser site data resets the save.

## Game progression

- Start: tiny dock, basic rod, bluegill
- Upgrade: rods, bait, boats, catch-value Angler bonuses, and fishing spots
- Late game: own a lake, run deep-sea charters, win tournaments, and collect eight fish rarities
