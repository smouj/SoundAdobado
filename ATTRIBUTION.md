# Attribution

Every asset bundled with or committed to SoundCraft is listed here with its author, source and
license. `cargo xtask assets` fails CI when a tracked asset file has no row.

**Rule:** no Avid, Pro Tools, Adobe or other proprietary icons, images, sounds or presets — ever.
Assets must be original, public domain (CC0) or permissively licensed. See `AGENTS.md`.

## Icons

All UI icons (tools, transport, track buttons) are drawn procedurally in
`crates/ui-egui/src/icons.rs` by the SoundCraft contributors (MIT OR Apache-2.0). No UI icon image
files are used. The app icon (`assets/app-icon/`) is the official Adobado Sound product mark supplied by the project owner; its source and licence are listed under Files below.

## Audio

The demo session's audio (drums, bass, pad) and its MIDI parts are synthesised in code in
`crates/engine/src/demo.rs` by the SoundCraft contributors (MIT OR Apache-2.0). No sample files
are bundled.

## Fonts

SoundCraft bundles no font files. It uses the default fonts shipped inside the `egui` crate
(Ubuntu-Light: Ubuntu Font Licence 1.0; Hack: MIT; Noto Emoji: OFL-1.1; emoji-icon-font: OFL-1.1/MIT)
and, at runtime, the operating system's own UI fonts when available (never redistributed).

## Files

| Path | Author | Source | License |
|---|---|---|---|
| `docs/screenshot.png` | @smouj | Original screenshot captured from SoundAdobado; empty session workspace with the Setup menu open, no third-party application UI | MIT OR Apache-2.0 |
| `assets/adobado/icon.png` | @smouj | Official Adobado icon pack supplied by the project owner; SHA256SUMS.txt verified | MIT OR Apache-2.0 (`assets/app-icon/LICENSE.txt`) |
| `assets/adobado/icon.ico` | @smouj | Official Adobado icon pack supplied by the project owner; SHA256SUMS.txt verified | MIT OR Apache-2.0 (`assets/app-icon/LICENSE.txt`) |
| `docs/brand/adobado-logo.png` | @smouj | Byte-for-byte copy of the canonical PNG from the official icon pack | MIT OR Apache-2.0 (`assets/app-icon/LICENSE.txt`) |
| `docs/brand/adobado-logo-white.png` | @smouj | Byte-for-byte copy of the canonical PNG from the official icon pack | MIT OR Apache-2.0 (`assets/app-icon/LICENSE.txt`) |
| `assets/app-icon/icon.svg` | @smouj (project owner) | Official Adobado Sound icon; SVG packaging wrapper embeds the verified 512 px PNG from Adobado_Icon_Pack_Final.zip | MIT OR Apache-2.0 (`assets/app-icon/LICENSE.txt`) |
| `packaging/macos/dmg/` (all files) | @XusBadia | original (macOS DMG window background and layout, from the app icon; see `packaging/macos/dmg/README.md`) | MIT OR Apache-2.0 |
| `assets/app-icon/soundcraft-1024.png` | @smouj (project owner) | Original PNG from Adobado_Icon_Pack_Final.zip (SHA256SUMS.txt verified) | MIT OR Apache-2.0 (`assets/app-icon/LICENSE.txt`) |
| `assets/app-icon/soundcraft-macos-512.png` | @smouj (project owner) | Original 512 px PNG from Adobado_Icon_Pack_Final.zip | MIT OR Apache-2.0 (`assets/app-icon/LICENSE.txt`) |
| `assets/app-icon/soundcraft.icns` | @smouj (project owner) | original owner-supplied Adobado icon, rendered to the required platform sizes | MIT OR Apache-2.0 (`assets/app-icon/LICENSE.txt`) |
| `assets/app-icon/soundcraft.ico` | @smouj (project owner) | original owner-supplied Adobado icon, rendered to the required platform sizes | MIT OR Apache-2.0 (`assets/app-icon/LICENSE.txt`) |
| `assets/app-icon/hicolor/` | @smouj (project owner) | original owner-supplied Adobado icon, rendered to the required platform sizes | MIT OR Apache-2.0 (`assets/app-icon/LICENSE.txt`) |
| `docs/images/` | SoundCraft contributors | screenshots of SoundCraft rendered from the synthesised demo session | MIT OR Apache-2.0 |
