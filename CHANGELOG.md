# Changelog

All notable changes to this project will be documented in this file.

## [Unreleased]

### Added

### Fixed
- compilation with modern clang (thanks to https://github.com/jchv)
  - stop linking against `libstdc++fs`
  - include `<sstream>`

## [0.2.1] 2022-05-08

### Added

- `info` command, showing archive metadata
- `list -v` command, showing size and date/time
- support for uncompressed archives

## [0.1.0] 2022-04-17

Minimal viable implementation that's able to list and extract regular archives.

Contributors:
- https://github.com/OmniBlade
- https://github.com/ligfx
- https://github.com/adrium
