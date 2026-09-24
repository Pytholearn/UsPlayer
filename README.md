<div align="center">

<img src="assets/banner.svg" alt="Us Player — Watch together, enjoy together" width="100%">

<br>

**Watch the same movie at the same time — with friends, anywhere.**

<br>

<p align="center">
<a href="https://github.com/Pytholearn/UsPlayer/releases/latest"><img src="https://img.shields.io/github/v/release/Pytholearn/UsPlayer?style=for-the-badge&logo=github&label=release&color=2b7fff" alt="Release"></a><!--
--><a href="https://github.com/Pytholearn/UsPlayer/releases"><img src="https://img.shields.io/github/downloads/Pytholearn/UsPlayer/total?style=for-the-badge&logo=windows&label=downloads&color=6a3cff" alt="Downloads"></a><!--
--><a href="#install"><img src="https://img.shields.io/badge/Windows-10%20%7C%2011%20%C2%B7%2064--bit-0078D6?style=for-the-badge&logo=windows11&logoColor=white" alt="Windows 10 and 11"></a><!--
--><a href="LICENSE"><img src="https://img.shields.io/github/license/Pytholearn/UsPlayer?style=for-the-badge&label=license&color=3ee0ff" alt="MIT License"></a>
</p>

<p align="center">
<img src="https://img.shields.io/badge/stack-Python%203.12%20%C2%B7%20PyQt6%20%C2%B7%20libVLC%203.0-1e293b?style=flat-square&logo=python&logoColor=fbbf24" alt="Python, PyQt6, libVLC">
</p>

<p align="center">
<img src="https://img.shields.io/badge/app%20UI-English%20%7C%20%D9%81%D8%A7%D8%B1%D8%B3%DB%8C-2b7fff?style=flat-square" alt="App UI languages">
<img src="https://img.shields.io/badge/docs-EN%20%7C%20%E4%B8%AD%E6%96%87%20%7C%20FA%20%7C%20RU-6a3cff?style=flat-square" alt="Documentation languages">
<img src="https://img.shields.io/badge/telemetry-none-2ea44f?style=flat-square" alt="No telemetry">
<img src="https://img.shields.io/badge/port%20forwarding-not%20needed-2ea44f?style=flat-square" alt="No port forwarding">
</p>

<br>

