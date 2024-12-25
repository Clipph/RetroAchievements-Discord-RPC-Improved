# RetroAchievements-Discord-Presence-Improved

This is a simple that allows RetroAchievements rich presence to be tracked on discord's rich presence.

## Instructions

1. Install Python. _(It works currently at version 3.13.1)_
2. Run `cmd` and ensure that python is installed correctly by entering this command `py --version`.
3. Run the command, `py -m pip install -r requirements.txt`. Make sure that you're running this command in this directory.
4. Go to Discord > User Settings > Activity Privacy. Toggle on `Share your detected activity with others.`
5. Run the `run.bat` file, enter your credentials, `username` and `api key` from RetroAchievements.

After running the `run.bat` file, a `config.ini` file will be created in the same directory. The credentials that you've submitted are stored in this config file.

### Optional
- Discord Application (https://discord.com/developers/applications/) [For the Discord Application ID]

<hr>

## Features:
- The game icon is displayed on the Discord's RP.
- The console currently being played is also displayed. 
- Hovering over the game icon displays the user's achievement status about the current game. _(e.g, 32 of 148 achieved | 21 %)_
- A first button that redirects to the user's RA profile. _(Don't worry, I made an option to turn this off)_
- If the username display is turned off, the first button will have the link of the RetroAchievements website instead.
- A second button that redirects to the current game info inside the RetroAchievements website. 
- Not having updates within the current game status for a certain period of time would lead to RP idling. This helps to prevent unintended up-counting of elapsed time. _(Not fully functional yet)_
- Making movements that triggers the game status would display the Discord RP again. _(Not fully functional yet)_
- Optimized game title.
- Optimized game status. 

### How to turn off username display?
1. If ever you don't want your username to have a redirection button on your Discord RP, just edit the `config.ini` file and modify the value inside the `displayUsername` to `False`. By default, this is `True`. _Notice the capital letters in the True and False as wrong cases may result to an error._
2. After this, you can just close the `run.bat` file and open it again to reflect changes. 
