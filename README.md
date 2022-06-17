# Discord Bot Instructions

### Step 1
Download the latest version of [NodeJS](https://nodejs.org/) and follow the install instructions. 

### Step 2
Navigate to the file path the bot is saved in using command prompt and the ``cd [FILEPATH]`` command.

### Step 3
Open ``config.json`` in a text editor of your choice.

### Step 4
In Discord, go to Settings, then Advanced, and once there, enable "Developer Mode".

### Step 5
Navigate to the server you would like to add the Discord bot to (you MUST be an administrator of said server), right click, and click "Copy ID"

### Step 6
In ``config.json``, copy the ID into the quotes by "guildId"

### Step 7
Visit the [Discord Developers Site](https://discord.com/developers/applications), then click "New Application" and name it whatever you would like.

### Step 8
Once made, copy the "Application ID" and paste it into the quotes by "cclientId" in ``config.json``.

### Step 9
Go into the bot tab, and create your bot. Here you will be able to change the profile picture and name of your bot.

### Step 10
Press "Reset Token" then copy the token into the space by "token" in ``config.json``

### Step 11
Go into the OAuth2 tab, then URL Generator tab. Once there, check the boxes for "bot" and "applications.commands". In the new dialogue box below, check "Administrator"

### Step 12
Copy the URL into your search engine, then add the bot to the server of your choice.

### Step 13
Finally, type ``node odeploy-commands.js`` in the command prompt. Whenever you would like to make the bot run, type ``node oindex.js`` in command prompt. You MUST keep the command prompt window open for the bot to run.
