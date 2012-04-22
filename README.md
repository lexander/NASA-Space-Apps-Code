NASA-Space-Apps-Code
====================

Public repo for code snippets related to NASA Space Apps Challenge Hackday

See http://www.datatables.org/ for details on data-table format.

See http://developer.yahoo.com/yql/ for details on the YQL.

To use the data-tables in this repository you can either:

1. Set the "env" URL parameter of the YQL console to point to the ".env" file in this repository, e.g.
````
    https://developer.yahoo.com/yql/console/?env=https://raw.github.com/lexander/NASA-Space-Apps-Code/master/allTables.env
````
2. Invoke the table using the "USE" operator in the YQL console, e.g.
````
    USE "https://raw.github.com/lexander/NASA-Space-Apps-Code/master/TestYqlTable.xml" AS testTable;
````