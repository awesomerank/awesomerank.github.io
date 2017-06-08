<h1 align="center">
Ranked awesome lists, all in one place
</h1>
<p align="center">
	This list is a copy of <a href="JStumpp/awesome-android">JStumpp/awesome-android</a> with ranks
</p>
---
﻿# Awesome Android [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg) ★59088](sindresorhus/awesome)

# [<img src="https://raw.githubusercontent.com/jstumpp/awesome-android/master/awesome-android.png"> ★3961](jstumpp/awesome-android)

A curated list of awesome Android [libraries](#libraries) and [resources](#resources). For general Java libraries have a look at [awesome-java ★12695](akullpp/awesome-java).

- [Emulators](#emulators)
- [Libraries](#libraries)
    - [Charts](#charts)
    - [Cloud Services](#cloud-services)
    - [Dependency Injection](#dependency-injection)
    - [Game Development](#game-development)
    - [GUI](#gui)
        - [ActionBar](#actionbar)
        - [Navigation](#navigation)
        - [Animations](#animations)
        - [Images](#images)
        - [Inputs](#inputs)
        - [Loading images](#loading-images)
        - [Video](#video)
        - [Camera](#camera)
    - [JSON](#json)
    - [Crash monitoring](#crash-monitoring)
    - [Networking](#networking)
    - [Logger](#logger)
    - [Notifications](#notifications)
    - [Database](#database)
        - [ORM](#orm)
    - [REST](#rest)
    - [Testing](#testing)
    - [Tracking](#tracking)
    - [Maps](#maps)
    - [Utility](#utility)
    - [Debugging tools](#debugging-tools)
    - [Wireless](#wireless)
    - [Chat and Messaging](#chat--messaging)
    - [Custom Dialog](#custom-dialog)
    - [Version Checking](#version-checking)
    - [Date & Time](#date--time)
    - [Other](#other)
- [Resources](#resources)
    - [More lists of libraries](#more-lists-of-libraries)
- [Development Alternatives](#development-alternatives)
    - [C#](#c)
    - [HTML, CSS and Javascript](#html-css-and-javascript)
    - [Lua](#lua)
    - [Scala](#scala)
    - [Groovy](#groovy)
    - [Kotlin](#kotlin)
- [Performance](#performance)
- [Other Awesome Lists](#other-awesome-lists)
- [Contributing](#contributing)

## Emulators
- [AMIDuOS](https://www.amiduos.com)
- [AndY](https://andyroid.net)
- [ARChon](https://archon-runtime.github.io)
- [BlueStacks](http://www.bluestacks.com)
- [Genymotion](https://www.genymotion.com)
- [nox](https://www.bignox.com)
- [Xamarin](https://www.xamarin.com)

## Libraries

### Charts

- [AChartEngine ★399](ddanny/achartengine) - Charting Engine.
- [EazeGraph ★1217](blackfizz/EazeGraph) - Chart and graph library.
- [WilliamChart ★3118](diogobernardino/WilliamChart) - Chart library with good motion capabilities.
- [HelloCharts ★4273](lecho/hellocharts-android) - Chart and graph library with support for scaling, scrolling and animations.
- [MPAndroidChart ★15802](PhilJay/MPAndroidChart) - An Android chart and graph library supporting scaling and dragging by gesture.

### Cloud Services

- [CloudRail](https://cloudrail.com) - Unified API Library for: Cloud Storage, Social Profiles, Payment, Email, SMS & POIs.

### Data binding

- [Anvil ★1000](zserge/anvil) - A small library to create reactive UI components, inspired by React. Provides data binding and event listener binding, fits well for MVVM.
- [RoboBinding ★1307](RoboBinding/RoboBinding) - A data-binding Presentation Model (MVVM) framework for the Android platform.
- [Data Binding Library](https://developer.android.com/topic/libraries/data-binding/index.html) - Official Android Data Binding Library to write declarative layouts and minimize the glue code necessary to bind application logic and layouts.

### Dependency Injection

- [RoboGuice ★3878](roboguice/roboguice) - Dependency injection framework for Android.
- [Dagger ★6171](square/Dagger) - Dependency injection framework for Java and Android.
- [Dagger 2 ★7286](google/dagger) - A fast dependency injector for Android and Java.
- [Butter Knife](http://jakewharton.github.io/butterknife/) - View "injection" library for Android.
- [ActivityStarter ★179](MarcinMoskala/ActivityStarter) - Android Library that provide simpler way to start the Activities with multiple arguments.
- [AndroidAnnotations ★9320](androidannotations/androidannotations) - Java annotations with dependency injection at compile time.

### Game Development

- [AndEngine](http://www.andengine.org/) - Free, Fun and Fast Android 2D OpenGL Game Engine.
- [Libgdx](https://libgdx.badlogicgames.com/) - Cross-platform game engine and SDK. [Open Source ★11560](libGDX/libGDX)
- [Vuforia](https://www.vuforia.com/) - Augmented Reality library.
- [Unity](https://unity3d.com/unity/multiplatform) - Cross-platform game creation system.
- [Rajawali ★1383](Rajawali/Rajawali) - Android OpenGL ES 2.0/3.0 Engine

### GUI

- [Pull to refresh](https://developer.android.com/reference/android/support/v4/widget/SwipeRefreshLayout.html) - A swipe refresh layout is available in the v4 support library.
- [Cardslib ★4669](gabrielemariotti/cardslib) - Android Library to build a UI Card.
- [AndroidStaggeredGrid ★4539](etsy/AndroidStaggeredGrid) - Grid view which supports multiple columns with rows of varying sizes.
- [AndroidQuery ★1998](androidquery/androidquery) - Android-Query (AQuery) is a light-weight library for doing asynchronous tasks and manipulating UI elements in Android.
- [Flow ★2258](square/flow) - Library that helps with describing an app as a collection of moderately independent screens.
- [Crouton ★3003 ⏳1Y](keyboardsurfer/Crouton) - Context sensitive notifications for Android
- [DragSortListView ★3104 ⏳1Y](bauerca/drag-sort-listview) - Extension of the Android ListView that enables drag-and-drop reordering (No longer maintained).
- [MaterialProgressBar ★1185](DreaminginCodeZH/MaterialProgressBar) - Material design ProgressBar with consistent appearance.
- [AndroidFillableLoaders ★1596](JorgeCastilloPrz/AndroidFillableLoaders) - Fillable progress view working with SVG paths. Nice option too for creating interesting app logos.
- [NexusDialog ★147](dkharrat/NexusDialog) - Allows you to easily and quickly create forms in Android with little code.
- [Snap RecyclerView Utils ★70](prashantsolanki3/Snap-RecyclerView-Utils) - Populate Single or multiple Layout RecyclerView without creating an Adapter.
- [SwipeableCard ★588](michelelacorte/SwipeableCard) - Implementation of swipe card like StreetView!!
- [ElasticProgressBar ★258](michelelacorte/ElasticProgressBar) - Beautiful loading bar.
- [EntryScreenManager ★26 ⏳1Y](kunall17/EntryScreenManager) - Intro/Entry/Walkthrough/Starting Screens.
- [EasyIntro ★65](meNESS/EasyIntro) - The flexible, easy to use, all in one app intro library for your Android project.
- [Material-Calendar-View ★269](BlackBoxVision/material-calendar-view) - Material Design Calendar compatible with API 8+
- [SectionedRecyclerViewAdapter ★487](luizgrp/SectionedRecyclerViewAdapter) - An Adapter that allows a RecyclerView to be split into Sections with headers and/or footers.
- [DragListView ★243](woxblom/DragListView) - Drag and drop to reorder items in a list, grid or board.
- [Animated Expanding ListView ★121](LeonardoCardoso/Animated-Expanding-ListView) - Animated Expanding ListView provides a fancy animation on expanding or collapsing the content of a listview item.
- [TastyToast ★1474](yadav-rahul/TastyToast) - Toasts with icons and color.
- [DotLoader ★85](bhargavms/DotLoader) - A customizable loading animation with Dots.
- [PodSlider ★89](bhargavms/PodSLider) - A customizable slider widget adhering to material design specs.
- [TapTargetView ★2630](KeepSafe/TapTargetView) - An implementation of tap targets from the Material Design guidelines for feature discovery.
- [MaterialIntroScreen ★1857](TangoAgency/material-intro-screen) - Material Intro Screen implementation with easily extensible API.
- [FloatingView ★1179](UFreedom/FloatingView) - FloatingView can make the target view floating above the anchor view with cool animation.
- [Timecon ★134](alxrm/animated-clock-icon) - Easy-to-use animated clock icon
- [Audiogram ★100](alxrm/audiowave-progressbar) - Lightweight audiowave progressbar
- [Bubbles for Android ★1125](txusballesteros/bubbles-for-android) - Facebook like chat bubble library
- [Litho (By Facebook) ★3360](facebook/litho) - A declarative framework for building efficient UIs on Android.
#### ActionBar
- [ActionBarSherlock](http://actionbarsherlock.com) - ActionBar for older Android versions.
- [FadingActionBar ★2856 ⏳2Y](ManuelPeinado/FadingActionBar) - Fading action bar effect that can be seen in the new Play Music app.

#### Navigation
- [SlidingMenu ★10435](jfeinstein10/SlidingMenu) - Library to create applications with slide-in menus.
- [SlidingTutorial ★1856](Cleveroad/slidingtutorial-android) - Simple library that helps to create awesome sliding android app tutorials.
- [PagerSlidingTabStrip ★6044](astuetz/PagerSlidingTabStrip) - An interactive indicator to navigate between the different pages of a ViewPager.
- [Page View indicator ★8936](JakeWharton/ViewPagerIndicator) - Support for horizontally scrolling ViewPager.
- [MaterialDrawer ★7516](mikepenz/MaterialDrawer) - Simple take on a material design navigation drawer.
- [Debug-Artist ★31](baristaventures/debug-artist) - Debug menu to enable leakcanary, scalpel and others easy.
- [Floating-Navigation-View ★796](andremion/Floating-Navigation-View) - A simple Floating Action Button that shows an anchored Navigation View.

#### Animations
- [NineOldAndroids ★4130 ⏳1Y](JakeWharton/NineOldAndroids) - Library for using the Honeycomb animation API on all versions of the platform back to 1.0.
- [Rebound ★4478](facebook/rebound) - Rebound is a Java library that models spring dynamics.
- [Android View Animations ★7520](daimajia/AndroidViewAnimations) - Cute view animation collection.
- [Android-Transition ★550](kaichunlin/android-transition) - Allows the easy creation of view transitions that react to user inputs.
- [Android-View-Actions ★128](dtx12/AndroidAnimationsActions) - Makes creating complex animations for views easy.
- [Swipper ★58](sdsmdg/Swipper) - Android library for swipeable gestures to control volume , brightness and seek .

#### Images

- [Crescento ★892](developer-shivam/crescento) - Explore new style in material design by adding curve below image view.
- [android-crop ★3570](jdamcd/android-crop) - Library project for cropping images.
- [CircularImageView ★1130 ⏳1Y](Pkmmte/CircularImageView) - Custom view for circular images while maintaining the best draw performance.
- [Android-Image-Filter ★506 ⏳1Y](ragnraok/android-image-filter) - Library project for applying image filters easily.
- [Compressor ★2268](zetbaitsu/Compressor) - Compressor is a lightweight and powerful android image compression library.

#### Inputs

- [FloatingLabel ★229](hardik-trivedi/FloatingLabel) - FloatingLabel Allows you to create a blow kind of EditText. *Doesn't have Gradle or Maven Support.*
- [MaterialEditText ★4178](rengwuxian/MaterialEditText) - Supporting Floating Labels, Single Line Ellipsis, Max/Min Characters, Helper Text and Error Text with Custom Colors.
- [Emojicon ★2748](rockerhieu/emojicon) - Adds emoticons to your app
- [MaterialSearchBar ★995](mancj/MaterialSearchBar) - Material Design Search Bar for Android

#### Loading Images

- [Picasso ★13448](square/picasso) - A powerful image downloading and caching library for Android.
- [Universal Image Loader ★15260](nostra13/Android-Universal-Image-Loader) - Asynchronous, out of the box loading and caching of images.
- [Glide ★15563](bumptech/glide) - An image loading and caching library for Android focused on smooth scrolling, Recommended by Google.
- [Fresco ★12727](facebook/fresco) - An Android library for managing images and the memory they use.
- [Glide Bitmap Pool ★250](amitshekhariitbhu/GlideBitmapPool) - Glide Bitmap Pool is a memory management library for reusing the bitmap memory.
- [MediaPicker ★62](alhazmy13/MediaPicker) - Android Library that lets you to select multiple images, video or voice for Android

#### Video

- [ijkplayer ★13406](Bilibili/ijkplayer) - Android/iOS video player based on FFmpeg n3.2, with MediaCodec, VideoToolbox support.

#### Camera

- [MagicalCamera ★200](fabian7593/MagicalCamera) - Simple way to take or select photos of your gallery, with other features for manage pictures.

### JSON

- [Gson ★8856](google/gson) - Gson is a Java library used for serializing and deserializing Java objects from and into JSON.
- [Jackson JSON Processor ★2917](FasterXML/jackson) - High-performance JSON processor.
- [Moshi ★2784](square/moshi) - A modern JSON library for Android and Java.
### Crash monitoring

- [Fabric Crashlytics](https://get.fabric.io/) - Easy crash reporting solution.
- [HockeyApp](https://www.hockeyapp.net/) - Distribution, Crash Reports, Feedback and Analytics
- [Splunk MINT](https://mint.splunk.com/) - Monitoring, Crash Reports, Real time data, Statistic.
- [Bugsnag](https://www.bugsnag.com/) - Cross platform error monitoring.
- [Catcho ★19](alhazmy13/Catcho) - No Force Close any more.
- [Apteligent](https://www.apteligent.com/) - Cross platform crash reporting/analytics solution. Supports NDK log.
- [Instabug](https://instabug.com/) - Bug reporting, Crash Reporting, In-app Feedback.

### Networking

- [Ion ★5282](koush/ion) - Good networking library for android.
- [OkHttp ★20059](square/okhttp) - An HTTP+SPDY client for Android and Java applications.
- [Asynchronous Http Client ★9830](loopj/android-async-http) - An Asynchronous HTTP Library.
- [RoboSpice ★3012](stephanenicolas/robospice) - Library that makes writing asynchronous network requests easy.
- [IceNet ★67 ⏳2Y](anton46/IceNet) - Fast, Simple and Easy Networking for Android
- [Android Volley](https://developer.android.com/training/volley/index.html) - Official Android HTTP library that makes networking for easier and faster.
- [IceSoap ★67 ⏳1Y](AlexGilleran/IceSoap) - Easy, asynchronous, annotation-based SOAP for Android.
- [node-android ★452](InstantWebP2P/node-android) - Run Node.js on Android.
- [HappyDns ★121](qiniu/happy-dns-android) - A Dns library, user can use custom dns server, dnspod httpdns. Only support A record.
- [RESTMock ★405](andrzejchm/RESTMock) - HTTP Web server for mocking API responses in Android Instrumentation tests.
- [Packetzoom](https://packetzoom.com/blog/introducing-http-optimizer-and-analytics-service.html) - SDK for optimizing HTTP requests and free analytics service for networking.
- [Fast-Android-Networking ★1711](amitshekhariitbhu/Fast-Android-Networking) - A Complete Fast Android Networking Library that also support HTTP/2.

### Logger
- [logger ★6518](orhanobut/logger) - Simple, pretty and powerful logger for android
- [timber ★4090](JakeWharton/timber) - A logger with a small, extensible API which provides utility on top of Android's normal Log class.
- [LoggingInterceptor ★398](ihsanbal/LoggingInterceptor) - An OkHttp interceptor which pretty logs request and response data.
- [Bugfender ★11](bugfender/BugfenderSDK-android-sample) - Upload your logs and check them online, specially made for mobile
- [EzyLogger ★2](afiqiqmal/EzyLogger) - Simple Lightweight logger

### Notifications
- [android-remote-notifications ★68 ⏳1Y](kaiwinter/android-remote-notifications) - Pulls notifications from a remote JSON file and shows them in your app.
- [Android HeartBeat Fixer ★38 ⏳1Y](joaopedronardari/AndroidHeartBeatFixer) - Way to set heartbeat interval and users receive PushNotifications from GCM.

### Database
- [Cupboard](https://bitbucket.org/littlerobots/cupboard) - Access the sqlite easily via direct database access or through the ContentProvider framework.
- [DbInspector ★745](infinum/android_dbinspector) - Provides a simple way to view the contents of the in-app database for debugging purposes.
- [SQLite Asset Helper ★1797](jgilfelt/android-sqlite-asset-helper) - manage database creation and version management using an application's raw asset files.
- [Realm ★7782](realm/realm-java) - The alternative to SQLite and ORMs: Simple, modern and fast! Object oriented API and multi platform support.
- [Realm Asset Helper ★19](eggheadgames/android-realm-asset-helper) - Copies a realm database from the apk assets folder. Efficiently handles versioning of read-only realm databases.
- [RestorableSQLiteDatabase ★15 ⏳1Y](yaa110/RestorableSQLiteDatabase) - A wrapper to replicate android's SQLiteDatabase with restoring capability.

#### ORM

- [requery ★1929](requery/requery) - Compile time ORM and SQL query library for Java & Android.
- [GreenDAO](http://greenrobot.org/greendao/) - Light & fast ORM solution.
- [ORMLite](http://ormlite.com/sqlite_java_android_orm.shtml) - Lightweight ORM Java package for JDBC and Android.
- [ActiveAndroid](http://www.activeandroid.com) - Active record style ORM.
- [Sugar ORM](http://satyan.github.io/sugar/) - Insanely easy way to work with Android Databases.
- [DBFlow ★3471](Raizlabs/DBFlow) - Fast and powerful ORM with compile-time annotation processing.
- [NexusData ★71 ⏳2Y](dkharrat/NexusData) - Object graph and persistence framework for Android.
- [SimpleNoSQL ★396](Jearil/SimpleNoSQL) - A simple NoSQL client for Android. Meant as a document store using key/value pairs and some rudimentary querying. Useful for avoiding the hassle of SQL code.
- [RxSimpleNoSQL ★35](xmartlabs/RxSimpleNoSQL) - Reactive extensions for SimpleNoSQL. Manipulate entities using Observables.

### REST

- [Retrofit](http://square.github.io/retrofit/) - Retrofit turns your REST API into a Java interface.
- [Spring for Android - Rest Template ★651 ⏳1Y](spring-projects/spring-android) - A Rest Client for Android.

### Testing

- [Robotium ★2139](robotiumtech/robotium) - Test automation framework for black-box UI tests.
- [Roboletric](http://robolectric.org/) - Unit test framework to run tests inside the JVM on your workstation, not in the emulator.
- [AssertJ Android ★1473](square/assertj-android) - AssertJ assertions geared towards Android.
- [Green Coffee ★154](mauriciotogneri/green-coffee) - Run your Cucumber tests in your Android instrumentation tests.

### Tracking

- [MobileAppTracking](https://www.tune.com/) - Tracking your marketing campaigns across multiple ad networks.
- [Mixpanel](https://mixpanel.com/) - Analytics platform to analyze the users.
- [Countly](https://count.ly) - Open source mobile & web analytics, push notifications and crash reporting platform, based on Node.js, MongoDB and Linux.
- [CleverTap](https://clevertap.com) - Analytics platform and user-engagement platform with 1 million free events

### Maps

- [Google-Directions-Android ★639](jd-alexander/Google-Directions-Android) - Allows you to calculate the direction between two locations and display the route on a Google Map using the Google Directions API.
- [Android Maps Extensions ★347](mg6maciej/android-maps-extensions) - Extending capabilities of Google Maps Android API v2, adding marker clustering among other things
- [Clusterkraf ★267 ⏳2Y](twotoasters/clusterkraf) - Clustering library for the Google Maps Android API v2
- [MapScaleView ★36](pengrad/MapScaleView) - Scale bar for Google Maps Android API

### Utility

- [Conceal SharedPreferences ★24](afiqiqmal/ConcealSharedPreference-Android) - Secured Preferences using Facebook Secure Encryption called Conceal.
- [EventBus](http://greenrobot.github.io/EventBus/) - EventBus is a library that simplifies communication between different parts of your application.
- [Otto ★4809](square/otto) - Event Bus for Android.
- [Weak handler ★1065 ⏳1Y](badoo/android-weak-handler) - Memory safer implementation of android.os.Handler.
- [Byte Buddy](http://bytebuddy.net) - Runtime code generation library with support for Android.
- [Secure Preference Manager ★65](prashantsolanki3/Secure-Pref-Manager) - Secure Preference Manager for android. It uses various Encryption to protect your application's Shared Preferences.
- [LeakCanary ★15263](square/leakcanary) - Catch memory leaks as they occur.
- [Drekkar ★14 ⏳1Y](coshx/drekkar) - An Android event bus for WebView and JS.
- [Androl4b ★378](sh4hin/Androl4b) - A vm for assessing android applications.
- [DroidMVP ★204](andrzejchm/DroidMVP) - Android library to help you incorporate MVP along with Passive View and Presentation Model patterns into your app.
- [Gota ★41](alhazmy13/Gota) - Simplifying Android Permissions.
- [EasyDeviceInfo ★1079](nisrulz/easydeviceinfo) - Get device information in a super easy way.


### Debugging Tools

- [Linx ★534](pedrovgs/Lynx) - Show logcat inside the device for debug builds
- [Scalpel ★2098](JakeWharton/scalpel) - View the entire hierarchy in 3d in the phone.
- [Stetho ★7694](facebook/stetho) - Debug hierarchy and network from chrome.
- [Android Debug Database ★2228](amitshekhariitbhu/Android-Debug-Database) - Android Debug Database is a powerful library for debugging databases and shared preferences in Android applications.

### Wireless

- [SmartGattLib ★208](movisens/SmartGattLib) - Simplifies the work with Bluetooth SMART devices (a.k.a. Bluetooth Low Energy in Bluetooth 4.0).

### Chat & Messaging

- [Applozic Android Chat SDK ★375](AppLozic/Applozic-Android-SDK) - Android Chat and Messaging SDK for adding real time chat and in-app messaging into your android application.
- [Qiscus SDK ★98](qiscus/qiscus-sdk-android) - Qiscus SDK is a lightweight and powerful android chat library. Qiscus SDK will allow you to easily integrating Qiscus engine with your apps to make cool chatting application.

#### Custom Dialog

- [MediaRecorderDialog ★38](alhazmy13/MediaRecorderDialog) - Custom Dialog to record audio, store it and play it in your phone.
- [HijriDatePicker ★39](alhazmy13/HijriDatePicker) - offers a hijri (Islamic Calendar) Date Picker designed on Google's Material Design Principals For Pickers.
- [Noty ★4](emre1512/Noty) - A simple library for creating animated alerts/dialogs/warnings.

### Version Checking

 - [AppUpdater ★717](javiersantos/AppUpdater) - comprehensive and feature rich library, including support for checks at Amazon and FDroid.
 - [Gandalf ★261](btkelly/gandalf) - comprehensive features and a "companion" iOS solution.
 - [Siren ★55](eggheadgames/Siren) - focused feature set that mimicks the popular iOS library of the same name. Supports Play and Amazon.
 - [Fit ★53](KeithYokoma/Fit) - version checking callback framework with no UI.

### Date & Time

- [ThreeTen Android Backport ★1532](JakeWharton/ThreeTenABP) - An adaptation of the JSR-310 backport for Android.
- [Joda-Time Android ★1926](dlew/joda-time-android) - Joda-Time library with Android specialization.
- [True Time ★448](instacart/truetime-android) - Android NTP time library. Get the true current time impervious to device clock time changes.

### Other

- [Android Support library](https://developer.android.com/topic/libraries/support-library/index.html) - The Android Support Library package is a set of code libraries that provide backward-compatible versions of Android framework API.
- [Google Play Services](https://developers.google.com/android/guides/overview) - Library to access Google services, such as account syncing, Google+ (sharing, single sign-on), Google Maps, Location APIs, Google Play Games, Cloud Messaging, Android Device Manager, and others.
- [Tape ★1843](square/tape) - A lightning fast, transactional, file-based FIFO for Android and Java.
- [Guava: Google Core Libraries for Java ★16658](google/guava) - Collections, caching, primitives support, concurrency libraries, common annotations, string processing, I/O, and so forth.
- [Android Scripting ★1309](damonkohler/sl4a) - Allows to run scripting languages on Android.
- [Android Priority Job Queue ★2365 ⏳1Y](path/android-priority-jobqueue) - Implementation of a Job Queue to easily schedule jobs (tasks) that run in the background, improving UX and application stability.
- [RateMeMaybe ★92 ⏳4Y](nspo/RateMeMaybe) - Asks the user if (s)he wants to open the Play Store to rate your application.
- [Easy Rating Dialog ★89](fernandodev/easy-rating-dialog) - Lib provides a simple way to display an alert dialog for rating app.
- [ZXing Android-Integration ★13660](zxing/zxing) - Integration with Barcode Scanner via Intent.
- [Gradle Retrolambda Plugin ★4773](evant/gradle-retrolambda) - Java 8 Lambdas on Android!
- [RxJava ★24565](ReactiveX/RxJava)- RxJava – Reactive Extensions for the JVM – a library for composing asynchronous and event-based programs using observable sequences for the Java VM.
- [Caffeine ★413](percolate/caffeine) - A collection of utility classes that help make Android development faster.
- [AboutLibraries ★1766](mikepenz/AboutLibraries) - Automatically generates an About this app section, with a list of used libraries.
- [AudioPlayerView ★76 ⏳1Y](HugoMatilla/AudioPlayerView) - A view that loads audio from an url and have basic playback tools.
- [andle ★42](Jintin/andle) - command line tool help you sync dependencies, sdk or build tool version.
- [Typography ★40 ⏳1Y](workarounds/typography) - An Android library that makes it easy to use custom fonts in views.
- [Calligraphy ★6286](chrisjenx/Calligraphy) - Custom fonts in Android an OK way.
- [transai ★38](Jintin/transai) - command line tool help you manage localization string files.
- [Android-Link-Preview ★214](LeonardoCardoso/Android-Link-Preview) - It makes a preview from an url, grabbing all the information such as title, relevant texts and images.
- [Sensey ★1930](nisrulz/sensey) - Detecting gestures in a snap.
- [UserAwareVideoView ★43](kevalpatel2106/UserAwareVideoView) - A customized video view that will automatically pause video is user is not looking at device screen!

## Resources

- [Vogella Tutorials](http://www.vogella.com/tutorials/android.html) - Very good tutorials by Lars Vogel.
- [Android Design in Action Video series](https://www.youtube.com/playlist?list=PLWz5rJ2EKKc8j2B95zGMb8muZvrIy-wcF) The video series by Android Design Team of Google.
- [Android Design in Action slides](https://play.google.com/store/apps/details?id=com.astuetz.android.adia&feature=md)- The application that gives you access to the slides of the video series.
- [Android DevBytes Video Series](https://www.youtube.com/playlist?list=PLWz5rJ2EKKc_XOgcRukSoKKjewFJZrKV0) - It is the technical counterpart of Android Design in Action series.
- [Developing for Android](https://medium.com/google-developers/developing-for-android-introduction-5345b451567c) - A series of articles from Googler Chet Hasae and others, answering most commonly asked question: "What are some of the important rules to keep in mind when developing Android applications?".
- [Android Hive Tutorials](http://www.androidhive.info) - Very good tutorials for beginners.
- [Android Weekly](http://androidweekly.net) - Newsletter with weekly information about android.
- [Android Asset Studio](http://romannurik.github.io/AndroidAssetStudio/) - Generator for icons and other assets.
- [Android Action Bar Style Generator](http://jgilfelt.github.io/android-actionbarstylegenerator/).
- [Device Art Generator](https://developer.android.com/distribute/marketing-tools/device-art-generator.html) - Wraps app screenshots in real device artwork.
- [Android UI design resources](https://androiduiux.com/free-design-resources/) - Gives you wide variety of design resources form a Google Developer Expert in UI/UX.
- [Pencil Project](http://pencil.evolus.vn/) - An open source prototyping software.
- [Google Wear App ★9 ⏳2Y](mbcrump/FirstGoogleWearableApp) - This is an open source Google Wear App that uses speech recognition to calculate a tip.
- [How to Make Android Apps](https://www.youtube.com/playlist?list=PLGLfVvz_LVvSPjWpLPFEfOCbezi6vATIh) - Video tutorials by Derek Banas.
- [android-blogs ★354](vbauer/android-blogs) - List with blogs about Android.
- [Future Studio](https://futurestud.io/tutorials/tag/android) - Extensive Android tutorials on Retrofit, Picasso, Glide & Gson.
- [Android Tips & Tricks ★2212](nisrulz/android-tips-tricks) - Cheatsheet about tips and tricks for Android Development.

### Podcast
- [Fragmented](http://fragmentedpodcast.com/)  is the Android developer podcast where Donn Felker and Kaushik Gopal talk about building good software and becoming better Android developers.
- [Android Developers Backstage](http://androidbackstage.blogspot.com/) is a podcast by and for Android developers. Hosted by developers from the Android engineering team, this show covers topics of interest to Android programmers, with in-depth discussions and interviews with engineers on the Android team at Google.
- [Android Dialogs](https://www.youtube.com/channel/UCMEmNnHT69aZuaOrE-dF6ug/feed) is a video based podcast, where they have bite-sized conversations with people from the Android community.
- [Android Intelligence](https://plus.google.com/collection/ATg6b) features in-depth interviews with interesting people from the Android world.
- [The Context ★427](artem-zinnatullin/TheContext-Podcast) a podcast about Android Development with Hannes Dorfmann, Artem Zinnatullin and wonderful guests!


### More lists of libraries
- [The Android Arsenal](https://android-arsenal.com/) - Large list of android libraries
- [Square libraries](http://square.github.io/#android) - Multiple high quality libraries by square.
- [Awesome Android @LibHunt](https://android.libhunt.com) - Your go-to Android Toolbox.

## Development Alternatives

My personal recommendation is (for now) to use the android api to build a native app. Scala can help to build this native apps with cleaner code but it adds to many methods (Multidex required). Kotlin is a modern language with 100% interoperatibility with java projects **without multidex**. But there are also use cases where alternatives like cross-platform development can be useful.

### C&#35;

- [Xamarin](https://www.xamarin.com/) - Framework to create native iOS, Android, Mac and Windows apps in C#.

### HTML, CSS and Javascript

- [PhoneGap](https://phonegap.com) - Open source framework by Adobe to create cross platform mobile apps using HTML, CSS, and JavaScript.
- [Titanium](http://www.appcelerator.com/mobile-app-development-products/) - Open-source framework to create 'native' cross platform apps using JavaScript.
- [NativeScript](https://www.nativescript.org/) - An open-source framework to build native iOS and Android apps with JavaScript from a single code base.
- [React Native ★48867](facebook/react-native) - A framework for building native apps with React by Facebook.
- [Ionic Framework](http://ionicframework.com) - A framework to build hybrid apps with mobile-optimized HTML, CSS and JS with AngularJS.
- [Apache Cordova ★1905](apache/cordova-android) - Cordova based applications are, at the core, applications written with web technology: HTML, CSS and JavaScript.
- [Reapp.io](http://reapp.io/) - Cordova based framework to build hybrid apps with mobile-optimized HTML, CSS and JS with ReactJS.

### Lua
- [Corona SDK](https://coronalabs.com/corona-sdk/) - Framework to create native iOS and Android Apps (especially Games).

### Scala
- [Scaloid ★2072](pocorall/scaloid) - Library for less painful Android development with Scala.
- [Macroid ★518](47deg/macroid) - A modular functional UI language for Android.

### Groovy
- [Groovy on Android](http://melix.github.io/blog/2014/06/grooid.html) - Introduction to Groovy on Android.
- [Groovy Language Support for Android ★694](groovy/groovy-android-gradle-plugin) - Gradle Plugin for Compiling Groovy for Android.
- [SwissKnife ★254 ⏳1Y](Arasthel/SwissKnife) - A multi-purpose Groovy library containing view injection and threading for Android using annotations.

### Kotlin
- [Anko ★5736](Kotlin/anko) - DSL for Android written in Kotlin by JetBrains.
- [Kotterknife ★1111](JakeWharton/kotterknife) - Android view injection written in Kotlin based on ButterKnife
- [Android Kotlin Samples ★169 ⏳1Y](irontec/android-kotlin-samples) - Some basic Android code samples written in Kotlin.
- [KAndroid ★497](pawegio/KAndroid) - Lightweight library providing useful extensions to eliminate boilerplate code in Android SDK.
- [RxKotlin/Pocket ★12](RxKotlin/Pocket) - This app help user to save links easily, and can export to Evernote as weekly.

# Performance
- [awesome-android-performance ★2096](Juude/awesome-android-performance) - A list of awesome Android tutorials, videos and tools for performance optimization.

# Other Awesome Lists
Other amazingly awesome lists can be found in the [awesome-awesomeness ★18868](bayandin/awesome-awesomeness) list.

## Contributing

Your contributions are always welcome! Please read the [contribution guidelines](https://github.com/JStumpp/awesome-android/blob/master/contributing.md) first.
---
<p align="center">
	This list is a copy of <a href="JStumpp/awesome-android">JStumpp/awesome-android</a> with ranks
</p>
<script>
  (function(i,s,o,g,r,a,m){i['GoogleAnalyticsObject']=r;i[r]=i[r]||function(){
  (i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),
  m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)
  })(window,document,'script','https://www.google-analytics.com/analytics.js','ga');

  ga('create', 'UA-100705027-1', 'auto');
  ga('send', 'pageview');

</script>
