# icons — Cutefish Icon Theme

## Purpose
System default icon theme ("Crule" and "Crule-dark"), based on vinceliuice's WhiteSur icon theme.

## Build
```bash
cmake -B build -DCMAKE_INSTALL_PREFIX=/usr && sudo cmake --install build
```

## Dependencies
None (install-only, no compilation)

## Structure
- `Crule/` — light icon theme directory
- `Crule-dark/` — dark icon theme directory

## Install Targets
- `Crule/` → `${CMAKE_INSTALL_PREFIX}/share/icons/`
- `Crule-dark/` → `${CMAKE_INSTALL_PREFIX}/share/icons/`

## Qt5→Qt6 Migration Notes
- `cmake_minimum_version` bumped to 3.16

## Status
✅ Ported, built, installed, pushed (github.com/ali-soomro)
