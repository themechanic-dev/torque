# Changelog

All notable changes to **Torque** are listed here. Torque updates itself automatically — on Windows silently in the background, on Linux through your system's package manager, and on Android by offering the new version for you to confirm.

The latest version is always at **[themechanic.store](https://themechanic.store)**.

---

## v2.1.0 — 20 Oct 2026
- 🎨 **A whole new look** — cleaner icons, a single toolbar row, a new home page, and one box for addresses, searches, questions and commands. Press Ctrl+K to reach any action by typing.
- 🌍 **Translate whole pages** — any page in another language turns into yours in place, starting with what's on screen. One click brings the original back.
- 🕰️ **History that understands you** — ask "what was I reading yesterday about electric cars?" and Torque finds it, tells you when, and opens or reads it to you. 90 days, with a short preview of each page.
- 📺 **Picture-in-picture** — keep a video playing in a small floating window while you browse.
- 🖱️ **Right-click menus** — open links in a new or private tab, and ask Torque about any link or image.
- ↩️ **Reopen closed tabs** — Undo, Ctrl+Shift+T, or just say "reopen what I closed".
- 🗂️ **Find any tab by voice** — "go to the YouTube tab", "close the news tab".
- 🎙️ **Voice everywhere** — sites with a microphone button now hear you through Torque, and articles are read aloud with each sentence highlighted.
- 👀 **See what the assistant is doing** — step-by-step cards and a Stop button, and it checks what actually loaded instead of guessing.
- 🧠 **Claude Opus 5.5, Sonnet 5.5 and Haiku 5.5** are now available in Settings.
- 🛟 **Sturdier** — a crashing page no longer takes Torque down, and a page that doesn't open tells you why, with a Try again button.
- 🔊 **Natural voices are back**, with a faster first word.
- 🧹 **Dozens of fixes from hands-on testing on Windows and Linux** — typing always works after a confirmation, Esc closes panels, the address bar updates instantly, and new tabs open your start page.

## Android 1.1.0 — 20 Oct 2026
- 🎨 **The new look comes to your phone** — page translation, history that understands you and finding tabs by voice, just like on desktop.
- 📺 **Real fullscreen video** — it fills the screen and turns sideways, and pressing Home keeps it playing in a small floating window.
- ✍️ **Easier typing** — tapping the address bar simply selects it and opens the keyboard, no copy/paste popup in the way.
- ⏰ **Routines you can count on** — they wake the phone on Android 16 even when Torque was closed, and the lock screen shows just the page and the slide-to-stop bar.
- 🔁 **Hands-free that stays on**, and faster replies.

## Android 1.0.2 — 30 Jul 2026
- ⏰ **Spin a dial to set a routine's time** — hours, minutes, AM/PM, instead of nudging a tiny three-segment stepper that never raised a keyboard. It also says AM/PM in the language you chose, rather than the one your phone happens to be set to.

## Android 1.0.1 — 29 Jul 2026
- 📱 **Torque on Android** — the same browser, now on your phone: your voice, your bookmarks, your saved passwords, your routines. Android 8.0 or newer.
- ⏰ **Routines wake the phone** — when one is due, Torque turns the screen on by itself and shows the page over the lock screen, alarm-clock style. The phone stays locked underneath.

## v2.0.14 — 29 Jul 2026
- 🧠 **Claude Opus 5** — the newest and most capable Claude model is now available, and is the first choice in the model list.
- 🎨 **Light theme** — a proper daylight look with crisp dark controls, alongside the existing dark themes.
- 🔐 **Password autofill, rewritten** — it now fills sites built with React, skips hidden decoy fields, handles two-step logins like Google, and will never put a saved password into a site it was not saved for.
- 🛡️ **Honest VPN indicator** — "connecting" is now amber. Green means you are actually protected, nothing else.
- 🚪 **Sign out really signs you out** — the app locks immediately instead of staying usable until the next restart.
- 🔎 **Web search fix** — a search could quietly return the contents of another open tab instead of the result. It no longer can.
- ⏱️ **Routines** — one that gets stuck now gives up after a few minutes instead of blocking every routine after it.
- 🎯 **Polish** — bigger, easier-to-hit ‹ › ⟳ buttons, and the save/fill bars wrap instead of pushing their buttons off-screen in narrow windows.

## v2.0.13 — 21 Jul 2026
- 📂 **Open local files** — open a PDF or image straight from your computer with the new Open-file button, or by pasting its path in the address bar.
- 🖱️ **"Open with" Torque** — right-click any PDF or image on your disk → *Open with* → **Torque**, and it opens directly in the browser (Windows & Linux).

## v2.0.12 — 20 Jul 2026
- 📄 **Read PDFs** — open a PDF and ask Torque to read or summarise it. It understands both the text **and** scanned/image pages, and answers you right in the chat.
- 🖼️ **Export PDF to images** — turn any open PDF into high-resolution **PNG** images (one per page), saved to your computer, with live progress in the downloads panel.

## v2.0.11 — 19 Jul 2026
- 🛡️ New tray icon — Torque now sits in your system tray (bottom-right on Windows, top-right on Ubuntu). Hover or click to see at a glance whether the VPN is protecting all your traffic, plus live upload and download speed.
- 🐧 Linux: fixed a launch failure where the app could close immediately right after installing the `.deb` on some systems. Fresh installs and updates now start reliably.
- 🔧 More dependable crash reports on Linux, so real issues reach us and get fixed faster.

## v2.0.10 — 19 Jul 2026
- 🔒 VPN IPv6 leak protection — while connected, IPv6 traffic can no longer slip outside the tunnel, so your whole connection stays private.
- 📦 Linux: installing the `.deb` now registers the update channel automatically — install once and get every future update through your system, like any other app.
- 📐 Roomier settings window so every tab (including Backup) is easy to reach.

## v2.0.9 — 18 Jul 2026
- 🔐 Backup & Restore — save an encrypted backup of your bookmarks, saved passwords, API key, VPN connections and browsing history in a single file, then restore it here or on another computer. Locked with your master password.
- 🐧 Correct "start on login" wording on Linux, plus small cross-platform polish.

## v2.0.8 — 17 Jul 2026
- 🐧 Torque is now on Linux — install on Ubuntu/Debian from a single `.deb` (double-click) or one apt command. Same voice, VPN, downloads and ad-blocking as on Windows.
- 🔒 Local device access — pages on your own network (routers, NAS, home servers that use a self-signed certificate) now open instead of showing a blank page. Public sites stay strictly validated.
- ⚡ Faster voice — speech recognition now uses all your CPU cores, and your graphics card automatically when one is available.

## v2.0.7 — 15 Jul 2026
- 📈 Trade position analysis — ask Torque to analyze your open position and it estimates the odds of reaching your target versus your stop, reading your live chart without ever navigating away from it.
- 🎲 Prediction-market analysis — on markets like Polymarket, Torque reads the implied odds and estimates your win probability. Any extra research happens quietly in the background, so your page never changes.

## v2.0.6 — 15 Jul 2026
- 🌍 English everywhere — every button tooltip, the tools menu, the start page and all remaining labels now switch fully to English.
- 🧹 New "clear conversation" button in the chat — wipe the chat history in one click.
- ♿ Accessibility page — highlighting hands-free and read-aloud use for mobility and visual impairments.

## v2.0.5 — 14 Jul 2026
- 🌍 Fully translated interface — with English selected, every screen (VPN, Routines, Account, dialogs) now shows in English.
- 🔊 New Sound settings — pick your microphone, speaker/headset (incl. Bluetooth) and camera, with a live mic level meter and camera preview. Makes messengers like Facebook Messenger work.

## v2.0.4 — 13 Jul 2026
- 🛡️ Self-healing data protection — automatic backups & recovery keep your API keys, saved passwords and favorites safe, even after a crash or power loss.
- 🐞 Built-in crash reporter, so problems get spotted and fixed fast.
- 🔄 A crashed tab now reloads on its own — a heavy page (video, social) no longer takes down the whole browser.

## v2.0.3 — 11 Jul 2026
- 🔒 Rock-solid reliability — the browser can no longer lose your data when restarting or updating.
- 🔌 AI on/off switch — pause all AI to save tokens without deleting your routines.
- 🖥️ Redesigned full-screen mode — sleek floating panels (tools on top, chat on the right, favorites on the left).
- 🔄 Gentler updates that install when you close the app.

## v2.0.2 — 11 Jul 2026
- ⬇️ Real download manager — progress bar, open file, open folder.
- 🖥️ Immersive full-screen: move your mouse to the edges to reveal tools, chat, or favorites.
- 📷 Choose where screenshots are saved.
- 🕘 History upgrades — search, delete by time range, clear-on-exit, and a private tab.

## v2.0.1 — 10 Jul 2026
- 🔄 Automatic, silent updates — always stay on the latest version.
- 👤 Account sign-in inside the app.
- 🇬🇧 English interface by default.
- 🐛 Fixed the first-run voice-model download & added a Retry button.

## v2.0.0 — 10 Jul 2026
- 🎉 First public release — the voice-first AI browser.
- 🎙️ Hands-free voice control, 🤖 AI that browses & acts, 🛡️ ad/tracker blocker, 🔐 built-in VPN, 🔑 local password vault, 🎧 read-aloud, 📖 reader mode, 🔎 search across tabs.
