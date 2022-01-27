ErrorNull Zombies (enZombies) v2.5
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


ADD-ONS: These are optional mods created for enZombies that are officially supported. The main enZombies mod must still be installed in order for these Add-Ons to work. Follow the link shown at the top of this readme file. On that page, scroll down to the Add-Ons section, click on Reveal hidden contents, and click on the download link for the specific add-on you want. Download the zip file for the add-on and extract the contents to your 7 Days to Die "Mods" folder. 

*** Snufkin Zombies Plus *** 
This mod adds all Snufkin community zombies alongside enZombies. The Snufkin zombies will spawn outside in the various biomes, within the screamer hordes, the wandering hordes, and the blood moon horde night.. along with the enZombies. The Snufkin zombies do not spawn inside POI's like as sleepers, but I have included code within ENTITYGROUPS.XML where you can enable it. This add-on also makes the "Snufkin Raid" challenge quest available, where you must fight through all the Snifkin zombies in order face the boss of them all - the evil scientist Snufkin. Note: Do not use the main "Snufkin Server Side Zombies - PLUS" mod together with this Addon.  To follow the continued development of the main Snufkin Server Size Zombies Plus mod that is managed by @arramus, view the main mod page here. https://community.7daystodie.com/topic/22698-snufkins-custom-server-side-zombies-plus/

*** enZombie Harvest ***
This mod adds the ability to harvest all enZombies for resources (eg. cloth, rotten flesh, bones) when they are defeated. To counter-balance the added abundance of resources from zombie harvesting, this mod also slightly increases the resource requirements of any recipes that rely on them.  

*** No Nudes ***
There are a number of female enZombies that show lots of skin. If this is more than you prefer, this mod will cover them up by adding a bra top for their chest, and the default underwear shorts for their bottoms. Download the zip file and extract the contents to your 7 Days to Die "Mods" folder. 


KNOWN ISSUES: There are some interesting bugs when working with UMA zombies and molding them from the archetypes.xml. It's not unique to enZombies and are present in any mod that uses UMA style zombies - for example, the Snufkin mod also contain some UMA zombies which will experience these bugs. In my opinion, the relative ease in creating and modifying these zombies outweigh the quirks: 

- UMA zombies fly amazing distances when struck with a powerful attack. Their physics seem to be more 'floaty' compared to the vanilla zombies. This also results in the occasional zombie getting stuck into nearby walls and bars when explosions and powerful attacks send them rag-dolling overhead. To some this is a bug, to others this is a feature. ??

- UMA zombies do not collide with player vehicles whether driven or parked. So the zombies will simply walk right through them. This behavior does not occur with the abandoned POI vehicles that litter the landscape.. UMA zombies interact with them like normal.

- UMA zombies don't get shocked when walking into electric fence traps.. not really, at least. It seems that if they are knocked down while on the fence, they will occasionally get shocked! Stun batons behave normally and shock the zombies just fine.

- UMA zombies appear to cause a 'micro-freeze' or stutter in the game each time a set number of them are spawned. This was not the case (or it was very insignificant) in Alpha 19. The number of zombies that trigger this stutter seem to range from 5 to 8. Thus, while exploring POIs and encountering sleeper zombies, or fighting through horde night, there will be a short stutter when every 5th to 8th UMA zombie is spawned in. The severity of the micro-freeze might depend on your system specs, but it's not completely certain at this point.
 
- There is a NullReferenceException error that can occur when sleepers are spawning inside POIs. Majority of the incidents are occurring during trader quest, and can sometimes even result in a sleeper zombie being spawned invisible - which can be a vanilla zombie and possibly UMA zombie. Unfortunately, this zombie cannot be killed and if part of a Clear quest will cause the quest to fail. This issue is still being investigated. Troubleshooting is challenging as this NRE error appears intermittent and not tied to a specific POI or specific UMA zombie. However, it only occurs when UMA zombies are spawning as sleepers. If you encounter this NRE error - please take a screenshot and let me know which POI and if the error was repeatable later at the same POI. This will help with the research. To assist in troubleshooting, please download this "No Decos" mod which removes any prefab attachments to the zombies: https://drive.google.com/file/d/15C47k0XIG3EyNR5jTj8JuttaLnU5l7Qh/view?usp=sharing

Let me know if it helps or even if it does not help.. that information will be useful for further research. Thanks!


