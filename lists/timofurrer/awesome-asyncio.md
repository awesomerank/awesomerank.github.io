---
layout: default
title: Awesome Rank for timofurrer/awesome-asyncio
---

<p align="center">
	This list is a copy of <a href="https://github.com/timofurrer/awesome-asyncio">timofurrer/awesome-asyncio</a> with ranks
</p>
---
# Awesome asyncio [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg) ★87749](https://github.com/sindresorhus/awesome)

> A carefully curated list of awesome Python asyncio frameworks, libraries, software and resources.

The Python [asyncio](https://docs.python.org/3/library/asyncio.html) module introduced to the standard library with Python 3.4 provides infrastructure for writing single-threaded concurrent code using coroutines, multiplexing I/O access over sockets and other resources, running network clients and servers, and other related primitives.

Asyncio is not really a brand-new technology however it appears to be very trending since a few years - especially in the Python community and with the release of Python 3.4 in March 2016.
Thus, it's pretty hard to keep yourself up-to-date with the most awesome packages out there.
Find some of those *awesome* packages here and if you are missing one we count on you to [create an Issue or a Pull Request](https://github.com/timofurrer/awesome-asyncio/blob/master/CONTRIBUTING.md) with your suggestion.

## Contents

* [Web Frameworks](#web-frameworks)
* [Message Queues](#message-queues)
* [Database Drivers](#database-drivers)
* [Networking](#networking)
* [Testing](#testing)
* [Alternative Loops](#alternative-loops)
* [Misc](#misc)
* [Writings](#writings)
* [Talks](#talks)

***

## Web Frameworks

*Libraries to build web applications.*

* [aiohttp](https://github.com/KeepSafe/aiohttp) - Http client/server for asyncio (PEP-3156).
* [sanic ★9585](https://github.com/channelcat/sanic) - Python 3.5+ web server that's written to go fast.
* [Quart](https://gitlab.com/pgjones/quart) - An asyncio web microframework with the same API as Flask.
* [Kyoukai](https://github.com/SunDwarf/Kyoukai) - Fully async web framework for Python3.5+ using asyncio.
* [cirrina ★19](https://github.com/neolynx/cirrina) - Opinionated asynchronous web framework based on aiohttp.
* [autobahn ★1813](https://github.com/crossbario/autobahn-python) - WebSocket and WAMP supporting asyncio and Twisted, for clients and servers.
* [websockets ★1515](https://github.com/aaugustin/websockets) - A library for building WebSocket servers and clients in Python with a focus on correctness and simplicity.
* [Tornado](http://www.tornadoweb.org/en/stable/) - Performant web framework and asynchronous networking library.

## Message Queues

*Libraries to implement applications using message queues.*

* [aioamqp ★146](https://github.com/Polyconseil/aioamqp) - AMQP implementation using asyncio.
* [aiozmq ★259](https://github.com/aio-libs/aiozmq) - Asyncio (pep 3156) integration with ZeroMQ.
* [crossbar ★1521](https://github.com/crossbario/crossbar) - Crossbar.io is a networking platform for distributed and microservice applications.

## Database Drivers

*Libraries to connect to databases.*

* [asyncpg ★2684](https://github.com/MagicStack/asyncpg) - Fast PostgreSQL Database Client Library for Python/asyncio.
* [asyncpgsa ★214](https://github.com/CanopyTax/asyncpgsa) - Asyncpg with sqlalchemy core support.
* [aiopg ★634](https://github.com/aio-libs/aiopg) - Library for accessing a PostgreSQL database.
* [aiomysql ★537](https://github.com/aio-libs/aiomysql) - Library for accessing a MySQL database
* [aioodbc ★100](https://github.com/aio-libs/aioodbc) - Library for accessing a ODBC databases.
* [motor ★999](https://github.com/mongodb/motor) - The async Python driver for MongoDB.
* [aioredis ★618](https://github.com/aio-libs/aioredis) - [aio-libs](https://github.com/aio-libs) Redis client (PEP 3156).
* [asyncio-redis ★422](https://github.com/jonathanslenders/asyncio-redis) - Redis client for Python asyncio (PEP 3156).
* [aiocouchdb ★42](https://github.com/aio-libs/aiocouchdb) - CouchDB client built on top of aiohttp (asyncio).
* [aioinflux ★37](https://github.com/plugaai/aioinflux) - InfluxDB client built on top of aiohttp.
* [aioes](https://github.com/aio-libs/aioes) - Asyncio compatible driver for elasticsearch.
* [peewee-async](https://github.com/05bit/peewee-async) - ORM implementation based on [peewee ★5350](https://github.com/coleifer/peewee) and aiopg.
* [GINO](https://github.com/fantix/gino) - is a lightweight asynchronous Python ORM based on [SQLAlchemy](https://www.sqlalchemy.org/) core, with [asyncpg ★2684](https://github.com/MagicStack/asyncpg) dialect.

## Networking

*Libraries to communicate in your network.*

* [AsyncSSH ★686](https://github.com/ronf/asyncssh) - Provides an asynchronous client and server implementation of the SSHv2 protocol.

## Testing

*Libraries to test asyncio based applications.*

* [aiomock ★14 ⏳1Y](https://github.com/nhumrich/aiomock) - A python mock library that supports async methods.
* [asynctest ★132](https://github.com/Martiusweb/asynctest) - Enhance the standard unittest package with features for testing. asyncio libraries
* [pytest-asyncio ★255](https://github.com/pytest-dev/pytest-asyncio) - Pytest support for asyncio.

## Alternative Loops

*Alternative asyncio loop implementations.*

* [uvloop ★4826](https://github.com/MagicStack/uvloop) - Ultra fast implementation of asyncio event loop on top of libuv.
* [curio ★2520](https://github.com/dabeaz/curio) - The coroutine concurrency library.

## Misc

*Other awesome asyncio libraries.*

* [aiofiles ★503](https://github.com/Tinche/aiofiles) - File support for asyncio.
* [aiodebug ★14 ⏳1Y](https://github.com/qntln/aiodebug) - A tiny library for monitoring and testing asyncio programs.
* [aiorun ★27](https://github.com/cjrh/aiorun) - A `run()` function that handles all the usual boilerplate for startup and graceful shutdown.
* [aiozipkin ★77](https://github.com/aio-libs/aiozipkin) - Distributed tracing instrumentation for asyncio with zipkin

## Writings

*Documentation, blog posts, and other awesome writing about asyncio.*

* [Official asyncio documentation](https://docs.python.org/3/library/asyncio.html) - Asynchronous I/O, event loop, coroutines and tasks.
* [Short well-written intro to asyncio](http://masnun.com/2015/11/13/python-generators-coroutines-native-coroutines-and-async-await.html) - Generators, Coroutines, Native Coroutines and async/await.
* [Async Through the looking Glass](https://hackernoon.com/async-through-the-looking-glass-d69a0a88b661) - Nice writing about it's worth using asyncio or not for specific use-cases.
* [Asynchronous Python](https://hackernoon.com/asynchronous-python-45df84b82434) - Introduction into asynchronous programming with Python.
* [AsyncIO for the Working Python Developer](https://hackernoon.com/asyncio-for-the-working-python-developer-5c468e6e2e8e) - A gentle introduction to asynchronous programming from basic examples working up to URL fetching.
* [Test limits of Python aiohttp](https://pawelmhm.github.io/asyncio/python/aiohttp/2016/04/22/asyncio-aiohttp.html) - Making 1 million requests with python-aiohttp.

## Talks

*People has given awesome talks about asyncio.*

* [Topics of Interest (Python Asyncio)](https://www.youtube.com/watch?v=ZzfHjytDceU) - Keynote by David Beazley.
* [Python Asynchronous I/O Walkthrough](https://www.youtube.com/playlist?list=PLpEcQSRWP2IjVRlTUptdD05kG-UkJynQT) - 8-part code walkthrough by Philip Guo
---
<p align="center">
	This list is a copy of <a href="https://github.com/timofurrer/awesome-asyncio">timofurrer/awesome-asyncio</a> with ranks
</p>
