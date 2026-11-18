# Plot Twisted — Recognition Update

Production files:
- `index.html`
- `clues.json`
- `manifest.webmanifest`, `sw.js`, `assets/` (install and offline support; icons are placeholders, and `assets/og-image.png` is still to be added)

Archive: `archive/clues.md` (not served)

Changes:
- Recognition-first answer matching
- `Sonic` counts for `Sonic the Hedgehog`
- `Zelda` or `Legend of Zelda` counts when only one Zelda game appears in the current run
- Franchise shorthand is accepted only when it points to one current question
- Existing aliases, typo tolerance, and number-optional matching remain
- Display Theme removed from Settings
- Main menu gains subtle cartridge motion, pixel activity, status readout, title signal glitch, and animated Start control
- Compact letter-only keyboard is unchanged

Fixes in this pass:
- Stage advances cancel when you eject to the title
- The boss is a hard clue when the deck has no difficulty-3 clues
- The More Modes cheat only reports an unlock when its button exists
- Installable shell with offline support; clues refresh network-first

Replace the existing `index.html` and `clues.json` with these files, and add the new files alongside them.
