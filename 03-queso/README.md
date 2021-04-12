
In the `products` table, we'd like to see the `product_id` and `product_name` for
those products where the `product_name` includes the string "queso" (regardless of
whether it is uppercase or lowercase).
Here's a hint. Take a look at
[PostgreSQL pattern matching](https://www.postgresql.org/docs/current/functions-matching.html).

Your results should look like this

```
product_id |       product_name
------------+---------------------------
        11 | Queso Cabrales
        12 | Queso Manchego La Pastora
(2 rows)
```