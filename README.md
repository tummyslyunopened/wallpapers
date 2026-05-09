# wallpapers

Per-host desktop wallpapers, vendored as a submodule of
[`tummyslyunopened/config`](https://github.com/tummyslyunopened/config).

Naming convention: `wallpaper-<hostname>.<ext>` — one image per machine, picked
up automatically by the host's wallpaper-setting script.

| File                  | Host  |
|-----------------------|-------|
| `wallpaper-pda1.jpg`  | pda1  |
| `wallpaper-srv3.jpg`  | srv3  |
| `wallpaper-ws0.jpg`   | ws0   |
| `wallpaper-ws1.jpg`   | ws1   |

Add a new wallpaper for a host by dropping in `wallpaper-<hostname>.<jpg|png>`
and committing.
