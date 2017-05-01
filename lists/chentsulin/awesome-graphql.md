# awesome-graphql [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg) ★57421](https://github.com/sindresorhus/awesome)

> Awesome list of GraphQL & Relay

If you want to contribute to this list (please do), send me a pull request.

## Table of Contents

<!-- MarkdownTOC depth=4 -->

- [Specification](#spec)
- [Community](#community)
- [Libraries](#lib)
	- [Javascript](#lib-js)
	- [Ruby](#lib-rb)
	- [PHP](#lib-php)
	- [Python](#lib-py)
	- [Java](#lib-java)
	- [C/C++](#lib-c)
	- [Go](#lib-go)
	- [Scala](#lib-scala)
	- [.NET](#lib-dotnet)
	- [Elixir](#lib-elixir)
	- [Haskell](#lib-haskell)
	- [SQL](#lib-sql)
	- [Lua](#lib-lua)
	- [Elm](#lib-elm)
	- [Clojure](#lib-clojure)
	- [ClojureScript](#lib-clojurescript)
	- [Swift](#lib-swift)
	- [OCaml](#lib-ocaml)
	- [Rust](#lib-rust)
- [Tools](#tools)
- [Services](#services)
- [Databases](#databases)
- [Examples](#example)
	- [Javascript](#example-js)
	- [Typescript](#example-ts)
	- [Ruby](#example-rb)
	- [Go](#example-go)
	- [Scala](#example-scala)
	- [Python](#example-python)
	- [Elixir](#example-elixir)
- [Videos](#video)
- [Blogs](#blogs)
- [Posts](#post)
- [Workshoppers](#workshopper)

<!-- /MarkdownTOC -->

<a name="spec" />

## Specification

* [facebook/graphql](http://facebook.github.io/graphql/) - Working Draft of the Specification for GraphQL created by Facebook.

<a name="community" />

## Community

* [Slack](http://graphql.slack.com/messages/general/) - Share and help people on the chat. Get your invite [here](https://graphql-slack.herokuapp.com/)
* [`#graphql` on Freenode](https://webchat.freenode.net/?channels=#graphql) - The official IRC channel for GraphQL
* [Facebook](https://www.facebook.com/groups/795330550572866/) - Group for discussions, articles and knowledge sharing
* [Twitter](https://twitter.com/search?q=%23GraphQL) - Use the hashtag [#graphql](https://twitter.com/search?q=%23GraphQL)
* [StackOverflow](http://stackoverflow.com/questions/tagged/graphql) - Questions and answers. Use the tag [graphql](http://stackoverflow.com/questions/tagged/graphql)
* [GraphQL APIs ★165](https://github.com/APIs-guru/graphql-apis) - A collective list of public GraphQL APIs
* [GraphQL World](https://graphql-world.com) - The fastest growing community of GraphQL developers

<a name="meetups" />

## GraphQL Meetups

* [Berlin](https://www.meetup.com/graphql-berlin)
* [London](https://www.meetup.com/GraphQL-London)
* [Melbourne](https://www.meetup.com/GraphQL-Melbourne)
* [San Francisco](https://www.meetup.com/GraphQL-SF)
* [Tel Aviv](https://www.meetup.com/GraphQL-TLV)

<a name="lib" />

## Libraries

<a name="lib-js" />

### JavaScript Libraries

* [GraphQL.js ★6358](https://github.com/graphql/graphql-js) - A reference implementation of GraphQL for JavaScript.
* [express-graphql ★1878](https://github.com/graphql/express-graphql) - GraphQL Express Middleware.
* [koa-graphql ★329](https://github.com/chentsulin/koa-graphql) - GraphQL Koa Middleware.
* [hapi-graphql ★84](https://github.com/SimonDegraeve/hapi-graphql) - Create a GraphQL HTTP server with Hapi.
* [codemirror-graphql ★50](https://github.com/graphql/codemirror-graphql) - GraphQL mode and helpers for CodeMirror.
* [graphql-schema ★114](https://github.com/devknoll/graphql-schema) - Create GraphQL schemas with a fluent/chainable interface.
* [graphql-sequelize ★600](https://github.com/mickhansen/graphql-sequelize) - Sequelize helpers for GraphQL.
* [graffiti ★1041](https://github.com/RisingStack/graffiti) - Node.js GraphQL ORM.
* [graffiti-mongoose](https://github.com/RisingStack/graffiti-mongoose) - Mongoose (MongoDB) adapter for graffiti (Node.js GraphQL ORM).
* [babel-plugin-graphql ★60](https://github.com/ooflorent/babel-plugin-graphql) - Babel plugin that compile GraphQL tagged template strings.
* [adrenaline ★698](https://github.com/gyzerok/adrenaline) - React bindings for Redux with Relay in mind.
* [graphql-bookshelf ★140](https://github.com/brysgo/graphql-bookshelf) - Some help defining GraphQL schema around BookshelfJS models.
* [graphql-bookshelfjs ★7](https://github.com/weyoss/graphql-bookshelfjs) - A simple bridge between your graphql queries and your bookshelf models, perform batched and optimised queries.
* [graph.ql ★483](https://github.com/matthewmueller/graph.ql) - Faster and simpler technique for creating and querying GraphQL schemas.
* [react-reach ★107](https://github.com/kennetpostigo/react-reach) - A library to communicate with Graphql through Redux
* [Lokka ★914](https://github.com/kadirahq/lokka) - Simple JavaScript client for GraphQL, which you can use anywhere.
* [Strapi](http://strapi.io/documentation/graphql) - Open-source Node.js framework that supports "GraphQL" out of the box.
* [GraysQL ★22](https://github.com/larsbs/graysql) - A GraphQL manager and loader.
* [graysql-orm-loader ★5](https://github.com/larsbs/graysql-orm-loader) - A GraysQL extension to load a GraphQL schema from an ORM.
* [Annotated GraphQL](https://github.com/almilo/annotated-graphql) - Proof of Concept for annotations in GraphQL (i.e.: transform an existing REST api into a GraphQL endpoint).
* [Apollo Client ★2598](https://github.com/apollographql/apollo-client) - A well-documented GraphQL client that integrates with Redux. Has React and Angular bindings.
* [graphql-tools ★668](https://github.com/apollographql/graphql-tools) - Tool library for building and maintaining GraphQL-JS servers.
* [graphql-anywhere ★398](https://github.com/apollographql/graphql-anywhere) - Run a GraphQL query anywhere, against any data, with no schema.
* [graphql-tag ★229](https://github.com/apollographql/graphql-tag) - A JavaScript template literal tag that parses GraphQL queries.
* [modelizr ★130](https://github.com/julienvincent/modelizr) - A library for simplifying the process of writing GraphQL queries, mocking them and normalizing their responses.
* [vue-apollo ★440](https://github.com/Akryum/vue-apollo) - Vue integration for apollo.
* [graphql-thinky ★42](https://github.com/fenos/graphql-thinky) - Build an optimized GraphQL schema from Thinky RethinkDB models.
* [graphql-pouch ★98](https://github.com/MikeBild/graphql-pouch) - A GraphQL-API runtime on top of PouchDB created by GraphQL shorthand notation as a self contained service with CouchDB synchronization.
* [gql-tools ★10](https://github.com/almilo/gql-tools) - Tool library with CLI for schema generation and manipulation.
* [graphql-iso-date ★27](https://github.com/excitement-engineer/graphql-iso-date) - A GraphQL date scalar type to be used with GraphQL.js. This scalar represents a date in the ISO 8601 format YYYY-MM-DD.
* [graphql-compose ★134](https://github.com/nodkz/graphql-compose) - Tool which allows you to construct flexible graphql schema from different data sources via plugins.
* [node-graphjoiner ★21](https://github.com/mwilliamson/node-graphjoiner) - Create GraphQL APIs using joins, SQL or otherwise.
* [FetchQL ★71](https://github.com/gucheen/FetchQL) - GraphQL query client with Fetch
* [Join Monster ★516](https://github.com/stems/join-monster) - A GraphQL-to-SQL query execution layer for batch data fetching.
* [Create-GraphQL ★214](https://github.com/lucasbento/create-graphql) - Command-line utility to build production-ready servers with GraphQL.
* [GraphQL-Pokémon ★79](https://github.com/lucasbento/graphql-pokemon) - Get information of a Pokémon with GraphQL!
* [graphql-factory](https://github.com/graphql-factory) - Create GraphQL types from JSON definitions
* [ChromeiQL](https://chrome.google.com/webstore/detail/chromeiql/fkkiamalmpiidkljmicmjfbieiclmeij) - Chrome extension to use GraphiQL anywhere
* [graphql-auto-mutation ★19](https://github.com/ejoebstl/graphql-auto-mutation) - Automatically generates functions for mutations specified in a GraphQL schema.
* [GraphiteJS ★27](https://github.com/graphitejs/graphitejs) - Full stack GraphQL framework.

##### Relay Related

* [relay ★8677](https://github.com/facebook/relay) - Relay is a JavaScript framework for building data-driven React applications.
* [graphql-relay-js ★733](https://github.com/graphql/graphql-relay-js) - A library to help construct a graphql-js server supporting react-relay.
* [sequelize-relay ★61](https://github.com/MattMcFarland/sequelize-relay) - Serverside library that connects sequelize and graphql-relay-js together.
* [babel-plugin-react-relay ★50](https://github.com/graphcool/babel-plugin-react-relay) - Babel Plugin for Relay with support for JSON & graphql-js schemas and URL endpoints.
* [babel-relay-plugin](https://www.npmjs.com/package/babel-relay-plugin) - Babel Relay Plugin for transpiling GraphQL queries for use with Relay.
* [react-router-relay ★537](https://github.com/relay-tools/react-router-relay) - Relay integration for React Router.
* [relay-local-schema ★155](https://github.com/relay-tools/relay-local-schema) - Use Relay without a GraphQL server.
* [relay-sink ★123](https://github.com/acdlite/relay-sink) - Use Relay to fetch and store data outside of a React component.
* [recompose-relay](https://github.com/acdlite/recompose/tree/master/src/packages/recompose-relay) - Recompose helpers for Relay.
* [Graylay ★22](https://github.com/larsbs/graysql#Graylay) - A GraysQL extension to create a Relay compatible Schema.
* [Apollo Client](https://github.com/apollostack/apollo-client) - A simple alternative to Relay, integrates with Redux and comes with React and Angular bindings.
* [react-relay-network-layer](https://github.com/nodkz/react-relay-network-layer) - A network layer for Relay with query batching and middleware support (urlThunk, retryThunk, auth, defer and other).
* [relay-subscriptions ★170](https://github.com/edvinerikson/relay-subscriptions) - Subscription support for Relay.
* [Portfolio Relay Example ★6](https://github.com/alex-cory/portfolio) - An example website that fetches data from various apis and uses Relay and GraphQL to feed the data to React components!
* [Relay Pokédex ★40](https://github.com/lucasbento/react-relay-pokemon) - Project using GraphQL Pokémon to show how powerful Relay is.

<a name="lib-rb" />

### Ruby Libraries

* [graphql-ruby ★1677](https://github.com/rmosolgo/graphql-ruby) - Ruby implementation of Facebook's GraphQL.
* [graphql-parser ★37](https://github.com/Shopify/graphql-parser) - A small ruby gem wrapping the libgraphqlparser C library for parsing GraphQL.
* [graphql-client ★317](https://github.com/github/graphql-client) - A Ruby library for declaring, composing and executing GraphQL queries.
* [graphql-batch ★265](https://github.com/Shopify/graphql-batch) - A query batching executor for the graphql gem.

<a name="lib-php" />

### PHP Libraries

* [graphql-php ★879](https://github.com/webonyx/graphql-php) - A PHP port of GraphQL reference implementation.
* [graphql-relay-php ★57](https://github.com/ivome/graphql-relay-php) - Relay helpers for GraphQL & PHP.
* [laravel-graphql ★448](https://github.com/Folkloreatelier/laravel-graphql) - Facebook GraphQL for Laravel 5.
* [laravel-graphql-relay ★38](https://github.com/nuwave/laravel-graphql-relay) - A Laravel library to help construct a server supporting react-relay.
* [graphql-mapper ★28](https://github.com/4rthem/graphql-mapper) - This library allows to build a GraphQL schema based on your model.
* [graphql-bundle ★27](https://github.com/suribit/GraphQLBundle) - GraphQL Bundle for Symfony 2.
* [overblog/graphql-bundle ★104](https://github.com/overblog/GraphQLBundle) - This bundle provides tools to build a complete GraphQL server in your Symfony App. Supports react-relay.
* [GraphQL ★351](https://github.com/Youshido/GraphQL) – Well documented PHP implementation with no dependencies.
* [GraphQL Symfony Bundle](https://github.com/Youshido/GraphQLBundle) – GraphQL Bundle for the Symfony 3 (supports 2.6+).
* [WPGraphQL ★20](https://github.com/wp-graphql/wp-graphql) - WordPress plugin that exposes a Relay compliant GraphQL endpoint
* [graphql-wp ★181](https://github.com/tim-field/graphql-wp) – a WordPress plugin that exposes a GraphQL endpoint.
* [eZ Platform GraphQL Bundle](https://www.symfony.fi/entry/graphql-bundle-adds-protocol-support-to-ez-platform-symfony-cms) - GraphQL Bundle for the eZ Platform Symfony CMS.
* [GraphQL Middleware ★1](https://github.com/stefanorg/graphql-middleware) - GraphQL Psr7 Middleware
* [Zend Expressive GraphiQL Extension ★0](https://github.com/stefanorg/zend-expressive-graphiql) - GraphiQL extension for zend expressive

<a name="lib-py" />

### Python Libraries

* [graphql-parser ★38](https://github.com/tryolabs/graphql-parser) - GraphQL parser for Python.
* [graphql-core ★139](https://github.com/graphql-python/graphql-core) - GraphQL implementation for Python.
* [graphql-relay-py ★80](https://github.com/graphql-python/graphql-relay-py) - A library to help construct a graphql-py server supporting react-relay.
* [graphql-parser-python ★3](https://github.com/tallstreet/graphql-parser-python) - A python wrapper around libgraphqlparser.
* [graphene ★1652](https://github.com/graphql-python/graphene) - A package for creating GraphQL schemas/types in a Pythonic easy way.
* [graphene-gae](https://github.com/graphql-python/graphene-gae) - Adds GraphQL support to Google AppEngine (GAE).
* [django-graphiql ★32](https://github.com/graphql-python/django-graphiql) - Integrate GraphiQL easily into your Django project.
* [flask-graphql ★151](https://github.com/graphql-python/flask-graphql) - Adds GraphQL support to your Flask application.
* [python-graphql-client ★4](https://github.com/graphcool/python-graphql-client) - Simple GraphQL client for Python 2.7+
* [python-graphjoiner ★18](https://github.com/healx/python-graphjoiner) - Create GraphQL APIs using joins, SQL or otherwise.
* [graphene-django ★330](https://github.com/graphql-python/graphene-django) - A Django integration for Graphene.

<a name="lib-java" />

### Java Libraries

* [graphql-java ★1089](https://github.com/graphql-java/graphql-java) - GraphQL Java implementation.
* [graphql-java-type-generator ★19](https://github.com/graphql-java/graphql-java-type-generator) - Auto-generates types for use with GraphQL Java
* [schemagen-graphql ★23](https://github.com/bpatters/schemagen-graphql) - Schema generation and execution package that turns POJO's into a GraphQL Java queryable set of objects. Enables exposing any service as a GraphQL service using Annotations.
* [graphql-java-annotations ★82](https://github.com/graphql-java/graphql-java-annotations) - Provides annotations-based syntax for schema definition with GraphQL Java.
* [spring-graphql-common ★60](https://github.com/oembedler/spring-graphql-common) - Spring Framework GraphQL Library.
* [graphql-spring-boot ★10](https://github.com/graphql-java/graphql-spring-boot) - GraphQL and GraphiQL Spring Framework Boot Starters.
* [vertx-graphql-service-discovery ★9](https://github.com/engagingspaces/vertx-graphql-service-discovery) - Asynchronous GraphQL service discovery and querying for your microservices.
* [vertx-dataloader ★23](https://github.com/engagingspaces/vertx-dataloader) - Port of Facebook DataLoader for efficient, asynchronous batching and caching in clustered GraphQL environments

<a name="lib-c" />

### C/C++ Libraries

* [libgraphqlparser ★373](https://github.com/graphql/libgraphqlparser) - A GraphQL query parser in C++ with C and C++ APIs.

<a name="lib-go" />

### Go Libraries

* [graphql ★1270](https://github.com/graphql-go/graphql) - An implementation of GraphQL for Go follows graphql-js
* [graphql-relay-go ★163](https://github.com/graphql-go/relay) - A Go/Golang library to help construct a server supporting react-relay.
* [graphql-go ★451](https://github.com/neelance/graphql-go) - GraphQL server with a focus on ease of use.
* [c-graphqlparser ★25](https://github.com/tecbot/c-graphqlparser) - Go-gettable version of the libgraphqlparser C library for parsing GraphQL.
* [tallstreet-graphql ★14](https://github.com/tallstreet/graphql) - GraphQL parser and server for Go that leverages libgraphqlparser
* [go-graphql ★104](https://github.com/playlyfe/go-graphql) - A powerful GraphQL server implementation for Golang

<a name="lib-scala" />

### Scala Libraries

* [sangria ★681](https://github.com/sangria-graphql/sangria) - Scala GraphQL client and server library.
* [sangria-relay ★50](https://github.com/sangria-graphql/sangria-relay) - Sangria Relay Support.
* [graphql-scala ★5](https://github.com/hrosenhorn/graphql-scala) - An attempt to get GraphQL going with Scala.

<a name="lib-dotnet" />

### .NET Libraries

* [graphql-dotnet ★801](https://github.com/graphql-dotnet/graphql-dotnet) - GraphQL for .NET.
* [graphql-net ★245](https://github.com/ckimes89/graphql-net) - GraphQL to IQueryable for .NET
* [FSharp.Data.GraphQL ★73](https://github.com/fsprojects/FSharp.Data.GraphQL) - FSharp GraphQL.

<a name="lib-elixir" />

### Elixir Libraries

* [absinthe-graphql ★870](https://github.com/absinthe-graphql/absinthe) - Fully Featured Elixir GraphQL Library.
* [graphql-elixir ★644](https://github.com/graphql-elixir/graphql) - GraphQL Elixir.
* [plug_graphql ★114](https://github.com/graphql-elixir/plug_graphql) - Plug integration for GraphQL Elixir.
* [graphql_relay ★30](https://github.com/graphql-elixir/graphql_relay) - Relay helpers for GraphQL Elixir.
* [graphql_parser](https://github.com/graphql-elixir/graphql_parser) - Elixir bindings for [libgraphqlparser ★373](https://github.com/graphql/libgraphqlparser)
* [graphql ★87](https://github.com/asonge/graphql) - Elixir GraphQL parser.
* [plot ★27](https://github.com/peburrows/plot) - GraphQL parser and resolver for Elixir.

<a name="lib-haskell" />

### Haskell Libraries

* [graphql-haskell ★109](https://github.com/jdnavarro/graphql-haskell) - GraphQL AST and parser for Haskell.

<a name="lib-sql" />

### SQL Libraries

* [GraphpostgresQL ★944](https://github.com/solidsnack/GraphpostgresQL) - GraphQL for Postgres.
* [sql-to-graphql ★266](https://github.com/rexxars/sql-to-graphql) - Generate a GraphQL API based on your SQL database structure.
* [PostGraphQL](https://github.com/calebmer/postgraphql) - A GraphQL schema created by reflection over a PostgreSQL schema.

<a name="lib-lua" />

### Lua Libraries

* [graphql-lua ★55](https://github.com/bjornbytes/graphql-lua) - GraphQL for Lua.

<a name="lib-elm" />

### Elm Libraries

* [elm-graphql ★248](https://github.com/jahewson/elm-graphql) - GraphQL for Elm.

<a name="lib-clojure" />

### Clojure Libraries

* [graphql-clj ★197](https://github.com/tendant/graphql-clj) - A Clojure library designed to provide GraphQL implementation.
* [lacinia ★441](https://github.com/walmartlabs/lacinia) - GraphQL implementation in pure Clojure.

<a name="lib-clojurescript" />
### ClojureScript Libraries

* [speako ★4](https://github.com/johanatan/speako) - A ClojureScript/NPM compiler for GraphQL Schema Language.

<a name="lib-swift" />

### Swift Libraries

* [GraphQL ★264](https://github.com/GraphQLSwift/GraphQL) - The Swift implementation for GraphQL.

<a name="lib-ocaml" />

### OCaml Libraries

* [ocaml-graphql-server ★75](https://github.com/andreas/ocaml-graphql-server) - GraphQL servers in OCaml.

<a name="lib-rust" />

### Rust Libraries

* [juniper ★223](https://github.com/mhallin/juniper) - GraphQL server library for Rust.

<a name="tools" />

## Tools

* [graphiql ★2880](https://github.com/graphql/graphiql) - An in-browser IDE for exploring GraphQL.
* [GraphiQL.app ★550](https://github.com/skevy/graphiql-app) - A light, Electron-based wrapper around GraphiQL.
* [GraphQLviz](https://github.com/Macroz/GraphQLviz) - GraphQLviz marries GraphQL (schemas) with Graphviz.
* [graphqlviz ★187](https://github.com/sheerun/graphqlviz) - GraphQL API visualizer in Node.js
* [Relay Playground](http://facebook.github.io/relay/prototyping/playground.html)
* [GraphQL AST Explorer](http://dferber90.github.io/graphql-ast-explorer/) - Explore the AST of a GraphQL document interactively
* [GraphQLHub](https://www.graphqlhub.com/) - Query public API's schemas (e.g. Reddit, Twitter, Github, etc) using GraphiQL
* [js-graphql-intellij-plugin ★136](https://github.com/jimkyndemeyer/js-graphql-intellij-plugin) - GraphQL language support for IntelliJ IDEA and WebStorm, including Relay.QL tagged templates in JavaScript and TypeScript.
* [gdom ★849](https://github.com/syrusakbary/gdom) - DOM Traversing and Scraping using GraphQL.
* [Annotated GraphQL Server ★8](https://github.com/almilo/annotated-graphql-server) - Server for annotated GraphQL showing how to transform a REST api into a GraphQL endpoint with annotations.
* [Model Visualizer](http://nathanrandal.com/graphql-visualizer/) - A small webapp that generates an ERD-like visualization of a GraphQL endpoint from an introspection query.
* [GraphQL Network ★104](https://github.com/Ghirro/graphql-network) - A chrome dev-tools extension for debugging GraphQL network requests.
* [eslint-plugin-graphql ★238](https://github.com/apollographql/eslint-plugin-graphql) - An ESLint plugin that checks your GraphQL strings against a schema.
* [AST Explorer](https://astexplorer.net/) - Select "GraphQL" at the top, explore the GraphQL AST and highlight different parts by clicking in the query.
* [vim-graphql ★32](https://github.com/jparise/vim-graphql) - A Vim plugin that provides GraphQL file detection and syntax highlighting.
* [GraphQL CMS ★159](https://github.com/sarkistlt/graphql-auto-generating-cms) - Use your existing GraphQL schema to generate simple for use, fully functional CMS in a couple steps.
* [graphdoc ★86](https://github.com/2fd/graphdoc) - Static page generator for documenting GraphQL Schema.
* [graphql-autocomplete ★24](https://github.com/orionsoft/atom-graphql-autocomplete) - Autocomplete and lint from a GraphQL endpoint in Atom.
* [GraphQL IDE ★361](https://github.com/redound/graphql-ide) - An extensive IDE for exploring GraphQL API's.
* [Swagger to GraphQL ★69](https://github.com/yarax/swagger-to-graphql) - GraphQL types builder based on REST API described in Swagger. Allows to migrate to GraphQL from REST for 5 minutes
* [GraphQL Voyager ★1546](https://github.com/APIs-guru/graphql-voyager) - Represent any GraphQL API as an interactive graph.
* [GraphQL Docs](https://graphql-docs.com) - Instantly create beautiful GraphQL API docs hosted online.
* [GraphQL Faker ★136](https://github.com/APIs-guru/graphql-faker) - 🎲 Mock or extend your GraphQL API with faked data. No coding required.

<a name="databases" />

## Databases

* [Dgraph](https://dgraph.io/) - Scalable, distributed, low latency, high throughput Graph database with GraphQL as the query language

<a name="services" />

## Services

* [GraphCMS](https://graphcms.com/) - GraphQL based Headless Content Management System.
* [Graphcool](https://www.graph.cool/) - Your own GraphQL backend in under 5 minutes. Works with every GraphQL client such as Relay and Apollo.
* [Reindex](https://www.reindex.io/) - Instant GraphQL Backend for Your React Apps.
* [Scaphold](https://scaphold.io/) - GraphQL as a service that includes API integrations such as Stripe and Mailgun.

<a name="example" />

## Examples

<a name="example-js" />

### JavaScript Examples

* [relay-starter-kit ★962](https://github.com/relayjs/relay-starter-kit) - Barebones starting point for a Relay application.
* [react-starter-kit ★13688](https://github.com/kriasoft/react-starter-kit) - Isomorphic web app boilerplate (Node.js/Express, GraphQL, React)
* [nodejs-api-starter ★404](https://github.com/kriasoft/nodejs-api-starter) - Boilerplate and tooling for authoring data API backends with Node.js and GraphQL
* [swapi-graphql ★348](https://github.com/graphql/swapi-graphql) - A GraphQL schema and server wrapping [swapi](http://swapi.co/).
* [graphql-server](https://github.com/RisingStack/graphql-server) - GraphQL server with Mongoose (MongoDB) and Node.js.
* [graphql-intro ★73](https://github.com/clayallsopp/graphql-intro) - https://medium.com/the-graphqlhub/your-first-graphql-server-3c766ab4f0a2
* [graphql-aws ★60](https://github.com/jonsharratt/graphql-aws) - Amazon AWS GraphQL API Server.
* [graffiti-todo ★52](https://github.com/RisingStack/graffiti-todo) - Example Relay TodoMVC application using graffiti-mongoose.
* [devknoll/gist:8b274f1c5d05230bfade](https://gist.github.com/devknoll/8b274f1c5d05230bfade)
* [UniversalRelayBoilerplate ★418](https://github.com/codefoundries/UniversalRelayBoilerplate)
Boilerplate + examples for React Native (iOS, Android), React (isomorphic, Material-UI), Relay, GraphQL, JWT, Node.js, Apache Cassandra.
* [vslinko/ripster](https://github.com/vslinko/ripster/tree/master/src/graphql)
* [relay-skeleton ★121](https://github.com/fortruce/relay-skeleton) - React, Relay, GraphQL project skeleton
* [simple-relay-starter ★149](https://github.com/mhart/simple-relay-starter) - A very simple starter for React Relay using Browserify.
* [relay-chat ★87](https://github.com/transedward/relay-chat) - an chat example showing Relay with routing and pagination.
* [relay-todomvc ★115](https://github.com/taion/relay-todomvc) - Relay TodoMVC with routing.
* [graphql-express-sqlite ★41](https://github.com/mrblueblue/graphql-express-sqlite) - GraphQL server with Sqlite and Express
* [koa-graphql-relay-example](https://github.com/chentsulin/koa-graphql-relay-example) - Example of [koa-graphql ★329](https://github.com/chentsulin/koa-graphql)
* [relay-fullstack ★722](https://github.com/lvarayut/relay-fullstack) - Relay Starter Kit integrated with Relay, GraphQL, Express, ES6/ES7, JSX, Webpack, Babel, Material Design Lite, and PostCSS.
* [serverless-graphql-blog ★554](https://github.com/serverless/serverless-graphql-blog) - A Serverless Blog leveraging GraphQL to offer a REST API with only 1 endpoint
* [relay-cart ★15](https://github.com/soonlive/relay-cart) - A simple shopping cart example leveraging relay & GraphQL with routing and pagination.
* [graphql-loader ★34](https://github.com/applification/graphql-loader) - Example project to illustrate GraphQL, Express and Facebook DataLoader to connect to third party REST API
* [swapi-graphql-lambda ★12](https://github.com/alvinthen/swapi-graphql-lambda) - A GraphQL schema hosted in AWS Lambda wrapping http://swapi.co/
* [Apollo Client documentation](http://dev.apollodata.com/react/) - Documentation and example for building GraphQL apps using apollo client
* [Apollo Server tools documentation](http://dev.apollodata.com/tools/) - Documentation, tutorial and examples for building GraphQL server and connecting to SQL, MongoDB and REST endpoints.
* [f8-apollo ★87](https://github.com/nnance/f8app-apollo) - Refactored version of the official F8 app of 2016, powered by React Native and the Apollo Stack.
* [f8app ★9493](https://github.com/fbsamples/f8app) - Source code of the official F8 app of 2016, powered by React Native and other Facebook open source projects. [http://makeitopen.com](http://makeitopen.com)
* [Reindex Examples ★128](https://github.com/reindexio/reindex-examples) - Example projects for Reindex with using React Native and React.js for web.
* [Modelizr Documentation](https://julienvincent.github.io/modelizr/) - Documentation and Usage Examples for modelizr
* [Vue Apollo Example ★50](https://github.com/Akryum/frontpage-vue-app) - Apollo example project for Vue 2.0.
* [angular2-graphql-rest ★24](https://github.com/kamilkisiela/angular2-graphql-rest) - An example app with REST Api working side by side with GraphQL using Apollo Client with angular2-apollo. Includes step-by-step tutorial how to migrate from REST to GraphQL.
* [GraphQL-DataLoader-Boilerplate ★109](https://github.com/entria/graphql-dataloader-boilerplate) - Boilerplate to start your GraphQL with DataLoader server
* [GraphQL-CEP ★7](https://github.com/sibelius/graphql-cep) - Query address by CEP
* [Apollo React example for Github GraphQL API ★48](https://github.com/katopz/react-apollo-graphql-github-example) - Usage Examples Apollo React for Github GraphQL API with create-react-app
* [Intuitive GraphQL Resolver Example](https://github.com/xpepermint/graphql-example) - GraphQL application example using [RawModel.js ★43](https://github.com/xpepermint/rawmodeljs).
* [ReactQL starter kit](https://reactql.org) - Universal React + Apollo + Redux + React Router 4, with SSR-enabled GraphQL, store (de/re)hydration and production code bundling.

<a name="example-ts" />

### TypeScript Examples
* [Basic Apollo Server ★51](https://github.com/DxCx/webpack-graphql-server) - Basic Starter for Apollo Server, Using typescript and Webpack.

<a name="example-rb" />

### Ruby Examples

* [graphql-ruby-demo ★151](https://github.com/rmosolgo/graphql-ruby-demo) - Use graphql-ruby to expose a Rails app.
* [github-graphql-rails-example ★145](https://github.com/github/github-graphql-rails-example) - Example Rails app using GitHub's GraphQL API.
* [relay-on-rails ★35](https://github.com/nethsix/relay-on-rails) - Barebones starter kit for Relay application with Rails GraphQL server.
* [relay-rails-blog ★91](https://github.com/gauravtiwari/relay-rails-blog) - A graphql, relay and standard rails application powered demo weblog.
* [to_eat_app] (https://github.com/jcdavison/to_eat_app) - A sample graphql/rails/relay application with a related 3-part article series.

<a name="example-go" />

### Go Examples

* [golang-relay-starter-kit ★71](https://github.com/sogko/golang-relay-starter-kit) - Barebones starting point for a Relay application with Golang GraphQL server.
* [golang-graphql-playground ★52](https://github.com/graphql-go/playground) - An example Golang GraphQL server written with graphql-go and graphql-relay-go. Try live demo at: http://golanggraphqlplayground-sogko.rhcloud.com
* [todomvc-relay-go ★36](https://github.com/sogko/todomvc-relay-go) - Port of the React/Relay TodoMVC app, driven by a Golang GraphQL backend.

<a name="example-scala" />

### Scala Examples

* [sangria-akka-http-example ★102](https://github.com/sangria-graphql/sangria-akka-http-example) - An example GraphQL server written with akka-http and [sangria](http://sangria-graphql.org)
* [sangria-playground ★35](https://github.com/sangria-graphql/sangria-playground) - An example of GraphQL server written with Play and sangria.

<a name="example-python" />

### Python Examples

* [swapi-graphene ★117](https://github.com/graphql-python/swapi-graphene) - A GraphQL schema and server using [Graphene](http://graphene-python.org) - [View demo online](http://swapi.graphene-python.org).

<a name="example-elixir" />

### Elixir Examples

* [absinthe_example ★28](https://github.com/absinthe-graphql/absinthe_example) - Example usage of Absinthe GraphQL
* [hello_graphql_phoenix ★77](https://github.com/graphql-elixir/hello_graphql_phoenix) - Examples of GraphQL Elixir Plug endpoints mounted in Phoenix - [View demo online](http://playground.graphql-elixir.org).

<a name="video" />

## Videos

* [Zero to GraphQL in 30 Minutes](https://www.youtube.com/embed/UBGzsb2UkeY)
* [Data fetching for React applications at Facebook](https://www.youtube.com/watch?v=9sc8Pyc51uU)
* [React Native & Relay: Bringing Modern Web Techniques to Mobile](https://www.youtube.com/watch?v=X6YbAKiLCLU)
* [Exploring GraphQL](https://www.youtube.com/watch?v=WQLzZf34FJ8)
* [Creating a GraphQL Server](https://www.youtube.com/watch?v=gY48GW87Feo)
* [GraphQL at The Financial Times](https://www.youtube.com/watch?v=S0s935RKKB4)
* [Relay: An Application Framework For React](https://www.youtube.com/watch?v=IrgHurBjQbg)
* [Building and Deploying Relay with Facebook](https://www.youtube.com/watch?t=643&v=Pxdgu2XIAAg)
* [Introduction to GraphQL](https://vimeo.com/144817545)
* [Exploring GraphQL@Scale](https://www.youtube.com/watch?v=_9RgHXqH8J0)
* [What's Next for Phoenix by Chris McCord](https://www.youtube.com/watch?v=IMUpYOc9z3c&feature=youtu.be)
* [GraphQL with Nick Schrock](https://www.youtube.com/watch?v=Ed6oJXKt3-M)
* [Build a GraphQL server for Node.js using PostgreSQL/MySQL](https://www.youtube.com/watch?v=DNPVqK_woRQ)
* [GraphQL server tutorial for Node.js with SQL, MongoDB and REST](https://www.youtube.com/watch?v=PHabPhgRUuU)
* [JavaScript Air Episode 023: Transitioning from REST to GraphQL](https://www.youtube.com/watch?v=ENqDNIp1Nd8)
* [GraphQL Future at react-europe 2016](https://www.youtube.com/watch?v=ViXL0YQnioU)
* [GraphQL at Facebook at react-europe 2016](https://www.youtube.com/watch?v=etax3aEe2dA)
* [Building native mobile apps with GraphQL at react-europe 2016](https://www.youtube.com/watch?v=z5rz3saDPJ8)

<a name="blogs" />

## Blogs
* [Official GraphQL blog](http://graphql.org/blog/)
* [Building Apollo](https://dev-blog.apollodata.com/)

<a name="post" />

## Posts

* [Using DataLoader to batch GraphQL requests](http://gajus.com/blog/9/using-dataloader-to-batch-requests)
* [Introducing Relay and GraphQL](https://facebook.github.io/react/blog/2015/02/20/introducing-relay-and-graphql.html)
* [GraphQL Introduction](https://facebook.github.io/react/blog/2015/05/01/graphql-introduction.html)
* [Unofficial Relay FAQ](https://gist.github.com/wincent/598fa75e22bdfa44cf47)
* [Your First GraphQL Server](https://medium.com/@clayallsopp/your-first-graphql-server-3c766ab4f0a2)
* [GraphQL Overview - Getting Started with GraphQL and Node.js](https://blog.risingstack.com/graphql-overview-getting-started-with-graphql-and-nodejs/)
* [4 Reasons you should try out GraphQL](https://medium.freecodecamp.com/introduction-to-graphql-1d8011b80159)
* [Moving from REST to GraphQL](https://medium.com/@frikille/moving-from-rest-to-graphql-e3650b6f5247)
* [Writing a Basic API with GraphQL](http://davidandsuzi.com/writing-a-basic-api-with-graphql/)
* [Start using GraphQL with Graffiti](https://blog.risingstack.com/start-using-graphql-with-graffiti/?utm_source=nodeweekly&utm_medium=email)
* [Building a GraphQL Server with Node.js and SQL](https://www.reindex.io/blog/building-a-graphql-server-with-node-js-and-sql/)
* [GraphQL at The Financial Times](https://www.slideshare.net/LondonReact/graph-ql)
* [Relay for visual learners](http://sgwilym.github.io/relay-visual-learners/)
* [Relay and Routing](https://medium.com/@cpojer/relay-and-routing-36b5439bad9)
* [Learn Golang + GraphQL + Relay, Part 1: Your first Golang GraphQL server](https://wehavefaces.net/learn-golang-graphql-relay-1-e59ea174a902)
* [Learn Golang + GraphQL + Relay, Part 2: Your first Relay application](https://wehavefaces.net/learn-golang-graphql-relay-2-a56cbcc3e341)
* [From REST to GraphQL](https://0x2a.sh/from-rest-to-graphql-b4e95e94c26b)
* [GraphQL: A data query language](http://graphql.org/blog/graphql-a-query-language/)
* [Subscriptions in GraphQL and Relay](http://graphql.org/blog/subscriptions-in-graphql-and-relay/)
* [Relay 101: Building A Hacker News Client](https://medium.com/@clayallsopp/relay-101-building-a-hacker-news-client-bb8b2bdc76e6)
* [GraphQL Shorthand Notation Cheatsheet](https://wehavefaces.net/graphql-shorthand-notation-cheatsheet-17cd715861b6)
* [The GitHub GraphQL API](https://githubengineering.com/the-github-graphql-api/)
* [Github GraphQL API React Example](https://medium.com/@katopz/github-graphql-api-react-example-eace824d7b61)
* [Testing a GraphQL Server using Jest](https://medium.com/entria/testing-a-graphql-server-using-jest-4e00d0e4980e)
* [How to implement viewerCanSee in  GraphQL](https://medium.com/entria/how-to-implement-viewercansee-in-graphql-78cc48de7464)

<a name="workshopper" />

## Workshoppers

* [learning-graphql ★499](https://github.com/mugli/learning-graphql) - An attempt to learn GraphQL.
* [Let's Learn GraphQL](https://learngraphql.com) - Lessons/walkthrough of GraphQL concepts.
* [Learn Relay](https://www.learnrelay.org/) - A comprehensive introduction to Relay
* [Learn Apollo](https://www.learnapollo.com/) - A hands-on tutorial for Apollo GraphQL Client

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Chen-Tsu Lin](https://github.com/chentsulin) has waived all copyright and related or neighboring rights to this work.
