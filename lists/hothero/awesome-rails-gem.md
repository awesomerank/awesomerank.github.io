<h1 align="center">
Ranked awesome lists, all in one place
</h1>
<p align="center">
	This list is a copy of <a href="hothero/awesome-rails-gem">hothero/awesome-rails-gem</a> with ranks
</p>
---
# Awesome Rails Gem [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg) ★59088](sindresorhus/awesome)
A collection of awesome Ruby Gems for Rails development.

The goal is to help every Rails developer to build an awesome Rails product/service.

* [Rails Gem List](#rails-gem-list)
  * [User](#user)
  * [Active Record](#active-record)
  * [Plugins](#plugins)
  * [API](#api)
  * [Email](#email)
  * [File Uploading](#file-uploading)
  * [Searching](#searching)
  * [Scheduled/Recurrence Jobs](#scheduledrecurrence-jobs)
  * [View Helper](#view-helper)
  * [Environment Variables](#environment-variables)
  * [Admin Panel](#admin-panel)
  * [Logging](#logging)
  * [Debug](#debug)
  * [Coding Style](#coding-style)
  * [Testing](#testing)
  * [Production](#production)
  * [Error Logging](#error-logging)
  * [Database](#database)

## User

### Authentication
* [Devise ★17119](plataformatec/devise) - Devise is a flexible authentication solution for Rails based on Warden.
* [Knock ★1063](nsarno/knock) - Seamless JWT authentication for Rails API.
* [Clearance ★2681](thoughtbot/clearance) - Rails authentication with email & password.
* [Devise token auth ★1947](lynndylanhurley/devise_token_auth) - Token based authentication for Rails JSON APIs.
* [Sorcery ★262](Sorcery/sorcery) - Magical Authentication for Rails. Supports ActiveRecord, DataMapper, Mongoid and MongoMapper.

### Authorization
* [Pundit ★5195](elabs/pundit) - Pundit provides a set of helpers which guide you in leveraging regular Ruby classes and object oriented design patterns to build a simple, robust and scaleable authorization system.
* [cancancan ★3560](CanCanCommunity/cancancan) - Continuation of CanCan, the authorization Gem for Ruby on Rails.CanCan is an authorization library for Ruby on Rails which restricts what resources a given user is allowed to access. All permissions are defined in a single location (the Ability class) and not duplicated across controllers, views, and database queries.
* [rolify ★2096](RolifyCommunity/rolify) - Role management library with resource scoping.
* [acl9 ★825](be9/acl9) - Acl9 is a role-based authorization system that provides a concise DSL for securing your Rails application.


### Omniauth
* [omniauth-facebook ★1030](mkdynamic/omniauth-facebook)
* [omniauth-google-oauth2 ★837](zquestz/omniauth-google-oauth2)
* [omniauth-weibo-oauth2 ★138](beenhero/omniauth-weibo-oauth2)
* [omniauth-twitter ★481](arunagw/omniauth-twitter)
* [omniauth-github ★305](intridea/omniauth-github)
* [omniauth-linkedin-oauth2 ★79](decioferreira/omniauth-linkedin-oauth2)

## Active Record
* [Enumerize ★1265](brainspec/enumerize) - Enumerated attributes with I18n and ActiveRecord/Mongoid support. It can be integrated with Simple Form.
* [counter_culture ★792](magnusvk/counter_culture) - Turbo-charged counter caches for your Rails app. Huge improvements over the Rails standard counter caches.
* [custom_counter_cache ★49](cedric/custom_counter_cache) - A simple approach to creating a custom counter cache that can be used across multiple models.
* [Sequenced ★147 ⏳1Y](djreimer/sequenced) - Sequenced is a simple gem that generates scoped sequential IDs for ActiveRecord models.
* [FriendlyId ★4578](norman/friendly_id) - FriendlyId is the “Swiss Army bulldozer” of slugging and permalink plugins for ActiveRecord. It allows you to create pretty URL’s and work with human-friendly strings as if they were numeric ids for ActiveRecord models.
* [AASM ★2872](aasm/aasm) - State machines for Ruby classes (plain Ruby, Rails Active Record, Mongoid).
* [PaperTrail ★4596](airblade/paper_trail) - PaperTrail lets you track changes to your models' data. It's good for auditing or versioning.
* [paranoia ★1957](rubysherpas/paranoia) - ActiveRecord plugin allowing you to hide and restore records without actually deleting them.
* [Validates ★120](kaize/validates) - Validates provides collection of useful custom validators for Rails applications, including:
  * EmailValidator
  * UrlValidator
  * SlugValidator
  * MoneyValidator
  * IpValidator
  * AssociationLengthValidator
  * AbsolutePathValidator
  * UriComponentValidator
  * ColorValidator
  * EanValidator (EAN-8 & EAN-13)
* [globalize ★1512](globalize/globalize) - Rails I18n de-facto standard library for ActiveRecord model/data translation.
* [deep_cloneable ★386](moiristo/deep_cloneable) - This gem gives every ActiveRecord::Base object the possibility to do a deep clone that includes user specified associations.
* [social_shares ★269](Timrael/social_shares) - Check how many times url was shared in social networks.
* [public_activity ★2364](chaps-io/public_activity) - Easy activity tracking for models - similar to Github's Public Activity.
* [goldiloader ★618](salsify/goldiloader) - Automatic ActiveRecord eager loading to reduce the number of database queries run by your application.
* Tagging
  * [ActsAsTaggableOn ★4013](mbleigh/acts-as-taggable-on) - A tagging plugin for Rails applications that allows for custom tagging along dynamic contexts.
  * [closure_tree ★1068](mceachen/closure_tree) - Easily and efficiently make your ActiveRecord models support hierarchies.
* [ActionStore ★173](rails-engine/action-store) - Store different kind of actions (Like, Follow, Star, Block ...) in one table via ActiveRecord Polymorphic Association.

## Plugins
* [Spreadsheet ★758](zdavatz/spreadsheet) - Library is designed to read and write Spreadsheet Documents.
* [Chartkick ★4301](ankane/chartkick) - Chartkick helps your to create beautiful Javascript charts with one line of Ruby.
* [kaminari](https://github.com/amatsuda/kaminari) - A Scope & Engine based, clean, powerful, customizable and sophisticated paginator for Rails 3 and 4.
* [CKEditor ★1728](galetahub/ckeditor) - CKEditor is a WYSIWYG text editor designed to simplify web content creation. It brings common word processing features directly to your web pages. Enhance your website experience with our community maintained editor. [ckeditor.com](http://ckeditor.com)
* [HTML::Pipeline ★1788](jch/html-pipeline) - GitHub HTML processing filters and utilities. This module includes a small framework for defining DOM based content filters and applying them to user provided content.
* [Slack Notifier ★931](stevenosloan/slack-notifier) is a simple wrapper to send notifications to [Slack](https://slack.com/) webhooks.
* [Rails ERD ★2153](voormedia/rails-erd) - Generate Entity-Relationship Diagrams for Rails applications.
* [Parity ★521](thoughtbot/parity) - Shell commands for development, staging, and production parity for Heroku apps.
* [Airbrussh ★488](mattbrictson/airbrussh) - Airbrussh pretties up your SSHKit and Capistrano output

## API
* [Grape ★8020](ruby-grape/grape) - Microframework to create REST-ful APIs in Ruby.
* [ActiveModel::Serializers ★4189](rails-api/active_model_serializers) - Serializer brings convention over configuration to your JSON generation.
* [Jbuilder ★3005](rails/jbuilder) - Jbuilder gives you a simple DSL for declaring JSON structures that beats massaging giant hash structures. This is particularly helpful when the generation process is fraught with conditionals and loops.
* [rest-client ★3932](rest-client/rest-client) - Simple HTTP and REST client for Ruby, inspired by microframework syntax for specifying actions.
* [has_scope ★1206](plataformatec/has_scope) - Map incoming controller parameters to named scopes in your resources.
* Documentation
	* [Grape Swagger ★783](ruby-grape/grape-swagger) - Autogenerate documentation on Grape API.
	* [Grape Swagger UI ★8140](swagger-api/swagger-ui) - Display documentation that is generated using Grape Swagger.
	* [apiary](https://apiary.io/) - Work together to quickly design, prototype, document and test APIs.
	* [apiblueprint](https://apiblueprint.org) - API Documentation with powerful tooling.

## Email
* [letter_opener ★2578](ryanb/letter_opener) - Preview mail in the browser instead of sending.

## File Uploading
* [Carrierwave ★7499](carrierwaveuploader/carrierwave) - Carrierwave is a classier solution for file uploads for Rails, Sinatra and other Ruby web frameworks.
  * [carrierwave_backgrounder ★641](lardawge/carrierwave_backgrounder) - Offload CarrierWave's image processing and storage to a background process using Delayed Job, Resque, Sidekiq, Qu, Queue Classic or Girl Friday.
  * [CarrierWave Crop ★92 ⏳1Y](kirtithorat/carrierwave-crop) - Carrierwave extension to crop uploaded images using Jcrop plugin with preview.
  * [CarrierWave ImageOptimizer ★157](jtescher/carrierwave-imageoptimizer) - This gem allows you to simply optimize CarrierWave images via jpegoptim or optipng using the image_optimizer gem.
* [remotipart ★952](JangoSteve/remotipart) - Rails jQuery file uploads via standard Rails "remote: true" forms.
* [MiniMagick ★2015](minimagick/minimagick) - MiniMagick is a ruby wrapper for ImageMagick or GraphicsMagick command line.
* [fog ★4009](fog/fog) - Fog is the Ruby cloud services library, top to bottom.
* [refile ★2349](refile/refile) - Refile is a modern file upload library for Ruby applications. It is simple, yet powerful.
* [Paperclip ★8550](thoughtbot/paperclip) - Easy file attachment management for ActiveRecord.
* [Dragonfly](http://markevans.github.io/dragonfly) - Dragonfly is for on-the-fly file processing - suitable for images or other attachments

## Searching
* [ransack ★3337](activerecord-hackery/ransack) - Ransack enables the creation of both simple and advanced search forms for your Ruby on Rails application.
* [elasticsearch-rails ★1986](elastic/elasticsearch-rails) - Elasticsearch integrations for ActiveModel/Record and Ruby on Rails.
* [Chewy ★1116](toptal/chewy) - High-level Elasticsearch Ruby framework based on the official elasticsearch-ruby client.
* [Chewy_Kiqqer ★28](averell23/chewy_kiqqer) - This is an alternative update/callback mechanism for Chewy. It queues the updates as Sidekiq jobs.
* [pg_search ★1891](Casecommons/pg_search) - pg_search builds ActiveRecord named scopes that take advantage of PostgreSQL's full text search
* [sunspot ★2746](sunspot/sunspot) - Sunspot is a Ruby library for expressive, powerful interaction with the Solr search engine. Sunspot is built on top of the RSolr library, which provides a low-level interface for Solr interaction; Sunspot provides a simple, intuitive, expressive DSL backed by powerful features for indexing objects and searching for them.
* [searchkick ★3603](ankane/searchkick) - Intelligent search made easy with Rails and Elasticsearch.

## Scheduled/Recurrence Jobs
* [Whenever ★7085](javan/whenever) - Whenever is a Ruby gem that provides a clear syntax for writing and deploying cron jobs.
* [Resque ★7835](resque/resque) - Redis-backed Ruby library for creating background jobs, placing them on multiple queues, and processing them later.
* [Rufus-Scheduler ★1675](jmettraux/rufus-scheduler) - Rufus-scheduler is a Ruby gem for scheduling pieces of code (jobs). It understands running a job AT a certain time, IN a certain time, EVERY x time or simply via a CRON statement.
* [Delayed Job ★4122](collectiveidea/delayed_job) - Database based asynchronous priority queue system.
* [Sidekiq ★7519](mperham/sidekiq) - Simple, efficient background processing for Ruby.
  * [sidetiq](https://github.com/tobiassvn/sidetiq) - Recurring jobs for sidekiq.
  * [sidekiq-cron ★546](ondrejbartas/sidekiq-cron) - Scheduler / Cron for Sidekiq jobs
  * [sidekiq-scheduler ★394](Moove-it/sidekiq-scheduler) - Lightweight job scheduler extension for Sidekiq
* [Sucker Punch ★2082](brandonhilkert/sucker_punch) - Sucker punch is a single-process Ruby asynchronous processing library.

## View Helper
* [formtastic ★4972](justinfrench/formtastic) - Formtastic is a Rails FormBuilder DSL (with some other goodies) to make it far easier to create beautiful, semantically rich, syntactically awesome, readily stylable and wonderfully accessible HTML forms in your Rails applications
* [Simple Form ★6634](plataformatec/simple_form) - Simple form aims to be as flexible as possible while helping you with powerful components to create your forms. The basic goal of Simple Form is to not touch your way of defining the layout, letting you find the better design for your eyes.
* [Nested Form ★1759](ryanb/nested_form) - This is a Rails gem for conveniently manage multiple nested models in a single form. It does so in an unobtrusive way through jQuery or Prototype. It can also be integrated with Simple Form.
* [meta-tags ★1734](kpumuk/meta-tags) - Search Engine Optimization (SEO) plugin for Ruby on Rails applications.
* [active_link_to ★577](comfy/active_link_to) - active_link_to adds css 'active' class to your links.
* [cells](https://github.com/apotonick/cells) - Cells allow you to encapsulate parts of your UI into components into view models. View models, or cells, are simple ruby classes that can render templates.
* [i18n Country Code Select ★25](onomojo/i18n_country_select) - I18n Country Code Select Form Helper for Rails 3 & 4.
* [Subdivision Select ★11](cllns/subdivision_select) - A Rails plugin to populate a state/province select box from country_select.
* [cocoon ★2344](nathanvda/cocoon) - Dynamic nested forms using jQuery made easy

## Environment Variables
* [Config ★1255](railsconfig/config) - Multi-environment YAML style configurations that helps easily manage environment specific settings in an easy and usable manner.
* [Figaro ★3058](laserlemon/figaro) - Figaro is very simple, Heroku-friendly Rails app configuration using ENV and a single YAML file.
* [dotenv ★4045](bkeepers/dotenv) - Dotenv is a gem that allows you to set your environment variables in .env file, and it will load it in to ENV.
* [opsworks-dotenv ★8 ⏳1Y](mikamai/opsworks-dotenv) - Opsworks-dotenv let you configure the environment for you Rails application using OpsWorks, Chef and Dotenv.

## Admin Panel
* [ActiveAdmin](http://activeadmin.info) - ActiveAdmin is a administration framework for Ruby on Rails applications.
  - [active_skin ★382](rstgroup/active_skin): Flat skin for active admin.
* [RailsAdmin ★6514](sferik/rails_admin) - RailsAdmin is a Rails engine that provides an easy-to-use interface for managing your data.
* [Typus ★1129](typus/typus) - Typus is a control panel for Ruby on Rails applications to allow trusted users edit structured content.
* [administrate ★3338](thoughtbot/administrate) - A Rails engine that helps you put together a super-flexible admin dashboard.

## Logging
* [Impressionist ★1018](charlotte-ruby/impressionist) - Impressionist can log page impressions (technically action impressions), but it is not limited to that. You can log impressions multiple times per request. And you can also attach it to a model. The goal of this project is to provide customizable stats that are immediately accessible in your application as opposed to using Google Analytics and pulling data using their API.
* [Ahoy ★1907](ankane/ahoy) - Ahoy provides a solid foundation to track visits and events in Ruby, JavaScript, and native apps.
* [Lograge ★2002](roidrage/lograge) - An attempt to tame Rails' default policy to log everything.

## Debug
* [byebug ★2298](deivid-rodriguez/byebug) - Byebug is a simple to use, feature rich debugger for Ruby 2. It uses the new TracePoint API for execution control and the new Debug Inspector API for call stack navigation, so it doesn't depend on internal core sources.
  * [pry-byebug ★1073](deivid-rodriguez/pry-byebug) - Pry navigation commands via byebug.
* [pry-rails ★933](rweng/pry-rails) - Avoid repeating yourself, use pry-rails instead of copying the initializer to every rails project. This is a small gem which causes rails console to open pry. It therefore depends on pry.
* [awesome_print ★3083](awesome-print/awesome_print) - Awesome Print is a Ruby library that pretty prints Ruby objects in full color exposing their internal structure with proper indentation.
* [web-console ★1012](rails/web-console) - Web Console is a debugging tool for your Ruby on Rails applications.
* [spring ★2277](rails/spring) - Spring is a Rails application preloader. It speeds up development by keeping your application running in the background so you don't need to boot it every time you run a test, rake task or migration.
* [rails-footnotes ★1438](josevalim/rails-footnotes) - Rails footnotes displays footnotes in your application for easy debugging, such as sessions, request parameters, cookies, filter chain, routes, queries, etc.
* [g ★101 ⏳3Y](jugyo/g) - The Kernel.g that works like Kernel.p by using terminal-notifier or growl.
* [terminal-notifier ★3923](julienXX/terminal-notifier) - terminal-notifier is a command-line tool to send Mac OS X User Notifications, which are available in Mac OS X 10.8 and higher.
* [letter_opener ★2578](ryanb/letter_opener) - Preview email in the default browser instead of sending it. This means you do not need to set up email delivery in your development environment, and you no longer need to worry about accidentally sending a test email to someone else's address.
* [Better Errors ★6140](charliesome/better_errors) - Better errors replaces the standard Rails error page with a much better and more useful error page.
  * If you would like to use Better Errors' advanced features (REPL, local/instance variable inspection, pretty stack frame names), you need to add the [binding_ _of__caller ★509](banister/binding_of_caller).
* [RailsPanel ★3075](dejan/rails_panel) - RailsPanel is a Chrome extension for Rails development that will end your tailing of development.log.

## Coding Style
* [RuboCop](https://github.com/bbatsov/rubocop) - Rubocop is a Ruby static code analyzer. Out of the box it will enforce many of the guidelines outlined in the community [Ruby Style Guide ★12372](bbatsov/ruby-style-guide).
* [Rails Best Practice](https://github.com/railsbp/rails_best_practices) - Rails best practice is a code metric tool to check the quality of rails codes.
* [Metric Fu]( https://github.com/metricfu/metric_fu) - A fist full of code metrics
* [Pronto](https://github.com/mmozuras/pronto) - Quick automated code review of your changes

## Testing
* [rspec-rails ★3290](rspec/rspec-rails) - Rspec-rails is a testing framework for Rails 3.x and 4.x.
* [Capybara](https://github.com/jnicklas/capybara) - Capybara helps you test web applications by simulating how a real user would interact with your app. And drivers:
  - [capybara-webkit ★1868](thoughtbot/capybara-webkit) - Capybara-webkit is a capybara driver that uses Webkit via QtWebkit.
  - [selenium-webdriver ★21 ⏳1Y](vertis/selenium-webdriver) - Selenium-webdriver provides ruby bindings for WebDriver.
  - [poltergeist ★2362](teampoltergeist/poltergeist) - Poltergeist allows you to run your Capybara tests on a headless WebKit browser, provided by PhantomJS.
  - [page-object ★535](cheezy/page-object) - Page-object is a simple gem that assists in creating flexible page objects for testing browser based applications.
* [factory_girl ★5335](thoughtbot/factory_girl) - Factory_girl is a fixtures replacement with a straightforward definition syntax, support for multiple build strategies (saved instances, unsaved instances, attribute hashes, and stubbed objects), and support for multiple factories for the same class (user, admin_user, and so on), including factory inheritance.
* [factory_girl_rails ★1824](thoughtbot/factory_girl_rails) - Factory_girl_rails provides Rails integration for factory_girl.
* [factory_factory_girl ★44 ⏳1Y](st0012/factory_factory_girl) - FactoryFactoryGirl lets you generate factory files more efficiently with naming rules.
* [Database Cleaner ★2068](DatabaseCleaner/database_cleaner) - Database Cleaner is a set of strategies for cleaning your database in Ruby.Support ActiveRecord, DataMapper, Sequel, MongoMapper, Mongoid, CouchPotato, Ohm and Redis.
* [shoulda-matchers ★1986](thoughtbot/shoulda-matchers) - Shoulda-matchers provides serveral matchers for testing common Rails functionality.
* [ResponseCodeMatchers ★50 ⏳2Y](r7kamura/response_code_matchers) - ResponseCodeMatchers provides rspec matchers to match http response code.
* [SimpleCov ★3006](colszowka/simplecov) - SimpleCov is a code coverage analysis tool for Ruby.
* [Timecop ★2369](travisjeffery/timecop) - A gem providing "time travel" and "time freezing" capabilities, making it dead simple to test time-dependent code.
* [VCR ★3491](vcr/vcr) - Record your test suite's HTTP interactions and replay them during future test runs for fast, deterministic, accurate tests.

### Security
* [brakeman ★4204](presidentbeef/brakeman) - Brakeman is a static analysis tool which checks Ruby on Rails applications for security vulnerabilities.
* [bundle-audit ★1426](rubysec/bundler-audit) - bundler-audit is a patch-level verification tool for Bundler which checks for vulnerable versions of gems and insecure gem sources.
* [Secure Headers ★2241](twitter/secureheaders) -  Secure Headers will automatically apply several headers that are related to security.

## Production
* [Capistrano ★9569](capistrano/capistrano) - Remote multi-server automation tool.
* [Slowpoke ★123](ankane/slowpoke) - Rack::Timeout is great. Slowpoke makes it better.
* [Rack Attack ★3266](kickstarter/rack-attack) - Rack middleware to blocking & throttling.
* [Responders ★1569](plataformatec/responders) - A set of Rails responders to dry up your application.
* [production_rails ★700 ⏳1Y](ankane/production_rails) - Best practices for running Rails in production.
* [Mina ★3536](mina-deploy/mina) - fast deployer and server automation tool.

## Error Logging
* [Rollbar ★273](rollbar/rollbar-gem) - Exception tracking and logging from Ruby to Rollbar.
* [Airbrake ★776](airbrake/airbrake) - Notifier gem for integrating apps with Airbrake
* [Errbit ★3657](errbit/errbit) - Open source notifier gem compliant with Airbrake.

## Database
* [rails_db ★896](igorkasyanchuk/rails_db) - Rails Database Viewer and SQL Query Runner

## Asset Pipeline
* [Alaska ★44](mavenlink/alaska) - ExecJS runtime with persistent connection to nodejs, speeds up your coffeescript compilation process during development and deployment.

## Contribute

Contributions welcome! Read the [contribution guidelines](https://github.com/hothero/awesome-rails-gem/blob/master/contributing.md) first.
---
<p align="center">
	This list is a copy of <a href="hothero/awesome-rails-gem">hothero/awesome-rails-gem</a> with ranks
</p>
<script>
  (function(i,s,o,g,r,a,m){i['GoogleAnalyticsObject']=r;i[r]=i[r]||function(){
  (i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),
  m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)
  })(window,document,'script','https://www.google-analytics.com/analytics.js','ga');

  ga('create', 'UA-100705027-1', 'auto');
  ga('send', 'pageview');

</script>
