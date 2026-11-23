# BunnyTunes V1 - Official Release 🐰✨

**Release Date:** November 2026  
**Developer:** Raj Dalvi  
**Platforms:** Android (APK) & Windows (Desktop x64)  
**Package:** `com.music.bitchord` (Customized BunnyTunes Edition)  

---

### 🎉 What's New in BunnyTunes V1:

#### 🪟 Windows Desktop Edition (New!)
- **Native Windows Port:** Packaged standalone desktop app for Windows 10 & 11 (64-bit).
- **Self-Contained Runtime:** Bundles an isolated OpenJDK 21 environment with all FFmpeg and native audio decoders included. No Java or runtime installation required.
- **Native Desktop Integration:** Fluent dark window with Mica/Acrylic frosted liquid glass aesthetics, native Windows media keys (Play/Pause/Next/Previous), System Media Transport Controls (SMTC) integration, and system tray minimization.
- **Zero Ads & Lossless Audio:** Full bit-perfect audio streaming, YouTube Music & JioSaavn search/streaming, and real-time scrolling synchronized lyrics.
- **Custom Desktop Branding:** Updated window chrome, official BunnyTunes vector emblem, and desktop string bundles.

#### 🤖 Android Mobile Edition
- **Full BunnyTunes Vector Emblem:** Integrated the custom Bunny studio-headphone emblem into Compose Multiplatform drawables (`composeResources/drawable/ic_logo.xml`), replacing the legacy 3-wave logo everywhere (top-left home header, "Top Picks for You", "Find Your Mood", and Library cards).
- **All-New Changeable Icon Previews:** Generated custom BunnyTunes vector icons across all densities (`mdpi`, `hdpi`, `xhdpi`, `xxhdpi`, `xxxhdpi`) for all themes (Liquid Glass, Dark Glass, Clear Glass, Neon Cyan, Neon Violet, Neon Silver, and Monochrome).
- **Zero Traces of Previous Branding:** Replaced all occurrences of "BitChord listener" in Compose Variable Resources (`.cvr`) across all 19 supported languages with "BunnyTunes listener".
- **Direct History in Navbar:** Replaced legacy radio/similar mix menus with direct, intuitive access to your listening history right in the navigation dock.
- **Liquid Glass Theme by Default:** Deep OLED glass theme (`#0E0E11`) with ambient background glow enabled out of the box.
- **Lossless Audio Quality:** Enforced highest bitrate audio decoding across Wi-Fi and mobile data with bit-perfect DAC pass-through support.
- **Hindi & Indian Music Feed:** Default region locked to India (`IN`), instantly loading trending Bollywood hits, Indian charts, and regional playlists.
- **Optimized & Lightweight:** Wear OS smartwatch services removed, lowering total memory and battery footprint.
- **Settings Rebranded:** Customized app settings with "BunnyTunes V1", developer links to Raj Dalvi's GitHub, and the live showcase website.
- **Signed & Verified:** Packaged with APK Signature Scheme v2 and v3 for full Android 8.0 through Android 17 compatibility.

---

### 📦 Release Assets & Downloads

| File | Platform | Size | SHA-256 Checksum |
|:---|:---:|:---:|:---|
| [**BunnyTunes-V1.apk**](https://github.com/rajvdalvi/BunnyTunes/releases/download/v1.0/BunnyTunes-V1.apk) | Android 8.0+ | 81.36 MB | `2D9E6D5F1CE7D06B2CC355A4F7260076FA0626FB0C3B38E64CDC5465DBBD6666` |
| [**BunnyTunes-V1-Windows-Portable.zip**](https://github.com/rajvdalvi/BunnyTunes/releases/download/v1.0/BunnyTunes-V1-Windows-Portable.zip) | Windows 10/11 x64 | 302.26 MB | `3ADAFA036156E2C8CAFBD53B00BA7DE71A8F8F44E4FD4169725E579C29A8A4C5` |

---

### 🛠️ Verification & Installation

#### Android:
Download `BunnyTunes-V1.apk`, grant unknown source permissions if prompted, and install.
*(If you have an older version installed, uninstall it first to prevent certificate mismatch).*

#### Windows PC:
Download `BunnyTunes-V1-Windows-Portable.zip`, unzip to any folder, and double-click `BunnyTunes.exe` (or `Run-BunnyTunes.bat`).
