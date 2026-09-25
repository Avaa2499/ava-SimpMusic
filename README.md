<div align="center">
<img src="https://raw.githubusercontent.com/maxrave-dev/SimpMusic/dev/fastlane/metadata/android/en-US/images/featureGraphic.png">
<h1>SimpMusic</h1>

A YouTube Music client for Android and Desktop, built with Compose Multiplatform.
</div>

This is a personal fork of [maxrave-dev/SimpMusic](https://github.com/maxrave-dev/SimpMusic), tweaked to taste.
Upstream's README (badges, store links, sponsors, donations, FAQ) lives at the link above if you need any of that.

## Features
- Play music from YouTube Music or YouTube for free, without ads and in the background
- Three Now Playing styles: Classic, Material 3 Expressive and Apple Music
- Ten-band equalizer with presets and AutoEq headphone profiles, plus Delay and Reverb effects
- On-device listening analytics: charts, period history, listening clock, and a yearly Wrapped recap
- Word-by-word lyrics with romanization for 12 languages, share lyrics as an image
- High quality up-to 256kbps stream (Opus or AAC) for YouTube Music Premium users
- Browsing Home, Charts, Podcast, Moods & Genre with YouTube Music data
- Search everything on YouTube
- Spotify Canvas and Animated Album Art
- Play 1080p video with subtitles
- AI song suggestions
- Import playlists converted from Spotify and other apps
- Customize your playlist, synced with YouTube Music
- Notifications from followed artists
- Caching and offline playback support
- Crossfade with DJ-style transitions
- Synced lyrics from SimpMusic Lyrics, LRCLIB, Spotify (login required) and YouTube Transcript, with AI lyrics translation
- Multi-YouTube-account support
- Last.fm scrobbling (Full version)
- Supports SponsorBlock and Return YouTube Dislike
- Sleep Timer
- Android Auto with online content
- Discord Rich Presence
- Listen Together: shared rooms that stay in sync with friends, compatible with Metrolist

## Desktop app

### Which file should I download?
- Windows: download the `.msix` package and run `install.bat` to install.
- macOS: download the `.dmg` file.
- Linux: download the `.AppImage` file (all distributions).

### Known limitations
- Some Linux distributions may have stability issues (upstream JetBrains issue).
- ARM64 on Windows and Linux: use the x64 build.

## Data & privacy
- Uses YouTube Music's hidden API to fetch data, and the Spotify Web API for Canvas/lyrics.
- No tracking or third-party data collection in the FOSS build. The Full build adds only Sentry crash reporting.
- If you enable "Send back to Google," listening history is reported to YouTube Music's own tracking API for recommendations.

## Credit
- [InnerTune](https://github.com/z-huang/InnerTune/) — inspiration for pulling data from YouTube Music.
- [SmartTube](https://github.com/yuliskov/SmartTube) — streaming URL extraction technique.
- [SponsorBlock](https://sponsor.ajay.app/) and Return YouTube Dislike for their respective APIs.
- [LRCLIB](https://lrclib.net/) for lyrics.
- Everyone who built and documented the upstream project this is forked from.

## Legal

See [Legal Disclaimer & Terms of Use](composeApp/src/commonMain/composeResources/files/legal_disclaimer.md) (also shown in-app under Credits). Short version: FOSS, non-commercial, no hosted media, use at your own legal risk.
