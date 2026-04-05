# ⬇ VidGet — Universal Video Downloader

https://vid-get.netlify.app/

> Download videos from YouTube, TikTok, Instagram, Facebook, Twitter/X, Amazon and 1000+ sites — with a single double-click. No Python. No installs. Just a `.bat` file.

![Windows](https://img.shields.io/badge/Windows-10%2F11-blue?style=flat-square&logo=windows)
![Free](https://img.shields.io/badge/Price-Free-brightgreen?style=flat-square)
![Powered by yt-dlp](https://img.shields.io/badge/Powered%20by-yt--dlp-orange?style=flat-square)
![No Install](https://img.shields.io/badge/Install-None%20Required-success?style=flat-square)

---

## 🚀 What is VidGet?

VidGet is a simple, powerful video downloader for Windows. It runs as a `.bat` file — no Python, no Node.js, no setup wizard, no bloatware. Just download the file, double-click it, paste a URL, and your video is saved.

On the first launch it automatically downloads `yt-dlp.exe` from the official GitHub. After that, everything works instantly.

---

## ✨ Features

- **Zero install** — one `.bat` file is all you need
- **1000+ supported sites** — YouTube, TikTok, Instagram, Facebook, Twitter/X, Amazon, Reddit, Twitch, Vimeo, Pinterest, Dailymotion, SoundCloud and more
- **Best quality MP4** — automatically picks the highest available resolution
- **Audio-only download** — saves as high-quality MP3
- **Quality selector** — manually pick 4K, 1080p, 720p, 480p, etc.
- **Playlist download** — grab entire YouTube playlists or channels
- **Batch download** — paste multiple URLs from different platforms at once
- **Custom save folder** — choose where your files are saved
- **Self-updating** — one-click update to latest yt-dlp version
- **No ads, no accounts, no tracking**

---

## 📋 Supported Platforms (and many more)

| Platform | Works? |
|---|---|
| YouTube | ✅ Videos, Shorts, Playlists, Channels |
| TikTok | ✅ |
| Instagram | ✅ Reels, Posts (public) |
| Facebook | ✅ Public videos |
| Twitter / X | ✅ |
| Amazon | ✅ Product & creator videos |
| Reddit | ✅ |
| Twitch | ✅ VODs & Clips |
| Vimeo | ✅ |
| Pinterest | ✅ |
| Dailymotion | ✅ |
| SoundCloud | ✅ |
| 1000+ more | ✅ Powered by yt-dlp |

---

## 📥 Download & Usage

### Step 1 — Download
Download `VideoDownloader.bat` from the [Releases](../../releases/latest) page and save it anywhere on your PC.

### Step 2 — Run
Double-click `VideoDownloader.bat`.

On first launch it will auto-download `yt-dlp.exe` (~3MB). This only happens once.

> ⚠️ Windows may show a SmartScreen warning. Click **"More info" → "Run anyway"**. This is normal for unsigned `.bat` files.

### Step 3 — Pick an option

```
[1]  Download Video        (best quality MP4)
[2]  Download Audio Only   (MP3)
[3]  Download with Quality (choose 1080p/720p/480p...)
[4]  Download Playlist     (YouTube playlists)
[5]  Batch Download        (multiple URLs at once)
[6]  Change Save Folder
[7]  Update yt-dlp
[8]  Exit
```

### Step 4 — Paste URL & press Enter
Copy any video URL from your browser, paste it in, press Enter. Done.

Files are saved to `Downloads\VideoDownloader\` by default.

---

## 🗂 Menu Options Explained

### `[1]` Download Video
Downloads in the best available quality and saves as MP4. Best for everyday use.

### `[2]` Download Audio Only
Extracts audio and saves as MP3 at highest quality. Great for music, podcasts, lectures.

### `[3]` Download with Quality Choice
Shows all available formats (resolution + codec) and lets you pick exactly what you want.

### `[4]` Download Playlist
Paste a YouTube playlist or channel URL — downloads all videos into a named subfolder.

### `[5]` Batch Download
Enter multiple URLs one by one from any platform. Type `DONE` when finished and they all download in sequence.

### `[6]` Change Save Folder
Set a custom save path. Example: `D:\Videos` or `C:\Users\You\Desktop\Downloads`.

### `[7]` Update yt-dlp
Downloads the latest `yt-dlp.exe` from GitHub. Run this if a site stops working — yt-dlp releases fixes regularly.

### `[8]` Exit
Closes the app. Your downloaded files stay in the save folder.

---

## 📁 File Structure

```
your-folder/
├── VideoDownloader.bat   ← the app (run this)
└── yt-dlp.exe            ← auto-downloaded on first run
```

Downloaded videos are saved to:
```
C:\Users\YourName\Downloads\VideoDownloader\
```

---

## ❓ FAQ

**Do I need Python or any software installed?**
No. The `.bat` file handles everything. `yt-dlp.exe` is downloaded automatically on first run.

**Why does Windows show a security warning?**
Windows SmartScreen warns about any file downloaded from the internet without a paid code-signing certificate. The script is safe — it only contacts the official yt-dlp GitHub. Click "More info" → "Run anyway".

**A site stopped working. What do I do?**
Use option `[7] Update yt-dlp` to get the latest version. Platform changes are usually fixed by the yt-dlp team within 1–2 days.

**Can I download private videos?**
Only public videos are supported. Private Instagram posts, password-protected content, and DRM-protected platforms (Netflix, Amazon Prime Video) cannot be downloaded.

**Does it work on Mac or Linux?**
The `.bat` file is Windows-only. For Mac/Linux, install yt-dlp directly with `pip install yt-dlp` and use it from the terminal.

**Where do my videos get saved?**
By default: `Downloads\VideoDownloader\` in your user folder. Change it anytime with option `[6]`.

---

## ⚙️ Requirements

- Windows 10 or Windows 11
- Internet connection (for downloading videos)
- No other software required

---

## 📄 License

This project is released under the [MIT License](LICENSE).

`yt-dlp` is a separate open-source project licensed under the [Unlicense](https://github.com/yt-dlp/yt-dlp/blob/master/LICENSE). VidGet simply provides a friendly interface for it.

---

## 🙏 Credits

- Video downloading powered by **[yt-dlp](https://github.com/yt-dlp/yt-dlp)** — the open-source community's best video downloader engine.

---

> **For personal use only. Please respect copyright and platform terms of service when downloading content.**
