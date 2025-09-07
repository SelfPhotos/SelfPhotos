<h1 align="center">
  <img src="https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/logo.png?raw=true" height="80" alt="Aicasa Logo" />
  <p>Self Photos</p>
</h1>

<p align="center">English | <a href="./README.zh.md">中文</a></p>


**Self Photos** is a **self-hosted cross-platform photo/video management tool** written in **Rust** programming language, available for all major platforms — Windows, macOS, Linux (coming soon), Android, and iOS.
Think of it as your localized Google Photos, designed with privacy, ownership, and full control in mind.

> 👏 Join [Discord](https://discord.gg/VCqXcAz6Js) | Follow on [X(Twitter)](https://x.com/wikkefly)

# ✨ Core Features

## 1. Scanning Computer Disk and Build Local Media Library

- Define custom scan paths
- Support for scanning network drives, such as SMB-mounted drives (Windows) or directories (Unix)
- Nested scanning rules: exclude certain folders, but allow subpaths inside them to be included
- Threshold settings for filtering out small files (e.g., icons, cache images)
- Built with Rust for maximum performance and safety, ensuring a smooth experience
- Parse and extract photo/video metadata, organize by shooting date, and browse via timeline
- Favorite photos/videos for quick access
- Open photos/videos with your system’s default apps
- Locate and open files directly in the system’s file explorer
- Features reminiscent of the beloved `Google Picasa` (now discontinued)

## 2. Mobile Albums Backup to Computer or External Drive

- Install the **Self Photos** mobile app and pair with the desktop application on the same LAN
- **Automatic backup**: selected mobile albums are backed up automatically
- **Manual backup**: choose specific photos/videos to back up
- Assign different backup paths for each mobile device
- Flexible naming rules for subfolders and filenames, e.g `E:/Backup/iPhone 16 Pro Max/2025/2025-12/2025.12.01_IMG_1234.jpg`
- Support concurrent uploads of multiple photos/videos

## 3. Excellent Photo Browsing Experience like `Google Photos`

- Timeline browsing by **shooting date**
- Custom scroll bar for quickly jumping to a specific month/year
- Browse by your OS’s original folder structure for familiarity
- Thumbnail options: keep original aspect ratio or crop to square
- Optimized to handle **hundreds of thousands of photos** while staying smooth
- Split-view preview for side-by-side photo comparison

## 4. Privacy Always First

- Works fully offline — no internet required
- Your photos/videos never leave your devices; only indexed and displayed locally
- Mobile backup requires desktop and mobile to be on the same LAN (internet connection not required)

## 5. Unlimited Storage & Speed

- Backup storage is limited only by the available space on your own disks
- No speed throttling — transfer as fast as your LAN allows
- No limits, no subscriptions — because it’s **your devices and your network**

# 🌠 Screenshot

## Mobile APP

![Screenshot: mobile app](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/screenshot-mobile.png?raw=true)

<p align="center">Mobile APP, from connecting to backing up</p>

## Desktop APP

![Screenshot 1](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/screenshot-1.png?raw=true)

<p align="center">Timeline View</p>

![Screenshot 2](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/screenshot-2.png?raw=true)

<p align="center">Folder Structure View</p>

![Screenshot 3](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/screenshot-3.png?raw=true)

<p align="center">Preview in light/dark mode</p>

![Screenshot: Pairing mobile with desktop](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/screenshot-pairing.png?raw=true)

<p align="center">Pairing mobile with desktop, and configure backup path, dir and file naming pattern</p>

![Screenshot: importing photos from mobile device](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/screenshot-importing.png?raw=true)

<p align="center">Importing photos/videos from mobile devices</p>

# ⬇️ Download

Download **Windows/MacOS/Linux installer** and **Android/iOS APP** at [https://selfphotos.com/download](https://selfphotos.com/download)
