# CyberCat Adventures 🐱🌀

![Cyberpunk Cat Game](https://img.shields.io/badge/Theme-Cyberpunk-neongreen) 
![License](https://img.shields.io/badge/License-MIT-blue) 
![Accessibility](https://img.shields.io/badge/Accessibility-AA-orange)

A futuristic puzzle game where you strategically block pathways to trap an elusive cyber-cat in a neon-lit grid world.

## 🌟 Features

- **5 Difficulty Levels**: From 7x7 to 15x15 grids with adaptive AI
- **Cyberpunk Aesthetic**: Neon glow, matrix rain, and retro-futuristic design
- **Smart Cat AI**: Uses pathfinding algorithms to escape
- **Full Immersion Mode**: Optional fullscreen with scanline effects
- **Progressive Challenge**: Track your best moves for each level
- **Accessible Design**: Keyboard navigable with ARIA labels

## 🎮 How to Play

1. **Select your level** from the cyber-panel
2. **Click dots** to create barriers
3. **Trap the cat** before it reaches the edge
4. **Adjust difficulty** slider for smarter AI
5. **Track progress** with move counters and best scores

## 🛠️ Tech Stack

- Pure HTML/CSS/JS - No frameworks
- TailwindCSS for utility styling
- Canvas API for matrix rain effect
- Web Storage API for persisting best scores
- Fullscreen API for immersive mode

## 🚀 Quick Start

```bash
# No installation needed - just open in browser!
git clone https://github.com/your-repo/cybercat-adventures.git
open index.html
```

Or play directly by opening the HTML file in any modern browser.

## 🌈 Customization

Easily modify in the `<style>` section:
- Change neon colors (`--neon-blue`, `--neon-pink`, `--neon-green`)
- Adjust grid sizes in `LEVEL_CONFIG`
- Toggle visual effects (matrix rain, scanlines)

## 🤖 AI Behavior

The cat uses:
- Weighted random movement (based on difficulty)
- BFS pathfinding to find shortest escape
- Adaptive intelligence combining level + difficulty

## 📊 Stats Tracking

LocalStorage saves:
- Best moves for each level
- Persistent between sessions

## ♿ Accessibility

- Keyboard navigable
- ARIA labels for screen readers
- Color contrast compliant
- Reduced motion options (coming soon)

## 📜 License

MIT License - Free for personal and commercial use

---

**Pro Tip**: Try level 5 with max difficulty for the ultimate cyber-cat challenge! 💀

![Gameplay](https://kaleeswaran001.github.io/catch_the_cat1/) *Example gameplay animation*
