# Commands and permissions

## Commands

| Command | Description | Permission | Usage |
|---------|-------------|------------|-------|
| `/report` | Report a player (includes last 30 min chat, commands, CoreProtect) | `` | `/report <player> [reason]` |
| `/kick` | Kick player | `` | `/kick` |
| `/ban` | Ban player (IP ban + confiscate value to Server Reserve) | `` | `/ban` |
| `/tempban` | Temporarily ban player (IP ban + confiscate value to Server Reserve) | `` | `/tempban` |
| `/unban` | Unban player | `` | `/unban` |
| `/mute` | Mute player | `` | `/mute` |
| `/unmute` | Unmute player | `` | `/unmute` |
| `/tpoffline` | Teleport to online player by name | `` | `/tpoffline` |
| `/vanish` | Toggle vanish | `` | `/vanish` |
| `/socialspy` | Toggle social spy | `` | `/socialspy` |
| `/invsee` | Open player inventory | `` | `/invsee` |
| `/echest` | Open your ender chest (or another player's with staff permission) | `` | `/echest` |
| `/enderchest` | Open your ender chest (or another player's with staff permission) | `` | `/enderchest` |
| `/setspawn` | Set server spawn | `` | `/setspawn` |
| `/tppos` | Teleport to coordinates | `` | `/tppos` |
| `/sudo` | Run command as player | `` | `/sudo` |
| `/give` | Give items to player | `` | `/give` |
| `/speed` | Set walk or fly speed | `` | `/speed` |
| `/realname` | Resolve nickname to username | `` | `/realname` |
| `/whois` | Player information lookup | `` | `/whois` |
| `/recipe` | Lookup item recipe | `` | `/recipe` |
| `/skull` | Get player head | `` | `/skull` |
| `/lightning` | Strike lightning | `` | `/lightning` |
| `/ext` | Extinguish fire | `` | `/ext` |
| `/mutechat` | Mute global chat | `` | `/mutechat` |
| `/unmutechat` | Unmute global chat | `` | `/unmutechat` |
| `/tpo` | Force teleport to player | `` | `/tpo` |
| `/tpohere` | Force teleport player to you | `` | `/tpohere` |
| `/tpall` | Teleport all players to you | `` | `/tpall` |
| `/fly` | Toggle flight | `` | `/fly` |
| `/god` | Toggle god mode | `` | `/god` |
| `/gamemode` | Change gamemode (server console only) | `` | `/gamemode` |
| `/gms` | Survival mode | `` | `/gms` |
| `/gmc` | Creative mode | `` | `/gmc` |
| `/gma` | Adventure mode | `` | `/gma` |
| `/gmsp` | Spectator mode | `` | `/gmsp` |
| `/broadcast` | Broadcast message | `` | `/broadcast` |
| `/timeset` | Set world time (staff) | `rootadmin.time` | `/timeset [ticks]` |
| `/day` | Set time to day | `` | `/day` |
| `/night` | Set time to night | `` | `/night` |
| `/weather` | Set weather | `` | `/weather` |
| `/remove` | Remove items from player | `` | `/remove` |
| `/burn` | Ignite player | `` | `/burn` |
| `/world` | Teleport to world spawn | `` | `/world` |
| `/setwarp` | Create warp | `` | `/setwarp` |
| `/delwarp` | Delete warp | `` | `/delwarp` |
| `/item` | Give items (alias) | `` | `/item` |
| `/worldborder` | Reapply world border from root-admin.yml | `` | `/worldborder` |
| `/rootrestart` | Graceful server restart with countdown | `` | `/rootrestart [cancel]` |
| `/rootstop` | Graceful stop for update with countdown | `` | `/rootstop [cancel]` |
| `/rootannouncer` | RootMC announcer admin | `` | `/<command> reload/list/now [index]` |
| `/announcer` | Toggle RootMC rotating announcements for yourself | `` | `/<command> [on/off/status]` |
| `/mapper` | Map polygon areas for RootMC features | `` | `/mapper list / start <area> / refine <area> / lava <area> / create <name> [waypoint/refine/lava] / stop / reload` |

## Permissions

| Permission | Description | Default |
|------------|-------------|---------|
| `rootadmin.time` | Set world time via /timeset, /day, /night | `op` |
| `rootrestart.admin` | Start a manual restart or stop-for-update countdown | `op` |
| `rootrestart.cancel` | Cancel a pending restart or stop countdown | `op` |
| `rootannouncer.toggle` | Toggle whether you receive RootMC announcements | `true` |
| `rootannouncer.reload` | Reload root-announcer.yml | `op` |
| `rootannouncer.now` | Broadcast a message immediately | `op` |
| `rootmapper.admin` | Use all /mapper commands | `op` |

