---
LastUpdate: 2023-09-17
LastImport: 2023-09-18
LastPublish: 2023-09-15
Deployment: Inventory
CollectIcon: 
Category: Materials_Supplies
Stack: 100
Icon: Hardware(Sheet02_a_33)
tags:
  - LocationDescription_Parts
  - LootGenerator_Trader
  - Scavengable
  - Timeline_Materials
  - Container_Furniture
Sound: UI_Lootable_Tools
Value: A1
Description: Screws, bolts, nails, hinges, blades, and other useful metal pieces.
Speeches: 
Looting: 0-20@anywhere
Trading: 100% chance of 10-50
TradeModifier: 1
Influences:
---

###### Recipes
- A(9--)@[[G_MetalShop(MetalWorkshop)]]: 0.5+0HR
	- [[C_ScrapMetal(Parts)]]
- C(9--)@[[G_SawHorse(BasicWorkshop)]]: 0.1+0HR
	- ==D3[[C_Lumber(Wood)]]==
	- [[B_Prybar(Crowbar)]]
- C(5-)@[[G_SawHorse(BasicWorkshop)]]: 0.05+0HR
	- ==[[C_DirtyGunpart(Shotgun_broken)]]==
- C(5-)@[[G_SawHorse(BasicWorkshop)]]: 0.05+0HR
	- ==[[D_CleanGunpart(Pistol_broken)]]==