# QuickCam - Shorter camera delays for HBS BATTLETECH
This ModTek mod changes the camera delays found in the CombatGameConstants.json.  This is intended for experienced players that don't want the longer pauses for status updates.  Meant to be used in addition to shortening the common audio delays, but may be used alone. Feel free to edit the values to your own liking.

QuickCam shouldn't cause any errors with save files, even saves in combat, or with version updates. I've done extensive testing back and forth between stock and modded play without any errors. It does not add any new items to the VersionManifest.csv.

#### A/B Video: https://youtu.be/pmEC6UIdYws

### Instructions:

    Copy QuickCam folder in to Mods folder created for ModTek.
    
### ModTek/BTML
This mod needs ModTek and BTML to work:

https://github.com/BattletechModders/ModTek/releases

https://github.com/BattletechModders/BattleTechModLoader/releases

## Stock File Edits:
StreamingAssets\data\constants -

    CombatGameConstants.json
        "CameraConstants":
    
            "CamDelayDeath" : 2.0, *From 4.0*
            "CamDelayBuildingDeath" : 1.5, *From 4.5*
            "CamDelayFall" : 2.0, *From 4.0*
            "CamDelayLocationDestroyed" : 2.0, *From 3.0*
            "CamDelayCriticalHit" : 2.0, *Unchanged*
            "CamDelayComponentDestroyed" : 2.0,*Unchanged*
            "CamDelayPilotInjured" : 2.0, *From 3.0*
            "CamDelayPilotInspired" : 3.0, *Unchanged*
            "CamDelayMiscInfo" : 1.5 *Unchanged*
