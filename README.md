# Game Presence

Show **just the game you're playing** on your Discord profile, with no "GeForce NOW" in the name. If it ever shows the wrong game, fix it in two clicks.

> Not affiliated with, endorsed by, or sponsored by Discord or NVIDIA.

<!-- Add a screenshot here: ![Game Presence](screenshots/app.png) -->

## Features

- Shows **"Playing <game name>"** on your Discord profile, with the real game's name and a running timer
- **Auto-detect** the game from your GeForce NOW window (when available)
- **Fix a wrong game** any time by searching and picking the right one
- Optional **Details** and **State** lines, like "Ranked" or "In match"
- Up to **2 profile buttons** with your own links (your server, Twitch, YouTube...)
- **Auto-clear**: your game disappears when GeForce NOW closes

## Requirements

- Windows 10 or 11
- The **Discord desktop app**, open and logged in (the browser version does not work)

## Install

1. Go to the **[Releases](../../releases)** page and download **`Game Presence Setup x.x.x.exe`**.
2. Double-click the file. It installs by itself and opens the app.
3. Use the **Game Presence** icon on your desktop or in the Start menu from now on.

### "Windows protected your PC" warning

The installer isn't code-signed, so Windows may show a blue SmartScreen warning the first time. This is normal for small free apps.

1. Click **More info**.
2. Click **Run anyway**.

## How to use

### Show a game

1. Open **Game Presence** (keep Discord open).
2. Type the game's name in **Search** and click it in the list.
3. Optionally fill in **Details** and **State**.
4. Click **Set game**.

Your Discord profile now shows **Playing <game>**.

### Use auto-detect

Turn on the **Auto-detect** switch. While GeForce NOW is running, the app reads its window and switches your game automatically.

- The **Detected title** line under the switch shows what it found.
- Auto-detect only works if the GeForce NOW window title contains the game name. If it stays empty, pick the game manually.
- Picking a game by hand turns auto-detect off. Switch it on again whenever you like.

### Fix a wrong game

1. Search for the correct game and click it.
2. Click **Set game**.

If the wrong game came from auto-detect, the app remembers your fix for next time.

### Add profile buttons

1. In **Profile buttons**, type a **label** (like `Join my server`) and a **link** that starts with `https://`.
2. Add a second button if you want.
3. Click **Save**.

Notes:

- **You can't see your own buttons.** Other people can. Ask a friend or check from another account.
- Buttons appear next to your game, so they only show while a game is set.
- Discord may not show buttons everywhere, such as some mobile views. That is Discord's behavior.
- Use public links only, since anyone who can see your activity can click them.

### Remove your game or buttons

- **Clear** (top of the app, or next to **Set game**) removes your game from Discord.
- **Clear buttons** removes the profile buttons.

### Auto-clear

With **Auto-clear** on, your game is removed about 30 seconds after GeForce NOW closes, so you never show a game you've quit.

## Good to know

- Closing the app window **quits the app**, and your presence disappears. Minimize it while you play.
- Your saved fixes and settings are stored on your PC only. Nothing is sent anywhere except to Discord's local app and Discord's public game list.
- The list of games comes from Discord. If a game isn't in the search, it can't be shown.

## Troubleshooting

| Problem | What to try |
|---|---|
| The app won't open | Press Ctrl+Shift+Esc, end any **Game Presence** tasks, and open it again. |
| "Could not reach Discord" | Open the **Discord desktop app** and make sure you're logged in, then try **Set game** again. |
| My game shows on Discord but not for me | Look at your profile from another account, or ask a friend. Your own buttons are hidden from you. |
| The buttons don't show | Check that the link starts with `https://`. If an orange warning appears in the app, Discord rejected the buttons for that game. |
| The game I want isn't in the search | Discord doesn't list it, so it can't be shown with this app. |
| "GeForce NOW" still shows next to my game | Turn off Discord integration in the GeForce NOW settings if it has that option, or hide it in Discord under **Settings → Activity Privacy**. |
| Auto-detect shows nothing | The GeForce NOW window title doesn't include the game name. Pick the game manually. |
| Windows or antivirus flags the installer | The installer is unsigned. See the SmartScreen steps above. |

## Uninstall

**Windows Settings → Apps → Installed apps → Game Presence → Uninstall.**

## Feedback and bugs

Open an issue on this repository and include what you were doing and what you saw.

## Disclaimer

Game Presence is an independent hobby project. It uses Discord's local app connection and Discord's public game list in a way that isn't officially documented, so Discord could change or block it at any time. Use it at your own risk.
