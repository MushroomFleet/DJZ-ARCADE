<div align="center">
<img width="1200" height="475" alt="GHBanner" src="https://github.com/user-attachments/assets/0aa67016-6eaf-458a-adb2-6e31a0763ed6" />
</div>

# REACT-TANKS

<div align="center">

[![Version](https://img.shields.io/badge/version-1.0.0-cyan.svg?style=flat-square)](https://github.com/yourusername/react-tanks/releases)
[![License](https://img.shields.io/badge/license-MIT-cyan.svg?style=flat-square)](LICENSE)
[![React](https://img.shields.io/badge/React-18.2.0-61dafb.svg?style=flat-square&logo=react)](https://reactjs.org/)
[![Three.js](https://img.shields.io/badge/Three.js-0.160.0-000000.svg?style=flat-square&logo=three.js)](https://threejs.org/)

*A TRON-inspired 3D tank combat game built with React and Three.js*

[Play in Browser](https://scuffedepoch.com/react-tanks/) • [Download Windows](https://github.com/yourusername/react-tanks/releases) • [Report Bug](https://github.com/yourusername/react-tanks/issues)

</div>

---

## 🎮 About

**REACT-TANKS** is a fast-paced 3D tank combat game featuring a stunning cyberpunk aesthetic inspired by TRON. Battle AI opponents across progressively challenging campaign levels, or create your own custom battlegrounds in the built-in level editor.

Built entirely with modern web technologies including React, TypeScript, and Three.js, the game showcases the power of WebGL and demonstrates advanced 3D graphics techniques in the browser.

### 🌟 Key Features

- 🎯 **Engaging Campaign Mode** - Progress through increasingly difficult levels with AI opponents
- 🛠️ **Level Editor** - Design and create your own custom battle arenas
- 🎨 **TRON-Inspired Aesthetics** - Cyberpunk visuals with neon lighting and grid effects
- 🎮 **Smooth Controls** - Responsive tank movement and aiming mechanics
- ⚡ **Power-ups & Pickups** - Strategic items to enhance your tank's capabilities
- 🤖 **AI Opponents** - Challenging computer-controlled enemies
- 🎵 **Immersive Audio** - Sound effects and ambient audio

---

## 🚀 Play Now

### 🌐 Web Version (Recommended)

**Play instantly in your browser - no installation required!**

👉 **[https://scuffedepoch.com/react-tanks/](https://scuffedepoch.com/react-tanks/)**

The web version offers the best experience with instant access and automatic updates.

### 💻 Desktop Version

**For offline play, download the Windows installer:**

1. Go to the [Releases](https://github.com/yourusername/react-tanks/releases) section
2. Download `React Tanks_1.0.0_x64_en-US.msi`
3. Run the installer
4. Launch from your Start Menu

**Requirements:** Windows 10/11 (64-bit)

---

## 🎯 How to Play

### Controls

| Action | Control |
|--------|---------|
| Move Forward | `W` |
| Move Backward | `S` |
| Turn Left | `A` |
| Turn Right | `D` |
| Aim | `Mouse` |
| Fire | `Left Click` |
| Pause Menu | `ESC` |

### Gameplay Tips

- **Keep Moving** - Stationary tanks are easy targets
- **Use Cover** - Arena obstacles can protect you from enemy fire
- **Collect Power-ups** - Purple pickups enhance your tank's abilities
- **Watch Your Health** - The health bar is displayed in the HUD
- **Aim Carefully** - Projectiles have travel time; lead your shots

### Game Modes

- **The Bunker (Campaign)** - Progress through challenging levels
- **Battle Tanks** - Quick skirmish mode
- **Level Editor** - Create and test custom arenas

---

## 🖼️ Screenshots

<div align="center">
<i>Screenshots coming soon</i>
</div>

---

## 🛠️ Tech Stack

### Core Technologies

- **[React](https://reactjs.org/)** - UI framework and component architecture
- **[TypeScript](https://www.typescriptlang.org/)** - Type-safe development
- **[Three.js](https://threejs.org/)** - 3D graphics rendering
- **[React Three Fiber](https://docs.pmnd.rs/react-three-fiber)** - React renderer for Three.js
- **[React Three Drei](https://github.com/pmndrs/drei)** - Useful helpers for R3F
- **[Vite](https://vitejs.dev/)** - Lightning-fast build tool
- **[Tailwind CSS](https://tailwindcss.com/)** - Utility-first CSS framework

### State Management & Utilities

- **[Zustand](https://github.com/pmndrs/zustand)** - Lightweight state management
- **[UUID](https://github.com/uuidjs/uuid)** - Unique ID generation

### Desktop Distribution

- **[Tauri](https://tauri.app/)** - Rust-powered desktop app framework

---

## 💻 Development

### Prerequisites

- **Node.js** (v18 or higher)
- **npm** or **yarn**
- **Rust** (for Tauri desktop builds)

### Local Development

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/react-tanks.git
   cd react-tanks
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start development server**
   ```bash
   npm run dev
   ```

4. **Open in browser**
   ```
   http://localhost:3000/react-tanks/
   ```

### Build Commands

| Command | Description |
|---------|-------------|
| `npm run dev` | Start development server |
| `npm run build:web` | Build for web deployment |
| `npm run preview` | Preview web build locally |
| `npm run tauri:dev` | Run desktop app in development |
| `npm run tauri:build` | Build Windows MSI installer |

### Project Structure

```
react-tanks/
├── components/
│   ├── three/         # 3D game objects (Tank, Arena, Effects, etc.)
│   └── ui/            # UI components (HUD, Menus, Buttons)
├── screens/           # Game screens (MainMenu, Battle, Editor)
├── hooks/             # Custom React hooks
├── systems/           # Game systems (AI, Physics)
├── types/             # TypeScript type definitions
├── utils/             # Utility functions
├── data/              # Game data (levels, presets)
└── src-tauri/         # Tauri desktop app configuration
```

---

## 📦 Distribution

### Web Deployment

The web version is deployed to: **https://scuffedepoch.com/react-tanks/**

To deploy your own instance:
```bash
npm run build:web
# Upload the dist/ folder to your web server
```

### Desktop Builds

Windows MSI installers are available in the [Releases](https://github.com/yourusername/react-tanks/releases) section.

To build your own:
```bash
npm run tauri:build
# Installer will be in: src-tauri/target/release/bundle/msi/
```

---

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 🙏 Acknowledgments

- TRON franchise for aesthetic inspiration
- React Three Fiber community for excellent 3D tools
- All contributors and players

---

<div align="center">

**Built with ❤️ using React and Three.js**

[⬆ Back to Top](#react-tanks)

</div>
