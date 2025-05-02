# Hoisin Sway Edition

This project provides a clean, atomic, and stable installation of the **Sway** window manager using the Vanilla OS build system.

## Features

- ✅ Minimal and reproducible
- ✅ Pure Wayland with Sway
- ✅ No bloat, no unnecessary packages
- ✅ Ready for daily use with essential utilities

## Included Components

- `sway` — tiling Wayland compositor
- `xwayland` — compatibility for X11 apps
- `mako`, `waybar`, `grim`, `slurp` — status bar, notifications, and screenshot tools
- `foot` — lightweight terminal
- `network-manager`, `dmenu`, `light` — essential desktop utilities

## Getting Started

Add the following modules to your build recipe:

```yaml
includes:
  - modules/20-sway-core.yml
  - modules/30-sway-essentials.yml
```

Make sure to replace any existing Hyprland configurations and modules.

---
Built with ❤️ for simplicity and stability.
