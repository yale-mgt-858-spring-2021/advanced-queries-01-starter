
We’d like to show a list of the orders that were made, including the
shipper that was used. Show the `order_id`, `order_date`, and
`company_name` of the shipper, and sort by `order_id`.  In order to not show
all the orders (there’s more than 800), show only those rows with an
`order_id` of less than 10300.

Your results should look like this

```
order_id | order_date |   company_name
----------+------------+------------------
    10248 | 2019-04-17 | Federal Shipping
    10249 | 2019-04-18 | Speedy Express
    10250 | 2019-04-21 | United Package
    10251 | 2019-04-21 | Speedy Express
(...)
    10297 | 2019-06-18 | United Package
    10298 | 2019-06-19 | United Package
    10299 | 2019-06-20 | United Package
(52 rows)
```