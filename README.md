##[PC] Achievements Mods Enabler - Fallout 4 & Skyrim SE

**What is this?**

It's a plugin I made that re-enables achievements while using mods by patching Fallout4.exe or SkyrimSE.exe during runtime.
It's designed to be version independent.
It also works on already modded saves!

**How to install**

1. Copy all the files from the download to Fallout 4/Skyrim SE's root folder.

2. Read the notes.

3. Play (you may need to restart Steam for the mod to work).

**How to uninstall**

1. Delete DllLoader.txt, AchievementsModsEnabler.dll_Exports.txt, X3DAudio1_7.dll & AchievementsModsEnabler.dll from Fallout 4's/Skyrim SE's root folder.

**How do I know if it's working?**

You'll get no achievement warnings, and the [M] will won't appear in the saves menu (already modded saves will need to be re-saved for [M] to disappear), alternatively you can check the log just to be sure.

After you've started Skyrim SE (you can alt-tab for this part), In the same folder where you installed the mod, there's a log file called: AchievementsModsEnabler.log. 
It will either say "YES" or "NO". Indicating whether or not the plugin successfully patched Skyrim SE. So if it says NO, lemme know!

**Will it need updating?**

Probably not! I've designed this to be version independent.
However in the case that it does, I will have it fixed very quickly.
Below is a list of Fallout 4 & Skyrim SE versions that have been tested and working.

**Fallout 4 tested & working versions:**

- 1.8.7.0.0
- 1.7.22.0

**Skyrim SE tested & working versions:**

- 1.2.36.0.8

**Discussion**: 

Fallout 4: http://www.nexusmods.com/fallout4/mods/15639/?

Skyrim SE: http://www.nexusmods.com/skyrimspecialedition/mods/245/?

**Compile Notes**

- HJWasm must be setup before opening the project.

**NOTES**

- Achievements are baked into the saves. So any achievement that you would of gotten most likely won't be obtainable unless you load an earlier save or start again.
- If your save is already modded, you'll have to save again to order for the [M] to disappear.
- This will not get you VAC banned in any manner as Fallout 4/Skyrim SE does not use any anti-cheat.
- If the mod is not working, try restarting Steam and/or your computer.
- This is NOT NMM compatible. It must be installed manually.
- This does not use F4SE/SKSE. It will also not conflict with it.
- Written in C++/ASM (Visual Studio 2015 & HJWasm).

**CREDITS**

Bethesda for Fallout 4. (https://store.steampowered.com/app/377160/)

Bethesda for Skyrim SE. (http://store.steampowered.com/app/489830/)

Microsoft for Visual Studio 2015. (https://www.visualstudio.com/)

The HJWasm devs. (https://github.com/Terraspace/HJWasm)
