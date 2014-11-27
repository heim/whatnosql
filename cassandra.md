# Cassandra

## Quick glance

**Paradigm**: Wide Column Store

**Made by**: Datastax (originated from Facebook) [http://hwww.datastax.com/]

**Vendor-supported clients**: Java, C#, Node.js, Python, Ruby, C++

**Open-source clients**: Clojure, Erlang, Go, Haskell, Java, Perl, PHP, R, Rust, Scala, ODBC, Apache Spark. 


## Description

Cassandra is a mature database used by my major actors [[http://www.datastax.com/customers](http://www.datastax.com/customers)]. It is the right choice when you need scalability and high availability without compromising performance.

## Querying

Cassandra supports querying with a custom-made query-language, [CQL](http://www.datastax.com/documentation/cql/3.1/cql/cql_using/about_cql_c.html), or through a variety of vendor- and open-source client. 

## Tooling

Shell (cqlsh). Open source and enterprise tools to monitor and manage the cluster.

## Import (?)

Import data from csv-files.

## Interface

Standalone servers.

## Implementation

Cassandra is implemented in Java.

## Licensing

Apache License 2.0.

## Is a good fit for:

Fraud detection, Recommendation, Personalization, Sensor data, Internet of things, Write-intensive applications, Product catalog, Playlist, Messaging, Always available, Easily scalable

## Limitations

Joins and subqueries are not supported. Aggregations are limited like Apache Solr and Apache Spark is often used to provide search- and aggregations. A column value may not be larger than 2GB. The maximum number of columns for a single row is 2 billion. 

## Good places to start

* [Getting Started Guide](http://www.datastax.com/documentation/getting_started/doc/getting_started/gettingStartedCassandraIntro.html)
* [Official website](http://cassandra.apache.org/)
* [Documentation](http://www.datastax.com/docs)
* [Community website](http://planetcassandra.org/)
* [Free online training](https://academy.datastax.com/)
