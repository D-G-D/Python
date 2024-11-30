## Homework day 4

Related technical note(s): 
- PY-07
  
Questions:

1. For `x = np.array([True, False])` and `y = np.array([True, True])`, calculate `~x`, `x & y` and `x | y`. What is the meaning of these operations?

2. Plot together the curves $y = x^3 + x^2 - 3^x +1$ and $y = -x^3 + 0.5\,x^2 + x + 1$ in the interval $-2 \le x \le 2$.

3. Real data frequently comes with **missing values**. The designers of NumPy allowed for this creating `np.nan`, which has data type `float`. This value has to be handled with care. To get an idea of it works, calculate `np.nan + 3`, `np.nan < 3`, `np.nan == np.nan` and `np.nan <= np.nan`. Can you explain the results obtained?

4. In the stock market, the **daily return** is the percentage change in the price of a specific company's shares with respect to the preceding trading day. If $p(t)$ is the price on day $t$, the corresponding return would be
$$r(t) =\frac{p(t) - p(t-1)}{p(t-1)}=\frac{p(t)}{p(t-1)}-1,$$
which can be multiplied by 100 to get percentage scale. The list `msft_price`, given below, contains the opening prices of Microsoft stock in the NASDAQ market, from September 5th to October 3rd of 2023 (only trading days), in US dollars. Calculate a 1D array containing the daily returns. Note that there will be no return for September 5th, because you are not given the price for the preceding day.

```
msft_price = [329.00, 333.38, 331.29, 330.09, 337.24, 335.82, 331.31, 339.15, 336.92, 327.80,
    326.17, 329.51, 319.26, 321.32, 316.59, 315.13, 312.30, 310.99, 317.75, 316.28, 320.83])
```

5. In the first exercise of the homework of day 3, you wrote a function which takes the height and the weight (single numbers, not vectors) and returns a **categorization** of the BMI. Can you modify that function so it takes a vector of heights and a vector of weights and returns a vector of categorized BMI's? Note that what you need is a **vectorized function**.
