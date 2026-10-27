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
- **Auto-clear**: your game disappears when you quit the game or close GeForce NOW
- **Status text**: change the Details and State lines on the fly, without picking the game again
- **Preview**: see roughly how your activity looks to others
- **Friend-safe mode**: hide Details, State, party and buttons with one switch
- **Pause when away**: your game hides itself when you're idle and returns when you're back
- **Status per game**: each game can remember its own Details and State
- **Recent games**: your last 5 games as one-click chips under Search
- **Game icons** next to game names (loaded from Discord)
- **Connection help**: a short checklist appears when the app can't reach Discord
- **Reset everything**: clear all saved data in one click
- **Custom games**: add a game that isn't in Discord's list
- **Party size**: show "(2 of 4)" next to your State line, with an on/off switch
- **Languages**: English, Hindi, Spanish, Portuguese, French and German
- **Saved statuses**: keep up to 5 Details/State combos and switch between them in one click
- **Saved fixes list**: see and remove the corrections auto-detect remembers
- **Pause**: hide your game from Discord in one click, and bring it back when you want
- **Notifications**: an optional Windows alert when your game switches or is cleared
- **Runs in the tray** and can **start with Windows**, so it's always ready
- **Update notice** when a new version is released

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

### Change Details and State

Use the **Status text** card to add or change the two lines under the game name, like "Ranked" and "In match". Click **Update status**. It works on whatever game is showing, including ones found by auto-detect. Leave a box empty to remove that line. Each line needs at least 2 characters.

### Auto-clear

With **Auto-clear** on, your game is removed a few seconds after you quit it or close GeForce NOW, so you never show a game you've quit.

It tells that you've left the game by watching the GeForce NOW window. If it isn't clearing for you, open **Debug info** in the app, click **Copy debug info**, and include it in your bug report.

### Saved statuses

In the **Status text** card, type your Details and State and click **Save this status**. You can keep up to 5. Click **Use** on a saved status to put it on whatever game is showing, or **×** to delete it.

### Preview

The **Preview** card shows roughly what other people see: the game, your Details and State, the party size, the timer and your button names. It follows Pause and Friend-safe mode. It's an approximation, since Discord decides the final look, and you can't see your own buttons on Discord itself.

### Friend-safe mode

Switch on **Friend-safe mode** (under the Preview, or in the tray menu) to hide Details, State, party size and profile buttons. Only the game name and the timer stay. Switch it off and everything comes back. Nothing is deleted.

### Status per game

Type a Details and State, then click **Remember for this game**. From then on, that game starts with its own text, whether you pick it by hand with empty boxes or auto-detect finds it. Remembered games are listed under **Saved per game**, where you can remove them. Text you typed by hand is never copied onto a game that has its own saved status, and one game's saved status is never copied onto another. Switch **Auto-fill status per game** off in the **Behavior** card to ignore saved statuses.

### Pause when away

In the **Behavior** card, turn on **Pause when away** and choose 5, 10, 15 or 30 minutes. If you stop using the keyboard and mouse for that long, your game is hidden from Discord. Move the mouse or press a key and it returns. If you paused yourself, it stays paused until you resume.

It only counts keyboard and mouse. **Controller input may not count**, so if you play with a controller, leave this off or choose a longer time. It's off by default.

### Recent games

Your last 5 games show as chips under **Search**. Click one to select it, then click **Set game**.

### Reset everything

In the **App** card, click **Reset**, then click again within 4 seconds to confirm. It clears your saved fixes, statuses, custom games, recent games, buttons and settings, and removes the game from Discord. Your language and the Start with Windows choice stay.

### Custom games

If a game isn't in the search, you can add it yourself. Discord shows the name of the application, so you create one with the game's name:

