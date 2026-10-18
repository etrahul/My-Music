# 🎵 My Music

**My Music** is a Spotify-inspired online music player powered by the **YouTube IFrame & Data API v3**, featuring interactive 3D flip lyrics, custom playlists, JSON backup/restore, and real-time **Listen Together** jam rooms for listening in sync with friends anywhere.

---

## ✨ Key Features

1. **🖼️ 3D Flip Card (Thumbnail + Synced Lyrics):** Click on the album thumbnail card to flip it in 3D and view synchronized, scrollable song lyrics. Includes a built-in lyrics editor.
2. **⏯️ Interactive Music Player Bar:** Persistent bottom control bar with real-time elapsed time, total track duration, percentage indicator, seek slider, Shuffle, Left (Previous), Play/Pause, Right (Next), Repeat, and Volume controls.
3. **❤️ One-Tap Favourites:** Click the Heart (`♥`) icon on any track or in the player bar to instantly save or remove songs from your **Favourites** list.
4. **📂 Custom Playlists:** Create unlimited custom playlists, add or remove tracks anytime, and filter your library by playlist.
5. **💾 Backup & Restore (`.json`):** Export all your custom playlists, favourite songs, and imported YouTube tracks as a `.json` backup file, and restore them anytime with a single upload or paste.
6. **🎧 Listen Together (Live Sync Room):** Create a live room with a unique shareable Room Code (e.g., `MM-4829`) using WebRTC (PeerJS) so friends 200km+ away can join, chat, send live reactions, and listen to the exact same music in real time.

---

## 📱 Build Android APK (`My Music.apk`)

This repository includes an automated GitHub Actions workflow (`.github/workflows/build-apk.yml`) that wraps `my_music.html` into a signed Android app named **My Music** using Capacitor and Gradle.

### How to Download the APK:
1. Go to the **Actions** tab in this GitHub repository.
2. Select the **My Music** workflow and click **Run workflow** (or push any change to `main`).
3. Once the build completes, scroll down to **Artifacts** and download **My Music** to get `My Music.apk`.
