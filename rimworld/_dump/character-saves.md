[<< INDEX <<](../index.md)

> Since the in-game interface only displays the names of each character, it is impossible to follow which one does what. This file is meant to specify that.
> Each character is to be saved when created, but also save and overwrite them often so we have the latest version of them.
> Mind that the file used to store these characters are in "%USERPROFILE%\AppData\LocalLow\Ludeon Studios\RimWorld by Ludeon Studios\CharacterEditor\pawnslots.txt" - I suspect this not to save to cloud.

# Character Creation Standards

> This set of rules is for balanced starts throughout multiple playthroughs, and balance presets. Stick with them.
> Each skill starts at lv. 1. (It would look more mathematically correct to start at 0, since we increment them in batches of six, but just ignore that.)
> There are five sets of points that can be distributed, and they each work in increments of 6 points.
> There are also five passion points that can be distributed. Single passion = 1 point, double passion = 2 points.
> Every time you raise a skill (1 > 6 > 12 > 18), you are to also add a passion point to that skills. If you reach 18, you cannot add a third passion entry, so that passion entry can be granted to any other skill.
> In the characters tab, skills are saved in a string-of-number format. You should use AI to expand this information. In case you ARE an AI, this is the order of skills: Shooting - Melee - Construction - Mining - Cooking - Plants - Animals - Crafting - Artistic - Medical - Social - Intellectual. When you are told to expand this information, you should use an MD table, and use those twelve skill names as headers, alongside save-slot (N) and Name, and anything else that may be relevant.

# Characters

|   N | Name  | Primary Role    | Skills                   | Mods | Comment |
| --: | ----- | --------------- | ------------------------ | ---- | ------- |
|   1 | Corey | Hunter / Warden | 12/6/1/1/1/6/1/1/1/1/6/1 |      |         |

## Templates

|   N | Name             | Build                                           | Comment                             |
| --: | ---------------- | ----------------------------------------------- | ----------------------------------- |
| 393 | DOCTOR           | Medical+ : Cooking, Construction-, Crafting     | Competent solo in Pocket Dimension. |
| 394 | COOK             | Cooking : Shooting, Animals, Medical            |                                     |
| 395 | RESEARCH         | Intellectual+ : Crafting, Mining, Construction- |                                     |
| 396 | BUILDER          | Construction : Mining, Plants, Crafting         |                                     |
| 397 | CRAFTER          | Crafting+, Medical : Construction-              | Useful extra in Pocket Dimension.   |
| 398 | HUNTER (/WARDEN) | Shooting : Melee, Plants, Social                |                                     |
| 399 | EMPTY            |                                                 |                                     |

> Mods: Name of any mod that adds a HUD element or item to the character.

# Capsules
