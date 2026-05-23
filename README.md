# Friday Assistant — Project Overview

**Version:** 0.1.0  
**Platform:** Windows 10/11  
**Language:** Python 3.12+ (recommended for voice)

---

## What is Friday?

Friday is a JARVIS / F.R.I.D.A.Y.-inspired personal AI assistant for Windows. It provides:

- Futuristic neon desktop UI (PySide6)
- Voice wake-word control ("Friday")
- Typed command input
- Real-time web search, news, and weather
- Browser control (Chrome, Brave)
- App launching via allowlist
- **Strict safety:** never reads or opens your personal files

---

## Key Features

| Feature | Description |
|---------|-------------|
| Wake word | Say "Friday" to launch or activate the app |
| Background listener | Hears "Friday" even when the window is closed |
| Voice commands | Open apps, sites, search, news, weather, jokes |
| Text commands | Same commands via the command box |
| Policy engine | Blocks all file-system and shell access |
| Installable EXE | Package with PyInstaller |

---

## Repository Structure

```
friday-assistant/
  friday/           Main Python package
  tests/            Unit tests (policy, intents, router)
  docs/             Documentation (Markdown + PDF)
  assets/           Icons and theme assets
  install.bat       Windows setup script
  run.bat           Launch Friday
  build_exe.bat     Build standalone EXE
```

---

## Quick Start

1. Install Python 3.12 from python.org
2. Run `install.bat`
3. Run `run.bat` or double-click **Friday Assistant** on Desktop
4. Run `Enable Friday at Login.bat` for wake-word at startup

---

## License

MIT License — see LICENSE file in the repository root.

