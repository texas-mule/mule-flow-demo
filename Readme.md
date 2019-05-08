# Flows and Database Connectors
Subflows can be created and then referenced from other flows. By placing a flow reference inside an Async block, the subflow becomes a non-blocking process.

# Postgres database connection
Set Build Path -> Set External Archives to point to your postgresql driver. Then set up a Database connector with a generic JDBC connection profile using the following format:
Url: jdbc:postgresql://localhost:5432/postgres?user=postgres&password=postgres
Driver Class Name: org.postgresql.Driver

