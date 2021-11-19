---
title: Commands
description: Commands for the TransmuteIt plugin
published: true
date: 2021-11-19T04:01:52.466Z
tags: plugin, help, command
editor: markdown
dateCreated: 2021-11-19T04:01:52.466Z
---

# TransmuteIt Commands

TransmuteIt has some commands for you to use!

[] - Indicates a required argument.

() - Optional Argument

(x = y) - Optional argument where, if left blank, will fill it in as `y` instead.
 
This is separated into 2 categories, as there are 2 parent nodes: player commands and admin commands.

## Player Commands

ALL of these are granted by default, or can be granted with `transmute.player`. You do NOT need to give them manually, the nodes are really there if you choose to take them away.

### `/transmute`
*Permission node: `transmute.main`*

This opens a GUI with 4 menu options. 

1) Player Head - Your stats (clicking does nothing)
2) Paper - The equivalent of `/transmute help`
3) Enchant Table - The equivalent of `/discoveries`
4) Bucket - A GUI that enables Click to Transmute mode. Clicking items in your inventory transmutes them, assuming they have a value.

There are also subcommands, such as:

#### `/transmute take (amount = all of that item)`
*Permission node: `transmute.command.take`*

This takes an [amount] of the item in your main hand and converts it to EMC, given it has an EMC value (see /getemc). `/transmute take` without any arguments takes all items like this from your inventory. If this is your first time transmuting the item, you'll have discovered it, enabling you to get it below. Amount is anywhere between 1 and however much is in your inventory.

#### `/transmute get [item] [amount]` 
*Permission node: `transmute.command.get`*

This converts a discovered item from EMC. Tab complete is supported for the item name.

#### `/transmute learn`
*Permission node: `transmute.command.learn`*

This discovers the item without turning it into EMC.

#### `/transmute analyze`
*Permission node: `transmute.command.analyze`*

This analyses all your items in your inventory for their EMC values. Doesn't discover it though, maybe I should add that.

### `/discoveries (search term)`
*Permission node: `transmute.player.discoveries`*

Here you can view everything you've discovered. Just typing `/discoveries` shows everything. Adding an argument searches for that item.

### `/getemc (item = item in main hand)`
*Permission node: `transmute.command.getemc`*

Gets the current EMC value of the held item. Supply an item name to show its stats instead.

### `/emc`
*Permission node: `transmute.player.emc`*

Gets your current EMC value.

## Admin Commands

These can all be granted with `transmute.*`, though they each have their separate permissions. By default are given to operators.

### `/setemc`
*Permission node: `transmute.admin.setemc`*

Set the EMC value of the held item.