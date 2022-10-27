+++
title = "Ukozi Static"
date = 2022-10-25T00:46:40-04:00
description = "An AI Powered AV Bot for Discord"
facets = ["security"]
tags = ["nexus", "SentinelOne", "Discord"]
categories = ["tools"]
+++

Ukozi Static is a Discord bot that scans attachments to messages using SentinelOne's Static AI engine to determine if they pose any threat. The bot then posts the outcome. In the case of "suspicious" detections, the bot will also poll VirusTotal to assist in making any decision around removing messages (or users) that are posting files. While Discord offers some malicious file detection natively, it's pretty minimal and although it automatically removes files it deems to be malicious, the bot has (so far) been able to scan and post results faster than Discord can remove the file. I've also implemented some quality of life messages around things like encrypted archives and feedback on the types of files that won't be scanned.

{{<button https://discord.com/api/oauth2/authorize?client_id=992267176524382209&permissions=536890368&scope=bot addbot>}}