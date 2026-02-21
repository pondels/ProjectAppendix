# MineBot Update Changelog
## These will look like Discord messages because they were initially sent out as messages through Discord.
<strong>Version numbers will be different than originally posted to reflect realistic version control (as there was no system before now)</strong>
---
# Feb. 21, 2026
# 1.1 The Combat Update
### New Features
  - **New Command**: `/fight`
    - Fight creatures from an array of dimensions
    - Choose who you fight, and get rewards based on the creature you fight
    - See what your odds are of winning a fight, and the potential loot you could yield
    - Combat is structurally the same, with a few added features
    - Now will receive SXP from combat
    - On failed encounter, will receive half User XP and SXP, as well as no loot from the creature
    - Drops now account for armor power bonus
    - New fight tab in in the MineBot Hub and in `/help`
  - **Creatures now have a base SXP value** based on their difficulty
  - **New Tool**: Sword (kinda)
  - **New Upgrades** For Sword
    - Pheromone: Increase number of creatures you fight per combat
    - Withering: Chance to gain double Sword XP from creatures
    - Durability: Increase the base amount of durability of your sword
  - **New account settings** for sword messages
  - **New economy system** for personalized upgrading per tool
  - **Money is now specific to the tool you are using and is referred to as Tool XP (TXP)**
  - **Complete Potions Overhaul**
    - Potions are now craftable starting from the overworld
    - Potion recipes completely changed
    - Potions are now crafted using essence
  - **New quick menu** in the mines (visualized with a +)
    - Use items quick menu
    - Upgrade quick menu
    - Smelt quick menu
    - Craft quick menu
    - Armory quick menu
    - Fight quick menu
  - **Added 2 new forms**, one where you [create](https://docs.google.com/forms/d/e/1FAIpQLSf_HSAbrc9X0be5fdjEqXzq3NKrkhRmShBwNM0oU8O0e9v0Ag/viewform?usp=publish-editor) an account and [delete](https://docs.google.com/forms/d/e/1FAIpQLSf8HeuCAU7BfB48EybapUyI-FGicjOHhP5-9a3xV8IyvsNa5Q/viewform?usp=publish-editor) your account (for servers as well)

### Small Changes
  - Creature drops recategorized in inventory
  - `/brew` now limits your potions to what you are able to craft based on progression
  - Lure potion changed from % chance to encounter a creature to % chance of another creature being fought
  - Durabliss potion now applies to all tools
  - Inheritence and incomprehensible greed now affect all tools
  - Changed all instances of money to either TXP, PXP, or SXP
  - Swapped out money in crates to a mixture of SXP and PXP
  - New achievements to reflect the new upgrades
  - Data requests now decrypt any encrypted data for added security (no more potential reverse engineering)
  - New update message notification formats
  - Added 2 new cosmetics
    - Weeb: Stickman holding a body pillow
    - Biker: Stickman wearing a bandana holding a helmet
  - (If server members intent is approved) Server owners will now receive an exit form for MineBot to fill out if they remove minebot from their servers.
  - User `/stats` menu now shows each individual tool with their respective durability and tool experience
  - `/world_info` temporary formatted differently
  - Changed formatting in `/server_stats`
  - Updated various wording in `/info`
    - Your Account will now link to the Privacy Policy
    - Voting changed money modifier to Tool XP Modifier
    - Slight rewording in the Upgrades panel
    - Armor money modifier changed to TXP modifier
    - Creature encounters adjusted to reflect the new combat system
    - Money and XP field changed to Tool XP and User XP respectfully
  
### Balances
  - Adjusted creatures base AC
  - Changed creatures loot pool
  - Tool upgrade price changes
  - Increased rage upgrade max to 4
  - Tweaked vampire upgrade effect
  - Added another Rage upgrade
  - Balanced Enlightened Fixation
  - Tweaked how many times Cherophobia can be casted
  - Amend spell now repairs all tools and not just the pickaxe
  - Tweaked lure potion effect

### Bug Fixes
  - Fixed a bug where minebot would go offline randomly for an unknown amount of time
  - Opening crates now adds to your total experience gained
  - Fixed a bug where the mystery potion would active inactive holiday potion effects

### Known Issues
  - GUIs are still kinda choppy (in the works)
  - Same issues as prior update
---
# Dec. 27, 2025
# 1.1 HotFixes
- Fixes
  - (This was a woopsy daisy) You can now use `/contact` without the need of an account
  - Drop modifier displayed incorrect information, and is now corrected
  - There are now checks to see if a user has DMs enabled to recieve DM notifications
  - Relative time corrections for items smelting, pickaxe repair, and other relative times to bot launch
  - Fixed some misinformation in `/info`
  - Fixed `/setup`, `/recover` and mining to no longer ping users with messages, and instead send them as silent messages.
- Known Bugs
  - Clickable commands are still only working for server administrators
---
# Nov. 24, 2025
# 1.0 Full Release! (wooo)
- New Features
  - Can now request
    - Your MineBot Account Data
    - Your Server's MineBot Account Data (if you're the server owner)
  - We now have an official email for you to contact us through with questions using `/contact` or by looking at MineBot's profile
  - You can now customize exactly what you see when you mine blocks in the mines in `/account`!
  - More events created (What will they be? :eyes:)
  - Server admins can now `/purge` all MineBot generated channels and categories via command or when removing their server from MineBot's Database
