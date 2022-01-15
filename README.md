# CS:GO Discord Rich Presence  
![GitHub release (latest SemVer)](https://img.shields.io/github/v/release/Retr0-01/CSGO-Discord-RP?sort=semver)
![GitHub release (latest by SemVer)](https://img.shields.io/github/downloads/Retr0-01/CSGO-Discord-RP/latest/total?sort=semver)  
A Rich Presence application for showing custom status of your active Counter-Strike:Global Offensive game.

- [CS:GO Discord Rich Presence](#csgo-discord-rich-presence)
	- [How It Works](#how-it-works)
	- [Install](#install)
	- [Credits](#credits)
	- [Licensing](#licensing)

## How It Works
This application uses the [Counter-Strike: Global Offensive Game State Integration](https://developer.valvesoftware.com/wiki/Counter-Strike:_Global_Offensive_Game_State_Integration) to fetch the data of your active game. It creates a local server (port 3000) which listens for the data and then applies it to your Discord client.

## Install
Go to the [latest release](https://github.com/Retr0-01/CSGO-Discord-RP/releases), download the ``CSGO-Discord-RP.zip`` file from the Assets section and then extract it to the location of your choosing. Now you should have the folder containing the application and a file called ``gamestate_integration_discord-rp.cfg``.  
Cut the cfg file and paste it inside the "cfg" folder of your CS:GO installation.  
For example ``C:\Program Files (x86)\Steam\steamapps\common\Counter-Strike Global Offensive\csgo\cfg`` is where I will have to put it.  
Once you have done that just open the folder containing the application and run the exe file.

## Credits
Huge thanks to the following devs/teams for creating some of the packages/tools used.  
- [Newtonsoft](https://www.newtonsoft.com/json) for Json.NET
- [Lachee](https://github.com/Lachee/discord-rpc-csharp) for the C# implementation of the Discord RPC
- [quicktype](https://quicktype.io/csharp) for instantly generating the needed C# models in order to use the JSON data

## Licensing  
This repository is licensed under the MIT Licence. [Learn more.](https://github.com/Retr0-01/CSGO-Discord-RP/blob/main/LICENCE.md)