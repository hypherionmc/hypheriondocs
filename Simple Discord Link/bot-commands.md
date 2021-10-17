---
order: d
---

The bot current includes two commands. The commands are `whitelist` and `list`.

## Whitelist Command
!!!warning
You need to set whitelisting to true in the config and whitelisting needs to be enabled on your server before this command will work.

Also note that the bot can ONLY unwhitelist players that have been whitelisted through the bot!
!!!

### whitelist add playerName
The command is `prefix`whitelist add. `prefix` will be what you configured in the config. The default is `~`

This adds a minecraft player to your server whitelist. Only one user can add a profile. Example: `~whitelist add hypherionsa`

### whitelist remove playerName
The command is `prefix`whitelist remove. `prefix` will be what you configured in the config. The default is `~`

This removes a minecraft player from your server whitelist. Only the person that added the whitelist, Discord admins and people with KICK perms can unwhitelist users. Example: `~whitelist remove hypherionsa`

### whitelist list
This command lists all player whitelisted THROUGH THE BOT!

## Other Commands

### list
The command is `prefix`list. `prefix` will be what you configured in the config. The default is `~`

This command returns a list of online players on the server
