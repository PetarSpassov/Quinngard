# Quinngard
An extensive PVE-oriented balance and QoL mod for Northgard by Shiro Games, Quinngard seeks to add quality of life and balance changes to the PVE modes of the game, especially Bifrost.

## __Disclaimer__
None of the assets used in this mod belong to me. All credit and rights go to the creators of Northgard, Shiro Games. This mod is merely a harmless modification of game files meant to be used in solo and cooperative PVE play.

All rights to music used from outside the game belong to their respective creators. Credit for music used from outside Northgard has been given where appropriate.

Special thanks to Manevolent, whose setup, patience, and guidance made this possible.

## __Installation__
Download `res1.pak` and place it within your Northgard folder. For Steam, this would look something like this: `X\Steam\steamapps\common\Northgard`

You can easily reach it by right-clicking the game in your Steam Library and pressing `Manage -> Browse local files`. You should now have `res.pak` and `res1.pak`.

NOTE: If you already have a `res1.pak`, you will need to rename this one to `res2.pak`. The game reads `res.pak` files in numerical order, starting from `res.pak` -> `res1.pak` -> `res2.pak`, etc. If you have `res.pak` and `res2.pak`, the game will NOT load `res2.pak`.

### **Will this mod work in co-op?**
Yes. You can play co-op with your friends, but you must launch the game in Peer-to-Peer, and they must also have this mod installed. If you play on servers, the mod will not be loaded.

### **Will this mod affect multiplayer?**
Only if played in Peer-to-Peer, so it will not impact Ranked. Only custom games hosted by *you* in Peer-to-Peer will be affected. To avoid this, refer to the uninstallation instructions below.

## __Uninstallation__
Simply delete `res1.pak` (or whatever you named this pak to) from the folder.

# Changes
## __Building Changes__
- Carved Stone building cost reduced (10 -> 5 stone)
- Woodcutter's Lodge stone cost to upgrade reduced from 10 to 5.
- Lumber Camp wood cost to upgrade reduced from 100 to 50.

## __Clan Rebalancing__
- **Bear**
  - Harpoons now replaces Eradication instead of Shiny Happy People.
- **Kraken**
  - Relic-summoned Kraken forewarning reduced from 6 to 3 months.
  - Kraken event feast duration increased from 2 to 3 months.
- **Stoat**
  - Mutual Effort now replaces Trading Caravan instead of Medicine.

## __Conquest__
**__Generic Bonuses__**
- Free tools are now only offered for Miners.
- "+20% unit production" will no longer appear for Smiths and Miners.
- "+30% defense for unit" no longer appears for Axe Throwers, Trackers, Archers, and Foxskins.
**__Clan Specific__**
- **Eagle**
  - Changed the Conquest bonus icons to the correct ones. They already existed in the files, but were unused for some reason.
  - Glacial Winds now displays the slow amount in its tooltip.
- **Bear**
  - First Conquest bonus now increases the Armoured Bear's attack and defense by ~~10%~~ -> 20%
- **Horse**
  - Horse 2nd Conquest Bonus: ~~+10%~~ +20% bonus production in zones with a warchief
- **Stoat**
  - Lords, Domain Lords, and War Lords are now excluded from all Military-related conquest bonuses (+atk, +def, -cost)

## __Bifrost__
- Carved Stone and Offering Well are now starter buildings. They have been removed from the reward pool.
- Number of secondary objectives increased from (2,2,3,3) to (3,4,4,4) (for 1/2/3/4 players respectively)
  - Niflheim number of islands increased to match
- Secondary objectives (Pillar, Beacon, Wyvern) now offer 2 choices each, one is picked for the whole team via percentage team vote.
  - If three people vote and the split is 66%-33%, there is a 66% chance the first bonus will be picked and a 33% chance the second bonus will be picked.
  - **IMPORTANT NOTE: DO NOT PRESS "CHOOSE" MORE THAN ONCE PER PERSON WITH 2+ PLAYERS, IT *WILL* LOCK YOUR GAME**
- Secondary objectives minimap icon updated
- Beacon of Light now offers several unused tower-related bonuses. The starting resource bonuses from Beacon of Light were moved to Pillar of Glory.
- The Hidden Bifrost now opens 33% faster (four months with three scouts)

### __Realms__
- All realms have had their music tracks updated for a fresher and more unique listening experience. Music used that comes from outside Northgard:
  - Miklagard intro - "Media Vita" from Manor Lords
  - Muspelheim - "Mjolnir" by Alexander Nakarada
  - Nidavellir - "King Gylfi's Settlement OST" from Titan Quest Ragnarök
- **NEW REALM: Helheim!** Helheim is the cold and unforgiving land of the restless dead. Great power awaits those who step into this cursed land, though beware: many have entered, but none may leave...
  - A special challenge realm where, if you want your rewards, you will need to FIGHT for them! All objectives are much harder, the map is teeming with undead foes, and they are more aggressive. Don't blink, because this realm does not let go of those who close their eyes...
  - Four new secondary objectives, a new enemy unit, a new military unit, and two new buildings!
  - Each secondary objective (except one) gives TWO rewards instead of one, *and* they are more powerful! Surely, all this power is worth the struggle...?
