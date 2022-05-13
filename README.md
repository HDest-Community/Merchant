### Important
---
- This mod requires [AceCoreLib](https://gitlab.com/accensi/hd-addons/acecorelib).
- There are three merchants, one for each type of item: weapons, ammo, and items.
- Up to three merchants can spawn on a map. They have a different inventory each time, meaning some items may be missing.
- You can carry the merchant by using Sprinting + Use. Put them down by crouching and holding the sprint key for half a second. You can only carry one merchant at a time.

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
- A game of Texas Hold'em can be assembled with up to 8 nearby players (3m radius) using the `HDM_AssemblePokerGame` command. The players can be either AI-controlled (merchants) or other human players.
- Each player needs to have the amount of the big blind ($20) in mercenary bucks in order to join the game.
- If you walk away from the game, your bet is forfeit. You can shoot enemies if they show up, but do not go farther than 4m away from the spot you occupied when the game started.
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