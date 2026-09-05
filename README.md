<p align="center">
  <img src="Assets/PadPointer.png" alt="PadPointer — Xbox controller mouse and keyboard remapper for Windows" width="128" height="128" />
</p>

# PadPointer

**Xbox controller mouse and keyboard for Windows.** PadPointer is a Windows 10/11 gamepad remapper that turns an Xbox, HID, or legacy joystick into a mouse, keyboard, media remote, text editor, and desktop navigator — without taking exclusive ownership of the physical controller, so games still see the pad.

[![Windows](https://img.shields.io/badge/Windows-10%20%2F%2011-0078D4?logo=windows&logoColor=white)](https://github.com/Syenar/PadPointer)
[![Download](https://img.shields.io/github/v/release/Syenar/PadPointer?label=download)](https://github.com/Syenar/PadPointer/releases/latest)
[![Version](https://img.shields.io/badge/version-2.4.0-informational)](https://github.com/Syenar/PadPointer/releases/latest)

**This repository is the public download page.** PadPointer is released as a compiled Windows app only. Source code is not published.

### [Download PadPointer.exe](https://github.com/Syenar/PadPointer/releases/latest)

Use an Xbox controller as a mouse on Windows, map gamepad buttons to keyboard keys, run JoyToKey-style macros and turbo, switch desktop vs gaming mode, and jump between on-screen controls with Smart D-pad.

**Search terms:** Xbox controller to mouse, gamepad mouse Windows, controller remapper, JoyToKey alternative, XInput mapper, HID joystick, DualSense / PlayStation-style labels, media remote, accessibility mouse, couch desktop control.

## Install

1. Open the [latest Release](https://github.com/Syenar/PadPointer/releases/latest).
2. Download `PadPointer.exe`.
3. Run it on Windows 10 or 11 (64-bit). No installer is required.

Windows SmartScreen may warn on first launch because the EXE is not code-signed. Choose **More info** → **Run anyway** if you downloaded it from this GitHub account.

## Why PadPointer

- **Not exclusive.** Games keep the real Xbox / XInput device. PadPointer injects mouse and keyboard; it does not hide the pad.
- **Desktop + gaming.** Swap modes with a hold or two-button combo (default View + Menu). Gaming mode suspends injection so the controller is just a controller.
- **Three mapping layers.** Base desktop map, plus two modifier layers (default LT media, RT text editing) with tap-vs-hold.
- **JoyToKey-class depth.** Turbo, sequences, press-count, analog bands, profiles, auto profile switch, launch program/URL, and Raw Input/HID up to 128 buttons.
- **Smart D-pad.** Spatial UI Automation jumps to the next visible control in that direction.

## Features

- Either analog stick can control the Windows pointer; the other stick can scroll.
- Pointer sensitivity, deadzone, acceleration, response curves, and scroll sensitivity.
- Two controller inputs per mapping action, plus Turbo (0.1–60 Hz).
- Full XInput coverage: A/B/X/Y, LB/RB, LT/RT, View/Menu, L3/R3, D-pad.
- Mouse: left/right/middle click, drag, Back/Forward, vertical and horizontal wheel.
- Keyboard capture, Copy/Cut/Paste, Refresh, on-screen controller keyboard, macros, media keys, clock overlay.
- Profiles (Default Desktop, FPS, MOBA/ARPG, Media Center, Productivity, Presentation/Browser) and auto-switch by app.
- Four themes: Porcelain, Midnight, Sage, Clay.
- Runs in the notification tray when the window is closed.

### Default LT media layer

| Input | Action |
|---|---|
| A | Play / Pause |
| B | Stop |
| X | Previous / Skip Back |
| Y | Next / Skip |
| LB | Rewind |
| RB | Fast-Forward |
| RT | Mute |
| D-pad Up / Down | Volume Up / Down |
| D-pad Left / Right | Previous / Next |

### Default RT text-editing layer

| Input | Action |
|---|---|
| A | Enter |
| B | Backspace |
| X | Copy |
| Y | Paste |
| LB | Cut |
| RB | Delete |
| LT | Shift |
| D-pad | Arrow keys |

## Controller support

Xbox-class XInput pads, Windows legacy joysticks, and Raw Input/HID devices (extra axes, POV hats, Xbox Series Share/Capture, vendor paddles, buttons through 128). Multiple controllers can run independent profiles, or you can combine connected devices into one logical pad.

## License

PadPointer is distributed as an official compiled executable. Source code is not included. See [LICENSE](LICENSE).
