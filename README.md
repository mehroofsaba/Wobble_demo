# Wobble

**A tiny desktop companion with a big personality.** 💗

Wobble is a cozy desktop pet you can look after throughout the day. Feed it, play little games, keep it clean, and watch its mood and bond level change as you spend time together.

## What you can do

- **Care for Wobble:** manage hunger, happiness, energy, cleanliness, and boredom.
- **Play together:** try four mini-games — Catch the Stars, Bubble Pop, Memory Match, and Color Splash.
- **Build your bond:** earn experience as you interact and unlock accessories.
- **Make it yours:** dress Wobble up, adjust reminders and sounds, and choose whether it stays on top.
- **Keep a desktop buddy:** use the small companion window alongside the main app.
- **Pick up where you left off:** pet progress and settings are saved locally.

## Getting started

### Requirements

- [Node.js](https://nodejs.org/)
- [Rust](https://www.rust-lang.org/tools/install) (via rustup)
- The [Tauri 2 prerequisites](https://v2.tauri.app/start/prerequisites/) for your operating system
  - On Windows, this includes Microsoft Edge WebView2.

### Run in development

Clone the repository, open its folder in a terminal, then run:

```bash
npm install
npm run dev
```

### Build the desktop app

```bash
npm run build
```

Tauri will create the platform-specific build output.

## Desktop companion

The companion window can be shown or hidden from the app settings. The system-tray menu also provides **Open, Hide, Mute, Settings,** and **Quit**. Closing the main window hides Wobble in the tray.

You can drag the desktop companion to move it; its position is remembered.

## Preview the interface

For a quick look without setting up the Rust toolchain, open `src/index.html` in a browser. The companion layout can be previewed with `src/index.html?c=1`.

The browser preview is for the interface; native desktop features require running the Tauri app.

## Built with

- HTML, CSS, and JavaScript
- [Tauri 2](https://v2.tauri.app/)
- Rust

---

Made with care for anyone who could use a little desktop company. ✨
