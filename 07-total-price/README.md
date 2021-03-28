
In the `order_details` table, we have the fields `unit_price` and
`quantity`.  I want you to write a query in which you create a new field
`total_price`, that multiplies these two together. We’ll ignore the
`discount` field for now.  In addition, show the `order_id`, `product_id`,
`unit_price`, and `quantity`. Order by `order_id` and `product_id`.


Your results should look like this

```
order_id | product_id | unit_price | quantity |    total_price
----------+------------+------------+----------+--------------------
    10248 |         11 |         14 |       12 |                168
    10248 |         42 |        9.8 |       10 |  98.00000190734863
    10248 |         72 |       34.8 |        5 | 173.99999618530273
    10249 |         14 |       18.6 |        9 | 167.40000343322754
(...)
    11077 |         66 |         17 |        1 |                 17
    11077 |         73 |         15 |        2 |                 30
    11077 |         75 |       7.75 |        4 |                 31
    11077 |         77 |         13 |        2 |                 26
(2155 rows)
```