# [Lab - Inconsistent security controls](https://portswigger.net/web-security/logic-flaws/examples/lab-logic-flaws-inconsistent-security-controls)

This lab's flawed logic allows arbitrary users to access administrative functionality that should only be available to company employees. To solve the lab, access the admin panel and delete the user `carlos`.

---
## Solution
- Register an account
- ![03-lab-1.png](./images/03-lab-1.png)
- you will get a option to update your email address
- update email with `DontWannaCry@dontwannacry.com`
- ![03-lab-1.png](./images/03-lab-2.png)
- now visit admin panel, u will get a option to delete carlos
