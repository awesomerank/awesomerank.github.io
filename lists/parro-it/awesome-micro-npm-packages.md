<h1 align="center">
Ranked awesome lists, all in one place
</h1>
<p align="center">
	This list is a copy of <a href="parro-it/awesome-micro-npm-packages">parro-it/awesome-micro-npm-packages</a> with ranks
</p>
---
# Awesome Micro npm Packages [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg) ★59088](sindresorhus/awesome)

> A curated list of small, focused Node.js modules.

*Inspired by the [awesome ★59088](sindresorhus/awesome) list thing.*


## Articles

* [One-line node modules](https://github.com/sindresorhus/ama/issues/10)
* [Build small single purpose modules](http://thenodeway.io/introduction/#build-small-single-purpose-modules)
* [Module best practices ★873 ⏳1Y](mattdesl/module-best-practices)
* [Evaluating Packages Part 1 - Turn to community](http://bytearcher.com/articles/evaluating-packages-1-check-community/) 
* [Evaluating Packages Part 2 - Review repository](http://bytearcher.com/articles/evaluating-packages-2-review-repository/)
* [Small modules: it’s not quite that simple](https://medium.com/@Rich_Harris/small-modules-it-s-not-quite-that-simple-3ca532d65de4)
* [Hyper Modular Packages: A Crazy Cult or a Reasonable Practice?](http://thefullstack.xyz/hyper-modular-packages-a-crazy-cult-or-a-reasonable-practice/)
* [In Defense of Hyper Modular JavaScript](https://medium.freecodecamp.com/in-defense-of-hyper-modular-javascript-33934c79e113)
* [Tiny npm package: Guidelines to create a Node.js module following the small package philosophy](http://g14n.info/2015/12/tiny-npm-package/)
* [The cost of small modules](https://nolanlawson.com/2016/08/15/the-cost-of-small-modules/)

## Modules

### Array

* [is-sorted ★4](dcousens/is-sorted) - A small module to check if an Array is sorted.
* [array-first ★5](jonschlinkert/array-first) - Get the first element or first n elements of an array.
* [array-last ★8 ⏳1Y](jonschlinkert/array-last) - Return the last element in an array.
* [arr-flatten ★21](jonschlinkert/arr-flatten) - Recursively flatten an array or arrays.
* [dedupe ★8](seriousManual/dedupe) - Remove duplicates from an array.
* [array-range ★13 ⏳2Y](mattdesl/array-range) - Creates a new array with given range.
* [arr-diff ★15](jonschlinkert/arr-diff) - Returns an array with only the unique values from the first array, by excluding all values from additional arrays using strict equality for comparisons.
* [filled-array ★25 ⏳1Y](sindresorhus/filled-array) - Returns an array filled with the specified input
* [map-array ★3](parro-it/map-array) - Map object keys and values into an array.
* [in-array ★14 ⏳1Y](jonschlinkert/in-array) - Return true if any of passed values exists in array - faster than using indexOf.
* [unordered-array-remove ★100 ⏳1Y](mafintosh/unordered-array-remove) - Efficiently remove an element from an unordered array without doing a splice.
* [array-swap ★1 ⏳1Y](michaelzoidl/swap-array) - Swap position of two items in an array.


### String

* [decamelize ★57 ⏳1Y](sindresorhus/decamelize) - Convert a camelized string into a lowercased one with a custom separator: unicornRainbow → unicorn_rainbow.
* [pad-left ★30](jonschlinkert/pad-left) - Left pad a string with zeros or a specified string.
* [to-camel-case ★16](ianstormtaylor/to-camel-case) - Convert a string to a camel case.
* [to-capital-case ★3 ⏳1Y](ianstormtaylor/to-capital-case) - Convert a string to a capital case.
* [to-constant-case ★0 ⏳1Y](ianstormtaylor/to-constant-case) - Convert a string to a constant case.
* [to-dot-case ★2 ⏳1Y](ianstormtaylor/to-dot-case) - Convert a string to a dot case.
* [to-no-case ★6](ianstormtaylor/to-no-case) - Remove an existing case from a string.
* [to-pascal-case ★2 ⏳1Y](ianstormtaylor/to-pascal-case) - Convert a string to a pascal case.
* [to-sentence-case ★1 ⏳1Y](ianstormtaylor/to-sentence-case) - Convert a string to a sentence case.
* [to-snake-case ★5 ⏳1Y](ianstormtaylor/to-snake-case) - Convert a string to a snake case.
* [to-space-case ★1 ⏳1Y](ianstormtaylor/to-space-case) - Convert a string to a space case.
* [to-title-case ★9 ⏳1Y](ianstormtaylor/to-title-case) - Convert a string to a title case.
* [node-slug ★775](dodo/node-slug) - slugifies even utf-8 chars.
* [rtrim ★0](sergejmueller/rtrim) - Strip whitespace - or other characters - from the end of a string.
* [slice.js ★15](hustcc/slice.js) - Javascript library to engance String.substring / Array.slice with python slice style.

### Date & Time

* [pretty-ms ★224 ⏳1Y](sindresorhus/pretty-ms) - Convert milliseconds to a human readable string: 1337000000 → 15d 11h 23m 20s.
* [hirestime ★3](seriousManual/hirestime) - A wrapper around the built-in high resolution timer which simplifies the calculation of timestamps.
* [periods ★1 ⏳2Y](timruffles/periods) - Defined time-periods constants for Javascript, in milliseconds.
* [fecha ★993](taylorhakes/fecha) - Javascript Date formatting and parsing.
* [akamai-time-reference ★0](jucrouzet/akamai-time-reference) - Get reference time using Akamai's time reference service.
* [timeago.js ★2535](hustcc/timeago.js) - A tiny(~1.7kb) library used to format date with `*** time ago` statement.

### Object

* [map-obj ★36](sindresorhus/map-obj) - Map object keys and values into a new object.
* [filter-obj ★21](sindresorhus/filter-obj) - Filter object keys and values into a new object.
* [object-values ★14](sindresorhus/object-values) - Get the values of an object.
* [object-pairs ★2 ⏳2Y](eush77/object-pairs) - Turn an object into list of [key, value] pairs for mapping, iterating or other purposes.
* [zipmap ★4 ⏳2Y](landau/zipmap) - Returns a map with the keys mapped to the corresponding vals. zipmap also accepts a single value of objects or pairs.
* [just-pluck ★3 ⏳1Y](jarofghosts/just-pluck) - Pluck without the madness.
* [deep-equal ★209](substack/node-deep-equal) - Node's assert.deepEqual() algorithm as a standalone module.
* [deep-assign ★217](sindresorhus/deep-assign) - Recursive Object.assign().
* [set-value ★16](jonschlinkert/set-value) - Create nested values and any intermediaries dot notation (`'a.b.c'`) paths.
* [get-value ★33](jonschlinkert/get-value) - Use property paths (a.b.c) to get a nested value from an object.
* [has-value ★7](jonschlinkert/has-value) - Returns true if a value exists, false if empty. Works with deeply nested values using dot notation (`'a.b.c'`) paths.
* [has-key-deep ★1](ryanaghdam/has-key-deep) - Deep-search objects for keys. Keys can be searched by providing an array of keys, or using a dot-notiation.
* [flatkeys ★3 ⏳3Y](ricardobeat/flatkeys) - Flatten object key hierarchies into a list of strings using a custom separator.
* [flatten-obj ★10](watson/flatten-obj) - Converts an object literal with deeply nested nodes to a simple key/value object.
* [is-empty-object ★10 ⏳1Y](gummesson/is-empty-object) - Check if an object is empty.
* [stringify-object ★124](yeoman/stringify-object) - Stringify an object/array like JSON.stringify just without all the double-quotes.
* [sorted-object ★18](domenic/sorted-object) - Returns a copy of an object with its keys sorted.
* [static-props ★1](fibo/static-props) - Defines static object attributes using `Object.defineProperties`
* [missing-deep-keys ★1](vladgolubev/missing-deep-keys) - Returns an array of keys from first object that are missing in second.
* [has-own-property ★2](LinusU/has-own-property) - Check if an object has a local property. 

### Function

* [compose-function ★25](stoeffel/compose-function) - Compose a new function from smaller functions `f(g(x)).
* [curry ★245 ⏳1Y](dominictarr/curry) - A curry function without anything too clever.
* [once ★122](isaacs/once) - Run a function exactly one time.
* [deep-bind ★7 ⏳1Y](jonschlinkert/deep-bind) - Bind a context to all functions in an object, including deeply nested functions.
* [identity-function ★5 ⏳1Y](substack/identity-function) - Always return the input argument. 
* [mem ★266](sindresorhus/mem) - An optimization technique used to speed up consecutive function calls by caching the result of calls with identical input.

### Math

* [is-number ★21](jonschlinkert/is-number) - Returns `true` if the value is a number.

### Stream
* [through2 ★1105](rvagg/through2) - Tiny wrapper around Node streams2 Transform to avoid explicit subclassing noise.
* [through2-filter ★18 ⏳1Y](brycebaril/through2-filter) - A through2 to create an Array.prototype.filter analog for streams.
* [through2-map ★52](brycebaril/through2-map) - A through2 to create an Array.prototype.map analog for streams.
* [stream-spigot ★15](brycebaril/node-stream-spigot) - A readable stream generator, useful for testing or converting simple functions into Readable streams.
* [concat-stream ★403](maxogden/concat-stream) - writable stream that concatenates strings or data and calls a callback with the result.
* [JSONStream ★1227](dominictarr/JSONStream) - streaming JSON.parse and stringify
* [through2-map-promise ★0 ⏳1Y](RangerMauve/through2-map-promise) - A small promise-based wrapper for through2.
* [pump ★332](mafintosh/pump) - pipe streams together and close all of them if one of them closes.
* [split ★262](dominictarr/split) - Break up a stream and reassemble it so that each line is a chunk.

### Promise

* [pify ★457](sindresorhus/pify) - Promisify a callback-style function.
* [promise-all-props ★5](Siilwyn/promise-all-props) - Like `Promise.all` but for object properties.
* [sleep-promise ★18](brummelte/sleep-promise) - Resolves a promise after a specified delay.
* [is-promise ★36 ⏳1Y](then/is-promise) - Test whether an object looks like a promises-a+ promise.

### File System

* [rimraf ★1689](isaacs/rimraf) - A deep deletion module for node (like rm -rf).
* [mkdirp ★1394](substack/node-mkdirp) - Recursively mkdir, like mkdir -p.
* [du ★19 ⏳3Y](rvagg/node-du) - A simple JavaScript implementation of du -sb.
* [file-size ★186 ⏳2Y](Nijikokun/file-size) - Lightweight filesize to human-readable / proportions w/o dependencies.
* [tmp ★289](raszi/node-tmp) - Temporary file and directory creator for node.js.
* [fs-promise ★174](kevinbeaty/fs-promise) - Node fs methods as Promise/A+ (optional fs-extra, graceful-fs).

### Browser

* [delegate ★65](zenorocha/delegate) - Lightweight event delegation.
* [insert-css ★175](substack/insert-css) - Insert a string of css into the head
* [dom-element-value ★3](crysalead-js/dom-element-value) - DOM element value getter/setter.
* [image-promise ★23](bfred-it/image-promise) - Load one or more `<img>`s in a Promise.
* [get-media-size ★4](bfred-it/get-media-size) - Get the original size of any `img`/`video`/`svg`/`canvas` tags or canvas context.
* [document-ready ★20](bendrucker/document-ready) - Document ready listener for modern browsers.

### Semver

* [semver ★1744](npm/node-semver) - The semantic version parser used by npm.
* [semver-max ★1 ⏳1Y](eush77/semver-max) - Find maximum (or minimum) version according to semver.
* [semver-first-satisfied ★3 ⏳1Y](parro-it/semver-first-satisfied) - Find minimum in an array of version that satisfies a semver range.



### CLI

* [abbrev ★101](isaacs/abbrev-js) - Calculate the set of unique abbreviations for a given set of strings.
* [glob ★3408](isaacs/node-glob) - Glob functionality for node.js.
* [username ★59](sindresorhus/username) - Get the username of the current user.
* [minimist ★2241](substack/minimist) - Parse argument options.

### Module management

* [pkg-conf ★47](sindresorhus/pkg-conf) - Get namespaced config from the closest package.json.
* [normalize-pkg ★10](jonschlinkert/normalize-pkg) - Normalize values in package.json to improve compatibility, programmatic readability and usefulness with third party libs.

### Generators

* [is-generator ★7](blakeembrey/is-generator) - Check whether a given value is a generator function.

### Other

* [node-uuid ★89](broofa/node-uuid) - Generate RFC-compliant UUIDs in JavaScript.
* [node-mime ★918](broofa/node-mime) - Comprehensive MIME type mapping API based on mime-db module.
* [not-defined ★1](fibo/not-defined) - Is a shortcut to `(typeof foo === 'undefined') || (foo === null)`.
* [is-fqdn ★13 ⏳1Y](parro-it/is-fqdn) - Check if a string represent a fully qualified domain name.

## Related lists

This section contains awesome lists that you may find useful if you use or write small NPM modules.

* [awesome-nodejs ★17249](sindresorhus/awesome-nodejs) - A curated list of delightful Node.js packages and resources.
* [awesome-npm ★2423](sindresorhus/awesome-npm) - Awesome npm resources and tips.

## Small modules rockstars to follow

These people are used to develop awesome NPM modules that follows the single responsibility philosophy.
Follow them to discover new great modules:

[![Sindre Sorhus](https://avatars.githubusercontent.com/u/170270?s=130)](https://github.com/sindresorhus) | [![James Halliday](https://avatars1.githubusercontent.com/u/12631?s=130)](https://github.com/substack) | [![Eugene Sharygin](https://avatars3.githubusercontent.com/u/4472489?s=130)](https://github.com/eush77) | [![Isaac Z. Schlueter](https://avatars3.githubusercontent.com/u/9287?s=130)](https://github.com/isaacs) | [![Jon Schlinkert](https://avatars1.githubusercontent.com/u/383994?s=130)](https://github.com/jonschlinkert) | [![Dominic Tarr](https://avatars3.githubusercontent.com/u/259374?s=130)](https://github.com/dominictarr)
---|---|---|---|---|---
[Sindre Sorhus](https://github.com/sindresorhus) | [James Halliday](https://github.com/substack) | [Eugene Sharygin](https://github.com/eush77) | [Isaac Z. Schlueter](https://github.com/isaacs) | [Jon Schlinkert](https://github.com/jonschlinkert) | [Dominic Tarr](https://github.com/dominictarr)

[![Rod Vagg](https://avatars0.githubusercontent.com/u/495647?s=130)](https://github.com/rvagg) | [![Max Ogden](https://avatars3.githubusercontent.com/u/39759?s=130)](https://github.com/maxogden)
---|---
[Rod Vagg](https://github.com/rvagg) | [Max Ogden](https://github.com/maxogden)


## Contribute

Contributions welcome! Read the [contribution guidelines](https://github.com/parro-it/awesome-micro-npm-packages/blob/master/contributing.md) first.


## License

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Andrea Parodi](https://github.com/parro-it) has waived all copyright and related or neighboring rights to this work.
---
<p align="center">
	This list is a copy of <a href="parro-it/awesome-micro-npm-packages">parro-it/awesome-micro-npm-packages</a> with ranks
</p>
