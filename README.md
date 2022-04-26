# Rimworld-TPatches
Many fixes, tweaks, settings and mod compatibility patches. Everything is toggleable. Made using XML Extensions!

It is a framework which allows me to add new toggleable patches into mod settings with as little effort as just writing a patch.

### [Detailed list of all settings](https://docs.google.com/spreadsheets/d/1nhq6maAQgqy5VEXBN_rNa-neVqVlNxartAt38_Km4TA/edit?usp=sharing)

[Discord](https://discord.gg/dcVj4b5VwJ)


## Content
- duplicate animal remover
- duplicate material remover (WIP)
- stuffable stone floors
- research fixes, text fixes, xml fixes
- filter for rottable items
- designation category overhaul based on DocWorld
- many small fixes, tweaks and balancing changes

By default all fixes are enabled, all tweaks and balancing changes are disabled. You can enable/disable any feature in this mod using XML Extensions mod menu.

## Compatibility
- If you use designation categories setting, load TPatches after Niilo's QOL mod. Niilo has similar setting which overwrites TPatches causing inconsistencies, like some VFE lights will be in furniture tab instead of lights tab.
- Should be compatible with everything, but loading order is important!
- **Loading order** - load as low as possible, just above the performance mods.

## Bugs
- Rottable filter isn't perfect and might contain some non-rottable food item, but only meals, so they fit in a fridge anyway.
- Disabling VFE Mechanoids designation category can cause a supposedly harmless red error. Something is still trying to access that category, but if I don't delete it, ther is just nothing there, and there is no XML referencing it.

## Info
Requires [XML Extensions](https://steamcommunity.com/sharedfiles/filedetails/?id=2574315206).


## Screenshots
Screenshots show default settings.
![tp1](https://user-images.githubusercontent.com/76593873/141163396-b440bfdf-3465-43d0-8a3c-3399d2f1ffc7.png)
![tp2](https://user-images.githubusercontent.com/76593873/141163402-e20055a0-8aff-4125-a058-7a6e495008cd.png)
![tp3](https://user-images.githubusercontent.com/76593873/141163406-67d18562-620b-4d57-83ec-c22489028e85.png)
![tp4](https://user-images.githubusercontent.com/76593873/141163416-67a1cbb8-751c-4348-9f1d-c20a26bfeb60.png)
![image](https://user-images.githubusercontent.com/76593873/137011197-77af973f-c791-46d1-a3c3-a63ec137c729.png)
![image](https://user-images.githubusercontent.com/76593873/137011210-e827b089-c395-4ee0-89d2-b28c49110538.png)


Imranfish's XML Extensions is an incredible modding tool, using it I made a "framework" which automatically creates a fancy setting entry for each patch I make. If you have any suggestions, I can now very easily implement them into the mod.


Load as low as possible!

To access settings menu, go to rimworld settings and press the "More Mod Settings" button which is added by XML Extensions.
