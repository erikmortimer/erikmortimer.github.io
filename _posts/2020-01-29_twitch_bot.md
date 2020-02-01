---
layout: post
title: Creating a Twitch Bot
categories: [Programming,Bot,Twitch,Python]
excerpt:  How I created my own twitch bot for my channel and how it helps me run my stream
---
I have always wanted to try this "live streaming" thing out for a while now. After a couple of tries over the years, I am now trying to stream consistently on the platform and have been for a couple weeks now. Since I am mainly going to be streaming my programming session and also talk tech, I needed to brainstorm personal projects for me to do on stream. And with that, I decided to create my own twitch bot for my twitch stream called "SnowForgeBot". This idea/inspiration came from a fellow twitch streamer in the Science & Technology catagory called [Adam13531](https://www.twitch.tv/adam13531). Besides being tremendous motivation to code in general, he has built himself a twitch bot with features such as setting bot responses to commands like !today which gives the viewer insight into what he is working on that day. Because of his phenomenal intraction with his chat, the bot acts as a helping hand or extension of his intraction with the viewers which overall helps retain and attract more to his channel. 

For this twitch bot, I am using a python library called `IRC` to help with all of the IRC message parsing (Here is a [link](https://github.com/twitchdev/chat-samples/tree/master/python) to an example bot written in python by TwitchDev). First, I implement some basic features such as giving out links to my social media accounts, invite link to the community discord server, and what my current stream schedule is just to name a few. After that, I started to add features were I could change the bots response from chat itself, sort of like `GET` or `SET` functions in a class. One of the command that uses this idea is `!today` and `!project`. By typing `!today set I am doing more bot development` for example, would change the response of the bot to now say `I am doing more boy development` whenever the !today command is called by a viewer. Something so trival and simple, is very powerful, giving the viewer the information they need to understand what is going on and to be engaged in the stream. Another way to accomplish this is to "at" someone in chat about the command, for example `!today foobar` with the response being `@foobar -> I am doing more bot development`.
![demo1](../images/snowforgebot_demo_1.gif "SnowForgeBot Demo 1")

Since I am still very new to this live streaming thing, I don't want to spend all my time making features that won't be useful for me. Instead, I plan on adding features as time goes on and my community grows as well. Some future features to add to this bot be adding a localize database and track when the last time a user was in the chat room, leaderboard for most interactive viewer in chat, and commands to change the RGB lights in my room (this idea might come sooner than later tbh). 


- Talk about the features that I want in the bot and the I wanted
- Why did I use Python over Javascript
- Might want to add a photo of the raspberry pi thats running the bot
