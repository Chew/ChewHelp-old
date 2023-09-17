---
title: Chewbotcca Commands
description: Commands for Chewbotcca Discord bot
published: true
date: 2023-09-17T18:58:15.487Z
tags: chewbotcca, commands, discord
editor: markdown
dateCreated: 2023-08-20T19:23:02.228Z
---

# Chewbotcca Discord Commands

Bot obviously needs at least Read and Send messages if you want a response. Permissions listed under "Bot Permissions" are permissions the bot needs to execute the command. Permissions listed under "User Permissions" are permissions you, the executor, need to execute the command. The bot will notify you of missing permissions if needed.

The following permissions are required for most text-based commands.
They are not required for *slash-based* commands. In that case, the user needs "Use Application Commands" permission.

- Read Messages - required to see commands
- Send Messages - required to respond to commands
- Embed Links - required for most commands

The rest of the permissions are optional, but are required if you plan on utilizing all bot commands.

- Add Reactions - needed for paginators to work properly
- External Emotes - makes some commands look nicer (this must be given to the @everyone role for slash-commands)
- Ban Members - for `/ban`, as you'd expect
- Manage Roles - for `/role` command
- Manage Nicknames - for `/dehoist` command
- Manage Webhooks - to view webhook count in `/channelinfo` and to `/rory follow`

## Command List

> *Please note: Not all commands have help pages yet! Ones with pages are marked in blue.*
{.is-warning}

