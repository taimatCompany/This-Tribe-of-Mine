---
LastUpdate: 2023-09-17
LastImport: 2023-09-21
LastPublish: 2023-09-23
Deployment: Inventory
CollectIcon: 
Category: Guns_Combat
Stack: 50
Icon: WeaponParts(Sheet02_a_17)
tags:
  - Container_Scrap
  - Scavengable
  - Timeline_Parts
  - LocationDescription_Scrap
  - LootGenerator_Ammo
Sound: UI_Lootable_Ammo
Value: C9
Description: Old, dirty gun parts. Could be salvaged for hardware and scrap, or cleaned up with a little love and some oil.
Speeches: 
Looting: 0-5@someplaces
Trading: 75% chance of 0-20
TradeModifier: 1.25
Influences:
---

###### RECIPES
1. C(9--)@[[H_MachineShop(metalWorkshop2)]]: 0.5+0HR
	- [[D_Rubber(FoodScraps)]]
	- C3[[B_Kindling(004_item)]]
	- B5[[A_Hardware(WeaponParts)]]
	- [[C_ScrapMetal(Parts)]]
2. E(15--)@[[G_SawHorse(BasicWorkshop)]]: 0.1+0HR
	- ==[[G_Shotgun(Shotgun)]]==
3. E(20--)@[[G_SawHorse(BasicWorkshop)]]: 0.1+0HR
	- ==[[G_SniperRifle(SniperRifle)]]==
4. E(25--)@[[G_SawHorse(BasicWorkshop)]]: 0.1+0HR
	- ==[[G_Pistol(Pistol)]]==
5. F(30---)@[[G_SawHorse(BasicWorkshop)]]: 0.1+0HR
	- ==[[H_Machinegun(Machinegun)]]==

###### PENDING