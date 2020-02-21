<p align="center">
  <img src=".\media\halbui_mod.png">
  <br>
  <b>v0.4.1</b>
</p>

# <strong><span style="color:green">halbUI</span></strong> for Fallout Shelter

## What is this?
A mod for Fallout Shelter (currently only for Steam and Android versions) intended to remedy some UI issues present in the retail version, and provide some quality-of-life improvements that make the game easier and more enjoyable to play.

<strong><span style="color:green">halbUI</span></strong> is not a content modification or a cheating tool, and does not aim to alter the fundamental game experience.

## Changes to vanilla Fallout Shelter
* __Heal All button__ -- apply a Radaway and a Stimpak to every Dweller in a room or quest team with one click
* __Evacuate button__ -- If a Radscorpion just popped up in a training room of Level 1 Dwellers and you're scrambling to move all them to safety, fear not! There's now an Evacuate button that un-assigns all Dwellers from the target room at once, causing them to abandon the room and run for cover
* __Repair Mr. Handy button__ -- Mr. Handy has been upgraded and can now be repaired in the field - for a price! - instead of having to wait for him to explode
* __Send Outside button__ -- Additional button added to the Dweller UI that allows you to send a Dweller exploring, or evict them, from wherever they are in the Vault.
* __Coffee Break button__ -- Additional button added to the Dweller UI that allows you to un-assign a dweller from whatever task they were engaged in and set them wandering around the Vault.
* __Drag Lock toggle__ -- enable this and Dwellers cannot be picked up and dragged. Prevent messing your vault up with accidental reassignments when you're just trying to scroll around
* __LVL-UP Lock toggle__ -- enable this and the 'LVL UP' button over Dwellers' heads is deactivated. Often (particularly in Survival Mode) you actually don't _want_ to level Dwellers up and doing so with a misclick is frustrating
* __Cam Lock toggle__ -- enable this and camera control will never be hijacked from you again. Births, emergencies, attacks from outside, you name it - the camera will remain where you put it, always
* __Return After Incident toggle__ -- enable this and Dwellers, when an incident ends, will no longer run back to where they were when it started. Sometimes you just want to rearrange your Dwellers while a fire's burning itself out somewhere, but have to twiddle your thumbs because when it ends they'll go back to their original positions - this behavior is now optional rather than mandatory with <strong><span style="color:green">halbUI</span></strong>.
* __Quick Look UI options__ -- As well as the name tag floating over a Dweller's head, you can now optionally also see the name/rarity of their weapon, outfit and pet, or their stat/damage bonuses from outfit and weapon. View the whole loadout of a room with a click
* __Lots of extra info added to the UI:__
  - The Dweller panel now also shows you the Dweller's total max HP (including modifiers such as pets), and the average Endurance per level that they've been levelled up with so far - no more renaming your characters to keep track of what outfit you leveled them with
  - The amount of Lunchboxes, Pet Carriers, Mr. Handy boxes, and Nuka-Cola that an exploring Dweller has found in the Wasteland, either through quests or random encounters, is now displayed in the Wasteland UI
  - The total amount of items (weapons, outfits and junk) that an exploring Dweller has found is now displayed in the Wasteland UI - the carry limit is 100 and it's nice to know how close to that mark you are
  - Item icon backgrounds in the Dweller inventory panel are colorised by rarity, helping to differentiate between the many sets of outfits that re-use the same sprites
  - Item names in the Dweller gear selection lists are color-coded by rarity
  - The total amount of the relevant stat present across all working Dwellers in production/crafting/etc rooms is displayed in the Room UI
  - Dwellers' equipped weapons are displayed along with their name in the room-overview sidebar, for another way of skimming loadouts quickly
  - The time remaining for a pregnancy, in minutes and seconds, is now shown in the Dweller UI
  - Dragging a Dweller to a room with an open slot will show you a breakdown of where their relevant stats for that room come from. In Vanilla FS you were just shown a number between 1 and 10 (even if the effective stat was above 10); now the tooltip is shown in the form Base Stat + Outfit Bonus
* __Quality of Life improvements:__
  - Dwellers' inventories in the Wasteland are now _always_ sorted by rarity, then by type and then by name. See all their good stuff at a glance instead of having to scroll through everything
  - Vault Storage items are now sorted by rarity and then by name. The sort ordering is user-configurable (descending or ascending rarity). In retail Fallout Shelter everything is thrown haphazardly into storage in whatever order you found it; now you can navigate easily to whatever you're looking for
  - You can now sell 10 of an item at a time from storage, for a happy medium between vanilla FS's options of selling either 1 item at a time or all items at once
  - For each item type (weapon/outfit/junk/pet) there is now a button that lets you sell every Common-tier item of that type in one shot
  - Tabbing through exploring Dwellers in the Wasteland is now faster
  - SPECIAL stat increases now take priority over XP level ups - you are no longer forced to level up a Dweller before continuing to train their SPECIAL stats

## Releases

Version 0.4.1 of <strong><span style="color:green">halbUI</span></strong> is currently in a closed testing phase.

## Installation

Before proceeding with installation __please back up your saves__.

### Windows (Steam)
Copy `Assembly-CSharp.dll` to the `FalloutShelter_Data\Managed` folder under your root Fallout Shelter directory (the default path to this folder is `C:\Program Files (x86)\Steam\steamapps\common\Fallout Shelter\FalloutShelter_Data\Managed`). You're done! 

### Android
- Copy the .apk file and `com.bethsoft.falloutshelter` folder to your device.
- Place the `com.bethsoft.falloutshelter` folder into the folder `Android\obb` in your internal storage.
- Install the .apk.

Please be sure to perform these last two steps in that order. Installing the .apk first will cause it to look for the extra game data, fail to find it, and try to download it, which will not work as the .apk has been modded.


## FAQ

### Can I install <strong><span style="color:green">halbUI</span></strong> and continue to play my current Vault?
* Yes.
### Can I revert to vanilla Fallout Shelter if I don't like <strong><span style="color:green">halbUI</span></strong>?
* Yes. It won't affect your save file in any way.
### Can I still purchase Lunchboxes, Pet Carriers, Mr. Handys and Nuka-Cola while using <strong><span style="color:green">halbUI</span></strong>?
* On Windows via Steam, yes (I spent £0.79 of my own money to verify this - you're welcome).
* On Android, not directly, as it is a modded .apk and so will not connect to Google Play. You can get around this by copying the save file to a vanilla installation of FS, buying whatever you want, and moving the save file back.
### Can I install <strong><span style="color:green">halbUI</span></strong> for Android alongside an existing installation of Fallout Shelter?
* At present, no. Vanilla FS must be uninstalled first (remember to back up your saves before uninstalling if you are 'upgrading' to <strong><span style="color:green">halbUI</span></strong>). Side-by-side installs of vanilla and <strong><span style="color:green">halbUI</span></strong> FS is a goal for a future release.