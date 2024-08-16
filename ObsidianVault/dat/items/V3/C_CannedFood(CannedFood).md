---
LastUpdate: 2023-10-02
RECIPES: true
Deployment: Inventory
CollectIcon: 
Category: BasicItems_Provisions
Stack: 8
Icon: x
tags:
  - Scavengable
  - Container_Food
  - LocationDescription_Food
  - AngerManagement_Food
  - LootGenerator_Trader
Sound: UI_Lootable_ConsumableFluid
Value: C9
Description: Canned meat, vegetables, or maybe even chili or soup.
Speeches:
  - HungryRefusal
  - CannedFoodUsage
Influences:
  - Hungry
  - Sick
Foraging: 5/anywhere
---

###### SUMMER
- F(20--)@[[G_Office(HerbalWorkshop)]]: 0.5HR+Random1
	- [[G_Voucher(AdvancedTools)]]

###### RECIPES
- C(1)@[[H_MachineShop(metalWorkshop2)]]: 0.5+0HR
	- [[B_ColdCuts(ShotgunAmmo)]]
	- [[C_Salt(Joint)]]
	- B3[[A_Hardware(WeaponParts)]]
- E(1)@[[H_MachineShop(metalWorkshop2)]]: 0.5+0HR
	- B3[[A_Hardware(WeaponParts)]]
	- C10[[A_VegetableSlices(001_item)]]
	- [[D_Vinegar(002_item)]]