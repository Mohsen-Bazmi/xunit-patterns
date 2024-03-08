# xunit-patterns
A graph of xunit test patterns.
Importing this graph should add `281` pattern nodes and `71` smell nodes to the database.

```cypher
MATCH (p:Pattern)
RETURN count(p)
```
```cypher
MATCH (p:Smell)
RETURN count(p)
```
