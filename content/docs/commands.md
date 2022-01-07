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
| ``ban <member> [reason]`` | Ban a member from the server. | ``Ban Members`` |
| ``embed <title>, <description>`` | Create an embed-message in the current channel | ``Manage Channel`` |
| ``guildstats`` | Get a list of in-depth statistics about the current guild. ||
| ``help`` | Get a list of the bot's commands and what they do ||
| ``id`` | Get the current channel's numeric identifier. ||
| ``info`` | Get to know more about the bot. ||
| ``instagram`` | Search for & view an instagram profile. ||
| ``insult`` | Generate a random insult from the bot. ||
| ``invite`` | Get a list of the server's partner-servers and their invite links. ||
| ``kick <member> [reason]`` | Kick a member from the server. | ``Kick Members`` |
| ``poll <title>, <option>, <option>, [option], [option], ...`` | Create a poll with up to ten (10) options for users to vote on; parameters are separated by commas. ||
| ``prefix <character>`` | Change the prefix the bot listens to commands through. ||
| ``purge <number>`` | Delete a specified amount of messages from the current channel | ``Manage Channel`` |
| ``role <name>`` | Customize your user with one of several toggleable roles. | ``Manage Roles`` |
| ``roles`` | Get a list of the server's roles, in order from highest to lowest-hoisted. ||
| ``search <name>`` | Search the server's member list for a name. ||
| ``stats`` | Get a list of neat, live statistics about Guardian. ||
| ``storage	 <view / upload / download> <path>`` | View, download, and upload files stored in the bot's directory. | ``Administrator`` |
| ``valorant`` | Check a player's average VALORANT statistics. ||