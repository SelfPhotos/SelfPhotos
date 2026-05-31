<h1 align="center">
  <img src="https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/logo.png?raw=true" height="80" alt="Aicasa Logo" />
  <p>Self Photos</p>
</h1>

<p align="center">English | <a href="./README.zh.md">中文</a></p>

**Self Photos** is a **cross-platform photo and video management tool** built with Rust, available for Windows, macOS, Linux (coming soon), Android, and iOS.

Think of it as a fully local Google Photos for your own devices. It helps organize photos and videos from your computer, external drives, NAS, and phones while keeping privacy and control first: your media is not uploaded to the cloud and stays on your own devices.

![Screenshot: desktop app](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/self-photos-screenshot.png?raw=true)

> 👏 Join [Discord](https://discord.gg/VCqXcAz6Js) | Follow on [X(Twitter)](https://x.com/wikkefly)

# ✨ Core Features

## 1. Bring Scattered Photos and Videos Together

Self Photos scans photos and videos from your computer, external drives, attached disks, and NAS, then builds them into one local media library.

- **One-click scanning**: quickly discover photos and videos on your computer and automatically extract shooting time, location, media type, and other metadata
- **Flexible data sources**: add local folders, external drives, network locations, and more; the previous folder page has been upgraded into a clearer data source page with an improved folder list view
- **SMB support**: scan and index photos and videos on a NAS directly through SMB without copying files to your computer first
- **Flexible scan rules**: specify scan paths, exclude folders, configure nested path rules, and filter out icons, cache images, and other irrelevant small files by file size threshold
- **File monitoring and manual scanning**: local data sources can be monitored in real time and update the index dynamically; non-local data sources can be scanned manually when needed
- **Live Photo detection**: automatically detect and bind Live Photos across data sources, keeping still photos and motion clips together

![Screenshot: scan select](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/scan-screenshot.png?raw=true)

## 2. Back Up Mobile Albums to Your Computer

After installing the Self Photos mobile app, pair it with the desktop app on the same local network to back up photos and videos from Android and iOS devices to your computer or external drive.

- **Plug in and back up**: after selecting mobile albums, new photos and videos can sync automatically to your computer
- **Manual backup**: choose specific photos and videos to back up whenever you need
- **Date range backup**: back up only recent photos and videos, useful for quickly organizing new content
- **Original quality**: save original photos and videos without compression or quality loss
- **Independent multi-device management**: set separate backup folders for different phones, with rules for generated subfolders and filenames, such as `E:/Backup/iPhone 16 Pro Max/2025/2025-12/2025.12.01_IMG_1234.jpg`
- **Local network transfer**: backups do not use mobile data; speed depends on your local network and disk performance

![Screenshot: mobile app](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/screenshot-mobile.png?raw=true)

## 3. Revisit Memories by Timeline

Self Photos organizes your library by the real shooting time of photos and videos, so you can return to a specific day, month, or year like flipping through a diary.

- **Automatic archive by shooting date**: photos and videos are arranged by when they were taken, not just by file creation time
- **Fast date jumping**: quickly jump to a specific year or month through the timeline and date navigation
- **Smooth browsing for large libraries**: optimized desktop experience that stays fluid even with hundreds of thousands of photos
- **Hover preview**: hover to quickly preview photos and videos, making browsing and filtering much faster
- **Built-in video player**: play videos directly in the app, with format support depending on your system codecs
- **Multiple ways to browse**: use timeline, original folder structure, favorites, the system default app, or reveal files in the system file manager

![Screenshot: timeline](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/timeline.png?raw=true)

## 4. Organize Important Moments with Albums

In addition to automatic organization by time and folder structure, Self Photos includes albums for actively collecting travel, family, project, holiday, or theme-based media.

- **Create themed albums**: collect photos and videos from different sources and dates into one album
- **Keep original files in place**: albums organize and display media without moving the original files
- **Made for long-term collections**: weddings, children growing up, travel sets, creative assets, and other meaningful collections can each have their own album

![Screenshot: album](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/album.png?raw=true)

## 5. Clean Up, Manage, and Enjoy a New Desktop Experience

Self Photos is not only for viewing. It also helps you manage your media library more efficiently.

- **Duplicate detection**: intelligently find duplicate photos and videos, preview them, and delete them in batches to clean up your library
- **New design system**: a more modern UI and desktop software experience for long-term management of large photo and video libraries
- **Favorites and comparison preview**: quickly favorite important media and compare photos side by side in the preview page
- **Unlimited storage and speed**: capacity is limited only by your disks, and transfer speed is limited only by your local network and device performance
- **Private and secure**: the app works offline; photos and videos do not leave your devices, and mobile backup only requires devices to be on the same local network

![Screenshot: duplicate detection](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/duplicate.png?raw=true)

# ⬇️ Download

Download the latest **desktop installer** and **mobile app** from the official website: [https://selfphotos.com/download](https://selfphotos.com/download)
