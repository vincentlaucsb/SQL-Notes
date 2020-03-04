## Joins
Joins are a way to combine data from two different tables, or rows in a table with rows from another table. In general, a join query combines two or more rows into one if they match some condition.

### Inner Join
This is the "default" join option, because if no qualifiers are put before the "JOIN" in a SQL query, then an inner join is performed.

In an inner join between table A and table B, a row from table A is matched with one or more rows from table B if they satisfy a join condition.

### Outer Joins
There are *left* and *right* outer joins. In a left outer join, all of the rows in the left table (the table left of the JOIN operator) appear at least once, even if there are no matching right table rows. In that case, all the right table columns are filled with NULL values. A right outer join works similarly.

### Full Joins
In a full join, all rows from both tables are present in the result at least once. If a row from the left table has no corresponding match in the right table, then the right table columns are filled with NULLs and vice-versa. 