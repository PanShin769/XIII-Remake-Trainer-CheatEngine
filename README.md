# XIII Remake (2020 / 2022 Update) - Free Trainer & Cheat Engine Table (v2.0)
Free Cheat Engine Trainer (.exe) &amp; Cheat Table (.ct) for XIII Remake (Post-2022 Update) - God Mode, Full Health/Armor, Unlimited Ammo.

[![Platform](https://img.shields.io/badge/Platform-Windows%20x64-blue)]()
[![Game Version](https://img.shields.io/badge/Game%20Version-Steam%20%2F%20GOG%20Latest%20(Post--2022%20Remake%20Update)-green)]()
[![License](https://img.shields.io/badge/Mode-Single--Player%20Only-orange)]()

A lightweight, free, and open-source **Cheat Engine Trainer (`.exe`) & Cheat Table (`.ct`)** for **XIII Remake** (Tower Five updated version). Designed to work cleanly with the game's native Unity IL2CPP methods without breaking HUD updates or triggering crashes.

> **Keywords:** XIII Remake Trainer, XIII 2020 Cheat Table, XIII Remake God Mode, Unlimited Health, Full Armor, Unlimited Ammo, Free Download, Cheat Engine 7.5+

---

## ✨ Features & Hotkeys

| Hotkey | Feature | Technical Mechanism & Notes |
| :--- | :--- | :--- |
| **`Numpad 1`** | **God Mode + Auto Full Health / Armor / Oxygen** | Hooks `PlayerState.CanReceiveDamage` to block incoming damage (`false`). Automatically invokes native `ResetHealth(true)` and `AddArmor(100)` on hit/trigger to restore full HP, 100% Armor, and full Breath while properly refreshing the HUD bars. |
| **`Numpad 2`** | **Unlimited Ammo / No Reload** | Prevents weapon magazine and reserve ammo depletion during combat. |

*(Note: Hotkeys can be customized anytime by opening the included `.ct` file in Cheat Engine.)*

## 🎥 Gameplay & Trainer Showcase

https://youtu.be/QfJhHEO-SiA

---

## 📥 Download & How to Use

Head over to the [**Releases Page**](../../releases) to download the latest `XIII_Remake_Trainer_V2.zip` package (contains both the standalone `.exe` trainer and the open-source `.ct` Cheat Table).

### Option A: Using the Standalone `.exe` Trainer (No Cheat Engine Required)
1. Launch **XIII Remake** and load into your single-player campaign save.
2. Run **`XIII Remake Trainer V2.exe`** **as Administrator** (required for process memory attachment).
3. Press **`Numpad 1`** or **`Numpad 2`** in-game to toggle features on/off. *(If your HP/Armor is currently low, take one hit or jump off a ledge once to trigger the instant full-restore hook).*

### Option B: Using the `.ct` Cheat Table (Recommended for Transparency)
1. Install and open **Cheat Engine (v7.4 or newer)** as Administrator.
2. Load `XIII_Remake.ct`, click the **Select a process to open** icon, and attach to **`XIII.exe`**.
3. Check the boxes next to the desired scripts or use the assigned hotkeys.

---

## ⚠️ Antivirus / Windows Defender False Positive Notice

Because the standalone `.exe` is compiled using **Cheat Engine's built-in Trainer Generator**, Windows Defender or third-party antivirus software may flag it as **`HackTool:Win32/CheatEngine`** or **`PUA:Win32/GameHack`**.

* **This is a 100% false positive** inherent to all Cheat Engine standalone executables due to memory injection behavior.
* **Verify it yourself:** If you prefer not to run the `.exe`, simply open the included **`.ct` file** in Notepad or Cheat Engine—it is plain-text XML/Auto-Assemble script containing zero obfuscated or external network code.
* **Fix if blocked:** Add your download folder to Windows Security Exclusions or restore the file from *Protection History*.

---

## 📋 Compatibility & Disclaimer

* **Supported Versions:** Tested on the latest Steam & GOG x64 builds (Post-2022 Tower Five Remake Update). *Not compatible with the unpatched 2020 launch build or XIII Classic (2003).*
* **Single-Player Only:** Strictly intended for offline single-player enjoyment. Do not use in multiplayer lobbies.
* **Author:** Created by **pansheng** using Cheat Engine & `Il2CppDumper`.
