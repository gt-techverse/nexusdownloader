# Nexus Video Downloader Pro 

A modern, robust Windows desktop video downloading suite and download manager built with **PyQt6**, **yt-dlp**, and **FFmpeg**.

---

##  Key Features

###  Modern Fluent & Dark Aesthetic
- **Sleek Dark Interface**: Linear/Raycast/Fluent 2 styling (Electric Indigo `#6366F1`, deep charcoal cards, emerald chips).
- **High-DPI Support**: Pixel-perfect rendering across 1080p, 2K, and 4K displays.
- **Windows Integration**: Dedicated taskbar branding, custom app icon, and system tray alerts.

###  Download Manager & Multi-Tasking
- **Concurrent Download Queue**: Download multiple videos simultaneously (configurable from 1 to 10 slots).
- **Live Real-time Metrics**: Percentage progress bar, dynamic download speed (MB/s), downloaded size vs total size, and ETA timer.
- **Task Controls**: Pause, Resume, Cancel, Retry failed tasks, or Clear finished items.
- **Batch URL Importer**: Paste multiple URLs at once to queue an entire batch.

###  Integrated In-App Video Browser & Discovery
- **Native Web Surfing**: Browse video sites (YouTube, SoundCloud, Vimeo, TikTok, Twitch, Twitter/X, and more) directly inside the app without switching to an external browser.
- **Smart Media Detection Banner**: Automatically detects active video streams and surfaces one-click download actions.
- **One-Click Quick Download**: Instantly add playing videos straight to your download queue with your default preferences.
- **Inspect & Customize**: One-click jump to the Format & Quality Picker to choose specific 4K, 1080p, or MP3 settings.
- **Quick-Access Launchpad**: Instant bookmark chips for YouTube, SoundCloud, TikTok, Vimeo, Twitch, and more.

###  Smart Video Analyzer
- **URL Inspection**: Fetch video titles, creator/channel, duration, and thumbnail previews before starting the download.
- **Interactive Resolution Chips**: Clickable pills (`[  Auto Best ]`, `[ 4K UHD ]`, `[ 2K QHD ]`, `[ 1080p ]`, `[ 720p ]`, `[ MP3 320k ]`) with instant visual feedback.
- **Audio Extraction**: Dedicated audio mode with format choice (MP3, M4A, FLAC, WAV) and bitrates up to 320 kbps.

###  Rich Configurations & Settings
- **Custom Download Directory**: Choose your default destination directory with quick access shortcuts.
- **Network Throttling**: Optional bandwidth limiter (1 MB/s, 2 MB/s, 5 MB/s, 10 MB/s, 20 MB/s, or Unlimited).
- **Subtitles & Metadata**: Embed subtitles in your preferred language, embed ID3 metadata tags, and attach thumbnail covers.
- **Browser Cookies Import**: Seamlessly import cookies from Chrome, Edge, Firefox, Brave, Opera, or Vivaldi to download private, member-only, or age-restricted videos.

###  History & File Management
- **Searchable History**: Filter completed downloads by video title or channel name.
- **Direct Playback**: Launch media files directly in your default Windows player.
- **Folder Navigation**: Locate and highlight downloaded files in Windows File Explorer with a single click.

---

##  How to Run

### Option 1: Standalone .EXE (Recommended for Users)
Double-click **`NexusDownloader.exe`** directly.

### Option 2: Python Source Code (Developers)
```powershell
python main.py
```
or
```powershell
python yt.py
```

### Option 3: Command Line (CLI Mode)
```powershell
python yt.py --cli [optional_url]
```
