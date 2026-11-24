# Sugu Clips

Instant replay game clipping for Windows. Press F8 to save the last few seconds of gameplay, or let it clip your kills automatically.

## Download

Get the latest `Sugu-Clips-Setup-x.x.x.exe` from [Releases](https://github.com/sugur-a/Sugu-Clips-releases/releases/latest) and run it. Nothing else needs installing.

Windows might say "Windows protected your PC" because the app isn't signed yet. Click **More info** then **Run anyway**.

The app updates itself from here, so you only need to download it once.

## What it does

- Keeps the last 15 seconds to 2 minutes in a buffer and saves it when you press the hotkey
- Records just the game window when it spots a game you're playing
- Auto clips kills in League, CS2, and any game you teach it (Valorant, The Finals...)
- Trims and exports clips for TikTok, Shorts and YouTube
- Small pop-up in the corner when a clip saves

Nothing hooks into or reads the game. Recording uses Windows' own capture, and kill detection uses official game APIs or just looks at the recorded video.
