<h1 align="center">
Ranked awesome lists, all in one place
</h1>
<p align="center">
	This list is a copy of <a href="Urigo/awesome-meteor">Urigo/awesome-meteor</a> with ranks
</p>
---
# Awesome Meteor [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg) ★59088](sindresorhus/awesome)

A curated list of awesome Meteor Packages, libraries and software.

The official Meteor resources page can be found [here](https://www.meteor.com/tools/resources)

- [Awesome Meteor](#awesome-meteor)
    - [Getting Started](#getting-started)
    - [Collections](#collections)
    - [Forms and Templates](#forms-and-templates)
    - [Users and Authentication](#users-and-authentication)
    - [REST](#rest)
    - [Files](#files)
    - [Routers](#routers)
    - [Debugging Tools](#debugging-tools)
    - [Editor Plugins](#editor-plugins)
    - [Search sort paginate](#search-sort-paginate)
    - [Mobile](#mobile)
    - [Offline](#offline)
    - [Testing](#testing)
    - [SEO](#seo)
    - [Analytics](#analytics)
    - [Cron Jobs](#cron-jobs)
    - [Payments](#payments)
    - [Deployment](#deployment)
    - [Front End Frameworks](#front-end-frameworks)
    - [Alternative Databases](#alternative-databases)
    - [Package managers](#package-managers)
    - [Internationalization](#internationalization)
    - [Scaffolding](#scaffolding)
    - [Tooling](#tooling)
- [Boilerplate](#boilerplate)
- [Resources](#resources)
    - [Books](#books)
    - [Courses](#courses)
    - [Tutorials](#tutorials)
    - [Blogs](#blogs)
    - [Websites](#websites)
    - [Weekly](#weekly)
    - [Twitter](#twitter)
    - [Job Boards](#job-boards)
- [Contributing](#contributing)

- - -


## Getting Started

*Where to start*

* [Official Meteor tutorial](https://www.meteor.com/try)
* [Discover Meteor Book](https://www.discovermeteor.com/)
* [Official Guide](http://guide.meteor.com/)
* [Why Meteor](https://wiki.dandascalescu.com/essays/why_meteor) to begin with, and [Meteor vs. the MEAN stack](https://wiki.dandascalescu.com/essays/meteor_js_vs_the_mean_stack)

## Collections

*Helpers and expensions for collections*

* [aldeed:collection2 ★962](aldeed/meteor-collection2) - Automatic validation of insert and update operations on the client and server.
* [dburles:collection-helpers ★483](dburles/meteor-collection-helpers) – Transform your collections with helpers that you define.
* [matb33:collection-hooks ★568](matb33/meteor-collection-hooks) - Extends Mongo.Collection with before/after hooks for insert/update/remove/find/findOne.
* [reywood:publish-composite ★487](englue/meteor-publish-composite) - publish a set of related documents from various collections using a reactive join
* [jagi:astronomy ★549](jagi/meteor-astronomy) - The Model layer for Meteor

## REST

*REST support for Meteor*

* [simple:rest ★319](stubailo/meteor-rest) - automatically make your Meteor app accessible over HTTP and DDP alike.
* [nimble:restivus ★504](kahmali/meteor-restivus) - Make REST endpoints for your Meteor app with incredible ease.

## Forms and Templates

*Helpers for templates*

* [aldeed:autoform ★1413](aldeed/meteor-autoform) - UI components and helpers to easily create basic forms with automatic insert and update events, and automatic reactive validation.
* [dispatch:scrollview ★23 ⏳1Y](DispatchMe/meteor-scrollview) - A high performance infinite scrollview for meteor
* [themeteorites:blaze-magic-events ★23](themeteorites/blaze-magic-events) - A new way of binding event handlers to html elements for Meteor's Blaze
* [manuel:viewmodel ★206](ManuelDeLeon/viewmodel) - MVVM for Meteor
* [webix:webix ★341](dandv/meteor-webix) - Meteor.js - Webix UI integration

## Users and Authentication

*Tools for handling users and authentication*

* [alanning:roles ★824](alanning/meteor-roles) - Roles support for the built-in accounts packages.

## Deployment

*Tools for deploying and maintaining Meteor apps*

* [When a Meteor finally hits production](https://medium.com/@davidyahalomi/when-a-meteor-finally-hits-production-6c37b81f795b) - Blog post about deploying Meteor apps
* [BulletProof Meteor](https://bulletproofmeteor.com/)
* [meteorhacks:kadira ★189](meteorhacks/kadira) - Performance Monitoring for Meteor.
* [meteor-up](https://github.com/arunoda/meteor-up) – Meteor Deployments.
* [davidyaha:collection2-migrations ★36 ⏳1Y](davidyaha/meteor-collection2-migrations) - Auto DB migrations with collection2 and simple schema on Meteor
* [percolate:migrations ★194](percolatestudio/meteor-migrations) - Simple migration system for Meteor
* [meteorhacks:fast-render ★585](kadirahq/fast-render) - Render you app even before the DDP connection is live
* [meteorhacks:cluster ★633](meteorhacks/cluster) - Clustering solution for Meteor with load balancing and service discovery
* [yogiben:admin ★806](yogiben/meteor-admin) - A complete admin dashboard solution
* [demeteorizer](https://github.com/onmodulus/demeteorizer) - Converts a Meteor app into a "standard" Node.js application
* [Amazon auto scaling and Meteor](https://allandequeirozblog.wordpress.com/2015/09/27/amazon-auto-scaling-and-meteor/) - An detailed description of how to build an infrastructure that auto scale and auto update without human interaction.
* [houston:admin ★819](gterrono/houston) - A zero-config, Django Admin-like admin for Meteor

## Routers

*Routers for Blaze*

* [iron:router ★2050](iron-meteor/iron-router) - A client and server side router designed specifically for Meteor.
* [meteorhacks:flow-router ★1057](kadirahq/flow-router) - Client Side Router for Meteor.

## Offline

*Tools for Meteor offline support*

* [ground:db ★531](GroundMeteor/db) - GroundDB is a thin layer providing Meteor offline database and methods

## Testing

*Testing tools*

* [Meteor Testing Manual](http://www.meteortesting.com/)
* [Velocity](http://velocity.meteor.com/) - A reactive test-runner for Meteor.
* [mike:mocha ★157 ⏳1Y](mad-eye/meteor-mocha-web) – Run mocha tests within the Meteor framework.
* [xolvio:chimp ★631](xolvio/chimp) - Testing so easy, a primate could do it! Supports mocha, Cucumber, jasmine, and chai.
* [velocity:html-reporter ★25 ⏳1Y](meteor-velocity/html-reporter) - HTML reporter for Meteor velocity testing framework.

## Files

*Handling files in Meteor*

* [Meteor-CollectionFS ★1051](CollectionFS/Meteor-CollectionFS) - Meteor webbased filesystem handling up and downloads.
* [netanelgilad:excel ★49](netanelgilad/meteor-excel) - Parsing and generating excel files (xlsx, xls).

## Search sort paginate

*Search sort paginate related tools*

* [tmeasday:publish-counts ★187](percolatestudio/publish-counts) - Publish the count of a cursor, in real time.
* [percolate:find-from-publication ★30](versolearning/find-from-publication) - Enable finding all documents that have been published by a given publication.
* [meteorhacks:search-source ★153](meteorhacks/search-source) - Reactive Data Source for Search
* [matteodem:easy-search ★420](matteodem/meteor-easy-search) - Easy-to-use search with Blaze Components (+ Elastic Search Support
* [alethes:pages ★410](alethes/meteor-pages) - Out of the box Meteor pagination
* [Discover Meteor Blog about pagination](https://www.discovermeteor.com/blog/pagination-problems-meteor/)

## Mobile

*Mobile Development*

* [meteoric:ionic ★1587](meteoric/meteor-ionic) - Ionic components for Meteor.
* [driftyco:ionic ★29729](driftyco/ionic) - Official Ionic support for Meteor.
* [raix:push ★439](raix/push) - Push notifications for cordova (ios, android) browser (Chrome, Safari, Firefox).
* [martijnwalraven:meteor-ios ★756](martijnwalraven/meteor-ios) - Integrates native iOS apps with the Meteor platform through DDP.
* [delight-im/Android-DDP ★245](delight-im/Android-DDP) - DDP for clients on Android.
* [okland:accounts-phone ★104](okland/accounts-phone) - A login service based on mobile phone number for Meteor.
* [okland:camera-ui ★24 ⏳1Y](okland/camera-ui) - Meteor package for taking photos with user interface, one function call on desktop and mobile. Allows to choose between camera to photoLibrary on mobile.
* [percolatestudio/cordova-plugin-safe-reload ★13 ⏳1Y](percolatestudio/cordova-plugin-safe-reload) - Cordova plugin to watch and recover after a broken Meteor Hot Code Push.

## Analytics

*Analytics*

* [okgrow:analytics ★176](okgrow/analytics) - Google Analytics, Mixpanel, KISSmetrics (and more) integration for meteor.

## Cron Jobs

*Cron Jobs in Meteor*

* [percolate:synced-cron ★425](percolatestudio/meteor-synced-cron) - Cron system for Meteor. It supports syncronizing jobs between multiple processes.
* [vsivsi:job-collection ★341](vsivsi/meteor-job-collection) - A persistent and reactive job queue for Meteor, supporting distributed workers that can run anywhere.

## Debugging Tools

*Debugging Tools*

* [msavin:mongol ★806 ⏳1Y](msavin/Mongol) - Visual Editing Tool for Meteor for MongoDB Collections.
* [msavin:jetsetter ★186 ⏳1Y](msavin/JetSetter) - Visual Get/Set Tool for Meteor Session Variables.
* [meteorhacks:kadira-debug ★158 ⏳1Y](kadirahq/meteor-debug) - Full Stack Debugging Solution for Meteor.
* [babrahams:constellation ★30 ⏳1Y](JackAdams/constellation-distro) - An extensible dev console for Meteor.
* [Meteor DDP Monitor](https://github.com/thebakeryio/meteor-ddp-monitor) - Chrome Dev tools extension for monitoring Meteor DDP traffic
* [Dr. Mongo](http://www.drmongo.com/) - Open-source MongoDB admin app built on MeteorJs.

## Package Managers

*Using package managers in Meteor*

* [meteorhacks:npm ★545 ⏳1Y](meteorhacks/npm) - Use Npm Modules with Your Meteor App.
* [cosmos:browserify ★79](elidoran/cosmos-browserify) - Browserify npm modules for client side in Meteor packages.

## Scaffolding

*Scaffolding*

* [Meteor Kitchen](http://www.meteorkitchen.com/) - Code generator for Meteor
* [iron-cli ★654](iron-meteor/iron-cli) - A scaffolding command line tool for Meteor applications 
* [Differential - meteor-boilerplate ★920 ⏳1Y](Differential/meteor-boilerplate)
* [matteodem - meteor-boilerplate ★843](matteodem/meteor-boilerplate)
* [meteoris2 ★269 ⏳1Y](radiegtya/meteoris2)
* [Base ★639](themeteorchef/base)

## Tooling

* [ESLint-plugin-Meteor ★87](dferber90/eslint-plugin-meteor) - ESLint plugin for Meteor

## Boilerplate

* [React with Webpack + Meteor as a backend](http://julian.io/react-with-webpack-meteor-as-a-backend/)

## Open source apps
* [Telescope](https://github.com/TelescopeJS/Telescope) - An open-source social news app built with Meteor
* [Microscope ★911](DiscoverMeteor/Microscope) - The Discover Meteor book's example app
* [Wekan ★9766](wekan/wekan) - Open source Trello-like kanban
* [Reaction Commerce ★4693](reactioncommerce/reaction) - Open source Commerce platform developed with Meteor
* [Crowducate Platform ★174](Crowducate/crowducate-platform) - Open source education platform Powered by meteor
* [Orion CMS](http://orionjs.org/)

## Front End Frameworks

*Alternative Front End Frameworks to Blaze*

* [Blaze](https://www.meteor.com/blaze)
* [React](http://react-in-meteor.readthedocs.org/en/latest/) - Working with React and Meteor
* [Angular ★2168](Urigo/angular-meteor) - Working with Angular and Meteor
* [Angular 2 ★328](Urigo/angular2-meteor) - Working with Angular 2 and Meteor
* [Famo.us ★349](gadicc/meteor-famous-views) - Famo.us and Meteor
* [Vue](https://github.com/Akryum/meteor-vue-component) - Working with Vue and Meteor (plus single-file components & apollo support)

* [frozeman:build-client ★212](frozeman/meteor-build-client) - A tool to bundle the client part of a Meteor app.
* [Asteroid ★679](mondora/asteroid) - An alternative client for a Meteor backend
* [ddp.js ★164](mondora/ddp.js) - Isomorphic JavaScript DDP client

## Alternative Databases

**Alternative Databases for MongoDB

* [meteor-pg ★8](Richie765/meteor-pg) - New and improved PostgreSQL support for Meteor
* [numtel:pg ★306 ⏳1Y](numtel/meteor-pg) - Reactive PostgreSQL for Meteor
* [numtel:mysql ★330](numtel/meteor-mysql) - Reactive MySQL for Meteor
* [simple:rethink ★310](Slava/meteor-rethinkdb) - RethinkDB integration for Meteor

# Resources

Where to discover new Meteor things.

## Books

* [Meteor Explained](https://gumroad.com/l/meteor-explained)
* [Meteor Tips](http://meteortips.com/)
* [Meteor Cookbook](https://github.com/awatson1978/meteor-cookbook)

## Courses

* [EventedMind](https://www.eventedmind.com/)
* [Udemy — Meteor: Build a real-time web app using only JavaScript](https://www.udemy.com/meteor-course/)
* [Udemy - A Beginner's Guide to the Meteor JavaScript Framework](https://www.udemy.com/meteorjs/)
* [tuts+ - Single Page Web Apps with Meteor](http://code.tutsplus.com/courses/single-page-web-apps-with-meteor)
* [DevFreeCasts.org](http://devfreecasts.org/meteor/)
* [MeteorTuts](http://meteortuts.com/)

## Tutorials

* [Building a CMS-powered blog in Meteor](https://buttercms.com/blog/meteor-cms-blog-tutorial)
* [scotch.io - Building a Slack Clone in Meteor](https://scotch.io/tutorials/building-a-slack-clone-in-meteor-js-getting-started)
* [Rocket-Chat Slack Clone](https://rocket.chat/)
* [Meteor Learning ★1538](ericdouglas/Meteor-Learning) - List of resources to learn
* [Learning Resources for Meteor](https://www.yauh.de/best-learning-resources-for-meteorjs/)
* [Phusion Passenger: Meteor tutorial](https://github.com/phusion/passenger/wiki/Phusion-Passenger:-Meteor-tutorial)

## Blogs

* [Official Meteor blog](http://blog.meteor.com)
* [Meteor Hacks Blog](https://meteorhacks.com/)
* [Meteor Create](http://meteorcreate.com/) - Discover the Best Meteor Tutorials
* [The Meteor podcast](http://podcast.crater.io)
* [Meteor club podcast](https://podcast.meteorjs.club/)
* [Blog about Optimistic UIs With Meteor Latency Compensation](http://info.meteor.com/blog/optimistic-ui-with-meteor-latency-compensation)

## Websites

* [Official website](https://www.meteor.com/)
* [Official Documentation](http://docs.meteor.com/)
* [Official Guide](http://guide.meteor.com/) 
* [Atmosphere](https://atmospherejs.com/) - The catalog of Meteor packages, resources and tools.
* [BulletProof Meteor](https://bulletproofmeteor.com/) - Online course for Meteor performance in production, by Arunoda Susiripala
* [Meteorpedia](http://www.meteorpedia.com) ([infrequently](http://www.meteorpedia.com/special/RecentChanges/) updated)
* [DiscoverMeteor Encyclopedia](https://www.discovermeteor.com/encyclopedia)
* [Roadmap](https://trello.com/b/hjBDflxp/meteor-roadmap)
* [Meetups](http://meteor.meetup.com/)
* [Reddit](https://www.reddit.com/r/meteor)
* [YouTube](https://www.youtube.com/channel/UC3fBiJrFFMhKlsWM46AsAYw) videos from meetups around the world
* [Unofficial Meteor FAQ ★1012 ⏳1Y](oortcloud/unofficial-meteor-faq)
* [The Meteor Chef](https://themeteorchef.com) 

### Q&A

* [Stack Overflow](http://stackoverflow.com/questions/tagged/meteor?sort=newest&pagesize=15)
* [Meteor forums](https://forums.meteor.com/)
* [Gitter IM channel](https://gitter.im/meteor/meteor)
* [The Meteor Chef Slack channel](https://themeteorchef.slack.com)
* IRC - #meteor on freenode


## Weekly

* [Meteor-Blog](http://info.meteor.com/blog)
* [Meteor Weekly](https://goodbits.io)
* [Crater.io](https://crater.io/)
* [This Week In Meteor](https://goodbits.io)

## Twitter

* [Official Meteor](https://twitter.com/meteorjs)

## Job Boards

* [We Work Meteor](https://www.weworkmeteor.com/)

# [Contributing](https://github.com/urigo/awesome-meteor/blob/master/CONTRIBUTING.md)

Your contributions are always welcome!

Thank you @gillesfabio for creating this repo!
---
<p align="center">
	This list is a copy of <a href="Urigo/awesome-meteor">Urigo/awesome-meteor</a> with ranks
</p>
