---
title: EmulatorJS Player
description: Information about EmulatorJS, the web-based emulator
---
[EmulatorJS](https://emulatorjs.org/) is a web-based emulator for various system; that is, it allows you to run old games in your web browser. It's based on [Emscripten](https://emscripten.org/), which is a toolchain for compiling C and C++ code to WebAssembly.

!!! warning
    Due to a [change by Apple in iOS 18.2](https://bugs.webkit.org/show_bug.cgi?id=284752), emulation is severely limited, and likely non-functional, on iOS devices.

!!! warning
    PSP emulation with the PPSSPP core requires [special setup with a reverse proxy](https://emulatorjs.org/docs/options#ejs_threads), or launching Chrome browser with the `--disable-web-security` and `--enable-features=SharedArrayBuffer` flags, which WE STRONGLY DISCOURAGE as it disables important security features.

!!! warning
    Emulation is a complex and resource-intensive process. As such, it may not work well in all browser, especially older or less powerful ones. If you're having trouble running a game, try using a different browser or device.

### Loading saves and states

Our integration with EmulatorJS automates the process of loading and saving save files and save states. Before starting the game, select a save and/or state file to load (if one is available). Anytime you save the game (or create a save state), the save and state files stored with RomM will be updated, so there's no need to manually download or upload them.

### Supported systems

Note that only the following systems are currently supported:

* 3DO
* Amiga
* Arcade/MAME
* Atari 2600
* Atari 5200
* Atari 7800
* Atari Jaguar
* Atari Lynx
* Commodore 64
* ColecoVision
* Neo Geo Pocket
* Neo Geo Pocket Color
* Nintendo 64
* Nintendo Entertainment System (NES)
* Nintendo Family Computer (Famicom)
* Nintendo DS
* Game Boy
* Game Boy Color
* Game Boy Advance
* PC-FX
* PlayStation (PS)
* Sega 32X
* Sega CD
* Sega Game Gear
* Sega Master System
* Sega Genesis/Megadrive
* Sega Saturn
* Super Nintendo Entertainment System (SNES)
* Super Famicom
* TurboGraphx-16/PC Engine
* Virtual Boy
* WonderSwan
* WonderSwan Color
