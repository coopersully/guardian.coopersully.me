---
author: "Cooper Sullivan"
title: "Audit Logs"
date: "2021-06-05"
description: "An overview of Guardian's audit-logging features."
tags: ["features", "live"]
categories: ["documentation"]
ShowToc: false
ShowBreadCrumbs: false
draft: false
---

![](https://i.imgur.com/qXwy1yk.png#center)

## Guardian vs. Discord Audit Logs
While Discord's native Audit Logs are a great way to keep a record of different happenings in your server,
they're pretty incomplete and lack detail. Each server's Audit Logs, however, are managed automatically by
Discord's basic moderation and cannot be modified, added to, or changed; this is why many popular bots such
as [MEE6](https://mee6.xyz/), [Dyno](https://dyno.gg/), and more create their own channels in which they log
events, etc. Guardian does the exact same thing.

## #guardian-logs
Guardian will automatically create its audit-logging channel as soon as it joins your server. Upon creation,
this channel is only accessible to the guild's owner and users with the ``Administrator`` permission. Guardian
will also introduce itself with a summary of the logs, a few helpful tips, and a link to this website.

![](https://i.imgur.com/Cek9pjd.png#center)

It's important to note that Guardian's log channel is created with the ``[LOGS]`` channel tag. Guardian
often scans channel topics for tags that can change it's behavior- the logs tag is no different. This tells
Guardian where to send the events it's been recording; if this tag is removed, Guardian will create a new
audit-logging channel because it could not find one with the proper tag. In addition to this, do not add this
tag into any other channels, as it may cause Guardian's automatic logging system to fail for your server until
the issue is resolved.

### What events are logged?
As mentioned earlier, Guardian's audit-logging differs greatly from Discord's own logs. Guardian will automatically
detect and take record of all events and changes listed below:
* A user joins the server
* A user leaves the server
* A user joins a voice channel
* A user leaves a voice channel
* A user mutes themselves
* A user unmutes themselves
* A user deafens themselves
* A user undeafens themselves
* A user is server muted
* A user is server-unmuted
* A user is server deafened
* A user is server-undeafened
* A user's nickname is updated
* A user's roles are added to
* A user's roles are removed from
* A user moves from one voice channel to another
* A user begins boosting the server with Discord Nitro
* A user stops boosting the server with Discord Nitro
* A user's boost renews for the server with Discord Nitro
* A user's message is deleted by Guardian's chat filter
* A user's message is deleted by Guardian's malicious-content filter