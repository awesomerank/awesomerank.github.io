<h1 align="center">
Ranked awesome lists, all in one place
</h1>
<p align="center">
	This list is a copy of <a href="sindresorhus/awesome-nodejs">sindresorhus/awesome-nodejs</a> with ranks
</p>
---
# Awesome Node.js [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg) ★59088](sindresorhus/awesome)

[<img src="https://cdn.rawgit.com/gilbarbara/logos/e7b1dc2666c3dabe6c1276abd0a767b6ebd6af43/logos/nodejs-icon.svg" align="right" width="70">](https://nodejs.org)

> A curated list of delightful Node.js [packages](#packages) and [resources](#resources).

Just type [`node.cool`](https://node.cool) to go here ✨

*You might also like [awesome-npm ★2423](sindresorhus/awesome-npm).*
*Please read the [contribution guidelines](https://github.com/sindresorhus/awesome-nodejs/blob/master/contributing.md) before contributing.*


---

<p align="center"><sup>🦄 Support <a href="https://github.com/sindresorhus">my open-source work</a> by buying this awesome video course:</sup><br><b><a href="https://learnnode.com/friend/AWESOME">Learn to build apps and APIs with Node.js</a> by Wes Bos</b><br><sub>Try his free <a href="https://javascript30.com/friend/AWESOME">JavaScript 30</a> course for a taste of what to expect & check out his <a href="https://ES6.io/friend/AWESOME">ES6</a>, <a href="https://ReactForBeginners.com/friend/AWESOME">React</a>, <a href="https://SublimeTextBook.com/friend/AWESOME">Sublime</a> courses.</sub></p>

---


<sub>Check out my [blog](https://blog.sindresorhus.com) and say "hi" on [Twitter](https://twitter.com/sindresorhus).</sub>


## Contents

- [Packages](#packages)
	- [Mad science](#mad-science)
	- [Command-line apps](#command-line-apps)
	- [Functional programming](#functional-programming)
	- [HTTP](#http)
	- [Debugging / Profiling](#debugging--profiling)
	- [Logging](#logging)
	- [Command-line utilities](#command-line-utilities)
	- [Build tools](#build-tools)
	- [Hardware](#hardware)
	- [Templating](#templating)
	- [Web frameworks](#web-frameworks)
	- [Documentation](#documentation)
	- [Filesystem](#filesystem)
	- [Control flow](#control-flow)
	- [Streams](#streams)
	- [Real-time](#real-time)
	- [Image](#image)
	- [Text](#text)
	- [Number](#number)
	- [Math](#math)
	- [Date](#date)
	- [URL](#url)
	- [Data validation](#data-validation)
	- [Parsing](#parsing)
	- [Humanize](#humanize)
	- [Compression](#compression)
	- [Network](#network)
	- [Database](#database)
	- [Testing](#testing)
	- [Security](#security)
	- [Benchmarking](#benchmarking)
	- [Minifiers](#minifiers)
	- [Authentication](#authentication)
	- [Email](#email)
	- [Job queues](#job-queues)
	- [Node.js management](#nodejs-management)
	- [Polyfills](#polyfills)
	- [Natural language processing](#natural-language-processing)
	- [Process management](#process-management)
	- [Automation](#automation)
	- [AST](#ast)
	- [Static site generators](#static-site-generators)
	- [Content management systems](#content-management-systems)
	- [Forum](#forum)
	- [Blogging](#blogging)
	- [Weird](#weird)
	- [Miscellaneous](#miscellaneous)
- [Resources](#resources)
	- [Tutorials](#tutorials)
	- [Discovery](#discovery)
	- [Articles](#articles)
	- [Newsletters](#newsletters)
	- [Videos](#videos)
	- [Podcasts](#podcasts)
	- [Books](#books)
	- [Blogs](#blogs)
	- [Courses](#courses)
	- [Cheatsheets](#cheatsheets)
	- [Tools](#tools)
	- [Community](#community)
	- [Miscellaneous](#miscellaneous)


## Packages

### Mad science

- [webtorrent](https://github.com/feross/webtorrent) - Streaming torrent client for Node.js and the browser.
- [peerflix ★4253](mafintosh/peerflix) - Streaming torrent client.
- [dat](http://dat-data.com) - Real-time replication and versioning for data sets.
- [ipfs ★928](ipfs/js-ipfs) - Distributed file system that seeks to connect all computing devices with the same system of files.
- [GitTorrent ★3643 ⏳1Y](cjb/GitTorrent) - Peer-to-peer network of Git repositories being shared over BitTorrent.
- [stackgl](http://stack.gl) - Open software ecosystem for WebGL, built on top of browserify and npm.
- [peerwiki ★255 ⏳2Y](mafintosh/peerwiki) - All of Wikipedia on BitTorrent.
- [peercast ★327 ⏳2Y](mafintosh/peercast) - Stream a torrent video to Chromecast.
- [BitcoinJS](http://bitcoinjs.org) - Clean, readable, proven Bitcoin library.
- [Bitcore](https://bitcore.io) - Pure and powerful Bitcoin library.
- [PDFKit](http://pdfkit.org) - PDF generation library.
- [turf ★2691](Turfjs/turf) - Modular geospatial processing and analysis engine.
- [webcat ★339](mafintosh/webcat) - p2p pipe across the web using WebRTC that uses your GitHub private/public key for authentication.
- [NodeOS](http://node-os.com) - The first operating system powered by npm.
- [limdu ★566](erelsgl/limdu) - Machine-learning framework.
- [Cytoscape.js](http://js.cytoscape.org) - Graph theory (a.k.a. network) modeling and analysis.
- [kad ★191](kadtools/kad) - Kademlia distributed hash table.
- [seedshot ★87](twobucks/seedshot) - Temporary P2P screenshot sharing from your browser.
- [js-git ★3082](creationix/js-git) - JavaScript implementation of Git.
- [skale ★128](skale-me/skale-engine) - High performance distributed data processing engine.


### Command-line apps

- [np ★2191](sindresorhus/np) - Better `npm publish`.
- [trash ★1323](sindresorhus/trash) - Safer alternative to `rm`.
- [npm-name ★47 ⏳1Y](sindresorhus/npm-name) - Check whether a package name is available on npm.
- [speed-test ★1873](sindresorhus/speed-test) - Test your internet connection speed and ping.
- [emoj ★1255](sindresorhus/emoj) - Find relevant emoji from text on the command-line.
- [pageres ★8009](sindresorhus/pageres) - Capture website screenshots.
- [cpy ★124](sindresorhus/cpy) - Copy files.
- [vtop ★1978](MrRio/vtop) - More better top, with nice charts.
- [empty-trash ★78](sindresorhus/empty-trash) - Empty the trash.
- [is-up ★259 ⏳1Y](sindresorhus/is-up) - Check whether a website is up or down.
- [is-online ★279](sindresorhus/is-online) - Check if the internet connection is up.
- [public-ip ★226](sindresorhus/public-ip) - Get your public IP address.
- [clipboard-cli ★109](sindresorhus/clipboard-cli) - Copy & paste on the terminal.
- [ttystudio ★2711 ⏳1Y](chjj/ttystudio) - Record your terminal and compile it to a GIF or APNG without any external dependencies, bash scripts, gif concatenation, etc.
- [XO ★2621](sindresorhus/xo) - Enforce strict code style using the JavaScript happiness style.
- [Standard ★11789](feross/standard) - JavaScript Standard Style — One style to rule them all.
- [ESLint](http://eslint.org) - The pluggable linting utility for JavaScript.
- [dev-time ★136](samverschueren/dev-time-cli) - Get the current local time of a GitHub user.
- [David ★741](alanshaw/david) - Tells you when your package npm dependencies are out of date.
- [http-server ★5021](indexzero/http-server) - Simple, zero-config command-line HTTP server.
- [Live Server ★1353](tapio/live-server) - Development HTTP-server with livereload capability.
- [bcat ★249 ⏳2Y](kessler/node-bcat) - Pipe command output to web browsers.
- [normit ★166](pawurb/normit) - Google Translate with speech synthesis in your terminal.
- [slap ★3551](slap-editor/slap) - Sublime-like terminal-based text editor.
- [jsinspect ★1449](danielstjules/jsinspect) - Detect copy-pasted and structurally similar code.
- [esformatter ★881](millermedeiros/esformatter) - JavaScript code beautifier/formatter.
- [fkill ★1464](sindresorhus/fkill-cli) - Fabulously kill processes. Cross-platform.
- [pjs ★311](danielstjules/pjs) - Pipeable JavaScript. Quickly filter, map, and reduce from the terminal.
- [license-checker ★382](davglass/license-checker) - Check licenses of your app's dependencies.
- [browser-run ★264](juliangruber/browser-run) - Easily run code in a browser environment.
- [tmpin ★102 ⏳2Y](sindresorhus/tmpin) - Adds stdin support to any CLI app that accepts file input.
- [modhelp ★18 ⏳1Y](runvnc/modhelp) - Syntax-highlighted module READMEs in terminal with ANSI-friendly pager.
- [wifi-password ★59](kevva/wifi-password-cli) - Get the current wifi password.
- [wallpaper ★390](sindresorhus/wallpaper) - Change the desktop wallpaper.
- [brightness ★88 ⏳1Y](kevva/brightness-cli) - Change the screen brightness.
- [torrent ★464 ⏳1Y](maxogden/torrent) - Download torrents.
- [tfa ★23](jasnell/tfa) - Two-factor authentication client.
- [rtail ★1312 ⏳1Y](kilianc/rtail) - Terminal output to the browser in seconds, using UNIX pipes.
- [kill-tabs ★199](sindresorhus/kill-tabs) - Kill all Chrome tabs to improve performance, decrease battery usage, and save memory.
- [alex ★1787](wooorm/alex) - Catch insensitive, inconsiderate writing.
- [vantage ★3295](dthree/vantage) - Distributed, realtime CLI for your live app.
- [pen ★131](noraesae/pen) - Live Markdown preview in the browser from your favorite editor.
- [subdownloader ★67](beatfreaker/subdownloader) - Subtitle downloader for movies and TV series.
- [dark-mode ★176](sindresorhus/dark-mode) - Toggle the macOS Dark Mode.
- [iponmap ★111](nogizhopaboroda/iponmap) - IP location finder.
- [Jsome ★66](Javascipt/Jsome) - Pretty prints JSON with configurable colors and indentation.
- [itunes-remote ★252 ⏳1Y](mischah/itunes-remote) - Interactively control iTunes.
- [text-meme ★45](beatfreaker/text-meme-cli) - Generate a text meme.
- [mobicon ★31 ⏳1Y](samverschueren/mobicon-cli) - Mobile app icon generator.
- [mobisplash ★16](samverschueren/mobisplash-cli) - Mobile app splash screen generator.
- [diff2html-cli ★64](rtfpessoa/diff2html-cli) - Pretty git diff to HTML generator.
- [Cash ★7227](dthree/cash) - Cross-platform Unix shell commands in pure JavaScript.
- [vaca ★76 ⏳1Y](sindresorhus/vaca) - Get a random ASCII 🐮.
- [gh-home ★78](sindresorhus/gh-home) - Open the GitHub page of the repo in the current directory.
- [npm-home ★49](sindresorhus/npm-home) - Open the npm page of a package.
- [trymodule ★967](VictorBjelkholm/trymodule) - Try out npm packages in the terminal.
- [terminal-recorder ★53](cortezcristian/terminal-recorder) - Record your terminal usage and export it to interactive HTML.
- [jscpd ★451](kucherenko/jscpd) - Copy/paste detector for source code.
- [atmo ★435](Raathigesh/Atmo) - Server-side API mocking.
- [auto-install ★599](siddharthkp/auto-install) - Auto installs dependencies as you code.
- [lessmd ★58](linuxenko/lessmd) - Markdown in the terminal.
- [cost-of-modules ★1708](siddharthkp/cost-of-modules) - Find out which dependencies are slowing you down.
- [localtunnel ★4623](localtunnel/localtunnel) - Expose your localhost to the world.


### Functional programming

- [lodash](https://lodash.com) - Utility library delivering consistency, customization, performance, & extras. A better and faster Underscore.js.
- [immutable ★18899](facebook/immutable-js) - Immutable data collections.
- [mori](http://swannodette.github.io/mori/) - Library for using ClojureScript's persistent data structures and supporting API from the comfort of vanilla JavaScript.
- [Ramda](http://ramdajs.com) - Utility library with a focus on flexible functional composition enabled by automatic currying and reversed argument order. Avoids mutating data.
- [Folktale](http://folktalejs.org) - Suite of libraries for generic functional programming in JavaScript that allows you to write elegant, modular applications with fewer bugs, and more reuse.
- [underscore-contrib](http://documentcloud.github.io/underscore-contrib/) - The brass buckles on Underscore's utility belt.
- [Mout](http://moutjs.com) - Utility library with the biggest difference between other existing solutions is that you can choose to load only the modules/functions that you need, no extra overhead.
- [Bacon.js](http://baconjs.github.io) - Functional reactive programming.
- [RxJS](http://reactivex.io) - Functional reactive library for transforming, composing, and querying various kinds of data.
- [Lazy.js ★4154](dtao/lazy.js) - Utility library similar to lodash/Underscore but with lazy evaluation, which can translate to superior performance in many cases.
- [Kefir.js ★1252](rpominov/kefir) - Reactive library with focus on high performance and low memory usage.


### HTTP

- [got ★1658](sindresorhus/got) - Nicer interface to the built-in `http` module.
- [gh-got ★76](sindresorhus/gh-got) - Convenience wrapper for `got` to interact with the GitHub API.
- [axios ★20217](mzabriskie/axios) - Promise based HTTP client (works in the browser too).
- [request ★15566](request/request) - Simplified HTTP request client.
- [Nock](https://github.com/pgte/nock) - HTTP mocking and expectations library.
- [spdy](https://github.com/indutny/node-spdy) - Creates SPDY servers with the same API as the built-in `https` module.
- [wreck ★255](hapijs/wreck) - HTTP Client Utilities.
- [download ★496](kevva/download) - Download and extract files effortlessly.
- [http-proxy ★7200](nodejitsu/node-http-proxy) - HTTP proxy.
- [rocky ★246](h2non/rocky) - Featured, middleware-oriented HTTP proxy with traffic replay and intercept.
- [superagent ★10587](visionmedia/superagent) - HTTP request library.
- [node-fetch ★1737](bitinn/node-fetch) - `window.fetch` for Node.js.
- [flashheart ★51](bbc/flashheart) - REST client.
- [http-fake-backend ★94](micromata/http-fake-backend) - Build a fake backend by providing the content of JSON files or JavaScript objects through configurable routes.


### Debugging / Profiling

- [ironNode ★2324](s-a/iron-node) - Node.js debugger supporting ES2015 out of the box.
- [node-inspector ★11394](node-inspector/node-inspector) - Debugger based on Blink Developer Tools.
- [devtool ★3696](Jam3/devtool) - Run Node.js programs through Chrome Dev Tools.
- [Theseus ★1344 ⏳2Y](adobe-research/theseus) - JavaScript debugger featuring real-time code coverage, retroactive inspection and asynchronous call tree.
- [longjohn ★580](mattinsler/longjohn) - Long stack traces with configurable call trace length.
- [debug ★4358](visionmedia/debug) - Tiny debugging utility.
- [jstrace ★377](jstrace/jstrace) - Dynamic tracing for JavaScript, similar to dtrace, ktap etc.
- [why-is-node-running ★540](mafintosh/why-is-node-running) - Node.js is running but you don't know why?
- [njsTrace ★197](valyouw/njstrace) - Instrument and trace your code, see all function calls, arguments, return values, as well as the time spent in each function.
- [vstream ★54 ⏳2Y](joyent/node-vstream) - Instrumentable streams mix-ins to inspect a pipeline of streams.
- [stackman ★125](watson/stackman) - Enhance an error stacktrace with code excerpts and other goodies.
- [locus](https://github.com/alidavut/locus) - Starts a REPL at runtime that has access to all variables.
- [bugger ★149](buggerjs/bugger) - Provides Chrome Devtools bindings to debug programs in Chrome.
- [0x ★499](davidmarkclements/0x) - Flamegraph profiling.
- [ctrace ★81](automation-stack/ctrace) - Well-formatted and improved trace system calls and signals.


### Logging

- [pino ★1064](pinojs/pino) - Extremely fast logger inspired by Bunyan.
- [winston ★7581](winstonjs/winston) - Multi-transport async logging library.
- [Bunyan ★4034](trentm/node-bunyan) - JSON logging library.
- [intel](http://seanmonstar.github.io/intel/) - Logging library (handlers, filters, formatters, console injection).
- [console-log-level ★14](watson/console-log-level) - The most simple logger imaginable with support for log levels and custom prefixes.
- [storyboard ★318](guigrpa/storyboard) - End-to-end, hierarchical, real-time, colorful logs and stories.


### Command-line utilities

- [chalk ★5355](chalk/chalk) - Terminal string styling done right.
- [meow ★823](sindresorhus/meow) - CLI app helper.
- [minimist ★2241](substack/minimist) - Parse command-line flags.
- [get-stdin ★114](sindresorhus/get-stdin) - Easier stdin.
- [ora ★1740](sindresorhus/ora) - Elegant terminal spinner.
- [log-update ★318](sindresorhus/log-update) - Log by overwriting the previous output in the terminal. Useful for rendering progress bars, animations, etc.
- [Inquirer.js ★4452](SBoudrias/Inquirer.js) - Interactive command-line prompt.
- [listr ★827](samverschueren/listr) - Terminal task list.
- [conf ★146](sindresorhus/conf) - Simple config handling for your app or module.
- [update-notifier ★660](yeoman/update-notifier) - Update notifications for your CLI app.
- [ansi-escapes ★114](sindresorhus/ansi-escapes) - ANSI escape codes for manipulating the terminal.
- [log-symbols ★207](sindresorhus/log-symbols) - Colored symbols for various log levels.
- [figures ★162](sindresorhus/figures) - Unicode symbols with Windows CMD fallbacks.
- [boxen ★219](sindresorhus/boxen) - Create boxes in the terminal.
- [string-width ★67](sindresorhus/string-width) - Get the visual width of a string - the number of columns required to display it.
- [cli-truncate ★21](sindresorhus/cli-truncate) - Truncate a string to a specific width in the terminal.
- [first-run ★32](sindresorhus/first-run) - Check if it's the first time the process is run.
- [vorpal ★3917](dthree/vorpal) - Interactive CLI apps.
- [blessed ★6127](chjj/blessed) - Curses-like library.
- [yn ★72](sindresorhus/yn) - Parse yes/no like values.
- [cli-table ★1259](Automattic/cli-table) - Pretty unicode tables.
- [drawille ★598](madbence/node-drawille) - Draw on the terminal with unicode braille characters.
- [sudo-block ★43](sindresorhus/sudo-block) - Block users from running your app with root permissions.
- [googleauth ★39 ⏳2Y](maxogden/googleauth) - Create and load persistent Google authentication tokens for command-line apps.
- [ascii-charts ★190](jstrace/chart) - ASCII bar chart in the terminal.
- [progress](https://github.com/tj/node-progress) - Flexible ascii progress bar.
- [insight ★356](yeoman/insight) - Helps you understand how your tool is being used by anonymously reporting usage metrics to Google Analytics.
- [cli-cursor ★27](sindresorhus/cli-cursor) - Toggle the CLI cursor.
- [columnify ★229](timoxley/columnify) - Create text-based columns suitable for console output. Supports cell wrapping.
- [cli-columns ★6](shannonmoeller/cli-columns) - Columnated unicode and ansi-safe text lists.
- [cfonts ★167](dominikwilkowski/cfonts) - Sexy ASCII fonts for the console.
- [multispinner ★180](codekirei/node-multispinner) - Multiple, simultaneous, individually controllable CLI spinners.
- [omelette ★609](f/omelette) - Shell autocompletion helper.
- [cross-env ★1333](kentcdodds/cross-env) - Set environment variables cross-platform.
- [shelljs ★5972](shelljs/shelljs) - Portable Unix shell commands.
- [loud-rejection ★159](sindresorhus/loud-rejection) - Make unhandled promise rejections fail loudly instead of the default silent fail.
- [sparkly ★242 ⏳1Y](sindresorhus/sparkly) - Generate sparklines ▁▂▃▅▂▇
- [term-img ★158](sindresorhus/term-img) - Display images in your terminal.
- [yargs ★2984](yargs/yargs) - Command-line parser that automatically generates an elegant user-interface.
- [DraftLog ★779](ivanseidel/node-draftlog) - Create multiple updatable log lines. Works just like `console.log`.


### Build tools

- [webpack ★28143](webpack/webpack) - Packs modules and assets for the browser.
- [rollup ★9440](rollup/rollup) - Next-generation ES2015 module bundler.
- [gulp](http://gulpjs.com) - Streaming and fast build system that favors code over config.
- [browserify ★11052](substack/node-browserify) - Browser-side require() the Node.js way.
- [Broccoli ★3030](broccolijs/broccoli) - Fast, reliable asset pipeline, supporting constant-time rebuilds and compact build definitions.
- [Brunch ★5949](brunch/brunch) - Front-end web app build tool with simple declarative config, fast incremental compilation, and an opinionated workflow.
- [strong-build ★39](strongloop/strong-build) - Build a node app package and prepare to deploy it as a package to production or use git to commit to a deploy branch.
- [start ★191](start-runner/start) - Simple tasks runner powered by composable functions and promise chaining.
- [ygor ★32](shannonmoeller/ygor) - Promising task runner for when `npm run` isn't enough and everything else is too much.
- [grunt](http://gruntjs.com) - Task runner that can perform repetitive tasks like minification, compilation, unit testing, linting, etc.
- [Fly](https://github.com/bucaran/fly) - Modern build system based in co-routines, generators and promises.
- [FuseBox ★2237](fuse-box/fuse-box) - Fast build system that combines the power of webpack, JSPM and SystemJS, with first-class TypeScript support.
- [pkg ★6273](zeit/pkg) - Package your Node.js project into an executable.


### Hardware

- [johnny-five ★7677](rwaldron/johnny-five) - Firmata based Arduino Framework.
- [serialport](https://github.com/voodootikigod/node-serialport) - Access serial ports for reading and writing.
- [usb](https://github.com/nonolith/node-usb) - USB library.
- [cylon.js](http://cylonjs.com) - Next generation robotics framework with support for 26 different platforms.
- [i2c-bus ★81](fivdi/i2c-bus) - I2C serial bus access.
- [onoff ★495](fivdi/onoff) - GPIO access and interrupt detection.
- [spi-device ★15](fivdi/spi-device) - SPI serial bus access.
- [pigpio ★157](fivdi/pigpio) - Fast GPIO, PWM, servo control, state change notification, and interrupt handling on the Raspberry Pi.


### Templating

- [marko ★2847](marko-js/marko) - HTML-based templating engine that compiles templates to CommonJS modules and supports streaming, async rendering and custom tags.
- [nunjucks ★4229](mozilla/nunjucks) - Templating engine with inheritance, asynchronous control, and more (jinja2 inspired).
- [handlebars.js ★11951](wycats/handlebars.js) - Superset of Mustache templates which adds powerful features like helpers and more advanced blocks.
- [hogan.js](http://twitter.github.io/hogan.js/) - Twitter's small, fast, phase-separated compiler for Mustache templates.
- [EJS ★1449](mde/ejs) - Simple unopinionated templating language.
- [Pug ★14429](pugjs/pug) - High-performance template engine heavily influenced by Haml.


### Web frameworks

- [Hapi](http://hapijs.com) - Framework for building applications and services.
- [Koa](http://koajs.com) - Framework designed by the team behind Express, which aims to be a smaller, more expressive, and more robust foundation for web applications and APIs.
- [Express](http://expressjs.com) - Web application framework, providing a robust set of features for building single and multi-page, and hybrid web applications.
- [Feathers](http://feathersjs.com) - Microservice framework built in the spirit of Express.
- [LoopBack](http://loopback.io) - Powerful framework for creating REST APIs and easily connecting to backend data sources.
- [Meteor](https://www.meteor.com) - An ultra-simple, database-everywhere, data-on-the-wire, pure-Javascript web framework. *(You might like [awesome-meteor ★978](Urigo/awesome-meteor))*
- [SailsJS](http://sailsjs.org) - An MVC web framework with a modern twist, supporting WebSockets, streams, and a data-driven API.
- [Restify](http://restify.com) - Enables you to build correct REST web services.
- [Interfake ★792](basicallydan/interfake) - Rapid prototyping framework for making mock HTTP APIs, with a Node.js, command-line and HTTP interface.
- [Catberry](http://catberry.org) - Framework with Flux architecture, isomorphic web-components, and progressive rendering.
- [ThinkJS](https://thinkjs.org) - Framework with ES2015+ support, WebSockets, REST API.
- [ActionHero](http://www.actionherojs.com) - Framework for making reusable & scalable APIs for TCP sockets, WebSockets, and HTTP clients.
- [MERN](http://mern.io) - Easily build production-ready universal apps with MongoDB, Express, React, and webpack.
- [Next.js](https://zeit.co/blog/next) - Minimalistic framework for server-rendered React apps.
- [Nuxt.js](https://nuxtjs.org) - Minimalistic framework for server-rendered Vue.js apps.
- [seneca ★2252](senecajs/seneca) - Toolkit for writing microservices.
- [AdonisJs](http://adonisjs.com) - A true MVC framework for Node.js built on solid foundations of Dependency Injection and IoC container.


### Documentation

- [Docco](http://jashkenas.github.io/docco/) - Documentation generator which produces an HTML document that displays your comments intermingled with your code.
- [JSDoc](http://usejsdoc.org) - API documentation generator similar to JavaDoc or PHPDoc.
- [dox ★1973](tj/dox) - JavaScript documentation generator using Markdown and JSDoc.
- [jsdox ★186](sutoiku/jsdox) - JSDoc3 to Markdown documentation generator.
- [apiDoc ★4500](apidoc/apidoc) - Inline documentation for RESTful web APIs.
- [documentation.js](http://documentation.js.org) - API documentation generator with support for ES2015+ and flow annotation.
- [YUIDoc](http://yui.github.com/yuidoc/) - Generates API documentation from comments in source.
- [ESDoc](https://esdoc.org) - Documentation generator targeting ES2015, attaching test code and measuring documentation coverage.


### Filesystem

- [del ★623](sindresorhus/del) - Delete files/folders using globs.
- [globby ★318](sindresorhus/globby) - Glob files with support for multiple patterns.
- [cpy ★124](sindresorhus/cpy) - Copy files.
- [rimraf ★1689](isaacs/rimraf) - Recursively delete files like `rm -rf`.
- [mkdirp ★1394](substack/node-mkdirp) - Recursively create directories like `mkdir -p`.
- [graceful-fs ★614](isaacs/node-graceful-fs) - Drop-in replacement for the `fs` module with various improvements.
- [chokidar ★2905](paulmillr/chokidar) - Filesystem watcher which stabilizes events from `fs.watch` and `fs.watchFile` as well as using native `fsevents` on macOS.
- [find-up ★88](sindresorhus/find-up) - Find a file by walking up parent directories.
- [proper-lockfile ★31](IndigoUnited/node-proper-lockfile) - Inter-process and inter-machine lockfile utility.
- [load-json-file ★61](sindresorhus/load-json-file) - Read and parse a JSON file.
- [write-json-file ★55](sindresorhus/write-json-file) - Stringify and write JSON to a file atomically.
- [fs-write-stream-atomic ★35](npm/fs-write-stream-atomic) - Like `fs.createWriteStream()`, but atomic.
- [filenamify ★68](sindresorhus/filenamify) - Convert a string to a valid filename.
- [lnfs ★8 ⏳1Y](kevva/lnfs) - Force create symlinks like `ln -fs`.
- [istextorbinary ★31](bevry/istextorbinary) - Check if a file is text or binary.
- [fs-jetpack ★284](szwacz/fs-jetpack) - Completely redesigned file system API for convenience in everyday use.
- [fs-extra ★2434](jprichardson/node-fs-extra) - Extra methods for the `fs` module.
- [pkg-dir ★43](sindresorhus/pkg-dir) - Find the root directory of an npm package.
- [sander ★55](rich-harris/sander) - Promise-based replacement for the `fs` module.
- [filehound ★56](nspragg/filehound) - Flexible and fluent interface for searching the file system.


### Control flow

- Promises
	- [Bluebird ★14650](petkaantonov/bluebird) - Promise library with focus on innovative features and performance.
	- [pify ★457](sindresorhus/pify) - Promisify a callback-style function.
	- [delay ★126](sindresorhus/delay) - Delay a promise a specified amount of time.
	- [promise-memoize ★8](nodeca/promise-memoize) - Memoize promise-returning functions, with expire and prefetch.
	- [valvelet ★8](lpinca/valvelet) - Limit the execution rate of a promise-returning function.
	- [p-map ★105](sindresorhus/p-map) - Map over promises concurrently.
	- [More…](https://github.com/wbinnssmith/awesome-promises)
- Observables
	- [zen-observable ★221](zenparsing/zen-observable) - Implementation of Observables.
	- [RxJS ★6486](ReactiveX/RxJS) - Reactive programming.
	- [observable-to-promise ★193](sindresorhus/awesome-observables) - Convert an Observable to a Promise.
	- [More…](https://github.com/sindresorhus/awesome-observables)
- Generators
	- [co ★8204](tj/co) - The ultimate generator based flow-control goodness.
	- [bluebird-co ★78](novacrazy/bluebird-co) - High performance yield handlers for Bluebird coroutines.
	- [iterum ★13](xgbuils/iterum) - Build generator pipelines using Array-like methods.
- Streams
	- [Highland.js](http://highlandjs.org) - Manages synchronous and asynchronous code easily, using nothing more than standard JavaScript and Node-like Streams.
- Callbacks
	- [each-async ★93](sindresorhus/each-async) - Async concurrent iterator like forEach.
	- [async ★21343](caolan/async) - Provides straight-forward, powerful functions for working with asynchronicity.
- Channels
	- [js-csp ★281 ⏳1Y](jlongster/js-csp) - Communicating sequential processes for JavaScript (like Clojurescript core.async, or Go).
- Other
	- [zone ★282](strongloop/zone) - Provides a way to group and track resources and errors across asynchronous operations.


### Streams

- [through2 ★1105](rvagg/through2) - Tiny wrapper around streams2 Transform to avoid explicit subclassing noise.
- [from2 ★77](hughsk/from2) - Convenience wrapper for ReadableStream, inspired by `through2`.
- [get-stream ★70](sindresorhus/get-stream) - Get a stream as a string or buffer.
- [into-stream ★40](sindresorhus/into-stream) - Convert a buffer/string/array/object into a stream.
- [duplexify ★108](mafintosh/duplexify) - Turn a writeable and readable stream into a single streams2 duplex stream.
- [pumpify ★101](mafintosh/pumpify) - Combine an array of streams into a single duplex stream.
- [peek-stream ★28](mafintosh/peek-stream) - Transform stream that lets you peek the first line before deciding how to parse it.
- [binary-split ★45](maxogden/binary-split) - Newline (or any delimiter) splitter stream.
- [byline ★219](jahewson/node-byline) - Super-simple line-by-line Stream reader.
- [first-chunk-stream ★13 ⏳1Y](sindresorhus/first-chunk-stream) - Transform the first chunk in a stream.
- [pad-stream ★5](sindresorhus/pad-stream) - Pad each line in a stream.
- [multistream ★115](feross/multistream) - Combine multiple streams into a single stream.
- [stream-combiner2 ★62](substack/stream-combiner2) - Turn a pipeline into a single stream.
- [readable-stream ★523](nodejs/readable-stream) - Mirror of Streams2 and Streams3 implementations in core.
- [through2-concurrent ★45 ⏳1Y](almost/through2-concurrent) - Transform object streams concurrently.
- [graphicsmagick-stream ★56 ⏳1Y](e-conomic/graphicsmagick-stream) - Fast conversion/scaling of images using a pool of long lived GraphicsMagick processes.


### Real-time

- [µWebSockets](https://github.com/uWebSockets/uWebSockets) - Highly scalable WebSocket server & client library.
- [Socket.io](http://socket.io) - Enables real-time bidirectional event-based communication.
- [SockJS ★1425](sockjs/sockjs-node) - Low latency, full duplex, cross-domain channel browser-server, with WebSockets or without.
- [Faye](http://faye.jcoglan.com) - Real-time client-server message bus, based on Bayeux protocol.
- [SocketCluster ★3895](SocketCluster/socketcluster) - Scalable HTTP + WebSocket engine which can run on multiple CPU cores.
- [Primus ★3186](primus/primus) - An abstraction layer for real-time frameworks to prevent module lock-in.
- [Straw ★241](simonswain/straw) - Real-time dataflow framework.
- [deepstream.io](https://deepstream.io) - Scalable real-time microservice framework.
- [Kalm ★13](kalm/kalm.js) - Low-level socket router and middleware framework.
- [MQTT.js ★2257](mqttjs/MQTT.js) - Client for MQTT - Pub-sub based messaging protocol for use on top of TCP/IP.


### Image

- [sharp ★5313](lovell/sharp) - The fastest module for resizing JPEG, PNG, WebP and TIFF images.
- [image-type ★110](sindresorhus/image-type) - Detect the image type of a Buffer/Uint8Array.
- [gm ★4125](aheckmann/gm) - GraphicsMagick and ImageMagick wrapper.
- [lwip ★1842](EyalAr/lwip) - Lightweight image processor which does not require ImageMagick.
- [pica ★715](nodeca/pica) - High quality & fast resize (lanczos3) in pure JS. Alternative to canvas drawImage(), when no pixelation allowed.
- [jimp ★3965](oliver-moran/jimp) - Image processing in pure JavaScript.
- [is-progressive ★162 ⏳1Y](sindresorhus/is-progressive) - Check if a JPEG image is progressive.
- [probe-image-size ★90](nodeca/probe-image-size) - Get the size of most image formats without a full download.


### Text

- [Underscore.string ★3174](epeli/underscore.string) - Collection of string manipulation utilities.
- [iconv-lite ★1280](ashtuchkin/iconv-lite) - Convert character encodings.
- [string-length ★30](sindresorhus/string-length) - Get the real length of a string - by correctly counting astral symbols and ignoring ansi escape codes.
- [camelcase ★127](sindresorhus/camelcase) - Convert a dash/dot/underscore/space separated string to camelCase: foo-bar → fooBar.
- [escape-string-regexp ★138 ⏳1Y](sindresorhus/escape-string-regexp) - Escape RegExp special characters.
- [execall ★57](sindresorhus/execall) - Find multiple RegExp matches in a string.
- [splice-string ★11](sindresorhus/splice-string) - Remove or replace part of a string like `Array#splice`.
- [indent-string ★34](sindresorhus/indent-string) - Indent each line in a string.
- [strip-indent ★45](sindresorhus/strip-indent) - Strip leading whitespace from every line in a string.
- [detect-indent ★86](sindresorhus/detect-indent) - Detect the indentation of code.
- [he ★1022](mathiasbynens/he) - HTML entity encoder/decoder.
- [i18n-node ★1664](mashpie/i18n-node) - Simple translation module with dynamic JSON storage.
- [babelfish ★160 ⏳1Y](nodeca/babelfish) - i18n with very easy syntax for plurals.
- [hanging-indent ★2 ⏳1Y](codekirei/hanging-indent) - Format a string into a hanging-indented paragraph.
- [matcher ★274](sindresorhus/matcher) - Simple wildcard matching.
- [unhomoglyph ★7](nodeca/unhomoglyph) - Normalize visually similar unicode characters.


### Number

- [random-int ★19](sindresorhus/random-int) - Generate a random integer.
- [random-float ★12](sindresorhus/random-float) - Generate a random float.
- [unique-random ★38](sindresorhus/unique-random) - Generate random numbers that are consecutively unique.
- [round-to ★66](sindresorhus/round-to) - Round a number to a specific number of decimal places: `1.234` → `1.2`.


### Math

- [ndarray ★604](scijs/ndarray) - Multidimensional arrays.
- [mathjs ★4525](josdejong/mathjs) - An extensive math library.
- [math-sum ★4](sindresorhus/math-sum) - Sum numbers.
- [math-clamp ★4 ⏳1Y](sindresorhus/math-clamp) - Clamp a number.
- [algebra ★41](fibo/algebra) - Algebraic structures.


### Date

- [date-fns ★4893](date-fns/date-fns) - Modern date utility.
- [Moment.js](http://momentjs.com) - Parse, validate, manipulate, and display dates.
- [Moment Timezone](http://momentjs.com/timezone/) - IANA Time Zone Database + Moment.js.
- [dateformat ★646](felixge/node-dateformat) - Date formatting.
- [tz-format ★4](samverschueren/tz-format) - Format a date with timezone: `2015-11-30T10:40:35+01:00`.
- [cctz ★41](floatdrop/node-cctz) - Fast parsing, formatting, and timezone conversation for dates.


### URL

- [normalize-url ★148](sindresorhus/normalize-url) - Normalize a URL.
- [humanize-url ★43 ⏳1Y](sindresorhus/humanize-url) - Humanize a URL: http://sindresorhus.com → sindresorhus.com.
- [url-unshort ★20](nodeca/url-unshort) - Expand shortened URLs.
- [speakingurl ★762](pid/speakingurl) - Generate a slug from a string with transliteration.
- [linkify-it ★154](markdown-it/linkify-it) - Link patterns detector with full unicode support.
- [url-pattern ★226](snd/url-pattern) - Easier than regex string matching patterns for URLs and other strings.
- [embedza ★26](nodeca/embedza) - Create HTML snippets/embeds from URLs using info from oEmbed, Open Graph, meta tags.


### Data validation

- [joi ★4967](hapijs/joi) - Object schema description language and validator for JavaScript objects.
- [is-my-json-valid ★683](mafintosh/is-my-json-valid) - JSON Schema validator that uses code generation to be extremely fast.
- [property-validator ★121](nettofarah/property-validator) - Easy property validation for Express.
- [schema-inspector ★403](Atinux/schema-inspector) - JSON API sanitization and validation.
- [ajv ★1718](epoberezkin/ajv) - The fastest JSON Schema validator. Supports v5 proposals.


### Parsing

- [remark ★904](wooorm/remark) - Markdown processor powered by plugins.
- [markdown-it ★3552](markdown-it/markdown-it) - Markdown parser with 100% CommonMark support, extensions and syntax plugins.
- [parse5 ★1394](inikulin/parse5) - Fast full-featured spec compliant HTML parser.
- [strip-json-comments ★280](sindresorhus/strip-json-comments) - Strip comments from JSON.
- [strip-css-comments ★72](sindresorhus/strip-css-comments) - Strip comments from CSS.
- [parse-json ★80](sindresorhus/parse-json) - Parse JSON with more helpful errors.
- [URI.js ★4730](medialize/URI.js) - URL mutation.
- [PostCSS ★14858](postcss/postcss) - CSS parser / stringifier.
- [JSONStream ★1227](dominictarr/JSONStream) - Streaming JSON.parse and stringify.
- [neat-csv ★46 ⏳1Y](sindresorhus/neat-csv) - Fast CSV parser. Callback interface for the above.
- [csv-parser ★280](mafintosh/csv-parser) - Streaming CSV parser that aims to be faster than everyone else.
- [PEG.js ★2311](pegjs/pegjs) - Simple parser generator that produces fast parsers with excellent error reporting.
- [x-ray](https://github.com/lapwinglabs/x-ray) - Web scraping utility.
- [nearley ★1449](Hardmath123/nearley) - Simple, fast, powerful parsing for JavaScript.
- [binary-extract ★131](juliangruber/binary-extract) - Extract a value from a buffer of JSON without parsing the whole thing.
- [json-mask ★455](nemtsov/json-mask) - Tiny language and engine for selecting parts of an object, hiding/masking the rest.
- [Stylecow ★115](stylecow/stylecow) - Parse, manipulate and convert modern CSS to make it compatible with all browsers. Extensible with plugins.
- [js-yaml ★2178](nodeca/js-yaml) - Very fast YAML parser.
- [excel-stream ★102](dominictarr/excel-stream) - Streaming Excel spreadsheet to JSON parser.
- [xml2js ★2514](Leonidas-from-XIV/node-xml2js) - XML to JavaScript object converter.
- [Jison](http://zaach.github.io/jison/) - Friendly JavaScript parser generator. It shares genes with Bison, Yacc and family.
- [google-libphonenumber ★276](seegno/google-libphonenumber) - Parse, format, store and validate phone numbers.
- [ref ★222](TooTallNate/ref) - Read/write structured binary data in Buffers.
- [xlsx-populate ★36](dtjohnson/xlsx-populate) - Read/write Excel XLSX.


### Humanize

- [pretty-bytes ★281](sindresorhus/pretty-bytes) - Convert bytes to a human readable string: `1337` → `1.34 kB`.
- [pretty-ms ★224 ⏳1Y](sindresorhus/pretty-ms) - Convert milliseconds to a human readable string: `1337000000` → `15d 11h 23m 20s`.
- [ms](https://github.com/rauchg/ms.js) - Tiny millisecond conversion utility.
- [pretty-error ★728](AriaMinaei/pretty-error) - Errors with less clutter.
- [humanize ★338 ⏳1Y](taijinlee/humanize) - Data formatter for human readability.
- [read-art ★212](Tjatse/node-readability) - Extract readable content from any page.


### Compression

- [yazl ★76](thejoshwolfe/yazl) - Zip.
- [yauzl ★198](thejoshwolfe/yauzl) - Unzip.
- [Archiver ★808](archiverjs/node-archiver) - Streaming interface for archive generation, supporting ZIP and TAR.
- [pako ★1102](nodeca/pako) - High speed zlib port to pure js (deflate, inflate, gzip).
- [tar-stream](https://github.com/mafintosh/tar-stream) - Streaming tar parser and generator. Also see [tar-fs ★168](mafintosh/tar-fs).
- [decompress ★124](kevva/decompress) - Decompression module with support for `tar`, `tar.gz` and `zip` files out of the box.


### Network

- [get-port ★136](sindresorhus/get-port) - Get an available port.
- [ipify ★118](sindresorhus/ipify) - Get your public IP address.
- [getmac ★103](bevry/getmac) - Get the computer MAC address.
- [polo ★185 ⏳2Y](mafintosh/polo) - Zero-config service discovery.


### Database

- Drivers
	- [PostgreSQL ★4745](brianc/node-postgres) - PostgreSQL client. Pure JavaScript and native libpq bindings.
	- [Redis ★2927](luin/ioredis) - Redis client.
	- [LevelUP ★2662](Level/levelup) - LevelDB.
	- [MySQL ★9371](mysqljs/mysql) - MySQL client.
	- [nano ★1100](dscape/nano) - CouchDB client.
	- [Aerospike ★130](aerospike/aerospike-client-nodejs) - Aerospike client.
	- [Couchbase ★343](couchbase/couchnode) - Couchbase client.
	- [MongoDB ★5719](mongodb/node-mongodb-native) - MongoDB driver.
- ODM / ORM
	- [Sequelize ★9868](sequelize/sequelize) - Multi-dialect ORM. Supports PostgreSQL, SQLite, MySQL.
	- [Bookshelf](http://bookshelfjs.org) - ORM for PostgreSQL, MySQL and SQLite3 in the style of Backbone.js.
	- [Massive](https://github.com/robconery/massive-js) - PostgreSQL data access tool.
	- [Mongoose](http://mongoosejs.com) - Elegant MongoDB object modeling.
	- [Waterline ★3959](balderdashy/waterline) - Datastore-agnostic tool that dramatically simplifies interaction with one or more databases.
	- [Iridium ★373](SierraSoftworks/Iridium) - MongoDB ORM with support for promises, distributed caching, preprocessing, validation and plugins.
	- [OpenRecord ★109](PhilWaldmann/openrecord) - ORM for PostgreSQL, MySQL, SQLite3 and RESTful datastores. Similar to ActiveRecord.
	- [orm2 ★2468](dresende/node-orm2) - ORM for PostgreSQL, MariaDB, MySQL, Amazon Redshift, SQLite, MongoDB.
	- [firenze ★125](fahad19/firenze) - Adapter-based ORM for MySQL, Memory, Redis, localStorage and more.
	- [pg-promise ★1277](vitaly-t/pg-promise) - PostgreSQL framework for native SQL using promises.
	- [Objection.js ★1187](Vincit/objection.js) - Lightweight ORM built on the SQL query builder Knex.
- Query builder
	- [Knex](http://knexjs.org) - Query builder for PostgreSQL, MySQL and SQLite3, designed to be flexible, portable, and fun to use.
- Other
	- [NeDB ★6545](louischatriot/nedb) - Embedded persistent database written in JavaScript.
	- [Lowdb ★4629](typicode/lowdb) - Small JavaScript database powered by Lodash.


### Testing

- [AVA](https://ava.li) - Futuristic test runner.
- [Mocha](http://mochajs.org) - Feature-rich test framework making asynchronous testing simple and fun.
- [nyc](https://github.com/bcoe/nyc) - Code coverage tool built on istanbul that works with subprocesses.
- [tap](https://github.com/isaacs/node-tap) - TAP test framework.
- [tape ★3869](substack/tape) - TAP-producing test harness.
- [power-assert ★1511](power-assert-js/power-assert) - Provides descriptive assertion messages through the standard assert interface.
- [Mochify ★275](mantoni/mochify.js) - TDD with Browserify, Mocha, PhantomJS and WebDriver.
- [trevor](https://github.com/vdemedes/trevor) - Run tests against multiple versions of Node.js without switching versions manually or pushing to Travis CI.
- [loadtest ★739](alexfernandez/loadtest) - Run load tests for your web application, with an API for automation.
- [Sinon.JS ★4189](sinonjs/sinon) - Test spies, stubs and mocks.
- [navit ★40](nodeca/navit) - PhantomJS / SlimerJS wrapper to simplify browser test scripting.
- [nock](https://github.com/pgte/nock) - HTTP mocking and expectations.
- [intern ★3745](theintern/intern) - Code testing stack.
- [toxy ★2330](h2non/toxy) - Hackable HTTP proxy to simulate failure scenarios and network conditions.
- [hook-std ★18](sindresorhus/hook-std) - Hook and modify stdout/stderr.
- [testen ★152](egoist/testen) - Run tests for multiple versions of Node.js locally with NVM.
- [Nightwatch ★6484](nightwatchjs/nightwatch) - Automated UI testing framework based on Selenium WebDriver.
- [WebdriverIO](http://webdriver.io) - Automated testing based on the WebDriver protocol.
- [Jest ★10350](facebook/jest) - Painless JavaScript testing.
- [TestCafe ★2589](DevExpress/testcafe) - Automated browser testing.


### Security

- [snyk ★479](Snyk/snyk) - CLI and build-time tool to find & fix vulnerable npm dependencies.
- [nsp ★833](nodesecurity/nsp) - CLI tool to identify known vulnerabilities in your project.
- [RegEx-DoS ★51](jagracey/RegEx-DoS) - CLI tool to identify possible regex denial of service (ReDos) vulnerabilities in your project.


### Benchmarking

- [Benchmark.js](http://benchmarkjs.com) - Benchmarking library that supports high-resolution timers and returns statistically significant results.
- [matcha ★435](logicalparadox/matcha) - Simplistic approach to benchmarking.


### Minifiers

- [babili ★2357](babel/babili) - ES2015+ aware minifier based on the Babel toolchain.
- [UglifyJS2](http://lisperator.net/uglifyjs/) - JavaScript minifier.
- [clean-css ★2440](jakubpawlowicz/clean-css) - CSS minifier.
- [minimize ★128](Swaagie/minimize) - HTML minifier.
- [imagemin ★1289](imagemin/imagemin) - Image minifier.


### Authentication

- [Passport](http://passportjs.org) - Simple, unobtrusive authentication.
- [everyauth ★3375 ⏳1Y](bnoguchi/everyauth) - Authentication and authorization (password, Facebook, etc) for your Connect and Express apps.
- [passwordless](https://passwordless.net) - Token-based authentication middleware for Express allowing authentication without passwords.
- [Lockit ★434 ⏳1Y](zemirco/lockit) - Full featured authentication solution for Express. Supports a variety of databases, predefined routes, email and two-factor authentication.
- [Grant ★1268](simov/grant) - OAuth middleware for Express, Koa, and Hapi.
- [CloudRail ★211](CloudRail/cloudrail-si-node-sdk) - Unified API for social authentication (Facebook, Twitter, Slack, Instagram, …).


### Email

- [Nodemailer](https://github.com/andris9/Nodemailer) - The fastest way to handle email.
- [emailjs ★1425](eleith/emailjs) - Send text/HTML emails with attachments to any SMTP server.


### Job queues

- [kue ★5993](Automattic/kue) - Priority job queue backed by Redis.
- [bull ★1528](OptimalBits/bull) - Persistent job and message queue.
- [agenda ★2871](rschmukler/agenda) - Lightweight job scheduling on MongoDB.
- [idoit ★8](nodeca/idoit) - Redis-backed job queue engine with advanced job control.


### Node.js management

- [n ★6843](tj/n) - Node.js version management.
- [nave ★1048](isaacs/nave) - Virtual Environments for Node.js.
- [nodeenv ★699](ekalinin/nodeenv) - Node.js virtual environment compatible to Python's virtualenv.
- [nvm for Windows ★3376](coreybutler/nvm-windows) - Version management for Windows.


### Polyfills

- Node.js
	- [user-info ★32](sindresorhus/user-info) - Node.js 6 `os.userInfo()` ponyfill.
	- [buffer-includes ★7](sindresorhus/buffer-includes) - Node.js 5.3 `buffer.includes()` ponyfill.
	- [deep-strict-equal ★20](sindresorhus/deep-strict-equal) - Test for deep equality - Node.js `assert.deepStrictEqual()` algorithm as a standalone module.
- JavaScript
	- [harmony-reflect ★340](tvcutsem/harmony-reflect) - ES2015 `Reflect` and `Proxy` polyfill.
	- [es6-shim ★2219](paulmillr/es6-shim) - Collection of ES2015 polyfills.


### Natural language processing

- [retext ★1241](wooorm/retext) - An extensible natural language system.
- [franc ★2264](wooorm/franc) - Detect the language of text.
- [leven ★270](sindresorhus/leven) - Measure the difference between two strings using the Levenshtein distance algorithm.
- [natural ★6405](NaturalNode/natural) - Natural language facility.


### Process management

- [PM2 ★19068](Unitech/pm2) - Advanced Process Manager.
- [nodemon ★10900](remy/nodemon) - Monitor for changes in your app and automatically restart the server.
- [node-mac ★377](coreybutler/node-mac) - Run scripts as a native Mac daemon and log to the console app.
- [node-linux ★311](coreybutler/node-linux) - Run scripts as native system service and log to syslog.
- [node-windows ★1069](coreybutler/node-windows) - Run scripts as a native Windows service and log to the Event viewer.
- [forever ★9688](foreverjs/forever) - Ensures that a given script runs continuously.
- [supervisor ★3105](petruisfan/node-supervisor) - Restart scripts when they crash or restart when a `*.js` file changes.
- [Phusion Passenger](https://www.phusionpassenger.com) - Friendly process manager that integrates directly into Nginx.
- [naught ★676](andrewrk/naught) - Process manager with zero downtime deployment.


### Automation

- [robotjs ★6007](octalmage/robotjs) - Desktop Automation: control the mouse, keyboard and read the screen.


### AST

- [Acorn ★2496](ternjs/acorn) - Tiny, fast JavaScript parser.
- [Rocambole ★143 ⏳1Y](millermedeiros/rocambole) - Recursively walk and transform JavaScript AST.


### Static site generators

- [Metalsmith](http://www.metalsmith.io) - Pluggable static site generator.
- [Wintersmith](http://wintersmith.io) - Flexible, minimalistic, multi-platform static site generator.
- [Assemble](http://assemble.io) - Static site generator for Node.js, Grunt.js, and Yeoman.
- [DocPad ★2917](docpad/docpad) - Static site generator with dynamic abilities and huge plugin ecosystem.
- [Phenomic](https://phenomic.io) - Modern static website generator based on the React and Webpack ecosystem.
- [docsify](https://docsify.js.org) - Markdown documentation site generator with no statically built HTML files.


### Content management systems

- [KeystoneJS](http://keystonejs.com) - CMS and web application platform built on Express and MongoDB.
- [Apostrophe2](http://apostrophenow.org) - Content management system with an emphasis on intuitive front end content editing and administration built on Express and MongoDB.


### Forum

- [nodeBB](https://nodebb.org) - Forum platform for the modern web.


### Blogging

- [ghost](https://ghost.org) - Simple, powerful publishing platform.
- [Hexo](https://hexo.io) - Fast, simple and powerful blogging framework.


### Weird

- [cows ★156 ⏳1Y](sindresorhus/cows) - ASCII cows.
- [superb ★210](sindresorhus/superb) - Get superb like words.
- [cat-names ★169](sindresorhus/cat-names) - Get popular cat names.
- [dog-names ★73](sindresorhus/dog-names) - Get popular dog names.
- [superheroes ★117](sindresorhus/superheroes) - Get superhero names.
- [supervillains ★62](sindresorhus/supervillains) - Get supervillain names.
- [cool-ascii-faces ★1465](maxogden/cool-ascii-faces) - Get some cool ascii faces.
- [cat-ascii-faces ★162 ⏳2Y](melaniecebula/cat-ascii-faces) - ₍˄·͈༝·͈˄₎◞ ̑̑ෆ⃛ (=ↀωↀ=)✧ (^･o･^)ﾉ”
- [nerds ★18](SkyHacks/nerds) - Get data from nerdy topics like Harry Potter, Star Wars, and Pokémon.


### Miscellaneous

- [execa ★710](sindresorhus/execa) - Better `child_process`.
- [cheerio ★12297](cheeriojs/cheerio) - Fast, flexible, and lean implementation of core jQuery designed specifically for the server.
- [Electron](https://github.com/atom/electron) - Build cross platform desktop apps with web technologies. *(You might like [awesome-electron ★11149](sindresorhus/awesome-electron))*
- [opn ★538](sindresorhus/opn) - Opens stuff like websites, files, executables.
- [hasha ★510](sindresorhus/hasha) - Hashing made simple. Get the hash of a buffer/string/stream/file.
- [dot-prop ★163](sindresorhus/dot-prop) - Get a property from a nested object using a dot path.
- [onetime ★63](sindresorhus/onetime) - Only run a function once.
- [mem ★266](sindresorhus/mem) - Memoize functions - an optimization technique used to speed up consecutive function calls by caching the result of calls with identical input.
- [import-fresh ★69](sindresorhus/import-fresh) - Import a module while bypassing the cache.
- [strip-bom ★45](sindresorhus/strip-bom) - Strip UTF-8 byte order mark (BOM) from a string/buffer/stream.
- [os-locale ★83](sindresorhus/os-locale) - Get the system locale.
- [nan ★1811](nodejs/nan) - Makes native add-on development for across Node.js versions easier.
- [ssh2 ★2517](mscdex/ssh2) - SSH2 client and server module.
- [adit ★10](markelog/adit) - SSH tunneling made simple.
- [import-lazy ★96](sindresorhus/import-lazy) - Import a module lazily.
- [file-type ★366](sindresorhus/file-type) - Detect the file type of a Buffer.
- [Bottleneck ★264](SGrondin/bottleneck) - Rate limiter that makes throttling easy.
- [webworker-threads ★1265](audreyt/node-webworker-threads) - Lightweight Web Worker API implementation with native threads.
- [clipboardy ★237](sindresorhus/clipboardy) - Access the system clipboard (copy/paste).
- [node-pre-gyp ★394](mapbox/node-pre-gyp) - Makes it easy to publish and install Node.js C++ addons from binaries.
- [opencv ★2706](peterbraden/node-opencv) - Bindings for OpenCV. The defacto computer vision library.
- [dotenv ★3115](motdotla/dotenv) - Load environment variables from .env file.
- [remote-git-tags ★26](sindresorhus/remote-git-tags) - Get tags from a remote git repo.
- [semver ★1744](npm/node-semver) - [semver](http://semver.org) parser.
- [nar ★404](h2non/nar) - Create self-contained executable binaries.
- [Faker.js ★10299](Marak/Faker.js) - Generate massive amounts of fake data.
- [nodegit ★2757](nodegit/nodegit) - Native bindings to Git.
- [json-strictify ★1](pigulla/json-strictify) - Safely serialize a value to JSON without data loss or going into an infinite loop.
- [parent-module ★15 ⏳1Y](sindresorhus/parent-module) - Get the path of the parent module.
- [resolve-from ★31](sindresorhus/resolve-from) - Resolve the path of a module like `require.resolve()` but from a given path.
- [simplecrawler ★1452](cgiffard/node-simplecrawler) - Event driven web crawler.
- [jsdom ★7667](tmpvar/jsdom) - JavaScript implementation of HTML and the DOM.
- [hypernova ★3086](airbnb/hypernova) - Server-side rendering your JavaScript views.


## Resources

### Tutorials

- [Nodeschool](http://nodeschool.io) - Learn Node.js with interactive lessons.
- [The Art of Node](https://github.com/maxogden/art-of-node/#the-art-of-node) - An introduction to Node.js.
- [stream-handbook ★10191](substack/stream-handbook) - How to write Node.js programs with streams.
- [browserify-handbook ★4052](substack/browserify-handbook) - The definitive guide for browserify.
- [module-best-practices ★873 ⏳1Y](mattdesl/module-best-practices) - Some good practices when writing new npm modules.
- [The Node Way](http://thenodeway.io) - An entire philosophy of Node.js best practices and guiding principles exists for writing maintainable modules, scalable applications, and code that is actually pleasant to read.
- [You Don't Know Node.js ★621](azat-co/you-dont-know-node) - Introduction to Node.js core features and asynchronous JavaScript.


### Discovery

- [npms](https://npms.io) - Superb package search with deep analysis of package quality using a [myriad of metrics](https://npms.io/about).
- [node-modules.com](http://node-modules.com) - An alternative npm search engine with a more intelligent and personal results ranking.
- [npm addict](https://npmaddict.com) - Your daily injection of npm packages.
- [npmcompare.com](https://npmcompare.com) - Compare and discover npm packages.

### Articles

- [Error Handling in Node.js](https://www.joyent.com/node-js/production/design/errors)
- [Teach Yourself Node.js in 10 Steps](https://ponyfoo.com/articles/teach-yourself-nodejs-in-10-steps)
- [Mastering the filesystem in Node.js](https://medium.com/@yoshuawuyts/mastering-the-filesystem-in-node-js-4706b7cb0801)
- [Semver: A Primer](https://nodesource.com/blog/semver-a-primer/)
- [Semver: Tilde and Caret](https://nodesource.com/blog/semver-tilde-and-caret/)
- [Why Asynchronous?](https://nodesource.com/blog/why-asynchronous/)
- [Understanding the Node.js Event Loop](https://nodesource.com/blog/understanding-the-nodejs-event-loop/)
- [Understanding Object Streams](https://nodesource.com/blog/understanding-object-streams/)
- [Art of README ★4387](noffle/art-of-readme) - Learn the art of writing quality READMEs.

### Newsletters

- [node weekly](http://nodeweekly.com) - Weekly e-mail round-up of Node.js news and articles.
- [nmotw](http://nmotw.in) - Node Module Of The Week, weekly dose of hand picked node modules.

### Videos

- [Introduction to Node.js with Ryan Dahl](https://www.youtube.com/watch?v=jo_B4LTHi3I)
- [Introduction to Node.js Fundamentals](http://strongloop.com/node-js/videos/#a-video-intro-to-nodejs-fundamentals)
- [Hands on with Node.js](https://learn.bevry.me/node/preface)
- [Full Streams Ahead](http://dry.ly/full-streams-ahead) - Introduction to streams.
- [StrongLoop Talks](https://strongloop.com/node-js/videos/) - Series of talks.
- [thenewboston's Node.js for Beginners](https://www.thenewboston.com/videos.php?cat=355)
- [Nodetuts](http://nodetuts.com) - Series of talks, including TCP & HTTP API servers, async programming, and more.
- [Node Interactive 2015 ★36 ⏳1Y](duffn/nodeinteractive-2015) - List of talks, keynotes and panels from the 2015 Node Interactive conference.

### Podcasts

- [NodeUp](http://nodeup.com)
- [Mostly Node](http://mostlynode.com)

### Books

- [Node.js in Action](http://www.amazon.com/Node-js-Action-Mike-Cantelon/dp/1617290572)
- [Node.js in Practice](http://www.amazon.com/Node-js-Practice-Alex-R-Young/dp/1617290939)
- [Mastering Node](http://visionmedia.github.io/masteringnode/)
- [Professional Node.js: Building Javascript Based Scalable Software](http://www.amazon.com/Professional-Node-js-Building-Javascript-Scalable-ebook/dp/B009L7QETY/)
- [Practical Node.js: Building Real-World Scalable Web Apps](http://practicalnodebook.com)
- [Mixu's Node book](http://book.mixu.net/node/)
- [Web Development with Node and Express](http://shop.oreilly.com/product/0636920032977.do)
- [Pro Express.js](http://proexpressjs.com)
- [Secure Your Node.js Web Application](http://www.amazon.com/Secure-Your-Node-js-Web-Application/dp/1680500856)
- [Express in Action](https://www.manning.com/books/express-in-action)

### Blogs

- [Node.js blog](https://nodejs.org/en/blog/)
- [HowToNode](http://howtonode.org) - Teaching how to do various tasks in Node.js as well as teach fundamental concepts that are needed to write effective code.
- [webapplog.com](http://webapplog.com/tag/node-js/) - Blog posts on Node.js and JavaScript from the author of Practical Node.js and Pro Express.js Azat Mardan.

### Courses

- [Real Time Web with Node.js](https://www.codeschool.com/courses/real-time-web-with-node-js)
- [Learn and Understand Node.js](https://www.udemy.com/understand-nodejs)
- [Learn to build apps and APIs with Node.js](https://learnnode.com/friend/AWESOME) - Video course by Wes Bos.

### Cheatsheets

- [Express.js](https://github.com/azat-co/cheatsheets/blob/master/express4)
- [Stream FAQs ★142 ⏳1Y](stephenplusplus/stream-faqs) - Answering common questions about streams, covering pagination, events, and more.

### Tools

- [OctoLinker](https://chrome.google.com/webstore/detail/octolinker/jlmafbaeoofdegohdhinkhilhclaklkp) - Chrome extension that linkifies dependencies in package.json, .js, .jsx, .coffee and .md files on GitHub.
- [npm-hub](https://chrome.google.com/webstore/detail/npm-hub/kbbbjimdjbjclaebffknlabpogocablj) - Chrome extension to display npm dependencies at the bottom of a repo's readme.
- [RunKit](http://blog.tonicdev.com/2015/09/30/embedded-tonic.html) - Embed a Node.js environment on any website.
- [RequireBin](http://requirebin.com) - Shareable JavaScript programs powered by npm and browserify.

### Community

- [Gitter](https://gitter.im/nodejs/node)
- [`#node.js` on Freenode](http://webchat.freenode.net/?channels=node.js)
- [Stack Overflow](http://stackoverflow.com/questions/tagged/node.js)
- [Reddit](https://www.reddit.com/r/node)
- [Twitter](https://twitter.com/nodejs)
- [Hashnode](https://hashnode.com/n/nodejs)

### Miscellaneous

- [nodebots](http://nodebots.io) - Robots powered by JavaScript.
- [node-module-boilerplate ★356](sindresorhus/node-module-boilerplate) - Boilerplate to kickstart creating a node module.
- [generator-nm ★450](sindresorhus/generator-nm) - Scaffold out a node module.
- [awesome-cross-platform-nodejs ★200](bcoe/awesome-cross-platform-nodejs) - Resources for writing and testing cross-platform code.
- [Microsoft Node.js Guidelines ★1690](Microsoft/nodejs-guidelines) - Tips, tricks, and resources for working with Node.js on Microsoft platforms.


## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Sindre Sorhus](http://sindresorhus.com) has waived all copyright and related or neighboring rights to this work.
---
<p align="center">
	This list is a copy of <a href="sindresorhus/awesome-nodejs">sindresorhus/awesome-nodejs</a> with ranks
</p>
