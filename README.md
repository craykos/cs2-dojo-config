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

ᴠ. 3.80

**Instant smokes for: ancient, anubis, inferno & mirage**

Video Guide:
https://youtu.be/JBK9XNZ9MwE

## Installation: 
1.    Copy files `dojo.cfg, dojoBindings.cfg, dojoOff.cfg` and the `folder dojo` for CS2 to the folder  
     Steam\steamapps\common\Counter-Strike Global Offensive\game\csgo\cfg    
2.   Set the keys for the program in the file dojobindings.cfg   

Default Keys:  
F4 = Next spawn  
F5 = Same spawn again  
F6 = Reveals lineup  
F7 = Clears smoke  
F8 = Rethrow 
 
j = Places bot        
k = Kicks all bots         
l = Toggle bot crouch 

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
 - Clear smokes with `F7` (Default Key, modify in dojobindings.cfg)      
 - To rethrow grenades press `F8` (Default Key, modify in dojobindings.cfg)  
 - To place a bot press `j` (Default Key, modify in dojobindings.cfg)  
 - To kick all bots press `k` (Default Key, modify in dojobindings.cfg)  
 - To toggle between crouch and standing bots press `l` (Default Key, modify in dojobindings.cfg)

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
-  Press `F4` (Default Key, modify in dojobindings.cfg)  
   to cycle through the lineups of the instant smokes.
-  Press `F6` (Default Key, modify in dojobindings.cfg)  
   to get teleportet to the same lineup again.   
 - Clear smokes with `F7` (Default Key, modify in dojobindings.cfg)      
 - To rethrow grenades press `F8` (Default Key, modify in dojobindings.cfg)  

#### Practice without help ####
-  Press `F4` (Default Key, modify in dojobindings.cfg)  
   to cycle through the spawn positions (The spawn locations are extracted directly out of the game files).
-  Press `F5` (Default Key, modify in dojobindings.cfg)  
   to get teleportet to the same spawn again.  
 -  Press `F6` (Default Key, modify in dojobindings.cfg)  
   to reveal the lineup of the current instant smoke.    
 - Clear smokes with `F7` (Default Key, modify in dojobindings.cfg)      
 - To rethrow grenades press `F8` (Default Key, modify in dojobindings.cfg) 

Tip: Bind the command `noclip` to a key for fast movement through the map.  
  - To toggle noclip with the middle mouse button write  
       `bind mouse3 noclip` in console

### Restore binds ###
To restore the original binds you set in the dojoBindings.cfg  
write in console:
- `dojooff` when the config is still loaded
- `exec dojooff` when the config is not loaded anymore
