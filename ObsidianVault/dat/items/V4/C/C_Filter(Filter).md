---
LastUpdate: 2023-10-17
RECIPES: false
PROPERTIES: false
STRINGS: false
DISTRIBUTION: false
TRADE: false
Deployment: Inventory
Category: Materials_Supplies
Stack: 20
Icon: x
tags:
  - Scavengable
  - LootGenerator_Trader
  - Container_Food
  - Timeline_Materials
  - LocationDescription_Parts
Sound: UI_Lootable_Materials
Value: C9
Description: An old coffee or handsewn charcoal filter for purifying water or alcohol
Foraging: 20/uncommon
Stock: 5
Supply: C - 50%
Demand: 0.25
Vendors:
  - Food
  - Mechanic
  - Merchant
---

###### RECIPES

***Expensive***
- C(2)@[[G_SawHorse(BasicWorkshop)]]: 0.5+0HR
	- [[B_Fabric(Materials)]]
	- [[A_Charcoal(HeaterFuel)]]
	- 2[[A_Twine(Mixer)]]

***Cheaper***
- B(10--)@[[G_SawHorse(BasicWorkshop)]]: 0.5+0HR
	- C5[[B_Fabric(Materials)]]
	- C10[[A_Twine(Mixer)]]
	- ==[[A_Charcoal(HeaterFuel)]]==