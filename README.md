# MHRise-Overlay-Ultrawide
And ultrawide version of the already created MH Rise overlay. Credit to GreenComfyTea, cursecat and coavins for all of the original code

Updated to v1.3 of original mod.

## My additions to make the centering work
I added two more choices: top_center and bottom_center
```lua
position = {
    x = 0,
    y = 27,  
    --Possible values: "top_left", "top_right", "top_center", "bottom_left", "bottom_right", "bottom,center"
    anchor = "top_center"
}
```

This is what I used to center the monsters on the screen. I also used this to edit  
the for loop to only loop as many times as there are monsters.
```lua
local total_monsters = enemy_manager:call("getBossEnemyCount");
```

![alt text](https://i.imgur.com/0eFzsPm.jpg)