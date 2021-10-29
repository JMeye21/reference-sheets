# SQL Commands

The following table includes the clauses, keywords, and statements that I have encountered and have experience with, they are listed alphabetically.

| Keyword | Description | Syntax |
| --- | --- | --- |
| [AND] | All conditions must be true to return a record | condition AND condition |
| [AVG] | Returns column's average | AVG(column) |
| [BETWEEN] | Selects values within a range (inclusive) | WHERE column BETWEEN value AND value |
| [CEILING] | Returns the lowest integer >= x | CEILING(x) |
| [COUNT] | Returns a count of matching records | COUNT(column) |
| [DISTINCT] | Fetch different values only | SELECT DISTINCT column |
| [FLOOR] | Returns the highest integer =< x | FLOOR(x) |
| [FROM] | Specify the table | FROM table |
| [GROUP BY] | Group the resulting entries based on a column | GROUP BY column |
| [IN] | Returns a record if it is in a list of conditions, alternative to OR | WHERE column IN (value, value) |
| [LEFT] | Grabs a substring of x characters starting on the left | LEFT(text, x) |
| [LIMIT] | Limits the amount of results to a certain num | LIMIT num |
| [LOWER] | Converts text to lowercase | LOWER(text) |
| [MAX] | Returns max value in column | MIN(column) |
| [MIN] | Returns min value in column | MAX(column) |
| [MOD] | Returns the remainder of x/y | MOD(x, y) |
| [NOT] | Returns a record if the condition was FALSE  | NOT condition |
| [OR] | One of the conditions must be true to return a record | condition OR condition |
| [ORDER BY] | Sort results in ascending/descending order, default: ASC | ORDER BY column ASC\|DESC |
| [POW] | Raises x to the y power | POW(x, y) |
| [REPLACE] | Replace x with y in the string | REPLACE(column/text, x, y) |
| [RIGHT] | Grabs a substring of x characters starting on the right | RIGHT(text, x) |
| [ROUND] | Round x down to y decimal places | ROUND(x, y) |
| [SELECT] | Use to select data | SELECT column |
| [SQUARE] | Returns the square of x | SQUARE(x) |
| [SQRT] | Returns the square root of x | SQRT(x) |
| [SUBSTR] | Grabs a substring | SUBSTR(string/column, position, length) |
| [SUM] | Returns the sum of a column | SUM(column) |
| [TRUNCATE] | Truncates x to y decimal places | TRUNCATE(x, y) |
| [UPPER] | Converts text to uppercase | UPPER(text) |
| [WHERE] | Filter results | WHERE condition |

### Example Queries

The queries interact with the "NAME" table:
| x | y | z |
| --- | --- | --- |
| v1 | v2 | v3 |

| Keyword | Example Query |
| --- | --- |
| [AND] | |



<!-- TEMPLATE LINE FOR THE TABLE
| [] |  |  |
--->
<!-- Below is the list of links --->
[AND]: https://www.w3schools.com/Sql/sql_and_or.asp
[AVG]: https://www.w3schools.com/Sql/sql_count_avg_sum.asp
[BETWEEN]: https://www.w3schools.com/sql/sql_between.asp
[CEILING]: https://www.w3schools.com/Sql/func_sqlserver_ceiling.asp
[COUNT]: https://www.w3schools.com/SQl/sql_count_avg_sum.asp
[DISTINCT]: https://www.w3schools.com/Sql/sql_distinct.asp
[FLOOR]: https://www.w3schools.com/Sql/func_sqlserver_floor.asp
[FROM]: https://www.w3schools.com/sql/sql_ref_from.asp
[GROUP BY]: https://www.w3schools.com/sql/sql_groupby.asp
[IN]: https://www.w3schools.com/Sql/sql_in.asp
[LEFT]: https://www.w3schools.com/SQL/func_sqlserver_left.asp
[LIMIT]: https://www.geeksforgeeks.org/sql-limit-clause/
[LOWER]: https://www.w3schools.com/SQL/func_sqlserver_lower.asp
[MAX]: https://www.w3schools.com/Sql/sql_min_max.asp
[MIN]: https://www.w3schools.com/Sql/sql_min_max.asp
[MOD]: https://www.w3schools.com/Sql/func_mysql_mod.asp
[NOT]: https://www.w3schools.com/Sql/sql_and_or.asp
[OR]: https://www.w3schools.com/Sql/sql_and_or.asp
[ORDER BY]: https://www.w3schools.com/Sql/sql_orderby.asp
[POW]: https://www.w3schools.com/sqL/func_mysql_pow.asp
[REPLACE]: https://www.w3schools.com/SQL/func_sqlserver_replace.asp
[RIGHT]: https://www.w3schools.com/SQL/func_sqlserver_right.asp
[ROUND]: https://www.w3schools.com/SQL/func_sqlserver_round.asp
[SELECT]: https://www.w3schools.com/sql/sql_select.asp
[SQUARE]: https://www.w3schools.com/SQL/func_sqlserver_square.asp
[SQRT]: https://www.w3schools.com/SQl/func_mysql_sqrt.asp
[SUBSTR]: https://www.w3schools.com/SQL/func_sqlserver_substring.asp
[SUM]: https://www.w3schools.com/Sql/sql_count_avg_sum.asp
[TRUNCATE]: https://www.sqltutorial.org/sql-math-functions/sql-truncate/
[UPPER]: https://www.w3schools.com/SQL/func_sqlserver_upper.asp
[WHERE]: https://www.w3schools.com/Sql/sql_where.asp
