<h1 align="center">
Ranked awesome lists, all in one place
</h1>
<p align="center">
	This list is a copy of <a href="razum2um/awesome-clojure">razum2um/awesome-clojure</a> with ranks
</p>
---
# Awesome Clojure [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg) ★59088](sindresorhus/awesome)

- [Awesome products in Clojure](#awesome-products-in-clojure)
  - [LightTable (IDE)](http://lighttable.com/)
  - [Nightcode (IDE)](https://sekao.net/nightcode/)
  - [Riemann (Monitoring)](http://riemann.io/)
  - [Puppet Server](https://github.com/puppetlabs/puppet-server)
  - [PuppetDB ★211](puppetlabs/puppetdb)
  - [Metabase ★5769](metabase/metabase)
  - [Avi (vim rewrite) ★182](maitria/avi)
- [Languages written with Clojure](#languages-written-with-clojure)
  - [jank ★46](jeaye/jank)
  - [lux ★722](LuxLang/lux)
  - [mal](https://github.com/kanaka/mal/tree/master/clojure)
  - [scheje ★60](turbopape/scheje)
- [Awesome tools in Clojure](#awesome-tools-in-clojure)
  - [Web Framework](#web-framework)
  - [Dependency injection](#dependency-injection)
  - [Build Automation and Package management](#build-automation-and-package-management)
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
  - [Editor Plugins](#editor-plugins)
  - [Literate Programming](#literate-programming)
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

  * [Web Non-Framework ★17](webnf/webnf)
  * [Luminus](http://www.luminusweb.net/)
  * [Joodo ★3 ⏳3Y](slagyr/joodoweb)
  * [Coils](https://github.com/zubairq/AppShare)
  * [Duct](https://github.com/weavejester/duct)
  * [Pedestal ★1756](pedestal/pedestal)
  * [Catalysis](https://github.com/metasoarous/catalysis)
  * [yada ★449](juxt/yada)
  * [Hoplon](http://hoplon.io/)

## Dependency injection

*Managed lifecycle of stateful objects*

  * [Component ★1381](stuartsierra/component)
  * [System ★469](danielsz/system)
  * [mount ★607](tolitius/mount)

## Build Automation and Package management

*Libraries for project build automation and package/dependency management.*

  * [Leiningen ★5434](technomancy/leiningen)
  * [Boot ★1238](boot-clj/boot)

## Date and Time

*Libraries for working with dates and times.*

  * [clj-time ★561](clj-time/clj-time)

## GUI

  * [fx-clj ★80 ⏳1Y](aaronc/fx-clj)
  * [seesaw ★1112](daveray/seesaw)

## Audio

  * [Overtone](http://overtone.github.io/)
  * [Alda ★2646](alda-lang/alda)

## HTTP

*Libraries for working with HTTP.*

  * [clj-http ★1073](dakrone/clj-http)
  * [http-kit](http://www.http-kit.org/)
  * [ring ★2229](ring-clojure/ring)
  * [kvlt ★44](nervous-systems/kvlt)

## Database

*Databases and database client libraries*

  * [Datomic](http://www.datomic.com/)
  * [clojure.jdbc ★85](funcool/clojure.jdbc)
  * [cravendb ★50 ⏳3Y](robashton/cravendb)
  * [Mongo](http://clojuremongodb.info/)
  * [RethinkDB ★170](apa512/clj-rethinkdb)
  * [ElasticSearch](http://clojureelasticsearch.info/)
  * [Neo4j](http://clojureneo4j.info/)

## Connection pools

*Database connection pools*

  * [hikari-cp ★164](tomekw/hikari-cp)

## Structural Migrations

*Keeps database and others in sync*

  * [Lobos ★262](budu/lobos)
  * [Ragtime ★353](weavejester/ragtime)
  * [Joplin ★246](juxt/joplin)
  * [Migratus ★213](yogthos/migratus)
  * [Drift ★110](macourtney/drift)

## Redis

  * [carmine ★717](ptaoussanis/carmine)

## JSON

  * [cheshire ★925](dakrone/cheshire)

## Database Cli

## ORM and SQL generation

*DSL for SQL generation.*

  * [Korma](http://sqlkorma.com/)
  * [stch-library/sql ★22](stch-library/sql)
  * [sqlingvo ★143](r0man/sqlingvo)
  * [honeysql ★564](jkk/honeysql)
  * [Toucan ★107](metabase/toucan)

## Security

*Authentication, authorization and other security related libraries.*

  * [Buddy ★519](funcool/buddy)
  * [Friend ★1079](cemerick/friend)
  * [bolt ★124 ⏳1Y](juxt/bolt)

## RESTful API

*Libraries for developing RESTful APIs.*

  * [Liberator](http://clojure-liberator.github.io/liberator/)
  * [compojure-api ★665](metosin/compojure-api)
  * [Friboo ★93](zalando/friboo)
  * [yada ★449](juxt/yada)
  * [router ★73](darkleaf/router)

## Emails

  * [postal ★384](drewr/postal)

## HTML Manipulation

*Libraries for working with HTML.*

  * [Enlive](https://github.com/cgrand/enlive/wiki)
  * [hiccup ★1556](weavejester/hiccup)
  * [clostache ★267](fhd/clostache)

## Data Validation

*Libraries for validating data.*

  * [Validateur](http://clojurevalidations.info/)
  * [Prismatic's schema ★1745](plumatic/schema)
  * [domaintypes ★5 ⏳2Y](friemen/domaintypes)
  * [Bouncer ★304](leonardoborges/bouncer)
  * [clova ★9](markwoodhall/clova)
  * [Orchestra ★56](jeaye/orchestra)

## Type System
*Optional type system for Clojure*

  * [core.typed ★917](clojure/core.typed)

## Pattern Matching

  * [core.match ★765](clojure/core.match)
  * [Verbal-Exprejon ★90 ⏳1Y](GuillaumeBadi/Verbal-Exprejon)
  * [defun ★323](killme2008/defun)
  * [cats.match ★22](zalando/cats.match)
  * [Akar ★152](missingfaktor/akar)

## Async processing

  * [core.async ★1367](clojure/core.async)
  * [pulsar ★761](puniverse/pulsar)
  * [lamina ★735 ⏳1Y](ztellman/lamina)
  * [aleph ★1820](ztellman/aleph)

## Monads

  * [cats ★546](funcool/cats)
  * [algo.monads ★332](clojure/algo.monads)

## WebSocket

  * [Sente ★1205](ptaoussanis/sente)

## Testing

  * [Expectations](http://jayfields.com/expectations/)
  * [Midje ★1285](marick/Midje)

## Webdriver automation

  * [Etaoin ★40](igrishaev/etaoin)

## Code Analysis and Linter

  * [Slamhound ★363](technomancy/slamhound)
  * [eastwood ★667](jonase/eastwood)
  * [kibit ★1238](jonase/kibit)

## Science and Data Analysis

  * [Incanter ★1881](incanter/incanter)
  * [Cascalog](http://cascalog.org/)
  * [Onyx ★1495](onyx-platform/onyx)
  * [Neanderthal ★322](uncomplicate/neanderthal)

## Machine Learning

  * [clj-ml ★132 ⏳1Y](antoniogarrote/clj-ml)
  * [clj-bigml ★47 ⏳1Y](bigmlcom/clj-bigml)
  * [Clatern ★67 ⏳1Y](rinuboney/clatern)
  * [Deeplearning4j ★6723](deeplearning4j/deeplearning4j)
  * [Enclog ★136 ⏳1Y](jimpil/enclog)
  * [Infer ★159 ⏳1Y](aria42/infer)
  * [k9 ★88 ⏳2Y](gigasquid/k9)
  * [lambda-ml ★22](cloudkj/lambda-ml)
  * [Statistiker ★50 ⏳1Y](clojurewerkz/statistiker)
  * [Synaptic ★81 ⏳1Y](japonophile/synaptic)

## Computer Vision

  * [clj-tesseract ★41](antoniogarrote/clj-tesseract)
  * [vision](http://nakkaya.com/vision.html)

## Natural Language Processing

  * [clojure-opennlp ★620](dakrone/clojure-opennlp)
  * [postagga](https://github.com/turbopape/postagga)

## Parsing

  * [Instaparse ★1781](Engelberg/instaparse)

## Editor Plugins

  * [CIDER ★2121](clojure-emacs/cider)
  * [vim-fireplace ★1226](tpope/vim-fireplace)
  * [vim-redl ★105 ⏳2Y](dgrnbrg/vim-redl)
  * [vim-leiningen ★134 ⏳1Y](tpope/vim-salve)
  * [rainbow_parentheses.vim ★152](junegunn/rainbow_parentheses.vim)
  * [Cursive (IntelliJ)](https://cursive-ide.com/)
  * [Parinfer](http://shaunlebron.github.io/parinfer/)

## Literate Programming

  * [marginalia ★621](gdeer81/marginalia)
  * [klipse ★1180](viebel/klipse)

## Miscellaneous

 * [clj-tuple ★170 ⏳1Y](ztellman/clj-tuple)
 * [slingshot ★470](scgilardi/slingshot)

## Debugging

  * [debugger ★188 ⏳1Y](razum2um/clj-debugger)
  * [debug-repl ★138 ⏳3Y](GeorgeJahad/debug-repl)
  * [ritz ★327 ⏳4Y](pallet/ritz)
  * [redl ★30 ⏳2Y](dgrnbrg/redl)
  * [limit-break ★16 ⏳4Y](technomancy/limit-break)
  * [spyscope ★372](dgrnbrg/spyscope)
  * [aprint ★106 ⏳1Y](razum2um/aprint)
  * [pretty ★331](AvisoNovate/pretty)
  * [prone ★439](magnars/prone)
  * [figwheel ★2132](bhauman/lein-figwheel)

## CI

  * [lambdacd ★455](flosell/lambdacd)

## Guides

  * [Clojure Distilled](http://yogthos.github.io/ClojureDistilled.html)
  * [clojure-cookbook ★1793](clojure-cookbook/clojure-cookbook)
  * [A Brief Beginner's Guide To Clojure](http://www.unexpected-vortices.com/clojure/brief-beginners-guide/index.html)
  * [Clojure for the Brave and True](http://www.braveclojure.com/)
  * [Clojure from the ground up](https://aphyr.com/tags/Clojure-from-the-ground-up)

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
  * [Wonderland Clojure Katas ★503](gigasquid/wonderland-clojure-katas)
  * [Clojure Katas](http://clojurekatas.org)
  * [4clojure](http://www.4clojure.com/)
  * [exercism.io](http://exercism.io/languages/clojure)

## Project Management
  
  * [milestones](https://github.com/turbopape/milestones)
---
<p align="center">
	This list is a copy of <a href="razum2um/awesome-clojure">razum2um/awesome-clojure</a> with ranks
</p>
