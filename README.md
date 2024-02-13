# BetterUI v1.0.2 - LessonLethal | CLIENT SIDE 🎈

[![Latest Version](https://img.shields.io/thunderstore/v/LessonLethal/BetterUI?logo=thunderstore&logoColor=white)](https://thunderstore.io/c/lethal-company/p/LessonLethal/BetterUI)
[![Total Downloads](https://img.shields.io/thunderstore/dt/LessonLethal/BetterUI?logo=thunderstore&logoColor=white)](https://thunderstore.io/c/lethal-company/p/LessonLethal/BetterUI)

![Banner](https://i.imgur.com/1OexyaD.png)

Better Controls for HUD, Clock, Chat, and FPS with Addition Hotkeys

# FEATURES 📃

### 👉 UI/HUD
You can toggle on and off the visibility of all UI/HUD elements on the screen, with the push of a hotkey that you can set.

```Default Hotkey: Keypad7```

### 👉 FPS
Adds a FPS counter to the top right corner of the screen that is simple and small. You can toggle it on and off with the push of a hotkey that you can set. It's off by default.
  
```Default Hotkey: Keypad8```

### 👉 CLOCK
By default, a player can only see the time of day when outside on a moon. With the push of a key, this toggles the clocks visibility when you're inside a facility, mansion, or ship between 0% visibility (vanilla) and 30% visibility. *By default it's 0% visibility (vanilla) until you turn it on with hotkey.*

```Default Hotkey: Keypad9```

### 👉 CHAT
Changes the chat area to fade out when not being used. It will appear again if you receive or want to send a message. *The chat area is affected when you toggle the hotkey for UI/HUD visibility.*

### 👉 FRAME RATE
Set Target Frame Rate to 500 and turn vSync OFF with a config setting.

```default: false```

### 👉 SMOOTH CLOCK
Smooth the speed of time on the clock with a config setting.

```default: true```

# CONFIGURATION ⚙
### Run the game once after installing this mod for it to create the config file.
#### Open ```BepInEx/config/LessonLethal.BetterUI.cfg``` with a text editor.

```
HUDKeybind - Hotkey to toggle the visibility of all UI elements on your screen.
Default value: Keypad7
```

```
FPSKeybind - Hotkey to toggle the visibility of a simple FPS counter located top right.
(FPS monitor/counter hidden by default)
Default value: Keypad8
```

```
ClockKeybind - Hotkey to toggle the visibility of the clock when you're inside the facility, mansion, or ship. 
(Clock hidden by default inside the facility, mansion, or ship)
Default value: Keypad9
```

```
FrameRateOverride - Set Target Frame Rate to 500 and turn vSync OFF
Default value: False
```

```
SmoothTimeOverride - Smooth the speed of time on the clock (appearance only)
Default value: True
```

# Installation 🛠

## R2ModMan or Thunderstore Manager (highly recommended)

### R2ModMan
1. Go to the [thunderstore page](https://thunderstore.io/c/lethal-company/p/LessonLethal/BetterUI/)
2. Click `Install with Mod Manager`

### Thunderstore Manager
(if the above doesn't work for you, open up the Thunderstore App to do the following)
1. Click `Get mods`/`Online` (whatever it happens to be called)
2. Search for BetterUI
3. Download it

## Manual
1. Go to the [thunderstore page](https://thunderstore.io/c/lethal-company/p/LessonLethal/BetterUI/)
2. Click `Manual Download`
3. Unzip files
4. Navigate to `LessonLethal-BetterUI-VERSION/BepinEx/plugins` and copy the contents
5. Find your BepinEx installation's plugin folder, by default it would be in steamapps: `steamapps\common\Lethal Company\BepInEx\plugins`
6. Create a folder titled `LessonLethal-BetterUI`
7. Paste the contents into that folder

If you did all of this correctly, it should load properly.

The resulting file structure should look like this:
```
BepinEx
├───cache
├───config
├───core
├───patchers
└───plugins
    └───LessonLethal-BetterUI
        └───BetterUI.dll
```

# TODO 📝
- Add a list to this README of all keyboard shortcuts possible when setting hotkeys.
- Add support for [InputUtils](https://thunderstore.io/c/lethal-company/p/Rune580/LethalCompany_InputUtils/)

# Contact
Discord: @[tyleroutcast](https://discord.com/users/235518194612305920)

# Credits
Thanks to the following who helped and inspired this project:
- [BlueAmulet](https://thunderstore.io/c/lethal-company/p/BlueAmulet/) - LCBetterClock: smooth time updating
- [Cookies](https://thunderstore.io/c/lethal-company/p/Cookies/) - NoHUD
- [Monkeytype](https://thunderstore.io/c/lethal-company/p/Monkeytype/) - HideChat
- [Solar32](https://thunderstore.io/c/lethal-company/p/Solar32/) - PerformanceEnhancer: fps & frame rate changes
