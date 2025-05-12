# Kryszard's PD2 Loot-Filter
**Hello PD2 Fans!**

Welcome to **Kryszard's PD2 Loot Filter!**  
You can know me from: [Twitch](https://twitch.tv/kryszard). Feel free to follow me there *(I'll try to stream as much as I can for you)*

# About
I am trying to make one filter, which will suit most players needs.  
Filter is good for both: leveling and endgame experience.  
It's gonna show you almost everything which can help you during leveling process at early stages of your new characters, and became more strict after you hit **lvl 80+** (select your lootfilter level in-game settings to adjust it more for your needs)

# Season 11 Filter Update – Patch Notes

The filter has been updated to reflect **all Season 11 changes** that could affect its behavior or appearance.

---

## 🔍 What's New?

### 🧭 Built-in Map Assistance (Legal Maphack?)
While this is **not** a maphack (to comply with ToS), a new feature has been added to assist you in navigating the **LoD campaign** more efficiently:

> **📌 Pathfinding and map-reading tips are now displayed on every Keys stack** in LoD areas!

Preview:

![image](https://github.com/user-attachments/assets/3c88fd7a-1550-4e4a-ac01-93ff9476cb8c)

![image](https://github.com/user-attachments/assets/ef0bb0fa-2ccb-42ff-9248-e0559da4018e)

![image](https://github.com/user-attachments/assets/00c6a8ac-575e-4551-adb6-277a763a4bf7)

![image](https://github.com/user-attachments/assets/c2e3504d-7397-4d9b-b24f-2020abde6f89)
---

### 🛒 Shop Hunting Revisited

Preview:
https://github.com/user-attachments/assets/b5e71954-e481-4597-a183-12eecc16bf37


The Shop Hunting highlights have been **completely reworked**.

- "Notice me, that's me!" notes have been replaced **inside vendor screens**.
- The filter now highlights **+3 or more to any individual skill**, including all combinations such as:
  - `+3` to a specific skill
  - `+1` class skill + `+2` specific skill
  - `+2` skill tree + `+1` specific skill
  - Works for `+4`, `+5`, `+6` as well
 
    **Highlight intensity scales** with +skills: +3 is subtle, +4 is stronger, +5 stands out, and **+6 absolutely pops!**

#### 🎨 Skill Tree Color Coding (Based on Sorceress Trees):
| Skill Tree | Theme     | Color  |
|------------|-----------|--------|
| Tree 1     | Cold      | Teal   |
| Tree 2     | Lightning | Yellow |
| Tree 3     | Fire      | Coral  |

- Font color is blended if bonuses come from multiple trees.
- Applies to **all character classes**.

#### Additional Highlights:
- High ED weapons & armors
- High PDR armors or combined with ED versions
- CtC or Charges for useful skills like:
  - Teleport
  - Amplify Damage
  - Lower Resist

📝 Old "Notice me, that's me!" notes still appear **outside vendor screens**.

---

### 🔊 Sound Notifications

Added **optional** Sound Notifications for rare and valuable items.

Preview:
https://github.com/user-attachments/assets/6960a1d9-e9c7-4466-870a-813f9dc54f6e

🔈 Enabled for:
- Good&Rare Uniques
- Uber Boss Materials
- Uber Boss Uniques
- Puzzlebox, Demonic Box, Puzzlepieces
- Mid Runes
- High Runes
- Super-rare items:
  - Lilith Mirror
  - Horadric Navigator
  - Skeleton Key
  - etc.

🎮 Toggle sound notifications via the **in-game menu**.

---

### 📦 Staffmods & Price Tag Updates

- All staffmods (`+skills`, `+ED`, `eth`) now shown inside a **single bracket**:
It is now: 
 ```text
  [15%|30r|eth]Sup Sacred Targe [4] *
  ```
Previously was:
 ```text
  [15%] [30r] [eth] Sup Sacred Targe [4] *
  ```
#### 💲 New Price Tag Display:

| Price Range       | Display Format           |
|-------------------|--------------------------|
| 0 – 999           | Exact (e.g. `842`)       |
| 1,000 – 4,999     | Nearest 100 (`1.0k`, `1.2k`) |
| 5,000 – 9,999     | Nearest 500 (`5.0k`, `5.5k`) |
| 10,000 – 35,000   | Nearest 1000 (`12k`, `15k`)  |

> Full, unrounded values are still shown **in towns**.  
> Extra spacing removed to reduce screen clutter.

NEW (Season 11): 
![image](https://github.com/user-attachments/assets/28f30fd1-7aaa-4114-a8b1-de7ce8ca9dfb)

OLD (Season 10):
![image](https://github.com/user-attachments/assets/bc8301da-f3d2-48d7-9e39-f614193abcbc)

---

### 🗺️ Map Descriptions Updated

Maps now display:
- All **monster immunities**
- Highest **resistance values**
- Each **Boss’s damage type**

> ⚠️ If you notice missing or incorrect data, please report it.

---

## 🔧 Other Changes

- RuneWords are now listed on **each required rune**
- Removed:
  - Price Tags on equipped items
  - Craft Alvl info on equipped items
- Added:
  - Price Tags on crafted items
  - Few missing good charm highlights
  - Max socket info for throwing weapons
  - RuneWords shown on socketed throwing weapons
  - Some new RuneWord base items
- Slight updates to some Unique item highlights due to affix changes
- Included **all new Uniques**, including descriptions for **Gheed's Event**
- Minor fixes and improvements to various item descriptions
- Filter code refactored to use **Aliases** extensively for better future maintainability

---

## 🧪 Feedback

Please report any bugs, missing highlights, or inconsistencies so they can be addressed in future updates.

**Happy hunting! 🔥**


---

## Mid Season X Update:

![S10_update2](https://github.com/user-attachments/assets/9a0485dd-18b6-481c-9a99-23b1e55acdb2)

What's new?
- Added information on Magic and Rare Crafting bases, that will show Craft ALVL from now on.
	- High Craft ALVL Values gonna be highlighted in 3 tiers:
		1. ORANGE color - Can Roll All Affixes,
  		2. YELLOW color - Can Roll Most Affixes - Can't roll all of them, but you still might want to craft it, cause it can roll well,
  		3. TEAL color - Good for +Skills Affixes - It's designed for class items that can roll +Skills - For Caster recipes (Can't roll the highest affixes, but this shouldn't be an issue for caster weapon),
   		4. Low Craft ALVL values gonna be just displayed without any extra information.
- Revisieted Upgrading items section:
	- Added info with Value of Level Requirement after item being upgraded,
	- Added coloring of Required stat Values - When your character doesn't meet creteria, values would be displayed in RED color. When it meet the req, it will be in WHITE. 
		- <s>(In some cases it might display required level in Light Red/Coral color - When LEVELREQ before upgrade is higher, then LVLREQ of upgraded base - Then Filter can't evaluate the right RED/WHITE color, becouse of limitation with comparation "LEVELREQ>CLVL" that is not supported for now.)</s> - I managed to find workaround, all should be good now.
- Some other minor changes:
	- Highlights of some unique items reduced/improved slightly,
	- Highlights of crafting bases is now based on ALVL/CRAFTALVL instead of ILVL,
	- Rare Class items will show for all classes on Strict Filter Level (and still would be hidden if don't match your class on Max-Strict filter Level),
	- High ED with CTC Amp damage Weapon higlight description changed slightly,
	- Added some new +skills RW bases to be displayed,
	- Fixed spelling od NMAG Hierophant Trophy (was h-EI-rophant trophy before),
	- Added correct descriptions on Lucion Uber ingredients,
	- In Previous update you might notice the extra info for ReRolling Rare Jewels,
	- Some other fixes and improvements here and there.

## Season X Launch Update:

What's new?
- Adjusted items descriptions to match all S10 changes like max sockets increase on some items, new possible runewords on rw bases, new runewords recipes on keys etc.,
- Some unique items are slightly highlighted more or less because of their changes,
- All new upcoming Uniques included,
- Added a feature, which will highlight and ping for all new unknown items (like new uber mats etc - thx to BetweenWalls),
- Added some new RW bases during to max sockets change, adjustet paladin shields RW bases,
- Added better highlight for high Corpse Explosion +skills wands and necro heads (for shop hunting),
- Added descriptions with immunities for new maps,
- Removed TAN color "x" signs on magic/rare quivers,
- Fixed an issue that showed magic uneth throwing knifes for necros and sins even on high strict levels (which are in the same pool in DAGGER keyword as regular staffmods'able daggers),
- Fixed an issue that showed Unique Fallen Gardens Map as Tier 3 - It's a Tier 2 map,
- Some other fixes/improves here and there,
- Filter will be updated with all upcoming post-beta changes, so do not worry about anything :)

## Season IX Update:

![S9 update](https://github.com/Kryszard-POD/Kryszard-s-PD2-Loot-Filter/assets/63604590/6ebcd8be-9e69-4604-ac2a-61ae16b46562)

This update is one of the biggest in history, even if it will not feel very different from your - gamers perspective. Most of the code has been re-visited and optimised/adjusted even more then it was before. There is still some places for improvements, so I'll do my best to provide you the best quality filter I can - Bringing some more updates during the season.

Changelog:
- Item descriptions adjusted more by using new %CL% keyword instead of %NL% - This one is to prevent extra empty description lines to appear when they shouldn't - It never was an issue in my filter, but thanks to it I was able to remove ~40 lines with conditions where description line should break and when not. Now it's much easier to mange it (Big thanks to BetweenWalls and Kanzeon for that!),
- New Filter Level implemented - "Strict Filter - w/o Potions" - This one is set to be like regular "Strict Filter" but in addition it's hiding all health and mana potions, leaving just Juvies,
- Difference between "Strict Filters" and "Max-Strict Filter" is more noticable now - Mostly when it comes to RW bases and Chat Notifies about them,
- Possible Unique items will be listed on Gheed's Event screen from now (divided into Tier Levels - Norm/Exc/Elite),
- Added Notes about Guaranteed Stats of Crafted Items on both: Craft Infusions and Keys stacks with Quantity between 20-26,
- Visual Changes: 
	- PD2 "Pick Up"-Tagged items will be displayed with correct "*-stars" colors now (It should be like this from previous season, but I didn't notice it stays with same coloring as LoD items).
	- Added better highlights for Unique Horadric Tomes and Skeleton Key,
	- Superior items with ED tags color changed to New avaliable options:
		- Weapons - "Sup" color changed from RED to CORAL (light red) - Percentage values on high-tier items will stay in RED.
		- Armors - "Sup" color changed from BLUE to TEAL (light blue-ish) - Percentage values on high-tier items will stay in BLUE.
	- Removed displayed Quantity on Quivers - Those will be displayed as "x  Arrows  x" if MAG or RARE from now on.
	- +SKILLS staffmods will be highlighted a little bit more when roll with max +3 value (+1/+2 will appear with TAN "+" sign and LIGHT_GRAY "number value", while +3 will be displayed with ORANGE "+" sign and "YELLOW" "number value".
	- 3-signs Skill Names Abbreviations color when it match your class changed from ORANGE to SAGE (light green). If those are for other classes it will stay in DARK_GREEN as before. This will work also with Daggers, which can be spawn with both: Necromancer and Assassin skills at the same time.
- Fixed an issue, where Holy Freeze and Holy Fire skills has the same "HFR" abbreviations - Holy Freeze switched to "HFZ" from now on,
- Fixed an issue with abbreviation of "Poison Strike" skill which is "PST" now - It was "PDG" as Poison Dagger before,
- Goblin Toes highlighting reduced a little (but still noticable),
- Added better highlighting for good SET Etheral Weapons,
- Added chat notify for Skull Collector,
- White Etheral Throwing Weapons for Imbue/Crafting will be shown up to Filter Level 3 with chat notify up to Filter Level 2 (or up to Filter Level 5 with chat notify up to Filter Level 3 when your class is Barbarian) - Which means those are no longer visible on Strict Filters,
- Etheral Magic Necro Heads removed for filter levels 2+,
- MAG/RARE Daggers added since those can roll Staffmods now (with similar logic between filter levels as other staffmods-able items),
- Grand Matron Bows and its lower tiers will be displayed on all Filter levels now (caused by popularity of safety bows crafts),
- Highlights with DARK_GREEN *-star and chat notify of non-superior high-def RW bases removed (caused by general Defense values on body armors change),
- NMAG Chest Armors considered as good RW bases will be shown as all Elite Tiers - with adjusted +ED Values and Chat Notify messages between filter levels - also as few NORM and EXC tier bases if someone is hunting not only for highest DEF values but also their favourite skin options,
- Added a Note on RW Bases about Aviability of RW Recipes on Keys Stacks,
- Whole RuneWord Section has been re-visited and re-wrote to adjust filtering experience even more - There was too many changes to list in this small note, but trust me - It should be even better now! (if you will notice that some bases are missing, or some of them should be moved to lower filter levels let me know),
- Added a Dynamic Note with info that 2 x Half Freeze Duration sources will provide Cannot Be Frozen - It will help you to track your currently using Anti-Freezing sources.
- Added "notice me" Notes on Combo of 250+ED weapons with any Amp CTC proc,
- Added "notice me" Notes on High Lower Resist CTC proc items,
- "Notice me" notes adjusted to be less distractive on some common things like just CTC items or items with Charges,
- Adjusted descriptions of some items like Pandemonium Talisman, Skeleton Key, Perfect Diamonds (with info about new Brilliant Crafting Recipes), infos about presence of Immune Monsters on maps, and few other things,
- Health/Mana Potions Notes about Crafting recipes moved to Chipped/Square Gems instead,
- Some other adjustments and fixes here and there... :)

## Season VIII Update:

![Kryszard-S8](https://github.com/Kryszard-POD/Kryszard-s-PD2-Loot-Filter/assets/63604590/6b5c5532-9d01-4c5d-979f-66253cef5ea5)

General changes:

- Info about current filter version added to Horadric Cube description,
- Corrupted items that drop on "Warlord of Blood Map" got red stars extra highlight,
- New "RuneWords" recipes updated on keys stacks,
- Updated possibles RW's on Item Bases,
- New Throwing Potions added (low tier to level 18, mid tier to level 24, high tier to level 40),
- PD2 items now keep the same naming convention/highlights, but with different colors then LoD items,
- Good SET parts highlights changed a little (preview on main pic),
- +skills AutoMod's now will be highlighted in better colors for class that you play,
- Added 0/6 sockets uneth Colossus Blade as good Asylum RW base,
- Mirrored Jewels will show their colors in descriptions now (black/white),
- Rathma/DClone entrance key description updated (3 tiers avaliable),
- Some general fixes&improvements like Shadow Bow wasn't showing possible max sockets from corruption etc.,

## New QoL Feature:

![image](https://user-images.githubusercontent.com/63604590/236599499-a7b304e1-f333-4a2c-bf53-5975a1dd53f8.png)

## Season VII Update:

![image](https://user-images.githubusercontent.com/63604590/233369590-f72dfb33-08a0-4817-bb6e-dd0c4154c936.png)

What's new:

- Info about currently selected loot filter level added to horadric cube description,
- Charges weapons "Notice me" note color reduced from green to dark green,
- "Notice me" Notes are showing only for uncorrupted items now,
- Added "Notice me" Note for High Amp CTC Proc weapons,
- Charms now displays it's orginal name + what stats it adds if its good in next line,
- eth unique Tomahawk added for better highlighting,
- Ohm Rune, Um Rune, and other misc items descriptions updated,
- Possible RuneWords Note updated for RW bases,
- Added Notes for new S7 items like Hellfire Ashes, Catalyst Shard, etc.,
- Updated already existing Notes to match s7 changes,
- Added new "+Xdwo" abbreviation on NMAG barb helms to catch new Deep Wounds skill,
- Adjusted Filter code with new avaliable improvements,
- Paladin shields will show exact Enhanced Damage % automod values,
- Removed Spirit Sword bases from filter level 4+,
- Added few more staves RW bases for your new A4 Merc,
- +3 Cleansing Scepters 0/4/5 Sockets added with hihglight for your A3 Merc (it does scale his Cleansing Aura),
- Removed Gold-worthy items from filter level 4+ (hidden gold piles are auto-picked up now),

## Season VI Update:
General changes:
* Added all ETH EXC and ELT weapons with 0 and 2 or more sockets to "FILTER LEVEL 1 - Hide Just Trash Items",
* Changed how info about max sockets is displayed. Before it was using shortcuts of:
**Q, PB and C** - stands for Larzuk Quest, PuzzleBox and Corruption
Changed to:
**L, P and C** - stands for Larzuk Quest(and Larzuk Mallus - magic items will still show value of 2 sockets, but you need to know that Larzuk Mallus will give always 1 socket, mechanism is diffrent then Larzuk Quest - Larzuk Mallus description shows correct value of possible sockets which is 1), P is for Puzzle(Piece/Box) and C for Corruption,
* Few small fixes.

Season VI update changes:
* Added new items with accurate descriptions of what they do: Larzuk Mallus and Orb of Fortification,
* Map Tier changes - Maps now show correct values of tiers in their names (rotation of tiers),
* Map Immunes changes - Maps now show correct immunes values (to verify and adjust during the season if needed),
* Runes Descriptions changes - Affected runes: Dol, Ist, Ohm, Ber and Jah,
* New Runewords (Asylum and Shattered Wall) added to Possible Runewords descriptions for correct bases,
* Doom shown as possible Runeword for 5sock Scepters,
* Rift shown as possible Runewerd for 4sock Swords.


## Season V Update:
I made 5 strictness levels, which you can choose directly from in-game settings menu:

* 0 - Show All Items - Default setup for all Filters - Like it say's, It gonna show you every garbage.
* 1 - Hide Just Trash Items - Clear your screen a little bit, hide just junk items
* 2 - Item Filter - More Notify - This one is classic Item.Filter that you all know and love, but with extra notifies for more items - all uniques and sets, low runes, flawlesses etc.
* 3 - Item Filter - Recommended - Classic Filter that most of us were using to this day :) I Recommend you use it, or use option 1 for first days of the ladder.
* 4 - Strict Filter - Something like my current strict filter, but with super health and mana potions
* 5 - Max-Strictness Filter - For EndGame Maniac Farmers - Should show just good stuff.

Those Strict Levels are not perfect for now (but should be fine), and we need to balance them to suit most of our needs, so I really want to hear your feedback.

There is also a change for Crafting Recipes descriptions. I've decided to transfer them from items to Perfect Gems instead. It gonna make our Items much Cleaner and Better! QoL Descriptions updated, all new Items and Runewords Supported!
I would describe it more, but don't have much time lately.
Please report any bugs you gonna notice. I need your Feedback to make it better.

![SeasonV.1](https://i.redd.it/o022vrzios891.png "SeasonV.1")  
![SeasonV.2](https://i.redd.it/saodw48and891.png "SeasonV.2")
![SeasonV.3](https://i.redd.it/4666g25zbeb91.png "SeasonV.3")

Below description is outdated, but filter works still on similar behaviour.

## Some Filter Features:

* Filter adds a lot of **useful NOTES** in item descriptions *(like crafting formulas, socketing and upgrading recipes, possible runewords, usability info etc.)*.  
* Inferior items are always hidden *(except for useful class items with +skills)*.  
* Filter is showing exactly +skills values on all NMAG items, even when item is on the ground *(so you don't have to pick those up to check +skills on them)*.
* Filter highlight useful vendor items to make those easier to catch *(like +3 to Warcries Weapons, Teleport Charges staves, Life Tap Charges wands, +3skill/+20IAS gloves, Trap Claws, etc.)*.  
* Every MAG and RARE WEAPON or ARMOR displays a PRICETAG only when its IDENTIFIED *(so you can know if its wotrh to visit Charsi)*.  
* Good CHARMS have changed names to make those easier to mule and organise in your inventory. *(for e.g. +1 to Warcries Grand Charm gonna be called "Warcries Skiller")*.
* hp and mana potions which are showing on screen depends of difficulty of your game. You gonna see every potions on normal diff. On nightmare only Great +, and on hell only Super and Juvies *(and antidotes)*. Showing gems depends of game difficulty aswell. Perfect Gems drop with chat notify.  
* Gold piles with low amount of gold are hidden  
* You can see most of the items and runeword bases when you are on low lvl. Items gonna dissapear when your character gain more lvls. You gonna see every white item *(RW base)* to lvl 30. Normal tier runeword bases gonna be hidden when you hit lvl 30+. Then you will still see every runeword base *(exceptional and elite tier ones)* until you hit **lvl 80+**. Similar rule counts with every magic/rare item will be shown until you hit **lvl 80+** *(normal tier ones only to lvl 40)*.  

## "EndGame" experience starts when you hit lvl 80+, then:

* Filter will show you only good runeword bases. *(check supported RW bases below)*  
* You gonna see exactly ED values on superior RW bases, exactly RES values on Paladin shields RW bases, exactly +skills values on Class-Specific RW bases.
* You will be able to see magic and rare: Circlets and Class Items like Barb Helms, Druid Pelts, Sorc Globes, Wands, Assasin Claws, Amazon Javelins and:  
* Rare gloves, boots and belts (and since rares are better then in LoD also chests, helmets and shields) and:  
* Every ETH Rare and Magic WEAPONS, and:
* Good magical bases for crafting, and:  
* Potentially expensive (Woth some GOLD) items are shown with a PRICETAG, like 2square in eq throwables, wands, sorc orbs etc.  
* Gold piles only in stacks **5k+**  
* Good Uniques (only when UNID!) will be shown with Chat Notification, Minimap Pin and extra colorful ** **STARS** **, the Best Uniques with extra green note. *(pick up!)*
* Runes Number colors 1-14 and 16-17 TAN, 15 and 18-19 WHITE with extra TAN *, 20-25 RED with extra RED * and chat notification, and 26+ GREEN with extra wide-box with COLORFUL ** **STARS** ** . *(to build some hype)*
* New PD2 items like: WorldStone Shards, Larzuk Puzzleboxes, Maps, DClone parts, etc. are included.

## Supported RuneWord bases:

*List coming soon. Meanwhile you can test it using [FilterBird Tool](https://betweenwalls.github.io/filterbird/?v=PD2).*

# ScreenShots preview:
![ScreenShot 5](https://user-images.githubusercontent.com/63604590/146273870-9d67317f-3ae7-4e0a-8ca1-1ad451d866aa.png "ScreenShot 5")
ver 4.4.1 update
![ScreenShot 1](https://preview.redd.it/55pqcgwugvl61.png?width=1920&format=png&auto=webp&s=b276f3bad428f6ee403ea28b247ab20d73f1ec76 "ScreenShot 1")  
![ScreenShot 2](https://i.postimg.cc/38mfnbD2/1.png "ScreenShot 2")  
![ScreenShot 3](https://i.postimg.cc/3NLF0GfF/2.png "ScreenShot 3")  
![ScreenShot 4](https://i.postimg.cc/mZVwnxZ1/3.png "ScreenShot 4")  

# Futureal version:
![ScreenShot 4](https://i.postimg.cc/y6PrDd5Q/obraz-2021-07-29-192957.png "ScreenShot 6")  
Tweaked for [Futureal](https://www.twitch.tv/futureal) - Less colorful, more Vanilla looking version of the filter. No more "colorful *STARS*" and "PICK UP" things.
Few small changes compararing to orginal item.filter, but still almost the same functianolity and QoL features.

# strict.filter:
![ScreenShot 4](https://i.postimg.cc/QXZjWxXw/compare.png "ScreenShot 7")  
More strict version of a filter for late season farmers.
Filter is pretty much the same for characters below lvl 80, at 80+ diffrences are:
- Keys removed
- Mana and Health potions removed (only juvies and antidotes will be shown)
- Class items (magic and rare) will show only to class which with you are playing
- Rare Helmets removed (circlets are still there)
- Rare uneth Weapons removed
- Magic gloves removed
- Quivers: Only rare Arrows will be shown for all clases
- Expensive/worth some gold items with pricetag removed (RW bases with good +skills still there)
- Armor RW bases (body chests, helmets, shields) showing only when rolled with extra ED%
- Eth Body Chests only with 750+ defence
- Some common RW bases like spirit swords, phase blades w/o ED removed.
- Runes: Only Lem [20]+ will drop chat notify

## in-game settings:
![Options_LootFilter](https://github.com/user-attachments/assets/a839ec77-8df1-4ddc-969e-6272dce0b013)


# Donate/Support:
![image](https://github.com/Kryszard-POD/Kryszard-s-PD2-Loot-Filter/assets/63604590/cde75db6-48a6-4d47-9732-b123e71ce784)

### **You don't know what to do with your hard earnd money?**

I've got solution to your problem! Waste them by supporting me and my work! Every donations are more then welcome :)  
Link for donations: [PayPal - Click](https://www.paypal.com/donate?business=X7TTETKQ64W6G&item_name=Kryszard%27s+PD2+Loot-Filter&currency_code=USD)

### **Are you young, dumb and broke like I am?**

You can show your gratitude in a diffrent way:  
Follow me on my: [Twitch channel!](https://twitch.tv/kryszard)

### **Thank you!**
