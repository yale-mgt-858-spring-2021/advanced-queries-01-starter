
OK, we're going to have a little sales contest.  💵📈 First prize is a
Cadillac Eldorado. Anyone want to see second prize? Second prize is a set
of steak knives.  Third prize is you're fired.

Please rank our sales persons by their aggregate sales in 2021.  Give the
`employee_id`, `first_name`, `last_name` and `sales` total in descending
order. Make sure you account for discounts customers received (as
indicated in the `order_details` table). The discounts are fractional
prices, so a discount of `0.25` means a customer paid 75% of the price,
that is 1 - 0.25 = 0.75.
 
Your results should look as follows

```
employee_id | first_name | last_name |       sales
------------+------------+-----------+--------------------
          2 | Andrew     | Fuller    | 40675.594987826196
          1 | Nancy      | Davolio   |  39869.94541339143
          7 | Robert     | King      |  29751.39744670667
          8 | Laura      | Callahan  |  28530.20009724617
          3 | Janet      | Leverling |   16971.1549362652
          4 | Margaret   | Peacock   |  16447.95995879769
          9 | Anne       | Dodsworth | 11028.694984717966
          6 | Michael    | Suyama    |  5538.499986787885
          5 | Steven     | Buchanan  |                210
(9 rows)
```