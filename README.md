# Neo4j Cypher Query Formatter

When I first started working with Neo4j and Cypher, I quite liked the syntax overall - but I couldn't see any simple, accessible query formatters online - hence this project.

It uses a primitive regex approach to take an unformatted Cypher query and return a fairly usefully formatted query.

You can try the formatter out [on my personal site here](https://www.tristanperry.com/cypher-query-formatter).

## Project TODOs

* Add formatting for `CASE WHEN...` statements.
* Add extra formatting for the contents of `return { ... }` block (currently I just add two-space indentation to each line within a `return` block).
* Add colored output (as an option).
* Add a few unit tests to verify a few different queries get returned as expected.
