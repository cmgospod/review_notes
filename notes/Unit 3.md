Using python 101
modules, environments, packages
oop, code styling, etc
docker lets you create an environment with pipenv so that code will be reproducible on different machines
testing!
unittest is built in
you can make a separate unittest file to ensure your code is working
SQL in python
1 library
2 connection
3 cursor(s)
4 execute query
5 fetch results if applicable
6 close connection
inner join is the one you really care about, but you can also right or left join
cross join multiplies all the rows
many-to-many, many-to-one, one-to-many
many-to-many allows for a lot of operations
one-to-one is also great
mySQL, SQLite for small projects, postgres for larger ones
document-oriented stores are based off hash tables
non-relational is the correct term
huge cloud databases
Atomicity: Each transaction is treated as a unit which either succeeds totally or fails totally
Consistency: Every transaction must take the database from one valid state to another
Isolation: Concurrent and sequential transactions produce the same result
Durability: Completed transactions will remain completed even in the case of a power failure or system crash
BASE: Basically Available, Soft state, Eventually consistent
FLASK
pickling: builtin feature to dump an object in memory as a string or binary

