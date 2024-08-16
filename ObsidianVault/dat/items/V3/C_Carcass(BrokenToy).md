---
LastUpdate: 2023-09-24
RECIPES: false
PROPERTIES: false
STRINGS: false
DISTRIBUTION: false
TRADE: false
Deployment: Collect
CollectIcon: DogStuffyRipped(Sheet07_o/01)
Category: BasicItems_Provisions
Stack: 3
Icon: DogStuffyRipped(Sheet07_a/01)
tags:
  - Container_Scrap
  - LocationDescription_Food
  - Scavengable
  - LootGenerator_Survival
Value: B3
Sound: UI_Lootable_Materials
Description: The carcass of a small animal such as a racoon, porcupine, rabbit, skunk, or rat. Hopefully not a rat.
Foraging: 20/special
Stock: 2
Supply: B - 75%
Demand: 0.5
Vendors:
  - Food
---

###### RECIPES
- C(1)@[[D_MudOven(Trap)]]: 0.5+Rand8
	- [[B_Garbage(StaleFood)]]
	- [[A_Twine(Mixer)]]
	- [[B_Kindling(004_item)]]
- C(1)@[[D_MudOven(Trap)]]: 0.5+Rand4
	- [[A_Berries(Vegetables)]]
	- [[A_Twine(Mixer)]]
	- [[B_Kindling(004_item)]]
- C(1)@[[D_MudOven(Trap)]]: 0.5+Rand2
	- [[B_Meat(RawFood)]]
	- [[A_Twine(Mixer)]]
	- [[B_Kindling(004_item]]
- C(1)@[[D_MudOven(Trap)]]: 0.5+Rand1
	- [[C_CannedFood(CannedFood)]]
	- [[A_Twine(Mixer)]]
	- [[B_Kindling(004_item)]]

###### PENDING