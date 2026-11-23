# NeoDevX — Mobile Games Privacy Policies & `app-ads.txt`

Public static legal hub for **NeoDevX / Milo Island Games** Android apps, keeping all actual game source code repositories (`hatch-merge-pets`, etc.) **100% private**.

## Live URLs
- **Studio Developer Website / Games Hub:** `https://neodevx72.github.io/`
- **Milo's Island Rescue Privacy Policy:** `https://neodevx72.github.io/games/milos-island-rescue/privacy-policy.html`
- **General Studio Privacy Policy:** `https://neodevx72.github.io/privacy-policy.html`
- **Root `app-ads.txt` (All Games):** `https://neodevx72.github.io/app-ads.txt`

## Adding a Future Game
1. Copy `games/_template/privacy-policy.html` to `games/<new-game-slug>/privacy-policy.html` and fill placeholders (`{{GAME_NAME}}`, `{{PACKAGE_ID}}`, `{{SAVE_FILE}}`, etc.).
2. Add a `<section class="game-card">` entry in `index.html` linking to `/games/<new-game-slug>/privacy-policy.html`.
3. Commit and push to `main`.

## Activating AdMob `app-ads.txt`
1. Copy your AdMob Publisher ID (`pub-XXXXXXXXXXXXXXXX`) from AdMob &rarr; **Settings &rarr; Account information**.
2. Uncomment and update the `google.com, pub-..., DIRECT, f08c47fec0942fa0` line in `app-ads.txt` and push to `main`.
3. Set `https://neodevx72.github.io` as your **Website** in Google Play Console &rarr; **Store settings**. Every current and future game under that developer account shares the single root `app-ads.txt`.
