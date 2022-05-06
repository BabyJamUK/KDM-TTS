# kdm-tts
Source for my Kingdom Death: Monster mod for Tabletop Simulator (https://steamcommunity.com/sharedfiles/filedetails/?id=2112101994)
This is a direct copy of MeixDev/kdm-tts source for me to learn both lua and Kingdom Death Monster
Updates for my version below, for all updates by Mei go to https://github.com/MeixDev/kdm-tts

# KDM_VERSION = "1.4.9"
* Added another context menu to Showdown Monster ('End Monster Turn').  I have included a round and player/monster turn counter.  If a player is knocked then it will automatically flip to standing after the monsters next turn has finished

# KDM_VERSION = "1.4.8"
* Added context menu to Monster Figure on Hunt ('Begin Showdown') to start showdown against hunt monster
* If hunting the White Lion and certain hunt cards are played (White Lion Cub as example), then showdown will setup with this card already in play as per rules.  Note that if the card does not take effect then turn it face down so it will be ignored

# KDM_VERSION = "1.4.7"
* Added new Context Menu Item to Monster Figures ('Players Win')
* Automated Rewards from winning using the conext menu, this includes Basic Resources, Monster Resources, Strange Resources, Hunt XP, Weapon Proficiency and Endevours.
* note: Not all rewards have been added to game (even core), you may get errors or have to still manually add until a later release

# todo
* 'Players Win' context menu will error on expansion monsters, need to update this
* with 1.4.9 I wanted to add this to the Battle Ui but not learnt enough to get this running.  I also introduced some global variables which might not be the right place to go and might need looking at
