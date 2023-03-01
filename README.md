<p align="center">
<img src="/site_images/logo.png?" alt="Game miner logo">
</p>
<br/><br/>

# What is Game Miner?
Game Miner is a set of tools that aliviates the burden of managing and adding non steam games to the steam client. It manages a list of given folders that from now on we will call "The user game library" (UGL) holding non steam games or any other type of external application that the user wants to add and launch from the steam client.

On the other hand, Game Miner provides the needed tools to manage non steam application data like compatdata, haderdata and artwork folders that are not deleted when the game/application is removed from the steam client.

Game Miner was created with the steam deck in mind but should work on any linux distribution. If there is enough interest a windows version could be released in the future.

# Who is behind Game Miner?
Game Miner has been developed by me, Hexdump. You can follow me on [Twitter](https://www.twitter.com/_HexDump_) if you want to get news about Game Miner or you are interested in development in general or game development in particular.

# Community
If you want to get in contact with other Game Miner users and share your suggestions, doubts or opinions you can make your way into the official Telegram channel: https://t.me/+5XEVcUO8QKk5MWRk. Main language is spanish but we welcome any other users that speak english.

# Are there any tutorials about how to use Game Miner?
Yes, it is in spanish but has subtitles for a lot of other languages and can be followed easily. The great TTconT did the tutorial and you can find it on youtube at https://youtu.be/66hIRhu2rD4 

# Key Game Miner functionalities?
- Slick user interface.
- Support for multiple steam user accounts
- Per user game library and configuration settings
- Add non steam games in seconds instead of minutes and export their configurations for later use (Artwork included)
- Discover steam shortcut problems like broken links or missing compatibility tools instantly
- Share your application or games with other game miner users to use them with 0 configuration. Just add them to the library and save ;)
- Manage your games in bulk of any size with the multi selection mode
- Select the way you want your games list view. From full banner images to the most simplistic icon list.
- Manage shadercache and compatdata folders in batch or individually
- No more unknown shadercache or compatdata origins. If you use Game miner to add all your non steam games, it will keep track of all games you installed and its data. You won't ever again loose track of any game data.
- Advanced filtering to find what you need in the blink of an eye
- Smart closing/opening of steam client to do not loose any data when saving.
- And much more...

# How do I install Game Miner?
Game Miner doesn't need to be installed. It is just a portable program that can be executed from any folder you like. So, the only thing you have to do is download the latest release, make it executable and run it. Done!

To make the app image executable you can ussually right click the appimage file and in file properties under permissions there should be a switch or checkbox to make it executable. A second option is to open a terminal window and type "chmod +x ./GameMiner.AppImage" in the folder where the AppImage was stored. This will make the AppImage executable too.

Here is a picture showing how Fedora presents this option, your Distribution shoud have something similar:

![Fedora](/site_images/fedora_set_as_executable.png?raw=true "Fedora")
<br/><br/>
__Warning__: Game Miner creates app icons when it runs for the first time. If you move the AppImage to another folder afterwards, you need to recreate the icons link. To do this just open the Game Miner settings page and click on "Remove app icons" and then "Add app icons". This will clean old icons and create new ones for the new location.
<br/><br/>
__Warning__: Game Miner needs the Steam client to be closed while running so you can't add it to game mode. However, I you only use the Cleaner tool you could use it without problem in game mode.

![Fedora](/site_images/add_remove_icons.png?raw=true "Fedora")

# How does Game Miner looks like?

Game miner has different tools aimed to very specific tasks. Right now it has a Game Manager and a Game Data Managerl. 

Game Manager
<br/>
![Game Manager](/site_images/game_manager.png?raw=true "Game manager")
<br/></br>
Game Data Manager
<br/>
![Game Data Manager](/site_images/game_data_manager.png?raw=true "Game data manager")
<br/></br>
Settings
<br/>
![Settings](/site_images/settings.png?raw=true "Settings")
<br/></br>
Change user Screen
<br/>
![User Change](/site_images/change_user.png?raw=true "User change")

# Game Miner tools


### Game Manager and Navigation tools

