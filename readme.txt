ErrorNull Zombies (enZombies) v2.6
https://community.7daystodie.com/topic/24594-enzombies-more-zombie-variations/


ErrorNull Zombies (enZombies): 
This mod has been updated for Alpha 20 and adds much more zombie variations to the game, using the UMA archetype method most notably showcased by the Snufkin's Custom Server Side Zombies - PLUS mod maintained by arramus. All the UMA Zombies by khzmusik are also included in enZombies. The goal of this mod is to always be server-side, thus only needs to be installed on the server, and not on the individual clients. These zombies are meant to be your average walkers and crawlers to complement the existing vanilla ones.. though stronger and boss-level zombies are slowly being added. Each enZombie also has their own feral, radiated and crawler variant. The exception are zombies that wield weapons and some that wear hats.

enZombies spawn out in the terrain based on the biome, with each zombie group sporting a unique color theme that matches the biome.  So you will find foresty zombies in the forest, deserty zombies in the desert, snowy zombies in the snow, and so forth. enZombies also spawn as sleepers inside the POIs, though unfortunately there's no easy way to spawn them as sleepers based on biome. So you see a wider range of enZombies appear inside the POIs.  

The short challenge quests are an underutilized feature in the vanilla game, and enZombies appear within them as well. New challenge quests have also been added to showcase the new zombies. All new quests are simply found as items within the usual loot containers where vanilla quests are found. Many more quests are planned.

- Goblin Raid
- Forest Goblin Raid
- Desert Goblin Raid
- Snow Goblin Raid
- Red Goblin Raid
- Wasteland Goblin Raid
- Business Meeting Gone Wrong


COMPATIBILITY: I removed and redid most of the vanilla zombie groups in entitygroups.xml, created a few of my own, and redid a number of the main spawners in gamestages.xml. For this reason, I don't expect this mod to work well with any mods that also make changes to these two XML files. The only mods I do officially support are in the Add-Ons section below. If you are getting errors or strange glitches while using non-supported mods with enZombies, I'll be glad to take a glance when I get the chance, but making sure other mods work with enZombies is not my current focus. If I see enough demand, I might spend the time to modify a non-supported mod to work with enZombies and thus will be included as an official Add-On mod below. 


USAGE: You may use my mod as it is presented, or you are also welcome to disregard my spawning customization and just pull my zombies (from archetypes.xml and entityclasses.xml) and merge them into your own mod. But, I'd appreciate if you credit me in that case like mentioning my mod or the link on your website, discord or forum post. I love making these custom zombies and plan to continue for a long while, but it does take lots of time and effort. 


ADD-ONS: These are optional mods created for enZombies. The main enZombies mod must be installed in order for these Add-Ons to work.

*** enZombie Harvest Add-On **** This mod adds the ability to harvest all enZombies for resources (eg. cloth, rotten flesh, bones) when they are defeated. Zombies that carry bags or backpacks can also be looted before harvesting their corpses. To counter-balance the added abundance of resources from zombie harvesting, this mod also slightly increases the resource requirements of any recipes that rely on them. https://github.com/ErrorNull0/enZombieHarvest

*** enZombie Settings Add-On *** A collection of small mods that allow adjusting certain zombie settings: No Nudes, Attack Range, Wilderness Spawn Amount, and Wandering Horde Spawn Amount. Download the add-on package and take the specific folder that matches the setting you wish to adjust and place it into your 7 Days to Die "Mods" folder. https://github.com/ErrorNull0/enZombieSettings


Patches: These will patch someone else's mod to work with enZombies. Go to the enZombiePatches GitHub page and you will see a collection of available patches. Download the package. Take the specific folder that matches the patch you want and place it into your 7 Days to Die "Mods" folder. Don't forget, you need to have the main enZombies mod installed as well as the other mod you are trying to patch. https://github.com/ErrorNull0/enZombiePatches

*** Robeloto's Custom Zombie's Patch *** This patch does two things: 1) Modifies the Robeloto custom zombies mod to work with enZombies. It appends the new spawning groups required by enZombies into the entitygroups.xml file. This results in more control over which Robeloto zombies spawn in which biome situation. 2) Provides the option to enable zombie body harvesting for the Robeloto zombies.

*** Snufkin's Server Side Zombies PLUS Patch *** This patch does two things: 1) Modifies the Snufkin custom zombies mod to work with enZombies. Specifically, it appends the new spawning groups required by enZombies into the entitygroups.xml file. This results in more control over which Snufkin zombies spawn in which biome situation. 2) Provides the option to enable zombie body harvesting for the Snufkin zombies.

*** Zulk Zombie Patch *** This patch does two things: 1) Modifies the Zulk zombie mod to work with enZombies. Specifically, it appends the new spawning groups required by enZombies into the entitygroups.xml file. This results in more control over which Zulk zombies spawn in which biome situation. 2) Provides the option to enable zombie body harvesting for the Zulk zombie.

