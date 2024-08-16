---
LastUpdate: 2023-09-24
RECIPES: false
PROPERTIES: false
STRINGS: false
DISTRIBUTION: false
TRADE: false
Deployment: Collect
CollectIcon: BreadLoafThin(Sheet01/19)
Category: BasicItems_Provisions
Stack: 2
Icon: BreadLoafThin(Sheet01_a_19)
tags:
  - LootGenerator_Trader
  - Scavengable
  - Container_Food
  - LocationDescription_Food
Sound: UI_Lootable_Consumable
Value: D27
Description: A loaf of homemade bread with a tough exterior to prevent insect damage. Needs a knife to be cut.
Foraging: 0/nowhere
Stock: 3
Supply: 25%
Demand: 1.5
Vendors:
  - Food
  - Army
  - Merchant
---

###### RECIPES
*cheapest on top*
- D(1)@[[D_MudOven(Trap)]]:1+3HR
	- [[C_Salt(Joint)]]
	- C3[[A_FireBundle(QualityJoint)]]
	- [[B_BakingSoda(Fluorescent)]]
	- [[B_Sugar(Sugar)]]
	- ==2[[B_Flour(ContainerSmall)]]==
	- [[B_CleanWater(005_item)]]

###### PENDING
*planned recipes that could slowly modify prices*