# Companion Button Organizer - Releases

Mac installers for Companion Button Organizer. Source code is private; this repo only hosts releases so the app can update itself.

## Install

1. Open the latest release and download the `.dmg` for your Mac: `arm64` for Apple Silicon (M1 and newer), `x64` for Intel.
2. Open the DMG and drag the app into Applications.
3. The app is not notarized by Apple. The first time, right-click the app and choose Open, or go to System Settings > Privacy & Security and click Open Anyway.

## Updates

The app checks this page on launch and every 2 hours. When a new version is posted, a Mac notification appears along with an Update button in the top bar (or use the app menu > Check for Updates). The app must be running from /Applications to update itself.


## Publishing (maintainer)

Bump `version` in `desktop/app/package.json` in the source repo and push. Within the hour, the Build and publish Mac app workflow here builds and posts the release. To publish right away, open Actions > Build and publish Mac app > Run workflow.
