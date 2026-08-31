# Cortex Android releases

This repository holds **signed Android release artifacts only**. There is no application source here.

Source of truth: the private `cortex-ai` repository.

## What ships on each release

Each GitHub Release is tagged `android-v<versionName>` and publishes:

- `cortex-prod-release.apk` — signed `prodRelease` APK for sideload
- `prod.json` — static update manifest the app fetches (not the GitHub API)

Latest manifest (stable URL):

`https://github.com/m-eylon/cortex-releases/releases/latest/download/prod.json`

Do not commit APK or AAB files to this repository. Releases attach them as assets.