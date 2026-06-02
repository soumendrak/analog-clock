# Analog Clock

<div align="center">
  <img src="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 100 100' width='64' height='64'%3E%3Ccircle cx='50' cy='50' r='45' fill='%231a1a2e' stroke='%23ff6b35' stroke-width='4'/%3E%3Ccircle cx='50' cy='50' r='3' fill='%23ff6b35'/%3E%3Cline x1='50' y1='50' x2='50' y2='25' stroke='%23ff6b35' stroke-width='4' stroke-linecap='round'/%3E%3Cline x1='50' y1='50' x2='65' y2='50' stroke='%23ff6b35' stroke-width='3' stroke-linecap='round'/%3E%3Cline x1='50' y1='50' x2='50' y2='15' stroke='%23ff6b35' stroke-width='1.5' stroke-linecap='round' opacity='0.7'/%3E%3C/svg%3E" alt="Analog Clock Logo" width="64">

  [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
  [![Zero Dependencies](https://img.shields.io/badge/dependencies-0-success)](package-free)
  [![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-ready-blue)](https://pages.github.com/)
  [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen)](http://makeapullrequest.com)
</div>

A **polished, fully self-contained analog clock** built in a single HTML file — zero dependencies, canvas-rendered, deployable on GitHub Pages.

![Screenshot](https://raw.githubusercontent.com/nousresearch/hermes-agent/main/assets/analog-clock-preview.png)

## ✨ Features

- **Canvas-rendered analog clock** with hour, minute, and second hands
- **Smooth continuous second hand** — no tick-step; sweeps at sub-millisecond precision
- **Three numeral systems** — toggle between Standard (1–12), Roman (I–XII), and Odia (୧–୧୨)
- **Three visual themes** — Dark (default, orange glow), Classic (warm serif), Neon (cyan/pink glow)
- **Digital time display** below the clock face
- **Date display** — day, month, and year with English or Odia names
- **Fullscreen mode** — click or press `F`
- **Responsive** — automatically resizes to fit any viewport
- **Keyboard shortcuts**:
  - `T` — cycle themes
  - `N` — cycle numeral systems
  - `D` — toggle date language
  - `F` — toggle fullscreen

## 🚀 Live Demo

[https://your-username.github.io/analog-clock/](https://your-username.github.io/analog-clock/)

*(Replace with your actual URL after deploying)*

## 🧩 Architecture

```mermaid
flowchart TD
    A["🕐 Analog Clock"] --> B["Numeral Systems"]
    A --> C["Themes"]
    A --> D["Features"]

    B --> B1["Standard 1–12"]
    B --> B2["Roman I–XII"]
    B --> B3["Odia ୧–୧୨"]

    C --> C1["Dark<br/>(default)"]
    C --> C2["Classic"]
    C --> C3["Neon"]

    D --> D1["Smooth Second Hand"]
    D --> D2["Digital Time"]
    D --> D3["Date Display<br/>(EN / Odia)"]
    D --> D4["Fullscreen Mode"]
    D --> D5["Responsive Layout"]
    D --> D6["Keyboard Shortcuts"]
```

## 📁 Usage

1. **Download** the file:
   ```bash
   curl -O https://raw.githubusercontent.com/your-username/analog-clock/main/index.html
   ```
2. **Open** in any modern browser:
   ```bash
   open index.html
   ```
3. **Deploy** to GitHub Pages by pushing `index.html` to the `main` branch of a repo named `analog-clock`.

No build step. No package manager. One file.

## 🎨 Themes

| Theme     | Background | Accent  | Vibe                  |
|-----------|------------|---------|-----------------------|
| **Dark**  | `#0f0f1a`  | Orange  | Modern, moody         |
| **Classic** | `#f5f0e8` | Brown   | Warm, traditional     |
| **Neon**  | `#05050f`  | Cyan/Pink | Cyberpunk, glowing  |

## 🔤 Numeral Systems

| System     | Display                     |
|------------|-----------------------------|
| Standard   | 1 2 3 4 5 6 7 8 9 10 11 12 |
| Roman      | I II III IV V VI VII VIII IX X XI XII |
| Odia       | ୧ ୨ ୩ ୪ ୫ ୬ ୭ ୮ ୯ ୧୦ ୧୧ ୧୨ |

## 📄 License

MIT — see [LICENSE](LICENSE) for details.

---

*Built with ❤️ using vanilla JavaScript and Canvas API.*
