# Dockside Dark

- Author: Jenx
- Version: 0.1.0
- Theme framework: 0.7 (built from the stock `wargames` theme)

## Description

The dark-mode version of Dockside: a desktop-computer look for the WiFi Pineapple Pager in
graphite windows with light text and a bright blue accent.

- **Desktop:** the main screen is a desktop with a night wallpaper, a dark translucent menu bar
  (the Pager's status icons sit in it like menu bar extras), desktop icons and a dock of six
  custom app icons. The selected icon magnifies, gets an indicator dot, and shows its name in a
  tooltip above it.
- **Windows everywhere:** every screen is a dark window with a title bar and red/yellow/green
  window buttons. Selected rows get a blue highlight bar, dialogs use rounded push buttons (the
  focused one is blue), toggles are green switches, and longer lists and pages show a classic
  scroll bar.
- **Payloads:** browsing user, recon and alert payloads looks like a file browser, with a
  Favorites sidebar, a Name/Kind list and a path bar showing where you are
  (`Pager HD > root > payloads > user > games`). Launching a payload drops a sheet from that
  window, where the Terminal icon's cursor blinks.
- **Settings and PineAP:** styled like a system-settings app, with a sidebar of colored category
  icons and grouped rows showing switches, current values and chevrons, previewed live as you
  move through the sidebar. About lists the device info with a scroll bar and a Developer Tools
  row.
- **Pager Portal:** styled like an app store, with Discover tiles, section rows, GET/UPDATE pills
  and payload pages. Its icon shows the Pager itself, drawn like Hak5's Pager character.
- **Recon:** an activity-monitor style graph, results and clients as tables with column headers,
  and access point / client details with an info grid beside an actions card.
- **Everything else:** the power menu is a drop-down menu, the payload log is a Terminal window,
  option and edit dialogs are sheets, alerts have info/warning/error icons, the keyboards are
  redrawn as graphite keycaps, and the lock, boot, update, battery, heat, license and QR screens
  all match the look.

## Installation

1. Copy the `dockside-dark` folder to `/root/themes/` (or `/mmc/root/themes/`) on your Pager
2. Go to **Settings > General > Theme**
3. Select **dockside-dark**

## Known limitations

- Status icons and some small glyphs are recolored stock art, not redrawn.
- Text drawn by the firmware uses the Pager's system font, so on-screen labels are monospaced.
- Not yet tested on real hardware.
