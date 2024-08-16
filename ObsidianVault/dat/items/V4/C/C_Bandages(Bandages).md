---
LastUpdate: 2023-10-17
RECIPES: false
PROPERTIES: false
STRINGS: false
DISTRIBUTION: false
TRADE: false
Deployment: Inventory
Category: ToolsAndMedicine
Stack: 20
Icon: x
tags:
  - Scavengable
  - Container_Bathroom
  - LootGenerator_Med
  - LocationDescription_Medicine
  - Timeline_Materials
  - AngerManagement_Bandages
Sound: UI_Lootable_Consumable
Value: C9
Influences:
  - Wounded
Description: x
Speeches:
  - BandageRefusal
Foraging: 1/anywhere
Stock: 40
Supply: C - 50%
Demand: 2
Vendors:
  - Medic
  - Merchant
  - Army
---

###### RECIPES
1. C(1)@[[G_SawHorse(BasicWorkshop)]]: 0.25+0HR
	- [[B_Fabric(Materials)]]
	- ==[[A_Tobacco(Tobacco)]]==
2. E(15--)@[[G_SawHorse(BasicWorkshop)]]: 0.25+0HR
	- ==F3[[E_Vodka(Alcohol)]]==
	- C5[[B_Fabric(Materials)]]
3. E(3-)@[[G_SawHorse(BasicWorkshop)]]: 0.25+0HR
	- ==[[E_Vodka(Alcohol)]]==
	- [[B_Fabric(Materials)]]
4. E(1)@[[G_SawHorse(BasicWorkshop)]]: 0.25+0HR
	- ==[[D_Vinegar(002_item)]]==
	- [[B_Fabric(Materials)]]
5. F(30---)[[G_Office(HerbalWorkshop)]]: 0.25+RANDOM1
	- ==[[G_Voucher(AdvancedTools)]]==

###### PENDING