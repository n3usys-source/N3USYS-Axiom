# N3USYS AXIOM

**N3USYS AXIOM** is a dark, cyan-accented KDE Plasma visual system built around the N3USYS computational aesthetic.

## Status

**Version:** 0.2.2  
**Platform:** KDE Plasma 6 / Linux  
**State:** Functional development release

AXIOM currently provides a Plasma desktop theme, KDE color scheme, Konsole profile/color scheme, wallpapers, and an Aurorae KWin window decoration.

## Components

- **Aurorae Window Decoration** — dark structural frame with cyan borders and cyan window titles.
- **Plasma Desktop Theme** — N3USYS visual language for the Plasma shell.
- **Color Scheme** — AXIOM dark/cyan system palette.
- **Konsole Theme/Profile** — terminal presentation aligned with AXIOM.
- **Wallpapers** — N3USYS AXIOM visual backgrounds.

## Design Language

AXIOM is intentionally restrained:

- near-black structural surfaces
- cyan signal/accent color
- thin technical borders
- high contrast typography
- minimal ornamentation
- instrument/HUD-inspired geometry
- visual hierarchy based on signal, state, and structure

The objective is not to imitate a fictional operating system. AXIOM is a practical desktop implementation of the N3USYS visual language.

## Version History

- **0.1.0** — Initial AXIOM concept/design system.
- **0.2.0** — Initial Plasma theme implementation.
- **0.2.1** — Integrated theme package.
- **0.2.2** — Functional Aurorae window decoration and cyan window-title integration.

## Current Aurorae Note

In 0.2.2 the window-control hit regions are functional while their glyphs are intentionally visually minimal. This is accepted as part of the current AXIOM aesthetic; control glyph refinement can be addressed in a later release.

## Repository Structure

```text
N3USYS-Axiom/
├── README.md
├── VERSION
├── CHANGELOG.md
├── LICENSE
├── aurorae/
│   └── N3USYS-Axiom/
├── plasma/
│   └── N3USYS-Axiom/
├── colors/
│   └── N3USYS-Axiom.colors
├── konsole/
│   ├── N3USYS-Axiom.colorscheme
│   └── n3usys_term.profile
├── wallpapers/
├── docs/
├── scripts/
└── packaging/
```

## Installation

The project is intended to be installed into the user's KDE data directories under `~/.local/share/`. An installer script will be provided as the package is consolidated.

After installation, select the AXIOM components through KDE System Settings where appropriate.

## Development Philosophy

AXIOM is developed as a living visual system rather than a single static theme. Components should share the same visual grammar while remaining independently usable.

Future releases may add a unified KDE Global Theme package, iconography, improved Aurorae controls, additional wallpapers, and automated packaging.

## License

GPL-3.0-or-later. See `LICENSE`.

---

**N3USYS**  
Computational coherence through observation, structure, and deliberate design.
