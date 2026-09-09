<div align="center">

# 🧹 EasyMac Cleaner

### A simple, native cleaner and optimizer for macOS

[![Homebrew Cask](https://img.shields.io/badge/Homebrew-easymac--cleaner-orange?style=flat-square&logo=homebrew)](https://formulae.brew.sh/cask/easymac-cleaner)
[![macOS](https://img.shields.io/badge/macOS-11.0%2B-blue?style=flat-square&logo=apple)](https://martiancat.space)
[![Apple Notarized](https://img.shields.io/badge/Apple%20Security-Notarized%20%26%20Signed-success?style=flat-square&logo=apple)](https://martiancat.space)
[![Swift](https://img.shields.io/badge/Swift-5.0%2B-FA7343?style=flat-square&logo=swift&logoColor=white)](https://swift.org)
[![UI](https://img.shields.io/badge/UI-SwiftUI-0071E3?style=flat-square&logo=apple&logoColor=white)](https://developer.apple.com/xcode/swiftui/)
[![Languages](https://img.shields.io/badge/Languages-11%20Supported-purple?style=flat-square)](https://github.com/MartianCatBR/easymac-cleaner#-supported-languages)
<br/>
[![SIP](https://img.shields.io/badge/SIP-100%25%20Compatible-success?style=flat-square&logo=apple)](https://martiancat.space)
[![Root](https://img.shields.io/badge/Root-Not%20Required-success?style=flat-square)](https://martiancat.space)
[![Privacy First](https://img.shields.io/badge/Privacy-Anonymous-green?style=flat-square)](https://martiancat.space/privacy.html)
[![Architecture](https://img.shields.io/badge/Architecture-Universal-lightgrey?style=flat-square)](https://martiancat.space)
[![Download](https://img.shields.io/badge/Download-v1.3-007EC6?style=flat-square)](https://updates.martiancat.space/cleaner/EasyMacCleaner-1.3.zip)

<br/>

<img src="screenshots/hero-dashboard.png" alt="EasyMac Cleaner Dashboard" width="850" />

<br/><br/>

[**🌐 Official website**](https://martiancat.space) &nbsp;•&nbsp; 
[**⬇️ Download latest**](https://updates.martiancat.space/cleaner/EasyMacCleaner-1.3.zip) &nbsp;•&nbsp; 
[**📜 Privacy policy**](https://martiancat.space/privacy.html) &nbsp;•&nbsp; 
[**💬 Report an issue**](https://github.com/MartianCatBR/easymac-cleaner/issues)

</div>

---

## ⚡ Quick install via Homebrew

The easiest way to install and keep it updated:

```bash
brew install --cask easymac-cleaner
```

> 💡 **Tip**: later you can just run `brew upgrade --cask easymac-cleaner` or use the built-in Sparkle updater.

### 📦 Direct download
Prefer the zip? Grab the signed and notarized build from the [Official website](https://martiancat.space) or from the [Releases](https://github.com/MartianCatBR/easymac-cleaner/releases) page.

---

## ✨ What it does

Three main parts: cleaning junk, light optimization, and a few extra tools.

### 🧹 1. Cleanup
- **Accumulations**: Clears orphaned caches, temp files, crash logs, and Xcode derived data. Usually frees up a good amount of space.
- **Trash & Downloads**: Removes old trash items and leftover installers with simple age rules.
- **Large Files**: Fast finder for the biggest space hogs so you can decide what to keep or delete.
- **Duplicate Files**: Finds exact duplicates by content hash, shows a side-by-side preview, then lets you remove them safely.
- **Old Files**: Surfaces documents and archives you haven’t touched in months or years.
- **Traces & Privacy**: Wipes browsing history, cookies, download lists and caches from Safari, Chrome, Brave, Edge, Firefox and other browsers.
- **Lipo**: Strips the unused architecture from universal binaries (e.g. removes the Intel slice on Apple Silicon Macs). Keeps a backup just in case.

### 🚀 2. Optimization
- **Login Items**: Turn off startup apps and background helpers that slow down boot.
- **Scheduled Tasks**: View and manage third-party LaunchDaemons and LaunchAgents.
- **Storage**: Simple visualizer that shows volume health and recovers purgeable space.

### 🛠️ 3. Tools
- **System Monitor**: Lightweight menu-bar display for live CPU, memory pressure, disk activity and temperature.
- **Free RAM**: Releases inactive memory and flushes caches with safe native calls.
- **Maintenance**: Rebuilds Spotlight, flushes DNS, repairs permissions and runs the usual system scripts.
- **Shredder**: Secure multi-pass deletion so files can’t be recovered later.
- **Optimize Cloud**: Clears local offline caches from iCloud Drive, OneDrive, Google Drive and Dropbox without touching the cloud copies.
- **Server & NAS Cleanup**: Removes .DS_Store, AppleDouble and other network junk from SMB, NFS and AFP shares.
- **Optimize Battery**: Basic energy info, power tweaks and longevity tips for MacBooks.

---

## 🌐 Community crowdsourcing

Anyone can suggest new leftover patterns or cache locations from inside the app. After a quick check, the new rules go out to everyone through the MartianCat API — no need to wait for a full app update.
When a suggestion of yours gets accepted you get a small badge and it shows up in your Metrics page under resolved contributions.

---

## 🏆 Optional ranking (metrics)

There’s a completely optional ranking system if you feel like competing a bit:

- Global and country leaderboar based on total space recovered.
- Simple achievements for cleanup volume and accepted community suggestions.
- 100 % opt-in and anonymous. It only uses a random install token — no names, no personal data, no file names.

---

## 📸 Screenshots

<div align="center">

| ⚡ Junk cleaning | 📊 Storage health and purgeable space |
| :---: | :---: |
| <img src="screenshots/accumulations.png" width="410" alt="Accumulations Cleanup" /> | <img src="screenshots/storage.png" width="410" alt="Storage Analysis" /> |

| 🎛️ Real-time system monitor | 🔧 System maintenance and scripts |
| :---: | :---: |
| <img src="screenshots/system_monitor.png" width="410" alt="System Monitor" /> | <img src="screenshots/maintenance.png" width="410" alt="Maintenance" /> |

| 🌐 Community crowdsourcing | 🏆 Metrics and global ranking |
| :---: | :---: |
| <img src="screenshots/crowdsourcing.png" width="410" alt="Community Crowdsourcing" /> | <img src="screenshots/metrics.png" width="410" alt="Metrics and Leaderboard" /> |

</div>

---

## 🛡️ Security & privacy

- Signed with an Apple Developer ID and notarized.
- Stays inside normal macOS security rules. No need to turn off SIP or install any kernel extensions.
- All file processing is done locally. Your personal files never leave the Mac.
- We collect only basic, 100% anonymous telemetry to improve the app. No data reveals who you are or what you do.
- Full details are in the privacy policy at [**martiancat.space/privacy.html**](https://martiancat.space/privacy.html).

---

## 💻 System requirements

- macOS 11.0 (Big Sur) or later.
- Universal binary — native on both Apple Silicon and Intel

---

## 🌍 Supported languages

Fully localized in **11 languages**:

- 🇺🇸 **English**
- 🇧🇷 **Português** (portuguese)
- 🇪🇸 **Español** (spanish)
- 🇩🇪 **Deutsch** (german)
- 🇮🇹 **Italiano** (italian)
- 🇫🇷 **Français** (french)
- 🇨🇳 **简体中文** (simplified Chinese)
- 🇯🇵 **日本語** (japanese)
- 🇰🇷 **한국어** (korean)
- 🇳🇱 **Nederlands** (dutch)
- 🇵🇱 **Polski** (polish)

---

## 📬 Feedback & support

- Bug reports and suggestions: please open an issue in the [Issues](https://github.com/MartianCatBR/easymac-cleaner/issues) tab.
- Website, licensing, etc: Visit [martiancat.space](https://martiancat.space).

<br/>

<div align="center">
  <sub>Developed with ❤️ by <a href="https://martiancat.space">MartianCat</a>.</sub>
</div>
