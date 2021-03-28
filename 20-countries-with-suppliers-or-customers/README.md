
The CEO is going on a trip ✈️⛴.! Please list all the countries with either a
supplier or a customer. List them in descending order of the total number of
visits possible (sum of number of customer and number of suppliers).

Maybe try using the PostgreSQL [`COALESCE`](https://www.postgresql.org/docs/current/functions-conditional.html#FUNCTIONS-COALESCE-NVL-IFNULL)
function.

Your results should look as follows
```
  country   | num_suppliers | num_customers | num_visits
------------+---------------+---------------+------------
USA         |             4 |            13 |         17
Germany     |             3 |            11 |         14
France      |             3 |            11 |         14
Brazil      |             1 |             9 |         10
UK          |             2 |             7 |          9
Spain       |             1 |             5 |          6
Italy       |             2 |             3 |          5
Mexico      |             0 |             5 |          5
Canada      |             2 |             3 |          5
Venezuela   |             0 |             4 |          4
Sweden      |             2 |             2 |          4
Denmark     |             1 |             2 |          3
Finland     |             1 |             2 |          3
Argentina   |             0 |             3 |          3
Australia   |             2 |             0 |          2
Austria     |             0 |             2 |          2
Switzerland |             0 |             2 |          2
Norway      |             1 |             1 |          2
Japan       |             2 |             0 |          2
Portugal    |             0 |             2 |          2
Belgium     |             0 |             2 |          2
Poland      |             0 |             1 |          1
Netherlands |             1 |             0 |          1
Singapore   |             1 |             0 |          1
Ireland     |             0 |             1 |          1
(25 rows)
```