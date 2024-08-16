---
LastUpdate: 2023-10-14
RECIPES: false
PROPERTIES: false
STRINGS: false
DISTRIBUTION: false
TRADE: false
Deployment: Inventory
Category: Tools_ToolsAndMedicine
Stack: 5
Icon: Hatchet(Sheet05_a/09)
tags:
  - Container_Weapons
  - LocationDescription_Tool
  - LootGenerator_Trader
  - Scavengable
Sound: UI_Lootable_Tools
Value: C9
Description: A sharp object... on a stick! Doubles as a hammer.
Foraging: 1/anywhere
Stock: 10
Supply: C - 50%
Demand: 2
Vendors:
  - Merchant
  - Residents
  - Smuggler
CollectIcon: 
Influences: 
Speeches: 
Suppliers: 
Consumers:
---

###### RECIPES
*cheapest on top*
- C(1)@[[G_SawHorse(BasicWorkshop)]]: 1+0HR
	- [[B_Kindling(004_item)]]
	- B3[[A_Twine(Mixer)]]
	- ==2[[A_Hardware(WeaponParts)]]==
- C(1)@[[G_MetalShop(MetalWorkshop)]]: 0.5+0HR
	- 2[[B_Fabric(Materials)]]
	- B3[[A_Twine(Mixer)]]
	- ==[[C_ScrapMetal(Parts)]]==