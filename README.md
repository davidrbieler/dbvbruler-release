<p align="center">
  <img src="logo/app-icon.png" width="300" alt="dbvbruler logo" />
</p>

<h1 align="center">dbvbruler</h1>

<p align="center">
  Volleyball court zone lines that float on top of any video/scouting app 
</p>

---

## About

**dbvbruler** is an app that draws reference lines over your match video so you can easily see the 9 court zones directly on top of wherever you're scouting: VolleyStation/VSO, Daatavolley, VolleyMetrics/Hudl, etc.

A simple calibration process (~10 seconds) will calculate where the rest of the lines should go, making coordinate cleaning *much* simpler

<img width="1395" height="815" alt="image" src="https://github.com/user-attachments/assets/aeecaf1b-39ef-4402-911b-86785cd927a8" />

Customization options include:
- Color/Opacity/Number of lines drawn
- Profiles to save calibration on frequently uesd camera angles (home Volleymetrics cameras)
- Changeable keybinds
- External monitor support
  
## Requirements

- **Windows 10 or 11**

---

## Download or Install

1. Go to the **[Releases page](https://github.com/davidrbieler/dbvbruler/releases)**.
2. Under the newest release, click **Assets**
3. Download the installer: **`dbvbruler_x.x.x_x64-setup.exe`** or the standalone exe: **`dbvbruler.exe`**
4. Double-click the downloaded file to install or run it

> **"Windows protected your PC"?**
> Because this is a small independent app (not signed with a paid certificate), Windows may show a warning box the first time. Just click **More info**, then **Run anyway**.

---

## Usage

While running, the app lives in the system tray.  Right-click the app icon for a menu: **Toggle window**, **Recalibrate**, **Quit**.

There are **two modes**, one shortcut (default **`Ctrl + Alt + R`**) flips between them:

| Mode | What it means |
|---|---|
| **Window ON** | The menu appears to the left and catches your clicks. Use this to set up, customize, or calibrate. *While it's on, clicks go to the overlay, not to your other apps.* |
| **Window OFF** | Your clicks go straight through to whatever app is underneath, but the lines stay visible. **This is the mode you scout in.** |

> **`Ctrl + Alt + R`** switches between the two, from anywhere. If it ever feels like your mouse "isn't working" on your other apps, you're just in **Window ON** mode. Press `Ctrl + Alt + R` to toggle it off.
<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/6f0397ca-ef09-4d08-9515-6c16cef5da6f" />

---

## Calibration and Profiles

You only have to do this once per camera angle / video source.

1. Get your video on screen, **paused on a frame that shows the whole court clearly** (ideally no players standing on the lines).
2. Click **New Profile** or press the shortcut (default **`Ctrl + Alt + C`**)
4. The guide bar at the top will tell you **which point to click next**, a total of 10 times:
   - the 4 court **corners**,
   - the 2 spots where the **midline meets the sidelines**,
   - the 4 ends of the **3-meter lines**.
5. After the 10th click, your **divider lines are drawn on the court**. The app automatically switches the window off so you can get back to scouting.

If you mess up during calibration, **`Ctrl + Alt + Z`** undoes the last point, **`Ctrl + Alt + X`** cancels and starts over.

> If the lines look off later, just press **`Ctrl + Alt + C`** or press recalibrate to redo it. Calibration is tied to where the video sits on your screen, so if you move or resize the video window, recalibrate.

---

## Troubleshooting

- **My mouse won't click other apps.** You're in **Window ON** mode. Press **`Ctrl + Alt + R`** to toggle it off.
- **The lines don't line up with the court.** The video probably moved or resized since you calibrated. Press **`Ctrl + Alt + C`** or click the recalibrate button.
- **Nothing shows up / I can't find the window.** Look for the **`dbvbruler` system tray icon** and right-click it. The overlay has no taskbar button by design (so it doesn't get in your way).
- **The video went dark while I was clicking around the panel.** Most video websites or apps hide/disappear when losing focus to save system resources. It comes back as soon as you click the video again and won't affect calibration as it uses a screenshot.
- **A "screen recording" style app won't show through.** Some video players use copy-protected (DRM) video that renders black to any overlay/screenshot. Those sources can't be calibrated against but the major ones have been tested and work fine (Volleystation Online, Volleymetrics, Youtube)
- **To close it:** right-click the tray icon → **Quit**.

---
