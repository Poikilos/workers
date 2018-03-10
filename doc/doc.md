# Minetest Workers Mod Documenation

This documentation is written by LocaL_ALchemisT (see README.md for mod authors).

Dependencies: Default, Bucket (highly recommended)

## CONTENTS

1. Introduction

2. Crafting Recipe

3. Guide on Workers

## INTRODUCTION

Before we go further, I apologize for bad English.

This mod adds a set of nodes that can move and can be interact to do specified work.

The nodes, or workers, are created for the lulz and used for fun only. If you are a serious builder, then this mod might not be useful to you.

A brief history about this mod:

 Ver. 0.0: Harvester was the first (and only) worker available

 Ver. 1.0: Added Miner & Gardener

 Ver. 1.1: Revised & improved Miner inventory management

 Ver. 2.0 (Current): Added 5 more workers

Sometimes the workers would be addressed either as ‘him’ or ‘it’. It does not really matter to me.

Known bugs and problems:

1. Workers move too fast when they face north or east.

2. Lag or crash occurs at some point (happens rarely, depend on how many workers are working in one place).

This mod has been tested using Minetest 0.4dev.

If there are any problems, raise it up in the official Minetest forum (in this mod’s topic, maybe?).

Have fun.

## CRAFTING RECIPES

![recipe_all.bmp](images/image002.jpg)

Some building plans for builder (will be explained further below):

![plan_recipe_almost_all.bmp](images/image004.jpg)

## GUIDE ON WORKERS

### A. Harvey The Harvester

![face_harvey.png](images/image005.png)

Put it on the ground and right click. Enter the item name that you want it to collect (you can write in modname:nodename or alias).

Left click to activate, left click it again to stop it and take it and everything it has collected into your inventory.

![harvey_00.bmp](images/image006.png)

### B. Mordec The Miner

![face_mordec.png](images/image007.png)

Put it on the ground and right click. Place some default:wood into the wood slot at top left corner.

Left click to activate, left click it again to stop it. For each level of ground it digs, it will consume one wood. Right click to open its inventory.

![mordec_00.bmp](images/image009.jpg)![mordec_01.bmp](images/image011.jpg)

![mordec_02.bmp](images/image013.jpg)![mordec_03.bmp](images/image015.jpg)

Mordec glows in the dark.

![mordec_04.bmp](images/image017.jpg)

### C. Garren The Gardener

![face_garren.png](images/image018.png)

Put it on the ground and right click. Place one plant sample into the top left slot and put some default:sapling into the top right slot. Left click to activate, left click it again to stop it.

![garren_00.bmp](images/image020.jpg)![garren_01.bmp](images/image022.jpg)

![garren_02.bmp](images/image024.jpg)![garren_03.bmp](images/image026.jpg)

For each jungle tree it grows, it will consume 9 saplings.

For each apple tree, papyrus or cactus it grows, it will consume 3 saplings.

For each jungle grass or dry shrub it grows, it will consume one sapling.

If there is no plant sample or the sample is not one of the plants mentioned above, it will plant a sapling, and that of course will use one sapling each.

### D. Benjo The Builder

![face_benjo.png](images/image027.png)

Put it on the ground and right click. Place a building plan into the top left slot and put any type* of material into the top right slot. Left click to start building.

After that, your plan will turn into blank paper.

![benjo_00.bmp](images/image029.jpg)![benjo_01.bmp](images/image031.jpg)

The building plans (refer further above for craft recipes):

1. House

![plan_house.png](images/image033.png)![benjo_02.bmp](images/image035.jpg)![benjo_03.bmp](images/image037.jpg)

2. Hut

![plan_hut.png](images/image039.png)![benjo_04.bmp](images/image041.jpg)

3. Tower

![plan_tower.png](images/image043.png)![benjo_05.bmp](images/image045.jpg)

4. 9x9 wall

![plan_wall.png](images/image047.png)![benjo_06.bmp](images/image049.jpg)![benjo_07.bmp](images/image051.jpg)

![](images/image053.png)![benjo_08.bmp](images/image055.jpg)

5. Underground bunker

![plan_ubunker.png](images/image057.png)![benjo_12.bmp](images/image059.jpg)![benjo_13.bmp](images/image061.jpg)

6. Pool

![plan_pool.png](images/image063.png)![benjo_09.bmp](images/image065.jpg)![benjo_10.bmp](images/image067.jpg)

7. Moat

![plan_moat.png](images/image069.png)![benjo_11.bmp](images/image071.jpg)

*All allowed materials are in default mod: stone, cobble, mossycobble, tree, jungletree, wood, brick, clay, desert stone, glass, steelblock, cactus and dirt.

**There are 2 more building plans which are not shown in this doc. Figure it out by yourself, it’s easy ;)

### E. Gredo The Guard

![face_gredo.png](images/image072.png)

You only need to put it on the ground and let it catch any worker which enters its radius. The owner of the caught worker will be notified about the catch.

Only you (the owner of the guard) can take caught workers from its inventory.

![gredo_00.bmp](images/image074.jpg)![gredo_01.bmp](images/image076.jpg)

### F. Asvard The Assassin

![face_asvard.png](images/image077.png)

Put it on the ground and right click. Enter player’s name which you want it to kill.

Left click to activate, left click it again to stop it.

It can wait for the targeted player to be online. Any guard within its radius will be annihilated.

Once it is stopped or completed its job, it will turn to steel sword.

![asvard_00.bmp](images/image079.jpg)![asvard_01.bmp](images/image081.jpg)

*It would not move if the targeted player is too far away (like _you-can’t-see-the-player_ far away).

### G. Toco The Thief

![face_toco.png](images/image082.png)

It is almost invisible and cannot be detected by guard or any workers above.

You only need to put it anywhere and let it steal everything inside locked chests and players’ inventory nearby.

![toco_01.bmp](images/image084.jpg)![toco_02.bmp](images/image086.jpg)

![toco_03.bmp](images/image088.jpg)![toco_04.bmp](images/image090.jpg)

*Tips for its victim: Take your stuff back from him.

### H. Cardon The Cop

![face_cardon.png](images/image091.png)

It’s the only worker so far that can beat assassin and thief. It can detect nearby thief and tell you its location and owner.

When it detects an assassin, it will destroy the assassin.

If the assassin has no target yet, then Cardon will give the owner a warning.

If it has a target, then Cardon will beat the owner and sends the owner to a prison high above him.

![cardon_00.bmp](images/image093.jpg)![cardon_01.bmp](images/image095.jpg)

**END**
