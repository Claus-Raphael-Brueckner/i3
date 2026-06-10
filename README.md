![Logo](docs/logo-30.png) i3 with titlebar buttons
====================================================

This is a fork of [i3](https://github.com/i3/i3) that adds opt-in titlebar buttons for closing, toggling floating mode, and toggling sticky.


<img width="1920" height="1080" alt="titlebar_buttons" src="https://github.com/user-attachments/assets/cc3e710d-d038-4833-8377-3716f7a991a4" />

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
