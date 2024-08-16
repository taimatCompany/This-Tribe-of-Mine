---
LastUpdate: 2023-09-17
RECIPES: false
PROPERTIES: false
STRINGS: false
DISTRIBUTION: false
TRADE: false
Deployment: Collect
CollectIcon: BottleThick%(Sheet05_o_55)
Category: BasicItems_Provisions
Stack: 20
Icon: BottleThick%(Sheet05_a_55)
tags:
  - Scavengable
  - Container_Treasure
  - Container_Kitchen
  - AngerManagement_Food
  - LootGenerator_Skarby
Sound: UI_Lootable_ConsumableFluid
Value: C9
Influences:
  - Tired
  - Depression
Description: The most ancient of alcohols, made from fruit, sugar, and natural yeasts.
Speeches:
  - HoochUsage
Foraging: 3/anywhere
Stock: 20
Supply: C - 50%
Demand: 1
Vendors:
  - Food
  - Merchant
  - Smuggler
---

###### RECIPES
- C(9--)@[[G_Distiller(HoochGear)]]: 0.5+24HR
	- D9[[B_Sugar(Sugar)]]
	- [[C_Filter(Filter)]]
	- ==C9[[A_Berries(Vegetables)]]==
	- C3[[B_CleanWater(005_item)]]
	- [[A_Greens(Plants)]]

