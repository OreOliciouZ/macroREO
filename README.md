# MacroREO ▶️

<p align="center">
  <strong>The Lightest & Fastest Native Macro Recorder for Windows.</strong><br>
  <em>Engineered for precision. Built for speed. Optimized for zero footprint.</em>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Language-C%23-blue?style=for-the-badge" alt="C#">
  <img src="https://img.shields.io/badge/Platform-Windows-0078d7?style=for-the-badge&logo=windows" alt="Windows">
  <img src="https://img.shields.io/badge/Size-~520_KB-success?style=for-the-badge" alt="Size">
  <img src="https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge" alt="License">
</p>

---

## 🚀 The Native Evolution
MacroREO has been completely rewritten in native C# to deliver a seamless Windows experience that eliminates the bloat of traditional recorders.

- **Instantaneous Launch:** Zero load time. By leveraging the native Windows environment, the UI pops up the millisecond you click it.
- **Ultra-Lightweight:** At just **~403 KB**, it provides heavy-duty functionality in a tiny package without external dependencies.
- **Structured Logging:** The custom `.oreo` format utilizes clean JSON pathing with dedicated `start` and `finish` markers for perfect timing accuracy.

---

## ✨ Key Features

- 🖥️ **Modern Compact UI:** A sleek, high-DPI 380x95px toolbar designed to stay out of your way.
- 🛡️ **Auto-Admin Detection:** Automatically detects if the app is running with elevated privileges (required for games).
- ⌨️ **Global System Hooks:** Control your macros with global hotkeys even while working in other applications.
- 🚫 **Smart Exclusion:** Intelligent window-detection logic prevents the app from recording its own button interactions.
- 📥 **Background Mode:** Fully supports System Tray minimization with **1-click restore** functionality.
- ⚡ **Variable Speed:** Dial in your workflow with playback speeds ranging from **0.5x** to **10.0x**.
- 🔄 **Infinite Loop:** A modern, mobile-style toggle switch for effortless task repetition.
- 🟢 **Live Status & Updates:** Stay informed with real-time status logging and automatic GitHub update notifications.
- 💾 **Standard Data Format:** Macros are stored in readable, portable **`.oreo`** (JSON) files.

---

## 🛡️ Standard vs. Admin Mode

MacroREO displays its current mode directly in the window title bar:

| Mode | Description |
| :--- | :--- |
| **Standard Mode** | Perfect for regular desktop tasks, web browsing, and office work. |
| **Admin Mode** | Required for **Games**, Task Manager, or installing software. |

> [!IMPORTANT]
> If your macro **does not work inside a game**, the game likely runs with higher privileges than the recorder. 
> **Solution:** Close MacroREO, right-click the `.exe`, and select **"Run as Administrator"**.

---

## ⌨️ Default Hotkeys

| Action | Key |
| :--- | :--- |
| **Start / Stop Recording** | `F8` |
| **Start / Stop Playback** | `F9` |

> [!TIP]
> You can fully rebind these keys to any combination in the **Settings (⚙️)** menu.

---

## 🛠️ How to use

1. **Record:** Press `F8` or click the 🔴 button to begin capturing your actions.
2. **Stop Rec:** Press `F8` again or click the ■ button to save the sequence.
3. **Play:** Press `F9` or click the ▶ button to execute your macro.
4. **Stop Play:** Press `F9` again or click the ■ button to cancel playback.
5. **Configure:** Click ⚙ to adjust playback speed, toggle the infinite loop, or remap your keys.
6. **Hide:** Hit the `_` button to tuck the app away into your System Tray.

---

## 📦 Requirements

- **OS:** Windows 10 or Windows 11
- **Runtime:** [.NET 8.0 Desktop Runtime](https://dotnet.microsoft.com/download/dotnet/8.0/runtime) (Standard on most modern Windows systems)

---

## 👤 Author

Created with ❤️ by **OreOliciouZ**  
[Check out my GitHub Profile](https://github.com/OreOliciouZ)

## 📄 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.