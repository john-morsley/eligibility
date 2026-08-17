Eligibility
===========

An attempt to take a flat table, held within a single file, and process it until we are capable of determining eligibility.

Eligibiliy is a yes or no result when various criteria are met.

Here is the table:

```
+-------+-----------+----------+-----------------------------+
|       |           |          |       Finance Product       |
|       |           |          +-----------------+-----------+  
|       |           |          |     Purchase    |    Hire   |
|       |           |          +-----+-----+-----+-----+-----+
| Power | Condition | Customer | HP  | PCP | LP  | PCH | BCH |
+=======+===========+==========+=====+=====+=====+=====+=====+
| BEV   | New       | Personal |  Y  |  Y  |  Y  |  Y  |  N  |
| BEV   | New       | Business |  Y  |  Y  |  Y  |  N  |  Y  |
| BEV   | Used      | Personal |  Y  |  Y  |  Y  |  Y  |  N  |
| BEV   | Used      | Business |  Y  |  N  |  Y  |  N  |  Y  |
| BEV   | New       | Personal |  Y  |  Y  |  Y  |  Y  |  N  |
| BEV   | New       | Business |  Y  |  Y  |  Y  |  N  |  Y  |
| BEV   | Used      | Personal |  Y  |  N  |  Y  |  N  |  N  |
| BEV   | Used      | Business |  Y  |  N  |  Y  |  N  |  Y  |
| ICE   | New       | Personal |  Y  |  Y  |  Y  |  Y  |  N  |
| ICE   | New       | Business |  Y  |  Y  |  Y  |  N  |  Y  |
| ICE   | Used      | Personal |  Y  |  Y  |  Y  |  N  |  N  |
| ICE   | Used      | Business |  Y  |  N  |  Y  |  N  |  Y  |
| ICE   | New       | Personal |  Y  |  Y  |  Y  |  Y  |  N  |
| ICE   | New       | Business |  Y  |  Y  |  Y  |  N  |  Y  |
| ICE   | Used      | Personal |  Y  |  N  |  Y  |  N  |  N  |
| ICE   | Used      | Business |  Y  |  N  |  Y  |  N  |  Y  |
+-------+-----------+----------+-----+-----+-----+-----+-----+
```