- Small Changes
  - Terms of Service and Privacy Policy updated! (viewable in `/info`)
  - `/recover` now asks for confirmation before creating and deleting old MineBot channels
  - Update Channel now has a default changelog embed to see previous updates
  - MineBot's name is now just MineBot and not MineBot (/help)
  - Updated the message MineBot sends when invited to a server
  - Changed commands referenced to be clickable through messages
    - (This only effects commands ran in channels where commands can be typed)
  - Slight adjustments to the tutorial
  - Can now convert all items for rewards all at once instead of one at a time.
  - Crates now contain more than 1 item
- Balances
  - Reworked the Economy
  - Reworked Crafting Recipes
- Fixes
  - Fixed changes on Bot status display
  - Fixed the blocks mined stat to now compound off of all your profiles instead of a per-profile basis
  - Fixed a bug where the tutorial wouldn't show if all steps were completed
  - Fixed a bug where certain tool upgrades weren't being caught in the achievements
- Known Bugs
  - Clickable commands only work for server administrators
---
# Oct. 22, 2025
# 0.16 Reworks!
- **New Features**
  - `/find` now explains what enchantments and potions do
  - `/info`
    - Now displays event items during an active event
    - Now has a section for events
  - MineBot will now play random games throughout the day
- **Small Changes**
  - Changed Enchantment Names
    - Fortune -> Extraction
    - Mending -> Vitality
    - Looting -> Harvest
- **Balances**
  - Adjusted recipes
  - Adjusted tool upgrade prices
  - Adjusted server modifiers for ore chance and xp
  - Changed the ring armor slot to be consistent with each dimension
  - Packs drop fewer base blocks than before
- **Fixes**
  - MineBot will now delete server data when leaving a server.
  - Fixed a bug where xp and money modifiers applied from armor were flipped
  - You can now no longer mine in dimensions you are not yet able to mine in (progressive-wise)
  - Server admin panel can now handle up to 100 roles for custom notifications
  - Soul-Steal spell works as intended
  - Changed enchantments to upgrades
  - Changed mobs/monsters to creatures
  - Fixed a bug where your profile could have trailing whitespace
  - Fixed visual bug with drop modifier being inaccurately displayed
---
# Sept. 30, 2025
# 0.15 Spooky Month 
**New Features**
- New MineBot Hub with quick commands for easy accessibility!
- `/find` now can search for enchantments, potions, spells, crates, event items and currencies.
- Crates (Obtainable in `/trade`)
  - Use in `/use_items`
  - Chance of getting a random item from a loot pool
