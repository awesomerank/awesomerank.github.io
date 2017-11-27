---
layout: default
title: Awesome Rank for ramnes/awesome-mongodb
---

<p align="center">
	This list is a copy of <a href="https://github.com/ramnes/awesome-mongodb">ramnes/awesome-mongodb</a> with ranks
</p>
---
![Awesome MongoDB](https://github.com/ramnes/awesome-mongodb/blob/master/logo.png)

# Awesome MongoDB [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg) ★69735](https://github.com/sindresorhus/awesome)

> A curated list of awesome MongoDB resources, libraries, tools and applications

Inspired by the [awesome ★69735](https://github.com/sindresorhus/awesome) list thing. Feel free to improve this list by [contributing](https://github.com/ramnes/awesome-mongodb/blob/master/CONTRIBUTING.md)!

## Table of Contents
 - [Resources](#resources)
   - [Documentation](#documentation)
   - [Articles](#articles)
   - [Books](#books)
   - [Talks](#talks)
   - [Tutorials](#tutorials)
   - [More](#more)
 - [Libraries](#libraries)
   - [C](#c)
   - [C++](#c-1)
   - [C#/.NET](#cnet)
   - [Delphi](#delphi)
   - [Elixir](#elixir)
   - [Erlang](#erlang)
   - [Go](#go)
   - [Haskell](#haskell)
   - [Java](#java)
   - [JavaScript](#javascript)
   - [Julia](#julia)
   - [Lisp](#lisp)
   - [Mathematica](#mathematica)
   - [Perl](#perl)
   - [PHP](#php)
   - [Python](#python)
   - [R](#r)
   - [Ruby](#ruby)
   - [Rust](#rust)
   - [Scala](#scala)
 - [Tools](#tools)
   - [Administration](#administration)
   - [Big Data](#big-data)
   - [Deployment](#deployment)
   - [Desktop](#desktop)
   - [Monitoring](#monitoring)
   - [Shell](#shell)
   - [Web](#web)
 - [Applications](#applications)

## Resources
### Documentation
 - [MongoDB introduction](https://docs.mongodb.org/manual/core/introduction/)
 - [MongoDB documentation](https://docs.mongodb.org/manual/)
 - [MongoDB tutorials](https://docs.mongodb.org/manual/tutorial/)

### Articles
 - [Five Things About Scaling MongoDB (A. Jesse Jiryu Davis, MongoDB Inc.)](https://emptysqua.re/blog/five-things/) - Scale 101
 - [Optimizing MongoDB Compound Indexes (A. Jesse Jiryu Davis, MongoDB Inc.)](http://emptysqua.re/blog/optimizing-mongodb-compound-indexes/) - Everything you need/have to know about indexes
 - [Server Discovery And Monitoring In PyMongo, Perl, And C (A. Jesse Jiryu Davis, MongoDB Inc.) ](https://emptysqua.re/blog/server-discovery-and-monitoring-in-pymongo-perl-and-c/)
 - [Monitoring MongoDB performance metrics (Jean-Mathieu Saponaro, Datadog)](https://www.datadoghq.com/blog/monitoring-mongodb-performance-metrics-wiredtiger/)

### Books
 - [MongoDB Applied Design Patterns (Rick Copeland)](http://shop.oreilly.com/product/0636920027041.do)
 - [The Little MongoDB Book](http://openmymind.net/2011/3/28/The-Little-MongoDB-Book/) - Basic introduction to MongoDB

### Talks
 - [MongoDB Schema Design (Tugdual Grall, MongoDB Inc.)](https://www.youtube.com/watch?v=csKBT8zkRf0) [47']
 - [Partial and Fuzzy Matching with MongoDB (John Page, MongoDB Inc.)](https://www.youtube.com/watch?v=hXbLHInH5qU) [35']
 - [Scaling MongoDB on Amazon Web Services (Michael Saffitz, Apptentive)](https://www.youtube.com/watch?v=bkjVhEQocFI) [50']

### Tutorials
 - [Create a TV Show Tracker Using AngularJS, Node.js, and MongoDB](http://sahatyalkabov.com/create-a-tv-show-tracker-using-angularjs-nodejs-and-mongodb/) - Build a REST API using Mongoose to create and retrieve data from MongoDB
 - [Write a Tumblelog Application with Flask and MongoEngine](https://docs.mongodb.org/ecosystem/tutorial/write-a-tumblelog-application-with-flask-mongoengine/) - Nice Python tutorial hidden into the official Python driver documentation
 - [Kubernetes examples](https://github.com/kubernetes/kubernetes/tree/master/examples/nodesjs-mongodb) - Deployment tutorial of a basic Node.js and MongoDB web stack on [Kubernetes](https://kubernetes.io/docs/whatisk8s/)

### More
 - [MongoDB source code ★12537](https://github.com/mongodb/mongo)
 - [MongoDB University](https://university.mongodb.com/) - Certifications and free online courses
 - [MongoDB Cloud Manager](https://www.mongodb.com/cloud/) - MongoDB Inc. cloud offer
 - [MongoLab](https://mongolab.com/) - Fully managed MongoDB-as-a-Service
 - [Scalegrid](https://scalegrid.io) - Fully managed MongoDB-as-a-Service (with option to bring your own Azure/AWS account)

## Libraries
### C
 - [mongo-c-driver ★362](https://github.com/mongodb/mongo-c-driver) - Official C driver

### C++
 - [mongo-cxx-driver ★414](https://github.com/mongodb/mongo-cxx-driver) - Official C++ driver

### C#/.NET ###
 - [mongo-csharp-driver ★1703](https://github.com/mongodb/mongo-csharp-driver) - Official C# driver
 - [mongo-queue-csharp ★24 ⏳2Y](https://github.com/dominionenterprises/mongo-queue-csharp) - C# message queue backed by MongoDB
 - [MongoDB Messaging ★38](https://github.com/loresoft/MongoDB.Messaging) - Lightweight queue pub/sub processing library
 - [MongoRepository ★195](https://github.com/RobThree/MongoRepository) - Repository abstraction layer on top of the C# driver

### Delphi
 - [TMongoWire ★67](https://github.com/stijnsanders/TMongoWire) - Minimal community Delphi driver

### Elixir
 - [mongodb ★221](https://github.com/ankhers/mongodb) - Community Elixir driver
 - [mongodb_ecto ★241](https://github.com/ankhers/mongodb_ecto) - Adapter for the Ecto database wrapper

### Erlang
 - [mongodb-erlang ★259](https://github.com/comtihon/mongodb-erlang) - Community Erlang driver

### Go
 - [mgo ★1755](https://github.com/go-mgo/mgo) - Community Go driver

### Haskell
 - [mongodb ★77](https://github.com/mongodb-haskell/mongodb) - Community Haskell driver

### Java
 - [Jongo ★471](https://github.com/bguerout/jongo) - Query in Java as in Mongo shell
 - [Hibernate OGM ★236](https://github.com/hibernate/hibernate-ogm) - The power and simplicity of JPA for NoSQL datastores
 - [mongo-java-driver ★1861](https://github.com/mongodb/mongo-java-driver) - Official Java driver
 - [mongo-queue-java ★28](https://github.com/gaillard/mongo-queue-java) - Java message queue backed by MongoDB
 - [mongoFS ★18 ⏳1Y](https://github.com/dbuschman7/mongoFS) - An enhancement of MongoDB's GridFS to allow for more features and capabilities
 - [Mongojack ★183](https://github.com/mongojack/mongojack) - Based on Jackson, allows you to easily handle your mongo objects as POJOs
 - [Morphia ★1210](https://github.com/mongodb/morphia) - Official Java ODM
 - [Morphium ★40](https://github.com/sboesebeck/morphium) - Java ODM and caching layer
 - [Mungbean ★20 ⏳6Y](https://github.com/jannehietamaki/mungbean) - Community driver for languages running on the JVM
 - [Spring Data MongoDB ★755](https://github.com/spring-projects/spring-data-mongodb) - Spring based, object-document support and repositories for MongoDB

### JavaScript
 - [Camo ★373](https://github.com/scottwrobinson/camo) - Class-based ES6 ODM for Mongo-like databases
 - [MEAN.JS ★4378](https://github.com/meanjs/mean) - Full-Stack based on MongoDB, Express, AngularJS, and Node.js
 - [MERN (mern-starter) ★4147](https://github.com/Hashnode/mern-starter) - Full-Stack based on MongoDB, Express, React and Node.js
 - [Mongoose ★13805](https://github.com/Automattic/mongoose) - Node.js asynchronous ODM
 - [mongration](https://github.com/eberhara/mongration) - Node.js migration framework
 - [Moonridge ★55](https://github.com/capaj/Moonridge) - Framework with live querying on top of Mongoose and socket.io
 - [node-mongodb-native ★6188](https://github.com/mongodb/node-mongodb-native) - Official Node.js driver

### Julia
 - [Mongo.jl ★27 ⏳1Y](https://github.com/Lytol/Mongo.jl) - Bindings on MongoDB official C driver

### Lisp
 - [cl-mongo ★110](https://github.com/fons/cl-mongo) - Community Common Lisp interface
 - [mongo-cl-driver ★29 ⏳2Y](https://github.com/archimag/mongo-cl-driver) Community Common Lisp driver
 - [mongo-el ★40 ⏳2Y](https://github.com/m2ym/mongo-el) - Community Emacs Lisp driver

### Mathematica
 - [MongoDBLink ★12](https://github.com/zbjornson/MongoDBLink) - Community Mathematica driver

### Perl
 - [mongo-perl-driver ★188](https://github.com/mongodb/mongo-perl-driver) - Official Perl driver

### PHP
 - [Doctrine MongoDB ★299](https://github.com/doctrine/mongodb) - Wrapper around the native PHP Mongo PECL extension to provide additional functionality
 - [eloquent-mongodb-repository](https://github.com/PHPRepository/php-eloquent-mongodb-repository) - Repository implementation built on top of laravel-mongodb
 - [laravel-mongodb ★2941](https://github.com/jenssegers/laravel-mongodb) - Eloquent model and query builder for Laravel
 - [mongodb-repository](https://github.com/PHPRepository/php-mongodb-repository) - Repository implementation
 - [pecl/mongodb ★423](https://github.com/mongodb/mongo-php-driver) - Official PHP driver

### Python
 - [Flask-PyMongo ★360](https://github.com/dcrosta/flask-pymongo) - PyMongo support for Flask applications
 - [MongoEngine ★1947](https://github.com/MongoEngine/mongoengine) - Python ODM on top of PyMongo
 - [MongoLog ★102 ⏳4Y](https://github.com/puentesarrin/mongodb-log) - MongoDB logging handler
 - [Mongo-Thingy ★7](https://github.com/numberly/mongo-thingy) - The most Pythonic and friendly-yet-powerful way to use MongoDB
 - [Motor ★862](https://github.com/mongodb/motor) - Non-blocking Python driver for Tornado applications
 - [PyMongo ★2140](https://github.com/mongodb/mongo-python-driver) - Official (and recommended) Python driver
 - [minimongo ★296](https://github.com/slacy/minimongo) - A lightweight, schemaless, Pythonic Object-Oriented interface
 - [scrapy-mongodb ★228](https://github.com/sebdah/scrapy-mongodb) - MongoDB pipeline for Scrapy
 - [μMongo ★59](https://github.com/Scille/umongo) - Driver-independent (async/sync) ODM based on marshmallow

### R
 - [mongolite](https://github.com/jeroenooms/mongolite) - Fast and Simple MongoDB Client for R

### Ruby
 - [mongo-ruby-driver ★1314](https://github.com/mongodb/mongo-ruby-driver) - Official Ruby driver
 - [Mongoid ★3551](https://github.com/mongodb/mongoid) - Ruby ODM framework

### Rust
 - [mongo-rust-driver-prototype ★215](https://github.com/mongodb-labs/mongo-rust-driver-prototype) - Prototype driver written for Rust 1.x and MongoDB 3.0.x

### Scala
 - [mongo-scala-driver ★172](https://github.com/mongodb/mongo-scala-driver) - Official Scala driver
 - [ReactiveMongo ★735](https://github.com/ReactiveMongo/ReactiveMongo) - Non-blocking Scala driver
 - [Spark-MongoDB ★289 ⏳1Y](https://github.com/Stratio/Spark-MongoDB) - Read/write data with Spark SQL

## Tools
### Administration
 - [mongo_fdw ★117](https://github.com/EnterpriseDB/mongo_fdw) - PostgreSQL foreign data wrapper for MongoDB
 - [mongoctl ★165](https://github.com/mongolab/mongoctl) - Manage MongoDB servers and replica sets using JSON configurations
 - [MongoDB Smasher ★19 ⏳1Y](https://github.com/duckie/mongo_smasher) - Generate randomized datasets and benchmark your MongoDB setup
 - [mongodb-tools ★244 ⏳1Y](https://github.com/jwilder/mongodb-tools) - Three neat Python scripts to work with collections and indexes
 - [Mongoeye ★18](https://github.com/mongoeye/mongoeye) - Schema and data analyzer: explore data in your collections
 - [Mongolastic ★60](https://github.com/ozlerhakan/mongolastic) - A dataset migration tool from MongoDB to Elasticsearch and vice versa
 - [MongoMultiMaster ★54 ⏳5Y](https://github.com/rick446/mmm) - Multi-Master MongoDB replication
 - [MoSQL ★1396](https://github.com/stripe/mosql) - MongoDB to PostgreSQL streaming replication
 - [mtools ★991](https://github.com/rueckstiess/mtools) - Collection of scripts to set up MongoDB test environments and parse and visualize MongoDB log files
 - [nginx-gridfs ★762 ⏳4Y](https://github.com/mdirolf/nginx-gridfs) - Nginx module for serving files from MongoDB's GridFS
 - [nginx-mongodb-rest ★31 ⏳6Y](https://github.com/minhajuddin/nginx-mongodb-rest) - MongoDB REST client written as an Nginx module
 - [Variety ★1052](https://github.com/variety/variety) - Schema analyzer: see what fields are in your collection and what's their content

### Big Data
 - [mongo-hadoop ★1297](https://github.com/mongodb/mongo-hadoop) - MongoDB connector for Hadoop

### Deployment
 - [ansible-role-mongodb ★114](https://github.com/UnderGreen/ansible-role-mongodb) - Ansible role
 - [chef-mongodb ★382](https://github.com/edelight/chef-mongodb) - Chef cookbook
 - [Dockerfile ★224](https://github.com/dockerfile/mongodb)
 - [Helm Chart](https://github.com/kubernetes/charts/tree/master/stable/mongodb) - Bootstraps a MongoDB deployment on a [Kubernetes](https://kubernetes.io/docs/whatisk8s/) cluster using the [Helm ★2946](https://github.com/kubernetes/helm) package manager.
 - [puppetlabs-mongodb](https://github.com/puppetlabs/puppetlabs-mongodb) - Puppet module

### Desktop
 - [MongoChef](http://3t.io/mongochef) - Cross-platform MongoDB manager, stable and powerful
 - [MongoBooster](http://www.mongobooster.com) - Feature-rich but easy-to-use cross-platform MongoDB manager
 - [MongoHub ★2218 ⏳2Y](https://github.com/jeromelebel/MongoHub-Mac) - Mac native client
 - [Mongotron](http://mongotron.io/) - Cross-platform, open-source MongoDB client built with Electron
 - [Robomongo](https://github.com/paralect/robomongo) - Native and cross-platform MongoDB manager

### Monitoring
 - [check_mongodb ★15 ⏳1Y](https://github.com/dalenys/check_mongodb) - Nagios plugin (in Bash)
 - [Datadog](https://www.datadoghq.com/blog/monitor-mongodb-performance-with-datadog?ref=awesome) - SaaS-based MongoDB monitoring
 - [Mongoop ★32 ⏳1Y](https://github.com/Lujeni/mongoop) - Long operations monitoring and alerting
 - [Motop ★60 ⏳2Y](https://github.com/tart/motop) - MongoDB top clone
 - [mtop ★50 ⏳2Y](https://github.com/beaufour/mtop) - Another top clone
 - [mongo-munin ★148 ⏳5Y](https://github.com/erh/mongo-munin) - Collection of Munin plugins
 - [mongomon ★25 ⏳3Y](https://github.com/pcdummy/mongomon) - More Munin plugins
 - [nagios-plugin-mongodb ★320](https://github.com/mzupan/nagios-plugin-mongodb) - Nagios plugin (in Python)

### Shell
 - [mongo-hacker ★1312](https://github.com/TylerBrock/mongo-hacker) - MongoDB shell enhancements

### Web
 - [adminMongo ★1092](https://github.com/mrvautin/adminMongo) - Web-based user interface to handle connections and databases needs
 - [Compass](https://www.mongodb.com/products/compass) - MongoDB Inc. commercial online GUI and data-visualization platform
 - [HumongouS.io](https://www.humongous.io) - Easy online GUI and data-visualization dashboards
 - [mongo-express ★2387](https://github.com/mongo-express/mongo-express) - Web-based admin interface written with Node.js, Express and Bootstrap3
 - [mongoadmin ★260 ⏳5Y](https://github.com/thomasst/mongoadmin) - Admin interface for MongoDB built using Django and Bootstrap
 - [mongri ★64 ⏳1Y](https://github.com/dongri/mongri) - Web-based user interface for MongoDB (written in JavaScript)
 - [Rockmongo ★783](https://github.com/iwind/rockmongo) - PHPMyAdmin for MongoDB, sort of

## Applications
 - [Leanote ★6207](https://github.com/leanote/leanote) - Evernote clone built with Go and MongoDB
 - [Quokka ★1732](https://github.com/quokkaproject/quokka) - Python CMS built on top of Flask and MongoDB
 - [uptime ★3356](https://github.com/fzaninotto/uptime) - Remote monitoring application using Node.js, MongoDB, and Bootstrap

## License
[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Guillaume Gelin](https://github.com/ramnes) has waived all copyright and related or neighboring rights to this work.
---
<p align="center">
	This list is a copy of <a href="https://github.com/ramnes/awesome-mongodb">ramnes/awesome-mongodb</a> with ranks
</p>
