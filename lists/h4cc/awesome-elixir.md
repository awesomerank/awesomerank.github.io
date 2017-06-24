---
layout: default
title: Awesome Rank for h4cc/awesome-elixir
---

<p align="center">
	This list is a copy of <a href="https://github.com/h4cc/awesome-elixir">h4cc/awesome-elixir</a> with ranks
</p>
---
# Awesome Elixir [![Build Status](https://api.travis-ci.org/h4cc/awesome-elixir.svg?branch=master)](https://travis-ci.org/h4cc/awesome-elixir) [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg) ★59088](https://github.com/sindresorhus/awesome)
A curated list of amazingly awesome Elixir libraries, resources, and shiny things inspired by [awesome-php ★15483](https://github.com/ziadoz/awesome-php).

If you think a package should be added, please add a :+1: (`:+1:`) at the according issue or create a new one.

There are [other sites with curated lists of elixir packages](#other-awesome-lists) which you can have a look at.

- [Awesome Elixir](#awesome-elixir)
    - [Actors](#actors)
    - [Algorithms and Data structures](#algorithms-and-data-structures)
    - [Applications](#applications)
    - [Artificial Intelligence](#artificial-intelligence)
    - [Audio and Sounds](#audio-and-sounds)
    - [Authentication](#authentication)
    - [Authorization](#authorization)
    - [Behaviours and Interfaces](#behaviours-and-interfaces)
    - [Benchmarking](#benchmarking)
    - [Bittorrent](#bittorrent)
    - [BSON](#bson)
    - [Build Tools](#build-tools)
    - [Caching](#caching)
    - [Chatting](#chatting)
    - [Cloud Infrastructure and Management](#cloud-infrastructure-and-management)
    - [Code Analysis](#code-analysis)
    - [Command Line Applications](#command-line-applications)
    - [Configuration](#configuration)
    - [Cryptography](#cryptography)
    - [CSV](#csv)
    - [Date and Time](#date-and-time)
    - [Debugging](#debugging)
    - [Deployment](#deployment)
    - [Documentation](#documentation)
    - [Domain-specific language](#domain-specific-language)
    - [ECMAScript](#ecmascript)
    - [Email](#email)
    - [Embedded Systems](#embedded-systems)
    - [Encoding and Compression](#encoding-and-compression)
    - [Errors and Exception Handling](#errors-and-exception-handling)
    - [Eventhandling](#eventhandling)
    - [Examples and funny stuff](#examples-and-funny-stuff)
    - [Feature Flags and Toggles](#feature-flags-and-toggles)
    - [Feeds](#feeds)
    - [Files and Directories](#files-and-directories)
    - [Formulars](#formulars)
    - [Framework Components](#framework-components)
    - [Frameworks](#frameworks)
    - [Games](#games)
    - [Geolocation](#geolocation)
    - [Hardware](#hardware)
    - [HTTP](#http)
    - [Images](#images)
    - [Instrumenting / Monitoring](#instrumenting--monitoring)
    - [JSON](#json)
    - [Languages](#languages)
    - [Lexical analysis](#lexical-analysis)
    - [Logging](#logging)
    - [Macros](#macros)
    - [Markdown](#markdown)
    - [Miscellaneous](#miscellaneous)
    - [Native Implemented Functions](#native-implemented-functions)
    - [Natural Language Processing (NLP)](#natural-language-processing-nlp)
    - [Networking](#networking)
    - [Office](#office)
    - [ORM and Datamapping](#orm-and-datamapping)
    - [OTP](#otp)
    - [Package Management](#package-management)
    - [PDF](#pdf)
    - [Protocols](#protocols)
    - [Queue](#queue)
    - [Release Management](#release-management)
    - [REST and API](#rest-and-api)
    - [Security](#security)
    - [Static Page Generation](#static-page-generation)
    - [Statistics](#statistics)
    - [Templating](#templating)
    - [Testing](#testing)
    - [Text and Numbers](#text-and-numbers)
    - [Third Party APIs](#third-party-apis)
    - [Translations and Internationalizations](#translations-and-internationalizations)
    - [Utilities](#utilities)
    - [Validations](#validations)
    - [Version Control](#version-control)
    - [Video](#video)
    - [XML](#xml)
    - [YAML](#yaml)
- [Resources](#resources)
    - [Books](#books)
    - [Community](#community)
    - [Editors](#editors)
    - [Newsletters](#newsletters)
    - [Other Awesome Lists](#other-awesome-lists)
    - [Reading](#reading)
    - [Screencasts](#screencasts)
    - [Styleguides](#styleguides)
    - [Websites](#websites)
- [Contributing](#contributing)

## Actors
*Libraries and tools for working with actors and such.*

* [dflow ★8](https://github.com/dalmatinerdb/dflow) - Pipelined flow processing engine.
* [exactor ★445](https://github.com/sasa1977/exactor) - Helpers for easier implementation of actors in Elixir.
* [exos](https://github.com/awetzel/exos) - A Port Wrapper which forwards cast and call to a linked Port.
* [flowex ★127](https://github.com/antonmi/flowex) - Railway Flow-Based Programming with Elixir GenStage.
* [mon_handler ★1 ⏳1Y](https://github.com/tattdcodemonkey/mon_handler) - A minimal GenServer that monitors a given GenEvent handler.
* [pool_ring ★2 ⏳2Y](https://github.com/camshaft/pool_ring) - Create a pool based on a hash ring.
* [poolboy ★896](https://github.com/devinus/poolboy) - A hunky Erlang worker pool factory.
* [pooler ★236](https://github.com/seth/pooler) - An OTP Process Pool Application.
* [sbroker ★68](https://github.com/fishcakez/sbroker) - Sojourn-time based active queue management library.
* [workex ★55 ⏳1Y](https://github.com/sasa1977/workex) - Backpressure and flow control in EVM processes.

## Algorithms and Data structures
*Libraries and implementations of algorithms and data structures.*

* [array ★18](https://github.com/takscape/elixir-array) - An Elixir wrapper library for Erlang's array.
* [aruspex ★13](https://github.com/dkendal/aruspex) - Aruspex is a configurable constraint solver, written purely in Elixir.
* [bitmap ★16](https://github.com/hashd/bitmap-elixir) - Pure Elixir implementation of [bitmaps](https://en.wikipedia.org/wiki/Bitmap).
* [blocking_queue ★33](https://github.com/joekain/BlockingQueue) - BlockingQueue is a simple queue implemented as a GenServer. It has a fixed maximum length established when it is created.
* [bloomex ★32](https://github.com/gmcabrita/bloomex) - A pure Elixir implementation of Scalable Bloom Filters.
* [clope ★1](https://github.com/ayrat555/clope) - Elixir implementation of [CLOPE](http://www.inf.ufrgs.br/~alvares/CMP259DCBD/clope.pdf): A Fast and Effective Clustering Algorithm for Transactional Data.
* [combination ★8](https://github.com/seantanly/elixir-combination) - Elixir library to generate combinations and permutations from Enumerable collection.
* [count_buffer ★2 ⏳1Y](https://github.com/camshaft/count_buffer) - Buffer a large set of counters and flush periodically.
* [cuckoo ★18](https://github.com/gmcabrita/cuckoo) - A pure Elixir implementation of [Cuckoo Filters](https://www.cs.cmu.edu/%7Edga/papers/cuckoo-conext2014.pdf).
* [cuid ★17 ⏳2Y](https://github.com/duailibe/cuid) - Collision-resistant ids optimized for horizontal scaling and sequential lookup performance, written in Elixir.
* [data_morph](https://hex.pm/packages/data_morph) - Create Elixir structs from data.
* [dataframe ★12](https://github.com/JordiPolo/dataframe) - Package providing functionality similar to Python's Pandas or R's data.frame().
* [datastructures ★162](https://github.com/meh/elixir-datastructures) - A collection of protocols, implementations and wrappers to work with data structures.
* [dlist ★2 ⏳2Y](https://github.com/stocks29/dlist) - Deque implementations in Elixir.
* [eastar](https://github.com/herenowcoder/eastar) - A* graph pathfinding in pure Elixir.
* [ecto_state_machine ★34](https://github.com/asiniy/ecto_state_machine) - Finite state machine pattern implemented on Elixir and  adopted for Ecto.
* [elistrix ★9 ⏳2Y](https://github.com/tobz/elistrix) - A latency / fault tolerance library to help isolate your applications from an uncertain world of slow or failed services.
* [erlang-algorithms ★74](https://github.com/aggelgian/erlang-algorithms) - Implementations of popular data structures and algorithms.
* [exconstructor ★128](https://github.com/appcues/exconstructor) - An Elixir library for generating struct constructors that handle external data with ease.
* [exfsm](https://github.com/awetzel/exfsm) - Simple elixir library to define a static FSM.
* [exkad ★0](https://github.com/rozap/exkad) - A [kademlia](https://en.wikipedia.org/wiki/Kademlia) implementation in Elixir.
* [exmatrix ★43 ⏳1Y](https://github.com/a115/exmatrix) - ExMatrix is a small library for working with matrices, originally developed for testing matrix multiplication in parallel.
* [ezcryptex ★0 ⏳1Y](https://github.com/stocks29/ezcryptex) - Thin layer on top of Cryptex.
* [fnv ★1 ⏳1Y](https://github.com/asaaki/fnv.ex) - Pure Elixir implementation of Fowler–Noll–Vo hash functions.
* [fsm ★198](https://github.com/sasa1977/fsm) - Finite state machine as a functional data structure.
* [fuse ★269](https://github.com/jlouis/fuse) - This application implements a so-called circuit-breaker for Erlang.
* [gen_fsm ★30 ⏳1Y](https://github.com/pavlos/gen_fsm) - A generic finite state-machine - Elixir wrapper around OTP's gen_fsm.
* [graphmath ★40](https://github.com/crertel/graphmath) - An Elixir library for performing 2D and 3D mathematics.
* [hash_ring_ex ★17](https://github.com/reset/hash-ring-ex) - A consistent hash-ring implementation for Elixir.
* [hypex ★4 ⏳1Y](https://github.com/zackehh/hypex) - Fast Elixir implementation of HyperLogLog.
* [indifferent ★4](https://github.com/vic/indifferent) - Indifferent access for Elixir maps/list/tuples with custom key conversion.
* [isaac ★2 ⏳2Y](https://github.com/arianvp/elixir-isaac) - Isaac is an elixir module for ISAAC: a fast cryptographic random number generator.
* [key2value ★3](https://github.com/okeuday/key2value) - Erlang 2-way Set Associative Map.
* [lfsr ★4](https://github.com/pma/lfsr) - Elixir implementation of a binary Galois Linear Feedback Shift Register.
* [loom ★137](https://github.com/asonge/loom) - A CRDT library with δ-CRDT support.
* [luhn ★7](https://github.com/ma2gedev/luhn_ex) - Luhn algorithm in Elixir.
* [lz4 ★43](https://github.com/szktty/erlang-lz4) - LZ4 bindings for Erlang for fast data compressing.
* [memoize ★25](https://github.com/os6sense/DefMemo) - A memoization macro (defmemo) for elixir using a genserver backing store.
* [merkle_tree ★25](https://github.com/yosriady/merkle_tree) - A Merkle hash tree implementation in Elixir.
* [minmaxlist ★4](https://github.com/seantanly/elixir-minmaxlist) - Elixir library extending `Enum.min_by/2`, `Enum.max_by/2` and `Enum.min_max_by/2` to return a list of results instead of just one.
* [mmath ★2](https://github.com/dalmatinerdb/mmath) - A library for performing math on number 'arrays' in binaries.
* [monad ★98 ⏳1Y](https://github.com/rmies/monad) - Haskell inspired monads in Elixir stylish syntax.
* [monadex ★217](https://github.com/rob-brown/MonadEx) - Upgrade your Elixir pipelines with monads.
* [murmur ★10](https://github.com/gmcabrita/murmur) - A pure Elixir implementation of the non-cryptographic hash Murmur3.
* [natural_sort ★4 ⏳2Y](https://github.com/DanCouper/natural_sort) - Elixir natural sort implementation for lists of strings.
* [navigation_tree ★1 ⏳1Y](https://github.com/gutschilla/elixir-navigation-tree) - A navigation tree representation with helpers to generate HTML out of it.
* [parallel_stream ★40](https://github.com/beatrichartz/parallel_stream) - A parallel stream implementation for Elixir.
* [paratize ★17](https://github.com/seantanly/elixir-paratize) - Elixir library providing some handy parallel processing (execution) facilities that support configuring number of workers and timeout.
* [parex ★61 ⏳2Y](https://github.com/StevenJL/parex) - Parallel Execute (Parex) is an Elixir module for executing multiple (slow) processes in parallel.
* [qex ★2](https://github.com/princemaple/elixir-queue) - Wraps `:queue`, with improved API and `Inspect`, `Collectable` and `Enumerable` protocol implementations.
* [ratio ★7](https://github.com/Qqwy/elixir-rational) - Adds Rational Numbers and allows them to be used in common arithmatic operations. Also supports conversion between Floats and Rational Numbers.
* [red_black_tree ★21](https://github.com/SenecaSystems/red_black_tree) - Red-Black tree implementation in Elixir.
* [remodel ★89](https://github.com/stavro/remodel) - An Elixir presenter package used to transform map structures.
* [rendezvous ★3 ⏳1Y](https://github.com/timdeputter/Rendezvous) - Implementation of the Rendezvous or Highest Random Weight (HRW) hashing algorithm in Elixir.
* [rock ★0](https://github.com/ayrat555/rock) - Elixir implementation of ROCK: A Robust Clustering Algorithm for Categorical Attributes.
* [sfmt ★58](https://github.com/jj1bdx/sfmt-erlang) - SIMD-oriented Fast Mersenne Twister (SFMT) for Erlang.
* [simhash ★9](https://github.com/UniversalAvenue/simhash-ex) - Simhash implementation using Siphash and N-grams.
* [sorted_set ★14](https://github.com/SenecaSystems/sorted_set) - Sorted Sets for Elixir.
* [spacesaving ★2 ⏳1Y](https://github.com/rozap/spacesaving) - stream count distinct element estimation using the "space saving" algorithm.
* [structurez ★11 ⏳1Y](https://github.com/hamiltop/structurez) - A playground for data structures in Elixir.
* [supermemo ★5 ⏳2Y](https://github.com/edubkendo/supermemo) - An Elixir implementation of the [Supermemo 2 algorithm](https://www.supermemo.com/english/ol/sm2.htm).
* [tfidf ★11 ⏳1Y](https://github.com/OCannings/tf-idf) - An Elixir implementation of term frequency–inverse document frequency.
* [the_fuzz ★30](https://github.com/smashedtoatoms/the_fuzz) - Fuzzy string-matching algorithm implementations.
* [tinymt ★26 ⏳1Y](https://github.com/jj1bdx/tinymt-erlang) - Tiny Mersenne Twister (TinyMT) for Erlang.
* [trie ★93](https://github.com/okeuday/trie) - Erlang Trie Implementation.
* [witchcraft ★81](https://github.com/expede/witchcraft) - Common algebraic structures and functions for Elixir.
* [zipper_tree ★11 ⏳2Y](https://github.com/Dkendal/zipper_tree) - Variadic arity tree with a zipper for Elixir.

## Applications
*Standalone applications.*
* [Alher ★24 ⏳1Y](https://github.com/Queertoo/Alher) - Alexander is a rock-solid IRC bot written in Elixir with powerful plugins.
* [bpe ★77](https://github.com/spawnproc/bpe) - Business Process Engine in Erlang.
* [Consolex ★83 ⏳1Y](https://github.com/sivsushruth/consolex) - Consolex is a tool that allows you to attach a web based console to any mix project.
* [dragonfly_server ★37 ⏳1Y](https://github.com/cloud8421/dragonfly-server) - Elixir app to serve Dragonfly images.
* [ExChat ★155](https://github.com/tony612/exchat) - A Slack-like app by Elixir, Phoenix & React(redux).
* [Exon ★14](https://github.com/tchoutri/Exon) - A “mess manager” developed in Elixir and provides a simple API to manage & document your stuff.
* [ExShop ★141](https://github.com/authentic-pixels/ex-shop) - Digital goods shop & blog created using Phoenix framework.
* [Hydra ★34 ⏳1Y](https://github.com/doomspork/hydra) - A multi-headed beast: API gateway, request cache, and data transformations.
* [majremind](https://bitbucket.org/Anwen/majremind) - A self-maintained database of your updated server which tells you which one needs to be updated.
* [medex ★4 ⏳1Y](https://github.com/xerions/medex) - Medical Examination - application for register health check callbacks and represent their state via HTTP.
* [medusa_server ★2](https://github.com/IcaliaLabs/medusa_server) - A simple cowboy web server written in Elixir to stack images.
* [n2o ★1041](https://github.com/synrc/n2o) - WebSocket Application Server.
* [Nvjorn ★5](https://github.com/tchoutri/Nvjorn) - A multi-protocol network services monitor written in Elixir using Poolboy.
* [Phoenix Battleship ★382](https://github.com/bigardone/phoenix-battleship) - The Good Old game built with Elixir, Phoenix Framework, React and Redux.
* [Phoenix Toggl ★150](https://github.com/bigardone/phoenix-toggl) - Toggl tribute done in Elixir, Phoenix Framework, React and Redux.
* [Phoenix Trello ★1785](https://github.com/bigardone/phoenix-trello) - Trello tribute done in Elixir, Phoenix Framework, React and Redux.
* [poxa ★599](https://github.com/edgurgel/poxa) - Open Pusher implementation, compatible with Pusher libraries.
* [Queerlink ★18 ⏳1Y](https://github.com/Queertoo/Queerlink) - A simple yet efficient URL shortening service written in Elixir.
* [Sprint Poker ★136](https://github.com/elpassion/sprint-poker) - Online estimation tool for Agile teams, written using Elixir Lang, Phoenix Framework and React.
* [Startup Job ★22](https://github.com/tsurupin/job_search) - An umbrella project to search startup jobs scraped from websites written in Elixir/Phoenix and React/Redux.
* [tty2048 ★128 ⏳1Y](https://github.com/lexmag/tty2048) - Terminal-based 2048 game written in Elixir.

## Artificial Intelligence
*When your code becomes smarter than you.*

* [Exnn ★46](https://github.com/zampino/exnn) - Evolutive Neural Networks framework à la G.Sher written in Elixir.
* [Neat-Ex](https://gitlab.com/onnoowl/Neat-Ex) - An Elixir implementation of the NEAT algorithm.
* [simple_bayes ★253](https://github.com/fredwu/simple_bayes) - A Simple Bayes / Naive Bayes implementation in Elixir.

## Audio and Sounds
*Libraries working with sounds and tones.*

* [erlaudio ★16 ⏳1Y](https://github.com/asonge/erlaudio) - Erlang PortAudio bindings.
* [synthex ★23](https://github.com/bitgamma/synthex) - A signal synthesis library.

## Authentication
*Libraries for implementing authentication schemes.*

* [aeacus ★29 ⏳1Y](https://github.com/zmoshansky/aeacus) - A simple configurable identity/password authentication module (Compatible with Ecto/Phoenix).
* [apache_passwd_md5](https://github.com/kevinmontuori/Apache.PasswdMD5) - Apache/APR Style Password Hashing.
* [aws_auth ★38](https://github.com/bryanjos/aws_auth) - AWS Signature Version 4 Signing Library for Elixir.
* [blackbook ★24 ⏳1Y](https://github.com/bigmachine-io/blackbook) - All-in-one membership/authentication system for Elixir.
* [coherence ★533](https://github.com/smpallen99/coherence) - Coherence is a full featured, configurable authentication system for Phoenix.
* [doorman ★62](https://github.com/BlakeWilliams/doorman) - Tools to make Elixir authentication simple and flexible.
* [github_oauth ★4 ⏳2Y](https://github.com/lidashuang/github_oauth) - A simple github oauth library.
* [goth ★44](https://github.com/peburrows/goth) - OAuth 2.0 library for server to server applications via Google Cloud APIs.
* [guardian ★1599](https://github.com/ueberauth/guardian) - An authentication framework for use with Elixir applications.
* [htpasswd](https://github.com/kevinmontuori/Apache.htpasswd) - Apache htpasswd file reader/writer in Elixir.
* [mojoauth ★2 ⏳1Y](https://github.com/mojolingo/mojo-auth.ex) - MojoAuth implementation in Elixir.
* [oauth2 ★344](https://github.com/scrogson/oauth2) - An OAuth 2.0 client library for Elixir.
* [oauth2cli ★3 ⏳2Y](https://github.com/mgamini/oauth2cli-elixir) - Simple OAuth2 client written for Elixir.
* [oauth2ex ★54](https://github.com/parroty/oauth2ex) - Another OAuth 2.0 client library for Elixir.
* [oauther ★32](https://github.com/lexmag/oauther) - An OAuth 1.0 implementation for Elixir.
* [openmaize ★197](https://github.com/riverrun/openmaize) - Authentication library for Elixir.
* [sesamex ★7](https://github.com/khusnetdinov/sesamex) - Another simple and flexible authentication solution in 5 minutes!.
* [shield ★106](https://github.com/mustafaturan/shield) - An OAuth 2.0 provider library and implementation for Phoenix Framework.
* [sigaws ★2](https://github.com/handnot2/sigaws) - AWS Signature V4 signing and verification library ([Doc](https://hexdocs.pm/sigaws/Sigaws.html)).
* [ueberauth ★521](https://github.com/ueberauth/ueberauth) - An Elixir Authentication System for Plug-based Web Applications.
* [ueberauth_active_directory ★6](https://github.com/torrick/ueberauth_active_directory) - Uberauth strategy for Active Directory authentication.
* [ueberauth_auth0](https://hex.pm/packages/ueberauth_auth0) - An Ueberauth strategy for using Auth0 to authenticate your users.
* [ueberauth_cas ★8](https://github.com/marceldegraaf/ueberauth_cas) - Central Authentication Service strategy for Überauth.
* [ueberauth_facebook ★32](https://github.com/ueberauth/ueberauth_Facebook) - Facebook OAuth2 Strategy for Überauth.
* [ueberauth_foursquare ★0](https://github.com/borodiychuk/ueberauth_foursquare) - Foursquare OAuth2 Strategy for Überauth.
* [ueberauth_github ★29](https://github.com/ueberauth/ueberauth_github) - A GitHub strategy for Überauth.
* [ueberauth_google ★30](https://github.com/ueberauth/ueberauth_google) - A Google strategy for Überauth.
* [ueberauth_identity ★37](https://github.com/ueberauth/ueberauth_identity) - A simple username/password strategy for Überauth.
* [ueberauth_line ★1](https://github.com/alexfilatov/ueberauth_line) - LINE Strategy for Überauth.
* [ueberauth_microsoft ★0](https://github.com/swelham/ueberauth_microsoft) - A Microsoft strategy for Überauth.
* [ueberauth_slack ★7](https://github.com/ueberauth/ueberauth_slack) - A Slack strategy for Überauth.
* [ueberauth_twitter ★17](https://github.com/ueberauth/ueberauth_twitter) - Twitter Strategy for Überauth.
* [ueberauth_vk ★9](https://github.com/sobolevn/ueberauth_vk) - [vk.com](https://vk.com) Strategy for Überauth.
* [ueberauth_weibo ★10 ⏳1Y](https://github.com/he9qi/ueberauth_weibo) - [Weibo](https://weibo.com) OAuth2 Strategy for Überauth.

## Authorization
*Libraries for implementing Authorization handling.*

* [authorize ★29](https://github.com/jfrolich/authorize) - Rule based authorization, for advanced authorization rules.
* [bodyguard ★107](https://github.com/schrockwell/bodyguard) - A flexible authorization library for Phoenix applications.
* [canada ★113](https://github.com/jarednorman/canada) - A simple authorization library that provides a friendly interface using declarative permission rules.
* [canary ★265](https://github.com/cpjk/canary) - An authorization library for Elixir applications that restricts what resources the current user is allowed to access.

## Behaviours and Interfaces
*Definitions how something should behave, like Interfaces from OOP-World*

* [connection ★140](https://github.com/fishcakez/connection) - Connection behaviour for connection processes. The API is superset of the GenServer API.
* [gen_state_machine ★64](https://github.com/antipax/gen_state_machine) - Elixir wrapper for gen_statem.
* [stockastic ★19 ⏳1Y](https://github.com/shanewilton/stockastic) - Simple Elixir wrapper for the Stockfighter API.

## Benchmarking
*Running code to see how long it takes, which is faster and/or if improvements have been made.*

* [benchee ★188](https://github.com/PragTob/benchee) - Easy and extensible benchmarking in Elixir!
* [benchfella ★231](https://github.com/alco/benchfella) - Benchmarking tool for Elixir.
* [bmark ★52](https://github.com/joekain/bmark) - A benchmarking tool for Elixir.

## Bittorrent
*Sharing is caring with Elixir*

* [bento ★30](https://github.com/folz/bento) - An incredibly fast, correct, pure-Elixir Bencoding library.
* [tracker_request ★8 ⏳2Y](https://github.com/alehander42/tracker_request) - Dealing with bittorrent tracker requests and responses.
* [wire ★9 ⏳1Y](https://github.com/alehander42/wire) - Encode and decode bittorrent peer wire protocol messages with Elixir.

## BSON
*Libraries and implementations working with BSON.*

* [BSONMap ★3](https://github.com/Nebo15/bsoneach) - Elixir package that applies a function to each document in a BSON file and has a low memory consumption.

## Build Tools
*Project build and automation tools.*

* [active ★49](https://github.com/synrc/active) - Recompilation and Reloading on FileSystem changes.
* [coffee_rotor ★16 ⏳2Y](https://github.com/HashNuke/coffee_rotor) - Rotor plugin to compile CoffeeScript files.
* [dismake ★3 ⏳2Y](https://github.com/jarednorman/dismake) - Mix compiler running make.
* [etude ★9](https://github.com/exstruct/etude) - Parallel computation coordination compiler for Erlang/Elixir.
* [ExMake ★16 ⏳2Y](https://github.com/lycus/exmake) - A modern, scriptable, dependency-based build tool loosely based on Make principles.
* [Exscript ★5](https://github.com/liveforeverx/exscript) - Elixir escript library.
* [mad ★114](https://github.com/synrc/mad) - Small and Fast Rebar Replacement.
* [pc ★25](https://github.com/blt/port_compiler) - A rebar3 port compiler.
* [reaxt](https://github.com/awetzel/reaxt) - React template into your Elixir application for server rendering.
* [rebar3_abnfc_plugin ★1 ⏳1Y](https://github.com/surik/rebar3_abnfc_plugin) - Rebar3 abnfc compiler.
* [rebar3_asn1_compiler ★0 ⏳1Y](https://github.com/pyykkis/rebar3_asn1_compiler) - Plugin for compiling ASN.1 modules with Rebar3.
* [rebar3_auto ★24](https://github.com/vans163/rebar3_auto) - Rebar3 plugin to auto compile and reload on file change.
* [rebar3_diameter_compiler ★0](https://github.com/carlosedp/rebar3_diameter_compiler) - Compile diameter .dia files in rebar3 projects.
* [rebar3_eqc ★9](https://github.com/kellymclaughlin/rebar3-eqc-plugin) - A rebar3 plugin to enable the execution of Erlang QuickCheck properties.
* [rebar3_exunit ★0 ⏳1Y](https://github.com/processone/rebar3_exunit) - A plugin to run Elixir ExUnit tests from rebar3 build tool.
* [rebar3_idl_compiler ★0](https://github.com/sebastiw/rebar3_idl_compiler) - This is a plugin for compiling Erlang IDL files using Rebar3.
* [rebar3_live ★2 ⏳1Y](https://github.com/pvmart/rebar3_live) - Rebar3 live plugin.
* [rebar3_neotoma_plugin ★0 ⏳1Y](https://github.com/zamotivator/rebar3_neotoma_plugin) - Rebar3 neotoma (Parser Expression Grammar) compiler.
* [rebar3_protobuffs ★9 ⏳1Y](https://github.com/benoitc/rebar3_protobuffs) - rebar3 protobuffs provider using protobuffs from Basho.
* [rebar3_run ★14](https://github.com/tsloughter/rebar3_run) - Run a release with one simple command.
* [rebar3_yang_plugin ★0 ⏳1Y](https://github.com/surik/rebar3_yang_plugin) - Rebar3 yang compiler.
* [reltool_util ★13](https://github.com/okeuday/reltool_util) - Erlang reltool utility functionality application.
* [relx ★451](https://github.com/erlware/relx) - A release assembler for Erlang.
* [remix ★64](https://github.com/AgilionApps/remix) - Automatic recompilation of Mix code on file change.
* [rotor ★80 ⏳2Y](https://github.com/HashNuke/rotor) - Super-simple build system for Elixir.
* [sass_elixir ★0 ⏳2Y](https://github.com/zamith/sass_elixir) - A sass plugin for Elixir projects.

## Caching
*Libraries for caching data.*

* [cachex ★231](https://github.com/zackehh/cachex) - A powerful caching library for Elixir with a wide featureset.
* [con_cache ★281](https://github.com/sasa1977/con_cache) - ConCache is an ETS based key/value storage.
* [elixir_locker ★9 ⏳1Y](https://github.com/tsharju/elixir_locker) - Locker is an Elixir wrapper for the locker Erlang library that provides some useful libraries that should make using locker a bit easier.
* [jc ★13](https://github.com/jr0senblum/jc) - In-memory, distributable cache with pub/sub, JSON-query and consistency support.
* [locker ★128 ⏳1Y](https://github.com/wooga/locker) - Atomic distributed "check and set" for short-lived keys.
* [lru_cache ★18](https://github.com/arago/lru_cache) - Simple LRU Cache, implemented with ets.
* [stash ★34](https://github.com/zackehh/stash) - A straightforward, fast, and user-friendly key/value store.

## Chatting
*Chatting via IRC, Slack, HipChat and other systems using Elixir.*

* [chatty ★29](https://github.com/alco/chatty) - A basic IRC client that is most useful for writing a bot.
* [cog ★731](https://github.com/operable/cog) - Cog is an open chatops platform that gives you a secure, collaborative command line right in your chat window.
* [ExIrc ★83](https://github.com/bitwalker/exirc) - IRC client adapter for Elixir projects.
* [ExMustang ★27](https://github.com/techgaun/ex_mustang) - A simple, clueless slackbot and collection of responders.
* [Guri ★13 ⏳1Y](https://github.com/elvio/guri) - Automate tasks using chat messages.
* [hedwig ★320](https://github.com/hedwig-im/hedwig) - XMPP Client/Bot Framework for Elixir.
* [kaguya ★52](https://github.com/Luminarys/Kaguya) - A small, powerful, and modular IRC bot.
* [slacker ★72 ⏳1Y](https://github.com/koudelka/slacker) - A bot library for the Slack chat service.
* [yocingo ★25](https://github.com/Yawolf/yocingo) - Create your own Telegram Bot.

## Cloud Infrastructure and Management
*Applications, tools and libraries for your own cloud service.*

* [aws ★138](https://github.com/jkakar/aws-elixir) - AWS clients for Elixir.
* [Cloudi](http://cloudi.org/) - CloudI is for back-end server processing tasks that require soft-realtime transaction.
* [discovery ★195](https://github.com/undeadlabs/discovery) - An OTP application for auto-discovering services with Consul.
* [erlcloud ★493](https://github.com/erlcloud/erlcloud) - Cloud Computing library for Erlang (Amazon EC2, S3, SQS, SimpleDB, Mechanical Turk, ELB).
* [ex_aws ★403](https://github.com/CargoSense/ex_aws) - AWS client, supporting Dynamo, Kinesis, Lambda, SQS, and S3.
* [ex_riak_cs ★4](https://github.com/ayrat555/ex_riak_cs) - Riak CS API client.
* [fleet_api ★7 ⏳1Y](https://github.com/jordan0day/fleet-api) - A simple wrapper for the Fleet (CoreOS) API. Can be used with etcd tokens or via direct node URLs.
* [Gandi ★0](https://github.com/Ahamtech/elixir-Gandi) - Gandi Wrapper for Leaseweb infrastructure.
* [IElixir ★113](https://github.com/pprzetacznik/IElixir) - Jupyter's kernel for Elixir programming language.
* [Kubex ★26 ⏳1Y](https://github.com/ingerslevio/kubex) - Kubernetes client and integration for Elixir, written in pure Elixir.
* [Leaseweb ★0](https://github.com/Ahamtech/elixir-leaseweb) - Elixir Wrapper for Leaseweb infrastructure.
* [libcluster ★234](https://github.com/bitwalker/libcluster) - Automatic cluster formation/healing for Elixir applications.
* [nodefinder ★34](https://github.com/okeuday/nodefinder) - Strategies for automatic node discovery in Erlang.
* [nomad ★50](https://github.com/sashaafm/nomad) - Create cloud portable Elixir and Phoenix apps. Write once, use everywhere!
* [oceanex ★9](https://github.com/mustafaturan/oceanex) - Digital Ocean API client.
* [sidejob ★79](https://github.com/basho/sidejob) - Parallel worker and capacity limiting library for Erlang.
* [sidetask ★60](https://github.com/PSPDFKit-labs/sidetask) - SideTask is an alternative to Task.Supervisor using Basho's sidejob library with parallelism and capacity limiting.
* [skycluster ★5](https://github.com/Nebo15/skycluster) - Automatic Erlang cluster formation, messaging and management for Elixir/Erlang applications. Integrated with Kubernetes.

## Code Analysis
*Libraries and tools for code base analysis, parsing, and manipulation.*

* [belvedere ★12 ⏳1Y](https://github.com/nirvana/belvedere) - An example of CircleCI integration with Elixir.
* [coverex ★67](https://github.com/alfert/coverex) - Coverage Reports for Elixir.
* [credo ★1866](https://github.com/rrrene/credo) - A static code analysis tool with a focus on code consistency and teaching Elixir.
* [dialyxir ★499](https://github.com/jeremyjh/dialyxir) - Mix tasks to simplify use of Dialyzer in Elixir projects.
* [dogma ★383](https://github.com/lpil/dogma) - A code style linter for Elixir, powered by shame.
* [excoveralls ★251](https://github.com/parroty/excoveralls) - Coverage report tool for Elixir with coveralls.io integration.
* [exprof ★63 ⏳1Y](https://github.com/parroty/exprof) - A simple code profiler for Elixir, using eprof.

## Command Line Applications
*Anything helpful for building CLI applications.*

* [anubis ★77](https://github.com/bennyhallett/anubis) - Command-Line application framework for Elixir.
* [firex ★10](https://github.com/msoedov/firex) - Firex is a library for automatically generating command line interfaces (CLIs) from an elixir module.
* [getopt ★196 ⏳1Y](https://github.com/jcomellas/getopt) - Command-line options parser for Erlang.
* [loki ★29](https://github.com/khusnetdinov/loki) - Library for creating interactive command-line application.
* [meld](https://github.com/Lac/meld) - Create global binaries from mix tasks.
* [optimus ★19](https://github.com/savonarola/optimus) - Command-line option parser for Elixir inspired by [clap.rs](https://clap.rs/).
* [progress_bar ★162](https://github.com/henrik/progress_bar) - Command-line progress bars and spinners.
* [table_rex ★56](https://github.com/djm/table_rex) - Generate configurable ASCII style tables for display.
* [tabula ★26](https://github.com/aerosol/tabula) - Pretty print list of Ecto query results / maps in ascii tables (GitHub Markdown/OrgMode).

## Configuration
*Libraries and tools working with configurations*

* [confex ★35](https://github.com/Nebo15/confex) - Helper module that provides a nice way to read environment configuration at runtime.
* [configparser_ex ★4](https://github.com/easco/configparser_ex) - A simple Elixir parser for the same kind of files that Python's configparser library handles.
* [conform ★241](https://github.com/bitwalker/conform) - Easy release configuration for Elixir apps.
* [dotenv ★122](https://github.com/avdi/dotenv_elixir) - A port of dotenv to Elixir.
* [ex_conf ★28 ⏳2Y](https://github.com/phoenixframework/ex_conf) - Simple Elixir Configuration Management.
* [figaro ★7 ⏳1Y](https://github.com/trestrantham/ex_figaro) - Simple Elixir project configuration.
* [figaro_elixir ★8](https://github.com/KamilLelonek/figaro-elixir) - Environmental variables manager for Elixir.
* [sweetconfig ★1 ⏳3Y](https://github.com/d0rc/sweetconfig) - Read YAML configuration files from any point at your app.

## Cryptography
*Encrypting and decrypting data*

* [aescmac ★4](https://github.com/kleinernik/elixir-aes-cmac) - AES CMAC ([RFC 4493](https://tools.ietf.org/html/rfc4493)) in Elixir.
* [cipher ★19](https://github.com/rubencaro/cipher) - Elixir crypto library to encrypt/decrypt arbitrary binaries.
* [cloak ★128](https://github.com/danielberkompas/cloak) - Cloak makes it easy to use encryption with Ecto.
* [comeonin ★569](https://github.com/riverrun/comeonin) - Password authorization (bcrypt, pbkdf2_sha512 and one-time passwords) library for Elixir.
* [crypto_rsassa_pss ★3 ⏳1Y](https://github.com/potatosalad/erlang-crypto_rsassa_pss) - RSASSA-PSS Public Key Cryptographic Signature Algorithm for Erlang.
* [elixir_tea ★1 ⏳2Y](https://github.com/keichan34/elixir_tea) - TEA implementation in Elixir.
* [ex_bcrypt ★2 ⏳1Y](https://github.com/manelli/ex_bcrypt) - Elixir wrapper for the OpenBSD bcrypt password hashing algorithm.
* [ex_crypto ★28](https://github.com/ntrepid8/ex_crypto) - Elixir wrapper for Erlang `crypto` and `public_key` modules. Provides sensible defaults for many crypto functions to make them easier to use.
* [exgpg ★6 ⏳1Y](https://github.com/rozap/exgpg) - Use gpg from Elixir.
* [pot ★38](https://github.com/yuce/pot) - Erlang library for generating one time passwords compatible with Google Authenticator.
* [rsa ★13 ⏳2Y](https://github.com/trapped/elixir-rsa) - `public_key` cryptography wrapper for Elixir.
* [rsa_ex ★6](https://github.com/anoskov/rsa-ex) - Library for working with RSA keys.
* [siphash-elixir ★7](https://github.com/zackehh/siphash-elixir) - Elixir implementation of the SipHash hash family.
* [tea_crypto ★0 ⏳2Y](https://github.com/keichan34/tea_crypto_erl) - Tiny Encryption Algorithm implementation.

## CSV
*Libraries and implementations working with CSV.*

* [cesso ★19 ⏳3Y](https://github.com/meh/cesso) - CSV handling library for Elixir.
* [csv ★199](https://github.com/beatrichartz/csv) - CSV Decoding and Encoding for Elixir.
* [csvlixir ★24](https://github.com/jimm/csvlixir) - A CSV reading/writing application for Elixir.
* [ex_csv ★32](https://github.com/CargoSense/ex_csv) - CSV for Elixir.
* [nimble_csv ★180](https://github.com/plataformatec/nimble_csv) - A simple and fast CSV parsing and dumping library for Elixir.

## Date and Time
*Libraries for working with dates and times.*

* [block_timer ★7 ⏳2Y](https://github.com/adamkittelson/block_timer) - Macros to use :timer.apply_after and :timer.apply_interval with a block.
* [calendar ★258](https://github.com/lau/calendar) - Calendar is a date and time library for Elixir.
* [chronos ★82](https://github.com/nurugger07/chronos) - An Elixir date/time library.
* [cronex ★14](https://github.com/jbernardo95/cronex) - Cron like system you can mount in your supervision tree.
* [crontab ★9](https://github.com/jshmrtn/crontab) - A Cron Expressions Parser, Composer & Date Candidate Finder.
* [ex_ical ★15](https://github.com/fazibear/ex_ical) - ICalendar parser.
* [filtrex ★30](https://github.com/rcdilorenzo/filtrex) - A library for performing and validating complex SQL-like filters from a client (e.g. smart filters).
* [good_times ★36 ⏳1Y](https://github.com/DevL/good_times) - Expressive and easy to use datetime functions.
* [jalaali ★7](https://github.com/jalaali/elixir-jalaali) - Jalaali calendar implementation for Elixir.
* [milliseconds ★1 ⏳2Y](https://github.com/davebryson/elixir_milliseconds) - Simple library to work with milliseconds in Elixir.
* [moment ★25 ⏳1Y](https://github.com/atabary/moment) - Parse, validate, manipulate, and display dates in Elixir.
* [quantum ★681](https://github.com/c-rack/quantum-elixir) - Cron-like job scheduler for Elixir applications.
* [repeatex ★23](https://github.com/rcdilorenzo/repeatex) - Natural language parsing for repeating dates.
* [timelier ★9](https://github.com/ausimian/timelier) - A cron-style scheduler for Elixir.
* [timex ★680](https://github.com/bitwalker/timex) - Easy to use Date and Time modules for Elixir.
* [timex_interval ★7 ⏳1Y](https://github.com/atabary/timex-interval) - A date/time interval library for Elixir projects, based on Timex.
* [tzdata ★46](https://github.com/lau/tzdata) - The timezone database in Elixir.

## Debugging
*Libraries and tools for debugging code and applications.*

* [beaker ★261](https://github.com/hahuang65/beaker) - Statistics and Metrics library for Elixir.
* [booter ★13 ⏳2Y](https://github.com/eraserewind/booter) - Boot an Elixir application, step by step.
* [dbg ★109](https://github.com/fishcakez/dbg) - Distributed tracing for Elixir.
* [eflame ★236](https://github.com/proger/eflame) - Flame Graph profiler for Erlang.
* [eh ★14 ⏳1Y](https://github.com/Frost/eh) - A tool to look up Elixir documentation from the command line.
* [eper ★388](https://github.com/massemanet/eper) - Erlang performance and debugging tools.
* [ether ★3 ⏳2Y](https://github.com/maarek/ether) - Ether provides functionality to hook Elixir into the Erlang debugger.
* [exrun ★63](https://github.com/liveforeverx/exrun) - Distributed tracing for Elixir with rate limiting and simple macro-based interface.
* [observer_cli ★324](https://github.com/zhongwencool/observer_cli) - Visualize Elixir & Erlang nodes on the command line, it aims to helpe developers debug production systems.
* [quaff ★53](https://github.com/qhool/quaff) - The Debug module provides a simple helper interface for running Elixir code in the erlang graphical debugger.
* [visualixir ★622](https://github.com/koudelka/visualixir) - A process visualizer for remote BEAM nodes.

## Deployment
*Installing and running your code automatically on other machines.*

* [ansible-elixir-stack ★243](https://github.com/HashNuke/ansible-elixir-stack) - 1-command setup & deploys to servers, with first-class support for Phoenix apps.
* [bottler ★22](https://github.com/rubencaro/bottler) - Bottler is a collection of tools that aims to help you generate releases, ship them to your servers, install them there, and get them live on production.
* [edeliver ★1207](https://github.com/boldpoker/edeliver) - Deployment for Elixir and Erlang.
* [exdm ★10 ⏳1Y](https://github.com/joeyates/exdm) - Deploy Elixir applications via mix tasks.
* [gatling ★344](https://github.com/hashrocket/gatling) - Collection of mix tasks to automatically create a exrm release from git and launch/upgrade it on your server.
* [heroku-buildpack-elixir ★515](https://github.com/HashNuke/heroku-buildpack-elixir) - Heroku buildpack to deploy Elixir apps to Heroku.
* [Nanobox ★939](https://github.com/nanobox-io/nanobox) - A micro-PaaS (μPaaS) for creating consistent, isolated, development environments deployable anywhere https://nanobox.io.

## Documentation
*Libraries and tools for creating documentation.*

* [bureaucrat ★118](https://github.com/api-hogs/bureaucrat) - Generate Phoenix API documentation from tests.
* [ex_doc ★396](https://github.com/elixir-lang/ex_doc) - ExDoc is a tool to generate documentation for your Elixir projects.
* [ex_doc_dash ★60](https://github.com/JonGretar/ExDocDash) - Formatter for ExDoc to generate docset documentation for use in Dash.app.
* [hexdocset ★18 ⏳1Y](https://github.com/yesmeck/hexdocset) - Convert hex doc to Dash.app's docset format.
* [inch-ci](http://inch-ci.org/) - Documentation badges for Ruby & Elixir.
* [maru_swagger](https://github.com/falood/maru_swagger) - Add swagger compliant documentation to your maru API.
* [phoenix_api_docs ★16](https://github.com/smoku/phoenix_api_docs) - Generate API Blueprint documentation from controllers and tests in the Phoenix framework.
* [phoenix_swagger ★183](https://github.com/xerions/phoenix_swagger) - Provides swagger integration to the Phoenix framework.

## Domain-specific language
*Specialized computer languages for a particular application domain.*

* [Absinthe Graphql ★962](https://github.com/absinthe-graphql/absinthe) - Fully featured GraphQL library.
* [graphql ★658](https://github.com/graphql-elixir/graphql) - An Elixir implementation of Facebook's GraphQL.

## ECMAScript
*Implementations working with JavaScript, JScript or ActionScript.*

* [estree](https://github.com/bryanjos/elixir-estree) - A implementation of the SpiderMonkey Parser API in Elixir.
* [phoenix_gon ★16](https://github.com/khusnetdinov/phoenix_gon) - Allow you to pass Phoenix environment or controller variables to JavaScript without problems.

## Email
*Working with Email and stuff.*

* [bamboo ★619](https://github.com/thoughtbot/bamboo) - Composable, testable and adapter based email library. Out of the box support for rendering with Phoenix and a plug for previewing sent emails in dev.
* [echo ★24 ⏳1Y](https://github.com/zmoshansky/echo) - A meta-notification system; Echo checks notification preferences & dispatches notifications.
* [ex_postmark ★1](https://github.com/KamilLelonek/ex_postmark) - Postmark adapter for sending template emails in Elixir.
* [gen_smtp ★420](https://github.com/Vagabond/gen_smtp) - A generic Erlang SMTP server and client that can be extended via callback modules.
* [gmail ★33](https://github.com/craigp/elixir-gmail) - A simple Gmail REST API client for Elixir.
* [mail ★249](https://github.com/DockYard/elixir-mail) - An RFC2822 implementation in Elixir, built for composability.
* [mailer ★40](https://github.com/antp/mailer) - A simple SMTP mailer.
* [mailibex](https://github.com/awetzel/mailibex) - Library containing Email-related implementations in Elixir: dkim, spf, dmark, mimemail, smtp.
* [mailman ★136](https://github.com/kamilc/mailman) - Mailman provides a clean way of defining mailers in your Elixir applications.
* [pop3mail](https://hex.pm/packages/pop3mail) - Pop3 client to download email (including attachments) from the inbox via the commandline or Elixir API.
* [ravenx ★39](https://github.com/acutario/ravenx) - Notification dispatch library for Elixir applications.
* [smoothie ★17](https://github.com/jfrolich/smoothie) - Smoothie inline styles of your email templates, and generates a plain text version from the HTML.
* [swoosh ★312](https://github.com/swoosh/swoosh) - Compose, deliver and test your Emails easily in Elixir with adapters for SMTP, Sendgrid, Mandrill, Mailgun, Postmark and Phoenix integration with mailbox preview.

## Embedded Systems
*Embedded systems development.*

* [bake ★49 ⏳1Y](https://github.com/bakeware/bake) - Configure, compile and share systems, toolchains and linux firmware.
* [nerves](http://nerves-project.org) - A framework for writing embedded software in Elixir.

## Encoding and Compression
*Transforming data in different formats or compressing it.*

* [huffman ★12 ⏳2Y](https://github.com/SenecaSystems/huffman) - Huffman encoding and decoding in Elixir.

## Errors and Exception Handling
*Working with errors and exceptions.*

* [exceptional ★61](https://github.com/expede/exceptional) - Helpers for happy-path programming & exception handling.
* [happy ★24](https://github.com/vic/happy) - Happy path programming, alternative to elixir `with` form.
* [OK ★104](https://github.com/CrowdHailer/OK) - Elegant error handling with result monads, featuring a simple & powerful `with` construct and a happy path pipe operator.
* [ok_jose ★43](https://github.com/vic/ok_jose) - Pipe elixir functions that match `{:ok,_}`, `{:error,_}` tuples or custom patterns.
* [sentry-elixir ★114](https://github.com/getsentry/sentry-elixir) - The Official Elixir client for [Sentry](https://sentry.io/).

## Eventhandling
*Sending/Emitting and receiving/handling Events in Elixir.*

* [goldrush ★56](https://github.com/DeadZen/goldrush) - Small, Fast event processing and monitoring for Erlang/OTP applications.
* [reaxive ★128 ⏳1Y](https://github.com/alfert/reaxive) - Reaxive is a reactive event handling library, inspired by [Elm](http://elm-lang.org) and Reactive Extensions.

## Examples and funny stuff
*Example code and stuff too funny or curious not to mention.*

* [butler_cage ★1 ⏳1Y](https://github.com/keathley/butler_cage) - A Butler plugin for showing silly photos of Nick Cage.
* [butler_tableflip ★1 ⏳1Y](https://github.com/keathley/butler_tableflip) - Flipping tables with butler.
* [dice ★11](https://github.com/stocks29/dice) - Roll the dice, in Elixir.
* [elixir_koans ★557](https://github.com/elixirkoans/elixir-koans) - [Elixir koans](http://elixirkoans.io/) is a fun, easy way to get started with the elixir programming language.
* [ex_chain ★11 ⏳1Y](https://github.com/eljojo/ex_chain) - Simple Markov Chain that generates funny tweets, built using Elixir.
* [ex_iss ★2 ⏳1Y](https://github.com/cryptobird/ex_iss) - This package is for interfacing with the Open Notify API to information such as the ISS's current location, crew, and when it will pass over a location.
* [harakiri ★13](https://github.com/rubencaro/harakiri) - Help applications kill themselves.
* [hello_phoenix ★116 ⏳1Y](https://github.com/bigardone/phoenix-react-redux-template) - Application template for SPAs with Phoenix, React and Redux.
* [kaisuu ★57 ⏳1Y](https://github.com/SebastianSzturo/kaisuu) - Watch Japan's Kanji Usage on Twitter in Realtime.
* [koans ★238 ⏳1Y](https://github.com/dojo-toulouse/elixir-koans) - Learn Elixir by using elixir-koans.
* [lolcat ★4 ⏳2Y](https://github.com/restartr/ex-lolcat) - This is the clone of busyloop/lolcat. But it does not support animation and some features of the original.
* [magnetissimo ★1896](https://github.com/sergiotapia/magnetissimo) - Web application that indexes all popular torrent sites, and saves it to the local database.
* [oop ★112](https://github.com/wojtekmach/oop) - OOP in Elixir!
* [phoenix-flux-react ★166 ⏳2Y](https://github.com/fxg42/phoenix-flux-react) - An experiment with Phoenix Channels, GenEvents, React and Flux.
* [portal ★30](https://github.com/josevalim/portal) - A shooting fault-tolerant doors for distributed portal data-transfer application in Elixir.
* [rollex](https://gitlab.com/olhado/rollex) - Elixir library using a Pratt Parser algorithm to calculate dice rolls.
* [rubix ★2 ⏳2Y](https://github.com/YellowApple/Rubix) - A very simple (and barely-functioning) Ruby runner for Elixir.
* [stranger](https://github.com/cazrin/stranger) - Elixir Phoenix app to chat anonymously with a randomly chosen stranger.
* [weather ★59 ⏳1Y](https://github.com/tacticiankerala/elixir-weather) - A command line weather app built using Elixir.

## Feature Flags and Toggles
*Libraries to manage feature toggles (AKA feature flags): ON/OFF values that can be toggled at runtime through some interface*

* [flippant ★16](https://github.com/sorentwo/flippant) - Feature flipping for the Elixir world.
* [fun_with_flags ★38](https://github.com/tompave/fun_with_flags) - A feature toggle library using Redis for persistance, ETS for local caching and Redis PubSub for inter-node cache busting. Optimized for speed and low Redis usage.
* [molasses ★51](https://github.com/securingsincity/molasses) - A feature toggle library using redis or SQL (using Ecto) as a backing service.

## Feeds
*Libraries working with feeds like RSS or ATOM.*

* [feeder ★22](https://github.com/michaelnisi/feeder) - Parse RSS and Atom feeds.
* [feeder_ex ★38](https://github.com/manukall/feeder_ex) - RSS feed parser. Simple wrapper for feeder.
* [feedme ★6](https://github.com/umurgdk/elixir-feedme) - RSS/Atom parser built on erlang's xmerl xml parser.

## Files and Directories
*Libraries and implementations for working with files and directories.*

* [arc ★579](https://github.com/stavro/arc) - Flexible file upload and attachment library for Elixir.
* [cassius ★7 ⏳1Y](https://github.com/jquadrin/cassius) - Monitor Linux file system events.
* [dir_walker ★19](https://github.com/pragdave/dir_walker) - DirWalker lazily traverses one or more directory trees, depth first, returning successive file names.
* [elixgrep ★26](https://github.com/bbense/elixgrep) - A framework for doing Hadoop style Map/Reduce operations on collections of files.
* [ex_guard ★32](https://github.com/slashmili/ex_guard) - ExGuard is a mix command to handle events on file system modifications.
* [ex_minimatch ★8 ⏳2Y](https://github.com/gniquil/ex_minimatch) - Globbing paths without walking the tree!.
* [exfile ★56](https://github.com/keichan34/exfile) - File upload handling, persistence, and processing in Elixir and Plug.
* [exfswatch ★35](https://github.com/falood/exfswatch) - A file change watcher wrapper based on __fs__.
* [eye_drops ★33](https://github.com/rkotze/eye_drops) - Configurable mix task to watch file changes and run the corresponding command.
* [fs ★127](https://github.com/synrc/fs) - Erlang FileSystem Listener.
* [fwatch ★3](https://github.com/ryo33/fwatch-ex) - A callback-based file watcher based on __fs__.
* [librex ★10](https://github.com/ricn/librex) - Elixir library to convert office documents to other formats using LibreOffice.
* [Radpath ★17](https://github.com/lowks/Radpath) - Path library for Elixir, inspired by Python's Enhpath.
* [sentix ★7](https://github.com/zackehh/sentix) - A cross-platform file watcher for Elixir based on fswatch.
* [sizeable ★15](https://github.com/arvidkahl/sizeable) - An Elixir library to make file sizes human-readable.
* [zarex ★10 ⏳1Y](https://github.com/ricn/zarex) - Filename sanitization for Elixir.

## Formulars
*Handling web formulars and similar stuff.*

* [forms ★17](https://github.com/spawnproc/forms) - Erlang Business Documents Generator.

## Framework Components
*Standalone component from web development frameworks.*

* [absinthe_plug ★55](https://github.com/absinthe-graphql/absinthe_plug) - Plug support for Absinthe.
* [addict ★567](https://github.com/trenpixster/addict) - User authentication for Phoenix Framework.
* [airbrake_plug ★5 ⏳2Y](https://github.com/romul/airbrake_plug) - Report errors in your Plug stack or whatever to Airbrake.
* [ashes ★66 ⏳2Y](https://github.com/nickgartmann/ashes) - A code generation tool for the Phoenix web framework.
* [blaguth ★15](https://github.com/lexmag/blaguth) - Basic Access Authentication in Plug applications.
* [commanded ★201](https://github.com/slashdotdash/commanded) - Command handling middleware for Command Query Responsibility Segregation (CQRS) applications.
* [cors_plug ★116](https://github.com/mschae/cors_plug) - An Elixir plug that adds CORS headers to requests and responds to preflight requests (OPTIONS).
* [corsica ★174](https://github.com/whatyouhide/corsica) - Elixir library for dealing with CORS requests.
* [crudex ★13 ⏳2Y](https://github.com/bitgamma/crudex) - CRUD utilities for Phoenix and Ecto.
* [dayron ★122](https://github.com/inaka/Dayron) - A repository _similar_ to `Ecto.Repo` that works with REST API requests instead of a database.
* [ex_admin ★714](https://github.com/smpallen99/ex_admin) - ExAdmin is an auto administration package for Elixir and the Phoenix Framework.
* [exdjango ★10](https://github.com/nicksanders/exdjango) - A few elixir libraries for working with django.
* [exrecaptcha ★8 ⏳1Y](https://github.com/adanselm/exrecaptcha) - Simple reCaptcha display/verify code for Elixir applications.
* [filterable ★17](https://github.com/omohokcoj/filterable) - Simple query params filtering for Phoenix framework inspired by Rails has_scope.
* [graphql_parser](https://github.com/graphql-elixir/graphql_parser) - An Elixir binding for [libgraphqlparser ★388](https://github.com/graphql/libgraphqlparser).
* [http_router ★9](https://github.com/sugar-framework/elixir-http-router) - HTTP Router with various macros to assist in developing your application and organizing your code.
* [kerosene ★126](https://github.com/elixirdrops/kerosene) - Pagination for Ecto and Phoenix.
* [mellon ★10 ⏳1Y](https://github.com/sajmoon/mellon) - An authentication module for Plug applications.
* [multiverse ★19](https://github.com/Nebo15/multiverse) - Plug that allows to add version compatibility layers via API Request/Response Gateways.
* [params ★59](https://github.com/vic/params) - Use Ecto to enforce/validate parameters structure, akin to Rails' strong parameters.
* [passport ★145](https://github.com/opendrops/passport) - Passport provides authentication for Phoenix applications.
* [phoenix_ecto ★113](https://github.com/phoenixframework/phoenix_ecto) - Phoenix and Ecto integration.
* [phoenix_haml ★121](https://github.com/chrismccord/phoenix_haml) - Phoenix Template Engine for Haml.
* [phoenix_html ★96](https://github.com/phoenixframework/phoenix_html) - Phoenix.HTML functions for working with HTML strings and templates.
* [phoenix_html_sanitizer ★12](https://github.com/elixirstatus/phoenix_html_sanitizer) - HTML Sanitizer integration for Phoenix.
* [phoenix_html_simplified_helpers ★11](https://github.com/ikeikeikeike/phoenix_html_simplified_helpers) - Some helpers for phoenix html (truncate, time_ago_in_words, number_with_delimiter).
* [phoenix_linguist ★13 ⏳1Y](https://github.com/jxs/phoenix_linguist) - A project that integrates Phoenix with Linguist, providing a plug and view helpers.
* [phoenix_live_reload ★81](https://github.com/phoenixframework/phoenix_live_reload) - Provides live-reload functionality for Phoenix.
* [phoenix_pubsub_postgres ★23 ⏳2Y](https://github.com/opendrops/phoenix-pubsub-postgres) - Postgresql PubSub adapter for Phoenix apps.
* [phoenix_pubsub_rabbitmq ★29 ⏳1Y](https://github.com/pma/phoenix_pubsub_rabbitmq) - RabbitMQ adapter for Phoenix's PubSub layer.
* [phoenix_pubsub_redis ★63](https://github.com/phoenixframework/phoenix_pubsub_redis) - The Redis PubSub adapter for the Phoenix framework.
* [phoenix_pubsub_vernemq ★21 ⏳2Y](https://github.com/larshesel/phoenix_pubsub_vernemq) - The VerneMQ MQTT pubsub adapter for the Phoenix framework.
* [phoenix_slime ★137](https://github.com/slime-lang/phoenix_slime) - Slim template support for Phoenix.
* [phoenix_token_auth ★164](https://github.com/manukall/phoenix_token_auth) - Token authentication solution for Phoenix. Useful for APIs or single page apps.
* [plug ★1378](https://github.com/elixir-lang/plug) - A specification and conveniences for composable modules in between web applications.
* [plug_accesslog ★13](https://github.com/mneudert/plug_accesslog) - Plug for writing access logs.
* [plug_and_play ★7](https://github.com/henrik/plug_and_play) - Set up a Plug application with less boilerplate.
* [plug_auth ★57](https://github.com/bitgamma/plug_auth) - Collection of authentication-related plugs.
* [plug_cloudflare ★10](https://github.com/c-rack/plug_cloudflare) - Inspired by mod_cloudflare, this Elixir plug parses Cloudflares CF-Connecting-IP HTTP request header into Plug.Conn's remote_ip field.
* [plug_forward_peer](https://github.com/awetzel/plug_forwarded_peer) - Very simple plug which reads X-Forwarded-For or Forwarded header according to RFC7239 and fill conn.remote_ip with the root client ip.
* [plug_fprof ★2 ⏳1Y](https://github.com/obmarg/plug_fprof) - A Plug that adds fprof tracing to requests, to allow for easy profiling.
* [plug_graphql ★114](https://github.com/graphql-elixir/plug_graphql) - Phoenix Plug integration for [GraphQL Elixir](http://graphql-elixir.org/).
* [plug_heartbeat ★12 ⏳1Y](https://github.com/whatyouhide/plug_heartbeat) - A plug for responding to heartbeat requests.
* [plug_jwt ★33 ⏳1Y](https://github.com/bryanjos/plug_jwt) - Plug for JWT authentication.
* [plug_rails_cookie_session_store ★62](https://github.com/cconstantin/plug_rails_cookie_session_store) - Rails compatible Plug session store.
* [plug_redirect_https ★5](https://github.com/stocks29/plug_redirect_https) - Plug to redirect http requests to https requests behind a reverse proxy.
* [plug_require_header ★18 ⏳1Y](https://github.com/DevL/plug_require_header) - Require and extract HTTP headers and handle missing ones.
* [plug_response_header ★9 ⏳1Y](https://github.com/c-rack/plug_response_header) - easy manipulation of HTTP response headers.
* [plug_ribbon ★19 ⏳1Y](https://github.com/stnly/plug_ribbon) - Injects a ribbon to your web application in the development environment.
* [plug_secex ★5](https://github.com/techgaun/plug_secex) - Plug that adds various HTTP Headers to make Phoenix/Elixir app more secure.
* [plug_session_memcached ★8](https://github.com/gutschilla/plug-session-memcached) - A very simple memcached session store for Elixir's plug.
* [plug_sigaws ★0](https://github.com/handnot2/plug_sigaws) - AWS Signature V4 authentication protection for Phoenix/Plug Routes ([Docs](https://hexdocs.pm/plug_sigaws/PlugSigaws.html)).
* [plug_statsd ★41](https://github.com/jeffweiss/plug_statsd) - A plug for automatically sending timing and count metrics to statsd.
* [plugs ★15 ⏳1Y](https://github.com/sugar-framework/plugs) - Collection of Plug middleware for web applications.
* [plugsnag ★36](https://github.com/jarednorman/plugsnag) - Bugsnag notifier for Elixir's plug.
* [raygun ★15](https://github.com/cobenian/raygun) - Capture bugs and send them to Raygun.
* [react_phoenix ★115](https://github.com/geolessel/react-phoenix) - Render React.js components in Phoenix views focusing on easy installation and Brunch compatibility.
* [resin ★3 ⏳1Y](https://github.com/Frost/resin) - Resin is a plug that will add a configurable delay to every request that's passing through it, unless run in production.
* [revision_plate_ex ★2](https://github.com/KazuCocoa/revision_plate_ex) - Plug application and middleware that serves endpoint returns application's REVISION.
* [rummage_ecto](https://github.com/Excipients/rummage_ecto) - A configurable framework to search, sort and paginate Ecto Queries.
* [rummage_phoenix](https://github.com/Excipients/rummage_phoenix) - A support framework for searching, sorting and paginating models in Phoenix, with HTML support.
* [scaffold ★5 ⏳2Y](https://github.com/gausby/scaffold) - A mix task for creating new projects based on templates fetched from a Git-repo.
* [scrivener ★322](https://github.com/drewolson/scrivener) - Paginate your Ecto queries.
* [scrivener_headers ★29](https://github.com/doomspork/scrivener_headers) - Helpers for paginating API responses with Scrivener and HTTP headers.
* [scrivener_html ★55](https://github.com/mgwidmann/scrivener_html) - Helpers built to work with Scrivener's page struct to easily build HTML output for various CSS frameworks.
* [sentinel ★78](https://github.com/britton-jb/sentinel) - An authentication framework for Phoenix extending guardian with routing and other basic functionality.
* [trailing_format_plug ★15](https://github.com/mschae/trailing_format_plug) - An Elixir plug to support legacy APIs that use a rails-like trailing format.
* [webassembly](https://github.com/herenowcoder/webassembly) - Web DSL for Elixir.
* [weebo ★3 ⏳1Y](https://github.com/stevenschobert/weebo) - An XML-RPC parser/formatter for Elixir, with full support for datatype mapping.

## Frameworks
*Web development frameworks.*

* [exelli ★12 ⏳2Y](https://github.com/pigmej/exelli) - An Elli Elixir wrapper with some sugar syntax goodies.
* [kitto ★533](https://github.com/kittoframework/kitto) - A framework for interactive dashboards.
* [phoenix ★9627](https://github.com/phoenixframework/phoenix) - Elixir Web Framework targeting full-featured, fault tolerant applications with realtime functionality.
* [placid ★136](https://github.com/slogsdon/placid) - A REST toolkit for building highly-scalable and fault-tolerant HTTP APIs with Elixir.
* [rackla ★189](https://github.com/AntonFagerberg/rackla) - API Gateways in Elixir.
* [relax ★122 ⏳1Y](https://github.com/AgilionApps/relax) - Simple Elixir implementation of a [jsonapi.org](http://jsonapi.org) server.
* [rest ★46 ⏳1Y](https://github.com/synrc/rest) - Micro-REST framework with typed JSON.
* [sugar ★321](https://github.com/sugar-framework/sugar) - Modular web framework for Elixir.
* [trot ★209](https://github.com/hexedpackets/trot) - An Elixir web micro-framework.

## Games
*Libraries for and implementations of games.*

* [entice ★57 ⏳1Y](https://github.com/entice/entice) - A distributed Entity-Component-System framework, providing its own example MMORPG server.
* [mines ★1](https://github.com/kevlar1818/mines) - A minesweeper clone in the terminal.

## Geolocation
*Libraries for geocoding addresses and working with latitudes and longitudes.*

* [distance_api_matrix ★23 ⏳1Y](https://github.com/C404/distance-matrix-api) - Provide distance and heading calculations via Google distance matrix api.
* [geo ★260](https://github.com/bryanjos/geo) - A collection of GIS functions for Elixir.
* [geocalc ★34](https://github.com/yltsrc/geocalc) - Calculate distance, bearing and more between latitude/longitude points.
* [geohash ★8](https://github.com/polmuz/elixir-geohash) - Geohash encode/decode library.
* [geohax ★3](https://github.com/evuez/geohax) - Geohash encoding and decoding with neighbors finder.
* [geoip ★19](https://github.com/navinpeiris/geoip) - Find geolocation for a given IP, hostname or `Plug.Conn`.
* [geolix](https://github.com/mneudert/geolix) - MaxMind GeoIP2 database reader/decoder.
* [geonames ★4](https://github.com/pareeohnos/geonames-elixir) - A simple Elixir wrapper around the GeoNames API.
* [ip2location ★10 ⏳1Y](https://github.com/nazipov/ip2location-elixir) - An Elixir library for IP2Location database.
* [ipgeobase ★8 ⏳1Y](https://github.com/sergey-chechaev/elixir_ipgeobase) - Find Russian and Ukraine city by IP address and find country for other country.
* [proj ★2](https://github.com/CandyGumdrop/proj) - Elixir coordinate conversion library using OSGeo's PROJ.4.
* [segseg ★1](https://github.com/pkinney/segseg_ex) - Segment-segment intersection classifier and calculator.
* [topo ★10](https://github.com/pkinney/topo) - A Geometry library for Elixir that calculates spatial relationships between two geometries.

## Hardware
*Hardware related things like I/O interfaces and such.*

* [elixir_ale ★196](https://github.com/fhunleth/elixir_ale) - Elixir access to hardware I/O interfaces such as GPIO, I2C, and SPI.
* [nerves ★414](https://github.com/nerves-project/nerves) - Framework for building firmware for platforms like Raspberry Pi and BeagleBone Black.

## HTTP
*Libraries for working with HTTP and scraping websites.*

* [bolt ★30 ⏳1Y](https://github.com/SebastianSzturo/bolt) - Simple and fast http proxy.
* [cauldron ★68](https://github.com/meh/cauldron) - An HTTP/SPDY server as a library.
* [elli ★644](https://github.com/knutin/elli) - Elli is a webserver you can run inside your Erlang application to expose an HTTP API.
* [explode ★5](https://github.com/pkinney/explode) - An easy utility for responding with standard HTTP/JSON error payloads in Plug- and Phoenix-based applications.
* [exvcr ★283](https://github.com/parroty/exvcr) - HTTP request/response recording library for Elixir, inspired by VCR.
* [fuzzyurl](https://github.com/gamache/fuzzyurl.ex) - An Elixir library for parsing, constructing, and wildcard-matching URLs. Also available for [Ruby](https://github.com/gamache/fuzzyurl.rb) and [JavaScript ★3 ⏳1Y](https://github.com/gamache/fuzzyurl.js).
* [hackney ★678](https://github.com/benoitc/hackney) - Simple HTTP client written in Erlang.
* [http ★11 ⏳2Y](https://github.com/slogsdon/http) - HTTP server for Elixir.
* [http_digex ★1](https://github.com/techgaun/http_digex) - A module to create basic digest HTTP auth header.
* [http_proxy ★21](https://github.com/KazuCocoa/http_proxy) - Multi port HTTP Proxy.
* [httpoison ★937](https://github.com/edgurgel/httpoison) - Yet Another HTTP client for Elixir powered by hackney.
* [httpotion ★569](https://github.com/myfreeweb/httpotion) - Fancy HTTP client for Elixir, based on ibrowse.
* [ivar ★7](https://github.com/swelham/ivar) - A lightweight wrapper around HTTPoison that provides a fluent and composable way to build http requests.
* [lhttpc ★1 ⏳1Y](https://github.com/talko/lhttpc) - A lightweight HTTP/1.1 client implemented in Erlang.
* [mnemonic_slugs ★4](https://github.com/devshane/mnemonic_slugs) - A memorable, mnemonic slug generator in Elixir.
* [mochiweb ★1480](https://github.com/mochi/mochiweb) - MochiWeb is an Erlang library for building lightweight HTTP servers.
* [plug_wait1 ★1](https://github.com/wait1/plug_wait1) - Plug adapter for the wait1 protocol.
* [river ★59](https://github.com/peburrows/river) - An HTTP/2 client that is lightweight and lightning fast.
* [scrape ★159](https://github.com/Anonyfox/elixir-scrape) - Scrape any website, article or RSS/Atom Feed with ease.
* [spell ★46](https://github.com/MyMedsAndMe/spell) - Spell is a [Web Application Messaging Protocol](http://wamp-proto.org/) (WAMP) client implementation in Elixir.
* [tesla ★349](https://github.com/teamon/tesla) - HTTP client library, with support for middleware and multiple adapters.
* [Tube ★6](https://github.com/narrowtux/Tube) - Pure Elixir WebSocket client library.
* [uri_query ★5](https://github.com/shhavel/uri_query) - URI encode nested GET parameters and array values in Elixir.
* [uri_template ★11 ⏳1Y](https://github.com/pezra/ex-uri-template) - RFC6570 compliant URI template processor for Elixir.
* [web_socket ★41](https://github.com/slogsdon/plug-web-socket) - An exploration into a stand-alone library for Plug applications to easily adopt WebSockets.
* [webdriver ★75 ⏳1Y](https://github.com/stuart/elixir-webdriver) - This is an implementation of the WebDriver protocol client. It currently supports PhantomJS, FireFox, ChromeDriver and remote webdriver servers (e.g. Selenium).
* [yuri ★7 ⏳1Y](https://github.com/kemonomachi/yuri) - Simple struct for representing URIs.

## Images
*Libraries for working with and manipulating images.*
* [alchemic_avatar ★29](https://github.com/zhangsoledad/alchemic_avatar) - Elixir library for generating letter avatar from string.
* [artifact ★34 ⏳1Y](https://github.com/doomspork/artifact) - File upload and on-the-fly processing for Elixir.
* [bump ★2](https://github.com/evanfarrar/ex_bump) - A BMP file writer in pure Elixir.
* [chunky_svg ★18](https://github.com/mmmries/chunky_svg) -  A library for drawing things with SVG.
* [cloudex ★22](https://github.com/smeevil/cloudex) - Cloudex is an Elixir library that can upload image files or urls to Cloudinary.
* [eikon ★8 ⏳1Y](https://github.com/tchoutri/Eikon) - An Elixir library providing a read-only interface for image files.
* [elixir_exif ★10](https://github.com/sschneider1207/ElixirExif) - Parse exif tags and thumbnail data from jpeg files.
* [ex_image_info ★6](https://github.com/rNoz/ex_image_info) - An Elixir library to parse images (binaries) and get the dimensions, detected mime-type and overall validity for a set of image formats.
* [exexif ★9](https://github.com/pragdave/exexif) - Pure Elixir library to extract TIFF and EFIX metadata from jpeg files.
* [exfavicon ★5 ⏳1Y](https://github.com/ikeikeikeike/exfavicon) - An Elixir library for discovering favicons.
* [identicon ★10](https://github.com/rbishop/identicon) - An Elixir library for generating 5x5 identicons.
* [image64](https://hex.pm/packages/image64) - A tool for working with base64 encoded images.
* [imagineer ★73](https://github.com/SenecaSystems/imagineer) - Image parsing in Elixir.
* [imgex ★13](https://github.com/ianwalter/imgex) - Unofficial client library for generating imgix URLs in Elixir.
* [mogrify ★170](https://github.com/route/mogrify) - An Elixir wrapper for ImageMagick command line.
* [png ★8 ⏳1Y](https://github.com/yuce/png) - A pure Erlang library for creating PNG images. It can currently create 8 and 16 bit RGB, RGB with alpha, indexed, grayscale and grayscale with alpha images.
* [thumbnex ★8](https://github.com/talklittle/thumbnex) - Create thumbnails from images and video screenshots.

## Instrumenting / Monitoring
*Libraries for collecting and exporting metrics.*

* [appsignal-elixir ★35](https://github.com/appsignal/appsignal-elixir) - Collects error and performance data from your Elixir applications and sends it to [AppSignal](https://appsignal.com/).
* [elixometer ★517](https://github.com/pinterest/elixometer) - A light Elixir wrapper around exometer.
* [erlang-metrics ★38](https://github.com/benoitc/erlang-metrics) - A generic interface to different metrics systems in Erlang.
* [exometer ★394](https://github.com/Feuerlabs/exometer) - Basic measurement objects and probe behavior in Erlang.
* [folsom_ddb ★2](https://github.com/dalmatinerdb/folsom_ddb) - DalmatinerDB backend to store folsom metrics.
* [graphitex ★1](https://github.com/msoedov/graphitex) - Graphite/Carbon client for Elixir.
* [instream ★76](https://github.com/mneudert/instream) - InfluxDB driver for Elixir.
* [instrumental ★9 ⏳1Y](https://github.com/undeadlabs/instrumental-ex) - An Elixir client for [Instrumental](https://instrumentalapp.com/).
* [newrelic.ex ★37](https://github.com/romul/newrelic.ex) - Collects metrics from your Elixir/Phoenix application and sends them to [NewRelic](https://newrelic.com/).
* [prometheus ★65](https://github.com/deadtrickster/prometheus.erl) - [Prometheus.io](https://prometheus.io) monitoring system and time series database client in Erlang.
* [prometheus-ecto ★14](https://github.com/deadtrickster/prometheus-ecto) - Ecto instrumenter for prometheus.ex.
* [prometheus-phoenix ★14](https://github.com/deadtrickster/prometheus-phoenix) - Phoenix instrumenter for prometheus.ex.
* [prometheus-plugs ★14](https://github.com/deadtrickster/prometheus-plugs) - Plugs instrumenters/exporter for prometheus.ex.
* [prometheus.ex ★79](https://github.com/deadtrickster/prometheus.ex) - Elixir-friendly [Prometheus.io](https://prometheus.io) monitoring system and time series database client.
* [prometheus_process_collector ★5](https://github.com/deadtrickster/prometheus_process_collector) - Prometheus collector which exports the current state of process metrics including cpu, memory, file descriptor usage and native threads count as well as the process start and up times.

## JSON
*Libraries and implementations working with JSON.*

* [exjson ★69](https://github.com/guedes/exjson) - JSON parser and generator in Elixir.
* [exjsx ★144](https://github.com/talentdeficit/exjsx) - JSON for Elixir, based on `jsx`.
* [ja_serializer](https://github.com/AgilionApps/ja_serializer) - JSONAPI.org Serialization in Elixir.
* [jazz ★61 ⏳2Y](https://github.com/meh/jazz) - Yet another library to handle JSON in Elixir.
* [joken ★302](https://github.com/bryanjos/joken) - Encodes and decodes JSON Web Tokens.
* [jose ★102](https://github.com/potatosalad/erlang-jose) - JSON Object Signing and Encryption (JOSE) for Erlang and Elixir.
* [json ★175](https://github.com/cblage/elixir-json) - Native JSON library for Elixir.
* [json_pointer ★6 ⏳1Y](https://github.com/xavier/json_pointer) - Implementation of RFC 6901 which defines a string syntax for identifying a specific value within a JSON document.
* [json_web_token_ex ★95](https://github.com/garyf/json_web_token_ex) - An Elixir implementation of the JSON Web Token (JWT) Standards Track (RFC 7519).
* [jsonapi ★193](https://github.com/jeregrine/jsonapi) - A project that will render your data models into [JSONAPI Documents](http://jsonapi.org/format/).
* [jsx ★518](https://github.com/talentdeficit/jsx) - An Erlang application for consuming, producing, and manipulating json.
* [jsxn ★30 ⏳1Y](https://github.com/talentdeficit/jsxn) - jsx but with maps.
* [jwalk ★5](https://github.com/jr0senblum/jwalk) - Helper module for working with Erlang representations of JSON.
* [jwtex ★4 ⏳2Y](https://github.com/mschae/jwtex) - A library to encode and decode [JWT tokens](http://jwt.io/).
* [poison ★1059](https://github.com/devinus/poison) - Poison is a new JSON library for Elixir focusing on wicked-fast speed without sacrificing simplicity, completeness, or correctness.
* [tiny ★33](https://github.com/zackehh/tiny) - Tiny, fast and fully compliant JSON parser for Elixir.
* [world_json ★4 ⏳2Y](https://github.com/camshaft/world_json_ex) - topojson country and state/province collections for elixir/erlang.

## Languages
*Languages built on top of Elixir.*

* [lighthouse_scheme ★26](https://github.com/jwhiteman/lighthouse-scheme) - A small Lisp-like language and interactive REPL, built in Elixir.
* [Monkey ★67](https://github.com/fabrik42/writing_an_interpreter_in_elixir) - Elixir implementation of an interpreter and REPL for the js-like Monkey programming language.

## Lexical analysis
*All about lexical analyser, lexer, scanner, tokenizer or compiler.*

* [elixir_script](https://github.com/bryanjos/elixirscript) - The goal is to convert a subset (or full set) of Elixir code to JavaScript.
* [ex_abnf ★21](https://github.com/marcelog/ex_abnf) - Parser for ABNF Grammars in Elixir.
* [lex_luthor ★12](https://github.com/jamesotron/lex_luthor) - LexLuthor is a Lexer in Elixir which uses macros to generate a reusable lexers.

## Logging
*Logging infos and messages.*

* [exlager ★54](https://github.com/khia/exlager) - Elixir binding for lager.
* [exsentry ★24](https://github.com/appcues/exsentry) - Error logging to [Sentry](https://getsentry.com/).
* [gelf_logger ★10](https://github.com/jschniper/gelf_logger) - A Logger backend that will generate Graylog Extended Log Format (GELF) messages.
* [honeybadger ★48](https://github.com/honeybadger-io/honeybadger-elixir) - Error logging to [Honeybadger](https://www.honeybadger.io/).
* [json_logger ★16 ⏳1Y](https://github.com/LeeroyDing/json_logger) - JSON Logger is a logger backend that outputs elixir logs in JSON format.
* [lager ★16](https://github.com/basho/lager) - A logging framework for Erlang/OTP by basho.com.
* [lager_logger ★15](https://github.com/PSPDFKit-labs/lager_logger) - A lager backend that forwards all log messages to Elixir's Logger.
* [logfmt ★10](https://github.com/jclem/logfmt-elixir) - Logfmt is a module for encoding and decoding logfmt-style log lines.
* [logger_logstash_backend ★32](https://github.com/marcelog/logger_logstash_backend) - A backend for the Elixir Logger that will send logs to the Logstash UDP input.
* [logglix ★7](https://github.com/pragmaticivan/logglix) - A logger backend for posting errors to Loggly.
* [logster ★61](https://github.com/navinpeiris/logster) - Easily parsable, one-line logging for Phoenix and Plug applications, inspired by Lograge.
* [metrix ★35](https://github.com/rwdaigle/metrix) - Log custom app metrics to stdout for use by Librato and other downstream processors.
* [mstore ★10](https://github.com/dalmatinerdb/mstore) - MStore is a experimental metric store build in erlang, the primary functions are open, new, get and put.
* [raven](https://github.com/vishnevskiy/raven-elixir) - Elixir client for [Sentry](http://getsentry.com/).
* [rogger ★7 ⏳2Y](https://github.com/duartejc/rogger) - Elixir logger to publish log messages in RabbitMQ.
* [rollbax ★124](https://github.com/elixir-addicts/rollbax) - Exception tracking and logging to [Rollbar](https://rollbar.com/).
* [slack_logger_backend ★23](https://github.com/craigp/slack_logger_backend) - A logger backend for posting errors to Slack.
* [syslog ★70](https://github.com/Vagabond/erlang-syslog) - Erlang port driver for interacting with syslog via syslog(3).
* [timber ★29](https://github.com/timberio/timber-elixir) - Structured logging platform; turns raw text logs into rich structured events.

## Macros
*Macros for faster and easier development. Sugar for your code.*

* [anaphora ★11 ⏳1Y](https://github.com/sviridov/anaphora-elixir) - Anaphora is the anaphoric macro collection for Elixir. An anaphoric macro is one that deliberately captures a variable (typically it) from forms supplied to the macro.
* [apix ★8](https://github.com/liveforeverx/apix) - Simple convention and DSL for transformation of elixir functions to an API for later documentation and or validation.
* [backports ★1](https://github.com/leifg/backports) - Use new functions in Elixir 1.1 and 1.2.
* [eventsourced ★72](https://github.com/slashdotdash/eventsourced) - Build functional, event-sourced domain models.
* [exceptional ★61](https://github.com/expede/exceptional) - Helpers for happy-path programming & exception handling.
* [expat ★43](https://github.com/vic/expat) - Simple pattern generator for matching on elixir quoted expressions.
* [guardsafe ★19 ⏳1Y](https://github.com/DevL/guardsafe) - Macros expanding into code that can be safely used in guard clauses.
* [happy ★24](https://github.com/vic/happy) - Happy path programming, alternative to elixir `with` form.
* [kwfuns ★2 ⏳1Y](https://github.com/RobertDober/lab42_defkw) - Macros to create functions with syntax based keyword parameters with default values.
* [lineo ★0 ⏳2Y](https://github.com/camshaft/lineo) - parse transform for accurate line numbers.
* [mdef ★35 ⏳2Y](https://github.com/pragdave/mdef) - Easily define multiple function heads in Elixir.
* [named_args ★9 ⏳1Y](https://github.com/mgwidmann/named_args) - Allows named arg style arguments in Elixir.
* [OK ★104](https://github.com/CrowdHailer/OK) - Macros for elegant happy path coding, maximizing power and readability.
* [ok_jose ★43](https://github.com/vic/ok_jose) - Pipe elixir functions that match `{:ok,_}`, `{:error,_}` tuples or custom patterns.
* [pattern_tap ★36 ⏳1Y](https://github.com/mgwidmann/elixir-pattern_tap) - Macro for tapping into a pattern match while using the pipe operator.
* [pipe_here ★19](https://github.com/vic/pipe_here) - Easily pipe values into any argument position.
* [pipe_to ★22](https://github.com/taiansu/pipe_to) - The enhanced pipe operator which can specify the target position.
* [pipes ★284](https://github.com/batate/elixir-pipes) - Macros for more flexible composition with the Elixir Pipe operator.
* [pit ★13](https://github.com/vic/pit) - Transform values as they flow inside a pipe.
* [rebind ★0 ⏳2Y](https://github.com/camshaft/rebind) - rebind parse transform for Erlang.
* [rulex](https://github.com/awetzel/rulex) - Simple rule handler using Elixir pattern matching.

## Markdown
*Libraries and tools working with Markdown and such.*

* [cmark ★37](https://github.com/asaaki/cmark.ex) - Elixir NIF for CommonMark (in C), a parser following the CommonMark spec.
* [discount ★20 ⏳1Y](https://github.com/asaaki/discount.ex) - Elixir NIF for discount, a Markdown parser.
* [earmark ★293](https://github.com/pragdave/earmark) - Markdown parser for Elixir.
* [Markdown ★53](https://github.com/devinus/markdown) - Implemented entirely as a NIF binding to the Hoedown library.
* [Pandex ★26 ⏳1Y](https://github.com/filterkaapi/pandex) - Lightweight Elixir wrapper for Pandoc. Converts Markdown, CommonMark, HTML, Latex, HTML, HTML5, opendocument, rtf, texttile, asciidoc to each other.

## Miscellaneous
*Useful libraries or tools that don't fit in the categories above.*

* [address_us ★7](https://github.com/smashedtoatoms/address_us) - Library for parsing US Addresses into their individual parts.
* [Apex ★184](https://github.com/bjro/apex) - Awesome Print for Elixir.
* [bupe ★35](https://github.com/milmazz/bupe) - EPUB Generator and Parser.
* [charm ★4 ⏳2Y](https://github.com/tomgco/elixir-charm) - Use ANSI terminal characters to write colors and cursor positions.
* [Countries ★37](https://github.com/SebastianSzturo/countries) - Countries is a collection of all sorts of useful information for every country in the ISO 3166 standard.
* [countriex ★6](https://github.com/navinpeiris/countriex) - A pure elixir country data provider containing various information for every country in ISO 3166.
* [dye ★14 ⏳1Y](https://github.com/Kabie/dye) - A library for dyeing your terminal output.
* [dynamic_compile ★0 ⏳2Y](https://github.com/okeuday/dynamic_compile) - Compile and load Erlang modules from string input.
* [ecto_autoslug_field ★26](https://github.com/sobolevn/ecto_autoslug_field) - Automatically creates slugs for your Ecto models.
* [egaugex ★1](https://github.com/Brightergy/egaugex) - Client to fetch and parse realtime data from egauge devices.
* [elixir-browser ★21](https://github.com/tuvistavie/elixir-browser) - Browser detection for Elixir.
* [erlang_term ★14](https://github.com/okeuday/erlang_term) - Provide the in-memory size of Erlang terms, ignoring where these are stored.
* [ex2ms ★38](https://github.com/ericmj/ex2ms) - Translates Elixir functions to match specifications for use with `ets`.
* [ex_rated ★108](https://github.com/grempe/ex_rated) - Simple and flexible rate-limiting for API's or anything.
* [exfcm ★1](https://github.com/Hajto/ExFCM) - Simple wrapper for posting Firebase Cloud Messages.
* [exldap ★19](https://github.com/jmerriweather/exldap) - A module for working with LDAP from Elixir.
* [exlibris ★7 ⏳2Y](https://github.com/pragdave/exlibris) - A collection of random library functions.
* [expool ★16 ⏳1Y](https://github.com/zackehh/expool) - A small process pooling library for parallel tasks in Elixir.
* [exprint ★20](https://github.com/parroty/exprintf) - A printf / sprintf library for Elixir, works as a wrapper for :io.format.
* [exquisite ★46](https://github.com/meh/exquisite) - LINQ-like match_spec generation for Elixir.
* [exsync ★26](https://github.com/falood/exsync) - Yet another Elixir reloader.
* [funnel ★30 ⏳1Y](https://github.com/chatgris/funnel) - Streaming Elixir API built upon ElasticSearch's percolation.
* [gen_task ★5](https://github.com/Nebo15/gen_task) - Generic Task behavior that helps to encapsulate worker errors and recover from them in classic GenStage's.
* [gimei_ex ★6 ⏳1Y](https://github.com/ma2gedev/gimei_ex) - Elixir port of gimei library.
* [growl ★1 ⏳1Y](https://github.com/zachallett/growl) - Simple wrapper for growl, the notification system for OSX.
* [html_entities ★27](https://github.com/martinsvalin/html_entities) - Elixir module for decoding HTML entities in a string.
* [huex ★23](https://github.com/xavier/huex) - Elixir client for Philips Hue connected light bulbs.
* [japan_municipality_key ★1](https://github.com/hykw/japan_municipality_key) - Elixir Library for Japan municipality key converting.
* [keys1value ★0](https://github.com/okeuday/keys1value) - Erlang set associative map for key lists.
* [mixgraph ★7 ⏳1Y](https://github.com/sivsushruth/mixgraph) - An interactive dependency plotter for your Hex Package.
* [mixstar ★13 ⏳1Y](https://github.com/ma2gedev/mix-star) - MixStar starred GitHub repository that depends on your project.
* [netrc ★4 ⏳1Y](https://github.com/ma2gedev/netrcex) - Reads netrc files implemented in Elixir.
* [notifier](https://hex.pm/packages/notifier) - A pluggable architecture for desktop notifications.
* [onetime ★4](https://github.com/ryo33/onetime-elixir) - An onetime key-value store for Elixir.
* [pact ★38](https://github.com/BlakeWilliams/pact) - Better dependency injection in Elixir for cleaner code and testing.
* [phone ★35](https://github.com/fcevado/phone) - A parser to get useful info from telephone numbers.
* [porcelain ★474](https://github.com/alco/porcelain) - Porcelain implements a saner approach to launching and communicating with external OS processes from Elixir.
* [presentex ★9 ⏳1Y](https://github.com/Cobenian/Presentex) - Elixir to HTML/JavaScript based presentation framework.
* [ratx ★15](https://github.com/liveforeverx/ratx) - Rate limiter and overload protection for erlang application.
* [reprise](https://github.com/herenowcoder/reprise) - Simplified module reloader for Elixir.
* [spawndir ★3 ⏳2Y](https://github.com/jtmoulia/spawndir) - Spawns processes from the file system.
* [spotify_ex ★27](https://github.com/jsncmgs1/spotify_ex) - An Elixir wrapper for the Spotify Web API.
* [std_json_io ★20](https://github.com/hassox/std_json_io) - Application for managing and communicating with IO servers via JSON.
* [url_unroller ★4 ⏳1Y](https://github.com/semanticart/url_unroller) - Simple URL unroller (un-shortener) in Elixir.
* [vessel ★12](https://github.com/zackehh/vessel) - Elixir MapReduce interfaces with Hadoop Streaming integration.

## Native Implemented Functions
*Tools and libraries working with Erlang NIF.*

* [hsnif ★15 ⏳4Y](https://github.com/urbanserj/hsnif) - Tool that allows to write Erlang NIF libraries in Haskell.
* [nifty ★23 ⏳1Y](https://github.com/rossjones/nifty) - Helper script for setting up the boilerplate required when writing a NIF.
* [Rustler ★581](https://github.com/hansihe/Rustler) - Library for writing NIFs for Erlang or Elixir safely in Rust. No segfaults.

## Natural Language Processing (NLP)
*Tools and libraries that work with human (natural) languages.*

* [gibran](https://github.com/abitdodgy/gibran) - Gibran is an Elixir port of [WordsCounted ★100](https://github.com/abitdodgy/words_counted), a natural language processor that extracts useful statistics from text.
* [Paasaa ★29](https://github.com/minibikini/paasaa) - Natural language detection for Elixir.
* [Woolly ★23](https://github.com/pjhampton/woolly) - Woolly is an ambitious Text Mining and Natural Language Processing API for Elixir.

## Networking
*Libraries and tools for using network related stuff.*

* [asn ★2](https://github.com/ephe-meral/asn) - Can be used to map from IP to AS to ASN.
* [chatter ★21 ⏳1Y](https://github.com/dbeck/chatter_ex) - Secure message broadcasting based on a mixture of UDP multicast and TCP.
* [eio ★8 ⏳1Y](https://github.com/falood/eio) - Elixir server of engine.io.
* [ejabberd ★3011](https://github.com/processone/ejabberd) - Robust, ubiquitous and massively scalable Jabber/XMPP Instant Messaging platform.
* [ExPcap ★14 ⏳2Y](https://github.com/cobenian/expcap) - PCAP parser written in Elixir.
* [mac ★0](https://github.com/ephe-meral/mac) - Can be used to find a vendor of a MAC given in hexadecimal string (according to IEEE).
* [pool ★7 ⏳1Y](https://github.com/slogsdon/pool) - Socket acceptor pool for Elixir.
* [reagent ★87](https://github.com/meh/reagent) - reagent is a socket acceptor pool for Elixir.
* [socket ★449](https://github.com/meh/elixir-socket) - Socket wrapping for Elixir.
* [sshex ★66](https://github.com/rubencaro/sshex) - Simple SSH helpers for Elixir.
* [wifi ★25 ⏳2Y](https://github.com/gausby/wifi) - Various utility functions for working with the local Wifi network in Elixir.
* [wpa_supplicant ★4 ⏳1Y](https://github.com/fhunleth/wpa_supplicant.ex) - Elixir interface to the wpa_supplicant.

## Office
*Libraries for working with office suite documents.*

* [excellent ★18 ⏳1Y](https://github.com/leifg/excellent) - An OpenXL (Excel 2000) Parser for Elixir.
* [xlsxir](https://github.com/kennellroxco/xlsxir) - Xlsx file parser with support for ISO 8601 date formats. Data is extracted to an Erlang Term Storage (ETS) table and is accessed through various functions.

## ORM and Datamapping
*Libraries that implement object-relational mapping or datamapping techniques.*

* [amnesia ★386](https://github.com/meh/amnesia) - Mnesia wrapper for Elixir.
* [arbor ★57](https://github.com/coryodaniel/arbor) - Ecto adjacency list and tree traversal.
* [arc_ecto ★131](https://github.com/stavro/arc_ecto) - Arc.Ecto provides an integration with Arc and Ecto.
* [atlas ★191 ⏳1Y](https://github.com/chrismccord/atlas) - Object Relational Mapper for Elixir.
* [Bolt.Sips ★52](https://github.com/florinpatrascu/bolt_sips) - Neo4j driver for Elixir using the Bolt protocol.
* [boltun ★81](https://github.com/bitgamma/boltun) - Transforms notifications from the Postgres LISTEN/NOTIFY mechanism into callback execution.
* [cassandra_ecto ★15](https://github.com/vintikzzz/cassandra_ecto) - Ecto adapter for Apache Cassandra.
* [caylir ★13](https://github.com/mneudert/caylir) - Cayley driver for Elixir.
* [comeonin_ecto_password ★8](https://github.com/vic/comeonin_ecto_password) - Ecto custom type for storing encrypted password using Comeonin.
* [couchdb_connector ★58](https://github.com/locolupo/couchdb_connector) - A connector for CouchDB, the Erlang-based, JSON document database.
* [craterl ★9 ⏳1Y](https://github.com/crate/craterl) - Erlang client for crate.
* [database_url ★6 ⏳2Y](https://github.com/s-m-i-t-a/database_url) - Parse database URL and return keyword list for use with Ecto.
* [datomex ★30 ⏳1Y](https://github.com/edubkendo/datomex) - Elixir driver for the Datomic REST API.
* [ddb_client ★2](https://github.com/dalmatinerdb/ddb_client) - DalmatinerDB client.
* [defql ★73](https://github.com/fazibear/defql) - Create elixir functions with SQL as a body.
* [dexts ★4](https://github.com/meh/dexts) - Disk Elixir Terms Storage, dest wrapper.
* [diver ★38](https://github.com/novabyte/diver) - A HBase driver for Erlang/Elixir using Jinterface and the Asynchbase Java client to query the database.
* [dproto ★1](https://github.com/dalmatinerdb/dproto) - Protocols for DalmatinerDB.
* [dqe ★9](https://github.com/dalmatinerdb/dqe) - DalmatinerDB query engine.
* [ecto ★2690](https://github.com/elixir-ecto/ecto) - A database wrapper and language integrated query for Elixir.
* [ecto_enum ★155](https://github.com/gjaldon/ecto_enum) - Ecto extension to support enums in models.
* [ecto_factory](https://hex.pm/packages/ecto_factory) - Easily generate structs based on your ecto schemas.
* [ecto_fixtures ★90](https://github.com/DockYard/ecto_fixtures) - Fixtures for Elixir apps using Ecto.
* [ecto_hstore ★13 ⏳1Y](https://github.com/stavro/ecto_hstore) - Ecto.Hstore adds Postgres Hstore compatibility to Ecto.
* [ecto_lazy_float ★6](https://github.com/joshdholtz/ecto-lazy-float) - Ecto.LazyFloat - An Ecto.Float that accepts binary and integers.
* [ecto_migrate ★19](https://github.com/xerions/ecto_migrate) - Ecto auto migration library. It allows to generate and run migrations for initial and update migrations.
* [ecto_mnesia ★51](https://github.com/Nebo15/ecto_mnesia) - Ecto adapter for Mnesia Erlang term database.
* [ecto_ordered ★23](https://github.com/zovafit/ecto-ordered) - Ecto extension for ordered models.
* [ecto_paging ★5](https://github.com/Nebo15/ecto_paging) - Cursor-based pagination for Ecto.
* [ecto_rut ★52](https://github.com/sheharyarn/ecto_rut) - Simple and Powerful Ecto Shortcuts to simplify and speed up development.
* [ecto_shortcuts ★18](https://github.com/MishaConway/ecto_shortcuts) - Shortcuts for common operations in ecto.
* [ecto_validation_case ★7 ⏳1Y](https://github.com/danielberkompas/ecto_validation_case) - Simplify your Ecto model validation tests. Loosely inspired by shoulda matchers, but simpler.
* [ectophile ★30 ⏳1Y](https://github.com/gjaldon/ectophile) - Ecto extension to instantly support file uploads in models.
* [elastic ★16](https://github.com/radar/elastic) - A thin-veneer over HTTPotion to help you talk to Elastic Search.
* [elastix ★77](https://github.com/werbitzky/elastix) - A simple Elastic REST client written in Elixir.
* [eredis ★497](https://github.com/wooga/eredis) - Erlang Redis client.
* [erlastic_search ★107](https://github.com/tsloughter/erlastic_search) - An Erlang app for communicating with Elastic Search's rest interface.
* [esqlite ★46](https://github.com/mmzeeman/esqlite) - Erlang NIF for sqlite.
* [eternal ★29](https://github.com/zackehh/eternal) - Keep your ETS tables alive forever, safely and easily.
* [ets_map ★6 ⏳1Y](https://github.com/antipax/ets_map) - An Elixir package that provides a Map-like interface (Map/Access/Enumerable/Collectable) backed by an ETS table.
* [eventstore ★205](https://github.com/slashdotdash/eventstore) - A CQRS EventStore using Postgres for persistence, written in Elixir.
* [ex_bitcask ★9 ⏳2Y](https://github.com/JonGretar/ExBitcask) - Elixir wrapper of Basho's Bitcask Key/Value store.
* [ex_sider ★5](https://github.com/ephe-meral/ex_sider) - Elixir Map/List/Set interfaces for Redis data structures (uses Redix, but that is configurable).
* [exleveldb ★26](https://github.com/skovsgaard/exleveldb) - Elixir wrapper around Basho's eleveldb module for LevelDB.
* [exnumerator ★27](https://github.com/KamilLelonek/exnumerator) - Elixir enumerable type definition in a simple way to be used with any database.
* [exredis ★289](https://github.com/artemeff/exredis) - Redis client for Elixir.
* [exseed ★10](https://github.com/seaneshbaugh/exseed) - An Elixir library that provides a simple DSL for seeding databases through Ecto.
* [exsolr ★17](https://github.com/dcarneiro/exsolr) - A Solr wrapper written in Elixir.
* [extreme ★59](https://github.com/exponentially/extreme) - An Elixir library using [Eventstore](https://geteventstore.com) for persistance of events generated by aggregates (CQRS).
* [exts ★6](https://github.com/meh/exts) - Elixir Terms Storage, ets wrapper.
* [github_ecto ★95](https://github.com/wojtekmach/github_ecto) - Ecto adapter for GitHub API.
* [hstore ★9 ⏳1Y](https://github.com/senecasystems/hstore) - Hstore support for Postgrex.
* [inquisitor ★105](https://github.com/dockyard/inquisitor) - Composable query builder for Ecto.
* [isn ★8](https://github.com/Frost/isn) - Ecto types for the postgreSQL isn extension.
* [kalecto ★105](https://github.com/lau/calecto) - Glue between Kalends and Ecto for saving dates, times and datetimes.
* [kst ★121](https://github.com/synrc/kvs) - Erlang Abstract Term Database.
* [level ★2 ⏳2Y](https://github.com/gausby/level) - Level for Elixir implements various helper functions and data types for working with Googles Level data store.
* [mariaex ★154](https://github.com/xerions/mariaex) - MariaDB/MySQL driver for Elixir.
* [moebius ★414](https://github.com/robconery/moebius) - A functional query tool for Elixir and PostgreSQL.
* [mongo ★99 ⏳1Y](https://github.com/checkiz/elixir-mongo) - MongoDB driver for Elixir.
* [mongodb ★165](https://github.com/ericmj/mongodb) - MongoDB driver for Elixir.
* [mongodb_ecto ★210](https://github.com/michalmuskala/mongodb_ecto) - MongoDB adapter for Ecto.
* [mysql ★188](https://github.com/mysql-otp/mysql-otp) - MySQL/OTP – MySQL driver for Erlang/OTP.
* [mysqlex ★2](https://github.com/tjheeta/mysqlex) - An Ecto-compatible wrapper around the mysql-otp library.
* [neo4j_sips ★64](https://github.com/florinpatrascu/neo4j_sips) - Neo4j driver for Elixir.
* [neo4j_sips_models ★3 ⏳1Y](https://github.com/florinpatrascu/neo4j_sips_models) - Minimalistic Model support for the Neo4j.Sips Elixir driver.
* [paper_trail ★114](https://github.com/izelnakri/paper_trail) - Ecto plugin for tracking and recording all the changes in your database.
* [postgrex ★418](https://github.com/elixir-ecto/postgrex) - PostgreSQL driver for Elixir.
* [red ★13](https://github.com/rodrigues/red) - Persist relationships between objects in Redis, in a graph-like way.
* [redix ★289](https://github.com/whatyouhide/redix) - Superfast, pipelined, resilient Redis driver for Elixir.
* [redo ★15](https://github.com/heroku/redo) - Heroku's pipelining redis client for erlang.
* [rethinkdb ★455](https://github.com/hamiltop/rethinkdb-elixir) - Rethinkdb client in pure Elixir using JSON protocol.
* [riak ★151](https://github.com/drewkerrigan/riak-elixir-client) - A Riak client written in Elixir.
* [riak_ecto ★24](https://github.com/pma/riak_ecto) - Riak adapter for Ecto.
* [shards ★157](https://github.com/cabol/shards) - Transparent and out-of-box Sharding support for Erlang/Elixir ETS tables.
* [sql_dust ★89](https://github.com/bettyblocks/sql_dust) - Generate (complex) SQL queries using magical Elixir SQL dust.
* [sqlite_ecto ★62](https://github.com/jazzyb/sqlite_ecto) - SQLite3 adapter for Ecto.
* [sqlitex ★43](https://github.com/mmmries/sqlitex) - An Elixir wrapper around esqlite. Allows access to sqlite3 databases.
* [ssdb_elixir ★6](https://github.com/lidashuang/ssdb-elixir) - ssdb client for Elixir, with focus on performance.
* [tds ★24](https://github.com/livehelpnow/tds) - MSSQL / TDS Database driver for Elixir.
* [tds_ecto ★41](https://github.com/livehelpnow/tds_ecto) - MSSQL / TDS Adapter for Ecto.
* [timex_ecto ★93](https://github.com/bitwalker/timex_ecto) - An adapter for using Timex DateTimes with Ecto.
* [tirexs ★350](https://github.com/Zatvobor/tirexs) - An Elixir flavored DSL for building JSON based requests to Elasticsearch engine.
* [udpflux ★3 ⏳2Y](https://github.com/timbuchwaldt/udpflux) - An opinionated InfluxDB UDP only client.
* [yar ★8 ⏳2Y](https://github.com/dantswain/yar) - Yet another Redis client for Elixir.

## OTP
*Libraries for working with OTP related things.*

* [core ★27 ⏳2Y](https://github.com/fishcakez/core) - Library for selective receive OTP processes.
* [erlexec ★252](https://github.com/saleyn/erlexec) - Execute and control OS processes from Erlang/OTP.
* [immortal ★93](https://github.com/danielberkompas/immortal) - Immortal is a small collection of helper modules intended to make it easier to build a fault-tolerant OTP application.
* [libex_config ★1 ⏳2Y](https://github.com/reset/libex-config) - Helpers for accessing OTP application configuration.

## Package Management
*Libraries and tools for package and dependency management.*

* [Hex](https://hex.pm/) - A package manager for the Erlang ecosystem.
* [rebar3_hex ★30](https://github.com/hexpm/rebar3_hex) - Hex.pm plugin for rebar3.

## PDF
*Libraries and software for working with PDF files.*

* [gutenex ★156](https://github.com/SenecaSystems/gutenex) - Native PDF generation for Elixir.
* [pdf2htmlex ★31 ⏳1Y](https://github.com/ricn/pdf2htmlex) - Convert PDF docs to beautiful HTML files without losing text or format.
* [pdf_generator ★71](https://github.com/gutschilla/elixir-pdf-generator) - A simple wrapper for wkhtmltopdf (HTML to PDF) for use in Elixir projects.

## Protocols
*Special protocol and format libraries.*

* [elixir_radius ★6 ⏳1Y](https://github.com/bearice/elixir-radius) - RADIUS Protocol on Elixir.
* [ex_hl7 ★13 ⏳1Y](https://github.com/jcomellas/ex_hl7) - Health Level 7 (HL7) is a protocol designed to model and transfer health-related data electronically.
* [ex_marshal ★25](https://github.com/gaynetdinov/ex_marshal) - Ruby Marshal format implemented in Elixir.
* [exprotobuf ★253](https://github.com/bitwalker/exprotobuf) - Protocol Buffers in Elixir, made easy.
* [grpc-elixir ★131](https://github.com/tony612/grpc-elixir) - The Elixir implementation of gRPC.
* [message_pack ★42 ⏳1Y](https://github.com/mururu/msgpack-elixir) - MessagePack Implementation for Elixir.
* [msgpax ★120](https://github.com/lexmag/msgpax) - MessagePack (de)serializer implementation for Elixir.
* [protox ★5](https://github.com/ahamez/protox) - Elixir implementation for Protocol Buffers.
* [riffed ★234](https://github.com/pinterest/riffed) - Provides idiomatic Elixir bindings for Apache Thrift.
* [Sippet ★4](https://github.com/balena/elixir-sippet) - An Elixir library designed to be used as SIP protocol middleware.
* [SMPPEX ★14](https://github.com/savonarola/smppex) - SMPP 3.4 protocol and framework implementation in Elixir.

## Queue
*Libraries for working with event and task queues.*

* [adap](https://github.com/awetzel/adap) - Create a data stream across your information systems to query, augment and transform data according to Elixir matching rules.
* [amqp ★232](https://github.com/pma/amqp) - Simple Elixir wrapper for the Erlang RabbitMQ client, based on Langohr.
* [cspex ★6 ⏳1Y](https://github.com/costaraphael/cspex) - Simple, OTP compliant, Elixir implementation of CSP channels.
* [dbus ★5 ⏳2Y](https://github.com/aforward/sadbus) - A dumb message bus for sharing data between microservices decoupled using Redis.
* [elixir_nsq ★42](https://github.com/wistia/elixir_nsq) - NSQ client library for Elixir.
* [elixir_talk ★16 ⏳1Y](https://github.com/jsvisa/elixir_talk) - An Elixir client for beanstalkd.
* [enm ★83](https://github.com/basho/enm) - enm is an Erlang port driver that wraps the nanomsg C library.
* [exdisque](https://github.com/mosic/exdisque) - Elixir client for [Disque ★6190](https://github.com/antirez/disque), an in-memory, distributed job queue.
* [exq ★607](https://github.com/akira/exq) - Job processing library for Elixir - compatible with Resque/Sidekiq.
* [exrabbit ★47 ⏳2Y](https://github.com/d0rc/exrabbit) - RabbitMQ bindings and DSL for Elixir.
* [heapq ★5 ⏳1Y](https://github.com/takscape/elixir-heapq) - A Heap-based Priority Queue Implementation in Elixir.
* [honeydew ★150](https://github.com/koudelka/honeydew) - Honeydew is a worker pool library for Elixir.
* [hulaaki ★63](https://github.com/suvash/hulaaki) - An MQTT 3.1.1 client library written in Elixir.
* [kafka_consumer ★13](https://github.com/anoskov/kafka-consumer) - Consumer for Kafka using kafka_ex.
* [kafka_ex ★176](https://github.com/kafkaex/kafka_ex) - Kafka client library for Elixir.
* [mqs ★27 ⏳1Y](https://github.com/synrc/mqs) - RabbitMQ client library, routing keys, RPC over MQ and other stuff.
* [pqueue ★87](https://github.com/okeuday/pqueue) - Erlang Priority Queue Implementation.
* [queuex ★8](https://github.com/falood/queuex) - Priority Queue with multiple backends.
* [RBMQ ★11](https://github.com/Nebo15/rbmq) - Simple API for spawning RabbitMQ Producers and Consumers.
* [stream_weaver](https://hex.pm/packages/stream_weaver) - Library for working with streams.
* [task_bunny ★79](https://github.com/shinyscorpion/task_bunny) - background processing application written in Elixir and uses RabbitMQ as a messaging backend.
* [toniq ★211](https://github.com/joakimk/toniq) - Simple and reliable background job library for Elixir.
* [verk ★328](https://github.com/edgurgel/verk) - Verk is a job processing system backed by Redis. It uses the same job definition of Sidekiq/Resque.
* [work_queue ★29 ⏳2Y](https://github.com/pragdave/work_queue) - Simple implementation of the hungry-consumer model in Elixir.


## Release Management
*Libraries and tools for release management.*

* [changex ★23 ⏳2Y](https://github.com/Gazler/changex) - Automated changelog generation from GIT logs.
* [distillery ★1074](https://github.com/bitwalker/distillery) - A pure Elixir implementation of release packaging functionality for the Erlang VM.
* [eliver ★21](https://github.com/glasnoster/eliver) - Interactive semantic versioning for Elixir packages.
* [exrm ★901](https://github.com/bitwalker/exrm) - Automatically generate a release for your Elixir project.
* [exrm_deb ★54](https://github.com/johnhamelink/exrm_deb) - Create a deb for your Elixir release with ease.
* [exrm_heroku ★42 ⏳2Y](https://github.com/epsanchezma/exrm-heroku) - Publish your Elixir releases to Heroku with ease.
* [exrm_rpm ★32 ⏳1Y](https://github.com/smpallen99/exrm-rpm) - Create a RPM for your Elixir release with ease.
* [mix_docker ★136](https://github.com/Recruitee/mix_docker) - Put your Elixir app production release inside minimal docker image.
* [relex ★56 ⏳3Y](https://github.com/yrashk/relex) - Erlang/Elixir Release Assembler.
* [renew ★18](https://github.com/Nebo15/renew) - Mix task to create mix projects that builds into Docker containers.

## REST and API
*Libraries and web tools for developing REST-ful APIs.*

* [accent ★1](https://github.com/sticksnleaves/accent) - Plug for handling the conversion of JSON API keys to different cases.
* [detergent ★46](https://github.com/devinus/detergent) - An emulsifying Erlang SOAP library.
* [detergentex ★40](https://github.com/r-icarus/detergentex) - Elixir binding to Detergent erlang library used to call WSDL/SOAP Services.
* [maru](https://github.com/falood/maru) - Elixir copy of grape for creating REST-like APIs.
* [mazurka ★14](https://github.com/exstruct/mazurka) - hypermedia api toolkit.
* [plug_rest ★31](https://github.com/christopheradams/plug_rest) - REST behaviour and Plug router for hypermedia web applications.
* [signaturex ★15 ⏳1Y](https://github.com/edgurgel/signaturex) - Simple key/secret based authentication for APIs.
* [urna ★75](https://github.com/meh/urna) - Urna is a simple DSL around cauldron to implement REST services.
* [versionary ★4](https://github.com/sticksnleaves/versionary) - API versioning for Elixir Plug and Phoenix.

## Security
*Libraries and tools regarding security.*

* [safetybox ★14 ⏳1Y](https://github.com/aforward/safetybox) - Security oriented helper functions for Elixir.
* [ssl_verify_fun ★26](https://github.com/deadtrickster/ssl_verify_fun.erl) - Collection of ssl verification functions for Erlang.

## Static Page Generation
*Tools and libraries for generating static websites and content.*

* [coil ★50 ⏳3Y](https://github.com/badosu/coil) - Minimalistic static content engine.
* [obelisk ★230](https://github.com/BennyHallett/obelisk) - Static blog and website generator.
* [serum ★40](https://github.com/Dalgona/Serum) - A simple static website generator written in Elixir.


## Statistics
*Libraries around the topic statistics.*

* [descriptive_statistics ★8](https://github.com/pusewicz/descriptive_statistics) - Descriptive Statistics for Elixir.
* [mtx ★15 ⏳1Y](https://github.com/synrc/mtx) - MTX supports front-end API for tracking Histogram, Meter, Counter, Gauge, Timing keys.
* [numerix ★43](https://github.com/safwank/Numerix) - A collection of useful mathematical functions with a slant towards statistics, linear algebra and machine learning.
* [statistics ★47](https://github.com/msharp/elixir-statistics) - Some basic statistical functions for Elixir.
* [wizard ★8 ⏳1Y](https://github.com/raywan/wizard) - Math and statistics functions for Elixir.

## Templating
*Libraries parsing and helping with templates*

* [bbmustache ★60](https://github.com/soranoba/bbmustache) - Binary pattern match Based Mustache template engine for Erlang/OTP.
* [eml ★74](https://github.com/zambal/eml) - Library for writing and manipulating (HTML) markup in Elixir.
* [exgen ★20](https://github.com/rwdaigle/exgen) - A templating library for quickly generating Elixir projects.
* [expug ★45](https://github.com/rstacruz/expug) - Pug templates for Elixir.
* [mustache ★13](https://github.com/schultyy/Mustache.ex) - Mustache templates for Elixir.
* [mustachex ★12 ⏳1Y](https://github.com/jui/mustachex) - Mustache for Elixir - Logic-less templates.
* [templates ★2 ⏳1Y](https://github.com/sugar-framework/templates) - Helper library for adding templating to web applications.

## Testing
*Libraries for testing codebases and generating test data.*

* [amrita ★203](https://github.com/josephwilk/amrita) - A polite, well mannered and thoroughly upstanding testing framework for Elixir.
* [apocryphal ★12](https://github.com/coryodaniel/apocryphal) - Swagger based document driven development for ExUnit.
* [blacksmith ★141](https://github.com/batate/blacksmith) - Data generation framework for Elixir.
* [blitzy ★59](https://github.com/benjamintanweihao/blitzy) - A simple HTTP load tester in Elixir.
* [bypass ★284](https://github.com/pspdfkit-labs/bypass) - Bypass provides a quick way to create a mock HTTP server with a custom plug.
* [chemistry ★3](https://github.com/genericlady/chemistry) - Testing Framework for Elixir.
* [cobertura_cover ★9 ⏳2Y](https://github.com/PSPDFKit-labs/cobertura_cover) - Writes a coverage.xml from `mix test --cover` file compatible with Jenkins' Cobertura plugin.
* [double ★14](https://github.com/sonerdy/double) - Create stub dependencies for testing without overwriting global modules.
* [ecto_it ★1 ⏳1Y](https://github.com/xerions/ecto_it) - Ecto plugin with default configuration for repos for testing different ecto plugins with databases.
* [efrisby ★18](https://github.com/FabioBatSilva/efrisby) - A REST API testing framework for erlang.
* [espec ★404](https://github.com/antonmi/espec) - BDD test framework for Elixir inspired by RSpec.
* [espec_phoenix ★85](https://github.com/antonmi/espec_phoenix) - ESpec for Phoenix web framework.
* [ex_machina ★678](https://github.com/thoughtbot/ex_machina) - Flexible test factories for Elixir. Works out of the box with Ecto and Ecto associations.
* [ex_parameterized ★6](https://github.com/KazuCocoa/ex_parameterized) - Simple macro for parameterized testing.
* [ex_spec ★78](https://github.com/drewolson/ex_spec) - BDD-like syntax for ExUnit.
* [ex_unit_fixtures ★8 ⏳1Y](https://github.com/obmarg/ex_unit_fixtures) - A library for defining modular dependencies for ExUnit tests.
* [ex_unit_notifier ★48](https://github.com/navinpeiris/ex_unit_notifier) - Desktop notifications for ExUnit.
* [excheck ★224](https://github.com/parroty/excheck) - Property-based testing library for Elixir (QuickCheck style).
* [exkorpion ★28](https://github.com/wesovilabs/exkorpion) - A BDD library for Elixir developers.
* [factory_girl_elixir ★36 ⏳2Y](https://github.com/sinetris/factory_girl_elixir) - Minimal implementation of Ruby's factory_girl in Elixir.
* [faker ★262](https://github.com/igas/faker) - Faker is a pure Elixir library for generating fake data.
* [faker_elixir ★91](https://github.com/GesJeremie/faker-elixir) - FakerElixir is an Elixir package that generates fake data for you.
* [fqc ★0 ⏳1Y](https://github.com/project-fifo/fqc) - FiFo Quickcheck helper, a set of helpers for running EQC.
* [gimei ★2 ⏳1Y](https://github.com/KazuCocoa/elixir-gimei) - Gimei is a pure Elixir library for generating Japanese fake data.
* [hound ★792](https://github.com/HashNuke/hound) - Elixir library for writing integration tests and browser automation.
* [hypermock ★22 ⏳1Y](https://github.com/stevegraham/hypermock) - HTTP request stubbing and expectation Elixir library.
* [ignorant ★9](https://github.com/campezzi/ignorant) - Partial `Map` comparison that ensures fields are present while ignoring their values.
* [katt ★42](https://github.com/for-GET/katt) - KATT (Klarna API Testing Tool) is an HTTP-based API testing tool for Erlang.
* [kovacs ★5 ⏳2Y](https://github.com/antp/kovacs) - A simple ExUnit test runner.
* [meck ★511](https://github.com/eproxus/meck) - A mocking library for Erlang.
* [mix_erlang_tasks ★9](https://github.com/alco/mix-erlang-tasks) - Common tasks for Erlang projects that use Mix.
* [mix_eunit ★6](https://github.com/dantswain/mix_eunit) - A Mix task to execute eunit tests.
* [mix_test_watch ★284](https://github.com/lpil/mix-test.watch) - Automatically run your Elixir project's tests each time you save a file.
* [mixunit ★2 ⏳2Y](https://github.com/talentdeficit/mixunit) - An EUnit task for Mix based projects.
* [mock ★221](https://github.com/jjh42/mock) - Mocking library for the Elixir language.
* [pavlov ★124 ⏳1Y](https://github.com/sproutapp/pavlov) - BDD framework for your Elixir projects.
* [plug_test_helpers ★8 ⏳2Y](https://github.com/xavier/plug_test_helpers) - A simple testing DSL for Plugs.
* [ponos ★97 ⏳1Y](https://github.com/klarna/ponos) - Ponos is an Erlang application that exposes a flexible load generator API.
* [power_assert ★142](https://github.com/ma2gedev/power_assert_ex) - Power Assert in Elixir. Shows evaluation results each expression.
* [proper ★537](https://github.com/manopapad/proper) - PropEr (PROPerty-based testing tool for ERlang) is a QuickCheck-inspired open-source property-based testing tool for Erlang.
* [setup_tag ★1 ⏳1Y](https://github.com/vic/setup_tag) - Easily mix and match functions marked with tags to setup your test context.
* [shouldi ★128](https://github.com/batate/shouldi) - Elixir testing libraries with nested contexts, superior readability, and ease of use.
* [test_that_json ★7](https://github.com/facto/test_that_json) - JSON assertions and helpers for your Elixir testing needs.
* [tuco_tuco ★56](https://github.com/stuart/tuco_tuco) - TucoTuco helps you test your web application by running a web browser and simulating user interaction with your application.
* [wallaby ★417](https://github.com/keathley/wallaby) - Wallaby helps test your web applications by simulating user interactions concurrently and manages browsers.
* [white_bread ★117](https://github.com/meadsteve/white-bread) - Story based BDD in Elixir using the gherkin syntax.

## Text and Numbers
*Libraries for parsing and manipulating text and numbers.*

* [abacus ★8](https://github.com/narrowtux/abacus) - Evaluate math terms in Elixir.
* [base58 ★9 ⏳2Y](https://github.com/jrdnull/base58) - Base58 encoding/decoding for Elixir.
* [base58check ★10 ⏳1Y](https://github.com/gjaldon/base58check) - Base58Check encoding/decoding for Bitcoin.
* [base62 ★12](https://github.com/igas/base62) - Base62 encoder/decoder in pure Elixir.
* [bencode ★10](https://github.com/gausby/bencode) - A Bencode encoder and decoder for Elixir. The decoder will return the checksum value of the info dictionary, if an info dictionary was found in the input.
* [bencoder ★4 ⏳2Y](https://github.com/alehander42/bencoder) - bencode in Elixir.
* [brcpfcnpj ★8 ⏳1Y](https://github.com/williamgueiros/Brcpfcnpj) - Number format and Validation for Brazilian documents (CPF/CNPJ).
* [calliope ★158](https://github.com/nurugger07/calliope) - An Elixir HAML parser.
* [ccc ★4](https://github.com/Joe-noh/ccc) - Character Code Converter.
* [chinese_translation ★67 ⏳2Y](https://github.com/tyrchen/chinese_translation) - Translate between traditional chinese and simplified chinese based on wikipedia data, and translate chinese words/characters to pinyin (or slug with or without tone).
* [cidr ★8](https://github.com/c-rack/cidr-elixir) - Classless Inter-Domain Routing (CIDR) for Elixir.
* [cirru_parser ★0 ⏳2Y](https://github.com/Cirru/parser.ex) - Cirru Parser in Elixir.
* [cldr ★1 ⏳3Y](https://github.com/magicienap/cldr) - cldr is a library to use information from CLDR data.
* [colorful ★2 ⏳2Y](https://github.com/Joe-noh/colorful) - Elixir macros to decorate characters on CUI.
* [colors ★5](https://github.com/lidashuang/colors) - Colors util written in Elixir.
* [convertat ★9 ⏳1Y](https://github.com/whatyouhide/convertat) - An Elixir library for converting from and to arbitrary bases.
* [curtail ★19](https://github.com/seankay/curtail) - HTML tag-safe string truncation.
* [custom_base ★6](https://github.com/igas/custom_base) - Allow you to make custom base conversion in Elixir.
* [decimal ★119](https://github.com/ericmj/decimal) - Arbitrary precision decimal arithmetic for Elixir.
* [dicer ★3 ⏳2Y](https://github.com/olhado/dicer) - A dice roller expression evaluator.
* [eden](https://github.com/jfacorro/Eden) - [EDN ★1466](https://github.com/edn-format/edn) encoder/decoder for Elixir.
* [elixilorem ★6 ⏳1Y](https://github.com/mgamini/elixilorem) - Lorem Ipsum generator for Elixir.
* [elixir-range-extras ★6 ⏳1Y](https://github.com/lnikkila/elixir-range-extras) - Elixir range utilities: constant-time random sampling and set operations.
* [elixir_bencode ★10 ⏳2Y](https://github.com/AntonFagerberg/elixir_bencode) - Bencode implemented in Elixir.
* [erldn](https://github.com/marianoguerra/erldn) - [EDN ★1466](https://github.com/edn-format/edn) format parser for the Erlang platform.
* [event_source_encoder ★3 ⏳2Y](https://github.com/chatgris/event_source_encoder) - Encode data into EventSource compliant data.
* [ex_brace_expansion ★3 ⏳2Y](https://github.com/gniquil/ex_brace_expansion) - Brace expansion, as known from sh/bash, in Elixir.
* [ex_rfc3966 ★0](https://github.com/marcelog/ex_rfc3966) - Elixir Tel URI parser compatible with RFC3966.
* [ex_rfc3986 ★5](https://github.com/marcelog/ex_rfc3986) - RFC3986 URI/URL parser.
* [ex_uc ★7](https://github.com/carturoch/ex_uc) - Extensible Units Converter for Elixir.
* [exmoji ★49](https://github.com/mroth/exmoji) - Emoji encoding Swiss Army knife for Elixir/Erlang.
* [expletive ★15](https://github.com/xavier/expletive) - Profanity filter library for Elixir.
* [expr ★5](https://github.com/Rob-bie/Expr) - An Elixir library for parsing and evaluating mathematical expressions.
* [faust ★19 ⏳1Y](https://github.com/jquadrin/faust) - Markov Text Generator for Elixir.
* [haikunator ★15](https://github.com/knrz/Haikunator) - Generate Heroku-like memorable random names to use in your apps or anywhere else.
* [hashids ★117](https://github.com/alco/hashids-elixir) - Hashids lets you obfuscate numerical identifiers via reversible mapping.
* [hexate ★16](https://github.com/rjsamson/hexate) - Simple module for Hex encoding / decoding in Elixir.
* [html_sanitize_ex ★69](https://github.com/rrrene/html_sanitize_ex) - HTML sanitizer for Elixir.
* [inet_cidr ★7](https://github.com/cobenian/inet_cidr) - Classless Inter-Domain Routing (CIDR) for Elixir that is compatible with :inet and supports both IPv4 and IPv6.
* [inflex ★102](https://github.com/nurugger07/inflex) - An Inflector library for Elixir.
* [kitsune ★9 ⏳2Y](https://github.com/edubkendo/kitsune) - An Elixir library for transforming the representation of data.
* [ltsvex ★9 ⏳1Y](https://github.com/ma2gedev/ltsvex) - LTSV parser implementation in Elixir.
* [mbcs ★11 ⏳1Y](https://github.com/woxtu/elixir-mbcs) - Wrapper for erlang-mbcs. This module provides functions for character encoding conversion.
* [mimetype_parser ★2 ⏳1Y](https://github.com/camshaft/mimetype_parser) - parse mimetypes.
* [monetized ★30](https://github.com/theocodes/monetized) - A lightweight solution for handling and storing money.
* [money ★109](https://github.com/liuggio/money) - Working with Money safer, easier, and fun, interpretation of the Fowler's Money pattern.
* [mt940 ★7](https://github.com/my-flow/mt940) - MT940 (standard structured SWIFT Customer Statement message) parser for Elixir.
* [neotomex ★40](https://github.com/jtmoulia/neotomex) - A [PEG](http://bford.info/packrat/) implementation with a pleasant Elixir DSL.
* [number ★67](https://github.com/danielberkompas/number) - Number is a pretentiously-named Elixir library which provides functions to convert numbers into a variety of different formats.
* [numero ★2](https://github.com/alisinabh/numero) - A micro library for converting non-english utf-8 digits in elixir.
* [palette ★1 ⏳2Y](https://github.com/lpil/palette) - A handy library for colouring strings in Elixir.
* [pinyin ★12](https://github.com/lidashuang/pinyin) - Chinese Pinyin lib for Elixir.
* [porterstemmer ★4 ⏳2Y](https://github.com/frpaulas/porterstemmer) - Porter Stemmer in Elixir.
* [pretty_hex ★4 ⏳2Y](https://github.com/polsab/pretty_hex) - A binary hex dumping library in Elixir.
* [quickrand ★15](https://github.com/okeuday/quickrand) - Quick Random Number Generation.
* [ref_inspector ★4](https://github.com/elixytics/ref_inspector) - Referer parser library in Elixir. Fetching info from URLs.
* [secure_random ★58](https://github.com/patricksrobertson/secure_random.ex) - Convenience library for random base64 strings modeled after my love for Ruby's SecureRandom.
* [sentient ★25](https://github.com/dantame/sentient) - Simple sentiment analysis based on the AFINN-111 wordlist.
* [simetric ★32](https://github.com/lexmag/simetric) - String similarity metrics for Elixir.
* [slime ★143](https://github.com/slime-lang/slime) - An Elixir library for rendering slim-like templates.
* [slugger ★69](https://github.com/h4cc/slugger) - Slugger can generate slugs from given strings that can be used in URLs or file names.
* [stemmer ★110](https://github.com/fredwu/stemmer) - An English (Porter2) stemming implementation in Elixir.
* [tau ★2 ⏳1Y](https://github.com/FranklinChen/tau) - Provide the famous mathematical constant, tau, τ = 6.2831....
* [tomlex ★25](https://github.com/zamith/tomlex) - A TOML parser for Elixir.
* [ua_inspector ★22](https://github.com/elixytics/ua_inspector) - User agent parser library like `piwik/device-detector`.
* [ua_parser2 ★1](https://github.com/nazipov/ua_parser2-elixir) - A port of ua-parser2 to Elixir. User agent parser library.
* [unit_fun ★13](https://github.com/meadsteve/unit_fun) - Attempt to add units to numbers in elixir to give some added type saftey when dealing with numeric quantities.
* [uuid ★154](https://github.com/zyro/elixir-uuid) - UUID generator and utilities for Elixir.
* [uuid_erl ★132](https://github.com/okeuday/uuid) - Erlang Native UUID Generation.
* [veritaserum ★31](https://github.com/uesteibar/veritaserum) - Sentiment analysis based on afinn-165, emojis and some enhancements.

## Third Party APIs
*Libraries for accessing third party APIs.*

* [airbax ★6](https://github.com/adjust/airbax) - Exception tracking from Elixir to Airbrake.
* [airbrake ★13](https://github.com/romul/airbrake-elixir) - An Elixir notifier for the Airbrake.
* [airbrakex ★14](https://github.com/fazibear/airbrakex) - Elixir client for the Airbrake service.
* [amazon_product_advertising_client ★21](https://github.com/zachgarwood/elixir-amazon-product-advertising-client) - Amazon Product Advertising API client for Elixir.
* [anilixir ★1](https://github.com/sotojuan/anilixir) - Elixir client for the Anilist API.
* [apns ★62](https://github.com/chvanikoff/apns4ex) - Apple Push Notifications Service client library for elixir.
* [apostle ★0 ⏳1Y](https://github.com/jamesotron/apostle-elixir) - Elixir client for Apostle.io.
* [asanaficator ★1 ⏳2Y](https://github.com/trenpixster/asanaficator) - Simple Elixir wrapper for the Asana API. Based on Tentacat.
* [assembla_api ★0 ⏳1Y](https://github.com/Assembla/ex_assembla_api) - Assembla API client for Elixir.
* [balalaika_bear ★4](https://github.com/ayrat555/balalaika_bear) - Simple VK API client for Elixir.
* [balanced ★1 ⏳2Y](https://github.com/bryanjos/balanced-elixir) - Balanced API Client for Elixir.
* [bandwidth ★0 ⏳1Y](https://github.com/bandwidthcom/elixir-bandwidth) - An Elixir client library for the Bandwidth Application Platform.
* [bing_translator ★6](https://github.com/ikeikeikeike/bing_translator) - A simple Elixir interface to Bing's translation API.
* [bitpay ★20 ⏳1Y](https://github.com/bitpay/elixir-client) - Elixir core library for connecting to bitpay.com.
* [cashier ★11](https://github.com/swelham/cashier) - Payment gateway offering a common interface into multiple payment providers.
* [cleverbot ★2](https://github.com/BlakeWilliams/Elixir-Cleverbot) - Simple implementation of the Cleverbot API in Elixir.
* [coinbase ★6 ⏳1Y](https://github.com/gregpardo/coinbase-elixir) - A unofficial Coinbase API v1 Client.
* [commerce_billing ★113](https://github.com/joshnuss/commerce_billing) - A payment-processing library for Elixir that supports multiple gateways (e.g. Bogus & Stripe).
* [currently ★4 ⏳1Y](https://github.com/chatgris/currently) - A tool to display cards currently assigns on Trello.
* [darkskyx ★2](https://github.com/techgaun/darkskyx) - A Darksky.com (formerly forecast.io) API client for Elixir.
* [digitalocean ★8](https://github.com/lukeed/elixir-digitalocean) - Elixir wrapper for the Digital Ocean API v2.
* [digoc](https://github.com/kevinmontuori/digoc) - Digital Ocean API v2 Elixir Client.
* [diplomat ★42](https://github.com/peburrows/diplomat) - A [Google Cloud Datastore](https://cloud.google.com/datastore/) client.
* [dnsimple ★28](https://github.com/dnsimple/dnsimple-elixir) - Elixir client for the DNSimple API v2.
* [docker ★10 ⏳1Y](https://github.com/hexedpackets/docker-elixir) - Elixir client for the Docker Remote API.
* [dockerex ★10](https://github.com/hisea/dockerex) - Lightweight Docker Remote API Client with SSL/TLS login/connection support.
* [dogstatsd ★12](https://github.com/adamkittelson/dogstatsd-elixir) - An Elixir client for [DogStatsd](https://www.datadoghq.com/).
* [dpd_client ★1 ⏳1Y](https://github.com/knewter/dpd_client) - An API client for the DPD service.
* [dropbox ★13 ⏳2Y](https://github.com/ammmir/elixir-dropbox) - Dropbox Core API client for Elixir.
* [dublin_bus_api ★0](https://github.com/carlo-colombo/dublin-bus-api) - Access to the Real Time Passenger Information (RTPI) for Dublin Bus services.
* [edgarex ★0 ⏳2Y](https://github.com/rozap/edgarex) - Elixir interface for fetching SEC filings from EDGAR.
* [elixir_authorizenet ★4](https://github.com/marcelog/elixir_authorizenet) - Unofficial client for the Authorize.Net merchant API.
* [elixir_ipfs_api ★13 ⏳1Y](https://github.com/zabirauf/elixir-ipfs-api) - IPFS (InterPlanetary File System) API client for Elixir.
* [elixirfm ★3](https://github.com/jrichocean/Elixirfm) - Last.fm API wrapper for Elixir.
* [elixtagram ★47](https://github.com/zensavona/elixtagram) - Instagram API client for Elixir.
* [ethereumex ★4](https://github.com/exthereum/ethereumex) - Elixir JSON-RPC client for the Ethereum blockchain.
* [everex ★8 ⏳2Y](https://github.com/jwarlander/everex) - Evernote API client for Elixir.
* [everyoneapi ★1 ⏳2Y](https://github.com/knewter/everyoneapi) - API Client for EveryoneAPI.com.
* [ex_codeship ★0](https://github.com/securingsincity/ex_codeship) - API Client for Codeship.
* [ex_gecko](https://github.com/Brightergy/ex_gecko) - Elixir SDK to communicate with Geckoboard's API.
* [ex_statsd ★70](https://github.com/CargoSense/ex_statsd) - A statsd client implementation for Elixir.
* [ex_twilio ★114](https://github.com/danielberkompas/ex_twilio) - Twilio API client for Elixir.
* [ex_twiml ★18](https://github.com/danielberkompas/ex_twiml) - Generate TwiML for your Twilio integration, right inside Elixir.
* [exdesk ★3 ⏳1Y](https://github.com/deadkarma/exdesk) - Elixir library for the Desk.com API.
* [exfacebook ★13](https://github.com/oivoodoo/exfacebook) - Facebook API, written in Elixir using similar methods like Ruby koala gem.
* [exgenius ★1 ⏳1Y](https://github.com/jeffweiss/exgenius) - Elixir library for the (undocumented) Rap Genius API.
* [exgravatar ★12 ⏳1Y](https://github.com/scrogson/exgravatar) - An Elixir module for generating Gravatar URLs.
* [exgrid ★7](https://github.com/bradleyd/exgrid) - interact with Sendgrid's API.
* [exjira ★5 ⏳2Y](https://github.com/mattweldon/exjira) - JIRA client library for Elixir.
* [exlingr ★1 ⏳2Y](https://github.com/mtwtkman/exlingr) - A Lingr client module.
* [exstagram ★9 ⏳1Y](https://github.com/arthurcolle/exstagram) - Elixir library for Instagram v1 API.
* [extripe ★15](https://github.com/princemaple/extripe) - Feature complete Stripe API wrapper.
* [extwitter ★247](https://github.com/parroty/extwitter) - Twitter client library for Elixir.
* [exurban ★1 ⏳2Y](https://github.com/oscar-lopez/exurban) - Elixir wrapper for UrbanAirship API.
* [facebook ★67](https://github.com/mweibel/facebook.ex) - Facebook Graph API Wrapper written in Elixir.
* [feedlex ★3 ⏳1Y](https://github.com/essenciary/feedlex) - Feedly RSS reader client for Elixir.
* [fluent_client ★3 ⏳2Y](https://github.com/trustatom-oss/elixir-fluent-client) - Minimalistic fluentd client.
* [forcex ★23](https://github.com/jeffweiss/forcex) - Elixir library for the Force.com REST API.
* [forecast_io ★6 ⏳1Y](https://github.com/r-icarus/forecast_io) - Simple wrapper for Forecast.IO API.
* [gcmex ★7 ⏳1Y](https://github.com/dukex/gcmex) - Google Cloud Messaging client library for elixir.
* [google_sheets ★26](https://github.com/GrandCru/GoogleSheets) - Elixir library for fetching and polling Google spreadsheet data in CSV format.
* [govtrack ★2](https://github.com/walterbm/govtrack-elixir) - A simple Elixir wrapper for the [govtrack.us](https://www.govtrack.us/developers) API.
* [hexoku ★7 ⏳2Y](https://github.com/JonGretar/Hexoku) - Heroku API client and Heroku Mix tasks for Elixir projects.
* [honeywell ★0](https://github.com/jeffutter/honeywell-elixir) - A client for the Honeywell Lyric, Round and Water Leak & Freeze Detector APIs.
* [kane ★33](https://github.com/peburrows/kane) - A [Google Cloud Pub/Sub](https://cloud.google.com/pubsub/overview) client.
* [keenex ★17](https://github.com/bryanjos/keenex) - A Keen.io API Client.
* [link_shrinkex ★6 ⏳2Y](https://github.com/jonahoffline/link_shrinkex) - Elixir library for creating short URLs using Google's URL Shortener API.
* [m2x](https://github.com/attm2x/m2x-elixir) - Elixir client for the AT&T M2X, a cloud-based fully managed time-series data storage service for network connected machine-to-machine (M2M) devices and the Internet of Things (IoT). ([Erlang Version ★2 ⏳1Y](https://github.com/attm2x/m2x-erlang)).
* [mailchimp ★18](https://github.com/duartejc/mailchimp) - A basic Elixir wrapper for version 3 of the MailChimp API.
* [mailgun ★152](https://github.com/chrismccord/mailgun) - Elixir Mailgun Client.
* [mandrill ★49 ⏳1Y](https://github.com/slogsdon/mandrill-elixir) - A Mandrill wrapper for Elixir.
* [marvel ★6 ⏳2Y](https://github.com/bryanjos/marvel) - CLI and Elixir API Client for the Marvel API.
* [mixpanel ★5](https://github.com/michihuber/mixpanel_ex) - An Elixir client for the Mixpanel HTTP API.
* [mixpanel_data_client ★3 ⏳1Y](https://github.com/jeregrine/mixpanel_data_client) - Client for interacting with the Mixpanel Data Export API.
* [mmExchangeRate ★0 ⏳2Y](https://github.com/Arkar-Aung/mmExchangeRate) - A simple exchange rate checker and calculator based on Central Bank of Myanmar Api.
* [nadia ★99](https://github.com/zhyu/nadia) - Telegram Bot API Wrapper written in Elixir.
* [omise ★4](https://github.com/teerawat1992/omise-elixir) - Omise client library for Elixir.
* [opbeat ★7](https://github.com/teodor-pripoae/opbeat) - Elixir client for Opbeat.
* [pagexduty](https://github.com/ride/pagexduty) - A Pagerduty client for Elixir.
* [parse_client ★4 ⏳2Y](https://github.com/elixircnx/parse_elixir_client) - Elixir client for the parse.com REST API.
* [parsex ★1 ⏳2Y](https://github.com/maarek/ParsEx) - ParsEx is an Elixir HTTP Client for communicating with Parse.com's Restful API.
* [particle ★1](https://github.com/jeffutter/particle-elixir) - An Elixir client for the Particle IoT platform's HTTP API.
* [pathway ★3 ⏳2Y](https://github.com/novabyte/pathway) - An Erlang/Elixir client for the [Trak.io](http://trak.io/) REST API.
* [pay ★14](https://github.com/era/pay) - An Elixir Lib to deal with Paypal and other payment solutions.
* [peatio_client ★3 ⏳1Y](https://github.com/peatio/peatio-client-elixir) - Peatio exchange project compatible API for Elixir.
* [pigeon ★114](https://github.com/codedge-llc/pigeon) - HTTP2-compliant wrapper for sending iOS and Android push notifications.
* [pocketex ★4 ⏳1Y](https://github.com/essenciary/pocketex) - Pocketex is an Elixir client for the Pocket read later service [getpocket.com](https://getpocket.com/).
* [pusher ★10](https://github.com/edgurgel/pusher) - Elixir library to access the Pusher REST API.
* [qiita_ex ★6 ⏳2Y](https://github.com/ma2gedev/qiita_ex) - A Qiita API v2 Interface for Elixir.
* [qiniu ★48](https://github.com/tony612/qiniu) - Qiniu SDK for Elixir.
* [random_user ★7](https://github.com/katgironpe/random_user) - An Elixir client for randomuser.me API.
* [reap ★3 ⏳2Y](https://github.com/Raynes/reap) - Reap is a simple Elixir library for working with the refheap API.
* [reddhl ★3 ⏳1Y](https://github.com/MonkeyIsNull/reddhl) - An headline and link puller for Reddit and its various subreddits.
* [redtube ★6 ⏳2Y](https://github.com/kkirsche/Redtube_Elixir) - Redtube API Wrapper written in Elixir.
* [reporter ★4](https://github.com/KazuCocoa/simple_app_reporter_ex) - Reporter is simple reporting App reviews library. Support AppStore and GooglePlay.
* [riemann ★33](https://github.com/koudelka/elixir-riemann) - A [Riemann](http://riemann.io/) client for Elixir.
* [semver ★2 ⏳1Y](https://github.com/lee-dohm/semver) - Utilities for working with semver.org-compliant version strings.
* [sendgrid ★26](https://github.com/alexgaribay/sendgrid_elixir) - Send composable, transactional emails with SendGrid.
* [sift_ex ★13](https://github.com/C404/sift_ex) - A Siftscience API Library for Elixir.
* [simplex ★3 ⏳1Y](https://github.com/adamkittelson/simplex) - An Elixir library for interacting with the Amazon SimpleDB API.
* [slack ★330](https://github.com/BlakeWilliams/Elixir-Slack) - Slack real time messaging client in Elixir.
* [sparkpost ★29](https://github.com/SparkPost/elixir-sparkpost) - An Elixir library for sending email using SparkPost.
* [statix ★70](https://github.com/lexmag/statix) - Expose app metrics in the StatsD protocol.
* [stripe ★19 ⏳2Y](https://github.com/SenecaSystems/stripe) - An Elixir Library wrapping Stripe's API.
* [stripity_stripe](https://github.com/robconery/stripity-stripe) - An Elixir Library for [Stripe](https://stripe.com/).
* [tagplay ★0 ⏳2Y](https://github.com/tagplay/elixir-tagplay) - Elixir client for Tagplay API.
* [telephonist ★24 ⏳1Y](https://github.com/danielberkompas/telephonist) - Elixir state machines for Twilio calls.
* [tentacat ★196](https://github.com/edgurgel/tentacat) - Simple Elixir wrapper for the GitHub API.
* [tg_client ★10](https://github.com/ccsteam/ex-telegram-client) - An Elixir wrapper which communicates with the Telegram-CLI.
* [traitify_elixir ★1 ⏳2Y](https://github.com/traitify/traitify_elixir) - An Elixir client library for the Traitify Developer's API.
* [ui_faces ★1](https://github.com/katgironpe/ui_faces) - UIFaces API client for Elixir applications.
* [unsplash-elixir ★2 ⏳1Y](https://github.com/waynehoover/unsplash-elixir) - An Elixir library for Unsplash.
* [xe ★17 ⏳1Y](https://github.com/paulodiniz/xe) - Real time conversion for currencies.
* [xend ★2](https://github.com/saulecabrera/xend) - Simple Elixir wrapper for Facebook's Send API.
* [zanox ★1 ⏳1Y](https://github.com/rafaelss/zanox) - Zanox API.

## Translations and Internationalizations
*Libraries providing translations or internationalizations.*

* [ecto_gettext](https://github.com/exbugs-elixir/ecto_gettext) - Library for localization Ecto validation errors with using Gettext.
* [exkanji ★8](https://github.com/ikeikeikeike/exkanji) - A Elixir library for translating between hiragana, katakana, romaji and kanji. It uses Mecab.
* [exromaji ★4](https://github.com/ikeikeikeike/exromaji) - A Elixir library for translating between hiragana, katakana and romaji.
* [linguist ★117 ⏳1Y](https://github.com/chrismccord/linguist) - Elixir Internationalization library.
* [parabaikElixirConverter ★1 ⏳2Y](https://github.com/Arkar-Aung/ParabaikElixirConverter) - ParabaikElixirConverter is just a Elixir version of Parabaik converter. It can convert from Unicode to Zawgyi-One and Zawgyi-One to Unicode vice versa.
* [trans ★64](https://github.com/belaustegui/trans) - A Elixir library to manage embedded translations into models leveraging PostgreSQL JSONB datatype.

## Utilities
*Utilities libraries.*

* [ar2ecto ★9 ⏳2Y](https://github.com/aforward/ar2ecto) - Ar2ecto is a set of mix tasks to help you migrate from ActiveRecord to Ecto.
* [crutches ★114](https://github.com/mykewould/crutches) - Utility library for Elixir, designed to complement the standard library bundled with the language.
* [deppie ★5](https://github.com/zackehh/deppie) - Elixir's coolest deprecation logger.
* [dot-notes ★2 ⏳1Y](https://github.com/zackehh/dot-notes-elixir) - Simple dot/bracket notation parsing/conversion for Maps/Lists.
* [dress ★36](https://github.com/veelenga/dress) - Cli app that makes your stdout fancy.
* [erlang-history ★433](https://github.com/ferd/erlang-history) - Hacks to add shell history to Erlang's shell.
* [erlsh ★47](https://github.com/proger/erlsh) - Family of functions and ports involving interacting with the system shell, paths and external programs.
* [erlware_commons ★155](https://github.com/erlware/erlware_commons) - Additional standard library for Erlang.
* [exjprop ★0](https://github.com/stocks29/exjprop) - Elixir library for reading Java properties files from various sources.
* [fitex ★1 ⏳1Y](https://github.com/timdeputter/FitEx) - FitEx is a Macro-Module which provides a bit of sugar for function definitions.
* [global ★2 ⏳2Y](https://github.com/mgwidmann/global) - Wrapper of the Erlang `:global` module.
* [mandrake ★6 ⏳1Y](https://github.com/mbasso/mandrake) - Mandrake is a functional programming library that bring something else magic in elixir.
* [mnemonix ★13](https://github.com/christhekeele/mnemonix) - A unified interface to key/value stores.
* [plasm ★58](https://github.com/facto/plasm) - Plasm is Ecto's composable query multitool, containing higher-level functions such as .count, .random, .first, .last, .find, .inserted_before, .inserted_after, etc.
* [pubsub ★23](https://github.com/simonewebdesign/elixir_pubsub) - A Publish-Subscribe utility library that implements a pub-sub mechanism to ease the burden of communication on the business logic processes.
* [quark](https://github.com/robot-overlord/quark) - A library for common functional programming idioms: combinators, currying, and partial application.
* [retry ★56](https://github.com/safwank/ElixirRetry) - Simple Elixir macros for linear retry, exponential backoff and wait with composable delays.
* [sips_downloader ★13](https://github.com/DavsX/SipsDownloader) - Elixir module for downloading the ElixirSips episodes and all other files.
* [sitemap ★34](https://github.com/ikeikeikeike/sitemap) - Sitemap is the easiest way to generate Sitemaps in Elixir.

## Validations
*Libraries and implementations for validation of data.*

* [bankster ★7](https://github.com/railsmechanic/bankster) - A IBAN account number and BIC validation library for Elixir.
* [exop ★24](https://github.com/madeinussr/exop) - A library that allows to encapsulate business logic and validate params with predefined contract.
* [jeaux ★5](https://github.com/zbarnes757/jeaux) - A light and easy schema validator.
* [shape ★7 ⏳2Y](https://github.com/prio/shape) - A data validation library for Elixir based on Prismatic Scheme.
* [uk_postcode ★7 ⏳2Y](https://github.com/KushalP/uk_postcode) - UK postcode parsing and validation library.
* [vex ★217](https://github.com/CargoSense/vex) - An extensible data validation library for Elixir.
* [voorhees ★39 ⏳1Y](https://github.com/danmcclain/voorhees) - A library for validating JSON responses.

## Version Control
*Working with version control like git, mercury, subversion ...*

* [gitex](https://github.com/awetzel/gitex) - Elixir implementation of the Git object storage, but with the goal to implement the same semantic with other storage and topics.

## Video
*Libraries for working with and manipulating video and multimedia.*

* [ffmpex ★29](https://github.com/talklittle/ffmpex) - FFmpeg command line wrapper.
* [silent_video ★3](https://github.com/talklittle/silent_video) - Convert GIFs and videos to silent videos, optimized for mobile playback.

## XML
*Libraries and implementations working with XML.*

* [erlsom ★169](https://github.com/willemdj/erlsom) - Erlsom is an Erlang library to parse (and generate) XML documents.
* [exmerl ★8](https://github.com/pwoolcoc/exmerl) - Elixir wrapper for xmerl.
* [exml ★17](https://github.com/expelledboy/exml) - Most simple Elixir wrapper for xmerl xpath.
* [exquery ★31](https://github.com/rozap/exquery) - A library for parsing HTML and querying elements within.
* [floki ★606](https://github.com/philss/floki) - A simple HTML parser that enables searching using CSS like selectors.
* [meeseeks ★41](https://github.com/mischov/meeseeks) - A library for parsing and extracting data from HTML and XML with CSS or XPath selectors.
* [quinn ★29](https://github.com/nhu313/Quinn) - XML parser for Elixir.
* [readability ★72](https://github.com/keepcosmos/readability) - Readability is for extracting and curating articles.
* [sweet_xml](https://github.com/awetzel/sweet_xml) - Query XML simply and effectively.
* [xml_builder ★57](https://github.com/joshnuss/xml_builder) - Elixir library for generating xml.
* [xmlrpc ★16](https://github.com/ewildgoose/elixir-xml_rpc) - Library for encoding and decoding XML-RPC for clients and servers.

## YAML
*Libraries and implementations working with YAML.*

* [fast_yaml ★11](https://github.com/processone/fast_yaml) - Fast YAML is an Erlang wrapper for libyaml "C" library.
* [yamerl ★116](https://github.com/yakaz/yamerl) - YAML 1.2 parser in Erlang.
* [yaml_elixir ★33](https://github.com/KamilLelonek/yaml-elixir) - Yaml parser for Elixir based on native Erlang implementation.
* [yomel ★5 ⏳1Y](https://github.com/Joe-noh/yomel) - libyaml interface for Elixir.

# Resources
Various resources, such as books, websites and articles, for improving your Elixir development skills and knowledge.

## Books
*Fantastic books and e-books.*

* [Elixir Cookbook](https://www.packtpub.com/application-development/elixir-cookbook) - This book is a set of recipes grouped by topic by Paulo A Pereira (2015).
* [Elixir in Action](https://www.manning.com/books/elixir-in-action) - A brief intro to the language followed by a more detailed look at building production-ready systems in Elixir by Saša Jurić (2015).
* [Erlang and Elixir for Imperative Programmers](https://leanpub.com/erlangandelixirforimperativeprogrammers) - Introduction to Erlang and Elixir in the context of functional concepts by Wolfgang Loder (2016).
* [Erlang in Anger](http://www.erlang-in-anger.com/) - This book intends to be a little guide about how to be the Erlang medic in a time of war by Fred Hebert (2014).
* [Functional Web Development with Elixir, OTP, and Phoenix](https://pragprog.com/book/lhelph/functional-web-development-with-elixir-otp-and-phoenix) - Open doors to powerful new techniques that will get you thinking about web development in fundamentally new ways (2017).
* [Getting Started - Elixir ★51](https://github.com/potatogopher/elixir-getting-started) - PDF, MOBI, and EPUB documents for Elixir's Getting Started tutorial (2016).
* [Introducing Elixir ](http://shop.oreilly.com/product/0636920030584.do) - A gentle introduction to the language, with lots of code examples and exercises by Simon St. Laurent and J. David Eisenberg (2013).
* [Metaprogramming Elixir: Write Less Code, Get More Done (and Have Fun!)](https://pragprog.com/book/cmelixir/metaprogramming-elixir) - Thorough explanation on how to exploit Elixir's metaprogramming capabilities to improve your Elixir coding by Chris McCord (2015).
* [Programming Elixir](https://pragprog.com/book/elixir/programming-elixir) - The book provides introduction to functional and concurrent programming with Elixir by Dave Thomas (2014).
* [Programming Phoenix](https://pragprog.com/book/phoenix/programming-phoenix) - Definitive guide to build web applications with the Phoenix framework by Chris McCord, José Valim and Bruce Tate (2015).
* [The Little Elixir & OTP Guidebook](https://www.manning.com/books/the-little-elixir-and-otp-guidebook) - A book for learning Elixir and OTP through small to medium-sized projects by Benjamin Tan Wei Hao (2014).
* [Études for Elixir](http://chimera.labs.oreilly.com/books/1234000001642) - A collection of exercises to program in Elixir by J. David Eisenberg (2013) ([Github Repo ★406](https://github.com/oreillymedia/etudes-for-elixir)).

## Community
*Getting in contact with the community via chat or mailinglist.*

* [#elixir-lang](http://webchat.freenode.net/?channels=elixir-lang) - The IRC Channel #elixir-lang on Freenode.
* [Elixir Forum](https://elixirforum.com/) - Community run discussion forums for all things Elixir.
* [elixir-lang-core](https://groups.google.com/d/forum/elixir-lang-core) - Mailinglist for Elixir Core development, use "talk" for questions and general discussions.
* [elixir-lang-talk](https://groups.google.com/d/forum/elixir-lang-talk) - Official Elixir Mailinglist for questions and discussions.
* [ElixirSlack](https://elixir-slackin.herokuapp.com/) - Elixir Slack Community.

## Editors
*Editors and IDEs useable for Elixir/Erlang*

* [Alchemist ★647](https://github.com/tonini/alchemist.el) - Elixir Tooling Integration Into Emacs.
* [Alchemist-Server ★155](https://github.com/tonini/alchemist-server) - Editor/IDE independent background server to inform about Elixir mix projects.
* [Alchemist.vim ★319](https://github.com/slashmili/alchemist.vim) - Elixir Tooling Integration Into Vim.
* [Atom](https://atom.io/packages/language-elixir) - Elixir language support for Atom.
* [atom-elixir ★378](https://github.com/msaraiva/atom-elixir) - An Atom package for Elixir.
* [atom-iex ★15](https://github.com/indiejames/atom-iex) - Run an IEx session in Atom.
* [elixir-tmbundle ★180](https://github.com/elixir-lang/elixir-tmbundle) - A TextMate and SublimeText bundle for Elixir.
* [elixir_generator ★7 ⏳1Y](https://github.com/jadercorrea/elixir_generator.vim) - Vim plugin to generate Elixir module and test files with one command.
* [ElixirSublime ★335](https://github.com/vishnevskiy/ElixirSublime) - Elixir plugin for SublimeText 3 that provides code completion and linting.
* [ilexir ★4](https://github.com/dm1try/ilexir) - IDE-like things for Elixir in Neovim.
* [intellij_elixir ★0](https://github.com/KronicDeth/intellij_elixir) - Elixir helpers for intellj-elixir, the Elixir plugin for JetBrains IDEs.
* [Jetbrains](http://plugins.jetbrains.com/plugin/7522) - Elixir for IntelliJ IDEA, RubyMine, WebStorm, PhpStorm, PyCharm, AppCode, Android Studio, 0xDBE.
* [Notepad++ ★3 ⏳2Y](https://github.com/Hades32/elixir-udl-npp) - Elixir syntax highlighting for Notepad++.
* [nvim ★11](https://github.com/dm1try/nvim) - Neovim host for writing plugins in Elixir.
* [phoenix-snippets ★4 ⏳1Y](https://github.com/phoenixframework-Brazil/phoenix-snippets) - Phoenix Snippets for Atom.
* [TextMate ★180](https://github.com/elixir-lang/elixir-tmbundle) - Elixir syntax highlighting for TextMate.
* [vim-elixir ★711](https://github.com/elixir-lang/vim-elixir) - Vim configuration files for Elixir.
* [vim-ex_test ★2 ⏳1Y](https://github.com/moofish32/vim-ex_test) - Vim test runner based on Thoughtbots vim-rspec.
* [vscode-elixir](https://github.com/mat-mcloughlin/vscode-elixir) - Elixir Support for Visual Studio Code.

## Newsletters
*Useful Elixir-related newsletters.*

* [Elixir Digest](http://elixirdigest.net) - A weekly newsletter with the latest articles on Elixir and Phoenix.
* [Elixir Radar](http://plataformatec.com.br/elixir-radar) - The "official" Elixir newsletter, published weekly via email by Plataformatec.
* [ElixirWeekly](https://elixirweekly.net) - The Elixir community newsletter, covering stuff you easily miss, shared on [ElixirStatus](http://elixirstatus.com) and the web.

## Other Awesome Lists
*Other amazingly awesome lists can be found at [jnv/lists](https://github.com/jnv/lists#lists-of-lists) or [bayandin/awesome-awesomeness ★18878](https://github.com/bayandin/awesome-awesomeness#awesome-awesomeness).*

* [Awesome Elixir by LibHunt](https://elixir.libhunt.com) - A curated list of awesome Elixir and Erlang packages and resources.
* [Awesome Erlang ★675](https://github.com/drobakowski/awesome-erlang) - A curated list of awesome Erlang libraries, resources and shiny things.
* [Erlang Bookmarks ★969](https://github.com/0xAX/erlang-bookmarks) - A collection of links for Erlang developers.

## Reading
*Elixir-releated reading materials.*

* [Discover Elixir & Phoenix](https://www.ludu.co/course/discover-elixir-phoenix/) - An online course that teaches both the Elixir language and the Phoenix framework.
* [Elixir Cheat-Sheet](http://media.pragprog.com/titles/elixir/ElixirCheat.pdf) - A Elixir cheat sheet, by Andy Hunt & Dave Thomas.
* [Elixir Functional Programming ★189](https://github.com/kblake/functional-programming) - Material to introduce functional programming using the Elixir language.
* [Elixir School](https://elixirschool.com/) - Lessons about the Elixir programming language.
* [The Little Schemer in Elixir ★311 ⏳1Y](https://github.com/jwhiteman/a-little-elixir-goes-a-long-way) - Exercises and algorithms from the Little Schemer book, ported to Elixir.
* [xElixir ★170](https://github.com/exercism/xelixir) - Exercism Exercises in Elixir.

## Screencasts
*Cool video tutorials.*

* [Confreaks (Elixir)](http://confreaks.tv/tags/40) - Elixir related conference talks.
* [Elixir for Programmers](https://codestool.coding-gnome.com/courses/elixir-for-programmers) - Functional, Parallel, Reliable (and fun!), taught by Dave Thomas.
* [Elixir Sips](http://elixirsips.com/) - Tiny screencasts for learning Elixir.
* [ExCasts](https://excasts.com) - Elixir and Phoenix screencasts for all skill levels.
* [LearnElixir.tv](https://www.learnelixir.tv/) - Beginner friendly, in-depth, step by step screencasts.
* [Meet Elixir](https://www.pluralsight.com/courses/meet-elixir) - Walk through some features and concepts of Elixir by José Valim.

## Styleguides
*Styleguides for ensuring consistency while coding.*

* [christopheradams/elixir_style_guide ★2105](https://github.com/christopheradams/elixir_style_guide) - A community-driven style guide for Elixir.
* [lexmag/elixir-style-guide ★170](https://github.com/lexmag/elixir-style-guide) - An opinionated Elixir style guide.
* [rrrene/elixir-style-guide](https://github.com/rrrene/elixir-style-guide) - Style guide checked by [Credo ★1866](https://github.com/rrrene/credo).

## Websites
*Useful Elixir-related websites.*

* [30 Days of Elixir ★1934](https://github.com/seven1m/30-days-of-elixir) - A walk through the Elixir language in 30 exercises.
* [Awesome Elixir @LibHunt](https://elixir.libhunt.com) - Your go-to Elixir Toolbox.
* [BEAM Community](http://beamcommunity.github.io/) - From distributed systems, to robust servers and language design on the Erlang VM.
* [Benjamin Tan - Learnings & Writings](http://benjamintan.io/blog/tags/elixir/) - A blog consisting of mostly Elixir posts.
* [Elixir China ★187](https://github.com/jw2013/elixir-china) - Chinese Elixir website [elixir-cn.com](http://elixir-cn.com/).
* [Elixir Examples](http://elixir-examples.github.io/) - A collection of small Elixir programming language examples.
* [Elixir Flashcards](https://elixircards.co.uk/) - Flashcards are a powerful way to improve your knowledge. Elixircards are hand crafted, professionally printed flashcards for levelling up your Elixir.
* [Elixir Fountain](https://soundcloud.com/elixirfountain) - A weekly podcast with news & interviews from around the Elixir community hosted by [Johnny Winn](https://twitter.com/johnny_rugger).
* [Elixir Github Repository ★10139](https://github.com/elixir-lang/elixir) - The project repository.
* [Elixir Github Wiki](https://github.com/elixir-lang/elixir/wiki) - The project's wiki, containing much useful information.
* [Elixir Job Board](http://jobs.elixirdose.com) - A job board for Elixir, and community of Elixir developers, [written using Phoenix ★68](https://github.com/rizafahmi/elixirjobs).
* [Elixir Playground](http://play.elixirbyexample.com/) - Try Elixir code in your browser.
* [Elixir Quiz](http://elixirquiz.github.io/) - Weekly programming problems to help you learn Elixir.
* [Elixir Recipes](http://elixir-recipes.github.io/) - Collection of patterns & solutions to common problems in Elixir.
* [Elixre](http://www.elixre.uk/) - An Elixir regular expression editor & tester.
* [Erlang Patterns](http://www.erlangpatterns.org/) - Unlike traditional software design pattern efforts, which tend to emphasize the importance of code reuse, this project emphasizes patterns that feel good to humans.
* [Hashrocket Today I Learned - Elixir](https://til.hashrocket.com/elixir) - Small posts about Elixir from the team at Hashrocket.
* [How I start - Elixir](http://howistart.org/posts/elixir/1) - Explanation and intro to Elixir by José Valim.
* [Learning Elixir](http://learningelixir.joekain.com/) - A blog about a Professional Software Engineer learning Elixir.

# Contributing
Please see [CONTRIBUTING](https://github.com/h4cc/awesome-elixir/blob/master/.github/CONTRIBUTING.md) for details.
---
<p align="center">
	This list is a copy of <a href="https://github.com/h4cc/awesome-elixir">h4cc/awesome-elixir</a> with ranks
</p>
