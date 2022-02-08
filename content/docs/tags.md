---
author: "Cooper Sullivan"
title: "Channel Tags"
date: "2022-02-06"
description: "All about Guardian's channel tags."
tags: ["features", "live"]
categories: ["documentation"]
ShowToc: false
ShowBreadCrumbs: false
draft: false
---

![](https://i.imgur.com/fqTptsr.png#center)

## "I have no idea what that is."
In short, channel tags are bits of info added to the channel topic of certain text channels that change the way
Guardian interacts with these channels. Usually channel topics look like the following:

- Name: **#chat-nsfw**
- Topic: ```This channel is unmonitored; feel free to send NSFW content here.```

Let's say, for example, we want the **#chat-nsfw** channel to be completely unmonitored by Guardian- this means
that Guardian won't check it with it's automatic scam-protection or profanity protection moderation. If this was
the case, we'd add the ``[NOT-FILTERED]`` channel tag to the text channel's topic.

- Name: **#chat-nsfw**
- Topic: ```This channel is unmonitored; feel free to send NSFW content here. [NOT-FILTERED]```

Guardian will now completely ignore this channel with it's automatic moderation features. This will continue so long
as the channel's topic contains the channel tag. If the channel tag is removed, Guardian will continue monitoring it.

> Note that channel tags are not case sensitive, meaning that capitilzation is not important in the usage of channel tags.

> Note that channel tags will only affect the channel from the point of addition, meaning that if a channel containing messages
is later marked as a temporary channel with ``[TEMPORARY]``, only new messages sent after the tags addition will be considered temporary messages.

## All channel tags
| Tag | Description | Maximum |
| :- | :-: | -: |
| ``[LOGS]`` | Guaridan's audit-logging channel; all of Guardian's automatic logs and alerts will be sent here. | 1 channel / guild |
| ``[NOT-FILTERED]`` | This channel will be removed from Guardian's automatic moderation (profanity and scam removal). ||
| ``[TEMPORARY-10m]`` | All messages in the channel will be deleted after ten (10) minutes. ||
| ``[TEMPORARY-1d]`` | All messages in the channel will be deleted after one (1) day. ||
| ``[TEMPORARY-1h]`` | All messages in the channel will be deleted after one (1) hour. ||
| ``[TEMPORARY-1m]`` | All messages in the channel will be deleted after one (1) minute. ||
| ``[TEMPORARY-1w]`` | All messages in the channel will be deleted after one (1) week. ||
| ``[TEMPORARY-5m]`` | All messages in the channel will be deleted after five (5) minutes. ||
| ``[TEMPORARY]`` or ``[TEMPORARY-15s]`` | All messages in the channel will be deleted after fifteen (15) seconds. ||