# Recipe Class #
---

## Attributes ##
ingredients     (Array)

cookTimeHr      (Float)

utensilsUsed    (Hash)

burnersUsed     (Integer)

ovenUsed        (Boolean)


---

## Methods ##
miseEnPlace       (Gather necessary items. *Uses* ingredients, utensilsUsed)

coordinateDishes  (Ensure various dishes aren't conflicting with each other. *Uses* burnersUsed, ovenUsed. *Modifies* cookTimeHr)

prepIngredients   (Prepare ingredients to be cooked. *Uses* ingredients. *Modifies* utensilsUsed)

cookMeal          (Cook meal as necessary. *Uses* burnersUsed, ovenUsed, cookTimeHr.)

dirtyDishes       (Nothing is clean. *Modifies* cookTimeHr, utensilsUsed)

---
