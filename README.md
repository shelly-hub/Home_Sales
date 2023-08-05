# Home_Sales

## Project Aim

This challenge practises the use of SparkSQL on big data and in this case is home sales data which made up of about 30,000 data points and 2600Kb size of CSV file. 

## Project Description
This challenge particularly uses Google Colab, an app in a Google drive to write and execute Python in personal browser. 

Particularly our challenge practises the use of Sparks library to read big data in an efficient way.

## Project Method
Three methods from Sparks were used to compare the time taken to execute a particular query.

1. Original time query
2. Cache and Uncache temporary table
3. Partition data on "date_built"

## Results
Cache does output half of the time taken from original query. 

Partioning data that does not have relationships in the query delay the output. 

## Reference
GROUP BY and FILTER.(N.D.).Data World. Retrieved on 03/8/2023, from <https://docs.data.world/documentation/sql/concepts/intermediate/GROUP_BY.html>

MySQL ROUND() Function.(1999-2023). W3 Schools. Retrieved on 03/08/2023, from<https://www.w3schools.com/sql/func_mysql_round.asp>

SQL - Group By.(N.D.). tutorialspoint. Retrieved on 03/08/2023, from< https://www.tutorialspoint.com/sql/sql-group-by.htm>


