---
LastUpdate: 2024-08-16
RECIPES: false
PROPERTIES: false
STRINGS: false
Deployment: Upgrade
Category: Improvement_Upgrade
Icon: x
Sound: x
Description: A hot water heater that could keep this place really warm.
---

Fuel: `[[A_Charcoal(HeaterFuel)]]`

###### RECIPES
- ?(1)@[[Boiler(Heater2)]]: 0.1+0HR
	- UPGRADE [[Boiler(Heater2)]]
	- 1[[A_Hardware(WeaponParts)]]
	- ==Testing==

- ?(1)@[[WoodStove(Heater)]]: 3+0HR
	- Upgrade [[WoodStove(Heater)]]
	- F20[[D_Rubber(FoodScraps)]]
	- E10[[C_ScrapMetal(Parts)]]
	- D20[[B_CleanWater(005_item)]]
	- C20[[A_Hardware(WeaponParts)]]
	- 2[[C_Barrel(RifleAmmo)]]