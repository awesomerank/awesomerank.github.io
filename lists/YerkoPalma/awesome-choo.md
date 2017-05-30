<h1 align="center">
Ranked awesome lists, all in one place
</h1>
<p align="center">
	This list is a copy of <a href="YerkoPalma/awesome-choo">YerkoPalma/awesome-choo</a> with ranks
</p>
---
# Awesome choo [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg) ★59088](sindresorhus/awesome) <div align="right">:steam_locomotive::train::train::train::train::train:</div>

> [choo](https://choo.io/) is a `5kb` framework for creating
> sturdy frontend applications

## Contents

- [Official resources](#official-resources)
- [Dependencies](#dependencies)
- [Demos](#demos)
- [Community](#community)
- [Plugins and addons](#plugins-and-addons)
- [Elements](#elements)
- [CLI Templates](#cli-templates)
- [Resources](#resources)
- [Projects using choo](#projects-using-choo)

### Official resources

- [Docs](https://github.com/yoshuawuyts/choo/blob/master/README.md)
- [Handbook ★138](yoshuawuyts/choo-handbook)
- [Repo ★3811](yoshuawuyts/choo)
- [Website](https://choo.io/)
- [Twitter thread](https://twitter.com/yoshuawuyts/status/730087077803528193)

### Dependencies
`choo` is a modular framework. These are the dependencies it glues together
under the hood:

- [yo-yo ★1075](maxogden/yo-yo) - Modular UI library using DOM
  diffing and ES6 template strings.
- [bel ★302](shama/bel) - Create composable DOM elements using
  template strings.
- [hyperx ★690](substack/hyperx) - Convert template strings to
  library backends.
- [morphdom ★1238](patrick-steele-idem/morphdom) - Fast and
  lightweight DOM diffing/patching (without the virtual part).
- [nanoraf ★41](yoshuawuyts/nanoraf) - Only call RAF when needed.
- [barracks ★167](yoshuawuyts/barracks) - Action dispatcher for
  unidirectional data flows.
- [sheet-router ★180](yoshuawuyts/sheet-router) - Fast, modular
  client-side router.

### Demos

- [Input example](http://requirebin.com/?gist=e589473373b3100a6ace29f7bbee3186) - ([repo](https://github.com/yoshuawuyts/choo/tree/master/examples/title))
- [HTTP effects](https://hyperdev.com/#!/project/fork-fang)
- [Mailbox routing](https://github.com/yoshuawuyts/choo/tree/master/examples/mailbox)
- [TodoMVC](http://shuheikagawa.com/todomvc-choo) - ([repo ★35](shuhei/todomvc-choo))
- [choo-firebase](https://choo-firebase-2ec21.firebaseapp.com) - ([repo](https://github.com/mw222rs/choo-firebase))
- [Grow](https://grow.static.land) - ([repo ★15](sethvincent/grow))
- [Chatbot](http://chootbot.herokuapp.com) - ([repo ★1](plaey/chatbot))
- [chat-random ★3](akiva/chat-random)
- [choo-leaflet-demo ★12](timwis/choo-leaflet-demo)

### Community

- [Freenode](https://webchat.freenode.net/?channels=choo)

### Plugins and addons

- [choo-location-electron](https://github.com/bcomnes/choo-location-electron) - Fix `choo`'s router in electron.
- [choo-log ★38](yoshuawuyts/choo-log) - Development logger for choo.
- [choo-test ★16](mantoni/choo-test) - Easy choo app unit testing.
- [choo-persist ★29](yoshuawuyts/choo-persist) - Synchronize choo state with indexedDB.
- [choo-promise ★1](rahatarmanahmed/choo-promise) - Use promises in effects and subscriptions.
- [choo-pull ★12](yoshuawuyts/choo-pull) - Wrap handlers to use pull-stream in a choo plugin.
- [choo-redirect ★10](yoshuawuyts/choo-redirect) - Redirect a view to another view.
- [choo-model ★9](yoshuawuyts/choo-model) - Experimental state management lib for choo.
- [choo-resume ★12](bengourley/choo-resume) - choo-resume + hot-rld = hot app reload in choo.

### Elements

- [dom-notifications ★100](finnp/dom-notifications) - Atom-inspired notifications component.
- [choodown ★13](trainyard/choodown) - A simple markdown component for choo.
- [choo-md-editor ★1](dbtek/choo-md-editor) - Lightweight markdown editor that can be used inside Choo app or as a standalone library.
- [choo-chartist ★7](rexmortus/choo-chartist) - A little component for using [Chartist](https://gionkunz.github.io/chartist-js/) with the choo framework.

### CLI Templates

Templates for [choo-cli ★51](trainyard/choo-cli)

- [trainyard/template-basic ★1](trainyard/template-basic)
- [haroenv/template-webpack ★3](haroenv/template-webpack)

### Resources
> :movie_camera: : videos
> :computer: : tutorials
> :book: : articles

- :computer: [Your first choo app](https://yoshuawuyts.gitbooks.io/choo/content/02_your_first_app.html)
- :movie_camera: [TCBY community live hangout](https://www.youtube.com/watch?v=a97Mw2z1SAI)
- :book: [A better frontend experience](https://medium.com/@yoshuawuyts/a-better-frontend-experience-7b0498c85658)
- :book: [Composition in CycleJS, choo, React and Angular2](http://blog.krawaller.se/posts/composition-in-cyclejs-choo-react-and-angular2)
- :book: [Stupidly smart components in choo](http://blog.krawaller.se/posts/stupidly-smart-components-in-choo)

### Projects using choo

- [boxcar ★9](toddself/boxcar) - A choo-based grid/spreadsheet editor.
- [choo-sortable ★2](willkessler/choo-sortable) - Building sortable code with choo.
- [hacker-choo](https://github.com/mw222rs/hacker-choo) - Hacker Typer clone written in choo.
- [footprint-rechoo](https://github.com/npeihl/footprint-rechoo) - A choo rewrite of [footprint-review](http://github.com/sjcgis/footprint-review).
- [minidocs ★116](freeman-lab/minidocs) – A documentation site generator built with choo.
- [dataface ★11](timwis/dataface) - Desktop application to manage databases.
- [BlankUp ★29](HoverBaum/BlankUp-Electron) - Multiplatform markdown editor.
- [hackernews-choo ★27](kvnneff/hackernews-choo) - A Hacker News reader built with choo.
- [tic-tac-choo ★5](YerkoPalma/tic-tac-toe) - Progressive tic tac toe game, made with choo.
- [enviar ★28](timwis/enviar) - Chat interface for SMS / text messages.
- [kaktus ★328](kaktus/kaktus) - A new minimalistic web browser, built on `choo` and IndexedDB.
- [civicdr.org ★2](CiviCDR/civicdr.org) - Website for [CiviCDR](https://civicdr.org/).
- [nekocafe ★11](notenoughneon/nekocafe) - Web chat room :cat: :speech_balloon:.

### License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Yerko Palma](https://github.com/YerkoPalma) has waived all copyright and related or neighboring rights to this work.
---
<p align="center">
	This list is a copy of <a href="YerkoPalma/awesome-choo">YerkoPalma/awesome-choo</a> with ranks
</p>
