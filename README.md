# Cyber Command DSP — Interactive Live Wallpaper

Welcome to **Cyber Command DSP**, an interactive, music-reactive live wallpaper for your laptop or desktop. 

Every time you move your cursor or play music, warring binary factions (`0` and `1`) spawn on your screen, battle each other with lightning, and evolve into powerful Hexadecimal bosses (`0xA`, `0xF`). The central Command HUD tracks your system stats, reacts to bass drops, and lets you control the physics in real time.

---

## Folder Contents

Make sure both of these files are kept together in the same folder:
1. **`wallpaper.html`** — The main visual, physics, and audio engine.
2. **`LivelyProperties.json`** — The configuration file that adds a custom settings menu inside Lively Wallpaper.

---

## How to Install (Step-by-Step)

### Option 1: Using Lively Wallpaper (Recommended for Windows)
1. Download and install **[Lively Wallpaper](https://www.rocksdanister.com/lively/)** (Free & Open Source).
2. Put `wallpaper.html` and `LivelyProperties.json` inside a single folder, right-click the folder, and compress it into a **`.zip` file** (or simply drag `wallpaper.html` directly into Lively).
3. Open Lively Wallpaper, click the **`+` (Add Wallpaper)** button at the top, and select your `.zip` file or `wallpaper.html`.
4. **Enable Interactive Controls in Lively:**
   * Click the **Gear Icon (Settings)** in the top-right corner of Lively.
   * Go to **Input** -> Set **Mouse** to **All** and **Keyboard** to **Always**.
   * Go to **Audio** -> Check **System Audio** so the wallpaper reacts to your music.
   * Go to **Performance** -> Set **Application Fullscreen** to **Pause** (this automatically pauses the wallpaper when you play games or maximize your browser/IDE so it uses 0% battery).

### Option 2: Testing in Your Web Browser (Chrome / Brave / Edge)
1. Double-click `wallpaper.html` to open it in any modern browser.
2. **Double-click anywhere on the black screen** and allow microphone/audio access if you want to test the music visualizer directly in your browser.

---

## Mouse Controls

You can interact directly with the particles and the music equalizer using your mouse:

| Action | What It Does |
| :--- | :--- |
| **Move Cursor** | Spawns `0` and `1` fighters along your mouse trail. |
| **Left-Click & Hold** | **Singularity Vortex:** Pulls nearby fighters into a swirling gravity well. Release the click to detonate a shockwave that blasts them across the screen. |
| **Right-Click & Hold** | **Tesla Conductor:** Pulls live high-voltage lightning arcs straight from the central music equalizer ring to your cursor. |
| **Scroll Wheel (Up / Down)** | **Switch Audio Mode:** Cycles between 4 music reaction modes (`AUTO_SPECTRUM`, `SUB_BASS_CRUSHER`, `SYNTH_RAILGUN`, and `CHRONO_FREEZE`). |

---

## Keyboard Shortcuts

Press these keys at any time to control the wallpaper without opening any menus:

| Key | Function | Description |
| :--- | :--- | :--- |
| **`1` – `5`** | **Change Color Theme** | `1`: Kali Stealth Blue<br>`2`: Matrix Phosphor Green<br>`3`: Red Team Breach Alert<br>`4`: Amber CRT Phosphor<br>`5`: Ghost Covert Ops |
| **`0`** | **Custom Theme** | Switches to your custom color picker settings. |
| **`Spacebar`** | **EMP Blast** | Fires a massive shockwave from the center of the screen. |
| **`L`** | **Toggle Lasers** | Turns the equalizer's **Harmonic Railgun Lasers** ON or OFF. |
| **`H`** | **Toggle HUD** | Shows or hides the central clock, equalizer ring, and corner stats. |
| **`I`** | **Toggle Idle Battles** | Turns automatic background battles ON or OFF when you aren't moving the mouse. |
| **`C`** | **Clear Screen** | Immediately wipes all fighters and sparks off the screen. |
| **`S`** or **`P`** | **Work / Sleep Mode** | Puts the wallpaper into **0.0% CPU Standby Mode** when you need to focus on work or save battery. Press `S` again to wake it up. |

---

## Customizing via the Lively Tray Menu

You don't need to edit any code to change colors or performance settings:
1. Right-click the **Lively Wallpaper icon** in your Windows system tray (bottom-right corner near your clock).
2. Right-click your active wallpaper thumbnail and select **Customize**.
3. From here, you can:
   * Pick a **Tactical Color Matrix** preset from the dropdown.
   * Change the **HUD Header Text** (e.g., put your own username or system name).
   * Pick custom colors for Faction `0`, Faction `1`, Combat Lightning, and the Background.
   * Adjust the **Max Particle Cap** (lower it for older laptops, raise it for more chaos).
   * Adjust **Audio Gain & Bass Sensitivity**.
   * Toggle **Work Sleep Mode**, **Lasers**, and **HUD visibility** with a single click.

---

## How the Music Reactivity Works

* **Bass Drops:** Heavy bass kicks trigger central shockwaves, shake the screen, and warp the 3D background grid.
* **Musical Build-Ups (Bullet-Time):** When a song enters a vocal bridge or build-up (high vocals/synths with no bass), the wallpaper enters **slow-motion**, pulling fighters into a tight ring around the clock until the beat drops!
* **Harmonic Railgun Lasers:** When high-frequency synth or vocal notes peak, the equalizer bars automatically lock onto nearby fighters and snipe them with laser beams.