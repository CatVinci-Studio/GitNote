# GitNote Quick

[中文版](./README_ZH.md)

A lightweight Electron desktop app for managing text snippets with zero-cost sync via a private GitHub repository.

## Features

- **Global Shortcut** — `Ctrl+Shift+V` to toggle a floating window, always on top
- **GitHub Sync** — Auto pull/push to private repo, conflict resolution support
- **AES-256 Encryption** — Encrypted storage with PBKDF2 key derivation
- **System Tray** — Quick access, real-time search, snippet management

## Download

Current version: **v1.1.0**

- [Release](https://github.com/CatVinci-Studio/GitNote/releases)

**v1.0.0**

- [Release](https://github.com/Muyiiiii/GitNote/releases/tag/v1)

## Quick Start

```bash
npm install
npm start
```

On first launch, enter your private GitHub repo URL, branch, and PAT (with `repo` scope).

## Build

```bash
npm run build:win   # Windows
npm run build:mac   # macOS
npm run build       # current platform
```

## License

MIT

