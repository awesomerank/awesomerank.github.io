---
layout: default
title: Awesome Rank for drobakowski/awesome-erlang
---

<p align="center">
	This list is a copy of <a href="https://github.com/drobakowski/awesome-erlang">drobakowski/awesome-erlang</a> with ranks
</p>
---
# Awesome Erlang [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![Analytics](https://ga-beacon.appspot.com/UA-82766782-1/awesome-erlang?flat&useReferer) ★773](https://github.com/drobakowski/awesome-erlang)
A curated list of amazingly awesome Erlang libraries, resources and shiny thing inspired by [awesome-elixir ★7409](https://github.com/h4cc/awesome-elixir).

- [Awesome Erlang](#awesome-Erlang)
    - [Package Management](#package-management)
    - [Release Management](#release-management)
    - [Configuration Management](#configuration-management)
    - [Codebase Maintenance](#codebase-maintenance)
    - [Web Frameworks](#web-frameworks)
    - [Web Framework Components](#web-framework-components)
    - [HTTP](#http)
    - [Testing](#testing)
    - [Logging](#logging)
    - [Monitoring](#monitoring)
    - [Deployment](#deployment)
    - [Distributed Systems](#distributed-systems)
    - [Code Analysis](#code-analysis)
    - [Build Tools](#build-tools)
    - [Geolocation](#geolocation)
    - [Debugging](#debugging)
    - [Actors](#actors)
    - [Date and Time](#date-and-time)
    - [ORM and Datamapping](#orm-and-datamapping)
    - [Queue](#queue)
    - [Authentication](#authentication)
    - [Text and Numbers](#text-and-numbers)
    - [REST and API](#rest-and-api)
    - [Caching](#caching)
    - [Third Party APIs](#third-party-apis)
    - [Networking](#networking)
    - [Internet of Things](#internet-of-things)
    - [Algorithms and Datastructures](#algorithms-and-datastructures)
    - [Translations and Internationalizations](#translations-and-internationalizations)
    - [Miscellaneous](#miscellaneous)
- [Resources](#resources)
    - [Websites](#websites)
    - [Books](#books)
    - [Web Reading](#web-reading)
    - [Erlang Reading](#Erlang-reading)
    - [Screencasts](#screencasts)
- [Other Awesome Lists](#other-awesome-lists)
- [Contributing](#contributing)

## Package Management
*Libraries and tools for package and dependency management.*

* [hex.pm](https://hex.pm/) - A package manager for the Erlang ecosystem.

## Release Management
*Libraries and tools for release management.*

* [relx ★474](https://github.com/erlware/relx) - A release assembler for Erlang.

## Configuration Management
*Libraries and tools related to configuration management.*

* [stillir ★34](https://github.com/heroku/stillir) - Cache environment variables as Erlang app variables.

## Codebase Maintenance
*Libraries and tools to maintain a clean codebase.*

* [elvis ★286](https://github.com/inaka/elvis) - Erlang Style Reviewer.

## Web Frameworks
*Web development frameworks.*

* [Axiom](https://github.com/tsujigiri/axiom) - A micro-framework, inspired by Ruby's [Sinatra ★9714](https://github.com/sinatra/sinatra).
* [ChicagoBoss ★1687](https://github.com/ChicagoBoss/ChicagoBoss) - A server framework inspired by Rails and written in Erlang.
* [cowboy ★4622](https://github.com/ninenines/cowboy) - A simple HTTP server.
* [Giallo](https://github.com/kivra/giallo) - A small and flexible web framework on top of [Cowboy ★4622](https://github.com/ninenines/cowboy).
* [MochiWeb ★1567](https://github.com/mochi/mochiweb) - An Erlang library for building lightweight HTTP servers.
* [N2O ★1067](https://github.com/synrc/n2o) - WebSocket Application Server.
* [Nitrogen ★835](https://github.com/nitrogen/nitrogen) - Framework to build web applications (including front-end) in pure Erlang.
* [Zotonic ★539](https://github.com/zotonic/zotonic) - High speed, real-time web framework and content management system.

## Web Framework Components
*Standalone component from web development frameworks.*

* [cb_admin ★74 ⏳1Y](https://github.com/ChicagoBoss/cb_admin) - An admin interface for Chicago Boss.
* [cb_websocket_controller ★7 ⏳4Y](https://github.com/dkuhlman/cb_websocket_controller) - A template for implementing a Websocket controller for ChicagoBoss.
* [giallo_session ★10 ⏳3Y](https://github.com/kivra/giallo_session) - A session management library for the Giallo web framework.
* [simple_bridge ★92](https://github.com/nitrogen/simple_bridge) - An abstraction layer providing a unified interface to popular Erlang web servers (Cowboy, Inets, Mochiweb, Webmachine, and Yaws).

## HTTP
*Libraries for working with HTTP and scraping websites.*

* [bullet ★284 ⏳1Y](https://github.com/ninenines/bullet) - Simple, reliable, efficient streaming for Cowboy.
* [gun ★374](https://github.com/ninenines/gun) - Erlang HTTP client with support for HTTP/1.1, SPDY and Websocket.
* [hackney ★766](https://github.com/benoitc/hackney) - Simple HTTP client in Erlang.
* [ibrowse ★466](https://github.com/cmullaparthi/ibrowse) - Erlang HTTP client.
* [lhttpc ★119](https://github.com/esl/lhttpc) - A lightweight HTTP/1.1 client implemented in Erlang.
* [shotgun ★116](https://github.com/inaka/shotgun) - For the times you need more than just a gun.

## Testing
*Libraries for testing codebases and generating test data.*

* [PropEr ★554](https://github.com/manopapad/proper) - A QuickCheck-inspired property-based testing tool for Erlang.
* [tracerl ★16 ⏳3Y](https://github.com/esl/tracerl) - Dynamic tracing tests and utilities for Erlang/OTP

## Logging
*Libraries for generating and working with log files.*

* [lager ★24](https://github.com/basho/lager) - A logging framework for Erlang/OTP.
* [lager_amqp_backend ★33 ⏳5Y](https://github.com/jbrisbin/lager_amqp_backend) - AMQP RabbitMQ Lager backend.
* [lager_hipchat ★6](https://github.com/synlay/lager_hipchat) - HipChat backend for lager.
* [lager_loggly ★16 ⏳1Y](https://github.com/kivra/lager_loggly) - Loggly backend for lager.
* [lager_smtp ★13 ⏳5Y](https://github.com/blinkov/lager_smtp) - SMTP backend for lager.
* [logplex ★812](https://github.com/heroku/logplex) - Heroku log router.

## Monitoring
*Libraries for gathering metrics and monitoring.*

* [entop ★236](https://github.com/mazenharake/entop) - A top-like Erlang node monitoring tool.
* [eper ★407](https://github.com/massemanet/eper) - A loose collection of Erlang Performance related tools.
* [Exometer ★416](https://github.com/Feuerlabs/exometer) - An Erlang instrumentation package.
* [folsom](https://github.com/boundary/folsom) - An Erlang based metrics system inspired by Coda Hale's [metrics ★418 ⏳1Y](https://github.com/codahale/metrics).
* [statsderl ★81](https://github.com/lpgauth/statsderl) - A statsd Erlang client.
* [vmstats ★157](https://github.com/ferd/vmstats) - Tiny Erlang app that works in conjunction with statsderl in order to generate information on the Erlang VM for graphite logs.

## Deployment
*Libraries and tools related to deployment of Erlang/OTP applications.*

* [docker-erlang ★4](https://github.com/synlay/docker-erlang) - Basic Docker Container Images for Erlang/OTP.

## Distributed Systems
*Tools for stress/load testing, latency issues, etc. across microservices.*

* [Typhoon](https://github.com/zalando/typhoon) - Stress and load testing tool for distributed systems that simulates traffic from a test cluster toward a system-under-test (SUT) and visualizes related latencies.

## Code Analysis
*Libraries and tools for analysing, parsing and manipulation codebases.*

* [Concuerror ★133](https://github.com/parapluu/Concuerror) - Concuerror is a systematic testing tool for concurrent Erlang programs.
* [eflame ★249](https://github.com/proger/eflame) - A Flame Graph profiler for Erlang.

## Build Tools
*Project build and automation tools.*

* [rebar ★919](https://github.com/rebar/rebar) - Erlang build tool that makes it easy to compile and test Erlang applications, port drivers and releases.
* [rebar3](https://github.com/rebar/rebar3) - A build tool for Erlang which can manage Erlang packages from [Hex.pm](https://hex.pm/). See more at [rebar3.org](https://www.rebar3.org/)
* [sync ★615](https://github.com/rustyio/sync) - On-the-fly recompiling for Erlang.

## Geolocation
*Libraries for geocoding addresses and working with latitudes and longitudes.*

* [erl-rstar ★37](https://github.com/armon/erl-rstar) - An Erlang implementation of the R*-tree spacial data structure.
* [GeoCouch ★473](https://github.com/couchbase/geocouch) - A spatial extension for Couchbase and Apache CouchDB.
* [Teles ★12 ⏳1Y](https://github.com/armon/teles) - An Erlang network service for manipulating geographic data.

## Debugging
*Libraries and tools for debugging code and applications.*

* [tx ★61 ⏳3Y](https://github.com/kvakvs/tx) - An HTML Erlang term viewer, starts own webserver and displays any term you give it from your Erlang node.

## Actors
*Libraries and tools for working with actors and such.*

* [poolboy ★996](https://github.com/devinus/poolboy) - A hunky Erlang worker pool factory.

## Date and Time
*Libraries for working with dates and times.*

* [erlang_localtime ★39](https://github.com/dmitryme/erlang_localtime) - Erlang library for conversion from one local time to another.
* [qdate ★189](https://github.com/choptastic/qdate) - Erlang date, time, and timezone management: formatting, conversion, and date arithmetic.

## ORM and Datamapping
*Libraries that implement object-relational mapping or datamapping techniques.*

* [boss_db ★243](https://github.com/ErlyORM/boss_db) - A sharded, caching, pooling, evented ORM for Erlang.
* [epgsql ★217](https://github.com/epgsql/epgsql) - PostgreSQL Driver for Erlang.
* [mysql-otp ★219](https://github.com/mysql-otp/mysql-otp) - MySQL/OTP – MySQL driver for Erlang/OTP.
* [pgsql_migration ★10](https://github.com/artemeff/pgsql_migration) – PostgreSQL migrations for Erlang.

## Queue
*Libraries for working with event and task queues.*

* [dq ★25 ⏳2Y](https://github.com/darach/dq) - Distributed Fault Tolerant Queue library.
* [ebqueue ★5 ⏳2Y](https://github.com/rgrinberg/ebqueue) - Tiny simple blocking queue in erlang.
* [pqueue ★95](https://github.com/okeuday/pqueue) - Erlang Priority Queues.
* [tinymq ★97](https://github.com/ChicagoBoss/tinymq) - A diminutive, in-memory message queue for Erlang.

## Authentication
*Libraries for implementing authentications schemes.*

* [oauth2 ★193](https://github.com/kivra/oauth2) - Erlang Oauth2 implementation.

## Text and Numbers
*Libraries for parsing and manipulating text and numbers.*

* [eql ★66](https://github.com/artemeff/eql) - Erlang with SQL or not.
* [jiffy ★627](https://github.com/davisp/jiffy) - JSON NIFs for Erlang.
* [jsonrec ★13 ⏳3Y](https://github.com/EduardSergeev/jsonrec) - JSON encoder/decoder with the ability to map to records.
* [jsx ★548](https://github.com/talentdeficit/jsx) - An erlang application for consuming, producing and manipulating json.
* [qsp ★14 ⏳1Y](https://github.com/artemeff/qsp) - Enhanced query string parser for Erlang.

## REST and API
*Libraries and web tools for developing REST-ful APIs.*

* [leptus](https://github.com/s1n4/leptus) - Leptus is an Erlang REST framework that runs on top of cowboy.

## Caching
*Libraries for caching data.*

* [cache ★86](https://github.com/fogfish/cache) - In-memory Segmented Cache

## Third Party APIs
*Libraries for accessing third party APIs.*

* [restc ★68](https://github.com/kivra/restclient) - An Erlang REST client
* [oauth2c ★57](https://github.com/kivra/oauth2_client) - An Erlang oAuth 2 client (uses restc)

## Networking
*Libraries and tools for using network related stuff.*

* [barrel_tcp ★83 ⏳2Y](https://github.com/benoitc-attic/barrel_tcp) - barrel_tcp is a generic TCP acceptor pool with low latency in Erlang.
* [gen_rpc ★133](https://github.com/priestjim/gen_rpc) - A scalable RPC library for Erlang-VM based languages.
* [gen_tcp_server ★9 ⏳2Y](https://github.com/rpt/gen_tcp_server) - A library that takes the concept of gen_server and introduces the same mechanics for operating a TCP server.
* [gossiperl ★36 ⏳2Y](https://github.com/gossiperl/gossiperl) - Language agnostic gossip middleware and message bus written in Erlang.
* [nat_upnp ★35 ⏳1Y](https://github.com/benoitc/nat_upnp) - Erlang library to map your internal port to an external using UNP IGD.
* [ranch ★741](https://github.com/ninenines/ranch) - Socket acceptor pool for TCP protocols.

## Internet of Things
*Libraries and tools for interacting with the physical world.*
* [lemma_erlang ★2](https://github.com/noam-io/lemma_erlang) - A lemma for IDEO's Noam internet-of-things prototyping platform.

## Algorithms and Datastructures
*Libraries and implementations of algorithms and datastructures.*

* [erlando ★2 ⏳1Y](https://github.com/travelping/erlando) - A set of syntax extensions like currying and monads for Erlang.
* [statebox ★236 ⏳2Y](https://github.com/mochi/statebox) - Erlang state "monad" with merge/conflict-resolution capabilities.
* [riak_dt ★229](https://github.com/basho/riak_dt) - Erlang library of state based CRDTs.

## Translations and Internationalizations
*Libraries providing translations or internationalizations.*

## Miscellaneous
*Useful libraries or tools that don't fit in the categories above.*

* [erlang-history ★466](https://github.com/ferd/erlang-history) - Hacks to add shell history to Erlang's shell.
* [erld ★192 ⏳1Y](https://github.com/ShoreTel-Inc/erld) - erld is a small program designed to solve the problem of running Erlang programs as a UNIX daemon.

# Resources
Various resources, such as books, websites and articles, for improving your Erlang development skills and knowledge.

## Websites
*Useful web and Erlang-related websites and newsletters.*

* [Erlang Bookmarks](https://github.com/0xAX/erlang-bookmarks/wiki/Erlang-bookmarks) - All about erlang programming language [powerd by community].
* [Erlang Central](https://erlangcentral.org/) - An awesome collections of erlang resource along with live community chat for discussing and seeking help.
* [Planet Erlang](http://www.planeterlang.com/) - Planet site/RSS feed of blog posts covering topics across the Erlang ecosystem.
* [Spawned Shelter](http://spawnedshelter.com/) - Erlang Spawned Shelter. A collection of the best articles, videos and presentations related to Erlang.

## Books
*Fantastic books and e-books.*

* [Erlang and Elixir for Imperative Programmers](https://leanpub.com/erlangandelixirforimperativeprogrammers) - Introduction to Erlang and Elixir in the context of functional concepts by Wolfgang Loder (2016)
* [Learn You Some Erlang](http://learnyousomeerlang.com/) - Learn you some Erlang - for great good! A very thorough resource covering everything from beginning Erlang programming to large-scale development and deployment.
* [Stuff Goes Bad - ERLANG IN ANGER](http://www.erlang-in-anger.com/) - This book intends to be a little guide about how to be the Erlang medic in a time of war.

## Web Reading
*General web-development-related reading materials.*

## Erlang Reading
*Erlang-releated reading materials.*

* [The Joy of Erlang; Or, How To Ride A Toruk](http://www.evanmiller.org/joy-of-erlang.html) - The Joy of Erlang; Or, How To Ride A Toruk A fast track introduction to Erlang that teaches the language by walking through a few example projects.

## Screencasts
*Cool video tutorials.*

# Contributing
Please see [CONTRIBUTING](https://github.com/drobakowski/awesome-erlang/blob/master/CONTRIBUTING.md) for details.
---
<p align="center">
	This list is a copy of <a href="https://github.com/drobakowski/awesome-erlang">drobakowski/awesome-erlang</a> with ranks
</p>
