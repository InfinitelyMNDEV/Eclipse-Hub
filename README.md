<div align="center">

# ✨ Eclipse Hub

### A premium, lightweight Roblox script interface built on top of WindUI

[![WindUI](https://img.shields.io/badge/UI%20Library-WindUI-8A2BE2?style=for-the-badge)](https://github.com/Footagesus/WindUI)
[![Status](https://img.shields.io/badge/Status-Active-brightgreen?style=for-the-badge)]()
[![License](https://img.shields.io/badge/License-All%20Rights%20Reserved-red?style=for-the-badge)]()
[![Platform](https://img.shields.io/badge/Platform-Roblox-000000?style=for-the-badge&logo=roblox)]()

**Eclipse Hub** is a clean, modular, and constantly updated Roblox interface designed to give you a smooth, no-bloat experience across supported games. Built entirely on the [WindUI](https://github.com/Footagesus/WindUI) framework for a modern look, buttery animations, and rock-solid performance.

[Getting Started](#-getting-started) • [Features](#-features) • [Supported Games](#-supported-games) • [FAQ](#-faq) • [Disclaimer](#️-disclaimer)

</div>

---

## 📖 Table of Contents

- [About Eclipse Hub](#-about-eclipse-hub)
- [Features](#-features)
- [Supported Games](#-supported-games)
- [Getting Started](#-getting-started)
  - [Requirements](#requirements)
  - [Installation](#installation)
- [Usage Guide](#-usage-guide)
- [UI Overview](#-ui-overview)
- [Configuration & Settings](#-configuration--settings)
- [Roadmap](#-roadmap)
- [Changelog](#-changelog)
- [FAQ](#-faq)
- [Troubleshooting](#-troubleshooting)
- [Credits](#-credits)
- [Contributing](#-contributing)
- [Disclaimer](#️-disclaimer)
- [License](#-license)

---

## 🧭 About Eclipse Hub

Eclipse Hub was built with one goal in mind: deliver a **fast, stable, and visually polished** control panel for supported Roblox experiences without the clutter, lag, or confusing menus that plague most script interfaces.

Instead of reinventing the wheel on UI design, Eclipse Hub is powered by **WindUI**, a modern Roblox UI library known for its fluid animations, clean visual hierarchy, and developer-friendly API. This means every toggle, slider, dropdown, and tab you interact with inside Eclipse Hub benefits from a battle-tested rendering engine — so the focus stays entirely on functionality.

> Eclipse Hub is currently in an early, focused stage of development — supporting **one** game with full depth and precision rather than spreading thin across many.

---

## 🚀 Features

| Feature | Description |
|---|---|
| 🎨 **WindUI-Powered Interface** | Smooth animations, modern layout, and a fully responsive window system |
| ⚡ **Lightweight Footprint** | Minimal memory and performance overhead — won't tank your FPS |
| 🧩 **Modular Tab System** | Organized categories so features are always easy to find |
| 🔄 **Auto-Update Ready** | Structured to receive live updates without needing a full re-inject |
| 💾 **Config Saving** | Save and load your preferred toggle/slider setup automatically |
| 🖱️ **Draggable / Resizable Window** | Move and resize the UI anywhere on screen |
| 🔔 **In-UI Notifications** | Get real-time feedback via WindUI's notification system |
| 🌙 **Theme Support** | Multiple color themes inherited from WindUI's theming engine |
| 🛡️ **Safety-First Design** | No unnecessary permissions, no obfuscation abuse, transparent execution |

---

## 🎮 Supported Games

Eclipse Hub currently supports the following experience(s):

| Game | Status | Notes |
|---|---|---|
| **Examination** | ✅ Fully Supported | Actively maintained, primary focus of development |

> More games may be added in future releases. Check the [Roadmap](#-roadmap) section for planned expansions.

---

## 🛠️ Getting Started

### Requirements

Before using Eclipse Hub, make sure you have:

- ✅ A **Roblox executor** capable of running Luau scripts (with a stable HTTP request function such as `game:HttpGet` or `request`)
- ✅ An active internet connection (the script is loaded remotely via `loadstring`)
- ✅ The game **Examination** open and loaded in Roblox

### Installation

1. Open your executor of choice.
2. Join the **Examination** game in Roblox.
3. Paste the following script into your executor:

```lua
loadstring(game:HttpGet("https://raw.githubusercontent.com/InfinitelyMNDEV/Eclipse-Hub/refs/heads/main/Loader.lua"))()
```

4. Execute the script.
5. The Eclipse Hub window will appear — you're ready to go! 🎉

> ⚠️ Replace the placeholder link above with your actual raw script URL before publishing this repository.

---

## 📘 Usage Guide

Once Eclipse Hub loads, you'll be greeted with the main WindUI window containing organized tabs. Here's a general breakdown of how to navigate it:

1. **Main Tab** — Core toggles and quick-access features for Examination.
2. **Settings Tab** — UI preferences, theme selection, and keybind configuration.
3. **Config Tab** — Save, load, or reset your personal configuration profile.
4. **Info Tab** — Version number, credits, and support links.

Toggle switches, sliders, and dropdowns behave exactly as expected from a standard WindUI-based interface — click, drag, or select to apply changes in real time.

---

## 🧱 UI Overview

Eclipse Hub structures its interface using WindUI's element system:

```
Eclipse Hub
│
├── Window (Draggable / Resizable)
│   ├── Tab: Main
│   │   ├── Toggle
│   │   ├── Slider
│   │   └── Button
│   ├── Tab: Settings
│   │   ├── Dropdown (Theme)
│   │   └── Keybind Selector
│   └── Tab: Config
│       ├── Save Config
│       ├── Load Config
│       └── Reset Config
```

All UI elements are rendered natively through WindUI, ensuring consistent styling and animation across every tab.

---

## ⚙️ Configuration & Settings

Eclipse Hub supports persistent configuration files so your setup stays exactly how you left it:

| Action | Description |
|---|---|
| **Save Config** | Stores your current toggle/slider state to a local config file |
| **Load Config** | Restores a previously saved configuration |
| **Auto Load** | Optionally load your last-used config automatically on script start |
| **Reset Config** | Wipes settings back to default |

---

## 🗺️ Roadmap

- [x] Core WindUI integration
- [x] Full support for Examination
- [ ] Additional theme presets
- [ ] Expanded config profiles (multiple save slots)
- [ ] Support for additional games (TBD)
- [ ] Discord webhook integration for logs/notifications

---

## 📝 Changelog

### v1.0.0 — Initial Release
- 🎉 Initial public release of Eclipse Hub
- ✅ Full WindUI interface integration
- ✅ Examination support added
- 💾 Config save/load system implemented

---

## ❓ FAQ

**Q: Is Eclipse Hub free to use?**
A: Yes, Eclipse Hub is free and open for the community.

**Q: Why does Eclipse Hub only support one game right now?**
A: The focus is on delivering a stable, deeply-tested experience for Examination before expanding to additional games.

**Q: Does Eclipse Hub work on mobile executors?**
A: This depends entirely on whether your executor supports WindUI's rendering requirements. Check WindUI's own compatibility notes for details.

**Q: Can I request a new game to be supported?**
A: Yes — open an issue in this repository with the game name and details, and it may be considered for a future update.

---

## 🩹 Troubleshooting

| Issue | Possible Fix |
|---|---|
| UI doesn't appear after running the script | Confirm your executor supports `loadstring` + `HttpGet`, and that the game is fully loaded |
| Script errors on execution | Make sure you're using an up-to-date executor version |
| Config doesn't save | Verify your executor has file-system read/write permissions enabled |
| UI looks visually broken | Ensure WindUI dependencies are loading correctly (check console/output for errors) |

---

## 🙌 Credits

- **[WindUI](https://github.com/Footagesus/WindUI)** by [Footagesus](https://github.com/Footagesus) — the UI framework powering Eclipse Hub's entire interface
- **Eclipse Hub Development Team** — script logic, feature design, and Examination integration
- The Roblox scripting community for continued tools, testing, and feedback

---

## 🤝 Contributing

Contributions, bug reports, and feature suggestions are welcome!

1. Fork this repository
2. Create a new branch (`git checkout -b feature/your-feature`)
3. Commit your changes (`git commit -m "Add your feature"`)
4. Push to the branch (`git push origin feature/your-feature`)
5. Open a Pull Request

---

## ⚠️ Disclaimer

Eclipse Hub is provided **as-is**, for educational and personal-use purposes. Use of third-party scripts/executors may violate the Terms of Service of the games or platform you use them on, and can carry risks including account moderation. The developers of Eclipse Hub are not responsible for any consequences resulting from its use. Use at your own discretion and risk.

---

## 📄 License

**All Rights Reserved.**

This project and all of its associated files, source code, and assets are proprietary. No part of Eclipse Hub may be copied, modified, redistributed, or used in derivative works without explicit written permission from the owner(s).

---

<div align="center">

Made with ⚡ using [WindUI](https://github.com/Footagesus/WindUI)

</div>
