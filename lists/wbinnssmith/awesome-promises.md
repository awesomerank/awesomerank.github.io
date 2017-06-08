<h1 align="center">
Ranked awesome lists, all in one place
</h1>
<p align="center">
	This list is a copy of <a href="wbinnssmith/awesome-promises">wbinnssmith/awesome-promises</a> with ranks
</p>
---
<a href="https://promisesaplus.com/">
    <img src="https://promisesaplus.com/assets/logo-small.png" alt="Promises/A+ logo" align="right" />
</a>

# Awesome Promises [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg) ★59088](sindresorhus/awesome)

> A curated list of useful resources for JavaScript Promises

Inspired by the [awesome ★59088](sindresorhus/awesome) list thing. Not to be confused with other awesome promises like "I promise you a million dollars" or "I promise you'll stay fit and never have to go to the gym again".

**Table of Contents**

- [Resources, Blogs, and Books](#resources-blogs-and-books)
- [Promises/A+ Implementations (ES6/ES2015 compatible)](#promisesa-implementations-es6es2015-compatible)
  - [Strict Implementations](#strict-implementations)
  - [Implementations with extras](#implementations-with-extras)
  - [Fallbacks](#fallbacks)
- [Convenience Utilities](#convenience-utilities)

## Resources, Blogs, and Books

### For beginners
* [Promise Cookbook ★1125 ⏳1Y](mattdesl/promise-cookbook) - The why, what, and how. "A brief introduction [...] primarily aimed at frontend developers".
* [Promises for Asynchronous Programming](http://exploringjs.com/es6/ch_promises.html) - Chapter from [Exploring ES6](http://exploringjs.com/)
* [You Don't Know JS: Promises](https://github.com/getify/You-Dont-Know-JS/blob/master/async%20&%20performance/ch3.md) - Chapter from [You Don't Know JS: Async & Performance](https://github.com/getify/You-Dont-Know-JS/tree/master/async%20%26%20performance)
* [JavaScript Promises: an Introduction](https://developers.google.com/web/fundamentals/getting-started/primers/promises) - Basics of JavaScript's native promise implementation.
* [JavaScript with Promises](http://shop.oreilly.com/product/0636920032151.do) - from O'Reilly. Short and to-the-point. Uses native and bluebird.
* [Promise it won't hurt ★459](stevekane/promise-it-wont-hurt) - An interactive [nodeschool](https://nodeschool.io/) workshop
* [ES6 Kata Promises](http://es6katas.org/) - Promises Katas : [Basics](http://tddbin.com/#?kata=es6/language/promise/basics)
* [ES6 Promises in Depth](https://ponyfoo.com/articles/es6-promises-in-depth)
* [An Incremental Tutorial on Promises](http://www.sohamkamani.com/blog/2016/08/28/incremenal-tutorial-to-promises/) - An FAQ styled tutorial for beginners.

### Deep Dive
* [Promise Fun ★857](sindresorhus/promise-fun) - @sindresorhus's notes, patterns, and solutions to common Promise problems
* [You're Missing the Point of Promises](https://blog.domenic.me/youre-missing-the-point-of-promises/) - Promises are much more than callback aggregation, and that jQuery's implementation (prior to 3.0) isn't enough.
* [We have a problem with promises](https://pouchdb.com/2015/05/18/we-have-a-problem-with-promises.html) - "Many of us are using promises without really understanding them."
* [Promise anti-patterns](https://github.com/petkaantonov/bluebird/wiki/Promise-anti-patterns) - Common misuses and how to avoid them.
* [Promise anti-patterns (2)](http://taoofcode.net/promise-anti-patterns/) - Another set of promises anti-patterns
* [Promise Ponderings, (Anti-)Patterns, and Apologies](https://sdgluck.github.io/2015/08/24/promise-ponderings-patterns-apologies/) - Promise behaviour demonstrated and explained by common questions and their answers.
* [Javascript Promises...In Wicked Detail](http://www.mattgreer.org/articles/promises-in-wicked-detail/) - Recreate the promise implementation
* [Writing Promise-Using Specifications](https://www.w3.org/2001/tag/doc/promises-guide) - "This document gives guidance on how to write specifications that create, accept, or manipulate promises"
* [Async functions - making promises friendly](https://developers.google.com/web/fundamentals/getting-started/primers/async-functions)

### References
* [Promises/A+ specification](https://promisesaplus.com/)
* [caniuse promises](http://caniuse.com/#feat=promises)
* [Fates and States](https://github.com/domenic/promises-unwrapping/blob/master/docs/states-and-fates.md) - Quick definitions of possible states.
* [Promisees](https://bevacqua.github.io/promisees/) - Promise visualization playground for the adventurous.

## Promises/A+ Implementations (ES6/ES2015 compatible)

### Strict Implementations
These implement no more or less than the es6 spec. They make great polyfills and are exceptionally compatible with native promises.

* [pinkie](https://github.com/floatdrop/pinkie) - Ponyfill. Node-oriented, but [browserifyable ★11052](substack/node-browserify). *Extremely* small implementation.
* [native-promise-only ★548](getify/native-promise-only) - Polyfill. Browser and node-compatible.
* [es6-promise ★4529](stefanpenner/es6-promise) - Opt-in polyfill. A strict-spec subset of rsvp.js.
* [lie ★549](calvinmetcalf/lie) - Small, browserifyable with an opt-in polyfill.

### Implementations with extras
All of these provide more features than the language yet remain compatible. Node + Browsers for all.

* [bluebird ★14650](petkaantonov/bluebird) - Fully featured, extremely performant. Long stack traces & generator/coroutine support.
* [creed ★166](briancavalier/creed) - Hyper performant & full featured like Bluebird, but FP-oriented. Coroutines, generators, promises, ES2015 iterables, & fantasy-land spec.
* [rsvp.js ★3284](tildeio/rsvp.js) - Lightweight with a few extras. Compatible down to IE6!
* [Q ★13298](kriskowal/q) - One of the original implementations. Long stack traces and other goodies.
* [then/promise ★1526](then/promise) - Small with `nodeify`, `denodify` and `done()` additions.
* [when.js ★3197](cujojs/when) - Packed with control flow, functional, and utility methods.


### Fallbacks
* [native-or-bluebird](https://www.npmjs.com/package/native-or-bluebird) - Helps transition to completely native.
* [pinkie-promise ★94](floatdrop/pinkie-promise) - Use native, or fall back to `pinkie`. Great for node library authors.
* [any-promise ★142](kevinbeaty/any-promise) - Loads the first available implementation. Safe for browserify.

## Convenience Utilities
Native and strictly spec-compliant promises are awesome for compatibility, future-proofness, library authors, and browsers. However, libraries like bluebird patch goodies onto the `Promise` constructor and prototype. Solution? tiny modules of course!

### sindresorhus's many Promise utilities ([see notes ★857](sindresorhus/promise-fun))
* [delay ★126](sindresorhus/delay) - Delay a promise a specified amount of time.
* [pify ★457](sindresorhus/pify) - Promisify ("denodify") a callback-style function.
* [loud-rejection ★159](sindresorhus/loud-rejection) - Make unhandled promise rejections fail loudly instead of the default silent fail.
* [hard-rejection ★49](sindresorhus/hard-rejection) - Make unhandled promise rejections fail hard right away instead of the default silent fail
* [p-queue ★90](sindresorhus/p-queue) - Promise queue with concurrency control
* [p-break ★6](sindresorhus/p-break) - Break out of a promise chain
* [p-lazy ★37](sindresorhus/p-lazy) - Create a lazy promise that defers execution until `.then()` or `.catch()` is called
* [p-defer ★14](sindresorhus/p-defer) - Create a deferred promise
* [p-if ★28](sindresorhus/p-if) - Conditional promise chains
* [p-tap ★30](sindresorhus/p-tap) - Tap into a promise chain without affecting its value or state
* [p-map ★105](sindresorhus/p-map) - Map over promises concurrently
* [p-all ★26](sindresorhus/p-all) - Run promise-returning & async functions concurrently with optional limited concurrency
* [p-limit ★28](sindresorhus/p-limit) - Run multiple promise-returning & async functions with limited concurrency
* [p-times ★13](sindresorhus/p-times) - Run promise-returning & async functions a specific number of times concurrently
* [p-catch-if ★25](sindresorhus/p-catch-if) - Conditional promise catch handler
* [p-time ★50](sindresorhus/p-time) - Measure the time a promise takes to resolve
* [p-log ★15](sindresorhus/p-log) - Log the value/error of a promise
* [p-filter ★16](sindresorhus/p-filter) - Filter promises concurrently
* [p-settle ★18](sindresorhus/p-settle) - Settle promises concurrently and get their fulfillment value or rejection reason
* [p-memoize ★23](sindresorhus/p-memoize) - Memoize promise-returning & async functions
* [p-whilst ★26](sindresorhus/p-whilst) - Calls a function repeatedly while a condition returns true and then resolves the promise
* [p-throttle ★24](sindresorhus/p-throttle) - Throttle promise-returning & async functions
* [p-debounce ★23](sindresorhus/p-debounce) - Debounce promise-returning & async functions
* [p-retry ★54](sindresorhus/p-retry) - Retry a promise-returning or async function
* [p-wait-for ★24](sindresorhus/p-wait-for) - Wait for a condition to be true
* [p-timeout ★20](sindresorhus/p-timeout) - Timeout a promise after a specified amount of time
* [p-race ★12](sindresorhus/p-race) - A better `Promise.race()`
* [p-try ★6](sindresorhus/p-try) - `Promise#try()` ponyfill - Starts a promise chain
* [p-finally ★13](sindresorhus/p-finally) - `Promise#finally()` ponyfill - Invoked when the promise is settled regardless of outcome
* [p-any ★12](sindresorhus/p-any) - Wait for any promise to be fulfilled
* [p-some ★12](sindresorhus/p-some) - Wait for a specified number of promises to be fulfilled
* [p-pipe ★28](sindresorhus/p-pipe) - Compose promise-returning & async functions into a reusable pipeline
* [p-each-series ★12](sindresorhus/p-each-series) - Iterate over promises serially
* [p-map-series ★11](sindresorhus/p-map-series) - Map over promises serially
* [p-reduce ★13](sindresorhus/p-reduce) - Reduce a list of values using promises into a promise for a value
* [p-props ★37](sindresorhus/p-props) - Like `Promise.all()` but for `Map` and `Object`

### Others
* [promise-method ★2 ⏳1Y](wbinnssmith/promise-method) - Standalone `bluebird.method`. Turn a synchronously-returning method into a promise-returning one.
* [is-promise ★36 ⏳1Y](then/is-promise) - Determine if something looks like a Promise.
* [sprom ★12 ⏳1Y](then/sprom) - Resolve when a stream ends. Optional buffering (be careful with this!)
* [task.js ★1606](mozilla/task.js) - Write async functions in a blocking style using promises and generators. Like `bluebird.coroutine`.
* [co ★8204](tj/co) - Like `task.js` and `bluebird.coroutine`, but supports thunks too.
* [lie-fs](https://www.npmjs.com/package/lie-fs) - Promise wrappers for Node's FS API.
* [promise-do-until ★0 ⏳1Y](busterc/promise-do-until) - Calls a function repeatedly until a condition returns true and then resolves the promise.
* [promise-do-whilst ★2 ⏳1Y](busterc/promise-do-whilst) - Calls a function repeatedly while a condition returns true and then resolves the promise.
* [promise-semaphore ★24](samccone/promise-semaphore) - Push a set of work to be done in a configurable serial fashion
* [promise-nodeify ★0](kevinoid/promise-nodeify) - Standalone `nodeify` method which calls a Node-style callback on resolution or rejection.

## License
Licensed under the [Creative Commons CC0 License](https://creativecommons.org/publicdomain/zero/1.0/).
---
<p align="center">
	This list is a copy of <a href="wbinnssmith/awesome-promises">wbinnssmith/awesome-promises</a> with ranks
</p>
<script>
  (function(i,s,o,g,r,a,m){i['GoogleAnalyticsObject']=r;i[r]=i[r]||function(){
  (i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),
  m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)
  })(window,document,'script','https://www.google-analytics.com/analytics.js','ga');

  ga('create', 'UA-100705027-1', 'auto');
  ga('send', 'pageview');

</script>
