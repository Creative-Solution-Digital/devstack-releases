# DevStack releases

Installers for DevStack, a portable local development environment for
Windows and macOS (nginx, PHP, MariaDB/MySQL, PostgreSQL, Redis, Mailpit,
Node, Bun and more), by Creative Solution Digital.

Download the newest one from [Releases](../../releases/latest):

- **Windows:** `DevStack_<version>_x64-setup.exe`. It installs for your user
  account, in a folder you choose; DevStack keeps your projects and databases
  in that folder. Not signed yet: Windows SmartScreen asks first (More info,
  then Run anyway). Running a newer installer upgrades DevStack, and DevStack
  offers new versions itself.
- **macOS (Apple Silicon):** the `.dmg`. Open it and drag DevStack to
  Applications. Not notarized yet: the first time, allow it in System
  Settings → Privacy & Security → Open Anyway.

Each release lists SHA-256 checksums in `SHA256SUMS-*.txt`.

The source is private; this repository only holds the builds, made by
[the release workflow](.github/workflows/release.yml).
