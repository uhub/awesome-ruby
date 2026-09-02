# awesome-ruby

A curated list of awesome Ruby frameworks, libraries and software.

* Learning and Reference
	* [Tutorials and Books](#tutorials-and-books)
	* [Examples and Exercises](#examples-and-exercises)
	* [Awesome Lists and Collections](#awesome-lists-and-collections)
* Language and Tooling
	* [Compilers and Interpreters](#compilers-and-interpreters)
	* [Build Systems](#build-systems)
	* [Package Management](#package-management)
	* [Linters and Formatters](#linters-and-formatters)
	* [Debugging and Profiling](#debugging-and-profiling)
	* [Editor and IDE Support](#editor-and-ide-support)
	* [Version Control](#version-control)
* Web
	* [Web Frameworks](#web-frameworks)
	* [HTTP and Networking Clients](#http-and-networking-clients)
	* [API and GraphQL](#api-and-graphql)
	* [Frontend and UI Components](#frontend-and-ui-components)
	* [Web Servers and Proxies](#web-servers-and-proxies)
	* [Scraping and Crawling](#scraping-and-crawling)
* Data and Storage
	* [Databases](#databases)
	* [Database Clients and ORMs](#database-clients-and-orms)
	* [Serialization and Formats](#serialization-and-formats)
	* [Caching and Queues](#caching-and-queues)
	* [Search and Indexing](#search-and-indexing)
* Machine Learning and AI
	* [LLM and Inference](#llm-and-inference)
	* [Machine Learning Frameworks](#machine-learning-frameworks)
	* [Computer Vision](#computer-vision)
	* [Natural Language Processing](#natural-language-processing)
	* [Data Science and Analytics](#data-science-and-analytics)
* Networking and Distributed
	* [Networking](#networking)
	* [RPC and Messaging](#rpc-and-messaging)
	* [Distributed Systems](#distributed-systems)
	* [Cloud and Infrastructure](#cloud-and-infrastructure)
	* [Monitoring and Observability](#monitoring-and-observability)
* User Interface
	* [GUI Toolkits](#gui-toolkits)
	* [Terminal and Console UI](#terminal-and-console-ui)
	* [Mobile](#mobile)
	* [Applications and End User Tools](#applications-and-end-user-tools)
* Graphics and Media
	* [Graphics and Rendering](#graphics-and-rendering)
	* [Game Development](#game-development)
	* [Audio](#audio)
	* [Image and Video](#image-and-video)
* Security
	* [Cryptography](#cryptography)
	* [Security Tools](#security-tools)
	* [Authentication and Authorization](#authentication-and-authorization)
	* [Reverse Engineering](#reverse-engineering)
* Concurrency and Performance
	* [Concurrency and Parallelism](#concurrency-and-parallelism)
	* [Performance and Optimization](#performance-and-optimization)
* Testing and Quality
	* [Testing](#testing)
* Utilities
	* [Command Line Tools](#command-line-tools)
	* [Logging and Configuration](#logging-and-configuration)
	* [Text Processing](#text-processing)
	* [Files and Operating System](#files-and-operating-system)
	* [Date and Time](#date-and-time)
	* [Automation and Scripting](#automation-and-scripting)
	* [General Purpose Libraries](#general-purpose-libraries)
* Science and Math
	* [Mathematics](#mathematics)
	* [Scientific Computing](#scientific-computing)
* [Other](#other)

## Learning and Reference

### Tutorials and Books

* [lewagon/setup](https://github.com/lewagon/setup) - Setup instructions for Le Wagon's students on their first day of AI Software Development Bootcamp
* [fastruby/fast-ruby](https://github.com/fastruby/fast-ruby) - :dash: Writing Fast Ruby :heart_eyes: -- Collect Common Ruby idioms.
* [TheOdinProject/theodinproject](https://github.com/TheOdinProject/theodinproject) - Main website for The Odin Project
* [airbnb/ruby](https://github.com/airbnb/ruby) - Ruby Style Guide
* [railsbridge/docs](https://github.com/railsbridge/docs) - Curriculum for RailsBridge workshops
* [ankane/the-ultimate-guide-to-ruby-timeouts](https://github.com/ankane/the-ultimate-guide-to-ruby-timeouts) - Timeouts for popular Ruby gems
* [franzejr/best-ruby](https://github.com/franzejr/best-ruby) - Ruby Tricks, Idiomatic Ruby, Refactoring and Best Practices
* [brunofacca/zen-rails-security-checklist](https://github.com/brunofacca/zen-rails-security-checklist) - Checklist of security precautions for Ruby on Rails applications.
* [uohzxela/clean-code-ruby](https://github.com/uohzxela/clean-code-ruby) - 🛁 Clean Code concepts adapted for Ruby
* [radar/guides-old](https://github.com/radar/guides-old) - Guides for Ruby and Elixir and whatever else I feel like
* [augustl/net-http-cheat-sheet](https://github.com/augustl/net-http-cheat-sheet) - A collection of Ruby Net::HTTP examples.
* [fpsvogel/learn-ruby](https://github.com/fpsvogel/learn-ruby) - Learning resources for Ruby, Rails, and related skills.
* [evilmartians/terraforming-rails](https://github.com/evilmartians/terraforming-rails) - Terraforming legacy Rails applications guides and tools
* [skmetz/poodr](https://github.com/skmetz/poodr) - Practical Object-Oriented Design in Ruby
* [thoughtbot/ruby-science](https://github.com/thoughtbot/ruby-science) - The reference for writing fantastic Rails applications
* [Shopify/ruby-style-guide](https://github.com/Shopify/ruby-style-guide) - Shopify’s Ruby Style Guide
* [khusnetdinov/ruby.fundamental](https://github.com/khusnetdinov/ruby.fundamental) - :books: Fundamental programming with ruby examples and references. It covers threads, SOLID principles, design patterns, data structures, algorithms. Books for reading. Repo for website https://github.com/khusnetdinov/betterdocs
* [Ada-Developers-Academy/textbook-curriculum](https://github.com/Ada-Developers-Academy/textbook-curriculum) - Ada Developers Academy Online Curriculum

### Examples and Exercises

* [ryanb/ruby-warrior](https://github.com/ryanb/ruby-warrior) - Game written in Ruby for learning Ruby.
* [sagivo/algorithms](https://github.com/sagivo/algorithms) - algorithms playground for common questions
* [design-patterns-in-ruby/design-patterns-in-ruby](https://github.com/design-patterns-in-ruby/design-patterns-in-ruby) - Examples from the book Design Patterns in Ruby by Russ Olsen. # ruby 2.2.0
* [eliotsykes/rspec-rails-examples](https://github.com/eliotsykes/rspec-rails-examples) - RSpec cheatsheet & Rails app: Learn how to expertly test Rails apps from a model codebase *(archived)*
* [tradingview/charting-library-examples](https://github.com/tradingview/charting-library-examples) - Examples of Charting Library integrations with other libraries, frameworks and data transports
* [eliotsykes/real-world-rails](https://github.com/eliotsykes/real-world-rails) - Real World Rails applications and their open source codebases for developers to learn from *(archived)*
* [TheAlgorithms/Ruby](https://github.com/TheAlgorithms/Ruby) - All algorithms implemented in Ruby
* [HipByte/RubyMotionSamples](https://github.com/HipByte/RubyMotionSamples) - A collection of RubyMotion applications for code samples.
* [ledermann/docker-rails](https://github.com/ledermann/docker-rails) - Dockerize Rails 7 with ActionCable, Webpacker, Stimulus, Elasticsearch, Sidekiq *(archived)*
* [piscolomo/ruby-patterns](https://github.com/piscolomo/ruby-patterns) - Examples of Patterns in Ruby
* [kumar91gopi/Algorithms-and-Data-Structures-in-Ruby](https://github.com/kumar91gopi/Algorithms-and-Data-Structures-in-Ruby) - Ruby implementation of Algorithms,Data-structures and programming challenges
* [dennybritz/rails_startup_template](https://github.com/dennybritz/rails_startup_template) - A startup template for Ruby on Rails 4 applications
* [brunofacca/zen-rails-base-app](https://github.com/brunofacca/zen-rails-base-app) - Base application for Ruby on Rails 6 projects. Built to minimize the time spent writing boilerplate code and performing repetitive setup tasks.
* [nickjj/orats](https://github.com/nickjj/orats) - Opinionated rails application templates. *(archived)*
* [rootstrap/rails_api_base](https://github.com/rootstrap/rails_api_base) - API boilerplate project for Ruby on Rails 8
* [exercism/ruby](https://github.com/exercism/ruby) - Exercism exercises in Ruby.
* [avdi/sbpprb](https://github.com/avdi/sbpprb) - Smalltalk Best Practice Patterns in Ruby
* [railstutorial/sample_app](https://github.com/railstutorial/sample_app) - Ruby on Rails Tutorial sample application
* [Haseeb-Qureshi/lets-build-a-blockchain](https://github.com/Haseeb-Qureshi/lets-build-a-blockchain) - A mini cryptocurrency in Ruby

### Awesome Lists and Collections

* [2factorauth/twofactorauth](https://github.com/2factorauth/twofactorauth) - List of sites with two factor auth support which includes SMS, email, phone calls, hardware, and software.
* [hothero/awesome-rails-gem](https://github.com/hothero/awesome-rails-gem) - A collection of awesome Ruby Gems for Rails development.
* [dreikanter/ruby-bookmarks](https://github.com/dreikanter/ruby-bookmarks) - Ruby and Ruby on Rails bookmarks collection
* [arbox/machine-learning-with-ruby](https://github.com/arbox/machine-learning-with-ruby) - Curated list: Resources for machine learning in Ruby
* [remote-jp/remote-in-japan](https://github.com/remote-jp/remote-in-japan) - Tech companies in Japan that hire remote workers.
* [arbox/nlp-with-ruby](https://github.com/arbox/nlp-with-ruby) - Curated List: Practical Natural Language Processing done in Ruby
* [github/brasil](https://github.com/github/brasil) - Recursos e informações do GitHub para a comunidade tech do Brasil. *(archived)*
* [arbox/data-science-with-ruby](https://github.com/arbox/data-science-with-ruby) - Practical Data Science with Ruby based tools.
* [rubytoolbox/rubytoolbox](https://github.com/rubytoolbox/rubytoolbox) - Find actively maintained & popular open source software libraries for the Ruby programming language

## Language and Tooling

### Compilers and Interpreters

* [ruby/ruby](https://github.com/ruby/ruby) - The Ruby Programming Language
* [opal/opal](https://github.com/opal/opal) - Ruby ♥︎ JavaScript
* [jruby/jruby](https://github.com/jruby/jruby) - JRuby, an implementation of Ruby on the JVM
* [truffleruby/truffleruby](https://github.com/truffleruby/truffleruby) - A high performance implementation of the Ruby programming language, built on GraalVM.
* [MacRuby/MacRuby](https://github.com/MacRuby/MacRuby) - MacRuby is an implementation of Ruby 1.9 directly on top of Mac OS X core technologies such as the Objective-C runtime and garbage collector, the LLVM compiler infrastructure and the Foundation and ICU frameworks.
* [natalie-lang/natalie](https://github.com/natalie-lang/natalie) - a work-in-progress Ruby compiler, written in Ruby and C++
* [nathansobo/treetop](https://github.com/nathansobo/treetop) - A Ruby-based parsing DSL based on parsing expression grammars.
* [ruby/ruby.wasm](https://github.com/ruby/ruby.wasm) - ruby.wasm is a collection of WebAssembly ports of the CRuby.
* [tenderlove/asmrepl](https://github.com/tenderlove/asmrepl) - A REPL for x86-64 assembly language
* [chrisseaton/rhizome](https://github.com/chrisseaton/rhizome) - A JIT for Ruby, implemented in pure Ruby
* [ruby-next/ruby-next](https://github.com/ruby-next/ruby-next) - Ruby Next makes modern Ruby code run in older versions and alternative implementations
* [wouterken/crystalruby](https://github.com/wouterken/crystalruby) - Embed Crystal code directly in Ruby
* [rails/execjs](https://github.com/rails/execjs) - Run JavaScript code from Ruby
* [DavidHuie/quartz](https://github.com/DavidHuie/quartz) - A gem for calling Go code from within your Ruby code
* [MagLev/maglev](https://github.com/MagLev/maglev) - GemStone Maglev Ruby Repository *(archived)*
* [opal/opal-rails](https://github.com/opal/opal-rails) - Bringing Ruby to Rails · Rails bindings for Opal
* [seattlerb/ruby_parser](https://github.com/seattlerb/ruby_parser) - ruby_parser is a ruby parser written in pure ruby. It outputs s-expressions which can be manipulated and converted back to ruby via the ruby2ruby gem.
* [jbarnette/johnson](https://github.com/jbarnette/johnson) - Johnson wraps JavaScript in a loving Ruby embrace. *(archived)*
* [headius/rubyflux](https://github.com/headius/rubyflux) - A Ruby static compiler.
* [chriswailes/RLTK](https://github.com/chriswailes/RLTK) - The Ruby Language Toolkit
* [SciRuby/rubex](https://github.com/SciRuby/rubex) - rubex - A Ruby-like language for writing Ruby C extensions.

### Build Systems

* [ruby/rake](https://github.com/ruby/rake) - A make-like build utility for Ruby.
* [CocoaPods/Xcodeproj](https://github.com/CocoaPods/Xcodeproj) - Create and modify Xcode projects from Ruby.
* [ElMassimo/vite_ruby](https://github.com/ElMassimo/vite_ruby) - ⚡️ Vite.js in Ruby, bringing joy to your JavaScript experience
* [jruby/warbler](https://github.com/jruby/warbler) - Warbler chirpily constructs .war files of your Ruby applications.
* [larsch/ocra](https://github.com/larsch/ocra) - One-Click Ruby Application Builder
* [browserify-rails/browserify-rails](https://github.com/browserify-rails/browserify-rails) - Browserify + Rails = a great way to modularize your legacy JavaScript
* [rake-compiler/rake-compiler](https://github.com/rake-compiler/rake-compiler) - Provide a standard and simplified way to build and package Ruby C and Java extensions using Rake as glue.
* [mipearson/webpack-rails](https://github.com/mipearson/webpack-rails) - Integrate webpack with your Ruby on Rails application *(archived)*
* [hone/mruby-cli](https://github.com/hone/mruby-cli) - mruby-cli is a platform to build native command line applications for Linux, Windows, and OS X. It provides the tools necessary for building a standalone binary of your application from any machine. Take advantage of the power of Ruby without the cross-platform dependency headaches that go with it.
* [rayh/xcoder](https://github.com/rayh/xcoder) - ruby wrapper for Xcode build tools to aid automating builds

### Package Management

* [Homebrew/brew](https://github.com/Homebrew/brew) - 🍺 The Package Manager for Everywhere
* [Homebrew/homebrew-core](https://github.com/Homebrew/homebrew-core) - 🍻 Default and OSS formulae (built-from-source packages) for the package manager for everywhere
* [dependabot/dependabot-core](https://github.com/dependabot/dependabot-core) - 🤖 Dependabot's core logic for creating update PRs.
* [Homebrew/homebrew-bundle](https://github.com/Homebrew/homebrew-bundle) - 💀 Homebrew/bundle (merged into Homebrew/brew) *(archived)*
* [rubygems/bundler](https://github.com/rubygems/bundler) - Manage your Ruby application's gem dependencies *(archived)*
* [ruby/rubygems](https://github.com/ruby/rubygems) - Library packaging and distribution for Ruby.
* [Linuxbrew/brew](https://github.com/Linuxbrew/brew) - :beer::penguin: The Homebrew package manager for Linux *(archived)*
* [rubygems/rubygems.org](https://github.com/rubygems/rubygems.org) - The Ruby community's gem hosting service.
* [github/pages-gem](https://github.com/github/pages-gem) - A simple Ruby Gem to bootstrap dependencies for setting up and maintaining a local Jekyll environment in sync with GitHub Pages
* [pivotal/LicenseFinder](https://github.com/pivotal/LicenseFinder) - Find licenses for your project's dependencies.
* [geminabox/geminabox](https://github.com/geminabox/geminabox) - Really simple rubygem hosting
* [DomT4/homebrew-autoupdate](https://github.com/DomT4/homebrew-autoupdate) - :tropical_drink: An easy, convenient way to automatically update Homebrew.
* [oneclick/rubyinstaller](https://github.com/oneclick/rubyinstaller) - RubyInstaller for Windows - Build recipes
* [openSUSE/open-build-service](https://github.com/openSUSE/open-build-service) - Build and distribute Linux packages from sources in an automatic, consistent and reproducible way #obs
* [licensee/licensed](https://github.com/licensee/licensed) - A Ruby gem to cache and verify the licenses of dependencies
* [vertiginous/pik](https://github.com/vertiginous/pik) - Ruby version manager for Windows
* [gel-rb/gel](https://github.com/gel-rb/gel) - A modern gem manager: Gel is a lightweight alternative to Bundler
* [oneclick/rubyinstaller2](https://github.com/oneclick/rubyinstaller2) - MSYS2 based RubyInstaller for Windows
* [svenfuchs/gem-release](https://github.com/svenfuchs/gem-release) - Release your ruby gems with ease.
* [rvm/rubygems-bundler](https://github.com/rvm/rubygems-bundler) - no more `bundle exec ...`

### Linters and Formatters

* [rubocop/rubocop](https://github.com/rubocop/rubocop) - A Ruby static code analyzer and formatter, based on the community Ruby style guide.
* [troessner/reek](https://github.com/troessner/reek) - Code smell detector for Ruby
* [sorbet/sorbet](https://github.com/sorbet/sorbet) - A fast, powerful type checker designed for Ruby
* [whitesmith/rubycritic](https://github.com/whitesmith/rubycritic) - A Ruby code quality reporter
* [standardrb/standard](https://github.com/standardrb/standard) - Ruby's bikeshed-proof linter and formatter 🚲
* [ruby/rbs](https://github.com/ruby/rbs) - The type signature language for Ruby
* [glebm/i18n-tasks](https://github.com/glebm/i18n-tasks) - Manage translation and localization with static analysis, for Ruby i18n
* [markdownlint/markdownlint](https://github.com/markdownlint/markdownlint) - Markdown lint tool
* [DamirSvrtan/fasterer](https://github.com/DamirSvrtan/fasterer) - :zap: Don't make your Rubies go fast. Make them go fasterer ™. :zap:
* [soutaro/steep](https://github.com/soutaro/steep) - Static type checker for Ruby
* [egonSchiele/contracts.ruby](https://github.com/egonSchiele/contracts.ruby) - Contracts for Ruby.
* [PaulTaykalo/swift-scripts](https://github.com/PaulTaykalo/swift-scripts) - Some useful scripts for swift developers
* [ruby-formatter/rufo](https://github.com/ruby-formatter/rufo) - The Ruby Formatter
* [rubocop/rubocop-rails](https://github.com/rubocop/rubocop-rails) - A RuboCop extension focused on enforcing Rails best practices and coding conventions.
* [Shopify/tapioca](https://github.com/Shopify/tapioca) - The swiss army knife of RBI generation
* [rubocop/rubocop-rspec](https://github.com/rubocop/rubocop-rspec) - Code style checking for RSpec files.
* [ruby/typeprof](https://github.com/ruby/typeprof) - An experimental type-level Ruby interpreter for testing and understanding Ruby code
* [makaroni4/sandi_meter](https://github.com/makaroni4/sandi_meter) - Static analysis tool for checking Ruby code for Sandi Metz' rules.
* [rubocop/rubocop-performance](https://github.com/rubocop/rubocop-performance) - An extension of RuboCop focused on code performance checks.
* [yorickpeterse/ruby-lint](https://github.com/yorickpeterse/ruby-lint) - Moved to https://gitlab.com/yorickpeterse/ruby-lint *(archived)*
* [synvert-hq/synvert-ruby](https://github.com/synvert-hq/synvert-ruby) - write snippet code to rewrite your project code
* [github/rubocop-github](https://github.com/github/rubocop-github) - Code style checking for GitHub's Ruby projects
* [chanzuckerberg/sorbet-rails](https://github.com/chanzuckerberg/sorbet-rails) - A set of tools to make the Sorbet typechecker work with Ruby on Rails seamlessly. *(archived)*
* [ruby-syntax-tree/syntax_tree](https://github.com/ruby-syntax-tree/syntax_tree) - A Ruby language formatter written in Ruby
* [tupl-tufts/rdl](https://github.com/tupl-tufts/rdl) - Types, type checking, and contracts for Ruby
* [rails/rubocop-rails-omakase](https://github.com/rails/rubocop-rails-omakase) - Omakase Ruby styling for Rails
* [fastruby/skunk](https://github.com/fastruby/skunk) - A SkunkScore Calculator for Ruby Code -- Find the most complicated code without test coverage!
* [rrrene/inch](https://github.com/rrrene/inch) - A documentation analysis tool for the Ruby language
* [m1foley/fit-commit](https://github.com/m1foley/fit-commit) - A Git hook to validate your commit messages based on community standards.
* [codegram/pelusa](https://github.com/codegram/pelusa) - Static analysis Lint-type tool to improve your OO Ruby code

### Debugging and Profiling

* [pry/pry](https://github.com/pry/pry) - A runtime developer console and IRB alternative with powerful introspection capabilities.
* [awesome-print/awesome_print](https://github.com/awesome-print/awesome_print) - Pretty print your Ruby objects with style -- in full color and with proper indentation
* [MiniProfiler/rack-mini-profiler](https://github.com/MiniProfiler/rack-mini-profiler) - Profiler for your development and production Ruby rack apps.
* [deivid-rodriguez/byebug](https://github.com/deivid-rodriguez/byebug) - Debugging in Ruby
* [peek/peek](https://github.com/peek/peek) - Take a peek into your Rails applications.
* [tmm1/stackprof](https://github.com/tmm1/stackprof) - a sampling call-stack profiler for ruby 2.2+
* [ruby-prof/ruby-prof](https://github.com/ruby-prof/ruby-prof) - A ruby profiler. See https://ruby-prof.github.io for more information.
* [deivid-rodriguez/pry-byebug](https://github.com/deivid-rodriguez/pry-byebug) - Step-by-step debugging and stack navigation in Pry
* [SamSaffron/memory_profiler](https://github.com/SamSaffron/memory_profiler) - memory_profiler for ruby
* [tmm1/rbtrace](https://github.com/tmm1/rbtrace) - like strace, but for ruby code
* [ruby/debug](https://github.com/ruby/debug) - Debugging functionality for Ruby
* [jhawthorn/vernier](https://github.com/jhawthorn/vernier) - 📏 next generation CRuby profiler
* [brunofacca/active-record-query-trace](https://github.com/brunofacca/active-record-query-trace) - Rails plugin that logs/displays a backtrace of all SQL queries executed by Active Record
* [amazing-print/amazing_print](https://github.com/amazing-print/amazing_print) - Pretty print your Ruby objects with style -- in full color and with proper indentation
* [0x2c7/ruby_jard](https://github.com/0x2c7/ruby_jard) - Just Another Ruby Debugger. Provide a rich Terminal UI that visualizes everything your need, navigates your program with pleasure, stops at matter places only, reduces manual and mental efforts. You can now focus on real debugging. *(archived)*
* [ileitch/hijack](https://github.com/ileitch/hijack) - Provides an irb session to a running ruby process.
* [nixme/pry-debugger](https://github.com/nixme/pry-debugger) - Pry navigation commands via debugger (formerly ruby-debug)
* [aderyabin/sniffer](https://github.com/aderyabin/sniffer) - Log and Analyze Outgoing HTTP Requests
* [richpeck/exception_handler](https://github.com/richpeck/exception_handler) - Ruby on Rails Custom Error Pages
* [rollbar/rollbar-gem](https://github.com/rollbar/rollbar-gem) - Exception tracking and logging from Ruby to Rollbar
* [st0012/object_tracer](https://github.com/st0012/object_tracer) - ObjectTracer tracks objects and records their activities *(archived)*

### Editor and IDE Support

* [Shopify/ruby-lsp](https://github.com/Shopify/ruby-lsp) - An opinionated language server for Ruby
* [castwide/solargraph](https://github.com/castwide/solargraph) - A Ruby language server.
* [drnic/ruby-on-rails-tmbundle](https://github.com/drnic/ruby-on-rails-tmbundle) - Ruby on Rails TextMate bundle [Learn it with PeepCode - http://peepcode.com/products/textmate-for-rails-2]
* [rubychan/coderay](https://github.com/rubychan/coderay) - Fast and easy syntax highlighting for selected languages, written in Ruby.
* [Shopify/ruby-lsp-rails](https://github.com/Shopify/ruby-lsp-rails) - A Ruby LSP add-on for Rails
* [tmm1/ripper-tags](https://github.com/tmm1/ripper-tags) - fast, accurate ctags generator for ruby source code using Ripper

### Version Control

* [mojombo/grit](https://github.com/mojombo/grit) - **Grit is no longer maintained. Check out libgit2/rugged.** Grit gives you object oriented read/write access to Git repositories via Ruby.
* [ruby-git/ruby-git](https://github.com/ruby-git/ruby-git) - Ruby/Git is a Ruby library that can be used to create, read and manipulate Git repositories by wrapping system calls to the git binary.

## Web

### Web Frameworks

* [rails/rails](https://github.com/rails/rails) - Ruby on Rails
* [sinatra/sinatra](https://github.com/sinatra/sinatra) - Classy web-development dressed in a DSL (official / canonical repo)
* [activeadmin/activeadmin](https://github.com/activeadmin/activeadmin) - The administration framework for Ruby on Rails applications.
* [hanami/hanami](https://github.com/hanami/hanami) - A flexible framework for maintainable Ruby apps
* [thoughtbot/administrate](https://github.com/thoughtbot/administrate) - A Rails engine that helps you put together a super-flexible admin dashboard.
* [drapergem/draper](https://github.com/drapergem/draper) - Decorators/View-Models for Rails Applications
* [trailblazer/trailblazer](https://github.com/trailblazer/trailblazer) - The advanced business logic framework for Ruby.
* [padrino/padrino-framework](https://github.com/padrino/padrino-framework) - Padrino is a full-stack ruby framework built upon Sinatra.
* [voltrb/volt](https://github.com/voltrb/volt) - A Ruby web framework where your Ruby runs on both server and client
* [rubyonjets/jets](https://github.com/rubyonjets/jets) - Ruby on Jets
* [heartcombo/responders](https://github.com/heartcombo/responders) - A set of Rails responders to dry up your application
* [TrestleAdmin/trestle](https://github.com/TrestleAdmin/trestle) - A modern, responsive admin framework for Ruby on Rails
* [bullet-train-co/bullet_train](https://github.com/bullet-train-co/bullet_train) - The Open Source Ruby on Rails SaaS Template
* [avo-hq/avo](https://github.com/avo-hq/avo) - The Essential Toolkit for building Internal Tools and admin panels with Ruby on Rails
* [soveran/cuba](https://github.com/soveran/cuba) - Rum based microframework for web development.
* [rage-rb/rage](https://github.com/rage-rb/rage) - Fiber-based Ruby web framework combining Rails ergonomics with a unified runtime
* [bridgetownrb/bridgetown](https://github.com/bridgetownrb/bridgetown) - A next-generation progressive site generator & fullstack framework, powered by Ruby
* [amatsuda/active_decorator](https://github.com/amatsuda/active_decorator) - ORM agnostic truly Object-Oriented view helper for Rails 4, 5, 6, 7, and 8
* [jekyll/jekyll-sitemap](https://github.com/jekyll/jekyll-sitemap) - Jekyll plugin to silently generate a sitemaps.org compliant sitemap for your Jekyll site
* [gma/nesta](https://github.com/gma/nesta) - File Based CMS and Static Site Generator
* [jekyll/jekyll-feed](https://github.com/jekyll/jekyll-feed) - :memo: A Jekyll plugin to generate an Atom (RSS-like) feed of your Jekyll posts
* [midori-rb/midori.rb](https://github.com/midori-rb/midori.rb) - Lightweight, Flexible and Fast Ruby Web Framework
* [pakyow/pakyow](https://github.com/pakyow/pakyow) - Design-First Web Framework
* [excid3/madmin](https://github.com/excid3/madmin) - A robust Admin Interface for Ruby on Rails apps
* [upmin/upmin-admin-ruby](https://github.com/upmin/upmin-admin-ruby) - Framework for creating powerful admin backends with minimal effort in Ruby on Rails.
* [mattt/sinatra-param](https://github.com/mattt/sinatra-param) - Parameter Validation & Type Coercion for Sinatra
* [varvet/godmin](https://github.com/varvet/godmin) - Admin framework for Rails 5+
* [asakusarb/action_args](https://github.com/asakusarb/action_args) - Controller action arguments parameterizer for Rails 4+ & Ruby 2.0+
* [raggi/async_sinatra](https://github.com/raggi/async_sinatra) - A plugin for Sinatra to provide a DSL extension for using Thin for asynchronous responses

### HTTP and Networking Clients

* [jnunemaker/httparty](https://github.com/jnunemaker/httparty) - :tada: Makes http fun again!
* [rest-client/rest-client](https://github.com/rest-client/rest-client) - Simple HTTP and REST client for Ruby, inspired by microframework syntax for specifying actions.
* [sferik/twitter-ruby](https://github.com/sferik/twitter-ruby) - A Ruby interface to the Twitter API.
* [octokit/octokit.rb](https://github.com/octokit/octokit.rb) - Ruby toolkit for the GitHub API
* [arsduo/koala](https://github.com/arsduo/koala) - A lightweight Facebook library supporting the Graph, Marketing, and Atlas APIs, realtime updates, test users, and OAuth.
* [httprb/http](https://github.com/httprb/http) - HTTP (The Gem! a.k.a. http.rb) - a fast Ruby HTTP client with a chainable API, streaming support, and timeouts
* [googleapis/google-api-ruby-client](https://github.com/googleapis/google-api-ruby-client) - REST client for Google APIs
* [stripe/stripe-ruby](https://github.com/stripe/stripe-ruby) - Ruby library for the Stripe API.
* [savonrb/savon](https://github.com/savonrb/savon) - Heavy metal SOAP client
* [timdorr/tesla-api](https://github.com/timdorr/tesla-api) - 🚘 A Ruby gem and unofficial documentation of Tesla's JSON API for the Model S, 3, X, and Y.
* [gimite/google-drive-ruby](https://github.com/gimite/google-drive-ruby) - A Ruby library to read/write files/spreadsheets in Google Drive/Docs.
* [slack-notifier/slack-notifier](https://github.com/slack-notifier/slack-notifier) - A simple wrapper for posting to slack channels
* [facebookarchive/instagram-ruby-gem](https://github.com/facebookarchive/instagram-ruby-gem) - The official gem for the Instagram API *(archived)*
* [twilio/twilio-ruby](https://github.com/twilio/twilio-ruby) - A Ruby gem for communicating with the Twilio API and generating TwiML
* [taf2/curb](https://github.com/taf2/curb) - Ruby bindings for libcurl
* [slack-ruby/slack-ruby-client](https://github.com/slack-ruby/slack-ruby-client) - A ruby client for the Slack Web and Event APIs.
* [igrigorik/em-http-request](https://github.com/igrigorik/em-http-request) - Asynchronous HTTP Client (EventMachine + Ruby)
* [piotrmurach/github](https://github.com/piotrmurach/github) - Ruby interface to GitHub API
* [excon/excon](https://github.com/excon/excon) - Usable, fast, simple HTTP 1.1 for Ruby
* [Shopify/shopify-api-ruby](https://github.com/Shopify/shopify-api-ruby) - ShopifyAPI is a lightweight gem for accessing the Shopify admin REST and GraphQL web services.
* [NARKOZ/gitlab](https://github.com/NARKOZ/gitlab) - Ruby wrapper and CLI for the GitLab REST API
* [janko/down](https://github.com/janko/down) - Streaming downloads using Net::HTTP, http.rb or HTTPX
* [balvig/spyke](https://github.com/balvig/spyke) - Interact with REST services in an ActiveRecord-like manner
* [restforce/restforce](https://github.com/restforce/restforce) - A Ruby client for the Salesforce REST API.
* [hexgnu/linkedin](https://github.com/hexgnu/linkedin) - Ruby wrapper for the LinkedIn API
* [tansengming/stripe-rails](https://github.com/tansengming/stripe-rails) - A Rails Engine for integrating with Stripe
* [claudiob/yt](https://github.com/claudiob/yt) - The reliable YouTube API Ruby client
* [guilhermesad/rspotify](https://github.com/guilhermesad/rspotify) - A ruby wrapper for the Spotify Web API
* [chloerei/alipay](https://github.com/chloerei/alipay) - Unofficial alipay ruby gem
* [jeremytregunna/ruby-trello](https://github.com/jeremytregunna/ruby-trello) - Implementation of the Trello API for Ruby
* [nahi/httpclient](https://github.com/nahi/httpclient) - 'httpclient' gives something like the functionality of libwww-perl (LWP) in Ruby.
* [discordrb/discordrb](https://github.com/discordrb/discordrb) - Discord API for Ruby
* [sumoheavy/jira-ruby](https://github.com/sumoheavy/jira-ruby) - A Ruby gem for the JIRA REST API
* [Fosome/garb](https://github.com/Fosome/garb) - A Ruby wrapper for the Google Analytics API
* [sendgrid/sendgrid-ruby](https://github.com/sendgrid/sendgrid-ruby) - The Official Twilio SendGrid Led, Community Driven Ruby API Library
* [shardlab/discordrb](https://github.com/shardlab/discordrb) - Discord API for Ruby
* [kylejginavan/youtube_it](https://github.com/kylejginavan/youtube_it) - An object-oriented Ruby wrapper for the YouTube GData API
* [mislav/instagram](https://github.com/mislav/instagram) - The first Instagram website and lightweight API HTTP client *(archived)*
* [hakanensari/vacuum](https://github.com/hakanensari/vacuum) - Amazon Creators API in Ruby
* [jugend/amazon-ecs](https://github.com/jugend/amazon-ecs) - Amazon Product Advertising Ruby API
* [maccman/nestful](https://github.com/maccman/nestful) - Simple Ruby HTTP/REST client with a sane API
* [ostinelli/apnotic](https://github.com/ostinelli/apnotic) - A Ruby APNs HTTP/2 gem able to provide instant feedback.
* [hanklords/flickraw](https://github.com/hanklords/flickraw) - Ruby library to access flickr api.
* [line/line-bot-sdk-ruby](https://github.com/line/line-bot-sdk-ruby) - LINE Messaging API SDK for Ruby
* [mailgun/mailgun-ruby](https://github.com/mailgun/mailgun-ruby) - Mailgun's Official Ruby Library
* [saberma/china_sms](https://github.com/saberma/china_sms) - 中国各个短信平台 Ruby 接口，现支持云片网、推立方、亿美软通、短信宝、畅友网络
* [philnash/bitly](https://github.com/philnash/bitly) - 🗜 A Ruby wrapper for the bit.ly API
* [braintree/braintree_ruby](https://github.com/braintree/braintree_ruby) - Braintree Ruby library
* [adelevie/parse-ruby-client](https://github.com/adelevie/parse-ruby-client) - A simple Ruby client for the parse.com REST API
* [interagent/heroics](https://github.com/interagent/heroics) - Ruby HTTP client for APIs represented with JSON schema
* [lanrion/weixin_rails_middleware](https://github.com/lanrion/weixin_rails_middleware) - 微信集成 ruby weixin_rails_middleware for integration weixin.
* [tpitale/legato](https://github.com/tpitale/legato) - Google Analytics Reporting API Client for Ruby

### API and GraphQL

* [ruby-grape/grape](https://github.com/ruby-grape/grape) - An opinionated framework for creating REST-like APIs in Ruby.
* [rmosolgo/graphql-ruby](https://github.com/rmosolgo/graphql-ruby) - Ruby implementation of GraphQL
* [fixerAPI/fixer](https://github.com/fixerAPI/fixer) - A foreign exchange rates and currency conversion API
* [Apipie/apipie-rails](https://github.com/Apipie/apipie-rails) - Ruby on Rails API documentation tool
* [lineofflight/frankfurter](https://github.com/lineofflight/frankfurter) - 💱 Currency data API
* [zipmark/rspec_api_documentation](https://github.com/zipmark/rspec_api_documentation) - Automatically generate API documentation from RSpec
* [exAspArk/batch-loader](https://github.com/exAspArk/batch-loader) - :zap: Powerful tool for avoiding N+1 DB or HTTP queries
* [ruby-grape/grape-swagger](https://github.com/ruby-grape/grape-swagger) - Add OAPI/swagger v2.0 compliant documentation to your grape API
* [graphiti-api/graphiti](https://github.com/graphiti-api/graphiti) - Stylish Graph APIs, built on JSON:API
* [bploetz/versionist](https://github.com/bploetz/versionist) - A plugin for versioning Rails based RESTful APIs. *(archived)*
* [seven1m/bible_api](https://github.com/seven1m/bible_api) - Ruby web app that serves JSON API for open and public domain bibles
* [interagent/pliny](https://github.com/interagent/pliny) - An opinionated toolkit for writing excellent APIs in Ruby.
* [ruby-grape/grape-entity](https://github.com/ruby-grape/grape-entity) - An API focused facade that sits on top of an object model.
* [davidcelis/api-pagination](https://github.com/davidcelis/api-pagination) - :page_facing_up: Link header pagination for Rails and Grape APIs.
* [bwillis/versioncake](https://github.com/bwillis/versioncake) - :cake: Version Cake is an unobtrusive way to version APIs in your Rails or Rack apps
* [fotinakis/swagger-blocks](https://github.com/fotinakis/swagger-blocks) - Define and serve live-updating Swagger JSON for Ruby apps. *(archived)*
* [stitchfix/stitches](https://github.com/stitchfix/stitches) - Create a Microservice in Rails with minimal ceremony
* [brettchalupa/graphql-docs](https://github.com/brettchalupa/graphql-docs) - Easily generate beautiful documentation from your GraphQL schema.
* [fabrik42/acts_as_api](https://github.com/fabrik42/acts_as_api) - makes creating API responses in Rails easy and fun

### Frontend and UI Components

* [kaminari/kaminari](https://github.com/kaminari/kaminari) - ⚡ A Scope & Engine based, clean, powerful, customizable and sophisticated paginator for Ruby webapps
* [heartcombo/simple_form](https://github.com/heartcombo/simple_form) - Forms made easy for Rails! It's tied to a simple DSL, with no opinion on markup.
* [mislav/will_paginate](https://github.com/mislav/will_paginate) - Pagination library for Rails and other Ruby applications
* [ddnexus/pagy](https://github.com/ddnexus/pagy) - Agnostic pagination in plain ruby
* [ViewComponent/view_component](https://github.com/ViewComponent/view_component) - A framework for building reusable, testable & encapsulated view components in Ruby on Rails.
* [trailblazer/cells](https://github.com/trailblazer/cells) - View components for Ruby and Rails.
* [kpumuk/meta-tags](https://github.com/kpumuk/meta-tags) - Search Engine Optimization (SEO) for Ruby on Rails applications.
* [DavyJonesLocker/client_side_validations](https://github.com/DavyJonesLocker/client_side_validations) - Client Side Validations made easy for Ruby on Rails
* [hotwired/turbo-rails](https://github.com/hotwired/turbo-rails) - Use Turbo in your Ruby on Rails app
* [stimulusreflex/stimulus_reflex](https://github.com/stimulusreflex/stimulus_reflex) - Build reactive applications with the Rails tooling you already know and love.
* [twbs/bootstrap-rubygem](https://github.com/twbs/bootstrap-rubygem) - Bootstrap rubygem for Rails / Sprockets / Hanami / etc
* [bootstrap-ruby/bootstrap_form](https://github.com/bootstrap-ruby/bootstrap_form) - Official repository of the bootstrap_form gem, a Rails form builder that makes it super easy to create beautiful-looking forms using Bootstrap 5.
* [yippee-fun/phlex](https://github.com/yippee-fun/phlex) - Object-oriented views in Ruby.
* [Mange/roadie](https://github.com/Mange/roadie) - Making HTML emails comfortable for the Ruby rockstars
* [ai/autoprefixer-rails](https://github.com/ai/autoprefixer-rails) - Autoprefixer for Ruby and Ruby on Rails
* [bogdan/datagrid](https://github.com/bogdan/datagrid) - Gem to create tables grids with sortable columns and filters
* [ruby-ui/ruby_ui](https://github.com/ruby-ui/ruby_ui) - Ruby gem for RubyUI Components
* [hotwired/hotwire-rails](https://github.com/hotwired/hotwire-rails) - Use Hotwire in your Ruby on Rails app *(archived)*
* [weppos/breadcrumbs_on_rails](https://github.com/weppos/breadcrumbs_on_rails) - A simple Ruby on Rails plugin for creating and managing a breadcrumb navigation.
* [FortAwesome/font-awesome-sass](https://github.com/FortAwesome/font-awesome-sass) - Font-Awesome Sass gem for use in Ruby/Rails projects
* [lassebunk/gretel](https://github.com/lassebunk/gretel) - Flexible Ruby on Rails breadcrumbs plugin.
* [codeplant/simple-navigation](https://github.com/codeplant/simple-navigation) - A ruby gem for creating navigations (with multiple levels) for your Rails, Sinatra or Padrino applications. Render your navigation as html list, link list or breadcrumbs.
* [livingstyleguide/livingstyleguide](https://github.com/livingstyleguide/livingstyleguide) - Easily create front-end style guides with Markdown and Sass/SCSS.
* [rails/sass-rails](https://github.com/rails/sass-rails) - Ruby on Rails stylesheet engine for Sass
* [claudiob/bh](https://github.com/claudiob/bh) - Bootstrap Helpers for Ruby
* [activeadmin/arbre](https://github.com/activeadmin/arbre) - An Object Oriented DOM Tree in Ruby
* [jamesmartin/inline_svg](https://github.com/jamesmartin/inline_svg) - Embed SVG documents in your Rails views and style them with CSS
* [stimulusreflex/cable_ready](https://github.com/stimulusreflex/cable_ready) - Use simple commands on the server to control client browsers in real-time
* [unabridged/motion](https://github.com/unabridged/motion) - Reactive frontend UI components for Rails in pure Ruby
* [josefarias/hotwire_combobox](https://github.com/josefarias/hotwire_combobox) - An accessible autocomplete for Ruby on Rails.
* [jbox-web/ajax-datatables-rails](https://github.com/jbox-web/ajax-datatables-rails) - A wrapper around DataTable's ajax methods that allow synchronization with server-side pagination in a Rails app
* [clearwater-rb/clearwater](https://github.com/clearwater-rb/clearwater) - Component-based Ruby front-end framework
* [primer/view_components](https://github.com/primer/view_components) - ViewComponents for the Primer Design System
* [matestack/matestack-ui-core](https://github.com/matestack/matestack-ui-core) - Component based web UIs in pure Ruby for Rails. Boost your productivity & easily create component based web UIs in pure Ruby.
* [zetachang/react.rb](https://github.com/zetachang/react.rb) - Opal Ruby wrapper of React.js library.
* [styd/apexcharts.rb](https://github.com/styd/apexcharts.rb) - Beautiful and interactive visualizations for your ruby web pages powered by ApexCharts.JS. :bar_chart:
* [Sology/smart_listing](https://github.com/Sology/smart_listing) - Ruby on Rails data listing gem with built-in sorting, filtering and in-place editing.
* [lassebunk/metamagic](https://github.com/lassebunk/metamagic) - Simple Ruby on Rails plugin for creating meta tags.
* [winston/google_visualr](https://github.com/winston/google_visualr) - A Ruby Gem for the Google Visualization API. Write Ruby code. Generate Javascript. Display a Google Chart.
* [komposable/komponent](https://github.com/komposable/komponent) - An opinionated way of organizing front-end code in Ruby on Rails, based on components
* [kete/tiny_mce](https://github.com/kete/tiny_mce) - A Ruby on Rails plugin (pre-Rails 3.1) that allows easy implementation of the TinyMCE editor into your applications.

### Web Servers and Proxies

* [puma/puma](https://github.com/puma/puma) - A Ruby/Rack web server built for parallelism
* [rack/rack](https://github.com/rack/rack) - A modular Ruby web server interface.
* [socketry/falcon](https://github.com/socketry/falcon) - A high-performance web server for Ruby, supporting HTTP/1, HTTP/2 and TLS.
* [postrank-labs/goliath](https://github.com/postrank-labs/goliath) - Goliath is a non-blocking Ruby web server framework
* [macournoyer/thin](https://github.com/macournoyer/thin) - A very fast & simple Ruby web server *(archived)*
* [dryruby/rack-throttle](https://github.com/dryruby/rack-throttle) - Rack middleware for rate-limiting incoming HTTP requests.
* [webmachine/webmachine-ruby](https://github.com/webmachine/webmachine-ruby) - Webmachine, the HTTP toolkit (in Ruby)
* [jlong/serve](https://github.com/jlong/serve) - Serve is a small Rack-based web server and rapid prototyping framework for Web applications (specifically Rails apps). Serve is meant to be a lightweight version of the Views part of the Rails MVC. This makes Serve an ideal framework for prototyping Rails applications or creating simple websites. Serve has full support for Rails-style partials and layouts.
* [igrigorik/em-proxy](https://github.com/igrigorik/em-proxy) - EventMachine Proxy DSL for writing high-performance transparent / intercepting proxies in Ruby
* [mojombo/proxymachine](https://github.com/mojombo/proxymachine) - A simple TCP routing proxy built on EventMachine that lets you configure the routing logic in Ruby.
* [torquebox/torquebox](https://github.com/torquebox/torquebox) - TorqueBox Ruby Platform *(archived)*

### Scraping and Crawling

* [sparklemotion/mechanize](https://github.com/sparklemotion/mechanize) - Mechanize is a ruby library that makes automated web interaction easy.
* [rubycdp/ferrum](https://github.com/rubycdp/ferrum) - Headless Chrome Ruby API
* [watir/watir](https://github.com/watir/watir) - Watir Powered By Selenium
* [felipecsl/wombat](https://github.com/felipecsl/wombat) - Lightweight Ruby web crawler/scraper with an elegant DSL which extracts structured data from pages.
* [vifreefly/kimuraframework](https://github.com/vifreefly/kimuraframework) - Write web scrapers in Ruby using a clean, AI-assisted DSL. Kimurai uses AI to figure out where the data lives, then caches the selectors and scrapes with pure Ruby. Get the intelligence of an LLM without the per-request latency or token costs.
* [jaimeiniesta/metainspector](https://github.com/jaimeiniesta/metainspector) - Ruby gem for web scraping purposes. It scrapes a given URL, and returns you its title, meta description, meta keywords, links, images...
* [leonid-shevtsov/headless](https://github.com/leonid-shevtsov/headless) - Create a virtual X screen from Ruby, record videos and take screenshots.
* [cantino/ruby-readability](https://github.com/cantino/ruby-readability) - Port of arc90's readability project to Ruby
* [postmodern/spidr](https://github.com/postmodern/spidr) - A versatile Ruby web spidering library that can spider a site, multiple domains, certain links or infinitely. Spidr is designed to be fast and easy to use.
* [rubycdp/vessel](https://github.com/rubycdp/vessel) - Fast high-level web crawling Ruby framework
* [gottfrois/link_thumbnailer](https://github.com/gottfrois/link_thumbnailer) - Ruby gem that fetches images and metadata from a given URL. Much like popular social website with link preview.
* [mynyml/harmony](https://github.com/mynyml/harmony) - Javascript + DOM in your ruby, the simple way

## Data and Storage

### Databases

* [jeremycole/innodb_ruby](https://github.com/jeremycole/innodb_ruby) - A parser for InnoDB file formats, in Ruby
* [RailsEventStore/rails_event_store](https://github.com/RailsEventStore/rails_event_store) - A Ruby implementation of an Event Store based on Active Record
* [shayonj/pg_easy_replicate](https://github.com/shayonj/pg_easy_replicate) - Easily setup logical replication and switchover to new database with minimal downtime
* [pauldowman/gitmodel](https://github.com/pauldowman/gitmodel) - (Old/dead) An ActiveModel-compliant persistence framework for Ruby that uses Git for versioning and remote syncing.

### Database Clients and ORMs

* [paper-trail-gem/paper_trail](https://github.com/paper-trail-gem/paper_trail) - Track changes to your rails models
* [norman/friendly_id](https://github.com/norman/friendly_id) - FriendlyId is the “Swiss Army bulldozer” of slugging and permalink plugins for ActiveRecord. It allows you to create pretty URL’s and work with human-friendly strings as if they were numeric ids for ActiveRecord models.
* [activerecord-hackery/ransack](https://github.com/activerecord-hackery/ransack) - Object-based searching.
* [jeremyevans/sequel](https://github.com/jeremyevans/sequel) - Sequel: The Database Toolkit for Ruby
* [ctran/annotate_models](https://github.com/ctran/annotate_models) - Annotate Rails classes with schema and routes info
* [redis/redis-rb](https://github.com/redis/redis-rb) - A Ruby client library for Redis
* [mongodb/mongoid](https://github.com/mongodb/mongoid) - The Official Ruby Object Mapper for MongoDB
* [scenic-views/scenic](https://github.com/scenic-views/scenic) - Versioned database views for Rails
* [collectiveidea/audited](https://github.com/collectiveidea/audited) - Audited (formerly acts_as_audited) is an ORM extension that logs all changes to your Rails models.
* [public-activity/public_activity](https://github.com/public-activity/public_activity) - Easy activity tracking for models - similar to Github's Public Activity
* [thiagopradi/octopus](https://github.com/thiagopradi/octopus) - Database Sharding for ActiveRecord
* [brianmario/mysql2](https://github.com/brianmario/mysql2) - A modern, simple and very fast Mysql library for Ruby - binding to libmysql
* [magnusvk/counter_culture](https://github.com/magnusvk/counter_culture) - Turbo-charged counter caches for your Rails app.
* [rom-rb/rom](https://github.com/rom-rb/rom) - Data mapping and persistence toolkit for Ruby
* [nateware/redis-objects](https://github.com/nateware/redis-objects) - Map Redis types directly to Ruby objects
* [remi/her](https://github.com/remi/her) - Her is an ORM (Object Relational Mapper) that maps REST resources to Ruby objects. It is designed to build applications that are powered by a RESTful API instead of a database.
* [ClosureTree/closure_tree](https://github.com/ClosureTree/closure_tree) - Easily and efficiently make your ActiveRecord models support hierarchies
* [gregnavis/active_record_doctor](https://github.com/gregnavis/active_record_doctor) - Identify database issues before they hit production.
* [brainspec/enumerize](https://github.com/brainspec/enumerize) - Enumerated attributes with I18n and ActiveRecord/Mongoid support
* [mperham/connection_pool](https://github.com/mperham/connection_pool) - Generic connection pooling for Ruby
* [mongomapper/mongomapper](https://github.com/mongomapper/mongomapper) - A Ruby Object Mapper for Mongo
* [plentz/lol_dba](https://github.com/plentz/lol_dba) - lol_dba is a small package of rake tasks that scan your application models and displays a list of columns that probably should be indexed. Also, it can generate .sql migration scripts.
* [jalkoby/squasher](https://github.com/jalkoby/squasher) - Squasher - squash your old migrations in a single command
* [mongodb/mongo-ruby-driver](https://github.com/mongodb/mongo-ruby-driver) - The Official MongoDB Ruby Driver
* [neo4jrb/activegraph](https://github.com/neo4jrb/activegraph) - An active model wrapper for the Neo4j Graph Database for Ruby.
* [soveran/ohm](https://github.com/soveran/ohm) - Object-Hash Mapping for Redis
* [Shopify/maintenance_tasks](https://github.com/Shopify/maintenance_tasks) - A Rails engine for queueing and managing data migrations.
* [DmitryTsepelev/store_model](https://github.com/DmitryTsepelev/store_model) - Work with JSON-backed attributes as ActiveRecord-ish models
* [djezzzl/database_consistency](https://github.com/djezzzl/database_consistency) - The tool to avoid various issues due to inconsistencies and inefficiencies between a database schema and application models.
* [madeintandem/jsonb_accessor](https://github.com/madeintandem/jsonb_accessor) - Adds typed jsonb backed fields to your ActiveRecord models.
* [makandra/active_type](https://github.com/makandra/active_type) - Make any Ruby object quack like ActiveRecord
* [ridgepole/ridgepole](https://github.com/ridgepole/ridgepole) - Ridgepole is a tool to manage DB schema. It defines DB schema using Rails DSL, and updates DB schema according to DSL. (like Chef/Puppet)
* [rails-sqlserver/activerecord-sqlserver-adapter](https://github.com/rails-sqlserver/activerecord-sqlserver-adapter) - SQL Server Adapter For Rails
* [rgeo/activerecord-postgis-adapter](https://github.com/rgeo/activerecord-postgis-adapter) - ActiveRecord connection adapter for PostGIS, based on postgresql and rgeo
* [sparklemotion/sqlite3-ruby](https://github.com/sparklemotion/sqlite3-ruby) - Ruby bindings for the SQLite3 embedded database
* [amoeba-rb/amoeba](https://github.com/amoeba-rb/amoeba) - A ruby gem to allow the copying of ActiveRecord objects and their associated children, configurable with a DSL on the model
* [fatkodima/online_migrations](https://github.com/fatkodima/online_migrations) - Catch unsafe PostgreSQL migrations in development and run them easier in production (code helpers for table/column renaming, changing column type, adding columns with default, background migrations, etc).
* [ledermann/unread](https://github.com/ledermann/unread) - Handle unread records and mark them as read with Ruby on Rails
* [DmitryTsepelev/ar_lazy_preload](https://github.com/DmitryTsepelev/ar_lazy_preload) - Lazy loading associations for the ActiveRecord models
* [ClosureTree/with_advisory_lock](https://github.com/ClosureTree/with_advisory_lock) - Advisory locking for ActiveRecord
* [github/github-ds](https://github.com/github/github-ds) - A collection of Ruby libraries for working with SQL on top of ActiveRecord's connection
* [nullobject/rein](https://github.com/nullobject/rein) - Database constraints made easy for ActiveRecord.
* [cassandra-rb/cassandra](https://github.com/cassandra-rb/cassandra) - A Ruby client for the Cassandra distributed database
* [rmm5t/strip_attributes](https://github.com/rmm5t/strip_attributes) - :hocho: An ActiveModel extension that automatically strips all attributes of leading and trailing whitespace before validation. If the attribute is blank, it strips the value to nil.
* [afair/postgresql_cursor](https://github.com/afair/postgresql_cursor) - ActiveRecord PostgreSQL Adapter extension for using a cursor to return a large result set
* [drwl/annotaterb](https://github.com/drwl/annotaterb) - A Ruby Gem that adds annotations to your Rails models and route files.
* [riak-ripple/ripple](https://github.com/riak-ripple/ripple) - A rich Ruby modeling layer for Riak, Basho's distributed database
* [rails-sqlserver/tiny_tds](https://github.com/rails-sqlserver/tiny_tds) - TinyTDS - Simple and fast FreeTDS bindings for Ruby using DB-Library.
* [Dynamoid/dynamoid](https://github.com/Dynamoid/dynamoid) - Ruby ORM for Amazon's DynamoDB.
* [maxdemarzi/neography](https://github.com/maxdemarzi/neography) - A thin Ruby wrapper to the Neo4j Rest API
* [rtomayko/replicate](https://github.com/rtomayko/replicate) - Dump and load relational objects between Ruby environments. *(archived)*
* [toptal/database_validations](https://github.com/toptal/database_validations) - Database validations for ActiveRecord
* [evilmartians/evil-seed](https://github.com/evilmartians/evil-seed) - A Gem for creating partial anonymized dumps of your database using your app model relations.
* [LendingHome/zero_downtime_migrations](https://github.com/LendingHome/zero_downtime_migrations) - Zero downtime migrations with ActiveRecord 3+ and PostgreSQL *(archived)*
* [cequel/cequel](https://github.com/cequel/cequel) - Ruby ORM for Cassandra with CQL3
* [rkrage/pg_party](https://github.com/rkrage/pg_party) - ActiveRecord PostgreSQL Partitioning
* [glebm/order_query](https://github.com/glebm/order_query) - Find next / previous Active Record(s) in one query
* [couchrest/couchrest](https://github.com/couchrest/couchrest) - A minimalist CouchDB client in ruby
* [mdeering/attribute_normalizer](https://github.com/mdeering/attribute_normalizer) - Adds the ability to normalize attributes cleanly with code blocks and predefined normalizers
* [hanami/model](https://github.com/hanami/model) - Ruby persistence framework with entities and repositories *(archived)*

### Serialization and Formats

* [rails-api/active_model_serializers](https://github.com/rails-api/active_model_serializers) - ActiveModel::Serializer implementation and Rails hooks
* [Netflix/fast_jsonapi](https://github.com/Netflix/fast_jsonapi) - No Longer Maintained - A lightning fast JSON:API serializer for Ruby Objects.
* [nesquena/rabl](https://github.com/nesquena/rabl) - General ruby templating with json, bson, xml, plist and msgpack support
* [voxpupuli/json-schema](https://github.com/voxpupuli/json-schema) - Ruby JSON Schema Validator
* [tilo/smarter_csv](https://github.com/tilo/smarter_csv) - Fastest end-to-end CSV ingestion for Ruby (with C acceleration). SmarterCSV auto-detects formats, applies smart defaults, and returns Rails-ready hashes for seamless use with ActiveRecord, Sidekiq, parallel jobs, and S3 pipelines — even for messy user-uploaded real-world data.
* [jsonapi-serializer/jsonapi-serializer](https://github.com/jsonapi-serializer/jsonapi-serializer) - A fast JSON:API serializer for Ruby (fork of Netflix/fast_jsonapi)
* [westonganger/spreadsheet_architect](https://github.com/westonganger/spreadsheet_architect) - Spreadsheet Architect is a library that allows you to create XLSX, ODS, or CSV spreadsheets super easily from ActiveRecord relations, plain Ruby objects, or tabular data.
* [amatsuda/jb](https://github.com/amatsuda/jb) - A simple and fast JSON API template engine for Ruby on Rails
* [procore-oss/blueprinter](https://github.com/procore-oss/blueprinter) - Simple, Fast, and Declarative Serialization Library for Ruby
* [okuramasafumi/alba](https://github.com/okuramasafumi/alba) - Alba is a JSON serializer for Ruby, JRuby and TruffleRuby.
* [yorickpeterse/oga](https://github.com/yorickpeterse/oga) - Oga is an XML/HTML parser written in Ruby.
* [zdavatz/spreadsheet](https://github.com/zdavatz/spreadsheet) - The Ruby Spreadsheet by ywesee GmbH
* [msgpack/msgpack-ruby](https://github.com/msgpack/msgpack-ruby) - MessagePack implementation for Ruby / msgpack.org[Ruby]
* [ruby/json](https://github.com/ruby/json) - JSON implementation for Ruby
* [kgiszczak/shale](https://github.com/kgiszczak/shale) - Shale is a Ruby object mapper and serializer for JSON, YAML, TOML, CSV and XML. It allows you to parse JSON, YAML, TOML, CSV and XML data and convert it into Ruby data structures, as well as serialize data structures into JSON, YAML, TOML, CSV or XML.
* [dmendel/bindata](https://github.com/dmendel/bindata) - BinData - Reading and Writing Binary Data in Ruby
* [caxlsx/caxlsx](https://github.com/caxlsx/caxlsx) - xlsx generation with charts, images, automated column width, customizable styles and full schema validation. Axlsx excels at helping you generate beautiful Office Open XML Spreadsheet documents without having to understand the entire ECMA specification. Check out the README for some examples of how easy it is. Best of all, you can validate your xlsx file before serialization so you know for sure that anything generated is going to load on your client's machine.
* [yosiat/panko_serializer](https://github.com/yosiat/panko_serializer) - High Performance JSON Serialization for ActiveRecord & Ruby Objects
* [pcreux/csv-importer](https://github.com/pcreux/csv-importer) - CSV Import for humans on Ruby / Ruby on Rails
* [ruby/psych](https://github.com/ruby/psych) - A libyaml wrapper for Ruby
* [comma-csv/comma](https://github.com/comma-csv/comma) - Comma is a small CSV (ie. comma separated values) generation extension for Ruby objects, that lets you seamlessly define a CSV output format via a small DSL
* [ruby-protobuf/protobuf](https://github.com/ruby-protobuf/protobuf) - A pure ruby implementation of Google's Protocol Buffers
* [joshbuddy/jsonpath](https://github.com/joshbuddy/jsonpath) - Ruby implementation of http://goessner.net/articles/JsonPath/
* [fotinakis/jsonapi-serializers](https://github.com/fotinakis/jsonapi-serializers) - Pure Ruby readonly serializers for the JSON:API spec.

### Caching and Queues

* [sidekiq/sidekiq](https://github.com/sidekiq/sidekiq) - Simple, efficient background processing for Ruby
* [resque/resque](https://github.com/resque/resque) - Resque is a Redis-backed Ruby library for creating background jobs, placing them on multiple queues, and processing them later.
* [petergoldstein/dalli](https://github.com/petergoldstein/dalli) - High performance memcached client for Ruby
* [bensheldon/good_job](https://github.com/bensheldon/good_job) - Multithreaded, Postgres-based, Active Job backend for Ruby on Rails.
* [brandonhilkert/sucker_punch](https://github.com/brandonhilkert/sucker_punch) - Sucker Punch is a Ruby asynchronous processing library using concurrent-ruby, heavily influenced by Sidekiq and girl_friday.
* [que-rb/que](https://github.com/que-rb/que) - A Ruby job queue that uses PostgreSQL's advisory locks for speed and reliability.
* [karafka/karafka](https://github.com/karafka/karafka) - Ruby and Rails efficient Kafka processing framework
* [jondot/sneakers](https://github.com/jondot/sneakers) - A fast background processing framework for Ruby and RabbitMQ
* [ruby-shoryuken/shoryuken](https://github.com/ruby-shoryuken/shoryuken) - A super efficient Amazon SQS thread based message processor for Ruby.
* [zoolutions/sidekiq-unique-jobs](https://github.com/zoolutions/sidekiq-unique-jobs) - Prevents duplicate Sidekiq jobs
* [redis-store/redis-store](https://github.com/redis-store/redis-store) - Namespaced Rack::Session, Rack::Cache, I18n and cache Redis stores for Ruby web frameworks
* [ruby-amqp/bunny](https://github.com/ruby-amqp/bunny) - Bunny is a popular, easy to use, mature Ruby client for RabbitMQ
* [zendesk/ruby-kafka](https://github.com/zendesk/ruby-kafka) - A Ruby client library for Apache Kafka
* [QueueClassic/queue_classic](https://github.com/QueueClassic/queue_classic) - Simple, efficient worker queue for Ruby & PostgreSQL.
* [chaps-io/gush](https://github.com/chaps-io/gush) - Fast and distributed workflow runner using ActiveJob and Redis
* [redis-store/redis-rails](https://github.com/redis-store/redis-rails) - Redis stores for Ruby on Rails
* [rtomayko/rack-cache](https://github.com/rtomayko/rack-cache) - Real HTTP Caching for Ruby Web Apps
* [ruby-amqp/amqp](https://github.com/ruby-amqp/amqp) - EventMachine-based RabbitMQ client. Prefer Bunny: http://rubybunny.info. See documentation guides at http://ruby-amqp.github.io/amqp/. *(archived)*
* [fractaledmind/acidic_job](https://github.com/fractaledmind/acidic_job) - 🧪 Durable execution workflows for Active Job
* [bkeepers/qu](https://github.com/bkeepers/qu) - a Ruby library for queuing and processing background jobs.
* [sorentwo/readthis](https://github.com/sorentwo/readthis) - :newspaper: Pooled active support compliant caching with redis *(archived)*
* [socialpandas/sidekiq-superworker](https://github.com/socialpandas/sidekiq-superworker) - Directed acyclic graphs of Sidekiq jobs
* [arthurnn/memcached](https://github.com/arthurnn/memcached) - A Ruby interface to the libmemcached C client
* [nesquena/backburner](https://github.com/nesquena/backburner) - Simple and reliable beanstalkd job queue for ruby
* [d34ndev/sidekiq-limit_fetch](https://github.com/d34ndev/sidekiq-limit_fetch) - A Sidekiq plugin to support advanced queue control (limiting, pausing, blocking, querying)

### Search and Indexing

* [elastic/elasticsearch-rails](https://github.com/elastic/elasticsearch-rails) - Elasticsearch integrations for ActiveModel/Record and Ruby on Rails
* [elastic/elasticsearch-ruby](https://github.com/elastic/elasticsearch-ruby) - Ruby integrations for Elasticsearch
* [toptal/chewy](https://github.com/toptal/chewy) - High-level Elasticsearch Ruby framework based on the official elasticsearch-ruby client
* [karmi/retire](https://github.com/karmi/retire) - A rich Ruby API and DSL for the Elasticsearch search engine *(archived)*
* [pat/thinking-sphinx](https://github.com/pat/thinking-sphinx) - Sphinx/Manticore plugin for ActiveRecord/Rails
* [Casecommons/pg_search](https://github.com/Casecommons/pg_search) - pg_search builds ActiveRecord named scopes that take advantage of PostgreSQL’s full text search
* [textacular/textacular](https://github.com/textacular/textacular) - Textacular exposes full text search capabilities from PostgreSQL, and allows you to declare full text indexes. Textacular will extend ActiveRecord with named_scope methods making searching easy and fun!
* [mrkamel/search_cop](https://github.com/mrkamel/search_cop) - Search engine like fulltext query support for ActiveRecord
* [projectblacklight/blacklight](https://github.com/projectblacklight/blacklight) - Blacklight provides a discovery interface for any Solr (http://lucene.apache.org/solr) index.
* [huacnlee/redis-search](https://github.com/huacnlee/redis-search) - Deprecated! High performance real-time prefix search, indexes store in Redis for Rails application *(archived)*
* [nathanl/searchlight](https://github.com/nathanl/searchlight) - Searchlight helps you build searches from options via Ruby methods that you write.
* [rsolr/rsolr](https://github.com/rsolr/rsolr) - A Ruby client for Apache Solr

## Machine Learning and AI

### LLM and Inference

* [crmne/ruby_llm](https://github.com/crmne/ruby_llm) - One delightful Ruby framework for every major AI provider. Build AI agents, chatbots, RAG apps, and multimodal workflows in beautiful, expressive code.
* [alexrudall/ruby-openai](https://github.com/alexrudall/ruby-openai) - OpenAI API + Ruby! 🤖❤️ GPT-5 & Realtime WebRTC compatible!
* [patterns-ai-core/langchainrb](https://github.com/patterns-ai-core/langchainrb) - Build LLM-powered applications in Ruby
* [yjacquin/fast-mcp](https://github.com/yjacquin/fast-mcp) - A Ruby Implementation of the Model Context Protocol
* [modelcontextprotocol/ruby-sdk](https://github.com/modelcontextprotocol/ruby-sdk) - The official Ruby SDK for the Model Context Protocol servers and clients.
* [obie/claude-on-rails](https://github.com/obie/claude-on-rails) - A development framework for Ruby on Rails developers using Claude Code, inspired by SuperClaude
* [maquina-app/rails-mcp-server](https://github.com/maquina-app/rails-mcp-server) - A Ruby gem implementation of a Model Context Protocol (MCP) server for Rails projects. This server allows LLMs (Large Language Models) to interact with Rails projects through the Model Context Protocol.

### Machine Learning Frameworks

* [igrigorik/decisiontree](https://github.com/igrigorik/decisiontree) - ID3-based implementation of the ML Decision Tree algorithm
* [davidcelis/recommendable](https://github.com/davidcelis/recommendable) - :+1::-1: A recommendation engine using Likes and Dislikes for your Ruby app
* [yoshoku/rumale](https://github.com/yoshoku/rumale) - Rumale is a machine learning library in Ruby
* [ankane/torch.rb](https://github.com/ankane/torch.rb) - Deep learning for Ruby, powered by LibTorch
* [somaticio/tensorflow.rb](https://github.com/somaticio/tensorflow.rb) - tensorflow for ruby
* [SergioFierens/ai4r](https://github.com/SergioFierens/ai4r) - Artificial Intelligence for Ruby - A Ruby playground for AI researchers
* [ankane/eps](https://github.com/ankane/eps) - Machine learning for Ruby
* [ankane/disco](https://github.com/ankane/disco) - Recommendations for Ruby and Rails using collaborative filtering
* [jekyll/classifier-reborn](https://github.com/jekyll/classifier-reborn) - A general classifier module to allow Bayesian and other types of classifications. A fork of cardmagic/classifier.
* [jedld/tensor_stream](https://github.com/jedld/tensor_stream) - A ground-up and standalone reimplementation of TensorFlow for ruby. Comes with a pure ruby and OpenCL opcode evaluator

### Computer Vision

* [dannnylo/rtesseract](https://github.com/dannnylo/rtesseract) - Ruby library for working with the Tesseract OCR.
* [meh/ruby-tesseract-ocr](https://github.com/meh/ruby-tesseract-ocr) - A Ruby wrapper library to the tesseract-ocr API.

### Natural Language Processing

* [louismullie/treat](https://github.com/louismullie/treat) - Natural language processing framework for Ruby.
* [inukshuk/anystyle](https://github.com/inukshuk/anystyle) - Fast citation reference parsing
* [jpmckinney/tf-idf-similarity](https://github.com/jpmckinney/tf-idf-similarity) - Ruby gem to calculate the similarity between texts using tf*idf
* [ankane/transformers-ruby](https://github.com/ankane/transformers-ruby) - State-of-the-art transformers for Ruby
* [peterc/whatlanguage](https://github.com/peterc/whatlanguage) - Pure Ruby natural language detection library for 160+ languages.
* [ankane/informers](https://github.com/ankane/informers) - Fast transformer inference for Ruby
* [subosito/gingerice](https://github.com/subosito/gingerice) - Ruby wrapper for correcting spelling and grammar mistakes based on the context of complete sentences. *(archived)*
* [7compass/sentimental](https://github.com/7compass/sentimental) - Simple sentiment analysis with Ruby
* [alexandru/stuff-classifier](https://github.com/alexandru/stuff-classifier) - simple text classifier(s) implemetation in ruby *(archived)*
* [louismullie/stanford-core-nlp](https://github.com/louismullie/stanford-core-nlp) - Ruby bindings to the Stanford Core NLP tools (English, French, German).

### Data Science and Analytics

* [ankane/chartkick](https://github.com/ankane/chartkick) - Create beautiful JavaScript charts with one line of Ruby
* [red-data-tools/YouPlot](https://github.com/red-data-tools/YouPlot) - A command line tool that draw plots on the terminal.
* [thbar/kiba](https://github.com/thbar/kiba) - Data processing & ETL framework for Ruby
* [Multiwoven/multiwoven](https://github.com/Multiwoven/multiwoven) - 🔥🔥🔥 Open source Reverse ETL - alternative to hightouch and census.
* [assaf/vanity](https://github.com/assaf/vanity) - Experiment Driven Development for Ruby *(archived)*
* [topfunky/gruff](https://github.com/topfunky/gruff) - Gruff graphing library for Ruby
* [SciRuby/daru](https://github.com/SciRuby/daru) - Data Analysis in RUby
* [michelson/lazy_high_charts](https://github.com/michelson/lazy_high_charts) - Make highcharts a la ruby , works in rails 5.X / 4.X / 3.X, and other ruby web frameworks
* [ankane/ruby-polars](https://github.com/ankane/ruby-polars) - Blazingly fast DataFrames for Ruby
* [SciRuby/iruby](https://github.com/SciRuby/iruby) - Official gem repository: Ruby kernel for Jupyter/IPython Notebook
* [mattetti/googlecharts](https://github.com/mattetti/googlecharts) - Ruby Google Chart API *(archived)*
* [Lackoftactics/facebook_data_analyzer](https://github.com/Lackoftactics/facebook_data_analyzer) - Analyze facebook copy of your data with ruby language. Download zip file from facebook and get info about friends ranking by message, vocabulary, contacts, friends added statistics and more *(archived)*
* [BaseSecrete/active_analytics](https://github.com/BaseSecrete/active_analytics) - First-party, privacy-focused traffic analytics for Ruby on Rails applications.
* [infochimps-labs/wukong](https://github.com/infochimps-labs/wukong) - Ruby on Hadoop: Efficient, effective Hadoop streaming & bulk data processing. Write micro scripts for terabyte-scale data
* [ruport/ruport](https://github.com/ruport/ruport) - Ruby Reports : Making your reporting life suck less, through Ruby
* [clbustos/statsample](https://github.com/clbustos/statsample) - A suite for basic and advanced statistics on Ruby.

## Networking and Distributed

### Networking

* [mikel/mail](https://github.com/mikel/mail) - A Really Ruby Mail Library
* [anycable/anycable](https://github.com/anycable/anycable) - Realtime server for reliable two-way communication to power-up any backend
* [websocket-rails/websocket-rails](https://github.com/websocket-rails/websocket-rails) - Plug and play websocket support for ruby on rails.
* [truemail-rb/truemail](https://github.com/truemail-rb/truemail) - 🚀 Configurable framework agnostic plain Ruby 📨 email validator/verifier. Verify email via Regex, DNS, SMTP and even more. Be sure that email address valid and exists.
* [weppos/whois](https://github.com/weppos/whois) - An intelligent — pure Ruby — WHOIS client and parser.
* [faye/faye-websocket-ruby](https://github.com/faye/faye-websocket-ruby) - Standards-compliant WebSocket client and server
* [net-ssh/net-ssh](https://github.com/net-ssh/net-ssh) - Pure Ruby implementation of an SSH (protocol 2) client
* [mailman/mailman](https://github.com/mailman/mailman) - An incoming mail processing microframework in Ruby *(archived)*
* [igrigorik/http-2](https://github.com/igrigorik/http-2) - Pure Ruby implementation of HTTP/2 protocol
* [dcparker/ruby-gmail](https://github.com/dcparker/ruby-gmail) - A Rubyesque interface to Gmail. Connect to Gmail via IMAP and manipulate emails and labels. Send email with your Gmail account via SMTP. Includes full support for parsing and generating MIME messages.
* [socketry/rubydns](https://github.com/socketry/rubydns) - A DSL for building fun, high-performance DNS servers.
* [cjheath/geoip](https://github.com/cjheath/geoip) - The Ruby gem for querying Maxmind.com's GeoIP database, which returns the geographic location of a server given its IP address
* [weppos/publicsuffix-ruby](https://github.com/weppos/publicsuffix-ruby) - Domain name parser for Ruby based on the Public Suffix List.
* [adhearsion/adhearsion](https://github.com/adhearsion/adhearsion) - A Ruby framework for building telephony applications
* [adhearsion/blather](https://github.com/adhearsion/blather) - XMPP/Jabber Library and DSL for Ruby written on EventMachine and Nokogiri.
* [tent/tentd](https://github.com/tent/tentd) - Reference implementation of a Tent server in Ruby *(archived)*
* [negativecode/vines](https://github.com/negativecode/vines) - An XMPP chat server for Ruby.
* [imanel/websocket-ruby](https://github.com/imanel/websocket-ruby) - Universal Ruby library to handle WebSocket protocol
* [WinRb/WinRM](https://github.com/WinRb/WinRM) - Ruby library for Windows Remote Management

### RPC and Messaging

* [krisleech/wisper](https://github.com/krisleech/wisper) - A micro library providing Ruby objects with Publish-Subscribe capabilities
* [discourse/message_bus](https://github.com/discourse/message_bus) - A reliable and robust messaging bus for Ruby and Rack
* [nats-io/nats.rb](https://github.com/nats-io/nats.rb) - Ruby client for NATS, the cloud native messaging system.
* [firehoseio/firehose](https://github.com/firehoseio/firehose) - Build realtime Ruby web applications. Created by the fine folks at Poll Everywhere.
* [pusher/pusher-http-ruby](https://github.com/pusher/pusher-http-ruby) - Ruby library for Pusher Channels HTTP API
* [bigcommerce/gruf](https://github.com/bigcommerce/gruf) - gRPC Ruby Framework
* [njh/ruby-mqtt](https://github.com/njh/ruby-mqtt) - Pure Ruby gem that implements the MQTT protocol, a lightweight protocol for publish/subscribe messaging.
* [anycable/anycable-rails](https://github.com/anycable/anycable-rails) - AnyCable for Ruby on Rails applications

### Distributed Systems

* [Shopify/semian](https://github.com/Shopify/semian) - :monkey: Resiliency toolkit for Ruby for failing fast
* [lian/bitcoin-ruby](https://github.com/lian/bitcoin-ruby) - bitcoin utils and protocol in ruby.
* [yammer/circuitbox](https://github.com/yammer/circuitbox) - Circuit breaker built with large Ruby apps in mind.
* [ezmobius/nanite](https://github.com/ezmobius/nanite) - self assembling fabric of ruby daemons
* [leandromoreira/redlock-rb](https://github.com/leandromoreira/redlock-rb) - Redlock is a redis-based distributed lock implementation in Ruby. More than 40 Millions of downloads.
* [EthWorks/ethereum.rb](https://github.com/EthWorks/ethereum.rb) - Ethereum library for the Ruby language
* [celluloid/dcell](https://github.com/celluloid/dcell) - UNMAINTAINED: See celluloid/celluloid#779 - Actor-based distributed objects in Ruby based on Celluloid and 0MQ *(archived)*
* [zilverline/sequent](https://github.com/zilverline/sequent) - CQRS & event sourcing framework for Ruby
* [ryanlecompte/redis_failover](https://github.com/ryanlecompte/redis_failover) - redis_failover is a ZooKeeper-based automatic master/slave failover solution for Ruby.

### Cloud and Infrastructure

* [fastlane/fastlane](https://github.com/fastlane/fastlane) - 🚀 The easiest way to automate building and releasing your iOS and Android apps
* [hashicorp/vagrant](https://github.com/hashicorp/vagrant) - Vagrant is a tool for building and distributing development environments.
* [capistrano/capistrano](https://github.com/capistrano/capistrano) - A deployment automation tool built on Ruby, Rake, and SSH.
* [ubicloud/ubicloud](https://github.com/ubicloud/ubicloud) - Open source alternative to AWS. Elastic compute, block storage (non replicated), firewall and load balancer, managed Postgres, K8s, AI inference, and IAM services.
* [danger/danger](https://github.com/danger/danger) - 🚫 Stop saying "you forgot to …" in code review (in Ruby)
* [mina-deploy/mina](https://github.com/mina-deploy/mina) - Blazing fast deployer and server automation tool
* [fog/fog](https://github.com/fog/fog) - The Ruby cloud services library.
* [aws/aws-sdk-ruby](https://github.com/aws/aws-sdk-ruby) - The official AWS SDK for Ruby
* [SUSE/Portus](https://github.com/SUSE/Portus) - Authorization service and frontend for Docker registry (v2) *(archived)*
* [theforeman/foreman](https://github.com/theforeman/foreman) - an application that automates the lifecycle of servers
* [github/janky](https://github.com/github/janky) - Continuous integration server built on top of Jenkins and Hubot *(archived)*
* [vagrant-libvirt/vagrant-libvirt](https://github.com/vagrant-libvirt/vagrant-libvirt) - Vagrant provider for libvirt.
* [welaika/wordmove](https://github.com/welaika/wordmove) - Multi-stage command line deploy/mirroring and task runner for Wordpress
* [coinbase/terraform-landscape](https://github.com/coinbase/terraform-landscape) - Improve Terraform's plan output to be easier to read and understand
* [travis-ci/travis.rb](https://github.com/travis-ci/travis.rb) - Travis CI Client (CLI and Ruby library)
* [kontena/kontena](https://github.com/kontena/kontena) - The developer friendly container and micro services platform. Works on any cloud, easy to setup, simple to use.
* [petems/tugboat](https://github.com/petems/tugboat) - A command line tool for interacting with your DigitalOcean droplets.
* [googleapis/google-cloud-ruby](https://github.com/googleapis/google-cloud-ruby) - Google Cloud Client Library for Ruby
* [ManageIQ/manageiq](https://github.com/ManageIQ/manageiq) - ManageIQ Open-Source Management Platform
* [tryzealot/zealot](https://github.com/tryzealot/zealot) - Self-hosted Beta App Distribution for Android, iOS, macOS, Linux and Windows apps | 开源自部署移动应用、 macOS、Linux 和 Windows 应用分发平台，提供 iOS、Android SDK、fastlane 等丰富组件库
* [bibendi/dip](https://github.com/bibendi/dip) - The dip is a CLI dev–tool that provides native-like interaction with a Dockerized application.
* [capistrano/sshkit](https://github.com/capistrano/sshkit) - A toolkit for deploying code and assets to servers in a repeatable, testable, reliable way.
* [itamae-kitchen/itamae](https://github.com/itamae-kitchen/itamae) - Configuration management tool inspired by Chef, but simpler and lightweight. Formerly known as Lightchef.
* [upserve/docker-api](https://github.com/upserve/docker-api) - A lightweight Ruby client for the Docker Remote API
* [capistrano/rails](https://github.com/capistrano/rails) - Official Ruby on Rails specific tasks for Capistrano
* [thoughtbot/parity](https://github.com/thoughtbot/parity) - Shell commands for development, staging, and production parity for Heroku apps
* [heroku/heroku-buildpack-ruby](https://github.com/heroku/heroku-buildpack-ruby) - Heroku's classic buildpack for Ruby apps
* [marcel/aws-s3](https://github.com/marcel/aws-s3) - AWS-S3 is a Ruby implementation of Amazon's S3 REST API
* [oscardelben/firebase-ruby](https://github.com/oscardelben/firebase-ruby) - Ruby wrapper for Firebase
* [vagrant-landrush/landrush](https://github.com/vagrant-landrush/landrush) - A Vagrant plugin that provides a simple DNS server for Vagrant guests *(archived)*
* [travis-ci/travis-build](https://github.com/travis-ci/travis-build) - .travis.yml => build.sh converter
* [seuros/capistrano-puma](https://github.com/seuros/capistrano-puma) - Puma integration for Capistrano
* [aws/aws-sdk-rails](https://github.com/aws/aws-sdk-rails) - Official repository for the aws-sdk-rails gem, which integrates the AWS SDK for Ruby with Ruby on Rails.
* [thoughtworks/cruisecontrol.rb](https://github.com/thoughtworks/cruisecontrol.rb) - CruiseControl for Ruby. Keep it simple. *(archived)*
* [tombh/peas](https://github.com/tombh/peas) - Docker and Ruby based PaaS *(archived)*
* [seuros/capistrano-sidekiq](https://github.com/seuros/capistrano-sidekiq) - Sidekiq integration for Capistrano
* [drewblas/aws-ses](https://github.com/drewblas/aws-ses) - Provides an easy ruby DSL & interface to AWS SES
* [decision-labs/fcm](https://github.com/decision-labs/fcm) - Ruby bindings to Firebase Cloud Messaging (FCM) for Android, iOS or Web
* [digitalocean/droplet_kit](https://github.com/digitalocean/droplet_kit) - DropletKit is the official DigitalOcean API client for Ruby.
* [flexera-public/right_aws](https://github.com/flexera-public/right_aws) - RightScale Amazon Web Services Ruby Gems
* [grempe/amazon-ec2](https://github.com/grempe/amazon-ec2) - WARNING : You probably don't want this code. Its archived and ancient and probably doesn't work. Try the official AWS Ruby SDK instead. *(archived)*
* [arangamani/jenkins_api_client](https://github.com/arangamani/jenkins_api_client) - Ruby Client libraries for communicating with Jenkins Remote Access API
* [intercity/chef-repo](https://github.com/intercity/chef-repo) - Set up your server to host Ruby on Rails apps. - Follow us on Twitter: @intercityup *(archived)*
* [coinbase/geoengineer](https://github.com/coinbase/geoengineer) - DEPRECATED — Infrastructure As Code *(archived)*
* [voxpupuli/puppet-elasticsearch](https://github.com/voxpupuli/puppet-elasticsearch) - Elasticsearch Puppet module
* [the-teacher/rails-start](https://github.com/the-teacher/rails-start) - Launch Rails with 1 shell command!

### Monitoring and Observability

* [errbit/errbit](https://github.com/errbit/errbit) - The open source error catcher that's Airbrake API compliant :ukraine:
* [jamesrwhite/minicron](https://github.com/jamesrwhite/minicron) - 🕰️ Monitor your cron jobs *(archived)*
* [mojombo/god](https://github.com/mojombo/god) - Ruby process monitor
* [charlotte-ruby/impressionist](https://github.com/charlotte-ruby/impressionist) - Rails Plugin that tracks impressions and page views
* [igorkasyanchuk/rails_performance](https://github.com/igorkasyanchuk/rails_performance) - Monitor performance of you Rails applications (self-hosted and free)
* [newrelic/newrelic-ruby-agent](https://github.com/newrelic/newrelic-ruby-agent) - New Relic RPM Ruby Agent
* [getsentry/sentry-ruby](https://github.com/getsentry/sentry-ruby) - Sentry SDK for Ruby
* [airbrake/airbrake](https://github.com/airbrake/airbrake) - The official Airbrake library for Ruby applications
* [yabeda-rb/yabeda](https://github.com/yabeda-rb/yabeda) - Extendable framework for collecting and exporting metrics from your Ruby application
* [marckohlbrugge/sessy](https://github.com/marckohlbrugge/sessy) - Open-source email observability for AWS SES
* [basecamp/upright](https://github.com/basecamp/upright) - Synthetic monitoring engine with Playwright and Prometheus metrics
* [davydovanton/sidekiq-statistic](https://github.com/davydovanton/sidekiq-statistic) - See statistic about your workers
* [Fudge/gltail](https://github.com/Fudge/gltail) - Real-time visualization of server traffic, events and statistics with Ruby, SSH and OpenGL
* [noahhl/batsd](https://github.com/noahhl/batsd) - A ruby statsd server implementation storing to Redis and disk
* [open-telemetry/opentelemetry-ruby](https://github.com/open-telemetry/opentelemetry-ruby) - OpenTelemetry Ruby API & SDK, and related gems
* [Shopify/statsd-instrument](https://github.com/Shopify/statsd-instrument) - A StatsD client for Ruby apps. Provides metaprogramming methods to inject StatsD instrumentation into your code.
* [prometheus/client_ruby](https://github.com/prometheus/client_ruby) - Prometheus instrumentation library for Ruby applications
* [scoutapp/ruby_server_timing](https://github.com/scoutapp/ruby_server_timing) - Bring Rails server-side performance metrics 📈 to Chrome's Developer Tools via the Server Timing API. Production Safe™.
* [eric/metriks](https://github.com/eric/metriks) - An experimental library to instrument ruby
* [reinh/statsd](https://github.com/reinh/statsd) - A Ruby Statsd client that isn't a direct port of the Python example code. Because Ruby isn't Python.

## User Interface

### GUI Toolkits

* [shoes/shoes4](https://github.com/shoes/shoes4) - Shoes 4 : the next version of Shoes
* [AndyObtiva/glimmer](https://github.com/AndyObtiva/glimmer) - DSL Framework consisting of a DSL Engine and a Data-Binding Library used in Glimmer DSL for SWT (JRuby Desktop Development GUI Framework), Glimmer DSL for Opal (Pure Ruby Web GUI), Glimmer DSL for LibUI (Prerequisite-Free Ruby Desktop Development GUI Library), Glimmer DSL for Tk (Ruby Tk Desktop Development GUI Library), Glimmer DSL for GTK (Ruby-GNOME Desktop Development GUI Library), Glimmer DSL for XML (& HTML), and Glimmer DSL for CSS
* [maccman/bowline](https://github.com/maccman/bowline) - Ruby/JS GUI and Binding framework (deprecated)
* [AndyObtiva/glimmer-dsl-libui](https://github.com/AndyObtiva/glimmer-dsl-libui) - Glimmer DSL for LibUI - Prerequisite-Free Ruby Desktop Development Cross-Platform Native GUI Library - The Quickest Way From Zero To GUI - If You Liked Shoes, You'll Love Glimmer! - No need to pre-install any prerequisites. Just install the gem and have platform-independent GUI that just works on Mac, Windows, and Linux.

### Terminal and Console UI

* [jfelchner/ruby-progressbar](https://github.com/jfelchner/ruby-progressbar) - Ruby/ProgressBar is a text progress bar library for Ruby.
* [tj/terminal-table](https://github.com/tj/terminal-table) - Ruby ASCII Table Generator, simple and feature rich.
* [fazibear/colorize](https://github.com/fazibear/colorize) - Ruby string class extension. It add some methods to set color, background color and text effect on console easier using ANSI escape sequences.
* [janlelis/irbtools](https://github.com/janlelis/irbtools) - Improvements for Ruby's IRB console 💎︎
* [ku1ik/rainbow](https://github.com/ku1ik/rainbow) - Ruby gem for colorizing printed text on ANSI terminals
* [piotrmurach/pastel](https://github.com/piotrmurach/pastel) - Terminal output styling with intuitive and clean API.
* [paul/progress_bar](https://github.com/paul/progress_bar) - A Ruby terminal progress_bar
* [gavinlaking/vedeu](https://github.com/gavinlaking/vedeu) - A framework written in Ruby for building GUI/TUI terminal/console applications. *(archived)*
* [wbailey/command_line_reporter](https://github.com/wbailey/command_line_reporter) - A gem for making it easy to produce a report while a ruby script is executing

### Mobile

* [nomad-cli/houston](https://github.com/nomad-cli/houston) - Apple Push Notifications; No Dirigible Required *(archived)*
* [rpush/rpush](https://github.com/rpush/rpush) - The push notification service for Ruby.
* [jamonholmgren/ProMotion](https://github.com/jamonholmgren/ProMotion) - ProMotion is a RubyMotion gem that makes iPhone development less like Objective-C and more like Ruby. *(archived)*
* [rubymotion-community/BubbleWrap](https://github.com/rubymotion-community/BubbleWrap) - Cocoa wrappers and helpers for RubyMotion (Ruby for iOS and OS X) - Making Cocoa APIs more Ruby like, one API at a time. Fork away and send your pull requests
* [grocer/grocer](https://github.com/grocer/grocer) - Pushing your Apple notifications since 2012. *(archived)*

### Applications and End User Tools

* [maybe-finance/maybe](https://github.com/maybe-finance/maybe) - The personal finance app for everyone *(archived)*
* [jekyll/jekyll](https://github.com/jekyll/jekyll) - :globe_with_meridians: Jekyll is a blog-aware static site generator in Ruby
* [discourse/discourse](https://github.com/discourse/discourse) - A platform for community discussion. Free, open, simple.
* [chatwoot/chatwoot](https://github.com/chatwoot/chatwoot) - Open-source live-chat, email support, omni-channel desk. An alternative to Intercom, Zendesk, Salesforce Service Cloud etc. 🔥💬
* [gitlabhq/gitlabhq](https://github.com/gitlabhq/gitlabhq) - GitLab CE Mirror | Please open new issues in our issue tracker on GitLab.com
* [forem/forem](https://github.com/forem/forem) - For empowering community 🌱
* [postalserver/postal](https://github.com/postalserver/postal) - 📮 A fully featured open source mail delivery platform for incoming & outgoing e-mail
* [opf/openproject](https://github.com/opf/openproject) - OpenProject is the leading open source project management software for product, project and portfolio management. A powerful Jira alternative with agile planning, issue tracking, roadmaps, Gantt charts, time tracking, collaboration features, and more. Available on premises or in the cloud. ⭐ Star us on GitHub
* [spree/spree](https://github.com/spree/spree) - Open Source eCommerce Platform for B2B, Marketplace, and Enterprise. REST API, TypeScript SDK, and production-ready Next.js storefront. Self-host it. Own your stack. No vendor lock-in. Zero platform fees.
* [gollum/gollum](https://github.com/gollum/gollum) - A simple, Git-powered wiki with a local frontend and support for many kinds of markup and content.
* [diaspora/diaspora](https://github.com/diaspora/diaspora) - A privacy-aware, distributed, open source social network.
* [basecamp/fizzy](https://github.com/basecamp/fizzy) - Kanban as it should be. Not as it has been.
* [sj26/mailcatcher](https://github.com/sj26/mailcatcher) - Catches mail and serves it through a dream.
* [zammad/zammad](https://github.com/zammad/zammad) - Zammad is a web based open source helpdesk/customer support system.
* [solidusio/solidus](https://github.com/solidusio/solidus) - 🛒 Solidus, the open-source eCommerce framework for industry trailblazers.
* [lobsters/lobsters](https://github.com/lobsters/lobsters) - Computing-focused community centered around link aggregation and discussion
* [octobox/octobox](https://github.com/octobox/octobox) - 📮 Untangle your GitHub Notifications
* [blackcandy-org/blackcandy](https://github.com/blackcandy-org/blackcandy) - A self hosted music streaming server
* [stringer-rss/stringer](https://github.com/stringer-rss/stringer) - A self-hosted, anti-social RSS reader.
* [refinery/refinerycms](https://github.com/refinery/refinerycms) - An extendable Ruby on Rails CMS that supports Rails 6.1 to 8.1+ and Ruby 3.x to 4.x
* [ruby-china/homeland](https://github.com/ruby-china/homeland) - :circus_tent: An open source forum/community system based on Rails, developed based on Ruby China.
* [fatfreecrm/fat_free_crm](https://github.com/fatfreecrm/fat_free_crm) - Ruby on Rails CRM platform
* [pglombardo/PasswordPusher](https://github.com/pglombardo/PasswordPusher) - 🔐 Securely share sensitive information with automatic expiration & deletion after a set number of views or duration. Track who, what and when with full audit logs.
* [openstreetmap/openstreetmap-website](https://github.com/openstreetmap/openstreetmap-website) - The Rails application that powers OpenStreetMap
* [danbooru/danbooru](https://github.com/danbooru/danbooru) - A taggable image board written in Rails.
* [comfy/comfortable-mexican-sofa](https://github.com/comfy/comfortable-mexican-sofa) - ComfortableMexicanSofa is a powerful Ruby on Rails 5.2+ CMS (Content Management System) Engine
* [edavis10/redmine](https://github.com/edavis10/redmine) - Redmine is a flexible project management web application written using Ruby on Rails framework. http://github.com/edavis10/redmine is the official git mirror of the svn repository
* [nanoc/nanoc](https://github.com/nanoc/nanoc) - A powerful web publishing system
* [publify/publify](https://github.com/publify/publify) - A self hosted Web publishing platform on Rails.
* [decidim/decidim](https://github.com/decidim/decidim) - The participatory democracy framework. A generator and multiple gems made with Ruby on Rails
* [24pullrequests/24pullrequests](https://github.com/24pullrequests/24pullrequests) - :christmas_tree: Giving back to open source for the holidays
* [joeyates/imap-backup](https://github.com/joeyates/imap-backup) - Backup and Migrate IMAP Email Accounts
* [catarse/catarse](https://github.com/catarse/catarse) - The first open source crowdfunding platform for creative projects in the world *(archived)*
* [ifmeorg/ifme](https://github.com/ifmeorg/ifme) - Free, open source mental health communication web app to share experiences with loved ones
* [thredded/thredded](https://github.com/thredded/thredded) - The best Rails forums engine ever.
* [insoshi/insoshi](https://github.com/insoshi/insoshi) - An open source social networking platform in Ruby on Rails
* [consuldemocracy/consuldemocracy](https://github.com/consuldemocracy/consuldemocracy) - Consul Democracy - Open Government and E-Participation Web Software
* [codetriage/CodeTriage](https://github.com/codetriage/CodeTriage) - Discover the best way to get started contributing to Open Source projects
* [seven1m/onebody](https://github.com/seven1m/onebody) - private member portal for churches, built with Ruby on Rails *(archived)*
* [github-education-resources/classroom](https://github.com/github-education-resources/classroom) - GitHub Classroom automates repository creation and access control, making it easy for teachers to distribute starter code and collect assignments on GitHub. *(archived)*
* [ivaldi/brimir](https://github.com/ivaldi/brimir) - Email helpdesk built using Ruby on Rails and Zurb Foundation *(archived)*
* [antirez/lamernews](https://github.com/antirez/lamernews) - Lamer News -- an HN style social news site written in Ruby/Sinatra/Redis/JQuery
* [openfoodfoundation/openfoodnetwork](https://github.com/openfoodfoundation/openfoodnetwork) - Connect suppliers, distributors and consumers to trade local produce.
* [owen2345/camaleon-cms](https://github.com/owen2345/camaleon-cms) - Camaleon CMS is a dynamic and advanced content management system based on Ruby on Rails
* [TracksApp/tracks](https://github.com/TracksApp/tracks) - Tracks is a GTD™ web application, built with Ruby on Rails
* [drhenner/ror_ecommerce](https://github.com/drhenner/ror_ecommerce) - Ruby on Rails Ecommerce platform, perfect for your small business solution.
* [DefactoSoftware/Hours](https://github.com/DefactoSoftware/Hours) - Time registration that doesn't suck
* [publiclab/plots2](https://github.com/publiclab/plots2) - a collaborative knowledge-exchange platform in Rails; we welcome first-time contributors! :balloon:
* [TarteelAI/quranic-universal-library](https://github.com/TarteelAI/quranic-universal-library) - A comprehensive collection of Quran resources
* [danlucraft/redcar](https://github.com/danlucraft/redcar) - A cross-platform programmer's editor written in Ruby.
* [sup-heliotrope/sup](https://github.com/sup-heliotrope/sup) - A curses threads-with-tags style email client (mailing list: supmua@googlegroups.com)
* [openSUSE/osem](https://github.com/openSUSE/osem) - Open Source Event Manager. An event management tool tailored to Free and Open Source Software conferences.
* [AlchemyCMS/alchemy_cms](https://github.com/AlchemyCMS/alchemy_cms) - Alchemy is the Open Source Rails CMS framework for the component based web that can be used as classic server side rendered or headless CMS.
* [JacobEvelyn/friends](https://github.com/JacobEvelyn/friends) - Spend time with the people you care about. Introvert-tested. Extrovert-approved.
* [wearefine/fae](https://github.com/wearefine/fae) - CMS for Rails. For Reals.
* [hibiken/stories](https://github.com/hibiken/stories) - Medium clone built with Ruby on Rails *(archived)*
* [xaviershay/enki](https://github.com/xaviershay/enki) - A Ruby on Rails blogging app for the fashionable developer. It's better than Mephisto or SimpleLog
* [joemasilotti/railsdevs.com](https://github.com/joemasilotti/railsdevs.com) - The reverse job board for Ruby on Rails developers. *(archived)*
* [annict/annict](https://github.com/annict/annict) - A platform for anime addicts.
* [klausmeyer/docker-registry-browser](https://github.com/klausmeyer/docker-registry-browser) - 🐳 Web Interface for the Docker Registry HTTP API V2 written in Ruby on Rails.
* [usetrmnl/terminus](https://github.com/usetrmnl/terminus) - The flagship TRMNL BYOS application.
* [daqing/rabel](https://github.com/daqing/rabel) - An open-source web forum built on the Ruby on Rails framework.
* [etewiah/property_web_builder](https://github.com/etewiah/property_web_builder) - Create a fully featured real estate website on Rails in minutes! ⛺
* [davidesantangelo/dato.rss](https://github.com/davidesantangelo/dato.rss) - The best RSS Search experience you can find
* [whiteleaf7/narou](https://github.com/whiteleaf7/narou) - Narou.rb - 小説家になろうのダウンローダ＆縦書き整形＆管理アプリ。Kindle（などの電子書籍端末）でなろうを読む場合に超便利です！
* [moebooru/moebooru](https://github.com/moebooru/moebooru) - Moebooru, a fork of danbooru1 that has been heavily modified
* [chiliproject/chiliproject](https://github.com/chiliproject/chiliproject) - ChiliProject is a web based project management system built on Ruby on Rails *(archived)*
* [rubyevents/rubyevents](https://github.com/rubyevents/rubyevents) - On a mission to index all Ruby events.
* [stevenbristol/lovd-by-less](https://github.com/stevenbristol/lovd-by-less) - Open Source Social Network written in Ruby on Rail by Less Everything
* [Hacktoberfest/hacktoberfest-2020](https://github.com/Hacktoberfest/hacktoberfest-2020) - Hacktoberfest - App to manage the annual open-source challenge, used for the 2019 & 2020 seasons. *(archived)*
* [hacketyhack/hacketyhack](https://github.com/hacketyhack/hacketyhack) - the coder’s starter kit: sound, animation, video, messaging in a low-key ruby environment.
* [meme-search/meme-search](https://github.com/meme-search/meme-search) - The open source Meme Search Engine and Finder. Free and built to self-host locally with Python, Ruby, and Docker.

## Graphics and Media

### Graphics and Rendering

* [jashkenas/ruby-processing](https://github.com/jashkenas/ruby-processing) - Code as Art, Art as Code. Processing and Ruby are meant for each other.
* [jasonlong/geo_pattern](https://github.com/jasonlong/geo_pattern) - Create beautiful generative geometric background images from a string.
* [ruby2d/ruby2d](https://github.com/ruby2d/ruby2d) - 🎨 The Ruby 2D gem
* [glejeune/Ruby-Graphviz](https://github.com/glejeune/Ruby-Graphviz) - [MIRROR] Ruby interface to the GraphViz graphing tool
* [danini-the-panini/mittsu](https://github.com/danini-the-panini/mittsu) - 3D Graphics Library for Ruby.

### Game Development

* [andymeneely/squib](https://github.com/andymeneely/squib) - A Ruby DSL for prototyping card games.
* [mame/optcarrot](https://github.com/mame/optcarrot) - A NES emulator written in Ruby
* [kaievns/ruby-fighter](https://github.com/kaievns/ruby-fighter) - Street Fighter II in Ruby!

### Audio

* [pedrozath/coltrane](https://github.com/pedrozath/coltrane) - 🎹🎸A music theory library with a command-line interface

### Image and Video

* [layervault/psd.rb](https://github.com/layervault/psd.rb) - Parse Photoshop files in Ruby with ease
* [markevans/dragonfly](https://github.com/markevans/dragonfly) - A Ruby gem for on-the-fly processing - suitable for image uploading in Rails, Sinatra and much more!
* [streamio/streamio-ffmpeg](https://github.com/streamio/streamio-ffmpeg) - Simple yet powerful ruby ffmpeg wrapper for reading metadata and transcoding movies
* [toy/image_optim](https://github.com/toy/image_optim) - Optimize images using multiple utilities
* [wvanbergen/chunky_png](https://github.com/wvanbergen/chunky_png) - Read/write access to PNG images in pure Ruby.
* [elcuervo/airplay](https://github.com/elcuervo/airplay) - Airplay bindings to Ruby
* [janko/image_processing](https://github.com/janko/image_processing) - Web-friendly image processing macros for libvips and ImageMagick
* [libvips/ruby-vips](https://github.com/libvips/ruby-vips) - Ruby extension for the libvips image processing library.
* [toretore/barby](https://github.com/toretore/barby) - The Ruby barcode generator
* [westonplatter/phashion](https://github.com/westonplatter/phashion) - Ruby wrapper around pHash, the perceptual hash library for detecting duplicate multimedia files
* [rbuchberger/jekyll_picture_tag](https://github.com/rbuchberger/jekyll_picture_tag) - Easy responsive images for Jekyll.
* [jonbuda/miro](https://github.com/jonbuda/miro) - A Ruby gem to help extract the dominant colors from an image.
* [grosser/smusher](https://github.com/grosser/smusher) - Ruby/CLI: Automatic lossless reduction of all your images
* [remvee/exifr](https://github.com/remvee/exifr) - Moved to codeberg *(archived)*
* [ucnv/pnglitch](https://github.com/ucnv/pnglitch) - A Ruby library to glitch PNG images.
* [cloudinary/cloudinary_gem](https://github.com/cloudinary/cloudinary_gem) - Upload, transform, optimize, and manage images and videos with Cloudinary from Ruby and Rails

## Security

### Cryptography

* [ankane/lockbox](https://github.com/ankane/lockbox) - Modern encryption for Ruby and Rails
* [RubyCrypto/rbnacl](https://github.com/RubyCrypto/rbnacl) - Ruby FFI binding to the Networking and Cryptography (NaCl) library (a.k.a. libsodium)
* [jcs/rubywarden](https://github.com/jcs/rubywarden) - An unofficial, mostly Bitwarden-compatible API server written in Ruby (Sinatra and ActiveRecord) *(archived)*
* [tobmatth/rack-ssl-enforcer](https://github.com/tobmatth/rack-ssl-enforcer) - A simple Rack middleware to enforce ssl connections
* [substrakt/letsencrypt-heroku](https://github.com/substrakt/letsencrypt-heroku) - Make any Heroku application secure in just a couple of minutes. *(archived)*
* [unixcharles/acme-client](https://github.com/unixcharles/acme-client) - A Ruby client for the letsencrypt's ACME protocol.
* [reidmorrison/symmetric-encryption](https://github.com/reidmorrison/symmetric-encryption) - Encrypt data at rest in Ruby and Rails, with keys held outside your source code.
* [kbsecret/kbsecret](https://github.com/kbsecret/kbsecret) - A secret manager backed by Keybase and KBFS. *(archived)*

### Security Tools

* [presidentbeef/brakeman](https://github.com/presidentbeef/brakeman) - A static analysis security vulnerability scanner for Ruby on Rails applications
* [urbanadventurer/WhatWeb](https://github.com/urbanadventurer/WhatWeb) - Next generation web scanner
* [rack/rack-attack](https://github.com/rack/rack-attack) - Rack middleware for blocking & throttling
* [Hackplayers/evil-winrm](https://github.com/Hackplayers/evil-winrm) - The ultimate WinRM shell for hacking/pentesting
* [Arachni/arachni](https://github.com/Arachni/arachni) - Web Application Security Scanner Framework *(archived)*
* [github/secure_headers](https://github.com/github/secure_headers) - Manages application of security headers with many safe defaults
* [rubysec/bundler-audit](https://github.com/rubysec/bundler-audit) - Patch-level verification for Bundler
* [ambethia/recaptcha](https://github.com/ambethia/recaptcha) - ReCaptcha helpers for ruby apps
* [hahwul/XSpear](https://github.com/hahwul/XSpear) - 🔱 Powerfull XSS Scanning and Parameter analysis tool&gem *(archived)*
* [rubysec/ruby-advisory-db](https://github.com/rubysec/ruby-advisory-db) - A database of vulnerable Ruby Gems
* [rastating/wordpress-exploit-framework](https://github.com/rastating/wordpress-exploit-framework) - A Ruby framework designed to aid in the penetration testing of WordPress systems. *(archived)*
* [rapid7/recog](https://github.com/rapid7/recog) - Pattern recognition for hosts, services, and content
* [ronin-rb/ronin](https://github.com/ronin-rb/ronin) - Ronin is a Free and Open Source Ruby Toolkit for Security Research and Development. Ronin also allows for the rapid development and distribution of code, exploits, payloads, etc, via 3rd-party git repositories.
* [thesp0nge/dawnscanner](https://github.com/thesp0nge/dawnscanner) - Dawn is a static analysis security scanner for ruby written web applications. It supports Sinatra, Padrino and Ruby on Rails frameworks.
* [anaynayak/aws-security-viz](https://github.com/anaynayak/aws-security-viz) - Visualize your aws security groups.
* [juuso/BozoCrack](https://github.com/juuso/BozoCrack) - A silly & effective MD5 cracker in Ruby
* [urbanadventurer/urlcrazy](https://github.com/urbanadventurer/urlcrazy) - Generate and test domain typos and variations to detect and perform typo squatting, URL hijacking, phishing, and corporate espionage.
* [Fuzzapi/fuzzapi](https://github.com/Fuzzapi/fuzzapi) - Fuzzapi is a tool used for REST API pentesting and uses API_Fuzzer gem *(archived)*
* [Sliim/pentest-env](https://github.com/Sliim/pentest-env) - Pentest environment deployer (kali linux + targets) using vagrant and chef.
* [m0nad/HellRaiser](https://github.com/m0nad/HellRaiser) - Vulnerability scanner using Nmap for scanning and correlating found CPEs with CVEs.
* [0xsauby/yasuo](https://github.com/0xsauby/yasuo) - A ruby script that scans for vulnerable & exploitable 3rd-party web applications on a network
* [HatBashBR/HatCloud](https://github.com/HatBashBR/HatCloud) - discontinued
* [stephenfewer/grinder](https://github.com/stephenfewer/grinder) - Grinder is a system to automate the fuzzing of web browsers and the management of a large number of crashes.

### Authentication and Authorization

* [heartcombo/devise](https://github.com/heartcombo/devise) - Flexible authentication solution for Rails with Warden.
* [varvet/pundit](https://github.com/varvet/pundit) - Minimal authorization through OO design and pure Ruby classes
* [omniauth/omniauth](https://github.com/omniauth/omniauth) - OmniAuth is a flexible authentication system utilizing Rack middleware.
* [ryanb/cancan](https://github.com/ryanb/cancan) - Authorization Gem for Ruby on Rails. *(archived)*
* [CanCanCommunity/cancancan](https://github.com/CanCanCommunity/cancancan) - The authorization Gem for Ruby on Rails.
* [doorkeeper-gem/doorkeeper](https://github.com/doorkeeper-gem/doorkeeper) - Doorkeeper is an OAuth 2 provider for Ruby on Rails / Grape.
* [binarylogic/authlogic](https://github.com/binarylogic/authlogic) - A simple ruby authentication solution.
* [thoughtbot/clearance](https://github.com/thoughtbot/clearance) - Rails authentication with email & password.
* [jwt/ruby-jwt](https://github.com/jwt/ruby-jwt) - A ruby implementation of the RFC 7519 OAuth JSON Web Token (JWT) standard.
* [scambra/devise_invitable](https://github.com/scambra/devise_invitable) - An invitation strategy for devise
* [NoamB/sorcery](https://github.com/NoamB/sorcery) - Magical authentication for Rails 3 & 4
* [ruby-oauth/oauth2](https://github.com/ruby-oauth/oauth2) - 🔐 oauth2 - A Ruby wrapper for the OAuth 2.0, & 2.1 Authorization Frameworks, including OpenID Connect (OIDC)
* [jeremyevans/rodauth](https://github.com/jeremyevans/rodauth) - Ruby's Most Advanced Authentication Framework
* [lazaronixon/authentication-zero](https://github.com/lazaronixon/authentication-zero) - An authentication system generator for Rails applications.
* [mdp/rotp](https://github.com/mdp/rotp) - Ruby One Time Password library
* [palkan/action_policy](https://github.com/palkan/action_policy) - Authorization framework for Ruby/Rails applications
* [zquestz/omniauth-google-oauth2](https://github.com/zquestz/omniauth-google-oauth2) - Oauth2 strategy for Google
* [gonzalo-bulnes/simple_token_authentication](https://github.com/gonzalo-bulnes/simple_token_authentication) - Simple (and safe*) token authentication for Rails apps or API with Devise.
* [Sorcery/sorcery](https://github.com/Sorcery/sorcery) - Magical Authentication
* [mikker/passwordless](https://github.com/mikker/passwordless) - 🗝 Authentication for your Rails app without the icky-ness of passwords
* [nathanl/authority](https://github.com/nathanl/authority) - *CURRENTLY UNMAINTAINED*. Authority helps you authorize actions in your Rails app. It's ORM-neutral and has very little fancy syntax; just group your models under one or more Authorizer classes and write plain Ruby methods on them. *(archived)*
* [SAML-Toolkits/ruby-saml](https://github.com/SAML-Toolkits/ruby-saml) - SAML SSO for Ruby
* [benbalter/jekyll-auth](https://github.com/benbalter/jekyll-auth) - A simple way to use GitHub OAuth to serve a protected Jekyll site to your GitHub organization *(archived)*
* [chaps-io/access-granted](https://github.com/chaps-io/access-granted) - Multi-role and whitelist based authorization gem for Rails (and not only Rails!)
* [cedarcode/webauthn-ruby](https://github.com/cedarcode/webauthn-ruby) - WebAuthn ruby server library ― Make your Ruby/Rails web server become a conformant WebAuthn Relying Party
* [ruby-oauth/oauth](https://github.com/ruby-oauth/oauth) - 🔑 A Ruby wrapper for OAuth 1.0, and 1.0a protocols; clients & servers
* [devise-security/devise-security](https://github.com/devise-security/devise-security) - A security extension for devise, meeting industry-standard security demands for web applications.
* [rubycas/rubycas-server](https://github.com/rubycas/rubycas-server) - Provides single sign-on authentication for web applications, implementing the server-end of Jasig's CAS protocol.
* [tuwukee/jwt_sessions](https://github.com/tuwukee/jwt_sessions) - XSS/CSRF safe JWT auth designed for SPA
* [oivoodoo/devise_masquerade](https://github.com/oivoodoo/devise_masquerade) - Extension for devise, enable login as functionality. Add link to the masquerade_path(resource) and use it.
* [googleapis/google-auth-library-ruby](https://github.com/googleapis/google-auth-library-ruby) - Google Auth Library for Ruby
* [mgomes/api_auth](https://github.com/mgomes/api_auth) - HMAC authentication for Rails and HTTP Clients
* [exAspArk/graphql-guard](https://github.com/exAspArk/graphql-guard) - Simple authorization gem for GraphQL :lock:

### Reverse Engineering

* [hack-different/apple-knowledge](https://github.com/hack-different/apple-knowledge) - A collection of reverse engineered Apple things, as well as a machine-readable database of Apple hardware
* [jjyg/metasm](https://github.com/jjyg/metasm) - This is the main repository for metasm, a free assembler / disassembler / compiler written in ruby

## Concurrency and Performance

### Concurrency and Parallelism

* [ruby-concurrency/concurrent-ruby](https://github.com/ruby-concurrency/concurrent-ruby) - Modern concurrency tools including agents, futures, promises, thread pools, supervisors, and more. Inspired by Erlang, Clojure, Scala, Go, Java, JavaScript, and classic concurrency patterns.
* [eventmachine/eventmachine](https://github.com/eventmachine/eventmachine) - EventMachine: fast, simple event-processing library for Ruby programs
* [grosser/parallel](https://github.com/grosser/parallel) - Ruby: parallel processing made simple and fast
* [celluloid/celluloid](https://github.com/celluloid/celluloid) - Actor-based concurrent object framework for Ruby
* [socketry/async](https://github.com/socketry/async) - An awesome asynchronous event-driven reactor for Ruby.
* [ReactiveX/RxRuby](https://github.com/ReactiveX/RxRuby) - Reactive Extensions for Ruby
* [igrigorik/agent](https://github.com/igrigorik/agent) - Agent is an attempt at modelling Go-like concurrency, in Ruby
* [meh/ruby-thread](https://github.com/meh/ruby-thread) - Various extensions to the base thread library.

### Performance and Optimization

* [rails/bootsnap](https://github.com/rails/bootsnap) - Boot large Ruby/Rails apps faster
* [evanphx/benchmark-ips](https://github.com/evanphx/benchmark-ips) - Provides iteration per second benchmarking for Ruby
* [rubyzip/rubyzip](https://github.com/rubyzip/rubyzip) - Official Rubyzip repository
* [drujensen/fib](https://github.com/drujensen/fib) - Performance Benchmark of top Github languages
* [panorama-ed/memo_wise](https://github.com/panorama-ed/memo_wise) - The wise choice for Ruby memoization
* [Shopify/autotuner](https://github.com/Shopify/autotuner) - Get suggestions to tune Ruby's garbage collector

## Testing and Quality

### Testing

* [faker-ruby/faker](https://github.com/faker-ruby/faker) - A library for generating fake data such as names, addresses, and phone numbers.
* [thoughtbot/factory_bot](https://github.com/thoughtbot/factory_bot) - A library for setting up Ruby objects as test data.
* [github/scientist](https://github.com/github/scientist) - :microscope: A Ruby library for carefully refactoring critical paths.
* [cucumber/cucumber-ruby](https://github.com/cucumber/cucumber-ruby) - Cucumber for Ruby. It's amazing!
* [simplecov-ruby/simplecov](https://github.com/simplecov-ruby/simplecov) - Code coverage for Ruby with a powerful configuration library and automatic merging of coverage across test suites
* [bblimke/webmock](https://github.com/bblimke/webmock) - Library for stubbing and setting expectations on HTTP requests in Ruby.
* [thoughtbot/shoulda-matchers](https://github.com/thoughtbot/shoulda-matchers) - Simple one-liner tests for common Rails functionality
* [grosser/parallel_tests](https://github.com/grosser/parallel_tests) - Ruby: 2 CPUs = 2x Testing Speed for RSpec, Test::Unit and Cucumber
* [travisjeffery/timecop](https://github.com/travisjeffery/timecop) - A gem providing "time travel", "time freezing", and "time acceleration" capabilities, making it simple to test time-dependent code. It provides a unified method to mock Time.now, Date.today, and DateTime.now in a single call.
* [minitest/minitest](https://github.com/minitest/minitest) - minitest provides a complete suite of testing facilities supporting TDD, BDD, and benchmarking.
* [DatabaseCleaner/database_cleaner](https://github.com/DatabaseCleaner/database_cleaner) - Strategies for cleaning databases in Ruby. Can be used to ensure a clean state for testing.
* [rspec/rspec-metagem](https://github.com/rspec/rspec-metagem) - RSpec meta-gem that depends on the other components *(archived)*
* [danmayer/coverband](https://github.com/danmayer/coverband) - Ruby production code coverage collection and reporting (line of code usage)
* [pact-foundation/pact-ruby](https://github.com/pact-foundation/pact-ruby) - Enables consumer driven contract testing, providing a mock service and DSL for the consumer project, and interaction playback and verification for the service provider project.
* [mbj/mutant](https://github.com/mbj/mutant) - Mutation testing for Ruby. AI writes your code. AI writes your tests. But who tests the tests?
* [test-prof/test-prof](https://github.com/test-prof/test-prof) - Ruby Tests Profiling Toolbox
* [test-kitchen/test-kitchen](https://github.com/test-kitchen/test-kitchen) - Test Kitchen is an integration tool for developing and testing infrastructure code and software on isolated target platforms
* [dchelimsky/rspec](https://github.com/dchelimsky/rspec) - Behaviour Driven Development framework for Ruby *(archived)*
* [gjtorikian/html-proofer](https://github.com/gjtorikian/html-proofer) - Test your rendered HTML files to make sure they're accurate.
* [brynary/webrat](https://github.com/brynary/webrat) - Webrat - Ruby Acceptance Testing for Web applications
* [testdouble/suture](https://github.com/testdouble/suture) - 🏥 A Ruby gem that helps you refactor your legacy code
* [thoughtbot/appraisal](https://github.com/thoughtbot/appraisal) - A Ruby library for testing your library against different versions of dependencies.
* [freerange/mocha](https://github.com/freerange/mocha) - A mocking and stubbing library for Ruby
* [rspec/rspec-expectations](https://github.com/rspec/rspec-expectations) - Provides a readable API to express expected outcomes of a code example *(archived)*
* [rspec/rspec-core](https://github.com/rspec/rspec-core) - RSpec runner and formatters *(archived)*
* [email-spec/email-spec](https://github.com/email-spec/email-spec) - Collection of RSpec/MiniTest matchers and Cucumber steps for testing email in a ruby app using ActionMailer or Pony
* [rspec/rspec-mocks](https://github.com/rspec/rspec-mocks) - RSpec's 'test double' framework, with support for stubbing and mocking *(archived)*
* [newcontext-oss/kitchen-terraform](https://github.com/newcontext-oss/kitchen-terraform) - Test Kitchen plugins for testing Terraform configurations *(archived)*
* [chrisk/fakeweb](https://github.com/chrisk/fakeweb) - Ruby test helper for injecting fake responses to web requests
* [splitwise/super_diff](https://github.com/splitwise/super_diff) - A more helpful way to view differences between complex data structures in RSpec.
* [cucumber/cucumber-rails](https://github.com/cucumber/cucumber-rails) - Rails Generators for Cucumber with special support for Capybara and DatabaseCleaner
* [yujinakayama/transpec](https://github.com/yujinakayama/transpec) - The RSpec syntax converter
* [stripe-ruby-mock/stripe-ruby-mock](https://github.com/stripe-ruby-mock/stripe-ruby-mock) - A mocking library for testing stripe ruby
* [paulelliott/fabrication](https://github.com/paulelliott/fabrication) - This project has moved to GitLab! Please check there for the latest updates. *(archived)*
* [cucumber/aruba](https://github.com/cucumber/aruba) - Test command-line applications with Cucumber-Ruby, RSpec or Minitest.
* [rack/rack-test](https://github.com/rack/rack-test) - Rack::Test is a small, simple testing API for Rack apps.
* [grodowski/undercover](https://github.com/grodowski/undercover) - undercover warns about methods, classes and blocks that were changed without tests, to help you easily find untested code and reduce the number of bugs. It does so by analysing data from git diffs, code structure and SimpleCov coverage reports
* [ThrowTheSwitch/Ceedling](https://github.com/ThrowTheSwitch/Ceedling) - Unit testing and build system for C projects
* [voicerepublic/vr-api-specs](https://github.com/voicerepublic/vr-api-specs) - Ruby RSpec suite against our public API
* [dchelimsky/rspec-rails](https://github.com/dchelimsky/rspec-rails) - RSpec extension library for Ruby on Rails *(archived)*
* [jasmine/jasmine-gem](https://github.com/jasmine/jasmine-gem) - Jasmine ruby gem *(archived)*
* [oesmith/puffing-billy](https://github.com/oesmith/puffing-billy) - A rewriting web proxy for testing interactions between your browser and external sites. Works with ruby + rspec.
* [ruby/spec](https://github.com/ruby/spec) - The Ruby Spec Suite aka ruby/spec
* [thoughtbot/climate_control](https://github.com/thoughtbot/climate_control) - Modify your ENV
* [palkan/n_plus_one_control](https://github.com/palkan/n_plus_one_control) - RSpec and Minitest matchers to prevent N+1 queries problem
* [KnapsackPro/knapsack](https://github.com/KnapsackPro/knapsack) - Knapsack splits tests evenly across parallel CI nodes to run fast CI build and save you time.
* [sds/mock_redis](https://github.com/sds/mock_redis) - Mock Redis gem for Ruby
* [btakita/rr](https://github.com/btakita/rr) - RR (Double Ruby) is a test double framework that features a rich selection of double techniques and a terse syntax.
* [mongoid/mongoid-rspec](https://github.com/mongoid/mongoid-rspec) - RSpec matchers and macros for Mongoid.
* [test-kitchen/kitchen-docker](https://github.com/test-kitchen/kitchen-docker) - A Test Kitchen Driver for Docker
* [bebanjo/delorean](https://github.com/bebanjo/delorean) - DISCONTINUED - Delorean lets you travel in time with Ruby by mocking Time.now
* [abepetrillo/evergreen](https://github.com/abepetrillo/evergreen) - Run Jasmine JavaScript unit tests, integrate them into Ruby applications.

## Utilities

### Command Line Tools

* [github-changelog-generator/github-changelog-generator](https://github.com/github-changelog-generator/github-changelog-generator) - Automatically generate change log from your tags, issues, labels and pull requests on GitHub.
* [sferik/x-cli](https://github.com/sferik/x-cli) - A command-line power tool for Twitter.
* [athityakumar/colorls](https://github.com/athityakumar/colorls) - A Ruby gem that beautifies the terminal's ls command, with color and font-awesome icons. :tada:
* [cesarferreira/dryrun](https://github.com/cesarferreira/dryrun) - ☁️ Try the demo project of any Android Library
* [bashly-framework/bashly](https://github.com/bashly-framework/bashly) - Bash command line framework and CLI generator
* [twitter/twurl](https://github.com/twitter/twurl) - OAuth-enabled curl for the Twitter API
* [htty/htty](https://github.com/htty/htty) - htty is the HTTP TTY, a console application for interacting with web servers.
* [thisredone/rb](https://github.com/thisredone/rb) - Turns Ruby into a versatile command line utility
* [leejarvis/slop](https://github.com/leejarvis/slop) - Simple Lightweight Option Parsing - ✨ new contributors welcome ✨
* [tj/commander](https://github.com/tj/commander) - The complete solution for Ruby command-line executables
* [commander-rb/commander](https://github.com/commander-rb/commander) - The complete solution for Ruby command-line executables
* [ianks/octodown](https://github.com/ianks/octodown) - Github markdown previewing straight from your shell.
* [nhmood/watson-ruby](https://github.com/nhmood/watson-ruby) - inline issue manager
* [grosser/pru](https://github.com/grosser/pru) - Pipeable Ruby - forget about grep / sed / awk / wc ... use pure, readable Ruby!
* [adamwiggins/rush](https://github.com/adamwiggins/rush) - Ruby replacement for bash+ssh
* [tj/pomo](https://github.com/tj/pomo) - Ruby Pomodoro app for the command-line (time / task management)
* [davetron5000/optparse-plus](https://github.com/davetron5000/optparse-plus) - Start your command line scripts off right in Ruby
* [pawurb/termit](https://github.com/pawurb/termit) - Translations with speech synthesis in your terminal as a ruby gem *(archived)*
* [cbbrowne/tpp](https://github.com/cbbrowne/tpp) - Text Powerpoint
* [matt-harvey/git_curate](https://github.com/matt-harvey/git_curate) - ✂️ Peruse and delete git branches ergonomically
* [tombenner/ru](https://github.com/tombenner/ru) - Ruby in your shell!
* [ku1ik/racksh](https://github.com/ku1ik/racksh) - Console for Rack based ruby web apps

### Logging and Configuration

* [fluent/fluentd](https://github.com/fluent/fluentd) - Fluentd: Unified Logging Layer (project under CNCF)
* [bkeepers/dotenv](https://github.com/bkeepers/dotenv) - A Ruby gem to load environment variables from `.env`.
* [flippercloud/flipper](https://github.com/flippercloud/flipper) - 🐬 Beautiful, performant feature flags for Ruby.
* [fetlife/rollout](https://github.com/fetlife/rollout) - Feature flippers.
* [rubyconfig/config](https://github.com/rubyconfig/config) - Easiest way to add multi-environment yaml settings to Rails, Sinatra, Padrino and other Ruby projects.
* [ledermann/rails-settings](https://github.com/ledermann/rails-settings) - Manage settings with Ruby on Rails
* [reidmorrison/semantic_logger](https://github.com/reidmorrison/semantic_logger) - Semantic Logger is a high-performance, asynchronous structured logging framework for Ruby and Rails.
* [palkan/anyway_config](https://github.com/palkan/anyway_config) - Configuration library for Ruby gems and applications
* [trusche/httplog](https://github.com/trusche/httplog) - Log outgoing HTTP requests in ruby
* [markbates/configatron](https://github.com/markbates/configatron) - A super cool, simple, and feature rich configuration system for Ruby apps.
* [silva96/log_bench](https://github.com/silva96/log_bench) - A terminal-based Rails log viewer with real-time monitoring and filtering capabilities
* [TwP/logging](https://github.com/TwP/logging) - A flexible logging library for use in Ruby programs based on the design of Java's log4j library.
* [vinistock/sail](https://github.com/vinistock/sail) - Sail is a lightweight Rails engine that brings an admin panel for managing configuration settings on a live Rails app
* [dwbutler/logstash-logger](https://github.com/dwbutler/logstash-logger) - Ruby logger that writes logstash events
* [papertrail/papertrail-cli](https://github.com/papertrail/papertrail-cli) - Command-line client for Papertrail hosted syslog & app log management service

### Text Processing

* [realm/jazzy](https://github.com/realm/jazzy) - Soulful docs for Swift & Objective-C
* [slim-template/slim](https://github.com/slim-template/slim) - Slim is a template language whose goal is to reduce the syntax to the essential parts without becoming cryptic.
* [asciidoctor/asciidoctor](https://github.com/asciidoctor/asciidoctor) - :gem: A fast, open source text processor and publishing toolchain, written in Ruby, for converting AsciiDoc content to HTML 5, DocBook 5, and other formats.
* [prawnpdf/prawn](https://github.com/prawnpdf/prawn) - Fast, Nimble PDF Writer for Ruby
* [github/gemoji](https://github.com/github/gemoji) - Emoji images and names.
* [svenfuchs/rails-i18n](https://github.com/svenfuchs/rails-i18n) - Repository for collecting Locale data for Ruby on Rails I18n as well as other interesting, Rails related I18n stuff
* [mileszs/wicked_pdf](https://github.com/mileszs/wicked_pdf) - PDF generator (from HTML) plugin for Ruby on Rails
* [rouge-ruby/rouge](https://github.com/rouge-ruby/rouge) - A pure Ruby code highlighter that is compatible with Pygments
* [mustache/mustache](https://github.com/mustache/mustache) - Logic-less Ruby templates.
* [pdfkit/pdfkit](https://github.com/pdfkit/pdfkit) - A Ruby gem to transform HTML + CSS into PDFs using the command-line utility wkhtmltopdf
* [premailer/premailer](https://github.com/premailer/premailer) - Preflight for HTML email
* [rgrove/sanitize](https://github.com/rgrove/sanitize) - Ruby HTML and CSS sanitizer.
* [lsegal/yard](https://github.com/lsegal/yard) - YARD is a Ruby Documentation tool. The Y stands for "Yay!"
* [whomwah/rqrcode](https://github.com/whomwah/rqrcode) - A Ruby library that encodes QR Codes
* [rtomayko/tilt](https://github.com/rtomayko/tilt) - Generic interface to multiple Ruby template engines
* [ruby/did_you_mean](https://github.com/ruby/did_you_mean) - The gem that has been saving people from typos since 2014
* [gettalong/kramdown](https://github.com/gettalong/kramdown) - kramdown is a fast, pure Ruby Markdown superset converter, using a strict syntax definition and supporting several common extensions.
* [fphilipe/premailer-rails](https://github.com/fphilipe/premailer-rails) - CSS styled emails without the hassle.
* [sporkmonger/addressable](https://github.com/sporkmonger/addressable) - Addressable is an alternative implementation to the URI implementation that is part of Ruby's standard library. It is flexible, offers heuristic parsing, and additionally provides extensive support for IRIs and URI templates.
* [benbalter/word-to-markdown](https://github.com/benbalter/word-to-markdown) - A ruby gem to liberate content from Microsoft Word documents
* [gettalong/hexapdf](https://github.com/gettalong/hexapdf) - Versatile PDF creation and manipulation for Ruby
* [samg/diffy](https://github.com/samg/diffy) - Easy Diffing in Ruby
* [asciidoctor/asciidoctor-pdf](https://github.com/asciidoctor/asciidoctor-pdf) - :page_with_curl: Asciidoctor PDF: A native PDF converter for AsciiDoc based on Asciidoctor and Prawn, written entirely in Ruby.
* [daddyz/phonelib](https://github.com/daddyz/phonelib) - Ruby gem for phone validation and formatting using google libphonenumber library data
* [shioyama/mobility](https://github.com/shioyama/mobility) - Pluggable Ruby translation framework
* [Studiosity/grover](https://github.com/Studiosity/grover) - A Ruby gem to transform HTML into PDFs, PNGs or JPEGs using Google Puppeteer/Chromium
* [ruby-i18n/i18n](https://github.com/ruby-i18n/i18n) - Internationalization (i18n) library for Ruby
* [flavorjones/loofah](https://github.com/flavorjones/loofah) - Ruby library for HTML/XML transformation and sanitization
* [rsl/stringex](https://github.com/rsl/stringex) - Some [hopefully] useful extensions to Ruby’s String class. It is made up of three libraries: ActsAsUrl [permalink solution with better character translation], Unidecoder [Unicode to Ascii transliteration], and StringExtensions [miscellaneous helper methods for the String class].
* [peterhellberg/hashids.rb](https://github.com/peterhellberg/hashids.rb) - A small Ruby gem to generate YouTube-like hashes from one or many numbers. Use hashids when you do not want to expose your database ids to the user.
* [k0kubun/hamlit](https://github.com/k0kubun/hamlit) - High Performance Haml Implementation
* [ruby/rdoc](https://github.com/ruby/rdoc) - RDoc produces HTML and online documentation for Ruby projects.
* [licensee/licensee](https://github.com/licensee/licensee) - A Ruby Gem to detect under what license a project is distributed.
* [boazsegev/combine_pdf](https://github.com/boazsegev/combine_pdf) - A Pure ruby library to merge PDF files, number pages and maybe more...
* [podigee/device_detector](https://github.com/podigee/device_detector) - DeviceDetector is a precise and fast user agent parser and device detector written in Ruby
* [twitter/twitter-cldr-rb](https://github.com/twitter/twitter-cldr-rb) - Ruby implementation of the ICU (International Components for Unicode) that uses the Common Locale Data Repository to format dates, plurals, and more.
* [fnando/kitabu](https://github.com/fnando/kitabu) - A framework for creating e-books from Markdown using Ruby. Using the Prince PDF generator, you'll be able to get high quality PDFs. Also supports EPUB, Mobi, Text and HTML generation.
* [xijo/reverse_markdown](https://github.com/xijo/reverse_markdown) - Ruby gem to convert html into markdown
* [zendesk/curly](https://github.com/zendesk/curly) - The Curly template language allows separating your logic from the structure of your HTML templates. *(archived)*
* [pygments/pygments.rb](https://github.com/pygments/pygments.rb) - 💎 Ruby wrapper for Pygments syntax highlighter
* [ryan-endacott/verbal_expressions](https://github.com/ryan-endacott/verbal_expressions) - Make difficult regular expressions easy! Ruby port of the awesome VerbalExpressions repo - https://github.com/jehna/VerbalExpressions
* [sstephenson/global_phone](https://github.com/sstephenson/global_phone) - Parse, validate, and format phone numbers in Ruby using Google's libphonenumber database *(archived)*
* [infinum/phrasing](https://github.com/infinum/phrasing) - Edit phrases inline for your Ruby on Rails applications! *(archived)*
* [janx/ruby-pinyin](https://github.com/janx/ruby-pinyin) - 中文汉字转拼音, 支持中英文符号混合词语。Pinyin is a romanization system (phonemic notation) of Chinese characters, this gem helps you to convert Chinese characters into pinyin form.
* [tom-lord/regexp-examples](https://github.com/tom-lord/regexp-examples) - Generate strings that match a given regular expression
* [judofyr/temple](https://github.com/judofyr/temple) - Template compilation framework in Ruby
* [r18n/r18n](https://github.com/r18n/r18n) - I18n tool to translate your Ruby application.
* [usmanbashir/haikunator](https://github.com/usmanbashir/haikunator) - Heroku-like random name generator.
* [bhollis/maruku](https://github.com/bhollis/maruku) - A pure-Ruby Markdown-superset interpreter (Official Repo). *(archived)*
* [yaroslav/russian](https://github.com/yaroslav/russian) - Russian language support for Ruby and Rails: localization, date and time handling, pluralization, and improved Russian language support in Rails. | Поддержка русского языка для Ruby и Rails: локализация, работа с датой и временем, плюрализация, локализация, улучшенная поддержка русского языка в Rails.
* [bmuller/gender_detector](https://github.com/bmuller/gender_detector) - Get gender from first name in Ruby.
* [rtomayko/rocco](https://github.com/rtomayko/rocco) - Rocco is Docco in Ruby *(archived)*

### Files and Operating System

* [carrierwaveuploader/carrierwave](https://github.com/carrierwaveuploader/carrierwave) - Classier solution for file uploads for Rails, Sinatra and other Ruby web frameworks
* [backup/backup](https://github.com/backup/backup) - Easy full stack backup operations on UNIX-like systems.
* [shrinerb/shrine](https://github.com/shrinerb/shrine) - File Attachment toolkit for Ruby applications
* [Chris911/iStats](https://github.com/Chris911/iStats) - Ruby gem for your mac stats
* [refile/refile](https://github.com/refile/refile) - Ruby file uploads, take 3
* [copiousfreetime/launchy](https://github.com/copiousfreetime/launchy) - A helper for launching cross-platform applications in a fire and forget manner.
* [danielpclark/faster_path](https://github.com/danielpclark/faster_path) - Faster Pathname handling for Ruby written in Rust
* [chef/ohai](https://github.com/chef/ohai) - Ohai profiles your system and emits JSON
* [thuehlinger/daemons](https://github.com/thuehlinger/daemons) - Ruby daemons gem official repository
* [adamcooke/procodile](https://github.com/adamcooke/procodile) - 🐊 Run processes in the background (and foreground) on Mac & Linux from a Procfile (for production and/or development environments)
* [enkessler/childprocess](https://github.com/enkessler/childprocess) - Cross-platform Ruby library for managing child processes.
* [kennethkalmer/daemon-kit](https://github.com/kennethkalmer/daemon-kit) - Daemon Kit aims to simplify creating Ruby daemons by providing a sound application skeleton (through a generator), task specific generators (jabber bot, etc) and robust environment management code.
* [rtomayko/posix-spawn](https://github.com/rtomayko/posix-spawn) - Ruby process spawning library
* [DAddYE/foreverb](https://github.com/DAddYE/foreverb) - Small daemon framework for ruby, with logging, error handler, scheduling and much more.
* [filewatcher/filewatcher](https://github.com/filewatcher/filewatcher) - Ruby gem to perform actions when files are changed. No config files. Pure Ruby implementation and minimalistic Ruby API.

### Date and Time

* [javan/whenever](https://github.com/javan/whenever) - Cron jobs in Ruby
* [mojombo/chronic](https://github.com/mojombo/chronic) - Chronic is a pure Ruby natural language date parser.
* [ice-cube-ruby/ice_cube](https://github.com/ice-cube-ruby/ice_cube) - Ruby Date Recurrence Library - Allows easy creation of recurrence rules and fast querying
* [jmettraux/rufus-scheduler](https://github.com/jmettraux/rufus-scheduler) - scheduler for Ruby (at, in, cron and every jobs)
* [sidekiq-cron/sidekiq-cron](https://github.com/sidekiq-cron/sidekiq-cron) - Scheduler / Cron for Sidekiq jobs
* [sidekiq-scheduler/sidekiq-scheduler](https://github.com/sidekiq-scheduler/sidekiq-scheduler) - Lightweight job scheduler extension for Sidekiq
* [excid3/simple_calendar](https://github.com/excid3/simple_calendar) - A wonderfully simple calendar gem for Rails
* [holidays/holidays](https://github.com/holidays/holidays) - A collection of Ruby methods to deal with statutory and other holidays. You deserve a holiday!
* [rossta/montrose](https://github.com/rossta/montrose) - Recurring events library for Ruby. Enumerable recurrence objects and convenient chainable interface.
* [plashchynski/crono](https://github.com/plashchynski/crono) - A time-based background job scheduler daemon (just like Cron) for Rails
* [Intrepidd/working_hours](https://github.com/Intrepidd/working_hours) - ⏰ A modern ruby gem allowing to do time calculation with business / working hours.
* [floraison/fugit](https://github.com/floraison/fugit) - time tools (cron, parsing, durations, ...) for Ruby, rufus-scheduler, and flor
* [gocardless/business](https://github.com/gocardless/business) - Ruby business day calculations
* [codegram/date_validator](https://github.com/codegram/date_validator) - A simple, ORM agnostic, Ruby >=2.2 compatible date validator for Rails, based on ActiveModel.
* [zendesk/biz](https://github.com/zendesk/biz) - Time calculations using business hours.
* [rubyredrick/ri_cal](https://github.com/rubyredrick/ri_cal) - New Rfc 2445 (iCalendar) gem for Ruby
* [jeremyevans/home_run](https://github.com/jeremyevans/home_run) - Fast Date/DateTime classes for ruby :: Unmaintained, unnecessary on ruby 1.9.3+ *(archived)*

### Automation and Scripting

* [Mark24Code/rime-auto-deploy](https://github.com/Mark24Code/rime-auto-deploy) - Rime输入法安装脚本，让一切更轻松。Make using Rime easy.
* [litaio/lita](https://github.com/litaio/lita) - ChatOps for Ruby. *(archived)*
* [reenhanced/gitreflow](https://github.com/reenhanced/gitreflow) - Reflow automatically creates pull requests, ensures the code review is approved, and squash merges finished branches to master with a great commit message template.
* [atipugin/telegram-bot-ruby](https://github.com/atipugin/telegram-bot-ruby) - Ruby wrapper for Telegram's Bot API
* [slack-ruby/slack-ruby-bot](https://github.com/slack-ruby/slack-ruby-bot) - The easiest way to write a Slack bot in Ruby. *(archived)*
* [jgorset/facebook-messenger](https://github.com/jgorset/facebook-messenger) - Definitely the best way to make Bots on Facebook Messenger with Ruby
* [benhoskings/babushka](https://github.com/benhoskings/babushka) - Test-driven sysadmin. *(archived)*
* [antifuchs/gmail-britta](https://github.com/antifuchs/gmail-britta) - Generate complex gmail filters via a neat little ruby DSL
* [braintree/runbook](https://github.com/braintree/runbook) - A framework for gradual system automation
* [x-motemen/git-pr-release](https://github.com/x-motemen/git-pr-release) - Release pull request generator
* [telegram-bot-rb/telegram-bot](https://github.com/telegram-bot-rb/telegram-bot) - Ruby gem for building Telegram Bot with optional Rails integration
* [hellostealth/stealth](https://github.com/hellostealth/stealth) - An open source Ruby framework for text and voice chatbots. 🤖
* [gousiosg/github-mirror](https://github.com/gousiosg/github-mirror) - Scripts to mirror Github in a cloudy fashion
* [jekyll/jekyll-import](https://github.com/jekyll/jekyll-import) - :inbox_tray: The "jekyll import" command for importing from various blogs to Jekyll format.
* [jmettraux/ruote](https://github.com/jmettraux/ruote) - a ruby workflow engine (dead) *(archived)*
* [muffinista/chatterbot](https://github.com/muffinista/chatterbot) - A straightforward ruby-based Twitter Bot Framework, using OAuth to authenticate. *(archived)*
* [r7kamura/ruboty](https://github.com/r7kamura/ruboty) - Ruby + Bot = Ruboty

### General Purpose Libraries

* [aasm/aasm](https://github.com/aasm/aasm) - AASM - State machines for Ruby classes (plain Ruby, ActiveRecord, Mongoid, NoBrainer, Dynamoid)
* [solnic/virtus](https://github.com/solnic/virtus) - [DISCONTINUED ] Attributes on Steroids for Plain Old Ruby Objects
* [pluginaweek/state_machine](https://github.com/pluginaweek/state_machine) - Adds support for creating state machines for attributes on any Ruby class
* [hashie/hashie](https://github.com/hashie/hashie) - Hashie is a collection of classes and mixins that make Ruby hashes more powerful.
* [RubyMoney/money](https://github.com/RubyMoney/money) - A Ruby Library for dealing with money and currency conversion.
* [kanwei/algorithms](https://github.com/kanwei/algorithms) - Ruby algorithms and data structures. C extensions
* [fnando/browser](https://github.com/fnando/browser) - Do some browser detection with Ruby. Includes ActionController integration.
* [countries/countries](https://github.com/countries/countries) - All sorts of useful information about every country packaged as convenient little country objects. It includes data from ISO 3166 (countries and states/subdivisions ), ISO 4217 (currency), and E.164 (phone numbers).
* [AaronLasseigne/active_interaction](https://github.com/AaronLasseigne/active_interaction) - :briefcase: Manage application specific business logic.
* [fxn/zeitwerk](https://github.com/fxn/zeitwerk) - Efficient and thread-safe code loader for Ruby
* [ffi/ffi](https://github.com/ffi/ffi) - Ruby FFI
* [hamstergem/hamster](https://github.com/hamstergem/hamster) - Efficient, Immutable, Thread-Safe Collection classes for Ruby
* [geekq/workflow](https://github.com/geekq/workflow) - Ruby finite-state-machine-inspired API for modeling workflow
* [dry-rb/dry-validation](https://github.com/dry-rb/dry-validation) - Validation library with type-safe schemas and rules
* [leereilly/swot](https://github.com/leereilly/swot) - Archived — SWOT delighted millions of students with GitHub discounts and saved bazillions of review hours. Follow JetBrains/swot for future updates. *(archived)*
* [carmen-ruby/carmen](https://github.com/carmen-ruby/carmen) - A repository of geographic regions for Ruby
* [avdi/naught](https://github.com/avdi/naught) - A toolkit for building Null Object classes in Ruby
* [dry-rb/dry-types](https://github.com/dry-rb/dry-types) - Flexible type system for Ruby with coercions and constraints
* [dry-rb/dry-monads](https://github.com/dry-rb/dry-monads) - Useful, common monads in idiomatic Ruby
* [adomokos/light-service](https://github.com/adomokos/light-service) - Series of Actions with an emphasis on simplicity.
* [state-machines/state_machines](https://github.com/state-machines/state_machines) - Adds support for creating state machines for attributes on any Ruby class
* [rubyworks/facets](https://github.com/rubyworks/facets) - Ruby Facets
* [sunny/actor](https://github.com/sunny/actor) - Composable Ruby service objects
* [nebulab/simple_command](https://github.com/nebulab/simple_command) - A simple, standardized way to build and use Service Objects (aka Commands) in Ruby
* [liufengyun/hashdiff](https://github.com/liufengyun/hashdiff) - Hashdiff is a ruby library to to compute the smallest difference between two hashes
* [apneadiving/waterfall](https://github.com/apneadiving/waterfall) - A slice of functional programming to chain ruby services and blocks, thus providing a new approach to flow control. Make them flow!
* [tomstuart/monads](https://github.com/tomstuart/monads) - Simple Ruby implementations of some common monads.
* [sferik/active_emoji](https://github.com/sferik/active_emoji) - A collection of emoji aliases for core Ruby methods
* [barsoom/attr_extras](https://github.com/barsoom/attr_extras) - Takes some boilerplate out of Ruby with methods like attr_initialize.
* [u-gems/u-case](https://github.com/u-gems/u-case) - Represent use cases in a simple and powerful way while writing modular, expressive and sequentially logical code.
* [jdantonio/functional-ruby](https://github.com/jdantonio/functional-ruby) - A gem for adding functional programming tools to Ruby. Inspired by Erlang, Clojure, Haskell, and Functional Java. *(archived)*
* [tom-pang/Values](https://github.com/tom-pang/Values) - Simple immutable value objects for ruby (the readme is longer than the code)
* [soveran/micromachine](https://github.com/soveran/micromachine) - Minimal Finite State Machine
* [marcandre/backports](https://github.com/marcandre/backports) - The latest features of Ruby backported to older versions.
* [jarmo/require_all](https://github.com/jarmo/require_all) - A wonderfully simple way to load Ruby code

## Science and Math

### Mathematics

* [rgeo/rgeo](https://github.com/rgeo/rgeo) - Geospatial data library for Ruby
* [olbrich/ruby-units](https://github.com/olbrich/ruby-units) - A unit handling library for ruby

### Scientific Computing

* [hybridgroup/artoo](https://github.com/hybridgroup/artoo) - Ruby framework for robotics, drones, and the Internet of Things (IoT)
* [SciRuby/sciruby](https://github.com/SciRuby/sciruby) - Tools for scientific computation in Ruby
* [jwhitehorn/pi_piper](https://github.com/jwhitehorn/pi_piper) - Event driven Raspberry Pi GPIO programming in Ruby
* [atduskgreg/rad](https://github.com/atduskgreg/rad) - Ruby Arduino Development: a framework for programming the Arduino physcial computing platform using Ruby

## Other

* [mastodon/mastodon](https://github.com/mastodon/mastodon) - Your self-hosted, globally interconnected microblogging community
* [huginn/huginn](https://github.com/huginn/huginn) - Create agents that monitor and act on your behalf. Your agents are standing by!
* [freeCodeCamp/devdocs](https://github.com/freeCodeCamp/devdocs) - API Documentation Browser
* [rapid7/metasploit-framework](https://github.com/rapid7/metasploit-framework) - Metasploit Framework
* [kilimchoi/engineering-blogs](https://github.com/kilimchoi/engineering-blogs) - A curated list of engineering blogs
* [bayandin/awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness) - A curated list of awesome awesomeness
* [matteocrippa/awesome-swift](https://github.com/matteocrippa/awesome-swift) - A collaborative list of awesome Swift libraries and resources. Feel free to contribute!
* [Homebrew/homebrew-cask](https://github.com/Homebrew/homebrew-cask) - 🍻 Default casks (upstream binary packages) for the package manager for everywhere
* [docusealco/docuseal](https://github.com/docusealco/docuseal) - Open source DocuSign alternative. Create, fill, and sign digital documents ✍️
* [CocoaPods/CocoaPods](https://github.com/CocoaPods/CocoaPods) - The Cocoa Dependency Manager.
* [mame/quine-relay](https://github.com/mame/quine-relay) - An uroboros program with 100+ programming languages
* [basecamp/kamal](https://github.com/basecamp/kamal) - Deploy web apps anywhere.
* [neutraltone/awesome-stock-resources](https://github.com/neutraltone/awesome-stock-resources) - :city_sunrise: A collection of links for free stock photography, video and Illustration websites
* [tmuxinator/tmuxinator](https://github.com/tmuxinator/tmuxinator) - Manage complex tmux sessions easily
* [github-linguist/linguist](https://github.com/github-linguist/linguist) - Language Savant. If your repository's language is being reported incorrectly, send us a pull request!
* [Shopify/liquid](https://github.com/Shopify/liquid) - Liquid markup language. Safe, customer facing template language for flexible web apps.
* [greatghoul/remote-working](https://github.com/greatghoul/remote-working) - 收集整理远程工作相关的资料
* [jordansissel/fpm](https://github.com/jordansissel/fpm) - Effing package management! Build packages for multiple platforms (deb, rpm, etc) with great ease and sanity.
* [DeathKing/Learning-SICP](https://github.com/DeathKing/Learning-SICP) - MIT视频公开课《计算机程序的构造和解释》中文化项目及课程学习资料搜集。
* [Freika/dawarich](https://github.com/Freika/dawarich) - Your favorite self-hostable alternative to Google Timeline (Google Location History)
* [teamcapybara/capybara](https://github.com/teamcapybara/capybara) - Acceptance test framework for web applications
* [wpscanteam/wpscan](https://github.com/wpscanteam/wpscan) - WPScan WordPress security scanner. Written for security professionals and blog maintainers to test the security of their WordPress websites. Contact us via contact@wpscan.com
* [we-promise/sure](https://github.com/we-promise/sure) - The personal finance app for everyone (by everyone)
* [antiwork/gumroad](https://github.com/antiwork/gumroad) - See what sticks
* [thoughtbot/guides](https://github.com/thoughtbot/guides) - A guide for programming in style.
* [freeCodeCamp/how-to-contribute-to-open-source](https://github.com/freeCodeCamp/how-to-contribute-to-open-source) - A guide to contributing to open source
* [imathis/octopress](https://github.com/imathis/octopress) - Octopress is an obsessively designed framework for Jekyll blogging. It’s easy to configure and easy to deploy. Sweet huh?
* [thoughtbot/paperclip](https://github.com/thoughtbot/paperclip) - Easy file attachment management for ActiveRecord *(archived)*
* [thoughtbot/bourbon](https://github.com/thoughtbot/bourbon) - A Lightweight Sass Tool Set *(archived)*
* [ankane/pghero](https://github.com/ankane/pghero) - A performance dashboard for Postgres
* [community/community](https://github.com/community/community) - Public feedback discussions for: GitHub Mobile, GitHub Discussions, GitHub Codespaces, GitHub Sponsors, GitHub Issues and more!
* [chef/chef](https://github.com/chef/chef) - Chef Infra, a powerful automation platform that transforms infrastructure into code automating how infrastructure is configured, deployed and managed across any environment, at any scale
* [railsadminteam/rails_admin](https://github.com/railsadminteam/rails_admin) - RailsAdmin is a Rails engine that provides an easy-to-use interface for managing your data
* [puppetlabs/puppet](https://github.com/puppetlabs/puppet) - Server automation framework and application
* [flyerhzm/bullet](https://github.com/flyerhzm/bullet) - help to kill N+1 queries and unused eager loading
* [middleman/middleman](https://github.com/middleman/middleman) - Hand-crafted frontend development
* [skwp/dotfiles](https://github.com/skwp/dotfiles) - YADR - The best vim,git,zsh plugins and the cleanest vimrc you've ever seen
* [chyingp/nodejs-learning-guide](https://github.com/chyingp/nodejs-learning-guide) - Nodejs学习笔记以及经验总结，公众号"程序猿小卡"
* [BetterErrors/better_errors](https://github.com/BetterErrors/better_errors) - Better error page for Rack apps
* [midudev/autoskills](https://github.com/midudev/autoskills) - One command. Your entire AI skill stack. Installed.
* [instructure/canvas-lms](https://github.com/instructure/canvas-lms) - The open LMS by Instructure, Inc.
* [ankane/searchkick](https://github.com/ankane/searchkick) - Intelligent search made easy
* [kkuchta/css-only-chat](https://github.com/kkuchta/css-only-chat) - A truly monstrous async web chat using no JS whatsoever on the frontend
* [busyloop/lolcat](https://github.com/busyloop/lolcat) - Rainbows and unicorns!
* [alexreisner/geocoder](https://github.com/alexreisner/geocoder) - Complete Ruby geocoding solution.
* [guard/guard](https://github.com/guard/guard) - Guard is a command line tool to easily handle events on file system modifications.
* [ddollar/foreman](https://github.com/ddollar/foreman) - Manage Procfile-based applications
* [felixonmars/dnsmasq-china-list](https://github.com/felixonmars/dnsmasq-china-list) - Chinese-specific configuration to improve your favorite DNS server. Best partner for chnroutes.
* [vcr/vcr](https://github.com/vcr/vcr) - Record your test suite's HTTP interactions and replay them during future test runs for fast, deterministic, accurate tests.
* [github/markup](https://github.com/github/markup) - Determines which markup library to use to render a content file (e.g. README) on GitHub
* [venmo/synx](https://github.com/venmo/synx) - A command-line tool that reorganizes your Xcode project folder to match your Xcode groups
* [redmine/redmine](https://github.com/redmine/redmine) - Mirror of redmine code source - Official Subversion repository is at https://svn.redmine.org/redmine - contact: @vividtone or maeda (at) farend (dot) jp
* [progit/progit](https://github.com/progit/progit) - Pro Git Book Content, 1st Edition - This content is deprecated. See 2nd edition at [progit2](https://github.com/progit/progit2) *(archived)*
* [lostisland/faraday](https://github.com/lostisland/faraday) - Simple, but flexible HTTP client library, with support for multiple backends.
* [hartator/wayback-machine-downloader](https://github.com/hartator/wayback-machine-downloader) - Download an entire website from the Wayback Machine.
* [square/maximum-awesome](https://github.com/square/maximum-awesome) - Config files for vim and tmux.
* [rails/webpacker](https://github.com/rails/webpacker) - Use Webpack to manage app-like JavaScript modules in Rails
* [rspec/rspec-rails](https://github.com/rspec/rspec-rails) - RSpec for Rails 7+
* [rails/thor](https://github.com/rails/thor) - Thor is a toolkit for building powerful command-line interfaces.
* [formtastic/formtastic](https://github.com/formtastic/formtastic) - A Rails form builder plugin with semantically rich and accessible markup.
* [shakacode/react_on_rails](https://github.com/shakacode/react_on_rails) - Integration of React + Webpack + Rails including server-side rendering of React, enabling a better developer experience and faster client performance.
* [rails-api/rails-api](https://github.com/rails-api/rails-api) - Rails for API only applications
* [hahwul/WebHackersWeapons](https://github.com/hahwul/WebHackersWeapons) - ⚔️ Web Hacker's Weapons / A collection of cool tools used by Web hackers. Happy hacking , Happy bug-hunting
* [mbleigh/acts-as-taggable-on](https://github.com/mbleigh/acts-as-taggable-on) - A tagging plugin for Rails applications that allows for custom tagging along dynamic contexts.
* [react-native-config/react-native-config](https://github.com/react-native-config/react-native-config) - Bring some 12 factor love to your mobile apps!
* [github/explore](https://github.com/github/explore) - Community-curated topic and collection pages on GitHub
* [bbc/wraith](https://github.com/bbc/wraith) - Wraith — A responsive screenshot comparison tool *(archived)*
* [lolcommits/lolcommits](https://github.com/lolcommits/lolcommits) - :camera: git-based selfies for software developers
* [ankane/blazer](https://github.com/ankane/blazer) - Business intelligence made simple
* [SteveLTN/https-portal](https://github.com/SteveLTN/https-portal) - A fully automated HTTPS server powered by Nginx, Let's Encrypt and Docker.
* [nomad-cli/shenzhen](https://github.com/nomad-cli/shenzhen) - CLI for Building & Distributing iOS Apps (.ipa Files) *(archived)*
* [activemerchant/active_merchant](https://github.com/activemerchant/active_merchant) - Active Merchant is a simple payment abstraction library extracted from Shopify. The aim of the project is to feel natural to Ruby users and to abstract as many parts as possible away from the user to offer a consistent interface across all supported gateways.
* [basecamp/once-campfire](https://github.com/basecamp/once-campfire) - Super simple group chat, without a subscription
* [ankane/ahoy](https://github.com/ankane/ahoy) - Simple, powerful, first-party analytics for Rails
* [ankane/strong_migrations](https://github.com/ankane/strong_migrations) - Catch unsafe migrations in development
* [rails/jbuilder](https://github.com/rails/jbuilder) - Jbuilder: generate JSON objects with a Builder-style DSL
* [thoughtbot/neat](https://github.com/thoughtbot/neat) - A fluid and flexible grid Sass framework *(archived)*
* [dtan4/terraforming](https://github.com/dtan4/terraforming) - Export existing AWS resources to Terraform style (tf, tfstate) / No longer actively maintained *(archived)*
* [noraj/OSCP-Exam-Report-Template-Markdown](https://github.com/noraj/OSCP-Exam-Report-Template-Markdown) - :orange_book: Markdown Templates for Offensive Security OSCP, OSWE, OSCE, OSEE, OSWP exam report
* [flyerhzm/rails_best_practices](https://github.com/flyerhzm/rails_best_practices) - a code metric tool for rails projects
* [zdennis/activerecord-import](https://github.com/zdennis/activerecord-import) - A library for bulk insertion of data into your database using ActiveRecord.
* [typhoeus/typhoeus](https://github.com/typhoeus/typhoeus) - Typhoeus wraps libcurl in order to make fast and reliable requests.
* [voormedia/rails-erd](https://github.com/voormedia/rails-erd) - Generate Entity-Relationship Diagrams for Rails applications
* [thoughtbot/suspenders](https://github.com/thoughtbot/suspenders) - A Rails application template with our standard defaults, optimized for deployment on Heroku.
* [xcpretty/xcpretty](https://github.com/xcpretty/xcpretty) - Flexible and fast xcodebuild formatter
* [kneath/kss](https://github.com/kneath/kss) - A methodology for documenting CSS and generating styleguides.
* [sds/overcommit](https://github.com/sds/overcommit) - A fully configurable and extendable Git hook manager
* [iberianpig/fusuma](https://github.com/iberianpig/fusuma) - Multitouch gestures with libinput driver on Linux
* [citation-style-language/styles](https://github.com/citation-style-language/styles) - Official repository for Citation Style Language (CSL) citation styles.
* [ankane/groupdate](https://github.com/ankane/groupdate) - The simplest way to group temporal data
* [stefankroes/ancestry](https://github.com/stefankroes/ancestry) - Organise ActiveRecord model into a tree structure
* [ryanb/letter_opener](https://github.com/ryanb/letter_opener) - Preview mail in the browser instead of sending.
* [haml/haml](https://github.com/haml/haml) - HTML Abstraction Markup Language - A Markup Haiku
* [fnando/i18n-js](https://github.com/fnando/i18n-js) - It's a small library to provide the I18n translations on the Javascript. It comes with Rails support.
* [defunkt/gist](https://github.com/defunkt/gist) - Potentially the best command line gister.
* [feedbin/feedbin](https://github.com/feedbin/feedbin) - A nice place to read on the web.
* [openblockchains/awesome-blockchains](https://github.com/openblockchains/awesome-blockchains) - A collection about awesome blockchains - open distributed public databases w/ crypto hashes incl. git ;-). Blockchains are the new tulips :tulip::tulip::tulip:. Distributed is the new centralized.
* [trogdoro/xiki](https://github.com/trogdoro/xiki) - A shell console with GUI features
* [laserlemon/figaro](https://github.com/laserlemon/figaro) - Simple Rails app configuration
* [sds/scss-lint](https://github.com/sds/scss-lint) - Configurable tool for writing clean, consistent SCSS
* [hpyhacking/peatio](https://github.com/hpyhacking/peatio) - An open-source assets exchange.
* [roidrage/lograge](https://github.com/roidrage/lograge) - An attempt to tame Rails' default policy to log everything.
* [lynndylanhurley/devise_token_auth](https://github.com/lynndylanhurley/devise_token_auth) - Token based authentication for Rails JSON APIs. Designed to work with jToker and ng-token-auth.
* [EugenMayer/docker-sync](https://github.com/EugenMayer/docker-sync) - Run your application at full speed while syncing your code for development, finally empowering you to utilize docker for development under OSX/Windows/*Linux
* [ytti/oxidized](https://github.com/ytti/oxidized) - Oxidized is a network device configuration backup tool. It's a RANCID replacement!
* [livoras/blog](https://github.com/livoras/blog) - Too young, too simple. Sometimes, naive.
* [ankane/pgsync](https://github.com/ankane/pgsync) - Sync data from one Postgres database to another
* [collectiveidea/interactor](https://github.com/collectiveidea/interactor) - Interactor provides a common interface for performing complex user interactions.
* [in3rsha/sha256-animation](https://github.com/in3rsha/sha256-animation) - Animation of the SHA-256 hash function in your terminal.
* [oa414/objc-zen-book-cn](https://github.com/oa414/objc-zen-book-cn) - ObjC Zen Book 中文翻译
* [sketchplugins/plugin-directory](https://github.com/sketchplugins/plugin-directory) - Official Sketch Plugin directory
* [endoflife-date/endoflife.date](https://github.com/endoflife-date/endoflife.date) - Informative site with EoL dates of everything
* [RailsApps/rails-composer](https://github.com/RailsApps/rails-composer) - Rails Composer. The Rails generator on steroids for starter apps.
* [plusjade/jekyll-bootstrap](https://github.com/plusjade/jekyll-bootstrap) - The quickest way to start and publish your Jekyll powered blog. 100% compatible with GitHub pages. *(archived)*
* [FontCustom/fontcustom](https://github.com/FontCustom/fontcustom) - Generate custom icon webfonts from the comfort of the command line.
* [soffes/sstoolkit](https://github.com/soffes/sstoolkit) - A collection of well-documented iOS classes for making life easier *(archived)*
* [thoughtbot/high_voltage](https://github.com/thoughtbot/high_voltage) - Easily include static pages in your Rails app.
* [theswiftdev/awesome-xcode-extensions](https://github.com/theswiftdev/awesome-xcode-extensions) - Awesome native Xcode extensions.
* [RolifyCommunity/rolify](https://github.com/RolifyCommunity/rolify) - Role management library with resource scoping
* [apigy/selfstarter](https://github.com/apigy/selfstarter) - Roll your own crowdfunding
* [defunkt/dotjs](https://github.com/defunkt/dotjs) - ~/.js
* [thoughtbot/factory_bot_rails](https://github.com/thoughtbot/factory_bot_rails) - Factory Bot ♥ Rails
* [collabnix/kubelabs](https://github.com/collabnix/kubelabs) - Get Started with Kubernetes
* [gazay/gon](https://github.com/gazay/gon) - Your Rails variables in your JS
* [inspec/inspec](https://github.com/inspec/inspec) - InSpec: Auditing and Testing Framework
* [igrigorik/gharchive.org](https://github.com/igrigorik/gharchive.org) - GH Archive is a project to record the public GitHub timeline, archive it, and make it easily accessible for further analysis.
* [nathanvda/cocoon](https://github.com/nathanvda/cocoon) - Dynamic nested forms using jQuery made easy; works with formtastic, simple_form or default forms
* [zombocom/derailed_benchmarks](https://github.com/zombocom/derailed_benchmarks) - Go faster, off the Rails - Benchmarks for your whole Rails app
* [eddiezane/lunchy](https://github.com/eddiezane/lunchy) - A friendly wrapper for launchctl
* [JXA-Cookbook/JXA-Cookbook](https://github.com/JXA-Cookbook/JXA-Cookbook) - Cookbook for JavaScript for Automation in Mac OS X Yosemite
* [w181496/Web-CTF-Cheatsheet](https://github.com/w181496/Web-CTF-Cheatsheet) - Web CTF CheatSheet 🐈
* [curtis0x/fake-s3](https://github.com/curtis0x/fake-s3) - A lightweight server clone of Amazon S3 that simulates most of the commands supported by S3 with minimal dependencies *(archived)*
* [d12frosted/homebrew-emacs-plus](https://github.com/d12frosted/homebrew-emacs-plus) - Emacs Plus formulae for the Homebrew package manager
* [CanineHQ/canine](https://github.com/CanineHQ/canine) - A developer friendly PaaS for your Kubernetes
* [onetimesecret/onetimesecret](https://github.com/onetimesecret/onetimesecret) - Keep passwords and other sensitive information out of your chat logs and inboxes.
* [rubysherpas/paranoia](https://github.com/rubysherpas/paranoia) - acts_as_paranoid for Rails 5, 6 and 7
* [zmoazeni/csscss](https://github.com/zmoazeni/csscss) - A CSS redundancy analyzer that analyzes redundancy. *(archived)*
* [roo-rb/roo](https://github.com/roo-rb/roo) - Roo provides an interface to spreadsheets of several sorts.
* [shivammathur/homebrew-php](https://github.com/shivammathur/homebrew-php) - Homebrew tap for PHP 5.6 to 8.6. PHP 8.6 is built nightly :beer:
* [sensu/sensu](https://github.com/sensu/sensu) - Monitoring for today's infrastructure. *(archived)*
* [dotless-de/vagrant-vbguest](https://github.com/dotless-de/vagrant-vbguest) - A Vagrant plugin to keep your VirtualBox Guest Additions up to date *(archived)*
* [minimagick/minimagick](https://github.com/minimagick/minimagick) - mini replacement for RMagick
* [zombocom/wicked](https://github.com/zombocom/wicked) - Use wicked to turn your controller into a wizard
* [rails/spring](https://github.com/rails/spring) - Rails application preloader
* [digininja/CeWL](https://github.com/digininja/CeWL) - CeWL is a Custom Word List Generator
* [activeadmin/inherited_resources](https://github.com/activeadmin/inherited_resources)
* [splitrb/split](https://github.com/splitrb/split) - :chart_with_upwards_trend: The Rack Based A/B testing framework
* [excid3/noticed](https://github.com/excid3/noticed) - Notifications for Ruby on Rails applications
* [buo/homebrew-cask-upgrade](https://github.com/buo/homebrew-cask-upgrade) - A command line tool for upgrading every outdated app installed by Homebrew Cask
* [play/play](https://github.com/play/play) - play ► — your company's dj *(archived)*
* [influitive/apartment](https://github.com/influitive/apartment) - Database multi-tenancy for Rack (and Rails) applications
* [prontolabs/pronto](https://github.com/prontolabs/pronto) - Quick automated code review of your changes
* [objc-zen/objc-zen-book](https://github.com/objc-zen/objc-zen-book) - Zen and the Art of the Objective-C Craftsmanship
* [Netflix-Skunkworks/Scumblr](https://github.com/Netflix-Skunkworks/Scumblr) - Web framework that allows performing periodic syncs of data sources and performing analysis on the identified results
* [X140Yu/Developing_iOS_8_Apps_With_Swift](https://github.com/X140Yu/Developing_iOS_8_Apps_With_Swift) - Stanford 公开课，Developing iOS 8 Apps with Swift 字幕翻译
* [randym/axlsx](https://github.com/randym/axlsx) - xlsx generation with charts, images, automated column width, customizable styles and full schema validation. Axlsx excels at helping you generate beautiful Office Open XML Spreadsheet documents without having to understand the entire ECMA specification. Check out the README for some examples of how easy it is. Best of all, you can validate your xlsx file before serialization so you know for sure that anything generated is going to load on your client's machine.
* [nomad-cli/cupertino](https://github.com/nomad-cli/cupertino) - CLI for the Apple Dev Center *(archived)*
* [pluralsight/git-internals-pdf](https://github.com/pluralsight/git-internals-pdf) - PDF on Git Internals *(archived)*
* [pickhardt/betty](https://github.com/pickhardt/betty) - Friendly English-like interface for your command line. Don't remember a command? Ask Betty.
* [xcpretty/xcode-install](https://github.com/xcpretty/xcode-install) - 🔽 Install and update your Xcodes
* [loomio/loomio](https://github.com/loomio/loomio) - Loomio is a collaborative decision making tool
* [aanand/git-up](https://github.com/aanand/git-up) - NOT MAINTAINED
* [mitchellh/vagrant-aws](https://github.com/mitchellh/vagrant-aws) - Use Vagrant to manage your EC2 and VPC instances. *(archived)*
* [boxen/our-boxen](https://github.com/boxen/our-boxen) - Copy me for your team. *(archived)*
* [piotrmurach/tty](https://github.com/piotrmurach/tty) - Toolkit for developing sleek command line apps.
* [mizzy/serverspec](https://github.com/mizzy/serverspec) - RSpec tests for your servers configured by CFEngine, Puppet, Chef, Ansible, Itamae or anything else even by hand
* [lisamelton/video_transcoding](https://github.com/lisamelton/video_transcoding) - Tools to transcode, inspect and convert videos.
* [wardencommunity/warden](https://github.com/wardencommunity/warden) - General Rack Authentication Framework
* [chromebrew/chromebrew](https://github.com/chromebrew/chromebrew) - Package manager for Chrome OS
* [lg/murder](https://github.com/lg/murder) - Large scale server deploys using BitTorrent and the BitTornado library (NOTE: project no longer maintained) *(archived)*
* [lucasgomide/videos-pt.br-tecnologia](https://github.com/lucasgomide/videos-pt.br-tecnologia) - Repositório de canais no Youtube BR sobre desenvolvimento
* [rails/solid_queue](https://github.com/rails/solid_queue) - Database-backed Active Job backend
* [trailblazer/reform](https://github.com/trailblazer/reform) - Form objects decoupled from models.
* [teampoltergeist/poltergeist](https://github.com/teampoltergeist/poltergeist) - A PhantomJS driver for Capybara *(archived)*
* [helpyio/helpy](https://github.com/helpyio/helpy) - Helpy is a modern, open source helpdesk customer support application. Features include knowledgebase, community discussions and support tickets integrated with email.
* [lukes/ISO-3166-Countries-with-Regional-Codes](https://github.com/lukes/ISO-3166-Countries-with-Regional-Codes) - ISO 3166-1 country lists merged with their UN Geoscheme regional codes in ready-to-use JSON, XML, CSV data sets
* [TrashUwU/PokeAssistant](https://github.com/TrashUwU/PokeAssistant) - Amazing Free Pokétwo Assistant that identifies Pokémons from Pokétwo spawns, pings a role if a legendary spawns and pins them, pings you if your Shiny Hunt Pokémon spawns and other features like Quest Ping! Every features are automated. *(archived)*
* [technicalpickles/homesick](https://github.com/technicalpickles/homesick) - Your home directory is your castle. Don't leave your dotfiles behind.
* [sharetribe/sharetribe](https://github.com/sharetribe/sharetribe) - Sharetribe Go is Sharetribe's old source-available marketplace software, which was also available as a hosted SaaS product. Sharetribe Go is no longer actively maintained.
* [gravityblast/web-app-theme](https://github.com/gravityblast/web-app-theme) - A simple theme for web apps
* [jhawthorn/discard](https://github.com/jhawthorn/discard) - 🃏🗑 Soft deletes for ActiveRecord done right
* [collectiveidea/awesome_nested_set](https://github.com/collectiveidea/awesome_nested_set) - An awesome replacement for acts_as_nested_set and better_nested_set.
* [remi/teamocil](https://github.com/remi/teamocil) - There's no I in Teamocil. At least not where you think. Teamocil is a simple tool used to automatically create windows and panes in tmux with YAML files.
* [activerecord-hackery/squeel](https://github.com/activerecord-hackery/squeel) - Active Record, improved. Live again :) *(archived)*
* [david942j/one_gadget](https://github.com/david942j/one_gadget) - The best tool for finding one gadget RCE in libc.so.6
* [gjtorikian/html-pipeline](https://github.com/gjtorikian/html-pipeline) - HTML processing filters and utilities
* [JSONAPI-Resources/jsonapi-resources](https://github.com/JSONAPI-Resources/jsonapi-resources) - A resource-focused Rails library for developing JSON:API compliant servers.
* [locomotivecms/engine](https://github.com/locomotivecms/engine) - A platform to create, publish and edit sites
* [apple/homebrew-apple](https://github.com/apple/homebrew-apple)
* [pay-rails/pay](https://github.com/pay-rails/pay) - Payments for Ruby on Rails apps
* [wvanbergen/request-log-analyzer](https://github.com/wvanbergen/request-log-analyzer) - Create reports based on your log files. Supports Rails, Apache, MySQL, Delayed::Job, and other formats. *(archived)*
* [galetahub/ckeditor](https://github.com/galetahub/ckeditor) - Ckeditor 4.x integration gem for rails
* [orbitalindex/awesome-space](https://github.com/orbitalindex/awesome-space) - 🛰️🚀A list of awesome space-related packages and resources maintained by The Orbital Index
* [Linuxbrew/legacy-linuxbrew](https://github.com/Linuxbrew/legacy-linuxbrew) - :skull: This repository is defunct, because it has been split into https://github.com/Linuxbrew/brew and https://github.com/Linuxbrew/homebrew-core *(archived)*
* [otwcode/otwarchive](https://github.com/otwcode/otwarchive) - The Organization for Transformative Works (OTW) - Archive Of Our Own (AO3) Project
* [thoughtbot/shoulda](https://github.com/thoughtbot/shoulda) - Makes tests easy on the fingers and the eyes
* [rswag/rswag](https://github.com/rswag/rswag) - Seamlessly adds a Swagger to Rails-based API's
* [LionSec/xerosploit](https://github.com/LionSec/xerosploit) - Efficient and advanced man in the middle framework
* [NatLabRockies/api-umbrella](https://github.com/NatLabRockies/api-umbrella) - Open source API management platform
* [logstash-plugins/logstash-patterns-core](https://github.com/logstash-plugins/logstash-patterns-core)
* [tobi/delayed_job](https://github.com/tobi/delayed_job) - Database backed asynchronous priority queue -- Extracted from Shopify
* [adamcooke/staytus](https://github.com/adamcooke/staytus) - 💡 An open source solution for publishing the status of your services
* [trulia/hologram](https://github.com/trulia/hologram) - A markdown based documentation system for style guides.
* [motor-admin/motor-admin](https://github.com/motor-admin/motor-admin) - Deploy a no-code admin panel for any application in less than a minute. Search, create, update, and delete data entries, create custom actions, and build reports.
* [globalize/globalize](https://github.com/globalize/globalize) - Rails I18n de-facto standard library for ActiveRecord model/data translation.
* [manyfold3d/manyfold](https://github.com/manyfold3d/manyfold) - A self-hosted digital asset manager for 3d print files.
* [stephencelis/ghi](https://github.com/stephencelis/ghi) - GitHub Issues on the command line. Use your $EDITOR, not your browser. *(archived)*
* [plamoni/SiriProxy](https://github.com/plamoni/SiriProxy) - A (tampering) proxy server for Apple's Siri *(archived)*
* [feedjira/feedjira](https://github.com/feedjira/feedjira) - A feed parsing library
* [codekitchen/dinghy](https://github.com/codekitchen/dinghy) - faster, friendlier Docker on OS X. Deprecated. *(archived)*
* [pluosi/app-host](https://github.com/pluosi/app-host) - 应用内网发布 | iOS OTA (Over-the-Air) | APP publish website like fir.im | 适用于企业 iOS & Android 内网发布测试使用，方便管理和分发 APP 包
* [ankane/dexter](https://github.com/ankane/dexter) - The automatic indexer for Postgres
* [CombineCommunity/rxswift-to-combine-cheatsheet](https://github.com/CombineCommunity/rxswift-to-combine-cheatsheet) - RxSwift to Apple’s Combine Cheat Sheet
* [interagent/prmd](https://github.com/interagent/prmd) - JSON Schema tools and doc generation for HTTP APIs
* [mislav/git-deploy](https://github.com/mislav/git-deploy) - git deployment made easy *(archived)*
* [brendon/acts_as_list](https://github.com/brendon/acts_as_list) - An ActiveRecord plugin for managing lists.
* [cloudfoundry/bosh](https://github.com/cloudfoundry/bosh) - Cloud Foundry BOSH is an open source tool chain for release engineering, deployment and lifecycle management of large scale distributed services.
* [greasyfork-org/greasyfork](https://github.com/greasyfork-org/greasyfork) - An online repository of user scripts.
* [syxanash/awesome-web-desktops](https://github.com/syxanash/awesome-web-desktops) - Websites, web apps, portfolios that look like desktop operating systems
* [fastlane/ci](https://github.com/fastlane/ci) - Open source, self hosted, mobile optimized CI powered by fastlane *(archived)*
* [airbnb/synapse](https://github.com/airbnb/synapse) - A transparent service discovery framework for connecting an SOA
* [nsarno/knock](https://github.com/nsarno/knock) - Seamless JWT authentication for Rails API *(archived)*
* [dblock/fui](https://github.com/dblock/fui) - Find unused Objective-C imports.
* [ruboto/ruboto](https://github.com/ruboto/ruboto) - A platform for developing apps using JRuby on Android.
* [attr-encrypted/attr_encrypted](https://github.com/attr-encrypted/attr_encrypted) - Generates attr_accessors that encrypt and decrypt attributes
* [junegunn/redis-stat](https://github.com/junegunn/redis-stat) - (UNMAINTAINED) A real-time Redis monitoring tool
* [brotandgames/ciao](https://github.com/brotandgames/ciao) - HTTP checks & tests (private & public) monitoring - check the status of your URL
* [Shopify/identity_cache](https://github.com/Shopify/identity_cache) - IdentityCache is a blob level caching solution to plug into Active Record. Don't #find, #fetch!
* [ryanb/nifty-generators](https://github.com/ryanb/nifty-generators) - A collection of useful Rails generator scripts. *(archived)*
* [guard/listen](https://github.com/guard/listen) - The Listen gem listens to file modifications and notifies you about the changes.
* [illacceptanything/illacceptanything](https://github.com/illacceptanything/illacceptanything) - The project where literally anything* goes.
* [thoughtbot/gitsh](https://github.com/thoughtbot/gitsh) - An interactive shell for git
* [thoughtbot/capybara-webkit](https://github.com/thoughtbot/capybara-webkit) - A Capybara driver for headless WebKit to test JavaScript web apps *(archived)*
* [lewagon/data-setup](https://github.com/lewagon/data-setup) - Setup instructions for Le Wagon's students on their first day of Data Science Bootcamp
* [Shopify/shopify_app](https://github.com/Shopify/shopify_app) - A Rails Engine for building Shopify Apps
* [yob/pdf-reader](https://github.com/yob/pdf-reader) - The PDF::Reader library implements a PDF parser conforming as much as possible to the PDF specification from Adobe.
* [will/slacktyping](https://github.com/will/slacktyping) - i'm typing when you're typing
* [openjournals/joss](https://github.com/openjournals/joss) - The Journal of Open Source Software
* [maid/maid](https://github.com/maid/maid) - Be lazy. Let Maid clean up after you, based on rules you define. Think of it as "Hazel for hackers".
* [gocardless/statesman](https://github.com/gocardless/statesman) - A statesmanlike state machine library.
* [Shopify/packwerk](https://github.com/Shopify/packwerk) - Good things come in small packages.
* [charkost/prosopite](https://github.com/charkost/prosopite) - Rails N+1 queries auto-detection with zero false positives / false negatives
* [RoseSecurity/Red-Teaming-TTPs](https://github.com/RoseSecurity/Red-Teaming-TTPs) - Useful Techniques, Tactics, and Procedures for red teamers and defenders, alike!
* [AssetSync/asset_sync](https://github.com/AssetSync/asset_sync) - Synchronises Assets between Rails and S3
* [github/github-services](https://github.com/github/github-services) - Legacy GitHub Services Integration *(archived)*
* [RubyMoney/money-rails](https://github.com/RubyMoney/money-rails) - Integration of RubyMoney - Money with Rails
* [etsy/deployinator](https://github.com/etsy/deployinator) - Deployinate! *(archived)*
* [soundcloud/lhm](https://github.com/soundcloud/lhm) - Online MySQL schema migrations *(archived)*
* [redbooth/teambox](https://github.com/redbooth/teambox) - This is the legacy version of Teambox - the award-winning collaboration solution, inspired by Basecamp, Yammer and Twitter. *(archived)*
* [trailblazer/roar](https://github.com/trailblazer/roar) - Parse and render REST API documents using representers.
* [raganwald-deprecated/homoiconic](https://github.com/raganwald-deprecated/homoiconic) - An experiment in publishing code and words about code on a small scale.
* [github/india](https://github.com/github/india) - GitHub resources and information for the developer community in India
* [sinclairtarget/um](https://github.com/sinclairtarget/um) - Create and maintain your own man pages so you can remember how to do stuff
* [strongself/Generamba](https://github.com/strongself/Generamba) - This codegenerator is too brilliant to be real!
* [snibox/snibox](https://github.com/snibox/snibox) - Self-hosted snippet manager
* [AdoptOpenJDK/homebrew-openjdk](https://github.com/AdoptOpenJDK/homebrew-openjdk) - AdoptOpenJDK HomeBrew Tap *(archived)*
* [enjoiz/XXEinjector](https://github.com/enjoiz/XXEinjector) - Tool for automatic exploitation of XXE vulnerability using direct and different out of band methods.
* [hashrocket/decent_exposure](https://github.com/hashrocket/decent_exposure) - A helper for creating declarative interfaces in controllers
* [calabash/calabash-ios](https://github.com/calabash/calabash-ios) - Calabash for iOS
* [ryanb/nested_form](https://github.com/ryanb/nested_form) - Rails plugin to conveniently handle multiple models in a single form. *(archived)*
* [basecamp/marginalia](https://github.com/basecamp/marginalia) - Attach comments to ActiveRecord's SQL queries
* [railwaycat/homebrew-emacsmacport](https://github.com/railwaycat/homebrew-emacsmacport) - Emacs mac port formulae for the Homebrew package manager
* [alan-ai/alan-sdk-flutter](https://github.com/alan-ai/alan-sdk-flutter) - The Self-Coding System for Your App — Alan AI SDK for Flutter
* [newrelic/centurion](https://github.com/newrelic/centurion) - A mass deployment tool for Docker fleets *(archived)*
* [philhagen/sof-elk](https://github.com/philhagen/sof-elk) - Configuration files for the SOF-ELK VM
* [octopress/octopress](https://github.com/octopress/octopress) - Octopress 3.0 – Jekyll's Ferrari
* [resque/resque-scheduler](https://github.com/resque/resque-scheduler) - A light-weight job scheduling system built on top of Resque
* [openfarmcc/OpenFarm](https://github.com/openfarmcc/OpenFarm) - A free and open database for farming and gardening knowledge. You can grow anything! *(archived)*
* [heartcombo/has_scope](https://github.com/heartcombo/has_scope) - Map incoming controller parameters to named scopes in your resources
* [jekyll/jekyll-seo-tag](https://github.com/jekyll/jekyll-seo-tag) - A Jekyll plugin to add metadata tags for search engines and social networks to better index and display your site's content.
* [iridakos/duckrails](https://github.com/iridakos/duckrails) - Development tool to mock API endpoints quickly and easily - NOT MAINTAINED *(archived)*
* [devopsgroup-io/vagrant-digitalocean](https://github.com/devopsgroup-io/vagrant-digitalocean) - :droplet: A Vagrant provider plugin that manages DigitalOcean droplets.
* [ErwinM/acts_as_tenant](https://github.com/ErwinM/acts_as_tenant) - Easy multi-tenancy for Rails in a shared database setup.
* [railsware/js-routes](https://github.com/railsware/js-routes) - Brings Rails named routes to javascript
* [cldwalker/hirb](https://github.com/cldwalker/hirb) - A mini view framework for console/irb that's easy to use, even while under its influence. Console goodies include a no-wrap table, auto-pager, tree and menu.
* [igrigorik/em-websocket](https://github.com/igrigorik/em-websocket) - EventMachine based WebSocket server
* [stevegraham/slanger](https://github.com/stevegraham/slanger) - Open Pusher implementation compatible with Pusher libraries *(archived)*
* [palkan/logidze](https://github.com/palkan/logidze) - Database changes log for Rails
* [calabash/calabash-android](https://github.com/calabash/calabash-android) - Automated Functional testing for Android using cucumber
* [radiant/radiant](https://github.com/radiant/radiant) - Radiant is a no-fluff, open source content management system designed for small teams.
* [salsify/goldiloader](https://github.com/salsify/goldiloader) - Just the right amount of Rails eager loading
* [asmuth/recommendify](https://github.com/asmuth/recommendify) - Generate recommendations using collaborative filtering
* [contribsys/einhorn](https://github.com/contribsys/einhorn) - Einhorn: the language-independent shared socket manager
* [adrianmihalko/ch340g-ch34g-ch34x-mac-os-x-driver](https://github.com/adrianmihalko/ch340g-ch34g-ch34x-mac-os-x-driver) - CH340G CH34G CH34X Mac OS X driver
* [dennisreimann/ioctocat](https://github.com/dennisreimann/ioctocat) - iOctocat v1 - GitHub for iOS (works on the iPhone, iPad, and iPod Touch) *(archived)*
* [mailboxer/mailboxer](https://github.com/mailboxer/mailboxer) - A Rails gem to send messages inside a web application
* [geokit/geokit](https://github.com/geokit/geokit) - Official Geokit Gem. Geokit gem provides geocoding and distance/heading calculations. Pair with the geokit-rails plugin for full-fledged location-based app functionality.
* [guipdutra/awesome-geek-podcasts](https://github.com/guipdutra/awesome-geek-podcasts) - A curated list of podcasts we like to listen to.
* [mlandauer/cuttlefish](https://github.com/mlandauer/cuttlefish) - Transactional email server with a lovely web interface
* [zed-0xff/zsteg](https://github.com/zed-0xff/zsteg) - detect stegano-hidden data in PNG & BMP
* [tenex/rails-assets](https://github.com/tenex/rails-assets) - The solution to assets management in Rails
* [adzap/validates_timeliness](https://github.com/adzap/validates_timeliness) - Date and time validation plugin for ActiveModel and Rails. Supports multiple ORMs and allows custom date/time formats.
* [stripe-archive/mosql](https://github.com/stripe-archive/mosql) - MongoDB → PostgreSQL streaming replication *(archived)*
* [chriskite/anemone](https://github.com/chriskite/anemone) - Anemone web-spider framework
* [liftoffcli/liftoff](https://github.com/liftoffcli/liftoff) - CLI for creating and configuring new Xcode projects *(archived)*
* [codebrew/backbone-rails](https://github.com/codebrew/backbone-rails) - Easily use backbone.js with rails 3.1
* [SlatherOrg/slather](https://github.com/SlatherOrg/slather) - Generate test coverage reports for Xcode projects & hook it into CI.
* [elastic/ansible-elasticsearch](https://github.com/elastic/ansible-elasticsearch) - Ansible playbook for Elasticsearch *(archived)*
* [rails/tailwindcss-rails](https://github.com/rails/tailwindcss-rails)
* [geokit/geokit-rails](https://github.com/geokit/geokit-rails) - Official Geokit plugin for Rails/ActiveRecord. Provides location-based goodness for your Rails app. Requires the Geokit gem.
* [vdaubry/github-awards](https://github.com/vdaubry/github-awards) - Discover your ranking on github :
* [ffaker/ffaker](https://github.com/ffaker/ffaker) - Faker refactored.
* [boxen/boxen](https://github.com/boxen/boxen) - Manage Mac development boxes with love (and Puppet). *(archived)*
* [piotrmurach/tty-prompt](https://github.com/piotrmurach/tty-prompt) - A beautiful and powerful interactive command line prompt
* [technoweenie/restful-authentication](https://github.com/technoweenie/restful-authentication) - inactive project *(archived)*
* [steelThread/redmon](https://github.com/steelThread/redmon) - A web interface for managing redis: cli, admin, and live monitoring
* [ilyakatz/data-migrate](https://github.com/ilyakatz/data-migrate) - Migrate and update data alongside your database structure.
* [rubysherpas/forem](https://github.com/rubysherpas/forem) - The best Rails 3 and Rails 4 forum engine. Ever.
* [haileys/rustboot](https://github.com/haileys/rustboot) - A tiny 32 bit kernel written in Rust
* [orta/cocoapods-keys](https://github.com/orta/cocoapods-keys) - A key value store for storing per-developer environment and application keys
* [tute/merit](https://github.com/tute/merit) - Reputation engine for Rails apps
* [ryanto/acts_as_votable](https://github.com/ryanto/acts_as_votable) - Votable ActiveRecord for Rails
* [indirect/rails-footnotes](https://github.com/indirect/rails-footnotes) - Every Rails page has footnotes that gives information about your application and links back to your editor
* [samg/timetrap](https://github.com/samg/timetrap) - Simple command line timetracker
* [ActsAsParanoid/acts_as_paranoid](https://github.com/ActsAsParanoid/acts_as_paranoid) - ActiveRecord plugin allowing you to hide and restore records without actually deleting them.
* [steveklabnik/request_store](https://github.com/steveklabnik/request_store) - Per-request global storage for Rack.
* [usbarmory/usbarmory](https://github.com/usbarmory/usbarmory) - USB armory - The open source compact secure computer
* [cloudhead/toto](https://github.com/cloudhead/toto) - the 10 second blog-engine for hackers
* [Shopify/shipit-engine](https://github.com/Shopify/shipit-engine) - Deployment coordination
* [senchalabs/jsduck](https://github.com/senchalabs/jsduck) - Simple JavaScript Duckumentation generator.
* [defunkt/unicorn](https://github.com/defunkt/unicorn) - Unofficial Unicorn Mirror.
* [technicalpickles/jeweler](https://github.com/technicalpickles/jeweler) - Opinionated tool for creating and managing Rubygem projects
* [GeorgeKaraszi/ActiveRecordExtended](https://github.com/GeorgeKaraszi/ActiveRecordExtended) - Adds additional postgres functionality to an ActiveRecord / Rails application
* [devopsgroup-io/vagrant-hostmanager](https://github.com/devopsgroup-io/vagrant-hostmanager) - :pencil: A Vagrant plugin that manages hosts files within a multi-machine environment.
* [urbanadventurer/username-anarchy](https://github.com/urbanadventurer/username-anarchy) - Username tools for penetration testing
* [oldmoe/litestack](https://github.com/oldmoe/litestack)
* [rubber/rubber](https://github.com/rubber/rubber) - A capistrano/rails plugin that makes it easy to deploy/manage/scale to various service providers, including EC2, DigitalOcean, vSphere, and bare metal servers.
* [rharriso/bower-rails](https://github.com/rharriso/bower-rails) - Bundler-like DSL + rake tasks for Bower on Rails
* [gottfrois/dashing-rails](https://github.com/gottfrois/dashing-rails) - The exceptionally handsome dashboard framework for Rails.
* [noidontdig/gitdown](https://github.com/noidontdig/gitdown) - Don't commit when you're drunk
* [gitlabhq/gitlab-ci](https://github.com/gitlabhq/gitlab-ci) - DEPRECATED - Please use the GitLab.com issue tracker *(archived)*
* [zendesk/samson](https://github.com/zendesk/samson) - Web interface for deployments, with plugin architecture and kubernetes support *(archived)*
* [Shopify/graphql-batch](https://github.com/Shopify/graphql-batch) - A query batching executor for the graphql gem
* [maccman/monocle](https://github.com/maccman/monocle) - Link and news sharing
* [bobthecow/genghis](https://github.com/bobthecow/genghis) - The single-file MongoDB admin app *(archived)*
* [ankane/pretender](https://github.com/ankane/pretender) - Log in as another user in Rails
* [fastlane/examples](https://github.com/fastlane/examples) - 📝 A collection of example fastlane setups
* [Shopify/krane](https://github.com/Shopify/krane) - A command-line tool that helps you ship changes to a Kubernetes namespace and understand the result
* [RailsApps/rails_apps_composer](https://github.com/RailsApps/rails_apps_composer) - A gem with recipes to create Rails application templates for Rails starter apps.
* [rroblak/seed_dump](https://github.com/rroblak/seed_dump) - Rails task to dump your data to db/seeds.rb
* [jewel/clearskies](https://github.com/jewel/clearskies) - Open source btsync clone
* [rtomayko/ronn](https://github.com/rtomayko/ronn) - the opposite of roff
* [evrone/quiet_assets](https://github.com/evrone/quiet_assets) - DEPRECATED: As of sprockets-rails version 3.1.0, used in current versions of rails, this gem is deprecated *(archived)*
* [kmuto/review](https://github.com/kmuto/review) - Re:VIEW is flexible document format/conversion system
* [tybenz/vimdeck](https://github.com/tybenz/vimdeck) - VIM as a presentation tool
* [grobie/soundcloud2000](https://github.com/grobie/soundcloud2000) - A terminal client for https://soundcloud.com *(archived)*
* [rails/activeresource](https://github.com/rails/activeresource) - Connects business objects and REST web services
* [rails/kredis](https://github.com/rails/kredis) - Higher-level data structures built on Redis
* [sous-chefs/docker](https://github.com/sous-chefs/docker) - Development repository for the docker cookbook
* [cypriss/mutations](https://github.com/cypriss/mutations) - Compose your business logic into commands that sanitize and validate input.
* [rubycdp/cuprite](https://github.com/rubycdp/cuprite) - Headless Chrome/Chromium driver for Capybara
* [binarylogic/settingslogic](https://github.com/binarylogic/settingslogic) - A simple and straightforward settings solution that uses an ERB enabled YAML file and a singleton design pattern.
* [chrismccord/render_sync](https://github.com/chrismccord/render_sync) - Real-time Rails Partials
* [binarylogic/searchlogic](https://github.com/binarylogic/searchlogic) - Searchlogic provides object based searching, common named scopes, and other useful tools.
* [sporkrb/spork](https://github.com/sporkrb/spork) - A DRb server for testing frameworks (RSpec / Cucumber currently) that forks before each run to ensure a clean testing state.
* [sdsykes/fastimage](https://github.com/sdsykes/fastimage) - FastImage finds the size or type of an image given its uri by fetching as little as needed
* [TideSec/Mars](https://github.com/TideSec/Mars) - Mars(战神)——资产发现、子域名枚举、C段扫描、资产变更监测、端口变更监测、域名解析变更监测、Awvs扫描、POC检测、web指纹探测、端口指纹探测、CDN探测、操作系统指纹探测、泛解析探测、WAF探测、敏感信息检测等等
* [natew/obtvse](https://github.com/natew/obtvse) - Deprecated: See natew/obtvse2
* [OpnTec/bodyapps-web](https://github.com/OpnTec/bodyapps-web) - Web service and web application components of #bodyapps project
* [prat0318/json_resume](https://github.com/prat0318/json_resume) - Generates pretty HTML, LaTeX, markdown, with biodata feeded as input in JSON
* [eliotsykes/rails-security-checklist](https://github.com/eliotsykes/rails-security-checklist) - :key: Community-driven Rails Security Checklist (see our GitHub Issues for the newest checks that aren't yet in the README)
* [pry/pry-rails](https://github.com/pry/pry-rails) - Rails >= 3 pry initializer
* [thoughtbot/griddler](https://github.com/thoughtbot/griddler) - Simplify receiving email in Rails (deprecated) *(archived)*
* [garybernhardt/selecta](https://github.com/garybernhardt/selecta) - A fuzzy text selector for files and anything else you need to select. Use it from vim, from the command line, or anywhere you can run a shell command.
* [ossf/best-practices-badge](https://github.com/ossf/best-practices-badge) - 🏆Open Source Security Foundation (OpenSSF) Best Practices Badge (formerly Core Infrastructure Initiative (CII) Best Practices Badge)
* [active-hash/active_hash](https://github.com/active-hash/active_hash) - A readonly ActiveRecord-esque base class that lets you use a hash, a Yaml file or a custom file as the datasource
* [heroku/legacy-cli](https://github.com/heroku/legacy-cli) - Heroku CLI *(archived)*
* [maccman/abba](https://github.com/maccman/abba) - A/B testing framework
* [Eric-Guo/wechat](https://github.com/Eric-Guo/wechat) - API, command and message handling for WeChat in Rails
* [emberjs/ember-rails](https://github.com/emberjs/ember-rails) - Ember for Rails 3.1+
* [github/developer.github.com](https://github.com/github/developer.github.com) - GitHub Developer site *(archived)*
* [NationalSecurityAgency/SIMP](https://github.com/NationalSecurityAgency/SIMP) - A system automation and configuration management stack targeted toward operational flexibility and policy compliance. *(archived)*
* [sudara/awesome-juce](https://github.com/sudara/awesome-juce) - A curated list of JUCE modules, templates, plugins, oh my!
* [bokmann/business_time](https://github.com/bokmann/business_time) - Support for doing time math in business hours and days
* [desktoppr/wbench](https://github.com/desktoppr/wbench) - It benchmarks websites, YO!
* [elixir-editors/vim-elixir](https://github.com/elixir-editors/vim-elixir) - Vim configuration files for Elixir
* [guard/guard-rspec](https://github.com/guard/guard-rspec) - Guard::RSpec automatically run your specs (much like autotest)
* [twitter/activerecord-reputation-system](https://github.com/twitter/activerecord-reputation-system) - An Active Record Reputation System for Rails *(archived)*
* [basecamp/mail_view](https://github.com/basecamp/mail_view) - Visual email testing *(archived)*
* [leavez/cocoapods-binary](https://github.com/leavez/cocoapods-binary) - integrate pods in form of prebuilt frameworks conveniently, reducing compile time
* [holman/boom](https://github.com/holman/boom) - Motherfucking TEXT SNIPPETS! On the COMMAND LINE!
* [JoshCheek/seeing_is_believing](https://github.com/JoshCheek/seeing_is_believing) - Displays the results of every line of code in your file
* [chef/omnibus](https://github.com/chef/omnibus) - Easily create full-stack installers for your project across a variety of platforms.
* [matthuhiggins/foreigner](https://github.com/matthuhiggins/foreigner) - Adds foreign key helpers to migrations and correctly dumps foreign keys to schema.rb
* [Shopify/job-iteration](https://github.com/Shopify/job-iteration) - Makes your background jobs interruptible and resumable by design.
* [supermarin/YosemiteSanFranciscoFont](https://github.com/supermarin/YosemiteSanFranciscoFont) - Replace Helvetica Neue on your 10.10 Yosemite Mac with San Francisco – the Watch font. *(archived)*
* [dergachev/screengif](https://github.com/dergachev/screengif) - Create animated gif screencasts.
* [JEG2/highline](https://github.com/JEG2/highline) - A higher level command-line oriented interface.
* [stelligent/cfn_nag](https://github.com/stelligent/cfn_nag) - Linting tool for CloudFormation templates
* [devise-two-factor/devise-two-factor](https://github.com/devise-two-factor/devise-two-factor) - Barebones two-factor authentication with Devise
* [square/cane](https://github.com/square/cane) - Code quality threshold checking as part of your build
* [cloudfoundry-attic/vcap](https://github.com/cloudfoundry-attic/vcap) - Cloud Foundry - the open platform as a service project *(archived)*
* [travis-ci/dpl](https://github.com/travis-ci/dpl) - Dpl (dee-pee-ell) is a deploy tool made for continuous deployment.
* [fluent/fluentd-kubernetes-daemonset](https://github.com/fluent/fluentd-kubernetes-daemonset) - Fluentd daemonset for Kubernetes and it Docker image
* [waiting-for-dev/devise-jwt](https://github.com/waiting-for-dev/devise-jwt) - JWT token authentication with devise and rails
* [ttscoff/doing](https://github.com/ttscoff/doing)
* [asmallteapot/cocoapods-playgrounds](https://github.com/asmallteapot/cocoapods-playgrounds) - :black_joker: Generate Swift Playgrounds for any library. *(archived)*
* [vapor-community/awesome-vapor](https://github.com/vapor-community/awesome-vapor) - A curated list of Vapor-related awesome projects.
* [KrauseFx/FxLifeSheet](https://github.com/KrauseFx/FxLifeSheet) - Tracking the key metrics of my life
* [hahwul/MobileHackersWeapons](https://github.com/hahwul/MobileHackersWeapons) - Mobile Hacker's Weapons / A collection of cool tools used by Mobile hackers. Happy hacking , Happy bug-hunting
* [powder-rb/powder](https://github.com/powder-rb/powder) - Makes Pow even easier. I mean really, really, ridiculously easy
* [rails/globalid](https://github.com/rails/globalid) - Identify app models with a URI
* [davetron5000/gli](https://github.com/davetron5000/gli) - Make awesome command-line applications the easy way
* [mynyml/watchr](https://github.com/mynyml/watchr) - Modern continuous testing (flexible alternative to Autotest)
* [simi/omniauth-facebook](https://github.com/simi/omniauth-facebook) - Facebook OAuth2 Strategy for OmniAuth
* [rails/strong_parameters](https://github.com/rails/strong_parameters) - Taint and required checking for Action Pack and enforcement in Active Model *(archived)*
* [rack/rack-contrib](https://github.com/rack/rack-contrib) - Contributed Rack Middleware and Utilities
* [markets/invisible_captcha](https://github.com/markets/invisible_captcha) - 🍯 Unobtrusive and flexible spam protection for Rails apps
* [pawurb/rails-pg-extras](https://github.com/pawurb/rails-pg-extras) - Rails PostgreSQL database performance insights. Locks, index usage, buffer cache hit ratios, vacuum stats and more.
* [ankane/pgslice](https://github.com/ankane/pgslice) - Postgres partitioning as easy as pie
* [stffn/declarative_authorization](https://github.com/stffn/declarative_authorization) - An unmaintained authorization plugin for Rails. Please fork to support current versions of Rails
* [mbleigh/seed-fu](https://github.com/mbleigh/seed-fu) - Advanced seed data handling for Rails, combining the best practices of several methods together.
* [freshshell/fresh](https://github.com/freshshell/fresh) - Keep your dotfiles fresh.
* [inertiajs/inertia-rails](https://github.com/inertiajs/inertia-rails) - The Rails adapter for Inertia.js.
* [ddollar/heroku-accounts](https://github.com/ddollar/heroku-accounts) - Multiple account management for Heroku
* [mattes/rotating-proxy](https://github.com/mattes/rotating-proxy) - Rotating TOR proxy with Docker
* [soulteary/Home-Network-Note](https://github.com/soulteary/Home-Network-Note) - 🚧 持续更新 🚧 记录搭建兼顾学习娱乐的家用网络环境的过程，折腾过的一些软硬件小经验。
* [brentd/xray-rails](https://github.com/brentd/xray-rails) - ☠️ A development tool that reveals your UI's bones
* [Shopify/roast](https://github.com/Shopify/roast) - Structured AI workflows made easy
* [messense/homebrew-macos-cross-toolchains](https://github.com/messense/homebrew-macos-cross-toolchains) - macOS cross compiler toolchains
* [icalendar/icalendar](https://github.com/icalendar/icalendar) - icalendar.rb main repository
* [brandonhilkert/fucking_shell_scripts](https://github.com/brandonhilkert/fucking_shell_scripts) - The easiest, most common sense configuration management tool... because you just use fucking shell scripts.
* [cgriego/active_attr](https://github.com/cgriego/active_attr) - What ActiveModel left out
* [kostya/eye](https://github.com/kostya/eye) - Process monitoring tool. Inspired from Bluepill and God.
* [ankane/ahoy_email](https://github.com/ankane/ahoy_email) - First-party email analytics for Rails
* [fgrehm/vagrant-lxc](https://github.com/fgrehm/vagrant-lxc) - LXC provider for Vagrant *(archived)*
* [igorkasyanchuk/active_storage_validations](https://github.com/igorkasyanchuk/active_storage_validations) - Do it like => validates :photos, attached: true, content_type: ['image/png', 'image/jpg', 'image/jpeg'], size: { less_than: 500.kilobytes }, limit: { min: 1, max: 3 }, aspect_ratio: :landscape, dimension: { width: { in: 800..1600 }
* [ricardochimal/taps](https://github.com/ricardochimal/taps) - simple database import/export app
* [clacky-ai/openclacky](https://github.com/clacky-ai/openclacky) - The most Token-efficient open-source AI Agent
* [inket/update_xcode_plugins](https://github.com/inket/update_xcode_plugins) - No more messing with plugin UUIDs; Plugins on Xcode 8+! *(archived)*
* [roberdam/Xaddress](https://github.com/roberdam/Xaddress) - Xaddress - Give 7 billion people an instant physical address
* [aanand/deadweight](https://github.com/aanand/deadweight) - NOT MAINTAINED
* [BuffaloWill/oxml_xxe](https://github.com/BuffaloWill/oxml_xxe) - A tool for embedding XXE/XML exploits into different filetypes
* [k1LoW/awspec](https://github.com/k1LoW/awspec) - RSpec tests for your AWS resources.
* [mattprusak/autoresearch-genealogy](https://github.com/mattprusak/autoresearch-genealogy) - Structured prompts, vault templates, and archive guides for AI-assisted genealogy research. Built for Claude Code.
* [browsermedia/browsercms](https://github.com/browsermedia/browsercms) - BrowserCMS: Humane Content Management for Rails
* [noahd1/oink](https://github.com/noahd1/oink) - Log parser to identify actions which significantly increase VM heap size
* [rails/importmap-rails](https://github.com/rails/importmap-rails) - Use ESM with importmap to manage modern JavaScript in Rails without transpiling or bundling.
* [jordansissel/pleaserun](https://github.com/jordansissel/pleaserun) - An attempt to abstract this "init" script madness.
* [librariesio/libraries.io](https://github.com/librariesio/libraries.io) - :books: The Open Source Discovery Service
* [andrewculver/koudoku](https://github.com/andrewculver/koudoku) - Robust subscription support for Rails with Stripe.
* [documentcloud/jammit](https://github.com/documentcloud/jammit) - Industrial Strength Asset Packaging for Rails
* [agiledivider/vagrant-hostsupdater](https://github.com/agiledivider/vagrant-hostsupdater)
* [CocoaPods/cocoapods-packager](https://github.com/CocoaPods/cocoapods-packager) - CocoaPods plugin which allows you to generate a static library from a podspec.
* [petewarden/dstk](https://github.com/petewarden/dstk) - A collection of the best open data sets and open-source tools for data science
* [Telefonica/Eternalblue-Doublepulsar-Metasploit](https://github.com/Telefonica/Eternalblue-Doublepulsar-Metasploit) - Module of Metasploit to exploit the vulnerability Eternalblue-Doublepulsar.
* [james2m/seedbank](https://github.com/james2m/seedbank) - Seedbank gives your seed data a little structure. Create seeds for each environment, share seeds between environments and specify dependencies to load your seeds in order. All nicely integrated with simple rake tasks.
* [cryptosphere/cryptosphere](https://github.com/cryptosphere/cryptosphere) - Encrypted peer-to-peer web application platform for decentralized, privacy-preserving applications *(archived)*
* [sprinkle-tool/sprinkle](https://github.com/sprinkle-tool/sprinkle) - Sprinkle is a software provisioning tool you can use to build remote servers with. eg. to install a Rails, or Sinatra stack on a brand new slice directly after its been created
* [brooklynDev/airborne](https://github.com/brooklynDev/airborne) - RSpec driven API testing framework
* [david942j/seccomp-tools](https://github.com/david942j/seccomp-tools) - Provide powerful tools for seccomp analysis
* [activescaffold/active_scaffold](https://github.com/activescaffold/active_scaffold) - Save time and headaches, and create a more easily maintainable set of pages, with ActiveScaffold. ActiveScaffold handles all your CRUD (create, read, update, delete) user interface needs, leaving you more time to focus on more challenging (and interesting!) problems.
* [RailsApps/rails-stripe-membership-saas](https://github.com/RailsApps/rails-stripe-membership-saas) - An example Rails 4.2 app with Stripe and the Payola gem for a membership or subscription site.
* [alan-ai/alan-sdk-cordova](https://github.com/alan-ai/alan-sdk-cordova) - The Self-Coding System for Your App — Alan AI SDK for Cordova
* [bborn/communityengine](https://github.com/bborn/communityengine) - Adds basic social networking capabilities to your existing application, including users, blogs, photos, clippings, favorites, and more. *(archived)*
* [defunkt/github-gem](https://github.com/defunkt/github-gem) - `github` command line helper for simplifying your GitHub experience.
* [Shopify/cli-ui](https://github.com/Shopify/cli-ui) - CLI tooling framework with simple interactive widgets
* [tumblr/jetpants](https://github.com/tumblr/jetpants) - MySQL toolkit for managing billions of rows and hundreds of database machines
* [huacnlee/rails-settings-cached](https://github.com/huacnlee/rails-settings-cached) - Global settings for your Rails application.
* [ging/social_stream](https://github.com/ging/social_stream) - A framework for building distributed social network websites
* [envygeeks/jekyll-assets](https://github.com/envygeeks/jekyll-assets) - :art: Asset pipelines for Jekyll.
* [jquery-ui-rails/jquery-ui-rails](https://github.com/jquery-ui-rails/jquery-ui-rails) - jQuery UI for the Rails asset pipeline
* [palkan/isolator](https://github.com/palkan/isolator) - Detect non-atomic interactions within DB transactions
* [moneta-rb/moneta](https://github.com/moneta-rb/moneta) - a unified interface to key/value stores
* [fxn/tkn](https://github.com/fxn/tkn) - Terminal Keynote - A hack for terminal-based talks
* [notahat/machinist](https://github.com/notahat/machinist) - Fixtures aren't fun. Machinist is.
* [kciter/awesome-style-guide](https://github.com/kciter/awesome-style-guide) - A list of awesome style guide.
* [passbolt/passbolt_docker](https://github.com/passbolt/passbolt_docker) - Get started with Passbolt CE using docker!
* [tweetstream/tweetstream](https://github.com/tweetstream/tweetstream) - A simple EventMachine-based library for consuming Twitter's Streaming API.
* [jeffreywildman/homebrew-virt-manager](https://github.com/jeffreywildman/homebrew-virt-manager) - A set of homebrew formulae to install virt-manager and virt-viewer on MAC OSX
* [floere/phony](https://github.com/floere/phony) - E164 international phone number normalizing, splitting, formatting.
* [brendon/ranked-model](https://github.com/brendon/ranked-model) - An acts_as_sortable/acts_as_list replacement built for Rails 4+
* [tomgi/git_stats](https://github.com/tomgi/git_stats) - GitStats is a git repository statistics generator.
* [brianmario/charlock_holmes](https://github.com/brianmario/charlock_holmes) - Character encoding detection, brought to you by ICU
* [nickjj/docker-rails-example](https://github.com/nickjj/docker-rails-example) - A production ready example Rails app that's using Docker and Docker Compose.
* [thoughtbot/hotwire-example-template](https://github.com/thoughtbot/hotwire-example-template) - A collection of branches that transmit HTML over the wire.
* [Lightricks/Kintsugi](https://github.com/Lightricks/Kintsugi) - A tool to automatically resolve Git conflicts that occur in Xcode project files
* [brynary/rack-bug](https://github.com/brynary/rack-bug) - Debugging toolbar for Rack applications implemented as middleware
* [CocoaPods/cocoapods-deintegrate](https://github.com/CocoaPods/cocoapods-deintegrate) - A CocoaPods plugin to remove and de-integrate CocoaPods from your project.
* [mattbrictson/rails-template](https://github.com/mattbrictson/rails-template) - My former app template for Rails 7. All recommendations you see here have been moved to https://github.com/mattbrictson/nextgen *(archived)*
* [MeetYouDevs/cocoapods-imy-bin](https://github.com/MeetYouDevs/cocoapods-imy-bin)
* [berkshelf/berkshelf](https://github.com/berkshelf/berkshelf) - A Chef Cookbook manager
* [nikolalsvk/render_async](https://github.com/nikolalsvk/render_async) - render_async lets you include pages asynchronously with AJAX
* [sunaku/tamzen-font](https://github.com/sunaku/tamzen-font) - 💌 Bitmapped programming font, based on Tamsyn
* [amro/gibbon](https://github.com/amro/gibbon) - Gibbon is an API wrapper for MailChimp's API
* [fgrehm/vagrant-cachier](https://github.com/fgrehm/vagrant-cachier) - Caffeine reducer *(archived)*
* [PGYER/fir-cli](https://github.com/PGYER/fir-cli) - fir.im(betaqr.com) command-line interface
* [fakefs/fakefs](https://github.com/fakefs/fakefs) - A fake filesystem. Use it in your tests.
* [rails/mission_control-jobs](https://github.com/rails/mission_control-jobs) - Dashboard and Active Job extensions to operate and troubleshoot background jobs
* [hypriot/image-builder-rpi](https://github.com/hypriot/image-builder-rpi) - SD card image for Raspberry Pi with Docker: HypriotOS *(archived)*
* [iobridge/thingspeak](https://github.com/iobridge/thingspeak) - ThingSpeak is an open source “Internet of Things” application and API to store and retrieve data from things using HTTP over the Internet or via a Local Area Network. With ThingSpeak, you can create sensor logging applications, location tracking applications, and a social network of things with status updates.
* [seatgeek/soulmate](https://github.com/seatgeek/soulmate) - Unmaintained, use Soulheart! *(archived)*
* [Shopify/shopify-cli](https://github.com/Shopify/shopify-cli) - Shopify CLI helps you build against the Shopify platform faster. *(archived)*
* [defunkt/cijoe](https://github.com/defunkt/cijoe) - CI Joe is a fun Continuous Integration server. Unmaintained.
* [haml/haml-rails](https://github.com/haml/haml-rails) - let your Gemfile do the talking
* [radar/by_star](https://github.com/radar/by_star) - Lets you find ActiveRecord + Mongoid objects by year, month, fortnight, week and more!
* [rails/propshaft](https://github.com/rails/propshaft) - Deliver assets for Rails
* [aws/opsworks-cookbooks](https://github.com/aws/opsworks-cookbooks) - Chef Cookbooks for the AWS OpsWorks Service *(archived)*
* [caged/gitnub](https://github.com/caged/gitnub) - A Gitk-like application written in RubyCocoa that looks like it belongs on a Mac. See the wiki for downloads and screenshots.
* [jfirebaugh/konacha](https://github.com/jfirebaugh/konacha) - Test your Rails application's JavaScript with the mocha test framework and chai assertion library
* [romainbutteaud/Kaffeine](https://github.com/romainbutteaud/Kaffeine) - Keeping free Heroku apps awake.
* [rails/solid_cache](https://github.com/rails/solid_cache) - A database-backed ActiveSupport::Cache::Store
* [igrigorik/em-synchrony](https://github.com/igrigorik/em-synchrony) - Fiber aware EventMachine clients and convenience classes
* [k0kubun/md2key](https://github.com/k0kubun/md2key) - Convert markdown to keynote
* [nov/fb_graph](https://github.com/nov/fb_graph) - This gem doesn't support FB Graph API v2.0+. Please use fb_graph2 gem instead.
* [alphagov/whitehall](https://github.com/alphagov/whitehall) - Publishes government content on GOV.UK
* [phusion/juvia](https://github.com/phusion/juvia) - A commenting server similar to Disqus and IntenseDebate. *(archived)*
* [composite-primary-keys/composite_primary_keys](https://github.com/composite-primary-keys/composite_primary_keys) - Composite Primary Keys support for Active Record
* [technoweenie/attachment_fu](https://github.com/technoweenie/attachment_fu) - Treat an ActiveRecord model as a file attachment, storing its patch, size, content type, etc.
* [mattheworiordan/capybara-screenshot](https://github.com/mattheworiordan/capybara-screenshot) - Automatically save screen shots when a Capybara scenario fails
* [GliaX/Stethoscope](https://github.com/GliaX/Stethoscope) - A research-validated stethoscope whose plans are available Freely and openly. The cost of the entire stethoscope is between $2.5 to $5 to produce
* [Parallels/vagrant-parallels](https://github.com/Parallels/vagrant-parallels) - Vagrant Parallels Provider
* [ruby/www.ruby-lang.org](https://github.com/ruby/www.ruby-lang.org) - Source of the https://www.ruby-lang.org website.
* [jekyll/jekyll-redirect-from](https://github.com/jekyll/jekyll-redirect-from) - :twisted_rightwards_arrows: Seamlessly specify multiple redirections URLs for your pages and posts.
* [iain/http_accept_language](https://github.com/iain/http_accept_language) - Ruby on Rails plugin. Fishes out the Accept-Language header into an array.
* [mbulat/plutus](https://github.com/mbulat/plutus) - A Ruby on Rails Engine which provides a double entry accounting system for your application
* [markets/maily](https://github.com/markets/maily) - 📫 Rails Engine to preview emails in the browser
* [excid3/receipts](https://github.com/excid3/receipts) - Easy receipts and invoices for your Ruby on Rails applications
* [palkan/active_delivery](https://github.com/palkan/active_delivery) - Ruby framework for keeping all types of notifications (mailers, push notifications, whatever) in one place
* [railslove/rack-tracker](https://github.com/railslove/rack-tracker) - Tracking made easy: Don’t fool around with adding tracking and analytics partials to your app and concentrate on the things that matter.
* [chrislloyd/gravtastic](https://github.com/chrislloyd/gravtastic) - Add Gravatars to your Rubies/Rails (and now Javascript)! *(archived)*
* [nomad-cli/venice](https://github.com/nomad-cli/venice) - Ruby Gem for In-App Purchase Receipt Verification *(archived)*
* [Sology/maily_herald](https://github.com/Sology/maily_herald) - Advanced email processing solution for Ruby on Rails applications
* [glebm/rails_email_preview](https://github.com/glebm/rails_email_preview) - Preview and edit app mailer templates in Rails.
* [yuki24/rambulance](https://github.com/yuki24/rambulance) - Simple and safe way to dynamically render error pages or JSON responses for Rails apps
* [simukappu/activity_notification](https://github.com/simukappu/activity_notification) - Integrated user activity notifications for Ruby on Rails
* [ulfurinn/wongi-engine](https://github.com/ulfurinn/wongi-engine) - A rule engine written in Ruby.
* [agoragames/leaderboard](https://github.com/agoragames/leaderboard) - Leaderboards backed by Redis in Ruby
* [yeahrb/CEX-Option-Futures-Crypto-Quant-Algorithm-Trading-Bot](https://github.com/yeahrb/CEX-Option-Futures-Crypto-Quant-Algorithm-Trading-Bot) - Ruby video game framework
