# Yume Nikki v0.10a English Bugfix Build
Fixed up English build of Yume Nikki

## About
The Steam build of Yume Nikki is not very good. Say what you want about the official translation, but this build introduced several bugs and inconsistencies that didn’t exist in the original Japanese version, or even the unofficial English translation. It also did not patch bugs that have been known about for years, and has the entire RPG Maker 2003 RTP packed with it, despite never using it.

So, what I sought out to do was make the best possible English build of Yume Nikki possible. This was accomplished using the [2012 Japanese release of v0.10a from PLAYISM](https://archive.org/details/yume-nikki-010a), and [vgperson’s RPG Maker 200X Translation Assistant](https://vgperson.com/other), which helped me majorly in renaming files into ASCII and having them still work in-game.

**This is meant as a replacement to the Steam build.** This is because the original Steam build file structure is an actual nightmare, and it was easier long term to do this, rather than try and just patch the Steam build.

**Saves from the Steam build and anything based on it are still cross compatible,** I made sure of that, but if you’re using the unofficial translation you will need to use EasyRPG or something to properly open your save file.

This build comes in two versions, one with the official translation, and one with a modified version of the unofficial version, labeled the alternative translation. Pick whichever one you prefer, the only difference is text.

## Installation
You can either backup your Steam build's saves somewhere else, delete the Steam build, replace it with this one, and then put your saves in, or just put this anywhere and launch RPG_RT.exe

## General Changes
### NOTE: Because some of these changes are very specific, from now on THERE WILL BE SPOILERS!

- Entire file structure translated and renamed into ASCII
	- Unlike the Steam build, all assets are renamed to what they approximately mean in English instead of random, confusing numbers
		- There are 5 files still named with random numbers in order for Steam saves to load properly however
		- Most file names are based on vgperson's REM data build, and The Cutting Room Floor wiki's translations
	- Also unlike the Steam build, thanks to vgperson's RPG Maker 200X Translation Assistant, ALL assets are accounted for in-game
- Smaller file size because the entire RTP isn't packed with it (it's not needed)
- More consistent text
	- Consistent effect descriptions (no more random capitals)
	- Recentered effect names when recieving them (best I could anyway, some vary)
	- Corrected all instances of incorrect effect names
		- Nexus eggs and FC Menu
	- Removed the FC World Effect windows having stars, since no other window has them
	- Fixed the Menu Theme text in The Mall when using the Traffic Light effect
- Everything except all switches, variables, events, and common events have been translated code-wise
	- i.e. the map names
- Quieter effect sounds than the Steam release
	- Probably changed because they must've done everything by hand
- Less lag with rotating pictures on screen 
	- i.e. the spotlight when saving

## Alternative Translation
As mentioned above, this build comes in two versions, one of which contains an alternative translation based on the unofficial one. Note that the file names/code refer to the effects as such, and not by the official translation names. This is because I built this version first.

- Text on Pictures are different (i.e. the tutorial)
    - Font is also different
    - More things are translated than the original unofficial translation (Famigame Menu and dreaming countdown)
- Effect names changed
    - Snow Woman -> Yuki-onna
    - Kitchen Knife -> Knife
    - Eye Palm -> Medamaude
    - Fatten -> Fat
    - Midget -> Small (vgperson's version)
    - Faceless Ghost -> Nopperabou
    - Poo Hair -> Poop Hair
    - Blonde -> Blonde Hair
    - Spirit Headband -> Triangle Kerchief
    - Squish-Squish -> Squishy (vgperson's version)
    - Traffic Light -> Stoplight
- Effect descriptions changed to be all more consistent with each other
    - i.e. most are "Become [blank]" like the original unofficial translation

## Bugs Fixed
I wanted this to be the best English version of Yume Nikki it can be, so I fixed some bugs that were present in the original v0.10a. Credit to The Cutting Room Floor wiki for listing these on Yume Nikki's bug page.

- Chair glitch
    - Optional patch because I know a lot of people like this one, and it's used for speedruns
- Incorrect tileset swapping for broom in Number World Bedroom, Neon Tile Path B, and Pink Sea
- Bonus red eggplant in NASU being invisible the next game, if you caught it as soon as you got a game over last game
- Softlocking while sitting down during the Spaceship crash event (I’m unsure about this one, please let me know if this isn’t the case)
- Unused Kinoko-san colors when using Cat effect
- Additional bugs that only the English Steam release has:
    - Spaceship bed transition being invisible
    - Missing SFX

## Credits
- Kikiyama for Yume Nikki v0.10a
- PLAYISM for the 2012 Japanese release used as a base and the official translation
- vgperson for the RPG Maker 200X Translation Assistant used to ASCII-fy everything, most filenames, and alternative effect translations
- The Cutting Room Floor wiki for the v0.10a bug list, and some file/map name translations
