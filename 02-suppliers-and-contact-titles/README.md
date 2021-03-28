
In the Suppliers table, show the `supplier_id`, `contact_name`, and `contact_title`
for those `suppliers` whose `contact_title` is not "Marketing Manager".

Your results should look like this

```
supplier_id |        contact_name        |        contact_title
-------------+----------------------------+------------------------------
          1  | Charlotte Cooper           | Purchasing Manager
          2  | Shelley Burke              | Order Administrator
          3  | Regina Murphy              | Sales Representative
          5  | Antonio del Valle Saavedra | Export Administrator
          6  | Mayumi Ohno                | Marketing Representative
          8  | Peter Wilson               | Sales Representative
          9  | Lars Peterson              | Sales Agent
          11 | Petra Winkler              | Sales Manager
          12 | Martin Bein                | International Marketing Mgr.
          13 | Sven Petersen              | Coordinator Foreign Markets
          14 | Elio Rossi                 | Sales Representative
          16 | Cheryl Saylor              | Regional Account Rep.
          17 | Michael Björn              | Sales Representative
(...)
(24 rows)
```