# <img width="2233" height="264" alt="Python Application Builder" src="https://github.com/user-attachments/assets/e3db44ac-8dc1-40e9-bb25-211973b34dc3" />

Python Application Builder is a lightweight Windows tool built with .NET Framework that lets you convert any Python script into a standalone `.exe` with a single click — no command line required.

## Features

- One-click Python-to-EXE conversion powered by PyInstaller.
- Custom icon support for your generated executable.
- Option to hide the console window for GUI applications.
- UAC admin elevation flag for applications that require it.
- Auto-installs PyInstaller if not already present.
- Clean build mode to remove cached build artifacts.
- Keep-only-EXE mode for a minimal, clutter-free output.
- Automatic update checker with one-click installer.

## Installation

1. Download the latest release from the [Releases](../../releases) page.
2. Run the installer (`PyAppBuilder_Setup.exe`) and follow the instructions.

## Usage

1. Open **Python Application Builder**.
2. Click **Browse** and select your `.py` script.
3. Optionally select a custom `.ico` icon file.
4. Configure build options:
   - **Remove Console** — hides the terminal window (for GUI apps).
   - **Require Admin** — adds a UAC elevation prompt on launch.
   - **Clean Build** — deletes previous build cache before building.
   - **Keep Only EXE** — moves the final `.exe` to your script folder and removes all build artifacts.
5. Click **Build**.
6. Once complete, choose to open the output folder directly.

## System Requirements

- Windows 10 or higher
- .NET Framework 4.7.2 or higher
- Python 3.x installed and available in PATH

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Author

Bentendo © 2026
