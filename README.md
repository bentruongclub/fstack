# fstack

Install as a local Cursor plugin from this folder. Invoke `/fstack`.

Classifies the ask. Opens one playbook. Runs it. Proves it on a real artifact.

MIT. See LICENSE.

## Install

1. Copy this folder into `~/.cursor/plugins/local/fstack` as a real directory (no symlink out of that folder). Keep `.cursor-plugin/plugin.json`.
2. Restart Cursor or run Developer: Reload Window.
3. Open Customize in the sidebar. Confirm the fstack skill loaded.
4. In Agent chat, run `/fstack`.

Teams/Enterprise: admins must allow Local Plugin Imports (Dashboard → Settings → Security & Identity → Marketplace and Plugins). Off by default on Enterprise. Marketplace `/add-plugin` does not apply yet.

Skills live in `skills/`.
