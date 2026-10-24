# The Warriors Recomp

A native PC static recompilation of the **original Xbox version of The Warriors** (Rockstar, 2005). Work in progress.

## Status
- Game executable unpacked and fully analysed in Ghidra (XBE loader, x86).
- Export and recompilation tooling in progress.

## Goals
- Runs natively on modern PC, no emulator.
- Online play built on the original local multiplayer.
- Upscaled textures and UI.
- PS5, Xbox and Switch controller support with matching button icons.
- A launcher that points at your own game image.
- Full graphics settings menu: render resolution scaling (3x native and beyond), widescreen, anti-aliasing, frame rate options.
- Texture and asset replacement system: AI-upscaled textures, UI and assets loaded at runtime as optional packs (dump-and-replace, never shipping original files).

## Legal
No game files, code or assets from the original game are included in this repo. You must supply your own legally owned copy.

## Want to help?
Reverse engineers, Xbox/x86 folks, graphics and netcode people are all welcome. Open an issue to say hi and what you'd like to work on.
