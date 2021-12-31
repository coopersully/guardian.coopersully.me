---
author: "Cooper Sullivan"
title: "About the bot"
date: "2021-06-05"
description: "All about Guardian's purpose, features, and design."
tags: []
categories: ["documentation"]
ShowToc: false
ShowBreadCrumbs: false
draft: false
---

## An Introduction
The starting goal of Guardian was simple: to create a bot that serves as an all-in-one solution.
I, in the beginning, attempted to create a Discord bot that offered a free alternative to the premium bot-army that many production-level servers require to achieve the amount of features they'd like.
Guardian has of-course evolved and changed over time, but it's goal still remains the same. The project is still in it's experimental phase, but the results look promising. :)

![](images/discord-profile.png#center)

## Using Guardian
The bot is currently public and free-to-use, but please remember that it's still in early alpha.
You may experience some downtime (on the bot's end) and Guardian may not always behave exactly the way it should. If that's alright with you and you'd like to partake in the alpha-testing process,
you can [invite Guardian to your own server by clicking here](https://discord.com/api/oauth2/authorize?client_id=885618073904767008&permissions=8&scope=bot).

## Personalization & hosting
If you'd like a much more customizable, server-specific version of Guardian, you can request a downloadable program
to be able to host your own bot. This is only utilized by a handful of users at the moment and is only available upon
request. If you are hosting your own iteration of guardian, the default config.yml is as follows:

### config.yml

```
# What prefix should the bot use for it's commands?
# i.e. "!play <song>" uses the prefix "!"
bot-prefix: "!"

# What is the bot token the application should run on?
# You can find this on your Discord developer portal
bot-token: <INSERT-TOKEN-HERE>

# How intense should the chat language filter be? Choose one of 4 options:
# "0" disables chat moderation entirely.
# "1" enables light chat moderation, filtering out slurs.
# "2" enables moderate chat moderation, filtering out expletives and slurs.
# "3" enables heavy chat moderation, filtering out all profane language.
filter-intensity: MEDIUM

# What channel ID's should the bot designate as temporary channels?
# All content sent in channels marked as temporary will be deleted
# after fifteen (15) seconds. This is perfect for bot-commands text
# channels etc. If you would like to stop any message(s) from decaying,
# you can pin them and they will not be deleted over time.
# Leave this blank if you do not want any temporary channels.
temporary-channels:
	- [INSERT-CHANNEL-ID-HERE]
	- [INSERT-CHANNEL-ID-HERE]
```