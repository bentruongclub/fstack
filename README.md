# fstack

One job. Route it. Prove it.

Cursor plugin: invoke `/fstack`. Classifies the ask, opens one playbook, runs it, proves on a real artifact.

MIT. See LICENSE.

## Usage

In Agent chat: `/fstack` plus the ask.

Routes (see `skills/fstack/SKILL.md`):

- write / open the next skill or plugin file
- ship / commit / land / push
- review / look over / before commit
- bug / broken / fix
- how / why / are we sure (read-only)
- new idea while a file is already open (park)

No MCP. No config vars.

## Install (local)

1. Copy this folder into `~/.cursor/plugins/local/fstack` as a real directory (no symlink out of that folder). Keep `.cursor-plugin/plugin.json`.
2. Restart Cursor or run Developer: Reload Window.
3. Open Customize in the sidebar. Confirm the fstack skill loaded.
4. In Agent chat, run `/fstack`.

Teams/Enterprise: admins must allow Local Plugin Imports (Dashboard → Settings → Security & Identity → Marketplace and Plugins). Off by default on Enterprise.

## Marketplace

Not listed yet. Publish needs a **public** GitHub repo. This one is still private: https://github.com/bentruongclub/fstack

When public: submit at https://cursor.com/marketplace/publish (do not click Submit until Fuji approves). After listing, install via Marketplace `/add-plugin` instead of the local copy path above.

Skills live in `skills/`.
