<div align="center">
<img width="1200" height="475" alt="GHBanner" src="https://github.com/user-attachments/assets/0aa67016-6eaf-458a-adb2-6e31a0763ed6" />
</div>

# REACT-ACE
## Vector Combat Simulation

A retro-style 3D space combat game built with React, Three.js, and TypeScript. Defend the Mega Carrier from waves of enemy fighters in intense time-limited missions. Features classic vector graphics aesthetics with modern web technology.

<div align="center">

### [🎮 PLAY NOW](https://scuffedepoch.com/react-ace/) | [📦 DOWNLOAD INSTALLER](https://github.com/MushroomFleet/DJZ-ARCADE/releases)

</div>

---

## 🎯 Game Overview

You are the last line of defense for the **Mega Carrier** - a massive capital ship attempting to complete a hyperjump sequence. Enemy fighters are closing in with nuclear torpedoes, and you must eliminate all threats before time runs out.

Each successful mission earns credits to upgrade your fighter in the **Hangar**, unlocking more powerful weapons and systems to tackle increasingly difficult waves.

### Key Features

- ⚡ **Mission-Based Gameplay** - Time-limited objectives with escalating difficulty
- 🚀 **Upgrade System** - Enhance your fighter's speed, hull, weapons, and radar
- 🔫 **Advanced Weaponry** - Unlock special systems like Point Defense, Combat Drones, and Quasar Wave super-weapon
- 🎨 **Retro Vector Graphics** - Classic SVGA-style vertex shading with scanline effects
- 💾 **Progress Saving** - Your upgrades and score persist between sessions
- 🎮 **Customizable Controls** - Invert pitch/yaw and adjust sensitivity to your preference

---

## 🕹️ Controls

### Flight Controls
| Action | Keys |
|--------|------|
| **Pitch** | W / S |
| **Yaw** | A / D |
| **Roll** | Q / E |
| **Throttle** | Shift / Ctrl |
| **Afterburner** | Tab (hold) |

### Combat
| Action | Keys |
|--------|------|
| **Fire Weapon** | Space |
| **Lock Target** | R |
| **Auto-Chase** | F (hold) |
| **Quasar Wave** | V (if owned) |

> **Tip:** Enable inverted controls in Settings if you prefer flight sim-style controls!

---

## 🛠️ Upgrade System

### Core Systems (Max Level 5)
Enhance fundamental ship capabilities:
- **Turbine Engine** - +10% Speed & Acceleration per level
- **Nano-Composite Hull** - +10% Hull Strength & Handling per level
- **Missile Systems** - +10% Damage & Reload Speed per level
- **Avionics Suite** - +10% Radar Range per level

### Advanced Weaponry (Max Level 2)
Unlock devastating special systems:
- **PDS Defense** - Auto-targeting point defense turret (Lvl 2: 2x range & fire rate)
- **Dual Drones** - AI wingmen with auto-cannons (Lvl 2: enhanced combat parameters)
- **Quasar Wave Engine** - Devastating energy beam super-weapon (Lvl 2: chain lightning & massive AOE)
- **Missile Engineering** - Enhanced warhead systems (Lvl 2: +100% speed & massive blast radius)

---

## 🎮 Play Options

### 🌐 Web Version (Instant Play)
No installation required! Play directly in your browser:

**[▶️ LAUNCH GAME](https://scuffedepoch.com/react-ace/)**

*Requires a modern browser with WebGL support. Works best on Chrome, Edge, or Firefox.*

### 💿 Offline Version (Windows)
Download the standalone installer for offline play:

**[📥 Download Latest Release](https://github.com/MushroomFleet/DJZ-ARCADE/releases)**

Available formats:
- Windows MSI Installer (`.msi`)
- Windows NSIS Setup (`.exe`)

---

## 🎨 Graphics Settings

### SVGA Vertex Shading
Toggle between classic wireframe and retro solid-fill rendering with vertex lighting. The solid-fill mode emulates the look of classic SVGA-era 3D games while maintaining smooth 60 FPS performance.

### Visual Effects
- **Scanlines** - Authentic CRT monitor effect
- **Vignette** - Classic tunnel vision effect for immersion
- **Retro UI** - Monospace green text on black, true to 80s vector arcade aesthetic

---

## 🏆 Gameplay Tips

1. **Manage Your Time** - Each mission has a countdown. Clear enemies quickly to maximize your time bonus!
2. **Prioritize Upgrades** - Focus on weapon and engine early for better combat effectiveness
3. **Use Special Weapons Wisely** - Advanced systems have cooldowns but can turn the tide of battle
4. **Master Auto-Chase** - Hold F to automatically track targets while you focus on firing
5. **Save Between Missions** - Your progress auto-saves, so you can return anytime

---

## 🛠️ Development

### Prerequisites
- Node.js 18+ or Bun
- Modern browser with WebGL support

### Local Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/MushroomFleet/DJZ-ARCADE.git
   cd DJZ-ARCADE
   ```

2. Install dependencies:
   ```bash
   bun install
   # or
   npm install
   ```

3. Start development server:
   ```bash
   bun run dev
   # or
   npm run dev
   ```

4. Open http://localhost:3000

### Building

**Web Build:**
```bash
bun run build
```

**Desktop Build (Tauri):**
```bash
bun run tauri:build
```

---

## 📝 Tech Stack

- **React 19** - UI framework
- **Three.js** - 3D graphics engine
- **@react-three/fiber** - React renderer for Three.js
- **@react-three/drei** - Three.js helpers
- **Zustand** - State management
- **TypeScript** - Type safety
- **Vite** - Build tool
- **Tauri** - Desktop app framework

---

## 📄 License

This project is open source. See the repository for license details.

---

## 🎮 Credits

Developed with ❤️ for retro gaming enthusiasts.

**Repository:** [github.com/MushroomFleet/DJZ-ARCADE](https://github.com/MushroomFleet/DJZ-ARCADE)

---

<div align="center">

**Ready to defend the carrier?**

[🚀 PLAY NOW](https://scuffedepoch.com/react-ace/)

</div>
