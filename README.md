# RideX Companion — release assets

This repository holds only signed APK assets for the RideX Companion Android updater.
The app source lives in [Supernova70/Ridex](https://github.com/Supernova70/Ridex).

Release rules enforced by the in-app updater:

- Tag is exactly `vX.Y.Z` (stable, no draft, no prerelease).
- Exactly one asset, named `RideX-Companion-vX.Y.Z.apk`.
- The APK must keep the same signing certificate as the installed app.
- `versionCode` must increase with every release.
