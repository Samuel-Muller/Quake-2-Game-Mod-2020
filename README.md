# Quake-2-Game-Mod-2020

> Quake 2 modding project for IT266 Spring 2020 at New Jersey Institute of Technology.

# Personal Deliverables:
*	Player can plant and tend plants
    - The blaster now plants plants instead of shooting a laser. These plants may look like monsters to the untrained eye.
*	Plants Give bonuses / attack enemies when mature
    - After a little while, plants mature and spawn a randomized health bonus
*	Monsters spawn in waves to attack the plants and then the player
    - Monsters spawn in groups of 3 + wave number near the start of the level.
*	Win conditions based on surviving a number of waves
    - Waves count up, lasting about a minute. At wave 10, a win message is displayed in the console, and the player is given god mode. To advance waves for easy testing, use command wnext in the console.
*	5 bonuses that can drop from enemies
    - Light Guards drop a randomized health item on death

# Common Deliverables:
*	Separate your project into its own folder (not baseq2)
    - Done locally. Heres how: Make a new folder in the same directory as quake2.exe and baseq2 and name it QVZ (can actually be named anything, but QVZ is what I chose). Put the compiled gamex86.dll into this folder, along with other necessary files for the mod such as pak files. 
*	A shortcut to auto launch your mod
    - Done locally. Heres how: Make a shortcut to quake2.exe. Edit the target of the shortcut in its properties to "<path to quake2.exe>" +set game QVZ (this is assuming the mod's folder is named QVZ, if it's something else, make it that name) 
*	A README.md explaining your project and how to showcase your deliverables
    - Hmm...
*	UI Changes
    - Changed the help menu to display data about waves. To see updated help menu background, put it in the appropriate folder in the pak files.
*	In Game Visuals (temporary entities)
    - Made a temp entity explosion when planting plants
