# FengXia-Packer

> Write HTML on the go, and package it into a standalone Windows executable (.exe) with one click.

FengXia-Packer bundles your HTML, images, CSS and JavaScript files into a single `.exe` that anyone can just double-click to run. The recipient does **not** need to install Node.js, a browser, or any runtime — everything is packaged in.

---

## ✨ Features

- **One-click packaging** — HTML and all its assets (images, styles, scripts) are packed into a standalone exe.
- **Built-in code editor** — write and edit inside the tool; supports 8 common languages with real-time syntax highlighting and auto-completion.
- **Built on NW.js** — the output app ships with its own Chromium, so it runs the same everywhere on Windows.
- **GUI workflow** — no command line, no build config; just pick your entry file and go.

## 📦 What it's good for

- Sending an HTML game / small tool to a friend — they just double-click to open it.
- Shipping a webpage as a desktop app instead of opening a browser.
- Quick offline demos and showcases.

## 🚀 How to use

1. Open FengXia-Packer.
2. Select your entry file (usually `index.html`).
3. Click package and wait — you'll get a ready-to-share `.exe`.

## ⚠️ About the bundled HTML sample

The demo HTML in this repo is **source code that talks to the editor through a custom in-app bridge (IPC)**. It is **not** meant to be opened directly in a normal browser. If you want to run it outside FengXia-Packer, you must adapt the bridge calls yourself — a plain browser has no access to that bridge.

## 🛠️ Tech stack

- Runtime: [NW.js](https://nwjs.io/)
- Packager: nwjs-packager

## 📄 Disclaimer

This project is for learning and personal use only. Do not package content you do not own or have the right to distribute.

---

<div align="center">

Developed by <b>Fengxia Studio</b> · China

</div>
