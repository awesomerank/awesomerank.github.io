---
layout: default
title: Awesome Rank for dustinspecker/awesome-eslint
---

<p align="center">
	This list is a copy of <a href="https://github.com/dustinspecker/awesome-eslint">dustinspecker/awesome-eslint</a> with ranks
</p>
---
# Awesome ESLint [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[<img src="http://eslint.org/img/logo.svg" width="160" align="right" alt="eslint">](http://eslint.org)

> A list of awesome ESLint configs, plugins, etc.

If you want to contribute, please read the [contribution guidelines](https://github.com/dustinspecker/awesome-eslint/blob/master/contributing.md).

## Contents

- [Configs](#configs)
- [Parsers](#parsers)
- [Plugins](#plugins)
  - [Frameworks and Libraries](#frameworks-and-libraries)
  - [Misc.](#misc)
  - [Practices](#practices)
  - [Style](#style)
- [Preconfigured Tools with ESLint Set up](#preconfigured-tools-with-eslint-set-up)
- [Tools](#tools)
- [Developing for ESLint](#developing-for-eslint)
- [Tutorials](#tutorials)

## Configs

- [Airbnb](https://github.com/airbnb/javascript/tree/master/packages/eslint-config-airbnb) - Shareable config for [Airbnb's style guide ★72605](https://github.com/airbnb/javascript)
- [Canonical](https://github.com/gajus/eslint-config-canonical) – Shareable config for [Canonical style guide ★12 ⏳1Y](https://github.com/gajus/canonical)
- [ESLint](https://github.com/eslint/eslint/tree/master/packages/eslint-config-eslint) - Contains the ESLint configuration used for projects maintained by the ESLint team.
- [ES ★9](https://github.com/thenativeweb/eslint-config-es) - Shareable config for very strict code
- [Facebook](https://www.npmjs.com/package/eslint-config-fbjs) - Sharable config for Facebook's style guide.
- [Google ★822](https://github.com/google/eslint-config-google) - Shareable config for the [Google style](http://google.github.io/styleguide/javascriptguide.xml)
- [Problems ★8](https://github.com/RyanZim/eslint-config-problems) - Shareable config that only catches actual problems, and doesn't enforce stylistic preferences.
- [Shopify](https://github.com/Shopify/eslint-plugin-shopify) - Shareable config for [Shopify's style guide ★162](https://github.com/Shopify/javascript)
- [Standard](https://github.com/feross/eslint-config-standard) - Shareable config for JavaScript [Standard Style](https://github.com/feross/standard)
- [Supermind ★2](https://github.com/supermind/eslint-config-supermind) - Shareable config for Supermind style
- [XO](https://github.com/sindresorhus/eslint-config-xo) - Shareable config for [XO](https://github.com/sindresorhus/xo)

## Parsers

- [Babel ★2153](https://github.com/babel/babel-eslint) - Use Babel's parser for linting all Babel features
- [TypeScript ★643](https://github.com/eslint/typescript-eslint-parser) - A TypeScript parser that produces output compatible with ESLint
- [BrightScript ★22](https://github.com/RokuRoad/eslint-plugin-roku) - BrightScript plugin for Roku development. Includes Parser and Rules

## Plugins

### Frameworks and Libraries

- [Angular](https://github.com/Gillespie59/eslint-plugin-angular) - Linting rules to adhere to the [John Papa's Angular Styleguide ★23942](https://github.com/johnpapa/angular-styleguide)
- [AVA](https://github.com/sindresorhus/eslint-plugin-ava) - Linting rules for AVA
- [Backbone ★92](https://github.com/ilyavolodin/eslint-plugin-backbone) - Linting rules for Backbone
- [Chai ★7](https://github.com/turbo87/eslint-plugin-chai-expect) - Linting rules for Chai
- [Ember](https://github.com/netguru/eslint-plugin-ember) - Linting rules for Ember
- [Hapi](https://github.com/continuationlabs/eslint-plugin-hapi) – Linting rules for hapi
- [Jasmine ★62](https://github.com/tlvince/eslint-plugin-jasmine) - Linting rules for Jasmine
- [Jest ★142](https://github.com/jest-community/eslint-plugin-jest) - Linting rules for Jest
- [JSDoc ★147](https://github.com/gajus/eslint-plugin-jsdoc) - Linting rules for JSDoc comments
- [Lodash ★139](https://github.com/wix/eslint-plugin-lodash) - Lodash specific linting rules
- [Lodash/fp ★110](https://github.com/jfmengels/eslint-plugin-lodash-fp) - Lodash/fp specific linting rules
- [Lodash template ★1](https://github.com/ota-meshi/eslint-plugin-lodash-template) - Plugin for Lodash template/Underscore template
- [Meteor ★97](https://github.com/dferber90/eslint-plugin-meteor) - Meteor specific linting rules
- [Mocha ★179](https://github.com/lo1tuma/eslint-plugin-mocha) - Linting rules for Mocha
- [Mongodb](https://github.com/nfroidure/eslint-plugin-mongodb) - Mongodb native nodejs driver linting rules
- [Ramda ★68](https://github.com/ramda/eslint-plugin-ramda) - Ramda specific linting rules
- [React ★4213](https://github.com/yannickcr/eslint-plugin-react) - Linting rules for React and JSX
- [React Native ★348](https://github.com/Intellicode/eslint-plugin-react-native) - React Native specific linting rules
- [RequireJS ★24](https://github.com/cvisco/eslint-plugin-requirejs) - Linting rules for RequireJS
- [VueJS ★1484](https://github.com/vuejs/eslint-plugin-vue) - Plugin for VueJS

### Misc

- [Babel ★269](https://github.com/babel/eslint-plugin-babel) - Adds replacements for built-in rules to include Babel features
- [Compat ★1921](https://github.com/amilajack/eslint-plugin-compat) - Lint browser compatability of APIs used ([caniuse](http://caniuse.com/#search=fetch) as an ESLint plugin)
- [Coffee ★3](https://github.com/aminland/eslint-plugin-coffee) - Enables linting CoffeeScript files with, with optional linting rules from the Coffeelint library.
- [deprecate ★23](https://github.com/AlexMost/eslint-plugin-deprecate) - Mark functions or modules as deprecated and get lint messages when they are used
- [disable ★20](https://github.com/mradionov/eslint-plugin-disable) - Disable specified plugins using file path patterns and inline comments
- [es5 ★22](https://github.com/nkt/eslint-plugin-es5) - ESLint plugin for ES5 users (forbid ES2015+ usage)
- [Flow ★839](https://github.com/gajus/eslint-plugin-flowtype) - Flow type linting rules
- [Flow Errors ★374](https://github.com/amilajack/eslint-plugin-flowtype-errors) - Run Flow as an ESLint plugin
- [GraphQL](https://github.com/apollostack/eslint-plugin-graphql) - Check your GraphQL query strings against a schema
- [HTML ★224](https://github.com/BenoitZugmeyer/eslint-plugin-html) - Linting for JavaScript inside of HTML `<script>` tags
- [import ★1289](https://github.com/benmosher/eslint-plugin-import) - Linting of ES2015+  import/export syntax, and prevent issues with misspelling of file paths and import names
- [JSON ★36 ⏳1Y](https://github.com/azeemba/eslint-plugin-json) - Lint your JSON files
- [Markdown ★142](https://github.com/eslint/eslint-plugin-markdown) - Linting JavaScript in Markdown
- [Node ★317](https://github.com/mysticatea/eslint-plugin-node) - Linting rules for Node.js (checking importing paths, ES syntax, ...)
- [Notice ★5](https://github.com/nickdeis/eslint-plugin-notice) - An eslint rule that checks the top of files and fixes them too!
- [Optimize Regex ★22](https://github.com/BrainMaestro/eslint-plugin-optimize-regex) - Optimize regex literals
- [SonarJS ★5](https://github.com/SonarSource/eslint-plugin-sonarjs) – Rules detecting bugs and suspicious patterns
- [SQL ★10](https://github.com/gajus/eslint-plugin-sql) – SQL linting rules for ESLint
- [TypeLint](https://github.com/yarax/typelint) - Introduces types, based on existing schemas (Swagger, Redux) and linting access to object properties, preventing `undefined` errors
- [unicorn ★292](https://github.com/sindresorhus/eslint-plugin-unicorn) - Various awesome ESLint rules
- [ESLint Comments ★57](https://github.com/mysticatea/eslint-plugin-eslint-comments) - Best practices about ESLint directive comments (`/*eslint-disable*/`, etc...)
- [eslint-plugin-eslint-plugin ★14](https://github.com/not-an-aardvark/eslint-plugin-eslint-plugin) - An ESLint plugin for linting ESLint plugins

### Practices

- [array-func ★8](https://github.com/freaktechnik/eslint-plugin-array-func) - Avoid redundancy when using es2015 array methods and functions.
- [fp ★466](https://github.com/jfmengels/eslint-plugin-fp) - ESLint rules for functional programming
- [Immutable ★747](https://github.com/jhusain/eslint-plugin-immutable) - Disable all mutation in JavaScript
- [JSX a11y ★1008](https://github.com/evcohen/eslint-plugin-jsx-a11y) - Accessibility rules on JSX elements
- [new-with-error ★17 ⏳2Y](https://github.com/Trott/eslint-plugin-new-with-error) - Require errors to be thrown using `new`
- [no-inferred-method-name ★27 ⏳2Y](https://github.com/johnstonbl01/eslint-no-inferred-method-name) - Custom rule for ESLint that checks for inferred method names within object literals.
- [no-loops ★41](https://github.com/buildo/eslint-plugin-no-loops) - It's 2017 and you still use loops?
- [no-use-extend-native ★27](https://github.com/dustinspecker/eslint-plugin-no-use-extend-native) - Prevent using extended native objects
- [Promise ★286](https://github.com/xjamundx/eslint-plugin-promise) - Best practices when working with promises
- [Security ★680](https://github.com/nodesecurity/eslint-plugin-security) - ESLint rules for Node Security
- [this ★5](https://github.com/matijs/eslint-plugin-this) - Write pure functions, don't allow `this`
- [XSS ★15](https://github.com/Rantanen/eslint-plugin-xss) - Tries to detect XSS issues in codebase before they end up in production

### Style

- [filenames ★102](https://github.com/selaux/eslint-plugin-filenames) - Ensure consistent filenames for your javascript files

## Preconfigured Tools with ESLint Set up

- [Node.js Standard Style ★3 ⏳1Y](https://github.com/geek/node-style) - Node.js core config.
- [prettier-standard ★400](https://github.com/sheerun/prettier-standard) - Prettier formatter with custom eslint rules allowed
- [Standard](https://github.com/feross/standard) - JavaScript Standard Style
- [Superlint ★0](https://github.com/supermind/superlint) - JavaScript Supermind Style
- [XO](https://github.com/sindresorhus/xo) - JavaScript happiness style linter ❤️

## Tools

- [eslint-cli ★40](https://github.com/eslint/eslint-cli) - This is the `eslint` command that executes a local installed ESLint.
- [eslint-find-rules ★97](https://github.com/sarbbottam/eslint-find-rules) - Find built-in ESLint rules you don't have in your custom config
- [eslint-index ★8](https://github.com/wagerfield/eslint-index) - CLI for finding and managing rules in ESLint config files
- [eslint-nibble ★179](https://github.com/IanVS/eslint-nibble) - Ease into ESLint, by fixing one rule at a time
- [eslint-rule-documentation ★21](https://github.com/jfmengels/eslint-rule-documentation) - Find the url for the documentation of an ESLint rule
- [eslint-watch ★110](https://github.com/rizowski/eslint-watch) - Run ESLint with watch mode
- [codacy-eslint ★11](https://github.com/codacy/codacy-eslint) - Docker used at [Codacy](https://www.codacy.com) to run ESLint
- [esprint ★290](https://github.com/pinterest/esprint) - Run ESLint across multiple threads

## Developing for ESLint

- [eslint-docs ★1](https://github.com/j-f1/eslint-docs) - Keep your rule descriptions up-to-date across the repository

## Tutorials

- [Creating an ESLint Plugin](https://medium.com/tumblbug-engineering/creating-an-eslint-plugin-87f1cb42767f) - Article walking through the creation of an ESLint rule and plugin
- [Lint Like It’s 2015](https://medium.com/@dan_abramov/lint-like-it-s-2015-6987d44c5b48#.5p3yk0b03) - Article walking through the benefits of using ESLint
- [Linting JavaScript with ESLint](https://egghead.io/lessons/javascript-linting-javascript-with-eslint) - Video showing ESLint setup and basics
- [Linting React JSX with ESLint (in ES6)](https://egghead.io/lessons/react-linting-react-jsx-with-eslint-in-es6) - Video showing how to use React and JSX with ESLint
- [Plugin Module with Mixins](https://akullpp.com/eslint-integration) - Article on how to write a plugin as a node module containing modular mixin configuration
- [Writing a rule to spot undeclared props hiding in plain sight](http://blog.cowchimp.com/writing-a-custom-eslint-rule-to-spot-undeclared-props/) - Article about creating rules that require scope analysis

## License

[![CC0](https://i.creativecommons.org/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)
---
<p align="center">
	This list is a copy of <a href="https://github.com/dustinspecker/awesome-eslint">dustinspecker/awesome-eslint</a> with ranks
</p>
