# idleboxed

Open-source tools for preparing a retro-gaming setup, organising your own ROM
collection and choosing games in a lightweight menu. The toolkit targets Linux
PCs and Game Stick Lite with the GBX-066-V02 board and RK3032 chip.

- [iroll](https://github.com/idleboxed/iroll) — prepares the build environment,
  builds the software and places it in the target directory.
- [icat](https://github.com/idleboxed/icat) — imports your ROMs and builds a game
  catalogue with metadata and pictures for igui.
- [igui](https://github.com/idleboxed/igui) — the game browser, with search,
  filters, favourites and gamepad controls.
- [iman](https://github.com/idleboxed/iman) — connects the menu to RetroArch,
  manages game sessions and returns to the menu after a game ends.
- [itrampoline](https://github.com/idleboxed/itrampoline) — an experimental
  stock-menu entry for launching iman and igui from SD.
- [imanlib](https://github.com/idleboxed/imanlib) — shared local IPC, display
  and input primitives for the Rust applications.

Device-specific installation requirements are documented in the component
guides; compatibility with every product sold as a game stick is not implied.
Games and BIOS files are not provided.

[Website](https://idleboxed.github.io/) ·
[Build and setup guide](https://github.com/idleboxed/iroll#readme) ·
[Stock-menu entry](https://github.com/idleboxed/itrampoline#readme)
