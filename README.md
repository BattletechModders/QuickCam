# QuickCam - Shorter camera delays for HBS BATTLETECH
### Works in 1.9.1 without any update, with or without ModTek
This mod changes the camera delays found in the CombatGameConstants.json and AudioConstants.json.  This is intended for experienced players that don't want the longer pauses for status updates.  These settings are seperate from the stock "speed up gameplay" options and will work with or without the speedup setting enabled.  With BATTLETECH 1.5, many of the changes QuickCam made are now stock.  I've updated this mod's variables to remove those that are same as stock.  Most stock values that remain to be changed, are now only off a about half a second or less.

When used with ModTek, QuickCam shouldn't cause any errors with save files, even saves in combat, or with version changes. I've done extensive testing back and forth between stock and modded play without any errors. It does not add any new items to the VersionManifest.csv.  Of course, when used with the HBS Mod Loader, any save that has this mod enabled will need it going forward as normal.

#### 1.5 A/B Video https://youtu.be/FSuSgwByn30
Old pre-1.5 comparison video here: https://youtu.be/pmEC6UIdYws

### Instructions:

    Copy QuickCam folder in to Mods folder created for ModTek or in the HBS Mods folder.
    
### ModTek
This mod can use either HBS Mod Manager or ModTek:

https://github.com/BattletechModders/ModTek/releases

## Stock File Edits:
StreamingAssets\data\constants

    CombatGameConstants.json
        "CameraConstants":
    
            "ShowAttackCamTime" : 1.8, *From 3.0*
            "CamDelayLocationDestroyed" : 2.0, *From 2.5*
            "CamDelayPilotInjured" : 2.0, *From 2.25*

    AudioConstants.json
        "AttackAfterCompletionDuration" : 0.0 *From 0.5*
