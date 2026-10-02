<p align="center"><img src="https://raw.githubusercontent.com/swayward-wm/.github/main/logo/swayward-256.png" width="160" alt="swayward logo: a neon circuit tree on an isometric island"></p>

# swayward-wm

Home of **[swayward](https://github.com/swayward-wm/swayward)**, an i3/sway-compatible
Wayland compositor built in Rust on Smithay.

> sway, gone its own way.

swayward gives you i3's fully nested container tree (splits inside splits,
tabbed and stacked containers, marks, criteria, the scratchpad) on a modern
Wayland compositor, and speaks sway's IPC protocol on `SWAYSOCK`. Waybar's sway
modules, `swaymsg`, i3ipc-python and other sway tools run unmodified.

## Repositories

| Repository | What it is |
|---|---|
| [swayward](https://github.com/swayward-wm/swayward) | The compositor. A fork of [niri](https://github.com/niri-wm/niri) with niri's scrolling layout replaced by i3's container tree and its IPC replaced by sway's. |
| [sway-ipc-oracle](https://github.com/swayward-wm/sway-ipc-oracle) | The compatibility oracle: i3's own test suite, unchanged, plus IPC replies captured from real sway. swayward is measured against it. |

## Start here

- [Getting started](https://github.com/swayward-wm/swayward/wiki/Getting-Started)
- [Differences from sway](https://github.com/swayward-wm/swayward/wiki/Differences-from-Sway)
- [Testing and conformance](https://github.com/swayward-wm/swayward/wiki/Testing-and-Conformance)

swayward is in beta. Bug reports and sway configs that don't behave go to
[swayward issues](https://github.com/swayward-wm/swayward/issues).
