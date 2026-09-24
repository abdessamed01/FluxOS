# FluxOS

<p align="center">
  <img src="config/includes.chroot/usr/share/icons/hicolor/256x256/fluxos.png" alt="FluxOS Logo" width="128"/>
</p>

A lightweight, modern Linux distribution built on **Debian Trixie** and powered by the **labwc** Wayland compositor. Designed specifically for low-resource hardware with a high-contrast magenta/cyan aesthetic.

## Features
- **Base**: Debian Trixie (Testing)
- **Compositor**: `labwc` (Wayland)
- **Panel**: `waybar`
- **Target Specs**: 4GB RAM, lightweight 64-bit systems
- **Identity**: Dark mode with vibrant magenta and cyan accents

## Build from Source
```
sudo lb clean --purge
lb config
sudo lb build
```
