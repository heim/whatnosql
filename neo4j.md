# Neo4j

## Quick glance

**Paradigm**: Graph

**Made by**: Neo Technologies [http://neo4j.com/]

**Vendor-supported clients**: Java

**Open-source clients**: NodeJS (experimental), Ruby, Clojure (+++)


## Description

Neo4j is a mature graph database used by major actors [http://neo4j.com/customers]. Neo4j is the leading graph database today, but other players are gaining momentum. 

## Querying

Neo4j supports querying with a proprietary query language, CYPHER [docs.neo4j.org/refcard/2.0/]. For more advanced queries one can use the Java APIs (Core and Traversal) [http://neo4j.com/docs/2.1.5/advanced-usage.html]

## Tooling
Web based admin interface deployed with the standalone REST server (http://www.neo4j.org/tracks/neo4j_server) and shell (http://docs.neo4j.org/chunked/milestone/shell.html).

## Import (?)
One may import data from csv files, or via custom import routines. It's important to use the batch-api in order to get good performance in the import-process.

## Interface
Neo4j may be used in two ways, as embedded or as a standalone REST server. 

## Implementation

Neo4j is implemented in Java. Some parts are implemented in Scala.

## Licensing

Three license-models: AGPLv3, GPLv3 or Enterprise Licence.

## Is a good fit for:

Highly relational data, social networks, fraud detection or general graph-like data structures. Queries should always start in a small set of nodes and traverse the database from there.

## Limitations

The database can't be sharded. Requires fast disks and lots of memory. Neo4j works best when the whole database fits in memory.

## Good places to start

* Tutorial: http://docs.neo4j.org/chunked/stable/tutorials.html
* Cypher reference: http://docs.neo4j.org/refcard/2.0/
* Graph Databases, the book: http://graphdatabases.com/
* Introduction to graph databases by Jim Webber: http://watch.neo4j.org/video/68905994
* Lots of tutorials: http://gist.neo4j.org/

