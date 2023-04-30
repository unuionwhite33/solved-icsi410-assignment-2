Download Link: https://assignmentchef.com/product/solved-icsi410-assignment-2
<br>
Write 10 separate SQL queries, named “Query11” through “Query20”. Put them in the same Access file you used to submit your first assignment. Each query will contain a SQL statement that is your solution for the translation of a “plain English” request. Each query is worth one point. The 10 “plain English” queries are:

<ol start="11">

 <li>Display all the columns in Customer for those that have one or more rows in Purchaser. (In other words, customers that have bought at least one vehicle.) Your overall strategy must be a subquery connected by an “<strong>IN</strong>”.</li>

 <li>Display all the columns in Customer for those that have one or more rows in Purchaser. (In other words, customers that have bought at least one vehicle.)</li>

</ol>

Your overall strategy must be a subquery connected by an “<strong>EXISTS</strong>”.

<ol start="13">

 <li>Display all the columns in Customer for those that have one or more rows in Purchaser. (In other words, customers that have bought at least one vehicle.) Your overall strategy must be a <strong>join</strong>.</li>

</ol>

Your solution can <strong>not</strong> contain any subqueries.

Note that the sequence of the output rows for Query 11, 12, and 13 may be different, but the overall data values returned must be identical.

<ol start="14">

 <li>Union together all 4 dealership code columns: dcode, edcode, vdcode, and rdcode.</li>

 <li>Display all the columns in Invoice for those invoices that have an iprice that is at least $25,000 but not more than $40,000. Use BETWEEN in your solution.</li>

 <li>Display vyear, row count, minimum weight, maximum weight, average weight, and total weight for each unique vyear value. Use just the Vehicle table.</li>

 <li>Count the number of different (i.e., unique) values of ieid in Invoice.</li>

 <li>Display vdcode for those dealerships that have less than 5 vehicles. Use just the Vehicle table.</li>

 <li>For each employee, display its count of rows in Invoice followed by all its columns in Employee. Include zero counts. Do <strong><u>not</u></strong> use UNION in your solution.</li>

 <li>Display the cid and clast columns in Customer for those customers that do not have a value for czip.</li>

</ol>

The rules for assignment #1 are still in effect for this assignment. Be sure to re-read them