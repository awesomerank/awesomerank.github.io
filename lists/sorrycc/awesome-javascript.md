<h1 align="center">
Ranked awesome lists, all in one place
</h1>
<p align="center">
	This list is a copy of <a href="sorrycc/awesome-javascript">sorrycc/awesome-javascript</a> with ranks
</p>
---
# Awesome JavaScript [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg) ★59088](sindresorhus/awesome)

A collection of awesome browser-side [JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript) libraries, resources and shiny things.

* [Awesome JavaScript](#awesome-javascript)
  * [Package Managers](#package-managers)
  * [Loaders](#loaders)
  * [Bundlers](#bundlers)
  * [Testing Frameworks](#testing-frameworks)
  * [QA Tools](#qa-tools)
  * [MVC Frameworks and Libraries](#mvc-frameworks-and-libraries)
  * [Node-Powered CMS Frameworks](#node-powered-cms-frameworks)
  * [Templating Engines](#templating-engines)
  * [Articles/Posts](#articles-and-posts)
  * [Data Visualization](#data-visualization)
    * [Timeline](#timeline)
    * [Spreadsheet](#spreadsheet)
  * [Editors](#editors)
  * [Documentation](#documentation)
  * Utilities
    * [Files](#files)
    * [Functional Programming](#functional-programming)
    * [Reactive Programming](#reactive-programming)
    * [Data Structure](#data-structure)
    * [Date](#date)
    * [String](#string)
    * [Number](#number)
    * [Storage](#storage)
    * [Color](#color)
    * [I18n And L10n](#i18n-and-l10n)
    * [Class](#class)
    * [Control Flow](#control-flow)
    * [Routing](#routing)
    * [Security](#security)
    * [Log](#log)
    * [RegExp](#regexp)
    * [Media](#media)
    * [Voice Command](#voice-command)
    * [API](#api)
    * [Streaming](#streaming)
    * [Vision Detection](#vision-detection)
    * [Browser Detection](#browser-detection)
    * [Benchmark](#benchmark)
    * [Machine Learning](#machine-learning)
  * UI
    * [Code Highlighting](#code-highlighting)
    * [Loading Status](#loading-status)
    * [Validation](#validation)
    * [Keyboard Wrappers](#keyboard-wrappers)
    * [Tours And Guides](#tours-and-guides)
    * [Notifications](#notifications)
    * [Sliders](#sliders)
    * [Range Sliders](#range-sliders)
    * [Form Widgets](#form-widgets)
    * [Tips](#tips)
    * [Modals and Popups](#modals-and-popups)
    * [Scroll](#scroll)
    * [Menu](#menu)
    * [Table/Grid](#tablegrid)
    * [Frameworks](#frameworks-1)
    * [Boilerplates](#boilerplates)
  * [Gesture](#gesture)
  * [Maps](#maps)
  * [Typography](#typography)
  * [Animations](#animations)
  * [Image processing](#image-processing)
  * [ES6](#es6)
  * [SDK](#sdk)
  * [Misc](#misc)
  * [Podcasts](#podcasts)
* [Worth Reading](#worth-reading)
* [Other Awesome Lists](#other-awesome-lists)
* [Contributing](#contributing)

----


## Package Managers
*Host the javascript libraries and provide tools for fetching and packaging them.*

* [npm](https://www.npmjs.com/) - npm is the package manager for javascript.
* [Bower ★15099](bower/bower) - A package manager for the web.
* [component ★4602 ⏳1Y](componentjs/component) - Client package management for building better web applications.
* [spm ★911 ⏳1Y](spmjs/spm) - Brand new static package manager.
* [jam ★1536](caolan/jam) - A package manager using a browser-focused and RequireJS compatible repository.
* [jspm ★3575](jspm/jspm-cli) - Frictionless browser package management.
* [Ender ★1825 ⏳2Y](ender-js/Ender) - The no-library library.
* [volo ★1380](volojs/volo) - Create front end projects from templates, add dependencies, and automate the resulting projects.
* [Duo ★3546](duojs/duo) - Next-generation package manager that blends the best ideas from Component, Browserify and Go to make organizing and writing front-end code quick and painless.
* [yarn](https://yarnpkg.com/) - Fast, reliable, and secure dependency management.


## Loaders
*Module or loading system for JavaScript.*

* [RequireJS ★10611](requirejs/requirejs) - A file and module loader for JavaScript.
* [browserify ★11052](substack/node-browserify) - Browser-side require() the node.js way.
* [SeaJS ★6735](seajs/seajs) - A Module Loader for the Web.
* [HeadJS ★4108](headjs/headjs) - The only script in your HEAD.
* [curl ★1749](cujojs/curl) - A small, fast, extensible module loader that handles AMD, CommonJS Modules/1.1, CSS, HTML/text, and legacy scripts.
* [lazyload ★1223 ⏳1Y](rgrove/lazyload) - Tiny, dependency-free async JavaScript and CSS loader.
* [script.js ★2310](ded/script.js) - Asyncronous JavaScript loader and dependency manager.
* [systemjs ★8256](systemjs/systemjs) - AMD, CJS & ES6 spec-compliant module loader.
* [LodJS ★267](yanhaijing/lodjs) - Module loader based on AMD
* [ESL ★662](ecomfe/esl) - Module loader browser first, support lazy define and AMD.
* [modulejs ★100](lrsjng/modulejs) - Lightweight JavaScript module system.


## Bundlers

* [browserify ★11052](substack/node-browserify) - Browserify lets you require('modules') in the browser by bundling up all of your dependencies.
* [webpack ★28143](webpack/webpack) - Packs CommonJs/AMD modules for the browser.
* [Rollup ★9440](rollup/rollup) - Next-generation ES6 module bundler.
* [Brunch ★5949](brunch/brunch) - Fast front-end web app build tool with simple declarative config.


## Testing Frameworks

### Frameworks

* [mocha ★12418](mochajs/mocha) - Simple, flexible, fun javascript test framework for node.js & the browser.
* [jasmine ★12492](jasmine/jasmine) - DOM-less simple JavaScript testing framework.
* [qunit](https://github.com/jquery/qunit) - An easy-to-use JavaScript Unit Testing framework.
* [jest ★10350](facebook/jest) - Painless Javascript Unit Testing.
* [prova ★323](azer/prova) - Node & Browser test runner based on Tape and Browserify
* [DalekJS ★727](dalekjs/dalek) - Automated cross browser functional testing with JavaScript
* [Protractor ★6605](angular/protractor) - Protractor is an end-to-end test framework for AngularJS applications.
* [tape ★3869](substack/tape) - Tap-producing test harness for node and browsers.
* [TestCafe ★2589](DevExpress/testcafe) - Automated browser testing for the modern web development stack.
* [ava ★10262](avajs/ava) - 🚀 Futuristic JavaScript test runner

### Assertion

* [chai ★4181](chaijs/chai) - BDD / TDD assertion framework for node.js and the browser that can be paired with any testing framework.
* [Enzyme](http://airbnb.io/enzyme/index.html) - Enzyme is a JavaScript Testing utility for React that makes it easier to assert, manipulate, and traverse your React Components' output.
* [Sinon.JS ★4189](sinonjs/sinon) - Test spies, stubs, and mocks for JavaScript.
* [expect.js ★1702](Automattic/expect.js) - Minimalistic BDD-style assertions for Node.JS and the browser.

### Coverage

* [istanbul ★6208](gotwarlost/istanbul) - Yet another JS code coverage tool.
* [blanket ★1347 ⏳1Y](alex-seville/blanket) - A simple code coverage library for javascript. Designed to be easy to install and use, for both browser and nodejs.
* [JSCover ★327](tntim96/JSCover) - JSCover is a tool that measures code coverage for JavaScript programs.

### Runner

* [phantomjs ★22244](ariya/phantomjs) - Scriptable Headless WebKit.
* [slimerjs ★2247](laurentj/slimerjs) - A PhantomJS-like tool running Gecko.
* [casperjs ★6622](casperjs/casperjs) - Navigation scripting & testing utility for PhantomJS and SlimerJS.
* [zombie ★4492](assaf/zombie) - Insanely fast, full-stack, headless browser testing using node.js.
* [totoro ★545 ⏳2Y](totorojs/totoro) - A simple and stable cross-browser testing tool.
* [karma ★8596](karma-runner/karma) - Spectacular Test Runner for JavaScript.
* [nightwatch ★6484](nightwatchjs/nightwatch) - UI automated testing framework based on node.js and selenium webdriver.
* [intern ★3745](theintern/intern) - A next-generation code testing stack for JavaScript.
* [yolpo](http://www.yolpo.com) - A statement-by-statement javascript interpreter in the browser.


## QA Tools

* [JSHint ★7237](jshint/jshint) - JSHint is a tool that helps to detect errors and potential problems in your JavaScript code.
* [jscs ★5140](jscs-dev/node-jscs) - JavaScript Code Style checker.
* [jsfmt ★1702](rdio/jsfmt) - For formatting, searching, and rewriting JavaScript.
* [jsinspect ★1449](danielstjules/jsinspect) - Detect copy-pasted and structurally similar code.
* [buddy.js ★552](danielstjules/buddy.js) - Magic number detection for JavaScript.
* [ESLint ★7676](eslint/eslint) - A fully pluggable tool for identifying and reporting on patterns in JavaScript.
* [JSLint ★2957](douglascrockford/JSLint) - High-standards, strict & opinionated code quality tool, aiming to keep only good parts of the language.


## MVC Frameworks and Libraries

* [angular.js ★55921](angular/angular.js) - HTML enhanced for web apps.
* [aurelia](http://aurelia.io) - A Javascript client framework for mobile, desktop and web.
* [backbone ★26349](jashkenas/backbone) - Give your JS App some Backbone with Models, Views, Collections, and Events.
* [batman.js](http://batmanjs.org/) - The best JavaScript framework for Rails developers.
* [ember.js ★17886](emberjs/ember.js) - A JavaScript framework for creating ambitious web applications.
* [meteor ★37519](meteor/meteor) - An ultra-simple, database-everywhere, data-on-the-wire, pure-Javascript web framework.
* [ractive ★5285](ractivejs/ractive) - Next-generation DOM manipulation.
* [vue ★54875](vuejs/vue) - Intuitive, fast & composable MVVM for building interactive interfaces.
* [knockout ★8209](knockout/knockout) - Knockout makes it easier to create rich, responsive UIs with JavaScript.
* [spine ★3294](spine/spine) - Lightweight MVC library for building JavaScript applications.
* [espresso.js ★527 ⏳2Y](techlayer/espresso.js) - A minimal javascript library for crafting user interfaces.
* [canjs ★1492](canjs/canjs) - Can do JS, better, faster, easier.
* [react](https://facebook.github.io/react/) - A library for building user interfaces. It's declarative, efficient, and extremely flexible. Works with a Virtual DOM.
* [preact ★9766](developit/preact) - Fast 3kb React alternative with the same ES6 API. Components & Virtual DOM.
* [nativescript ★10290](NativeScript/NativeScript) - Build truly native cross-platform iOS and Android apps with JavaScript
* [react-native ★48867](facebook/react-native) - A framework for building native apps with React.
* [riot ★11960](riot/riot) - React-like library, but with very small size.
* [thorax ★1371 ⏳1Y](walmartlabs/thorax) - Strengthening your Backbone.
* [chaplin ★2971](chaplinjs/chaplin) - An architecture for JavaScript applications using the Backbone.js library.
* [marionette ★7125](marionettejs/backbone.marionette) - A composite application library for Backbone.js that aims to simplify the construction of large scale JavaScript applications.
* [ripple ★1279 ⏳2Y](ripplejs/ripple) - A tiny foundation for building reactive views.
* [rivets ★2977](mikeric/rivets) - Lightweight and powerful data binding + templating solution.
* [derby ★4262](derbyjs/derby) - MVC framework making it easy to write realtime, collaborative applications that run in both Node.js and browsers.
    * [derby-awesome ★10 ⏳2Y](russll/awesome-derby) - A collection of awesome derby components
* [way.js ★2764](gwendall/way.js) - Simple, lightweight, persistent two-way databinding.
* [mithril.js](https://github.com/lhorie/mithril.js) - Mithril is a client-side MVC framework (Light-weight, Robust, Fast).
* [jsblocks ★2814](astoilkov/jsblocks) - jsblocks is better MV-ish framework.
* [LiquidLava](http://www.lava-framework.com/) - Transparent MVC framework for building user interfaces.
* [feathers ★6523](feathersjs/feathers) - A minimalist real-time JavaScript framework for tomorrow's apps.
* [Keo ★206](Wildhoney/Keo) - Functional stateless React components with Shadow DOM support.

## Node-Powered CMS Frameworks

* [KeystoneJS ★9972](keystonejs/keystone) - powerful CMS and web app framework
* [Reaction Commerce ★4693](reactioncommerce/reaction) - reactive CMS, real-time architecture and design
* [Ghost ★22764](tryghost/Ghost) - simple, powerful publishing platform
* [Apostrophe ★1492](punkave/apostrophe) - CMS with content editing and essential services
* [We.js ★172](wejs/we) - framework for real time apps, sites or blogs
* [Hatch.js ★68](inventures/hatchjs) - CMS platform with social features.
* [TaracotJS ★15 ⏳2Y](xtremespb/taracotjs-generator) - fast and minimalist CMS based on Node.js.
* [Nodizecms ★183 ⏳4Y](nodize/nodizecms) - CMS for CoffeeScript lovers
* [Cody ★614](jcoppieters/cody) - CMS with WSYWYG editor
* [PencilBlue ★1575](pencilblue/pencilblue) - CMS and blogging platform

## Templating Engines
*Templating engines allow you to perform string interpolation.*

* [mustache.js ★10773](janl/mustache.js) - Minimal templating with {{mustaches}} in JavaScript.
* [handlebars.js ★11951](wycats/handlebars.js) - An extension to the Mustache templating language.
* [hogan.js ★4747](twitter/hogan.js) - A compiler for the Mustache templating language.
* [doT ★3414](olado/doT) - The fastest + concise javascript template engine for nodejs and browsers.
* [dustjs ★2573](linkedin/dustjs) - Asynchronous templates for the browser and node.js.
* [eco ★1777 ⏳2Y](sstephenson/eco) - Embedded CoffeeScript templates.
* [JavaScript-Templates ★1163](blueimp/JavaScript-Templates) - < 1KB lightweight, fast & powerful JavaScript templating engine with zero dependencies.
* [t.js ★763](jasonmoo/t.js) - A tiny javascript templating framework in ~400 bytes gzipped.
* [Jade ★14429](pugjs/pug) - Robust, elegant, feature rich template engine for nodejs.
* [EJS ★1449](mde/ejs) - Effective JavaScript templating.
* [xtemplate ★331](xtemplate/xtemplate) - eXtensible Template Engine lib for node and the browser
* [marko ★2847](marko-js/marko) - A fast, lightweight, HTML-based templating engine for Node.js and the browser with async, streaming, custom tags and CommonJS modules as compiled output.
* [swig](http://paularmstrong.github.io/swig/) - A simple, powerful, and extendable Node.js and browser-based JavaScript template engine.

## Articles and Posts

* [The JavaScript that you should know](https://medium.com/@pedropolisenso/o-javasscript-que-você-deveria-conhecer-b70e94d1d706) - Article about concepts of JavaScript Functional.

## Data Visualization
*Data visualization tools for the web.*

* [d3 ★64800](d3/d3) - A JavaScript visualization library for HTML and SVG.
  * [metrics-graphics ★6626](mozilla/metrics-graphics) - A library optimized for concise, principled data graphics and layouts.
* [pykcharts.js ★269](pykih/PykCharts.js) - Well designed d3.js charting without the complexity of d3.js.
* [three.js ★33048](mrdoob/three.js) - JavaScript 3D library.
* [Chart.js ★30194](chartjs/Chart.js) - Simple HTML5 Charts using the <canvas> tag.
* [paper.js ★7850](paperjs/paper.js) - The Swiss Army Knife of Vector Graphics Scripting – Scriptographer ported to JavaScript and the browser, using HTML5 Canvas.
* [fabric.js ★8037](kangax/fabric.js) - Javascript Canvas Library, SVG-to-Canvas (& canvas-to-SVG) Parser.
* [peity ★3811](benpickles/peity) - Progressive <svg> bar, line and pie charts.
* [raphael ★9100](DmitryBaranovskiy/raphael) - JavaScript Vector Library.
* [echarts ★18131](ecomfe/echarts) - Enterprise Charts.
* [vis ★5188](almende/vis) - Dynamic, browser-based visualization library.
* [two.js ★5029](jonobr1/two.js) - A renderer agnostic two-dimensional drawing api for the web.
* [g.raphael ★1514 ⏳1Y](DmitryBaranovskiy/g.raphael) - Charts for Raphaël.
* [sigma.js ★7238](jacomyal/sigma.js) - A JavaScript library dedicated to graph drawing.
* [arbor ★2391 ⏳1Y](samizdatco/arbor) - A graph visualization library using web workers and jQuery.
* [cubism ★4523](square/cubism) - A D3 plugin for visualizing time series.
* [dc.js ★5660](dc-js/dc.js) - Multi-Dimensional charting built to work natively with crossfilter rendered with d3.js
* [vega ★16 ⏳1Y](trifacta/vega) - A visualization grammar.
* [processing.js](http://processingjs.org/) - Processing.js makes your data visualizations work using web standards and without any plug-ins
* [envisionjs ★1556 ⏳4Y](HumbleSoftware/envisionjs) - Dynamic HTML5 visualization.
* [rickshaw ★6035](shutterstock/rickshaw) - JavaScript toolkit for creating interactive real-time graphs.
* [flot ★5351](flot/flot) - Attractive JavaScript charts for jQuery.
* [morris.js ★6500](morrisjs/morris.js) - Pretty time-series line graphs.
* [nvd3 ★5982](novus/nvd3) - Build re-usable charts and chart components for d3.js
* [svg.js](https://github.com/wout/svg.js) - A lightweight library for manipulating and animating SVG.
* [heatmap.js ★3822](pa7/heatmap.js) - JavaScript Library for HTML5 canvas based heatmaps.
* [jquery.sparkline ★1052](gwatts/jquery.sparkline) - A plugin for the jQuery javascript library to generate small sparkline charts directly in the browser.
* [xCharts ★1793 ⏳3Y](tenxer/xCharts) - A D3-based library for building custom charts and graphs.
* [trianglify ★7509](qrohlf/trianglify) - Low poly style background generator with d3.js
* [d3-cloud ★2077](jasondavies/d3-cloud) - Create word clouds in JavaScript.
* [d4 ★393](heavysixer/d4) - A friendly reusable charts DSL for D3.
* [dimple.js](http://dimplejs.org) -  Easy charts for business analytics powered by d3
* [chartist-js ★9525](gionkunz/chartist-js) - Simple responsive charts.
* [epoch ★4832](epochjs/epoch) - A general purpose real-time charting library.
* [c3 ★6756](c3js/c3) - D3-based reusable chart library.
* [BabylonJS ★4509](BabylonJS/Babylon.js) - A framework for building 3D games with HTML 5 and WebGL.
* [recharts ★5674](recharts/recharts) - Redefined chart library built with React and D3
* [GraphicsJS](https://www.graphicsjs.org) - A lightweight JavaScript graphics library with the intuitive API, based on SVG/VML technology.

There're also some great commercial libraries, like [amchart](https://www.amcharts.com/), [anychart](http://www.anychart.com), [plotly](https://plot.ly/), and [highchart](http://www.highcharts.com/).


## Timeline

* [TimelineJS ★8364](NUKnightLab/TimelineJS) - A Storytelling Timeline built in JavaScript.
* [timesheet.js ★36 ⏳2Y](semu/timesheet.js) - JavaScript library for simple HTML5 & CSS3 time sheets.

## Spreadsheet

* [HANDSONTABLE ★8060](handsontable/handsontable) - Handsontable is a JavaScript/HTML5 Spreadsheet Library for Developers

## Editors

* [ace ★14993](ajaxorg/ace) - Ace (Ajax.org Cloud9 Editor).
* [CodeMirror ★11831](codemirror/CodeMirror) - In-browser code editor.
* [esprima ★253](ariya/esprima) - ECMAScript parsing infrastructure for multipurpose analysis.
* [quill ★13491](quilljs/quill) - A cross browser rich text editor with an API.
* [medium-editor ★10553](yabwe/medium-editor) - Medium.com WYSIWYG editor clone.
* [pen ★4136](sofish/pen) - enjoy live editing (+markdown).
* [jquery-notebook ★1688](raphaelcruzeiro/jquery-notebook) - A simple, clean and elegant text editor. Inspired by the awesomeness of Medium.
* [bootstrap-wysiwyg ★5318](mindmup/bootstrap-wysiwyg) - Tiny bootstrap-compatible WYSIWYG rich text editor.
* [ckeditor-releases ★346](ckeditor/ckeditor-releases) - The best web text editor for everyone.
* [editor ★2357 ⏳1Y](lepture/editor) - A markdown editor. still on development.
* [EpicEditor ★4369](OscarGodson/EpicEditor) - An embeddable JavaScript Markdown editor with split fullscreen editing, live previewing, automatic draft saving, offline support, and more.
* [jsoneditor ★3331](josdejong/jsoneditor) - A web-based tool to view, edit and format JSON.
* [vim.js ★4091 ⏳1Y](coolwanglu/vim.js) - JavaScript port of Vim with a persistent ~/.vimrc
* [Squire ★3604](neilj/Squire) - HTML5 rich text editor.
* [TinyMCE ★4359](tinymce/tinymce) - The JavaScript Rich Text editor.
* [trix ★7668](basecamp/trix) - A rich text editor for everyday writing. By Basecamp.
* [Trumbowyg ★1591](Alex-D/Trumbowyg) - A lightweight and amazing WYSIWYG JavaScript editor.
* [Draft.js ★9977](facebook/draft-js) - A React framework for building text editors.
* [bootstrap-wysihtml5 ★4209](jhollingworth/bootstrap-wysihtml5) - Simple, beautiful wysiwyg editor
* [wysihtml5 ★6598 ⏳1Y](xing/wysihtml5) - Open source rich text editor based on HTML5 and the progressive-enhancement approach. Uses a sophisticated security concept and aims to generate fully valid HTML5 markup by preventing unmaintainable tag soups and inline styles.
* [raptor-editor ★523 ⏳2Y](PANmedia/raptor-editor) - Raptor, an HTML5 WYSIWYG content editor!
* [popline ★1031 ⏳1Y](kenshin54/popline) - Popline is an HTML5 Rich-Text-Editor Toolbar


## Documentation

* [DevDocs](http://devdocs.io/) is an all-in-one API documentation reader with a fast, organized, and consistent interface.
* [dexy](http://www.dexy.it/) is a free-form literate documentation tool for writing any kind of technical document incorporating code.
* [docco](http://jashkenas.github.io/docco/) is a quick-and-dirty, hundred-line-long, literate-programming-style documentation generator.
* [styledocco](http://jacobrask.github.io/styledocco/) generates documentation and style guide documents from your stylesheets.
* [Ronn ★945](rtomayko/ronn) builds manuals. It converts simple, human readable textfiles to roff for terminal display, and also to HTML for the web.
* [dox ★1973](tj/dox) is a JavaScript documentation generator written with node. Dox no longer generates an opinionated structure or style for your docs, it simply gives you a JSON representation, allowing you to use markdown and JSDoc-style tags.
* [jsdox ★186](sutoiku/jsdox) is a JSDoc3 to Markdown documentation generator.
* [YUIDoc](http://yui.github.io/yuidoc/) is a Node.js application that generates API documentation from comments in source, using a syntax similar to tools like Javadoc and Doxygen.
* [coddoc](http://doug-martin.github.io/coddoc/) is a jsdoc parsing library. Coddoc is different in that it is easily extensible by allowing users to add tag and code parsers through the use of coddoc.addTagHandler and coddoc.addCodeHandler. coddoc also parses source code to be used in APIs.
* [sphinx](http://www.sphinx-doc.org/) a tool that makes it easy to create intelligent and beautiful documentation
* [Using JSDoc](http://usejsdoc.org/)
* [Beautiful docs](http://beautifuldocs.com/) is a documentation viewer based on markdown files.
* [documentation.js](http://documentation.js.org) - API documentation generator with support for ES2015+ and flow annotation.
* [jsduck ★1405](senchalabs/jsduck) - API documentation generator made for Sencha JavaScript frameworks, but can be used for other frameworks too.



## Files
*Libraries for working with files.*

* [Papa Parse ★4170](mholt/PapaParse) - A powerful CSV library that supports parsing CSV files/strings and also exporting to CSV.
* [jBinary ★387](jDataView/jBinary) - High-level I/O (loading, parsing, manipulating, serializing, saving) for binary files with declarative syntax for describing file types and data structures.
* [diff2html ★330](rtfpessoa/diff2html) - Git diff output parser and pretty HTML generator.
* [jsPDF ★8193](MrRio/jsPDF) - JavaScript PDF generation.


## Functional Programming
*Functional programming libraries to extend JavaScript’s capabilities.*

* [underscore ★20713](jashkenas/underscore) - JavaScript's utility _ belt.
* [lodash ★23692](lodash/lodash) - A utility library delivering consistency, customization, performance, & extras.
* [Sugar ★3322](andrewplummer/Sugar) - A Javascript library for working with native objects.
* [lazy.js ★4154](dtao/lazy.js) - Like Underscore, but lazier.
* [ramda ★30](CrossEye/ramda) - A practical functional library for Javascript programmers.
* [mout ★746](mout/mout) - Modular JavaScript Utilities.
* [mesh ★1018](crcn/mesh.js) - Streamable data synchronization utility.
* [preludejs ★51](alanrsoares/prelude-js) - Hardcore Functional Programming for JavaScript.


## Reactive Programming
*Reactive programming libraries to extend JavaScript’s capabilities.*

* [RxJs ★16169](Reactive-Extensions/RxJS) - The Reactive Extensions for JavaScript.
* [Bacon ★5663](baconjs/bacon.js) - FRP (functional reactive programming) library for Javascript.
* [Kefir ★5 ⏳1Y](pozadi/kefir) - FRP library for JavaScript inspired by Bacon.js and RxJS with focus on high performance and low memory consumption.
* [Highland] (http://highlandjs.org/) - Re-thinking the JavaScript utility belt, Highland manages synchronous and asynchronous code easily, using nothing more than standard JavaScript and Node-like Streams.
* [Most.js ★1962](cujojs/most) - high performance FRP library.
* [MobX ★9285](mobxjs/mobx) - TFRP library for simple, scalable state management.
* [Cycle.js](https://cycle.js.org) - A functional and reactive JavaScript library for cleaner code.

## Data Structure
*Data structure libraries to build a more sophisticated application.*

* [immutable-js ★18899](facebook/immutable-js) - Immutable Data Collections including Sequence, Range, Repeat, Map, OrderedMap, Set and a sparse Vector.
* [mori ★2607](swannodette/mori) - A library for using ClojureScript's persistent data structures and supporting API from the comfort of vanilla JavaScript.
* [buckets ★717](mauriciosantos/Buckets-JS) - A complete, fully tested and documented data structure library written in JavaScript.
* [hashmap ★265](flesler/hashmap) - Simple hashmap implementation that supports any kind of keys.


## Date
*Date Libraries.*

* [moment ★31540](moment/moment) - Parse, validate, manipulate, and display dates in javascript.
* [moment-timezone ★2138](moment/moment-timezone) - Timezone support for moment.js.
* [jquery-timeago ★3622](rmm5t/jquery-timeago) - A jQuery plugin that makes it easy to support automatically updating fuzzy timestamps (e.g. "4 minutes ago").
* [timezone-js ★778](mde/timezone-js) - Timezone-enabled JavaScript Date object. Uses Olson zoneinfo files for timezone data.
* [date ★1238](MatthewMueller/date) - Date() for humans.
* [ms.js](https://github.com/rauchg/ms.js) - Tiny millisecond conversion utility.
* [countdown.js ★374 ⏳3Y](gumroad/countdown.js) - Super simple countdowns.
* [timeago.js ★2535](hustcc/timeago.js) - Simple library (less then 2kb) used to format date with `*** time ago` statement.
* [fecha ★993](taylorhakes/fecha) - Lightweight date formatting and parsing (~2KB). Meant to replace parsing and formatting functionality of moment.js.

## String
*String Libraries.*

* [selecting ★53 ⏳1Y](EvandroLG/selecting) - A library that allows you to access the text selected by the user
* [underscore.string ★3174](epeli/underscore.string) - String manipulation extensions for Underscore.js javascript library.
* [string.js ★1458](jprichardson/string.js) - Extra JavaScript string methods.
* [he ★1022](mathiasbynens/he) - A robust HTML entity encoder/decoder written in JavaScript.
* [multiline ★1416 ⏳1Y](sindresorhus/multiline) - Multiline strings in JavaScript.
* [query-string ★1011](sindresorhus/query-string) - Parse and stringify URL query strings.
* [URI.js ★4730](medialize/URI.js) - Javascript URL mutation library.
* [jsurl ★363](Mikhus/domurl) - Lightweight URL manipulation with JavaScript.
* [sprintf.js ★1404](alexei/sprintf.js) - A sprintf implementation.
* [url-pattern ★226](snd/url-pattern) - Easier than regex string matching patterns for urls and other strings. Turn strings into data or data into strings

## Number

* [Numeral-js ★5086](adamwdraper/Numeral-js) - A javascript library for formatting and manipulating numbers.
* [chance.js ★2478](chancejs/chancejs) - Random generator helper in Javascript. Can generate numbers, strings etc.
* [odometer ★5579](HubSpot/odometer) - Smoothly transitions numbers with ease.
* [accounting.js](https://github.com/josscrowcroft/accounting.js) - A lightweight JavaScript library for number, money and currency formatting - fully localisable, zero dependencies.
* [money.js](https://github.com/josscrowcroft/money.js) - A tiny (1kb) javascript currency conversion library, for web & nodeJS.
* [Fraction.js ★92](infusion/Fraction.js) - A rational number library for JavaScript
* [Complex.js ★89](infusion/Complex.js) - A complex number library for JavaScript
* [Polynomial.js ★31](infusion/Polynomial.js) - A polynomials library for JavaScript


## Storage

* [store.js ★9571](marcuswestin/store.js) - LocalStorage wrapper for all browsers without using cookies or flash. Uses localStorage, globalStorage, and userData behavior under the hood.
* [localForage](https://github.com/mozilla/localForage) - Offline storage, improved. Wraps IndexedDB, WebSQL, or localStorage using a simple but powerful API.
* [jStorage ★1479](andris9/jStorage) - jStorage is a simple key/value database to store data on browser side.
* [cross-storage ★931](zendesk/cross-storage) - Cross domain local storage, with permissions.
* [basket.js ★2937](addyosmani/basket.js) - A script and resource loader for caching & loading scripts with localStorage.
* [bag.js ★59](nodeca/bag.js) - A caching script and resource loader, similar to basket.js, but with additional k/v interface and localStorage / websql / indexedDB support.
* [basil.js ★1874](Wisembly/basil.js) - The missing Javascript smart persistent layer.
* [jquery-cookie ★8232](carhartl/jquery-cookie) - A simple, lightweight jQuery plugin for reading, writing and deleting cookies.
* [js-cookie ★6166](js-cookie/js-cookie) - A simple, lightweight JavaScript API for handling browser cookies
* [Cookies ★1634](ScottHamper/Cookies) - JavaScript Client-Side Cookie Manipulation Library.
* [DB.js] (https://github.com/aaronpowell/db.js/) - Promise based IndexDB Wrapper library
* [lawnchair.js] (https://github.com/brianleroux/lawnchair/) - Simple client-side JSON storage.
* [sql.js] (https://github.com/kripken/sql.js) - SQLite compiled to JavaScript through Emscripten.


## Color

* [randomColor ★4022](davidmerfield/randomColor) - A color generator for JavaScript.
* [chroma.js ★4200](gka/chroma.js) - JavaScript library for all kinds of color manipulations.
* [color ★1460](Qix-/color) - JavaScript color conversion and manipulation library.
* [colors ★7421](mrmrs/colors) - Smarter defaults for colors on the web.
* [PleaseJS ★2073](Fooidge/PleaseJS) - JavaScript Library for creating random pleasing colors and color schemes.
* [TinyColor ★1650](bgrins/TinyColor) - Fast, small color manipulation and conversion for JavaScript.
* [Vibrant.js] (https://github.com/jariz/vibrant.js/) - Extract prominent colors from an image.

## I18n And L10n
*Localization (l10n) and internationalization (i18n) JavaScript libraries.*

* [i18next ★2191](i18next/i18next) - internationalisation (i18n) with javascript the easy way.
* [polyglot ★2274](airbnb/polyglot.js) - tiny i18n helper library.
* [babelfish ★160 ⏳1Y](nodeca/babelfish) - i18n with human friendly API and built in plurals support.

## Class

* [ClassManager ★35](kogarashisan/ClassManager) - One of the fastest and most convenient class systems in the world
* [klass ★722 ⏳1Y](ded/klass) - A utility for creating expressive classes in JavaScript.
* [augment ★897 ⏳1Y](javascript/augment) - The world's smallest and fastest classical JavaScript inheritance pattern.


## Control Flow

* [async ★21343](caolan/async) - Async utilities for node and the browser.
* [q ★13298](kriskowal/q) - A tool for making and composing asynchronous promises in JavaScript.
* [step ★2120](creationix/step) - An async control-flow library that makes stepping through logic easy.
* [contra ★714 ⏳1Y](bevacqua/contra) - Asynchronous flow control with a functional taste to it.
* [Bluebird ★14650](petkaantonov/bluebird) - fully featured promise library with focus on innovative features and performance.
* [when ★3197](cujojs/when) - A solid, fast Promises/A+ and when() implementation, plus other async goodies.
* [ObjectEventTarget ★7 ⏳1Y](gartz/ObjectEventTarget) - Provide a prototype that add support to event listeners (with same behavior of EventTarget from DOMElements available on browsers).


## Routing

* [director ★4752](flatiron/director) - A tiny and isomorphic URL router for JavaScript.
* [page.js ★4842](visionmedia/page.js) - Micro client-side router inspired by the Express router (~1200 bytes).
* [pathjs ★1045](mtrpcic/pathjs) - Simple, lightweight routing for web browsers.
* [crossroads ★1366](millermedeiros/crossroads.js) - JavaScript Routes.
* [davis.js ★540](olivernn/davis.js) - RESTful degradable JavaScript routing using pushState.


## Security

* [DOMPurify ★1443](cure53/DOMPurify) - A DOM-only, super-fast, uber-tolerant XSS sanitizer for HTML, MathML and SVG.
* [js-xss ★1409](leizongmin/js-xss) - Sanitize untrusted HTML (to prevent XSS) with a configuration specified by a Whitelist.
* [xss-filters ★601](yahoo/xss-filters) - Secure XSS Filters by Yahoo


## Log

* [log ★2461](adamschwartz/log) - Console.log with style.
* [Conzole ★184 ⏳1Y](Oaxoa/Conzole) - A debug panel built in javascript that wraps javascript native console object methods and functionality in a panel displayed inside the page.
* [console.log-wrapper ★391](patik/console.log-wrapper) - Log to the console in any browser with clarity.
* [loglevel ★808](pimterry/loglevel) - Minimal lightweight logging for JavaScript, adding reliable log level methods to wrap any available console.log methods.
* [minilog](http://mixu.net/minilog/) – Lightweight client & server-side logging with Stream-API backends
* [storyboard](http://guigrpa.github.io/storyboard/) - Universal logging library + Chrome extension; it lets you see all client and server tasks triggered by a user action in a single place.

## RegExp
* [RegEx101](https://regex101.com/#javascript) - Online regex tester and debugger for JavaScript. Also supports Python, PHP and PCRE.
* [RegExr](http://regexr.com) - HTML/JS based tool for creating, testing, and learning about Regular Expressions.
* [RegExpBuilder ★1055 ⏳2Y](thebinarysearchtree/regexpbuilderjs) - Create regular expressions using chained methods.


## Voice Command

* [annyang ★4043](TalAter/annyang) - A JavaScript library for adding voice commands to your site, using speech recognition.
* [voix.js ★499](pazguille/voix) - A JavaScript library to add voice commands to your sites, apps or games.


## API

* [bottleneck ★264](SGrondin/bottleneck) - A powerful rate limiter that makes throttling easy.
* [oauth-signature-js ★185](bettiolo/oauth-signature-js) - JavaScript OAuth 1.0a signature generator for node and the browser.
* [amygdala ★398](lincolnloop/amygdala) - RESTful HTTP client for JavaScript powered web applications.
* [jquery.rest ★562](jpillora/jquery.rest) - A jQuery plugin for easy consumption of RESTful APIs.

## Streaming

* [Tailor ★352](zalando/tailor) - Streaming layout service for front-end microservices, inspired by Facebook's BigPipe.


## Vision Detection

* [tracking.js ★4964](eduardolundgren/tracking.js) - A modern approach for Computer Vision on the web.
* [ocrad.js ★2604](antimatter15/ocrad.js) - OCR in Javascript via Emscripten.


## Machine Learning

* [ConvNetJS ★7166](karpathy/convnetjs) - Deep Learning in Javascript. Train Convolutional Neural Networks (or ordinary ones) in your browser.
* [DN2A ★443](dn2a/dn2a-javascript) - Digital Neural Networks Architecture.
* [Brain.js ★7707](harthur/brain) - Neural networks in JavaScript.
* [Mind.js ★987](stevenmiller888/mind) - A flexible neural network library.
* [Synaptic.js ★4121](cazala/synaptic) - Architecture-free neural network library for node.js and the browser.


## Browser Detection

* [bowser](https://github.com/ded/bowser) - a browser detector

## Benchmark

* [benchmark.js ★2715](bestiejs/benchmark.js) - A benchmarking library. As used on jsPerf.com.
* [matcha ★435](logicalparadox/matcha) - A caffeine driven, simplistic approach to benchmarking.

## Code highlighting

* [Highlight.js ★9943](isagalaev/highlight.js) - Javascript syntax highlighter.
* [PrismJS ★4164](PrismJS/prism) - Lightweight, robust, elegant syntax highlighting.


## Loading Status
*Libraries for indicate load status.*

* [Mprogress.js ★1483](lightningtgc/MProgress.js) - Create Google Material Design progress linear bars.
* [NProgress](http://ricostacruz.com/nprogress/) - Slim progress bars for Ajax'y applications.
* [Spin.js ★8735](fgnass/spin.js) - A spinning activity indicator.
* [progress.js ★2224 ⏳1Y](usablica/progress.js) - Create and manage progress bar for every objects on the page.
* [progressbar.js ★5605](kimmobrunfeldt/progressbar.js) - Beautiful and responsive progress bars with animated SVG paths.
* [pace ★11956](HubSpot/pace) - Automatically add a progress bar to your site.
* [topbar ★130 ⏳2Y](buunguyen/topbar) - Tiny & beautiful site-wide progress indicator.
* [nanobar ★2409](jacoborus/nanobar) - Very lightweight progress bars. No jQuery.
* [PageLoadingEffects ★546 ⏳3Y](codrops/PageLoadingEffects) - Modern ways of revealing new content using SVG animations.
* [SpinKit ★13233](tobiasahlin/SpinKit) - A collection of loading indicators animated with CSS.
* [Ladda ★6880](hakimel/Ladda) - Buttons with built-in loading indicators.
* [css-loaders ★4882](lukehaas/css-loaders) - A collection of loading spinners animated with CSS

Besides libraries, there're [Collection on Codepen](http://codepen.io/collection/HtAne/), and generators like [Ajaxload](http://www.ajaxload.info/), [Preloaders](http://preloaders.net/) and [CSSLoad](http://cssload.net/).


## Validation

* [Parsley.js ★7867](guillaumepotier/Parsley.js) - Validate your forms, frontend, without writing a single line of javascript.
* [jquery-validation](https://github.com/jzaefferer/jquery-validation) - jQuery Validation Plugin.
* [validator.js ★7798](chriso/validator.js) - String validation and sanitization.
* [validate.js ★2097](rickharrison/validate.js) - Lightweight JavaScript form validation library inspired by CodeIgniter.
* [validatr ★277](jaymorrow/validatr) - Cross Browser HTML5 Form Validation.
* [FormValidation](http://formvalidation.io/) - The best jQuery plugin to validate form fields. Formerly BootstrapValidator.
* [is.js ★7831](arasatasaygin/is.js) -  Check types, regexps, presence, time and more.
* [FieldVal ★135](FieldVal/fieldval-js) - multipurpose validation library. Supports both sync and async validation.


## Keyboard Wrappers

* [mousetrap ★7775](ccampbell/mousetrap) - Simple library for handling keyboard shortcuts in Javascript.
* [keymaster ★5722](madrobby/keymaster) - A simple micro-library for defining and dispatching keyboard shortcuts.
* [Keypress ★3034](dmauro/Keypress) - A keyboard input capturing utility in which any key can be a modifier key.
* [KeyboardJS ★1290](RobertWHurst/KeyboardJS) - A JavaScript library for binding keyboard combos without the pain of key codes and key combo conflicts.
* [jquery.hotkeys ★2418](jeresig/jquery.hotkeys) - jQuery Hotkeys lets you watch for keyboard events anywhere in your code supporting almost any key combination.
* [jwerty ★1183](keithamus/jwerty) - Awesome handling of keyboard events.


## Tours And Guides

* [intro.js ★15276](usablica/intro.js) - A better way for new feature introduction and step-by-step users guide for your website and project.
* [shepherd ★4910](HubSpot/shepherd) - Guide your users through a tour of your app.
* [bootstrap-tour ★3844](sorich87/bootstrap-tour) - Quick and easy product tours with Twitter Bootstrap Popovers.
* [tourist ★1192 ⏳1Y](easelinc/tourist) - Simple, flexible tours for your app.
* [chardin.js ★4569](heelhook/chardin.js) - Simple overlay instructions for your apps.
* [pageguide ★858](tracelytics/pageguide) - An interactive guide for web page elements using jQuery and CSS3.
* [hopscotch ★3688](linkedin/hopscotch) - A framework to make it easy for developers to add product tours to their pages.
* [joyride ★1336](zurb/joyride) - jQuery feature tour plugin.
* [focusable ★1072 ⏳1Y](zzarcon/focusable) - Set a spotlight focus on DOM element adding a overlay layer to the rest of the page.

## Notifications

* [messenger ★3908](HubSpot/messenger) - Growl-style alerts and messages for your app.
* [noty ★5134](needim/noty) - jQuery notification plugin.
* [pnotify ★2926](sciactive/pnotify) - JavaScript notifications for Bootstrap, jQuery UI, and the Web Notifications Draft.
* [toastr ★6705](CodeSeven/toastr) - Simple javascript toast notifications.
* [humane-js ★2055](wavded/humane-js) - A simple, modern, browser notification system.
* [smoke.js ★942](hxgf/smoke.js) - Framework-agnostic styled alert system for javascript.
* [notie ★5424](jaredreich/notie) - Simple notifications and inputs with no dependencies.


## Sliders

* [Swiper ★12354](nolimits4web/Swiper) - Mobile touch slider and framework with hardware accelerated transitions.
* [slick ★18371](kenwheeler/slick) - The last carousel you'll ever need.
* [slidesJs](http://www.slidesjs.com) - Is a ressponsive slideshow plug-in for JQuery(1.7.1+) with features like touch and CSS3 transitions
* [FlexSlider](https://github.com/woothemes/FlexSlider) - An awesome, fully responsive jQuery slider plugin.
* [unslider ★3984](idiot/unslider) - The simplest jQuery slider there is.
* [sly ★2721](darsain/sly) - JavaScript library for one-directional scrolling with item based navigation support.
* [vegas ★1534](jaysalvat/vegas) - A jQuery plugin to add beautiful fullscreen backgrounds to your webpages. It even allows Slideshows.
* [Sequence ★3274 ⏳1Y](IanLunn/Sequence) - CSS animation framework for creating responsive sliders, presentations, banners, and other step-based applications.
* [reveal.js ★34726](hakimel/reveal.js) - A framework for easily creating beautiful presentations using HTML.
* [impress.js ★31610](impress/impress.js) - It's a presentation framework based on the power of CSS3 transforms and transitions in modern browsers and inspired by the idea behind prezi.com.
* [bespoke.js ★4163](bespokejs/bespoke) - DIY Presentation Micro-Framework
* [Strut ★1402](tantaman/Strut) - Strut - An Impress.js and Bespoke.js Presentation Editor
* [PhotoSwipe ★13986](dimsemenov/PhotoSwipe) - JavaScript image gallery for mobile and desktop, modular, framework independent.
* [jcSlider ★33 ⏳1Y](JoanClaret/jcSlider) - A responsive slider jQuery plugin with CSS animations.
* [basic-jquery-slider ★575 ⏳1Y](jcobb/basic-jquery-slider) - Simple to use, simple to theme, simple to customise.
* [jQuery.adaptive-slider ★49 ⏳3Y](creative-punch/jQuery.adaptive-slider) - A jQuery plugin for a slider with adaptive colored figcaption and navigation.
* [slidr ★1490 ⏳1Y](bchanx/slidr) - add some slide effects.
* [Flickity ★3731](metafizzy/flickity) - Touch, responsive, flickable galleries.
* [Glide.js ★1593](jedrzejchalubek/glidejs) - Responsive and touch-friendly jQuery slider. It's simple, lightweight and fast.
* [jQuery.adaptive-slider ★49 ⏳3Y](creative-punch/jQuery.adaptive-slider) - A jQuery plugin for a slider with adaptive colored figcaption and navigation.

## Range Sliders

* [Ion.RangeSlider ★1593](IonDen/ion.rangeSlider) - Powerful and easily customizable range slider with many options and skin support.
* [jQRangeSlider ★673](ghusse/jQRangeSlider) - A javascript slider selector that supports dates.
* [noUiSlider ★2807](leongersen/noUiSlider) - A lightweight, highly customizable range slider without bloat.
* [rangeslider.js ★1474](andreruffert/rangeslider.js) - HTML5 input range slider element polyfill.


## Form Widgets

### Input

* [typeahead.js ★14211](twitter/typeahead.js) - A fast and fully-featured autocomplete library.
* [tag-it ★2297](aehlke/tag-it) - A jQuery UI plugin to handle multi-tag fields as well as tag suggestions/autocomplete.
* [At.js ★4452](ichord/At.js) - Add Github like mentions autocomplete to your application.
* [Placeholders.js ★924](jamesallardice/Placeholders.js) - A JavaScript polyfill for the HTML5 placeholder attribute.
* [fancyInput ★1900](yairEO/fancyInput) - Makes typing in input fields fun with CSS3 effects.
* [jQuery-Tags-Input ★1995](xoxco/jQuery-Tags-Input) - Magically convert a simple text input into a cool tag list with this jQuery plugin.
* [vanilla-masker](https://github.com/BankFacil/vanilla-masker) - A pure javascript mask input.
* [Ion.CheckRadio ★65 ⏳1Y](IonDen/ion.checkRadio) - jQuery plugin for styling checkboxes and radio-buttons. With skin support.
* [awesomplete ★5458](LeaVerou/awesomplete) - Ultra lightweight, usable, beautiful autocomplete with zero dependencies. - http://leaverou.github.io/awesomplete/

### Calendar

* [pickadate.js ★6873](amsul/pickadate.js) - The mobile-friendly, responsive, and lightweight jQuery date & time input picker.
* [bootstrap-datepicker](https://github.com/eternicode/bootstrap-datepicker) - A datepicker for @twitter bootstrap forked from Stefan Petre's (of eyecon.ro), improvements by @eternicode.
* [Pikaday ★5245](dbushell/Pikaday) - A refreshing JavaScript Datepicker — lightweight, no dependencies, modular CSS.
* [fullcalendar ★6745](fullcalendar/fullcalendar) - Full-sized drag & drop event calendar (jQuery plugin).
* [rome ★2678](bevacqua/rome) - A customizable date (and time) picker. Dependency free, opt-in UI.
* [datedropper ★1695](felicegattuso/datedropper) -  datedropper is a jQuery plugin that provides a quick and easy way to manage dates for input fields.


### Select

* [selectize.js ★19](brianreavis/selectize.js) - Selectize is the hybrid of a textbox and select box. It's jQuery based and it has autocomplete and native-feeling keyboard navigation; useful for tagging, contact lists, etc.
* [select2 ★20332](select2/select2) - a jQuery based replacement for select boxes. It supports searching, remote data sets, and infinite scrolling of results.
* [chosen ★20783](harvesthq/chosen) - A library for making long, unwieldy select boxes more friendly.

### File Uploader

* [jQuery-File-Upload ★26749](blueimp/jQuery-File-Upload) - File Upload widget with multiple file selection, drag&amp;drop support, progress bar, validation and preview images, audio and video for jQuery.
* [dropzone ★12392](enyo/dropzone) - Dropzone is an easy to use drag'n'drop library. It supports image previews and shows nice progress bars.
* [flow.js ★2269](flowjs/flow.js) - A JavaScript library providing multiple simultaneous, stable, fault-tolerant and resumable/restartable file uploads via the HTML5 File API.
* [fine-uploader ★6937](FineUploader/fine-uploader) - Multiple file upload plugin with progress-bar, drag-and-drop, direct-to-S3 uploading.
* [FileAPI ★3039](mailru/FileAPI) - A set of javascript tools for working with files. Multiupload, drag'n'drop and chunked file upload. Images: crop, resize and auto orientation by EXIF.
* [plupload ★4349](moxiecode/plupload) - A JavaScript API for dealing with file uploads it supports features like multiple file selection, file type filtering, request chunking, client side image scaling and it uses different runtimes to achieve this such as HTML 5, Silverlight and Flash.

### Other

* [form](https://github.com/malsup/form) - jQuery Form Plugin.
* [Garlic.js ★2172](guillaumepotier/Garlic.js) - Automatically persist your forms' text and select field values locally, until the form is submitted.
* [Countable ★1454](RadLikeWhoa/Countable) - A JavaScript function to add live paragraph-, word- and character-counting to an HTML element.
* [card ★8704](jessepollak/card) - Make your credit card form better in one line of code.
* [stretchy ★1144](LeaVerou/stretchy) - Form element autosizing, the way it should be.


## Tips

* [tipsy ★2045](jaz303/tipsy) - Facebook-style tooltips plugin for jQuery.
* [opentip ★1238 ⏳1Y](enyo/opentip) - An open source javascript tooltip based on the prototype framework.
* [qTip2 ★1963](qTip2/qTip2) - Pretty powerful tooltips.
* [tooltipster ★2261](iamceege/tooltipster) - A jQuery tooltip plugin.
* [simptip ★626](arashmanteghi/simptip) - A simple CSS tooltip made with Sass.
* [jquery-popup-overlay ★396](vast-engineering/jquery-popup-overlay) - jQuery plugin for responsive and accessible modal windows and tooltips.
* [toolbar ★2321](paulkinzett/toolbar) - A tooltip style toolbar jQuery plugin
* [hint.css ★7351](chinchang/hint.css) - A tooltip library in CSS for your lovely websites.

## Modals and Popups

* [Magnific-Popup ★9373](dimsemenov/Magnific-Popup) - Light and responsive lightbox script with focus on performance.
* [jquery-popbox ★452](gristmill/jquery-popbox) - jQuery PopBox UI Element.
* [jquery.avgrund.js ★1824 ⏳1Y](voronianski/jquery.avgrund.js) - A jQuery plugin with new modal concept for popups.
* [vex ★6108](HubSpot/vex) - A modern dialog library which is highly configurable and easy to style.
* [bootstrap-modal ★5026 ⏳1Y](jschr/bootstrap-modal) - Extends the default Bootstrap Modal class. Responsive, stackable, ajax and more.
* [css-modal ★1669](drublic/css-modal) - A modal built out of pure CSS.
* [jquery-popup-overlay ★396](vast-engineering/jquery-popup-overlay) - jQuery plugin for responsive and accessible modal windows and tooltips.
* [SweetAlert ★15904](t4t5/sweetalert) - An awesome replacement for JavaScript's alert.
* [baguetteBox.js ★1226](feimosi/baguetteBox.js) - Simple and easy to use lightbox script written in pure JavaScript.
* [colorbox ★4631](jackmoore/colorbox) - A light-weight, customizable lightbox plugin for jQuery.
* [fancyBox ★4520](fancyapps/fancyBox) - A tool that offers a nice and elegant way to add zooming functionality for images, html content and multi-media on your webpages.
* [swipebox ★1787](brutaldesign/swipebox) - A touchable jQuery lightbox
* [jBox ★831](StephanWagner/jBox) - jBox is a powerful and flexible jQuery plugin, taking care of all your popup windows, tooltips, notices and more.

## Scroll

* [scrollMonitor ★2188](stutrek/scrollMonitor) - A simple and fast API to monitor elements as you scroll.
* [headroom ★9163](WickyNilliams/headroom.js) - Give your pages some headroom. Hide your header until you need it.
* [onepage-scroll ★9048](peachananr/onepage-scroll) - Create an Apple-like one page scroller website (iPhone 5S website) with One Page Scroll plugin.
* [iscroll ★9503](cubiq/iscroll) - iScroll is a high performance, small footprint, dependency free, multi-platform javascript scroller.
* [skrollr ★17070](Prinzhorn/skrollr) - Stand-alone parallax scrolling library for mobile (Android + iOS) and desktop. No jQuery.
* [parallax ★11460](wagerfield/parallax) - Parallax Engine that reacts to the orientation of a smart device.
* [stellar.js ★4204](markdalgleish/stellar.js) - Parallax scrolling made easy.
* [plax ★2314](cameronmcefee/plax) - jQuery powered parallaxing.
* [jparallax ★1118 ⏳1Y](stephband/jparallax) - jQuery plugin for creating interactive parallax effect.
* [fullPage ★19189](alvarotrigo/fullPage.js) - A simple and easy to use plugin to create fullscreen scrolling websites (also known as single page websites).
* [ScrollMenu ★164](s-yadav/ScrollMenu) - A new interface to replace old boring scrollbar.
* [Clusterize.js ★5139](NeXTs/Clusterize.js) - Tiny vanilla JS plugin to display large data sets easily.


## Menu

* [jQuery-menu-aim ★7466](kamens/jQuery-menu-aim) - jQuery plugin to fire events when user's cursor aims at particular dropdown menu items. For making responsive mega dropdowns like Amazon's.
* [jQuery contextMenu] (https://github.com/swisnl/jQuery-contextMenu) -  contextMenu manager.
* [Slideout ★6583](mango/slideout) - A responsive touch slideout navigation menu for mobile web apps.
* [Slide and swipe ★77](JoanClaret/slide-and-swipe-menu) - A sliding swipe menu that works with touchSwipe library.


## Table/Grid

* [jTable ★804](hikalkan/jtable) - A jQuery plugin to create AJAX based CRUD tables.
* [DataTables](https://www.datatables.net/) - (jQuery plug-in) It is a highly flexible tool, based upon the foundations of progressive enhancement, and will add advanced interaction controls to any HTML table.
* [floatThead ★839](mkoryak/floatThead) - (jQuery plug-in) lock any table's header while scrolling within the body. Works on any table and requires no custom html or css.
* [Masonry](http://masonry.desandro.com/) - A cascading grid layout library.
* [Packery](http://packery.metafizzy.co/) - A grid layout library that uses a bin-packing algorithm. Useable for draggable layouts.
* [Isotope](http://isotope.metafizzy.co/) - A filterable, sortable, grid layout library. Can implement Masonry, Packery, and other layouts.
* [flexboxgrid ★5989](kristoferjoseph/flexboxgrid) - Grid based on CSS3 flexbox

## Frameworks

* [Semantic UI](http://semantic-ui.com/) - UI Kit with lots of themes and elements
* [w2ui](http://w2ui.com/) - A set of jQuery plugins for front-end development of data-driven web applications.
* [fluidity ★1109](mrmrs/fluidity) - The worlds smallest fully-responsive css framework
* [Ink ★1895](sapo/Ink) - An HTML5/CSS3 framework used at SAPO for fast and efficient website design and prototyping

## Boilerplates

 * [html5-boilerplate ★37420](h5bp/html5-boilerplate) - A professional front-end template for building fast, robust, and adaptable web apps or sites.
 * [mobile-boilerplate ★4023 ⏳1Y](h5bp/mobile-boilerplate) - A front-end template that helps you build fast, modern mobile web apps.
 * [webplate ★584](chrishumboldt/webplate) - An awesome front-end framework that lets you stay focused on building your site or app while remaining really easy to use.
 * [Cerberus ★2199](TedGoas/Cerberus) - A few simple, but solid patterns for responsive HTML emails. Even in Outlook.
 * [full-page-intro-and-navigation ★28 ⏳2Y](CodyHouse/full-page-intro-and-navigation) - An intro page with a full width background image, a bold animated menu and an iOS-like blurred effect behind the navigation
 * [Fluid-Squares ★25 ⏳2Y](crozynski/Fluid-Squares) - A fluid grid of square units.
 * [Mobile-First-RWD ★53 ⏳4Y](bradfrost/Mobile-First-RWD) - An example of a mobile-first responsive web design
 * [this-is-responsive ★1472](bradfrost/this-is-responsive) - This Is Responsive
 * [npm run-scripts](https://gist.github.com/addyosmani/9f10c555e32a8d06ddb0) Task automation with NPM run-scripts.

## Gesture

* [hammer.js ★16305](hammerjs/hammer.js) - A javascript library for multi-touch gestures.
* [touchemulator ★160](hammerjs/touchemulator) - Emulate touch input on your desktop.
* [Dragula] (https://github.com/bevacqua/dragula/) - Drag and drop so simple it hurts


## Maps

* [Leaflet ★18499](Leaflet/Leaflet) - JavaScript library for mobile-friendly interactive maps.
* [Cesium ★2215](AnalyticalGraphicsInc/cesium) - Open Source WebGL virtual globe and map engine.
* [gmaps ★6674](HPNeo/gmaps) - The easiest way to use Google Maps.
* [polymaps ★1445 ⏳2Y](simplegeo/polymaps) - A free JavaScript library for making dynamic, interactive maps in modern web browsers.
* [kartograph.js ★1486](kartograph/kartograph.js) - Open source JavaScript renderer for Kartograph SVG maps.
* [mapbox.js ★1429](mapbox/mapbox.js) - Mapbox JavaScript API, a Leaflet Plugin.
* [jqvmap ★1443](manifestinteractive/jqvmap) - jQuery Vector Map Library.
* [OpenLayers3](http://openlayers.org/) - A high-performance, feature-packed library for all your mapping needs.

## Video/Audio

 * [prettyembed.js ★1053](mike-zarandona/prettyembed.js) - Prettier embeds for your YouTubes - with nice options like high-res preview images, advanced customization of embed options, and optional FitVids support.
 * [html5media ★941](etianen/html5media) -  Enables <video> and <audio> tags in all major browsers. <https://html5media.info/>
 * [Play-em JS ★40](adrienjoly/playemjs) -  Play'em is a javascript component that manages a music/video track queue and plays a sequence of songs by embedding several players in a HTML DIV including Youtube, Soundcloud and Vimeo.
 * [polyplayer ★31 ⏳2Y](Acconut/polyplayer) - Rule YouTube, Soundcloud and Vimeo player with one API
 * [flowplayer ★1448](flowplayer/flowplayer) -  The HTML5 video player for the web
 <https://flowplayer.org/>
 * [mediaelement](https://github.com/johndyer/mediaelement) -  HTML5 <audio> or <video> player with Flash and Silverlight shims that mimics the HTML5 MediaElement API, enabling a consistent UI in all browsers. <http://mediaelementjs.com/>
 * [SoundJS ★2353](CreateJS/SoundJS) - A library to make working with audio on the web easier. It provides a consistent API for playing audio in different browsers.
 * [video.js ★16404](videojs/video.js) - Video.js - open source HTML5 & Flash video player
 * [FitVids.js ★4493](davatron5000/FitVids.js) - A lightweight, easy-to-use jQuery plugin for fluid width video embeds.
 * [Ion.Sound ★592](IonDen/ion.sound) - Simple sounds on any web page
 * [photobooth-js ★582](WolframHempel/photobooth-js) - A widget that allows users to take their avatar pictures on your site
 * [clappr ★3542](clappr/clappr) - An extensible media player for the web http://clappr.io

## Typography

 * [FlowType.JS ★4387](simplefocus/FlowType.JS) - Web typography at its finest: font-size and line-height based on element width.
 * [BigText ★818](zachleat/BigText) - jQuery plugin, calculates the font-size and word-spacing needed to match a line of text to a specific width.
 * [circletype ★301](peterhry/circletype) - A jQuery plugin that lets you curve type on the web
 * [slabText ★1323](freqDec/slabText) - A jQuery plugin for producing big, bold & responsive headlines
 * [simple-text-rotator ★646](peachananr/simple-text-rotator) - Add a super simple rotating text to your website with little to no markup
 * [novacancy.js ★132](chuckyglitch/novacancy.js) - Text Neon Golden effect jQuery plug-in.
 * [jquery-responsive-text ★119 ⏳2Y](ghepting/jquery-responsive-text) - Make your text sizing responsive!
 * [FitText.js ★6316](davatron5000/FitText.js) - A jQuery plugin for inflating web type
 * [Lettering.js ★4819](davatron5000/Lettering.js) - A lightweight, easy to use Javascript `<span>` injector for radical Web Typography


## Animations

* [velocity ★12915](julianshapiro/velocity) - Accelerated JavaScript animation.
* [jquery.transit ★7312](rstacruz/jquery.transit) - Super-smooth CSS3 transformations and transitions for jQuery.
* [imrpess.js ★31610](impress/impress.js) - Make Prezi-like presentations with CSS3 transformations/transitions in an HTML document.
* [bounce.js ★5002 ⏳1Y](tictail/bounce.js) - Create tasty CSS3 powered animations in no time.
* [GreenSock-JS ★6148](greensock/GreenSock-JS) - High-performance HTML5 animations that work in all major browsers.
* [TransitionEnd ★85](EvandroLG/transitionEnd) - TransitionEnd is an agnostic and cross-browser library to work with transitionend event.
* [Dynamic.js ★6301](michaelvillar/dynamics.js) - Javascript library to create physics-based CSS animations.
* [the-cube ★6 ⏳4Y](pstadler/the-cube) - The Cube is an experiment with CSS3 transitions.
* [Effeckt.css ★10968 ⏳1Y](h5bp/Effeckt.css) - A Performant Transitions and Animations Library
* [animate.css ★42134](daneden/animate.css) - A cross-browser library of CSS animations. As easy to use as an easy thing.
* [textillate ★2970](jschr/textillate) - A simple plugin for CSS3 text animations
* [move.js ★4031](visionmedia/move.js) - CSS3 backed JavaScript animation framework
* [animatable ★2271 ⏳1Y](LeaVerou/animatable) - One property, two values, endless possiblities
* [shuffle-images ★173 ⏳1Y](peachananr/shuffle-images) -  The Simplest Way to shuffle through images in a Creative Way http://www.thepetedesign.com/demos/shuffle-images_demo.html
* [smoothState.js ★3988](miguel-perez/smoothState.js) - Unobtrusive page transitions with jQuery. http://smoothstate.com/

## Image Processing

* [lena.js ★114](davidsonfellipe/lena.js) - A Library for image processing with filters and util functions.
* [pica ★715](nodeca/pica) - High quality image resize (with fast Lanczos filter, implemented in pure JS).
* [cropper ★5365](fengyuanchen/cropper) - A simple jQuery image cropping plugin.


## ES6

* [es6features ★20243](lukehoban/es6features) - Overview of ECMAScript 6 features.
* [es6-features ★3479](rse/es6-features) - ECMAScript 6: Feature Overview & Comparison.
* [es6-cheatsheet ★9590](DrkSephy/es6-cheatsheet) - ES2015 [ES6] cheatsheet containing tips, tricks, best practices and code snippets.
* [ECMAScript 6 compatibility table](http://kangax.github.io/compat-table/es6/) - Compatibility tables for all ECMAScript 6 features on a variety of environments.
* [Babel (Formerly 6to5) ★21180](babel/babel) - Turn ES6+ code into vanilla ES5 with no runtime.
* [Traceur compiler ★7280](google/traceur-compiler) - ES6 features > ES5. Includes classes, generators, promises, destructuring patterns, default parameters & more.


## SDK

* [javascript-sdk-design](https://github.com/huei90/javascript-sdk-design) - Javascript SDK design guide extracted from work and personal experience
* [Spotify SDK ★128](loverajoel/spotify-sdk) - Entity oriented SDK to work with the Spotify Web API.


## Misc

* [echo ★3318](toddmotto/echo) - Lazy-loading images with data-* attributes.
* [picturefill ★9140](scottjehl/picturefill) - A responsive image polyfill for &lt;picture&gt;, srcset, sizes.
* [platform.js ★1543](bestiejs/platform.js) - A platform detection library that works on nearly all JavaScript platforms.
* [json3 ★946](bestiejs/json3) - A modern JSON implementation compatible with nearly all JavaScript platforms.
* [Logical Or Not](http://gabinaureche.com/logicalornot/) - A game about JavaScript specificities.
* [BitSet.js ★119](infusion/BitSet.js) - A JavaScript Bit-Vector implementation
* [spoiler-alert ★475](joshbuddy/spoiler-alert) - SPOILER ALERT! A happy little jquery plugin to hide spoilers on your site.
* [jquery.vibrate.js ★130 ⏳1Y](illyism/jquery.vibrate.js) - Vibration API Wrappers
* [list.js ★7950](javve/list.js) -  Adds search, sort, filters and flexibility to tables, lists and various HTML elements. Built to be invisible and work on existing HTML.
http://www.listjs.com
* [mixitup ★3772](patrickkunka/mixitup) - MixItUp - A Filter & Sort Plugin
* [grid ★3209](hootsuite/grid) - Drag and drop library for two-dimensional, resizable and responsive lists.
* [jquery-match-height ★2528](liabru/jquery-match-height) - a responsive equal heights plugin for jQuery.
* [survey.js ★491](surveyjs/surveyjs) - JavaScript Survey Engine. It uses JSON for survey metadata and results. http://surveyjs.org/

## Podcasts
* [JavaScript Air](https://javascriptair.com/) - The live video broadcast podcast all about JavaScript and the Web platform.
* [Web of Tomorrow](http://www.weboftomorrowpodcast.com/) - Podcast about JavaScript for beginners.
* [Javascript Jabber](https://devchat.tv/js-jabber) - A weekly podcast about JavaScript, including Node.js, Front-End Technologies, Careers, Teams and more.

# Worth Reading
* [braziljs/js-the-right-way ★6380](braziljs/js-the-right-way)
* [JSbooks ★1912](revolunet/JSbooks)
* [Superhero.js](http://superherojs.com) - A collection of resources about creating, testing and maintaining a large JavaScript code base.
* [SJSJ ★1994](HugoGiraudel/SJSJ) - Simplified JavaScript Jargon is a community-driven attempt at explaining the loads of buzzwords making the current JavaScript ecosystem in a few simple words.
* [How to Write an Open Source JavaScript Library ★78](sarbbottam/write-an-open-source-js-lib) - A comprehensive guide through a set of steps to publish a JavaScript open source library.


# Other Awesome Lists
* [sotayamashita/awesome-css ★962](sotayamashita/awesome-css)
* [emijrp/awesome-awesome ★790](emijrp/awesome-awesome)
* [bayandin/awesome-awesomeness ★18868](bayandin/awesome-awesomeness)
* [sindresorhus/awesome ★59088](sindresorhus/awesome)
* [jnv/list ★4263](jnv/lists)
* [gianarb/angularjs ★2129](gianarb/awesome-angularjs)
* [peterkokot/awesome-dojo](https://github.com/peterkokot/awesome-dojo)
* [addyosmani/es6-tools ★3430](addyosmani/es6-tools)
* [ericdouglas/ES6-Learning ★3815](ericdouglas/ES6-Learning)
* [obetomuniz/awesome-webcomponents ★119](obetomuniz/awesome-webcomponents)
* [willianjusten/awesome-svg ★3201](willianjusten/awesome-svg)
* [davidsonfellipe/awesome-wpo ★5787](davidsonfellipe/awesome-wpo)
* [instanceofpro/awesome-backbone ★362](sadcitizen/awesome-backbone)
* [enaqx/awesome-react ★19630](enaqx/awesome-react)
* [bolshchikov/js-must-watch ★11196](bolshchikov/js-must-watch)
* [peterkokot/awesome-jquery](https://github.com/peterkokot/awesome-jquery)
* [dinbror/you-might-not-need-jquery-plugins ★8 ⏳1Y](dinbror/you-might-not-need-jquery-plugins)
* [MaximAbramchuck/awesome-interviews ★14930](MaximAbramchuck/awesome-interview-questions)


# Contributing

Contributions welcome! Read the [contribution guidelines](https://github.com/sorrycc/awesome-javascript/blob/master/CONTRIBUTING.md) first.


# License

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [chencheng](https://github.com/sorrycc) has waived all copyright and related or neighboring rights to this work.
---
<p align="center">
	This list is a copy of <a href="sorrycc/awesome-javascript">sorrycc/awesome-javascript</a> with ranks
</p>