- **NEW REALM: Miklagard!** Miklagard, formerly a city of great riches, has fallen victim to the assaults from the gods. What law there once was has been replaced by pillagers and thieves.
  - The map is full of beaches, where most resources are concentrated. Befriend the Marmennill for a choice of unique new buildings which will allow you to commune with them in the future for great riches or knowledge!
  - Money is a dominant force here. Mine the gold deposits and use the extra cash to purchase your knowledge! Beware, though, mercenaries will come after you and your riches...
- Vanaheim
  - Piercing Light event replaced by Healing Rain (because our eyes and FPS have suffered enough)
  - Dens can now be closed (until Shiro fixes map generation)
  - Gullveig (Boss) rebalanced slightly:
    - Bomb on Unit countdown increased from 8 to 12 seconds.
    - Delay between explosions in collapsing circle increased from 1.75 seconds to 2.5 seconds. Damage increased from 60 to 80.

### __Blades, Towers, Barricades__
- Description of all Blades, Towers, and Barricades has been updated to include all relevant information.
- All Blades, Towers, and Barricades now show their effects before being selected and their names have been clarified. Their selection and ability icons have been updated.

**Blades**
- Holy Blades cooldown reduced from 30 to 10 seconds.
- Thunder Blades name changed to Lightning Blades. Units affected increased from 3 to 5.
- Venom Blades chance increased from 20% to 30% and damage per second increased from 0.2 to 0.3.
- Confusion Blades cooldown per target reduced from 15 to 10 seconds.
- Vanaheim Blades chance decreased from 25% to 20%, duration reduced from 4 to 1 second, and cooldown increased from 10 to 12 seconds.
- Storm Blades chance decreased from 25% to 10%.

**Towers**
- Towers now cost more to build (50/20 -> 65/30) and have higher upkeep (mod 1.5 -> 1.75), but have more HP and defense (150/15 -> 180/18).
- Guardian Watch Towers no longer have lower upkeep.
- Lightning Tower targets affected increased from 3 to 5.

**Barricades**
- Barricades now build much faster and cost no upkeep.
- Damage dealt by Barricades reduced from 15% to 10% of the enemy's max HP.
- Damage taken by barricades when a mob walks through them reduced by 50%.
- Lightning Barricade targets affected increased from 3 to 5.
- Venom Barricade damage increased from 0.3 to 0.6 per second.
- Frost Barricade duration increased (2 -> 4 seconds) and slow increased (-15% -> -30%).

### End of Year bonuses
- End of Year bonuses per map reduced from 4 to 3.
  - *Modder note: As the number of secondary objectives has increased, and average reward quality has been drastically increased, it should be around the same power level to leave 803 instead of 804. This should make games a lot shorter and make people feel less forced to stay until 804.*

**__General__**
- Free tools are now only offered for Miners. They should appear less often (weight 4 -> 2)
- "+20% unit production" will no longer appear for Smiths, Miners, and Brewers. It should appear more often (weight 3 -> 4)
- "Food Silos store +40% and bonus is increased by +20%" should appear more often (weight 1 -> 5)
- "+30% defense for unit" no longer appears for Axe Throwers, Trackers, Archers, and Foxskins.
- "+30% attack power for unit" should appear more often (weight 1 -> 2)
- "+3 Warband" should appear less often (weight 3 -> 2)
- "Relic forge time and price is reduced by 60%" should appear more often (weight 2 -> 5)
- All food buildings should appear more often (weight 2 -> 4) except Fishing Cabin (weight 1, unchanged).
- Fishing Cabin can now be offered even if you have other fishing buildings.
- All military camps should appear much less often (weight 5 -> 1)
- "-60% attacks from neutral zones" will no longer appear
- Brewery no longer requires you to have another happiness building in order to be offered

**__Clan Specific__**
- **Stag**
  - Stag 1st Conquest Bonus no longer appears if your team has no Hall of Skalds in Bifrost
  - Stag 1st Conquest Bonus no longer has a ridiculous weight (500 -> 15)
  - Stag 2nd Conquest Bonus should appear more often (weight 15 -> 30)
  - Stag 2nd Conquest Bonus will now only appear if the Stag player can build a silo.
  - Hall of Skalds will now appear even with no Stag in team (weight 2), and more often with Stag in team (weight 1 -> 5)
- **Goat**
  - Goat 2nd Conquest Bonus will no longer appear if you don't have Defensive Strategy
  - Removed "Food Trade" lore from the reward pool
- **Raven**
  - Removed the 1st Conquest Bonus from the reward pool
- **Wolf**
  - Added "Spoils of War" lore into the reward pool (weight 5, clan weight 20)
  - "Field Rations" lore reduction, er, reduced from -75% to -35%.
