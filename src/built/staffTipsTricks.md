# Discord
#### Do not include <> nor [] - <> means required and [] means optional.

## How to Use [Support Tickets](http://liba001.github.io/Support-Manager)
`/tickets here` - View all tickets for the current server
`/tickets [user]` - View tickets for a specific user
`/ticket show <ticket number>` - Show a specific ticket.
`/ticket close <ticket number>; [reason]` - CLose a specific ticket.

##  How to use Moderation Commands
#### All Moderation should be done via [Dyno](http://dynobot.net) commands!
- `?blacklist <url>` - Add a url or comma separated list of urls to automod blacklist
- `?whitelist <url>` - Add a url or comma separated list of urls to automod whitelist
- `?clearwarn <user>` - Clear warnings a user
- `?prune` - Delete a number of messages from a channel (limit 1000)
- `?command <command name>` - Enable/disable a command
- `?module <module name>` - Enable/disable a module
- `?ignorechannel <channel>` - TOggles command usage for a channel.
- `?ignoreuser <user> <reason>` - Toggles command usage for a user.
- `?ban <user> [limit] <reason>` - Ban a member, optional time limit
- `?kick <user> <reason>` - Kick a member
- `?mute <user> [limit] <reason>` - Mute a member so they cannot type or speak, time limit in minutes
- `?softban <user> <reason>` - Softban a member (ban and immediate unban to delete user messages)
- `?unban <user or id> [reason]` - Unban a member
- `?unmute <user> [reason]` - Unmute a member
- `?warn <user> <reason>` - Warn a member
- `?warnings [user]` - Get warnings for the server or user
- `?modlogs <user>` - Get a list of modlogs for a user
- `?ignored` - List channels and users where commands are ignored
- `?rolepersist <user> <role>, <reason>` - Assign/unassign a role that persists if the user leaves and rejoins
- `?moderations` - Get a list of active moderations (timed) and remaining time
- `?lock <channel> [time] [message]` - Lock a channel
- `?unlock <channel> [message]` - UNlock a previously locked channel

## How to use [@GiveawayBot#2381](http://giveawaybot.party)
- `!gcreate` - creates a giveaway (interactive setup)
- `!gstart <time> [winners]w [prize]` - starts a giveaway (quick setup)
- `!gend [messageId]` - ends (picks a winner for) the specified or latest giveaway in the current channel
- `!greroll [messageId]` - re-rolls the specified or latest giveaway in the current channel
- `!glist` - lists active giveaways on the server

# Minecraft
## NBT General Formats
- Named Items - `display:{Name:"\"name here\""}`
- Renaming Animals - `/data merge entity @e[sort=nearest,limit=1,type=ANIME_TYPE_HERE] {CustomName:"\"NAME_HERE\""}`

## Specific Commands
- Invisibility - `/effect give @p minecraft:invisibility 100000 1 true`
- CATNIP - `/give @p minecraft:potion{CustomPotionEffects:[{Id:9,Duration:60000}],CustomPotionColor:16122102,display:{Name:"\"cat16's catnip >:)\""}}`
- Drill - `/give @p minecraft:diamond_pickaxe{display:{Name:"\"Drill\""},Unbreakable:1,Enchantments:[{id:efficiency,lvl:100}]} 1`
- WAK-E STICC - `/give @p stick{display:{Name:"\"WHACC-E STICC\""},Enchantments:[{id:knockback,lvl:100}]} 1`

## How to Deal with Hackers
- `/team join hacker [name]` -  Add a hacker to the database
- `/team leave hacker [name]` __&&__ `/gamemode survival [name]` - Remove a hacker from the database
