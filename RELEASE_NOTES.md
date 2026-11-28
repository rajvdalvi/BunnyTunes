## BunnyTunes V2 (`v2.0`) — Android Release

### Highlights
- **100% BunnyTunes Identity:** Completely rebranded app UI, launcher name (`BunnyTunes`), **BunnyTunes Pass** (`bunnytunes.app`), **BunnyTunes Radio**, **BunnyTunes Replay**, and **BunnyTunes v2.0** (`Developer: Raj Dalvi`) with zero upstream legacy branding.
- **Black & White Liquid Glass Logo:** Redesigned monochrome liquid glass launcher icon, adaptive/monochrome icons, and sharp app vector wordmarks.
- **Spotify Playlist Import Fix:**
  - Fixed 100+ track Spotify playlist pagination by adding pure-OkHttp embed session token harvesting in `SpotifyToken` (no fragile WebView `/api/token` dependency).
  - Added fallback extraction & resolution for `spotify.link` / `spoti.fi` shortlinks, pasted share text, and bare 22-character playlist IDs in `SpotifyImporter`.
- **Resource & Stability Fixes:** Recomputed all 4,432 Compose Multiplatform `.cvr` resource offsets with 0 errors and verified v2/v3 release signing.

### Showcase
- Live Website & Screenshots: https://rajvdalvi.github.io/BunnyTunes/#screenshots

### APK Verification
- **File:** `BunnyTunes-V2.apk`
- **Size:** `83.67 MB` (`87,736,812` bytes)
- **Package:** `com.dev.bitchord` (`versionCode 200`, `versionName 2.0`)
- **Min / Target SDK:** `26` / `36`
- **SHA-256:** `42df74211c9719a44d9d62ccfbd22d6c0ffb1ff369b984e69ef173fe89179df8`
