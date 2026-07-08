# Peeku Releases

Peeku is a private, on-device macOS app that can automatically lock your screen when you walk away, using built-in camera face detection and optional Apple Watch proximity. It also coaches healthier desk habits with walk rhythm and eye-rest break reminders. No account required, no cloud face data, no video leaves your Mac.

Learn more: https://peeku.app

## Download Peeku

- Mac App Store coaching build: https://apps.apple.com/app/peeku-presence-coach/id6773651327?mt=12
- Review after trying the App Store build: https://peeku.app/review
- Full auto-lock Mac app: https://peeku.app/get
- Direct 1.7 DMG: https://peeku.app/downloads/Peeku-1.7.dmg

The Mac App Store build is a free coaching version with walk reminders, eye-rest nudges, Desk Health, and local presence signals. The full auto-lock build is distributed outside the Mac App Store because Apple's sandbox blocks automatic screen-lock commands.

## About This Repository

This repository hosts the notarised DMG downloads for Peeku's direct distribution channel, along with SHA-256 checksums for verification. This enables checksum-based trust for users downloading directly from peeku.app, version history visibility via GitHub Releases, durable per-release download statistics via the GitHub API, and CDN availability as a backup.

The source code repository is private. Peeku is the work of Amit Patnaik, an independent developer.

## Verification

To verify the integrity of the current DMG, compare its SHA-256 hash against the published checksum:

```bash
shasum -a 256 Peeku-1.7.dmg
```

Current 1.7 SHA-256:

```text
fab7e88214255885a0ae7ca62017d31219b843044e39dd3bb75a9b60495403c6
```

Release notes and historical downloads are available on the [Releases](https://github.com/iamitp/peeku-releases/releases) page.

---

Built with Swift on macOS. Notarised via Apple Developer ID.