CREDITS: Thanks to @Snufkin for starting it all with your Snukfin's Server Side Z(S)ombies mod, and thanks to @arramus for keeping it going with the Snufkin's Custom Server Side Zombies - PLUS mod. I studied these mods for weeks to figure out how it worked and gave me inspiration to contribute as well. Also thanks to @khzmusik who gave me permission to add his UMA Zombies into enZombies. Much appreciated!


MENTIONED MODS:
Snukfin's Server Side Z(S)ombies
https://community.7daystodie.com/topic/17992-snukfins-server-side-zsombies/
Snufkin's Custom Server Side Zombies - PLUS
https://community.7daystodie.com/topic/22698-snufkins-custom-server-side-zombies-plus/
khzmusik's UMA Zombies
https://community.7daystodie.com/topic/24348-a19-khzmusiks-modlets/


enZOMBIES DOWNLOAD & INSTALL: Follow the link shown at the top of this readme file. On that page, scroll down to the Download & Install section and click on the download link to start the download. Unzip or extract the contents of zip file into the 7 Days to Die "Mods" folder. 

Version 2.5 Update:
- renamed enSpider196 (the spider zombie using HD Tom clark mesh) to enSpiderTom 
- re-added vanilla non-HD zombies from Alpha 19.6: zombieLab, zombieScreamer, zombieSoldier, and zombieSpider. renamed to enLab196, enScreamer196, enSoldier196, enSpider196. created feral and glowing radiated versions. 
- restored Goblin Raid quests and Businessman Raid quest. They can appear in same lootcontainers as treasure maps.
- fixed error with BusinessManBoss zombie.
- updated entitygroups.xml code so that enZombies are more compatible with unsupported mods that also modify the vanilla entitygroups.xml file.
- redid wandering hordes to consist of more unique zombie groups (including KHz zombies) and removed wolves to reduce meat harvesting
- Fixed gamestage.xml code for ZombieBadassGSHorde group. This should fix some NRE errors.
- fixed enFemaleFlamerRadiated missing radiated/green texture colors
- gave all female enzombies dancetype 2 (that twirly dance)
- reduced on-screen buff effects of green screamer3
- slightly reduced chance of hiker spawns in the forest wilderness (sleeper, scout horde, or bloodmoon horde spawning unchanged)
- slightly reduced chance of miner spawns in the desert wilderness (sleeper, scout horde, or bloodmoon horde spawning unchanged)
- made a few zombies look fatter: enFarmerFemale2, enForestMale3, enSnowMale3, enBusinessman4


Version 2.4 Update:
- custom challenge quests have been temporarily disabled due to changes in Alpha 20
- reworked / removed code that referenced entities that were removed (or renamed) for Alpha 20: zombieFootballPlayer, zombieOldTimer, zombieCheerleader, zombieSnow, zombieFarmer, zombieStripper, legendaryZombieBusinessMan, legendaryZombieUtilityWorker, legendaryZombieLab, invisibleAnimal, invisibleAnimalEnemy
- added wildling girl zombie (spawns in forest, burn forest, and caves)
- santa and santa's helper (spawn only in the city of snow biome at night)
- added feral versions of a few kHz UMA zombies, for purpose of spawning in the city and downtown locations: khzMiguel, khzEmma, khzMaria, and khzCharlotte 
- added feral versions of all male and female punk zombies, for purpose of spawning in the city and downtown locations
- added the spider version of vanilla "tom clark" zombie (spawns in the same places as the new HD spider zombie)
- modified spawning groups for new vanilla lumbergack and existing enZombie football zombies to spawn in a a few more locations.
- update all code to include any other changes to entitygroups, spawning, gamestages, quests, and loot from Alpha 20 (there were quite a few)
- tweaked physicsbody code for all for all enZombies so they fall a bit faster and closer to the ground, so they behave a bit less floaty
- gave some of the larger and more powerful zombies a 50% chance to knowdown player: all giants, businessman boss, radiated miners, lab creature male 4, radiated lumberjacks, radiated bikers, radiated cowboys, radiated male flamer, etc
- all zombies have radomized HP which can vary from +0% to +20%
- all animals have radomized HP which can vary from -10% to +10%
- updated zombie harvest, snufkin zombies, and no nudes add-ons to be compatible with all changes to main enZombies mod