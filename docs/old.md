**English** | [日本語](https://greasyfork.org/ja/scripts/428651/) | [中文](https://greasyfork.org/zh-TW/scripts/428651/)

## Since 2025, there will be no major development of Tabview Youtube.  
Please move to [Tabview YouTube Totara](https://greasyfork.org/scripts/501249-tabview-youtube-totara).

### There was a fundamental design failure in this script so Tabview YouTube Totara (v5) is developed and will completely replace this script.  
Some features will be completely removed in Tabview YouTube Totara as we have other scripts to improve YouTube's performance issues, and some old features are no longer required in the latest YouTube engine.  
You can just use Tabview Youtube V4 for a while as some features are still not available in V5.

#### Notice: [Tabview YouTube Torato](https://greasyfork.org/scripts/501249-tabview-youtube-totara) is the redesigned v5 version of Tabview Youtube

**Please make sure you install the script from _greasyfork.org_, not fake sites.**

##### Disabled Experimental Flags
- `kevlar_watch_metadata_refresh_no_old_secondary_data = false`
- `live_chat_overflow_hide_chat = false`
- `web_watch_chat_hide_button_killswitch = false`
- `web_watch_theater_chat = false`
- `suppress_error_204_logging = true`
- `kevlar_watch_grid = false`

![Tampermonkey-OK](https://img.shields.io/badge/Tampermonkey-OK-006989?labelColor=012A36)
![Violentmonkey-OK](https://img.shields.io/badge/Violentmonkey-OK-006989?labelColor=4B3F72)
![FireMonkey-Partial](https://img.shields.io/badge/FireMonkey-Partial-1b0852?labelColor=885053)
![Greasemonkey-NG](https://img.shields.io/badge/Greasemonkey-NG-888?labelColor=A2A392)
![Stay-OK](https://img.shields.io/badge/Stay-OK-006989?labelColor=a34598)

**Minimum Browser Versions:**  
![Chrome 61](https://img.shields.io/badge/Chrome-61-4b1?logo=googlechrome) ![Edge 79](https://img.shields.io/badge/Edge-79-4b1?logo=microsoftedge) ![Firefox 55](https://img.shields.io/badge/Firefox-55-4b1?logo=firefoxbrowser) ![Opera 48](https://img.shields.io/badge/Opera-48-4b1?logo=opera) ![Safari 12.1](https://img.shields.io/badge/Safari-12.1-4b1?logo=safari)

**Recommended Browser Versions:**  
![Chrome 84+](https://img.shields.io/badge/Chrome-84+-1b6?logo=googlechrome) ![Edge 84+](https://img.shields.io/badge/Edge-84+-1b6?logo=microsoftedge) ![Firefox 79+](https://img.shields.io/badge/Firefox-79+-1b6?logo=firefoxbrowser) ![Opera 70+](https://img.shields.io/badge/Opera-70+-1b6?logo=opera) ![Safari 14.1.2+](https://img.shields.io/badge/Safari-14.1.2+-1b6?logo=safari)

[MIT license](https://github.com/cyfung1031/Tabview-Youtube/blob/main/LICENSE); [Tabview Youtube GitHub](https://github.com/cyfung1031/Tabview-Youtube);  
[UserCSS: Tabview Youtube Design Customization](https://greasyfork.org/scripts/467638-tabview-youtube-design-customization/)  
[UserCSS: Fix Youtube Watch Flexible Menu Items](https://greasyfork.org/en/scripts/475124-fix-youtube-watch-flexible-menu-items)

## Features provided by Tabview Youtube
1. Info, Comments, Videos, Playlist are all put into tabs at the right side (if it is two column layout).
2. ~~Alive the background tabs if they are playing the video / music song (i.e. avoid killing inactive tab, see [Tabs Discard](#tab-discard)).~~
3. Reduce lagging issue regarding (LIVE PLAYBACK) chatroom messages (see [below](#what-tabview-youtube-makes-for-chatroom-messages)).
4. Fix various issues related to transcript panel (e.g. effect texts and dual captions).
5. Features to against YouTube native coding bugs, such as the display of channel name being unreasonably trimmed in Japanese layout, side panel for extra wide video.
6. Allow users to switch to browse / search layout using miniview playing (by default, this is only available if there is playlist).
7. Various CSS hacks to enhance rendering performance.
8. Floating the sider panel if the layout sizing is incorrect due to extra wide video.
9. ~~Fix Chatroom messages issues (live playback - backwards) [disabled if [hyperchat](https://chrome.google.com/webstore/detail/hyperchat-by-livetl/naipgebhooiiccifflecbffmnjbabdbh) is used]~~ (No longer required as YouTube engineers fixed in 2023)
10. Show Livestream DateTime and duration when hovering the video title.
11. Prevent playback shift during text selection change with keyboard.
12. Single Column with PIP (desktop, blink / webkit).
13. Fixed various YouTube native bugs for playlist.

## Suggested Related Scripts / Plugins / Extensions
**[Full List here](https://greasyfork.org/en/users/371179-𝖢𝖸-𝖥𝗎𝗇𝗀?site=youtube.com&sort=updated)**

- ![Ytd-Watch](https://img.shields.io/badge/Ytd-Watch-1C77C3) Tabview Youtube
- ![Ytd-Watch](https://img.shields.io/badge/Ytd-Watch-1C77C3) [Youtube Live Borderless](https://greasyfork.org/scripts/457317-youtube-live-borderless) & [YouTube Video Resize Fix](https://greasyfork.org/scripts/457319-youtube-video-resize-fix)
- ![Ytd-Live](https://img.shields.io/badge/Ytd-Live-E94F37) [YouTube Chat Bubbles](https://greasyfork.org/scripts/457375-youtube-chat-bubbles) & [YouTube Chat Tints](https://greasyfork.org/scripts/457391-youtube-chat-tints)
- ![Ytd-Perf](https://img.shields.io/badge/Ytd-Perf-00AF54) [YouTube CPU Tamer by AnimationFrame](https://greasyfork.org/scripts/431573-youtube-cpu-tamer-by-animationframe); [YouTube Super Fast Chat](https://greasyfork.org/scripts/469878-youtube-super-fast-chat); [YouTube JS Engine Tamer](https://greasyfork.org/scripts/473972-youtube-js-engine-tamer)
- ![Yt-Audio](https://img.shields.io/badge/Yt-Audio-B850CF) [YouTube: Audio Only](https://greasyfork.org/scripts/484611-youtube-audio-only); [Disable YouTube AutoPause (Desktop)](https://greasyfork.org/scripts/457219-disable-youtube-autopause)
- ![Yt-Music](https://img.shields.io/badge/Yt-Music-B850CF) [YouTube Music: Audio Only](https://greasyfork.org/scripts/486384-youtube-music-audio-only); [Disable YouTube AutoPause (Music)](https://greasyfork.org/scripts/464888-disable-youtube-music-autopause)
- ![Ytd-Feat](https://img.shields.io/badge/Ytd-Feat-0D1821) [YouTube: Quality Auto Max](https://greasyfork.org/scripts/483406-youtube-quality-auto-max); [AutoPlay Next More Than 3 seconds](https://greasyfork.org/scripts/475579-youtube-make-autoplay-next-more-than-3-seconds); [Exit Fullscreen on Video End](https://greasyfork.org/scripts/469750-youtube-exit-fullscreen-on-video-end)
- ![Yt-Feat](https://img.shields.io/badge/Yt-Feat-0D1821) [Restore YouTube Username](https://greasyfork.org/scripts/468740-restore-youtube-username-from-handle-to-custom)
- ![Yt-Other](https://img.shields.io/badge/Yt-Other-E0E1DD) [Unhold YouTube Resource Locks](https://greasyfork.org/scripts/457205-unhold-youtube-resource-locks)
- ![Ytd-Other](https://img.shields.io/badge/Ytd-Other-E0E1DD) [Reset YouTube Settings](https://greasyfork.org/scripts/457255-reset-youtube-settings)
- ![Ytd-Other](https://img.shields.io/badge/Ytd-Other-E0E1DD) [Force YouTube AV1 (Chrome/Firefox/Opera)](https://greasyfork.org/scripts/466127-force-youtube-av1)

##### If you are looking for the way to watch YouTube with least CPU resources in your old machine, please use [YouTube Minimal on PC](https://greasyfork.org/en/scripts/457579-youtube-minimal-on-pc) and [YouTube Minimal Fixs](https://greasyfork.org/en/scripts/457587-youtube-minimal-fixs)

## [Screenshots](#screenshots)
## [Compatibility](#compatibility)

## **VER. v4.70 (Stable) [4.70.4](https://greasyfork.org/scripts/428651-tabview-youtube)** <small>@ 20 Apr 2024</small>
- Changed to `ytConfigHacks` for disabling experimental flags like `kevlar_watch_grid`
- Code Hack to override `overscrollConfig` (wheel/scroll cooldown feature) (4.70.2)
- Adopt CSS change for wrapper [`ytd-watch-info-text#ytd-watch-info-text` is used to wrap the `#info-container`](https://github.com/cyfung1031/Tabview-Youtube/issues/35) (4.70.4)
- Fixed a long existed bug related to Tabview Event Control (4.70.20 ~ 4.70.32)

### **VER. v4.69 (Stable) [4.69.4](https://greasyfork.org/scripts/428651-tabview-youtube)** <small>@ 10 Mar 2024</small>
- Set `web_watch_theater_chat` to `false` for using re-openable chat
- Fix `getTextContentArr` issue

### **VER. v4.68 (Stable) [4.68.1](https://greasyfork.org/scripts/428651-tabview-youtube)** <small>@ 8 Mar 2024</small>
- Bug Fix for chatroom container related issue
- added `--fix-horizontal-card-scroller-in-tab-info`

### **VER. v4.67 (Beta) [4.67.0](https://greasyfork.org/scripts/428651-tabview-youtube)** <small>@ 27 Feb 2024</small>
- added `FIX_liveChatPageUrl` setting

### **VER. v4.66 (Stable) [4.66.11](https://greasyfork.org/scripts/428651-tabview-youtube)** <small>@ 26 Feb 2024</small>
- Bug fixing (v4.66.11)

### **VER. v4.63 (Stable) [4.62.1](https://greasyfork.org/scripts/428651-tabview-youtube)** <small>@ 14 Dec 2023</small>
- Advanced Script Injection for disabling `kevlar_watch_metadata_refresh_no_old_secondary_data`

### **VER. v4.62 (BETA) [4.62.1](https://greasyfork.org/scripts/428651-tabview-youtube)** <small>@ 15 Oct 2023</small>
- Code Changed for better content detection mechanism
- Adapt latest transcript button (scrollToSection)

### **VER. v4.40 (BETA) [4.40.16](https://greasyfork.org/scripts/428651-tabview-youtube)** <small>@ 06 Oct 2023</small>
- Change CSS Injection to make compatible with [Youtube Livestream Theater Mode](https://chrome.google.com/webstore/detail/youtube-livestreams-theat/cmjhejfkhdonjimgkinjdombabgfbcal/)
- CSS Event Bug Fixing
- Changed compatibility fix for "Youtube Search While Watching Video"
- Fix Firefox's XRays issue to make compatible with Firemonkey

### **VER. v4.34 (Stable) [4.34.12](https://greasyfork.org/scripts/428651-tabview-youtube)** <small>@ 29 Sep 2023</small>
- Bug Fix

### **VER. v4.34 (Stable) [4.34.0](https://greasyfork.org/scripts/428651-tabview-youtube)** <small>@ 23 Sep 2023</small>
- Bug Fix & Adaption to _Controller Extraction v2_

### [Past UserScript Update History Changelog](https://github.com/cyfung1031/Tabview-Youtube/blob/main/Changelog.md)

### Supports:
- Violentmonkey 2.16.2 or later (recommended)
- Tampermonkey (it's closed-source)
- Blink 66+: Chrome / Edge / Brave / Cent
- Webkit: Orion Version 0.99.126.4.1 Beta or later
- Gecko: Firefox 57+ / Waterfox / Librefox / Waterfox Classic (backward compatible)

*FireMonkey is not recommended due to limitation of feature.*

### Remarks

At this moment, I have no plan to publish this in Chrome Web Store as I do not have such a time to deal with Chrome Web Store's requirement.  
Please do **NOT** publish this in Chrome Web Store on behalf of yourself.

The source code and design were originally inspired by [SuperYouTube (Extension for Youtube™)](https://chrome.google.com/webstore/detail/superyoutube-extension-fo/nojdofjkkahhdklccleaaeinfklmlaga), but I have done many coding improvement and design changes for better and faster experience (for example, dark / light theme adaptation). This UserScript has NO relationship with SuperYouTube.

The reason I created this UserScript is, I do not like there are so many settings in SuperYouTube and waste my RAM for just watching youtube as a separate extension, and also I feel buggy and slow for SuperYouTube.

As for performance boost, I imposed many CSS hacks for this UserScript to maximize the user experience (contain and content-visibility). Some might make other UserScripts or plugins broken. So please let me know and I will try to fix the bugs.

### Remarks - Tab Discard
Chrome/Edge: _about://discards_  
Firefox: _about:unloads_

This is a default feature on Chromium-based engines. This is to save resources by putting background tabs into 'sleeping'.  
YouTube tabs are easily killed by the browser, including music playing and live streaming.  
Tabview Youtube has implemented some specific coding to handle this issue.  
However, if you open many YouTube tabs, and only one of them is playing video/music song, it makes all tabs not being slept.

Note: The issue related to "Tab is currently holding an IndexedDB lock" can be resolved by installing [Unhold YouTube Resource Locks](https://greasyfork.org/scripts/457205-unhold-youtube-resource-locks).

### Remarks - What Tabview Youtube makes for chatroom messages

#### Live Playback Only
Live Chat is an essential feature for YouTube videos, although some might not like it.  
Its content is inside iframe.  
The fetching of its content is changed such that it will wait for animation frames, and thus also reduce the refresh of contents if the tab is in background.  
For background tabs, it will still load the chatroom messages, but it will be a much slower rate (comparatively).

There is no conflict with using [YouTube CPU Tamer by AnimationFrame](https://greasyfork.org/scripts/431573-youtube-cpu-tamer-by-animationframe/) and/or [YouTube Super Fast Chat](https://greasyfork.org/scripts/469878-youtube-super-fast-chat). YouTube CPU Tamer by AnimationFrame is changing the setTimeout / setInterval behavior to avoid the page lagging, while Tabview Youtube makes specific measures to the fetching of chatroom messages. YouTube Super Fast Chat focus on the content rendering.

## Screenshots

### Preview (Dark Theme - Two Columns)

**Theater Mode**  
![img](https://na.cx/i/MMw4whT.png) ![img](https://na.cx/i/4mboMRc.png)

**Live Chat - Live / Replay**  
![img](https://na.cx/i/yKfkO4y.png) ![img](https://na.cx/i/tvktdwd.png)

**Video Info**  
![img](https://na.cx/i/6cyuHqt.png) ![img](https://na.cx/i/NePBnqt.png)  
![img](https://na.cx/i/1EpBnqu.png)

**Normal Comment Mode, if available**  
![img](https://na.cx/i/vHpRbiO.png) ![img](https://na.cx/i/8qparR8.png)

**Related Videos**  
![img](https://na.cx/i/bH0Ekda.png) ![img](https://na.cx/i/gwAtdya.png)

**Playlist, if available**  
![img](https://na.cx/i/YexWnrv.png) ![img](https://na.cx/i/Nm9qfMv.png)

**[Chapter](https://support.google.com/youtube/answer/9884579?hl=en) & [Caption](https://support.google.com/youtube/answer/100078?hl=en#zippy=%2Cview-captions-transcript), if available**  
![img](https://na.cx/i/AYMj4EQ.png) ![img](https://na.cx/i/Bd4xFda.png)

**Popup Live Chat (v4)**  
![img](https://na.cx/i/7xOQT6E.png)

_Sample YouTube Link - Combined Test @ Mar 2024_
- [ヨルシカ - 晴る](https://www.youtube.com/watch?v=CkvWJNt77mU)

_Sample Youtube Links - Standard Test Case (2000+ Comments + Live Chat Playback):_
- [BAND-MAID / Sense (Official Music Video)](https://www.youtube.com/watch?v=BWN6iOFjm9U)
- [【Cover】Beat Eater / calliope × reine × suisei](https://www.youtube.com/watch?v=nbB3KsFRv4U)

_Sample Youtube Links - Long Comments (229,342+):_
- [米津玄師 MV「Lemon」](https://www.youtube.com/watch?v=SX_ViT4Ra7k&list=RDCLAK5uy_kvhjcPWzH7xZL-WnqGbiA_euQGy5_cbHI&index=2)

_Sample Youtube Links - Live Chat Playback:_
- [【中天互動LIVE】大嗆林昶佐滾! 攤商出面再嗆 @中天新聞 20210703](https://www.youtube.com/watch?v=RpGv7kaBA6Q)

_Sample Youtube Links - Live Chat Playback Disabled:_
- [バキ 大擂台賽編 ll Yujiro shows his demon face muscles, 勇次郎が鬼顔の筋肉を見せる!](https://www.youtube.com/watch?v=6uvQE21iOjA)
- [HACHI 1st ONE-MAN LIVE 「The Beginning ∞」 ダイジェスト](https://www.youtube.com/watch?v=xJjzlPkaleE)

_Sample Youtube Links - Playlist:_
- [J-Pop Stress Busters by YouTube Music](https://www.youtube.com/watch?v=VTUgZ3-Ovws&list=RDCLAK5uy_k_OEunzsOIJ_BOfbbTDgYN253bcPItURY&start_radio=1&rv=h_RZwRbI1QI)

_Sample Youtube Links - Chapter:_
- [Kami カミ ☯ Japanese Lofi HipHop Mix](https://www.youtube.com/watch?v=goxmvGJkoi0)
- [BAND-MAID : (Almost) Greatest Hits Compilation a.k.a. Part 2](https://www.youtube.com/watch?v=RvVeaz1lY_g)
- [ULTIMATE MacBook Battery Guide! (Should You Keep It Plugged In?)](https://www.youtube.com/watch?v=d34p7ULZbzU)
- [Anya Loves Them Very Much | SPY x FAMILY | スパイファミリー](https://www.youtube.com/watch?v=TsMZxnaeRIo)
- [[Sad Japanese Songs] - Fujita Maiko's ( 藤田麻衣子) Playlist](https://www.youtube.com/watch?v=xPyCjiHIUVw)
- [SAO Songs](https://www.youtube.com/watch?v=rElBuTD7wTw)

_Sample Youtube Links - DISABLED Comment Section (by Uploader Setting):_
- [僕の存在証明](https://www.youtube.com/watch?v=PVUZ8Nvr1ic)
- [ブルーアンビエンス](https://www.youtube.com/watch?v=ZP3GFkEE93A)
- [Ame Sansan](https://www.youtube.com/watch?v=7rpl6blm3Hw)
- [Ienai](https://www.youtube.com/watch?v=N5mtThfDp_Q)
- [夏灯篭](https://www.youtube.com/watch?v=mlIUyE-19VU)

_Sample Youtube Links - EXTRA META INFO:_
- [相羽あいな - 閃光 from CrosSing](https://www.youtube.com/watch?v=kGihxscQCPE)

_Sample Youtube Link - NO TITLE (e.g. `\u200b`):_
- [(NO TITLE) 《界隈曲》](https://www.youtube.com/watch?v=KjIzJZGrz1c)

_Sample Youtube Links - NO COMMENT SECTION:_
- [《盾之勇者成名錄 第二季》#1 (繁中字幕 | 日語原聲)【Ani-One ULTRA】](https://www.youtube.com/watch?v=mIxeKvHKC24&list=PLxSscENEp7JgFgNCOymq2ClIN3CTGC63X)

_Sample Youtube Links - Youtube's incorrect counting of comments:_
- ~~[Video Link](https://www.youtube.com/watch?v=Q6JDF9AlNLE)~~ (already fixed by Youtube)
- ~~[Video Link](https://www.youtube.com/watch?v=K2aNAf2qi_0)~~ (private video)
- [Video Link](https://www.youtube.com/watch?v=yskthUMlcu4)

_Sample Youtube Links - Old Static Background Video (Sqaure or 4:3):_
- ~~[Rising Hope](https://www.youtube.com/watch?v=L0RXVnRbFg8)~~ (Unlisted/Removed)
- [Alan - Sakura Modern](https://www.youtube.com/watch?v=bK_rKhMIotU)
- [alan / 久遠の河](https://www.youtube.com/watch?v=4Oc0tBsc91s)
- [栗林みな実 - ZERO!!](https://www.youtube.com/watch?v=se4VTu6SK4E)

_Sample Youtube Links - New Static Background Video (Transparent 16:9):_
- [Ame Sansan](https://www.youtube.com/watch?v=7rpl6blm3Hw)
- [Hitoshibai](https://www.youtube.com/watch?v=xjKU5QM_MUs)

_Sample Youtube Links - 21:9 Video_
- [櫻坂46『摩擦係数』](https://www.youtube.com/watch?v=D8piCp9XMKA)

_Sample Youtube Links - Non-effected subtitles:_
- [DAOKO × 米津玄師『打上花火』MUSIC VIDEO](https://www.youtube.com/watch?v=-tKVN2mAKRI)

_Sample Youtube Links - Effected subtitles:_  
_(Be careful - opening the transcript panel without Tabview YouTube 2.1.0 might make your browser crash)_
- [【オリジナル曲】　Palette/常闇トワ　【フルMV】](https://www.youtube.com/watch?v=Ud73fm4Uoq0) (transcript fix)
- [天球、彗星は夜を跨いで / 星街すいせい(official)](https://www.youtube.com/watch?v=zLak0dxBKpM) (effect fix)
- [[ORIGINAL SONG] MERA MERA - Mori Calliope](https://www.youtube.com/watch?v=DOzpsXZS-j0)
- [Kikuo - 愛して愛して愛して](https://www.youtube.com/watch?v=NTrm_idbhUk) [*out sync under fullscreen*](#out-sync)

_Sample Youtube Links - Two line subtitles:_
- [【オリジナル曲】　Palette/常闇トワ　【フルMV】](https://www.youtube.com/watch?v=Ud73fm4Uoq0)
- [Stellar Stellar / 星街すいせい(official)](https://www.youtube.com/watch?v=a51VH9BYzZA)

_Sample Yotubue Links - Live Chat / Reply with Reduced Refresh Speed:_
- [LiSA 『明け星』 -MUSiC CLiP-（テレビアニメ「鬼滅の刃」無限列車編 オープニングテーマ）](https://www.youtube.com/watch?v=yGcm81aaTHg)

_Youtube Transcript only lang bug_
- [n-buna - 七月、影法師、藍色、ロッカー](https://www.youtube.com/watch?v=e8SzC-pVA6c)

_Default Chatroom Expanded_
- [【Minecraft】青ウーパー最終回セカンドシーズン後編【天音かなた/ホロライブ】](https://www.youtube.com/watch?v=Xlx_cAJP13o)

_3D Video_
- [やくしまるえつこ『アンノウン・ワールドマップ』360°MV / Yakushimaru Etsuko - Unknown World Map](https://www.youtube.com/watch?v=2h3pbdTPu6Q)

_YouTube Modern Layout 2022 (Darker Dark Theme) - #cinematics_
- [ウォルピスカーター MV 『泥中に咲く』](https://www.youtube.com/watch?v=40dJS_LC6S8)
- [星の消えた夜に / HACHI.cover 【歌ってみた】](https://www.youtube.com/watch?v=t9yTrHENj6g)

_2.44 Aspect Ratio Videos (`[is-extra-wide-video_]`) [YouTube Experimental]_
- [CHANMINA - Don't go (feat. ASH ISLAND) (Official Music Video) -](https://www.youtube.com/watch?v=E_0AOHXcw_8)
- [涙することは疎か、息も出来ない。 / HACHI 【Official MV】](https://www.youtube.com/watch?v=yK2Cdi6R43c)
- [夏灯篭 / HACHI 【Official MV】](https://www.youtube.com/watch?v=2epJQyYSF2Q)
- [ソビエトフューリー |アクション、戦争 |フルムービー](https://www.youtube.com/watch?v=A4yClBq7xpY)
- [eill | Finale. (Official Music Video)](https://www.youtube.com/watch?v=1lYb9nLO_FY)

_Comment with Colored Background_
- [KICK BACK / 久遠たま (Cover) アニメ『チェンソーマン』OP](https://www.youtube.com/watch?v=Ewnt9o7c1vo)
- [逆光のフリューゲル / 久遠たま × HACHI (Cover)](https://www.youtube.com/watch?v=nBHSGuLCRX8)

_Related Videos in Information Tab_
- [Ariabl'eyeS サビメドレー](https://www.youtube.com/watch?v=UY5bp5CNhak)

_YouTube Music Premium Member Only_
- [瞬く星の下で](https://www.youtube.com/watch?v=YrJYtf2eI-4)

_Long Playlist Test Case_
- <https://www.youtube.com/watch?v=30PcoavqFq0&list=PLS3XGZxi7cBXnYfJpUas1ud6XATvWATHb&index=300>

_Donation YouTube Videos_
- <https://www.youtube.com/watch?v=NGQ2Zhrkk4o>
- <https://www.youtube.com/watch?v=L_tg2u26tCU>
- <https://www.youtube.com/watch?v=cV2gBU6hKfY>

_List of Songs (Music Songs)_
- [LoveLive! 強迫症專用µ's全曲完美歌單](https://www.youtube.com/watch?v=OzGVz1ClxIc&list=PLiYH7mFLKu4fywBPL70nFrQONd6rT_ihU&index=3)

_Chapter on Info_
- [地獄少女 1,2,3期 OP曲&ED曲 フルメドレー 【逆さまの蝶 NightmaRe 月華】【かりぬい あいぞめ いちぬけ】Jigoku Shoujo Hell Girl](https://www.youtube.com/watch?v=jZEwANkWmjE)

_Error UI (To be reviewed)_
- <https://www.youtube.com/watch?v=Am4TdJ2cR4I>

### Known Issues
1. ~~abnormal attribute "hidden" in invisible layout - Sometimes the playlist is still hidden after clicking the playlist item.~~
2. ~~Youtube Coding Bug: No chat replay if the video is paused~~
3. ~~[Webkit bug](https://bugs.webkit.org/show_bug.cgi?id=45399) - [comments lines clamped without "show more" button](https://github.com/cyfung1031/Tabview-Youtube/issues/1)~~
4. ~~Show More / Show Less Button might be always visible for full content after resizing the comments section~~
5. ~~MiniView Switching Video Not Available Yet~~ (v2.1.0 feature)
6. ~~[Sometime the player go miniview after the page is just loaded](https://github.com/cyfung1031/Tabview-Youtube/issues/3)~~ (v2.1.0 feature)
7. **Request Default Tab Feature** [94022](https://greasyfork.org/en/scripts/428651-tabview-youtube/discussions/94022) [92458](https://greasyfork.org/scripts/428651-tabview-youtube/discussions/92458#comment-216960) (trial - v4.4.3)
8. ~~Text Size for Tab Info - will let users to adjust the text size~~ (v2.4.1 feature)
9. ~~Teaser UI - when `window.yt.config_.EXPERIMENT_FLAGS.kevlar_watch_metadata_refresh` is true~~ Removed due to Teaser UI abandoned by YouTube
10. ~~**playing -> show comment -> auto play next ->  css not injected to iframe?**~~ Fixed in v2.11.3 by using Iframe load event checking
11. ~~Tooltips overlapped by Video ([#157029](https://greasyfork.org/scripts/428651-tabview-youtube/discussions/157029)) - this relates to the `position: relative` which is essential for #cinematics feature)~~ (Fixed in v3.10.0)
12. ~~Adjustment for time delay for layout changing shall be required to make the response immediately~~ no need
13. ~~Toggle Button Text Incorrect (switching among live streams) ([#157029](https://greasyfork.org/scripts/428651-tabview-youtube/discussions/157029))~~
14. ~~Playlist Display Issue (queue video in 'browse' page) ([#157029](https://greasyfork.org/scripts/428651-tabview-youtube/discussions/157029))~~
15. _Possible Caption Out-sync Issues_ ([#156915](https://greasyfork.org/en/scripts/428651-tabview-youtube/discussions/156915))
16. _No round angle for engagement panel??_
17. ~~Possible Wrong comments count when the video is auto-played in the background.~~ (fixed in v3.11.0)
18. ~~Possible Wrong desc info duplication `check-info-duplicate false true false` checking when the video is auto-played in the background.~~ (fixed in v3.11.0)
19. ~~Fullscreen Description overflow issues (due to 2022/12/10 layout change)~~ (fixed in v3.13.1)
20. ~~Engagement Panel Visibility Change not being detected after clicking the time of video in the comments~~ (fixed in v3.13.1)
21. ~~Live Chat Playback is okay, but if the page url is "&t=xxxx", "continuation" value for iframe url is fixed to the certain time. First batch of chat messages will be wrong.~~ (fixed in v3.16.7)
22. ~~Due to Recent YouTube Coding Change: If the watch page was navigated with mini player mode, Live Chat Playback will not occur in the correct time position when the iframe is shown. After seeking in the timeline progress, it will resume normal.~~ (fixed in v4.1.0)
23. ~~Due to Recent YouTube Coding Change: collapse and re-expand the chatframe will make the chat messages shown incorrectly.~~ (fixed in v4.1.0)
24. ~~Switch Page + collapse + expand rapidly will make the layouting broken.~~ (fixed in v4.1.xx ~ v4.2.2)
25. ~~Switch Pages with LiveChatFrame will make the chat frame content flicking.~~ (fixed in v4.1.xx ~ v4.2.2)
26. ~~TODO: Reload playback chat messages after the chat is expanded at the previous time tick~~ (fixed in v4.1.xx ~ v4.2.2)
27. ~~comments loaded twice when the ads is played~~ (fixed in v4.2.x ~ v4.2.4)
28. CSS cause lagging in video page with complicated effected subtitles
29. ~~Incorrect Chat Displayed for Video after page switched~~ (fixed in v4.15.10)
30. Chapter Popup would not minimize the tab container, after page switched [link](https://www.youtube.com/watch?v=jZEwANkWmjE) (Might not reproducible)
31. Migration to Polymer Controller Extraction - TBC
32. ~~Chat Not Shown if it is expanded by default [link](https://www.youtube.com/watch?v=pFwb-U3BwjA)~~ (fixed in v4.15.13)
33. YouTube's error "something is wrong" appears sometimes when the video page is switched at the same time the live chat iframe is network fetching (might be not reproducible)

### Known Issues - YouTube Native
1. When the page wide is slowly reducing, extra wide video `[is-extra-wide-video_]` (eg. 1:2.44) squeeze the side panel out of the page ([#157029](https://greasyfork.org/scripts/428651-tabview-youtube/discussions/157029)) - this is known as YouTube bug
2. YouTube native bug for channel name - Japanese layout + window width = 1185px for [video](https://www.youtube.com/watch?v=NasyGUeNMTs&list=PLQntWbrycbJf7XrH4da-PIKUC__bepot5&index=12) (screenshot)  
   [![HfUpZfS.md.png](https://iili.io/HfUpZfS.md.png)](https://freeimage.host/i/HfUpZfS)  
   This is because YouTube engineers just consider English layout. For Japanese, the buttons will be much longer and thus the layout would not work.  
   This will change soon along with the darker dark theme.
3. YouTube only enable the SPA browsing for playlist.
4. MiniPlayer View History change is buggy.

### Known & Fixed YouTube Native Chatroom Issues
1. Possible No content after switching pages between live/playback video pages, where the chatroom is still open, the solution is trigger urlChanged once page is fetched **~~(still buggy ??)~~ [resolved in v4.1.47]**
2. Backward timeline seeking is wrong (After backwarded, some messages (usually wrong) will show, and then completely frozen). The solution is to use reload continuation instead of seek continuation with by pass all unused mechanisms.
3. When the chat is expanded at progress >0, the messages could be wrong. The solution is to use reload continuation instead of seek continuation with by pass all unused mechanisms.
4. the first rendering might fail and all afterwards messages will not be rendered. Solution is force seeking at the first rendering.

### De-customize Tabview Youtube CSS rules
Some CSS rules used in Tabview Youtube change the default appearance for a better user experience.  
You can de-customize (revert to YouTube default) by adding the following:

#### Chatroom Iframe
~~~
span#message {
    --tabview-chat-message-display: 'invalid' !important;
    --tabview-chat-message-mt: 'invalid' !important;
    --tabview-chat-message-mb: 'invalid' !important;
}
~~~

#### Main Page
```css
yt-formatted-string.ytd-transcript-segment-renderer > span {
    --tabview-transcript-segment-span-display: 'invalid' !important;
}
````

> [Example Link](https://www.youtube.com/watch?v=Ud73fm4Uoq0)
> [Tabview Youtube Default Appearance](https://iili.io/H33dEXf.md.png)
> [After invaliding the customized CSS rule](https://iili.io/H33dVql.md.png)

### APIs

* **Element**: `ytd-comments#comments`
  **Property**: `loadComments`
  **Description**: Function; trigger comments to load

* **Element**: `ytd-comments#comments ytd-expander[max-number-of-lines]`
  **Property**: `recomputeOnResize`
  **Description**: Boolean; default = false; changed to `true`

* **Element**: `ytd-comments#comments ytd-expander[max-number-of-lines]`
  **Property**: `calculateCanCollapse`
  **Description**: Function; changed to `this.$.content.scrollHeight>this.collapsedHeight`

* **Element**: `ytd-live-chat-frame#chat`
  **Property**: `postToContentWindow`
  **Description**: argument 1 is an object. Render chat message by using `{ "yt-player-video-progress": ... }`. Tabview Youtube change the function implementation (`g_postToContentWindow()`) to reduce CPU usage and fix bugs.

## [Caption Out-Sync Issue](#out-sync)

The caption out-sync issue might be fixed by installing all the following scripts:

1. [Disable all YouTube EXPERIMENT_FLAGS](https://greasyfork.org/scripts/470428-disable-all-youtube-experiment-flags/)
2. [YouTube CPU Tamer by AnimationFrame](https://greasyfork.org/scripts/431573-youtube-cpu-tamer-by-animationframe)
3. [YouTube Live Chat Tamer](https://greasyfork.org/scripts/468838/) (if there is chatroom in your watch page)
4. [YouTube Super Fast Chat](https://greasyfork.org/scripts/469878/) (if there is chatroom in your watch page)

Please also ensure that you do not have styles relying on `:has(...)` selector very much.

## Compatibility

### Compatible Userscript Managers

* Tampermonkey / Tampermonkey beta
* ViolentMonkey

### Compatible Web Browsers

* Chrome / Chromium / Edge
* Firefox / Waterfox / LibreWolf / Brave
* Safari
* Waterfox Classic
* Vivaldi / Opera
* Cent / Catsxp / Maxthon

*Waterfox Classic is Firefox 55 / 56 which shall use [violentmonkey](https://addons.mozilla.org/en-US/firefox/addon/violentmonkey/) and [Tampermonkey 4.8.5847](https://addons.mozilla.org/firefox/downloads/file/1076900/tampermonkey-4.8.5847.xpi)*

### Compatible YouTube Features

* [360° Video](https://www.youtube.com/watch?v=2h3pbdTPu6Q)
* Mini Player View
* ~~[Teaser UI](https://www.socialmediatoday.com/news/youtubes-moving-the-placement-of-video-comments-on-desktop/624325/) (partial support)~~ Removed due to Teaser UI abandoned by YouTube
* [Darker Dark Layout (Modern Layout 2022) with Dark Mode Cinematics](https://9to5google.com/2022/10/26/new-dark-youtube-gallery/)
* Playlist Row Highlight (introduced by the end of 2022)

### Compatible Userscript / Plugin / Extension

* [Maximize Video](https://greasyfork.org/scripts/4870)'s ESC Video Full Page
* [Youtube - Search While Watching Video](https://greasyfork.org/scripts/29451-youtube-search-while-watching-video)'s In-page Video Search
* [YouTubeLiveClock](https://chrome.google.com/webstore/detail/youtubeliveclock/chpodcedholiggcllnmmjlnghllddgmj) *Chrome Version:* **105+**
* [Youtube Genius Lyrics](https://greasyfork.org/en/scripts/386259-youtube-genius-lyrics)
* [YouTube Comment Translation Button](https://greasyfork.org/scripts/456108)
* [YouTube Livestreams Theater Mode](https://www.napalighost.com/youtube-livestreams-theater-mode)

### Also see...

* @"CY Fung" - [YouTube CPU Tamer by AnimationFrame](https://greasyfork.org/scripts/431573-youtube-cpu-tamer-by-animationframe)
* @"CY Fung" - [HTML Video Player Enhance](https://greasyfork.org/scripts/390143-html5-video-player-enhance)
* @"CY Fung" - [Youtube Subtitle Caption Stylish](https://greasyfork.org/scripts/458161-youtube-subtitle-caption-stylish)
* @"CY Fung" - [Youtube MiniView](https://greasyfork.org/scripts/429064-youtube-miniview)
* @Cptmathix - [YouTube Play Next Queue](https://greasyfork.org/scripts/28678-youtube-play-next-queue)
* @Cptmathix - [Youtube - Search While Watching Video](https://greasyfork.org/scripts/29451-youtube-search-while-watching-video)
* @cuzi / @"CY Fung" - [Youtube Genius Lyrics](https://github.com/cvzi/Youtube-Genius-Lyrics-userscript) (10.9.9 or above)
* @knoa - [Youtube Live Filled Up View](https://greasyfork.org/scripts/394945-youtube-live-filled-up-view)
* @linkwanggo - [YouTube Comment Translation Button](https://greasyfork.org/scripts/456108)
* @ok! - [u-Youtube](https://greasyfork.org/scripts/442317-u-youtube)
* @冻猫 - [Maximize Video](https://greasyfork.org/scripts/4870)

*Remarks: Auto-generated Music Video can be commented since Dec 2022.*
