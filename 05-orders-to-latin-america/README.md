
Write a query that shows the `order_id`, `customer_id`, and
`ship_country` for the orders where the `ship_country` is in Latin
America. That is "Brazil", "Mexico", "Argentina" or "Venezuela" in these
data. (There are no other countries in Latin America in the data set.)
Sort by ascending `order_id`.

Your results should look like this

```
order_id | customer_id | ship_country
----------+-------------+--------------
    10250 | HANAR       | Brazil
    10253 | HANAR       | Brazil
    10256 | WELLI       | Brazil
    10257 | HILAA       | Venezuela
    10259 | CENTC       | Mexico
    (...)
    11069 | TORTU       | Mexico
    11071 | LILAS       | Venezuela
    11073 | PERIC       | Mexico
(173 rows)
```