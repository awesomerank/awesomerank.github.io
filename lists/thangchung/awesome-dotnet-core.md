<h1 align="center">
Ranked awesome lists, all in one place
</h1>
<p align="center">
	This list is a copy of <a href="thangchung/awesome-dotnet-core">thangchung/awesome-dotnet-core</a> with ranks
</p>
---
# Awesome .NET Core [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg) ★59088](sindresorhus/awesome)

> A collection of awesome [.NET Core](#frameworks-libraries-and-tools) frameworks, libraries, tools, resources and software.

Inspired by [awesome](https://github.com/sindresorhus/awesome), [awesome-dotnet](https://github.com/quozd/awesome-dotnet),  [awesome-nodejs](https://github.com/sindresorhus/awesome-nodejs), [frontend-dev-bookmarks ★21704](dypsilon/frontend-dev-bookmarks).

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
  * [Graphics](#graphics)
  * [GUI](#gui)
  * [Functional Programming](#functional-programming)
  * [IDE](#ide)
  * [Internationalization](#internationalization)
  * [IOC](#ioc)
  * [Logging](#logging)
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
* [.NET Core SDK](https://www.microsoft.com/net/core) - .NET Core SDK is a general purpose development platform maintained by Microsoft and the .NET community on [GitHub ★4510](dotnet/core). 
* [.NET Platform Standard](https://github.com/dotnet/corefx/blob/master/Documentation/architecture/net-platform-standard.md) - The differrent between the old version and the new version of .NET.
* [Introducing .NET Standard 2.0](https://blogs.msdn.microsoft.com/dotnet/2016/09/26/introducing-net-standard) - The description of what will be going on for .NET Standard 2.0 and the roadmap for some missing parts of the current .NET Standard. 

## Frameworks, Libraries and Tools

### API
* [autorest ★820](Azure/autorest) - Swagger (OpenAPI) Specification code generator featuring C# and Razor templates. Supports C#, Java, Node.js, TypeScript, Python and Ruby. `4.5.x or above`
* [Flurl ★607](tmenier/Flurl) - Fluent URL builder and testable HTTP for .NET [http://tmenier.github.io/Flurl](http://tmenier.github.io/Flurl).
* [LightNode ★104](neuecc/LightNode) - Micro RPC/REST Framework built on OWIN [http://neuecc.github.io/LightNode](http://neuecc.github.io/LightNode).
* [NSwag ★609](NSwag/NSwag) - The Swagger API toolchain for .NET, Web API and TypeScript [http://NSwag.org](http://NSwag.org).
* [refit ★1264](paulcbetts/refit) - The automatic type-safe REST library for Xamarin and .NET [http://paulcbetts.github.io/refit/](http://paulcbetts.github.io/refit/).
* [RESTClient .NET](https://bitbucket.org/MelbourneDeveloper/restclient-.net) - Simple REST Client for all .NET platforms.
* [RestEase ★141](canton7/RestEase) - Easy-to-use typesafe REST API client library, which is simple and customisable.
* [Swashbuckle](https://github.com/domaindrivendev/Ahoy) - Seamlessly adds a swagger to WebApi projects.
* [WebAPIContrib for ASP.NET CORE ★221](WebApiContrib/WebAPIContrib.Core) - Community Contributions for ASP.NET Core.
* GraphQL
  * [graphql-dotnetcore](https://github.com/mkmarek/graphql-dotnetcore) - GraphQL for .NET Core based on [https://github.com/graphql/graphql-js ★6690](graphql/graphql-js).
  * [graphql-dotnet ★892](graphql-dotnet/graphql-dotnet) - GraphQL for .NET.
  * [FSharp.Data.GraphQL ★83](fsprojects/FSharp.Data.GraphQL) - FSharp implementation of Facebook GraphQL query language [https://fsprojects.github.io/FSharp.Data.GraphQL](https://fsprojects.github.io/FSharp.Data.GraphQL).
  * [parser ★27](graphql-dotnet/parser) - A lexer and parser for GraphQL in .NET.

### Application Frameworks
* [akka.net](https://github.com/akkadotnet/akka.net/tree/netcore) - Toolkit and runtime for building highly concurrent, distributed, and fault tolerant event-driven applications on .NET & Mono. `Stable version only works for 4.5.x, but development version is available for .NET Core 1.0`
* [ASP.NET MVC ★4329](aspnet/Mvc) - Model view controller framework for building dynamic web sites with clean separation of concerns, including the merged MVC, Web API, and Web Pages w/ Razor.
* [CQRSlite ★356](gautema/CQRSlite) - Lightweight framework for helping writing CQRS and Eventsourcing applications in C#.
* [DotNetty ★885](Azure/DotNetty) - Port of netty, event-driven asynchronous network application framework.
* [ExtCore](https://github.com/ExtCore) - Free, open source and cross-platform framework for creating modular and extendable web applications based on ASP.NET Core 1.0.
* [Halibut ★120](OctopusDeploy/Halibut) - A secure communication stack for .NET using JSON-RPC over SSL.
* [grpc](https://github.com/grpc/grpc/tree/master/src/csharp) - Remote Procedure Calls (RPCs) provide a useful abstraction for building distributed applications and services. The libraries in this repository provide a concrete implementation of the gRPC protocol, layered over HTTP/2. These libraries enable communication between clients and servers using any combination of the supported languages.
* [Nancy ★5279](NancyFx/Nancy) - Lightweight, low-ceremony, framework for building HTTP based services on .NET and Mono.
* [protoactor-dotnet ★286](AsynkronIT/protoactor-dotnet) - Ultra fast distributed actors for Golang and C# [http://proto.actor](http://proto.actor).
* [ServiceStack ★3849](ServiceStack/ServiceStack) - Thoughtfully architected, obscenely fast, thoroughly enjoyable web services for all [https://servicestack.net](https://servicestack.net).
* [Steeltoe OSS](https://github.com/SteelToeOSS) - .NET toolkit for common microservice patterns.

### Application Templates
* [ASP.NET MVC Boilerplate](https://github.com/RehanSaeed/ASP.NET-MVC-Boilerplate) - A professional ASP.NET MVC template for building secure, fast, robust and adaptable web applications or sites. It provides the minimum amount of code required on top of the default MVC template provided by Microsoft.
* [kendo-ui-core ★1689](telerik/kendo-ui-core) - An HTML5, jQuery-based widget library for building modern web apps. [http://www.telerik.com/kendo-ui](http://www.telerik.com/kendo-ui).
* [JavaScriptServices ★2066](aspnet/JavaScriptServices) - Microsoft ASP.NET Core JavaScript Services.
* [Scaffolder ★72](dncuug/scaffolder) - Lets you create extensible data-driven Web applications by automatically generated UI for each table in the database and  lets create a applications for viewing and editing data based on the schema of the data. 

### Authentication and Authorization
* [Identity ★1201](aspnet/Identity) - ASP.NET Core Identity is the membership system for building ASP.NET Core web applications, including membership, login, and user data.
* [IdentityServer ★1341](IdentityServer/IdentityServer4) - IdentityServer for ASP.NET Core 1.0
  * [IdentityServer4.EntityFramework ★57](IdentityServer/IdentityServer4.EntityFramework) - EntityFramework persistence layer
  * [IdentityServer4.MongoDB ★12](diogodamiani/IdentityServer4.MongoDB) - MongoDB persistence layer
  * [IdentityServer4.EntityFrameworkCore ★33](2020IP/TwentyTwenty.IdentityServer4.EntityFrameworkCore) - Entity Framework Core persistence layer
* [openiddict ★406](openiddict/openiddict-core) - Easy-to-use OpenID Connect server for ASP.NET Core.
* [stormpath-sdk](https://github.com/stormpath/stormpath-sdk-dotnet) - Build [simple, secure web applications ★18](stormpath/stormpath-aspnetcore) with Stormpath and ASP.NET Core.
* [stuntman ★173](ritterim/stuntman) - Library for impersonating users during development leveraging ASP.NET Identity.

### Build Automation
* [cake-build ★1205](cake-build/cake) - Cross platform build automation system. [http://cakebuild.net](http://cakebuild.net).
* [Colorful.Console ★217](tomakita/Colorful.Console) - Style your C# console output! [http://colorfulconsole.com](http://colorfulconsole.com).
* [dotnet-docker ★294](dotnet/dotnet-docker) - The base Docker images for working with .NET Core and the .NET Core Tools.
* [go-dotnet ★125](matiasinsaurralde/go-dotnet) - Go wrapper for the .NET Core Runtime.
* [msbuild ★3021](Microsoft/msbuild) - The Microsoft Build Engine is a platform for building applications.
* [vsts-agent](https://github.com/Microsoft/vsts-agent/blob/master/README.md) - Visual Studio Team Services Build and Release Agent.

### Bundling and Minification
* [BundlerMinifier ★213](madskristensen/BundlerMinifier) - Visual Studio extension that let's you configure bundling and minification of JS, CSS and HTML files.
* [JavaScriptViewEngine ★47](pauldotknopf/JavaScriptViewEngine) - ASP.NET MVC ViewEngine for rendering markup in a JavaScript environment. Ideal for React and Angular server-side rendering.
* [Smidge ★115](Shazwazza/Smidge) - Lightweight runtime CSS/JavaScript file minification, combination, compression & management library for ASP.NET Core.
* [Web Markup Minifier ★103](Taritsyn/WebMarkupMin) - .NET library that contains a set of markup minifiers. The objective of this project is to improve the performance of web applications by reducing the size of HTML, XHTML and XML code.

### Caching
* [CacheManager ★654](MichaCo/CacheManager) - Open source caching abstraction layer for .NET written in C#. It supports various cache providers and implements many advanced features. [http://cachemanager.michaco.net](http://cachemanager.michaco.net)
* [Foundatio ★541](exceptionless/Foundatio) - Pluggable foundation blocks for building distributed apps.
* [Microsoft Caching ★288](aspnet/Caching) - Libraries for in-memory caching and distributed caching.
* [Stack Exchange Redis ★2114](StackExchange/StackExchange.Redis) - High performance general purpose redis client for .NET languages (C# etc).

### Cryptography
* [BCrypt.NET-Core ★30](neoKushan/BCrypt.Net-Core) - .NET Core port of BCrypt.NET used to store passwords securely.
* [BouncyCastle PCL ★84](onovotny/BouncyCastle-PCL) - The Bouncy Castle Crypto package is a C# implementation of cryptographic algorithms and protocols.

### CMS
* [OrchardCMS2 ★898](OrchardCMS/Orchard2) - The implementation of Orchard CMS in ASP.NET Core (also known as DNX).
* [Platformus](https://github.com/Platformus) - Free, open source and cross-platform CMS based on ASP.NET Core 1.0 and ExtCore framework.
* [SimpleContent ★116](joeaudette/cloudscribe.SimpleContent) - Simple, yet flexible content and blog engine for ASP.NET Core that can work with or without a database.
* [Squidex ★43](Squidex/squidex) - Headless CMS, based on MongoDB, CQRS and Event Sourcing.

### Code Analysis and Metrics
* [App.Metrics ★157](alhardy/AppMetrics) - App Metrics is an open-source and cross-platform .NET library used to record and report metrics within an application and reports it's health. See the [docs](https://alhardy.github.io/app-metrics-docs/) for me details.
* [AspNet.Metrics](https://github.com/alhardy/aspnet-metrics) - Capturing CLR, application-level web request metrics. Middleware and extensions using [Metrics.Net ★281](Recognos/Metrics.NET).
* [Audit.NET ★315](thepirat000/Audit.NET) - Small framework to audit .NET object changes.
* [BenchmarkDotNet](https://github.com/PerfDotNet/BenchmarkDotNet) - Powerful .NET library for benchmarking.
* [NBench](https://github.com/petabridge/NBench/tree/dev) - Performance benchmarking and testing framework for .NET applications. `4.5.x or above`
* [OpenCover ★741](OpenCover/opencover) - Code coverage tool for .NET 2 and above (WINDOWS OS only), support for 32 and 64 processes with both branch and sequence points.

### Compilers, Transpilers and Languages
* [roslyn ★7571](dotnet/roslyn) - The .NET Compiler Platform ("Roslyn") provides open-source C# and Visual Basic compilers with rich code analysis APIs.
* [Sprache ★721](sprache/Sprache) - Tiny C# Monadic Parser Framework.

### Database Drivers
* [cassandra-csharp-driver ★237](datastax/csharp-driver) - DataStax C# Driver for Apache Cassandra.
* [LiteDB ★1511](mbdavid/LiteDB) - .NET NoSQL Document Store in a single data file - [http://www.litedb.org](http://www.litedb.org). `work-around for .NET Core at` [#219](https://github.com/mbdavid/LiteDB/issues/219)
* [MongoDB.Driver ★1583](mongodb/mongo-csharp-driver) - .NET Driver for MongoDB. `Stable version only works for 4.5.x, but beta available for .NET Core 1.0`
* [mysql-connector-net](https://github.com/mysql/mysql-connector-net/tree/7.0) - Connector/Net is a fully-managed ADO.NET driver for MySQL. [https://dev.mysql.com/downloads/connector/net](https://dev.mysql.com/downloads/connector/net/)
* [Neo4jClient](https://github.com/Readify/Neo4jClient/tree/DotNetCore) - .NET client binding for Neo4j.
* [npgsql ★967](npgsql/npgsql) - .NET data provider for PostgreSQL. It allows any program developed for .NET framework to access a PostgreSQL database server. It is implemented in 100% C# code. PostgreSQL versions since 9.1 are officially supported, others may work. [http://www.npgsql.org](http://www.npgsql.org)
* [ravendb](https://github.com/ayende/ravendb/tree/v4.0) - Linq enabled document database for .NET.
* [RethinkDb.Driver ★197](bchavez/RethinkDb.Driver) - C#/.NET RethinkDB driver with 100% ReQL API coverage.
* [tarantool-csharp ★0](progaudi/tarantool-csharp) - .NET CLI client for Tarantool NoSql database.

### E-Commerce and Payments
* [SimplCommerce ★646](simplcommerce/SimplCommerce) - Super simple ecommerce system built on .NET Core.
* [Stripe ★106](ServiceStack/Stripe) - Typed .NET clients for stripe.com REST APIs.

### Graphics
* [ImageProcessor ★1626](JimBobSquarePants/ImageProcessor) - A fluent wrapper around System.Drawing for the processing of image files [http://imageprocessor.org](http://imageprocessor.org). `4.5.x or above`
* [ImageSharp ★828](JimBobSquarePants/ImageSharp) - Cross-platform library for processing of image files written in C# [http://imageprocessor.org](http://imageprocessor.org).
* [Structure.Sketching ★33](JaCraig/Structure.Sketching) - Image processing library for use in .NET applications that supports .NET Core.
* [veldrid ★93](mellinoe/veldrid) - A low-level, hardware-accelerated 3D graphics library for .NET.

### GUI
* [Avalonia ★2215](AvaloniaUI/Avalonia) - A multi-platform .NET UI framework (formerly known as Perspex).
* [AvaloniaEdit](https://github.com/AvaloniaUI/AvaloniaEdit/) - The Avalonia-based text editor component forked from [AvalonEdit ★438](icsharpcode/AvalonEdit)

### Functional Programming
* [CSharpFunctionalExtensions ★104](vkhorikov/CSharpFunctionalExtensions) - Functional Extensions for C#.
* [language-ext ★1548](louthy/language-ext) - C# functional language extensions and 'Erlang like' concurrency system.
* [NetMQ.ReactiveExtensions ★26](NetMQ/NetMQ.ReactiveExtensions) - Effortlessly send messages anywhere on the network using Reactive Extensions (RX). Transport protocol is ZeroMQ.
* [Optional ★125](nlkl/Optional) - A robust option type for C#.
* [ReactiveUI ★3071](reactiveui/ReactiveUI) - A MVVM framework that integrates with the Reactive Extensions for .NET to create elegant, testable User Interfaces that run on any mobile or desktop platform.
* [Rx.NET ★1900](Reactive-Extensions/Rx.NET) - The [Reactive Extensions](http://reactivex.io) for .NET.
* [sodium](https://github.com/SodiumFRP/sodium/tree/master/c%23) - Functional Reactive Programming (FRP) Library. `4.5.x or above`

### IDE
* [rider](https://www.jetbrains.com/rider/) - Cross-platform C# IDE based on the IntelliJ platform and ReSharper.
* [Omnisharp](http://www.omnisharp.net/) - Family of Open Source projects, each with one goal: To enable a great .NET experience in YOUR editor of choice.
* [Visual Studio Code ★28340](Microsoft/vscode) - New type of tool that combines the simplicity of a code editor with what developers need for their core edit-build-debug cycle. Code provides comprehensive editing and debugging support, an extensibility model, and lightweight integration with existing tools.
* [Visual Studio Community](https://www.visualstudio.com/en-us/products/visual-studio-community-vs.aspx) - Free editor for individual developers, open source projects, academic research, education, and small professional teams.

### Internationalization
* [Localization ★84](aspnet/Localization) - Localization abstractions and implementations for ASP.NET Core applications.
* [nodatime ★611](nodatime/nodatime) - Better date and time API for .NET [http://nodatime.org](http://nodatime.org).

### IOC
* [Autofac ★1481](autofac/Autofac) - Addictive .NET IoC container.
* [DryIoc](https://bitbucket.org/dadhi/dryioc) - Fast, small, full-featured IoC Container for .NET.
* [LightInject ★229](seesharper/LightInject) - Ultra lightweight IoC container [http://www.lightinject.net](http://www.lightinject.net).
* [SimpleInjector ★437](simpleinjector/SimpleInjector) - Easy, flexible, and fast Dependency Injection library that promotes best practice to steer developers towards the pit of success.
* [StructureMap](https://github.com/structuremap/structuremap.dnx) - Dependency Injection/Inversion of Control tool for .NET.

### Logging
* [common-logging ★462](net-commons/common-logging) - Portable logging abstraction for .NET [http://net-commons.github.io/common-logging](http://net-commons.github.io/common-logging).
* [dnxcore-logging-logstash ★4 ⏳1Y](jvandevelde/dnxcore-logging-logstash) - Logstash logging extension for .NET Core applications with UDP and Redis transports.
* [serilog ★1364](serilog/serilog) - Simple .NET logging with fully-structured events.
* [NLog ★2349](NLog/NLog) - Advanced .NET, Silverlight and Xamarin Logging.
* [Q42.Logging.ApplicationInsights ★2](Q42/Q42.Logging.ApplicationInsights) - Log appender for the build in ASP.NET Core logging to send all logs to Application Insights.

### Mail
* [MailBody ★58](doxakis/MailBody) - Create transactional email with a fluent interface (.NET).
* [MailKit ★1458](jstedfast/MailKit) - Cross-platform .NET library for IMAP, POP3, and SMTP.
* [MailMergeLib ★35](axuno/MailMergeLib) - SMTP mail client library which provides comfortable mail merge capabilities for text, inline images and attachments, as well as good throughput and fault tolerance for sending mail messages.
* [MimeKit ★598](jstedfast/MimeKit) - Cross-platform .NET MIME creation and parser library with support for S/MIME, PGP, DKIM, TNEF and Unix mbox spools.
* [PreMailer.Net](https://github.com/milkshakesoftware/PreMailer.Net/tree/dotnet-core) - C# library that moves your stylesheets to inline style attributes, for maximum compatibility with E-mail clients.
* [SendGrid Client ★14](0xdeafcafe/sendgrid-dotnet) - C# library for the SendGrid v3 mail endpoint.

### Mathematics
* [UnitConversion ★15](Stratajet/UnitConversion) - Expansible Unit Conversion Library for .NET Core and .NET Framework.

### Misc
* [AngleSharp ★1385](AngleSharp/AngleSharp) - The ultimate angle brackets parser library. It parses HTML5, MathML, SVG and CSS to construct a DOM based on the official W3C specification. Comparable to beautifulsoup4 of python.
* [aspnetcore-health ★23](lurumad/aspnetcore-health) - Enables load balancers to monitor the status of deployed Web applications.
* [AutoMapper ★4473](AutoMapper/AutoMapper) - Convention-based object-object mapper in .NET.
* [Castle.Core](https://github.com/castleproject/Core/tree/netcore) - Castle Core, including Castle DynamicProxy, Logging Services and DictionaryAdapter [http://www.castleproject.org](http://www.castleproject.org).
* [Chessie ★102](fsprojects/Chessie) - Railway-oriented programming for .NET [http://fsprojects.github.io/Chessie](http://fsprojects.github.io/Chessie).
* [CommonMark.NET ★625](Knagis/CommonMark.NET) - The implementation of CommonMark specification in C# for converting Markdown documents to HTML.
* [consuldotnet](https://github.com/PlayFab/consuldotnet/tree/develop) - .NET API for Consul.
* [CoreWF ★33](dmetzgar/corewf) - Port of Windows Workflow Foundation (WF) to .NET Core.
* [datatables](https://github.com/ALMMa/datatables.aspnet/tree/dev) - Microsoft ASP.NET server-side support and helpers for jQuery DataTables.
* [Docker.DotNet ★306](Microsoft/Docker.DotNet) - .NET (C#) Client Library for Docker API.
* [Enums.NET ★284](TylerBrinkley/Enums.NET) - Enums.NET is a high-performance type-safe .NET enum utility library
* [FluentValidation ★2237](JeremySkinner/FluentValidation) - Small validation library for .NET that uses a fluent interface and lambda expressions for building validation rules.
* [Humanizer ★2655](Humanizr/Humanizer) - Humanizer meets all your .NET needs for manipulating and displaying strings, enums, dates, times, timespans, numbers and quantities.
* [LibSass Host ★12](Taritsyn/LibSassHost) - .NET wrapper around the [libSass](http://sass-lang.com/libsass) library with the ability to support a virtual file system.
* [markdig ★557](lunet-io/markdig) - Fast, powerfull, CommonMark compliant, extensible Markdown processor for .NET.
* [Microphone ★369](rogeralsing/Microphone) - Lightweight framework to run self hosting REST services using Web Api or NancyFx ontop of a Consul or ETCD cluster.
* [NReco.LambdaParser ★26](nreco/lambdaparser) - Parses string expressions (formulas, methods calls, conditions) to LINQ expression tree that can be compiled to lambda and evaluated. 
* [NReco.PivotData](https://www.nuget.org/packages/NReco.PivotData/) - In-memory data cube with OLAP operations and PivotTable data model.
* [Ocelot ★297](TomPallister/Ocelot) - API Gateway created using .NET Core.
* [readline ★386](tsolarin/readline) - Pure C# GNU-Readline like library for .NET/.NET Core.
* [reCAPTCHA ★30](PaulMiami/reCAPTCHA) - reCAPTCHA 2.0 for ASP.NET Core.
* [Relinq ★173](re-motion/Relinq) - With re-linq, it's now easier than ever to create full-featured LINQ providers.
* [PdfReport.Core ★38](VahidN/PdfReport.Core) - PdfReport.Core is a code first reporting engine, which is built on top of the iTextSharp.LGPLv2.Core and EPPlus.Core libraries.
* [PreStorm ★8](jshirota/PreStorm) - Parallel REST Client for ArcGIS Server.
* [Polly ★2366](App-vNext/Polly) - .NET 3.5 / 4.0 / 4.5 / PCL library that allows developers to express transient exception and fault handling policies such as Retry, Retry Forever, Wait and Retry or Circuit Breaker in a fluent manner.
* [Scrutor ★131](khellang/Scrutor) - Assembly scanning extensions for Microsoft.Extensions.DependencyInjection.
* [sharpcompress ★447](adamhathcock/sharpcompress) - Fully managed C# library to deal with many compression types and formats.
* [SmartFormat.NET ★283](scottrippey/SmartFormat.NET) - An extensible replacement for string.Format.
* [System.Linq.Dynamic.Core ★57](StefH/System.Linq.Dynamic.Core) - The .NET Standard (.NET Core) version from the System Linq Dynamic functionality.
* [warden-stack](https://github.com/warden-stack) - "health checks" for your applications, resources and infrastructure. Keep your Warden on the watch.

### ORM
* [Entity Framework Core ★4598](aspnet/EntityFramework) - Familiar developer experience to previous versions of EF, including LINQ, POCO, and Code First support.
* [Dapper](https://github.com/StackExchange/dapper-dot-net/tree/netstandard) - Simple object mapper for .NET.
 * [Dapper-FluentMap ★98](henkmollema/Dapper-FluentMap) - Provides a simple API to fluently map POCO properties to database columns when using Dapper.
 * [Dommel ★53](henkmollema/Dommel) - Simple CRUD operations for Dapper.
* [Limebean](https://nick-lucas.github.io/LimeBean/) - Hybrid-ORM, designed to be simple to use and not totally hide SQL, while having all the nice things you expect from an ORM. Inspired by RedBeanPHP.
* [marten ★518](JasperFx/marten) - Postgresql as a Document Database and Event Store for .NET Applications [http://jasperfx.github.io/marten](http://jasperfx.github.io/marten).
* [NEventStore](https://github.com/NEventStore/NEventStore/tree/feature/dotnetcore) - Persistence library used to abstract different storage implementations when using event sourcing as storage mechanism. This library is developed with a specific focus on DDD/CQRS applications.
* [NoDb ★78](joeaudette/NoDb) - "no database" file system storage for .NET Core/ASP.NET Core because not every project needs a database.
* [NPoco ★464](schotime/NPoco) - Simple microORM that maps the results of a query onto a POCO object. Project based on Schotime's branch of PetaPoco.
* [NReco.Data ★35](nreco/data) - Lightweight provider-independent DAL for SQL commands generation, CRUD operations and simple POCO mapping.
* [ServiceStack.OrmLite ★916](ServiceStack/ServiceStack.OrmLite) - Light, simple and fast convention-based POCO ORM.
* [SqlFu ★192](sapiens/SqlFu) - Fast and versatile Micro-ORM.
* [yessql ★288](sebastienros/yessql) - .NET document database working on any RDBMS.

### Profiling
* [Glimpse](http://getglimpse.com) - Lightweight, open-source, real-time diagnostics and insights profiler for .NET. 
* [MiniProfiler ★922](MiniProfiler/dotnet) - A simple but effective mini-profiler for ASP.NET websites.

### Queue and Messaging
* [emitter](https://emitter.io/) - Free open source real-time messaging service that connects all devices. This publish-subscribe messaging API is built for speed and security.
* [EventStore ★1988](EventStore/EventStore) - The open-source, functional database with Complex Event Processing in JavaScript. [https://geteventstore.com](https://geteventstore.com)
* [MediatR ★1068](jbogard/MediatR) - Simple, unambitious mediator implementation in .NET.
 * [MediatR.Extensions.Microsoft.DependencyInjection ★10](jbogard/MediatR.Extensions.Microsoft.DependencyInjection) - MediatR extensions for Microsoft.Extensions.DependencyInjection.
* [Mediator.Net ★74](mayuanyang/Mediator.Net) - A simple mediator for .Net for sending command, publishing event and request response with pipelines supported.
* [MicroBus ★90](Lavinski/Enexure.MicroBus) - Simple in process mediator for .NET.
* [netmq ★1045](zeromq/netmq) - 100% native C# implementation of ZeroMQ for .NET.
* [rabbitmq-dotnet-client ★391](rabbitmq/rabbitmq-dotnet-client) - RabbitMQ .NET client [https://www.rabbitmq.com](https://www.rabbitmq.com).
* [RawRabbit ★216](pardahlman/RawRabbit) - Modern .NET framework for communication over RabbitMq.
* [Rebus ★558](rebus-org/Rebus) - Simple and lean service bus implementation for .NET.
* [Restbus](http://restbus.org) - Messaging library for RabbitMq.

### Scheduler and Job
* [Chroniton.NetCore ★83](leosperry/Chroniton) - Lightweight robust library for running tasks(jobs) on schedules. 
* [FluentScheduler ★880](fluentscheduler/FluentScheduler) - Automated job scheduler with fluent interface.
* [HangfireIO ★2669](HangfireIO/Hangfire) - Easy way to perform fire-and-forget, delayed and recurring tasks inside ASP.NET apps [http://hangfire.io](http://hangfire.io).
* [quartznet](https://github.com/quartznet/quartznet/tree/quartznet-3) - Quartz Enterprise Scheduler .NET [http://www.quartz-scheduler.net](http://www.quartz-scheduler.net).
* [stateless ★1588](dotnet-state-machine/stateless) - Simple library for creating state machines in C# code.

### SDKs
* [AWS SDK ★630](aws/aws-sdk-net) - The Amazon Web Services (AWS) .NET Core SDK components. Each AWS service has its own NuGet package.
* [azure-event-hubs-dotnet ★30](azure/azure-event-hubs-dotnet) - .NET Standard client library for Azure Event Hubs.
* [NBitcoin ★370](MetacoSA/NBitcoin) - Comprehensive Bitcoin library for the .NET framework.
* [NetTelegramBotApi ★36](justdmitry/NetTelegramBotApi) - C# client library for building Telegram bot [https://core.telegram.org/bots/api](https://core.telegram.org/bots/api).
* [octokit.net](https://github.com/octokit/octokit.net/tree/target-the-coreclr) - GitHub API client library for .NET.
* [Open-XML-SDK-for-NET-Platform-Standard ★19](xrkolovos/Open-XML-SDK-for-NET-Platform-Standard) - .NET Platform Standard implementation of Open XML SDK 2.5.
* [SendGrid-csharp ★361](sendgrid/sendgrid-csharp) - C# client library for using the full SendGrid API.
* [statsd-csharp-client](https://github.com/Pereingo/statsd-csharp-client) - .NET Standard compatible C# client to interface with Etsy's excellent [statsd ★11427](etsy/statsd) server.
* [tweetinvi](https://github.com/linvi/tweetinvi/tree/tweetinvi.netcore) - Intuitive .NET C# library to access the Twitter REST and STREAM API.

### Security
* [HtmlSanitizer ★304](mganss/HtmlSanitizer) - Cleans HTML to avoid XSS attacks.
* [jose-jwt ★272](dvsekhvalnov/jose-jwt) - Library for processing JOSE objects (JWT, JWA, JWS and related).
* [NWebsec ★185](NWebsec/NWebsec) - Security libraries for ASP.NET [https://www.nwebsec.com](https://www.nwebsec.com).
* [roslyn-security-guard ★92](dotnet-security-guard/roslyn-security-guard) - Roslyn analyzers that aim to help security audit on .NET applications. 
* [Security ★547](aspnet/Security) - Middleware for security and authorization of web apps.

### Searching
* [AutoComplete ★12](omerfarukz/autocomplete) - Persistent, simple, powerful and portable autocomplete library.
* [Elasticsearch.Net & NEST ★1397](elastic/elasticsearch-net) - Repository for both NEST and Elasticsearch.NET, the two official elasticsearch .NET clients.
* [ElasticsearchCRUD ★84](damienbod/ElasticsearchCRUD) - Elasticsearch .NET API.
* [SolrExpress ★36](solr-express/solr-express) - Simple and lightweight query .NET library for Solr, in a controlled, buildable and fail fast way.

### Serialization
* [bond ★1556](Microsoft/bond) - Cross-platform framework for working with schematized data. It supports cross-language de/serialization and powerful generic mechanisms for efficiently manipulating data. Bond is broadly used at Microsoft in high scale services.
* [Channels ★283](davidfowl/Channels) - Push based .NET Streams.
* [CsvHelper ★1232](JoshClose/CsvHelper) - Library to help reading and writing CSV files [http://csvhelper.com](http://csvhelper.com).
* [Edi.Net ★42](indice-co/EDI.Net) - EDI Serializer/Deserializer. Supports EDIFact, X12 and TRADACOMS format.
* [ExtendedXmlSerializer ★25](wojtpl2/ExtendedXmlSerializer) - Extended Xml Serializer for .NET.
* [Jil ★1535](kevin-montrose/Jil) - Fast .NET JSON (De)Serializer, Built On Sigil.
* [msgpack-cli ★450](msgpack/msgpack-cli) - MessagePack implementation for Common Language Infrastructure / [msgpack.org](http://msgpack.org).
* [Newtonsoft.Json ★4285](JamesNK/Newtonsoft.Json) - Popular high-performance JSON framework for .NET.
* [protobuf-net ★1361](mgravell/protobuf-net) - Protocol Buffers library for idiomatic .NET.
* [ServiceStack.Text ★823](ServiceStack/ServiceStack.Text) - JSON, JSV and CSV Text Serializers.
* [TinyCsvParser ★35](bytefish/TinyCsvParser) - Easy to use, easy to extend and high-performance library for CSV parsing with .NET.
* [Wire ★273](rogeralsing/Wire) - Binary serializer for POCO objects.
* [YamlDotNet ★485](aaubry/YamlDotNet) - .NET 
* [ZeroFormatter ★657](neuecc/ZeroFormatter) - Fast binary (de)serializer for .NET.
* [YAXLib ★59](sinairv/YAXLib) - XML Serialization Library for the .NET Framework and .NET Core. Extremely flexible and powerful.

### Testing
* [Bogus ★390](bchavez/Bogus) - Simple and sane fake data generator for C#. Based on and ported from the famed faker.js.
* [GenFu ★229](MisterJames/GenFu) - Library you can use to generate realistic test data.
* [FakeItEasy ★654](FakeItEasy/FakeItEasy) - The easy mocking library for .NET.
* [FluentAssertions ★3](dennisdoomen/FluentAssertions) - Set of .NET extension methods that allow you to more naturally specify the expected outcome of a TDD or BDD-style test.
* [moq.netcore ★1791](Moq/moq4) - Most popular and friendly mocking framework for .NET.
* [MSpec ★662](machine/machine.specifications) - Popular testing framework for writing BDD-style tests.
* [MyTested.AspNetCore.Mvc ★649](ivaylokenov/MyTested.AspNetCore.Mvc) - Fluent testing
  framework for ASP.NET Core MVC.
* [Netling ★721](hallatore/Netling) - Load tester client for easy web testing.
* [NSpec ★181](nspec/NSpec) - Battle hardened testing framework for C# that's heavily inspired by Mocha and RSpec.
* [NSubstitute ★794](nsubstitute/NSubstitute) - A friendly substitute for .NET mocking frameworks.
* [nunit ★51](nunit/dotnet-test-nunit) - NUnit test runner for .NET Core.
* [shouldly ★588](shouldly/shouldly) - Should testing for .NET - the way Asserting *Should* be! [http://shouldly.readthedocs.org/en/latest](http://shouldly.readthedocs.org/en/latest)
* [SpecFlow](https://github.com/techtalk/SpecFlow/tree/DotNetCore) - Pragmatic BDD solution for .NET. It uses the Gherkin specification language and integrates to Visual Studio.
* [Storyteller ★178](storyteller/Storyteller) - Executable Specifications for .NET [http://storyteller.github.io](http://storyteller.github.io).
* [Stubbery](https://markvincze.github.io/Stubbery/) - A simple library for creating and running Api stubs in .NET.
* [TestStack.BDDfy ★213](TestStack/TestStack.BDDfy) - The simplest BDD framework EVER!
* [xunit ★1359](xunit/xunit) - Free, open source, community-focused unit testing tool for the .NET Framework.

### Tools
* [CatLight](https://catlight.io) - Status notifier for developers that monitors builds and tasks in the project. Built using .Net Core and Electron.
* [docfx ★665](dotnet/docfx) - Tools for building and publishing API documentation for .NET projects [http://dotnet.github.io/docfx](http://dotnet.github.io/docfx)
* [dotnetfiddle](https://dotnetfiddle.net) - .NET sandbox for developers to quickly try out code and share code snippets.
* [EntryPoint ★68](Nick-Lucas/EntryPoint) - Composable CLI (Command Line) Argument Parser for .Net Core & .Net Framework 4.5+.
* [gitignore.io ★2262](joeblau/gitignore.io) - Create useful .gitignore files for your project [https://www.gitignore.io](https://www.gitignore.io).
* [GitInfo ★51](kzu/GitInfo) - Git and SemVer Info from MSBuild, C# and VB.
* [ICanHasDotnetCore ★36](OctopusDeploy/ICanHasDotnetCore) - Scans uploaded packages.config files or GitHub repository and determines whether the nuget packages target .NET Standard [https://icanhasdot.net](https://icanhasdot.net).
* [json2csharp](http://json2csharp.com) - Generate C# classes from JSON.
* [OctoLinker ★2149](OctoLinker/browser-extension) - Navigate through `projects.json` files efficiently with the OctoLinker browser extension for GitHub.
* [Opserver ★3027](opserver/Opserver) - Stack Exchange's Monitoring System.
* [ShareX ★5743](ShareX/ShareX) - Free and open source program that lets you capture or record any area of your screen and share it with a single press of a key. It also allows uploading images, text or other types of files to over 80 supported destinations you can choose from. [https://getsharex.com](https://getsharex.com)
* [X.Web.Sitemap ★11](dncuug/X.Web.Sitemap) – Simple sitemap generator for .NET and .NET Core
* [X.Web.RSS ★4](dncuug/X.Web.RSS) – Simple RSS Feed generator for .NET and .NET Core

### Web Framework
* [ReactJS.NET ★1081](reactjs/React.NET) - .NET library for JSX compilation and server-side rendering of React components.
* [redux.NET](https://github.com/GuillaumeSalles/redux.NET) - Predictable state container for .NET apps. Inspired by [https://github.com/reactjs/redux ★31252](reactjs/redux).
* [RService.io ★15](Stoom/RService.IO) - ASP.Net Core RESTful microservice framework that focusing on speed and ease of use.

### Web Socket
* [SignalR Server ★590](aspnet/signalr) - Real-time web functionality for web apps, including server-side push.
* [WampSharp ★181](Code-Sharp/WampSharp) - C# implementation of [The Web Application Messaging Protocol](http://wamp-proto.org/) - Protocol that provides messaging patterns of Remote Procedure Calls and Publish/Subscribe over WebSockets.

### Windows Service
* [dotnet-win32-service ★158](dasMulli/dotnet-win32-service) - Set up and run as Windows Service directly from .NET Core.
* [Topshelf ★1905](Topshelf/Topshelf) - Easy service hosting framework for building Windows services using .NET. `4.5.x or above`

## Starter Kits
* [ASP.NET Core Starter Kit ★698](kriasoft/aspnet-starter-kit) - Opinionated boilerplate for web development based on .NET Core, Kestrel, GraphQL on the backend and Babel, Webpack, React and Redux on the frontend. This boilerplate comes in both C# and F# flavors.
* [ASP.NET Boilerplate ★2746](aspnetboilerplate/aspnetboilerplate) - ASP.NET Boilerplate is a starting point for new modern web applications using best practices and most popular tools. It's aimed to be a SOLID model, a general-purpose application framework and a project template. `4.5.x or above`
* [aspnetcore-spa generator ★2066](aspnet/JavaScriptServices) - Yeoman generator to build a brand-new ASP.NET Core single page application that uses Angular 2 / React / React With Redux / Knockout / Aurelia on the client.
* [bitwarden-core ★448](bitwarden/core) - The core infrastructure backend (API, database, etc) [https://bitwarden.com](https://bitwarden.com).
* [dotNetify ★194](dsuryd/dotNetify) - Simple, lightweight, yet powerful way to build real-time HTML5/C# .NET web apps.
* [generator-aspnet ★834](OmniSharp/generator-aspnet) - yo generator for ASP.NET Core.
* [react-aspnet-boilerplate ★237](pauldotknopf/react-aspnet-boilerplate) - Starting point for building isomorphic React applications with ASP.NET Core 1, leveraging existing techniques.
* [saaskit ★482](saaskit/saaskit) - Developer toolkit for building SaaS applications.

## Sample Projects
* [AlbumViewerVNext ★211](RickStrahl/AlbumViewerVNext) - West Wind Album Viewer ASP.NET 5 Sample.
* [allReady ★539](HTBox/allReady) - Open-source solution focused on increasing awareness, efficiency and impact of preparedness campaigns as they are delivered by humanitarian and disaster response organizations in local communities. [http://www.htbox.org/projects/allready](http://www.htbox.org/projects/allready)
* [AspNet5GeoElasticsearch ★16](damienbod/AspNet5GeoElasticsearch) - ASP.NET Core MVC Geo Elasticsearch Swashbuckle Swagger.
* [aspnet-servicediscovery-patterns ★74](cecilphillip/aspnet-servicediscovery-patterns) - Samples of implementing Service Discovery patterns with ASP.NET Core.
* [AspNetAuthorizationWorkshop ★393](blowdart/AspNetAuthorizationWorkshop) - A workshop for moving through the various new pieces in ASP.NET Core Authorization
* [BikeSharing360 Suite of Apps from Microsoft](https://blogs.msdn.microsoft.com/visualstudio/2016/12/14/connectdemos-2016-bikesharing360-on-github/) Presented December Connect 2016 Conference, a compreshsive set of interworking apps for both enterprise users and the consumers (bike riders):
 [Mobile Apps](https://github.com/Microsoft/BikeSharing360_MobileApps), [Backend Services](https://github.com/Microsoft/BikeSharing360_BackendServices), [Websites](https://github.com/Microsoft/BikeSharing360_Websites), [Single Container Apps](https://github.com/Microsoft/BikeSharing360_SingleContainer), [Multi Container Apps](https://github.com/Microsoft/BikeSharing360_MultiContainer), [Cognitive Services Kiosk App ★20](Microsoft/BikeSharing360_CognitiveServicesKioskApp),
 [Azure Bot App ★19](Microsoft/BikeSharing360_BotApps).
* [cloudscribe ★429](joeaudette/cloudscribe) - ASP.NET Core Multi-tenant web application foundation.
* [CoreCodeCamp ★16](shawnwildermuth/CoreCodeCamp) - An Open Source Website for running small, local development events.
* [distributed-playground ★13 ⏳1Y](jvandevelde/distributed-playground) - Distributed service playground with Vagrant, Consul, Docker & ASP.NET Core.
* [DotNetClub ★189](scheshan/DotNetClub) - Tiny club written in ASP.NET Core.
* [Entropy ★267](aspnet/Entropy) - Chaotic experimental playground for new features and ideas - check here for small and simple samples for individual features.
* [eShopOnContainers](https://github.com/dotnet/eShopOnContainers) - Microservices Architecture and Containers based Reference Application.
* [guidance-identity-management-for-multitenant-apps ★42](Azure-Samples/guidance-identity-management-for-multitenant-apps) - How to manage user identities in a multitenant app on Microsoft Azure, using Azure Active Directory for authentication.
* [magazine-website ★65](thangchung/magazine-website) - Magazine website (using .NET Core, ASP.NET Core, EF Core) with DDD, CQRS, microservices, asynchronous programming applied.
* [MegaMine ★17](Nootus/MegaMine) - Open source mining solution that helps miners in extracting Gold, Quartz, Granite etc. This solution is built using ASP.NET Core and AngularJS utilizing multiple light weight components in a Microservices way.
* [minicompiler ★6](ealsur/minicompiler) - Minification, bundling and compiling sample.
* [MusicStore ★1040](aspnet/MusicStore) - Sample MusicStore application that uses MVC and Entity Framework.
* [ReactiveTraderCloud ★576](AdaptiveConsulting/ReactiveTraderCloud) - Real-time trading platform demo showcasing reactive programming principles applied across the full application stack.
* [PhotoGallery ★303](chsakell/aspnet5-angular2-typescript) - Cross-platform Single Page Applications with ASP.NET Core, Angular 2 & TypeScript [http://wp.me/p3mRWu-11L](http://wp.me/p3mRWu-11L).
* [Practical ASP.NET Core ★468](dodyg/practical-aspnetcore) - A daily updated micro samples of ASP.NET Core features and facilities. 

## Articles 
* Basic knowledge
  * [A guide to the .NET Core projects on GitHub](https://blog.rendle.io/a-guide-to-the-net-projects-on-github/)
  * [Microsoft architectual overview of comprehensive BikeSharing360 suite of demo apps with related videos](https://blogs.msdn.microsoft.com/visualstudio/2016/12/14/connectdemos-2016-bikesharing360-on-github/)
  * [Porting .NET Framework Library to .NET Core](http://www.michael-whelan.net/porting-dotnet-framework-library-to-dotnet-core)
  * [The 68 things the CLR does before executing a single line of your code](http://mattwarren.org/2017/02/07/The-68-things-the-CLR-does-before-executing-a-single-line-of-your-code/)
  * The comparison between .NET Core and Nodejs at [here](https://manuel-rauber.com/2016/03/07/node-js-asp-net-core-1-0-a-usage-comparison/), [here](https://gist.github.com/ilyaigpetrov/f6df3e6f825ae1b5c7e2) and [here ★46 ⏳1Y](thinktecture/nodejs-aspnetcore-webapi)
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
  * [A very good example about EF Core ★79](rowanmiller/Demo-EFCore)
* Miraculous
  * [Vue.js server side rendering with ASP.NET Core](http://mgyongyosi.com/2016/Vuejs-server-side-rendering-with-aspnet-core/)
* Security
  * [.NET Continuous Delivery Microservices](http://stackshare.io/tomstaijen/net-continuous-delivery-microservices)
  * [A walk-through for an ASP.NET Authorization Lab ★393](blowdart/AspNetAuthorizationWorkshop)
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
	This list is a copy of <a href="thangchung/awesome-dotnet-core">thangchung/awesome-dotnet-core</a> with ranks
</p>
<script>
  (function(i,s,o,g,r,a,m){i['GoogleAnalyticsObject']=r;i[r]=i[r]||function(){
  (i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),
  m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)
  })(window,document,'script','https://www.google-analytics.com/analytics.js','ga');

  ga('create', 'UA-100705027-1', 'auto');
  ga('send', 'pageview');

</script>
