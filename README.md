<div align="center">

<img src="docs/logo.png" alt="BunnyTunes Logo" width="112" height="112" />

# BunnyTunes V2
### Minimal Monochrome Liquid Glass Music Client for Android

[![Website](https://img.shields.io/badge/Website-Live%20Showcase-white?style=flat-square&logo=safari&logoColor=black)](https://rajvdalvi.github.io/BunnyTunes/)
[![Android](https://img.shields.io/badge/Android-8.0%2B-3DDC84?style=flat-square&logo=android&logoColor=white)](https://github.com/rajvdalvi/BunnyTunes/releases)
[![Windows](https://img.shields.io/badge/Windows-Coming%20Soon-lightgrey?style=flat-square&logo=windows&logoColor=white)](#-installation--downloads)
[![License: GPL-3.0](https://img.shields.io/badge/License-GPL--3.0-blue.svg?style=flat-square)](LICENSE)
[![Latest Release](https://img.shields.io/badge/Release-v2.0-000000?style=flat-square&logo=github&logoColor=white)](https://github.com/rajvdalvi/BunnyTunes/releases/tag/v2.0)
[![Developer](https://img.shields.io/badge/Developer-Raj%20Dalvi-black?style=flat-square)](https://github.com/rajvdalvi)

A clean, ad-free Android music streaming client designed around a monochrome **Liquid Glass aesthetic**, fluid transitions, lossless audio streaming, live synced lyrics & translation, **BunnyTunes Pass**, and **Spotify playlist import**.

[**Download Android APK**](https://github.com/rajvdalvi/BunnyTunes/releases/download/v2.0/BunnyTunes-V2.apk) • [**Live Showcase**](https://rajvdalvi.github.io/BunnyTunes/) • [**App Walkthrough**](#-app-showcase) • [**Installation**](#-installation--downloads)

---

</div>

## 🎬 App Showcase

<div align="center">

[![Watch BunnyTunes V2 Walkthrough](docs/logo.png)](https://rajvdalvi.github.io/BunnyTunes/#demo)

**▶ [Watch Full Screen Recording Showcase](https://rajvdalvi.github.io/BunnyTunes/#demo)** &nbsp;|&nbsp; [View Video in Repository](docs/assets/BunnyTunes-V2-Demo.mp4)

<sub>Real-device Android walkthrough showing Home, Podcasts, BunnyTunes Radio, Library, Instant Search, Lyrics &amp; Translation, Audio Output, BunnyTunes Pass, Appearance &amp; BunnyTunes v2.0 Settings.</sub>

</div>

---

## ✨ What's New in V2 (`v2.0`)

- **Complete BunnyTunes Rebrand:** Installed launcher name is **`BunnyTunes`**, Settings shows **`BunnyTunes v2.0`** (`Developer: Raj Dalvi`), plus **BunnyTunes Pass** (`bunnytunes.app`), **BunnyTunes Radio**, and **BunnyTunes Replay** with zero legacy upstream branding.
- **Redesigned Black & White Liquid Glass Logo:** Custom monochrome adaptive launcher foreground, themed monochrome icon (`#070709` obsidian glass backdrop), and crisp SVG marks.
- **Fixed Spotify Playlist Import:** Resolved anonymous session token harvesting via fast OkHttp embed fallback for 100+ track playlists and added support for `spotify.link` / `spoti.fi` shortlinks, share text, and bare playlist IDs.
- **Resource & Stability Fixes:** Recomputed all 4,432 Compose Multiplatform `.cvr` resource offsets with zero errors and verified APK v2/v3 release signatures.

---

## 📥 Installation & Downloads

### 🤖 Android (Direct APK)
1. Download **`BunnyTunes-V2.apk`** (`83.67 MB`) from [GitHub Releases](https://github.com/rajvdalvi/BunnyTunes/releases/download/v2.0/BunnyTunes-V2.apk).
2. Open the `.apk` on your Android device and tap **Install**.
3. *Alternative (ADB):*
   ```bash
   adb install -r BunnyTunes-V2.apk
   ```

| Asset | Platform | Type | Size | SHA-256 Checksum |
|:---|:---:|:---:|:---:|:---|
| **BunnyTunes-V2.apk** | Android 8.0+ | Signed APK | 83.67 MB | `42df74211c9719a44d9d62ccfbd22d6c0ffb1ff369b984e69ef173fe89179df8` |

---

## 🛠️ Tech Stack & Architecture

- **UI Framework:** Jetpack Compose (Material 3) & Compose Multiplatform
- **Audio Engine:** AndroidX Media3 / ExoPlayer with Lossless PCM & Spatial/Dolby Atmos support
- **Package Name:** `com.dev.bitchord` (`versionCode 200`, `versionName 2.0`)
- **Min / Target SDK:** Android 8.0 (API 26) / Target API 36
- **Security:** Signed with **APK Signature Scheme v2 & v3**

---

<div align="center">
Built &amp; maintained by <b>Raj Dalvi</b> · Licensed under <a href="LICENSE">GPL-3.0</a>
</div>
