# [Lab - Flawed enforcement of business rules](https://portswigger.net/web-security/logic-flaws/examples/lab-logic-flaws-flawed-enforcement-of-business-rules)

This lab has a logic flaw in its purchasing workflow. To solve the lab, exploit this flaw to buy a "Lightweight l33t leather jacket".

You can log in to your own account using the following credentials: `wiener:peter`

---
## Solution

- Signup for the newsletter u will get a new discount cupon
- ![](04-lab1.png)
	- SIGNUP30

- Try applying the codes more than once. Notice that if you enter the same code twice in a row, it is rejected because the coupon has already been applied. However, if you alternate between the two codes, you can bypass this control.
- Reuse the two codes enough times to reduce your order total to less than your remaining store credit. Complete the order to solve the lab.
- ![](04-lab2.png)