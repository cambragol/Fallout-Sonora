---
layout: page
title: Extra
include_in_header: false
---

# Fallout: Sonora - Patched
This page contains the optional 'patched' install file for bugs and dialogue/quest fixes and improvements for Fallout: Sonora + Dayglow DLC. It contains both the full English translation for the Vanilla version and the Dayglow DLC, along with over 90 quest, dialogue and general fixes. This version of the translation provides the best English experience for Fallout: Sonora.

[<img class="center" src="https://raw.githubusercontent.com/cambragol/Fallout-Sonora/refs/heads/main/assets/Screen%20Shot%20Patches.png" width="300" />](https://github.com/cambragol/Fallout-Sonora-English/releases/download/1.0/sonora_eng_DLC_script.zip "sonora_eng_DLC_script.zip")

### `Install Instructions for Sonora + Dayglow DLC + Script Patch 1.0`
# **Version 1.0**

1. Download and install [Fallout Sonora](https://cloud.mail.ru/public/jsg1/HSrkfMyPB)
2. Download and unpack [Dayglow DLC](https://cloud.mail.ru/public/s3bg/oiJr6N1Gh) into the install directory of Fallout Sonora, created above
3. Download your OS version of [Fallout 2 CE](https://github.com/alexbatalov/fallout2-ce/releases/tag/v1.3.0) and put it in the install directory of Fallout Sonora, created above
4. Download the .zip file named [sonora_eng_DLC_script.zip](https://github.com/cambragol/Fallout-Sonora-English/releases/download/1.0/sonora_eng_DLC_script.zip) and unzip it in the install directory of Fallout Sonora
5. Change the language setting of the fallout2.cfg file to 'english'
6. Click 'Fallout II Community Edition' (for macOS and windows and linxu) to play the game

**_Optional_** - if on windows, Fallout2.exe may be dropped into the install folder to play the game, **or** rename patch000.dat to patchDLC.dat and use FSonora.exe or FSonoraDLC.exe to run the game. Only FSonora.exe or FSonoraDLC.exe will give the correct game start


<br>


### `Script Patch`

# **Version 1.0**
This is the a first release of the script patch. It is has been tested. Users who wish to experience the most polished version of Fallout: Sonora in English are encouraged to use the script patch in the zip provided above. Uses are encouraged to report any bugs at the [NMA Thread](https://www.nma-fallout.com/threads/fallout-sonora-1-14-vanilla-translation.222396/).

#### Quest and Dialogue Fixes/Improvements

- YCBoss.ssl - restored a node to flesh out mission setup
- YCGhlMat.ssl - fixed incorrect NodeAnswer
- YCIsdCrh.ssl - fixed incorrect dialogue option 221 to 222
- YCLiveB.ssl - added recognition of the Ghoul perk, which was missing, but setup
- YSMonoGh.ssl - fixed activation point for the Monorail quest when being activated by the monorail supervisor
  
<br>

### `Script Patch`

# **Version 0.10**
This is the a pre-release of the script patch. It is still mostly **untested**. Users who wish to take advantege of the fixes and quest/dialogue improvements are welcome to, though they are encouraged to report any bugs at the [NMA Thread](https://www.nma-fallout.com/threads/fallout-sonora-1-14-vanilla-translation.222396/).

#### Quest and Dialogue Fixes/Improvements

- SCBoss.ssl added small Spanish Trait use
- SCShpBoy - fixed incorrect reply in script
- tweaked PVCOvrser as there was an incorrect reaction result in script
  
<br>

# **Version 0.9**
This is the a pre-release of the script patch. It is still mostly **untested**. Users who wish to take advantege of the fixes and quest/dialogue improvements are welcome to, though they are encouraged to report any bugs at the [NMA Thread](https://www.nma-fallout.com/threads/fallout-sonora-1-14-vanilla-translation.222396/).

#### Quest and Dialogue Fixes/Improvements

- fixed a misdirected node in RCAcvBnd to correct the dialogue
- fixed a node in RCAcvTlk to complete the 'Fish' trade route for Garage City quest
- added a bit check in RCBoss to prevent a conversation loop.
- added a bit check in RCFrmMan to prevent make a conversation start more natural, using existing dialogue lines
  
<br>

# **Version 0.8**
This is the a pre-release of the script patch. It is still mostly **untested**. Users who wish to take advantege of the fixes and quest/dialogue improvements are welcome to, though they are encouraged to report any bugs at the [NMA Thread](https://www.nma-fallout.com/threads/fallout-sonora-1-14-vanilla-translation.222396/).

#### Quest and Dialogue Fixes/Improvements

- added small espanol trait use for Jose

<br>

# **Version 0.7**
This is the a pre-release of the script patch. It is still mostly **untested**. Users who wish to take advantege of the fixes and quest/dialogue improvements are welcome to, though they are encouraged to report any bugs at the [NMA Thread](https://www.nma-fallout.com/threads/fallout-sonora-1-14-vanilla-translation.222396/).

#### Quest and Dialogue Fixes/Improvements

- Fixed BCCrvnQT to make limit the response if Phoenix not known yet
- BCGarPst - fixed backwards skill check, bonusReaction corrected
- BCMisBos - fixed Mark_state_visited to Mark_state_unknown
- BCMisSld - added Espanol trait to spanish song
- PCGopStp - fixed dialogue options
- PCMerkBs - Many fixes, head claiming was broken/messed up. Fixed multiple nodes, and dialogue
- PCBdBos - added alternate answers for one node
- PCPrtznA - added check to see if PC knows Matthias
- PCScvTlk - gave armor reaction correct dialogue number
- PCCasBar - Changed int check from -4 to 1
- PCAtmBld - Added dialogue node to complete dialogue as written
- PCAtmBos - added node to makes sense of negative answer to job offer
- PCAtmClt - added nore graceful conversation exit

<br>

### `Initial Pre-Release`

# **Version 0.6**
This is the first pre-release of the script patch. It is still mostly **untested**. Users who wish to take advantege of the fixes and quest/dialogue improvements are welcome to, though they are encouraged to report any bugs at the [NMA Thread](https://www.nma-fallout.com/threads/fallout-sonora-1-14-vanilla-translation.222396/).

#### Quest and Dialogue Fixes/Improvements

- upgraded Espanol Trait to translate mexican and spanish 'combat taunts' (multiple scripts)
- fixed bug with Nightkin Boss rescue in Dayglow (YCMutBos.ssl)
- fixed incorrect reply bug CCNina.ssl
- fixed incorrect reply bug CCCrvBos.ssl
- fixed CCBoss.ssl to prevent big response being repeated on main dialogue node
- Added fix to PCBdLohB.ssl to have floating message of revenge after end of quest
- fixed goodbye message in FCSlvRdr.ssl
- fixed FCCtznB.ssl to make better transition to offer to cure kid
- changed FCBishop to have 'idiot' node more in line with other idiot nodes
- Added 'Brahmin Sausages' to Flagstaff barman and used this for food delivery quest (FCBarmen.ssl and FCAdmin.ssl)
- Added Espanol_Trait to GCPit.ssl dialogue
- Fixed GCGate.ssl to have correct result for successful perception check - also added Jackal quest ditch node.
- Added node to GCBrmAtk.ssl to have better responses for buying the brahmin
- fixed VCRobot.ssl to differentiate between grandson/daughter, and use Espanol_Trait
- Added Espanol_Trait to ZIUseStp.ssl

<br>

# **Version 0.5**
This is the first pre-release of the script patch. It is still mostly **untested**. Users who wish to take advantege of the fixes and quest/dialogue improvements are welcome to, though they are encouraged to report any bugs at the [NMA Thread](https://www.nma-fallout.com/threads/fallout-sonora-1-14-vanilla-translation.222396/).

#### Quest and Dialogue Fixes/Improvements

- Fixed the feedback for ZSblock to not spam 'destroying' process with constant 'look' messages
- Modified HCBoss, HCPrisnr, HCRunchA, HCRunchB, and HCRunchC to incorporate use of the Espanol Perk

<br>

# **Version 0.4**
This is the first pre-release of the script patch. It is still mostly **untested**. Users who wish to take advantege of the fixes and quest/dialogue improvements are welcome to, though they are encouraged to report any bugs at the [NMA Thread](https://www.nma-fallout.com/threads/fallout-sonora-1-14-vanilla-translation.222396/).

#### Quest and Dialogue Fixes/Improvements

- updated OBJ_CAR.ssl to account for trying to power with a Generator Fusion Cell
- fixed brahmin quest at Bar to account for buying the brahmin, rather than stealing - GCBarmen.ssl and GCBrmPsA.ssl
- fixed TCBoss.ssl to use correct dialogue line when discussing ZAX being destroyed
- fixed TCCrvBos.ssl to use correct node  when responding to paying for escort
- fixed TCCrvQst.ssl to only off generator cell if the quest is started. Moved quest start as well and added zReply to use amigo/amiga correclty
- fixed TCCtzTlk.ssl to add missing dialogue from dialogue file.
- fixed TCCult.ssl to give Science check different results. Original had identical results.
- fixed TCTins.ssl to make 'worker' and 'guard' tinsmiths have different 'look' descriptions and different floating lines.
- fixed NCApcAst.ssl to force the PC to correctly work to get access to pre-war medicines/drugs
- multiple small fixes to NCApcBos to improve dialogue and include missing lines
- fixed NCQuestA to prevent endlessly introducing oneself
- improved NCSilosA.ssl to make dilalogue smoother

<br>

# **Version 0.3**
This is the first pre-release of the script patch. It is still mostly **untested**. Users who wish to take advantege of the fixes and quest/dialogue improvements are welcome to, though they are encouraged to report any bugs at the [NMA Thread](https://www.nma-fallout.com/threads/fallout-sonora-1-14-vanilla-translation.222396/).

#### Quest and Dialogue Fixes/Improvements
- modified ZcImgrnt, DCCtznE, NCHimadr, NCMer, HCPost, HCSolder, HSComp, ACCtzCav, CCBosGrd, CCNina, CCNinb, AFTinTan, and EncMexSC script files to standardize Spanish_trait handling.
- Fixed DCCtzn and NCHimadr scripts, as they were broken/unfinished at several points

<br>

# **Version 0.2**
This is the first pre-release of the script patch. It is still mostly **untested**. Users who wish to take advantege of the fixes and quest/dialogue improvements are welcome to, though they are encouraged to report any bugs at the [NMA Thread](https://www.nma-fallout.com/threads/fallout-sonora-1-14-vanilla-translation.222396/).

#### Quest and Dialogue Fixes/Improvements
- Fixed incorrect text line reference in MCRio.ssl
- Fixed incorrect text line reference in MCBoss.ssl
- Finished incomplete and non-working scripting for DCCtznE.ssl

<br>

# **Version 0.1**
This is the first pre-release of the script patch. It is still mostly **untested**. Users who wish to take advantege of the fixes and quest/dialogue improvements are welcome to, though they are encouraged to report any bugs at the [NMA Thread](https://www.nma-fallout.com/threads/fallout-sonora-1-14-vanilla-translation.222396/).

#### Quest and Dialogue Fixes/Improvements
- added intermediary steps and dialogue logic to 'Brahmin Quest' in GCBrmAtk
- fixes to dialogue logic to discuss looking for Villa people that are already found - FCMadre
- fixes to end of quest for freeing trapped Villa kin, added dialogue on Mine Exit - FCVillaA
- fixes to FCBoss to make the idiot PC Rat King quest work
- fixes to pinball machine quest in FCBarmen
- made PCDrgdlr push his stuff with floating lines
- fixed all three Sonora express scripts so PC recognizes after visiting one
- fixed Phoenix Sonora express 'letter' quest to have better dialogue logic - PCPost
- fixed RCAcvTlk to have better dialogue logic
- added mid-quest feedback for 'spy quest' to PCMaster
- added mid-radio-quest feedback and dialogue logic to RCComndr
- fixed dialogue logic and 'spy' quest for RCRngRad
- added fixes to start of quest with RCPresly
- fixes to RCAgata to fix start of quest with Presley
- changed coordinates of repeater in ZIRadio
- fixed CCNina to make Spanish perk work correctly
- fixed quest to restore power to Monorail in YSMonoGh
- added clues and improvements to AFGold 'map' quest
- multiple fixes to the 'survey' quest in RCRngMap
- fixes to ZTMap for Jackals raid quest and Inferno Robot event bug
- fixes to GCGate dialogues for Jackal quest and first vist
- added fixes to 'Jackal attack' quest in GCMercJc, and added quest fail consequences

<br>
