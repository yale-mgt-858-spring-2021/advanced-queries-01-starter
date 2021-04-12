OMG. We realized that we've made over a million dollars in 
revenue. Woot! Crud, we should have had a party 🥳 to celebrate.
Well, we're going to do that that now. But, out of curiosity,
we'd like to know on what day we should have held our party.
On what day did our total revenue (in the history of the company)
exceed $1M?

You might want to look at [PostgreSQL window functions](https://www.postgresql.org/docs/9.1/tutorial-window.html).

Your results should look as follows

```
party_date
------------
2020-12-02
(1 row)
```

## Edits

### Sun Apr 11 08:53:29 EDT 2021
* Add hint on `highest-freight-charges` regarding finding the most
  recent 12mo of data.
* Clarify `end-of-month-orders`. The "last week" means the "last seven days".

## Sun Apr 11 16:08:33 EDT 2021
* Add that `orders-to-latin-america` should be sorted by `order_id`

## Mon Apr 12 08:32:31 EDT 2021
* Mention that I won't be telling you what tables to query.
* Clarify that I don't care about uppercase vs. lowercase in the
  `queso` problem.
* Add that `orders-to-france-or-belgium` should be ordered by
  `order_id`.
* Fix typo in `products-with-suppliers`.
* Fix markdown formatting in `highest-freight-charges`