---
author: "Cooper Sullivan"
title: "Commands"
date: "2021-06-05"
description: "All of Guardian's commands in one place."
tags: []
categories: ["documentation"]
ShowToc: false
ShowBreadCrumbs: false
draft: false
---

## Prefixes, parameters, and what-not
All of Guardian's universally-accessible commands are listed below; when performed in Discord, all commands
must follow the server's command prefix (i.e. ``~help`` instead of ``help``). The table of commands below, however,
does not prefix any commands as the bot's prefix may vary from server to server. Some of the bot's commands have
parameters that are also required for the command to work. The parameters are surrounded with one of two types of brackets:
* ``<>`` signifies a required parameter.
* ``[]`` signifies an optional parameter.

## All commands
| Command | Description | Permission Required |
| :- | :-: | -: |
| ``apex <origin \| xbox \| playstation> <username>`` | Check a player's average Apex Legends statistics. ||
| ``csgo`` | Check a player's average Counter-Strike: Global Offensive statistics. ||
| ``embed <title> [description] [footer] [color] [channel]`` | Create an embed-message in the current channel | ``Manage Channel`` |
| ``fortnite <pc \| console \| mobile> <nae \| naw \| eu> <username>`` | Check a player's average Fortnite statistics. ||
| ``help`` | Get to know more about the bot. ||
| ``id`` | Get the current channel's numeric identifier. ||
| ``instagram`` | Search for & view an instagram profile. ||
| ``log <message>`` | Send a manual note to Guardian's audit logs. | ``View Audit Logs`` |
| ``partners`` | Get a list of the server's partner-servers and their invite links. ||
| ``poll <title> <option-a> <option-b> [option-c] [option-d] ...`` | Create a poll with up to ten (10) options for users to vote on; parameters are separated by commas. ||
| ``purge <number>`` | Delete a specified amount of messages from the current channel | ``Manage Channel`` |
| ``role <name>`` | Customize your user with one of several toggleable roles. | ``Manage Roles`` |
| ``roles`` | Get a list of the server's roles, in order from highest to lowest-hoisted. ||
| ``search <name>`` | Search the server's member list for a name. ||
| ``splitgate <steam \| xbox \| playstation> <username>`` | Check a player's average Splitgate statistics. ||
| ``stats-server`` | Get a list of in-depth statistics about the current guild. ||
| ``stats`` | Get a list of neat, live statistics about Guardian. ||
| ``storage	 <view \| upload \| download> <path>`` | View, download, and upload files stored in the bot's directory. | ``Administrator`` |
| ``valorant <username>`` | Check a player's average VALORANT statistics. ||