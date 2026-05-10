# The Pecking Order v0.1

A gravity-flipping office survival game (v0.1 - core mechanics implemented as side-scrolling avoider). Avoid corporate hazards by flying your businessman through meeting blocks. Features a looming executive rooster (chicken boss) that you must dodge. Power-ups include coffee shield, bad connection slow, and camera off shrink.

Built with vanilla HTML5 Canvas + JavaScript (self-contained single file game - play instantly in browser!). Not using Phaser.js in this version (future update planned).

**Note:** Gravity flipping mechanic described in initial concept but implemented as classic lift/gravity in v0.1. Hazards are meeting blocks (staplers concept in future).

## How to Play
- Tap/click/space to fly up (avoid meetings scrolling left)
- Collect power-ups (☕ shield, 📶 slow, 🚫 shrink)
- Dodge the chicken boss Director
- Survive as many "days" (meetings passed) as possible

## Files
- `index.html` - The complete game (open in browser)
- `flying_businessman.png` - Player sprite sheet (8 frames horizontal)
- `chicken_boss.png` - Boss sprite sheet (8 frames horizontal)

## Fixes Applied
- Improved chicken collision detection with accurate hitbox
- Fixed potential array mutation bug in meeting removal logic
- Updated title for branding consistency

Play it live at the GitHub Pages or just open index.html locally!

Made with ❤️ for office humor and retro game vibes.