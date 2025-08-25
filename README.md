# Sum-and-Product-Check

Question Explanation:

Input: 5
 -3

Output: True

This program determines whether at least one of two conditions is true for two integers A and B:

The sum of A and B is negative.
The product of A and B is negative.
Logical Approach:

Read Input:

Read two integers from the input, representing A and B.

Calculate Sum and Product:

Calculate the sum of A and B and store it in sum_result.

Calculate the product of A and B and store it in product_result.

Check Conditions:

Check if either sum_result or product_result is negative.
If either of them is negative, the result is True. Otherwise, it's False.

Output:

Print the boolean result (True or False).

Example for Clarity:

If A = 5 and B = -3:

The sum of A and B (5 + (-3) = 2) is not negative, so the first condition is False.

The product of A and B (5 * (-3) = -15) is negative, so the second condition is True.

Since one of the conditions (product being negative) is True, the output will be:

True
