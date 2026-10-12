# Jumplight Odyssey Recontinued (JLOR)

UNOFFICIAL mod aimed primarily at fixing bugs and (rarely) adding new content to the discontinued game [Jumplight Odyssey](https://store.steampowered.com/app/1893820/Jumplight_Odyssey/).

Currently work in progress, you can report any bugs you find in the game and it will be patched in the mod on release (use issues!!). I will try to respond and fix any bugs reported via issues before the mod releases.

The mod will be discontinued if the developers decide to continue development on Jumplight Odyssey.

This ENTIRE mod is unofficial. All the mod's code is under Unlicense.

AI is used for most, if not all code since I don't really know much about Unity. I primarily use two LLMs for coding things like this: Gemini 3.8 Flash, and GPT 6 Astra.

### The content below here is for when the mod releases, you can ignore it:

# Features

This mod was created since the Jumplight Odyssey developers abandoned the game (or temporarily halted development on the game), the game was left in a state with hundreds of bugs, almost unplayable for those who didn't want to lose a lot of progress or reload the game every 5 minutes.



This mod is aimed at fixing bugs the developers didn't fix, improving core game features, and potentially adding more content or balance changes. Multiplayer is one of the main features that are planned, after a majority of the bugs have been fixed. Custom sandboxed Lua mods, and a full mod repository is also planned, likely gonna be at JLOR.oxygenlow.com/mods (you'll need an account at oxygenlow.com to publish mods though downloading and auto-updating mods is free).



The primary bugs I found and have (or will be) fixed are:

- The topbar tooltips almost always displaying inaccurate/false information
- AI not attempting to consume food while starving
- Game crashing after attempting to save corrupted screenshot for save
- Game displaying successful save after not saving due to low storage on device

## Compatibility with existing saves

This mod is likely compatible with most existing saves, though I suggest you back everything up if you're planning to use an existing save.



Do not report bugs if you are using a save that wasn't created with the mod.


# Installation

BepInEx is a dependency, download it from:



https://github.com/BepInEx/BepInEx/releases/download/v5.4.23.5/BepInEx\_win\_x64\_5.4.23.5.zip



Then extract it into your Jumplight Odyssey files (usually \[drive]:\\SteamLibrary\\steamapps\\common\\Jumplight Odyssey).



Then run the game once and close it.



Place the mod .dll files in BepInEx\plugins.



If you want it to automatically update, also move the JLOR-AutoUpdate.dll into plugins, then it will check for updates every time you start the game and automatically update the mod.

