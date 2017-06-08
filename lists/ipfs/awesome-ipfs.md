<h1 align="center">
Ranked awesome lists, all in one place
</h1>
<p align="center">
	This list is a copy of <a href="ipfs/awesome-ipfs">ipfs/awesome-ipfs</a> with ranks
</p>
---
# Awesome IPFS [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg) ★59088](sindresorhus/awesome)

[![](https://img.shields.io/badge/made%20by-Protocol%20Labs-blue.svg?style=flat-square)](http://ipn.io)
[![](https://img.shields.io/badge/project-IPFS-blue.svg?style=flat-square)](http://ipfs.io/)
[![](https://img.shields.io/badge/freenode-%23ipfs-blue.svg?style=flat-square)](http://webchat.freenode.net/?channels=%23ipfs)

> Useful resources for using [IPFS](https://ipfs.io) and building things on top of it

_This list is for projects, tools, or pretty much any things related to IPFS that
are totally_ **awesome**_. This is for products which are already awesome - if
you have plans for cool stuff to do with IPFS, you should build it, and then
link it here. If you have an idea for an awesome thing to do with IPFS, a good
place to ask about it might be in [ipfs/apps ★38](ipfs/apps) or
[ipfs/notes ★108](ipfs/notes)._

## Table of Contents

- [Apps](#apps)
  - [Single page Webapps](#single-page-webapps)
- [Tools](#tools)
- [Videos](#videos)
- [Archives](#archives)
- [Articles and Press](#articles-and-press)
  - [Articles independently hosted on IPFS](#articles-independently-hosted-on-ipfs)
- [Discussions](#discussions)
- [Contribute](#contribute)
  - [Want to hack on IPFS?](#want-to-hack-on-ipfs)
- [License](#license)

## Apps

* [akasha](http://akasha.world/) - A Next-Generation Social Media Network, powered by Ethereum and embedded into IPFS.
* [Beaker Browser](https://beakerbrowser.com/) - An experimental P2P browser that can view files over HTTP, IPFS, and [Dat](https://datproject.org/).
* [beets ★5884](beetbox/beets) - Beets has a plugin which allows for easy sharing of music libraries using IPFS
* [Boards](https://ipfs.io/ipns/boards.ydns.eu) - Distributed social platform that runs in the browser. [GitHub ★133](fazo96/ipfs-boards)
* [Cohort ★15](zignig/cohort) - A golang app to preset a threejs interface and get all of its assets out of IPFS.
* [dapple](https://github.com/nexusdev/dapple) - Dapple is a Solidity developer multitool designed to manage the growing complexity of interconnected smart contract systems.
* [digx](https://www.dgx.io/) - Digix is an asset-tokenisation platform built on Ethereum and IPFS.
* [Ethlance](http://ethlance.com) - First completely decentralised job market platform built on Ethereum and IPFS. [Github ★95](madvas/ethlance)
* [git-ipfs-rehost ★69](whyrusleeping/git-ipfs-rehost) - A script to rehost your git repos in ipfs.
* [Global Upload](https://globalupload.io/) - File transportation service for IPFS, upload files to the future of distributed web.
* [HydrusNetwork ★192](hydrusnetwork/hydrus) - A booru-style media tagging application with a multitude of features, recently added basic ipfs support.
* [InterPlanetary Wayback ★66](oduwsdl/ipwb) - Web Archive (WARC) indexing and replay using IPFS.
* [Interplanetary Wiki ★44 ⏳1Y](jamescarlyle/ipfs-wiki) - Wiki built on top of IPFS
* [IPFS Event Drop ★5 ⏳2Y](travisperson/ipfs-event-drops) - An app that allows for improved visualization of ipfs events.
* [ipfs.ink](https://ipfs.ink) - Publish and render markdown essays to and from ipfs. [GitHub ★7](kpcyrd/ipfs.ink)
* [ipfs-search](http://ipfs-search.com) - Search engine for files and directories on IPFS.
* [ipfs-share ★21 ⏳2Y](rameshvarun/ipfs-share) - Pastebin/Image host/File sharing application
* [ipfs-userscript ★5](loadletter/ipfs-redirect-userscript) -  Browser userscript for redirecting gateway.ipfs.io links to your local gateway. This should work on any browser that hasn’t had an extension written for it yet and has support for userscripts.
* [ipfs.pics](https://ipfs.pics) - Upload and share pics. [GitHub ★775](ipfspics/ipfspics-server)
* [IPFSBin ★83 ⏳1Y](victorbjelkholm/ipfsbin) - Pastebin clone build.
* [markup.rocks ★13 ⏳1Y](davidar/markup.rocks) - Pandoc-based markup editor/previewer/converter, ported to IPFS. [Example](https://ipfs.io/ipfs/QmWPgJnUGLB1LPh9KMG9LEN4LVu5e17TwkEtcmTWdNn9V6/#/ipfs/QmfQ75DjAxYzxMP2hdm6o4wFwZS5t7uorEZ2pX9AKXEg2u)
* [Orbit](https://github.com/haadcode/orbit) - Distributed, peer-to-peer chat application on IPFS.
* [Philes](http://philes.co) - Philes is a browser-based, IPFS-powered distributed notepad (editor & viewer).
* [Playback](https://mafintosh.github.io/playback/) - IPFS playback support. This allows casting a video in IPFS to a Chromecast.
* [ujo](http://ujomusic.com/) - A blockchain marketplace for musicians.
* [uport](https://uport.me/#home) - Uport is a mobile, self-sovereign identity and key management system, built on the Ethereum blockchain.

### Single page Webapps

These are narrowly-scoped, little JS "apps" deployed through IPFS.

- [a markdown renderer](https://github.com/ipfs/examples/tree/master/webapps/markdown-viewer) - [example](
  https://ipfs.io/ipfs/QmSrCRJmzE4zE1nAfWPbzVfanKQNBhp7ZWmMnEdbiLvYNh/mdown#/ipfs/QmfQ75DjAxYzxMP2hdm6o4wFwZS5t7uorEZ2pX9AKXEg2u
)
- [a js video player](https://github.com/ipfs/examples/tree/master/webapps/play) - [example](
  https://ipfs.io/ipfs/QmVc6zuAneKJzicnJpfrqCH9gSy6bz54JhcypfJYhGUFQu/play#/ipfs/QmTKZgRNwDNZwHtJSjCp6r5FYefzpULfy37JvMt9DwvXse
)
- [a qr-code renderer](https://github.com/ipfs/examples/tree/master/webapps/qr-render) - [example](
  https://ipfs.io/ipfs/QmccqhJg5wm5kNjAP4k4HrYxoqaXUGNuotDUqfvYBx8jrR/qr#enter%20text%20here
)
- [hasteIPFS](https://ipfs.io/ipns/bin.ipfs.ovh/) - IPFS based code bin. (Read only for now)
- [Gorilla REPL viewer ★3 ⏳1Y](keorn/ipfs-gorilla-repl) - [example](https://ipfs.io/ipfs/QmRNUauWDvZFkAp1Bw3kAode3jT8aH2vx7LYzbS7H6R3Mg/view.html?path=/ipfs/QmbRdyLXiFWrKc5hW1NbvpUxF9tLovWCPgiz4BDhjD9k3j)

## Tools

* [cachewarmer ★28](BrendanBenshoof/cachewarmer) - Donate ipfs gateways to cache other people's content
* [git-remote-ipfs ★90](cryptix/git-remote-ipfs) - push/pull repositories from/to IPFS
* [http2ipfs ★19 ⏳1Y](jbenet/http2ipfs-web) - This is a simple webtool to add URLs to an IPFS node.
* [ipcat ★3 ⏳1Y](noffle/ipcat) - :cat2: Retrieve IPFS object data and send it to stdout.
* [ipfs-chrome-station ★39](fbaiodias/ipfs-chrome-station) - Chrome extension to redirect ipfs.io traffic to local gateway
* [ipfs-chrome-extension ★53 ⏳1Y](dylanPowers/ipfs-chrome-extension) - Chrome extension to redirect ipfs.io traffic to local gateway
* [ipfs-firefox-addon](https://github.com/lidel/ipfs-firefox-addon) - Firefox addon to provide access to IPFS via local gateway
* [ipfs-linux-service ★31 ⏳2Y](dylanPowers/ipfs-linux-service) - IPFS Linux Init Daemon
* [ipfs-paste ★16 ⏳1Y](jbenet/ipfs-paste) - Paste stdin and clipboard to IPFS
* [ipfs-screencap ★25](jbenet/ipfs-screencap) - Capture screenshots, publish them to IPFS, and copy the link to the clipboard.
* [ipfscrape ★95](victorbjelkholm/ipfscrape) - Scrape a webpage with all assets and put it in IPFS
* [ipget ★56](ipfs/ipget) - :satellite: wget for IPFS: retrieve files over IPFS and save them locally.
* [ipscend ★130](diasdavid/ipscend) - Tool for hosting web apps and static websites in IPFS
* [pinbot ★15](whyrusleeping/pinbot) - Pin content via IRC
* [ipfs-mount ★10](richardschneider/net-ipfs-mount) - Mount IPFS as a mapped drive on Windows

## Videos

* [IPFS Alpha - Why we must redistribute the web](https://www.youtube.com/watch?v=skMTdSEaCtA) (YouTube)
* [Juan Benet at Stanford 2015](https://www.youtube.com/watch?v=HUVmypx9HGI) (YouTube)
* [Juan Benet at Fullstack Fest 2016](https://www.youtube.com/watch?v=jONZtXMu03w) (YouTube) ([IPFS Mirror](https://ipfs.io/ipfs/QmX8LDhDSYdX3xG6cHFUybXLDSuvo9Lz6wF5NU3UVmJRnB))

## Archives

## Articles and Press

* 2017-03-31: [Using IPFS for IoT Communications](https://medium.com/@chrismatthieu/using-ipfs-for-iot-communications-b49c2139783a) (medium.com)
* 2016-09-12: [IPFS: The Internet Democratised](https://medium.com/@tonywillenberg/web-3-0-a-truly-democratised-internet-f4b06cb4077b) (medium.com)
* 2016-05-20: [Changelog Podcast](https://changelog.com/204/) (changelog.com)
* 2015-09-10: [First Steps Toward Implementing Distributed Permanent Web With IPFS](https://hacked.com/first-steps-toward-implementing-distributed-permanent-web-ipfs/) (Hacked.com)
* 2015-09-13: [Introduction to IPFS](http://whatdoesthequantsay.com/2015/09/13/ipfs-introduction-by-example) (whatdoesthequantsay.com)
* 2015-09-18: [The InterPlanetary File System Wants to Create a Permanent Web](http://motherboard.vice.com/read/the-interplanetary-file-system-wants-to-create-a-permanent-web) (Vice // Motherboard)
* 2015-11-01: [Eris + IPFS](http://db.erisindustries.com/distributed%20business/2015/11/01/eris-and-ipfs/) (erisindustries.com)

### Articles independently hosted on IPFS
* 2015-09-08: [HTTP is obsolete. It's time for the distributed, permanent web](https://ipfs.io/ipfs/QmNhFJjGcMPqpuYfxL62VVB9528NXqDNMFXiqN5bgFYiZ1/its-time-for-the-permanent-web.html)
* [Downloading nodejs versions with nvm/n over IPFS](https://ipfs.io/ipfs/QmTkzDwWqPbnAh5YiV5VwcTLnGdwSNsNTn2aDxdXBFca7D/example#/ipfs/QmUx363UFtgiQqkHHsPK3TSDmwoALDo2hrbMWbcxjH2vFc) (ipfs.io)

## Discussions

* [CRDTs discussion](https://github.com/ipfs/notes/issues/23)

## Contribute

Please add (or remove) stuff from this list if you see anything awesome! [Open an issue](https://github.com/ipfs/awesome-ipfs/issues) or a PR.

### Want to hack on IPFS?

[![](https://cdn.rawgit.com/jbenet/contribute-ipfs-gif/master/img/contribute.gif)](https://github.com/ipfs/community/blob/master/contributing.md)

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)
---
<p align="center">
	This list is a copy of <a href="ipfs/awesome-ipfs">ipfs/awesome-ipfs</a> with ranks
</p>
<script>
  (function(i,s,o,g,r,a,m){i['GoogleAnalyticsObject']=r;i[r]=i[r]||function(){
  (i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),
  m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)
  })(window,document,'script','https://www.google-analytics.com/analytics.js','ga');

  ga('create', 'UA-100705027-1', 'auto');
  ga('send', 'pageview');

</script>
