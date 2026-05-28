# Snow Glide

Snow Glide is a 2D endless runner built in C++ with **raylib**. You glide across a snowy landscape, collect coins, and survive as long as possible while the pace gradually ramps up.

## What's it about
You play as a lone rider sliding through a winter world. The game focuses on timing jumps, managing mana, and choosing when to use special abilities so you can keep your health up and your score climbing. Coins you collect during a run become your score and are also saved for upgrades in the workshop.

## How to play
1. **Start a run:** From the main menu, click the **"tap to start"** area.
2. **Jump to survive:** Use **Space** to jump. Jumping costs **1 mana**.
3. **Avoid hazards:**  
   - **Rocks** and **birds** damage your health.  
   - Birds also remove a few coins from your current run.
4. **Collect coins:** Coins are your **score** for the run and are added to your **total coins** when the run ends.
5. **Use power-ups:**  
   - **Magnets** pull nearby coins toward you for a short time.  
   - **Ice crystals** slow you temporarily, making timing trickier.
6. **Activate Bankai (B):** A powerful ability that clears current hazards, costs mana, and has a cooldown. You can reduce its cost and cooldown in the workshop.
7. **Game over:** When health reaches 0, you can enter a name for the high-score board, then return to the menu and spend coins on upgrades.

## Controls
- **Space** — Jump (uses mana)
- **B** — Bankai ability
- **Mouse** — UI buttons (tap to start, workshop, high score, pause/resume, sound toggle)
- **Esc / Backspace** — Return to menu
- **Right Arrow** — Enter Zen/credits scene from the menu
- **Left Arrow** — Return from Zen mode
- **Enter / Backspace** — Confirm or edit your name on the high-score entry screen

## Modes & menus
- **Endless Run:** Main gameplay loop; speed increases over time.
- **Workshop:** Spend coins to upgrade max health, max mana, Bankai cooldown, and Bankai cost. Cycle available skins (YUSEOL, ITACHI, GOKU).
- **High Score:** View your best run and top 5 scores.
- **Zen Mode:** A calm, scrolling credits scene accessible from the menu.

## Build & run
**Requirements**
- raylib 5.0
- C++14-compatible compiler (e.g., g++)
- make

**Build**
```bash
cd Snow-Glide-main
make
```

**Run**
- Linux/macOS: `./game`
- Windows: `game.exe`

> The game expects `img/` and `sound/` assets to be present in the working directory.
