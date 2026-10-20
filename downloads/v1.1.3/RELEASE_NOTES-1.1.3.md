# Satellite 1.1.3 release notes

Release date: 2026-10-20

## What changed

- **Chats side by side.** In the chat list, "Open beside" shows another chat
  in a panel next to the main chat, in the same window. Up to 3 chats can be
  open at once, each with its own work, queue and settings. "+ New chat
  beside" starts a fresh one. Separate chat windows are gone.
- **Steadier chats.** Each chat keeps its own state. A message you send
  while the agent works waits in a queue strip above the composer, and you
  can remove it or send it now. One button shows Stop or Send, never both.
  A chat that waits for your permission says "Needs approval".
- **Chat settings in the ⋯ menu.** Model, effort and permission mode apply
  from the next message. A sound plays when a reply finishes while Satellite
  is in the background.
- **Journey planning.** Phases can start with a UI ticket that you approve
  before other work begins, and end with a review. Routine checks fold into
  one "close milestone" step. Fixes for applying plan changes.

## Data and rollback safety

Data schema version: `2`.

- **Rollback is safe:** this release does not advance Satellite's data schema.
  You can reinstall 1.1.2, 1.1.1 or 1.1.0 without restoring a backup.

## Update instructions

Download the DMG from https://yourimvp.github.io/satellite-releases/downloads/,
replace Satellite.app in Applications, and restart Satellite.
