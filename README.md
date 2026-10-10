# Aerocept releases

Installers for **Aerocept**, which lets you control your Mac with hand gestures using your webcam.

**Download:** [latest Aerocept.dmg](https://github.com/jathinravilla/aerocept-releases/releases/latest/download/Aerocept.dmg) · Website: https://aerocept.vercel.app

## Install

1. Open `Aerocept.dmg` and drag Aerocept into Applications.
2. The first time, macOS blocks it because this early version isn't notarized by Apple yet. Open **System Settings > Privacy & Security**, scroll down, and click **Open Anyway** next to Aerocept.
3. Allow Camera, Accessibility and Input Monitoring when asked.

Requires macOS 12 or newer on Apple silicon.

Each release lists the installer's SHA-256 so you can check your download:

```bash
shasum -a 256 ~/Downloads/Aerocept.dmg
```

This repository only holds release files. The source code is private.
