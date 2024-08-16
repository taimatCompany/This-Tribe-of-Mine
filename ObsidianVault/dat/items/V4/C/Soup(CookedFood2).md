---
LastUpdate: 2023-10-17
RECIPES: false
PROPERTIES: false
STRINGS: false
Deployment: Consume
CollectIcon: BowlSoupSteam(Sheet01/20)
Category: Consumables_Cooking
Icon: BowlSoupSteam(Sheet01_a/20)
Sound: UI_Lootable_ConsumableFluid
Influences:
  - Hungry
  - Depression
  - Sick
Description: A hearty and filling soup. Takes effort to make, but lasts several days.
Speeches:
  - FoodUsage
---


###### RECIPES

***Thin Soup***
- 2@[[G_Kitchen(Cooker2)]]: 1+3hr
	- [[B_Meat(RawFood)]]
	- [[C_Roots(008_item)]]
	- [[A_Greens(Plants)]]
	- [[C_Salt(Joint)]]
	- 3[[B_CleanWater(005_item)]]
	- 3[[A_FireBundle(QualityJoint)]]

***Tomato Soup***
- 4@[[G_Kitchen(Cooker2)]]: 0.5+1hr
	- D3[[C_Roots(008_item)]]
	- [[C_Salt(Joint)]]
	- [[D_VegetableOil(015_item)]]
	- [[A_Greens(Plants)]]
	- 6[[B_CleanWater(005_item)]]
	- [[A_FireBundle(QualityJoint)]]

***Chicken Soup***
- 10@[[G_Kitchen(Cooker2)]]: 1hr+5hr 
	- [[C_RoastBeast(HeaterPart)]]
	- 3[[C_Roots(008_item)]]
	- 2[[A_Greens(Plants)]]
	- D10[[B_CleanWater(005_item)]]
	- 2[[C_Salt(Joint)]]
	- 5[[A_FireBundle(QualityJoint)]]