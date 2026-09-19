<div align="center">

# 🧹 EasyMac Cleaner

### A simple, native cleaner and optimizer for macOS

[![Homebrew Cask](https://img.shields.io/badge/Homebrew-easymac--cleaner-orange?style=flat-square&logo=homebrew)](https://formulae.brew.sh/cask/easymac-cleaner)
[![macOS](https://img.shields.io/badge/macOS-11.0%2B-blue?style=flat-square&logo=apple)](https://martiancat.space)
[![Apple Notarized](https://img.shields.io/badge/Apple%20Security-Notarized-success?style=flat-square&logo=apple)](https://martiancat.space)
[![Swift](https://img.shields.io/badge/Swift-5.0%2B-FA7343?style=flat-square&logo=swift&logoColor=white)](https://swift.org)
[![UI](https://img.shields.io/badge/UI-SwiftUI-0071E3?style=flat-square&logo=apple&logoColor=white)](https://developer.apple.com/xcode/swiftui/)
[![Languages](https://img.shields.io/badge/Languages-14-purple?style=flat-square)](https://github.com/MartianCatBR/easymac-cleaner#-supported-languages)
<br/>
[![SIP](https://img.shields.io/badge/SIP-100%25%20Compatible-success?style=flat-square&logo=apple)](https://martiancat.space)
[![Root](https://img.shields.io/badge/Root-Not%20Required-success?style=flat-square)](https://martiancat.space)
[![Privacy First](https://img.shields.io/badge/Privacy-Anonymous-green?style=flat-square)](https://martiancat.space/privacy.html)
[![Architecture](https://img.shields.io/badge/Architecture-Universal-lightgrey?style=flat-square)](https://martiancat.space)
[![Download](https://img.shields.io/badge/Download-v1.4.1-007EC6?style=flat-square)](https://updates.martiancat.space/cleaner/EasyMacCleaner-1.4.1.zip)

<br/>

<img src="screenshots/hero-dashboard.png" alt="EasyMac Cleaner Dashboard" width="850" />

<br/><br/>

[**🌐 Official website**](https://martiancat.space) &nbsp;•&nbsp; 
[**⬇️ Download latest**](https://updates.martiancat.space/cleaner/EasyMacCleaner-1.4.1.zip) &nbsp;•&nbsp; 
[**📜 Privacy policy**](https://martiancat.space/privacy.html) &nbsp;•&nbsp; 
[**💬 Report an issue**](https://github.com/MartianCatBR/easymac-cleaner/issues)

</div>

---

## ⚡ Quick install via Homebrew

The easiest way to install and keep it updated:

```bash
brew install --cask easymac-cleaner
```

> 💡 **Tip**: you can update anytime with `brew upgrade --cask easymac-cleaner` or use the built-in Sparkle updater.

### 📦 Direct download
Prefer a standalone build? Download the signed and notarized app from the [official website](https://martiancat.space) or from the [Releases](https://github.com/MartianCatBR/easymac-cleaner/releases) page.

---

## ✨ What it does

EasyMac Cleaner is divided into three main sections: cleaning junk, system optimization, and maintenance tools.

### 🧹 1. Cleanup
- **Accumulations**: Cleans orphan caches, temporary files, crash logs, and Xcode derived data safely.
- **Trash & Downloads**: Empties old trash bins and removes leftover dmg/pkg installers based on configurable age rules.
- **Large Files**: Finds the heaviest files taking up disk space so you can review and delete what you don't need.
- **Duplicate Files**: Detects duplicate files using content hash comparison and provides side-by-side previews before deleting.
- **Old Files**: Locates forgotten archives, media, and documents that haven't been opened in months or years.
- **Traces & Privacy**: Clears browsing history, cookies, download logs, and website caches from Safari, Chrome, Firefox, Brave, Edge, and other browsers.
- **Lipo (App Thinning)**: Removes unused architecture slices from universal binaries (e.g., removing Intel code on Apple Silicon Macs) with automatic backup protection.

### 🚀 2. Optimization
- **Login Items**: Disables unnecessary startup applications and background helpers to speed up boot times.
- **Scheduled Tasks**: Inspects and manages LaunchAgents and LaunchDaemons.
- **Storage**: Disk visualizer, S.M.A.R.T. drive health diagnostics, purgeable space cleanup, and built-in SSD read/write benchmark.

### 🛠️ 3. Tools
- **System Monitor**: Lightweight menu-bar item for real-time CPU, RAM pressure, disk activity, and hardware temperatures.
- **Free RAM**: Flushes inactive memory and system caches using native macOS APIs.
- **Maintenance**: Runs essential maintenance scripts, rebuilds Spotlight search indexes, flushes DNS cache, and repairs disk permissions.
- **File Shredder**: Multi-pass secure file destruction to prevent recovery of sensitive data.
- **Optimize Cloud**: Clears local cached copies from iCloud Drive, OneDrive, Google Drive, and Dropbox without removing remote files.
- **Server & NAS Cleanup**: Cleans up `.DS_Store`, `._*` resource forks, and AppleDouble metadata from network shares (SMB, NFS, AFP).
- **Optimize Battery**: Real-time battery health info (cycle count, max capacity percentage, temperature, charging wattage), energy optimization profiles, and longevity tips.
- **AI Models Manager**: Detects and cleans local model weights, caches, and context files from Ollama, LM Studio, Hugging Face, and local AI engines.

---

## 🏎️ SSD Benchmark & Storage Diagnostics

The Storage tool includes a native disk benchmark designed specifically for modern macOS drives and external media:
- **Realistic measurements**: Uses incompressible random buffers and direct-to-disk I/O (`F_NOCACHE` / `F_FULLFSYNC`) to avoid artificial controller compression.
- **Sequential & 4K IOPS**: Measures sequential read/write throughput and random 4K IOPS to evaluate real-world responsiveness.
- **Controller warmup**: Automatic brief pre-run pass to eliminate cold-start controller latency spikes.
- **S.M.A.R.T. Health**: Reads wear levels, spare blocks, thermal sensors, and hardware status on supported internal and external drives.

---

## 🏆 Metrics, Achievements & Global Ranking

The Metrics dashboard tracks your Mac maintenance history and includes an optional community system:

- **Lifetime metrics**: Total disk space recovered, apps thinned, duplicate files removed, and maintenance routines run.
- **Cleanup reports**: Review post-cleanup summaries with exact items deleted, space freed, and status details.
- **Gamified achievements**: Over a dozen achievements for storage milestones, system monitor alerts, community contributions, and secret discoveries.
- **Global & country leaderboards**: Completely opt-in rankings based on total space recovered and verified SSD benchmark scores.
- **100% anonymous**: Participates using only a random local token without collecting names, IP addresses, paths, or file contents.

---

## 🌐 Community Crowdsourcing

Users can suggest new leftover patterns and cleanup rules directly inside the app. Accepted community rules are distributed automatically to all users via the MartianCat API without needing a full software update.

Accepted contributors receive the Community Hero achievement and a badge in the app metrics.

---

## 📸 Screenshots

<div align="center">

| ⚡ Junk cleaning | 📊 Storage health and purgeable space |
| :---: | :---: |
| <img src="screenshots/accumulations.png" width="410" alt="Accumulations Cleanup" /> | <img src="screenshots/storage.png" width="410" alt="Storage Analysis" /> |

| 🎛️ Real-time system monitor | 🔧 System maintenance and scripts |
| :---: | :---: |
| <img src="screenshots/system_monitor.png" width="410" alt="System Monitor" /> | <img src="screenshots/maintenance.png" width="410" alt="Maintenance" /> |

| 🌐 Community crowdsourcing | 🏆 Metrics, achievements and leaderboard |
| :---: | :---: |
| <img src="screenshots/crowdsourcing.png" width="410" alt="Community Crowdsourcing" /> | <img src="screenshots/metrics.png" width="410" alt="Metrics and Leaderboard" /> |

</div>

---

## 🛡️ Security & Privacy

- Signed with an Apple Developer ID and notarized by Apple.
- Operates strictly within user-space permissions. No root daemons, no kernel extensions, and no SIP disabling required.
- All scans and file operations run 100% locally on your machine.
- Telemetry is minimal, fully anonymized, and can be managed directly in the app settings.
- Read our full privacy policy at [**martiancat.space/privacy.html**](https://martiancat.space/privacy.html).

---

## 💻 System Requirements

- macOS 11.0 (Big Sur) or later.
- Universal binary — native on both Apple Silicon and Intel

---

## 🌍 Supported Languages

Fully localized in **14 languages**:

- 🇺🇸 **English**
- 🇧🇷 **Português** (Portuguese)
- 🇪🇸 **Español** (Spanish)
- 🇩🇪 **Deutsch** (German)
- 🇫🇷 **Français** (French)
- 🇮🇹 **Italiano** (Italian)
- 🇨🇳 **简体中文** (Simplified Chinese)
- 🇹🇼 **繁體中文** (Traditional Chinese)
- 🇯🇵 **日本語** (Japanese)
- 🇰🇷 **한국어** (Korean)
- 🇳🇱 **Nederlands** (Dutch)
- 🇵🇱 **Polski** (Polish)
- 🇷🇺 **Русский** (Russian)
- 🇮🇳 **हिन्दी** (Hindi)

---

## 📬 Feedback & Support

- Bug reports and feature suggestions: open an issue in the [Issues](https://github.com/MartianCatBR/easymac-cleaner/issues) tab.
- Website, licensing, and documentation: visit [martiancat.space](https://martiancat.space).

<br/>

<div align="center">
  <sub>Developed with ❤️ by <a href="https://martiancat.space">MartianCat</a>.</sub>
</div>
