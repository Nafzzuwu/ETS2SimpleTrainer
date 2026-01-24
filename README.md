# 🚚 Euro Truck Simulator 2 Trainer

![ETS2 Banner](https://img.shields.io/badge/Game-Euro%20Truck%20Simulator%202-orange?style=for-the-badge) ![Language](https://img.shields.io/badge/Made%20With-C%23-purple?style=for-the-badge) ![Status](https://img.shields.io/badge/Status-UNDETECTED-brightgreen?style=for-the-badge)

> **Rule the Roads Instantly!**
> Simple, Lightweight, and Effective. No need for manual Cheat Engine tables.

---

## 📋 About The Project
An external trainer application for **Euro Truck Simulator 2 (ETS2)** built using C# and memory manipulation (.NET Framework). This tool is designed for players who want to focus on truck modifications or map exploration without the grind for money or levels.

It is lightweight, portable (plug & play), and features an **Auto-Attach** mechanism.

---

## 🔥 Key Features

### 💸 1. Money Injector
Running low on cash for that Scania V8? No problem.
* Instantly adds cash (**Euros**) to your save game.
* **Options:** +€500k, +€1 Million, +€2 Million.

### 🆙 2. Experience (XP) Booster
Low level locking you out of cool parts?
* Instantly adds **XP** to your progress.
* **Benefit:** Grants effectively **Unlimited Skill Points** as your level increases rapidly.

### 🛡️ 3. Protection System (No Damage)
* Crash into anything without taking damage to your Truck, Engine, Wheels, or Cargo.
* Perfect for reckless high-speed driving.

### ⛽ 4. Infinite Fuel (NEW)
* Locks your fuel tank to **Full Capacity** (1500L). You never need to visit a gas station again.
* **Usage Note:** This feature can **ONLY** be activated when you are inside the truck (Drive Mode). It cannot be enabled from the Main Menu/Lobby because the game hasn't loaded the truck physics yet.

### 🚀 5. Speed Hack / Turbo Mode (NEW)
* Forces your wheels to spin at high velocity instantly.
* **Controls:**
    * **Toggle ON/OFF:** Press `[DELETE]`
    * **Activate Boost:** Hold `[W]` (Gas) while enabled.

---

## 🚨 IMPORTANT: PREVENTING CRASHES (Speed Hack)

The **Speed Hack** modifies the wheel physics in real-time. Because the game engine resets physics when changing states, you must follow these rules to avoid crashing the game:

1.  **Searching Phase:** When you change trucks, modify your truck in the garage, or take a new job, the trainer will display **"SEARCHING POINTER..."**. This is normal; wait until you are in the driver's seat for it to say **"SYSTEM READY"**.
2.  **THE GOLDEN RULE:** Before you **Finish a Job** (docking the trailer) or **Abandon a Job**, you **MUST manually turn OFF the Speed Hack** using the `[DELETE]` key.
    * *If you finish a job while the Speed Hack is forcing wheel spin, the game memory will conflict and **CRASH** to the desktop.*

---

## 📸 Screenshots

| Main Menu | Connected Status |
| :---: | :---: |
<img width="347" height="434" alt="image" src="https://github.com/user-attachments/assets/f4cf0361-385c-4939-9c77-7b14afcc7c1e" />

---

## 🛠️ How to Use

1. **Launch Game:** Open Euro Truck Simulator 2 and load your profile.
2. **Enter Drive Mode:** Go into the truck (Driving view). **This is required for Fuel and Speed hacks to detect addresses.**
3. **Run Trainer:** Open `ETS2_TrainerByNafzz` (Recommended: *Run as Administrator*).
4. **Execute:**
    * Click Money/XP buttons for instant rewards.
    * Check "No Damage" or "Infinite Fuel" to freeze those values.
    * Press `[DELETE]` to toggle Speed Hack (Read the warning above!).
5. **Profit:** Enjoy the game!

---

## ⚠️ Antivirus Warning (False Positive)

Since this application works by **manipulating the RAM (WriteProcessMemory)** of another process (the game), some Antivirus software might flag it as a threat or a "HackTool".

* **It is Safe:** This is standard behavior for Game Trainers. There is no malicious code.
* **Solution:** If the file gets deleted, please disable your Antivirus temporarily or add the trainer folder to your *Exclusion List*.

---

## ⚙️ Requirements
* OS: Windows 10 / 11
* Game: Euro Truck Simulator 2 (Tested on Latest Version)
* .NET Framework 4.7.2 or later.

---

## 📝 Disclaimer
This tool is for **Educational Purposes** (learning C# Memory Manipulation) and **Single Player** use only. I am not responsible for any corrupted save files (always backup your save!) or bans if used in Multiplayer modes (TruckersMP).

---

<p align="center">
  Made with ❤️ by <b>Nafzz</b>
</p>
