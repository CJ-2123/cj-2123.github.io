# KH1 + KH2 Multiworld

Setups for KH1 + KH2 AP and individual games AP.

---

## Generating a KH1 + KH2 Multiworld Seed

Follow intital setup guides for each game before following this guide.

**KH1: https://github.com/gaithernOrg/KH1FM-AP/releases**

- Follow through step 8. This guide picks up at step 9.

**KH2: https://archipelago.gg/tutorial/Kingdom%20Hearts%202/setup/en**

- Follow at least the "Required Software" section.

### KH1 YAML

1. Run ArchipelagoLauncher.exe
2. Click "Generate Template Settings". This will open file explorer
3. Find "Kingdom Hearts.yaml" and copy it to /Players/ (create this folder if it does not exist)
4. Open the YAML file and change the line that says "name: Player{number}" to your desired player name
5. Adjust the settings in the YAML to your liking
6. Save the YAML

### KH2 YAML

1. Go to https://archipelago.gg/games/Kingdom%20Hearts%202/player-options
2. Set "Player Name" to your desired player name
3. Adjust the settings to your liking
4. Press "Export Options" and save the YAML
5. You can save it to the /Players/ folder or copy it to there

### KH 1+2 Setup

1. Go to /Players/ folder
   1. Make sure both YAML files are in the folder with the names and settings you want
2. Run ArchipelagoGenerate.exe
3. Take the AP_XXX.zip file the exe created in the /output/ folder and upload it: https://archipelago.gg/uploads
4. Create a room, you should see KH1 and KH2 players
5. For KH2, click "Download Kingdom Hearts 2 Mod..." to get an AP_XXX.zip folder to load into the mod manager
6. Install KH2's seed into mod manager
   1. Seed
   2. AP companion QoL
   3. AP companion
   4. Auto Save
   5. GoA ROM Edition
7. Open ArchipelagoLauncher.exe
8. Open KH1 and KH2 Clients
9. Connect to server hosted on archipelago.gg
   1. KH2 needs to be open and on title screen to connect
      1. If playing solo, you can wait to connect KH2's client until you actually start playing it. Then when you go back to KH1, disconnect.
10. Play!

---

## KH1 Setup

1. Run ArchipelagoLauncher.exe
2. Click "Generate Template Settings". This will open file explorer
3. Find "Kingdom Hearts.yaml" and copy it to /Players/ (create this folder if it does not exist)
4. Open the YAML file and change the line that says "name: Player{number}" to your desired player name
5. Adjust the settings in the YAML to your liking
6. Run ArchipelagoGenerate.exe
7. Take the newly created AP_XXX.zip file in /output/ in upload it here: [https://archipelago.gg/uploads](https://archipelago.gg/uploads)
8. Open ArchipelagoLauncher.exe
9. Click "KH1 Client" and connect to your server hosted on archipelago.gg
10. Play!

## KH2 Setup

1. Download seed zip and install into Mod Manager
2. Seed should be highest priority
   1. Seed
   2. AP companion QOL
   3. AP Companion
   4. Auto Save
   5. GoA ROM Edition
3. Start game go to title screen
4. Run ArchipelagoKH2Client.exe
5. Connect to your server hosted on archipelago.gg
6. Play!
