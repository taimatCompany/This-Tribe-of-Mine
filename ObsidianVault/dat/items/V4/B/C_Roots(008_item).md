---
LastUpdate: 2023-10-14
RECIPES: false
PROPERTIES: false
STRINGS: false
DISTRIBUTION: false
TRADE: false
Deployment: Inventory
Category: BasicItems_Provisions
Stack: 20
Icon: Vegetables(Sheet05_a_03)
tags:
  - Container_Food
  - LocationDescription_Food
  - LootGenerator_Trader
  - Scavengable
  - Container_Kitchen
Sound: UI_Lootable_Consumable
Value: B3
Description: Stringy plant roots or starchy vegetables. Can be cooked or used to make twine.
Foraging: 3/anywhere
Stock: 10
Supply: B - 75%
Demand: 0.5
Vendors:
  - Food
  - Merchant
---

###### SUMMER
- C(1)@[[D_MudOven(Trap)]]:0.1+0HR
	- ==B3[[A_Dirt(000_item)]]==

###### RECIPES
- C(1)@[[D_MudOven(Trap)]]:0.1+0HR
	- ==[[B_WildPlants(Blade)]]==
