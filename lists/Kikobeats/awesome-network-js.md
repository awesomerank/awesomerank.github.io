<h1 align="center">
Ranked awesome lists, all in one place
</h1>
<p align="center">
	This list is a copy of <a href="Kikobeats/awesome-network-js">Kikobeats/awesome-network-js</a> with ranks
</p>
---
# Awesome JavaScript Network [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg) ★321](https://github.com/Kikobeats/awesome-network-js) [![Build Status](https://img.shields.io/travis/Kikobeats/awesome-network-js/master.svg?style=flat-square)](https://travis-ci.org/Kikobeats/awesome-network-js) [![Donate](https://img.shields.io/badge/donate-paypal-blue.svg?style=flat-square)](https://paypal.me/kikobeats)

> A 🎩 list of network layer resources written pure JS.

## High level

> Based, at least, in a CLI interface.

* [airpaste ★600 ⏳2Y](https://github.com/mafintosh/airpaste) – 1-1 network pipe that auto discovers other peers using mdns.
* [blecat ★92 ⏳2Y](https://github.com/mafintosh/blecat) – 1-1 pipe over bluetooth low energy.
* [deejay ★106 ⏳1Y](https://github.com/mafintosh/deejay) – Music player that broadcasts to everyone on the same network.
* [dhtkv ★45 ⏳1Y](https://github.com/maxogden/dhtkv) – CLI for storing arbitrary key/value data in the bittorrent mainline DHT.
* [gun ★4678](https://github.com/amark/gun) – A realtime, decentralized, offline-first, graph database engine.
* [hyperpipe ★91](https://github.com/mafintosh/hyperpipe) – Distributed input/output pipe.
* [instant.io](https://github.com/feross/instant.io) – Streaming file transfer over WebTorrent.
* [ipp-printer ★267 ⏳1Y](https://github.com/watson/ipp-printer) – Create a printer on your network.
* [peercast ★327 ⏳2Y](https://github.com/mafintosh/peercast) – Like peerflix but for Chromecast.
* [peerflix ★4253](https://github.com/mafintosh/peerflix) – Streaming torrent client.
* [peervisionary ★37 ⏳1Y](https://github.com/mafintosh/peervisionary) – Stream p2p content over your local network.
* [peerwiki ★255 ⏳2Y](https://github.com/mafintosh/peerwiki) – browse all of wikipedia using bittorrent.
* [screencat ★1951 ⏳1Y](https://github.com/maxogden/screencat) – WebRTC screensharing app.
* [signalhub ★268](https://github.com/mafintosh/signalhub) – Simple signalling server that can be used to coordinate handshaking with webrtc or other fun stuff.
* [torrent-mount ★1071 ⏳2Y](https://github.com/mafintosh/torrent-mount) – Mount a torrent (or magnet link) as a filesystem in real time using torrent-stream and fuse.
* [webcat ★339](https://github.com/mafintosh/webcat) – pipe across the web using WebRTC.
* [websocketd ★8053](https://github.com/joewalnes/websocketd) – Turn any program that uses stdin/stdout into a WebSocket server.
* [webtorrent](https://github.com/feross/webtorrent) – BitTorrent over WebRTC.
* [wifi-triangulate ★46 ⏳1Y](https://github.com/watson/wifi-triangulate) – Finds your current position on planet earth using the wifi access point.

## Protocols

> Implementation of protocols specs in pure javascript.

* [airswarm ★104 ⏳1Y](https://github.com/mafintosh/airswarm) – Network swarm that automagically discovers other peers on the network using multicast dns.
* [bittorrent-dht](https://github.com/feross/bittorrent-dht) – BitTorrent DHT protocol implementation.
* [bittorrent-protocol](https://github.com/feross/bittorrent-protocol) – BitTorrent peer wire protocol implementation.
* [bittorrent-swarm](https://github.com/feross/bittorrent-swarm) – BitTorrent "swarm" implementation.
* [bittorrent-tracker](https://github.com/feross/bittorrent-tracker) – BitTorrent tracker (client & server) implementation
* [bonjour ★166](https://github.com/watson/bonjour) – A Bonjour/Zeroconf protocol implementation.
* [castv2 ★336](https://github.com/thibauts/node-castv2) – An implementation of the Chromecast CASTV2 protocol.
* [dht-rpc ★45](https://github.com/mafintosh/dht-rpc) – Make RPC calls over a [Kademlia](https://pdos.csail.mit.edu/~petar/papers/maymounkov-kademlia-lncs.pdf) based DHT.
* [dns-discovery ★117](https://github.com/mafintosh/dns-discovery) – Discovery peers in a distributed system using regular dns and multicast dns.
* [hypercore ★498](https://github.com/mafintosh/hypercore) – A p2p network for distributing and replicating static feeds of binary data.
* [ipfs ★256](https://github.com/ipfs/js-ipfs-api) – The InterPlanetary File System, a new peer-to-peer hypermedia protocol.
* [k-bucket ★65](https://github.com/tristanls/k-bucket) – Kademlia DHT K-bucket implementation as a binary tree.
* [k-rpc](https://github.com/mafintosh/k-rpc) – Implementation of the k-rpc protocol used the BitTorrent DHT. Also see [k-rpc-socket ★18](https://github.com/mafintosh/k-rpc-socket).
* [mdns ★615](https://github.com/agnat/node_mdns) – mdns/zeroconf/bonjour service discovery.
* [multicast-dns ★168](https://github.com/mafintosh/multicast-dns) – Low level multicast-dns implementation.
* [peervision ★84 ⏳1Y](https://github.com/mafintosh/peervision) – Live p2p streaming protocol.
* [polo ★185 ⏳2Y](https://github.com/mafintosh/polo) – A zero configuration service discovery module.
* [rtsp-server ★16 ⏳1Y](https://github.com/watson/rtsp-server) – A low level module for creating RTSP servers.
* [utp-native ★51](https://github.com/mafintosh/utp-native) – micro transport protocol, a network protocol similar to tcp that runs on top of udp.

## Modules

> Do one thing well.

* [airplay-server ★184](https://github.com/watson/airplay-server) – A low level AirPlay server.
* [castnow ★74](https://github.com/xat/chromecast-player) – simple chromecast player.
* [discovery-swarm](https://github.com/mafintosh/discovery-swarm) – A network swarm that uses [discovery-channel](https://github.com/maxogden/discovery-channel) to find peers. Also check [webrtc-swarm ★155](https://github.com/mafintosh/webrtc-swarm).
* [dns-packet](https://github.com/mafintosh/dns-packet) – Abstract-encoding compliant module for encoding / decoding DNS packets. Also see [dns-socket ★46](https://github.com/mafintosh/dns-socket).
* [etcdjs ★47](https://github.com/mafintosh/etcdjs) – Low level etcd v2 client written in Javascript with failover support.
* [geocode-wifi ★24 ⏳1Y](https://github.com/watson/geocode-wifi) – Get yours latitude/longitude based on your wifi access point.
* [hash-to-port ★22 ⏳1Y](https://github.com/mafintosh/hash-to-port) – Hash a value to a valid port.
* [ip-packet ★22 ⏳1Y](https://github.com/mafintosh/ip-packet) – Encode/decode raw ip packets.
* [magnet-uri](https://github.com/feross/magnet-uri) – Parse a magnet URI and return an object of keys/values.
* [network-address ★50](https://github.com/mafintosh/network-address) – Get the local network address of your machine.
* [network-simulator ★40 ⏳1Y](https://github.com/substack/network-simulator) – Simulate a low-level computer network.
* [rtsp-stream ★32 ⏳1Y](https://github.com/watson/rtsp-stream) - A transport agnostic RTSP serial multiplexer module for Node.
* [simple-peer ★1066](https://github.com/feross/simple-peer) – Simple WebRTC video/voice and data channels.
* [simple-websocket ★59](https://github.com/feross/simple-websocket) – Simple, EventEmitter API for WebSockets.
* [torrent-discovery](https://github.com/feross/torrent-discovery) – Discover BitTorrent and WebTorrent peers.
* [torrent-stream ★1366](https://github.com/mafintosh/torrent-stream) – The low level streaming torrent engine that peerflix uses.
* [udp-packet ★31 ⏳1Y](https://github.com/substack/udp-packet) – Encode/decode raw udp packets.
---
<p align="center">
	This list is a copy of <a href="Kikobeats/awesome-network-js">Kikobeats/awesome-network-js</a> with ranks
</p>

<script>
  (function(i,s,o,g,r,a,m){i['GoogleAnalyticsObject']=r;i[r]=i[r]||function(){
  (i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),
  m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)
  })(window,document,'script','https://www.google-analytics.com/analytics.js','ga');

  ga('create', 'UA-100705027-1', 'auto');
  ga('send', 'pageview');

</script>
