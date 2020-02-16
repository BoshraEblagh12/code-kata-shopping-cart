##Description


First I need to import ‘scanner’ to accept the user input and store the item of list entered in a string variable called ‘items’

As only item A and item B have discounts available, and so only the number of items of A and B purchased need to be counted and so corresponding variables are created. 

A for loop is used to read each character in the string ‘items’ and add the correct amount to the total price. If the user has entered an incorrect item (not A,B,C or D), a counter is incremented each time to keep a record of the invalid selections.

If the number of item A is purchased more than 3 times, a discount is applied. Normally, the customer would have been charged 150 but with the discount 30 is subtracted from the total price. If the customer have purchased more than 3, integer division is used to subtract as this number is then multiple by 30 and subtracted from the total price. The same is done for the number of item B, but instead only 23 is subtracted but for every 2 purchases.

If the customer has entered an invalid item letter, the customer is notified that they have made an invalid selection and it has not been included in the price.
