---
layout: default
title: Awesome Rank for neueda/awesome-neo4j
---

<p align="center">
	This list is a copy of <a href="https://github.com/neueda/awesome-neo4j">neueda/awesome-neo4j</a> with ranks
</p>
---
Awesome Neo4j
==============
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg) ★67308](https://github.com/sindresorhus/awesome)
[![Build Status](https://api.travis-ci.org/neueda/awesome-neo4j.svg?branch=master )](https://travis-ci.org/neueda/awesome-neo4j)

A curated list of awesome [Neo4j](https://neo4j.com/) resources.  
Inspired by the `awesome-*` trend on GitHub.

The goal is to build a categorized community-driven collection of very well-known resources.  
Sharing, suggestions and contributions are always welcome!

Thanks to all [contributors](https://github.com/Neueda/awesome-neo4j/graphs/contributors).

Maintained by [Neueda R&D](https://neueda.lv/).


Table of Contents
=================

  * [Basics](#basics)
  * [Connectors](#connectors)
    * [Bolt](#bolt)
    * [REST API](#rest-api)
      * [Java](#java)
      * [Ruby](#ruby)
      * [Python](#python)
      * [PHP](#php)
      * [Other](#other)
  * [Cloud](#cloud)
  * [Packages](#packages)
  * [Docker](#docker)
  * [Full\-text search](#full-text-search)
  * [Import](#import)
  * [Benchmarking](#benchmarking)
  * [Extensions](#extensions)
  * [Stored Procedures](#stored-procedures)
  * [Development](#development)
  * [Editors](#editors)
  * [Shell](#shell)
  * [Visualization](#visualization)
  * [Tools](#tools)
  * [Resources](#resources)
    * [Learn](#learn)
    * [Certification](#certification)
    * [Bolt](#bolt-1)
    * [Books](#books)
    * [Miscellaneous](#miscellaneous)
  * [License](#license)

Created by [gh-md-toc ★137](https://github.com/ekalinin/github-markdown-toc.go)

# Basics

- [Official documentation](http://neo4j.com/docs/)
- [Cypher Refcard](http://neo4j.com/docs/cypher-refcard/current/)
- [Developer resources](https://neo4j.com/developer/get-started/)
- [Gists](http://graphgist.neo4j.com/) - With Neo4j GraphGists you can describe and model your domain in a simple text file and render it as a rich, interactive page in any browser. Perfect to document a specific domain, use-case, question or graph problem.
- [Neo4j Examples](https://github.com/neo4j-examples) - Examples for Neo4j and Library Usage.

# Related project

- [openCypher](http://www.opencypher.org/) - openCypher is an open source project to bring a new public implementation of the industry’s most widely adopted graph query language: Cypher.
- [Bolt Protocol](http://boltprotocol.org/) - The Bolt network protocol is a highly efficient, lightweight client-server protocol designed for database applications.

# Connectors

## Bolt

- [neo4j-java-driver ★101](https://github.com/neo4j/neo4j-java-driver) - Java driver for Neo4j binary protocol.
- [neo4j-python-driver ★127](https://github.com/neo4j/neo4j-python-driver) - Python driver for Neo4j binary protocol.
- [neo4j-javascript-driver ★267](https://github.com/neo4j/neo4j-javascript-driver) - JavaScript driver for Neo4j binary protocol.
- [neo4j-dotnet-driver ★46](https://github.com/neo4j/neo4j-dotnet-driver) - .Net driver for Neo4j (Bolt).
- [neo4j-bolt-php ★16](https://github.com/graphaware/neo4j-bolt-php) - PHP driver for Neo4j binary protocol.
- [libneo4j-client ★38](https://github.com/cleishm/libneo4j-client) - libneo4j-client is a client library written in C for Neo4j. It is not intended as a complete driver, but rather as a foundation on which basic tools and drivers for various languages may be built. libneo4j-client takes care of all the detail of establishing a session with a Neo4j server, sending statements for evaluation, and retrieving results.
- [neo4j-spark-connector ★86](https://github.com/neo4j-contrib/neo4j-spark-connector) - Neo4j-Spark-Connector based on Neo4j 3.0's Bolt protocol
- [neo4j-elixir-driver ★19](https://github.com/mschae/boltex) - Elixir driver for the neo4j bolt protocol
- [neo4j-elixir-wrapper ★62](https://github.com/florinpatrascu/bolt_sips) - Neo4j driver for Elixir, wrapped around the Bolt protocol. Fork of the Boltex.

## REST API

### Java

- [neo4j-ogm ★140](https://github.com/neo4j/neo4j-ogm) - Object-Graph Mapping Library for Neo4j.
- [spring-data-neo4j ★467](https://github.com/spring-projects/spring-data-neo4j) - Provides support to increase developer productivity in Java when using the neo4j graph database.
- [neo4j-jdbc ★32](https://github.com/neo4j-contrib/neo4j-jdbc) - Neo4j JDBC driver.
- [jcypher ★46](https://github.com/Wolfgang-Schuetzelhofer/jcypher) - Java access to Neo4J graph databases at multiple levels of abstraction.

### Ruby

- [neo4jrb ★1147](https://github.com/neo4jrb/neo4j) - An active model wrapper for the Neo4j Graph Database for Ruby.
- [neography ★605](https://github.com/maxdemarzi/neography) - A thin Ruby wrapper to the Neo4j Rest API.

### Python

- [py2neo ★22](https://github.com/nigelsmall/py2neo) - Py2neo is a comprehensive toolkit for working with Neo4j from within Python applications or from the command line.
- [neomodel ★306](https://github.com/robinedwards/neomodel) - An Object Graph Mapper (OGM) for the neo4j graph database, built on the awesome py2neo.
- [BulbFlow](https://github.com/espeed/bulbs) - A Python persistence framework for graph databases like Neo4j, OrientDB and Titan.

### PHP

- [Neo4j-PHP-OGM ★95](https://github.com/graphaware/neo4j-php-ogm) - Doctrine style Object Graph Mapper for Neo4j
- [neo4jphp ★536](https://github.com/jadell/neo4jphp) - PHP wrapper of the Neo4j REST interface.
- [NeoEloquent ★327](https://github.com/Vinelab/NeoEloquent) - A Neo4j ORM - Based on Eloquent.
- [neo4j-php-client](https://github.com/graphaware/neo4j-php-client/tree/4.0) - PHP Client for Neo4j leveraging the Http and Bolt protocols.
- [Spider ★22 ⏳1Y](https://github.com/spider/spider) - A simple, flexible, and beautiful graph-data abstraction for php.

### Other

- [node-neo4j ★923](https://github.com/thingdom/node-neo4j) - REST API client for Node.
- [Neo4jClient ★213](https://github.com/Readify/Neo4jClient) - .NET client binding.
- [neoism ★305](https://github.com/jmcvetta/neoism) - Client for Golang.
- [neocons ★161](https://github.com/michaelklishin/neocons) - A feature rich idiomatic Clojure client for the REST API.
- [RNeo4j ★201](https://github.com/nicolewhite/RNeo4j) - Driver for R.
- [AnormCypher ★121](https://github.com/AnormCypher/AnormCypher) - Scala library based on Anorm in the Play Framework.

# Cloud

- [GrapheneDB](http://www.graphenedb.com/) - The world's first fully managed
Neo4j graph database.
- [GraphStory](https://www.graphstory.com/) - Neo4j enterprise cloud provider

# Packages

- [Debian Packages](http://debian.neo4j.org/)
- [Yum Repo](http://yum.neo4j.org/)

# Docker

- [docker-neo4j ★84](https://github.com/neo4j/docker-neo4j) - Docker Images for the Neo4j Graph Database.
- [docker-neo4j-cluster ★32 ⏳1Y](https://github.com/ekino/docker-neo4j-cluster) - Up & Running Neo4j cluster in no time.

# Full-text search

- [GraphAware Neo4j Elasticsearch Integration ★90](https://github.com/graphaware/neo4j-to-elasticsearch) - GraphAware Framework Module for Integrating Neo4j with Elasticsearch.
- [GraphAware Graph-Aided Search ★60](https://github.com/graphaware/graph-aided-search) - Elasticsearch plugin offering Neo4j integration for Personalized Search.
- [neo4j-elasticsearch ★73](https://github.com/neo4j-contrib/neo4j-elasticsearch) - Neo4j ElasticSearch Integration.

# Import

- [GraphAware Neo4j Importer ★15](https://github.com/graphaware/neo4j-importer) - Java importer skeleton for complicated, business-logic-heavy high-performance Neo4j imports directly from SQL databases, CSV files, etc.
- [neo4j-csv-firehose ★7 ⏳1Y](https://github.com/sarmbruster/neo4j-csv-firehose) - Enables Neo4j’s `LOAD CSV` Cypher command to load from other datasources as well.
- [neo4j-rdbms-import ★26 ⏳1Y](https://github.com/jexp/neo4j-rdbms-import) - An automatic importer for relational databases into Neo4j.
- [Doc manager for Neo4j ★61 ⏳1Y](https://github.com/neo4j-contrib/neo4j_doc_manager) - The Neo4j Doc Manager takes MongoDB documents and makes it easy to query them for relationships by making them available in a Neo4j graph structure, following the format specified by Mongo Connector.

# Benchmarking

- [neoprofiler ★23 ⏳2Y](https://github.com/moxious/neoprofiler) - Neo4J database profiling utility.

# Extensions

- [GraphAware Neo4j UUID ★50](https://github.com/graphaware/neo4j-uuid) - GraphAware Runtime Module that assigns a UUID to all nodes in the graph transparently.
- [GraphAware Neo4j ChangeFeed ★9 ⏳1Y](https://github.com/graphaware/neo4j-changefeed) - A GraphAware Framework Runtime Module allowing users to find out what were the latest changes performed on the graph.
- [GraphAware Neo4j TimeTree ★120](https://github.com/graphaware/neo4j-timetree) - Java and REST APIs for working with time-representing tree in Neo4j.
- [GraphAware Neo4j Recommendation Engine ★202](https://github.com/graphaware/neo4j-reco) - Neo4j-based recommendation engine module with real-time and pre-computed recommendations.
- [GraphAware Neo4j NodeRank ★25](https://github.com/graphaware/neo4j-noderank) - GraphAware Timer-Driven Runtime Module that executes PageRank-like algorithm on the graph.
- [GraphAware Neo4j Algorithms ★32 ⏳1Y](https://github.com/graphaware/neo4j-algorithms) - Custom graph algorithms for Neo4j with own Java and REST APIs.
- [GraphAware Neo4j Warmup ★10 ⏳1Y](https://github.com/graphaware/neo4j-warmup) - Simple library that warms up Neo4j caches with a single REST call.
- [GraphAware Neo4j RestTest ★8](https://github.com/graphaware/neo4j-resttest) - GraphAware RestTest is a simple library for testing code that talks to Neo4j running in standalone server mode.
- [GraphAware Neo4j Expire ★20](https://github.com/graphaware/neo4j-expire) - GraphAware Expire is a simple library that automatically deletes nodes and relationships from the database when they've reached their expiration date or time-to-live (TTL).
- [Spatial ★530](https://github.com/neo4j-contrib/spatial) - Neo4j Spatial is a library of utilities for Neo4j that faciliates the enabling of spatial operations on data.
- [Graphify ★339](https://github.com/Graphify/graphify) - Graphify is a Neo4j unmanaged extension used for document and text classification using graph-based hierarchical pattern recognition.
- [neo4j-tx-participation ★3 ⏳2Y](https://github.com/jexp/neo4j-tx-participation) - This is a Neo4j Server Extension to make Neo4j REST-API participate in transactions started by the transactional Cypher endpoint.

# Stored Procedures

- [Apoc : Awesome Procedures on Cypher ★382](https://github.com/neo4j-contrib/neo4j-apoc-procedures) - Collection of useful procedures for Neo4j 3.x
- [Graphgen ★5 ⏳1Y](https://github.com/graphaware/neo4j-graphgen-procedure) - Neo4j procedure for generating test data easily with Cypher

# Development

- [Maven repositories](https://m2.neo4j.org/index.html) - Neo4j Maven repositories (releases, snapshots).
- [GraphAware Neo4j Framework ★159](https://github.com/graphaware/neo4j-framework)- GraphAware Framework speeds up development with Neo4j by providing a platform for building useful generic as well as domain-specific functionality, analytical capabilities, (iterative) graph algorithms, etc.
- [cypher-dsl ★52](https://github.com/neo4j-contrib/cypher-dsl) - A Java DSL for the Cypher Query Language and an optional Query DSL mode.
- [Liquigraph ★66](https://github.com/liquigraph/liquigraph) - Database migrations management tool, based on how Liquibase works.
- [blueprints ★1252](https://github.com/tinkerpop/blueprints) - Blueprints is a collection of interfaces, implementations, ouplementations, and test suites for the property graph data model. Blueprints is analogous to the JDBC, but for graph databases.
- [structr ★461](https://github.com/structr/structr) - Graph Application Platform based on Neo4j.
- [Reco4PHP ★75](https://github.com/graphaware/reco4php) - Neo4j based Recommendation Engine Framework for PHP.

# Editors

- [jetbrains-plugin-graph-database-support ★65](https://github.com/neueda/jetbrains-plugin-graph-database-support) - Graph Databases support for Jetbrains family IDE's.
- [cypher-vim-syntax ★17 ⏳3Y](https://github.com/neo4j-contrib/cypher-vim-syntax) - Very basic Vim syntax for Cypher.

# Shell

- [cycli ★193](https://github.com/nicolewhite/cycli) - A Command Line Interface for Cypher.
- [neo4j-shell-tools ★217](https://github.com/jexp/neo4j-shell-tools) - A bunch of import/export tools for the neo4j-shell.

# Visualization

- [neoclipse ★183](https://github.com/neo4j-contrib/neoclipse) - Neoclipse is a tool to view, edit and explore Neo4j databases.
- [Gephi ★2235](https://github.com/gephi/gephi) - Gephi is an award-winning open-source platform for visualizing and manipulating large graphs.
- [Linkurious](http://linkurio.us/) - Linkurious helps search and visualize your graph data through a simple web-based interface.

# Tools

- [Graphgen](http://graphgen.graphaware.com) - Graph Generation engine based on the Cypher DSL.
- [store-utils ★54](https://github.com/jexp/store-utils) - Utilities to compact, copy, fix, analyse Neo4j stores.
- [ineo ★32](https://github.com/cohesivestack/ineo)- A simple but useful Neo4j instance manager.

## Learn

- [Getting Started with Neo4j](https://neo4j.com/graphacademy/online-training/introduction-graph-databases/)
- [Neo4j in Production](https://neo4j.com/graphacademy/online-training/neo4j-production/)
- [Neo4j Koans ★290 ⏳2Y](https://github.com/jimwebber/neo4j-tutorial) - A koan-style tutorial in Java for Neo4j.

## Certification

- [Neo4j Certification](https://neo4j.com/graphacademy/neo4j-certification/) - Become a Neo4j-Certified Professional.

## Miscellaneous

- [Neo4j's Idea board](https://trello.com/b/2zFtvDnV/public-idea-board)
- [Hardware Sizing Calculator](https://neo4j.com/hardware-sizing-calculator/)

# License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Neueda R&D](https://github.com/Neueda) has waived all copyright and related or neighboring rights to this work.
---
<p align="center">
	This list is a copy of <a href="https://github.com/neueda/awesome-neo4j">neueda/awesome-neo4j</a> with ranks
</p>
