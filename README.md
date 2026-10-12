# ModEngine

<p align="center">
  <strong>Game Tools, Reimagined.</strong>
</p>

<p align="center">
  A Windows application for game memory inspection and modification, built with Python.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/version-1.0.0-6366f1?style=for-the-badge" alt="Version 1.0.0">
  <img src="https://img.shields.io/badge/platform-Windows-0078D4?style=for-the-badge&logo=windows&logoColor=white" alt="Windows">
  <img src="https://img.shields.io/badge/language-Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/license-MIT-green?style=for-the-badge" alt="MIT License">
  <img src="https://img.shields.io/badge/status-In%20Development-orange?style=for-the-badge" alt="In Development">
</p>

---

## Overview

**ModEngine** is a Windows desktop application designed for inspecting and modifying the memory of compatible games and processes.

Built with Python and PySide6, ModEngine aims to provide a modern dark interface, memory-scanning tools, address management, and an extensible foundation for future features.

The project is currently in development. Some features are incomplete or planned for future releases.

## Features

### Current Foundation

* Modern dark-themed interface
* Process selection
* Memory scan controls
* Results table layout
* Address list interface
* Modular application design

### Planned Features

* [ ] First Scan and Next Scan
* [ ] Exact-value scanning
* [ ] Unknown initial value scanning
* [ ] Increased and decreased value filtering
* [ ] Memory address inspection
* [ ] Memory value editing
* [ ] Address list management
* [ ] Scan history and session management
* [ ] Pointer scanning
* [ ] Plugin support
* [ ] Game compatibility integrations
* [ ] Export and import of scan results
* [ ] Standalone Windows executable

Features will be marked as complete as they are implemented and tested.

## Technology

* **Python** — application logic
* **PySide6** — graphical interface
* **psutil** — process enumeration
* **pymem** — optional process-memory functionality
* **pytest** — automated testing
* **PyInstaller** — executable packaging

## Compatibility

ModEngine is being developed for Windows. Compatibility depends on the target game, process architecture, permissions, operating-system restrictions, and implemented functionality.

**Important:** Using memory inspection or modification tools in games protected by anti-cheat software may trigger security detections and result in a temporary or permanent account ban. Even running a tool may violate a game's rules. Check the game's policies before using ModEngine, especially in online or competitive games.

ModEngine does not guarantee compatibility with every game or protection system.

## Getting Started

### Requirements

* Windows 10 or Windows 11
* A compatible Python installation
* Git, if cloning the repository

### Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/ModEngine.git
cd ModEngine
```

Replace `YOUR_USERNAME` with your GitHub username.

### Install Dependencies

```bash
python -m venv .venv
.venv\Scripts\activate
python -m pip install --upgrade pip
pip install -r requirements.txt
```

### Run the Application

```bash
python main.py
```

Some functionality may not be available until further development is completed.

## Building

ModEngine can be packaged as a Windows executable using PyInstaller.

Install PyInstaller:

```bash
python -m pip install pyinstaller
```

Build the application:

```bash
python -m PyInstaller --noconfirm --clean --windowed --name ModEngine main.py
```

Test the generated executable before distributing it. Additional configuration may be required for resources or dependencies.

## Roadmap

* [x] Initial graphical interface
* [x] Process selection interface
* [ ] Functional memory-scanning engine
* [ ] Address management
* [ ] Session management
* [ ] Plugin system
* [ ] Improved compatibility
* [ ] Windows release builds

## Contributing

Contributions, suggestions, and bug reports are welcome.

Please test changes where possible, keep contributions focused, and update documentation when functionality changes.

Do not include passwords, private tokens, or other sensitive information in issues or pull requests.

## Disclaimer

ModEngine is provided for educational purposes, software development, debugging, and authorized experimentation.

You are responsible for ensuring that your use complies with applicable laws, software licenses, and game rules. Memory modification can cause crashes, unexpected behavior, or data loss. Using ModEngine with protected games may result in anti-cheat detections and account bans.

ModEngine is not affiliated with, endorsed by, or officially associated with any game developer or publisher unless explicitly stated.

## License

ModEngine is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.

---

<p align="center">
  <strong>ModEngine 1.0.0</strong>
  <br>
  Built for experimentation. Designed for extensibility.
</p>
