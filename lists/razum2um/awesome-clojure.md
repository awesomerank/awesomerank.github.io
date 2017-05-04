<h1 align="center">
Ranked awesome lists, all in one place
</h1>
<p align="center">
	This list is a copy of <a href="https://github.com/razum2um/awesome-clojure">https://github.com/razum2um/awesome-clojure</a> with ranks
</p>
---
# Awesome Clojure [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg) ★57421](https://github.com/sindresorhus/awesome)

- [Awesome products in Clojure](#awesome-products-in-clojure)
  - [LightTable (IDE)](http://lighttable.com/)
  - [Nightcode (IDE)](https://sekao.net/nightcode/)
  - [Riemann (Monitoring)](http://riemann.io/)
  - [Puppet Server](https://github.com/puppetlabs/puppet-server)
  - [PuppetDB ★210](https://github.com/puppetlabs/puppetdb)
  - [Metabase ★5365](https://github.com/metabase/metabase)
  - [Avi (vim rewrite) ★182](https://github.com/maitria/avi)
- [Languages written with Clojure](#languages-written-with-clojure)
  - [jank ★45](https://github.com/jeaye/jank)
  - [lux ★697](https://github.com/LuxLang/lux)
  - [mal](https://github.com/kanaka/mal/tree/master/clojure)
  - [scheje ★60](https://github.com/turbopape/scheje)
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

  * [Web Non-Framework ★17](https://github.com/webnf/webnf)
  * [Luminus](http://www.luminusweb.net/)
  * [Joodo ★3 ⏳3Y](https://github.com/slagyr/joodoweb)
  * [Coils](https://github.com/zubairq/AppShare)
  * [Duct](https://github.com/weavejester/duct)
  * [Pedestal ★1745](https://github.com/pedestal/pedestal)
  * [Catalysis](https://github.com/metasoarous/catalysis)
  * [yada ★443](https://github.com/juxt/yada)
  * [Hoplon](http://hoplon.io/)

## Dependency injection

*Managed lifecycle of stateful objects*

  * [Component ★1363](https://github.com/stuartsierra/component)
  * [System ★468](https://github.com/danielsz/system)
  * [mount ★598](https://github.com/tolitius/mount)

## Build Automation and Package management

*Libraries for project build automation and package/dependency management.*

  * [Leiningen ★5391](https://github.com/technomancy/leiningen)
  * [Boot ★1219](https://github.com/boot-clj/boot)

## Date and Time

*Libraries for working with dates and times.*

  * [clj-time ★556](https://github.com/clj-time/clj-time)

## GUI

  * [fx-clj ★80 ⏳1Y](https://github.com/aaronc/fx-clj)
  * [seesaw ★1109](https://github.com/daveray/seesaw)

## Audio

  * [Overtone](http://overtone.github.io/)
  * [Alda ★2625](https://github.com/alda-lang/alda)

## HTTP

*Libraries for working with HTTP.*

  * [clj-http ★1060](https://github.com/dakrone/clj-http)
  * [http-kit](http://www.http-kit.org/)
  * [ring ★2208](https://github.com/ring-clojure/ring)
  * [kvlt ★44](https://github.com/nervous-systems/kvlt)

## Database

*Databases and database client libraries*

  * [Datomic](http://www.datomic.com/)
  * [clojure.jdbc ★86](https://github.com/funcool/clojure.jdbc)
  * [cravendb ★50 ⏳3Y](https://github.com/robashton/cravendb)
  * [Mongo](http://clojuremongodb.info/)
  * [RethinkDB ★170](https://github.com/apa512/clj-rethinkdb)
  * [ElasticSearch](http://clojureelasticsearch.info/)
  * [Neo4j](http://clojureneo4j.info/)

## Connection pools

*Database connection pools*

  * [hikari-cp ★158](https://github.com/tomekw/hikari-cp)

## Structural Migrations

*Keeps database and others in sync*

  * [Lobos ★265](https://github.com/budu/lobos)
  * [Ragtime ★355](https://github.com/weavejester/ragtime)
  * [Joplin ★245](https://github.com/juxt/joplin)
  * [Migratus ★210](https://github.com/yogthos/migratus)
  * [Drift ★109](https://github.com/macourtney/drift)

## Redis

  * [carmine ★712](https://github.com/ptaoussanis/carmine)

## JSON

  * [cheshire ★915](https://github.com/dakrone/cheshire)

## Database Cli

## ORM and SQL generation

*DSL for SQL generation.*

  * [Korma](http://sqlkorma.com/)
  * [stch-library/sql ★22](https://github.com/stch-library/sql)
  * [sqlingvo ★142](https://github.com/r0man/sqlingvo)
  * [honeysql ★554](https://github.com/jkk/honeysql)
  * [Toucan ★91](https://github.com/metabase/toucan)

## Security

*Authentication, authorization and other security related libraries.*

  * [Buddy ★515](https://github.com/funcool/buddy)
  * [Friend ★1073](https://github.com/cemerick/friend)
  * [bolt ★124 ⏳1Y](https://github.com/juxt/bolt)

## RESTful API

*Libraries for developing RESTful APIs.*

  * [Liberator](http://clojure-liberator.github.io/liberator/)
  * [compojure-api ★655](https://github.com/metosin/compojure-api)
  * [Friboo ★89](https://github.com/zalando/friboo)
  * [yada ★443](https://github.com/juxt/yada)
  * [router ★72](https://github.com/darkleaf/router)

## Emails

  * [postal ★381](https://github.com/drewr/postal)

## HTML Manipulation

*Libraries for working with HTML.*

  * [Enlive](https://github.com/cgrand/enlive/wiki)
  * [hiccup ★1541](https://github.com/weavejester/hiccup)
  * [clostache ★266](https://github.com/fhd/clostache)

## Data Validation

*Libraries for validating data.*

  * [Validateur](http://clojurevalidations.info/)
  * [Prismatic's schema ★1729](https://github.com/plumatic/schema)
  * [domaintypes ★5 ⏳2Y](https://github.com/friemen/domaintypes)
  * [Bouncer ★304](https://github.com/leonardoborges/bouncer)
  * [clova ★9](https://github.com/markwoodhall/clova)

## Type System
*Optional type system for Clojure*

  * [core.typed ★913](https://github.com/clojure/core.typed)

## Pattern Matching

  * [core.match ★760](https://github.com/clojure/core.match)
  * [Verbal-Exprejon ★90](https://github.com/GuillaumeBadi/Verbal-Exprejon)
  * [defun ★321](https://github.com/killme2008/defun)
  * [cats.match ★22](https://github.com/zalando/cats.match)
  * [Akar ★152](https://github.com/missingfaktor/akar)

## Async processing

  * [core.async ★1346](https://github.com/clojure/core.async)
  * [pulsar ★758](https://github.com/puniverse/pulsar)
  * [lamina ★735 ⏳1Y](https://github.com/ztellman/lamina)
  * [aleph ★1809](https://github.com/ztellman/aleph)

## Monads

  * [cats ★529](https://github.com/funcool/cats)
  * [algo.monads ★329](https://github.com/clojure/algo.monads)

## WebSocket

  * [Sente ★1188](https://github.com/ptaoussanis/sente)

## Testing

  * [Expectations](http://jayfields.com/expectations/)
  * [Midje ★1285](https://github.com/marick/Midje)

## Webdriver automation

  * [Etaoin ★36](https://github.com/igrishaev/etaoin)

## Code Analysis and Linter

  * [Slamhound ★364](https://github.com/technomancy/slamhound)
  * [eastwood ★656](https://github.com/jonase/eastwood)
  * [kibit ★1212](https://github.com/jonase/kibit)

## Science and Data Analysis

  * [Incanter ★1872](https://github.com/incanter/incanter)
  * [Cascalog](http://cascalog.org/)
  * [Onyx ★1480](https://github.com/onyx-platform/onyx)
  * [Neanderthal ★295](https://github.com/uncomplicate/neanderthal)

## Machine Learning

  * [clj-ml ★131 ⏳1Y](https://github.com/antoniogarrote/clj-ml)
  * [clj-bigml ★46 ⏳1Y](https://github.com/bigmlcom/clj-bigml)
  * [Clatern ★66 ⏳1Y](https://github.com/rinuboney/clatern)
  * [Deeplearning4j ★6526](https://github.com/deeplearning4j/deeplearning4j)
  * [Enclog ★137 ⏳1Y](https://github.com/jimpil/enclog)
  * [Infer ★158 ⏳1Y](https://github.com/aria42/infer)
  * [k9 ★87 ⏳2Y](https://github.com/gigasquid/k9)
  * [lambda-ml ★19](https://github.com/cloudkj/lambda-ml)
  * [Statistiker ★50 ⏳1Y](https://github.com/clojurewerkz/statistiker)
  * [Synaptic ★79 ⏳1Y](https://github.com/japonophile/synaptic)

## Computer Vision

  * [clj-tesseract ★41](https://github.com/antoniogarrote/clj-tesseract)
  * [vision](http://nakkaya.com/vision.html)

## Natural Language Processing

  * [clojure-opennlp ★619](https://github.com/dakrone/clojure-opennlp)
  * [postagga](https://github.com/turbopape/postagga)

## Parsing

  * [Instaparse ★1762](https://github.com/Engelberg/instaparse)

## Editor Plugins

  * [CIDER ★2091](https://github.com/clojure-emacs/cider)
  * [vim-fireplace ★1224](https://github.com/tpope/vim-fireplace)
  * [vim-redl ★105 ⏳2Y](https://github.com/dgrnbrg/vim-redl)
  * [vim-leiningen ★133 ⏳1Y](https://github.com/tpope/vim-salve)
  * [rainbow_parentheses.vim ★147](https://github.com/junegunn/rainbow_parentheses.vim)
  * [Cursive (IntelliJ)](https://cursive-ide.com/)
  * [Parinfer](http://shaunlebron.github.io/parinfer/)

## Literate Programming

  * [marginalia ★615](https://github.com/gdeer81/marginalia)
  * [klipse ★1147](https://github.com/viebel/klipse)

## Miscellaneous

 * [clj-tuple ★171 ⏳1Y](https://github.com/ztellman/clj-tuple)
 * [slingshot ★470](https://github.com/scgilardi/slingshot)

## Debugging

  * [debugger ★188 ⏳1Y](https://github.com/razum2um/clj-debugger)
  * [debug-repl ★137 ⏳3Y](https://github.com/GeorgeJahad/debug-repl)
  * [ritz ★327 ⏳4Y](https://github.com/pallet/ritz)
  * [redl ★29 ⏳2Y](https://github.com/dgrnbrg/redl)
  * [limit-break ★16 ⏳4Y](https://github.com/technomancy/limit-break)
  * [spyscope ★371](https://github.com/dgrnbrg/spyscope)
  * [aprint ★104 ⏳1Y](https://github.com/razum2um/aprint)
  * [pretty ★331](https://github.com/AvisoNovate/pretty)
  * [prone ★436](https://github.com/magnars/prone)
  * [figwheel ★2105](https://github.com/bhauman/lein-figwheel)

## CI

  * [lambdacd ★449](https://github.com/flosell/lambdacd)

## Guides

  * [Clojure Distilled](http://yogthos.github.io/ClojureDistilled.html)
  * [clojure-cookbook ★1777](https://github.com/clojure-cookbook/clojure-cookbook)
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
  * [Wonderland Clojure Katas ★495](https://github.com/gigasquid/wonderland-clojure-katas)
  * [Clojure Katas](http://clojurekatas.org)
  * [4clojure](http://www.4clojure.com/)
  * [exercism.io](http://exercism.io/languages/clojure)

## Project Management
  
  * [milestones](https://github.com/turbopape/milestones)
---
<p align="center">
	This list is a copy of <a href="https://github.com/razum2um/awesome-clojure">https://github.com/razum2um/awesome-clojure</a> with ranks
</p>
