---
LastUpdate: 2023-10-02
RECIPES: true
PROPERTIES: false
STRINGS: false
DISTRIBUTION: false
TRADE: false
Deployment: Inventory
Category: Equipment_Fuel
Stack: 10
Icon: KindlingBars(Sheet05_a_34)
tags:
  - LootGenerator_Trader
  - Timeline_WoodAndFuel
  - Scavengable
  - Container_Furniture
Sound: UI_Lootable_Fuel
Value: B3
Description: Cut, split, and dried wood.
Foraging: 20/anywhere
Stock: 8
Supply: 75%
Demand: 0.75
Vendors:
  - Residents
---

###### RECIPES

***WoodShop***
1. B(36---)@[[G_WoodShop(BasicWorkshop2)]]: 0.1+0HR
	- ==D6[[C_Lumber(Wood)]]==
4. D(6-)@[[G_WoodShop(BasicWorkshop2)]]: 0.1+0HR
	- ==[[C_Lumber(Wood)]]==

***SawHorse***
1. B(36---)@[[G_SawHorse(BasicWorkshop)]]: 0.1+0HR
	- D6[[C_Lumber(Wood)]]
	- ==[[D_SawBlade(SawBlade)]]==
2. C(4-)@[[G_SawHorse(BasicWorkshop)]]: 0.25+0HR
	- [[C_Lumber(Wood)]]
	- ==[[C_Hatchet(Hatchet)]]==
3. D(6-)@[[G_SawHorse(BasicWorkshop)]]: 0.1+0HR
	- [[C_Lumber(Wood)]]
	- ==[[D_SawBlade(SawBlade)]]==
4. D(24--)@[[G_SawHorse(BasicWorkshop)]]: 0.25+0HR
	- D6[[C_Lumber(Wood)]]
	- ==[[C_Hatchet(Hatchet)]]==

***MudOven***
1. D(6-)@[[[[D_MudOven(Trap)]]: 0.5+0HR
	- D3==[[C_Lumber(Wood)]]==

###### PENDING