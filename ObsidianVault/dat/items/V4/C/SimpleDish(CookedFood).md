---
LastUpdate: 2023-10-17
RECIPES: false
PROPERTIES: false
STRINGS: false
Deployment: Consume
CollectIcon: PlateWithUtensils(Sheet02_o/04)
Category: Consumables_Cooking
Icon: PlateWithUtensils(Sheet02_a/04)
Sound: UI_Lootable_ConsumableFluid
Influences:
  - Hungry
  - Depression
Description: A simple homemade dish. Oatmeal, pancakes, sandwiches, baked potatoes, etc.
Speeches:
  - FoodUsage
---

###### RECIPES

1. ***Cookies***
	- C(4-)@[[D_MudOven(Trap)]]: 1+1hr
		- ==[[B_Flour(ContainerSmall)]]==
		- [[A_Tallow(009_item)]]
		- [[B_Sugar(Sugar)]]
		- [[B_BakingSoda(Fluorescent)]]
		- C4[[B_CleanWater(005_item)]]
		- [[A_FireBundle(QualityJoint)]]
- ***Oatmeal***
	- 4@[[G_Kitchen(Cooker2)]]: 0.5+0hr
		- C4[[B_CleanWater(005_item)]]
		- [[A_FireBundle(QualityJoint)]]
		- ==[[A_Oats(ContainerBig)]]==
		- [[B_Sugar(Sugar)]]
3. ***Sandwich***
	- (1)@[[G_Kitchen(Cooker2)]]: 0.25+0hr
		- ==2[[C_SlicedBread(HeatLamp)]]==
		- [[A_VegetableSlices(001_item)]]
		- [[A_Tallow(009_item)]]
		- [[B_ColdCuts(ShotgunAmmo)]]
		- [[B_CleanWater(005_item)]]
4. ***Baked Potato***
	- (1)@[[D_MudOven(Trap)]]: 0.1+1hr
		- [[C_Roots(008_item)]]
		- ==[[A_Tallow(009_item)]]==
		- 2[[A_FireBundle(QualityJoint)]]
		- [[B_CleanWater(005_item)]]
5. ***Hashbrowns***
	- D(2)@[[G_Kitchen(Cooker2)]]: 0.25+0hr
		- C9[[A_VegetableSlices(001_item)]]
		- ==[[D_VegetableOil(015_item)]]==
		- [[A_FireBundle(QualityJoint)]]
		- 2[[B_CleanWater(005_item)]]
6. ***Pancakes***
	- (4)@[[G_Kitchen(Cooker2)]]: 1+0hr
		- ==2[[B_Flour(ContainerSmall)]]==
		- [[C_Salt(Joint)]]
		- [[B_Sugar(Sugar)]]
		- [[D_VegetableOil(015_item)]]
		- [[A_FireBundle(QualityJoint)]]
		- 4[[B_CleanWater(005_item)]]
7. ***Bacon***
	- (2)@[[G_Kitchen(Cooker2)]]: 0.25+0hr
		- ==[[B_Meat(RawFood)]]==
		- [[A_FireBundle(QualityJoint)]]
		- 2[[B_CleanWater(005_item)]]
8. ***Baked Chicken Leg***
	- (1)@[[D_MudOven(Trap)]]: 0.1+0.5hr
		- ==[[B_Meat(RawFood)]]==
		- [[A_FireBundle(QualityJoint)]]
		- [[B_CleanWater(005_item)]]
9. ***Big Salad***
	- C(4)@[[G_Kitchen(Cooker2)]]: 0.25+0hr
		- ==B10[[A_Greens(Plants)]]==
		- [[D_Vinegar(002_item)]]
		- [[D_VegetableOil(015_item)]]
