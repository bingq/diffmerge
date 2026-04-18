# DiffMerge

A native macOS file comparison and merge tool, inspired by WinMerge. Compare two text files side-by-side and merge changes with keyboard-driven efficiency.

**This repository contains user-facing documentation only.** The DiffMerge source code is proprietary and not published here.

## Download

DiffMerge is available on the Mac App Store.

<!-- TODO: replace with real App Store URL once live -->
[![Download on the Mac App Store](https://developer.apple.com/assets/elements/badges/download-on-the-mac-app-store.svg)](https://apps.apple.com/app/idTODO)

## Features

- **Side-by-side diff view** with inline character-level highlighting
- **Real-time scroll synchronization** across all three panes
- **Keyboard-driven merge workflow** — ⌘←, ⌘→, ⌘↑, ⌘↓
- **Location overview map** (WinMerge-style) to jump between changes
- **Broad file-type support** — plaintext, TypeScript, JavaScript, Swift, Python, Java, C/C++, JSON, XML, HTML, CSS, Markdown, and more
- **Fully sandboxed** — no network access, files never leave your Mac
- **Native SwiftUI** — not Electron, not Wine, not a web view

## System Requirements

- macOS 14.0 or later
- Apple Silicon or Intel Mac

## Privacy

DiffMerge collects no data. Files you open stay on your Mac. See the full [Privacy Policy](PRIVACY.md).

## Support

For bug reports, feature requests, or questions, see [SUPPORT.md](SUPPORT.md).

## Version History

### v0.5 — December 2025
- Real-time scroll synchronization across all three panes
- Expanded file-type support (TypeScript, JavaScript, Swift, Python, Java, C/C++, JSON, XML, HTML, CSS, Markdown)
- Files display immediately on load
- Performance improvements for file loading

### v0.3 — August 2025
- Initial Mac App Store release

## Roadmap

Planned for future releases:
- Accept Both (merge both sides into result) — unique to DiffMerge
- Change heatmap navigation
- Recent file pairs / fuzzy open (⌘P)
- Undo/redo for merge operations
- Preferences (colors, fonts, shortcuts)
- 3-way merge
- Folder / directory diff
- Git integration
- Syntax-aware diff
- Export diff report (HTML/PDF)
- Command-line interface

## License

See [LICENSE](LICENSE).

---

DiffMerge — making file comparison simple and efficient on macOS.
