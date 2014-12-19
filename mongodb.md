#MongoDB

**Paradigm**: Document

**Made by**: MongoDB, Inc.

## Description
MongoDB is a [widely adopted](http://db-engines.com/en/ranking) [open-source](https://github.com/mongodb/mongo) [Document-store](www.nosql.com).

## Querying
Querying in MongoDB is done with a [Javascript interface](http://docs.mongodb.org/manual/tutorial/query-documents/). Most often however when developing applications you would use one of the many native drivers out [there](http://docs.mongodb.org/ecosystem/drivers/). Querying is developer centric as the query language is natively javascript code not a [DSL](http://en.wikipedia.org/wiki/Domain-specific_language).

## Tooling

## Import (?)
MongoDB natively has a [import command](http://docs.mongodb.org/ecosystem/drivers/) that accepts JSON, CSV and TSV. In addition there are various [supported](https://github.com/10gen-labs/mongo-connector) and third-party connectors for syncing with different databases.

## Interface


## Implementation
MongoDB is implemented in C++. Drivers are commonly implemented in their respective languages.

## Licensing
MongoDB Database Server and Tools: GNU AGPL v3.0.

mongodb.org supported drivers: Apache License v2.0.

third party drivers varies

## Is a good fit for:
Because of flexible schemas good fit for heterogeneous data.
E.g. Product data

Rapid development, prototyping, easy access javascript API.

## Limitations
Since MongoDB uses memory-mapped files, the 32bit-build limits total filesize (server, data, indexes) is 2GB.
Not recommended to use 32-bit build in production.

The 64-bit version have virtually no limit in storage size.

Ref: http://docs.mongodb.org/manual/faq/storage/#faq-storage-memory-mapped-files

## Good places to start
* Online courses: https://university.mongodb.com/
* Documentation: http://docs.mongodb.org/manual/
