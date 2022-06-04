---
order: b
title: Configuring the mod
---

Configuration of the mod is done completely using COMMANDS. These can be executed by players with Permission level 3 (default vanilla OP level).

Below you can find all the commands, as well as what they do.

***

||| Command `maintenance status`
This command displays the current status of the mod. It will be either `true` or `false`
|||

||| Command `maintenance on/off`
Enable or disable maintenance mode
|||

||| Command `maintenance list`
Return a list of users that can join your server during maintenance mode. YOU WILL HAVE TO ADD YOURSELF AS WELL, REGARDLESS OF YOUR PERMISSIONS
|||

||| Command `maintenance reload`
Reload the config, if you edited the config file manually. (The config file is named `mmode.json`)
|||

||| Command `maintenance backup`
Perform a full backup manually
|||

||| Command `maintenance doBackups true/false`
Enable or disable the creation of backups when enabling maintenance mode
|||

||| Command `maintenance setMessage "Your Message Here"`
Set the message to be displayed to the player when they try to join the server during maintenance mode. This might include the planned timeframe, and or other information about the maintenance
|||

||| Command `maintenance addAllowed MinecraftNameHere`
Add a player to the list of allowed players that can join the server during maintenance mode
|||

||| Command `maintenance removeAllowed MinecraftNameHere`
Remove a player from the list of allowed players that can join the server during maintenance mode
|||


And that's it. More feature/commands will come in the future
