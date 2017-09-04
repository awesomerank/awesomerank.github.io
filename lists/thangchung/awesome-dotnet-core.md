---
layout: default
title: Awesome Rank for thangchung/awesome-dotnet-core
---

<p align="center">
	This list is a copy of <a href="https://github.com/thangchung/awesome-dotnet-core">thangchung/awesome-dotnet-core</a> with ranks
</p>
---
# Awesome .NET Core [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg) ★63835](https://github.com/sindresorhus/awesome)

> A collection of awesome [.NET Core](#frameworks-libraries-and-tools) frameworks, libraries, tools, resources and software.

Inspired by [awesome](https://github.com/sindresorhus/awesome), [awesome-dotnet](https://github.com/quozd/awesome-dotnet),  [awesome-nodejs](https://github.com/sindresorhus/awesome-nodejs), [frontend-dev-bookmarks ★22372](https://github.com/dypsilon/frontend-dev-bookmarks).

Contributions are always welcome! Please take a look at the [contribution guidelines](https://github.com/thangchung/awesome-dotnet-core/blob/master/contributing.md) pages first. We accept proprietary and commercial software too.

Thanks to all [contributors](https://github.com/thangchung/awesome-dotnet-core/graphs/contributors), you're awesome and wouldn't be possible without you! The goal is to build a categorized community-driven collection of very well-known resources.

## Contents

* [General](#general)
* [Frameworks, Libraries and Tools](#frameworks-libraries-and-tools)  
  * [API](#api)
  * [Application Frameworks](#application-frameworks)
  * [Application Templates](#application-templates)
  * [Authentication and Authorization](#authentication-and-authorization)
  * [Build Automation](#build-automation)
  * [Bundling and Minification](#bundling-and-minification)
  * [Caching](#caching)
  * [Cryptography](#cryptography)
  * [CMS](#cms)  
  * [Code Analysis and Metrics](#code-analysis-and-metrics)
  * [Compilers, Transpilers and Languages](#compilers-transpilers-and-languages)
  * [Database Drivers](#database-drivers)
  * [E-Commerce and Payments](#e-commerce-and-payments)
  * [Functional Programming](#functional-programming)
  * [Graphics](#graphics)
  * [GUI](#gui)
  * [IDE](#ide)
  * [Internationalization](#internationalization)
  * [IOC](#ioc)
  * [Logging](#logging)
  * [Machine Learning and Data Science](#machine-learning-and-data-science)
  * [Mail](#mail)
  * [Mathematics](#mathematics)
  * [Misc](#misc)
  * [ORM](#orm)
  * [Profiling](#profiling)
  * [Queue and Messaging](#queue-and-messaging)
  * [Scheduler and Job](#scheduler-and-job)
  * [SDKs](#sdks)
  * [Security](#security)
  * [Searching](#searching)
  * [Serialization](#serialization)
  * [Testing](#testing)
  * [Tools](#tools)
  * [Web Framework](#web-framework)
  * [Web Socket](#web-socket)
  * [Windows Service](#windows-service)
  * [Workflow](#workflow)
* [Starter Kits](#starter-kits)
* [Sample Projects](#sample-projects)
* [Articles](#articles)
* [Books](#books)
* [Videos](#videos)
* [Podcasts](#podcasts)
* [Community](#community)

## General

* [ASP.NET Core Documentation](https://docs.asp.net/en/latest/) - The official ASP.NET Core documentation site.
* [.NET Core Documentation](https://docs.microsoft.com/en-us/dotnet/articles/welcome) - Home of the technical documentation for .NET Core, C#, F# and Visual Basic, including basic concepts, getting started instructions, tutorials and samples.
* [.NET Core SDK](https://www.microsoft.com/net/core) - .NET Core SDK is a general purpose development platform maintained by Microsoft and the .NET community on [GitHub ★5012](https://github.com/dotnet/core). 
* [.NET Platform Standard](https://github.com/dotnet/corefx/blob/master/Documentation/architecture/net-platform-standard.md) - The differrent between the old version and the new version of .NET.
* [Introducing .NET Standard 2.0](https://blogs.msdn.microsoft.com/dotnet/2016/09/26/introducing-net-standard) - The description of what will be going on for .NET Standard 2.0 and the roadmap for some missing parts of the current .NET Standard. 

## Frameworks, Libraries and Tools

### API
* [autorest ★912](https://github.com/Azure/autorest) - Swagger (OpenAPI) Specification code generator featuring C# and Razor templates. Supports C#, Java, Node.js, TypeScript, Python and Ruby. `4.5.x or above`
* [Flurl ★672](https://github.com/tmenier/Flurl) - Fluent URL builder and testable HTTP for .NET [http://tmenier.github.io/Flurl](http://tmenier.github.io/Flurl).
* [halcyon ★24](https://github.com/visualeyes/halcyon) - HAL implementation for ASP.NET.
* [LightNode ★113](https://github.com/neuecc/LightNode) - Micro RPC/REST Framework built on OWIN [http://neuecc.github.io/LightNode](http://neuecc.github.io/LightNode).
* [NSwag](https://github.com/NSwag/NSwag) - The Swagger API toolchain for .NET, Web API and TypeScript [http://NSwag.org](http://NSwag.org).
* [refit ★1365](https://github.com/paulcbetts/refit) - The automatic type-safe REST library for Xamarin and .NET [http://paulcbetts.github.io/refit/](http://paulcbetts.github.io/refit/).
* [RESTClient .NET](https://bitbucket.org/MelbourneDeveloper/restclient-.net) - Simple REST Client for all .NET platforms.
* [RestEase ★173](https://github.com/canton7/RestEase) - Easy-to-use typesafe REST API client library, which is simple and customisable.
* [Swashbuckle](https://github.com/domaindrivendev/Ahoy) - Seamlessly adds a swagger to WebApi projects.
* [WebAPIContrib for ASP.NET CORE ★231](https://github.com/WebApiContrib/WebAPIContrib.Core) - Community Contributions for ASP.NET Core.
* GraphQL
  * [graphql-dotnetcore](https://github.com/mkmarek/graphql-dotnetcore) - GraphQL for .NET Core based on [https://github.com/graphql/graphql-js ★7481](https://github.com/graphql/graphql-js).
  * [graphql-dotnet ★1158](https://github.com/graphql-dotnet/graphql-dotnet) - GraphQL for .NET.
  * [FSharp.Data.GraphQL ★97](https://github.com/fsprojects/FSharp.Data.GraphQL) - FSharp implementation of Facebook GraphQL query language [https://fsprojects.github.io/FSharp.Data.GraphQL](https://fsprojects.github.io/FSharp.Data.GraphQL).
  * [parser ★33](https://github.com/graphql-dotnet/parser) - A lexer and parser for GraphQL in .NET.

### Application Frameworks
* [ABP ★3098](https://github.com/aspnetboilerplate/aspnetboilerplate) - ASP.NET Boilerplate is a general purpose application framework especially designed for new modern web applications. It uses already familiar tools and implements best practices arround them to provide you a SOLID development experience.
* [akka.net ★2370](https://github.com/akkadotnet/akka.net) - Toolkit and runtime for building highly concurrent, distributed, and fault tolerant event-driven applications on .NET & Mono.
* [ASP.NET MVC ★4513](https://github.com/aspnet/Mvc) - Model view controller framework for building dynamic web sites with clean separation of concerns, including the merged MVC, Web API, and Web Pages w/ Razor.
* [CQRSlite ★385](https://github.com/gautema/CQRSlite) - Lightweight framework for helping writing CQRS and Eventsourcing applications in C#.
* [DotNetty ★1077](https://github.com/Azure/DotNetty) - Port of netty, event-driven asynchronous network application framework.
* [EmbedIO ★230](https://github.com/unosquare/embedio) - A tiny, cross-platform, module based web server for .NET Framework and .NET Core.
* [ExtCore](https://github.com/ExtCore) - Free, open source and cross-platform framework for creating modular and extendable web applications based on ASP.NET Core 1.0.
* [Halibut ★125](https://github.com/OctopusDeploy/Halibut) - A secure communication stack for .NET using JSON-RPC over SSL.
* [grpc](https://github.com/grpc/grpc/tree/master/src/csharp) - Remote Procedure Calls (RPCs) provide a useful abstraction for building distributed applications and services. The libraries in this repository provide a concrete implementation of the gRPC protocol, layered over HTTP/2. These libraries enable communication between clients and servers using any combination of the supported languages.
* [Nancy ★5480](https://github.com/NancyFx/Nancy) - Lightweight, low-ceremony, framework for building HTTP based services on .NET and Mono.
* [protoactor-dotnet ★390](https://github.com/AsynkronIT/protoactor-dotnet) - Ultra fast distributed actors for Golang and C# [http://proto.actor](http://proto.actor).
* [ServiceStack ★3920](https://github.com/ServiceStack/ServiceStack) - Thoughtfully architected, obscenely fast, thoroughly enjoyable web services for all [https://servicestack.net](https://servicestack.net).
* [Steeltoe OSS](https://github.com/SteelToeOSS) - .NET toolkit for common microservice patterns.

### Application Templates
* [ASP.NET MVC Boilerplate](https://github.com/RehanSaeed/ASP.NET-MVC-Boilerplate) - A professional ASP.NET MVC template for building secure, fast, robust and adaptable web applications or sites. It provides the minimum amount of code required on top of the default MVC template provided by Microsoft.
* [kendo-ui-core ★1739](https://github.com/telerik/kendo-ui-core) - An HTML5, jQuery-based widget library for building modern web apps. [http://www.telerik.com/kendo-ui](http://www.telerik.com/kendo-ui).
* [JavaScriptServices ★2302](https://github.com/aspnet/JavaScriptServices) - Microsoft ASP.NET Core JavaScript Services.
* [QuickApp ★162](https://github.com/emonney/QuickApp) - ASP.NET Core / Angular4 startup project template with complete login, user and role management.
* [Scaffolder ★77](https://github.com/dncuug/scaffolder) - Lets you create extensible data-driven Web applications by automatically generated UI for each table in the database and  lets create a applications for viewing and editing data based on the schema of the data. 

### Authentication and Authorization
* [AspNet.Security.OpenIdConnect.Server ★306](https://github.com/aspnet-contrib/AspNet.Security.OpenIdConnect.Server) - OpenID Connect/OAuth2 server framework for OWIN/Katana and ASP.NET Core.
* [Auth0 ★55](https://github.com/auth0/auth0.net) - Hosted, enterprise-grade platform for modern identity.
* [Identity ★1287](https://github.com/aspnet/Identity) - ASP.NET Core Identity is the membership system for building ASP.NET Core web applications, including membership, login, and user data.
* [IdentityServer ★1615](https://github.com/IdentityServer/IdentityServer4) - IdentityServer for ASP.NET Core 1.0
  * [IdentityServer4.EntityFramework ★64](https://github.com/IdentityServer/IdentityServer4.EntityFramework) - EntityFramework persistence layer
  * [IdentityServer4.MongoDB ★17](https://github.com/diogodamiani/IdentityServer4.MongoDB) - MongoDB persistence layer
  * [IdentityServer4.EntityFrameworkCore ★38](https://github.com/2020IP/TwentyTwenty.IdentityServer4.EntityFrameworkCore) - Entity Framework Core persistence layer
* [openiddict ★467](https://github.com/openiddict/openiddict-core) - Easy-to-use OpenID Connect server for ASP.NET Core.
* [stormpath-sdk](https://github.com/stormpath/stormpath-sdk-dotnet) - Build [simple, secure web applications ★19](https://github.com/stormpath/stormpath-aspnetcore) with Stormpath and ASP.NET Core.
* [stuntman ★183](https://github.com/ritterim/stuntman) - Library for impersonating users during development leveraging ASP.NET Identity.

### Build Automation
* [cake-build ★1312](https://github.com/cake-build/cake) - Cross platform build automation system. [http://cakebuild.net](http://cakebuild.net).
* [Colorful.Console ★246](https://github.com/tomakita/Colorful.Console) - Style your C# console output! [http://colorfulconsole.com](http://colorfulconsole.com).
* [dotnet-docker ★333](https://github.com/dotnet/dotnet-docker) - The base Docker images for working with .NET Core and the .NET Core Tools.
* [go-dotnet ★139](https://github.com/matiasinsaurralde/go-dotnet) - Go wrapper for the .NET Core Runtime.
* [msbuild ★3097](https://github.com/Microsoft/msbuild) - The Microsoft Build Engine is a platform for building applications.
* [vsts-agent](https://github.com/Microsoft/vsts-agent/blob/master/README.md) - Visual Studio Team Services Build and Release Agent.

### Bundling and Minification
* [BundlerMinifier ★227](https://github.com/madskristensen/BundlerMinifier) - Visual Studio extension that let's you configure bundling and minification of JS, CSS and HTML files.
* [JavaScriptViewEngine ★49](https://github.com/pauldotknopf/JavaScriptViewEngine) - ASP.NET MVC ViewEngine for rendering markup in a JavaScript environment. Ideal for React and Angular server-side rendering.
* [Smidge ★115](https://github.com/Shazwazza/Smidge) - Lightweight runtime CSS/JavaScript file minification, combination, compression & management library for ASP.NET Core.
* [Web Markup Minifier ★113](https://github.com/Taritsyn/WebMarkupMin) - .NET library that contains a set of markup minifiers. The objective of this project is to improve the performance of web applications by reducing the size of HTML, XHTML and XML code.

### Caching
* [CacheManager ★748](https://github.com/MichaCo/CacheManager) - Open source caching abstraction layer for .NET written in C#. It supports various cache providers and implements many advanced features. [http://cachemanager.michaco.net](http://cachemanager.michaco.net)
* [Foundatio](https://github.com/exceptionless/Foundatio) - Pluggable foundation blocks for building distributed apps.
* [Microsoft Caching ★305](https://github.com/aspnet/Caching) - Libraries for in-memory caching and distributed caching.
* [Stack Exchange Redis ★2254](https://github.com/StackExchange/StackExchange.Redis) - High performance general purpose redis client for .NET languages (C# etc).

### Cryptography
* [BCrypt.NET-Core ★39](https://github.com/neoKushan/BCrypt.Net-Core) - .NET Core port of BCrypt.NET used to store passwords securely.
* [BouncyCastle PCL ★86](https://github.com/onovotny/BouncyCastle-PCL) - The Bouncy Castle Crypto package is a C# implementation of cryptographic algorithms and protocols.

### CMS
* [Lynicon ★1](https://github.com/jamesej/lyniconanc) - O/S ASP.Net Core/.Net Core CMS with paid for modules: JSON content, works with variety of data stores, c# content types
* [OrchardCMS2 ★995](https://github.com/OrchardCMS/Orchard2) - The implementation of Orchard CMS in ASP.NET Core (also known as DNX).
* [Platformus](https://github.com/Platformus) - Free, open source and cross-platform CMS based on ASP.NET Core 1.0 and ExtCore framework.
* [SimpleContent ★137](https://github.com/joeaudette/cloudscribe.SimpleContent) - Simple, yet flexible content and blog engine for ASP.NET Core that can work with or without a database.
* [Squidex ★68](https://github.com/Squidex/squidex) - Headless CMS, based on MongoDB, CQRS and Event Sourcing.
* [Weapsy ★276](https://github.com/Weapsy/Weapsy) - Open source ASP.NET Core CMS based on DDD and CQRS. It supports MSSQL, MySQL, SQLite and PostgreSQL out of the box.

### Code Analysis and Metrics
* [App.Metrics ★321](https://github.com/alhardy/AppMetrics) - App Metrics is an open-source and cross-platform .NET library used to record and report metrics within an application and reports it's health. See the [docs](https://alhardy.github.io/app-metrics-docs/) for me details.
* [AspNet.Metrics](https://github.com/alhardy/aspnet-metrics) - Capturing CLR, application-level web request metrics. Middleware and extensions using [Metrics.Net ★309](https://github.com/Recognos/Metrics.NET).
* [Audit.NET ★340](https://github.com/thepirat000/Audit.NET) - Small framework to audit .NET object changes.
* [BenchmarkDotNet](https://github.com/PerfDotNet/BenchmarkDotNet) - Powerful .NET library for benchmarking.
* [NBench ★364](https://github.com/petabridge/NBench) - Performance benchmarking and testing framework for .NET applications.
* [OpenCover ★770](https://github.com/OpenCover/opencover) - Code coverage tool for .NET 2 and above (WINDOWS OS only), support for 32 and 64 processes with both branch and sequence points.

### Compilers, Transpilers and Languages
* [roslyn ★7912](https://github.com/dotnet/roslyn) - The .NET Compiler Platform ("Roslyn") provides open-source C# and Visual Basic compilers with rich code analysis APIs.
* [Sprache ★869](https://github.com/sprache/Sprache) - Tiny C# Monadic Parser Framework.

### Database Drivers
* [cassandra-csharp-driver ★251](https://github.com/datastax/csharp-driver) - DataStax C# Driver for Apache Cassandra.
* [confluent-kafka-dotnet ★205](https://github.com/confluentinc/confluent-kafka-dotnet) - Confluent's Apache Kafka .NET client.
* [LiteDB ★1612](https://github.com/mbdavid/LiteDB) - .NET NoSQL Document Store in a single data file - [http://www.litedb.org](http://www.litedb.org). `work-around for .NET Core at` [#219](https://github.com/mbdavid/LiteDB/issues/219)
* [MongoDB.Driver ★1633](https://github.com/mongodb/mongo-csharp-driver) - .NET Driver for MongoDB.
* [mysql-connector-net](https://github.com/mysql/mysql-connector-net/tree/7.0) - Connector/Net is a fully-managed ADO.NET driver for MySQL. [https://dev.mysql.com/downloads/connector/net](https://dev.mysql.com/downloads/connector/net/)
* [Neo4jClient](https://github.com/Readify/Neo4jClient/tree/DotNetCore) - .NET client binding for Neo4j.
* [npgsql ★1018](https://github.com/npgsql/npgsql) - .NET data provider for PostgreSQL. It allows any program developed for .NET framework to access a PostgreSQL database server. It is implemented in 100% C# code. PostgreSQL versions since 9.1 are officially supported, others may work. [http://www.npgsql.org](http://www.npgsql.org)
* [ravendb](https://github.com/ayende/ravendb/tree/v4.0) - Linq enabled document database for .NET.
* [RethinkDb.Driver ★209](https://github.com/bchavez/RethinkDb.Driver) - C#/.NET RethinkDB driver with 100% ReQL API coverage.
* [tarantool-csharp ★0](https://github.com/progaudi/tarantool-csharp) - .NET CLI client for Tarantool NoSql database.

### E-Commerce and Payments
* [SimplCommerce ★729](https://github.com/simplcommerce/SimplCommerce) - Super simple ecommerce system built on .NET Core.
* [Stripe ★111](https://github.com/ServiceStack/Stripe) - Typed .NET clients for stripe.com REST APIs.

### Functional Programming
* [CSharpFunctionalExtensions ★134](https://github.com/vkhorikov/CSharpFunctionalExtensions) - Functional Extensions for C#.
* [language-ext ★1631](https://github.com/louthy/language-ext) - C# functional language extensions and 'Erlang like' concurrency system.
* [NetMQ.ReactiveExtensions ★33](https://github.com/NetMQ/NetMQ.ReactiveExtensions) - Effortlessly send messages anywhere on the network using Reactive Extensions (RX). Transport protocol is ZeroMQ.
* [Optional ★152](https://github.com/nlkl/Optional) - A robust option type for C#.
* [reactive-streams-dotnet ★76](https://github.com/reactive-streams/reactive-streams-dotnet) - [Reactive Streams](http://www.reactive-streams.org/) for .NET.
* [ReactiveUI ★3183](https://github.com/reactiveui/ReactiveUI) - A MVVM framework that integrates with the Reactive Extensions for .NET to create elegant, testable User Interfaces that run on any mobile or desktop platform.
* [Rx.NET ★2069](https://github.com/Reactive-Extensions/Rx.NET) - The [Reactive Extensions](http://reactivex.io) for .NET.
* [Qactive ★75](https://github.com/RxDave/Qactive) - Reactive queryable observable framework. `4.x.x or above`
* [sodium](https://github.com/SodiumFRP/sodium/tree/master/c%23) - Functional Reactive Programming (FRP) Library. `4.x.x or above`

### Graphics
* [ImageProcessor ★1684](https://github.com/JimBobSquarePants/ImageProcessor) - A fluent wrapper around System.Drawing for the processing of image files [http://imageprocessor.org](http://imageprocessor.org). `4.5.x or above`
* [ImageSharp](https://github.com/JimBobSquarePants/ImageSharp) - Cross-platform library for processing of image files written in C# [http://imageprocessor.org](http://imageprocessor.org).
* [Structure.Sketching ★34](https://github.com/JaCraig/Structure.Sketching) - Image processing library for use in .NET applications that supports .NET Core.
* [veldrid ★110](https://github.com/mellinoe/veldrid) - A low-level, hardware-accelerated 3D graphics library for .NET.

### GUI
* [Avalonia ★2359](https://github.com/AvaloniaUI/Avalonia) - A multi-platform .NET UI framework (formerly known as Perspex).
* [AvaloniaEdit](https://github.com/AvaloniaUI/AvaloniaEdit/) - The Avalonia-based text editor component forked from [AvalonEdit ★474](https://github.com/icsharpcode/AvalonEdit)
* [WinApi ★48](https://github.com/prasannavl/WinApi) - A simple, direct, ultra-thin CLR library for high-performance Win32 Native Interop with automation, windowing, DirectX, OpenGL and Skia helpers.

### IDE
* [rider](https://www.jetbrains.com/rider/) - Cross-platform C# IDE based on the IntelliJ platform and ReSharper.
* [Omnisharp](http://www.omnisharp.net/) - Family of Open Source projects, each with one goal: To enable a great .NET experience in YOUR editor of choice.
* [Visual Studio Code ★31952](https://github.com/Microsoft/vscode) - New type of tool that combines the simplicity of a code editor with what developers need for their core edit-build-debug cycle. Code provides comprehensive editing and debugging support, an extensibility model, and lightweight integration with existing tools.
* [Visual Studio Community](https://www.visualstudio.com/en-us/products/visual-studio-community-vs.aspx) - Free editor for individual developers, open source projects, academic research, education, and small professional teams.

### Internationalization
* [Localization ★91](https://github.com/aspnet/Localization) - Localization abstractions and implementations for ASP.NET Core applications.
* [nodatime ★665](https://github.com/nodatime/nodatime) - Better date and time API for .NET [http://nodatime.org](http://nodatime.org).

### IOC
* [Autofac ★1589](https://github.com/autofac/Autofac) - Addictive .NET IoC container.
* [DryIoc](https://bitbucket.org/dadhi/dryioc) - Fast, small, full-featured IoC Container for .NET.
* [LightInject ★239](https://github.com/seesharper/LightInject) - Ultra lightweight IoC container [http://www.lightinject.net](http://www.lightinject.net).
* [SimpleInjector ★469](https://github.com/simpleinjector/SimpleInjector) - Easy, flexible, and fast Dependency Injection library that promotes best practice to steer developers towards the pit of success.
* [Stashbox ★11](https://github.com/z4kn4fein/stashbox) - A lightweight, portable dependency injection framework for .NET based solutions.
* [StructureMap ★746](https://github.com/structuremap/structuremap) - Dependency Injection/Inversion of Control tool for .NET.

### Logging
* [common-logging ★490](https://github.com/net-commons/common-logging) - Portable logging abstraction for .NET [http://net-commons.github.io/common-logging](http://net-commons.github.io/common-logging).
* [dnxcore-logging-logstash ★4 ⏳1Y](https://github.com/jvandevelde/dnxcore-logging-logstash) - Logstash logging extension for .NET Core applications with UDP and Redis transports.
* [serilog ★1463](https://github.com/serilog/serilog) - Simple .NET logging with fully-structured events.
* [NLog ★2508](https://github.com/NLog/NLog) - Advanced .NET, Silverlight and Xamarin Logging.
* [Q42.Logging.ApplicationInsights ★2](https://github.com/Q42/Q42.Logging.ApplicationInsights) - Log appender for the build in ASP.NET Core logging to send all logs to Application Insights.

### Machine Learning and Data Science
* [Spreads ★152](https://github.com/Spreads/Spreads) - Series and Panels for Real-time and Exploratory Analysis of Data Streams.

### Mail
* [MailBody ★63](https://github.com/doxakis/MailBody) - Create transactional email with a fluent interface (.NET).
* [MailKit ★1546](https://github.com/jstedfast/MailKit) - Cross-platform .NET library for IMAP, POP3, and SMTP.
* [MailMergeLib ★34](https://github.com/axuno/MailMergeLib) - SMTP mail client library which provides comfortable mail merge capabilities for text, inline images and attachments, as well as good throughput and fault tolerance for sending mail messages.
* [MimeKit ★615](https://github.com/jstedfast/MimeKit) - Cross-platform .NET MIME creation and parser library with support for S/MIME, PGP, DKIM, TNEF and Unix mbox spools.
* [PreMailer.Net](https://github.com/milkshakesoftware/PreMailer.Net/tree/dotnet-core) - C# library that moves your stylesheets to inline style attributes, for maximum compatibility with E-mail clients.
* [SendGrid Client ★14](https://github.com/0xdeafcafe/sendgrid-dotnet) - C# library for the SendGrid v3 mail endpoint.

### Mathematics
* [UnitConversion ★19](https://github.com/Stratajet/UnitConversion) - Expansible Unit Conversion Library for .NET Core and .NET Framework.

### Misc
* [AngleSharp ★1500](https://github.com/AngleSharp/AngleSharp) - The ultimate angle brackets parser library. It parses HTML5, MathML, SVG and CSS to construct a DOM based on the official W3C specification. Comparable to beautifulsoup4 of python.
* [aspnetcore-health ★27](https://github.com/lurumad/aspnetcore-health) - Enables load balancers to monitor the status of deployed Web applications.
* [AutoMapper ★4708](https://github.com/AutoMapper/AutoMapper) - Convention-based object-object mapper in .NET.
* [Castle.Core ★557](https://github.com/castleproject/Core) - Castle Core, including Castle DynamicProxy, Logging Services and DictionaryAdapter [http://www.castleproject.org](http://www.castleproject.org).
* [Chessie ★104](https://github.com/fsprojects/Chessie) - Railway-oriented programming for .NET [http://fsprojects.github.io/Chessie](http://fsprojects.github.io/Chessie).
* [CommonMark.NET ★655](https://github.com/Knagis/CommonMark.NET) - The implementation of CommonMark specification in C# for converting Markdown documents to HTML.
* [consuldotnet](https://github.com/PlayFab/consuldotnet/tree/develop) - .NET API for Consul.
* [datatables](https://github.com/ALMMa/datatables.aspnet/tree/dev) - Microsoft ASP.NET server-side support and helpers for jQuery DataTables.
* [Docker.DotNet ★338](https://github.com/Microsoft/Docker.DotNet) - .NET (C#) Client Library for Docker API.
* [Enums.NET ★378](https://github.com/TylerBrinkley/Enums.NET) - Enums.NET is a high-performance type-safe .NET enum utility library
* [FluentFTP ★220](https://github.com/hgupta9/FluentFTP) - FTP and FTPS client, with extensive FTP commands, SSL/TLS connections, hashing/checksums and more.
* [FluentValidation ★2416](https://github.com/JeremySkinner/FluentValidation) - Small validation library for .NET that uses a fluent interface and lambda expressions for building validation rules.
* [Humanizer ★2739](https://github.com/Humanizr/Humanizer) - Humanizer meets all your .NET needs for manipulating and displaying strings, enums, dates, times, timespans, numbers and quantities.
* [LibSass Host ★13](https://github.com/Taritsyn/LibSassHost) - .NET wrapper around the [libSass](http://sass-lang.com/libsass) library with the ability to support a virtual file system.
* [markdig ★633](https://github.com/lunet-io/markdig) - Fast, powerfull, CommonMark compliant, extensible Markdown processor for .NET.
* [Microphone ★388](https://github.com/rogeralsing/Microphone) - Lightweight framework to run self hosting REST services using Web Api or NancyFx ontop of a Consul or ETCD cluster.
* [NReco.LambdaParser ★36](https://github.com/nreco/lambdaparser) - Parses string expressions (formulas, methods calls, conditions) to LINQ expression tree that can be compiled to lambda and evaluated. 
* [NReco.PivotData](https://www.nuget.org/packages/NReco.PivotData/) - In-memory data cube with OLAP operations and PivotTable data model.
* [Ocelot ★353](https://github.com/TomPallister/Ocelot) - API Gateway created using .NET Core.
* [readline](https://github.com/tsolarin/readline) - Pure C# GNU-Readline like library for .NET/.NET Core.
* [reCAPTCHA ★38](https://github.com/PaulMiami/reCAPTCHA) - reCAPTCHA 2.0 for ASP.NET Core.
* [Relinq ★183](https://github.com/re-motion/Relinq) - With re-linq, it's now easier than ever to create full-featured LINQ providers.
* [ReverseMarkdown ★14](https://github.com/mysticmind/reversemarkdown-net) - Html to Markdown converter library.
* [PdfReport.Core ★43](https://github.com/VahidN/PdfReport.Core) - PdfReport.Core is a code first reporting engine, which is built on top of the iTextSharp.LGPLv2.Core and EPPlus.Core libraries.
* [PreStorm ★10](https://github.com/jshirota/PreStorm) - Parallel REST Client for ArcGIS Server.
* [Polly ★2600](https://github.com/App-vNext/Polly) - .NET 3.5 / 4.0 / 4.5 / PCL library that allows developers to express transient exception and fault handling policies such as Retry, Retry Forever, Wait and Retry or Circuit Breaker in a fluent manner.
* [Scrutor ★149](https://github.com/khellang/Scrutor) - Assembly scanning extensions for Microsoft.Extensions.DependencyInjection.
* [sharpcompress ★513](https://github.com/adamhathcock/sharpcompress) - Fully managed C# library to deal with many compression types and formats.
* [SmartFormat.NET ★297](https://github.com/scottrippey/SmartFormat.NET) - An extensible replacement for string.Format.
* [System.Linq.Dynamic.Core ★76](https://github.com/StefH/System.Linq.Dynamic.Core) - The .NET Standard (.NET Core) version from the System Linq Dynamic functionality.
* [warden-stack](https://github.com/warden-stack) - "health checks" for your applications, resources and infrastructure. Keep your Warden on the watch.

### ORM
* [Entity Framework Core ★4821](https://github.com/aspnet/EntityFramework) - Familiar developer experience to previous versions of EF, including LINQ, POCO, and Code First support.
* [Dapper ★6891](https://github.com/StackExchange/Dapper) - Simple object mapper for .NET.
  * [Dapper-FluentMap ★102](https://github.com/henkmollema/Dapper-FluentMap) - Provides a simple API to fluently map POCO properties to database columns when using Dapper.
  * [Dommel ★66](https://github.com/henkmollema/Dommel) - Simple CRUD operations for Dapper.
* [DBreeze ★134](https://github.com/hhblaze/DBreeze) - C# .NET MONO NOSQL ( key value store embedded ) ACID multi-paradigm database management system.
* [EntityFramework-Plus ★420](https://github.com/zzzprojects/EntityFramework-Plus) - Entity Framework Utilities | Bulk Operations | Batch Delete | Batch Update | Query Cache | Query Filter | Query Future | Query Include | Audit
* [Limebean](https://nick-lucas.github.io/LimeBean/) - Hybrid-ORM, designed to be simple to use and not totally hide SQL, while having all the nice things you expect from an ORM. Inspired by RedBeanPHP.
* [marten ★566](https://github.com/JasperFx/marten) - Postgresql as a Document Database and Event Store for .NET Applications [http://jasperfx.github.io/marten](http://jasperfx.github.io/marten).
* [NEventStore](https://github.com/NEventStore/NEventStore/tree/feature/dotnetcore) - Persistence library used to abstract different storage implementations when using event sourcing as storage mechanism. This library is developed with a specific focus on DDD/CQRS applications.
* [NoDb ★89](https://github.com/joeaudette/NoDb) - "no database" file system storage for .NET Core/ASP.NET Core because not every project needs a database.
* [NPoco ★486](https://github.com/schotime/NPoco) - Simple microORM that maps the results of a query onto a POCO object. Project based on Schotime's branch of PetaPoco.
* [NReco.Data ★45](https://github.com/nreco/data) - Lightweight provider-independent DAL for SQL commands generation, CRUD operations and simple POCO mapping.
* [ServiceStack.OrmLite ★965](https://github.com/ServiceStack/ServiceStack.OrmLite) - Light, simple and fast convention-based POCO ORM.
* [SqlFu ★194](https://github.com/sapiens/SqlFu) - Fast and versatile Micro-ORM.
* [yessql ★307](https://github.com/sebastienros/yessql) - .NET document database working on any RDBMS.

### Profiling
* [Glimpse](http://getglimpse.com) - Lightweight, open-source, real-time diagnostics and insights profiler for .NET. 
* [MiniProfiler ★959](https://github.com/MiniProfiler/dotnet) - A simple but effective mini-profiler for ASP.NET websites.

### Queue and Messaging
* [emitter](https://emitter.io/) - Free open source real-time messaging service that connects all devices. This publish-subscribe messaging API is built for speed and security.
* [EventStore ★2074](https://github.com/EventStore/EventStore) - The open-source, functional database with Complex Event Processing in JavaScript. [https://geteventstore.com](https://geteventstore.com)
* [MediatR ★1209](https://github.com/jbogard/MediatR) - Simple, unambitious mediator implementation in .NET.
 * [MediatR.Extensions.Microsoft.DependencyInjection ★12](https://github.com/jbogard/MediatR.Extensions.Microsoft.DependencyInjection) - MediatR extensions for Microsoft.Extensions.DependencyInjection.
* [Mediator.Net ★70](https://github.com/mayuanyang/Mediator.Net) - A simple mediator for .Net for sending command, publishing event and request response with pipelines supported.
* [MicroBus ★94](https://github.com/Lavinski/Enexure.MicroBus) - Simple in process mediator for .NET.
* [netmq ★1110](https://github.com/zeromq/netmq) - 100% native C# implementation of ZeroMQ for .NET.
* [rabbitmq-dotnet-client ★431](https://github.com/rabbitmq/rabbitmq-dotnet-client) - RabbitMQ .NET client [https://www.rabbitmq.com](https://www.rabbitmq.com).
* [RawRabbit ★242](https://github.com/pardahlman/RawRabbit) - Modern .NET framework for communication over RabbitMq.
* [Rebus ★599](https://github.com/rebus-org/Rebus) - Simple and lean service bus implementation for .NET.
* [Restbus](http://restbus.org) - Messaging library for RabbitMq.
* [Tossit ★17](https://github.com/turgayozgur/tossit) - Simple, easy to use library for distributed job/worker logic. Distributed messages handled by built in RabbitMQ implementation.

### Scheduler and Job
* [Chroniton.NetCore ★90](https://github.com/leosperry/Chroniton) - Lightweight robust library for running tasks(jobs) on schedules. 
* [FluentScheduler ★964](https://github.com/fluentscheduler/FluentScheduler) - Automated job scheduler with fluent interface.
* [HangfireIO ★2864](https://github.com/HangfireIO/Hangfire) - Easy way to perform fire-and-forget, delayed and recurring tasks inside ASP.NET apps [http://hangfire.io](http://hangfire.io).
* [LiquidState ★74](https://github.com/prasannavl/LiquidState) - Efficient asynchronous and synchronous state machines for .NET
* [quartznet](https://github.com/quartznet/quartznet/tree/quartznet-3) - Quartz Enterprise Scheduler .NET [http://www.quartz-scheduler.net](http://www.quartz-scheduler.net).
* [stateless ★1698](https://github.com/dotnet-state-machine/stateless) - Simple library for creating state machines in C# code.

### SDKs
* [AWS SDK ★677](https://github.com/aws/aws-sdk-net) - The Amazon Web Services (AWS) .NET Core SDK components. Each AWS service has its own NuGet package.
* [azure-event-hubs-dotnet ★34](https://github.com/azure/azure-event-hubs-dotnet) - .NET Standard client library for Azure Event Hubs.
* [NBitcoin ★450](https://github.com/MetacoSA/NBitcoin) - Comprehensive Bitcoin library for the .NET framework.
* [NetTelegramBotApi ★38](https://github.com/justdmitry/NetTelegramBotApi) - C# client library for building Telegram bot [https://core.telegram.org/bots/api](https://core.telegram.org/bots/api).
* [octokit.net](https://github.com/octokit/octokit.net/tree/target-the-coreclr) - GitHub API client library for .NET.
* [Open-XML-SDK-for-NET-Platform-Standard ★19](https://github.com/xrkolovos/Open-XML-SDK-for-NET-Platform-Standard) - .NET Platform Standard implementation of Open XML SDK 2.5.
* [SendGrid-csharp ★369](https://github.com/sendgrid/sendgrid-csharp) - C# client library for using the full SendGrid API.
* [statsd-csharp-client](https://github.com/Pereingo/statsd-csharp-client) - .NET Standard compatible C# client to interface with Etsy's excellent [statsd ★11785](https://github.com/etsy/statsd) server.
* [tweetinvi](https://github.com/linvi/tweetinvi/tree/tweetinvi.netcore) - Intuitive .NET C# library to access the Twitter REST and STREAM API.

### Security
* [HtmlSanitizer ★329](https://github.com/mganss/HtmlSanitizer) - Cleans HTML to avoid XSS attacks.
* [jose-jwt ★297](https://github.com/dvsekhvalnov/jose-jwt) - Library for processing JOSE objects (JWT, JWA, JWS and related).
* [NWebsec ★197](https://github.com/NWebsec/NWebsec) - Security libraries for ASP.NET [https://www.nwebsec.com](https://www.nwebsec.com).
* [roslyn-security-guard ★113](https://github.com/dotnet-security-guard/roslyn-security-guard) - Roslyn analyzers that aim to help security audit on .NET applications. 
* [Security ★612](https://github.com/aspnet/Security) - Middleware for security and authorization of web apps.

### Searching
* [AutoComplete ★15](https://github.com/omerfarukz/autocomplete) - Persistent, simple, powerful and portable autocomplete library.
* [Elasticsearch.Net & NEST ★1454](https://github.com/elastic/elasticsearch-net) - Repository for both NEST and Elasticsearch.NET, the two official elasticsearch .NET clients.
* [ElasticsearchCRUD ★89](https://github.com/damienbod/ElasticsearchCRUD) - Elasticsearch .NET API.
* [SolrExpress ★41](https://github.com/solr-express/solr-express) - Simple and lightweight query .NET library for Solr, in a controlled, buildable and fail fast way.

### Serialization
* [bond ★1593](https://github.com/Microsoft/bond) - Cross-platform framework for working with schematized data. It supports cross-language de/serialization and powerful generic mechanisms for efficiently manipulating data. Bond is broadly used at Microsoft in high scale services.
* [Channels ★287](https://github.com/davidfowl/Channels) - Push based .NET Streams.
* [CsvHelper ★1296](https://github.com/JoshClose/CsvHelper) - Library to help reading and writing CSV files [http://csvhelper.com](http://csvhelper.com).
* [Edi.Net ★47](https://github.com/indice-co/EDI.Net) - EDI Serializer/Deserializer. Supports EDIFact, X12 and TRADACOMS format.
* [ExtendedXmlSerializer ★29](https://github.com/wojtpl2/ExtendedXmlSerializer) - Extended Xml Serializer for .NET.
* [Jil ★1569](https://github.com/kevin-montrose/Jil) - Fast .NET JSON (De)Serializer, Built On Sigil.
* [msgpack-cli ★473](https://github.com/msgpack/msgpack-cli) - MessagePack implementation for Common Language Infrastructure / [msgpack.org](http://msgpack.org).
* [Newtonsoft.Json ★4534](https://github.com/JamesNK/Newtonsoft.Json) - Popular high-performance JSON framework for .NET.
* [protobuf-net ★1482](https://github.com/mgravell/protobuf-net) - Protocol Buffers library for idiomatic .NET.
* [ServiceStack.Text ★844](https://github.com/ServiceStack/ServiceStack.Text) - JSON, JSV and CSV Text Serializers.
* [TinyCsvParser ★38](https://github.com/bytefish/TinyCsvParser) - Easy to use, easy to extend and high-performance library for CSV parsing with .NET.
* [Wire ★289](https://github.com/rogeralsing/Wire) - Binary serializer for POCO objects.
* [YamlDotNet ★516](https://github.com/aaubry/YamlDotNet) - .NET 
* [ZeroFormatter ★747](https://github.com/neuecc/ZeroFormatter) - Fast binary (de)serializer for .NET.
* [YAXLib ★63](https://github.com/sinairv/YAXLib) - XML Serialization Library for the .NET Framework and .NET Core. Extremely flexible and powerful.

### Testing
* [Bogus ★476](https://github.com/bchavez/Bogus) - Simple and sane fake data generator for C#. Based on and ported from the famed faker.js.
* [GenFu ★255](https://github.com/MisterJames/GenFu) - Library you can use to generate realistic test data.
* [FakeItEasy ★672](https://github.com/FakeItEasy/FakeItEasy) - The easy mocking library for .NET.
* [FluentAssertions ★8](https://github.com/dennisdoomen/FluentAssertions) - Set of .NET extension methods that allow you to more naturally specify the expected outcome of a TDD or BDD-style test.
* [moq.netcore ★1908](https://github.com/Moq/moq4) - Most popular and friendly mocking framework for .NET.
* [MSpec ★674](https://github.com/machine/machine.specifications) - Popular testing framework for writing BDD-style tests.
* [MyTested.AspNetCore.Mvc ★676](https://github.com/ivaylokenov/MyTested.AspNetCore.Mvc) - Fluent testing
  framework for ASP.NET Core MVC.
* [Netling ★741 ⏳1Y](https://github.com/hallatore/Netling) - Load tester client for easy web testing.
* [NSpec ★187](https://github.com/nspec/NSpec) - Battle hardened testing framework for C# that's heavily inspired by Mocha and RSpec.
* [NSubstitute ★814](https://github.com/nsubstitute/NSubstitute) - A friendly substitute for .NET mocking frameworks.
* [nunit ★58](https://github.com/nunit/dotnet-test-nunit) - NUnit test runner for .NET Core.
* [shouldly ★626](https://github.com/shouldly/shouldly) - Should testing for .NET - the way Asserting *Should* be! [http://shouldly.readthedocs.org/en/latest](http://shouldly.readthedocs.org/en/latest)
* [SpecFlow](https://github.com/techtalk/SpecFlow/tree/DotNetCore) - Pragmatic BDD solution for .NET. It uses the Gherkin specification language and integrates to Visual Studio.
* [Storyteller ★185](https://github.com/storyteller/Storyteller) - Executable Specifications for .NET [http://storyteller.github.io](http://storyteller.github.io).
* [Stubbery](https://markvincze.github.io/Stubbery/) - A simple library for creating and running Api stubs in .NET.
* [TestStack.BDDfy ★216](https://github.com/TestStack/TestStack.BDDfy) - The simplest BDD framework EVER!
* [xunit ★1438](https://github.com/xunit/xunit) - Free, open source, community-focused unit testing tool for the .NET Framework.

### Tools
* [CatLight](https://catlight.io) - Status notifier for developers that monitors builds and tasks in the project. Built using .Net Core and Electron.
* [docfx ★738](https://github.com/dotnet/docfx) - Tools for building and publishing API documentation for .NET projects [http://dotnet.github.io/docfx](http://dotnet.github.io/docfx)
* [dotnetfiddle](https://dotnetfiddle.net) - .NET sandbox for developers to quickly try out code and share code snippets.
* [EntryPoint ★72](https://github.com/Nick-Lucas/EntryPoint) - Composable CLI (Command Line) Argument Parser for .Net Core & .Net Framework 4.5+.
* [gitignore.io ★2442](https://github.com/joeblau/gitignore.io) - Create useful .gitignore files for your project [https://www.gitignore.io](https://www.gitignore.io).
* [GitInfo ★59](https://github.com/kzu/GitInfo) - Git and SemVer Info from MSBuild, C# and VB.
* [ICanHasDotnetCore ★38](https://github.com/OctopusDeploy/ICanHasDotnetCore) - Scans uploaded packages.config files or GitHub repository and determines whether the nuget packages target .NET Standard [https://icanhasdot.net](https://icanhasdot.net).
* [json2csharp](http://json2csharp.com) - Generate C# classes from JSON.
* [OctoLinker ★2266](https://github.com/OctoLinker/browser-extension) - Navigate through `projects.json` files efficiently with the OctoLinker browser extension for GitHub.
* [Opserver ★3124](https://github.com/opserver/Opserver) - Stack Exchange's Monitoring System.
* [ShareX ★6191](https://github.com/ShareX/ShareX) - Free and open source program that lets you capture or record any area of your screen and share it with a single press of a key. It also allows uploading images, text or other types of files to over 80 supported destinations you can choose from. [https://getsharex.com](https://getsharex.com)
* [X.Web.Sitemap ★15](https://github.com/dncuug/X.Web.Sitemap) – Simple sitemap generator for .NET and .NET Core
* [X.Web.RSS ★6](https://github.com/dncuug/X.Web.RSS) – Simple RSS Feed generator for .NET and .NET Core

### Web Framework
* [ReactJS.NET ★1170](https://github.com/reactjs/React.NET) - .NET library for JSX compilation and server-side rendering of React components.
* [redux.NET](https://github.com/GuillaumeSalles/redux.NET) - Predictable state container for .NET apps. Inspired by [https://github.com/reactjs/redux ★33313](https://github.com/reactjs/redux).
* [RService.io ★19](https://github.com/Stoom/RService.IO) - ASP.Net Core RESTful microservice framework that focusing on speed and ease of use.

### Web Socket
* [SignalR Server ★804](https://github.com/aspnet/signalr) - Real-time web functionality for web apps, including server-side push.
* [WampSharp ★197](https://github.com/Code-Sharp/WampSharp) - C# implementation of [The Web Application Messaging Protocol](http://wamp-proto.org/) - Protocol that provides messaging patterns of Remote Procedure Calls and Publish/Subscribe over WebSockets.

### Windows Service
* [dotnet-win32-service ★177](https://github.com/dasMulli/dotnet-win32-service) - Set up and run as Windows Service directly from .NET Core.
* [Topshelf ★2008](https://github.com/Topshelf/Topshelf) - Easy service hosting framework for building Windows services using .NET. `4.5.x or above`

### Workflow
* [CoreWF ★45](https://github.com/dmetzgar/corewf) - Port of Windows Workflow Foundation (WF) to .NET Core.
* [workflow-core ★95](https://github.com/danielgerlag/workflow-core) - Lightweight workflow engine for .NET Standard.

## Starter Kits
* [ASP.NET Core Starter Kit ★764](https://github.com/kriasoft/aspnet-starter-kit) - Opinionated boilerplate for web development based on .NET Core, Kestrel, GraphQL on the backend and Babel, Webpack, React and Redux on the frontend. This boilerplate comes in both C# and F# flavors.
* [ASP.NET Boilerplate ★3098](https://github.com/aspnetboilerplate/aspnetboilerplate) - ASP.NET Boilerplate is a starting point for new modern web applications using best practices and most popular tools. It's aimed to be a SOLID model, a general-purpose application framework and a project template. `4.5.x or above`
* [aspnetcore-spa generator ★2302](https://github.com/aspnet/JavaScriptServices) - Yeoman generator to build a brand-new ASP.NET Core single page application that uses Angular 2 / React / React With Redux / Knockout / Aurelia on the client.
* [bitwarden-core ★508](https://github.com/bitwarden/core) - The core infrastructure backend (API, database, etc) [https://bitwarden.com](https://bitwarden.com).
* [dotNetify ★241](https://github.com/dsuryd/dotNetify) - Simple, lightweight, yet powerful way to build real-time HTML5/C# .NET web apps.
* [generator-aspnet ★856](https://github.com/OmniSharp/generator-aspnet) - yo generator for ASP.NET Core.
* [react-aspnet-boilerplate ★244](https://github.com/pauldotknopf/react-aspnet-boilerplate) - Starting point for building isomorphic React applications with ASP.NET Core 1, leveraging existing techniques.
* [saaskit ★507](https://github.com/saaskit/saaskit) - Developer toolkit for building SaaS applications.

## Sample Projects
* [AlbumViewerVNext ★239](https://github.com/RickStrahl/AlbumViewerVNext) - West Wind Album Viewer ASP.NET 5 Sample.
* [allReady ★568](https://github.com/HTBox/allReady) - Open-source solution focused on increasing awareness, efficiency and impact of preparedness campaigns as they are delivered by humanitarian and disaster response organizations in local communities. [http://www.htbox.org/projects/allready](http://www.htbox.org/projects/allready)
* [AspNet5GeoElasticsearch ★18](https://github.com/damienbod/AspNet5GeoElasticsearch) - ASP.NET Core MVC Geo Elasticsearch Swashbuckle Swagger.
* [aspnet-servicediscovery-patterns ★89](https://github.com/cecilphillip/aspnet-servicediscovery-patterns) - Samples of implementing Service Discovery patterns with ASP.NET Core.
* [AspNetAuthorizationWorkshop ★460](https://github.com/blowdart/AspNetAuthorizationWorkshop) - A workshop for moving through the various new pieces in ASP.NET Core Authorization
* [BikeSharing360 Suite of Apps from Microsoft](https://blogs.msdn.microsoft.com/visualstudio/2016/12/14/connectdemos-2016-bikesharing360-on-github/) Presented December Connect 2016 Conference, a compreshsive set of interworking apps for both enterprise users and the consumers (bike riders):
 [Mobile Apps](https://github.com/Microsoft/BikeSharing360_MobileApps), [Backend Services](https://github.com/Microsoft/BikeSharing360_BackendServices), [Websites](https://github.com/Microsoft/BikeSharing360_Websites), [Single Container Apps](https://github.com/Microsoft/BikeSharing360_SingleContainer), [Multi Container Apps](https://github.com/Microsoft/BikeSharing360_MultiContainer), [Cognitive Services Kiosk App ★22](https://github.com/Microsoft/BikeSharing360_CognitiveServicesKioskApp),
 [Azure Bot App ★21](https://github.com/Microsoft/BikeSharing360_BotApps).
* [cloudscribe ★473](https://github.com/joeaudette/cloudscribe) - ASP.NET Core Multi-tenant web application foundation.
* [CoreCodeCamp ★23](https://github.com/shawnwildermuth/CoreCodeCamp) - An Open Source Website for running small, local development events.
* [distributed-playground ★15 ⏳1Y](https://github.com/jvandevelde/distributed-playground) - Distributed service playground with Vagrant, Consul, Docker & ASP.NET Core.
* [DotNetClub ★197](https://github.com/scheshan/DotNetClub) - Tiny club written in ASP.NET Core.
* [Entropy ★279](https://github.com/aspnet/Entropy) - Chaotic experimental playground for new features and ideas - check here for small and simple samples for individual features.
* [EquinoxProject ★606](https://github.com/EduardoPires/EquinoxProject) - Full ASP.NET Core 2.0 application with DDD, CQRS and Event Sourcing.
* [eShopOnContainers](https://github.com/dotnet/eShopOnContainers) - Microservices Architecture and Containers based Reference Application.
* [guidance-identity-management-for-multitenant-apps ★43](https://github.com/Azure-Samples/guidance-identity-management-for-multitenant-apps) - How to manage user identities in a multitenant app on Microsoft Azure, using Azure Active Directory for authentication.
* [magazine-website ★71](https://github.com/thangchung/magazine-website) - Magazine website (using .NET Core, ASP.NET Core, EF Core) with DDD, CQRS, microservices, asynchronous programming applied.
* [MegaMine ★18](https://github.com/Nootus/MegaMine) - Open source mining solution that helps miners in extracting Gold, Quartz, Granite etc. This solution is built using ASP.NET Core and AngularJS utilizing multiple light weight components in a Microservices way.
* [minicompiler ★5](https://github.com/ealsur/minicompiler) - Minification, bundling and compiling sample.
* [MusicStore ★1096](https://github.com/aspnet/MusicStore) - Sample MusicStore application that uses MVC and Entity Framework.
* [NLayerAppV3 ★5](https://github.com/cesarcastrocuba/nlayerappv3) - NLayerAppV3 N-Layered Architecture with .NET Core Preview 2.
* [ReactiveTraderCloud ★643](https://github.com/AdaptiveConsulting/ReactiveTraderCloud) - Real-time trading platform demo showcasing reactive programming principles applied across the full application stack.
* [PhotoGallery ★316](https://github.com/chsakell/aspnet5-angular2-typescript) - Cross-platform Single Page Applications with ASP.NET Core, Angular 2 & TypeScript [http://wp.me/p3mRWu-11L](http://wp.me/p3mRWu-11L).
* [Practical ASP.NET Core ★776](https://github.com/dodyg/practical-aspnetcore) - A daily updated micro samples of ASP.NET Core features and facilities. 

## Articles 
* Basic knowledge
  * [A guide to the .NET Core projects on GitHub](https://blog.rendle.io/a-guide-to-the-net-projects-on-github/)
  * [Microsoft architectual overview of comprehensive BikeSharing360 suite of demo apps with related videos](https://blogs.msdn.microsoft.com/visualstudio/2016/12/14/connectdemos-2016-bikesharing360-on-github/)
  * [Porting a .NET Framework library to .NET Core](https://www.codeproject.com/Articles/1190475/Porting-a-NET-Framework-library-to-NET-Core)
  * [The 68 things the CLR does before executing a single line of your code](http://mattwarren.org/2017/02/07/The-68-things-the-CLR-does-before-executing-a-single-line-of-your-code/)
  * The comparison between .NET Core and Nodejs at [here](https://manuel-rauber.com/2016/03/07/node-js-asp-net-core-1-0-a-usage-comparison/), [here](https://gist.github.com/ilyaigpetrov/f6df3e6f825ae1b5c7e2) and [here ★47 ⏳1Y](https://github.com/thinktecture/nodejs-aspnetcore-webapi)
  * [Understanding ASP.NET Core Initialization](http://developer.telerik.com/featured/understanding-asp-net-core-initialization/)
* Cloud Development
  * [Configuring the AWS SDK in .NET Core](https://aws.amazon.com/blogs/developer/configuring-aws-sdk-with-net-core/)
  * [Serverless Architecture using C# and AWS Amazon Gateway Api/Lambda](https://www.codeproject.com/Articles/1178781/Serverless-Architecture-using-Csharp-and-AWS-Amazo)
  * [Using C# and .NET Core in Amazon Web Services (AWS) Lambda](https://aws.amazon.com/blogs/compute/announcing-c-sharp-support-for-aws-lambda/)
* Configuration and deployment
  * [.NET project structure](https://gist.github.com/davidfowl/ed7564297c61fe9ab814)
  * [Adding Travis CI builds to a .NET Core app](http://andrewlock.net/adding-travis-ci-to-a-net-core-app/)
  * [ASP.NET Core 1.0 - Configure ApplicationInsights](http://social.technet.microsoft.com/wiki/contents/articles/35918.asp-net-core-1-0-configure-applicationinsights.aspx)
  * [haproxy, nginx, Angular 2, ASP.NET Core, Redis and Docker](http://tattoocoder.azurewebsites.net/legion-of-heroes-haproxy-nginx-angular2-aspnetcore-redis-docker/)
  * [Project.json to MSBuild conversion guide](http://www.natemcmaster.com/blog/2017/01/19/project-json-to-csproj/)
  * [Publishing a .NET project with Appveyor and NuGet](https://few-lines-of-code.blogspot.com/2016/03/publishing-net-project-with-appveyor.html)
  * [The New Configuration Model in ASP.NET Core](http://developer.telerik.com/featured/new-configuration-model-asp-net-core/)
* Entity Framework Core 
  * [.NET Core Data Access](https://blogs.msdn.microsoft.com/dotnet/2016/11/09/net-core-data-access/)
  * [A very good example about EF Core ★85](https://github.com/rowanmiller/Demo-EFCore)
* Miraculous
  * [Vue.js server side rendering with ASP.NET Core](http://mgyongyosi.com/2016/Vuejs-server-side-rendering-with-aspnet-core/)
* Security
  * [.NET Continuous Delivery Microservices](http://stackshare.io/tomstaijen/net-continuous-delivery-microservices)
  * [A walk-through for an ASP.NET Authorization Lab ★460](https://github.com/blowdart/AspNetAuthorizationWorkshop)
  * [Authentication in ASP.NET Core](https://stormpath.com/blog/authentication-asp-net-core)
* Testing
  * [Selenium with .NET Core](http://www.dotnetcatch.com/2016/11/23/selenium-with-net-core/)

## Books
* [ASP.NET Core Application Development: Building an application in four sprints (Developer Reference)](https://www.amazon.com/ASP-NET-Core-Application-Development-application/dp/1509304061)
* [ASP.NET Core in Action](https://www.manning.com/books/asp-dot-net-core-in-action)
* [ASP.NET Core 1.0 High Performance](https://www.amazon.com/ASP-NET-Core-1-0-High-Performance/dp/1785881892)
* [Building Microservices with ASP.NET Core: Develop, Test, and Deploy Cross-Platform Services in the Cloud](https://www.amazon.com/Building-Microservices-ASP-NET-Core-Cross-Platform/dp/1491961732)
* [C# 6 and .NET Core 1.0: Modern Cross-Platform Development](https://www.amazon.com/NET-Core-1-0-Cross-Platform-Development/dp/1785285696)
* [Dependency Injection in .NET Core, 2nd edition](https://www.manning.com/books/dependency-injection-in-dot-net-second-edition)
* [Microservices in .NET Core: with C#, the Nancy framework, and OWIN middleware](https://www.amazon.com/Microservices-NET-Core-framework-middleware/dp/1617293377)
* [Professional C# 6 and .NET Core 1.0](https://www.amazon.com/Professional-NET-Core-Christian-Nagel/dp/111909660X)
* [.NET Core in Action](https://manning.com/books/dotnet-core-in-action)

## Videos
* [Channel9](https://channel9.msdn.com)
 * [ASP.NET Monsters](https://channel9.msdn.com/Series/aspnetmonsters)
* [Visual Studio](https://www.youtube.com/user/VisualStudio/channels)
* [.NET World](https://www.youtube.com/channel/UClW5uIyHKPhfSEloQxn7b0Q)

## Podcasts
* [.NET Rocks](https://www.dotnetrocks.com)
* [Static Void Podcast](https://www.staticvoidpodcast.com)
* [The sound of .NET](http://thesoundof.net/?q=.NET+Core)

## Community
* [ASP.NET](https://forums.asp.net)
* [.NET Foundation](http://forums.dotnetfoundation.org)
* [Channel9](https://channel9.msdn.com/Forums)
* Stack Overflow
  *  [.NET Core](https://stackoverflow.com/questions/tagged/.net-core)
  *  [CoreCLR](https://stackoverflow.com/questions/tagged/coreclr)
  *  [ASP.NET Core](https://stackoverflow.com/questions/tagged/asp.net-core)
  *  [ASP.NET Core MVC](https://stackoverflow.com/questions/tagged/asp.net-core-mvc)
  *  [ASP.NET Core 1.0](https://stackoverflow.com/questions/tagged/asp.net-core-1.0)
  *  [Entity Framework Core](https://stackoverflow.com/questions/tagged/entity-framework-core)

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [thangchung](http://weblogs.asp.net/thangchung) has waived all copyright and related or neighboring rights to this work.
---
<p align="center">
	This list is a copy of <a href="https://github.com/thangchung/awesome-dotnet-core">thangchung/awesome-dotnet-core</a> with ranks
</p>
