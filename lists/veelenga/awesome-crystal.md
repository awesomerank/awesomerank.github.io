<h1 align="center">
Ranked awesome lists, all in one place
</h1>
<p align="center">
	This list is a copy of <a href="veelenga/awesome-crystal">veelenga/awesome-crystal</a> with ranks
</p>
---
# Awesome Crystal [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg) ★59088](sindresorhus/awesome) [![Build Status](https://travis-ci.org/veelenga/awesome-crystal.svg)](https://travis-ci.org/veelenga/awesome-crystal)

A curated list of awesome Crystal code and resources. Inspired by [awesome](https://github.com/sindresorhus/awesome) and [awesome-awesomeness ★18868](bayandin/awesome-awesomeness).
The goal is to have projects mostly stable and useful for users.

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
  * [Database Drivers](#database-drivers)
  * [Database Tools](#database-tools)
  * [Development Tools](#development-tools)
  * [Email](#email)
  * [Environment Management](#environment-management)
  * [Examples and funny stuff](#examples-and-funny-stuff)
  * [Framework Components](#framework-components)
  * [Game Development](#game-development)
  * [HTML/XML parsing](#htmlxml-parsing)
  * [HTTP](#http)
  * [Image Processing](#image-processing)
  * [Implementations/Compilers](#implementationscompilers)
  * [Logging and monitoring](#logging-and-monitoring)
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
 * [aho_corasick ★1](chenkovsky/aho_corasick) - AhoCorasick algorithm
 * [crystal-linked-list ★3](abvdasker/crystal-linked-list) - Implementation of Linked List
 * [crystaledge ★4](unn4m3d/crystaledge) - A pure Vector Math library
 * [crystalg ★8](TobiasGSmollett/crystalg) - A Generic Algorithm Library
 * [crystalline ★68](jtomschroeder/crystalline) - A collection of containers and algorithms
 * [delimiter_tree ★7](drujensen/delimiter_tree) - A tree structure that is built using a delimiter
 * [edits.cr ★4](tcrouch/edits.cr) - Collection of edit distance algorithms
 * [heap.cr ★1](chenkovsky/heap.cr) - Implementation of heap data structure
 * [miller_rabin ★0](kuende/miller_rabin) - Implements [Miller-Rabin](https://en.wikibooks.org/wiki/Algorithm_Implementation/Mathematics/Primality_Testing) algorithm to check if a number is prime
 * [multiset.cr ★1](tcrouch/multiset.cr) - Implementation of a multiset
 * [murmur3 ★1](kuende/murmur3) - Implementation of Murmur3 hash algorithm used by Cassandra
 * [primes ★2](dkhofer/primes) - Library for testing if a number is prime and finding its prime factorization
 * [radix ★23](luislavena/radix) - Radix Tree implementation
 * [ranger ★2](akwiatkowski/ranger) - Range object operation library
 * [text ★8](johnjansen/text) - A collection of phonetic algorithms

## Api Builders
 * [crystal_api ★50](akwiatkowski/crystal_api) - Simple PostgreSQL REST API with Rails devise-like auth
 * [kemal-rest-api ★2](blocknotes/kemal-rest-api) - A library to create RESTful API with Kemal

## C bindings
 * [asound-cr ★1](TamasSzekeres/asound-cr) - Bindings for ALSA/libasound
 * [cairo-cr ★0](TamasSzekeres/cairo-cr) - Bindings for [Cairo](https://cairographics.org/) graphics library
 * [crass ★5](vonKingsley/crass) - Bindings for libsass
 * [crt.cr ★7](maiha/crt.cr) - Bindings for libncursesw and crt
 * [crystal-dbus](https://github.com/BlaXpirit/crystal-dbus) - Bindings to D-Bus
 * [crystal-gsl ★9](ruivieira/crystal-gsl) - GNU Scientific Library bindings
 * [crystal-liblmdb ★3](timuckun/crystal-liblmdb) - Bindings for the Symas LMDB database
 * [crystal-libpcap ★5](puppetpies/crystal-libpcap) - Bindings for libpcap
 * [crystal-libtar ★4](puppetpies/crystal-libtar) - Bindings for libtar
 * [crystal_av ★3](kofno/crystal_av) - Bindings to [ClamAV](https://www.clamav.net/) anti-virus
 * [curl-crystal ★4](blocknotes/curl-crystal) - Bindings for [libcurl](https://curl.haxx.se/libcurl/)
 * [curses ★3 ⏳1Y](ruivieira/curses) - Bindings for the curses library
 * [duktape.cr](https://github.com/jessedoyle/duktape.cr) - Bindings for the [Duktape ★2722](svaarala/duktape) javascript engine
 * [glfw ★0](lirith-engine/glfw) - GLFW bindings
 * [gphoto2.cr ★5](Sija/gphoto2.cr) - Bindings for the [libgphoto2](http://www.gphoto.org/) library
 * [icu.cr ★1](olbat/icu.cr) - Bindings for the [ICU](http://site.icu-project.org/) library
 * [java.cr ★6](ysbaddaden/java.cr) - Java Native Interface (JNI) bindings (and generator)
 * [kt ★1](kuende/kt) - Bindings for [Kyoto Tycoon](http://fallabs.com/kyototycoon/)
 * [libmagic-crystal ★2](pablotron/libmagic-crystal) - Bindings for libmagic
 * [libnotify.cr ★9](splattael/libnotify.cr) - Bindings for Libnotify
 * [libui.cr](https://github.com/Fusion/libui.cr) - Bindings for [libui ★4372](andlabs/libui)
 * [nanomsg.cr ★0](chenkovsky/nanomsg.cr) - Bindings for nanomsg
 * [openssl.cr ★12](datanoise/openssl.cr) - Bindings for OpenSSL library
 * [pcap.cr ★8](maiha/pcap.cr) - Bindings for libpcap
 * [posix ★16](ysbaddaden/posix) - POSIX/C bindings
 * [serialport.cr ★7](Sija/serialport.cr) - Bindings for [libserialport](http://sigrok.org/wiki/Libserialport) library
 * [snappy-crystal ★3 ⏳1Y](benoist/snappy-crystal) - Bindings for Snappy library
 * [soundfile ★0](mjago/soundfile) - Bindings for [libsndfile](http://www.mega-nerd.com/libsndfile/) library
 * [ssh2.cr ★21](datanoise/ssh2.cr) - Bindings for libssh2 library
 * [termbox-crystal](https://github.com/andrewsuzuki/termbox-crystal) - Bindings and extension library for [termbox ★1033](nsf/termbox) (terminal UI library)
 * [x11-cr ★1](TamasSzekeres/x11-cr) - X11 bindings
 * [zeromq-crystal ★18](benoist/zeromq-crystal) - Bindings for ZeroMQ

## Caching
 * [Bloom Filter ★12 ⏳1Y](greyblake/crystal-bloom_filter) - Implementation of Bloom filter
 * [bojack ★47](marceloboeira/bojack) - A non-reliable in-memory key-value store
 * [crystal-kiwi ★17](greyblake/crystal-kiwi) - A unified interface for key-value stores
 * [crystal-memcached ★19](comandeo/crystal-memcached) - Implementation of a memcached client
 * [Nuummite ★6](CodeSteak/Nuummite) - A tiny persistent embedded key-value store

## Cli Builders
 * [admiral ★20](jwaldrip/admiral.cr) - A robust DSL for writing command line interfaces
 * [cli ★39](mosop/cli) - Library for building command-line interface applications
 * [clim ★8](at-grandpa/clim) - Slim command line interface builder
 * [commander ★63](mrrooijen/commander) - Command-line interface builder
 * [completion ★37](f/completion) - Easy command line completion engine
 * [docopt ★8](chenkovsky/docopt.cr) - A [docopt.org](http://docopt.org) port
 * [optarg ★9](mosop/optarg) - Yet another library for parsing command-line options and arguments

## Cli Utils
 * [progress ★88](askn/progress) - [==..] Progress bar
 * [spinner ★35](askn/spinner) - Terminal Spinner
 * [terminal_table.cr ★11](benoist/terminal_table.cr) - Simple ASCII table generator

## Configuration
 * [ambience ★11 ⏳1Y](vjdhama/ambience) - Simple app configuration using `ENV`
 * [cr-dotenv ★20](gdotdesign/cr-dotenv) - Loads .env file
 * [crystal-toml ★23](manastech/crystal-toml) - TOML parser
 * [dockerfile.cr ★1](keplersj/dockerfile.cr) - Dockerfile Parsing Library
 * [zq ★2](colstrom/zq) - Command-line ZPL processor

## Converters
 * [moola](https://github.com/dorkrawk/moola) - Library for dealing with money and conversion (inspired by [RubyMoney ★1757](RubyMoney/money))
 * [ms ★0](SuperPaintman/ms) - Library to easily convert various time formats to milliseconds and milliseconds to human readable format
 * [turkish-number ★5](izniburak/turkish-number) - Turn integers into the Turkish words
 * [wkhtmltopdf-crystal ★2](blocknotes/wkhtmltopdf-crystal) - Bindings / wrapper for libwkhtmltox (HTML to PDF / image converter)

## Data Generators
 * [faker ★63](askn/faker) - A library for generating fake data
 * [hashids.cr ★17](splattael/hashids.cr) - A library to generate YouTube-like ids from one or many numbers

## Database Drivers
 * [crystal-db ★67](crystal-lang/crystal-db) - Common db api
 * [crystal-leveldb ★15](greyblake/crystal-leveldb) - Crystal bindings for LevelDB
 * [crystal-monetdb-libmapi ★1](puppetpies/crystal-monetdb-libmapi) - Bindings for MonetDB
 * [crystal-mysql ★36](waterlink/crystal-mysql) - Basic MySQL bindings
 * [crystal-mysql ★23](crystal-lang/crystal-mysql) - MySQL connector for Crystal
 * [crystal-pg ★172](will/crystal-pg) - A Postgres driver
 * [crystal-redis ★162](stefanwille/crystal-redis) - Full featured Redis client
 * [crystal-sqlite3 ★38](crystal-lang/crystal-sqlite3) - SQLite3 bindings
 * [eventql-crystal ★5](measurechina/eventql-crystal) - EventQL driver
 * [influxdb.cr ★10](jeromegn/influxdb.cr) - InfluxDB driver
 * [mongo.cr ★51](datanoise/mongo.cr) - Binding for MongoDB C driver
 * [rethinkdb-crystal](https://github.com/lbguilherme/rethinkdb-crystal) - RethinkDB Driver
 * [rocksdb.cr ★8](maiha/rocksdb.cr) - RocksDB client

## Database Tools
 * [micrate ★54](juanedi/micrate) - Database migration tool

## Development Tools
 * [guardian ★158](f/guardian) - File change watcher for Crystal and Non-Crystal libs
 * [kemal-watcher ★3](faustinoaq/kemal-watcher) - Kemal plugin to watch files and live-reload the browser
 * [sentry ★61](samueleaton/sentry) - Watches src files, rebuilds/reruns application on file changes
 * [sentry-run ★3](faustinoaq/sentry-run) - Reload code changes using Sentry.run
 * [watchbird ★6](agatan/watchbird) - Monitors directories and files, runs tasks automatically
 * [watcher ★3](faustinoaq/watcher) - Watch file changes using File.stat

## Email
 * [CrystalEmail ★8](Nephos/CrystalEmail) - A RFC compliant Email validator
 * [devmail ★7](tijn/devmail) - A combined SMTP/POP3-server with volatile mail storage
 * [sendgrid.cr ★6](dlanileonardo/sendgrid.cr) - Simple Sendgrid Client
 * [smtp.cr ★17](raydf/smtp.cr) - Email SMTP client

## Environment Management
 * [asdf-crystal ★5](marciogm/asdf-crystal) - Plugin for asdf version manager
 * [crenv ★133](pine/crenv) - Crystal version manager
 * [rcm.cr ★10](maiha/rcm.cr) - Redis Cluster Manager

## Examples and funny stuff
 * [crsfml-examples](https://github.com/BlaXpirit/crsfml-examples) - Simple games made with CrSFML
 * [crystal-benchmarks-game ★43](kostya/crystal-benchmarks-game) - The Computer Language Benchmarks Game
 * [crystal-by-example ★192](askn/crystal-by-example) - Crystal By Example
 * [Crystal-Maze ★9](Demonstrandum/Crystal-Maze) - A* Path finding for PNG mazes
 * [crystal-patterns ★35](veelenga/crystal-patterns) - Examples of GOF patters
 * [crystal_samples ★25](tbpgr/crystal_samples) - Variety of Crystal samples
 * [crystalized_ruby ★98](phoffer/crystalized_ruby) - Native Ruby extensions written in Crystal
 * [docker-kemal ★7 ⏳1Y](ianblenke/docker-kemal) - An example Dockerized Crystal Kemal project
 * [fast_sleep ★24](asterite/fast_sleep) - Blazing fast (funny) implementation of sleep for Crystal
 * [kemal-chat ★26](sdogruyol/kemal-chat) - Build realtime applications with Kemal and WebSocket
 * [kemal-heroku-example ★1](cagataycali/kemal-heroku-example) - This repository shows, how you can publish your open source apps which powered kemal framework publish as heroku app in seconds
 * [kemal-monetdb-test ★0](puppetpies/kemal-monetdb-test) - MonetDB Kemal test project
 * [kemal-pg-sample ★4 ⏳1Y](sdogruyol/kemal-pg-sample) - Sample app to demonstrate kemal + postgresql usage
 * [kemal-react-chat ★49](f/kemal-react-chat) - Build Realtime Web applications with Kemal and React
 * [kemal-react-pg-chat](https://github.com/Angarsk8/kemal-react-pg-chat) - Chat application developed with Kemal, React, ES2015 and PostgreSQL
 * [kemal-ws-pg-todo-app ★1](Angarsk8/kemal-ws-pg-todo-app) - Realtime Todo application developed with Kemal, Websockets, jQuery, ES2015 and PostgreSQL
 * [kemal-ws-react-pg-todo-app](https://github.com/Angarsk8/kemal-ws-react-pg-todo-app) - Realtime Todo application developed with Kemal, Websockets, React, ES2015 and PostgreSQL
 * [kemal-ws-todo-app ★5](Angarsk8/kemal-ws-todo-app) - Realtime Todo application developed with Kemal and Websockets
 * [kemal_elm_chat ★10](kofno/kemal_elm_chat) - Simple chat server written with Kemal and Elm
 * [lattice-core-card-game ★140](jasonl99/card_game) - A demo web app for (WebSocket-based) lattice-core
 * [medley ★6](jwoertink/medley) - A mixture of music related methods
 * [os-crystal ★27](lbguilherme/os-crystal) - x86 Kernel implemented in Crystal
 * [rocky ★69](codingphasedotcom/rocky) - React Over Crystal Kemal and Yarn
 * [try.cr ★12](maiha/try.cr) - Try monad
 * [xcrystal ★26](exercism/xcrystal) - Exercism exercises

## Framework Components
 * [artanis ★34](ysbaddaden/artanis) - Sinatra-like DSL (abusing macros)
 * [cr-melon ★5](gdotdesign/cr-melon) - Class based Http APIs
 * [crystal-mime ★14](spalger/crystal-mime) - Mimetypes for Crystal
 * [kave ★15](jwoertink/kave) - Kemal API Version Extension
 * [kemal-auth-token ★11](akwiatkowski/kemal-auth-token) - Kemal middleware to authentication via HTTP header token using JWT
 * [kemal-comments ★2 ⏳1Y](TyanNN/kemal-comments) - Simple comments for Kemal site
 * [kemal-flash ★4](neovintage/kemal-flash) - Temporary storage between actions in Kemal
 * [kemal-monetdb ★0](puppetpies/kemal-monetdb) - MonetDB Data connection for Kemal
 * [kemal-mysql ★13](sdogruyol/kemal-mysql) - Easily add MySQL database to Kemal
 * [kemal-redis ★7](sdogruyol/kemal-redis) - Easily add Redis to Kemal
 * [kemal-session ★17](kemalcr/kemal-session) - Session handler for Kemal
 * [kemalyst-i18n ★1](TechMagister/kemalyst-i18n) - i18n support for Kemalyst
 * [mime-types.cr ★4](jwaldrip/mime-types.cr) - A port of the Ruby MIME-types library
 * [multi-auth ★1](msa7/multi_auth) - Standardized multi-provider OAuth2 authentication (inspired by omniauth)
 * [request_id ★0](SuperPaintman/request-id) - Middleware for generates / pick up a unique request ID for Crystal servers
 * [response_time ★6](SuperPaintman/response-time) - Response time for Crystal servers (pure http server, kemal, etc.)
 * [spec-kemal](https://github.com/sdogruyol/spec-kemal) - Easy testing for Kemal

## Game Development
 * [CrSFML ★120](oprypin/crsfml) - Bindings to [SFML](http://www.sfml-dev.org/) multimedia/game library
 * [crystal-chipmunk](https://github.com/BlaXpirit/crystal-chipmunk) - Bindings for [Chipmunk](http://chipmunk-physics.net/), a fast and lightweight 2D game physics library
 * [flight-crusader ★9](umurgdk/flight-crusader) - POC top down flight game
 * [glove ★22](ddfreyne/glove) - A library for gaming development
 * [inari ★7](ddfreyne/inari) - A collection of games using Glove as the game engine
 * [medico ★0](konovod/medico) - Game about a medieval doctor
 * [mos_game ★6](bararchy/mos_game) - Mini Offline Singleplayer game

## HTML/XML Parsing
 * [crystagiri](https://github.com/madeindjs/Crystagiri) - An Html Reader / parser like [Nokogiri ★4409](sparklemotion/nokogiri) Ruby gem
 * [gumbo-crystal](https://github.com/blocknotes/gumbo-crystal) - Bindings for [Gumbo ★4025](google/gumbo-parser), an HTML5 parsing library made by Google
 * [hq.cr ★2](maiha/hq.cr) - Simple wrapper for crystal-xml
 * [modest ★24](kostya/modest) - CSS selectors for HTML5 Parser myhtml
 * [myhtml ★19](kostya/myhtml) - Fast HTML5 Parser

## HTTP
 * [crul ★83](porras/crul) - Command line HTTP client
 * [cryload ★97](sdogruyol/cryload) - HTTP benchmarking tool
 * [crystal-cossack ★47](greyblake/crystal-cossack) - Simple flexible HTTP client
 * [etag ★0](SuperPaintman/etag) - Library to generate HTTP ETags
 * [helmet ★10](EvanHahn/crystal-helmet) - Set security-related HTTP headers
 * [http-protection ★9](rogeriozambon/http-protection) - Protection against typical web attacks
 * [http2 ★32](ysbaddaden/http2) - HTTP/2 Protocol Implementation
 * [http_distributor ★0](Nephos/http_distributor) - HTTP server which allows sneaky http requests
 * [http_parser.cr](https://github.com/kostya/http_parser.cr) - Wrapper for [Http Parser lib ★3261](nodejs/http-parser)
 * [keyer_cr ★0](danielpclark/keyer_cr) - Adds HTTP GET/POST parameter parsing as a Hash-like object
 * [multipart.cr ★9](RX14/multipart.cr) - Adds multipart and multipart/form-data support to the crystal standard library
 * [resp-crystal ★4](soveran/resp-crystal) - Lightweight RESP client
 * [session](https://github.com/porras/session.git) - Cookie based sessions in Crystal HTTP applications

## Image processing
 * [magickwand-crystal ★13](blocknotes/magickwand-crystal) - Bindings for [MagickWand](https://www.imagemagick.org/script/magick-wand.php), the C interface for ImageMagick processing libraries
 * [stumpy_gif](https://github.com/l3kn/stumpy_gif) - Write (animated) GIF images
 * [stumpy_png](https://github.com/l3kn/stumpy_png) - Read and write PNG images

## Implementations/Compilers
 * [charly](https://github.com/charly-lang) - Charly Programming Language
 * [cltk ★29](ziprandom/cltk) - A crystal port of the Ruby Language Toolkit
 * [cppize ★16](unn4m3d/cppize) - Crystal-to-C++ transpiler
 * [crisp ★17](rhysd/Crisp) - Lisp dialect implemented with Crystal
 * [crow ★34](geppetto-apps/crow) - Transpile/compile Crystal to [Flow](https://flowtype.org/)
 * [crystal ★8192](crystal-lang/crystal) - Crystal itself is written in Crystal
 * [csmli ★1](david50407/csmli) - Mini-Lisp interpreter
 * [NuummiteOS ★37](TheKernelCorp/NuummiteOS) - An OS written in Crystal as a Proof of Concept
 * [onix ★48](ozra/onyx-lang) - ONYX Programming Language
 * [zir ★9](tbrand/zir) - Realizes to write macros in any scripts into any languages

## Logging and monitoring
 * [crometheus](https://gitlab.com/ezrast/crometheus) - A [Prometheus](https://prometheus.io/) client library
 * [crystal-logreader ★0](arcage/crystal-logreader) - Tailing log file
 * [gelf-crystal ★4 ⏳1Y](benoist/gelf-crystal) - A GELF logger
 * [katip ★15](guvencenanguvenal/katip) - JSONbase logger
 * [statsd.cr](https://github.com/miketheman/statsd.cr) - [Statsd ★11427](etsy/statsd) client library
 * [syslog.cr ★3](comandeo/syslog.cr) - Implementation of Syslog client

## Markdown/Text Processors
 * [html-pipeline ★2](huacnlee/html-pipeline) - HTML processing filters and utilities
 * [remarkdown ★4](huacnlee/remarkdown) - GFM for Crystal

## Misc
 * [aasm.cr ★18](veelenga/aasm.cr) - Easy to use finite state machine for Crystal classes
 * [accord ★9](neovintage/accord) - Sharable validations for Crystal objects
 * [acorn ★7](rmosolgo/acorn) - State Machine Compiler for Crystal
 * [any_hash.cr ★6](Sija/any_hash.cr) - Recursive Hash with better JSON::Any included
 * [chalk-box ★17](azukiapp/crystal-chalk-box) - Terminal color toolbox, check support and colorized (without String monkey patch)
 * [circuit_breaker ★12](TPei/circuit_breaker) - Implementation of the circuit breaker pattern
 * [clamd.cr ★1](RX14/clamd.cr) - Client for the clamd antivirus server
 * [crdoc ★6 ⏳1Y](rhysd/crdoc) - CLI tool to search and open documentation
 * [crystal-binary_parser ★0](DanSnow/crystal-binary_parser) - Binary parser
 * [crystal-diff ★14](MakeNowJust/crystal-diff) - A Crystal sequence differencing implementation
 * [crystal-futures ★36](dhruvrajvanshi/crystal-futures) - Future type implementation
 * [crystal-i18n ★7](whity/crystal-i18n) - Internationalization library
 * [crz ★15](dhruvrajvanshi/crz) - Functional programming library
 * [denetmen ★19](izniburak/denetmen) - Useful micro validator / check library
 * [emoji.cr ★11](veelenga/emoji.cr) - Emoji library
 * [evented ★25 ⏳1Y](krisleech/evented) - A micro library to publish and subscribe for Crystal objects
 * [executable_path](https://github.com/kostya/executable_path) - Portable current executable's path
 * [hoop](https://github.com/hoopcr/hoop) - Building native OSX apps
 * [html_builder ★22](crystal-lang/html_builder) - DSL for creating HTML
 * [immutable ★101](lucaong/immutable) - Implementation of thread-safe, persistent, immutable collections
 * [inflector.cr ★14](phoffer/inflector.cr) - Singularize, pluralize, camelize, etc (port from ActiveSupport)
 * [kreal ★38](f/kreal) - Model sharing & RPC library built on and works with Kemal seamlessly
 * [lambda.cr ★26](f/lambda.cr) - Uniformed function call syntax
 * [lirith ★4](lirith-engine/lirith) - Graphics engine
 * [manual-generator ★0](blocknotes/manual-generator) - Tool to generate PDF manuals from documentation sites
 * [metaclass ★2](mosop/metaclass) - A library for manipulating class-level definitions
 * [observable ★4](TPei/observable) - Implementation of the Observer pattern
 * [ramlrenderer ★4](beno/ramlrenderer) - HTML doc builder for RAML 1.0
 * [raytracer-crystal](https://github.com/l3kn/raytracer-crystal) - CPU Raytracer with examples
 * [shell.cr ★6](dmytro/shell.cr) - Small simplistic helper class for executing shell commands
 * [syscall.cr ★9](kubo39/syscall.cr) - Raw syscall interface
 * [tren ★65](sdogruyol/tren) - Give your SQL some love
 * [ulid ★2](SuperPaintman/ulid) - Universally Unique Lexicographically Sortable Identifier (ULID)

## Networking
 * [amqp.cr ★25](datanoise/amqp.cr) - AMQP 0.9.1 client with RabbitMQ extensions
 * [bson.cr ★7 ⏳1Y](jeromegn/bson.cr) - Native BSON implementation
 * [CrystalIrc ★8](Meoowww/CrystalIrc) - IRC implementation (Client, Server, Bots)
 * [fast_irc.cr ★5](RX14/fast_irc.cr) - Fast IRC parser/generator
 * [ipaddress.cr ★8](Sija/ipaddress.cr) - Library to handle IPv4 and IPv6 addresses
 * [jwt ★51](greyblake/crystal-jwt) - Implementation of JWT (JSON Web Token)
 * [msgpack-crystal ★47](benoist/msgpack-crystal) - MessagePack library
 * [wire ★9](puppetpies/WIre) - A packet analyzer

## ORM/ODM Extensions
 * [active_record.cr ★150](waterlink/active_record.cr) - Active Record pattern implementation
 * [crecto](https://github.com/fridgerator/crecto) - Database wrapper, based on Ecto
 * [jennifer ★45](imdrasil/jennifer.cr) - Active Record pattern implementation with flexible query chainable builder and migration system
 * [kemalyst-model](https://github.com/drujensen/kemalyst-model) - ORM Model for the Kemalyst Framework
 * [ohm-crystal ★34](soveran/ohm-crystal) - Object-hash mapping library for Redis
 * [redis-tsv.cr ★4](maiha/redis-tsv.cr) - Import and export data from Redis in TSV format
 * [selenite-db ★2](xdougx/selenite-db) - A simple persistency-model based library
 * [stal-crystal ★2](soveran/stal-crystal) - Set algebra solver for Redis
 * [topaz](https://github.com/tbrand/topaz) - A simple and useful db wrapper

## Package Management
 * [shards](https://github.com/ysbaddaden/shards) - Dependency manager for the Crystal

## Processes and Threads
 * [daemonize.cr ★9](DougEverly/daemonize.cr) - Crystal process daemonizer
 * [neph ★23](tbrand/neph) - A modern command line job processor that can execute jobs concurrently
 * [promise](https://github.com/jwaldrip/promise-cr) - A Promise Implementation

## Project Generators
 * [bindgencr ★1](TechMagister/bindgencr) - Generator of bindings based on castxml output
 * [crystal_lib ★71](crystal-lang/crystal_lib) - Automatic binding generator for native libraries
 * [fez ★29](jwoertink/fez) - A Kemal application generator
 * [generate ★19](generate-cr/generate) - A tool for generating whole Crystal project structure, or any part of it during lifetime of project
 * [kgen](https://github.com/TechMagister/kemalyst-generator) - Kemalyst command line tool for console, init, generate (scaffolding), and watch.
 * [libgen ★7](olbat/libgen) - Automatic bindings generator configured using JSON/YAML files
 * [skaf ★1](elorest/skaf) - Scaffolding for Kemal
 * [wasp ★4](icyleaf/wasp) - Static Site Generator

## Queue
 * [crystal-resque-client ★2 ⏳1Y](pine/crystal-resque-client) - Simple Resque queue client
 * [dispatch ★5](bmulvihill/dispatch) - In memory asynchronous job processing
 * [disque-cr](https://github.com/foca/disque-cr) - Client for [Disque ★6190](antirez/disque) queueing system
 * [sidekiq.cr ★349](mperham/sidekiq.cr) - Simple, efficient job processing

## Routing
 * [beryl ★17 ⏳1Y](luislavena/beryl) - Action-focused HTTP routing library
 * [crouter ★22](jreinert/crouter) - A standalone router
 * [crystal-routing ★19 ⏳1Y](bcardiff/crystal-routing) - Extensible library to deal with http request and string based routing
 * [router-simple.cr ★5 ⏳1Y](karupanerura/router-simple.cr) - Simple path router
 * [router.cr ★44](tbrand/router.cr) - Minimum but powerful http router for HTTP::Server
 * [toro ★57](soveran/toro) - Tree Oriented Routing

## Scheduling
 * [cron_scheduler ★19](kostya/cron_scheduler) - Job scheduler with crontab patterns
 * [quartz ★1](andrewhamon/quartz) - Crystal clear timers
 * [schedule.cr ★7](hugoabonizio/schedule.cr) - Run periodic tasks

## Science and Data analysis
 * [chizge](https://github.com/aladagemre/chizge) - A Network (Graph) Analysis library, inspired by [NetworkX ★2979](networkx/networkx)
 * [crystal-learn ★20](pbrusco/crystal-learn) - Sklearn-like machine-learning library
 * [machine ★13](mathieulaporte/machine) - Simple machine learning algorithm
 * [predict.cr ★4](RX14/predict.cr) - Satellite prediction library using the sgp4 model
 * [scorystal ★2](asafschers/scorystal) - Scoring API for PMML - supports RF and GBM
 * [stats ★3](Nephos/stats) - An expressive implementation of statistical distributions

## Search
 * [hermes ★8](imdrasil/hermes.cr) - Data Mapper pattern implementation for ElastiSearch
 * [query-builder ★28](izniburak/query-builder) - Sql Query Builder library
 * [query.cr ★8](waterlink/query.cr) - Query abstraction
 * [soegen ★11](Ragmaanir/soegen) - Elasticsearch client for Crystal similar to the stretcher gem for ruby

## Task management
 * [cake ★2](axvm/cake) - Production-ready Make-like utility tool
 * [crake ★30 ⏳1Y](MakeNowJust/crake) - Rake-like build utility library. It is just a library, so it does not provide CLI
 * [lake ★8 ⏳1Y](adlerhsieh/lake) - Rake-like task management for Crystal programs
 * [sam ★8](imdrasil/sam.cr) - Another one Rake-like task manager with namespacing and arguments system

## Template Engine
 * [Bunny ★9 ⏳2Y](samsheff/Bunny) - A simple HTML templating language for Crystal, same syntax as erb
 * [crikey](https://github.com/domgetter/crikey) - Templating engine inspired by [Hiccup ★1556](weavejester/hiccup)
 * [crustache ★31](MakeNowJust/crustache) - [{{Mustache}}](https://mustache.github.io) for Crystal
 * [Kilt ★51](jeromegn/kilt) - Abstraction layer for template engines
 * [Slang ★70](jeromegn/slang) - Lightweight, terse, templating language inspired by Ruby's Slim
 * [teeplate ★4](mosop/teeplate) - A library for rendering multiple template files
 * [temel ★32](f/temel) - Extensible HTML::Builder alternative for Crystal, supports custom tag definitions

## Testing
 * [crotest ★15](emancu/crotest) - A tiny and simple test framework
 * [matchi ★0 ⏳1Y](fixcr/matchi) - Collection of expectation matchers
 * [minitest.cr ★48](ysbaddaden/minitest.cr) - Library for unit tests and assertions
 * [mock ★12 ⏳1Y](porras/mock) - Mocking library, inspired by the API of rspec-mocks
 * [mocks.cr ★17](waterlink/mocks.cr) - Mocking library for Crystal
 * [power_assert.cr ★36](rosylilly/power_assert.cr) - Powerful assertion for Crystal
 * [spec2-mocks ★5](waterlink/spec2-mocks.cr) - An adapter of mocks.cr for spec2.cr
 * [spec2.cr ★61](waterlink/spec2.cr) - Enhanced testing library
 * [timecop.cr](https://github.com/waterlink/timecop.cr) - Library for mocking with `Time.now`. Inspired by [timecop ruby gem ★2369](travisjeffery/timecop)
 * [webmock.cr ★33](manastech/webmock.cr) - Library for stubbing `HTTP::Client` requests

## Third-party APIs
 * [airbrake-crystal ★8 ⏳1Y](kyrylo/airbrake-crystal) - A Crystal notifier for [Airbrake](https://airbrake.io)
 * [AnyBar_cr ★4 ⏳1Y](davydovanton/AnyBar_cr) - Simple crystal wrapper for AnyBar library
 * [aws-signer.cr ★6](beanieboi/aws-signer.cr) - This library signs your HTTP requests using AWS v4
 * [awscr-signer ★3](taylorfinnell/awscr-signer) - Sign HTTP::Request objects and generate presigned post forms
 * [bugsnag.cr ★2](gewo/bugsnag.cr) - Bugsnag exception notifier and sidekiq middleware
 * [crystal-connpass ★1 ⏳1Y](pine/crystal-connpass) - Wrapper for the [Connpass](http://connpass.com/) API
 * [crystal-darksky ★4](sb89/crystal-darksky) - Wrapper for the [Dark Sky](https://darksky.net) API
 * [crystal-github ★1](felipeelias/crystal-github) - Wrapper for the [Github](https://github.com/) API
 * [crystal-mondo](https://github.com/barisbalic/crystal-mondo) - A client for the [Mondo API](https://getmondo.co.uk/docs/)
 * [crystal-newrelic ★3](waj/crystal-newrelic) - NewRelic API client
 * [crystal-qiita ★0 ⏳1Y](pine/crystal-qiita) - A wrapper for the [Qiita](https://qiita.com/) API
 * [crystal-swapi ★2](sb89/crystal-swapi) - Star Wars API (SWAPI) wrapper
 * [crystal_brium ★1](manastech/crystal_brium) - Access Brium's API using Crystal
 * [crystal_slack ★8](manastech/crystal_slack) - A tool that parses Slack slash commands or send incoming web hooks
 * [crystalforce ★3](ucmsky/crystalforce) - Salesforce REST api
 * [docker.cr ★11](jeromegn/docker.cr) - Docker API client
 * [dotacr ★7](azah/dotacr) - Wrapper for Valve's DotA API
 * [fantasy_football_nerd_api ★0](fridgerator/fantasy_football_nerd_api) - A library for the [Fantasy Football Nerd API](http://www.fantasyfootballnerd.com/fantasy-football-api)
 * [gitlab.cr ★8](icyleaf/gitlab.cr) - GitLab API wrapper
 * [glosbe ★3](greyblake/crystal-glosbe) - Client for [Glosbe API](https://glosbe.com/a-api)
 * [google_maps_api ★6](fridgerator/google_maps_api) - Google Maps API
 * [google_translate ★5](greyblake/crystal-google_translate) - Client for Google Translate
 * [gravatar.cr](https://github.com/fg/gravatar.cr.git) - A library to use Gravatar service
 * [hncr ★1](Gangwolf/hncr) - A Hacker News API wrapper
 * [nexmo-crystal ★1](timcraft/nexmo-crystal) - [Nexmo REST API](https://docs.nexmo.com/) client
 * [ocean_kit ★2](osfx/ocean_kit) - [Digital Ocean v2 API](https://developers.digitalocean.com/documentation/v2) client
 * [open_exchange_rates ★8](osfx/open_exchange_rates) - A library to access [Open Exchange Rates](https://openexchangerates.org/) API
 * [openweather.cr ★3 ⏳1Y](lucasocon/openweather.cr) - A wrapper for the Openweather API
 * [pullword ★1](googya/pullword) - A package to use [pullword](http://pullword.com/)
 * [raven.cr](https://github.com/sija/raven.cr) - Raven is a client for [Sentry ★12747](getsentry/sentry)
 * [shorturl.cr ★7](veelenga/shorturl.cr) - A library to use URL shortening services
 * [slack.cr ★5](DougEverly/slack.cr) - A Slack [Real Time Messaging API](https://api.slack.com/rtm) WebSocket client library
 * [soundcloud-crystal ★9 ⏳1Y](sferik/soundcloud-crystal) - A library to access the SoundCloud API
 * [spotify.cr ★27](marceloboeira/spotify.cr) - A library to access the Spotify API
 * [TelegramBot](https://github.com/hangyas/TelegramBot) - A wrapper for the Telegram Bot API
 * [twitter-crystal ★48](sferik/twitter-crystal) - A library to access the Twitter API
 * [wit-crystal ★9](spalladino/wit-crystal) - Crystal SDK for [wit.ai](https://wit.ai/)

## Virtualization
 * [backed_file_system ★45](schovi/baked_file_system) - Virtual file system implementation
 * [rcpu ★30](ddfreyne/rcpu) - A virtual machine emulator and assembler

## Web Frameworks
 * [amatista ★50 ⏳1Y](werner/amatista) - A web framework to create quick applications
 * [amber ★29](Amber-Crystal/amber) - Open source efficient and cohesive web application framework
 * [amethyst ★504](Codcore/Amethyst) - A Rails inspired web-framework
 * [carbon-crystal ★43 ⏳1Y](benoist/carbon-crystal) - A framework with Rails in mind
 * [chocolate ★10 ⏳1Y](Grabli66/chocolate) - Simple web framework and template engine
 * [frost ★96 ⏳1Y](ysbaddaden/frost) - Full featured MVC Web Framework, largely inspired by Ruby on Rails
 * [iceberg ★25 ⏳1Y](adlerhsieh/iceberg) - A full-stack web framework
 * [kemal](https://github.com/sdogruyol/kemal) - Lightning Fast, Super Simple web framework. Inspired by Sinatra
 * [kemalyst](https://github.com/drujensen/kemalyst) - A Rails like framework inspired by Kemal but includes the kitchen sink
 * [lattice-core ★37](jasonl99/lattice-core) - A WebSocket-first object-oriented framework (based on Kemal)
 * [mustafa ★27](guvencenanguvenal/mustafa) - Simple MVC framework

## Web Servers
 * [fast-http-server ★96](sdogruyol/fast-http-server) - Super fast, zero configuration command line HTTP Server
 * [kamber ★140](f/kamber) - Blog server based on Kemal
 * [prax.cr ★86](ysbaddaden/prax.cr) - Rack proxy server for development
 * [serve ★10](SuperPaintman/serve) - Command line static HTTP server

# Community
 * [Crystal Shards on Twitter](https://twitter.com/shardscrystal)
 * [Crystal weekly newsletters](http://www.crystalweekly.com/)
 * [Gitter](https://gitter.im/crystal-lang/crystal)
 * [Google Group](https://groups.google.com/forum/?fromgroups#!forum/crystal-lang)
 * [IRC](http://irc.lc/freenode/crystal-lang) - #crystal-lang on Freenode
 * [Metaruby](https://metaruby.com/c/crystal-forum) - Crystal Forum on Metaruby
 * [Reddit](https://www.reddit.com/r/crystal_programming)
 * [Slack Group](http://crystal.pine.moe/en/)
 * [Stackoverflow](http://stackoverflow.com/tags/crystal-lang/info)

# Resources
 * [Crystal for Rubyists](http://www.crystalforrubyists.com/) - free book to bootstrap your Crystal journey
 * [crystal-lang.org](http://crystal-lang.org) - Official language site

## Official Documentation Translations
 * [br.crystal-lang.org](http://br.crystal-lang.org/) - Brazilian
 * [ja.crystal-lang.org](http://ja.crystal-lang.org/) - Japanese
 * [kr.crystal-lang.org](https://kr.crystal-lang.org/) - Korean
 * [ru.crystal-lang.org](http://ru.crystal-lang.org/) - Russian
 * [tw.crystal-lang.org](http://tw.crystal-lang.org/) - Chinese Traditional

# Services and Apps
 * [carc.in](https://carc.in/) - A web service that runs your code and displays the result
 * [Crank ★22](arktisklada/crank) - A Procfile-based application manager (like Foreman)
 * [crystalshards.herokuapp.com](https://crystalshards.herokuapp.com/), [crystalshards.xyz](http://crystalshards.xyz/) - Web services that list all available Crystal shards
 * [DeBot ★29](jhass/DeBot) - IRC bot written in Crystal
 * [fikri ★43](askn/fikri) - Simple CLI To-Do App
 * [icr ★158](greyblake/crystal-icr) - Interactive console for Crystal (like IRB for Ruby)
 * [nes ★25 ⏳1Y](romeroadrian/nes.cr) - A NES emulator
 * [shards.rocks](https://shards.rocks/) - Service that manages dependencies inspired by [Gemnasium](https://gemnasium.com/) and [David](https://david-dm.org/)
 * [torrent ★19](Papierkorb/torrent) - A BitTorrent client
 * [vicr](https://github.com/veelenga/vicr.git) - Vim-like Interactive CRystal

# Tools
 * [crystal-ctags ★5](SuperPaintman/crystal-ctags) - Ctags generator for Crystal
 * [crystal-dash-docset ★3](Sija/crystal-dash-docset) - [Dash](https://kapeli.com/dash) docset generator

## DevOps
 * [crystal-cookbook ★3 ⏳1Y](vjdhama/crystal-cookbook) - Chef cookbook for installing crystal

## Editor Plugins
 * Atom
   * [crystal-tools](https://atom.io/packages/crystal-tools) - Enables built in tools in Crystal compiler
   * [language-crystal-actual](https://atom.io/packages/language-crystal-actual) - Crystal language support in Atom
   * [linter-crystal](https://atom.io/packages/linter-crystal) - Lint Crystal using the Crystal compiler in Atom
 * Emacs
   * [emacs-crystal-mode ★13](dotmilk/emacs-crystal-mode) - Crystal language support for Emacs
   * [play-crystal.el ★0](veelenga/play-crystal.el) - [play.crystal-lang.org](https://play.crystal-lang.org/#/cr) integration in Emacs
 * Spacemacs
   * [crystal-spacemacs-layer ★8](juanedi/crystal-spacemacs-layer) - Spacemacs contribution layer for Crystal
 * Sublime
   * [sublime-crystal ★38](crystal-lang/sublime-crystal) - Crystal syntax highlighting for sublime Text
 * TextMate
   * [Crystal.tmbundle ★3](huacnlee/Crystal.tmbundle) - Crystal syntax highlighting, compile, format command, snippets
 * Vim
   * [carcin.vim ★5 ⏳1Y](MakeNowJust/carcin.vim) - Vim plugin to provide utility functions for carc.in
   * [vim-crystal ★164](rhysd/vim-crystal) - Vim filetype support for Crystal
   * [vim-slang](https://github.com/isaacsloan/vim-slang) - Vim filetype support for Slang Templating Engine
 * Visual Studio Code
   * [vscode-crystal ★10](g3ortega/vscode-crystal) - Crystal language support in VSCode
   * [vscode-crystal-ide ★19](kofno/crystal-ide) - Crystal IDE powered by [Language Server Protocol](https://code.visualstudio.com/blogs/2016/06/27/common-language-protocol)

## Shell plugins
 * [crystal-zsh ★15](veelenga/crystal-zsh) - .oh-my-zsh plugin
---
<p align="center">
	This list is a copy of <a href="veelenga/awesome-crystal">veelenga/awesome-crystal</a> with ranks
</p>
