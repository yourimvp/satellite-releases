# Satellite 1.1.2 release notes

Release date: 2026-10-18

## What changed

- **Check for updates now links the download.** When an update is available,
  Settings → About shows "Download Satellite <version>" next to the release
  notes. The DMG downloads in your browser. Before, it only linked the notes.

## Data and rollback safety

Data schema version: `2`.

- **Rollback is safe:** this release does not advance Satellite's data schema.
  You can reinstall 1.1.1 or 1.1.0 without restoring a backup.

## Update instructions

Download the DMG from https://yourimvp.github.io/satellite-releases/downloads/,
replace Satellite.app in Applications, and restart Satellite.
