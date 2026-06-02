# 🐧 Penguin Isle

A cozy penguin world-building game you can play right in your browser — no installs, no accounts needed.

**[▶ Play it live](https://YOUR-USERNAME.github.io/penguin-isle/)**

---

## Features

- 🌍 **World Builder** — Place buildings on your island grid and watch it grow
- 📖 **Story Mode** — 5 chapters with tasks, narrative, and unlockable content
- 🎮 **5 Mini-games** — Fish Catch, Ice Slide, Snowball Toss, Memory Match, Penguin Trivia
- 🛒 **Shop** — Spend fish to unlock 16 unique buildings & decorations
- 💾 **Auto-Save** — Progress is saved to your browser's localStorage, so it persists across reloads

---

## Deploy to GitHub Pages (free hosting)

1. **Create a new GitHub repository** (e.g. `penguin-isle`)
2. **Upload `index.html`** to the root of the repo
3. Go to **Settings → Pages**
4. Under *Source*, select **Deploy from a branch** → branch: `main`, folder: `/ (root)`
5. Click **Save** — your game will be live at `https://YOUR-USERNAME.github.io/penguin-isle/` in ~60 seconds

That's it! One file, zero dependencies, zero build steps.

---

## How to Play

| Action | How |
|--------|-----|
| Place a building | Click a building in the toolbar, then click any empty tile |
| Erase a tile | Click 🗑️ Erase, then click a tile |
| Expand your world | Earn fish in mini-games, then click "Expand World" |
| Unlock buildings | Complete story chapters OR buy from the Shop |
| Earn fish | Play any mini-game |

---

## Save Data

Progress is stored in your browser's `localStorage` under the key `penguin_isle_v2`.  
To reset: open your browser console and run `localStorage.removeItem('penguin_isle_v2')` then refresh.

---

## Tech Stack

- Pure HTML + CSS + JavaScript — no frameworks, no build tools
- Canvas API for mini-games
- Google Fonts (Nunito + Fredoka One)
- `localStorage` for persistence

---

Made with ❄️ and 🐟
