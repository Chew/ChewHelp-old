---
title: MLB Game Feed Bot
description: Introduction to the MLB Game Feed Discord bot
published: true
date: 2023-08-17T20:39:33.367Z
tags: bot, discord, mlb
editor: markdown
dateCreated: 2023-08-01T02:22:56.346Z
---

# MLB-GameFeed-Bot

Add to your server with [this link](https://canary.discord.com/api/oauth2/authorize?client_id=987144502374436895&permissions=1067024&scope=bot%20applications.commands)!

View the bot on Discord's [app directory](https://discord.com/application-directory/987144502374436895)!

This bot allows you to view the live play-by-plays for any MLB.com game. This attempts to mimic [gameday](https://mlb.com/gameday)

To get started, add the bot to your server. Next, wait for a game to be active, finally, type `/startgame` to see active Major League games.

## Watching a Game Feed

You can learn about watching a game feed [here](/bots/discord/mlb-game-feed/watching-a-game-feed). You can see hits, game advisories, and more.

## Commands

Click a command to learn more about it!

- [`/plangame`](/bots/discord/mlb-game-feed/commands/plangame) - Plans a game by sending an embed of the upcoming game. Optionally create a thread or a scheduled event! Select a team, then a date, shows up to 25 upcoming games. Optionally pass a sport to find minor league games!
- [`/startgame [game]`](/bots/discord/mlb-game-feed/commands/startgame) - Starts a game. Select a game from the list, but any gamePk is acceptable. You can grab this from sites like https://mlb.chew.pw to show minor league games. If no games show up, there are no active Major League games.
- [`/stopgame`](/bots/discord/mlb-game-feed/commands/stopgame) - Stops the currently running game.
- [`/score`](/bots/discord/mlb-game-feed/commands/score) - Shows you the current score privately.
- [`/setinfo`](/bots/discord/mlb-game-feed/commands/setinfo) - A command to show specific info as a Voice Channel name.
- [`/config`](/bots/discord/mlb-game-feed/commands/config) - A way to tune the bot to your liking per-channel!

Running `/startgame` does not memorize the game, you will have to start it every time a game starts!
