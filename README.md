# GateSignal

GateSignal is a lightweight, local-first NPI project control tool for macOS. It helps teams organize product planning, milestones, gates, risks, and project progress without requiring a server.

## Download

Download the latest notarized Apple Silicon DMG from [GitHub Releases](https://github.com/papalon0505/gatesignal/releases/latest).

## Install

1. Download `GateSignal_0.1.3_aarch64.dmg`.
2. Open the DMG.
3. Drag GateSignal into the Applications folder.
4. Launch GateSignal from Applications.

## Privacy

- Project data remains on the Mac in a local SQLite database.
- GateSignal does not require Electron, a local HTTP server, or a cloud account.
- The distributed app is signed with a Developer ID certificate and notarized by Apple.

## System Requirements

- macOS on Apple Silicon
- Version: 0.1.3

## What's New in 0.1.3

- All destructive actions now require confirmation.
- Delete audit records retain a snapshot of the removed data.
- Database backups are verified before a success audit is recorded.
- Data-protection tests now cover authorization, CSRF, deletion, and backup failures.

## Verify

SHA-256:

```text
bf6a18bc32bdd1ee444aea18ca482c4863023ece49599bbd00f71956bc2eb583  GateSignal_0.1.3_aarch64.dmg
```

Copyright (c) 2026 GateSignal.
