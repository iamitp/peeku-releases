# Peeku Releases

Peeku is a private, on-device macOS app that automatically locks your screen when you walk away, using built-in camera face detection and optional Apple Watch proximity. It coaches healthier desk habits with walk rhythm and eye-rest break reminders. No account required, no cloud face data, no video leaves your Mac.

Learn more: https://peeku.app

## About This Repository

This repository hosts the notarised DMG downloads for Peeku's direct distribution channel, along with SHA-256 checksums for verification. This enables checksum-based trust for users downloading directly from peeku.app/downloads/, version history visibility via GitHub Releases, durable per-release download statistics via the GitHub API, and CDN availability as a backup.

The source code repository is private. Peeku is the work of Amit Patnaik, an independent developer.

## Verification

To verify the integrity of a downloaded DMG, compare its SHA-256 hash against the published checksum:

```bash
shasum -a 256 Peeku-1.3.dmg
```

Compare the output against the checksum published in the [Release Notes](https://github.com/iamitp/peeku-releases/releases).

## Downloads

See the [Releases](https://github.com/iamitp/peeku-releases/releases) page for current and historical versions.

---

Built with Swift on macOS. Notarised via Apple Developer ID.
