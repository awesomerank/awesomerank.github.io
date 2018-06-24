---
layout: default
title: Awesome Rank for razum2um/awesome-clojure
---

<p align="center">
	This list is a copy of <a href="https://github.com/razum2um/awesome-clojure">razum2um/awesome-clojure</a> with ranks
</p>
---
# Awesome Clojure [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg) ★87749](https://github.com/sindresorhus/awesome)

- [Awesome products in Clojure](#awesome-products-in-clojure)
  - [LightTable (IDE)](http://lighttable.com/)
  - [Nightcode (IDE)](https://sekao.net/nightcode/)
  - [Riemann (Monitoring)](http://riemann.io/)
  - [Puppet Server](https://github.com/puppetlabs/puppet-server)
  - [PuppetDB ★225](https://github.com/puppetlabs/puppetdb)
  - [Metabase ★10007](https://github.com/metabase/metabase)
  - [Avi (vim rewrite) ★198](https://github.com/maitria/avi)
  - [Liquid (Text Editor) ★195](https://github.com/mogenslund/liquid)
  - [Clojupyter ★348](https://github.com/clojupyter/clojupyter)
  - [Meo ★82](https://github.com/matthiasn/meo)
  - [Jepsen ★3104](https://github.com/jepsen-io/jepsen)
- [Languages written with Clojure](#languages-written-with-clojure)
  - [jank ★61](https://github.com/jeaye/jank)
  - [lux ★939](https://github.com/LuxLang/lux)
  - [mal](https://github.com/kanaka/mal/tree/master/clojure)
  - [scheje](https://github.com/turbopape/scheje)
- [Awesome tools in Clojure](#awesome-tools-in-clojure)
  - [Web Framework](#web-framework)
  - [Dependency injection](#dependency-injection)
  - [Build Automation and Package management](#build-automation-and-package-management)
  - [Version Control Management](#version-control-management)
  - [Date and Time](#date-and-time)
  - [GUI](#gui)
  - [Audio](#audio)
  - [HTTP](#http)
  - [Database](#database)
  - [Connection pools](#connection-pools)
  - [Structural Migrations](#structural-migrations)
  - [Redis](#redis)
  - [JSON](#json)
  - [ORM and SQL generation](#orm-and-sql-generation)
  - [Security](#security)
  - [RESTful API](#restful-api)
  - [Emails](#emails)
  - [HTML Manipulation](#html-manipulation)
  - [Data Validation](#data-validation)
  - [Type System](#type-system)
  - [Pattern Matching](#pattern-matching)
  - [Async processing](#async-processing)
  - [Monads](#monads)
  - [WebSocket](#websocket)
  - [Testing](#testing)
  - [Webdriver automation](#webdriver-automation)
  - [Code Analysis and Linter](#code-analysis-and-linter)
  - [Science and Data Analysis](#science-and-data-analysis)
  - [Machine Learning](#machine-learning)
  - [Computer Vision](#computer-vision)
  - [Natural Language Processing](#natural-language-processing)
  - [Parsing](#parsing)
  - [Reflection](#reflection)
  - [Editor Plugins](#editor-plugins)
  - [Documentation](#documentation)
  - [Literate Programming](#literate-programming)
  - [Archives and Compression](#archives-and-compression)
  - [Miscellaneous](#miscellaneous)
  - [Debugging tools](#debugging)
  - [CI](#ci)
  - [Project Management](#project-management)

- [Resources](#resources)
  - [Guides](#guides)
  - [Websites](#websites)
  - [Twitter](#twitter)
  - [Exercises](#exercises)


## Web Framework

*Actually don't search rails/django here, but compose them by yourself*
  * [Compojure ★3401](https://github.com/weavejester/compojure)
  * [Web Non-Framework ★18](https://github.com/webnf/webnf)
  * [Luminus](http://www.luminusweb.net/)
  * [Joodo ★3 ⏳4Y](https://github.com/slagyr/joodoweb)
  * [Coils ★0 ⏳3Y](https://github.com/l4u/coils)
  * [Duct](https://github.com/weavejester/duct)
  * [Pedestal ★1894](https://github.com/pedestal/pedestal)
  * [Datsys ★182](https://github.com/metasoarous/datsys)
  * [yada ★547](https://github.com/juxt/yada)
  * [Hoplon](http://hoplon.io/)
  * [Fulcro ★291](https://github.com/fulcrologic/fulcro)
  * [Coast](http://coastonclojure.com/)

## Dependency injection

*Managed lifecycle of stateful objects*

  * [Component ★1511](https://github.com/stuartsierra/component)
  * [System ★538](https://github.com/danielsz/system)
  * [mount ★765](https://github.com/tolitius/mount)
  * [Integrant ★444](https://github.com/weavejester/integrant)

## Build Automation and Package management

*Libraries for project build automation and package/dependency management.*

  * [Leiningen ★5922](https://github.com/technomancy/leiningen)
  * [Boot ★1449](https://github.com/boot-clj/boot)
  * [lucid.distribute](http://docs.caudate.me/lucidity/lucid-distribute.html)
  * [lucid.package](http://docs.caudate.me/lucidity/lucid-package.html)

## Version Control Management

*Code utilities for interacting with VCS software*

  * [lucid.git](http://docs.caudate.me/lucidity/lucid-git.html)

## Date and Time

*Libraries for working with dates and times.*

  * [clj-time ★623](https://github.com/clj-time/clj-time)

## GUI

  * [fx-clj ★93](https://github.com/aaronc/fx-clj)
  * [seesaw ★1191](https://github.com/daveray/seesaw)

## Audio

  * [Overtone](http://overtone.github.io/)
  * [Alda ★2945](https://github.com/alda-lang/alda)

## HTTP

*Libraries for working with HTTP.*

  * [clj-http ★1214](https://github.com/dakrone/clj-http)
  * [http-kit](http://www.http-kit.org/)
  * [ring ★2555](https://github.com/ring-clojure/ring)
  * [kvlt ★69](https://github.com/nervous-systems/kvlt)

## Database

*Databases and database client libraries*

  * [Datomic](http://www.datomic.com/)
  * [clojure.jdbc ★99](https://github.com/funcool/clojure.jdbc)
  * [cravendb ★53 ⏳4Y](https://github.com/robashton/cravendb)
  * [Mongo](http://clojuremongodb.info/)
  * [Monglorious](https://baumandm.github.io/monglorious/)
  * [RethinkDB ★180](https://github.com/apa512/clj-rethinkdb)
  * [Revise (RethinkDB) ★146 ⏳3Y](https://github.com/bitemyapp/revise)
  * [ElasticSearch](http://clojureelasticsearch.info/)
  * [Neo4j](http://clojureneo4j.info/)

## Connection pools

*Database connection pools*

  * [hikari-cp ★210](https://github.com/tomekw/hikari-cp)

## Structural Migrations

*Keeps database and others in sync*

  * [Lobos ★262 ⏳1Y](https://github.com/budu/lobos)
  * [Ragtime ★396](https://github.com/weavejester/ragtime)
  * [Joplin ★267](https://github.com/juxt/joplin)
  * [Migratus ★283](https://github.com/yogthos/migratus)
  * [Drift ★112 ⏳1Y](https://github.com/macourtney/drift)

## Redis

  * [carmine ★779](https://github.com/ptaoussanis/carmine)
  * [celtuce ★6](https://github.com/lerouxrgd/celtuce)

## JSON

  * [cheshire ★1027](https://github.com/dakrone/cheshire)

## Database Cli

## ORM and SQL generation

*DSL for SQL generation.*
  * [Walkable ★165](https://github.com/walkable-server/walkable)
  * [Korma](http://sqlkorma.com/)
  * [Specql ★80](https://github.com/tatut/specql)
  * [stch-library/sql ★28](https://github.com/stch-library/sql)
  * [sqlingvo ★164](https://github.com/r0man/sqlingvo)
  * [sqlium ★22](https://github.com/TheLadders/sqlium)
  * [honeysql ★809](https://github.com/jkk/honeysql)
  * [Toucan ★192](https://github.com/metabase/toucan)

## Security

*Authentication, authorization and other security related libraries.*

  * [Buddy ★603](https://github.com/funcool/buddy)
  * [Friend ★1117](https://github.com/cemerick/friend)
  * [bolt ★125 ⏳2Y](https://github.com/juxt/bolt)

## RESTful API

*Libraries for developing RESTful APIs.*

  * [Liberator](http://clojure-liberator.github.io/liberator/)
  * [compojure-api ★803](https://github.com/metosin/compojure-api)
  * [Friboo ★113 ⏳1Y](https://github.com/zalando/friboo)
  * [yada ★547](https://github.com/juxt/yada)
  * [router ★73 ⏳1Y](https://github.com/darkleaf/router)

## Emails

  * [postal ★426](https://github.com/drewr/postal)

## HTML Manipulation

*Libraries for working with HTML.*

  * [Enlive](https://github.com/cgrand/enlive/wiki)
  * [hiccup ★1748](https://github.com/weavejester/hiccup)
  * [clostache ★271](https://github.com/fhd/clostache)
  * [selmer ★579](https://github.com/yogthos/Selmer)

## Data Validation

*Libraries for validating data.*

  * [Validateur](http://clojurevalidations.info/)
  * [Prismatic's schema ★1839](https://github.com/plumatic/schema)
  * [domaintypes ★5 ⏳3Y](https://github.com/friemen/domaintypes)
  * [Bouncer ★325](https://github.com/leonardoborges/bouncer)
  * [clova ★11](https://github.com/markwoodhall/clova)
  * [Orchestra ★256](https://github.com/jeaye/orchestra)

## Type System
*Optional type system for Clojure*

  * [core.typed ★1006](https://github.com/clojure/core.typed)

## Pattern Matching

  * [core.match ★834](https://github.com/clojure/core.match)
  * [Verbal-Exprejon ★89 ⏳2Y](https://github.com/GuillaumeBadi/Verbal-Exprejon)
  * [defun ★346 ⏳1Y](https://github.com/killme2008/defun)
  * [cats.match](https://github.com/zalando/cats.match)
  * [Akar ★164](https://github.com/missingfaktor/akar)

## Async processing

  * [core.async ★1491](https://github.com/clojure/core.async)
  * [pulsar ★813](https://github.com/puniverse/pulsar)
  * [lamina ★731 ⏳2Y](https://github.com/ztellman/lamina)
  * [aleph ★1981](https://github.com/ztellman/aleph)

## Monads

  * [cats ★655](https://github.com/funcool/cats)
  * [algo.monads ★356 ⏳1Y](https://github.com/clojure/algo.monads)

## WebSocket

  * [Chord ★376](https://github.com/jarohen/chord)
  * [Sente ★1317](https://github.com/ptaoussanis/sente)

## Testing

  * [Expectations ★359](https://github.com/clojure-expectations/expectations)
  * [Midje ★1383](https://github.com/marick/Midje)
  * [lucid.unit](http://docs.caudate.me/lucidity/lucid-unit.html)
  * [test-doubles ★28](https://github.com/GreenPowerMonitor/test-doubles) 

## Webdriver automation

  * [Etaoin ★265](https://github.com/igrishaev/etaoin)

## Code Analysis and Linter

  * [Slamhound ★384 ⏳1Y](https://github.com/technomancy/slamhound)
  * [eastwood ★797](https://github.com/jonase/eastwood)
  * [kibit ★1404](https://github.com/jonase/kibit)
  * [lucid.query](http://docs.caudate.me/lucidity/lucid-query.html)
  * [yagni ★163](https://github.com/venantius/yagni)
  * [lein-bikeshed ★146](https://github.com/dakrone/lein-bikeshed)
  * [spectrum ★405](https://github.com/arohner/spectrum)
  * [cloverage ★296](https://github.com/cloverage/cloverage)

## Science and Data Analysis

*Libraries, extended REPLs, and other tools for scientific and statistical data
anylysis and visualization.*

  * [Incanter ★1969](https://github.com/incanter/incanter)
  * [Cascalog](http://cascalog.org/)
  * [Onyx ★1741](https://github.com/onyx-platform/onyx)
  * [sparklling ★332](https://github.com/gorillalabs/sparkling)
  * [flambo ★562](https://github.com/yieldbot/flambo)
  * [Neanderthal ★515](https://github.com/uncomplicate/neanderthal)
  * [lucid.graph](http://docs.caudate.me/lucidity/lucid-graph.html)
  * [Streaming Histograms ★137](https://github.com/bigmlcom/histogram)
  * [Gorilla REPL](http://gorilla-repl.org/)  

## Machine Learning

  * [clj-ml ★139 ⏳2Y](https://github.com/antoniogarrote/clj-ml)
  * [cortex ★1029](https://github.com/originrose/cortex)
  * [clj-bigml ★48](https://github.com/bigmlcom/clj-bigml)
  * [Clatern ★67 ⏳2Y](https://github.com/rinuboney/clatern)
  * [Deeplearning4j ★9002](https://github.com/deeplearning4j/deeplearning4j)
  * [Enclog ★137 ⏳2Y](https://github.com/jimpil/enclog)
  * [Infer ★171 ⏳2Y](https://github.com/aria42/infer)
  * [k9 ★98 ⏳3Y](https://github.com/gigasquid/k9)
  * [lambda-ml ★46](https://github.com/cloudkj/lambda-ml)
  * [Statistiker ★53 ⏳3Y](https://github.com/clojurewerkz/statistiker)
  * [Synaptic ★87 ⏳2Y](https://github.com/japonophile/synaptic)

## Computer Vision

  * [clj-tesseract ★43 ⏳1Y](https://github.com/antoniogarrote/clj-tesseract)
  * [vision](http://nakkaya.com/vision.html)

## Natural Language Processing

  * [clojure-opennlp ★653 ⏳1Y](https://github.com/dakrone/clojure-opennlp)
  * [postagga](https://github.com/turbopape/postagga)

## Parsing

  * [Instaparse ★1944](https://github.com/Engelberg/instaparse)
  * [kern ★163](https://github.com/blancas/kern)
  * [duckling](https://github.com/wit-ai/duckling)
  
## Exceptions and Error Handling
  * [Perseverance ★95](https://github.com/grammarly/perseverance)
  * [Dire ★473 ⏳2Y](https://github.com/MichaelDrogalis/dire)
  
## Reflection
*Libraries for improved code reflection and object introspection

  * [hara.reflect](docs.caudate.me/hara/hara-reflect.html)
  * [lucid.mind](http://docs.caudate.me/lucidity/lucid-mind.html)
  * [lucid.query](http://docs.caudate.me/lucidity/lucid-query.html)

## Editor Plugins

  * [CIDER (Emacs) ★2399](https://github.com/clojure-emacs/cider)
  * [smartparens (Emacs) ★986](https://github.com/Fuco1/smartparens)
  * [rainbow-delimiters (Emacs) ★247](https://github.com/Fanael/rainbow-delimiters)
  * [aggressive-indent (Emacs) ★397](https://github.com/Malabarba/aggressive-indent-mode)
  * [vim-fireplace (Vim) ★1347](https://github.com/tpope/vim-fireplace)
  * [vim-redl (Vim) ★110 ⏳3Y](https://github.com/dgrnbrg/vim-redl)
  * [vim-leiningen (Vim) ★139](https://github.com/tpope/vim-salve)
  * [rainbow_parentheses.vim (Vim) ★195](https://github.com/junegunn/rainbow_parentheses.vim)
  * [Cursive (IntelliJ)](https://cursive-ide.com/)
  * [Parinfer (multiple editors)](http://shaunlebron.github.io/parinfer/)

## Documentation

*Utilities and libraries for (non-LP) code and project documentation*

 * [lucid.publish](http://docs.caudate.me/lucidity/lucid-publish.html)

## Literate Programming

  * [marginalia ★666](https://github.com/gdeer81/marginalia)
  * [klipse ★1598](https://github.com/viebel/klipse)

## Archives and Compression

  * [swindon (java.util.zip wrapper) ★2 ⏳3Y](https://github.com/AeroNotix/swindon)

## Miscellaneous

 * [clj-tuple ★173 ⏳3Y](https://github.com/ztellman/clj-tuple)
 * [slingshot ★512 ⏳1Y](https://github.com/scgilardi/slingshot)
 * [lucid.system](http://docs.caudate.me/lucidity/lucid-system.html)
 * [virgil ★198](https://github.com/ztellman/virgil)
 * [javastar ★58 ⏳5Y](https://github.com/tailrecursion/javastar)
 * [riddley ★126](https://github.com/ztellman/riddley)

## Debugging

  * [debugger ★200 ⏳2Y](https://github.com/razum2um/clj-debugger)
  * [debug-repl ★141 ⏳4Y](https://github.com/GeorgeJahad/debug-repl)
  * [ritz ★327 ⏳5Y](https://github.com/pallet/ritz)
  * [redl ★33 ⏳3Y](https://github.com/dgrnbrg/redl)
  * [limit-break ★16 ⏳5Y](https://github.com/technomancy/limit-break)
  * [spyscope ★444](https://github.com/dgrnbrg/spyscope)
  * [aprint ★114 ⏳2Y](https://github.com/razum2um/aprint)
  * [packed-printer ★33](https://github.com/cgrand/packed-printer)
  * [pretty ★382](https://github.com/AvisoNovate/pretty)
  * [prone ★474](https://github.com/magnars/prone)
  * [figwheel ★2498](https://github.com/bhauman/lein-figwheel)
  * [ultra ★1056](https://github.com/venantius/ultra)

## CI

  * [lambdacd ★533](https://github.com/flosell/lambdacd)

## Guides

  * [The Clojure Style Guide ★2869](https://github.com/bbatsov/clojure-style-guide)
  * [Clojure Distilled](http://yogthos.github.io/ClojureDistilled.html)
  * [clojure-cookbook ★1970](https://github.com/clojure-cookbook/clojure-cookbook)
  * [A Brief Beginner's Guide To Clojure](http://www.unexpected-vortices.com/clojure/brief-beginners-guide/index.html)
  * [Clojure for the Brave and True](http://www.braveclojure.com/)
  * [Clojure from the ground up](https://aphyr.com/tags/Clojure-from-the-ground-up)
  * [Error message catalog ★346](https://github.com/yogthos/clojure-error-message-catalog)
  * [Clojure by Example](https://kimh.github.io/clojure-by-example/)

## Websites

  * [Clojure](http://clojure.org/)
  * [Clojure Slack](http://clojurians.net/)
  * [clojuredocs](http://clojuredocs.org)
  * [crossclj](https://crossclj.info/)
  * [clojure-doc](http://clojure-doc.org/)
  * [Grimoire](http://conj.io/)
  * [The Clojure Toolbox](http://www.clojure-toolbox.com/)
  * [InstaREPL Online](http://web.clojurerepl.com/)
  * [ZEEF/Clojure](https://clojure.zeef.com/vlad.bokov)
  * [Try Clojure](http://www.tryclj.com/)

## Twitter

  * [oss_clj](https://twitter.com/oss_clj)

## Exercises

  * [Clojure Koans](http://clojurekoans.com)
  * [Wonderland Clojure Katas ★584](https://github.com/gigasquid/wonderland-clojure-katas)
  * [Clojure Katas](http://clojurekatas.org)
  * [4clojure](http://www.4clojure.com/)
  * [exercism.io](http://exercism.io/languages/clojure)
  * [Clojurecademy](https://clojurecademy.com)
  * [Codewars](https://www.codewars.com/kata/search/clojure)

## Project Management
  
  * [milestones](https://github.com/turbopape/milestones)
---
<p align="center">
	This list is a copy of <a href="https://github.com/razum2um/awesome-clojure">razum2um/awesome-clojure</a> with ranks
</p>
