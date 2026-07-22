# Tabview YouTube Totara

[English](./README.md) | **日本語** | [中文](./README.zh-TW.md)

[![Tampermonkey](https://img.shields.io/badge/Tampermonkey-OK-006989?labelColor=012A36)](https://www.tampermonkey.net/)
[![Violentmonkey](https://img.shields.io/badge/Violentmonkey-OK-006989?labelColor=4B3F72)](https://violentmonkey.github.io/)
[![FireMonkey](https://img.shields.io/badge/FireMonkey-Partial-1b0852?labelColor=885053)](https://addons.mozilla.org/firefox/addon/firemonkey/)
[![Greasemonkey](https://img.shields.io/badge/Greasemonkey-NG-888?labelColor=A2A392)](https://www.greasespot.net/)
[![Stay](https://img.shields.io/badge/Stay-OK-006989?labelColor=a34598)](https://stay.app/)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](https://spdx.org/licenses/MIT.html)

> **お知らせ：** [Tabview YouTube Totara](https://greasyfork.org/scripts/501249-tabview-youtube-totara) は [Tabview YouTube](https://greasyfork.org/scripts/428651) の再設計版 (v5) です。
>
> **重要：** 必ず **greasyfork.org** からスクリプトをインストールしてください。偽サイトからはインストールしないでください。

---

## インストール

[スクリプトをインストール](https://update.greasyfork.org/scripts/501249/Tabview%20YouTube%20Totara.user.js)

[Tampermonkey](https://www.tampermonkey.net/)、[Violentmonkey](https://violentmonkey.github.io/)、または [FireMonkey](https://addons.mozilla.org/firefox/addon/firemonkey/) などのユーザースクリプトマネージャーが必要です。Tampermonkey を使用する場合、Chrome/Chromium でデベロッパーモードを有効にする必要があります。

---

## 無効化された実験的フラグ

### 有効中

- `web_watch_chat_hide_button_killswitch = false`
- `web_watch_theater_chat = false`
- `suppress_error_204_logging = true`
- `kevlar_watch_grid = false`

### レガシー — 保持しておいてください。YouTube はすでに失敗した設計を放棄しています

- `enable_shadydom_free_scoped_node_methods = false`
- `enable_shadydom_free_scoped_query_methods = false`
- `enable_shadydom_free_scoped_readonly_properties_batch_one = false`
- `enable_shadydom_free_parent_node = false`
- `enable_shadydom_free_children = false`
- `enable_shadydom_free_last_child = false`

---

## Userscript マネージャー & 最小ブラウザバージョン

| マネージャー | ステータス |
|---|---|
| Tampermonkey | ✅ OK |
| Violentmonkey | ✅ OK |
| FireMonkey | ⚠️ Partial |
| Greasemonkey | ❌ NG |
| Stay | ✅ OK |

### ブラウザ

| ブラウザ | 最小バージョン | 推奨バージョン |
|---|---|---|
| Chrome | 61 | 84+ |
| Edge | 79 | 84+ |
| Firefox | 55 | 79+ |
| Opera | 48 | 70+ |
| Safari | 12.1 | 14.1.2+ |

---

## 関連 URL

- [MIT ライセンス](https://github.com/cyfung1031/Tabview-Youtube/blob/main/LICENSE)
- [Tabview YouTube GitHub](https://github.com/cyfung1031/Tabview-Youtube)
- [UserCSS: Tabview YouTube デザインカスタマイズ](https://greasyfork.org/scripts/467638-tabview-youtube-design-customization/)
- [UserCSS: YouTube Watch フレキシブルメニュー項目の修正](https://greasyfork.org/en/scripts/475124-fix-youtube-watch-flexible-menu-items)
- [旧 Readme](https://github.com/tabview-youtube/Tabview-YouTube-Totara/blob/main/docs/old.md)

---

## 機能

1. **タブ表示レイアウト：** 情報、コメント、動画、プレイリストが右側のタブに整理されます（2カラムレイアウトの場合）。
2. **レイアウト切替：** ミニビュー再生付きの閲覧/検索レイアウトに切り替えることができます（プレイリストが存在する場合、デフォルトで利用可能）。

### 完全には利用できない機能 / 確認中の機能

1. **YouTube バグ修正：** 日本語レイアウトで切り詰められるチャンネル名や、超ワイドな動画のサイドパネルの問題など、ネイティブなバグに対処します。
2. **CSS 強化：** レンダリングパフォーマンスを向上させるために複数の CSS 調整を実施しています。
3. **動画情報の強化：** 動画タイトルにカーソルを合わせると、ライブストリームの日時や再生時間が表示されます。

### 既知の問題

1. デフォルトタブ選択機能はまだ実装されていません。
2. ドネーションパネルの問題は未確認です。
3. 動画またはページ切替後に、折りたたまれたタブコンテナが自動で展開されない場合があります。

---

## 推奨される関連スクリプト / 拡張機能

- **Tabview YouTube：** （コア機能）
- **Live Borderless & Video Resize Fix：**
  - [YouTube Live Borderless](https://greasyfork.org/scripts/457317-youtube-live-borderless)
  - [YouTube Video Resize Fix](https://greasyfork.org/scripts/457319-youtube-video-resize-fix)
- **チャット機能強化：**
  - [YouTube Chat Bubbles](https://greasyfork.org/scripts/457375-youtube-chat-bubbles)
  - [YouTube Chat Tints](https://greasyfork.org/scripts/457391-youtube-chat-tints)
- **パフォーマンス向上ツール：**
  - [YouTube CPU Tamer by AnimationFrame](https://greasyfork.org/scripts/431573-youtube-cpu-tamer-by-animationframe)
  - [YouTube Super Fast Chat](https://greasyfork.org/scripts/469878-youtube-super-fast-chat)
  - [YouTube JS Engine Tamer](https://greasyfork.org/scripts/473972-youtube-js-engine-tamer)
- **オーディオ強化：**
  - [YouTube: Audio Only](https://greasyfork.org/scripts/484611-youtube-audio-only)
  - [Disable YouTube AutoPause (Desktop)](https://greasyfork.org/scripts/457219-disable-youtube-autopause)
- **ミュージックモード強化：**
  - [YouTube Music: Audio Only](https://greasyfork.org/scripts/486384-youtube-music-audio-only)
  - [Disable YouTube AutoPause (Music)](https://greasyfork.org/scripts/464888-disable-youtube-music-autopause)
- **機能調整：**
  - [YouTube: Quality Auto Max](https://greasyfork.org/scripts/483406-youtube-quality-auto-max)
  - [AutoPlay Next More Than 3 Seconds](https://greasyfork.org/scripts/475579-youtube-make-autoplay-next-more-than-3-seconds)
  - [Exit Fullscreen on Video End](https://greasyfork.org/scripts/469750-youtube-exit-fullscreen-on-video-end)
- **ユーザー名復元：** [Restore YouTube Username](https://greasyfork.org/scripts/468740-restore-youtube-username-from-handle-to-custom)
- **リソース管理：** [Unhold YouTube Resource Locks](https://greasyfork.org/scripts/457205-unhold-youtube-resource-locks)
- **設定リセット：** [Reset YouTube Settings](https://greasyfork.org/scripts/457255-reset-youtube-settings)
- **AV1 強制再生：** [Force YouTube AV1](https://greasyfork.org/scripts/466127-force-youtube-av1)

> **ヒント：** 古いマシンで最小限の CPU 使用で YouTube を視聴したい場合は、[YouTube Minimal on PC](https://greasyfork.org/en/scripts/457579-youtube-minimal-on-pc) と [YouTube Minimal Fixs](https://greasyfork.org/en/scripts/457587-youtube-minimal-fixs) をお試しください。

---

## スクリーンショット（旧版。参考用）

### プレビュー（ダークテーマ — 2カラム）

#### シアターモード

![Theater Mode 1](https://na.cx/i/MMw4whT.png)
![Theater Mode 2](https://na.cx/i/4mboMRc.png)

#### ライブチャット — ライブ / リプレイ

![Live Chat 1](https://na.cx/i/yKfkO4y.png)
![Live Chat 2](https://na.cx/i/tvktdwd.png)

#### 動画情報

![Video Info 1](https://na.cx/i/6cyuHqt.png)
![Video Info 2](https://na.cx/i/NePBnqt.png)
![Video Info 3](https://na.cx/i/1EpBnqu.png)

#### 通常コメントモード

![Comments 1](https://na.cx/i/vHpRbiO.png)
![Comments 2](https://na.cx/i/8qparR8.png)

#### 関連動画

![Related Videos 1](https://na.cx/i/bH0Ekda.png)
![Related Videos 2](https://na.cx/i/gwAtdya.png)

#### プレイリスト

![Playlist 1](https://na.cx/i/YexWnrv.png)
![Playlist 2](https://na.cx/i/Nm9qfMv.png)

#### チャプター＆キャプション

![Chapter/Captions 1](https://na.cx/i/AYMj4EQ.png)
![Chapter/Captions 2](https://na.cx/i/Bd4xFda.png)

---

## 変更履歴

> **注意：** 以下の変更履歴は Tabview YouTube の旧バージョンに基づいています。Tabview YouTube Totara (v5) は、さらなる改善を加えた再設計版です。

### v5.0 (ベータ) — [5.0.054](https://greasyfork.org/ja/scripts/501249-tabview-youtube-totara) @ 2025年3月

- コア機能の実装

---

## サポート対象プラットフォーム

### Userscript マネージャー

- **推奨：** Violentmonkey 2.16.2 以降
- **対応：** Tampermonkey（クローズドソース）
- **部分対応：** FireMonkey（機能制限のため非推奨）

### ブラウザ

- **Chromium系：** Chrome, Edge, Brave, Cent (Blink 66+)
- **Webkit系：** Orion Version 0.99.126.4.1 Beta 以降
- **Gecko系：** Firefox 57+、Waterfox、Librefox、Waterfox Classic

---

## 備考

- **着想元：** ソースコードとデザインはもともと [SuperYouTube](https://chrome.google.com/webstore/detail/superyoutube-extension-fo/nojdofjkkahhdklccleaaeinfklmlaga) に触発されましたが、大幅な改善（ダーク/ライトテーマ対応など）を施しています。この Userscript は SuperYouTube とは無関係です。
- **動機：** SuperYouTube と比較して設定を簡素化し、RAM 使用量を削減するとともに、バグとパフォーマンス問題を解決するために作成されました。
- **パフォーマンス：** `contain` や `content-visibility` など、多くの CSS ハックがパフォーマンス向上のために利用されています。これらのハックが他の Userscript やプラグインに干渉する場合は、報告してください。
- 旧バージョンは、YouTube エンジンの変更や根本的な設計の誤りによりバグが多く発生しています。

---

## 互換性

### 対応 Userscript マネージャー

- Tampermonkey（およびそのベータ版）
- ViolentMonkey

### 対応ウェブブラウザ（デスクトップ）

Chrome, Chromium, Edge, Firefox, Waterfox, LibreWolf, Brave, Safari, Waterfox Classic, Vivaldi, Opera, Cent, Catsxp, Maxthon

> **注意：** Waterfox Classic（Firefox 55/56）の場合は、[ViolentMonkey](https://addons.mozilla.org/en-US/firefox/addon/violentmonkey/) または [Tampermonkey 4.8.5847](https://addons.mozilla.org/firefox/downloads/file/1076900/tampermonkey-4.8.5847.xpi) を使用してください。

### 対応 YouTube 機能

- [360° 動画](https://www.youtube.com/watch?v=2h3pbdTPu6Q)
- ミニプレイヤービュー
- モダンダークレイアウト
- プレイリストの行ハイライト（2022年末に導入）

### 対応拡張機能 & プラグイン

- [Maximize Video](https://greasyfork.org/scripts/4870) の ESC Video Full Page
- [YouTube - Search While Watching Video](https://greasyfork.org/scripts/29451-youtube-search-while-watching-video) のインページ検索
- [YouTubeLiveClock](https://chrome.google.com/webstore/detail/youtubeliveclock/chpodcedholiggcllnmmjlnghllddgmj) (Chrome 105+)
- [Youtube Genius Lyrics](https://greasyfork.org/en/scripts/386259-youtube-genius-lyrics)
- [YouTube Comment Translation Button](https://greasyfork.org/scripts/456108)
- [YouTube Livestreams Theater Mode](https://www.napalighost.com/youtube-livestreams-theater-mode)

### 非互換

- DanMage <= 5.3.1

---

## ライセンス

[MIT](https://github.com/cyfung1031/Tabview-Youtube/blob/main/LICENSE)
