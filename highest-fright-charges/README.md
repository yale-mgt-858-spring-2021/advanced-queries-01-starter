
_💩 just got real. You're going to need a
[subquery](https://www.postgresql.org/docs/8.1/functions-subquery.html)
here (see [also](https://www.postgresqltutorial.com/postgresql-subquery/
and the [PostgreSQL date functions and
operators](https://www.postgresql.org/docs/9.1/functions-datetime.html))_.
Some of the countries we ship to have very high freight charges. This is
indicated in the `freight` column of the `orders` table. Each order has
its own value for `freight`. Imagine we want to save money on freight 💰💰
and so we first want to know where we're spending the most money on 
freight.
Find the ten
countries to which we ship that had the highest average freight charges
in the most recent 12 months of data available.

Your results should look as follows

```
ship_country |  average_freight
--------------+--------------------
Ireland      |  200.2099952697754
Austria      | 186.45960102081298
USA          | 117.97046036692872
Germany      |  105.8452499628067
Sweden       | 100.11692355229304
Canada       |   85.6783338089784
Denmark      |  85.62846147097073
Switzerland  |  74.37999927080594
Belgium      |  70.87214185829673
France       |  58.05446791181222
(10 rows)
```