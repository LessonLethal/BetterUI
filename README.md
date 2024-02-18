# BetterUI v1.1.0 - LessonLethal 🎈

![Banner](https://i.imgur.com/hjSTjPn.png)

[![Latest Version](https://img.shields.io/thunderstore/v/LessonLethal/BetterUI?logo=thunderstore&logoColor=white)](https://thunderstore.io/c/lethal-company/p/LessonLethal/BetterUI)
[![Total Downloads](https://img.shields.io/thunderstore/dt/LessonLethal/BetterUI?logo=thunderstore&logoColor=white)](https://thunderstore.io/c/lethal-company/p/LessonLethal/BetterUI)

Custom Settings & Hotkeys for the HUD, FPS, Clock, and Chat

# FEATURES 📃

**COMPATIBILITY:** To deal with mod conflict, every feature in this mod can be individually enabled or disabled.

## 👉 HUD TOGGLE
>  Use this to disable your HUD when you want to take screenshots, video, etc.
- Toggle your HUD ON and OFF with a hotkey.
- Hides the entire HUD, except the visor. Does NOT hide menus.
> ✔️ **ENABLED** by Default. [Visit **Configuration** Section Below](#CONFIGURATION)

```Default Hotkey: Keypad7```

## 👉 FPS COUNTER
> View your FPS in a simple and non-intrusive format. 
- Toggle the FPS counter ON and OFF with a hotkey. OFF by default.
- Located at the top right corner of the screen. *Small and white...*
- You can change both the font size and color of the counter.
> ✔️ **ENABLED** by Default. [Visit **Configuration** Section Below](#CONFIGURATION)

``` Default Hotkey: Keypad8 ```

## 👉 VIEW CLOCK INSIDE
> A convenient way to view the clock while you're inside a building or ship.
- Toggle the inside clock ON and OFF with a hotkey. OFF by default.
- Affects only the visibility of clock inside the ship or a building.
- Until you use the hotkey, the clock when inside will stay at the vanilla 0% visibility.
- You can change the visibility of the (toggled ON) inside clock. By default it's set to 30% (0.3) visibility.
> ✔️ **ENABLED** by Default. [Visit **Configuration** Section Below](#CONFIGURATION)

``` Default Hotkey: Keypad9```

## 👉 REAL TIME CLOCK
> Feature for those who want a smooth clock.
- Change the clock to update in real time, affects appearance only.
- The time shown on the clock will appear to flow smoother because it is being updated much faster.

> ❌ **DISABLED** by Default. [Visit **Configuration** Section Below](#CONFIGURATION)

## 👉 CHAT AUTO FADE
> Feature for those who don't want to see the chat box when not using it.
- Changes the chat area to fade out when not being used. 
- It will appear again if you receive or want to send a message.
- The chat area is affected when you toggle the hotkey for UI/HUD visibility.

> ✔️ **ENABLED** by Default. [Visit **Configuration** Section Below](#CONFIGURATION)

## 👉 INCREASE TARGET FRAME RATE 
> **Experimental:** Use to increase maximum FPS possible. Not recommended for slower computers. 
- Set Target Frame Rate to 500.
- Set vSync to OFF.
- Shows a wider range with the FPS counter enabled.
- Can affect performance, but not made for that.

> ❌ **DISABLED** by Default. [Visit **Configuration** Section Below](#CONFIGURATION)

___

# CONFIGURATION ⚙

##### *INSTALLING MOD:* Run the game once after installing this mod for it to create the config file.

##### *UPDATING MOD:* Delete the config file and run the game to create the new config file. (Only necessary when update changes config settings)

##### CHANGE CONFIG - R2ModMan: After loading a profile, select the 'Config Editor' then search for ```BepInEx/config/LessonLethal.BetterUI.cfg``` and edit it from there.

##### CHANGE CONFIG - Manual: In most cases you can find the config file located at ```BepInEx/config/LessonLethal.BetterUI.cfg``` then just open it with a text editor.

## 🛠️ HUD SETTINGS
- `Enable_HUD` -> Type: Boolean -> Default: `true`
  - `true` -> Enables `HUD_Hotkey`
  - `false` -> Disables `HUD_Hotkey`
- `HUD_Hotkey` -> Type: KeyboardShortcut -> Default: `Keypad7`
  - [Visit **List of KeyboardShort Values** at the bottom](#)

## 🛠️ FPS SETTINGS
- `Enable_FPS` -> Type: Boolean -> Default: `true`
  - `true` -> Enables `FPS_Hotkey`
  - `false` -> Disables `FPS_Hotkey`
- `FPS_Hotkey` -> Type: KeyboardShortcut -> Default: `Keypad8`
  - [Visit **List of KeyboardShort Values** at the bottom](#)
- `FPS_Font_Size` -> Type: Int -> Default: `13`
  - Anywhere between `10` to `18` will work fine
  - Rounded numbers only
- `FPS_Font_Color` -> Type: String -> Default: `#FFFFFF`
  - [Visit Googles HEX Color Picker](https://g.co/kgs/Z3zb5f3)
  
## 🛠️ CLOCK SETTINGS
- `Enable_Clock` -> Type: Boolean -> Default: `true`
  - `true` -> Enables `Clock_Hotkey`
  - `false` -> Disables `Clock_Hotkey`
- `Clock_Hotkey` -> Type: KeyboardShortcut -> Default: `Keypad9`
  - [Visit **List of KeyboardShort Values** at the bottom](#)
- `Clock_Inside_Visibility` -> Type: Float -> Default: `0.3f`
  - `0f` = 0% Visibility of Inside Clock
  - `0.3f` = 30% Visibility of Inside Clock
  - `0.6f` = 60% Visibility of Inside Clock
  - `1f` = 100% Visibility of Inside Clock
  - You may use other values between `0` and `1` 
  - Be sure to append a `f` at the end of value
- `Real_Time_Clock` -> Type: Boolean -> Default: `false`
  - `true` -> Changes the clock to update faster
  - `false` -> Doesn't affect the clock
  
## 🛠️ CHAT SETTINGS
- `Auto_Fade_Chat` -> Type: Boolean -> Default: `true`
  - `true` -> Enables the auto fading chat box
  - `false` -> Doesn't affect the chat box
  
## 🛠️ EXPERIMENTAL SETTINGS
- `Frame_Rate_Override` -> Type: Boolean -> Default: `false`
  - `true` -> Sets target frame rate to 500 and turns off vSync
  - `false` -> Doesn't affect any display settings

___
___

# TODO 📝
- Add support for [InputUtils](https://thunderstore.io/c/lethal-company/p/Rune580/LethalCompany_InputUtils/)
- Add a conductive notification on the items icon.
- Add an items worth to its icon.

# Contact
Discord: [@tyleroutcast](https://discord.com/users/235518194612305920)

Github: [@LessonLethal](https://github.com/LessonLethal)

# Credits
Special thanks to the following who helped and inspired this project:
- @paradox75831004 - For testing and providing suggestions to make this mod better
- [BlueAmulet](https://thunderstore.io/c/lethal-company/p/BlueAmulet/) - LCBetterClock: fast time updating
- [Cookies](https://thunderstore.io/c/lethal-company/p/Cookies/) - NoHUD
- [Monkeytype](https://thunderstore.io/c/lethal-company/p/Monkeytype/) - HideChat
- [Solar32](https://thunderstore.io/c/lethal-company/p/Solar32/) - PerformanceEnhancer: fps & frame rate changes
___
___

# Installation ⛓️

## R2ModMan or Thunderstore Manager (recommended)

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
___
___

# List of KeyboardShortcut Values 
| Value           | Value Description                                                               |
|---------------|---------------------------------------------------------------------------|
| None          | Not assigned (never returned as the result of a keystroke).               |
| Backspace     | The backspace key.                                                       |
| Delete        | The forward delete key.                                                  |
| Tab           | The tab key.                                                             |
| Clear         | The Clear key.                                                           |
| Return        | Return key.                                                              |
| Pause         | Pause on PC machines.                                                    |
| Escape        | Escape key.                                                              |
| Space         | Space key.                                                               |
| Keypad0       | Numeric keypad 0.                                                        |
| Keypad1       | Numeric keypad 1.                                                        |
| Keypad2       | Numeric keypad 2.                                                        |
| Keypad3       | Numeric keypad 3.                                                        |
| Keypad4       | Numeric keypad 4.                                                        |
| Keypad5       | Numeric keypad 5.                                                        |
| Keypad6       | Numeric keypad 6.                                                        |
| Keypad7       | Numeric keypad 7.                                                        |
| Keypad8       | Numeric keypad 8.                                                        |
| Keypad9       | Numeric keypad 9.                                                        |
| KeypadPeriod  | Numeric keypad '.'.                                                      |
| KeypadDivide  | Numeric keypad '/'.                                                      |
| KeypadMultiply| Numeric keypad '*'.                                                      |
| KeypadMinus   | Numeric keypad '-'.                                                      |
| KeypadPlus    | Numeric keypad '+'.                                                      |
| KeypadEnter   | Numeric keypad Enter.                                                    |
| KeypadEquals  | Numeric keypad '='.                                                      |
| UpArrow       | Up arrow key.                                                            |
| DownArrow     | Down arrow key.                                                          |
| RightArrow    | Right arrow key.                                                         |
| LeftArrow     | Left arrow key.                                                          |
| Insert        | Insert key key.                                                          |
| Home          | Home key.                                                                |
| End           | End key.                                                                 |
| PageUp        | Page up.                                                                 |
| PageDown      | Page down.                                                               |
| F1            | F1 function key.                                                         |
| F2            | F2 function key.                                                         |
| F3            | F3 function key.                                                         |
| F4            | F4 function key.                                                         |
| F5            | F5 function key.                                                         |
| F6            | F6 function key.                                                         |
| F7            | F7 function key.                                                         |
| F8            | F8 function key.                                                         |
| F9            | F9 function key.                                                         |
| F10           | F10 function key.                                                        |
| F11           | F11 function key.                                                        |
| F12           | F12 function key.                                                        |
| F13           | F13 function key.                                                        |
| F14           | F14 function key.                                                        |
| F15           | F15 function key.                                                        |
| Alpha0        | The '0' key on the top of the alphanumeric keyboard.                    |
| Alpha1        | The '1' key on the top of the alphanumeric keyboard.                    |
| Alpha2        | The '2' key on the top of the alphanumeric keyboard.                    |
| Alpha3        | The '3' key on the top of the alphanumeric keyboard.                    |
| Alpha4        | The '4' key on the top of the alphanumeric keyboard.                    |
| Alpha5        | The '5' key on the top of the alphanumeric keyboard.                    |
| Alpha6        | The '6' key on the top of the alphanumeric keyboard.                    |
| Alpha7        | The '7' key on the top of the alphanumeric keyboard.                    |
| Alpha8        | The '8' key on the top of the alphanumeric keyboard.                    |
| Alpha9        | The '9' key on the top of the alphanumeric keyboard.                    |
| Exclaim       | Exclamation mark key '!'. Deprecated if "Use Physical Keys" is enabled in Input Manager settings, use KeyCode.Alpha1 instead. |
| DoubleQuote   | Double quote key '"'. Deprecated if "Use Physical Keys" is enabled in Input Manager settings, use KeyCode.Quote instead. |
| Hash          | Hash key '#'. Deprecated if "Use Physical Keys" is enabled in Input Manager settings, use KeyCode.Alpha3 instead. |
| Dollar        | Dollar sign key '$'. Deprecated if "Use Physical Keys" is enabled in Input Manager settings, use KeyCode.Alpha4 instead. |
| Percent       | Percent '%' key. Deprecated if "Use Physical Keys" is enabled in Input Manager settings, use KeyCode.Alpha5 instead. |
| Ampersand     | Ampersand key '&'. Deprecated if "Use Physical Keys" is enabled in Input Manager settings, use KeyCode.Alpha7 instead. |
| Quote         | Quote key '. |
| LeftParen     | Left Parenthesis key '('. Deprecated if "Use Physical Keys" is enabled in Input Manager settings, use KeyCode.Alpha9 instead. |
| RightParen    | Right Parenthesis key ')'. Deprecated if "Use Physical Keys" is enabled in Input Manager settings, use KeyCode.Alpha0 instead. |
| Asterisk      | Asterisk key '*'. Deprecated if "Use Physical Keys" is enabled in Input Manager settings, use KeyCode.Alpha8 instead. |
| Plus          | Plus key '+'. Deprecated if "Use Physical Keys" is enabled in Input Manager settings, use KeyCode.Equals instead. |
| Comma         | Comma ',' key.                                                           |
| Minus         | Minus '-' key.                                                          |
| Period        | Period '.' key.                                                         |
| Slash         | Slash '/' key.                                                          |
| Colon         | Colon ':' key.Deprecated if "Use Physical Keys" is enabled in Input Manager settings, use KeyCode.Semicolon instead. |
| Semicolon     | Semicolon ';' key.                                                      |
| Less          | Less than '<' key. Deprecated if "Use Physical Keys" is enabled in Input Manager settings, use KeyCode.Comma instead. |
| Equals        | Equals '=' key.                                                         |
| Greater       | Greater than '>' key. Deprecated if "Use Physical Keys" is enabled in Input Manager settings, use KeyCode.Period instead. |
| Question      | Question mark '?' key. Deprecated if "Use Physical Keys" is enabled in Input Manager settings, use KeyCode.Slash instead. |
| At            | At key '@'. Deprecated if "Use Physical Keys" is enabled in Input Manager settings, use KeyCode.Alpha2 instead. |
| LeftBracket   | Left square bracket key '['.                                            |
| Backslash     | Backslash key '\'.                                                      |
| RightBracket  | Right square bracket key ']'.                                           |
| Caret         | Caret key '^'. Deprecated if "Use Physical Keys" is enabled in Input Manager settings, use KeyCode.Alpha6 instead. |
| Underscore    | Underscore '_' key. Deprecated if "Use Physical Keys" is enabled in Input Manager settings, use KeyCode.Minus instead. |
| BackQuote     | Back quote key '`'.                                                     |                                                             |
| A                 | 'a' key.                                                                                                                                      |
| B                 | 'b' key.                                                                                                                                      |
| C                 | 'c' key.                                                                                                                                      |
| D                 | 'd' key.                                                                                                                                      |
| E                 | 'e' key.                                                                                                                                      |
| F                 | 'f' key.                                                                                                                                      |
| G                 | 'g' key.                                                                                                                                      |
| H                 | 'h' key.                                                                                                                                      |
| I                 | 'i' key.                                                                                                                                      |
| J                 | 'j' key.                                                                                                                                      |
| K                 | 'k' key.                                                                                                                                      |
| L                 | 'l' key.                                                                                                                                      |
| M                 | 'm' key.                                                                                                                                      |
| N                 | 'n' key.                                                                                                                                      |
| O                 | 'o' key.                                                                                                                                      |
| P                 | 'p' key.                                                                                                                                      |
| Q                 | 'q' key.                                                                                                                                      |
| R                 | 'r' key.                                                                                                                                      |
| S                 | 's' key.                                                                                                                                      |
| T                 | 't' key.                                                                                                                                      |
| U                 | 'u' key.                                                                                                                                      |
| V                 | 'v' key.                                                                                                                                      |
| W                 | 'w' key.                                                                                                                                      |
| X                 | 'x' key.                                                                                                                                      |
| Y                 | 'y' key.                                                                                                                                      |
| Z                 | 'z' key.                                                                                                                                      |
| LeftCurlyBracket   | Left curly bracket key '{'. Deprecated if "Use Physical Keys" is enabled in Input Manager settings, use KeyCode.LeftBracket instead.    |
| Pipe              | Pipe '|' key. Deprecated if "Use Physical Keys" is enabled in Input Manager settings, use KeyCode.Backslash instead.                       |
| RightCurlyBracket  | Right curly bracket key '}'. Deprecated if "Use Physical Keys" is enabled in Input Manager settings, use KeyCode.RightBracket instead.  |
| Tilde              | Tilde '~' key. Deprecated if "Use Physical Keys" is enabled in Input Manager settings, use KeyCode.BackQuote instead.                      |
| Numlock           | Numlock key.                                                                                                                                  |
| CapsLock          | Capslock key.                                                                                                                                 |
| ScrollLock        | Scroll lock key.                                                                                                                              |
| RightShift        | Right shift key.                                                                                                                              |
| LeftShift         | Left shift key.                                                                                                                               |
| RightControl      | Right Control key.                                                                                                                            |
| LeftControl       | Left Control key.                                                                                                                             |
| RightAlt          | Right Alt key.                                                                                                                                |
| LeftAlt           | Left Alt key.                                                                                                                                 |
| LeftMeta          | Maps to left Windows key or left Command key if physical keys are enabled in Input Manager settings, otherwise maps to left Command key only. |
| LeftCommand       | Left Command key.                                                                                                                             |
| LeftApple         | Left Command key.                                                                                                                             |
| LeftWindows       | Left Windows key. Deprecated if "Use Physical Keys" is enabled in Input Manager settings, use KeyCode.LeftMeta instead.                        |
| RightMeta         | Maps to right Windows key or right Command key if physical keys are enabled in Input Manager settings, otherwise maps to right Command key only. |
| RightCommand      | Right Command key.                                                                                                                            |
| RightApple        | Right Command key.                                                                                                                            |
| RightWindows      | Right Windows key. Deprecated if "Use Physical Keys" is enabled in Input Manager settings, use KeyCode.RightMeta instead.                       |
| AltGr             | Alt Gr key. Deprecated if "Use Physical Keys" is enabled in Input Manager settings, use KeyCode.RightAlt instead.                               |
| Help              | Help key. Deprecated if "Use Physical Keys" is enabled in Input Manager settings, doesn't map to any physical key.                              |
| Print             | Print key.                                                                                                                                    |
| SysReq            | Sys Req key. Deprecated if "Use Physical Keys" is enabled in Input Manager settings, doesn't map to any physical key.                          |
| Break             | Break key. Deprecated if "Use Physical Keys" is enabled in Input Manager settings, doesn't map to any physical key.                             |
| Menu              | Menu key.                                                                                                                                     |
| Mouse0            | The Left (or primary) mouse button.                                                                                                           |
| Mouse1            | Right mouse button (or secondary mouse button).                                                                                               |
| Mouse2            | Middle mouse button (or third button).                                                                                                        |
| Mouse3            | Additional (fourth) mouse button.                                                                                                             |
| Mouse4            | Additional (fifth) mouse button.                                                                                                              |
| Mouse5            | Additional (or sixth) mouse button.                                                                                                           |
| Mouse6            | Additional (or seventh) mouse button.                                                                                                         |