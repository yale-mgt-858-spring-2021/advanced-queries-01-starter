What products do we have in our inventory that should be reordered?
"Products that need reordering" are those for which

* `units_in_stock` plus `units_on_order` is less than or equal to `reorder_level`
* the `discontinued` flag is false (0)

Your results should look like this (please pay attention to the columns)

```
product_id |     product_name      | units_in_stock | units_on_order | reorder_level | discontinued
-----------+-----------------------+----------------+----------------+---------------+--------------
        30 | Nord-Ost Matjeshering |             10 |              0 |            15 |            0
        70 | Outback Lager         |             15 |             10 |            30 |            0
(2 rows)
```