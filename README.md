# Taskbar App Volume Control 🔊

[![Windhawk Mod](https://img.shields.io/badge/Windhawk-Mod-blue?style=for-the-badge&logo=windows)](https://windhawk.net/)
[![Version](https://img.shields.io/badge/Version-1.0-green?style=for-the-badge)](https://github.com/tz39/Taskbar-APP-Volume-Control)

**Control individual application volumes directly from your Windows Taskbar.**

This [Windhawk](https://windhawk.net/) mod allows you to adjust the volume of specific running applications simply by scrolling your mouse wheel over their taskbar icons. It seamlessly integrates with Windows 10 and 11, providing a convenient and intuitive way to manage your audio mix without opening the Volume Mixer.

---

## ✨ Features

- **Per-App Volume Control**: Hover over any open application on the taskbar and scroll to adjust its specific volume.
- **System Volume Control**: Scroll over empty space on the taskbar to adjust the master system volume.
- **Quick Mute**: Middle-click on an application's taskbar icon to instantly toggle mute.
- **Smart Detection**: automatically detects audio sessions for most applications, including browsers (Chrome, Firefox, Edge), media players (Spotify, VLC), and communication tools (Discord, Teams).
- **High DPI Support**: Optimized for modern high-resolution displays.
- **Customizable**: extensive settings to tailor the behavior to your preference.

## 🚀 Installation

This mod is designed for **Windhawk**, the comprehensive customization marketplace for Windows.

1.  **Download & Install Windhawk**:
    Get it from [windhawk.net](https://windhawk.net/).

2.  **Get the Mod**:
    - Open Windhawk.
    - Search for **"Taskbar App Volume Control"**.
    - Click **Install**.

    *Alternatively, if you have the source code (`volume.wh.cpp`), you can create a new mod in Windhawk and paste the code into the editor.*

## 🎮 How to Use

| Action | Result |
| :--- | :--- |
| **Scroll on App Icon** | Changes volume for **that specific app** (e.g., Spotify, Chrome). |
| **Scroll on Empty Taskbar** | Changes **Global System Volume**. |
| **Middle-Click App Icon** | Mutes / Unmutes the application. |
| **Ctrl + Scroll** | (Optional) Hold Ctrl while scrolling for finer control (configurable). |

## ⚙️ Configuration

You can customize the mod via the Windhawk settings tab:

- **Scroll Area**: Define where the scroll action triggers (Taskbar, Notification Area, etc.).
- **Volume Step**: Set how much the volume changes per scroll tick (default is 2%).
- **Middle Click to Mute**: Enable/Disable the mute shortcut.
- **Modifier Keys**: Toggle requirement for modifier keys like `Ctrl` or `Shift`.
- **Targeting Mode**: Optimize for Windows 10 or Windows 11 taskbar styles.

## 🧩 Supported Applications

The mod uses a **Smart Match** system to detect audio sessions. It works out-of-the-box with almost all modern Windows applications, including but not limited to:

- **Browsers**: Chrome, Firefox, Edge, Brave, Opera, Vivaldi.
- **Music/Video**: Spotify, iTunes, VLC, Netflix App.
- **Social**: Discord, Microsoft Teams, Slack, Telegram, WhatsApp.
- **Games**: Most games running in windowed/borderless modes, Steam, Epic Games Launcher.

*Note: If an app is not detected, check if it is running as Administrator (Windhawk might need elevated privileges).*

## 🛠️ Troubleshooting

- **Volume not changing?** Ensure the application is actually playing audio or has an active audio session. Some apps don't create an audio session until they make a sound.
- **Wrong app adjusted?** In rare cases with grouped windows, the mod might target the active instance. Ungrouping icons usually resolves this.
- **Windows 11 Support**: Ensure you have selected the correct "Old Taskbar" setting if you are using mods that restore the Windows 10 taskbar styles.

## 📄 License & Credits

- **Author**: [tz39](https://github.com/tz39)
- **License**: The code is provided as a Windhawk mod; check the specific license terms within the Windhawk platform or the source header.

---

*Enjoying the mod? Star the repo or leave a review on Windhawk!* ⭐
