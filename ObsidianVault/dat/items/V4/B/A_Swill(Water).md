---
LastUpdate: 2023-10-14
RECIPES: false
PROPERTIES: false
STRINGS: false
DISTRIBUTION: false
TRADE: false
Deployment: Inventory
CollectIcon: WaterDrop(Sheet02_o_29)
Category: BasicItems_Provisions
Stack: 20
Icon: WaterDrop(Sheet02_a_29)
tags:
  - Container_Bathroom
  - LocationDescription_Food
  - Scavengable
Sound: UI_Lootable_ConsumableFluid
Value: A1
Description: Water that is polluted, stagnant, or otherwise unfit for drinking.
Foraging: 20/anywhere
Stock: 1
Supply: A - 99%
Demand: 0.02
Vendors:
  - Merchant
---

###### Summer
- A(20--)@[[D_RainBarrel(waterCollector)]]: 0.1+24HR

###### Recipes
- A(10--)@[[G_Kitchen(Cooker2)]]: 0.05+2HR
	- [[A_Snow(Snow)]]
- C(1)@[[G_SawHorse(BasicWorkshop)]]: 0.05+0HR
	- [[B_CleanWater(005_item)]]