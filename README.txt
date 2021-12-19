Mod Creator: Victoria Gorski
Date: 12 / 19 / 21
CSC375 Open - Source Project

Special thanks to the creator of the Kade Engine which makes Friday Night Funkin easier to mod and run the
more smoothly than the original 

There weren't that many files I had to modify to put the mod in, but here is the list of the files I did 
modify:
- freeplaySonglist.txt (to add my song to FreePlay mode)
- stageList.txt (to put my character in a stage)
- PlayState.hx (to actually move the mod into the game)
- Character.hx (to add the character)

I used the DADDY_DEAREST .xml and offsets file for the positioning of my character, but that and the stage are 
all I used from the game itself. The character, music, and music chart is all original.

Apparently the game freaks out if you have a music chart that's more than 1 minute and 30 seconds, so I only did
a small sample of the original song which is about 1 minute 30 seconds, but you can listen to the full song with 
and without tuning or just the instrumental on the Songs-and-Characters branch.

The project does not come with the compiled game so you'll have to do that on your own. To do that you'll need to download 
Haxe and lime on your computer so go to https://haxe.org/download/ to download Haxe and once that's all said and done, you can 
run "haxelib install lime" on your command prompt to install lime. Once you have those two things, you can open up your
downloaded master brnach, change directory to the folder of the game, and run the command "lime test [your os]" for just the regular
game and "lime test [your os] -debug" for the game in debug mode.
