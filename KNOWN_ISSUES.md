# Known issues
## Launcher crashes during game update/installation
- Select `wine-ge-proton-8.26` as your runner in Lutris and run launcher again
- After game update/installation, revert your runner to previous one

## Exception window
After few minutes exception appears. It is already fixed in the yaml file:
- `wine: overrides: tdh.dll: n`
the tdh.dll is set to native wich is required to prevent the exception window from poping up.

## No background music in launcher
Still not fixed, appears to be GStreamer issue

## Missing textures on NVIDIA GPU
Not enought data