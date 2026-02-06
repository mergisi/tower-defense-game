# 🏰 Crystal Siege — Tower Defense

A browser-based tower defense game built with vanilla HTML5 Canvas, CSS, and JavaScript. No frameworks, no dependencies — just open and play.

![Crystal Siege](https://img.shields.io/badge/Game-Tower%20Defense-00f0ff?style=for-the-badge) ![Tech](https://img.shields.io/badge/Built%20With-HTML5%20Canvas-ff2d7b?style=for-the-badge) ![License](https://img.shields.io/badge/License-MIT-ffd700?style=for-the-badge)

## 🎮 Play

Simply open `index.html` in your browser. No build step, no server required.

**[▶ Play Now on GitHub Pages](#)** *(enable GitHub Pages in repo settings to activate)*

## 🕹️ How to Play

1. **Select a tower** from the right panel (or press `1-4`)
2. **Click on the map** to place it on grass tiles (not on the path)
3. Press **Send Wave** (or `Spacebar`) to start each wave
4. **Survive 25 waves** of increasingly difficult enemies
5. **Click a placed tower** to upgrade it (up to 2 levels)

### Keyboard Shortcuts

| Key | Action |
|-----|--------|
| `1` | Select Bolt Tower |
| `2` | Select Blast Tower |
| `3` | Select Frost Tower |
| `4` | Select Beam Tower |
| `S` | Sell mode |
| `Space` | Send next wave |
| `ESC` | Cancel selection |
| `Right Click` | Cancel selection |

## 🗼 Towers

| Tower | Cost | Type | Description |
|-------|------|------|-------------|
| 🏹 **Bolt Tower** | 50g | Single Target | Fast attacks, medium range |
| 💣 **Blast Tower** | 100g | Area of Effect | Splash damage, slow fire rate |
| ❄️ **Frost Tower** | 75g | Slow/Debuff | Slows enemies by 50% |
| ⚡ **Beam Tower** | 150g | Continuous DPS | Laser beam, high sustained damage |

Each tower can be upgraded **twice** for increased damage, range, and special effects.

## 👾 Enemies

| Enemy | HP | Speed | Reward |
|-------|----|-------|--------|
| 🔴 **Scout** | Low | Normal | 10g |
| 🟠 **Runner** | Very Low | Fast | 15g |
| 🟣 **Brute** | High | Slow | 25g |
| 🟢 **Swarmer** | Very Low | Fast | 5g |
| 🔴 **Overlord** | Very High | Very Slow | 100g |

Enemy HP scales with each wave.

## ⚙️ Features

- **25 waves** with progressive difficulty
- **4 unique tower types** with 2 upgrade levels each
- **5 enemy types** including bosses
- **Sell & upgrade** mechanics
- **2× speed** mode
- **Particle effects** for explosions and kills
- **Responsive canvas** — adapts to window size
- **Keyboard shortcuts** for fast gameplay
- **Zero dependencies** — pure vanilla JS

## 🛠️ Tech Stack

- HTML5 Canvas for rendering
- Vanilla JavaScript (no frameworks)
- CSS3 with custom properties
- Google Fonts (Orbitron + Rajdhani)

## 📁 Project Structure

```
tower-defense-game/
├── index.html    # Complete game (single file)
├── README.md     # This file
└── LICENSE        # MIT License
```

## 🚀 Deploy

Enable **GitHub Pages** in your repo settings (Settings → Pages → Source: main branch) to get a free hosted version.

## 📄 License

MIT License — feel free to fork, modify, and use however you like.

---

Built with ❤️ and Canvas API
