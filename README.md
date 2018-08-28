# critteremote
WoW Addon BP Critter Emote

This addon will have your summoned non-combat pet do fun and random things. The terms 'critter' and 'pet' refer to non-combat pets in this file.

When you have a pet out every so often it will emote something fun. You can have your pets become more interactive by having them emote custom actions by using /ce instead of /emote.

Your pets will now respond to in-game emotes.  Target your summoned pet and try /wave or /angry.

Your pet will do an emote every five to ten minutes as long as you are not in combat or a pet battle.
Pets are fun things, if you target something else, they just might do or say something to the target.

If you find any typos, or mistakes please let me know and I'll fix them.

If you would like to add your own emotes edit the file CritterEmote_Emotes.lua You can also delete emotes you just don't like. It is important to note that when you do make changes to the .lua that new updates from Twitch will erase them. You may want to save them to a text file or, better yet, send them to me and I'll review them to add to or consider their removal from the main release :)

Usage:
/ce - have your non-combat pet perform a random emote.
/ce <message> - have your critter emote your <message>.
/ce [options] - perform the various option:
[options] =
info     : displays Critter Emote information.
help     : displays this help.
off      : turns the random emote off.
on       : turns the random emotes back on
options  : Displays current options
silly    : Toggles silly emotes
jokes    : Toggles joke emotes
locations: Toggles location emotes
songs    : Toggles song emotes
faction  : Toggles faction emotes
        
Currently emotes can be in the following category:

Default - for all Battle Pets, Companion Pets, Vanity Pets (critters)
type - subtype of critter ( cat )
name - specific critter ( Lil' K.T. )

Under each category there is 
emote - such as /cry or /wave
random - anything
target - if something is targeted

Version 1.14
Updated to 8.0.1 Battle for Azeroth
Made a fork to Chinchilla Critter Emote so add-on could be updated

Version 1.13
Updated to Legion
Included updates from Acidfrost59
Big thanks to Acidfrost59 for adding many more emotes and fixing some minor issues!

Version 1.11a
Fixed some typos's added user requested emotes.

Version 1.11
Works with 6.2

Version 1.10a
One can now just turn off/on random emotes via: /ce random_off or /ce random_on
Fixed Typos

Version 1.10
Works with 6.1.0

Version 1.9b/c/d
Fixed typos

Version 1.9a
Invaded by the old ones!
(more emotes)

Version 1.9
More emotes! (and corrections)

Version 1.8a
Now respects custom pet names.

Version 1.8
Works with 6.0
Back again Chin is back Tell a friend

Version 1.7b
Works with 5.2.0

Version 1.7a
Fixed a bug where Critter Emote would crash if no pet was out.

Version 1.7
Updated to MoP!
Big Thanks to Liz.

Version 1.6
Updated by Jî - Sylvanas
Big Thanks!
Spellchecked (might have missed a few, but did alot) added all currents pets into the roster. Gave lil' ragnaros and gregarious grell quite alot of custom emotes.

Version 1.5b
Updated for 4.3 version of the game.

Version 1.5a
Updated for 4.1 version of the game.

Version 1.5
Rewrite of Emote Database.  This makes it easier to add new types without having the file size grow too large.  Also speeds things up slightly.
Added a lot more responsive emotes.

Version 1.4
Snake type creatures now have a full personality
Now remembers your state between sessions
Emotes now have a category.  This way you can turn on and off certain types of emotes.
silly, locations, jokes, songs
/ce help for more info on this.

Version 1.3
cat type creatures now have a full personality
Fixed a bug where pet types and names were not correctly being called in the table.

Version 1.2
Added more emotes.
Fixed typos
Random interval time is longer.

Version 1.1
Added additional emotes.
Removed some debugging info.
Now seed the random a bit better.

Version 1.0
Initial Version
