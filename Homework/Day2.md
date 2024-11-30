## Homework day 2

Related technical note(s): 
- PY-03
- PY-04

Questions:

1. Write a Python function which, given three integers, returns `True` if any of them is zero, and `False` otherwise.

2. Write a Python function which, given three integers, returns `True` if they are in order from smallest to largest, and `False` otherwise. Modify your function so that it returns `1`/`0` instead of `True`/`False`.

3. Given two positive integers `a` and `b`, you can get the **remainder** of the integer division of `a` by `b` with `a%b`. So `7%3` returns `1`, and `9%5` returns `4`. Write a function which, given an integer, returns `True` if that integer is a multiple of 7, and `False` otherwise.

4. A year is a **leap year** if it is divisible by 4, unless it is a century year that is not divisible by 400. So, 1800 and 1900 are not leap years while 1600 and 2000 are. Write a function that tells you whether a year is a leap year.

5. Write a function which anonymizes credit card numbers, turning, for instance, `'2875765488882745'` into `'Credit card ****745'`. That is, have 4 stars followed by the last three digits of the original card number.

6. Write a list containing the month names and use it to create a function for **date conversion** that takes `'1954-04-30'` and returns `'April 30, 1954'`.

7. To write a function that returns more than one result, we specify them in the `return` statement, separated by commas. For instance, if our function must return `result1` and `result2`, we write `return result1, result2` (don't forget the comma). Then, the results will be returned together as a tuple. Write a function that takes a date in the format 'yyyy-mm-dd' and returns the year, the month and the day as three integers. 

8. Modify the definition of the previous question, so that your function takes the string `'1954-04-30'` and returns the dictionary `{'year': 1954, 'month': 4, 'day': 30}`.

9. Write a Python function for a **change dispenser**. The coins are named as follows: a quarter is 25 cents, a dime is 10 cents, a nickel is 5 cents and a penny is 1 cent. The function must take a number of cents and return a dictionary with the number of coins of every type needed. For instance, for the argument `quantity=67` it would return `{'quarters': 2, 'dimes': 1, 'nickels': 1, 'pennies': 2}`. Hint: you can get the **quotient** of the integer division operator of `a` by `b` with `a//b` (examples: `7//3` returns `2`, `23//4` returns 5).
