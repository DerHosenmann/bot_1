# Zenith Chimera Bot

Zenith Chimera Bot is an automation tool for the game "Rise of Kingdoms". This repository contains the source code and configuration files required to run the bot on Windows with an Android emulator.

## Installation

1. Install [Python 3.11](https://www.python.org/) or newer.
2. Install the dependencies listed in `requirements.txt`:

```bash
pip install -r requirements.txt
```

3. Install ADB (Android Debug Bridge). You can obtain it from the Android SDK Platform Tools.
4. If `adb.exe` is not installed at `C:\platform-tools\adb.exe`, edit `filepath/file_relative_paths.py` and update `ADB_EXE_PATH` to the full path of your `adb.exe`.
5. Ensure your Android emulator is running and has USB debugging enabled.

## Usage

Run the main entry point:

```bash
python main.py
```

The program will open a window titled **Zenith Chimera Bot**. Configure your device and settings using the tabs provided in the interface. When you are ready, start the bot and monitor the output.

## Notes

This project is provided as‑is and carries no guarantees. Use the software responsibly and comply with the terms of service of any game or platform you interact with.
