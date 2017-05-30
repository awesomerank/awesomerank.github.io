<h1 align="center">
Ranked awesome lists, all in one place
</h1>
<p align="center">
	This list is a copy of <a href="vsouza/awesome-ios">vsouza/awesome-ios</a> with ranks
</p>
---
<img src="https://raw.githubusercontent.com/vsouza/awesome-ios/master/awesome_logo.png">

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg) ★59088](sindresorhus/awesome)
[![Join the chat at https://gitter.im/norio-nomura/SwiftTalkInJapanese](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/vsouza/awesome-ios?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
[![Build Status](https://api.travis-ci.org/vsouza/awesome-ios.svg?branch=master)](https://travis-ci.org/vsouza/awesome-ios)
[![Language](https://awesomelinkcounter.herokuapp.com/swift)]()
[![Language](https://awesomelinkcounter.herokuapp.com/objc)]()
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)

## We've launched our Newsletter!! ✅🚀📰
* [Check out our new website 🗞](http://weekly.awesomeios.com/)

# About
A curated list of awesome iOS frameworks, libraries, tutorials, Xcode plugins, components and much more.
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
    - [Apple TV](#apple-tv)
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
        - [Menu](#menu)
        - [Navigation Bar](#navigation-bar)
        - [PickerView](#pickerview)
        - [Popup](#popup)
        - [Pull to Refresh](#pull-to-refresh)
        - [Rating Stars](#rating-stars)
        - [ScrollView](#scrollview)
        - [Slider](#slider)
        - [Splash View](#splash-view)
        - [Stepper](#stepper)
        - [Switch](#switch)
        - [Tab Bar](#tab-bar)
        - [Table View / Collection View](#table-view--collection-view)
        - [Tag](#tag)
        - [TextField & TextView](#textfield--textview)
        - [Web View](#web--view)
    - [URL Scheme](#url-scheme)
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
* [Lifehacker](http://lifehacker.com/i-want-to-write-ios-apps-where-do-i-start-1644802175) - I Want to Write iOS Apps. Where Do I Start?
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
* [GTrack ★85](gemr/GTrack) - Lightweight Objective-C wrapper around the Google Analytics for iOS SDK with some extra goodies.
* [ARAnalytics ★1626](orta/ARAnalytics) - Analytics abstraction library offering a sane API for tracking events and user data.
* [Segment ★243](segmentio/analytics-ios) - The hassle-free way to integrate analytics into any iOS application.
* [MOCA Analytics](https://mocaplatform.com/features) - Paid cross-platform analytics backend.
* [Countly](https://count.ly) - Open source, mobile & web analytics, crash reports and push notifications platform for iOS & Android.
* [Abbi ★1](abbiio/iosdk) - A Simple SDK for developers to manage and maximise conversions of all in-app promotions.
* [devtodev](https://www.devtodev.com/) - Comprehensive analytics service that improves your project and saves time for product development.

## Apple TV
* [Voucher ★477](rsattar/Voucher) - A simple library to make authenticating tvOS apps easy via their iOS counterparts.
* [XCDYouTubeKit ★2080](0xced/XCDYouTubeKit) - YouTube video player for iOS, tvOS and OS X
* [TVMLKitchen ★53](toshi0383/TVMLKitchen) - Swifty TVML template manager with or without client-server :large_orange_diamond:
* [BrowserTV ★201 ⏳1Y](zats/BrowserTV) - Turn your TV into a dashboard displaying any webpage! :large_orange_diamond:
* [Swift-GA-Tracker-for-Apple-tvOS ★63](analytics-pros/Swift-GA-Tracker-for-Apple-tvOS) - Google Analytics tracker for Apple tvOS provides an easy integration of Google Analytics’ measurement protocol for Apple TV. :large_orange_diamond:
* [ParallaxView ★302](PGSSoft/ParallaxView) - iOS controls and extensions that add parallax effect to your application. :large_orange_diamond:
* [TvOSTextViewer ★4](dcordero/TvOSTextViewer) - Light and scrollable view controller for tvOS to present blocks of text :large_orange_diamond:
* [FocusTvButton ★13](dcordero/FocusTvButton) - Light wrapper of UIButton that allows extra customization for tvOS :large_orange_diamond:
* [TvOSMoreButton ★9](cgoldsby/TvOSMoreButton) - A basic tvOS button which truncates long text with '... More'. :large_orange_diamong:

## Authentication
* [Heimdallr.swift ★239](trivago/Heimdallr.swift) - Easy to use OAuth 2 library for iOS, written in Swift. :large_orange_diamond:
* [OhMyAuth ★37](hyperoslo/OhMyAuth) - Simple OAuth2 library with a support of multiple services. :large_orange_diamond:
* [AuthenticationViewController ★231](raulriera/AuthenticationViewController) - A simple to use, standard interface for authenticating to oauth 2.0 protected endpoints via SFSafariViewController. :large_orange_diamond:
* [OAuth2 ★544](p2/OAuth2) - OAuth2 framework for OS X and iOS, written in Swift. :large_orange_diamond:
* [OAuthSwift ★1652](OAuthSwift/OAuthSwift) - Swift based OAuth library for iOS :large_orange_diamond:
* [SimpleAuth ★1147 ⏳1Y](calebd/SimpleAuth) - Simple social authentication for iOS.
* [AlamofireOauth2 ★67](evermeer/AlamofireOauth2) - A swift implementation of OAuth2 :large_orange_diamond:
* [SwiftyOAuth ★450](delba/SwiftyOAuth) - A simple OAuth library for iOS with a built-in set of providers :large_orange_diamond:
* [Simplicity ★601](SimplicityMobile/Simplicity) - A simple way to implement Facebook and Google login in your iOS and OS X apps. :large_orange_diamond:
* [InstagramAuthViewController ★32 ⏳1Y](Isuru-Nanayakkara/InstagramAuthViewController) - A ViewController for Instagram authentication. :large_orange_diamond:
* [Cely ★64](chaione/Cely) - Plug-n-Play login framework written in Swift. :large_orange_diamond:

## Bridging
* [RubyMotion](http://www.rubymotion.com/) - RubyMotion is a revolutionary toolchain that lets you quickly develop and test native iOS and OS X applications for iPhone, iPad and Mac, all using the Ruby language.
* [JSPatch ★9835](bang590/JSPatch) - JSPatch bridge Objective-C and Javascript using the Objective-C runtime. You can call any Objective-C class and method in JavaScript by just including a small engine. JSPatch is generally use for hotfix iOS App.
* [WebViewJavascriptBridge ★8711](marcuswestin/WebViewJavascriptBridge) - An iOS/OSX bridge for sending messages between Obj-C and JavaScript in UIWebViews/WebViews
* [MAIKit ★131](MichaelBuckley/MAIKit) - A framework for sharing code between iOS and OS X

## Cache
* [Awesome Cache ★1023](aschuch/AwesomeCache) - Delightful on-disk cache (written in Swift) :large_orange_diamond:
* [mattress ★427](buzzfeed/mattress) - iOS Offline Caching for Web Content :large_orange_diamond:
* [Carlos ★427](WeltN24/Carlos) - A simple but flexible cache :large_orange_diamond:
* [HanekeSwift ★4310](Haneke/HanekeSwift) - A lightweight generic cache for iOS written in Swift with extra love for images. :large_orange_diamond:
* [YYCache ★1362](ibireme/YYCache) - High performance cache framework for iOS.
* [Cache ★669](hyperoslo/Cache) - Nothing but Cache. :large_orange_diamond:
* [MGCacheManager ★7](Mortgy/MGCacheManager) - A delightful iOS Networking Cache Managing Class.
* [SPTPersistentCache ★1118](spotify/SPTPersistentCache) - Everyone tries to implement a cache at some point in their iOS app’s lifecycle, and this is ours. By Spotify
* [Track ★180](maquannene/Track) - Track is a thread safe cache write by Swift. Composed of DiskCache and MemoryCache which support LRU. :large_orange_diamond:
* [UITableView Cache ★56](Kilograpp/UITableView-Cache) - UITableView cell cache that cures scroll-lags on a cell instantiating.
* [RocketData ★498](linkedin/RocketData) - A caching and consistency solution for immutable models. :large_orange_diamond:
* [PINCache ★1629](pinterest/PINCache) - Fast, non-deadlocking parallel object cache for iOS and OS X
* [Johnny ★24](zolomatok/Johnny) - Melodic Caching for Swift :large_orange_diamond:

## Charts
* [Charts](https://github.com/danielgindi/Charts) - A powerful chart / graph framework, the iOS equivalent to [MPAndroidChart ★15802](PhilJay/MPAndroidChart). :large_orange_diamond:
* [JTChartView ★110](kubatruhlar/JTChartView) - JTChartView is the new lightweight and fully customizable solution to draw a chart.
* [PNChart ★8455](kevinzhow/PNChart) - A simple and beautiful chart lib used in Piner and CoinsMan for iOS
* [XJYChart ★183](JunyiXie/XJYChart) - A Beautiful chart for iOS. Support animation, click, slide, area highlight.
* [BEMSimpleLineGraph ★2542](Boris-Em/BEMSimpleLineGraph) - Elegant Line Graphs for iOS (charting library).
* [JBChartView ★3660](Jawbone/JBChartView) - iOS-based charting library for both line and bar graphs.
* [XYPieChart ★1725 ⏳1Y](xyfeng/XYPieChart) - A simple and animated Pie Chart for your iOS app.
* [TEAChart ★1122](xhacker/TEAChart) - Simple and intuitive iOS chart library. Contribution graph, clock chart, and bar chart.
* [EChart ★621](zhuhuihuihui/EChart) - iOS/iPhone/iPad Chart, Graph. Event handling and animation supported.
* [FSLineChart ★785](ArthurGuibert/FSLineChart) - A line chart library for iOS.
* [chartee ★829 ⏳1Y](zhiyu/chartee) - a charting library for mobile platforms.
* [ANDLineChartView ★401](anaglik/ANDLineChartView) - ANDLineChartView is easy to use view-based class for displaying animated line chart.
* [TWRCharts ★362 ⏳2Y](chasseurmic/TWRCharts) - An iOS wrapper for ChartJS. Easily build animated charts by leveraging the power of native Obj-C code.
* [SwiftCharts ★1328](i-schuetz/SwiftCharts) - Easy to use and highly customizable charts library for iOS. :large_orange_diamond:
* [FlowerChart ★7 ⏳1Y](drinkius/flowerchart) - Flower-shaped chart with custom appearance animation, fully vector. :large_orange_diamond:
* [Scrollable-GraphView ★3748](philackm/Scrollable-GraphView) - An adaptive scrollable graph view for iOS to visualise simple discrete datasets. Written in Swift. :large_orange_diamond:
* [Dr-Charts ★55](Zomato/DR-charts) - Dr-Charts is a highly customisable, easy to use and interactive chart / graph framework in Objective-C.
* [Graphs ★807](recruit-mtl/Graphs) - Light weight charts view generator for iOS. :large_orange_diamond:
* [FSInteractiveMap ★438](ArthurGuibert/FSInteractiveMap) - A charting library to visualize and interact with a vector map on iOS. It's like Geochart but for iOS!
* [JYRadarChart ★387](johnnywjy/JYRadarChart) - An iOS open source Radar Chart implementation.
* [TKRadarChart ★120](TBXark/TKRadarChart) - A customizable radar chart in Swift :large_orange_diamond:
* [MagicPie ★518](AlexandrGraschenkov/MagicPie) - Awesome layer based pie chart. Fantastically fast and fully customizable. Amazing animations available with MagicPie!!1 :large_orange_diamond: 🎉 ✨✨✨✨✨
* [PieCharts ★270](i-schuetz/PieCharts) - Easy to use and highly customizable pie charts library for iOS. :large_orange_diamond:
* [CSPieChart ★22](youkchansim/CSPieChart) - iOS PieChart Opensource. This is very easy to use and customizable. :large_orange_diamond:
* [DDSpiderChart ★19](dadalar/DDSpiderChart) - Easy to use and customizable Spider (Radar) Chart library for iOS written in Swift. :large_orange_diamond:

## Code Quality
* [Bootstrap ★1793](krzysztofzablocki/Bootstrap) - iOS project bootstrap aimed at high quality coding.
* [KZAsserts ★103 ⏳1Y](krzysztofzablocki/KZAsserts) - Set of custom assertions that automatically generate NSError's, allow for both Assertions in Debug and Error handling in Release builds, with beautiful DSL.
* [PSPDFUIKitMainThreadGuard](https://gist.github.com/steipete/5664345) - Simple snippet generating assertions when UIKit is used on background threads.
* [Flex ★7814](Flipboard/FLEX) - An in-app debugging and exploration tool for iOS.
* [chisel ★5938](facebook/chisel) - Collection of LLDB commands to assist debugging iOS apps.
* [ocstyle ★245](Cue/ocstyle) - Objective-C style checker.
* [spacecommander ★758](square/spacecommander) - Commit fully-formatted Objective-C code as a team without even trying.
* [DWURecyclingAlert ★552](diwu/DWURecyclingAlert) - Optimizing UITableViewCell For Fast Scrolling.
* [Tailor ★1020](sleekbyte/tailor) - Cross-platform static analyzer for Swift that helps you to write cleaner code and avoid bugs.
* [SwiftCop ★487](andresinaka/SwiftCop) -  SwiftCop is a validation library fully written in Swift and inspired by the clarity of Ruby On Rails Active Record validations. :large_orange_diamond:
* [Trackable ★120](VojtaStavik/Trackable) - Trackable is a simple analytics integration helper library. It’s especially designed for easy and comfortable integration with existing projects. :large_orange_diamond:
* [MLeaksFinder ★2106](Zepo/MLeaksFinder) - Find memory leaks in your iOS app at develop time.
* [HeapInspector-for-iOS ★1570](tapwork/HeapInspector-for-iOS) - Find memory issues & leaks in your iOS app without instruments
* [FBMemoryProfiler ★2574](facebook/FBMemoryProfiler) - iOS tool that helps with profiling iOS Memory usage.
* [FBRetainCycleDetector ★2412](facebook/FBRetainCycleDetector) - iOS library to help detecting retain cycles in runtime.
* [Buglife ★244](Buglife/Buglife-iOS) - Awesome bug reporting for iOS apps
* [Warnings-xcconfig ★424 ⏳1Y](boredzo/Warnings-xcconfig) - An xcconfig (Xcode configuration) file for easily turning on a boatload of warnings in your project or its targets.
* [Aardvark ★178](square/Aardvark) - Aardvark is a library that makes it dead simple to create actionable bug reports.
* [Stats ★137](shu223/Stats) - In-app memory usage monitoring.
* [Alpha ★626](Legoless/Alpha) - Next generation debugging framework for iOS.
* [GlueKit ★328](lorentey/GlueKit) - A type-safe observer framework for Swift. :large_orange_diamond:
* [SwiftFormat ★1341](nicklockwood/SwiftFormat) - A code library and command-line formatting tool for reformatting Swift code. :large_orange_diamond:
* [PSTModernizer ★209](PSPDFKit-labs/PSTModernizer) - Makes it easier to support older versions of iOS by fixing things and adding missing methods.
* [SwiftyVIPER ★42](codytwinton/SwiftyVIPER) - Makes implementing VIPER architecture much easier and cleaner.  :large_orange_diamond:
* [Bugsee](https://www.bugsee.com) - In-app bug and crash reporting with video, logs, network traffic and traces.
* [Fallback ★32](devxoul/Fallback) - Syntactic sugar for nested do-try-catch. :large_orange_diamond:
* [ODUIThreadGuard ★629](olddonkey/ODUIThreadGuard) - A guard to help you check if you make UI changes not in main thread. :large_orange_diamond:
* [IBAnalyzer ★784](fastred/IBAnalyzer) - Find common xib and storyboard-related problems without running your app or writing unit tests. :large_orange_diamond:
* [Dotzu ★1066](remirobert/Dotzu) - iOS app debugger while using the app. Crash report, logs, network.
* [CleanArchitectureRxSwift ★563](sergdort/CleanArchitectureRxSwift) - Example of Clean Architecture of iOS app using RxSwift. :large_orange_diamond:
* [PIDOR ★270](applepride/pidor) - Simple design pattern with the best iOS dev experience.
* [DecouplingKit ★98](coderyi/DecouplingKit) - decoupling between modules in your iOS Project.
* [Clue ★226](Geek-1001/Clue) - Flexible bug report framework for iOS with screencast, networking, interactions and view structure.
* [Viperit ★151](ferranabello/Viperit) - Viper Framework for iOS. Develop an app following VIPER architecture in an easy way. Written and tested in Swift. :large_orange_diamond:

#### Linter
* [OCLint](http://oclint.org/) - Static code analysis tool for improving quality and reducing defects.
* [Taylor ★152](yopeso/Taylor) - Measure Swift code metrics and get reports in Xcode, Jenkins and other CI platforms. :large_orange_diamond:
* [Swiftlint ★6892](realm/SwiftLint) - A tool to enforce Swift style and conventions. :large_orange_diamond:

## Color
* [Chameleon ★9072](ViccAlexander/Chameleon) - A lightweight, yet powerful, flat color framework for iOS (ObjC & Swift). :large_orange_diamond:
* [SDevFlatColors ★57](0x73/SDevFlatColors) - Flat Colors on Swift :large_orange_diamond:
* [ColorArt ★130 ⏳1Y](vinhnx/ColorArt) - extract dominant colors from image like iTunes 11.
* [DynamicColor ★1621](yannickl/DynamicColor) - Yet another extension to manipulate colors easily in Swift. :large_orange_diamond:[e]
* [SwiftHEXColors ★474](thii/SwiftHEXColors) - HEX color handling as an extension for UIColor. :large_orange_diamond:[e]
* [Colours ★2858](bennyguitar/Colours) - A beautiful set of predefined colors and a set of color methods to make your iOS/OSX development life easier.
* [UIColor-Hex-Swift ★754](yeahdongcn/UIColor-Hex-Swift) - Convenience method for creating autoreleased color using RGBA hex string. :large_orange_diamond:
* [Crayons ★489 ⏳1Y](Sephiroth87/Crayons) - An Xcode plugin to improve dealing with colors in your project
* [Hue ★2012](hyperoslo/Hue) - Hue is the all-in-one coloring utility that you'll ever need.
* [FlatUIColors ★129](brynbellomy/FlatUIColors) - Flat UI color palette helpers written in Swift. :large_orange_diamond:
* [RandomColorSwift ★424](onevcat/RandomColorSwift) - An attractive color generator for Swift. Ported from randomColor.js. :large_orange_diamond:
* [PFColorHash ★17](PerfectFreeze/PFColorHash) - Generate color based on the given string. :large_orange_diamond:
* [BCColor ★421](boycechang/BCColor) - A lightweight but powerful color kit (Swift) :large_orange_diamond:
* [XcodeColorSense ★75](onmyway133/XcodeColorSense) - :balloon: An Xcode plugin that makes working with color easier :large_orange_diamond:
* [DKNightVersion ★2628](Draveness/DKNightVersion) - Manage Colors, Integrate Night/Multiple Themes
* [PrettyColors ★145](jdhealy/PrettyColors) - PrettyColors is a Swift library for styling and coloring text in the Terminal. The library outputs [ANSI escape codes](https://en.wikipedia.org/wiki/ANSI_escape_code) and conforms to [ECMA Standard 48](http://www.ecma-international.org/publications/standards/Ecma-048.htm). :large_orange_diamond:
* [TFTColor ★15](burhanuddin353/TFTColor) - Simple Extension for RGB and CMKY Hex Strings and Hex Values (ObjC & Swift). :large_orange_diamond:
* [CostumeKit ★273](jakemarsh/CostumeKit) - Base types for theming an app. :large_orange_diamond:
* [CSS3ColorsSwift ★48](WorldDownTown/CSS3ColorsSwift) - A UIColor extension with CSS3 Colors name. :large_orange_diamond:

## Command Line
* [Swiftline ★954](nsomar/Swiftline) - Swiftline is a set of tools to help you create command line applications. :large_orange_diamond:
* [CommandLine ★874](jatoben/CommandLine) - A pure Swift library for creating command-line interfaces :large_orange_diamond:
* [Colors ★82 ⏳1Y](paulot/Colors) - Terminal Colors for Swift :large_orange_diamond:
* [Commander ★765](kylef/Commander) - Compose beautiful command line interfaces in Swift :large_orange_diamond:
* [ColorizeSwift ★161](mtynior/ColorizeSwift) - Terminal string styling for Swift. :large_orange_diamond:
* [Guaka ★1021](nsomar/Guaka) - The smartest and most beautiful (POSIX compliant) Command line framework for Swift :large_orange_diamond:
* [Marathon ★901](JohnSundell/Marathon) - Marathon makes it easy to write, run and manage your Swift scripts :large_orange_diamond:
* [CommandCougar ★5](surfandneptune/CommandCougar) - An elegant pure Swift library for building command line applications. :large_orange_diamond:

## Concurrency
* [Venice ★1271](Zewo/Venice) - CSP (Coroutines, Channels, Select) for Swift :large_orange_diamond:
* [Safe ★397](tidwall/Safe) - Modern Concurrency and Synchronization for Swift. :large_orange_diamond:
* [Concurrent ★132](typelift/Concurrent) - Functional Concurrency Primitives :large_orange_diamond:
* [Flow ★186](JohnSundell/Flow) - Operation Oriented Programming in Swift :large_orange_diamond:
* [Brisk ★19](jmfieldman/Brisk) - A Swift DSL that allows concise and effective concurrency manipulation. :large_orange_diamond:
* [Aojet ★9](aojet/Aojet) - An actor model library for swift.
* [Overdrive ★801](arikis/Overdrive) - Fast async task based Swift framework with focus on type safety, concurrency and multi threading. :large_orange_diamond:
* [NSLock+Synchronized ★2](Jon-Schneider/NSLock-Synchronized) - Do you miss @synchronized in Swift? NSLock+Synchronized gives you back @synchronized in Swift via a global function and NSLock class and instance methods, conveniently usable via Cocoapod and Carthage Framework. :large_orange_diamond:[e]
* [AsyncNinja ★47](AsyncNinja/AsyncNinja) - A complete set of concurrency and reactive programming primitives. :large_orange_diamond:
* [Kommander ★79](intelygenz/Kommander-iOS) - Kommander is a Swift library to manage the task execution in different threads. Through the definition a simple but powerful concept, Kommand. :large_orange_diamond:

## Core Data
* [CWCoreData ★72 ⏳1Y](jayway/CWCoreData) - Additions and utilities to make it concurrency easier with the Core Data framework.
* [ObjectiveRecord ★1320](supermarin/ObjectiveRecord) - ActiveRecord for Objective-C.
* [SSDataKit ★466 ⏳1Y](soffes/SSDataKit) - Eliminate your Core Data boilerplate code.
* [ios-queryable ★236 ⏳1Y](martydill/ios-queryable) - ios-queryable is an implementation of IQueryable/IEnumerable for Core Data.
* [Ensembles ★1463](drewmccormack/ensembles) - A synchronization framework for Core Data.
* [SLRESTfulCoreData ★186 ⏳2Y](OliverLetterer/SLRESTfulCoreData) - Objc naming conventions, autogenerated accessors at runtime, URL substitutions and intelligent attribute mapping.
* [Mogenerator ★2928](rentzsch/mogenerator) - Automatic Core Data code generation.
* [HardCoreData ★203 ⏳1Y](Krivoblotsky/HardCoreData) - CoreData stack and controller that will never block UI thread.
* [encrypted-core-data ★624](project-imas/encrypted-core-data) - Core Data encrypted SQLite store using SQLCipher.
* [MagicalRecord ★10336](magicalpanda/MagicalRecord) - Super Awesome Easy Fetching for Core Data.
* [QueryKit ★1249](QueryKit/QueryKit) - A simple type-safe Core Data query language. :large_orange_diamond:
* [CoreStore ★1455](JohnEstropia/CoreStore) - Powerful Core Data framework for Incremental Migrations, Fetching, Observering, etc. :large_orange_diamond:
* [Core Data Query Interface ★19](prosumma/CoreDataQueryInterface) A type-safe, fluent query framework for Core Data. :large_orange_diamond:
* [Graph ★699](CosmicMind/Graph) - An elegant data-driven framework for CoreData in Swift. :large_orange_diamond:
* [CoreDataDandy ★32](fuzz-productions/CoreDataDandy) - A feature-light wrapper around Core Data that simplifies common database operations. :large_orange_diamond:
* [Sync ★1918](SyncDB/Sync) - :arrows_counterclockwise: Modern Swift JSON synchronization to Core Data :large_orange_diamond:
* [AlecrimCoreData ★715](Alecrim/AlecrimCoreData) - A powerful and simple Core Data wrapper framework written in Swift. :large_orange_diamond:
* [AERecord ★279](tadija/AERecord) - Super awesome Core Data wrapper in Swift. :large_orange_diamond:
* [CoreDataStack ★501](bignerdranch/CoreDataStack) - The Big Nerd Ranch Core Data Stack :large_orange_diamond:
* [JSQCoreDataKit ★409](jessesquires/JSQCoreDataKit) - A swifter Core Data stack :large_orange_diamond:
* [Skopelos ★172](albertodebortoli/Skopelos) - A minimalistic, thread safe, non-boilerplate and super easy to use version of Active Record on Core Data. Simply all you need for doing Core Data. Swift flavour. :large_orange_diamond:
* [Cadmium ★88](jmfieldman/cadmium) - A complete swift framework that wraps CoreData and helps facilitate best practices. :large_orange_diamond:
* [DataKernel ★4](mrdekk/DataKernel) - Simple CoreData wrapper to ease operations. :large_orange_diamond:
* [DATAStack ★158](SyncDB/DATAStack) - 100% Swift Simple Boilerplate Free Core Data Stack. NSPersistentContainer. :large_orange_diamond:
* [JustPersist ★85](justeat/JustPersist) - JustPersist is the easiest and safest way to do persistence on iOS with Core Data support out of the box.
* [PrediKit ★463](KrakenDev/PrediKit) - An NSPredicate DSL for iOS, OSX, tvOS, & watchOS. Inspired by SnapKit and lovingly written in Swift. :large_orange_diamond:

## Database
* [Realm ★10708](realm/realm-cocoa) - The alternative to CoreData and SQLite: Simple, modern and fast.
* [YapDatabase ★2828](yapstudios/YapDatabase) - YapDatabase is an extensible database for iOS & Mac.
* [Couchbase Mobile](https://developer.couchbase.com/mobile/) - Couchbase document store for mobile with cloud sync.
* [FMDB ★11543](ccgus/fmdb) - A Cocoa / Objective-C wrapper around SQLite.
* [Akaibu-NSUserDefaults ★13 ⏳1Y](roytang121/Akaibu-NSUserDefaults) - a Swifty Key-value store for archiving NSObject in only one line of code. Class properties are automatically mapped and archived under the hood.
* [FCModel ★1621](marcoarment/FCModel) - An alternative to Core Data for people who like having direct SQL access.
* [Zephyr ★358](ArtSabintsev/Zephyr) - Effortlessly synchronize NSUserDefaults over iCloud. :large_orange_diamond:
* [Prephirences ★425](phimage/Prephirences) - Prephirences is a Swift library that provides useful protocols and convenience methods to manage application preferences, configurations and app-state. :large_orange_diamond:
* [Storez ★42](SwiftKitz/Storez) - Safe, statically-typed, store-agnostic key-value storage (with namespace support). :large_orange_diamond:
* [SwiftyUserDefaults ★2466](radex/SwiftyUserDefaults) - Statically-typed NSUserDefaults. :large_orange_diamond:
* [swiftydb ★441](Oyvindkg/swiftydb) - Making SQLite databases a blast :large_orange_diamond:
* [SugarRecord ★1880](carambalabs/SugarRecord) - Data persistence management library written in Swift 2.0 :large_orange_diamond:
* [SQLite.swift ★4225](stephencelis/SQLite.swift) - A type-safe, Swift-language layer over SQLite3. :large_orange_diamond:
* [GRDB.swift ★826](groue/GRDB.swift) - A versatile SQLite toolkit for Swift, with WAL mode support :large_orange_diamond:
* [SwiftData ★515](ryanfowler/SwiftData) - Simple and Effective SQLite Handling in Swift :large_orange_diamond:
* [Fluent ★691](vapor/fluent) - Simple ActiveRecord implementation for working with your database in Swift. :large_orange_diamond:
* [RealmIncrementalStore ★207 ⏳1Y](eure/RealmIncrementalStore) - Realm-powered Core Data persistent store. :large_orange_diamond:
* [Palau ★386](symentis/Palau) - NSUserDefaults with Wings! Custom Validation, Swift Generics.  :large_orange_diamond:
* [ParseAlternatives ★2537](relatedcode/ParseAlternatives) - A collaborative list of Parse alternative backend service providers.
* [TypedDefaults ★106](tasanobu/TypedDefaults) - TypedDefaults is a utility library to type-safely use NSUserDefaults. :large_orange_diamond:
* [realm-cocoa-converter ★120](realm/realm-cocoa-converter) - A library that provides the ability to import/export Realm files from a variety of data container formats. :large_orange_diamond:
* [YapDatabaseExtensions ★79](danthorpe/YapDatabaseExtensions) - YapDatabase extensions for use with Swift :large_orange_diamond:
* [RealmGeoQueries ★80](mhergon/RealmGeoQueries) - RealmGeoQueries simplifies spatial queries with Realm Cocoa. In the absence of and official functions, this library provide the possibility to do proximity search.  :large_orange_diamond:[e]
* [SwiftMongoDB ★255](Danappelxx/SwiftMongoDB) - A MongoDB interface for Swift :large_orange_diamond:
* [ObjectiveRocks ★32](iabudiab/ObjectiveRocks) - An Objective-C wrapper of Facebook's RocksDB - A Persistent Key-Value Store for Flash and RAM Storage.
* [OHMySQL ★24](oleghnidets/OHMySQL) - An Objective-C wrapper of MySQL C API.
* [SwiftStore ★50](hemantasapkota/SwiftStore) - Key-Value store for Swift backed by LevelDB :large_orange_diamond:
* [PredicateEditor ★348](arvindhsukumar/PredicateEditor) - A visual editor for dynamically creating NSPredicates to query data in your iOS app. :large_orange_diamond:
* [OneStore ★11](muukii/OneStore) - A single value proxy for NSUserDefaults, with clean API. :large_orange_diamond:
* [MongoDB](https://github.com/PerfectlySoft/Perfect-MongoDB) - A Swift wrapper around the mongo-c client library, enabling access to MongoDB servers. Part of the [Perfect ★11528](PerfectlySoft/Perfect) project, but stand-alone. SPM and Swift 3 support.
* [SQLite](https://github.com/PerfectlySoft/Perfect-SQLite) - A Swift wrapper around the SQLite 3 client library, enabling access to SQLite servers. Part of the [Perfect ★11528](PerfectlySoft/Perfect) project, but stand-alone. SPM and Swift 3 support.
* [MySQL](https://github.com/PerfectlySoft/Perfect-MySQL) - A Swift wrapper around the MySQL client library, enabling access to MySQL servers. Part of the [Perfect ★11528](PerfectlySoft/Perfect) project, but stand-alone. SPM and Swift 3 support.
* [Redis](https://github.com/PerfectlySoft/Perfect-Redis) - A Swift wrapper around the Redis client library, enabling access to Redis. Part of the [Perfect ★11528](PerfectlySoft/Perfect) project, but stand-alone. SPM and Swift 3 support.
* [PostgreSQL](https://github.com/PerfectlySoft/Perfect-PostgreSQL) - A Swift wrapper around the libpq client library, enabling access to PostgreSQL servers. Part of the [Perfect ★11528](PerfectlySoft/Perfect) project, but stand-alone. SPM and Swift 3 support.
* [FileMaker](https://github.com/PerfectlySoft/Perfect-FileMaker) - A Swift wrapper around the FileMaker XML Web publishing interface, enabling access to FileMaker servers. Part of the [Perfect ★11528](PerfectlySoft/Perfect) project, but stand-alone. SPM and Swift 3 support.
* [Nora ★171](SD10/Nora) - Nora is a Firebase abstraction layer for working with FirebaseDatabase and FirebaseStorage. :large_orange_diamond:
* [PersistentStorageSerializable ★155](IvanRublev/PersistentStorageSerializable) - Swift library that makes easier to serialize the user's preferences (app's settings) with system User Defaults or Property List file on disk. :large_orange_diamond:

## Data Structures / Algorithms
* [SwiftSortedList ★3](bemindinteractive/SwiftSortedList) - A sorted list implementation written in Swift :large_orange_diamond:
* [Changeset ★649](osteslag/Changeset) - Minimal edits from one collection to another :large_orange_diamond:
* [BTree ★866](lorentey/BTree) - Fast ordered collections for Swift using in-memory B-trees :large_orange_diamond:
* [SwiftStructures ★1688](waynewbishop/SwiftStructures) - Examples of commonly used data structures and algorithms in Swift. :large_orange_diamond:
* [diff ★74](soffes/diff) - Simple diff library in pure Swift :large_orange_diamond:
* [Brick ★48](hyperoslo/Brick) - :droplet: A generic view model for both basic and complex scenarios :large_orange_diamond:
* [Algorithm ★517](CosmicMind/Algorithm) - Algorithm is a collection of data structures that are empowered by a probability toolset. :large_orange_diamond:
* [AnyObjectConvertible ★52](tarunon/AnyObjectConvertible) - Convert your own struct/enum to AnyObject easily. :large_orange_diamond:
* [Dollar ★3643](ankurp/Dollar) - A functional tool-belt for Swift Language similar to Lo-Dash or Underscore.js in Javascript https://www.dollarswift.org/. :large_orange_diamond:
* [Result ★1631](antitypical/Result) - Swift type modeling the success/failure of arbitrary operations. :large_orange_diamond:
* [EKAlgorithms ★2214](EvgenyKarkan/EKAlgorithms) - Some well known CS algorithms & data structures in Objective-C.
* [Monaka ★22](naru-jpn/Monaka) - Convert custom struct and fundamental values to NSData.
* [Buffer ★302](alexdrone/Buffer) - Swift μ-framework for efficient array diffs, collection observation and cell configuration. :large_orange_diamond:
* [SwiftGraph ★283](davecom/SwiftGraph) - Graph data structure and utility functions in pure Swift. :large_orange_diamond:
* [SwiftPriorityQueue ★215](davecom/SwiftPriorityQueue) - A priority queue with a classic binary heap implementation in pure Swift. :large_orange_diamond:
* [Pencil ★64](naru-jpn/pencil) - Write values to file and read it more easily. :large_orange_diamond:
* [HeckelDiff ★21](mcudich/HeckelDiff) - A fast Swift diffing library. :large_orange_diamond:
* [Dekoter ★17](artemstepanenko/Dekoter) - `NSCoding`'s counterpart for Swift structs. :large_orange_diamond:

## Date & Time

* [Every.swift ★276 ⏳1Y](samhann/Every.swift) - A swift wrapper for NSTimer  :large_orange_diamond:
* [Timepiece ★2046](naoty/Timepiece) - Intuitive NSDate extensions in Swift :large_orange_diamond:
* [SwiftDate ★2960](malcommac/SwiftDate) - Easy NSDate Management in Swift 2.0 :large_orange_diamond:
* [SwiftMoment ★1442](akosma/SwiftMoment) - A time and calendar manipulation library written in Swift 2 :large_orange_diamond:
* [DateTools ★5471](MatthewYork/DateTools) - Dates and times made easy in Objective-C
* [Punctual.swift ★318](harlanhaskins/Punctual.swift) - Swift dates, more fun. :large_orange_diamond:
* [SwiftyTimer ★852](radex/SwiftyTimer) - Swifty API for NSTimer :large_orange_diamond:
* [DateHelper ★778](melvitax/DateHelper) - Convenience extension for NSDate in Swift :large_orange_diamond:
* [Tempo ★153 ⏳2Y](remirobert/Tempo) - :watch: Date and time manager for iOS/OSX written in Swift :large_orange_diamond:
* [iso-8601-date-formatter ★589](boredzo/iso-8601-date-formatter) - A Cocoa NSFormatter subclass to convert dates to and from ISO-8601-formatted strings. Supports calendar, week, and ordinal formats.
* [EmojiTimeFormatter ★76](thomaspaulmann/EmojiTimeFormatter) - Format your dates/times as emojis. :large_orange_diamond:
* [Kronos ★207](lyft/Kronos) - Elegant NTP date library in Swift :large_orange_diamond:
* [TrueTime ★164](instacart/TrueTime.swift) - Get the true current time impervious to device clock time changes. (NTP library for Swift) . :large_orange_diamond:
* [10Clock ★411](joedaniels29/10Clock) - This Control is a beautiful time-of-day picker heavily inspired by the iOS 10 "Bedtime" timer. :large_orange_diamond:
* [NSDate-TimeAgo ★1650](kevinlawler/NSDate-TimeAgo) - A "time ago", "time since", "relative date", or "fuzzy date" category for NSDate and iOS, Objective-C, Cocoa Touch, iPhone, iPad.
* [ServerSync ★4](skylovely/ServerSync-iOS) - Synchronize server's UTC time and app's UTC time :large_orange_diamond:[e]

## EventBus
* [SwiftEventBus ★536](cesarferreira/SwiftEventBus) - A publish/subscribe event bus optimized for iOS8. :large_orange_diamond:
* [PromiseKit ★7655](mxcl/PromiseKit) - Promises for iOS and OS X.
* [Bolts ★5104](BoltsFramework/Bolts-ObjC) - Bolts is a collection of low-level libraries designed to make developing mobile apps easier, including tasks (promises) and app links (deep links).
* [SwiftTask ★1679](ReactKit/SwiftTask) - Promise + progress + pause + cancel + retry for Swift.  :large_orange_diamond:
* [When ★74](vadymmarkov/When) - A lightweight implementation of Promises in Swift. :large_orange_diamond:
* [then🎬 ★515](freshOS/then) - Elegant Async code in Swift. :large_orange_diamond:
* [Bolts-Swift ★965](BoltsFramework/Bolts-Swift) - Bolts is a collection of low-level libraries designed to make developing mobile apps easier. :large_orange_diamond:
* [RWPromiseKit ★91](deput/RWPromiseKit) - A light-weighted Promise library for Objective-C
* [FutureLib ★40](couchdeveloper/FutureLib) - FutureLib is a pure Swift 2 library implementing Futures & Promises inspired by Scala. :large_orange_diamond:
* [SwiftNotificationCenter ★419](100mango/SwiftNotificationCenter) - A Protocol-Oriented NotificationCenter which is type safe, thread safe and with memory safety :large_orange_diamond:
* [FutureKit ★631](FutureKit/FutureKit) - A Swift based Future/Promises Library for IOS and OS X. :large_orange_diamond:
* [signals-ios ★472](uber/signals-ios) - Typeful eventing
* [BrightFutures ★1440](Thomvis/BrightFutures) - Write great asynchronous code in Swift using futures and promises. :large_orange_diamond:
* [NoticeObserveKit ★106](marty-suzuki/NoticeObserveKit) - NoticeObserveKit is type-safe NotificationCenter wrapper that associates notice type with info type. :large_orange_diamond:
* [Hydra ★1003](malcommac/Hydra) - Promises & Await - Write better async code in Swift :large_orange_diamond:

## Files
* [FileKit ★1381](nvzqz/FileKit) - Simple and expressive file management in Swift. :large_orange_diamond:
* [Zip ★960](marmelroy/Zip) - Swift framework for zipping and unzipping files. :large_orange_diamond:
* [FileBrowser ★1020](marmelroy/FileBrowser) - Powerful Swift file browser for iOS. :large_orange_diamond:
* [Ares ★113 ⏳1Y](indragiek/Ares) - Zero-setup P2P file transfer between Macs and iOS devices :large_orange_diamond:
* [FileProvider ★112](amosavian/FileProvider) - FileManager replacement for Local, iCloud and Remote (WebDAV/FTP/Dropbox/OneDrive/SMB2) files on iOS/tvOS and macOS. :large_orange_diamond:
* [KZFileWatchers ★760](krzysztofzablocki/KZFileWatchers) - A micro-framework for observing file changes, both local and remote. Helpful in building developer tools. :large_orange_diamond:
* [ZipArchive ★2801](ZipArchive/ZipArchive) - ZipArchive is a simple utility class for zipping and unzipping files on iOS and Mac.
* [FileExplorer ★473](Augustyniak/FileExplorer) - Powerful file browser for iOS that allows its users to choose and remove files and/or directories. :large_orange_diamond:

## Functional Programming
* [Forbind ★44](ulrikdamm/Forbind) - Functional chaining and promises in Swift. :large_orange_diamond:
* [Funky ★12 ⏳1Y](brynbellomy/Funky) - Functional programming tools and experiments in Swift. :large_orange_diamond:
* [LlamaKit ★634 ⏳1Y](LlamaKit/LlamaKit) - Collection of must-have functional Swift tools. :large_orange_diamond:
* [Oriole ★11 ⏳1Y](tptee/Oriole) - A functional utility belt implemented as Swift 2.0 protocol extensions. :large_orange_diamond:[e]
* [Prelude ★294](robrix/Prelude) - Swift µframework of simple functional programming tools. :large_orange_diamond:
* [Swiftx ★173](typelift/Swiftx) - Functional data types and functions for any project. :large_orange_diamond:
* [Swiftz ★2923](typelift/Swiftz) -  Functional programming in Swift. :large_orange_diamond:
* [OptionalExtensions ★166](RuiAAPeres/OptionalExtensions) - Swift µframework with extensions for the  Optional Type. :large_orange_diamond:[e]
* [Hookah ★57](HookahSwift/Hookah) - Hookah is a functional library for Swift. It's inspired by LoDash, Underscore project. :large_orange_diamond:
* [Argo ★3073](thoughtbot/Argo) - Functional JSON parsing library for Swift :large_orange_diamond:
* [Runes ★615](thoughtbot/Runes) - Infix operators for monadic functions in Swift. :large_orange_diamond:
* [ifAction ★1](trilliwon/ifAction) - Custom if for Optional and Boolean :large_orange_diamond: [e]

## Games
* [Sage ★318](nvzqz/Sage) - A cross-platform chess library for Swift. :large_orange_diamond:
* [ShogibanKit ★50](codelynx/ShogibanKit) - ShogibanKit is a framework for implementing complex Japanese Chess (Shogii) in Swift. No UI, nor AI. :large_orange_diamond:
* [SKTiled ★71](mfessenden/SKTiled) - Swift framework for working with Tiled assets in SpriteKit :large_orange_diamond:

## Gesture
* [Tactile ★598](delba/Tactile) - A better way to handle gestures on iOS :large_orange_diamond:
* [SwiftyGestureRecognition ★143](b3ll/SwiftyGestureRecognition) - Aids with prototyping UIGestureRecognizers in Xcode Playgrounds :large_orange_diamond:
* [DBPathRecognizer ★1053](didierbrun/DBPathRecognizer) - Gesture recognizer tool [Swift / iOS] :large_orange_diamond:
* [Sensitive ★433](igormatyushkin014/Sensitive) - Fresh look at work with gestures in Swift. :large_orange_diamond:

## Graphics
* [Graphicz ★24](SwiftKitz/Graphicz) - Light-weight, operator-overloading-free complements to CoreGraphics! :large_orange_diamond:
* [PKCoreTechniques ★142 ⏳1Y](pkluz/PKCoreTechniques) - The code for my CoreGraphics+CoreAnimation talk, held during the 2012 iOS Game Design Seminar at the Technical University Munich.
* [MPWDrawingContext ★89 ⏳1Y](mpw/MPWDrawingContext) - An Objective-C wrapper for CoreGraphics CGContext
* [DePict ★24](davidcairns/DePict) - A simple, declarative, functional drawing framework, in Swift! :large_orange_diamond:
* [SwiftSVG ★764](mchoe/SwiftSVG) -  A single pass SVG parser with multiple interface options (String, NS/UIBezierPath, CAShapeLayer, and NS/UIView). :large_orange_diamond:
* [InkKit ★332](shaps80/InkKit) - Write-Once, Draw-Everywhere for iOS and OSX -- Now in Swift! :large_orange_diamond:
* [YYAsyncLayer ★308](ibireme/YYAsyncLayer) - iOS utility classes for asynchronous rendering and display.
* [NXDrawKit ★943](Nicejinux/NXDrawKit) - NXDrawKit is a simple and easy but useful drawing kit for iPhone :large_orange_diamond:
* [jot ★1590](IFTTT/jot) - An iOS framework for easily adding drawings and text to images.
* [SVGKit ★2738](SVGKit/SVGKit) - Display and interact with SVG Images on iOS / OS X, using native rendering (CoreAnimation) (currently only supported for iOS - OS X code needs updating).
* [Snowflake ★777](onmyway133/Snowflake) - ❄️ SVG in Swift. :large_orange_diamond:
* [HxSTLParser ★6](victorgama/HxSTLParser) - Basic STL loader for SceneKit

## Hardware
#### Bluetooth
* [Discovery ★362 ⏳1Y](omergul123/Discovery) - A very simple library to discover and retrieve data from nearby devices (even if the peer app works at background).
* [LGBluetooth ★135](LGBluetooth/LGBluetooth) - Simple, block-based, lightweight library over CoreBluetooth. Will clean up your Core Bluetooth related code.
* [PeerKit ★674](jpsim/PeerKit) An open-source Swift framework for building event-driven, zero-config Multipeer Connectivity apps. :large_orange_diamond:
* [simple-share ★124 ⏳3Y](lauraskelton/simple-share) - Easy Proximity-based Bluetooth LE Sharing for iOS.
* [BluetoothKit ★1495](rhummelmose/BluetoothKit) - Easily communicate between iOS/OSX devices using BLE. :large_orange_diamond:
* [CocoaMultipeer ★85 ⏳1Y](manavgabhawala/CocoaMultipeer) - This repository is a peer to peer framework for OS X, iOS and watchOS 2 that presents a similar interface to the MultipeerConnectivity framework (which is iOS only) that lets you connect any 2 devices from any platform. :large_orange_diamond:
* [Bluetonium ★113](e-sites/Bluetonium) - Bluetooth mapping in Swift :large_orange_diamond:
* [BlueCap ★369](troystribling/BlueCap) - iOS Bluetooth LE framework :large_orange_diamond:
* [Apple Family ★21](kirankunigiri/Apple-Family) - Quickly connect Apple devices together with Bluetooth, wifi, and USB.  :large_orange_diamond:
* [Bleu ★411](1amageek/Bleu) - BLE (Bluetooth LE) for U  :large_orange_diamond:

#### Camera
* [TGCameraViewController ★1346](tdginternet/TGCameraViewController) - Custom camera with AVFoundation. Beautiful, light and easy to integrate with iOS projects.
* [PBJVision ★1674](piemonte/PBJVision) - iOS camera engine, features touch-to-record video, slow motion video, and photo capture.
* [Cool-iOS-Camera ★1145](GabrielAlva/Cool-iOS-Camera) - A fully customisable and modern camera implementation for iOS made with AVFoundation.
* [SCRecorder ★2551](rFlex/SCRecorder) - Camera engine with Vine-like tap to record, animatable filters, slow motion, segments editing.
* [ALCameraViewController ★1340](AlexLittlejohn/ALCameraViewController) - A camera view controller with custom image picker and image cropping. Written in Swift. :large_orange_diamond:
* [ImagePicker ★2814](hyperoslo/ImagePicker) - Reinventing the way ImagePicker works. :large_orange_diamond:
* [CameraManager ★574](imaginary-cloud/CameraManager) - Simple Swift class to provide all the configurations you need to create custom camera view in your app. :large_orange_diamond:
* [RSBarcodes_Swift ★529](yeahdongcn/RSBarcodes_Swift) - 1D and 2D barcodes reader and generators for iOS 8 with delightful controls. Now Swift. :large_orange_diamond:
* [LLSimpleCamera ★1044](omergul123/LLSimpleCamera) - A simple, customizable camera control - video recorder for iOS.
* [Fusuma ★1657](ytakzk/Fusuma) - Instagram-like photo browser and a camera feature with a few line of code in Swift. :large_orange_diamond:
* [BarcodeScanner ★618](hyperoslo/BarcodeScanner) - 🔎 Simple and beautiful barcode scanner. :large_orange_diamond:
* [JVTImageFilePicker ★41](mcmatan/JVTImageFilePicker) - Easy and beautiful way for a user to pick content, files or images. Written in Objective C.
* [HorizonSDK-iOS ★156](HorizonCamera/HorizonSDK-iOS) - State of the art real-time video recording / photo shooting iOS library.
* [FastttCamera ★1658](IFTTT/FastttCamera) - Fasttt and easy camera framework for iOS with customizable filters
* [DKCamera ★25](zhangao0086/DKCamera) - A lightweight & simple camera framework for iOS. Written in Swift. 🔶
* [NextLevel ★797](NextLevel/NextLevel) - Next Level is a media capture camera library for iOS. :large_orange_diamond:
* [CameraEngine ★381](remirobert/CameraEngine) - 🐒📷 Camera engine for iOS, written in Swift, above AVFoundation. 🐒 :large_orange_diamond:
* [SwiftyCam ★756](Awalz/SwiftyCam) -  A Snapchat Inspired iOS Camera Framework written in Swift. :large_orange_diamond:

#### Force Touch
* [QuickActions ★182](ricardopereira/QuickActions) - Swift wrapper for iOS Home Screen Quick Actions (App Icon Shortcuts) :large_orange_diamond:
* [JustPeek ★48](justeat/JustPeek) - JustPeek is an iOS Library that adds support for Force Touch-like Peek and Pop interactions on devices that do not natively support this kind of interaction. :large_orange_diamond:

#### iBeacon
* [Proxitee ★15 ⏳2Y](Proxitee/iOS-SDK) - Allows developers to create proximity aware applications utilizing iBeacons & geo fences.
* [OWUProximityManager ★359 ⏳3Y](ohayon/OWUProximityManager) - iBeacons + CoreBluetooth.
* [Vicinity ★357](Instrument/Vicinity) - Vicinity replicates iBeacons (by analyzing RSSI) and supports broadcasting and detecting low-energy Bluetooth devices in the background.
* [BeaconEmitter ★795 ⏳2Y](lgaches/BeaconEmitter) - Turn your Mac as an iBeacon.
* [MOCA Proximity](https://mocaplatform.com/features) - Paid proximity marketing platform that lets you add amazing proximity  experiences to your app.
* [JMCBeaconManager ★131](izotx/JMCBeaconManager) - An iBeacon Manager class that is responsible for detecting beacons nearby. 🔶

## Layout
* [FlexboxLayout ★286](alexdrone/FlexboxLayout) - Port of Facebook's css-layout to Swift :large_orange_diamond:
* [Masonry ★14879](SnapKit/Masonry) - Harness the power of AutoLayout NSLayoutConstraints with a simplified, chainable and expressive syntax.
* [FLKAutoLayout ★1495](floriankugler/FLKAutoLayout) - UIView category which makes it easy to create layout constraints in code.
* [Façade ★707](mamaral/Facade) - Programmatic view layout for the rest of us - an autolayout alternative.
* [PureLayout ★6432](PureLayout/PureLayout) - The ultimate API for iOS & OS X Auto Layout — impressively simple, immensely powerful. Objective-C and Swift compatible.
* [SnapKit ★9827](SnapKit/SnapKit) - A Swift Autolayout DSL for iOS & OS X. :large_orange_diamond:
* [Cartography ★5626](robb/Cartography) - A declarative Auto Layout DSL for Swift :iphone::triangular_ruler: :large_orange_diamond:
* [AutoLayoutPlus ★25](ruipfcosta/AutoLayoutPlus) - A bit of steroids for AutoLayout, powered by Swift. :large_orange_diamond:
* [Neon ★3945](mamaral/Neon) - A powerful Swift programmatic UI layout framework. :large_orange_diamond:
* [MisterFusion ★252](marty-suzuki/MisterFusion) - A Swift DSL for AutoLayout. It is the extremely clear, but concise syntax, in addition, can be used in both Swift and Objective-C. :large_orange_diamond:
* [SwiftBox ★781](joshaber/SwiftBox) - Flexbox in Swift, using Facebook's css-layout. :large_orange_diamond:
* [ManualLayout ★259](isair/ManualLayout) - Easy to use and flexible library for manually laying out views and layers for iOS and tvOS. Supports AsyncDisplayKit. :large_orange_diamond:[e]
* [Stevia ★2035](freshOS/Stevia) - Elegant view layout for iOS. :large_orange_diamond:
* [Manuscript ★79](floriankrueger/Manuscript) - AutoLayoutKit in pure Swift. :large_orange_diamond:
* [FDTemplateLayoutCell ★7656](forkingdog/UITableView-FDTemplateLayoutCell) - Template auto layout cell for automatically UITableViewCell height calculating
* [SwiftAutoLayout ★646](indragiek/SwiftAutoLayout) - Tiny Swift DSL for Autolayout :large_orange_diamond:
* [FormationLayout ★52](evan-liu/FormationLayout) - Work with auto layout and size classes easily. :large_orange_diamond:
* [SwiftyLayout ★13](fhisa/SwiftyLayout) - Lightweight declarative auto-layout framework for Swift :large_orange_diamond:
* [Swiftstraints ★93](Skyvive/Swiftstraints) - Auto Layout In Swift Made Easy :large_orange_diamond:
* [SwiftBond ★3130](ReactiveKit/Bond) - Bond is a Swift binding framework that takes binding concepts to a whole new level. It's simple, powerful, type-safe and multi-paradigm. :large_orange_diamond:
* [Restraint ★72](puffinsupply/Restraint) - Minimal Auto Layout in Swift :large_orange_diamond:
* [EasyPeasy ★1495](nakiostudio/EasyPeasy) - Auto Layout made easy  :large_orange_diamond:
* [Auto Layout Magic](http://akordadev.github.io/AutoLayoutMagic/) - Build 1 scene, let Auto Layout Magic generate the  constraints for you!  Scenes look great across all devices! :large_orange_diamond:
* [Anchorman ★49](mergesort/Anchorman) - An autolayout library for the damn fine citizens of San Diego. :large_orange_diamond:
* [LayoutKit ★2044](linkedin/LayoutKit) - LayoutKit is a fast view layout library for iOS. :large_orange_diamond:
* [MarkupKit ★393](gk-brown/MarkupKit) - Declarative UI for iOS applications
* [Relayout ★578](stevestreza/Relayout) - Swift microframework for declaring Auto Layout constraints functionally :large_orange_diamond:
* [Anchorage ★266](Raizlabs/Anchorage) - A collection of operators and utilities that simplify iOS layout code. :large_orange_diamond:
* [Compose ★123](VivaReal/Compose) - Compose is a library that helps you compose complex and dynamic views. :large_orange_diamond:
* [BrickKit ★515](wayfair/brickkit-ios) - With BrickKit, you can create complex and responsive layouts in a simple way. It's easy to use and easy to extend. Create your own reusable bricks and behaviors. :large_orange_diamond:
* [Framezilla ★59](Otbivnoe/Framezilla) - Elegant library which wraps working with frames with a nice chaining syntax. :large_orange_diamond:
* [TinyConstraints ★1588](roberthein/TinyConstraints) -  The syntactic sugar that makes Auto Layout sweeter for human use. :large_orange_diamond:
* [MyLinearLayout ★2137](youngsoft/MyLinearLayout) - MyLayout is a powerful iOS UI framework implemented by Objective-C. It integrates the functions with Android Layout,iOS AutoLayout,SizeClass, HTML CSS float and flexbox and bootstrap.
* [SugarAnchor ★17](ashikahmad/SugarAnchor) - Same native NSLayoutAnchor & NSLayoutConstraints; but with more natural and easy to read syntactic sugar. Typesafe, concise & readable. :large_orange_diamond:
* [Anchors ★63](onmyway133/Anchors) - Declarative, extensible, powerful Auto Layout for iOS 8+ and macOS 10.10+ :large_orange_diamond:
* [PinLayout ★2](mirego/PinLayout) - Layout most views using a single line without constraints. Stateless, so it can be used with any other Layout frameworks without conflicts. Consise syntax, readable & chainable. 🔶
* [SnapLayout ★7](sp71/SnapLayout) - Concise Auto Layout API to chain programmatic constraints while easily updating existing constraints. 🔶[e]

#### Location
* [IngeoSDK ★85](IngeoSDK/ingeo-ios-sdk) - Always-On Location monitoring framework for iOS.
* [LocationManager ★2046](intuit/LocationManager) - Provides a block-based asynchronous API to request the current location, either once or continuously.
* [SwiftLocation ★1244](malcommac/SwiftLocation) - Location & Beacon Monitoring in Swift :large_orange_diamond:
* [SOMotionDetector ★973](SocialObjects-Software/SOMotionDetector) - Simple library to detect motion. Based on location updates and acceleration.
* [LocationPicker ★257](JeromeTan1997/LocationPicker) - A ready for use and fully customizable location picker for your app :large_orange_diamond:
* [PlaceKit](http://www.placekit.io/) - Advanced location SDK - highly accurate location data with very low battery drain and contextual location information :large_orange_diamond:
* [BBLocationManager ★51](benzamin/BBLocationManager) - A Location Manager for easily implementing location services & geofencing in iOS.
* [set-simulator-location ★155](lyft/set-simulator-location) - CLI for setting location in the iOS simulator. :large_orange_diamond:

#### Other Hardware
* [MotionKit ★924](MHaroonBaig/MotionKit) - Get the data from Accelerometer, Gyroscope and Magnetometer in only Two or a few lines of code. CoreMotion now made insanely simple.
* [DarkLightning ★154](jensmeder/DarkLightning) - Simply the fastest way to transmit data between iOS/tvOS and OSX.
* [Deviice ★20](andrealufino/Deviice) - Simply library to detect the device on which the app is running (and some properties) 🔶
* [DeviceKit ★1204](dennisweissmann/DeviceKit) - DeviceKit is a value-type replacement of UIDevice. :large_orange_diamond:
* [Luminous ★140](andrealufino/Luminous) - Luminous is a big framework which can give you a lot of information (more than 50) about the current system. :large_orange_diamond:
* [Device ★885](Ekhoo/Device) - Light weight tool for detecting the current device and screen size written in swift. :large_orange_diamond:
* [WatchShaker ★133](ezefranca/WatchShaker) - WatchShaker is a watchOS helper to get your ⌚️ shake movement written in swift. :large_orange_diamond:
* [WatchCon ★24](abdullahselek/WatchCon) - WatchCon is a tool which enables creating easy connectivity between iOS and WatchOS. ⌚️
* [TapticEngine ★140](WorldDownTown/TapticEngine) - TapticEngine generates iOS Device vibrations. :large_orange_diamond:

## Localization
* [Hodor ★474](Aufree/Hodor) - Simple solution to localize your iOS App.
* [Swifternalization ★493](tomkowz/Swifternalization) - Localize iOS apps in a smarter way using JSON files. Swift framework. :large_orange_diamond:
* [Rubustrings ★43](dcordero/Rubustrings) - Check the format and consistency of Localizable.strings files
* [BartyCrouch ★210](Flinesoft/BartyCrouch) - Incrementally update/translate your Strings files from Code and Storyboards/XIBs. :large_orange_diamond:
* [Lin ★1226 ⏳1Y](questbeat/Lin) - Xcode plugin that provides auto-completion for NSLocalizedString.
* [LocalizationKit ★823](willpowell8/LocalizationKit_iOS) - Localization management in realtime from a web portal. Easily manage your texts and translations without redeploy and resubmission.
* [Localize-Swift ★1305](marmelroy/Localize-Swift) - Swift 2.0 friendly localization and i18n with in-app language switching :large_orange_diamond:
* [LocalizedView ★7](darkcl/LocalizedView) - Setting up application specific localized string within Xib file.
* [transai ★38](Jintin/transai) - command line tool help you manage localization string files.
* [lokalise](https://lokalise.co/en ) - Translation platform for software developers. Free for open source projects
* [Strsync ★96](metasmile/strsync) - Automatically translate and synchronize .strings files from base language.
* [IBLocalizable ★380](PiXeL16/IBLocalizable) - Localize your views directly in Interface Builder with IBLocalizable :large_orange_diamond:
* [extract-localizable-string-plugin-xcode ★217 ⏳1Y](viniciusmo/extract-localizable-string-plugin-xcode) - Xcode plugin for quickly creating localized strings
* [nslocalizer ★114](samdmarshall/nslocalizer) - A tool for finding missing and unused NSLocalizedStrings

## Logging
* [CleanroomLogger ★1005](emaloney/CleanroomLogger) - A configurable and extensible Swift-based logging API that is simple, lightweight and performant. :large_orange_diamond:
* [CocoaLumberjack ★9092](CocoaLumberjack/CocoaLumberjack) - A fast & simple, yet powerful & flexible logging framework for Mac and iOS.
* [NSLogger ★3924](fpillet/NSLogger) - a high performance logging utility which displays traces emitted by client applications running on Mac OS X, iOS and Android.
* [QorumLogs ★692](goktugyil/QorumLogs) — Swift Logging Utility for Xcode & Google Docs. :large_orange_diamond:
* [Log ★631](delba/Log) - A logging tool with built-in themes, formatters, and a nice API to define your owns. :large_orange_diamond:
* [Rainbow ★847](onevcat/Rainbow) - Delightful console output for Swift developers. :large_orange_diamond:
* [LinkedConsole ★896](krzysztofzablocki/LinkedConsole) - Clickable links in your Xcode console, so you never wonder which class logged the message. http://merowing.info :large_orange_diamond:
* [SwiftyBeaver ★2766](SwiftyBeaver/SwiftyBeaver) - Convenient logging during development & release in Swift 2 & 3 :large_orange_diamond:
* [SwiftyTextTable ★86](scottrhoyt/SwiftyTextTable) - A lightweight tool for generating text tables. :large_orange_diamond:
* [Watchdog ★1371](wojteklu/Watchdog) - Class for logging excessive blocking on the main thread :large_orange_diamond:
* [XCGLogger ★2408](DaveWoodCom/XCGLogger) - A debug log framework for use in Swift projects. Allows you to log details to the console (and optionally a file), just like you would have with NSLog or println, but with additional information, such as the date, function name, filename and line number. :large_orange_diamond:
* [puree ★133](cookpad/puree-ios) - A log collector for iOS
* [AFNetworkActivityLogger ★472](AFNetworking/AFNetworkActivityLogger) - AFNetworking 2.0 Extension for Network Request Logging
* [Colors ★21](icodeforlove/Colors) - A pure Swift library for using ANSI codes. Basically makes command-line coloring and styling very easy! :large_orange_diamond:[e]
* [Loggerithm ★265](honghaoz/Loggerithm) - A lightweight Swift logger, uses `print` in development and `NSLog` in production. Support colourful and formatted output. :large_orange_diamond:
* [AELog ★7](tadija/AELog) - Simple, lightweight and flexible debug logging framework written in Swift. :large_orange_diamond:
* [AEConsole ★65](tadija/AEConsole) - Customizable Console UI overlay with debug log on top of your iOS App. :large_orange_diamond:
* [ReflectedStringConvertible ★48](mattcomi/ReflectedStringConvertible) - A protocol that allows any class to be printed as if it were a struct. :large_orange_diamond:
* [Evergreen ★62](knly/Evergreen) - Most natural Swift logging :large_orange_diamond:
* [Logkit ★122](logkit/logkit) - An efficient logging library for OS X, iOS, watchOS, and tvOS – written in Swift. Log to console, file, HTTP service, or your own endpoint. Simple to get started, but smartly customizable :large_orange_diamond:
* [SwiftTrace ★118](johnno1962/SwiftTrace) - Trace Swift and Objective-C method invocations :large_orange_diamond:
* [Willow ★973](Nike-Inc/Willow) - Willow is a powerful, yet lightweight logging library written in Swift. :large_orange_diamond:
* [Bugfender ★33](bugfender/BugfenderSDK-iOS) - Cloud storage for your app logs. Track user behaviour to find problems in your mobile apps.
* [LxDBAnything ★415](DeveloperLx/LxDBAnything) - Automate box any value! Print log without any format control symbol! Change debug habit thoroughly!
* [XLTestLog ★57](xareelee/XLTestLog) - Styling and coloring your XCTest logs on Xcode Console
* [XLFacility ★246](swisspol/XLFacility) - Elegant and extensive logging facility for OS X & iOS (includes database, Telnet and HTTP servers)
* [Atlantis ★202](DrewKiino/Atlantis) - A powerful input-agnostic swift logging framework made to speed up development with maximum readability. :large_orange_diamond:
* [StoryTeller ★8](drekka/StoryTeller) - Taking a completely different approach to logging, Story Teller replacing fixed logging levels in It then uses dynamic expressions to control the logging so you only see what is important.
* [LumberMill ★2](ubclaunchpad/LumberMill) - Stupidly simple logging for iOS 10 and Swift 3.0
* [TinyConsole ★1663](Cosmo/TinyConsole) - A tiny log console to display information while using your iOS app. Written in Swift 3. :large_orange_diamond:
* [Lighty ★33](abdullahselek/Lighty) - Easy to use and lightweight logger for iOS, macOS, tvOS, watchOS and Linux with Swift 3. :large_orange_diamond:
* [JustLog ★158](justeat/JustLog) - Console, file and remote Logstash logging via TCP socket. :large_orange_diamond:
* [Twitter Logging Service ★156](twitter/ios-twitter-logging-service) - Twitter Logging Service is a robust and performant logging framework for iOS clients.
* [Reqres ★12](AckeeCZ/Reqres) - Network request and response body logger with Alamofire support :large_orange_diamond:
* [GodEye ★2460](zixun/GodEye) - Automatically display Log,Crash,Network,ANR,Leak,CPU,RAM,FPS,NetFlow,Folder and etc with one line of code based on Swift. :large_orange_diamond:

## Machine Learning
* [Swift-AI ★4692](Swift-AI/Swift-AI) - Highly optimized Artificial Intelligence and Machine Learning library written in Swift. :large_orange_diamond:
* [Swift-Brain ★285](vlall/Swift-Brain) - Artificial Intelligence/Machine Learning data structures and Swift algorithms for future iOS development. Bayes theorem, Neural Networks, and more AI. :large_orange_diamond:
* [AIToolbox ★579](KevinCoble/AIToolbox) - A toolbox of AI modules written in Swift: Graphs/Trees, Linear Regression, Support Vector Machines, Neural Networks, PCA, KMeans, Genetic Algorithms, MDP, Mixture of Gaussians. :large_orange_diamond:
* [Tensorflow-iOS](https://github.com/tensorflow/tensorflow/tree/master/tensorflow/contrib/ios_examples/) - The official Google-built powerful neural network library port for iOS.

## Maps
* [Route-me ★1291 ⏳4Y](route-me/route-me) - Open source map library for iOS.
* [NAMapKit ★253 ⏳1Y](neilang/NAMapKit) - Allows you to use custom maps in iPhone applications and attempts to mimics some of the behaviour of the MapKit framework.
* [Mapbox GL ★1890](mapbox/mapbox-gl-native) - An OpenGL renderer for Mapbox Vector Tiles with SDK bindings for iOS.
* [CMMapLauncher ★185 ⏳1Y](citymapper/CMMapLauncher) - iOS library that makes it quick and easy to show directions in various mapping applications.
* [GEOSwift ★784](andreacremaschi/GEOSwift) - The Swift Geographic Engine. :large_orange_diamond:
* [PXGoogleDirections ★175](poulpix/PXGoogleDirections) - Google Directions API helper for iOS, written in Swift :large_orange_diamond:
* [Cluster ★603](efremidze/Cluster) - Easy Map Annotation Clustering. :large_orange_diamond:

## Math
* [Euler ★842](mattt/Euler) - Swift Custom Operators for Mathematical Notation :large_orange_diamond:
* [SwiftMath ★136 ⏳1Y](madbat/SwiftMath) - :triangular_ruler: A math framework for Swift. Includes: vectors, matrices, complex numbers, quaternions and polynomials. :large_orange_diamond:
* [Arithmosophi ★48](phimage/Arithmosophi) - A set of protocols for Arithmetic and Logical operations :large_orange_diamond:
* [Surge ★3641](mattt/Surge) - A Swift library that uses the Accelerate framework to provide high-performance functions for matrix math, digital signal processing, and image manipulation. :large_orange_diamond:
* [Upsurge ★86](aleph7/Upsurge) - Swift math :large_orange_diamond:
* [Swift-MathEagle ★22](rugheid/Swift-MathEagle) - A general math framework to make using math easy. Currently supports function solving and optimisation, matrix and vector algebra, complex numbers, big int and big frac and general handy extensions and functions. :large_orange_diamond:
* [iosMath ★603](kostub/iosMath) - A library for displaying beautifully rendered math equations. Enables typesetting LaTeX math formulae in iOS.
* [swift-pons ★209](dankogai/swift2-pons) - Protocol-Oriented Number System in Pure Swift :large_orange_diamond:
* [BigInt ★131](lorentey/BigInt) - Arbitrary-precision arithmetic in pure Swift :large_orange_diamond:
* [SigmaSwiftStatistics ★456](evgenyneu/SigmaSwiftStatistics) - A collection of functions for statistical calculation. :large_orange_diamond:
* [VectorMath ★135](nicklockwood/VectorMath) - A Swift library for Mac and iOS that implements common 2D and 3D vector and matrix functions, useful for games or vector-based graphics :large_orange_diamond:
* [Expression ★176](nicklockwood/Expression) - A Mac and iOS library for evaluating numeric expressions at runtime :large_orange_diamond:

## Media
#### Audio
* [AudioBus](https://developer.audiob.us/) - Add Next Generation Live App-to-App Audio Routing.
* [AudioKit ★3526](audiokit/AudioKit) - A powerful toolkit for synthesizing, processing, and analyzing sounds. :large_orange_diamond:
* [EZAudio ★3900](syedhali/EZAudio) - An iOS/OSX audio visualization framework built upon Core Audio useful for anyone doing real-time, low-latency audio processing and visualizations.
* [novocaine ★2034 ⏳1Y](alexbw/novocaine) - Painless high-performance audio on iOS and Mac OS X.
* [QHSpeechSynthesizerQueue ★24 ⏳1Y](quentinhayot/QHSpeechSynthesizerQueue) - Queue management system for AVSpeechSynthesizer (iOS Text to Speech).
* [Cephalopod ★75](evgenyneu/Cephalopod) - A sound fader for AVAudioPlayer written in Swift. :large_orange_diamond:
* [Chirp ★303](trifl/Chirp) - The easiest way to prepare, play, and remove sounds in your Swift app! :large_orange_diamond:
* [Beethoven ★239](vadymmarkov/Beethoven) - An audio processing Swift library for pitch detection of musical signals. :large_orange_diamond:
* [AudioPlayerSwift]( https://github.com/tbaranes/AudioPlayerSwift) - AudioPlayer is a simple class for playing audio in iOS, macOS and tvOS apps. :large_orange_diamond:
* [AudioPlayer ★252](delannoyk/AudioPlayer) - AudioPlayer is syntax and feature sugar over AVPlayer. It plays your audio files (local & remote). :large_orange_diamond:
* [TuningFork ★335](comyar/TuningFork) - :musical_keyboard: Simple Tuner for iOS :large_orange_diamond:
* [MusicKit ★429](benzguo/MusicKit) - A framework for composing and transforming music in Swift :large_orange_diamond:
* [SubtleVolume ★566](andreamazz/SubtleVolume) - Replace the system volume popup with a more subtle indicator. :large_orange_diamond:
* [NVDSP ★318](bartolsthoorn/NVDSP) - iOS/OSX DSP for audio (with Novocaine)
* [SRGMediaPlayer-iOS ★60](SRGSSR/SRGMediaPlayer-iOS) - The SRG Media Player library for iOS provides a simple way to add a universal audio / video player to any iOS application.
* [IQAudioRecorderController ★382](hackiftekhar/IQAudioRecorderController) - A drop-in universal library allows to record audio within the app with a nice User Interface.
* [TheAmazingAudioEngine2 ★323](TheAmazingAudioEngine/TheAmazingAudioEngine2) - The Amazing Audio Engine is a sophisticated framework for iOS audio applications, built so you don't have to.
* [InteractivePlayerView ★216](AhmettKeskin/InteractivePlayerView) - Custom iOS music player view :large_orange_diamond:
* [ESTMusicIndicator ★333](Aufree/ESTMusicIndicator) - Cool Animated music indicator view written in Swift :large_orange_diamond:
* [QuietModemKit ★287](quiet/QuietModemKit) - iOS framework for the Quiet Modem (data over sound)
* [SwiftySound ★420](adamcichy/SwiftySound) - Super simple library that lets you play sounds with a single line of code (and much more). Written in Swift 3, supports iOS, macOS and tvOS. Cocoapods and Carthage compatible. :large_orange_diamond:
* [BPMAnalyser ★6](Luccifer/BPM-Analyser) - Fast and simple instrument to get the BPM rate from your audio-files. :large_orange_diamond:

#### GIF
* [YLGIFImage ★1618](liyong03/YLGIFImage) - Async GIF image decoder and Image viewer supporting play GIF images. It just use very less memory.
* [FLAnimatedImage ★5660](Flipboard/FLAnimatedImage) - Performant animated GIF engine for iOS
* [gifu ★1698](kaishin/gifu) - Highly performant animated GIF support for iOS in Swift :large_orange_diamond:
* [AnimatedGIFImageSerialization ★1009](mattt/AnimatedGIFImageSerialization) - Complete Animated GIF Support for iOS, with Functions, NSJSONSerialization-style Class, and (Optional) UIImage Swizzling
* [XAnimatedImage ★578 ⏳1Y](khaledmtaha/XAnimatedImage) - XAnimatedImage is a performant animated GIF engine for iOS written in Swift based on FLAnimatedImage :large_orange_diamond:
* [SwiftGif ★608](bahlo/SwiftGif) - :sparkles: A small UIImage extension with gif support :large_orange_diamond:
* [APNGKit ★1181](onevcat/APNGKit) - High performance and delightful way to play with APNG format in iOS. :large_orange_diamond:
* [YYImage ★902](ibireme/YYImage) - Image framework for iOS to display/encode/decode animated WebP, APNG, GIF, and more.
* [AImage ★713](wangjwchn/AImage) - A animated GIF&APNG engine for iOS in Swift with low memory & cpu usage.Optimized for Multi-Image case.:large_orange_diamond:
* [NSGIF2 ★50](metasmile/NSGIF2) - Simplify creation of a GIF from the provided video file url.
* [SwiftyGif ★623](kirualex/SwiftyGif) - High performance GIF engine :large_orange_diamond:

#### Image
* [GPU Image ★15708](BradLarson/GPUImage) - An open source iOS framework for GPU-based image and video processing.
* [UIImage DSP ★371 ⏳4Y](gdawg/uiimage-dsp) - IOS UIImage processing functions using the vDSP/Accelerate framework for speed.
* [AsyncImageView ★941](nicklockwood/AsyncImageView) - Simple extension of UIImageView for loading and displaying images asynchronously without lock up the UI.
* [SDWebImage ★17768](rs/SDWebImage) - Asynchronous image downloader with cache support with an UIImageView category.
* [DFImageManager ★1210](kean/DFImageManager) - Modern framework for fetching images from various sources. Zero config yet immense customization and extensibility. Uses NSURLSession.
* [MapleBacon ★185](zalando-incubator/MapleBacon) - An image download and caching library for iOS written in Swift. :large_orange_diamond:
* [NYTPhotoViewer ★2059](NYTimes/NYTPhotoViewer) - Slideshow and image viewer.
* [IDMPhotoBrowser ★2320](thiagoperes/IDMPhotoBrowser) - Photo Browser / Viewer.
* [JTSImageViewController ★2215](jaredsinclair/JTSImageViewController) - Interactive iOS image viewer.
* [Concorde ★1225 ⏳1Y](contentful-labs/Concorde) - Download and decode progressive JPEGs.
* [TOCropViewController ★1545](TimOliver/TOCropViewController) - A view controller that allows users to crop UIImage objects.
* [YXTMotionView ★76 ⏳1Y](hanton/YXTMotionView) - A custom image view that implements device motion scrolling.
* [PINRemoteImage ★2952](pinterest/PINRemoteImage) - A thread safe, performant, feature rich image fetcher.
* [SABlurImageView ★443](marty-suzuki/SABlurImageView) - Easily Adding Animated Blur/Unblur Effects To An Image. :large_orange_diamond:
* [FastImageCache ★7395](path/FastImageCache) - iOS library for quickly displaying images while scrolling.
* [BKAsciiImage ★396 ⏳2Y](bkoc/BKAsciiImage) - Convert UIImage to ASCII art
* [AlamofireImage ★2456](Alamofire/AlamofireImage) - An image component library for Alamofire. :large_orange_diamond:
* [Nuke ★2188](kean/Nuke) - Image loading, processing, caching and preheating :large_orange_diamond:
* [FlagKit ★1392](madebybowtie/FlagKit) - Beautiful flag icons for usage in apps and on the web. :large_orange_diamond:
* [YYWebImage ★2736](ibireme/YYWebImage) - Asynchronous image loading framework (supports WebP, APNG, GIF).
* [RSKImageCropper ★1668](ruslanskorb/RSKImageCropper) - An image cropper for iOS like in the Contacts app with support for landscape orientation.
* [Silo ★10 ⏳1Y](josejuanqm/Silo) - Image loading framework with loaders. :large_orange_diamond:
* [Ody ★40](josejuanqm/Ody) - Ody is an easy to use random image generator built with Swift, Perfect for placeholders. :large_orange_diamond:
* [Banana ★16](gauravkatoch007/banana) - Image slider with very simple interface. :large_orange_diamond:
* [JDSwiftAvatarProgress ★78](JellyDevelopment/JDSwiftAvatarProgress) - Easy customizable avatar image asynchronously with progress bar animated :large_orange_diamond:
* [Kingfisher ★8508](onevcat/Kingfisher) - A lightweight and pure Swift implemented library for downloading and caching image from the web. :large_orange_diamond:
* [EBPhotoPages ★1578](EddyBorja/EBPhotoPages) - A photo gallery for iOS with a modern feature set. Similar features as the Facebook photo browser.
* [UIImageView-BetterFace-Swift ★431](croath/UIImageView-BetterFace-Swift) - The Swift version of https://github.com/croath/UIImageView-BetterFace :large_orange_diamond:
* [KFSwiftImageLoader ★334](kiavashfaisali/KFSwiftImageLoader) - An extremely high-performance, lightweight, and energy-efficient pure Swift async web image loader with memory and disk caching for iOS and  Watch. :large_orange_diamond:
* [Toucan ★1942](gavinbunney/Toucan) - Fabulous Image Processing in Swift :large_orange_diamond:
* [ImageLoaderSwift ★257](hirohisa/ImageLoaderSwift) - A lightweight and fast image loader for iOS written in Swift. :large_orange_diamond:
* [ImageScout ★844](kaishin/ImageScout) - A Swift implementation of fastimage. Supports PNG, GIF, and JPEG. :large_orange_diamond:
* [JLStickerTextView ★327](luiyezheng/JLStickerTextView) - A UIImageView allow you to add multiple Label (multiple line text support) on it, you can edit, rotate, resize the Label as you want with one finger ,then render the text on Image. :large_orange_diamond:
* [Agrume ★184](JanGorman/Agrume) - A lemony fresh iOS image viewer written in Swift. :large_orange_diamond:
* [PASImageView ★163](abiaad/PASImageView) - Rounded async imageview downloader lightly cached and written in Swift :large_orange_diamond:
* [Navi ★111](nixzhu/Navi) - Focus on avatar caching. :large_orange_diamond:
* [SwiftPhotoGallery ★61](Inspirato/SwiftPhotoGallery) - Simple, fullscreen image gallery with tap, swipe, and pinch gestures. :large_orange_diamond:
* [MetalAcc ★181 ⏳1Y](wangjwchn/MetalAcc) - GPU-based Media processing library using Metal written in Swift.:large_orange_diamond:
* [MWPhotoBrowser ★7372](mwaterfall/MWPhotoBrowser) - A simple iOS photo and video browser with grid view, captions and selections.
* [UIImageColors ★1597](jathu/UIImageColors) - iTunes style color fetcher for UIImage. :large_orange_diamond:[e]
* [CDFlipView ★94](jibeex/CDFlipView) - A view that takes a set of images, make transition from one to another by using flipping effects.
* [GPUImage2 ★3119](BradLarson/GPUImage2) - GPUImage 2 is a BSD-licensed Swift framework for GPU-accelerated video and image processing. :large_orange_diamond:
* [TGLParallaxCarousel ★383](taglia3/TGLParallaxCarousel) - A lightweight 3D Linear Carousel with parallax effect :large_orange_diamond:
* [ImageButter ★379](dollarshaveclub/ImageButter) - Makes dealing with images buttery smooth
* [SKPhotoBrowser ★1196](suzuki-0000/SKPhotoBrowser) - Simple PhotoBrowser/Viewer inspired by Facebook, Twitter photo browsers written by swift :large_orange_diamond:
* [YUCIHighPassSkinSmoothing ★647 ⏳1Y](YuAo/YUCIHighPassSkinSmoothing) - An implementation of High Pass Skin Smoothing using Apple's Core Image Framework
* [CLImageViewPopup ★19](vinbhai4u/CLImageViewPopup) - A simple Image full screen pop up :large_orange_diamond:
* [APKenBurnsView ★38](Alterplay/APKenBurnsView) - Ken Burns effect with face recognition! :large_orange_diamond:
* [Moa ★251](evgenyneu/moa) - An image download extension of the image view for iOS, tvOS and macOS. :large_orange_diamond:[e]
* [JMCMarchingAnts ★123](izotx/JMCMarchingAnts) - Library that lets you add marching ants (animated) selection to the edges of the images. :large_orange_diamond:
* [ImageViewer ★1186](MailOnline/ImageViewer) - An image viewer à la Twitter :large_orange_diamond:
* [FaceAware ★1932](BeauNouvelle/FaceAware) - An extension that gives UIImageView the ability to focus on faces within an image when using AspectFill. :large_orange_diamond:
* [SwiftyAvatar ★149](dkalaitzidis/SwiftyAvatar) - A UiimageView class for creating circular avatar images, IBDesignable to make all changes via storyboard
* [ShinpuruImage ★59 ⏳1Y](FlexMonkey/ShinpuruImage) - Syntactic Sugar for Accelerate/vImage and Core Image Filters :large_orange_diamond:
* [ImagePickerSheetController ★1301](lbrndnr/ImagePickerSheetController) - ImagePickerSheetController is like the custom photo action sheet in iMessage just without the glitches. :large_orange_diamond:
* [ComplimentaryGradientView ★494](gkye/ComplimentaryGradientView) - Create complementary gradients generated from dominant and prominent colors in supplied image. Inspired by Grade.js. :large_orange_diamond:
* [ImageSlideshow ★566](zvonicek/ImageSlideshow) - Swift image slideshow with circular scrolling, timer and full screen viewer. :large_orange_diamond:
* [Imaginary ★64](hyperoslo/Imaginary) - 🦄 Remote images, as easy as one, two, three. :large_orange_diamond:
* [PPAssetsActionController ★46](pantuspavel/PPAssetsActionController) - Highly customizable Action Sheet Controller with Assets Preview. :large_orange_diamond:
* [Vulcan ★271](jinSasaki/Vulcan) - Multi image downloader with priority in Swift. :large_orange_diamond:
* [FacebookImagePicker ★62](terflogag/FacebookImagePicker) - Facebook album photo picker written in Swift. :large_orange_diamond:
* [Lightbox ★93](hyperoslo/Lightbox) - A convenient and easy to use image viewer for your iOS app. :large_orange_diamond:
* [AvatarImageView ★182](ayushn21/AvatarImageView) - AvatarImageView is a UIImageView subclass designed to show a user's profile picture, falling back to their initials when a picture is unavailable. :large_orange_diamond:
* [Ebblink ★3](ebbapp/ebblinkSDK) - An iOS SDK for sharing photos that automatically expire and can be deleted at any time.
* [Sharaku ★1148](makomori/Sharaku) - Instagram-like image filter ViewController. :large_orange_diamond:
* [CTPanoramaView ★676](scihant/CTPanoramaView) - Displays spherical or cylindrical panoramas or 360-photos with touch or motion based control options. :large_orange_diamond:
* [Twitter Image Pipline ★1368](twitter/ios-twitter-image-pipeline) - streamlined framework for fetching and storing images in an application.
* [TinyCrayon ★90](TinyCrayon/TinyCrayon-iOS-SDK) - A smart and easy-to-use image masking and cutout SDK for mobile apps. :large_orange_diamond:
* [FlexibleImage ★494](kawoou/FlexibleImage) - A simple way to play with image! :large_orange_diamond:
* [TLPhotoPicker ★825](tilltue/TLPhotoPicker) - Multiple phassets picker for iOS lib. like a facebook. :large_orange_diamond:

#### Media Processing
* [SwiftOCR ★2449](garnele007/SwiftOCR) - Fast and simple OCR library written in Swift :large_orange_diamond:
* [QR Code Scanner](http://www.appcoda.com/qr-code-ios-programming-tutorial/) - QR Code implementation.
* [QRCode ★384](aschuch/QRCode) - A QRCode generator written in Swift. :large_orange_diamond:
* [EFQRCode ★1535](EyreFree/EFQRCode) - A better way to operate two-dimensional code in Swift. :large_orange_diamond:

#### PDF
* [Reader ★3782](vfr/Reader) - PDF Reader Core for iOS.
* [UIView 2 PDF ★24 ⏳1Y](RobertAPhillips/UIView_2_PDF) - PDF generator using UIViews or UIViews with an associated XIB
* [FolioReaderKit ★1328](FolioReader/FolioReaderKit) - A Swift ePub reader and parser framework for iOS. :large_orange_diamond:
* [PDFGenerator ★217](sgr-ksmt/PDFGenerator) - A simple Generator of PDF in Swift. Generate PDF from view(s) or image(s). :large_orange_diamond:
* [SimplePDF ★79](nRewik/SimplePDF) - Create a simple PDF effortlessly. :large_orange_diamond:
* [SwiftPDFGenerator ★11 ⏳1Y](kayoslab/SwiftPDFGenerator) - PDF generator using UIViews; Swift Version of 'UIView 2 PDF'. :large_orange_diamond:
* [PSPDFKit](https://pspdfkit.com/) - Render PDF, add/edit annotations, fill forms, add/edit pages, view/create digital signatures.
* [TPPDF ★134](Techprimate/TPPDF) - Generate PDF using commands and automatic layout. :large_orange_diamond:

#### Streaming
* [lf.swift ★642](shogo4405/lf.swift) - Camera and Microphone streaming library via RTMP, HLS for iOS, macOS. :large_orange_diamond:
* [StreamingKit ★1532](tumtumtum/StreamingKit) - A fast and extensible gapless AudioPlayer/AudioStreamer for OSX and iOS.
* [Jukebox ★355](teodorpatras/Jukebox) - Player for streaming local and remote audio files. Written in Swift. :large_orange_diamond:
* [LFLiveKit ★2306](LaiFengiOS/LFLiveKit) - H264 and AAC Hard coding，support GPUImage Beauty， rtmp transmission，weak network lost frame，Dynamic switching rate
* [Airstream ★311](qasim/Airstream) - A framework for streaming audio between Apple devices using AirPlay.
* [OTAcceleratorCore ★16](opentok/accelerator-core-ios) - A painless way to integrate audio/video(screen sharing) to any iOS applications via Tokbox.

#### Video
* [VIMVideoPlayer ★256](vimeo/VIMVideoPlayer) - A simple wrapper around the AVPlayer and AVPlayerLayer classes.
* [MobilePlayer ★2085](mobileplayer/mobileplayer-ios) - A powerful and completely customizable media player for iOS.
* [XCDYouTubeKit ★2080](0xced/XCDYouTubeKit) - YouTube video player for iOS, tvOS and OS X
* [AVAnimator](http://www.modejong.com/AVAnimator/) - An open source iOS native library that makes it easy to implement non-trivial video/audio enabled apps.
* [Periscope VideoViewController ★461](gontovnik/Periscope-VideoViewController) - Video view controller with Periscope fast rewind control :large_orange_diamond:
* [SSVideoPlayer ★176](immrss/SSVideoPlayer) - A video player that support both local and network resource.
* [MHVideoPhotoGallery ★1938](mariohahn/MHVideoPhotoGallery) - A Photo and Video Gallery
* [PlayerView ★82](davidlondono/PlayerView) - Player View is a delegated view using AVPlayer of Swift :large_orange_diamond:
* [SRGMediaPlayer-iOS ★60](SRGSSR/SRGMediaPlayer-iOS) - The SRG Media Player library for iOS provides a simple way to add a universal audio / video player to any iOS application.
* [AVPlayerViewController-Subtitles ★56](mhergon/AVPlayerViewController-Subtitles) - AVPlayerViewController-Subtitles is a library to display subtitles on iOS. It's built as a Swift extension and it's very easy to integrate. :large_orange_diamond:[e]
* [MPMoviePlayerController-Subtitles ★166](mhergon/MPMoviePlayerController-Subtitles) - MPMoviePlayerController-Subtitles is a library to display subtitles on iOS. It's built as a Swift extension and it's very easy to integrate. :large_orange_diamond:[e]
* [ZFPlayer ★3005](renzifeng/ZFPlayer) - Based on AVPlayer, support for the horizontal screen, vertical screen (full screen playback can also lock the screen direction), the upper and lower slide to adjust the volume, the screen brightness, or so slide to adjust the playback progress.
* [Player ★767](piemonte/Player) - ▶️ video player in Swift, simple way to play and stream media in your iOS or tvOS app :large_orange_diamond:
* [BMPlayer ★558](BrikerMan/BMPlayer) - video player in swift3 and swift2 for iOS, based on AVPlayer, support the horizontal, vertical screen. support adjust volume, brigtness and seek by slide. :large_orange_diamond:
* [VideoPager ★27](entotsu/VideoPager) - Paging Video UI, and some control components is available. :large_orange_diamond:
* [ios-360-videos ★152](NYTimes/ios-360-videos) - NYT360Video plays 360-degree video streamed from an AVPlayer.
* [swift-360-videos ★41](team-pie/DDDKit) - Pure swift (no SceneKit) 3D library with focus on video and 360.
* [ABMediaView ★17](andrewboryk/ABMediaView) - UIImageView subclass for drop-in image, video, GIF, and audio display, with functionality for fullscreen and minimization to the bottom-right corner.

## Messaging

Also see [push notifications](#push-notifications)

* [LayerKit ★136](layerhq/releases-ios) - iOS SDK for Layer, the easiest way to add in-app messaging (text, photos, videos, data) to any mobile or web application.
* [Twilio](https://www.twilio.com/) - Power modern communications. Build the next generation of voice and SMS applications.
* [Plivo](https://www.plivo.com/) - SMS API, Voice API, & Global Carrier Provider.
* [XMPPFramework ★5106](robbiehanson/XMPPFramework) - An XMPP Framework in Objective-C for Mac and iOS.
* [Chatto ★2735](badoo/Chatto) - A lightweight framework to build chat applications, made in Swift :large_orange_diamond:
* [JSQMessagesViewController ★10432](jessesquires/JSQMessagesViewController) - An elegant messages UI library for iOS.
* [Smooch](https://smooch.io) - Simple, lightweight SDKs and interfaces that enable customer messaging inside your apps and websites.
* [SlackTextViewController ★7705](slackhq/SlackTextViewController) - A drop-in UIViewController subclass with a growing text input view and other useful messaging features.
* [MessageKit ★662](MessageKit/MessageKit-iOS) - Eventually, a Swift re-write of JSQMessagesViewController :large_orange_diamond:
* [NoChat ★430](little2s/NoChat) - A lightweight chat UI framework for iOS. :large_orange_diamond:
* [NMessenger ★1866](eBay/NMessenger) - A fast, lightweight messenger component built on AsyncDisplaykit and written in Swift :large_orange_diamond:
* [Atlas ★3588](layerhq/Atlas-iOS) - A library of native iOS messaging user interface components for Layer.
* [Messenger ★2656](relatedcode/Messenger) - This is a native iOS Messenger app, making realtime chat conversations and audio calls with full offline support.
* [OTTextChatAccelerator ★10](opentok/accelerator-textchat-ios) - OpenTok Text Chat Accelerator Pack enables text messages between mobile or browser-based devices.

## Networking
* [AFNetworking ★29238](AFNetworking/AFNetworking) - A delightful iOS and OS X networking framework.
* [RestKit ★10052](RestKit/RestKit) - RestKit is an Objective-C framework for iOS that aims to make interacting with RESTful web services simple, fast and fun.
* [FSNetworking ★401 ⏳1Y](foursquare/FSNetworking) - Foursquare iOS networking library.
* [ASIHTTPRequest ★5783](pokeb/asi-http-request) - Easy to use CFNetwork wrapper for HTTP requests, Objective-C, Mac OS X and iPhone.
* [Overcoat ★1129](Overcoat/Overcoat) - Small but powerful library that makes creating REST clients simple and fun.
* [ROADFramework ★51 ⏳1Y](epam/road-ios-framework) - Attributed-oriented approach for interacting with web services. The framework has built-in json and xml serialization for requests and responses and can be easily extensible.
* [Alamofire ★23662](Alamofire/Alamofire) - Alamofire is an HTTP networking library written in Swift, from the creator of AFNetworking. :large_orange_diamond:
* [Transporter ★423 ⏳1Y](nghialv/Transporter) - A tiny library makes uploading and downloading easier. :large_orange_diamond:
* [CDZPinger ★42 ⏳3Y](cdzombak/CDZPinger) - Easy-to-use ICMP Ping.
* [NSRails ★529](dingbat/nsrails) - iOS/Mac OS framework for Rails.
* [NKMultipeer ★13 ⏳1Y](nathankot/NKMultipeer) - A testable abstraction over multipeer connectivity. :large_orange_diamond:
* [CocoaAsyncSocket ★8668](robbiehanson/CocoaAsyncSocket) - Asynchronous socket networking library for Mac and iOS.
* [Siesta](https://bustoutsolutions.github.io/siesta/) - Elegant abstraction for RESTful resources that untangles stateful messes. An alternative to callback- and delegate-based networking. :large_orange_diamond:
* [Reachability.swift ★3774](ashleymills/Reachability.swift) - Replacement for Apple's Reachability re-written in Swift with closures :large_orange_diamond:
* [NetworkEye ★929](coderyi/NetworkEye) - a iOS network debug library, It can monitor HTTP requests within the App and displays information related to the request.
* [Netfox ★1929](kasketis/netfox) - A lightweight, one line setup, iOS / OSX network debugging library! :large_orange_diamond:
* [OctopusKit ★1 ⏳1Y](icoco/OctopusKit) - A simplicity but graceful solution for invoke RESTful web service APIs.
* [Moya ★5877](Moya/Moya) - Network abstraction layer written in Swift. :large_orange_diamond:
* [TWRDownloadManager ★314](chasseurmic/TWRDownloadManager) - A modern download manager based on NSURLSession to deal with asynchronous downloading, management and persistence of multiple files.
* [HappyDns ★286](qiniu/happy-dns-objc) - A Dns library, support custom dns server, dnspod httpdns. Only support A record.
* [Bridge ★92](BridgeNetworking/Bridge) - A simple extensible typed networking library. Intercept and process/alter requests and responses easily. :large_orange_diamond:
* [TRON ★347](MLSDev/TRON) - Lightweight network abstraction layer, written on top of Alamofire :large_orange_diamond:
* [EVCloudKitDao ★483](evermeer/EVCloudKitDao) - Simplified access to Apple's CloudKit :large_orange_diamond:
* [EVURLCache ★241](evermeer/EVURLCache) - a NSURLCache subclass for handling all web requests that use NSURLRequest :large_orange_diamond:
* [ResponseDetective ★1471](netguru/ResponseDetective) - Sherlock Holmes of the networking layer. :large_orange_diamond:
* [Pitaya ★845](johnlui/Pitaya) - A Swift HTTP / HTTPS networking library just incidentally execute on machines :large_orange_diamond:
* [Just ★968](JustHTTP/Just) - Swift HTTP for Humans :large_orange_diamond:
* [agent ★613](hallas/agent) - Minimalistic Swift HTTP request agent for iOS and OS X :large_orange_diamond:
* [Reach ★405](Isuru-Nanayakkara/Reach) - A simple class to check for internet connection availability in Swift. :large_orange_diamond:
* [SwiftHTTP ★1668](daltoniam/SwiftHTTP) - Thin wrapper around NSURLSession in swift. Simplifies HTTP requests. :large_orange_diamond:
* [Netdiag ★53](qiniu/iOS-netdiag) - A network diagnosis library. Support Ping/TcpPing/Rtmp/TraceRoute/DNS/external IP/external DNS.
* [AFNetworkingHelper ★17 ⏳2Y](betacraft/AFNetworkingHelper) - A custom wrapper over AFNetworking library that we use inside RC extensively
* [NetKit ★4](azizuysal/NetKit) - A Concise HTTP Framework in Swift. :large_orange_diamond:
* [RealReachability ★2278](dustturtle/RealReachability) - We need to observe the REAL reachability of network. That's what RealReachability do.
* [MonkeyKing ★1728](nixzhu/MonkeyKing) - MonkeyKing helps you post messages to Chinese Social Networks. :large_orange_diamond:
* [NetworkKit ★27](imex94/NetworkKit) - Lightweight Networking and Parsing framework made for iOS, Mac, WatchOS and tvOS. :large_orange_diamond:
* [APIKit ★1187](ishkawa/APIKit) - A networking library for building type safe web API client in Swift. :large_orange_diamond:
* [ws ☁️](https://github.com/freshOS/ws) - Elegant JSON WebService in Swift.:large_orange_diamond:
* [SPTDataLoader ★571](spotify/SPTDataLoader) - The HTTP library used by the Spotify iOS client.
* [SWNetworking ★22](skywite/SWNetworking) - Powerful high-level iOS, OS X and tvOS networking library.
* [Networking ★1007](3lvis/Networking) - Simple HTTP Networking in Swift a NSURLSession wrapper with image caching support :large_orange_diamond:
* [SOAPEngine ★405](priore/SOAPEngine) - This generic SOAP client allows you to access web services using a your iOS app, Mac OS X app and AppleTV app.
* [Swish ★352](thoughtbot/Swish) - Nothing but Net(working) :large_orange_diamond:
* [Malibu ★249](hyperoslo/Malibu) - :surfer: Malibu is a networking library built on promises :large_orange_diamond:
* [YTKNetwork ★4353](yuantiku/YTKNetwork) - YTKNetwork is a high level request util based on AFNetworking.
* [UnboxedAlamofire ★47](serejahh/UnboxedAlamofire) - Alamofire + Unbox: the easiest way to download and decode JSON into swift objects. :large_orange_diamond:
* [MMLanScan ★158](mavris/MMLanScan) - An iOS LAN Network Scanner library
* [Domainer ★5](FelixLinBH/Domainer) - Manage multi-domain url auto mapping ip address table
* [Restofire ★138](Restofire/Restofire) - Restofire is a protocol oriented network abstraction layer in swift that is built on top of Alamofire to use services in a declartive way :large_orange_diamond:
* [AFNetworking+RetryPolicy ★124](kubatruhlar/AFNetworking-RetryPolicy) - An objective-c category that adds the ability to set the retry logic for requests made with AFNetworking.
* [SwiftyZeroMQ ★20](azawawi/SwiftyZeroMQ) - ZeroMQ Swift Bindings for iOS, macOS, tvOS and watchOS. :large_orange_diamond: ⌚
* [Nikka ★11](JustaLab/Nikka) - A super simple Networking wrapper that supports many JSON libraries, Futures and Rx :large_orange_diamond: ⌚
* [XMNetworking ★672](kangzubin/XMNetworking) - A lightweight but powerful network library with simplified and expressive syntax based on AFNetworking.
* [Merhaba ★27](abdullahselek/Merhaba) - Bonjour networking for discovery and connection between iOS, macOS and tvOS devices.
* [DBNetworkStack ★15](dbsystel/DBNetworkStack) - Resource-oritented networking which is typesafe, extendable, composeable and makes testing a lot easier. :large_orange_diamond:
* [EFInternetIndicator ★88](ezefranca/EFInternetIndicator) - A little swift Internet error status indicator using ReachabilitySwift. :large_orange_diamond:
* [AFNetworking-Synchronous ★125](paulmelnikow/AFNetworking-Synchronous) - Synchronous requests for AFNetworking 1.x, 2.x, and 3.x.
* [QwikHttp ★1](logansease/QwikHttp) - a robust, yet lightweight and simple to use HTTP networking library designed for RESTful APIs. 🔶
* [NetClient ★27](intelygenz/NetClient-iOS) - Versatile HTTP networking library written in Swift 3. :large_orange_diamond:

#### Email

* [Mail Core 2 ★1521](MailCore/mailcore2) - MailCore 2 provide a simple and asynchronous API to work with e-mail protocols IMAP, POP and SMTP.
* [Postal ★415](snipsco/Postal) - A swift framework providing simple access to common email providers. :large_orange_diamond:

#### Representations

 * [apollo-ios ★503](apollographql/apollo-ios) - A GraphQL client for iOS, written in Swift :large_orange_diamond:
 * [JSONRPCKit ★65](bricklife/JSONRPCKit) - A JSON-RPC 2.0 library purely written in Swift :large_orange_diamond:
 * [protobuf-swift ★721](alexeyxo/protobuf-swift) - Google ProtocolBuffers for Apple Swift http://protobuf.io/#swift :large_orange_diamond:

## Notifications

#### Push Notifications
* [Orbiter ★696](mattt/Orbiter) - Push Notification Registration for iOS.
* [PEM](https://github.com/fastlane/fastlane/tree/master/pem) - Automatically generate and renew your push notification profiles.
* [Knuff ★3710](KnuffApp/Knuff) - The debug application for Apple Push Notification Service (APNS).
* [FBNotifications ★440](facebook/FBNotifications) - Facebook Analytics In-App Notifications Framework.
* [NWPusher ★2910](noodlewerk/NWPusher) - OS X and iOS application and framework to play with the Apple Push Notification service (APNs)
* [SimulatorRemoteNotifications ★1163](acoomans/SimulatorRemoteNotifications) - Library to send mock remote notifications to the iOS simulator

##### Push Notification Providers

Most of these are paid services, some have free tiers.

* [Urban Airship](https://www.urbanairship.com/products/mobile-app-engagement )
* [Growth Push](https://growthpush.com) - Popular in Japan.
* [Appboy](https://www.appboy.com)
* [Batch](https://batch.com)
* [Boxcar](https://boxcar.io)
* [Carnival](http://www.carnival.io)
* [Catapush](http://www.catapush.com/)
* [Netmera](http://www.netmera.com)
* [OneSignal](https://onesignal.com) - Free.
* [PushBots](https://pushbots.com/)
* [Pushwoosh](https://www.pushwoosh.com)
* [Pushkin ★136](Nordeus/pushkin) - Free and open-source.
* [Pusher](https://pusher.com/push-notifications) - Free and unlimited.

#### Local Notifications
* [DLLocalNotifications ★40](d7laungani/DLLocalNotifications) -  Easily create Local Notifications in swift - Wrapper of UserNotifications Framework. :large_orange_diamond:

## Parsing

#### CSV
* [CSwiftV ★115](Daniel1of1/CSwiftV) - A csv parser written in swift conforming to rfc4180 :large_orange_diamond:
* [SwiftCSV ★266](naoty/SwiftCSV) - CSV parser for Swift :large_orange_diamond:

#### JSON
* [JSON-Framework ★3787](stig/json-framework) -  This framework implements a strict JSON parser and generator in Objective-C.
* [Mantle ★10566](Mantle/Mantle) - Model framework for Cocoa and Cocoa Touch.
* [Groot ★461](gonzalezreal/Groot) - Convert JSON dictionaries and arrays to and from Core Data managed objects.
* [PropertyMapper ★1118](krzysztofzablocki/PropertyMapper) - Data mapping and validation with minimal amount of code.
* [JSONModel ★6140](JSONModel/JSONModel) - Magical Data Modeling Framework for JSON. Create rapidly powerful, atomic and smart data model classes.
* [SwiftyJSON ★14542](SwiftyJSON/SwiftyJSON) - The better way to deal with JSON data in Swift. :large_orange_diamond:
* [FastEasyMapping ★499](Yalantis/FastEasyMapping) - Serialize & deserialize JSON fast.
* [OCMapper ★347](aryaxt/OCMapper) - Objective-C & Swift library to easily map NSDictionary to model objects. :large_orange_diamond:
* [ObjectMapper ★5673](Hearst-DD/ObjectMapper) - A framework written in Swift that makes it easy for you to convert your Model objects (Classes and Structs) to and from JSON. :large_orange_diamond:
* [JASON ★981](delba/JASON) - JSON parsing with outstanding performances and convenient operators. :large_orange_diamond:
* [Gloss ★1466](hkellaway/Gloss) - A shiny JSON parsing library in Swift. :large_orange_diamond:
* [Cereal ★367](Weebly/Cereal) - Swift object serialization :large_orange_diamond:
* [SwiftyJSONAccelerator ★490](insanoid/SwiftyJSONAccelerator) - Generate Swift model files from JSON using either SwiftyJSON or ObjectMapper. Supports NSCoding and provides method for JSON string representation of the model. :large_orange_diamond:
* [JSONCodable ★595](matthewcheok/JSONCodable) - Hassle-free JSON encoding and decoding in Swift :large_orange_diamond:
* [Coolie ★515](nixzhu/Coolie) - Coolie helps you to create models (& their constructors) from JSON file. :large_orange_diamond:
* [Tailor ★231](zenangst/Tailor) - A super fast & convenient object mapper tailored for your needs. :large_orange_diamond:
* [alexander ★34](hodinkee/alexander) - An extremely simple JSON helper written in Swift. :large_orange_diamond:
* [Freddy ★1085](bignerdranch/Freddy) - A reusable framework for parsing JSON in Swift. :large_orange_diamond:
* [mapper ★922](lyft/mapper) - A JSON deserialization library for Swift :large_orange_diamond:
* [AlamofireJsonToObjects ★142](evermeer/AlamofireJsonToObjects) - An Alamofire extension which converts JSON response data into swift objects using EVReflection :large_orange_diamond:
* [Jay ★123](DanToml/Jay) - Pure-Swift JSON parser & formatter. Linux & OS X ready. :large_orange_diamond:
* [YYModel ★2787](ibireme/YYModel) - High performance model framework for iOS/OSX.
* [Alembic ★93](ra1028/Alembic) - Functional JSON parsing, mapping to objects, and serialize to JSON :large_orange_diamond:
* [Wrap ★492](JohnSundell/Wrap) - The easy to use Swift JSON encoder :large_orange_diamond:
* [Arrow 🏹 ★236](freshOS/Arrow) - Elegant JSON Parsing in Swift. :large_orange_diamond:
* [Decodable ★1051](Anviking/Decodable) - Swift 2/3 JSON parsing done (more) right :large_orange_diamond:
* [Genome ★781](LoganWright/Genome) - A simple, type safe, failure driven mapping library for serializing JSON to models in Swift 3.0 (Supports Linux) :large_orange_diamond:
* [Tyro ★48](typelift/Tyro) - Functional JSON parsing and encoding :large_orange_diamond:
* [Unbox ★1556](JohnSundell/Unbox) - The easy to use Swift JSON decoder :large_orange_diamond:
* [JSONJoy-Swift ★342](daltoniam/JSONJoy-Swift) - Convert JSON to Swift objects. :large_orange_diamond:
* [LazyObject ★8](iwasrobbed/LazyObject) - Lazily deserialize JSON into strongly typed Swift objects :large_orange_diamond:
* [JSONExport ★2593](Ahmed-Ali/JSONExport) - JSONExport is a desktop application for Mac OS X which enables you to export JSON objects as model classes with their associated constructors, utility methods, setters and getters in your favorite language. :large_orange_diamond:
* [Elevate ★600](Nike-Inc/Elevate) - Elevate is a JSON parsing framework that leverages Swift to make parsing simple, reliable and composable. :large_orange_diamond:
* [MJExtension ★6936](CoderMJLee/MJExtension) - A fast, convenient and nonintrusive conversion between JSON and model. Your model class don't need to extend another base class. You don't need to modify any model file.
* [AlamofireObjectMapper ★1787](tristanhimmelman/AlamofireObjectMapper) - An Alamofire extension which converts JSON response data into swift objects using ObjectMapper :large_orange_diamond:
* [GuardedSwiftyJSON ★4](wiggzz/GuardedSwiftyJSON) - An add-on to SwiftyJSON to make it easier to create failable initalizers for data models. :large_orange_diamond:
* [JAYSON ★225](muukii/JAYSON) - Strict and Scalable JSON library. :large_orange_diamond:
* [HandyJSON ★985](alibaba/handyjson) - A handy swift JSON-object serialization/deserialization library for swift 2.x/3.x. :large_orange_diamond:
* [Marshal ★472](utahiosmac/Marshal) - Marshaling the typeless wild west of [String: Any] (Protocol based).
* [Motis ★245](mobilejazz/Motis) - Easy JSON to NSObject mapping using Cocoa's key value coding (KVC).
* [NSTEasyJSON ★5](bernikowich/NSTEasyJSON) - The easiest way to deal with JSON data in Objective-C (similar to SwiftyJSON).
* [Serpent ★264](nodes-ios/Serpent) - A protocol to serialize Swift structs and classes for encoding and decoding. :large_orange_diamond:
* [MagicMapper ★24](adrianitech/magic-mapper-swift) - :star2: Super light and easy automatic JSON to model mapper. :large_orange_diamond:

#### XML & HTML
* [AEXML ★650](tadija/AEXML) - Simple and lightweight XML parser written in Swift. :large_orange_diamond:
* [Ji ★694](honghaoz/Ji) - XML/HTML parser for Swift. :large_orange_diamond:
* [Ono ★2127](mattt/Ono) - A sensible way to deal with XML & HTML for iOS & OS X
* [AlamofireXmlToObjects ★58](evermeer/AlamofireXmlToObjects) - Fetch a XML feed and parse it into objects :large_orange_diamond:
* [Fuzi ★539](cezheng/Fuzi) - A fast & lightweight XML & HTML parser in Swift with XPath & CSS support :large_orange_diamond:
* [Kanna ★1238](tid-kijyun/Kanna)  - Kanna(鉋) is an XML/HTML parser for MacOSX/iOS. :large_orange_diamond:
* [SwiftyXMLParser ★112](yahoojapan/SwiftyXMLParser) - Simple XML Parser implemented in Swift :large_orange_diamond:
* [HTMLKit ★66](iabudiab/HTMLKit) - An Objective-C framework for your everyday HTML needs.
* [SWXMLHash ★772](drmohundro/SWXMLHash) - Simple XML parsing in Swift :large_orange_diamond:
* [SwiftyXML ★16](chenyunguiMilook/SwiftyXML) - The most swifty way to deal with XML data in swift 3 :large_orange_diamond:

#### Other Parsing
* [WKZombie ★801](mkoehnke/WKZombie) - WKZombie is a Swift framework for iOS/OSX to navigate within websites and collect data without the need of User Interface or API, also known as Headless browser. It can be used to run automated tests or manipulate websites using Javascript. :large_orange_diamond:
* [URLPreview ★180](itsmeichigo/URLPreview) - An NSURL extension for showing preview info of webpages :large_orange_diamond:
* [FeedKit ★103](nmdias/FeedKit) - An RSS and Atom feed parser written in Swift :large_orange_diamond:
* [Erik ★221](phimage/Erik) - Erik is an headless browser based on WebKit. An headless browser allow to run functional tests, to access and manipulate webpages using javascript. :large_orange_diamond:
* [URLEmbeddedView ★388](marty-suzuki/URLEmbeddedView) - Automatically caches the object that is confirmed the Open Graph Protocol, and displays it as URL embedded card. :large_orange_diamond:
* [SwiftyConfiguration ★106](ykyouhei/SwiftyConfiguration) - Modern Swift API for Plist. :large_orange_diamond:
* [JSONFeed ★17](totocaster/JSONFeed) - Swift parser for JSON Feed, a format similar to RSS and Atom but in JSON. :large_orange_diamond:

## Passbook
* [passbook ★214](frozon/passbook) - Passbook gem let's you create pkpass for passbook iOS 6+.
* [Dubai ★316](nomad/dubai) - Generate and Preview Passbook Passes.
* [Passkit](https://passkit.com) - Design, Create and validate Passbook Passes.

## Payments
* [Caishen ★634](prolificinteractive/Caishen) - A Payment Card UI & Validator for iOS. :large_orange_diamond:
* [Stripe](https://stripe.com) - Payment integration on your app with PAY. Suitable for people with low knowledge on Backend.
* [Braintree](https://www.braintreepayments.com) - Free payment processing on your first $50k. Requires Backend.
* [Venmo ★130](venmo/venmo-ios-sdk) Make and accept payments in your iOS app via Venmo.
* [Moltin](https://www.moltin.com/ios-ecommerce-sdk/) - Add eCommerce to your app with a simple SDK, so you can create a store and sell physical products, no backend required.
* [PatronKit ★350 ⏳1Y](MosheBerman/PatronKit) - A framework to add patronage to your apps. :large_orange_diamond:
* [SwiftyStoreKit ★1982](bizz84/SwiftyStoreKit) - Lightweight In App Purchases Swift framework for iOS 8.0+ and OSX 9.0+ :large_orange_diamond:
* [InAppFramework ★35](sandorgyulai/InAppFramework) - In App Purchase Manager framework for iOS :large_orange_diamond:
* [SwiftInAppPurchase ★15 ⏳1Y](rpzzzzzz/SwiftInAppPurchase) - Simply code In App Purchases with this Swift Framework :large_orange_diamond:
* [monza ★83](gabrielgarza/monza) - Ruby Gem for Rails - Easy iTunes In-App Purchase Receipt validation, including auto-renewable subscriptions
* [EasyIAPs ★5](aaalveee/EasyIAPs) - An easy way to manage In App Purchases
* [PayPal ★822](paypal/PayPal-iOS-SDK) - Accept payments in your iOS app via PayPal.
* [card.io-iOS-SDK ★1746](card-io/card.io-iOS-SDK) - card.io provides fast, easy credit card scanning in mobile apps
* [SwiftLuhn ★92](MaxKramer/SwiftLuhn) - Debit/Credit card validation port of the Luhn Algorithm in Swift :large_orange_diamond:
* [ObjectiveLuhn ★116](MaxKramer/ObjectiveLuhn) - Luhn Credit Card Validation Algorithm
* [RMStore ★1947](robotmedia/RMStore) - A lightweight iOS library for In-App Purchases
* [MFCard ★247](mobilefirstinc/MFCard) - Easily integrate Credit Card payments in iOS App / Customisable Card UI
* [TPInAppReceipt ★17](tikhop/TPInAppReceipt) - Reading and Validating In App Store Receipt :large_orange_diamond:

## Permissions
* [PermissionScope ★4148](nickoneill/PermissionScope) - Intelligent iOS permissions UI and unified API (Supports Location, Notifications, Camera, Contacts, Calendar, Photos, Microphone, BT, Activity Monitoring, HealthKit and CloudKit). :large_orange_diamond:
* [Proposer ★732](nixzhu/Proposer) - Make permission request easier (Supports Camera, Photos, Microphone, Contacts, Location). :large_orange_diamond:
* [ICanHas ★77 ⏳1Y](wircho/ICanHas) - Simplifies iOS user permission requests (Supports location, push notifications, camera, contacts, calendar, photos). :large_orange_diamond:
* [VWWPermissionKit ★130 ⏳1Y](zakkhoyt/VWWPermissionKit) - A visual permission manager for iOS.
* [ISHPermissionKit ★559](iosphere/ISHPermissionKit) - A unified way for iOS apps to request user permissions.
* [JLPermissions ★396](jlaws/JLPermissions) - An iOS pre-permissions utility that lets developers ask users on their own dialog for calendar, contacts, location, photos, reminders, twitter, push notifications and more, before making the system-based permission request.
* [ClusterPrePermissions ★1171](clusterinc/ClusterPrePermissions) - Reusable pre-permissions utility that lets developers ask users for access in their own dialog, before making the system-based request.
* [Permission ★2129](delba/Permission) - A unified API to ask for permissions on iOS :large_orange_diamond:
* [STLocationRequest ★528](SvenTiigi/STLocationRequest) - A simple and elegant 3D-Flyover location request screen written Swift. :large_orange_diamond:
* [PAPermissions ★647](pascalbros/PAPermissions) - A unified API to ask for permissions on iOS :large_orange_diamond:
* [AREK ★740](ennioma/arek) - AREK is a clean and easy to use wrapper over any kind of iOS permission. :large_orange_diamond:
* [RequestPermission ★1391](IvanVorobei/RequestPermission) - simple permission request with beautiful UI :large_orange_diamond:

## Products
* [Import.io](https://www.import.io/) - Instantly Turn Web Pages into Data.
* [Tapglue](https://www.tapglue.com/) - Build social products and a activity feed with a few lines of code.
* [OpenShop.io ★251](openshopio/openshop.io-ios) - mobile e-commerce solution connected to Facebook Ads and Google.

## Reactive Programming
* [RxSwift ★9394](ReactiveX/RxSwift) - Reactive Programming in Swift :large_orange_diamond:
* [RxOptional ★7 ⏳1Y](thanegill/RxOptional) - RxSwift extentions for Swift optionals and "Occupiable" types :large_orange_diamond:
* [ReactiveTask ★116](Carthage/ReactiveTask) - Flexible, stream-based abstraction for launching processes :large_orange_diamond:
* [ReactiveCocoa ★17305](ReactiveCocoa/ReactiveCocoa) - Streams of values over time.
* [RxMediaPicker ★81](RxSwiftCommunity/RxMediaPicker) - A reactive wrapper built around UIImagePickerController. :large_orange_diamond:
* [ReactiveCoreData ★275 ⏳1Y](apparentsoft/ReactiveCoreData) - ReactiveCoreData (RCD) is an attempt to bring Core Data into the ReactiveCocoa (RAC) world.
* [ReSwift ★3692](ReSwift/ReSwift) - Unidirectional Data Flow in Swift - Inspired by Redux :large_orange_diamond:
* [ReactiveKit ★851](ReactiveKit/ReactiveKit) - ReactiveKit is a collection of Swift frameworks for reactive and functional reactive programming. :large_orange_diamond:
* [RxPermission ★144](sunshinejr/RxPermission) - RxSwift bindings for Permissions API in iOS. :large_orange_diamond:
* [RxAlamofire ★657](RxSwiftCommunity/RxAlamofire) - RxSwift wrapper around the elegant HTTP networking in Swift Alamofire :large_orange_diamond:
* [RxRealm ★402](RxSwiftCommunity/RxRealm) - Rx wrapper for Realm's collection types :large_orange_diamond:
* [RxMultipeer ★44](RxSwiftCommunity/RxMultipeer) - A testable RxSwift wrapper around MultipeerConnectivity :large_orange_diamond:
* [RxBluetoothKit ★544](Polidea/RxBluetoothKit) - iOS & OSX Bluetooth library for RxSwift :large_orange_diamond:
* [RxGesture ★354](RxSwiftCommunity/RxGesture) - RxSwift reactive wrapper for view gestures :large_orange_diamond:
* [NSObject-Rx ★190](RxSwiftCommunity/NSObject-Rx) - Handy RxSwift extensions on NSObject, including rx_disposeBag. :large_orange_diamond:
* [RxCoreData ★65](RxSwiftCommunity/RxCoreData) - RxSwift extensions for Core Data :large_orange_diamond:
* [Render ★1469](alexdrone/Render) - Swift and UIKit a la React. :large_orange_diamond:
* [RxAutomaton ★552](inamiy/RxAutomaton) - RxSwift + State Machine, inspired by Redux and Elm. :large_orange_diamond:
* [ReactiveArray ★54 ⏳1Y](Wolox/ReactiveArray) - An array class implemented in Swift that can be observed using ReactiveCocoa's Signals. :large_orange_diamond:
* [Interstellar ★936](JensRavens/Interstellar) - Simple and lightweight Functional Reactive Coding in Swift for the rest of us. :large_orange_diamond:
* [ReduxSwift ★30](lsunsi/ReduxSwift) - Predictable state container for Swift apps too. :large_orange_diamond:
* [Aftermath ★49](hyperoslo/Aftermath) - Stateless message-driven micro-framework in Swift. :large_orange_diamond:
* [RxKeyboard ★457](RxSwiftCommunity/RxKeyboard) - Reactive Keyboard in iOS. :large_orange_diamond:
* [JASONETTE-iOS ★4570](Jasonette/JASONETTE-iOS) - Native App over HTTP. Create your own native iOS app with nothing but JSON.
* [Katana ★1542](BendingSpoons/katana-swift) - Swift apps a la React and Redux. :large_orange_diamond:
* [TemplateKit ★102](mcudich/TemplateKit) - React-inspired framework for building component-based user interfaces in Swift. :large_orange_diamond:
* [ReactiveSwift ★1255](ReactiveCocoa/ReactiveSwift) - Streams of values over time by ReactiveCocoa group
* [Listenable ★2](msaps/Listenable) - Swift object that provides an observable platform. :large_orange_diamond:
* [Reactor ★115](ReactorSwift/Reactor) - :arrows_counterclockwise: Unidirectional Data Flow using idiomatic Swift—inspired by Elm and Redux . :large_orange_diamond:
* [Snail ★45](UrbanCompass/Snail) - An observables framework for Swift :large_orange_diamond:
* [RxWebSocket ★29](fjcaetano/RxWebSocket) - Reactive extension over Starscream for websockets :large_orange_diamond:
* [ACKReactiveExtensions ★6](AckeeCZ/ACKReactiveExtensions) - Useful extensions for ReactiveCocoa :large_orange_diamond:
* [ReactiveLocation ★10](AckeeCZ/ReactiveLocation) - CoreLocation made reactive :large_orange_diamond:
* [Hanson ★73](blendle/Hanson) - Lightweight observations and bindings in Swift, with support for KVO and NotificationCenter. :large_orange_diamond:

## Reflection
* [Reflection ★294](Zewo/Reflection) - Reflection provides an API for advanced reflection at runtime including dynamic construction of types. :large_orange_diamond:
* [Reflect ★289](CharlinFeng/Reflect) - Reflection, Dict2Model, Model2Dict, Archive :large_orange_diamond:
* [EVReflection ★670](evermeer/EVReflection) - Reflection based JSON encoding and decoding. Including support for NSDictionary, NSCoding, Printable, Hashable and Equatable :large_orange_diamond:
* [JSONNeverDie ★462](johnlui/JSONNeverDie) - Auto reflection tool from JSON to Model, user friendly JSON encoder / decoder, aims to never die :large_orange_diamond:
* [SwiftKVC ★94](bradhilton/SwiftKVC) - Key-Value Coding (KVC) for native Swift classes and structs :large_orange_diamond:

## Regex
* [Regex ★389](sharplet/Regex) - A Swift µframework providing an NSRegularExpression-backed Regex type :large_orange_diamond:
* [SwiftRegex ★116](kasei/SwiftRegex) - Perl-like Regex =~ operator for Swift :large_orange_diamond:
* [PySwiftyRegex ★199](cezheng/PySwiftyRegex) - Easily deal with Regex in Swift in a Pythonic way :large_orange_diamond:
* [Regex ★176](crossroadlabs/Regex) - Regular expressions for swift :large_orange_diamond:
* [Regex ★57](brynbellomy/Regex) - Regex class for Swift. Wraps NSRegularExpression. :large_orange_diamond:

## SDK

#### Official

* [Spotify ★727](spotify/ios-sdk) Spotify iOS SDK.
* [Facebook ★5748](facebook/facebook-ios-sdk) Facebook iOS SDK.
* [Facebook Swift ★1100](facebook/facebook-sdk-swift) Integrate your iOS apps in Swift with Facebook Platform.
* [Google Analytics](https://developers.google.com/analytics/devguides/collection/ios/v3/) Google Analytics SDK for iOS
* [Paypal iOS SDK ★822](paypal/PayPal-iOS-SDK) The PayPal Mobile SDKs enable native apps to easily accept PayPal and credit card payments.
* [Pocket ★193](Pocket/Pocket-ObjC-SDK) SDK for saving stuff to Pocket.
* [Tumblr ★361](tumblr/TMTumblrSDK) Library for easily integrating Tumblr data into your iOS or OS X application.
* [Evernote ★203](evernote/evernote-cloud-sdk-ios) Evernote SDK for iOS.
* [Box ★43](box/box-ios-sdk) iOS + OS X SDK for the Box API.
* [OneDrive ★53](OneDrive/onedrive-sdk-ios) Live SDK for iOS.
* [Stripe ★801](stripe/stripe-ios) Stripe bindings for iOS and OS X.
* [Venmo](#payments)
* [AWS ★815](aws/aws-sdk-ios) Amazon Web Services Mobile SDK for iOS.
* [Zendesk ★58](zendesk/zendesk_sdk_ios) Zendesk Mobile SDK for iOS.
* [Adobe Creative SDK](https://creativesdk.adobe.com/) Adobe creative tools and Creative Cloud SDK.
* [Dropbox](https://www.dropbox.com/developers) SDKs for Drop-ins and Dropbox Core API.
* [Fabric by Twitter](https://docs.fabric.io/apple/fabric/overview.html) Fabric Twitter Kit for iOS.
* [Liquid Analytics ★24](lqd-io/liquid-sdk-ios) Identify behaviours through Analytics and react with real-time Personalization.
* [ResearchKit ★4841](ResearchKit/ResearchKit) ResearchKit is an open source software framework that makes it easy to create apps for medical research or for other research projects.
* [PacketZoom](https://packetzoom.com) PacketZoom SDK for iOS.
* [Primer](https://www.goprimer.com) - Easy SDK for creating personalized landing screens, signup, and login flows on a visual editor with built in a/b/n testing and analytics.
* [Azure ★50](Azure/azure-storage-ios) - Client library for accessing Azure Storage on an iOS device
* [1Password ★2300](AgileBits/onepassword-app-extension) - 1Password Extension for iOS Apps
* [CareKit ★1332](carekit-apple/CareKit) - CareKit is an open source software framework for creating apps that help people better understand and manage their health. By Apple :large_orange_diamond:
* [Shopify ★138](Shopify/mobile-buy-sdk-ios) - Shopify’s Mobile Buy SDK makes it simple to sell physical products inside your mobile app.
* [Pinterest ★90](pinterest/ios-pdk) - Pinterest iOS SDK
* [playkit-ios ★15](kaltura/playkit-ios) - PlayKit: Kaltura Player SDK for iOS.

#### Unofficial

* [STTwitter ★1011](nst/STTwitter) A stable, mature and comprehensive Objective-C library for Twitter REST API 1.1
* [FHSTwitterEngine ★219](natesymer/FHSTwitterEngine) Twitter API for Cocoa developers.
* [Giphy ★46](heyalexchoi/Giphy-iOS) Giphy API client for iOS in Objective-C.
* [UberKit ★96 ⏳1Y](sachinkesiraju/UberKit) - A simple, easy-to-use Objective-C wrapper for the Uber API.
* [InstagramKit ★872](shyambhat/InstagramKit) - Instagram iOS SDK.
* [DribbbleSDK ★72 ⏳1Y](agilie/dribbble-ios-sdk) - Dribbble iOS SDK.
* [objectiveflickr ★730 ⏳1Y](lukhnos/objectiveflickr) - ObjectiveFlickr, a Flickr API framework for Objective-C.
* [Easy Social ★129 ⏳1Y](pjebs/EasySocial) - Twitter & Facebook Integration.
* [das-quadrat ★163](Constantine-Fry/das-quadrat) - A Swift wrapper for Foursquare API. iOS and OSX. :large_orange_diamond:
* [SocialLib ★10 ⏳1Y](darkcl/SocialLib) - SocialLib handles sharing message to multiple social media.
* [PokemonKit ★62](ContinuousLearning/PokemonKit) - Pokeapi wrapper, written in Swift :large_orange_diamond:
* [TJDropbox ★46](timonus/TJDropbox) - A Dropbox v2 client library written in Objective-C
* [Lyft ★58](genadyo/Lyft) - Some pink mustache company forgot to build that SDK. :large_orange_diamond:
* [Github.swift ★142](onmyway133/github.swift) - :octocat: Unofficial GitHub API client in Swift :large_orange_diamond:
* [CloudRail SI ★190](CloudRail/cloudrail-si-ios-sdk) - Abstraction layer / unified API for multiple API providers. Interfaces eg for Cloud Storage (Dropbox, Google, ...), Social Networks (Facebook, Twitter, ...) and more.
* [Medium SDK - Swift ★6](96-problems/medium-sdk-swift) - Unofficial Medium API SDK in Swift with sample project :large_orange_diamond:
* [Swifter ★1810](mattdonnelly/Swifter) - :bird: A Twitter framework for iOS & OS X written in Swift :large_orange_diamond:
* [SlackKit ★365](SlackKit/SlackKit) - a Slack client library for iOS and OS X written in Swift :large_orange_diamond:
* [RandomUserSwift ★77](dingwilson/RandomUserSwift) - Swift 3 Framework to Generate Random Users - An Unofficial SDK for randomuser.me :large_orange_diamond:
* [PPEventRegistryAPI ★8](pantuspavel/PPEventRegistryAPI) - Swift 3 Framework for Event Registry API (eventregistry.org). :large_orange_diamond:
* [UnsplashKit ★134](carambalabs/UnsplashKit) - Swift client for Unsplash. :large_orange_diamond:
* [Swiftly Salesforce ★49](mike4aday/SwiftlySalesforce) - An easy-to-use framework for building iOS apps that integrate with Salesforce, using Swift and promises. :large_orange_diamond:
* [Spartan ★12](Daltron/Spartan) - An Elegant Spotify Web API Library Written in Swift for iOS and macOS. :large_orange_diamond:
* [BigBoard ★30](Daltron/BigBoard) - An Elegant Financial Markets Library Written in Swift that makes requests to Yahoo Finance API's under the hood. :large_orange_diamond:

## Security
* [cocoapods-keys ★850](orta/cocoapods-keys) - A key value store for storing environment and application keys.
* [simple-touch ★91](simple-machines/simple-touch) - Very simple swift wrapper for Biometric Authentication Services (Touch ID) on iOS.
* [SwiftPasscodeLock ★508](yankodimitrov/SwiftPasscodeLock) - An iOS passcode lock with TouchID authentication written in Swift. :large_orange_diamond:
* [Smile-Lock ★428](recruit-lifestyle/Smile-Lock) - A library for make a beautiful Passcode Lock View.
* [zxcvbn-ios ★133](dropbox/zxcvbn-ios) - A realistic password strength estimator.
* [TPObfuscatedString ★11](Techprimate/TPObfuscatedString) - Simple String obfuscation using core Swift. :large_orange_diamond:
* [LTHPasscodeViewController ★584](rolandleth/LTHPasscodeViewController) - An iOS passcode lockscreen replica (from Settings), with TouchID and simple (variable length) / complex support.
* [iOS-App-Security-Class ★29](karek314/iOS-App-Security-Class) - Simple class to check if iOS app has been cracked, being debugged or enriched with custom dylib and as well detect jailbroken environment.
* [BiometricAuth ★14](vasilenkoigor/BiometricAuth) - Simple framework for biometric authentication (via TouchID) in your application 🔶
* [SAPinViewController ★14](siavashalipour/SAPinViewController) - Simple and easy to use default iOS PIN screen. This simple library allows you to draw a fully customisable PIN screen same as the iOS default PIN view. My inspiration to create this library was form THPinViewController, however SAPinViewController is completely implemented in Swift. Also the main purpose of creating this library was to have simple, easy to use and fully customisable PIN screen. 🔶

#### Encryption
* [AESCrypt-ObjC ★656](Gurpartap/AESCrypt-ObjC) - A simple and opinionated AES encrypt / decrypt Objective-C class that just works.
* [IDZSwiftCommonCrypto ★312](iosdevzone/IDZSwiftCommonCrypto) - A wrapper for Apple's Common Crypto library written in Swift. :large_orange_diamond:
* [Arcane ★63](onmyway133/Arcane) - 🔱 Lightweight wrapper around CommonCrypto in Swift :large_orange_diamond:
* [SwiftMD5 ★7](mpurland/SwiftMD5) - A pure Swift implementation of MD5 :large_orange_diamond:
* [SwiftHash ★20](onmyway133/SwiftHash) - 🍕 Hash in Swift :large_orange_diamond:
* [SweetHMAC ★29](jancassio/SweetHMAC) - A tiny and easy to use Swift class to encrypt strings using HMAC algorithms. :large_orange_diamond:
* [SwCrypt ★397](soyersoyer/SwCrypt) - RSA public/private key generation, RSA, AES encryption/decryption, RSA sign/verify in Swift with CommonCrypto in iOS and OS X :large_orange_diamond:
* [SwiftSSL ★182 ⏳1Y](SwiftP2P/SwiftSSL) - An Elegant crypto toolkit in Swift. :large_orange_diamond:
* [SwiftyRSA ★305](TakeScoop/SwiftyRSA) - RSA public/private key encryption in Swift :large_orange_diamond:
* [EnigmaKit ★97 ⏳1Y](mikaoj/EnigmaKit) - Enigma encryption in Swift :large_orange_diamond:
* [Themis ★379](cossacklabs/themis) - High-level crypto library, providing basic asymmetric encryption, secure messaging with forward secrecy and secure data storage, supports iOS/OS X, Android and different server side platforms.
* [Obfuscator-iOS ★323](pjebs/Obfuscator-iOS) - Secure your app by obfuscating all the hard-coded security-sensitive strings.
* [swift-sodium ★148](jedisct1/swift-sodium) - Safe and easy to use crypto for iOS :large_orange_diamond:
* [CryptoSwift ★3770](krzyzanowskim/CryptoSwift) - Crypto related functions and helpers for Swift implemented in Swift programming language :large_orange_diamond:
* [SCrypto ★13](sgl0v/SCrypto) - Elegant Swift interface to access the CommonCrypto routines :large_orange_diamond:
* [SipHash ★174](lorentey/SipHash) - Simple and secure hashing in Swift with the SipHash algorithm. :large_orange_diamond:

#### Keychain
* [UICKeyChainStore ★2347](kishikawakatsumi/UICKeyChainStore) - UICKeyChainStore is a simple wrapper for Keychain on iOS.
* [Valet ★2430](square/Valet) - Securely store data in the iOS or OS X Keychain without knowing a thing about how the Keychain works.
* [Locksmith ★2202](matthewpalmer/Locksmith) - A powerful, protocol-oriented library for working with the keychain in Swift. :large_orange_diamond:
* [KeychainAccess ★2879](kishikawakatsumi/KeychainAccess) - Simple Swift wrapper for Keychain that works on iOS and OS X :large_orange_diamond:
* [Keychain ★41](hyperoslo/Keychain) - Because you should care... about the security... of your shit. :large_orange_diamond:
* [Lockbox ★831](granoff/Lockbox) - Objective-C utility class for storing data securely in the key chain.
* [SAMKeychain ★4365](soffes/SAMKeychain) - Simple Objective-C wrapper for the keychain that works on Mac and iOS.
* [SwiftKeychainWrapper ★508](jrendel/SwiftKeychainWrapper) - A simple wrapper for the iOS Keychain to allow you to use it in a similar fashion to User Defaults. Written in Swift. :large_orange_diamond:

## Server
* [Perfect ★11528](PerfectlySoft/Perfect) - Server-side Swift. The Perfect library, application server, connectors and example apps. :large_orange_diamond:
* [Swifter ★2011](httpswift/swifter) - Tiny http server engine written in Swift programming language. :large_orange_diamond:
* [CocoaHTTPServer ★4132](robbiehanson/CocoaHTTPServer) - A small, lightweight, embeddable HTTP server for Mac OS X or iOS applications.
* [Curassow ★386](kylef/Curassow) - Swift HTTP server using the pre-fork worker model. :large_orange_diamond:
* [Zewo ★1668](Zewo/Zewo) - Venice based HTTP server for Swift 2.2 on Linux :large_orange_diamond:
* [Vapor ★9683](vapor/vapor) - Elegant web framework for Swift that works on iOS, OS X, and Ubuntu. :large_orange_diamond:
* [swiftra ★274](takebayashi/swiftra) - Sinatra-like DSL for developing web apps in Swift :large_orange_diamond:
* [blackfire ★951](elliottminns/blackfire) - A fast HTTP web server based on Node.js and Express written in Swift :large_orange_diamond:
* [swift-http ★463](huytd/swift-http) - HTTP Implementation for Swift on Linux and Mac OS X :large_orange_diamond:
* [Trevi ★47 ⏳1Y](Yoseob/Trevi) - libuv base Swift web HTTP server framework :large_orange_diamond:
* [Express ★853](crossroadlabs/Express) - Swift Express is a simple, yet unopinionated web application server written in Swift :large_orange_diamond:
* [Taylor ★915](izqui/Taylor) - A lightweight library for writing HTTP web servers with Swift :large_orange_diamond:
* [Frank ★367](kylef/Frank) - Frank is a DSL for quickly writing web applications in Swift :large_orange_diamond:
* [Kitura ★5711](IBM-Swift/Kitura) - A Swift Web Framework and HTTP Server :large_orange_diamond:
* [Swifton ★2053](necolt/Swifton) - A Ruby on Rails inspired Web Framework for Swift that runs on Linux and OS X :large_orange_diamond:
* [Dynamo ★65](johnno1962/Dynamo) - High Performance (nearly)100% Swift Web server supporting dynamic content. :large_orange_diamond:
* [Redis ★333](vapor/redis) - Pure-Swift Redis client implemented from the original protocol spec. OS X + Linux compatible. :large_orange_diamond:
* [NetworkObjects ★269 ⏳1Y](colemancda/NetworkObjects) - Swift backend / server framework (Pure Swift, Supports Linux) :large_orange_diamond:
* [Noze.io](http://noze.io) - Evented I/O streams a.k.a. Node.js for Swift. :large_orange_diamond:
* [Edge ★281](SwiftOnEdge/Edge) - A Swift Multiplatform Web and Networking Framework. :large_orange_diamond:
* [SwiftGD ★151](twostraws/swiftgd) - A simple Swift wrapper for libgd. :large_orange_diamond:
* [Jobs ★107](BrettRToomey/Jobs) - A job system for Swift backends. :large_orange_diamond:
* [ApacheExpress ★163](ApacheExpress/ApacheExpress) - Write Apache Modules in Swift! :large_orange_diamond:

## Text
* [Twitter Text Obj ★1599](twitter/twitter-text) - An Objective-C implementation of Twitter's text processing library.
* [Nimbus ★6278](jverkoey/nimbus) - Nimbus is a toolkit for experienced iOS software designers.
* [NSStringEmojize ★583](diy/nsstringemojize) - A category on NSString to convert Emoji Cheat Sheet codes to their equivalent Unicode characters.
* [MMMarkdown ★1030](mdiep/MMMarkdown) - An Objective-C static library for converting Markdown to HTML.
* [DTCoreText ★4933](Cocoanetics/DTCoreText) - Methods to allow using HTML code with CoreText.
* [DTRichTextEditor ★281](Cocoanetics/DTRichTextEditor) - A rich-text editor for iOS.
* [NBEmojiSearchView ★75 ⏳1Y](neerajbaid/NBEmojiSearchView) - A searchable emoji dropdown view.
* [Pluralize.swift ★126](joshualat/Pluralize.swift) - Great Swift String Pluralize Extension :large_orange_diamond:
* [RichEditorView ★846](cjwirth/RichEditorView) - RichEditorView is a simple, modular, drop-in UIView subclass for Rich Text Editing. :large_orange_diamond:
* [Money ★741](danthorpe/Money) - Swift value types for working with money & currency :large_orange_diamond:
* [PhoneNumberKit ★1774](marmelroy/PhoneNumberKit) - A Swift framework for parsing, formatting and validating international phone numbers. Inspired by Google's libphonenumber. :large_orange_diamond:
* [YYText ★6272](ibireme/YYText) - Powerful text framework for iOS to display and edit rich text.
* [Format ★1124](marmelroy/Format) - A Swift Formatter Kit. :large_orange_diamond:
* [Tribute ★53](zats/Tribute) - Programmatic creation of NSAttributedString doesn't have to be a pain :large_orange_diamond:
* [EmojiKit ★81](dasmer/EmojiKit) - Effortless emoji-querying in Swift :large_orange_diamond:
* [Roman ★29 ⏳1Y](nvzqz/Roman) - Seamless Roman numeral conversion in Swift. :large_orange_diamond:
* [ZSSRichTextEditor ★2390](nnhubbard/ZSSRichTextEditor) - A beautiful rich text WYSIWYG editor for iOS with a syntax highlighted source view.
* [pangu.Objective-C ★104](Cee/pangu.objective-c) - Paranoid text spacing in Objective-C.
* [SwiftString ★1374](amayne/SwiftString) - A comprehensive, lightweight string extension for Swift :large_orange_diamond:
* [Marklight ★326](macteo/Marklight) - Markdown syntax highlighter for iOS :large_orange_diamond:
* [MarkdownTextView ★506 ⏳1Y](indragiek/MarkdownTextView) - Rich Markdown editing control for iOS :large_orange_diamond:
* [TextAttributes ★1870](delba/TextAttributes) - An easier way to compose attributed strings. :large_orange_diamond:[e]
* [Reductio ★336](fdzsergio/Reductio) - Automatic summarizer text in Swift :large_orange_diamond:
* [SmarkDown ★52 ⏳1Y](SwiftStudies/SmarkDown) - A Pure Swift implementation of the markdown mark-up language :large_orange_diamond:
* [SwiftyMarkdown ★698](SimonFairbairn/SwiftyMarkdown) - Converts Markdown files and strings into NSAttributedString :large_orange_diamond:
* [SZMentions ★6](szweier/SZMentions) - Library to help handle mentions
* [SZMentionsSwift ★23](szweier/SZMentionsSwift) - Library to help handle mentions.
* [Heimdall ★267](henrinormak/Heimdall) - Heimdall is a wrapper around the Security framework for simple encryption/decryption operations. :large_orange_diamond:
* [NoOptionalInterpolation ★36](T-Pham/NoOptionalInterpolation) - Get rid of "Optional(...)" and "nil" in string interpolation. Easy pluralization.🔶[e]
* [Smile ★220](onmyway133/Smile) 😄 Emoji in Swift
* [ISO8601 ★11](onmyway133/iso8601) Super lightweight ISO8601 Date Formatter in Swift 🔶[e]
* [Translucid ★500](Ekhoo/Translucid) - Lightweight library to set an Image as text background. Written in swift. :large_orange_diamond:
* [FormatterKit ★3979](mattt/FormatterKit) - `stringWithFormat:` for the sophisticated hacker set
* [BonMot ★1682](Raizlabs/BonMot) - Beautiful, easy attributed strings in Swift :large_orange_diamond:
* [SwiftValidators ★110](gkaimakas/SwiftValidators) - String validation for iOS developed in Swift. Inspired by [validator.js](https://www.npmjs.com/package/validator).
* [StringStylizer ★29](kazuhiro4949/StringStylizer) - Type strict builder class for NSAttributedString. :large_orange_diamond:
* [SwiftyAttributes ★785](eddiekaiger/SwiftyAttributes) - Swift extensions that make it a breeze to work with attributed strings. :large_orange_diamond:
* [MarkdownKit ★68](ivanbruel/MarkdownKit) - A simple and customizable Markdown Parser for Swift. :large_orange_diamond:
* [CocoaMarkdown ★905](indragiek/CocoaMarkdown) - Markdown parsing and rendering for iOS and OS X. :large_orange_diamond:
* [Apodimark ★426](loiclec/Apodimark) - Fast, flexible markdown parser written in Swift. :large_orange_diamond:
* [Notepad ★251](ruddfawcett/Notepad) - A fully themeable markdown editor with live syntax highlighting. :large_orange_diamond:
* [KKStringValidator ★14](krizhanovskii/KKStringValidator) - Fast and simple string validation for IOS. With UITextField extension. :large_orange_diamond:
* [ISO8859 ★10](Cosmo/ISO8859) - 📄⚙ Convert ISO8859 1-16 Encoded Text to String in Swift. Supports iOS, tvOS, watchOS and macOS. :large_orange_diamond:
* [Emojica](https://github.com/xoudini/emojica) - Replace standard emoji in strings with a custom emoji set, such as [Twemoji](https://github.com/twitter/twemoji) or [EmojiOne ★3417](emojione/emojione). :large_orange_diamond:
* [SwiftRichString ★949](malcommac/SwiftRichString) - Elegant & Painless Attributed Strings Management Library in Swift. :large_orange_diamond:
* [libPhoneNumber-iOS ★1625](iziz/libPhoneNumber-iOS) - iOS port from libphonenumber (Google's phone number handling library).
* [AttributedTextView ★179](evermeer/AttributedTextView) - Easiest way to create an attributed UITextView with support for multiple links (including hashtags and mentions).
* [StyleDecorator ★9](dimpiax/StyleDecorator) - Design string simply by linking attributes to needed parts
* [Mustard ★652](mathewsanders/Mustard) - Mustard is a Swift library for tokenizing strings when splitting by whitespace doesn't cut it. :large_orange_diamond:
* [Input Mask ★55](RedMadRobot/input-mask-ios) - Pattern-based user input formatter, parser and validator for iOS. :large_orange_diamond:
* [Attributed ★475](Nirma/Attributed) - Modern Swift µframework for attributed strings. :large_orange_diamond:
* [Atributika ★100](psharanda/Atributika) - Easily build NSAttributedString by detecting and styling HTML-like tags, hashtags, mentions, RegExp or NSDataDetector patterns. :large_orange_diamond:
* [Guitar ★525](ArtSabintsev/Guitar) - A Cross-Platform String Library Written in Swift. :large_orange_diamond:
* [RealTimeCurrencyFormatter ★11](kaiomedau/realtime-currency-formatter-objc) - An ObjC international currency formatting utility.
* [Down ★388](iwasrobbed/Down) - Blazing fast Markdown rendering in Swift, built upon cmark. 🔶
* [Marky Mark ★30](m2mobi/Marky-Mark) - Highly customizable Markdown parsing and native rendering in Swift. 🔶

## Testing

#### TDD / BDD
* [Kiwi ★3590](kiwi-bdd/Kiwi) - A behavior-driven development library for iOS development.
* [Specta ★1976](specta/specta) - A light-weight TDD / BDD framework for Objective-C & Cocoa.
* [Quick ★6457](Quick/Quick) - A behavior-driven development framework for Swift and Objective-C.
* [XcodeCoverage ★673](jonreid/XcodeCoverage) - Code coverage for Xcode projects.
* [OHHTTPStubs ★3166](AliSoftware/OHHTTPStubs) - Stub your network requests easily! Test your apps with fake network data and custom response time, response code and headers!
* [Dixie ★202 ⏳1Y](Skyscanner/Dixie) - Dixie is an open source Objective-C testing framework for altering object behaviours.
* [gh-unit ★1915](gh-unit/gh-unit) - Test Framework for Objective-C.
* [Nimble ★2128](Quick/Nimble) - A Matcher Framework for Swift and Objective-C :large_orange_diamond:
* [Sleipnir ★839 ⏳1Y](railsware/Sleipnir) - BDD-style framework for Swift :large_orange_diamond:
* [SwiftCheck ★705](typelift/SwiftCheck) - QuickCheck for Swift :large_orange_diamond:

#### A/B Testing
* [Switchboard ★255](KeepSafe/Switchboard) - Switchboard - easy and super light weight A/B testing for your mobile iPhone or android app. This mobile A/B testing framework allows you with minimal servers to run large amounts of mobile users.
* [SkyLab ★678 ⏳2Y](mattt/SkyLab) - Multivariate & A/B Testing for iOS and Mac
* [MSActiveConfig ★80 ⏳3Y](mindsnacks/MSActiveConfig) - Remote configuration and A/B Testing framework for iOS
* [ABKit ★94 ⏳1Y](recruit-mp/ABKit) - AB testing framework for iOS :large_orange_diamond:

#### UI Testing
* [CrashMonkey ★173](mokemokechicken/CrashMonkey) - Monkey Test Tool For iOS.
* [appium](http://appium.io/) - Appium is an open source test automation framework for use with native and hybrid mobile apps.
* [robotframework-appiumlibrary ★128](serhatbolsu/robotframework-appiumlibrary) - AppiumLibrary is an appium testing library for RobotFramework.
* [Cucumber](https://cucumber.io/) - Behavior driver development for iOS.
* [Kif ★4865](kif-framework/KIF) - An iOS Functional Testing Framework.
* [Subliminal ★787 ⏳1Y](inkling/Subliminal) - An understated approach to iOS integration testing.
* [ios-driver](http://ios-driver.github.io/ios-driver/index.html) - Test any IOS native, hybrid, or mobile web application using Selenium / WebDriver.
* [Zucchini ★162 ⏳3Y](zucchini-src/zucchini) - A visual iOS testing framework that loves your apps.
* [Remote ★635](johnno1962/Remote) - Control your iPhone from inside Xcode for end-to-end testing.
* [LayoutTest-iOS ★465](linkedin/LayoutTest-iOS) - Write unit tests which test the layout of a view in multiple configurations.
* [EarlGrey ★3651](google/EarlGrey) - :tea: iOS UI Automation Test Framework.
* [UI Testing Cheat Sheet ★1026](joemasilotti/UI-Testing-Cheat-Sheet) - How do I test this with UI Testing? :large_orange_diamond:
* [Floater_ ★230 ⏳1Y](Buglife/Floater_) - Add a floating fingertip to your app demo :large_orange_diamond:
* [Bluepill ★2301](linkedin/bluepill) - Bluepill is a reliable iOS testing tool that runs UI tests using multiple simulators on a single machine

#### Other Testing
* [NaughtyKeyboard ★567 ⏳1Y](Palleas/NaughtyKeyboard) - The Big List of Naughty Strings is a list of strings which have a high probability of causing issues when used as user-input data. This is a keyboard to help you test your app from your iOS device.
* [PonyDebugger ★5382](square/PonyDebugger) - Remote network and data debugging for your native iOS app using Chrome Developer Tools
* [ios-snapshot-test-case ★2429](facebook/ios-snapshot-test-case) - Snapshot view unit tests for iOS.
* [Fakery ★671](vadymmarkov/Fakery) - Swift fake data generator. :large_orange_diamond:
* [DVR ★491](venmo/DVR) - Network testing for Swift :large_orange_diamond:
* [Cuckoo ★520](Brightify/Cuckoo) - First boilerplate-free mocking framework for Swift :large_orange_diamond:
* [Parallel iOS Tests ★0](plu/parallel_ios_tests) - Run iOS tests on multiple simulators in parallel at the same time :large_orange_diamond:
* [Vinyl ★198](Velhotes/Vinyl) - Network testing à la VCR in Swift :large_orange_diamond:
* [Mockit ★47](sabirvirtuoso/Mockit) - A simple mocking framework for Swift, inspired by the famous Mockito for Java :large_orange_diamond:
* [Cribble ★267](maxsokolov/Cribble) - Swifty tool for visual testing iPhone and iPad apps :large_orange_diamond:
* [second_curtain ★108 ⏳1Y](ashfurrow/second_curtain) - Upload failing iOS snapshot tests cases to S3
* [trainer ★81](KrauseFx/trainer) - Convert xcodebuild plist files to JUnit reports
* [Buildasaur ★701](buildasaurs/Buildasaur) - Automatic testing of your Pull Requests on GitHub and BitBucket using Xcode Server. Keep your team productive and safe. Get up and running in minutes. @buildasaur :large_orange_diamond:
* [Kakapo ★712](devlucky/Kakapo) - 🐤Dynamically Mock server behaviors and responses in Swift :large_orange_diamond:
* [AcceptanceMark ★49](bizz84/AcceptanceMark) Tool to auto-generate Xcode tests classes from Markdown tables
* [MetovaTestKit ★19](metova/MetovaTestKit) - A collection of testing utilities to turn crashing test suites into failing test suites. :large_orange_diamond:
* [MirrorDiffKit ★60](Kuniwak/MirrorDiffKit) - Pretty diff between any structs or classes :large_orange_diamond:

#### Font
* [FontBlaster ★817](ArtSabintsev/FontBlaster) - Programmatically load custom fonts into your iOS app. :large_orange_diamond:
* [GoogleMaterialIconFont ★130](kitasuke/GoogleMaterialIconFont) - Google Material Design Icons for Swift and ObjC project :large_orange_diamond:
* [ios-fontawesome ★1715](alexdrone/ios-fontawesome) - NSString+FontAwesome.
* [FontAwesome.swift ★802](thii/FontAwesome.swift) - Use FontAwesome in your Swift projects. :large_orange_diamond:
* [SwiftFontName ★88](morizotter/SwiftFontName) - OS font complements library. Localized font supported :large_orange_diamond:
* [SwiftIconFont ★611](0x73/SwiftIconFont) - Icons fonts for iOS (FontAwesome, Iconic, Ionicon, Octicon, Themify, MapIcon, MaterialIcon) :large_orange_diamond:
* [FontAwesomeKit ★2426](PrideChung/FontAwesomeKit) - Icon font library for iOS. Currently supports Font-Awesome, Foundation icons, Zocial, and ionicons.
* [Iconic ★1316](dzenbot/Iconic) - Auto-generated icon font library for iOS, watchOS and tvOS  :large_orange_diamond:
* [GoogleMaterialDesignIcons ★359](dekatotoro/GoogleMaterialDesignIcons) - Google Material Design Icons Font for iOS. :large_orange_diamond:
* [OcticonsKit ★32](keitaoouchi/OcticonsKit) - Use Octicons as UIImage / UIFont in your projects with Swifty manners. :large_orange_diamond:
* [IoniconsKit ★283](keitaoouchi/IoniconsKit) - Use Ionicons as UIImage / UIFont in your projects with Swifty manners. :large_orange_diamond:
* [FontAwesomeKit.Swift ★143](qiuncheng/FontAwesomeKit.Swift) - A better choice for iOS Developer to use FontAwesome Icon. :large_orange_diamond:
* [UIFontComplete ★784](Nirma/UIFontComplete) - Make working with UIFont faster and less error-prone. :large_orange_diamond:
* [Swicon ★33](UglyTroLL/Swicon) - Use 1600+ icons (and more!) from FontAwesome and Google Material Icons in your swift/iOS project in an easy and space-efficient way! :large_orange_diamond:
* [SwiftIcons ★260](ranesr/SwiftIcons) - A library for using different font icons: dripicons, emoji, font awesome, icofont, ionicons, linear icons, map icons, material icons, open iconic, state, weather. It supports UIImage, UIImageView, UILabel, UIButton, UISegmentedControl, UITabBarItem, UISlider, UIBarButtonItem, UIViewController, UITextfield, UIStepper. :large_orange_diamond:

## UI
* [FlatUIKit ★7554](Grouper/FlatUIKit) - A collection of awesome flat UI components for iOS.
* [BetweenKit ★260](ice3-software/between-kit) - A robust drag-and-drop framework for iOS.
* [MDCSwipeToChoose ★2398](modocache/MDCSwipeToChoose) - Swipe to "like" or "dislike" any view, just like Tinder.app. Build a flashcard app, a photo viewer, and more, in minutes, not hours!
* [BLKFlexibleHeightBar ★2854](bryankeller/BLKFlexibleHeightBar) - Create condensing header bars like those seen in the Facebook, Square Cash, and Safari iOS apps.
* [Motif ★771](erichoracek/Motif) - A lightweight and customizable JSON stylesheet framework for iOS.
* [Texture ★1099](TextureGroup/Texture) - Smooth asynchronous user interfaces for iOS apps.
* [GaugeKit ★875](skywinder/GaugeKit) - Customizable gauges. Easy reproduce Apple's style gauges. :large_orange_diamond:
* [MVMaterialView ★66 ⏳1Y](TheMrugraj/MVMaterialView) - Subclass of UIControls and UIButton to mimic Ripple effect of Material Design concept.
* [TisprCardStack ★606](tispr/tispr-card-stack) - Library that allows to have cards UI. :large_orange_diamond:
* [SAHistoryNavigationViewController ★1440](marty-suzuki/SAHistoryNavigationViewController) - SAHistoryNavigationViewController realizes iOS task manager like UI in UINavigationContoller,3D Touch Compatible. :large_orange_diamond:
* [SAInboxViewController ★265](marty-suzuki/SAInboxViewController) - UIViewController subclass inspired by "Inbox by google" animated transitioning. :large_orange_diamond:
* [iCarousel ★9361](nicklockwood/iCarousel) - A simple, highly customisable, data-driven 3D carousel for iOS and Mac OS.
* [Cocoa Controls](https://www.cocoacontrols.com/) - Open source UI components for iOS and OS X.
* [HoneycombView ★185 ⏳1Y](suzuki-0000/HoneycombView) - HoneycombView is the iOS UIView for displaying like Honyecomb layout written by swift. :large_orange_diamond:
* [tapkulibrary ★4011](devinross/tapkulibrary) - tap + haiku = tapku, a well crafted open source iOS framework.
* [HorizontalDial ★87](kciter/HorizontalDial) - A horizontal scroll dial like Instagram. :large_orange_diamond:
* [ComponentKit](http://componentkit.org/) - A React-Inspired View Framework for iOS, by Facebook.
* [PMTween ★336](poetmountain/PMTween) - An elegant and flexible tweening library for iOS.
* [WobbleView ★2151](inFullMobile/WobbleView) - WobbleView is an implementation of a recently popular wobble effect for any view in your app. It can be used to easily add dynamics to user interactions and transitions. :large_orange_diamond:
* [RKNotificationHub ★2629](cwRichardKim/RKNotificationHub) - Make any UIView a full fledged notification center.
* [EatFit ★561](Yalantis/EatFit) - Eat fit is a component for attractive data representation inspired by Google Fit :large_orange_diamond:
* [phone-number-picker ★102](hughbe/phone-number-picker) - A simple and easy to use view controller enabling you to enter a phone number with a country code similar to WhatsApp written in Swift :large_orange_diamond:
* [DLWBouncyView ★50 ⏳1Y](cute/DLWBouncyView) - BouncyView is an implementation of a recently popular bouncy effect for any view.
* [EXTView ★148 ⏳1Y](recruit-mtl/EXTView) - Extended UIView for Interface Builder by using IB_DESIGNABLE and IBInspectable.
* [SFFocusViewLayout ★1511](fdzsergio/SFFocusViewLayout) - UICollectionViewLayout with focused content.
* [CardAnimation ★928 ⏳1Y](seedante/CardAnimation) - Card flip animation by pan gesture. :large_orange_diamond:
* [BEMCheckBox ★1748](Boris-Em/BEMCheckBox#sample-app) - Tasteful Checkbox for iOS. (Check box)
* [HorizontalProgress ★147](AliThink/HorizontalProgress) - Simple horizontal progress bar with animation
* [JRSplitVC ★24 ⏳1Y](tommypeps/JRSplitVC) - UISplitViewController with adaptative layouts
* [MPParallaxView ★1456](DroidsOnRoids/MPParallaxView) - Apple TV Parallax effect in Swift. :large_orange_diamond:
* [Splitflap ★722](yannickl/Splitflap) - A simple split-flap display for your Swift applications :large_orange_diamond:
* [EZSwipeController ★653](goktugyil/EZSwipeController) - :point_up_2: UIPageViewController like Snapchat/Tinder/iOS Main Pages :large_orange_diamond:
* [SWRevealViewController ★4133](John-Lluch/SWRevealViewController) - A UIViewController subclass for presenting side view controllers inspired on the FaceBook and Wunderlist apps, done right.
* [Koloda ★3127](Yalantis/Koloda) - KolodaView is a class designed to simplify the implementation of Tinder like cards on iOS. :large_orange_diamond:
* [XLActionController ★1918](xmartlabs/XLActionController) - Fully customizable and extensible action sheet controller written in Swift. :large_orange_diamond:
* [StackPageView ★32 ⏳1Y](noppefoxwolf/StackPageView) - Vertical page view with UIViewControllers stacked on the top of each other :large_orange_diamond:
* [PageControl ★87](kasper-lahti/PageControl) - ● ○ ○ ○ A nice, animated UIPageControl alternative. :large_orange_diamond:
* [Curry ★27](devinross/curry) - Curry is a framework built to enhance and compliment Foundation and UIKit.
* [Pages ★339](hyperoslo/Pages) - :page_facing_up: UIPageViewController made simple :large_orange_diamond:
* [BothamUI ★332](Karumi/BothamUI) - Model View Presenter Framework written in Swift. :large_orange_diamond:
* [RainbowNavigation ★588](DanisFabric/RainbowNavigation) - An easy way to change backgroundColor of UINavigationBar when Push & Pop :large_orange_diamond:
* [ALTextInputBar ★156](AlexLittlejohn/ALTextInputBar) - An auto growing text input bar for messaging apps. :large_orange_diamond:
* [APCustomBlurView ★135 ⏳1Y](collinhundley/APCustomBlurView) - A subclass of UIVisualEffectView with customizable blur radius. :large_orange_diamond:
* [BAFluidView ★1242](antiguab/BAFluidView) - UIView that simulates a 2D view of a fluid in motion
* [WZDraggableSwitchHeaderView ★487](wongzigii/WZDraggableSwitchHeaderView) - :hammer: Showing status for switching between viewControllers
* [MICountryPicker ★59](mustafaibrahim989/MICountryPicker) - Swift country picker with search option. :large_orange_diamond:
* [SCNavigationControlCenter ★395 ⏳1Y](SergioChan/SCNavigationControlCenter) - This is an advanced navigation control center on iOS that can allow you to navigate to whichever view controller you want
* [SCTrelloNavigation ★768](SergioChan/SCTrelloNavigation) - :clipboard: An iOS native implementation of a Trello Animated Navagation.
* [FXBlurView ★4899](nicklockwood/FXBlurView) - UIView subclass that replicates the iOS 7 realtime background blur effect, but works on iOS 5 and above.
* [NGAParallaxMotion ★678 ⏳1Y](michaeljbishop/NGAParallaxMotion) - A tiny category on UIView that allows you to set one property: "parallaxIntensity" to achieve a parallax effect with UIMotionEffect
* [EPShapes ★356](ipraba/EPShapes) - Design shapes in Interface Builder. :large_orange_diamond:
* [CRParticleEffect ★351 ⏳1Y](Cleveroad/CRParticleEffect) - A CocoaPod that simplifies creation of the particle effects.
* [Spots ★1082](hyperoslo/Spots) - Spots is a view controller framework that makes your setup and future development blazingly fast. :large_orange_diamond:
* [APAddressBook ★1347](Alterplay/APAddressBook) - Easy access to iOS address book
* [AZExpandableIconListView ★173](Azuritul/AZExpandableIconListView) - An expandable/collapsible view component written in Swift. :large_orange_diamond:
* [greedo-layout-for-ios ★783](500px/greedo-layout-for-ios) - Full aspect ratio grid layout for iOS
* [FlourishUI ★193](thinkclay/FlourishUI) - A highly configurable and out-of-the-box-pretty UI library :large_orange_diamond:
* [GranadaLayout ★38 ⏳1Y](gskbyte/GranadaLayout) - Alternative layout system for iOS, inspired on the Android layout system, that includes linear and relative layouts, as well as an extensible JSON-based layout inflater.
* [Navigation Stack ★1799](Ramotion/navigation-stack) - Navigation Stack is a stack-modeled navigation controller. :large_orange_diamond:
* [UIView-draggable ★365](andreamazz/UIView-draggable) - UIView category that adds dragging capabilities.
* [PeekPop ★1817](marmelroy/PeekPop) - Backwards-compatible Peek and Pop.
* [MKGradientView ★61](maxkonovalov/MKGradientView) - Core Graphics based gradient view capable of producing Linear (Axial), Radial (Circular), Conical (Angular), Bilinear (Four Point) gradients, written in Swift. 🔶
* [EPSignature ★600](ipraba/EPSignature) - Signature component for iOS in Swift :large_orange_diamond:
* [CoreDragon ★706](nevyn/CoreDragon)  - [iOS] Stop using context menus. Drag and drop instead, even between apps!
* [AEConicalGradient ★29](tadija/AEConicalGradient) - Conical (angular) gradient layer written in Swift. :large_orange_diamond:
* [EVFaceTracker ★212](evermeer/EVFaceTracker) - Calculate the distance and angle of your device with regards to your face.
* [Fashion ★65](vadymmarkov/Fashion) - Fashion accessories and beauty tools to share and reuse UI styles in a Swifty way. :large_orange_diamond:
* [LeeGo ★882](wangshengjia/LeeGo) - Declarative, configurable & highly reusable UI development as making Lego bricks. :large_orange_diamond:
* [MEVHorizontalContacts ★279](manuelescrig/MEVHorizontalContacts) - An iOS UICollectionViewLayout subclass to show a list of contacts with configurable expandable menu items.
* [Ripple ★47](RamonGilabert/Ripple) - Remember there's no such thing as a small act of kindness. Every act creates a ripple with no logical end. :large_orange_diamond:
* [ScalePicker ★130](kronik/ScalePicker) - Generic scale and a handy float-value picker for any iOS app.
* [VisualEffectView ★390](efremidze/VisualEffectView) - UIVisualEffectView subclass with tint color. :large_orange_diamond:
* [NumPad ★41](efremidze/NumPad) - Number Pad (inspired by Square's design). :large_orange_diamond:
* [expanding-collection ★3486](Ramotion/expanding-collection) - ExpandingCollection is a card peek/pop controller :large_orange_diamond:
* [Cacao ★650](PureSwift/Cacao) - Pure Swift Cross-platform UIKit (Cocoa Touch) implementation (Supports Linux) :large_orange_diamond:
* [LFTimePicker ★27](awesome-labs/LFTimePicker) - Custom Time Picker ViewController with Selection of start and end times in Swift :large_orange_diamond:
* [StateView ★475](sahandnayebaziz/StateView) - Views that automatically update themselves. :large_orange_diamond:
* [JDFlipNumberView ★707](calimarkus/JDFlipNumberView) - Representing analog flip numbers like airport/trainstation displays.
* [JQSwiftIcon ★5](josejuanqm/JQSwiftIcon) - Icon Fonts on iOS using string interpolation written in Swift. :large_orange_diamond:
* [FlickToDismiss ★198](jakelawson1/FlickToDismiss) - A basic UIViewController class that presents a UIView which can be dismissed by flicking it off the screen. :large_orange_diamond:
* [ISTimeline ★845](instant-solutions/ISTimeline) - Simple timeline view written in Swift 2.2 :large_orange_diamond:
* [JFCardSelectionViewController ★366](atljeremy/JFCardSelectionViewController) - A fancy collection style view controller :large_orange_diamond:
* [DCKit ★75](agordeev/DCKit) - Set of iOS controls, which have useful IBInspectable properties. Written on Swift. :large_orange_diamond:
* [BackgroundVideoiOS ★477](Guzlan/BackgroundVideoiOS) - A swift and objective-C object that lets you add a background video to iOS views.
* [NightNight ★546](Draveness/NightNight) - Elegant way to integrate night mode to swift projects :large_orange_diamond:
* [SwiftTheme ★784](jiecao-fm/SwiftTheme) - Powerful theme/skin manager for iOS 7+ :large_orange_diamond:
* [PinpointKit ★895](Lickability/PinpointKit) - Let your testers and users send feedback with annotated screenshots and logs using a simple gesture. :large_orange_diamond:
* [FDStackView ★2236](forkingdog/FDStackView) - Use UIStackView directly in iOS6+
* [Popover ★1152](corin8823/Popover) - Popover is a balloon library like Facebook app. It is written in pure swift. :large_orange_diamond:
* [YangMingShan ★583](yahoo/YangMingShan) - YangMingShan is a collection of iOS UI components that we created while building Yahoo apps.
* [TOActionSheet ★149](TimOliver/TOActionSheet) - A custom-designed reimplementation of the UIActionSheet control for iOS
* [LFLoginController ★64](awesome-labs/LFLoginController) - Customizable login screen, written in Swift :large_orange_diamond:
* [nui ★3707](tombenner/nui) - Style iOS apps with a stylesheet, similar to CSS
* [RedBeard](http://www.redbeard.io/) - It's a complete framework that takes away much of the pain of getting a beautiful, powerful iOS App crafted.
* [Material ★7906](CosmicMind/Material) - Material is an animation and graphics framework that allows developers to easily create beautiful applications. :large_orange_diamond:
* [Blurable ★787](FlexMonkey/Blurable) - Apply a Gaussian Blur to any UIView with Swift Protocol Extensions :large_orange_diamond:
* [EZYGradientView ★270](shashankpali/EZYGradientView) - Create gradients and blur gradients without a single line of code :large_orange_diamond:
* [DistancePicker ★82](qmathe/DistancePicker) - Custom control to select a distance with a pan gesture, written in Swift. :large_orange_diamond:
* [OAStackView ★2126](nsomar/OAStackView) - OAStackView tries to port back the stackview to iOS 7+. OAStackView aims at replicating all the features in UIStackView.
* [StyleKit ★1101](146BC/StyleKit) - StyleKit is a microframework that enables you to style your applications using a simple JSON file. Behind the scenes, StyleKit uses UIAppearance and some selector magic to apply the styles. You can also customize the parser for greater flexibility. :large_orange_diamond:
* [planet ★44](kwallet/planet) - A country picker :large_orange_diamond:
* [PageController ★193](hirohisa/PageController) - Infinite paging controller, scrolling through contents and title bar scrolls with a delay. :large_orange_diamond:
* [StatusProvider ★753](mariohahn/StatusProvider) - Protocol to handle initial Loadings, Empty Views and Error Handling in a ViewController & views :large_orange_diamond:
* [ASBubbleDrag ★35](scamps88/ASBubbleDrag) - round icon drag control (made in swift) dock style :large_orange_diamond:
* [StackLayout ★70 ⏳1Y](bridger/StackLayout) - An alternative to UIStackView for common Auto Layout patterns.
* [NightView ★155](Boris-Em/NightView) - Dazzling Nights on iOS. :large_orange_diamond:
* [VENTokenField ★724](venmo/VENTokenField) - Easy-to-use token field that is used in the Venmo app.
* [SwiftVideoBackground ★65](dingwilson/SwiftVideoBackground) - Easy to Use UIView subclass for implementing a video background in Swift 3 :large_orange_diamond:
* [MRArticleViewController ★95](mrigdon/MRArticleViewController) - Easily create UIViewControllers for news articles similar to those in the News app. :large_orange_diamond:
* [iCheckbox ★27](mancunianetz/iCheckbox) - A checkbox like component for iOS apps. :large_orange_diamond:
* [Macaw ★2682](exyte/macaw) - Powerful and easy-to-use vector graphics library with SVG support written in Swift. :large_orange_diamond:
* [HubFramework ★1656](spotify/HubFramework) - Spotify’s component-driven UI framework for iOS.
* [ConfettiView ★205](OrRon/ConfettiView) - Confetti View lets you create a magnificent confetti view in your app :large_orange_diamond:
* [BouncyPageViewController ★558](BohdanOrlov/BouncyPageViewController) - Page view controller with bounce effect :large_orange_diamond:
* [LTHRadioButton ★179](rolandleth/LTHRadioButton) - A radio button with a pretty fill animation. :large_orange_diamond:
* [CRRulerControl ★88](Cleveroad/CRRulerControl) - Customizable component is aimed at turning a simple ruler into a handy and smart instrument.
* [Macaw-Examples ★105](exyte/Macaw-Examples) - Various usages of the Macaw library. :large_orange_diamond:
* [KVCardSelectionVC ★12](kunalverma25/KVCardSelectionVC) - Awesome looking Dial like card selection ViewController. :large_orange_diamond:
* [Reactions ★417](yannickl/Reactions) - Fully customizable Facebook reactions control :large_orange_diamond:
* [Newly ★161](dhirajjadhao/Newly) - Newly is a drop in solution to add Twitter/Facebook/Linkedin-style new updates/tweets/posts available button :large_orange_diamond:
* [CardStackController ★273](jobandtalent/CardStackController) - iOS custom controller used in Jobandtalent app to present new view controllers as cards :large_orange_diamond:
* [Material Components ★1207](material-components/material-components-ios) - Google developed UI components that help developers execute Material Design.
* [DMSwipeCards ★181](D-32/DMSwipeCards) - Tinder like card stack that supports lazy loading and generics :large_orange_diamond:
* [RKMultiUnitRuler ★14](farshidce/RKMultiUnitRuler) - Simple customizable ruler control that supports multiple units. 🔶
* [FAQView ★332](mukeshthawani/FAQView) - An easy to use FAQ view for iOS written in Swift. :large_orange_diamond:
* [CRPageViewController ★337](Cleveroad/CRPageViewController) - While a standard page view allows you to navigate between pages by using simple gestures, our component goes further.
* [OXPatternLock ★13](oxozle/OXPatternLock) - An iOS pattern lock like Android authentication written in Swift. :large_orange_diamond:
* [LMArticleViewController ★3](lucamozza/LMArticleViewController) - UIViewController subclass to beautifully present news articles and blog posts
* [FSPagerView ★1548](WenchaoD/FSPagerView) - FSPagerView is an elegant Screen Slide Library. It is extremely helpful for making Banner、Product Show、Welcome/Guide Pages、Screen/ViewController Sliders. :large_orange_diamond:
* [PanelKit ★2706](louisdh/panelkit) - A UI framework that enables panels on iOS. :large_orange_diamond:
* [ElongationPreview ★468](Ramotion/elongation-preview) - ElongationPreview is an elegant push-pop style view controller with 3D-Touch support and gestures. :large_orange_diamond:
* [Pageboy ★734](uias/Pageboy) - A simple, highly informative page view controller. :large_orange_diamond:
* [IGColorPicker ★51](iGenius-Srl/IGColorPicker) - 🎨 A customizable color picker for iOS in Swift 🔶
* [KPActionSheet ★4](khuong291/KPActionSheet) - 🔶 A replacement of default action sheet, but has very simple usage. 🔶
* [SegmentedProgressBar ★117](D-32/SegmentedProgressBar) - Snapchat / Instagram Stories style animated indicator :large_orange_diamond:
* [CHIPageControl ★1356](ChiliLabs/CHIPageControl) - A set of cool animated page controls to replace boring UIPageControl. :large_orange_diamond:
* [Magnetic ★488](efremidze/Magnetic) - SpriteKit Floating Bubble Picker (inspired by Apple Music). 🔶
* [AmazingBubbles ★34](GlebRadchenko/AmazingBubbles) - Apple Music like Bubble Picker using Dynamic Animation. 🔶
* [LoginKit ★328](IcaliaLabs/LoginKit) - LoginKit is a quick and easy way to add a Login/Signup UX to your iOS app.  🔶
* [Haptica ★163](efremidze/Haptica) - Easy Haptic Feedback Generator. :large_orange_diamond:
* [GDCheckbox ★0](SaeidBsn/GDCheckbox) - An easy to use custom checkbox/radio button component for iOS, with support of IBDesign Inspector. 🔶
* [HamsterUIKit ★3](ChromieIsDangerous/HamsterUIKit) - A simple and elegant UIKit(Chart) for iOS.  🔶
* [AZEmptyState ★8](Minitour/AZEmptyState) - A UIControl subclass that makes it easy to create empty states. 🔶

#### Activity Indicator

* [NVActivityIndicatorView ★5079](ninjaprox/NVActivityIndicatorView) - Collection of nice loading animations. :large_orange_diamond:
* [TKRubberIndicator ★975](TBXark/TKRubberIndicator) - Rubber Indicator in Swift :large_orange_diamond:
* [RPLoadingAnimation ★166](naoyashiga/RPLoadingAnimation) - Loading animations :cyclone: by using Swift CALayer :large_orange_diamond:
* [LiquidLoader ★909](yoavlt/LiquidLoader) - Spinner loader components with liquid animation :large_orange_diamond:
* [iOS-CircleProgressView ★360](CardinalNow/iOS-CircleProgressView) - This control will allow a user to use code instantiated or interface builder to create and render a circle progress view. :large_orange_diamond:
* [iOS Circle Progress Bar ★306](Eclair/CircleProgressBar) - iOS Circle Progress Bar
* [LinearProgressBar ★64](PhilippeBoisney/LinearProgressBar) - Linear Progress Bar (inspired by Google Material Design) for iOS written in Swift 2.0. :large_orange_diamond:
* [STLoadingGroup ★274](saitjr/STLoadingGroup) - loading views :large_orange_diamond:
* [ALThreeCircleSpinner ★30](AlexLittlejohn/ALThreeCircleSpinner) - A pulsing spinner view written in swift :large_orange_diamond:
* [MHRadialProgressView ★74 ⏳1Y](mehfuzh/MHRadialProgressView) - iOS 7 radial animated progress view.
* [Loader ★79](Ekhoo/Loader) - Amazing animated switch activity indicator written in swift :large_orange_diamond:
* [MBProgressHUD ★13275](jdg/MBProgressHUD) - Drop-in class for displays a translucent HUD with an indicator and/or labels while work is being done in a background thread.
* [SVProgressHUD ★9726](SVProgressHUD/SVProgressHUD) - A clean and lightweight progress HUD for your iOS app.
* [ProgressHUD ★892](relatedcode/ProgressHUD) - ProgressHUD is a lightweight and easy-to-use HUD.
* [M13ProgressSuite ★3448](Marxon13/M13ProgressSuite) - A suite containing many tools to display progress information on iOS.
* [JHProgressHUD ★76](harikrishnant1991/JHProgressHUD) - An easy and lightweight Swift library to show HUD in IOS applications. :large_orange_diamond:
* [PKHUD ★2228](pkluz/PKHUD) - A Swift based reimplementation of the Apple HUD (Volume, Ringer, Rotation,…) for iOS 8 and above. :large_orange_diamond:
* [EZLoadingActivity ★485](goktugyil/EZLoadingActivity) - Lightweight loading activity HUD.  :large_orange_diamond:
* [FFCircularProgressView ★992 ⏳1Y](elbryan/FFCircularProgressView) - FFCircularProgressView - An iOS 7-inspired blue circular progress view
* [MRProgress ★2551](mrackwitz/MRProgress) - Collection of iOS drop-in components to visualize progress
* [BigBrother ★446](marcelofabri/BigBrother) - Automatically sets the network activity indicator for any performed request. :large_orange_diamond:
* [AlamofireNetworkActivityIndicator ★367](Alamofire/AlamofireNetworkActivityIndicator) - Controls the visibility of the network activity indicator on iOS using Alamofire. :large_orange_diamond:
* [KDCircularProgress ★580](kaandedeoglu/KDCircularProgress) - A circular progress view with gradients written in Swift :large_orange_diamond:
* [DACircularProgress ★2123](danielamitay/DACircularProgress) - DACircularProgress is a UIView subclass with circular UIProgressView properties.
* [KYNavigationProgress ★179](ykyouhei/KYNavigationProgress) - Simple extension of UINavigationController to display progress on the UINavigationBar. :large_orange_diamond:[e]
* [GearRefreshControl ★520](andreamazz/GearRefreshControl) - A custom animation for the UIRefreshControl :large_orange_diamond:
* [NJKWebViewProgress ★3594](ninjinkun/NJKWebViewProgress) - A progress interface library for UIWebView. You can implement progress bar for your in-app browser using this module.
* [MKRingProgressView ★552](maxkonovalov/MKRingProgressView) - A beautiful ring/circular progress view similar to Activity app on Apple Watch, written in Swift. 🔶
* [Hexacon ★236](gautier-gdx/Hexacon) - A new way to display content in your app like the Apple Watch SpringBoard, written in Swift. 🔶
* [StackViewController ★592](seedco/StackViewController) - A controller that uses a UIStackView and view controller composition to display content in a list :large_orange_diamond:
* [ParticlesLoadingView ★737](BalestraPatrick/ParticlesLoadingView) - A customizable SpriteKit particles animation on the border of a view. :large_orange_diamond:
* [RPCircularProgress ★82](iwasrobbed/RPCircularProgress) - (Swift) Circular progress UIView subclass with UIProgressView properties :large_orange_diamond:
* [MBCircularProgressBar ★603](MatiBot/MBCircularProgressBar) -  A circular, animatable & highly customizable progress bar, editable from the Interface Builder using IBDesignable.
* [WSProgressHUD ★505](devSC/WSProgressHUD) - This is a beautiful hud view for iPhone & iPad
* [DBMetaballLoading ★45](dabing1022/DBMetaballLoading) - A metaball loading written in Swift. :large_orange_diamond:
* [FillableLoaders ★1630](poolqf/FillableLoaders) - Completely customizable progress based loaders drawn using custom CGPaths written in Swift :large_orange_diamond:
* [PageControls ★579](popwarsweet/PageControls) - This is a selection of custom page controls to replace UIPageControl, inspired by a dribbble found here :large_orange_diamond:
* [VHUD ★114](xxxAIRINxxx/VHUD) Simple HUD. :large_orange_diamond:
* [SwiftSpinner ★1512](icanzilb/SwiftSpinner) - A beautiful activity indicator and modal alert written in Swift using blur effects, translucency, flat and bold design :large_orange_diamond:
* [SnapTimer ★243](andresinaka/SnapTimer) - Implementation of Snapchat's stories timer. :large_orange_diamond:
* [AudioIndicatorBars ★145](LeonardoCardoso/AudioIndicatorBars) - AIB indicates for your app users which audio is playing. Just like the Podcasts app. :large_orange_diamond:
* [LLSpinner ★10](alaphao/LLSpinner) - An easy way to create a full screen activity indicator. :large_orange_diamond:
* [SVUploader ★14](kirankunigiri/SVUploader) - A beautiful uploader progress view that makes things simple and easy.  :large_orange_diamond:
* [YLProgressBar ★898](yannickl/YLProgressBar) - UIProgressView replacement with an highly and fully customizable animated progress bar in pure Core Graphics.
* [FlexibleSteppedProgressBar ★67](amratab/FlexibleSteppedProgressBar) - A beautiful easily customisable stepped progress bar.  :large_orange_diamond:
* [GradientLoadingBar ★27](fxm90/GradientLoadingBar) - An animated gradient loading bar. :large_orange_diamond:
* [DSGradientProgressView ★210](DholStudio/DSGradientProgressView) - A simple and customizable animated progress bar written in Swift. :large_orange_diamond:
* [GradientProgressBar ★9](fxm90/GradientProgressBar) - A gradient progress bar (UIProgressView). :large_orange_diamond:
* [BPCircleActivityIndicator ★26](ppth0608/BPCircleActivityIndicator) - A lightweight and awesome Loading Activity Indicator for your iOS app. :large_orange_diamond:
* [DottedProgressBar ★11](nikola9core/DottedProgressBar) - Simple and customizable animated progress bar with dots for iOS. :large_orange_diamond:
* [RSLoadingView ★144](roytornado/RSLoadingView) - Awesome loading animations using 3D engine written with Swift. :large_orange_diamond:

#### Animation
* [Pop ★17713](facebook/pop) - An extensible iOS and OS X animation library, useful for physics-based interactions.
* [AnimationEngine ★1010 ⏳1Y](intuit/AnimationEngine) - Easily build advanced custom animations on iOS.
* [Awesome-iOS-Animation ★762](jackyzh/awesome-ios-animation) - Collection of Animation projects
* [RZTransitions ★1683](Raizlabs/RZTransitions) - A library of custom iOS View Controller Animations and Interactions.
* [DCAnimationKit ★712 ⏳1Y](daltoniam/DCAnimationKit) - A collection of animations for iOS. Simple, just add water animations.
* [Spring ★10734](MengTo/Spring) - A library to simplify iOS animations in Swift. :large_orange_diamond:
* [Canvas ★5165 ⏳1Y](CanvasPod/Canvas) - Animate in Xcode without code http://canvaspod.io
* [Fluent ★297](matthewcheok/Fluent) - Swift animation made easy :large_orange_diamond:
* [Cheetah ★538](suguru/Cheetah) - Easy animation library on iOS with Swift2. :large_orange_diamond:
* [RadialLayer ★47 ⏳1Y](soheil/RadialLayer) - Animation for clickable elements (similar to Youtube Music). :large_orange_diamond:
* [Pop By Example ★165 ⏳1Y](hossamghareeb/Facebook-POP-Tutorial) - A project tutorial in how to use Pop animation framework by example.
* [AppAnimations](http://www.appanimations.com) - Collection of iOS animations to inspire your next project
* [EasyAnimation ★2379](icanzilb/EasyAnimation) - A Swift library to take the power of UIView.animateWithDuration() to a whole new level - layers, springs, chain-able animations, and mixing view/layer animations together. :large_orange_diamond:
* [Animo ★164](eure/Animo) - SpriteKit-like animation builders for CALayers. :large_orange_diamond:
* [CurryFire ★75](devinross/curry-fire) - A framework for creating unique animations.
* [IBAnimatable ★6316](IBAnimatable/IBAnimatable) - Design and prototype UI, interaction, navigation, transition and animation for App Store ready Apps in Interface Builder with IBAnimatable. :large_orange_diamond:
* [CKWaveCollectionViewTransition ★1516](CezaryKopacz/CKWaveCollectionViewTransition) - Cool wave like transition between two or more UICollectionView :large_orange_diamond:
* [DaisyChain ★19](alikaragoz/DaisyChain) - :link: Easy animation chaining :large_orange_diamond:
* [SYBlinkAnimationKit ★83](shoheiyokoyama/SYBlinkAnimationKit) - A blink effect animation framework for iOS, written in Swift. :large_orange_diamond:
* [PulsingHalo ★1542](shu223/PulsingHalo) - iOS Component for creating a pulsing animation.
* [DKChainableAnimationKit ★1752](Draveness/DKChainableAnimationKit) - Chainable animations in Swift :large_orange_diamond:
* [JDAnimationKit ★500](JellyDevelopment/JDAnimationKit) - Animate easy and with less code with Swift :large_orange_diamond:
* [Advance ★3938](storehouse/Advance) - A powerful animation framework for iOS. :large_orange_diamond:
* [UIView-Shake ★447](andreamazz/UIView-Shake) - UIView category that adds shake animation
* [Walker ★122](RamonGilabert/Walker) - A new animation engine for your app. :large_orange_diamond:
* [Morgan ★84](RamonGilabert/Morgan) - An animation set for your app. :large_orange_diamond:
* [MagicMove ★10 ⏳1Y](patrickreynolds/MagicMove) - Keynote-style Magic Move transition animations :large_orange_diamond:
* [Shimmer ★7829](facebook/Shimmer) - An easy way to add a simple, shimmering effect to any view in an iOS app.
* [SAConfettiView ★936](sudeepag/SAConfettiView) - Confetti! Who doesn't like confetti? :large_orange_diamond:
* [CCMRadarView ★177](cacmartinez/CCMRadarView) - CCMRadarView uses the IBDesignable tools to make an easy customizable radar view with animation :large_orange_diamond:
* [Pulsator ★714](shu223/Pulsator) - Pulse animation for iOS :large_orange_diamond:
* [Interpolate ★1475](marmelroy/Interpolate) - Swift interpolation for gesture-driven animations :large_orange_diamond:
* [ADPuzzleAnimation ★106](Antondomashnev/ADPuzzleAnimation) - Custom animation for UIView inspired by Fabric - Answers animation. :large_orange_diamond:
* [Wave ★59](onmyway133/Wave) - :ocean: Declarative chainable animations in Swift :large_orange_diamond:
* [Stellar ★2300](AugustRush/Stellar) - A fantastic Physical animation library for swift :large_orange_diamond:
* [MotionMachine ★315](poetmountain/MotionMachine) - A powerful, elegant, and modular animation library for Swift. :large_orange_diamond:
* [JRMFloatingAnimation ★149](carleihar/JRMFloatingAnimation) - An Objective-C animation library used to create floating image views.
* [AHKBendableView ★593](fastred/AHKBendableView) - UIView subclass that bends its edges when its position changes. :large_orange_diamond:
* [FlightAnimator ★543](AntonTheDev/FlightAnimator) - Advanced Natural Motion Animations, Simple Blocks Based Syntax :large_orange_diamond:
* [ZoomTransitioning ★508](WorldDownTown/ZoomTransitioning) - A custom transition with image zooming animation. :large_orange_diamond:
* [Ubergang ★39](RobinFalko/Ubergang) - A tweening engine for iOS written in Swift. :large_orange_diamond:
* [JHChainableAnimations ★2884](jhurray/JHChainableAnimations) - Easy to read and write chainable animations in Objective-C
* [Popsicle ★1126](DavdRoman/Popsicle) - Delightful, extensible Swift value interpolation framework :large_orange_diamond:
* [WXWaveView ★267](WelkinXie/WXWaveView) - Add a pretty water wave to your view.
* [Twinkle ★414](piemonte/Twinkle) - :sparkles: Swift and easy way to make elements in your iOS and tvOS app twinkle :large_orange_diamond:
* [MotionBlur ★1457 ⏳2Y](fastred/MotionBlur) - MotionBlur allows you to add motion blur effect to iOS animations.
* [RippleEffectView ★281](alsedi/RippleEffectView) - RippleEffectView - A Neat Rippling View Effect :large_orange_diamond:
* [Keyframes ★4405](facebookincubator/Keyframes) - A library for converting Adobe AE shape based animations to a data format and play it back on Android and iOS devices.
* [SwiftyAnimate ★128](rchatham/SwiftyAnimate) - Composable animations in Swift. :large_orange_diamond:
* [SamuraiTransition ★187](hachinobu/SamuraiTransition) - Swift based library providing a collection of ViewController transitions featuring a number of neat “cutting” animations. :large_orange_diamond:
* [Lottie ★8610](airbnb/lottie-ios) - An iOS library for a real time rendering of native vector animations from Adobe After Effects.
* [Overlap ★106](ML-Works/Overlap) - Tiny iOS library to achieve overlap visual effect. :large_orange_diamond:
* [anim ★26](onurersel/anim) - An animation library for iOS with custom easings and easy to follow API. :large_orange_diamond:
* [AnimatedCollectionViewLayout ★2425](KelvinJin/AnimatedCollectionViewLayout) - A UICollectionViewLayout subclass that adds custom transitions/animations to the UICollectionView. :large_orange_diamond:
* [Dance ★571](saoudrizwan/Dance) - A radical & elegant animation library built for iOS. :large_orange_diamond:
* [AKVideoImageView ★108](numen31337/AKVideoImageView) - UIImageView subclass which allows you to display a looped video as a background.
* [Spruce iOS Animation Library ★1978](willowtreeapps/spruce-ios) - Swift library for choreographing animations on the screen.:large_orange_diamond:
* [CircularRevealKit ★8](T-Pro/CircularRevealKit) - UI framework that implements the material design's reveal effect. 🔶
* [TweenKit ★445](SteveBarnegren/TweenKit) - Animation library for iOS in Swift. 🔶
* [Water ★291](KrisYu/Water) - Simple calculation to render cheap water effects. 🔶
* [CRRefresh ★296](CRAnimation/CRRefresh) - An easy way to use pull-to-refresh. 🔶
* [Pastel ★1801](cruisediary/Pastel) - Gradient animation effect like Instagram. 🔶

##### Transition
* [BlurryModalSegue ★917 ⏳1Y](Citrrus/BlurryModalSegue) - A custom modal segue for providing a blurred overlay effect.
* [DAExpandAnimation ★508](ifitdoesntwork/DAExpandAnimation) - A custom modal transition that presents a controller with an expanding effect while sliding out the presenter remnants. :large_orange_diamond:
* [BubbleTransition ★2407](andreamazz/BubbleTransition) - A custom modal transition that presents and dismiss a controller with an expanding bubble effect. :large_orange_diamond:
* [RPModalGestureTransition ★78](naoyashiga/RPModalGestureTransition) - You can dismiss modal by using gesture :point_up_2: :iphone: :large_orange_diamond:
* [RMPZoomTransitionAnimator ★1483](recruit-mp/RMPZoomTransitionAnimator) - A custom zooming transition animation for UIViewController
* [ElasticTransition ★1661](lkzhao/ElasticTransition) - A UIKit custom transition that simulates an elastic drag. Written in Swift. :large_orange_diamond:
* [ElasticTransition-ObjC ★343 ⏳1Y](taglia3/ElasticTransition-ObjC) - A UIKit custom transition that simulates an elastic drag.This is the Objective-C Version of Elastic Transition written in Swift by lkzhao
* [ZFDragableModalTransition ★2203](zoonooz/ZFDragableModalTransition) - Custom animation transition for present modal view controller
* [ImageOpenTransition ★766](mcmatan/ImageOpenTransition) - Beautiful and precise transitions between ViewControllers images written in Swift. :large_orange_diamond:
* [ZOZolaZoomTransition ★849](NewAmsterdamLabs/ZOZolaZoomTransition) - Zoom transition that animates the entire view heirarchy. Used extensively in the Zola iOS application.
* [JTMaterialTransition ★848](jonathantribouharet/JTMaterialTransition) - An iOS transition for controllers based on material design.
* [AnimatedTransitionGallery ★2133](shu223/AnimatedTransitionGallery) - Collection of iOS 7 custom animated transitions using UIViewControllerAnimatedTransitioning protocol.
* [TransitionTreasury ★1797](DianQK/TransitionTreasury) - Easier way to push your viewController. :large_orange_diamond:
* [Presenter ★8](muukii/Presenter) - Screen transition with safe and clean code.  :large_orange_diamond:
* [Kaeru ★398](bannzai/Kaeru) - Switch viewcontroller like iOS task manager :large_orange_diamond:
* [View2ViewTransition ★759](naru-jpn/View2ViewTransition) - Custom interactive view controller transition from one view to another view. :large_orange_diamond:
* [AZTransitions ★350](azimin/AZTransitions) - API to make great custom transitions in one method. :large_orange_diamond:
* [Hero ★8825](lkzhao/Hero) - Supercharged transition engine for iOS. Build your custom view transitions with no code at all. Inspired by Keynote's Magic Move. :large_orange_diamond:
* [Motion ★510](CosmicMind/Motion) - Seamless animations and transitions in Swift. :large_orange_diamond:
* [PresenterKit ★365](jessesquires/PresenterKit) - Swifty view controller presentation for iOS :large_orange_diamond:
* [Transition ★1598](Touchwonders/Transition) - Easy interactive interruptible custom ViewController transitions. :large_orange_diamond:

#### Alert & Action Sheet

* [NZAlertView ★714](NZN/NZAlertView) - Simple and intuitive alert view. Similar to push notification effect.
* [AMSmoothAlert ★1290 ⏳1Y](mtonio91/AMSmoothAlert) - A cool AlertView.
* [SweetAlert ★1678](codestergit/SweetAlert-iOS) - Live animated Alert View for iOS written in Swift. :large_orange_diamond:
* [NYAlertViewController ★484](nealyoung/NYAlertViewController) - Highly configurable iOS Alert Views with custom content views.
* [SCLAlertView-Swift ★3767](vikmeup/SCLAlertView-Swift) - Beautiful animated Alert View, written in Swift. :large_orange_diamond:
* [TTGSnackbar ★294](zekunyan/TTGSnackbar) - Show simple message and action button on the bottom of the screen with multi kinds of animation. :large_orange_diamond:
* [TSMessages ★4822](KrauseFx/TSMessages) - Show notification views on top of screen such as success, error, warning or messages for iOS.
* [PJAlertView ★6 ⏳1Y](PrajeetShrestha/PJAlertView) - Apple has deprecated beloved alert view but this library will add revamped alert view with far more customization possibility.
* [Swift-Prompts ★705](GabrielAlva/Swift-Prompts) - A Swift library to design custom prompts with a great scope of options to choose from. :large_orange_diamond:
* [BRYXBanner ★768](bryx-inc/BRYXBanner) - A lightweight dropdown notification for iOS 7+, in Swift. :large_orange_diamond:
* [LNRSimpleNotifications ★162](LISNR/LNRSimpleNotifications) - Simple Swift in-app notifications. LNRSimpleNotifications is a simplified Swift port of TSMessages :large_orange_diamond:
* [HDNotificationView ★235](nhdang103/HDNotificationView) - Emulates the native Notification Banner UI for any alert.
* [JDStatusBarNotification ★3141](calimarkus/JDStatusBarNotification) - Easy, customizable notifications displayed on top of the statusbar.
* [Notie ★72](thii/Notie) - In-app notification in Swift, with customizable buttons and input text field. :large_orange_diamond:
* [EZAlertController ★266](thellimist/EZAlertController) - Easy Swift UIAlertController :large_orange_diamond:
* [SnowGlobeFramework ★59](stringcode86/SnowGlobeFramework) - Delightful / slightly cheese easter egg for Christmas season. Turns your awesome app into a snow globe, when user shake the device. :large_orange_diamond:
* [GSMessages ★208](wxxsw/GSMessages) - A simple style messages/notifications for iOS 7+. :large_orange_diamond:
* [OEANotification ★17 ⏳1Y](OEA/OEANotification) - In-app customizable notification views on top of screen for iOS which is written in Swift 2.1. :large_orange_diamond:
* [GSAlert ★25 ⏳1Y](wxxsw/GSAlert) - If you want to use UIAlertController, but still need to support iOS 7 this project is for you. :large_orange_diamond:
* [RKDropdownAlert ★1370](cwRichardKim/RKDropdownAlert) - Extremely simple UIAlertView alternative.
* [TKSwarmAlert ★421](entotsu/TKSwarmAlert) - Animated alert library like Swarm app. :large_orange_diamond:
* [Whisper ★2786](hyperoslo/Whisper) - Whisper is a component that will make the task of display messages and in-app notifications simple. It has three different views inside :large_orange_diamond:
* [SimpleAlert ★278](KyoheiG3/SimpleAlert) - Customizable simple Alert and simple ActionSheet for Swift :large_orange_diamond:
* [Hokusai ★362](ytakzk/Hokusai) - A Swift library to provide a bouncy action sheet :large_orange_diamond:
* [SwiftNotice ★543](johnlui/SwiftNotice) - SwiftNotice is a GUI library for displaying various popups (HUD) written in pure Swift, fits any scrollview. :large_orange_diamond:
* [SwiftOverlays ★438](peterprokop/SwiftOverlays) - SwiftOverlays is a Swift GUI library for displaying various popups and notifications :large_orange_diamond:
* [SwiftyDrop ★517](morizotter/SwiftyDrop) - SwiftyDrop is a lightweight pure Swift simple and beautiful dropdown message. :large_orange_diamond:
* [LKAlertController ★54](Lightningkite/LKAlertController) - An easy to use UIAlertController builder for swift. :large_orange_diamond:
* [DOAlertController ★314](okmr-d/DOAlertController) - Simple Alert View written in Swift, which can be used as a UIAlertController. (AlertController/AlertView/ActionSheet) :large_orange_diamond:
* [CustomizableActionSheet ★121](beryu/CustomizableActionSheet) - Action sheet allows including your custom views and buttons. :large_orange_diamond:
* [Toast-Swift ★715](scalessec/Toast-Swift) - A Swift extension that adds toast notifications to the UIView object class. :large_orange_diamond:
* [PMAlertController ★1574](Codeido/PMAlertController) - PMAlertController is a great and customizable substitute to UIAlertController. 🔶
* [PopupViewController ★15](dimillian/PopupViewController) - UIAlertController drop in replacement with much more customization. 🔶
* [AlertViewLoveNotification ★22](PhilippeBoisney/AlertViewLoveNotification) - A simple and attractive AlertView to ask permission to your users for Push Notification. 🔶
* [CRToast ★3809](cruffenach/CRToast) - A modern iOS toast view that can fit your notification needs
* [JLToast ★749](devxoul/Toaster) - Toast for iOS with very simple interface. :large_orange_diamond:
* [CuckooAlert ★5](singcodes/CuckooAlert) - Multiple use of presentViewController for UIAlertController. 🔶
* [KRAlertController ★31](krimpedance/KRAlertController) - A colored alert view for your iOS. :large_orange_diamond:
* [Dodo ★730](marketplacer/Dodo) - A message bar for iOS written in Swift. :large_orange_diamond:
* [MaterialActionSheetController ★80](ntnhon/MaterialActionSheetController) - A Google like action sheet for iOS written in Swift. :large_orange_diamond:
* [SwiftMessages ★2091](SwiftKickMobile/SwiftMessages) - A very flexible message bar for iOS written in Swift. :large_orange_diamond:
* [FCAlertView ★65](krispenney/FCAlertView) - A Flat Customizable AlertView for iOS. (Swift) :large_orange_diamond:
* [FCAlertView ★576](nimati/FCAlertView) - A Flat Customizable AlertView for iOS. (Objective-C)
* [CDAlertView ★656](candostdagdeviren/CDAlertView) - Highly customizable alert/notification/success/error/alarm popup 🔶
* [RMActionController ★218](CooperRS/RMActionController) - Present any UIView in an UIAlertController like manner.
* [RMDateSelectionViewController ★986](CooperRS/RMDateSelectionViewController) - Select a date using UIDatePicker in a UIAlertController like fashion.
* [RMPickerViewController ★315](CooperRS/RMPickerViewController) - Select something using UIPickerView in a UIAlertController like fashion.
* [Hedwig ★15](Lab111/Hedwig) - Interactive notification :large_orange_diamond:
* [Jelly ★1313](SebastianBoldt/Jelly) - Jelly provides custom view controller transitions with just a few lines of code. :large_orange_diamond:
* [Malert ★147](vitormesquita/Malert) - Malert is a simple, easy and custom iOS UIAlertView written in Swift 🔶
* [RAlertView ★29](roycms/AlertView) - AlertView, iOS popup window, A pop-up framework, Can be simple and convenient to join your project.
* [NoticeBar ★212](qiuncheng/NoticeBar) - 😍A simple NoticeBar written by Swift 3, similar with QQ notice view. :large_orange_diamond:
* [LIHAlert ★19](Lasithih/LIHAlert) - Advance animated banner alerts for iOS :large_orange_diamond:
* [BPStatusBarAlert ★56](ppth0608/BPStatusBarAlert) - A simple alerts that appear on the status bar and below navigation bar(like Facebook).🔶
* [CFAlertViewController ★720](Codigami/CFAlertViewController) -  A library that helps you display and customise alerts and action sheets on iPad and iPhone.🔶
* [NotificationBanner ★979](Daltron/NotificationBanner) - The easiest way to display highly customizable in app notification banners in iOS. 🔶
* [Alertift ★41](sgr-ksmt/Alertift) - Swifty, modern UIAlertController wrapper. :large_orange_diamond:
* [PCLBlurEffectAlert ★112](hryk224/PCLBlurEffectAlert) - Swift AlertController with UIVisualEffectView. :large_orange_diamond:
* [JDropDownAlert ★28](trilliwon/JDropDownAlert) - Multi dirction dropdown alert view. 🔶

#### Badge
* [MIBadgeButton ★253](mustafaibrahim989/MIBadgeButton-Swift) - Notification badge for UIButtons. :large_orange_diamond:
* [EasyNotificationBadge ★22](Minitour/EasyNotificationBadge) - UIView extension that adds a notification badge. :large_orange_diamond:[e]
* [Sheriff ★222](gemr/Sheriff) - Add badges to anything.
* [swift-badge ★187](marketplacer/swift-badge) - Badge view for iOS written in swift :large_orange_diamond:

#### Button
* [SSBouncyButton ★290](StyleShare/SSBouncyButton) - iOS7-style bouncy button UI component.
* [DOFavoriteButton ★2764](okmr-d/DOFavoriteButton) - Cute Animated Button written in Swift. :large_orange_diamond:
* [SDevBootstrapButton ★38 ⏳1Y](0x73/SDevBootstrapButton) - Twitter Bootstrap buttons for Swift :large_orange_diamond:
* [SDevCircleButton ★22 ⏳1Y](0x73/SDevCircleButton) - Flat circle button :large_orange_diamond:
* [VBFPopFlatButton ★2785](victorBaro/VBFPopFlatButton) - Flat button with 9 different states animated using Facebook POP.
* [HTPressableButton ★805](Famolus/HTPressableButton) - Flat design pressable button.
* [LiquidFloatingActionButton ★2965](yoavlt/LiquidFloatingActionButton) - Material Design Floating Action Button in liquid state :large_orange_diamond:
* [JTFadingInfoView ★122 ⏳1Y](JunichiT/JTFadingInfoView) - An UIButton-based view with fade in/out animation features.
* [Floaty ★428](kciter/Floaty) - :heart: Floating Action Button for iOS :large_orange_diamond:
* [Hamburger-Menu-Button ★115 ⏳1Y](toannt/Hamburger-Menu-Button) - A hamburger menu button with full customization. :large_orange_diamond:
* [TVButton ★893](marmelroy/TVButton) - Recreating the cool parallax icons from Apple TV as iOS UIButtons (in Swift). :large_orange_diamond:
* [SwiftyButton ★211](TakeScoop/SwiftyButton) - Simple and customizable button in Swift :large_orange_diamond:
* [AnimatablePlayButton ★61 ⏳1Y](suzuki-0000/AnimatablePlayButton) - Animated Play and Pause Button using CALayer, CAKeyframeAnimation. :large_orange_diamond:
* [VCFloatingActionButton ★280](giridharvc7/VCFloatingActionButton) - A Floating Action Button just like Google inbox for iOS
* [FlowBarButtonItem ★148 ⏳1Y](noppefoxwolf/FlowBarButtonItem) - Bar Button Item that can be moved anywhere in the screen, like Android's stickers button. :large_orange_diamond:
* [gbkui-button-progress-view ★500 ⏳1Y](Guidebook/gbkui-button-progress-view) - Inspired by Apple’s download progress buttons in the App Store.
* [ZFRippleButton ★1243](zoonooz/ZFRippleButton) - Custom UIButton effect inspired by Google Material Design :large_orange_diamond:
* [ProgressButton ★109 ⏳1Y](sprint84/ProgressButton) - Custom button class that displays a progress bar around it to gauge :large_orange_diamond:
* [JOEmojiableBtn ★202](lojals/JOEmojiableBtn) - Emoji selector like Facebook Reactions.
* [EMEmojiableBtn ★67](Eke/EMEmojiableBtn) - Option selector that works similar to Reactions by fb. Objective-c version.
* [WYMaterialButton ★41](Yu-w/WYMaterialButton) - Interactive and fully animated Material Design button for iOS developers.
* [DynamicButton ★815](yannickl/DynamicButton) - Yet another animated flat buttons in Swift :large_orange_diamond:
* [OnOffButton ★394](rakaramos/OnOffButton) - Custom On/Off Animated UIButton, written in Swift. By Creativedash :large_orange_diamond:
* [CRNetworkButton ★561](Cleveroad/CRNetworkButton) - Send Button for iOS :large_orange_diamond:
* [WCLShineButton ★834](imwcl/WCLShineButton) - This is a UI lib for iOS. Effects like shining. :large_orange_diamond:
* [EasySocialButton ★121](Minitour/EasySocialButton) - An easy way to create beautiful social authentication buttons. :large_orange_diamond:
* [NFDownloadButton ★164](LeonardoCardoso/NFDownloadButton) - Revamped Download Button. 🔶

#### Calendar
* [CVCalendar ★2554](CVCalendar/CVCalendar) - A custom visual calendar for iOS 8+ written in Swift (2.0). :large_orange_diamond:
* [RSDayFlow ★738](ruslanskorb/RSDayFlow) - iOS 7+ Calendar with Infinite Scrolling.
* [NWCalendarView ★53](nbwar/NWCalendarView) - An availability calendar implementation for iOS :large_orange_diamond:
* [FSCalendar ★4226](WenchaoD/FSCalendar) - A superiorly awesome iOS7+ calendar control, compatible with both Objective-C and Swift2.
* [GLCalendarView ★795](Glow-Inc/GLCalendarView) - A fully customizable calendar view acting as a date range picker
* [JTCalendar ★2319](jonathantribouharet/JTCalendar) - A customizable calendar view for iOS.
* [JTAppleCalendar ★2972](patchthecode/JTAppleCalendar) - The Unofficial Swift Apple Calendar Library. View. Control. for iOS & tvOS :large_orange_diamond:
* [Daysquare ★555](unixzii/Daysquare) - An elegant calendar control for iOS.
* [ASCalendar ★182](scamps88/ASCalendar) - A calendar control for iOS written in swift with mvvm pattern :large_orange_diamond:
* [Calendar ★477](jumartin/Calendar) - A set of views and controllers for displaying and scheduling events on iOS
* [Koyomi ★391](shoheiyokoyama/Koyomi) - Simple customizable calendar component in Swift :large_orange_diamond:
* [DateTimePicker ★1100](itsmeichigo/DateTimePicker) - A nicer iOS UI component for picking date and time :large_orange_diamond:
* [RCalendarPicker ★36](roycms/RCalendarPicker) - RCalendarPicker A date picker control.
* [CalendarKit ★703](richardtop/CalendarKit) - Fully customizable calendar day view. :large_orange_diamond:

#### Form & Settings
* [Form ★1551](hyperoslo/Form) - The most flexible and powerful way to build a form on iOS
* [XLForm ★4477](xmartlabs/XLForm) - XLForm is the most flexible and powerful iOS library to create dynamic table-view forms. Fully compatible with Swift & Obj-C.
* [Eureka ★6103](xmartlabs/Eureka) - Elegant iOS form builder in pure Swift. :large_orange_diamond:
* [YALField ★439](Yalantis/YALField) - Custom Field component with validation for creating easier form-like UI from interface builder.
* [Former ★900](ra1028/Former) - Former is a fully customizable Swift2 library for easy creating UITableView based form. :large_orange_diamond:
* [SwiftForms ★1061](ortuman/SwiftForms) - A small and lightweight library written in Swift that allows you to easily create forms. :large_orange_diamond:
* [APValidators ★107](Alterplay/APValidators) - Codeless solution for form validation in iOS!
* [Formalist ★120](seedco/Formalist) - Declarative form building framework for iOS :large_orange_diamond:
* [SwiftyFORM ★666](neoneye/SwiftyFORM) - SwiftyFORM is a form framework for iOS written in Swift :large_orange_diamond:
* [FXForms ★2988](nicklockwood/FXForms) - FXForms is an Objective-C library for easily creating table-based forms on iOS. It is ideal for settings pages, or user data entry tasks.
* [SwiftValidator ★879](jpotts18/SwiftValidator) - A rule-based validation library for Swift :large_orange_diamond:
* [MZFormSheetPresentationController ★811](m1entus/MZFormSheetPresentationController) - MZFormSheetPresentationController provides an alternative to the native iOS UIModalPresentationFormSheet, adding support for iPhone and additional opportunities to setup controller size and feel form sheet.
* [GenericPasswordRow ★126](EurekaCommunity/GenericPasswordRow) - A row for Eureka to implement password validations. :large_orange_diamond:
* [SuggestionsBox ★96](manuelescrig/SuggestionsBox) - SuggestionsBox helps you build better a product trough your user suggestions. :large_orange_diamond:
* [formvalidator-swift ★449](ustwo/formvalidator-swift) - A framework to validate inputs of text fields and text views in a convenient way. :large_orange_diamond:
* [LightForm ★2](farshidce/LightForm) - A Simple interactive and customizable library to handle form input and validations

#### Keyboard
* [RSKKeyboardAnimationObserver ★31 ⏳1Y](ruslanskorb/RSKKeyboardAnimationObserver) - Showing / dismissing keyboard animation in simple UIViewController category.
* [RFKeyboardToolbar ★395](ruddfawcett/RFKeyboardToolbar) - This is a flexible UIView and UIButton subclass to add customized buttons and toolbars to your UITextFields/UITextViews.
* [IQKeyboardManager ★9051](hackiftekhar/IQKeyboardManager) - Codeless drop-in universal library allows to prevent issues of keyboard sliding up and cover UITextField/UITextView.
* [NgKeyboardTracker ★761 ⏳1Y](meiwin/NgKeyboardTracker) - Objective-C library for tracking keyboard in iOS apps.
* [MMNumberKeyboard ★831](matmartinez/MMNumberKeyboard) - A simple keyboard to use with numbers and, optionally, a decimal point.
* [KeyboardObserver ★90](morizotter/KeyboardObserver) - For less complicated keyboard event handling. :large_orange_diamond:
* [TPKeyboardAvoiding ★5191](michaeltyson/TPKeyboardAvoiding) - A drop-in universal solution for moving text fields out of the way of the keyboard in iOS
* [YYKeyboardManager ★350](ibireme/YYKeyboardManager) - iOS utility class allows you to access keyboard view and track keyboard animation.
* [KeyboardMan ★320](nixzhu/KeyboardMan) - KeyboardMan helps you make keyboard animation. :large_orange_diamond:
* [MakemojiSDK ★80](makemoji/MakemojiSDK) - Emoji Keyboard SDK (iOS)
* [Typist ★783](totocaster/Typist) - Small, drop-in Swift UIKit keyboard manager for iOS apps-helps manage keyboard's screen presence and behavior without notification center. :large_orange_diamond:
* [KeyboardHideManager ★40](bonyadmitr/KeyboardHideManager) - Codeless manager to hide keyboard by tapping on views for iOS written in Swift :large_orange_diamond:

#### Label
* [LTMorphingLabel ★5607](lexrus/LTMorphingLabel) - Graceful morphing effects for UILabel written in Swift. :large_orange_diamond:
* [ActiveLabel.swift ★1740](optonaut/ActiveLabel.swift) - UILabel drop-in replacement supporting Hashtags (#), Mentions (@) and URLs (http://) written in Swift :large_orange_diamond:
* [MZTimerLabel ★1248](mineschan/MZTimerLabel) - A handy class for iOS to use UILabel as a countdown timer or stopwatch just like in Apple Clock App.
* [CountdownLabel ★267](suzuki-0000/CountdownLabel) - Simple countdown UILabel with morphing animation, and some useful function. :large_orange_diamond:
* [IncrementableLabel ★32](tbaranes/IncrementableLabel) - Incrementable label for iOS, OS X, and tvOS. :large_orange_diamond:
* [TTTAttributedLabel ★7496](TTTAttributedLabel/TTTAttributedLabel) - A drop-in replacement for UILabel that supports attributes, data detectors, links, and more
* [NumberMorphView ★1251](me-abhinav/NumberMorphView) - A label view for displaying numbers which can transition or animate using a technique called number tweening or number morphing. :large_orange_diamond:
* [GlitchLabel ★635](kciter/GlitchLabel) - Glitching UILabel for iOS. :large_orange_diamond:
* [TOMSMorphingLabel ★1831 ⏳1Y](tomknig/TOMSMorphingLabel) - Configurable morphing transitions between text values of a label.
* [THLabel ★522](tobihagemann/THLabel) - UILabel subclass, which additionally allows shadow blur, inner shadow, stroke text and fill gradient.
* [RQShineLabel ★1600](zipme/RQShineLabel) - Secret app like text animation
* [ZCAnimatedLabel ★1712](overboming/ZCAnimatedLabel) - UILabel replacement with fine-grain appear/disappear animation
* [TriLabelView ★97](mukeshthawani/TriLabelView) - A triangle shaped corner label view for iOS written in Swift. :large_orange_diamond:
* [Preloader.Ophiuchus ★804](Yalantis/Preloader.Ophiuchus) - Custom Label to apply animations on whole text or letters.
* [MTLLinkLabel ★67](recruit-mtl/MTLLinkLabel) - MTLLinkLabel is linkable UILabel. Written in Swift. :large_orange_diamond:
* [UICountingLabel ★1103](dataxpress/UICountingLabel) - Adds animated counting support to UILabel.
* [SlidingText ★29](dnKaratzas/SlidingText) -  Swift UIView for sliding text with page indicator. :large_orange_diamond:
* [NumericAnimatedLabel ★2](javalnanda/NumericAnimatedLabel) -  Swift UIView for showing numeric label with incremental and decremental step animation while changing value. Useful for scenarios like displaying currency. :large_orange_diamond:

#### Menu
* [ENSwiftSideMenu ★1682](evnaz/ENSwiftSideMenu) - A simple side menu for iOS 7/8 written in Swift. :large_orange_diamond:
* [RESideMenu ★6926](romaonthego/RESideMenu) - iOS 7/8 style side menu with parallax effect inspired by Dribbble shots.
* [SSASideMenu ★556](SSA111/SSASideMenu) - A Swift implementation of RESideMenu. A iOS 7/8 style side menu with parallax effect. :large_orange_diamond:
* [PagingMenuController ★1809](kitasuke/PagingMenuController) - Paging view controller with customizable menu in Swift. :large_orange_diamond:
* [RadialMenu ★263 ⏳1Y](bradjasper/radialmenu) - RadialMenu is a custom control for providing a touch context menu (like iMessage recording in iOS 8) built with Swift & POP :large_orange_diamond:
* [cariocamenu ★532](arn00s/cariocamenu) - The fastest zero-tap iOS menu. :large_orange_diamond:
* [VLDContextSheet ★163 ⏳1Y](vangelov/VLDContextSheet) - Context menu similar to the one in the Pinterest iOS app
* [GuillotineMenu ★2432](Yalantis/GuillotineMenu) - Our Guillotine Menu Transitioning Animation implemented in Swift reminds a bit of a notorious killing machine. :large_orange_diamond:
* [MediumMenu ★286](pixyzehn/MediumMenu) - A menu based on Medium iOS app. :large_orange_diamond:
* [SwiftySideMenu ★77 ⏳1Y](hossamghareeb/SwiftySideMenu) - SwiftySideMenu is a lightweight and easy to use side menu controller to add left menu and center view controllers with scale animation based on Pop framework.
* [LLSlideMenu ★521](lilei644/LLSlideMenu) - This is a spring slide menu for iOS apps
* [Swift-Slide-Menu ★53 ⏳1Y](PhilippeBoisney/Swift-Slide-Menu) - A Slide Menu, written in Swift, inspired by Slide Menu Material Design. :large_orange_diamond:
* [MenuItemKit ★326](cxa/MenuItemKit) - UIMenuItem with image and block(closure) :large_orange_diamond:
* [BTNavigationDropdownMenu ★1983](PhamBaTho/BTNavigationDropdownMenu) - The elegant dropdown menu, written in Swift, appears underneath navigation bar to display a list of related items when a user click on the navigation title. :large_orange_diamond:
* [ALRadialMenu ★29](AlexLittlejohn/ALRadialMenu) - A radial/circular menu featuring spring animations. Written in swift :large_orange_diamond:
* [AZDropdownMenu ★140](Azuritul/AZDropdownMenu) - An easy to use dropdown menu that supports images. :large_orange_diamond:
* [CircleMenu ★2166](Ramotion/circle-menu) - An animated, multi-option menu button. :large_orange_diamond:
* [SlideMenuControllerSwift ★2469](dekatotoro/SlideMenuControllerSwift) - iOS Slide Menu View based on Google+, iQON, Feedly, Ameba iOS app. It is written in pure Swift. :large_orange_diamond:
* [SideMenu ★1252](jonkykong/SideMenu) - Simple side menu control in Swift inspired by Facebook. Right and Left sides. Lots of customization and animation options. Can be implemented in Storyboard with no code. :large_orange_diamond:
* [CategorySliderView ★349 ⏳1Y](cemolcay/CategorySliderView) - slider view for choosing categories. add any UIView type as category item view. Fully customisable
* [MKDropdownMenu ★250](maxkonovalov/MKDropdownMenu) - A Dropdown Menu for iOS with many customizable parameters to suit any needs.
* [ExpandingMenu ★248](monoqlo/ExpandingMenu) - ExpandingMenu is menu button for iOS written in Swift. :large_orange_diamond:
* [PageMenu ★3971](PageMenu/PageMenu) - A paging menu controller built from other view controllers placed inside a scroll view (like Spotify, Windows Phone, Instagram) :large_orange_diamond:
* [XXXRoundMenuButton ★269](zsy78191/XXXRoundMenuButton) - A simple circle style menu.
* [IGCMenu ★68](sunilsharma08/IGCMenu) - Grid and Circular menu with animation.Easy to customise.
* [EEJSelectMenu ★13](eejahromi/EEJSelectMenu) - Single selection menu with cool animations, responsive with all screen sizes.
* [IGLDropDownMenu ★1023](bestwnh/IGLDropDownMenu) - An iOS drop down menu with pretty animation and easy to customize.
* [Side-Menu.iOS ★2262](Yalantis/Side-Menu.iOS) - Animated side menu with customizable UI :large_orange_diamond:
* [PopMenu ★756](xhzengAIB/PopMenu) - PopMenu is pop animation menu inspired by Sina weibo / NetEase app.
* [FlowingMenu ★681](yannickl/FlowingMenu) - Interactive view transition to display menus with flowing and bouncing effects in Swift :large_orange_diamond:
* [Persei ★2653](Yalantis/Persei) - Animated top menu for UITableView / UICollectionView / UIScrollView written in Swift :large_orange_diamond:
* [DropDown ★779](AssistoLab/DropDown) - A Material Design drop down for iOS :large_orange_diamond:
* [KYGooeyMenu ★1663 ⏳1Y](KittenYang/KYGooeyMenu) - A not bad gooey effects menu.
* [SideMenuController ★835](teodorpatras/SideMenuController) - A side menu controller written in Swift :large_orange_diamond:
* [Context-Menu.iOS ★1701](Yalantis/Context-Menu.iOS) - You can easily add awesome animated context menu to your app.
* [ViewDeck ★5088](ViewDeck/ViewDeck) - An implementation of the sliding functionality found in the Path 2.0 or Facebook iOS apps.
* [FrostedSidebar ★423](edekhayser/FrostedSidebar) - Hamburger Menu using Swift and iOS 8 API's :large_orange_diamond:
* [VHBoomMenuButton ★316](Nightonke/VHBoomMenuButton) - A menu which can ... BOOM!
* [DropDownMenuKit ★107](qmathe/DropDownMenuKit) - A simple, modular and highly customizable UIKit menu, that can be attached to the navigation bar or toolbar, written in Swift. :large_orange_diamond:
* [RevealMenuController ★14](anatoliyv/RevealMenuController) - Expandable item groups, custom position and appearance animation. Similar to ActionSheet style. :large_orange_diamond:
* [RHSideButtons ★54](robertherdzik/RHSideButtons) - Library provides easy to implement variation of Android (Material Design) Floating Action Button for iOS. You can use it as your app small side menu. :large_orange_diamond:
* [Swift-CircleMenu ★99](Sufi-Al-Hussaini/Swift-CircleMenu) - Rotating circle menu written in Swift 3. :large_orange_diamond:
* [AKSideMenu ★82](dogo/AKSideMenu) - Beautiful iOS side menu library with parallax effect. :large_orange_diamond:
* [InteractiveSideMenu ★178](handsomecode/InteractiveSideMenu) - Customizable iOS Interactive Side Menu written in Swift 3. :large_orange_diamond:
* [YNDropDownMenu ★586](younatics/YNDropDownMenu) - Adorable iOS drop down menu with Swift3. :large_orange_diamond:
* [KWDrawerController ★39](Kawoou/KWDrawerController) - Drawer view controller that easy to use! :large_orange_diamond:
* [JNDropDownMenu ★22](javalnanda/JNDropDownMenu) - Easy to use tableview style drop down menu with multi-column support written in Swift3. :large_orange_diamond:
* [FanMenu ★31](exyte/fan-menu) - Menu with a circular layout based on Macaw. :large_orange_diamond:

#### Navigation Bar
* [HidingNavigationBar ★503](tristanhimmelman/HidingNavigationBar) - Easily hide and show a view controller's navigation bar (and tab bar) as a user scrolls :large_orange_diamond:
* [TLYShyNavBar ★3181](telly/TLYShyNavBar) - Unlike all those arrogant UINavigationBar, this one is shy and humble! Easily create auto-scrolling navigation bars!
* [KMNavigationBarTransition ★1860](MoZhouqi/KMNavigationBarTransition) - A drop-in universal library helps you to manage the navigation bar styles and makes transition animations smooth between different navigation bar styles while pushing or popping a view controller for all orientations.
* [LTNavigationBar ★3988](ltebean/LTNavigationBar) - UINavigationBar Category which allows you to change its appearance dynamically
* [BusyNavigationBar ★817](gmertk/BusyNavigationBar) - A UINavigationBar extension to show loading effects :large_orange_diamond:
* [KDInteractiveNavigationController ★97](kingiol/KDInteractiveNavigationController) - A UINavigationController subclass that support pop interactive UINavigationbar with hidden or show. :large_orange_diamond:
* [AMScrollingNavbar ★4720](andreamazz/AMScrollingNavbar) - Scrollable UINavigationBar that follows the scrolling of a UIScrollView :large_orange_diamond:
* [NavKit ★16](wilbertliu/NavKit) - Simple and integrated way to customize navigation bar experience on iOS app. :large_orange_diamond:

#### PickerView
* [ActionSheetPicker-3.0 ★2608](skywinder/ActionSheetPicker-3.0) - Quickly reproduce the dropdown UIPickerView / ActionSheet functionality on iOS.
* [PickerView ★233](filipealva/PickerView) - A customizable alternative to UIPickerView in Swift. :large_orange_diamond:
* [DatePickerDialog ★266](squimer/DatePickerDialog-iOS-Swift) - Date picker dialog for iOS :large_orange_diamond:
* [CZPicker ★447](chenzeyu/CZPicker) - A picker view shown as a popup for iOS.
* [AIDatePickerController ★76](alikaragoz/AIDatePickerController) - :date: UIDatePicker modally presented with iOS 7 custom transitions.
* [CountryPicker ★27](4taras4/CountryCode) - :date: UIPickerView with Country names flags and phoneCodes 🔶

#### Popup
* [PopupKit](https://github.com/rynecheow/PopupKit) - A simple and flexible class for presenting custom views as a popup in iOS and tvOS, maintained from [KLCPopup ★1605](jmascia/KLCPopup).
* [MMPopupView ★1629](adad184/MMPopupView) - Pop-up based view(e.g. alert sheet), can easily customize.
* [STPopup ★1902](kevin0571/STPopup) - STPopup provides a UINavigationController in popup style, for both iPhone and iPad.
* [NMPopUpView ★165](psy2k/NMPopUpView) - Simple iOS class for showing nice popup windows. Swift and Objective-C versions available. :large_orange_diamond:
* [CNPPopupController ★1510](carsonperrotti/CNPPopupController) - Simple and versatile class for presenting a custom popup in a variety of fashions. It includes a many options for controlling how your popup appears and behaves.
* [PopupController ★199](daisuke310vvv/PopupController) - A customizable controller for showing temporary popup view.
* [SubscriptionPrompt ★190](binchik/SubscriptionPrompt) - Subscription View Controller like the Tinder uses :large_orange_diamond:
* [Presentr ★1318](IcaliaLabs/Presentr) - Wrapper for custom ViewController presentations in iOS 8+ :large_orange_diamond:
* [PopupDialog ★1760](Orderella/PopupDialog) - A simple, customizable popup dialog for iOS written in Swift. Replaces UIAlertControllers alert style. :large_orange_diamond:
* [SelectionDialog ★63](kciter/SelectionDialog) - Simple selection dialog. :large_orange_diamond:
* [AZDialogViewController ★21](Minitour/AZDialogViewController) - A highly customizable alert dialog controller that mimics Snapchat's alert dialog. :large_orange_diamond:

#### Pull to Refresh
* [DGElasticPullToRefresh ★2739](gontovnik/DGElasticPullToRefresh) - Elastic pull to refresh for iOS developed in Swift :large_orange_diamond:
* [PullToBounce ★1563](entotsu/PullToBounce) - Animated "Pull To Refresh" Library for UIScrollView. :large_orange_diamond:
* [SVPullToRefresh ★4721](samvermette/SVPullToRefresh) - Give pull-to-refresh & infinite scrolling to any UIScrollView with 1 line of code. http://samvermette.com/314
* [UzysAnimatedGifPullToRefresh ★1387](uzysjung/UzysAnimatedGifPullToRefresh) - Add PullToRefresh using animated GIF to any scrollView with just simple code
* [PullToRefreshCoreText ★311](cemolcay/PullToRefreshCoreText) - PullToRefresh extension for all UIScrollView type classes with animated text drawing style
* [BOZPongRefreshControl ★892 ⏳2Y](boztalay/BOZPongRefreshControl) - A pull-down-to-refresh control for iOS that plays pong, originally created for the MHacks III iOS app
* [CBStoreHouseRefreshControl ★3907](coolbeet/CBStoreHouseRefreshControl) - Fully customizable pull-to-refresh control inspired by Storehouse iOS app
* [SurfingRefreshControl ★46](peiweichen/SurfingRefreshControl) - Inspired by CBStoreHouseRefreshControl.Customizable pull-to-refresh control,written in pure Swift :large_orange_diamond:
* [mntpulltoreact ★771 ⏳2Y](mentionapp/mntpulltoreact) - One gesture, many actions. An evolution of Pull to Refresh.
* [ADChromePullToRefresh ★221](Antondomashnev/ADChromePullToRefresh) - Chrome iOS app style pull to refresh with multiple actions.
* [BreakOutToRefresh ★2089](dasdom/BreakOutToRefresh) - A playable pull to refresh view using SpriteKit. :large_orange_diamond:
* [MJRefresh ★10409](CoderMJLee/MJRefresh) An easy way to use pull-to-refresh.
* [HTPullToRefresh ★26](hoang-tran/HTPullToRefresh) - Easily add vertical and horizontal pull to refresh to any UIScrollView. Can also add multiple pull-to-refesh views at once.
* [PullToRefreshSwift ★460](dekatotoro/PullToRefreshSwift) - iOS Simple Cool PullToRefresh Library. It is written in pure swift. :large_orange_diamond:
* [GIFRefreshControl ★125](delannoyk/GIFRefreshControl) - GIFRefreshControl is a pull to refresh that supports GIF images as track animations. :large_orange_diamond:
* [ReplaceAnimation ★775 ⏳1Y](fruitcoder/ReplaceAnimation) - Pull-to-refresh animation in UICollectionView with a sticky header flow layout, written in Swift :large_orange_diamond: :large_orange_diamond:
* [PullToMakeSoup ★1609](Yalantis/PullToMakeSoup) - Custom animated pull-to-refresh that can be easily added to UIScrollView :large_orange_diamond:
* [RainyRefreshControl ★561](Onix-Systems/RainyRefreshControl) - Simple refresh control for iOS inspired by [concept](https://dribbble.com/shots/2242263--1-Pull-to-refresh-Freebie-Weather-Concept). :large_orange_diamond:
* [ESPullToRefresh ★515](eggswift/pull-to-refresh) - Customisable pull-to-refresh, including nice animation on the top :large_orange_diamond:

#### Rating Stars
* [FloatRatingView ★350](glenyi/FloatRatingView) - Whole, half or floating point ratings control written in Swift :large_orange_diamond:
* [TTGEmojiRate ★203](zekunyan/TTGEmojiRate) - An emoji-liked rating view for iOS, implemented in Swift. :large_orange_diamond:
* [StarryStars ★128](peterprokop/StarryStars) - StarryStars is iOS GUI library for displaying and editing ratings :large_orange_diamond:
* [Cosmos ★605](marketplacer/Cosmos) - A star rating control for iOS / Swift :large_orange_diamond:
* [HCSStarRatingView ★922](hsousa/HCSStarRatingView) - Simple star rating view for iOS written in Objective-C
* [MBRateApp ★48](MatiBot/MBRateApp) - A groovy app rate stars screen for iOS written in Swift :large_orange_diamond:

#### ScrollView
* [ScrollingFollowView ★128](ktanaka117/ScrollingFollowView) - ScrollingFollowView is a simple view which follows UIScrollView scrolling.
* [UIScrollView-InfiniteScroll ★670](pronebird/UIScrollView-InfiniteScroll) - UIScrollView infinite scroll category.
* [GoAutoSlideView ★39](zjmdp/GoAutoSlideView) - GoAutoSlideView extends UIScrollView by featuring infinitely and automatically slide.
* [AppStoreStyleHorizontalScrollView ★528](terenceLuffy/AppStoreStyleHorizontalScrollView) - App store style horizontal scroll view. :large_orange_diamond:
* [PullToDismiss ★136](sgr-ksmt/PullToDismiss) - You can dismiss modal viewcontroller by pulling scrollview or navigationbar in Swift. :large_orange_diamond:
* [SpreadsheetView ★1528](kishikawakatsumi/SpreadsheetView) - Full configurable spreadsheet view user interfaces for iOS applications. With this framework, you can easily create complex layouts like schedule, gantt chart or timetable as if you are using Excel. :large_orange_diamond:

#### Slider
* [VolumeControl ★55](12Rockets/VolumeControl) - Custom volume control for iPhone featuring a well-designed round slider.
* [WESlider ★76 ⏳1Y](Ekhoo/WESlider) - Simple and light weight slider with chapter management
* [IntervalSlider ★48](shushutochako/IntervalSlider) - IntervalSlider is a slider library like ReutersTV app. written in pure swift. :large_orange_diamond:
* [RangeSlider ★131](warchimede/RangeSlider) - A simple range slider made in Swift :large_orange_diamond:
* [CircleSlider ★102](shushutochako/CircleSlider) - CircleSlider is a Circular slider library. written in pure Swift. :large_orange_diamond:
* [MARKRangeSlider ★121](vadymmarkov/MARKRangeSlider) - A custom reusable slider control with 2 thumbs (range slider).
* [ASValueTrackingSlider ★1677](alskipp/ASValueTrackingSlider) - A UISlider subclass that displays the slider value in a popup view
* [TTRangeSlider ★579](TomThorpe/TTRangeSlider) - A slider, similar in style to UISlider, but which allows you to pick a minimum and maximum range.
* [MMSegmentSlider ★23](MedvedevMax/MMSegmentSlider) - Customizable animated slider for iOS.
* [StepSlider ★96](spromicky/StepSlider) - StepSlider its custom implementation of slider such as UISlider for preset integer values.
* [JDSlider ★65](JellyDevelopment/JDSlider) - An iOS Slider written in Swift. :large_orange_diamond:
* [SnappingSlider ★517](rehatkathuria/SnappingSlider) - A beautiful slider control for iOS built purely upon Swift :large_orange_diamond:
* [MTCircularSlider ★12](EranBoudjnah/MTCircularSlider) - A feature-rich circular slider control. :large_orange_diamond:
* [VerticalSlider ★19](jonkykong/VerticalSlider) - VerticalSlider is a vertical implementation of the UISlider slider control. :large_orange_diamond:
* [CircularSlider ★139](taglia3/CircularSlider) - A powerful Circular Slider. It's written in Swift, it's 100% IBDesignable and all parameters are IBInspectable. :large_orange_diamond:
* [HGCircularSlider ★726](HamzaGhazouani/HGCircularSlider) - A custom reusable circular slider control for iOS application. :large_orange_diamond:
* [PivotSlider ★22](lab111/pivot-slider) - Slider that pivots :large_orange_diamond:
* [RangeSeekSlider ★99](WorldDownTown/RangeSeekSlider) - A customizable range slider for iOS. :large_orange_diamond:

#### Splash View
* [CBZSplashView ★1381](callumboddy/CBZSplashView) - Twitter style Splash Screen View. Grows to reveal the Initial view behind.
* [SKSplashView ★437](sachinkesiraju/SKSplashView) - Create custom animated splash views similar to the ones in the Twitter, Uber and Ping iOS app.
* [RevealingSplashView ★679](PiXeL16/RevealingSplashView) - A Splash view that animates and reveals its content, inspired by Twitter splash :large_orange_diamond:

#### Stepper
* [PFStepper ★24](PerfectFreeze/PFStepper) - May be the most elegant stepper you have ever had! :large_orange_diamond:
* [ValueStepper ★190](BalestraPatrick/ValueStepper) - A Stepper object that displays its value. :large_orange_diamond:
* [GMStepper ★526](gmertk/GMStepper) - A stepper with a sliding label in the middle. :large_orange_diamond:
* [barceloneta ★30](arn00s/barceloneta) - The right way to increment/decrement values with a simple gesture on iOS. :large_orange_diamond:
* [SnappingStepper ★313](yannickl/SnappingStepper) - An elegant alternative to the UIStepper written in Swift :large_orange_diamond:
* [SMNumberWheel] (https://github.com/SinaMoetakef/SMNumberWheel) - A custom control written in Swift, which is ideal for picking numbers very fast but yet very accurate using a rotating wheel :large_orange_diamond:

#### Switch
* [AnimatedSwitch ★144](alsedi/AnimatedSwitch) - UISwitch which paints over the parent view with the color in Swift. :large_orange_diamond:
* [ViralSwitch ★311](andreamazz/ViralSwitch) - A UISwitch that infects its superview with its tint color.
* [JTMaterialSwitch ★209 ⏳1Y](JunichiT/JTMaterialSwitch) - A customizable switch UI with ripple effect and bounce animations, inspired from Google's Material Design.
* [TKSwitcherCollection ★454](TBXark/TKSwitcherCollection) - An animate switch collection :large_orange_diamond:
* [SevenSwitch ★729](bvogelzang/SevenSwitch) - iOS7 style drop in replacement for UISwitch. :large_orange_diamond:
* [DGRunkeeperSwitch ★1775](gontovnik/DGRunkeeperSwitch) - Runkeeper design switch control (two part segment control) :large_orange_diamond:
* [PMZSwitch ★44 ⏳1Y](kovpas/PMZSwitch) - Yet another animated toggle :large_orange_diamond:
* [Switcher ★153](knn90/Switcher) - Swift - Custom UISwitcher with animation when change status :large_orange_diamond:
* [BetterSegmentedControl ★804](gmarm/BetterSegmentedControl) - An easy to use, customizable replacement for UISegmentedControl & UISwitch. :large_orange_diamond:
* [RAMPaperSwitch ★2188](Ramotion/paper-switch) - RAMPaperSwitch is a Swift module which paints over the parent view when the switch is turned on. :large_orange_diamond:
* [DynamicMaskSegmentSwitch ★287](KittenYang/DynamicMaskSegmentSwitch) - A segment switcher with dynamic text mask effect :large_orange_diamond:
* [LUNSegmentedControl ★168](Stormotion-Mobile/LUNSegmentedControl) - Customizable segmented control with interactive animation.
* [AKASegmentedControl ★403](alikaragoz/AKASegmentedControl) - :chocolate_bar: Fully customizable Segmented Control for iOS
* [AIFlatSwitch ★578](cocoatoucher/AIFlatSwitch) - A flat component alternative to UISwitch on iOS :large_orange_diamond:
* [Switch ★64](T-Pham/Switch) - An iOS switch control implemented in Swift with full Interface Builder support.🔶
* [TwicketSegmentedControl ★1053](twicketapp/TwicketSegmentedControl) - Custom UISegmentedControl replacement for iOS, written in Swift. :large_orange_diamond:
* [SJFluidSegmentedControl ★623](sasojadrovski/SJFluidSegmentedControl) - A segmented control with custom appearance and interactive animations. Written in Swift 3.0. :large_orange_diamond:
* [HMSegmentedControl ★2961](HeshamMegid/HMSegmentedControl) - A drop-in replacement for UISegmentedControl mimicking the style of the segmented control used in Google Currents and various other Google products.
* [PinterestSegment ★260](TBXark/PinterestSegment) - A Pinterest-like segment control with masking animation. :large_orange_diamond:
* [YUSegment ★86](afishhhhh/YUSegment) - A customizable segmented control for iOS. Supports both text and image.

#### Tab Bar
* [ESTabBarController ★95](ezescaruli/ESTabBarController) - A tab bar controller for iOS that allows highlighting buttons and setting custom actions to them.
* [GooeyTabbar ★643](KittenYang/GooeyTabbar) -A gooey effect tabbar :large_orange_diamond:
* [animated-tab-bar ★7255](Ramotion/animated-tab-bar) - RAMAnimatedTabBarController is a Swift module for adding animation to tabbar items. :large_orange_diamond:
* [FoldingTabBar.iOS ★3154](Yalantis/FoldingTabBar.iOS) - Folding Tab Bar and Tab Bar Controller
* [GGTabBar ★146](Goles/GGTabBar) - Another UITabBar & UITabBarController (iOS Tab Bar) replacement, but uses Auto Layout for arranging it's views hierarchy.
* [adaptive-tab-bar ★1707](Ramotion/adaptive-tab-bar) - AdaptiveController is a 'Progressive Reduction' Swift module for adding custom states to Native or Custom iOS UI elements :large_orange_diamond:
* [Pager ★190](lucoceano/Pager) - Easily create sliding tabs with Pager :large_orange_diamond:
* [XLPagerTabStrip ★3921](xmartlabs/XLPagerTabStrip) - Android PagerTabStrip for iOS. :large_orange_diamond:
* [TabPageViewController ★617](EndouMari/TabPageViewController) - Paging view controller and scroll tab view. 🔶
* [TabDrawer ★498 ⏳1Y](winslowdibona/TabDrawer) - Customizable TabBar UI element that allows you to run a block of code upon TabBarItem selection, written in Swift 🔶
* [SwipeViewController ★421](fortmarek/SwipeViewController) - SwipeViewController is a Swift modification of RKSwipeBetweenViewControllers - navigate between pages / ViewControllers :large_orange_diamond:
* [ColorMatchTabs ★884](Yalantis/ColorMatchTabs) - Interesting way to display tabs :large_orange_diamond:
* [BATabBarController ★597](antiguab/BATabBarController) - A TabBarController with a unique animation for selection
* [ScrollPager ★415](aryaxt/ScrollPager) - A scroll pager that displays a list of tabs (segments) and manages paging between given views :large_orange_diamond:
* [Segmentio ★1255](Yalantis/Segmentio) - Animated top/bottom segmented control written in Swift. :large_orange_diamond:
* [KYWheelTabController ★83](ykyouhei/KYWheelTabController) - KYWheelTabController is a subclass of UITabBarController.It displays the circular menu instead of UITabBar. :large_orange_diamond:
* [SuperBadges ★15](odedharth/SuperBadges) - Add emojis and colored dots as badges for your Tab Bar buttons 🔶
* [AZTabBarController ★67](Minitour/AZTabBarController) - A custom tab bar controller for iOS written in Swift 3.0 🔶
* [MiniTabBar ★49](D-32/MiniTabBar) - A clean simple alternative to the UITabBar 🔶
* [SwipeableTabBarController ★71](marcosgriselli/SwipeableTabBarController) - UITabBarController with swipe interaction between its tabs. 🔶
* [SMSwipeableTabView ★21](smahajan28/SMSwipeableTabView) - Swipeable Views with Tabs (Like Android SwipeView With Tabs Layout) 🔶
* [Tabman ★284](uias/Tabman) - A powerful paging view controller with indicator bar for iOS. 🔶

#### Table View / Collection View
* [MGSwipeTableCell ★5312](MortimerGoro/MGSwipeTableCell) - UITableViewCell subclass that allows to display swippable buttons with a variety of transitions.
* [ParallaxTableViewHeader ★1201 ⏳1Y](Vinodh-G/ParallaxTableViewHeader) - Parallax scrolling effect on UITableView header view when a tableView is scrolled.
* [YXTPageView ★57](hanton/YXTPageView) - A PageView, which supporting scrolling to transition between a UIView and a UITableView.
* [DZNEmptyDataSet ★8499](dzenbot/DZNEmptyDataSet) - A drop-in UITableView/UICollectionView superclass category for showing empty datasets whenever the view has no content to display.
* [ConfigurableTableViewController ★236](fastred/ConfigurableTableViewController) - Typed, yet Flexible Table View Controller http://holko.pl/2016/01/05/typed-table-view-controller/ :large_orange_diamond:
* [CSStickyHeaderFlowLayout ★4622](CSStickyHeaderFlowLayout/CSStickyHeaderFlowLayout) - UICollectionView replacement of UITableView. Do even more like Parallax Header, Sticky Section Header. :large_orange_diamond:
* [folding-cell ★5772](Ramotion/folding-cell) - FoldingCell is an expanding content cell inspired by folding paper material :large_orange_diamond:
* [Lightning-Table ★20 ⏳2Y](electrickangaroo/Lightning-Table) - A declarative api for working with UITableView.
* [Static ★912](venmo/Static) - Simple static table views for iOS in Swift. :large_orange_diamond:
* [GSKStretchyHeaderView ★880](gskbyte/GSKStretchyHeaderView) - Configurable yet easy to use stretchy header view for UITableView and UICollectionView.
* [MEVFloatingButton ★269](manuelescrig/MEVFloatingButton) - An iOS drop-in UITableView, UICollectionView and UIScrollView superclass category for showing a customizable floating button on top of it.
* [AMWaveTransition ★2291](andreamazz/AMWaveTransition) - Custom transition between viewcontrollers holding tableviews.
* [Dwifft ★1200](jflinter/Dwifft) - Swift Diff :large_orange_diamond:
* [CollapsableTable ★187](rob-nash/CollapsableTable) - A kit for building tableviews with a collapsable animation, for each section.
* [AEAccordion ★147 ⏳1Y](tadija/AEAccordion) - UITableViewController with accordion effect (expand / collapse cells). :large_orange_diamond:
* [SWTableViewCell ★6787](CEWendel/SWTableViewCell) - An easy-to-use UITableViewCell subclass that implements a swippable content view which exposes utility buttons (similar to iOS 7 Mail Application)
* [ZYThumbnailTableView ★869](liuzhiyi1992/ZYThumbnailTableView) - a TableView have thumbnail cell only, and you can use gesture let it expands other expansionView, all diy :large_orange_diamond:
* [BWSwipeRevealCell ★44](bitwit/BWSwipeRevealCell) - A Swift library for swipeable table cells :large_orange_diamond:
* [preview-transition ★1467](Ramotion/preview-transition) - PreviewTransition is a simple preview gallery controller :large_orange_diamond:
* [QuickTableViewController ★72](bcylin/QuickTableViewController) - A simple way to create a UITableView for settings in Swift. :large_orange_diamond:
* [TableKit ★211](maxsokolov/TableKit) - Type-safe declarative table views with Swift :large_orange_diamond:
* [Preheat ★558](kean/Preheat) - Automates prefetching of content in UITableView and UICollectionView :large_orange_diamond:
* [VBPiledView ★114](v-braun/VBPiledView) - Simple and beautiful stacked UIView to use as a replacement for an UITableView, UIImageView or as a menu :large_orange_diamond:
* [DisplaySwitcher ★1462](Yalantis/DisplaySwitcher) - Custom transition between two collection view layouts :large_orange_diamond:
* [CHTCollectionViewWaterfallLayout ★3271](chiahsien/CHTCollectionViewWaterfallLayout) - The waterfall (i.e., Pinterest-like) layout for UICollectionView.
* [FMMosaicLayout ★542](fmitech/FMMosaicLayout) - A drop-in mosaic collection view layout with a focus on simple customizations.
* [TRMosaicLayout ★129](vinnyoodles/TRMosaicLayout) - A mosaic collection view layout inspired by Lightbox's Algorithm, written in Swift 🔶
* [Reusable ★1040](AliSoftware/Reusable) - A Swift mixin for UITableViewCells and UICollectionViewCells :large_orange_diamond:
* [VTMagic ★1345](tianzhuo112/VTMagic) - VTMagic is a page container library for iOS.
* [MCSwipeTableViewCell ★2975](alikaragoz/MCSwipeTableViewCell) - :point_up_2: Convenient UITableViewCell subclass that implements a swippable content to trigger actions (similar to the Mailbox app).
* [Sapporo ★226](nghialv/Sapporo) - Cellmodel-driven collectionview manager :large_orange_diamond:
* [MYTableViewIndex ★273](mindz-eye/MYTableViewIndex) - A pixel perfect replacement for UITableView section index, written in Swift :large_orange_diamond:
* [RAReorderableLayout ★731](ra1028/RAReorderableLayout) - A UICollectionView layout which can move item with drag and drop.
* [PageFeedControl ★27](rob-nash/PageFeedControl) - Add paging to your table views with a cool animation.
* [StickyCollectionView-Swift ★167](matbeich/StickyCollectionView-Swift) - UICollectionView layout for presenting of the overlapping cells. :large_orange_diamond:
* [ios-dragable-table-cells ★33](palmin/ios-dragable-table-cells) - Support for drag-n-drop of UITableViewCells in a navigation hierarchy of view controllers. You drag cells by tapping and holding them.
* [TLLayoutTransitioning ★321](SwiftKickMobile/TLLayoutTransitioning) - Enhanced transitioning between UICollectionView layouts in iOS.
* [Bohr ★1168](DavdRoman/Bohr) - Bohr allows you to set up a settings screen for your app with three principles in mind: ease, customization and extensibility.
* [SwiftReorder ★30](adamshin/SwiftReorder) - Add drag-and-drop reordering to any table view with just a few lines of code. Robust, lightweight, and completely customizable. :large_orange_diamond:[e]
* [TLIndexPathTools ★330](SwiftKickMobile/TLIndexPathTools) - TLIndexPathTools is a small set of classes that can greatly simplify your table and collection views.
* [HoverConversion ★159](marty-suzuki/HoverConversion) - HoverConversion realized vertical paging with UITableView. UIViewController will be paging when reaching top or bottom of UITableView contentOffset. :large_orange_diamond:
* [TableViewDragger ★295](KyoheiG3/TableViewDragger) - A cells of UITableView can be rearranged by drag and drop. :large_orange_diamond:
* [IGListKit ★5541](Instagram/IGListKit) - A data-driven UICollectionView framework for building fast and flexible lists.
* [MMCardView ★379](MillmanY/MMCardView) - Custom CollectionView like Wallet App :large_orange_diamond:
* [FlexibleTableViewController ★7](dimpiax/FlexibleTableViewController) - Swift library of generic table view controller with external data processing of functionality, like determine cell's reuseIdentifier related to indexPath, configuration of requested cell for display and cell selection handler
* [FlexibleCollectionViewController ★1](dimpiax/FlexibleCollectionViewController) - Swift library of generic collection view controller with external data processing of functionality, like determine cell's reuseIdentifier related to indexPath, configuration of requested cell for display and cell selection handler etc
* [CascadingTableDelegate ★742](edopelawi/CascadingTableDelegate) - A no-nonsense way to write cleaner UITableViewDelegate and UITableViewDataSource in Swift.:large_orange_diamond:
* [TimelineTableViewCell ★731](kf99916/TimelineTableViewCell) - Simple timeline view implemented by UITableViewCell written in Swift 3.0.:large_orange_diamond:
* [RHPreviewCell ★320](robertherdzik/RHPreviewCell) - I envied so much Spotify iOS app this great playlist preview cell. Now you can give your users ability to quick check "what content is hidden under your UITableViewCell". :large_orange_diamond:
* [ThreeLevelAccordian ★19](amratab/ThreeLevelAccordian) - This is a customisable three level accordian with options for adding images and accessories images. :large_orange_diamond:
* [TORoundedTableView ★42](TimOliver/TORoundedTableView) - A subclass of UITableView that styles it like Settings.app on iPad
* [ASCollectionView ★102](abdullahselek/ASCollectionView) - A Swift collection view inspired by Airbnb. :large_orange_diamond:
* [TableFlip ★310](mergesort/TableFlip) - A simpler way to do cool UITableView animations! (╯°□°）╯︵ ┻━┻ :large_orange_diamond:
* [DTTableViewManager ★294](DenHeadless/DTTableViewManager) - Protocol-oriented UITableView management, powered by generics and associated types. :large_orange_diamond:
* [GLTableCollectionView ★382](giulio92/GLTableCollectionView) - Netflix and App Store like UITableView with UICollectionView :large_orange_diamond:
* [SwipeCellKit ★2034](SwipeCellKit/SwipeCellKit) - Swipeable UITableViewCell based on the stock Mail.app, implemented in Swift. :large_orange_diamond:
* [EditDistance ★39](kazuhiro4949/EditDistance) - Incremental update tool for UITableView and UICollectionView :large_orange_diamond:
* [CenteredCollectionView ★53](BenEmdon/CenteredCollectionView) - A lightweight CollectionView that _'pages'_ and _centers_ it's cells 🎡 written in Swift. :large_orange_diamond:
* [YBSlantedCollectionViewLayout ★110](yacir/YBSlantedCollectionViewLayout) - UICollectionViewLayout with slanted content.
* [ReverseExtension ★1058](marty-suzuki/ReverseExtension) - A UITableView extension that enables cell insertion from the bottom of a table view.
* [YNExpandableCell ★239](younatics/YNExpandableCell) - Awesome expandable, collapsible tableview cell for iOS written in Swift 3 🔶
* [SquareMosaicLayout ★30](iwheelbuy/SquareMosaicLayout) - An extandable mosaic UICollectionViewLayout with a focus on extremely flexible customizations 🔶
* [SwiftSpreadSheet ★379](stuffrabbit/SwiftSpreadsheet) - Spreadsheet CollectionViewLayout in Swift. Fully customizable. 🔶
* [GenericDataSource ★32](GenericDataSource/GenericDataSource) - A generic small reusable components for data source implementation for UITableView/UICollectionView in Swift. 🔶
* [BouncyLayout ★2304](roberthein/BouncyLayout) - BouncyLayout is a collection view layout that makes your cells bounce. 🔶
* [Savory ★1](Nandiin/Savory) - A swift accordion view implementation. 🔶

#### Tag
* [PARTagPicker ★243](paulrolfe/PARTagPicker) - This pod provides a view controller for choosing and creating tags in the style of wordpress or tumblr.
* [AMTagListView ★680](andreamazz/AMTagListView) - UIScrollView subclass that allows to add a list of highly customizable tags.
* [TagCellLayout ★92](riteshhgupta/TagCellLayout) - UICollectionView layout for Tags with Left, Center & Right alignments. :large_orange_diamond:
* [TTGTagCollectionView ★513](zekunyan/TTGTagCollectionView) - Show simple text tags or custom tag views in a vertical scrollable view.
* [TagListView ★982](ElaWorkshop/TagListView) - Simple and highly customizable iOS tag list view, in Swift. :large_orange_diamond:
* [RKTagsView ★330](kuler90/RKTagsView) - Highly customizable iOS tags view (like NSTokenField). Supports editing, multiple selection, Auto Layout and much more.
* [WSTagsField ★575](whitesmith/WSTagsField) - An iOS text field that represents different Tags :large_orange_diamond:
* [AKMaskField ★173](artemkrachulov/AKMaskField) - AKMaskField is UITextField subclass which allows enter data in the fixed quantity and in the certain format. :large_orange_diamond:
* [YNSearch ★524](younatics/YNSearch) - Awesome fully customizable search view like Pinterest written in Swift 3 🔶

#### TextField & TextView
* [JVFloatLabeledTextField ★6271](jverdi/JVFloatLabeledTextField) - UITextField subclass with floating labels.
* [ARAutocompleteTextView ★258](alexruperez/ARAutocompleteTextView) - subclass of UITextView that automatically displays text suggestions in real-time. Perfect for email Textviews.
* [IQDropDownTextField ★215](hackiftekhar/IQDropDownTextField) - TextField with DropDown support using UIPickerView
* [UITextField-Shake](https://github.com/andreamazz/UITextField-Shake) - UITextField category that adds shake animation. [Also with Swift version ★12](King-Wizard/UITextField-Shake-Swift) :large_orange_diamond:
* [HTYTextField ★211](hanton/HTYTextField) - A UITextField with bouncy placeholder. :large_orange_diamond:
* [MVAutocompletePlaceSearchTextField ★64 ⏳1Y](TheMrugraj/MVAutocompletePlaceSearchTextField) - A drop-in Autocompletion control for Place Search like Google Places, Uber, etc.
* [AutocompleteField ★641](filipstefansson/AutocompleteField) - Add word completion to your UITextFields. :large_orange_diamond:
* [RSKGrowingTextView ★466](ruslanskorb/RSKGrowingTextView) - A light-weight UITextView subclass that automatically grows and shrinks. :large_orange_diamond:
* [RSKPlaceholderTextView ★41](ruslanskorb/RSKPlaceholderTextView) - A light-weight UITextView subclass that adds support for placeholder. :large_orange_diamond:
* [StatefulViewController ★1583](aschuch/StatefulViewController) - Placeholder views based on content, loading, error or empty states :large_orange_diamond:
* [MBAutoGrowingTextView ★115 ⏳1Y](MatejBalantic/MBAutoGrowingTextView) - An auto-layout base UITextView subclass which automatically grows with user input and can be constrained by maximal and minimal height - all without a single line of code
* [TextFieldEffects ★3934](raulriera/TextFieldEffects) - Custom UITextFields effects inspired by Codrops, built using Swift :large_orange_diamond:
* [Reel Search ★1751](Ramotion/reel-search) - RAMReel is a controller that allows you to choose options from a list. :large_orange_diamond:
* [MLPAutoCompleteTextField ★1103](EddyBorja/MLPAutoCompleteTextField) - a subclass of UITextField that behaves like a typical UITextField with one notable exception: it manages a drop down table of autocomplete suggestions that update as the user types.
* [SkyFloatingLabelTextField ★1837](Skyscanner/SkyFloatingLabelTextField) - A beautiful and flexible text field control implementation of "Float Label Pattern". Written in Swift.:large_orange_diamond:
* [VMaskTextField ★344](viniciusmo/VMaskTextField) - VMaskTextField is a library which create an input mask for iOS.
* [TJTextField ★31](tejas-ardeshna/TJTextField) - UITextField with underline and left image :large_orange_diamond:
* [NextGrowingTextView ★778](muukii/NextGrowingTextView) - The next in the generations of 'growing textviews' optimized for iOS 7 and above.
* [RPFloatingPlaceholders ★1087](iwasrobbed/RPFloatingPlaceholders) - UITextField and UITextView subclasses with placeholders that change into floating labels when the fields are populated with text.
* [CurrencyTextField ★17](richa008/CurrencyTextField) - UITextField that automatically formats text to display in the currency format. :large_orange_diamond:
* [UITextField-Navigation ★319](T-Pham/UITextField-Navigation) - UITextField-Navigation adds next, previous and done buttons to the keyboard for your UITextFields.🔶[e]
* [AutoCompleteTextField ★17](nferocious76/AutoCompleteTextField) - Auto complete with suggestion textfield :large_orange_diamond:
* [EmojiTextView ★339](fastred/EmojiTextView) - Tap to swap out words with emojis. Inspired by Messages.app on iOS 10. :large_orange_diamond:
* [PLCurrencyTextField ★80](nonameplum/PLCurrencyTextField) - UITextField that support currency in the right way. :large_orange_diamond:
* [PasswordTextField ★119](PiXeL16/PasswordTextField) - A custom TextField with a switchable icon which shows or hides the password and enforce good password policies :large_orange_diamond:
* [AnimatedTextInput ★430](jobandtalent/AnimatedTextInput) - Animated UITextField and UITextView replacement for iOS :large_orange_diamond:
* [KMPlaceholderTextView ★419](MoZhouqi/KMPlaceholderTextView) - A UITextView subclass that adds support for multiline placeholder written in Swift. :large_orange_diamond:
* [NxEnabled ★19](Otbivnoe/NxEnabled) - Library which allows you binding `enabled` property of button with textable elements (TextView, TextField) :large_orange_diamond:
* [AwesomeTextField ★77](aleksandrshoshiashvili/AwesomeTextFieldSwift) - Awesome TextField is a nice and simple library for iOS. It's highly customisable and easy-to-use tool. Works perfectly for any registration or login forms in your app. :large_orange_diamond:
* [ModernSearchBar ★41](PhilippeBoisney/ModernSearchBar) - The famous iOS search bar with auto completion feature implemented. :large_orange_diamond:
* [SelectableTextView ★527](jhurray/SelectableTextView) - A text view that supports selection and expansion :large_orange_diamond:
* [CBPinEntryView ★16](Fawxy/CBPinEntryView) - A customisable view written in Swift 3.0 for any numerical pin or code entry. :large_orange_diamond:
* [GrowingTextView ★98](KennethTsang/GrowingTextView) - An UITextView in Swift3 and Swift2.3. Support auto growing, placeholder and length limit. :large_orange_diamond:
* [DTTextField ★50](iDhaval/DTTextField) - DTTextField is a custom textfield with floating placeholder and error label in Swift3.0.🔶
* [TextFieldCounter ★273](serralvo/TextFieldCounter) - UITextField character counter with lovable UX. 🔶
* [RSFloatInputView ★35](roytornado/RSFloatInputView) - A Float Input View with smooth animation and supporting icon and seperator written with Swift. 🔶

#### Web View
* [Otafuku ★43](tasanobu/Otafuku) - Otafuku provides utility classes to use WKWebView in Swift. :large_orange_diamond:
* [SwiftWebVC ★137](meismyles/SwiftWebVC) - A drop-in inline browser for your Swift iOS app. :large_orange_diamond:
* [SVWebViewController ★2495](TransitApp/SVWebViewController) - A drop-in inline browser for your iOS app.
* [PTPopupWebView ★52](pjocprac/PTPopupWebView) - PTPopupWebView is a simple and useful WebView for iOS, which can be popup and has many of the customized item. :large_orange_diamond:

## URL Scheme
* [WAAppRouting ★545 ⏳1Y](Wasappli/WAAppRouting) - iOS routing done right. Handles both URL recognition and controller displaying with parsed parameters. All in one line, controller stack preserved automatically!
* [DeepLinkKit ★2869](button/DeepLinkKit) - A splendid route-matching, block-based way to handle your deep links.
* [IntentKit ★1785](intentkit/IntentKit) - An easier way to handle third-party URL schemes in iOS apps.
* [JLRoutes ★3528](joeldev/JLRoutes) - URL routing library for iOS with a simple block-based API.
* [IKRouter ★92 ⏳1Y](IanKeen/IKRouter) - URLScheme router than supports auto creation of UIViewControllers for associated url parameters to allow creation of navigation stacks :large_orange_diamond:
* [Compass ★495](hyperoslo/Compass) - :earth_africa: Compass helps you setup a central navigation system for your application :large_orange_diamond:
* [Appz ★810](SwiftKitz/Appz) - Easily launch and deeplink into external applications, falling back to web if not installed. :large_orange_diamond:
* [URLNavigator ★1135](devxoul/URLNavigator) - ⛵️ Elegant URL Routing for Swift :large_orange_diamond:

## Utility
 * [Underscore.m ★1509 ⏳1Y](robb/Underscore.m) - A DSL for Data Manipulation.
 * [XExtensionItem ★79 ⏳1Y](tumblr/XExtensionItem) - Easier sharing of structured data between iOS applications and share extensions.
 * [ReflectableEnum ★327](fastred/ReflectableEnum) - Reflection for enumerations in Objective-C.
 * [ObjectiveSugar ★2188](supermarin/ObjectiveSugar) - ObjectiveC additions for humans. Ruby style.
 * [GroundControl ★1943 ⏳1Y](mattt/GroundControl) - Remote configuration for iOS.
 * [OpinionatedC ★44 ⏳1Y](leoschweizer/OpinionatedC) - Because Objective-C should have inherited more from Smalltalk.
 * [SwiftRandom ★445](thellimist/SwiftRandom) - Generator for random data. :large_orange_diamond:
 * [RandomKit ★1053](nvzqz/RandomKit) - Random data generation in Swift. :large_orange_diamond:
 * [YOLOKit ★615](mxcl/YOLOKit) - Getting square objects down round holes.
 * [EZSwiftExtensions ★2069](goktugyil/EZSwiftExtensions) - :smirk: How Swift standard types and classes were supposed to work. :large_orange_diamond:[e]
 * [Pantry ★816](nickoneill/Pantry) - The missing light persistence layer for Swift :large_orange_diamond:
 * [SwiftParsec ★109](davedufresne/SwiftParsec) - A parser combinator library written in the Swift programming language. :large_orange_diamond:
 * [OrderedSet ★97](Weebly/OrderedSet) - A Swift collection of unique, ordered objects :large_orange_diamond:
 * [Datez ★191](SwiftKitz/Datez) - Swift library for dealing with `NSDate`, `NSCalendar`, and `NSDateComponents`. :large_orange_diamond:
 * [BFKit ★724](FabrizioBrancati/BFKit) - An Objective-C collection of useful classes to develop Apps faster.
 * [BFKit-Swift ★572](FabrizioBrancati/BFKit-Swift) - A Swift collection of useful classes to develop Apps faster. :large_orange_diamond:
 * [Scale ★299](onmyway133/scale) - Unit converter in Swift (available via CocoaPods) :large_orange_diamond:
 * [Standard Template Protocols ★380 ⏳1Y](cconeil/Standard-Template-Protocols) - Protocols for your every day iOS needs :large_orange_diamond:
 * [TimeLord ★5](JonFir/TimeLord) - Easy DateTime (NSDate) management in Swift :large_orange_diamond:
 * [AppVersionMonitor ★207](eure/AppVersionMonitor) - Monitor iOS app version easily.
 * [Sugar ★824](hyperoslo/Sugar) - Something sweet that goes great with your Cocoa. :large_orange_diamond:[e]
 * [Then ★1650](devxoul/Then) - ✨ Super sweet syntactic sugar for Swift initializers. :large_orange_diamond:[e]
 * [Kvitto ★183](Cocoanetics/Kvitto) - App Store Receipt Validation :large_orange_diamond:
 * [Notificationz ★51](SwiftKitz/Notificationz) - Helping you own NSNotificationCenter in Swift :large_orange_diamond:
 * [SwiftFoundation ★580](PureSwift/SwiftFoundation) - Cross-Platform, Protocol-Oriented Programming base library to complement the Swift Standard Library. (Pure Swift, Supports Linux) :large_orange_diamond:[e]
 * [libextobjc ★3538](jspahrsummers/libextobjc) - A Cocoa library to extend the Objective-C programming language.
 * [VersionTrackerSwift ★49](tbaranes/VersionTrackerSwift) - Track which versions of your app a user has previously installed. :large_orange_diamond:
 * [DeviceGuru ★183](InderKumarRathore/DeviceGuru) - DeviceGuru is a simple lib (Swift) to know the exact type of the device, e.g. iPhone 6 or iPhone 6s. :large_orange_diamond:
 * [swift-algorithm-club ★12655](raywenderlich/swift-algorithm-club) - Algorithms and data structures in Swift, with explanations! :large_orange_diamond:
 * [AEAppVersion ★5](tadija/AEAppVersion) - Simple and Lightweight App Version Tracking for iOS written in Swift :large_orange_diamond:
 * [BlocksKit ★6133](zwaldowski/BlocksKit) - The Objective-C block utilities you always wish you had.
 * [SwiftyUtils ★127](tbaranes/swiftyutils) - All the reusable code that we need in each project. :large_orange_diamond:[e]
 * [RateLimit ★836](soffes/RateLimit) - Simple utility for only executing code every so often. :large_orange_diamond:
 * [Outlets ★127](phatblat/Outlets) - Utility functions for validating IBOutlet and IBAction connections :large_orange_diamond:
 * [EasyAbout ★41](JARMourato/EasyAbout) - A way to easily add Cocoapod licenses and App Version to your iOS App using the Settings Bundle
 * [Validated ★572](Ben-G/Validated) - A Swift μ-Library for Somewhat Dependent Types :large_orange_diamond:
 * [Cent ★148](ankurp/Cent) - Extensions for Swift Standard Types and Classes :large_orange_diamond:
 * [AssistantKit ★394](anatoliyv/AssistantKit) - Easy way to detect iOS device properties, OS versions and work with screen sizes. Powered by Swift. :large_orange_diamond:
 * [SwiftLinkPreview ★665](LeonardoCardoso/SwiftLinkPreview) - It makes a preview from an url, grabbing all the information such as title, relevant texts and images. 🔶
 * [BundleInfos ★0](singcodes/BundleInfos) - Simple getter for Bundle informations. like short version from bundle. 🔶
 * [YAML.framework ★177](mirek/YAML.framework) - Proper YAML support for Objective-C based on `LibYAML`.
 * [ReadabilityKit ★576](exyte/ReadabilityKit) - Metadata extractor for news, articles and full-texts in Swift. 🔶
 * [MissionControl-iOS ★99](appculture/MissionControl-iOS) - Super powerful remote config utility written in Swift (iOS, watchOS, tvOS, OSX) :large_orange_diamond:
 * [SwiftTweaks ★925](Khan/SwiftTweaks) - Tweak your iOS app without recompiling! :large_orange_diamond:
 * [UnsupportedOSVersionAlert ★9](caloon/UnsupportedOSVersionAlert) - Alerts users with a popup if they use an app with an unsupported version of iOS (e.g. iOS betas) :large_orange_diamond:
 * [SwiftRouter ★128](skyline75489/SwiftRouter) - A URL Router for iOS, written in Swift 2.2 :large_orange_diamond:
 * [SwiftSortUtils ★57](dsmatter/SwiftSortUtils) - This library takes a shot at making sorting in Swift more pleasant. It also allows you to reuse your old NSSortDescriptor instances in Swift. :large_orange_diamond:
 * [Retry ★419](icanzilb/Retry) - Haven't you wished for `try` to sometimes try a little harder? Meet `retry` . :large_orange_diamond:
 * [ObjectiveKit ★635](marmelroy/ObjectiveKit) - Swift-friendly API for Objective C runtime functions. :large_orange_diamond:
 * [MoyaSugar ★49](devxoul/MoyaSugar) -  Syntactic sugar for Moya. :large_orange_diamond:
 * [SwifterSwift ★3376](SwifterSwift/SwifterSwift) -  A handy collection of more than 400 native Swift 3 extensions to boost your productivity. :large_orange_diamond:
 * [Eject ★501](Raizlabs/Eject) - An eject button for Interface Builder to generate swift code. :large_orange_diamond:
 * [ContactsWrapper ★17](abdullahselek/ContactsWrapper) - Easy to use wrapper for both contacts and contacts group with Objective-C.
 * [XestiMonitors ★236](eBardX/XestiMonitors) - An extensible monitoring framework written in Swift :large_orange_diamond:
 * [OpenSourceController ★25](terflogag/OpenSourceController) - The simplest way to display the libraries licences used in your application. :large_orange_diamond:
 * [App-Update-Tracker ★22 ⏳1Y](Stunner/App-Update-Tracker) - Easily detect and run code upon app installation or update.
 * [ExtensionalSwift ★1](4taras4/SwiftExtension) - Useful swift extensions in one place 🔶[e]
 * [InAppSettingsKit ★2762](futuretap/InAppSettingsKit) - This iOS framework allows settings to be in-app in addition to or instead of being in the Settings app.

## VR
* [VR Toolkit iOS ★72 ⏳1Y](Aralekk/VR_Toolkit_iOS) - A sample project that provides the basics to create an interactive VR experience on iOS :large_orange_diamond:
* [360 VR Player ★1601](hanton/HTY360Player) - A open source, ad-free, native and universal 360 degree panorama video player for iOS.
* [simple360player ★118 ⏳1Y](Aralekk/simple360player_iOS) - Free & ad-free 360 VR Video Player. Flat or Stereoscopic. In Swift 2. :large_orange_diamond:

## Walkthrough / Intro / Tutorial
* [Onboard ★5289](mamaral/Onboard) - Easily create a beautiful and engaging onboarding experience with only a few lines of code.
* [EAIntroView ★3369](ealeksandrov/EAIntroView) - Highly customizable drop-in solution for introduction views.
* [MYBlurIntroductionView ★1515](MatthewYork/MYBlurIntroductionView) - A super-charged version of MYIntroductionView for building custom app introductions and tutorials.
* [BWWalkthrough ★2390](ariok/BWWalkthrough) - A class to build custom walkthroughs for your iOS App. :large_orange_diamond:
* [GHWalkThrough ★736](GnosisHub/GHWalkThrough) - A UICollectionView backed drop-in component for introduction views.
* [ICETutorial ★822](icepat/ICETutorial) - A nice tutorial like the one introduced in the Path 3.X App.
* [JazzHands ★6175](IFTTT/JazzHands) - Jazz Hands is a simple keyframe-based animation framework for UIKit. Animations can be controlled via gestures, scroll views, KVO, or ReactiveCocoa.
* [RazzleDazzle ★2703](IFTTT/RazzleDazzle) - A simple keyframe-based animation framework for iOS, written in Swift. Perfect for scrolling app intros. :large_orange_diamond:
* [Instructions ★2717](ephread/Instructions) - Easily add customizable coach marks into you iOS project. :large_orange_diamond:
* [SwiftyWalkthrough ★189](ruipfcosta/SwiftyWalkthrough) - The easiest way to create a great walkthrough experience in your apps, powered by Swift. :large_orange_diamond:
* [Gecco ★1490](yukiasai/Gecco) - Spotlight view for iOS. :large_orange_diamond:
* [VideoSplashKit ★1060](mojilala/VideoSplashKit) - VideoSplashKit - UIViewController library for creating easy intro pages with background videos :large_orange_diamond:
* [Presentation ★2112](hyperoslo/Presentation) - Presentation helps you to make tutorials, release notes and animated pages. :large_orange_diamond:
* [AMPopTip ★1785](andreamazz/AMPopTip) - An animated popover that pops out a given frame, great for subtle UI tips and onboarding.
* [AlertOnboarding ★242](PhilippeBoisney/AlertOnboarding) - A simple and handsome AlertView for onboard your users in your amazing world. :large_orange_diamond:
* [EasyTipView ★1514](teodorpatras/EasyTipView) - Fully customisable tooltip view in Swift. :large_orange_diamond:
* [paper-onboarding ★1814](Ramotion/paper-onboarding) - PaperOnboarding is a material design slider :large_orange_diamond:
* [InfoView ★30](anatoliyv/InfoView) - Swift based simple information view with pointed arrow. :large_orange_diamond:
* [Intro ★23](nbolatov/Intro) - An iOS framework to easily create simple animated walkthrough, written in Swift. :large_orange_diamond:
* [AwesomeSpotlightView ★16](aleksandrshoshiashvili/AwesomeSpotlightView) - Tool to create awesome tutorials or educate user to use application. Or just highlight something on screen. Written in Swift. :large_orange_diamond:
* [SwiftyOnboard ★503](juanpablofernandez/SwiftyOnboard) - A simple way to add onboarding to your project. :large_orange_diamond:
* [WVWalkthroughView ★18](praagyajoshi/WVWalkthroughView) - Utility to easily create walkthroughs to help with user onboarding.
* [SwiftyGuideOverlay ★5](SaeidBsn/SwiftyGuideOverlay) - Easy and quick way to show intro / instructions over app UI without any additional images in real-time!. 🔶

## WebSocket
* [SocketRocket ★6815](facebook/SocketRocket) - A conforming Objective-C WebSocket client library.
* [socket.io-client-swift ★2316](socketio/socket.io-client-swift) - Socket.IO-client for iOS/OS X. :large_orange_diamond:
* [SwiftWebSocket ★787](tidwall/SwiftWebSocket) - High performance WebSocket client library for Swift, iOS and OSX. :large_orange_diamond:
* [Starscream ★2792](daltoniam/Starscream) - Websockets in swift for iOS and OSX :large_orange_diamond:
* [SwiftSocket ★545](swiftsocket/SwiftSocket) - simple socket library for apple swift lang. :large_orange_diamond:
* [Socks ★431](vapor/sockets) - Pure-Swift Sockets: TCP, UDP; Client, Server; Linux, OS X :large_orange_diamond:
* [SwifterSockets ★55](Balancingrock/SwifterSockets) - A collection of socket utilities in Swift for OS-X and iOS :large_orange_diamond:
* [Swift-ActionCableClient ★87](danielrhodes/Swift-ActionCableClient) - ActionCable is a new WebSocket server being released with Rails 5 which makes it easy to add real-time features to your app. :large_orange_diamond:

#### GCD
 * [GCDKit ★277](JohnEstropia/GCDKit) - Grand Central Dispatch simplified with Swift. :large_orange_diamond:
 * [Async ★3989](duemunk/Async) - Syntactic sugar in Swift for asynchronous dispatches in Grand Central Dispatch :large_orange_diamond:
 * [SwiftSafe ★154](nodes-ios/SwiftSafe) - Thread synchronization made easy :large_orange_diamond:
 * [YYDispatchQueuePool ★251](ibireme/YYDispatchQueuePool) - iOS utility class to manage global dispatch queue.
 * [AlecrimAsyncKit ★68](Alecrim/AlecrimAsyncKit) - Bringing async and await to Swift world with some flavouring. :large_orange_diamond:
 * [GrandSugarDispatch ★31](jessesquires/GrandSugarDispatch) - Syntactic sugar for Grand Central Dispatch (GCD) :large_orange_diamond:
 * [Threader ★41](mitchtreece/Threader) - Pretty GCD calls and easier code execution.
 * [Dispatch ★168](Swiftification/Dispatch) - Just a tiny library to make using GCD easier and intuitive :large_orange_diamond:
 * [GCDTimer ★161](hemantasapkota/GCDTimer) - Well tested Grand Central Dispatch (GCD) Timer in Swift. :large_orange_diamond:
 * [Chronos-Swift ★246](comyar/Chronos-Swift) - :hourglass: Grand Central Dispatch Utilities :large_orange_diamond:
 * [Me ★194](pascalbros/Me) - A super slim solution to the nested asynchronous computations. :large_orange_diamond:
 * [SwiftyTask ★10](CR-Creations/SwiftyTask) - An extreme queuing system with high performance for managing all task in app with closure. :large_orange_diamond:

# Project setup
* [crafter ★534](krzysztofzablocki/crafter) - CLI that allows you to configure iOS project's template using custom DSL syntax, simple to use and quite powerful.
* [liftoff ★1538](liftoffcli/liftoff) - Another CLI for creating iOS projects.
* [amaro ★370 ⏳1Y](crushlovely/Amaro) - iOS Boilerplate full of delights.
* [chairs ★235 ⏳2Y](orta/chairs) - Swap around your iOS Simulator Documents
* [SwiftPlate ★1087](JohnSundell/SwiftPlate) - Easily generate cross platform Swift framework projects from the command line. :large_orange_diamond:

# Dependency / Package Manager
* [CocoaPods](https://cocoapods.org/) - CocoaPods is the dependency manager for Objective-C projects. It has thousands of libraries and can help you scale your projects elegantly.
* [Xcode Maven](http://sap-production.github.io/xcode-maven-plugin/site/) - The Xcode Maven Plugin can be used in order to run Xcode builds embedded in a Maven lifecycle.
* [Carthage ★9468](Carthage/Carthage) - A simple, decentralized dependency manager for Cocoa. :large_orange_diamond:
* [SWM (Swift Modules) ★55 ⏳2Y](jankuca/swm) - A package/dependency manager for Swift projects similar to npm (node.js package manager) or bower (browser package manager from Twitter). Does not require the use of Xcode. :large_orange_diamond:
* [Alcatraz](http://alcatraz.io/) - The package manager for Xcode.
* [CocoaSeeds ★331](devxoul/CocoaSeeds) - Git Submodule Alternative for Cocoa.
* [Podage ★8 ⏳1Y](jensmeder/Podage) - A simple tool to bundle any Cocoapod and its dependencies into frameworks.
* [swift-package-manager ★5533](apple/swift-package-manager) - The Package Manager for the Swift Programming Language :large_orange_diamond:
* [punic ★233](schwa/punic) - Clean room reimplementation of Carthage tool

# Tools
* [Shark ★278](kaandedeoglu/Shark) - Swift Script that transforms the .xcassets folder into a type safe enum. :large_orange_diamond:
* [SBConstants ★306](paulsamuels/SBConstants) - Generate a constants file by grabbing identifiers from storyboards in a project.
* [R.swift ★3718](mac-cain13/R.swift) - Tool to get strong typed, autocompleted resources like images, cells and segues in your Swift project. :large_orange_diamond:
* [SwiftGen ★3576](SwiftGen/SwiftGen) - A collection of Swift tools to generate Swift code (enums for your assets, storyboards, Localizable.strings and UIColors). :large_orange_diamond:
* [Blade ★768 ⏳1Y](jondot/blade) - Generate Xcode image catalogs for iOS / OSX app icons, universal images, and more.
* [Retini ★88](terwanerik/Retini) - A super simple retina (2x, 3x) image converter.
* [Provisioning ★1339](chockenberry/Provisioning) - A Quick Look plug-in to preview .mobileprovision files.
* [Jazzy ★4409](realm/jazzy) - Soulful docs for Swift & Objective-C. :large_orange_diamond:
* [appledoc ★3660](tomaz/appledoc) - ObjectiveC code Apple style documentation set generator.
* [Azkaban ★66](neonichu/Azkaban) - A CLI to Alcatraz, the Xcode package manager. :large_orange_diamond:
* [Laurine ★987](JiriTrecak/Laurine) - Laurine - Localization code generator written in Swift. Sweet! :large_orange_diamond:
* [Chocolat ★186 ⏳1Y](pepibumur/Chocolat) - :chocolate_bar: Generate podspecs from Swift packages. :large_orange_diamond:
* [StoryboardMerge ★197 ⏳1Y](marcinolawski/StoryboardMerge) - Xcode storyboards diff and merge tool.
* [ai2app ★80](metasmile/ai2appiconset) - Creating AppIcon sets from Adobe Illustrator (all supported formats).
* [ViewMonitor ★703](daisuke0131/ViewMonitor) - ViewMonitor can measure view positions with accuracy. :large_orange_diamond:
* [abandoned-strings ★63](ijoshsmith/abandoned-strings) - Command line program that detects unused resource strings in an iOS or OS X application. :large_orange_diamond:
* [swiftenv ★1280](kylef/swiftenv) - swiftenv allows you to easily install, and switch between multiple versions of Swift. :large_orange_diamond:
* [ThisCouldBeUsButYouPlaying ★1082](neonichu/ThisCouldBeUsButYouPlaying) - :black_joker: Generate Swift Playgrounds for any library. :large_orange_diamond:
* [Misen ★116](tasanobu/Misen) - Script to support easily using Xcode Asset Catalog in Swift. :large_orange_diamond:[e]
* [git-xcp ★14](metasmile/git-xcp) - A Git plugin for versioning workflow of real-world Xcode project. fastlane's best friend.
* [WatchdogInspector ★428](tapwork/WatchdogInspector) - Shows your current framerate (fps) in the status bar of your iOS app
* [Cichlid ★254](dealforest/Cichlid) - automatically delete the current project's DerivedData directories :large_orange_diamond:
* [Delta ★240](thoughtbot/Delta) - Managing state is hard. Delta aims to make it simple. :large_orange_diamond:
* [SwiftLintXcode ★237](ypresto/SwiftLintXcode) - An Xcode plug-in to format your code using SwiftLint. :large_orange_diamond:
* [XCSwiftr ★301](dzenbot/XCSwiftr) - An Xcode Plugin to convert Objective-C to Swift :large_orange_diamond:
* [SwiftKitten ★124](johncsnyder/SwiftKitten) - Swift autocompleter for Sublime Text, via the adorable SourceKitten framework :large_orange_diamond:
* [Kin ★93](Karumi/Kin) - Have you ever found yourself undoing a merge due to a broken Xcode build? Then Kin is your tool. It will parse your project configuration file and detect errors. :large_orange_diamond:
* [AVXCAssets-Generator ★275](angelvasa/AVXCAssets-Generator) - AVXCAssets Generator takes path for your assets images and creates appiconset and imageset for you in just one click :large_orange_diamond:
* [Peek ★1149](shaps80/Peek) - Take a Peek at your application. :large_orange_diamond:
* [SourceKitten ★1019](jpsim/SourceKitten) - An adorable little framework and command line tool for interacting with SourceKit. :large_orange_diamond:
* [Localizations ★95](athiercelin/localizations) - OS X app that manages localizations of Xcode projects. :large_orange_diamond:
* [xcbuild ★1290](facebook/xcbuild) - Xcode-compatible build tool.
* [XcodeIssueGenerator ★142](doubleencore/XcodeIssueGenerator) - An executable that can be placed in a Run Script Build Phase that marks comments like // TODO: or // SERIOUS: as warnings or errors so they display in the Xcode Issue Navigator. :large_orange_diamond:
* [SwiftCompilationPerformanceReporter ★146](tumblr/SwiftCompilationPerformanceReporter) - Generate automated reports for slow Swift compilation paths in specific targets :large_orange_diamond:
* [BuildTimeAnalyzer ★1708](RobertGummesson/BuildTimeAnalyzer-for-Xcode) - Build Time Analyzer for Swift :large_orange_diamond:
* [Duration ★286](SwiftStudies/Duration) - A simple Swift package for measuring and reporting the time taken for operations :large_orange_diamond:
* [Benchmark ★54](WorldDownTown/Benchmark) - The Benchmark⏲ module provides methods to measure and report the time used to execute Swift code. :large_orange_diamond:
* [MBAssetsImporter ★69](MatiBot/MBAssetsImporter) - Import assets from Panoramio or from your OS X file system with their metadata to your iOS simulator (Swift 2.0) :large_orange_diamond:
* [Realm Browser ★393](realm/realm-browser-osx) - Realm Browser is a Mac OS X utility to open and modify realm database files.
* [SuperDelegate ★370](square/SuperDelegate) – SuperDelegate provides a clean application delegate interface and protects you from bugs in the application lifecycle.
* [fastlane-plugin-appicon ★121](KrauseFx/fastlane-plugin-appicon) - Generate required icon sizes and iconset from a master application icon.
* [infer ★6755](facebook/infer) - A static analyzer for Java, C and Objective-C.
* [PlayNow ★92](marcboquet/PlayNow) - Small app that creates empty Swift playground files and opens them with Xcode. :large_orange_diamond:
* [Xtrace ★1640 ⏳1Y](johnno1962/Xtrace) - Trace Objective-C method calls by class or instance
* [xcenv ★196](xcenv/xcenv) - Groom your Xcode environment.
* [playgroundbook ★195](playgroundbooks/playgroundbook) - Tool for Swift Playground books
* [Ecno ★48](xmartlabs/Ecno) - Ecno is a task state manager built on top of UserDefaults in pure Swift 3. :large_orange_diamond:
* [ipanema ★3](toshi0383/ipanema) - ipanema analyzes and prints useful information from *.ipa file.
* [pxctest ★713](plu/pxctest) - Parallel XCTest - Execute XCTest suites in parallel on multiple iOS Simulators.
* [IBM Swift Sandbox](https://swift.sandbox.bluemix.net/verify) - The IBM Swift Sandbox is an interactive website that lets you write Swift code and execute it in a server environment – on top of Linux! :large_orange_diamond:
* [FBSimulatorControl ★1965](facebook/FBSimulatorControl) - A Mac OS X library for managing and manipulating iOS Simulators
* [IconResizer](https://iconresizer.com/) - A simple web application to resize iPhone and iPad app icons for the App Store
* [Nomad](http://nomad-cli.com) - Suite of command line utilities & libraries for sending APNs, create & distribute *.ipa*, verify In-App-Purchase receipt and more.
* [Cookiecutter ★386](JetpackSwift/FrameworkTemplate) - A template for new Swift iOS / tvOS / watchOS / macOS Framework project ready with travis-ci, cocoapods, Carthage, SwiftPM and a Readme file :large_orange_diamond:
* [Sourcery ★2117](krzysztofzablocki/Sourcery) - A tool that brings meta-programming to Swift, allowing you to code generate Swift code. :large_orange_diamond:
* [AssetChecker 👮 ★33](freshOS/AssetChecker) - Keeps your Assets.xcassets files clean and emits warnings when something is suspicious. :large_orange_diamond:
* [PlayAlways ★376](insidegui/PlayAlways) - Create Xcode playgrounds from your menu bar :large_orange_diamond:
* [GDPerformanceView-Swift ★1333](dani-gavrilov/GDPerformanceView-Swift) - Shows FPS, CPU usage, app and iOS versions above the status bar and report FPS and CPU usage via delegate. :large_orange_diamond:
* [Traits ★832](krzysztofzablocki/Traits) - Library for a real-time design and behavior modification of native iOS apps without recompiling (code and interface builder changes are supported). :large_orange_diamond:
* [Struct](https://www.get-struct.tools) - A tool for iOS and Mac developers to automate the creation and management of Xcode projects.
* [Nori ★280](yukiasai/Nori) - Easier to apply code based style guide to storyboard. :large_orange_diamond:
* [DBDebugToolkit ★494](dbukowski/DBDebugToolkit) - Set of easy to use debugging tools for iOS developers & QA engineers.
* [Attabench ★478](lorentey/Attabench) - Microbenchmarking app for Swift with nice log-log plots :large_orange_diamond:
* [Gluten ★5](wilbertliu/Gluten) - Nano library to unify XIB and it's code. :large_orange_diamond:
* [LicensePlist ★777](mono0926/LicensePlist) - A license list generator of all your dependencies for iOS applications. :large_orange_diamond:

# Rapid Development
* [Playgrounds ★2269](krzysztofzablocki/Playgrounds) - Playgrounds for Objective-C for extremely fast prototyping / learning.
* [MMBarricade ★344](mutualmobile/MMBarricade) - Runtime configurable local server for iOS apps.
* [STV Framework](http://www.sensiblecocoa.com) - Native visual iOS development.

# Injection
* [dyci ★1043](DyCI/dyci-main) - Code injection tool.
* [injectionforxcode ★4653](johnno1962/injectionforxcode) - Code injection including Swift.
* [Swinject ★1568](Swinject/Swinject) - Dependency injection framework for Swift
* [Reliant ★51](appfoundry/Reliant) - Nonintrusive Objective-C dependency injection.
* [Kraken ★17](sabirvirtuoso/Kraken) - A Dependency Injection Container for Swift with easy-to-use syntax.
* [Cleanse ★868](square/Cleanse) - Lightweight Swift Dependency Injection Framework by Square. :large_orange_diamond:
* [Typhoon ★2158](appsquickly/Typhoon) - Powerful dependency injection (Objective-C & Swift).
* [Perform ★226](thoughtbot/Perform) - Easy dependency injection for storyboard segues. :large_orange_diamond:
* [Alchemic ★10](drekka/Alchemic) - Advanced, yet simple to use DI framework for Objective-C.
* [Guise ★15](prosumma/Guise) - An elegant, flexible, type-safe dependency resolution framework for Swift :large_orange_diamond:

# Deployment / Distribution
* [fastlane ★16105](fastlane/fastlane) - Connect all iOS deployment tools into one streamlined workflow.
* [deliver](https://github.com/fastlane/fastlane/tree/master/deliver) - Upload screenshots, metadata and your app to the App Store using a single command.
* [snapshot](https://github.com/fastlane/fastlane/tree/master/snapshot) Automate taking localized screenshots of your iOS app on every device.
* [buddybuild](https://www.buddybuild.com/) - A mobile iteration platform - build, deploy, and collaborate.
* [Bitrise](https://www.bitrise.io) Mobile Continuous Integration & Delivery with dozens of integrations to build, test, deploy and collaborate.
* [watchbuild ★21](fastlane/watchbuild) - Get a notification once your iTunes Connect build is finished processing.
* [Crashlytics](https://try.crashlytics.com/) - A crash reporting and beta testing service.
* [TestFlight Beta Testing](https://developer.apple.com/testflight/) - The beta testing service hosted on iTunes Connect (requires iOS 8 or later).
* [HockeyApp](https://www.hockeyapp.net) - With HockeyApp, you can distribute beta versions of your app, collect live crash reports, get feedback from users, and analyze test coverage.
* [boarding ★520](fastlane/boarding) - Instantly create a simple signup page for TestFlight beta testers.
* [HockeyKit ★2195](bitstadium/HockeyKit) - A software update kit.
* [Boombox.io](https://boombox.io/) - Sign up TestFlight beta testers on your website. Embeddable and hosted TestFlight beta sign-up forms
* [Rollout.io](https://rollout.io/) - SDK to patch, fix bugs, modify and manipulate native apps (Obj-c & Swift) in real-time.
* [AppLaunchpad](https://theapplaunchpad.com/) - Free App Store screenshot builder.
* [LaunchKit ★1586](LaunchKit/LaunchKit) - A set of web-based tools for mobile app developers, now open source!

# App Store
* [Average App Store Review Times](http://appreviewtimes.com) This site tracks the average App Store review times for both the iOS and the Mac App Store using data crowdsourced from iOS and Mac developers.
* [Apple's Common App Rejections Styleguide](https://developer.apple.com/app-store/review/rejections/)  Highlighted some of the most common issues that cause apps to get rejected.
* [Free App Store Optimization Tool](https://www.mobileaction.co) Lets you track your App Store visibility in terms of keywords and competitors.
* [App Release Checklist](https://github.com/oisin/app-release-checklist/blob/master/checklist.md) - A checklist to pore over before you ship that amazing app that has taken ages to complete, but you don't want to rush out in case you commit a schoolboy error that will end up making you look dumber than you are.
* [Harpy ★2291](ArtSabintsev/Harpy) - Notify users when a new version of your iOS app is available, and prompt them with the App Store link.
* [iRate ★4166](nicklockwood/iRate) - A handy class that prompts users of your iPhone or Mac App Store app to rate your application after using it for a while. Similar to Appirater, but with a simpler, cleaner interface and automatic support for iOS fast application switching.
* [appirater ★4397](arashpayan/appirater) - A utility that reminds your iPhone app's users to review the app.
* [Siren ★1852](ArtSabintsev/Siren) - Notify users when a new version of your app is available and prompt them to upgrade. :large_orange_diamond:
* [Appstore Review Guidelines ★2](aashishtamsya/Appstore-Review-Guidelines) - A curated list of points which a developer has to keep in mind before submitting his/her application on appstore for review.

# Xcode

#### Plugins
* [FuzzyAutocompletePlugin ★3410](FuzzyAutocomplete/FuzzyAutocompletePlugin) - A Xcode 5+ plugin that adds more flexible autocompletion rather than just prefix-matching.
* [SCXcodeMiniMap ★1047](stefanceriu/SCXcodeMiniMap) - SCXcodeMiniMap is a plugin that adds a source editor MiniMap to Xcode.
* [Show in Github ★242 ⏳1Y](larsxschneider/ShowInGitHub) - Xcode plugin to open the GitHub page of the commit of the currently selected line in the editor window.
* [BBUFullIssueNavigator ★248 ⏳1Y](neonichu/BBUFullIssueNavigator) - Xcode plugin for showing all issue content in the issue navigator.
* [BBUDebuggerTuckAway ★702](neonichu/BBUDebuggerTuckAway) - Xcode plugin for auto-hiding the debugger once you start typing in the source code editor.
* [SCXcodeSwitchExpander ★669](stefanceriu/SCXcodeSwitchExpander) - SCXcodeSwitchExpander is a small Xcode plugin that expands switch statements by inserting missing cases.
* [VVDocumenter-Xcode ★8351](onevcat/VVDocumenter-Xcode) - Xcode plug-in which helps you write Javadoc style documents easier.
* [XAlign ★2649](qfish/XAlign) - An amazing Xcode plugin to align regular code. It can align anything by using custom alignment patterns.
* [CocoaPods Xcode Plugin ★2390](kattrali/cocoapods-xcode-plugin) - Dependency management helper for your CocoaPods, right in Xcode.
* [KSImageNamed-Xcode ★4292](ksuther/KSImageNamed-Xcode) - Xcode plug-in that provides autocomplete for imageNamed: calls.
* [ColorSense-for-Xcode ★2918 ⏳1Y](omz/ColorSense-for-Xcode) - Plugin for Xcode to make working with colors more visual.
* [Backlight-for-XCode ★442 ⏳1Y](limejelly/Backlight-for-XCode) - Highlights the current editing line in Xcode
* [KPRunEverywhereXcodePlugin ★330 ⏳1Y](kitschpatrol/KPRunEverywhereXcodePlugin) - An Xcode plugin to build and run an app across multiple iOS devices with one click.
* [RevealPlugin ★236](shjborage/Reveal-Plugin-for-Xcode) - Plugin for Xcode to integrate the Reveal App to your project automatic.
* [RealmPlugin](https://realm.io/docs/objc/0.81.0/#xcode-plugin)- Xcode plugin to generate new Realm models.
* [AdjustFontSize ★283](zats/AdjustFontSize-Xcode-Plugin) - Instant font size adjustment with `⌘ +` / `⌘ -`.
* [Rephrase](https://www.rephrase.io) - Localise from Xcode.
* [XCActionBar ★1229](pdcgomes/XCActionBar) - "Alfred for Xcode" plugin.
* [QuickJump ★27](wiruzx/QuickJump) - Quick code navigation for Xcode.
* [CATweaker ★704 ⏳1Y](keefo/CATweaker) - Plugin for creating beautiful CAMediaTimingFunction curve.
* [XcodeWay ★225](onmyway133/XcodeWay) - An Xcode plugin that makes navigating to many places easier (available via Alcatraz).
* [GitDiff ★840](johnno1962/GitDiff) - Highlights deltas against git repo in Xcode.
* [MCLog ★610](yuhua-chen/MCLog) - Xcode plugin for filtering the console area.
* [XToDo ★1590](trawor/XToDo) - Dialog with list of all TODO, FIXME, ??? and !!! in the project.
* [CopyIssue ★180 ⏳1Y](hanton/CopyIssue-Xcode-Plugin) - Makes Copy Xcode Issue Description Easy.
* [RTImageAssets ★2388](rickytan/RTImageAssets) - A Xcode plugin to automatically generate all the App icons needed.
* [BBUncrustifyPlugin-Xcode ★1212](benoitsan/BBUncrustifyPlugin-Xcode) - Xcode plugin to format source code using ClangFormat or Uncrustify.
* [Aviator ★30](marksands/Aviator) - Xcode plugin that brings ⇧⌘T (source/test toggle) from AppCode over to Xcode.
* [JumpMarks ★50](merrickp/JumpMarks) - Navigate your code files with numbered bookmarks.
* [XCSnippetr ★95](dzenbot/XCSnippetr) - An Xcode Plugin to upload code snippets directly into Slack and Gist.
* [Peckham ★737](markohlebar/Peckham) - Add #import-s from anywhere in the code.
* [MLAutoReplace ★242](molon/MLAutoReplace) - Xcode plugin, Re-Intent, make you write code more quickly.
* [AutoHighlightSymbol ★74](chiahsien/AutoHighlightSymbol) - A Xcode plugin to add highlight to the instances of selected symbol.
* [Reveal-In-GitHub ★272 ⏳1Y](lzwjava/Reveal-In-Github) - Xcode plugin to let you jump to GitHub History, Blame, PRs, Issues, Notifications of any GitHub repo with one shortcut.
* [CleanHeaders-Xcode ★68](insanoid/CleanHeaders-Xcode) - A simple iSort like header sorting and duplicate removal plugin for Xcode, makes your headers look more organized.
* [Luft ★183](k0nserv/luft) - The Xcode Plugin that helps you write lighter view controllers
* [You-Can-Do-It ★231](orta/You-Can-Do-It) - Is learning a new language getting you down? Worry not, this Xcode plugin will keep you motivated.
* [PreciseCoverage ★171 ⏳1Y](zats/PreciseCoverage) - Make Xcode code coverage more informative
* [AutoIndentWithSave ★53](ThilinaHewagama/AutoIndentWithSave) Xcode plugin which indent the source code when save
* [Refactorator ★974](johnno1962/Refactorator) - Xcode Plugin that Refactors Swift & Objective-C :large_orange_diamond:
* [VWInstantRun ★1064](wangshengjia/VWInstantRun) - An Xcode plugin let you build & run your selected lines of code in Xcode without running the whole project, you'll have the output instantly in your Xcode console. :large_orange_diamond:
* [TTPasteHistory ★30 ⏳1Y](tutumagi/TTPasteHistory) - A Xcode plugin. Recording you copy-and-paste history easily to write the code
* [xSendIssue ★4 ⏳1Y](hungri-yeti/xSendIssue) - Plugin for Xcode to submit GitHub issues directly from within Xcode.
* [Swimat ★675](Jintin/Swimat) - An Xcode formatter plug-in to format your swift code.
* [Fastlane-Plugin ★35](RishabhTayal/Fastlane-Plugin) - The awesome Fastlane tools brought into your Xcode.
* [Gradle Xcode plugin](https://openbakery.org/gxp/) - Build iOS or Mac OS X Projects using Gradle.
* [SYXcodeIconVersion ★96](dvkch/SYXcodeIconVersion) - This Xcode plugin shows Xcode app version in the Dock and App Switcher icon.
* [Gradle ★353](openbakery/gradle-xcodePlugin) - gradle xcodePlugin to build iOS and Mac projects.
* [HOStringSense-for-Xcode ★723 ⏳1Y](holtwick/HOStringSense-for-Xcode) - Plugin for Xcode to make perfect editing regular expressions, multi line texts, inline HTML and many more use cases. Also provides quick feedback on string length.
* [CleanClosureXcode ★139](BalestraPatrick/CleanClosureXcode) - An Xcode Source Editor extension to clean the closure syntax. :large_orange_diamond:
* [xTextHandler ★1330](cyanzhong/xTextHandler) - Xcode Source Editor Extension Toolset (Plugins for Xcode 8) :large_orange_diamond:
* [FastStub-Xcode ★485](music4kid/FastStub-Xcode) - Xcode Plugin helps you find missing methods in your class header, protocols, and super class, also makes fast inserting.
* [JSPatchX ★738](bang590/JSPatchX) - JSPatch bridge Objective-C and Javascript using the Objective-C runtime. You can call any Objective-C class and method in JavaScript by just including a small engine. JSPatch is generally use for hotfix iOS App.
* [Dash](https://kapeli.com/dash) - Dash is a great documentation browser which integrates closely into Xcode with its plugin.
* [SFJumpToLine ★10 ⏳2Y](sferrini/SFJumpToLine) - Xcode plugin that moves the instruction pointer to the selected line
* [ClangFormat-Xcode ★2499](travisjeffery/ClangFormat-Xcode) - An Xcode plug-in to format your code using Clang's format tools.
* [update_xcode_plugins ★876](inket/update_xcode_plugins) - No more messing with plugin UUIDs; Plugins on Xcode 8!
* [MakeXcodeGr8Again ★694](fpg1503/MakeXcodeGr8Again) - Xcode + Plugins = :blue_heart: :large_orange_diamond:
* [SwiftInitializerGenerator ★495](Bouke/SwiftInitializerGenerator) - Xcode 8 Source Code Extension to Generate Swift Initializers. :large_orange_diamond:
* [XcodeEquatableGenerator ★135](sergdort/XcodeEquatableGenerator) - Xcode 8 Source Code Extension will generate conformance to Swift Equatable protocol based on type and fields selection. :large_orange_diamond:
* [Import ★649](markohlebar/Import) - Xcode extension for adding imports from anywhere in the code. :large_orange_diamond:
* [Mark ★94](velyan/Mark) - Xcode extension for generating MARK comments. :large_orange_diamond:
* [XShared ★53](Otbivnoe/XShared) - Xcode extension which allows you copying the code with special formatting quotes for social (Slack, Telegram). :large_orange_diamond:
* [XGist ★47](Bunn/Xgist) - Xcode extension which allows you to send your text selection or entire file to Github's Gist and automatically copy the Gist URL into your Clipboard. :large_orange_diamond:

#### Themes
* [Dracula Theme ★12 ⏳1Y](zenorocha/dracula-theme) - A dark theme for Xcode.
* [Xcode themes list ★1595](hdoria/xcode-themes) - Color themes for Xcode.
* [Solarized-Dark-for-Xcode ★248](ArtSabintsev/Solarized-Dark-for-Xcode) - Solarized Dark Theme for Xcode 5.
* [WWDC2016 Xcode Color Scheme ★334](cargath/WWDC2016-Xcode-Color-Scheme) - A color scheme for Xcode based on the WWDC 2016 invitation.

#### Other Xcode

* [awesome-xcode-scripts ★20](aashishtamsya/awesome-xcode-scripts) - A curated list of useful xcode scripts 📝.
* [Synx ★5404](venmo/synx) - A command-line tool that reorganizes your Xcode project folder to match your Xcode groups.
* [dsnip ★9 ⏳1Y](Tintenklecks/IBDelegateCodesippets) - Tool to generate (native) Xcode code snippets from all protocols/delegate methods of UIKit (UITableView, ...)
* [SBShortcutMenuSimulator ★1760](DeskConnect/SBShortcutMenuSimulator) - 3D Touch shortcuts in the Simulator
* [awesome-gitignore-templates ★6](aashishtamsya/awesome-gitignore-templates) - A collection of swift, objective-c, android and many more langugages .gitignore templates 📝.
* [swift-project-template ★14](artemnovichkov/swift-project-template) - Template for iOS Swift project generation.
* [Swift-VIPER-Module ★164](Juanpe/Swift-VIPER-Module) - Xcode template for create modules with VIPER Architecture written in Swift 3 :large_orange_diamond:
* [ViperC ★24](abdullahselek/ViperC) - Xcode template for VIPER Architecture written in Objective-C

# Reference
* [Swift Cheat Sheet ★637](iwasrobbed/Swift-CheatSheet) - A quick reference cheat sheet for common, high level topics in Swift. :large_orange_diamond:
* [Objective-C Cheat Sheet ★912](iwasrobbed/Objective-C-CheatSheet) - A quick reference cheat sheet for common, high level topics in Objective-C.
* [SwiftSnippets ★86](hyperoslo/SwiftSnippets) - A collection of Swift snippets to be used in Xcode
* [App Store Checklist ★12](whitef0x0/app-store-checklist) - A checklist of what to look for before submitting your app to the App Store.

# Style Guides
* [NY Times - Objective C Style Guide ★4411](NYTimes/objective-c-style-guide) - The Objective-C Style Guide used by The New York Times.
* [raywenderlich Style Guide ★2541](raywenderlich/objective-c-style-guide) - A style guide that outlines the coding conventions for raywenderlich.com.
* [Github Objective-C Style Guide ★1643 ⏳1Y](github/objective-c-style-guide) - Style guide & coding conventions for Objective-C projects.
* [Objective-C Coding Convention and Best Practices](https://gist.github.com/soffes/812796) - Gist with coding conventions.
* [Swift Style Guide by @raywenderlich ★7126](raywenderlich/swift-style-guide) - The official Swift style guide for raywenderlich.com. :large_orange_diamond:
* [Spotify Objective-C Coding Style ★194](spotify/ios-style) - Guidelines for iOS development in use at Spotify.
* [Github - Style guide & coding conventions for Swift projects ★4083](github/swift-style-guide) - A guide to our Swift style and conventions by @github. :large_orange_diamond:
* [Futurice iOS Good Practices ★6142](futurice/ios-good-practices) - iOS starting guide and good practices suggestions by [@futurice](https://github.com/futurice).
* [Swift-Community-Best-Practices ★1882](schwa/Swift-Community-Best-Practices) - Best practices for software development with Swift :large_orange_diamond:
* [SlideShare Swift Style Guide](https://github.com/SlideShareInc/swift-style-guide/blob/master/swift_style_guide.md) - SlideShare Swift Style Guide we are using for our upcoming iOS 8 only app written in Swift :large_orange_diamond:
* [Prolific Interactive Style Guide ★141](prolificinteractive/swift-style-guide) - A style guide for Swift.

# Good Websites

#### News, Blogs and more
* [BGR](http://bgr.com/ios-7/)
* [iMore](http://www.imore.com/)
* [Lifehacker](http://lifehacker.com/tag/ios)
* [NSHipster](http://nshipster.com)
* [Objc.io](https://www.objc.io/)
* [ASCIIwwdc](http://asciiwwdc.com)
* [Natasha The Robot](https://www.natashatherobot.com/)
* [Apple's Swift Blog](https://developer.apple.com/swift/blog/) :large_orange_diamond:
* [iOS Programming Subreddit](https://www.reddit.com/r/iOSProgramming/)
* [iOS8-day-by-day ★2680](shinobicontrols/iOS8-day-by-day) :large_orange_diamond:
* [iOScreator](https://www.ioscreator.com/) :large_orange_diamond:
* [Mathew Sanders](http://mathewsanders.com/) :large_orange_diamond:
* [Little Bites of Cocoa](https://littlebitesofcocoa.com/) :large_orange_diamond:
* [iOS Dev Nuggets](http://hboon.com/iosdevnuggets/) :large_orange_diamond:
* [This Week in Swift](http://swiftnews.curated.co) :large_orange_diamond:
* [iOS Developer and Designer interview ★1300 ⏳1Y](9magnets/iOS-Developer-and-Designer-Interview-Questions) - A small guide to help those looking to hire a developer or designer for iOS work.
* [iOS9-day-by-day ★1427 ⏳1Y](shinobicontrols/iOS9-day-by-day) :large_orange_diamond:
* [Code Facebook](https://code.facebook.com/ios/)
* [iOS Cookies](http://www.ioscookies.com/) - A hand curated collection of iOS libraries written in Swift :large_orange_diamond:
* [Feeds for iOS Developer ★46](rgnlax/Feeds-for-iOS-Developer) - The list of RSS feeds for iOS developers.
* [iOS10 day-by-day](https://www.shinobicontrols.com/blog/ios-10-day-by-day-index) :large_orange_diamond:

#### UIKit references
* [iOS Fonts](http://iosfonts.com/)
* [UIAppearance list](https://gist.github.com/mattt/5135521)

#### Forums and discuss lists
* [iPhone Dev SDK Forum](http://iphonedevsdk.com/)
* ["iOS" on Stackoverflow](https://stackoverflow.com/questions/tagged/ios)

#### Tutorials and Keynotes
* [AppCoda](http://www.appcoda.com)
* [Tutorials Point](http://www.tutorialspoint.com/ios/)
* [Code with Chris](http://codewithchris.com/)
* [Cocoa with Love](http://www.cocoawithlove.com/)
* [Code School - Try Objective-C](http://tryobjectivec.codeschool.com/)
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
* [Awesome-Swift-Education ★5172](hsavit1/Awesome-Swift-Education) - :fire: All of the resources for Learning About Swift :large_orange_diamond:
* [Awesome-Swift-Playgrounds ★1557](uraimo/Awesome-Swift-Playgrounds) - ⭐ A List of Awesome Swift Playgrounds! :large_orange_diamond:
* [learn-swift ★749](nettlep/learn-swift) - Learn Apple's Swift programming language interactively through these playgrounds. :large_orange_diamond:
* [Treehouse's iOS Courses and Workshops](https://teamtreehouse.com/library/topic:ios) - Topics for beginner and advanced developers in both Objective-C and Swift.
* [The Swift Summary Book ★1628](jakarmy/swift-summary) - A summary of Apple's Swift language written on Playgrounds. :large_orange_diamond:
* [Hacking With Swift](https://www.hackingwithswift.com) - Learn to code iPhone and iPad apps with 3 Swift tutorials. :large_orange_diamond:

#### iOS UI Template
* [iOS UI Design Kit](https://www.invisionapp.com/tethr)
* [iOS Design Guidelines](http://ivomynttinen.com/blog/ios-design-guidelines)
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
* [Swift Sandbox](http://swiftsandbox.io) - Swift developer newsletter, curated collection of Swift open source news, projects & resources. :large_orange_diamond:
* [raywenderlich.com Weekly](https://www.raywenderlich.com/newsletter) - sign up to receive the latest tutorials from raywenderlich.com each week
* [iOS Dev Tools Weekly](https://iosdev.tools) - The greatest iOS development tools, including websites, desktop and mobile apps, and back-end services.
* [iOS Trivia Weekly](http://wanderbit.us4.list-manage.com/subscribe?u=4e20cd8ea3a0ce09ff4619a52&id=5898a5992b) - Three challenging questions about iOS development every Wednesday
* [Indie iOS Focus Weekly](https://indieiosfocus.curated.co) - Looking for the best iOS dev links, tutorials, & tips beyond the usual news? Curated by Chris Beshore. Published every Thursday.
* [iOS Dev Weekly](https://iosdevweekly.com/) - Subscribe to a hand-picked round up of the best iOS development links every week. Free.
* [Swift Weekly Brief](https://swiftweekly.github.io/) - A community-driven weekly newsletter about Swift.org. Curated by Jesse Squires and published for free every Thursday
* [Server-Side Swift Weekly](https://www.serverswift.tech) - A weekly newsletter with the best links related to server-side Swift and cross-platform developer tools. Curated by [@maxdesiatov](https://twitter.com/maxdesiatov)

#### Medium
* [iOS App Development](https://medium.com/ios-os-x-development) - Stories and technical tips about building apps for iOS, Apple Watch, and iPad/iPhone
* [Swift Programming](https://medium.com/swift-programming) - The Swift Programming Language

# Social Media

#### Twitter
* [@objcio](https://twitter.com/objcio)
* [@nshipster](https://twitter.com/NSHipster)
* [@CocoaPods](https://twitter.com/CocoaPods)
* [@CocoaPodsFeed](https://twitter.com/CocoaPodsFeed)
* [@RubyMotion](https://twitter.com/RubyMotion)
* [@SwiftSandbox](https://twitter.com/SwiftSandbox) - Swift open source news, projects and resources.


#### Facebook Groups
* [HH iOS](https://www.facebook.com/groups/hhios/)
* [Sketch - Official group](https://www.facebook.com/groups/sketchformac/)
* [Design-Code](https://www.facebook.com/groups/designcode/)
* [Sketch-Design.io](https://www.facebook.com/groups/sketchdesignio)
* [Origami Community](https://www.facebook.com/groups/origami.community/)
* [Framer JS](https://www.facebook.com/groups/framerjs/)

# Podcasts
* [The Ray Wenderlich Podcast](https://www.raywenderlich.com/rwpodcast)
* [Debug](http://www.imore.com/debug)
* [iDeveloper](http://blog.ideveloper.co/)
* [App Story](http://www.appstorypodcast.com)
* [Mobile Couch](http://mobilecouch.co/)
* [iPhreaks](https://devchat.tv/iphreaks)
* [Under the Radar](https://www.relay.fm/radar)
* [Core Intuition](http://www.coreint.org/)
* [Swift Playhouse](http://www.swiftplayhouse.com/)
* [Release Notes](https://releasenotes.tv/)
* [More Than Just Code](http://mtjc.fm/)
* [Runtime](https://spec.fm/podcasts/runtime)
* [Consult](http://consultpodcast.com/)

# Books
* [The Swift Programming Language by Apple](https://itunes.apple.com/us/book/swift-programming-language/id881256329?mt=11) :large_orange_diamond:
* [Using Swift with Cocoa and Objective C by Apple](https://itunes.apple.com/us/book/using-swift-cocoa-objective/id888894773?mt=11) :large_orange_diamond:
* [iOS Programming: The Big Nerd Ranch Guide by Christian Keur, Aaron Hillegass, Joe Conway](https://www.bignerdranch.com/books/ios-programming/)
* [Programming in Objective-C by Stephen G. Kochan](https://www.amazon.com/Programming-Objective-C-6th-Developers-Library/dp/0321967607)
* [The Complete Friday Q & A: Volume 1](https://www.mikeash.com/book.html)
* [Core Data for iOS: Developing Data-Driven Applications for the iPad, iPhone, and iPod touch](https://www.amazon.com/Core-Data-iOS-Data-Driven-Applications/dp/0321670426)
* [Cocoa Design Patterns](https://www.amazon.com/Cocoa-Design-Patterns-Erik-Buck/dp/0321535022)
* [Hello Swift! by Tanmay Bakshi with Lynn Beighley](https://www.manning.com/books/hello-swift) :large_orange_diamond:
* [OS Development with Swift by Craig Grummitt](https://www.manning.com/books/ios-development-with-swift) :large_orange_diamond:
* [Anyone Can Create an App by Wendy L. Wise](https://www.manning.com/books/anyone-can-create-an-app) :large_orange_diamond:
* [Advanced Swift by Chris Eidhof, Ole Begemann, and Airspeed Velocity](https://www.objc.io/books/advanced-swift/) :large_orange_diamond:
* [Functional Swift by Chris Eidhof, Florian Kugler, and Wouter Swierstra](https://www.objc.io/books/functional-swift/) :large_orange_diamond:
* [Core Data by Florian Kugler and Daniel Eggert](https://www.objc.io/books/core-data/) :large_orange_diamond:

# Other Awesome Lists
Other amazingly awesome lists can be found in the
* [awesome-awesomeness ★18868](bayandin/awesome-awesomeness) list.
* [Open Source apps ★13322](dkhamsing/open-source-ios-apps) list of open source iOS apps
* Awesome-swift
  * [@matteocrippa ★12149](matteocrippa/awesome-swift) - A collaborative list of awesome swift resources.
  * [@Wolg ★3899](Wolg/awesome-swift) - A curated list of awesome Swift frameworks, libraries and software.
  * [Awesome-Swift-Education ★5172](hsavit1/Awesome-Swift-Education) - All of the resources for Learning About Swift :large_orange_diamond:
* [awesome watchkit apps ★186 ⏳1Y](sanketfirodiya/sample-watchkit-apps) curated list of sample watchkit apps and tutorials. :watch:
* [iOS Learning Resources ★213](sanketfirodiya/iOS-learning-resources) Comprehensive collection of high quality, frequently updated and well maintained iOS tutorial sites.
* [awesome-ios-animation ★2540](ameizi/awesome-ios-animation) - A curated list of awesome iOS animation, including Objective-C and Swift libraries.
* [awesome-ios-chart ★918](ameizi/awesome-ios-chart) - A curated list of awesome iOS chart libraries, including Objective-C and Swift.
* [awesome-gists ★152](vsouza/awesome-gists#ios) - A list of amazing gists (iOS section).
* [awesome-ios-ui ★9429](cjwirth/awesome-ios-ui) - A curated list of awesome iOS UI/UX libraries.
* [Awesome Reactive Programming in Swift ★84 ⏳1Y](SideEffects-xyz/Awesome-Reactive-Programming-Swift) - A collection of frameworks, talks and resources about reactive programming in Swift.
* [Awesome-Server-Side-Swift/TheList ★461](Awesome-Server-Side-Swift/TheList) - A list of Awesome Server Side Swift 3 projects
* [awesome-interview-questions ★14931](MaximAbramchuck/awesome-interview-questions#ios) - A curated awesome list of lists of interview questions including iOS.
* [Awesome-iOS-Companies](https://ioscompanies.info/about/welcome) - A curated geographical directory of companies doing iOS development.
* [iOS-Playbook ★54](bakkenbaeck/iOS-handbook) - Guidelines and best practices for excellent iOS apps

# Contributing and License
 * [See the guide](https://github.com/vsouza/awesome-ios/blob/master/.github/CONTRIBUTING.md)
 * Distributed under the MIT license. See LICENSE for more information.
---
<p align="center">
	This list is a copy of <a href="vsouza/awesome-ios">vsouza/awesome-ios</a> with ranks
</p>
