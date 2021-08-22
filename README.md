# SVHeretic
![Intermission Screen](https://github.com/SibTiger/SVHeretic/blob/main/GitHub%20Services/ReadMe/SVHeretic.png)

This [PWAD](http://doomwiki.org/wiki/PWAD) allows the players to continuously play through all of the [Heretic](https://store.steampowered.com/app/2390/) [episodes](https://doomwiki.org/wiki/Heretic#Heretic_levels) without needing to start a new game or to restart the same episode again within a multiplayer environment.  _SVHeretic_ is ideal for both Multiplayer environments as well as Single Player games.

# Requirements

* **Recommended Doom Engine Port**
  * [ZDoom](https://zdoom.org/index) 1.22 or later

* **Game Requirement**
  * [Heretic](http://www.idsoftware.com/)
    * You can also buy it on [Steam](https://store.steampowered.com/app/2390/)
  * [Blasphemer](https://github.com/Blasphemer/blasphemer)
    * An alternative if it is not possible to retrieve _Heretic_.


# ReadMe
```
===========================================================================
Advanced engine needed  : ZDoom 1.22 or later
Primary purpose         : No levels included
===========================================================================
Title                   : Server Heretic
Filename                : SVHertic.wad
Release date            : 10 October. 2016
Author                  : Nicholas "Tiger" Gautier
Email Address           : SibTiger_and_Life@Hotmail.com

Description             : This allows any specific supported engine to
                          continuously run all maps from E1 to E5.
                          This file ignores (End Episode), and well reroute
                          to the next episode when the current is
                          finished.
                          Perfect for multiplayer proposes!
                          
                          Version 1.00: 25 April. 2008
                               Original Release
                          
                          Version 1.01: 20 November. 2008
                               Fixed a possible HOM issue that sometimes occur
                                 in SkullTag.
                          
                          Version 2.00: 30 November. 2012
                               * Expunged CISVH.txt; superfluous ASCII file...
                               * Added a new lump 'ZMAPINFO' for engines that support it
                               * Applied level number capability; useful for ACS scripts.
                               * Enforced 'No Jumping' and 'No Crouching'; changable
                               * Enforce 'Smooth Lighting' variable to true.
                               * Enforce 'Normal Infighting'
                               * Ports that use MAPINFO should render intermission screens
                                   almost adjacent to those that use ZMAPINFO.
                               * Added support for the sixth episodes.
                          
                          Unversioned: 10 October. 2016
                               * Renamed file from 'SVHeretic' to 'SVHertic'.
                                   This is in compliance with /idgames policy with 8char max filenames.
===========================================================================
* What is included *

Sounds                  : No
Music                   : No
Graphics                : No
Dehacked/BEX Patch      : No
Demos                   : No
Other                   : No
Other files required    : None


* Play Information *

Game                    : Heretic
Single Player           : No
Cooperative 2-4 Player  : No
Deathmatch 2-4 Player   : No
Other game styles       : None
Difficulty Settings     : Not implemented


* Construction *

Base                    : Modified
Build Time              : Several hours
Editor(s) used          : Notepad++
May Not Run With...     : Any non-ZDoom based engine


* Copyright / Permissions *

Authors MAY use the contents of this file as a base for modification or
reuse.  Permissions have been obtained from original authors for any of
their resources modified or included in this file.

You MAY distribute this file, provided you include this text file, with no
modifications.  You may distribute this file in any electronic format (BBS,
Diskette, CD, etc) as long as you include this file intact.  I have
received permission from the original authors of any modified or included
content in this file to allow further distribution.

* Where to get the file that this text file describes *

The Usual: ftp://archives.3dgamers.com/pub/idgames/ and mirrors
```
