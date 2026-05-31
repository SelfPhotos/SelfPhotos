<h1 align="center">
  <img src="https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/logo.png?raw=true" height="80" alt="Self Photos Logo" />
  <p>Self Photos</p>
</h1>

<p align="center"><a href="./README.md">English</a> | <a href="./README.zh.md">中文</a> | <a href="./README.de.md">Deutsch</a> | <a href="./README.es.md">Español</a> | <a href="./README.fr.md">Français</a> | <a href="./README.hi.md">हिन्दी</a> | <a href="./README.it.md">Italiano</a> | 日本語 | <a href="./README.pt.md">Português</a> | <a href="./README.ru.md">Русский</a></p>

**Self Photos** は Rust で作られた**クロスプラットフォームの写真・動画管理ツール**で、Windows、macOS、Linux（近日対応）、Android、iOS で利用できます。

自分の端末向けの、完全にローカルな Google Photos だと考えてください。パソコン、外付けドライブ、NAS、スマホから写真や動画を整理しながら、プライバシーと管理権を最優先にします。メディアはクラウドにアップロードされず、あなた自身の端末に残ります。

![Screenshot: desktop app](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/self-photos-screenshot.png?raw=true)

> 👏 [Discord](https://discord.gg/VCqXcAz6Js) に参加 | [X(Twitter)](https://x.com/wikkefly) でフォロー

# ✨ 主な機能

## 1. ばらばらの写真と動画をまとめる

Self Photos は、パソコン、外付けドライブ、接続済みディスク、NAS から写真と動画をスキャンし、ひとつのローカルなメディアライブラリにまとめます。

- **ワンクリックスキャン**: パソコン上の写真と動画をすばやく見つけ、撮影日時、場所、メディア種類などのメタデータを自動抽出
- **柔軟なデータソース**: ローカルフォルダ、外付けドライブ、ネットワーク上の場所などを追加可能。旧フォルダ画面は、より分かりやすいデータソース画面と改善されたフォルダ一覧に刷新されています
- **SMB 対応**: NAS 上の写真と動画を、先にコピーせず SMB で直接スキャンしてインデックス化
- **柔軟なスキャンルール**: スキャンパスの指定、フォルダ除外、ネストしたパスルールの設定、アイコンやキャッシュ画像など不要な小さいファイルのサイズフィルタが可能
- **ファイル監視と手動スキャン**: ローカルデータソースはリアルタイム監視と自動更新に対応し、非ローカルデータソースは必要に応じて手動でスキャン可能
- **Live Photo 検出**: データソースをまたいで Live Photo を自動検出して結び付け、静止画と動きのあるクリップを一緒に保ちます

![Screenshot: scan select](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/scan-screenshot.png?raw=true)

## 2. モバイルのアルバムをパソコンへバックアップ

Self Photos のモバイルアプリをインストールしたら、同じローカルネットワーク上でデスクトップアプリとペアリングして、Android と iOS の写真や動画をパソコンや外付けドライブにバックアップできます。

- **接続してバックアップ**: モバイルアルバムを選ぶと、新しい写真や動画を自動でパソコンへ同期
- **手動バックアップ**: 必要なときに特定の写真や動画だけを選んでバックアップ
- **期間指定バックアップ**: 最近の写真や動画だけを保存でき、新しいコンテンツの整理に便利
- **オリジナル品質**: 圧縮や画質低下なしで元の写真と動画を保存
- **複数端末を個別管理**: 端末ごとに別のバックアップフォルダを設定でき、サブフォルダやファイル名のルールも指定可能。例: `E:/Backup/iPhone 16 Pro Max/2025/2025-12/2025.12.01_IMG_1234.jpg`
- **ローカルネットワーク転送**: バックアップにモバイルデータは使わず、速度はローカルネットワークとディスク性能に依存

![Screenshot: mobile app](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/screenshot-mobile.png?raw=true)

## 3. タイムラインで思い出を振り返る

Self Photos は写真と動画の実際の撮影時刻でライブラリを整理するので、日記をめくるように特定の日、月、年へ戻れます。

- **撮影日で自動整理**: ファイル作成日時ではなく、実際の撮影時刻で並べ替え
- **すばやい日付ジャンプ**: タイムラインと日付ナビゲーションで特定の年や月へすぐ移動
- **大規模ライブラリでも滑らか**: 数十万枚規模でも快適に使えるよう最適化されたデスクトップ体験
- **ホバーでプレビュー**: マウスを乗せるだけで写真と動画を素早く確認でき、閲覧と絞り込みがより速くなる
- **内蔵ビデオプレーヤー**: アプリ内で動画を直接再生。対応形式はシステムのコーデックに依存
- **複数の見方**: タイムライン、元のフォルダ構造、お気に入り、システム標準アプリ、またはファイルマネージャーで場所を表示

![Screenshot: timeline](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/timeline.png?raw=true)

## 4. アルバムで大切な瞬間を整理する

時間やフォルダ構造による自動整理に加えて、Self Photos には旅行、家族、プロジェクト、休暇、テーマ別のメディアを集めるアルバム機能があります。

- **テーマ別アルバムを作成**: 異なる場所や日付の写真と動画を 1 つのアルバムにまとめる
- **元のファイルはそのまま**: アルバムはメディアを整理して表示するだけで、元ファイルは移動しない
- **長期コレクション向け**: 結婚式、子どもの成長、旅行セット、制作素材など、それぞれ独立したアルバムにできる

![Screenshot: album](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/album.png?raw=true)

## 5. 整理して管理し、新しいデスクトップ体験を楽しむ

Self Photos は見るだけのアプリではありません。メディアライブラリをより効率よく管理する助けにもなります。

- **重複検出**: 重複した写真や動画を賢く見つけ、プレビューしてまとめて削除し、ライブラリを整理
- **新しいデザインシステム**: 大規模な写真・動画ライブラリを長期管理するための、よりモダンな UI とデスクトップ体験
- **お気に入りと比較プレビュー**: 大切なメディアを素早くお気に入りにし、プレビューページで写真を並べて比較
- **無制限の保存容量と速度**: 容量はディスク次第、転送速度はローカルネットワークとデバイス性能次第
- **プライベートで安全**: アプリはオフラインで動作し、写真と動画は端末の外に出ません。モバイルバックアップも同じローカルネットワーク上にあるだけで使えます

![Screenshot: duplicate detection](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/duplicate.png?raw=true)

# ⬇️ ダウンロード

最新の **デスクトップインストーラ** と **モバイルアプリ** は公式サイトから入手できます: [https://selfphotos.com/download](https://selfphotos.com/download)
