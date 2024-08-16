---
LastUpdate: 2024-08-16
RECIPES: false
PROPERTIES: false
STRINGS: false
DISTRIBUTION: false
TRADE: false
Deployment: Collect
CollectIcon: WaterGlass(Sheet01/58)
Category: BasicItems_Provisions
Stack: 20
Icon: WaterGlass(Sheet01_a/58)
tags:
  - LootGenerator_Trader
  - Container_Kitchen
Sound: UI_Lootable_ConsumableFluid
Value: B3
Influences: 
Description: Distilled or filtered and boiled. Clean drinking water. An impotent potable.
Speeches: 
Foraging: 0/nowhere
Stock: 10
Supply: B - 75%
Demand: 0.5
Vendors:
  - Food
  - Medic
  - Merchant
  - Army
---

###### RECIPES
1. ***Distillation***
	- B(20--)@[[G_Distiller(HoochGear)]]: 0.1+2HR
		- ==C20[[A_Swill(Water)]]==
		- 2[[A_FireBundle(QualityJoint)]]
3. ***MudOven Light Filter and Boil***
	- D(1)@[[D_MudOven(Trap)]]: 0.1+0.1HR
		- [[C_Filter(Filter)]] 
		- ==B3[[A_Swill(Water)]]==
		- [[A_FireBundle(QualityJoint)]]
4. ***Kitchen Full Filter and Boil***
	- C(25--)@[[G_Kitchen(Cooker2)]]: 0.1+0.5HR
		- ==D30[[A_Swill(Water)]]==
		- [[C_Filter(Filter)]] 
		- [[A_FireBundle(QualityJoint)]]
5. ***Kitchen Light Filter and Boil***
	- D(2)@[[G_Kitchen(Cooker2)]]: 0.1+0.1HR
		- [[C_Filter(Filter)]] 
		- ==B3[[A_Swill(Water)]]==
		- [[A_FireBundle(QualityJoint)]]
6. ***Voucher Order***
	- D(48---)@[[G_Office(HerbalWorkshop)]]: 0.25+Random2
		- ==[[G_Voucher(AdvancedTools)]]==
