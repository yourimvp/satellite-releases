# Satellite 1.1.0 release notes

Release date: 2026-10-18

## What changed

- **Journeys are now planned in chat.** A planning chat writes your project's
  Vision and Design documents with you, then drafts the plan: milestones,
  phases, groups of tickets and their dependencies. You see a preview and
  confirm it before anything changes.
- **Each milestone has a goal and "done when" checks.** A milestone closes
  only through a review: Satellite gathers the evidence from shipped work,
  you confirm the checks only you can observe, and a milestone with open
  tickets cannot close.
- **Plan one phase at a time.** Later phases can stay sketched. "Plan this
  phase" on the first sketched phase opens its planning chat.
- **Open questions go to Needs you.** Answer them there; each answer is kept
  in the plan, so later planning chats do not ask again.
- **A quieter Journey page.** Approved Foundations shrink to one line, the
  checks fold away until review, and tier labels only mark exceptions.
- **Chats stay in your folders.** A chat now starts in your vault instead of
  inside the app, so it no longer searches your whole Mac (or asks macOS for
  access to Music, Photos or network drives). The chat header shows what a
  chat is about: a project, or "Vault". A new chat on a project's Journey is
  about that project; press **⌘J** anywhere else to ask about the page you
  are on.
- Fixes: Needs-you questions show in full and stay open while you type;
  clearer provider sign-in messages.
- Settings → **Check for updates** works again.

## Data and rollback safety

Data schema version: `2`.

- **Rollback is not safe without restoring a backup:** this release advances
  Satellite's data schema. On first start, Satellite upgrades your Journeys
  automatically and first copies the old data to
  `~/Library/Application Support/Satellite Beta/data/archives/`. Do not
  reinstall 1.0.0 afterwards: it refuses to open the upgraded data.

## Update instructions

1. Quit Satellite Beta.
2. Download `Satellite-1.1.0.dmg` from
   `https://yourimvp.github.io/satellite-releases/downloads/v1.1.0/`.
3. Open it and drag Satellite Beta to Applications, replacing the old copy.
4. Open Satellite Beta. If macOS blocks it, right-click the app and choose
   **Open**. Your data and vault stay where they are.