*** Undead Legacy v2.5.44 Patch *** This patch allows enZombies and Undead Legacy to run together. The conflict areas that is patched is the spawning.xml and gamestages.xml files. Instructions: Download the patch package from the link above. Go into the folder "UndeadLegacyPatch". Note that contains another folder called "UndeadLegacy_Content01". Be sure that this folder and it's contents OVERWRITES the existing same folder that's already in your Mods folder. This is what will make the needed changes to your current install of Undead Legacy to work with enZombies. Tested with Undead Legacy v2.5.44. Subquake's Undead Legacy mod page.


KNOWN ISSUES: There are some interesting bugs when working with UMA zombies and molding them from the archetypes.xml. It's not unique to enZombies and are present in any mod that uses UMA style zombies - for example, the Snufkin mod also contain some UMA zombies which will experience these bugs. In my opinion, the relative ease in creating and modifying these zombies outweigh the quirks: 

- UMA zombies fly amazing distances when struck with a powerful attack. Their physics seem to be more 'floaty' compared to the vanilla zombies. This also results in the occasional zombie getting stuck into nearby walls and bars when explosions and powerful attacks send them rag-dolling overhead. To some this is a bug, to others this is a feature. ??

- UMA zombies do not collide with player vehicles whether driven or parked. So the zombies will simply walk right through them. This behavior does not occur with the abandoned POI vehicles that litter the landscape.. UMA zombies interact with them like normal.

- UMA zombies don't get shocked when walking into electric fence traps.. not really, at least. It seems that if they are knocked down while on the fence, they will occasionally get shocked! Stun batons behave normally and shock the zombies just fine.

- UMA zombies appear to cause a 'micro-freeze' or stutter in the game each time a set number of them are spawned. This was not the case (or it was very insignificant) in Alpha 19. The number of zombies that trigger this stutter seem to range from 5 to 8. Thus, while exploring POIs and encountering sleeper zombies, or fighting through horde night, there will be a short stutter when every 5th to 8th UMA zombie is spawned in. The severity of the micro-freeze might depend on your system specs, but it's not completely certain at this point.
 
- There is a NullReferenceException error that can occur when sleepers are spawning inside POIs. Majority of the incidents are occurring during trader quest, and can sometimes even result in a sleeper zombie being spawned invisible - which can be a vanilla zombie and possibly UMA zombie. Unfortunately, this zombie cannot be killed and if part of a Clear quest will cause the quest to fail. This issue is still being investigated. Troubleshooting is challenging as this NRE error appears intermittent and not tied to a specific POI or specific UMA zombie. However, it only occurs when UMA zombies are spawning as sleepers. If you encounter this NRE error - please take a screenshot and let me know which POI and if the error was repeatable later at the same POI. This will help with the research.

Let me know if it helps or even if it does not help.. that information will be useful for further research. Thanks!


CREDITS: Thanks to @Snufkin for starting it all with your Snukfin's Server Side Z(S)ombies mod, and thanks to @arramus for keeping it going with the Snufkin's Custom Server Side Zombies - PLUS mod. I studied these mods for weeks to figure out how it worked and gave me inspiration to contribute as well. Also thanks to @khzmusik who gave me permission to add his UMA Zombies into enZombies. Much appreciated!


MENTIONED MODS:
Snufkin's Custom Server Side Zombies - PLUS
https://community.7daystodie.com/topic/22698-snufkins-custom-server-side-zombies-plus/
khzmusik's UMA Zombies
https://community.7daystodie.com/topic/24348-a19-khzmusiks-modlets/
Robeloto's Custom Zombies
https://community.7daystodie.com/topic/12229-robelotos-a20-modlets/


enZOMBIES DOWNLOAD & INSTALL: Go to the enZombies GitHub page. Download the package and unzip the conents to your 7 Days to Die "Mods" folder. https://github.com/ErrorNull0/enZombies

Version 2.6 Update:
-created XML builder program to automatically generate sliding prob values for entitygroups
-used xml builder to redo the following spawn groups to have custom prob values but maintain vanilla gamestage labels and progression: badassHorde, badassOnlyHord, scoutHorde, sleeperHorde, and feralHorde.
-fixed bug that made male bellies look all pregnant
-made all enZombies a bit taller and have bigger feet to better match vanilla zombie proportions
-updated code that used outdated UMA mesh plant_fiber_shirt
-updated code that used outdated UMA texture fiberCloth_chest
-increased the wilderness random zombie spawn amount for all biomes 
-made female joggers move faster
-made vanilla lumberjack taller
-removed knockdown ability from all zombies except for giants
-reduced knockdown prob of giants from 50% to 25%
-added knockdown prob of 50% to vanilla bear and zombie bear 
-updated KHz zombies to have HP/XP consistent with enZombies
-ensured female KHZ zombies have dancetype 2 (males have dancetype 1)
-renamed enUtility1, enUtility2, enUtility3 to enUtilityMale1, enUtilityMale2, enUtilityMale3
-added enUtilityMale4, enUtilityMale5, enUtilityFemale1, enUtilityFemale2
-added enFootballMale3 and enFootballMale4
-added 2 male and 2 female school zombies
-lots of code cleanup
