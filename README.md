# Flashpoint Spawn Adjustments
MOD DOES NOT CONTAIN FULL PLAYABLE FLASHPOINTS!

This ModTek mod changes spawn weights to let low difficulty Flashpoints to appear first.  It alters the base 10 weight of lower difficulty Flashpoints and those with rep requirements to allow them to spawn more often than harder Flashpoints.  This is intended for Career Mode when you will be able to complete some Flashpoints with the starting Lance or close to it.  This does affect campaign mode as well, but it is trivial to clear these early FPs quickly after the story is complete.  This does not edit anything with the Heavy Metal FP campaign as those have their own method of spawning.

### DLC WARNING
YOU MUST ONLY DOWNLOAD THE PACKAGE FOR DLC YOU OWN OR YOUR GAME MAY NOT LOAD.

This mod only contains the flashpoint.json files for these Flashpoints, it does not contain the MilestoneSets, Contracts or any other files required to actually play the FPs it alters.

### Packages
ONLY ONE PACKAGE CAN BE INSTALLED AT A TIME.

YOU MUST ONLY DOWNLOAD THE PACKAGE FOR DLCs YOU OWN OR YOUR GAME MAY NOT LOAD.

On the release page, there will be three .zip files.  One with both Flashpoint and Urban Warfare files, and two with either FP or UW files only for those who do not have both.  They all run off of the same mod.json and have the same ModTek name.

### Instructions:

    Download the package that corresponds with the DLC owned, FP+UW, FP only, or UW only.
    Remove older Flashpoint Spawn Adjustments folder if present.
    Copy Flashpoint Spawn Adjustments folder in to Mods folder created for ModTek or in the HBS Mods folder.
    
### ModTek
This mod can use either HBS Mod Manager or ModTek:

https://github.com/BattletechModders/ModTek/releases
    
#### Optional Dependancies:
    cFixes
This mod does not need cFixes to work. It will load after cFixes if present and if cFixes adjustments are needed I will copy them to this mod manually.  

### Scaling
Flashpoints have a base 10 weight to spawn.  The Difficulty number corresponds with the Skull rating x2, so a 2.5 Skull rated FP is Difficulty 5.  The "Joint Venture" FP has a weight of 200, and all "Alliance" FP's have a weight of 1000.  I've scaled the lowest difficulty FPs to 100 and rapidly sloped down to base 10 for Difficulty 7 and up where the majority of FPs reside.

    Difficulty	Weight
    4	          100
    5	          40
    6	          20
    7	          10
    8	          10
    9	          10
    10	          10

### Stock Files Edited:
#### Flashpoint DLC
    fp_gladiator.json - D6
    fp_greed.json - D6
    fp_justinAllard.json - D6
    fp_shadowOrg.json - D6
    
#### Urban Warfare DLC
    fp_doubleAgent.json - D5
    fp_lastChance.json - D6
    fp_prize.json - D4
    fp_redHunt.json - D7 + weight doubled for rep requirement
    fp_sentinel.json - D4
    fp_siegebreaker.json - D5
    fp_succession.json - D5
    fp_tournament.json - D4
    fp_yangBigScore.json - D5
