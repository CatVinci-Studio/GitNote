# GitNote Quick

一款轻量级 Electron 桌面应用，通过私有 GitHub 仓库同步文本片段。

## 功能特点

- **全局快捷键** — `Ctrl+Shift+V` 唤醒浮动窗口，始终置顶
- **GitHub 同步** — 自动 pull/push 到私有仓库，支持冲突解决
- **AES-256 加密** — PBKDF2 密钥派生的加密存储
- **系统托盘** — 快捷访问，实时搜索，片段管理

## 下载

当前版本：**v1.1.0**

- [发布页](https://github.com/CatVinci-Studio/GitNote/releases)

**v1.0.0**

- [发布页](https://github.com/Muyiiiii/GitNote/releases/tag/v1)

## 快速开始

```bash
npm install
npm start
```

首次启动时，输入你的私有 GitHub 仓库地址、分支和 PAT（需具备 `repo` 权限）。

## 打包构建

```bash
npm run build:win   # Windows
npm run build:mac   # macOS
npm run build       # 当前平台
```

## 许可证

MIT

[English](./README.md)
