# ⚡ CleanMaster Pro

> A CCleaner-inspired system cleaner built as a single-file web app — dark futuristic UI, fully interactive, zero dependencies.

![HTML](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![No Dependencies](https://img.shields.io/badge/dependencies-none-brightgreen?style=flat-square)
![Single File](https://img.shields.io/badge/single--file-yes-00c8ff?style=flat-square)

---

## 📸 Preview

The app features a dark futuristic aesthetic with a two-column layout: a fixed sidebar navigator on the left and a dynamic main panel on the right. Real-time animated scan progress, interactive checkboxes, disk usage visualizations, and toast notifications make it feel like a production desktop utility.

---

## ✨ Features

### 🧹 Cleaner
- Detects and lists junk categories: Windows temp files, system logs, browser caches (Chrome, Firefox, Edge), Teams cache, and more
- Individual checkboxes per category — enable/disable what gets cleaned
- Animated **Analyze** flow with step-by-step progress bar and live status messages
- Animated **Clean Now** flow that updates space counters in real time
- Activity log panel that records every operation with timestamps

### 🗃️ Registry
- Lists simulated Windows Registry issues: orphan keys, invalid DLL references, broken paths, obsolete services, invalid ActiveX entries
- Select individual entries and fix them with one click
- Live feedback — fixed entries fade out visually

### 🚀 Startup Manager
- Shows all programs that launch at Windows startup
- Impact rating per program: **High / Medium / Low**
- Toggle switches to enable or disable startup entries

### 🔧 Tools
Six tool cards with descriptions:
- **Uninstaller** — deep removal including leftover files and registry entries
- **Duplicate Finder** — content-based duplicate detection
- **Secure Erase** — multi-pass overwrite (DoD 5220.22-M)
- **System Restore** — manage and remove restore points
- **Driver Manager** — detect outdated or broken drivers
- **Privacy Protector** — wipe activity traces and Windows telemetry

### ❤️ System Health
- Real-time-style dashboard: CPU usage, RAM usage, CPU temperature, overall health score
- Disk usage bar chart segmented by category: System, Temp, Apps, User, Free
- Color-coded legend

### 💾 Disk Analyzer
- Lists the largest folders on the system drive
- Highlights folders using abnormal amounts of space

---

## 🚀 Getting Started

No install. No build step. No dependencies.

```bash
git clone https://github.com/your-username/cleanmaster-pro.git
cd cleanmaster-pro
```

Then open `CleanMaster.html` in any modern browser:

```bash
# macOS
open CleanMaster.html

# Linux
xdg-open CleanMaster.html

# Windows
start CleanMaster.html
```

That's it.

---

## 🗂️ Project Structure

```
cleanmaster-pro/
└── CleanMaster.html     # Entire app — HTML + CSS + JS in one file
└── README.md
```

Everything lives in a single self-contained file. No frameworks, no bundlers, no node_modules.

---

## 🎨 Design System

| Token | Value | Usage |
|---|---|---|
| `--bg` | `#0a0d14` | Page background |
| `--surface` | `#111520` | Cards and sidebar |
| `--accent` | `#00c8ff` | Primary highlight, active states |
| `--accent2` | `#0077ff` | Gradient pair |
| `--green` | `#00e5a0` | Success, low impact |
| `--yellow` | `#ffd600` | Warnings, medium impact |
| `--red` | `#ff4757` | Errors, high impact, found items |

**Fonts:** [Rajdhani](https://fonts.google.com/specimen/Rajdhani) (headings, values) · [Inter](https://fonts.google.com/specimen/Inter) (body, labels)

**Effects:** CSS scanline overlay · animated spinning ring · glowing progress bar · staggered log entries · spring toast notifications

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Structure | Semantic HTML5 |
| Styling | Vanilla CSS3 (CSS variables, Grid, Flexbox, animations) |
| Logic | Vanilla JavaScript (ES6+) |
| Fonts | Google Fonts (loaded via CDN) |
| Icons | Unicode emoji |

No libraries. No frameworks. No build tools required.

---

## 🔮 Roadmap / Possible Extensions

- [ ] Connect to a local Node.js or Python backend for real system data
- [ ] Electron wrapper for a true desktop experience
- [ ] Tauri port for a lightweight native binary
- [ ] Chart.js integration for animated disk usage graphs
- [ ] Dark/Light theme toggle
- [ ] Internationalization (i18n) support
- [ ] Persist startup toggle states via localStorage

---

## 📄 License

MIT License — free to use, modify, and distribute.

---

## 🙌 Acknowledgements

Inspired by [CCleaner](https://www.ccleaner.com/) by Piriform. This is a UI/UX demo project and does not perform any real system operations.

---

<p align="center">Built with ⚡ and pure HTML/CSS/JS · No frameworks were harmed</p>
