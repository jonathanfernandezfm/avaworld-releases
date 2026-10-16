# Avaworld

Avalon road companion for Albion Online: live zone tracking, roam map, loot and
dragon portal tracking. Windows only.

This repository hosts the official installers and update feed. The source code is
private.

## Install

1. Download `Avaworld_<version>_x64-setup.exe` from the
   [latest release](https://github.com/jonathanfernandezfm/avaworld-releases/releases/latest)
   and run it. It installs for the current user only; no administrator rights needed.
   Installed copies check for a new version at startup and offer to update.
2. The installer is not code-signed yet, so Windows SmartScreen may warn about an
   unrecognized app. Choose *More info*, then *Run anyway*.
3. Install [Npcap](https://npcap.com/#download) for live capture. Keep the default
   options; "Restrict Npcap driver's access to Administrators only" forces you to
   run Avaworld as administrator.
4. Map tooltip reading (OCR) uses the Windows OCR engine. It works best with the
   Spanish (es-ES) OCR language pack and otherwise falls back to your Windows
   display languages (Settings → Time & language → Language & region → add a
   language with the optical character recognition feature).

## Privacy

Live capture is passive, local and read-only: Avaworld listens to the game's own
UDP traffic through Npcap and never injects or modifies anything.

## License

Copyright (c) 2026 Jonathan Fernandez Mertanen. All rights reserved. The
installers may be used free of charge as distributed here.
