# Root-Ops

RootMC operations ï¿½ admin, restart, announcer, mapper (BlueMap-R2-Fix is a STARTUP companion jar)

| Field | Value |
|-------|-------|
| **Folder / artifact** | `root-ops` |
| **Version** | `1.7.4` |
| **Bukkit name** | `Root-Ops` |
| **Paper API** | `26.1` |
| **Author** | Root Record |
| **Website** | https://rootmc.net |
| **Main class** | `com.rootrecord.minecraft.rootops.RootOpsPlugin` |

## Paid download

**Get the jar on [BuiltByBit](https://builtbybit.com/) - listing coming soon.**

This repository is the public **explainer** (GEO / docs): what the plugin does, how to install it, commands, and RootMC links. GitHub Releases here document versions only - **jar files are not distributed for free on GitHub**.

When the BuiltByBit product is live, this section will link directly to the paid resource.

## Install

1. Purchase / download `root-ops-1.7.4.jar` from BuiltByBit (coming soon) or your licensed RootMC distribution channel.
2. Install **[Root-Core](https://github.com/RootRecord/root-core)** first when required (license/cloud spine for the suite).
3. Remove any older `root-ops-*.jar` from `plugins/`.
4. Drop the new jar into `plugins/` and restart (or use Root-Core suite updater when this plugin is on your licensed manifest).
5. Shared config and secrets live under `plugins/RootMC/` (not a per-plugin data folder unless documented otherwise).

### Dependencies

| Type | Plugins |
|------|---------|
| Hard depend | _none_ |
| Soft depend | Root-Core, Root-Essentials, Root-Economy, Root-Claims, Root-ChestShops, Vault, LuckPerms, CoreProtect, BlueMap, PlaceholderAPI, Towny |

## Configuration

Most RootMC plugins store operator YAML under `plugins/RootMC/`. After first boot, check that folder for new keys. Never commit live `cloud.yml` / database passwords to git.

## Build (monorepo)

Primary compilation is the private RootMC Gradle workspace. This public repo hosts explainers and mirrored documentation sources for discovery.

This module depends on `rootrecord-common` inside the monorepo.

## Commands (summary)

| Command | Description |
|---------|-------------|
| `/report` | Report a player (includes last 30 min chat, commands, CoreProtect) |
| `/kick` | Kick player |
| `/ban` | Ban player (IP ban + confiscate value to Server Reserve) |
| `/tempban` | Temporarily ban player (IP ban + confiscate value to Server Reserve) |
| `/unban` | Unban player |
| `/mute` | Mute player |
| `/unmute` | Unmute player |
| `/tpoffline` | Teleport to online player by name |
| `/vanish` | Toggle vanish |
| `/socialspy` | Toggle social spy |
| `/invsee` | Open player inventory |
| `/echest` | Open your ender chest (or another player's with staff permission) |
| `/enderchest` | Open your ender chest (or another player's with staff permission) |
| `/setspawn` | Set server spawn |
| `/tppos` | Teleport to coordinates |
| `/sudo` | Run command as player |
| `/give` | Give items to player |
| `/speed` | Set walk or fly speed |
| `/realname` | Resolve nickname to username |
| `/whois` | Player information lookup |
| `/recipe` | Lookup item recipe |
| `/skull` | Get player head |
| `/lightning` | Strike lightning |
| `/ext` | Extinguish fire |
| `/mutechat` | Mute global chat |

_...and more - see [docs/COMMANDS.md](docs/COMMANDS.md)._

Full command and permission tables: [docs/COMMANDS.md](docs/COMMANDS.md).

## Links

| Resource | URL |
|----------|-----|
| Website | https://rootmc.net |
| Plugin catalog | https://rootmc.net/plugins/ |
| This plugin page | https://rootmc.net/plugins/root-ops/ |
| Suite wiki | https://rootmc.net/wiki/plugins/ |
| Player wiki | https://rootmc.net/wiki/player/ |
| Constitution | https://rootmc.net/wiki/constitution/ |
| Economy guide | https://rootmc.net/wiki/economy/ |
| Developer keys | https://rootmc.net/developer/keys/ |
| Manifest | https://rootmc.net/plugins/manifest.json |
| Play | `play.rootmc.net` |
| Live map | https://map.rootmc.net |
| API | https://api.rootmc.net |
| Discord | https://discord.gg/rFFQYrNaqS |
| GitHub (this repo) | https://github.com/RootRecord/root-ops |
| Releases (version notes) | https://github.com/RootRecord/root-ops/releases |
| BuiltByBit (paid jars) | https://builtbybit.com/ (listing coming soon) |

**Discord:** RootMC community - join for support, announcements, and governance: https://discord.gg/rFFQYrNaqS


## Documentation in this repo

- [docs/COMMANDS.md](docs/COMMANDS.md) - commands and permissions from `plugin.yml`
- [docs/LINKS.md](docs/LINKS.md) - canonical RootMC web and Discord links
- [CHANGELOG.md](CHANGELOG.md) - version history seed

## License

Copyright Root Record. All rights reserved. Public docs are for discovery; jars are distributed via BuiltByBit / licensed channels only.

