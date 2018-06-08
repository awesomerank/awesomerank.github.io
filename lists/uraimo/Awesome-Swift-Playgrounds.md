---
layout: default
title: Awesome Rank for uraimo/Awesome-Swift-Playgrounds
---

<p align="center">
	This list is a copy of <a href="https://github.com/uraimo/Awesome-Swift-Playgrounds">uraimo/Awesome-Swift-Playgrounds</a> with ranks
</p>
---
# Awesome Swift Playgrounds [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg) ★85445](https://github.com/sindresorhus/awesome)  ![147 playgrounds](https://img.shields.io/badge/Playgrounds:-147-orange.svg) [![Tweet](https://img.shields.io/twitter/url/http/shields.io.svg?style=social)](https://twitter.com/intent/tweet?text=A%20List%20of%20more%20than%20150%20Awesome%20Swift%20Playgrounds&url=https://github.com/uraimo/Awesome-Swift-Playgrounds&via=uraimo)

> A curated list of awesome Swift playgrounds.

### Contributing

Please take a quick look at the [contribution guidelines](https://github.com/uraimo/awesome-swift-playgrounds/blob/master/CONTRIBUTING.md) first. Thanks to all [contributors](https://github.com/uraimo/awesome-swift-playgrounds/graphs/contributors); you rock!

If you see a playground here that does not work anymore with the current release of Xcode or is not a good fit, please submit a pull request to improve this file or consider updating it, thank you!

### Downloading all the playgrounds

Unless otherwise indicated, all playgrounds are compatible with Swift 3.

All the playgrounds are available as submodules in the `playgrounds/` directory, to download them all in one go, just clone this repository with `git clone --recursive https://github.com/uraimo/Awesome-Swift-Playgrounds.git` or execute `git submodule update --init` after you have cloned the repository the usual way. 

Apple's playgrounds distributed as zip archives have to be downloaded manually.

### Tags

🌟 = My personal favorites

🍁 = Swift 4+ Playground

⏳ = Pre-Swift 3 Playground

### Contents

- [PlaygroundBooks](#playgroundbooks)
- [Learning Swift](#learning-swift)
- [Learning Swift: Advanced Topics](#learning-swift-advanced-topics)
  - [Design Patterns](#design-patterns)
  - [Protocol Oriented Programming](#protocol-oriented-programming)
  - [Functional Reactive Programming](#functional-reactive-programming)
- [Apple's Playgrounds](#apples-playgrounds)
- [Playgrounds about Playgrounds](#playgrounds-about-playgrounds)
- [Playgrounds from Playgroundbooks](#playgrounds-from-playgroundbooks)
- [Theoretical Computer Science](#theoretical-computer-science)
    - [Algorithms and Data Structures](#algorithms-and-data-structures)
    - [Languages](#languages)
    - [Machine Learning](#machine-learning)
- [UIKit And Graphics](#uikit-and-graphics)
  - [Core Image](#core-image)
  - [Metal](#metal)
  - [Animations](#animations)
  - [SpriteKit](#spritekit)
- [Audio](#audio)
- [Mathematics](#mathematics)
- [Libraries and APIs](#libraries-and-apis)
- [Playground sets](#playground-sets)
- [Miscellaneous](#miscellaneous)


## PlaygroundBooks
*Playgrounds that can be run on your iPad*

* [Tree Trouble Playbook ★15 ⏳1Y](https://github.com/joelrorseth/Tree-Trouble) - An interactive Swift Playground Book about Binary Search Trees.
* [Auto Pong ★2 ⏳1Y](https://github.com/cardoso/AutoPong) - A tutorial to implement a pong based on a simple AI.
* [Neural Network Playground ★358](https://github.com/hetelek/Neural-Network-Playground) - A neural network Swift playground, with no third party dependencies.
* [Window Manager Playground ★35 ⏳1Y](https://github.com/steventroughtonsmith/windowmanager-playgroundbook) - Playground for an experimental window manager.
* [AudioKit Playground Book ★67 ⏳1Y](https://github.com/audiokit/AudioKitPlaygroundBook) - A set of playgrounds using AudioKit designed for the iOS10 Playgrounds app.
* [Numsw ★106](https://github.com/sonsongithub/numsw) - A swift playground book that mimics some of the features of numpy and jupyter notebook.
* [File Browser Playground ★188 ⏳1Y](https://github.com/steventroughtonsmith/files-playgroundbook) - Simple File Browser for Swift Playgrounds on iOS.
* [Geometry with Swift ★3](https://github.com/dbbudd/Geometry-Swift-PlaygroundBook) - In this course your students will learn the fundamentals of Swift 3 programming, using geometry as their context for learning. 
* [Image Filtering ★42](https://github.com/lennet/image-filtering) - A Swift playgroundbook about Image Filtering. 🌟
* [Spacetime Rhapsody ★11 ⏳1Y](https://github.com/hollisliu/Spacetime-Rhapsody) - A Swift Playground visualizing gravity based on Einstein's Theory of General Relativity. 🌟
* [Guilloche Pattern Playground Book ★7](https://github.com/TheWildHorse/GuillochePlayground) - Learn more about this pattern you see every day, but probably never knew it was really carefully designed. 🍁
* [Accessibility ★1](https://github.com/xReee/wwdc2018) - Accessibility for iOS developers. 🍁 

## Learning Swift
*Some interesting playgrounds to learn Swift*

* [The Swift Programming Language Playgrounds ★165](https://github.com/danielpi/Swift-Playgrounds) - 40+ playgrounds, one for each chapter of Apple's Swift book. 🌟
* [Swift Hack Pack ★10 ⏳1Y](https://github.com/GuildSA/swift-hack-pack) - Collection of playgrounds that teaches Swift.
* [The Swift Summary Book ★1659](https://github.com/jakarmy/swift-summary) - A summary of Apple's Swift language. 🌟
* [Swifter Tips ★105 ⏳1Y](https://github.com/swifter-tips/Playground) - Examples for every feature of the Swift language.
* [About Swift ★35](https://github.com/NicolaLancellotti-About/About-Swift) - A playground about Swift language.
* [MPCS51032 UChicago iOS Course ★4](https://github.com/uchicago-mobi/mcps51032-2017-spring-playground) - Playgrounds from the 2017 Spring iOS course of the University of Chicago.
* [What's new in Swift 4 ★1906](https://github.com/ole/whats-new-in-swift-4) - An Xcode playground showing off the new features in Swift 4.0. 🍁 🌟 
* [Codable Playground ★7](https://github.com/filip-zielinski/CodablePlayground) - Playground that demonstrates advanced uses of Codable 🍁

## Learning Swift: Advanced Topics
*Advanced topics, useful once you have mastered the basics of the language*

* [A Swift Introduction to Core Data ★120](https://github.com/andyshep/CoreDataPlaygrounds) - Learn Core Data experimenting directly in this playground. 🌟
* [TDDSwiftPlayground ★42 ⏳1Y](https://github.com/sshrpe/TDDSwiftPlayground) - Demonstration of using Swift Playgrounds in Test Driven Development with XCTest.
* [Concurrency on iOS ★33 ⏳1Y](https://github.com/sammyd/2017AtSwift_Concurrency) - Concurrency and Parallelism in iOS.
* [Modern Core Data ★18](https://github.com/dfreniche/modern-core-data-playground) - An introduction to Core Data.
* [Swift DSL Example ★16](https://github.com/cfdrake/swift-dsl-example) - Implementation of a DSL in Swift.
* [Katan ★14 ⏳1Y](https://github.com/marciok/katan) - A micro web server that replies "Hello world!" to every request, an example of how to use sockets in Swift.
* [Swift Regular Expressions ★3](https://github.com/ogulcan/SwiftRegEx) - A playground to learn regular expressions with Swift.
* [Network Stack ★3](https://github.com/AndrejKolar/NetworkStack) - Clean & simple Swift networking stack playground.
* [Swiftly Typed Resources ★73 ⏳1Y](https://github.com/jstart/Swiftly-Typed-Resources) - A playground showing how Swift makes Strings, Colors, Fonts, Images, etc easier to deal with. ⏳
* [Swift KVO Closures ★10 ⏳3Y](https://github.com/rectalogic/KVOPlayground) - Swift KVO playground. ⏳ 
* [Swift Date Tutorial ★7 ⏳2Y](https://github.com/liuyubobobo/Swift-NSDate-Tutorial) - Learn everythig about NSDate. ⏳ 
* [Swift And C ★4 ⏳2Y](https://github.com/MacMark/SwiftAndC) - Examples about using C with Swift. ⏳ 
* [Swift Memory Management ★2 ⏳2Y](https://github.com/ndethore/swift-memory-management) - How to avoid retain cycles, from [this post](http://detho.re/2016/01/21/writing-memory-efficient-swift-code/). ⏳

### Design Patterns

* [Design Patterns Playground ★23](https://github.com/edopelawi/DesignPatternsPlayground) - Learning GoF's Design Patterns in Swift 3.
* [iOS Design Patterns ★39](https://github.com/haxpor/ios-design-patterns) - Sample projects for MVC, MVP, MVVM, and VIPER.
* [Design Patterns in Swift ★9583](https://github.com/ochococo/Design-Patterns-In-Swift) - Design patterns in Swift 3.
* [GOF Swift ★23](https://github.com/SebastianBoldt/Gang-of-Four-and-Solid-Principles-in-Swift) - Learn all 23 Gang of Four patterns using Swift.
* [The Principles of OOD in Swift 4 ★1363](https://github.com/ochococo/OOD-Principles-In-Swift) - The Principles of OOD based on Uncle Bob articles.🍁

### Protocol Oriented Programming

* [Swift Diagram Playgrounds ★249 ⏳1Y](https://github.com/alskipp/Swift-Diagram-Playgrounds) - Adaptation of the Protocol-Oriented Programming in Swift talk from WWDC 2015.
* [Swift Protocol Extensions ★19 ⏳2Y](https://github.com/davidahouse/SwiftProtocolExtensions) - A playground to explore Protocol Extensions. ⏳ 
* [Battleship Example ★9](https://github.com/vichudson1/Battleship-POP-Example) - An example of how to use Protocol Oriented Programming with the battleship game. ⏳ 

### Functional Reactive Programming

* [ReactiveCocoa Playground ★94](https://github.com/nikita-leonov/ReactiveCocoaPlayground) - The easiest way to get a taste of ReactiveCocoa. ⏳ 
* [Swift Reactive Playground ★26 ⏳3Y](https://github.com/ColinEberhardt/SwiftReactivePlayground) - Companion to the article: ReactiveCocoa made Simple With Swift. ⏳ 


## Apple's Playgrounds
*Playgrounds from Apple, usually presented at some WWDC*

* [Apple's Mandelbrot Playground ★11 ⏳1Y](https://github.com/palmerc/Mandelbrot-Swift-Playground) - A playground with the mandelbrot fractal (updated to Swift 3 by @palmerc, @kemalenver).
* [Interactive Newton's Cradle](https://github.com/p-sun/iOS-Effects-and-Animations/tree/master/Newton'sCradle) - Apple's interactive playground of a Newton's Cradle where collisions and gravity are applyed with UIKit dynamics. 🌟 (updated to Swift 3 by @p-sun) 
* [Apple's Balloons Playground](https://developer.apple.com/swift/blog/downloads/Balloons.zip) - The balloons playground showed at WWDC14. ⏳ 
* [Apple's Crustacean Playground](https://developer.apple.com/sample-code/wwdc/2015/downloads/Crustacean.zip) - Protocol-Oriented Programming with Value Types. ⏳ 
* [Apple's Swift Standard Library Playground](https://developer.apple.com/sample-code/swift/downloads/Standard-Library.zip) - experiment with Swift standard library types and high-level concepts using visualizations and practical examples. ⏳ 

## Playgrounds about Playgrounds
*Playgrounds that describe what you can do with playgrounds*

* [XCTest Playground ★45](https://github.com/Liquidsoul/XCTestPlayground) - Better looking tests for playgrounds.
* [Interactive Playground ★49 ⏳1Y](https://github.com/dasdom/InteractivePlayground) - Exploring interactivity in Playgrounds.
* [Mondrian ★3 ⏳2Y](https://github.com/timbellay/Mondrian) - Make iOS app mockups in Swift 2.x playgrounds. ⏳ 

## Playgrounds from Playgroundbooks
*Playgrounds derived from iPad Swift Playgroundbooks*

* [iPad Swift Playgrounds ★15 ⏳1Y](https://github.com/kushtaneja/iPad_Swift_Playgrounds) - The sample playgroundbooks converted to playgrounds.

## Theoretical Computer Science

* [Logician ★115](https://github.com/mdiep/Logician) - Logic programming in Swift. 🌟
* [Function Composition in Swift ★48 ⏳1Y](https://github.com/ijoshsmith/function-composition-in-swift) - Exploration of function composition in Swift. 🌟
* [Functional Debug View ★28](https://github.com/tomquist/DebugView) - Playground to visualize functional programming with graphical sequences. 🍁 🌟
* [Swift Adventures in Monad Land ★164 ⏳1Y](https://github.com/alskipp/Swift-Adventures-In-Monad-Land) - Learn about monads.
* [Functional Design Patterns ★4](https://github.com/cmvicentehe/FunctionalProgrammingDesignPatterns) - A few functional programming concept and patterns.
* [OOP with Functions in Swift ★58](https://github.com/iamleeg/OOPInFPInSwift) - Object-Oriented Programming in Functional Programming in Swift. 🍁
* [Learn about transducers ★79 ⏳3Y](https://github.com/mbrandonw/learn-transducers-playground) - A little tutorial that explains transducers. ⏳ 
* [Swift Functors, Applicatives, and Monads in Pictures ★56 ⏳1Y](https://github.com/mokacoding/Swift-Functors-Applicative-Monads-In-Pictures-Playground) - Companion to the article: Swift Functors, Applicatves, and Monads in Pictures. ⏳ 
* [Functors in Swift ★7 ⏳2Y](https://github.com/mokagio/Swift-Functor-Introduction-Playground) - A playground to introduce Functors in Swift, and their practical usage. ⏳ 

### Algorithms and Data Structures
*Algorithms and data structures implemented in Swift*

* [Swift Algorithm Club ★17207](https://github.com/raywenderlich/swift-algorithm-club) - Algorithms and data structures in Swift with explanations. 🌟
* [Sorting Experiments ★5 ⏳1Y](https://github.com/adrfer/Sort) - Alluring experiments with sorting algorithms in Swift, sort of.
* [Visual Binary Trees ★44 ⏳1Y](https://github.com/akpw/VisualBinaryTrees) - Effortless visualization of arbitrary Binary Trees, along with their pluggable traversal implementations. 🌟
* [Julia Fractal Playground ★203](https://github.com/gongzhang/julia-set-playground#julia-set-playground) - A Swift playground that generates beautiful Julia set fractal images. 
* [A Star ★8](https://github.com/Dev1an/A-Star) - Protocol oriented A* pathfinding algorithm implementation in Swift 4.🍁
* [Sorting Algorithms ★1](https://github.com/bwide/Sorting-Algorithms-Playground) - Live Visualization of some famous sorting algorithms and your experiments.
* [Animated Sorting Algorithms ★3](https://github.com/p-sun/Animated-Sorting-Algorithms) - Swift 4 playgrounds to view and manipulate sorting algorithms.🍁
* [Expressions ★381](https://github.com/mpangburn/Expressions) - Arithmetic and logical expressions elegantly modeled and visualized using protocol-oriented binary trees.🍁
* [DataStructures Playground ★14 ⏳2Y](https://github.com/oliverfoggin/DataStructuresPlayground) - Data Structures and Algorithms in Swift. ⏳
* [Swiftography ★8](https://github.com/sketchytech/Swiftography) - Standard cryptographic algorithms in a Swift Playground. ⏳
* [Algorithms Playground ★3 ⏳3Y](https://github.com/ashokgelal/AlgorithmsPlayground) - Various algorithm implementation in Swift. ⏳
* [The Jelly Bean Problem ★2 ⏳2Y](https://github.com/kyleweiner/Jelly-Bean-Problem) - The Jelly Bean problem from Wait But Why. ⏳
* [Euclidean Strings ★1 ⏳2Y](https://github.com/modulusMathews/ReEuclid) - A playground leveraging ReSwift to generate Euclidean Strings. ⏳

### Languages
*Programming language interpreters implemented in Swift*

* [Introduction to Compilers ★324](https://github.com/ahoppen/introduction-to-compilers) - Great introduction to the inner workings of compilers. 🌟
* [Write your own language: Mu ★1069 ⏳1Y](https://github.com/marciok/Mu) - A playground explaining how to create a tiny programming language named Mu. 🌟
* [ASM Swift ★56 ⏳1Y](https://github.com/NSExceptional/ASM-Swift) - A playground for learning Assembly language through Swift. 🌟
* [Let's build a compiler in Swift ★146](https://github.com/mkchoi212/LBAC-Swift) - Let's Build a Compiler by Jack Crenshaw translated to Swift Playgrounds. 🌟 
* [Pascal interpreter ★224](https://github.com/igorkulman/SwiftPascalInterpreter) - Simple Swift interpreter for the Pascal language inspired by the Let’s Build A Simple Interpreter article series. 🍁
* [Register VM ★4 ⏳2Y](https://github.com/brianhill/register-vm-in-swift) - A register-based VM in a Swift playground. 🌟 ⏳
* [Turtle Playground ★124 ⏳2Y](https://github.com/dimsumthinking/TurtlePlayground) - A playground with Logo-like commands. 🌟 ⏳
* [Swift Brainfuck ★8 ⏳4Y](https://github.com/xavieryao/Swift-Brainfuck) - Brainfuck interpreter written in Swift using Playground. ⏳

### Machine Learning

* [Emoji Intelligence ★1192](https://github.com/BilalReffas/EmojiIntelligence) - Neural Network built in Apple Playground using Swift. 🌟  

## UIKit And Graphics
*A list of playgrounds that demostrate various aspect of UIKit and other graphical frameworks*

* [UIStackView Playground ★298 ⏳1Y](https://github.com/dasdom/UIStackViewPlayground) - Interesting examples of use of UIStackViews.🌟
* [Bezier Path Playgrounds ★22 ⏳1Y](https://github.com/DigitalLeaves/BezierPathPlaygrounds) - Some playgrounds to better understand UIBezierPaths.
* [UIKit playground ★34](https://github.com/ralfebert/uikit-playground) - Playgrounds to experiment interactively with UIKit views.
* [Checkmark Button ★7 ⏳1Y](https://github.com/BilalReffas/CheckmarkButton) - Animated check mark button.
* [UIDynamic Playground ★4 ⏳1Y](https://github.com/andresbrun/UIDynamicsPlayground) - Multiple Playgrounds using almost every behaviour of UIDynamic.
* [WWDC16 Typography ★7 ⏳1Y](https://github.com/tototti/wwdc16_typography_playground) 🇯🇵 - Draw a logo or any text with the WWDC16 ASCII texture.  
* [Animated GIF Playground ★1 ⏳1Y](https://github.com/danielrhammond/GIF-Playground) - Swift playground for generating animated GIFs.
* [RPClarity ★39 ⏳2Y](https://github.com/RobotsAndPencils/RPClarity) - Shows a technique for blurring an image behind the characters behind one or more UILabels. ⏳
* [Swift Clock ★25 ⏳3Y](https://github.com/nickoneill/swiftclock) - An animated clock in a swift playground. ⏳
* [WatchKit Asset Playground ★5 ⏳3Y](https://github.com/cwimberger/WatchKitAssetPlayground) - A swift playground for creating awesome animations for your WatchKit Apps. ⏳
* [Swift 2.0 Protocol Extension Example ★40 ⏳2Y](https://github.com/jhurray/Swift2-Protocol-Extension-Example) - Showing how to use Swift2 protocol extensions to render errors in UIViews and UIViewControllers without subclassing or creating classes. ⏳
* [Tinting ★0 ⏳2Y](https://github.com/Jesse-calkin/tinting) - A small playground to demonstrate image tinting in UIKit. ⏳
* [Ray tracing Playground](https://github.com/mhorga/Raytracing) - A playground and a series of articles on ray tracing, see also part [2](https://github.com/mhorga/Raytracing2), [3](https://github.com/mhorga/Raytracing3), [4](https://github.com/mhorga/Raytracing4), [5 ★4 ⏳2Y](https://github.com/mhorga/Raytracing5) 🌟 ⏳
* [WWDC16 Logo Playground ★3 ⏳1Y](https://github.com/krutarth/WWDC16Logo) - Drawing the WWDC16 logo in a playground. ⏳

### Core Image

* [Interpolation Playground ★44 ⏳2Y](https://github.com/FlexMonkey/Interpolation-Playground-) - Playground demonstrating lerp, smooth step, Catcall-Rom and others! ⏳
* [CoreImage for Swift Playgrounds ★58 ⏳1Y](https://github.com/FlexMonkey/CoreImageForSwiftPlaygrounds) - Growing collection of CoreImage playgrounds from the upcoming book "CoreImage For Swift". 🌟 ⏳
* [Image Processor ★4](https://github.com/mortenbrudvik/ImageProcessor) - Implementing different image filter algorithms. ⏳

### Metal

* [Metalbrot ★71](https://github.com/jtbandes/metalbrot-playground) - Interactive playground that draws the Mandelbrot fractal with Metal. 🌟
* [METAL Playground ★48 ⏳3Y](https://github.com/haawa799/METAL_Playground) - Apple Metal framework playground. 🌟 ⏳

### Animations

* [Core Animation Swift Playgrounds ★29 ⏳1Y](https://github.com/rmirabelli/CoreAnimationSwiftPlaygrounds) - A set of interesting Core Animation playgounds.
* [UIViewPropertyAnimator Playground ★23 ⏳1Y](https://github.com/mathewsanders/Scrubber) - Playground demonstrating UIViewPropertyAnimator.
* [WWDC Crowd Simulator 2017 ★17 ⏳1Y](https://github.com/neilsardesai/WWDC-Crowd-Simulator-2017) - A SpriteKit experiment to simulate the WWDC2017 logo crowd.
* [Duet-Inspired Trail Effect ★14 ⏳1Y](https://github.com/dionlarson/Duet-Trail-Effect-SpriteKit-Playground) - How to get a Duet style trailing effect in SpriteKit.
* [Additive Animations ★31 ⏳4Y](https://github.com/d-ronnqvist/Additive-Animations-Playground) - Experiment with multiple additive animations in Core Animation. ⏳
* [Core Animation Playground ★5 ⏳2Y](https://github.com/knightsc/CoreAnimationPlayground) - Companion to Apple's Core Animation Programming Guide. ⏳

### SpriteKit

* [SpriteKit Swift 3 ★6 ⏳1Y](https://github.com/MacMeDan/SpriteKitCollisions) - Playground for exploring Sprite Kit.
* [SpriteKit Collisions ★27](https://github.com/jaredmpayne/SpriteKitCollisionsPlayground) - Demonstrates how to perform physics collision detection using Swift and SpriteKit. ⏳
* [SceneKit Examples ★14 ⏳3Y](https://github.com/UCh/swift-scene-kit-playgrounds) - Experiment with SceneKit and Swift. ⏳
* [SceneKit ARKit Demo ★30](https://github.com/mhanlon/ARKitDemoPlayground) - The Xcode 9 ARKit SpriteKit demo as a playground.🍁
* [Astronomy ★9](https://github.com/cl7/Astronomy) - A 3D earth model written in swift playground using SceneKit.


## Audio
*Sounds and music*

* [Bach Playground ★2 ⏳1Y](https://github.com/dreamwieber/BachPlayground) - A Simple Swift Playground that plays a brief piece by Bach with AVAudioEngine and AVMIDIPlayer.
* [PlayerNode Playground ★2 ⏳1Y](https://github.com/genedelisa/PlayerNodePlayground) - Playground using AVAudioEngine with a playernode and effects to play an audio file. 🌟
* [Miles ★12](https://github.com/LaloMrtnz/Miles) - A Swift Playground that creates jazz improvisations in any key using AudioToolbox and AVFoundation. 

## Mathematics
*Live math with playgrounds*

* [Lindenmayer Systems ★6 ⏳1Y](https://github.com/henrinormak/lindenmayer) - A Swift playground exploring Lindemayer systems.
* [Swift Natural Numbers ★3 ⏳2Y](https://github.com/jakebromberg/Swift-Natural-Numbers) - A playground for implementing the natural numbers and more concepts in number theory.
* [Polydoxical ★0 ⏳1Y](https://github.com/kirkbyo/Polydoxical) - Interactive playground to experiment with roulettes and polygons.
* [Abstract Algebra ★100](https://github.com/taketo1024/SwiftyMath) - Abstract algebra concepts implemented in Swift.
* [Swift Accelerate ★95 ⏳1Y](https://github.com/haginile/SwiftAccelerate) - Using the Accelerate framework and Swift for Linear Algebra. ⏳
* [Swifty Mathematics ★1 ⏳1Y](https://github.com/DylanModesitt/swiftyMathematics) - A collection of swift playground about mathematics. ⏳
* [Numerical Algorithms](https://www.raywenderlich.com/99559/numeric-algorithms-using-playgrounds) - Numerical argorithms playground from Ray Wenderlich. ⏳
* [Guilloche Pattern Playground Book ★7](https://github.com/TheWildHorse/GuillochePlayground) - Learn more about this pattern you see every day, but probably never knew it was really carefully designed. 🍁

## Libraries and APIs
*Library tutorials, in a playground*

* [AudioKit Playgrounds](http://audiokit.io/playgrounds/) - 130+ Audio synthesis, processing, playback, and analysis playgrounds with AudioKit.
* [AIToolbox](https://github.com/KevinCoble/AIToolbox/tree/master/Playgrounds) - A set of playgrounds showing machine learning algorithms, all implemented with pieces of the AIToolbox framework code.
* [Cognitive Service APIs ★39](https://github.com/codePrincess/playgrounds) - Get started with the Microsoft Cognitive Services APIs.
* [Rx Playground ★2 ⏳1Y](https://github.com/sgr-ksmt/RxPlayground) - A playground with RxSwift examples.

## Playground Sets
*Sets of playgrounds about various topics*

* [Public Extensions ★6 ⏳1Y](https://github.com/Jasdev/Public-Extension) - A set of useful extensions from [@PublicExtension](https://twitter.com/publicextension). 🌟
* [Parks And Recreation ★74](https://github.com/zwaldowski/ParksAndRecreation) - Great collection of interesting playgrounds, for fun and for profit. 🌟
* [URaimo's Playgrounds ★125](https://github.com/uraimo/Swift-Playgrounds) - My playgrounds, various topics.
* [ManuelCarlos's Playgrouds ★5](https://github.com/manuelCarlos/Swift-Playgrounds) - Various playgrounds.
* [Mgrebenets's Playgrounds ★7](https://github.com/mgrebenets/playgrounds) - Various playgrounds.c 🌟
* [Cocoa With Love Playgrounds ★76](https://github.com/mattgallagher/CocoaWithLovePlaygrounds) - Playground versions of select articles from Cocoa with Love.  🌟 
* [Sketchytech's Playgrounds ★9 ⏳2Y](https://github.com/sketchytech/SwiftPlaygrounds) - Various Playgrounds. 🌟 ⏳
* [Swift fun playgrounds ★7 ⏳3Y](https://github.com/madbat/Swift-fun-playgrounds) - A few playgrounds to showcase Swift peculiar features. ⏳
* [BradLarson's Playgrounds ★19 ⏳3Y](https://github.com/BradLarson/PersonalSwiftPlaygrounds) - Various playgrounds. ⏳
* [Dmikusa's Playgrounds ★14 ⏳2Y](https://github.com/dmikusa/swift_playgrounds) - Playgrounds that show basic Swift, JSON parsing, sending HTTP requests and basic file IO. ⏳
* [Cananito's Playgrounds ★1](https://github.com/Cananito/Playgrounds) - Various playgrounds. ⏳
* [Uberbruns's Playgrounds ★4](https://github.com/uberbruns/SwiftPlaygrounds) - Various playgrounds. ⏳

## Miscellaneous
*What doesn't fit anywhere else, but still awesome*

* [Icon Creator ★18](https://github.com/tnantoka/IconCreator) - Create app icons on Swift playground.
* [2048 Playground ★26 ⏳1Y](https://github.com/robin/2048_Playground) - The 2048 game implemented with a playground.
* [SwiftShell ★15](https://github.com/JustinJiaDev/SwiftShell) - Bash shell in a playground.
* [LaunchPad Playground ★3](https://github.com/Juniorlimaivd/LaunchPad-Playground) - A playground that simulates a real LaunchPad for making music.
* [Super Maze ★5 ⏳1Y](https://github.com/W00dL3cs/Super-Maze) - A programmatic maze generator and solver.
* [Tic Tac Toe ★5 ⏳1Y](https://github.com/aabosh/Tic-Tac-Toe) - Tic tac toe in a playground.
* [Pixel Art Maker ★39](https://github.com/BenEmdon/PixelArtMaker) - A playground where you can make pixel art.
* [SwiftCoin ★23](https://github.com/Thomvis/Swiftcoin) - A simplistic blockchain & cryptocurrency in a playground.
* [SentimentlySwift ★3](https://github.com/benbahrenburg/SentimentlySwift) - Sentiment analysis in Swift. 
* [Rubik's Cube ★8](https://github.com/codelynx/CoreRubiksCube) - Implementing basic model and behavior of Rubic's Cube in Swift. 🍁 
* [Game Boards ★161](https://github.com/joalbright/Gameboard) - Chess, checkers, tic-tac-toe, sudoku and many others in playground. 🌟 ⏳
* [StarWars Seals ★3](https://github.com/jeremyconkin/StarWarsSeals) - Emblems from Star Wars in Swift playgrounds via CoreGraphics and UIViews. ⏳
* [SwiftFiles ★33 ⏳2Y](https://github.com/sketchytech/SwiftFiles) - Save, Load and Delete files easily from within a Swift playground. ⏳
* [Earth photos ★4 ⏳2Y](https://github.com/jtbandes/DSCOVR.playground) - A slideshow of Earth photos taken by DSCOVR/EPIC. 🌟 ⏳
* [SwiftChain ★5](https://github.com/gg2001/SwiftChain) - Simple Cryptocurrency in a Swift Playground.


---
<p align="center">
	This list is a copy of <a href="https://github.com/uraimo/Awesome-Swift-Playgrounds">uraimo/Awesome-Swift-Playgrounds</a> with ranks
</p>
