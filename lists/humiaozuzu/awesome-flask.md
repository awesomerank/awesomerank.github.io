---
layout: default
title: Awesome Rank for humiaozuzu/awesome-flask
---

<p align="center">
	This list is a copy of <a href="https://github.com/humiaozuzu/awesome-flask">humiaozuzu/awesome-flask</a> with ranks
</p>
---
# Awesome Flask [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg) ★87749](https://github.com/sindresorhus/awesome)

> A curated list of awesome Flask resources and plugins

- [Awesome Flask](#awesome-flask)
  - [Framework](#framework)
  - [Admin interface](#admin-interface)
  - [Authentication](#authentication)
  - [Authorization](#authorization)
  - [Database](#database)
  - [Database Migrations](#database-migrations)
  - [Session](#session)
  - [Cache](#cache)
  - [Data Validation](#data-validation)
  - [Email](#email)
  - [i18n](#i18n)
  - [Full-text searching](#full-text-searching)
  - [Rate Limiting](#rate-limiting)
  - [Task Queue](#task-queue)
  - [Exception tracking](#exception-tracking)
  - [Tracing](#tracing)
  - [APM](#apm)
  - [Other SDK](#other-sdk)
  - [Frontend](#frontend)
  - [Development (Debugging/Testing/Documentation)](#development-debuggingtestingdocumentation)
  - [Utils](#utils)
- [Resources](#resources)
  - [Tutorials](#tutorials)
  - [Courses](#courses)
  - [Books](#books)
  - [Slides](#slides)
  - [Videos](#videos)
  - [Built with Flask](#built-with-flask)
  - [Boilerplate](#boilerplate)

## Framework

- [Connexion ★1281](https://github.com/zalando/connexion) - Swagger/OpenAPI First framework for Python on top of Flask with automatic endpoint validation and OAuth2 support
- [Flask-MongoRest ★425](https://github.com/closeio/flask-mongorest) - Restful API framework wrapped around MongoEngine
- [Eve ★5066](https://github.com/pyeve/eve) - REST API framework powered by Flask, MongoDB and good intentions
- [Flask-Restless ★895](https://github.com/jfinkels/flask-restless) - A Flask extension for creating simple ReSTful APIs from SQLAlchemy models
- [Flask-RESTful ★3767](https://github.com/flask-restful/flask-restful) - Simple framework for creating REST APIs
- [Flask-RestPlus ★973](https://github.com/noirbizarre/flask-restplus) - syntaxic sugar, helpers and automatically generated Swagger documentation.
- [Flask-Potion ★417](https://github.com/biosustain/potion) - RESTful API framework for Flask and SQLAlchemy
- [Zappa ★7256](https://github.com/Miserlou/Zappa) - Build and deploy server-less Flask applications on AWS Lambda and API Gateway

## Admin interface

- [Flask-Admin ★2982](https://github.com/flask-admin/flask-admin) - Simple and extensible administrative interface framework for Flask

## Authentication

- [Flask-Security ★1186](https://github.com/mattupstate/flask-security) - Quick and simple security for Flask applications
- [Flask-Login ★1745](https://github.com/maxcountryman/flask-login) - Flask user session management
- [Flask-User ★654](https://github.com/lingthio/Flask-User) - Customizable user account management for Flask
- [Flask-HTTPAuth ★481](https://github.com/miguelgrinberg/Flask-HTTPAuth) - Simple extension that provides Basic and Digest HTTP authentication for Flask routes

## Authorization

- [Authlib ★488](https://github.com/lepture/authlib) - Authlib is an ambitious authentication library for OAuth 1, OAuth 2, OpenID clients, servers and more.
- [Authomatic ★867](https://github.com/authomatic/authomatic) - Authomatic provides out of the box support for a number of providers using OAuth 1.0a (Twitter, Tumblr and more) and OAuth 2.0 (Facebook, Foursquare, GitHub, Google, LinkedIn, PayPal and more)
- [Flask-Pundit](https://github.com/anurag90x/flask-pundit) - Extension based on Rails' [Pundit ★5891](https://github.com/varvet/pundit) gem that provides easy way to organize access control for your models

## Database

- [Flask-MongoEngine ★549](https://github.com/MongoEngine/flask-mongoengine) - MongoEngine flask extension with WTF model forms support
- [Flask-SQLAlchemy ★2111](https://github.com/mitsuhiko/flask-sqlalchemy) - Adds SQLAlchemy support to Flask

## Database Migrations

- [Flask-Migrate ★942](https://github.com/miguelgrinberg/Flask-Migrate) - SQLAlchemy database migrations for Flask applications using Alembic

## Session

- [Flask-Session ★201](https://github.com/fengsp/flask-session) - Server side session extension for Flask

## Cache

- [Flask-Caching ★200](https://github.com/sh4nks/flask-caching) - Adds easy cache support to Flask
- [flask-heroku-cacheify ★32](https://github.com/rdegges/flask-heroku-cacheify) - Automatic Flask cache configuration on Heroku

## Data Validation

- [Flask-WTF ★773](https://github.com/lepture/flask-wtf) - Simple integration of Flask and WTForms, including CSRF, file upload and Recaptcha integration.

## Email

- [Flask-Mail ★364](https://github.com/mattupstate/flask-mail) - Flask-Mail adds SMTP mail sending to your Flask applications

## i18n

- [flask-babel ★267](https://github.com/python-babel/flask-babel) - i18n and l10n support for Flask based on Babel and pytz

## Full-text searching

- [SQLAlchemy-Searchable ★106](https://github.com/kvesteri/sqlalchemy-searchable) - Full-text searching for Flask-SQLAlchemy (Postgres only)
- [flask_msearch ★43](https://github.com/honmaple/flask-msearch) - Full text search for flask with whoosh

## Rate Limiting

- [Flask-Limiter ★330](https://github.com/alisaifee/flask-limiter) - Flask-Limiter provides rate limiting features to flask routes

## Task Queue

- [dramatiq ★802](https://github.com/Bogdanp/dramatiq) - A fast and reliable distributed task processing library for Python 3
- [huey ★1803](https://github.com/coleifer/huey) - a little task queue for python
- [Flask-RQ ★160 ⏳1Y](https://github.com/mattupstate/flask-rq) - RQ (Redis Queue) integration for Flask applications
- [celery ★9648](https://github.com/celery/celery) - Distributed Task Queue

## Exception tracking

- [Raven ★1457](https://github.com/getsentry/raven-python) - Raven is a Python client for [Sentry](https://sentry.io/welcome/).
- [airbrake-python ★37](https://github.com/airbrake/airbrake-python) - Python client for [Airbrake](https://airbrake.io/)

## Tracing

- [flask-zipkin ★19](https://github.com/qiajigou/flask-zipkin) - Distributed tracing with [Zipkin](https://zipkin.io/).
- [Flask-OpenTracing ★29](https://github.com/opentracing-contrib/python-flask) - Distributed tracing with [OpenTracing](http://opentracing.io/).

## APM

- [elastic-apm ★61](https://github.com/elastic/apm-agent-python) - Elastic APM agent for Python

## Other SDK

- [Flask-GoogleMaps ★372](https://github.com/rochacbruno/Flask-GoogleMaps) - Build and embed google maps in our Flask templates
- [Flask-Gravatar ★71](https://github.com/zzzsochi/Flask-Gravatar) - Small and simple gravatar usage in Flask
- [Flask-Pusher ★5](https://github.com/iurisilvio/Flask-Pusher) - Pusher integration for Flask
- [Flask-Azure-Storage ★5](https://github.com/alejoar/Flask-Azure-Storage) - Flask extension that provides integration with Azure Storage

## Frontend

- [Flask-CORS ★403](https://github.com/corydolphin/flask-cors) - A Flask extension for handling Cross Origin Resource Sharing (CORS), making cross-origin AJAX possible
- [flask-assets ★349 ⏳1Y](https://github.com/miracle2k/flask-assets) - Flask webassets integration
- [flask-s3 ★138](https://github.com/e-dard/flask-s3) - Seamlessly serve your static assets of your Flask app from Amazon S3
- [Flask-SSLify ★434](https://github.com/kennethreitz/flask-sslify) - Force SSL on your Flask app
- [Flask-HTMLmin ★37](https://github.com/hamidfzm/Flask-HTMLmin) - Flask html minifier

## Development (Debugging/Testing/Documentation)

- [Flasgger ★872](https://github.com/rochacbruno/flasgger) - Create API documentation for Flask views using Swagger 2.0 specs
- [flask-apispec ★256](https://github.com/jmcarp/flask-apispec) - simple self-documenting APIs with flask
- [flask2postman ★84](https://github.com/numberly/flask2postman) - Generate a Postman collection from your Flask application
- [flask_profiler ★393](https://github.com/muatik/flask-profiler) - endpoint analyzer/profiler for Flask
- [Flask-DebugToolbar ★646](https://github.com/mgood/flask-debugtoolbar) - A port of the django debug toolbar to flask
- [flask-debug-toolbar-mongo ★3 ⏳1Y](https://github.com/cenkalti/flask-debug-toolbar-mongo) - MongoDB panel for the Flask Debug Toolbar
- [Flask-Testing ★367](https://github.com/jarus/flask-testing) - Unittest extensions for Flask
- [pytest-flask ★162 ⏳1Y](https://github.com/pytest-dev/pytest-flask) - A set of pytest fixtures to test Flask applications
- [Flask-MonitoringDashboard ★26](https://github.com/flask-dashboard/Flask-MonitoringDashboard) - Automatically monitor the evolving performance of Flask/Python web services.

## Utils

- [flask-marshmallow ★321](https://github.com/marshmallow-code/flask-marshmallow) Flask + marshmallow for beautiful APIs
- [flask-jsonrpc ★136](https://github.com/cenobites/flask-jsonrpc) - A basic JSON-RPC implementation for your Flask-powered sites
- [Flask-Bcrypt ★203](https://github.com/maxcountryman/flask-bcrypt) - Flask-Bcrypt is a Flask extension that provides bcrypt hashing utilities for your application
- [Mixer ★510](https://github.com/klen/mixer) - Mixer is application to generate instances of Django or SQLAlchemy models
- [Flask-FeatureFlags ★99](https://github.com/trustrachel/Flask-FeatureFlags) - A Flask extension that enables or disables features based on configuration
- [Flask-Reggie ★42 ⏳5Y](https://github.com/rhyselsmore/flask-reggie) - Regex Converter for Flask URL Routes
- [Flask-SocketIO ★2340](https://github.com/miguelgrinberg/Flask-SocketIO) - Socket.IO integration for Flask applications
- [Flask-Moment ★194](https://github.com/miguelgrinberg/Flask-Moment) - Formatting of dates and times in Flask templates using moment.js
- [Flask-Paginate ★150](https://github.com/lixxu/flask-paginate) - Pagination support for Flask

# Resources
## Tutorials

- [How to build a news app that never goes down and costs you practically nothing](http://blog.apps.npr.org/2013/02/14/app-template-redux.html) (by NPR)
- [Building websites in Python with Flask](http://maximebf.com/blog/2012/10/building-websites-in-python-with-flask/)
- [The Flask Mega-Tutorial](https://blog.miguelgrinberg.com/post/the-flask-mega-tutorial-part-i-hello-world)
- [Implementing a RESTful Web API with Python & Flask](http://blog.luisrei.com/articles/flaskrest.html)
- [Discover Flask - Full Stack Web Development with Flask ★3110](https://github.com/realpython/discover-flask)
- [Flaskr - Intro to Flask, Test Driven Development, and jQuery ★1143](https://github.com/mjhea0/flaskr-tdd)

## Courses

- [Full Stack Foundations](https://www.udacity.com/course/full-stack-foundations--ud088)
- [Designing RESTful APIs](https://www.udacity.com/course/designing-restful-apis--ud388)

## Books

- [Explore Flask](https://exploreflask.com/en/latest/)
- [Flask Web Development](http://shop.oreilly.com/product/0636920031116.do)
- [Real Python](https://realpython.com)
- [Learning Flask Framework](https://www.packtpub.com/web-development/learning-flask-framework)
- [Flask Blueprints](https://www.packtpub.com/web-development/flask-blueprints)
- [Flask Framework Cookbook](https://www.packtpub.com/web-development/flask-framework-cookbook)
- [Mastering Flask](https://www.packtpub.com/web-development/mastering-flask)
- [Building Web Applications with Flask](https://www.packtpub.com/web-development/building-web-applications-flask)

## Slides

- [Creating beautiful REST APIs with Flask](http://pycoder.net/bospy/presentation.html)
- [Advanced Flask Patterns](https://speakerdeck.com/mitsuhiko/advanced-flask-patterns)
- [Flasky Goodness](https://speakerdeck.com/kennethreitz/flasky-goodness)
- [Domain Driven Design (... with Flask)](https://speakerdeck.com/mikedebo/domain-driven-design-dot-dot-dot-with-flask)
- [In Flask we Trust](https://speakerdeck.com/playpauseandstop/in-flask-we-trust)

## Videos

- [Flask by Example](http://pyvideo.org/video/2608/flask-by-example/)
- [Writing RESTful web services with Flask](http://pyvideo.org/video/2668/writing-restful-web-services-with-flask/)
- [Practical Flask Web Development Tutorials](https://www.youtube.com/playlist?list=PLQVvvaa0QuDc_owjTbIY4rbgXOFkUYOUB)

## Built with Flask

- [zmusic-ng](https://git.zx2c4.com/zmusic-ng/) - ZX2C4 Music provides a web interface for playing and downloading music files using metadata.
- [GuitarFan ★40 ⏳3Y](https://github.com/lowrain/GuitarFan) - guitar tab
- [June ★1071 ⏳3Y](https://github.com/pythoncn/june) - ~~python-china.org~~
- [Zerqu ★156 ⏳1Y](https://github.com/lepture/zerqu) - ZERQU is a content-focused API-based platform. eg: [Python-China](https://python-china.org)
- [motiky ★41 ⏳5Y](https://github.com/notedit/motiky)
- [missing ★9 ⏳5Y](https://github.com/notedit/missing) - a list service called missing
- [thenewsmeme.com ★73 ⏳7Y](https://github.com/danjac/newsmeme)
- [overholt ★1400 ⏳2Y](https://github.com/mattupstate/overholt) - Example Flask application illustrating common practices
- [pypress ★526 ⏳1Y](https://github.com/laoqiu/pypress) - flask team blog
- [thepast.me ★755 ⏳3Y](https://github.com/laiwei/thepast)
- [redispapa ★367 ⏳1Y](https://github.com/no13bus/redispapa) - another redis monitor by using flask, angular, socket.io
- [flaskblog ★151 ⏳1Y](https://github.com/defshine/flaskblog) - a simple blog system based on flask
- [cleanblog ★97 ⏳1Y](https://github.com/defshine/cleanblog) - a clean blog system based on flask and mongoengine
- [Quokka CMS ★1883](https://github.com/rochacbruno/quokka) - CMS made with Flask and MongoDB
- [chat ★283 ⏳6Y](https://github.com/lzyy/chat) - a live chat built with python (flask + gevent + apscheduler) + redis
- [chatapp](https://github.com/vinceprignano/chatapp) - Flask and Angular.js Chat Application using Socket.io
- [Frozen-Flask ★535](https://github.com/Frozen-Flask/Frozen-Flask) - Freezes a Flask application into a set of static files
- [mcflyin ★70 ⏳4Y](https://github.com/wrobstory/mcflyin) - A small timeseries transformation API built on Flask and Pandas
- [Skylines ★169](https://github.com/skylines-project/skylines) - Live tracking, flight database and competition framework
- [airflow ★8345](https://github.com/apache/incubator-airflow) - Airflow is a system to programmatically author, schedule and monitor data pipelines.
- [timesketch ★860](https://github.com/google/timesketch) - Collaborative forensics timeline analysis
- [changes ★768 ⏳1Y](https://github.com/dropbox/changes) - A dashboard for your code. A build system.
- [security_monkey ★2738](https://github.com/Netflix/security_monkey) - monitors policy changes and alerts on insecure configurations in an AWS account.
- [securedrop ★2423](https://github.com/freedomofpress/securedrop)- an open-source whistleblower submission system that media organizations can use to securely accept documents from and communicate with anonymous sources.
- [sync_engine ★3446](https://github.com/nylas/sync-engine) - IMAP/SMTP sync system with modern APIs
- [cleansweep ★32](https://github.com/AamAadmiParty/cleansweep) - Volunteer & Campaign Management System
- [indico ★329](https://github.com/indico/indico) - a general-purpose event management web-based solution. It includes a full-blown conference organization workflow as well as tools for meeting management and room booking. It provides as well integration with video-conferencing solutions.
- [flaskbb ★1284](https://github.com/flaskbb/flaskbb) - A classic Forum Software in Python using Flask.

## Boilerplate

- [fbone ★1500](https://github.com/imwilsonxu/fbone)
- [cookiecutter-flask ★1893](https://github.com/sloria/cookiecutter-flask)
- [Flask-Foundation ★1140](https://github.com/JackStouffer/Flask-Foundation)
- [flask-rest-template ★57 ⏳1Y](https://github.com/alexandre/flask-rest-template)
- [gae-init](https://gae-init.appspot.com) - Flask boilerplate running on Google App Engine
- [Flask-AppBuilder ★1572](https://github.com/dpgaspar/Flask-AppBuilder) - Simple and rapid application builder framework, built on top of Flask. includes detailed security, auto form generation, google charts and much more
---
<p align="center">
	This list is a copy of <a href="https://github.com/humiaozuzu/awesome-flask">humiaozuzu/awesome-flask</a> with ranks
</p>
