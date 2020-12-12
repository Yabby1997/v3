# General

- [The Python Numbers Tutorial](https://docs.python.org/3/tutorial/introduction.html#numbers) and [Python numeric types](https://docs.python.org/3.9/library/stdtypes.html#numeric-types-int-float-complex) can be a great introduction.

## 1. Estimate value after exchange

- You can use the [division operator](https://docs.python.org/3/tutorial/introduction.html#numbers) to get the value of exchanged currency.

## 2. Calculate currency left after an exchange

- You can use the [substraction operator](https://docs.python.org/3/tutorial/introduction.html#numbers) to get the amount of changes.

## 3. Calculate value of bills

- You can use the [multiplication operator](https://docs.python.org/3/tutorial/introduction.html#numbers) to get the value of bills.

## 4. Calculate number of bills

- You need to divide `budget` into `denomination`.
- You need to use type casting _int_ to get exact number of bill.
- To remove decimal places from a `float`, you can convert it to `int`.

  **Note:** The `//` operator also does floor division. But, if the operand has `float`, the result is still `float`.

## 5. Calculate value after exchange

- You need to calculate `spread` percent of `exchange_rate` using multiplication operator and add it to `exchange_rate` to get the exchanged currency.
- Actual rate need to be computed! add exchange rate and exchange fee.
- You can get exchanged money affected by commission by using divide operation and type casting _int_.

## 6. Calculate unexchangeable value

- You need to calculate `spread` percent of `exchange_rate` using multiplication operator and add it to `exchange_rate` to get the exchanged currency.
- Actual rate need to be computed! add exchange rate and exchange fee.
- You can get remainder by using modular arithmetic.
