---
title: Serverinfo Command
description: Breakdown and description for the serverinfo command for the Chewbotcca Discord bot
published: true
date: 2023-08-26T02:33:10.533Z
tags: bot, chewbotcca, command, discord
editor: markdown
dateCreated: 2023-08-26T02:33:10.533Z
---

# `/serverinfo` Command

> This page is under construction.
{.is-warning}


Gets information about the current server. Such as general info, bot info, boosters, etc.

## `general` Sub-Command

Shows basic information, such as the server name, owner, ID, creation date, locale, member and bot count, channel count and breakdown, perks, features, and booster counts. At the bottom are command mentions to find other useful sub-commands.

### Arguments

This sub-command has no arguments.

## `roles` Sub-Command

This sub-command lists all the roles in the server. The response is a paginator which shows you how many people have the role. With arguments, you can show more data, such as how many people use it as a display role, and how many people are online with the role.

### Arguments

| Name | Type | Kind | Description |
|------|------|------|-------------|
| `display_role` | `boolean` | Optional | Show amount of members whose display role is this.
| `online` | `boolean` | Optional | Shows amount of members with this role currently online. |

## `bots` Sub-Command

This sub-command lists all bots in the server, and when they were added.

### Arguments

| Name | Type | Kind | Description |
|------|------|------|-------------|
| `render_mention` | `boolean` | Optional | Whether to render mentions or leave them as a tag |

## Permissions

No special permissions are needed by users for any sub-command. The bot needs Attach Image for the `joingraph` sub-command.