# wurst-bonus-handler

Easy unit stat management. 
Allows you to add and remove the following bonuses:

* Hitpoints
* Manapoints
* Damage
* Armor
* Sightrange
* HP regenration
* MP regeneration
* Attackspeed
* Strength
* Agility
* Intelligence

## API

```
/** Gets the current bonus value */
public function unit.getBonus(Bonus bonusType) returns int

/** Adds to current bonus bonus value */
public function unit.addBonus(Bonus bonusType, int bonusValue)

/** Sets the bonus of specified type for the unit to the given amount. */
public function unit.setBonus(Bonus bonusType, int amount)
```
