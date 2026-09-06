# Changelog

All notable changes to this project are documented here, following
[Keep a Changelog](https://keepachangelog.com/) and semantic versioning.

## [0.2.0] - 2026-09-06

### Fixed
- Phones without 32-bit float render targets now run on probed 16-bit float targets instead of showing the fallback.
- Mobile quality scaling: smaller sim/dye textures, fewer Jacobi iterations, DPR capped at 1.
- Toolbar scrolls on narrow screens; viewport-fit cover; safe pointer capture; context-loss fallback.

## [0.1.0] - 2026-09-05

### Added
- Initial release: real-time GPU fluid simulation (stable fluids) in one HTML file.
