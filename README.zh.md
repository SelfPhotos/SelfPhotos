<h1 align="center">
  <img src="https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/logo.png?raw=true" height="80" alt="Aicasa Logo" />
  <p>爱看相册</p>
</h1>

<p align="center"><a href="https://github.com/SelfPhotos/SelfPhotos">English</a> | 中文</p>

**爱看相册**是一款由 Rust 打造的**跨平台照片/视频管理工具**，支持 Windows, Macos 和 Linux(即将发布)，以及安卓，iOS。

它就像一个完全本地化的 Google 相册 —— 但更注重隐私与掌控，所有照片都只存放在你自己的设备中。

> 👏 扫码关注微信公众号，获取下载链接，抢先体验测试版最新功能，AI功能版也会第一时间在群里发出
> 
> <img src="https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/wechat-qrcode.jpg?raw=true" alt="Wechat QR Code" height="150">


# ✨ 特色功能

## 一、扫描电脑及移动硬盘照片/视频

- 自定义扫描路径
- 支持扫描网络驱动器，比如通过SMB映射到本地的网路驱动器(Windows)或目录(Unix)
- 支持嵌套扫描路径规则，比如扫描路径下指定排除文件夹；排除文件夹下添加可扫描字路径
- 设置扫描照片或视频的阈值，小于该阈值则不显示，以排除图标，缓存图片等
- Rust语言的极致性能和安全性，保障了您丝滑的用户体验
- 解析并提取照片视频的元信息，根据拍摄时间来整理媒体库，并提供时间轴浏览
- 支持收藏功能
- 支持从系统默认应用打开照片或视频
- 支持定位并打开照片所在系统的文件夹
- 如同曾经Google Picasa软件的功能，不过它现在已被Google下架

## 二、手机相册备份到电脑

- 手机安装“爱看相册”APP后，与同局域网内桌面端匹配
- 支持自动备份：指定的手机相册会自动备份到电脑
- 支持手动备份：手动选择照片并备份
- 桌面端可为不同手机设备，设置不同的备份路径
- 支持备份路径下的**子文件夹**和**照片名称**按规则命名，比如"E:/Backup/iPhone 16 Pro Max/2025/2025-12/2025.12.01_IMG_1234.jpg"
- 支持多个并发同时上传照片视频

## 三、Google相册一样的丝滑浏览体验

- 支持按**拍摄日期**的时间轴浏览
- 支持自定义滚动条，快速定位到某年某月
- 以照片所在操作系统的目录，以熟悉的目录结构展示照片
- 缩略图可按照片真实比例展示，或裁剪为中间内容的正方形
- 充分优化的程序，在几十万张照片下仍然极致丝滑
- 预览页面可左右分屏预览以对比

## 四、隐私至上

- 软件在离线情况下可以正常使用
- 您的照片，视频不会传递到云端，软件仅索引该照片并展示
- 手机相册备份功能，需要和桌面端连接到相同的局域网（该网路可以不连通互联网）

## 五、无限存储，无限速度

- 手机备份到电脑的存储仅仅受限于你硬件磁盘的可用容量，软件不会做任何限制
- 手机备份照片视频，或浏览照片视频，不会做速度限制，你可以跑慢局域网带宽
- 不限制容量，不限制速度，并且，都是免费提供给您，因为那是您的设备和网络

# 🌠 截图

## 手机APP

![Screenshot: mobile app](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/screenshot-mobile.png?raw=true)

<p align="center">手机APP界面</p>

## 桌面端

![Screenshot 1](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/screenshot-1.png?raw=true)

<p align="center">时间轴</p>

![Screenshot 2](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/screenshot-2.png?raw=true)

<p align="center">保留目录结构</p>

![Screenshot 3](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/screenshot-3.png?raw=true)

<p align="center">浅色/深色模式预览</p>

![Screenshot: Pairing mobile with desktop](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/screenshot-pairing.png?raw=true)

<p align="center">连接桌面端，并设置备份目录，子文件夹和文件命名规则</p>

![Screenshot: importing photos from mobile device](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/screenshot-importing.png?raw=true)

<p align="center">从手机APP备份照片</p>

# ⬇️ 下载

- (推荐)扫码关注微信公众号，获取最新 **桌面端程序** 和 **移动端APP** **稳定版**下载链接，点击公众号菜单栏入群，可获取最新信息和**内测版**下载链接<br />
<img src="https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/wechat-qrcode.jpg?raw=true" alt="Wechat QR Code" height="150">
- 从官网网站 <a href="https://aikanxiangce.com/download">https://aikanxiangce.com/download</a> 下载
