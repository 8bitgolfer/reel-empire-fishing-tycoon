# Reel Empire — Fishing Tycoon

A colorful, pixel-art automatic fishing game. Start on a tiny dock with a basic rod and bluegill, then grow into private lakes, deep-sea charters, legendary waters, and a complete rare-fish collection. A fish is caught automatically every three seconds while the game is open. The fishing-specific navigation includes Tycoon, Rods, Upgrades, Crates, Hub, and Fishdex.

The game saves automatically in the player's browser. It has no dependencies, accounts, or server, so it works free on GitHub Pages.

The layout automatically switches to a complete portrait lake on phones, keeping every navigation tab, counter, and the stats row on screen without horizontal cropping. Desktop keeps the original wide lake layout.

When the site opens, players see a pixel-art welcome screen and enter with **Play as Guest**. No account or Apple sign-in is used.

For testing, the small **DEV** button in the top HUD toggles Developer Mode. While active, coins display as `∞` and purchases cost nothing. Turning it off restores the exact coin balance saved when Developer Mode was enabled.

## Living-world gameplay

- Offline crew earn for up to 8 hours at 35% catch value and can find gems using your current bait odds.
- Live fishing builds Angler Momentum and is the only way to catch trophy fish.
- Weather changes every 2 minutes, migrations every 5 minutes, and seasons every 10 minutes. Each changes value, rarity, trophy odds, or bite patterns.
- Trips focus on dock evolution and fishing spots.
- The Upgrades page combines Bait Shop, Anglers, and Trips into internal tabs and opens to Bait Shop by default.
- Named trophy fish have randomized weights, species records, and a six-fish personal aquarium.
- Players can specialize the dock as a Marina, Research Station, Fishing Resort, or Conservation Lake, then build it through three visible stages.
- The economy is tuned for a smoother start: early bait, angler, and travel upgrades are cheaper, while later upgrades still scale into a long grind.
- The Tycoon lake uses lightweight animated water shimmer, ripples, canopy sway, drifting leaves, and swimming fish on both desktop and phones.
- Trophy aquarium cards show each fish's formatted sale value.
- Bait now raises gem-drop odds from 1% on starter bait up to 10% on max bait, with the exact chance shown in each bait description.
- Rods are crate-only unlocks bought with gems. Tier 1 crates contain rods 1-6, Tier 2 crates contain rods 7-12, and Tier 3 crates contain rods 13-18.
- Crates are tuned for slower progression: Tier 1 costs 80 gems, Tier 2 costs 650 gems, and Tier 3 costs 4,200 gems.
- The strongest owned rod equips automatically.
- Rods have rarities, duplicate crate pulls refund half the crate price in gems, and the Rods tab is sorted by rarity.
- Crate keys can open crates without spending gems.
- The Captain's Hub adds daily quests, rotating live events, and prestige.
- Trophy aquariums now give passive empire bonuses based on trophy count, species variety, and records.
- Prestige resets the economy for permanent Pearls while keeping Fishdex, trophies, records, and rod collection.
- Returning players see an offline welcome report, plus a placeholder **Watch an ad and get 2x coins** bonus button for future ad integration.
- The bottom HUD now focuses on Coins, Gems, and Caught; Fish / Min, Level, and the redundant Auto Fishing panel were removed.

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

- `lake-background-mobile.png` - the portrait pixel-art lake scene used on phones

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
3. Upload the changed `index.html`, `README.md`, and any new or changed image files, then allow GitHub to replace files with matching names.
4. Select **Commit changes**.
5. The public game updates automatically after a minute or two.

## Test before uploading

Double-click `index.html` to play locally. Progress is stored separately for each browser and website address. Clearing browser site data resets the save.

## Game progression

- Start: tiny dock, basic rod, bluegill
- Upgrade: 18 crate-only rods with rarities, 19 bait tiers, 19 catch-value Angler bonuses, and 20 fishing spots
- Billionaire endgame: maximum upgrades still climb into massive late-game prices
- Trips are functional: spots unlock species and multiply value up to 220×
- Late game: own a lake, run deep-sea charters, reach legendary waters, and collect eight fish rarities
- Long-term loop: chase crate keys, complete daily quests, collect high-value trophies, and prestige for permanent Pearls
