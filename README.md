# The Legendary Adventurers Convene 🛡️

An interactive, high-fidelity Guild Showcase and Hero Selection dashboard designed with modern UI/UX principles, replicating the fantasy-themed layout of legendary game adventurer classes.

## Features

- 🌌 **Visual Splendor**: Dark theme with gold-yellow title typography replicating the original "THE LEGENDARY ADVENTURERS CONVENE" header.
- 🎯 **Interactive Hotspots**:
  - Leverages the complete illustration as a responsive canvas.
  - Hovering over individual heroes spawns animated concentric **magic runes (summoning circles)** under their feet.
- 🃏 **Hero Card Deck**:
  - Switches to a grid layout presenting Hearthstone-style character cards.
  - Uses CSS background-offset positions to crop and present individual hero portraits dynamically from the primary background image.
- 🔍 **Detail Inspector Panel**:
  - Highlights details like lore, role types, signature abilities (with custom icons), and animated combat statistics bars (Attack, Defense, Magic, Speed).

## Quick Start

1. **Start the local server**:
   ```bash
   npm run dev
   ```
2. **Access the portal**: Open [http://localhost:3000](http://localhost:3000) in Chrome, Edge, or any modern web browser.
3. **Explore**:

- Toggle between **Illustration View** and **Card Deck** modes in the header.
- Hover or click on the 8 adventurer classes to inspect their profile statistics and abilities.

## GitHub Repository Sync

All files are version-controlled and hosted on GitHub at [cairns1105-cyber/Gemini-Demo](https://github.com/cairns1105-cyber/Gemini-Demo). To push updates from your local workspace:

```powershell
# Stage changes
git add .

# Commit changes
git commit -m "Update Guild Portal dashboard"

# Push to origin
git push origin main
```
