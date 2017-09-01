---
layout: default
title: Awesome Rank for avelino/awesome-go
---

<p align="center">
	This list is a copy of <a href="https://github.com/avelino/awesome-go">avelino/awesome-go</a> with ranks
</p>
---
# Awesome Go [![Build Status](https://travis-ci.org/avelino/awesome-go.svg?branch=master)](https://travis-ci.org/avelino/awesome-go) [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg) ★63835](https://github.com/sindresorhus/awesome) [![Join the chat at https://gitter.im/avelino/awesome-go](https://badges.gitter.im/avelino/awesome-go.svg)](https://gitter.im/avelino/awesome-go?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

A curated list of awesome Go frameworks, libraries and software. Inspired by [awesome-python ★37548](https://github.com/vinta/awesome-python).

### Contributing

Please take a quick gander at the [contribution guidelines](https://github.com/avelino/awesome-go/blob/master/CONTRIBUTING.md) first. Thanks to all [contributors](https://github.com/avelino/awesome-go/graphs/contributors); you rock!

#### *If you see a package or project here that is no longer maintained or is not a good fit, please submit a pull request to improve this file. Thank you!*

### Contents

- [Awesome Go](#awesome-go)
    - [Audio and Music](#audio-and-music)
    - [Authentication and OAuth](#authentication-and-oauth)
    - [Command Line](#command-line)
    - [Configuration](#configuration)
    - [Continuous Integration](#continuous-integration)
    - [CSS Preprocessors](#css-preprocessors)
    - [Data Structures](#data-structures)
    - [Database](#database)
    - [Database Drivers](#database-drivers)
    - [Date and Time](#date-and-time)
    - [Distributed Systems](#distributed-systems)
    - [Email](#email)
    - [Embeddable Scripting Languages](#embeddable-scripting-languages)
    - [Files](#files)
    - [Financial](#financial)
    - [Forms](#forms)
    - [Game Development](#game-development)
    - [Generation and Generics](#generation-and-generics)
    - [Go Compilers](#go-compilers)
    - [Goroutines](#goroutines)
    - [GUI](#gui)
    - [Hardware](#hardware)
    - [Images](#images)
    - [IoT](#iot-internet-of-things)
    - [Logging](#logging)
    - [Machine Learning](#machine-learning)
    - [Messaging](#messaging)
    - [Miscellaneous](#miscellaneous)
    - [Natural Language Processing](#natural-language-processing)
    - [Networking](#networking)
    - [OpenGL](#opengl)
    - [ORM](#orm)
    - [Package Management](#package-management)
    - [Query Language](#query-language)
    - [Resource Embedding](#resource-embedding)
    - [Science and Data Analysis](#science-and-data-analysis)
    - [Security](#security)
    - [Serialization](#serialization)
    - [Template Engines](#template-engines)
    - [Testing](#testing)
    - [Text Processing](#text-processing)
    - [Third-party APIs](#third-party-apis)
    - [Utilities](#utilities)
    - [Validation](#validation)
    - [Version Control](#version-control)
    - [Video](#video)
    - [Web Frameworks](#web-frameworks)
        - [Middlewares](#middlewares)
            - [Actual middlewares](#actual-middlewares)
            - [Libraries for creating HTTP middlewares](#libraries-for-creating-http-middlewares)
        - [Routers](#routers)
    - [Windows](#windows)
    - [XML](#xml)

- [Tools](#tools)
    - [Code Analysis](#code-analysis)
    - [Editor Plugins](#editor-plugins)
    - [Go Tools](#go-tools)
    - [Software Packages](#software-packages)
        - [DevOps Tools](#devops-tools)
        - [Other Software](#other-software)

- [Server Applications](#server-applications)

- [Resources](#resources)
    - [Benchmarks](#benchmarks)
    - [Conferences](#conferences)
    - [E-Books](#e-books)
    - [Twitter](#twitter)
    - [Websites](#websites)
        - [Tutorials](#tutorials)

## Audio and Music

*Libraries for manipulating audio.*

* [flac ★69 ⏳1Y](https://github.com/eaburns/flac) - Native Go FLAC decoder.
* [flac ★49](https://github.com/mewkiz/flac) - Native Go FLAC decoder.
* [gaad ★30](https://github.com/Comcast/gaad) - Native Go AAC bitstream parser.
* [go-sox ★48](https://github.com/krig/go-sox) - libsox bindings for go.
* [go_mediainfo ★16 ⏳1Y](https://github.com/zhulik/go_mediainfo) - libmediainfo bindings for go.
* [gosamplerate ★3](https://github.com/dh1tw/gosamplerate) - libsamplerate bindings for go.
* [id3v2 ★46](https://github.com/bogem/id3v2) - Fast and stable ID3 parsing and writing library for Go.
* [mix ★62](https://github.com/go-mix/mix) - Sequence-based Go-native audio mixer for music apps.
* [mp3 ★59](https://github.com/tcolgate/mp3) - Native Go MP3 decoder.
* [music-theory ★167 ⏳1Y](https://github.com/go-music-theory/music-theory) - Music theory models in Go.
* [PortAudio ★146](https://github.com/gordonklaus/portaudio) - Go bindings for the PortAudio audio I/O library.
* [portmidi ★134](https://github.com/rakyll/portmidi) - Go bindings for PortMidi.
* [taglib ★52 ⏳1Y](https://github.com/wtolson/go-taglib) - Go bindings for taglib.
* [vorbis ★15 ⏳1Y](https://github.com/mccoyst/vorbis) - "Native" Go Vorbis decoder (uses CGO, but has no dependencies).
* [waveform ★187 ⏳1Y](https://github.com/mdlayher/waveform) - Go package capable of generating waveform images from audio streams.

## Authentication and OAuth

*Libraries for implementing authentications schemes.*

* [authboss ★1170](https://github.com/volatiletech/authboss) - Modular authentication system for the web. It tries to remove as much boilerplate and "hard things" as possible so that each time you start a new web project in Go, you can plug it in, configure, and start building your app without having to build an authentication system each time.
* [casbin](https://github.com/hsluoyz/casbin) - Authorization library that supports access control models like ACL, RBAC, ABAC.
* [Go-AWS-Auth ★173](https://github.com/smartystreets/go-aws-auth) - AWS (Amazon Web Services) request signing library.
* [go-jose ★710](https://github.com/square/go-jose) - Fairly complete implementation of the JOSE working group's JSON Web Token, JSON Web Signatures, and JSON Web Encryption specs.
* [go-oauth2-server ★608](https://github.com/RichardKnop/go-oauth2-server) - Standalone, specification-compliant,  OAuth2 server written in Golang.
* [go.auth ★348 ⏳2Y](https://github.com/bradrydzewski/go.auth) - Authentication API for Go web applications.
* [gologin ★767](https://github.com/dghubble/gologin) - chainable handlers for login with OAuth1 and OAuth2 authentication providers.
* [gorbac ★587](https://github.com/mikespook/gorbac) - provides a lightweight role-based access control (RBAC) implementation in Golang.
* [goth ★1280](https://github.com/markbates/goth) - provides a simple, clean, and idiomatic way to use OAuth and OAuth2. Handles multiple provides out of the box.
* [httpauth ★118 ⏳1Y](https://github.com/goji/httpauth) - HTTP Authentication middleware.
* [jwt ★18](https://github.com/robbert229/jwt) - Clean and easy to use implementation of JSON Web Tokens (JWT).
* [jwt-auth ★75](https://github.com/adam-hanna/jwt-auth) - JWT middleware for goLang http servers with many configuration options.
* [jwt-go ★2430](https://github.com/dgrijalva/jwt-go) - Golang implementation of JSON Web Tokens (JWT).
* [loginsrv ★395](https://github.com/tarent/loginsrv) - JWT login microservice with plugable backends such as OAuth2 (Github), htpasswd, osiam.
* [oauth2 ★1222](https://github.com/golang/oauth2) - Successor of goauth2. Generic OAuth 2.0 package that comes with JWT, Google APIs, Compute Engine and App Engine support.
* [osin ★1205](https://github.com/RangelReale/osin) - Golang OAuth2 server library.
* [permissions2 ★233](https://github.com/xyproto/permissions2) - Library for keeping track of users, login states and permissions. Uses secure cookies and bcrypt.
* [session ★34](https://github.com/icza/session) - Go session management for web servers (including support for Google App Engine - GAE).
* [sessions ★22](https://github.com/adam-hanna/sessions) - Dead simple, highly performant, highly customizable sessions service for go http servers.
* [traefik ★9259](https://github.com/containous/traefik) - Reverse proxy and load balancer with support for multiple backends.
* [yubigo ★75](https://github.com/GeertJohan/yubigo) - Yubikey client package that provides a simple API to integrate the Yubico Yubikey into a go application.

## Command Line

### Standard CLI

*Libraries for building standard or basic Command Line applications.*

* [argv ★2](https://github.com/cosiner/argv) - Go library to split command line string as arguments array using the bash syntax.
* [cli ★296](https://github.com/mkideal/cli) - Feature-rich and easy to use command-line package based on golang tag.
* [cli-init ★725](https://github.com/tcnksm/gcli) - The easy way to start building Golang command line application.
* [climax](http://github.com/tucnak/climax) - Alternative CLI with "human face", in spirit of Go command.
* [cobra ★4907](https://github.com/spf13/cobra) - Commander for modern Go CLI interactions.
* [complete ★190](https://github.com/posener/complete) - Write bash completions in Go + Go command bash completion.
* [docopt.go ★847](https://github.com/docopt/docopt.go) - Command-line arguments parser that will make you smile.
* [drive ★3417](https://github.com/odeke-em/drive) - Google Drive client for the commandline.
* [env ★5](https://github.com/codingconcepts/env) - Tag-based environment configuration for structs.
* [flag ★69](https://github.com/cosiner/flag) - Simple but powerful command line option parsing library for Go support subcommand.
* [go-arg ★422](https://github.com/alexflint/go-arg) - Struct-based argument parsing in Go.
* [go-flags ★856](https://github.com/jessevdk/go-flags) - go command line option parser.
* [kingpin ★1349](https://github.com/alecthomas/kingpin) - Command line and flag parser supporting sub commands.
* [liner ★390](https://github.com/peterh/liner) - Go readline-like library for command-line interfaces.
* [mitchellh/cli ★650](https://github.com/mitchellh/cli) - Go library for implementing command-line interfaces.
* [mow.cli ★417](https://github.com/jawher/mow.cli) - Go library for building CLI applications with sophisticated flag and argument parsing and validation.
* [pflag ★230](https://github.com/spf13/pflag) - Drop-in replacement for Go's flag package, implementing POSIX/GNU-style --flags.
* [readline ★844](https://github.com/chzyer/readline) - Pure golang implementation that provide most of features in GNU-Readline under MIT license.
* [sflags ★44](https://github.com/octago/sflags) - Struct based flags generator for flag, urfave/cli, pflag, cobra, kingpin and other libraries.
* [ukautz/clif ★76](https://github.com/ukautz/clif) - Small command line interface framework.
* [urfave/cli ★6315](https://github.com/urfave/cli) - Simple, fast, and fun package for building command line apps in Go (formerly codegangsta/cli).
* [wlog ★19](https://github.com/dixonwille/wlog) - Simple logging interface that supports cross-platform color and concurrency.
* [wmenu ★33](https://github.com/dixonwille/wmenu) - Easy to use menu structure for cli applications that prompts users to make choices.

### Advanced Console UIs

*Libraries for building Console Applications and Console User Interfaces.*

* [aurora ★241](https://github.com/logrusorgru/aurora) - ANSI terminal colors that supports fmt.Printf/Sprintf.
* [chalk ★206 ⏳1Y](https://github.com/ttacon/chalk) - Intuitive package for prettifying terminal/console output.
* [color ★1759](https://github.com/fatih/color) - Versatile package for colored terminal output.
* [colourize ★11 ⏳1Y](https://github.com/TreyBastian/colourize) - Go library for ANSI colour text in terminals.
* [go-ataman ★1](https://github.com/workanator/go-ataman) - Go library for rendering ANSI colored text templates in terminals.
* [go-colorable ★195](https://github.com/mattn/go-colorable) - Colorable writer for windows.
* [go-colortext ★158](https://github.com/daviddengcn/go-colortext) - Go library for color output in terminals.
* [go-isatty ★170](https://github.com/mattn/go-isatty) - isatty for golang.
* [gocui ★1839](https://github.com/jroimartin/gocui) - Minimalist Go library aimed at creating Console User Interfaces.
* [gommon/color](https://github.com/labstack/gommon/tree/master/color) - Style terminal text.
* [mpb ★92](https://github.com/vbauerster/mpb) - Multi progress bar for terminal applications.
* [termbox-go ★2316](https://github.com/nsf/termbox-go) - Termbox is a library for creating cross-platform text-based interfaces.
* [termtables](https://github.com/apcera/termtables) - Go port of the Ruby library [terminal-tables ★913](https://github.com/tj/terminal-table) for simple ASCII table generation as well as providing markdown and HTML output.
* [termui](https://github.com/gizak/termui) - Go terminal dashboard based on **termbox-go** and inspired by [blessed-contrib ★10122](https://github.com/yaronn/blessed-contrib).
* [uilive ★558](https://github.com/gosuri/uilive) - Library for updating terminal output in realtime.
* [uiprogress ★977](https://github.com/gosuri/uiprogress) - Flexible library to render progress bars in terminal applications.
* [uitable ★385 ⏳1Y](https://github.com/gosuri/uitable) - Library to improve readability in terminal apps using tabular data.

## Configuration

*Libraries for configuration parsing.*

* [config ★122](https://github.com/olebedev/config) - JSON or YAML configuration wrapper with environment variables and flags parsing.
* [configure ★28](https://github.com/paked/configure) - Provides configuration through multiple sources, including JSON, flags and environment variables.
* [env ★297](https://github.com/caarlos0/env) - Parse environment variables to Go structs (with defaults).
* [envcfg ★79](https://github.com/tomazk/envcfg) - Un-marshaling environment variables to Go structs.
* [envconf ★5 ⏳2Y](https://github.com/ian-kent/envconf) - Configuration from environment.
* [envconfig ★108](https://github.com/vrischmann/envconfig) - Read your configuration from environment variables.
* [gcfg ★63 ⏳1Y](https://github.com/go-gcfg/gcfg) - read INI-style configuration files into Go structs; supports user-defined types and subsections.
* [goConfig ★43](https://github.com/crgimenes/goConfig) - Parse a struct as input and populates the fields of this struct with parameters fom command line, environment variables and configuration file.
* [godotenv ★645](https://github.com/joho/godotenv) - Go port of Ruby's dotenv library (Loads environment variables from `.env`).
* [gofigure ★42](https://github.com/ian-kent/gofigure) - Go application configuration made easy.
* [gone/jconf](https://github.com/One-com/gone/tree/master/jconf#readme) - Modular JSON configuration. Keep you config structs along the code they configure and delegate parsing to submodules without sacrificing full config serialization.
* [hjson ★87](https://github.com/hjson/hjson-go) - Human JSON, a configuration file format for humans. Relaxed syntax, fewer mistakes, more comments.
* [ingo ★13](https://github.com/schachmat/ingo) - Flags persisted in an ini-like config file.
* [ini ★640](https://github.com/go-ini/ini) - Go package for read and write INI files.
* [joshbetz/config ★142](https://github.com/joshbetz/config) - Small configuration library for Go that parses environment variables, JSON files, and reloads automatically on SIGHUP.
* [mini ★10](https://github.com/sasbury/mini) - Golang package for parsing ini-style configuration files.
* [store ★206](https://github.com/tucnak/store) - Lightweight configuration manager for Go.
* [viper ★3510](https://github.com/spf13/viper) - Go configuration with fangs.
* [xdg ★0](https://github.com/OpenPeeDeeP/xdg) - Cross platform package that follows the [XDG Standard](https://standards.freedesktop.org/basedir-spec/basedir-spec-latest.html).

## Continuous Integration

*Tools for help with continuous integration.*

* [drone ★10683](https://github.com/drone/drone) - Drone is a Continuous Integration platform built on Docker, written in Go.
* [goveralls ★405](https://github.com/mattn/goveralls) - Go integration for Coveralls.io continuous code coverage tracking system.
* [overalls ★64](https://github.com/go-playground/overalls) - Multi-Package go project coverprofile for tools like goveralls.
* [roveralls ★1](https://github.com/LawrenceWoodman/roveralls) - Recursive coverage testing tool.

## CSS Preprocessors

*Libraries for preprocessing CSS files.*

* [c6 ★376](https://github.com/c9s/c6) - High performance SASS compatible-implementation compiler written in Go.
* [gcss ★382 ⏳2Y](https://github.com/yosssi/gcss) - Pure Go CSS Preprocessor.
* [go-libsass ★60](https://github.com/wellington/go-libsass) - Go wrapper to the 100% Sass compatible libsass project.

## Data Structures

*Generic datastructures and algorithms in Go.*

* [binpacker ★48](https://github.com/zhuangsirui/binpacker) - Binary packer and unpacker helps user build custom binary stream.
* [bit ★4](https://github.com/yourbasic/bit) - Golang set data structure with bonus bit-twiddling functions.
* [bitset ★298](https://github.com/willf/bitset) - Go package implementing bitsets.
* [bloom](https://github.com/zhenjl/bloom) - Bloom filters implemented in Go.
* [bloom ★2](https://github.com/yourbasic/bloom) - Golang Bloom filter implementation.
* [boomfilters ★840](https://github.com/tylertreat/BoomFilters) - Probabilistic data structures for processing continuous, unbounded streams.
* [count-min-log ★30](https://github.com/seiflotfy/count-min-log) - Go implementation Count-Min-Log sketch: Approximately counting with approximate counters (Like Count-Min sketch but using less memory).
* [cuckoofilter ★232](https://github.com/seiflotfy/cuckoofilter) - Cuckoo filter: a good alternative to a counting bloom filter implemented in Go.
* [encoding ★74 ⏳3Y](https://github.com/zhenjl/encoding) - Integer Compression Libraries for Go.
* [go-adaptive-radix-tree ★21](https://github.com/plar/go-adaptive-radix-tree) - Go implementation of Adaptive Radix Tree.
* [go-datastructures ★3365](https://github.com/Workiva/go-datastructures) - Collection of useful, performant, and thread-safe data structures.
* [go-geoindex ★258 ⏳1Y](https://github.com/hailocab/go-geoindex) - In-memory geo index.
* [go-rquad ★69](https://github.com/aurelien-rainone/go-rquad) - Region quadtrees with efficient point location and neighbour finding.
* [gods ★3069](https://github.com/emirpasic/gods) - Go Data Structures. Containers, Sets, Lists, Stacks, Maps, BidiMaps, Trees, HashSet etc.
* [golang-set ★578](https://github.com/deckarep/golang-set) - Thread-Safe and Non-Thread-Safe high-performance sets for Go.
* [goset ★4](https://github.com/zoumo/goset) - A useful Set collection implementation for Go.
* [goskiplist ★134](https://github.com/ryszard/goskiplist) - Skip list implementation in Go.
* [gota ★307](https://github.com/kniren/gota) - Implementation of dataframes, series, and data wrangling methods for Go.
* [hilbert ★93](https://github.com/google/hilbert) - Go package for mapping values to and from space-filling curves, such as Hilbert and Peano curves.
* [hyperloglog ★545](https://github.com/axiomhq/hyperloglog) - HyperLogLog implementation with Sparse, LogLog-Beta bias correction and TailCut space reduction.
* [levenshtein ★6](https://github.com/agext/levenshtein) - Levenshtein distance and similarity metrics with customizable edit costs and Winkler-like bonus for common prefix.
* [levenshtein ★9](https://github.com/agnivade/levenshtein) - Implementation to calculate levenshtein distance in Go.
* [mafsa ★252](https://github.com/smartystreets/mafsa) - MA-FSA implementation with Minimal Perfect Hashing.
* [merkletree ★7](https://github.com/cbergoon/merkletree) - Implementation of a merkle tree providing an efficient and secure verification of the contents of data structures.
* [roaring ★268](https://github.com/RoaringBitmap/roaring) - Go package implementing compressed bitsets.
* [skiplist ★39 ⏳2Y](https://github.com/gansidui/skiplist) - Skiplist implementation in Go.
* [trie ★194](https://github.com/derekparker/trie) - Trie implementation in Go.
* [ttlcache](https://github.com/diegobernardes/ttlcache) - In-memory LRU string-interface{} map with expiration for golang.
* [willf/bloom ★350](https://github.com/willf/bloom) - Go package implementing Bloom filters.

## Database

*Databases implemented in Go.*

* [BigCache ★1036](https://github.com/allegro/bigcache) - Efficient key/value cache for gigabytes of data.
* [bolt ★6735](https://github.com/boltdb/bolt) - Low-level key/value database for Go.
* [buntdb ★1551](https://github.com/tidwall/buntdb) - Fast, embeddable, in-memory key/value database for Go with custom indexing and spatial support.
* [cache2go ★297](https://github.com/muesli/cache2go) - In-memory key:value cache which supports automatic invalidation based on timeouts.
* [cockroach ★10870](https://github.com/cockroachdb/cockroach) - Scalable, Geo-Replicated, Transactional Datastore.
* [couchcache ★25](https://github.com/codingsince1985/couchcache) - RESTful caching micro-service backed by Couchbase server.
* [dgraph ★3604](https://github.com/dgraph-io/dgraph) - Scalable, Distributed, Low Latency, High Throughput Graph Database.
* [diskv ★471](https://github.com/peterbourgon/diskv) - Home-grown disk-backed key-value store.
* [eliasdb ★430](https://github.com/krotik/eliasdb) - Dependency-free, transactional graph database with REST API, phrase search and SQL-like query language.
* [forestdb ★27](https://github.com/couchbase/goforestdb) - Go bindings for ForestDB.
* [GCache ★228](https://github.com/bluele/gcache) - Cache library with support for expirable Cache, LFU, LRU and ARC.
* [geocache ★68 ⏳1Y](https://github.com/melihmucuk/geocache) - In-memory cache that is suitable for geolocation based applications.
* [go-cache](https://github.com/pmylund/go-cache) - In-memory key:value store/cache (similar to Memcached) library for Go, suitable for single-machine applications.
* [goleveldb](https://github.com/syndtr/goleveldb) - Implementation of the [LevelDB ★10286](https://github.com/google/leveldb) key/value database in the Go.
* [groupcache ★5655](https://github.com/golang/groupcache) - Groupcache is a caching and cache-filling library, intended as a replacement for memcached in many cases.
* [influxdb](https://github.com/influxdb/influxdb) - Scalable datastore for metrics, events, and real-time analytics.
* [ledisdb ★2205](https://github.com/siddontang/ledisdb) - Ledisdb is a high performance NoSQL like Redis based on LevelDB.
* [levigo ★305](https://github.com/jmhodges/levigo) - Levigo is a Go wrapper for LevelDB.
* [moss ★343](https://github.com/couchbase/moss) - Moss is a simple LSM key-value storage engine written in 100% Go.
* [piladb ★138](https://github.com/fern4lvarez/piladb) - Lightweight RESTful database engine based on stack data structures.
* [prometheus ★11106](https://github.com/prometheus/prometheus) - Monitoring system and time series database.
* [rqlite ★3107](https://github.com/rqlite/rqlite) - The lightweight, distributed, relational database built on SQLite.
* [Scribble ★70](https://github.com/nanobox-io/golang-scribble) - Tiny flat file JSON store.
* [tempdb ★6](https://github.com/rafaeljesus/tempdb) - Key-value store for temporary items.
* [tidb ★9219](https://github.com/pingcap/tidb) - TiDB is a distributed SQL database. Inspired by the design of Google F1.
* [tiedot ★1887](https://github.com/HouzuoGuo/tiedot) - Your NoSQL database powered by Golang.
* [Tile38 ★3318](https://github.com/tidwall/tile38) - Geolocation DB with spatial index and realtime geofencing.

*Database schema migration.*

* [darwin ★42](https://github.com/GuiaBolso/darwin) - Database schema evolution library for Go.
* [go-fixtures ★2](https://github.com/RichardKnop/go-fixtures) - Django style fixtures for Golang's excellent built-in database/sql library.
* [goose ★45](https://github.com/steinbacher/goose) - Database migration tool. You can manage your database's evolution by creating incremental SQL or Go scripts.
* [gormigrate ★54](https://github.com/go-gormigrate/gormigrate) - Database schema migration helper for Gorm ORM.
* [migrate ★1489](https://github.com/mattes/migrate) - Database migrations. CLI and Golang library.
* [pravasan ★18 ⏳2Y](https://github.com/pravasan/pravasan) - Simple Migration tool - currently for MySQL but planning to support soon for Postgres, SQLite, MongoDB, etc.
* [soda](https://github.com/markbates/pop/tree/master/soda) - Database migration, creation, ORM, etc... for MySQL, PostgreSQL, and SQLite.
* [sql-migrate ★738](https://github.com/rubenv/sql-migrate) - Database migration tool. Allows embedding migrations into the application using go-bindata.

*Database tools.*

* [go-mysql ★616](https://github.com/siddontang/go-mysql) - Go toolset to handle MySQL protocol and replication.
* [go-mysql-elasticsearch ★815](https://github.com/siddontang/go-mysql-elasticsearch) - Sync your MySQL data into Elasticsearch automatically.
* [kingshard ★2836](https://github.com/flike/kingshard) - kingshard is a high performance proxy for MySQL powered by Golang.
* [myreplication ★80 ⏳2Y](https://github.com/2tvenom/myreplication) - MySql binary log replication listener. Support statement and row based replication.
* [orchestrator ★809](https://github.com/github/orchestrator) - MySQL replication topology manager & visualizer.
* [pgweb ★4415](https://github.com/sosedoff/pgweb) - Web-based PostgreSQL database browser.
* [pREST](https://github.com/nuveo/prest) - Serve a RESTful API from any PostgreSQL database.
* [vitess ★4865](https://github.com/youtube/vitess) - vitess provides servers and tools which facilitate scaling of MySQL databases for large scale web services.

*SQL query builder, libraries for building and using SQL.*

* [dat ★451](https://github.com/mgutz/dat) - Go Postgres Data Access Toolkit.
* [Dotsql ★304 ⏳1Y](https://github.com/gchaincl/dotsql) - Go library that helps you keep sql files in one place and use it with ease.
* [goqu ★332](https://github.com/doug-martin/goqu) - Idiomatic SQL builder and query library.
* [igor ★60](https://github.com/galeone/igor) - Abstraction layer for PostgreSQL that supports advanced functionality and uses gorm-like syntax.
* [ozzo-dbx ★170](https://github.com/go-ozzo/ozzo-dbx) - Powerful data retrieval methods as well as DB-agnostic query building capabilities.
* [scaneo ★107](https://github.com/variadico/scaneo) - Generate Go code to convert database rows into arbitrary structs.
* [sqrl ★77](https://github.com/elgris/sqrl) - SQL query builder, fork of Squirrel with improved performance.
* [Squirrel ★1183](https://github.com/Masterminds/squirrel) - Go library that helps you build SQL queries.
* [xo ★1203](https://github.com/knq/xo) - Generate idiomatic Go code for databases based on existing schema definitions or custom queries supporting PostgreSQL, MySQL, SQLite, Oracle, and Microsoft SQL Server.

## Database Drivers

*Libraries for connecting and operating databases.*

* Relational Databases
    * [avatica ★30](https://github.com/Boostport/avatica) - Apache Phoenix/Avatica SQL driver for database/sql.
    * [bgc ★5](https://github.com/viant/bgc) - Datastore Connectivity for BigQuery for go.
    * [firebirdsql ★63](https://github.com/nakagami/firebirdsql) - Firebird RDBMS SQL driver for Go.
    * [go-adodb ★59](https://github.com/mattn/go-adodb) - Microsoft ActiveX Object DataBase driver for go that using database/sql.
    * [go-bqstreamer](https://github.com/rounds/go-bqstreamer) - BigQuery fast and concurrent stream insert.
    * [go-mssqldb ★582](https://github.com/denisenkom/go-mssqldb) - Microsoft MSSQL driver for Go.
    * [go-oci8 ★226](https://github.com/mattn/go-oci8) - Oracle driver for go that using database/sql.
    * [go-sql-driver/mysql ★3986](https://github.com/go-sql-driver/mysql) - MySQL driver for Go.
    * [go-sqlite3 ★1933](https://github.com/mattn/go-sqlite3) - SQLite3 driver for go that using database/sql.
    * [gofreetds ★49](https://github.com/minus5/gofreetds) - Microsoft MSSQL driver. Go wrapper over [FreeTDS](http://www.freetds.org).
    * [pgx ★1076](https://github.com/jackc/pgx) - PostgreSQL driver supporting features beyond those exposed by database/sql.
    * [pq ★3085](https://github.com/lib/pq) - Pure Go Postgres driver for database/sql.

* NoSQL Databases
    * [aerospike-client-go ★229](https://github.com/aerospike/aerospike-client-go) - Aerospike client in Go language.
    * [arangolite ★50](https://github.com/solher/arangolite) - Lightweight golang driver for ArangoDB.
    * [asc ★2](https://github.com/viant/asc) - Datastore Connectivity for Aerospike for go.
    * [cayley](https://github.com/google/cayley) - Graph database with support for multiple backends.
    * [dsc ★4](https://github.com/viant/dsc) - Datastore connectivity for SQL, NoSQL, structured files.
    * [dynago ★43](https://github.com/underarmour/dynago) - Dynago is a principle of least surprise client for DynamoDB.
    * [go-couchbase ★245](https://github.com/couchbase/go-couchbase) - Couchbase client in Go.
    * [go-couchdb ★45](https://github.com/fjl/go-couchdb) - Yet another CouchDB HTTP API wrapper for Go.
    * [gocb ★222](https://github.com/couchbase/gocb) - Official Couchbase Go SDK.
    * [gocql](http://gocql.github.io) - Go language driver for Apache Cassandra.
    * [gomemcache ★796](https://github.com/bradfitz/gomemcache) - memcache client library for the Go programming language.
    * [gorethink](https://github.com/dancannon/gorethink) - Go language driver for RethinkDB.
    * [goriak ★18](https://github.com/zegl/goriak) - Go language driver for Riak KV.
    * [mgo](https://godoc.org/labix.org/v2/mgo) - MongoDB driver for the Go language that implements a rich and well tested selection of features under a very simple API following standard Go idioms.
    * [neo4j ★22 ⏳2Y](https://github.com/cihangir/neo4j) - Neo4j Rest API Bindings for Golang.
    * [Neo4j-GO ★65 ⏳4Y](https://github.com/davemeehan/Neo4j-GO) - Neo4j REST Client in golang.
    * [neoism ★302](https://github.com/jmcvetta/neoism) - Neo4j client for Golang.
    * [redigo ★3420](https://github.com/garyburd/redigo) - Redigo is a Go client for the Redis database.
    * [redis ★2131](https://github.com/go-redis/redis) - Redis client for Golang.
    * [redis ★537 ⏳1Y](https://github.com/hoisie/redis) - Simple, powerful Redis client for Go.
    * [redis ★139](https://github.com/bsm/redeo) - Redis-protocol compatible TCP servers/services.
    * [xredis ★6](https://github.com/shomali11/xredis) - Typesafe, customizable, clean & easy to use Redis client.

* Search and Analytic Databases.
    * [bleve ★3441](https://github.com/blevesearch/bleve) - Modern text indexing library for go.
    * [elastic ★1583](https://github.com/olivere/elastic) - Elasticsearch client for Go.
    * [elasticsql ★88](https://github.com/cch123/elasticsql) - Convert sql to elasticsearch dsl in Go.
    * [elastigo ★873](https://github.com/mattbaird/elastigo) - Elasticsearch client library.
    * [goes ★75](https://github.com/belogik/goes) - Library to interact with Elasticsearch.
    * [skizze ★44 ⏳1Y](https://github.com/seiflotfy/skizze) - probabilistic data-structures service and storage.

## Date and Time

*Libraries for working with dates and times.*

* [carbon ★117](https://github.com/uniplaces/carbon) - Simple Time extension with a lot of util methods, ported from PHP Carbon library.
* [dateparse ★29](https://github.com/araddon/dateparse) - Parse date's without knowing format in advance.
* [durafmt ★164](https://github.com/hako/durafmt) - Uime duration formatting library for Go.
* [feiertage ★4](https://github.com/wlbr/feiertage) - Set of functions to calculate public holidays in Germany, incl. specialization on the states of Germany (Bundesländer). Things like Easter, Pentecoast, Thanksgiving...
* [go-persian-calendar ★25](https://github.com/yaa110/go-persian-calendar) - The implementation of the Persian (Solar Hijri) Calendar in Go (golang).
* [goweek ★12](https://github.com/grsmv/goweek) - Library for working with week entity in golang.
* [now ★929](https://github.com/jinzhu/now) - Now is a time toolkit for golang.
* [NullTime ★3](https://github.com/kirillDanshin/nulltime) - Nullable `time.Time`.
* [timeutil ★138 ⏳2Y](https://github.com/leekchan/timeutil) - Useful extensions (Timedelta, Strftime, ...) to the golang's time package.
* [tuesday ★1](https://github.com/osteele/tuesday) - Ruby-compatible Strftime function.

## Distributed Systems

*Packages that help with building Distributed Systems.*

* [celeriac ★26](https://github.com/svcavallar/celeriac.v1) - Library for adding support for interacting and monitoring Celery workers, tasks and events in Go.
* [digota ★120](https://github.com/digota/digota) - grpc ecommerce microservice.
* [drmaa ★18](https://github.com/dgruber/drmaa) - Job submission library for cluster schedulers based on the DRMAA standard.
* [flowgraph ★31](https://github.com/vectaport/flowgraph) - MPI-style ready-send coordination layer.
* [gleam ★820](https://github.com/chrislusf/gleam) - Fast and scalable distributed map/reduce system written in pure Go and Luajit, combining Go's high concurrency with Luajit's high performance, runs standalone or distributed.
* [glow ★1695](https://github.com/chrislusf/glow) - Easy-to-Use scalable distributed big data processing, Map-Reduce, DAG execution, all in pure Go.
* [go-jump ★127](https://github.com/dgryski/go-jump) - Port of Google's "Jump" Consistent Hash function.
* [go-kit ★7491](https://github.com/go-kit/kit) - Microservice toolkit with support for service discovery, load balancing, pluggable transports, request tracking, etc.
* [gorpc ★384](https://github.com/valyala/gorpc) - Simple, fast and scalable RPC library for high load.
* [grpc-go ★3745](https://github.com/grpc/grpc-go) - The Go language implementation of gRPC. HTTP/2 based RPC.
* [hprose ★611](https://github.com/hprose/hprose-golang) - Very newbility RPC Library, support 25+ languages now.
* [jsonrpc ★32](https://github.com/osamingo/jsonrpc) - The jsonrpc package helps implement of JSON-RPC 2.0.
* [jsonrpc ★7](https://github.com/ybbus/jsonrpc) - JSON-RPC 2.0 HTTP client implementation.
* [KrakenD ★91](https://github.com/devopsfaith/krakend) - Ultra performant API Gateway framework with middlewares.
* [micro ★3444](https://github.com/micro/micro) - Pluggable microservice toolkit and distributed systems platform.
* [NATS ★3294](https://github.com/nats-io/gnatsd) - Lightweight, high performance messaging system for microservices, IoT, and cloud native systems.
* [raft ★1290](https://github.com/hashicorp/raft) - Golang implementation of the Raft consensus protocol, by HashiCorp.
* [raft](https://github.com/coreos/etcd/tree/master/raft#readme) - Go implementation of the Raft consensus protocol, by CoreOS.
* [ringpop-go ★355](https://github.com/uber/ringpop-go) - Scalable, fault-tolerant application-layer sharding for Go applications.
* [rpcx ★1337](https://github.com/smallnest/rpcx) - Distributed pluggable RPC service framework like alibaba Dubbo.
* [sleuth](https://github.com/ursiform/sleuth) - Library for master-less p2p auto-discovery and RPC between HTTP services (using [ZeroMQ ★3600](https://github.com/zeromq/libzmq)).
* [tendermint ★594](https://github.com/tendermint/tendermint) - High-performance middleware for transforming a state machine written in any programming language into a Byzantine Fault Tolerant replicated state machine using the Tendermint consensus and blockchain protocols.
* [torrent ★1764](https://github.com/anacrolix/torrent) - BitTorrent client package.
    * [dht](https://godoc.org/github.com/anacrolix/dht) - BitTorrent Kademlia DHT implementation.
    * [go-peerflix ★279](https://github.com/Sioro-Neoku/go-peerflix) - Video streaming torrent client.

## Email

*Libraries that implement email creation and sending.*

* [douceur ★96](https://github.com/aymerick/douceur) - CSS inliner for your HTML emails.
* [email ★787](https://github.com/jordan-wright/email) - A robust and flexible email library for Go.
* [go-dkim ★30](https://github.com/toorop/go-dkim) - DKIM library, to sign & verify email.
* [go-imap ★264](https://github.com/emersion/go-imap) - IMAP library for clients and servers.
* [go-message ★25](https://github.com/emersion/go-message) - Streaming library for the Internet Message Format and mail messages.
* [Gomail ★1304](https://github.com/go-gomail/gomail) - Gomail is a very simple and powerful package to send emails.
* [Hectane ★117](https://github.com/hectane/hectane) - Lightweight SMTP client providing an HTTP API.
* [hermes ★960](https://github.com/matcornic/hermes) - Golang package that generates clean, responsive HTML e-mails.
* [MailHog ★2363](https://github.com/mailhog/MailHog) - Email and SMTP testing with web and API interface.
* [SendGrid ★268](https://github.com/sendgrid/sendgrid-go) - SendGrid's Go library for sending email.
* [smtp ★34](https://github.com/mailhog/smtp) - SMTP server protocol state machine.

## Embeddable Scripting Languages

*Embedding other languages inside your go code.*

* [agora](https://github.com/PuerkitoBio/agora) - Dynamically typed, embeddable programming language in Go.
* [anko ★427](https://github.com/mattn/anko) - Scriptable interpreter written in Go.
* [binder](https://github.com/alexeyco/binder) - Go to Lua binding library, based on [gopher-lua ★1744](https://github.com/yuin/gopher-lua).
* [gisp ★363 ⏳3Y](https://github.com/jcla1/gisp) - Simple LISP in Go.
* [go-duktape ★514](https://github.com/olebedev/go-duktape) - Duktape JavaScript engine bindings for Go.
* [go-lua ★1030](https://github.com/Shopify/go-lua) - Port of the Lua 5.2 VM to pure Go.
* [go-php ★332](https://github.com/deuill/go-php) - PHP bindings for Go.
* [go-python ★521](https://github.com/sbinet/go-python) - naive go bindings to the CPython C-API.
* [golua ★346](https://github.com/aarzilli/golua) - Go bindings for Lua C API.
* [gopher-lua ★1744](https://github.com/yuin/gopher-lua) - Lua 5.1 VM and compiler written in Go.
* [ngaro ★8 ⏳1Y](https://github.com/db47h/ngaro) - Embeddable Ngaro VM implementation enabling scripting in Retro.
* [otto ★3114](https://github.com/robertkrimen/otto) - JavaScript interpreter written in Go.
* [purl ★17 ⏳2Y](https://github.com/ian-kent/purl) - Perl 5.18.2 embedded in Go.

## Files

*Libraries for  handling files and file systems.*

* [afero ★1089](https://github.com/spf13/afero) - FileSystem Abstraction System for Go.
* [go-csv-tag ★7](https://github.com/artonge/go-csv-tag) - Load csv file using tag.
* [go-gtfs ★2](https://github.com/artonge/go-gtfs) - Load gtfs files in go.
* [notify ★260](https://github.com/rjeczalik/notify) - File system event notification library with simple API, similar to os/signal.
* [skywalker ★10](https://github.com/dixonwille/skywalker) - Package to allow one to concurrently go through a filesystem with ease.
* [tarfs ★10](https://github.com/posener/tarfs) - Implementation of the [`FileSystem` interface](https://godoc.org/github.com/kr/fs#FileSystem) for tar files.

## Financial

*Packages for accounting and finance.*

* [accounting ★299](https://github.com/leekchan/accounting) - money and currency formatting for golang.
* [decimal ★577](https://github.com/shopspring/decimal) - Arbitrary-precision fixed-point decimal numbers.
* [go-finance ★453](https://github.com/FlashBoys/go-finance) - Comprehensive financial markets data in Go.
* [go-money ★332](https://github.com/rhymond/go-money) - Implementation of Fowler's Money pattern.
* [ofxgo ★10](https://github.com/aclindsa/ofxgo) - Query OFX servers and/or parse the responses (with example command-line client).
* [vat ★36](https://github.com/dannyvankooten/vat) - VAT number validation & EU VAT rates.

## Forms

*Libraries for working with forms.*

* [bind ★13 ⏳3Y](https://github.com/robfig/bind) - Bind form data to any Go values.
* [binding ★600](https://github.com/mholt/binding) - Binds form and JSON data from net/http Request to struct.
* [conform ★83](https://github.com/leebenson/conform) - Keeps user input in check. Trims, sanitizes & scrubs data based on struct tags.
* [form ★191](https://github.com/go-playground/form) - Decodes url.Values into Go value(s) and Encodes Go value(s) into url.Values. Dual Array and Full map support.
* [formam ★78](https://github.com/monoculum/formam) - decode form's values into a struct.
* [forms ★71](https://github.com/albrow/forms) - Framework-agnostic library for parsing and validating form/JSON data which supports multipart forms and files.
* [gorilla/csrf ★220](https://github.com/gorilla/csrf) - CSRF protection for Go web applications & services.
* [nosurf ★765](https://github.com/justinas/nosurf) - CSRF protection middleware for Go.

## Game Development

*Awesome game development libraries.*

* [Azul3D ★294](https://github.com/azul3d/engine) - 3D game engine written in Go.
* [Ebiten ★408](https://github.com/hajimehoshi/ebiten) - simple 2D game library in Go.
* [engo ★632](https://github.com/EngoEngine/engo) - Engo is an open-source 2D game engine written in Go. It follows the Entity-Component-System paradigm.
* [GarageEngine ★280 ⏳4Y](https://github.com/vova616/GarageEngine) - 2d game engine written in Go working on OpenGL.
* [glop ★77 ⏳1Y](https://github.com/runningwild/glop) - Glop (Game Library Of Power) is a fairly simple cross-platform game library.
* [go-astar ★203](https://github.com/beefsack/go-astar) - Go implementation of the A\* path finding algorithm.
* [go-collada ★11 ⏳3Y](https://github.com/GlenKelley/go-collada) - Go package for working with the Collada file format.
* [go-sdl2 ★647](https://github.com/veandco/go-sdl2) - Go bindings for the [Simple DirectMedia Layer](https://www.libsdl.org/).
* [go3d ★124 ⏳2Y](https://github.com/ungerik/go3d) - Performance oriented 2D/3D math package for Go.
* [gonet ★842](https://github.com/xtaci/gonet) - Game server skeleton implemented with golang.
* [goworld ★239](https://github.com/xiaonanln/goworld) - Scalable game server engine, featuring space-entity framework and hot-swapping
* [Leaf ★1461](https://github.com/name5566/leaf) - Lightweight game server framework.
* [nano ★177](https://github.com/lonnng/nano) - Lightweight, facility, high performance golang based game server framework
* [Oak ★330](https://github.com/oakmound/oak) - Pure Go game engine.
* [Pixel ★663](https://github.com/faiface/pixel) - Hand-crafted 2D game library in Go.
* [raylib-go ★158](https://github.com/gen2brain/raylib-go) - Go bindings for [raylib](http://www.raylib.com/), a simple and easy-to-use library to learn videogames programming.
* [termloop ★778](https://github.com/JoelOtter/termloop) - Terminal-based game engine for Go, built on top of Termbox.

## Generation and Generics

*Tools to enhance the language with features like generics via code generation.*

* [efaceconv ★21](https://github.com/t0pep0/efaceconv) - Code generation tool for high performance conversion from interface{} to immutable type without allocations.
* [gen ★823](https://github.com/clipperhouse/gen) - Code generation tool for ‘generics’-like functionality.
* [go-enum ★11](https://github.com/abice/go-enum) - Code generation for enums from code comments.
* [go-linq](https://github.com/ahmetalpbalkan/go-linq) - .NET LINQ-like query methods for Go.
* [interfaces ★111](https://github.com/rjeczalik/interfaces) - Command line tool for generating interface definitions.
* [jennifer ★502](https://github.com/dave/jennifer) - Generate arbitrary Go code without templates.
* [pkgreflect ★56](https://github.com/ungerik/pkgreflect) - Go preprocessor for package scoped reflection.

## Go Compilers

*Tools for compiling Go to other languages.*

* [gopherjs ★5449](https://github.com/gopherjs/gopherjs) - Compiler from Go to JavaScript.
* [llgo ★836 ⏳2Y](https://github.com/go-llvm/llgo) - LLVM-based compiler for Go.
* [tardisgo ★346](https://github.com/tardisgo/tardisgo) - Golang to Haxe to CPP/CSharp/Java/JavaScript transpiler.

## Goroutines

*Tools for managing and working with Goroutines.*

* [go-floc ★69](https://github.com/workanator/go-floc) - Orchestrate goroutines with ease.
* [go-flow ★50](https://github.com/kamildrazkiewicz/go-flow) - Control goroutines execution order.
* [goworker ★1753](https://github.com/benmanns/goworker) - goworker is a Go-based background worker.
* [grpool ★223](https://github.com/ivpusic/grpool) - Lightweight Goroutine pool.
* [pool ★297 ⏳1Y](https://github.com/go-playground/pool) - Limited consumer goroutine or unlimited goroutine pool for easier goroutine handling and cancellation.
* [semaphore ★6](https://github.com/kamilsk/semaphore) - Semaphore pattern implementation with timeout of lock/unlock operations based on channel and context.
* [tunny ★555](https://github.com/Jeffail/tunny) - Goroutine pool for golang.

## GUI

*Libraries for building GUI Applications.*

*Toolkits*

* [app ★1755](https://github.com/murlokswarm/app) - Package to create apps with GO, HTML and CSS. Supports: MacOS, Windows in progress.
* [go-astilectron ★432](https://github.com/asticode/go-astilectron) - Build cross platform GUI apps with GO and HTML/JS/CSS (powered by Electron).
* [go-gtk](http://mattn.github.io/go-gtk/) - Go bindings for GTK.
* [go-qml ★1805 ⏳1Y](https://github.com/go-qml/qml) - QML support for the Go language.
* [go-sciter ★673](https://github.com/sciter-sdk/go-sciter) - Go bindings for Sciter: the Embeddable HTML/CSS/script engine for modern desktop UI development. Cross platform.
* [goqt ★1287](https://github.com/visualfc/goqt) - Golang bindings to the Qt cross-platform application framework.
* [gotk3 ★264](https://github.com/gotk3/gotk3) - Go bindings for GTK3.
* [gowd ★34](https://github.com/dtylman/gowd) - Rapid and simple desktop UI development with GO, HTML, CSS and NW.js. Cross platform.
* [qt ★2794](https://github.com/therecipe/qt) - Qt binding for Go (support for Windows / macOS / Linux / Android / iOS / Sailfish OS / Raspberry Pi).
* [ui ★4365](https://github.com/andlabs/ui) - Platform-native GUI library for Go. Cross platform.
* [walk ★1970](https://github.com/lxn/walk) - Windows application library kit for Go.

*Interaction*

* [gosx-notifier ★379](https://github.com/deckarep/gosx-notifier) - OSX Desktop Notifications library for Go.
* [robotgo ★1958](https://github.com/go-vgo/robotgo) - Go Native cross-platform GUI system automation;Control the mouse, keyboard and other.
* [systray ★212](https://github.com/getlantern/systray) - Cross platform Go library to place an icon and menu in the notification area.
* [trayhost ★102](https://github.com/shurcooL/trayhost) - Cross-platform Go library to place an icon in the host operating system's taskbar.


## Hardware

*Libraries, tools, and tutorials for interacting with hardware.*

See [go-hardware ★546](https://github.com/rakyll/go-hardware) for a comprehensive list.

## Images

*Libraries for manipulating images.*

* [bild ★1516](https://github.com/anthonynsimon/bild) - Collection of image processing algorithms in pure Go.
* [bimg ★342](https://github.com/h2non/bimg) - Small package for fast and efficient image processing using libvips.
* [geopattern ★912](https://github.com/pravj/geopattern) - Create beautiful generative image patterns from a string.
* [gg ★1014](https://github.com/fogleman/gg) - 2D rendering in pure Go.
* [gift ★930](https://github.com/disintegration/gift) - Package of image processing filters.
* [go-cairo ★61 ⏳1Y](https://github.com/ungerik/go-cairo) - Go binding for the cairo graphics library.
* [go-gd ★40 ⏳2Y](https://github.com/bolknote/go-gd) - Go binding for GD library.
* [go-nude ★227 ⏳2Y](https://github.com/koyachi/go-nude) - Nudity detection with Go.
* [go-opencv](https://github.com/lazywei/go-opencv) - Go bindings for OpenCV.
* [go-webcolors ★21 ⏳2Y](https://github.com/jyotiska/go-webcolors) - Port of webcolors library from Python to Go.
* [imagick ★609](https://github.com/gographics/imagick) - Go binding to ImageMagick's MagickWand C API.
* [imaginary ★1289](https://github.com/h2non/imaginary) - Fast and simple HTTP microservice for image resizing.
* [imaging ★1231](https://github.com/disintegration/imaging) - Simple Go image processing package.
* [img ★105 ⏳2Y](https://github.com/hawx/img) - Selection of image manipulation tools.
* [ln ★1968](https://github.com/fogleman/ln) - 3D line art rendering in Go.
* [mpo ★3](https://github.com/donatj/mpo) - Decoder and conversion tool for MPO 3D Photos.
* [picfit ★663](https://github.com/thoas/picfit) - An image resizing server written in Go.
* [pt ★1443](https://github.com/fogleman/pt) - Path tracing engine written in Go.
* [resize ★1497](https://github.com/nfnt/resize) - Image resizing for the Go with common interpolation methods.
* [rez ★138](https://github.com/bamiaux/rez) - Image resizing in pure Go and SIMD.
* [smartcrop ★873](https://github.com/muesli/smartcrop) - Finds good crops for arbitrary images and crop sizes.
* [svgo ★905](https://github.com/ajstarks/svgo) - Go Language Library for SVG generation.
* [tga ★16 ⏳2Y](https://github.com/ftrvxmtrx/tga) - Package tga is a TARGA image format decoder/encoder.

## IoT (Internet of Things)

*Libraries for programming devices of the IoT.*

* [connectordb ★72](https://github.com/connectordb/connectordb) - Open-Source Platform for Quantified Self & IoT.
* [devices ★187 ⏳1Y](https://github.com/goiot/devices) - Suite of libraries for IoT devices, experimental for x/exp/io.
* [eywa ★7](https://github.com/xcodersun/eywa) - Project Eywa is essentially a connection manager that keeps track of connected devices.
* [flogo ★244](https://github.com/tibcosoftware/flogo) - Project Flogo is an Open Source Framework for IoT Edge Apps & Integration.
* [gatt ★530](https://github.com/paypal/gatt) - Gatt is a Go package for building Bluetooth Low Energy peripherals.
* [gobot ★3359](https://github.com/hybridgroup/gobot) - Gobot is a framework for robotics, physical computing, and the Internet of Things.
* [mainflux ★203](https://github.com/Mainflux/mainflux) - Industrial IoT Messaging and Device Management Server.
* [sensorbee ★102](https://github.com/sensorbee/sensorbee) - Lightweight stream processing engine for IoT.

## Logging

*Libraries for generating and working with log files.*

* [glg ★1](https://github.com/kpango/glg) - glg is simple and fast leveled logging library for Go.
* [glog ★1465](https://github.com/golang/glog) - Leveled execution logs for Go.
* [go-cronowriter ★1](https://github.com/utahta/go-cronowriter) - Simple writer that rotate log files automatically based on current date and time, like cronolog.
* [go-log ★14 ⏳3Y](https://github.com/siddontang/go-log) - Log lib supports level and multi handlers.
* [go-log ★24](https://github.com/ian-kent/go-log) - Log4j implementation in Go.
* [go-logger ★162](https://github.com/apsdehal/go-logger) - Simple logger of Go Programs, with level handlers.
* [gologger ★25](https://github.com/sadlil/gologger) - Simple easy to use log lib for go, logs in Colored Console, Simple Console, File or Elasticsearch.
* [gomol ★6](https://github.com/aphistic/gomol) - Multiple-output, structured logging for Go with extensible logging outputs.
* [gone/log](https://github.com/One-com/gone/tree/master/log#readme) - Fast, extendable, full-featured, std-lib source compatible log library.
* [log ★423](https://github.com/apex/log) - Structured logging package for Go.
* [log ★216](https://github.com/go-playground/log) - Simple, configurable and scalable Structured Logging for Go.
* [log-voyage ★70](https://github.com/firstrow/logvoyage) - Full-featured logging saas written in golang.
* [log15 ★620](https://github.com/inconshreveable/log15) - Simple, powerful logging for Go.
* [logdump ★4](https://github.com/ewwwwwqm/logdump) - Package for multi-level logging.
* [logex ★28](https://github.com/chzyer/logex) - Golang log lib, supports tracking and level, wrap by standard log lib.
* [logger ★75 ⏳1Y](https://github.com/azer/logger) - Minimalistic logging library for Go.
* [logrus ★5322](https://github.com/Sirupsen/logrus) - Structured logger for Go.
* [logrusly](https://github.com/sebest/logrusly) - [logrus ★5322](https://github.com/sirupsen/logrus) plug-in to send errors to a [Loggly](https://www.loggly.com/).
* [logutils ★174 ⏳2Y](https://github.com/hashicorp/logutils) - Utilities for slightly better logging in Go (Golang) extending the standard logger.
* [logxi ★298](https://github.com/mgutz/logxi) - 12-factor app logger that is fast and makes you happy.
* [lumberjack ★553](https://github.com/natefinch/lumberjack) - Simple rolling logger, implements io.WriteCloser.
* [mlog ★11 ⏳1Y](https://github.com/jbrodriguez/mlog) - Simple logging module for go, with 5 levels, an optional rotating logfile feature and stdout/stderr output.
* [ozzo-log ★73 ⏳1Y](https://github.com/go-ozzo/ozzo-log) - High performance logging supporting log severity, categorization, and filtering. Can send filtered log messages to various targets (e.g. console, network, mail).
* [seelog ★945](https://github.com/cihub/seelog) - Logging functionality with flexible dispatching, filtering, and formatting.
* [slf ★33 ⏳1Y](https://github.com/ventu-io/slf) - The Structured Logging Facade (SLF) for Go (like SLF4J but structured and for Go).
* [slog ★22 ⏳1Y](https://github.com/ventu-io/slog) - The reference implementation of the Structured Logging Facade (SLF) for Go.
* [spew ★1522](https://github.com/davecgh/go-spew) - Implements a deep pretty printer for Go data structures to aid in debugging.
* [stdlog ★40 ⏳1Y](https://github.com/alexcesaro/log) - Stdlog is an object-oriented library providing leveled logging. It is very useful for cron jobs.
* [tail ★806](https://github.com/hpcloud/tail) - Go package striving to emulate the features of the BSD tail program.
* [xlog ★1](https://github.com/xfxdev/xlog) - Plugin architecture and flexible log system for Go, with level ctrl, multiple log target and custom log format.
* [xlog ★105](https://github.com/rs/xlog) - Structured logger for `net/context` aware HTTP handlers with flexible dispatching.
* [zap ★2680](https://github.com/uber-go/zap) - Fast, structured, leveled logging in Go.
* [zerolog ★418](https://github.com/rs/zerolog) - Zero-allocation JSON logger.

## Machine Learning

*Libraries for Machine Learning.*

* [bayesian ★473](https://github.com/jbrukh/bayesian) - Naive Bayesian Classification for Golang.
* [CloudForest ★541](https://github.com/ryanbressler/CloudForest) - Fast, flexible, multi-threaded ensembles of decision trees for machine learning in pure Go.
* [gago ★339](https://github.com/MaxHalford/gago) - Multi-population, flexible, parallel genetic algorithm.
* [go-fann ★90 ⏳2Y](https://github.com/white-pony/go-fann) - Go bindings for Fast Artificial Neural Networks(FANN) library.
* [go-galib ★150 ⏳1Y](https://github.com/thoj/go-galib) - Genetic Algorithms library written in Go / golang.
* [go-pr ★48 ⏳4Y](https://github.com/daviddengcn/go-pr) - Pattern recognition package in Go lang.
* [gobrain ★198](https://github.com/goml/gobrain) - Neural Networks written in go.
* [godist ★16 ⏳2Y](https://github.com/e-dard/godist) - Various probability distributions, and associated methods.
* [goga ★58](https://github.com/tomcraven/goga) - Genetic algorithm library for Go.
* [GoLearn ★4391](https://github.com/sjwhitworth/golearn) - General Machine Learning library for Go.
* [golinear ★34](https://github.com/danieldk/golinear) - liblinear bindings for Go.
* [goml ★746](https://github.com/cdipaolo/goml) - On-line Machine Learning in Go.
* [goRecommend ★82 ⏳3Y](https://github.com/timkaye11/goRecommend) - Recommendation Algorithms library written in Go.
* [gorgonia ★1234](https://github.com/chewxy/gorgonia) - graph-based computational library like Theano for Go that provides primitives for building various machine learning and neural network algorithms.
* [libsvm ★52 ⏳1Y](https://github.com/datastream/libsvm) - libsvm golang version derived work based on LIBSVM 3.14.
* [mlgo ★3 ⏳1Y](https://github.com/NullHypothesis/mlgo) - This project aims to provide minimalistic machine learning algorithms in Go.
* [neat ★27](https://github.com/jinyeom/neat) - Plug-and-play, parallel Go framework for NeuroEvolution of Augmenting Topologies (NEAT).
* [neural-go ★54 ⏳3Y](https://github.com/schuyler/neural-go) - Multilayer perceptron network implemented in Go, with training via backpropagation.
* [probab ★6 ⏳1Y](https://github.com/ThePaw/probab) - Probability distribution functions. Bayesian inference. Written in pure Go.
* [regommend ★162](https://github.com/muesli/regommend) - Recommendation & collaborative filtering engine.
* [shield ★104 ⏳1Y](https://github.com/eaigner/shield) - Bayesian text classifier with flexible tokenizers and storage backends for Go.

## Messaging

*Libraries that implement messaging systems.*

* [Centrifugo ★2025](https://github.com/centrifugal/centrifugo) - Real-time messaging (Websockets or SockJS) server in Go.
* [dbus ★162](https://github.com/godbus/dbus) - Native Go bindings for D-Bus.
* [drone-line ★37](https://github.com/appleboy/drone-line) - Sending [Line](https://business.line.me/en/services/bot) notifications using a binary, docker or Drone CI.
* [emitter ★138](https://github.com/olebedev/emitter) - Emits events using Go way, with wildcard, predicates, cancellation possibilities and many other good wins.
* [event ★2](https://github.com/agoalofalife/event) - Implementation of the pattern observer.
* [EventBus ★276](https://github.com/asaskevich/EventBus) - The lightweight event bus with async compatibility.
* [gaurun-client ★4](https://github.com/osamingo/gaurun-client) - Gaurun Client written in Go.
* [Glue ★229](https://github.com/desertbit/glue) - Robust Go and Javascript Socket Library (Alternative to Socket.io).
* [go-longpoll ★20 ⏳1Y](https://github.com/ventu-io/go-longpoll) - PubSub with long polling.
* [go-notify ★28 ⏳1Y](https://github.com/TheCreeper/go-notify) - Native implementation of the freedesktop notification spec.
* [go-nsq ★849](https://github.com/nsqio/go-nsq) - the official Go package for NSQ.
* [go-socket.io ★1795](https://github.com/googollee/go-socket.io) - socket.io library for golang, a realtime application framework.
* [go-vitotrol ★2](https://github.com/maxatome/go-vitotrol) - Client library to Viessmann Vitotrol web service.
* [Gollum ★547](https://github.com/trivago/gollum) - A n:m multiplexer that gathers messages from different sources and broadcasts them to a set of destinations.
* [golongpoll ★338 ⏳1Y](https://github.com/jcuga/golongpoll) - HTTP longpoll server library that makes web pub-sub simple.
* [goose ★30 ⏳2Y](https://github.com/ian-kent/goose) - Server Sent Events in Go.
* [gopush-cluster ★1553](https://github.com/Terry-Mao/gopush-cluster) - gopush-cluster is a go push server cluster.
* [gorush](https://github.com/appleboy/gorush) - Push notification server using [APNs2](https://github.com/sideshow/apns2) and google [GCM](https://github.com/google/go-gcm).
* [guble ★99](https://github.com/smancke/guble) - Messaging server using push notifications (Google Firebase Cloud Messaging, Apple Push Notification services, SMS) as well as websockets, a REST API, featuring distributed operation and message-persistence.
* [machinery ★1649](https://github.com/RichardKnop/machinery) - Asynchronous task queue/job queue based on distributed message passing.
* [mangos ★1180](https://github.com/go-mangos/mangos) - Pure go implementation of the Nanomsg ("Scalable Protocols") with transport interoperability.
* [melody ★666](https://github.com/olahol/melody) - Minimalist framework for dealing with websocket sessions, includes broadcasting and automatic ping/pong handling.
* [NATS Go Client](https://github.com/nats-io/nats) - Lightweight and high performance publish-subscribe and distributed queueing messaging system - this is the Go library.
* [nsq-event-bus ★16](https://github.com/rafaeljesus/nsq-event-bus) - A tiny wrapper around NSQ topic and channel.
* [oplog ★82 ⏳1Y](https://github.com/dailymotion/oplog) - Generic oplog/replication system for REST APIs.
* [pubsub](https://github.com/tuxychandru/pubsub) - Simple pubsub package for go.
* [RapidMQ ★27](https://github.com/sybrexsys/RapidMQ) - RapidMQ is a lightweight and reliable library for managing of the local messages queue.
* [sarama ★2054](https://github.com/Shopify/sarama) - Go library for Apache Kafka.
* [Uniqush-Push ★913](https://github.com/uniqush/uniqush-push) - Redis backed unified push service for server-side notifications to mobile devices.
* [zmq4](https://github.com/pebbe/zmq4) - Go interface to ZeroMQ version 4. Also available for [version 3](https://github.com/pebbe/zmq3) and [version 2 ★14](https://github.com/pebbe/zmq2).

## Miscellaneous

*These libraries were placed here because none of the other categories seemed to fit.*

* [alice ★5](https://github.com/magic003/alice) - Additive dependency injection container for Golang.
* [archiver ★635](https://github.com/mholt/archiver) - Library and command for making and extracting .zip and .tar.gz archives.
* [autoflags ★18](https://github.com/artyom/autoflags) - Go package to automatically define command line flags from struct fields.
* [avgRating ★3](https://github.com/kirillDanshin/avgRating) - Calculate average score and rating based on Wilson Score Equation.
* [banner ★136](https://github.com/dimiro1/banner) - Add beautiful banners into your Go applications.
* [battery ★70](https://github.com/distatus/battery) - Cross-platform, normalized battery information library.
* [bitio ★29](https://github.com/icza/bitio) - Highly optimized bit-level Reader and Writer for Go.
* [browscap_go ★24](https://github.com/digitalcrab/browscap_go) - GoLang Library for [Browser Capabilities Project](http://browscap.org/).
* [conv ★304](https://github.com/cstockton/go-conv) - Package conv provides fast and intuitive conversions across Go types.
* [datacounter ★17](https://github.com/miolini/datacounter) - Go counters for readers/writer/http.ResponseWriter.
* [errors ★2135](https://github.com/pkg/errors) - Package that provides simple error handling primitives.
* [go-chat-bot ★229](https://github.com/go-chat-bot/bot) - IRC, Slack & Telegram bot written in Go.
* [go-commons-pool ★378](https://github.com/jolestar/go-commons-pool) - Generic object pool for Golang.
* [go-multierror ★323](https://github.com/hashicorp/go-multierror) - Go (golang) package for representing a list of errors as a single error.
* [go-openapi](https://github.com/go-openapi) - Collection of packages to parse and utilize open-api schemas.
* [go-resiliency ★511](https://github.com/eapache/go-resiliency) - Resiliency patterns for golang.
* [go-sarah ★14](https://github.com/oklahomer/go-sarah) - Framework to build bot for desired chat services including LINE, Slack, Gitter and more.
* [go-shortid ★164](https://github.com/ventu-io/go-shortid) - Distributed generation of super short, unique, non-sequential, URL friendly IDs.
* [go-unarr ★14](https://github.com/gen2brain/go-unarr) - Decompression library for RAR, TAR, ZIP and 7z archives.
* [go.uuid ★1303](https://github.com/satori/go.uuid) - Implementation of Universally Unique Identifier (UUID). Supported both creation and parsing of UUIDs.
* [gofakeit ★41](https://github.com/brianvoe/gofakeit) - Random data generator written in go.
* [goid ★11](https://github.com/jakehl/goid) - Generate and Parse RFC4122 compliant V4 UUIDs.
* [gopsutil ★1849](https://github.com/shirou/gopsutil) - Cross-platform library for retrieving process and system utilization(CPU, Memory, Disks, etc).
* [gosms ★1037](https://github.com/haxpax/gosms) - Your own local SMS gateway in Go that can be used to send SMS.
* [gountries ★131](https://github.com/pariz/gountries) - Package that exposes country and subdivision data.
* [hanu ★31](https://github.com/sbstjn/hanu) - Framework for writing Slack bots.
* [health ★239](https://github.com/dimiro1/health) - Easy to use, extensible health check library.
* [indigo ★23](https://github.com/osamingo/indigo) - Distributed unique ID generator of using Sonyflake and encoded by Base58.
* [jobs ★398](https://github.com/albrow/jobs) - Persistent and flexible background jobs library.
* [margelet ★46](https://github.com/zhulik/margelet) - Framework for building Telegram bots.
* [secdl ★5](https://github.com/xor-gate/secdl) - Lighttpd ModSecDownload algorithm ported to go to secure download urls.
* [slacker ★102](https://github.com/shomali11/slacker) - Easy to use framework to create Slack bots.
* [stats ★71](https://github.com/go-playground/stats) - Monitors Go MemStats + System stats such as Memory, Swap and CPU and sends via UDP anywhere you want for logging etc...
* [uuid ★2](https://github.com/agext/uuid) - Generate, encode, and decode UUIDs v1 with fast or cryptographic-quality random node identifier.
* [VarHandler](https://github.com/azr/generators/tree/master/varhandler) - Generate boilerplate http input and ouput handling.
* [werr ★5 ⏳1Y](https://github.com/txgruppi/werr) - Error Wrapper creates an wrapper for the error type in Go which captures the File, Line and Stack of where it was called.
* [xkg ★25 ⏳2Y](https://github.com/go-xkg/xkg) - X Keyboard Grabber.
* [xstrings ★387 ⏳1Y](https://github.com/huandu/xstrings) - Collection of useful string functions ported from other languages.

## Natural Language Processing

*Libraries for working with human languages.*

* [dpar ★18 ⏳1Y](https://github.com/danieldk/dpar) - Transition-based statistical dependency parser.
* [go-eco ★2 ⏳1Y](https://github.com/ThePaw/go-eco) - Similarity, dissimilarity and distance matrices; diversity, equitability and inequality measures; species richness estimators; coenocline models.
* [go-i18n ★462](https://github.com/nicksnyder/go-i18n) - Package and an accompanying tool to work with localized text.
* [go-mystem ★7](https://github.com/dveselov/mystem) - CGo bindings to Yandex.Mystem - russian morphology analyzer.
* [go-nlp ★67 ⏳5Y](https://github.com/nuance/go-nlp) - Utilities for working with discrete probability distributions and other tools useful for doing NLP work.
* [go-stem ★42 ⏳2Y](https://github.com/agonopol/go-stem) - Implementation of the porter stemming algorithm.
* [go-unidecode ★16](https://github.com/mozillazg/go-unidecode) - ASCII transliterations of Unicode text.
* [go2vec ★22](https://github.com/danieldk/go2vec) - Reader and utility functions for word2vec embeddings.
* [gojieba](https://github.com/yanyiwu/gojieba) - This is a Go implementation of [jieba ★9639](https://github.com/fxsjy/jieba) which a Chinese word splitting algorithm.
* [golibstemmer ★12 ⏳3Y](https://github.com/rjohnsondev/golibstemmer) - Go bindings for the snowball libstemmer library including porter 2.
* [gounidecode ★54 ⏳1Y](https://github.com/fiam/gounidecode) - Unicode transliterator (also known as unidecode) for Go.
* [icu ★14](https://github.com/goodsign/icu) - Cgo binding for icu4c C library detection and conversion functions. Guaranteed compatibility with version 50.1.
* [libtextcat ★7 ⏳4Y](https://github.com/goodsign/libtextcat) - Cgo binding for libtextcat C library. Guaranteed compatibility with version 2.2.
* [MMSEGO ★52 ⏳5Y](https://github.com/awsong/MMSEGO) - This is a GO implementation of [MMSEG](http://technology.chtsai.org/mmseg/) which a Chinese word splitting algorithm.
* [nlp ★276](https://github.com/Shixzie/nlp) - Extract values from strings and fill your structs with nlp.
* [paicehusk ★17 ⏳3Y](https://github.com/rookii/paicehusk) - Golang implementation of the Paice/Husk Stemming Algorithm.
* [porter ★5 ⏳3Y](https://github.com/a2800276/porter) - This is a fairly straightforward port of Martin Porter's C implementation of the Porter stemming algorithm.
* [porter2](https://github.com/zhenjl/porter2) - Really fast Porter 2 stemmer.
* [prose ★190](https://github.com/jdkato/prose) - Library for text processing that supports tokenization, part-of-speech tagging, named-entity extraction, and more.
* [RAKE.go ★18](https://github.com/Obaied/RAKE.go) - Go port of the Rapid Automatic Keyword Extraction Algorithm (RAKE).
* [segment ★29](https://github.com/blevesearch/segment) - Go library for performing Unicode Text Segmentation as described in [Unicode Standard Annex #29](http://www.unicode.org/reports/tr29/)
* [sentences ★206](https://github.com/neurosnap/sentences) - Sentence tokenizer:  converts text into a list of sentences.
* [shamoji ★2](https://github.com/osamingo/shamoji) - The shamoji is word filtering package written in Go.
* [snowball ★14](https://github.com/goodsign/snowball) - Snowball stemmer port (cgo wrapper) for Go. Provides word stem extraction functionality [Snowball native](http://snowball.tartarus.org/).
* [stemmer ★35](https://github.com/dchest/stemmer) - Stemmer packages for Go programming language. Includes English and German stemmers.
* [textcat ★49](https://github.com/pebbe/textcat) - Go package for n-gram based text categorization, with support for utf-8 and raw text.
* [whatlanggo ★219](https://github.com/abadojack/whatlanggo) - Natural language detection package for Go. Supports 84 languages and 24 scripts (writing systems e.g. Latin, Cyrillic, etc).
* [when ★729](https://github.com/olebedev/when) - Natural EN and RU language date/time parser with pluggable rules.

## Networking

*Libraries for working with various layers of the network.*

* [arp ★92](https://github.com/mdlayher/arp) - Package arp implements the ARP protocol, as described in RFC 826.
* [buffstreams ★168](https://github.com/stabbycutyou/buffstreams) - Streaming protocolbuffer data over TCP made easy.
* [canopus ★82](https://github.com/zubairhamed/canopus) - CoAP Client/Server implementation (RFC 7252).
* [dhcp6 ★27](https://github.com/mdlayher/dhcp6) - Package dhcp6 implements a DHCPv6 server, as described in RFC 3315.
* [dns ★2280](https://github.com/miekg/dns) - Go library for working with DNS.
* [ether ★42 ⏳1Y](https://github.com/songgao/ether) - Cross-platform Go package for sending and receiving ethernet frames.
* [ethernet ★107](https://github.com/mdlayher/ethernet) - Package ethernet implements marshaling and unmarshaling of IEEE 802.3 Ethernet II frames and IEEE 802.1Q VLAN tags.
* [fasthttp ★4784](https://github.com/valyala/fasthttp) - Package fasthttp is a fast HTTP implementation for Go, up to 10 times faster than net/http.
* [ftp ★245](https://github.com/jlaffaye/ftp) - Package ftp implements a FTP client as described in [RFC 959](http://tools.ietf.org/html/rfc959).
* [go-getter ★359](https://github.com/hashicorp/go-getter) - Go library for downloading files or directories from various sources using a URL.
* [go-stun ★158](https://github.com/ccding/go-stun) - Go implementation of the STUN client (RFC 3489 and RFC 5389).
* [gobgp ★1009](https://github.com/osrg/gobgp) - BGP implemented in the Go Programming Language.
* [golibwireshark ★7](https://github.com/sunwxg/golibwireshark) - Package golibwireshark use libwireshark library to decode pcap file and analyse dissection data.
* [gopacket ★1391](https://github.com/google/gopacket) - Go library for packet processing with libpcap bindings.
* [gopcap ★273](https://github.com/akrennmair/gopcap) - Go wrapper for libpcap.
* [goshark ★5](https://github.com/sunwxg/goshark) - Package goshark use tshark to decode IP packet and create data struct to analyse packet.
* [gosnmp ★214](https://github.com/soniah/gosnmp) - Native Go library for performing SNMP actions.
* [gotcp ★283](https://github.com/gansidui/gotcp) - Go package for quickly writing tcp applications.
* [grab ★203](https://github.com/cavaliercoder/grab) - Go package for managing file downloads.
* [graval ★17](https://github.com/koofr/graval) - Experimental FTP server framework.
* [jazigo ★62](https://github.com/udhos/jazigo) - Jazigo is a tool written in Go for retrieving configuration for multiple network devices.
* [kcp-go ★740](https://github.com/xtaci/kcp-go) - KCP - Fast and Reliable ARQ Protocol.
* [kcptun ★5945](https://github.com/xtaci/kcptun) - Extremely simple & fast udp tunnel based on KCP protocol.
* [lhttp ★340](https://github.com/fanux/lhttp) - Powerful websocket framework, build your IM server more easily.
* [linkio ★27](https://github.com/ian-kent/linkio) - Network link speed simulation for Reader/Writer interfaces.
* [llb ★5 ⏳1Y](https://github.com/kirillDanshin/llb) - It's a very simple but quick backend for proxy servers. Can be useful for fast redirection to predefined domain with zero memory allocation and fast response.
* [mdns ★343](https://github.com/hashicorp/mdns) - Simple mDNS (Multicast DNS) client/server library in Golang.
* [mqttPaho](https://eclipse.org/paho/clients/golang/) - The Paho Go Client provides an MQTT client library for connection to MQTT brokers via TCP, TLS or WebSockets.
* [portproxy ★31 ⏳2Y](https://github.com/aybabtme/portproxy) - Simple TCP proxy which adds CORS support to API's which don't support it.
* [publicip ★9](https://github.com/polera/publicip) - Package publicip returns your public facing IPv4 address (internet egress).
* [raw ★104](https://github.com/mdlayher/raw) - Package raw enables reading and writing data at the device driver level for a network interface.
* [sftp ★380](https://github.com/pkg/sftp) - Package sftp implements the SSH File Transfer Protocol as described in https://filezilla-project.org/specs/draft-ietf-secsh-filexfer-02.txt.
* [ssh ★462](https://github.com/gliderlabs/ssh) - Higher-level API for building SSH servers (wraps crypto/ssh).
* [sslb ★90](https://github.com/eduardonunesp/sslb) - It's a Super Simples Load Balancer, just a little project to achieve some kind of performance.
* [tcp_server ★136](https://github.com/firstrow/tcp_server) - Go library for building tcp servers faster.
* [utp ★107](https://github.com/anacrolix/utp) - Go uTP micro transport protocol implementation.
* [water ★276](https://github.com/songgao/water) - Simple TUN/TAP library.
* [winrm ★125](https://github.com/masterzen/winrm) - Go WinRM client to remotely execute commands on Windows machines.
* [xtcp ★19](https://github.com/xfxdev/xtcp) - TCP Server Framework with simultaneous full duplex communication,graceful shutdown,custom protocol.

## OpenGL

*Libraries for using OpenGL in Go.*

* [gl ★379](https://github.com/go-gl/gl) - Go bindings for OpenGL (generated via glow).
* [glfw ★398](https://github.com/go-gl/glfw) - Go bindings for GLFW 3.
* [goxjs/gl ★96](https://github.com/goxjs/gl) - Go cross-platform OpenGL bindings (OS X, Linux, Windows, browsers, iOS, Android).
* [goxjs/glfw ★42](https://github.com/goxjs/glfw) - Go cross-platform glfw library for creating an OpenGL context and receiving events.
* [mathgl ★183 ⏳1Y](https://github.com/go-gl/mathgl) - Pure Go math package specialized for 3D math, with inspiration from GLM.

## ORM

*Libraries that implement Object-Relational Mapping or datamapping techniques.*

* [beego orm](https://github.com/astaxie/beego/tree/master/orm) - Powerful orm framework for go. Support: pq/mysql/sqlite3.
* [go-pg ★993](https://github.com/go-pg/pg) - PostgreSQL ORM with focus on PostgreSQL specific features and performance.
* [go-store ★82](https://github.com/gosuri/go-store) - Simple and fast Redis backed key-value store library for Go.
* [gomodel ★54](https://github.com/cosiner/gomodel) - Lightweight, fast, orm-like library helps interactive with database.
* [GORM ★6363](https://github.com/jinzhu/gorm) - The fantastic ORM library for Golang, aims to be developer friendly.
* [gorp ★2544](https://github.com/go-gorp/gorp) - Go Relational Persistence, ORM-ish library for Go.
* [pop/soda ★260](https://github.com/markbates/pop) - Database migration, creation, ORM, etc... for MySQL, PostgreSQL, and SQLite.
* [QBS ★457](https://github.com/coocood/qbs) - Stands for Query By Struct. A Go ORM.
* [reform ★540](https://github.com/go-reform/reform) - Better ORM for Go, based on non-empty interfaces and code generation.
* [SQLBoiler ★729](https://github.com/volatiletech/sqlboiler) - ORM generator. Generate a featureful and blazing-fast ORM tailored to your database schema.
* [upper.io/db ★937](https://github.com/upper/db) - Single interface for interacting with different data sources through the use of adapters that wrap mature database drivers.
* [Xorm ★2196](https://github.com/go-xorm/xorm) - Simple and powerful ORM for Go.
* [Zoom ★163](https://github.com/albrow/zoom) - Blazing-fast datastore and querying engine built on Redis.

## Package Management

*Libraries for package and dependency management.*

* [dep ★4173](https://github.com/golang/dep) - Go dependency tool.
* [gigo ★187 ⏳2Y](https://github.com/LyricalSecurity/gigo) - PIP-like dependency tool for golang, with support for private repositories and hashes.
* [glide ★5153](https://github.com/Masterminds/glide) - Manage your golang vendor and vendored packages with ease. Inspired by tools like Maven, Bundler, and Pip.
* [godep ★4836](https://github.com/tools/godep) - dependency tool for go, godep helps build packages reproducibly by fixing their dependencies.
* [gom ★1274](https://github.com/mattn/gom) - Go Manager - bundle for go.
* [goop](https://github.com/nitrous-io/goop) - Simple dependency manager for Go (golang), inspired by Bundler.
* [gop ★28](https://github.com/lunny/gop) - Build and manage your Go applications out of GOPATH
* [gopm ★1491](https://github.com/gpmgo/gopm) - Go Package Manager.
* [govendor ★2314](https://github.com/kardianos/govendor) - Go Package Manager. Go vendor tool that works with the standard vendor file.
* [gpm ★1151](https://github.com/pote/gpm) - Barebones dependency manager for Go.
* [gvt ★673](https://github.com/FiloSottile/gvt) - `gvt` is a simple vendoring tool made for Go native vendoring (aka GO15VENDOREXPERIMENT), based on gb-vendor.
* [johnny-deps ★214 ⏳3Y](https://github.com/VividCortex/johnny-deps) - Minimal dependency version using Git.
* [nut ★248 ⏳2Y](https://github.com/jingweno/nut) - Vendor Go dependencies.
* [VenGO ★98 ⏳1Y](https://github.com/DamnWidget/VenGO) - create and manage exportable isolated go virtual environments.

## Query Language

* [graphql ★41](https://github.com/tmc/graphql) - graphql parser + utilities.
* [graphql ★32 ⏳1Y](https://github.com/sevki/graphql) - GraphQL implementation in go.
* [graphql ★675](https://github.com/neelance/graphql-go) - GraphQL server with a focus on ease of use.
* [graphql-go ★1790](https://github.com/graphql-go/graphql) - Implementation of GraphQL for Go.
* [jsonql ★104 ⏳1Y](https://github.com/elgs/jsonql) - JSON query expression library in Golang.

## Resource Embedding

* [esc ★223](https://github.com/mjibson/esc) - Embeds files into Go programs and provides http.FileSystem interfaces to them.
* [fileb0x ★167](https://github.com/UnnoTed/fileb0x) - Simple tool to embed files in go with focus on "customization" and ease to use.
* [go-bindata ★3040](https://github.com/jteeuwen/go-bindata) - Package that converts any file into managable Go source code.
* [go-embed ★8 ⏳1Y](https://github.com/pyros2097/go-embed) - Generates go code to embed resource files into your library or executable.
* [go-resources ★118](https://github.com/omeid/go-resources) - Unfancy resources embedding with Go.
* [go.rice ★1046](https://github.com/GeertJohan/go.rice) - go.rice is a Go package that makes working with resources such as html,js,css,images and templates very easy.
* [statics ★41](https://github.com/go-playground/statics) - Embeds static resources into go files for single binary compilation + works with http.FileSystem + symlinks.
* [statik ★633](https://github.com/rakyll/statik) - Embeds static files into a Go executable.
* [templify ★4](https://github.com/wlbr/templify) - Embed external template files into Go code to create single file binaries.
* [vfsgen ★175](https://github.com/shurcooL/vfsgen) - Generates a vfsdata.go file that statically implements the given virtual filesystem.

## Science and Data Analysis

*Libraries for scientific computing and data analyzing.*

* [blas ★109 ⏳3Y](https://github.com/ziutek/blas) - Implementation of BLAS (Basic Linear Algebra Subprograms).
* [chart ★422 ⏳1Y](https://github.com/vdobler/chart) - Simple Chart Plotting library for Go. Supports many graphs types.
* [evaler ★30](https://github.com/soniah/evaler) - Simple floating point arithmetic expression evaluator.
* [ewma ★184](https://github.com/VividCortex/ewma) - Exponentially-weighted moving averages.
* [geom ★33 ⏳4Y](https://github.com/skelterjohn/geom) - 2D geometry for golang.
* [go-dsp ★473](https://github.com/mjibson/go-dsp) - Digital Signal Processing for Go.
* [go-fn ★6 ⏳2Y](https://github.com/ematvey/go-fn) - Mathematical functions written in Go language, that are not covered by math pkg.
* [go-gt ★3 ⏳1Y](https://github.com/ThePaw/go-gt) - Graph theory algorithms written in "Go" language.
* [go.matrix ★297 ⏳1Y](https://github.com/skelterjohn/go.matrix) - linear algebra for go (has been stalled).
* [gocomplex ★3 ⏳2Y](https://github.com/varver/gocomplex) - Complex number library for the Go programming language.
* [gofrac ★6 ⏳2Y](https://github.com/anschelsc/gofrac) - (goinstallable) fractions library for go with support for basic arithmetic.
* [gohistogram ★94](https://github.com/VividCortex/gohistogram) - Approximate histograms for data streams.
* [gonum/mat64 ★474](https://github.com/gonum/matrix) - The general purpose package for matrix computation. Package mat64 provides basic linear algebra operations for float64 matrices.
* [gonum/plot ★558](https://github.com/gonum/plot) - gonum/plot provides an API for building and drawing plots in Go.
* [goraph ★393](https://github.com/gyuho/goraph) - Pure Go graph theory library(data structure, algorith visualization).
* [gostat ★18 ⏳2Y](https://github.com/ematvey/gostat) - Statistics library for the go language.
* [graph ★11](https://github.com/yourbasic/graph) - Library of basic graph algorithms.
* [ode ★2](https://github.com/ChristopherRabotin/ode) - Ordinary differential equation (ODE) solver which supports extended states and channel-based iteration stop conditions.
* [pagerank ★30 ⏳1Y](https://github.com/alixaxel/pagerank) - Weighted PageRank algorithm implemented in Go.
* [PiHex ★5](https://github.com/claygod/PiHex) - Implementation of the "Bailey-Borwein-Plouffe" algorithm for the hexadecimal number Pi.
* [stats ★746](https://github.com/montanaflynn/stats) - Statistics package with common functions missing from the Golang standard library.
* [streamtools ★1294 ⏳2Y](https://github.com/nytlabs/streamtools) - general purpose, graphical tool for dealing with streams of data.
* [vectormath ★57 ⏳4Y](https://github.com/spate/vectormath) - Vectormath for Go, an adaptation of the scalar C functions from Sony's Vector Math library, as found in the Bullet-2.79 source code (currently inactive).

## Security

*Libraries that are used to help make your application more secure.*

* [acmetool ★1293](https://github.com/hlandau/acme) - ACME (Let's Encrypt) client tool with automatic renewal.
* [BadActor ★209](https://github.com/jaredfolkins/badactor) - In-memory, application-driven jailer built in the spirit of fail2ban.
* [go-yara](https://github.com/hillu/go-yara) - Go Bindings for [YARA ★43 ⏳1Y](https://github.com/plusvic/yara), the "pattern matching swiss knife for malware researchers (and everyone else)".
* [lego ★2035](https://github.com/xenolf/lego) - Pure Go ACME client library and CLI tool (for use with Let's Encrypt).
* [memguard ★577](https://github.com/awnumar/memguard) - A pure Go library for handling sensitive values in memory.
* [passlib ★161](https://github.com/hlandau/passlib) - Futureproof password hashing library.
* [secure ★728](https://github.com/unrolled/secure) - HTTP middleware for Go that facilitates some quick security wins.
* [simple-scrypt ★114](https://github.com/elithrar/simple-scrypt) - Scrypt package with a simple, obvious API and automatic cost calibration built-in.
* [ssh-vault ★63](https://github.com/ssh-vault/ssh-vault) - encrypt/decrypt using ssh keys.

## Serialization

*Libraries and tools for binary serialization.*

* [asn1](https://github.com/PromonLogicalis/asn1) - Asn.1 BER and DER encoding library for golang.
* [colfer ★253](https://github.com/pascaldekloe/colfer) - Code generation for the Colfer binary format.
* [go-capnproto ★254](https://github.com/glycerine/go-capnproto) - Cap'n Proto library and parser for go.
    * [bambam ★57](https://github.com/glycerine/bambam) - generator for Cap'n Proto schemas from go.
* [go-codec ★809](https://github.com/ugorji/go) - High Performance, feature-Rich, idiomatic encode, decode and rpc library for msgpack, cbor and json, with runtime-based OR code-generation support.
* [gogoprotobuf ★1102](https://github.com/gogo/protobuf) - Protocol Buffers for Go with Gadgets.
* [goprotobuf ★2017](https://github.com/golang/protobuf) - Go support, in the form of a library and protocol compiler plugin, for Google's protocol buffers.
* [jsoniter ★974](https://github.com/json-iterator/go) - High-performance 100% compatible drop-in replacement of "encoding/json".
* [mapstructure ★1043](https://github.com/mitchellh/mapstructure) - Go library for decoding generic map values into native Go structures.
* [php_session_decoder ★74](https://github.com/yvasiyarov/php_session_decoder) - GoLang library for working with PHP session format and PHP Serialize/Unserialize functions.
* [structomap ★61 ⏳2Y](https://github.com/tuvistavie/structomap) - Library to easily and dynamically generate maps from static structures.

## Server Applications

* [algernon ★359](https://github.com/xyproto/algernon) - HTTP/2 web server with built-in support for Lua, Markdown, GCSS and Amber.
* [Caddy ★13535](https://github.com/mholt/caddy) - Caddy is an alternative, HTTP/2 web server that's easy to configure and use.
* [consul](https://www.consul.io/) - Consul is a tool for service discovery, monitoring and configuration.
* [devd ★2376](https://github.com/cortesi/devd) - Local webserver for developers.
* [etcd ★14528](https://github.com/coreos/etcd) - Highly-available key value store for shared configuration and service discovery.
* [minio ★7944](https://github.com/minio/minio) - Minio is a distributed object storage server.
* [nsq](http://nsq.io/) - A realtime distributed messaging platform.
* [yakvs ★18](https://github.com/sci4me/yakvs) - Small, networked, in-memory key-value store.

## Template Engines

*Libraries and tools for templating and lexing.*

* [ace ★611](https://github.com/yosssi/ace) - Ace is an HTML template engine for Go, inspired by Slim and Jade. Ace is a refinement of Gold.
* [amber ★740](https://github.com/eknkc/amber) - Amber is an elegant templating engine for Go Programming Language It is inspired from HAML and Jade.
* [damsel ★19 ⏳1Y](https://github.com/dskinner/damsel) - Markup language featuring html outlining via css-selectors, extensible via pkg html/template and others.
* [ego ★320](https://github.com/benbjohnson/ego) - Lightweight templating language that lets you write templates in Go. Templates are translated into Go and compiled.
* [fasttemplate ★143](https://github.com/valyala/fasttemplate) - Simple and fast template engine. Substitutes template placeholders up to 10x faster than [text/template](http://golang.org/pkg/text/template/).
* [gofpdf ★696](https://github.com/jung-kurt/gofpdf) - PDF document generator with high level support for text, drawing and images.
* [grender ★58](https://github.com/dannyvankooten/grender) - small wrapper around html/template for file-based templates that support extending other template files.
* [hero ★776](https://github.com/shiyanhui/hero) - Hero is a handy, fast and powerful go template engine.
* [jet ★396](https://github.com/CloudyKit/jet) - Jet template engine.
* [kasia.go ★70 ⏳2Y](https://github.com/ziutek/kasia.go) - Templating system for HTML and other text documents - go implementation.
* [liquid ★25](https://github.com/osteele/liquid) - Go implementation of Shopify Liquid templates.
* [mustache ★848](https://github.com/hoisie/mustache) - Go implementation of the Mustache template language.
* [pongo2 ★1010](https://github.com/flosch/pongo2) - Django-like template-engine for Go.
* [quicktemplate ★786](https://github.com/valyala/quicktemplate) - Fast, powerful, yet easy to use template engine. Converts templates into Go code and then compiles it.
* [raymond ★183](https://github.com/aymerick/raymond) - Complete handlebars implementation in Go.
* [Razor ★592 ⏳1Y](https://github.com/sipin/gorazor) - Razor view engine for Golang.
* [Soy ★120](https://github.com/robfig/soy) - Closure templates (aka Soy templates) for Go, following the [official spec](https://developers.google.com/closure/templates/).
* [velvet ★52](https://github.com/gobuffalo/velvet) - Complete handlebars implementation in Go.

## Testing

*Libraries for testing codebases and generating test data.*

* Testing Frameworks
    * [assert ★9 ⏳1Y](https://github.com/go-playground/assert) - Basic Assertion Library used along side native go testing, with building blocks for custom assertions.
    * [badio ★2 ⏳1Y](https://github.com/cavaliercoder/badio) - Extensions to Go's `testing/iotest` package.
    * [baloo ★270](https://github.com/h2non/baloo) - Expressive and versatile end-to-end HTTP API testing made easy.
    * [bro ★13](https://github.com/marioidival/bro) - Watch files in directory and run tests for them.
    * [cupaloy ★5](https://github.com/bradleyjkemp/cupaloy) - Simple snapshot testing addon for your test framework.
    * [dbcleaner ★20](https://github.com/khaiql/dbcleaner) - Clean database for testing purpose, inspired by `database_cleaner` in Ruby.
    * [dsunit ★4](https://github.com/viant/dsunit) - Datastore testing for SQL, NoSQL, structured files.
    * [frisby ★201](https://github.com/verdverm/frisby) - REST API testing framework.
    * [ginkgo](http://onsi.github.io/ginkgo/) - BDD Testing Framework for Go.
    * [go-carpet ★160](https://github.com/msoap/go-carpet) - Tool for viewing test coverage in terminal.
    * [go-mutesting ★101](https://github.com/zimmski/go-mutesting) - Mutation testing for Go source code.
    * [go-vcr ★150](https://github.com/dnaeon/go-vcr) - Record and replay your HTTP interactions for fast, deterministic and accurate tests.
    * [goblin ★401](https://github.com/franela/goblin) - Mocha like testing framework fo Go.
    * [gocheck](http://labix.org/gocheck) - More advanced testing framework alternative to gotest.
    * [GoConvey ★3007](https://github.com/smartystreets/goconvey) - BDD-style framework with web UI and live reload.
    * [godog ★226](https://github.com/DATA-DOG/godog) - Cucumber or Behat like BDD framework for Go.
    * [gofight ★101](https://github.com/appleboy/gofight) - API Handler Testing for Golang Router framework.
    * [gomega](http://onsi.github.io/gomega/) - Rspec like matcher/assertion library.
    * [GoSpec ★109 ⏳3Y](https://github.com/orfjackal/gospec) - BDD-style testing framework for the Go programming language.
    * [gospecify ★51 ⏳5Y](https://github.com/stesla/gospecify) - This provides a BDD syntax for testing your Go code. It should be familiar to anybody who has used libraries such as rspec.
    * [gosuite ★3](https://github.com/pavlo/gosuite) - Brings lightweight test suites with setup/teardown facilities to `testing` by leveraging Go1.7's Subtests.
    * [Hamcrest ★24 ⏳6Y](https://github.com/rdrdr/hamcrest) - fluent framework for declarative Matcher objects that, when applied to input values, produce self-describing results.
    * [httpexpect ★741](https://github.com/gavv/httpexpect) - Concise, declarative, and easy to use end-to-end HTTP and REST API testing.
    * [restit](https://github.com/yookoala/restit) - Go micro framework to help writing RESTful API integration test.
    * [testfixtures ★111](https://github.com/go-testfixtures/testfixtures) - A helper for Rails' like test fixtures to test database applications.
    * [Testify ★3593](https://github.com/stretchr/testify) - Sacred extension to the standard go testing package.
    * [wstest ★20](https://github.com/posener/wstest) - Websocket client for unit-testing a websocket http.Handler.

* Mock
    * [counterfeiter ★160](https://github.com/maxbrunsfeld/counterfeiter) - Tool for generating self-contained mock objects.
    * [go-sqlmock ★520](https://github.com/DATA-DOG/go-sqlmock) - Mock SQL driver for testing database interactions.
    * [go-txdb ★33](https://github.com/DATA-DOG/go-txdb) - Single transaction based database driver mainly for testing purposes.
    * [gock ★335](https://github.com/h2non/gock) - Versatile HTTP mocking made easy.
    * [gomock ★755](https://github.com/golang/mock) - Mocking framework for the Go programming language.
    * [govcr ★26](https://github.com/seborama/govcr) - HTTP mock for Golang: record and replay HTTP interactions for offline testing.
    * [minimock ★72](https://github.com/gojuno/minimock) - Mock generator for Go interfaces.
    * [mockhttp ★18 ⏳2Y](https://github.com/tv42/mockhttp) - Mock object for Go http.ResponseWriter.

* Fuzzing and delta-debugging/reducing/shrinking.
    * [go-fuzz ★1927](https://github.com/dvyukov/go-fuzz) - Randomized testing system.
    * [gofuzz ★340](https://github.com/google/gofuzz) - Library for populating go objects with random values.
    * [Tavor ★167](https://github.com/zimmski/tavor) - Generic fuzzing and delta-debugging framework.

* Selenium and browser control tools.
    * [cdp ★33](https://github.com/mafredri/cdp) - Type-safe bindings for the Chrome Debugging Protocol that can be used with browsers or other debug targets that implement it.
    * [chromedp ★1385](https://github.com/knq/chromedp) - Way to drive/test Chrome, Safari, Edge, Android Webviews, and other browsers supporting the Chrome Debugging Protocol.
    * [ggr ★4](https://github.com/aandryashin/ggr) - Lightweight server that routes and proxies Selenium Wedriver requests to multiple Selenium hubs.
    * [selenoid ★2](https://github.com/aandryashin/selenoid) - alternative Selenium hub server that launches browsers within containers.

## Text Processing

*Libraries for parsing and manipulating texts.*

* Specific Formats
    * [align ★26](https://github.com/Guitarbum722/align) - A general purpose application that aligns text.
    * [allot ★19](https://github.com/sbstjn/allot) - Placeholder and wildcard text parsing for CLI tools and bots.
    * [bbConvert ★2](https://github.com/CalebQ42/bbConvert) - Converts bbCode to HTML that allows you to add support for custom bbCode tags.
    * [blackfriday ★2565](https://github.com/russross/blackfriday) - Markdown processor in Go.
    * [bluemonday ★706](https://github.com/microcosm-cc/bluemonday) - HTML Sanitizer.
    * [doi ★0](https://github.com/hscells/doi) - Document object identifier (doi) parser in Go.
    * [editorconfig-core-go ★15 ⏳1Y](https://github.com/editorconfig/editorconfig-core-go) - Editorconfig file parser and manipulator for Go.
    * [enca ★3 ⏳1Y](https://github.com/endeveit/enca) - Minimal cgo bindings for [libenca](http://cihar.com/software/enca/).
    * [genex ★40 ⏳1Y](https://github.com/alixaxel/genex) - Count and expand Regular Expressions into all matching Strings.
    * [github_flavored_markdown](https://godoc.org/github.com/shurcooL/github_flavored_markdown) - GitHub Flavored Markdown renderer (using blackfriday) with fenced code block highlighting, clickable header anchor links.
    * [go-humanize ★1086](https://github.com/dustin/go-humanize) - Formatters for time, numbers, and memory size to human readable format.
    * [go-nmea ★31](https://github.com/adrianmo/go-nmea) - NMEA parser library for the Go language.
    * [go-pkg-rss ★300 ⏳1Y](https://github.com/jteeuwen/go-pkg-rss) - This package reads RSS and Atom feeds and provides a caching mechanism that adheres to the feed specs.
    * [go-runewidth ★86](https://github.com/mattn/go-runewidth) - Functions to get fixed width of the character or string.
    * [go-slugify ★14 ⏳1Y](https://github.com/mozillazg/go-slugify) - Make pretty slug with multiple languages support.
    * [go-vcard ★4](https://github.com/emersion/go-vcard) - Parse and format vCard.
    * [gofeed ★661](https://github.com/mmcdole/gofeed) - Parse RSS and Atom feeds in Go.
    * [gographviz ★124](https://github.com/awalterschulze/gographviz) - Parses the Graphviz DOT language.
    * [gommon/bytes](https://github.com/labstack/gommon/tree/master/bytes) - Format bytes to string.
    * [gonameparts ★24](https://github.com/polera/gonameparts) - Parses human names into individual name parts.
    * [goq ★35](https://github.com/andrewstuart/goq) - Declarative unmarshaling of HTML using struct tags with jQuery syntax (uses GoQuery).
    * [GoQuery ★4477](https://github.com/PuerkitoBio/goquery) - GoQuery brings a syntax and a set of features similar to jQuery to the Go language.
    * [goregen ★27 ⏳1Y](https://github.com/zach-klippenstein/goregen) - Library for generating random strings from regular expressions.
    * [gotext ★132](https://github.com/leonelquinteros/gotext) - GNU gettext utilities for Go.
    * [guesslanguage ★32 ⏳2Y](https://github.com/endeveit/guesslanguage) - Functions to determine the natural language of a unicode text.
    * [inject ★698](https://github.com/facebookgo/inject) - Package inject provides a reflect based injector.
    * [mxj ★194](https://github.com/clbanning/mxj) - Encode / decode XML as JSON or map[string]interface{}; extract values with dot-notation paths and wildcards. Replaces x2j and j2x packages.
    * [sh ★593](https://github.com/mvdan/sh) - Shell parser and formatter.
    * [slug ★126](https://github.com/gosimple/slug) - URL-friendly slugify with multiple languages support.
    * [Slugify ★13 ⏳2Y](https://github.com/avelino/slugify) - Go slugify application that handles string.
    * [toml ★1532](https://github.com/BurntSushi/toml) - TOML configuration format (encoder/decoder with reflection).
* Utility
    * [gotabulate ★159](https://github.com/bndr/gotabulate) - Easily pretty-print your tabular data with Go.
    * [kace ★4](https://github.com/codemodus/kace) - Common case conversions covering common initialisms.
    * [parseargs-go](https://github.com/nproc/parseargs-go) - string argument parser that understands quotes and backslashes.
    * [parth ★14](https://github.com/codemodus/parth) - URL path segmentation parsing.
    * [radix ★23](https://github.com/yourbasic/radix) - fast string sorting algorithm.
    * [xurls ★277](https://github.com/mvdan/xurls) - Extract urls from text.

## Third-party APIs

*Libraries for accessing third party APIs.*

* [amazon-product-advertising-api ★16](https://github.com/ngs/go-amazon-product-advertising-api) - Go Client Library for [Amazon Product Advertising API](https://affiliate-program.amazon.com/gp/advertising/api/detail/main.html).
* [anaconda ★750](https://github.com/ChimeraCoder/anaconda) - Go client library for the Twitter 1.1 API.
* [aws-sdk-go ★3364](https://github.com/aws/aws-sdk-go) - The official AWS SDK for the Go programming language.
* [brewerydb ★11 ⏳2Y](https://github.com/naegelejd/brewerydb) - Go library for accessing the BreweryDB API.
* [cachet ★33 ⏳1Y](https://github.com/andygrunwald/cachet) - Go client library for [Cachet (open source status page system)](https://cachethq.io/).
* [circleci ★13](https://github.com/jszwedko/go-circleci) - Go client library for interacting with CircleCI's API.
* [clarifai](https://github.com/samuelcouch/clarifai) - Go client library for interfacing with the Clarifai API.
* [discordgo ★355](https://github.com/bwmarrin/discordgo) - Go bindings for the Discord Chat API.
* [facebook ★484](https://github.com/huandu/facebook) - Go Library that supports the Facebook Graph API.
* [fcm ★16](https://github.com/maddevsio/fcm) - Go library for Firebase Cloud Messaging.
* [gads ★25](https://github.com/emiddleton/gads) - Google Adwords Unofficial API.
* [gami ★20](https://github.com/bit4bit/gami) - Go library for Asterisk Manager Interface.
* [gcm ★30 ⏳1Y](https://github.com/Aorioli/gcm) - Go library for Google Cloud Messaging.
* [geo-golang ★199](https://github.com/codingsince1985/geo-golang) - Go Library to access [Google Maps](https://developers.google.com/maps/documentation/geocoding/intro), [MapQuest](http://open.mapquestapi.com/geocoding/), [Nominatim](http://open.mapquestapi.com/nominatim/), [OpenCage](http://geocoder.opencagedata.com/api.html), [HERE](https://developer.here.com/rest-apis/documentation/geocoder), [Bing](https://msdn.microsoft.com/en-us/library/ff701715.aspx), [Mapbox](https://www.mapbox.com/developers/api/geocoding/), and [OpenStreetMap](https://wiki.openstreetmap.org/wiki/Nominatim) geocoding / reverse geocoding APIs.
* [ghost ★21 ⏳1Y](https://github.com/neuegram/ghost) - Go Library for accessing the Snapchat API.
* [github ★2809](https://github.com/google/go-github) - Go library for accessing the GitHub REST API v3.
* [githubql ★96](https://github.com/shurcooL/githubql) - Go library for accessing the GitHub GraphQL API v4.
* [go-hacknews ★2](https://github.com/PaulRosset/go-hacknews) - Tiny Go client for HackerNews API.
* [go-imgur ★5 ⏳1Y](https://github.com/koffeinsource/go-imgur) - Go client library for [imgur](https://imgur.com)
* [go-jira ★161](https://github.com/andygrunwald/go-jira) - Go client library for [Atlassian JIRA](https://www.atlassian.com/software/jira)
* [go-marathon ★147](https://github.com/gambol99/go-marathon) - Go library for interacting with Mesosphere's Marathon PAAS.
* [go-myanimelist ★9](https://github.com/nstratos/go-myanimelist) - Go client library for accessing the [MyAnimeList API](http://myanimelist.net/modules.php?go=api).
* [go-telegraph ★33](https://github.com/toby3d/go-telegraph) - Telegraph publishing platform API client.
* [go-tgbot ★44](https://github.com/olebedev/go-tgbot) - Pure Golang Telegram Bot API wrapper, generated from swagger file, session-based router and middleware.
* [go-trending](https://github.com/andygrunwald/go-trending) - Go library for accessing [trending repositories](https://github.com/trending) and [developers](https://github.com/trending/developers) at Github.
* [go-twitch ★7](https://github.com/knspriggs/go-twitch) - Go client for interacting with the Twitch v3 API.
* [go-twitter ★293](https://github.com/dghubble/go-twitter) - Go client library for the Twitter v1.1 APIs.
* [go-unsplash ★2](https://github.com/hbagdi/go-unsplash) - Go client library for the [Unsplash.com](https://unsplash.com) API.
* [go-xkcd ★21 ⏳1Y](https://github.com/nishanths/go-xkcd) - Go client for the xkcd API.
* [goamz ★671](https://github.com/mitchellh/goamz) - Popular fork of [goamz](https://launchpad.net/goamz) which adds some missing API calls to certain packages.
* [golyrics ★18](https://github.com/mamal72/golyrics) - Golyrics is a Go library to fetch music lyrics data from the Wikia website.
* [GoMusicBrainz ★24](https://github.com/michiwend/gomusicbrainz) - Go MusicBrainz WS2 client library.
* [google ★1088](https://github.com/google/google-api-go-client) - Auto-generated Google APIs for Go.
* [google-analytics ★7 ⏳2Y](https://github.com/chonthu/go-google-analytics) - Simple wrapper for easy google analytics reporting.
* [google-cloud](https://github.com/GoogleCloudPlatform/gcloud-golang) - Google Cloud APIs Go Client Library.
* [google-email-audit-api ★4](https://github.com/ngs/go-google-email-audit-api) - Go client library for [Google G Suite Email Audit API](https://developers.google.com/admin-sdk/email-audit/).
* [gostorm ★97](https://github.com/jsgilmore/gostorm) - GoStorm is a Go library that implements the communications protocol required to write Storm spouts and Bolts in Go that communicate with the Storm shells.
* [govkbot ★11](https://github.com/nikepan/govkbot) - Simple Go [VK](https://vk.com) bot library.
* [hipchat ★105 ⏳1Y](https://github.com/andybons/hipchat) - This project implements a golang client library for the Hipchat API.
* [hipchat (xmpp) ★103](https://github.com/daneharrigan/hipchat) - A golang package to communicate with HipChat over XMPP.
* [Medium ★78](https://github.com/Medium/medium-sdk-go) - Golang SDK for Medium's OAuth2 API.
* [megos ★47](https://github.com/andygrunwald/megos) - Client library for accessing an [Apache Mesos](http://mesos.apache.org/) cluster.
* [micha ★4](https://github.com/onrik/micha) - Go Library for Telegram bot api.
* [minio-go ★356](https://github.com/minio/minio-go) - Minio Go Library for Amazon S3 compatible cloud storage.
* [mixpanel ★20](https://github.com/dukex/mixpanel) - Mixpanel is a library for tracking events and sending Mixpanel profile updates to Mixpanel from your go applications.
* [patreon-go ★2](https://github.com/mxpv/patreon-go) - Go library for Patreon API.
* [paypal](https://github.com/logpacker/paypalsdk) - Wrapper for PayPal payment API.
* [playlyfe ★0 ⏳1Y](https://github.com/playlyfe/playlyfe-go-sdk) - The Playlyfe Rest API Go SDK.
* [pushover ★28](https://github.com/gregdel/pushover) - Go wrapper for the Pushover API.
* [rrdaclient ★4 ⏳2Y](https://github.com/Omie/rrdaclient) - Go Library to access statdns.com API, which is in turn RRDA API. DNS Queries over HTTP.
* [shopify ★13 ⏳1Y](https://github.com/rapito/go-shopify) - Go Library to make CRUD request to the Shopify API.
* [slack ★1179](https://github.com/nlopes/slack) - Slack API in Go.
* [smite ★8 ⏳3Y](https://github.com/sergiotapia/smitego) - Go package to wraps access to the Smite game API.
* [spotify ★12 ⏳2Y](https://github.com/rapito/go-spotify) - Go Library to access Spotify WEB API.
* [steam ★8](https://github.com/sostronk/go-steam) - Go Library to interact with Steam game servers.
* [stripe ★583](https://github.com/stripe/stripe-go) - Go client for the Stripe API.
* [tbot ★112](https://github.com/yanzay/tbot) - Telegram bot server with API similar to net/http.
* [telebot ★319](https://github.com/tucnak/telebot) - Telegram bot framework written in Go.
* [telegram-bot-api](https://github.com/Syfaro/telegram-bot-api) - Simple and clean Telegram bot client.
* [textbelt](https://github.com/dietsche/textbelt) - Go client for the textbelt.com txt messaging API.
* [TheMovieDb ★10 ⏳1Y](https://github.com/jbrodriguez/go-tmdb) - Simple golang package to communicate with [themoviedb.org](https://themoviedb.org).
* [translate](https://github.com/poorny/translate) - Go online translation package.
* [Trello ★16](https://github.com/adlio/trello) - Go wrapper for the Trello API.
* [tumblr ★6](https://github.com/mattcunningham/gumblr) - Go wrapper for the Tumblr v2 API.
* [webhooks ★102](https://github.com/go-playground/webhooks) - Webhook receiver for GitHub and Bitbucket.
* [zooz ★1](https://github.com/gojuno/go-zooz) - Go client for the Zooz API.

## Utilities

*General utilities and tools to make your life easier.*

* [abutil ★31 ⏳2Y](https://github.com/bahlo/abutil) - Collection of often-used Golang helpers.
* [apm ★90](https://github.com/topfreegames/apm) - Process manager for Golang applications with an HTTP API.
* [boilr ★524](https://github.com/tmrts/boilr) - Blazingly fast CLI tool for creating projects from boilerplate templates.
* [circuitbreaker ★481](https://github.com/rubyist/circuitbreaker) - Circuit Breakers in Go.
* [clockwerk](http://github.com/onatm/clockwerk) - Go package to schedule periodic jobs using a simple, fluent syntax.
* [command ★6 ⏳1Y](https://github.com/txgruppi/command) - Command pattern for Go with thread safe serial and parallel dispatcher.
* [coop ★1193 ⏳1Y](https://github.com/rakyll/coop) - Cheat sheet for some of the common concurrent flows in Go.
* [copy-pasta ★20](https://github.com/jutkko/copy-pasta) - Universal multi-workstation clipboard that uses S3 like backend for the storage.
* [ctop ★5873](https://github.com/bcicen/ctop) - [Top-like](http://ctop.sh) interface (e.g. htop) for container metrics.
* [Death ★63](https://github.com/vrecan/death) - Managing go application shutdown with signals.
* [Deepcopier ★116](https://github.com/ulule/deepcopier) - Simple struct copying for Go.
* [delve ★6196](https://github.com/derekparker/delve) - Go debugger.
* [dlog ★6](https://github.com/kirillDanshin/dlog) - Compile-time controlled logger to make your release smaller without removing debug calls.
* [excelize](https://github.com/Luxurioust/excelize) - Golang library for reading and writing Microsoft Excel (XLSX) files.
* [fastlz ★6 ⏳2Y](https://github.com/digitalcrab/fastlz) - Wrap over [FastLz](http://fastlz.org/) (free, open-source, portable real-time compression library) for GoLang.
* [filetype ★157](https://github.com/h2non/filetype) - Small package to infer the file type checking the magic numbers signature.
* [filler ★8](https://github.com/yaronsumel/filler) - small utility to fill structs using "fill" tag.
* [fzf ★9839](https://github.com/junegunn/fzf) - Command-line fuzzy finder written in Go.
* [generate ★6](https://github.com/go-playground/generate) - runs go generate recursively on a specified path or environment variable and can filter by regex.
* [gentleman ★443](https://github.com/h2non/gentleman) - Full-featured plugin-driven HTTP client library.
* [git-time-metric ★359](https://github.com/git-time-metric/gtm) - Simple, seamless, lightweight time tracking for Git.
* [GJSON ★1630](https://github.com/tidwall/gjson) - Get a JSON value with one line of code.
* [go-astitodo ★25](https://github.com/asticode/go-astitodo) - Parse TODOs in your GO code.
* [go-bind-plugin ★147](https://github.com/wendigo/go-bind-plugin) - go:generate tool for wrapping symbols exported by golang plugins (1.8 only).
* [go-cron ★146 ⏳2Y](https://github.com/rk/go-cron) - Simple Cron library for go that can execute closures or functions at varying intervals, from once a second to once a year on a specific date and time. Primarily for web applications and long running daemons.
* [go-debug ★371](https://github.com/tj/go-debug) - Conditional debug logging for Golang libraries & applications.
* [go-dry ★189](https://github.com/ungerik/go-dry) - DRY (don't repeat yourself) package for Go.
* [go-funk ★260](https://github.com/thoas/go-funk) - Modern Go utility library which provides helpers (map, find, contains, filter, chunk, reverse, ...).
* [go-httpheader ★9](https://github.com/mozillazg/go-httpheader) - Go library for encoding structs into Header fields.
* [go-rate ★219 ⏳3Y](https://github.com/beefsack/go-rate) - Timed rate limiter for Go.
* [go-respond ★4](https://github.com/nicklaw5/go-respond) - Go package for handling common HTTP JSON responses.
* [go-sitemap-generator ★51](https://github.com/ikeikeikeike/go-sitemap-generator) - XML Sitemap generator written in Go.
* [go-torch ★2120](https://github.com/uber/go-torch) - Stochastic flame graph profiler for Go programs.
* [go-trigger ★95](https://github.com/sadlil/go-trigger) - Go-lang global event triggerer, Register Events with an id and trigger the event from anywhere from your project.
* [go-underscore ★909 ⏳2Y](https://github.com/tobyhede/go-underscore) - Useful collection of helpfully functional Go collection utilities.
* [goback ★30 ⏳2Y](https://github.com/carlescere/goback) - Go simple exponential backoff package.
* [godaemon ★315 ⏳2Y](https://github.com/VividCortex/godaemon) - Utility to write daemons.
* [godropbox ★3351](https://github.com/dropbox/godropbox) - Common libraries for writing Go services/applications from Dropbox.
* [gohper ★222](https://github.com/cosiner/gohper) - Various tools/modules help for development.
* [gojq ★77 ⏳1Y](https://github.com/elgs/gojq) - JSON query in Golang.
* [gojson ★1409](https://github.com/ChimeraCoder/gojson) - Automatically generate Go (golang) struct definitions from example JSON.
* [golarm ★23 ⏳2Y](https://github.com/msempere/golarm) - Fire alarms with system events.
* [golog ★28](https://github.com/mlimaloureiro/golog) - Easy and lightweight CLI tool to time track your tasks.
* [gopencils ★391](https://github.com/bndr/gopencils) - Small and simple package to easily consume REST APIs.
* [goplaceholder ★14 ⏳1Y](https://github.com/michiwend/goplaceholder) - a small golang lib to generate placeholder images.
* [goreleaser ★1629](https://github.com/goreleaser/goreleaser) - Deliver Go binaries as fast and easily as possible.
* [goreporter](https://github.com/wgliang/goreporter) - Golang tool that does static analysis, unit testing, code review and generate code quality report.
* [goreq ★599](https://github.com/franela/goreq) - Minimal and simple request library for Go language.
* [goreq ★51 ⏳1Y](https://github.com/smallnest/goreq) - Enhanced simplified HTTP client based on gorequest.
* [gorequest ★1256](https://github.com/parnurzeal/gorequest) - Simplified HTTP client with rich features for Go.
* [goseaweedfs ★1](https://github.com/linxGnu/goseaweedfs) - SeaweedFS client library with almost full features.
* [gotenv ★63](https://github.com/subosito/gotenv) - Load environment variables from `.env` or any `io.Reader` in Go.
* [goxlsxwriter ★7](https://github.com/fterrag/goxlsxwriter) - Golang bindings for libxlsxwriter for writing XLSX (Microsoft Excel) files.
* [gpath ★17](https://github.com/tenntenn/gpath) - Library to simplify access struct fields with Go's expression in reflection.
* [grequests ★909](https://github.com/levigross/grequests) - Elegant and simple `net/http` wrapper that follows Python's requests library.
* [gron ★468](https://github.com/roylee0704/gron) - Define time-based tasks using a simple Go API and Gron’s scheduler will run them accordingly.
* [htcat ★438 ⏳2Y](https://github.com/htcat/htcat) - Parallel and Pipelined HTTP GET Utility.
* [httpcontrol ★456 ⏳2Y](https://github.com/facebookgo/httpcontrol) - Package httpcontrol allows for HTTP transport level control around timeouts and retries.
* [hub ★11143](https://github.com/github/hub) - wrap git commands with additional functionality to interact with github from the terminal.
* [hystrix-go ★672](https://github.com/afex/hystrix-go) - Implements Hystrix patterns of programmer-defined fallbacks aka circuit breaker.
* [immortal ★409](https://github.com/immortal/immortal) - *nix cross-platform (OS agnostic) supervisor.
* [intrinsic ★8](https://github.com/mengzhuo/intrinsic) - Use x86 SIMD without writing any assembly code.
* [JobRunner ★384](https://github.com/bamzi/jobrunner) - Smart and featureful cron job scheduler with job queuing and live monitoring built in.
* [jsonapi-errors ★3](https://github.com/AmuzaTkts/jsonapi-errors) - Go bindings based on the JSON API errors reference.
* [jsonf ★45 ⏳1Y](https://github.com/miolini/jsonf) - Console tool for highlighted formatting and struct query fetching JSON.
* [jsongo ★69](https://github.com/ricardolonga/jsongo) - Fluent API to make it easier to create Json objects.
* [jsonhal ★4](https://github.com/RichardKnop/jsonhal) - Simple Go package to make custom structs marshal into HAL compatible JSON responses.
* [kazaam ★39](https://github.com/Qntfy/kazaam) - API for arbitrary transformation of JSON documents.
* [lrserver ★85](https://github.com/jaschaephraim/lrserver) - LiveReload server for Go.
* [mc ★549](https://github.com/minio/mc) - Minio Client provides minimal tools to work with Amazon S3 compatible cloud storage and filesystems.
* [mergo ★305](https://github.com/imdario/mergo) - Helper to merge structs and maps in Golang. Useful for configuration default values, avoiding messy if-statements.
* [minify ★1018](https://github.com/tdewolff/minify) - Fast minifiers for HTML, CSS, JS, XML, JSON and SVG file formats.
* [mmake ★1256](https://github.com/tj/mmake) - Modern Make.
* [moldova ★134](https://github.com/StabbyCutyou/moldova) - Utility for generating random data based on an input template.
* [mp ★21 ⏳1Y](https://github.com/sanbornm/mp) - Simple cli email parser. It currently takes stdin and outputs JSON.
* [mssqlx ★13](https://github.com/linxGnu/mssqlx) - HA client for master slave (or master master) database which integrates simple, lightweight round-robin balancer. Based on sqlx.
* [multitick ★48 ⏳1Y](https://github.com/VividCortex/multitick) - Multiplexor for aligned tickers.
* [netbug ★51 ⏳1Y](https://github.com/e-dard/netbug) - Easy remote profiling of your services.
* [ngrok ★10970](https://github.com/inconshreveable/ngrok) - Introspected tunnels to localhost.
* [okrun ★11 ⏳2Y](https://github.com/xta/okrun) - go run error steamroller.
* [onecache ★54](https://github.com/adelowo/onecache) - Caching library with support for multiple backend stores (Redis, Memcached, filesystem etc).
* [panicparse ★1447](https://github.com/maruel/panicparse) - Groups similar goroutines and colorizes stack dump.
* [peco ★4030](https://github.com/peco/peco) - Simplistic interactive filtering tool.
* [pester ★186](https://github.com/sethgrid/pester) - Go HTTP client calls with retries, backoff, and concurrency.
* [pm ★49 ⏳1Y](https://github.com/VividCortex/pm) - Process (i.e. goroutine) manager with an HTTP API.
* [profile ★628](https://github.com/pkg/profile) - Simple profiling support package for Go.
* [rclient ★18](https://github.com/zpatrick/rclient) - Readable, flexible, simple-to-use client for REST APIs.
* [realize ★1533](https://github.com/tockins/realize) - Go build system with file watchers and live reload. Run, build and watch file changes with custom paths.
* [request ★213](https://github.com/mozillazg/request) - Go HTTP Requests for Humans™.
* [rerate ★7](https://github.com/abo/rerate) - Redis-based rate counter and rate limiter for Go.
* [rerun ★128](https://github.com/ivpusic/rerun) - Recompiling and rerunning go apps when source changes.
* [resty ★555](https://github.com/go-resty/resty) - Simple HTTP and REST client for Go inspired by Ruby rest-client.
* [retry ★26](https://github.com/kamilsk/retry) - Functional mechanism based on context to perform actions repetitively until successful.
* [robustly ★118](https://github.com/VividCortex/robustly) - Runs functions resiliently, catching and restarting panics.
* [scheduler ★161](https://github.com/carlescere/scheduler) - Cronjobs scheduling made easy.
* [sling ★543](https://github.com/dghubble/sling) - Go HTTP requests builder for API clients.
* [spinner ★355](https://github.com/briandowns/spinner) - Go package to easily provide a terminal spinner with options.
* [sqlx ★3170](https://github.com/jmoiron/sqlx) - provides a set of extensions on top of the excellent built-in database/sql package.
* [Storm ★613](https://github.com/asdine/storm) - Simple and powerful toolkit for BoltDB.
* [Task ★306](https://github.com/go-task/task) - simple "Make" alternative.
* [toolbox ★6](https://github.com/viant/toolbox) - Slice, map, multimap, struct, function, data conversion utilities. Service router, macro evaluator, tokenizer.
* [ugo ★13 ⏳1Y](https://github.com/alxrm/ugo) - ugo is slice toolbox with concise syntax for Go.
* [UNIS ★62](https://github.com/esemplastic/unis) - Common Architecture™ for String Utilities in Go.
* [usql ★2046](https://github.com/knq/usql) - usql is a universal command-line interface for SQL databases.
* [util ★24](https://github.com/shomali11/util) - Collection of useful utility functions. (strings, concurrency, manipulations, ...).
* [wuzz ★6591](https://github.com/asciimoo/wuzz) - Interactive cli tool for HTTP inspection.
* [xferspdy ★41 ⏳1Y](https://github.com/monmohan/xferspdy) - Xferspdy provides binary diff and patch library in golang.
* [xlsx ★1847](https://github.com/tealeg/xlsx) - Library to simplify reading the XML format used by recent version of Microsoft Excel in Go programs.

## Validation

*Libraries for validation.*

* [govalidator ★1990](https://github.com/asaskevich/govalidator) - Validators and sanitizers for strings, numerics, slices and structs.
* [ozzo-validation ★407](https://github.com/go-ozzo/ozzo-validation) - Supports validation of various data types (structs, strings, maps, slices, etc.) with configurable and extensible validation rules specified in usual code constructs instead of struct tags.
* [validate ★14](https://github.com/markbates/validate) - This package provides a framework for writing validations for Go applications.
* [validator ★1101](https://github.com/go-playground/validator) - Go Struct and Field validation, including Cross Field, Cross Struct, Map, Slice and Array diving.

## Version Control

*Libraries for version control.*

* [gh ★48](https://github.com/rjeczalik/gh) - Scriptable server and net/http middleware for GitHub Webhooks.
* [git2go ★1022](https://github.com/libgit2/git2go) - Go bindings for libgit2.
* [go-vcs ★50 ⏳1Y](https://github.com/sourcegraph/go-vcs) - manipulate and inspect VCS repositories in Go.
* [hgo ★9 ⏳2Y](https://github.com/beyang/hgo) - Hgo is a collection of Go packages providing read-access to local Mercurial repositories.

## Video

*Libraries for manipulating video.*

* [gmf ★296](https://github.com/3d0c/gmf) - Go bindings for FFmpeg av\* libraries.
* [go-astisub ★24](https://github.com/asticode/go-astisub) - Manipulate subtitles in GO (.srt, .stl, .ttml, .webvtt, .ssa/.ass, teletext, .smi, etc.).
* [goav ★341](https://github.com/giorgisio/goav) - Comphrensive Go bindings for FFmpeg.
* [gst ★131 ⏳1Y](https://github.com/ziutek/gst) - Go bindings for GStreamer.
* [libgosubs ★1](https://github.com/wargarblgarbl/libgosubs) - Subtitle format support for go. Supports .srt, .ttml, and .ass.
* [v4l ★11](https://github.com/korandiz/v4l) - Video capture library for Linux, written in Go.

## Web Frameworks

*Full stack web frameworks.*

* [aah](https://aahframework.org) - Scalable, performant, rapid development Web framework for Go.
* [Air ★38](https://github.com/sheng/air) - Ideal RESTful web framework for Go.
* [Beego ★11966](https://github.com/astaxie/beego) - beego is an open-source, high-performance web framework for the Go programming language.
* [Buffalo](http://gobuffalo.io) - Bringing the productivity of Rails to Go!
* [Echo ★8020](https://github.com/labstack/echo) - High performance, minimalist Go web framework.
* [Fireball ★24](https://github.com/zpatrick/fireball) - More "natural" feeling web framework.
* [Florest ★30](https://github.com/jabong/florest-core) - High-performance workflow based REST API framework.
* [Gem ★142](https://github.com/go-gem/gem) - Simple and fast web framework, friendly to REST API.
* [Gin ★11287](https://github.com/gin-gonic/gin) - Gin is a web framework written in Go! It features a martini-like API with much better performance, up to 40 times faster. If you need performance and good productivity.
* [Gizmo ★1868](https://github.com/NYTimes/gizmo) - Microservice toolkit used by the New York Times.
* [go-json-rest ★2866](https://github.com/ant0ine/go-json-rest) - Quick and easy way to setup a RESTful JSON API.
* [go-relax ★142](https://github.com/codehack/go-relax) - Framework of pluggable components to build RESTful API's.
* [go-rest ★104](https://github.com/ungerik/go-rest) - Small and evil REST framework for Go.
* [goa](https://github.com/raphael/goa) - Framework for developing microservices based on the design of Ruby's Praxis.
* [Goat ★137](https://github.com/bahlo/goat) - Minimalistic REST API server in Go.
* [Golf ★199](https://github.com/dinever/golf) - Golf is a fast, simple and lightweight micro-web framework for Go. It comes with powerful features and has no dependencies other than the Go Standard Library.
* [Gondola ★305](https://github.com/rainycape/gondola) - The web framework for writing faster sites, faster.
* [gongular ★378](https://github.com/mustafaakin/gongular) - Fast Go web framework with input mapping/validation and (DI) Dependency Injection.
* [Macaron ★1981](https://github.com/go-macaron/macaron) - Macaron is a high productive and modular design web framework in Go.
* [mango ★308 ⏳1Y](https://github.com/paulbellamy/mango) - Mango is a modular web-application framework for Go, inspired by Rack, and PEP333.
* [Microservice ★34](https://github.com/claygod/microservice) - The framework for the creation of microservices, written in Golang.
* [neo ★312](https://github.com/ivpusic/neo) - Neo is minimal and fast Go Web Framework with extremely simple API.
* [Resoursea ★28 ⏳2Y](https://github.com/resoursea/api) - REST framework for quickly writing resource based services.
* [REST Layer](http://rest-layer.io) - Framework to build REST/GraphQL API on top of databases with mostly configuration over code.
* [Revel ★8650](https://github.com/revel/revel) - High-productivity web framework for the Go language.
* [rex ★13](https://github.com/goanywhere/rex) - Rex is a library for modular development built upon gorilla/mux, fully compatible with `net/http`.
* [sawsij ★1 ⏳1Y](https://github.com/jaybill/sawsij) - lightweight, open-source web framework for building high-performance, data-driven web applications.
* [tango ★614](https://github.com/lunny/tango) - Micro & pluggable web framework for Go.
* [tigertonic ★946](https://github.com/rcrowley/go-tigertonic) - Go framework for building JSON web services inspired by Dropwizard.
* [traffic ★513 ⏳1Y](https://github.com/pilu/traffic) - Sinatra inspired regexp/pattern mux and web framework for Go.
* [utron ★1906](https://github.com/gernest/utron) - Lightweight MVC framework for Go(Golang).
* [violetear ★71](https://github.com/nbari/violetear) - Go HTTP router.
* [YARF ★38](https://github.com/yarf-framework/yarf) - Fast micro-framework designed to build REST APIs and web services in a fast and simple way.
* [Zerver ★139 ⏳1Y](https://github.com/cosiner/zerver) - Zerver is an expressive, modular, feature completed RESTful framework.

## Windows

* [d3d9 ★54](https://github.com/gonutz/d3d9) - Go bindings for Direct3D9.
* [go-ole ★315](https://github.com/go-ole/go-ole) - Win32 OLE implementation for golang.

## XML

*Libraries and tools for manipulating XML.*

* [go-pkg-xmlx ★122 ⏳1Y](https://github.com/jteeuwen/go-pkg-xmlx) - Extension to the standard Go XML package. Maintains a node tree that allows forward/backwards browsing and exposes some simple single/multi-node search functions.
* [XML-Comp ★6](https://github.com/xml-comp/xml-comp) - Simple command line XML comparer that generates diffs of folders, files and tags.
* [xmlwriter ★0](https://github.com/shabbyrobe/xmlwriter) - Procedural XML generation API based on libxml2's xmlwriter module.
* [xpath ★23](https://github.com/antchfx/xpath) - XPath package for Go.
* [xquery ★68](https://github.com/antchfx/xquery) - XQuery lets you extract data from HTML/XML documents using XPath expression.

### Middlewares

#### Actual middlewares

* [CORS ★556](https://github.com/rs/cors) - Easily add CORS capabilities to your API.
* [formjson ★25 ⏳1Y](https://github.com/rs/formjson) - Transparently handle JSON input as a standard form POST.
* [Limiter ★263](https://github.com/ulule/limiter) - Dead simple rate limit middleware for Go.
* [Tollbooth ★578](https://github.com/didip/tollbooth) - Rate limit HTTP request handler.
* [XFF ★60](https://github.com/sebest/xff) - Handle `X-Forwarded-For` header and friends.

#### Libraries for creating HTTP middlewares

* [alice ★1313](https://github.com/justinas/alice) - Painless middleware chaining for Go.
* [catena ★6](https://github.com/codemodus/catena) - http.Handler wrapper catenation (same API as "chain").
* [chain ★63](https://github.com/codemodus/chain) - Handler wrapper chaining with scoped data (net/context-based "middleware").
* [go-wrap ★52 ⏳2Y](https://github.com/go-on/wrap) - Small middlewares package for net/http.
* [gores ★57](https://github.com/alioygur/gores) - Go package that handles HTML, JSON, XML and etc. responses. Useful for RESTful APIs.
* [interpose ★275](https://github.com/carbocation/interpose) - Minimalist net/http middleware for golang.
* [muxchain ★200 ⏳2Y](https://github.com/stephens2424/muxchain) - Lightweight middleware for net/http.
* [negroni ★4852](https://github.com/urfave/negroni) - Idiomatic HTTP middleware for Golang.
* [render ★922](https://github.com/unrolled/render) - Go package for easily rendering JSON, XML, and HTML template responses.
* [rye ★57](https://github.com/InVisionApp/rye) - Tiny Go middleware library (with canned Middlewares) that supports JWT, CORS, Statsd, and Go 1.7 context.
* [stats ★429 ⏳1Y](https://github.com/thoas/stats) - Go middleware that stores various information about your web application.
* [Volatile ★80 ⏳1Y](https://github.com/volatile/core) - Minimalist middleware stack promoting flexibility, good practices and clean code.

### Routers

* [alien ★79](https://github.com/gernest/alien) - Lightweight and fast http router from outer space.
* [Bone ★1048](https://github.com/go-zoo/bone) - Lightning Fast HTTP Multiplexer.
* [Bxog ★74](https://github.com/claygod/Bxog) - Simple and fast HTTP router for Go. It works with routes of varying difficulty, length and nesting. And he knows how to create a URL from the received parameters.
* [chi ★2335](https://github.com/go-chi/chi) - Small, fast and expressive HTTP router built on net/context.
* [fasthttprouter ★338](https://github.com/buaazp/fasthttprouter) - High performance router forked from `httprouter`. The first router fit for `fasthttp`.
* [gocraft/web ★1227](https://github.com/gocraft/web) - Mux and middleware package in Go.
* [Goji ★501](https://github.com/goji/goji) - Goji is a minimalistic and flexible HTTP request multiplexer with support for `net/context`.
* [GoRouter ★15](https://github.com/vardius/gorouter) - GoRouter is a Server/API micro framwework, HTTP request router, multiplexer, mux that provides request router with middleware supporting `net/context`.
* [gowww/router ★125](https://github.com/gowww/router) - Lightning fast HTTP router fully compatible with the net/http.Handler interface.
* [httprouter ★5396](https://github.com/julienschmidt/httprouter) - High performance router. Use this and the standard http handlers to form a very high performance web framework.
* [httptreemux ★254](https://github.com/dimfeld/httptreemux) - High-speed, flexible tree-based HTTP router for Go. Inspiration from httprouter.
* [lars ★330](https://github.com/go-playground/lars) - Is a lightweight, fast and extensible zero allocation HTTP router for Go used to create customizable frameworks.
* [medeina ★17 ⏳2Y](https://github.com/imdario/medeina) - Medeina is a HTTP routing tree based on HttpRouter, inspired by Roda and Cuba.
* [mux ★4328](https://github.com/gorilla/mux) - Powerful URL router and dispatcher for golang.
* [ozzo-routing ★203](https://github.com/go-ozzo/ozzo-routing) - An extremely fast Go (golang) HTTP router that supports regular expression route matching. Comes with full support for building RESTful APIs.
* [pat ★1053](https://github.com/bmizerany/pat) - Sinatra style pattern muxer for Go’s net/http library, by the author of Sinatra.
* [pure ★36](https://github.com/go-playground/pure) - Is a lightweight HTTP router that sticks to the std "net/http" implementation.
* [Siesta ★343](https://github.com/VividCortex/siesta) - Composable framework to write middleware and handlers.
* [vestigo ★165](https://github.com/husobee/vestigo) - Performant, stand-alone, HTTP compliant URL Router for go web applications.
* [xmux ★72](https://github.com/rs/xmux) - High performance muxer based on `httprouter` with `net/context` support.
* [zeus ★108](https://github.com/daryl/zeus) - Very simple and fast HTTP router for Go.

# Tools

*Go software and plugins.*

## Code Analysis

* [apicompat ★91](https://github.com/bradleyfalzon/apicompat) - Checks recent changes to a Go project for backwards incompatible changes.
* [dupl ★87](https://github.com/mibk/dupl) - Tool for code clone detection.
* [errcheck ★859](https://github.com/kisielk/errcheck) - Errcheck is a program for checking for unchecked errors in Go programs.
* [gcvis ★709 ⏳1Y](https://github.com/davecheney/gcvis) - Visualise Go program GC trace data in real time.
* [Go Metalinter ★1828](https://github.com/alecthomas/gometalinter) - Metalinter is a tool to automatically apply all static analysis tool and report their output in normalized form.
* [go-checkstyle ★46 ⏳1Y](https://github.com/qiniu/checkstyle) - checkstyle is a style check tool like java checkstyle. This tool inspired by java checkstyle, golint. The style refered to some points in Go Code Review Comments.
* [go-cleanarch ★162](https://github.com/roblaszczak/go-cleanarch) - go-cleanarch was created to validate Clean Architecture rules, like a The Dependency Rule and interaction between packages in your Go projects.
* [go-outdated ★34 ⏳1Y](https://github.com/firstrow/go-outdated) - Console application that displays outdated packages.
* [goast-viewer ★175](https://github.com/yuroyoro/goast-viewer) - Web based Golang AST visualizer.
* [GoCover.io](http://gocover.io/) - GoCover.io offers the code coverage of any golang package as a service.
* [goimports](https://godoc.org/golang.org/x/tools/cmd/goimports) - Tool to fix (add, remove) your Go imports automatically.
* [GoLint ★1946](https://github.com/golang/lint) - Golint is a linter for Go source code.
* [Golint online](http://go-lint.appspot.com/) - Lints online Go source files on GitHub, Bitbucket and Google Project Hosting using the golint package.
* [goreturns](https://sourcegraph.com/github.com/sqs/goreturns) - Adds zero-value return statements to match the func return types.
* [gosimple](https://github.com/dominikh/go-tools/tree/master/cmd/gosimple) - gosimple is a linter for Go source code that specialises on simplifying code.
* [gostatus ★206](https://github.com/shurcooL/gostatus) - Command line tool, shows the status of repositories that contain Go packages.
* [interfacer ★655](https://github.com/mvdan/interfacer) - Linter that suggests interface types.
* [lint ★53](https://github.com/surullabs/lint) - Run linters as part of go test.
* [staticcheck](https://github.com/dominikh/go-tools/tree/master/cmd/staticcheck) - staticcheck is `go vet` on steroids, applying a ton of static analysis checks you might be used to from tools like ReSharper for C#.
* [unconvert ★177 ⏳1Y](https://github.com/mdempsky/unconvert) - Remove unnecessary type conversions from Go source.
* [unused](https://github.com/dominikh/go-tools/tree/master/cmd/unused) - unused checks Go code for unused constants, variables, functions and types.
* [validate ★61 ⏳1Y](https://github.com/mccoyst/validate) - Automatically validates struct fields with tags.

## Editor Plugins

* [Go plugin for JetBrains IDEs](https://plugins.jetbrains.com/plugin/9568-go) - Go plugin for JetBrains IDEs.
* [go-lang-idea-plugin ★4365](https://github.com/go-lang-plugin-org/go-lang-idea-plugin) (deprecated) - The previous Go plugin for IntelliJ (JetBrains) IDEA, now replaced by the official plugin (above).
* [go-mode ★637](https://github.com/dominikh/go-mode.el) - Go mode for GNU/Emacs.
* [go-plus ★1277](https://github.com/joefitzgerald/go-plus) - Go (Golang) Package For Atom That Adds Autocomplete, Formatting, Syntax Checking, Linting and Vetting.
* [Goclipse ★707](https://github.com/GoClipse/goclipse) - Eclipse plugin for Go.
* [gocode ★3813](https://github.com/nsf/gocode) - Autocompletion daemon for the Go programming language.
* [GoSublime ★2673](https://github.com/DisposaBoy/GoSublime) - Golang plugin collection for the text editor SublimeText 2 providing code completion and other IDE-like features.
* [velour ★14 ⏳1Y](https://github.com/velour/velour) - IRC client for the acme editor.
* [vim-compiler-go ★73 ⏳1Y](https://github.com/rjohnsondev/vim-compiler-go) - Vim plugin to highlight syntax errors on save.
* [vim-go ★7012](https://github.com/fatih/vim-go) - Go development plugin for Vim.
* [vscode-go ★2729](https://github.com/Microsoft/vscode-go) - Extension for Visual Studio Code (VS Code) which provides support for the Go language.
* [Watch ★136 ⏳1Y](https://github.com/eaburns/Watch) - Runs a command in an acme win on file changes.

## Go Tools

* [colorgo ★83](https://github.com/songgao/colorgo) - Wrapper around `go` command for colorized `go build` output.
* [depth ★140](https://github.com/KyleBanks/depth) - Visualize dependency trees of any package by analyzing imports.
* [gb](https://getgb.io/) - An easy to use project based build tool for the Go programming language.
* [go-callvis ★863](https://github.com/TrueFurby/go-callvis) - Visualize call graph of your Go program using dot format.
* [go-pkg-complete ★30](https://github.com/skelterjohn/go-pkg-complete) - Bash completion for go and wgo.
* [go-swagger ★1361](https://github.com/go-swagger/go-swagger) - Swagger 2.0 implementation for go. Swagger is a simple yet powerful representation of your RESTful API.
* [OctoLinker ★2266](https://github.com/OctoLinker/browser-extension) - Navigate through go files efficiently with the OctoLinker browser extension for GitHub.
* [rts ★136](https://github.com/galeone/rts) - RTS: response to struct. Generates Go structs from server responses.

## Software Packages

*Software written in Go.*

### DevOps Tools

* [aptly ★1386](https://github.com/smira/aptly) - aptly is a Debian repository management tool.
* [aurora](https://github.com/Luxurioust/aurora) - Cross-platform web-based Beanstalkd queue server console.
* [awsenv ★11](https://github.com/soniah/awsenv) - Small binary that loads Amazon (AWS) environment variables for a profile.
* [Banshee ★826](https://github.com/eleme/banshee) - Anomalies detection system for periodic metrics.
* [bombardier ★586](https://github.com/codesenberg/bombardier) - Fast cross-platform HTTP benchmarking tool.
* [bosun ★2331](https://github.com/bosun-monitor/bosun) - Time Series Alerting Framework.
* [dogo ★143](https://github.com/liudng/dogo) - Monitoring changes in the source file and automatically compile and run (restart).
* [drone-jenkins ★7](https://github.com/appleboy/drone-jenkins) - Trigger downstream Jenkins jobs using a binary, docker or Drone CI.
* [drone-scp ★10](https://github.com/appleboy/drone-scp) - Copy files and artifacts via SSH using a binary, docker or Drone CI.
* [Dropship ★35 ⏳1Y](https://github.com/chrismckenzie/dropship) - Tool for deploying code via cdn.
* [easyssh-proxy ★29](https://github.com/appleboy/easyssh-proxy) - Golang package for easy remote execution through SSH and SCP downloading via `ProxyCommand`.
* [Gitea ★3381](https://github.com/go-gitea/gitea) - Fork of Gogs, entirely community driven.
* [Go Metrics ★1648](https://github.com/rcrowley/go-metrics) - Go port of Coda Hale's Metrics library: https://github.com/codahale/metrics.
* [go-selfupdate ★508](https://github.com/sanbornm/go-selfupdate) - Enable your Go applications to self update.
* [gobrew ★166](https://github.com/cryptojuice/gobrew) - gobrew lets you easily switch between multiple versions of go.
* [godbg ★207 ⏳1Y](https://github.com/sirnewton01/godbg) - Web-based gdb front-end application.
* [Gogs](https://gogs.io/) - A Self Hosted Git Service in the Go Programming Language.
* [gonative ★267 ⏳1Y](https://github.com/inconshreveable/gonative) - Tool which creates a build of Go that can cross compile to all platforms while still using the Cgo-enabled versions of the stdlib packages.
* [govvv](https://github.com/ahmetalpbalkan/govvv) - “go build” wrapper to easily add version information into Go binaries.
* [gox ★2268](https://github.com/mitchellh/gox) - Dead simple, no frills Go cross compile tool.
* [goxc ★1448](https://github.com/laher/goxc) - build tool for Go, with a focus on cross-compiling and packaging.
* [grapes ★46](https://github.com/yaronsumel/grapes) - Lightweight tool designed to distribute commands over ssh with ease.
* [GVM ★2953](https://github.com/moovweb/gvm) - GVM provides an interface to manage Go versions.
* [Hey ★1828](https://github.com/rakyll/hey) - Hey is a tiny program that sends some load to a web application.
* [kala ★1047](https://github.com/ajvb/kala) - Simplistic, modern, and performant job scheduler.
* [kubernetes ★25979](https://github.com/kubernetes/kubernetes) - Container Cluster Manager from Google.
* [Moby ★45037](https://github.com/moby/moby) - Collaborative project for the container ecosystem to assemble container-based systems.
* [Mora ★208](https://github.com/emicklei/mora) - REST server for accessing MongoDB documents and meta data.
* [ostent ★145](https://github.com/ostrost/ostent) - collects and displays system metrics and optionally relays to Graphite and/or InfluxDB.
* [Packer](https://github.com/mitchellh/packer) - Packer is a tool for creating identical machine images for multiple platforms from a single source configuration.
* [Pewpew ★112](https://github.com/bengadbois/pewpew) - Flexible HTTP command line stress tester.
* [Rodent ★31](https://github.com/alouche/rodent) - Rodent helps you manage Go versions, projects and track dependencies.
* [s3gof3r ★839](https://github.com/rlmcpherson/s3gof3r) - Small utility/library optimized for high speed transfer of large objects into and out of Amazon S3.
* [Scaleway-cli ★336](https://github.com/scaleway/scaleway-cli) - Manage BareMetal Servers from Command Line (as easily as with Docker).
* [sg ★1](https://github.com/ChristopherRabotin/sg) - Benchmarks a set of HTTP endpoints (like ab), with possibility to use the reponse code and data between each call for specific server stress based on its previous response.
* [StatusOK ★785](https://github.com/sanathp/statusok) - Monitor your Website and REST APIs.Get Notified through Slack, E-mail when your server is down or response time is more than expected.
* [Vegeta ★6145](https://github.com/tsenart/vegeta) - HTTP load testing tool and library. It's over 9000!
* [webhook ★1876](https://github.com/adnanh/webhook) - Tool which allows user to create HTTP endpoints (hooks) that execute commands on the server.
* [Wide](https://wide.b3log.org/login) - Web-based IDE for Teams using Golang.
* [winrm-cli ★22](https://github.com/masterzen/winrm-cli) - Cli tool to remotely execute commands on Windows machines.

### Other Software
* [borg](https://github.com/crufter/borg) - Terminal based search engine for bash snippets.
* [boxed ★60 ⏳1Y](https://github.com/tejo/boxed) - Dropbox based blog engine.
* [Cherry ★129](https://github.com/rafael-santiago/cherry) - Tiny webchat server in Go.
* [Circuit ★1547](https://github.com/gocircuit/circuit) - Circuit is a programmable platform-as-a-service (PaaS) and/or Infrastructure-as-a-Service (IaaS), for management, discovery, synchronization and orchestration of services and hosts comprising cloud applications.
* [Comcast ★4842](https://github.com/tylertreat/Comcast) - Simulate bad network connections.
* [confd ★4074](https://github.com/kelseyhightower/confd) - Manage local application configuration files using templates and data from etcd or consul.
* [DDNS ★26](https://github.com/skibish/ddns) - Personal DDNS client with Digital Ocean Networking DNS as backend.
* [Docker](http://www.docker.com/) - Open platform for distributed applications for developers and sysadmins.
* [Documize ★190](https://github.com/documize/community) - Modern wiki software that integrates data from SaaS tools.
* [fleet ★2396](https://github.com/coreos/fleet) - Distributed init System.
* [Go Package Store ★763](https://github.com/shurcooL/Go-Package-Store#go-package-store-) - App that displays updates for the Go packages in your GOPATH.
* [gocc ★119](https://github.com/goccmack/gocc) - Gocc is a compiler kit for Go written in Go.
* [GoDocTooltip ★10 ⏳1Y](https://github.com/diankong/GoDocTooltip) - Chrome extension for Go Doc sites, which shows function description as tooltip at funciton list.
* [Gogland](https://jetbrains.com/go) - Full featured cross-platform Go IDE.
* [Gor](https://github.com/buger/gor) - Http traffic replication tool, for replaying traffic from production to stage/dev environments in real-time.
* [hugo](http://gohugo.io/) - Fast and Modern Static Website Engine.
* [ipe ★197](https://github.com/dimiro1/ipe) - Open source Pusher server implementation compatible with Pusher client libraries written in GO.
* [JayDiff ★7](https://github.com/yazgazan/jaydiff) - JSON diff utility written in Go.
* [Juju](https://jujucharms.com/) - Cloud-agnostic service deployment and orchestration - supports EC2, Azure, Openstack, MAAS and more.
* [Leaps ★500](https://github.com/jeffail/leaps) - Pair programming service using Operational Transforms.
* [limetext](http://limetext.org/) - Lime Text is a powerful and elegant text editor primarily developed in Go that aims to be a Free and open-source software successor to Sublime Text.
* [LiteIDE ★3876](https://github.com/visualfc/liteide) - LiteIDE is a simple, open source, cross-platform Go IDE.
* [mockingjay ★329](https://github.com/quii/mockingjay-server) - Fake HTTP servers and consumer driven contracts from one configuration file. You can also make the server randomly misbehave to help do more realistic performance tests.
* [myLG ★1823](https://github.com/mehrdadrad/mylg) - Command Line Network Diagnostic tool written in Go.
* [naclpipe ★11](https://github.com/unix4fun/naclpipe) - Simple NaCL EC25519 based crypto pipe tool written in Go.
* [nes ★2781](https://github.com/fogleman/nes) - Nintendo Entertainment System (NES) emulator written in Go.
* [orange-cat ★153 ⏳1Y](https://github.com/noraesae/orange-cat) - Markdown previewer written in Go.
* [Orbit ★41](https://github.com/gulien/orbit) - A simple tool for running commands and generating files from templates.
* [peg ★418](https://github.com/pointlander/peg) - Peg, Parsing Expression Grammar, is an implementation of a Packrat parser generator.
* [Postman ★682](https://github.com/zachlatta/postman) - Command-line utility for batch-sending email.
* [restic ★2216](https://github.com/restic/restic) - De-duplicating backup program.
* [rkt](https://github.com/coreos/rkt) - App Container runtime that integrates with init systems, is compatible with other container formats like Docker, and supports alternative execution engines like KVM.
* [Seaweed File System ★4541](https://github.com/chrislusf/seaweedfs) - Fast, Simple and Scalable Distributed File System with O(1) disk seek.
* [shell2http ★124](https://github.com/msoap/shell2http) - Executing shell commands via http server (for prototyping or remote control).
* [snap ★1551](https://github.com/intelsdi-x/snap) - Powerful telemetry framework.
* [Stack Up ★1502](https://github.com/pressly/sup) - Stack Up, a super simple deployment tool - just Unix - think of it like 'make' for a network of servers.
* [syncthing](https://syncthing.net/) - Open, decentralized file synchronization tool and protocol.
* [Tenyks ★163](https://github.com/kyleterry/tenyks) - Service oriented IRC bot using Redis and JSON for messaging.
* [toto ★18](https://github.com/blogcin/ToTo) - Simple proxy server written in Go language, can be used together with browser.
* [toxiproxy ★2052](https://github.com/shopify/toxiproxy) - Proxy to simulate network and system conditions for automated tests.
* [tsuru](https://tsuru.io/) - Extensible and open source Platform as a Service software.
* [vFlow ★222](https://github.com/VerizonDigital/vflow) - High-performance, scalable and reliable IPFIX, sFlow and Netflow collector.
* [websysd](https://github.com/ian-kent/websysd) - Web based process manager (like Marathon or Upstart).
* [wellington ★245](https://github.com/wellington/wellington) - Sass project management tool, extends the language with sprite functions (like Compass).

# Resources

*Where to discover new Go libraries.*

## Benchmarks

* [autobench ★82 ⏳3Y](https://github.com/davecheney/autobench) - Framework to compare the performance between different Go versions.
* [go-benchmark-app ★7](https://github.com/mrLSD/go-benchmark-app) - Powerful HTTP-benchmark tool mixed with Аb, Wrk, Siege tools. Gathering statistics and various parameters for benchmarks and comparison results.
* [go-benchmarks ★72 ⏳1Y](https://github.com/tylertreat/go-benchmarks) - Few miscellaneous Go microbenchmarks. Compare some language features to alternative approaches.
* [go-http-routing-benchmark ★931](https://github.com/julienschmidt/go-http-routing-benchmark) - Go HTTP request router benchmark and comparison.
* [go-type-assertion-benchmark ★4 ⏳2Y](https://github.com/hgfischer/go-type-assertion-benchmark) - Naive performance test of two ways to do type assertion in Go.
* [go-web-framework-benchmark ★489](https://github.com/smallnest/go-web-framework-benchmark) - Go web framework benchmark.
* [go_serialization_benchmarks ★540](https://github.com/alecthomas/go_serialization_benchmarks) - Benchmarks of Go serialization methods.
* [gocostmodel](https://github.com/PuerkitoBio/gocostmodel) - Benchmarks of common basic operations for the Go language.
* [golang-micro-benchmarks ★11 ⏳1Y](https://github.com/amscanne/golang-micro-benchmarks) - Tiny collection of Go micro benchmarks. The intent is to compare some language features to others.
* [golang-sql-benchmark ★31](https://github.com/tyler-smith/golang-sql-benchmark) - Collection of benchmarks for popular Go database/SQL utilities.
* [gospeed ★65 ⏳1Y](https://github.com/feyeleanor/GoSpeed) - Go micro-benchmarks for calculating the speed of language constructs.
* [kvbench ★11 ⏳3Y](https://github.com/jimrobinson/kvbench) - Key/Value database benchmark.
* [skynet ★772 ⏳1Y](https://github.com/atemerev/skynet) - Skynet 1M threads microbenchmark.
* [speedtest-resize ★109](https://github.com/fawick/speedtest-resize) - Compare various Image resize algorithms for the Go language.

## Conferences

* [Capital Go](http://www.capitalgolang.com) - Washington, D.C., USA
* [dotGo](http://www.dotgo.eu) - Paris, France
* [GoCon](http://gocon.connpass.com/) - Tokyo, Japan
* [GolangUK](http://golanguk.com/) - London, UK
* [GopherChina](http://gopherchina.org) - Shanghai, China
* [GopherCon](http://www.gophercon.com/) - Denver, USA
* [GopherCon Brazil](https://gopherconbr.org) - Florianópolis, BR
* [GopherCon Dubai](http://www.gophercon.ae/) - Dubai, UAE
* [GopherCon India](http://www.gophercon.in/) - Pune, India
* [GopherCon Singapore](https://gophercon.sg) - Mapletree Business City, Singapore
* [GothamGo](http://gothamgo.com/) - New York City, USA

## E-Books

* [A Go Developer's Notebook](https://leanpub.com/GoNotebook/read)
* [An Introduction to Programming in Go](http://www.golang-book.com/)
* [Build Web Application with Golang](https://www.gitbook.com/book/astaxie/build-web-application-with-golang/details)
* [Building Web Apps With Go](https://www.gitbook.com/book/codegangsta/building-web-apps-with-go/details)
* [Go Bootcamp](http://golangbootcamp.com)
* [GoBooks ★3814](https://github.com/dariubs/GoBooks) - A curated list of Go books.
* [Learning Go](https://www.miek.nl/downloads/Go/Learning-Go-latest.pdf)
* [Network Programming With Go](https://jan.newmarch.name/go/)
* [The Go Programming Language](http://www.gopl.io/)
* [Web Application with Go the Anti-Textbook ★1749](https://github.com/thewhitetulip/web-dev-golang-anti-textbook)

## Twitter

* [@golang](https://twitter.com/golang)
* [@golang_news](https://twitter.com/golang_news)
* [@golangflow](https://twitter.com/golangflow)
* [@golangweekly](https://twitter.com/golangweekly)

## Websites

* [Awesome Go @LibHunt](https://go.libhunt.com) - Your go-to Go Toolbox.
* [Awesome Remote Job ★9692](https://github.com/lukasz-madon/awesome-remote-job) - Curated list of awesome remote jobs. A lot of them is looking for Go hackers.
* [awesome-awesomeness ★19452](https://github.com/bayandin/awesome-awesomeness) - List of other amazingly awesome lists.
* [Flipboard - Go Magazine](https://flipboard.com/section/the-golang-magazine-bVP7nS) - Collection of Go articles and tutorials.
* [Go Blog](http://blog.golang.org) - The official Go blog.
* [Go Challenge](http://golang-challenge.org/) - Learn Go by solving problems and getting feedback from Go experts.
* [Go Forum](https://forum.golangbridge.org) - Forum to discuss Go.
* [Go In 5 Minutes](https://www.goin5minutes.com/) - 5 minute screencasts focused on getting one thing done.
* [Go Projects](https://github.com/golang/go/wiki/Projects) - List of projects on the Go community wiki.
* [gocryforhelp ★23](https://github.com/ninedraft/gocryforhelp) - Collection of Go projects that needs help. Good place to start your open-source way in Go.
* [godoc.org](https://godoc.org/) - Documentation for open source Go packages.
* [Golang Flow](http://golangflow.io) - Post Updates, News, Packages and more.
* [Golang News](https://golangnews.com) - Links and news about Go programming.
* [golang-graphics ★112 ⏳2Y](https://github.com/mholt/golang-graphics) - Collection of Go images, graphics, and art.
* [golang-nuts](https://groups.google.com/forum/#!forum/golang-nuts) - Go mailing list.
* [Google Plus Community](https://plus.google.com/communities/114112804251407510571) - The Google+ community for #golang enthusiasts.
* [gowalker.org](https://gowalker.org) - Go Project API documentation.
* [r/Golang](https://www.reddit.com/r/golang) - News about Go.
* [Trending Go repositories on GitHub today](https://github.com/trending?l=go) - Good place to find new Go libraries.

### Tutorials

* [A Tour of Go](http://tour.golang.org/) - Interactive tour of Go.
* [Build web application with Golang ★17469](https://github.com/astaxie/build-web-application-with-golang) - Golang ebook intro how to build a web app with golang.
* [Building Go Web Applications and Microservices Using Gin](https://semaphoreci.com/community/tutorials/building-go-web-applications-and-microservices-using-gin) - Get familiar with Gin and find out how it can help you reduce boilerplate code and build a request handling pipeline.
* [Go By Example](https://gobyexample.com/) - Hands-on introduction to Go using annotated example programs.
* [Go Cheat Sheet ★2253](https://github.com/a8m/go-lang-cheat-sheet) - Go's reference card.
* [Go database/sql tutorial](http://go-database-sql.org/) - Introduction to database/sql.
* [Golangbot](https://golangbot.com/learn-golang-series/) - Tutorials to get started with programming in Go.
* [How to Use Godog for Behavior-driven Development in Go](https://semaphoreci.com/community/tutorials/how-to-use-godog-for-behavior-driven-development-in-go) - Get started with Godog — a Behavior-driven development framework for building and testing Go applications.
* [Working with Go ★753](https://github.com/mkaz/working-with-go) - Intro to go for experienced programmers.
---
<p align="center">
	This list is a copy of <a href="https://github.com/avelino/awesome-go">avelino/awesome-go</a> with ranks
</p>
