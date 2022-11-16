to setup:

in .env file, set token=

the paste the token that was generated for you when you created your discord bot application through discord.

in the handleCommands.js file, input the clientId as the ID you obtain by right-clicking your bot user in the server.
in the guildId, input the guildId you obtain by right clicking your discord server.

in checkVideo.js, you'll input your unique youtube channel id link,  discord server
 id, the channel id to post videos, the url for your youtube channel icon, 
 and the url link to your youtube channel.

video.json updates to show your most recent video, and each time the bot finds that your last video does not match the one
in video.json, it will post the new video and update the video.json.