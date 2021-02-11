# Using fork of jopeek's Loot Sheet NPC 5E to create a NPC loot sheet for Genefunk 2090 - No current releases (WIP) - Go to jopeek/fvtt-loot-sheet-npc-5e for 5E version updates

This module aims to add an additional NPC sheet to the Genefunk 2090 game system which can be used for loot containers such as containers or shopkeepers. It also allows hacks to be automatically converted into sellable items by dragging them onto this sheet. 

This version was forked from Jopeek's module for 5e (https://github.com/jopeek/fvtt-loot-sheet-npc-5e/network/members). 

### Features

Allows for easy assembly of items and credits to be distributed to players.

More features detailed below.

##### Permissions
Permissions can be set in the sheet for each player and range from no access (cannot open sheet) to observer (view sheet and contents) to owner (view sheet and add/remove items).

##### Shopkeeper Sheet
Can be used to create an inventory of a shopkeeper to allow players to peruse their inventory. Prices are listed next to each item.

##### Price Modifier
Prices can be adjusted by percentage for all owned items.

A Biography tab is also available.

##### Credit Distribution
Any credits in the sheet can easily be split evenly across all players with owner access. The math and distribution is done for you via a single click if you're the GM.

##### Create hack items
Dragging of hacks into the sheet will automatically turn them into sellable items.

### Compatibility:
- Tested with FVTT v0.5.3.

### Known Issues:
- Dragging an item out of the sheet does not actually remove it from the sheet's inventory.
- Price Modifier currently doesn't save owned item prices properly on Tokens, so the button will not appear on tokens. Believe this to be related to a FoundryVTT issue. 
- Currently can't get back to original prices, especially if percentage is set to 0.
