# callvoteAdminEnforce

Dystopia has a callvoting system that works separately from SourceMod, so admin immunity is not accounted for when targeting a player with a callvote. It is possible for a regular player to call a vote to kick an admin from their own server, for example. This plugin will block callvote commands that target another player, and reply to the command with an explanation of why it was blocked, if the player has higher SourceMod admin immunity, than the player that sent the command. The plugin currently will affect these specific commands:
```
callvote kick <name>
callvote kickid <userid>
callvote ban <name>
callvote banid <userid>
callvote forcespec <userid|name>
```

Although this plugin was made specifically to work for Dystopia, I think it should work in any Source game that uses the same commands.