- Holidays and Events
  - Mine blocks to find an event's unique currency to buy holiday exclusive items!
  - Claim rewards in `/rewards` to purchase/brew event specific items!
  - Brew event exclusive potions in `/brew` to gain better rewards during the event!
  - Find event specific packs while mining to purchase more event items quicker!
  - Upgrade event enchantments to increase your outcome for each event!
  - Purchase crates using event tokens to get exclusive rewards!
  - Event items are cleared at the end of an event **except** for crates.
**Balances**
- `/find` now allows for searching up event items
- `/inventory` now categorizes event items
**Fixes**
- `/mine` removed in favor of the buttons in the mining channels
  - Can no longer send messages in the mining channels
- Various wording changes in the tutorial.
- Reformatted `/help` wording
- Formatting changes in the inventory
- Fixed a bug where users weren't receiving update notifications
- Fixed a bug where drinking potions softlocks you for the day
---
# Sept. 14, 2025
# 0.14 Balances and Corrections
**Balances**
- Discovery pickaxe upgrade now sells and multiplies.
- Mob drops now vary instead of bulk drop 1 item
- Odds for ores being found have been reworked
- Ore spawn server modifier changed
- Armor bonus is now a power bonus.
  - Always get the lowest power bonus instead of a set bonus (this system is just better)
- Packs are more balanced in drops and XP
  - Packs now give money
**Fixes**
- `/stats` now differentiates account and profile statistics
  - New stats shown for account
- Several enchantment values tweaked
- `/account` settings now visually shows settings
- Voting now has an `/info`  related tag on the message
- Corrected a visual error with voting not switching out at the correct time
- `/find` now displays readable fractions for ore lookup
- Updated tutorial step 1 to be up to date
- Several formatting changes across informational commands
---
# Aug. 15, 2025
# 0.13 Out With the Old, In With the New!
- Can no longer send unwanted messages in mining/update/tutorial channels
- `/contribute` is no longer a command!
  - All ores and dimensions are unlocked by default
- `/admin_panel` now lets you opt-in/out of update notifications, while also choosing a custom role to ping when minebot updates!Cosmetics!New server feature, Voting!
  - Vote for a new cosmetic to be displayed the next day
  - Vote for a global modifier to help aid all players in the server in a given categoryView more in-depth details in /info -> VotingNew tutorial step for voting!
## QoL
- Mining is faster
- `/find` now attaches the block as an image for a much better visual aid
  - Now displays odds of a block being found
  - Links related ChannelMade /world_info a bit more readable
- Drinking potions is now more clearYou can see how long an event lasts
- All times are based on user local time and are now translatable
- Slight visual upgrades to the armory and /stats for viewing armor stats
- Users and Servers will now start receiving notifications if desired!
  - Will no longer recover the notifications channel if you do not want to receive notifications
- When setting up your server, you will be prompted to confirm you want all the channels created before it happens
## Bug Fixes
- Fixed a bug where you could try deleting your already deleted server
- Fixed a visual bug where rewards would say to wait to claim even though it was claimableFixed formatting issues in /info for mobile usersFixed a bug where you could claim rewards when a streak was made
---
# Jun. 21, 2025
# 0.12 Overhauls!
- **Completely Overhauled `/trade`**
- **`/tutorial` updated to include new commands**
- **New tutorial channel in servers**
- **`/rewards` now has proper streak rewards implemented**
- **Added New Item | *Spells***
  - **New spell: Fireball**
  - **Can trade for spells using tickets from `/rewards`**
  - **New Spell information in `/stats`**
- **New Information in `/info`**
  - **Added Media Information**
  - **Added Recovery Information**
  - **Added Account Information**
  - **Added Spell Information**
  - **Added Money/XP Information**
- **`/report` and `/suggestion` are now `/contact`**
- **Moved `/settings` into `/account`**
- **Changed initial Direct Message to a standard message when you create your account**
- **`/mine` (while still a command) is now interactable through buttons!**
- **Messages that used to respond with "Noted" no longer show up!**
- **You can now go back tabs in the `/account` command**
- **You can now suppress mining messages in account settings!**
- **Rewards can now be claimed at the beginning of the day instead of exactly 24 hours after claiming**
- **Fixed Several Exploits and Bugs**
---
# Apr. 21, 2025
# 0.11 Shower Me In Rewards!
- **DMs are no longer part of the flow**
   - The only time you will receive DM's is when you specify in `/settings`
   - Your direct messages will need to be open for MineBot to send you DM's
