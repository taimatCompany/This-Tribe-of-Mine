---
LastUpdate: 2023-10-17
RECIPES: false
PROPERTIES: false
STRINGS: false
DISTRIBUTION: false
TRADE: false
Deployment: Consume
CollectIcon: MugHot(Sheet05_o/40)
Category: Tools_ToolsAndMedicine
Stack: 1
Icon: MugHot(Sheet05_a/40)
tags:
  - AngerManagement_Meds
Sound: UI_Lootable_ConsumableFluid
Value: C9
Influences:
  - Sick
  - Depression
Description: A strong tea made from ginger, cinnamon, honey, garlic, and pine needles.
Speeches:
  - MedicineUsage?
Foraging: 0/nowhere
Stock: 2
Supply: C - 50%
Demand: 2
Vendors:
  - Food
  - Medic
---

###### RECIPES
- C(3)@[[G_Kitchen(Cooker2)]]: 1+0.25HR
	- ==[[C_Roots(008_item)]]==
	- C3[[B_CleanWater(005_item)]]
	- [[B_Sugar(Sugar)]]
	- [[A_FireBundle(QualityJoint)]]
	- ==[[A_Greens(Plants)]]==