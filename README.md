# twitchbot

**Information:**  
Eazy customizable discord bot with a few ready functions.

Main files are bot.js, functions.js and util.js.  
Everything in the /functions/ folder are extra functions that can be added/removed at any time. Some of the functions can't function without another so be carefull if you remove something.

Bot currently is set to store user data only in mysql database. i'll see what i'm going to do in the future about that.  
Twitch recommends no more than 10 connections on one client.

**How the bot works:**  
Make sure you set the .env variables

To add a new channel to the client just simply make a new folder in the /channels/ folder and give it the name of the channel.  
On the startup the bot is going to generate .json config files in the chanel folders for each of the functions in the /functions/ folder. After that just edit the .json files to your liking.
Bot also generates a config.json file in the chanel folders where you have to set the chat prefix for commands and the channel owners ID.

Bot is currently working on my twitch channel: [ttv/tw1stybg](https://twitch.tv/tw1stybg)(unless i'm testing something new on it and it crashes :d).

Included functions:

**Go to function:**  
[accountagefunc](https://github.com/Tw1ster95/discordbot#accountagefunc)  
[blacklistfunc](https://github.com/Tw1ster95/discordbot#blacklistfunc)  
[checkstreamfunc](https://github.com/Tw1ster95/discordbot#checkstreamfunc)  
[counterfunc](https://github.com/Tw1ster95/discordbot#counterfunc)  
[followagefunc](https://github.com/Tw1ster95/discordbot#followagefunc)  
[giveawayfunc](https://github.com/Tw1ster95/discordbot#giveawayfunc)  
[hifunc](https://github.com/Tw1ster95/discordbot#hifunc)  
[logfunc](https://github.com/Tw1ster95/discordbot#logfunc)  
[mysqlfunc](https://github.com/Tw1ster95/discordbot#mysqlfunc)  
[pointgamesfunc](https://github.com/Tw1ster95/discordbot#pointgamesfunc)  
[pointsshopfunc](https://github.com/Tw1ster95/discordbot#pointsshopfunc)  
[pointssysfunc](https://github.com/Tw1ster95/discordbot#pointssysfunc)  
[simplecmdfunc](https://github.com/Tw1ster95/discordbot#simplecmdfunc)  
[timedmessagesfunc](https://github.com/Tw1ster95/discordbot#timedmessagesfunc)  
[viewersinfofunc](https://github.com/Tw1ster95/discordbot#viewersinfofunc)

**More info soon :)**
# twitchbot
