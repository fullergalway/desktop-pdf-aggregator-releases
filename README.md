# Desktop PDF Aggregator — evaluation builds

Unsigned test installers. **Source is not in this repository.**

**Download the latest build:** [Releases](https://github.com/fullergalway/desktop-pdf-aggregator-releases/releases/latest)

| File | For |
|---|---|
| `Desktop-PDF-Aggregator-windows-x64.exe` | Windows 10/11, 64-bit |
| `Desktop-PDF-Aggregator-macos-arm64.dmg` | macOS 11+, Apple Silicon (M1 and later) |

Intel Macs are not in this drop.

## First open (these builds are not signed yet)

**Windows.** SmartScreen may say “Windows protected your PC”. Choose **More info** → **Run anyway**.

**Mac.** Drag the app to Applications. These builds are not notarized. If macOS says the app is **damaged**, it is Gatekeeper, not a corrupt file:

```bash
xattr -cr "/Applications/Desktop PDF Aggregator.app"
```

Then open it. Or System Settings → Privacy & Security → Open Anyway. If it only says unidentified developer: **right-click** → **Open** → **Open**.

## What it is

A local app for building chronological legal PDF packs (cover, linked contents, page numbers) from a folder of case files. Documents stay on the machine.

This is an evaluation build. Exports may carry a small footer mark until a licence is activated.

## Privacy

No account. No cloud conversion. Case files are not uploaded.
