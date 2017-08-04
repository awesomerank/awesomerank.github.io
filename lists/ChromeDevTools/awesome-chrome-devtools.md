---
layout: default
title: Awesome Rank for ChromeDevTools/awesome-chrome-devtools
---

<p align="center">
	This list is a copy of <a href="https://github.com/ChromeDevTools/awesome-chrome-devtools">ChromeDevTools/awesome-chrome-devtools</a> with ranks
</p>
---
# Awesome chrome-devtools [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg) ★62884](https://github.com/sindresorhus/awesome)

> Awesome tooling and resources in the Chrome DevTools ecosystem

### Learning
- [Dev Tips](https://umaar.com/dev-tips/) - Large collection of tips as animated gifs.

#### DevTools as an IDE
- [Chrome DevTools App ★1407 ⏳1Y](https://github.com/auchenberg/chrome-devtools-app) - Standalone app which can inspect various targets.
- [DevTools Remote ★525](https://github.com/auchenberg/devtools-remote) - Remotely debug someone else's browser.
- [DevTools Snippets ★1213](https://github.com/bahmutov/code-snippets) - Collection of snippets.

---

### DevTools tooling and ecosystem

#### Object formatting
- [immutable-devtools ★508 ⏳1Y](https://github.com/andrewdavey/immutable-devtools) - Custom formatter for Immutable-js values.

#### Network Inspection
- [betwixt ★3514](https://github.com/kdzwinel/betwixt) - System level network proxy, providing inspection via Network panel

#### CPU profile
- [JSCLegacyProfiler/json2trace](https://github.com/facebook/react-native/blob/master/JSCLegacyProfiler/json2trace) - Converts Safari's JavaScriptCore profiler output into `.cpuprofile`
- [call-trace ★10 ⏳1Y](https://github.com/brendankenny/call-trace) - Can instrument your JS with hooks, and then generate a `.cpuprofile`  of the of the complete (non-sampled) execution. View either time or call counts.
- [cpuprofilify ★110](https://github.com/thlorenz/cpuprofilify) - Converts output of various profiling/sampling tools to the `.cpuprofile` format.
- [Wishbone python framework](http://wishbone.readthedocs.org/en/develop/miscellaneous.html#profiling) - Profiling data can export as `.cpuprofile`.

#### Multimedia
- [snapline ★276 ⏳1Y](https://github.com/pmdartus/snapline) - Converts timeline screenshots to gif.

#### Timeline, Tracing & Profiling
- [DevTools Timeline Viewer](https://chromedevtools.github.io/timeline-viewer/) - Share URLs of your timeline recordings.

#### Chrome Debugger integration with Editors
- [VS Code - Debugger for Chrome ★727](https://github.com/Microsoft/vscode-chrome-debug) - Chrome Debugger for Visual Studio Code
- [Sublime Web Inspector](http://sokolovstas.github.io/SublimeWebInspector/) - Debug Javascript right in the Sublime Text editor
- [WebStorm & JetBrains Chrome Extension](https://www.jetbrains.com/help/webstorm/2017.1/configuring-javascript-debugger-and-jetbrains-chrome-extension.html) - The WebStorm IDE can debug JavaScript, view the DOM tree, and edit HTML, CSS and JS live.

---

## Chrome DevTools Protocol
- [DevTools Protocol API Docs](https://chromedevtools.github.io/devtools-protocol/) - Easy browsable UI for exploring the protocol's domains, methods and events
- [ChromeDevTools/devtools-protocol ★76](https://github.com/chromedevtools/devtools-protocol) - Issue tracker for protocol bugs
- [Remote Debug Gateway ★54 ⏳1Y](https://github.com/RemoteDebug/remotedebug-gateway) - Allows you to connect a client to multiple browsers at once.
- [RemoteDebug](https://github.com/RemoteDebug) - Initiative to normalize debugging protocols across today's browsers.
- [ChromeDriver](https://sites.google.com/a/chromium.org/chromedriver/) - The official Selenium/WebDriver implementation for Chrome is implemented on top of the DevTools Protocol.

#### Protocol driver libraries (in various languages)
- JavaScript/Node.js: [chrome-remote-interface ★1732](https://github.com/cyrus-and/chrome-remote-interface) - The most-used JavaScript API for the protocol
- TypeScript/Node.js: [chrome-debugging-client ★25](https://github.com/krisselden/chrome-debugging-client) - A TypeScript async/await-friendly debugging client
- Java: [cdp4j ★44](https://github.com/webfolderio/cdp4j) - Java library for CDP
- Python: [chromote ★247](https://github.com/iiSeymour/chromote) - Simple wrapper to drive Google Chrome from Python
- Python: [PyChromeDevTools ★10](https://github.com/marty90/PyChromeDevTools) - Python wrapper for Google Chrome Dev Protocol
- Go: [chromedp ★1363](https://github.com/knq/chromedp) - High level actions and tasks for driving browsers via the Chrome Debugging Protocol
- Go: [cdp ★29](https://github.com/mafredri/cdp) - A Golang library for the protocol
- Go: [gcd ★115](https://github.com/wirepair/gcd) - A different client library in Go
- Go: [godet ★149](https://github.com/raff/godet) - Also different, also Go.
- C#/dotnet: [chrome-dev-tools ★11](https://github.com/BaristaLabs/chrome-dev-tools) - Protocol wrapper generator that can be customized by editing handlebars templates. Includes .Net Core template.

#### Developing with the protocol
- [chrome-remote-interface Wiki](https://github.com/cyrus-and/chrome-remote-interface/wiki) - Many useful recipes
- [Getting Started with Headless Chrome](https://developers.google.com/web/updates/2017/04/headless-chrome)
- [crmux ★86](https://github.com/sidorares/crmux) - Multiplexes protocol connections.
- [automated-chrome-profiling ★662](https://github.com/paulirish/automated-chrome-profiling#readme) - Node.js recipes for automating JavaScript profiling in Chrome.
- [chrome-devtools-frontend](https://www.npmjs.com/package/chrome-devtools-frontend) - Mirror of the frontend that ships in Chrome.
- [chrome-timeline-model](https://www.npmjs.com/package/devtools-timeline-model) - Uses frontend as lib to process profiling data.
- [crconsole ★173](https://github.com/sidorares/crconsole) - Terminal based chrome console and debugger.

#### Browser Adapters
- [Remote Debug Firefox adapter ★109 ⏳1Y](https://github.com/RemoteDebug/remotedebug-firefox-adapter) - Translates Firefox's devtools protocol to the CDP
- [ios-webkit-debug-proxy ★2955](https://github.com/google/ios-webkit-debug-proxy) - Exposes Mobile Safari & UIWebView instances via the CDP.
- [Remote Debug iOS WebKit adapter ★265](https://github.com/RemoteDebug/remotedebug-ios-webkit-adapter) - Builts upon ios-webkit-debug-proxy and translates WebKit's Remote Debugging Protocol API to the CDP
- [IE Diagnostics Adapter ★532 ⏳1Y](https://github.com/Microsoft/IEDiagnosticsAdapter) - Protocol adaptor for Microsoft IE 10/11 to CDP.
- [Edge Diagnostics Adaptor](https://github.com/Microsoft/edge-diagnostics-adaptor) - Protocol adaptor that enables tools to debug Edge using the CDP.

### Using DevTools frontend with other targets/platforms

##### Android
- [Facebook Stetho ★8138](https://github.com/facebook/stetho) - Native Android debugging with Chrome DevTools

##### ClosureScript
- [Dirac ★467](https://github.com/binaryage/dirac) - Debugging of ClojsureScript

##### Lua
- [Mare ★188](https://github.com/muzuiget/mare) - Lua debugging with Chrome DevTools

#### iOS
- [PonyDebugger ★5428](https://github.com/square/PonyDebugger) - Remote network and data debugging iOS apps with Chrome DevTools

##### Go
- [go-debugger-devtools](https://github.com/allada/go-debugger-devtools)

##### Node.js
- [Debugging Node.js with Chrome DevTools](https://medium.com/@paul_irish/debugging-node-js-nightlies-with-chrome-devtools-7c4a1b95ae27) - Guide on using the full debugging and profiling support in Node v6.3+
- [devtool ★3720](https://github.com/Jam3/devtool) - Debug & profile Node.js apps with Chrome DevTools (using Electron).
- [buggerJS ★149](https://github.com/buggerjs/bugger) - Provides Chrome DevTools bindings for node.


---

## DevTools Extensions

#### Accessibility (A11y)
- [Chromelens](http://chromelens.xyz) - See how your web app will look to people with different types of vision and the path users will travel when tabbing through your page.

#### Workflow
- [Clockwork](https://chrome.google.com/webstore/detail/clockwork/dmggabnehkmmfmdffgajcflpdjlnoemp?hl=en) - View PHP application profiling data.
- [Emulated Device Lab](https://chrome.google.com/webstore/detail/emulated-device-lab/oaonfodocibcdobdeelbbfggjombamff) - Experiment with multiple devices being emulated at the same time.
- [RailsPanel](https://chrome.google.com/webstore/detail/railspanel/gjpfobpafnhjhbajcjgccbbdofdckggg?hl=en-US) - View Ruby on Rails application profiling data.
- [React Developer Tools](https://chrome.google.com/webstore/detail/react-developer-tools/fmkadmapgofadopljbjfkapdkoienihi) - Inspect the React component hierarchies.
- [EmberJS Inspector](https://chrome.google.com/webstore/detail/ember-inspector/bmdblncegkenkacieihfhpjfppoconhi) - Allows you to inspect EmberJS objects in your application.
- [VueJS Developer Tools ★4436](https://github.com/vuejs/vue-devtools) - Inspect VueJS components and manipulate their data.
- [Angular Batarang](https://chrome.google.com/webstore/detail/angularjs-batarang/ighdmehidhipcmcojjgiloacoafjmpfk) - Inspect an Angular application's scope and profile its data.
- [Augury](https://augury.angular.io)  - Debugging and Profiling for Angular 2 applications.
- [Marionette Inspector](https://chrome.google.com/webstore/detail/marionette-inspector/fbgfjlockdhidoaempmjcddibjklhpka) - Inspect a Marionette application's views, events, and live data.
- [Backbone Debugger](https://chrome.google.com/webstore/detail/backbone-debugger/bhljhndlimiafopmmhjlgfpnnchjjbhd) - Inspect a Backbone application's views, models, events, and routes.
- [App Inspector for Sencha](https://chrome.google.com/webstore/detail/app-inspector-for-sencha/pbeapidedgdpniokbedbfbaacglkceae) - Inspect a Sencha ExtJS/Touch application's component tree, data stores, events, and layouts.
- [Redux Devtools](https://chrome.google.com/webstore/detail/redux-devtools/lmhkpmbekcpmknklioeibfkpmmfibljd) - Inspect Redux with actions history, undo and replay.
- [Three.js](https://chrome.google.com/webstore/detail/threejs-editor-extension/fbgbekpggeldiacgjkacbkkcbjhmakea/) - Edit any three.js project.
- [Insight ★684 ⏳1Y](https://github.com/3Dparallax/insight) - A WebGL debugging toolkit which enables more productive WebGL development and more efficient WebGL applications.
- [BEM devtools ★36 ⏳1Y](https://github.com/escaton/bem-chrome-devtools) - Inspect BEM entities expressed in `i-bem` framework.

#### UX
- [DevTools Author](https://chrome.google.com/webstore/detail/devtools-author/egfhcfdfnajldliefpdoaojgahefjhhi) - A selection of themes to modify parts of DevTools related to authoring web applications.
- [Zero Dark Matrix](https://chrome.google.com/webstore/detail/devtools-theme-zero-dark/bomhdjeadceaggdgfoefmpeafkjhegbo) - Dark theme for Chrome Developer Tools.

#### Performance
- [Chrome React Perf](https://chrome.google.com/webstore/detail/react-perf/hacmcodfllhbnekmghgdlplbdnahmhmm) - An Operation Interface for react-addons-perf Package.

#### Testing
- [UI-automation-chrome-extension](https://chrome.google.com/webstore/detail/ui-automation/aacdhbhfmngpoiinjmphdcpalpdcmbpf/) - Provides simple DOM selectors with Java code snippets so you can write automated Selenium tests faster.

---
<p align="center">
	This list is a copy of <a href="https://github.com/ChromeDevTools/awesome-chrome-devtools">ChromeDevTools/awesome-chrome-devtools</a> with ranks
</p>
