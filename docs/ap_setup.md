# KH1 + KH2 Multiworld

Setups for KH1 + KH2 AP.

---

Follow setup for individual games first.

**KH1:** https://www.kh1fmrando.com/software_setup.html including https://www.kh1fmrando.com/multiworld_guide

**KH2:** https://tommadness.github.io/KH2Randomizer/setup/Archipelago/

## Generating a KH1 + KH2 Multiworld Seed

### KH1 YAML

1. Generate a yaml here: https://www.kh1fmrando.com/generate_a_seed.html
   1. Under "Misc", set slot name (player name) to your desired player name
2. On the "Finish" tab, press "Save Settings" to save the YAML
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

1. Take the PX_SlotName_XXX.zip file created from the room and install it into the mod manager
   1. KH1 Randomizer Seed XXX (PX_SlotName_XXX.zip)
   2. KH1 Randomizer Core
   3. KH1 Lua Library

#### KH2

1. Take the PX_SlotName_XXX.zip file created from the room and install it into the mod manager
   1. Archipelago Seed - KH2 (PX_SlotName_XXX.zip)
   2. AP companion QoL (optional)
   3. AP companion
   4. **EITHER** ArchipelagoEnablers **OR** equations AutoSave and Soft Reset and ArchipelagoEnablersLITE
   5. Lua Library **IF** using equations Autosave and Soft Reset
   6. GoA ROM Edition

#### Launching

1. Start KH1 and press F4 to open the KH1 Client
2. Open ArchipelagoLauncher.exe and open the KH2 Client
3. Connect to server hosted on archipelago.gg
   1. The server/port number can be found in the room page
   2. KH1 needs to be connected by pressing F4 and entering the host, archipelago.gg:XXXXX, and slot name
   3. KH2 needs to be open and on title screen to connect
4. Enter the slot name associated with your game into the clients
5. Play!

## Helpful stuff

- [Pop Tracker](https://github.com/black-sliver/PopTracker/releases)
- [KH1 Pop Tracker](https://github.com/culk/Kingdom-Hearts-FM-AP-Tracker/releases/latest/)
- [KH1 Locations Guide](https://www.kh1fmrando.com/locations_guide)
- [KH2 Pop Tracker](https://github.com/palex00/kh2-ap-tracker/releases/latest/)
- [KH2 Logic Sheet](https://docs.google.com/spreadsheets/d/1nNi8ohEs1fv-sDQQRaP45o6NoRcMlLJsGckBonweDMY/edit?usp=sharing)
