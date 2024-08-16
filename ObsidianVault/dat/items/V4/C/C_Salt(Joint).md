---
LastUpdate: 2023-10-17
RECIPES: false
PROPERTIES: false
STRINGS: false
DISTRIBUTION: false
TRADE: false
Deployment: Collect
CollectIcon: CubeMultiple(Sheet01/55)
Category: BasicItems_Provisions
Stack: 100
Icon: CubeMultiple(Sheet01_a/55)
tags:
  - Container_Food
  - LocationDescription_Food
  - LootGenerator_Trader
  - Scavengable
Sound: UI_Lootable_Consumable
Value: C9
Description: A potent and necessary mineral derived from certain tree roots. Used for preserving meat and flavoring dishes.
Foraging: 5/anywhere
Stock: 100
Supply: C - 50%
Demand: 1
Vendors:
  - Food
---

###### RECIPES
- C(3-)@[[D_MudOven(Trap)]]:0.5/1HR
	- ==2[[C_Roots(008_item)]]==
	- [[B_CleanWater(005_item)]]
	- [[A_FireBundle(QualityJoint)]]
