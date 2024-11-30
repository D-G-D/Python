## Homework day 3

Related technical note(s): 
- PY-05

Questions:

1. The **body mass index** (BMI) is defined as the body mass (kg) divided by the square of the body height (m2). It is used to broadly categorize a major adult person as underweight (under 18.5 kg/m2), normal weight (18.5 to 24.9), overweight (25 to 29.9), or obese (30 or more). Write a function that takes the heigh and weight of a person, in the adequate units, and returns the categorization underweight/normal weight/overweight/obese.

2. In databases, names are usually split in two or more columns. In US, we usually find three columns, such as `firstname`, `midname` and `lastname`. When the name has to be printed, the three pieces are pasted together. Write a function for this job. If the arguments supplied are `firstname='Donald'`, `midname='John'` and `lastname='Trump'`, the function would return `'Donald John Trump'`. But it should work also for the cases in which the middle name is omitted, which is not rare, in particular for foreign people.

3. Write a function that, given a list of integers, returns the number of positive terms and the number of negative terms. Modify the definition so the your function returns a dictionary with keys '`positive` and `negative`. So, given the list `[2, 3, -7, 0]`, your function must return `{'positive': 2, 'negative': 1}`.

4. Suppose that you are given an **interest rate** *r* for your capital, so that at the end of every year your capital gets the corresponding increase. For instance if the capital is $1 and the interest rate is 10% (`r=0.1`), after one year you have $1.10, after two years $1.21, etc. Write a function that, by using a loop, takes *r* and returns the number of years needed to double it. The solution does not depend on the actual value of the capital, so you can set it at $1. *Note*: this can also be solved mathematically, by means of logarithms).

5. The **Fibonacci numbers** are 1, 1, 2, 3, 5, 8, 13, 21, etc. Except for the first two terms of this sequence, both equal to 1, every term is the sum of the two preceding terms. Use a loop to calculate the first 10 Fibonacci numbers. Based on that loop, write a function which, given a number, returns a list of Fibonacci numbers of that length.

6. A **prime** is a positive integer greater than 1 that is not a product of two smaller positive integers. Starting with the list `primes = [2]`, use a loop for building the list of primes lower than 100. The number 100 of course can be replaced ny any other number, so you would probably be able to write a function that takes an integer `n` and returns the numer of primes lower than `n`.

7. Going back to exercise 4 of lecture PY-03, create a list containing the leap years of the 20th century.

8. Write a function that drops the duplicate items from a list, keeping the order. For instance, given the list `['a', 'f', 'a', 'b']`, that function would return `['a', 'f', 'b']`.

9. A **nested list** is a list of lists, that is, a list whose items are lists. For instance, `[[1, 2], [], ['a']]`. Write a function that *flattens* a nested list, transforming it into a new list whose items are the items contained in the items of the original list. Given the above example, that function would return `[1, 2, 'a']`.

10. Write a function that combines strings from two lists of the same length, pasting every string from the second list after every string from the first list. For instance, given the lists `['A', 'B']` and `['X', 'Y']`, that function would return the list `['AX', 'AY', 'BX', 'BY']`.
