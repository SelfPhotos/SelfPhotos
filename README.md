<h1 align="center">
  <img src="https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/logo.png?raw=true" height="80" alt="Self Photos Logo" />
  <p>Self Photos</p>
</h1>

<p align="center">English | <a href="./README.zh.md">中文</a> | <a href="./README.de.md">Deutsch</a> | <a href="./README.es.md">Español</a> | <a href="./README.fr.md">Français</a> | <a href="./README.hi.md">हिन्दी</a> | <a href="./README.it.md">Italiano</a> | <a href="./README.ja.md">日本語</a> | <a href="./README.pt.md">Português</a> | <a href="./README.ru.md">Русский</a></p>

**Self Photos** is a **cross-platform photo and video management desktop app** built with Rust. It supports Windows, macOS, and Linux (coming soon), and has Android and iOS apps for backing up phone albums to your computer. Core features include:

- 💽 **Unified media library**: scan photos and videos from your computer, external drives, and NAS, and bring them together into one local library.
- 📱 **Automatic phone backup**: pair the mobile app with the desktop app to automatically back up original photos and videos from Android and iOS to your computer.
- 🗓️ **Timeline browsing**: automatically organize by shooting time, quickly jump to dates, and smoothly browse large libraries.
- 😀 **Face recognition**: automatically group the same person together, with naming, searching, and finding group photos with multiple people.
- 🔍 **AI image search**: describe content in natural language to accurately find photos and videos.
- 🧹 **Duplicate cleanup**: detect duplicate files between local disks and NAS, and move them to the recycle bin with one click.
- 📁 **Preserve folder structure**: display media by local folder structure and move, copy, delete, and rename files directly.
- 🗺️ **Map memories**: review photos on a map by location; location information stays local only.
- 📚 **Themed albums**: collect photos from different sources into albums for organization without moving original files.
- 🔒 **Privacy commitment**: photos always stay local and are never uploaded to the cloud.

![Screenshot: desktop app](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/self-photos-screenshot.png?raw=true)

