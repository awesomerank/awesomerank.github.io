---
layout: default
title: Awesome Rank for vsouza/awesome-ios
---

<p align="center">
	This list is a copy of <a href="https://github.com/vsouza/awesome-ios">vsouza/awesome-ios</a> with ranks
</p>
---
<img src="https://raw.githubusercontent.com/vsouza/awesome-ios/master/awesome_logo.png">

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg) ★69735](https://github.com/sindresorhus/awesome)
[![Join the chat at https://gitter.im/norio-nomura/SwiftTalkInJapanese](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/vsouza/awesome-ios?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
[![Build Status](https://api.travis-ci.org/vsouza/awesome-ios.svg?branch=master)](https://travis-ci.org/vsouza/awesome-ios)
[![Language](https://awesomelinkcounter.herokuapp.com/swift)]()
[![Language](https://awesomelinkcounter.herokuapp.com/objc)]()
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)

## We've launched our Newsletter!! ✅🚀📰
* [Check out our new website 🗞](http://weekly.awesomeios.com/)

# About
A curated list of awesome iOS frameworks, libraries, tutorials, Xcode extensions and plugins, components and much more.
The list is divided into categories such as Frameworks, Components, Testing and others, open source projects, free and paid services. There is no pre-established order of items in each category, the order is for contribution. If you want to contribute, please read the [guide](https://github.com/vsouza/awesome-ios/blob/master/.github/CONTRIBUTING.md).

Projects in Swift will be marked with :large_orange_diamond:, Swift Extensions will be marked with 🔶[e] and ⌚ for Apple Watch projects. Feel free to add your project.

# How to Use
Awesome-iOS is an amazing list for people who need a certain feature on their app, so the best ways to use are:
- Ask for help on our [Twitter](https://twitter.com/awesome_ios) or [Gitter Channel](https://gitter.im/vsouza/awesome-ios)
- Simply press <kbd>command</kbd> + <kbd>F</kbd> to search for a keyword
- Go through our *Content Menu*

## Content
- [About](#about)
- [How to Use](#how-to-use)
- [Getting Started](#getting-started)
- [Library and Frameworks](#libraries-and-frameworks)
    - [Analytics](#analytics)
    - [App Routing](#app--routing)
    - [Apple TV](#apple-tv)
    - [ARKit](#arkit)
    - [Authentication](#authentication)
    - [Bridging](#bridging)
    - [Cache](#cache)
    - [Charts](#charts)
    - [Code Quality](#code-quality)
        - [Linter](#linter)
    - [Color](#color)
    - [Command Line](#command-line)
    - [Concurrency](#concurrency)
    - [Core Data](#core-data)
    - [Database](#database)
    - [Data Structures / Algorithms](#data-structures--algorithms)
    - [Date & Time](#date--time)
    - [Debugging](#debugging)
    - [EventBus](#eventbus)
    - [Files](#files)
    - [Functional Programming](#functional-programming)
    - [Games](#games)
    - [Gesture](#gesture)
    - [Graphics](#graphics)
    - [Hardware](#hardware)
        - [Bluetooth](#bluetooth)
        - [Camera](#camera)
        - [Force Touch](#force-touch)
        - [iBeacon](#ibeacon)
        - [Location](#location)
        - [Other Hardware](#other-hardware)
    - [Layout](#layout)
    - [Logging](#logging)
    - [Localization](#localization)
    - [Machine Learning](#machine-learning)
    - [Maps](#maps)
    - [Math](#math)
    - [Media](#media)
        - [Audio](#audio)
        - [GIF](#gif)
        - [Image](#image)
        - [Media Processing](#media-processing)
        - [PDF](#pdf)
        - [Streaming](#streaming)
        - [Video](#video)
    - [Messaging](#messaging)
    - [Networking](#networking)
    - [Notifications](#notifications)
        - [Push Notifications](#push-notifications)
            - [Push Notification Providers](#push-notification-providers)
        - [Local Notifications](#local-notifications)
    - [Optimization](#optimization)
    - [Parsing](#parsing)
        - [CSV](#csv)
        - [JSON](#json)
        - [XML & HTML](#xml--html)
        - [Other Parsing](#other-parsing)
    - [Passbook](#passbook)
    - [Payments](#payments)
    - [Permissions](#permissions)
    - [Products](#products)
    - [Reactive Programming](#reactive-programming)
        - [React-Like](#react-like)
    - [Reflection](#reflection)
    - [Regex](#regex)
    - [SDK](#sdk)
        - [Official](#official)
        - [Unofficial](#unofficial)
    - [Security](#security)
        - [Encryption](#encryption)
        - [Keychain](#keychain)
    - [Server](#server)
    - [Testing](#testing)
        - [TDD / BDD](#tdd--bdd)
        - [A/B Testing](#ab-testing)
        - [UI Testing](#ui-testing)
        - [Other Testing](#other-testing)
    - [Text](#text)
        - [Font](#font)
    - [UI](#ui)
        - [Activity Indicator](#activity-indicator)
        - [Alert & Action Sheet](#alert--action-sheet)
        - [Animation](#animation)
          - [Transition](#transition)
        - [Badge](#badge)
        - [Button](#button)
        - [Calendar](#calendar)
        - [Form & Settings](#form--settings)
        - [Keyboard](#keyboard)
        - [Label](#label)
        - [Login](#login)
        - [Menu](#menu)
        - [Navigation Bar](#navigation-bar)
        - [PickerView](#pickerview)
        - [Popup](#popup)
        - [Pull to Refresh](#pull-to-refresh)
        - [Rating Stars](#rating-stars)
        - [ScrollView](#scrollview)
        - [Segmented Control](#segmented-control)
        - [Slider](#slider)
        - [Splash View](#splash-view)
        - [Stepper](#stepper)
        - [Switch](#switch)
        - [Tab Bar](#tab-bar)
        - [Table View / Collection View](#table-view--collection-view)
        - [Tag](#tag)
        - [TextField & TextView](#textfield--textview)
        - [Web View](#web--view)
    - [Utility](#utility)
    - [VR](#vr)
    - [Walkthrough / Intro / Tutorial](#walkthrough--intro--tutorial)
    - [Websocket](#websocket)
- [Project setup](#project-setup)
- [Dependency / Package Manager](#dependency--package-manager)
- [Tools](#tools)
- [Rapid Development](#rapid-development)
  - [Injection](#injection)
- [Deployment / Distribution](#deployment--distribution)
- [App Store](#app-store)
- [SDK](#sdk)
    - [Official](#official)
    - [Unofficial](#unofficial)
- [Xcode](#xcode)
    - [Extensions (Xcode 8+)](#extensions-xcode-8)
    - [Plugins](#plugins)
    - [Themes](#themes)
    - [Other Xcode](#other-xcode)
- [Reference](#reference)
- [Style Guides](#style-guides)
- [Good Websites](#good-websites)
    - [News, Blogs and more](#news-blogs-and-more)
    - [UIKit references](#uikit-references)
    - [Forums and discuss lists](#forums-and-discuss-lists)
    - [Tutorials and Keynotes](#tutorials-and-keynotes)
    - [Prototyping](#prototyping)
    - [Newsletters](#newsletters)
    - [Medium](#medium)
- [Social Media](#social-media)
  - [Twitter](#twitter)
  - [Facebook Groups](#facebook-groups)
- [Podcasts](#podcasts)
- [Books](#books)
- [Other Awesome Lists](#other-awesome-lists)
- [Contributing](#contributing-and-license)

***
# Getting Started
* [Start Developing with iOS](https://developer.apple.com/library/content/referencelibrary/GettingStarted/DevelopiOSAppsSwift/) - Apple Guide. :large_orange_diamond:
* [Lifehacker](https://lifehacker.com/i-want-to-write-ios-apps-where-do-i-start-1644802175) - I Want to Write iOS Apps. Where Do I Start?
* [CodeProject](https://www.codeproject.com/articles/88929/getting-started-with-iphone-and-ios-development) - Getting Started with iPhone and iOS Development.
* [Ray Wenderlich](https://www.raywenderlich.com/38557/learn-to-code-ios-apps-1-welcome-to-programming) - Learn to code iOS Apps.
* [Stanford - Developing iOS 7 Apps for iPhone and iPad](https://itunes.apple.com/us/course/developing-ios-7-apps-for-iphone-and-ipad/id733644550)
* [Stanford - Developing iOS 10 Apps with Swift](https://itunes.apple.com/in/course/developing-ios-10-apps-swift/id1198467120) - Stanford's 2017 iTunes U course. :large_orange_diamond:
* [Programming with Objective-C by Apple](https://developer.apple.com/library/content/documentation/Cocoa/Conceptual/ProgrammingWithObjectiveC/Introduction/Introduction.html)
* [Object-Oriented Programming with Objective-C by Apple](https://developer.apple.com/library/content/documentation/Cocoa/Conceptual/OOP_ObjC/Introduction/Introduction.html)
* [Udacity: Start A Career Developing iOS Apps](https://www.udacity.com/course/ios-developer-nanodegree--nd003?v=ios1) - Udacity's intro course on writing iOS apps [Paid Resource] :large_orange_diamond:

# Libraries And Frameworks

## Analytics
* [Mixpanel](https://mixpanel.com/) - Advanced analytics platform.
* [Localytics](https://www.localytics.com/) - Brings app marketing and analytics together.
* [Answers by Fabric](https://answers.io/) - Answers gives you real-time insight into people’s experience in your app.
* [Liquid Analytics](https://onliquid.com) - Identify behaviours through Analytics and react with real-time Personalization.
* [GTrack ★85](https://github.com/gemr/GTrack) - Lightweight Objective-C wrapper around the Google Analytics for iOS SDK with some extra goodies.
* [ARAnalytics ★1689](https://github.com/orta/ARAnalytics) - Analytics abstraction library offering a sane API for tracking events and user data.
* [Segment ★258](https://github.com/segmentio/analytics-ios) - The hassle-free way to integrate analytics into any iOS application.
* [MOCA Analytics](https://mocaplatform.com/features) - Paid cross-platform analytics backend.
* [Countly](https://count.ly) - Open source, mobile & web analytics, crash reports and push notifications platform for iOS & Android.
* [Abbi ★2](https://github.com/abbiio/iosdk) - A Simple SDK for developers to manage and maximise conversions of all in-app promotions.
* [devtodev](https://www.devtodev.com/) - Comprehensive analytics service that improves your project and saves time for product development.
* [Bugsnag](https://www.bugsnag.com/platforms/ios-crash-reporting/) - Error tracking with a free tier. Error reports include data on device, release, user, and allows arbitrary data.
* [Inapptics](https://inapptics.com) - Helps analyze and visualize user behavior in mobile apps. Provides visual user journeys, heatmaps and crash replays.

## App Routing
* [WAAppRouting ★559 ⏳1Y](https://github.com/Wasappli/WAAppRouting) - iOS routing done right. Handles both URL recognition and controller displaying with parsed parameters. All in one line, controller stack preserved automatically!
* [DeepLinkKit ★2999](https://github.com/button/DeepLinkKit) - A splendid route-matching, block-based way to handle your deep links.
* [IntentKit ★1806](https://github.com/intentkit/IntentKit) - An easier way to handle third-party URL schemes in iOS apps.
* [JLRoutes ★3861](https://github.com/joeldev/JLRoutes) - URL routing library for iOS with a simple block-based API.
* [IKRouter ★92 ⏳2Y](https://github.com/IanKeen/IKRouter) - URLScheme router than supports auto creation of UIViewControllers for associated url parameters to allow creation of navigation stacks :large_orange_diamond:
* [Compass ★559](https://github.com/hyperoslo/Compass) - :earth_africa: Compass helps you setup a central navigation system for your application :large_orange_diamond:
* [Appz ★872](https://github.com/SwiftKitz/Appz) - Easily launch and deeplink into external applications, falling back to web if not installed. :large_orange_diamond:
* [URLNavigator ★1362](https://github.com/devxoul/URLNavigator) - ⛵️ Elegant URL Routing for Swift :large_orange_diamond:
* [Marshroute ★134](https://github.com/avito-tech/Marshroute) - Marshroute is an iOS Library for making your Routers simple but extremely powerful. :large_orange_diamond: 
* [SwiftRouter ★153](https://github.com/skyline75489/SwiftRouter) - A URL Router for iOS, written in Swift 3 :large_orange_diamond:
* [Router ★89](https://github.com/freshOS/Router) - 🛣 Simple Navigation for iOS. :large_orange_diamond:
* [ApplicationCoordinator ★213](https://github.com/AndreyPanov/ApplicationCoordinator) - Coordinator is an object that handles navigation flow and shares flow’s handling for the next coordinator after switching on the next chain.

## Apple TV
* [Voucher ★491](https://github.com/rsattar/Voucher) - A simple library to make authenticating tvOS apps easy via their iOS counterparts.
* [XCDYouTubeKit ★2217](https://github.com/0xced/XCDYouTubeKit) - YouTube video player for iOS, tvOS and macOS
* [TVMLKitchen ★67](https://github.com/toshi0383/TVMLKitchen) - Swifty TVML template manager with or without client-server :large_orange_diamond:
* [BrowserTV ★206 ⏳1Y](https://github.com/zats/BrowserTV) - Turn your TV into a dashboard displaying any webpage! :large_orange_diamond:
* [Swift-GA-Tracker-for-Apple-tvOS ★67](https://github.com/analytics-pros/Swift-GA-Tracker-for-Apple-tvOS) - Google Analytics tracker for Apple tvOS provides an easy integration of Google Analytics’ measurement protocol for Apple TV. :large_orange_diamond:
* [ParallaxView ★337](https://github.com/PGSSoft/ParallaxView) - iOS controls and extensions that add parallax effect to your application. :large_orange_diamond:
* [TvOSTextViewer ★25](https://github.com/dcordero/TvOSTextViewer) - Light and scrollable view controller for tvOS to present blocks of text :large_orange_diamond:
* [FocusTvButton ★32](https://github.com/dcordero/FocusTvButton) - Light wrapper of UIButton that allows extra customization for tvOS :large_orange_diamond:
* [TvOSMoreButton ★19](https://github.com/cgoldsby/TvOSMoreButton) - A basic tvOS button which truncates long text with '... More'. :large_orange_diamond:
* [TvOSPinKeyboard ★90](https://github.com/zattoo/TvOSPinKeyboard) - PIN keyboard for tvOS :large_orange_diamond:
* [TvOSScribble ★159](https://github.com/dcordero/TvOSScribble) - Handwriting numbers recognizer for Siri Remote :large_orange_diamond:
* [TvOSCustomizableTableViewCell ★17](https://github.com/zattoo/TvOSCustomizableTableViewCell) - Light wrapper of UITableViewCell that allows extra customization for tvOS :large_orange_diamond:

## ARKit
* [ARKit-CoreLocation ★2966](https://github.com/ProjectDent/ARKit-CoreLocation) -Combines the high accuracy of AR with the scale of GPS data. :large_orange_diamond:
* [Virtual Objects ★134](https://github.com/ignacio-chiazzo/ARKit) - Placing Virtual Objects in Augmented Reality.
* [ARVideoKit ★438](https://github.com/AFathi/ARVideoKit) - Record and capture ARKit videos 📹, photos 🌄, Live Photos 🎇, and GIFs 🎆. :large_orange_diamond:

## Authentication
* [Heimdallr.swift ★438](https://github.com/trivago/Heimdallr.swift) - Easy to use OAuth 2 library for iOS, written in Swift. :large_orange_diamond:
* [OhMyAuth ★49](https://github.com/hyperoslo/OhMyAuth) - Simple OAuth2 library with a support of multiple services. :large_orange_diamond:
* [AuthenticationViewController ★234](https://github.com/raulriera/AuthenticationViewController) - A simple to use, standard interface for authenticating to oauth 2.0 protected endpoints via SFSafariViewController. :large_orange_diamond:
* [OAuth2 ★616](https://github.com/p2/OAuth2) - OAuth2 framework for macOS and iOS, written in Swift. :large_orange_diamond:
* [OAuthSwift ★1876](https://github.com/OAuthSwift/OAuthSwift) - Swift based OAuth library for iOS :large_orange_diamond:
* [SimpleAuth ★1161 ⏳1Y](https://github.com/calebd/SimpleAuth) - Simple social authentication for iOS.
* [AlamofireOauth2 ★71](https://github.com/evermeer/AlamofireOauth2) - A swift implementation of OAuth2 :large_orange_diamond:
* [SwiftyOAuth ★458](https://github.com/delba/SwiftyOAuth) - A simple OAuth library for iOS with a built-in set of providers :large_orange_diamond:
* [Simplicity ★636](https://github.com/SimplicityMobile/Simplicity) - A simple way to implement Facebook and Google login in your iOS and macOS apps. :large_orange_diamond:
* [InstagramAuthViewController ★33 ⏳1Y](https://github.com/Isuru-Nanayakkara/InstagramAuthViewController) - A ViewController for Instagram authentication. :large_orange_diamond:
* [InstagramSimpleOAuth ★82](https://github.com/rbaumbach/InstagramSimpleOAuth) - A quick and simple way to authenticate an Instagram user in your iPhone or iPad app.
* [DropboxSimpleOAuth ★42](https://github.com/rbaumbach/DropboxSimpleOAuth) - A quick and simple way to authenticate a Dropbox user in your iPhone or iPad app.
* [BoxSimpleOAuth ★15](https://github.com/rbaumbach/BoxSimpleOAuth) - A quick and simple way to authenticate a Box user in your iPhone or iPad app.
* [InstagramLogin ★18](https://github.com/AnderGoig/InstagramLogin) - A simple way to authenticate Instagram accounts on iOS. :large_orange_diamond:
* [ReCaptcha ★38](https://github.com/fjcaetano/ReCaptcha) - [In]visible ReCaptcha for iOS. :large_orange_diamond:
* [LinkedInSignIn ★9](https://github.com/serhii-londar/LinkedInSignIn) - Simple view controller to login and retrieve access token from LinkedIn. :large_orange_diamond:

## Bridging
* [RubyMotion](http://www.rubymotion.com/) - RubyMotion is a revolutionary toolchain that lets you quickly develop and test native iOS and macOS applications for iPhone, iPad and Mac, all using the Ruby language.
* [JSPatch ★10132](https://github.com/bang590/JSPatch) - JSPatch bridge Objective-C and Javascript using the Objective-C runtime. You can call any Objective-C class and method in JavaScript by just including a small engine. JSPatch is generally use for hotfix iOS App.
* [WebViewJavascriptBridge ★9663](https://github.com/marcuswestin/WebViewJavascriptBridge) - An iOS/macOS bridge for sending messages between Obj-C and JavaScript in UIWebViews/WebViews
* [MAIKit ★135 ⏳1Y](https://github.com/MichaelBuckley/MAIKit) - A framework for sharing code between iOS and macOS

## Cache
* [Awesome Cache ★1084](https://github.com/aschuch/AwesomeCache) - Delightful on-disk cache (written in Swift) :large_orange_diamond:
* [mattress ★444](https://github.com/buzzfeed/mattress) - iOS Offline Caching for Web Content :large_orange_diamond:
* [Carlos ★451](https://github.com/WeltN24/Carlos) - A simple but flexible cache :large_orange_diamond:
* [HanekeSwift ★4542](https://github.com/Haneke/HanekeSwift) - A lightweight generic cache for iOS written in Swift with extra love for images. :large_orange_diamond:
* [YYCache ★1562](https://github.com/ibireme/YYCache) - High performance cache framework for iOS.
* [Cache ★955](https://github.com/hyperoslo/Cache) - Nothing but Cache. :large_orange_diamond:
* [MGCacheManager ★8](https://github.com/Mortgy/MGCacheManager) - A delightful iOS Networking Cache Managing Class.
* [SPTPersistentCache ★1145](https://github.com/spotify/SPTPersistentCache) - Everyone tries to implement a cache at some point in their iOS app’s lifecycle, and this is ours. By Spotify
* [Track ★190](https://github.com/maquannene/Track) - Track is a thread safe cache write by Swift. Composed of DiskCache and MemoryCache which support LRU. :large_orange_diamond:
* [UITableView Cache ★61](https://github.com/Kilograpp/UITableView-Cache) - UITableView cell cache that cures scroll-lags on a cell instantiating.
* [RocketData ★520](https://github.com/linkedin/RocketData) - A caching and consistency solution for immutable models. :large_orange_diamond:
* [PINCache ★1793](https://github.com/pinterest/PINCache) - Fast, non-deadlocking parallel object cache for iOS and macOS
* [Johnny ★26](https://github.com/zolomatok/Johnny) - Melodic Caching for Swift :large_orange_diamond:
* [Disk ★1705](https://github.com/saoudrizwan/Disk) - Delightful framework for iOS to easily persist structs, images, and data. 🔶
* [Cachyr ★96](https://github.com/YR/Cachyr) - A small key-value data cache for iOS, macOS and tvOS, written in Swift :large_orange_diamond:

## Charts
* [Charts](https://github.com/danielgindi/Charts) - A powerful chart / graph framework, the iOS equivalent to [MPAndroidChart ★19104](https://github.com/PhilJay/MPAndroidChart). :large_orange_diamond:
* [JTChartView ★116 ⏳1Y](https://github.com/kubatruhlar/JTChartView) - JTChartView is the new lightweight and fully customizable solution to draw a chart.
* [PNChart ★8900](https://github.com/kevinzhow/PNChart) - A simple and beautiful chart lib used in Piner and CoinsMan for iOS
* [XJYChart ★228](https://github.com/JunyiXie/XJYChart) - A Beautiful chart for iOS. Support animation, click, slide, area highlight.
* [BEMSimpleLineGraph ★2643](https://github.com/Boris-Em/BEMSimpleLineGraph) - Elegant Line Graphs for iOS (charting library).
* [JBChartView ★3736](https://github.com/Jawbone/JBChartView) - iOS-based charting library for both line and bar graphs.
* [XYPieChart ★1737 ⏳1Y](https://github.com/xyfeng/XYPieChart) - A simple and animated Pie Chart for your iOS app.
* [TEAChart ★1141](https://github.com/xhacker/TEAChart) - Simple and intuitive iOS chart library. Contribution graph, clock chart, and bar chart.
* [EChart ★640 ⏳1Y](https://github.com/zhuhuihuihui/EChart) - iOS/iPhone/iPad Chart, Graph. Event handling and animation supported.
* [FSLineChart ★812](https://github.com/ArthurGuibert/FSLineChart) - A line chart library for iOS.
* [chartee ★862 ⏳1Y](https://github.com/zhiyu/chartee) - a charting library for mobile platforms.
* [ANDLineChartView ★412](https://github.com/anaglik/ANDLineChartView) - ANDLineChartView is easy to use view-based class for displaying animated line chart.
* [TWRCharts ★369 ⏳3Y](https://github.com/chasseurmic/TWRCharts) - An iOS wrapper for ChartJS. Easily build animated charts by leveraging the power of native Obj-C code.
* [SwiftCharts ★1496](https://github.com/i-schuetz/SwiftCharts) - Easy to use and highly customizable charts library for iOS. :large_orange_diamond:
* [FlowerChart ★8](https://github.com/drinkius/flowerchart) - Flower-shaped chart with custom appearance animation, fully vector. :large_orange_diamond:
* [Scrollable-GraphView ★4078](https://github.com/philackm/ScrollableGraphView) - An adaptive scrollable graph view for iOS to visualise simple discrete datasets. Written in Swift. :large_orange_diamond:
* [Dr-Charts ★66](https://github.com/Zomato/DR-charts) - Dr-Charts is a highly customisable, easy to use and interactive chart / graph framework in Objective-C.
* [Graphs ★854](https://github.com/recruit-mtl/Graphs) - Light weight charts view generator for iOS. :large_orange_diamond:
* [FSInteractiveMap ★457](https://github.com/ArthurGuibert/FSInteractiveMap) - A charting library to visualize and interact with a vector map on iOS. It's like Geochart but for iOS!
* [JYRadarChart ★392](https://github.com/johnnywjy/JYRadarChart) - An iOS open source Radar Chart implementation.
* [TKRadarChart ★129](https://github.com/TBXark/TKRadarChart) - A customizable radar chart in Swift :large_orange_diamond:
* [MagicPie ★530 ⏳1Y](https://github.com/AlexandrGraschenkov/MagicPie) - Awesome layer based pie chart. Fantastically fast and fully customizable. Amazing animations available with MagicPie!!1 :large_orange_diamond: 🎉 ✨✨✨✨✨
* [PieCharts ★324](https://github.com/i-schuetz/PieCharts) - Easy to use and highly customizable pie charts library for iOS. :large_orange_diamond:
* [CSPieChart ★27](https://github.com/youkchansim/CSPieChart) - iOS PieChart Opensource. This is very easy to use and customizable. :large_orange_diamond:
* [DDSpiderChart ★28](https://github.com/dadalar/DDSpiderChart) - Easy to use and customizable Spider (Radar) Chart library for iOS written in Swift. :large_orange_diamond:
* [core-plot ★2513](https://github.com/core-plot/core-plot) - a 2D plotting lib which is highly customizable and capable of drawing many types of plots.
* [ChartProgressBar ★22](https://github.com/hadiidbouk/ChartProgressBar-iOS) - Draw a chart with progress bar style.
* [SMDiagramViewSwift ★14](https://github.com/VRGsoftUA/SMDiagramView) - Meet cute and very flexibility library for iOS application for different data view in one circle diagram. 

## Code Quality
* [Bootstrap ★1874](https://github.com/krzysztofzablocki/Bootstrap) - iOS project bootstrap aimed at high quality coding.
* [KZAsserts ★106](https://github.com/krzysztofzablocki/KZAsserts) - Set of custom assertions that automatically generate NSError's, allow for both Assertions in Debug and Error handling in Release builds, with beautiful DSL.
* [PSPDFUIKitMainThreadGuard](https://gist.github.com/steipete/5664345) - Simple snippet generating assertions when UIKit is used on background threads.
* [ocstyle ★249](https://github.com/Cue/ocstyle) - Objective-C style checker.
* [spacecommander ★791](https://github.com/square/spacecommander) - Commit fully-formatted Objective-C code as a team without even trying.
* [DWURecyclingAlert ★563](https://github.com/diwu/DWURecyclingAlert) - Optimizing UITableViewCell For Fast Scrolling.
* [Tailor ★1124](https://github.com/sleekbyte/tailor) - Cross-platform static analyzer for Swift that helps you to write cleaner code and avoid bugs.
* [SwiftCop ★502](https://github.com/andresinaka/SwiftCop) -  SwiftCop is a validation library fully written in Swift and inspired by the clarity of Ruby On Rails Active Record validations. :large_orange_diamond:
* [Trackable ★130](https://github.com/VojtaStavik/Trackable) - Trackable is a simple analytics integration helper library. It’s especially designed for easy and comfortable integration with existing projects. :large_orange_diamond:
* [MLeaksFinder ★2846](https://github.com/Tencent/MLeaksFinder) - Find memory leaks in your iOS app at develop time.
* [HeapInspector-for-iOS ★1635](https://github.com/tapwork/HeapInspector-for-iOS) - Find memory issues & leaks in your iOS app without instruments
* [FBMemoryProfiler ★2793](https://github.com/facebook/FBMemoryProfiler) - iOS tool that helps with profiling iOS Memory usage.
* [FBRetainCycleDetector ★2689](https://github.com/facebook/FBRetainCycleDetector) - iOS library to help detecting retain cycles in runtime.
* [Buglife ★273](https://github.com/Buglife/Buglife-iOS) - Awesome bug reporting for iOS apps
* [Warnings-xcconfig ★429 ⏳2Y](https://github.com/boredzo/Warnings-xcconfig) - An xcconfig (Xcode configuration) file for easily turning on a boatload of warnings in your project or its targets.
* [Aardvark ★196](https://github.com/square/Aardvark) - Aardvark is a library that makes it dead simple to create actionable bug reports.
* [Stats ★148](https://github.com/shu223/Stats) - In-app memory usage monitoring.
* [GlueKit ★352](https://github.com/attaswift/GlueKit) - A type-safe observer framework for Swift. :large_orange_diamond:
* [SwiftFormat ★1609](https://github.com/nicklockwood/SwiftFormat) - A code library and command-line formatting tool for reformatting Swift code. :large_orange_diamond:
* [PSTModernizer ★214](https://github.com/PSPDFKit-labs/PSTModernizer) - Makes it easier to support older versions of iOS by fixing things and adding missing methods.
* [SwiftyVIPER ★48](https://github.com/codytwinton/SwiftyVIPER) - Makes implementing VIPER architecture much easier and cleaner.  :large_orange_diamond:
* [Bugsee](https://www.bugsee.com) - In-app bug and crash reporting with video, logs, network traffic and traces.
* [Fallback ★33 ⏳1Y](https://github.com/devxoul/Fallback) - Syntactic sugar for nested do-try-catch. :large_orange_diamond:
* [ODUIThreadGuard ★700](https://github.com/olddonkey/ODUIThreadGuard) - A guard to help you check if you make UI changes not in main thread. :large_orange_diamond:
* [IBAnalyzer ★843](https://github.com/fastred/IBAnalyzer) - Find common xib and storyboard-related problems without running your app or writing unit tests. :large_orange_diamond:
* [CleanArchitectureRxSwift ★897](https://github.com/sergdort/CleanArchitectureRxSwift) - Example of Clean Architecture of iOS app using RxSwift. :large_orange_diamond:
* [DecouplingKit ★112](https://github.com/coderyi/DecouplingKit) - decoupling between modules in your iOS Project.
* [Clue ★239](https://github.com/Geek-1001/Clue) - Flexible bug report framework for iOS with screencast, networking, interactions and view structure.
* [Viperit ★201](https://github.com/ferranabello/Viperit) - Viper Framework for iOS. Develop an app following VIPER architecture in an easy way. Written and tested in Swift. :large_orange_diamond:

#### Linter
* [OCLint ★2085](https://github.com/oclint/oclint) - Static code analysis tool for improving quality and reducing defects.
* [Taylor ★186](https://github.com/yopeso/Taylor) - Measure Swift code metrics and get reports in Xcode, Jenkins and other CI platforms. :large_orange_diamond:
* [Swiftlint ★8020](https://github.com/realm/SwiftLint) - A tool to enforce Swift style and conventions. :large_orange_diamond:

## Color
* [Chameleon ★10237](https://github.com/ViccAlexander/Chameleon) - A lightweight, yet powerful, flat color framework for iOS (ObjC & Swift). :large_orange_diamond:
* [ColorArt ★130 ⏳1Y](https://github.com/vinhnx/ColorArt) - extract dominant colors from image like iTunes 11.
* [DynamicColor ★1719](https://github.com/yannickl/DynamicColor) - Yet another extension to manipulate colors easily in Swift. :large_orange_diamond:[e]
* [SwiftHEXColors ★505](https://github.com/thii/SwiftHEXColors) - HEX color handling as an extension for UIColor. :large_orange_diamond:[e]
* [Colours ★2930](https://github.com/bennyguitar/Colours) - A beautiful set of predefined colors and a set of color methods to make your iOS/macOS development life easier.
* [UIColor-Hex-Swift ★820](https://github.com/yeahdongcn/UIColor-Hex-Swift) - Convenience method for creating autoreleased color using RGBA hex string. :large_orange_diamond:
* [Hue ★2244](https://github.com/hyperoslo/Hue) - Hue is the all-in-one coloring utility that you'll ever need.
* [FlatUIColors ★138](https://github.com/brynbellomy/FlatUIColors) - Flat UI color palette helpers written in Swift. :large_orange_diamond:
* [RandomColorSwift ★446 ⏳1Y](https://github.com/onevcat/RandomColorSwift) - An attractive color generator for Swift. Ported from randomColor.js. :large_orange_diamond:
* [PFColorHash ★17 ⏳1Y](https://github.com/PerfectFreeze/PFColorHash) - Generate color based on the given string. :large_orange_diamond:
* [BCColor ★425](https://github.com/boycechang/BCColor) - A lightweight but powerful color kit (Swift) :large_orange_diamond:
* [DKNightVersion ★2855](https://github.com/Draveness/DKNightVersion) - Manage Colors, Integrate Night/Multiple Themes
* [PrettyColors ★147](https://github.com/jdhealy/PrettyColors) - PrettyColors is a Swift library for styling and coloring text in the Terminal. The library outputs [ANSI escape codes](https://en.wikipedia.org/wiki/ANSI_escape_code) and conforms to [ECMA Standard 48](http://www.ecma-international.org/publications/standards/Ecma-048.htm). :large_orange_diamond:
* [TFTColor ★16](https://github.com/burhanuddin353/TFTColor) - Simple Extension for RGB and CMKY Hex Strings and Hex Values (ObjC & Swift). :large_orange_diamond:
* [CostumeKit ★290](https://github.com/jakemarsh/CostumeKit) - Base types for theming an app. :large_orange_diamond:
* [CSS3ColorsSwift ★52 ⏳1Y](https://github.com/WorldDownTown/CSS3ColorsSwift) - A UIColor extension with CSS3 Colors name. :large_orange_diamond:
* [Colorify ★72](https://github.com/czater/Colorify) - Simple, yet powerful color library that includes latest and most trendy colors from 2017. :large_orange_diamond:
* [ChromaColorPicker ★82](https://github.com/joncardasis/ChromaColorPicker) - An intuitive iOS color picker built in Swift. :large_orange_diamond:
* [Lorikeet ★10](https://github.com/valdirunars/Lorikeet) - A lightweight Swift framework for aesthetically pleasing color-scheme generation and CIE color-difference calculation. :large_orange_diamond:

## Command Line
* [Swiftline ★986](https://github.com/nsomar/Swiftline) - Swiftline is a set of tools to help you create command line applications. :large_orange_diamond:
* [CommandLine ★969](https://github.com/jatoben/CommandLine) - A pure Swift library for creating command-line interfaces :large_orange_diamond:
* [Commander ★980](https://github.com/kylef/Commander) - Compose beautiful command line interfaces in Swift :large_orange_diamond:
* [ColorizeSwift ★169](https://github.com/mtynior/ColorizeSwift) - Terminal string styling for Swift. :large_orange_diamond:
* [Guaka ★1047](https://github.com/nsomar/Guaka) - The smartest and most beautiful (POSIX compliant) Command line framework for Swift :large_orange_diamond:
* [Marathon ★1257](https://github.com/JohnSundell/Marathon) - Marathon makes it easy to write, run and manage your Swift scripts :large_orange_diamond:
* [CommandCougar ★15](https://github.com/surfandneptune/CommandCougar) - An elegant pure Swift library for building command line applications. :large_orange_diamond:

## Concurrency
* [Venice ★1326](https://github.com/Zewo/Venice) - CSP (Coroutines, Channels, Select) for Swift :large_orange_diamond:
* [Concurrent ★144](https://github.com/typelift/Concurrent) - Functional Concurrency Primitives :large_orange_diamond:
* [Flow ★193](https://github.com/JohnSundell/Flow) - Operation Oriented Programming in Swift :large_orange_diamond:
* [Brisk ★22](https://github.com/jmfieldman/Brisk) - A Swift DSL that allows concise and effective concurrency manipulation. :large_orange_diamond:
* [Aojet ★20 ⏳1Y](https://github.com/aojet/Aojet) - An actor model library for swift.
* [Overdrive ★816](https://github.com/arikis/Overdrive) - Fast async task based Swift framework with focus on type safety, concurrency and multi threading. :large_orange_diamond:
* [NSLock+Synchronized ★2](https://github.com/Jon-Schneider/NSLock-Synchronized) - Do you miss @synchronized in Swift? NSLock+Synchronized gives you back @synchronized in Swift via a global function and NSLock class and instance methods, conveniently usable via CocoaPods and Carthage Framework. :large_orange_diamond:[e]
* [AsyncNinja ★62](https://github.com/AsyncNinja/AsyncNinja) - A complete set of concurrency and reactive programming primitives. :large_orange_diamond:
* [Kommander ★100](https://github.com/intelygenz/Kommander-iOS) - Kommander is a Swift library to manage the task execution in different threads. Through the definition a simple but powerful concept, Kommand. :large_orange_diamond:
* [Threadly ★41](https://github.com/nvzqz/Threadly) - Type-safe thread-local storage in Swift :large_orange_diamond:
* [Flow-iOS ★10](https://github.com/roytornado/Flow-iOS) - Make your logic flow and data flow clean and human readable :large_orange_diamond:
* [Queuer ★679](https://github.com/FabrizioBrancati/Queuer) - A queue manager, built on top of OperationQueue and Dispatch (aka GCD). :large_orange_diamond:
* [SwiftQueue ★14](https://github.com/lucas34/SwiftQueue) - Job Scheduler with Concurrent run, failure/retry, persistence, repeat, delay and more. :large_orange_diamond:

## Core Data
* [CWCoreData ★71 ⏳2Y](https://github.com/jayway/CWCoreData) - Additions and utilities to make it concurrency easier with the Core Data framework.
* [ObjectiveRecord ★1334](https://github.com/supermarin/ObjectiveRecord) - ActiveRecord for Objective-C.
* [SSDataKit ★466 ⏳1Y](https://github.com/soffes/SSDataKit) - Eliminate your Core Data boilerplate code.
* [ios-queryable ★237 ⏳2Y](https://github.com/martydill/ios-queryable) - ios-queryable is an implementation of IQueryable/IEnumerable for Core Data.
* [Ensembles ★1547](https://github.com/drewmccormack/ensembles) - A synchronization framework for Core Data.
* [SLRESTfulCoreData ★186 ⏳3Y](https://github.com/OliverLetterer/SLRESTfulCoreData) - Objc naming conventions, autogenerated accessors at runtime, URL substitutions and intelligent attribute mapping.
* [Mogenerator ★2947](https://github.com/rentzsch/mogenerator) - Automatic Core Data code generation.
* [HardCoreData ★206 ⏳2Y](https://github.com/Krivoblotsky/HardCoreData) - CoreData stack and controller that will never block UI thread.
* [encrypted-core-data ★650](https://github.com/project-imas/encrypted-core-data) - Core Data encrypted SQLite store using SQLCipher.
* [MagicalRecord ★10541](https://github.com/magicalpanda/MagicalRecord) - Super Awesome Easy Fetching for Core Data.
* [QueryKit ★1283](https://github.com/QueryKit/QueryKit) - A simple type-safe Core Data query language. :large_orange_diamond:
* [CoreStore ★1707](https://github.com/JohnEstropia/CoreStore) - Powerful Core Data framework for Incremental Migrations, Fetching, Observering, etc. :large_orange_diamond:
* [Core Data Query Interface ★20](https://github.com/prosumma/CoreDataQueryInterface) A type-safe, fluent query framework for Core Data. :large_orange_diamond:
* [Graph ★738](https://github.com/CosmicMind/Graph) - An elegant data-driven framework for CoreData in Swift. :large_orange_diamond:
* [CoreDataDandy ★32](https://github.com/fuzz-productions/CoreDataDandy) - A feature-light wrapper around Core Data that simplifies common database operations. :large_orange_diamond:
* [Sync ★2046](https://github.com/3lvis/Sync) - :arrows_counterclockwise: Modern Swift JSON synchronization to Core Data :large_orange_diamond:
* [AlecrimCoreData ★732](https://github.com/Alecrim/AlecrimCoreData) - A powerful and simple Core Data wrapper framework written in Swift. :large_orange_diamond:
* [AERecord ★284 ⏳1Y](https://github.com/tadija/AERecord) - Super awesome Core Data wrapper in Swift. :large_orange_diamond:
* [CoreDataStack ★518](https://github.com/bignerdranch/CoreDataStack) - The Big Nerd Ranch Core Data Stack :large_orange_diamond:
* [JSQCoreDataKit ★445](https://github.com/jessesquires/JSQCoreDataKit) - A swifter Core Data stack :large_orange_diamond:
* [Skopelos ★181](https://github.com/albertodebortoli/Skopelos) - A minimalistic, thread safe, non-boilerplate and super easy to use version of Active Record on Core Data. Simply all you need for doing Core Data. Swift flavour. :large_orange_diamond:
* [Cadmium ★93](https://github.com/jmfieldman/cadmium) - A complete swift framework that wraps CoreData and helps facilitate best practices. :large_orange_diamond:
* [DataKernel ★6](https://github.com/mrdekk/DataKernel) - Simple CoreData wrapper to ease operations. :large_orange_diamond:
* [DATAStack ★164](https://github.com/3lvis/DATAStack) - 100% Swift Simple Boilerplate Free Core Data Stack. NSPersistentContainer. :large_orange_diamond:
* [JustPersist ★94](https://github.com/justeat/JustPersist) - JustPersist is the easiest and safest way to do persistence on iOS with Core Data support out of the box.
* [PrediKit ★474](https://github.com/KrakenDev/PrediKit) - An NSPredicate DSL for iOS, macOS, tvOS, & watchOS. Inspired by SnapKit and lovingly written in Swift. :large_orange_diamond:
* [Records ★7](https://github.com/rob-nash/Records) - In just a few minutes, setup a fully functioning CoreData implementation that embraces the static, type-safe nature of Swift. :large_orange_diamond:

## Database
* [Realm ★11503](https://github.com/realm/realm-cocoa) - The alternative to CoreData and SQLite: Simple, modern and fast.
* [YapDatabase ★2946](https://github.com/yapstudios/YapDatabase) - YapDatabase is an extensible database for iOS & Mac.
* [Couchbase Mobile](https://developer.couchbase.com/mobile/) - Couchbase document store for mobile with cloud sync.
* [FMDB ★12045](https://github.com/ccgus/fmdb) - A Cocoa / Objective-C wrapper around SQLite.
* [FCModel ★1640](https://github.com/marcoarment/FCModel) - An alternative to Core Data for people who like having direct SQL access.
* [Zephyr ★417](https://github.com/ArtSabintsev/Zephyr) - Effortlessly synchronize NSUserDefaults over iCloud. :large_orange_diamond:
* [Prephirences ★440](https://github.com/phimage/Prephirences) - Prephirences is a Swift library that provides useful protocols and convenience methods to manage application preferences, configurations and app-state. :large_orange_diamond:
* [Storez ★48](https://github.com/SwiftKitz/Storez) - Safe, statically-typed, store-agnostic key-value storage (with namespace support). :large_orange_diamond:
* [SwiftyUserDefaults ★2877](https://github.com/radex/SwiftyUserDefaults) - Statically-typed NSUserDefaults. :large_orange_diamond:
* [SugarRecord ★1962](https://github.com/carambalabs/SugarRecord) - Data persistence management library written in Swift 2.0 :large_orange_diamond:
* [SQLite.swift ★4742](https://github.com/stephencelis/SQLite.swift) - A type-safe, Swift-language layer over SQLite3. :large_orange_diamond:
* [GRDB.swift ★1039](https://github.com/groue/GRDB.swift) - A versatile SQLite toolkit for Swift, with WAL mode support :large_orange_diamond:
* [Fluent ★750](https://github.com/vapor/fluent) - Simple ActiveRecord implementation for working with your database in Swift. :large_orange_diamond:
* [ParseAlternatives ★2601](https://github.com/relatedcode/ParseAlternatives) - A collaborative list of Parse alternative backend service providers.
* [TypedDefaults ★109](https://github.com/tasanobu/TypedDefaults) - TypedDefaults is a utility library to type-safely use NSUserDefaults. :large_orange_diamond:
* [realm-cocoa-converter ★140](https://github.com/realm/realm-cocoa-converter) - A library that provides the ability to import/export Realm files from a variety of data container formats. :large_orange_diamond:
* [YapDatabaseExtensions ★79](https://github.com/danthorpe/YapDatabaseExtensions) - YapDatabase extensions for use with Swift :large_orange_diamond:
* [RealmGeoQueries ★98](https://github.com/mhergon/RealmGeoQueries) - RealmGeoQueries simplifies spatial queries with Realm Cocoa. In the absence of and official functions, this library provide the possibility to do proximity search.  :large_orange_diamond:[e]
* [SwiftMongoDB ★267 ⏳1Y](https://github.com/Danappelxx/SwiftMongoDB) - A MongoDB interface for Swift :large_orange_diamond:
* [ObjectiveRocks ★37](https://github.com/iabudiab/ObjectiveRocks) - An Objective-C wrapper of Facebook's RocksDB - A Persistent Key-Value Store for Flash and RAM Storage.
* [OHMySQL ★35](https://github.com/oleghnidets/OHMySQL) - An Objective-C wrapper of MySQL C API.
* [SwiftStore ★58](https://github.com/hemantasapkota/SwiftStore) - Key-Value store for Swift backed by LevelDB :large_orange_diamond:
* [OneStore ★18](https://github.com/muukii/OneStore) - A single value proxy for NSUserDefaults, with clean API. :large_orange_diamond:
* [MongoDB](https://github.com/PerfectlySoft/Perfect-MongoDB) - A Swift wrapper around the mongo-c client library, enabling access to MongoDB servers. Part of the [Perfect ★12367](https://github.com/PerfectlySoft/Perfect) project, but stand-alone. SPM and Swift 3 support.
* [SQLite](https://github.com/PerfectlySoft/Perfect-SQLite) - A Swift wrapper around the SQLite 3 client library, enabling access to SQLite servers. Part of the [Perfect ★12367](https://github.com/PerfectlySoft/Perfect) project, but stand-alone. SPM and Swift 3 support.
* [MySQL](https://github.com/PerfectlySoft/Perfect-MySQL) - A Swift wrapper around the MySQL client library, enabling access to MySQL servers. Part of the [Perfect ★12367](https://github.com/PerfectlySoft/Perfect) project, but stand-alone. SPM and Swift 3 support.
* [Redis](https://github.com/PerfectlySoft/Perfect-Redis) - A Swift wrapper around the Redis client library, enabling access to Redis. Part of the [Perfect ★12367](https://github.com/PerfectlySoft/Perfect) project, but stand-alone. SPM and Swift 3 support.
* [PostgreSQL](https://github.com/PerfectlySoft/Perfect-PostgreSQL) - A Swift wrapper around the libpq client library, enabling access to PostgreSQL servers. Part of the [Perfect ★12367](https://github.com/PerfectlySoft/Perfect) project, but stand-alone. SPM and Swift 3 support.
* [FileMaker](https://github.com/PerfectlySoft/Perfect-FileMaker) - A Swift wrapper around the FileMaker XML Web publishing interface, enabling access to FileMaker servers. Part of the [Perfect ★12367](https://github.com/PerfectlySoft/Perfect) project, but stand-alone. SPM and Swift 3 support.
* [Nora ★203](https://github.com/SD10/Nora) - Nora is a Firebase abstraction layer for working with FirebaseDatabase and FirebaseStorage. :large_orange_diamond:
* [PersistentStorageSerializable ★163](https://github.com/IvanRublev/PersistentStorageSerializable) - Swift library that makes easier to serialize the user's preferences (app's settings) with system User Defaults or Property List file on disk. :large_orange_diamond:
* [WCDB ★4400](https://github.com/Tencent/wcdb) - WCDB is an efficient, complete, easy-to-use mobile database framework for iOS, macOS.
* [StorageKit ★163](https://github.com/StorageKit/StorageKit) - Your Data Storage Troubleshooter 🛠
* [UserDefaults ★788](https://github.com/nmdias/DefaultsKit) - Simple, Strongly Typed UserDefaults for iOS, macOS and tvOS :large_orange_diamond:
* [Default ★278](https://github.com/Nirma/Default) - Modern interface to UserDefaults + Codable support :large_orange_diamond:
* [IceCream ★600](https://github.com/caiyue1993/IceCream) - Sync Realm Database with CloudKit :large_orange_diamond:

## Data Structures / Algorithms
* [SwiftSortedList ★4 ⏳1Y](https://github.com/bemindinteractive/SwiftSortedList) - A sorted list implementation written in Swift :large_orange_diamond:
* [Changeset ★701](https://github.com/osteslag/Changeset) - Minimal edits from one collection to another :large_orange_diamond:
* [BTree ★947](https://github.com/attaswift/BTree) - Fast ordered collections for Swift using in-memory B-trees :large_orange_diamond:
* [SwiftStructures ★1775](https://github.com/waynewbishop/SwiftStructures) - Examples of commonly used data structures and algorithms in Swift. :large_orange_diamond:
* [diff ★82](https://github.com/soffes/diff) - Simple diff library in pure Swift :large_orange_diamond:
* [Brick ★53](https://github.com/hyperoslo/Brick) - :droplet: A generic view model for both basic and complex scenarios :large_orange_diamond:
* [Algorithm ★596](https://github.com/CosmicMind/Algorithm) - Algorithm is a collection of data structures that are empowered by a probability toolset. :large_orange_diamond:
* [AnyObjectConvertible ★56 ⏳1Y](https://github.com/tarunon/AnyObjectConvertible) - Convert your own struct/enum to AnyObject easily. :large_orange_diamond:
* [Dollar ★3764](https://github.com/ankurp/Dollar) - A functional tool-belt for Swift Language similar to Lo-Dash or Underscore.js in Javascript https://www.dollarswift.org/. :large_orange_diamond:
* [Result ★1865](https://github.com/antitypical/Result) - Swift type modeling the success/failure of arbitrary operations. :large_orange_diamond:
* [EKAlgorithms ★2272](https://github.com/EvgenyKarkan/EKAlgorithms) - Some well known CS algorithms & data structures in Objective-C.
* [Monaka ★22 ⏳1Y](https://github.com/naru-jpn/Monaka) - Convert custom struct and fundamental values to NSData.
* [Buffer ★330](https://github.com/alexdrone/Buffer) - Swift μ-framework for efficient array diffs, collection observation and cell configuration. :large_orange_diamond:
* [SwiftGraph ★330](https://github.com/davecom/SwiftGraph) - Graph data structure and utility functions in pure Swift. :large_orange_diamond:
* [SwiftPriorityQueue ★233](https://github.com/davecom/SwiftPriorityQueue) - A priority queue with a classic binary heap implementation in pure Swift. :large_orange_diamond:
* [Pencil ★71](https://github.com/naru-jpn/pencil) - Write values to file and read it more easily. :large_orange_diamond:
* [HeckelDiff ★37](https://github.com/mcudich/HeckelDiff) - A fast Swift diffing library. :large_orange_diamond:
* [Dekoter ★20](https://github.com/artemstepanenko/Dekoter) - `NSCoding`'s counterpart for Swift structs. :large_orange_diamond:
* [swift-algorithm-club ★14946](https://github.com/raywenderlich/swift-algorithm-club) - Algorithms and data structures in Swift, with explanations! :large_orange_diamond:
+* [Impeller ★91](https://github.com/mentalfaculty/impeller) - A Distributed Value Store in Swift :large_orange_diamond:

## Date & Time

* [Timepiece ★2362](https://github.com/naoty/Timepiece) - Intuitive NSDate extensions in Swift :large_orange_diamond:
* [SwiftDate ★3393](https://github.com/malcommac/SwiftDate) - Easy NSDate Management in Swift 2.0 :large_orange_diamond:
* [SwiftMoment ★1495](https://github.com/akosma/SwiftMoment) - A time and calendar manipulation library written in Swift 2 :large_orange_diamond:
* [DateTools ★5838](https://github.com/MatthewYork/DateTools) - Dates and times made easy in Objective-C
* [SwiftyTimer ★917](https://github.com/radex/SwiftyTimer) - Swifty API for NSTimer :large_orange_diamond:
* [DateHelper ★867](https://github.com/melvitax/DateHelper) - Convenience extension for NSDate in Swift :large_orange_diamond:
* [iso-8601-date-formatter ★598](https://github.com/boredzo/iso-8601-date-formatter) - A Cocoa NSFormatter subclass to convert dates to and from ISO-8601-formatted strings. Supports calendar, week, and ordinal formats.
* [EmojiTimeFormatter ★73 ⏳1Y](https://github.com/thomaspaulmann/EmojiTimeFormatter) - Format your dates/times as emojis. :large_orange_diamond:
* [Kronos ★233](https://github.com/lyft/Kronos) - Elegant NTP date library in Swift :large_orange_diamond:
* [TrueTime ★213](https://github.com/instacart/TrueTime.swift) - Get the true current time impervious to device clock time changes. (NTP library for Swift) . :large_orange_diamond:
* [10Clock ★437](https://github.com/joedaniels29/10Clock) - This Control is a beautiful time-of-day picker heavily inspired by the iOS 10 "Bedtime" timer. :large_orange_diamond:
* [NSDate-TimeAgo ★1698](https://github.com/kevinlawler/NSDate-TimeAgo) - A "time ago", "time since", "relative date", or "fuzzy date" category for NSDate and iOS, Objective-C, Cocoa Touch, iPhone, iPad.
* [AnyDate ★146](https://github.com/Kawoou/AnyDate) - Swifty Date & Time API inspired from Java 8 DateTime API. :large_orange_diamond:
* [TimeZonePicker ★89](https://github.com/gligorkot/TimeZonePicker) - A TimeZonePicker UIViewController similar to the iOS Settings app. :large_orange_diamond:
* [Time ★610](https://github.com/dreymonde/Time) - Type-safe time calculations in Swift, powered by generics. :large_orange_diamond:[e]
* [Chronology ★745](https://github.com/davedelong/Chronology) - Building a better date/time library :large_orange_diamond:

## Debugging
* [Xniffer](https://github.com/vsouza/awesome-ios/issues/1841) - A swift network profiler built on top of URLSession. 🔶
* [Netfox ★2007](https://github.com/kasketis/netfox) - A lightweight, one line setup, iOS / macOS network debugging library! :large_orange_diamond:
* [PonyDebugger ★5484](https://github.com/square/PonyDebugger) - Remote network and data debugging for your native iOS app using Chrome Developer Tools.
* [DBDebugToolkit ★572](https://github.com/dbukowski/DBDebugToolkit) - Set of easy to use debugging tools for iOS developers & QA engineers.
* [Flex ★8548](https://github.com/Flipboard/FLEX) - An in-app debugging and exploration tool for iOS.
* [chisel ★6349](https://github.com/facebook/chisel) - Collection of LLDB commands to assist debugging iOS apps.
* [Alpha ★660](https://github.com/Legoless/Alpha) - Next generation debugging framework for iOS.
* [AEConsole ★76](https://github.com/tadija/AEConsole) - Customizable Console UI overlay with debug log on top of your iOS App. :large_orange_diamond:
* [GodEye ★2783](https://github.com/zixun/GodEye) - Automatically display Log,Crash,Network,ANR,Leak,CPU,RAM,FPS,NetFlow,Folder and etc with one line of code based on Swift. :large_orange_diamond:
* [NetworkEye ★1020](https://github.com/coderyi/NetworkEye) - a iOS network debug library, It can monitor HTTP requests within the App and displays information related to the request.
* [Dotzu ★1193](https://github.com/remirobert/Dotzu) - iOS app debugger while using the app. Crash report, logs, network.
* [Hyperion ★194](https://github.com/willowtreeapps/Hyperion-iOS) - In-app design review tool to inspect measurements, attributes, and animations.

## EventBus
* [SwiftEventBus ★586](https://github.com/cesarferreira/SwiftEventBus) - A publish/subscribe event bus optimized for iOS8. :large_orange_diamond:
* [PromiseKit ★8464](https://github.com/mxcl/PromiseKit) - Promises for iOS and macOS.
* [Bolts ★5212](https://github.com/BoltsFramework/Bolts-ObjC) - Bolts is a collection of low-level libraries designed to make developing mobile apps easier, including tasks (promises) and app links (deep links).
* [SwiftTask ★1735](https://github.com/ReactKit/SwiftTask) - Promise + progress + pause + cancel + retry for Swift.  :large_orange_diamond:
* [When ★120](https://github.com/vadymmarkov/When) - A lightweight implementation of Promises in Swift. :large_orange_diamond:
* [then🎬 ★579](https://github.com/freshOS/then) - Elegant Async code in Swift. :large_orange_diamond:
* [Bolts-Swift ★1035](https://github.com/BoltsFramework/Bolts-Swift) - Bolts is a collection of low-level libraries designed to make developing mobile apps easier. :large_orange_diamond:
* [RWPromiseKit ★99](https://github.com/deput/RWPromiseKit) - A light-weighted Promise library for Objective-C
* [FutureLib ★38](https://github.com/couchdeveloper/FutureLib) - FutureLib is a pure Swift 2 library implementing Futures & Promises inspired by Scala. :large_orange_diamond:
* [SwiftNotificationCenter ★453](https://github.com/100mango/SwiftNotificationCenter) - A Protocol-Oriented NotificationCenter which is type safe, thread safe and with memory safety :large_orange_diamond:
* [FutureKit ★673](https://github.com/FutureKit/FutureKit) - A Swift based Future/Promises Library for iOS and macOS. :large_orange_diamond:
* [signals-ios ★493](https://github.com/uber/signals-ios) - Typeful eventing
* [BrightFutures ★1559](https://github.com/Thomvis/BrightFutures) - Write great asynchronous code in Swift using futures and promises. :large_orange_diamond:
* [NoticeObserveKit ★111](https://github.com/marty-suzuki/NoticeObserveKit) - NoticeObserveKit is type-safe NotificationCenter wrapper that associates notice type with info type. :large_orange_diamond:
* [Hydra ★1252](https://github.com/malcommac/Hydra) - Promises & Await - Write better async code in Swift :large_orange_diamond:
* [Promis ★53](https://github.com/albertodebortoli/Promis) - The easiest Future and Promises framework in Swift. No magic. No boilerplate. :large_orange_diamond:
* [Bluebird.swift ★23](https://github.com/AndrewBarba/Bluebird.swift) - Promise/A+, Bluebird inspired, implementation in Swift 4. :large_orange_diamond:

## Files
* [FileKit ★1645](https://github.com/nvzqz/FileKit) - Simple and expressive file management in Swift. :large_orange_diamond:
* [Zip ★1119](https://github.com/marmelroy/Zip) - Swift framework for zipping and unzipping files. :large_orange_diamond:
* [FileBrowser ★1123](https://github.com/marmelroy/FileBrowser) - Powerful Swift file browser for iOS. :large_orange_diamond:
* [Ares ★112 ⏳1Y](https://github.com/indragiek/Ares) - Zero-setup P2P file transfer between Macs and iOS devices :large_orange_diamond:
* [FileProvider ★185](https://github.com/amosavian/FileProvider) - FileManager replacement for Local, iCloud and Remote (WebDAV/FTP/Dropbox/OneDrive/SMB2) files on iOS/tvOS and macOS. :large_orange_diamond:
* [KZFileWatchers ★783](https://github.com/krzysztofzablocki/KZFileWatchers) - A micro-framework for observing file changes, both local and remote. Helpful in building developer tools. :large_orange_diamond:
* [ZipArchive ★3184](https://github.com/ZipArchive/ZipArchive) - ZipArchive is a simple utility class for zipping and unzipping files on iOS and Mac.
* [FileExplorer ★510](https://github.com/Augustyniak/FileExplorer) - Powerful file browser for iOS that allows its users to choose and remove files and/or directories. :large_orange_diamond:
* [ZIPFoundation ★827](https://github.com/weichsel/ZIPFoundation) - Effortless ZIP Handling in Swift :large_orange_diamond:

## Functional Programming
* [Forbind ★43](https://github.com/ulrikdamm/Forbind) - Functional chaining and promises in Swift. :large_orange_diamond:
* [Funky ★12 ⏳1Y](https://github.com/brynbellomy/Funky) - Functional programming tools and experiments in Swift. :large_orange_diamond:
* [LlamaKit ★636 ⏳2Y](https://github.com/LlamaKit/LlamaKit) - Collection of must-have functional Swift tools. :large_orange_diamond:
* [Oriole ★11 ⏳2Y](https://github.com/tptee/Oriole) - A functional utility belt implemented as Swift 2.0 protocol extensions. :large_orange_diamond:[e]
* [Prelude ★313 ⏳1Y](https://github.com/robrix/Prelude) - Swift µframework of simple functional programming tools. :large_orange_diamond:
* [Swiftx ★181](https://github.com/typelift/Swiftx) - Functional data types and functions for any project. :large_orange_diamond:
* [Swiftz ★3013](https://github.com/typelift/Swiftz) -  Functional programming in Swift. :large_orange_diamond:
* [OptionalExtensions ★171](https://github.com/RuiAAPeres/OptionalExtensions) - Swift µframework with extensions for the  Optional Type. :large_orange_diamond:[e]
* [Hookah ★56 ⏳1Y](https://github.com/HookahSwift/Hookah) - Hookah is a functional library for Swift. It's inspired by LoDash, Underscore project. :large_orange_diamond:
* [Argo ★3214](https://github.com/thoughtbot/Argo) - Functional JSON parsing library for Swift :large_orange_diamond:
* [Runes ★659](https://github.com/thoughtbot/Runes) - Infix operators for monadic functions in Swift. :large_orange_diamond:
* [ifAction ★2](https://github.com/trilliwon/ifAction) - Custom if for Optional and Boolean :large_orange_diamond: [e]

## Games
* [Sage ★330](https://github.com/nvzqz/Sage) - A cross-platform chess library for Swift. :large_orange_diamond:
* [ShogibanKit ★50](https://github.com/codelynx/ShogibanKit) - ShogibanKit is a framework for implementing complex Japanese Chess (Shogii) in Swift. No UI, nor AI. :large_orange_diamond:
* [SKTiled ★95](https://github.com/mfessenden/SKTiled) - Swift framework for working with Tiled assets in SpriteKit :large_orange_diamond:
* [CollectionNode ★42](https://github.com/bwide/CollectionNode) - A swift framework for a collectionView in SpriteKit :large_orange_diamond:

## Gesture
* [Tactile ★629 ⏳1Y](https://github.com/delba/Tactile) - A better way to handle gestures on iOS :large_orange_diamond:
* [SwiftyGestureRecognition ★141](https://github.com/b3ll/SwiftyGestureRecognition) - Aids with prototyping UIGestureRecognizers in Xcode Playgrounds :large_orange_diamond:
* [DBPathRecognizer ★1083](https://github.com/didierbrun/DBPathRecognizer) - Gesture recognizer tool [Swift / iOS] :large_orange_diamond:
* [Sensitive ★464](https://github.com/igormatyushkin014/Sensitive) - Fresh look at work with gestures in Swift. :large_orange_diamond:
* [SplitViewDragAndDrop ★288](https://github.com/MarioIannotta/SplitViewDragAndDrop) - Easily add drag and drop to pass data between your apps in split view mode. :large_orange_diamond:

## Graphics
* [Graphicz ★31](https://github.com/SwiftKitz/Graphicz) - Light-weight, operator-overloading-free complements to CoreGraphics! :large_orange_diamond:
* [PKCoreTechniques ★143 ⏳2Y](https://github.com/pkluz/PKCoreTechniques) - The code for my CoreGraphics+CoreAnimation talk, held during the 2012 iOS Game Design Seminar at the Technical University Munich.
* [MPWDrawingContext ★91 ⏳2Y](https://github.com/mpw/MPWDrawingContext) - An Objective-C wrapper for CoreGraphics CGContext
* [DePict ★29 ⏳1Y](https://github.com/davidcairns/DePict) - A simple, declarative, functional drawing framework, in Swift! :large_orange_diamond:
* [SwiftSVG ★843](https://github.com/mchoe/SwiftSVG) -  A single pass SVG parser with multiple interface options (String, NS/UIBezierPath, CAShapeLayer, and NS/UIView). :large_orange_diamond:
* [InkKit ★348](https://github.com/shaps80/InkKit) - Write-Once, Draw-Everywhere for iOS and macOS -- Now in Swift! :large_orange_diamond:
* [YYAsyncLayer ★353](https://github.com/ibireme/YYAsyncLayer) - iOS utility classes for asynchronous rendering and display.
* [NXDrawKit ★1000](https://github.com/Nicejinux/NXDrawKit) - NXDrawKit is a simple and easy but useful drawing kit for iPhone :large_orange_diamond:
* [jot ★1658](https://github.com/IFTTT/jot) - An iOS framework for easily adding drawings and text to images.
* [SVGKit ★2911](https://github.com/SVGKit/SVGKit) - Display and interact with SVG Images on iOS / macOS, using native rendering (CoreAnimation) (currently only supported for iOS - macOS code needs updating).
* [Snowflake ★809](https://github.com/onmyway133/Snowflake) - ❄️ SVG in Swift. :large_orange_diamond:
* [HxSTLParser ★11](https://github.com/victorgama/HxSTLParser) - Basic STL loader for SceneKit

## Hardware
#### Bluetooth
* [Discovery ★376 ⏳1Y](https://github.com/omergul/Discovery) - A very simple library to discover and retrieve data from nearby devices (even if the peer app works at background).
* [LGBluetooth ★144](https://github.com/LGBluetooth/LGBluetooth) - Simple, block-based, lightweight library over CoreBluetooth. Will clean up your Core Bluetooth related code.
* [PeerKit ★713](https://github.com/jpsim/PeerKit) An open-source Swift framework for building event-driven, zero-config Multipeer Connectivity apps. :large_orange_diamond:
* [BluetoothKit ★1582](https://github.com/rhummelmose/BluetoothKit) - Easily communicate between iOS/macOS devices using BLE. :large_orange_diamond:
* [Bluetonium ★125](https://github.com/e-sites/Bluetonium) - Bluetooth mapping in Swift :large_orange_diamond:
* [BlueCap ★421](https://github.com/troystribling/BlueCap) - iOS Bluetooth LE framework :large_orange_diamond:
* [Apple Family ★31](https://github.com/kirankunigiri/Apple-Family) - Quickly connect Apple devices together with Bluetooth, wifi, and USB.  :large_orange_diamond:
* [Bleu ★444](https://github.com/1amageek/Bleu) - BLE (Bluetooth LE) for U  :large_orange_diamond:
* [Bluejay ★603](https://github.com/steamclock/bluejay) - A simple Swift framework for building reliable Bluetooth LE apps. :large_orange_diamond:
* [BabyBluetooth ★3230](https://github.com/coolnameismy/BabyBluetooth) - The easiest way to use Bluetooth (BLE) in iOS/MacOS.
* [ExtendaBLE ★48](https://github.com/AntonTheDev/ExtendaBLE) - Simple Blocks-Based BLE Client for iOS/tvOS/watchOS/OSX/Android. Quickly configuration for centrals/peripherals, perform packet based read/write operations, and callbacks for characteristic updates.
* [PeerConnectivity ★25](https://github.com/rchatham/PeerConnectivity) - Functional wrapper for Apple's MultipeerConnectivity framework. :large_orange_diamond:

#### Camera
* [TGCameraViewController ★1405](https://github.com/tdginternet/TGCameraViewController) - Custom camera with AVFoundation. Beautiful, light and easy to integrate with iOS projects.
* [PBJVision ★1743](https://github.com/piemonte/PBJVision) - iOS camera engine, features touch-to-record video, slow motion video, and photo capture.
* [Cool-iOS-Camera ★1176](https://github.com/GabrielAlva/Cool-iOS-Camera) - A fully customisable and modern camera implementation for iOS made with AVFoundation.
* [SCRecorder ★2705](https://github.com/rFlex/SCRecorder) - Camera engine with Vine-like tap to record, animatable filters, slow motion, segments editing.
* [ALCameraViewController ★1478](https://github.com/AlexLittlejohn/ALCameraViewController) - A camera view controller with custom image picker and image cropping. Written in Swift. :large_orange_diamond:
* [ImagePicker ★3278](https://github.com/hyperoslo/ImagePicker) - Reinventing the way ImagePicker works. :large_orange_diamond:
* [CameraManager ★646](https://github.com/imaginary-cloud/CameraManager) - Simple Swift class to provide all the configurations you need to create custom camera view in your app. :large_orange_diamond:
* [RSBarcodes_Swift ★554](https://github.com/yeahdongcn/RSBarcodes_Swift) - 1D and 2D barcodes reader and generators for iOS 8 with delightful controls. Now Swift. :large_orange_diamond:
* [LLSimpleCamera ★1089](https://github.com/omergul/LLSimpleCamera) - A simple, customizable camera control - video recorder for iOS.
* [Fusuma ★1891](https://github.com/ytakzk/Fusuma) - Instagram-like photo browser and a camera feature with a few line of code in Swift. :large_orange_diamond:
* [BarcodeScanner ★780](https://github.com/hyperoslo/BarcodeScanner) - 🔎 Simple and beautiful barcode scanner. :large_orange_diamond:
* [JVTImageFilePicker ★52 ⏳1Y](https://github.com/mcmatan/JVTImageFilePicker) - Easy and beautiful way for a user to pick content, files or images. Written in Objective C.
* [HorizonSDK-iOS ★163](https://github.com/HorizonCamera/HorizonSDK-iOS) - State of the art real-time video recording / photo shooting iOS library.
* [FastttCamera ★1729](https://github.com/IFTTT/FastttCamera) - Fasttt and easy camera framework for iOS with customizable filters
* [DKCamera ★33](https://github.com/zhangao0086/DKCamera) - A lightweight & simple camera framework for iOS. Written in Swift. 🔶
* [NextLevel ★980](https://github.com/NextLevel/NextLevel) - Next Level is a media capture camera library for iOS. :large_orange_diamond:
* [CameraEngine ★423](https://github.com/remirobert/CameraEngine) - 🐒📷 Camera engine for iOS, written in Swift, above AVFoundation. 🐒 :large_orange_diamond:
* [SwiftyCam ★1041](https://github.com/Awalz/SwiftyCam) -  A Snapchat Inspired iOS Camera Framework written in Swift. :large_orange_diamond:
* [CameraBackground ★16](https://github.com/yonat/CameraBackground) -  Show camera layer as a background to any UIView. :large_orange_diamond:
* [Lumina ★80](https://github.com/dokun1/Lumina) - Full service camera that takes photos, videos, streams frames, detects metadata, and streams CoreML predictions :largeorangediamond:
* [RAImagePicker ★5](https://github.com/rallahaseh/RAImagePicker) - RAImagePicker is a protocol-oriented framework that provides custom features from the built-in Image Picker Edit.

#### Force Touch
* [QuickActions ★202](https://github.com/ricardopereira/QuickActions) - Swift wrapper for iOS Home Screen Quick Actions (App Icon Shortcuts) :large_orange_diamond:
* [JustPeek ★62](https://github.com/justeat/JustPeek) - JustPeek is an iOS Library that adds support for Force Touch-like Peek and Pop interactions on devices that do not natively support this kind of interaction. :large_orange_diamond:
* [PeekView ★107](https://github.com/itsmeichigo/PeekView) - PeekView supports peek, pop and preview actions for iOS devices without 3D Touch capibility. 🔶

#### iBeacon
* [Proxitee ★15 ⏳2Y](https://github.com/Proxitee/iOS-SDK) - Allows developers to create proximity aware applications utilizing iBeacons & geo fences.
* [OWUProximityManager ★359 ⏳4Y](https://github.com/ohayon/OWUProximityManager) - iBeacons + CoreBluetooth.
* [Vicinity ★364 ⏳1Y](https://github.com/Instrument/Vicinity) - Vicinity replicates iBeacons (by analyzing RSSI) and supports broadcasting and detecting low-energy Bluetooth devices in the background.
* [BeaconEmitter ★807 ⏳3Y](https://github.com/lgaches/BeaconEmitter) - Turn your Mac as an iBeacon.
* [MOCA Proximity](https://mocaplatform.com/features) - Paid proximity marketing platform that lets you add amazing proximity  experiences to your app.
* [JMCBeaconManager ★134 ⏳1Y](https://github.com/izotx/JMCBeaconManager) - An iBeacon Manager class that is responsible for detecting beacons nearby. 🔶

#### Location
* [IngeoSDK ★91](https://github.com/IngeoSDK/ingeo-ios-sdk) - Always-On Location monitoring framework for iOS.
* [LocationManager ★2160](https://github.com/intuit/LocationManager) - Provides a block-based asynchronous API to request the current location, either once or continuously.
* [SwiftLocation ★1483](https://github.com/malcommac/SwiftLocation) - Location & Beacon Monitoring in Swift :large_orange_diamond:
* [SOMotionDetector ★991 ⏳1Y](https://github.com/SocialObjects-Software/SOMotionDetector) - Simple library to detect motion. Based on location updates and acceleration.
* [LocationPicker ★288](https://github.com/JeromeTan1997/LocationPicker) - A ready for use and fully customizable location picker for your app :large_orange_diamond:
* [BBLocationManager ★70](https://github.com/benzamin/BBLocationManager) - A Location Manager for easily implementing location services & geofencing in iOS.
* [set-simulator-location ★184](https://github.com/lyft/set-simulator-location) - CLI for setting location in the iOS simulator. :large_orange_diamond:

#### Other Hardware
* [MotionKit ★959](https://github.com/MHaroonBaig/MotionKit) - Get the data from Accelerometer, Gyroscope and Magnetometer in only Two or a few lines of code. CoreMotion now made insanely simple.
* [DarkLightning ★178](https://github.com/jensmeder/DarkLightning) - Simply the fastest way to transmit data between iOS/tvOS and macOS.
* [Deviice ★21](https://github.com/andrealufino/Deviice) - Simply library to detect the device on which the app is running (and some properties) 🔶
* [DeviceKit ★1665](https://github.com/dennisweissmann/DeviceKit) - DeviceKit is a value-type replacement of UIDevice. :large_orange_diamond:
* [Luminous ★184](https://github.com/andrealufino/Luminous) - Luminous is a big framework which can give you a lot of information (more than 50) about the current system. :large_orange_diamond:
* [Device ★1006](https://github.com/Ekhoo/Device) - Light weight tool for detecting the current device and screen size written in swift. :large_orange_diamond:
* [WatchShaker ★147](https://github.com/ezefranca/WatchShaker) - WatchShaker is a watchOS helper to get your ⌚️ shake movement written in swift. :large_orange_diamond:
* [WatchCon ★25](https://github.com/abdullahselek/WatchCon) - WatchCon is a tool which enables creating easy connectivity between iOS and WatchOS. ⌚️
* [TapticEngine ★163](https://github.com/WorldDownTown/TapticEngine) - TapticEngine generates iOS Device vibrations. :large_orange_diamond:
* [UIDeviceComplete ★215](https://github.com/Nirma/UIDeviceComplete) - UIDevice extensions that fill in the missing pieces. :large_orange_diamond:
* [NFCNDEFParse ★3](https://github.com/jvk75/NFCNDEFParse) - NFC Forum Well Known Type Data Parser for iOS11 and Core NFC. :large_orange_diamond:

## Layout
* [FlexboxLayout ★317](https://github.com/alexdrone/FlexboxLayout) - Port of Facebook's css-layout to Swift :large_orange_diamond:
* [Masonry ★15683](https://github.com/SnapKit/Masonry) - Harness the power of AutoLayout NSLayoutConstraints with a simplified, chainable and expressive syntax.
* [FLKAutoLayout ★1509](https://github.com/floriankugler/FLKAutoLayout) - UIView category which makes it easy to create layout constraints in code.
* [Façade ★709](https://github.com/mamaral/Facade) - Programmatic view layout for the rest of us - an autolayout alternative.
* [PureLayout ★6721](https://github.com/PureLayout/PureLayout) - The ultimate API for iOS & macOS Auto Layout — impressively simple, immensely powerful. Objective-C and Swift compatible.
* [SnapKit ★11278](https://github.com/SnapKit/SnapKit) - A Swift Autolayout DSL for iOS & macOS. :large_orange_diamond:
* [Cartography ★5984](https://github.com/robb/Cartography) - A declarative Auto Layout DSL for Swift :iphone::triangular_ruler: :large_orange_diamond:
* [AutoLayoutPlus ★26](https://github.com/ruipfcosta/AutoLayoutPlus) - A bit of steroids for AutoLayout, powered by Swift. :large_orange_diamond:
* [Neon ★4110](https://github.com/mamaral/Neon) - A powerful Swift programmatic UI layout framework. :large_orange_diamond:
* [MisterFusion ★265](https://github.com/marty-suzuki/MisterFusion) - A Swift DSL for AutoLayout. It is the extremely clear, but concise syntax, in addition, can be used in both Swift and Objective-C. :large_orange_diamond:
* [SwiftBox ★801](https://github.com/joshaber/SwiftBox) - Flexbox in Swift, using Facebook's css-layout. :large_orange_diamond:
* [ManualLayout ★273](https://github.com/isair/ManualLayout) - Easy to use and flexible library for manually laying out views and layers for iOS and tvOS. Supports AsyncDisplayKit. :large_orange_diamond:[e]
* [Stevia ★2152](https://github.com/freshOS/Stevia) - Elegant view layout for iOS. :large_orange_diamond:
* [Manuscript ★78](https://github.com/floriankrueger/Manuscript) - AutoLayoutKit in pure Swift. :large_orange_diamond:
* [FDTemplateLayoutCell ★8247](https://github.com/forkingdog/UITableView-FDTemplateLayoutCell) - Template auto layout cell for automatically UITableViewCell height calculating
* [SwiftAutoLayout ★648](https://github.com/indragiek/SwiftAutoLayout) - Tiny Swift DSL for Autolayout :large_orange_diamond:
* [FormationLayout ★52](https://github.com/evan-liu/FormationLayout) - Work with auto layout and size classes easily. :large_orange_diamond:
* [SwiftyLayout ★15](https://github.com/fhisa/SwiftyLayout) - Lightweight declarative auto-layout framework for Swift :large_orange_diamond:
* [Swiftstraints ★97](https://github.com/Skyvive/Swiftstraints) - Auto Layout In Swift Made Easy :large_orange_diamond:
* [SwiftBond ★3318](https://github.com/ReactiveKit/Bond) - Bond is a Swift binding framework that takes binding concepts to a whole new level. It's simple, powerful, type-safe and multi-paradigm. :large_orange_diamond:
* [Restraint ★74](https://github.com/puffinsupply/Restraint) - Minimal Auto Layout in Swift :large_orange_diamond:
* [EasyPeasy ★1554](https://github.com/nakiostudio/EasyPeasy) - Auto Layout made easy  :large_orange_diamond:
* [Auto Layout Magic](http://akordadev.github.io/AutoLayoutMagic/) - Build 1 scene, let Auto Layout Magic generate the  constraints for you!  Scenes look great across all devices! :large_orange_diamond:
* [Anchorman ★61](https://github.com/mergesort/Anchorman) - An autolayout library for the damn fine citizens of San Diego. :large_orange_diamond:
* [LayoutKit ★2216](https://github.com/linkedin/LayoutKit) - LayoutKit is a fast view layout library for iOS. :large_orange_diamond:
* [MarkupKit ★438](https://github.com/gk-brown/MarkupKit) - Declarative UI for iOS applications
* [Relayout ★579](https://github.com/stevestreza/Relayout) - Swift microframework for declaring Auto Layout constraints functionally :large_orange_diamond:
* [Anchorage ★299](https://github.com/Raizlabs/Anchorage) - A collection of operators and utilities that simplify iOS layout code. :large_orange_diamond:
* [Compose ★127](https://github.com/VivaReal/Compose) - Compose is a library that helps you compose complex and dynamic views. :large_orange_diamond:
* [BrickKit ★566](https://github.com/wayfair/brickkit-ios) - With BrickKit, you can create complex and responsive layouts in a simple way. It's easy to use and easy to extend. Create your own reusable bricks and behaviors. :large_orange_diamond:
* [Framezilla ★80](https://github.com/Otbivnoe/Framezilla) - Elegant library which wraps working with frames with a nice chaining syntax. :large_orange_diamond:
* [TinyConstraints ★2058](https://github.com/roberthein/TinyConstraints) -  The syntactic sugar that makes Auto Layout sweeter for human use. :large_orange_diamond:
* [MyLinearLayout ★2531](https://github.com/youngsoft/MyLinearLayout) - MyLayout is a powerful iOS UI framework implemented by Objective-C. It integrates the functions with Android Layout,iOS AutoLayout,SizeClass, HTML CSS float and flexbox and bootstrap.
* [SugarAnchor ★19](https://github.com/ashikahmad/SugarAnchor) - Same native NSLayoutAnchor & NSLayoutConstraints; but with more natural and easy to read syntactic sugar. Typesafe, concise & readable. :large_orange_diamond:
* [Anchors ★103](https://github.com/onmyway133/Anchors) - Declarative, extensible, powerful Auto Layout for iOS 8+ and macOS 10.10+ :large_orange_diamond:
* [PinLayout ★729](https://github.com/mirego/PinLayout) - Extremely Fast views layouting without auto layout. No magic, pure code, full control and blazing fast. Concise syntax, intuitive, readable & chainable. 🔶
* [SnapLayout ★9](https://github.com/sp71/SnapLayout) - Concise Auto Layout API to chain programmatic constraints while easily updating existing constraints. 🔶[e]
* [Cupcake ★173](https://github.com/nerdycat/Cupcake) - An easy way to create and layout UI components for iOS. :large_orange_diamond:
* [MiniLayout ★4](https://github.com/yonat/MiniLayout) - Minimal AutoLayout convenience layer. Program constraints succinctly. :large_orange_diamond:
* [Bamboo ★44](https://github.com/wordlessj/Bamboo) - Bamboo makes Auto Layout (and manual layout) elegant and concise. :large_orange_diamond:
* [FlexLayout](https://github.com/layoutBox/FlexLayout) - FlexLayout gently wraps the highly optimized [facebook/yoga ★8786](https://github.com/facebook/yoga) flexbox implementation in a concise, intuitive & chainable syntax. 🔶
* [Layout ★1188](https://github.com/schibsted/layout) - A declarative UI framework for iOS :large_orange_diamond:
* [CGLayout ★21](https://github.com/k-o-d-e-n/CGLayout) - Powerful autolayout framework based on constraints, that can manage UIView(NSView), CALayer and not rendered views. Not Apple Autolayout wrapper. 🔶
* [YogaKit](https://github.com/facebook/yoga/tree/master/YogaKit) - Powerful layout engine which implements Flexbox. Developed and maintained by Facebook.
* [FlightLayout ★14](https://github.com/AntonTheDev/FlightLayout) -  Balanced medium between manual layout and auto-layout. Great for calculating frames for complex animations.
* [QLayout ★1](https://github.com/josejuanqm/QLayout) - AutoLayout Utility for iOS. 🔶

## Localization
* [Hodor ★493](https://github.com/Aufree/Hodor) - Simple solution to localize your iOS App.
* [Swifternalization ★533](https://github.com/tomkowz/Swifternalization) - Localize iOS apps in a smarter way using JSON files. Swift framework. :large_orange_diamond:
* [Rubustrings ★48 ⏳1Y](https://github.com/dcordero/Rubustrings) - Check the format and consistency of Localizable.strings files
* [BartyCrouch ★298](https://github.com/Flinesoft/BartyCrouch) - Incrementally update/translate your Strings files from Code and Storyboards/XIBs. :large_orange_diamond:
* [LocalizationKit ★913](https://github.com/willpowell8/LocalizationKit_iOS) - Localization management in realtime from a web portal. Easily manage your texts and translations without redeploy and resubmission.
* [Localize-Swift ★1545](https://github.com/marmelroy/Localize-Swift) - Swift 2.0 friendly localization and i18n with in-app language switching :large_orange_diamond:
* [LocalizedView ★8 ⏳1Y](https://github.com/darkcl/LocalizedView) - Setting up application specific localized string within Xib file.
* [transai ★47](https://github.com/Jintin/transai) - command line tool help you manage localization string files.
* [lokalise](https://lokalise.co/en ) - Translation platform for software developers. Free for open source projects
* [Strsync ★102](https://github.com/metasmile/strsync) - Automatically translate and synchronize .strings files from base language.
* [IBLocalizable ★398](https://github.com/PiXeL16/IBLocalizable) - Localize your views directly in Interface Builder with IBLocalizable :large_orange_diamond:
* [nslocalizer ★122](https://github.com/samdmarshall/nslocalizer) - A tool for finding missing and unused NSLocalizedStrings

## Logging
* [CleanroomLogger ★1088](https://github.com/emaloney/CleanroomLogger) - A configurable and extensible Swift-based logging API that is simple, lightweight and performant. :large_orange_diamond:
* [CocoaLumberjack ★9594](https://github.com/CocoaLumberjack/CocoaLumberjack) - A fast & simple, yet powerful & flexible logging framework for Mac and iOS.
* [NSLogger ★4101](https://github.com/fpillet/NSLogger) - a high performance logging utility which displays traces emitted by client applications running on macOS, iOS and Android.
* [QorumLogs ★722](https://github.com/goktugyil/QorumLogs) — Swift Logging Utility for Xcode & Google Docs. :large_orange_diamond:
* [Log ★684](https://github.com/delba/Log) - A logging tool with built-in themes, formatters, and a nice API to define your owns. :large_orange_diamond:
* [Rainbow ★929](https://github.com/onevcat/Rainbow) - Delightful console output for Swift developers. :large_orange_diamond:
* [SwiftyBeaver ★3203](https://github.com/SwiftyBeaver/SwiftyBeaver) - Convenient logging during development & release in Swift 2 & 3 :large_orange_diamond:
* [SwiftyTextTable ★103](https://github.com/scottrhoyt/SwiftyTextTable) - A lightweight tool for generating text tables. :large_orange_diamond:
* [Watchdog ★1437](https://github.com/wojteklu/Watchdog) - Class for logging excessive blocking on the main thread :large_orange_diamond:
* [XCGLogger ★2699](https://github.com/DaveWoodCom/XCGLogger) - A debug log framework for use in Swift projects. Allows you to log details to the console (and optionally a file), just like you would have with NSLog or println, but with additional information, such as the date, function name, filename and line number. :large_orange_diamond:
* [puree ★150](https://github.com/cookpad/puree-ios) - A log collector for iOS
* [Colors ★25](https://github.com/icodeforlove/Colors) - A pure Swift library for using ANSI codes. Basically makes command-line coloring and styling very easy! :large_orange_diamond:[e]
* [Loggerithm ★265](https://github.com/honghaoz/Loggerithm) - A lightweight Swift logger, uses `print` in development and `NSLog` in production. Support colourful and formatted output. :large_orange_diamond:
* [AELog ★13](https://github.com/tadija/AELog) - Simple, lightweight and flexible debug logging framework written in Swift. :large_orange_diamond:
* [ReflectedStringConvertible ★49](https://github.com/mattcomi/ReflectedStringConvertible) - A protocol that allows any class to be printed as if it were a struct. :large_orange_diamond:
* [Evergreen ★67](https://github.com/knly/Evergreen) - Most natural Swift logging :large_orange_diamond:
* [SwiftTrace ★123 ⏳1Y](https://github.com/johnno1962/SwiftTrace) - Trace Swift and Objective-C method invocations :large_orange_diamond:
* [Willow ★1004](https://github.com/Nike-Inc/Willow) - Willow is a powerful, yet lightweight logging library written in Swift. :large_orange_diamond:
* [Bugfender ★35](https://github.com/bugfender/BugfenderSDK-iOS) - Cloud storage for your app logs. Track user behaviour to find problems in your mobile apps.
* [LxDBAnything ★420](https://github.com/DeveloperLx/LxDBAnything) - Automate box any value! Print log without any format control symbol! Change debug habit thoroughly!
* [XLTestLog ★59 ⏳1Y](https://github.com/xareelee/XLTestLog) - Styling and coloring your XCTest logs on Xcode Console
* [XLFacility ★267](https://github.com/swisspol/XLFacility) - Elegant and extensive logging facility for macOS & iOS (includes database, Telnet and HTTP servers)
* [Atlantis ★200](https://github.com/DrewKiino/Atlantis) - A powerful input-agnostic swift logging framework made to speed up development with maximum readability. :large_orange_diamond:
* [StoryTeller ★8 ⏳1Y](https://github.com/drekka/StoryTeller) - Taking a completely different approach to logging, Story Teller replacing fixed logging levels in It then uses dynamic expressions to control the logging so you only see what is important.
* [LumberMill ★2 ⏳1Y](https://github.com/ubclaunchpad/LumberMill) - Stupidly simple logging for iOS 10 and Swift 3.0
* [TinyConsole ★1727](https://github.com/Cosmo/TinyConsole) - A tiny log console to display information while using your iOS app. Written in Swift 3. :large_orange_diamond:
* [Lighty ★37](https://github.com/abdullahselek/Lighty) - Easy to use and lightweight logger for iOS, macOS, tvOS, watchOS and Linux with Swift 3. :large_orange_diamond:
* [JustLog ★191](https://github.com/justeat/JustLog) - Console, file and remote Logstash logging via TCP socket. :large_orange_diamond:
* [Twitter Logging Service ★160](https://github.com/twitter/ios-twitter-logging-service) - Twitter Logging Service is a robust and performant logging framework for iOS clients.
* [Reqres ★20](https://github.com/AckeeCZ/Reqres) - Network request and response body logger with Alamofire support :large_orange_diamond:

## Machine Learning
* [Swift-Brain ★298](https://github.com/vlall/Swift-Brain) - Artificial Intelligence/Machine Learning data structures and Swift algorithms for future iOS development. Bayes theorem, Neural Networks, and more AI. :large_orange_diamond:
* [AIToolbox ★633](https://github.com/KevinCoble/AIToolbox) - A toolbox of AI modules written in Swift: Graphs/Trees, Linear Regression, Support Vector Machines, Neural Networks, PCA, KMeans, Genetic Algorithms, MDP, Mixture of Gaussians. :large_orange_diamond:
* [Tensorflow-iOS](https://github.com/tensorflow/tensorflow/tree/master/tensorflow/examples/ios) - The official Google-built powerful neural network library port for iOS.
* [Bender ★1292](https://github.com/xmartlabs/Bender) - Easily craft fast Neural Networks. Use TensorFlow models. Metal under the hood.
* [Caffe2 ★6273](https://github.com/caffe2/caffe2) - Lightweight, modular, and scalable deep learning framework.
* [CoreML-samples ★16](https://github.com/ytakzk/CoreML-samples) - Sample code for Core ML using ResNet50 provided by Apple and a custom model generated by coremltools. :large_orange_diamond:
* [Revolver ★12](https://github.com/petrmanek/Revolver) - A framework for building fast genetic algorithms in Swift. Comes with modular architecture, pre-implemented operators and loads of examples. :large_orange_diamond:
* [CoreML-Models ★1841](https://github.com/likedan/Awesome-CoreML-Models) - A collection of unique Core ML Models.
* [Serrano ★26](https://github.com/pcpLiu/Serrano) - A deep learning library for iOS and macOS. :large_orange_diamond:

## Maps
* [Route-me ★1304 ⏳5Y](https://github.com/route-me/route-me) - Open source map library for iOS.
* [NAMapKit ★254 ⏳1Y](https://github.com/neilang/NAMapKit) - Allows you to use custom maps in iPhone applications and attempts to mimics some of the behaviour of the MapKit framework.
* [Mapbox GL ★2245](https://github.com/mapbox/mapbox-gl-native) - An OpenGL renderer for Mapbox Vector Tiles with SDK bindings for iOS.
* [CMMapLauncher ★192 ⏳1Y](https://github.com/citymapper/CMMapLauncher) - iOS library that makes it quick and easy to show directions in various mapping applications.
* [GEOSwift ★854](https://github.com/GEOSwift/GEOSwift) - The Swift Geographic Engine. :large_orange_diamond:
* [PXGoogleDirections ★195](https://github.com/poulpix/PXGoogleDirections) - Google Directions API helper for iOS, written in Swift :large_orange_diamond:
* [Cluster ★752](https://github.com/efremidze/Cluster) - Easy Map Annotation Clustering. :large_orange_diamond:
* [JDSwiftHeatMap ★43](https://github.com/jamesdouble/JDSwiftHeatMap) - JDSwiftMap is an IOS Native MapKit Library. You can easily make a highly customized HeatMap. :large_orange_diamond:
* [ClusterKit ★223](https://github.com/hulab/ClusterKit) - An iOS map clustering framework targeting MapKit, Google Maps and Mapbox.

## Math
* [Euler ★861](https://github.com/mattt/Euler) - Swift Custom Operators for Mathematical Notation :large_orange_diamond:
* [SwiftMath ★142](https://github.com/madbat/SwiftMath) - :triangular_ruler: A math framework for Swift. Includes: vectors, matrices, complex numbers, quaternions and polynomials. :large_orange_diamond:
* [Arithmosophi ★54](https://github.com/phimage/Arithmosophi) - A set of protocols for Arithmetic and Logical operations :large_orange_diamond:
* [Surge ★3826](https://github.com/mattt/Surge) - A Swift library that uses the Accelerate framework to provide high-performance functions for matrix math, digital signal processing, and image manipulation. :large_orange_diamond:
* [Upsurge ★121](https://github.com/aleph7/Upsurge) - Swift math :large_orange_diamond:
* [Swift-MathEagle ★30](https://github.com/rugheid/Swift-MathEagle) - A general math framework to make using math easy. Currently supports function solving and optimisation, matrix and vector algebra, complex numbers, big int and big frac and general handy extensions and functions. :large_orange_diamond:
* [iosMath ★674](https://github.com/kostub/iosMath) - A library for displaying beautifully rendered math equations. Enables typesetting LaTeX math formulae in iOS.
* [swift-pons ★210 ⏳1Y](https://github.com/dankogai/swift2-pons) - Protocol-Oriented Number System in Pure Swift :large_orange_diamond:
* [BigInt ★326](https://github.com/attaswift/BigInt) - Arbitrary-precision arithmetic in pure Swift :large_orange_diamond:
* [SigmaSwiftStatistics ★480](https://github.com/evgenyneu/SigmaSwiftStatistics) - A collection of functions for statistical calculation. :large_orange_diamond:
* [VectorMath ★157](https://github.com/nicklockwood/VectorMath) - A Swift library for Mac and iOS that implements common 2D and 3D vector and matrix functions, useful for games or vector-based graphics :large_orange_diamond:
* [Expression ★313](https://github.com/nicklockwood/Expression) - A Mac and iOS library for evaluating numeric expressions at runtime :large_orange_diamond:
* [Metron ★922](https://github.com/toineheuvelmans/Metron) - Metron is a comprehensive collection of geometric functions and types that extend the 2D geometric primitives provided by CoreGraphics. :large_orange_diamond:
* [NumericAnnex ★27](https://github.com/xwu/NumericAnnex) - NumericAnnex supplements the numeric facilities provided in the Swift standard library with generic integer algorithms, complex numbers, rational numbers, and pseudorandom number generators (written in, and for, Swift 4) :large_orange_diamond:

## Media
#### Audio
* [AudioBus](https://developer.audiob.us/) - Add Next Generation Live App-to-App Audio Routing.
* [AudioKit ★4314](https://github.com/audiokit/AudioKit) - A powerful toolkit for synthesizing, processing, and analyzing sounds. :large_orange_diamond:
* [EZAudio ★4133](https://github.com/syedhali/EZAudio) - An iOS/macOS audio visualization framework built upon Core Audio useful for anyone doing real-time, low-latency audio processing and visualizations.
* [novocaine ★2085 ⏳1Y](https://github.com/alexbw/novocaine) - Painless high-performance audio on iOS and macOS.
* [QHSpeechSynthesizerQueue ★24 ⏳1Y](https://github.com/quentinhayot/QHSpeechSynthesizerQueue) - Queue management system for AVSpeechSynthesizer (iOS Text to Speech).
* [Cephalopod ★79](https://github.com/evgenyneu/Cephalopod) - A sound fader for AVAudioPlayer written in Swift. :large_orange_diamond:
* [Chirp ★304](https://github.com/trifl/Chirp) - The easiest way to prepare, play, and remove sounds in your Swift app! :large_orange_diamond:
* [Beethoven ★292](https://github.com/vadymmarkov/Beethoven) - An audio processing Swift library for pitch detection of musical signals. :large_orange_diamond:
* [AudioPlayerSwift]( https://github.com/tbaranes/AudioPlayerSwift) - AudioPlayer is a simple class for playing audio in iOS, macOS and tvOS apps. :large_orange_diamond:
* [AudioPlayer ★307](https://github.com/delannoyk/AudioPlayer) - AudioPlayer is syntax and feature sugar over AVPlayer. It plays your audio files (local & remote). :large_orange_diamond:
* [TuningFork ★348](https://github.com/comyar/TuningFork) - :musical_keyboard: Simple Tuner for iOS :large_orange_diamond:
* [MusicKit ★457](https://github.com/benzguo/MusicKit) - A framework for composing and transforming music in Swift :large_orange_diamond:
* [SubtleVolume ★594](https://github.com/andreamazz/SubtleVolume) - Replace the system volume popup with a more subtle indicator. :large_orange_diamond:
* [NVDSP ★329](https://github.com/bartolsthoorn/NVDSP) - iOS/macOS DSP for audio (with Novocaine)
* [SRGMediaPlayer-iOS ★67](https://github.com/SRGSSR/SRGMediaPlayer-iOS) - The SRG Media Player library for iOS provides a simple way to add a universal audio / video player to any iOS application.
* [IQAudioRecorderController ★429](https://github.com/hackiftekhar/IQAudioRecorderController) - A drop-in universal library allows to record audio within the app with a nice User Interface.
* [TheAmazingAudioEngine2 ★348](https://github.com/TheAmazingAudioEngine/TheAmazingAudioEngine2) - The Amazing Audio Engine is a sophisticated framework for iOS audio applications, built so you don't have to.
* [InteractivePlayerView ★229](https://github.com/AhmettKeskin/InteractivePlayerView) - Custom iOS music player view :large_orange_diamond:
* [ESTMusicIndicator ★350](https://github.com/Aufree/ESTMusicIndicator) - Cool Animated music indicator view written in Swift :large_orange_diamond:
* [QuietModemKit ★308](https://github.com/quiet/QuietModemKit) - iOS framework for the Quiet Modem (data over sound)
* [SwiftySound ★519](https://github.com/adamcichy/SwiftySound) - Super simple library that lets you play sounds with a single line of code (and much more). Written in Swift 3, supports iOS, macOS and tvOS. CocoaPods and Carthage compatible. :large_orange_diamond:
* [BPMAnalyser ★12](https://github.com/Luccifer/BPM-Analyser) - Fast and simple instrument to get the BPM rate from your audio-files. :large_orange_diamond:
* [PandoraPlayer ★577](https://github.com/AppliKeySolutions/PandoraPlayer) - A lightweight music player for iOS, based on AudioKit and completely written in Swift :large_orange_diamond:
* [BPMAnalyser ★6](https://github.com/Luccifer/SonogramView) - Fast and simple instrument to get the BPM rate from your audio-files. :large_orange_diamond:

#### GIF
* [YLGIFImage ★1685 ⏳1Y](https://github.com/liyong03/YLGIFImage) - Async GIF image decoder and Image viewer supporting play GIF images. It just use very less memory.
* [FLAnimatedImage ★6192](https://github.com/Flipboard/FLAnimatedImage) - Performant animated GIF engine for iOS
* [gifu ★1861](https://github.com/kaishin/gifu) - Highly performant animated GIF support for iOS in Swift :large_orange_diamond:
* [AnimatedGIFImageSerialization ★1030](https://github.com/mattt/AnimatedGIFImageSerialization) - Complete Animated GIF Support for iOS, with Functions, NSJSONSerialization-style Class, and (Optional) UIImage Swizzling
* [XAnimatedImage ★575 ⏳1Y](https://github.com/khaledmtaha/XAnimatedImage) - XAnimatedImage is a performant animated GIF engine for iOS written in Swift based on FLAnimatedImage :large_orange_diamond:
* [SwiftGif ★729](https://github.com/bahlo/SwiftGif) - :sparkles: A small UIImage extension with gif support :large_orange_diamond:
* [APNGKit ★1288](https://github.com/onevcat/APNGKit) - High performance and delightful way to play with APNG format in iOS. :large_orange_diamond:
* [YYImage ★1046](https://github.com/ibireme/YYImage) - Image framework for iOS to display/encode/decode animated WebP, APNG, GIF, and more.
* [AImage ★908](https://github.com/wangjwchn/AImage) - A animated GIF&APNG engine for iOS in Swift with low memory & cpu usage.Optimized for Multi-Image case.:large_orange_diamond:
* [NSGIF2 ★56](https://github.com/metasmile/NSGIF2) - Simplify creation of a GIF from the provided video file url.
* [SwiftyGif ★705](https://github.com/kirualex/SwiftyGif) - High performance GIF engine :large_orange_diamond:

#### Image
* [GPU Image ★16596](https://github.com/BradLarson/GPUImage) - An open source iOS framework for GPU-based image and video processing.
* [UIImage DSP ★376 ⏳4Y](https://github.com/gdawg/uiimage-dsp) - iOS UIImage processing functions using the vDSP/Accelerate framework for speed.
* [AsyncImageView ★944](https://github.com/nicklockwood/AsyncImageView) - Simple extension of UIImageView for loading and displaying images asynchronously without lock up the UI.
* [SDWebImage ★18862](https://github.com/rs/SDWebImage) - Asynchronous image downloader with cache support with an UIImageView category.
* [DFImageManager ★1217 ⏳1Y](https://github.com/kean/DFImageManager) - Modern framework for fetching images from various sources. Zero config yet immense customization and extensibility. Uses NSURLSession.
* [MapleBacon ★194](https://github.com/JanGorman/MapleBacon) - An image download and caching library for iOS written in Swift. :large_orange_diamond:
* [NYTPhotoViewer ★2231](https://github.com/NYTimes/NYTPhotoViewer) - Slideshow and image viewer.
* [IDMPhotoBrowser ★2466](https://github.com/thiagoperes/IDMPhotoBrowser) - Photo Browser / Viewer.
* [JTSImageViewController ★2268](https://github.com/jaredsinclair/JTSImageViewController) - Interactive iOS image viewer.
* [Concorde ★1282 ⏳1Y](https://github.com/contentful-labs/Concorde) - Download and decode progressive JPEGs.
* [TOCropViewController ★1815](https://github.com/TimOliver/TOCropViewController) - A view controller that allows users to crop UIImage objects.
* [YXTMotionView ★79 ⏳2Y](https://github.com/hanton/YXTMotionView) - A custom image view that implements device motion scrolling.
* [PINRemoteImage ★3181](https://github.com/pinterest/PINRemoteImage) - A thread safe, performant, feature rich image fetcher.
* [SABlurImageView ★476](https://github.com/marty-suzuki/SABlurImageView) - Easily Adding Animated Blur/Unblur Effects To An Image. :large_orange_diamond:
* [FastImageCache ★7606](https://github.com/path/FastImageCache) - iOS library for quickly displaying images while scrolling.
* [BKAsciiImage ★405 ⏳2Y](https://github.com/bkoc/BKAsciiImage) - Convert UIImage to ASCII art
* [AlamofireImage ★2718](https://github.com/Alamofire/AlamofireImage) - An image component library for Alamofire. :large_orange_diamond:
* [Nuke ★2406](https://github.com/kean/Nuke) - Image loading, processing, caching and preheating :large_orange_diamond:
* [FlagKit ★1932](https://github.com/madebybowtie/FlagKit) - Beautiful flag icons for usage in apps and on the web. :large_orange_diamond:
* [YYWebImage ★2943](https://github.com/ibireme/YYWebImage) - Asynchronous image loading framework (supports WebP, APNG, GIF).
* [RSKImageCropper ★1882](https://github.com/ruslanskorb/RSKImageCropper) - An image cropper for iOS like in the Contacts app with support for landscape orientation.
* [Silo ★12 ⏳1Y](https://github.com/josejuanqm/Silo) - Image loading framework with loaders. :large_orange_diamond:
* [Ody ★43](https://github.com/josejuanqm/Ody) - Ody is an easy to use random image generator built with Swift, Perfect for placeholders. :large_orange_diamond:
* [Banana ★16 ⏳1Y](https://github.com/gauravkatoch007/banana) - Image slider with very simple interface. :large_orange_diamond:
* [JDSwiftAvatarProgress ★82 ⏳1Y](https://github.com/JellyDevelopment/JDSwiftAvatarProgress) - Easy customizable avatar image asynchronously with progress bar animated :large_orange_diamond:
* [Kingfisher ★10207](https://github.com/onevcat/Kingfisher) - A lightweight and pure Swift implemented library for downloading and caching image from the web. :large_orange_diamond:
* [EBPhotoPages ★1614](https://github.com/EddyBorja/EBPhotoPages) - A photo gallery for iOS with a modern feature set. Similar features as the Facebook photo browser.
* [UIImageView-BetterFace-Swift ★442](https://github.com/croath/UIImageView-BetterFace-Swift) - The Swift version of https://github.com/croath/UIImageView-BetterFace :large_orange_diamond:
* [KFSwiftImageLoader ★340 ⏳1Y](https://github.com/kiavashfaisali/KFSwiftImageLoader) - An extremely high-performance, lightweight, and energy-efficient pure Swift async web image loader with memory and disk caching for iOS and  Watch. :large_orange_diamond:
* [Toucan ★2059](https://github.com/gavinbunney/Toucan) - Fabulous Image Processing in Swift :large_orange_diamond:
* [ImageLoaderSwift ★262](https://github.com/hirohisa/ImageLoaderSwift) - A lightweight and fast image loader for iOS written in Swift. :large_orange_diamond:
* [ImageScout ★849](https://github.com/kaishin/ImageScout) - A Swift implementation of fastimage. Supports PNG, GIF, and JPEG. :large_orange_diamond:
* [JLStickerTextView ★351](https://github.com/luiyezheng/JLStickerTextView) - A UIImageView allow you to add multiple Label (multiple line text support) on it, you can edit, rotate, resize the Label as you want with one finger ,then render the text on Image. :large_orange_diamond:
* [Agrume ★220](https://github.com/JanGorman/Agrume) - A lemony fresh iOS image viewer written in Swift. :large_orange_diamond:
* [PASImageView ★166 ⏳1Y](https://github.com/abiaad/PASImageView) - Rounded async imageview downloader lightly cached and written in Swift :large_orange_diamond:
* [Navi ★114](https://github.com/nixzhu/Navi) - Focus on avatar caching. :large_orange_diamond:
* [SwiftPhotoGallery ★83](https://github.com/Inspirato/SwiftPhotoGallery) - Simple, fullscreen image gallery with tap, swipe, and pinch gestures. :large_orange_diamond:
* [MetalAcc ★197 ⏳1Y](https://github.com/wangjwchn/MetalAcc) - GPU-based Media processing library using Metal written in Swift.:large_orange_diamond:
* [MWPhotoBrowser ★7814](https://github.com/mwaterfall/MWPhotoBrowser) - A simple iOS photo and video browser with grid view, captions and selections.
* [UIImageColors ★1712](https://github.com/jathu/UIImageColors) - iTunes style color fetcher for UIImage. :large_orange_diamond:[e]
* [CDFlipView ★94](https://github.com/jibeex/CDFlipView) - A view that takes a set of images, make transition from one to another by using flipping effects.
* [GPUImage2 ★3404](https://github.com/BradLarson/GPUImage2) - GPUImage 2 is a BSD-licensed Swift framework for GPU-accelerated video and image processing. :large_orange_diamond:
* [TGLParallaxCarousel ★398](https://github.com/taglia3/TGLParallaxCarousel) - A lightweight 3D Linear Carousel with parallax effect :large_orange_diamond:
* [ImageButter ★382 ⏳1Y](https://github.com/dollarshaveclub/ImageButter) - Makes dealing with images buttery smooth
* [SKPhotoBrowser ★1373](https://github.com/suzuki-0000/SKPhotoBrowser) - Simple PhotoBrowser/Viewer inspired by Facebook, Twitter photo browsers written by swift :large_orange_diamond:
* [YUCIHighPassSkinSmoothing ★760 ⏳1Y](https://github.com/YuAo/YUCIHighPassSkinSmoothing) - An implementation of High Pass Skin Smoothing using Apple's Core Image Framework
* [CLImageViewPopup ★21 ⏳1Y](https://github.com/vinbhai4u/CLImageViewPopup) - A simple Image full screen pop up :large_orange_diamond:
* [APKenBurnsView ★50 ⏳1Y](https://github.com/Alterplay/APKenBurnsView) - Ken Burns effect with face recognition! :large_orange_diamond:
* [Moa ★265](https://github.com/evgenyneu/moa) - An image download extension of the image view for iOS, tvOS and macOS. :large_orange_diamond:[e]
* [JMCMarchingAnts ★125 ⏳1Y](https://github.com/izotx/JMCMarchingAnts) - Library that lets you add marching ants (animated) selection to the edges of the images. :large_orange_diamond:
* [ImageViewer ★1572](https://github.com/MailOnline/ImageViewer) - An image viewer à la Twitter :large_orange_diamond:
* [FaceAware ★2141](https://github.com/BeauNouvelle/FaceAware) - An extension that gives UIImageView the ability to focus on faces within an image when using AspectFill. :large_orange_diamond:
* [SwiftyAvatar ★171](https://github.com/dkalaitzidis/SwiftyAvatar) - A UiimageView class for creating circular avatar images, IBDesignable to make all changes via storyboard
* [ShinpuruImage ★63 ⏳1Y](https://github.com/FlexMonkey/ShinpuruImage) - Syntactic Sugar for Accelerate/vImage and Core Image Filters :large_orange_diamond:
* [ImagePickerSheetController ★1362](https://github.com/lbrndnr/ImagePickerSheetController) - ImagePickerSheetController is like the custom photo action sheet in iMessage just without the glitches. :large_orange_diamond:
* [ComplimentaryGradientView ★538](https://github.com/gkye/ComplimentaryGradientView) - Create complementary gradients generated from dominant and prominent colors in supplied image. Inspired by Grade.js. :large_orange_diamond:
* [ImageSlideshow ★697](https://github.com/zvonicek/ImageSlideshow) - Swift image slideshow with circular scrolling, timer and full screen viewer. :large_orange_diamond:
* [Imaginary ★343](https://github.com/hyperoslo/Imaginary) - 🦄 Remote images, as easy as one, two, three. :large_orange_diamond:
* [PPAssetsActionController ★51](https://github.com/pantuspavel/PPAssetsActionController) - Highly customizable Action Sheet Controller with Assets Preview. :large_orange_diamond:
* [Vulcan ★275](https://github.com/jinSasaki/Vulcan) - Multi image downloader with priority in Swift. :large_orange_diamond:
* [FacebookImagePicker ★93](https://github.com/floriangbh/FacebookImagePicker) - Facebook album photo picker written in Swift. :large_orange_diamond:
* [Lightbox ★207](https://github.com/hyperoslo/Lightbox) - A convenient and easy to use image viewer for your iOS app. :large_orange_diamond:
* [AvatarImageView ★208](https://github.com/ayushn21/AvatarImageView) - AvatarImageView is a UIImageView subclass designed to show a user's profile picture, falling back to their initials when a picture is unavailable. :large_orange_diamond:
* [Ebblink ★3](https://github.com/ebbapp/ebblinkSDK) - An iOS SDK for sharing photos that automatically expire and can be deleted at any time.
* [Sharaku ★1273](https://github.com/makomori/Sharaku) - Instagram-like image filter ViewController. :large_orange_diamond:
* [CTPanoramaView ★754](https://github.com/scihant/CTPanoramaView) - Displays spherical or cylindrical panoramas or 360-photos with touch or motion based control options. :large_orange_diamond:
* [Twitter Image Pipline ★1419](https://github.com/twitter/ios-twitter-image-pipeline) - streamlined framework for fetching and storing images in an application.
* [TinyCrayon ★1458](https://github.com/TinyCrayon/TinyCrayon-iOS-SDK) - A smart and easy-to-use image masking and cutout SDK for mobile apps. :large_orange_diamond:
* [FlexibleImage ★604](https://github.com/kawoou/FlexibleImage) - A simple way to play with image! :large_orange_diamond:
* [TLPhotoPicker ★1076](https://github.com/tilltue/TLPhotoPicker) - Multiple phassets picker for iOS lib. like a facebook. :large_orange_diamond:
* [YapImageManager ★50](https://github.com/yapstudios/YapImageManager) - A high-performance image downloader written in Swift, powered by YapDatabase. :large_orange_diamond:
* [PhotoEditorSDK](https://www.photoeditorsdk.com) - A fully customizable photo editor for your app. :large_orange_diamond:
* [SimpleImageViewer ★198](https://github.com/aFrogleap/SimpleImageViewer) - A snappy image viewer with zoom and interactive dismissal transition. :large_orange_diamond:
* [AZImagePreview ★12](https://github.com/Minitour/AZImagePreview) - A framework that makes image viewing easy. :large_orange_diamond:
* [FaceCropper ★391](https://github.com/KimDarren/FaceCropper) - Crop faces, inside of your image, with iOS 11 Vision api :large_orange_diamond:
* [Paparazzo ★502](https://github.com/avito-tech/Paparazzo) - Custom iOS camera and photo picker with editing capabilities :large_orange_diamond:
* [ZImageCropper ★26](https://github.com/ZaidPathan/ZImageCropper) - A Swift  project to crop image in any shape. :large_orange_diamond:
* [InitialsImageView ★86](https://github.com/bachonk/InitialsImageView) - An UIImageView extension that generates letter initials as a placeholder for user profile images, with a randomized background color. :large_orange_diamond:
* [DTPhotoViewerController ★68](https://github.com/tungvoduc/DTPhotoViewerController) - A fully customizable photo viewer ViewController, inspired by Facebook photo viewer. :large_orange_diamond:
* [LetterAvatarKit ★48](https://github.com/vpeschenkov/LetterAvatarKit) - A UIImage extension that generates letter-based avatars written in Swift. :large_orange_diamond:
* [AXPhotoViewer ★248](https://github.com/alexhillc/AXPhotoViewer) - An iPhone/iPad photo gallery viewer, useful for viewing a large (or small!) number of photos :large_orange_diamond:
* [TJProfileImage ★27](https://github.com/tejas-ardeshna/TJProfileImage) - Live rendering of componet’s properties in Interface Builder. :large_orange_diamond:
* [Viewer ★292](https://github.com/bakkenbaeck/Viewer) - Image viewer (or Lightbox) with support for local and remote videos and images :large_orange_diamond:
* [OverlayComposite ★6](https://github.com/aaronjsutton/OverlayComposite) - An asynchronous, multithreaded, image compositing framework written in Swift. :large_orange_diamond:

#### Media Processing
* [SwiftOCR ★2869](https://github.com/garnele007/SwiftOCR) - Fast and simple OCR library written in Swift :large_orange_diamond:
* [QR Code Scanner](https://www.appcoda.com/qr-code-ios-programming-tutorial/) - QR Code implementation.
* [QRCode ★479](https://github.com/aschuch/QRCode) - A QRCode generator written in Swift. :large_orange_diamond:
* [EFQRCode ★2069](https://github.com/EyreFree/EFQRCode) - A better way to operate two-dimensional code in Swift. :large_orange_diamond:

#### PDF
* [Reader ★3931](https://github.com/vfr/Reader) - PDF Reader Core for iOS.
* [UIView 2 PDF ★27 ⏳2Y](https://github.com/RobertAPhillips/UIView_2_PDF) - PDF generator using UIViews or UIViews with an associated XIB
* [FolioReaderKit ★1492](https://github.com/FolioReader/FolioReaderKit) - A Swift ePub reader and parser framework for iOS. :large_orange_diamond:
* [PDFGenerator ★286](https://github.com/sgr-ksmt/PDFGenerator) - A simple Generator of PDF in Swift. Generate PDF from view(s) or image(s). :large_orange_diamond:
* [SimplePDF ★96](https://github.com/nRewik/SimplePDF) - Create a simple PDF effortlessly. :large_orange_diamond:
* [SwiftPDFGenerator ★12 ⏳1Y](https://github.com/kayoslab/SwiftPDFGenerator) - PDF generator using UIViews; Swift Version of 'UIView 2 PDF'. :large_orange_diamond:
* [PSPDFKit](https://pspdfkit.com/) - Render PDF, add/edit annotations, fill forms, add/edit pages, view/create digital signatures.
* [TPPDF ★152](https://github.com/Techprimate/TPPDF) - Generate PDF using commands and automatic layout. :large_orange_diamond:

#### Streaming
* [HaishinKit.swift ★825](https://github.com/shogo4405/HaishinKit.swift) - Camera and Microphone streaming library via RTMP, HLS for iOS, macOS. :large_orange_diamond:
* [StreamingKit ★1669](https://github.com/tumtumtum/StreamingKit) - A fast and extensible gapless AudioPlayer/AudioStreamer for macOS and iOS.
* [Jukebox ★414](https://github.com/teodorpatras/Jukebox) - Player for streaming local and remote audio files. Written in Swift. :large_orange_diamond:
* [LFLiveKit ★2772](https://github.com/LaiFengiOS/LFLiveKit) - H264 and AAC Hard coding，support GPUImage Beauty， rtmp transmission，weak network lost frame，Dynamic switching rate
* [Airstream ★325 ⏳1Y](https://github.com/qasim/Airstream) - A framework for streaming audio between Apple devices using AirPlay.
* [OTAcceleratorCore ★18](https://github.com/opentok/accelerator-core-ios) - A painless way to integrate audio/video(screen sharing) to any iOS applications via Tokbox.

#### Video
* [VIMVideoPlayer ★267](https://github.com/vimeo/VIMVideoPlayer) - A simple wrapper around the AVPlayer and AVPlayerLayer classes.
* [MobilePlayer ★2272](https://github.com/mobileplayer/mobileplayer-ios) - A powerful and completely customizable media player for iOS.
* [XCDYouTubeKit ★2217](https://github.com/0xced/XCDYouTubeKit) - YouTube video player for iOS, tvOS and macOS
* [AVAnimator](http://www.modejong.com/AVAnimator/) - An open source iOS native library that makes it easy to implement non-trivial video/audio enabled apps.
* [Periscope VideoViewController ★471 ⏳1Y](https://github.com/gontovnik/Periscope-VideoViewController) - Video view controller with Periscope fast rewind control :large_orange_diamond:
* [Pip ★182](https://github.com/immrss/Pip) - A video player that support both local and network resource.
* [MHVideoPhotoGallery ★1940](https://github.com/mariohahn/MHVideoPhotoGallery) - A Photo and Video Gallery
* [PlayerView ★94 ⏳1Y](https://github.com/davidlondono/PlayerView) - Player View is a delegated view using AVPlayer of Swift :large_orange_diamond:
* [SRGMediaPlayer-iOS ★67](https://github.com/SRGSSR/SRGMediaPlayer-iOS) - The SRG Media Player library for iOS provides a simple way to add a universal audio / video player to any iOS application.
* [AVPlayerViewController-Subtitles ★84](https://github.com/mhergon/AVPlayerViewController-Subtitles) - AVPlayerViewController-Subtitles is a library to display subtitles on iOS. It's built as a Swift extension and it's very easy to integrate. :large_orange_diamond:[e]
* [MPMoviePlayerController-Subtitles ★170](https://github.com/mhergon/MPMoviePlayerController-Subtitles) - MPMoviePlayerController-Subtitles is a library to display subtitles on iOS. It's built as a Swift extension and it's very easy to integrate. :large_orange_diamond:[e]
* [ZFPlayer ★3711](https://github.com/renzifeng/ZFPlayer) - Based on AVPlayer, support for the horizontal screen, vertical screen (full screen playback can also lock the screen direction), the upper and lower slide to adjust the volume, the screen brightness, or so slide to adjust the playback progress.
* [Player ★950](https://github.com/piemonte/Player) - ▶️ video player in Swift, simple way to play and stream media in your iOS or tvOS app :large_orange_diamond:
* [BMPlayer ★797](https://github.com/BrikerMan/BMPlayer) - video player in swift3 and swift2 for iOS, based on AVPlayer, support the horizontal, vertical screen. support adjust volume, brigtness and seek by slide. :large_orange_diamond:
* [VideoPager ★32 ⏳1Y](https://github.com/entotsu/VideoPager) - Paging Video UI, and some control components is available. :large_orange_diamond:
* [ios-360-videos ★188](https://github.com/NYTimes/ios-360-videos) - NYT360Video plays 360-degree video streamed from an AVPlayer.
* [swift-360-videos ★52](https://github.com/team-pie/DDDKit) - Pure swift (no SceneKit) 3D library with focus on video and 360.
* [ABMediaView ★33](https://github.com/andrewboryk/ABMediaView) - UIImageView subclass for drop-in image, video, GIF, and audio display, with functionality for fullscreen and minimization to the bottom-right corner.
* [PryntTrimmerView ★103](https://github.com/prynt/PryntTrimmerView) - A set of UI elements to trim, crop and select frames inside a video. :large_orange_diamond:
* [VGPlayer ★175](https://github.com/VeinGuo/VGPlayer) - A simple iOS video player in Swift,Support play local and network,Background playback mode. :large_orange_diamond:

## Messaging

Also see [push notifications](#push-notifications)

* [LayerKit ★138](https://github.com/layerhq/releases-ios) - iOS SDK for Layer, the easiest way to add in-app messaging (text, photos, videos, data) to any mobile or web application.
* [Twilio](https://www.twilio.com/) - Power modern communications. Build the next generation of voice and SMS applications.
* [Plivo](https://www.plivo.com/) - SMS API, Voice API, & Global Carrier Provider.
* [XMPPFramework ★5289](https://github.com/robbiehanson/XMPPFramework) - An XMPP Framework in Objective-C for Mac and iOS.
* [Chatto ★3027](https://github.com/badoo/Chatto) - A lightweight framework to build chat applications, made in Swift :large_orange_diamond:
* [JSQMessagesViewController ★10838](https://github.com/jessesquires/JSQMessagesViewController) - An elegant messages UI library for iOS.
* [Smooch](https://smooch.io) - Simple, lightweight SDKs and interfaces that enable customer messaging inside your apps and websites.
* [SlackTextViewController ★8101](https://github.com/slackhq/SlackTextViewController) - A drop-in UIViewController subclass with a growing text input view and other useful messaging features.
* [MessageKit ★1263](https://github.com/MessageKit/MessageKit) - Eventually, a Swift re-write of JSQMessagesViewController :large_orange_diamond:
* [NoChat ★493](https://github.com/little2s/NoChat) - A lightweight chat UI framework for iOS. :large_orange_diamond:
* [NMessenger ★2110](https://github.com/eBay/NMessenger) - A fast, lightweight messenger component built on AsyncDisplaykit and written in Swift :large_orange_diamond:
* [Atlas ★3708](https://github.com/layerhq/Atlas-iOS) - A library of native iOS messaging user interface components for Layer.
* [Messenger ★2879](https://github.com/relatedcode/Messenger) - This is a native iOS Messenger app, making realtime chat conversations and audio calls with full offline support.
* [OTTextChatAccelerator ★10](https://github.com/opentok/accelerator-textchat-ios) - OpenTok Text Chat Accelerator Pack enables text messages between mobile or browser-based devices.

## Networking
* [AFNetworking ★30261](https://github.com/AFNetworking/AFNetworking) - A delightful iOS and macOS networking framework.
* [RestKit ★10180](https://github.com/RestKit/RestKit) - RestKit is an Objective-C framework for iOS that aims to make interacting with RESTful web services simple, fast and fun.
* [FSNetworking ★401 ⏳2Y](https://github.com/foursquare/FSNetworking) - Foursquare iOS networking library.
* [ASIHTTPRequest ★5795](https://github.com/pokeb/asi-http-request) - Easy to use CFNetwork wrapper for HTTP requests, Objective-C, macOS and iPhone.
* [Overcoat ★1137 ⏳1Y](https://github.com/Overcoat/Overcoat) - Small but powerful library that makes creating REST clients simple and fun.
* [ROADFramework ★50 ⏳2Y](https://github.com/epam/road-ios-framework) - Attributed-oriented approach for interacting with web services. The framework has built-in json and xml serialization for requests and responses and can be easily extensible.
* [Alamofire ★25895](https://github.com/Alamofire/Alamofire) - Alamofire is an HTTP networking library written in Swift, from the creator of AFNetworking. :large_orange_diamond:
* [Transporter ★433 ⏳1Y](https://github.com/nghialv/Transporter) - A tiny library makes uploading and downloading easier. :large_orange_diamond:
* [CDZPinger ★46 ⏳3Y](https://github.com/cdzombak/CDZPinger) - Easy-to-use ICMP Ping.
* [NSRails ★527](https://github.com/dingbat/nsrails) - iOS/Mac OS framework for Rails.
* [NKMultipeer ★15 ⏳1Y](https://github.com/nathankot/NKMultipeer) - A testable abstraction over multipeer connectivity. :large_orange_diamond:
* [CocoaAsyncSocket ★9363](https://github.com/robbiehanson/CocoaAsyncSocket) - Asynchronous socket networking library for Mac and iOS.
* [Siesta](https://bustoutsolutions.github.io/siesta/) - Elegant abstraction for RESTful resources that untangles stateful messes. An alternative to callback- and delegate-based networking. :large_orange_diamond:
* [Reachability.swift ★4423](https://github.com/ashleymills/Reachability.swift) - Replacement for Apple's Reachability re-written in Swift with closures :large_orange_diamond:
* [OctopusKit ★1 ⏳1Y](https://github.com/icoco/OctopusKit) - A simplicity but graceful solution for invoke RESTful web service APIs.
* [Moya ★7471](https://github.com/Moya/Moya) - Network abstraction layer written in Swift. :large_orange_diamond:
* [TWRDownloadManager ★333 ⏳1Y](https://github.com/chasseurmic/TWRDownloadManager) - A modern download manager based on NSURLSession to deal with asynchronous downloading, management and persistence of multiple files.
* [HappyDns ★316](https://github.com/qiniu/happy-dns-objc) - A Dns library, support custom dns server, dnspod httpdns. Only support A record.
* [Bridge ★93](https://github.com/BridgeNetworking/Bridge) - A simple extensible typed networking library. Intercept and process/alter requests and responses easily. :large_orange_diamond:
* [TRON ★394](https://github.com/MLSDev/TRON) - Lightweight network abstraction layer, written on top of Alamofire :large_orange_diamond:
* [EVCloudKitDao ★513](https://github.com/evermeer/EVCloudKitDao) - Simplified access to Apple's CloudKit :large_orange_diamond:
* [EVURLCache ★251](https://github.com/evermeer/EVURLCache) - a NSURLCache subclass for handling all web requests that use NSURLRequest :large_orange_diamond:
* [ResponseDetective ★1674](https://github.com/netguru/ResponseDetective) - Sherlock Holmes of the networking layer. :large_orange_diamond:
* [Pitaya ★851](https://github.com/johnlui/Pitaya) - A Swift HTTP / HTTPS networking library just incidentally execute on machines :large_orange_diamond:
* [Just ★1058](https://github.com/JustHTTP/Just) - Swift HTTP for Humans :large_orange_diamond:
* [agent ★610 ⏳1Y](https://github.com/hallas/agent) - Minimalistic Swift HTTP request agent for iOS and macOS :large_orange_diamond:
* [Reach ★422](https://github.com/Isuru-Nanayakkara/Reach) - A simple class to check for internet connection availability in Swift. :large_orange_diamond:
* [SwiftHTTP ★1710](https://github.com/daltoniam/SwiftHTTP) - Thin wrapper around NSURLSession in swift. Simplifies HTTP requests. :large_orange_diamond:
* [Netdiag ★64](https://github.com/qiniu/iOS-netdiag) - A network diagnosis library. Support Ping/TcpPing/Rtmp/TraceRoute/DNS/external IP/external DNS.
* [AFNetworkingHelper ★18 ⏳3Y](https://github.com/betacraft/AFNetworkingHelper) - A custom wrapper over AFNetworking library that we use inside RC extensively
* [NetKit ★4](https://github.com/azizuysal/NetKit) - A Concise HTTP Framework in Swift. :large_orange_diamond:
* [RealReachability ★2434](https://github.com/dustturtle/RealReachability) - We need to observe the REAL reachability of network. That's what RealReachability do.
* [MonkeyKing ★1882](https://github.com/nixzhu/MonkeyKing) - MonkeyKing helps you post messages to Chinese Social Networks. :large_orange_diamond:
* [NetworkKit ★27 ⏳1Y](https://github.com/imex94/NetworkKit) - Lightweight Networking and Parsing framework made for iOS, Mac, WatchOS and tvOS. :large_orange_diamond:
* [APIKit ★1294](https://github.com/ishkawa/APIKit) - A networking library for building type safe web API client in Swift. :large_orange_diamond:
* [ws ☁️](https://github.com/freshOS/ws) - Elegant JSON WebService in Swift.:large_orange_diamond:
* [SPTDataLoader ★582](https://github.com/spotify/SPTDataLoader) - The HTTP library used by the Spotify iOS client.
* [SWNetworking ★21](https://github.com/skywite/SWNetworking) - Powerful high-level iOS, macOS and tvOS networking library.
* [Networking ★1066](https://github.com/3lvis/Networking) - Simple HTTP Networking in Swift a NSURLSession wrapper with image caching support :large_orange_diamond:
* [SOAPEngine ★428](https://github.com/priore/SOAPEngine) - This generic SOAP client allows you to access web services using a your iOS app, macOS app and AppleTV app.
* [Swish ★355](https://github.com/thoughtbot/Swish) - Nothing but Net(working) :large_orange_diamond:
* [Malibu ★301](https://github.com/hyperoslo/Malibu) - :surfer: Malibu is a networking library built on promises :large_orange_diamond:
* [YTKNetwork ★4820](https://github.com/yuantiku/YTKNetwork) - YTKNetwork is a high level request util based on AFNetworking.
* [UnboxedAlamofire ★56](https://github.com/serejahh/UnboxedAlamofire) - Alamofire + Unbox: the easiest way to download and decode JSON into swift objects. :large_orange_diamond:
* [MMLanScan ★221](https://github.com/mavris/MMLanScan) - An iOS LAN Network Scanner library
* [Domainer ★6 ⏳1Y](https://github.com/FelixLinBH/Domainer) - Manage multi-domain url auto mapping ip address table
* [Restofire ★147](https://github.com/Restofire/Restofire) - Restofire is a protocol oriented network abstraction layer in swift that is built on top of Alamofire to use services in a declartive way :large_orange_diamond:
* [AFNetworking+RetryPolicy ★152](https://github.com/kubatruhlar/AFNetworking-RetryPolicy) - An objective-c category that adds the ability to set the retry logic for requests made with AFNetworking.
* [SwiftyZeroMQ ★27](https://github.com/azawawi/SwiftyZeroMQ) - ZeroMQ Swift Bindings for iOS, macOS, tvOS and watchOS. :large_orange_diamond: ⌚
* [Nikka ★12](https://github.com/JustaLab/Nikka) - A super simple Networking wrapper that supports many JSON libraries, Futures and Rx :large_orange_diamond: ⌚
* [XMNetworking ★712](https://github.com/kangzubin/XMNetworking) - A lightweight but powerful network library with simplified and expressive syntax based on AFNetworking.
* [Merhaba ★33](https://github.com/abdullahselek/Merhaba) - Bonjour networking for discovery and connection between iOS, macOS and tvOS devices.
* [DBNetworkStack ★19](https://github.com/dbsystel/DBNetworkStack) - Resource-oritented networking which is typesafe, extendable, composeable and makes testing a lot easier. :large_orange_diamond:
* [EFInternetIndicator ★107](https://github.com/ezefranca/EFInternetIndicator) - A little swift Internet error status indicator using ReachabilitySwift. :large_orange_diamond:
* [AFNetworking-Synchronous ★143](https://github.com/paulmelnikow/AFNetworking-Synchronous) - Synchronous requests for AFNetworking 1.x, 2.x, and 3.x.
* [QwikHttp ★1](https://github.com/logansease/QwikHttp) - a robust, yet lightweight and simple to use HTTP networking library designed for RESTful APIs. 🔶
* [NetClient ★63](https://github.com/intelygenz/NetClient-iOS) - Versatile HTTP networking library written in Swift 3. :large_orange_diamond:
* [WANetworkRouting ★10](https://github.com/Wasappli/WANetworkRouting) - An iOS library to route API paths to objects on client side with request, mapping, routing and auth layers
* [Reactor ★179 ⏳1Y](https://github.com/MailOnline/Reactor) - Powering your RAC architecture :large_orange_diamond:
* [SWNetworking ★4](https://github.com/isamankumara/skywite) - Powerful high-level iOS, macOS and tvOS networking library. from the creator of SWNetworking 🔶
* [Digger ★364](https://github.com/cornerAnt/Digger) - Digger is a lightweight download framework that requires only one line of code to complete the file download task
. :large_orange_diamond:
* [Ciao ★18](https://github.com/AlTavares/Ciao) - Publish and discover services using mDNS(Bonjour, Zeroconf). :large_orange_diamond:
* [PerfectAPIClient ★15](https://github.com/SvenTiigi/PerfectAPIClient) - An API Client based on a network abstraction layer for the Perfect Server-Side Swift Framework 🔶

#### Email

* [Mail Core 2 ★1661](https://github.com/MailCore/mailcore2) - MailCore 2 provide a simple and asynchronous API to work with e-mail protocols IMAP, POP and SMTP.
* [Postal ★441](https://github.com/snipsco/Postal) - A swift framework providing simple access to common email providers. :large_orange_diamond:

#### Representations

 * [apollo-ios ★859](https://github.com/apollographql/apollo-ios) - A GraphQL client for iOS, written in Swift :large_orange_diamond:
 * [JSONRPCKit ★87](https://github.com/bricklife/JSONRPCKit) - A JSON-RPC 2.0 library purely written in Swift :large_orange_diamond:
 * [protobuf-swift ★807](https://github.com/alexeyxo/protobuf-swift) - Google ProtocolBuffers for Apple Swift :large_orange_diamond:

## Notifications

#### Push Notifications
* [Orbiter ★698 ⏳1Y](https://github.com/mattt/Orbiter) - Push Notification Registration for iOS.
* [PEM](https://github.com/fastlane/fastlane/tree/master/pem) - Automatically generate and renew your push notification profiles.
* [Knuff ★3922](https://github.com/KnuffApp/Knuff) - The debug application for Apple Push Notification Service (APNS).
* [FBNotifications ★460](https://github.com/facebook/FBNotifications) - Facebook Analytics In-App Notifications Framework.
* [NWPusher ★3564](https://github.com/noodlewerk/NWPusher) - macOS and iOS application and framework to play with the Apple Push Notification service (APNs)
* [SimulatorRemoteNotifications ★1226](https://github.com/acoomans/SimulatorRemoteNotifications) - Library to send mock remote notifications to the iOS simulator

##### Push Notification Providers

Most of these are paid services, some have free tiers.

* [Urban Airship](https://www.urbanairship.com/products/mobile-app-engagement )
* [Growth Push](https://growthpush.com) - Popular in Japan.
* [Braze](https://www.braze.com/)
* [Batch](https://batch.com)
* [Boxcar](https://boxcar.io)
* [Carnival](http://www.carnival.io)
* [Catapush](http://www.catapush.com/)
* [Netmera](https://www.netmera.com/)
* [OneSignal](https://onesignal.com) - Free.
* [PushBots](https://pushbots.com/)
* [Pushwoosh](https://www.pushwoosh.com)
* [Pushkin ★161](https://github.com/Nordeus/pushkin) - Free and open-source.
* [Pusher](https://pusher.com/push-notifications) - Free and unlimited.
* [Swrve](https://www.swrve.com)

#### Local Notifications
* [DLLocalNotifications ★67](https://github.com/d7laungani/DLLocalNotifications) -  Easily create Local Notifications in swift - Wrapper of UserNotifications Framework. :large_orange_diamond:

## Optimization
* [Unreachable ★87](https://github.com/nvzqz/Unreachable) - Unreachable code path optimization hint for Swift. :large_orange_diamond:

## Parsing

#### CSV
* [CSwiftV ★123](https://github.com/Daniel1of1/CSwiftV) - A csv parser written in swift conforming to rfc4180 :large_orange_diamond:

#### JSON
* [JSON-Framework ★3803](https://github.com/stig/json-framework) -  This framework implements a strict JSON parser and generator in Objective-C.
* [Mantle ★10805](https://github.com/Mantle/Mantle) - Model framework for Cocoa and Cocoa Touch.
* [Groot ★484](https://github.com/gonzalezreal/Groot) - Convert JSON dictionaries and arrays to and from Core Data managed objects.
* [PropertyMapper ★1119](https://github.com/krzysztofzablocki/PropertyMapper) - Data mapping and validation with minimal amount of code.
* [JSONModel ★6353](https://github.com/JSONModel/JSONModel) - Magical Data Modeling Framework for JSON. Create rapidly powerful, atomic and smart data model classes.
* [SwiftyJSON ★15814](https://github.com/SwiftyJSON/SwiftyJSON) - The better way to deal with JSON data in Swift. :large_orange_diamond:
* [FastEasyMapping ★523](https://github.com/Yalantis/FastEasyMapping) - Serialize & deserialize JSON fast.
* [ObjectMapper ★6509](https://github.com/Hearst-DD/ObjectMapper) - A framework written in Swift that makes it easy for you to convert your Model objects (Classes and Structs) to and from JSON. :large_orange_diamond:
* [JASON ★1003](https://github.com/delba/JASON) - JSON parsing with outstanding performances and convenient operators. :large_orange_diamond:
* [Gloss ★1583](https://github.com/hkellaway/Gloss) - A shiny JSON parsing library in Swift. :large_orange_diamond:
* [Cereal ★376](https://github.com/Weebly/Cereal) - Swift object serialization :large_orange_diamond:
* [SwiftyJSONAccelerator ★656](https://github.com/insanoid/SwiftyJSONAccelerator) - Generate Swift model files from JSON using either SwiftyJSON or ObjectMapper. Supports NSCoding and provides method for JSON string representation of the model. :large_orange_diamond:
* [JSONCodable ★612](https://github.com/matthewcheok/JSONCodable) - Hassle-free JSON encoding and decoding in Swift :large_orange_diamond:
* [Tailor ★245](https://github.com/zenangst/Tailor) - A super fast & convenient object mapper tailored for your needs. :large_orange_diamond:
* [alexander ★36](https://github.com/hodinkee/alexander) - An extremely simple JSON helper written in Swift. :large_orange_diamond:
* [Freddy ★1109](https://github.com/bignerdranch/Freddy) - A reusable framework for parsing JSON in Swift. :large_orange_diamond:
* [mapper ★1010](https://github.com/lyft/mapper) - A JSON deserialization library for Swift :large_orange_diamond:
* [AlamofireJsonToObjects ★151](https://github.com/evermeer/AlamofireJsonToObjects) - An Alamofire extension which converts JSON response data into swift objects using EVReflection :large_orange_diamond:
* [Jay ★127](https://github.com/DanToml/Jay) - Pure-Swift JSON parser & formatter. Linux & macOS ready. :large_orange_diamond:
* [YYModel ★3170](https://github.com/ibireme/YYModel) - High performance model framework for iOS/macOS.
* [Alembic ★102](https://github.com/ra1028/Alembic) - Functional JSON parsing, mapping to objects, and serialize to JSON :large_orange_diamond:
* [Wrap ★550](https://github.com/JohnSundell/Wrap) - The easy to use Swift JSON encoder :large_orange_diamond:
* [Arrow 🏹 ★255](https://github.com/freshOS/Arrow) - Elegant JSON Parsing in Swift. :large_orange_diamond:
* [Decodable ★1079](https://github.com/Anviking/Decodable) - Swift 2/3 JSON parsing done (more) right :large_orange_diamond:
* [Genome ★790](https://github.com/LoganWright/Genome) - A simple, type safe, failure driven mapping library for serializing JSON to models in Swift 3.0 (Supports Linux) :large_orange_diamond:
* [Unbox ★1754](https://github.com/JohnSundell/Unbox) - The easy to use Swift JSON decoder :large_orange_diamond:
* [JSONJoy-Swift ★348](https://github.com/daltoniam/JSONJoy-Swift) - Convert JSON to Swift objects. :large_orange_diamond:
* [LazyObject ★10](https://github.com/iwasrobbed/LazyObject) - Lazily deserialize JSON into strongly typed Swift objects :large_orange_diamond:
* [JSONExport ★2910](https://github.com/Ahmed-Ali/JSONExport) - JSONExport is a desktop application for macOS which enables you to export JSON objects as model classes with their associated constructors, utility methods, setters and getters in your favorite language. :large_orange_diamond:
* [Elevate ★611](https://github.com/Nike-Inc/Elevate) - Elevate is a JSON parsing framework that leverages Swift to make parsing simple, reliable and composable. :large_orange_diamond:
* [MJExtension ★7326](https://github.com/CoderMJLee/MJExtension) - A fast, convenient and nonintrusive conversion between JSON and model. Your model class don't need to extend another base class. You don't need to modify any model file.
* [AlamofireObjectMapper ★2026](https://github.com/tristanhimmelman/AlamofireObjectMapper) - An Alamofire extension which converts JSON response data into swift objects using ObjectMapper :large_orange_diamond:
* [GuardedSwiftyJSON ★4](https://github.com/wiggzz/GuardedSwiftyJSON) - An add-on to SwiftyJSON to make it easier to create failable initalizers for data models. :large_orange_diamond:
* [JAYSON ★224](https://github.com/muukii/JAYSON) - Strict and Scalable JSON library. :large_orange_diamond:
* [HandyJSON ★1485](https://github.com/alibaba/handyjson) - A handy swift JSON-object serialization/deserialization library for swift 2.x/3.x. :large_orange_diamond:
* [Marshal ★580](https://github.com/utahiosmac/Marshal) - Marshaling the typeless wild west of [String: Any] (Protocol based).
* [Motis ★248](https://github.com/mobilejazz/Motis) - Easy JSON to NSObject mapping using Cocoa's key value coding (KVC).
* [NSTEasyJSON ★5](https://github.com/bernikowich/NSTEasyJSON) - The easiest way to deal with JSON data in Objective-C (similar to SwiftyJSON).
* [Serpent ★272](https://github.com/nodes-ios/Serpent) - A protocol to serialize Swift structs and classes for encoding and decoding. :large_orange_diamond:
* [MagicMapper ★25 ⏳1Y](https://github.com/adrianitech/magic-mapper-swift) - :star2: Super light and easy automatic JSON to model mapper. :large_orange_diamond:
* [FlatBuffersSwift ★472](https://github.com/mzaks/FlatBuffersSwift) - This project brings FlatBuffers (an efficient cross platform serialization library) to Swift. :large_orange_diamond:
* [CodableAlamofire ★488](https://github.com/Otbivnoe/CodableAlamofire) - An extension for Alamofire that converts JSON data into Decodable objects (Swift 4). :large_orange_diamond:
* [WAMapping ★9](https://github.com/Wasappli/WAMapping) - A library to turn dictionary into object and vice versa for iOS. Designed for speed!

#### XML & HTML
* [AEXML ★705](https://github.com/tadija/AEXML) - Simple and lightweight XML parser written in Swift. :large_orange_diamond:
* [Ji ★732](https://github.com/honghaoz/Ji) - XML/HTML parser for Swift. :large_orange_diamond:
* [Ono ★2187](https://github.com/mattt/Ono) - A sensible way to deal with XML & HTML for iOS & macOS
* [AlamofireXmlToObjects ★62](https://github.com/evermeer/AlamofireXmlToObjects) - Fetch a XML feed and parse it into objects :large_orange_diamond:
* [Fuzi ★618](https://github.com/cezheng/Fuzi) - A fast & lightweight XML & HTML parser in Swift with XPath & CSS support :large_orange_diamond:
* [Kanna ★1447](https://github.com/tid-kijyun/Kanna)  - Kanna(鉋) is an XML/HTML parser for macOS/iOS. :large_orange_diamond:
* [SwiftyXMLParser ★144](https://github.com/yahoojapan/SwiftyXMLParser) - Simple XML Parser implemented in Swift :large_orange_diamond:
* [HTMLKit ★108](https://github.com/iabudiab/HTMLKit) - An Objective-C framework for your everyday HTML needs.
* [SWXMLHash ★876](https://github.com/drmohundro/SWXMLHash) - Simple XML parsing in Swift :large_orange_diamond:
* [SwiftyXML ★21](https://github.com/chenyunguiMilook/SwiftyXML) - The most swifty way to deal with XML data in swift 3 :large_orange_diamond:

#### Other Parsing
* [WKZombie ★878](https://github.com/mkoehnke/WKZombie) - WKZombie is a Swift framework for iOS/macOS to navigate within websites and collect data without the need of User Interface or API, also known as Headless browser. It can be used to run automated tests or manipulate websites using Javascript. :large_orange_diamond:
* [URLPreview ★182 ⏳1Y](https://github.com/itsmeichigo/URLPreview) - An NSURL extension for showing preview info of webpages :large_orange_diamond:
* [FeedKit ★379](https://github.com/nmdias/FeedKit) - An RSS and Atom feed parser written in Swift :large_orange_diamond:
* [Erik ★252](https://github.com/phimage/Erik) - Erik is an headless browser based on WebKit. An headless browser allow to run functional tests, to access and manipulate webpages using javascript. :large_orange_diamond:
* [URLEmbeddedView ★425](https://github.com/marty-suzuki/URLEmbeddedView) - Automatically caches the object that is confirmed the Open Graph Protocol, and displays it as URL embedded card. :large_orange_diamond:
* [SwiftyConfiguration ★105 ⏳1Y](https://github.com/ykyouhei/SwiftyConfiguration) - Modern Swift API for Plist. :large_orange_diamond:
* [JSONFeed ★28](https://github.com/totocaster/JSONFeed) - Swift parser for JSON Feed, a format similar to RSS and Atom but in JSON. :large_orange_diamond:
* [SwiftCssParser ★231](https://github.com/100mango/SwiftCssParser) - A Powerful , Extensible CSS Parser written in pure Swift. :large_orange_diamond:

## Passbook
* [passbook ★213](https://github.com/frozon/passbook) - Passbook gem let's you create pkpass for passbook iOS 6+.
* [Dubai ★316](https://github.com/nomad/dubai) - Generate and Preview Passbook Passes.
* [Passkit](https://passkit.com) - Design, Create and validate Passbook Passes.

## Payments
* [Caishen ★658](https://github.com/prolificinteractive/Caishen) - A Payment Card UI & Validator for iOS. :large_orange_diamond:
* [Stripe](https://stripe.com) - Payment integration on your app with PAY. Suitable for people with low knowledge on Backend.
* [Braintree](https://www.braintreepayments.com) - Free payment processing on your first $50k. Requires Backend.
* [Venmo ★136](https://github.com/venmo/venmo-ios-sdk) Make and accept payments in your iOS app via Venmo.
* [Moltin](https://moltin.com/ios-ecommerce-sdk/) - Add eCommerce to your app with a simple SDK, so you can create a store and sell physical products, no backend required.
* [PatronKit ★356](https://github.com/MosheBerman/PatronKit) - A framework to add patronage to your apps. :large_orange_diamond:
* [SwiftyStoreKit ★2547](https://github.com/bizz84/SwiftyStoreKit) - Lightweight In App Purchases Swift framework for iOS 8.0+ and macOS 9.0+ :large_orange_diamond:
* [InAppFramework ★37 ⏳1Y](https://github.com/sandorgyulai/InAppFramework) - In App Purchase Manager framework for iOS :large_orange_diamond:
* [SwiftInAppPurchase ★17 ⏳1Y](https://github.com/rpzzzzzz/SwiftInAppPurchase) - Simply code In App Purchases with this Swift Framework :large_orange_diamond:
* [monza ★90](https://github.com/gabrielgarza/monza) - Ruby Gem for Rails - Easy iTunes In-App Purchase Receipt validation, including auto-renewable subscriptions
* [EasyIAPs ★5 ⏳1Y](https://github.com/aaalveee/EasyIAPs) - An easy way to manage In App Purchases
* [PayPal ★886](https://github.com/paypal/PayPal-iOS-SDK) - Accept payments in your iOS app via PayPal.
* [card.io-iOS-SDK ★1911](https://github.com/card-io/card.io-iOS-SDK) - card.io provides fast, easy credit card scanning in mobile apps
* [SwiftLuhn ★103](https://github.com/MaxKramer/SwiftLuhn) - Debit/Credit card validation port of the Luhn Algorithm in Swift :large_orange_diamond:
* [ObjectiveLuhn ★119 ⏳1Y](https://github.com/MaxKramer/ObjectiveLuhn) - Luhn Credit Card Validation Algorithm
* [RMStore ★2043](https://github.com/robotmedia/RMStore) - A lightweight iOS library for In-App Purchases
* [MFCard ★274](https://github.com/mobilefirstinc/MFCard) - Easily integrate Credit Card payments in iOS App / Customisable Card UI
* [TPInAppReceipt ★33](https://github.com/tikhop/TPInAppReceipt) - Reading and Validating In App Store Receipt :large_orange_diamond:
* [iCard ★249](https://github.com/eliakorkmaz/iCard) - Bank Card Generator with Swift using SnapKit DSL :large_orange_diamond:

## Permissions
* [Proposer ★748](https://github.com/nixzhu/Proposer) - Make permission request easier (Supports Camera, Photos, Microphone, Contacts, Location). :large_orange_diamond:
* [ICanHas ★81](https://github.com/wircho/ICanHas) - Simplifies iOS user permission requests (Supports location, push notifications, camera, contacts, calendar, photos). :large_orange_diamond:
* [VWWPermissionKit ★131 ⏳2Y](https://github.com/zakkhoyt/VWWPermissionKit) - A visual permission manager for iOS.
* [ISHPermissionKit ★577](https://github.com/iosphere/ISHPermissionKit) - A unified way for iOS apps to request user permissions.
* [JLPermissions ★403 ⏳1Y](https://github.com/jlaws/JLPermissions) - An iOS pre-permissions utility that lets developers ask users on their own dialog for calendar, contacts, location, photos, reminders, twitter, push notifications and more, before making the system-based permission request.
* [ClusterPrePermissions ★1203](https://github.com/rsattar/ClusterPrePermissions) - Reusable pre-permissions utility that lets developers ask users for access in their own dialog, before making the system-based request.
* [Permission ★2274](https://github.com/delba/Permission) - A unified API to ask for permissions on iOS :large_orange_diamond:
* [STLocationRequest ★554](https://github.com/SvenTiigi/STLocationRequest) - A simple and elegant 3D-Flyover location request screen written Swift. :large_orange_diamond:
* [PAPermissions ★665](https://github.com/pascalbros/PAPermissions) - A unified API to ask for permissions on iOS :large_orange_diamond:
* [AREK ★787](https://github.com/ennioma/arek) - AREK is a clean and easy to use wrapper over any kind of iOS permission. :large_orange_diamond:
* [RequestPermission ★1623](https://github.com/IvanVorobei/RequestPermission) - simple permission request with beautiful UI :large_orange_diamond:

## Products
* [Import.io](https://www.import.io/) - Instantly Turn Web Pages into Data.
* [Tapglue](https://www.tapglue.com/) - Build social products and a activity feed with a few lines of code.
* [OpenShop.io ★293](https://github.com/openshopio/openshop.io-ios) - mobile e-commerce solution connected to Facebook Ads and Google.

## Reactive Programming
* [RxSwift ★11449](https://github.com/ReactiveX/RxSwift) - Reactive Programming in Swift :large_orange_diamond:
* [RxOptional ★7 ⏳1Y](https://github.com/thanegill/RxOptional) - RxSwift extentions for Swift optionals and "Occupiable" types :large_orange_diamond:
* [ReactiveTask ★121](https://github.com/Carthage/ReactiveTask) - Flexible, stream-based abstraction for launching processes :large_orange_diamond:
* [ReactiveCocoa ★18061](https://github.com/ReactiveCocoa/ReactiveCocoa) - Streams of values over time.
* [RxMediaPicker ★93](https://github.com/RxSwiftCommunity/RxMediaPicker) - A reactive wrapper built around UIImagePickerController. :large_orange_diamond:
* [ReactiveCoreData ★276 ⏳1Y](https://github.com/apparentsoft/ReactiveCoreData) - ReactiveCoreData (RCD) is an attempt to bring Core Data into the ReactiveCocoa (RAC) world.
* [ReSwift ★4447](https://github.com/ReSwift/ReSwift) - Unidirectional Data Flow in Swift - Inspired by Redux :large_orange_diamond:
* [ReactiveKit ★905](https://github.com/ReactiveKit/ReactiveKit) - ReactiveKit is a collection of Swift frameworks for reactive and functional reactive programming. :large_orange_diamond:
* [RxPermission ★187](https://github.com/sunshinejr/RxPermission) - RxSwift bindings for Permissions API in iOS. :large_orange_diamond:
* [RxAlamofire ★803](https://github.com/RxSwiftCommunity/RxAlamofire) - RxSwift wrapper around the elegant HTTP networking in Swift Alamofire :large_orange_diamond:
* [RxRealm ★545](https://github.com/RxSwiftCommunity/RxRealm) - Rx wrapper for Realm's collection types :large_orange_diamond:
* [RxMultipeer ★48](https://github.com/RxSwiftCommunity/RxMultipeer) - A testable RxSwift wrapper around MultipeerConnectivity :large_orange_diamond:
* [RxBluetoothKit ★645](https://github.com/Polidea/RxBluetoothKit) - iOS & macOS Bluetooth library for RxSwift :large_orange_diamond:
* [RxGesture ★471](https://github.com/RxSwiftCommunity/RxGesture) - RxSwift reactive wrapper for view gestures :large_orange_diamond:
* [NSObject-Rx ★250](https://github.com/RxSwiftCommunity/NSObject-Rx) - Handy RxSwift extensions on NSObject, including rx_disposeBag. :large_orange_diamond:
* [RxCoreData ★78](https://github.com/RxSwiftCommunity/RxCoreData) - RxSwift extensions for Core Data :large_orange_diamond:
* [RxAutomaton ★592](https://github.com/inamiy/RxAutomaton) - RxSwift + State Machine, inspired by Redux and Elm. :large_orange_diamond:
* [ReactiveArray ★54 ⏳1Y](https://github.com/Wolox/ReactiveArray) - An array class implemented in Swift that can be observed using ReactiveCocoa's Signals. :large_orange_diamond:
* [Interstellar ★970](https://github.com/JensRavens/Interstellar) - Simple and lightweight Functional Reactive Coding in Swift for the rest of us. :large_orange_diamond:
* [ReduxSwift ★32 ⏳1Y](https://github.com/lsunsi/ReduxSwift) - Predictable state container for Swift apps too. :large_orange_diamond:
* [Aftermath ★57](https://github.com/hyperoslo/Aftermath) - Stateless message-driven micro-framework in Swift. :large_orange_diamond:
* [RxKeyboard ★603](https://github.com/RxSwiftCommunity/RxKeyboard) - Reactive Keyboard in iOS. :large_orange_diamond:
* [JASONETTE-iOS ★4825](https://github.com/Jasonette/JASONETTE-iOS) - Native App over HTTP. Create your own native iOS app with nothing but JSON.
* [ReactiveSwift ★1606](https://github.com/ReactiveCocoa/ReactiveSwift) - Streams of values over time by ReactiveCocoa group
* [Listenable ★3](https://github.com/msaps/Listenable) - Swift object that provides an observable platform. :large_orange_diamond:
* [Reactor ★135](https://github.com/ReactorSwift/Reactor) - :arrows_counterclockwise: Unidirectional Data Flow using idiomatic Swift—inspired by Elm and Redux . :large_orange_diamond:
* [Snail ★66](https://github.com/UrbanCompass/Snail) - An observables framework for Swift :large_orange_diamond:
* [RxWebSocket ★33](https://github.com/fjcaetano/RxWebSocket) - Reactive extension over Starscream for websockets :large_orange_diamond:
* [ACKReactiveExtensions ★10](https://github.com/AckeeCZ/ACKReactiveExtensions) - Useful extensions for ReactiveCocoa :large_orange_diamond:
* [ReactiveLocation ★14](https://github.com/AckeeCZ/ReactiveLocation) - CoreLocation made reactive :large_orange_diamond:
* [Hanson ★465](https://github.com/blendle/Hanson) - Lightweight observations and bindings in Swift, with support for KVO and NotificationCenter. :large_orange_diamond:
* [Observable ★147](https://github.com/roberthein/Observable) - The easiest way to observe values in Swift. 🔶
* [SimpleApiClient ★62](https://github.com/jaychang0917/SimpleApiClient-ios) - A configurable api client based on Alamofire4 and RxSwift4 for iOS. 🔶
* [VueFlux ★47](https://github.com/ra1028/VueFlux) - Unidirectional Data Flow State Management Architecture for Swift - Inspired by Vuex and Flux 🔶
* [RxAnimated ★308](https://github.com/RxSwiftCommunity/RxAnimated) - Animated RxCocoa bindings

## React-Like
* [Render ★1652](https://github.com/alexdrone/Render) - Swift and UIKit a la React. :large_orange_diamond:
* [Katana ★1624](https://github.com/BendingSpoons/katana-swift) - Swift apps a la React and Redux. :large_orange_diamond:
* [TemplateKit ★126 ⏳1Y](https://github.com/mcudich/TemplateKit) - React-inspired framework for building component-based user interfaces in Swift. :large_orange_diamond:
* [Komponents 📦 ★146](https://github.com/freshOS/Komponents) - React-inspired UIKit Components. :large_orange_diamond:
* [Reactant ★308](https://github.com/Brightify/Reactant) - Reactant is a reactive architecture for iOS :large_orange_diamond:

## Reflection
* [Reflection ★366](https://github.com/Zewo/Reflection) - Reflection provides an API for advanced reflection at runtime including dynamic construction of types. :large_orange_diamond:
* [Reflect ★306](https://github.com/CharlinFeng/Reflect) - Reflection, Dict2Model, Model2Dict, Archive :large_orange_diamond:
* [EVReflection ★754](https://github.com/evermeer/EVReflection) - Reflection based JSON encoding and decoding. Including support for NSDictionary, NSCoding, Printable, Hashable and Equatable :large_orange_diamond:
* [JSONNeverDie ★474](https://github.com/johnlui/JSONNeverDie) - Auto reflection tool from JSON to Model, user friendly JSON encoder / decoder, aims to never die :large_orange_diamond:
* [SwiftKVC ★103](https://github.com/bradhilton/SwiftKVC) - Key-Value Coding (KVC) for native Swift classes and structs :large_orange_diamond:

## Regex
* [Regex ★453](https://github.com/sharplet/Regex) - A Swift µframework providing an NSRegularExpression-backed Regex type :large_orange_diamond:
* [SwiftRegex ★117](https://github.com/kasei/SwiftRegex) - Perl-like Regex =~ operator for Swift :large_orange_diamond:
* [PySwiftyRegex ★208](https://github.com/cezheng/PySwiftyRegex) - Easily deal with Regex in Swift in a Pythonic way :large_orange_diamond:
* [Regex ★210](https://github.com/crossroadlabs/Regex) - Regular expressions for swift :large_orange_diamond:
* [Regex ★63](https://github.com/brynbellomy/Regex) - Regex class for Swift. Wraps NSRegularExpression. :large_orange_diamond:

## SDK

#### Official

* [Spotify ★784](https://github.com/spotify/ios-sdk) Spotify iOS SDK.
* [SpotifyLogin ★216](https://github.com/spotify/SpotifyLogin) Spotify SDK Login in Swift. :large_orange_diamond:
* [Facebook ★5833](https://github.com/facebook/facebook-ios-sdk) Facebook iOS SDK.
* [Facebook Swift ★1231](https://github.com/facebook/facebook-sdk-swift) Integrate your iOS apps in Swift with Facebook Platform.
* [Google Analytics](https://developers.google.com/analytics/devguides/collection/ios/v3/) Google Analytics SDK for iOS
* [Paypal iOS SDK ★886](https://github.com/paypal/PayPal-iOS-SDK) The PayPal Mobile SDKs enable native apps to easily accept PayPal and credit card payments.
* [Pocket ★195](https://github.com/Pocket/Pocket-ObjC-SDK) SDK for saving stuff to Pocket.
* [Tumblr ★370](https://github.com/tumblr/TMTumblrSDK) Library for easily integrating Tumblr data into your iOS or macOS application.
* [Evernote ★216](https://github.com/evernote/evernote-cloud-sdk-ios) Evernote SDK for iOS.
* [Box ★57](https://github.com/box/box-ios-sdk) iOS + macOS SDK for the Box API.
* [OneDrive ★60](https://github.com/OneDrive/onedrive-sdk-ios) Live SDK for iOS.
* [Stripe ★896](https://github.com/stripe/stripe-ios) Stripe bindings for iOS and macOS.
* [Venmo](#payments)
* [AWS ★908](https://github.com/aws/aws-sdk-ios) Amazon Web Services Mobile SDK for iOS.
* [Zendesk ★66](https://github.com/zendesk/zendesk_sdk_ios) Zendesk Mobile SDK for iOS.
* [Adobe Creative SDK](https://creativesdk.adobe.com/) Adobe creative tools and Creative Cloud SDK.
* [Dropbox](https://www.dropbox.com/developers) SDKs for Drop-ins and Dropbox Core API.
* [Fabric by Twitter](https://docs.fabric.io/apple/fabric/overview.html) Fabric Twitter Kit for iOS.
* [Liquid Analytics ★24 ⏳1Y](https://github.com/lqd-io/liquid-sdk-ios) Identify behaviours through Analytics and react with real-time Personalization.
* [ResearchKit ★4924](https://github.com/ResearchKit/ResearchKit) ResearchKit is an open source software framework that makes it easy to create apps for medical research or for other research projects.
* [PacketZoom](https://packetzoom.com) PacketZoom SDK for iOS.
* [Primer](https://www.goprimer.com) - Easy SDK for creating personalized landing screens, signup, and login flows on a visual editor with built in a/b/n testing and analytics.
* [Azure ★52](https://github.com/Azure/azure-storage-ios) - Client library for accessing Azure Storage on an iOS device
* [1Password ★2377](https://github.com/AgileBits/onepassword-app-extension) - 1Password Extension for iOS Apps
* [CareKit ★1379](https://github.com/carekit-apple/CareKit) - CareKit is an open source software framework for creating apps that help people better understand and manage their health. By Apple :large_orange_diamond:
* [Shopify ★176](https://github.com/Shopify/mobile-buy-sdk-ios) - Shopify’s Mobile Buy SDK makes it simple to sell physical products inside your mobile app.
* [Pinterest ★99](https://github.com/pinterest/ios-pdk) - Pinterest iOS SDK
* [playkit-ios ★18](https://github.com/kaltura/playkit-ios) - PlayKit: Kaltura Player SDK for iOS.
* [algoliasearch-client-swift ★83](https://github.com/algolia/algoliasearch-client-swift) - Algolia Search API Client for Swift :large_orange_diamond:

#### Unofficial

* [STTwitter ★1017](https://github.com/nst/STTwitter) A stable, mature and comprehensive Objective-C library for Twitter REST API 1.1
* [FHSTwitterEngine ★220](https://github.com/natesymer/FHSTwitterEngine) Twitter API for Cocoa developers.
* [Giphy ★47](https://github.com/heyalexchoi/Giphy-iOS) Giphy API client for iOS in Objective-C.
* [UberKit ★96 ⏳1Y](https://github.com/sachinkesiraju/UberKit) - A simple, easy-to-use Objective-C wrapper for the Uber API.
* [InstagramKit ★905](https://github.com/shyambhat/InstagramKit) - Instagram iOS SDK.
* [DribbbleSDK ★78 ⏳1Y](https://github.com/agilie/dribbble-ios-sdk) - Dribbble iOS SDK.
* [objectiveflickr ★726 ⏳2Y](https://github.com/lukhnos/objectiveflickr) - ObjectiveFlickr, a Flickr API framework for Objective-C.
* [Easy Social ★130 ⏳1Y](https://github.com/pjebs/EasySocial) - Twitter & Facebook Integration.
* [das-quadrat ★169](https://github.com/Constantine-Fry/das-quadrat) - A Swift wrapper for Foursquare API. iOS and macOS. :large_orange_diamond:
* [SocialLib ★10 ⏳1Y](https://github.com/darkcl/SocialLib) - SocialLib handles sharing message to multiple social media.
* [PokemonKit ★72](https://github.com/ContinuousLearning/PokemonKit) - Pokeapi wrapper, written in Swift :large_orange_diamond:
* [TJDropbox ★48](https://github.com/timonus/TJDropbox) - A Dropbox v2 client library written in Objective-C
* [Lyft ★60](https://github.com/genadyo/Lyft) - Some pink mustache company forgot to build that SDK. :large_orange_diamond:
* [Github.swift ★160](https://github.com/onmyway133/github.swift) - :octocat: Unofficial GitHub API client in Swift :large_orange_diamond:
* [CloudRail SI ★200](https://github.com/CloudRail/cloudrail-si-ios-sdk) - Abstraction layer / unified API for multiple API providers. Interfaces eg for Cloud Storage (Dropbox, Google, ...), Social Networks (Facebook, Twitter, ...) and more.
* [Medium SDK - Swift ★8](https://github.com/96-problems/medium-sdk-swift) - Unofficial Medium API SDK in Swift with sample project :large_orange_diamond:
* [Swifter ★1852](https://github.com/mattdonnelly/Swifter) - :bird: A Twitter framework for iOS & macOS written in Swift :large_orange_diamond:
* [SlackKit ★608](https://github.com/SlackKit/SlackKit) - a Slack client library for iOS and macOS written in Swift :large_orange_diamond:
* [RandomUserSwift ★80](https://github.com/dingwilson/RandomUserSwift) - Swift 3 Framework to Generate Random Users - An Unofficial SDK for randomuser.me :large_orange_diamond:
* [PPEventRegistryAPI ★8 ⏳1Y](https://github.com/pantuspavel/PPEventRegistryAPI) - Swift 3 Framework for Event Registry API (eventregistry.org). :large_orange_diamond:
* [UnsplashKit ★151](https://github.com/carambalabs/UnsplashKit) - Swift client for Unsplash. :large_orange_diamond:
* [Swiftly Salesforce ★60](https://github.com/mike4aday/SwiftlySalesforce) - An easy-to-use framework for building iOS apps that integrate with Salesforce, using Swift and promises. :large_orange_diamond:
* [Spartan ★25](https://github.com/Daltron/Spartan) - An Elegant Spotify Web API Library Written in Swift for iOS and macOS. :large_orange_diamond:
* [BigBoard ★41](https://github.com/Daltron/BigBoard) - An Elegant Financial Markets Library Written in Swift that makes requests to Yahoo Finance API's under the hood. :large_orange_diamond:
* [SwiftyVK ★145](https://github.com/SwiftyVK/SwiftyVK) Library for easy interact with VK social network API written in Swift 🔶
* [ARKKit ★11](https://github.com/sleepdefic1t/ARKKit) - ARK Ecosystem Cryptocurrency API Framework for iOS & macOS, written purely in Swift 4.0. :large_orange_diamond:
* [SwiftInstagram ★351](https://github.com/AnderGoig/SwiftInstagram) - Swift Client for Instagram API. :large_orange_diamond:
* [SwiftyArk ★6](https://github.com/Awalz/SwiftyArk) - A simple, lightweight, fully-asynchronous cryptocurrency framework for the ARK Ecosystem. :large_orange_diamond:

## Security
* [cocoapods-keys ★909](https://github.com/orta/cocoapods-keys) - A key value store for storing environment and application keys.
* [simple-touch ★97](https://github.com/simple-machines/simple-touch) - Very simple swift wrapper for Biometric Authentication Services (Touch ID) on iOS.
* [SwiftPasscodeLock ★565](https://github.com/yankodimitrov/SwiftPasscodeLock) - An iOS passcode lock with TouchID authentication written in Swift. :large_orange_diamond:
* [Smile-Lock ★471](https://github.com/recruit-lifestyle/Smile-Lock) - A library for make a beautiful Passcode Lock View.
* [zxcvbn-ios ★148](https://github.com/dropbox/zxcvbn-ios) - A realistic password strength estimator.
* [TPObfuscatedString ★11](https://github.com/Techprimate/TPObfuscatedString) - Simple String obfuscation using core Swift. :large_orange_diamond:
* [LTHPasscodeViewController ★596](https://github.com/rolandleth/LTHPasscodeViewController) - An iOS passcode lockscreen replica (from Settings), with TouchID and simple (variable length) / complex support.
* [iOS-App-Security-Class ★33](https://github.com/karek314/iOS-App-Security-Class) - Simple class to check if iOS app has been cracked, being debugged or enriched with custom dylib and as well detect jailbroken environment.
* [BiometricAuth ★16](https://github.com/vasilenkoigor/BiometricAuth) - Simple framework for biometric authentication (via TouchID) in your application 🔶
* [SAPinViewController ★15](https://github.com/siavashalipour/SAPinViewController) - Simple and easy to use default iOS PIN screen. This simple library allows you to draw a fully customisable PIN screen same as the iOS default PIN view. My inspiration to create this library was form THPinViewController, however SAPinViewController is completely implemented in Swift. Also the main purpose of creating this library was to have simple, easy to use and fully customisable PIN screen. 🔶
* [VoiceItAPI1IosSDK ★4](https://github.com/voiceittech/VoiceItAPI1IosSDK) - A super easy way to add Voice Authentication(Biometrics) to your iOS apps, conveniently usable via cocoapods :large_orange_diamond:
* [TOPasscodeViewController ★223](https://github.com/timoliver/TOPasscodeViewController) - A modal passcode input and validation view controller for iOS
* [BiometricAuthentication ★349](https://github.com/rushisangani/BiometricAuthentication) - Use Apple FaceID or TouchID authentication in your app using BiometricAuthentication :large_orange_diamond:

#### Encryption
* [AESCrypt-ObjC ★700 ⏳1Y](https://github.com/Gurpartap/AESCrypt-ObjC) - A simple and opinionated AES encrypt / decrypt Objective-C class that just works.
* [IDZSwiftCommonCrypto ★356](https://github.com/iosdevzone/IDZSwiftCommonCrypto) - A wrapper for Apple's Common Crypto library written in Swift. :large_orange_diamond:
* [Arcane ★176](https://github.com/onmyway133/Arcane) - 🔱 Lightweight wrapper around CommonCrypto in Swift :large_orange_diamond:
* [SwiftMD5 ★12](https://github.com/mpurland/SwiftMD5) - A pure Swift implementation of MD5 :large_orange_diamond:
* [SwiftHash ★45](https://github.com/onmyway133/SwiftHash) - 🍕 Hash in Swift :large_orange_diamond:
* [SweetHMAC ★32 ⏳1Y](https://github.com/jancassio/SweetHMAC) - A tiny and easy to use Swift class to encrypt strings using HMAC algorithms. :large_orange_diamond:
* [SwCrypt ★431](https://github.com/soyersoyer/SwCrypt) - RSA public/private key generation, RSA, AES encryption/decryption, RSA sign/verify in Swift with CommonCrypto in iOS and macOS :large_orange_diamond:
* [SwiftSSL ★182 ⏳1Y](https://github.com/SwiftP2P/SwiftSSL) - An Elegant crypto toolkit in Swift. :large_orange_diamond:
* [SwiftyRSA ★381](https://github.com/TakeScoop/SwiftyRSA) - RSA public/private key encryption in Swift :large_orange_diamond:
* [EnigmaKit ★98](https://github.com/mikaoj/EnigmaKit) - Enigma encryption in Swift :large_orange_diamond:
* [Themis ★440](https://github.com/cossacklabs/themis) - High-level crypto library, providing basic asymmetric encryption, secure messaging with forward secrecy and secure data storage, supports iOS/macOS, Android and different server side platforms.
* [Obfuscator-iOS ★392](https://github.com/pjebs/Obfuscator-iOS) - Secure your app by obfuscating all the hard-coded security-sensitive strings.
* [swift-sodium ★191](https://github.com/jedisct1/swift-sodium) - Safe and easy to use crypto for iOS :large_orange_diamond:
* [CryptoSwift ★4631](https://github.com/krzyzanowskim/CryptoSwift) - Crypto related functions and helpers for Swift implemented in Swift programming language :large_orange_diamond:
* [SCrypto ★15](https://github.com/sgl0v/SCrypto) - Elegant Swift interface to access the CommonCrypto routines :large_orange_diamond:
* [SipHash ★193](https://github.com/attaswift/SipHash) - Simple and secure hashing in Swift with the SipHash algorithm. :large_orange_diamond:
* [RNCryptor ★2711](https://github.com/RNCryptor/RNCryptor) - CCCryptor (AES encryption) wrappers for iOS and Mac in Swift. -- For ObjC, see RNCryptor/RNCryptor-objc. :large_orange_diamond:

#### Keychain
* [UICKeyChainStore ★2470](https://github.com/kishikawakatsumi/UICKeyChainStore) - UICKeyChainStore is a simple wrapper for Keychain on iOS.
* [Valet ★2766](https://github.com/square/Valet) - Securely store data in the iOS or macOS Keychain without knowing a thing about how the Keychain works.
* [Locksmith ★2381](https://github.com/matthewpalmer/Locksmith) - A powerful, protocol-oriented library for working with the keychain in Swift. :large_orange_diamond:
* [KeychainAccess ★3366](https://github.com/kishikawakatsumi/KeychainAccess) - Simple Swift wrapper for Keychain that works on iOS and macOS :large_orange_diamond:
* [Keychains ★59](https://github.com/hyperoslo/Keychains) - Because you should care... about the security... of your shit. :large_orange_diamond:
* [Lockbox ★839 ⏳1Y](https://github.com/granoff/Lockbox) - Objective-C utility class for storing data securely in the key chain.
* [SAMKeychain ★4601](https://github.com/soffes/SAMKeychain) - Simple Objective-C wrapper for the keychain that works on Mac and iOS.
* [SwiftKeychainWrapper ★626](https://github.com/jrendel/SwiftKeychainWrapper) - A simple wrapper for the iOS Keychain to allow you to use it in a similar fashion to User Defaults. Written in Swift. :large_orange_diamond:

## Server
* [Perfect ★12367](https://github.com/PerfectlySoft/Perfect) - Server-side Swift. The Perfect library, application server, connectors and example apps. :large_orange_diamond:
* [Swifter ★2148](https://github.com/httpswift/swifter) - Tiny http server engine written in Swift programming language. :large_orange_diamond:
* [CocoaHTTPServer ★4346](https://github.com/robbiehanson/CocoaHTTPServer) - A small, lightweight, embeddable HTTP server for macOS or iOS applications.
* [Curassow ★393](https://github.com/kylef/Curassow) - Swift HTTP server using the pre-fork worker model. :large_orange_diamond:
* [Zewo ★1726](https://github.com/Zewo/Zewo) - Venice based HTTP server for Swift 2.2 on Linux :large_orange_diamond:
* [Vapor ★11654](https://github.com/vapor/vapor) - Elegant web framework for Swift that works on iOS, macOS, and Ubuntu. :large_orange_diamond:
* [swiftra ★273 ⏳1Y](https://github.com/takebayashi/swiftra) - Sinatra-like DSL for developing web apps in Swift :large_orange_diamond:
* [blackfire ★949](https://github.com/elliottminns/blackfire) - A fast HTTP web server based on Node.js and Express written in Swift :large_orange_diamond:
* [swift-http ★461 ⏳1Y](https://github.com/huytd/swift-http) - HTTP Implementation for Swift on Linux and macOS :large_orange_diamond:
* [Trevi ★47 ⏳1Y](https://github.com/Yoseob/Trevi) - libuv base Swift web HTTP server framework :large_orange_diamond:
* [Express ★848](https://github.com/crossroadlabs/Express) - Swift Express is a simple, yet unopinionated web application server written in Swift :large_orange_diamond:
* [Taylor ★924 ⏳1Y](https://github.com/izqui/Taylor) - A lightweight library for writing HTTP web servers with Swift :large_orange_diamond:
* [Frank ★381](https://github.com/kylef/Frank) - Frank is a DSL for quickly writing web applications in Swift :large_orange_diamond:
* [Kitura ★6124](https://github.com/IBM-Swift/Kitura) - A Swift Web Framework and HTTP Server :large_orange_diamond:
* [Swifton ★2055](https://github.com/necolt/Swifton) - A Ruby on Rails inspired Web Framework for Swift that runs on Linux and macOS :large_orange_diamond:
* [Dynamo ★65](https://github.com/johnno1962/Dynamo) - High Performance (nearly)100% Swift Web server supporting dynamic content. :large_orange_diamond:
* [Redis ★345](https://github.com/vapor/redis) - Pure-Swift Redis client implemented from the original protocol spec. macOS + Linux compatible. :large_orange_diamond:
* [NetworkObjects ★268 ⏳2Y](https://github.com/colemancda/NetworkObjects) - Swift backend / server framework (Pure Swift, Supports Linux) :large_orange_diamond:
* [Noze.io](http://noze.io) - Evented I/O streams a.k.a. Node.js for Swift. :large_orange_diamond:
* [Edge ★286](https://github.com/skylab-inc/Edge) - A Swift Multiplatform Web and Networking Framework. :large_orange_diamond:
* [SwiftGD ★177](https://github.com/twostraws/swiftgd) - A simple Swift wrapper for libgd. :large_orange_diamond:
* [Jobs ★153](https://github.com/BrettRToomey/Jobs) - A job system for Swift backends. :large_orange_diamond:
* [ApacheExpress ★168](https://github.com/ApacheExpress/ApacheExpress) - Write Apache Modules in Swift! :large_orange_diamond:
* [GCDWebServer ★3653](https://github.com/swisspol/GCDWebServer) - Lightweight GCD based HTTP server for macOS & iOS (includes web based uploader & WebDAV server)

## Text
* [Twitter Text Obj ★1780](https://github.com/twitter/twitter-text) - An Objective-C implementation of Twitter's text processing library.
* [Nimbus ★6357](https://github.com/jverkoey/nimbus) - Nimbus is a toolkit for experienced iOS software designers.
* [NSStringEmojize ★602](https://github.com/diy/nsstringemojize) - A category on NSString to convert Emoji Cheat Sheet codes to their equivalent Unicode characters.
* [MMMarkdown ★1096](https://github.com/mdiep/MMMarkdown) - An Objective-C static library for converting Markdown to HTML.
* [DTCoreText ★5181](https://github.com/Cocoanetics/DTCoreText) - Methods to allow using HTML code with CoreText.
* [DTRichTextEditor ★290](https://github.com/Cocoanetics/DTRichTextEditor) - A rich-text editor for iOS.
* [NBEmojiSearchView ★80 ⏳2Y](https://github.com/neerajbaid/NBEmojiSearchView) - A searchable emoji dropdown view.
* [Pluralize.swift ★134](https://github.com/joshualat/Pluralize.swift) - Great Swift String Pluralize Extension :large_orange_diamond:
* [RichEditorView ★951](https://github.com/cjwirth/RichEditorView) - RichEditorView is a simple, modular, drop-in UIView subclass for Rich Text Editing. :large_orange_diamond:
* [Money ★796](https://github.com/danthorpe/Money) - Swift value types for working with money & currency :large_orange_diamond:
* [PhoneNumberKit ★2128](https://github.com/marmelroy/PhoneNumberKit) - A Swift framework for parsing, formatting and validating international phone numbers. Inspired by Google's libphonenumber. :large_orange_diamond:
* [YYText ★6811](https://github.com/ibireme/YYText) - Powerful text framework for iOS to display and edit rich text.
* [Format ★1143](https://github.com/marmelroy/Format) - A Swift Formatter Kit. :large_orange_diamond:
* [Tribute ★57 ⏳1Y](https://github.com/zats/Tribute) - Programmatic creation of NSAttributedString doesn't have to be a pain :large_orange_diamond:
* [EmojiKit ★84](https://github.com/dasmer/EmojiKit) - Effortless emoji-querying in Swift :large_orange_diamond:
* [Roman ★31](https://github.com/nvzqz/Roman) - Seamless Roman numeral conversion in Swift. :large_orange_diamond:
* [ZSSRichTextEditor ★2634](https://github.com/nnhubbard/ZSSRichTextEditor) - A beautiful rich text WYSIWYG editor for iOS with a syntax highlighted source view.
* [pangu.Objective-C ★106](https://github.com/Cee/pangu.objective-c) - Paranoid text spacing in Objective-C.
* [SwiftString ★1424](https://github.com/amayne/SwiftString) - A comprehensive, lightweight string extension for Swift :large_orange_diamond:
* [Marklight ★362](https://github.com/macteo/Marklight) - Markdown syntax highlighter for iOS :large_orange_diamond:
* [MarkdownTextView ★550](https://github.com/indragiek/MarkdownTextView) - Rich Markdown editing control for iOS :large_orange_diamond:
* [TextAttributes ★1934](https://github.com/delba/TextAttributes) - An easier way to compose attributed strings. :large_orange_diamond:[e]
* [Reductio ★346](https://github.com/fdzsergio/Reductio) - Automatic summarizer text in Swift :large_orange_diamond:
* [SmarkDown ★60 ⏳1Y](https://github.com/SwiftStudies/SmarkDown) - A Pure Swift implementation of the markdown mark-up language :large_orange_diamond:
* [SwiftyMarkdown ★768](https://github.com/SimonFairbairn/SwiftyMarkdown) - Converts Markdown files and strings into NSAttributedString :large_orange_diamond:
* [SZMentions ★8 ⏳1Y](https://github.com/szweier/SZMentions) - Library to help handle mentions
* [SZMentionsSwift ★28](https://github.com/szweier/SZMentionsSwift) - Library to help handle mentions.
* [Heimdall ★293](https://github.com/henrinormak/Heimdall) - Heimdall is a wrapper around the Security framework for simple encryption/decryption operations. :large_orange_diamond:
* [NoOptionalInterpolation ★41](https://github.com/T-Pham/NoOptionalInterpolation) - Get rid of "Optional(...)" and "nil" in string interpolation. Easy pluralization.🔶[e]
* [Smile ★253](https://github.com/onmyway133/Smile) 😄 Emoji in Swift
* [ISO8601 ★12](https://github.com/onmyway133/iso8601) Super lightweight ISO8601 Date Formatter in Swift 🔶[e]
* [Translucid ★522](https://github.com/Ekhoo/Translucid) - Lightweight library to set an Image as text background. Written in swift. :large_orange_diamond:
* [FormatterKit ★4032](https://github.com/mattt/FormatterKit) - `stringWithFormat:` for the sophisticated hacker set
* [BonMot ★1858](https://github.com/Raizlabs/BonMot) - Beautiful, easy attributed strings in Swift :large_orange_diamond:
* [SwiftValidators ★125](https://github.com/gkaimakas/SwiftValidators) - String validation for iOS developed in Swift. Inspired by [validator.js](https://www.npmjs.com/package/validator).
* [StringStylizer ★32](https://github.com/kazuhiro4949/StringStylizer) - Type strict builder class for NSAttributedString. :large_orange_diamond:
* [SwiftyAttributes ★884](https://github.com/eddiekaiger/SwiftyAttributes) - Swift extensions that make it a breeze to work with attributed strings. :large_orange_diamond:
* [MarkdownKit ★112](https://github.com/ivanbruel/MarkdownKit) - A simple and customizable Markdown Parser for Swift. :large_orange_diamond:
* [CocoaMarkdown ★944](https://github.com/indragiek/CocoaMarkdown) - Markdown parsing and rendering for iOS and macOS. :large_orange_diamond:
* [Apodimark ★439](https://github.com/loiclec/Apodimark) - Fast, flexible markdown parser written in Swift. :large_orange_diamond:
* [Notepad ★305](https://github.com/ruddfawcett/Notepad) - A fully themeable markdown editor with live syntax highlighting. :large_orange_diamond:
* [KKStringValidator ★15 ⏳1Y](https://github.com/krizhanovskii/KKStringValidator) - Fast and simple string validation for iOS. With UITextField extension. :large_orange_diamond:
* [ISO8859 ★10](https://github.com/Cosmo/ISO8859) - 📄⚙ Convert ISO8859 1-16 Encoded Text to String in Swift. Supports iOS, tvOS, watchOS and macOS. :large_orange_diamond:
* [Emojica](https://github.com/xoudini/emojica) - Replace standard emoji in strings with a custom emoji set, such as [Twemoji](https://github.com/twitter/twemoji) or [EmojiOne ★3743](https://github.com/emojione/emojione). :large_orange_diamond:
* [SwiftRichString ★1244](https://github.com/malcommac/SwiftRichString) - Elegant & Painless Attributed Strings Management Library in Swift. :large_orange_diamond:
* [libPhoneNumber-iOS ★1739](https://github.com/iziz/libPhoneNumber-iOS) - iOS port from libphonenumber (Google's phone number handling library).
* [AttributedTextView ★216](https://github.com/evermeer/AttributedTextView) - Easiest way to create an attributed UITextView with support for multiple links (including hashtags and mentions).
* [StyleDecorator ★9](https://github.com/dimpiax/StyleDecorator) - Design string simply by linking attributes to needed parts
* [Mustard ★668](https://github.com/mathewsanders/Mustard) - Mustard is a Swift library for tokenizing strings when splitting by whitespace doesn't cut it. :large_orange_diamond:
* [Input Mask ★106](https://github.com/RedMadRobot/input-mask-ios) - Pattern-based user input formatter, parser and validator for iOS. :large_orange_diamond:
* [Attributed ★605](https://github.com/Nirma/Attributed) - Modern Swift µframework for attributed strings. :large_orange_diamond:
* [Atributika ★158](https://github.com/psharanda/Atributika) - Easily build NSAttributedString by detecting and styling HTML-like tags, hashtags, mentions, RegExp or NSDataDetector patterns. :large_orange_diamond:
* [Guitar ★544](https://github.com/ArtSabintsev/Guitar) - A Cross-Platform String Library Written in Swift. :large_orange_diamond:
* [RealTimeCurrencyFormatter ★11](https://github.com/kaiomedau/realtime-currency-formatter-objc) - An ObjC international currency formatting utility.
* [Down ★556](https://github.com/iwasrobbed/Down) - Blazing fast Markdown rendering in Swift, built upon cmark. 🔶
* [Marky Mark ★62](https://github.com/m2mobi/Marky-Mark) - Highly customizable Markdown parsing and native rendering in Swift. 🔶
* [MarkdownView ★1005](https://github.com/keitaoouchi/MarkdownView) - Markdown View for iOS. 🔶
* [Highlighter ★643](https://github.com/younatics/Highlighter) - Highlight whatever you want! Highlighter will magically find UI objects such as UILabel, UITextView, UITexTfield, UIButton in your UITableViewCell or other Class. :large_orange_diamond:

#### Font
* [FontBlaster ★856](https://github.com/ArtSabintsev/FontBlaster) - Programmatically load custom fonts into your iOS app. :large_orange_diamond:
* [GoogleMaterialIconFont ★136 ⏳1Y](https://github.com/kitasuke/GoogleMaterialIconFont) - Google Material Design Icons for Swift and ObjC project :large_orange_diamond:
* [ios-fontawesome ★1742](https://github.com/alexdrone/ios-fontawesome) - NSString+FontAwesome.
* [FontAwesome.swift ★901](https://github.com/thii/FontAwesome.swift) - Use FontAwesome in your Swift projects. :large_orange_diamond:
* [SwiftFontName ★91 ⏳1Y](https://github.com/morizotter/SwiftFontName) - OS font complements library. Localized font supported :large_orange_diamond:
* [SwiftIconFont ★801](https://github.com/0x73/SwiftIconFont) - Icons fonts for iOS (FontAwesome, Iconic, Ionicon, Octicon, Themify, MapIcon, MaterialIcon) :large_orange_diamond:
* [FontAwesomeKit ★2565](https://github.com/PrideChung/FontAwesomeKit) - Icon font library for iOS. Currently supports Font-Awesome, Foundation icons, Zocial, and ionicons.
* [Iconic ★1388](https://github.com/dzenbot/Iconic) - Auto-generated icon font library for iOS, watchOS and tvOS  :large_orange_diamond:
* [GoogleMaterialDesignIcons ★363](https://github.com/dekatotoro/GoogleMaterialDesignIcons) - Google Material Design Icons Font for iOS. :large_orange_diamond:
* [OcticonsKit ★33](https://github.com/keitaoouchi/OcticonsKit) - Use Octicons as UIImage / UIFont in your projects with Swifty manners. :large_orange_diamond:
* [IoniconsKit ★294](https://github.com/keitaoouchi/IoniconsKit) - Use Ionicons as UIImage / UIFont in your projects with Swifty manners. :large_orange_diamond:
* [FontAwesomeKit.Swift ★156](https://github.com/qiuncheng/FontAwesomeKit.Swift) - A better choice for iOS Developer to use FontAwesome Icon. :large_orange_diamond:
* [UIFontComplete ★899](https://github.com/Nirma/UIFontComplete) - Make working with UIFont faster and less error-prone. :large_orange_diamond:
* [Swicon ★34 ⏳1Y](https://github.com/UglyTroLL/Swicon) - Use 1600+ icons (and more!) from FontAwesome and Google Material Icons in your swift/iOS project in an easy and space-efficient way! :large_orange_diamond:
* [SwiftIcons ★344](https://github.com/ranesr/SwiftIcons) - A library for using different font icons: dripicons, emoji, font awesome, icofont, ionicons, linear icons, map icons, material icons, open iconic, state, weather. It supports UIImage, UIImageView, UILabel, UIButton, UISegmentedControl, UITabBarItem, UISlider, UIBarButtonItem, UIViewController, UITextfield, UIStepper. :large_orange_diamond:

## Testing

#### TDD / BDD
* [Kiwi ★3696](https://github.com/kiwi-bdd/Kiwi) - A behavior-driven development library for iOS development.
* [Specta ★2081](https://github.com/specta/specta) - A light-weight TDD / BDD framework for Objective-C & Cocoa.
* [Quick ★7029](https://github.com/Quick/Quick) - A behavior-driven development framework for Swift and Objective-C.
* [XcodeCoverage ★697](https://github.com/jonreid/XcodeCoverage) - Code coverage for Xcode projects.
* [OHHTTPStubs ★3459](https://github.com/AliSoftware/OHHTTPStubs) - Stub your network requests easily! Test your apps with fake network data and custom response time, response code and headers!
* [Dixie ★202 ⏳2Y](https://github.com/Skyscanner/Dixie) - Dixie is an open source Objective-C testing framework for altering object behaviours.
* [gh-unit ★1919 ⏳1Y](https://github.com/gh-unit/gh-unit) - Test Framework for Objective-C.
* [Nimble ★2498](https://github.com/Quick/Nimble) - A Matcher Framework for Swift and Objective-C :large_orange_diamond:
* [Sleipnir ★849 ⏳1Y](https://github.com/railsware/Sleipnir) - BDD-style framework for Swift :large_orange_diamond:
* [SwiftCheck ★863](https://github.com/typelift/SwiftCheck) - QuickCheck for Swift :large_orange_diamond:

#### A/B Testing
* [Switchboard ★266](https://github.com/KeepSafe/Switchboard) - Switchboard - easy and super light weight A/B testing for your mobile iPhone or android app. This mobile A/B testing framework allows you with minimal servers to run large amounts of mobile users.
* [SkyLab ★684 ⏳3Y](https://github.com/mattt/SkyLab) - Multivariate & A/B Testing for iOS and Mac
* [MSActiveConfig ★81 ⏳4Y](https://github.com/mindsnacks/MSActiveConfig) - Remote configuration and A/B Testing framework for iOS
* [ABKit ★99](https://github.com/recruit-mp/ABKit) - AB testing framework for iOS :large_orange_diamond:

#### UI Testing
* [CrashMonkey ★186 ⏳1Y](https://github.com/mokemokechicken/CrashMonkey) - Monkey Test Tool For iOS.
* [appium](http://appium.io/) - Appium is an open source test automation framework for use with native and hybrid mobile apps.
* [robotframework-appiumlibrary ★146](https://github.com/serhatbolsu/robotframework-appiumlibrary) - AppiumLibrary is an appium testing library for RobotFramework.
* [Cucumber](https://cucumber.io/) - Behavior driver development for iOS.
* [Kif ★5109](https://github.com/kif-framework/KIF) - An iOS Functional Testing Framework.
* [Subliminal ★788 ⏳2Y](https://github.com/inkling/Subliminal) - An understated approach to iOS integration testing.
* [ios-driver](http://ios-driver.github.io/ios-driver/index.html) - Test any iOS native, hybrid, or mobile web application using Selenium / WebDriver.
* [Zucchini ★164 ⏳3Y](https://github.com/zucchini-src/zucchini) - A visual iOS testing framework that loves your apps.
* [Remote ★650](https://github.com/johnno1962/Remote) - Control your iPhone from inside Xcode for end-to-end testing.
* [LayoutTest-iOS ★495](https://github.com/linkedin/LayoutTest-iOS) - Write unit tests which test the layout of a view in multiple configurations.
* [EarlGrey ★3937](https://github.com/google/EarlGrey) - :tea: iOS UI Automation Test Framework.
* [UI Testing Cheat Sheet ★1190](https://github.com/joemasilotti/UI-Testing-Cheat-Sheet) - How do I test this with UI Testing? :large_orange_diamond:
* [Floater_ ★234 ⏳1Y](https://github.com/Buglife/Floater_) - Add a floating fingertip to your app demo :large_orange_diamond:
* [Bluepill ★2478](https://github.com/linkedin/bluepill) - Bluepill is a reliable iOS testing tool that runs UI tests using multiple simulators on a single machine
* [Flawless App](https://flawlessapp.io/) - tool for visual quality check of mobile app in a real-time. It compares initial design with the actual implementation right inside iOS simulator.

#### Other Testing
* [NaughtyKeyboard ★584 ⏳2Y](https://github.com/Palleas/NaughtyKeyboard) - The Big List of Naughty Strings is a list of strings which have a high probability of causing issues when used as user-input data. This is a keyboard to help you test your app from your iOS device.
* [Fakery ★771](https://github.com/vadymmarkov/Fakery) - Swift fake data generator. :large_orange_diamond:
* [DVR ★508](https://github.com/venmo/DVR) - Network testing for Swift :large_orange_diamond:
* [Cuckoo ★630](https://github.com/Brightify/Cuckoo) - First boilerplate-free mocking framework for Swift :large_orange_diamond:
* [Parallel iOS Tests ★0](https://github.com/plu/parallel_ios_tests) - Run iOS tests on multiple simulators in parallel at the same time :large_orange_diamond:
* [Vinyl ★206](https://github.com/Velhotes/Vinyl) - Network testing à la VCR in Swift :large_orange_diamond:
* [Mockit ★62](https://github.com/sabirvirtuoso/Mockit) - A simple mocking framework for Swift, inspired by the famous Mockito for Java :large_orange_diamond:
* [Cribble ★273 ⏳1Y](https://github.com/maxsokolov/Cribble) - Swifty tool for visual testing iPhone and iPad apps :large_orange_diamond:
* [second_curtain ★113 ⏳2Y](https://github.com/ashfurrow/second_curtain) - Upload failing iOS snapshot tests cases to S3
* [trainer ★96](https://github.com/KrauseFx/trainer) - Convert xcodebuild plist files to JUnit reports
* [Buildasaur ★720](https://github.com/buildasaurs/Buildasaur) - Automatic testing of your Pull Requests on GitHub and BitBucket using Xcode Server. Keep your team productive and safe. Get up and running in minutes. @buildasaur :large_orange_diamond:
* [Kakapo ★731](https://github.com/devlucky/Kakapo) - 🐤Dynamically Mock server behaviors and responses in Swift :large_orange_diamond:
* [AcceptanceMark ★55](https://github.com/bizz84/AcceptanceMark) Tool to auto-generate Xcode tests classes from Markdown tables
* [MetovaTestKit ★19](https://github.com/metova/MetovaTestKit) - A collection of testing utilities to turn crashing test suites into failing test suites. :large_orange_diamond:
* [MirrorDiffKit ★95](https://github.com/Kuniwak/MirrorDiffKit) - Pretty diff between any structs or classes :large_orange_diamond:
* [SnappyTestCase ★8](https://github.com/tooploox/SnappyTestCase) - iOS Simulator type agnostic snapshot testing, built on top of the FBSnapshotTestCase. :large_orange_diamond:

## UI
* [FlatUIKit ★7671 ⏳1Y](https://github.com/Grouper/FlatUIKit) - A collection of awesome flat UI components for iOS.
* [BetweenKit ★260](https://github.com/ice3-software/between-kit) - A robust drag-and-drop framework for iOS.
* [MDCSwipeToChoose ★2477](https://github.com/modocache/MDCSwipeToChoose) - Swipe to "like" or "dislike" any view, just like Tinder.app. Build a flashcard app, a photo viewer, and more, in minutes, not hours!
* [Motif ★813](https://github.com/erichoracek/Motif) - A lightweight and customizable JSON stylesheet framework for iOS.
* [Texture ★2321](https://github.com/TextureGroup/Texture) - Smooth asynchronous user interfaces for iOS apps.
* [GaugeKit ★896](https://github.com/skywinder/GaugeKit) - Customizable gauges. Easy reproduce Apple's style gauges. :large_orange_diamond:
* [MVMaterialView ★66 ⏳1Y](https://github.com/TheMrugraj/MVMaterialView) - Subclass of UIControls and UIButton to mimic Ripple effect of Material Design concept.
* [TisprCardStack ★654](https://github.com/tispr/tispr-card-stack) - Library that allows to have cards UI. :large_orange_diamond:
* [SAHistoryNavigationViewController ★1490](https://github.com/marty-suzuki/SAHistoryNavigationViewController) - SAHistoryNavigationViewController realizes iOS task manager like UI in UINavigationContoller,3D Touch Compatible. :large_orange_diamond:
* [SAInboxViewController ★283](https://github.com/marty-suzuki/SAInboxViewController) - UIViewController subclass inspired by "Inbox by google" animated transitioning. :large_orange_diamond:
* [iCarousel ★9965](https://github.com/nicklockwood/iCarousel) - A simple, highly customisable, data-driven 3D carousel for iOS and Mac OS.
* [Cocoa Controls](https://www.cocoacontrols.com/) - Open source UI components for iOS and macOS.
* [tapkulibrary ★4011 ⏳1Y](https://github.com/devinross/tapkulibrary) - tap + haiku = tapku, a well crafted open source iOS framework.
* [HorizontalDial ★103](https://github.com/kciter/HorizontalDial) - A horizontal scroll dial like Instagram. :large_orange_diamond:
* [ComponentKit](http://componentkit.org/) - A React-Inspired View Framework for iOS, by Facebook.
* [PMTween ★337 ⏳1Y](https://github.com/poetmountain/PMTween) - An elegant and flexible tweening library for iOS.
* [RKNotificationHub ★2801](https://github.com/cwRichardKim/RKNotificationHub) - Make any UIView a full fledged notification center.
* [EatFit ★605](https://github.com/Yalantis/EatFit) - Eat fit is a component for attractive data representation inspired by Google Fit :large_orange_diamond:
* [phone-number-picker ★115 ⏳1Y](https://github.com/hughbe/phone-number-picker) - A simple and easy to use view controller enabling you to enter a phone number with a country code similar to WhatsApp written in Swift :large_orange_diamond:
* [EXTView ★153 ⏳1Y](https://github.com/recruit-mtl/EXTView) - Extended UIView for Interface Builder by using IB_DESIGNABLE and IBInspectable.
* [SFFocusViewLayout ★1591](https://github.com/fdzsergio/SFFocusViewLayout) - UICollectionViewLayout with focused content.
* [CardAnimation ★992](https://github.com/seedante/CardAnimation) - Card flip animation by pan gesture. :large_orange_diamond:
* [BEMCheckBox ★1913](https://github.com/Boris-Em/BEMCheckBox#sample-app) - Tasteful Checkbox for iOS. (Check box)
* [HorizontalProgress ★158](https://github.com/AliThink/HorizontalProgress) - Simple horizontal progress bar with animation
* [JRSplitVC ★29 ⏳1Y](https://github.com/tommypeps/JRSplitVC) - UISplitViewController with adaptative layouts
* [MPParallaxView ★1502](https://github.com/DroidsOnRoids/MPParallaxView) - Apple TV Parallax effect in Swift. :large_orange_diamond:
* [Splitflap ★766](https://github.com/yannickl/Splitflap) - A simple split-flap display for your Swift applications :large_orange_diamond:
* [EZSwipeController ★706](https://github.com/goktugyil/EZSwipeController) - :point_up_2: UIPageViewController like Snapchat/Tinder/iOS Main Pages :large_orange_diamond:
* [Koloda ★3512](https://github.com/Yalantis/Koloda) - KolodaView is a class designed to simplify the implementation of Tinder like cards on iOS. :large_orange_diamond:
* [XLActionController ★2240](https://github.com/xmartlabs/XLActionController) - Fully customizable and extensible action sheet controller written in Swift. :large_orange_diamond:
* [StackPageView ★34 ⏳1Y](https://github.com/noppefoxwolf/StackPageView) - Vertical page view with UIViewControllers stacked on the top of each other :large_orange_diamond:
* [PageControl ★95](https://github.com/kasper-lahti/PageControl) - ● ○ ○ ○ A nice, animated UIPageControl alternative. :large_orange_diamond:
* [Curry ★32](https://github.com/devinross/curry) - Curry is a framework built to enhance and compliment Foundation and UIKit.
* [Pages ★369](https://github.com/hyperoslo/Pages) - :page_facing_up: UIPageViewController made simple :large_orange_diamond:
* [BothamUI ★341](https://github.com/Karumi/BothamUI) - Model View Presenter Framework written in Swift. :large_orange_diamond:
* [RainbowNavigation ★656](https://github.com/DanisFabric/RainbowNavigation) - An easy way to change backgroundColor of UINavigationBar when Push & Pop :large_orange_diamond:
* [ALTextInputBar ★184](https://github.com/AlexLittlejohn/ALTextInputBar) - An auto growing text input bar for messaging apps. :large_orange_diamond:
* [APCustomBlurView ★154 ⏳1Y](https://github.com/collinhundley/APCustomBlurView) - A subclass of UIVisualEffectView with customizable blur radius. :large_orange_diamond:
* [BAFluidView ★1274](https://github.com/antiguab/BAFluidView) - UIView that simulates a 2D view of a fluid in motion
* [WZDraggableSwitchHeaderView ★509 ⏳1Y](https://github.com/wongzigii/WZDraggableSwitchHeaderView) - :hammer: Showing status for switching between viewControllers
* [MICountryPicker ★76](https://github.com/mustafaibrahim989/MICountryPicker) - Swift country picker with search option. :large_orange_diamond:
* [SCNavigationControlCenter ★396 ⏳1Y](https://github.com/SergioChan/SCNavigationControlCenter) - This is an advanced navigation control center on iOS that can allow you to navigate to whichever view controller you want
* [SCTrelloNavigation ★782](https://github.com/SergioChan/SCTrelloNavigation) - :clipboard: An iOS native implementation of a Trello Animated Navagation.
* [FXBlurView ★5000](https://github.com/nicklockwood/FXBlurView) - UIView subclass that replicates the iOS 7 realtime background blur effect, but works on iOS 5 and above.
* [NGAParallaxMotion ★681 ⏳2Y](https://github.com/michaeljbishop/NGAParallaxMotion) - A tiny category on UIView that allows you to set one property: "parallaxIntensity" to achieve a parallax effect with UIMotionEffect
* [EPShapes ★371](https://github.com/ipraba/EPShapes) - Design shapes in Interface Builder. :large_orange_diamond:
* [CRParticleEffect ★355 ⏳1Y](https://github.com/Cleveroad/CRParticleEffect) - A CocoaPod that simplifies creation of the particle effects.
* [Spots ★1168](https://github.com/hyperoslo/Spots) - Spots is a view controller framework that makes your setup and future development blazingly fast. :large_orange_diamond:
* [APAddressBook ★1388](https://github.com/Alterplay/APAddressBook) - Easy access to iOS address book
* [AZExpandableIconListView ★191 ⏳1Y](https://github.com/Azuritul/AZExpandableIconListView) - An expandable/collapsible view component written in Swift. :large_orange_diamond:
* [greedo-layout-for-ios ★806](https://github.com/500px/greedo-layout-for-ios) - Full aspect ratio grid layout for iOS
* [FlourishUI ★205 ⏳1Y](https://github.com/thinkclay/FlourishUI) - A highly configurable and out-of-the-box-pretty UI library :large_orange_diamond:
* [GranadaLayout ★41](https://github.com/gskbyte/GranadaLayout) - Alternative layout system for iOS, inspired on the Android layout system, that includes linear and relative layouts, as well as an extensible JSON-based layout inflater.
* [Navigation Stack ★1902](https://github.com/Ramotion/navigation-stack) - Navigation Stack is a stack-modeled navigation controller. :large_orange_diamond:
* [UIView-draggable ★383](https://github.com/andreamazz/UIView-draggable) - UIView category that adds dragging capabilities.
* [PeekPop ★1870](https://github.com/marmelroy/PeekPop) - Backwards-compatible Peek and Pop.
* [MKGradientView ★75](https://github.com/maxkonovalov/MKGradientView) - Core Graphics based gradient view capable of producing Linear (Axial), Radial (Circular), Conical (Angular), Bilinear (Four Point) gradients, written in Swift. 🔶
* [EPSignature ★641](https://github.com/ipraba/EPSignature) - Signature component for iOS in Swift :large_orange_diamond:
* [CoreDragon ★714 ⏳1Y](https://github.com/nevyn/CoreDragon)  - [iOS] Stop using context menus. Drag and drop instead, even between apps!
* [AEConicalGradient ★40 ⏳1Y](https://github.com/tadija/AEConicalGradient) - Conical (angular) gradient layer written in Swift. :large_orange_diamond:
* [EVFaceTracker ★220](https://github.com/evermeer/EVFaceTracker) - Calculate the distance and angle of your device with regards to your face.
* [Fashion ★73](https://github.com/vadymmarkov/Fashion) - Fashion accessories and beauty tools to share and reuse UI styles in a Swifty way. :large_orange_diamond:
* [LeeGo ★903](https://github.com/wangshengjia/LeeGo) - Declarative, configurable & highly reusable UI development as making Lego bricks. :large_orange_diamond:
* [MEVHorizontalContacts ★301 ⏳1Y](https://github.com/manuelescrig/MEVHorizontalContacts) - An iOS UICollectionViewLayout subclass to show a list of contacts with configurable expandable menu items.
* [Ripple ★54 ⏳1Y](https://github.com/RamonGilabert/Ripple) - Remember there's no such thing as a small act of kindness. Every act creates a ripple with no logical end. :large_orange_diamond:
* [ScalePicker ★140](https://github.com/kronik/ScalePicker) - Generic scale and a handy float-value picker for any iOS app.
* [VisualEffectView ★440](https://github.com/efremidze/VisualEffectView) - UIVisualEffectView subclass with tint color. :large_orange_diamond:
* [NumPad ★45](https://github.com/efremidze/NumPad) - Number Pad (inspired by Square's design). :large_orange_diamond:
* [expanding-collection ★3975](https://github.com/Ramotion/expanding-collection) - ExpandingCollection is a card peek/pop controller :large_orange_diamond:
* [Cacao ★715](https://github.com/PureSwift/Cacao) - Pure Swift Cross-platform UIKit (Cocoa Touch) implementation (Supports Linux) :large_orange_diamond:
* [LFTimePicker ★36](https://github.com/awesome-labs/LFTimePicker) - Custom Time Picker ViewController with Selection of start and end times in Swift :large_orange_diamond:
* [StateView ★496](https://github.com/sahandnayebaziz/StateView) - Views that automatically update themselves. :large_orange_diamond:
* [JDFlipNumberView ★721](https://github.com/calimarkus/JDFlipNumberView) - Representing analog flip numbers like airport/trainstation displays.
* [JQSwiftIcon ★5](https://github.com/josejuanqm/JQSwiftIcon) - Icon Fonts on iOS using string interpolation written in Swift. :large_orange_diamond:
* [FlickToDismiss ★206 ⏳1Y](https://github.com/jakelawson1/FlickToDismiss) - A basic UIViewController class that presents a UIView which can be dismissed by flicking it off the screen. :large_orange_diamond:
* [ISTimeline ★884](https://github.com/instant-solutions/ISTimeline) - Simple timeline view written in Swift 2.2 :large_orange_diamond:
* [JFCardSelectionViewController ★392](https://github.com/atljeremy/JFCardSelectionViewController) - A fancy collection style view controller :large_orange_diamond:
* [DCKit ★89](https://github.com/agordeev/DCKit) - Set of iOS controls, which have useful IBInspectable properties. Written on Swift. :large_orange_diamond:
* [BackgroundVideoiOS ★501](https://github.com/Guzlan/BackgroundVideoiOS) - A swift and objective-C object that lets you add a background video to iOS views.
* [NightNight ★598](https://github.com/Draveness/NightNight) - Elegant way to integrate night mode to swift projects :large_orange_diamond:
* [SwiftTheme ★952](https://github.com/jiecao-fm/SwiftTheme) - Powerful theme/skin manager for iOS 7+ :large_orange_diamond:
* [PinpointKit ★980](https://github.com/Lickability/PinpointKit) - Let your testers and users send feedback with annotated screenshots and logs using a simple gesture. :large_orange_diamond:
* [FDStackView ★2339 ⏳1Y](https://github.com/forkingdog/FDStackView) - Use UIStackView directly in iOS6+
* [Popover ★1301](https://github.com/corin8823/Popover) - Popover is a balloon library like Facebook app. It is written in pure swift. :large_orange_diamond:
* [YangMingShan ★615](https://github.com/yahoo/YangMingShan) - YangMingShan is a collection of iOS UI components that we created while building Yahoo apps.
* [TOActionSheet ★158](https://github.com/TimOliver/TOActionSheet) - A custom-designed reimplementation of the UIActionSheet control for iOS
* [nui ★3754](https://github.com/tombenner/nui) - Style iOS apps with a stylesheet, similar to CSS
* [RedBeard](http://www.redbeard.io/) - It's a complete framework that takes away much of the pain of getting a beautiful, powerful iOS App crafted.
* [Material ★8828](https://github.com/CosmicMind/Material) - Material is an animation and graphics framework that allows developers to easily create beautiful applications. :large_orange_diamond:
* [Blurable ★819](https://github.com/FlexMonkey/Blurable) - Apply a Gaussian Blur to any UIView with Swift Protocol Extensions :large_orange_diamond:
* [EZYGradientView ★300 ⏳1Y](https://github.com/shashankpali/EZYGradientView) - Create gradients and blur gradients without a single line of code :large_orange_diamond:
* [DistancePicker ★93](https://github.com/qmathe/DistancePicker) - Custom control to select a distance with a pan gesture, written in Swift. :large_orange_diamond:
* [OAStackView ★2172](https://github.com/nsomar/OAStackView) - OAStackView tries to port back the stackview to iOS 7+. OAStackView aims at replicating all the features in UIStackView.
* [StyleKit ★1128](https://github.com/146BC/StyleKit) - StyleKit is a microframework that enables you to style your applications using a simple JSON file. Behind the scenes, StyleKit uses UIAppearance and some selector magic to apply the styles. You can also customize the parser for greater flexibility. :large_orange_diamond:
* [planet ★49](https://github.com/kwallet/planet) - A country picker :large_orange_diamond:
* [PageController ★205](https://github.com/hirohisa/PageController) - Infinite paging controller, scrolling through contents and title bar scrolls with a delay. :large_orange_diamond:
* [StatusProvider ★794](https://github.com/mariohahn/StatusProvider) - Protocol to handle initial Loadings, Empty Views and Error Handling in a ViewController & views :large_orange_diamond:
* [ASBubbleDrag ★38 ⏳1Y](https://github.com/scamps88/ASBubbleDrag) - round icon drag control (made in swift) dock style :large_orange_diamond:
* [StackLayout ★75](https://github.com/bridger/StackLayout) - An alternative to UIStackView for common Auto Layout patterns.
* [NightView ★159 ⏳1Y](https://github.com/Boris-Em/NightView) - Dazzling Nights on iOS. :large_orange_diamond:
* [VENTokenField ★745 ⏳1Y](https://github.com/venmo/VENTokenField) - Easy-to-use token field that is used in the Venmo app.
* [SwiftVideoBackground ★88](https://github.com/dingwilson/SwiftVideoBackground) - Easy to Use UIView subclass for implementing a video background :large_orange_diamond:
* [MRArticleViewController ★101](https://github.com/mrigdon/MRArticleViewController) - Easily create UIViewControllers for news articles similar to those in the News app. :large_orange_diamond:
* [Macaw ★3187](https://github.com/exyte/macaw) - Powerful and easy-to-use vector graphics library with SVG support written in Swift. :large_orange_diamond:
* [HubFramework ★1785](https://github.com/spotify/HubFramework) - Spotify’s component-driven UI framework for iOS.
* [ConfettiView ★216](https://github.com/OrRon/ConfettiView) - Confetti View lets you create a magnificent confetti view in your app :large_orange_diamond:
* [BouncyPageViewController ★616 ⏳1Y](https://github.com/BohdanOrlov/BouncyPageViewController) - Page view controller with bounce effect :large_orange_diamond:
* [LTHRadioButton ★193](https://github.com/rolandleth/LTHRadioButton) - A radio button with a pretty fill animation. :large_orange_diamond:
* [CRRulerControl ★92 ⏳1Y](https://github.com/Cleveroad/CRRulerControl) - Customizable component is aimed at turning a simple ruler into a handy and smart instrument.
* [Macaw-Examples ★149](https://github.com/exyte/Macaw-Examples) - Various usages of the Macaw library. :large_orange_diamond:
* [KVCardSelectionVC ★14 ⏳1Y](https://github.com/kunalverma25/KVCardSelectionVC) - Awesome looking Dial like card selection ViewController. :large_orange_diamond:
* [Reactions ★439](https://github.com/yannickl/Reactions) - Fully customizable Facebook reactions control :large_orange_diamond:
* [Newly ★173](https://github.com/dhirajjadhao/Newly) - Newly is a drop in solution to add Twitter/Facebook/Linkedin-style new updates/tweets/posts available button :large_orange_diamond:
* [CardStackController ★334](https://github.com/jobandtalent/CardStackController) - iOS custom controller used in Jobandtalent app to present new view controllers as cards :large_orange_diamond:
* [Material Components ★1753](https://github.com/material-components/material-components-ios) - Google developed UI components that help developers execute Material Design.
* [DMSwipeCards ★197](https://github.com/D-32/DMSwipeCards) - Tinder like card stack that supports lazy loading and generics :large_orange_diamond:
* [RKMultiUnitRuler ★20](https://github.com/farshidce/RKMultiUnitRuler) - Simple customizable ruler control that supports multiple units. 🔶
* [FAQView ★358](https://github.com/mukeshthawani/FAQView) - An easy to use FAQ view for iOS written in Swift. :large_orange_diamond:
* [CRPageViewController ★370](https://github.com/Cleveroad/CRPageViewController) - While a standard page view allows you to navigate between pages by using simple gestures, our component goes further.
* [OXPatternLock ★18](https://github.com/oxozle/OXPatternLock) - An iOS pattern lock like Android authentication written in Swift. :large_orange_diamond:
* [LMArticleViewController ★5](https://github.com/lucamozza/LMArticleViewController) - UIViewController subclass to beautifully present news articles and blog posts
* [FSPagerView ★2389](https://github.com/WenchaoD/FSPagerView) - FSPagerView is an elegant Screen Slide Library. It is extremely helpful for making Banner、Product Show、Welcome/Guide Pages、Screen/ViewController Sliders. :large_orange_diamond:
* [PanelKit ★2869](https://github.com/louisdh/panelkit) - A UI framework that enables panels on iOS. :large_orange_diamond:
* [ElongationPreview ★621](https://github.com/Ramotion/elongation-preview) - ElongationPreview is an elegant push-pop style view controller with 3D-Touch support and gestures. :large_orange_diamond:
* [Pageboy ★878](https://github.com/uias/Pageboy) - A simple, highly informative page view controller. :large_orange_diamond:
* [IGColorPicker ★74](https://github.com/iGenius-Srl/IGColorPicker) - 🎨 A customizable color picker for iOS in Swift 🔶
* [KPActionSheet ★4](https://github.com/khuong291/KPActionSheet) - 🔶 A replacement of default action sheet, but has very simple usage. 🔶
* [SegmentedProgressBar ★174](https://github.com/D-32/SegmentedProgressBar) - Snapchat / Instagram Stories style animated indicator :large_orange_diamond:
* [CHIPageControl ★1597](https://github.com/ChiliLabs/CHIPageControl) - A set of cool animated page controls to replace boring UIPageControl. :large_orange_diamond:
* [Magnetic ★695](https://github.com/efremidze/Magnetic) - SpriteKit Floating Bubble Picker (inspired by Apple Music). 🔶
* [AmazingBubbles ★37](https://github.com/GlebRadchenko/AmazingBubbles) - Apple Music like Bubble Picker using Dynamic Animation. 🔶
* [Haptica ★200](https://github.com/efremidze/Haptica) - Easy Haptic Feedback Generator. :large_orange_diamond:
* [GDCheckbox ★3](https://github.com/saeid/GDCheckbox) - An easy to use custom checkbox/radio button component for iOS, with support of IBDesign Inspector. 🔶
* [HamsterUIKit ★9](https://github.com/ChromieIsDangerous/HamsterUIKit) - A simple and elegant UIKit(Chart) for iOS.  🔶
* [AZEmptyState ★64](https://github.com/Minitour/AZEmptyState) - A UIControl subclass that makes it easy to create empty states. 🔶
* [URWeatherView ★333](https://github.com/jegumhon/URWeatherView) - Show the weather effects onto view written in Swift3. 🔶
* [LCUIComponents ★5](https://github.com/linhcn/LCUIComponents) - A framework supports creating transient views on top of other content onscreen such as popover with a data list. 🔶
* [ViewComposer ★14](https://github.com/Sajjon/ViewComposer) - `let lbl: UILabel = [.text("Hello"), .textColor(.red)]` - Create views using array literal of enum expressing view attributes.
* [BatteryView ★10](https://github.com/yonat/BatteryView) - Simple battery shaped UIView. 🔶
* [ShadowView ★215](https://github.com/PierrePerrin/ShadowView) - Make shadows management easy on UIView :large_orange_diamond:
* [Pulley ★843](https://github.com/52inc/Pulley) - A library to imitate the iOS 10 Maps UI :large_orange_diamond:
* [N8iveKit ★18](https://github.com/n8iveapps/N8iveKit) - A set of frameworks making iOS development more fun. :large_orange_diamond:
* [Panda ★16](https://github.com/wordlessj/Panda) - Create view hierarchies declaratively. :large_orange_diamond:
* [NotchKit ★1786](https://github.com/HarshilShah/NotchKit) - A simple way to hide the notch on the iPhone X :large_orange_diamond:
* [Overlay ★35](https://github.com/TintPoint/Overlay) - Overlay is a flexible UI framework designed for Swift. It allows you to write CSS like Swift code. :large_orange_diamond:
* [SwiftyUI ★106](https://github.com/haoking/SwiftyUI) - High performance and lightweight(one class each UI) UIView, UIImage, UIImageView, UIlabel, UIButton, Promise and more. 🔶
* [NotchToolkit ★32](https://github.com/AFathi/NotchToolkit) - A framework for iOS that allow developers use the iPhone X notch in creative ways. 🔶
* [PullUpController ★345](https://github.com/MarioIannotta/PullUpController) - Pull up controller with multiple sticky points like in iOS Maps. 🔶
* [DrawerKit ★394](https://github.com/Babylonpartners/DrawerKit) - DrawerKit lets an UIViewController modally present another UIViewController in a manner similar to the way Apple's Maps app works. :large_orange_diamond:
* [TimelineCards ★155](https://github.com/vladaverin24/TimelineCards) - Presenting timelines as cards, single or bundled in scrollable feed!.
* [Shades ★3](https://github.com/aaronjsutton/Shades) - Easily add drop shadows, borders, and round corners to a UIView. :large_orange_diamond:

#### Activity Indicator

* [NVActivityIndicatorView ★6040](https://github.com/ninjaprox/NVActivityIndicatorView) - Collection of nice loading animations. :large_orange_diamond:
* [TKRubberIndicator ★1044](https://github.com/TBXark/TKRubberIndicator) - Rubber Indicator in Swift :large_orange_diamond:
* [RPLoadingAnimation ★179 ⏳1Y](https://github.com/naoyashiga/RPLoadingAnimation) - Loading animations :cyclone: by using Swift CALayer :large_orange_diamond:
* [LiquidLoader ★1007](https://github.com/yoavlt/LiquidLoader) - Spinner loader components with liquid animation :large_orange_diamond:
* [iOS-CircleProgressView ★395](https://github.com/CardinalNow/iOS-CircleProgressView) - This control will allow a user to use code instantiated or interface builder to create and render a circle progress view. :large_orange_diamond:
* [iOS Circle Progress Bar ★343](https://github.com/Eclair/CircleProgressBar) - iOS Circle Progress Bar
* [LinearProgressBar ★87](https://github.com/PhilippeBoisney/LinearProgressBar) - Linear Progress Bar (inspired by Google Material Design) for iOS written in Swift 2.0. :large_orange_diamond:
* [STLoadingGroup ★312](https://github.com/saitjr/STLoadingGroup) - loading views :large_orange_diamond:
* [ALThreeCircleSpinner ★35 ⏳1Y](https://github.com/AlexLittlejohn/ALThreeCircleSpinner) - A pulsing spinner view written in swift :large_orange_diamond:
* [MHRadialProgressView ★81 ⏳1Y](https://github.com/mehfuzh/MHRadialProgressView) - iOS 7 radial animated progress view.
* [Loader ★88 ⏳1Y](https://github.com/Ekhoo/Loader) - Amazing animated switch activity indicator written in swift :large_orange_diamond:
* [MBProgressHUD ★13924](https://github.com/jdg/MBProgressHUD) - Drop-in class for displays a translucent HUD with an indicator and/or labels while work is being done in a background thread.
* [SVProgressHUD ★10352](https://github.com/SVProgressHUD/SVProgressHUD) - A clean and lightweight progress HUD for your iOS app.
* [ProgressHUD ★973](https://github.com/relatedcode/ProgressHUD) - ProgressHUD is a lightweight and easy-to-use HUD.
* [M13ProgressSuite ★3621](https://github.com/Marxon13/M13ProgressSuite) - A suite containing many tools to display progress information on iOS.
* [PKHUD ★2557](https://github.com/pkluz/PKHUD) - A Swift based reimplementation of the Apple HUD (Volume, Ringer, Rotation,…) for iOS 8 and above. :large_orange_diamond:
* [EZLoadingActivity ★524](https://github.com/goktugyil/EZLoadingActivity) - Lightweight loading activity HUD.  :large_orange_diamond:
* [FFCircularProgressView ★1003 ⏳1Y](https://github.com/elbryan/FFCircularProgressView) - FFCircularProgressView - An iOS 7-inspired blue circular progress view
* [MRProgress ★2586](https://github.com/mrackwitz/MRProgress) - Collection of iOS drop-in components to visualize progress
* [BigBrother ★455](https://github.com/marcelofabri/BigBrother) - Automatically sets the network activity indicator for any performed request. :large_orange_diamond:
* [AlamofireNetworkActivityIndicator ★429](https://github.com/Alamofire/AlamofireNetworkActivityIndicator) - Controls the visibility of the network activity indicator on iOS using Alamofire. :large_orange_diamond:
* [KDCircularProgress ★657](https://github.com/kaandedeoglu/KDCircularProgress) - A circular progress view with gradients written in Swift :large_orange_diamond:
* [DACircularProgress ★2229](https://github.com/danielamitay/DACircularProgress) - DACircularProgress is a UIView subclass with circular UIProgressView properties.
* [KYNavigationProgress ★193](https://github.com/ykyouhei/KYNavigationProgress) - Simple extension of UINavigationController to display progress on the UINavigationBar. :large_orange_diamond:[e]
* [GearRefreshControl ★560](https://github.com/andreamazz/GearRefreshControl) - A custom animation for the UIRefreshControl :large_orange_diamond:
* [NJKWebViewProgress ★3772](https://github.com/ninjinkun/NJKWebViewProgress) - A progress interface library for UIWebView. You can implement progress bar for your in-app browser using this module.
* [MKRingProgressView ★651](https://github.com/maxkonovalov/MKRingProgressView) - A beautiful ring/circular progress view similar to Activity app on Apple Watch, written in Swift. 🔶
* [Hexacon ★252](https://github.com/gautier-gdx/Hexacon) - A new way to display content in your app like the Apple Watch SpringBoard, written in Swift. 🔶
* [StackViewController ★617](https://github.com/seedco/StackViewController) - A controller that uses a UIStackView and view controller composition to display content in a list :large_orange_diamond:
* [ParticlesLoadingView ★777](https://github.com/BalestraPatrick/ParticlesLoadingView) - A customizable SpriteKit particles animation on the border of a view. :large_orange_diamond:
* [RPCircularProgress ★112](https://github.com/iwasrobbed/RPCircularProgress) - (Swift) Circular progress UIView subclass with UIProgressView properties :large_orange_diamond:
* [MBCircularProgressBar ★698](https://github.com/MatiBot/MBCircularProgressBar) -  A circular, animatable & highly customizable progress bar, editable from the Interface Builder using IBDesignable.
* [WSProgressHUD ★533](https://github.com/devSC/WSProgressHUD) - This is a beautiful hud view for iPhone & iPad
* [DBMetaballLoading ★56 ⏳1Y](https://github.com/dabing1022/DBMetaballLoading) - A metaball loading written in Swift. :large_orange_diamond:
* [FillableLoaders ★1767](https://github.com/polqf/FillableLoaders) - Completely customizable progress based loaders drawn using custom CGPaths written in Swift :large_orange_diamond:
* [PageControls ★635](https://github.com/popwarsweet/PageControls) - This is a selection of custom page controls to replace UIPageControl, inspired by a dribbble found here :large_orange_diamond:
* [VHUD ★127](https://github.com/xxxAIRINxxx/VHUD) Simple HUD. :large_orange_diamond:
* [SwiftSpinner ★1652](https://github.com/icanzilb/SwiftSpinner) - A beautiful activity indicator and modal alert written in Swift using blur effects, translucency, flat and bold design :large_orange_diamond:
* [SnapTimer ★254 ⏳1Y](https://github.com/andresinaka/SnapTimer) - Implementation of Snapchat's stories timer. :large_orange_diamond:
* [AudioIndicatorBars ★166](https://github.com/LeonardoCardoso/AudioIndicatorBars) - AIB indicates for your app users which audio is playing. Just like the Podcasts app. :large_orange_diamond:
* [LLSpinner ★11 ⏳1Y](https://github.com/alaphao/LLSpinner) - An easy way to create a full screen activity indicator. :large_orange_diamond:
* [SVUploader ★30](https://github.com/kirankunigiri/SVUploader) - A beautiful uploader progress view that makes things simple and easy.  :large_orange_diamond:
* [YLProgressBar ★1050](https://github.com/yannickl/YLProgressBar) - UIProgressView replacement with an highly and fully customizable animated progress bar in pure Core Graphics.
* [FlexibleSteppedProgressBar ★116](https://github.com/amratab/FlexibleSteppedProgressBar) - A beautiful easily customisable stepped progress bar.  :large_orange_diamond:
* [GradientLoadingBar ★48](https://github.com/fxm90/GradientLoadingBar) - An animated gradient loading bar. :large_orange_diamond:
* [DSGradientProgressView ★247](https://github.com/DholStudio/DSGradientProgressView) - A simple and customizable animated progress bar written in Swift. :large_orange_diamond:
* [GradientProgressBar ★22](https://github.com/fxm90/GradientProgressBar) - A gradient progress bar (UIProgressView). :large_orange_diamond:
* [BPCircleActivityIndicator ★35](https://github.com/ppth0608/BPCircleActivityIndicator) - A lightweight and awesome Loading Activity Indicator for your iOS app. :large_orange_diamond:
* [DottedProgressBar ★18](https://github.com/nikola9core/DottedProgressBar) - Simple and customizable animated progress bar with dots for iOS. :large_orange_diamond:
* [RSLoadingView ★235](https://github.com/roytornado/RSLoadingView) - Awesome loading animations using 3D engine written with Swift. :large_orange_diamond:
* [SendIndicator ★33](https://github.com/LeonardoCardoso/SendIndicator) - Yet another task indicator :large_orange_diamond:
* [StepProgressView ★53](https://github.com/yonat/StepProgressView) - Step-by-step progress view with labels and shapes. A good replacement for UIActivityIndicatorView and UIProgressView. :large_orange_diamond:
* [BPBlockActivityIndicator ★24](https://github.com/ppth0608/BPBlockActivityIndicator) - A simple and awesome Loading Activity Indicator(with funny block animation) for your iOS app. :large_orange_diamond:
* [JustHUD ★13](https://github.com/shubh10/JustHUD) - JustHUD is an iOS drop-in class written in Swift that displays a translucent HUD. :large_orange_diamond:
* [JDBreaksLoading ★123](https://github.com/jamesdouble/JDBreaksLoading) - You can easily start up a little breaking game indicator by one line. :large_orange_diamond:
* [SkeletonView ★617](https://github.com/Juanpe/SkeletonView) - An elegant way to show users that something is happening and also prepare them to which contents he is waiting. :large_orange_diamond:
* [Windless ★162](https://github.com/Interactive-Studio/Windless) - Windless makes it easy to implement invisible layout loading view. :large_orange_diamond:
* [Skeleton ★297](https://github.com/gonzalonunez/Skeleton) - An easy way to create sliding CAGradientLayer animations! Works great for creating skeleton screens for loading content. 🔶
+* [StatusBarOverlay ★24](https://github.com/IdleHandsApps/StatusBarOverlay) - Automatically show/hide a "No Internet Connection" bar when your app loses/gains connection. It supports apps which hide the status bar and "The Notch" 🔶

#### Animation
* [Pop ★18321](https://github.com/facebook/pop) - An extensible iOS and macOS animation library, useful for physics-based interactions.
* [AnimationEngine ★1031 ⏳2Y](https://github.com/intuit/AnimationEngine) - Easily build advanced custom animations on iOS.
* [Awesome-iOS-Animation ★840](https://github.com/jackymelb/awesome-ios-animation) - Collection of Animation projects
* [RZTransitions ★1746](https://github.com/Raizlabs/RZTransitions) - A library of custom iOS View Controller Animations and Interactions.
* [DCAnimationKit ★728 ⏳1Y](https://github.com/daltoniam/DCAnimationKit) - A collection of animations for iOS. Simple, just add water animations.
* [Spring ★11551](https://github.com/MengTo/Spring) - A library to simplify iOS animations in Swift. :large_orange_diamond:
* [Canvas ★5240 ⏳2Y](https://github.com/CanvasPod/Canvas) - Animate in Xcode without code http://canvaspod.io
* [Fluent ★306](https://github.com/matthewcheok/Fluent) - Swift animation made easy :large_orange_diamond:
* [Cheetah ★562 ⏳1Y](https://github.com/suguru/Cheetah) - Easy animation library on iOS with Swift2. :large_orange_diamond:
* [RadialLayer ★52 ⏳2Y](https://github.com/soheil/RadialLayer) - Animation for clickable elements (similar to Youtube Music). :large_orange_diamond:
* [Pop By Example ★178 ⏳2Y](https://github.com/hossamghareeb/Facebook-POP-Tutorial) - A project tutorial in how to use Pop animation framework by example.
* [AppAnimations](http://www.appanimations.com) - Collection of iOS animations to inspire your next project
* [EasyAnimation ★2494](https://github.com/icanzilb/EasyAnimation) - A Swift library to take the power of UIView.animateWithDuration() to a whole new level - layers, springs, chain-able animations, and mixing view/layer animations together. :large_orange_diamond:
* [Animo ★186](https://github.com/eure/Animo) - SpriteKit-like animation builders for CALayers. :large_orange_diamond:
* [CurryFire ★85](https://github.com/devinross/curry-fire) - A framework for creating unique animations.
* [IBAnimatable ★6799](https://github.com/IBAnimatable/IBAnimatable) - Design and prototype UI, interaction, navigation, transition and animation for App Store ready Apps in Interface Builder with IBAnimatable. :large_orange_diamond:
* [CKWaveCollectionViewTransition ★1588 ⏳1Y](https://github.com/CezaryKopacz/CKWaveCollectionViewTransition) - Cool wave like transition between two or more UICollectionView :large_orange_diamond:
* [DaisyChain ★26](https://github.com/alikaragoz/DaisyChain) - :link: Easy animation chaining :large_orange_diamond:
* [SYBlinkAnimationKit ★101](https://github.com/shoheiyokoyama/SYBlinkAnimationKit) - A blink effect animation framework for iOS, written in Swift. :large_orange_diamond:
* [PulsingHalo ★1610](https://github.com/shu223/PulsingHalo) - iOS Component for creating a pulsing animation.
* [DKChainableAnimationKit ★1799](https://github.com/Draveness/DKChainableAnimationKit) - Chainable animations in Swift :large_orange_diamond:
* [JDAnimationKit ★547](https://github.com/JellyDevelopment/JDAnimationKit) - Animate easy and with less code with Swift :large_orange_diamond:
* [Advance ★4038](https://github.com/storehouse/Advance) - A powerful animation framework for iOS. :large_orange_diamond:
* [UIView-Shake ★471](https://github.com/andreamazz/UIView-Shake) - UIView category that adds shake animation
* [Walker ★139](https://github.com/RamonGilabert/Walker) - A new animation engine for your app. :large_orange_diamond:
* [Morgan ★95 ⏳1Y](https://github.com/RamonGilabert/Morgan) - An animation set for your app. :large_orange_diamond:
* [MagicMove ★11 ⏳1Y](https://github.com/patrickreynolds/MagicMove) - Keynote-style Magic Move transition animations :large_orange_diamond:
* [Shimmer ★8216](https://github.com/facebook/Shimmer) - An easy way to add a simple, shimmering effect to any view in an iOS app.
* [SAConfettiView ★1040](https://github.com/sudeepag/SAConfettiView) - Confetti! Who doesn't like confetti? :large_orange_diamond:
* [CCMRadarView ★182](https://github.com/cacmartinez/CCMRadarView) - CCMRadarView uses the IBDesignable tools to make an easy customizable radar view with animation :large_orange_diamond:
* [Pulsator ★807](https://github.com/shu223/Pulsator) - Pulse animation for iOS :large_orange_diamond:
* [Interpolate ★1530](https://github.com/marmelroy/Interpolate) - Swift interpolation for gesture-driven animations :large_orange_diamond:
* [ADPuzzleAnimation ★111 ⏳1Y](https://github.com/Antondomashnev/ADPuzzleAnimation) - Custom animation for UIView inspired by Fabric - Answers animation. :large_orange_diamond:
* [Wave ★69](https://github.com/onmyway133/Wave) - :ocean: Declarative chainable animations in Swift :large_orange_diamond:
* [Stellar ★2472](https://github.com/AugustRush/Stellar) - A fantastic Physical animation library for swift :large_orange_diamond:
* [MotionMachine ★334](https://github.com/poetmountain/MotionMachine) - A powerful, elegant, and modular animation library for Swift. :large_orange_diamond:
* [JRMFloatingAnimation ★170](https://github.com/carleihar/JRMFloatingAnimation) - An Objective-C animation library used to create floating image views.
* [AHKBendableView ★593 ⏳1Y](https://github.com/fastred/AHKBendableView) - UIView subclass that bends its edges when its position changes. :large_orange_diamond:
* [FlightAnimator ★559](https://github.com/AntonTheDev/FlightAnimator) - Advanced Natural Motion Animations, Simple Blocks Based Syntax :large_orange_diamond:
* [ZoomTransitioning ★545](https://github.com/WorldDownTown/ZoomTransitioning) - A custom transition with image zooming animation. :large_orange_diamond:
* [Ubergang ★46](https://github.com/RobinFalko/Ubergang) - A tweening engine for iOS written in Swift. :large_orange_diamond:
* [JHChainableAnimations ★3008](https://github.com/jhurray/JHChainableAnimations) - Easy to read and write chainable animations in Objective-C
* [Popsicle ★1130](https://github.com/DavdRoman/Popsicle) - Delightful, extensible Swift value interpolation framework :large_orange_diamond:
* [WXWaveView ★294](https://github.com/WelkinXie/WXWaveView) - Add a pretty water wave to your view.
* [Twinkle ★442](https://github.com/piemonte/Twinkle) - :sparkles: Swift and easy way to make elements in your iOS and tvOS app twinkle :large_orange_diamond:
* [MotionBlur ★1489 ⏳2Y](https://github.com/fastred/MotionBlur) - MotionBlur allows you to add motion blur effect to iOS animations.
* [RippleEffectView ★295](https://github.com/alsedi/RippleEffectView) - RippleEffectView - A Neat Rippling View Effect :large_orange_diamond:
* [Keyframes ★4704](https://github.com/facebookincubator/Keyframes) - A library for converting Adobe AE shape based animations to a data format and play it back on Android and iOS devices.
* [SwiftyAnimate ★147](https://github.com/rchatham/SwiftyAnimate) - Composable animations in Swift. :large_orange_diamond:
* [SamuraiTransition ★202](https://github.com/hachinobu/SamuraiTransition) - Swift based library providing a collection of ViewController transitions featuring a number of neat “cutting” animations. :large_orange_diamond:
* [Lottie ★11366](https://github.com/airbnb/lottie-ios) - An iOS library for a real time rendering of native vector animations from Adobe After Effects.
* [Overlap ★120](https://github.com/ML-Works/Overlap) - Tiny iOS library to achieve overlap visual effect. :large_orange_diamond:
* [anim ★45](https://github.com/onurersel/anim) - An animation library for iOS with custom easings and easy to follow API. :large_orange_diamond:
* [AnimatedCollectionViewLayout ★2811](https://github.com/KelvinJin/AnimatedCollectionViewLayout) - A UICollectionViewLayout subclass that adds custom transitions/animations to the UICollectionView. :large_orange_diamond:
* [Dance ★612](https://github.com/saoudrizwan/Dance) - A radical & elegant animation library built for iOS. :large_orange_diamond:
* [AKVideoImageView ★111](https://github.com/numen31337/AKVideoImageView) - UIImageView subclass which allows you to display a looped video as a background.
* [Spruce iOS Animation Library ★2159](https://github.com/willowtreeapps/spruce-ios) - Swift library for choreographing animations on the screen.:large_orange_diamond:
* [CircularRevealKit ★9](https://github.com/T-Pro/CircularRevealKit) - UI framework that implements the material design's reveal effect. 🔶
* [TweenKit ★607](https://github.com/SteveBarnegren/TweenKit) - Animation library for iOS in Swift. 🔶
* [Water ★321](https://github.com/KrisYu/Water) - Simple calculation to render cheap water effects. 🔶
* [CRRefresh ★383](https://github.com/CRAnimation/CRRefresh) - An easy way to use pull-to-refresh. 🔶
* [Pastel ★2315](https://github.com/cruisediary/Pastel) - Gradient animation effect like Instagram. 🔶
* [YapAnimator ★1725](https://github.com/yapstudios/YapAnimator) - Your fast and friendly physics-based animation system. :large_orange_diamond:
* [Bubble ★182](https://github.com/goldmoment/Bubble) - Fruit Animation :large_orange_diamond:
* [Gemini ★2017](https://github.com/shoheiyokoyama/Gemini) - Gemini is rich scroll based animation framework for iOS, written in Swift :large_orange_diamond:
* [WaterDrops ★207](https://github.com/LeFal/WaterDrops) - Simple water drops animation for iOS in Swift :large_orange_diamond:
* [ViewAnimator ★2506](https://github.com/marcosgriselli/ViewAnimator) - ViewAnimator brings your UI to life with just one line. 🔶

##### Transition
* [BlurryModalSegue ★923 ⏳1Y](https://github.com/Citrrus/BlurryModalSegue) - A custom modal segue for providing a blurred overlay effect.
* [DAExpandAnimation ★529](https://github.com/ifitdoesntwork/DAExpandAnimation) - A custom modal transition that presents a controller with an expanding effect while sliding out the presenter remnants. :large_orange_diamond:
* [BubbleTransition ★2588](https://github.com/andreamazz/BubbleTransition) - A custom modal transition that presents and dismiss a controller with an expanding bubble effect. :large_orange_diamond:
* [RPModalGestureTransition ★86 ⏳1Y](https://github.com/naoyashiga/RPModalGestureTransition) - You can dismiss modal by using gesture :point_up_2: :iphone: :large_orange_diamond:
* [RMPZoomTransitionAnimator ★1567](https://github.com/recruit-mp/RMPZoomTransitionAnimator) - A custom zooming transition animation for UIViewController
* [ElasticTransition ★1803](https://github.com/lkzhao/ElasticTransition) - A UIKit custom transition that simulates an elastic drag. Written in Swift. :large_orange_diamond:
* [ElasticTransition-ObjC ★362 ⏳1Y](https://github.com/taglia3/ElasticTransition-ObjC) - A UIKit custom transition that simulates an elastic drag.This is the Objective-C Version of Elastic Transition written in Swift by lkzhao
* [ZFDragableModalTransition ★2312](https://github.com/zoonooz/ZFDragableModalTransition) - Custom animation transition for present modal view controller
* [ImageOpenTransition ★791](https://github.com/mcmatan/ImageOpenTransition) - Beautiful and precise transitions between ViewControllers images written in Swift. :large_orange_diamond:
* [ZOZolaZoomTransition ★877 ⏳1Y](https://github.com/NewAmsterdamLabs/ZOZolaZoomTransition) - Zoom transition that animates the entire view heirarchy. Used extensively in the Zola iOS application.
* [JTMaterialTransition ★889 ⏳1Y](https://github.com/jonathantribouharet/JTMaterialTransition) - An iOS transition for controllers based on material design.
* [AnimatedTransitionGallery ★2243](https://github.com/shu223/AnimatedTransitionGallery) - Collection of iOS 7 custom animated transitions using UIViewControllerAnimatedTransitioning protocol.
* [TransitionTreasury ★1922](https://github.com/DianQK/TransitionTreasury) - Easier way to push your viewController. :large_orange_diamond:
* [Presenter ★9 ⏳1Y](https://github.com/muukii/Presenter) - Screen transition with safe and clean code.  :large_orange_diamond:
* [Kaeru ★416](https://github.com/bannzai/Kaeru) - Switch viewcontroller like iOS task manager :large_orange_diamond:
* [View2ViewTransition ★776](https://github.com/naru-jpn/View2ViewTransition) - Custom interactive view controller transition from one view to another view. :large_orange_diamond:
* [AZTransitions ★364](https://github.com/azimin/AZTransitions) - API to make great custom transitions in one method. :large_orange_diamond:
* [Hero ★11251](https://github.com/lkzhao/Hero) - Supercharged transition engine for iOS. Build your custom view transitions with no code at all. Inspired by Keynote's Magic Move. :large_orange_diamond:
* [Motion ★722](https://github.com/CosmicMind/Motion) - Seamless animations and transitions in Swift. :large_orange_diamond:
* [PresenterKit ★408](https://github.com/jessesquires/PresenterKit) - Swifty view controller presentation for iOS :large_orange_diamond:
* [Transition ★1781](https://github.com/Touchwonders/Transition) - Easy interactive interruptible custom ViewController transitions. :large_orange_diamond:
* [Gagat ★723](https://github.com/Boerworz/Gagat) - A delightful way to transition between visual styles in your iOS applications. :large_orange_diamond:
* [DeckTransition ★1599](https://github.com/HarshilShah/DeckTransition) - A library to recreate the iOS Apple Music now playing transition :large_orange_diamond:
* [TransitionableTab ★216](https://github.com/Interactive-Studio/TransitionableTab) - TransitionableTab makes it easy to animate when switching between tab :large_orange_diamond:

#### Alert & Action Sheet

* [SweetAlert ★1769](https://github.com/codestergit/SweetAlert-iOS) - Live animated Alert View for iOS written in Swift. :large_orange_diamond:
* [NYAlertViewController ★514](https://github.com/nealyoung/NYAlertViewController) - Highly configurable iOS Alert Views with custom content views.
* [SCLAlertView-Swift ★4084](https://github.com/vikmeup/SCLAlertView-Swift) - Beautiful animated Alert View, written in Swift. :large_orange_diamond:
* [TTGSnackbar ★347](https://github.com/zekunyan/TTGSnackbar) - Show simple message and action button on the bottom of the screen with multi kinds of animation. :large_orange_diamond:
* [Swift-Prompts ★714](https://github.com/GabrielAlva/Swift-Prompts) - A Swift library to design custom prompts with a great scope of options to choose from. :large_orange_diamond:
* [BRYXBanner ★849](https://github.com/bryx-inc/BRYXBanner) - A lightweight dropdown notification for iOS 7+, in Swift. :large_orange_diamond:
* [LNRSimpleNotifications ★169](https://github.com/LISNR/LNRSimpleNotifications) - Simple Swift in-app notifications. LNRSimpleNotifications is a simplified Swift port of TSMessages :large_orange_diamond:
* [HDNotificationView ★245 ⏳1Y](https://github.com/nhdang103/HDNotificationView) - Emulates the native Notification Banner UI for any alert.
* [JDStatusBarNotification ★3329](https://github.com/calimarkus/JDStatusBarNotification) - Easy, customizable notifications displayed on top of the statusbar.
* [Notie ★79](https://github.com/thii/Notie) - In-app notification in Swift, with customizable buttons and input text field. :large_orange_diamond:
* [EZAlertController ★280](https://github.com/thellimist/EZAlertController) - Easy Swift UIAlertController :large_orange_diamond:
* [GSMessages ★262](https://github.com/wxxsw/GSMessages) - A simple style messages/notifications for iOS 7+. :large_orange_diamond:
* [OEANotification ★18](https://github.com/OEA/OEANotification) - In-app customizable notification views on top of screen for iOS which is written in Swift 2.1. :large_orange_diamond:
* [RKDropdownAlert ★1433](https://github.com/cwRichardKim/RKDropdownAlert) - Extremely simple UIAlertView alternative.
* [TKSwarmAlert ★461](https://github.com/entotsu/TKSwarmAlert) - Animated alert library like Swarm app. :large_orange_diamond:
* [Whisper ★3134](https://github.com/hyperoslo/Whisper) - Whisper is a component that will make the task of display messages and in-app notifications simple. It has three different views inside :large_orange_diamond:
* [SimpleAlert ★292](https://github.com/KyoheiG3/SimpleAlert) - Customizable simple Alert and simple ActionSheet for Swift :large_orange_diamond:
* [Hokusai ★378](https://github.com/ytakzk/Hokusai) - A Swift library to provide a bouncy action sheet :large_orange_diamond:
* [SwiftNotice ★607](https://github.com/johnlui/SwiftNotice) - SwiftNotice is a GUI library for displaying various popups (HUD) written in pure Swift, fits any scrollview. :large_orange_diamond:
* [SwiftOverlays ★491](https://github.com/peterprokop/SwiftOverlays) - SwiftOverlays is a Swift GUI library for displaying various popups and notifications :large_orange_diamond:
* [SwiftyDrop ★554](https://github.com/morizotter/SwiftyDrop) - SwiftyDrop is a lightweight pure Swift simple and beautiful dropdown message. :large_orange_diamond:
* [LKAlertController ★61](https://github.com/Lightningkite/LKAlertController) - An easy to use UIAlertController builder for swift. :large_orange_diamond:
* [DOAlertController ★332](https://github.com/okmr-d/DOAlertController) - Simple Alert View written in Swift, which can be used as a UIAlertController. (AlertController/AlertView/ActionSheet) :large_orange_diamond:
* [CustomizableActionSheet ★128](https://github.com/beryu/CustomizableActionSheet) - Action sheet allows including your custom views and buttons. :large_orange_diamond:
* [Toast-Swift ★896](https://github.com/scalessec/Toast-Swift) - A Swift extension that adds toast notifications to the UIView object class. :large_orange_diamond:
* [PMAlertController ★1674](https://github.com/Codeido/PMAlertController) - PMAlertController is a great and customizable substitute to UIAlertController. 🔶
* [PopupViewController ★15 ⏳1Y](https://github.com/dimillian/PopupViewController) - UIAlertController drop in replacement with much more customization. 🔶
* [AlertViewLoveNotification ★25](https://github.com/PhilippeBoisney/AlertViewLoveNotification) - A simple and attractive AlertView to ask permission to your users for Push Notification. 🔶
* [CRToast ★3968](https://github.com/cruffenach/CRToast) - A modern iOS toast view that can fit your notification needs
* [JLToast ★873](https://github.com/devxoul/Toaster) - Toast for iOS with very simple interface. :large_orange_diamond:
* [CuckooAlert ★5 ⏳1Y](https://github.com/rollmind/CuckooAlert) - Multiple use of presentViewController for UIAlertController. 🔶
* [KRAlertController ★34](https://github.com/krimpedance/KRAlertController) - A colored alert view for your iOS. :large_orange_diamond:
* [Dodo ★774](https://github.com/evgenyneu/Dodo) - A message bar for iOS written in Swift. :large_orange_diamond:
* [MaterialActionSheetController ★84 ⏳1Y](https://github.com/ntnhon/MaterialActionSheetController) - A Google like action sheet for iOS written in Swift. :large_orange_diamond:
* [SwiftMessages ★2639](https://github.com/SwiftKickMobile/SwiftMessages) - A very flexible message bar for iOS written in Swift. :large_orange_diamond:
* [FCAlertView ★75 ⏳1Y](https://github.com/krispenney/FCAlertView) - A Flat Customizable AlertView for iOS. (Swift) :large_orange_diamond:
* [FCAlertView ★650](https://github.com/nimati/FCAlertView) - A Flat Customizable AlertView for iOS. (Objective-C)
* [CDAlertView ★742](https://github.com/candostdagdeviren/CDAlertView) - Highly customizable alert/notification/success/error/alarm popup 🔶
* [RMActionController ★363](https://github.com/CooperRS/RMActionController) - Present any UIView in an UIAlertController like manner.
* [RMDateSelectionViewController ★1028](https://github.com/CooperRS/RMDateSelectionViewController) - Select a date using UIDatePicker in a UIAlertController like fashion.
* [RMPickerViewController ★333](https://github.com/CooperRS/RMPickerViewController) - Select something using UIPickerView in a UIAlertController like fashion.
* [Hedwig ★17 ⏳1Y](https://github.com/dereklimbus/hedwig) - Interactive notification :large_orange_diamond:
* [Jelly ★1426](https://github.com/SebastianBoldt/Jelly) - Jelly provides custom view controller transitions with just a few lines of code. :large_orange_diamond:
* [Malert ★161](https://github.com/vitormesquita/Malert) - Malert is a simple, easy and custom iOS UIAlertView written in Swift 🔶
* [RAlertView ★43 ⏳1Y](https://github.com/roycms/AlertView) - AlertView, iOS popup window, A pop-up framework, Can be simple and convenient to join your project.
* [NoticeBar ★226](https://github.com/qiuncheng/NoticeBar) - 😍A simple NoticeBar written by Swift 3, similar with QQ notice view. :large_orange_diamond:
* [LIHAlert ★23](https://github.com/Lasithih/LIHAlert) - Advance animated banner alerts for iOS :large_orange_diamond:
* [BPStatusBarAlert ★68](https://github.com/ppth0608/BPStatusBarAlert) - A simple alerts that appear on the status bar and below navigation bar(like Facebook).🔶
* [CFAlertViewController ★809](https://github.com/Codigami/CFAlertViewController) -  A library that helps you display and customise alerts and action sheets on iPad and iPhone.🔶
* [NotificationBanner ★1467](https://github.com/Daltron/NotificationBanner) - The easiest way to display highly customizable in app notification banners in iOS. 🔶
* [Alertift ★69](https://github.com/sgr-ksmt/Alertift) - Swifty, modern UIAlertController wrapper. :large_orange_diamond:
* [PCLBlurEffectAlert ★126](https://github.com/hryk224/PCLBlurEffectAlert) - Swift AlertController with UIVisualEffectView. :large_orange_diamond:
* [JDropDownAlert ★35](https://github.com/trilliwon/JDropDownAlert) - Multi dirction dropdown alert view. 🔶
* [BulletinBoard ★2139](https://github.com/alexaubry/BulletinBoard) - Generate and Display Bottom Card Interfaces on iOS :large_orange_diamond:
* [Cards ★2014](https://github.com/PaoloCuscela/Cards) - Awesome iOS 11 AppStore's Card Views. :large_orange_diamond:
* [CFNotify ★372](https://github.com/hallelujahbaby/CFNotify) - A customizable framework to create draggable views. :large_orange_diamond:

#### Badge
* [MIBadgeButton ★292](https://github.com/mustafaibrahim989/MIBadgeButton-Swift) - Notification badge for UIButtons. :large_orange_diamond:
* [EasyNotificationBadge ★32](https://github.com/Minitour/EasyNotificationBadge) - UIView extension that adds a notification badge. :large_orange_diamond:[e]
* [Sheriff ★235](https://github.com/gemr/Sheriff) - Add badges to anything.
* [swift-badge ★232](https://github.com/evgenyneu/swift-badge) - Badge view for iOS written in swift :large_orange_diamond:

#### Button
* [SSBouncyButton ★297 ⏳1Y](https://github.com/StyleShare/SSBouncyButton) - iOS7-style bouncy button UI component.
* [DOFavoriteButton ★2920](https://github.com/okmr-d/DOFavoriteButton) - Cute Animated Button written in Swift. :large_orange_diamond:
* [SDevCircleButton ★24](https://github.com/0x73/SDevCircleButton) - Flat circle button :large_orange_diamond:
* [VBFPopFlatButton ★2872](https://github.com/victorBaro/VBFPopFlatButton) - Flat button with 9 different states animated using Facebook POP.
* [HTPressableButton ★826 ⏳1Y](https://github.com/Famolus/HTPressableButton) - Flat design pressable button.
* [LiquidFloatingActionButton ★3152](https://github.com/yoavlt/LiquidFloatingActionButton) - Material Design Floating Action Button in liquid state :large_orange_diamond:
* [JTFadingInfoView ★126 ⏳2Y](https://github.com/JunichiT/JTFadingInfoView) - An UIButton-based view with fade in/out animation features.
* [Floaty ★581](https://github.com/kciter/Floaty) - :heart: Floating Action Button for iOS :large_orange_diamond:
* [TVButton ★946](https://github.com/marmelroy/TVButton) - Recreating the cool parallax icons from Apple TV as iOS UIButtons (in Swift). :large_orange_diamond:
* [SwiftyButton ★254](https://github.com/TakeScoop/SwiftyButton) - Simple and customizable button in Swift :large_orange_diamond:
* [AnimatablePlayButton ★70](https://github.com/suzuki-0000/AnimatablePlayButton) - Animated Play and Pause Button using CALayer, CAKeyframeAnimation. :large_orange_diamond:
* [gbkui-button-progress-view ★514 ⏳1Y](https://github.com/Guidebook/gbkui-button-progress-view) - Inspired by Apple’s download progress buttons in the App Store.
* [ZFRippleButton ★1291](https://github.com/zoonooz/ZFRippleButton) - Custom UIButton effect inspired by Google Material Design :large_orange_diamond:
* [JOEmojiableBtn ★227](https://github.com/lojals/JOEmojiableBtn) - Emoji selector like Facebook Reactions.
* [EMEmojiableBtn ★70 ⏳1Y](https://github.com/Eke/EMEmojiableBtn) - Option selector that works similar to Reactions by fb. Objective-c version.
* [WYMaterialButton ★59](https://github.com/Yu-w/WYMaterialButton) - Interactive and fully animated Material Design button for iOS developers.
* [DynamicButton ★870](https://github.com/yannickl/DynamicButton) - Yet another animated flat buttons in Swift :large_orange_diamond:
* [OnOffButton ★415](https://github.com/rakaramos/OnOffButton) - Custom On/Off Animated UIButton, written in Swift. By Creativedash :large_orange_diamond:
* [CRNetworkButton ★609 ⏳1Y](https://github.com/Cleveroad/CRNetworkButton) - Send Button for iOS :large_orange_diamond:
* [WCLShineButton ★970](https://github.com/imwcl/WCLShineButton) - This is a UI lib for iOS. Effects like shining. :large_orange_diamond:
* [EasySocialButton ★128](https://github.com/Minitour/EasySocialButton) - An easy way to create beautiful social authentication buttons. :large_orange_diamond:
* [NFDownloadButton ★270](https://github.com/LeonardoCardoso/NFDownloadButton) - Revamped Download Button. 🔶
* [LGButton ★1498](https://github.com/loregr/LGButton) - A fully customisable subclass of the native UIControl which allows you to create beautiful buttons without writing any line of code. :large_orange_diamond:
* [MultiToggleButton ★27](https://github.com/yonat/MultiToggleButton) - A UIButton subclass that implements tap-to-toggle button text (Like the camera flash and timer buttons). :large_orange_diamond:
* [PMSuperButton ★378](https://github.com/Codeido/PMSuperButton) - A powerful UIButton with super powers, customizable from Storyboard! 🔶
* [JSButton ★0](https://github.com/imjog/JSButton) - A fully customisable swift subclass on UIButton which allows you to create beautiful buttons without writing any line of code. 🔶
* [TransitionButton ★348](https://github.com/AladinWay/TransitionButton) - UIButton sublass for loading and transition animation :large_orange_diamond:
* [ButtonProgressBar-iOS ★238](https://github.com/thePsguy/ButtonProgressBar-iOS) - A small and flexible UIButton subclass with animated loading progress, and completion animation. :large_orange_diamond:
* [SpicyButton ★1](https://github.com/lukecrum/SpicyButton) - Full-featured IBDesignable UIButton class 🔶
* [DesignableButton ★50](https://github.com/IdleHandsApps/DesignableButton) - UIButton subclass with centralised and reusable styles. View styles and customise in InterfaceBuilder in real time! 🔶

#### Calendar
* [CVCalendar ★2775](https://github.com/CVCalendar/CVCalendar) - A custom visual calendar for iOS 8+ written in Swift (2.0). :large_orange_diamond:
* [RSDayFlow ★757](https://github.com/ruslanskorb/RSDayFlow) - iOS 7+ Calendar with Infinite Scrolling.
* [NWCalendarView ★53 ⏳1Y](https://github.com/nbwar/NWCalendarView) - An availability calendar implementation for iOS :large_orange_diamond:
* [FSCalendar ★5492](https://github.com/WenchaoD/FSCalendar) - A superiorly awesome iOS7+ calendar control, compatible with both Objective-C and Swift2.
* [GLCalendarView ★813](https://github.com/Glow-Inc/GLCalendarView) - A fully customizable calendar view acting as a date range picker
* [JTCalendar ★2435](https://github.com/jonathantribouharet/JTCalendar) - A customizable calendar view for iOS.
* [JTAppleCalendar ★3936](https://github.com/patchthecode/JTAppleCalendar) - The Unofficial Swift Apple Calendar Library. View. Control. for iOS & tvOS :large_orange_diamond:
* [Daysquare ★610](https://github.com/unixzii/Daysquare) - An elegant calendar control for iOS.
* [ASCalendar ★188 ⏳1Y](https://github.com/scamps88/ASCalendar) - A calendar control for iOS written in swift with mvvm pattern :large_orange_diamond:
* [Calendar ★528](https://github.com/jumartin/Calendar) - A set of views and controllers for displaying and scheduling events on iOS
* [Koyomi ★494](https://github.com/shoheiyokoyama/Koyomi) - Simple customizable calendar component in Swift :large_orange_diamond:
* [DateTimePicker ★1271](https://github.com/itsmeichigo/DateTimePicker) - A nicer iOS UI component for picking date and time :large_orange_diamond:
* [RCalendarPicker ★55](https://github.com/roycms/RCalendarPicker) - RCalendarPicker A date picker control.
* [CalendarKit ★784](https://github.com/richardtop/CalendarKit) - Fully customizable calendar day view. :large_orange_diamond:
* [GDPersianCalendar ★4](https://github.com/saeid/GDPersianCalendar) - Customizable and easy to use Persian Calendar component. 🔶
* [MBCalendarKit ★543](https://github.com/MosheBerman/MBCalendarKit) - A calendar framework for iOS built with customization, and localization in mind.
* [PTEventView ★23](https://github.com/amantaneja/PTEventView) - An Event View based on Apple's Event Detail View within Calender.Supports ARC, Autolayout and editing via StoryBoard. 🔶
* [KDCalendarView ★98](https://github.com/mmick66/CalendarView) - A calendar component for iOS written in Swift 4.0. It features both vertical and horizontal layout (and scrolling) and the display of native calendar events.

#### Form & Settings
* [Form ★1594](https://github.com/hyperoslo/Form) - The most flexible and powerful way to build a form on iOS
* [XLForm ★4743](https://github.com/xmartlabs/XLForm) - XLForm is the most flexible and powerful iOS library to create dynamic table-view forms. Fully compatible with Swift & Obj-C.
* [Eureka ★7224](https://github.com/xmartlabs/Eureka) - Elegant iOS form builder in pure Swift. :large_orange_diamond:
* [YALField ★452](https://github.com/Yalantis/YALField) - Custom Field component with validation for creating easier form-like UI from interface builder.
* [Former ★939](https://github.com/ra1028/Former) - Former is a fully customizable Swift2 library for easy creating UITableView based form. :large_orange_diamond:
* [SwiftForms ★1130](https://github.com/ortuman/SwiftForms) - A small and lightweight library written in Swift that allows you to easily create forms. :large_orange_diamond:
* [APValidators ★115 ⏳1Y](https://github.com/Alterplay/APValidators) - Codeless solution for form validation in iOS!
* [Formalist ★126](https://github.com/seedco/Formalist) - Declarative form building framework for iOS :large_orange_diamond:
* [SwiftyFORM ★715](https://github.com/neoneye/SwiftyFORM) - SwiftyFORM is a form framework for iOS written in Swift :large_orange_diamond:
* [FXForms ★3030](https://github.com/nicklockwood/FXForms) - FXForms is an Objective-C library for easily creating table-based forms on iOS. It is ideal for settings pages, or user data entry tasks.
* [SwiftValidator ★973](https://github.com/SwiftValidatorCommunity/SwiftValidator) - A rule-based validation library for Swift :large_orange_diamond:
* [MZFormSheetPresentationController ★873](https://github.com/m1entus/MZFormSheetPresentationController) - MZFormSheetPresentationController provides an alternative to the native iOS UIModalPresentationFormSheet, adding support for iPhone and additional opportunities to setup controller size and feel form sheet.
* [GenericPasswordRow ★140](https://github.com/EurekaCommunity/GenericPasswordRow) - A row for Eureka to implement password validations. :large_orange_diamond:
* [SuggestionsBox ★98](https://github.com/manuelescrig/SuggestionsBox) - SuggestionsBox helps you build better a product trough your user suggestions. :large_orange_diamond:
* [formvalidator-swift ★457](https://github.com/ustwo/formvalidator-swift) - A framework to validate inputs of text fields and text views in a convenient way. :large_orange_diamond:
* [LightForm ★4](https://github.com/farshidce/LightForm) - A Simple interactive and customizable library to handle form input and validations
* [ValidationToolkit ★7](https://github.com/nsagora/validation-toolkit) - Lightweight framework for input validation written in Swift. :large_orange_diamond:

#### Keyboard
* [RSKKeyboardAnimationObserver ★36 ⏳2Y](https://github.com/ruslanskorb/RSKKeyboardAnimationObserver) - Showing / dismissing keyboard animation in simple UIViewController category.
* [RFKeyboardToolbar ★405](https://github.com/ruddfawcett/RFKeyboardToolbar) - This is a flexible UIView and UIButton subclass to add customized buttons and toolbars to your UITextFields/UITextViews.
* [IQKeyboardManager ★10364](https://github.com/hackiftekhar/IQKeyboardManager) - Codeless drop-in universal library allows to prevent issues of keyboard sliding up and cover UITextField/UITextView.
* [NgKeyboardTracker ★772 ⏳1Y](https://github.com/meiwin/NgKeyboardTracker) - Objective-C library for tracking keyboard in iOS apps.
* [MMNumberKeyboard ★874](https://github.com/matmartinez/MMNumberKeyboard) - A simple keyboard to use with numbers and, optionally, a decimal point.
* [KeyboardObserver ★103](https://github.com/morizotter/KeyboardObserver) - For less complicated keyboard event handling. :large_orange_diamond:
* [TPKeyboardAvoiding ★5410](https://github.com/michaeltyson/TPKeyboardAvoiding) - A drop-in universal solution for moving text fields out of the way of the keyboard in iOS
* [YYKeyboardManager ★381](https://github.com/ibireme/YYKeyboardManager) - iOS utility class allows you to access keyboard view and track keyboard animation.
* [KeyboardMan ★332](https://github.com/nixzhu/KeyboardMan) - KeyboardMan helps you make keyboard animation. :large_orange_diamond:
* [MakemojiSDK ★84 ⏳1Y](https://github.com/makemoji/MakemojiSDK) - Emoji Keyboard SDK (iOS)
* [Typist ★826](https://github.com/totocaster/Typist) - Small, drop-in Swift UIKit keyboard manager for iOS apps-helps manage keyboard's screen presence and behavior without notification center. :large_orange_diamond:
* [KeyboardHideManager ★48](https://github.com/bonyadmitr/KeyboardHideManager) - Codeless manager to hide keyboard by tapping on views for iOS written in Swift :large_orange_diamond:
* [Toolbar ★360](https://github.com/1amageek/Toolbar) - Awesome autolayout Toolbar. :large_orange_diamond:
* [IHKeyboardAvoiding ★1068](https://github.com/IdleHandsApps/IHKeyboardAvoiding) - A drop-in universal solution for keeping any UIView visible when the keyboard is being shown - no more UIScrollViews! 🔶

#### Label
* [LTMorphingLabel ★6002](https://github.com/lexrus/LTMorphingLabel) - Graceful morphing effects for UILabel written in Swift. :large_orange_diamond:
* [ActiveLabel.swift ★2014](https://github.com/optonaut/ActiveLabel.swift) - UILabel drop-in replacement supporting Hashtags (#), Mentions (@) and URLs (http://) written in Swift :large_orange_diamond:
* [MZTimerLabel ★1345](https://github.com/mineschan/MZTimerLabel) - A handy class for iOS to use UILabel as a countdown timer or stopwatch just like in Apple Clock App.
* [CountdownLabel ★334](https://github.com/suzuki-0000/CountdownLabel) - Simple countdown UILabel with morphing animation, and some useful function. :large_orange_diamond:
* [IncrementableLabel ★37](https://github.com/tbaranes/IncrementableLabel) - Incrementable label for iOS, macOS, and tvOS. :large_orange_diamond:
* [TTTAttributedLabel ★7843](https://github.com/TTTAttributedLabel/TTTAttributedLabel) - A drop-in replacement for UILabel that supports attributes, data detectors, links, and more
* [NumberMorphView ★1316](https://github.com/me-abhinav/NumberMorphView) - A label view for displaying numbers which can transition or animate using a technique called number tweening or number morphing. :large_orange_diamond:
* [GlitchLabel ★688](https://github.com/kciter/GlitchLabel) - Glitching UILabel for iOS. :large_orange_diamond:
* [TOMSMorphingLabel ★1846 ⏳2Y](https://github.com/tomknig/TOMSMorphingLabel) - Configurable morphing transitions between text values of a label.
* [THLabel ★547](https://github.com/tobihagemann/THLabel) - UILabel subclass, which additionally allows shadow blur, inner shadow, stroke text and fill gradient.
* [RQShineLabel ★1691 ⏳1Y](https://github.com/zipme/RQShineLabel) - Secret app like text animation
* [ZCAnimatedLabel ★1824 ⏳1Y](https://github.com/overboming/ZCAnimatedLabel) - UILabel replacement with fine-grain appear/disappear animation
* [TriLabelView ★113](https://github.com/mukeshthawani/TriLabelView) - A triangle shaped corner label view for iOS written in Swift. :large_orange_diamond:
* [Preloader.Ophiuchus ★823](https://github.com/Yalantis/Preloader.Ophiuchus) - Custom Label to apply animations on whole text or letters.
* [MTLLinkLabel ★68](https://github.com/recruit-mtl/MTLLinkLabel) - MTLLinkLabel is linkable UILabel. Written in Swift. :large_orange_diamond:
* [UICountingLabel ★1256](https://github.com/dataxpress/UICountingLabel) - Adds animated counting support to UILabel.
* [SlidingText ★37](https://github.com/dnKaratzas/SlidingText) -  Swift UIView for sliding text with page indicator. :large_orange_diamond:
* [NumericAnimatedLabel ★21](https://github.com/javalnanda/NumericAnimatedLabel) -  Swift UIView for showing numeric label with incremental and decremental step animation while changing value. Useful for scenarios like displaying currency. :large_orange_diamond:
* [JSLabel ★1](https://github.com/imjog/JSLabel) -  A simple designable subclass on UILabel with extra IBDesignable and Blinking features. :large_orange_diamond:

#### Login
* [LFLoginController ★88](https://github.com/awesome-labs/LFLoginController) - Customizable login screen, written in Swift. :large_orange_diamond:
* [LoginKit ★422](https://github.com/IcaliaLabs/LoginKit) - LoginKit is a quick and easy way to add a Login/Signup UX to your iOS app.  🔶
* [Cely ★83](https://github.com/chaione/Cely) - Plug-n-Play login framework written in Swift. :large_orange_diamond:

#### Menu
* [ENSwiftSideMenu ★1712](https://github.com/evnaz/ENSwiftSideMenu) - A simple side menu for iOS 7/8 written in Swift. :large_orange_diamond:
* [RESideMenu ★7053](https://github.com/romaonthego/RESideMenu) - iOS 7/8 style side menu with parallax effect inspired by Dribbble shots.
* [SSASideMenu ★584](https://github.com/SSA111/SSASideMenu) - A Swift implementation of RESideMenu. A iOS 7/8 style side menu with parallax effect. :large_orange_diamond:
* [PagingMenuController ★2045](https://github.com/kitasuke/PagingMenuController) - Paging view controller with customizable menu in Swift. :large_orange_diamond:
* [RadialMenu ★282](https://github.com/bradjasper/radialmenu) - RadialMenu is a custom control for providing a touch context menu (like iMessage recording in iOS 8) built with Swift & POP :large_orange_diamond:
* [cariocamenu ★575](https://github.com/arn00s/cariocamenu) - The fastest zero-tap iOS menu. :large_orange_diamond:
* [VLDContextSheet ★169 ⏳2Y](https://github.com/vangelov/VLDContextSheet) - Context menu similar to the one in the Pinterest iOS app
* [GuillotineMenu ★2553](https://github.com/Yalantis/GuillotineMenu) - Our Guillotine Menu Transitioning Animation implemented in Swift reminds a bit of a notorious killing machine. :large_orange_diamond:
* [MediumMenu ★296](https://github.com/pixyzehn/MediumMenu) - A menu based on Medium iOS app. :large_orange_diamond:
* [SwiftySideMenu ★79 ⏳2Y](https://github.com/hossamghareeb/SwiftySideMenu) - SwiftySideMenu is a lightweight and easy to use side menu controller to add left menu and center view controllers with scale animation based on Pop framework.
* [LLSlideMenu ★555](https://github.com/lilei644/LLSlideMenu) - This is a spring slide menu for iOS apps
* [Swift-Slide-Menu ★61 ⏳2Y](https://github.com/PhilippeBoisney/Swift-Slide-Menu) - A Slide Menu, written in Swift, inspired by Slide Menu Material Design. :large_orange_diamond:
* [MenuItemKit ★332](https://github.com/cxa/MenuItemKit) - UIMenuItem with image and block(closure) :large_orange_diamond:
* [BTNavigationDropdownMenu ★2160](https://github.com/PhamBaTho/BTNavigationDropdownMenu) - The elegant dropdown menu, written in Swift, appears underneath navigation bar to display a list of related items when a user click on the navigation title. :large_orange_diamond:
* [ALRadialMenu ★34](https://github.com/AlexLittlejohn/ALRadialMenu) - A radial/circular menu featuring spring animations. Written in swift :large_orange_diamond:
* [AZDropdownMenu ★164](https://github.com/Azuritul/AZDropdownMenu) - An easy to use dropdown menu that supports images. :large_orange_diamond:
* [CircleMenu ★2409](https://github.com/Ramotion/circle-menu) - An animated, multi-option menu button. :large_orange_diamond:
* [SlideMenuControllerSwift ★2791](https://github.com/dekatotoro/SlideMenuControllerSwift) - iOS Slide Menu View based on Google+, iQON, Feedly, Ameba iOS app. It is written in pure Swift. :large_orange_diamond:
* [SideMenu ★1940](https://github.com/jonkykong/SideMenu) - Simple side menu control in Swift inspired by Facebook. Right and Left sides. Lots of customization and animation options. Can be implemented in Storyboard with no code. :large_orange_diamond:
* [CategorySliderView ★358 ⏳1Y](https://github.com/cemolcay/CategorySliderView) - slider view for choosing categories. add any UIView type as category item view. Fully customisable
* [MKDropdownMenu ★330](https://github.com/maxkonovalov/MKDropdownMenu) - A Dropdown Menu for iOS with many customizable parameters to suit any needs.
* [ExpandingMenu ★273](https://github.com/monoqlo/ExpandingMenu) - ExpandingMenu is menu button for iOS written in Swift. :large_orange_diamond:
* [PageMenu ★4397](https://github.com/PageMenu/PageMenu) - A paging menu controller built from other view controllers placed inside a scroll view (like Spotify, Windows Phone, Instagram) :large_orange_diamond:
* [XXXRoundMenuButton ★294](https://github.com/zsy78191/XXXRoundMenuButton) - A simple circle style menu.
* [IGCMenu ★89](https://github.com/sunilsharma08/IGCMenu) - Grid and Circular menu with animation.Easy to customise.
* [EEJSelectMenu ★16 ⏳1Y](https://github.com/eejahromi/EEJSelectMenu) - Single selection menu with cool animations, responsive with all screen sizes.
* [IGLDropDownMenu ★1106 ⏳1Y](https://github.com/bestwnh/IGLDropDownMenu) - An iOS drop down menu with pretty animation and easy to customize.
* [Side-Menu.iOS ★2439](https://github.com/Yalantis/Side-Menu.iOS) - Animated side menu with customizable UI :large_orange_diamond:
* [PopMenu ★815 ⏳1Y](https://github.com/xhzengAIB/PopMenu) - PopMenu is pop animation menu inspired by Sina weibo / NetEase app.
* [FlowingMenu ★753](https://github.com/yannickl/FlowingMenu) - Interactive view transition to display menus with flowing and bouncing effects in Swift :large_orange_diamond:
* [Persei ★2842](https://github.com/Yalantis/Persei) - Animated top menu for UITableView / UICollectionView / UIScrollView written in Swift :large_orange_diamond:
* [DropDown ★980](https://github.com/AssistoLab/DropDown) - A Material Design drop down for iOS :large_orange_diamond:
* [KYGooeyMenu ★1734 ⏳1Y](https://github.com/KittenYang/KYGooeyMenu) - A not bad gooey effects menu.
* [SideMenuController ★926](https://github.com/teodorpatras/SideMenuController) - A side menu controller written in Swift :large_orange_diamond:
* [Context-Menu.iOS ★1784](https://github.com/Yalantis/Context-Menu.iOS) - You can easily add awesome animated context menu to your app.
* [ViewDeck ★5220](https://github.com/ViewDeck/ViewDeck) - An implementation of the sliding functionality found in the Path 2.0 or Facebook iOS apps.
* [FrostedSidebar ★434](https://github.com/edekhayser/FrostedSidebar) - Hamburger Menu using Swift and iOS 8 API's :large_orange_diamond:
* [VHBoomMenuButton ★418](https://github.com/Nightonke/VHBoomMenuButton) - A menu which can ... BOOM!
* [DropDownMenuKit ★137](https://github.com/qmathe/DropDownMenuKit) - A simple, modular and highly customizable UIKit menu, that can be attached to the navigation bar or toolbar, written in Swift. :large_orange_diamond:
* [RevealMenuController ★16 ⏳1Y](https://github.com/anatoliyv/RevealMenuController) - Expandable item groups, custom position and appearance animation. Similar to ActionSheet style. :large_orange_diamond:
* [RHSideButtons ★55](https://github.com/robertherdzik/RHSideButtons) - Library provides easy to implement variation of Android (Material Design) Floating Action Button for iOS. You can use it as your app small side menu. :large_orange_diamond:
* [Swift-CircleMenu ★109](https://github.com/Sufi-Al-Hussaini/Swift-CircleMenu) - Rotating circle menu written in Swift 3. :large_orange_diamond:
* [AKSideMenu ★100](https://github.com/dogo/AKSideMenu) - Beautiful iOS side menu library with parallax effect. :large_orange_diamond:
* [InteractiveSideMenu ★330](https://github.com/handsomecode/InteractiveSideMenu) - Customizable iOS Interactive Side Menu written in Swift 3. :large_orange_diamond:
* [YNDropDownMenu ★791](https://github.com/younatics/YNDropDownMenu) - Adorable iOS drop down menu with Swift3. :large_orange_diamond:
* [KWDrawerController ★56](https://github.com/Kawoou/KWDrawerController) - Drawer view controller that easy to use! :large_orange_diamond:
* [JNDropDownMenu ★46](https://github.com/javalnanda/JNDropDownMenu) - Easy to use tableview style drop down menu with multi-column support written in Swift3. :large_orange_diamond:
* [FanMenu ★215](https://github.com/exyte/fan-menu) - Menu with a circular layout based on Macaw. :large_orange_diamond:
* [AirBar ★137](https://github.com/uptechteam/AirBar) - UIScrollView driven expandable menu written in Swift 3. :large_orange_diamond:
* [FAPanels ★558](https://github.com/fahidattique55/FAPanels) - FAPanels for transition :large_orange_diamond:
* [SwipeMenuViewController ★343](https://github.com/yysskk/SwipeMenuViewController) - Swipable tab and menu View and ViewController. :large_orange_diamond:
* [DTPagerController ★53](https://github.com/tungvoduc/DTPagerController) - A fully customizable container view controller to display set of ViewControllers in horizontal scroller 🔶
* [PagingKit ★475](https://github.com/kazuhiro4949/PagingKit) - PagingKit provides customizable menu UI It has more flexible layout and design than the other libraries.  🔶
* [Dropdowns ★64](https://github.com/hyperoslo/Dropdowns) - 💧 Dropdown in Swift

#### Navigation Bar
* [HidingNavigationBar ★650](https://github.com/tristanhimmelman/HidingNavigationBar) - Easily hide and show a view controller's navigation bar (and tab bar) as a user scrolls :large_orange_diamond:
* [TLYShyNavBar ★3420](https://github.com/telly/TLYShyNavBar) - Unlike all those arrogant UINavigationBar, this one is shy and humble! Easily create auto-scrolling navigation bars!
* [KMNavigationBarTransition ★2262](https://github.com/MoZhouqi/KMNavigationBarTransition) - A drop-in universal library helps you to manage the navigation bar styles and makes transition animations smooth between different navigation bar styles while pushing or popping a view controller for all orientations.
* [LTNavigationBar ★4246](https://github.com/ltebean/LTNavigationBar) - UINavigationBar Category which allows you to change its appearance dynamically
* [BusyNavigationBar ★871](https://github.com/gmertk/BusyNavigationBar) - A UINavigationBar extension to show loading effects :large_orange_diamond:
* [KDInteractiveNavigationController ★117](https://github.com/kingiol/KDInteractiveNavigationController) - A UINavigationController subclass that support pop interactive UINavigationbar with hidden or show. :large_orange_diamond:
* [AMScrollingNavbar ★5034](https://github.com/andreamazz/AMScrollingNavbar) - Scrollable UINavigationBar that follows the scrolling of a UIScrollView :large_orange_diamond:
* [NavKit ★24](https://github.com/wilbertliu/NavKit) - Simple and integrated way to customize navigation bar experience on iOS app. :large_orange_diamond:

#### PickerView
* [ActionSheetPicker-3.0 ★2826](https://github.com/skywinder/ActionSheetPicker-3.0) - Quickly reproduce the dropdown UIPickerView / ActionSheet functionality on iOS.
* [PickerView ★287](https://github.com/filipealva/PickerView) - A customizable alternative to UIPickerView in Swift. :large_orange_diamond:
* [DatePickerDialog ★307](https://github.com/squimer/DatePickerDialog-iOS-Swift) - Date picker dialog for iOS :large_orange_diamond:
* [CZPicker ★482 ⏳1Y](https://github.com/chenzeyu/CZPicker) - A picker view shown as a popup for iOS.
* [AIDatePickerController ★84](https://github.com/alikaragoz/AIDatePickerController) - :date: UIDatePicker modally presented with iOS 7 custom transitions.
* [CountryPicker ★62](https://github.com/4taras4/CountryCode) - :date: UIPickerView with Country names flags and phoneCodes 🔶
* [McPicker ★42](https://github.com/kmcgill88/McPicker-iOS) - A customizable, closure driven UIPickerView drop-in solution with animations that is rotation ready. :large_orange_diamond:
* [Mandoline ★480](https://github.com/blueapron/Mandoline) - An iOS picker view to serve all your "picking" needs :large_orange_diamond:

#### Popup
* [PopupKit](https://github.com/rynecheow/PopupKit) - A simple and flexible class for presenting custom views as a popup in iOS and tvOS, maintained from [KLCPopup ★1664](https://github.com/jmascia/KLCPopup).
* [MMPopupView ★1783](https://github.com/adad184/MMPopupView) - Pop-up based view(e.g. alert sheet), can easily customize.
* [STPopup ★2035](https://github.com/kevin0571/STPopup) - STPopup provides a UINavigationController in popup style, for both iPhone and iPad.
* [NMPopUpView ★170](https://github.com/psy2k/NMPopUpView) - Simple iOS class for showing nice popup windows. Swift and Objective-C versions available. :large_orange_diamond:
* [CNPPopupController ★1578](https://github.com/carsonperrotti/CNPPopupController) - Simple and versatile class for presenting a custom popup in a variety of fashions. It includes a many options for controlling how your popup appears and behaves.
* [PopupController ★226](https://github.com/daisuke310vvv/PopupController) - A customizable controller for showing temporary popup view.
* [SubscriptionPrompt ★206](https://github.com/binchik/SubscriptionPrompt) - Subscription View Controller like the Tinder uses :large_orange_diamond:
* [Presentr ★1633](https://github.com/IcaliaLabs/Presentr) - Wrapper for custom ViewController presentations in iOS 8+ :large_orange_diamond:
* [PopupDialog ★2152](https://github.com/Orderella/PopupDialog) - A simple, customizable popup dialog for iOS written in Swift. Replaces UIAlertControllers alert style. :large_orange_diamond:
* [SelectionDialog ★72](https://github.com/kciter/SelectionDialog) - Simple selection dialog. :large_orange_diamond:
* [AZDialogViewController ★518](https://github.com/Minitour/AZDialogViewController) - A highly customizable alert dialog controller that mimics Snapchat's alert dialog. :large_orange_diamond:
* [MIBlurPopup ★356](https://github.com/MarioIannotta/MIBlurPopup) - MIBlurPopup let you create amazing popups with a blurred background.
* [LNPopupController ★2002](https://github.com/LeoNatan/LNPopupController) - a framework for presenting view controllers as popups of other view controllers, much like the Apple Music and Podcasts apps.

#### ProgressView
* [ProgressMeter ★14](https://github.com/khawajafarooq/ProgressMeter) - Display the progress on a meter with customized annotations for iOS developed in Swift :large_orange_diamond:

#### Pull to Refresh
* [DGElasticPullToRefresh ★2965](https://github.com/gontovnik/DGElasticPullToRefresh) - Elastic pull to refresh for iOS developed in Swift :large_orange_diamond:
* [PullToBounce ★1654](https://github.com/entotsu/PullToBounce) - Animated "Pull To Refresh" Library for UIScrollView. :large_orange_diamond:
* [SVPullToRefresh ★4826 ⏳1Y](https://github.com/samvermette/SVPullToRefresh) - Give pull-to-refresh & infinite scrolling to any UIScrollView with 1 line of code. http://samvermette.com/314
* [UzysAnimatedGifPullToRefresh ★1405 ⏳1Y](https://github.com/uzysjung/UzysAnimatedGifPullToRefresh) - Add PullToRefresh using animated GIF to any scrollView with just simple code
* [PullToRefreshCoreText ★315 ⏳1Y](https://github.com/cemolcay/PullToRefreshCoreText) - PullToRefresh extension for all UIScrollView type classes with animated text drawing style
* [BOZPongRefreshControl ★898 ⏳2Y](https://github.com/boztalay/BOZPongRefreshControl) - A pull-down-to-refresh control for iOS that plays pong, originally created for the MHacks III iOS app
* [CBStoreHouseRefreshControl ★3964 ⏳1Y](https://github.com/coolbeet/CBStoreHouseRefreshControl) - Fully customizable pull-to-refresh control inspired by Storehouse iOS app
* [SurfingRefreshControl ★49 ⏳1Y](https://github.com/peiweichen/SurfingRefreshControl) - Inspired by CBStoreHouseRefreshControl.Customizable pull-to-refresh control,written in pure Swift :large_orange_diamond:
* [mntpulltoreact ★780 ⏳2Y](https://github.com/mentionapp/mntpulltoreact) - One gesture, many actions. An evolution of Pull to Refresh.
* [ADChromePullToRefresh ★233 ⏳1Y](https://github.com/Antondomashnev/ADChromePullToRefresh) - Chrome iOS app style pull to refresh with multiple actions.
* [BreakOutToRefresh ★2174 ⏳1Y](https://github.com/dasdom/BreakOutToRefresh) - A playable pull to refresh view using SpriteKit. :large_orange_diamond:
* [MJRefresh ★11217](https://github.com/CoderMJLee/MJRefresh) An easy way to use pull-to-refresh.
* [HTPullToRefresh ★28 ⏳1Y](https://github.com/hoang-tran/HTPullToRefresh) - Easily add vertical and horizontal pull to refresh to any UIScrollView. Can also add multiple pull-to-refesh views at once.
* [PullToRefreshSwift ★490](https://github.com/dekatotoro/PullToRefreshSwift) - iOS Simple Cool PullToRefresh Library. It is written in pure swift. :large_orange_diamond:
* [GIFRefreshControl ★131 ⏳1Y](https://github.com/delannoyk/GIFRefreshControl) - GIFRefreshControl is a pull to refresh that supports GIF images as track animations. :large_orange_diamond:
* [ReplaceAnimation ★810 ⏳1Y](https://github.com/fruitcoder/ReplaceAnimation) - Pull-to-refresh animation in UICollectionView with a sticky header flow layout, written in Swift :large_orange_diamond: :large_orange_diamond:
* [PullToMakeSoup ★1707](https://github.com/Yalantis/PullToMakeSoup) - Custom animated pull-to-refresh that can be easily added to UIScrollView :large_orange_diamond:
* [RainyRefreshControl ★598](https://github.com/Onix-Systems/RainyRefreshControl) - Simple refresh control for iOS inspired by [concept](https://dribbble.com/shots/2242263--1-Pull-to-refresh-Freebie-Weather-Concept). :large_orange_diamond:
* [ESPullToRefresh ★729](https://github.com/eggswift/pull-to-refresh) - Customisable pull-to-refresh, including nice animation on the top :large_orange_diamond:

#### Rating Stars
* [FloatRatingView ★396](https://github.com/glenyi/FloatRatingView) - Whole, half or floating point ratings control written in Swift :large_orange_diamond:
* [TTGEmojiRate ★225](https://github.com/zekunyan/TTGEmojiRate) - An emoji-liked rating view for iOS, implemented in Swift. :large_orange_diamond:
* [StarryStars ★138](https://github.com/peterprokop/StarryStars) - StarryStars is iOS GUI library for displaying and editing ratings :large_orange_diamond:
* [Cosmos ★818](https://github.com/evgenyneu/Cosmos) - A star rating control for iOS / Swift :large_orange_diamond:
* [HCSStarRatingView ★1032](https://github.com/hsousa/HCSStarRatingView) - Simple star rating view for iOS written in Objective-C
* [MBRateApp ★52](https://github.com/MatiBot/MBRateApp) - A groovy app rate stars screen for iOS written in Swift :large_orange_diamond:

#### ScrollView
* [ScrollingFollowView ★140](https://github.com/ktanaka117/ScrollingFollowView) - ScrollingFollowView is a simple view which follows UIScrollView scrolling.
* [UIScrollView-InfiniteScroll ★771](https://github.com/pronebird/UIScrollView-InfiniteScroll) - UIScrollView infinite scroll category.
* [GoAutoSlideView ★46](https://github.com/zjmdp/GoAutoSlideView) - GoAutoSlideView extends UIScrollView by featuring infinitely and automatically slide.
* [AppStoreStyleHorizontalScrollView ★570](https://github.com/terenceLuffy/AppStoreStyleHorizontalScrollView) - App store style horizontal scroll view. :large_orange_diamond:
* [PullToDismiss ★189](https://github.com/sgr-ksmt/PullToDismiss) - You can dismiss modal viewcontroller by pulling scrollview or navigationbar in Swift. :large_orange_diamond:
* [SpreadsheetView ★2040](https://github.com/kishikawakatsumi/SpreadsheetView) - Full configurable spreadsheet view user interfaces for iOS applications. With this framework, you can easily create complex layouts like schedule, gantt chart or timetable as if you are using Excel. :large_orange_diamond:
*  [VegaScroll ★1507](https://github.com/AppliKeySolutions/VegaScroll) - VegaScroll is a lightweight animation flowlayout for UICollectionView completely written in Swift 4, compatible with iOS 11 and Xcode 9 :large_orange_diamond:
*  [ShelfView-iOS ★194](https://github.com/tdscientist/ShelfView-iOS) - iOS custom view to display books on shelf :large_orange_diamond:

#### Segmented Control
* [BetterSegmentedControl ★898](https://github.com/gmarm/BetterSegmentedControl) - An easy to use, customizable replacement for UISegmentedControl & UISwitch. :large_orange_diamond:
* [LUNSegmentedControl ★207](https://github.com/Stormotion-Mobile/LUNSegmentedControl) - Customizable segmented control with interactive animation.
* [AKASegmentedControl ★404 ⏳1Y](https://github.com/alikaragoz/AKASegmentedControl) - :chocolate_bar: Fully customizable Segmented Control for iOS.
* [TwicketSegmentedControl ★1193](https://github.com/twicketapp/TwicketSegmentedControl) - Custom UISegmentedControl replacement for iOS, written in Swift. :large_orange_diamond:
* [SJFluidSegmentedControl ★689](https://github.com/sasojadrovski/SJFluidSegmentedControl) - A segmented control with custom appearance and interactive animations. Written in Swift 3.0. :large_orange_diamond:
* [HMSegmentedControl ★3159](https://github.com/HeshamMegid/HMSegmentedControl) - A drop-in replacement for UISegmentedControl mimicking the style of the segmented control used in Google Currents and various other Google products.
* [YUSegment ★94](https://github.com/afishhhhh/YUSegment) - A customizable segmented control for iOS. Supports both text and image.
* [MultiSelectSegmentedControl ★77](https://github.com/yonat/MultiSelectSegmentedControl) - adds Multiple-Selection to the standard `UISegmentedControl`.
* [DynamicMaskSegmentSwitch ★290 ⏳1Y](https://github.com/KittenYang/DynamicMaskSegmentSwitch) - A segment switcher with dynamic text mask effect :large_orange_diamond:
* [PinterestSegment ★285](https://github.com/TBXark/PinterestSegment) - A Pinterest-like segment control with masking animation. :large_orange_diamond:

#### Slider
* [VolumeControl ★60](https://github.com/12Rockets/VolumeControl) - Custom volume control for iPhone featuring a well-designed round slider.
* [WESlider ★79 ⏳1Y](https://github.com/Ekhoo/WESlider) - Simple and light weight slider with chapter management
* [IntervalSlider ★50 ⏳1Y](https://github.com/shushutochako/IntervalSlider) - IntervalSlider is a slider library like ReutersTV app. written in pure swift. :large_orange_diamond:
* [RangeSlider ★162](https://github.com/warchimede/RangeSlider) - A simple range slider made in Swift :large_orange_diamond:
* [CircleSlider ★105](https://github.com/shushutochako/CircleSlider) - CircleSlider is a Circular slider library. written in pure Swift. :large_orange_diamond:
* [MARKRangeSlider ★138](https://github.com/vadymmarkov/MARKRangeSlider) - A custom reusable slider control with 2 thumbs (range slider).
* [ASValueTrackingSlider ★1726](https://github.com/alskipp/ASValueTrackingSlider) - A UISlider subclass that displays the slider value in a popup view
* [TTRangeSlider ★643](https://github.com/TomThorpe/TTRangeSlider) - A slider, similar in style to UISlider, but which allows you to pick a minimum and maximum range.
* [MMSegmentSlider ★28](https://github.com/MedvedevMax/MMSegmentSlider) - Customizable animated slider for iOS.
* [StepSlider ★136](https://github.com/spromicky/StepSlider) - StepSlider its custom implementation of slider such as UISlider for preset integer values.
* [JDSlider ★75](https://github.com/JellyDevelopment/JDSlider) - An iOS Slider written in Swift. :large_orange_diamond:
* [SnappingSlider ★530 ⏳1Y](https://github.com/rehatkathuria/SnappingSlider) - A beautiful slider control for iOS built purely upon Swift :large_orange_diamond:
* [MTCircularSlider ★19](https://github.com/EranBoudjnah/MTCircularSlider) - A feature-rich circular slider control. :large_orange_diamond:
* [VerticalSlider ★29](https://github.com/jonkykong/VerticalSlider) - VerticalSlider is a vertical implementation of the UISlider slider control. :large_orange_diamond:
* [CircularSlider ★159](https://github.com/taglia3/CircularSlider) - A powerful Circular Slider. It's written in Swift, it's 100% IBDesignable and all parameters are IBInspectable. :large_orange_diamond:
* [HGCircularSlider ★1208](https://github.com/HamzaGhazouani/HGCircularSlider) - A custom reusable circular slider control for iOS application. :large_orange_diamond:
* [PivotSlider ★24](https://github.com/dereklimbus/pivot-slider) - Slider that pivots :large_orange_diamond:
* [RangeSeekSlider ★149](https://github.com/WorldDownTown/RangeSeekSlider) - A customizable range slider for iOS. :large_orange_diamond:
* [SectionedSlider ★142](https://github.com/LeonardoCardoso/SectionedSlider) - Control Center Slider. :large_orange_diamond:
* [MultiSlider ★6](https://github.com/yonat/MultiSlider) - UISlider clone with multiple thumbs and values, optional snap intervals, optional value labels. :large_orange_diamond:
* [AGCircularPicker ★416](https://github.com/agilie/AGCircularPicker) - AGCircularPicker is helpful component for creating a controller aimed to manage any calculated parameter. :large_orange_diamond:
* [VSVerticalSlider ★12](https://github.com/vsmithers1087/VSVerticalSlider) - An animatable and customizable vertical slider written in Swift4.🔶
* [Fluid Slider ★30](https://github.com/Ramotion/fluid-slider) - A slider widget with a popup bubble displaying the precise value selected. :large_orange_diamond:

#### Splash View
* [CBZSplashView ★1432](https://github.com/callumboddy/CBZSplashView) - Twitter style Splash Screen View. Grows to reveal the Initial view behind.
* [SKSplashView ★453 ⏳1Y](https://github.com/sachinkesiraju/SKSplashView) - Create custom animated splash views similar to the ones in the Twitter, Uber and Ping iOS app.
* [RevealingSplashView ★789](https://github.com/PiXeL16/RevealingSplashView) - A Splash view that animates and reveals its content, inspired by Twitter splash :large_orange_diamond:

#### Stepper
* [PFStepper ★24](https://github.com/PerfectFreeze/PFStepper) - May be the most elegant stepper you have ever had! :large_orange_diamond:
* [ValueStepper ★218](https://github.com/BalestraPatrick/ValueStepper) - A Stepper object that displays its value. :large_orange_diamond:
* [GMStepper ★568](https://github.com/gmertk/GMStepper) - A stepper with a sliding label in the middle. :large_orange_diamond:
* [barceloneta ★37](https://github.com/arn00s/barceloneta) - The right way to increment/decrement values with a simple gesture on iOS. :large_orange_diamond:
* [SnappingStepper ★328](https://github.com/yannickl/SnappingStepper) - An elegant alternative to the UIStepper written in Swift :large_orange_diamond:
* [SMNumberWheel ★15](https://github.com/SinaMoetakef/SMNumberWheel) - A custom control written in Swift, which is ideal for picking numbers very fast but yet very accurate using a rotating wheel :large_orange_diamond:

#### Switch
* [AnimatedSwitch ★160](https://github.com/alsedi/AnimatedSwitch) - UISwitch which paints over the parent view with the color in Swift. :large_orange_diamond:
* [ViralSwitch ★318](https://github.com/andreamazz/ViralSwitch) - A UISwitch that infects its superview with its tint color.
* [JTMaterialSwitch ★234 ⏳2Y](https://github.com/JunichiT/JTMaterialSwitch) - A customizable switch UI with ripple effect and bounce animations, inspired from Google's Material Design.
* [TKSwitcherCollection ★505](https://github.com/TBXark/TKSwitcherCollection) - An animate switch collection :large_orange_diamond:
* [SevenSwitch ★749](https://github.com/bvogelzang/SevenSwitch) - iOS7 style drop in replacement for UISwitch. :large_orange_diamond:
* [DGRunkeeperSwitch ★1819](https://github.com/gontovnik/DGRunkeeperSwitch) - Runkeeper design switch control (two part segment control) :large_orange_diamond:
* [PMZSwitch ★52 ⏳1Y](https://github.com/kovpas/PMZSwitch) - Yet another animated toggle :large_orange_diamond:
* [Switcher ★165](https://github.com/knn90/Switcher) - Swift - Custom UISwitcher with animation when change status :large_orange_diamond:
* [RAMPaperSwitch ★2338](https://github.com/Ramotion/paper-switch) - RAMPaperSwitch is a Swift module which paints over the parent view when the switch is turned on. :large_orange_diamond:
* [AIFlatSwitch ★642](https://github.com/cocoatoucher/AIFlatSwitch) - A flat component alternative to UISwitch on iOS :large_orange_diamond:
* [Switch ★71](https://github.com/T-Pham/Switch) - An iOS switch control implemented in Swift with full Interface Builder support.🔶

#### Tab Bar
* [ESTabBarController ★99 ⏳1Y](https://github.com/ezescaruli/ESTabBarController) - A tab bar controller for iOS that allows highlighting buttons and setting custom actions to them.
* [GooeyTabbar ★706](https://github.com/KittenYang/GooeyTabbar) -A gooey effect tabbar :large_orange_diamond:
* [animated-tab-bar ★8239](https://github.com/Ramotion/animated-tab-bar) - RAMAnimatedTabBarController is a Swift module for adding animation to tabbar items. :large_orange_diamond:
* [FoldingTabBar.iOS ★3382](https://github.com/Yalantis/FoldingTabBar.iOS) - Folding Tab Bar and Tab Bar Controller
* [GGTabBar ★153](https://github.com/Goles/GGTabBar) - Another UITabBar & UITabBarController (iOS Tab Bar) replacement, but uses Auto Layout for arranging it's views hierarchy.
* [adaptive-tab-bar ★1781](https://github.com/Ramotion/adaptive-tab-bar) - AdaptiveController is a 'Progressive Reduction' Swift module for adding custom states to Native or Custom iOS UI elements :large_orange_diamond:
* [Pager ★203](https://github.com/lucoceano/Pager) - Easily create sliding tabs with Pager :large_orange_diamond:
* [XLPagerTabStrip ★4539](https://github.com/xmartlabs/XLPagerTabStrip) - Android PagerTabStrip for iOS. :large_orange_diamond:
* [TabPageViewController ★728](https://github.com/EndouMari/TabPageViewController) - Paging view controller and scroll tab view. 🔶
* [TabDrawer ★498 ⏳1Y](https://github.com/winslowdibona/TabDrawer) - Customizable TabBar UI element that allows you to run a block of code upon TabBarItem selection, written in Swift 🔶
* [SwipeViewController ★452](https://github.com/fortmarek/SwipeViewController) - SwipeViewController is a Swift modification of RKSwipeBetweenViewControllers - navigate between pages / ViewControllers :large_orange_diamond:
* [ColorMatchTabs ★974](https://github.com/Yalantis/ColorMatchTabs) - Interesting way to display tabs :large_orange_diamond:
* [BATabBarController ★646](https://github.com/antiguab/BATabBarController) - A TabBarController with a unique animation for selection
* [ScrollPager ★430](https://github.com/aryaxt/ScrollPager) - A scroll pager that displays a list of tabs (segments) and manages paging between given views :large_orange_diamond:
* [Segmentio ★1472](https://github.com/Yalantis/Segmentio) - Animated top/bottom segmented control written in Swift. :large_orange_diamond:
* [KYWheelTabController ★84](https://github.com/ykyouhei/KYWheelTabController) - KYWheelTabController is a subclass of UITabBarController.It displays the circular menu instead of UITabBar. :large_orange_diamond:
* [SuperBadges ★22](https://github.com/odedharth/SuperBadges) - Add emojis and colored dots as badges for your Tab Bar buttons 🔶
* [AZTabBarController ★115](https://github.com/Minitour/AZTabBarController) - A custom tab bar controller for iOS written in Swift 3.0 🔶
* [MiniTabBar ★58](https://github.com/D-32/MiniTabBar) - A clean simple alternative to the UITabBar 🔶
* [SwipeableTabBarController ★149](https://github.com/marcosgriselli/SwipeableTabBarController) - UITabBarController with swipe interaction between its tabs. 🔶
* [SMSwipeableTabView ★28](https://github.com/smahajan28/SMSwipeableTabView) - Swipeable Views with Tabs (Like Android SwipeView With Tabs Layout) 🔶
* [Tabman ★636](https://github.com/uias/Tabman) - A powerful paging view controller with indicator bar for iOS. 🔶

#### Table View / Collection View
* [MGSwipeTableCell ★5879](https://github.com/MortimerGoro/MGSwipeTableCell) - UITableViewCell subclass that allows to display swippable buttons with a variety of transitions.
* [ParallaxTableViewHeader ★1260 ⏳1Y](https://github.com/Vinodh-G/ParallaxTableViewHeader) - Parallax scrolling effect on UITableView header view when a tableView is scrolled.
* [YXTPageView ★61](https://github.com/hanton/YXTPageView) - A PageView, which supporting scrolling to transition between a UIView and a UITableView.
* [DZNEmptyDataSet ★9439](https://github.com/dzenbot/DZNEmptyDataSet) - A drop-in UITableView/UICollectionView superclass category for showing empty datasets whenever the view has no content to display.
* [ConfigurableTableViewController ★245 ⏳1Y](https://github.com/fastred/ConfigurableTableViewController) - Typed, yet Flexible Table View Controller http://holko.pl/2016/01/05/typed-table-view-controller/ :large_orange_diamond:
* [CSStickyHeaderFlowLayout ★4808 ⏳1Y](https://github.com/CSStickyHeaderFlowLayout/CSStickyHeaderFlowLayout) - UICollectionView replacement of UITableView. Do even more like Parallax Header, Sticky Section Header. :large_orange_diamond:
* [folding-cell ★6645](https://github.com/Ramotion/folding-cell) - FoldingCell is an expanding content cell inspired by folding paper material :large_orange_diamond:
* [Lightning-Table ★22 ⏳2Y](https://github.com/electrickangaroo/Lightning-Table) - A declarative api for working with UITableView.
* [Static ★991](https://github.com/venmo/Static) - Simple static table views for iOS in Swift. :large_orange_diamond:
* [GSKStretchyHeaderView ★1043](https://github.com/gskbyte/GSKStretchyHeaderView) - Configurable yet easy to use stretchy header view for UITableView and UICollectionView.
* [MEVFloatingButton ★278](https://github.com/manuelescrig/MEVFloatingButton) - An iOS drop-in UITableView, UICollectionView and UIScrollView superclass category for showing a customizable floating button on top of it.
* [AMWaveTransition ★2338](https://github.com/andreamazz/AMWaveTransition) - Custom transition between viewcontrollers holding tableviews.
* [Dwifft ★1415](https://github.com/jflinter/Dwifft) - Swift Diff :large_orange_diamond:
* [AEAccordion ★161](https://github.com/tadija/AEAccordion) - UITableViewController with accordion effect (expand / collapse cells). :large_orange_diamond:
* [SWTableViewCell ★6939](https://github.com/CEWendel/SWTableViewCell) - An easy-to-use UITableViewCell subclass that implements a swippable content view which exposes utility buttons (similar to iOS 7 Mail Application)
* [ZYThumbnailTableView ★892](https://github.com/liuzhiyi1992/ZYThumbnailTableView) - a TableView have thumbnail cell only, and you can use gesture let it expands other expansionView, all diy :large_orange_diamond:
* [BWSwipeRevealCell ★46 ⏳1Y](https://github.com/bitwit/BWSwipeRevealCell) - A Swift library for swipeable table cells :large_orange_diamond:
* [preview-transition ★1601](https://github.com/Ramotion/preview-transition) - PreviewTransition is a simple preview gallery controller :large_orange_diamond:
* [QuickTableViewController ★91](https://github.com/bcylin/QuickTableViewController) - A simple way to create a UITableView for settings in Swift. :large_orange_diamond:
* [TableKit ★275](https://github.com/maxsokolov/TableKit) - Type-safe declarative table views with Swift :large_orange_diamond:
* [Preheat ★587](https://github.com/kean/Preheat) - Automates prefetching of content in UITableView and UICollectionView :large_orange_diamond:
* [VBPiledView ★122](https://github.com/v-braun/VBPiledView) - Simple and beautiful stacked UIView to use as a replacement for an UITableView, UIImageView or as a menu :large_orange_diamond:
* [DisplaySwitcher ★1603](https://github.com/Yalantis/DisplaySwitcher) - Custom transition between two collection view layouts :large_orange_diamond:
* [CHTCollectionViewWaterfallLayout ★3474](https://github.com/chiahsien/CHTCollectionViewWaterfallLayout) - The waterfall (i.e., Pinterest-like) layout for UICollectionView.
* [FMMosaicLayout ★565 ⏳1Y](https://github.com/fmitech/FMMosaicLayout) - A drop-in mosaic collection view layout with a focus on simple customizations.
* [mosaic-layout ★164](https://github.com/vinnyoodles/mosaic-layout) - A mosaic collection view layout inspired by Lightbox's Algorithm, written in Swift :large_orange_diamond:
* [Reusable ★1281](https://github.com/AliSoftware/Reusable) - A Swift mixin for UITableViewCells and UICollectionViewCells :large_orange_diamond:
* [VTMagic ★1474](https://github.com/tianzhuo112/VTMagic) - VTMagic is a page container library for iOS.
* [MCSwipeTableViewCell ★3012](https://github.com/alikaragoz/MCSwipeTableViewCell) - :point_up_2: Convenient UITableViewCell subclass that implements a swippable content to trigger actions (similar to the Mailbox app).
* [Sapporo ★231 ⏳1Y](https://github.com/nghialv/Sapporo) - Cellmodel-driven collectionview manager :large_orange_diamond:
* [MYTableViewIndex ★315](https://github.com/mindz-eye/MYTableViewIndex) - A pixel perfect replacement for UITableView section index, written in Swift :large_orange_diamond:
* [RAReorderableLayout ★786](https://github.com/ra1028/RAReorderableLayout) - A UICollectionView layout which can move item with drag and drop.
* [StickyCollectionView-Swift ★205](https://github.com/matbeich/StickyCollectionView-Swift) - UICollectionView layout for presenting of the overlapping cells. :large_orange_diamond:
* [ios-dragable-table-cells ★38](https://github.com/palmin/ios-dragable-table-cells) - Support for drag-n-drop of UITableViewCells in a navigation hierarchy of view controllers. You drag cells by tapping and holding them.
* [TLLayoutTransitioning ★330](https://github.com/SwiftKickMobile/TLLayoutTransitioning) - Enhanced transitioning between UICollectionView layouts in iOS.
* [Bohr ★1236](https://github.com/DavdRoman/Bohr) - Bohr allows you to set up a settings screen for your app with three principles in mind: ease, customization and extensibility.
* [SwiftReorder ★61](https://github.com/adamshin/SwiftReorder) - Add drag-and-drop reordering to any table view with just a few lines of code. Robust, lightweight, and completely customizable. :large_orange_diamond:[e]
* [TLIndexPathTools ★337](https://github.com/SwiftKickMobile/TLIndexPathTools) - TLIndexPathTools is a small set of classes that can greatly simplify your table and collection views.
* [HoverConversion ★166 ⏳1Y](https://github.com/marty-suzuki/HoverConversion) - HoverConversion realized vertical paging with UITableView. UIViewController will be paging when reaching top or bottom of UITableView contentOffset. :large_orange_diamond:
* [TableViewDragger ★309 ⏳1Y](https://github.com/KyoheiG3/TableViewDragger) - A cells of UITableView can be rearranged by drag and drop. :large_orange_diamond:
* [IGListKit ★7063](https://github.com/Instagram/IGListKit) - A data-driven UICollectionView framework for building fast and flexible lists.
* [MMCardView ★428](https://github.com/MillmanY/MMCardView) - Custom CollectionView like Wallet App :large_orange_diamond:
* [FlexibleTableViewController ★9](https://github.com/dimpiax/FlexibleTableViewController) - Swift library of generic table view controller with external data processing of functionality, like determine cell's reuseIdentifier related to indexPath, configuration of requested cell for display and cell selection handler
* [FlexibleCollectionViewController ★1](https://github.com/dimpiax/FlexibleCollectionViewController) - Swift library of generic collection view controller with external data processing of functionality, like determine cell's reuseIdentifier related to indexPath, configuration of requested cell for display and cell selection handler etc
* [CascadingTableDelegate ★785](https://github.com/edopelawi/CascadingTableDelegate) - A no-nonsense way to write cleaner UITableViewDelegate and UITableViewDataSource in Swift.:large_orange_diamond:
* [TimelineTableViewCell ★804](https://github.com/kf99916/TimelineTableViewCell) - Simple timeline view implemented by UITableViewCell written in Swift 3.0.:large_orange_diamond:
* [RHPreviewCell ★331](https://github.com/robertherdzik/RHPreviewCell) - I envied so much Spotify iOS app this great playlist preview cell. Now you can give your users ability to quick check "what content is hidden under your UITableViewCell". :large_orange_diamond:
* [ThreeLevelAccordian ★29](https://github.com/amratab/ThreeLevelAccordian) - This is a customisable three level accordian with options for adding images and accessories images. :large_orange_diamond:
* [TORoundedTableView ★58](https://github.com/TimOliver/TORoundedTableView) - A subclass of UITableView that styles it like Settings.app on iPad
* [ASCollectionView ★127](https://github.com/abdullahselek/ASCollectionView) - A Swift collection view inspired by Airbnb. :large_orange_diamond:
* [TableFlip ★348](https://github.com/mergesort/TableFlip) - A simpler way to do cool UITableView animations! (╯°□°）╯︵ ┻━┻ :large_orange_diamond:
* [DTTableViewManager ★316](https://github.com/DenHeadless/DTTableViewManager) - Protocol-oriented UITableView management, powered by generics and associated types. :large_orange_diamond:
* [GLTableCollectionView ★453](https://github.com/giulio92/GLTableCollectionView) - Netflix and App Store like UITableView with UICollectionView :large_orange_diamond:
* [SwipeCellKit ★2564](https://github.com/SwipeCellKit/SwipeCellKit) - Swipeable UITableViewCell based on the stock Mail.app, implemented in Swift. :large_orange_diamond:
* [EditDistance ★49](https://github.com/kazuhiro4949/EditDistance) - Incremental update tool for UITableView and UICollectionView :large_orange_diamond:
* [CenteredCollectionView ★156](https://github.com/BenEmdon/CenteredCollectionView) - A lightweight UICollectionViewLayout that _'pages'_ and centers it's cells 🎡 written in Swift. :large_orange_diamond:
* [YBSlantedCollectionViewLayout ★132](https://github.com/yacir/YBSlantedCollectionViewLayout) - UICollectionViewLayout with slanted content.
* [ReverseExtension ★1158](https://github.com/marty-suzuki/ReverseExtension) - A UITableView extension that enables cell insertion from the bottom of a table view.
* [YNExpandableCell ★328](https://github.com/younatics/YNExpandableCell) - Awesome expandable, collapsible tableview cell for iOS written in Swift 3 🔶
* [SquareMosaicLayout ★69](https://github.com/iwheelbuy/SquareMosaicLayout) - An extandable mosaic UICollectionViewLayout with a focus on extremely flexible customizations 🔶
* [SwiftSpreadSheet ★409](https://github.com/stuffrabbit/SwiftSpreadsheet) - Spreadsheet CollectionViewLayout in Swift. Fully customizable. 🔶
* [GenericDataSource ★44](https://github.com/GenericDataSource/GenericDataSource) - A generic small reusable components for data source implementation for UITableView/UICollectionView in Swift. 🔶
* [BouncyLayout ★2688](https://github.com/roberthein/BouncyLayout) - BouncyLayout is a collection view layout that makes your cells bounce. 🔶
* [Savory ★0](https://github.com/Nandiin/Savory) - A swift accordion view implementation. :large_orange_diamond:
* [PagingView ★246](https://github.com/KyoheiG3/PagingView) - Infinite paging, Smart auto layout, Interface of similar to UIKit. :large_orange_diamond:🔶
* [ExpyTableView ★151](https://github.com/okhanokbay/ExpyTableView) - Make your table view expandable just by implementing one method. 🔶
* [FTFoldingPaper ★23](https://github.com/monofire/FTFoldingPaper) - Emulates paper folding effect. Can be integrated with UITableView or used with other UI components.
* [PJFDataSource ★82](https://github.com/square/PJFDataSource) - PJFDataSource is a small library that provides a simple, clean architecture for your app to manage its data sources while providing a consistent user interface for common content states (i.e. loading, loaded, empty, and error).
* [HGPlaceholders ★910](https://github.com/HamzaGhazouani/HGPlaceholders) - Nice library to show and create placeholders and Empty States for any UITableView/UICollectionView in your project 🔶
* [CollapsibleTableSectionViewController ★54](https://github.com/jeantimex/CollapsibleTableSectionViewController) - A swift library to support collapsible sections in a table view. :large_orange_diamond:
* [ExpandableCell ★180](https://github.com/younatics/ExpandableCell) - Fully refactored YNExapnadableCell with more concise, bug free. Awesome expandable, collapsible tableview cell for iOS written in Swift 3 🔶
* [DataSources ★336](https://github.com/muukii/DataSources) - Type-safe data-driven List-UI Framework. (We can also use ASCollectionNode) 🔶
* [KDDragAndDropCollectionView ★252](https://github.com/mmick66/KDDragAndDropCollectionView) - Dragging & Dropping data across multiple UICollectionViews. 🔶
* [ListPlaceholder ★269](https://github.com/malkouz/ListPlaceholder) - ListPlaceholder is a swift library allows you to easily add facebook style animated loading placeholder to your tableviews or collection views :large_orange_diamond:
* [SectionScrubber ★137](https://github.com/bakkenbaeck/SectionScrubber) - A component to quickly scroll between collection view sections :large_orange_diamond:
* [CardsLayout ★203](https://github.com/filletofish/CardsLayout) - Nice card-designed custom collection view layout. 🔶

#### Tag
* [PARTagPicker ★269](https://github.com/paulrolfe/PARTagPicker) - This pod provides a view controller for choosing and creating tags in the style of wordpress or tumblr.
* [AMTagListView ★703](https://github.com/andreamazz/AMTagListView) - UIScrollView subclass that allows to add a list of highly customizable tags.
* [TagCellLayout ★118](https://github.com/riteshhgupta/TagCellLayout) - UICollectionView layout for Tags with Left, Center & Right alignments. :large_orange_diamond:
* [TTGTagCollectionView ★666](https://github.com/zekunyan/TTGTagCollectionView) - Show simple text tags or custom tag views in a vertical scrollable view.
* [TagListView ★1161](https://github.com/ElaWorkshop/TagListView) - Simple and highly customizable iOS tag list view, in Swift. :large_orange_diamond:
* [RKTagsView ★364 ⏳1Y](https://github.com/kuler90/RKTagsView) - Highly customizable iOS tags view (like NSTokenField). Supports editing, multiple selection, Auto Layout and much more.
* [WSTagsField ★637](https://github.com/whitesmith/WSTagsField) - An iOS text field that represents different Tags :large_orange_diamond:
* [AKMaskField ★232](https://github.com/artemkrachulov/AKMaskField) - AKMaskField is UITextField subclass which allows enter data in the fixed quantity and in the certain format. :large_orange_diamond:
* [YNSearch ★704](https://github.com/younatics/YNSearch) - Awesome fully customizable search view like Pinterest written in Swift 3 🔶

#### TextField & TextView
* [JVFloatLabeledTextField ★6514](https://github.com/jverdi/JVFloatLabeledTextField) - UITextField subclass with floating labels.
* [ARAutocompleteTextView ★258](https://github.com/alexruperez/ARAutocompleteTextView) - subclass of UITextView that automatically displays text suggestions in real-time. Perfect for email Textviews.
* [IQDropDownTextField ★235](https://github.com/hackiftekhar/IQDropDownTextField) - TextField with DropDown support using UIPickerView
* [UITextField-Shake](https://github.com/andreamazz/UITextField-Shake) - UITextField category that adds shake animation. [Also with Swift version ★13](https://github.com/King-Wizard/UITextField-Shake-Swift) :large_orange_diamond:
* [HTYTextField ★224](https://github.com/hanton/HTYTextField) - A UITextField with bouncy placeholder. :large_orange_diamond:
* [MVAutocompletePlaceSearchTextField ★67 ⏳2Y](https://github.com/TheMrugraj/MVAutocompletePlaceSearchTextField) - A drop-in Autocompletion control for Place Search like Google Places, Uber, etc.
* [AutocompleteField ★653](https://github.com/filipstefansson/AutocompleteField) - Add word completion to your UITextFields. :large_orange_diamond:
* [RSKGrowingTextView ★512](https://github.com/ruslanskorb/RSKGrowingTextView) - A light-weight UITextView subclass that automatically grows and shrinks. :large_orange_diamond:
* [RSKPlaceholderTextView ★56](https://github.com/ruslanskorb/RSKPlaceholderTextView) - A light-weight UITextView subclass that adds support for placeholder. :large_orange_diamond:
* [StatefulViewController ★1809](https://github.com/aschuch/StatefulViewController) - Placeholder views based on content, loading, error or empty states :large_orange_diamond:
* [MBAutoGrowingTextView ★117 ⏳1Y](https://github.com/MatejBalantic/MBAutoGrowingTextView) - An auto-layout base UITextView subclass which automatically grows with user input and can be constrained by maximal and minimal height - all without a single line of code
* [TextFieldEffects ★4282](https://github.com/raulriera/TextFieldEffects) - Custom UITextFields effects inspired by Codrops, built using Swift :large_orange_diamond:
* [Reel Search ★1903](https://github.com/Ramotion/reel-search) - RAMReel is a controller that allows you to choose options from a list. :large_orange_diamond:
* [MLPAutoCompleteTextField ★1147](https://github.com/EddyBorja/MLPAutoCompleteTextField) - a subclass of UITextField that behaves like a typical UITextField with one notable exception: it manages a drop down table of autocomplete suggestions that update as the user types.
* [SkyFloatingLabelTextField ★2275](https://github.com/Skyscanner/SkyFloatingLabelTextField) - A beautiful and flexible text field control implementation of "Float Label Pattern". Written in Swift.:large_orange_diamond:
* [VMaskTextField ★356](https://github.com/viniciusmo/VMaskTextField) - VMaskTextField is a library which create an input mask for iOS.
* [TJTextField ★35](https://github.com/tejas-ardeshna/TJTextField) - UITextField with underline and left image :large_orange_diamond:
* [NextGrowingTextView ★874](https://github.com/muukii/NextGrowingTextView) - The next in the generations of 'growing textviews' optimized for iOS 7 and above.
* [RPFloatingPlaceholders ★1097 ⏳1Y](https://github.com/iwasrobbed/RPFloatingPlaceholders) - UITextField and UITextView subclasses with placeholders that change into floating labels when the fields are populated with text.
* [CurrencyTextField ★21](https://github.com/richa008/CurrencyTextField) - UITextField that automatically formats text to display in the currency format. :large_orange_diamond:
* [UITextField-Navigation ★340](https://github.com/T-Pham/UITextField-Navigation) - UITextField-Navigation adds next, previous and done buttons to the keyboard for your UITextFields.🔶[e]
* [AutoCompleteTextField ★23](https://github.com/nferocious76/AutoCompleteTextField) - Auto complete with suggestion textfield :large_orange_diamond:
* [EmojiTextView ★347 ⏳1Y](https://github.com/fastred/EmojiTextView) - Tap to swap out words with emojis. Inspired by Messages.app on iOS 10. :large_orange_diamond:
* [PLCurrencyTextField ★81 ⏳1Y](https://github.com/nonameplum/PLCurrencyTextField) - UITextField that support currency in the right way. :large_orange_diamond:
* [PasswordTextField ★140](https://github.com/PiXeL16/PasswordTextField) - A custom TextField with a switchable icon which shows or hides the password and enforce good password policies :large_orange_diamond:
* [AnimatedTextInput ★504](https://github.com/jobandtalent/AnimatedTextInput) - Animated UITextField and UITextView replacement for iOS :large_orange_diamond:
* [KMPlaceholderTextView ★474](https://github.com/MoZhouqi/KMPlaceholderTextView) - A UITextView subclass that adds support for multiline placeholder written in Swift. :large_orange_diamond:
* [NxEnabled ★25](https://github.com/Otbivnoe/NxEnabled) - Library which allows you binding `enabled` property of button with textable elements (TextView, TextField) :large_orange_diamond:
* [AwesomeTextField ★111](https://github.com/aleksandrshoshiashvili/AwesomeTextFieldSwift) - Awesome TextField is a nice and simple library for iOS. It's highly customisable and easy-to-use tool. Works perfectly for any registration or login forms in your app. :large_orange_diamond:
* [ModernSearchBar ★80](https://github.com/PhilippeBoisney/ModernSearchBar) - The famous iOS search bar with auto completion feature implemented. :large_orange_diamond:
* [SelectableTextView ★555](https://github.com/jhurray/SelectableTextView) - A text view that supports selection and expansion :large_orange_diamond:
* [CBPinEntryView ★29](https://github.com/Fawxy/CBPinEntryView) - A customisable view written in Swift 3.0 for any numerical pin or code entry. :large_orange_diamond:
* [GrowingTextView ★184](https://github.com/KennethTsang/GrowingTextView) - An UITextView in Swift3 and Swift2.3. Support auto growing, placeholder and length limit. :large_orange_diamond:
* [DTTextField ★76](https://github.com/iDhaval/DTTextField) - DTTextField is a custom textfield with floating placeholder and error label in Swift3.0.🔶
* [TextFieldCounter ★307](https://github.com/serralvo/TextFieldCounter) - UITextField character counter with lovable UX. 🔶
* [RSFloatInputView ★61](https://github.com/roytornado/RSFloatInputView) - A Float Input View with smooth animation and supporting icon and seperator written with Swift. 🔶
* [TaniwhaTextField ★20](https://github.com/iceman201/TaniwhaTextField) - TaniwhaTextField is a lightweight and beautiful swift textfield framework. It has float label pattern, and also you can highly customise it. it's written with Swift. 🔶
* [InstantSearch iOS ★390](https://github.com/algolia/instantsearch-ios) - A library of widgets and helpers to build instant-search applications on iOS. 🔶
* [SearchTextField ★242](https://github.com/apasccon/SearchTextField) - UITextField subclass with autocompletion suggestions list  :large_orange_diamond:
* [PYSearch ★2590](https://github.com/ko1o/PYSearch) - An elegant search controller which replaces the UISearchController for iOS (iPhone & iPad).
* [styled-text ★211](https://github.com/blueapron/styled-text) - Declarative text styles and streamlined Dynamic Type support for iOS. 🔶

#### Web View
* [Otafuku ★51 ⏳1Y](https://github.com/tasanobu/Otafuku) - Otafuku provides utility classes to use WKWebView in Swift. :large_orange_diamond:
* [SwiftWebVC ★174](https://github.com/meismyles/SwiftWebVC) - A drop-in inline browser for your Swift iOS app. :large_orange_diamond:
* [SVWebViewController ★2546](https://github.com/TransitApp/SVWebViewController) - A drop-in inline browser for your iOS app.
* [PTPopupWebView ★69](https://github.com/pjocprac/PTPopupWebView) - PTPopupWebView is a simple and useful WebView for iOS, which can be popup and has many of the customized item. :large_orange_diamond:

## Utility
 * [Underscore.m ★1518](https://github.com/robb/Underscore.m) - A DSL for Data Manipulation.
 * [XExtensionItem ★81 ⏳2Y](https://github.com/tumblr/XExtensionItem) - Easier sharing of structured data between iOS applications and share extensions.
 * [ReflectableEnum ★330](https://github.com/fastred/ReflectableEnum) - Reflection for enumerations in Objective-C.
 * [ObjectiveSugar ★2211 ⏳1Y](https://github.com/supermarin/ObjectiveSugar) - ObjectiveC additions for humans. Ruby style.
 * [OpinionatedC ★44 ⏳1Y](https://github.com/leoschweizer/OpinionatedC) - Because Objective-C should have inherited more from Smalltalk.
 * [SwiftRandom ★466](https://github.com/thellimist/SwiftRandom) - Generator for random data. :large_orange_diamond:
 * [RandomKit ★1240](https://github.com/nvzqz/RandomKit) - Random data generation in Swift. :large_orange_diamond:
 * [YOLOKit ★628 ⏳1Y](https://github.com/mxcl/YOLOKit) - Getting square objects down round holes.
 * [EZSwiftExtensions ★2275](https://github.com/goktugyil/EZSwiftExtensions) - :smirk: How Swift standard types and classes were supposed to work. :large_orange_diamond:[e]
 * [Pantry ★850](https://github.com/nickoneill/Pantry) - The missing light persistence layer for Swift :large_orange_diamond:
 * [SwiftParsec ★123](https://github.com/davedufresne/SwiftParsec) - A parser combinator library written in the Swift programming language. :large_orange_diamond:
 * [OrderedSet ★110](https://github.com/Weebly/OrderedSet) - A Swift collection of unique, ordered objects :large_orange_diamond:
 * [Datez ★206](https://github.com/SwiftKitz/Datez) - Swift library for dealing with `NSDate`, `NSCalendar`, and `NSDateComponents`. :large_orange_diamond:
 * [BFKit ★760](https://github.com/FabrizioBrancati/BFKit) - An Objective-C collection of useful classes to develop Apps faster.
 * [BFKit-Swift ★664](https://github.com/FabrizioBrancati/BFKit-Swift) - A Swift collection of useful classes to develop Apps faster. :large_orange_diamond:
 * [Scale ★300 ⏳1Y](https://github.com/onmyway133/scale) - Unit converter in Swift (available via CocoaPods) :large_orange_diamond:
 * [Standard Template Protocols ★379 ⏳1Y](https://github.com/cconeil/Standard-Template-Protocols) - Protocols for your every day iOS needs :large_orange_diamond:
 * [TimeLord ★6](https://github.com/JonFir/TimeLord) - Easy DateTime (NSDate) management in Swift :large_orange_diamond:
 * [AppVersionMonitor ★223](https://github.com/eure/AppVersionMonitor) - Monitor iOS app version easily.
 * [Sugar ★889](https://github.com/hyperoslo/Sugar) - Something sweet that goes great with your Cocoa. :large_orange_diamond:[e]
 * [Then ★1940](https://github.com/devxoul/Then) - ✨ Super sweet syntactic sugar for Swift initializers. :large_orange_diamond:[e]
 * [Kvitto ★195](https://github.com/Cocoanetics/Kvitto) - App Store Receipt Validation :large_orange_diamond:
 * [Notificationz ★57](https://github.com/SwiftKitz/Notificationz) - Helping you own NSNotificationCenter in Swift :large_orange_diamond:
 * [SwiftFoundation ★601](https://github.com/PureSwift/SwiftFoundation) - Cross-Platform, Protocol-Oriented Programming base library to complement the Swift Standard Library. (Pure Swift, Supports Linux) :large_orange_diamond:[e]
 * [libextobjc ★3724](https://github.com/jspahrsummers/libextobjc) - A Cocoa library to extend the Objective-C programming language.
 * [VersionTrackerSwift ★56](https://github.com/tbaranes/VersionTrackerSwift) - Track which versions of your app a user has previously installed. :large_orange_diamond:
 * [DeviceGuru ★213](https://github.com/InderKumarRathore/DeviceGuru) - DeviceGuru is a simple lib (Swift) to know the exact type of the device, e.g. iPhone 6 or iPhone 6s. :large_orange_diamond:
 * [AEAppVersion ★8](https://github.com/tadija/AEAppVersion) - Simple and Lightweight App Version Tracking for iOS written in Swift :large_orange_diamond:
 * [BlocksKit ★6434](https://github.com/BlocksKit/BlocksKit) - The Objective-C block utilities you always wish you had.
 * [SwiftyUtils ★168](https://github.com/tbaranes/swiftyutils) - All the reusable code that we need in each project. :large_orange_diamond:[e]
 * [RateLimit ★863](https://github.com/soffes/RateLimit) - Simple utility for only executing code every so often. :large_orange_diamond:
 * [Outlets ★128](https://github.com/phatblat/Outlets) - Utility functions for validating IBOutlet and IBAction connections :large_orange_diamond:
 * [EasyAbout ★43](https://github.com/JARMourato/EasyAbout) - A way to easily add CocoaPods licenses and App Version to your iOS App using the Settings Bundle
 * [Validated ★590](https://github.com/Ben-G/Validated) - A Swift μ-Library for Somewhat Dependent Types :large_orange_diamond:
 * [Cent ★164](https://github.com/ankurp/Cent) - Extensions for Swift Standard Types and Classes :large_orange_diamond:
 * [AssistantKit ★413](https://github.com/anatoliyv/AssistantKit) - Easy way to detect iOS device properties, OS versions and work with screen sizes. Powered by Swift. :large_orange_diamond:
 * [SwiftLinkPreview ★740](https://github.com/LeonardoCardoso/SwiftLinkPreview) - It makes a preview from an url, grabbing all the information such as title, relevant texts and images. 🔶
 * [BundleInfos ★0 ⏳1Y](https://github.com/rollmind/BundleInfos) - Simple getter for Bundle informations. like short version from bundle. 🔶
 * [YAML.framework ★185](https://github.com/mirek/YAML.framework) - Proper YAML support for Objective-C based on `LibYAML`.
 * [ReadabilityKit ★624](https://github.com/exyte/ReadabilityKit) - Metadata extractor for news, articles and full-texts in Swift. 🔶
 * [MissionControl-iOS ★99 ⏳1Y](https://github.com/appculture/MissionControl-iOS) - Super powerful remote config utility written in Swift (iOS, watchOS, tvOS, macOS) :large_orange_diamond:
 * [SwiftTweaks ★972](https://github.com/Khan/SwiftTweaks) - Tweak your iOS app without recompiling! :large_orange_diamond:
 * [UnsupportedOSVersionAlert ★9 ⏳1Y](https://github.com/caloon/UnsupportedOSVersionAlert) - Alerts users with a popup if they use an app with an unsupported version of iOS (e.g. iOS betas) :large_orange_diamond:
 * [SwiftSortUtils ★57](https://github.com/dsmatter/SwiftSortUtils) - This library takes a shot at making sorting in Swift more pleasant. It also allows you to reuse your old NSSortDescriptor instances in Swift. :large_orange_diamond:
 * [Retry ★432](https://github.com/icanzilb/Retry) - Haven't you wished for `try` to sometimes try a little harder? Meet `retry` . :large_orange_diamond:
 * [ObjectiveKit ★698](https://github.com/marmelroy/ObjectiveKit) - Swift-friendly API for Objective C runtime functions. :large_orange_diamond:
 * [MoyaSugar ★72](https://github.com/devxoul/MoyaSugar) -  Syntactic sugar for Moya. :large_orange_diamond:
 * [SwifterSwift ★4065](https://github.com/SwifterSwift/SwifterSwift) -  A handy collection of more than 400 native Swift 3 extensions to boost your productivity. :large_orange_diamond:
 * [Eject ★511 ⏳1Y](https://github.com/Raizlabs/Eject) - An eject button for Interface Builder to generate swift code. :large_orange_diamond:
 * [ContactsWrapper ★17](https://github.com/abdullahselek/ContactsWrapper) - Easy to use wrapper for both contacts and contacts group with Objective-C.
 * [XestiMonitors ★240](https://github.com/eBardX/XestiMonitors) - An extensible monitoring framework written in Swift :large_orange_diamond:
 * [OpenSourceController ★26](https://github.com/floriangbh/OpenSourceController) - The simplest way to display the libraries licences used in your application. :large_orange_diamond:
 * [App-Update-Tracker ★23 ⏳1Y](https://github.com/Stunner/App-Update-Tracker) - Easily detect and run code upon app installation or update.
 * [ExtensionalSwift ★2](https://github.com/4taras4/SwiftExtension) - Useful swift extensions in one place 🔶[e]
 * [InAppSettingsKit ★2815](https://github.com/futuretap/InAppSettingsKit) - This iOS framework allows settings to be in-app in addition to or instead of being in the Settings app.
 * [MMWormhole ★3325](https://github.com/mutualmobile/MMWormhole) - Message passing between iOS apps and extensions.
 * [DefaultStringConvertible ★129](https://github.com/jessesquires/DefaultStringConvertible) - A default CustomStringConvertible implementation for Swift types 🔶[e]
 * [FluxCapacitor ★93](https://github.com/marty-suzuki/FluxCapacitor) - FluxCapacitor makes implementing Flux design pattern easily with protocols and typealias. 🔶
 * [VTAcknowledgementsViewController ★813](https://github.com/vtourraine/VTAcknowledgementsViewController) - Ready to use “Acknowledgements”/“Licenses”/“Credits” view controller for CocoaPods.
 * [Closures ★1248](https://github.com/vhesener/Closures) - Swifty closures for UIKit and Foundation. 🔶
 * [WhatsNew ★1201](https://github.com/BalestraPatrick/WhatsNew) - Showcase new features after an app update similar to Pages, Numbers and Keynote :large_orange_diamond:

## VR
* [VR Toolkit iOS ★75 ⏳1Y](https://github.com/Aralekk/VR_Toolkit_iOS) - A sample project that provides the basics to create an interactive VR experience on iOS :large_orange_diamond:
* [360 VR Player ★1702 ⏳1Y](https://github.com/hanton/HTY360Player) - A open source, ad-free, native and universal 360 degree panorama video player for iOS.
* [simple360player ★131 ⏳1Y](https://github.com/Aralekk/simple360player_iOS) - Free & ad-free 360 VR Video Player. Flat or Stereoscopic. In Swift 2. :large_orange_diamond:
* [Swifty360Player ★24](https://github.com/abdullahselek/Swifty360Player) - iOS 360-degree video player streaming from an AVPlayer with Swift. :large_orange_diamond:

## Walkthrough / Intro / Tutorial
* [Onboard ★5871](https://github.com/mamaral/Onboard) - Easily create a beautiful and engaging onboarding experience with only a few lines of code.
* [EAIntroView ★3512](https://github.com/ealeksandrov/EAIntroView) - Highly customizable drop-in solution for introduction views.
* [MYBlurIntroductionView ★1538](https://github.com/MatthewYork/MYBlurIntroductionView) - A super-charged version of MYIntroductionView for building custom app introductions and tutorials.
* [BWWalkthrough ★2493](https://github.com/ariok/BWWalkthrough) - A class to build custom walkthroughs for your iOS App. :large_orange_diamond:
* [GHWalkThrough ★736](https://github.com/GnosisHub/GHWalkThrough) - A UICollectionView backed drop-in component for introduction views.
* [ICETutorial ★826](https://github.com/icepat/ICETutorial) - A nice tutorial like the one introduced in the Path 3.X App.
* [JazzHands ★6317](https://github.com/IFTTT/JazzHands) - Jazz Hands is a simple keyframe-based animation framework for UIKit. Animations can be controlled via gestures, scroll views, KVO, or ReactiveCocoa.
* [RazzleDazzle ★2846](https://github.com/IFTTT/RazzleDazzle) - A simple keyframe-based animation framework for iOS, written in Swift. Perfect for scrolling app intros. :large_orange_diamond:
* [Instructions ★2997](https://github.com/ephread/Instructions) - Easily add customizable coach marks into you iOS project. :large_orange_diamond:
* [SwiftyWalkthrough ★211](https://github.com/ruipfcosta/SwiftyWalkthrough) - The easiest way to create a great walkthrough experience in your apps, powered by Swift. :large_orange_diamond:
* [Gecco ★1578](https://github.com/yukiasai/Gecco) - Spotlight view for iOS. :large_orange_diamond:
* [VideoSplashKit ★1120](https://github.com/svtek/VideoSplashKit) - VideoSplashKit - UIViewController library for creating easy intro pages with background videos :large_orange_diamond:
* [Presentation ★2307](https://github.com/hyperoslo/Presentation) - Presentation helps you to make tutorials, release notes and animated pages. :large_orange_diamond:
* [AMPopTip ★1958](https://github.com/andreamazz/AMPopTip) - An animated popover that pops out a given frame, great for subtle UI tips and onboarding.
* [AlertOnboarding ★352](https://github.com/PhilippeBoisney/AlertOnboarding) - A simple and handsome AlertView for onboard your users in your amazing world. :large_orange_diamond:
* [EasyTipView ★1735](https://github.com/teodorpatras/EasyTipView) - Fully customisable tooltip view in Swift. :large_orange_diamond:
* [paper-onboarding ★2061](https://github.com/Ramotion/paper-onboarding) - PaperOnboarding is a material design slider :large_orange_diamond:
* [InfoView ★35 ⏳1Y](https://github.com/anatoliyv/InfoView) - Swift based simple information view with pointed arrow. :large_orange_diamond:
* [Intro ★25](https://github.com/nbolatov/Intro) - An iOS framework to easily create simple animated walkthrough, written in Swift. :large_orange_diamond:
* [AwesomeSpotlightView ★42](https://github.com/aleksandrshoshiashvili/AwesomeSpotlightView) - Tool to create awesome tutorials or educate user to use application. Or just highlight something on screen. Written in Swift. :large_orange_diamond:
* [SwiftyOnboard ★592](https://github.com/juanpablofernandez/SwiftyOnboard) - A simple way to add onboarding to your project. :large_orange_diamond:
* [WVWalkthroughView ★22](https://github.com/praagyajoshi/WVWalkthroughView) - Utility to easily create walkthroughs to help with user onboarding.
* [SwiftyGuideOverlay ★10](https://github.com/saeid/SwiftyGuideOverlay) - Easy and quick way to show intro / instructions over app UI without any additional images in real-time!. 🔶
* [SwiftyOnboardVC ★8](https://github.com/chaser79/SwiftyOnboardVC) - Lightweight walkthrough controller thats uses view controllers as its subviews making the customization endless. 🔶
* [PVOnboardKit ★41](https://github.com/vpeschenkov/PVOnboardKit) - Framework that allows you to add your own walkthrough/intro/tutorial into your app.

## WebSocket
* [SocketRocket ★7285](https://github.com/facebook/SocketRocket) - A conforming Objective-C WebSocket client library.
* [socket.io-client-swift ★2726](https://github.com/socketio/socket.io-client-swift) - Socket.IO-client for iOS/macOS. :large_orange_diamond:
* [SwiftWebSocket ★897](https://github.com/tidwall/SwiftWebSocket) - High performance WebSocket client library for Swift, iOS and macOS. :large_orange_diamond:
* [Starscream ★3291](https://github.com/daltoniam/Starscream) - Websockets in swift for iOS and macOS :large_orange_diamond:
* [SwiftSocket ★680](https://github.com/swiftsocket/SwiftSocket) - simple socket library for apple swift lang. :large_orange_diamond:
* [Socks ★479](https://github.com/vapor/sockets) - Pure-Swift Sockets: TCP, UDP; Client, Server; Linux, macOS :large_orange_diamond:
* [SwifterSockets ★55](https://github.com/Balancingrock/SwifterSockets) - A collection of socket utilities in Swift for OS-X and iOS :large_orange_diamond:
* [Swift-ActionCableClient ★107](https://github.com/danielrhodes/Swift-ActionCableClient) - ActionCable is a new WebSocket server being released with Rails 5 which makes it easy to add real-time features to your app. :large_orange_diamond:

#### GCD
 * [GCDKit ★283](https://github.com/JohnEstropia/GCDKit) - Grand Central Dispatch simplified with Swift. :large_orange_diamond:
 * [Async ★4151](https://github.com/duemunk/Async) - Syntactic sugar in Swift for asynchronous dispatches in Grand Central Dispatch :large_orange_diamond:
 * [SwiftSafe ★159](https://github.com/nodes-ios/SwiftSafe) - Thread synchronization made easy :large_orange_diamond:
 * [YYDispatchQueuePool ★289](https://github.com/ibireme/YYDispatchQueuePool) - iOS utility class to manage global dispatch queue.
 * [AlecrimAsyncKit ★66](https://github.com/Alecrim/AlecrimAsyncKit) - Bringing async and await to Swift world with some flavouring. :large_orange_diamond:
 * [GrandSugarDispatch ★31 ⏳1Y](https://github.com/jessesquires/GrandSugarDispatch) - Syntactic sugar for Grand Central Dispatch (GCD) :large_orange_diamond:
 * [Threader ★39 ⏳1Y](https://github.com/mitchtreece/Threader) - Pretty GCD calls and easier code execution.
 * [Dispatch ★173](https://github.com/JARMourato/Dispatch) - Just a tiny library to make using GCD easier and intuitive :large_orange_diamond:
 * [GCDTimer ★164](https://github.com/hemantasapkota/GCDTimer) - Well tested Grand Central Dispatch (GCD) Timer in Swift. :large_orange_diamond:
 * [Chronos-Swift ★249](https://github.com/comyar/Chronos-Swift) - :hourglass: Grand Central Dispatch Utilities :large_orange_diamond:
 * [Me ★193](https://github.com/pascalbros/Me) - A super slim solution to the nested asynchronous computations. :large_orange_diamond:
 * [SwiftyTask ★10](https://github.com/CR-Creations/SwiftyTask) - An extreme queuing system with high performance for managing all task in app with closure. :large_orange_diamond:

# Project setup
* [crafter ★543](https://github.com/krzysztofzablocki/crafter) - CLI that allows you to configure iOS project's template using custom DSL syntax, simple to use and quite powerful.
* [liftoff ★1559](https://github.com/liftoffcli/liftoff) - Another CLI for creating iOS projects.
* [amaro ★385](https://github.com/crushlovely/Amaro) - iOS Boilerplate full of delights.
* [chairs ★233 ⏳2Y](https://github.com/orta/chairs) - Swap around your iOS Simulator Documents
* [SwiftPlate ★1306](https://github.com/JohnSundell/SwiftPlate) - Easily generate cross platform Swift framework projects from the command line. :large_orange_diamond:
* [xclint ★63](https://github.com/xcodeswift/xclint) - Validate the state of your Xcode projects.
* [xcproj ★485](https://github.com/xcodeswift/xcproj) - Read and update Xcode projects.

# Dependency / Package Manager
* [CocoaPods](https://cocoapods.org/) - CocoaPods is the dependency manager for Objective-C projects. It has thousands of libraries and can help you scale your projects elegantly.
* [Xcode Maven](http://sap-production.github.io/xcode-maven-plugin/site/) - The Xcode Maven Plugin can be used in order to run Xcode builds embedded in a Maven lifecycle.
* [Carthage ★10432](https://github.com/Carthage/Carthage) - A simple, decentralized dependency manager for Cocoa. :large_orange_diamond:
* [SWM (Swift Modules) ★53 ⏳3Y](https://github.com/jankuca/swm) - A package/dependency manager for Swift projects similar to npm (node.js package manager) or bower (browser package manager from Twitter). Does not require the use of Xcode. :large_orange_diamond:
* [Alcatraz](http://alcatraz.io/) - The package manager for Xcode.
* [CocoaSeeds ★339](https://github.com/devxoul/CocoaSeeds) - Git Submodule Alternative for Cocoa.
* [swift-package-manager ★5873](https://github.com/apple/swift-package-manager) - The Package Manager for the Swift Programming Language :large_orange_diamond:
* [punic ★242](https://github.com/schwa/punic) - Clean room reimplementation of Carthage tool

# Tools
* [Shark ★285](https://github.com/kaandedeoglu/Shark) - Swift Script that transforms the .xcassets folder into a type safe enum. :large_orange_diamond:
* [SBConstants ★309](https://github.com/paulsamuels/SBConstants) - Generate a constants file by grabbing identifiers from storyboards in a project.
* [R.swift ★4301](https://github.com/mac-cain13/R.swift) - Tool to get strong typed, autocompleted resources like images, cells and segues in your Swift project. :large_orange_diamond:
* [SwiftGen ★3994](https://github.com/SwiftGen/SwiftGen) - A collection of Swift tools to generate Swift code (enums for your assets, storyboards, Localizable.strings and UIColors). :large_orange_diamond:
* [Blade ★779](https://github.com/jondot/blade) - Generate Xcode image catalogs for iOS / macOS app icons, universal images, and more.
* [Retini ★104](https://github.com/terwanerik/Retini) - A super simple retina (2x, 3x) image converter.
* [Jazzy ★4839](https://github.com/realm/jazzy) - Soulful docs for Swift & Objective-C. :large_orange_diamond:
* [appledoc ★3740](https://github.com/tomaz/appledoc) - ObjectiveC code Apple style documentation set generator.
* [Laurine ★1043](https://github.com/JiriTrecak/Laurine) - Laurine - Localization code generator written in Swift. Sweet! :large_orange_diamond:
* [StoryboardMerge ★204](https://github.com/marcinolawski/StoryboardMerge) - Xcode storyboards diff and merge tool.
* [ai2app ★76](https://github.com/metasmile/ai2appiconset) - Creating AppIcon sets from Adobe Illustrator (all supported formats).
* [ViewMonitor ★711](https://github.com/daisuke0131/ViewMonitor) - ViewMonitor can measure view positions with accuracy. :large_orange_diamond:
* [abandoned-strings ★90](https://github.com/ijoshsmith/abandoned-strings) - Command line program that detects unused resource strings in an iOS or macOS application. :large_orange_diamond:
* [swiftenv ★1391](https://github.com/kylef/swiftenv) - swiftenv allows you to easily install, and switch between multiple versions of Swift. :large_orange_diamond:
* [Misen ★120](https://github.com/tasanobu/Misen) - Script to support easily using Xcode Asset Catalog in Swift. :large_orange_diamond:[e]
* [git-xcp ★11](https://github.com/metasmile/git-xcp) - A Git plugin for versioning workflow of real-world Xcode project. fastlane's best friend.
* [WatchdogInspector ★438](https://github.com/tapwork/WatchdogInspector) - Shows your current framerate (fps) in the status bar of your iOS app
* [Cichlid ★253 ⏳1Y](https://github.com/dealforest/Cichlid) - automatically delete the current project's DerivedData directories :large_orange_diamond:
* [Delta ★246 ⏳1Y](https://github.com/thoughtbot/Delta) - Managing state is hard. Delta aims to make it simple. :large_orange_diamond:
* [SwiftLintXcode ★250](https://github.com/ypresto/SwiftLintXcode) - An Xcode plug-in to format your code using SwiftLint. :large_orange_diamond:
* [XCSwiftr ★320](https://github.com/dzenbot/XCSwiftr) - An Xcode Plugin to convert Objective-C to Swift :large_orange_diamond:
* [SwiftKitten ★129](https://github.com/johncsnyder/SwiftKitten) - Swift autocompleter for Sublime Text, via the adorable SourceKitten framework :large_orange_diamond:
* [Kin ★177](https://github.com/Karumi/Kin) - Have you ever found yourself undoing a merge due to a broken Xcode build? Then Kin is your tool. It will parse your project configuration file and detect errors. :large_orange_diamond:
* [AVXCAssets-Generator ★284](https://github.com/angelvasa/AVXCAssets-Generator) - AVXCAssets Generator takes path for your assets images and creates appiconset and imageset for you in just one click :large_orange_diamond:
* [Peek ★1155](https://github.com/shaps80/Peek) - Take a Peek at your application. :large_orange_diamond:
* [SourceKitten ★1147](https://github.com/jpsim/SourceKitten) - An adorable little framework and command line tool for interacting with SourceKit. :large_orange_diamond:
* [Localizations ★94](https://github.com/athiercelin/localizations) - macOS app that manages localizations of Xcode projects. :large_orange_diamond:
* [xcbuild ★1376](https://github.com/facebook/xcbuild) - Xcode-compatible build tool.
* [XcodeIssueGenerator ★142 ⏳1Y](https://github.com/doubleencore/XcodeIssueGenerator) - An executable that can be placed in a Run Script Build Phase that marks comments like // TODO: or // SERIOUS: as warnings or errors so they display in the Xcode Issue Navigator. :large_orange_diamond:
* [SwiftCompilationPerformanceReporter ★148 ⏳1Y](https://github.com/tumblr/SwiftCompilationPerformanceReporter) - Generate automated reports for slow Swift compilation paths in specific targets :large_orange_diamond:
* [BuildTimeAnalyzer ★2107](https://github.com/RobertGummesson/BuildTimeAnalyzer-for-Xcode) - Build Time Analyzer for Swift :large_orange_diamond:
* [Duration ★298](https://github.com/SwiftStudies/Duration) - A simple Swift package for measuring and reporting the time taken for operations :large_orange_diamond:
* [Benchmark ★62](https://github.com/WorldDownTown/Benchmark) - The Benchmark⏲ module provides methods to measure and report the time used to execute Swift code. :large_orange_diamond:
* [MBAssetsImporter ★68 ⏳1Y](https://github.com/MatiBot/MBAssetsImporter) - Import assets from Panoramio or from your macOS file system with their metadata to your iOS simulator (Swift 2.0) :large_orange_diamond:
* [Realm Browser ★456](https://github.com/realm/realm-browser-osx) - Realm Browser is a macOS utility to open and modify realm database files.
* [SuperDelegate ★387](https://github.com/square/SuperDelegate) – SuperDelegate provides a clean application delegate interface and protects you from bugs in the application lifecycle.
* [fastlane-plugin-appicon ★170](https://github.com/KrauseFx/fastlane-plugin-appicon) - Generate required icon sizes and iconset from a master application icon.
* [infer ★7613](https://github.com/facebook/infer) - A static analyzer for Java, C and Objective-C.
* [PlayNow ★90 ⏳1Y](https://github.com/marcboquet/PlayNow) - Small app that creates empty Swift playground files and opens them with Xcode. :large_orange_diamond:
* [Xtrace ★1681](https://github.com/johnno1962/Xtrace) - Trace Objective-C method calls by class or instance
* [xcenv ★208 ⏳1Y](https://github.com/xcenv/xcenv) - Groom your Xcode environment.
* [playgroundbook ★212](https://github.com/playgroundbooks/playgroundbook) - Tool for Swift Playground books
* [Ecno ★63](https://github.com/xmartlabs/Ecno) - Ecno is a task state manager built on top of UserDefaults in pure Swift 3. :large_orange_diamond:
* [ipanema ★5](https://github.com/toshi0383/ipanema) - ipanema analyzes and prints useful information from *.ipa file.
* [pxctest ★771](https://github.com/plu/pxctest) - Parallel XCTest - Execute XCTest suites in parallel on multiple iOS Simulators.
* [IBM Swift Sandbox](https://swift.sandbox.bluemix.net) - The IBM Swift Sandbox is an interactive website that lets you write Swift code and execute it in a server environment – on top of Linux! :large_orange_diamond:
* [FBSimulatorControl ★2107](https://github.com/facebook/FBSimulatorControl) - A macOS library for managing and manipulating iOS Simulators
* [Nomad](http://nomad-cli.com) - Suite of command line utilities & libraries for sending APNs, create & distribute *.ipa*, verify In-App-Purchase receipt and more.
* [Cookiecutter ★419](https://github.com/JetpackSwift/FrameworkTemplate) - A template for new Swift iOS / tvOS / watchOS / macOS Framework project ready with travis-ci, cocoapods, Carthage, SwiftPM and a Readme file :large_orange_diamond:
* [Sourcery ★2768](https://github.com/krzysztofzablocki/Sourcery) - A tool that brings meta-programming to Swift, allowing you to code generate Swift code. :large_orange_diamond:
* [AssetChecker 👮 ★50](https://github.com/freshOS/AssetChecker) - Keeps your Assets.xcassets files clean and emits warnings when something is suspicious. :large_orange_diamond:
* [PlayAlways ★384](https://github.com/insidegui/PlayAlways) - Create Xcode playgrounds from your menu bar :large_orange_diamond:
* [GDPerformanceView-Swift ★1574](https://github.com/dani-gavrilov/GDPerformanceView-Swift) - Shows FPS, CPU usage, app and iOS versions above the status bar and report FPS and CPU usage via delegate. :large_orange_diamond:
* [Traits ★860](https://github.com/krzysztofzablocki/Traits) - Library for a real-time design and behavior modification of native iOS apps without recompiling (code and interface builder changes are supported). :large_orange_diamond:
* [Struct](https://www.get-struct.tools) - A tool for iOS and Mac developers to automate the creation and management of Xcode projects.
* [Nori ★286](https://github.com/yukiasai/Nori) - Easier to apply code based style guide to storyboard. :large_orange_diamond:
* [Attabench ★582](https://github.com/attaswift/Attabench) - Microbenchmarking app for Swift with nice log-log plots :large_orange_diamond:
* [Gluten ★9](https://github.com/wilbertliu/Gluten) - Nano library to unify XIB and it's code. :large_orange_diamond:
* [LicensePlist ★1005](https://github.com/mono0926/LicensePlist) - A license list generator of all your dependencies for iOS applications. :large_orange_diamond:
* [Swizzlean ★80](https://github.com/rbaumbach/Swizzlean) - An Objective-C Swizzle Helper Class
* [AppDevKit ★1350](https://github.com/yahoo/AppDevKit) - AppDevKit is an iOS development library that provides developers with useful features to fulfill their everyday iOS app development needs.
* [Tweaks ★4632](https://github.com/facebook/Tweaks) - An easy way to fine-tune, and adjust parameters for iOS apps in development.
* [FengNiao ★1327](https://github.com/onevcat/FengNiao) - A command line tool for cleaning unused resources in Xcode. :large_orange_diamond:
* [LifetimeTracker ★1407](https://github.com/krzysztofzablocki/LifetimeTracker) - Find retain cycles / memory leaks sooner. :large_orange_diamond:
* [Plank ★359](https://github.com/pinterest/plank) - A tool for generating immutable model objects.
* [Lona ★2605](https://github.com/airbnb/Lona) - A tool for defining design systems and using them to generate cross-platform UI code, Sketch files, images, and other artifacts.

# Rapid Development
* [Playgrounds ★2347 ⏳1Y](https://github.com/krzysztofzablocki/Playgrounds) - Playgrounds for Objective-C for extremely fast prototyping / learning.
* [MMBarricade ★354](https://github.com/mutualmobile/MMBarricade) - Runtime configurable local server for iOS apps.
* [STV Framework](http://www.sensiblecocoa.com) - Native visual iOS development.
* [swiftmon ★2](https://github.com/dimpiax/swiftmon) - swiftmon restarts your swift application in case of any file change.

# Injection
* [dyci ★1065](https://github.com/DyCI/dyci-main) - Code injection tool.
* [injectionforxcode ★4960](https://github.com/johnno1962/injectionforxcode) - Code injection including Swift.
* [Swinject ★1975](https://github.com/Swinject/Swinject) - Dependency injection framework for Swift
* [Reliant ★53 ⏳1Y](https://github.com/appfoundry/Reliant) - Nonintrusive Objective-C dependency injection.
* [Kraken ★1](https://github.com/sabirvirtuoso/Kraken) - A Dependency Injection Container for Swift with easy-to-use syntax.
* [Cleanse ★968](https://github.com/square/Cleanse) - Lightweight Swift Dependency Injection Framework by Square. :large_orange_diamond:
* [Typhoon ★2287](https://github.com/appsquickly/Typhoon) - Powerful dependency injection (Objective-C & Swift).
* [Perform ★249](https://github.com/thoughtbot/Perform) - Easy dependency injection for storyboard segues. :large_orange_diamond:
* [Alchemic ★11](https://github.com/drekka/Alchemic) - Advanced, yet simple to use DI framework for Objective-C.
* [Guise ★23](https://github.com/prosumma/Guise) - An elegant, flexible, type-safe dependency resolution framework for Swift :large_orange_diamond:

# Deployment / Distribution
* [fastlane ★19224](https://github.com/fastlane/fastlane) - Connect all iOS deployment tools into one streamlined workflow.
* [deliver](https://github.com/fastlane/fastlane/tree/master/deliver) - Upload screenshots, metadata and your app to the App Store using a single command.
* [snapshot](https://github.com/fastlane/fastlane/tree/master/snapshot) Automate taking localized screenshots of your iOS app on every device.
* [buddybuild](https://www.buddybuild.com/) - A mobile iteration platform - build, deploy, and collaborate.
* [Bitrise](https://www.bitrise.io) Mobile Continuous Integration & Delivery with dozens of integrations to build, test, deploy and collaborate.
* [watchbuild ★62](https://github.com/fastlane/watchbuild) - Get a notification once your iTunes Connect build is finished processing.
* [Crashlytics](https://try.crashlytics.com/) - A crash reporting and beta testing service.
* [TestFlight Beta Testing](https://developer.apple.com/testflight/) - The beta testing service hosted on iTunes Connect (requires iOS 8 or later).
* [HockeyApp](https://www.hockeyapp.net) - With HockeyApp, you can distribute beta versions of your app, collect live crash reports, get feedback from users, and analyze test coverage.
* [boarding ★588](https://github.com/fastlane/boarding) - Instantly create a simple signup page for TestFlight beta testers.
* [HockeyKit ★2191](https://github.com/bitstadium/HockeyKit) - A software update kit.
* [Boombox.io](https://boombox.io/) - Sign up TestFlight beta testers on your website. Embeddable and hosted TestFlight beta sign-up forms
* [Rollout.io](https://rollout.io/) - SDK to patch, fix bugs, modify and manipulate native apps (Obj-c & Swift) in real-time.
* [AppLaunchpad](https://theapplaunchpad.com/) - Free App Store screenshot builder.
* [LaunchKit ★1823](https://github.com/LaunchKit/LaunchKit) - A set of web-based tools for mobile app developers, now open source!
* [Instabug](https://instabug.com) - In-app feedback, Bug and Crash reporting, Fix Bugs Faster through user-steps, video recordings, screen annotation, network requests logging.

# App Store
* [Average App Store Review Times](http://appreviewtimes.com) This site tracks the average App Store review times for both the iOS and the Mac App Store using data crowdsourced from iOS and Mac developers.
* [Apple's Common App Rejections Styleguide](https://developer.apple.com/app-store/review/rejections/)  Highlighted some of the most common issues that cause apps to get rejected.
* [Free App Store Optimization Tool](https://www.mobileaction.co) Lets you track your App Store visibility in terms of keywords and competitors.
* [App Release Checklist](https://github.com/oisin/app-release-checklist/blob/master/checklist.md) - A checklist to pore over before you ship that amazing app that has taken ages to complete, but you don't want to rush out in case you commit a schoolboy error that will end up making you look dumber than you are.
* [Harpy ★2409](https://github.com/ArtSabintsev/Harpy) - Notify users when a new version of your iOS app is available, and prompt them with the App Store link.
* [iRate ★4323](https://github.com/nicklockwood/iRate) - A handy class that prompts users of your iPhone or Mac App Store app to rate your application after using it for a while. Similar to Appirater, but with a simpler, cleaner interface and automatic support for iOS fast application switching.
* [appirater ★4505](https://github.com/arashpayan/appirater) - A utility that reminds your iPhone app's users to review the app.
* [Siren ★2221](https://github.com/ArtSabintsev/Siren) - Notify users when a new version of your app is available and prompt them to upgrade. :large_orange_diamond:
* [Appstore Review Guidelines ★5 ⏳1Y](https://github.com/aashishtamsya/Appstore-Review-Guidelines) - A curated list of points which a developer has to keep in mind before submitting his/her application on appstore for review.

# Xcode

#### Extensions (Xcode 8+)
* [CleanClosureXcode ★149 ⏳1Y](https://github.com/BalestraPatrick/CleanClosureXcode) - An Xcode Source Editor extension to clean the closure syntax. :large_orange_diamond:
* [xTextHandler ★1378 ⏳1Y](https://github.com/cyanzhong/xTextHandler) - Xcode Source Editor Extension Toolset (Plugins for Xcode 8) :large_orange_diamond:
* [SwiftInitializerGenerator ★524](https://github.com/Bouke/SwiftInitializerGenerator) - Xcode 8 Source Code Extension to Generate Swift Initializers. :large_orange_diamond:
* [XcodeEquatableGenerator ★166 ⏳1Y](https://github.com/sergdort/XcodeEquatableGenerator) - Xcode 8 Source Code Extension will generate conformance to Swift Equatable protocol based on type and fields selection. :large_orange_diamond:
* [Import ★693](https://github.com/markohlebar/Import) - Xcode extension for adding imports from anywhere in the code. :large_orange_diamond:
* [Mark ★112 ⏳1Y](https://github.com/velyan/Mark) - Xcode extension for generating MARK comments. :large_orange_diamond:
* [XShared ★69](https://github.com/Otbivnoe/XShared) - Xcode extension which allows you copying the code with special formatting quotes for social (Slack, Telegram). :large_orange_diamond:
* [XGist ★51](https://github.com/Bunn/Xgist) - Xcode extension which allows you to send your text selection or entire file to Github's Gist and automatically copy the Gist URL into your Clipboard. :large_orange_diamond:
* [Swiftify](https://objectivec2swift.com/) - Objective-C to Swift online code converter and Xcode extension. :large_orange_diamond:

#### Plugins
* [FuzzyAutocompletePlugin ★3390](https://github.com/FuzzyAutocomplete/FuzzyAutocompletePlugin) - A Xcode 5+ plugin that adds more flexible autocompletion rather than just prefix-matching.
* [SCXcodeMiniMap ★1040](https://github.com/stefanceriu/SCXcodeMiniMap) - SCXcodeMiniMap is a plugin that adds a source editor MiniMap to Xcode.
* [Show in Github ★242 ⏳1Y](https://github.com/larsxschneider/ShowInGitHub) - Xcode plugin to open the GitHub page of the commit of the currently selected line in the editor window.
* [BBUFullIssueNavigator ★247 ⏳1Y](https://github.com/neonichu/BBUFullIssueNavigator) - Xcode plugin for showing all issue content in the issue navigator.
* [BBUDebuggerTuckAway ★701 ⏳1Y](https://github.com/neonichu/BBUDebuggerTuckAway) - Xcode plugin for auto-hiding the debugger once you start typing in the source code editor.
* [SCXcodeSwitchExpander ★670](https://github.com/stefanceriu/SCXcodeSwitchExpander) - SCXcodeSwitchExpander is a small Xcode plugin that expands switch statements by inserting missing cases.
* [VVDocumenter-Xcode ★8448](https://github.com/onevcat/VVDocumenter-Xcode) - Xcode plug-in which helps you write Javadoc style documents easier.
* [XAlign ★2734](https://github.com/qfish/XAlign) - An amazing Xcode plugin to align regular code. It can align anything by using custom alignment patterns.
* [CocoaPods Xcode Plugin ★2389 ⏳1Y](https://github.com/kattrali/cocoapods-xcode-plugin) - Dependency management helper for your CocoaPods, right in Xcode.
* [KSImageNamed-Xcode ★4295](https://github.com/ksuther/KSImageNamed-Xcode) - Xcode plug-in that provides autocomplete for imageNamed: calls.
* [ColorSense-for-Xcode ★2912 ⏳1Y](https://github.com/omz/ColorSense-for-Xcode) - Plugin for Xcode to make working with colors more visual.
* [Backlight-for-XCode ★436 ⏳1Y](https://github.com/limejelly/Backlight-for-XCode) - Highlights the current editing line in Xcode
* [KPRunEverywhereXcodePlugin ★324](https://github.com/kitschpatrol/KPRunEverywhereXcodePlugin) - An Xcode plugin to build and run an app across multiple iOS devices with one click.
* [RevealPlugin ★235 ⏳1Y](https://github.com/shjborage/Reveal-Plugin-for-Xcode) - Plugin for Xcode to integrate the Reveal App to your project automatic.
* [RealmPlugin](https://realm.io/docs/objc/0.81.0/#xcode-plugin)- Xcode plugin to generate new Realm models.
* [AdjustFontSize ★285 ⏳1Y](https://github.com/zats/AdjustFontSize-Xcode-Plugin) - Instant font size adjustment with `⌘ +` / `⌘ -`.
* [Rephrase](https://www.rephrase.io) - Localise from Xcode.
* [XCActionBar ★1227](https://github.com/pdcgomes/XCActionBar) - "Alfred for Xcode" plugin.
* [QuickJump ★30](https://github.com/wiruzx/QuickJump) - Quick code navigation for Xcode.
* [CATweaker ★706 ⏳1Y](https://github.com/keefo/CATweaker) - Plugin for creating beautiful CAMediaTimingFunction curve.
* [XcodeWay ★332](https://github.com/onmyway133/XcodeWay) - An Xcode plugin that makes navigating to many places easier (available via Alcatraz).
* [GitDiff ★876](https://github.com/johnno1962/GitDiff) - Highlights deltas against git repo in Xcode.
* [MCLog ★608](https://github.com/yuhua-chen/MCLog) - Xcode plugin for filtering the console area.
* [XToDo ★1592 ⏳1Y](https://github.com/trawor/XToDo) - Dialog with list of all TODO, FIXME, ??? and !!! in the project.
* [CopyIssue ★179 ⏳1Y](https://github.com/hanton/CopyIssue-Xcode-Plugin) - Makes Copy Xcode Issue Description Easy.
* [RTImageAssets ★2404](https://github.com/rickytan/RTImageAssets) - A Xcode plugin to automatically generate all the App icons needed.
* [BBUncrustifyPlugin-Xcode ★1209](https://github.com/benoitsan/BBUncrustifyPlugin-Xcode) - Xcode plugin to format source code using ClangFormat or Uncrustify.
* [Aviator ★31 ⏳1Y](https://github.com/marksands/Aviator) - Xcode plugin that brings ⇧⌘T (source/test toggle) from AppCode over to Xcode.
* [JumpMarks ★55](https://github.com/merrickp/JumpMarks) - Navigate your code files with numbered bookmarks.
* [XCSnippetr ★95](https://github.com/dzenbot/XCSnippetr) - An Xcode Plugin to upload code snippets directly into Slack and Gist.
* [Peckham ★732 ⏳1Y](https://github.com/markohlebar/Peckham) - Add #import-s from anywhere in the code.
* [MLAutoReplace ★244](https://github.com/molon/MLAutoReplace) - Xcode plugin, Re-Intent, make you write code more quickly.
* [AutoHighlightSymbol ★77 ⏳1Y](https://github.com/chiahsien/AutoHighlightSymbol) - A Xcode plugin to add highlight to the instances of selected symbol.
* [Reveal-In-GitHub ★270 ⏳1Y](https://github.com/lzwjava/Reveal-In-Github) - Xcode plugin to let you jump to GitHub History, Blame, PRs, Issues, Notifications of any GitHub repo with one shortcut.
* [CleanHeaders-Xcode ★78 ⏳1Y](https://github.com/insanoid/CleanHeaders-Xcode) - A simple iSort like header sorting and duplicate removal plugin for Xcode, makes your headers look more organized.
* [Luft ★183](https://github.com/k0nserv/luft) - The Xcode Plugin that helps you write lighter view controllers
* [You-Can-Do-It ★232 ⏳1Y](https://github.com/orta/You-Can-Do-It) - Is learning a new language getting you down? Worry not, this Xcode plugin will keep you motivated.
* [PreciseCoverage ★172 ⏳1Y](https://github.com/zats/PreciseCoverage) - Make Xcode code coverage more informative
* [AutoIndentWithSave ★54](https://github.com/ThilinaHewagama/AutoIndentWithSave) Xcode plugin which indent the source code when save
* [Refactorator ★984](https://github.com/johnno1962/Refactorator) - Xcode Plugin that Refactors Swift & Objective-C :large_orange_diamond:
* [VWInstantRun ★1063](https://github.com/wangshengjia/VWInstantRun) - An Xcode plugin let you build & run your selected lines of code in Xcode without running the whole project, you'll have the output instantly in your Xcode console. :large_orange_diamond:
* [TTPasteHistory ★31 ⏳1Y](https://github.com/tutumagi/TTPasteHistory) - A Xcode plugin. Recording you copy-and-paste history easily to write the code
* [xSendIssue ★4 ⏳1Y](https://github.com/hungri-yeti/xSendIssue) - Plugin for Xcode to submit GitHub issues directly from within Xcode.
* [Swimat ★777](https://github.com/Jintin/Swimat) - An Xcode formatter plug-in to format your swift code.
* [Fastlane-Plugin ★35](https://github.com/RishabhTayal/Fastlane-Plugin) - The awesome Fastlane tools brought into your Xcode.
* [Gradle Xcode plugin](https://openbakery.org/gxp/) - Build iOS or macOS Projects using Gradle.
* [SYXcodeIconVersion ★95](https://github.com/dvkch/SYXcodeIconVersion) - This Xcode plugin shows Xcode app version in the Dock and App Switcher icon.
* [Gradle ★366](https://github.com/openbakery/gradle-xcodePlugin) - gradle xcodePlugin to build iOS and Mac projects.
* [HOStringSense-for-Xcode ★724 ⏳1Y](https://github.com/holtwick/HOStringSense-for-Xcode) - Plugin for Xcode to make perfect editing regular expressions, multi line texts, inline HTML and many more use cases. Also provides quick feedback on string length.
* [FastStub-Xcode ★494 ⏳1Y](https://github.com/music4kid/FastStub-Xcode) - Xcode Plugin helps you find missing methods in your class header, protocols, and super class, also makes fast inserting.
* [JSPatchX ★740](https://github.com/bang590/JSPatchX) - JSPatch bridge Objective-C and Javascript using the Objective-C runtime. You can call any Objective-C class and method in JavaScript by just including a small engine. JSPatch is generally use for hotfix iOS App.
* [Dash](https://kapeli.com/dash) - Dash is a great documentation browser which integrates closely into Xcode with its plugin.
* [SFJumpToLine ★10 ⏳2Y](https://github.com/sferrini/SFJumpToLine) - Xcode plugin that moves the instruction pointer to the selected line
* [ClangFormat-Xcode ★2568](https://github.com/travisjeffery/ClangFormat-Xcode) - An Xcode plug-in to format your code using Clang's format tools.
* [update_xcode_plugins ★974](https://github.com/inket/update_xcode_plugins) - No more messing with plugin UUIDs; Plugins on Xcode 8!
* [MakeXcodeGr8Again ★751](https://github.com/fpg1503/MakeXcodeGr8Again) - Xcode + Plugins = :blue_heart: :large_orange_diamond:

#### Themes
* [Dracula Theme ★12 ⏳1Y](https://github.com/zenorocha/dracula-theme) - A dark theme for Xcode.
* [Xcode themes list ★1789](https://github.com/hdoria/xcode-themes) - Color themes for Xcode.
* [Solarized-Dark-for-Xcode ★277](https://github.com/ArtSabintsev/Solarized-Dark-for-Xcode) - Solarized Dark Theme for Xcode 5.
* [WWDC2016 Xcode Color Scheme ★362 ⏳1Y](https://github.com/cargath/WWDC2016-Xcode-Color-Scheme) - A color scheme for Xcode based on the WWDC 2016 invitation.

#### Other Xcode

* [awesome-xcode-scripts ★30](https://github.com/aashishtamsya/awesome-xcode-scripts) - A curated list of useful xcode scripts 📝.
* [Synx ★5661](https://github.com/venmo/synx) - A command-line tool that reorganizes your Xcode project folder to match your Xcode groups.
* [dsnip ★11 ⏳2Y](https://github.com/Tintenklecks/IBDelegateCodesippets) - Tool to generate (native) Xcode code snippets from all protocols/delegate methods of UIKit (UITableView, ...)
* [SBShortcutMenuSimulator ★1784 ⏳1Y](https://github.com/DeskConnect/SBShortcutMenuSimulator) - 3D Touch shortcuts in the Simulator
* [awesome-gitignore-templates ★10](https://github.com/aashishtamsya/awesome-gitignore-templates) - A collection of swift, objective-c, android and many more langugages .gitignore templates 📝.
* [swift-project-template ★27](https://github.com/artemnovichkov/swift-project-template) - Template for iOS Swift project generation.
* [Swift-VIPER-Module ★223](https://github.com/Juanpe/Swift-VIPER-Module) - Xcode template for create modules with VIPER Architecture written in Swift 3 :large_orange_diamond:
* [ViperC ★35](https://github.com/abdullahselek/ViperC) - Xcode template for VIPER Architecture for both Objective-C and Swift :large_orange_diamond:
* [Microfeatures](https://github.com/microfeatures) - Architectural approach to structure your Xcode projects. :large_orange_diamond:
* [XcodeCodeSnippets ★12](https://github.com/ismetanin/XcodeCodeSnippets) - A set of code snippets for iOS development, includes code and comments snippets.

# Reference
* [Swift Cheat Sheet ★703](https://github.com/iwasrobbed/Swift-CheatSheet) - A quick reference cheat sheet for common, high level topics in Swift. :large_orange_diamond:
* [Objective-C Cheat Sheet ★951](https://github.com/iwasrobbed/Objective-C-CheatSheet) - A quick reference cheat sheet for common, high level topics in Objective-C.
* [SwiftSnippets ★100](https://github.com/hyperoslo/SwiftSnippets) - A collection of Swift snippets to be used in Xcode
* [App Store Checklist ★19 ⏳1Y](https://github.com/whitef0x0/app-store-checklist) - A checklist of what to look for before submitting your app to the App Store.
* [whats-new-in-swift-4 ★1788](https://github.com/ole/whats-new-in-swift-4) - An Xcode playground showcasing the new features in Swift 4.0. :large_orange_diamond:
* [WWDC17-Recap ★95](https://github.com/erenkabakci/WWDC17-Recap) - Markdown collection repo for the sessions at WWDC17.

# Style Guides
* [NY Times - Objective C Style Guide ★4575](https://github.com/NYTimes/objective-c-style-guide) - The Objective-C Style Guide used by The New York Times.
* [raywenderlich Style Guide ★2698](https://github.com/raywenderlich/objective-c-style-guide) - A style guide that outlines the coding conventions for raywenderlich.com.
* [Github Objective-C Style Guide ★1665](https://github.com/github/objective-c-style-guide) - Style guide & coding conventions for Objective-C projects.
* [Objective-C Coding Convention and Best Practices](https://gist.github.com/soffes/812796) - Gist with coding conventions.
* [Swift Style Guide by @raywenderlich ★7927](https://github.com/raywenderlich/swift-style-guide) - The official Swift style guide for raywenderlich.com. :large_orange_diamond:
* [Spotify Objective-C Coding Style ★201](https://github.com/spotify/ios-style) - Guidelines for iOS development in use at Spotify.
* [Github - Style guide & coding conventions for Swift projects ★4395](https://github.com/github/swift-style-guide) - A guide to our Swift style and conventions by @github. :large_orange_diamond:
* [Futurice iOS Good Practices ★6829](https://github.com/futurice/ios-good-practices) - iOS starting guide and good practices suggestions by [@futurice](https://github.com/futurice).
* [SlideShare Swift Style Guide](https://github.com/SlideShareInc/swift-style-guide/blob/master/swift_style_guide.md) - SlideShare Swift Style Guide we are using for our upcoming iOS 8 only app written in Swift :large_orange_diamond:
* [Prolific Interactive Style Guide ★153](https://github.com/prolificinteractive/swift-style-guide) - A style guide for Swift.

# Good Websites

#### News, Blogs and more
* [BGR](http://bgr.com/ios-7/)
* [iMore](https://www.imore.com/)
* [Lifehacker](https://lifehacker.com/tag/ios)
* [NSHipster](http://nshipster.com)
* [Objc.io](https://www.objc.io/)
* [ASCIIwwdc](http://asciiwwdc.com)
* [Natasha The Robot](https://www.natashatherobot.com/)
* [Apple's Swift Blog](https://developer.apple.com/swift/blog/) :large_orange_diamond:
* [iOS Programming Subreddit](https://www.reddit.com/r/iOSProgramming/)
* [iOS8-day-by-day ★2697](https://github.com/shinobicontrols/iOS8-day-by-day) :large_orange_diamond:
* [iOScreator](https://www.ioscreator.com/) :large_orange_diamond:
* [Mathew Sanders](http://mathewsanders.com/) :large_orange_diamond:
* [Little Bites of Cocoa](https://littlebitesofcocoa.com/) :large_orange_diamond:
* [iOS Dev Nuggets](http://hboon.com/iosdevnuggets/) :large_orange_diamond:
* [This Week in Swift](https://swiftnews.curated.co/) :large_orange_diamond:
* [iOS Developer and Designer interview ★1383](https://github.com/9magnets/iOS-Developer-and-Designer-Interview-Questions) - A small guide to help those looking to hire a developer or designer for iOS work.
* [iOS9-day-by-day ★1435 ⏳2Y](https://github.com/shinobicontrols/iOS9-day-by-day) :large_orange_diamond:
* [Code Facebook](https://code.facebook.com/ios/)
* [iOS Cookies](http://www.ioscookies.com/) - A hand curated collection of iOS libraries written in Swift :large_orange_diamond:
* [Feeds for iOS Developer ★73](https://github.com/rgnlax/Feeds-for-iOS-Developer) - The list of RSS feeds for iOS developers.
* [iOS10 day-by-day](https://www.shinobicontrols.com/blog/ios-10-day-by-day-index) :large_orange_diamond:

#### UIKit references
* [iOS Fonts](http://iosfonts.com/)
* [UIAppearance list](https://gist.github.com/mattt/5135521)

#### Forums and discuss lists
* [iPhone Dev SDK Forum](http://iphonedevsdk.com/)
* ["iOS" on Stackoverflow](https://stackoverflow.com/questions/tagged/ios)

#### Tutorials and Keynotes
* [AppCoda](https://www.appcoda.com/)
* [Tutorials Point](http://www.tutorialspoint.com/ios/)
* [Code with Chris](https://codewithchris.com/)
* [Cocoa with Love](http://www.cocoawithlove.com/)
* [Code School - Try Objective-C](https://www.codeschool.com/courses/try-objective-c)
* [Brian Advent youtube channel](https://www.youtube.com/channel/UCysEngjfeIYapEER9K8aikw/videos) - Swift tutorials Youtube Channel. :large_orange_diamond:
* [RAYWENDERLICH](https://www.raywenderlich.com/tutorials) - Tutorials for developers and gamers
* [Mike Ash](https://www.mikeash.com/pyblog/)
* [Big Nerd Ranch](https://www.bignerdranch.com/blog/categories/ios/) :large_orange_diamond:
* [Tuts+](https://code.tutsplus.com/categories/ios-sdk) :large_orange_diamond:
* [iOS-Blog](http://www.ios-blog.co.uk/) :large_orange_diamond:
* [Thinkster](https://thinkster.io/a-better-way-to-learn-swift) :large_orange_diamond:
* [Swift Education](https://github.com/swifteducation) - A community of educators sharing materials for teaching Swift and app development. :large_orange_diamond:
* [Cocoa Dev Central](http://cocoadevcentral.com)
* [Use Your Loaf](https://useyourloaf.com/)
* [Swift Tutorials by Jameson Quave](http://jamesonquave.com/blog/tutorials/) :large_orange_diamond:
* [Awesome-Swift-Education ★5273](https://github.com/hsavit1/Awesome-Swift-Education) - :fire: All of the resources for Learning About Swift :large_orange_diamond:
* [Awesome-Swift-Playgrounds ★1887](https://github.com/uraimo/Awesome-Swift-Playgrounds) - ⭐ A List of Awesome Swift Playgrounds! :large_orange_diamond:
* [learn-swift ★762](https://github.com/nettlep/learn-swift) - Learn Apple's Swift programming language interactively through these playgrounds. :large_orange_diamond:
* [Treehouse's iOS Courses and Workshops](https://teamtreehouse.com/library/topic:ios) - Topics for beginner and advanced developers in both Objective-C and Swift.
* [The Swift Summary Book ★1643](https://github.com/jakarmy/swift-summary) - A summary of Apple's Swift language written on Playgrounds. :large_orange_diamond:
* [Hacking With Swift](https://www.hackingwithswift.com) - Learn to code iPhone and iPad apps with 3 Swift tutorials. :large_orange_diamond:
* [Realm Academy](https://academy.realm.io/)

#### iOS UI Template
* [iOS UI Design Kit](https://www.invisionapp.com/tethr)
* [iOS Design Guidelines](https://ivomynttinen.com/blog/ios-design-guidelines)
* [iOS GUI by Facebook Design Resources](http://facebook.design/)

#### Prototyping
* [FluidUI](https://www.fluidui.com)
* [Proto.io](https://proto.io/)
* [Framer](https://framer.com/)
* [Pixate](http://www.pixate.com/)
* [Principle](http://principleformac.com)

#### Newsletters
* [iOS Goodies](http://ios-goodies.com) - Weekly iOS newsletter
* [This Week in Swift](https://swiftnews.curated.co) - I'm @NatashaTheRobot and I'm programmed to love #Swift! Every week, I put together a list of the best Swift resources for you. Happy Learning!
* [The iOS Times](http://theiostimes.com) - A weekly publication with news and trending projects in the open source iOS ecosystem.
* [raywenderlich.com Weekly](https://www.raywenderlich.com/newsletter) - sign up to receive the latest tutorials from raywenderlich.com each week
* [iOS Dev Tools Weekly](https://iosdev.tools) - The greatest iOS development tools, including websites, desktop and mobile apps, and back-end services.
* [iOS Trivia Weekly](http://wanderbit.us4.list-manage.com/subscribe?u=4e20cd8ea3a0ce09ff4619a52&id=5898a5992b) - Three challenging questions about iOS development every Wednesday
* [Indie iOS Focus Weekly](https://indieiosfocus.curated.co) - Looking for the best iOS dev links, tutorials, & tips beyond the usual news? Curated by Chris Beshore. Published every Thursday.
* [iOS Dev Weekly](https://iosdevweekly.com/) - Subscribe to a hand-picked round up of the best iOS development links every week. Free.
* [Swift Weekly Brief](https://swiftweekly.github.io/) - A community-driven weekly newsletter about Swift.org. Curated by Jesse Squires and published for free every Thursday
* [Server-Side Swift Weekly](https://www.serverswift.tech) - A weekly newsletter with the best links related to server-side Swift and cross-platform developer tools. Curated by [@maxdesiatov](https://twitter.com/maxdesiatov)
* [WeeklyCocoa.News](https://weeklycocoa.news) - Weekly updated newsletter about iOS, Swift, Objective-C, CocoaTouch, and other Apple connected development technologies.
* [iOS Cookies Newsletter](https://us11.campaign-archive.com/home/?u=cd1f3ed33c6527331d82107ba&id=532dc7fb64) - A weekly digest of new iOS libraries written in Swift.
* [Swift Developments](https://andybargh.com/swiftdevelopments) - A weekly curated newsletter containing a hand picked selection of the latest links, videos, tools and tutorials for people interested in designing and developing their own iOS, WatchOS and AppleTV apps using Swift.

#### Medium
* [iOS App Development](https://medium.com/ios-os-x-development) - Stories and technical tips about building apps for iOS, Apple Watch, and iPad/iPhone
* [Swift Programming](https://medium.com/swift-programming) - The Swift Programming Language

# Social Media

#### Twitter
* [@objcio](https://twitter.com/objcio)
* [@CocoaPods](https://twitter.com/CocoaPods)
* [@CocoaPodsFeed](https://twitter.com/CocoaPodsFeed)
* [@RubyMotion](https://twitter.com/RubyMotion)


#### Facebook Groups
* [HH iOS](https://www.facebook.com/groups/hhios/about/)
* [Sketch - Official group](https://www.facebook.com/groups/sketchformac/about/)
* [Design-Code](https://www.facebook.com/groups/designcode/about/)
* [Sketch-Design.io](https://www.facebook.com/groups/sketchdesignio/about/)
* [Origami Community](https://www.facebook.com/groups/origami.community/about/)
* [Framer JS](https://www.facebook.com/groups/framerjs/about/)

# Podcasts
* [The Ray Wenderlich Podcast](https://www.raywenderlich.com/rwpodcast)
* [Debug](https://www.imore.com/debug)
* [App Story](http://www.appstorypodcast.com)
* [Mobile Couch](http://mobilecouch.co/)
* [iPhreaks](https://devchat.tv/iphreaks)
* [Under the Radar](https://www.relay.fm/radar)
* [Core Intuition](http://coreint.org/)
* [Swift Playhouse](http://www.swiftplayhouse.com/)
* [Release Notes](https://releasenotes.tv/)
* [More Than Just Code](http://mtjc.fm/)
* [Runtime](https://spec.fm/podcasts/runtime)
* [Consult](http://consultpodcast.com/)
* [Swift Unwrapped](https://spec.fm/podcasts/swift-unwrapped)
* [Fireside Swift](https://itunes.apple.com/us/podcast/fireside-swift/id1269435221?mt=2)

# Books
* [The Swift Programming Language by Apple](https://itunes.apple.com/us/book/swift-programming-language/id881256329?mt=11) :large_orange_diamond:
* [Using Swift with Cocoa and Objective C by Apple](https://itunes.apple.com/us/book/using-swift-cocoa-objective/id888894773?mt=11) :large_orange_diamond:
* [iOS Programming: The Big Nerd Ranch Guide by Christian Keur, Aaron Hillegass, Joe Conway](https://www.bignerdranch.com/books/ios-programming/)
* [Programming in Objective-C by Stephen G. Kochan](https://www.amazon.com/Programming-Objective-C-6th-Developers-Library/dp/0321967607)
* [The Complete Friday Q & A: Volume 1](https://www.mikeash.com/book.html)
* [Core Data for iOS: Developing Data-Driven Applications for the iPad, iPhone, and iPod touch](https://www.amazon.com/Core-Data-iOS-Data-Driven-Applications/dp/0321670426)
* [Cocoa Design Patterns](https://www.amazon.com/Cocoa-Design-Patterns-Erik-Buck/dp/0321535022)
* [Hello Swift! by Tanmay Bakshi with Lynn Beighley](https://www.manning.com/books/hello-swift) :large_orange_diamond:
* [iOS Development with Swift by Craig Grummitt](https://www.manning.com/books/ios-development-with-swift) :large_orange_diamond:
* [Anyone Can Create an App by Wendy L. Wise](https://www.manning.com/books/anyone-can-create-an-app) :large_orange_diamond:
* [Advanced Swift by Chris Eidhof, Ole Begemann, and Airspeed Velocity](https://www.objc.io/books/advanced-swift/) :large_orange_diamond:
* [Functional Swift by Chris Eidhof, Florian Kugler, and Wouter Swierstra](https://www.objc.io/books/functional-swift/) :large_orange_diamond:
* [Core Data by Florian Kugler and Daniel Eggert](https://www.objc.io/books/core-data/) :large_orange_diamond:
* [Classic Computer Science Problems in Swift](https://www.manning.com/books/classic-computer-science-problems-in-swift) :large_orange_diamond:
* [Swift in Depth](https://www.manning.com/books/swift-in-depth) :large_orange_diamond:

# Other Awesome Lists
Other amazingly awesome lists can be found in the
* [awesome-awesomeness ★20083](https://github.com/bayandin/awesome-awesomeness) list.
* [Open Source apps ★14822](https://github.com/dkhamsing/open-source-ios-apps) list of open source iOS apps
* Awesome-swift
  * [@matteocrippa ★13277](https://github.com/matteocrippa/awesome-swift) - A collaborative list of awesome swift resources.
  * [@Wolg ★4342](https://github.com/Wolg/awesome-swift) - A curated list of awesome Swift frameworks, libraries and software.
  * [Awesome-Swift-Education ★5273](https://github.com/hsavit1/Awesome-Swift-Education) - All of the resources for Learning About Swift :large_orange_diamond:
* [awesome watchkit apps ★197 ⏳2Y](https://github.com/sanketfirodiya/sample-watchkit-apps) curated list of sample watchkit apps and tutorials. :watch:
* [iOS Learning Resources ★244](https://github.com/sanketfirodiya/iOS-learning-resources) Comprehensive collection of high quality, frequently updated and well maintained iOS tutorial sites.
* [awesome-ios-animation ★2923](https://github.com/ameizi/awesome-ios-animation) - A curated list of awesome iOS animation, including Objective-C and Swift libraries.
* [awesome-ios-chart ★1054 ⏳1Y](https://github.com/ameizi/awesome-ios-chart) - A curated list of awesome iOS chart libraries, including Objective-C and Swift.
* [awesome-gists ★180](https://github.com/vsouza/awesome-gists#ios) - A list of amazing gists (iOS section).
* [awesome-ios-ui ★9844](https://github.com/cjwirth/awesome-ios-ui) - A curated list of awesome iOS UI/UX libraries.
* [Awesome-Server-Side-Swift/TheList ★616](https://github.com/Awesome-Server-Side-Swift/TheList) - A list of Awesome Server Side Swift 3 projects
* [awesome-interview-questions ★16825](https://github.com/MaximAbramchuck/awesome-interview-questions#ios) - A curated awesome list of lists of interview questions including iOS.
* [iOS-Playbook ★72](https://github.com/bakkenbaeck/iOS-handbook) - Guidelines and best practices for excellent iOS apps
* [iOS-Learning-Materials ★59](https://github.com/jVirus/iOS-Learning-Materials) - Curated list of articles, web-resources, tutorials and code repositories that may help you dig a little bit deeper into iOS.
* [Awesome-iOS-Twitter ★158](https://github.com/carolanitz/Awesome-iOS-Twitter) - A curated list of awesome iOS Twitter accounts
* [Marketing for Engineers ★4159](https://github.com/LisaDziuba/Marketing-for-Engineers) - A curated collection of marketing articles & tools to grow your product.
* [Awesome-ARKit ★3434](https://github.com/olucurious/Awesome-ARKit) - A curated list of awesome ARKit projects and resources.
* [CocoaConferences ★744](https://github.com/Lascorbe/CocoaConferences) - List of cocoa conferences for iOS & macOS developers.
* [example-ios-apps ★12](https://github.com/imjog/example-ios-apps) - A curated list of Open Source example iOS apps developed in Swift.

# Contributing and License
 * [See the guide](https://github.com/vsouza/awesome-ios/blob/master/.github/CONTRIBUTING.md)
 * Distributed under the MIT license. See LICENSE for more information.
---
<p align="center">
	This list is a copy of <a href="https://github.com/vsouza/awesome-ios">vsouza/awesome-ios</a> with ranks
</p>
