# Roadmap
This file will generally outline the roadmap to the next major/minor version of the mod, so you can have some idea of what to expect.
This roadmap is subject to change, especially so early in this mod's life.
I would expect, as time goes on, that the roadmap has less drastic changes and gets more specific as we get closer to final implementation.

## Updates in the Pipeline
Since we're before the first major/minor version, there's a few updates we have in the pipeline that will precede our First Content Update.

### Party System - 0.1.0
Our first minor update will be the new Party System. Given the changes on the backend, I felt like this deserved a minor update rather than a patch release.
Formerly called the "Aid" system, the Party Update will allow players to keep track of their allies status (online/offline, health) as they play cooperatively.
Players will be able to manage their parties through Commands, and through a new Party Menu (opens by default with the 'o' key.)
The Party Menu will allow players to Teleport to each other (with a cooldown) so people can play together more easily.

#### Looking ahead for the Party System
This system also opens up a lot of cool room for abilities that affect the entire party, and can be more specific in their use.
Additionally, the Quest System could reward entire parties, and special events/locations in the world could interact with parties specially.

### Quest Implementation Update
Presently, Quests are items you can get through the Quest board block. 
They only concern collecting items, and give rewards when you use them while having that amount of items in your inventory.
Our vision for Quests was to be vastly more expanded through more quest types, and a whole new interface.

#### Quest Journal Interface
The plan is to have a keybind (presently J) to open up a Quest Journal.
This Journal would allow a player to keep track of quests on their character, as opposed to items in the world.
There, they could complete, or abandon quests.
(Depending on how this all works, likely the ability to abandon a quest would include converting it back into a Quest item that you could have another player take, we'll see.)

#### More Quest Types
We want quests that track how many enemies you kill of a given type, how many biomes you go to, etc.
A lot of this logic should be able to hook into existing Advancement logic, and should be hopefully easy to access.

## First Content Update
We want to start adding our first structures and expand our crafting more.
Given how far away this is and how much more creative work it is, I expect it to take some time.

### New Structures - The End Crusaders Faction Structures
One of the questions my friends and I asked was "Who were the people who made the Strongholds?"
We want to expand the lore and add Crusader Strongholds in the upper reaches of the world, and incursions into the Nether (clearly they must have gotten Blaze Powder somehow to make Eyes of Ender.)
Given their location in the peaks of the overworld, a lot of the Silver ore added by this mod would be used in their design and decoration.

#### New Mob - Revenants
The idea is that these Crusaders would be long gone, but their spirits would remain. We'd love to create a ghost like entity, and have it give you a new drop of some kind.

### Magic Expanded
The Magic Staff implementation was the basis for a lot of the new stuff we wanted to add.
Our goal is to expand it to the various Magic types already present in Minecraft (fire, water, earth, air in 1.21, undeath, end, abyssal, and holy with the silver ore.)
We'll be expanding this more in detail as we get closer to implementation.
