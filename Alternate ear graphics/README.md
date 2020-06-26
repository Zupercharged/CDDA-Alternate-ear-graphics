# Alternate ear graphics
A small mod I threw together which replaces certian mutation graphics with ones i'd redesigned. 
FULL DISCLAIMER, I designed these alternate graphics for a particular character of mine! I only made this because a few people seemed interested. Use this with the understanding that these graphics arent intended to work with all hairstyles, hair colours, skin colours or whatever other variables that might be relevant. 
 
Results may vary, you have been warned.


## Dependencies
Requires [UndeadPeopleTileset](https://github.com/SomeDeadGuy/UndeadPeopleTileset). 
The go to tileset for CDDA by this point and for good reason, its great!


## Usage Guide
This mod can be enabled mid-game, all it does is replace a few textures and add a few extra recipes. 

The ears arent covered properly by hats so make some of the cosmetic ears to layer ontop if your character has headwear. Ideally i'd make these specific mutations render over clothes but apparently that would take a load of C++ sorcery and i aint no harry potter.

### V1.1 Texture replacement
With v1.1 you now have a Texture folder with a selection of the mutation graphics in a selection of colour pallets, which means you can now choose a colour which better matches your characters hair colour! 

To change the texture colours, follow these steps:
> Open the /Alternate_ear_graphics/Textures folder, inside you will find a Hair_hue_index.png and a library of folders. If you're unsure which variant you are looking for, consult the Index. 

> To replace the in game textures, first open the folder for the colour you want and then copy both .png files, return to /Alternate_ear_graphics and  replace the existing .png files here.

> If open, restart the game. The changes should now have been applied!

The graphics can be swapped at any time, and the changes will register once you restart the game. If the colour you chose didnt suit your characters hair colour, refer again to the Hair_hue_index.png to see if there isnt a colour category that better suits it.


## Versions
v1.0 - Adds New mutation texures for Canine/ Lupine and Feline ears, as well as for the Fluffy tail mutation. Also adds recipies for ear mutation mimic hats for layering ontop of other headwear.

v1.1 - Adds Repository of mutation textures with different colour pallets designed to match most hair colours.
> Corrects all tail sprites Y offset to be 1 pixel lower.

## Issues
At the time of this writing, all the features in this mod are tested and work as intended. Lets hope that lasts!
