### Important
---
- There are three merchants, one for each type of item: weapons, ammo, and items.
- Up to three merchants can spawn on a map. They have a different inventory each time, meaning some items may be missing.
- Escorting the merchants to the exit will give you a 20% boost per merchant to whatever money you have earned, but will also remove them from the map, meaning they will no longer be there in the case of hubs. They can still spawn on the next map, however. In multiplayer games, the distance to the arbitrator (usually team leader) is taken into account, and not whoever exited the level. To escort all merchants in multiplayer, have all of them near the arbitrator, then exit the level.
- You can carry the merchant by using Sprinting + Use. Put them down by crouching and holding the sprint key for half a second. You can only carry one merchant at a time.

### Notes
---
- Change between currencies using the Page Up/Down keys.
- Change between categories using the Left/Right arrow keys, and between items with the Up/Down arrow keys
- Loadout code for the mercenary bucks is `bux`.

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