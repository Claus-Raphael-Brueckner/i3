![Logo](docs/logo-30.png) i3 with titlebar buttons
====================================================

This is a fork of [i3](https://github.com/i3/i3) that adds opt-in titlebar buttons for closing, toggling floating mode, and toggling sticky.

## Buttons

| Button | Action |
|--------|--------|
| Close  | Kills the window |
| Float  | Toggles floating/tiling mode |
| Sticky | Toggles sticky (floating windows only) |

## Configuration

Add the following line to your i3 config to enable the buttons:

```
titlebar_buttons enable
```

No buttons are shown without this option — default i3 behavior is unchanged.

## Building

Build instructions are the same as upstream i3: see [the upstream README](https://github.com/i3/i3) and [build documentation](https://i3wm.org/docs/hacking-howto.html).