- **`/help` now distinguishes between admin-only and user commands**
   - This is primarily to avoid confusion of what a user and server admin can do
- **Better end-user communication for MineBot expectations**
   - Wording for lots of usage has been vague, and I have since adjusted a lot of the wording
- **`/world_info` reworked**
   - You will now get an itemized list of all ores, drop rates, and percentages for the server
- **Buttons across menus are now visually consistent**
- **A new `/admin_panel` for server administrators to configure server data**
   - (no configurations made yet) though you can remove your server from the database if you so choose
- **New `/rewards` command to receive rewards over a timed basis**
   - This is including weekly and monthly streaks
   - This adds potential for holiday events and timed exclusive items.
- **Autosmelt will now automatically be enabled and stay enabled, as it's useless to toggle on/off**
- **Buttons and selections will no longer expire**
   - Before your messages would stop working after a few minutes. This is no longer the case. (theoretically)
- **`/leaderboard` temporarily removed (potentially permanent)**
   - There are a few concerns of privacy that I want to address, and this is a feature I feel should be opted into
   - I have plans for progression that could help keep things balanced no matter how many players there are
      - This could lead to not needing a leaderboard anymore, so it's gone temporarily until figured out
---
# Mar. 24, 2025
# **0.10 Small Changes and Bug Fixes**
- **`/profiles` is now `/account`**
- **You can now delete your profile from the database using `/account`**
- **Fixed a bug where crafting multiple items could miss an achievement**
- **`/server_stats` refactored to be easier to use**
- **Fixed a bug with recovering deleted channels**
---
# Jan. 26, 2025
# **0.9 Bug Fixes and QoL**
- **`/contribute` now shows what dimensions are locked**
- **`/recover` is more verbose on what happens behind the scenes**
- **`/smelt` now has a button to auto-smelt everything**
- **`/armory` now displays your active set bonus**
- **Crafting achievement is now properly being accounted for**
- **Furnace enchantment logic changed slightly**
- **Fortune on the pickaxe is fixed (wrong enchantment was being used before)**
- **All messages should now self-destruct after 5 minutes to devoid clutter**
- **Daily reminders are now more clean and only show important information**
- **Your balance in `/contribute` and `/stats` is now properly being rounded**
- **Packs will now display a preview of what's inside**
- **You can now choose how many packs you would like to open instead of all at once**
---
# Dec. 24, 2024
# **0.8 Update - QOL and Early Access!**
- __**The Full release is now live and ready to go! (though in early access)**__
   - You can now add MineBot to your own server [here!](https://top.gg/bot/1082189783654219776)
- **New Command `/tutorial`**
   - New users will be prompted with this command to get started
   - The tutorial covers all necessary commands for game progression
- **New Command `/find`**
   - You can now find items using this command
   - Spelling does not need to be perfect, and will try its best to find what you're looking for!
- **`/global_stats` renamed to `/leaderboards`**
   - You can now view player leaderboards and see top players in a given category
- **New Settings**
   - Added a new flag to notify players about updates to MineBot
   - Added tutorial notifications to notify players for the completion of a tutorial step
- **Auto Crafting**
   - Can now go to the recipe you want to craft and auto-craft the recipe
   - If unable to craft, you will receive an itemized list of missing ingredients
- **Bug Fixes and Changes**
   - The mystery potion now gives the effect of the durabliss potion
   - Commands that broke in player DM's no longer do
   - Messages sent via `/info` no longer linger in your DM's and break
   - Smelting achievement now accounted for the auto-smelting flag
---
# Dec. 10, 2024
**0.7 Update - Potions!**
- **`/report` and `/suggestion` have been added back in!**
- **Potion Revamp**
  - Potion recipes are now live and ready to brew in `/brew`
  - `/brew` UI slightly cleaned up
  - New Potion: **Lure**
  - New Potion: **Mystery**
- **`/recipes` has been deprecated from `/craft` and is now removed**
- **Bug Fixes and Changes**
  - Achievements slightly changed to better fit the general progression
  - General release flow mapped out
---
# Sept. 29, 2024
**0.6 Update - QOL and Other Cool Stuffs**
- **New Things for `/craft`**
   - You can now see what armor sets belong to which dimension
   - Dimensions representing templates now get removed when you craft all required ones
- **`/contribute` now shows which dimensions are maxed out**
- **Officially Removed `/report` and `/suggestion`**
   - This means there will be no more official support for bug reports and suggestions within MineBot
   - Bugs and Suggestions can still be made out in #minebot-discussion just not through a command
- **Bug Fixes and Changes**
   - Fixed a bug where you couldn't unlock all ores in the Zenith Dimension
   - Profiles now have sanitized Inputs
   - Fixed a bug when crafting items with resources you don't have
---
# Sept. 18, 2024
**0.5 Update - Armor and Crafting!**
- **Armor Is Now Craftable**
  - A system is now comprised to allow for armor progression and crafting your way up to better
  - Recipes no longer only contain artifacts and now comprise of templates alongside those artifacts
  -  Armor Templates have a tier system to craft into better gear
  - You slowly unlock these templates as you complete full armor sets to progress to the next dimensions
**As always, if you have any bugs you find or concerns with how things are laid out, please suggest/report said items in #minebot-discussion  <3**
*(this update is bigger than it sounds I promise, this is basically everything but it adds a ton)*
---
# May. 12, 2024
**0.4 Update - QOL and UI**
- **Better UI For Contributions**
  - Instead of a massive text dump, you get a neat list of ores you've unlocked
  - Clears up any confusion of what is needed and what you have obtained
- **New command `/world_info`**
  - Contrary to the name, this command shows stats about a given world
  - Shows the block unlocked, with its respective value and spawn chance
- **Removed `/suggestion` and `/report`**
  - This removal is currently temporary
  - Any bugs and suggestions should be sent over in #minebot-discussion 
---
# Feb. 22, 2024
**0.3 Update - Mining and QOL**
- **Complete Mining Overhaul!**
  - Instead of having to wait x amount of days, you pick and choose the mines you wish to mine from!
  - This negates any issues with new players joining and having to wait longer than expected
  - This is also just necessary in general
- **Admin Command `/recover`**
  - Used to recover lost channels
  - Can now mine and continue if the original message was deleted
  - Can run the command to restore all lost channels if lost
  - Restores all mine messages as well and preserves the old status
- **Quality of Life Changes**
  - You can view your balance in `/upgrade`
  - You can view your current durability when mining
  - The inventory has been moved to its own function `/inventory`
  - Stats now only contains statistics
  - Can now view where to obtain smelted materials from `/smelt`
# Dec. 21, 2023
**0.2 Update - Archaeology Overhaul!**
- **Added New Command: `/trade`**
  - You can now take artifacts and trade them for lower, current, or higher ranks for better flexibility when crafting with artifacts
- **Reworked Archaologist Enchantment**
  - Artifacts drop significantly more often, as they barely dropped before
  - Artifacts now have tiers, Common, Uncommon, Rare, and Epic
  - The conversion table is as follows:
    - Common (x2) -> Uncommon
    - Uncommon (x4) -> Rare
    - Rare (x5) -> Epic
- **Bug Fixes:**
  - Resolved issues with the archaeologist enchantment not being able to purchase due to achievement issues

**Find Some Artifacts Boys! :eyes:**
---
# Dec. 10, 2023
**0.1 Update - More Organized Information**
- **Improved /info Command:**
  - **Change:** `Blocks and Items` selection is  now organized into pages.
  - **Why:** To enhance readability and prevent overly long embeds.
- **Bug Fixes:**
  - Resolved several issues including developer testing commands, and opening packs in DMs.

**Thank you for your continued support!**
