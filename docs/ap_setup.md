# KH1 + KH2 Multiworld

Setups for KH1 + KH2 AP.

---

Follow setup for individual games first. 

**KH1:** https://www.kh1fmrando.com/software_setup.html

**KH2:** https://tommadness.github.io/KH2Randomizer/setup/Archipelago/

## Generating a KH1 + KH2 Multiworld Seed

### KH1 YAML

1. Generate a yaml here: https://www.kh1fmrando.com/generate_a_seed.html
	1. Under "Misc", set slot name (player name) to your desired player name
2. Press "Generate Settings File" to save the YAML
3. In your archipelago folder, open the /Players/ folder
4. Place YAML file in the folder

### KH2 YAML

1. Generate a yaml here: https://archipelago.gg/games/Kingdom%20Hearts%202/player-options
	1. Set "Player Name" to your desired player name
2. Press "Export Options" to save the YAML
3. In your archipelago folder, open the /Players/ folder
4. Place YAML file in the folder

### KH 1+2 Setup

1. Go to /Players/ folder in your archipelago folder
	1. Make sure both YAML files are in the folder with the names and settings you want
2. Run ArchipelagoGenerate.exe
3. Take the AP_XXX.zip file the exe created in the /output/ folder and upload it: [https://archipelago.gg/uploads](https://archipelago.gg/uploads)
4. Press "Create a room". You should see KH1 and KH2 players in the room. 
5. Download the file from "Download Patch File..." for both games

#### KH1

1. Open the KH1 Randomizer Mod Generator
2. Point to the zip file created from the room for "AP Zip File Output"
	1. Make sure KH1 Data Path is pointing to your kh1 data folder from OpenKH
3. Click "Start"
4. A mod_XXX.zip file will appear in /Output/
5. Install this into the mod manager

#### KH2

1. Take the AP_XXX.zip file created from the room and install it into the mod manager
	1. Seed (AP_XXX.zip)
	2. AP companion QoL (optional)
	3. AP companion
	4. AutoSave/Soft Reset (these can be replaced with Archipelago Enablers instead)
	5. Lua Library
	6. GoA ROM Edition

#### Launching

1. Open ArchipelagoLauncher.exe
2. Open KH1 and KH2 Clients
3. Connect to server hosted on archipelago.gg
	1. The server/port number can be found in the room page
	2. KH2 needs to be open and on title screen to connect
		1. If playing solo, you can wait to connect KH2's client until you actually start playing it. Then when you go back to KH1, disconnect.
4. Enter the slot name associated with your slot
5. Play!
