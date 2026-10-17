# Nibi releases

Nibi is a small desktop friend for Windows that watches your AI agents (Claude Code, Codex, Antigravity, VS Code, ChatGPT) and services (GitHub CI, Vercel, DevPulse, calendar) and rings a bell when one needs you. Everything stays on your PC.

**Website:** https://niranjand.in/nibi

This repository only holds the installers. The source code is private.

## Install

1. Download `Nibi_<version>_x64-setup.exe` from the [latest release](https://github.com/niranjan266/nibi-releases/releases/latest).
2. Run it. It installs just for you (no admin prompt) and does not start with Windows unless you switch that on in Settings.
3. The installer is not code-signed yet, so Windows SmartScreen may say "Windows protected your PC". Click **More info**, then **Run anyway**.

## Uninstall

Windows Settings → Apps → Nibi → Uninstall. Uninstalling removes every agent hook Nibi added (Claude Code, Codex, Antigravity, Copilot); your other hooks are left alone. Tick "Delete the application data" to also remove Nibi's local history.

## Updates

Nibi checks this repository once a day and asks before installing anything. Updates are signed with Nibi's update key.

## Licence

© 2026 Niranjan. All rights reserved. See [LICENSE](LICENSE) and [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md).
