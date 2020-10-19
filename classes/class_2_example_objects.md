## Johnson Party Checkout ##

 ---

### Attributes ###
```
typeOfPayment  ("Cash")
serviceQuality ("Excellent")
splitCheck     (1)
itemsOrdered   ({"Chicken and Rice" : 2 , "Steak and Potatoes" : 1 , "Chicken Tenders" : 1 , "Mac and Cheese" : 1 , "Birthday Cake" : 1})
coupon         (true)
```

---

### Methods ###
```
calculateGratuity (6 items ordered and Excellent service quality means the Johnson's will give a $20 dollar tip )
calculateSubtotal ($100)
calculateTotal    (The party split the check one way and have a coupon, so the total will be $80 paid in cash.)
leaveTip          (The Johnson party will leave the tip in cash on the table)
appeaseGuests     (The Johnson party was upset with one of the dishes having an allergen in it, the dish will be taken out of the itemsOrdered.)
paymentDeclined   (The Johnson party did not have enough cash, their typeOfPayment will change to "Credit Card")
```
