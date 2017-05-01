# Awesome Gulp [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg) ★57421](https://github.com/sindresorhus/awesome)

> A curated list of awesome [gulp ★26112](https://github.com/gulpjs/gulp) resources, plugins, and boilerplates for a better development workflow automation.

*Looking for something else? Take a look at other [awesome lists ★57421](https://github.com/sindresorhus/awesome).*

## Contribution
:octocat: All contributions welcome. Feel free to contribute ([guidelines](contributing.md)).

## Contents
- [Legend](#legend)
- [Resources](#resources)
  - [General Resources](#general-resources)
  - [Official Documentation](#official-documentation)
  - [Community](#community)
  - [Tutorials](#tutorials)
    - [Gulp Tutorials](#gulp-tutorials)
    - [Gulp 4 Tutorials](#gulp-4-tutorials)
    - [Gulp with Browserify](#gulp-with-browserify)
    - [Gulp with Angular](#gulp-with-browserify)
    - [Gulp with Angular and Browserify](#gulp-with-angular-and-browserify)
    - [Gulp with Angular and Webpack](#gulp-with-angular-and-webpack)
    - [Gulp with React and Browserify](#gulp-with-react-and-browserify)
    - [Gulp with Ember](#gulp-with-ember)
  - [Miscellaneous Resources](#miscellaneous-resources)
- [Plugins](#plugins)
  - [Compilation](#compilation)
  - [Transpilation](#transpilation)
  - [Concatenation](#concatenation)
  - [Minification](#minification)
  - [Optimization](#optimization)
  - [Injecting Assets](#injecting-assets)
  - [Templating](#templating)
  - [Linting](#linting)
  - [Live Reload](#live-reload)
  - [Caching](#caching)
  - [Flow Control](#flow-control)
  - [Logging](#logging)
  - [Testing](#testing)
  - [Miscellaneous Plugins](#miscellaneous-plugins)
- [Scaffolding](#scaffolding)
  - [Boilerplates](#boilerplates)
  - [Yeoman Generators](#yeoman-generators)
- [Miscellaneous](#miscellaneous)

## Legend
[:no_entry:] - A deprecation notice;

## Resources
### General Resources
* [Official Website](http://gulpjs.com/)
* [Github Repository ★26112](https://github.com/gulpjs/gulp)
* [Plugin Registry](http://gulpjs.com/plugins/)
* [NPM Module](https://www.npmjs.com/package/gulp)
* [Blacklisted Plugins](https://github.com/gulpjs/plugins/blob/master/src/blackList.json)

### Official Documentation
* [Getting Started](https://github.com/gulpjs/gulp/blob/master/docs/getting-started.md)
* [API Documentation](https://github.com/gulpjs/gulp/blob/master/docs/API.md)
* [CLI Documentation](https://github.com/gulpjs/gulp/tree/master/docs#articles)
* [Writing a Plugin](https://github.com/gulpjs/gulp/blob/master/docs/writing-a-plugin/README.md)
* [Recipes](https://github.com/gulpjs/gulp/tree/master/docs/recipes)

### Community
* [StackOverflow](http://stackoverflow.com/questions/tagged/gulp)
* [Twitter](https://twitter.com/gulpjs)

### Tutorials
#### Gulp Tutorials
* [Building with Gulp](https://www.smashingmagazine.com/2014/06/building-with-gulp/)
* [Automate Your Tasks Easily with Gulp.js](https://scotch.io/tutorials/automate-your-tasks-easily-with-gulp-js)
* [Gulp - The Vision, History, and Future of the Project](https://medium.com/@contrahacks/gulp-3828e8126466)
* [Introduction to Gulp.js](http://stefanimhoff.de/tag/gulp/)
* [Video: Learning Gulp](http://leveluptuts.com/tutorials/learning-gulp)
* [Using Gulp to Inject Scripts and Styles Tags Directly into Your HTML](http://blog.johnnyreilly.com/2015/02/using-gulp-in-asp-net-instead-of-web-optimization.html)
* [5 Lessons Learned Using Gulp.js](http://denbuzze.com/post/5-lessons-learned-using-gulpjs/)
* [Automating Linkage: How I Learned to Stop Worrying and Love the Build](http://conan.is/bower/gulp/wiredep/javascript/2014/08/18/automating_linkage-or-how-i-learned-to-stop-worrying-and-love-the-build.html)
* [Setting Up Gulp Tasks for the First Time](https://www.codementor.io/development-process/tutorial/how-to-set-up-gulp-beginner-guide#/)
* [Why You Shouldn’t Create a Gulp Plugin (or, How to Stop Worrying and Learn to Love Existing Node Packages)](http://blog.overzealous.com/post/74121048393/why-you-shouldnt-create-a-gulp-plugin-or-how-to)
* [6 Gulp Best Practices You Can Use Today to Radically Improve Your Development Experience](http://blog.rangle.io/angular-gulp-bestpractices/)
* [Gulp for Beginners](https://css-tricks.com/gulp-for-beginners/)

#### Gulp 4 Tutorials
* [Migrating to Gulp 4 by Example](https://blog.wearewizards.io/migrating-to-gulp-4-by-example)
* [Gulp 4: The new task execution system - gulp.parallel and gulp.series](http://fettblog.eu/gulp-4-parallel-and-series/)

#### Gulp with Browserify
* [Gulp + Browserify, the Gulp-y Way](https://medium.com/@sogko/gulp-browserify-the-gulp-y-way-bb359b3f9623)
* [Gulp + Browserify](https://viget.com/extend/gulp-browserify-starter-faq)
* [Fast Browserify Builds with Watchify](https://github.com/gulpjs/gulp/blob/master/docs/recipes/fast-browserify-builds-with-watchify.md)

#### Gulp with Angular
* [What Every Angular Project Likely Needs - and a Gulp Build to Provide It](http://blog.jhades.org/what-every-angular-project-likely-needs-and-a-gulp-build-to-provide-it/)

#### Gulp with Angular and Browserify
* [Advanced AngularJS Structure with Gulp, Node and Browserify](http://omarfouad.com/blog/2015/03/21/advanced-angularjs-structure-with-gulp-node-and-browserify/)

#### Gulp with Angular and Webpack
* [Angular, Webpack and Gulp for an SPA: Part I](https://luwenhuang.wordpress.com/2015/01/18/refactoring-an-angular-app-to-use-webpack-and-gulp/)
* [Angular, Webpack and Gulp for an SPA: Part II](https://luwenhuang.wordpress.com/2015/01/19/angular-webpack-and-gulp-for-an-spa-part-ii/)
* [Angular, Webpack and Gulp for an SPA: Part III](https://luwenhuang.wordpress.com/2015/01/28/angular-webpack-and-gulp-for-an-spa-part-iii/)

#### Gulp with React and Browserify
* [Browserify and Gulp with React](https://hacks.mozilla.org/2014/08/browserify-and-gulp-with-react/)
* [Taking React to the Next Level: Mixins, Gulp, and Browserify](http://pomax.github.io/1420592591221/taking-react-to-the-next-level-mixins-gulp-and-browserify)

#### Gulp with Ember
* [Improving Your Ember.js Workflow Using Gulp.js](http://www.sitepoint.com/improving-ember-js-workflow-using-gulp-js/)

#### Gulp with WordPress
* [Advanced WordPress Development Using Gulp](https://premium.wpmudev.org/blog/advanced-wordpress-development-using-gulp/)

### Miscellaneous Resources
* [Gulp Cheatsheet ★1336](https://github.com/osscafe/gulp-cheatsheet)
* [Playground for Gulp Recipes ★511](https://github.com/johnpapa/gulp-patterns)

## Plugins
### Compilation
* [gulp-sass](https://github.com/dlmanning/gulp-sass) - Sass → CSS with [libsass ★3472](https://github.com/sass/libsass).
* [gulp-ruby-sass ★472](https://github.com/sindresorhus/gulp-ruby-sass) - Sass → CSS with Ruby Sass.
* [gulp-compass ★171](https://github.com/appleboy/gulp-compass) - Sass → CSS with Ruby Sass & Compass.
* [gulp-less](https://github.com/plus3network/gulp-less) - [Less ★14672](https://github.com/less/less.js) → CSS.
* [gulp-stylus](https://github.com/stevelacy/gulp-stylus) - [Stylus ★8030](https://github.com/stylus/stylus) → CSS.
* [gulp-postcss](https://github.com/postcss/gulp-postcss) - Pipe CSS through [PostCSS ★14519](https://github.com/postcss/postcss) processors with a single parse.
* [gulp-coffee](https://github.com/contra/gulp-coffee) - [Coffeescript ★13913](https://github.com/jashkenas/coffeescript) → JavaScript.
* [gulp-typescript](https://github.com/ivogabe/gulp-typescript) - [TypeScript ★21486](https://github.com/Microsoft/TypeScript) → JavaScript.
* [gulp-react](https://github.com/sindresorhus/gulp-react) - Facebook [React ★65519](https://github.com/facebook/react) JSX templates → JavaScript.
* [webpack-stream](https://github.com/shama/webpack-stream) - Run [webpack ★27119](https://github.com/webpack/webpack) as a stream to conveniently integrate with gulp.

### Transpilation
* [gulp-babel](https://github.com/babel/gulp-babel) - ES6 → ES5 with [babel ★20847](https://github.com/babel/babel).
* [gulp-traceur](https://github.com/sindresorhus/gulp-traceur) - ES6 → ES5 using [Traceur ★7248](https://github.com/google/traceur-compiler).
* [gulp-regenerator](https://github.com/sindresorhus/gulp-regenerator) - ES6 → ES5 with [Regenerator ★1913](https://github.com/facebook/regenerator).
* [gulp-es6-transpiler](https://github.com/sindresorhus/gulp-es6-transpiler) - [:no_entry:] ES6 → ES5 with [es6-transpiler ★219](https://github.com/termi/es6-transpiler).
* [gulp-myth](https://github.com/sindresorhus/gulp-myth) - [Myth ★4272](https://github.com/segmentio/myth) - a polyfill for future versions of the CSS spec.
* [gulp-cssnext](https://github.com/MoOx/gulp-cssnext) - [:no_entry:] Use tomorrow's CSS syntax, today, using [cssnext ★4127](https://github.com/MoOx/postcss-cssnext).

### Concatenation
* [gulp-concat ★653](https://github.com/contra/gulp-concat) - Concatenate files.

### Minification
* [gulp-clean-css](https://github.com/scniro/gulp-clean-css) - Minify CSS with [clean-css ★2391](https://github.com/jakubpawlowicz/clean-css).
* [gulp-csso](https://github.com/ben-eb/gulp-csso) - Minify CSS with [CSSO ★2184](https://github.com/css/csso).
* [gulp-uglify](https://github.com/terinjokes/gulp-uglify) - Minify JavaScript with [UglifyJS2 ★6383](https://github.com/mishoo/UglifyJS2).
* [gulp-htmlmin](https://github.com/jonschlinkert/gulp-htmlmin) - Minify HTML with [html-minifier ★2316](https://github.com/kangax/html-minifier).
* [gulp-htmlmin ★463](https://github.com/jonschlinkert/gulp-htmlmin) - Minify HTML.
* [gulp-imagemin](https://github.com/sindresorhus/gulp-imagemin) - Minify PNG, JPEG, GIF and SVG images with [imagemin ★1251](https://github.com/imagemin/imagemin).
* [gulp-svgmin ★255](https://github.com/ben-eb/gulp-svgmin) - Minify SVG files with gulp.

### Optimization
* [gulp-uncss](https://github.com/ben-eb/gulp-uncss) - Remove unused CSS selectors with [UnCSS ★6633](https://github.com/giakki/uncss).
* [gulp-css-base64](https://github.com/zckrs/gulp-css-base64) - Transform all resources found (those within a url() declaration) in CSS files into base64-encoded data URI strings.
* [gulp-svg2png ★50](https://github.com/akoenig/gulp-svg2png) - Convert SVGs to PNGs.
* [gulp-responsive ★338](https://github.com/mahnunchik/gulp-responsive) - Generate images at different sizes.
* [gulp-svgstore ★535](https://github.com/w0rm/gulp-svgstore) - Combine svg files into one with <symbol> elements.
* [gulp-iconfont ★622](https://github.com/nfroidure/gulp-iconfont) - Create icon fonts from several SVG icons.

### Injecting Assets
* [gulp-useref ★616](https://github.com/jonkemp/gulp-useref) - Parse build blocks in HTML files to replace references to non-optimized scripts or stylesheets.
* [gulp-inject ★683](https://github.com/klei/gulp-inject) - Transform each file to a string and inject each transformed string into placeholders in the target stream files.
* [wiredep ★1147](https://github.com/taptapship/wiredep) - Wire Bower dependencies to your source code.

### Templating
* [gulp-angular-templatecache ★507](https://github.com/miickel/gulp-angular-templatecache) - Concatenate and register AngularJS templates in the $templateCache.
* [gulp-jade](https://github.com/phated/gulp-jade) - [Jade](https://github.com/pugjs/jade) → HTML.
* [gulp-handlebars](https://github.com/lazd/gulp-handlebars) - [Handlebars ★11838](https://github.com/wycats/handlebars.js) templates → JavaScript.
* [gulp-hb](https://github.com/shannonmoeller/gulp-hb) - [Handlebars ★11838](https://github.com/wycats/handlebars.js) templates → HTML.
* [gulp-nunjucks](https://github.com/sindresorhus/gulp-nunjucks) - [Nunjucks ★4122](https://github.com/mozilla/nunjucks) templates → JavaScript.
* [gulp-dustjs](https://github.com/sindresorhus/gulp-dust) - [Dust ★2545](https://github.com/linkedin/dustjs) templates → JavaScript.
* [gulp-riot](https://github.com/e-jigsaw/gulp-riot) - [Riot ★11834](https://github.com/riot/riot) templates → JavaScript.
* [gulp-markdown ★125](https://github.com/sindresorhus/gulp-markdown) - Markdown → HTML.
* [gulp-template](https://github.com/sindresorhus/gulp-template) - [Lodash  ★23091](https://github.com/lodash/lodash) templates → JavaScript.
* [gulp-swig](https://github.com/colynb/gulp-swig) - [Swig ★2889](https://github.com/paularmstrong/swig) templates → HTML.
* [gulp-remark](https://github.com/denysdovhan/gulp-remark) - Gulp plugin for [remark ★862](https://github.com/wooorm/remark) - markdown processor powered by plugins

### Linting
* [gulp-csslint](https://www.npmjs.com/package/gulp-csslint) - Automated linting of CSS with [CSSLint ★3717](https://github.com/CSSLint/csslint).
* [gulp-htmlhint](https://github.com/bezoerb/gulp-htmlhint) - [HTMLHint ★1426](https://github.com/yaniswang/HTMLHint) wrapper to validate your HTML.
* [gulp-jshint](https://github.com/spalger/gulp-jshint) - Detect errors and potential problems in JavaScript with [JSHint ★7177](https://github.com/jshint/jshint).
* [gulp-jscs](https://github.com/jscs-dev/gulp-jscs) - Check JavaScript code style with [jscs ★5125](https://github.com/jscs-dev/node-jscs).
* [gulp-coffeelint](https://github.com/janraasch/gulp-coffeelint) - A style checker that helps keep [CoffeeScript ★13913](https://github.com/jashkenas/coffeescript) code clean.
* [gulp-tslint](https://github.com/panuhorsmalahti/gulp-tslint) - [TypeScript ★21486](https://github.com/Microsoft/TypeScript) linter plugin for gulp.
* [gulp-eslint ★437](https://github.com/adametry/gulp-eslint) - Identify and report on patterns found in ECMAScript/JavaScript code.
* [gulp-w3cjs](https://github.com/callumacrae/gulp-w3cjs) - Validate HTML with [w3cjs ★124](https://github.com/thomasdavis/w3cjs).
* [gulp-lesshint](https://github.com/lesshint/gulp-lesshint) - Lint less files with [lesshint ★87](https://github.com/lesshint/lesshint).
* [gulp-check-unused-css ★341](https://github.com/zalando/gulp-check-unused-css) - Check your HTML templates for unused CSS classes.

### Live Reload
* [browser-sync](https://github.com/BrowserSync/browser-sync) - Keep multiple browsers & devices in sync when building websites ([recipes](https://github.com/BrowserSync/gulp-browser-sync)).
* [gulp-livereload ★728](https://github.com/vohof/gulp-livereload) - Gulp plugin for livereload.

### Caching
* [gulp-changed ★635](https://github.com/sindresorhus/gulp-changed) - Only pass through changed files.
* [gulp-cached ★399](https://github.com/contra/gulp-cached) - A simple in-memory file cache.
* [gulp-remember ★136](https://github.com/ahaurw01/gulp-remember) - Remember and recall files passed through it.
* [gulp-newer ★174](https://github.com/tschaub/gulp-newer) - Pass through newer source files only.

### Flow Control
* [merge-stream ★119](https://github.com/grncdr/merge-stream) - Merge multiple streams into one interleaved stream.
* [streamqueue ★57](https://github.com/nfroidure/StreamQueue) - Pipe queued streams progressively.
* [run-sequence ★824](https://github.com/OverZealous/run-sequence) - Run a series of dependent gulp tasks in order.
* [gulp-if ★528](https://github.com/robrich/gulp-if) - Conditionally run a task.

### Logging
* [gulp-notify ★543](https://github.com/mikaelbr/gulp-notify) - Notification plugin for gulp.
* [gulp-size ★197](https://github.com/sindresorhus/gulp-size) - Display the size of your project.
* [gulp-debug ★172](https://github.com/sindresorhus/gulp-debug) - Debug vinyl file streams to see what files are run through your gulp pipeline.

### Testing
* [gulp-mocha](https://github.com/sindresorhus/gulp-mocha) - Run [Mocha ★12192](https://github.com/mochajs/mocha) tests.
* [gulp-jasmine](https://github.com/sindresorhus/gulp-jasmine) - Run [Jasmine 2 ★12384](https://github.com/jasmine/jasmine) tests in Node.js.
* [gulp-protractor](https://github.com/mllrsohn/gulp-protractor) - Gulp wrapper for [Protractor ★6528](https://github.com/angular/protractor) tests.
* [gulp-coverage ★60](https://github.com/dylanb/gulp-coverage) - Coverage reporting for Node.js that is independent of the test runner.
* [gulp-karma ★302](https://github.com/karma-runner/gulp-karma) - Karma test runner for gulp.
* [gulp-ava](https://github.com/sindresorhus/gulp-ava)- Run [AVA](https://github.com/sindresorhus/ava) tests with gulp.

### Miscellaneous Plugins
* [gulp-util ★753](https://github.com/gulpjs/gulp-util) - Set of useful utilities.
* [gulp-plumber ★688](https://github.com/floatdrop/gulp-plumber) - Prevent pipe breaking caused by errors.
* [gulp-load-plugins ★682](https://github.com/jackfranklin/gulp-load-plugins) - Automatically load in gulp plugins.
* [main-bower-files ★580](https://github.com/ck86/main-bower-files) - Simplify build process setup by dynamically getting the library files.
* [autoprefixer ★12530](https://github.com/postcss/autoprefixer) - Parse CSS and add vendor prefixes to rules by Can I Use.
* [gulp-sourcemaps](https://github.com/floridoo/gulp-sourcemaps) - Provide source map support.
* [gulp-replace ★345](https://github.com/lazd/gulp-replace) - A string replace plugin for gulp.
* [gulp-rename ★518](https://github.com/hparra/gulp-rename) - Rename files easily.
* [gulp-rev ★1190](https://github.com/sindresorhus/gulp-rev) - Static asset revisioning by appending content hash to filenames: unicorn.css → unicorn-d41d8cd98f.css.
* [del ★612](https://github.com/sindresorhus/del) - Delete files/folders using globs.
* [gulp-exec ★110](https://github.com/robrich/gulp-exec) - Run a shell command.
* [gulp-strip-debug ★189](https://github.com/sindresorhus/gulp-strip-debug) - Strip console, alert, and debugger statements from JavaScript code.
* [gulp-cssimport ★23](https://github.com/unlight/gulp-cssimport) - Parses a CSS file, finds imports, grabs the content of the linked file and replaces the import statement with it.
* [gulp-inline-css ★208](https://github.com/jonkemp/gulp-inline-css) - Inline your CSS properties into the style attribute in an HTML file.
* [gulp-gh-pages ★545](https://github.com/shinnn/gulp-gh-pages) - Publish contents to Github pages.
* [gulp-ng-annotate](https://github.com/Kagami/gulp-ng-annotate) - Add AngularJS dependency injection annotations with [ng-annotate ★2061](https://github.com/olov/ng-annotate).
* [gulp-bump ★228](https://github.com/stevelacy/gulp-bump) - Bump any semver JSON version.
* [gulp-file-include ★396](https://github.com/coderhaoxin/gulp-file-include) - Include files with gulp.
* [gulp-zip ★195](https://github.com/sindresorhus/gulp-zip) - ZIP compress files.
* [gulp-git ★349](https://github.com/stevelacy/gulp-git) - Run Git commands with gulp.
* [gulp-filter ★259](https://github.com/sindresorhus/gulp-filter) - Filter files in a vinyl stream using globbing.
* [gulp-preprocess ★211](https://github.com/jas/gulp-preprocess) - Preprocess files based on custom context or environment configuration.
* [gulp-eval] (https://github.com/gulp-bem/gulp-eval) - Eval JS-expression or require CommonJS modules and JSON files.

## Scaffolding
### Boilerplates
* [web-starter-kit ★16277](https://github.com/google/web-starter-kit) - Google Web Starter Kit.
* [gulp-plugin-boilerplate ★57](https://github.com/sindresorhus/gulp-plugin-boilerplate) - Boilerplate to kickstart creating gulp plugins.
* [polymer-starter-kit ★2376](https://github.com/polymerelements/polymer-starter-kit) - A starting point for Polymer 1.0 apps.
* [este ★4848](https://github.com/este/este) - The most complete React/Flux dev stack and starter kit for isomorphic functional web apps.
* [mnml ★733](https://github.com/mrmrs/mnml) - Minimal boilerplate to start a responsive HTML5/Sass project.
* [kraken ★651](https://github.com/cferdinandi/kraken) - A lightweight, mobile-first boilerplate for front-end web developers.
* [angularjs-gulp-browserify-boilerplate ★1064](https://github.com/jakemmarsh/angularjs-gulp-browserify-boilerplate) - Boilerplate using AngularJS, Sass, gulp, and Browserify.
* [hapi-ninja ★394](https://github.com/poeticninja/hapi-ninja) - A Node.js, Hapi, and Swig boilerplate.
* [laravel-5-boilerplate ★2161](https://github.com/rappasoft/laravel-5-boilerplate) - A Laravel 5 boilerplate project.
* [react-starterkit ★359](https://github.com/wbkd/react-starterkit) - React starter kit that contains react-router, Reflux, jest, webpack, gulp and Stylus.

### Yeoman Generators
* [generator-gulp-webapp](https://github.com/yeoman/generator-gulp-webapp) - A gulp generator for modern webapps.
* [generator-gulp-angular ★3895](https://github.com/Swiip/generator-gulp-angular) - Yeoman generator for AngularJS with gulp.
* [generator-react-gulp-browserify ★424](https://github.com/randylien/generator-react-gulp-browserify) - A Yeoman Generator for React library. It includes gulp, Browserify, Browsersync and Bootstrap.
* [generator-node-gulp ★38](https://github.com/youngmountain/generator-node-gulp) - A Node.js module generator including gulp and Mocha.
* [generator-gulp-bootstrap ★70](https://github.com/niallobrien/generator-gulp-bootstrap) - Yeoman generator for Bootstrap, gulp & libsass.
* [generator-angulpify ★152](https://github.com/jgoux/generator-angulpify) - Yeoman generator involving AngularJS, gulp and Browserify.
* [generator-ionic-gulp ★141](https://github.com/tmaximini/generator-ionic-gulp) - A Yeoman generator for Ionic Projects with gulp.
* [generator-gulp-plugin-boilerplate](https://github.com/sindresorhus/generator-gulp-plugin-boilerplate) - Scaffold out a [gulp plugin boilerplate ★57](https://github.com/sindresorhus/gulp-plugin-boilerplate).
* [generator-jekyllized ★326](https://github.com/sondr3/generator-jekyllized) - Jekyll workflow with gulp, Sass, AutoPrefixer, asset optimization and cache busting and much more.

## Miscellaneous
* [elixir ★1071](https://github.com/laravel/elixir) - A clean, fluent API for defining basic gulp tasks for your Laravel applications.
* [gulp-app](https://github.com/sindresorhus/gulp-app) - Gulp as an app (OS X).
* [lmn-gulp-tasks ★21](https://github.com/Lostmyname/lmn-gulp-tasks) - Example of gulp tasks unit testing.
* [gulp-chef](http://gulp-cookery.github.io/gulp-chef/) - An elegant, intuitive way to reuse gulp tasks.

## License
[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Philipp Alferov](https://github.com/alferov) has waived all copyright and related or neighboring rights to this work.
