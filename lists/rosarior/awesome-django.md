<h1 align="center">
Ranked awesome lists, all in one place
</h1>
<p align="center">
	This list is a copy of <a href="rosarior/awesome-django">rosarior/awesome-django</a> with ranks
</p>
---
# <a href="http://awesome-django.com"><img src="https://raw.githubusercontent.com/rosarior/awesome-django/gh-pages/images/logo-small.png" align="absmiddle"/> Awesome Django</a>

[![Build Status](https://travis-ci.org/rosarior/awesome-django.svg)](https://travis-ci.org/rosarior/awesome-django)

This project is being migrated to GitLab: https://gitlab.com/rosarior/awesome-django. The GitHub repository will be removed once all tickets are closed.

A curated list of awesome Django apps, projects and resources.

*Q: What is an awesome Django package?*

**A: An awesome package is one that is mature (not recently released), is well
maintained, has a good amount of users, has good documentation, follows the best
practices, and which latest release is less than 1 year old. Awesome Django packages
and projects are the ones that inspire and serve as examples.**

Twitter feed: [twitter.com/AwesomeDjango](https://twitter.com/AwesomeDjango)

- [Awesome Django](#awesome-django)
    - [Admin Interface](#admin-interface)
    - [Analytics](#analytics)
    - [Asset Management](#asset-management)
    - [Authentication](#authentication)
    - [Authorization](#authorization)
    - [Blog Management](#blog-management)
    - [Boilerplate](#boilerplate)
    - [Caching](#caching)
    - [Compatibility](#compatibility)
    - [Dashboards](#dashboards)
    - [Data Sciences](#data-sciences)
    - [Database](#database)
    - [Debugging](#debugging)
    - [Email](#email)
    - [Fields](#fields)
    - [File Transfers](#file-transfers)
    - [Forms](#forms)
    - [GIS](#gis)
    - [Image handling](#image-handling)
    - [Import/Export](#importexport)
    - [Migrations](#migrations)
    - [Mobile Support](#mobile-support)
    - [Model Extensions](#model-extensions)
    - [Multitenancy](#multitenancy)
    - [Payment Processing](#payment-processing)
    - [Project Management](#project-management)
    - [Reporting](#reporting)
    - [RESTful API](#restful-api)
    - [SEO](#seo)
    - [Search](#search)
    - [Security](#security)
    - [Settings](#settings)
    - [Storage](#storage)
    - [Tagging](#tagging)
    - [Task Queue](#task-queue)
    - [Testing](#testing)
    - [Thumbnail](#thumbnail)
    - [Translations](#translations)
    - [Views](#views)
    - [Web frontend integration](#web-frontend-integration)
    - [Wiki apps](#wiki-apps)
    - [Workflows](#workflows)
    - [WYSIWYG Editors](#wysiwyg-editors)
    - [Other](#other)
- [Projects](#projects)
    - [CMS](#cms)
    - [Document Management](#document-management)
    - [Project Management](#project-management)
    - [e-Commerce](#e-commerce)
    - [Other](#other)
- [Resources](#resources)
    - [Books](#books)
    - [Conferences](#conferences)
    - [External documentation](#external-documentation)
    - [Videos](#videos)
    - [Websites](#websites)
- [Utilities](#utilities)
- [Contributing](#contributing)

## Admin interface

*Packages that extend the Admin interface, adding or improving features.*

* [djamin ★214 ⏳1Y](hersonls/djamin) - A new style for Django admin.
* [django-admin-bootstrap ★476](django-admin-bootstrap/django-admin-bootstrap) - Responsive Skin for Django Admin
* [django-admin-bootstrapped ★1360](django-admin-bootstrapped/django-admin-bootstrapped) - A Django admin theme using Twitter Bootstrap.
* [django-admin-easy ★72](ebertti/django-admin-easy) - Collection of admin fields and decorators.
* [django-admin-interface ★85](fabiocaccamo/django-admin-interface) - The ultimate admin interface, based on a modern flat theme, it lets you customize the admin title, logo and colors by the admin itself.
* [django-admin-tools ★229](django-admin-tools/django-admin-tools) - A collection of extensions/tools for the default django administration interface
* [django-admin2 ★952](jazzband/django-admin2) - Extendable, adaptable rewrite of django.contrib.admin
* [django-flat-theme ★393](elky/django-flat-theme) - A flat theme for Django admin interface. Modern, fresh, simple. ([merged into Django 1.9+](https://docs.djangoproject.com/en/1.9/releases/1.9/#new-styling-for-contrib-admin))
* [django-flat-responsive ★161](elky/django-flat-responsive) - An extension for Django admin and django-flat-theme that makes interface mobile friendly.
* [django-fluent-dashboard ★168](django-fluent/django-fluent-dashboard) - An improved django-admin-tools dashboard for Django projects
* [django-grappelli ★2102](sehmaschine/django-grappelli) - A jazzy skin for the Django Admin-Interface.
* [django-hijack ★545](arteria/django-hijack) - Allows superusers to hijack (=login as) and work on behalf of another user.
* [django-jet ★844](geex-arts/django-jet) - Modern responsive template for the admin interface with improved functionality.
* [django-material ★1067](viewflow/django-material) Material design for Django Forms and Admin. Template driven.
* [django-object-actions ★167](crccheck/django-object-actions) A Django app for adding object tools for models in the admin
* [django-suit ★1242](darklow/django-suit) - Modern theme for Django admin interface.
* [django-wpadmin ★203](barszczmm/django-wpadmin) - WordPress look and feel for Django administration panel.
* [django-xadmin ★2065](sshwsfc/xadmin) - Drop-in replacement of Django admin comes with lots of goodies, fully extensible with plugin support, pretty UI based on Twitter Bootstrap
* [yawd-admin ★130](yawd/yawd-admin) - An administration website for Django

## Analytics

*Packages that do web analytics or integrate web analytics services.*

* [django-analytical ★474](jcassee/django-analytical) - Integrates analytics services with a generic interface, templates stay clean.

## Asset Management

*Packages that help manage the static assets of a project.*

* [django-compressor ★1866](django-compressor/django-compressor) - Compresses linked and inline javascript or CSS into a single cached file.
* [django-gears ★54 ⏳2Y](gears/django-gears) - Compiles and concatenates JavaScript and CSS assets.
* [django-htmlmin ★342](cobrateam/django-htmlmin) - HTML minifier for Python with full support for HTML 5 and Django.
* [django-pipeline ★1150](jazzband/django-pipeline) - Asset packaging for Django.
* [django-systemjs ★42](sergei-maertens/django-systemjs) - Django SystemJS brings the Javascript of tomorrow to Django, today. (JSPM integration in Django)
* [django-webpack-loader](https://github.com/owais/django-webpack-loader/) - Transparent webpack integration for django.
* [python-webpack ★58 ⏳1Y](markfinger/python-webpack) - Python bindings for webpack with django integration.

## Authentication

*Packages that improve or extend the authentication methods of Django.*

* [django-allauth ★3041](pennersr/django-allauth) - Integrated set of Django applications addressing authentication, registration, account management as well as 3rd party (social) account authentication.
* [django-organizations ★345](bennylope/django-organizations) - Multi-user accounts for Django projects.
* [django-otp](https://bitbucket.org/psagers/django-otp/) - A pluggable framework for adding two-factor authentication to Django using one-time passwords.
* [django-registration ★556](macropin/django-registration) -  Simple user-registration application for Django, designed to make allowing user signups as painless as possible.
* [django-rest-auth ★831](Tivix/django-rest-auth) -  A set of REST API endpoints to handle User Registration and Authentication tasks.
* [django-two-factor-auth ★402](Bouke/django-two-factor-auth) - User-friendly Two-Factor authentication.
* [django-userena ★1177](bread-and-pepper/django-userena) - Accounts for Django made beautifully simple
* [python-social-auth ★2651](omab/python-social-auth) - Python Social Auth is an easy-to-setup social authentication/registration mechanism with support for several frameworks and auth providers.

## Authorization

*Packages related to authorization infrastructure and permissions.*

* [django-guardian ★1448](django-guardian/django-guardian) - Implementation of per object permissions as authorization backend.
* [django-oauth-toolkit ★977](evonove/django-oauth-toolkit) - OAuth2 goodies for the Djangonauts!
* [django-oauth2-provider ★304](caffeinehit/django-oauth2-provider) - Provide OAuth2 access to your app
* [django-oml ★10 ⏳1Y](angvp/django-oml) - Object Moderation Layer, mixin for models that allows you moderate several content types.
* [django-permission ★231](lambdalisue/django-permission) An enhanced permission library which enables a *logic-based permission system* to handle complex permissions in Django
* [django-rules ★447](dfunckt/django-rules) - A tiny but powerful app providing object-level permissions to Django, without requiring a database. At its core, it is a generic framework for building rule-based systems, similar to decision trees. It can also be used as a standalone library in other contexts and frameworks.

## Blog Management

*Packages to build and manage a blog app.*

* [django-blog-zinnia ★1460](Fantomas42/django-blog-zinnia) -  Simple yet powerful and really extendable application for managing a blog within your Django Web site.
* [puput ★191](APSL/puput) - A Django blog app implemented in Wagtail.

## Boilerplate

*Packages related to starting a new project.*

* [cookiecutter ★5128](audreyr/cookiecutter) - A command-line utility that creates projects from cookiecutters (project templates).
* [django-hackathon-starter ★1026](DrkSephy/django-hackathon-starter) - A boilerplate for Django web applications, containing various social authentication methods and several popular API examples.
* [edge ★463](arocks/edge) - A Django project skeleton that is modern and cutting edge.

## Caching

*Packages that help with caching.*

* [django-cachalot ★458](BertrandBordage/django-cachalot) - Caches your Django ORM queries and automatically invalidates them.
* [django-cache-machine ★660](django-cache-machine/django-cache-machine) - Automatic caching and invalidation for Django models through the ORM.
* [django-cacheops ★679](Suor/django-cacheops) - A slick ORM cache with automatic granular event-driven invalidation.
* [django-memoize ★46](tvavrys/django-memoize) - An implementation of [memoization](https://en.wikipedia.org/wiki/Memoization) technique for Django.
* [django-ormcache ★13](educreations/django-ormcache) - A cache manager mixin that provides some caching of objects for the ORM.
* [django-redis-cache ★755](sebleier/django-redis-cache) - A Redis cache backend for django.
* [johnny-cache ★266 ⏳1Y](jmoiron/johnny-cache) - Johnny Cache is a caching framework for django applications.
* [diskcache](http://www.grantjenks.com/docs/diskcache/) - Fast SQLite and file backed cache backend for Django.

## Compatibility

*Packages that help to keep compatibility of reusable apps between different Django versions.*

* [django-compat ★90](arteria/django-compat) - For- and backwards compatibility layer for the officially  supported Django versions.
* [django-compat-lint ★37 ⏳1Y](ubernostrum/django-compat-lint) - Check Django compatibility of your code.

## Dashboards

*Packages that create information dashboards to visualize data.*

* [django-dashing ★395](talpor/django-dashing) - a customisable, modular dashboard application framework for Django to visualize interesting data about your project. Inspired in the exceptionally handsome dashboard framework Dashing.

## Data sciences

*Packages that make it easier to work with large volumes of data.*

* [rest-pandas ★438](wq/django-rest-pandas) - Serves up your Pandas dataframes via the Django REST Framework for use in client-side (i.e. d3.js) visualizations and offline analysis (e.g. Excel).

## Database

*Packages that add support for 3rd party databases or database specific features.*

* [dj-database-url ★573](kennethreitz/dj-database-url) - Use Database URLs in your Django Application.
* [django-mysql ★131](adamchainz/django-mysql) - Extensions to Django for use with MySQL/MariaDB.
* [django-postgres-fuzzycount ★54](stephenmcd/django-postgres-fuzzycount) - Fast / fuzzy PostgreSQL counts for Django.
* [django-postgrespool ★261](kennethreitz/django-postgrespool) - Postgres Connection Pooling for Django, powered by SQLAlchemy.

## Debugging

*Packages that help hunt down bugs.*

* [django-debug-toolbar ★4185](jazzband/django-debug-toolbar) - A configurable set of panels that display various debug information about the current request/response.
* [django-devserver ★1193](dcramer/django-devserver) - A drop in replacement for Django's built-in runserver command.
* [django-querycount ★89](bradmontgomery/django-querycount) - Middleware that Prints the number of DB queries to the runserver console.
* [django-silk ★927](django-silk/silk) - Silky smooth profiling for Django
* [nplusone ★269](jmcarp/nplusone) - Auto-detecting the n+1 queries problem in Django (and other ORMs)
* [sentry ★12747](getsentry/sentry) - A modern error logging and aggregation platform.

## Email

*Packages that help manage email sending.*

* [django-celery-email ★146](pmclanahan/django-celery-email) - A Django email backend that uses a celery task for sending the email.
* [django-db-mailer ★160](LPgenerator/django-db-mailer) - Django module to easily send email/sms/push/tts using django templates stored on database and managed through the Django Admin.
* [django-drip ★542](zapier/django-drip) - Django Admin based management for drip email campaigns
* [django-email-extras ★67](stephenmcd/django-email-extras) - Various email utilities: PGP encryption, multipart templates, web browser test backend.
* [django-mailgun ★205](BradWhittington/django-mailgun) - A Django email backend for Mailgun.
* [django-post_office ★337](ui/django-post_office) - A simple app to send and manage your emails in Django, supports templates and can be easily integrated with task queues.
* [django-ses ★480](django-ses/django-ses) - A Django email backend for Amazon's Simple Email Service.
* [django-spoolgore ★5 ⏳3Y](20tab/django-spoolgore) - A django email backed for the Spoolgore daemon.
* [django-templated-email ★297](vintasoftware/django-templated-email) - Django module to easily send templated emails using django templates, or using a transactional mail provider (mailchimp, silverpop, etc.)
* [django-yubin ★24](APSL/django-yubin) - django-mailer2 + django-mailviews with some extras.
* [djmail ★59](bameda/djmail) - A simple and nonobstructive django email middleware.
* [djrill ★354](brack3t/Djrill) - Email backend and new message class for Mandrill transactional email service from MailChimp.

## Fields

*Packages that extend the functionality of existing field type or add new field types.*

* [django-audiofield ★94](areski/django-audiofield) -  Allows audio files upload, management and conversion to different audio format (mp3, wav & ogg).
* [django-bitfield ★285](disqus/django-bitfield) - A BitField extension for Django models.
* [django-countries ★372](SmileyChris/django-countries) - Provides country choices for forms, flag icons, and a CountryField.
* [django-enumfield ★98](5monkeys/django-enumfield) - Custom Django field for using enumerations of named constants.
* [django-image-tools ★36 ⏳1Y](bonsaistudio/django-image-tools) - A package to handle images in Django.
* [django-imagekit ★1176](matthewwithanm/django-imagekit) - Automated image processing for Django.
* [django-jsonfield](https://pypi.python.org/pypi/django-jsonfield) - JSONField for Django models.
* [django-location-field ★268](caioariede/django-location-field) - Location field and widget integrated with google maps.
* [django-macaddress ★23](django-macaddress/django-macaddress) - MAC Address model and form fields for Django.
* [django-money ★452](django-money/django-money) - A little Django app that uses py-moneyed to add support for Money fields in your models and forms.
* [django-phonenumber-field](https://github.com/stefanfoulis/django-phonenumber-field/) - A Django library which interfaces with [python-phonenumbers ★1531](daviddrysdale/python-phonenumbers) to validate, pretty print and convert
phone numbers.
* [django-picklefield ★93](gintas/django-picklefield) - A pickled object field for Django
* [django-searchable-select ★31](and3rson/django-searchable-select) - A better and faster multiple choice widget with suggestions.
* [django-uuidfield ★261](dcramer/django-uuidfield) - A UUIDField for Django.
* [django-versatileimagefield ★238](respondcreate/django-versatileimagefield) - A drop-in replacement for django's ImageField that provides a flexible, intuitive and easily-extensible interface for quickly creating new images from the one assigned to the field.

## File Transfers

*Packages that help transfer files between projects and users.*

* [django-downloadview ★131](benoitbryon/django-downloadview) - Serve files with Django.
* [django-sendfile ★315](johnsensible/django-sendfile) - This is a wrapper around web-server specific methods for sending files to web clients.
* [django-filer ★810](divio/django-filer) - Makes multiple files(text/image) uploading easy and provides interface with precise details.

## Forms

*Packages that extend the functionality of forms or add new types of forms.*

* [django-autocomplete-light ★811](yourlabs/django-autocomplete-light) - django-autocomplete-light's purpose is to enable autocompletes quickly and properly in a django project.
* [django-bootstrap-form ★485](tzangms/django-bootstrap-form) - Twitter Bootstrap for Django Form
* [django-bootstrap3 ★1762](dyve/django-bootstrap3) - Use Bootstrap in your Django templates, the Django way.
* [django-crispy-forms ★2781](django-crispy-forms/django-crispy-forms) - The best way to have DRY Django forms. The app provides a tag and filter that lets you quickly render forms in a div format while providing an enormous amount of capability to configure and control the rendered HTML.
* [django-floppyforms ★680](gregmuellegger/django-floppyforms) - django-floppyforms is an application that gives you full control of the output of forms rendering. The forms API and features are exactly the same as Django’s, the key difference is that fields and widgets are rendered in templates instead of using string interpolation, giving you full control of the output using Django templates.

## GIS

*Packages that make it easier to work with geographical information system projects.*

* [django-geoposition ★265](philippbosch/django-geoposition) - A model field that can hold a geoposition (latitude/longitude), and corresponding admin/form widget.
* [django-location-field ★268](caioariede/django-location-field) - Location field and widget integrated with Google Maps.
* [django-spillway ★42](bkg/django-spillway) -  Geodata extensions for Django REST Framework.
* [djangorestframework-gis ★381](djangonauts/django-rest-framework-gis) - Geographic add-ons for Django Rest Framework.

## Image handling

*Packages that help to manipulate, alter, or convert images.*

* [django-image-cropping ★391](jonasundderwolf/django-image-cropping) - helper application to easily and non-destructively crop arbitrarily large images in admin and frontend.
* [django-versatileimagefield ★238](respondcreate/django-versatileimagefield) - A drop-in replacement for django's ImageField that provides a flexible, intuitive and easily-extensible interface for quickly creating new images from the one assigned to the field.

## Import/Export

* [django-import-export ★895](django-import-export/django-import-export) - Django application and library for importing and exporting data with admin integration.

## Migrations

*Packages that help migrate the database when there are schema updates.*

* [South](https://bitbucket.org/andrewgodwin/south/src/) - Django application to provide schema and data migrations that supports Django up to 1.6.x. ([Django 1.7 and up have an integrated migration system, based on but not compatible with South](https://docs.djangoproject.com/en/dev/topics/migrations/))

## Mobile Support

*Packages that help you support for mobile iOS, Android and Others.*

* [django-push-notifications ★925](jleclanche/django-push-notifications) - A minimal Django app that implements Device models that can send messages through APNS and GCM.
* [django-pushy ★159](rakanalh/django-pushy) - Django app that provides push notifications functionality with celery. The main purpose of this app is to help you send push notifications to your users at scale. If you have lots of registered device keys, django-pushy will split your keys into smaller groups which run in parallel making the process of sending notifications faster.

## Model Extensions

*Packages that extend the functionality of models or add new classes of models.*

* [django-aggregate-if ★125 ⏳2Y](henriquebastos/django-aggregate-if) - Conditional aggregates for Django queries, just like the famous SumIf and CountIf in Excel.
* [django-localflavor ★299](django/django-localflavor) - Country-specific Django helpers, formerly of contrib fame.
* [django-model-utils](https://github.com/carljm/django-model-utils/) - Django model mixins and utilities.
* [django-mptt ★1453](django-mptt/django-mptt) - Utilities for implementing a modified pre-order traversal tree in django.
* [django-treebeard](https://github.com/tabo/django-treebeard) -Alternative tree data structures for Django (provides 3 different methods for storing hierarchical data, including MPTT )

## Multitenancy

*Packages that allow a single install of Django to serve multiple organizations.*

* [django-tenant-schemas ★641](bernardopires/django-tenant-schemas) - Tenant support for Django using PostgreSQL schemas.

## Payment Processing

*Packages that provide payment processing provider integration.*

* [dj-stripe ★376](kavdev/dj-stripe) - Django + Stripe Made Easy.
* [django-merchant ★863](agiliq/merchant) - A Django app that provides helpers for multiple pluggable payment backends.
* [django-oscar-adyen](https://github.com/oscaro/django-oscar-adyen/) - This package provides integration with the Adyen payment gateway. It is designed to work seamlessly with the e-commerce framework django-oscar but can be used without Oscar.
* [django-oscar-paymentexpress ★6 ⏳4Y](django-oscar/django-oscar-paymentexpress) - This package provides integration with the payment gateway, PaymentExpress using their PX POST API. It is designed to work seamlessly with the e-commerce framework django-oscar but can be used without it.
* [django-oscar-paypal ★71](django-oscar/django-oscar-paypal) - PayPal integration for django-oscar. Can be used without Oscar too.
* [django-paypal ★388](spookylukey/django-paypal) - A pluggable Django application for integrating PayPal Payments Standard or Payments Pro.
* [django-pinpayments ★19](rossp/django-pinpayments) - Django library to simplify payment processing with pin.
* [django-zebra ★178](GoodCloud/django-zebra) - Forms, widgets, template tags and examples that make Stripe + Django easier.

## Project Management

*Packages for project management and time-tracking.*

* [django-timepiece ★254](caktus/django-timepiece) - A multi-user Django application for tracking people's time on projects.

## Reporting
*Packages for creating reports*

* [django-model-report ★157 ⏳1Y](juanpex/django-model-report) - Django reports integrated with highcharts.
* [django-report-builder ★458](burke-software/django-report-builder) - A GUI for Django ORM. Build custom queries and display results. Targets sys admins and capable end users who might not be able to program.

## RESTful API

*Packages for developing RESTful APIs.*

* [django-nap ★175](funkybob/django-nap) - A minimalist approach to object serialization, RESTful views, and RPC views.
* [django-rest-auth ★831](Tivix/django-rest-auth) - This app makes it extremely easy to build Django powered SPA's (Single Page App) or Mobile apps exposing all registration and authentication related functionality as CBV's (Class Base View) and REST (JSON).
* [django-rest-framework](http://www.django-rest-framework.org/) - A powerful and flexible toolkit that makes it easy to build Web APIs.
* [django-rest-localflavor ★11](gilsondev/django-rest-localflavor) - Localized flavors of some serializers to use with Django Rest Framework.
* [django-rest-swagger ★1496](marcgibbons/django-rest-swagger) - Swagger Documentation Generator for Django REST Framework
* [drfdocs ★360](manosim/django-rest-framework-docs) - Document Web APIs made with Django REST Framework
* [django-tastypie](http://tastypieapi.org/) - Creating delicious APIs for Django apps since 2010.
* [restless ★605](toastdriven/restless) - A lightweight REST miniframework for Python
* [djangorestframework-recursive ★90](heywbj/django-rest-framework-recursive) - Recursive Serialization for Django REST framework

## Search

*Packages that provide search capabilities to projects.*

* [django-haystack ★2194](django-haystack/django-haystack) - Modular search for Django.
* [django-watson ★590](etianen/django-watson) - Fast multi-model full-text search plugin.
* [djorm-ext-pgfulltext ★238](linuxlewis/djorm-ext-pgfulltext) - PostgreSQL full-text search integration with django orm.

## Security

*Packages that improve the security of a project.*

* [django-admin-honeypot ★368](dmpayton/django-admin-honeypot) - A fake Django admin login screen to notify admins of attempted unauthorized access.
* [django-axes ★320](jazzband/django-axes) - is a very simple way for you to keep track of failed login attempts, both for the Django admin and for the rest of your site.
* [django-debreach ★68](lpomfrey/django-debreach) - BREACH mitigation for Django apps.
* [django-password-session ★10 ⏳2Y](atugushev/django-password-session) - Invalidate all active sessions after change password ([not needed for Django 1.7+](https://docs.djangoproject.com/en/dev/topics/auth/default/#session-invalidation-on-password-change)).
* [django-secure-auth ★24](gotlium/django-secure-auth) - Secure authentication by TOTP, SMS, Codes & Question. Login protection with ban by IP and captcha.
* [django-security ★109](sdelements/django-security) - A collection of models, views, middlewares, and forms to help secure a Django project.
* [django-sslify ★287](rdegges/django-sslify) - Force SSL on your Django site.
* [django-stronghold ★228](mgrouchy/django-stronghold) - Stronghold is middleware to default all your views to login required.
* [django-sudo ★236](mattrobenolt/django-sudo) - Sudo mode is an extra layer of security for your most sensitive pages. This is an implementation of GitHub's Sudo Mode for Django.

## SEO

*Packages that help improve SEO ( Search Engine Optimization ) of projects.*

* [django-meta ★149](nephila/django-meta) - a pluggable app to allow Django developers to quickly add meta tags and OpenGraph, Twitter, and Google Plus properties to their HTML responses.
* [django-robots ★210](jazzband/django-robots) - A Django app for managing robots.txt files following the robots exclusion protocol.
* [django-seo2 ★34](romansalin/django-seo2) - Provides a set of tools for managing Search Engine Optimisation (SEO) metadata for Django sites.

## Settings

*Packages that help manage the configurability of projects.*

* [django-configurations ★518](jazzband/django-configurations) - A helper for organizing Django project settings by relying on well established programming patterns.
* [django-constance ★740](jazzband/django-constance) - A Django app for storing dynamic settings in pluggable backends (Redis and Django model backend built in) with an integration with the Django admin app.
* [python-decouple ★397](henriquebastos/python-decouple) - Strict separation of config from code.
* [django-environ ★684](joke2k/django-environ) - Allows you to utilize 12factor inspired environment variables to configure your Django application.
* [django-split-settings ★167](sobolevn/django-split-settings) - Organize Django settings into multiple files and directories. Easily override and modify settings. Use wildcards and optional settings files.
* [django-dynamic-preferences ★77](EliotBerriot/django-dynamic-preferences) - Dynamic global and instance settings for your django project.

## Storage

*Packages that extend the functionality of the existing storage backend or provide new storage backends.*

* [django-selectel-storage ★10 ⏳1Y](marazmiki/django-selectel-storage) - This application allows you easily save media and static files into [Selectel](https://selectel.ru/) cloud storage.
* [django-storages](https://bitbucket.org/david/django-storages/src/) - django-storages is a collection of custom storage backends for Django.
* [django-queued-storage ★245](jazzband/django-queued-storage) - Provides a proxy for Django storage backends that allows you to upload files locally and eventually serve them remotely.
* [django-webdav-storage ★11 ⏳1Y](marazmiki/django-webdav-storage) - Django storage backend that stores files in custom WebDAV storage.

## Tagging

*Packages for adding tags to Django models.*

* [django-taggit ★1659](alex/django-taggit) - Simple tagging for Django.
* [django-taggit-helpers ★18](mfcovington/django-taggit-helpers) - Django admin helper classes for django-taggit tags.

## Task Queue

*Packages that make working with task/background queues easier.*

* [django-celery](http://celery.github.io/django-celery/) - Celery Integration for Django. (no longer required for Celery 3.1 and up)
* [django-q ★493](Koed00/django-q) - A native multiprocessing task queue for Django.
* [django-rq ★630](ui/django-rq) - The easiest way to monitor and use [RQ](http://python-rq.org) in your Django projects.
* [huey ★1229](coleifer/huey) - A little multi-threaded task queue for python.

## Testing

*Packages that help test code or generate test data.*

* [behave-django ★29](behave/behave-django) - Behave BDD integration for Django
* [django-behave ★174](django-behave/django-behave) - TestRunner for the Behave BDD module.
* [django-dynamic-fixture ★251](paulocheque/django-dynamic-fixture) - A complete library to create dynamic model instances for testing purposes.
* [django-faker ★148](joke2k/django-faker) - Fake-factory to generate test data.
* [django-jenkins ★802](kmmbvnr/django-jenkins) - Plug and play continuous integration with django and jenkins.
* [django-nose ★738](django-nose/django-nose) - Test runner using nose.
* [django-selenium ★84 ⏳1Y](dragoon/django-selenium) - Selenium testing support.
* [django-shotgun ★8 ⏳3Y](stephenmcd/django-shotgun) - Test entire Django sites.
* [django-slowtests ★110](realpython/django-slow-tests) - Locate your slowest tests.
* [django-test-plus ★208](revsys/django-test-plus) - Useful addons to Django's default TestCase that greatly reduces boilerplate code
* [factory_boy ★1164](FactoryBoy/factory_boy) - A test fixtures replacement for Python
* [hitchtest](http://hitchtest.com/) - High level integration testing framework for Django.
* [lettuce-django-terrain ★12 ⏳5Y](stringfellow/lettuce-django-terrain) - Terrain file for lettuce in django projects
* [mixer] (https://github.com/klen/mixer) - An application to generate instances of Django or SQLAlchemy models. Fast and convenient test-data generation.
* [mock-django] (https://github.com/dcramer/mock-django) - A simple library for mocking certain Django behavior, such as the ORM.
* [model-mommy ★668](vandersonmota/model_mommy) - Smart fixtures for better tests.
* [pytest-django](https://pypi.python.org/pypi/pytest-django/) - Test runner using py.test
* [splinter ★1400](cobrateam/splinter) - Test framework for web applications.

## Thumbnail

*Packages that help generate thumbnails.*

* [django-stdimage ★129](codingjoe/django-stdimage) - Thumbnails and image utils for Django.
* [django-versatileimagefield ★238](respondcreate/django-versatileimagefield) - A drop-in replacement for django's ImageField that provides a flexible, intuitive and easily-extensible interface for quickly creating new images from the one assigned to the field.
* [easy-thumbnails ★908](SmileyChris/easy-thumbnails) - Easy thumbnails for Django.
* [sorl-thumbnail](https://github.com/mariocesar/sorl-thumbnail/) - Thumbnails for Django.

## Translations

*Packages help with the task of translating projects.*

* [django-hvad ★424](KristianOellegaard/django-hvad) - Painless translations in django, using the regular ORM. Integrates easily into existing projects and apps. Easy convertible from django-multilingual-ng.
* [django-klingon ★36](angvp/django-klingon) - An attempt to make django model translations suckless and with no integrations pain in your app.
* [django-modeltranslation ★493](deschler/django-modeltranslation) - Translate dynamic content of existing Django models to an arbitrary number of languages without having to change the original model classes.
* [django-parler ★240](django-parler/django-parler) - Simple Django model translations without nasty hacks
* [django-rosetta ★609](mbi/django-rosetta) - Rosetta is a Django application that eases the translation process of your Django projects.

## Views

*Packages that enhance or provide new view classes.*

* [django-extra-views ★598](AndrewIngram/django-extra-views) - Django's class-based generic views are awesome, let's have more of them.
* [django-vanilla-views ★658](tomchristie/django-vanilla-views) - Beautifully simple class-based views.

## Web frontend integration

*Packages for integrating and managing front-end packages.*

* [django-angular ★1081](jrief/django-angular) - Let AngularJS play well with Django.
* [django-bower ★490](nvbn/django-bower) - Easy way to use [bower](https://bower.io) with your Django project.
* [django-js-reverse ★340](ierror/django-js-reverse) - Javascript url handling for Django that doesn't hurt.
* [djangular ★214 ⏳1Y](appliedsec/djangular) - A reusable Django app that provides better integration and tools for Angular.js.

## WYSIWYG Editors

*Packages that makes text editing awesome.*

* [django-ckeditor ★833](django-ckeditor/django-ckeditor) - Django admin CKEditor integration.
* [django-summernote ★330](summernote/django-summernote) - Summernote is a simple WYSIWYG editor. django-summernote allows you to embed Summernote into Django very handy. Support admin mixins and widgets.
* [django-tinymce ★623](aljosa/django-tinymce) - TinyMCE integration for Django.
* [django-wysiwyg ★440](pydanny-archive/django-wysiwyg) - A Django application for making Django textareas rich text editors. Certainly as a template tag and possibly as a form widget.
* [django-wysiwyg-redactor](https://github.com/douglasmiranda/django-wysiwyg-redactor/) - A lightweight wysiwyg editor for Django.

## Wikis

*Packages for adding wiki functionality to a project.*

* [django-wiki ★742](django-wiki/django-wiki) A wiki system with complex functionality for simple integration and a superb interface. Store your knowledge with style: Use django models.
* [waliki ★256](mgaitan/waliki) An extensible wiki app for Django with a Git backend.

## Workflows

*Packages that do process, procedure and/or business tasks management.*

* [django-flows ★90 ⏳1Y](carlio/django-flows) - django-flows keeps state and position in complicated flows of logic, allowing optional branches and complicated paths through a series of individual user actions.
* [django-fsm ★839](kmmbvnr/django-fsm) - Django friendly finite state machine support.
* [django-river ★306](javrasya/django-river) - Django state machine and workflow library provides on the fly changes.
* [django-states ★115](vikingco/django-states2) - State machine for django models.
* [django-viewflow ★651](viewflow/viewflow) - Reusable workflow library for Django.
* [django-workflows](https://bitbucket.org/jerzyk/django-workflows/) - django-workflows provides a generic workflow engine for Django.
* [django-xworkflows ★75](rbarrois/django_xworkflows) - Library to plug xworkflows into django models.

## Other

*Other awesome Django packages.*

* [django-activeurl ★95](hellysmile/django-activeurl) - Easy to use active URL highlighting for django
* [django-activity-stream ★1189](justquick/django-activity-stream) - Generate generic activity streams from the actions on your site. Users can follow any actors' activities for personalized streams.
* [django-adminactions ★170](saxix/django-adminactions) - Collection of useful actions to use with django.contrib.admin.ModelAdmin and/or django.contrib.admin.AdminSite
* [django-autoadmin ★29 ⏳1Y](rosarior/django-autoadmin) - Automatic admin users for Django projects.
* [django-braces ★1220](brack3t/django-braces) - Reusable, generic mixins for Django.
* [django-calendarium](https://github.com/bitmazk/django-calendarium/) - A reusable app to manage and display a calendar in your templates.
* [django-changuito ★47](angvp/django-changuito) - A cart app for your django site, an updated fork of django-cart
* [django-cors-headers ★1467](ottoyiu/django-cors-headers) - Django app for handling the server headers required for Cross-Origin Resource Sharing (CORS).
* [django-dfp ★4 ⏳1Y](praekelt/django-dfp) - App that provides tags to fetch Google DFP ads.
* [django-dynamic-scraper ★570](holgerd77/django-dynamic-scraper) - Creating Scrapy scrapers via the Django admin interface.
* [django-extensions ★3149](django-extensions/django-extensions) - This is a repository for collecting global custom management extensions for the Django Framework.
* [django-filter ★1758](carltongibson/django-filter) - A generic system for filtering Django QuerySets based on user selections.
* [django-friendship ★292](revsys/django-friendship) - Django app to manage following and bi-directional friendships.
* [django-gravatar2 ★93](twaddington/django-gravatar) - Essential Gravatar support for Django. Features helper methods, templatetags and a full test suite!
* [django-hackathon-starter ★1026](DrkSephy/django-hackathon-starter) - A boilerplate for Django web applications, containing various social authentication methods and several popular API examples.
* [django-ipware ★329](un33k/django-ipware) - A Django application to retrieve user's IP address.
* [django-magic-embed ★18 ⏳1Y](kronoscode/django-magicembed) - an easy and simple Django template tag and tool to embed video and get thumbnails from video providers.
* [django-markitup ★41](zsiciarz/django-markitup) - A Django reusable application for end-to-end markup handling.
* [django-mmc ★31](LPgenerator/django-mmc) - App for monitoring management commands on Django..
* [django-overextends ★91](stephenmcd/django-overextends) - Circular template inheritance for Django.
* [django-pagination ★504](ericflo/django-pagination) - https://github.com/ericflo/django-pagination.
* [django-el-pagination ★120](shtalinberg/django-el-pagination) - Django EL(Endless) Pagination can be used to provide Twitter-style or Digg-style pagination, with optional Ajax support.
* [django-quiz-app ★201](tomwalker/django_quiz) - This is a configurable quiz app for Django.
* [django-recaptcha ★395](praekelt/django-recaptcha) - Django reCAPTCHA form field/widget integration app.
* [django-smuggler ★231](semente/django-smuggler) - Django Smuggler is a pluggable application for Django Web Framework that helps you to import/export fixtures via the automatically-generated administration interface.
* [django-solo ★275](lazybird/django-solo) - Helps working with singletons - things like global settings that you want to edit from the admin site.
* [django-sql-explorer ★1251](groveco/django-sql-explorer) - Easily share data via SQL queries, right from Django
* [django-stored-messages ★70](evonove/django-stored-messages) - Store Django messages on your project's backend.
* [django-ratelimit ★342](jsocol/django-ratelimit) - provides a decorator to rate-limit views. Limiting can be based on IP address or a field in the request--either a GET or POST variable.
* [django-uuslug ★188](un33k/django-uuslug) - a slugify application that guarantees Uniqueness and handles Unicode.
* [django-watchman ★149](mwarkentin/django-watchman) - django-watchman exposes a status endpoint for your backing services like databases, caches, etc.
* [django-websocket-redis ★618](jrief/django-websocket-redis) - Websockets for Django applications using Redis as message queue.
* [metamon](http://tryolabs.github.io/metamon/) - Collection of Ansible playbooks to quickly start your Django Application
* [micawber ★347](coleifer/micawber) - A small library for extracting rich content from urls.
* [towel ★69](matthiask/towel) - a collection of tools which make your life easier if you are building a web application using Django.

# Projects

*Outstanding Django projects.*

## CMS

* [django-cms ★4929](divio/django-cms) - The easy-to-use and developer-friendly CMS.
* [django-fiber ★553](ridethepony/django-fiber) - Django Fiber, a simple, user-friendly CMS for all your Django projects
* [feincms ★695](feincms/feincms) - A Django-based CMS with a focus on extensibility and concise code.
* [Mezzanine ★3085](stephenmcd/mezzanine) - A content management platform built using the Django framework.
* [wagtail](https://github.com/torchbox/wagtail/) - A Django content management system focused on flexibility and user experience.
* [leonardo ★62](django-leonardo/django-leonardo) - A new Django content management system built on top of FeinCMS and OpenStack Horizon.

## Document Management

* [mayan-edms](https://gitlab.com/mayan-edms/mayan-edms) - Open source, Django based DMS (document management system) with custom metadata indexing, file serving integration, OCR capabilities, document versioning and electronic signature verification.

## e-Commerce

* [Cartridge ★526](stephenmcd/cartridge) - Ecommerce for Django/Mezzanine.
* [django-oscar ★2529](django-oscar/django-oscar) - Domain-driven e-commerce for Django.
* [Lighting Fas Shop](http://www.getlfs.com/) - Lighting Fas Shop is Ecommerce made with Django.
* [Saleor](http://getsaleor.com) - An e-commerce storefront for Python and Django.
* [Satchless](http://satchless.com) - Satchless brings e-commerce and Python together.
* [Satchmo](https://bitbucket.org/chris1610/satchmo/src/) - Satchmo is an eCommerce framework created in Django which allows you to develop unique and robust online stores.
* [Django-Shop](http://www.django-shop.org) - A Django based shop system.

## Other

* [Django packages](https://github.com/pydanny/djangopackages/) - Django Packages is a directory of reusable apps, sites, tools, and more for your Django projects.
* [django-salted ★329 ⏳3Y](wunki/django-salted) - Full stack SaltStack configuration for Django with the help of Vagrant.
* [Drum ★321](stephenmcd/drum) - Reddit / Hacker News clone for Django/Mezzanine.
* [koalixcrm ★61](tfroehlich82/koalixcrm) - Beautiful CRM/ERP for small business.

## Project Management

* [ITSY](https://github.com/orges/itsy/) - Issue Tracking System
* [taiga ★3495](taigaio/taiga-back) - Agile, Free and Open Source Project Management Tool

# Resources

*Where to discover new Django apps and projects.*

## Books

* [Django by Example ★15](kevinlondon/django-by-example) (1.2)
* [Djen of Django](http://agiliq.com/books/djenofdjango/) (< 1.7)
* [Effective Django](http://www.effectivedjango.com/) (1.5)
* [Getting started with Django](http://www.gettingstartedwithdjango.com/) (video)
* [High Performance Django](https://highperformancedjango.com/) (1.7) - Deploying fast, scalable Django sites.
* [Lightweight Django](http://shop.oreilly.com/product/0636920032502.do) (1.7) - Using REST, WebSockets, and Backbone with Django
* [Tango With Django](http://www.tangowithdjango.com/) (1.5)
* [Test-Driven Web Development with Python](http://chimera.labs.oreilly.com/books/1234000000754/index.html) (1.7)
* [Two Scoops of Django: Best Practices for Django 1.8](https://www.twoscoopspress.com/products/two-scoops-of-django-1-8/) - A best practice book for making Python and Django as fun as ice cream.

## Websites

* [Django Girls Tutorial](https://tutorial.djangogirls.org/) - A fun and engaging tutorial showing how to build a blog using Django and deploy it to Heroku.
* [Django Introduction](http://www.django-introduction.com/) - A reusable set of slides to educate more people about Django.
* [Django Packages](https://djangopackages.org/) - Django Packages is a directory of reusable apps, sites, tools, and more for your Django projects.
* [Django Sites](https://www.djangosites.org) - Django Sites is a showcase of websites powered by Django.
* [Full Stack Python's Django page](https://www.fullstackpython.com/django.html) - contains explanations for Django's philosophy and its components along with links to other resources and tutorials.
* [Simple is Better Than Complex](https://simpleisbetterthancomplex.com) - A blog about Django, Python and Web Development. Weekly updates containing tutorials, tips, featured packages, reference guides and code snippets.

## Conferences

* [Django Beer](https://www.djangobeer.com/) - the new meeting of the Django community of Florence.
* [Django Village](http://djangovillage.it/) - the Italian Django community conference. An opportunity to meet djangonauts from all over Italy and abroad.
* [Django Weekend](https://twitter.com/djangoweekend) - is a Django/Python non-profit community event, organised and run entirely by volunteers. The conference is Django-focused, but all aspects of Python fall within its remit.
* [Django: Under The Hood](https://www.djangounderthehood.com/) - is an exciting new Django conference for experienced Django developers. Come and learn about the internals of Django, and help to shape its future.
* [DjangoCon Europe](http://www.djangocon.eu/) - is the annual largest European-based Django conference that is usually held in late spring.
* [DjangoCon US](https://2016.djangocon.us/) - is the largest North American Django conference generally held the first week in September each year.

# Non Python packages

* [cookiecutter-django ★2604](pydanny/cookiecutter-django) - A cookiecutter template for creating Django projects quickly.

## External documentation

*Additional sources of information about django features.*

* [Classy Class-Based Views](http://ccbv.co.uk/) - Detailed descriptions, with full methods and attributes, for each of Django's class-based generic views.
* [Classy Django REST Framework](http://www.cdrf.co/) - Detailed descriptions, with full methods and attributes, for each of Django REST Framework's class-based views and serializers.

## Videos

* [CodingforEntrepreneur](https://www.codingforentrepreneurs.com/projects/) - One of the best collection of Django Videos and all the projects are written in Django.
* [Code School - Try Django](https://www.codeschool.com/courses/try-django) - An introduction to the basics of Django.
* [GoDjango](https://godjango.com) - Django videos from basics to advanced. Covering 3rd party apps to core Django compontents.
* [Must Watch Django Videos ★491 ⏳1Y](rosarior/django-must-watch) - Must-watch videos about Django (or about Python as applied to Django)
* [One Month Django](https://onemonth.com) - The video series will teach you Django in one month

# Utilities

*Non Django projects that make it easier to work with Django.*

* [Django-manage.py-anywhere ★14](timonweb/Django-manage.py-anywhere) - Run manage.py commands from anywhere. Finds closest to current path manage.py file and runs commands against it.
* [Logan ★193](dcramer/logan) - A toolkit for running standalone Django applications. It provides you with tools to create a CLI runner, manage settings, and the ability to bootstrap the process.

# Contributing

Just fork and send a pull request with your awesome Django apps, projects or resources.
By contributing you agree to abide by the Code of Merit.
---
<p align="center">
	This list is a copy of <a href="rosarior/awesome-django">rosarior/awesome-django</a> with ranks
</p>
