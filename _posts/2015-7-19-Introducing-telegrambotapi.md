---
layout: post
date: 2015-7-19
title: Introducing telegrambotapi
tags: Telegram Java
categories:
- Projects
---
Earlier today I published my first project on github: [**telegrambotapi**](https://github.com/errebenito/telegrambotapi). As its name implies, it's a Java implementation of the [**Telegram Bot API**](https://core.telegram.org/bots/api). It makes use of the Apache HTTP Components to make requests to the API endpoints and receive replies, and Google's GSon library to parse the related JSON.

Currently, [**telegrambotapi**](https://github.com/errebenito/telegrambotapi) supports all objects and methods exposed by the API at the time of writing. To make a bot using it all you need to do is extend the `AbstractBot` class and implement the `handleCommands(Update update)` method. Easy, isn't it?
