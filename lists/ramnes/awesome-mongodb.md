<h1 align="center">
Ranked awesome lists, all in one place
</h1>
<p align="center">
	This list is a copy of <a href="ramnes/awesome-mongodb">ramnes/awesome-mongodb</a> with ranks
</p>
---
![Awesome MongoDB](https://github.com/ramnes/awesome-mongodb/blob/master/logo.png)

# Awesome MongoDB [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg) ★59088](sindresorhus/awesome)

> A curated list of awesome MongoDB resources, libraries, tools and applications

Inspired by the [awesome ★59088](sindresorhus/awesome) list thing. Feel free to improve this list by [contributing](https://github.com/ramnes/awesome-mongodb/blob/master/CONTRIBUTING.md)!

## Table of Contents
 - [Resources](#resources)
   - [Documentation](#documentation)
   - [Articles](#articles)
   - [Talks](#talks)
   - [Tutorials](#tutorials)
   - [More](#more)
 - [Libraries](#libraries)
   - [C](#c)
   - [C++](#c-1)
   - [C#/.NET](#cnet)
   - [Delphi](#delphi)
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

### Talks
 - [MongoDB Schema Design (Tugdual Grall, MongoDB Inc.)](https://www.youtube.com/watch?v=csKBT8zkRf0) [47']
 - [Partial and Fuzzy Matching with MongoDB (John Page, MongoDB Inc.)](https://www.youtube.com/watch?v=hXbLHInH5qU) [35']
 - [Scaling MongoDB on Amazon Web Services (Michael Saffitz, Apptentive)](https://www.youtube.com/watch?v=bkjVhEQocFI) [50']

### Tutorials
 - [Create a TV Show Tracker Using AngularJS, Node.js, and MongoDB](http://sahatyalkabov.com/create-a-tv-show-tracker-using-angularjs-nodejs-and-mongodb/) - Build a REST API using Mongoose to create and retrieve data from MongoDB
 - [Write a Tumblelog Application with Flask and MongoEngine](https://docs.mongodb.org/ecosystem/tutorial/write-a-tumblelog-application-with-flask-mongoengine/) - Nice Python tutorial hidden into the official Python driver documentation
 - [Kubernetes examples](https://github.com/kubernetes/kubernetes/tree/master/examples/nodesjs-mongodb) - Deployment tutorial of a basic Node.js and MongoDB web stack on [Kubernetes](https://kubernetes.io/docs/whatisk8s/)

### More
 - [MongoDB source code ★11572](mongodb/mongo)
 - [MongoDB University](https://university.mongodb.com/) - Certifications and free online courses
 - [MongoDB Cloud Manager](https://www.mongodb.com/cloud/) - MongoDB Inc. cloud offer
 - [MongoLab](https://mongolab.com/) - Fully managed MongoDB-as-a-Service
 - [Scalegrid](https://scalegrid.io) - Fully managed MongoDB-as-a-Service (with option to bring your own Azure/AWS account)

## Libraries
### C
 - [mongo-c-driver ★330](mongodb/mongo-c-driver) - Official C driver

### C++
 - [mongo-cxx-driver ★371](mongodb/mongo-cxx-driver) - Official C++ driver

### C#/.NET ###
 - [mongo-csharp-driver ★1583](mongodb/mongo-csharp-driver) - Official C# driver
 - [mongo-queue-csharp ★23 ⏳1Y](dominionenterprises/mongo-queue-csharp) - C# message queue backed by MongoDB
 - [MongoDB Messaging ★35](loresoft/MongoDB.Messaging) - Lightweight queue pub/sub processing library
 - [MongoRepository ★168](RobThree/MongoRepository) - Repository abstraction layer on top of the C# driver

### Delphi
 - [TMongoWire ★62](stijnsanders/TMongoWire) - Minimal community Delphi driver

### Erlang
 - [mongodb-erlang ★243](comtihon/mongodb-erlang) - Community Erlang driver

### Go
 - [mgo ★1421](go-mgo/mgo) - Community Go driver

### Haskell
 - [mongodb ★64](mongodb-haskell/mongodb) - Community Haskell driver

### Java
 - [Jongo ★457](bguerout/jongo) - Query in Java as in Mongo shell
 - [Hibernate OGM ★225](hibernate/hibernate-ogm) - The power and simplicity of JPA for NoSQL datastores
 - [mongo-java-driver ★1764](mongodb/mongo-java-driver) - Official Java driver
 - [mongo-queue-java ★25 ⏳3Y](gaillard/mongo-queue-java) - Java message queue backed by MongoDB
 - [mongoFS ★16 ⏳1Y](dbuschman7/mongoFS) - An enhancement of MongoDB's GridFS to allow for more features and capabilities
 - [Mongojack ★171](mongojack/mongojack) - Based on Jackson, allows you to easily handle your mongo objects as POJOs
 - [Morphia ★1136](mongodb/morphia) - Official Java ODM
 - [Morphium ★38](sboesebeck/morphium) - Java ODM and caching layer
 - [Mungbean ★20 ⏳5Y](jannehietamaki/mungbean) - Community driver for languages running on the JVM
 - [Spring Data MongoDB ★689](spring-projects/spring-data-mongodb) - Spring based, object-document support and repositories for MongoDB

### JavaScript
 - [Camo ★329](scottwrobinson/camo) - Class-based ES6 ODM for Mongo-like databases
 - [MEAN.JS ★4186](meanjs/mean) - Full-Stack based on MongoDB, Express, AngularJS, and Node.js
 - [MERN (mern-starter) ★3746](Hashnode/mern-starter) - Full-Stack based on MongoDB, Express, React and Node.js
 - [Mongoose ★12389](Automattic/mongoose) - Node.js asynchronous ODM
 - [mongration](https://github.com/eberhara/mongration) - Node.js migration framework
 - [Moonridge ★55](capaj/Moonridge) - Framework with live querying on top of Mongoose and socket.io
 - [node-mongodb-native ★5719](mongodb/node-mongodb-native) - Official Node.js driver

### Julia
 - [Mongo.jl ★27 ⏳1Y](Lytol/Mongo.jl) - Bindings on MongoDB official C driver

### Lisp
 - [cl-mongo ★109 ⏳1Y](fons/cl-mongo) - Community Common Lisp interface
 - [mongo-cl-driver ★29 ⏳2Y](archimag/mongo-cl-driver) Community Common Lisp driver
 - [mongo-el ★39 ⏳2Y](m2ym/mongo-el) - Community Emacs Lisp driver

### Mathematica
 - [MongoDBLink ★12](zbjornson/MongoDBLink) - Community Mathematica driver

### Perl
 - [mongo-perl-driver ★188](mongodb/mongo-perl-driver) - Official Perl driver

### PHP
 - [Doctrine MongoDB ★285](doctrine/mongodb) - Wrapper around the native PHP Mongo PECL extension to provide additional functionality
 - [eloquent-mongodb-repository](https://github.com/PHPRepository/php-eloquent-mongodb-repository) - Repository implementation built on top of laravel-mongodb
 - [laravel-mongodb ★2557](jenssegers/laravel-mongodb) - Eloquent model and query builder for Laravel
 - [mongodb-repository](https://github.com/PHPRepository/php-mongodb-repository) - Repository implementation
 - [pecl/mongodb ★370](mongodb/mongo-php-driver) - Official PHP driver

### Python
 - [Flask-PyMongo ★321](dcrosta/flask-pymongo) - PyMongo support for Flask applications
 - [MongoEngine ★1719](MongoEngine/mongoengine) - Python ODM on top of PyMongo
 - [MongoLog ★95 ⏳4Y](puentesarrin/mongodb-log) - MongoDB logging handler
 - [Mongo-Thingy ★4](numberly/mongo-thingy) - The most Pythonic and friendly-yet-powerful way to use MongoDB
 - [Motor ★789](mongodb/motor) - Non-blocking Python driver for Tornado applications
 - [PyMongo ★2005](mongodb/mongo-python-driver) - Official (and recommended) Python driver
 - [minimongo ★291](slacy/minimongo) - A lightweight, schemaless, Pythonic Object-Oriented interface
 - [scrapy-mongodb ★211](sebdah/scrapy-mongodb) - MongoDB pipeline for Scrapy
 - [μMongo ★46](Scille/umongo) - Driver-independent (async/sync) ODM based on marshmallow

### R
 - [mongolite](https://github.com/jeroenooms/mongolite) - Fast and Simple MongoDB Client for R

### Ruby
 - [mongo-ruby-driver ★1297](mongodb/mongo-ruby-driver) - Official Ruby driver
 - [Mongoid ★3496](mongodb/mongoid) - Ruby ODM framework

### Rust
 - [mongo-rust-driver-prototype ★177](mongodb-labs/mongo-rust-driver-prototype) - Prototype driver written for Rust 1.x and MongoDB 3.0.x

### Scala
 - [mongo-scala-driver ★157](mongodb/mongo-scala-driver) - Official Scala driver
 - [ReactiveMongo ★711](ReactiveMongo/ReactiveMongo) - Non-blocking Scala driver
 - [Spark-MongoDB ★276](Stratio/Spark-MongoDB) - Read/write data with Spark SQL

## Tools
### Administration
 - [mongo_fdw ★100](EnterpriseDB/mongo_fdw) - PostgreSQL foreign data wrapper for MongoDB
 - [mongoctl ★158](mongolab/mongoctl) - Manage MongoDB servers and replica sets using JSON configurations
 - [MongoDB Smasher ★18 ⏳1Y](duckie/mongo_smasher) - Generate randomized datasets and benchmark your MongoDB setup
 - [mongodb-tools ★233 ⏳1Y](jwilder/mongodb-tools) - Three neat Python scripts to work with collections and indexes
 - [Mongolastic ★53](ozlerhakan/mongolastic) - A dataset migration tool from MongoDB to Elasticsearch and vice versa
 - [MongoMultiMaster ★52 ⏳4Y](rick446/mmm) - Multi-Master MongoDB replication
 - [MoSQL ★1367](stripe/mosql) - MongoDB to PostgreSQL streaming replication
 - [mtools ★885](rueckstiess/mtools) - Collection of scripts to set up MongoDB test environments and parse and visualize MongoDB log files
 - [nginx-gridfs ★744 ⏳3Y](mdirolf/nginx-gridfs) - Nginx module for serving files from MongoDB's GridFS
 - [nginx-mongodb-rest ★31 ⏳6Y](minhajuddin/nginx-mongodb-rest) - MongoDB REST client written as an Nginx module
 - [Variety ★955](variety/variety) - Schema analyzer: see what fields are in your collection and what's their content

### Big Data
 - [mongo-hadoop ★1246](mongodb/mongo-hadoop) - MongoDB connector for Hadoop

### Deployment
 - [ansible-role-mongodb ★102](UnderGreen/ansible-role-mongodb) - Ansible role
 - [chef-mongodb ★380](edelight/chef-mongodb) - Chef cookbook
 - [Dockerfile ★199](dockerfile/mongodb)
 - [Helm Chart](https://github.com/kubernetes/charts/tree/master/stable/mongodb) - Bootstraps a MongoDB deployment on a [Kubernetes](https://kubernetes.io/docs/whatisk8s/) cluster using the [Helm ★1706](kubernetes/helm) package manager.
 - [puppetlabs-mongodb ★81](puppetlabs/puppetlabs-mongodb) - Puppet module

### Desktop
 - [MongoChef](http://3t.io/mongochef) - Cross-platform MongoDB manager, stable and powerful
 - [MongoBooster](http://www.mongobooster.com) - Feature-rich but easy-to-use cross-platform MongoDB manager
 - [MongoHub ★2172 ⏳1Y](jeromelebel/MongoHub-Mac) - Mac native client
 - [Robomongo](https://github.com/paralect/robomongo) - Native and cross-platform MongoDB manager

### Monitoring
 - [check_mongodb ★15](dalenys/check_mongodb) - Nagios plugin (in Bash)
 - [Datadog](https://www.datadoghq.com/blog/monitor-mongodb-performance-with-datadog?ref=awesome) - SaaS-based MongoDB monitoring
 - [Mongoop ★30](Lujeni/mongoop) - Long operations monitoring and alerting
 - [Motop ★57 ⏳1Y](tart/motop) - MongoDB top clone
 - [mtop ★50 ⏳2Y](beaufour/mtop) - Another top clone
 - [mongo-munin ★149 ⏳5Y](erh/mongo-munin) - Collection of Munin plugins
 - [mongomon ★24 ⏳3Y](pcdummy/mongomon) - More Munin plugins
 - [nagios-plugin-mongodb ★311](mzupan/nagios-plugin-mongodb) - Nagios plugin (in Python)

### Shell
 - [mongo-hacker ★1236](TylerBrock/mongo-hacker) - MongoDB shell enhancements

### Web
 - [adminMongo ★841](mrvautin/adminMongo) - Web-based user interface to handle connections and databases needs
 - [Compass](https://www.mongodb.com/products/compass) - MongoDB Inc. commercial online GUI and data-visualization platform
 - [HumongouS.io](https://www.humongous.io) - Easy online GUI and data-visualization dashboards
 - [mongo-express ★2132](mongo-express/mongo-express) - Web-based admin interface written with Node.js, Express and Bootstrap3
 - [mongoadmin ★260 ⏳5Y](thomasst/mongoadmin) - Admin interface for MongoDB built using Django and Bootstrap
 - [mongri ★65](dongri/mongri) - Web-based user interface for MongoDB (written in JavaScript)
 - [Rockmongo ★749](iwind/rockmongo) - PHPMyAdmin for MongoDB, sort of

## Applications
 - [Leanote ★5378](leanote/leanote) - Evernote clone built with Go and MongoDB
 - [Quokka ★1636](quokkaproject/quokka) - Python CMS built on top of Flask and MongoDB
 - [uptime ★3287](fzaninotto/uptime) - Remote monitoring application using Node.js, MongoDB, and Bootstrap

## License
[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Guillaume Gelin](https://github.com/ramnes) has waived all copyright and related or neighboring rights to this work.
---
<p align="center">
	This list is a copy of <a href="ramnes/awesome-mongodb">ramnes/awesome-mongodb</a> with ranks
</p>
