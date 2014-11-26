# Datomic

## Quick glance

**Paradigm**: Row-oriented, graph, key-value and column-oriented.  [https://www.youtube.com/watch?v=YSriFOsoP7g#t=404]

**Made by**: Cognitect [http://cognitect.com/]

**Vendor-supported clients**: Java and Clojure. Accesible for all languages on the JVM. 

**Open-source clients**: 
[https://github.com/pellucidanalytics/datomisca] – Native JVM Peer with Scala idioms
[https://github.com/relevance/diametric] – Native (JRuby) and REST ActiveModel wrapper for Ruby
[https://github.com/limadelic/datomicjs] – REST client in JavaScript, for use with Node.js and similar
[https://github.com/jeffbrown/groovy-datomic] – Native JVM Peer with Groovy idioms
[https://github.com/gns24/pydatomic] – REST client in Python


## Description/Architecture?

Datomic is an immutable database with built-in versioning, supporting many database paradigms. The query engine (called Peer Library) is embedded in the consuming applications, storing part of the data in memory. Long running queries does not slow down overall database performance. Datomic does not include a datastore, but is pluggable into multiple datastores, e.g. Oracle, Infinispan and Amazon DynamoDB.


## Querying

Datomic uses EDN (extensible data notation) as its query language. TODO: describe eden.

## Tooling
TODO

## Import (?)
TODO

## Interface

Datomic is accesible via the Peer Library, but also has an experimental REST interface.

## Implementation

Datomic is implemented in Java and Clojure. 

## Licensing

A free license model for in memory storage and a pro license based on the number of peers.

## Is a good fit for:

Problems where traceability and auditing is of importance. Due to the immutable data model, no data is ever deleted. Problems where you need to see earlier versions of the data.

## Limitations

Datomic provides near linear read scaling, but has a limit on the number of writes.

## Good places to start


