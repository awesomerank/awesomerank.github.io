<h1 align="center">
Ranked awesome lists, all in one place
</h1>
<p align="center">
	This list is a copy of <a href="yissachar/awesome-dart">yissachar/awesome-dart</a> with ranks
</p>
---
Awesome Dart [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg) ★59088](sindresorhus/awesome)
============

A curated list of awesome Dart frameworks, libraries, and software. Items on the list are actively maintained, well documented, and popular in the Dart community. Inspired by the [awesome ★59088](sindresorhus/awesome) lists.

### Contributing

Please take a quick look at the [contribution guidelines](https://github.com/yissachar/awesome-dart/blob/master//CONTRIBUTING.md) first. If you see a package or project here that is no longer maintained or is not a good fit, please submit a pull request to improve this file. Thank you to all [contributors](https://github.com/yissachar/awesome-dart/graphs/contributors); you rock!

### Contents

* [Client Web App Frameworks](#client-web-app-frameworks)
* [Server Frameworks](#server-frameworks)
* [Game Development](#game-development)
* [Animation](#animation)
* [Template](#template)
* [Database](#database)
* [Package Managers](#package-managers)
* [Utilities](#utilities)
* [Dependency Injection](#dependency-injection)
* [Parsers](#parsers)
* [Validation](#validation)
* [ORM](#orm)
* [Image](#image)
* [Algorithms](#algorithms)
* [Testing](#testing)
* [Tools](#tools)
* [IDEs, Editors, and Plugins](#ides-editors-and-plugins)
* [Tutorials](#tutorials)
* [Everything Else](#everything-else)

----

## Client Web App Frameworks

* [Angular](https://angulardart.org/) - Angular is a framework for building client web-apps.
* [Angular2](https://angular.io/) - Angular is a development platform for building mobile and desktop web applications.
* [Polymer](https://www.dartlang.org/polymer/) - Use polymer to build structured, encapsulated, client-side web apps with web components.
* [uix ★66](localvoid/uix) - Library to build Web User Interfaces in Dart inspired by React.
* [MDL/Dart](http://www.material-design-lite.pub/) - Material Design Lite for Dart is a framework of components for web developers based on Google's Material Design philosophy.

## Server Frameworks

* [Jaguar ★24](Jaguar-dart/jaguar) - A server framework built for speed, simplicity and extensiblity.
* [Angel ★97](angel-dart/angel) - Angel is a server-side framework designed for full-stack development, with an emphasis on code sharing, scalability, and a low learning curve.
* [Aqueduct ★136](stablekernel/aqueduct) - Aqueduct is a fully-featured server-side framework, with an ORM, database migration tools, OAuth 2.0 implementation, automatic OpenAPI specification generation and multi-threading support.
* [Redstone ★268](redstone-dart/redstone) - Redstone is a server-side, metadata driven micro-framework for Dart.
* [Start ★387](lvivski/start) - Sinatra inspired web framework to serve static files, handle dynamic requests, websockets and create JSON responses.
* [Express ★104 ⏳2Y](dartist/express) - A simple, thin expressjs inspired layer around Dart's primitive HttpServer APIs.
* [Shelf](https://pub.dartlang.org/packages/shelf) - Shelf makes it easy to create and compose web servers and parts of web servers.
    * There are many packages written for Shelf. By convention they start with [shelf_](https://pub.dartlang.org/search?q=shelf_)
* [Force ★83](ForceUniverse/dart-force) - A real time web framework, embracing websockets, making communication even better
* [Vane ★24](Scorpiion/Vane) - Framework with built-in server runtime environment and middleware system
* [Rikulo Stream ★140](rikulo/stream) - Lightweight web server with request routing, filtering, template engine, WebSocket, MVC design pattern, and file-based static resources

## Game Development

* [StageXL](http://www.stagexl.org/) - StageXL offers an easy to use and complete API (based on the Flash API) for impressive 2D content like games and other rich applications.
* [DartRocket ★39 ⏳2Y](StrykerKKD/dartrocket) - DartRocket is a HTML5 game framework written in Dart and which uses the StageXL rendering engine.
* [Pixi Dart ★21 ⏳2Y](FedeOmoto/pixi) - A port of the pixi.js rendering engine.
* [Ranger ★15 ⏳2Y](wdevore/Ranger-Dart) - A game engine centered around HTML5 Canvas and a scene graph.

## Animation

* [Universal Tween Engine ★20 ⏳1Y](xaguzman/tween-engine-dart) - A port of the original java Universal Tween Engine created by Aurelien Ribbon.
* [Spine Dart ★6 ⏳2Y](FedeOmoto/spine) - An implementation of the Esoteric Software Spine runtime.

## Template

* [mustache4dart ★36](valotas/mustache4dart) - A simple implementation of Mustache.
* [jaded ★32 ⏳3Y](dartist/jaded) - Port of the excellent Jade view engine.

## Database

* [Postgres ★8](stablekernel/postgresql-dart) - A PostgreSQL database driver that uses the extended, binary protocol for more efficient and secure queries.
* [SQLJockey ★6](jamesots/sqljocky) - MySQL connector.
* [PostgreSQL ★69](xxgreg/dart_postgresql) - PostgreSQL database driver
* [dartabase_model](https://pub.dartlang.org/packages/dartabase_model) - Serverside Database Object Models for simple data manipulation using MySQL/PGSQL without having to write SQL
* [dartabase_migration](https://pub.dartlang.org/packages/dartabase_migration) - Serverside Database migration for simple version controlled database structure manipulation using MySQL/PGSQL without having to write SQL

## Package Managers

* [Pub](https://pub.dartlang.org/) - Pub is used to manage packages.

## Utilities

* [Flutter ★984](flutter/engine) - Flutter is a new way to build high-performance, cross-platform mobile apps, allowing you to write applications for Android and iOS.
* [Quiver ★143](google/quiver-dart) - A set of utility libraries that makes using many libraries easier and more convenient, or adds additional functionality.
* [route_hierarchical ★30 ⏳1Y](angular/route.dart) - Route is a client routing library for Dart that helps make building single-page web apps.
* [Archive](https://pub.dartlang.org/packages/archive) - A library to encode and decode various archive and compression formats.
* [Frappe](https://pub.dartlang.org/packages/frappe) - A functional reactive programming library for Dart. Frappé extends the functionality of Dart's streams, and introduces new concepts like properties/signals.

## Dependency Injection

* [DI ★65](angular/di.dart) - Dependency Injection framework by Angular

## Parsers

* [html](https://pub.dartlang.org/packages/html) - A library for working with HTML documents. Previously known as html5lib.
* [markdown ★61](dart-lang/markdown) - Parse markdown into HTML on both the client and server.
* [PetitParser ★80](petitparser/dart-petitparser) - PetitParser combines ideas from scannerless parsing, parser combinators, parsing expression grammars and packrat parsers to model grammars and parsers as objects that can be reconfigured dynamically.
* [XML](https://pub.dartlang.org/packages/xml) - A lightweight library for parsing, traversing, querying and building XML documents.
* [xmlstream](https://pub.dartlang.org/packages/xml) - A streaming event-based XML Parser.
* [YAML](https://pub.dartlang.org/packages/yaml) - A parser for YAML.

## Validation

* [Constrain](https://pub.dartlang.org/packages/constrain) - Provides a constraint based Validation library inspired by Java Bean Validation but leveraging the superior language capabilities of Dart.
* [validator.dart ★18 ⏳2Y](karan/validator.dart) - String validation and sanitization for Dart.

## ORM

* [Objectory ★42](vadimtsushko/objectory) - Objectory provides typed, checked environment to model, save and query data persisted on MongoDb.

## Image

* [image ★75](brendan-duncan/image) - Provides server and web apps the ability to load, manipulate, and save images with various image file formats including PNG, JPEG, GIF, WebP, TIFF, TGA, PSD, PVR, and OpenEXR.

## Algorithms

* [cassowary](https://github.com/domokit/cassowary) - Implements a subset of the functionality described in the Cassowary paper.  Accepts constraints and updates member variables in an attempt to satisfy the same.

## Testing

* [Guinness ★40 ⏳1Y](vsavkin/guinness) - A port of the Jasmine library.
* [test](https://pub.dartlang.org/packages/test) - Provides a standard way of writing and running tests in Dart.

## Tools

* [Observatory](https://www.dartlang.org/tools/observatory/) - Observatory is a tool for profiling and debugging your Dart applications.
* [dart2js](https://www.dartlang.org/tools/dart2js/) - compiles Dart code to JavaScript
* [js2dart ★16 ⏳2Y](vojtajina/js2dart) - compiles Javascript code to Dart
* [Stagehand ★193](google/stagehand) - A project scaffolding generator, inspired by tools like Web Starter Kit and Yeoman.
* [Crossdart](http://crossdart.info) - Cross-referenced source code of the packages from Pub.
* [Crossdart Github Chrome Extension](https://chrome.google.com/webstore/detail/crossdart-chrome-extensio/jmdjoliiaibifkklhipgmnciiealomhd) - Adds "Go to declaration" and "Find Usages" functionality to your Dart projects on Github (both in tree views and pull requests).
* [gulp-dart ★3 ⏳1Y](agudulin/gulp-dart) - A gulp plugin for compiling Dart code to JavaScript using dart2js.
* [dev_compiler](https://github.com/dart-lang/dev_compiler) - Dart to JavaScript compiler designed to create idiomatic, readable JavaScript output.

## Tutorials

* [Hello Dart](http://code.makery.ch/library/hello-dart/) - A playful introduction to Dart.
* [Darrrt](https://www.dartlang.org/codelabs/darrrt/) - Web app code lab.

## IDEs, Editors, and Plugins

* [IntelliJ Plugin](https://www.dartlang.org/tools/webstorm/) - Dart plugin from JetBrains for WebStorm, IntelliJ IDEA, PhpStorm, PyCharm, and RubyMine.
* [Sublime Text Package ★201](guillermooo/dart-sublime-bundle) - Sublime Text 3 Dart Package
* [Emacs Plugin ★53](nex3/dart-mode) - An Emacs mode for the Dart language
* [Vim Plugin ★161](dart-lang/dart-vim-plugin) - Syntax highlighting for Dart in Vim
* [Atom Plugin](https://atom.io/packages/atom-dart) - Dart support for Atom.
* [DartPad](https://dartpad.dartlang.org/) - Online lightweight editor.
* [Dart Code](https://marketplace.visualstudio.com/items?itemName=DanTup.dart-code) - Dart support for Visual Studio Code.
* [Module Linker](http://fiatjaf.alhur.es/module-linker/#/dart) - Chrome Extension that adds direct links to module import statements on GitHub.

## Everything Else

There are lots of awesome libraries being added to [Pub](https://pub.dartlang.org/) all the time. If you can't find a library on this list that meets your needs, go ahead and search for it on Pub. And if you end up finding an awesome library, we would love a pull request with the info so that everyone else can discover it as well. Just make sure to read the [contributing guidlines](https://github.com/yissachar/awesome-dart/blob/master/CONTRIBUTING.md) first.

## License

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)
---
<p align="center">
	This list is a copy of <a href="yissachar/awesome-dart">yissachar/awesome-dart</a> with ranks
</p>
