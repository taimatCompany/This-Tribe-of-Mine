---
LastUpdate: 2024-08-16
RECIPES: false
PROPERTIES: false
STRINGS: false
DISTRIBUTION: false
TRADE: false
Deployment: Inventory
CollectIcon: x
Category: BasicItems_Provisions
Stack: 10
Icon: x
tags:
  - LocationDescription_Food
  - Container_Kitchen
  - LootGenerator_Survival
  - Scavengable
Sound: UI_Lootable_Consumable
Value: D27
Influences:
  - Sick
  - Depression
  - Hungry
  - Tired
Description: Can't eat this without cooking it. Have some fruit instead.
Speeches:
  - HungryRefusal
  - RawMeatUsage
Foraging: 
Stock: 15
Supply: 25%
Demand: 1.5
Vendors:
  - Food
---

###### RECIPES
*cheapest on top*
- C(4-)@[[G_Kitchen(Cooker2)]]: 0.25+0HR
	- ==[[C_Carcass(BrokenToy)]]==
- D(2)@[[D_MudOven(Trap)]]: 0.5+0HR
	- [[C_Knife(Knife)]]
	- ==[[C_Carcass(BrokenToy)]]==
