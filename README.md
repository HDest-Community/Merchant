# Merchant

[![Nightly Build](https://github.com/HDest-Community/merchant/actions/workflows/nightly.yml/badge.svg)](https://github.com/HDest-Community/merchant/actions/workflows/nightly.yml)

### Important
---
- This mod requires [AceCoreLib](https://github.com/HDest-Community/AceCoreLib).
- There are three merchants, one for each type of item: weapons, ammo, and items.
- Up to three merchants can spawn on a map. They have a different inventory each time, meaning some items may be missing.
- You can carry the merchant by using Sprinting + Use. Put them down by crouching and holding the sprint key for half a second. You can only carry one merchant at a time.
- Monsters will now drop a random amount of currency, based on a few factors and scaled based on the `hdm_nonbounty_dropratio` CVar.
  - This is separate from Tiberium and/or Bounties.  If you'd prefer to only get money from either of those two systems, just set `hdm_nonbounty_dropratio` to `0.0`.
  - The same is true the other way around, if you'd prefer to only get money randomly through killing normal monsters, just set the Money Mode to "neither".

### Notes
---
- Change between currencies using the Page Up/Down keys.
- Change between categories using the Left/Right arrow keys, and between items with the Up/Down arrow keys
- Loadout code for the mercenary bucks is `bux`.
- CVars are:
	`hdm_cardback [0-1]`: Card back graphic.

### Tiberium
---
- Crystals can spawn in secret sectors and can only be "mined" with a chainsaw. You can also shoot them to clear out a path but don't expect them to drop much.
- Sectors with tiberium crystals will be toxic. Don't attempt to mine without a radsuit, you will die. Chunks will also be toxic.
- Blue crystals are much rarer and also much more dangerous.
- There is no guarantee you'd be able to mine a field if it's too large. That's a severe case of "working as intended". If you are clever enough, you might be able to do it with some strategic planning. But don't expect to always succeed.

### Bounty
---
- One of the enemies on the map, out of those valid, will have a bounty on their head. They can be recognized by the special effect other monsters do not have (if any).
- The standard effect is added or increased shield and increased health, along with increased aggressiveness. These enemies will be much deadlier and harder to kill.
- More valid targets for bounty and more effects (chosen at random) may be added by additional addons.
- Monsters that can currently be a target of bounty:
	- Healer Imps
	- Marines
	- Hell Knights/Barons
	- Cacodemons
	- Archviles
	- Cybers/Masterminds
	- Melodica's Cabal Cultists

### Slot Machines
---
Why play when you can gamble? Machines spawn in secret sectors, much like merchants, and cost 10 7mm rounds to roll. Hold Sprint when pressing Use to insert another min bet worth of rounds for a higher reward.
Payouts are as follows:
- 1 Stim = x1
- 2 Stims = x2.5
- 3 Stims = x5
- 3 Medkits = x10
- 3 Potions = x25
- 3 Spiritual Armors = x50
- 3 Megaspheres = x100
- 3 Precious = x200

### Poker
---
- A game of Texas Hold'em can be assembled with up to 8 nearby players (2m radius) using the `HDM_AssemblePokerGame` command. The players can be either AI-controlled (merchants) or other human players.
- Each player needs to have the amount of the big blind ($20) in mercenary bucks in order to join the game.
- If you walk away from the game, your bet is forfeit. You can shoot enemies if they show up, but do not go outside of the table's marked area.
- No idea how to play? See this: https://www.youtube.com/watch?v=b9HYxquQt-M
- The only way to quit is to walk away. Yes, you will lose what's in the pot. Yes that is intentional. Consider it a tax for getting to leave early.

### Modding
---
- The following custom UDMF properties are recognized by the mod:
	- `user_merchantsector [false/true]`: setting this to true will always spawn a merchant in this sector. Type of merchant is still randomized.
	- `user_merchantangle [0 - 360]`: The angle the merchant will have when they spawn.
	- `user_slotmachinesector [false/true]`: same as `user_merchantsector` but for slot machines.
	- `user_slotmachineangle [0 - 360]`: same as `user_merchantangle` but for slot machines.

### Known Issues
---
- Merchants can block some paths sometimes. Grab them or pick them up to move them out of the way.
- Tiberium crystals can block some paths. Either shoot a path through them or climb them.

### Credits
---

Original Mod Credits are displayed below.
- Cryomundus, for porting original mod to HDest Community Organization, updating as needed.
- Undead Zeratul, adding all sorts of Shop Entries & filters, updating ZForms, redesigning Shop Menu, incorporating FDA's HDest Avarice Coins mini-mod.
- FDA, for originally porting Avarice Coins into a compatible addon for Merchant.

Code:
- Accensus
- arooкas for the hand eval code. If I ever stop praising the guy, assume I died.

Sprites:
- Merchant (Hobo): Strife (Rogue)
- Merchant (Resident Evil): Based on above but made by PillowBlaster. Ten points to Gryffindor!
- Merchant (Daina skins): Hege Cactus. Taken from La Tailor Girl.
- Merchant (Succubus): YuraoftheHairFan, Espi, Ebola, Vader; greatly edited by Mor'ladim to match my high standards, the absolute madman and legend.
- Merchant (Morshu): Legend of Zelda by Capcom; rotations edited by HegeCactus.
- Merchant (Minecraft): Based on the Wandering Trader from Minecraft (Mojang), edited by Craneo.
- Bucks: Pillowblaster
- Chips: https://www.gamedeveloperstudio.com/graphics/viewgraphic.php?item=482839ps487in390430 // I didn't actually buy this. I ripped it like an absolute bastard. I wanted to buy it but account registrations are DISTUSTANG.
- Playing cards: https://www.spriters-resource.com/nec_pc_8801/ginga/sheet/107022/
- Tiberium: KANE HIMSELF! Nah, Pillowblaster.

Sounds:
- Poker stuff: https://www.sounds-resource.com/pc_computer/tabletopsimulator/sound/24381/
- Card deal sound by arookas.

ZForms:
- Gutawer & phantombeta

Card backs:
- Default: same as the rest of the cards.
- Classic: arooкas.

Additional:
- Kat, additional store items
 
#### Avarice Coins Mod Original Credits:

All Coin sprites:
- HorrorMovieRei, carvings on the coins based on Freedoom assets (The coin sprites are free to use in any mod or TC, commercial or not)

Small Gem sprites:
- Tyrian 2000 by Eclipse Software

Big Gem sprites:
- Sonic Spinball by Sega

Money shine sprites:
- Super Turrican 2 by Factor 5

Chest Sprites:
- RPG Maker XP by Enterbrain

Coin bouncing sound:
- Freedoom (Edited by HorrorMovieRei)

Gem bouncing sound:
- Blasphemer

Big Gem slamming sound:
- Blasphemer

Coin/Gem pickup Sounds:
- Rise of the Triad by Apogee Software

Decorate Code and ACS:
- HorrorMovieRei

Director code:
- Although I've wrote it from scratch, it is a technique that Beed28 gave me permission to use a long time ago for another unrelated mod, and I have been using this same technique ever since, so I feel like shouting them out is the right thing to do!

Zscript for making the coins fly towards you:
- Melodica
