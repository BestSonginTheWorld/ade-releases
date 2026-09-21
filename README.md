# ADE releases

ADE for Apple Silicon Macs. This repository contains public app downloads and release metadata; the application source repository is private.

## Install

Download the ZIP from [the latest release](https://github.com/BestSonginTheWorld/ade-releases/releases/latest), unzip it, and move `ADE.app` to Applications. Codex and Claude Code connections must be set up separately on each Mac.

These builds are not Developer ID signed or notarized. If macOS blocks a trusted download, follow [Apple's instructions for opening an app from an unknown developer](https://support.apple.com/guide/mac-help/open-a-mac-app-from-an-unknown-developer-mh40616/mac).

## Update

ADE checks for newer releases and can download the ZIP in advance. Finish your work, fully quit ADE, then replace the application in Finder. The app does not automatically terminate sessions, restart, or replace itself.

Each Mac keeps its own conversations, projects, settings, and provider login. Downloads do not synchronize this data between Macs.

## Release files

- `ADE-<version>-mac-arm64.zip`: application
- `release.json`: version, source revision, macOS requirement, download size and SHA-512 digest

Third-party notices are included inside the app package. There are currently no Intel, Windows, or Linux builds.
