## Checkout Class ##

---

### Attributes ###
typeOfPayment  (string)
serviceQuality (string)
splitCheck     (integer)
itemsOrdered   (hash)
coupon         (boolean)

---

### Methods ###
calculateGratuity (decides the tip a server receives. *Uses* serviceQuality, itemsOrdered)
calculateSubtotal (the total cost of food ordered. *Uses* itemsOrdered)
calculateTotal    (the total cost for each paying party. *Uses* itemsOrdered, splitCheck, coupon)
leaveTip          (how the tip is given. *Uses* splitCheck, typeOfPayment)
appeaseGuests     (when a customer is upset. *Modifies* itemsOrdered)
paymentDeclined   (not enough cash or a card is declined. *Modifies* typeOfPayment)

---
