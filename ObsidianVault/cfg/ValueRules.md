Values: A1 B3 C9 D27 E81 F243 G729 H2187 I6561 J19683 K59049

1. All Items start at "A1"
2. Value class is one higher than the most expensive ingredient 
3. 3-stack ingredients increases value by 1, 9/2, 27/3, etc.
4. Product output of 4 decrease its value class by 1, 9/2, 27/3, etc.

1
3+
9++
27+++
81++++
243++ ++ +

*Traders sell items at demand price, but not lower than 1.*
*Traders buy items at their demand price.*

### Supply(By Craft Value)
- A: 99%
- B: 75%
- C: 50%
- D: 25% 
- E: 10%
- F: 7.5%
- G: 5%
- H: 2.5%
- I: 1%
- J: 0.75%
- K: 0.50%

### Demand (CategoryValue x Rarity)
***Values below 0.01 are rounded to 0***

###### CATEGORY VALUE
- Junk/Cooking= 0.01
- Supplies= 0.5
- Provisions= 1
- Fuel= 1.5
- Tools/Medicines= 2
- Guns= 2.5
- Documents= 3
- Machining= 3.5

###### RARITY ((supply - 1) x -2)
- 99% = 0.02
- 75% = 0.5
- 50% = 1
- 25% = 1.5
- 10% = 1.8
- 7.5% = 1.88
- 5% = 1.90
- 2.5% = 1.96
- 0% = 2

### Stock (Stack x Demand) Rounded Up
*This is how much of any one particular item a trader typically has on hand*

### Vendors
*Suppliers who are trusted enough to purchase this product from*
*The player is considered a resident mechanic, and eventually a smuggler*
*Offered Items have a minimum valueMultiplier of 1*

`Army`: Functioning and clean weapons, ammunition and medicalAid.
	- ArmybaseTrader, DefenderTrader
`Food`: Fresh, safe, unspoiled food.
	- 016_FoodTrader, 025_FoodTrader, PriestTrader
`Medic`: Effective and safe medicalAid and drugs.
	- 016_MedsTrader, 017_HospitalTrader, 022_PharmacyTrader, PriestTrader
`Merchant`: Items that can be easily transported in a backpack and don't spoil quickly.
	- BasicTrader, GenericTrader, Petrolstation_son
`Resident`: Items that require a brick and mortar location.
	- **Not** ArmybaseTrader, BasicTrader, or GenericTrader
`Smuggler`: Sensitive, dangerous, or expensive items that don't spoil quickly.
	- KidnapersTrader, DefenderTrader
`Mechanic`: Deals in parts, hardware, tools, and metal.
	- 016_ElectroTechTrader, 016_ScrapTrader, Petrolstation_son


# Removed

### Suppliers
*Suppliers are creators of products and sell them at their craft value*
- All merchants are suppliers, but sell items at their highest value.
- The army and smugglers are considered merchants.

`SupplierOfferedItems= Wholesale Price(ValueMultiplier = 1)`
`MerchantOfferedItems= Market Price(ValueMultiplier = Demand)`

- **Suppliers:** Cooks, Mechanics, Doctors, Smugglers, Army

### Consumers
*Consumers are those that use the product, and buy them at their demand value.*
- All merchants are consumers, but buy everything at their lowest value.
- The army and smugglers are considered merchants.

`ConsumerAcceptedItems= Market Price`
`MerchantAcceptedItems= WHolesale Price`

> A supplier cannot also be a consumer.

- **Consumers:** Mechanics, Doctors, Cooks, Army, NonMechanicResidents, NonCookResidents, AllResidents, Smugglers

