# SuperConsole

**One workspace for all your AI coding agents.**

SuperConsole is a native desktop app that runs Claude Code, Codex, Droid, Antigravity, and plain shells side by side, inside your own project folders. It adds usage insights down to the session, scheduled agents, autonomous bots with approval gates, multi-device sync, and a mobile companion, in a lightweight native app.

[**Download the latest release**](https://github.com/superConsoleAI/superconsole/releases/latest)

---

## Download

| Platform | Download |
| --- | --- |
| macOS (Apple Silicon) | [Download for Mac (M1/M2/M3/M4)](https://github.com/superConsoleAI/superconsole/releases/latest/download/SuperConsole_macOS_arm64.dmg) |
| macOS (Intel) | [Download for Mac (Intel)](https://github.com/superConsoleAI/superconsole/releases/latest/download/SuperConsole_macOS_x64.dmg) |
| Windows (64-bit) | [Download for Windows](https://github.com/superConsoleAI/superconsole/releases/latest/download/SuperConsole_Windows_x64.exe) |
| Linux (64-bit) | [Download for Linux](https://github.com/superConsoleAI/superconsole/releases/latest/download/SuperConsole_Linux_x64.AppImage) |

These links always point to the newest release. Older versions are on the [Releases page](https://github.com/superConsoleAI/superconsole/releases).

## Install

**macOS**
1. Download the `.dmg` that matches your Mac.
2. Open it and drag **SuperConsole** into **Applications**.
3. Launch SuperConsole. If macOS shows a warning on first launch, right-click the app, choose **Open**, then confirm.

**Windows**
1. Download and run the `.exe` installer.
2. If Windows SmartScreen appears, click **More info → Run anyway**.
3. Launch SuperConsole from the Start menu.

**Linux**
1. Download the `.AppImage`.
2. Make it executable: `chmod +x SuperConsole_Linux_x64.AppImage`
3. Run it: `./SuperConsole_Linux_x64.AppImage`

Then click **Add Workspace** and pick any project folder.

To run an agent you need its CLI installed (for example Claude Code or Codex). SuperConsole launches them; it doesn't replace them.

---

## Usage insights

See exactly where your tokens and money go, at every level, with no spreadsheets and no guessing.

| Level | What you see |
| --- | --- |
| **Session** | Tokens and cost for each chat or CLI session. Resumed sessions count only the new usage, never double. |
| **Agent** | Spend and activity per agent or bot, with weekly budget tracking. |
| **Project** | Cost and tokens per workspace, with a 365-day activity heatmap. |
| **User** | Your personal lifetime usage across every project and device. |
| **Org** | Team-wide totals and breakdowns by member, ready for billing and budget reviews. |

**What's tracked**
- Input, output, reasoning, and cached tokens, priced separately for accurate cost.
- Breakdowns by model, provider, CLI, member, and project.
- Time ranges from the last 24 hours to the last 12 months.
- Cost report export.

Usage is calculated locally from your own sessions, so the dashboard opens instantly and works offline.

---

## What you get

**Terminals & agents**
- Real PTY terminals per workspace with a fast WebGL renderer.
- Run multiple CLIs at once: Claude, Codex, Droid, Antigravity, or a shell.
- Resume sessions directly, without duplicate history.
- Pick model and reasoning effort before launch (Low → Max); the choice is written to each CLI's native config.

**SuperBots**
- Autonomous agents defined as plain files in `.superconsole/agents/<bot>/`.
- Sensitive actions (shell commands, connectors, persona edits) wait for your approval, from the desktop, your phone, or Telegram.
- Secrets are masked in notifications and logs.
- Weekly budget caps pause a bot automatically.

**Scheduled jobs**
- Cron-style headless runs with results delivered to your Inbox.
- Trigger by schedule, manually, over HTTP, from Telegram, or on incoming Gmail.

**Mobile companion**
- Touch-friendly shell with live terminal streaming, accessory keys, and a stop button.
- Approve bot actions, review diffs, and switch models from your phone.
- Closing a tab on mobile closes it on desktop.

**Built-in tools**
- Native streaming chat (Anthropic, OpenAI-compatible, Gemini, OpenRouter).
- Code editor with Markdown preview, one-click Git commit and push, and an embedded browser tab.
- Plugin and hook marketplace for skills, MCP servers, and connectors.

**Local-first**
- Everything works offline; your data lives in a local SQLite database.
- Optional cloud sign-in syncs settings, keys, and connectors across devices.
- Optional bring-your-own Turso database for syncing workspaces, agents, and sessions.
- Credentials are encrypted at rest, and no OS keychain prompts.

---

## Updates

SuperConsole checks for new versions in-app. You can also download any release manually from the [Releases page](https://github.com/superConsoleAI/superconsole/releases).

## Support & feedback

- Found a bug or want a feature? [Open an issue](https://github.com/superConsoleAI/superconsole/issues).
- Please include your macOS version, app version, and steps to reproduce.

---

*This repository hosts public release builds of SuperConsole.*
