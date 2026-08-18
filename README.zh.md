<h1 align="center">
  <img src="https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/logo.png?raw=true" height="80" alt="爱看相册 Logo" />
  <p>爱看相册</p>
</h1>

<p align="center"><a href="./README.md">English</a> | 中文 | <a href="./README.de.md">Deutsch</a> | <a href="./README.es.md">Español</a> | <a href="./README.fr.md">Français</a> | <a href="./README.hi.md">हिन्दी</a> | <a href="./README.it.md">Italiano</a> | <a href="./README.ja.md">日本語</a> | <a href="./README.pt.md">Português</a> | <a href="./README.ru.md">Русский</a></p>

**爱看相册**是一款由 Rust 打造的**跨平台照片/视频管理桌面软件**，支持 Windows、macOS 和 Linux（即将发布），并且有 Android、iOS App 可以备份手机相册到电脑。核心功能包括：

## ✨ 核心功能

- 💽 **统一媒体库**：扫描电脑、移动硬盘及 NAS 的照片视频，汇总到一处本地媒体库。
- 📱 **手机自动备份**：手机 App 与桌面端配对，自动把 Android/iOS 相册原图备份到电脑。
- 🗓️ **时间轴浏览**：按拍摄时间自动整理，快速跳转日期并流畅浏览大图库。
- 😀 **人脸识别**：自动聚合同一人物，支持命名、搜索与多人合影查找。
- 🔍 **AI 以文搜图**：用自然语言描述内容即可精准检索照片和视频。
- 🧹 **重复清理**：检测本地与 NAS 间的重复文件，并支持一键移动到回收站。
- 📁 **保留目录结构**：按本地目录展示，可直接移动、复制、删除和重命名文件。
- 🗺️ **地图回忆**：按地理位置在地图上回看照片，位置信息仅存本地。
- 📚 **主题相册**：把不同来源的照片归入相册，组织展示而不移动原文件。
- 🔒 **隐私承诺**：照片永远留在本地，不上传云端，充分尊重、保障您的隐私安全。

![Screenshot: desktop app](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/self-photos-screenshot.png?raw=true)

> 👏 扫码关注微信公众号，加入交流群，获取最新内部信息和福利。
>
> <img src="https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/wechat-qrcode.jpg?raw=true" alt="Wechat QR Code" height="150">

## 一、扫描PC/Mac/Linux硬盘照片，以及NAS照片（未来还有云存储），并汇总到一处展示

爱看相册可以扫描电脑、移动硬盘以及 NAS 中的照片和视频，把分散在不同位置的回忆统一索引为一个本地媒体库。

- **构建统一本地媒体库**：自动提取照片 EXIF 中的拍摄时间、位置等信息，并在时间轴、地图页面展示
- **扫描 NAS 内媒体文件**：可直接通过 SMB 扫描和索引 NAS 上的照片视频，无需先把文件复制到本机
- **灵活的扫描规则**：支持指定扫描路径、排除文件夹、嵌套路径规则。设置大小阈值以过滤图标、缓存图等小图
- **文件监控与手动扫描**：实时监控本地硬盘媒体变化（新增、删除、移动），并快速自动更新媒体库；非本地数据源（NAS）可一键扫描更新媒体库
- **Live Photo 自动识别**：检测到相同目录内一张照片和一个视频的文件名相同，则软件内自动关联为 Live Photo

![Screenshot: scan select](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/scan-screenshot.png?raw=true)

## 二、手机相册自动备份到电脑

手机安装“爱看相册”App 后，与同一局域网内的桌面端配对，就可以把 Android 和 iOS 设备中的照片视频备份到电脑或外接硬盘。

- **自动备份**：指定手机相册后，新照片和视频可自动同步到电脑
- **按日期范围备份**：只备份最近一段时间的照片视频，也可选择全部时间范围的照片
- **按类型自动备份**：可以只备份照片，或只备份视频，或者默认两者都备份
- **原图原视频保存**：不压缩、不降低画质，保留完整细节
- **多设备独立管理**：可为不同手机设置不同备份目录，并支持按规则生成子文件夹和文件名，例如 `E:/Backup/iPhone 16 Pro Max/2025/2025-12/2025.12.01_IMG_1234.jpg`
- **局域网传输**：传输不消耗移动流量，速度取决于你的本地网络和硬盘性能

![Screenshot: mobile app](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/screenshot-mobile.png?raw=true)

## 三、按拍摄时间整理时间轴

爱看相册会根据照片、视频的实际拍摄时间自动整理媒体库，整理过程中会自动解析照片视频内的 EXIF 元数据以提取准确拍摄时间。

- **快速跳转日期**：通过时间轴和日期定位，迅速跳到某年某月某日
- **丝滑浏览大图库**：充分优化的桌面体验，即使面对**百万级**照片库也能流畅使用
- **悬浮预览**：鼠标悬停即可快速预览照片和视频，大幅提升筛选与浏览效率
- **内置视频播放器**：直接在应用中播放视频，支持格式取决于系统解码器

