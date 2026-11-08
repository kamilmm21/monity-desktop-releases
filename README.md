# Monity Desktop

**Website change monitoring, uptime checks and browser tests that run on your own computer. Free: no account, no subscription, no credits.**

Monity watches web pages for you and tells you what changed, what went down and what broke. The desktop app does it locally, with your monitors and their history stored on your machine.

## Download

| Your computer | Download |
|---|---|
| Mac with Apple Silicon (M1 or later) | [Monity-AI-mac-arm64.dmg](https://github.com/kamilmm21/monity-desktop-releases/releases/latest/download/Monity-AI-mac-arm64.dmg) |
| Mac with an Intel processor | [Monity-AI-mac-intel.dmg](https://github.com/kamilmm21/monity-desktop-releases/releases/latest/download/Monity-AI-mac-intel.dmg) |
| Windows 10 or 11 | [Monity-AI-windows.exe](https://github.com/kamilmm21/monity-desktop-releases/releases/latest/download/Monity-AI-windows.exe) |

These links always point to the newest release. On a Mac, open the dmg and drag Monity AI to Applications (the app is signed and notarized by Apple). On Windows, if you see "Windows protected your PC", choose More info, then Run anyway.

The app updates itself, and your monitors and their history carry over.

## What it does

- **Page changes.** Watch a whole page, one element or an area, for text or visual changes, as often as every 5 minutes, with a picture of exactly what changed.
- **Pages behind a login.** Sign in once in Monity's own browser; the session stays on your computer.
- **Uptime.** Website, keyword, port and DNS monitors, checked as often as every 30 seconds. Local addresses work too: your dev server, your router, a site on your VPN.
- **Browser tests.** Check that sign-up, login, search or checkout still works, step by step, with a picture of each page.
- **Datasets (beta).** Collect rows from many pages (products, prices, listings) and get told which rows are new, changed or gone. Export as CSV, Excel, JSON or Markdown.
- **Alerts** as desktop notifications, by email through your own mail server, or to Discord, Microsoft Teams and webhooks.

## Bring your own AI (optional)

Connect the AI you already have: the **Claude Code or Codex subscription** you already pay for, **Ollama**, or any OpenAI-compatible API key. It describes each change in plain words, and Ask Monity sets up monitors and answers questions about them. Everything else works without AI.

Claude Code, Codex and other MCP clients can also create and review monitors through Monity's local MCP server.

## Desktop or cloud?

The desktop app checks pages only while your computer is on and the app is running (it keeps working from the menu bar or system tray when you close the window). For checks around the clock, from Monity's servers, with full-page screenshots and saved copies of every page version, team workspaces, public status pages and heartbeat monitors, use [monity.ai](https://monity.ai). It has a free plan.

## Help

Questions and bug reports: [hello@monity.ai](mailto:hello@monity.ai) or [open an issue](https://github.com/kamilmm21/monity-desktop-releases/issues).

Made by [Monity.AI Ltd](https://monity.ai).
