
Our sales people are always scrambling to get their sales in by the end
of the month. At least, it feels like that.  But, is it true 🤔? Please
calculate the fraction of revenue that comes from orders placed in the
last week of each month (the last seven days of each month), being
careful to take off customer discounts.

Maybe checkout the PostgreSQL [`filter`](https://medium.com/little-programming-joys/the-filter-clause-in-postgres-9-4-3dd327d3c852)
clause and [`date_trunc`](https://www.postgresql.org/docs/current/functions-datetime.html#FUNCTIONS-DATETIME-TRUNC).

Your results should look as follows
```
       sales       |  last_week_sales   | fraction_last_week
-------------------+--------------------+---------------------
 1265793.038653364 | 311720.16393335356 | 0.24626471659615265
(1 row)
```