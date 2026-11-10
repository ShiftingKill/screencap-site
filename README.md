# ScreenCap

Lightweight Windows screen capture with resizable "camera" frames and an on-screen marker.
Nothing freezes the screen: frames are hollow, the marker is a click-through overlay, and PNGs
land straight in a folder.

**Homepage:** https://shiftingkill.github.io/screencap-site/

![ScreenCap overview](img/hero.png)

![ScreenCap toolbar](img/toolbar.png)

## Features

**Cameras**
- Spawn any number of capture frames; drag the thin border to resize, drag the bar to move.
- Bar at the bottom centre of each frame fades out when not hovered and is never in a capture.
- Size drop-down: pixel presets up to 8K, inch and mm paper/photo sizes (at 96 px/in), or custom.
- `+ Cam` on a bar spawns another camera of the same size.
- Edges stick to screen and taskbar edges; a camera cannot be pushed off the desktop.
- `Snap` saves one camera, `Snap all` saves every camera. Borders and bars of all cameras are
  hidden for the capture. The last shot is also copied to the clipboard.

**Marker**
- `Draw` turns on a marker across every monitor: six colours plus a colour wheel that remembers your last seven picks, 1-40 px tip.
- Strokes fade after 1-30 s, or stay until cleared with `Hold`.
- Right-click undoes the last stroke, Esc leaves draw mode.
- Marker strokes are included in captures.

![Colour wheel](img/wheel.png)

**Hotkeys**: Ctrl+Alt+S snap all, Ctrl+Alt+D toggle draw, Ctrl+Alt+X clear marker.

The toolbar and cameras reopen where they were left; if that monitor is gone they return to the
main display. A tray icon offers *Reset toolbar position*.

| Camera | Marker | Size presets |
| --- | --- | --- |
| ![Camera](img/camera.png) | ![Marker](img/marker.png) | ![Presets](img/presets.png) |
