# Redis

## Quick glance

**Paradigm**: Key/Value

**Made by**: Salvatore Sanfilippo, sponsored by Pivotal [http://redis.io]

**Vendor-supported clients**: Node.js, Ruby, C, Python

**Open-source clients**: Java, Scala, C#, Clojure, Dart, Go, Haskell +++

## Description

Redis is a fast and advanced in-memory key-value store. The database is used by companies like Twitter, Hulu and Pinterest [http://www.pivotal.io/big-data/redis]. 

## Querying

Redis is accessed via a series of commands. Being a key/value store it doesn't support traditional queries. A list of commands is available here: [http://redis.io/commands].

## Tooling
Web based admin interface deployed with the standalone REST server (http://www.neo4j.org/tracks/neo4j_server) and shell (http://docs.neo4j.org/chunked/milestone/shell.html).

## Import (?)
Import should be done using the Luke-protocol. See the documentation for more information: [http://redis.io/topics/mass-insert]

## Interface
Redis is accessed via the clients [http://redis.io/clients]. Not all clients support Redis Sentinel (Master-Slave architecture) at the moment.

## Implementation

Neo4j is implemented in C.

## Licensing

The BSD 3-Clause License [http://redis.io/topics/license]

## Is a good fit for:

Small high-performance databases. Typical use cases are advanced read/write caches and small publish/subscribe systems.

## Limitations

The whole database has to fit in RAM. There is currently no production-ready system in place for sharding data, but Redis has written a guide on this here: [http://redis.io/topics/partitioning]

## Good places to start

* Redis commands, http://redis.io/commands
* Introduction to data types, http://redis.io/topics/data-types-intro
* Spring Data Redis, http://projects.spring.io/spring-data-redis/

