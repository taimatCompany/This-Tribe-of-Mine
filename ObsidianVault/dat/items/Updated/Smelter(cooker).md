---
LastUpdate: 2024-08-16
RECIPES: false
PROPERTIES: false
STRINGS: false
Deployment: Shelter
Category: ShelterItems_Furniture
Icon: PotWithSmoke(Sheet04_a/02)
Sound: UI_Lootable_Fuel
Description: An insulated furnace for smelting. Can be fueled with coal to reach very high temperatures.
---

- Fuel Resource: NONE
- Animation: scavenging2

- [x] Swap Cooker and Heater item names
- [x] Add Heater upgrade recipe using Cooker

###### RECIPES
- ?(1)@[[G_SawHorse(BasicWorkshop)]]: 0.1+0HR
	- 1[[A_Hardware(WeaponParts)]]
	- ==Testing==

- ?(1)@[[G_MetalShop(MetalWorkshop)]]: 3+0hr
	1. ==[[F_Book(Book)]]== (foraging)
	2. [[F_Toolkit(PocketTools)]] (metalshop)
	3. 2[[C_Barrel(RifleAmmo)]] (foraging)
	4. [[C_Hatchet(Hatchet)]] (mudoven)
	5. C20[[A_Hardware(WeaponParts)]]
	6. C10[[A_Dirt(000_item)]]