<h1 align="center">Kuu</h1>

<p align="center">
  A small native macOS terminal. Real login shells on a Metal surface, tabs, color themes, and settings in one config file.
</p>

<p align="center">
  <a href="https://github.com/tretten/kuu/releases/latest/download/Kuu-macos.zip">Download Kuu for macOS</a>
</p>

## Features

- Real PTY login shells through the Ghostty Metal renderer.
- Windows and tabs (⌘N / ⌘T / ⌘W), with scroll arrows when tabs overflow and an optional full-height vertical tab rail.
- Tab titles show the running command with a directory prefix. Closing a tab with a running process asks for confirmation first.
- Color themes from the GhosttyTheme catalog, in light and dark.
- Font family, size, weight, and line height, plus per-tab zoom (⌘+, ⌘−, ⌘0).
- Find in scrollback with ⌘F; terminal links open in your browser.
- Window padding, starting position, and character-grid size.
- Settings live in a plain file at ~/.config/kuu/config.yml. Edit it by hand and press ⌘⇧, to reload.

## Privacy

Kuu runs entirely on your Mac, with no account and no telemetry. The only connection it makes is the automatic update check (Sparkle).

## Install

No public builds are published yet. Once the first release is out, two options will work.

Homebrew (recommended):

```bash
brew tap tretten/kuu
brew install --cask kuu
```

The cask clears the quarantine flag automatically.

Manual install: download Kuu-macos.zip from [Releases](https://github.com/tretten/kuu/releases), move Kuu.app to Applications, then right-click it and choose Open once. The app is self-signed rather than notarized, so Gatekeeper stops the first launch until you do.

Requires macOS 15.6 or later.

---

This repository holds only signed release builds (ZIP) for the auto-update feed. It does not contain source code.
