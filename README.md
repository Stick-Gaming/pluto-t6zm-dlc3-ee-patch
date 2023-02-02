# Stick Gaming Pluto Buried Easter Egg Quality of Life improvement
This script makes the Easter Egg achievable with any amount of players in the game session while keeping the original design of each step the same but allowing any player to complete it.


# Features
-	**Buired Easter Egg QOL V1.0**
	- **Maze Step**
        - With less than 4 players when the last switch has been pulled. The game will notify players if a switch is in the correct position.
	- **Timebomb Step**
        - Require all players in the lobby to be near the location of the timebomb.
    - **Shooting Gallery Step**
        - Depending on how many players are in the lobby when interacting with the fountain outside of the courthouse will decide how many targets will be needed to be shot to complete the step.
        - If there are 4 or more players - All targets will need to be shot (just like vanilla)
        - If there are 3 players in the lobby - 61 targets will need to be shot (Saloon + outside the candy store + Myster box area (big guy area 22))
        - If there are 2 players in the lobby - 39 targets will need to be shot (Saloon + outside the candy store (20))
        - If there is 1 player in the lobby - 19 targets will need to be shot (Saloon has 19 targets)
        - _Note: you can make the game tell the player how many targets are left to hit if you uncomment line 117 and recompile the script._

## Requirements
- Have a copy of Black ops 2 with all DLC.
- Have the latest version of Project [Plutonium](https://plutonium.pw/)
- Have a copy of the complier from [Plutonium forum](https://plutonium.pw/docs/modding/loading-mods/#t6), in the GSC Example Toolkit

## Installation
- Compile the script or for a pre-compile go look in our [release](https://github.com/Stick-Gaming/pluto-t6zm-dlc3-ee-patch/releases) 

- Copy the compile files to your `AppData/Local/Plutonium/storage/t6/scripts/zm/zm_buried` folder _(if you don't have a "zm_buried" folder then create one)_

- Once copy you will need to rename each script to remove -complied from there name

- Start your server or custom game


## Contributors
-	[Nathan3197](https://twitter.com/nathan3197) - Owner/developer
-   The hundreds of people who tested this on our servers
