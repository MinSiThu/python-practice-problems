# Calculate Discount Percentage for a customer Problem

Problem Question:

You are creating a program to determine the discount percentage a customer is eligible for based on their total purchase amount. The discount rates are as follows:

- If the purchase amount is greater than or equal to $100, apply a 10% discount.

- If the purchase amount is greater than or equal to $50 but less than $100, apply a 5% discount.

- If the purchase amount is less than $50, there is no discount.

Write a Python program that takes the total purchase amount as input and calculates the applicable discount. Display the original amount, the discount amount, and the final amount after applying the discount.

Example:

```yaml
Enter the total purchase amount: 120
Original Amount: $120.00
Discount: $12.00 (10%)
Final Amount after Discount: $108.00

Enter the total purchase amount: 65
Original Amount: $65.00
Discount: $3.25 (5%)
Final Amount after Discount: $61.75

Enter the total purchase amount: 40
Original Amount: $40.00
No discount applied. Final Amount: $40.00
```
Make use of if and else statements to implement the discount logic based on the given conditions.