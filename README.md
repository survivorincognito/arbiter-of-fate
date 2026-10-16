# Skyrim — The Fate Director

**The Arbiter of Fate** · A Survivor Incognito expedition companion.

A standalone, offline-first HTML tool to track a Skyrim expedition and optionally let Fate choose eligible objectives, character progression choices, perks and magic permissions. Includes Quest Journal, faction restrictions, Spellbook, Dragon Shouts, expedition history and JSON backup/restore.

## Run it

- Open `index.html` in a modern browser, or host it with GitHub Pages.
- For GitHub Pages, upload `index.html` to the root of the selected repository and enable Pages under **Settings → Pages** using the default branch and `/ (root)` folder. Your eventual public URL depends on the repository name and account; none is pre-configured here.
- No build, package manager, account, game installation or server is needed.

## How to use

The Dashboard has a short Getting Started guide. In **Settings → How to Use The Fate Director**, seven collapsible chapters explain expedition setup, the **Arbiter** tab, quest discovery and assignments, progression, magic and shouts, backup restoration and common troubleshooting. The controls under **Arbiter** were previously labelled **Director**; their saved rules are unchanged.

## Keep your expedition safe

Progress saves in the browser's local storage for its current origin. Opening a downloaded file, a different downloaded path, a different browser, or the future hosted site might not share the same saved data. **Export JSON** in Settings before switching, then **Import** on the destination page. Imports replace the currently open expedition after confirmation. Compatible earlier version-1 expedition backups remain supported.

## Caveats

- The Director cannot read or modify Skyrim save files or control the game. Follow the decisions manually.
- Quest/spell/shout coverage is curated and does not guarantee every quest trigger, alternate branch, mod or Creation acquisition condition. Manually confirm uncertain objectives in-game.
- This is an **unofficial fan-made tool** associated with Survivor Incognito. It is not endorsed by or affiliated with Bethesda.
- This publication bundle contains only the standalone HTML and documentation. No user's expedition backup or saved gameplay data is included.

## Version

App release **v2.0**. Existing expedition backup data schema **v1** (intentionally retained for compatibility).

See [RELEASE_NOTES.md](RELEASE_NOTES.md) and [RELEASE_QA.md](RELEASE_QA.md).
