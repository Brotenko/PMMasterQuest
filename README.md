![alt text](https://i.imgur.com/ln51Cu0.png)

# Description

**Paper Mario: Master Quest** is a mod made for "Paper Mario" on the N64. It was created by **Emperor_Thamz**, **Rainchus**, **JaThePlayer**, and **Brotenko**. It revamps old content and adds plenty of new as well.  
Often considered "The Dark Souls of Paper Mario", the mod is incredibly difficult. It was designed with elite challenge runners in mind, and unless you have extensive knowledge of Paper Mario, you may struggle with much of the content. 
For those players we offer **Paper Mario: Master Quest Jr** which has all of the content the original has, with a much more reasonable difficulty curve. If you want to stream the mod, starting with Jr. is recommended.

**Some of the new content includes:**
- 50+ new maps, including a brand new dungeon!
- A fully functional Pit of 100 Trials.
- 60+ new enemies, ranging from recolors to fully custom enemies.
- Heavy changes to enemy AI, and new battle mechanics not found in the vanilla game.
- A number of map changes to keep some areas feeling fresh, and keep the player on their toes.
- Item and Badge rebalancing, some more obscure tools are now viable.
- New badges and partner attacks.

# Setup

1. Download the newest .mod file
2. Get a Paper Mario (USA) ROM. A .z64 ROM file is required.
3. Go to [this link](https://hack64.net/tools/patcher.php) to patch your ROM.
4. Get an emulator, if you have one already, then load the patched ROM file and play! Bizhawk is the recommended emulator for Master Quest.

# FAQ

**Bizhawk: savestates don't work!**
> After loading the patched ROM, go to the N64 tab at the top and check "Use Expansion Slot".

**Project64: "R4300i opcode" error**
> After attempting to load the ROM, go to settings. Under Paper Mario,  change 4 MB ram to 8 MB. Then, click on Recompiler by expanding the Paper Mario settings. Uncheck register caching and save your changes.

**Project64: Graphical Issues / Screen Flicker**
> You need to manually setup the GLideN64 graphics plugin for your emulator. Visit [this link](https://github.com/gonetz/GLideN64/releases) and add extract the zip to path/to/project64/Plugin/GFX. Then, reopen PJ64, go to options -> settings, click on Plugins in the left pane, and select GLideN64 for the Video Plugin option.
Note that Glide64 is not GLideN64 - the latter is more accurate to the point of being required for decent Paper Mario emulation, although it doesn't support weaker machines.

**Project64: "Verify ROM and its settings" error**
> Your ROM is somehow corrupted! Most likely it was not in the correct format (.z64) when you patched it; try N64 Tool to convert your .n64 or .v64 ROM to .z64 and use the online patcher.

**Opening the pause menu causes a TON of lag!**
> Open up the graphics plugin settings for your emulator. Non-Bizhawk users should have setup GLideN64 first before this. In the GLideN64 ->Frame Buffer Settings tab, change the FB (Framebuffer) settings to the same as the picture below and click Save. Different emulators may use slightly different names for options.

**Where do I report bugs?**
> You can DM Emperor_Thamz on Discord, or open a Github issue, and we will try and fix any gamebreaking bugs.

**Why is _ so hard!? This mod is unfair!**
> This mod is made for the top 1% of challenge runners. MQ Jr will be what you are looking for!

**How can I support MQ?**
>Find someone streaming MQ, and sub to them on twitch or donate or however you want to do it.

**Where can I post a link if I stream this mod?**
> Paper Mario Modding and TwoPieRadian [Discord](https://discord.gg/5Gh7daH) channels are a good place to start. Feel free to @Emperor_Thamz if you do, I like to stop by sometimes!

# Patch Notes - **Spoiler warning**

### Balance changes:
#### Overall chapter changes:
- **Chapter 1:** 
  - Bill Blaster HP/ATK/DEF: **6/0/2** -> **5/0/3** 
  - Bullet Bills give less SP.  
- **Chapter 2:** 
  - Bandito's start battle invisible for one turn.
  - Swooper:
      - Perched attack sped up.
      - Flying attack greatly sped up and DMG changed: **4** -> **5** 
  - Stone Chomp now immune to dizzy.
  - Formations have been updated.  
- **Chapter 3:** 
  - Bzzap!:
      - Single sting poison duration: **4 turns** -> **2 turns**
      - Swarm attack effect changed: **2 turns poision** -> **4 turns shrink** 
  + Hyper Paragoomba DMG: **4** -> **5** 
  + Red Clubba randomized swing timing removed.
- **Chapter 4:** 
  - Shy Guy (all colors) acrobatic attack: **Variable shrink** -> **100% chance for 2 turns**.
  + Dandy Guy no longer makes contact on attack. 
  + Shy Stack:
      - Significantly more resistant to dizzy.
      - Slightly more resistant to paralysis.
  - General Guy AI reworked.
- **Chapter 5:** 
  - Fuzzipede heal improved: **4HP** -> **7HP**
  + Jungle Fuzzy will now deal a **6 DMG** tackle when schocked, instead of leeching. 
  + Putrid Piranha Dizzy turn modifier lowered: **-1** -> **-2** 
  + M. Bush attack randomization changed 
  + Raphael the Raven's mini raven attack bypasses Lifeshrooms again, to avoid a crash. 
- **Chapter 6:** 
  - Crazee Dayzee:
      - Sleep Song DMG: **5** -> **6**
      - Removed looping randomization.
      - Debuff Song changed: **DEF -1** -> **ATK -1** 
  + Bzzrk! 
      - HP: **7** -> **6**
      - Slightly changed timing of the attack. 
  - Pinkzee Dayzee Dizzy turn modifier: **0** -> **-2** 
  + Amazy Dayzee 
      - Now runs away after attempting to kill Mario, and failing.
      - Only gives SP the first time killed
  + Huff n Puff:
      - Thunderstorm attack DMG: **20** -> **25**
      - He will now charge and attack on the same turn below 20HP. 
      - Desperation attack now happens once at 60HP or lower
      - Desperation attack DMG is now: **10 + (2 x Ruff Puff ct.)** 
      - Steals all Life Shrooms the first time the tuff puffs attack. 
      - Every other Tuff Puff is now consistently invisible for: **3 turns** -> **2 turns**
- **Chapter 7:** 
  - Complete Monstar rework. 
  + White Clubba single swing attack now randomized.
  + Swoopula:
      - Now immune to zaptap.
      - Faster leeching while flying 
  + Crystal King:
      - Slightly higher resistance to fire. 
      - Fire shell will deal 9 DMG now.
      - Icebolt DMG increased: **12** -> **14**
      - Bit-Spit-Speed now based on the times healed.
      - Triple Breath randomization is now a **5 frame-window**. 
- **Chapter 8:** 
  - Ember:
      - Dizzy chance lowered: **100%** -> **60%** 
      - Dizzy turn modifier lowered: **1** -> **-2**
      - Shrink turn modifier lowered: **0** -> **-1** 
  + Hammer Bro sleep turn modifier lowered: **-1** -> **-2** 
  + Bony Beetle:
      - Sleep chance lowered: **60%** -> **30%**
      - Dizzy turn modifier lowered: **0** -> **-1**
      - Paralysis chance lowered: **75%** -> **25%** 
      - Paralysis turn modifier lowered: **-1** -> **-2** 
  + Magikoopa ATK boost: **2** -> **3** 
  + Ztar Attack now removes **one half of a bar** of Starenergy.
  + Bombshell Bill dizzy chance lowered: **100%** -> **50%** 
  + Castle Jr Troopa heal lowered: **20** -> **10** 
  + 007 Guy:
      - Shrink turn modifier lowered: **0** -> **-1**
      - Fire DEF lowered: **0** -> **-2**
      - Hammer DMG increased: **8** -> **9**
      - Slingshot DMG increaded: **12** -> **14** 
  + Hallway Bowser HP increased: **60** -> **80** 
  + Final Bowser:
      - Jump DMG increased: **10** -> **13**
      - Claw DMG lowered: **7** -> **6**
      - Shockwave DMG to Mario increased: **6** -> **10**
      - Changes attack pattern if the player uses Zaptap. 
  + Dark Koopatrol:
      - Main attack DMG increased: **11** -> **12**
      - Sleep turn modifier lowered: **-1** -> **-2**
      - Now immune to all status besides sleep.
      - A new attack has been added.

#### Location specific changes:
- **Superbosses:**
  - Goomba King EX:
      - 'Shroom Attack DMG increased: **6** -> **9**
      - Blue Goomba DEF increased: **0** -> **1** 
      - Blue Goomba ATK increased: **4** -> **5**
      - Red Goomba ATK increased: **4** -> **6** 
  - Koopa Bros EX:
      - HP increased: **70** -> **80**
      - AI has been reworked.
      - Shell Toss DMG increased: **6** -> **7**
      - Drop attack DMG increased: **11** -> **12** 
  - Tutankoopa EX:
      - The Chomp has been replaced with a Golden Chomp
      + Shell Throw DMG increased: **7** -> **9**
      - Shell Throw no longer shrinks.
      - **3 turn** Static has been replaced with **1 turn** Invis 
  + Tubba EX:
      - Better chance to be shrunk, but for less turns. 
      - Smash DMG increased: **8** -> **9** 
      - Leap DMG increaded: **10** -> **11** 
  - General Guy EX:
      - DEF increased: **4** -> **6**
      + Summons troops differently now. 
      + Bulb DEF increased: **1** -> **2** 
  - Huff n Puff EX:
      + Body Slam DMG increased: **11** -> **13**
      - Thunderstorm DMG increased: **24** -> **25** 
      + Thunderstorm now inflicts **1 turn** of paralysis.
      - The aerial verion of Thunderstorm is now slightly sped up.
      - Will now charge and attack on the same turn below 40HP. 
      - Desperation attack now happens once at 90HP or lower
      - DMG of the desperation attack is now: **20 + (2 x Ruff Puff ct.)** 
      - The desperation attack cannot be avoided anymore. 
      - Steals all Life Shrooms the first time the tuff puffs attack. 
      - 2 of every 3 puffs will be invisible when spawned. 
  + Crystal King EX:
      - Slight AI edits have been made
      - Slightly more resistant to fire now. 
      - Fire shell will deal 9 DMG now.
      - Bit-Spit-Speed now based on the times healed.
      - Triple Breath randomization is now a **5 frame-window**. 
  + Giga Bowser:
      - Claw DMG lowered: **9** -> **8**
      - Stomp DMG increased: **10** -> **15**
      - Attacks no longer make contact.
      - AI reworked for less RNG and story-style healing.
      - Star Rod combo HP trigger changed: **90HP** -> **150HP**
      - Heals decreased: **90HP** -> **80HP**
- **Sewers:** 
   - Dark Koopa AI reworked to be harder to get stunlocked. 
   + Boo:
      - DMG lowered: **7** -> **6**
      - Gains **1 turn** invisibility when at half HP.
   + Blooper now has increased status resistance. 
   + Electro Blooper now has increased status resistance. 
   + Super Blooper:
      - Ink DMG increased: **9** -> **11**
      - Now has increased status resistance. 
   + Added Anti Blooper:
      - Does exactly what he sounds like.
      - Spawns serparate from other bloopers and thus can't be skipped!
- **Endgame / Chapter 9:** 
  - Added 1 extra Star Piece to the endgame dungeon. 
  - Bandit Leader:
      - Now called "Bandito Elito".
      - Sleep modifier lowered: **-1** -> **-2**
      - Dizzy modifier lowered: **0** -> **-2** 
      - ATK increased: **7** -> **10** 
  + Iron Pokey:
      - Falling attack DMG increased: **10/9/8** -> **12/10/8** 
      - Ranged attack DMG increased: **8** -> **9**
      - Electric DEF lowered: **0** -> **-1**
      - Now immune to dizzy.
  + Dark Bones:
      - Shrink turn modifier lowered: **0** -> **-2**
      - Gets up **1 turn** faster 
  + Golden Chomp:
      - HP lowered: **16** -> **15**
      - DMG increased: **10** -> **14** 
  + Dark Boo:
      - Are now harder to block.
      - DMG increased: **7** -> **8**
      - They gain 1 turn invisibility at half HP
      - Shrink turn modifier lowered: **0** -> **-1** 
      - Stop turn modifier lowered: **0** -> **-1** 
  + Golden Cleft's are now immune to Quake 
  + **NEW ENEMY:** Gold Bristle
      - HP 12
      - ATK 11
      - DEF 
          - Normal: 8
          - Quake: -1
          - Fire/Blast:
  + Disastar:
      - Debuff attack cannot be avoided anymore.
      - Debuff attack changed: **DEF -1** -> **DEF -1 + ATK -1 + removes 1.5 bars of SE**
- **Dojo:** 
  - Lee Flying Tackle changed: **-1DEF** -> **-1DEF + -1ATK**
  + Master, SSJ Master, and SSJ2 Master:
      - Now raise DMG by 2 per hit.
      - Drain all SP with each hit.
      - SSJ2 Master Level: **86** -> **0**
      - SSJ2 10-Hit ignores transparency and Life Shroom.
- **Pit:** 
  - Rest Floor hidden block no longer hidden. 
  - Added Star Piece to each rest floor.
  
#### Other changes:
- Crystal Kind and Crystal King EX now sorta eat Stone Caps. He explains it.
- Water Block FP cost: **5FP** -> **4FP**
- Multibounce and Truth Stomp switched spots in Rowf's shop. 
- Truth Stomp is now available after Chapter 1.
- Multibounce is now available after Chapter 2.
- Truth Stomp DMG changed: **2/4/6** -> **1+1/2+2/3+3**
- Fright Jar replaced with Pebble in Toad Town Shop.
- Close Call overhauled, now gives **+1 DEF** in danger for **1BP**. (Thanks Brotenko!)
- Pretty Lucky overhauled, now **doubles SP regen** at the end of a turn for **3BP**. (Thanks Brotenko + Rain!)
- Lucky Day overhauled, now refunds **1/3 Star Energy** when using a star power for **8BP**. (Thanks Brotenko + Rain + Ja + Alex + Justin!)
- Changed some formations.
- Iron Bonk DMG changed: **3+5** -> **3+3**,
- Iron Bonk's hits now pierce defense. (Thanks Brotenko!) 
- Iron Bonk now works with Charge. (Thanks Brotenko!) 
- Iron Bonk cost changed: **7FP** -> **6FP**
- Goombario's Charge changed: **+2ATK** -> **+3ATk**
- Goombario's Charge cost increased: **1FP** -> **4FP**
- Gambler's Jump and Smash have been reworked. (Thanks, Brotenko!)
- Endgame enemy family Golden _enemy_ had status tables reworked. Each has a 50% weakness to one status now, at a -2 turn count. All other status are 0%.
- Air Lift FP cost increased: **5** -> **6**
- Removed some RNG from the floor 100 boss.
- D-Down Smash BP cost lowered: **3** -> **2**
- Dizzy Dance FP cost lowered: **7** -> **6**
- Dizzy Dance dizzy chance increased: **72%** -> **85%**
- Hammer Throw damage increased: **+1 DMG** -> **+2 DMG**
- Medicine Man now gives + 50% FP as well. (Thanks Brotenko!)
- Multi-Smash uses charge on each hit now, instead of just the first one. (Thanks, Brotenko!)
- Air Raid FP cost lowered: **8** -> **7**
- Screech Ultra Rank DMG increased: **3** -> **4** (Thanks Brotenko!)
- Dizzy Attack BP cost increased: **2** -> **3**
- Changed the formation a bit for the Chapter 8 Duplighost fight.
- Mega Smash and Multi-Smash switched locations.
- Bosses who destroy a specific item now destroy all of the particular item in one turn rather than one per turn.
- Kooky Cookie and Strange Cake now give **1 turn** of invisibility.
- Life Shroom on SSS has become an Ultra Shroom.
- Frozen Fries heal increased: **15HP** -> **25HP**
- Money Money BP lowered: **2** -> **0**
- Added Extra Happy Heart and Flower to the Star Piece shop.
- New endgame fight! Make sure you check the Dojo! (Thanks Brotenko!)

#### Bugfixes:
- Hitting the Goombnut tree in the Goomba King EX fight no longer has a chance to crash. (Thanks Brotenko!)
- Crystal King no longer has a chance to crash when his bits are out upon being defeated. (Thanks Brotenko!)
- Lava Piranha and Lava Piranha EX defense table is now fixed to actually work. (Thanks Brotenko!)
- Huff n Puff EX _shouldn't_ crash anymore.
- Text fixes. Like a ton of them. Ask Purseit, there were probably at LEAST like 12.
- Buzzar can no longer be skipped by getting the Super Hammer and opening the shortcut before beating Tutankoopa.
- Spike Tops in the Volcano now have the correct status table (overall much more resistant, especially to dizzy).
- Multi-Smash damage is the same for each hit now. (Thanks Brotenko!)
- General Guy EX Bulb doesnt crash stuff anymore, and tank is correctly immune to Quake.
- When the Lil' Oink machine is fixed the Toad correctly tells you.
- Fixed a few oob glitches/map errors.
- Fixed Endgame enemy Golden Chomp looping animation incorrectly.
- Fixed a few (read: a ton of) sprites. (Thanks Brotenko!)
- Chill Out doesn't crash when enemies habve >128HP anymore. Everyone say **"Thank you Rain!"**
- Hallway Bowser no longer has chance to be statused, and fixed an animation error.
- All Shyguys now have the same attack pattern.
- Fixed a few LZ that could give issues when entering the map.
- Goombario's Charge cap fixed.
- Normal Paragoombas now have the extra damage their family is supposed to get.
- Fixed the Chapter 8 skip using the badge block.
- You can no longer scam the Star Haven shop.
- Endgame boss Shadow Twink no longer can be hit by quake.
- Star Piece count in Mario's house corrected.
- Buzzy Beetles down in the sewers no longer have weaker genes that produce lower ATK values.
- Final Bowsers lightning attack inflicts the correct status now.
- Bony Beetle doesnt yeet invis anymore, and gets up + attack same turn.
- Dark Paratroopa doesnt yeet invis anymore, and gets up + attack same turn when dropped.
- Chapter 7 enemy Rogue Star no longer hits Bow through outta sight.
- Trees once frozen in time now properly shake when struck.
- Endgame enemy Dark Bones now properly gets up and attacks same turn.
- Kooky Cookie and Electro Pop no longer have janky FP recovery (Thanks Rain!).

#### QOL Changes:
- Chapter 7 enemy Rogue Star now has a sleep animation (Thanks, LuigiGeek + Brotenko!)
- New sprites for multiple new badges including Multi-Smash, Stop Smash, and Truth Stomp (Thanks Brotenko!)
- Renamed an enemy.
- When ATK and DEF are boosted/lowered, the arrow and number display correctly. Usually. (Thanks Rain!)
- New sprites/palettes for a bunch of enemies. Should be nicer to look at. (Thanks Brotenko!)
- The Pit final boss can now be battled each time you reach Floor 100.
- The Pit final reward has a new menu and a really cool animation that goes with it. (Thanks Rain!)
- Red Clubba now has its own name and tattle for in-battle.
- Final dungeon maps updated a bit, mostly visual-only.
- Updated some tattles to give away a few little tidbits about the enemy.
- Updated other tattles to just be less terrible.
- 0BP badges retain their costs even in Luigi's Challenge. (Thanks Quackles!)
- You can refight the final form of The Master.
- Not everyone has a **Lenny** to count for them, so the Pit now has a sign to tell the floor number.
- You can refight the dungeon final boss.
- Rewrote Luigi's Diary for some extra lore.
