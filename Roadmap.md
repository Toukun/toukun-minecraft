# Roadmap
This file will generally outline the roadmap to the next major/minor version of the mod, so you can have some idea of what to expect.
This roadmap is subject to change, especially so early in this mod's life.
I would expect, as time goes on, that the roadmap has less drastic changes and gets more specific as we get closer to final implementation.

## Updates in the Pipeline
Since we're before the first major/minor version, there's a few updates we have in the pipeline that wil preceed 0.1.0.

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

### Aid System
For some context, before this Mod I used Data Packs to make custom content.
We had a system where a player could request aid; this would make them send out a message to all players requesting for aid.
A player could answer the call, and then be teleported to the player who requested aid.
I would like to bring this back. The full implementation is still not yet as well defined as I'd like, but I have a couple ideas.

#### Idea 1 - Bring back the Original Implementation
The original implementation was free form and easy to understand.
Likely, it would be a menu with a button to Request Aid, and a button to Go to aid players if there were any that requested it.
If possible, there would also be hotkeys to do both of those operations.
(Note : This was vaguely based off of how Phantoms work in Dark Souls. So we did have ideas to expand this for PVP, but this is in general a PVE mod.)

#### Idea 2 - Implement a Custom Party System
The other route would be allowing players to create Parties.
Parties would allow players to keep track of one another and even TP to one another.
In this way, a player could invite members with a new set of commands / menu interface instead of the original implementation.

#### Have an opinion? Head over to Discussions and vote!
We've created a [Poll](https://github.com/Toukun/toukun-minecraft/discussions/2) around this in Discussions. Feel free to vote there.

## 0.1.0 - First Minor Update
0.1.0 is where we want to start adding our first structures and expand our crafting more.
Given how far away this is and how much more creative work it is, I expect it to take some time.
Additionally, I would 

### New Structures - The End Crusaders Faction Structures
One of the questions my friends and I asked was "Who were the people who made the Strongholds?"
We want to expand the lore and add Crusader Strongholds in the upper reaches of the world, and incursions into the Nether (clearly they must have gotten Blaze Powder somehow to make Eyes of Ender.)
Given their location in the peaks of the overworld, a lot of the Silver ore added by this mod would be used in their design and decoration.

#### New Mob - Revenants
The idea is that these Crusaders would be long gone, but their spirits would remain. We'd love to create a ghost like entity, and have it give you a new drop of some kind.

### Magic Expanded
The Magic Staf implemetnation was the basis for a lot of the new stuff we wanted to add.
Our goal is to expand it to the various Magic types already present in Minecraft (fire, water, earth, air in 1.21, undeath, end, abyssal, and holy with the silver ore.)
We'll be expanding this more in detail as we get closer to implementation.
