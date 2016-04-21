﻿# Extendable Discord Bot
####An extendable bot for your Discord Server

[![NPM](https://nodei.co/npm/extendable-discord-bot.png?downloads=true&downloadRank=true&stars=true)](https://nodei.co/npm/extendable-discord-bot/) 

[![Join the chat at https://gitter.im/Wolvan/ExtendableDiscordBot](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/Wolvan/ExtendableDiscordBot?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge) [![npm version](https://badge.fury.io/js/extendable-discord-bot.svg)](https://badge.fury.io/js/extendable-discord-bot)

## Introduction
This is an extendable bot for Discord chats. By itself it does nothing, that's where Plugins come in handy. Drop plugin files into the `/plugins` directory, load them from the bot console (or by restarting completely) and enjoy it's functionality.

## Features
* Lightweight: Being a NodeJS app makes it easily deployable everywhere! Even on low power servers
* Console commands allow you to administrate the bot easily
* Plugin API: The bot doesn't really do anything by itself, you install Plugins for functionality. The following plugins come pre-installed:
	* `roll_dice.dbot.js` A dice rolling script that allows to roll any number of dice
	* `message_output.dbot.js` Print messages from chat to your output
	* `request_q.dbot.js` A queue plugin for requests or commissions

## Install the bot
### from npm (globally)
1. Install NodeJS with npm
2. Use `npm install -g extendable-discord-bot` from a command prompt or terminal
3. Install Plugins
4. Run it with `discord-bot [-e|-p|-t|--help]`
5. Use the `help` command for a list of commands when the bot is running

### from GitHub (locally)
1. Install NodeJS with npm
2. Clone this repository or download the source as .zip file
3. Open a command prompt or terminal and navigate to the folder you cloned the repository to
4. Run `npm install` from a command prompt or terminal
5. Install Plugins
6. Run the bot with `node app.js [-e|-p|-t|--help]`
7. Use the `help` command for a list of commands when the bot is running

## Install plugins
Plugin installation is easy! Download the file with the extension `.dbot.js` and put it in the `/plugins` directory of the bot. Load it by typing `plugins enable <filename>` or by restarting the bot.

##For Developers
Want to write your own Plugin for the bot? That's great!
Easiest is to check existing plugins on how they are written, but you can also check the Wiki of this repository, it should give all the information you should need. I'll also provide a plugin template which you can use.
Make sure that your plugin has the file extension `.dbot.js`.
Plugin Pull Requests are welcome of course.

Wanna work on the bot itself? Go ahead and fork the repository, make your changes and open a Pull Request back into here!

Got any other questions? [Join the Gitter Channel of the bot](https://gitter.im/Wolvan/ExtendableDiscordBot), I should be available there most of the time.