Use the Game Manager tool to add, remove and edit the games you want to show in your steam library. You can even export working configurations to be shared with friends or just to have a healthy non steam game library stored wherever you want ready to be just imported and played.

The game manager tool also provides an overview of each game status (represented by colored squares) and differnt game stats.

You can apply different actions to just a game (Through the contextual menu hidden in the little 3 dots icon on the right of each game entry) or to a set of them. These two modes are called single mode and multi selection mode. You can switch between them through the multi selection switch in the top bar.

Game Miner supports multi user so, if more than one steam account is used in your device, you will be able to switch among them by clicking on the avatar picture. Settings and configurations are saved by user to avoid configuration clashing.

Game Miner in Single Mode
<br/>
![Game Manager](/site_images/navigation_and_game_manager_explanation.png?raw=true "Game manager Single Mode")
<br/><br/>
Game Miner in Multi Selection Mode
![Game Manager](/site_images/game_manager_multiselection.png?raw=true "Game manager Single Mode")
<br/><br/>
Every row in the game manager represents a folder in your game library or an external executable (blue squared color). They can be expanded and will show different executables that can be added to steam. Try to name each executable with a meaningful name if you want to easily find them when you come back to steam. If a default compat tool is selected in settings, it will be assigned as soon as the executable is added.
<br/>
![Game Manager](/site_images/game_manager_expanded_explanation.png?raw=true "Game manager")

### Data Manager tool

The data manager tool is where you manage all the data that your steam and non steam games store in your hard drive. You can delete game data in batches or one by one.

This tool will also show a high level view of how much storage is taken by each game and by cache size and compat tool types. This way, you will be able to track how big your game data is.

![Data Manager](/site_images/game_data_manager_explanation.png?raw=true "Data manager")


### Settings

All your seetings are managed in this screen. Settings take place when saved so, remember to save after you have modified them.

![Settings](/site_images/settings_explanation.png?raw=true "Settings")

Options are splitted in different sectios for easy finding.

In the Search path section you have to add all the paths containing your non steam games. All the games found in these paths will become your UGL.

In he Game Manager section you will find some options related to the Game Manager. You can define here the default view for it and different processing options when a game is added in the game manager. As an example you can remove the extension from the game name or make it lower case or upper case. It saves a ton of time when editing game names.

In the General options section you will be able to define the default compat tool to be added when an executable is added and how many backup files you want. Game miner backups important files when saving to make sure nothing is lost. We recommend to set it to the max.

The desktop App Icon Options section is provided for you to add or remove the app icons shortcuts. When game miner boots for the first time it will create the needed app icons (To make it visible in the tool bar, etc.). If Game Miner AppImage is then moved these icons won't show because the link between the icons and the AppImage is lost. Remove and then add icons using these buttons to make them back.


### Issues and Limitations

Steam client when closed writes a bunch of configuration files to disk. It doesn't matter if the configurations have been modified or not and this leads to changes being lost if you use game miner while Steam is open. So, when game miner is launched it closes the steam client automatically to avoid any data loss. But, this brings another problem, when steam client is not active, virtual keyboard won't appear so you won't be able to use all game miner functionalities. Mainly renaming, searches, etc. There are some options to avoid these caveats:

1) Install a virtual keyboard like Core Keyboard that is always active.
2) Open steam client, then open game miner and o all the changes you need and before saving your changes exit steam. Now you are able to save without any data loss and leveraging the steam keyboard.
3) Use a bluetooh keyboard.
4) Use anydesk that can be installed through discover and use your deck from the comfort of your computer.

### Acknowledgements

- AlbertDream: His Steamdeck suffered the initial versions of Game Miner but survivied! Contributed with great suggestions and encouragements
- Excitecube: Testing is hard and boring. He did it pretty well since the beginning and detected a load of bugs and contributed with great suggestions
- FranjeGueje: Inmense help with all the AppImage packaging and also contributed with great suggestions
- RubenAntonor: Contributed with great suggestions and encouragements.


Game miner has been developed by Hexdump 2023

Follow me on [Twitter](https://www.twitter.com/_HexDump_)
