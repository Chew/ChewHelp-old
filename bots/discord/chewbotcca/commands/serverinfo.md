---
title: Serverinfo Command
description: Breakdown and description for the serverinfo command for the Chewbotcca Discord bot
published: true
date: 2023-09-03T14:40:59.746Z
tags: bot, chewbotcca, command, discord
editor: markdown
dateCreated: 2023-08-26T02:33:10.533Z
---

# `/serverinfo` Command

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

## `boosts` Sub-Command

This sub-command lists all users boosting the server, and when they started boosting. Due to API limitations, it does not show how many times a user has boosted.

### Arguments

This sub-command has no arguments.

## `channnels` Sub-Command

This sub-command shows the channel type breakdown of the server. It shows more detailed information than what is already provided with the `general` sub-command.

### Arguments

This sub-command has no arguments.

## `milestones` Sub-Command

This sub-command shows upcoming member milestones based on a linear average. It takes the current amount of members, divides it by the age of the server in seconds, then figures out when the number will reach 25, 100, etc.

### Arguments

This sub-command has no arguments.

## `memberstats` Sub-Command

The member stats sub-command shows when there was most member joins in a day (assuming the members are all still on the server), and the largest slump between new joins.

### Arguments

This sub-command has no arguments.

## `joingraph` Sub-Command

This sub-command creates a graph of member joins. Since it only considers current members, the graph will always show positive growth.

An example graph can be seen below:

![joingraph](https://cdn.chew.pro/imgs/3sERPVb.png)

## Permissions

No special permissions are needed by users for any sub-command. The bot needs Attach Image for the `joingraph` sub-command.