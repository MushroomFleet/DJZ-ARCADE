<div align="center">
<img width="1200" height="475" alt="GHBanner" src="https://github.com/user-attachments/assets/0aa67016-6eaf-458a-adb2-6e31a0763ed6" />
</div>

# REACTWARRIOR: MERCENARIES

A retro-styled 3D mech combat simulator built with React, Three.js, and Tauri. Pilot a heavily-armed BattleMech through intense tactical combat missions featuring heat management, weapon systems, and strategic maneuvering.

## 🎮 Features

- **Authentic Mech Combat** - Pilot a walking tank with realistic physics and heat management systems
- **Advanced Weapon Systems** - Configure multiple weapon groups with chain fire and alpha strike capabilities
- **Heat Management** - Balance firepower with cooling systems to avoid catastrophic shutdown
- **Jump Jets** - Navigate terrain with vertical thrust capabilities
- **Multiple Vision Modes** - Normal, Night Vision, and Thermal imaging
- **Targeting Computer** - Lock onto enemies with advanced targeting systems
- **Mission Navigation** - Follow waypoints and complete objectives
- **Level Editor** - Create custom missions with enemy placements and obstacles
- **Cockpit View** - First-person immersive cockpit or third-person tactical camera
- **Retro Aesthetic** - Classic green CRT terminal styling with scanline effects

## 🕹️ Controls

### Movement & Navigation
- **W / S** - Increase/Decrease Throttle
- **A / D** - Turn Legs (Steering)
- **Mouse** - Twist Torso (Aiming)
- **C** - Center Torso
- **Space** - Jump Jets

### Combat
- **1-5** - Fire Weapon Groups
- **\\** (Backslash) - Toggle Chain Fire Mode
- **R** - Cycle Target
- **Click on Weapons** - Edit Weapon Groups

### Sensors & Display
- **Z** - Cycle Zoom (1x, 2x, 4x)
- **V** - Cycle Vision Mode (Normal, Night Vision, Thermal)
- **F3** - Toggle Camera (Cockpit / Third Person)

### General
- **Click Screen** - Enable Mouse Look (when playing)
- **ESC** - Release Mouse Lock

## 📥 Installation

### Option 1: Desktop Application (Recommended)
Download the latest `.msi` installer from the [Releases](https://github.com/MushroomFleet/REACTWARRIOR2/releases) page.

1. Download `ReactWarrior-Mercenaries-[version].msi`
2. Run the installer
3. Launch from your Start Menu or Desktop

### Option 2: Play in Browser
Experience the game instantly without installation:

**🌐 [Play Live Web Version](https://scuffedepoch.com/reactwarrior2/)**

### Option 3: Development Build

**Prerequisites:** Node.js 18+, pnpm

```bash
# Clone the repository
git clone https://github.com/MushroomFleet/REACTWARRIOR2.git
cd REACTWARRIOR2

# Install dependencies
pnpm install

# Run web version
pnpm dev

# Run desktop version
pnpm tauri:dev

# Build for production
pnpm build
pnpm tauri:build
```

## 🎯 Gameplay Overview

### Heat Management
Your mech generates heat from movement and weapons fire. Manage your heat levels carefully:
- **Safe Zone** - Below 70% heat, all systems nominal
- **Warning Zone** - 70-99% heat, reduced performance
- **Shutdown** - 100% heat causes emergency shutdown

### Combat Systems
- **Weapon Groups** - Organize weapons into 5 configurable groups
- **Chain Fire** - Fire weapons sequentially to manage heat
- **Alpha Strike** - Fire entire group simultaneously for maximum damage
- **Targeting** - Lock onto enemies for improved accuracy and damage display

### Mission Objectives
- Navigate to waypoints marked on your HUD
- Eliminate all enemy units
- Complete all objectives to finish the mission

### Level Editor
Create custom missions:
1. Select "LEVEL EDITOR" from main menu
2. Place enemies and obstacles
3. Export mission file
4. Load in-game via "LOAD MISSION FILE"

## 🛠️ Technical Stack

- **React 19** - UI Framework
- **Three.js** - 3D Graphics
- **React Three Fiber** - React renderer for Three.js
- **Tauri** - Desktop application framework
- **Vite** - Build tool
- **TypeScript** - Type safety
- **Tailwind CSS** - Styling

## 📚 Citation

### Academic Citation

If you use this codebase in your research or project, please cite:

```bibtex
@software{reactwarrior_mercenaries,
  title = {ReactWarrior: Mercenaries - A React-based Mech Combat Simulator},
  author = {Drift Johnson},
  year = {2025},
  url = {https://github.com/MushroomFleet/REACTWARRIOR2},
  version = {1.0.0}
}
```

### Donate

Support development of ReactWarrior: Mercenaries:

[![Ko-Fi](https://cdn.ko-fi.com/cdn/kofi3.png?v=3)](https://ko-fi.com/driftjohnson)

---

<div align="center">
<p><strong>REACTOR ONLINE. SENSORS ONLINE. WEAPONS ONLINE. ALL SYSTEMS NOMINAL.</strong></p>
</div>
