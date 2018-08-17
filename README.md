# Space Engineers Modding Cookbook
Modding (Plugins and In-Game Scripting) Cookbook for Space Engineers.

The goal of this repo is to gather together various tips and techniques for modding different parts of Space Engineers. This is aimed at SE modding beginners (both seasoned and beginner coders).

However, this guide will not go into tutorials about how C#, .NET or OO works. Readers are encouraged to seek out and understand those elements on their own, there is plenty material around.

A large part of this will be information from the amazing Space Engineers modding community at large, and most of the code will be distillations of techniques used by various mods on the Steam Workshop. I will try my very best to reference and give credit where applicable.

Each of the cookbook entries will have a sample mod that should be fully functional for what it is trying to illustrate.

To be entirely clear - going forward, 'IGS' or In Game Scripting will refer to the code that you can paste into a programmable block in-game. 'Modding' will refer to a mod that you put into the mods folder of your Space Engineers data folder. 'Plugin' refers to a .dll that fundamentally alters the game itself.

The IGS part is fully shared concepts that can be applied at all levels, so we'll cover a single entry on how to use an IGS inside a mod and then you can use any of the IGS scripting concepts inside a normal mod.

# Important Licence Disclaimer (Read this if you want to contribute/republish)

This is intended to be an organic cookbook that evolves with the game as Space Engineers matures. It is not intended to become an actual physical 'Print' book. HOWEVER, the license for all code and text in this repo is under an extremely open MIT licence, which means that lifting this text and republishing in any form is entirely allowed (with attribution).

Do not contribute to this repo if that does not sit well with you. If you see code in here that is yours and would prefer it removed, please feel free to contact me so that we can work together to still provide the modding community at large with valuable information but not feel as if your hard work has been compromised - I respect that

If you do republish this to make profit off this, please consider ways to give some of that money back into the modding community. Editing this content to make it book-worthy is no small task in and of itself, so there is definitely merit to it, but remember the plenty of hours of hard work that has gone into figuring this lot out by the community.

# Editing guide

- Guidelines for contributing to this cookbook, in short:
  - Focus on tiny mods that will help a beginner form an composable base for building their mods.
  - Keep the language clean, clear and succinct, but remember that there is no 'obviously'. Explain every step.
  - Have important pieces of code scattered in the article, along with mostly copy-able code at the end.
  - Adhere to a standard file structure, so that testing the entry in-game is quick and painless.
  - Give attribution to original authors. If you distilled a section from a specific mod, mention their work. Emphasis on 'distilled' - there may be licensing issues if you simply copy code from other authors, don't do that. 
  - Reference some other example mods that use a similar technique, to showcase what can be done.
  - Add a 'see also' section to give a beginner a natural progression from your entry.

# In Game Scripting

- General Do's and Don'ts for IGS
- Setting the update speed
- Hello World
- Publish and update project to Steam Workshop
- Project setup with external editor (Visual Studio)
- Find specific block types on a grid
- Turn blocks on or off on a timer
- Calculate inventory size
- Writing to LCD's
- Drawing pixels on LCD's
- Altering thruster values
- Altering suspension block values
- Altering rotor and piston values


# Modding

- General Do's and Don'ts for modding
- Setup your environment for modding (including tools)
- Migrate an IGS to a mod.
- Create a blank mod, setting update speed.
- Publish and update project to Steam Workshop
- Drawn debug lines, shapes.
- Find connected grids
- Spawn a blueprint into the game world
- Simple new custom block mesh + texture (no logic)
- Custom block programming
- Custom terminal UI
- Teleport a player
- Create explosions
- Warp effect
- Multiplayer server/client communication
- Handle custom chat commands

# Plugins

- General information and warnings around dll plugin development
- Setup your environment for plugin development
