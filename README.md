# QuickCam - Shorter camera delays for HBS BATTLETECH
This ModTek mod changes the camera delays found in the CombatGameConstants.json and AudioConstants.json.  This is intended for experienced players that don't want the longer pauses for status updates.  With BATTLETECH 1.5, many of the changes QuickCam made are now stock.  I've updated this mod's variables to remove those that are same as stock.  Most stock values that remain to be changed, are now only off a about half a second or less.

QuickCam shouldn't cause any errors with save files, even saves in combat, or with version updates. I've done extensive testing back and forth between stock and modded play without any errors. It does not add any new items to the VersionManifest.csv.

#### OBSOLETE Pre-1.5 A/B Video OBSOLETE: https://youtu.be/pmEC6UIdYws
Leaving this up as a reference, but this no longer reflects stock play as of BATTLETECH 1.5

### Instructions:

    Copy QuickCam folder in to Mods folder created for ModTek.
    
### ModTek
This mod needs ModTek to work:

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
