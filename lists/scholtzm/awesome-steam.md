---
layout: default
title: Awesome Rank for scholtzm/awesome-steam
---

<p align="center">
	This list is a copy of <a href="https://github.com/scholtzm/awesome-steam">scholtzm/awesome-steam</a> with ranks
</p>
---
# Awesome Steam [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg) ★59088](https://github.com/sindresorhus/awesome)

> A curated list of [packages](#packages) and [resources](#resources) regarding [Steam](http://store.steampowered.com/) development.

*Please read the [contribution guidelines](https://github.com/scholtzm/awesome-steam/blob/master/CONTRIBUTING.md) before contributing.*

The purpose of this document is to provide a quick overview over existing packages (libraries, modules etc.) and resources available regarding Steam client automation and WebAPI usage. Whenever you need to start a new project, have a look at the list of packages and see if there is anything useful for your use case. If you need technical details or tutorials, check out the resources section.

## Table of Contents

- [Packages](#packages)
  - [C#](#c)
  - [Node.js](#nodejs)
  - [PHP](#php)
  - [Go](#go)
  - [Python](#python)
  - [C++](#c-1)
  - [Java](#java)
  - [Objective-C](#objective-c)

- [Resources](#resources)
  - [General](#general-1)
  - [Tutorials](#tutorials)
  - [Posts](#posts)
  - [Standalone Tools](#standalone-tools)
  - [Discussion Boards](#discussion-boards)

## Packages

> 💡 Many of these package repositories provide helpful READMEs and wiki pages, which explain the usage and/or provide examples. Do not forget to check them out when using particular package.

### C&#35;

#### General

- [SteamKit2 ★952](https://github.com/SteamRE/SteamKit) - .NET library designed to interoperate with Valve's Steam network.
- [SteamAuth ★108](https://github.com/geel9/SteamAuth) - A C# library that provides vital Steam Mobile Authenticator functionality.
- [SteamBot ★906](https://github.com/Jessecar96/SteamBot) - Automated bot software for interacting with steam trade.
- [SteamTradeOffersBot ★32](https://github.com/waylaidwanderer/SteamTradeOffersBot) - SteamBot fork which focuses on trade offers.

#### Misc

- [BackpackLogin ★4](https://github.com/igeligel/BackpackLogin) - A .NET standard library for logging into backpack.tf using Steam credentials.
- [TeamFortressOutpostApi ★2](https://github.com/igeligel/TeamFortressOutpostApi) - A .NET standard class library which allows user to interact with TF2Outpost.

### Node.js

#### General

- [steam ★783](https://github.com/seishun/node-steam) - Interface directly with Steam servers from Node.js.
- [steam-client ★22](https://github.com/DoctorMcKay/node-steam-client) - API-compatible fork of node-steam's SteamClient.
- [steam-user ★152](https://github.com/DoctorMcKay/node-steam-user) - Feature-rich easy-to-use Steam client.
- [vapor ★81](https://github.com/scholtzm/vapor) - Lightweight Steam client framework.
- [steam-parentbot ★33](https://github.com/dragonbanshee/node-steam-parentbot) - Simple base class for a Steam bot.

#### WebAPI

- [steam-webapi ★8 ⏳1Y](https://github.com/DoctorMcKay/node-steam-webapi) - Complete WebAPI wrapper with support for extra HTTP headers sent by Steam.

#### Trading

- [steam-trade ★160 ⏳1Y](https://github.com/seishun/node-steam-trade) - Node.js wrapper around Steam live trading.
- [steam-tradeoffers ★262](https://github.com/Alex7Kom/node-steam-tradeoffers) - Steam Trade Offers for Node.js.
- [steam-tradeoffer-manager ★197](https://github.com/DoctorMcKay/node-steam-tradeoffer-manager) - Simple and sane Steam trade offer management.

#### Game Interaction

- [steam-gameserver ★4](https://github.com/DoctorMcKay/node-steam-gameserver) - Steam client handler for Gameserver and AnonGameserver account types.
- [tf2 ★22](https://github.com/DoctorMcKay/node-tf2) - Interact directly with TF2 game coordinator.
- [csgo ★183](https://github.com/joshuaferrara/node-csgo) - Interact directly with CS:GO game coordinator.
- [dota2](https://github.com/RJacksonm1/node-dota2) - Interact directly with Dota 2 game coordinator.

#### Community & Store Automation

- [steamcommunity ★162](https://github.com/DoctorMcKay/node-steamcommunity) - Interact with steamcommunity.com. Also allows to confirm trade offers.
- [steamstore ★21](https://github.com/DoctorMcKay/node-steamstore) - Interact with store.steampowered.com.
- [steam-weblogon ★22](https://github.com/Alex7Kom/node-steam-weblogon) - Retrieve SteamCommunity cookies if you are running Steam network client.
- [steam-web-api-key ★14 ⏳1Y](https://github.com/Alex7Kom/node-steam-web-api-key) - Automatically registers and retrieves Steam API key.
- [steam-parental ★3 ⏳1Y](https://github.com/Alex7Kom/node-steam-parental) - Disable parental lock.

#### Authentication

- [steam-login ★18](https://github.com/cpancake/steam-login) - Simple Connect / Express Steam authentication library.
- [passport-steam ★178](https://github.com/liamcurry/passport-steam) - Steam (OpenID) authentication strategy for Passport and Node.js.
- [meteor-accounts-steam ★9](https://github.com/scholtzm/meteor-accounts-steam) - Steam OpenID integration for Meteor Accounts.

#### Misc

- [steam-resources ★16](https://github.com/seishun/node-steam-resources) - Steam's enums, protobufs and structs.
- [steam-crypto ★13 ⏳1Y](https://github.com/seishun/node-steam-crypto) - Node.js implementation of Steam crypto.
- [steam-groups ★17 ⏳1Y](https://github.com/scholtzm/node-steam-groups) - Custom node-steam handler which provides group functions.
- [steamid ★27](https://github.com/DoctorMcKay/node-steamid) - SteamID usage and conversion made easy.
- [steam-totp ★92](https://github.com/DoctorMcKay/node-steam-totp) - Easily generate 2FA codes used by Steam.
- [steam-chat-bot ★71](https://github.com/Steam-Chat-Bot/node-steam-chat-bot) - Simplified interface for a steam chat bot.
- [vdf ★14 ⏳1Y](https://github.com/RJacksonm1/node-vdf) - vdf to object and vice versa.
- [steamrep ★8](https://github.com/scholtzm/node-steamrep) - Check user's SteamRep reputation.
- [reptf ★1](https://github.com/scholtzm/node-reptf) - Check user's rep.tf reputation.

### PHP

- [SteamCommunity ★34](https://github.com/waylaidwanderer/PHP-SteamCommunity) - A PHP library for interacting with the Steam Community website.
- [SteamAuthentication ★241](https://github.com/SmItH197/SteamAuthentication) - Steam OpenID authentication with PHP.
- [SteamAuthOOP ★14](https://github.com/BlackCetha/SteamAuthOOP) - An object-oriented alternative to SteamAuthentication.
- [steam-api ★54](https://github.com/DaMitchell/steam-api-php) - A PHP wrapper for the Steam API.
- [steamid ★3](https://github.com/DoctorMcKay/php-steamid) - SteamID class for PHP.
- [steam-totp ★9](https://github.com/DoctorMcKay/php-steam-totp) - PHP library to deal with Steam's proprietary TOTP algorithm.

### Go

- [steam ★143](https://github.com/Philipp15b/go-steam) - Steam's protocol in Go.
- [steam-mobileauth ★12 ⏳1Y](https://github.com/YellowOrWhite/go-steam-mobileauth) - Port of SteamAuth in Go.

### Python

#### General

- [steam ★83](https://github.com/ValvePython/steam) - Module for various interactions with Steam.
- [PySteamKit](https://bitbucket.org/AzuiSleet/pysteamkit) - Python port of SteamKit.
- [steamodd ★58 ⏳1Y](https://github.com/Lagg/steamodd) - Steam tools library.
- [steampy ★30](https://github.com/bukson/steampy) - Fully automated Steam trade offers library with SteamGuard support.

#### Misc

- [backpack.py ★2](https://github.com/Zwork101/backpack.py) - Library for interacting with backpack.tf.

### C++

- [SteamPP ★53](https://github.com/seishun/SteamPP) - C++ library to interoperate with Steam servers.

### Java

- [SteamKit-Java ★31 ⏳4Y](https://github.com/Top-Cat/SteamKit-Java) - Java port of SteamKit.

### Objective-C

- [SteamAuth ★3 ⏳2Y](https://github.com/michaelchum/SteamAuth) - An iOS wrapper around Steam's OpenID login.

## Resources

### General

- [Steam WebAPI @ ValveSoftware](https://developer.valvesoftware.com/wiki/Steam_Web_API)
- [Steam WebAPI @ TF2 Wiki](https://wiki.teamfortress.com/wiki/WebAPI)
- [Steam WebAPI Documentation by xpaw](https://lab.xpaw.me/steam_api_documentation.html)
- [Steam as OpenID Provider](http://steamcommunity.com/dev)
- [Steam API Key Registration](http://steamcommunity.com/dev/apikey)
- [Steam Error Codes](https://steamerrors.com/) - List of `EResult` codes with possible explanations.

### Tutorials

- [Creating a Steam Trade Bot with Node.js](https://firepowered.org/developer/create-a-steam-trade-bot-with-nodejs-iojs-updated-for-node-steam-v1-0/)
- [Charred's node.js Guide to Steam Bots ★27](https://github.com/charredgrass/nodejs-bot-guide)
- [Retrieving 2FA Keys from iOS Device](http://forums.backpack.tf/index.php?/topic/45995-guide-how-to-get-your-shared-secret-from-ios-device-steam-mobile/)

### Posts

- [Item IDs Explained](https://dev.doctormckay.com/topic/332-identifying-steam-items/)
- [Everything Related to Escrow](https://www.reddit.com/r/SteamBot/comments/3udhkd/everything_related_to_escrow/)
- [Understanding Avatar Hash](https://www.reddit.com/r/SteamBot/comments/3cv6k7/problem_downloading_an_avatar_using/)

### Standalone Tools

- [NetHook2](https://github.com/SteamRE/SteamKit/tree/master/Resources/NetHook2) - Intercept Steam client's network messages.
- [NetHook2 Analyzer](https://github.com/SteamRE/SteamKit/tree/master/Resources/NetHookAnalyzer2) - Inspect messages dumped by NetHook2.
- [steam-auth-web-util](http://scholtzm.github.io/steam-auth-web-util/) - Generate 2FA codes directly in your web browser.
- [SteamDesktopAuthenticator ★577](https://github.com/Jessecar96/SteamDesktopAuthenticator) - Desktop implementation of Steam's mobile authenticator app.

### Discussion Boards

- [/r/SteamBot](https://www.reddit.com/r/SteamBot)
- [/r/SteamBot Discord](https://discord.gg/0i5X3oDHJbDUsiGC)
- [/r/nodesteam](https://www.reddit.com/r/nodesteam)
- [DoctorMcKay's Dev Forum](https://dev.doctormckay.com/)
- [node-steam-forum ★42 ⏳1Y](https://github.com/steam-forward/node-steam-forum)

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the author and contributors of this text have waived all copyright and related or neighboring rights to this work.
---
<p align="center">
	This list is a copy of <a href="https://github.com/scholtzm/awesome-steam">scholtzm/awesome-steam</a> with ranks
</p>
