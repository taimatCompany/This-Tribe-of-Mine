---
LastUpdate: 2023-09-28
RECIPES: false
PROPERTIES: false
STRINGS: false
DISTRIBUTION: false
TRADE: false
Deployment: Collect
CollectIcon: CubeSingle(Sheet01/54)
Category: Consumables_Cooking
Stack: 20
Icon: CubeSingle(Sheet01_a_54)
tags:
  - LootGenerator_Trader
  - Scavengable
  - LocationDescription_Food
  - Container_Kitchen
Sound: UI_Lootable_Consumable
Value: C9
Description: A tablespoon of refined animal fat used in soap making and cooking.
Foraging: 1/anywhere
Stock: 1
Supply: A - 99%
Demand: 0.02
Vendors:
  - Food
---

###### RECIPES
- A(10--)@[[G_Kitchen(Cooker2)]]: 0.5+1HR
	- ==2[[B_Meat(RawFood)]]==
	- [[A_FireBundle(QualityJoint)]]
	- 2[[B_CleanWater(005_item)]]
- B(10--)@[[Recycling_Cookpot]]: 0.1+3HR
	- ==C3[[B_Meat(RawFood)]]==
	- 2[[A_FireBundle(QualityJoint)]]
	- B4[[B_CleanWater(005_item)]]

###### PENDING
