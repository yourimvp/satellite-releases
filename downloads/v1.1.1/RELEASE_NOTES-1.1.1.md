# Satellite 1.1.1 release notes

Release date: 2026-10-18

## What changed

- **"Start drafting" on a Journey works again.** In 1.1.0 the phase drafter
  stopped on start, and the phase showed "Drafting" forever without doing
  anything. It now drafts. If a draft cannot start, the phase says so and
  the activity log shows the reason.
- **New projects can draft their first phase.** A brand-new project has no
  code and no tests yet. Its first draft is no longer refused for that: the
  first ticket sets up the project's tests instead.
- **See what the draft agent is doing.** While a draft runs, the header shows
  its steps (Prepare → Draft → Save) and how long it has run. Click it to read
  the agent's live work, the same way you can follow a build.
- **The Journey header shows activity and usage.** The latest activity for
  this project, your Claude and Codex usage, and the activity log button now
  sit under the project name.
- **The Journey uses the full window.** When the chat is open against the
  right edge, the page makes room for it. If the chat grows too wide, the page
  returns to full width and the chat floats on top.

## Data and rollback safety

Data schema version: `2`.

- **Rollback is safe:** this release does not advance Satellite's data schema.
  You can reinstall 1.1.0 without restoring a backup.

## Update instructions

Download the matching DMG from `https://yourimvp.github.io/satellite-releases/downloads/`,
replace Satellite.app in Applications, and restart Satellite.
