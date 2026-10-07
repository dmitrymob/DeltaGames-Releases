# Delta Games — official downloads

Download **[Delta Hub for Windows](https://github.com/dmitrymob/DeltaGames-Releases/releases/latest/download/DeltaHubSetup.exe)**, install it, open the desktop shortcut, select a game and click **Установить**. The launcher downloads, verifies and installs the current game build automatically.

## Games

- [Delta Soul Survival 0.2.0 — Windows x64](https://github.com/dmitrymob/DeltaGames-Releases/releases/tag/dss-0.2.0)
- [Pixels Are Coming 1.5.3 — online build, Windows x64](https://github.com/dmitrymob/DeltaGames-Releases/releases/tag/pixels-1.5.3)

This public repository contains distribution metadata and compiled release assets only. Game source projects are maintained separately.

The launcher reads [manifest.json](https://raw.githubusercontent.com/dmitrymob/DeltaGames-Releases/main/manifest.json). Archives are downloaded over HTTPS and checked against their size and SHA-256 before installation.

When downloading a game ZIP manually, extract the whole archive; the EXE requires its accompanying data and libraries. Delta Hub installs games from the network and does not import existing local EXE files.

The launcher checks its own updates at startup and hourly. When available, click **Обновить Delta Hub**; it installs the verified update and restarts while keeping games and settings.
