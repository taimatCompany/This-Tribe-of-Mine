---
LastUpdate: 2023-10-02
RECIPES: false
Deployment: Inventory
CollectIcon: 
Category: Tools
Stack: 5
Icon: x
tags:
  - Container_Weapons
  - LootGenerator_Trader
  - Scavengable
  - LocationDescription_Tool
Sound: UI_Lootable_Melee
Value: C9
Description: Timeless, classic - the original sharp object. Made of metal, stone, or bone.
Speeches: 
Looting: 0-5@anywhere
Trading: 100% chance of 0-20
TradeModifier: 1
Influences:
---

###### RECIPES
- C(2)@[[G_WoodShop(BasicWorkshop2)]]: 2+0HR
	- ==[[B_Meat(RawFood)]]==
- C(1)@[[G_SawHorse(BasicWorkshop)]]: 0.1+0HR
	- ==[[A_Hardware(WeaponParts)]]==
	- [[B_Fabric(Materials)]]
- C(6-)@[[G_MetalShop(MetalWorkshop)]]: 0.25+0HR
	- [[C_ScrapMetal(Parts)]]
	- C3[[B_Fabric(Materials)]]