![Screenshot: timeline](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/timeline.png?raw=true)

## 四、人脸识别

爱看相册可以智能识别照片、视频中的人脸，把同一人物自动聚合成一个可管理的人物，供时间轴、目录等页面统一使用。

- **自动聚合人脸**：智能识别照片、视频中的人脸，并把同一人物的多张人脸自动合并为一个人，集中展示
- **人物命名与置顶**：可为识别出的人物设置名称并置顶，方便快速找到重要的人
- **按人物搜索**：可在软件内任意照片列表中按人物搜索照片和视频
- **多人合影搜索**：支持同时选择多个人物，快速找到包含这些人的合影
- **隐藏不想看到的人**：不希望在浏览中出现的人物可以一键隐藏
- **自定义人物封面**：可为每个人物切换封面图，选出最有代表性的一张

![Screenshot: timeline](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/face-recognition.png?raw=true)

## 五、AI图像识别及以文搜图

爱看相册内置 AI 模型，能够理解照片、视频中的内容，并支持用自然语言直接检索媒体库。

- **AI 内容识别**：AI 模型智能识别照片、视频中的主体、场景和细节，为以文搜图提供基础
- **自然语言搜索**：输入自然语言即可搜索与之匹配的照片和视频，无需手动打标签
- **长句精准定位**：可以放心搜索长句子，例如“小孩在玩一个蓝色的气球，背后是他的父母在亲吻”，AI 会准确找到目标照片并排在结果首位
- **智能分类**：常见主题默认完成分类，打开后即可直接查看结果

![Screenshot: timeline](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/vision-search.png?raw=true)

## 六、重复文件检测与一键清理

- **重复文件检测**：智能识别重复照片和视频，即使是本地磁盘与 NAS 之间的重复照片，也能检测出来
- **统计重复文件所在目录**：自动按重复文件所在的目录名进行聚合，方便一个目录一个目录查看并清理。这也符合现实世界中重复照片的特征，重复文件往往出现在两个相同的目录中
- **手动选择和自动选择**：每个重复组，你可以手动选择要删除的照片，或者按文件名、路径名、文件大小、重复数量排序后，选择保留每组第一个、最后一个，或当前目录中的文件，从而快速选择
- **一键清理**：在批量选择后，可以点击将所选照片全部移动到回收站，完成清理。对于 SMB 上的文件，没有回收站的概念，会弹出提示是否彻底删除，避免失去反悔恢复的机会。

![Screenshot: duplicate detection](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/duplicate.png?raw=true)

## 七、按本地目录结构展示/操作

Google Photos、Immich 等在线照片管理服务，都在淡化“目录结构”的概念，而作为一个本地照片管理软件，我们非常尊重您已有的目录结构，因为它很可能承载你过去对照片的整理记录（目录归类、文件命名等），所以：

- **数据源页面按目录展示**：数据源页面默认按目录层级展示，清楚呈现文件所在的目录结构
- **像资源管理器/访达一样可操作**：移动、复制、删除、重命名都可以在软件内完成，不用再去资源管理器或访达里操作了
- **未来 Agent 感知目录层级**：未来照片管理 Agent 上线后，会感知目录层级，并以此作为上下文，更好地识别照片并协助你整理

![Screenshot: folder view](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/folder.png?raw=true)

## 八、在地图上查看回忆

如果照片包含地理位置信息，爱看相册可以把它们呈现在地图上。

- **按地点回看照片**：从地图上的位置快速找到当时拍摄的照片视频
- **隐私优先**：位置信息只在本地用于索引和展示，不会上传到云端

![Screenshot: map](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/map-screenshot.png?raw=true)

## 九、相册功能

除了自动按时间、地点、目录组织，爱看相册也提供全新的相册功能，适合把旅行、家庭、项目、节日或某个主题的照片主动收集起来。

- **创建主题相册**：把分散在不同来源、不同日期的照片视频整理到同一个相册中
- **保留原文件位置**：相册用于组织和展示，不需要移动原始文件
- **适合长期收藏**：婚礼、宝宝成长、旅行合集、作品素材等都可以独立成册

![Screenshot: album](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/album.png?raw=true)

## 十、对隐私的郑重承诺

- **隐私第一**：爱看相册坚持本地优先、隐私之上的原则，您的照片资产永远在本地，不会上传到云端，包括元信息。
- **安全保障**：绝对不会修改、删除你的照片，除非你在软件内整理照片时需要这么做。而且默认都只会移动到回收站或废纸篓，让你的误操作还有反悔的机会。

# ⬇️ 下载

- Github(Desktop only): <a href="https://github.com/SelfPhotos/SelfPhotos/releases/latest">https://github.com/SelfPhotos/SelfPhotos/releases/latest</a>
- 官网(Desktop & Android/iOS APP): <a href="https://selfphotos.com/download">https://selfphotos.com/download</a>

# 关注我们

- 扫码关注微信公众号，通过公众号菜单栏加入群聊
<img src="https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/wechat-qrcode.jpg?raw=true" alt="Wechat QR Code" height="150">