- **Bear**
  - Bear 2nd Conquest Bonus will no longer appear if you don't have Shieldbearer Camp
- **Boar**
  - Boar 2nd Conquest Bonus can now appear (there was an error in the code where instead of Altar of Kings, it was looking for Altar of the Gods)
  - Boar 2nd Conquest Bonus should appear more often (weight 15 -> 40)
  - Removed "Bartering" lore from the reward pool
  - Mender's Hut now produces Faith for Kingdoms. (Formerly: Nothing)
- **Snake**
  - Signy can now scorch the boss tile.
- **Dragon**
  - Removed "Capture" lore from the reward pool
- **Horse**
  - Horse 2nd Conquest Bonus should appear a bit less often (weight 30 -> 22)
  - Horse 1st Conquest Bonus should appear a bit more often (weight 22 -> 30)
- **Rat**
  - Rat 1st Conquest Bonus should appear much less often (weight 15 -> 5)
  - "Healing Fire" lore should appear much more often (weight 30 -> 50)
- **Lynx**
  - Lynx 1st Conquest Bonus will no longer appear if you don't have Hunting Lodge
- **Ox**
  - "Warcraft" lore Military Exp conversion reduced (lore: 0.5 -> 0.3) (fame: 0.2 -> 0.1)
- **Kraken**
  - Removed "Knowledge from Beyond" lore from the reward pool
  - "Near the Sea Spirit" lore should appear more often (weight 40 -> 60)
  - "Foresight" lore Wyrd gain increased from +1 to +2, and female villager chance raised from 50% to 75%.
  - Removed the following bonuses from appearing for Kraken:
    - Happiness lores (Journeymen, Protector of the Land, Osmosis, Quality of Life, Training Field)
    - Brewery, Stove, Hall of Skalds (kingdom happiness buildings shouldn't appear for it to begin with)
- **Squirrel**
  - "Economics" lore will now only show up if there is a Squirrel in the game
  - Stove is now a starter building and has been removed from the reward pool.
  - "Rumor-mongering" lore can now only appear for Squirrel. It should appear less often (weight 25 -> 15)

## __Known Issues__
- **One person pressing "Choose" more than once on Team Vote objectives will not unselect the choice and will instead lock the game.**
  - Nothing I can do about this, sadly. It has just not been coded properly on Shiro's side, which may explain why it went unused. However, I think having the resolve to only click "Choose" once makes this cool mechanic worth having.
- **Hunter-related bonuses (e.g. +20% production) may appear even if you didn't bring a Hunting Lodge or don't have the Spoils of Plenty lore.**
  - This is not an issue with the mod, you will notice the same occurs in vanilla. The reason for this is because for the Spoils of Plenty lore to work on any clan, all clans need to have Standard Lure enabled from the start, and the game factors it in even if you can't possibly build it. Submit a bug report and let's get this fixed from Shiro's side.
  - All +20% production bonuses are bundled into one bonus, so it is not as easy as saying "Don't show +20% Hunter production if you don't have the building or the tech".
- **Bear spawns with fewer secondary objectives on Niflheim (and somewhat rarely, no guaranteed fish), most commonly in solo play.**
  - This is because of Bear's guaranteed fish spawn messing with the map seed, so sadly I can't do anything about it. Even adding another island would not work, as it just won't be able to spawn the portal.
- **Custom buildings always show up for all clans outside of Bifrost.**
  - This stuff seems almost hard-coded, I couldn't find anything about the Bifrost-specific buildings to mimic on this one. I'll investigate it eventually, but for now, just keep it in mind if you launch other modes with the mod on. (Though you don't have much reason to do that...)

### __Helheim__
- **Trained True Valkyries do not have a portrait.**
  - This is because there is no portrait for women, but if I add one, the game starts crashing. I don't think there is anything I can do about this. :(
- **The Nidavellir Mine shows that you can recruit more miners even though you have no gemstones left.**
  - This is because of several aspects of this being jankily hardcoded on Shiro's side. For it to even *consume* the resource, I had to code them as military units (even though they take up no warband slot, etc.). Some limitations are just forced upon me, I don't think there is much I can do about this one. **It still works as intended and causes no crash**, so don't worry. If you try to assign a miner when you have no gemstones, the unit will simply have a brainfart next to the mine.

### __Miklagard__
- **You can't use Shipyards and Harbours to trade with Marmennill.**
- **Marmennill Cove shows up on land and their name is NULL, unlike in the Conquest mission where they appear.**
  - A lot of rules related to the Marmennill - including how their cove changes terrain, how trade with them works, and how their names are assigned - seems to come from the Conquest rule that spawns them in to begin with. Sadly, this rule crashes Bifrost. On the bright side, you can befriend them with scouts with no issue, and their 30 relation benefit (+20% production on shores) works as expected.

# Other Mods by Me
- [NoMoreFog](https://github.com/PetarSpassov/NoMoreFog) - Removes intrusive fog from multiple weathers (e.g. storm, blizzard)
