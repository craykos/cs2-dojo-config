# cs2-dojo-config
*Practice tool for utility and instant smokes in cs2*

  _____           _              _     __                 _                __                ___  __ ____   
  \_   \_ __  ___| |_ __ _ _ __ | |_  / _\_ __ ___   ___ | | _____  ___   / _| ___  _ __    / __\/ _\___ \  
   / /\/ '_ \/ __| __/ _` | '_ \| __| \ \| '_ ` _ \ / _ \| |/ / _ \/ __| | |_ / _ \| '__|  / /   \ \  __) | 
/\/ /_ | | | \__ \ || (_| | | | | |_  _\ \ | | | | | (_) |   <  __/\__ \ |  _| (_) | |    / /___ _\ \/ __/  
\____/ |_| |_|___/\__\__,_|_| |_|\__| \__/_| |_| |_|\___/|_|\_\___||___/ |_|  \___/|_|    \____/ \__/_____| 

 _                                  _              
| |__  _   _    ___ _ __ __ _ _   _| | _____  ___  
| '_ \| | | |  / __| '__/ _` | | | | |/ / _ \/ __| 
| |_) | |_| | | (__| | | (_| | |_| |   < (_) \__ \ 
|_.__/ \__, |  \___|_|  \__,_|\__, |_|\_\___/|___/ 
       |___/                  |___/                

ᴠ. 3.20

**Instant smokes for: ancient, anubis & mirage**

## Installation: 
1.    Copy files for the limited test of CS2 to the folder  
     Steam\steamapps\common\Counter-Strike Global Offensive\game\csgo\cfg    
2.   Set the keys for the program in the file dojo.cfg   

Default Keys:  
F1 = Next spawn  
F2 = Same spawn again  
F4 = Reveals lineup  
F5 = Clears smoke  
F6 = Rethrow  

## How to use:
1.   Open CS2 -> press `Play` -> `Practice` -> `Competitive` 

2.   Choose the map you want to play -> press `Go`

3.   Open the console and write `exec dojo`  
   To restart the config in this session write `dojo` in console.

4.   Choose a practice mode
    - After writing `exec dojo` you are given 2 options.  
      * To choose the [freestyle mode](https://github.com/craykos/cs2-dojo-config#freestyle-mode) write `i1` in console.  
      * To choose the [instant smokes mode](https://github.com/craykos/cs2-dojo-config#instant-smokes-mode) write `i2` in console.

### freestyle mode
 - You start with an AK, molotov, smokegrenade, he and flash.  
   M4A1-S, M4A4 and incendiary grenade are lying on the floor for optional use.
 - Move freely through the map and practice your utility
 - Clear smokes with `F5` (Default Key, modify in dojo.cfg)      
 - To rethrow grenades press `F6` (Default Key, modify in dojo.cfg)  

Tip: Bind the command `noclip` to a key for fast movement through the map.  
  - To toggle noclip with the middle mouse button write  
       `bind mouse3 noclip` in console

### instant smokes mode  
5. You receive a list of supported maps. Choose the one you are currently on.  
   Write `imirage` to load the instant smokes for mirage.

   You are on the wrong map? You want to change the map to mirage for example?   
   Write `changelevel de_mirage` in console  
   and `dojo` in console after the map change to restart the config. 
 
6. After loading the instant smokes with `i<mapname>` you are given 2 options  
   To practice with lineups write `i1` in console.  
   To practice without help write `i2` in console.

#### Practice with lineups ####
-  Press `F1` (Default Key, modify in dojo.cfg)  
   to cycle through the lineups of the instant smokes.
-  Press `F2` (Default Key, modify in dojo.cfg)  
   to get teleportet to the same lineup again.   
 - Clear smokes with `F5` (Default Key, modify in dojo.cfg)      
 - To rethrow grenades press `F6` (Default Key, modify in dojo.cfg)  

#### Practice without help ####
-  Press `F1` (Default Key, modify in dojo.cfg)  
   to cycle through the spawn positions (The spawn locations are extracted directly out of the game files).
-  Press `F2` (Default Key, modify in dojo.cfg)  
   to get teleportet to the same spawn again.  
 -  Press `F4` (Default Key, modify in dojo.cfg)  
   to reveal the lineup of the current instant smoke.    
 - Clear smokes with `F5` (Default Key, modify in dojo.cfg)      
 - To rethrow grenades press `F6` (Default Key, modify in dojo.cfg) 

Tip: Bind the command `noclip` to a key for fast movement through the map.  
  - To toggle noclip with the middle mouse button write  
       `bind mouse3 noclip` in console

