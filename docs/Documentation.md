**- Table of Contents -**
===============
 - [**1. Opening Sequence**](#opening)
 - [**2. Overworld Navigation and Gameplay Changes**](#overworld_changes)
 - [**3. Gen 2 Glitch Fixes**](#fixes)
 - [**4. Battling**](#battling)
 - [**5. Residences and Decorations**](#residences)
 - [**6. New Features and Quality-of-Life Changes**](#features)
 - [**7. Move Tutors and other helpful NPCs**](#helpful_npcs)
 - [**8. New options**](#new_options)
 - [**9. Map changes and additions**](#map_changes)
 - [**10. Obtainability and Compatibility**](#obtainability)
 - [**11. Music**](#music)
 - [**12. Shiny Hunting**](#shiny_hunting)
 - [**13. Renewable Resources, E4 Resetting and Trades**](#renewables)
 - [**14. Marts**](#Marts)
 - [**15. HMs**](#hms)
 - [**16. Misc stuff**](#misc)

**- Preface -**
===============

This is the main documentation page, designed to detail the majority of new features in the game, without spoiling the entirety of it. Most things are written in the context of having played Gen 2, so if you haven't played it before, then some features may be more difficult to understand.

There's a lot of very minor changes that aren't going to be covered here. [Changelogs](Changelogs.md) will have details on a per-patch basis, but you are encouraged to play the game and discover what Crystal Clear has to offer on your own!

If you're looking for more specific information, [the index](index.md) may have what you're looking for. Throughout this document, there will be hyperlinks to other sections of the documentation, which may contain light spoilers, so be aware.

Last but not least, before asking a question in the Discord, please **use the search feature.** A lot of things have been covered in the documentation, FAQ, and discussions in the server. Help us help you.

 \- ShockSlayer

**1. Opening Sequence**<a name="opening"></a>
========================
 - New intro sequence, animation, music, title screen, etc.

### New Game:
 - Start in **any town** in Johto **or** Kanto. 
	 * This also gives you a customizable residence in that town! (See: [Residences](#residences))
	 * Each area has a matching difficulty rating, so choose wisely!

### Starters:<a name="starters"></a>
 - Can select from **30** different starters, or inject your own! (See the \#releases Discord channel for more info)
 - Upon entering the overworld, you'll be prompted to save immediately for soft resetting. (See: [Shiny Hunting.](#shiny_hunting))
	 * This also pairs well with the button shortcut to enable Quick Continue. (See: [New Options](#new_options))
 - Starters come with custom movesets and held items. Some even come with HM moves.
![](images/Documentation/image1.png)

### Character customization:
 - Can select from several different, familiar and new player characters
 - Includes full sprite previews including an animated walking sprite
 - You can also customize your gender and colors by choosing from predefined sets or defining any value that you want
 - Custom sprite injection is supported. (See the \#releases Discord channel for more info)
 - This can always be changed later, in the basement of the Goldenrod Dept.Store.

### Additional customization:
 - Can select from **50+** different bag designs, with more unlockable later.
	 * You can also set the primary bag color!
 - Can select from 8 different primary Gear colors
 - Both of these can be changed from the Options menu at any time. (See: [New Options](#new_options))

### Start with:
 - Fully unlocked Gear and Dex
 - Standard starting items, and the **House Key.** (See: [Residences](#residences))
 - Two useful phone numbers (Bill, **League**) (See: [Helpful NPCs](#helpful_npcs))
 - ¥3000 money
 - Link functions enabled

**2. Overworld Navigation and Gameplay Changes**<a name="overworld_changes"></a>
=================================================
### Overworld Navigation:
 - Forced story elements/barriers have been removed
	 * This includes Team Rocket and the Rival.
	 * Sudowoodo has wandered off...
 - Certain areas have been reworked to be more navigable earlier
	 * See: [Map changes and additions](#map_changes)
 - Many Cut trees have been removed, and any remaining/new Cut trees now stay cut forever.
 - Strength boulders are only in the Seafoam Islands and Slowpoke Well, which are optional
	 * This means places like Ice Path can be navigated without Strength
 - The **Magnet Train** is free and immediately available
 - A **Fast Ferry** service has been added for quick traveling without the need of HMs
	 * Can travel between Olivine, Cianwood, Cerulean, and New Cinnabar + Fuchsia
	 * Can be ridden for free after receiving a pass (2 badges, talk to any ferry sailor)
 - The **House Key** is a new travel option under certain circumstances. (See: [Residences](#residences))
 - HMs have received a few changes to be more useful. (See: [HMs](#hms))
 - Lots of misc map and NPC tweaks to help the open up the overworld experience
 - A ticket for the Fast Ship can be purchased at any time

### Gameplay Changes:
 - Gyms now scale based on badges, and can be rematched. (See: [Scaling Gyms](#scaling_gyms))
<a name="Fishing_Rods"></a>
 - Fishing Gurus now give you the different fishing rods in sequence
	 * If you have the Old Rod, the next Guru you meet will give you the Good Rod, etc.
	 * Locations are the same as vanilla Crystal (Route 32, Olivine City, Route 12)
 - A Master Ball can now be obtained in several different ways. (See: [Items](Items.md#master_ball))
 - The 1:7 gender ratio for certain species is now treated as 1:1 instead.
	 * This does not apply during link battles for compatibility, and trading/transferring these species to the vanilla games will revert to the original ratio.
	 * Trading/transferring can go the other way; trading/transferring these species from the vanilla games to Crystal Clear will give them the new ratio.

**3. Gen 2 Glitch Fixes**<a name="fixes"></a>
==========================
 - Kurt's specialty balls now work properly
 - This means Fast Ball properly boosts catch rate on the following species:
	 * Grimer
	 * Tangela
	 * Mr. Mime
	 * Eevee
	 * Porygon
	 * Dratini
	 * Dragonair
	 * Togetic
	 * Umbreon
	 * Unown
	 * Snubbull
	 * Heracross
	 * Cubone
	 * Quagsire
	 * Delibird
	 * Phanpy
	 * Teddiursa
	 * Raikou
	 * Entei
	 * Mew
 - Transform Ditto assumption glitch has been fixed
 - PAR/BRN/PSN now properly affect catch rate
 - Magikarp size related bugs are corrected
 - HP bar animation bug fixed
 - Slot machine sound bug fixed
 - 0.4% massage happiness bug fixed
 - Evolution stone bug fixed
 - Experience text bug fixed
 - Enemy trainer not healing nightmare fixed
 - Experience underflow glitch fixed
 - Ellipsis is fixed⋯
 - Several other fixes that won't affect 99% of users have also been applied.

**4. Battling**<a name="battling"></a>
================
### Scaling Gyms: <a name="scaling_gyms"></a>
 - All 16 Gyms can be faced in any order and have scaled teams based on the amount of earned badges
 - This goes from around ~Lv. 7 to ~Lv. 75, making the latter 8 Gyms more challenging than original GSC
 - Gym Leaders have fully custom movesets for an added challenge
 - There are no sidequests to enable Gyms or leaders (Amphy is ok, Blue is not traveling, etc.)

### Gym Rematches:
 - Unlocked at Gyms that you've defeated once
 - Rechallenge a Gym by talking to the statues at the door
 - All Gym Leaders and trainers are rebattleable
 - Levels are unlocked and correspond to badge count

### Elite Four:
 - Requires any 8 badges to face
 - A new, more difficult set of trainers
 - The original set can still be challenged at any time using the **BATTLE SIM**
	 * Located in the Indigo Plateau building (which no longer requires 8 badges to get to)
 - Rooms have been redesigned with new themes and new animations
 - Upon defeating the E4 once, the teams become much stronger
 - Mt. Silver Champion is unlocked after beating the E4.
	 * This is based on the player's gender, and starting region/or last defeated Mom.
	 * See [the 2.1.0 changelog](changelogs/2_1_0_Changelog.md#2_1_0_New_Trainers) for more info.
 - Hall of Fame now only stores two teams; very first time famers and most recent famers
 - Entering the Hall of Fame 200 times will now properly display "HOF Master!" on the screen

### Arena Matches:
 - Available from the Kanto Underground on Mondays, Wednesdays, and Fridays
 - Over 100 different trainers can appear, including the Battle Tower trainers
 - Randomized party generation based on a player-defined ruleset
 - See [the 2.1.0 changelog](changelogs/2_1_0_Changelog.md#arena) for more info.

### Overworld Trainers:
 - Trainers outside of Gyms scale as well, but not as harshly as Gym trainers do
 - This is to keep world navigation at a minimum hassle
 - Certain sidequest trainers do **not** scale *(Eusine, Sprout Tower, etc.)*
 - Many new special trainers have been added in the overworld.
	 * Many reset once per day.
	 * A special few only reset after beating the E4.

### Roaming Trainers:<a name="Roaming_Trainers"></a>
These trainers will appear in every possible location on every single day until you meet them for the first time. Then they follow this schedule:

**Chronicler Robert**
 - Route 28 (Sunday)
 - Cherrygrove Bay (Monday)
 - Route 24 (Tuesday)
 - Ruins of Alph (Wednesday)
 - Route 10 (Thursday)

**Fibbef**
 - Mt. Moon B2F (Monday)
 - Route 7 (Tuesday)
 - Cinnabar Tunnel (Wednesday)
 - New secret area within Mt. Silver (Thursday)

**Realter Neph**
 - Viridian Forest (Wednesday)
 - Route 28 (Friday)

**Diviner Ryan**
 - Goldenrod Cafe (Sunday)
 - Ruins of Alph (All other days)

**Ex-Rocket Zevach**
 - Goldenrod Cafe (Monday)
 - Silph Co. 1F (All other days)

**Acetrainer Cat**
 - Goldenrod Cafe (Tuesday)
 - Safari Zone Forest Area (All other days)

**Engineer Kensworth**
 - Goldenrod Cafe (Wednesday)
 - Goldenrod House (Saturday and Sunday)
 - Goldenrod Magnet Train Station (All other days)

**5. Residences and Decorations**<a name="residences"></a>
==================================
### Residences:
 - Residences are a rework of the "Player's Room" concept from original Gen 2.
 - The player's current residence(first set when choosing a starting town) can be changed to other towns, including a few hidden unlockable residences.
	* Some residences are more expensive than others!
 - Each residence has a different design, and is fully customizable.
 - A few residences include new shortcuts or other secrets.

### House Key:
 - The **HOUSE KEY** is a new Key Item that is given to the player when starting a new game.
 - Grants entry to where you live.
 - When activated, you can immediately travel to your residence if you meet the following requirements:
	 * Must be outside (so not in a building or cave)
	 * Must have a party member that knows **FLY, TELEPORT,** or **DIG.** 
	 * You can also choose to consume an **ESCAPE ROPE** if you don't have a suitable party member. 
 - This allows you to quickly travel back home anywhere in the overworld, and also provides a new fast-travel option for teams that don't support any of the transportation field moves.

<a name="decorations"></a>
### Decorations:
 - Can now be bought directly in the **Mahogany Bazaar**(new area!)
 - Consoles are now more than cosmetic; each now plays a related music theme
 - Replaced the Virtual Boy with a Wii
 - Carpet now applies to the entire floor, including under the desk and plants
 - Certain residences have an expanded TOWN MAP, allowing you to inspect each individual region.
 - Beds now heal the party, and have a different sound effect for each design.

**6. New Features and Quality-of-Life Changes**<a name="features"></a>
================================================
New Features:
-------------
### Followers:
 - Press Select on the party menu to choose any party member you'd like to follow you in the overworld.
 - All 251 (Including all 26 Unown forms) have unique overworld sprites and species-specific interactions.
 - Followers gain happiness at a rate of 1.5x the normal rate when walking.
 - Some interactions such as having low HP or recent events will take priority over other interactions, otherwise they are randomly generated.
 - Try watering different followers with the Squirtbottle!
 - Followers can also randomly pick up different items.
	 * Some species are better at finding items than others\...
 - For more detailed information on followers, see [the 2.0 BETA Changelog.](changelogs/2_0_BETA_Changelog.md#followers)

### Dex Rework:<a name="dex_rework"></a>
[(Youtube Video Breakdown)](https://www.youtube.com/watch?v=4-W5CGU_h9s "The Pigydex")
 - The Dex has been completely reworked, to offer a much larger library of information, including:
	 * Comprehensive species info, including evolution data, groupings, type advantages, and base stats.
	 * Full learnset information including egg, TM, HM, and tutor moves.
	 * All location data, including encounter rates, types, level ranges, and time of day.
	 * Information on species in the player's current area, registerable to the Select button.
	 * Species listing capability, with several new search modes.
	 * A plethora of new options, including disabling the need for seen data to view information.

### Stats Screen additions
 - Post-rus party members will now display a dot next to the gender icon
 - Press SELECT on the second (green) page of the stats screen will toggle N64 button combos.
	 * This is mostly for use with knowing how your team will function in Stadium 2
 - Press SELECT on the third (blue) page of the stats screen to view current STAT EXP and BASE STATS
	 * Stats with maxed STAT EXP will have a star icon next to them
 - Fourth stats screen:
	 * Shows happiness
	 * Shows place/level/time caught
	 * Shows DVs
	 * Shows personality/characteristic blurb text
	 * Shows Hidden Power type and Power

### PC additions:
 - "Mom saves your money" has been reworked into Bank Account
	 * Accessible from any PC
	 * Can set up auto-depositing money after battle
 - After meeting the Battle Tutor, Gen 1 TM Tutor, or the Event Tutor, the respective set of moves will become teachable from the PC.
 - When getting the Dex rated, Seen/Caught mon are re-evaluated
	 * Will fix things like Stadium 2/external tools not setting the correct Dex seen/caught data.

### In-battle additions:
 - Unlockable wild battle DV display; which can be configured in the Options.
	 * Unlockable by talking to a PC in New Cinnabar Lab
	 * OFF (displays nothing)
	 * LITE (minimal HUD numbers)
	 * FORCE (automatically opens DV vision screen on battle start)
	 * ALL (auto-opens the DV vision screen and displays the minimal numbers)
	 * (Pressing SELECT in battle will bring it up at any time)

 - Removed repetitive in-battle Leftovers text
 - Gym Leaders and certain special trainers have bonus in-battle text when on their last party member
 - Pressing B in a wild battle moves the cursor to RUN

### General Additions:
 - Buying coins has now been made simpler with a new UI and allows buying exact numbers
 - Added multiple item quantities
	* "Player found 5 FAST BALLS!"

Quality-of-life changes:
-----------------------
### General QoL:
 - Running shoes have been added, and can be turned on permanently in options menu
 - The Player Profile screen now shows Kanto Gym badges as well
 - Haircut/massage happiness has been increased
 - Nurse Joy now turns you around after she finishes healing your party.
	 * This is to prevent talking to her again
 - The clock reset function is available on the continue menu and does not require a password
	 * This also immediately saves the time change
 - Overworld poison fades away at 1HP
 - Name Rater is no longer restricted by matching OTIDs
	 * This means you can rename traded party members
 - Traded obedience was rescaled to be 10x the current badge count
	 * For example, 2 badges is up to Lv 20, 3 badges is up to Lv 30 etc.
	 * With the exception of 1 badge, which is up to Lv 15.
 - Any time the party is healed, each party member's stats are updated.
	 * This means you don't have to deposit and withdraw level 100 party members to update stats correctly
 - Low HP beeping can be disabled in the Music menu.
 - When running out of repel, the player will be prompted to use another.
 - The Magnet Train animation has recieved some QoL updates:
	 * Can now be ended earlier by pressing A, or can ride indefinitely until pressing A.
	 * Pressing Select will honk the train horn.
 - The player can now fish while surfing

### Stadium 2:
 - No longer requires saving at a center
 - No longer requires 150+ caught for full transfer capabilities
 - No longer requires beating the in-game E4 to use the enhanced speed modes in the GB Tower.

### Gear:
 - Added "Clear Contacts" function to phone (Press Select on the Gear screen)
	* Bill and League numbers can't be deleted
 - Added several additional radio stations
	* "The Sound of Pig" can be cycled through by pressing A
 - Press Select on any radio station to lock the current music.
	* Persists through map changes, battles, certain events, etc.
	* Several cutscenes do disable this, but only temporarily.

### Breeding/Eggs:
 - Daycare man now appears outside of the fence instead of inside
 - Rejecting an egg from the Daycare Man no longer stops egg production
 - Odd Egg is now a perfect shiny or has decent DVs, instead of the original all zeroes.
 - Odd Egg species probability has been tweaked to favor Magby and Elekid over Cleffa and Igglybuff
 - Goldenrod NPCs have been moved out of the main street
 - Two tiles of grass on Route 34 can be "permanently" cut
	 * They can also be restored by using the Squirtbottle
 - Eggs can be released from the PC
 - When the game tries to generate an egg, it rolls an extra time.
	 * After beating the E4, it will roll a third time if the first two don't succeed.
 - (See also: [Shiny Hunting.](#shiny_hunting))

### Visual Improvements:
 - Added new 251 overworld/menu mini sprites
 - Party screen now features all new dynamically loaded sprites for all 251 species and all 26 Unown forms.
 - Many shiny palettes have been updated to the modern colors
 - Some normal sprite colors have been tweaked as well
	 * These can be disabled from the Dex options menu if the original palettes are preferred.
 - New overworld sprite colors
 - Overworld sprites now have dynamic time of day palette modifications. (Sprites are darker at night, etc.)
 - Some asymmetrical sprites (such as BLUE) no longer flip the top 8 pixels while walking
 - Many overworld sprites have been tweaked or redesigned to better fit the new palette modifications.
 - The poison overworld animation is now much softer.
 - NPCs now have custom palettes to bring more color to the landscape
	 * This is also reflected in-battle for generic trainers, sprites will match the overworld colors
 - Some species have "nickname palettes" which will change their natural color with a certain combination of nickname and DVs.

**7. Move Tutors and other helpful NPCs**<a name="helpful_npcs"></a>
==========================================
### Move Tutors:
 - The Beam Tutors now take cash instead of coins, and are available immediately.
	 * Located in front of the Goldenrod and Celadon Game Corners.
 - Event Move Tutor can teach moves only given out at special events
	 * Found on the first floor of the Radio Tower in Goldenrod City
	 * This has also reflected on learnable TMs, and any event moves that are also TMs can now be taught directly.
 - Kanto TM Tutor can teach moves that were originally Gen 1 TMs
	 * Found on the first floor of the Radio Tower in Lavender Town
 - A new "Battle Tutor" teaches reasonable, but non-canon moves to boost the effectiveness of certain species. Located in Dark Cave (Blackthorn Side) without using Flash, and Route 3 (Mount Moon Square Exit.)
 - A new set of tutors are available in Vermilion City, who will teach egg moves and future level-up moves, in exchange for a Gold or Silver Leaf.
 - In the Ruins of Alph, there is an Unown Shrine that can teach Unown different moves.

### Helpful NPCs:
 - Several helpful NPCs have been consolidated to a new area, which is accessible from Goldenrod City, Blackthorn City, Lavender Town, and Fuchsia City. These include:
	 * Move Deleter
	 * Name Rater
	 * Move Reminder (new!)
	 * Legality Fixer (new!)
	 * Nature Tweaker (new!)

### Helpful Phone Numbers:
 - Bill will automatically call you when your Box is full, and switch it for you if you have room.
 - Added a new **League** phone number
	* Calls once after each badge to let you know what you've unlocked
	* Can be called to restate what you're told, or disable automatic calls
	* Will offer a random Crystal Clear related TRAINER TIP after each message

**8. New options**<a name="new_options"></a>
===================
### Quick Continue:
 - Four different bootup options:
	 * Normal: Full intro sequence	
	 * Title: Skip to title screen	
	 * Menu: Skip to main menu screen	
	 * Quick: Skip directly into the overworld
 - Can also be used by holding a button combo when booting:
	 * Normal: Select + A	
	 * Title: Select + B	
	 * Menu: Select	
	 * Quick: Start
 - These are also available in the options menu

### Quick Encounter:
 - Fancy:
	 * Normal encounter animation
 - Fast:
	 * A simple fade and no sliding animation
	 * Skips the "Got away safely" text	
	 * Skips the "Wild \<species\> appeared!" text

### Quick Nurse:
 - Skips all dialogue.

### Always run:
 - By default, pressing B in the overworld will allow you to run, activating this option will install have the player always run, and pressing B will make the player walk.

### Gear Color:
 - Change the Gear's primary color.

### Edit Pack Design:
 - Pick up to **60** different custom bag designs, and **8** primary bag color schemes.

### Last flown:
 - Start:
	 * Default fly icon on New Bark/Pallet.
 - Save:
	 * Remembers last flown cities for both regions.

### Text speed:
 - **NONE** setting instantly prints text.

See also: [Music Menu](#music)

**9. Map changes and additions**<a name="map_changes"></a>
=================================
As the game continues to grow, many small tweaks and changes will be made and only listed in changelogs, so keep this in mind while playing the game!

### New Areas:
 - New Cinnabar Island
 - Blaine's Gym
 - Cinnabar Tunnel
 - Moltres Chamber
 - Route 40 Olivine Fast Ferry Service
 - Cianwood City Fast Ferry Service
 - New Cinnabar Island Fast Ferry Terminal
 - Route 19 Fuchsia City Fast Ferry Service
 - Route 25 Cerulean City Fast Ferry Service
 - Route 24 Cave
 - Cherrygrove Bay
 - Cherrygrove Bay Caves
 - Cherrygrove Bay Forest Path
 - Grullo Gorge
 - Mt. Rose
 - Forest of Rage
 - Blackthorn-Silver Cave
 - Ace Trainer HQ
 - Route 16 Biker Bar
 - Route 21 Lighthouse
 - Underground Arena
 - Goldenrod Cafe

### Ported:
 - Viridian Forest (with a few minor changes)
 - Cinnabar Mansion
 - Seafoam Islands
 - Power Plant
 - Pewter Museum
 - Cinnabar Fossil Lab
 - Cerulean Cave
 - The Safari Zone
	 * Also has a new area!
 - Mt. Moon
	 * Also a flypoint as well

### Major changes:
 - Clair's Gym
 - Route 27
 - Ruins of Alph
 - Cianwood City
 - Route 40
 - Route 41 (Whirl Islands)
 - Route 42
 - Dark Cave (now usable as a shortcut to Blackthorn City)
 - The two Kanto Underground maps have been combined into one large, connected map
 - The Goldenrod/Lavender Name Rater and Blackthorn Move Deleter maps have been combined into one, now called the Modification Station.

Many maps in Kanto have also been restored to Gen 1 sizes. Additionally, there have been many minor changes to maps, including moving NPCs around and minor tweaks to make the overworld more polished.

**10. Obtainability and Compatibility**<a name="obtainability"></a>
=======================================
### Obtainability:
 - See: [the items page](Items.md) for information on obtaining most items in the game
 - [The dex rework](#dex_rework) covers all obtain methods for species including events and gifts, excluding trades[(which can be found here.)](#Trades)
 - Johto and Kanto Game Corners have many additional species as prizes
 - A Tradeback NPC has been added to help with trade based evolutions
	 * Can be found on the first floor of Goldenrod/Celadon Department Stores
 - Fishing has been tweaked to have a larger variety across rods/multiple areas.
	 * This means the Old Rod isn't just the Magikarp Rod anymore.
 - After a cutscene in Union Cave/Mount Moon, footprints will appear in the overworld to highlight rare species in areas

### Compatibility:
 - No new moves
 - No additions beyond 251 from later gens
 - No physical/special split
 - No compatibility-breaking bugfixes (see: Belly Drum, Dragon Fang, etc.)
 - Non-canon wild data exists, however no new landmarks are used to preserve Stadium 2/Seer compatibility.
	 * For example, you can fish on New Cinnabar, but the caught data will just say Cinnabar.
	 * CC features a last-known-legal-landmark system 
 - Confirmed working with Stadium 2, GSC, and RBY via Time Capsule
 - Mystery Gift still works properly, but is no longer required for obtaining certain decorations. (See: [Decorations](#decorations))

**11. Music**<a name="music"></a>
==============
 - Music is now customizable from the new Music menu on the start screen
	 * Surf music option has a "Regional" variant that plays a matching track per region
 - Many new tracks have been added, including a complete set of Gen 4 arrangements by FroggestSpirit!
 - Additional music can be unlocked by defeating certain trainers or completing specific tasks
	 * For a list of what tracks are unlockable and where to find them, see: [Unlockable Music.](Music.md)
 - Music can be disabled
 - Certain trainers and legendary encounters will have designated themes
 - Pressing Select on the music screen will set the highlighted track to **RANDOMIZE**

**12. Shiny Hunting**<a name="shiny_hunting"></a>
======================
The **1/8192** chance has been preserved for wild encounters, but some quality of life features have been added:
 - Shinies now have in-battle shiny icons
 - Shinies now display an icon on the nickname screen along with DVs (for quickly checking shinies from events.) It will also play a sound.
 - Party screen icon palettes will all have a different palette for shinies
	 * This is also reflected on the nickname screen
 - Egg sprite on the party screen will show shininess (blue instead of the default red)
 - Soft-reset is disabled when a shiny is initially found on the nickname screen or in battle.
	 * Note that this won't stop you from exiting or advancing text, which re-enables the ability to soft-reset.
 - When a shiny is found in battle, an "Oh, it's a shiny!" message will display. This includes Quick Encounter, to put an extra A button press between re-enabling soft resetting.
 - Sweet Scent takes repel into consideration
 - Certain gifts/events will prompt you to "Save game for soft resetting?"
	 * This sets up a nicer soft-reset point allowing you to skip dialogue/cutscenes.
 - Quick Continue allows you to minimize time between resets for shinies
 - Quick Encounter speeds up the startup battle animation times
 - Roamers now have a different palette and play the sparkle sound when being released
	 * Each roamer has shininess rolled for individually at the Burned Tower
	 * If Suicune is released from the Burned Tower as any set of shiny DVs, the stationary encounter will automatically be upped to the highest possible shiny DVs and will remain shiny even through resetting.
	 * If not, shininess can still be reset for at the Tin Tower event or the Cianwood City rechallenge.
	 * Shiny palettes are preserved for all overworld story events for all three beasts
	 * If a shiny roamer is fainted, when re-released, it will stay shiny (see: [E4 Resets.](#e4_resets))
	 * DVs are viewable in the Dex after enabling it from the Dex options.
 - Shinies will no longer flee
	 * This does not include roaming legendaries, who retain shininess even if they flee
 - Cannot run from shinies
	 * *(No, this was not a feature in Crystal, that was only for the stationary Red Gyarados encounter)*
 - Damaging moves will now fail if used by wild shinies
	 * This includes moves like Explosion, Curse, Take Down etc.
	 * Hi Jump Kick still works, but will not cause damage if it misses
	 * Struggle will continue to harm the wild shiny until it reaches red HP. It will then fail until you run out of balls, at which point it will work as normal to prevent a softlock
 - Perish Song always fails for wild species
 - If the Daycare Man has a shiny egg, he will be distracted by the blue spots
 - Legendary Dogs now have a full shiny animation which plays if they are released as shiny.
 - Suicune's DVs roll before the battle starts in the Tin Tower allowing for the proper palette and animation to play in the overworld.

### Increased odds:
 - Safari Zone shiny odds have been increased to **1/4096.**
 - Gifts (Like the Starter, Game Corner prizes, etc.) have been increased to **1/1024.**
	 * **This does not apply to stationary wild encounters.**

**13. Renewable Resources, E4 Resetting and Trades**<a name="renewables"></a>
====================================================
### Renewable Resources:
 - Master balls can be obtained as a Game Corner prize
	 * Can also be bought in the Mahogany Bazaar on Friday nights
	 * [For a full list of Game Corner Prizes, click here](Items.md#prizes)
 - TM Mart always stocks all 50 TMs once you have 8 badges.
	 * [Click here for the list of TMs sold in each set.](Items.md)
 - See the [Marts section](#Marts) for information on other changes
 - See: [Helpful NPCs](#helpful_npcs)

### E4 resets:<a name="e4_resets"></a>
 - Individual roamers, if they've been released and if they were fainted
	 * Plays cry and the shiny sound if applicable(keeps DVs if shiny)
	 * Also checks if they still exist on the save file
	 * Save before using the machine if you wish to SR for these.
 - Ho-oh/Lugia/Suicune/Articuno/Zapdos/Moltres/Mewtwo can be refought after each completion
 - Celebi, if it hasn't already been caught
 - Dome Fossil/Helix Fossil/Old Amber overworld events.
	 * Only if you don't currently have that fossil already
 - Dragon Shrine Dratini
 - Ilex/Viridian Sudowoodo
 - Celadon/Goldenrod Eevee
 - All the Voltorbs and Electrodes in the Power Plant
 - Kiyo's Tyrogue
 - Magikarp Salesman
 - Mania's Shuckie
 - Togepi Egg
 - Shiny Ditto Egg
 - Odd Egg
 - Gold Magikarp/Red Gyarados 
 - Cherrygrove Bay Sudowoodo
 - Lapras (optional early reset to avoid clock reset)
 - Certain rebattleable trainers, notably the Mt. Silver Champion
 
### In-game trades:<a name="Trades"></a>
 - A few trades got reworks to be better early-game options, including much better DVs and held-items.
 - Several additional trades have been added.
 
**Trade Locations:**
 - Goldenrod Dept.Store 5F
	 * (ABRA for MACHOP)
 - Violet City (House)
	 * (BELLSPROUT for ONIX)
 - Olivine City (House)
	 * (EEVEE for SQUIRTLE)
 - Blackthorn City (House)
	 * (BUTTERFREE for DODUO)
 - Pewter Center 1F
	 * (GASTLY for NATU)
 - Route 14
	 * (SNUBBULL for MISDREAVUS)
 - Goldenrod City (House)
	 * (DIGLETT for MAGNEMITE)
 - Route 43 Mahogany Gate
	 * (Anything for SWINUB)
 - Route 10 Center 1F
	 * (SLOWPOKE for TEDDIURSA)
 - Ace Trainer HQ
	 * (WOOPER for WOBBUFFET)
 - Route 16 (House)
	 * (LEDYBA for SMOOCHUM)
 - Vermilion Port Passage
	 * (KRABBY for STARYU)
 - Cinnabar Tunnel
	 * (BEEDRILL for LICKITUNG)
 - Elm's Lab
	 * (UNOWN for GIRAFARIG)

**14. Marts**<a name="Marts"></a>
==============================
### Marts:
 - Now scale with badges
See also: [the items page.](Items.md)

### Specialty marts:
 - Kurt's house (specialty balls for sale)
 - Pewter/Azalea (different sets of held items)
 - Celadon/Goldenrod (all evolution items)
 - New Cinnabar Island (mail, snack bar)
 - Route 16 Biker Bar (snack bar)

### Scaling TM mart:
 - All 50 TMs can be purchased
 - There are 4 unlockable sets, which are unlocked every 2 badges.
 - Mart now displays the name of the selected TM onscreen
 - Located in the Celadon/Goldenrod Department stores

**15. HMs**<a name="hms"></a>
============
## Changes:
 - HM moves no longer require badges to be used outside of battle
 - HMs are available in both regions, with the exception of Whirlpool and Waterfall (see below)
 - NPCs will give you the HMs based on how many badges you have
 - Badge requirements are different per region to encourage traveling between the two
 - Since most blocking Cut trees have been removed, Cut is only used for shortcuts and secrets
 - Fly can be used to fly between the two regions directly (press left/right on the fly map)
 - Having visited an area is no longer a requirement to fly to it
	 * Indigo Plateau, Mt. Silver and New Cinnabar Island however must be visited at least once.

## Locations:
### Cut:
 - *Johto*: Charcoal Kiln (2 badges)
 - *Kanto*: Route 2 Gate (2 badges)
### Surf:
 - *Johto*: Dance Theater (4 badges)
 - *Kanto*: Safari Warden's House (0 badges)
### Strength:
 - *Johto*: Olivine Cafe (0 badges)
 - *Kanto*: Vermilion Port (4 badges)
### Fly:
 - *Johto*: Cianwood City (3 badges)
 - *Kanto*: Route 16 House (3 badges)
### Flash:
 - *Johto*: Sprout Tower 1F (1 badge)
 - *Kanto*: Route 10 Center (1 badge)
### Whirlpool:
 - *Johto*: Dragon's Den (Enter with just the RISINGBADGE, or any other 2 badges. There is also a secret entrance from Mt. Rose.)
### Waterfall:
 - *Johto*: Ice Path (0 badges)

**Certain starters, gifts, and stationary encounters may also have HM moves.**

**16. Misc stuff**<a name="misc"></a>
==================
### **Easter Eggs:**
 - Try messing with the game's code in Celadon Mansion
 - Try messing with the guard's computer in New Cinnabar Lab.
 - Try talking to the Old Amber 5 times before speaking with the scientist about it.
 - There's a truck in a place. You know what to do.
 - There's a secret ledge on the cliff behind Bill's House. There may be secrets in his garden.
 - Rebattle Youngster Joey with 16 badges.
 - Defeat the E4 rematch to unlock a battle with THE CHAMP in Victory Road
 - Try inspecting the spot Silver stood in at the beginning of Gen 2
 - If a Shuckle holds Berry Juice long enough...
 - Try playing as Blue and talking to the Viridian Gym leader
 - And more!
