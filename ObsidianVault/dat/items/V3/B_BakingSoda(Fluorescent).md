---
LastUpdate: 2023-09-28
RECIPES: true
PROPERTIES: false
STRINGS: true
DISTRIBUTION: false
TRADE: true
Deployment: Collect
CollectIcon: BoxOpenTiny(Sheet02_o/39)
Category: BasicItems_Provisions
Stack: 100
Icon: BoxOpenTiny(Sheet02_a/39)
tags:
  - LootGenerator_Trader
  - Scavengable
  - LocationDescription_Food
  - Container_Kitchen
  - Timeline_WoodAndFuel
Sound: UI_Lootable_Consumable
Value: C9
Description: Also known as Sodium Bicarbonate. A white powder used in baking, crafting, and smelting.
Foraging: 20/anywhere
Stock: 50
Supply: B - 75%
Demand: 0.5
Suppliers:
  - Cooks
Consumers:
  - NonCookResidents
---

###### Recipes
- B(10--)@[[D_MudOven(Trap)]]: 0.1+2HRS
	- ==C9[[A_Greens(Plants)]]==
	- B3[[A_FireBundle(QualityJoint)]] 