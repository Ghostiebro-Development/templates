When createing an item in he items.lua the following steps MUST be followed.

A items "spawnname" must be in all LOWERCASE with NO SPACES, the name in [] and under ['name'] MUST match or else the system will not be able to spawn the item nor will it be able to link the 
item to the consumables.lua or config.lua

Items that are set to consumable = true must have the spawnname in the section labled "spawnname" and must DIRECTLY match the name shown in items.lua


The Config must be broken down by item CONSUMPTION type; Drink or Eat, as this will make an item fill HUNGER or THIRST.

when createing an immage please make sure the file has NO SPACES, UNDERSCORES, OR SPECIAL CHARACTERS.


Item names that need a ' should be done as follows (Jannet/'s Nuggets) 