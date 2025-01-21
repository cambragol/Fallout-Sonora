---
layout: page
title: What's New
include_in_header: true
---

# Changelog
This page will keep track of the changes made to new versions of the translation.

<br>


### `First Release`

# **Version 1.03**
This is an update of the first release of the translation. It addresses issues with some DLC content where dialogues and descriptions were displaying 'error' or '-DLC' messages. Users are encouraged to report any bugs, errors in flow, strange speech etc. at the [NMA Thread](https://www.nma-fallout.com/threads/fallout-sonora-1-14-vanilla-translation.222396/).

#### Based On
- Fallout: Sonora 1.14+ and Dayglow DLC 1.14

#### What's New

- adds gender specific 'amigo/amiga' comments for all relevent dialogues
- standardizes agave juice to agave syrup.
- Himador to Agave Farmer

#### Script Patch Fixes

- updated multiple scripts for 'amigo/amiga' 

#### Bug Fixes

- fixes to DLC that were giving 'error' or '-DLC' messages


# **Version 1.02**
This is an update of the first release of the translation. It addresses updates to the 1.14+ release from Nevada Band. Users are encouraged to report any bugs, errors in flow, strange speech etc. at the [NMA Thread](https://www.nma-fallout.com/threads/fallout-sonora-1-14-vanilla-translation.222396/).

#### Based On
- Fallout: Sonora 1.14+ and Dayglow DLC 1.14

#### What's New

- changed multiple 'Stairs' to 'Ladders' - hopefully correct now.
- updated RCRngMap.msg, AFGold.msg, and SCBoss.msg to match Nevada Band's new Russian dialogue additions.
- fixed some possible font issues in PIPBOY.msg
- fixed various item names in pro_item, to sync with wiki
- fixed Stealth Bio slightly
- fixed a few instances of 'here are your' to 'here's your' - more colloquial
- a few small style fixes in Garage City, explaining 'mine' more.
- Changed all instances of [Next] to [More] to align with Fallout 1
- surgical kit to doctor's bag in all dialogues
- Captain Helford to 'commander'
- Stamina to Endurance in several locations
- Fixed mis-translated line in ZSDoor.msg 'You haven't even left a mark on the door'

#### Script Patch Fixes

- updated several scripts VCRobot,RCRngMap,SCBoss, HCRunchA,HCRunchB, and AFGold to match Nevada Band's 1.14+ changes
- added more Spanish translation to GCPit.ssl

#### Thanks
- OnlyALad and QuantumApprentice for typos and dialogue fixes

#### Bug Fixes



### `First Release`
# **Version 1.01**
This is an update of the first release of the translation. Users are encouraged to report any bugs, errors in flow, strange speech etc. at the [NMA Thread](https://www.nma-fallout.com/threads/fallout-sonora-1-14-vanilla-translation.222396/).

#### Based On
- Fallout: Sonora 1.14 and Dayglow DLC 1.14

#### What's New

- multiple missing punctuation marks fixed
- multiple small changes to items names (hip flask, Jackal Storeroom keys etc.)
- multiple small spelling errors fixed
- Small Weapon/Large Weapon fixed to Small Guns/Big Guns in one location
- Jackal 'holes' fixed to 'dens'
- small fix to VCBandit.msg
- old world standardized to 'Old World'
- some pig-rat entries to 'pig rat'
- fixed multiple small typos, capitalization, commas etc.
- Mr. Helper corrected to Mr. Handy in several locations.
- Vault capitalization touched, but not completely standardized, as in Fallout 1
- Power Armor standardized to proper noun.
- caravaneers fixed to carvanners
- Some lines in ZTmap fixed/improved
- Henry Beamis fixed to Henry Bemis, and J. Crook fixed to G. Crook
- All 'min. strength:' standardized to Min ST: as in Fallout 1
- Broken Staircase corrected to Broken Ladder
- 'Deliver a report to Ranger' mission fixed to 'Retrieve a report'
- 'mainline' fixed to Blue Shields.
- Overseer Whip instance fixed to 'Overseer Lash'
- All Pescador references fixded to 'fishermen'
- Spanish accents added to Gloria, to test for now.
- council of elders in San Brahmin capitalised as proper noun
- fixed Brotherhood 'clerk' references to 'scribe'
- master key references fixed to 'lockpick'
- 'is  now in your backpack' fixed to 'added to your inventory'
- Small fixes to Rio's dialogue
- fixes Casa Neuva plantation quest instructions
- small fixes to Casino bartender in Phoenix
- small fixes to ZAX dialogue
- small fixes to Villa dialogues - hangar references to barn
- Stealth references to Sneak

#### Script Patch Fixes

- Fixes to Jackal raid quest in ZTMap.ssl, and GCGate.ssl
- Made asking about drilling machine parts mutually exclusive with telling that it is fixed - FCAdmin
- Made Villa marauders leave if Sancho or Hugo return - FCVillA or FCVillB
- fixed bug in drilling machine quest that made broke it if light restored before fixing machine. Also restored fade for machine fixing - FSRobot.ssl and FSTransf.ssl

#### Thanks
- Zaius238 and OnlyALad for many typos and dialogue fixes

#### Bug Fixes
- added AI.txt to data folder, without which translated combat taunts does not work



### `First Release`
# **Version 1.0**
This is a first release of the translation. It is has now been completely translated, with 3 full passes, player feedback, and multiple playthroughs. Users who wish to experience the Fallout: Sonora in English may now do so. Users are encouraged to report any bugs, errors in flow, strange speech etc. at the [NMA Thread](https://www.nma-fallout.com/threads/fallout-sonora-1-14-vanilla-translation.222396/).

#### Based On
- Fallout: Sonora 1.14 and Dayglow DLC 1.14

#### What's New

- massive tree-pass on all of DLC - Dayglow
- Thalius to Talius from Fallout 1
- Villa map names shortened
- Family relics to family heirlooms in Villa
- Scrounger's Sense to Scavenger's Instinct - just fits better

#### Script Patch Fixes

- YCBoss.ssl - restored a node to flesh out mission setup  
- YCGhlMat.ssl - fixed incorrect NodeAnswer  
- YCIsdCrh.ssl - fixed incorrect dialogue option 221 to 222  
- YCLiveB.ssl - added recognition of the Ghoul perk, which was missing, but setup  
- YSMonoGh.ssl - fixed activation point for the Monorail quest when being activated by the monorail supervisor  
- SCBoss.ssl - added small Spanish Trait use  
- SCShpBoy.ssl - fixed incorrect reply in script  
- tweaked PVCOvrser as there was an incorrect reaction result in script  
- fixed a misdirected node in RCAcvBnd to correct the dialogue  
- fixed a node in RCAcvTlk to complete the 'Fish' trade route for Garage City quest  
- added a bit check in RCBoss to prevent a conversation loop.  
- added a bit check in RCFrmMan to make a conversation start more natural, using existing dialogue lines  
- added small espanol trait use for Jose  
- fixed BCCrvnQT to limit the response if Phoenix not known yet  
- BCGarPst.ssl - fixed backwards skill check, bonusReaction corrected  
- BCMisBos.ssl - fixed Mark_state_visited to Mark_state_unknown  
- BCMisSld.ssl - added Espanol trait to Spanish song  
- PCGopStp.ssl - fixed dialogue options  
- PCMerkBs.ssl - Many fixes, head claiming was broken/messed up. Fixed multiple nodes, and dialogue  
- PCBdBos.ssl - added alternate answers for one node  
- PCPrtznA.ssl - added check to see if PC knows Matthias  
- PCScvTlk.ssl - gave armor reaction correct dialogue number  
- PCCasBar.ssl - changed int check from -4 to 1  
- PCAtmBld.ssl - added dialogue node to complete dialogue as written  
- PCAtmBos.ssl - added node to make sense of negative answer to job offer  
- PCAtmClt.ssl - added more graceful conversation exit  
- upgraded Espanol Trait to translate Mexican and Spanish ‘combat taunts’ (multiple scripts)  
- fixed bug with Nightkin Boss rescue in Dayglow (YCMutBos.ssl)  
- fixed incorrect reply bug CCNina.ssl  
- fixed incorrect reply bug CCCrvBos.ssl  
- fixed CCBoss.ssl to prevent big response being repeated on main dialogue node  
- added fix to PCBdLohB.ssl to have floating message of revenge after end of quest  
- fixed goodbye message in FCSlvRdr.ssl  
- fixed FCCtznB.ssl to make better transition to offer to cure kid  
- changed FCBishop to have ‘idiot’ node more in line with other idiot nodes  
- added ‘Brahmin Sausages’ to Flagstaff barman and used this for food delivery quest (FCBarmen.ssl and FCAdmin.ssl)  
- added Espanol_Trait to GCPit.ssl dialogue  
- fixed GCGate.ssl to have correct result for successful perception check - also added Jackal quest ditch node.  
- added node to GCBrmAtk.ssl to have better responses for buying the brahmin  
- fixed VCRobot.ssl to differentiate between grandson/daughter, and use Espanol_Trait  
- added Espanol_Trait to ZIUseStp.ssl  
- fixed the feedback for ZSblock to not spam 'destroying' process with constant 'look' messages  
- modified HCBoss, HCPrisnr, HCRunchA, HCRunchB, and HCRunchC to incorporate use of the Espanol Perk  
- updated OBJ_CAR.ssl to account for trying to power with a Generator Fusion Cell  
- fixed brahmin quest at Bar to account for buying the brahmin, rather than stealing - GCBarmen.ssl and GCBrmPsA.ssl  
- fixed TCBoss.ssl to use correct dialogue line when discussing ZAX being destroyed  
- fixed TCCrvBos.ssl to use correct node when responding to paying for escort  
- fixed TCCrvQst.ssl to only offer generator cell if the quest is started. Moved quest start as well and added zReply to use amigo/amiga correctly  
- fixed TCCtzTlk.ssl to add missing dialogue from dialogue file.  
- fixed TCCult.ssl to give Science check different results. Original had identical results.  
- fixed TCTins.ssl to make ‘worker’ and ‘guard’ tinsmiths have different ‘look’ descriptions and different floating lines.  
- fixed NCApcAst.ssl to force the PC to correctly work to get access to pre-war medicines/drugs  
- multiple small fixes to NCApcBos to improve dialogue and include missing lines  
- fixed NCQuestA to prevent endlessly introducing oneself  
- improved NCSilosA.ssl to make dialogue smoother  
- modified ZcImgrnt, DCCtznE, NCHimadr, NCMer, HCPost, HCSolder, HSComp, ACCtzCav, CCBosGrd, CCNina, CCNinb, AFTinTan, and EncMexSC script files to standardize Spanish_trait handling.  
- fixed DCCtzn and NCHimadr scripts, as they were broken/unfinished at several points  
- fixed incorrect text line reference in MCRio.ssl  
- fixed incorrect text line reference in MCBoss.ssl  
- finished incomplete and non-working scripting for DCCtznE.ssl  
- added intermediary steps and dialogue logic to ‘Brahmin Quest’ in GCBrmAtk.ssl  
- fixes to dialogue logic to discuss looking for Villa people that are already found - FCMadre.ssl  
- fixes to end of quest for freeing trapped Villa kin, added dialogue on Mine Exit - FCVillaA.ssl  
- fixes to FCBoss.ssl to make the idiot PC Rat King quest work  
- fixes to pinball machine quest in FCBarmen.ssl  
- made PCDrgdlr.ssl push his stuff with floating lines  
- fixed all three Sonora express scripts so PC recognizes after visiting one  
- fixed Phoenix Sonora express ‘letter’ quest to have better dialogue logic - PCPost.ssl  
- fixed RCAcvTlk.ssl to have better dialogue logic  
- added mid-quest feedback for ‘spy quest’ to PCMaster.ssl  
- added mid-radio-quest feedback and dialogue logic to RCComndr.ssl  
- fixed dialogue logic and ‘spy’ quest for RCRngRad.ssl  
- added fixes to start of quest with RCPresly.ssl  
- fixes to RCAgata.ssl to fix start of quest with Presley  
- changed coordinates of repeater in ZIRadio.ssl  
- fixed CCNina.ssl to make Spanish perk work correctly  
- fixed quest to restore power to Monorail in YSMonoGh.ssl  
- added clues and improvements to AFGold ‘map’ quest  
- multiple fixes to the ‘survey’ quest in RCRngMap.ssl  
- fixes to ZTMap.ssl for Jackals raid quest and Inferno Robot event bug  
- fixes to GCGate.ssl dialogues for Jackal quest and first visit  
- added fixes to ‘Jackal attack’ quest in GCMercJc.ssl, and added quest fail consequences  

#### Thanks
- All the players who took the time to report issues over at the NMA forum thread, in particular Fallout_Boy, Fic_Mon, gusterballs1983, OnlyALad, Perry The Chucktopus, Goat_Boy, Foxx, GrizzlyPA and others. I couldn't have done it without your input and support
- Nevada Band for the game
- Legions of modders who made the tools I was able to use to mod Fallout 2

#### Bug Fixes
- None

  
<br>

### `Pre-Release`
# **Version 0.9.9.13**
This is a pre-release of the translation. It is has now been **tested**, with multiple playthroughs. Users who wish to experience the first beta release are encouraged to report any bugs, errors in flow, strange speech etc. at the [NMA Thread](https://www.nma-fallout.com/threads/fallout-sonora-1-14-vanilla-translation.222396/).

The naming convention for this release has been altered to allow for several more updates prior to the 1.0 release. The formatting of the translation has also been changed, to allow for use in multiple OS and with multiple versions of Fallout2.exe
The new release format is a single patch file, named patch000.dat

#### Based On
- Fallout: Sonora 1.14 and Dayglow DLC 1.14

#### What's New

- Full tree-pass for Puerto, Vault 25, and all Encounters
- buffout to Buffout, psycho to Psycho, T51b to T-51b

#### Bug Fixes
- None

  
<br>

### `Pre-Release`
# **Version 0.9.9.12**
This is a pre-release of the translation. It is has now been **tested**, with multiple playthroughs. Users who wish to experience the first beta release are encouraged to report any bugs, errors in flow, strange speech etc. at the [NMA Thread](https://www.nma-fallout.com/threads/fallout-sonora-1-14-vanilla-translation.222396/).

The naming convention for this release has been altered to allow for several more updates prior to the 1.0 release. The formatting of the translation has also been changed, to allow for use in multiple OS and with multiple versions of Fallout2.exe
The new release format is a single patch file, named patch000.dat

#### Based On
- Fallout: Sonora 1.14 and Dayglow DLC 1.14

#### What's New

- Tree-pass on all dialogues in Rangers area
- fixed 'reaper' reference to reaver
- Made all quests 'verb' first, to match Fallout 1
- fixed Gyers Wash to Giers Wash
- small fixes in Garage City
- Made most jackal references to Jackal, a proper noun
- changed references to Los Angeles to Angel's Boneyard
- fixed Church of Holy Fire references to Church of the Holy Fire
- Changed 'Community Council' and 'Council of Elders' to village Council in Villa
- fixed some auto-formatted curly quotes to straight quotes
- fixed main menu graphic for Dayglow

#### Bug Fixes
- None

  
<br>

### `Pre-Release`
# **Version 0.9.9.11**
This is a pre-release of the translation. It is has now been **tested**, with multiple playthroughs. Users who wish to experience the first beta release are encouraged to report any bugs, errors in flow, strange speech etc. at the [NMA Thread](https://www.nma-fallout.com/threads/fallout-sonora-1-14-vanilla-translation.222396/).

The naming convention for this release has been altered to allow for several more updates prior to the 1.0 release. The formatting of the translation has also been changed, to allow for use in multiple OS and with multiple versions of Fallout2.exe
The new release format is a single patch file, named patch000.dat

#### Based On
- Fallout: Sonora 1.14 and Dayglow DLC 1.14

#### What's New

- Tree-pass on all of Villa
- small fix to scrname courtesy of Foxx

#### Bug Fixes
- None
  

<br>

### `Pre-Release`
# **Version 0.9.9.10**
This is a pre-release of the translation. It is has now been **tested**, with multiple playthroughs. Users who wish to experience the first beta release are encouraged to report any bugs, errors in flow, strange speech etc. at the [NMA Thread](https://www.nma-fallout.com/threads/fallout-sonora-1-14-vanilla-translation.222396/).

The naming convention for this release has been altered to allow for several more updates prior to the 1.0 release. The formatting of the translation has also been changed, to allow for use in multiple OS and with multiple versions of Fallout2.exe
The new release format is a single patch file, named patch000.dat

#### Based On
- Fallout: Sonora 1.14 and Dayglow DLC 1.14

#### What's New

- massive tree-pass on all of Phoenix
- complete tree-pass on San Brahmin
- Tree-pass on Vault 27
- Standardized some names NPC names, Thalius, Beatriz, German Valdes
- Sunglasses, jumpsuit, rad ash and several other items renamed, or descriptions fixed
- Renamed Klek canyon to Clacks Canyon
- All brahmins to brahmin
- Fixed 'At War with the Army'
- Fixed Ranger ending narration

#### Bug Fixes
- Fixed incorrectly formatted end narration for the Ranger ending
  

<br>

### `Initial Pre-Release`
# **Version 0.999**
This is the first pre-release of the translation. It is still **untested**, but complete. Users who wish to experience the first release are encouraged to report any bugs, errors in flow, strange speech etc. at the [NMA Thread](https://www.nma-fallout.com/threads/fallout-sonora-1-14-vanilla-translation.222396/).

This release also includes a second file, patch002.dat, which includes the translations for the Dayglow DLC.

#### Based On
- Fallout: Sonora 1.14 and Dayglow DLC 1.14

#### What's New

- Finished 'tree-passes' on all of Garage City, Santa Ana, and Flagstaff
- tweaked some world map messages
- Keruk changed to Kuyuk, a more authentic Indian (Mojave/Navajo?) name
- changed overseer Knut to 'Lash'
- Flagstaff mines to mine
- Flagstaff drilling robot and slot machine to drilling machine and pinball game
- Gulf of California mostly changed to Sea of Cortez, except for Californias.
- health and speed/disc to 'hit points and healing rate'
- En Brendly to Anne Brandley
- Stimpacks to Stimpaks
- Added Mexican generic, mexican generic eng , and mexican soldier eng to combat taunts to use with Espanol trait (only with patch003.dat)
- Ranger Citadel to Ranger Base
- some Spanish fixes thanks to OnlyALad
- some random encounter tree-passes
- Some tiny fixes to Villa dialogues thanks to player playthoughs
- removed many cases of 'Understood.' and replaced with more natural, Fallout 1 derived responses
- removed last instances of 'sect' for church of holy fire, replaced with 'cult'
- 'Temple of Fire''Chuch of Fire' consolidated to 'Church of Holy Fire'
- Ranger Jackson to Jason
- Mortal Stike ability to Slayer perk
- some small fixes to casino, thanks Fic_Mon
- some small fixes to Hermosillo, thanks to player playthroughs
- Brahmin scaps and giblets to 'Brahmin Sausages'
- military base in Dayglow to naval base
- Many small fixes thanks to playthroughs from OnlyALad and Fic_Mon


#### Bug Fixes
- Fixed crashing bug in patch001.dat caused by corrupted mainmenu.frm


<br>

### `Initial Pre-Release`
# **Version 0.998**
This is the first pre-release of the translation. It is still **untested**, but complete. Users who wish to experience the first release are encouraged to report any bugs, errors in flow, strange speech etc. at the [NMA Thread](https://www.nma-fallout.com/threads/fallout-sonora-1-14-vanilla-translation.222396/).

This release also includes a second file, patch002.dat, which includes the translations for the Dayglow DLC.

#### Based On
- Fallout: Sonora 1.14 and Dayglow DLC 1.14

#### What's New

- fixed Leviah to Levi
- Many, many small updates thanks to OnlyALad
- San Isidro to San Ysidro
- The Dayglow to 'Dayglow'
- Long Haulers to Far Go Traders
- Seth to Set
- Nightkin dumbed down a tab
- standardized Albert De Santi name
- standardized flare rounds to 'flares' 'modified flares' and 'reinforced flares'
- tin can to Tinsmith, except when PC is addressed while wearing Power Armor
- Badges and tokens fixed to 'dog tags'
- Some chems references switched to drugs
- Power screwdriver to Atomic Cutter
- Laser weapon to Laster Emitter (hand made one from Garage City)
- Emitter to 'Radiator Gun'
- Manhole in sewer hallway to 'Sewer Hatch'
- various fixes to items in pro_scen, thanks to OnlyALad
- 'Don't even think about' references diversified to more natural lines
- 'Treepass' on half of Garage City and most of Inferno
- fire bombs to molotov cocktails
- Alice to Elisa
- Gart to Garth
- Centipede weapon description made more accurate
- Vreya to Vree
- some air spears to pneumatic spears
- fixed Puerto level names numbering to fix error message
- Fixed some pro_crit messages - thanks OnlyALad
- numerous/various fixes from Fic_Mon

#### Bug Fixes
- None yet.


<br>

### `Initial Pre-Release`
# **Version 0.997**
This is the first pre-release of the translation. It is still **untested**, but complete. Users who wish to experience the first release are encouraged to report any bugs, errors in flow, strange speech etc. at the [NMA Thread](https://www.nma-fallout.com/threads/fallout-sonora-1-14-vanilla-translation.222396/).

This release also includes a second file, patch002.dat, which includes the translations for the Dayglow DLC.

#### Based On
- Fallout: Sonora 1.14 and Dayglow DLC 1.14

#### What's New

- changed all location label graphics to correct font, standarized size (like Fallout 1)
- several small fixes thanks to OnlyALad
- Major fixes to 13 Perks thanks to Gusterballs1983: Scrounder's Sense, Computer Whiz, Biker,
Forgotten Hero, Eternal Wanderer (post game play), Wanderer's Intuition, Wasteland Lessons, Math Logic, Block Strick, Hollywood karma, Intimidation, Pack Rat (description only), Alcohol Boots and Reduces (4), Purification, and Radiation Harms
- Small fixes to Editor.msg including restoration of 'drugs','addiction''addicted' etc.
- Chems references converted to drugs, except where originally chems
- Some map names changed, Worldmap location of 'Platform' changed to 'El Faro Pier'
- Small fixes to pro-item.msg fixing numerous items some thanks to OnlyALad and play-through
- Numerous small fixes to pro_scen.msg from play-through
- Coupier changed to Dealer or Card Dealer
- 'Flyers' changed to 'Floaters', dialogues around them improved slightly to lead to this renaming.
- San Felipe and El Faro Pier dialogues all fixed through play-through and script reference
- 'Fishing Club' in El Faro Pier changed to bar or 'Old Lighthouse'
- Thelma's dialogue around 'dad' improved
- Several encoutner dialogues improved 'Gold!' 'Henry Beamis'
- Big update for Hermosillo, including adding Espanol perk dialogue paths for all NPCs, and tweaking all English paths to broken/partially broken English
- Changed fonts to original Fallout 2 fonts, to add back Spanish characters
- extensive fixes to 'powerplant spy' quest in Phoenix, affecting numerous dialogues.
- Small fixes to numerous Two-Sun NPCs after play-through
- small fixes to Chris' interactions/quest thanks to OnlyALad
- made primitive fishermen use mix of English and Yaqui Rather than cave-man talk
- fixed Block scripts language (feedback for destroying fence etc)
- fixed Highwaymen title (for becoming a highwayman)

#### Bug Fixes
- None yet.


<br>

### `Initial Pre-Release`
# **Version 0.996**
This is the first pre-release of the translation. It is still **untested**, but complete. Users who wish to experience the first release are encouraged to report any bugs, errors in flow, strange speech etc. at the [NMA Thread](https://www.nma-fallout.com/threads/fallout-sonora-1-14-vanilla-translation.222396/).

This release also includes a second file, patch002.dat, which includes the translations for the Dayglow DLC.

#### Based On
- Fallout: Sonora 1.14 and Dayglow DLC 1.14

#### What's New

- removed references to 'change the topic', replaced with Fallout 1 lines
- removed references to 'on your mind' replaced with Fallout 1 style lines
- tidied up computer interface dialogues
- renamed some videos
- renamed Casa Grande hacienda to mansion
- renamed (restored) 10mm SFB to NSP - original intent of authors
- renamed commandant to sheriff
- fixed some naming of 'order' to Brotherhood or 'church'
- added dialogue lines for GC brahmin quest to respond to 'buying' the brahmin
- All Casa Nueva dialogues and quests modified by following dialogue trees
- Fixed Flower Child perk to 'Rehabilitation'
- Quarry changed to concrete plant for consistency
- Micro Fusion Cell entries corrected, all Small Energy Cell references removed
- Generator Fusion Cell renamed
- All battery entries for all three types synchronized through scripts for accurate reference
- All Two-Sun dialogues and quests modified by following dialogue trees
- Tinsmiths given more consistent 'cyborg' language
- Sporonos renamed to sporebearer
- fixed energy weapon ammo use
- renamed Reinforced Cattle Prod

#### Bug Fixes
- None yet.


<br>

### `Initial Pre-Release`
# **Version 0.995**
This is the first pre-release of the translation. It is still **untested**, but complete. Users who wish to experience the first release are encouraged to report any bugs, errors in flow, strange speech etc. at the [NMA Thread](https://www.nma-fallout.com/threads/fallout-sonora-1-14-vanilla-translation.222396/).

This release also includes a second file, patch002.dat, which includes the translations for the Dayglow DLC.

#### Based On
- Fallout: Sonora 1.14 and Dayglow DLC 1.14

#### What's New
- modified ZcImgrnt, DCCtznE, NCHimadr, NCMer, HCPost, HCSolder, HSComp, ACCtzCav, CCBosGrd, CCNina, CCNinb, AFTinTan, and EncMexSC script files to standardize Spanish_trait handling.
- modified the matching dialogue files to bring standardized Spanish_trait handling (double angular quotes for Spanish) multiple files required additional lines
- Fixed DCCtzn and NCHimadr scripts, as they were broken/unfinished at several points
- Fixed stray Fame/Glory entries to Karma

#### Bug Fixes
- None yet.

<br>

### `Initial Pre-Release`
# **Version 0.994**
This is the first pre-release of the translation. It is still **untested**, but complete. Users who wish to experience the first release are encouraged to report any bugs, errors in flow, strange speech etc. at the [NMA Thread](https://www.nma-fallout.com/threads/fallout-sonora-1-14-vanilla-translation.222396/).

This release also includes a second file, patch002.dat, which includes the translations for the Dayglow DLC.

#### Based On
- Fallout: Sonora 1.14 and Dayglow DLC 1.14

#### What's New
- fixed many stilted uses of you are to you're
- fixed some pro_scene descriptions that were missing articles
- numerous fixes to multiple Casa Grande NPCs
- major fixes to Casa Grande boss
- numerous fixes to multiple Blue Shield NPCs
- major fixes to Blue Shield boss
- fixed some quotation and apostrophes that were garbled
- restored 'attitude' to 'reaction', based off script comments
- restored 'glory' to 'karma', to synch with fallout 1/2, graphics etc.
- fixed Jimador to Himador
- changed Casa Grande water station to 'water pump'
- fixed an incorrect reference to the 'Long Haulers'
- fixed a few incorrect 'highwaymen' references
- Finished complete pass on all Casa Grande NPCs and fixed all issues.

#### Bug Fixes
- None yet.


<br>

### `Initial Pre-Release`
# **Version 0.993**
This is the first pre-release of the translation. It is still **untested**, but complete. Users who wish to experience the first release are encouraged to report any bugs, errors in flow, strange speech etc. at the [NMA Thread](https://www.nma-fallout.com/threads/fallout-sonora-1-14-vanilla-translation.222396/).

This release also includes a second file, patch002.dat, which includes the translations for the Dayglow DLC.

#### Based On
- Fallout: Sonora 1.14 and Dayglow DLC 1.14

#### What's New
- removed (female) from several lines of dialogue
- fixed mobile fortress encoutner (Fallout_Boy)
- slight fix to Padre encounter (Fallout_Boy)
- added floating lines for hostile scavengers in Garage
- All pipboy entries reformatted
- Some Info.msg lines improved
- fixed use of 'surely' everywhere to suitable terms
- Jackal Burrows to 'Dens'
- Fixes to 'Survey' quest at the Ranger Radio Station
- Multiple fixes to all Jackal PC dialogue

#### Bug Fixes
- None yet.


<br>

### `Initial Pre-Release`
# **Version 0.992**
This is the first pre-release of the translation. It is still **untested**, but complete. Users who wish to experience the first release are encouraged to report any bugs, errors in flow, strange speech etc. at the [NMA Thread](https://www.nma-fallout.com/threads/fallout-sonora-1-14-vanilla-translation.222396/).

This release also includes a second file, patch002.dat, which includes the translations for the Dayglow DLC.

#### Based On
- Fallout: Sonora 1.14 and Dayglow DLC 1.14

#### What's New
- replaced all PC's farewells with 'goodbye'
- nearly all robber instances changed to bandits
- replaced many instances of 'bandit' with 'raider' or 'highwaymen' for wasteland locations, and 'gangster', 'criminal', or 'mugger' for city locations
- replaced 'shelter' with 'vault' in several locations
- Phoenix Master corrected to Lord of Phoenix
- Multiple fixes to Map names
- Mysterious Mansion changed to church
- Multiple fixes to all Platform NPCs
- Some fixes to Rangers NPCs
- Fixes to map quest
- Fixes to naming around Blueshields quests
- Changed worldmap 'Raiders' to 'Highwaymen'
- Fixed some naming around Phoenix fire whorshipper quests
- Numerous small fixes in numerous locations

#### Bug Fixes
- None yet.

<br>

### `Initial Pre-Release`
# **Version 0.991**
This is the first pre-release of the translation. It is still **untested**, but complete. Users who wish to experience the first release are encouraged to report any bugs, errors in flow, strange speech etc. at the [NMA Thread](https://www.nma-fallout.com/threads/fallout-sonora-1-14-vanilla-translation.222396/).

This release also includes a second file, patch002.dat, which includes the translations for the Dayglow DLC.

#### Based On
- Fallout: Sonora 1.14 and Dayglow DLC 1.14

#### What's New
- removed some stray references to the 'Creator' and replaced with 'Master'
- fixed some missing names/lines (Fallout_Boy)
- renamed Pile/Heap/Kucha to 'Gomer' (Fallout_Boy)
- stray 'shadows' references corrected to 'Nightkin'
- some corrections to repeated text (token of gratitude etc.) (Fallout_Boy)
- fixes to location names
- Slight tweaking to pipboy messages layout
- some item and group naming/description fixes (Perry)(Fallout_Boy)
- consolidated Los Panchos boss names (Fallout_Boy)
- attempted to improve clarity between Blue Shields and highwaymen (may need work still)
- fixes to 'Platform' area dialogues
- fixed some male references to be 'neutral' to account for female models
- fixes to Casa Grande area dialogues
- fixes to Kogan and Lucas and Garage City dialogues (Perry)
- stray 'tinkerers' references changed to 'Tinsmiths'
- fixed some incorrect references to 'road armor'
- fixes to Ranger Agatha, cadet Presley and Ranger general and other Ranger dialogues
- fixes to robot grandpa (Fallout_boy)

#### Bug Fixes
- None yet.

<br>

### `Initial Pre-Release`
# **Version 0.99**
This is the first pre-release of the translation. It is still **untested**, but complete. Users who wish to experience the first release are encouraged to report any bugs, errors in flow, strange speech etc. at the [NMA Thread](https://www.nma-fallout.com/threads/fallout-sonora-1-14-vanilla-translation.222396/).

This release also includes a second file, patch002.dat, which includes the translations for the Dayglow DLC.

#### Based On
- Fallout: Sonora 1.14 and Dayglow DLC 1.14

#### What's New
- tweaked Rangers immigrant dialogue to handle quest stages better
- Fixed Ranger radio/spy quest to make the logic correct for accessing dialogue options
- Fixed leftover references to 'Daylight' ... fixed to 'Dayglow'
- Fixed Ranger Radio messages and Radio interface language
- Multiple small fixes to Rangers area
- Renamed several Ranger maps
- Changed rippers to 'reavers'
- Added various fixes to Rangers areas, thanks to Perry
- Added some item and scene message fixes thanks to Perry
- Fixed Kil to Keel, was misnamed in scrname.msg
- Made multiple fixes to multiple files to clarify use of ghouls, demons, and reavers. Added exposition to clarify the connections between these terms.
- Fixes to Santa Ana thanks to Fallout_Boy
- Various dialogue fixes thanks to Fallout_Boy
- renamed mutafruit to mutfruit
- Fixed Diana
- Replaced reconnaissance with 'scouting' in most cases

#### Bug Fixes
- None yet.

<br>

### `Initial Pre-Release`
# **Version 0.98**
This is the first pre-release of the translation. It is still **untested**, but complete. Users who wish to experience the first release are encouraged to report any bugs, errors in flow, strange speech etc. at the [NMA Thread](https://www.nma-fallout.com/threads/fallout-sonora-1-14-vanilla-translation.222396/).

This release also includes a second file, patch002.dat, which includes the translations for the Dayglow DLC.

#### Based On
- Fallout: Sonora 1.14 and Dayglow DLC 1.14

#### What's New
- fixed Henry the Quartermaster
- fixed 'networks' to 'nets' in a few dialogues.
- fixed pathologies to symptoms
- Casa Nueva references switched to 'town' form 'city'
- numerous fixes to Wang Chong
- Fixes to Senor Alvaro and Lo (Fallout_Boy)
- numerous large fixes to Rangers Base NPCs (more to come)
- removed em dash from Dayglow dialogues
- fixed doubled dialogue for Lord of Phoenix (Foxx)
- replaced campesino with peasant
- fixes to Officer Bell
- fixed a few curled apostrophes

#### Bug Fixes
- None yet.

<br>

### `Initial Pre-Release`
# **Version 0.97**
This is the first pre-release of the translation. It is still **untested**, but complete. Users who wish to experience the first release are encouraged to report any bugs, errors in flow, strange speech etc. at the [NMA Thread](https://www.nma-fallout.com/threads/fallout-sonora-1-14-vanilla-translation.222396/).

This release also includes a second file, patch002.dat, which includes the translations for the Dayglow DLC.

#### Based On
- Fallout: Sonora 1.14 and Dayglow DLC 1.14

#### What's New
- fixes to some character and object labels
- fixes to missnamed graphics mostly for Companion control
- renamed all stagecoach instances to caravan

#### Bug Fixes
- None yet.

<br>

### `Initial Pre-Release`
# **Version 0.96**
This is the first pre-release of the translation. It is still **untested**, but complete. Users who wish to experience the first release are encouraged to report any bugs, errors in flow, strange speech etc. at the [NMA Thread](https://www.nma-fallout.com/threads/fallout-sonora-1-14-vanilla-translation.222396/).

This release also includes a second file, patch002.dat, which includes the translations for the Dayglow DLC.

#### Based On
- Fallout: Sonora 1.14 and Dayglow DLC 1.14

#### What's New
- added 'skags' as a swear word
- fixed some item descriptions (Perry and myself)
- fixed some name references -Granny, Geronimo, and tribal child (Perry and myself)
- fixed naming of 'burst' graphic (was missing a period)
- small fixes in San Brahmin and Flagstaff
- numerous fixes in Garage City (Perry)
- fixes to Phoenix postal quests
- fixed cult 'novice' references to Acolyte. Novice still used with brotherhood.
- numerous small fixes in Phoenix cathedral mini-quests
- fixes to Granny Adonsia (Perry)
- fix to Levi dialogue in Inferno - missing a bracket
- Perk fix...several perks misnumbered.

#### Bug Fixes
- None yet.

<br>

### `Initial Pre-Release`
# **Version 0.95**
This is the first pre-release of the translation. It is still **untested**, but complete. Users who wish to experience the first release are encouraged to report any bugs, errors in flow, strange speech etc. at the [NMA Thread](https://www.nma-fallout.com/threads/fallout-sonora-1-14-vanilla-translation.222396/).

This release also includes a second file, patch002.dat, which includes the translations for the Dayglow DLC.

#### Based On
- Fallout: Sonora 1.14 and Dayglow DLC 1.14

#### What's New
- Fixes to 2 dialogues in Garage City based off feedback (Perry)
- Numerous fixes to Geronimo, to improve his 'herder' dialect
- Fixes to location names in Dayglow
- Fixed skills names Barter, Sneak, Outdoorsman, Lockpick, Small Guns, Big Guns, and Unarmed
- Fixed references to firewater, tequila and moonshine. Mostly tequila now
- Made all San Brahmin have more 'Indian/savage' dialect
- Small/Medium fixes to all major characters in San Brahmin
- Added naming and categories to CombatAI.msg for future improvements

#### Bug Fixes
- None yet.

<br>

### `Initial Pre-Release`
# **Version 0.94**
This is the first pre-release of the translation. It is still **untested**, but complete. Users who wish to experience the first release are encouraged to report any bugs, errors in flow, strange speech etc. at the [NMA Thread](https://www.nma-fallout.com/threads/fallout-sonora-1-14-vanilla-translation.222396/).

This release also includes a second file, patch002.dat, which includes the translations for the Dayglow DLC.

#### Based On
- Fallout: Sonora 1.14 and Dayglow DLC 1.14

#### What's New
- fixed wrong quotations marks which came out garbled
- changed most PC 'Thank You' responses to 'Thanks'
- Added more use of 'gotta' for PC
- fixed (hopefully) incorrect formatting in pipboy.msg (text too long)
- Made all cases of 'tinsmiths' into proper noun, 'Tinsmiths'
- Small fixes to Geronimo and Genaro
- Changed 'Garbage Men' of Garage City to 'Scavengers'
- Fixes to Kogan based off feedback
- Fixes to Eugene and Pa based off feedback
- Lots of Fixes to Lord of Phoenix
- Fixes to flow of Cardinals quests

#### Bug Fixes
- None yet.

<br>

### `Initial Pre-Release`
# **Version 0.93**
This is the first pre-release of the translation. It is still **untested**, but complete. Users who wish to experience the first release are encouraged to report any bugs, errors in flow, strange speech etc. at the [NMA Thread](https://www.nma-fallout.com/threads/fallout-sonora-1-14-vanilla-translation.222396/).

This release also includes a second file, patch002.dat, which includes the translations for the Dayglow DLC.

#### Based On
- Fallout: Sonora 1.14 and Dayglow DLC 1.14

#### What's New
- fixed all 'nightkin' to proper noun, 'Nightkin'
- fixed all Casa-Nueva to Casa Neuva
- made all brahmin references lower case, except the 'holy' versions
- fixed all 'Herman Henaro Cipriano Gomez Valdes-y-Castillo' references
- changed Phoenix power station references to power plant for consistency
- slightly fixed a couple of power plant operator dialogues
- changed 'Atomics' gang to 'Power Plant Ghouls' and reduced their 'gang' references
- slight fixes to casino cashier
- numerous fixes to crazy adept at gates of Phoenix
- numerous fixes to Lloyd in Phoenix
- slight fixes to mercenary at Phoenix entrance
- numerous fixes to Sonora Express clerk
- important fix to Red Cardinal boss, to smooth over quest transition
- slight fixes to NPCs in Arena area in Phoenix
- Phoenix Lord changed to Lord of Phoenix in most situations.

#### Bug Fixes
- None yet.

<br>

### `Initial Pre-Release`
# **Version 0.92**
This is the first pre-release of the translation. It is still **untested**, but complete. Users who wish to experience the first release are encouraged to report any bugs, errors in flow, strange speech etc. at the [NMA Thread](https://www.nma-fallout.com/threads/fallout-sonora-1-14-vanilla-translation.222396/).

This release also includes a second file, patch002.dat, which includes the translations for the Dayglow DLC.

#### Based On
- Fallout: Sonora 1.14 and Dayglow DLC 1.14

#### What's New
- Fixed an 'Invaders' reference to Raider
- Fixed the Barman in Flagstaffs responses
- Fixed the Randy and the Raiders dialogues in Flagstaff
- Fixed the Drugdealer in Phoenix's dialouge
- Fixed Lloyd in Phoenix, making him a little more 'street'
- Fixed a GECK reference

#### Bug Fixes
- None yet.

<br>

### `Initial Pre-Release`
# **Version 0.91**
This is the first pre-release of the translation. It is still **untested**, but complete. Users who wish to experience the first release are encouraged to report any bugs, errors in flow, strange speech etc. at the [NMA Thread](https://www.nma-fallout.com/threads/fallout-sonora-1-14-vanilla-translation.222396/).

This release also includes a second file, patch002.dat, which includes the translations for the Dayglow DLC.

#### Based On
- Fallout: Sonora 1.14 and Dayglow DLC 1.14

#### What's New
- Added patch002.dat for Dayglow DLC
- Fixes for Dayglow naming
- Changed black prospector to rogue scavenger
- Aligned all zombie references to ghouls, except in Vault 27
- Aligned all San-Brahmin to San Brahmin
- Fixed a few battery reference to Fuel cell
- Made several characters (caravaners) say ya' and yer' more often
- Changed 'nuclear scientists' to 'power plant operators'
- Fixed several stray 'tinker' references to Tinsmiths.
- Many small dialogue specific fixes in numerous locations.
- consolidated signal flares etc. to 'flares' or 'flare rounds'
- removed all instances of cartridge, replaced with rounds or bullets, like Fallout 1
- removed ... characters, as it appeared garbled
- improved dialogues of Phoenix market sellers

#### Bug Fixes
- None yet.

<br>

### `Initial Release`
# **Version 0.9**
This is the first release of the translation. It is still **untested**, but complete. Users who wish to experience the first release are encouraged to report any bugs, errors in flow, strange speech etc. at the [NMA Thread](https://www.nma-fallout.com/threads/fallout-sonora-1-14-vanilla-translation.222396/).

#### Based On
- Fallout: Sonora 1.14

#### What's New
- First release.

#### Bug Fixes
- None yet.

<br>
