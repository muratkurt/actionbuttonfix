# ActionButtonFix

Single click and double click for the Action Button. The long press stays Apple's.

## Install

Add the repo in Sileo:

```
https://muratkurt.github.io/
```

Then install **ActionButtonFix**. It needs **AltList** (opa334's repo) and PreferenceLoader.

Packages are also attached to each [release](../../releases).

## Requirements

- An iPhone with an Action Button — 15 Pro / Pro Max, and the 16 line
- iOS 17 or later
- RootHide or a rootless jailbreak
- **AltList** (opa334's repo) and PreferenceLoader

Tested on iPhone 15 Pro, iOS 17.0.3, RootHide. The rootless package is built and shipped the same way, not verified on the developer's device. iOS 18 and the iPhone 16 line are untested.

## Gestures

- **Single click** — an action you pick
- **Double click** — a different action you pick
- **Long press** — unchanged, whatever iOS Settings has

The short press is never handed to Apple, so the *Silent / hold* feedback in the Dynamic Island never appears. Only your action runs.

## Actions

- **Camera** — side and mode, set per click; optional auto-record, stopped by the same click
- **Screen Recording** — same as Control Center's, interchangeable with it
- **Control Center** — one module per click: Dark Mode, Rotation Lock, Silent Mode, Low Power Mode, QR Code Reader, Magnifier, Voice Memos, Quick Note, Stopwatch, Timer, Alarm, Calculator, Wallet
- **Flashlight** — stays in sync with Control Center
- **Screenshot** — the stock flow; does nothing while the screen is off
- **App** — any installed app; does not open from the Lock Screen
- **Stock Action** — the long-press action from iOS Settings
- **None** — turns a click off; with double click set to None, the single click fires instantly

Each click is configured on its own in **Settings › ActionButtonFix**, in 12 languages.

Full description and changelog are on the [package page](https://muratkurt.github.io/depictions/com.muratkurt.actionbuttonfix.html).

## First install

The tweak is off and both clicks are **None**. Turn it on in Settings › ActionButtonFix and pick your actions.

Updating to 2.6.0 resets existing settings once; later updates keep them.

## Reporting a bug

Open an [issue](../../issues/new/choose). The form asks for your device, iOS version, jailbreak and tweak version — without those a report usually can't be acted on.

## Credits

Built with [Claude Code](https://claude.com/claude-code).

## Licence

Closed source. All rights reserved. The packages are free to install and use; redistribution and reverse engineering are not permitted.
