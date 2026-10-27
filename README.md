<div align="center">

<img src="logo.png" width="104" alt="MuteFlow logo">

# MuteFlow

**Quiet your noisy apps with one key.**  
Per-app muting and volume control for Windows, from anywhere, even in the middle of a game.

<br>

![Latest release](https://img.shields.io/github/v/release/dimondevrepo/muteflow-releases?style=for-the-badge&color=7566F6&label=latest)
![Downloads](https://img.shields.io/github/downloads/dimondevrepo/muteflow-releases/total?style=for-the-badge&color=7566F6)
![Platform](https://img.shields.io/badge/Windows-10%20%7C%2011-7566F6?style=for-the-badge)

<br>

### [⬇&nbsp; Download the latest version](https://github.com/dimondevrepo/muteflow-releases/releases/latest)

<sub>Single `.exe`, no installer. Download, run, done.</sub>

</div>

---

## Why MuteFlow

Discord is too loud, a browser tab starts autoplaying, your music drowns out a call. You shouldn't have to alt-tab to a volume mixer. Pick the apps once, then mute or restore them all with a single key.

## Features

| | |
|---|---|
| ⌨️ **One-key control** | Press your hotkey to mute the selected apps, press it again to bring them back exactly as they were. |
| 🎚️ **Mute or lower** | Full mute, or drop the apps to a volume level you choose (0-100%). |
| 🖼️ **Real app icons** | Pick apps from a clean list of everything currently playing audio. |
| 🌍 **Layout-proof hotkey** | Bound to the physical key, so it keeps working when you switch keyboard language. Holding other keys never interferes. |
| 💬 **Overlay notification** | A small see-through indicator shows what is muted. Click-through, never steals focus, and you choose the screen corner. |
| 🔔 **Soft sound cue** | An optional gentle chime when apps are muted or restored. Off by default. |
| 🫥 **Lives in the tray** | Minimize or close to the tray, and optionally start with Windows. |
| 🎨 **Themes** | Midnight, Ocean and Rose. |
| 🔄 **Built-in updates** | Checks for new versions and installs them in a click, with a restart confirmation. |

<!-- Add screenshots to a docs/ folder and uncomment:
<p align="center">
  <img src="docs/overview.png" width="720" alt="MuteFlow overview">
</p>
-->

## Get started

1. **Download** `MuteFlow-x.y.exe` from the [latest release](https://github.com/dimondevrepo/muteflow-releases/releases/latest) and run it.
2. Open the **Apps** tab and switch on the apps you want to control. An app shows up in the list while it is playing audio.
3. Press your hotkey (default `F9`) to mute them, and press it again to restore. You can change the key on the **Overview** page with **Change**.

## Updating

MuteFlow checks for updates on startup (you can turn this off in **Settings**). When a new version is available, use **Settings → Check for updates**, then **Update**. After the download it asks before restarting, and your settings are kept.

## FAQ

<details>
<summary><b>Windows SmartScreen warns me when I run it.</b></summary>
<br>
The app is not code-signed yet, so Windows is cautious with new files. Click <b>More info</b>, then <b>Run anyway</b>.
</details>

<details>
<summary><b>An app is missing from the list.</b></summary>
<br>
Apps only appear while they are playing audio. Start the sound, then press <b>Refresh</b> on the Apps tab. Once selected, an app stays in your list even when it is closed.
</details>

<details>
<summary><b>The overlay doesn't show in my game.</b></summary>
<br>
It appears over windowed and borderless games. Windows does not allow overlays on top of exclusive fullscreen.
</details>

<details>
<summary><b>Is it safe to use in games with anti-cheat?</b></summary>
<br>
MuteFlow never touches game processes. It does not inject code, read memory or send input; it only changes volume through the Windows audio mixer. It does use a global keyboard hook to detect your hotkey, the same mechanism many utilities use. Anti-cheat systems are strict and make their own decisions, so no one can guarantee it, and you use it at your own risk.
</details>

<details>
<summary><b>Where are my settings stored? How do I uninstall?</b></summary>
<br>
Settings live in <code>%APPDATA%\MuteFlow</code>. To uninstall, turn off <b>Start with Windows</b> in Settings, delete the <code>.exe</code>, and optionally delete that folder.
</details>

## Privacy

MuteFlow collects nothing and has no accounts or telemetry. The only network request it makes is the update check to this repository's releases on GitHub.

## Requirements

Windows 10 or 11, 64-bit.

## Feedback

Found a bug or have an idea? [Open an issue](https://github.com/dimondevrepo/muteflow-releases/issues).

<sub>MuteFlow's source code is private. This repository only hosts the releases.</sub>
