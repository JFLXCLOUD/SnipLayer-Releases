# SnipLayer

SnipLayer is a private, local Windows screen-capture app with built-in background removal. Select a region, copy it immediately, open the cutout editor, or save it as transparent PNG/SVG.

## Download

Open [SnipLayer Releases](https://github.com/JFLXCLOUD/SnipLayer-Releases/releases) and download **SnipLayer-Setup.exe** from the newest release. A portable executable and SHA-256 checksum file are included as alternatives.

The current `0.3.0` release candidate is an unsigned pre-release. Windows may display an **Unknown publisher** or SmartScreen warning until production code signing is enabled. Verify the SHA-256 value published with the release before running a download.

## Highlights

- Multi-monitor rectangular capture
- Configurable global shortcut, default `Ctrl+Shift+X`
- Direct clipboard copy with PNG transparency
- Local automatic and selective background removal
- Keep/Erase brushes, crop, auto-trim, invert, reset, and undo
- Transparent PNG and SVG export
- Configurable shortcut, Enter-key action, startup, and notifications
- Local diagnostics with no captured pixels or clipboard contents
- Per-user installer with no administrator access required

All image processing happens on the PC. SnipLayer does not require an account or upload screenshots.

## Requirements and installation

- Windows 10 or Windows 11, x64
- Approximately 300 MB of available disk space during installation

Run `SnipLayer-Setup.exe` and follow the installer. SnipLayer installs for the current Windows account under `%LOCALAPPDATA%\Programs\SnipLayer`, so administrator approval is not required.

For managed deployment:

```text
SnipLayer-Setup.exe /silent [/desktop] [/launch]
"Uninstall SnipLayer.exe" /uninstall /silent
```

## Help and policies

- [Report a problem](https://github.com/JFLXCLOUD/SnipLayer-Releases/issues/new/choose)
- [Support guide](SUPPORT.md)
- [Privacy policy](PRIVACY.md)
- [Security reporting](SECURITY.md)
- [Preview license](PREVIEW-LICENSE.md)
- [Third-party notices](THIRD-PARTY-NOTICES.md)

This repository contains public downloads, release notes, and support materials. The SnipLayer application source repository is private.
