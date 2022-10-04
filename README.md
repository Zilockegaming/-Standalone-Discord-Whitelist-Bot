*Say hi to DiscordWhitelist, the number 1 whitelist resource for FiveM!*

Hate updating those ACE Permission white-lists? Well just use Discord! DiscordWhitelist allows you to use a dynamic whitelist system based off of Discord roles. Simply change the configuration to best fit your community! So keep white-lists easy and breezy. Oh, also, we forgot to mention there's also a blacklisted roles system, just incase you prefer to blacklist users.

**Documentation:**
As of version 3.0 of DiscordWhitelist it no longer uses any other script as a required dependency. It is now standalone and works by itself. Server owners/"developers" appeared to have much trouble installing the script. So now its a drag 'n drop!

Creating an Application 
To operate DiscordWhitelist we need to have a Discord bot application in our guild. This bot doesn't need to be online, just in the guild.

Create a new application from the Discord Developer Portal.
Click on 'Bot' on the left navigation bar and enable the bot. Then copy the Bot Token and have ready for the below.
Now in the 'General Information' tab copy the 'Client ID' and replace CLIENT_ID_HERE in the below template.
https://discord.com/oauth2/authorize?client_id=CLIENT_ID_HERE&scope=bot&permissions=8
Now invite your bot to your guild.

Installing DiscordWhitelist 
Now it's time to install the script itself. First off...

Download and extract Discord Whitelist into your resources folder.
Open the server.js file in the resource and edit to include the settings you want reflected.
Add ensure DiscordWhitelist into your server.cfg.


