<div align="center">
  <img src="docs/logo.png" alt="BunnyTunes Logo" width="128" height="128" />
  <h1>BunnyTunes V2</h1>
  <p><strong>Minimal monochrome Liquid Glass music player for Android</strong></p>

  <p>
    <a href="https://github.com/rajvdalvi/BunnyTunes/releases/latest">
      <img src="https://img.shields.io/badge/Download-BunnyTunes%20V2.0-black?style=for-the-badge&logo=android" alt="Download BunnyTunes V2.0" />
    </a>
    <a href="https://rajvdalvi.github.io/BunnyTunes/">
      <img src="https://img.shields.io/badge/Website-Live%20Showcase-white?style=for-the-badge&logo=githubpages&logoColor=black" alt="Website" />
    </a>
  </p>
</div>

---

## Screen Recording Demo

Watch the full Android app walkthrough captured on device:

- **Demo Video:** [BunnyTunes-V2-Demo.mp4](https://github.com/rajvdalvi/BunnyTunes/releases/download/v2.0/BunnyTunes-V2-Demo.mp4)

https://github.com/rajvdalvi/BunnyTunes/releases/download/v2.0/BunnyTunes-V2-Demo.mp4

---

## What's New in V2 (`v2.0`)

- **Complete BunnyTunes Rebrand:** Installed launcher name is **BunnyTunes**, app settings display **BunnyTunes v2.0** (`Developer: Raj Dalvi`), BunnyTunes Radio, BunnyTunes Replay, and **BunnyTunes Pass** (`bunnytunes.app`) — with zero upstream legacy branding anywhere in the UI.
- **Redesigned Black & White Liquid Glass Logo:** Custom monochrome adaptive foreground + monochrome themed icon (`#070709` obsidian glass backdrop) and matching in-app SVG marks.
- **Spotify Playlist Import Fix:** Fixed anonymous Spotify session token harvesting via pure OkHttp fallback (avoiding WebView `/api/token` hangs for 100+ track playlists) and added shortlink (`spotify.link` / `spoti.fi`), share-text, and bare playlist ID extraction.
- **Crash & Resource Stability Fixes:** Fixed all Compose Multiplatform `.cvr` string-resource byte offset descriptors, restored internal proxy/backup protocol compatibility, and signed with v2/v3 APK signature schemes.

## Download & Verify

| Field | Value |
|---|---|
| **Release Tag** | `v2.0` (`versionCode 200`, `versionName 2.0`) |
| **APK Asset** | [`BunnyTunes-V2.apk`](https://github.com/rajvdalvi/BunnyTunes/releases/download/v2.0/BunnyTunes-V2.apk) |
| **Demo Video Asset** | [`BunnyTunes-V2-Demo.mp4`](https://github.com/rajvdalvi/BunnyTunes/releases/download/v2.0/BunnyTunes-V2-Demo.mp4) |
| **Package ID** | `com.dev.bitchord` |
| **Min / Target Android** | Android 8.0+ (API 26) / Target API 36 |
| **File Size** | `83.67 MB` (`87,736,812` bytes) |
| **SHA-256** | `42df74211c9719a44d9d62ccfbd22d6c0ffb1ff369b984e69ef173fe89179df8` |

### Install via ADB

```bash
adb install -r BunnyTunes-V2.apk
```

---

## Key Features

- **Home, Explore & Radio:** Personalized mixes, curated moods/genres, podcasts, and BunnyTunes Radio.
- **Synchronized Lyrics & Translation:** Dynamic blurred artwork canvas with live synced lyrics and inline translation.
- **Lossless Audio & Spatial Support:** Lossless quality controls, Direct Source Stream, hardware Dolby Atmos support, and offline downloads.
- **Spotify Playlist Import & Local Playlists:** Paste a Spotify playlist link, `spotify:playlist:` URI, share text, or `spotify.link` URL to match tracks on YouTube Music and save directly or locally on-device.
- **BunnyTunes Pass & Replay:** Built-in listening telemetry cards and annual/monthly Replay summaries.

---

<p align="center">Built &amp; maintained by <strong>Raj Dalvi</strong></p>
