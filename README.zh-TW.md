# Tabview YouTube Totara

[English](./README.md) | [日本語](./README.ja.md) | **中文**

[![Tampermonkey](https://img.shields.io/badge/Tampermonkey-OK-006989?labelColor=012A36)](https://www.tampermonkey.net/)
[![Violentmonkey](https://img.shields.io/badge/Violentmonkey-OK-006989?labelColor=4B3F72)](https://violentmonkey.github.io/)
[![FireMonkey](https://img.shields.io/badge/FireMonkey-Partial-1b0852?labelColor=885053)](https://addons.mozilla.org/firefox/addon/firemonkey/)
[![Greasemonkey](https://img.shields.io/badge/Greasemonkey-NG-888?labelColor=A2A392)](https://www.greasespot.net/)
[![Stay](https://img.shields.io/badge/Stay-OK-006989?labelColor=a34598)](https://stay.app/)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](https://spdx.org/licenses/MIT.html)

> **注意：** [Tabview YouTube Totara](https://greasyfork.org/scripts/501249-tabview-youtube-totara) 是 [Tabview YouTube](https://greasyfork.org/scripts/428651) 重新設計的 v5 版本。
>
> **重要：** 請務必從 **greasyfork.org** 安裝此腳本，不要從假冒網站下載。

---

## 安裝

[安裝腳本](https://update.greasyfork.org/scripts/501249/Tabview%20YouTube%20Totara.user.js)

您需要一個使用者腳本管理器擴充功能：[Tampermonkey](https://www.tampermonkey.net/)、[Violentmonkey](https://violentmonkey.github.io/) 或 [FireMonkey](https://addons.mozilla.org/firefox/addon/firemonkey/)。使用 Tampermonkey 時，Chrome/Chromium 需要啟用開發者模式。

---

## 已停用的實驗性旗標

### 啟用中

- `web_watch_chat_hide_button_killswitch = false`
- `web_watch_theater_chat = false`
- `suppress_error_204_logging = true`
- `kevlar_watch_grid = false`

### 遺留項目 — 請保留。YouTube 已經放棄了這些失敗的設計

- `enable_shadydom_free_scoped_node_methods = false`
- `enable_shadydom_free_scoped_query_methods = false`
- `enable_shadydom_free_scoped_readonly_properties_batch_one = false`
- `enable_shadydom_free_parent_node = false`
- `enable_shadydom_free_children = false`
- `enable_shadydom_free_last_child = false`

---

## Userscript 管理器 & 最低瀏覽器版本

| 管理器 | 狀態 |
|---|---|
| Tampermonkey | ✅ OK |
| Violentmonkey | ✅ OK |
| FireMonkey | ⚠️ Partial |
| Greasemonkey | ❌ NG |
| Stay | ✅ OK |

### 瀏覽器

| 瀏覽器 | 最低版本 | 推薦版本 |
|---|---|---|
| Chrome | 61 | 84+ |
| Edge | 79 | 84+ |
| Firefox | 55 | 79+ |
| Opera | 48 | 70+ |
| Safari | 12.1 | 14.1.2+ |

---

## 相關網址

- [MIT 授權條款](https://github.com/cyfung1031/Tabview-Youtube/blob/main/LICENSE)
- [Tabview YouTube GitHub](https://github.com/cyfung1031/Tabview-Youtube)
- [UserCSS：Tabview YouTube 設計自訂](https://greasyfork.org/scripts/467638-tabview-youtube-design-customization/)
- [UserCSS：修正 YouTube Watch 彈性選單項目](https://greasyfork.org/en/scripts/475124-fix-youtube-watch-flexible-menu-items)
- [舊版 Readme](https://github.com/tabview-youtube/Tabview-YouTube-Totara/blob/main/docs/old.md)

---

## 功能

1. **分頁式佈局：** 資訊、留言、影片和播放清單將依照分頁方式顯示在右側（適用於雙欄佈局）。
2. **佈局切換：** 可切換到帶有迷你播放視圖的瀏覽/搜尋佈局（當存在播放清單時，預設可用）。

### 尚未完全提供 / 待確認的功能

1. **YouTube 錯誤修正：** 修正如日本語佈局中頻繁截斷的頻道名稱及超寬影片側邊欄等 YouTube 原生錯誤。
2. **CSS 強化：** 多項 CSS 調整以提升渲染效能。
3. **影片資訊增強：** 當滑鼠懸停於影片標題時，顯示直播日期/時間及播放時長。

### 已知問題

1. 預設分頁選擇功能尚未實作。
2. 捐贈面板問題尚未確認。
3. 有時影片或頁面切換後，摺疊的分頁容器不會自動展開。

---

## 推薦的相關腳本 / 擴充功能

- **Tabview YouTube：**（核心功能）
- **Live Borderless 與 Video Resize Fix：**
  - [YouTube Live Borderless](https://greasyfork.org/scripts/457317-youtube-live-borderless)
  - [YouTube Video Resize Fix](https://greasyfork.org/scripts/457319-youtube-video-resize-fix)
- **聊天室功能增強：**
  - [YouTube Chat Bubbles](https://greasyfork.org/scripts/457375-youtube-chat-bubbles)
  - [YouTube Chat Tints](https://greasyfork.org/scripts/457391-youtube-chat-tints)
- **效能工具：**
  - [YouTube CPU Tamer by AnimationFrame](https://greasyfork.org/scripts/431573-youtube-cpu-tamer-by-animationframe)
  - [YouTube Super Fast Chat](https://greasyfork.org/scripts/469878-youtube-super-fast-chat)
  - [YouTube JS Engine Tamer](https://greasyfork.org/scripts/473972-youtube-js-engine-tamer)
- **音效增強：**
  - [YouTube: Audio Only](https://greasyfork.org/scripts/484611-youtube-audio-only)
  - [Disable YouTube AutoPause (Desktop)](https://greasyfork.org/scripts/457219-disable-youtube-autopause)
- **音樂模式增強：**
  - [YouTube Music: Audio Only](https://greasyfork.org/scripts/486384-youtube-music-audio-only)
  - [Disable YouTube AutoPause (Music)](https://greasyfork.org/scripts/464888-disable-youtube-music-autopause)
- **功能調整：**
  - [YouTube: Quality Auto Max](https://greasyfork.org/scripts/483406-youtube-quality-auto-max)
  - [AutoPlay Next More Than 3 Seconds](https://greasyfork.org/scripts/475579-youtube-make-autoplay-next-more-than-3-seconds)
  - [Exit Fullscreen on Video End](https://greasyfork.org/scripts/469750-youtube-exit-fullscreen-on-video-end)
- **使用者名稱還原：** [Restore YouTube Username](https://greasyfork.org/scripts/468740-restore-youtube-username-from-handle-to-custom)
- **資源管理：** [Unhold YouTube Resource Locks](https://greasyfork.org/scripts/457205-unhold-youtube-resource-locks)
- **設定重置：** [Reset YouTube Settings](https://greasyfork.org/scripts/457255-reset-youtube-settings)
- **強制 AV1 播放：** [Force YouTube AV1](https://greasyfork.org/scripts/466127-force-youtube-av1)

> **提示：** 若您需要在舊電腦上以最低 CPU 使用率觀看 YouTube，請試試 [YouTube Minimal on PC](https://greasyfork.org/en/scripts/457579-youtube-minimal-on-pc) 以及 [YouTube Minimal Fixs](https://greasyfork.org/en/scripts/457587-youtube-minimal-fixs)。

---

## 截圖（舊版，僅供參考）

### 預覽（暗色主題 — 雙欄）

#### 劇院模式

![Theater Mode 1](https://na.cx/i/MMw4whT.png)
![Theater Mode 2](https://na.cx/i/4mboMRc.png)

#### 即時聊天室 — 直播 / 重播

![Live Chat 1](https://na.cx/i/yKfkO4y.png)
![Live Chat 2](https://na.cx/i/tvktdwd.png)

#### 影片資訊

![Video Info 1](https://na.cx/i/6cyuHqt.png)
![Video Info 2](https://na.cx/i/NePBnqt.png)
![Video Info 3](https://na.cx/i/1EpBnqu.png)

#### 一般留言模式

![Comments 1](https://na.cx/i/vHpRbiO.png)
![Comments 2](https://na.cx/i/8qparR8.png)

#### 相關影片

![Related Videos 1](https://na.cx/i/bH0Ekda.png)
![Related Videos 2](https://na.cx/i/gwAtdya.png)

#### 播放清單

![Playlist 1](https://na.cx/i/YexWnrv.png)
![Playlist 2](https://na.cx/i/Nm9qfMv.png)

#### 章節與字幕

![Chapter/Captions 1](https://na.cx/i/AYMj4EQ.png)
![Chapter/Captions 2](https://na.cx/i/Bd4xFda.png)

---

## 更新紀錄

> **注意：** 以下更新紀錄反映了 Tabview YouTube 早期版本的情況。Tabview YouTube Totara (v5) 是經過重新設計並進一步改進的版本。

### v5.0 (Beta) — [5.0.054](https://greasyfork.org/zh-TW/scripts/501249-tabview-youtube-totara) @ 2025年3月

- 核心功能

---

## 支援平台

### Userscript 管理器

- **推薦：** Violentmonkey 2.16.2 或更新版本
- **也支援：** Tampermonkey（閉源）
- **部分支援：** FireMonkey（因功能限制不建議使用）

### 瀏覽器

- **Chromium 系：** Chrome, Edge, Brave, Cent (Blink 66+)
- **Webkit 系：** Orion Version 0.99.126.4.1 Beta 或更新版本
- **Gecko 系：** Firefox 57+、Waterfox、Librefox、Waterfox Classic

---

## 備註

- **靈感來源：** 原始程式碼和設計受到 [SuperYouTube](https://chrome.google.com/webstore/detail/superyoutube-extension-fo/nojdofjkkahhdklccleaaeinfklmlaga) 的啟發，但已大幅改進（包含暗/亮主題支援）。此 Userscript 與 SuperYouTube 無任何關聯。
- **動機：** 為了簡化設定、降低 RAM 使用量，並修正 SuperYouTube 的錯誤與效能問題而創建此腳本。
- **效能：** 利用多項 CSS 技巧（如 `contain` 與 `content-visibility`）以提升效能，但部分技巧可能會干擾其他 Userscript 或插件，若遇到問題請回報。
- 舊版本由於 YouTube 引擎改變及其根本設計不正確，導致存在較多 Bug。

---

## 兼容性

### 相容的 Userscript 管理器

- Tampermonkey（及其 Beta 版本）
- ViolentMonkey

### 相容的網頁瀏覽器（桌面版）

Chrome, Chromium, Edge, Firefox, Waterfox, LibreWolf, Brave, Safari, Waterfox Classic, Vivaldi, Opera, Cent, Catsxp, Maxthon

> **注意：** 若使用 Waterfox Classic (Firefox 55/56)，請使用 [ViolentMonkey](https://addons.mozilla.org/en-US/firefox/addon/violentmonkey/) 或 [Tampermonkey 4.8.5847](https://addons.mozilla.org/firefox/downloads/file/1076900/tampermonkey-4.8.5847.xpi)。

### 相容的 YouTube 功能

- [360° 影片](https://www.youtube.com/watch?v=2h3pbdTPu6Q)
- 迷你播放視圖
- 現代暗色佈局
- 播放清單列高亮（2022 年底推出）

### 相容的擴充功能 & 插件

- [Maximize Video](https://greasyfork.org/scripts/4870) 的 ESC Video Full Page
- [YouTube - Search While Watching Video](https://greasyfork.org/scripts/29451-youtube-search-while-watching-video) 的頁內搜尋
- [YouTubeLiveClock](https://chrome.google.com/webstore/detail/youtubeliveclock/chpodcedholiggcllnmmjlnghllddgmj) (Chrome 105+)
- [Youtube Genius Lyrics](https://greasyfork.org/en/scripts/386259-youtube-genius-lyrics)
- [YouTube Comment Translation Button](https://greasyfork.org/scripts/456108)
- [YouTube Livestreams Theater Mode](https://www.napalighost.com/youtube-livestreams-theater-mode)

### 不相容

- DanMage <= 5.3.1

---

## 授權條款

[MIT](https://github.com/cyfung1031/Tabview-Youtube/blob/main/LICENSE)
