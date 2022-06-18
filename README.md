# READ EULA PRIOR TO USE

### Step 1
Download the latest version of [NodeJS](https://nodejs.org/) and follow the install instructions. 
![](https://imgur.com/Y6SmfJ7.png)

### Step 2
Navigate to the file path the bot is saved in using command prompt and the ``cd [FILEPATH]`` command.

![](https://imgur.com/fAYilsw.png)

### Step 3
Open ``config.json`` in a text editor of your choice.

### Step 4
In Discord, go to Settings, then Advanced, and once there, enable "Developer Mode".
![](https://imgur.com/kjyxzcG.png)

### Step 5
Navigate to the server you would like to add the Discord bot to (you MUST be an administrator of said server), right click, and click "Copy ID"

![](https://imgur.com/Ojqq7Tl.png)

### Step 6
In ``config.json``, copy the ID into the quotes by "guildId"

![](https://imgur.com/PfYmtkJ.png)

### Step 7
Visit the [Discord Developers Site](https://discord.com/developers/applications), then click "New Application" and name it whatever you would like.
![](https://imgur.com/TFAGowF.png)

### Step 8
Once made, copy the "Application ID" and paste it into the quotes by "cclientId" in ``config.json``.

![](https://imgur.com/cTpUPvq.png)

![](https://imgur.com/u8W2q7P.png)

### Step 9
Go into the bot tab, and create your bot. Here you will be able to change the profile picture and name of your bot.
![](https://imgur.com/UHxI7ns.png)
![](https://imgur.com/5Epehq9.png)

### Step 10
Press "Reset Token" then copy the token into the space by "token" in ``config.json``. **DO NOT SHOW ANYONE YOUR TOKEN.**

![](https://imgur.com/N97somL.png)
![](https://imgur.com/2sFAXuC.png)

### Step 11
Go into the OAuth2 tab, then URL Generator tab. Once there, check the boxes for "bot" and "applications.commands". In the new dialogue box below, check "Administrator"

![](https://imgur.com/OyMZ78q.png)

![](https://imgur.com/WBnLmGo.png)

### Step 12
Copy the URL into your search engine, then add the bot to the server of your choice.
![](https://imgur.com/J99Osot.png)
![](https://imgur.com/BJpX4xU.png)

### Step 13
Finally, type ``node odeploy-commands.js`` in the command prompt. Whenever you would like to make the bot run, type ``node oindex.js`` in command prompt. You MUST keep the command prompt window open for the bot to run.
![](https://imgur.com/bQIF0gW.png)
