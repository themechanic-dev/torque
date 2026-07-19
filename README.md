<div align="center">

<img src="assets/icon.png" width="112" alt="Torque">

# Torque

### The browser you talk to.

**A voice-first AI browser for Windows and Linux.** Browse hands-free, ask an assistant that actually reads and acts on the page, and stay private behind a built-in VPN, ad blocker and encrypted password vault.

Your voice is transcribed **on your own computer** — it never goes to a cloud service.

<br>

![Windows](https://img.shields.io/badge/Windows-10%20%2F%2011-0078D6?style=for-the-badge&logo=windows&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-Ubuntu%20%2F%20Debian-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)
![Version](https://img.shields.io/badge/version-2.0.11-3AA0FF?style=for-the-badge)
![Price](https://img.shields.io/badge/free%20while%20we%20grow-1DC98C?style=for-the-badge)

<br>

### [⬇ Download Torque](https://themechanic.store) · [What's new](https://themechanic.store/#changelog) · [Support](mailto:support@themechanic.store)

</div>

---

## Why Torque

Most browsers make you click. Torque lets you **talk**.

Say what you want and it opens the site, finds the thing, reads the page back to you, or summarises it — without you touching the mouse. Underneath it's a full, modern browser: tabs, bookmarks, downloads, history, reader mode. On top of it sits an assistant that can genuinely *use* the page you are looking at.

And it is built to respect you: speech recognition and speech synthesis run **locally on your machine**, you connect **your own AI key**, and there is **no subscription**.

---

## ✨ What it does

### 🎙️ Voice-first, hands-free
- Talk naturally — Torque listens and acts: open sites, search, scroll, go back, summarise.
- **Speech recognition runs on your computer**, accelerated by your graphics card when one is available.
- Spoken replies, so you can keep your eyes (and hands) somewhere else.

### 🧠 An assistant that actually does things
- Reads the page you are on and answers questions about it.
- Opens tabs, navigates, summarises long articles, takes screenshots.
- **Chat with your open tabs** — ask across everything you have open.
- **Routines** — save a multi-step task once, then trigger it whenever you like.

### 📈 Built for people who watch markets
- **Position analysis** — Torque reads your live chart and estimates the odds of reaching your target versus your stop, **without ever navigating away from the chart you are watching**.
- **Prediction markets** — on markets like Polymarket it reads the implied odds and estimates your win probability. Any extra research happens quietly in the background, so your page never changes.
- Paper-trading and Pine-script helpers for TradingView.

> These are estimates and research aids — not investment advice. Torque never places, confirms or cancels an order for you.

### 🔒 Privacy and protection, built in
- **VPN** (OpenVPN) — routes **all** your traffic through the country you choose, with IPv6 leak protection so nothing slips outside the tunnel.
- **Tray icon** — one glance tells you whether the VPN is actually protecting you, plus live upload/download speed.
- **Ad & tracker blocker** on by default.
- **Private tabs** that leave no history behind.
- **Password vault** — your logins encrypted behind a single master password.

### 💾 Your data, and it travels with you
- **Encrypted backup file** containing your bookmarks, saved passwords, API key, VPN connections *(including their certificates)* and browsing history.
- Restore it on another computer — **even a different operating system**. A backup made on Windows restores onto Linux, VPN connections included.
- Locked with the same master password you already use. Quiet automatic local backups protect you from crashes too.

### 🧰 Everything you expect from a browser
- Download manager with live progress, open-file and open-folder.
- History with search and delete-by-time-range, plus optional clear-on-exit.
- **Immersive fullscreen** where the toolbar, chat and favourites glide in from the screen edges.
- Reader mode and read-aloud.
- Screenshots saved to a folder you choose.
- Pick your microphone, speaker and camera — Bluetooth headsets included.

---

## ♿ Accessibility

Torque was built so that a browser can be used **without a mouse, a keyboard, or clear eyesight**.

- **Motor impairments** — full hands-free control. Speaking is enough to browse, search, read and navigate.
- **Visual impairments** — read-aloud and reader mode turn any page into clear spoken audio.
- **On-device processing** — because speech is handled locally, using your voice does not mean handing it to a cloud service.

Accessibility here is not a checkbox. It is one of the reasons the product exists.

---

## 🔑 Your AI, your key, your control

Torque connects to Claude using **your own Anthropic API key**, which you paste into Settings. That means:

- You see exactly what you use and what it costs — nothing is hidden behind us.
- Your conversations go straight from your machine to the AI provider.
- **Torque itself is free while we grow.** Later it becomes pay-once — **never a subscription**.

---

## 📦 Install

### 🪟 Windows 10 / 11 (64-bit)

1. Download from **[themechanic.store](https://themechanic.store/download?os=win)**
2. Run `Torque Setup ….exe` and follow the installer.

Updates are automatic and silent — Torque updates itself in the background and installs on the next restart.

### 🐧 Linux (Ubuntu / Debian, amd64)

**Option 1 — `.deb` (simplest)**

Download from **[themechanic.store](https://themechanic.store/download?os=linux)**, then double-click the file and press *Install* — or run it from your Downloads folder:

```bash
sudo apt install ./torque_*.deb
```

Installing the `.deb` also registers Torque's update channel, so future updates arrive through your system like any other app.

**Option 2 — apt (terminal)**

```bash
wget -qO- https://themechanic.store/apt/torque.gpg | sudo tee /usr/share/keyrings/torque.gpg >/dev/null
echo "deb [signed-by=/usr/share/keyrings/torque.gpg] https://themechanic.store/apt ./" | sudo tee /etc/apt/sources.list.d/torque.list
sudo apt update && sudo apt install -y torque
```

**Updating (either option)**

```bash
sudo apt update && sudo apt upgrade
```

> Packages are signed with our GPG key, so `apt` verifies every update before installing it.

---

## 🖥️ Requirements

| | |
|---|---|
| **Windows** | Windows 10 or 11, 64-bit |
| **Linux** | Ubuntu / Debian, amd64 |
| **AI features** | Your own Anthropic API key |
| **Voice** | A microphone. A GPU is optional — it just makes recognition faster. |

*macOS is not available yet.*

---

## 💬 Support

Questions, bug reports or ideas — we read everything.

- 🤖 The **AI assistant** on [themechanic.store](https://themechanic.store) answers install and setup questions instantly.
- ✉️ **[support@themechanic.store](mailto:support@themechanic.store)**

---

<div align="center">

**Torque** — built by [The Mechanic](https://themechanic.store)

© 2026 The Mechanic. All rights reserved.

*This repository is the public home of the Torque project: what it is, what it does, and how to get it.
Torque is proprietary software — its source code is not distributed here.*

</div>
