
Looking at the `orders` table, there’s a field called `ship_country`. Write a
query that shows the `order_id`, `customer_id`, and `ship_country` for the orders
where the `ship_country` is either "France" or "Belgium".
Here's a hint. See the 
[PostgreSQL `IN` subquery expression](https://www.postgresqltutorial.com/postgresql-in/).


Your results should look like this

```
order_id | customer_id | ship_country
----------+-------------+--------------
    10248 | VINET       | France
    10251 | VICTE       | France
    10252 | SUPRD       | Belgium
    10265 | BLONP       | France
    10274 | VINET       | France
(...)
    11038 | SUPRD       | Belgium
    11043 | SPECD       | France
    11051 | LAMAI       | France
    11076 | BONAP       | France
(96 rows)
```