| | |
| :--: | :--: |
| **Windows** | **Android** |
| [![Download Us Player](https://img.shields.io/badge/Download-Us%20Player-2563eb?style=for-the-badge&logo=windows11&logoColor=white)](https://github.com/Pytholearn/UsPlayer/releases/latest) | [![Get Android app](https://img.shields.io/badge/Get-Android%20app-059669?style=for-the-badge&logo=android&logoColor=white)](https://github.com/Pytholearn/UsPlayer-Android/releases/latest) |
| <sub><code>UsPlayer-Setup.exe</code> · portable <code>UsPlayer-win64.zip</code></sub> | <sub>Same rooms — chat, reactions &amp; voice</sub> |
| <sub><a href="#install">Install guide</a> · SHA-256 on releases</sub> | <sub><a href="https://github.com/Pytholearn/UsPlayer-Android">UsPlayer-Android</a></sub> |

<br>

**Read in your language** (English is the default)

<p align="center">
<a href="README.md"><img src="https://img.shields.io/badge/English-default-2b7fff?style=for-the-badge" alt="English (default)"></a><!--
--><a href="docs/README.zh-CN.md"><img src="https://img.shields.io/badge/%E4%B8%AD%E6%96%87-333?style=for-the-badge" alt="中文"></a><!--
--><a href="docs/README.fa.md"><img src="https://img.shields.io/badge/%D9%81%D8%A7%D8%B1%D8%B3%DB%8C-6a3cff?style=for-the-badge" alt="فارسی"></a><!--
--><a href="docs/README.ru.md"><img src="https://img.shields.io/badge/%D0%A0%D1%83%D1%81%D1%81%D0%BA%D0%B8%D0%B9-0078D6?style=for-the-badge" alt="Русский"></a>
</p>

</div>

---

**Us Player** is a watch-party player for Windows. Host a room with a **name**, invite friends with that same name, and everyone stays in sync — no IP addresses, port forwarding, or router tweaks. When someone pauses, the room pauses. Chat over the video, react with ❤️, and keep your eyes on the movie.

> **Windows + Android:** Friends on phones can join the same room. The [Android app](https://github.com/Pytholearn/UsPlayer-Android) uses the same protocol as the desktop player.

**On this page:** [Features](#features) · [Install](#install) · [Watch together](#watch-together) · [How it works](#how-it-works) · [Privacy](#privacy) · [FAQ](#faq) · [License](#license)

<a id="features"></a>

### ✨ Features

<table>
<tr>
<td width="50%" valign="top">

#### 🎬 Watch party
- **Host or join by room name** — one click, no network setup
- **Shared playback:** play, pause, seek, and speed changes sync for everyone
- **Tight sync** (about ±100 ms) via clock alignment and gentle rate correction
- Optional room **password** — verified on your device, not sent in plain text
- **Host controls:** remove a guest or mute someone’s chat
- **Shared subtitles:** files the host opens are sent to the room, including for late joiners

</td>
<td width="50%" valign="top">

#### 🎙️ Stay connected
- **Voice chat** — push-to-talk or always-on mic with a noise gate; mute anyone individually
- **On-screen chat** — messages fade in along the bottom of the video
- **Live reactions** 👍 ❤️ 😂 😮 🔥 👏
- See who’s in the room, ping, connection quality, and who’s speaking
- Typing indicators and unread message counts

</td>
</tr>
<tr>
<td valign="top">

#### 🔗 Smart links
- Paste a **movie page URL**, not only a direct file link — Us Player resolves `.mp4`, `.mkv`, or `.m3u8` and shows each step
- Chooses the **main movie** at the best quality and skips trailers and clutter
- **Search tab** with curated sites to find what you want to watch
- Fixes broken URLs (including duplicated query parameters) automatically

</td>
<td valign="top">

#### 🎛️ Player
- **0.25×–4×** speed, frame step, chapters, screenshots
- **Mini player** (always on top) and fullscreen with auto-hiding controls
- **Resume playback**, watch history, and favorites
- **Auto-reconnect** when a stream stalls; built-in network diagnostics
- **Subtitles:** delay, size, color, outline, font, plus an **encoding picker** for Persian `.srt` files

</td>
</tr>
<tr>
<td valign="top">

#### 🔊 Audio & video
- Volume up to **300%** with an optional compressor
- **10-band equalizer** with presets, normalization
- Brightness, contrast, saturation, gamma, hue — live
- Aspect, crop, zoom, rotate, mirror, sharpen, deinterlace

</td>
<td valign="top">

#### 💙 Built with care
- **English and Persian** UI with proper right-to-left layout
- Three themes: **Us Blue**, Dark Purple, and Dark Mint
- **First-run tour** in both supported UI languages
- **Automatic updates** with **SHA-256 verification** before install
- **Portable-friendly:** settings and history sit beside the app · **No telemetry**

</td>
</tr>
</table>

<a id="install"></a>

### 📥 Install

1. Download **`UsPlayer-Setup-<version>.exe`** from the [latest release](https://github.com/Pytholearn/UsPlayer/releases/latest).
2. Run the installer — it adds Start Menu shortcuts and an uninstall entry.
3. If Windows shows **“Windows protected your PC — unknown publisher”**, that’s expected until the app is code-signed. Choose **More info → Run anyway**. Every release lists **SHA-256** hashes so you can verify downloads.

**Prefer portable?** Grab **`UsPlayer-win64.zip`**, extract it anywhere, and run **`UsPlayer.exe`** — no installer required.

<a id="watch-together"></a>

### 🍿 Start a watch party in three steps

| Step | Host | Friends |
|:-:|---|---|
| **1** | Open **Party → Host**, pick a room name (optional password) | Open **Party → Join**, enter the same name |
| **2** | Click **Create Room** | Click **Join** |
| **3** | Open a movie from a link | The same movie opens for everyone, in sync |

<a id="how-it-works"></a>

### 🧠 How it works

Your movie **never passes through our servers**. Each person streams video **directly from the source**. Only small control messages — play, pause, seek, chat — plus voice audio go through the relay.

```mermaid
flowchart LR
    H["🎬 Host"] -->|"play · pause · seek · chat · voice"| R(("☁️ Relay"))
    R -->|"synced commands"| F1["💻 Friend on Windows"]
    R -->|"synced commands"| F2["📱 Friend on Android"]
    S[("🌐 Movie source")]
    S -.->|"video"| H
    S -.->|"video"| F1
    S -.->|"video"| F2
```

<a id="privacy"></a>

### 🔒 Privacy & security

- **Room passwords stay on your PC.** Join uses a salted challenge–response; only a proof is sent over the network.
- **Untrusted-by-default messaging.** Room traffic is size-limited, validated, protected against replay, and rate-limited.
- **Local file paths are not shared.** A path on your machine may not exist — or may point elsewhere — on a friend’s PC, so the room pauses and asks for a **link everyone can use**.
- **Verified updates.** Downloads that don’t match the published **SHA-256** are rejected.
- **No telemetry.** We don’t collect or send data about what you watch.

<a id="faq"></a>

### ❓ FAQ

<details>
<summary><b>Do friends need the same Wi‑Fi or an open port?</b></summary>
<br>
No. Rooms are registered by name on the relay, so anyone can join from anywhere using just the room name.
</details>

<details>
<summary><b>Can phone users join my room?</b></summary>
<br>
Yes. <a href="https://github.com/Pytholearn/UsPlayer-Android">Us Player for Android</a> can host and join the same rooms, with chat, reactions, and voice.
</details>

<details>
<summary><b>Persian subtitles show <code>???</code> or garbled text.</b></summary>
<br>
Open subtitle settings and set <b>encoding</b> to <b>Windows-1256</b> — most Persian <code>.srt</code> files use that encoding.
</details>

<details>
<summary><b>Can I share a movie stored on my PC?</b></summary>
<br>
Not via a local file path — paths don’t work on other people’s machines. Use a **link** that everyone can open. If you try a local path, the room will pause and prompt you to share a link instead.
</details>

<details>
<summary><b>A website says the movie can’t be played.</b></summary>
<br>
DRM-protected services (Filimo, Namava, Gapfilm, and similar) only play inside their official apps; Us Player will tell you clearly instead of failing silently. For some Iranian sites, **turning off your VPN** helps — their servers often block overseas IPs.
</details>

<a id="license"></a>

### 📄 License

Us Player is open source under the **[MIT License](LICENSE)**.

| | |
|---|---|
| **Copyright** | © 2026 [Pytholearn](https://github.com/Pytholearn) |
| **You can** | Use commercially, modify, distribute, and use privately |
| **Please** | Keep the copyright and license notice in copies |
| **Note** | Software is provided *as is*, without warranty |

See the full license text in [LICENSE](LICENSE).

---

<div align="center">

<img src="assets/logo.png" width="72" alt="Us Player">

**Us Player** · Created by **Hazard** · [usplayer.ir](https://usplayer.ir)

[Windows](https://github.com/Pytholearn/UsPlayer) · [Android](https://github.com/Pytholearn/UsPlayer-Android) · [MIT License](LICENSE)

[English](README.md) · [中文](docs/README.zh-CN.md) · [فارسی](docs/README.fa.md) · [Русский](docs/README.ru.md)

<br>

<sub>Enjoying Us Player? A ⭐ on GitHub helps more movie fans discover it.</sub>

</div>
