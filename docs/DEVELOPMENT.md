# Development

## Source of Truth

The GitHub repository is the canonical source for AXIOM releases.

## Versioning

AXIOM follows semantic versioning where practical:

- MAJOR — incompatible architectural or design-system change
- MINOR — new coordinated components or significant functionality
- PATCH — fixes, refinements, and packaging corrections

## Release Checklist

1. Test the components on KDE Plasma 6.
2. Verify Aurorae borders and title rendering.
3. Verify minimize, maximize/restore, and close controls.
4. Verify Plasma theme and color scheme registration.
5. Verify Konsole assets.
6. Verify wallpapers.
7. Update `VERSION` and `CHANGELOG.md`.
8. Tag the release in GitHub.

## Design Rule

Do not add visual effects simply because they are possible. New elements should reinforce structure, signal, state, or function.
