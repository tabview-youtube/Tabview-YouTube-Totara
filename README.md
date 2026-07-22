# Tabview YouTube Totara

**English** | [日本語](./README.ja.md) | [中文](./README.zh-TW.md)

[![Tampermonkey](https://img.shields.io/badge/Tampermonkey-OK-006989?labelColor=012A36)](https://www.tampermonkey.net/)
[![Violentmonkey](https://img.shields.io/badge/Violentmonkey-OK-006989?labelColor=4B3F72)](https://violentmonkey.github.io/)
[![FireMonkey](https://img.shields.io/badge/FireMonkey-Partial-1b0852?labelColor=885053)](https://addons.mozilla.org/firefox/addon/firemonkey/)
[![Greasemonkey](https://img.shields.io/badge/Greasemonkey-NG-888?labelColor=A2A392)](https://www.greasespot.net/)
[![Stay](https://img.shields.io/badge/Stay-OK-006989?labelColor=a34598)](https://stay.app/)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](https://spdx.org/licenses/MIT.html)

> **Notice:** [Tabview YouTube Totara](https://greasyfork.org/scripts/501249-tabview-youtube-totara) is the redesigned v5 version of [Tabview YouTube](https://greasyfork.org/scripts/428651).
>
> **Important:** Please make sure you install the script from **greasyfork.org**, not from fake sites.

---

## Installation

[Install this script](https://update.greasyfork.org/scripts/501249/Tabview%20YouTube%20Totara.user.js)

You need a userscript manager extension: [Tampermonkey](https://www.tampermonkey.net/), [Violentmonkey](https://violentmonkey.github.io/), or [FireMonkey](https://addons.mozilla.org/firefox/addon/firemonkey/). Tampermonkey requires enabling developer mode in Chrome/Chromium.

---

## Disabled Experimental Flags

### Active

- `web_watch_chat_hide_button_killswitch = false`
- `web_watch_theater_chat = false`
- `suppress_error_204_logging = true`
- `kevlar_watch_grid = false`

### Legacy — Just Keep. YouTube already abandoned their failure designs

- `enable_shadydom_free_scoped_node_methods = false`
- `enable_shadydom_free_scoped_query_methods = false`
- `enable_shadydom_free_scoped_readonly_properties_batch_one = false`
- `enable_shadydom_free_parent_node = false`
- `enable_shadydom_free_children = false`
- `enable_shadydom_free_last_child = false`

---

## Userscript Managers & Minimum Browser Versions

| Manager | Status |
|---|---|
| Tampermonkey | ✅ OK |
| Violentmonkey | ✅ OK |
| FireMonkey | ⚠️ Partial |
| Greasemonkey | ❌ NG |
| Stay | ✅ OK |

### Browsers

| Browser | Minimum | Recommended |
|---|---|---|
| Chrome | 61 | 84+ |
| Edge | 79 | 84+ |
| Firefox | 55 | 79+ |
| Opera | 48 | 70+ |
| Safari | 12.1 | 14.1.2+ |

---

## Related URLs

- [MIT License](https://github.com/cyfung1031/Tabview-Youtube/blob/main/LICENSE)
- [Tabview YouTube GitHub](https://github.com/cyfung1031/Tabview-Youtube)
- [UserCSS: Tabview YouTube Design Customization](https://greasyfork.org/scripts/467638-tabview-youtube-design-customization/)
- [UserCSS: Fix YouTube Watch Flexible Menu Items](https://greasyfork.org/en/scripts/475124-fix-youtube-watch-flexible-menu-items)
- [Old Readme](https://github.com/tabview-youtube/Tabview-YouTube-Totara/blob/main/docs/old.md)

---

## Features

1. **Tabbed Layout:** Info, Comments, Videos, and Playlist are organized into tabs on the right (in two-column layouts).
2. **Layout Switching:** Allows switching to a browse/search layout with mini-view playing (default available when a playlist exists).

### Features Not Fully Available / To Be Confirmed

1. **YouTube Bug Fixes:** Addresses native bugs such as trimmed channel names in Japanese layouts and fixes for extra-wide video side panels.
2. **CSS Enhancements:** Multiple CSS tweaks to boost rendering performance.
3. **Enhanced Video Information:** Displays livestream date/time and duration on video title hover.

### Known Issues

1. Default Tab Selection not yet implemented.
2. Donation Panel Issue not yet checked.
3. Sometimes the collapsed tab container does not auto expand after video / page changing.

---

## Suggested Related Scripts / Extensions

- **Tabview YouTube:** (Core functionality)
- **Live Borderless & Video Resize Fix:**
  - [YouTube Live Borderless](https://greasyfork.org/scripts/457317-youtube-live-borderless)
  - [YouTube Video Resize Fix](https://greasyfork.org/scripts/457319-youtube-video-resize-fix)
- **Chat Enhancements:**
  - [YouTube Chat Bubbles](https://greasyfork.org/scripts/457375-youtube-chat-bubbles)
  - [YouTube Chat Tints](https://greasyfork.org/scripts/457391-youtube-chat-tints)
- **Performance Tools:**
  - [YouTube CPU Tamer by AnimationFrame](https://greasyfork.org/scripts/431573-youtube-cpu-tamer-by-animationframe)
  - [YouTube Super Fast Chat](https://greasyfork.org/scripts/469878-youtube-super-fast-chat)
  - [YouTube JS Engine Tamer](https://greasyfork.org/scripts/473972-youtube-js-engine-tamer)
- **Audio Enhancements:**
  - [YouTube: Audio Only](https://greasyfork.org/scripts/484611-youtube-audio-only)
  - [Disable YouTube AutoPause (Desktop)](https://greasyfork.org/scripts/457219-disable-youtube-autopause)
- **Music Mode Enhancements:**
  - [YouTube Music: Audio Only](https://greasyfork.org/scripts/486384-youtube-music-audio-only)
  - [Disable YouTube AutoPause (Music)](https://greasyfork.org/scripts/464888-disable-youtube-music-autopause)
- **Feature Tweaks:**
  - [YouTube: Quality Auto Max](https://greasyfork.org/scripts/483406-youtube-quality-auto-max)
  - [AutoPlay Next More Than 3 Seconds](https://greasyfork.org/scripts/475579-youtube-make-autoplay-next-more-than-3-seconds)
  - [Exit Fullscreen on Video End](https://greasyfork.org/scripts/469750-youtube-exit-fullscreen-on-video-end)
- **Username Restoration:** [Restore YouTube Username](https://greasyfork.org/scripts/468740-restore-youtube-username-from-handle-to-custom)
- **Resource Management:** [Unhold YouTube Resource Locks](https://greasyfork.org/scripts/457205-unhold-youtube-resource-locks)
- **Settings Reset:** [Reset YouTube Settings](https://greasyfork.org/scripts/457255-reset-youtube-settings)
- **Force AV1 Playback:** [Force YouTube AV1](https://greasyfork.org/scripts/466127-force-youtube-av1)

> **Tip:** If you need to watch YouTube using minimal CPU on older machines, try [YouTube Minimal on PC](https://greasyfork.org/en/scripts/457579-youtube-minimal-on-pc) and [YouTube Minimal Fixs](https://greasyfork.org/en/scripts/457587-youtube-minimal-fixs).

---

## Screenshots (Old. For reference only)

### Preview (Dark Theme — Two Columns)

#### Theater Mode

![Theater Mode 1](https://na.cx/i/MMw4whT.png)
![Theater Mode 2](https://na.cx/i/4mboMRc.png)

#### Live Chat — Live / Replay

![Live Chat 1](https://na.cx/i/yKfkO4y.png)
![Live Chat 2](https://na.cx/i/tvktdwd.png)

#### Video Info

![Video Info 1](https://na.cx/i/6cyuHqt.png)
![Video Info 2](https://na.cx/i/NePBnqt.png)
![Video Info 3](https://na.cx/i/1EpBnqu.png)

#### Normal Comment Mode

![Comments 1](https://na.cx/i/vHpRbiO.png)
![Comments 2](https://na.cx/i/8qparR8.png)

#### Related Videos

![Related Videos 1](https://na.cx/i/bH0Ekda.png)
![Related Videos 2](https://na.cx/i/gwAtdya.png)

#### Playlist

![Playlist 1](https://na.cx/i/YexWnrv.png)
![Playlist 2](https://na.cx/i/Nm9qfMv.png)

#### Chapter & Caption

![Chapter/Captions 1](https://na.cx/i/AYMj4EQ.png)
![Chapter/Captions 2](https://na.cx/i/Bd4xFda.png)

---

## Changelog

> **Note:** The changelog below reflects previous versions of Tabview YouTube. Tabview YouTube Totara (v5) is a redesigned version with further improvements.

### v5.0 (Beta) — [5.0.054](https://greasyfork.org/scripts/501249-tabview-youtube-totara) @ Mar 2025

- Core Features

---

## Supported Platforms

### Userscript Managers

- **Recommended:** Violentmonkey 2.16.2 or later
- **Also Supported:** Tampermonkey (closed-source)
- **Partial Support:** FireMonkey (not recommended due to feature limitations)

### Browsers

- **Chromium-based:** Chrome, Edge, Brave, Cent (Blink 66+)
- **Webkit-based:** Orion Version 0.99.126.4.1 Beta or later
- **Gecko-based:** Firefox 57+, Waterfox, Librefox, Waterfox Classic

---

## Remarks

- **Inspiration:** The source code and design were originally inspired by [SuperYouTube](https://chrome.google.com/webstore/detail/superyoutube-extension-fo/nojdofjkkahhdklccleaaeinfklmlaga) but have been heavily improved (including dark/light theme support). This UserScript is not affiliated with SuperYouTube.
- **Motivation:** Created to simplify settings and reduce RAM usage compared to SuperYouTube while fixing bugs and performance issues.
- **Performance:** Many CSS hacks are employed for performance gains (e.g., using `contain` and `content-visibility`). Some hacks might interfere with other UserScripts or plugins — please report issues for fixes.
- Old version is buggy due to changes of YouTube's engine and its fundamental design was incorrect.

---

## Compatibility

### Compatible Userscript Managers

- Tampermonkey (and its beta)
- ViolentMonkey

### Compatible Web Browsers (Desktop)

Chrome, Chromium, Edge, Firefox, Waterfox, LibreWolf, Brave, Safari, Waterfox Classic, Vivaldi, Opera, Cent, Catsxp, Maxthon

> **Note:** For Waterfox Classic (Firefox 55/56), use [ViolentMonkey](https://addons.mozilla.org/en-US/firefox/addon/violentmonkey/) or [Tampermonkey 4.8.5847](https://addons.mozilla.org/firefox/downloads/file/1076900/tampermonkey-4.8.5847.xpi).

### Compatible YouTube Features

- [360° Video](https://www.youtube.com/watch?v=2h3pbdTPu6Q)
- Mini Player View
- Modern Dark Layout
- Playlist Row Highlight (introduced end of 2022)

### Compatible Extensions & Plugins

- [Maximize Video](https://greasyfork.org/scripts/4870)'s ESC Video Full Page
- [YouTube - Search While Watching Video](https://greasyfork.org/scripts/29451-youtube-search-while-watching-video)'s in-page search
- [YouTubeLiveClock](https://chrome.google.com/webstore/detail/youtubeliveclock/chpodcedholiggcllnmmjlnghllddgmj) (Chrome 105+)
- [Youtube Genius Lyrics](https://greasyfork.org/en/scripts/386259-youtube-genius-lyrics)
- [YouTube Comment Translation Button](https://greasyfork.org/scripts/456108)
- [YouTube Livestreams Theater Mode](https://www.napalighost.com/youtube-livestreams-theater-mode)

### Incompatible

- DanMage <= 5.3.1

---

## License

[MIT](https://github.com/cyfung1031/Tabview-Youtube/blob/main/LICENSE)