> 👏 Join [Discord](https://discord.gg/VCqXcAz6Js) | Follow on [X(Twitter)](https://x.com/wikkefly)

# ✨ Core Features

## 1. Scan PC/Mac/Linux Drives and NAS Photos, and Bring Them Together in One Place

Self Photos can scan photos and videos from your computer, external drives, and NAS, and index scattered memories into one local media library.

- **Build a unified local library**: automatically extract shooting time, location, and other information from EXIF metadata, and display it on the timeline and map pages
- **Scan NAS media**: scan and index photos and videos on NAS directly through SMB, without copying files to your computer first
- **Flexible scan rules**: specify scan paths, exclude folders, and configure nested path rules; set a file-size threshold to filter out icons, cache images, and other small files
- **File monitoring and manual scanning**: monitor local drive changes in real time (added, deleted, or moved) and update the library automatically; non-local data sources such as NAS can be updated with one-click scanning
- **Live Photo detection**: when a photo and a video with the same filename are found in the same directory, automatically associate them as a Live Photo

![Screenshot: scan select](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/scan-screenshot.png?raw=true)

## 2. Back Up Mobile Albums to Your Computer

Install the Self Photos mobile app and pair it with the desktop app on the same local network to back up photos and videos from Android and iOS devices to your computer or an external drive.

- **Automatic backup**: after selecting mobile albums, new photos and videos sync automatically to your computer
- **Back up by date range**: back up only photos and videos from a recent period, or choose the full time range
- **Back up by type**: choose to back up only photos, only videos, or both by default
- **Original quality**: save original photos and videos without compression or quality loss
- **Independent multi-device management**: set separate backup folders for different phones, with rules for generated subfolders and filenames, such as `E:/Backup/iPhone 16 Pro Max/2025/2025-12/2025.12.01_IMG_1234.jpg`
- **Local network transfer**: backups do not use mobile data; speed depends on your local network and disk performance

![Screenshot: mobile app](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/screenshot-mobile.png?raw=true)

## 3. Revisit Memories by Timeline

Self Photos automatically organizes your library by the actual shooting time of photos and videos, parsing EXIF metadata to extract accurate shooting times.

- **Fast date jumping**: quickly jump to a specific year, month, or day using the timeline and date navigation
- **Smooth browsing for large libraries**: optimized desktop experience that stays fluid even with millions of photos
- **Hover preview**: hover to quickly preview photos and videos, making browsing and filtering much faster
- **Built-in video player**: play videos directly in the app, with format support depending on your system codecs

![Screenshot: timeline](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/timeline.png?raw=true)

## 4. Face Recognition

Self Photos intelligently recognizes faces in photos and videos, automatically groups the same person into a manageable person, and makes them available across the timeline, folder, and other pages.

- **Automatic face grouping**: intelligently recognize faces in photos and videos, and automatically merge multiple faces of the same person into one person for centralized display
- **Name and pin people**: name recognized people and pin them so you can quickly find the important ones
- **Search by person**: search for photos and videos by person in any photo list
- **Find group photos**: select multiple people at the same time to quickly find photos that include all of them
- **Hide people you don't want to see**: hide any person with one click if you don't want them to appear while browsing
- **Custom person cover**: change the cover photo for each person and choose the most representative one

![Screenshot: face recognition](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/face-recognition.png?raw=true)

## 5. AI Image Recognition and Search by Text

Self Photos includes built-in AI models that understand the content of photos and videos, and lets you search your library directly using natural language.

- **AI content recognition**: AI models intelligently recognize subjects, scenes, and details in photos and videos, powering search by text
- **Natural language search**: enter natural language to search for matching photos and videos, without manual tagging
- **Accurate long queries**: feel free to search with long sentences, such as "a child playing with a blue balloon while their parents kiss in the background," and the AI will accurately find the target photo and rank it first
- **Smart categories**: common themes are categorized by default, so you can view results as soon as you open them

![Screenshot: AI search](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/vision-search.png?raw=true)

## 6. Duplicate Detection and One-Click Cleanup

- **Duplicate detection**: intelligently identify duplicate photos and videos, including duplicates between local disks and NAS
- **Group by directory**: automatically aggregate duplicates by the directory name they live in, so you can review and clean them one directory at a time; this matches real-world duplicate patterns, where duplicate files often appear in two similar directories
- **Manual or automatic selection**: in each duplicate group, manually choose which photos to delete, or sort by file name, path, size, or duplicate count and choose to keep the first, last, or files in the current directory
- **One-click cleanup**: after batch selection, move selected photos to the recycle bin. For files on SMB, where there is no recycle bin, the app will ask before permanently deleting so you don't lose the chance to recover them.

![Screenshot: duplicate detection](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/duplicate.png?raw=true)

## 7. Browse and Manage by Local Folder Structure

Services like Google Photos and Immich de-emphasize folder structure. As a local photo manager, Self Photos respects the folder structure you already have, because it may carry your past organization history, such as folder grouping and file naming.

- **Browse by folder in data sources**: the data source page shows files in a folder hierarchy by default, clearly presenting where files are located
- **Manage like a file explorer or Finder**: move, copy, delete, and rename files directly in the app, without switching to Explorer or Finder
- **Future agents understand folder hierarchy**: when the future photo-management agent arrives, it will use folder hierarchy as context to better recognize photos and help you organize them

![Screenshot: folder view](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/folder.png?raw=true)

## 8. Revisit Memories on a Map

If your photos include location information, Self Photos can show them on a map.

- **Review photos by place**: quickly find photos and videos taken at a location from the map
- **Privacy first**: location information is used only locally for indexing and display, never uploaded to the cloud

![Screenshot: map](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/map-screenshot.png?raw=true)

## 9. Albums

In addition to automatic organization by time, location, and folder, Self Photos includes albums for actively collecting travel, family, project, holiday, or theme-based media.

- **Create themed albums**: collect photos and videos from different sources and dates into one album
- **Keep original files in place**: albums organize and display media without moving the original files
- **Great for long-term collections**: weddings, baby growth, travel collections, creative assets, and more can each have their own album

![Screenshot: album](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/album.png?raw=true)

## 10. Our Strong Commitment to Privacy

- **Privacy first**: Self Photos is local-first and privacy-first. Your photo assets always remain local, and are never uploaded to the cloud, including metadata.
- **Safety guarantee**: we never modify or delete your photos unless you choose to do so while organizing in the app. By default, deletions only move files to the recycle bin or trash, giving you a chance to recover from mistakes.

# ⬇️ Download

- GitHub (Desktop only): [https://github.com/SelfPhotos/SelfPhotos/releases/latest](https://github.com/SelfPhotos/SelfPhotos/releases/latest)
- Official website (Desktop & Android/iOS app): [https://selfphotos.com/download](https://selfphotos.com/download)
