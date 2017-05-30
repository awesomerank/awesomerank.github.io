<h1 align="center">
Ranked awesome lists, all in one place
</h1>
<p align="center">
	This list is a copy of <a href="mre/awesome-static-analysis">mre/awesome-static-analysis</a> with ranks
</p>
---
![Logo](https://github.com/mre/awesome-static-analysis/blob/master/awesome.png)

> Static program analysis is the analysis of computer software that is performed without actually executing programs — [Wikipedia](https://en.wikipedia.org/wiki/Static_program_analysis)

This is a collection of static analysis tools and code quality checkers.  
**Note: :copyright: stands for proprietary software. All other tools are Open Source.**  
**Pull requests are very welcome!**

# Table of Contents

- [Programming Languages](#programming-languages)
  - [Ada](#ada)
  - [C/C++](#cc)
  - [C#](#c)
  - [Elixir](#elixir)
  - [Erlang](#erlang)
  - [Go](#go)
  - [Groovy](#groovy)
  - [Haskell](#haskell)
  - [Haxe](#haxe)
  - [Java](#java)
  - [JavaScript](#javascript)
  - [Kotlin](#kotlin)
  - [Lua](#lua)
  - [Perl](#perl)
  - [PHP](#php)
  - [Python](#python)
  - [R](#r)
  - [Ruby](#ruby)
  - [Rust](#rust)
  - [Scala](#scala)
  - [Shell](#shell)
  - [SQL](#sql)
  - [Swift](#swift)
  - [TypeScript](#typescript)
- [Multiple languages](#multiple-languages)
- [Other](#other)
  - [Build tools](#build-tools)
  - [Binaries](#binaries)
  - [Containers](#containers)
  - [Config Files](#config-files)
  - [Configuration Management](#configuration-management)
  - [CSS](#css)
  - [HTML](#html)
  - [Makefiles](#makefiles)
  - [Mobile](#mobile)
  - [Packages](#packages)
  - [Web services](#web-services)
- [More Collections](#more-collections)


# Programming Languages

## Ada

* [Codepeer](http://www.adacore.com/codepeer) - detects run-time and logic errors
* [Polyspace for Ada](https://www.mathworks.com/products/polyspace-ada.html) :copyright: - provide code verification that proves the absence of overflow, divide-by-zero, out-of-bounds array access, and certain other run-time errors in source code.
* [Understand](https://scitools.com/ada-programming-essential/) :copyright: - IDE that provides code analysis, standards testing, metrics, graphing, dependency analysis and more for Ada and VHDL.

## C/C++

* [clang-tidy](http://clang.llvm.org/extra/clang-tidy/) - clang static analyser
* [CMetrics ★17 ⏳2Y](MetricsGrimoire/CMetrics) - Measures size and complexity for C files
* [Corrode ★1570](jameysharp/corrode) - Semi-automatic translation from C to Rust. Could reveal bugs in the original implementation by showing Rust compiler warnings and errors.
* [cppcheck ★1264](danmar/cppcheck) - static analysis of C/C++ code
* [cqmetrics ★18](dspinellis/cqmetrics) - quality metrics for C code
* [CScout](https://www.spinellis.gr/cscout/) - complexity and quality metrics for for C and C preprocessor code
* [flawfinder](http://www.dwheeler.com/flawfinder/) - finds possible security weaknesses
* [flint++](http://l2program.co.uk/category/flint) - cross-platform, zero-dependency port of flint, a lint program for C++ developed and used at Facebook.
* [oclint](http://oclint.org/) - static analysis of C/C++ code
* [Polyspace Bug Finder](https://www.mathworks.com/products/polyspace-bug-finder.html) :copyright: - identifies run-time errors, concurrency issues, security vulnerabilities, and other defects in C and C++ embedded software.
* [Polyspace Code Prover](https://www.mathworks.com/products/polyspace-code-prover.html) :copyright: - provide code verification that proves the absence of overflow, divide-by-zero, out-of-bounds array access, and certain other run-time errors in C and C++ source code.
* [scan-build](https://clang-analyzer.llvm.org/scan-build.html) - Analyzes C/C++ code using LLVM at compile-time
* [splint](http://www.splint.org/) - static analysis of C/C++ code
* [tis-interpreter ★372](TrustInSoft/tis-interpreter) - An interpreter for finding subtle bugs in programs written in standard C
* [vera++](https://bitbucket.org/verateam/vera/wiki/Introduction) - Vera++ is a programmable tool for verification, analysis and transformation of C++ source code.

## C# #

* [.NET Analyzers](https://github.com/DotNetAnalyzers) - An organization for the development of analyzers (diagnostics and code fixes) using the .NET Compiler Platform.
* [Code Analysis Rule Collection](https://carc.codeplex.com/) - Contains a set of diagnostics, code fixes and refactorings built on the Microsoft .NET Compiler Platform "Roslyn".
* [code-cracker ★731](code-cracker/code-cracker) - An analyzer library for C# and VB that uses Roslyn to produce refactorings, code analysis, and other niceties.
* [CSharpEssentials ★137](DustinCampbell/CSharpEssentials) - C# Essentials is a collection of Roslyn diagnostic analyzers, code fixes and refactorings that make it easy to work with C# 6 language features.
* [Designite](http://www.designite-tools.com) :copyright: - Designite is a software design quality assessment tool. It supports detection of implementation and design smells, computation of various code quality metrics, and trend analysis.
* [Gendarme](http://www.mono-project.com/docs/tools+libraries/tools/gendarme/) - Gendarme inspects programs and libraries that contain code in ECMA CIL format (Mono and .NET) and looks for common problems with the code, problems that compiler do not typically check or have not historically checked.
* [NDepend](http://www.ndepend.com/) :copyright: - Measure, query and visualize your code and avoid unexpected issues, technical debt and complexity in your project.
* [Refactoring Essentials](http://vsrefactoringessentials.com/) - The premier free Visual Studio 2015 extension for C# and VB.NET refactorings, including code best practice analyzers to improve your projects.
* [ReSharper](https://www.jetbrains.com/resharper/) :copyright: - Extends Visual Studio with on-the-fly code inspections for C#, VB.NET, ASP.NET, JavaScript, TypeScript and other technologies.
* [Roslyn Security Guard](https://dotnet-security-guard.github.io/) - Project that focus on the identification of potential vulnerabilities such as SQL injection, cross-site scripting (XSS), CSRF, cryptography weaknesses, hardcoded passwords and many more.
* [SonarLint for Visual Studio](https://github.com/SonarSource/sonarlint-vs) - SonarLint is a Visual Studio 2015 extension that provides on-the-fly feedback to developers on new bugs and quality issues injected into .NET code.
* [VSDiagnostics](https://github.com/Vannevelj/VSDiagnostics) - A collection of static analyzers based on Roslyn that integrate with VS.
* [Wintellect.Analyzers ★67](Wintellect/Wintellect.Analyzers) - .NET Compiler Platform ("Roslyn") diagnostic analyzers and code fixes written by Wintellect.

## Elixir

* [credo ★1866](rrrene/credo) - A static code analysis tool with a focus on code consistency and teaching.
* [Dogma ★383](lpil/dogma) - A code style enforcer for Elixir

## Erlang

* [elvis ★253](inaka/elvis) - Erlang Style Reviewer

## Go

* [dingo-hunter ★98](nickng/dingo-hunter) - Static analyser for finding deadlocks in Go
* [flen ★31 ⏳1Y](lafolle/flen) - Get info on length of functions in a Go package
* [Go Meta Linter ★1634](alecthomas/gometalinter) - Concurrently run Go lint tools and normalise their output
* [go vet](https://golang.org/cmd/vet/) - Examines Go source code and reports suspicious constructs
* [go-staticcheck ★402](dominikh/go-staticcheck) - go vet on steroids, similar to ReSharper for C#
* [go/ast](https://golang.org/pkg/go/ast/) - Package ast declares the types used to represent syntax trees for Go packages.
* [gocyclo ★300](fzipp/gocyclo) - Calculate cyclomatic complexities of functions in Go source code
* [golint ★1864](golang/lint) - Prints out coding style mistakes in Go source code.
* [goreporter ★973](wgliang/goreporter) - concurrently runs many linters and normalises their output to a report
* [ineffassign ★119](gordonklaus/ineffassign) - Detect ineffectual assignments in Go code
* [safesql ★298](stripe/safesql) - Static analysis tool for Golang that protects against SQL injections

## Groovy

* [CodeNarc ★122](CodeNarc/CodeNarc) - a static analysis tool for Groovy source code, enabling monitoring and enforcement of many coding standards and best practices

## Haskell

* [HLint ★420](ndmitchell/hlint) - HLint is a tool for suggesting possible improvements to Haskell code.

## Haxe

* [Haxe Checkstyle ★68](HaxeCheckstyle/haxe-checkstyle) - A static analysis tool to help developers write Haxe code that adheres to a coding standard.

## Java

* [Checker Framework ★232](typetools/checker-framework) - Pluggable type-checking for Java http://checkerframework.org/
* [checkstyle ★2005](checkstyle/checkstyle) - checking Java source code for adherence to a Code Standard or set of validation rules (best practices)
* [ckjm](http://www.spinellis.gr/sw/ckjm/) - calculates Chidamber and Kemerer object-oriented metrics by processing the bytecode of compiled Java files
* [Error-prone ★2626](google/error-prone) - Catch common Java mistakes as compile-time errors
* [fb-contrib ★43](mebigfatguy/fb-contrib) - A plugin for FindBugs with additional bug detectors
* [Find Security Bugs](https://find-sec-bugs.github.io/) - IDE/SonarQube plugin for security audits of Java web applications.
* [Findbugs ★327](findbugsproject/findbugs) - FindBugs is a program to find bugs in Java programs. It looks for patterns are likely to be errors.
* [HuntBugs ★260](amaembo/huntbugs) - Bytecode static analyzer tool based on Procyon Compiler Tools aimed to supersede FindBugs.
* [OWASP Dependency Check](https://www.owasp.org/index.php/OWASP_Dependency_Check) - Checks dependencies for known, publicly disclosed, vulnerabilities.

## JavaScript

* [aether ★141](codecombat/aether) - Lint, analyze, normalize, transform, sandbox, run, step through, and visualize user JavaScript, in node or the browser.
* [ClosureLinter ★91](google/closure-linter) - ensures that all of your project's JavaScript code follows the guidelines in the Google JavaScript Style Guide. It can also automatically fix many common errors
* [coffeelint ★830](clutchski/coffeelint) - A style checker that helps keep CoffeeScript code clean and consistent.
* [complexity-report](https://github.com/jared-stilwell/complexity-report) - Software complexity analysis for JavaScript projects
* [escomplex](https://github.com/jared-stilwell/escomplex) - Software complexity analysis of JavaScript-family abstract syntax trees.
* [eslint ★7676](eslint/eslint) - A fully pluggable tool for identifying and reporting on patterns in JavaScript
* [Esprima ★3763](jquery/esprima) - ECMAScript parsing infrastructure for multipurpose analysis
* [jshint ★7237](jshint/jshint) - detect errors and potential problems in JavaScript code and enforce your team's coding conventions
* [JSLint ★2957](douglascrockford/JSLint) :copyright: - The JavaScript Code Quality Tool
* [plato ★3958](es-analysis/plato) - Visualize JavaScript source complexity
* [quality](https://github.com/jden/quality) - zero configuration code and module linting
* [standard](http://standardjs.com/) - An npm module that checks for Javascript Styleguide issues
* [XO ★2621](sindresorhus/xo) - Enforce strict code style. Never discuss code style on a pull request again!
* [yardstick ★23](calmh/yardstick) - Javascript code metrics

## Kotlin

* [detekt ★221](arturbosch/detekt) - Static code analysis for Kotlin code.
* [ktlint ★216](shyiko/ktlint) - An anti-bikeshedding Kotlin linter with built-in formatter

## Lua

* [luacheck ★473](mpeterv/luacheck) - A tool for linting and static analysis of Lua code.

## Perl

* [Perl::Critic](http://search.cpan.org/~thaljef/Perl-Critic-1.126/lib/Perl/Critic.pm) - Critique Perl source code for best-practices.

## PHP

* [dephpend ★55](mihaeu/dephpend) - Dependency analysis tool
* [deptrac ★511](sensiolabs-de/deptrac) - Enforce rules for dependencies between software layers.
* [DesignPatternDetector ★61](Halleck45/DesignPatternDetector) - detection of design patterns in PHP code
* [exakat ★64](exakat/exakat) - An automated code reviewing engine for PHP
* [GrumPHP ★1733](phpro/grumphp) - checks code on every commit
* [Parse ★154](psecio/parse) - A Static Security Scanner
* [phan ★2128](etsy/phan) - a modern static analyzer from etsy
* [Php Inspections (EA Extended) ★244](kalessil/phpinspectionsea) - A Static Code Analyzer for PHP.
* [PHP Refactoring Browser ★544](QafooLabs/php-refactoring-browser) - Refactoring helper
* [PHP-Parser ★2873](nikic/PHP-Parser) - A PHP parser written in PHP
* [PHP-Token-Reflection ★186](Andrewsville/PHP-Token-Reflection) - Library emulating the PHP internal reflection
* [php7cc ★1036](sstalle/php7cc) - PHP 7 Compatibility Checker
* [php7mar ★466](Alexia/php7mar) - assist developers in porting their code quickly to PHP 7
* [PHP_CodeSniffer ★3501](squizlabs/PHP_CodeSniffer) - detects violations of a defined set of coding standards
* [phpcpd ★1230](sebastianbergmann/phpcpd) - Copy/Paste Detector (CPD) for PHP code.
* [phpdcd ★332 ⏳1Y](sebastianbergmann/phpdcd) - Dead Code Detector (DCD) for PHP code.
* [PhpDependencyAnalysis ★260](mamuz/PhpDependencyAnalysis) - builds a dependency graph for a project
* [phpdoc-to-typehint ★185](dunglas/phpdoc-to-typehint) - Add scalar type hints and return types to existing PHP projects using PHPDoc annotations
* [PHPMD](https://phpmd.org/) - finds possible bugs in your code
* [PhpMetrics](https://github.com/Halleck45/PhpMetrics) - calculates code complexity metrics
* [PHPQA ★124](EdgedesignCZ/phpqa) - A tool for running QA tools (phploc, phpcpd, phpcs, pdepend, phpmd, phpmetrics)
* [phpqa ★313](jmolivas/phpqa) - PHPQA all-in-one Analyzer CLI tool
* [phpsa ★600](ovr/phpsa) - Static analysis tool for PHP.
* [PHPStan ★1862](phpstan/phpstan) - PHP Static Analysis Tool - discover bugs in your code without running it!
* [Psalm ★359](vimeo/psalm) - Static analysis tool for finding errors in PHP applications
* [RIPS ★134 ⏳1Y](ripsscanner/rips) - A static source code analyser for vulnerabilities in PHP scripts
* [Tuli ★160 ⏳1Y](ircmaxell/Tuli) - A static analysis engine
* [twig-lint ★61](asm89/twig-lint) - twig-lint is a lint tool for your twig files.
* [WAP](https://www.owasp.org/index.php/OWASP_WAP-Web_Application_Protection) - Tool to detect and correct input validation vulnerabilities in PHP (4.0 or higher) web applications and predicts false positives. It combines source code static analysis and data mining to detect vulnerabilities and predict false positives. 

## Python

* [bandit ★724](openstack/bandit) - a tool to find common security issues in Python code
* [jedi ★2657](davidhalter/jedi) - autocompletion/static analysis library for Python
* [linty fresh ★120](lyft/linty_fresh) - parse lint errors and report them to Github as comments on a pull request
* [mccabe ★112](PyCQA/mccabe) - check McCabe complexity
* [mypy ★2513](python/mypy) - an experimental optional static type checker for Python that aims to combine the benefits of dynamic (or "duck") typing and static typing
* [py-find-injection ★32 ⏳1Y](uber/py-find-injection) - find SQL injection vulnerabilities in Python code
* [pycodestyle ★2250](PyCQA/pycodestyle) - (formerly `pep8`) check Python code against some of the style conventions in PEP 8
* [pydocstyle ★333](PyCQA/pydocstyle) - check compliance with Python docstring conventions
* [pyflakes](https://github.com/pyflakes/pyflakes/) - check Python source files for errors
* [pylint ★651](PyCQA/pylint) - looks for programming errors, helps enforcing a coding standard and sniffs for some code smells. It additionally includes `pyreverse` (an UML diagram generator) and `symilar` (a similarities checker). [Optional extensions](https://pylint.readthedocs.io/en/latest/reference_guide/extensions.html) are also included.
* [pyroma](https://bitbucket.org/regebro/pyroma) - rate how well a Python project complies with the best practices of the Python packaging ecosystem, and list issues that could be improved
* [PyT - Python Taint ★280](python-security/pyt) - A static analysis tool for detecting security vulnerabilities in Python web applications.
* [vulture](https://bitbucket.org/jendrikseipp/vulture) - find unused classes, functions and variables in Python code
* [xenon](https://github.com/rubik/xenon) - monitor code complexity using [`radon` ★715](rubik/radon)

Wrappers:
* [ciocheck ★7](ContinuumIO/ciocheck) - linter, formatter and test suite helper. As a linter, it is a wrapper around `pep8`, `pydocstyle`, `flake8`, and `pylint`.
* [flake8 ★196](PyCQA/flake8) - a wrapper around `pyflakes`, `pycodestyle` and `mccabe`
* [prospector ★714](landscapeio/prospector) - a wrapper around `pylint`, `pep8`, `mccabe` and others

## R

* [lintr ★289](jimhester/lintr) :copyright: - Static Code Analysis for R

## Ruby

* [brakeman ★4204](presidentbeef/brakeman) - A static analysis security vulnerability scanner for Ruby on Rails applications
* [cane ★1306 ⏳1Y](square/cane) - Code quality threshold checking as part of your build
* [dawnscanner ★458](thesp0nge/dawnscanner) - a static analysis security scanner for ruby written web applications. It supports Sinatra, Padrino and Ruby on Rails frameworks.
* [flay ★478](seattlerb/flay) - Flay analyzes code for structural similarities.
* [flog ★533](seattlerb/flog) - Flog reports the most tortured code in an easy to read pain report. The higher the score, the more pain the code is in.
* [laser ★391 ⏳5Y](michaeledgar/laser) - Static analysis and style linter for Ruby code.
* [Mondrian](http://trismegiste.github.io/Mondrian/) - a set of static analysis and refactoring tools for more abstraction
* [pelusa ★446 ⏳2Y](codegram/pelusa) - Static analysis Lint-type tool to improve your OO Ruby code
* [quality ★121](apiology/quality) - Runs quality checks on your code using community tools, and makes sure your numbers don't get any worse over time.
* [reek ★2374](troessner/reek) - Code smell detector for Ruby
* [rubocop ★7695](bbatsov/rubocop) - A Ruby static code analyzer, based on the community Ruby style guide.
* [ruby-lint ★724](YorickPeterse/ruby-lint) - Static code analysis for Ruby
* [rubycritic ★1819](whitesmith/rubycritic) - A Ruby code quality reporter
* [SandyMeter ★679](makaroni4/sandi_meter) - Static analysis tool for checking Ruby code for Sandi Metz' rules.

## Rust

* [clippy ★1373](Manishearth/rust-clippy) - a code linter to catch common mistakes and improve your Rust code
* [electrolysis ★109](Kha/electrolysis) - A tool for formally verifying Rust programs by transpiling them into definitions in the Lean theorem prover.
* [herbie ★120](mcarton/rust-herbie-lint) - Adds warnings or errors to your crate when using a numerically unstable floating point expression.
* [linter-rust ★34](AtomLinter/linter-rust) - Linting your Rust-files in Atom, using rustc and cargo
* [rustfix ★94](killercup/rustfix) - read and apply the suggestions made by rustc (and third-party lints, like those offered by clippy).

## Scala

* [linter ★228](HairyFotr/linter) - Linter is a Scala static analysis compiler plugin which adds compile-time checks for various possible bugs, inefficiencies, and style problems.
* [Scalastyle](http://www.scalastyle.org) - Scalastyle examines your Scala code and indicates potential problems with it.
* [scapegoat ★180](sksamuel/scapegoat) - Scala compiler plugin for static code analysis
* [WartRemover](https://github.com/puffnfresh/wartremover) - a flexible Scala code linting tool.

## Shell

* [shellcheck ★7758](koalaman/shellcheck) - ShellCheck, a static analysis tool that gives warnings and suggestions for bash/sh shell scripts

## SQL

* [sqlint ★124](purcell/sqlint) - Simple SQL linter

## Swift

* [SwiftLint ★6892](realm/SwiftLint) - A tool to enforce Swift style and conventions
* [Tailor ★1020](sleekbyte/tailor) - A static analysis and lint tool for source code written in Apple's Swift programming language.

## TypeScript

* [Codelyzer ★1128](mgechev/codelyzer) - A set of tslint rules for static code analysis of Angular 2 TypeScript projects.

# Multiple languages

* [AppChecker](https://npo-echelon.ru/en/solutions/appchecker.php) :copyright: - Static analysis for C/C++/C#, PHP and Java
* [Application Inspector](https://www.ptsecurity.com/ww-en/products/ai/) :copyright: - Combined SAST, DAST, IAST security scanner for C#, PHP, Java, SQL languages
* [Axivion Bauhaus Suite](https://www.axivion.com/en/products-services-9#products_bauhaussuite) :copyright: - Tracks down error-prone code locations, style violations, cloned or dead code, cyclic dependencies and more for C/C++, C#/.NET, Java and Ada 83/Ada 95
* [coala](https://coala.io/) - Language independent framework for creating code analysis - supports [over 60 languages](https://coala.io/languages) by default
* [codeburner ★56](groupon/codeburner) - Provides a unified interface to sort and act on the issues it finds
* [Coverity Save](http://www.coverity.com/products/coverity-save/) :copyright: - Static analysis for  C/C++, Java and C#
* [Hound CI](https://houndci.com/) - Comments on style violations in GitHub pull requests. Supports Coffeescript, Go, HAML, JavaScript, Ruby, SCSS and Swift.
* [imhotep ★197](justinabrahms/imhotep) - Comment on commits coming into your repository and check for syntactic errors and general lint warnings.
* [Infer ★6755](facebook/infer) - A static analyzer for Java, C and Objective-C
* [Klocwork](http://www.klocwork.com/products-services/klocwork) :copyright: - Quality and Security Static analysis for  C/C++, Java and C#
* [oclint ★1792](oclint/oclint) - A static source code analysis tool to improve quality and reduce defects for C, C++ and Objective-C
* [pfff ★1993](facebook/pfff) - Facebook's tools for code analysis, visualizations, or style-preserving source transformation for many languages
* [PMD](https://pmd.github.io/) - A source code analyzer for Java, Javascript, PLSQL, XML, XSL and others
* [pre-commit ★1287](pre-commit/pre-commit) - A framework for managing and maintaining multi-language pre-commit hooks.
* [PVS-Studio](http://www.viva64.com/en/pvs-studio/) :copyright: - static analysis of C/C++ and C# code
* [shipshape ★163](google/shipshape) - Static program analysis platform that allows custom analyzers to plug in through a common interface
* [SonarQube](http://www.sonarqube.org/) - SonarQube is an open platform to manage code quality.
* [STOKE ★191](StanfordPL/stoke) - a programming-language agnostic stochastic optimizer for the x86_64 instruction set. It uses random search to explore the extremely high-dimensional space of all possible program transformations
* [Undebt ★1411](Yelp/undebt) - Language-independent tool for massive, automatic, programmable refactoring based on simple pattern definitions
* [WALA](http://wala.sourceforge.net/wiki/index.php/Main_Page) - static analysis capabilities for Java bytecode and related languages and for JavaScript
* [XCode](https://developer.apple.com/xcode/) [PROPRIETARY/OSS] - XCode provides a pretty decend UI for [Clang's](http://clang-analyzer.llvm.org/xcode.html) static code analyzer (C/C++, Obj-C)

# Other

## Build tools

* [checkmake ★111](mrtazz/checkmake) - Linter / Analyzer for Makefiles
* [codechecker ★327](Ericsson/codechecker) - a defect database and viewer extension for the Clang Static Analyzer

## Binaries

* [BinSkim ★216](Microsoft/binskim) - A binary static analysis tool that provides security and correctness results for Windows portable executables.
* [Manalyze ★226](JusticeRage/Manalyze) - A static analyzer, which checks portable executables for malicious content.

## Containers

* [clair ★2226](coreos/clair) - Vulnerability Static Analysis for Containers
* [collector ★150](banyanops/collector) - Run arbitrary scripts inside containers, and gather useful information
* [dagda ★259](eliasgranderubio/dagda) - Perform static analysis of known vulnerabilities in docker images/containers.
* [Docker Label Inspector ★62 ⏳1Y](garethr/docker-label-inspector) - Lint and validate Dockerfile labels
* [Haskell Dockerfile Linter ★594](lukasmartinelli/hadolint) - A smarter Dockerfile linter that helps you build best practice Docker images

## Config Files

* [gixy ★4369](yandex/gixy) - a tool to analyze Nginx configuration. The main goal is to prevent misconfiguration and automate flaw detection.

## Configuration Management

* [Puppet Lint ★625](rodjek/puppet-lint) - Check that your Puppet manifests conform to the style guide.

## CSS

* [CSS Stats ★1849](cssstats/cssstats) - Potentially interesting stats on stylesheets
* [CSScomb ★2086](csscomb/csscomb.js) - a coding style formatter for CSS. Supports own configurations to make style sheets beautiful and consistent
* [CSSLint ★3758](CSSLint/csslint) - Does basic syntax checking and finds problematic patterns or signs of inefficiency
* [Parker ★2265](katiefenn/parker) - Stylesheet analysis tool
* [scsslint ★2758](brigade/scss-lint) - Linter for SCSS files
* [Specificity Graph ★567 ⏳1Y](pocketjoso/specificity-graph) - CSS Specificity Graph Generator
* [Stylelint](http://stylelint.io/) - Linter for SCSS/CSS files

## HTML

* [HTMLHint ★1446](yaniswang/HTMLHint) - A Static Code Analysis Tool for HTML
* [HTML Inspector ★2306](philipwalton/html-inspector) - HTML Inspector is a code quality tool to help you and your team write better markup.

## Makefiles

* [portlint](https://www.freebsd.org/cgi/man.cgi?query=portlint&sektion=1&manpath=FreeBSD+8.1-RELEASE+and+Ports) - A verifier for FreeBSD and DragonFlyBSD port directories

## Mobile

* [FlowDroid ★146](secure-software-engineering/soot-infoflow-android) - static taint analysis tool for Android applications
* [paprika ★19](GeoffreyHecht/paprika) - A toolkit to detect some code smells in analyzed Android applications.
* [qark ★1313](linkedin/qark) - Tool to look for several security related Android application vulnerabilities

## Packages

* [lintian ★21](Debian/lintian) - Static analysis tool for Debian packages

## Web services

* [Bithound](https://www.bithound.io/) :copyright: - Code Analysis beyond Lint, specifically for Node.js.
* [Codacy](https://www.codacy.com/) :copyright: - Code Analysis to ship Better Code, Faster.
* [Code Climate](https://codeclimate.com/) :copyright: - The open and extensible static analysis platform, for everyone.
* [ConQAT](http://www.conqat.org/) - a toolkit for rapid development and execution of software quality analyses.
* [Functor Prevent](http://www.functor.se/products/prevent/) :copyright: - Static code analysis for C code.
* [kiuwan](https://www.kiuwan.com/) :copyright: - Software Analytics in the Cloud supporting more than 22 programming languages.
* [Landscape](https://landscape.io/) :copyright: - Static code analysis for Python
* [Nitpick CI](https://nitpick-ci.com) :copyright: - Automated PHP code review
* [Node Security Platform](https://nodesecurity.io/) :copyright: - Continuous Security monitoring for your node apps (free for Open Source Projects)
* [QuantifiedCode](https://www.quantifiedcode.com/) :copyright: - Automated code review & repair
* [Scrutinizer](https://scrutinizer-ci.com/) :copyright: - A proprietery code quality checker that can be integrated with GitHub
* [SensioLabs Insight](https://insight.sensiolabs.com/) :copyright: - Detect security risks, find bugs and provide actionable metrics for PHP projects
* [SideCI](https://sideci.com):copyright: - An automated code reviewing tool. Improving developers' productivity.
* [Snyk](https://snyk.io/) :copyright: - Vulnerability scanner for dependencies of node.js apps (free for Open Source Projects)
* [Teamscale](http://www.teamscale.com/) :copyright: - analyze, monitor, and improve the quality of your code.
* [Upsource](https://www.jetbrains.com/upsource/) :copyright: - Code review tool with static code analysis and code-aware navigation for Java, PHP, JavaScript and Kotlin.

# More collections

* [go-tools ★699](dominikh/go-tools) - A collection of tools and libraries for working with Go code, including linters and static analysis
* [linters ★157](mcandre/linters) - An introduction to static code analysis
* [php-static-analysis-tools ★929](exakat/php-static-analysis-tools) -  A reviewed list of useful PHP static analysis tools
* [Tools for C/C++](https://www.peerlyst.com/posts/a-list-of-static-analysis-tools-for-c-c-peerlyst?utm_source=twitter&utm_medium=social&utm_content=peerlyst_post&utm_campaign=peerlyst_resources) - A list of static analysis tools for C/C++
* [Wikipedia](http://en.wikipedia.org/wiki/List_of_tools_for_static_code_analysis) -  A list of tools for static code analysis.

## License

[![CC0](https://i.creativecommons.org/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Matthias Endler](http://matthias-endler.de) has waived all copyright and related or neighboring rights to this work. 
Title image [Designed by Freepik](http://www.freepik.com).
---
<p align="center">
	This list is a copy of <a href="mre/awesome-static-analysis">mre/awesome-static-analysis</a> with ranks
</p>
