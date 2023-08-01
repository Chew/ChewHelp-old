---
title: MLB Game Feed Bot
description: Introduction to the MLB Game Feed Discord bot
published: true
date: 2023-08-01T02:22:56.346Z
tags: bot, discord, mlb
editor: markdown
dateCreated: 2023-08-01T02:22:56.346Z
---

# MLB-GameFeed-Bot

Add to your server with [this link](https://canary.discord.com/api/oauth2/authorize?client_id=987144502374436895&permissions=1067024&scope=bot%20applications.commands)!

This bot allows you to view the live play-by-plays for any MLB.com game. This attempts to mimic [gameday](https://mlb.com/gameday)

To get started, add the bot to your server. Next, wait for a game to be active, finally, type `/startgame` to see active Major League games.

## Supported Message Types
- Score Changes
- Game Advisories (Injury Delay, Pitching changes, etc)
- Inning Changes

## Commands

Click a command to learn more about it!

- [`/plangame`](/bots/discord/mlb-game-feed/commands/plangame) - Plans a game to be played.
- [`/startgame [game]`](/bots/discord/mlb-game-feed/commands/startgame) - Starts a game. Select a game from the list, but any gamePk is acceptable. You can grab this from sites like https://mlb.chew.pw to show minor league games. If no games show up, there are no active Major League games.
- [`/stopgame`](/bots/discord/mlb-game-feed/commands/stopgame) - Stops the currently running game.
- [`/score`](/bots/discord/mlb-game-feed/commands/score) - Shows you the current score privately.
- [`/setinfo`](/bots/discord/mlb-game-feed/commands/setinfo) - A command to show specific info as a Voice Channel name.

Running `/startgame` does not memorize the game, you will have to start it every time a game starts!
