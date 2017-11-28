---
layout: default
title: Awesome Rank for manuzhang/awesome-streaming
---

<p align="center">
	This list is a copy of <a href="https://github.com/manuzhang/awesome-streaming">manuzhang/awesome-streaming</a> with ranks
</p>
---
## Awesome Streaming  [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg) ★69735](https://github.com/sindresorhus/awesome) [![Build Status](https://travis-ci.org/manuzhang/awesome-streaming.svg?branch=master)](https://travis-ci.org/manuzhang/awesome-streaming)

A curated list of awesome [streaming (stream processing)](http://radar.oreilly.com/2015/08/the-world-beyond-batch-streaming-101.html) frameworks, applications, readings and other resources. Inspired by [other awesome projects ★69735](https://github.com/sindresorhus/awesome). 

## Table of Contents

- [Streaming Engine](#streaming-engine)
- [Streaming Library](#streaming-library)
- [Streaming Application](#streaming-application)
- [IoT](#iot)
- [DSL](#dsl)
- [Data Pipeline](#data-pipeline)
- [Online Machine Learning](#online-machine-learning)
- [Streaming SQL](#streaming-sql)
- [Toolkit](#toolkit)
- [Benchmark](#benchmark)
- [Readings](#readings)

### Streaming Engine

* [Apache Apex](https://github.com/apache/incubator-apex-core) [Java] - unified platform for big data stream and batch processing.
* [Apache Flink Streaming](http://ci.apache.org/projects/flink/flink-docs-release-0.9/apis/streaming_guide.html) [Java] - system for high-throughput, low-latency data stream processing that supports stateful computation, data-driven windowing semantics and iterative stream processing.
* [Apache Gearpump](http://gearpump.apache.org) [Scala] - lightweight real-time distributed streaming engine built on Akka.
* [Apache Ignite Streaming](https://ignite.apache.org/features/streaming.html) [Java] - Ignite streaming allows to process continuous never-ending streams of data in scalable and fault-tolerant fashion. 
* [Apache Samza](http://samza.apache.org/) [Scala/Java] - distributed stream processing framework that build on Kafka(messaging, storage) and YARN(fault tolerance, processor isolation, security and resource management).
* [Apache Spark Streaming](https://spark.apache.org/streaming/) [Scala] - makes it easy to build scalable fault-tolerant streaming applications.
* [Apache Storm](https://storm.apache.org/) [Clojure/Java] - distributed real-time computation system. Storm is to stream processing what Hadoop is to batch processing. 
* [Hazelcast Jet ★145](https://github.com/hazelcast/hazelcast-jet) [Java] - A general purpose distributed data processing engine, built on top of Hazelcast.
* [IBM Streams](https://www.ibm.com/analytics/us/en/technology/stream-computing/) [Python/Java/Scala] - platform for distributed processing and real-time analytics. Integrates with many of the popular technologies in the Big Data ecosystem (Kafka, HDFS, Spark, etc.)
* [heron](http://heronstreaming.io/) - Twitter's real-time analytics platform that is fully API-compatible with Storm. Storm has been replaced by Heron at Twitter.
* [mantis](http://www.slideshare.net/g9yuayon/qcon-talk-on-netflix-mantis-a-stream-processing-system) - Netflix's event stream processing system.
* [millwheel](http://research.google.com/pubs/pub41378.html) - framework for building low-latency data-processing applications that is widely used at Google.
* [mupd8(muppet) ★125 ⏳2Y](https://github.com/walmartlabs/mupd8) [Scala/Java] - mapReduce-style framework for processing fast/streaming data.
* [s4](http://incubator.apache.org/s4/) [Java] - general-purpose, distributed, scalable, fault-tolerant, pluggable platform that allows programmers to easily develop applications for processing continuous unbounded streams of data.
* [SPQR ★26 ⏳1Y](https://github.com/ottogroup/SPQR) [Java] - dynamic framework for processing high volumn data streams through pipelines.
* [tigon ★244](https://github.com/caskdata/tigon) [C++/Java] - high throughput real-time streaming processing framework built on Hadoop and HBase.
* [hailstorm ★76 ⏳3Y](https://github.com/hailstorm-hs/hailstorm) [Haskell] - distributed stream processing with exactly-once semantics based on Storm.
* [Teknek ★5 ⏳1Y](https://github.com/edwardcapriolo/teknek-core) [Java] - Simple elegant stream processing with interactive prototying shell SOL (Stream Operator Language)
* [concord](http://concord.io/) [C++] - a distributed stream processing framework built in C++ on top of Apache Mesos, designed for high performance data processing jobs that require flexibility & control.
* [StreamBox](https://engineering.purdue.edu/~xzl/xsel/p/streambox/) - a modern stream processing engine which can handle out-of-order streaming data and achieve high throughput with low latency.
* [Wallaroo](http://www.wallaroolabs.com/community) [Python] - The ultrafast and elastic data processing engine. Big or fast data - no fuss, no Java needed.

### Streaming Library
* [IBM Streams](https://www.ibm.com/analytics/us/en/technology/stream-computing/) [Python/Java/Scala] - platform for distributed processing and real-time analytics. Provides toolkits for advanced analytics like geospatial, time series, etc. out of the box.
* [Apache Kafka Streams](http://kafka.apache.org/documentation#streams) [Java] - lightweight stream processing library included in Apache Kafka (since 0.10 version).
* [Akka Streams](http://doc.akka.io/docs/akka/2.4.16/scala/stream/stream-introduction.html) [Scala] - stream processing library on Akka Actors. 
* [Swave](http://swave.cc/) [Scala] - A lightweight Reactive Streams Infrastructure Toolkit for Scala.
* [FS2(prev. 'Scalaz-Stream') ★923](https://github.com/functional-streams-for-scala/fs2) [Scala] - Compositional, streaming I/O library for Scala.
* [monix ★911](https://github.com/monix/monix) [Scala] - high-performance Scala / Scala.js library for composing asynchronous and event-based programs.

### Streaming Application

* [straw ★76 ⏳1Y](https://github.com/rwalk/straw) [Python/Java] - A platform for real-time streaming search.
* [storm-crawler](http://stormcrawler.net/) [Java] - Web crawler SDK based on Apache Storm.

### IoT

* [sensorbee](http://sensorbee.io/) [Go] - lightweight stream processing engine for IoT.
* [Apache Edgent](http://edgent.apache.org/) [Java] - a programming model and runtime that enables continuous streaming analytics on gateways and edge devices which can work with centralized systems to provide efficient and timely analytics across the whole IoT ecosystem: from the center to the edge, opens sourced by IBM.

### DSL
* [summingbird ★1900](https://github.com/twitter/summingbird) [Scala] - library that lets you write MapReduce programs that look like native Scala or Java collection transformations and execute them on a number of well-known distributed MapReduce platforms, including Storm and Scalding.
* [coast ★60 ⏳1Y](https://github.com/bkirwi/coast) [Scala] - a DSL that builds DAGs on top of Samza and provides exactly-once semantics.
* [Apache Beam](https://github.com/apache/incubator-beam) [Java] - unified model and set of language-specific SDKs for defining and executing data processing workflows, and also data ingestion and integration flows, supporting Enterprise Integration Patterns (EIPs) and Domain Specific Languages (DSLs), open sourced by Google.
* [Esper ★324](https://github.com/espertechinc/esper) [Java] - component for complex event processing (CEP) and event series analysis.
* [Streamparse ★1216](https://github.com/Parsely/streamparse) [Python] - lets you run Python code against real-time streams of data via Apache Storm.

### Data Pipeline

* [Apache Kafka ★6693](https://github.com/apache/kafka) [Scala/Java] - distributed, partitioned, replicated commit log service, which provides the functionality of a messaging system, but with a unique design.
* [Apache Pulsar ★1401](https://github.com/apache/incubator-pulsar) [Java] - distributed pub-sub messaging platform with a very flexible messaging model and an intuitive client API.
* [metaq ★1054](https://github.com/killme2008/Metamorphosis) [Java] - Taobao's high available, high performance distributed messaging system
* [nsq](https://github.com/bitly/nsq) [Go] - realtime distributed messaging platform designed to operate at scale, handling billions of messages per day.
* [NATS streaming ★633](https://github.com/nats-io/nats-streaming-server) [Go] - fast disk-backed messaging solution
* [camus ★726 ⏳2Y](https://github.com/linkedin/camus) [Java] - Linkedin's Kafka -> HDFS pipeline.
* [databus ★1711](https://github.com/linkedin/databus) [Java] - Linkedin's source-agnostic distributed change data capture system.
* [flume ★1140](https://github.com/apache/flume) [Java] - distributed, reliable, and available service for efficiently collecting, aggregating, and moving large amounts of log data.
* [Redis Streams](http://antirez.com/news/114) - Redis implementation of a unified log structure
* [suro ★640 ⏳1Y](https://github.com/Netflix/suro) [Java] - data pipeline service for collecting, aggregating, and dispatching large volume of application events including log data.
* [StreamSets Data Collector ★365](https://github.com/streamsets/datacollector) [Java] - continuous big data ingestion infrastructure that reads from and writes to a large number of end-points, including S3, JDBC, Hadoop, Kafka, Cassandra and many others.

### Online Machine Learning 

* [streamDM ★291](https://github.com/huawei-noah/streamDM) [Scala] - mining Big Data streams using Spark Streaming from Huawei.
* [jubatus](http://jubat.us/en/) [C++] - distributed processing framework and streaming machine learning library.
* [Apache Samoa](https://github.com/yahoo/samoa) [Java] - distributed streaming machine learning (ML) framework that contains a programing abstraction for distributed streaming ML algorithms.
* [trident-ml ★374 ⏳2Y](https://github.com/pmerienne/trident-ml) [Java] - realtime online machine learning library based on Trident.
* [StormCV ★112](https://github.com/sensorstorm/StormCV) [Java] - enables the use of Apache Storm for video processing by adding computer vision (CV) specific operations and data model.
* [DataSketches ★470](https://github.com/DataSketches/sketches-core) [Java] - sketches library from Yahoo!.
* [StreamingBandit](https://github.com/MKaptein/streamingbandit) [Python] - Provides a webserver to quickly setup and evaluate possible solutions to contextual multi-armed bandit (cMAB) problems.

### Streaming SQL

* [pipelinedb ★1472](https://github.com/pipelinedb/pipelinedb) [C] - An open-source relational database that runs SQL queries continuously on streams, incrementally storing results in tables.
* [squall ★261](https://github.com/epfldata/squall) [Java] - Squall executes SQL queries on top of Storm for doing online processing.
* [StreamCQL ★332](https://github.com/HuaweiBigData/StreamCQL) [Java] - Continuous Query Language on RealTime Computation System.
* [KSQL ★1048](https://github.com/confluentinc/ksql) [Java] - a Streaming SQL Engine for Apache Kafka.


### Benchmark

* [storm-benchmark ★36 ⏳1Y](https://github.com/intel-hadoop/storm-benchmark) [Java] - a set of benchmarks to test Storm performance.
* [storm-perf-test ★70 ⏳1Y](https://github.com/yahoo/storm-perf-test) [Java] - a simple storm performance/stress test.
* [streaming-benchmarks ★312](https://github.com/yahoo/streaming-benchmarks) [Java] - Benchmarks for Low Latency (Streaming) solutions including Apache Storm, Apache Spark, Apache Flink, etc.
* [flotilla ★174 ⏳1Y](https://github.com/tylertreat/Flotilla) [Go] - Automated message queue orchestration for scaled-up benchmarking.




### Toolkit

* [akka](http://akka.io/) [Scala] - toolkit and runtime for building highly concurrent, distributed, and resilient message-driven application on the JVM.
* [pulsar](http://quantmind.github.io/pulsar/index.html#) [Python] - Actor based event driven concurrent framework for Python.
* [aeron ★3036](https://github.com/real-logic/Aeron) [Java/C++] - efficient reliable unicast and multicast message transport.
* [StreamFlow ★222 ⏳1Y](https://github.com/lmco/streamflow) [Java] - stream processing tool designed to help build and monitor processing workflows.
* [samza-luwak ★86 ⏳3Y](https://github.com/romseygeek/samza-luwak) [Java] - uses Luwak, a stored-query engine built on Lucene, to implement full-text search on streams.
* [Turbine ★590](https://github.com/Netflix/Turbine) [Java] - tool for aggregating streams of Server-Sent Event (SSE) JSON data into a single stream.

### Readings

1. [In-Stream Big Data Processing](https://highlyscalable.wordpress.com/2013/08/20/in-stream-big-data-processing/)
2. [The world beyond batch: Streaming 101](http://radar.oreilly.com/2015/08/the-world-beyond-batch-streaming-101.html) by Tyler Akidau. 
3. [Real Time Analytics: Algorithms and Systems (VLDB 2015)](http://www.vldb.org/pvldb/vol8/p2040-Kejariwal.pdf)


## License 

![Creative Commons License](https://i.creativecommons.org/l/by-sa/4.0/80x15.png) 

Licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/)
---
<p align="center">
	This list is a copy of <a href="https://github.com/manuzhang/awesome-streaming">manuzhang/awesome-streaming</a> with ranks
</p>