1. Open the **[Discord Developer Portal](https://discord.com/developers/applications)** and sign in.
2. Click **New Application** and type the game's exact name. This is the name people will see.
3. On the **General Information** page, copy the **Application ID**.
4. In Game Presence, open **Custom games**, type the name, paste the ID, and click **Add game**.
5. Click **Use** next to it, then **Set game**.

It's saved on your PC, and you can add up to 25. If Discord can't connect, check that the ID was copied fully and that the Discord desktop app is open.

### Party size

In the **Status text** card, type how many people are in your party and the max (for example **2** and **4**), then click **Update status**. Discord shows it as **(2 of 4)** next to your State line.

- When someone joins or leaves, click the **+** or **−** buttons next to the numbers. Discord updates right away, no need to click **Update status**.
- Use the **Show party size** switch to hide it without losing your numbers. Switch it back on and it returns.
- Clear both boxes and click **Update status** to remove it.
- The numbers save as soon as you type them and click away from the box, with no need to click **Update status**. Both numbers are needed, from 1 to 99, and the first can't be bigger than the max.

### Language

Pick your language in the **App** card. The app starts in your Windows language when it's supported, otherwise English. Error messages from the app's engine and the tray menu stay in English.

### Saved fixes

When you correct a wrong auto-detected game, the app remembers that window title. The **Saved fixes** card (it appears once you have one) lists them. Click **×** to forget a fix and let auto-detect guess again.

### Pause

Click **Pause** at the top of the app (or **Pause presence** in the tray menu) to hide your game from Discord without losing it. Auto-detect keeps tracking, and your status text stays saved. Click **Resume** and your current game shows again.

Pause is for the current session only. If you quit and reopen the app, it starts un-paused.

### Notifications

With **Notify on game change** on, you get a Windows notification when:

- auto-detect switches to a new game (so you can spot a wrong guess), or
- your game is cleared because you quit it.

Click the notification to open the app and fix it. Switch it off in the **Behavior** card or in the tray menu. Changes you make yourself in the app don't send a notification.

If you never see them, check that Windows notifications are on for Game Presence (**Settings → System → Notifications**) and that Focus assist / Do not disturb is off.

### Tray and start with Windows

- Closing the window **keeps the app running in the tray** (bottom-right of your taskbar), so your presence stays up.
- **Right-click the tray icon** to open the app, **pause** your presence, turn notifications or **Start with Windows** on or off, check for updates, or **Quit**.
- **Start with Windows** launches the app hidden in the tray when you sign in. You can also switch it on in the **App** card.

### Updates

The app checks for new versions on its own. When one is out, an **Update available** banner appears at the top with a **Download** button. You can also click **Check for updates** in the **App** card. To update, download the new installer and run it. It replaces the old version and keeps your settings.

## Window size

The app uses a single column in a small window and switches to two columns when the window is wide, such as full screen.

## Good to know

- Game Presence shows your live "Playing" status. It does not add games to Discord's "Recent activity" history, because Discord only records games it sees running on your PC, and GeForce NOW games run on NVIDIA's servers.

- Closing the window **hides the app to the tray** and keeps your presence up. To fully exit, right-click the tray icon and choose **Quit**. Your presence disappears when the app quits.
- Your saved fixes and settings are stored on your PC only. Nothing is sent anywhere except to Discord's local app and Discord's public game list.
- The list of games comes from Discord. If a game isn't in the search, it can't be shown.

## Troubleshooting

| Problem | What to try |
|---|---|
| The app won't open, or the window doesn't appear | It may be running in the tray. Click the tray icon, or right-click it and choose **Open**. If that fails, press Ctrl+Shift+Esc, end any **Game Presence** tasks, and open it again. |
| "Could not reach Discord" | Open the **Discord desktop app** and make sure you're logged in, then try **Set game** again. |
| My game shows on Discord but not for me | Look at your profile from another account, or ask a friend. Your own buttons are hidden from you. |
| The buttons don't show | Check that the link starts with `https://`. If an orange warning appears in the app, Discord rejected the buttons for that game. |
| The game I want isn't in the search | Discord doesn't list it, so it can't be shown with this app. |
| "GeForce NOW" still shows next to my game | Turn off Discord integration in the GeForce NOW settings if it has that option, or hide it in Discord under **Settings → Activity Privacy**. |
| Auto-detect shows nothing | The GeForce NOW window title doesn't include the game name. Pick the game manually. |
| My game stays up after I quit it | Check the **GeForce NOW:** line at the top of the app. If it says "open, no game running" while you're in a game, the app can't tell when you leave. Click **Copy debug info** and report it. You can always press **Clear**. |
| I don't get game-change notifications | Make sure **Notify on game change** is on, then check Windows **Settings → System → Notifications** and turn off Focus assist / Do not disturb. |
| "Couldn't check for updates" | You may be offline, or no release exists yet. Try again later. |
| Windows or antivirus flags the installer | The installer is unsigned. See the SmartScreen steps above. |

## Uninstall

**Windows Settings → Apps → Installed apps → Game Presence → Uninstall.**

## Feedback and bugs

Open an issue on this repository and include what you were doing and what you saw.

## Disclaimer

Game Presence is an independent hobby project. It uses Discord's local app connection and Discord's public game list in a way that isn't officially documented, so Discord could change or block it at any time. Use it at your own risk.