| Command | Args | Description |
| ------- | ---- | ----------- |
| [/help](/bots/discord/chewbotcca/commands/help) | None | Get help and some basic information about the bot |
| [/invite](/bots/discord/chewbotcca/commands/invite) | None | Get a link to invite the bot to your server |
| [/ping](/bots/discord/chewbotcca/commands/ping) | None | Ping the bot to check its heart rate. Is it ok? If it doesn't respond, it might not be okay, or perhaps you failed to configure permissions properly. |
| [/stats](/bots/discord/chewbotcca/commands/stats) | None | Get some cool, interesting, and very epic stats about the bot |
| [/cat](/bots/discord/chewbotcca/commands/cat) | None | A crucial command. Get a random picture of a cat! |
| [/catfact](/bots/discord/chewbotcca/commands/catfact) | None | Get a random cat fact! Cats are really interesting! |
| [/dog](/bots/discord/chewbotcca/commands/dog) | None | Same as cat, but a dog instead of a cat. Occasionally it puts a video which won't embed, but oh well. |
| [/define](/bots/discord/chewbotcca/commands/define) | None | Defines a word via a dictionary. Returns the first result, may not be the best result, but definitely a result nonetheless. |
| [/urban](/bots/discord/chewbotcca/commands/urban) | \<word to search> | Like define, but instead of defining with a real dictionary, it queries the slightly edgier Urban dictionary. As a result, this command is NSFW only. |
| [/youtube](/bots/discord/chewbotcca/commands/youtube) | \<search term> | Searches YouTube for a video and posts cool stats about it! This command costs me money (I think) so feel free to donate to keep it free for everyone! |
| [/mcserver](/bots/discord/chewbotcca/commands/mcserver) | \<java server ip> | Queries a Minecraft: Java edition server for its stats. This command does NOT support bedrock edition servers yet, but it may soon! |
| [/mcuser](/bots/discord/chewbotcca/commands/mcuser) | \<username or UUID> | Gets Minecraft profile information for a user, including their name, name history, and a picture of their face. |
| [/lastfm](/bots/discord/chewbotcca/commands/lastfm) | \<username> | Gets last played (or currently playing) song information for the specified last.fm user. |
| [/rubygem](/bots/discord/chewbotcca/commands/rubygem) | \<gem name> | Gets information for the specific ruby gem. |
| [/serverinfo](/bots/discord/chewbotcca/commands/serverinfo) | \[boosts,bots,channels,member \<position>,roles,milestones] | Gets basic information for the server |
| [/info](/bots/discord/chewbotcca/commands/info) | \<command> | Gets information about a specific command |
| [/github issue](/bots/discord/chewbotcca/commands/github#issue) | \<repo> \<issue#> | Gets an issue or pull request from the specified GitHub repository. |
| [/quote](/bots/discord/chewbotcca/commands/quote) | \<message id> \[optional: channel id] | Quotes a message, puts the message and provides a link to jump to it. Useful for quoting messages outside of the specific server. |
| [/github user](/bots/discord/chewbotcca/commands/github#user) | \<user/org name> | Gets a user or org's profile from GitHub |
| [/trbmb](/bots/discord/chewbotcca/commands/trbmb) | None | Generate a TRBMB Phrase! |
| [/acronym](/bots/discord/chewbotcca/commands/acronym) | \<acronym> | Generates a random acronym based on input! Letters only. |
| [/userinfo](/bots/discord/chewbotcca/commands/userinfo) | \[optional: mention] | Gets user info for you! Mention a user to get their info. |
| [/roleinfo](/bots/discord/chewbotcca/commands/roleinfo) | \<role mention/name/id> | Gets information about a role! Add "members" to view role members. |
| [/roll](/bots/discord/chewbotcca/commands/roll) | \[dice "d" sides] | Rolls dice. Uses D&D format, for example, 1d6 = Rolls 1 6 sided die. Using this command with no arguments rolls 1 6-sided die. |
| [/feedback](/bots/discord/chewbotcca/commands/feedback) | \<your feedback> | Leave some feedback for Chew! :3 |
| [/channelinfo](/bots/discord/chewbotcca/commands/channelinfo) | \[optional: channel id or mention] | Gets basic information about a channel. |
| [/github repository](/bots/discord/chewbotcca/commands/github#repository) | \<repo path> | Gets information about a specific GitHub repo. For example, %^ghrepo Chewbotcca/Discord |
| [/profile](/bots/discord/chewbotcca/commands/profile) | None | Gets your bot profile |
| [/botinfo](/bots/discord/chewbotcca/commands/botinfo) | \<bot mention> \[list] | Gets bot information from an optionally specified bot list. |
| [/8ball](/bots/discord/chewbotcca/commands/8ball) | \<question> | Ask the magic 8 ball a question! |
| [/qrcode](/bots/discord/chewbotcca/commands/qrcode) | \<data> | Turn input into a QR Code! |
| [/serversettings](/bots/discord/chewbotcca/commands/serversettings) | \[optional: set] \<data> | Get settings for your server. Must have Manage Server. |
| [/numberfact](/bots/discord/chewbotcca/commands/numberfact) | \<number> [trivia?,math,year,date] | Gets a numberfact for the specified number and type. |
| [/spigotdrama](/bots/discord/chewbotcca/commands/spigotdrama) | None | Generates some spigot drama. |
| [/mcwiki](/bots/discord/chewbotcca/commands/mcwiki) | \<article> | Searches the Minecraft Wiki for an article and returns a summary and an image. |
| [/reddit](/bots/discord/chewbotcca/commands/reddit) | \<subreddit> \[post #] | Grabs a post from a subreddit and links it. Leave both blank for a random post? |
| [/mcissue](/bots/discord/chewbotcca/commands/mcissue) | \<issue link or num> | Gets an issue from Mojira or Spigot JIRA and describes it. |
| [/discrim](/bots/discord/chewbotcca/commands/discrim) | \[optional: discrim to look up] | Looks through the user cache to find users with the specified (if none, your) discriminator. To cache the current server, run %^sinfo. |
| [/rory](/bots/discord/chewbotcca/commands/rory) | \[optional: id]/\<follow> | Gets a random picture of Rory :3. Add "follow" to receive new Rory pics! |
| [/privacy](/bots/discord/chewbotcca/commands/privacy) | None | Returns a link to the Chewbotcca Discord Bot privacy policy. |
| [/ocr](/bots/discord/chewbotcca/commands/ocr) | Attach Image or URL | Runs an OCR which finds texts on a given image and returns the result. 1 minute cooldown! |
| [/paste](/bots/discord/chewbotcca/commands/paste) | \[optional: path to discord upload] | Finds or uses provided discord attachment of a text file and uploads it to a pastebin site. Avoids having to download and view manually. |
| [/userstats](/bots/discord/chewbotcca/commands/userstats) | None | Finds amount of users with all user flags (excluding Nitro) and sorts them. |
| [/memerator](/bots/discord/chewbotcca/commands/memerator) | <meme/user> \<query> | Finds a Memerator.me meme or user based on query. |
| [/apod](/bots/discord/chewbotcca/commands/apod) | \[optional: mm/dd/yyyy] | Gets the current (or if args, that day's) NASA Astronomy Photo of the Day. |
| [/unsuppress](/bots/discord/chewbotcca/commands/unsuppress) | <message link/channel?+message id> | Unsuppresses an embed for a specified message. Can be just message ID, channel+message ID, or a link to the message, but the message has to be on the server. |
| [/coinflip](/bots/discord/chewbotcca/commands/coinflip) | None | Flip a coin, very simple! |
| [/hangar](/bots/discord/chewbotcca/commands/hangar) | \<search> | Searches Hangar for a specified project. |
| [/modrinth](/bots/discord/chewbotcca/commands/modrinth) | \[query] | Searches modrinth.com for a specified project. |
| [/wynncraft](/bots/discord/chewbotcca/commands/wynncraft) | \[guild/player] | Finds player or guild stats for Wynncraft |
