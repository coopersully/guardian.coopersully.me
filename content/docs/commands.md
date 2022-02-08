---
author: "Cooper Sullivan"
title: "Commands"
date: "2021-06-05"
description: "All of Guardian's commands in one place."
tags: ["features", "live"]
categories: ["documentation"]
ShowToc: false
ShowBreadCrumbs: false
draft: false
---

![](https://i.imgur.com/90moceq.png#center)

## Prefixes, parameters, and what-not
All of Guardian's universally-accessible commands are listed below. Every command implemented under Guardian
takes advantage of [Discord's native "Slash Commands"](https://support.discord.com/hc/en-us/articles/1500000368501-Slash-Commands-FAQ#:~:text=Slash%20Commands%20are%20the%20new,command%20right%20the%20first%20time.).
This allows us to create much more advanced commands while simplifying the user experience. However, this also means that the prefix of every command is ``/``, and this prefix
is completely unmodifiable. In addition, users attempting to execute any command via Guardian require the ``Slash Commands`` permission in the corresponding guild. An example of these "Slash Commands" can be found below.

![](https://i.imgur.com/yOEYpJW.png#center)

Some of the bot's commands have parameters that are also required for the command to work. The parameters are surrounded with one of two types of brackets:
* ``<>`` signifies a required parameter.
* ``[]`` signifies an optional parameter.

## All commands
| Command | Description | Permission Required |
| :- | :-: | -: |
| ``apex <origin ︱ xbox ︱ playstation> <username>`` | Check a player's average Apex Legends statistics. ||
| ``channel creation-date [channel]`` | Retrieve the timestamp at which a channel was created. ||
| ``channel id [channel]`` | Retrieve a channel's public identifier. ||
| ``channel topic [channel]`` | Retrieve the topic of a text channel. ||
| ``csgo <steam-id>`` | Check a player's average Counter-Strike: Global Offensive statistics. ||
| ``dadjoke`` | Generate a witty dad joke. ||
| ``dice <amount>`` | Roll a number of virtual dice, numbered 1-6 each. ||
| ``eight-ball [question] `` | Ask The Magic 8-Ball a yes or no question. ||
| ``embed <title> [description] [footer] [color] [channel]`` | Create an embed-message in the current channel | ``Manage Channel`` |
| ``flipacoin`` | Flip a virtual coin. ||
| ``fortnite <pc ︱ console ︱ mobile> <nae ︱ naw ︱ eu> <username>`` | Check a player's average Fortnite statistics. ||
| ``help`` | Get to know more about the bot. ||
| ``id`` | Get the current channel's numeric identifier. ||
| ``imgur <query>`` | Search for an image around the internet using Imgur ||
| ``instagram tag <query>`` | Search for & view an instagram hashtag. ||
| ``instagram user <query>`` | Search for & view an instagram user's profile. ||
| ``lock`` | Stops @everyone from sending messages and/or speaking in a specified channel. | ``Manage Channel`` |
| ``log <message>`` | Send a manual note to Guardian's audit logs. | ``View Audit Logs`` |
| ``meme`` | Generate a random meme from Imgur. ||
| ``partners`` | Get a list of the server's partner-servers and their invite links. ||
| ``ping``| Replies with "Pong!" ||
| ``poll <title> <option-a> <option-b> [option-c] [option-d] ...`` | Create a poll with up to ten (10) options for users to vote on; parameters are separated by commas. ||
| ``purge <number>`` | Delete a specified amount of messages from the current channel | ``Manage Channel`` |
| ``role <name>`` | Customize your user with one of several toggleable roles. | ``Manage Roles`` |
| ``roles`` | Get a list of the server's roles, in order from highest to lowest-hoisted. ||
| ``search message <query>`` | Search for a user in the current guild. ||
| ``search user <query>`` | Search for a user in the current guild. ||
| ``splitgate <steam ︱ xbox ︱ playstation> <username>`` | Check a player's average Splitgate statistics. ||
| ``stats-server`` | Get a list of in-depth statistics about the current guild. ||
| ``stats`` | Get a list of neat, live statistics about Guardian. ||
| ``storage	 <view ︱ upload ︱ download> <path>`` | View, download, and upload files stored in the bot's directory. | ``Administrator`` |
| ``sus`` | Generate a random "Among Us" related meme from Imgur. ||
| ``unlock`` | Allows @everyone to send messages and/or speak in a specified channel. | ``Manage Channel`` |
| ``user avatar [user]`` | Retrieve a user's avatar from their profile. ||
| ``user banner [user]`` | Retrieve a user's banner from their profile. ||
| ``user creation-date [user]`` | Retrieve the timestamp at which a user joined Discord. ||
| ``user id [user]`` | Retrieve a user's public identifier. ||
| ``user join-date [user]`` | Retrieve the timestamp at which a user joined this guild. ||
| ``valorant <username>`` | Check a player's average VALORANT statistics. ||