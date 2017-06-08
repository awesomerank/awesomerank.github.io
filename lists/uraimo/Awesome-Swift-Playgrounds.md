<h1 align="center">
Ranked awesome lists, all in one place
</h1>
<p align="center">
	This list is a copy of <a href="uraimo/Awesome-Swift-Playgrounds">uraimo/Awesome-Swift-Playgrounds</a> with ranks
</p>
---
# Awesome Swift Playgrounds [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg) ★59088](sindresorhus/awesome)  ![126 playgrounds](https://img.shields.io/badge/Playgrounds:-126-orange.svg)

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

📱 = iOS Playground book

🍁 = Swift 4+ Playground

⏳ = Pre-Swift 3 Playground

### Contents

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



## Learning Swift
*Some interesting playgrounds to learn Swift*

* [The Swift Programming Language Playgrounds ★125](danielpi/Swift-Playgrounds) - 40+ playgrounds, one for each chapter of Apple's Swift book. 🌟
* [Swift Hack Pack ★6](GuildSA/swift-hack-pack) - Collection of playgrounds that teaches Swift.
* [The Swift Summary Book ★1628](jakarmy/swift-summary) - A summary of Apple's Swift language. 🌟
* [Swifter Tips ★70](swifter-tips/Playground) - Examples for every feature of the Swift language.
* [About Swift ★20](NicolaLancellotti-About/About-Swift) - A playground about Swift language.
* [MPCS51032 UChicago iOS Course ★1](uchicago-mobi/mcps51032-2017-spring-playground) - Playgrounds from the 2017 Spring iOS course of the University of Chicago.
* [What's new in Swift 4 ★951](ole/whats-new-in-swift-4) - An Xcode playground showing off the new features in Swift 4.0. 🍁 🌟 

## Learning Swift: Advanced Topics
*Advanced topics, useful once you have mastered the basics of the language*

* [A Swift Introduction to Core Data ★113](andyshep/CoreDataPlaygrounds) - Learn Core Data experimenting directly in this playground. 🌟
* [TDDSwiftPlayground ★32](sshrpe/TDDSwiftPlayground) - Demonstration of using Swift Playgrounds in Test Driven Development with XCTest.
* [Concurrency on iOS ★11](sammyd/2017AtSwift_Concurrency) - Concurrency and Parallelism in iOS.
* [Modern Core Data ★9](dfreniche/modern-core-data-playground) - An introduction to Core Data.
* [Swift DSL Example ★11](cfdrake/swift-dsl-example) - Implementation of a DSL in Swift.
* [Katan ★13](marciok/katan) - A micro web server that replies "Hello world!" to every request, an example of how to use sockets in Swift.
* [Swiftly Typed Resources ★73 ⏳1Y](jstart/Swiftly-Typed-Resources) - A playground showing how Swift makes Strings, Colors, Fonts, Images, etc easier to deal with. ⏳
* [Swift KVO Closures ★10 ⏳2Y](rectalogic/KVOPlayground) - Swift KVO playground. ⏳ 
* [Swift Date Tutorial ★7 ⏳1Y](liuyubobobo/Swift-NSDate-Tutorial) - Learn everythig about NSDate. ⏳ 
* [Swift And C ★4 ⏳1Y](MacMark/SwiftAndC) - Examples about using C with Swift. ⏳ 
* [Swift Memory Management ★2 ⏳1Y](ndethore/swift-memory-management) - How to avoid retain cycles, from [this post](http://detho.re/2016/01/21/writing-memory-efficient-swift-code/). ⏳

### Design Patterns

* [Design Patterns Playground ★13](edopelawi/DesignPatternsPlayground) - Learning GoF's Design Patterns in Swift 3.
* [iOS Design Patterns ★13](haxpor/ios-design-patterns) - Sample projects for MVC, MVP, MVVM, and VIPER.
* [Design Patterns in Swift ★8067](ochococo/Design-Patterns-In-Swift) - Design patterns in Swift 3.
* [GOF Swift ★8](SebastianBoldt/GOFSwift) - Learn all 23 Gang of Four patterns using Swift.

### Protocol Oriented Programming

* [Swift Diagram Playgrounds ★235](alskipp/Swift-Diagram-Playgrounds) - Adaptation of the Protocol-Oriented Programming in Swift talk from WWDC 2015.
* [Swift Protocol Extensions ★19 ⏳1Y](davidahouse/SwiftProtocolExtensions) - A playground to explore Protocol Extensions. ⏳ 
* [Battleship Example ★8 ⏳1Y](vichudson1/Battleship-POP-Example) - An example of how to use Protocol Oriented Programming with the battleship game. ⏳ 

### Functional Reactive Programming

* [ReactiveCocoa Playground ★88](nikita-leonov/ReactiveCocoaPlayground) - The easiest way to get a taste of ReactiveCocoa. ⏳ 
* [Swift Reactive Playground ★25 ⏳2Y](ColinEberhardt/SwiftReactivePlayground) - Companion to the article: ReactiveCocoa made Simple With Swift. ⏳ 


## Apple's Playgrounds
*Playgrounds from Apple, usually presented at some WWDC*

* [Apple's Mandelbrot Playground ★7](palmerc/Mandelbrot-Swift-Playground) - A playground with the mandelbrot fractal (updated to Swift 3 by @palmerc, @kemalenver).
* [Apple's Balloons Playground](https://developer.apple.com/swift/blog/downloads/Balloons.zip) - The balloons playground showed at WWDC14. ⏳ 
* [Interactive Playgrounds](https://developer.apple.com/swift/blog/?id=35) - Playground that presents the interactive playgrounds feature with a UIKit dynamics Newton's cradle. ⏳ 🌟
* [Apple's Crustacean Playground](https://developer.apple.com/sample-code/wwdc/2015/downloads/Crustacean.zip) - Protocol-Oriented Programming with Value Types. ⏳ 
* [Apple's Swift Standard Library Playground](https://developer.apple.com/sample-code/swift/downloads/Standard-Library.zip) - experiment with Swift standard library types and high-level concepts using visualizations and practical examples. ⏳ 

## Playgrounds about Playgrounds
*Playgrounds that describe what you can do with playgrounds*

* [XCTest Playground ★40](Liquidsoul/XCTestPlayground) - Better looking tests for playgrounds.
* [Interactive Playground ★43](dasdom/InteractivePlayground) - Exploring interactivity in Playgrounds.
* [Mondrian ★3 ⏳1Y](timbellay/Mondrian) - Make iOS app mockups in Swift 2.x playgrounds. ⏳ 

## Playgrounds from Playgroundbooks
*Playgrounds derived from iPad Swift Playgroundbooks*

* [iPad Swift Playgrounds ★9](kushtaneja/iPad_Swift_Playgrounds) - The sample playgroundbooks converted to playgrounds.

## Theoretical Computer Science

* [Logician ★96](mdiep/Logician) - Logic programming in Swift. 🌟
* [Function Composition in Swift ★36](ijoshsmith/function-composition-in-swift) - Exploration of function composition in Swift. 🌟
* [Swift Adventures in Monad Land ★157](alskipp/Swift-Adventures-In-Monad-Land) - Learn about monads.
* [Functional Design Patterns ★3](cmvicentehe/FunctionalProgrammingDesignPatterns) - A few functional programming concept and patterns.
* [Learn about transducers ★76 ⏳2Y](mbrandonw/learn-transducers-playground) - A little tutorial that explains transducers. ⏳ 
* [Swift Functors, Applicatives, and Monads in Pictures ★54](mokacoding/Swift-Functors-Applicative-Monads-In-Pictures-Playground) - Companion to the article: Swift Functors, Applicatves, and Monads in Pictures. ⏳ 
* [Functors in Swift ★7 ⏳1Y](mokagio/Swift-Functor-Introduction-Playground) - A playground to introduce Functors in Swift, and their practical usage. ⏳ 

### Algorithms and Data Structures
*Algorithms and data structures implemented in Swift*

* [Swift Algorithm Club ★12655](raywenderlich/swift-algorithm-club) - Algorithms and data structures in Swift with explanations. 🌟
* [Sorting Experiments ★6](adrfer/Sort) - Alluring experiments with sorting algorithms in Swift, sort of.
* [Visual Binary Trees ★30](akpw/VisualBinaryTrees) - Effortless visualization of arbitrary Binary Trees, along with their pluggable traversal implementations. 🌟
* [Emoji Intelligence ★1003](Luubra/EmojiIntelligence) - Neural Network built in Apple Playground using Swift. 🌟  
* [Julia Fractal Playground ★68](gongzhang/julia-set-playground#julia-set-playground) - A Swift playground that generates beautiful Julia set fractal images. 
* [Tree Trouble Playbook ★3](joelrorseth/Tree-Trouble) - An interactive Swift Playground Book about Binary Search Trees. 📱
* [Auto Pong ★0](cardoso/AutoPong) - A tutorial to implement a pong based on a simple AI. 📱
* [DataStructures Playground ★14 ⏳1Y](oliverfoggin/DataStructuresPlayground) - Data Structures and Algorithms in Swift. ⏳
* [Swiftography ★8 ⏳1Y](sketchytech/Swiftography) - Standard cryptographic algorithms in a Swift Playground. ⏳
* [Algorithms Playground ★3 ⏳2Y](ashokgelal/AlgorithmsPlayground) - Various algorithm implementation in Swift. ⏳
* [Dynamic Programming With Swift ★2 ⏳1Y](evansjohnson/DynamicProgrammingWithSwift) - A set of three dynamic programming problems implemented in a Swift. ⏳
* [The Jelly Bean Problem ★2 ⏳1Y](kyleweiner/Jelly-Bean-Problem) - The Jelly Bean problem from Wait But Why. ⏳
* [Euclidean Strings ★1 ⏳1Y](modulusMathews/ReEuclid) - A playground leveraging ReSwift to generate Euclidean Strings. ⏳
* [Sorting Algorithms ★0](bwide/Sorting-Algorithms-Playground) - Live Visualization of some famous sorting algorithms and your experiments. ⏳

### Languages
*Programming language interpreters implemented in Swift*

* [Introduction to Compilers ★105](ahoppen/introduction-to-compilers) - Great introduction to the inner workings of compilers. 🌟
* [Write your own language: Mu ★1064](marciok/Mu) - A playground explaining how to create a tiny programming language named Mu. 🌟
* [ASM Swift ★43](NSExceptional/ASM-Swift) - A playground for learning Assembly language through Swift. 🌟
* [Register VM ★3 ⏳1Y](brianhill/register-vm-in-swift) - A register-based VM in a Swift playground. 🌟 ⏳
* [Turtle Playground ★123 ⏳1Y](dimsumthinking/TurtlePlayground) - A playground with Logo-like commands. 🌟 ⏳
* [Swift Brainfuck ★8 ⏳3Y](xavieryao/Swift-Brainfuck) - Brainfuck interpreter written in Swift using Playground. ⏳

## UIKit And Graphics
*A list of playgrounds that demostrate various aspect of UIKit and other graphical frameworks*

* [UIStackView Playground ★282](dasdom/UIStackViewPlayground) - Interesting examples of use of UIStackViews.🌟
* [Bezier Path Playgrounds ★16](DigitalLeaves/BezierPathPlaygrounds) - Some playgrounds to better understand UIBezierPaths.
* [UIKit playground ★20](ralfebert/uikit-playground) - Playgrounds to experiment interactively with UIKit views.
* [Checkmark Button ★6](BilalReffas/CheckmarkButton) - Animated check mark button.
* [Window Manager Playground ★31](steventroughtonsmith/windowmanager-playgroundbook) - Playground for an experimental window manager. 📱
* [UIDynamic Playground ★3](andresbrun/UIDynamicsPlayground) - Multiple Playgrounds using almost every behaviour of UIDynamic.
* [WWDC16 Typography ★4](tototti/wwdc16_typography_playground) 🇯🇵 - Draw a logo or any text with the WWDC16 ASCII texture.  
* [Animated GIF Playground ★1](danielrhammond/GIF-Playground) - Swift playground for generating animated GIFs.
* [RPClarity ★38 ⏳1Y](RobotsAndPencils/RPClarity) - Shows a technique for blurring an image behind the characters behind one or more UILabels. ⏳
* [Swift Clock ★21 ⏳2Y](nickoneill/swiftclock) - An animated clock in a swift playground. ⏳
* [WatchKit Asset Playground ★4 ⏳2Y](cwimberger/WatchKitAssetPlayground) - A swift playground for creating awesome animations for your WatchKit Apps. ⏳
* [Swift 2.0 Protocol Extension Example ★42 ⏳1Y](jhurray/Swift2-Protocol-Extension-Example) - Showing how to use Swift2 protocol extensions to render errors in UIViews and UIViewControllers without subclassing or creating classes. ⏳
* [Tinting ★0 ⏳1Y](Jesse-calkin/tinting) - A small playground to demonstrate image tinting in UIKit. ⏳
* [Ray tracing Playground](https://github.com/mhorga/Raytracing) - A playground and a series of articles on ray tracing, see also part [2](https://github.com/mhorga/Raytracing2), [3](https://github.com/mhorga/Raytracing3), [4](https://github.com/mhorga/Raytracing4), [5 ★3 ⏳1Y](mhorga/Raytracing5) 🌟 ⏳
* [WWDC16 Logo Playground ★3](krutarth/WWDC16Logo) - Drawing the WWDC16 logo in a playground. ⏳

### Core Image

* [Interpolation Playground ★35 ⏳1Y](FlexMonkey/Interpolation-Playground-) - Playground demonstrating lerp, smooth step, Catcall-Rom and others! ⏳
* [CoreImage for Swift Playgrounds ★37](FlexMonkey/CoreImageForSwiftPlaygrounds) - Growing collection of CoreImage playgrounds from the upcoming book "CoreImage For Swift". 🌟 ⏳
* [Image Processor ★3 ⏳1Y](mortenbrudvik/ImageProcessor) - Implementing different image filter algorithms. ⏳

### Metal

* [Metalbrot ★44](jtbandes/Metalbrot.playground) - Interactive playground that draws the Mandelbrot fractal with Metal. 🌟
* [METAL Playground ★39 ⏳2Y](haawa799/METAL_Playground) - Apple Metal framework playground. 🌟 ⏳

### Animations

* [Core Animation Swift Playgrounds ★21](rmirabelli/CoreAnimationSwiftPlaygrounds) - A set of interesting Core Animation playgounds.
* [UIViewPropertyAnimator Playground ★13](mathewsanders/Scrubber) - Playground demonstrating UIViewPropertyAnimator.
* [WWDC Crowd Simulator 2017 ★14](neilsardesai/WWDC-Crowd-Simulator-2017) - A SpriteKit experiment to simulate the WWDC2017 logo crowd.
* [Additive Animations ★29 ⏳2Y](d-ronnqvist/Additive-Animations-Playground) - Experiment with multiple additive animations in Core Animation. ⏳
* [Core Animation Playground ★5 ⏳1Y](knightsc/CoreAnimationPlayground) - Companion to Apple's Core Animation Programming Guide. ⏳
* [Duet-Inspired Trail Effect ★10](dionlarson/Duet-Trail-Effect-SpriteKit-Playground) - How to get a Duet style trailing effect in SpriteKit. ⏳

### SpriteKit

* [SpriteKit Swift 3 ★6](MacMeDan/SpriteKitCollisions) - Playground for exploring Sprite Kit.
* [SpriteKit Collisions ★22](jaredmpayne/Sprite-Kit-Collisions-Playground) - Demonstrates how to perform physics collision detection using Swift and SpriteKit. ⏳
* [SceneKit Examples ★10 ⏳2Y](UCh/swift-scene-kit-playgrounds) - Experiment with SceneKit and Swift. ⏳
* [SceneKit ARKit Demo ★0](mhanlon/ARKitDemoPlayground) - The Xcode 9 ARKit SpriteKit demo as a playground.📱🍁


## Audio
*Sounds and music*

* [AudioKit Playground Book ★41](audiokit/AudioKitPlaygroundBook) - A set of playgrounds using AudioKit designed for the iOS10 Playgrounds app. 📱
* [Bach Playground ★2](dreamwieber/BachPlayground) - A Simple Swift Playground that plays a brief piece by Bach with AVAudioEngine and AVMIDIPlayer.
* [PlayerNode Playground ★1](genedelisa/PlayerNodePlayground) - Playground using AVAudioEngine with a playernode and effects to play an audio file. 🌟

## Mathematics
*Live math with playgrounds*

* [Lindenmayer Systems ★4](henrinormak/lindenmayer) - A Swift playground exploring Lindemayer systems.
* [Swift Natural Numbers ★3](jakebromberg/Swift-Natural-Numbers) - A playground for implementing the natural numbers and more concepts in number theory.
* [Numsw ★71](sonsongithub/numsw) - A swift playground book that mimics some of the features of numpy and jupyter notebook. 📱
* [Geometry with Swift ★0](dbbudd/Geometry-Swift-PlaygroundBook) - Learn the basics of geometry and Swift. 📱
* [Polydoxical ★0](kirkbyo/Polydoxical) - Interactive playground to experiment with roulettes and polygons.
* [Abstract Algebra ★32](taketo1024/SwiftyAlgebra) - Abstract algebra concepts implemented in Swift.
* [Swift Accelerate ★84](haginile/SwiftAccelerate) - Using the Accelerate framework and Swift for Linear Algebra. ⏳
* [Swifty Mathematics ★1](DylanModesitt/swiftyMathematics) - A collection of swift playground about mathematics. ⏳
* [Numerical Algorithms](https://www.raywenderlich.com/99559/numeric-algorithms-using-playgrounds) - Numerical argorithms playground from Ray Wenderlich. ⏳

## Libraries and APIs
*Library tutorials, in a playground*

* [AudioKit Playgrounds](http://audiokit.io/playgrounds/) - 130+ Audio synthesis, processing, playback, and analysis playgrounds with AudioKit.
* [AIToolbox](https://github.com/KevinCoble/AIToolbox/tree/master/Playgrounds) - A set of playgrounds showing machine learning algorithms, all implemented with pieces of the AIToolbox framework code.
* [Cognitive Service APIs ★16](codePrincess/playgrounds) - Get started with the Microsoft Cognitive Services APIs.
* [Rx Playground ★2](sgr-ksmt/RxPlayground) - A playground with RxSwift examples.

## Playground Sets
*Sets of playgrounds about various topics*

* [Public Extensions ★197](Jasdev/Public-Extension) - A set of useful extensions from [@PublicExtension](https://twitter.com/publicextension). 🌟
* [Parks And Recreation ★65](zwaldowski/ParksAndRecreation) - Great collection of interesting playgrounds, for fun and for profit. 🌟
* [URaimo's Playgrounds ★93](uraimo/Swift-Playgrounds) - My playgrounds, various topics.
* [ManuelCarlos's Playgrouds ★3](manuelCarlos/Swift-Playgrounds) - Various playgrounds.
* [Sketchytech's Playgrounds ★8 ⏳1Y](sketchytech/SwiftPlaygrounds) - Various Playgrounds. 🌟 ⏳
* [Swift fun playgrounds ★5 ⏳2Y](madbat/Swift-fun-playgrounds) - A few playgrounds to showcase Swift peculiar features. ⏳
* [BradLarson's Playgrounds ★18 ⏳2Y](BradLarson/PersonalSwiftPlaygrounds) - Various playgrounds. ⏳
* [Dmikusa's Playgrounds ★13 ⏳1Y](dmikusa/swift_playgrounds) - Playgrounds that show basic Swift, JSON parsing, sending HTTP requests and basic file IO. ⏳
* [Cananito's Playgrounds ★1 ⏳1Y](Cananito/Playgrounds) - Various playgrounds. ⏳
* [Mgrebenets's Playgrounds ★3](mgrebenets/playgrounds) - Various playgrounds. ⏳
* [Uberbruns's Playgrounds ★2](uberbruns/SwiftPlaygrounds) - Various playgrounds. ⏳

## Miscellaneous
*What doesn't fit anywhere else, but still awesome*

* [Icon Creator ★12](tnantoka/IconCreator) - Create app icons on Swift playground.
* [2048 Playground ★20](robin/2048_Playground) - The 2048 game implemented with a playground.
* [SwiftShell ★10](JustinJiaDev/SwiftShell) - Bash shell in a playground.
* [File Browser Playground ★183](steventroughtonsmith/files-playgroundbook) - Simple File Browser for Swift Playgrounds on iOS.📱
* [LaunchPad Playground ★0](Juniorlimaivd/LaunchPad-Playground) - A playground that simulates a real LaunchPad for making music.
* [Super Maze ★3](W00dL3cs/Super-Maze) - A programmatic maze generator and solver.
* [Pixel Art Maker ★7](BenEmdon/PixelArtMaker) - A playground to make pixel art.
* [Tic Tac Toe ★0](aabosh/Tic-Tac-Toe) - Tic tac toe in a playground.
* [Spacetime Rhapsody ★0](hollisliu/Spacetime-Rhapsody) - A Swift Playground visualizing gravity based on Einstein's Theory of General Relativity. 🌟📱
* [Game Boards ★152 ⏳1Y](joalbright/Gameboard) - Chess, checkers, tic-tac-toe, sudoku and many others in playground. 🌟 ⏳
* [StarWars Seals ★2 ⏳1Y](jeremyconkin/StarWarsSeals) - Emblems from Star Wars in Swift playgrounds via CoreGraphics and UIViews. ⏳
* [SwiftFiles ★29 ⏳1Y](sketchytech/SwiftFiles) - Save, Load and Delete files easily from within a Swift playground. ⏳
* [Earth photos ★2 ⏳1Y](jtbandes/DSCOVR.playground) - A slideshow of Earth photos taken by DSCOVR/EPIC. 🌟 ⏳
---
<p align="center">
	This list is a copy of <a href="uraimo/Awesome-Swift-Playgrounds">uraimo/Awesome-Swift-Playgrounds</a> with ranks
</p>
<script>
  (function(i,s,o,g,r,a,m){i['GoogleAnalyticsObject']=r;i[r]=i[r]||function(){
  (i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),
  m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)
  })(window,document,'script','https://www.google-analytics.com/analytics.js','ga');

  ga('create', 'UA-100705027-1', 'auto');
  ga('send', 'pageview');

</script>
