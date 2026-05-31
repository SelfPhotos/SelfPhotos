<h1 align="center">
  <img src="https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/logo.png?raw=true" height="80" alt="Aicasa Logo" />
  <p>爱看相册</p>
</h1>

<p align="center"><a href="./README.md">English</a> | 中文 | <a href="./README.de.md">Deutsch</a> | <a href="./README.es.md">Español</a> | <a href="./README.fr.md">Français</a> | <a href="./README.hi.md">हिन्दी</a> | <a href="./README.it.md">Italiano</a> | <a href="./README.ja.md">日本語</a> | <a href="./README.pt.md">Português</a> | <a href="./README.ru.md">Русский</a></p>

**爱看相册**是一款由 Rust 打造的**跨平台照片/视频管理工具**，支持 Windows、macOS 和 Linux（即将发布），以及 Android、iOS。

它就像一个完全本地化的 Google 相册 —— 帮你把电脑、移动硬盘、NAS 和手机里的照片视频统一整理起来，同时更注重隐私与掌控：你的照片不会上传到云端，只保存在你自己的设备里。

![Screenshot: desktop app](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/self-photos-screenshot.png?raw=true)

> 👏 扫码关注微信公众号，获取下载链接，抢先体验测试版最新功能，AI功能版也会第一时间在群里发出
>
> <img src="https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/wechat-qrcode.jpg?raw=true" alt="Wechat QR Code" height="150">

# ✨ 核心功能

## 一、找回散落在各处的照片视频

爱看相册可以扫描电脑、移动硬盘、外接磁盘以及 NAS 中的照片和视频，把分散在不同位置的回忆统一索引成一个本地媒体库。

- **一键扫描**：快速发现电脑中的照片和视频，自动提取拍摄时间、位置、媒体类型等信息
- **自由选择数据源**：可添加本地文件夹、外接硬盘、网络位置等数据源；原“文件夹”页面已升级为全新的“数据源”页面，并提供更清晰的文件夹列表视图
- **SMB 协议支持**：可直接通过 SMB 扫描和索引 NAS 上的照片视频，无需先把文件复制到本机
- **灵活的扫描规则**：支持指定扫描路径、排除文件夹、嵌套路径规则，以及通过文件大小阈值过滤图标、缓存图等无关小图
- **文件监控与手动扫描**：本地数据源支持实时监控照片视频变化并动态更新索引；非本地数据源可按需手动扫描
- **Live Photo 自动识别**：扫描各类数据源时自动检测并绑定 Live Photo，让照片和动态片段保持在一起

![Screenshot: scan select](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/scan-screenshot.png?raw=true)

## 二、手机相册自动备份到电脑

手机安装“爱看相册”App 后，与同一局域网内的桌面端配对，就可以把 Android 和 iOS 设备中的照片视频备份到电脑或外接硬盘。

- **插上就备份**：指定手机相册后，新照片和视频可自动同步到电脑
- **手动备份**：也可以按需选择具体照片视频进行备份
- **按日期范围备份**：只备份最近一段时间的照片视频，适合快速整理新内容
- **原图原视频保存**：不压缩、不降低画质，保留完整细节
- **多设备独立管理**：可为不同手机设置不同备份目录，并支持按规则生成子文件夹和文件名，例如 `E:/Backup/iPhone 16 Pro Max/2025/2025-12/2025.12.01_IMG_1234.jpg`
- **局域网传输**：传输不消耗移动流量，速度取决于你的本地网络和硬盘性能

![Screenshot: mobile app](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/screenshot-mobile.png?raw=true)

## 三、按时间线重温回忆

爱看相册会根据照片视频的拍摄时间自动整理媒体库，让你像翻日记一样回到某一天、某个月或某一年。

- **按拍摄日期自动归档**：照片视频按真实拍摄时间排列，而不是只按文件创建时间堆在一起
- **快速跳转日期**：通过时间轴和日期定位，迅速跳到某年某月
- **丝滑浏览大图库**：充分优化的桌面体验，即使面对几十万张照片也能流畅滚动
- **Hover Preview**：鼠标悬停即可快速预览照片和视频，大幅提升筛选与浏览效率
- **内置视频播放器**：直接在应用中播放视频，支持格式取决于系统解码器
- **多种浏览方式**：支持时间线、原始目录结构、收藏、系统默认应用打开，以及定位到文件所在系统文件夹

![Screenshot: timeline](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/timeline.png?raw=true)

## 四、在地图上查看回忆

如果照片包含地理位置信息，爱看相册可以把它们呈现在地图上，让旅行、生活轨迹和某次出行的照片更容易被重新发现。

- **按地点回看照片**：从地图上的位置快速找到当时拍摄的照片视频
- **与时间线互补**：既可以按“什么时候”找，也可以按“在哪里”找
- **隐私优先**：位置信息只在本地用于索引和展示，不会上传到云端

## 五、用相册主动整理重要内容

除了自动按时间、地点、目录组织，爱看相册也提供全新的相册功能，适合把旅行、家庭、项目、节日或某个主题的照片主动收集起来。

- **创建主题相册**：把分散在不同来源、不同日期的照片视频整理到同一个相册中
- **保留原文件位置**：相册用于组织和展示，不需要移动原始文件
- **适合长期收藏**：婚礼、宝宝成长、旅行合集、作品素材等都可以独立成册

![Screenshot: album](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/album.png?raw=true)

## 六、清理、管理与全新桌面体验

爱看相册不仅负责“看”，也帮助你更高效地整理媒体库。

- **重复文件检测**：智能识别重复照片和视频，支持预览与批量删除，帮助你清理图库
- **全新设计系统**：更现代的 UI 与桌面软件体验，适合长期管理大规模照片视频
- **收藏与对比预览**：重要内容可快速收藏，预览页面支持左右分屏对比
- **无限存储与速度**：容量只取决于你的硬盘，传输速度只取决于你的局域网和设备性能
- **隐私安全**：软件离线也能使用；照片视频不会离开你的设备，手机备份只需要处在同一局域网

![Screenshot: duplicate detection](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/duplicate.png?raw=true)


# ⬇️ 下载

- (推荐)扫码关注微信公众号，获取最新 **桌面端程序** 和 **移动端APP** **稳定版**下载链接，点击公众号菜单栏入群，可获取最新信息和**内测版**下载链接<br />
<img src="https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/wechat-qrcode.jpg?raw=true" alt="Wechat QR Code" height="150">
- 从官网网站 <a href="https://aikanxiangce.com/download">https://aikanxiangce.com/download</a> 下载
