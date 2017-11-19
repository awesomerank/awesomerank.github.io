---
layout: default
title: Awesome Rank for veelenga/awesome-crystal
---

<p align="center">
	This list is a copy of <a href="https://github.com/veelenga/awesome-crystal">veelenga/awesome-crystal</a> with ranks
</p>
---
# Awesome Crystal
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg) ★69735](https://github.com/sindresorhus/awesome)
[![Build Status](https://api.travis-ci.org/veelenga/awesome-crystal.svg)](https://travis-ci.org/veelenga/awesome-crystal)

A curated list of awesome Crystal code and resources. Inspired by [awesome](https://github.com/sindresorhus/awesome) and [awesome-awesomeness ★20083](https://github.com/bayandin/awesome-awesomeness).
The goal is to have projects mostly stable and useful for the community.

Search [Crystal Shards](https://crystalshards.xyz) or follow announcements [Crystal [ANN]](https://crystal-ann.com) for more.

Contributions are welcome. Please take a quick look at the [contribution guidelines](https://github.com/veelenga/awesome-crystal/blob/master/.github/CONTRIBUTING.md) first.

* [Awesome Crystal](#awesome-crystal)
  * [Algorithms and Data structures](#algorithms-and-data-structures)
  * [Api Builders](#api-builders)
  * [C Bindings](#c-bindings)
  * [Caching](#caching)
  * [Cli Builders](#cli-builders)
  * [Cli Utils](#cli-utils)
  * [Configuration](#configuration)
  * [Converters](#converters)
  * [Data Generators](#data-generators)
  * [Database Drivers/Clients](#database-driversclients)
  * [Database Tools](#database-tools)
  * [Development Tools](#development-tools)
  * [Email](#email)
  * [Environment Management](#environment-management)
  * [Examples and funny stuff](#examples-and-funny-stuff)
  * [Feature Flipping](#feature-flipping)
  * [Framework Components](#framework-components)
  * [Game Development](#game-development)
  * [HTML/XML parsing](#htmlxml-parsing)
  * [HTTP](#http)
  * [Image Processing](#image-processing)
  * [Implementations/Compilers](#implementationscompilers)
  * [Logging and monitoring](#logging-and-monitoring)
  * [Machine Learning](#machine-learning)
  * [Markdown/Text Processors](#markdowntext-processors)
  * [Misc](#misc)
  * [Networking](#networking)
  * [ORM/ODM Extensions](#ormodm-extensions)
  * [Package Management](#package-management)
  * [Processes and Threads](#processes-and-threads)
  * [Project Generators](#project-generators)
  * [Queue](#queue)
  * [Routing](#routing)
  * [Scheduling](#scheduling)
  * [Science and Data analysis](#science-and-data-analysis)
  * [Search](#search)
  * [Task management](#task-management)
  * [Template Engine](#template-engine)
  * [Testing](#testing)
  * [Third-party APIs](#third-party-apis)
  * [Virtualization](#virtualization)
  * [Web Frameworks](#web-frameworks)
  * [Web Servers](#web-servers)
* [Community](#community)
* [Resources](#resources)
  * [Official Documentation Translations](#official-documentation-translations)
* [Services and Apps](#services-and-apps)
* [Tools](#tools)
  * [DevOps](#devops)
  * [Editor Plugins](#editor-plugins)
  * [Shell Plugins](#shell-plugins)

## Algorithms and Data structures
 * [aho_corasick ★1 ⏳1Y](https://github.com/chenkovsky/aho_corasick) - AhoCorasick algorithm
 * [crystal-diff ★17 ⏳1Y](https://github.com/MakeNowJust/crystal-diff) - A Crystal sequence differencing implementation
 * [crystal-linked-list ★5](https://github.com/abvdasker/crystal-linked-list) - Implementation of Linked List
 * [crystaledge ★6](https://github.com/unn4m3d/crystaledge) - A pure Vector Math library
 * [crystalg ★11](https://github.com/TobiasGSmollett/crystalg) - A Generic Algorithm Library
 * [crystalline ★76](https://github.com/jtomschroeder/crystalline) - A collection of containers and algorithms
 * [delimiter_tree ★7](https://github.com/drujensen/delimiter_tree) - A tree structure that is built using a delimiter
 * [edits.cr ★5](https://github.com/tcrouch/edits.cr) - Collection of edit distance algorithms
 * [hash_ring ★0](https://github.com/TobiasGSmollett/hash_ring) - An Implementation of Consistent Hash Ring
 * [markov ★7](https://github.com/mccallofthewild/markov) - Build Markov Chains and run Markov Processes
 * [miller_rabin ★0 ⏳1Y](https://github.com/kuende/miller_rabin) - Implements [Miller-Rabin](https://en.wikibooks.org/wiki/Algorithm_Implementation/Mathematics/Primality_Testing) algorithm to check if a number is prime
 * [multiset.cr ★1](https://github.com/tcrouch/multiset.cr) - Implementation of a multiset
 * [murmur3 ★2 ⏳1Y](https://github.com/kuende/murmur3) - Implementation of Murmur3 hash algorithm used by Cassandra
 * [radix ★30](https://github.com/luislavena/radix) - Radix Tree implementation
 * [ternary_search_tree ★1](https://github.com/johnjansen/ternary_search_tree) - Ternary Search Tree
 * [text ★13](https://github.com/johnjansen/text) - A collection of text algorithms

## Api Builders
 * [kemal-rest-api ★15](https://github.com/blocknotes/kemal-rest-api) - A library to create RESTful API with Kemal

## C bindings
 * [asound-cr ★3](https://github.com/TamasSzekeres/asound-cr) - Bindings for ALSA/libasound
 * [cairo-cr ★3](https://github.com/TamasSzekeres/cairo-cr) - Bindings for [Cairo](https://cairographics.org/) graphics library
 * [clang.cr ★11](https://github.com/ysbaddaden/clang.cr) - Libclang bindings
 * [crass ★7](https://github.com/vonKingsley/crass) - Bindings for libsass
 * [crt.cr ★13](https://github.com/maiha/crt.cr) - Bindings for libncursesw and crt
 * [crystal-gsl ★10](https://github.com/ruivieira/crystal-gsl) - GNU Scientific Library bindings
 * [curl-crystal ★4](https://github.com/blocknotes/curl-crystal) - Bindings for [libcurl](https://curl.haxx.se/libcurl/)
 * [duktape.cr](https://github.com/jessedoyle/duktape.cr) - Bindings for the [Duktape ★2942](https://github.com/svaarala/duktape) javascript engine
 * [gphoto2.cr ★8](https://github.com/Sija/gphoto2.cr) - Bindings for the [libgphoto2](http://www.gphoto.org/) library
 * [icu.cr ★2](https://github.com/olbat/icu.cr) - Bindings for the [ICU](http://site.icu-project.org/) library
 * [java.cr ★8](https://github.com/ysbaddaden/java.cr) - Java Native Interface (JNI) bindings (and generator)
 * [libnotify.cr ★11 ⏳1Y](https://github.com/splattael/libnotify.cr) - Bindings for Libnotify
 * [libui.cr](https://github.com/Fusion/libui.cr) - Bindings for [libui ★4682](https://github.com/andlabs/libui)
 * [pcap.cr ★13](https://github.com/maiha/pcap.cr) - Bindings for libpcap
 * [posix ★18](https://github.com/ysbaddaden/posix) - POSIX/C bindings
 * [soundfile ★1](https://github.com/mjago/soundfile) - Bindings for [libsndfile](http://www.mega-nerd.com/libsndfile/) library
 * [ssh2.cr ★24](https://github.com/datanoise/ssh2.cr) - Bindings for libssh2 library
 * [termbox-crystal](https://github.com/andrewsuzuki/termbox-crystal) - Bindings and extension library for [termbox ★1135](https://github.com/nsf/termbox) (terminal UI library)
 * [x11-cr ★2](https://github.com/TamasSzekeres/x11-cr) - X11 bindings

## Caching
 * [bloom_filter ★17](https://github.com/crystal-community/bloom_filter) - Implementation of Bloom filter
 * [bojack ★57](https://github.com/marceloboeira/bojack) - A non-reliable in-memory key-value store
 * [cache-hash ★11](https://github.com/samueleaton/cache-hash) - A key/value store where entries expire after a specified interval
 * [crystal-memcached ★21](https://github.com/comandeo/crystal-memcached) - Implementation of a memcached client
 * [Nuummite ★9](https://github.com/CodeSteak/Nuummite) - A tiny persistent embedded key-value store

## Cli Builders
 * [admiral ★35](https://github.com/jwaldrip/admiral.cr) - A robust DSL for writing command line interfaces
 * [cli ★47](https://github.com/mosop/cli) - Library for building command-line interface applications
 * [clim ★19](https://github.com/at-grandpa/clim) - Slim command line interface builder
 * [commander ★67](https://github.com/mrrooijen/commander) - Command-line interface builder
 * [completion ★42](https://github.com/f/completion) - Easy command line completion engine
 * [optarg ★11](https://github.com/mosop/optarg) - Yet another library for parsing command-line options and arguments

## Cli Utils
 * [dl ★1](https://github.com/creadone/dl) - Simple utility for download files by URLs from list
 * [noteesh ★1](https://github.com/arandilopez/noteesh) - Notes and Todo list in command line
 * [progress ★90](https://github.com/askn/progress) - [==..] Progress bar
 * [progress_bar.cr ★1](https://github.com/TPei/progress_bar.cr) - A simple and customizable progress bar
 * [spinner ★38](https://github.com/askn/spinner) - Terminal Spinner
 * [terminal_table.cr ★17 ⏳1Y](https://github.com/benoist/terminal_table.cr) - Simple ASCII table generator
 * [todo ★2](https://github.com/Nephos/todo) - Todo list working in command line

## Configuration
 * [cr-dotenv ★25](https://github.com/gdotdesign/cr-dotenv) - Loads .env file
 * [crystal-toml ★27](https://github.com/manastech/crystal-toml) - TOML parser
 * [dockerfile.cr ★1 ⏳1Y](https://github.com/keplersj/dockerfile.cr) - Dockerfile Parsing Library
 * [zq ★2](https://github.com/colstrom/zq) - Command-line ZPL processor

## Converters
 * [human_file_size.cr ★0](https://github.com/johnjansen/human_file_size.cr) - JSON & YAML mapping converter for human file sizes in serialized data
 * [moola](https://github.com/dorkrawk/moola) - Library for dealing with money and conversion (inspired by [RubyMoney ★1851](https://github.com/RubyMoney/money))
 * [ms ★12 ⏳1Y](https://github.com/SuperPaintman/ms) - Library to easily convert various time formats to milliseconds and milliseconds to human readable format
 * [sass.cr](https://github.com/straight-shoota/sass.cr) - Compile SASS/SCSS to CSS ([libsass ★3618](https://github.com/sass/libsass) binding)
 * [time_format.cr ★0](https://github.com/vladfaust/time_format.cr) - Convert time in human readable format with ease
 * [turkish-number ★6](https://github.com/izniburak/turkish-number) - Turn integers into the Turkish words
 * [wkhtmltopdf-crystal ★6](https://github.com/blocknotes/wkhtmltopdf-crystal) - Bindings / wrapper for libwkhtmltox (HTML to PDF / image converter)

## Data Generators
 * [faker ★73](https://github.com/askn/faker) - A library for generating fake data
 * [hashids.cr ★20](https://github.com/splattael/hashids.cr) - A library to generate YouTube-like ids from one or many numbers

## Database Drivers/Clients
 * [arangocr ★11](https://github.com/solisoft/arangocr) - ArangoDB client
 * [crystal-db ★85](https://github.com/crystal-lang/crystal-db) - Common db api
 * [crystal-monetdb-libmapi ★1](https://github.com/puppetpies/crystal-monetdb-libmapi) - Bindings for MonetDB
 * [crystal-mysql ★33](https://github.com/crystal-lang/crystal-mysql) - MySQL connector for Crystal
 * [crystal-pg ★228](https://github.com/will/crystal-pg) - A Postgres driver
 * [crystal-redis ★196](https://github.com/stefanwille/crystal-redis) - Full featured Redis client
 * [crystal-sqlite3 ★43](https://github.com/crystal-lang/crystal-sqlite3) - SQLite3 bindings
 * [eventql-crystal ★6](https://github.com/measurechina/eventql-crystal) - EventQL driver
 * [leveldb ★18](https://github.com/crystal-community/leveldb) - Crystal bindings for LevelDB
 * [mongo.cr ★64](https://github.com/datanoise/mongo.cr) - Binding for MongoDB C driver
 * [rethinkdb.cr ★24](https://github.com/CubosTecnologia/rethinkdb.cr) - RethinkDB Driver
 * [rocksdb.cr ★13](https://github.com/maiha/rocksdb.cr) - RocksDB client

## Database Tools
 * [crecto-admin ★12](https://github.com/Crecto/crecto-admin) - Admin dashboard for Crecto and your database
 * [micrate ★73](https://github.com/juanedi/micrate) - Database migration tool

## Development Tools
 * [guardian ★193](https://github.com/f/guardian) - File change watcher for Crystal and Non-Crystal libs
 * [kemal-watcher ★5](https://github.com/faustinoaq/kemal-watcher) - Kemal plugin to watch files and live-reload the browser
 * [sentry ★88](https://github.com/samueleaton/sentry) - Watches src files, rebuilds/reruns application on file changes
 * [sentry-run ★2](https://github.com/faustinoaq/sentry-run) - Reload code changes using Sentry.run
 * [Warden ★6](https://github.com/diggersheep/warden) - Watches files, run command and a git command if succeed on file changes
 * [watcher ★4](https://github.com/faustinoaq/watcher) - Watch file changes using File.stat

## Email
 * [crystal-email ★37](https://github.com/arcage/crystal-email) - Simple e-mail sending library
 * [CrystalEmail ★12](https://github.com/Nephos/CrystalEmail) - A RFC compliant Email validator
 * [devmail ★10](https://github.com/tijn/devmail) - A combined SMTP/POP3-server with volatile mail storage
 * [sendgrid.cr ★5](https://github.com/dlanileonardo/sendgrid.cr) - Simple Sendgrid Client

## Environment Management
 * [asdf-crystal ★6](https://github.com/marciogm/asdf-crystal) - Plugin for asdf version manager
 * [crenv ★140](https://github.com/pine/crenv) - Crystal version manager
 * [rcm.cr ★18](https://github.com/maiha/rcm.cr) - Redis Cluster Manager

## Examples and funny stuff
 * [breakout.cr ★6](https://github.com/petoem/breakout.cr) - Breakout game written using crsfml
 * [chuck-norris-holy-quotes ★4](https://github.com/codenoid/chuck-norris-holy-quotes) - Chuck Norris holy quotes
 * [clamp ★1](https://github.com/johnjansen/clamp) - Clamp any Comparable
 * [crsfml-examples ★31](https://github.com/oprypin/crsfml-examples) - Simple games made with CrSFML
 * [crystal-benchmarks-game ★50](https://github.com/kostya/crystal-benchmarks-game) - The Computer Language Benchmarks Game
 * [crystal-by-example ★257](https://github.com/askn/crystal-by-example) - Crystal By Example
 * [Crystal-Maze ★11](https://github.com/Demonstrandum/Crystal-Maze) - A* Path finding for PNG mazes
 * [crystal-mysql-crud-example ★0](https://github.com/codenoid/crystal-mysql-crud-example) - Crystal MySQL CRUD example
 * [crystal-patterns ★63](https://github.com/crystal-community/crystal-patterns) - Examples of GOF patters
 * [crystalized_ruby ★106 ⏳1Y](https://github.com/phoffer/crystalized_ruby) - Native Ruby extensions written in Crystal
 * [exercism-crystal ★34](https://github.com/exercism/crystal) - Exercism exercises
 * [jihantoro-cr-mysql ★0](https://github.com/codenoid/jihantoro-cr-mysql) - Crystal MySQL from scratch sample app
 * [jihantoro.sd ★0](https://github.com/codenoid/jihantoro.sd) - Crystal & Kemal version of Serdar Dogruyol blog
 * [kemal-chat ★34 ⏳1Y](https://github.com/sdogruyol/kemal-chat) - Build realtime applications with Kemal and WebSocket
 * [kemal-heroku-example ★2](https://github.com/cagataycali/kemal-heroku-example) - This repository shows, how you can publish your open source apps which powered kemal framework publish as heroku app in seconds
 * [kemal-mysql-blog ★2](https://github.com/codenoid/kemal-mysql-blog) - Blog written with Crystal, Kemal and MySQL
 * [kemal-react-chat ★53 ⏳1Y](https://github.com/f/kemal-react-chat) - Build Realtime Web applications with Kemal and React
 * [lattice-core-card-game ★140](https://github.com/jasonl99/card_game) - A demo web app for (WebSocket-based) lattice-core
 * [medley ★9 ⏳1Y](https://github.com/jwoertink/medley) - A mixture of music related methods
 * [os-crystal ★32 ⏳1Y](https://github.com/lbguilherme/os-crystal) - x86 Kernel implemented in Crystal
 * [realtime-todo-app ★12 ⏳1Y](https://github.com/Angarsk8/realtime-todo-app) - Realtime Todo application developed with Kemal, Websockets, React, ES2015 and PostgreSQL
 * [rocky ★80](https://github.com/codingphasedotcom/rocky) - React Over Crystal Kemal and Yarn
 * [try.cr ★15](https://github.com/maiha/try.cr) - Try monad

## Feature Flipping
 * [flipper ★7](https://github.com/metaware/flipper) - Feature flipping/flags/rollouts. Supports multiple backends

## Framework Components
 * [cr-melon ★5](https://github.com/gdotdesign/cr-melon) - Class based Http APIs
 * [Crystal-DI ★11](https://github.com/funk-yourself/crystal-di) - Lightweight DI Container
 * [crystal-mime ★17](https://github.com/spalger/crystal-mime) - Mimetypes for Crystal
 * [graphql-crystal ★58](https://github.com/ziprandom/graphql-crystal) - [Graphql](http://graphql.org) implementation
 * [kave ★17](https://github.com/jwoertink/kave) - Kemal API Version Extension
 * [kemal-auth-token ★16](https://github.com/akwiatkowski/kemal-auth-token) - Kemal middleware to authentication via HTTP header token using JWT
 * [kemal-monetdb ★0 ⏳1Y](https://github.com/puppetpies/kemal-monetdb) - MonetDB Data connection for Kemal
 * [kemal-session ★22](https://github.com/kemalcr/kemal-session) - Session handler for Kemal
 * [mime-types.cr ★6](https://github.com/jwaldrip/mime-types.cr) - A port of the Ruby MIME-types library
 * [multi-auth ★24](https://github.com/msa7/multi_auth) - Standardized multi-provider OAuth2 authentication (inspired by omniauth)
 * [phoenix.cr ★18](https://github.com/dtcristo/phoenix.cr) - Phoenix Channels client
 * [request_id ★0](https://github.com/SuperPaintman/request-id) - Middleware for generates / pick up a unique request ID for Crystal servers
 * [response_time ★6](https://github.com/SuperPaintman/response-time) - Response time for Crystal servers (pure http server, kemal, etc.)
 * [spec-kemal ★30](https://github.com/kemalcr/spec-kemal) - Easy testing for Kemal
 * [tele-broadcast.cr ★0](https://github.com/vladfaust/tele-broadcast.cr) - Broadcasting module for tele.cr

## Game Development
 * [CrSFML ★153](https://github.com/oprypin/crsfml) - Bindings to [SFML](https://www.sfml-dev.org/) multimedia/game library
 * [crystal-chipmunk ★15](https://github.com/oprypin/crystal-chipmunk) - Bindings for [Chipmunk](http://chipmunk-physics.net/), a fast and lightweight 2D game physics library
 * [glove ★34](https://github.com/ddfreyne/glove) - A library for gaming development
 * [inari ★9](https://github.com/ddfreyne/inari) - A collection of games using Glove as the game engine
 * [mos_game ★9](https://github.com/bararchy/mos_game) - Mini Offline Singleplayer game

## HTML/XML Parsing
 * [crystagiri](https://github.com/madeindjs/Crystagiri) - An Html Reader / parser like [Nokogiri ★4599](https://github.com/sparklemotion/nokogiri) Ruby gem
 * [gumbo-crystal](https://github.com/blocknotes/gumbo-crystal) - Bindings for [Gumbo ★4147](https://github.com/google/gumbo-parser), an HTML5 parsing library made by Google
 * [hq.cr ★5](https://github.com/maiha/hq.cr) - Simple wrapper for crystal-xml
 * [modest ★30](https://github.com/kostya/modest) - CSS selectors for HTML5 Parser myhtml
 * [myhtml ★29](https://github.com/kostya/myhtml) - Fast HTML5 Parser

## HTTP
 * [cossack ★67](https://github.com/crystal-community/cossack) - Simple flexible HTTP client
 * [crest ★19](https://github.com/mamantoha/crest) - Simple HTTP and REST client, inspired by the Ruby's RestClient gem
 * [crul ★94](https://github.com/porras/crul) - Command line HTTP client
 * [cryload ★107](https://github.com/sdogruyol/cryload) - HTTP benchmarking tool
 * [halite ★28](https://github.com/icyleaf/halite) - Yet another simple HTTP and REST client with a chainable API, built-in sessions and timeouts
 * [helmet ★14](https://github.com/EvanHahn/crystal-helmet) - Set security-related HTTP headers
 * [http-multiserver.cr ★5](https://github.com/vladfaust/http-multiserver.cr) - Mounting multiple servers via routes (a.k.a. URL mapping)
 * [http-protection ★32](https://github.com/rogeriozambon/http-protection) - Protection against typical web attacks
 * [http2 ★43](https://github.com/ysbaddaden/http2) - HTTP/2 Protocol Implementation
 * [http_distributor ★1](https://github.com/Nephos/http_distributor) - HTTP server which allows sneaky http requests
 * [http_parser.cr](https://github.com/kostya/http_parser.cr) - Wrapper for [Http Parser lib ★3596](https://github.com/nodejs/http-parser)
 * [keyer_cr ★0](https://github.com/danielpclark/keyer_cr) - Adds HTTP GET/POST parameter parsing as a Hash-like object
 * [resp-crystal ★4](https://github.com/soveran/resp-crystal) - Lightweight RESP client

## Image processing
 * [magickwand-crystal ★24](https://github.com/blocknotes/magickwand-crystal) - Bindings for [MagickWand](https://www.imagemagick.org/script/magick-wand.php), the C interface for ImageMagick processing libraries
 * [stumpy_gif ★7](https://github.com/stumpycr/stumpy_gif) - Write (animated) GIF images
 * [stumpy_png ★31](https://github.com/stumpycr/stumpy_png) - Read and write PNG images

## Implementations/Compilers
 * [charly](https://github.com/charly-lang) - Charly Programming Language
 * [cltk ★39](https://github.com/ziprandom/cltk) - A crystal port of the Ruby Language Toolkit
 * [cppize ★19](https://github.com/unn4m3d/cppize) - Crystal-to-C++ transpiler
 * [crisp ★17](https://github.com/rhysd/Crisp) - Lisp dialect implemented with Crystal
 * [crow ★38](https://github.com/geppetto-apps/crow) - Transpile/compile Crystal to [Flow](https://flow.org/)
 * [myst-lang](https://github.com/myst-lang/) - A practical, dynamic language designed to be written and understood as easily and efficiently as possible
 * [NuummiteOS ★45](https://github.com/TheKernelCorp/NuummiteOS) - An OS written in Crystal as a Proof of Concept
 * [zir ★14](https://github.com/tbrand/zir) - Realizes to write macros in any scripts into any languages

## Logging and monitoring
 * [crometheus](https://gitlab.com/ezrast/crometheus) - A [Prometheus](https://prometheus.io/) client library
 * [crystal-logreader ★0](https://github.com/arcage/crystal-logreader) - Tailing log file
 * [fluent-logger-crystal ★2](https://github.com/TobiasGSmollett/fluent-logger-crystal) - A structured logger for [Fluentd](https://www.fluentd.org/)
 * [katip ★19](https://github.com/guvencenanguvenal/katip) - JSONbase logger
 * [statsd.cr](https://github.com/miketheman/statsd.cr) - [Statsd ★12203](https://github.com/etsy/statsd) client library
 * [syslog.cr ★5](https://github.com/comandeo/syslog.cr) - Implementation of Syslog client

## Machine Learning
 * [ai4cr ★4](https://github.com/drhuffman12/ai4cr) - Artificial Intelligence (based on https://github.com/SergioFierens/ai4r)
 * [crystal-fann ★55](https://github.com/NeuraLegion/crystal-fann) - FANN (Fast Artifical Neural Network) binding
 * [crystal-learn ★27](https://github.com/pbrusco/crystal-learn) - Sklearn-like machine-learning library
 * [grey_matter ★6](https://github.com/dorkrawk/grey_matter) - A basic artificial neural network library
 * [tensorflow.cr](https://github.com/fazibear/tensorflow.cr) - Bindings for [TensorFlow ★75642](https://github.com/tensorflow/tensorflow)

## Markdown/Text Processors
 * [html-pipeline ★5](https://github.com/huacnlee/html-pipeline) - HTML processing filters and utilities
 * [markd ★7](https://github.com/icyleaf/markd) - Yet another markdown parser built for speed, Compliant to CommonMark specification
 * [remarkdown ★5](https://github.com/huacnlee/remarkdown) - GFM for Crystal

## Misc
 * [aasm.cr ★20](https://github.com/veelenga/aasm.cr) - Easy to use finite state machine for Crystal classes
 * [accord ★14 ⏳1Y](https://github.com/neovintage/accord) - Sharable validations for Crystal objects
 * [any_hash.cr ★11](https://github.com/Sija/any_hash.cr) - Recursive Hash with better JSON::Any included
 * [circuit_breaker ★14](https://github.com/TPei/circuit_breaker) - Implementation of the circuit breaker pattern
 * [crystal-binary_parser ★2](https://github.com/DanSnow/crystal-binary_parser) - Binary parser
 * [crystal-futures ★42](https://github.com/dhruvrajvanshi/crystal-futures) - Future type implementation
 * [crz ★16](https://github.com/dhruvrajvanshi/crz) - Functional programming library
 * [denetmen ★19](https://github.com/izniburak/denetmen) - Useful micro validator / check library
 * [emoji.cr ★11 ⏳1Y](https://github.com/veelenga/emoji.cr) - Emoji library
 * [hoop ★169](https://github.com/0x73/hoop) - Building native OSX apps
 * [html_builder ★26](https://github.com/crystal-lang/html_builder) - DSL for creating HTML
 * [i18n.cr ★5](https://github.com/vladfaust/i18n.cr) - Internationalization shard
 * [immutable ★121](https://github.com/lucaong/immutable) - Implementation of thread-safe, persistent, immutable collections
 * [inflector.cr ★22](https://github.com/phoffer/inflector.cr) - Singularize, pluralize, camelize, etc (port from ActiveSupport)
 * [lirith ★15](https://github.com/lirith-engine/lirith) - Graphics engine
 * [manual-generator ★0](https://github.com/blocknotes/manual-generator) - Tool to generate PDF manuals from documentation sites
 * [raytracer ★25](https://github.com/l3kn/raytracer) - CPU Raytracer with examples
 * [syscall.cr ★11](https://github.com/kubo39/syscall.cr) - Raw syscall interface
 * [tren ★76](https://github.com/sdogruyol/tren) - Give your SQL some love
 * [ulid ★3](https://github.com/SuperPaintman/ulid) - Universally Unique Lexicographically Sortable Identifier (ULID)
 * [wikicr ★4](https://github.com/Nephos/wikicr) - Wiki using git to manage revisions

## Networking
 * [amqp.cr ★31](https://github.com/datanoise/amqp.cr) - AMQP 0.9.1 client with RabbitMQ extensions
 * [bson.cr ★12](https://github.com/jeromegn/bson.cr) - Native BSON implementation
 * [CrystalIrc ★11](https://github.com/Meoowww/CrystalIrc) - IRC implementation (Client, Server, Bots)
 * [fast_irc.cr ★5](https://github.com/RX14/fast_irc.cr) - Fast IRC parser/generator
 * [ipaddress.cr ★10](https://github.com/Sija/ipaddress.cr) - Library to handle IPv4 and IPv6 addresses
 * [jwt ★67](https://github.com/crystal-community/jwt) - Implementation of JWT (JSON Web Token)
 * [msgpack-crystal ★57](https://github.com/crystal-community/msgpack-crystal) - MessagePack library
 * [transfer_more ★9](https://github.com/Nephos/transfer_more) - Clone of transfer.sh to uploads files

## ORM/ODM Extensions
 * [active_record.cr ★166](https://github.com/waterlink/active_record.cr) - Active Record pattern implementation
 * [core ★20](https://github.com/vladfaust/core.cr) - Pure, transparent and efficient ORM
 * [crecto ★155](https://github.com/Crecto/crecto) - Database wrapper, based on Ecto
 * [granite-orm ★67](https://github.com/amberframework/granite-orm) - ORM for Postgres, Mysql, Sqlite
 * [jennifer.cr ★90](https://github.com/imdrasil/jennifer.cr) - Active Record pattern implementation with flexible query chainable builder and migration system
 * [ohm-crystal ★42](https://github.com/soveran/ohm-crystal) - Object-hash mapping library for Redis
 * [redis-tsv.cr ★4](https://github.com/maiha/redis-tsv.cr) - Import and export data from Redis in TSV format
 * [stal-crystal ★3](https://github.com/soveran/stal-crystal) - Set algebra solver for Redis
 * [topaz ★53](https://github.com/topaz-crystal/topaz) - A simple and useful db wrapper

## Package Management
 * [CRelease ★6](https://github.com/elorest/crelease) - Version and git tag manager that makes shard releases easy
 * [shards ★381](https://github.com/crystal-lang/shards) - Dependency manager for the Crystal

## Processes and Threads
 * [neph ★64](https://github.com/tbrand/neph) - A modern command line job processor that can execute jobs concurrently
 * [promise ★22](https://github.com/jwaldrip/promise.cr) - A Promise Implementation

## Project Generators
 * [bindgencr ★0](https://github.com/TechMagister/bindgencr) - Generator of bindings based on castxml output
 * [crystal_lib ★79](https://github.com/crystal-lang/crystal_lib) - Automatic binding generator for native libraries
 * [fez ★30](https://github.com/jwoertink/fez) - A Kemal application generator
 * [kgen ★8](https://github.com/kemalyst/kemalyst-generator) - Kemalyst command line tool for console, init, generate (scaffolding), and watch.
 * [libgen ★17](https://github.com/olbat/libgen) - Automatic bindings generator configured using JSON/YAML files
 * [wasp ★3](https://github.com/icyleaf/wasp) - Static Site Generator

## Queue
 * [dispatch ★7](https://github.com/bmulvihill/dispatch) - In memory asynchronous job processing
 * [sidekiq.cr ★397](https://github.com/mperham/sidekiq.cr) - Simple, efficient job processing

## Routing
 * [crouter ★41](https://github.com/jreinert/crouter) - A standalone router
 * [orion ★7](https://github.com/obsidian/orion) - A minimal, rails'esk routing library.
 * [router.cr ★70](https://github.com/tbrand/router.cr) - Minimum but powerful http router for HTTP::Server
 * [toro ★59](https://github.com/soveran/toro) - Tree Oriented Routing

## Scheduling
 * [cron_scheduler ★22](https://github.com/kostya/cron_scheduler) - Job scheduler with crontab patterns
 * [quartz ★3](https://github.com/andrewhamon/quartz) - Crystal clear timers
 * [schedule.cr ★34](https://github.com/hugoabonizio/schedule.cr) - Run periodic tasks

## Science and Data analysis
 * [linalg ★9](https://github.com/konovod/linalg) - Linear algebra library inspired by MATLAB and SciPy.linalg
 * [predict.cr ★4](https://github.com/RX14/predict.cr) - Satellite prediction library using the sgp4 model
 * [scorystal ★3](https://github.com/asafschers/scorystal) - Scoring API for PMML - supports RF and GBM
 * [stats ★8](https://github.com/Nephos/stats) - An expressive implementation of statistical distributions

## Search
 * [hermes ★12](https://github.com/imdrasil/hermes.cr) - Data Mapper pattern implementation for ElastiSearch
 * [query-builder ★34](https://github.com/izniburak/query-builder) - Sql Query Builder library
 * [query.cr ★9](https://github.com/waterlink/query.cr) - Query abstraction
 * [soegen ★14](https://github.com/Ragmaanir/soegen) - Elasticsearch client for Crystal similar to the stretcher gem for ruby

## Task management
 * [cake ★8](https://github.com/axvm/cake) - Production-ready Make-like utility tool
 * [sam ★15](https://github.com/imdrasil/sam.cr) - Another one Rake-like task manager with namespacing and arguments system

## Template Engine
 * [crikey](https://github.com/domgetter/crikey) - Templating engine inspired by [Hiccup ★1647](https://github.com/weavejester/hiccup)
 * [crinja ★12](https://github.com/straight-shoota/crinja) - An implementation of the [Jinja2 template engine](http://jinja.pocoo.org/)
 * [crustache ★35](https://github.com/MakeNowJust/crustache) - [{{Mustache}}](https://mustache.github.io) for Crystal
 * [Kilt ★67](https://github.com/jeromegn/kilt) - Abstraction layer for template engines
 * [Slang ★90](https://github.com/jeromegn/slang) - Lightweight, terse, templating language inspired by Ruby's Slim
 * [teeplate ★5](https://github.com/mosop/teeplate) - A library for rendering multiple template files
 * [temel ★36](https://github.com/f/temel) - Extensible HTML::Builder alternative for Crystal, supports custom tag definitions

## Testing
 * [crotest ★17 ⏳1Y](https://github.com/emancu/crotest) - A tiny and simple test framework
 * [microtest ★13](https://github.com/Ragmaanir/microtest) - Small opinionated testing library focusing on power asserts
 * [minitest.cr ★59](https://github.com/ysbaddaden/minitest.cr) - Library for unit tests and assertions
 * [mocks.cr ★23](https://github.com/waterlink/mocks.cr) - Mocking library for Crystal
 * [spec2-mocks ★7](https://github.com/waterlink/spec2-mocks.cr) - An adapter of mocks.cr for spec2.cr
 * [spec2.cr ★74](https://github.com/waterlink/spec2.cr) - Enhanced testing library
 * [timecop.cr](https://github.com/TobiasGSmollett/timecop.cr) - Library for mocking with `Time.now`. Inspired by [timecop ruby gem ★2483](https://github.com/travisjeffery/timecop)
 * [webmock.cr ★39](https://github.com/manastech/webmock.cr) - Library for stubbing `HTTP::Client` requests

## Third-party APIs
 * [aws-signer.cr ★6](https://github.com/beanieboi/aws-signer.cr) - This library signs your HTTP requests using AWS v4
 * [awscr-s3 ★10](https://github.com/taylorfinnell/awscr-s3) - AWS S3 interface
 * [awscr-signer ★4](https://github.com/taylorfinnell/awscr-signer) - Sign HTTP::Request objects and generate presigned post forms
 * [bugsnag.cr ★2](https://github.com/gewo/bugsnag.cr) - Bugsnag exception notifier and sidekiq middleware
 * [crystal-darksky ★3](https://github.com/sb89/crystal-darksky) - Wrapper for the [Dark Sky](https://darksky.net) API
 * [crystal-github ★2](https://github.com/felipeelias/crystal-github) - Wrapper for the [Github](https://github.com/) API
 * [crystal-monzo ★0](https://github.com/barisbalic/crystal-monzo) - A client for the [Monzo API](https://monzo.com/docs/)
 * [crystal-swapi ★1](https://github.com/sb89/crystal-swapi) - Star Wars API (SWAPI) wrapper
 * [crystal_slack ★10](https://github.com/manastech/crystal_slack) - A tool that parses Slack slash commands or send incoming web hooks
 * [dotacr ★7](https://github.com/azah/dotacr) - Wrapper for Valve's DotA API
 * [GDAX ★0](https://github.com/mccallofthewild/gdax) - GDAX REST and WebSocket API Wrapper with request signing
 * [gitlab.cr ★9](https://github.com/icyleaf/gitlab.cr) - GitLab API wrapper
 * [google_maps_api ★8 ⏳1Y](https://github.com/fridgerator/google_maps_api) - Google Maps API
 * [hncr ★1 ⏳1Y](https://github.com/Gangwolf/hncr) - A Hacker News API wrapper
 * [mixpanel-crystal ★0](https://github.com/petoem/mixpanel-crystal) - A library for sending events to Mixpanel
 * [nexmo-crystal ★1 ⏳1Y](https://github.com/timcraft/nexmo-crystal) - [Nexmo REST API](https://developer.nexmo.com/) client
 * [ocean_kit ★4](https://github.com/osfx/ocean_kit) - [Digital Ocean v2 API](https://developers.digitalocean.com/documentation/v2/) client
 * [open_exchange_rates ★9](https://github.com/osfx/open_exchange_rates) - A library to access [Open Exchange Rates](https://openexchangerates.org/) API
 * [pinboard.cr ★1](https://github.com/oz/pinboard.cr) - [Pinboard](https://pinboard.in) API
 * [raven.cr](https://github.com/sija/raven.cr) - Raven is a client for [Sentry ★14531](https://github.com/getsentry/sentry)
 * [slack.cr ★9](https://github.com/DougEverly/slack.cr) - A Slack [Real Time Messaging API](https://api.slack.com/rtm) WebSocket client library
 * [spotify.cr ★28 ⏳1Y](https://github.com/marceloboeira/spotify.cr) - A library to access the Spotify API
 * [tele.cr ★13](https://github.com/vladfaust/tele.cr) - A *convenient* wrapper for the Telegram Bot API
 * [telegram_bot ★43](https://github.com/hangyas/telegram_bot) - A wrapper for the Telegram Bot API

## Virtualization
 * [baked_file_system ★60](https://github.com/schovi/baked_file_system) - Virtual file system implementation
 * [rcpu ★29](https://github.com/ddfreyne/rcpu) - A virtual machine emulator and assembler

## Web Frameworks
 * [amber ★446](https://github.com/amberframework/amber) - Open source efficient and cohesive web application framework
 * [kemal ★1904](https://github.com/kemalcr/kemal) - Lightning Fast, Super Simple web framework. Inspired by Sinatra
 * [lattice-core ★43](https://github.com/jasonl99/lattice-core) - A WebSocket-first object-oriented framework (based on Kemal)
 * [luckyframework](https://github.com/luckyframework) - Fast, maintainable and confidence boosting web framework
 * [raze ★55](https://github.com/samueleaton/raze) - Modular, light web framework

## Web Servers
 * [fast-http-server ★114](https://github.com/sdogruyol/fast-http-server) - Super fast, zero configuration command line HTTP Server
 * [prax.cr ★97](https://github.com/ysbaddaden/prax.cr) - Rack proxy server for development
 * [serve ★13](https://github.com/SuperPaintman/serve) - Command line static HTTP server

# Community
 * [Crystal weekly newsletters](http://crystalweekly.com/)
 * [Gitter](https://gitter.im/crystal-lang/crystal)
 * [Google Group](https://groups.google.com/forum/?fromgroups#!forum/crystal-lang)
 * [IRC](http://irc.lc/freenode/crystal-lang) - #crystal-lang on Freenode
 * [Metaruby](https://metaruby.com/c/crystal-forum) - Crystal Forum on Metaruby
 * [Reddit](https://www.reddit.com/r/crystal_programming/)
 * [Stackoverflow](https://stackoverflow.com/tags/crystal-lang/info)

# Resources
 * [Crystal for Rubyists](http://www.crystalforrubyists.com/) - free book to bootstrap your Crystal journey
 * [crystal-lang.org](https://crystal-lang.org) - Official language site

## Official Documentation Translations
 * [br.crystal-lang.org](http://br.crystal-lang.org/) - Brazilian
 * [ja.crystal-lang.org](http://ja.crystal-lang.org/) - Japanese
 * [kr.crystal-lang.org](https://kr.crystal-lang.org/) - Korean
 * [ru.crystal-lang.org](http://ru.crystal-lang.org/) - Russian
 * [tw.crystal-lang.org](http://tw.crystal-lang.org/) - Chinese Traditional

# Services and Apps
 * [carc.in](https://carc.in/) - A web service that runs your code and displays the result
 * [Crank ★28](https://github.com/arktisklada/crank) - A Procfile-based application manager (like Foreman)
 * [Crystal [ANN]](https://crystal-ann.com) - Announce new project, blog post, version update or any other Crystal work
 * [crystalshards.herokuapp.com](https://crystalshards.herokuapp.com/), [crystalshards.xyz](http://crystalshards.xyz/) - Web services that list all available Crystal shards
 * [DeBot ★30](https://github.com/jhass/DeBot) - IRC bot written in Crystal
 * [Ficha ★16](https://github.com/codenoid/ficha) - A super secret chat app, for any body who needs privacy
 * [icr ★212](https://github.com/crystal-community/icr) - Interactive console for Crystal (like IRB for Ruby)
 * [nes ★33](https://github.com/romeroadrian/nes.cr) - A NES emulator
 * [shards.rocks](https://shards.rocks/) - Service that manages dependencies inspired by [Gemnasium](https://gemnasium.com/) and [David](https://david-dm.org/)
 * [soundmemes.cr ★5](https://github.com/vladfaust/soundmemes.cr) - Telegram Bot built on top of tele.cr
 * [torrent ★24](https://github.com/Papierkorb/torrent) - A BitTorrent client

# Tools
 * [crystal-base ★0](https://github.com/ruivieira/crystal-base) - CentOS base docker image for Crystal development
 * [crystal-ctags ★5 ⏳1Y](https://github.com/SuperPaintman/crystal-ctags) - Ctags generator for Crystal
 * [crystal-dash-docset ★4](https://github.com/Sija/crystal-dash-docset) - [Dash](https://kapeli.com/dash) docset generator
 * [helptransl8 ★5](https://github.com/papilip/helptransl8) - Tool for document translators

## DevOps
 * [ansible-crystal ★0](https://github.com/CorbanR/ansible-crystal) - Ansible playbook for installing crystal
 * [crystal-cookbook ★4 ⏳1Y](https://github.com/vjdhama/crystal-cookbook) - Chef cookbook for installing crystal

## Editor Plugins
 * Atom
   * [crystal-tools](https://atom.io/packages/crystal-tools) - Enables built in tools in Crystal compiler
   * [language-crystal-actual](https://atom.io/packages/language-crystal-actual) - Crystal language support in Atom
   * [linter-crystal](https://atom.io/packages/linter-crystal) - Lint Crystal using the Crystal compiler in Atom
 * Emacs
   * [emacs-crystal-mode ★17](https://github.com/dotmilk/emacs-crystal-mode) - Crystal language support for Emacs
   * [play-crystal.el ★3](https://github.com/veelenga/play-crystal.el) - [play.crystal-lang.org](https://play.crystal-lang.org/#/cr) integration in Emacs
 * Spacemacs
   * [crystal-spacemacs-layer ★10 ⏳1Y](https://github.com/juanedi/crystal-spacemacs-layer) - Spacemacs contribution layer for Crystal
 * Sublime
   * [sublime-crystal ★45](https://github.com/crystal-lang-tools/sublime-crystal) - Crystal syntax highlighting for sublime Text
 * TextMate
   * [Crystal.tmbundle ★4](https://github.com/crystal-lang-tools/Crystal.tmbundle) - Crystal syntax highlighting, compile, format command, snippets
 * Vim
   * [carcin.vim ★4 ⏳1Y](https://github.com/MakeNowJust/carcin.vim) - Vim plugin to provide utility functions for carc.in
   * [vim-crystal ★186](https://github.com/rhysd/vim-crystal) - Vim filetype support for Crystal
   * [vim-slang ★6 ⏳1Y](https://github.com/elorest/vim-slang) - Vim filetype support for Slang Templating Engine
 * Visual Studio Code
   * [vscode-crystal ★10](https://github.com/g3ortega/vscode-crystal) - Crystal language support in VSCode
   * [vscode-crystal-ide ★26](https://github.com/crystal-lang-tools/crystal-ide) - Crystal IDE powered by [Language Server Protocol](https://code.visualstudio.com/blogs/2016/06/27/common-language-protocol)
   * [vscode-crystal-lang ★37](https://github.com/crystal-lang-tools/vscode-crystal-lang) - Formatter, linter and syntax highlighting for `cr` and `ecr` files

## Shell plugins
 * [crystal-zsh ★18](https://github.com/veelenga/crystal-zsh) - .oh-my-zsh plugin
---
<p align="center">
	This list is a copy of <a href="https://github.com/veelenga/awesome-crystal">veelenga/awesome-crystal</a> with ranks
</p>
