# AXIOM Architecture

AXIOM is organized as a collection of coordinated KDE components rather than one monolithic theme file.

```text
AXIOM
├── Plasma shell presentation
├── Aurorae/KWin window decoration
├── KDE color scheme
├── Konsole profile + color scheme
├── Wallpapers
└── Documentation / installation tooling
```

Each component can be installed independently while sharing the same design language.

## Aurorae

The Aurorae package contains the window decoration metadata, layout configuration, frame SVG, and control assets.

The plugin directory is:

```text
~/.local/share/aurorae/themes/N3USYS-Axiom/
```

The rc file is named `N3USYS-Axiomrc` to match the Aurorae plugin name.

## Design Boundary

AXIOM controls presentation. It does not alter KDE system behavior or replace core desktop services.
