---
LastUpdate: 2024-08-16
RECIPES: true
PROPERTIES: false
STRINGS: false
DISTRIBUTION: false
TRADE: false
Deployment: Inventory
CollectIcon: 
Category: BasicItems_Provisions
Stack: 20
Icon: Fruit(Sheet02_a_05)
tags:
  - LootGenerator_Trader
  - AngerManagement_Food
  - Container_Kitchen
Sound: UI_Lootable_Consumable
Value: A1
Influences:
  - Hungry
  - Sick
  - Depression
Description: A handful of sweet, edible berries. Could be eaten raw or used for wine or seeds.
Speeches:
  - VegetableUsage
  - HungryRefusal
Foraging: 0/nowhere
Stock: 1
Supply: A - 99%
Demand: 0.02
Vendors:
  - Food
---

###### RECIPES
- A(30---)@[[G_Kitchen(Cooker2)]]: 0.1/0 HR
	- ==[[B_WildPlants(Blade)]]==
	- [[B_CleanWater(005_item)]]
- A(10--)@[[G_Kitchen(Cooker2)]]: 0.05/0 HR
	- ==[[B_WildPlants(Blade)]]==
- A(3-)@[[G_SawHorse(BasicWorkshop)]]: 0.05/0 HR
	- ==[[B_WildPlants(Blade)]]==