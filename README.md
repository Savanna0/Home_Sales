# Home_Sales

## Overview
In this challenge, we used SparkSQL to look at home sales data. By using SparkSQL, we were able to create temporary views, create queries, partition the data, cache and uncache a temporary table, and verify that the table has been uncached.

## Runtimes
In this challenge, we used cached and uncached home sales data to determine the runtimes and compare the cached and uncached runtimes.
For the unchached data, we saw a runtime of 1.41. Using the same query, we cached the data and saw a runtime of 0.84. Finally, we used the cached data and used parquet formatted data, used the same query, and received a runtime of 1.02. 

Looking at the runtimes, we can see that using the cached data we returned the shortest time of 0.84.


## Resources
Resources provided by instructor assistance, class material, instructor video recordings, and examples given from TTC Bootcamp. Xpert Learning Assistant provided by TCC Bootcamp. Tutoring provided by TTC Bootcamp.
