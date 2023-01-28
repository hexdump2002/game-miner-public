<p align="center">
<img src="/site_images/logo.png?" alt="Game miner logo">
</p>
<br/><br/>

# What is Game Miner?
Game Miner is a set of tools that aliviates the burden of managing and adding non steam games to the steam client. It manages a list of given folders that from now on we will call "The user game library" holding non steam games or any other type of external application that the user wants to add and launch from the steam client.

On the other hand, Game Miner provides the needed tools to manage non steam application data like compatdata and shaderdata folders that are not deleted when the game/application is removed from the steam client.

Game Miner was created with the steam deck in mind but should work on any linux distribution. If there is enough interest a windows version could be released in the future.

# Key Game Miner functionalities?
- Slick user interface.
- Support for multiple steam user accounts
- Per user game library and configuration settings
- Add non steam games in seconds instead of minutes and export their configuration for later use
- Discover steam shortcut problems like broken links or missing compatibility tools instantly
- Share your application or games with other game miner users to use them with 0 configuration. Just add them to the library and save ;)
- Manage shadercache and compatdata folders in batch or individually
- No more unknown shadercache or compatdata origins. If you use Game miner to add all your non steam games, it will keep track of all games you installed and its data. You won't ever again loose track of any game data.
- And much more...


# How does Game Miner looks like?

Game miner has different tools aimed to very specific tasks. Right now it has a Game Manager, a Game Data Manager and a summary tool. The sumary tool is not yet ready for release but will be dropped shortly. 

![Game Manager](/site_images/game_manager.png?raw=true "Game manager")
![Game Data Manager](/site_images/game_data_manager.png?raw=true "Game data manager")
![Settings](/site_images/settings.png?raw=true "Settings")
![User Change](/site_images/change_user.png?raw=true "User change")

# Game Miner tools


### Game Manager and Navigation tools

Use the Game Manager tool to add, remove and edit the games you want to see in your steam library.

The game manager tool also provides an overview of each game status (represented by colored squares), storage stats and also provides diffent actions to apply on the physical folder that holds the game like deleting or renaming.

Game Miner supports multi user so, if more than one steam account is used in your device, you will be able to switch among them clicking on the avatar picture. Settings and configurations are saved by user to avoid configuration clashing.

![Game Manager](/site_images/navigation_and_game_manager_explanation.png?raw=true "Game manager")

Every row in the game manager represents a folder in your game library. They can be expadnded and will show differnt executables that can be added to steam. Try to name each executable with a meaningful name if you want to easily find them when you come back to steam. If a default proton is selected in settings, it will be assigned as soon as the executable is added.

![Game Manager](/site_images/game_manager_expanded_explanation.png?raw=true "Game manager")


### Data Manager tool

The data manager tool is where you manage all the data that your steam and non steam games store in your hard drive. You can delete game data in batches or one by one.

This tool will also show a high level view of how much storage is taken by each game and by cache size and compat tool types. This way, you will be able to track how big your game data is.

![Data Manager](/site_images/data_manager_explanation.png?raw=true "Data manager")


### Settings

All your seetings are managed in this screen. Settings take place when saved so, remember to save after you have modified them.

![Settings](/site_images/settings_explanation.png?raw=true "Settings")

### Issues and Limitations

Steam client when closed writes a bunch of configuration files to disk. It doesn't matter if the configurations have been modified or not and this leads to changes being lost if you use game miner while Steam is open. So, when game miner is launched it closes the steam client automatically to avoid any data loss. But, this brings another problem, when steam client is not active, virtual keyboard won't appear so you won't be able to use all game miner functionalities. Mainly renaming, searches, etc. There are some options to avoid these caveats:

1) Install a virtual keyboard like Core Keyboard that is always active.
2) Open steam client, then open game miner and o all the changes you need and before saving your changes exit steam. Now you are able to save without any data loss and leveraging the steam keyboard.
3) Use a bluetooh keyboard.
4) Use anydesk that can be installed through discover and use your deck from the comfort of your computer.


Game miner has been developed by Hexdump 2023

Follow me on [Twiter](https://www.twitter.com/_HexDump_)
