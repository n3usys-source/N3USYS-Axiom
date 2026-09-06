# Installation

## Requirements

- Linux
- KDE Plasma 6
- Aurorae/KWin window-decoration support

## User Installation Layout

AXIOM components are installed beneath:

```text
~/.local/share/
├── aurorae/themes/N3USYS-Axiom/
├── plasma/desktoptheme/N3USYS-Axiom/
├── color-schemes/
├── konsole/
└── wallpapers/
```

## Manual Selection

After installation:

1. Open **System Settings**.
2. Select the AXIOM color scheme.
3. Select the AXIOM Plasma style/theme where available.
4. Select **N3USYS AXIOM** under Window Decorations.
5. Select an AXIOM wallpaper.
6. Configure Konsole to use the AXIOM profile/color scheme.

Run `kbuildsycoca6` after installing new KDE theme components if they do not immediately appear.

## Wayland

AXIOM does not automatically restart KWin. This is intentional so installation does not risk disrupting an active Wayland session.
