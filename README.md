# What is discord-v11 repo?
It's an repo that i installed discord.js v11 and did some changes to fix Stage Channels.
### What does it includes:
It includes (**FFMPEG**) so, If you are the one who made an music bot with the old discord version, you don't need to make any fixes.
### How can i use it:
Just fork/clone it then type **npm init** and do your work.
### Where to use it?
You can put it in the Heroku Buildpath, Because the problems with channel staging with Discord.js V11.
I made this because sadly, you can't change the heroku app modules! Because it generates auto when deploying!
You can use discord.js-v11 in Heroku by changing the build pass!
### Before adding discord-v11 to it!
You need to remove **heroku/nodejs** or it won't work!
### After removeing **heruko/nodejs**
Now click add buildpack and add link -> *https://github.com/D7M51/discord-v11/tree/main* 
Then save changes, and restart all dynos!
### Then what?
Kaboom! your heruko runs with discordjs-v11 and no channel staging problems!


#### Tip: Don't use **index.js** ❌ use **main.js** ✅
