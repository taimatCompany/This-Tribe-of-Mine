---
LastUpdate: 2023-09-26
RECIPES: false
PROPERTIES: false
STRINGS: false
DISTRIBUTION: false
TRADE: false
Deployment: Inventory
Category: Tools_ToolsAndMedicine
Stack: 20
Icon: BottleLabeled%(Sheet04_a/05)
tags:
  - Scavengable
  - Container_Bathroom
  - LootGenerator_Med
  - LocationDescription_Medicine
  - AngerManagement_Meds
Sound: UI_Lootable_ConsumableFluid
Value: F243
Influences:
  - Sick
  - Wounded
Description: Liquid or pilled medicine for curing various infections. Extremely potent, extremely valuable.
Speeches:
  - MedsUsage
Foraging: 3/anywhere
Stock: 76
Supply: F - 7.5%
Demand: 3.76
Vendors:
  - Medic
---

###### RECIPES
- F(9--)@[[ResearchBench(HomeLab)]]: 0.5+0HR
	- G9[[E_Vodka(Alcohol)]]
	- F9[[D_Vinegar(002_item)]]
	- 3[[C_Brimstone(010_item)]]
	- [[A_Charcoal(HeaterFuel)]]
- F(9--)@[[G_Office(HerbalWorkshop)]]: 0.5+RANDOM3
	- [[G_Voucher(AdvancedTools)]]

###### PENDING
