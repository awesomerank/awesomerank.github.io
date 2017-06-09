<h1 align="center">
Ranked awesome lists, all in one place
</h1>
<p align="center">
	This list is a copy of <a href="http://github.com/veelenga/awesome-crystal">veelenga/awesome-crystal</a> with ranks
</p>
---
# Awesome Crystal [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg) ★59088](https://github.com/sindresorhus/awesome) [![Build Status](https://travis-ci.org/veelenga/awesome-crystal.svg)](https://travis-ci.org/veelenga/awesome-crystal)

A curated list of awesome Crystal code and resources. Inspired by [awesome](https://github.com/sindresorhus/awesome) and [awesome-awesomeness ★18868](https://github.com/bayandin/awesome-awesomeness).
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
 * [aho_corasick ★1](https://github.com/chenkovsky/aho_corasick) - AhoCorasick algorithm
 * [crystal-linked-list ★3](https://github.com/abvdasker/crystal-linked-list) - Implementation of Linked List
 * [crystaledge ★4](https://github.com/unn4m3d/crystaledge) - A pure Vector Math library
 * [crystalg ★8](https://github.com/TobiasGSmollett/crystalg) - A Generic Algorithm Library
 * [crystalline ★68](https://github.com/jtomschroeder/crystalline) - A collection of containers and algorithms
 * [delimiter_tree ★7](https://github.com/drujensen/delimiter_tree) - A tree structure that is built using a delimiter
 * [edits.cr ★4](https://github.com/tcrouch/edits.cr) - Collection of edit distance algorithms
 * [heap.cr ★1](https://github.com/chenkovsky/heap.cr) - Implementation of heap data structure
 * [miller_rabin ★0](https://github.com/kuende/miller_rabin) - Implements [Miller-Rabin](https://en.wikibooks.org/wiki/Algorithm_Implementation/Mathematics/Primality_Testing) algorithm to check if a number is prime
 * [multiset.cr ★1](https://github.com/tcrouch/multiset.cr) - Implementation of a multiset
 * [murmur3 ★1](https://github.com/kuende/murmur3) - Implementation of Murmur3 hash algorithm used by Cassandra
 * [primes ★2](https://github.com/dkhofer/primes) - Library for testing if a number is prime and finding its prime factorization
 * [radix ★23](https://github.com/luislavena/radix) - Radix Tree implementation
 * [ranger ★2](https://github.com/akwiatkowski/ranger) - Range object operation library
 * [text ★8](https://github.com/johnjansen/text) - A collection of phonetic algorithms

## Api Builders
 * [crystal_api ★50](https://github.com/akwiatkowski/crystal_api) - Simple PostgreSQL REST API with Rails devise-like auth
 * [kemal-rest-api ★2](https://github.com/blocknotes/kemal-rest-api) - A library to create RESTful API with Kemal

## C bindings
 * [asound-cr ★1](https://github.com/TamasSzekeres/asound-cr) - Bindings for ALSA/libasound
 * [cairo-cr ★0](https://github.com/TamasSzekeres/cairo-cr) - Bindings for [Cairo](https://cairographics.org/) graphics library
 * [crass ★5](https://github.com/vonKingsley/crass) - Bindings for libsass
 * [crt.cr ★7](https://github.com/maiha/crt.cr) - Bindings for libncursesw and crt
 * [crystal-dbus](https://github.com/BlaXpirit/crystal-dbus) - Bindings to D-Bus
 * [crystal-gsl ★9](https://github.com/ruivieira/crystal-gsl) - GNU Scientific Library bindings
 * [crystal-liblmdb ★3](https://github.com/timuckun/crystal-liblmdb) - Bindings for the Symas LMDB database
 * [crystal-libpcap ★5](https://github.com/puppetpies/crystal-libpcap) - Bindings for libpcap
 * [crystal-libtar ★4](https://github.com/puppetpies/crystal-libtar) - Bindings for libtar
 * [crystal_av ★3](https://github.com/kofno/crystal_av) - Bindings to [ClamAV](https://www.clamav.net/) anti-virus
 * [curl-crystal ★4](https://github.com/blocknotes/curl-crystal) - Bindings for [libcurl](https://curl.haxx.se/libcurl/)
 * [curses ★3 ⏳1Y](https://github.com/ruivieira/curses) - Bindings for the curses library
 * [duktape.cr](https://github.com/jessedoyle/duktape.cr) - Bindings for the [Duktape ★2722](https://github.com/svaarala/duktape) javascript engine
 * [glfw ★0](https://github.com/lirith-engine/glfw) - GLFW bindings
 * [gphoto2.cr ★5](https://github.com/Sija/gphoto2.cr) - Bindings for the [libgphoto2](http://www.gphoto.org/) library
 * [icu.cr ★1](https://github.com/olbat/icu.cr) - Bindings for the [ICU](http://site.icu-project.org/) library
 * [java.cr ★6](https://github.com/ysbaddaden/java.cr) - Java Native Interface (JNI) bindings (and generator)
 * [kt ★1](https://github.com/kuende/kt) - Bindings for [Kyoto Tycoon](http://fallabs.com/kyototycoon/)
 * [libmagic-crystal ★2](https://github.com/pablotron/libmagic-crystal) - Bindings for libmagic
 * [libnotify.cr ★9](https://github.com/splattael/libnotify.cr) - Bindings for Libnotify
 * [libui.cr](https://github.com/Fusion/libui.cr) - Bindings for [libui ★4372](https://github.com/andlabs/libui)
 * [nanomsg.cr ★0](https://github.com/chenkovsky/nanomsg.cr) - Bindings for nanomsg
 * [openssl.cr ★12](https://github.com/datanoise/openssl.cr) - Bindings for OpenSSL library
 * [pcap.cr ★8](https://github.com/maiha/pcap.cr) - Bindings for libpcap
 * [posix ★16](https://github.com/ysbaddaden/posix) - POSIX/C bindings
 * [serialport.cr ★7](https://github.com/Sija/serialport.cr) - Bindings for [libserialport](http://sigrok.org/wiki/Libserialport) library
 * [snappy-crystal ★3 ⏳1Y](https://github.com/benoist/snappy-crystal) - Bindings for Snappy library
 * [soundfile ★0](https://github.com/mjago/soundfile) - Bindings for [libsndfile](http://www.mega-nerd.com/libsndfile/) library
 * [ssh2.cr ★21](https://github.com/datanoise/ssh2.cr) - Bindings for libssh2 library
 * [tensorflow.cr](https://github.com/fazibear/tensorflow.cr) - Bindings for [TensorFlow ★58822](https://github.com/tensorflow/tensorflow)
 * [termbox-crystal](https://github.com/andrewsuzuki/termbox-crystal) - Bindings and extension library for [termbox ★1033](https://github.com/nsf/termbox) (terminal UI library)
 * [x11-cr ★1](https://github.com/TamasSzekeres/x11-cr) - X11 bindings
 * [zeromq-crystal ★18](https://github.com/benoist/zeromq-crystal) - Bindings for ZeroMQ

## Caching
 * [Bloom Filter ★12 ⏳1Y](https://github.com/greyblake/crystal-bloom_filter) - Implementation of Bloom filter
 * [bojack ★47](https://github.com/marceloboeira/bojack) - A non-reliable in-memory key-value store
 * [crystal-kiwi ★17](https://github.com/greyblake/crystal-kiwi) - A unified interface for key-value stores
 * [crystal-memcached ★19](https://github.com/comandeo/crystal-memcached) - Implementation of a memcached client
 * [Nuummite ★6](https://github.com/CodeSteak/Nuummite) - A tiny persistent embedded key-value store

## Cli Builders
 * [admiral ★20](https://github.com/jwaldrip/admiral.cr) - A robust DSL for writing command line interfaces
 * [cli ★39](https://github.com/mosop/cli) - Library for building command-line interface applications
 * [clim ★8](https://github.com/at-grandpa/clim) - Slim command line interface builder
 * [commander ★63](https://github.com/mrrooijen/commander) - Command-line interface builder
 * [completion ★37](https://github.com/f/completion) - Easy command line completion engine
 * [docopt ★8](https://github.com/chenkovsky/docopt.cr) - A [docopt.org](http://docopt.org) port
 * [optarg ★9](https://github.com/mosop/optarg) - Yet another library for parsing command-line options and arguments

## Cli Utils
 * [progress ★88](https://github.com/askn/progress) - [==..] Progress bar
 * [spinner ★35](https://github.com/askn/spinner) - Terminal Spinner
 * [terminal_table.cr ★11](https://github.com/benoist/terminal_table.cr) - Simple ASCII table generator

## Configuration
 * [ambience ★11 ⏳1Y](https://github.com/vjdhama/ambience) - Simple app configuration using `ENV`
 * [cr-dotenv ★20](https://github.com/gdotdesign/cr-dotenv) - Loads .env file
 * [crystal-toml ★23](https://github.com/manastech/crystal-toml) - TOML parser
 * [dockerfile.cr ★1](https://github.com/keplersj/dockerfile.cr) - Dockerfile Parsing Library
 * [zq ★2](https://github.com/colstrom/zq) - Command-line ZPL processor

## Converters
 * [moola](https://github.com/dorkrawk/moola) - Library for dealing with money and conversion (inspired by [RubyMoney ★1757](https://github.com/RubyMoney/money))
 * [ms ★0](https://github.com/SuperPaintman/ms) - Library to easily convert various time formats to milliseconds and milliseconds to human readable format
 * [turkish-number ★5](https://github.com/izniburak/turkish-number) - Turn integers into the Turkish words
 * [wkhtmltopdf-crystal ★2](https://github.com/blocknotes/wkhtmltopdf-crystal) - Bindings / wrapper for libwkhtmltox (HTML to PDF / image converter)

## Data Generators
 * [faker ★63](https://github.com/askn/faker) - A library for generating fake data
 * [hashids.cr ★17](https://github.com/splattael/hashids.cr) - A library to generate YouTube-like ids from one or many numbers

## Database Drivers
 * [crystal-db ★67](https://github.com/crystal-lang/crystal-db) - Common db api
 * [crystal-leveldb ★15](https://github.com/greyblake/crystal-leveldb) - Crystal bindings for LevelDB
 * [crystal-monetdb-libmapi ★1](https://github.com/puppetpies/crystal-monetdb-libmapi) - Bindings for MonetDB
 * [crystal-mysql ★36](https://github.com/waterlink/crystal-mysql) - Basic MySQL bindings
 * [crystal-mysql ★23](https://github.com/crystal-lang/crystal-mysql) - MySQL connector for Crystal
 * [crystal-pg ★172](https://github.com/will/crystal-pg) - A Postgres driver
 * [crystal-redis ★162](https://github.com/stefanwille/crystal-redis) - Full featured Redis client
 * [crystal-sqlite3 ★38](https://github.com/crystal-lang/crystal-sqlite3) - SQLite3 bindings
 * [eventql-crystal ★5](https://github.com/measurechina/eventql-crystal) - EventQL driver
 * [influxdb.cr ★10](https://github.com/jeromegn/influxdb.cr) - InfluxDB driver
 * [mongo.cr ★51](https://github.com/datanoise/mongo.cr) - Binding for MongoDB C driver
 * [rethinkdb-crystal](https://github.com/lbguilherme/rethinkdb-crystal) - RethinkDB Driver
 * [rocksdb.cr ★8](https://github.com/maiha/rocksdb.cr) - RocksDB client

## Database Tools
 * [crecto-admin ★2](https://github.com/Crecto/crecto-admin) - Admin dashboard for Crecto and your database
 * [micrate ★54](https://github.com/juanedi/micrate) - Database migration tool

## Development Tools
 * [guardian ★158](https://github.com/f/guardian) - File change watcher for Crystal and Non-Crystal libs
 * [kemal-watcher ★3](https://github.com/faustinoaq/kemal-watcher) - Kemal plugin to watch files and live-reload the browser
 * [sentry ★61](https://github.com/samueleaton/sentry) - Watches src files, rebuilds/reruns application on file changes
 * [sentry-run ★3](https://github.com/faustinoaq/sentry-run) - Reload code changes using Sentry.run
 * [watchbird ★6](https://github.com/agatan/watchbird) - Monitors directories and files, runs tasks automatically
 * [watcher ★3](https://github.com/faustinoaq/watcher) - Watch file changes using File.stat

## Email
 * [CrystalEmail ★8](https://github.com/Nephos/CrystalEmail) - A RFC compliant Email validator
 * [devmail ★7](https://github.com/tijn/devmail) - A combined SMTP/POP3-server with volatile mail storage
 * [sendgrid.cr ★6](https://github.com/dlanileonardo/sendgrid.cr) - Simple Sendgrid Client
 * [smtp.cr ★17](https://github.com/raydf/smtp.cr) - Email SMTP client

## Environment Management
 * [asdf-crystal ★5](https://github.com/marciogm/asdf-crystal) - Plugin for asdf version manager
 * [crenv ★133](https://github.com/pine/crenv) - Crystal version manager
 * [rcm.cr ★10](https://github.com/maiha/rcm.cr) - Redis Cluster Manager

## Examples and funny stuff
 * [crsfml-examples](https://github.com/BlaXpirit/crsfml-examples) - Simple games made with CrSFML
 * [crystal-benchmarks-game ★43](https://github.com/kostya/crystal-benchmarks-game) - The Computer Language Benchmarks Game
 * [crystal-by-example ★192](https://github.com/askn/crystal-by-example) - Crystal By Example
 * [Crystal-Maze ★9](https://github.com/Demonstrandum/Crystal-Maze) - A* Path finding for PNG mazes
 * [crystal-patterns ★35](https://github.com/veelenga/crystal-patterns) - Examples of GOF patters
 * [crystal_samples ★25](https://github.com/tbpgr/crystal_samples) - Variety of Crystal samples
 * [crystalized_ruby ★98](https://github.com/phoffer/crystalized_ruby) - Native Ruby extensions written in Crystal
 * [docker-kemal ★7 ⏳1Y](https://github.com/ianblenke/docker-kemal) - An example Dockerized Crystal Kemal project
 * [fast_sleep ★24](https://github.com/asterite/fast_sleep) - Blazing fast (funny) implementation of sleep for Crystal
 * [kemal-chat ★26](https://github.com/sdogruyol/kemal-chat) - Build realtime applications with Kemal and WebSocket
 * [kemal-heroku-example ★1](https://github.com/cagataycali/kemal-heroku-example) - This repository shows, how you can publish your open source apps which powered kemal framework publish as heroku app in seconds
 * [kemal-monetdb-test ★0](https://github.com/puppetpies/kemal-monetdb-test) - MonetDB Kemal test project
 * [kemal-pg-sample ★4 ⏳1Y](https://github.com/sdogruyol/kemal-pg-sample) - Sample app to demonstrate kemal + postgresql usage
 * [kemal-react-chat ★49](https://github.com/f/kemal-react-chat) - Build Realtime Web applications with Kemal and React
 * [kemal-react-pg-chat](https://github.com/Angarsk8/kemal-react-pg-chat) - Chat application developed with Kemal, React, ES2015 and PostgreSQL
 * [kemal-ws-pg-todo-app ★1](https://github.com/Angarsk8/kemal-ws-pg-todo-app) - Realtime Todo application developed with Kemal, Websockets, jQuery, ES2015 and PostgreSQL
 * [kemal-ws-react-pg-todo-app](https://github.com/Angarsk8/kemal-ws-react-pg-todo-app) - Realtime Todo application developed with Kemal, Websockets, React, ES2015 and PostgreSQL
 * [kemal-ws-todo-app ★5](https://github.com/Angarsk8/kemal-ws-todo-app) - Realtime Todo application developed with Kemal and Websockets
 * [kemal_elm_chat ★10](https://github.com/kofno/kemal_elm_chat) - Simple chat server written with Kemal and Elm
 * [lattice-core-card-game ★140](https://github.com/jasonl99/card_game) - A demo web app for (WebSocket-based) lattice-core
 * [medley ★6](https://github.com/jwoertink/medley) - A mixture of music related methods
 * [os-crystal ★27](https://github.com/lbguilherme/os-crystal) - x86 Kernel implemented in Crystal
 * [rocky ★69](https://github.com/codingphasedotcom/rocky) - React Over Crystal Kemal and Yarn
 * [try.cr ★12](https://github.com/maiha/try.cr) - Try monad
 * [xcrystal ★26](https://github.com/exercism/xcrystal) - Exercism exercises

## Framework Components
 * [artanis ★34](https://github.com/ysbaddaden/artanis) - Sinatra-like DSL (abusing macros)
 * [cr-melon ★5](https://github.com/gdotdesign/cr-melon) - Class based Http APIs
 * [crystal-mime ★14](https://github.com/spalger/crystal-mime) - Mimetypes for Crystal
 * [kave ★15](https://github.com/jwoertink/kave) - Kemal API Version Extension
 * [kemal-auth-token ★11](https://github.com/akwiatkowski/kemal-auth-token) - Kemal middleware to authentication via HTTP header token using JWT
 * [kemal-comments ★2 ⏳1Y](https://github.com/TyanNN/kemal-comments) - Simple comments for Kemal site
 * [kemal-flash ★4](https://github.com/neovintage/kemal-flash) - Temporary storage between actions in Kemal
 * [kemal-monetdb ★0](https://github.com/puppetpies/kemal-monetdb) - MonetDB Data connection for Kemal
 * [kemal-mysql ★13](https://github.com/sdogruyol/kemal-mysql) - Easily add MySQL database to Kemal
 * [kemal-redis ★7](https://github.com/sdogruyol/kemal-redis) - Easily add Redis to Kemal
 * [kemal-session ★17](https://github.com/kemalcr/kemal-session) - Session handler for Kemal
 * [kemalyst-i18n ★1](https://github.com/TechMagister/kemalyst-i18n) - i18n support for Kemalyst
 * [mime-types.cr ★4](https://github.com/jwaldrip/mime-types.cr) - A port of the Ruby MIME-types library
 * [multi-auth ★1](https://github.com/msa7/multi_auth) - Standardized multi-provider OAuth2 authentication (inspired by omniauth)
 * [request_id ★0](https://github.com/SuperPaintman/request-id) - Middleware for generates / pick up a unique request ID for Crystal servers
 * [response_time ★6](https://github.com/SuperPaintman/response-time) - Response time for Crystal servers (pure http server, kemal, etc.)
 * [spec-kemal](https://github.com/sdogruyol/spec-kemal) - Easy testing for Kemal

## Game Development
 * [CrSFML ★120](https://github.com/oprypin/crsfml) - Bindings to [SFML](http://www.sfml-dev.org/) multimedia/game library
 * [crystal-chipmunk](https://github.com/BlaXpirit/crystal-chipmunk) - Bindings for [Chipmunk](http://chipmunk-physics.net/), a fast and lightweight 2D game physics library
 * [flight-crusader ★9](https://github.com/umurgdk/flight-crusader) - POC top down flight game
 * [glove ★22](https://github.com/ddfreyne/glove) - A library for gaming development
 * [inari ★7](https://github.com/ddfreyne/inari) - A collection of games using Glove as the game engine
 * [medico ★0](https://github.com/konovod/medico) - Game about a medieval doctor
 * [mos_game ★6](https://github.com/bararchy/mos_game) - Mini Offline Singleplayer game

## HTML/XML Parsing
 * [crystagiri](https://github.com/madeindjs/Crystagiri) - An Html Reader / parser like [Nokogiri ★4409](https://github.com/sparklemotion/nokogiri) Ruby gem
 * [gumbo-crystal](https://github.com/blocknotes/gumbo-crystal) - Bindings for [Gumbo ★4025](https://github.com/google/gumbo-parser), an HTML5 parsing library made by Google
 * [hq.cr ★2](https://github.com/maiha/hq.cr) - Simple wrapper for crystal-xml
 * [modest ★24](https://github.com/kostya/modest) - CSS selectors for HTML5 Parser myhtml
 * [myhtml ★19](https://github.com/kostya/myhtml) - Fast HTML5 Parser

## HTTP
 * [crul ★83](https://github.com/porras/crul) - Command line HTTP client
 * [cryload ★97](https://github.com/sdogruyol/cryload) - HTTP benchmarking tool
 * [crystal-cossack ★47](https://github.com/greyblake/crystal-cossack) - Simple flexible HTTP client
 * [etag ★0](https://github.com/SuperPaintman/etag) - Library to generate HTTP ETags
 * [helmet ★10](https://github.com/EvanHahn/crystal-helmet) - Set security-related HTTP headers
 * [http-protection ★9](https://github.com/rogeriozambon/http-protection) - Protection against typical web attacks
 * [http2 ★32](https://github.com/ysbaddaden/http2) - HTTP/2 Protocol Implementation
 * [http_distributor ★0](https://github.com/Nephos/http_distributor) - HTTP server which allows sneaky http requests
 * [http_parser.cr](https://github.com/kostya/http_parser.cr) - Wrapper for [Http Parser lib ★3261](https://github.com/nodejs/http-parser)
 * [keyer_cr ★0](https://github.com/danielpclark/keyer_cr) - Adds HTTP GET/POST parameter parsing as a Hash-like object
 * [multipart.cr ★9](https://github.com/RX14/multipart.cr) - Adds multipart and multipart/form-data support to the crystal standard library
 * [resp-crystal ★4](https://github.com/soveran/resp-crystal) - Lightweight RESP client
 * [session](https://github.com/porras/session.git) - Cookie based sessions in Crystal HTTP applications

## Image processing
 * [magickwand-crystal ★13](https://github.com/blocknotes/magickwand-crystal) - Bindings for [MagickWand](https://www.imagemagick.org/script/magick-wand.php), the C interface for ImageMagick processing libraries
 * [stumpy_gif](https://github.com/l3kn/stumpy_gif) - Write (animated) GIF images
 * [stumpy_png](https://github.com/l3kn/stumpy_png) - Read and write PNG images

## Implementations/Compilers
 * [charly](https://github.com/charly-lang) - Charly Programming Language
 * [cltk ★29](https://github.com/ziprandom/cltk) - A crystal port of the Ruby Language Toolkit
 * [cppize ★16](https://github.com/unn4m3d/cppize) - Crystal-to-C++ transpiler
 * [crisp ★17](https://github.com/rhysd/Crisp) - Lisp dialect implemented with Crystal
 * [crow ★34](https://github.com/geppetto-apps/crow) - Transpile/compile Crystal to [Flow](https://flowtype.org/)
 * [crystal ★8192](https://github.com/crystal-lang/crystal) - Crystal itself is written in Crystal
 * [csmli ★1](https://github.com/david50407/csmli) - Mini-Lisp interpreter
 * [NuummiteOS ★37](https://github.com/TheKernelCorp/NuummiteOS) - An OS written in Crystal as a Proof of Concept
 * [onix ★48](https://github.com/ozra/onyx-lang) - ONYX Programming Language
 * [zir ★9](https://github.com/tbrand/zir) - Realizes to write macros in any scripts into any languages

## Logging and monitoring
 * [crometheus](https://gitlab.com/ezrast/crometheus) - A [Prometheus](https://prometheus.io/) client library
 * [crystal-logreader ★0](https://github.com/arcage/crystal-logreader) - Tailing log file
 * [gelf-crystal ★4 ⏳1Y](https://github.com/benoist/gelf-crystal) - A GELF logger
 * [katip ★15](https://github.com/guvencenanguvenal/katip) - JSONbase logger
 * [statsd.cr](https://github.com/miketheman/statsd.cr) - [Statsd ★11427](https://github.com/etsy/statsd) client library
 * [syslog.cr ★3](https://github.com/comandeo/syslog.cr) - Implementation of Syslog client

## Markdown/Text Processors
 * [html-pipeline ★2](https://github.com/huacnlee/html-pipeline) - HTML processing filters and utilities
 * [remarkdown ★4](https://github.com/huacnlee/remarkdown) - GFM for Crystal

## Misc
 * [aasm.cr ★18](https://github.com/veelenga/aasm.cr) - Easy to use finite state machine for Crystal classes
 * [accord ★9](https://github.com/neovintage/accord) - Sharable validations for Crystal objects
 * [acorn ★7](https://github.com/rmosolgo/acorn) - State Machine Compiler for Crystal
 * [any_hash.cr ★6](https://github.com/Sija/any_hash.cr) - Recursive Hash with better JSON::Any included
 * [chalk-box ★17](https://github.com/azukiapp/crystal-chalk-box) - Terminal color toolbox, check support and colorized (without String monkey patch)
 * [circuit_breaker ★12](https://github.com/TPei/circuit_breaker) - Implementation of the circuit breaker pattern
 * [clamd.cr ★1](https://github.com/RX14/clamd.cr) - Client for the clamd antivirus server
 * [crdoc ★6 ⏳1Y](https://github.com/rhysd/crdoc) - CLI tool to search and open documentation
 * [crystal-binary_parser ★0](https://github.com/DanSnow/crystal-binary_parser) - Binary parser
 * [crystal-diff ★14](https://github.com/MakeNowJust/crystal-diff) - A Crystal sequence differencing implementation
 * [crystal-futures ★36](https://github.com/dhruvrajvanshi/crystal-futures) - Future type implementation
 * [crystal-i18n ★7](https://github.com/whity/crystal-i18n) - Internationalization library
 * [crz ★15](https://github.com/dhruvrajvanshi/crz) - Functional programming library
 * [denetmen ★19](https://github.com/izniburak/denetmen) - Useful micro validator / check library
 * [emoji.cr ★11](https://github.com/veelenga/emoji.cr) - Emoji library
 * [evented ★25 ⏳1Y](https://github.com/krisleech/evented) - A micro library to publish and subscribe for Crystal objects
 * [executable_path](https://github.com/kostya/executable_path) - Portable current executable's path
 * [hoop](https://github.com/hoopcr/hoop) - Building native OSX apps
 * [html_builder ★22](https://github.com/crystal-lang/html_builder) - DSL for creating HTML
 * [immutable ★101](https://github.com/lucaong/immutable) - Implementation of thread-safe, persistent, immutable collections
 * [inflector.cr ★14](https://github.com/phoffer/inflector.cr) - Singularize, pluralize, camelize, etc (port from ActiveSupport)
 * [kreal ★38](https://github.com/f/kreal) - Model sharing & RPC library built on and works with Kemal seamlessly
 * [lambda.cr ★26](https://github.com/f/lambda.cr) - Uniformed function call syntax
 * [lirith ★4](https://github.com/lirith-engine/lirith) - Graphics engine
 * [manual-generator ★0](https://github.com/blocknotes/manual-generator) - Tool to generate PDF manuals from documentation sites
 * [metaclass ★2](https://github.com/mosop/metaclass) - A library for manipulating class-level definitions
 * [observable ★4](https://github.com/TPei/observable) - Implementation of the Observer pattern
 * [ramlrenderer ★4](https://github.com/beno/ramlrenderer) - HTML doc builder for RAML 1.0
 * [raytracer-crystal](https://github.com/l3kn/raytracer-crystal) - CPU Raytracer with examples
 * [shell.cr ★6](https://github.com/dmytro/shell.cr) - Small simplistic helper class for executing shell commands
 * [syscall.cr ★9](https://github.com/kubo39/syscall.cr) - Raw syscall interface
 * [tren ★65](https://github.com/sdogruyol/tren) - Give your SQL some love
 * [ulid ★2](https://github.com/SuperPaintman/ulid) - Universally Unique Lexicographically Sortable Identifier (ULID)

## Networking
 * [amqp.cr ★25](https://github.com/datanoise/amqp.cr) - AMQP 0.9.1 client with RabbitMQ extensions
 * [bson.cr ★7 ⏳1Y](https://github.com/jeromegn/bson.cr) - Native BSON implementation
 * [CrystalIrc ★8](https://github.com/Meoowww/CrystalIrc) - IRC implementation (Client, Server, Bots)
 * [fast_irc.cr ★5](https://github.com/RX14/fast_irc.cr) - Fast IRC parser/generator
 * [ipaddress.cr ★8](https://github.com/Sija/ipaddress.cr) - Library to handle IPv4 and IPv6 addresses
 * [jwt ★51](https://github.com/greyblake/crystal-jwt) - Implementation of JWT (JSON Web Token)
 * [msgpack-crystal ★47](https://github.com/benoist/msgpack-crystal) - MessagePack library
 * [wire ★9](https://github.com/puppetpies/WIre) - A packet analyzer

## ORM/ODM Extensions
 * [active_record.cr ★150](https://github.com/waterlink/active_record.cr) - Active Record pattern implementation
 * [crecto](https://github.com/fridgerator/crecto) - Database wrapper, based on Ecto
 * [jennifer ★45](https://github.com/imdrasil/jennifer.cr) - Active Record pattern implementation with flexible query chainable builder and migration system
 * [kemalyst-model](https://github.com/drujensen/kemalyst-model) - ORM Model for the Kemalyst Framework
 * [ohm-crystal ★34](https://github.com/soveran/ohm-crystal) - Object-hash mapping library for Redis
 * [redis-tsv.cr ★4](https://github.com/maiha/redis-tsv.cr) - Import and export data from Redis in TSV format
 * [selenite-db ★2](https://github.com/xdougx/selenite-db) - A simple persistency-model based library
 * [stal-crystal ★2](https://github.com/soveran/stal-crystal) - Set algebra solver for Redis
 * [topaz](https://github.com/tbrand/topaz) - A simple and useful db wrapper

## Package Management
 * [shards](https://github.com/ysbaddaden/shards) - Dependency manager for the Crystal

## Processes and Threads
 * [daemonize.cr ★9](https://github.com/DougEverly/daemonize.cr) - Crystal process daemonizer
 * [neph ★23](https://github.com/tbrand/neph) - A modern command line job processor that can execute jobs concurrently
 * [promise](https://github.com/jwaldrip/promise-cr) - A Promise Implementation

## Project Generators
 * [bindgencr ★1](https://github.com/TechMagister/bindgencr) - Generator of bindings based on castxml output
 * [crystal_lib ★71](https://github.com/crystal-lang/crystal_lib) - Automatic binding generator for native libraries
 * [fez ★29](https://github.com/jwoertink/fez) - A Kemal application generator
 * [generate ★19](https://github.com/generate-cr/generate) - A tool for generating whole Crystal project structure, or any part of it during lifetime of project
 * [kgen](https://github.com/TechMagister/kemalyst-generator) - Kemalyst command line tool for console, init, generate (scaffolding), and watch.
 * [libgen ★7](https://github.com/olbat/libgen) - Automatic bindings generator configured using JSON/YAML files
 * [skaf ★1](https://github.com/elorest/skaf) - Scaffolding for Kemal
 * [wasp ★4](https://github.com/icyleaf/wasp) - Static Site Generator

## Queue
 * [crystal-resque-client ★2 ⏳1Y](https://github.com/pine/crystal-resque-client) - Simple Resque queue client
 * [dispatch ★5](https://github.com/bmulvihill/dispatch) - In memory asynchronous job processing
 * [disque-cr](https://github.com/foca/disque-cr) - Client for [Disque ★6190](https://github.com/antirez/disque) queueing system
 * [sidekiq.cr ★349](https://github.com/mperham/sidekiq.cr) - Simple, efficient job processing

## Routing
 * [beryl ★17 ⏳1Y](https://github.com/luislavena/beryl) - Action-focused HTTP routing library
 * [crouter ★22](https://github.com/jreinert/crouter) - A standalone router
 * [crystal-routing ★19 ⏳1Y](https://github.com/bcardiff/crystal-routing) - Extensible library to deal with http request and string based routing
 * [router-simple.cr ★5 ⏳1Y](https://github.com/karupanerura/router-simple.cr) - Simple path router
 * [router.cr ★44](https://github.com/tbrand/router.cr) - Minimum but powerful http router for HTTP::Server
 * [toro ★57](https://github.com/soveran/toro) - Tree Oriented Routing

## Scheduling
 * [cron_scheduler ★19](https://github.com/kostya/cron_scheduler) - Job scheduler with crontab patterns
 * [quartz ★1](https://github.com/andrewhamon/quartz) - Crystal clear timers
 * [schedule.cr ★7](https://github.com/hugoabonizio/schedule.cr) - Run periodic tasks

## Science and Data analysis
 * [chizge](https://github.com/aladagemre/chizge) - A Network (Graph) Analysis library, inspired by [NetworkX ★2979](https://github.com/networkx/networkx)
 * [crystal-learn ★20](https://github.com/pbrusco/crystal-learn) - Sklearn-like machine-learning library
 * [machine ★13](https://github.com/mathieulaporte/machine) - Simple machine learning algorithm
 * [predict.cr ★4](https://github.com/RX14/predict.cr) - Satellite prediction library using the sgp4 model
 * [scorystal ★2](https://github.com/asafschers/scorystal) - Scoring API for PMML - supports RF and GBM
 * [stats ★3](https://github.com/Nephos/stats) - An expressive implementation of statistical distributions

## Search
 * [hermes ★8](https://github.com/imdrasil/hermes.cr) - Data Mapper pattern implementation for ElastiSearch
 * [query-builder ★28](https://github.com/izniburak/query-builder) - Sql Query Builder library
 * [query.cr ★8](https://github.com/waterlink/query.cr) - Query abstraction
 * [soegen ★11](https://github.com/Ragmaanir/soegen) - Elasticsearch client for Crystal similar to the stretcher gem for ruby

## Task management
 * [cake ★2](https://github.com/axvm/cake) - Production-ready Make-like utility tool
 * [crake ★30 ⏳1Y](https://github.com/MakeNowJust/crake) - Rake-like build utility library. It is just a library, so it does not provide CLI
 * [lake ★8 ⏳1Y](https://github.com/adlerhsieh/lake) - Rake-like task management for Crystal programs
 * [sam ★8](https://github.com/imdrasil/sam.cr) - Another one Rake-like task manager with namespacing and arguments system

## Template Engine
 * [Bunny ★9 ⏳2Y](https://github.com/samsheff/Bunny) - A simple HTML templating language for Crystal, same syntax as erb
 * [crikey](https://github.com/domgetter/crikey) - Templating engine inspired by [Hiccup ★1556](https://github.com/weavejester/hiccup)
 * [crinja ★4](https://github.com/straight-shoota/crinja) - An implementation of the [Jinja2 template engine](http://jinja.pocoo.org/)
 * [crustache ★31](https://github.com/MakeNowJust/crustache) - [{{Mustache}}](https://mustache.github.io) for Crystal
 * [Kilt ★51](https://github.com/jeromegn/kilt) - Abstraction layer for template engines
 * [Slang ★70](https://github.com/jeromegn/slang) - Lightweight, terse, templating language inspired by Ruby's Slim
 * [teeplate ★4](https://github.com/mosop/teeplate) - A library for rendering multiple template files
 * [temel ★32](https://github.com/f/temel) - Extensible HTML::Builder alternative for Crystal, supports custom tag definitions

## Testing
 * [crotest ★15](https://github.com/emancu/crotest) - A tiny and simple test framework
 * [matchi ★0 ⏳1Y](https://github.com/fixcr/matchi) - Collection of expectation matchers
 * [minitest.cr ★48](https://github.com/ysbaddaden/minitest.cr) - Library for unit tests and assertions
 * [mock ★12 ⏳1Y](https://github.com/porras/mock) - Mocking library, inspired by the API of rspec-mocks
 * [mocks.cr ★17](https://github.com/waterlink/mocks.cr) - Mocking library for Crystal
 * [power_assert.cr ★36](https://github.com/rosylilly/power_assert.cr) - Powerful assertion for Crystal
 * [spec2-mocks ★5](https://github.com/waterlink/spec2-mocks.cr) - An adapter of mocks.cr for spec2.cr
 * [spec2.cr ★61](https://github.com/waterlink/spec2.cr) - Enhanced testing library
 * [timecop.cr](https://github.com/waterlink/timecop.cr) - Library for mocking with `Time.now`. Inspired by [timecop ruby gem ★2369](https://github.com/travisjeffery/timecop)
 * [webmock.cr ★33](https://github.com/manastech/webmock.cr) - Library for stubbing `HTTP::Client` requests

## Third-party APIs
 * [airbrake-crystal ★8 ⏳1Y](https://github.com/kyrylo/airbrake-crystal) - A Crystal notifier for [Airbrake](https://airbrake.io)
 * [AnyBar_cr ★4 ⏳1Y](https://github.com/davydovanton/AnyBar_cr) - Simple crystal wrapper for AnyBar library
 * [aws-signer.cr ★6](https://github.com/beanieboi/aws-signer.cr) - This library signs your HTTP requests using AWS v4
 * [awscr-signer ★3](https://github.com/taylorfinnell/awscr-signer) - Sign HTTP::Request objects and generate presigned post forms
 * [bugsnag.cr ★2](https://github.com/gewo/bugsnag.cr) - Bugsnag exception notifier and sidekiq middleware
 * [crystal-connpass ★1 ⏳1Y](https://github.com/pine/crystal-connpass) - Wrapper for the [Connpass](http://connpass.com/) API
 * [crystal-darksky ★4](https://github.com/sb89/crystal-darksky) - Wrapper for the [Dark Sky](https://darksky.net) API
 * [crystal-github ★1](https://github.com/felipeelias/crystal-github) - Wrapper for the [Github](https://github.com/) API
 * [crystal-mondo](https://github.com/barisbalic/crystal-mondo) - A client for the [Mondo API](https://getmondo.co.uk/docs/)
 * [crystal-newrelic ★3](https://github.com/waj/crystal-newrelic) - NewRelic API client
 * [crystal-ovh ★6](https://github.com/ovh/crystal-ovh) - Lightweight Crystal wrapper around [OVH](https://eu.api.ovh.com/)'s API
 * [crystal-qiita ★0 ⏳1Y](https://github.com/pine/crystal-qiita) - A wrapper for the [Qiita](https://qiita.com/) API
 * [crystal-swapi ★2](https://github.com/sb89/crystal-swapi) - Star Wars API (SWAPI) wrapper
 * [crystal_brium ★1](https://github.com/manastech/crystal_brium) - Access Brium's API using Crystal
 * [crystal_slack ★8](https://github.com/manastech/crystal_slack) - A tool that parses Slack slash commands or send incoming web hooks
 * [crystalforce ★3](https://github.com/ucmsky/crystalforce) - Salesforce REST api
 * [docker.cr ★11](https://github.com/jeromegn/docker.cr) - Docker API client
 * [dotacr ★7](https://github.com/azah/dotacr) - Wrapper for Valve's DotA API
 * [fantasy_football_nerd_api ★0](https://github.com/fridgerator/fantasy_football_nerd_api) - A library for the [Fantasy Football Nerd API](http://www.fantasyfootballnerd.com/fantasy-football-api)
 * [gitlab.cr ★8](https://github.com/icyleaf/gitlab.cr) - GitLab API wrapper
 * [glosbe ★3](https://github.com/greyblake/crystal-glosbe) - Client for [Glosbe API](https://glosbe.com/a-api)
 * [google_maps_api ★6](https://github.com/fridgerator/google_maps_api) - Google Maps API
 * [google_translate ★5](https://github.com/greyblake/crystal-google_translate) - Client for Google Translate
 * [gravatar.cr](https://github.com/fg/gravatar.cr.git) - A library to use Gravatar service
 * [hncr ★1](https://github.com/Gangwolf/hncr) - A Hacker News API wrapper
 * [nexmo-crystal ★1](https://github.com/timcraft/nexmo-crystal) - [Nexmo REST API](https://docs.nexmo.com/) client
 * [ocean_kit ★2](https://github.com/osfx/ocean_kit) - [Digital Ocean v2 API](https://developers.digitalocean.com/documentation/v2) client
 * [open_exchange_rates ★8](https://github.com/osfx/open_exchange_rates) - A library to access [Open Exchange Rates](https://openexchangerates.org/) API
 * [openweather.cr ★3 ⏳1Y](https://github.com/lucasocon/openweather.cr) - A wrapper for the Openweather API
 * [pullword ★1](https://github.com/googya/pullword) - A package to use [pullword](http://pullword.com/)
 * [raven.cr](https://github.com/sija/raven.cr) - Raven is a client for [Sentry ★12747](https://github.com/getsentry/sentry)
 * [shorturl.cr ★7](https://github.com/veelenga/shorturl.cr) - A library to use URL shortening services
 * [slack.cr ★5](https://github.com/DougEverly/slack.cr) - A Slack [Real Time Messaging API](https://api.slack.com/rtm) WebSocket client library
 * [soundcloud-crystal ★9 ⏳1Y](https://github.com/sferik/soundcloud-crystal) - A library to access the SoundCloud API
 * [spotify.cr ★27](https://github.com/marceloboeira/spotify.cr) - A library to access the Spotify API
 * [TelegramBot](https://github.com/hangyas/TelegramBot) - A wrapper for the Telegram Bot API
 * [twitter-crystal ★48](https://github.com/sferik/twitter-crystal) - A library to access the Twitter API
 * [wit-crystal ★9 ⏳1Y](https://github.com/spalladino/wit-crystal) - Crystal SDK for [wit.ai](https://wit.ai/)

## Virtualization
 * [backed_file_system ★45](https://github.com/schovi/baked_file_system) - Virtual file system implementation
 * [rcpu ★30](https://github.com/ddfreyne/rcpu) - A virtual machine emulator and assembler

## Web Frameworks
 * [amber ★29](https://github.com/Amber-Crystal/amber) - Open source efficient and cohesive web application framework
 * [amethyst ★504](https://github.com/Codcore/Amethyst) - A Rails inspired web-framework
 * [kemal](https://github.com/sdogruyol/kemal) - Lightning Fast, Super Simple web framework. Inspired by Sinatra
 * [kemalyst](https://github.com/drujensen/kemalyst) - A Rails like framework inspired by Kemal but includes the kitchen sink
 * [lattice-core ★37](https://github.com/jasonl99/lattice-core) - A WebSocket-first object-oriented framework (based on Kemal)
 * [mustafa ★27](https://github.com/guvencenanguvenal/mustafa) - Simple MVC framework

## Web Servers
 * [fast-http-server ★96](https://github.com/sdogruyol/fast-http-server) - Super fast, zero configuration command line HTTP Server
 * [kamber ★140](https://github.com/f/kamber) - Blog server based on Kemal
 * [prax.cr ★86](https://github.com/ysbaddaden/prax.cr) - Rack proxy server for development
 * [serve ★10](https://github.com/SuperPaintman/serve) - Command line static HTTP server

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
 * [Crank ★22](https://github.com/arktisklada/crank) - A Procfile-based application manager (like Foreman)
 * [crystalshards.herokuapp.com](https://crystalshards.herokuapp.com/), [crystalshards.xyz](http://crystalshards.xyz/) - Web services that list all available Crystal shards
 * [DeBot ★29](https://github.com/jhass/DeBot) - IRC bot written in Crystal
 * [fikri ★43](https://github.com/askn/fikri) - Simple CLI To-Do App
 * [icr ★158](https://github.com/greyblake/crystal-icr) - Interactive console for Crystal (like IRB for Ruby)
 * [nes ★25 ⏳1Y](https://github.com/romeroadrian/nes.cr) - A NES emulator
 * [shards.rocks](https://shards.rocks/) - Service that manages dependencies inspired by [Gemnasium](https://gemnasium.com/) and [David](https://david-dm.org/)
 * [torrent ★19](https://github.com/Papierkorb/torrent) - A BitTorrent client
 * [vicr](https://github.com/veelenga/vicr.git) - Vim-like Interactive CRystal

# Tools
 * [crystal-ctags ★5](https://github.com/SuperPaintman/crystal-ctags) - Ctags generator for Crystal
 * [crystal-dash-docset ★3](https://github.com/Sija/crystal-dash-docset) - [Dash](https://kapeli.com/dash) docset generator

## DevOps
 * [crystal-cookbook ★3 ⏳1Y](https://github.com/vjdhama/crystal-cookbook) - Chef cookbook for installing crystal

## Editor Plugins
 * Atom
   * [crystal-tools](https://atom.io/packages/crystal-tools) - Enables built in tools in Crystal compiler
   * [language-crystal-actual](https://atom.io/packages/language-crystal-actual) - Crystal language support in Atom
   * [linter-crystal](https://atom.io/packages/linter-crystal) - Lint Crystal using the Crystal compiler in Atom
 * Emacs
   * [emacs-crystal-mode ★13](https://github.com/dotmilk/emacs-crystal-mode) - Crystal language support for Emacs
   * [play-crystal.el ★0](https://github.com/veelenga/play-crystal.el) - [play.crystal-lang.org](https://play.crystal-lang.org/#/cr) integration in Emacs
 * Spacemacs
   * [crystal-spacemacs-layer ★8](https://github.com/juanedi/crystal-spacemacs-layer) - Spacemacs contribution layer for Crystal
 * Sublime
   * [sublime-crystal ★38](https://github.com/crystal-lang/sublime-crystal) - Crystal syntax highlighting for sublime Text
 * TextMate
   * [Crystal.tmbundle ★3](https://github.com/huacnlee/Crystal.tmbundle) - Crystal syntax highlighting, compile, format command, snippets
 * Vim
   * [carcin.vim ★5 ⏳1Y](https://github.com/MakeNowJust/carcin.vim) - Vim plugin to provide utility functions for carc.in
   * [vim-crystal ★164](https://github.com/rhysd/vim-crystal) - Vim filetype support for Crystal
   * [vim-slang](https://github.com/isaacsloan/vim-slang) - Vim filetype support for Slang Templating Engine
 * Visual Studio Code
   * [vscode-crystal ★10](https://github.com/g3ortega/vscode-crystal) - Crystal language support in VSCode
   * [vscode-crystal-ide ★19](https://github.com/kofno/crystal-ide) - Crystal IDE powered by [Language Server Protocol](https://code.visualstudio.com/blogs/2016/06/27/common-language-protocol)

## Shell plugins
 * [crystal-zsh ★15](https://github.com/veelenga/crystal-zsh) - .oh-my-zsh plugin
---
<p align="center">
	This list is a copy of <a href="http://github.com/veelenga/awesome-crystal">veelenga/awesome-crystal</a> with ranks
</p>

<script>
  (function(i,s,o,g,r,a,m){i['GoogleAnalyticsObject']=r;i[r]=i[r]||function(){
  (i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),
  m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)
  })(window,document,'script','https://www.google-analytics.com/analytics.js','ga');

  ga('create', 'UA-100705027-1', 'auto');
  ga('send', 'pageview');

</script>
