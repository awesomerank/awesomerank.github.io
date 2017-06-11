---
layout: default
title: Awesome Rank
---

<a href="https://github.com/awesomerank/rank"><img style="position: absolute; top: 0; right: 0; border: 0;" src="https://camo.githubusercontent.com/a6677b08c955af8400f44c6298f40e7d19cc5b2d/68747470733a2f2f73332e616d617a6f6e6177732e636f6d2f6769746875622f726962626f6e732f666f726b6d655f72696768745f677261795f3664366436642e706e67" alt="Fork me on GitHub" data-canonical-src="https://s3.amazonaws.com/github/ribbons/forkme_right_gray_6d6d6d.png"></a>

<h1 align="center">
Ranked awesome lists, all in one place
</h1>
<p align="center">
	This list is a copy of <a href="https://github.com/unixorn/awesome-zsh-plugins">unixorn/awesome-zsh-plugins</a> with ranks
</p>
---

# awesome-zsh-plugins
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg) ★59088](https://github.com/sindresorhus/awesome)

## Status
[![Build Status](https://travis-ci.org/unixorn/awesome-zsh-plugins.svg?branch=master)](https://travis-ci.org/unixorn/awesome-zsh-plugins) [![Join the chat at https://gitter.im/unixorn/awesome-zsh-plugins](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/unixorn/awesome-zsh-plugins?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge) [![GitHub stars](https://img.shields.io/github/stars/unixorn/awesome-zsh-plugins.svg)](https://github.com/unixorn/awesome-zsh-plugins/stargazers)

A collection of ZSH frameworks, plugins, tutorials & themes inspired by the various awesome list collections out there.

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**  *generated with [DocToc ★1354](https://github.com/thlorenz/doctoc)*

- [Frameworks](#frameworks)
  - [alf](#alf)
  - [ansible-role-zsh](#ansible-role-zsh)
  - [ant-zsh](#ant-zsh)
  - [antibody](#antibody)
  - [antigen-hs](#antigen-hs)
  - [antigen](#antigen)
  - [ax-zsh](#ax-zsh)
  - [dotzsh](#dotzsh)
  - [fresh](#fresh)
  - [oh-my-zsh](#oh-my-zsh)
  - [prezto](#prezto)
  - [pumice](#pumice)
  - [zeesh](#zeesh)
  - [zgen](#zgen)
  - [zilsh](#zilsh)
  - [zim](#zim)
  - [zoppo](#zoppo)
  - [zplug](#zplug)
  - [zplugin](#zplugin)
  - [ZPM](#zpm)
  - [ZR](#zr)
  - [ztanesh](#ztanesh)
  - [zulu](#zulu)
- [Tutorials](#tutorials)
  - [Generic ZSH](#generic-zsh)
  - [Antigen](#antigen)
  - [Oh-My-Zsh](#oh-my-zsh)
  - [Prezto](#prezto)
  - [Zgen](#zgen)
- [Plugins](#plugins)
- [Even more completions](#even-more-completions)
- [Themes](#themes)
  - [Fonts](#fonts)
- [Installation](#installation)
  - [Antigen](#antigen-1)
  - [dotzsh](#dotzsh-1)
  - [Oh-My-Zsh](#oh-my-zsh-1)
  - [Prezto](#prezto-1)
  - [Zgen](#zgen-1)
  - [zplug](#zplug-1)
- [Writing New Plugins](#writing-new-plugins)
- [Other Resources](#other-resources)
  - [ZSH Tools](#zsh-tools)
  - [Other Useful Lists](#other-useful-lists)
  - [Other References](#other-references)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

*Please read the [Contributing Guidelines](https://github.com/unixorn/awesome-zsh-plugins/blob/master/Contributing.md) before contributing.*

## Frameworks

These frameworks make customizing your zsh setup easier.

### [alf ★29 ⏳1Y](https://github.com/psyrendust/alf)

**Alf** is an out of this world super fast and configurable framework for zsh; it's modeled after Prezto and Antigen while utilizing Oh My Zsh under the covers; and offers standard defaults, aliases, functions, auto completion, automated updates and installable prompt themes and plugins.

### [ansible-role-zsh ★36](https://github.com/viasite-ansible/ansible-role-zsh)

**ansible-role-zsh** is ansible role with zero-knowledge installation. It uses antigen for manage bundles and oh-my-zsh. Can load bundles conditionally. By default it includes powerlevel9k theme, autosuggestions, syntax-highlighting, fzf-widgets. Fully customizable.

### [ant-zsh ★8](https://github.com/anthraxx/ant-zsh)

**Ant-zsh** is a tiny and lightweight ZSH configuration environment for special customization needs. It includes plugins, themes and a basic convenient setup.

### [antibody](https://github.com/caarlos0/antibody)

**Antibody** A faster and simpler antigen written in Golang. More details at [http://getantibody.github.io/](http://getantibody.github.io/).

### [antigen-hs ★165](https://github.com/Tarrasch/antigen-hs)

**antigen-hs** is a replacement for antigen optimized for a low overhead when starting up the shell. It will automatically clone plugins for you.

### [antigen ★3160](https://github.com/zsh-users/antigen)

**Antigen** is a small set of functions that help you easily manage your shell (zsh) plugins, called bundles. The concept is pretty much the same as bundles in a typical vim+pathogen setup. Antigen is to zsh, what Vundle is to vim. Antigen can load oh-my-zsh themes and plugins and will automatically clone them for you.

### [ax-zsh ★3](https://github.com/alexbarton/ax-zsh)

**Ax-ZSH** is a modular configuration system for ZSH. It provides sane defaults and is extendable by plugins.

### [dotzsh ★129](https://github.com/dotphiles/dotzsh)

**Dotzsh** strives to be platform and version independent. Some functionality may be lost when running under older versions of zsh, but it should degrade cleanly and allow you to use the same setup on multiple machines of differing OSes without problems.

### [fresh ★782](https://github.com/freshshell/fresh)

**fresh** is a tool to source shell configuration (aliases, functions, etc) from others into your own configuration files. We also support files such as ackrc and gitconfig. Think of it as Bundler for your dot files.

### [oh-my-zsh](http://ohmyz.sh/)

**oh-my-zsh** is a community-driven framework for managing your zsh configuration. Includes 120+ optional plugins (rails, git, OSX, hub, capistrano, brew, ant, macports, etc), over 120 themes to spice up your morning, and an auto-update tool that makes it easy to keep up with the latest updates from the community.

### [prezto ★7609](https://github.com/sorin-ionescu/prezto)

**Prezto** enriches the ZSH command line interface environment with sane defaults, aliases, functions, auto completion, and prompt themes.

### [pumice ★3 ⏳2Y](https://github.com/ryutamaki/pumice)

**Pumice** is a lightweight plugin manager for zsh.

### [zeesh ★27](https://github.com/zeekay/zeesh)

**Zeesh** is a cross-platform Zsh framework. It's similar to, but incompatible with, oh-my-zsh. It has a modular plugin architecture making it easy to extend. It has a rich set of defaults, but is designed to be as lightweight as possible.

### [zgen ★747](https://github.com/tarjoilija/zgen)

**Zgen** is a lightweight plugin manager for ZSH inspired by Antigen. The goal is to have a minimal overhead when starting up the shell because nobody likes waiting. The script generates a static `init.zsh` file which does nothing but source your plugins and append them to your `fpath`. The downside is that you have to refresh the init script manually with `zgen reset` whenever you update your `.zshrc`. Can load oh-my-zsh compatible plugins and themes, and will automagically clone them for you when you add them to your plugin list.

### [zilsh ★22 ⏳2Y](https://github.com/zilsh/zilsh)

**zilsh** is a zsh config system that aims to appeal more to power-users and follow the simplistic approach of vim-pathogen.

### [zim ★837](https://github.com/Eriner/zim)

**Zim** is a Zsh configuration framework with blazing speed and modular extensions.

### [zoppo ★25](https://github.com/zoppo/zoppo)

**Zoppo** is the crippled configuration framework for Zsh. As an Italian saying goes: "chi va con lo zoppo, impara a zoppicare", we realized we were walking with a cripple and are now going to become crippled ourselves.

### [zplug ★1558](https://github.com/zplug/zplug)

**:hibiscus: Zplug** is a next-generation zsh plugin manager.

### [zplugin ★52](https://github.com/zdharma/zplugin)

**Zplugin** gives reports from plugin load. Plugins are no longer black boxes, report will tell what aliases, functions, bindkeys, Zle widgets, zstyles, completions, variables, PATH and FPATH elements a plugin has set up. Supported is **unloading** of plugin and ability to list, uninstall, reinstall and selectively disable, enable plugin's completions. Also, every plugin is compiled and the user can control this function. The system does not use $FPATH, it's kept clean!

### [ZPM](https://github.com/horosgrisa/ZPM)

**ZPM** ( Zsh plugin manager ) is a plugin manager for [zsh](http://www.zsh.org/) similar to vim-plug. ZPM plugins are compatible with [oh-my-zsh ★54129](https://github.com/robbyrussell/oh-my-zsh). ZPM runs on Linux, Android, FreeBSD and OS X.

### [ZR ★10](https://github.com/jedahan/zr)

**ZR** is a zsh plugin manager written in Rust.

### [ztanesh ★237](https://github.com/miohtama/ztanesh)

**Ztanesh** aims to improve your UNIX command line experience and productivity with the the configuration provided by the ztanesh project: the tools will make your shell more powerful and easier to use.

### [zulu ★44](https://github.com/zulu-zsh/zulu)

**Zulu** is a total environment manager for ZSH 5+

## Tutorials

### Generic ZSH

* [http://commandlinepoweruser.com](http://commandlinepoweruser.com/) - Wes Bos' videos introducing ZSH and oh-my-zsh.
* [https://wiki.archlinux.org/index.php/zsh](https://wiki.archlinux.org/index.php/zsh) - Arch Linux's ZSH introduction. Not Arch or Linux-specific.
* [Outrageously Useful Tips To Master Your Z Shell](http://reasoniamhere.com/2014/01/11/outrageously-useful-tips-to-master-your-z-shell/) covers some of the features that ZSH has that Bash doesn't, and using oh-my-zsh.
* [The Text Triumvirate](http://www.drbunsen.org/the-text-triumvirate/) - Seth Brown's tutorial on combining zsh, tmux and vim.
* [Why ZSH is Cooler than your Shell](http://www.slideshare.net/jaguardesignstudio/why-zsh-is-cooler-than-your-shell-16194692) - slideshare presentation
* [ZSH Pony ★78 ⏳5Y](https://github.com/mika/zsh-pony) - Covers customizing ZSH without a framework.
* [ZSH tips by Christian Schneider](http://strcat.de/zsh/#tipps) - An exhaustive list of ZSH tips by Christian Schneider.
* Larry Schrof's [ZSH Workshop](https://www-s.acm.illinois.edu/workshops/zsh/toc.html)

### Antigen

* [http://mgdm.net/weblog/zsh-antigen](http://mgdm.net/weblog/zsh-antigen/) - Michael Maclean's article about switching from oh-my-zsh to antigen.
* [Oh-my-zsh is the Disease and Antigen is the Vaccine](http://joshldavis.com/2014/07/26/oh-my-zsh-is-a-disease-antigen-is-the-vaccine/) - Josh Davis' introduction to Antigen

### Oh-My-Zsh

* [ZSH Gem 24](http://www.refining-linux.org/archives/59/ZSH-Gem-24-ZSH-frameworks/) - Part of the 2011 ZSH Advent Calendar. Covers oh-my-zsh and zshuery.

### Prezto

* [A Beautifully Productive Terminal Experience](http://mikebuss.com/2014/02/02/a-beautiful-productive-terminal-experience) - Mike Buss' blog post about using Prezto, Tmux & Tmuxinator.
* [Ditching oh-my-zsh for prezto](https://linhmtran168.github.io/blog/2013/12/15/ditching-oh-my-zsh-for-prezto/) - Linh M. Tran's post about transitioning to Prezto from Oh-My-Zsh.
* [Migrate from Oh-My-Zsh to Prezto](http://jeromedalbert.com/migrate-from-oh-my-zsh-to-prezto/) - Jerome Dalbert's blog post on migrating to Prezto.

### Zgen

* [zsh-quickstart-kit ★98](https://github.com/unixorn/zsh-quickstart-kit) - A simple quickstart for using zsh with zgen. This includes a curated collection of plugins, and will automatically configure zsh to use zgen to load them, configures zgen to periodically automatically update itself, the plugins, and the quickstart kit itself.

## Plugins

* [accurev-zsh ★1 ⏳2Y](https://github.com/dalefukami/accurev-zsh) - ZSH plugin for accurev.
* [alias-tips ★167](https://github.com/djui/alias-tips) - An oh-my-zsh plugin to help remembering those aliases you defined once.
* [allergen ★1](https://github.com/stanislas/allergen) - A collection of custom zsh plugins to use with antigen
* [almostontop ★34 ⏳1Y](https://github.com/Valiev/almostontop) - Clears previous command output every time before new command executed in shell. Inspired by alwaysontop plugin for bash.
* [ansible ★1](https://github.com/sparsick/ansible-zsh) - A plugin for Ansible.
* [ansiweather ★1282](https://github.com/fcambus/ansiweather) - Weather in your terminal, with ANSI colors and Unicode symbols.
* [antigen-git-rebase ★0 ⏳2Y](https://github.com/smallhadroncollider/antigen-git-rebase) - Antigen/zsh script to aid with Git rebasing.
* [antigen-git-store](https://github.com/smallhadroncollider/antigen-git-store) - Antigen/zsh script to store Git's current working directory. For working with Git between two computers without forcing arbitrary commits.
* [anyframe ★104](https://github.com/mollifier/anyframe) - A peco/percol/fzf wrapper plugin for zsh.
* [apache2.plugin.zsh ★3](https://github.com/voronkovich/apache2.plugin.zsh) - Adds aliases and functions for managing Apache2.
* [asciidoctor ★0](https://github.com/sparsick/asciidoctor-zsh) - A plugin for AsciiDoctor.
* [atom_plugin.zsh ★1](https://github.com/kingsj/atom_plugin.zsh) - A plugin for the Atom editor on OS X.
* [auto-fu.zsh ★327](https://github.com/hchbaw/auto-fu.zsh) - Automatic complete-word and list-choices. Originally incr-0.2.zsh by y.fujii <y-fujii at mimosa-pudica.net>.
* [auto-ls ★2](https://github.com/desyncr/auto-ls) - Automatically `ls` when cding to a new directory.
* [autoenv](https://github.com/horosgrisa/autoenv) - Extended version of the zsh-autoenv plugin.
* [autojump ★5506](https://github.com/wting/autojump) - A cd command that learns - easily navigate directories from the command line. Install autojump-zsh for best results.
* [autoupdate-antigen.zshplugin ★10 ⏳2Y](https://github.com/unixorn/autoupdate-antigen.zshplugin) - Antigen doesn't do automatic updates like oh-my-zsh. This plugin adds auto updating for antigen, both of antigen and the bundles loaded in your configuration.
* [aws-upload-zsh ★0](https://github.com/borracciaBlu/aws-upload-zsh) - Boost your productivity with aws-upload.
* [bitbucket-git-helpers ★6](https://github.com/unixorn/bitbucket-git-helpers.plugin.zsh) - Adds helper scripts to allow you to create bitbucket PRs or open a directory in the current branch.
* [blackbox ★3396](https://github.com/StackExchange/blackbox) - Stack Exchange's toolkit for storing keys/credentials securely in a git repository.
* [branch-manager ★0 ⏳1Y](https://github.com/elstgav/branch-manager) - A plugin for managing git branches.
* [browse-commit ★10 ⏳1Y](https://github.com/adolfoabegg/browse-commit) - A plugin that lets you open any commit in your browser from the command line.
* [bumblebee ★0](https://github.com/Niverton/zsh-bumblebee-plugin) - A plugin to toggle optirun in the command line
* [calc.plugin.zsh ★23 ⏳1Y](https://github.com/arzzen/calc.plugin.zsh) - A calculator for zsh.
* [caniuse.plugin.zsh ★11](https://github.com/walesmd/caniuse.plugin.zsh) - Add [Can I Use...](https://caniuse.com) support to ZSH.
* [cd-gitroot ★22 ⏳1Y](https://github.com/mollifier/cd-gitroot) - A zsh plugin to cd to the git repository root directory.
* [cdbk ★6 ⏳2Y](https://github.com/MikeDacre/cdbk) - A ZSH plugin to allow easy named directory creation - shortcuts to any directory you want.
* [cdr ★5 ⏳1Y](https://github.com/willghatch/zsh-cdr) - Easy setup of cdr for zsh.
* [colored-man-pages-mod ★0](https://github.com/zuxfoucault/colored-man-pages_mod) - Forked from [robbyrussell/oh-my-zsh/plugins/colored-man-pages](https://github.com/robbyrussell/oh-my-zsh/blob/master/plugins/colored-man-pages/colored-man-pages.plugin.zsh). Colorizes `man` output.
* [command-not-found ★7](https://github.com/Tarrasch/zsh-command-not-found) - mirror of the oh-my-zsh command-not-found plugin so you don't have to include all of omz.
* [copyzshell ★12](https://github.com/rutchkiwi/copyzshell) - A ZSH plugin to copy your shell configuration to another machine over ssh.
* [crash ★9](https://github.com/molovo/crash) - Adds proper error handling, exceptions and try/catch for ZSH.
* [crayon-syntax-zsh ★0 ⏳3Y](https://github.com/Stibbons/crayon-syntax-zsh) - ZSH syntax highlighting for the Crayon Plugin for Wordpress.
* [crystal](https://github.com/veelenga/crystal-zsh) - A plugin for [Crystal](https://github.com/manastech/crystal).
* [czhttpd ★23 ⏳1Y](https://github.com/jsks/czhttpd) - A simple http server written in 99.9% pure zsh.
* [deer ★190](https://github.com/Vifon/deer) - A file navigator for zsh heavily inspired by [ranger](http://ranger.nongnu.org/).
* [depot-tools ★0 ⏳4Y](https://github.com/jgrowl/depot_tools) - Simple oh-my-zsh plugin for installing the chromium depot_tools. Installing this plugin will put all of the chromium depot_tools in your path automatically.
* [docker-aliases ★2](https://github.com/webyneter/docker-aliases) Docker aliases for everyday use.
* [docker-compose ★22 ⏳1Y](https://github.com/sroze/docker-compose-zsh-plugin) Show docker container status in your prompt.
* [docker-fun ★2 ⏳1Y](https://github.com/johnlabarge/docker_fun) - Adds docker convenience functions.
* [docker-helpers ★12 ⏳1Y](https://github.com/unixorn/docker-helpers.zshplugin) - A collection of docker helper scripts.
* [dropbox](https://github.com/horosgrisa/zsh-dropbox) - A dropbox plugin for Zsh that provides `dropbox-cli` and `dropbox-uploader` commands.
* [elixir-oh-my-zsh ★75](https://github.com/gusaiani/elixir-oh-my-zsh) - Adds shortcuts for Elixir, IEX, Mix and Phoenix.
* [emoji-cli ★133](https://github.com/b4b4r07/emoji-cli) - :scream: Emoji completion on the command line.
* [enhancd ★639](https://github.com/b4b4r07/enhancd) - A simple tool that provides enhanced `cd` command.
* [exercism ★4 ⏳1Y](https://github.com/fabiokiatkowski/exercism.plugin.zsh) - A plugin for [exercism.io](http://exercism.io/).
* [expand-ealias ★4](https://github.com/zigius/expand-ealias.plugin.zsh) - Expand specific aliases with space.
* [fast-syntax-highlighting ★66](https://github.com/zdharma/fast-syntax-highlighting) - Optimized an improved `zsh-users/zsh-syntax-highlighting` – better response times, `zed/vared` can edit `10 kB` functions.
* [fixnumpad-osx.plugin.zsh](https://github.com/zsmizzle/fixnumpad-osx.plugin.zsh/blob/master/fixnumpad-osx.plugin.zsh) - Enables numpad keys of Apple keyboards to be recognized in zsh.
* [fzf-marks](https://github.com/uvaes/fzf-marks) - Little script to create, navigate and delete bookmarks in Bash and Zsh, using the fuzzy finder [fzf ★9056](https://github.com/junegunn/fzf).
* [fzf-widgets](https://github.com/ytet5uy4/fzf-widgets) - Adds some ZLE widgets for [fzf ★9056](https://github.com/junegunn/fzf).
* [fzf-z ★10](https://github.com/andrewferrier/fzf-z) - Brings together the *z* plugin and *fzf* to allow you to easily browse recently used directories at any point on the command line.
* [get-jquery ★0 ⏳2Y](https://github.com/voronkovich/get-jquery.plugin.zsh) - Plugin for fast downloading jQuery library from [code.jquery.com](code.jquery.com).
* [ghost-zeus ★3 ⏳2Y](https://github.com/fontno/ghost_zeus) - Lets you use zeus with normal rails commands.
* [git-add-remote ★6](https://github.com/caarlos0/git-add-remote) - Easily add the upstream remote to your git fork.
* [git-aliases.zsh ★27](https://github.com/peterhurford/git-aliases.zsh) - Creates a lot of useful aliases for combinations of commonly used git commands.
* [git-extra-commands ★162](https://github.com/unixorn/git-extra-commands) - Extra git helper scripts packaged as a plugin.
* [git-it-on.zsh ★39](https://github.com/peterhurford/git-it-on.zsh) - Adds ability to open a folder in your current branch on GitHub.
* [git-prompt-useremail ★0](https://github.com/mroth/git-prompt-useremail) - Adds prompt reminders for git user.email.
* [git-prune ★17](https://github.com/Seinh/git-prune) - Plugin that simplifies deleting merged branches.
* [git-secret ★535](https://github.com/sobolevn/git-secret) - A bash-tool to store your private data inside a git repository.
* [gitfast ★2 ⏳2Y](https://github.com/tevren/gitfast-zsh-plugin) - Updated fork of oh-my-zsh gitfast plugin.
* [gitignore.plugin.zsh ★15](https://github.com/voronkovich/gitignore.plugin.zsh) - Plugin for creating `.gitignore` files.
* [gitio-zsh ★9 ⏳1Y](https://github.com/denysdovhan/gitio-zsh) - A zsh plugin for generating a GitHub short URL using [git.io](https://git.io).
* [gitsync ★1 ⏳1Y](https://github.com/washtubs/gitsync) - zsh plugin to improve workflows for one person developing on the same repository on multiple machines.
* [goenv ★2 ⏳2Y](https://github.com/bbenne10/goenv) - Antigen plugin to manage `$GOPATH` similarly to Python's virtualenvwrapper.
* [going_places ★0](https://github.com/or17191/going_places) - A plugin that helps to use, create and maintain a list of shell locations.
* [gpg-agent ★3](https://github.com/axtl/gpg-agent.zsh) - Plugin that tries to do the right thing when it comes to setting up the GPG agent to act as an SSH agent as well on OS X.
* [grep2awk ★11 ⏳1Y](https://github.com/joepvd/grep2awk) - ZLE widget to transform grep command into awk command.
* [gtm-terminal-plugin ★3](https://github.com/git-time-metric/gtm-terminal-plugin) - terminal plugin for [git time metrics](https://github.com/git-time-metric/gtm/blob/master/README.md).
* [hipchat ★14 ⏳1Y](https://github.com/robertzk/hipchat.zsh) - Send hipchat messages from the shell.
* [history-search-multi-word ★41](https://github.com/zdharma/history-search-multi-word) - syntax highlighted, multi-word history searcher for Zsh, bound to Ctrl-R, with advanced functions (e.g. bump of history entry to top of history).
* [history-sync ★16](https://github.com/wulfgarpro/history-sync) - An Oh My Zsh plugin for GPG encrypted, Internet synchronized Zsh history using Git.
* [hooks ★14 ⏳1Y](https://github.com/willghatch/zsh-hooks) - Add missing hooks - for plugins and personal use.
* [host-switch ★1](https://github.com/LockonS/host-switch) - Make it easier to switch in different `/etc/hosts` files during development.
* [hub-ci-zsh-plugin ★0 ⏳1Y](https://github.com/raymondjcox/hub-ci-zsh-plugin) - A simple plugin for adding hub ci-status to your zsh theme.
* [iosctl ★1](https://github.com/obayer/iosctl) - quickly access App, Data, and Log of the running simulator.
* [iterm-tab-colors ★6](https://github.com/tysonwolker/iterm-tab-colors) - Automatically changes iTerm tab color based on the current working directory
* [java-zsh-plugin ★0](https://github.com/Xetius/java-zsh-plugin) - Adds a setjdk command so you can switch easily between different versions of the jdk.
* [jenkins-zsh ★1](https://github.com/tomplex/jenkins-zsh) - A jenkins plugin for ZSH, heavily inspired by the excellent jira plugin.
* [jhipster-oh-my-zsh-plugin ★13](https://github.com/jhipster/jhipster-oh-my-zsh-plugin) - Adds commands for [jHipster](https://jhipster.github.io/).
* [jvm ★2 ⏳2Y](https://github.com/mgryszko/jvm) - Allows selection of JDK on OS X.
* [k](https://github.com/rimraf/k) - Directory listings for zsh with git features.
* [kitsunebook.plugin.zsh ★0 ⏳2Y](https://github.com/d12frosted/kitsunebook.plugin.zsh) - KitsuneBook plugin for oh-my-zsh.
* [kubectl-zsh-plugin ★0](https://github.com/mattbangert/kubectl-zsh-plugin) - ZSH plugin for managing kubectl
* [laravel ★0](https://github.com/crazybooot/laravel-zsh-plugin) - Add shortcuts for Laravel 5, 5.1, 5.2 & 5.3.
* [lesaint-mvn ★0 ⏳2Y](https://github.com/lesaint/lesaint-mvn) - Maven plugins for Oh-My-Zsh.
* [linuxbrew ★0](https://github.com/zpm-zsh/linuxbrew) - Zsh plugin for [linuxbrew](http://linuxbrew.sh/)
* [listbox ★11](https://github.com/gko/listbox) - Listbox element for shell.
* [locate-sublime-projects-cli ★0 ⏳1Y](https://github.com/david-treblig/locate-sublime-projects-cli) - Allows searching for Sublime Text projects and opens them in Sublime.
* [lumberjack ★9](https://github.com/molovo/lumberjack) - Lumberjack is a logging interface for shell scripts
* [mac-packaging ★1 ⏳2Y](https://github.com/Temikus/mac-packaging) - A set of common functions used for enterprise Mac packaging with Munki.
* [macos-zsh-plugin ★0](https://github.com/joow/macos-zsh-plugin) - A zsh plugin for macOS.
* [mage2docker ★2](https://github.com/lukaszolszewski/mage2docker) - Makes it easy to work with Docker and Magento 2. Speeds up and simplifies common commands like clean cache, setup upgrade, compile di and much more in Magento 2 on containers.
* [markjump ★0](https://github.com/zakariaGatter/MarkGate) - Allows you to mark directories so you can jump directly to them.
* [mfunc ★3 ⏳1Y](https://github.com/hlohm/mfunc) - Allows you to define persistent functions on-the-fly, without the need to add them to your config files. These functions are permanently available until you delete them.
* [monorepo-plugin ★0](https://github.com/zilongqiu/monorepo-zsh-plugin) - ZSH plugin for monorepo management.
* [mylocation ★4](https://github.com/KasperChristensen/mylocation) - A plugin to show your current location based on your IP address.
* [mysql-colorize](https://github.com/horosgrisa/mysql-colorize) - Colors for mysql tables.
* [mysql.plugin.zsh ★9 ⏳2Y](https://github.com/voronkovich/mysql.plugin.zsh) - Adds some functions for dealing with mysql.
* [nice-exit-code ★16 ⏳2Y](https://github.com/bric3/nice-exit-code) - Maps exit status code to human readable string.
* [node.plugin.zsh ★5 ⏳2Y](https://github.com/srijanshetty/node.plugin.zsh) - Srijan Shetty's nodejs plugin for zsh with caching of nvm completions and autoloading of nvm if present.
* [nodenv.plugin.zsh ★0](https://github.com/jsahlen/nodenv.plugin.zsh) - Auto-load nodenv and its completions into the shell.
* [nohup ★0](https://github.com/micrenda/zsh-nohup) - Add `nohup` to the current command pressing `Ctrl-H`.
* [noreallyjustfuckingstopalready ★262](https://github.com/eventi/noreallyjustfuckingstopalready) - OS X users know the pain of trying to figure out what command actually flushes the DNS cache on their version of OS X, and this plugin makes that annoyance go away.
* [nvm-auto-use ★3 ⏳1Y](https://github.com/tomsquest/nvm-auto-use.zsh) - calls `nvm use` automatically whenever you enter a directory that contains an `.nvmrc` file with a string telling nvm which node to use.
* [nvm-auto ★6](https://github.com/dijitalmunky/nvm-auto) - Aims to alleviate needing to type `nvm use` as much as possible, especially if you often switch between versions of node.js and use `.nvmrc` files in your project to manage what version of node your project needs.
* [oh-my-dogesh ★3 ⏳3Y](https://github.com/keithhamilton/oh-my-dogesh) - Dogification plugin.
* [oh-my-zsh-dirstack ★1 ⏳2Y](https://github.com/gepoch/oh-my-zsh-dirstack) - Plugin for displaying dirstack info on a single line.
* [oh-my-zsh-flow-plugin ★28](https://github.com/sandstorm/oh-my-zsh-flow-plugin) - This plugin makes the flow command available inside every subdirectory of the TYPO3 Flow distribution.
* [oh-my-zsh-jira-plus ★2 ⏳2Y](https://github.com/gerges/oh-my-zsh-jira-plus) - Create JIRAs from the command line.
* [oh-my-zsh-opera-git-plugin ★0](https://github.com/aswitalski/oh-my-zsh-opera-git-plugin) - Git aliases.
* [oh-my-zsh-reminder ★9](https://github.com/AlexisBRENON/oh-my-zsh-reminder) - A plugin which displays reminders above every prompt.
* [oh-my-zsh-virtualenv-prompt ★30](https://github.com/tonyseek/oh-my-zsh-virtualenv-prompt) - A fork of the virtualenv plugin from upstream. It adds support for customizing the virtualenv prompt in oh-my-zsh themes.
* [open-create-projects ★0](https://github.com/marcossegovia/open-create-projects) - Open/Create projects in Jetbrains.
* [opp.zsh ★222 ⏳1Y](https://github.com/hchbaw/opp.zsh) - Vim's text-objects-ish for zsh.
* [osx-dev-zsh-plugin ★7 ⏳1Y](https://github.com/marshallmick007/osx-dev-zsh-plugin) - This plugin adds some commands for maintaining various server programs on my OSX install.
* [pantheon-terminal-notify-zsh-plugin ★9 ⏳2Y](https://github.com/deyvisonrocha/pantheon-terminal-notify-zsh-plugin) - Background notifications for long running commands. Supports Elementary OS Freya.
* [pctl ★3](https://github.com/ytet5uy4/pctl) - Toggle the environment variables for proxying.
* [phpcs.plugin.zsh](https://github.com/voronkovich/phpcs.plugin.zsh) - Plugin for [PHP code sniffer ★3501](https://github.com/squizlabs/PHP_CodeSniffer).
* [phpunit.plugin.zsh ★1 ⏳1Y](https://github.com/voronkovich/phpunit.plugin.zsh) - Plugin for [PHPUnit](https://phpunit.de/).
* [pip-app ★22](https://github.com/sharat87/pip-app) - Makes it easy to install python applications into distinct virtualenvs so they don't conflict with any other python requirements on your system.
* [plugin](https://github.com/hellodarren/plugin) - Creates custom oh-my-zsh plugins from a boilerplate template. Very oh-my-zsh centric, the generated plugins will need editing to work with other frameworks.
* [pretty-time-zsh ★29](https://github.com/sindresorhus/pretty-time-zsh) - Convert seconds to a human readable string: 165392 → 1d 21h 56m 32s.
* [project ★3](https://github.com/gko/project) - Create node/python/ruby project both locally and on github(private or public repository).
* [revolver ★26](https://github.com/molovo/revolver) - A progress spinner for ZSH scripts.
* [ripz ★5](https://github.com/jedahan/ripz) - A ripgrep-powered zsh plugin alias reminder.
* [robo-zsh-plugin ★2](https://github.com/shengyou/robo-zsh-plugin) - A ZSH plugin for [Robo](http://robo.li/).
* [rockz ★2](https://github.com/aperezdc/rockz) - Lua + LuaRocks virtual environment manager based upon VirtualZ.
* [ruby-switch ★0](https://github.com/LockonS/ruby-switch) - Switch ruby versions and manage the PATH variable at the same time.
* [rvm-zsh ★1 ⏳4Y](https://github.com/johnhamelink/rvm-zsh) - Initiates RVM and adds rubygem binaries (like compass) accessible in the user's `$PATH`.
* [safe-paste ★5 ⏳2Y](https://github.com/oz/safe-paste) - A safe-paste plugin. See Conrad Irwin's [bracketed-paste](https://cirw.in/blog/bracketed-paste) blog post.
* [saneopt ★7 ⏳1Y](https://github.com/willghatch/zsh-saneopt) - Sane defaults for zsh options, in the spirit of vim-sensible.
* [schroot ★0](https://github.com/fshp/schroot.plugin.zsh) - Show current chroot name in your prompt.
* [send.zsh ★6 ⏳1Y](https://github.com/robertzk/send.zsh) - Single command to git add, git commit, and git push for much faster git workflow.
* [sensei-git ★0](https://github.com/aswitalski/oh-my-zsh-sensei-git-plugin) - Adds many git aliases and helper shell functions.
* [setenv ★3](https://github.com/kalpakrg/setenv) - Runs a script when you change directories.
* [smart-cd ★12 ⏳2Y](https://github.com/dbkaplun/smart-cd) - Runs `ls` and `git status` after chpwd.
* [snippets ★16 ⏳1Y](https://github.com/willghatch/zsh-snippets) - Command line snippet expansion.
* [solarized-man ★7](https://github.com/zlsun/solarized-man) - A modified version of oh-my-zsh's plugin colored-man-pages, optimized for solarized dark theme in terminal.
* [ssh-connect ★10](https://github.com/gko/ssh-connect) - Simple ssh manager
* [startup-timer ★5](https://github.com/paulmelnikow/zsh-startup-timer) - Print the time it takes for the shell to start up.
* [statify ★2 ⏳1Y](https://github.com/vladmrnv/statify) - Plugin that does basic statistical analysis.
* [sterror.plugin.zsh ★2 ⏳4Y](https://github.com/aphelionz/strerror.plugin.zsh) - Interprets error messages from programs and displays a human readable error message when available.
* [symfony.plugin.zsh ★1 ⏳1Y](https://github.com/voronkovich/symfony.plugin.zsh) - ZSH plugin for Symfony 2 and 3.
* [sysadmin-util ★404 ⏳1Y](https://github.com/skx/sysadmin-util) - Steve Kemp's collection of tool scripts for sysadmins.
* [terminal-workload-report ★0](https://github.com/LockonS/terminal-workload-report) - A plugin that calculates and displays how many commands have been run via terminal.
* [tipz](https://github.com/molovo/tipz) - Displays your alias if you have an alias for the command you just ran (Similar to [alias-tips ★167](https://github.com/djui/alias-tips))
* [tsm ★5](https://github.com/RobertAudi/tsm) - Adds a tmux Session Manager.
* [tumult ★38](https://github.com/unixorn/tumult.plugin.zsh) - Adds tools for OS X.
* [up.zsh ★14 ⏳1Y](https://github.com/peterhurford/up.zsh) - Adds an up command to cd multiple levels up.
* [vanilli.sh ★1](https://github.com/yous/vanilli.sh) - A lightweight start point of shell configuration.
* [vimman ★9 ⏳2Y](https://github.com/yonchu/vimman) - View vim plugin manuals (help) like man in zsh.
* [virtualenv-mod ★0](https://github.com/mattcl/virtualenv-mod) - A modified virtualenv zsh plugin for oh-my-zsh.
* [virtualz ★2](https://github.com/aperezdc/virtualz) - Python virtualenv manager inspired by Virtualfish, replaces virtualenvwrapper.
* [vox ★4 ⏳1Y](https://github.com/andrewbonnington/vox.plugin.zsh) - An oh-my-zsh plugin to control [VOX](https://coppertino.com/vox/mac), a lightweight full-featured audio player for OS X that can play a variety of formats including FLAC and Ogg Vorbis.
* [vsc ★0](https://github.com/davidtong/vsc.plugin.zsh) - Plugin for Visual Studio Code on MacOS.
* [vscode ★5](https://github.com/qianxinfeng/vscode) - Plugin for Visual Studio Code.
* [wakatime ★34](https://github.com/wbinglee/zsh-wakatime) - Automatic time tracking for commands in ZSH using [wakatime](https://wakatime.com/).
* [warhol](https://github.com/unixorn/warhol.plugin.zsh) - Configures colorization with [grc ★337](https://github.com/garabik/grc).
* [watson.zsh](https://github.com/bcho/Watson.zsh) - A plugin for [watson ★580](https://github.com/TailorDev/Watson).
* [wd ★160](https://github.com/mfaerevaag/wd) - Warp directory lets you jump to custom directories in zsh, without using cd. Why? Because cd seems inefficient when the folder is frequently visited or has a long path.
* [yeoman-zsh-plugin ★33](https://github.com/edouard-lopez/yeoman-zsh-plugin) - Edouard Lopez's Yeoman plugin for oh-my-zsh, compatible with yeoman version ≥1.0 (includes options and command auto-completion).
* [zaw ★364](https://github.com/zsh-users/zaw) - ZSH anything.el-like widget.
* [zce ★24](https://github.com/hchbaw/zce.zsh) - Vim’s EasyMotion / Emacs’s ace-jump-mode for zsh.
* [zconvey ★6](https://github.com/zdharma/zconvey) - Adds ability to send commands to other Zsh sessions, you can use this to `cd $PWD` on all active Zshells, for example.
* [zero ★11 ⏳1Y](https://github.com/arlimus/zero.zsh) - Zero is both a plugin and a theme. See the github page for installation details.
* [zgdbm ★0](https://github.com/zdharma/zgdbm) - Adds GDBM as a plugin
* [zinfo_line ★1](https://github.com/kmhjs/zinfo_line) - Makes more information available to zsh themes.
* [zredis ★0](https://github.com/zdharma/zredis) - adds Redis database support, with `database_key` <-> `shell_variable` binding. Supports all data types.
* [zsh-256color ★33 ⏳1Y](https://github.com/chrissicool/zsh-256color) - Enhances the terminal environment with 256 colors. It looks at the chosen TERM environment variable and sees if there is respective ncurses' terminfo with 256 colors available. The result is a multicolor terminal, if available.
* [zsh-abbrev-alias ★4](https://github.com/momo-lab/zsh-abbrev-alias) - Provides functionality similar to Vim's abbreviation expansion.
* [zsh-async ★136](https://github.com/mafredri/zsh-async) - Library for running asynchronous tasks in zsh without requiring any external tools.
* [zsh-autoenv ★224](https://github.com/Tarrasch/zsh-autoenv) - If a directory contains a .env file, it will automatically be executed when you cd into it.
* [zsh-autopair ★50](https://github.com/hlissner/zsh-autopair) - A ZSH plugin for auto-closing, deleting and skipping over matching delimiters.
* [zsh-autosuggestions ★2737](https://github.com/zsh-users/zsh-autosuggestions) - [Fish](https://fishshell.com/)-like fast/unobtrusive autosuggestions for zsh.
* [zsh-autoswitch-virtualenv ★35](https://github.com/MichaelAquilina/zsh-autoswitch-virtualenv) - Zsh plugin to automatically switch python virtualenvs when traversing directories.
* [zsh-basex ★2 ⏳2Y](https://github.com/dirkk/zsh-basex) - Adds several [BaseX](http://basex.org/) aliases for simplified usage.
* [zsh-bash ★13 ⏳2Y](https://github.com/chrissicool/zsh-bash) - Makes ZSH more Bash compatible. It redefines the source command to act more like Bash does. It also enables Bash completions.
* [zsh-bd ★218 ⏳1Y](https://github.com/Tarrasch/zsh-bd) - Jump back to a specific directory, without doing `cd ../../..`.
* [zsh-carthage](https://github.com/cfdrake/zsh-carthage) - Provides completions and aliases for use with [Carthage ★9468](https://github.com/Carthage/Carthage)
* [zsh-cmd-architect ★33](https://github.com/psprint/zsh-cmd-architect) - build commands from what's in history and at prompt, move, delete, add command segments and search history with multi-word queries.
* [zsh-colors ★25](https://github.com/Tarrasch/zsh-colors) - Makes it easier to colorize text from the CLI. `red foo` just works.
* [zsh-command-time ★8](https://github.com/popstas/zsh-command-time) - Show execution time for long commands in zsh and powerlevel9k.
* [zsh-completion-generator ★59](https://github.com/RobSis/zsh-completion-generator) - This plugin tries to read the list of options from the help text of programs and generate a completion function automatically. Note that this doesn't do it automatically, you have to explicitly call the generator.
* [zsh-dircolors-solarized ★21](https://github.com/joel-porquet/zsh-dircolors-solarized) - Solarized dircolors plugin.
* [zsh-directory-history ★77](https://github.com/tymm/zsh-directory-history) - A per directory history for zsh.
* [zsh-dwim ★66 ⏳2Y](https://github.com/oknowton/zsh-dwim) - zsh-dwim attempts to predict what you will want to do next. It provides a key binding (control-u) that will replace the current (or previous) command line with the command you will want to run next.
* [zsh-editing-workbench ★17](https://github.com/psprint/zsh-editing-workbench) - Adds sane, complex command line editing (e.g. incremental history _word_ completion).
* [zsh-emojis ★6](https://github.com/MichaelAquilina/zsh-emojis) - Adds numerous ascii art emojis to your environment in convenient variables.
* [zsh-favorite-directories ★5](https://github.com/seletskiy/zsh-favorite-directories) - Fast jumps to your favorite directories.
* [zsh-functional ★71 ⏳2Y](https://github.com/Tarrasch/zsh-functional) - ZSH higher order functions.
* [zsh-fuzzy-search-and-edit ★11](https://github.com/seletskiy/zsh-fuzzy-search-and-edit) - ZSH plugin for fuzzy searching files and instantly opening a matched file on matched line.
* [zsh-geeknote ★11 ⏳1Y](https://github.com/s7anley/zsh-geeknote) - Geeknote plugin for zsh.
* [zsh-git-plugin ★2 ⏳1Y](https://github.com/rcruzper/zsh-git-plugin) - Adds some functions for git.
* [zsh-git-smart-commands ★3](https://github.com/seletskiy/zsh-git-smart-commands) - Adds git commands to make some common git usages more efficient.
* [zsh-git-sync ★16](https://github.com/caarlos0/zsh-git-sync) - A ZSH plugin to sync git repositories and clean them up.
* [zsh-google-lucky ★0](https://github.com/miked0004/zsh-google-lucky) - Simple plugin to search for last command in google's "I feel lucky"
* [zsh-grunt-plugin ★8 ⏳4Y](https://github.com/clauswitt/zsh-grunt-plugin) - Add autocompletion for grunt.
* [zsh-gvm (yerinle) ★0 ⏳3Y](https://github.com/yerinle/zsh-gvm) - Provides autocompletion for gvm (Groovy enVironment Manager).
* [zsh-hints ★25 ⏳3Y](https://github.com/joepvd/zsh-hints) - Display glob and parameter flags and other non completable info right under your editing buffer.
* [zsh-histdb ★17](https://github.com/larkery/zsh-histdb) - Stores your history in an SQLite database.
* [zsh-history-substring-search ★585](https://github.com/zsh-users/zsh-history-substring-search) - Needs to be loaded after zsh-syntax-highlighting, or they'll both break. You'll also need to bind keys to its functions, details are in the README.md.
* [zsh-history ★36](https://github.com/b4b4r07/zsh-history) - Extend history so that it can be queried by SQL.
* [zsh-interactive-cd ★39](https://github.com/changyuheng/zsh-interactive-cd) - Fish like interactive tab completion for `cd`.
* [zsh-iterm-touchbar ★50](https://github.com/iam4x/zsh-iterm-touchbar) - Display iTerm2 feedback in the MacbookPro TouchBar (Current directory, git branch & status)
* [zsh-konsole-theme-changer ★0](https://github.com/rocknrollMarc/zsh-konsole-theme-changer) - Toggle konsole theme from zsh.
* [zsh-kubernetes ★0](https://github.com/Dbz/zsh-kubernetes) - Add kubernetes helper functions and aliases.
* [zsh-manydots-magic ★19 ⏳3Y](https://github.com/knu/zsh-manydots-magic) - A zle tweak for emulating `...'==`../..' etc.
* [zsh-maven-plugin ★0 ⏳1Y](https://github.com/KyleChamberlin/zsh_maven_plugin) - A fork of the oh-my-zsh maven plugin.
* [zsh-mercurial ★0](https://github.com/hcgraf/zsh-mercurial) - extracted from oh-my-zsh so you can use it without omz.
* [zsh-morpho ★5](https://github.com/psprint/zsh-morpho) - terminal screen savers written in pure Zsh, and also screen saver framework.
* [zsh-navigation-tools ★135](https://github.com/psprint/zsh-navigation-tools) - Adds `htop`-like `kill`, directory bookmarks browser, multi-word incremental history searcher and more.
* [zsh-notify ★186](https://github.com/marzocchi/zsh-notify) - A plugin for the Z shell (on OS X and Linux) that posts desktop notifications when a command terminates with a non-zero exit status or when it took more than 30 seconds to complete, if the terminal application is in the background (or the command's terminal tab is inactive).
* [zsh-nvm ★255](https://github.com/lukechilds/zsh-nvm) - Zsh plugin for installing, updating and loading nvm.
* [zsh-open-pr ★27](https://github.com/caarlos0/zsh-open-pr) - A ZSH plugin to open pull requests from command line.
* [zsh-opt-path ★2 ⏳1Y](https://github.com/jreese/zsh-opt-path) - Automatically add `~/opt` subpaths to your `$PATH`.
* [zsh-osx ★8 ⏳1Y](https://github.com/mwilliammyers/plugin-osx) - Add some common OS X related aliases and functions.
* [zsh-peco-history ★11](https://github.com/jimeh/zsh-peco-history) - Search shell history with Peco when pressing ctrl+r.
* [zsh-pg ★12](https://github.com/caarlos0/zsh-pg) - Adds utility functions to work with PosgreSQL.
* [zsh-plugin-ibtool ★0 ⏳3Y](https://github.com/RudthMael/zsh-plugin-ibtool) - Adds ibtool shortcuts to generate localized XIB files.
* [zsh-plugin-rails ★3 ⏳2Y](https://github.com/paraqles/zsh-plugin-rails) - ZSH plugin for Rails.
* [zsh-plugin-vscode ★4 ⏳1Y](https://github.com/wuotr/zsh-plugin-vscode) - Plugin for Visual Studio Code, a text editor for Mac OS X, Windows, and Linux.
* [zsh-reentry-hook ★2 ⏳1Y](https://github.com/RobSis/zsh-reentry-hook) - Plugin that re-enters working directory if it has been removed and re-created.
* [zsh-select ★4](https://github.com/psprint/zsh-select) - multi-term searched selection list with approximate matching and uniq mode.
* [zsh-sudo ★3](https://github.com/hcgraf/zsh-sudo) - the sudo plugin from oh-my-zsh, extracted to a standalone. Toggles "sudo" before the current/previous command by pressing *ESC-ESC* in emacs-mode or vi-command mode.
* [zsh-suffix-alias ★0](https://github.com/srijanshetty/zsh-suffix-alias) - Directly open files in the shell using ZSH's suffix aliases.
* [zsh-syntax-highlighting-filetypes ★53 ⏳3Y](https://github.com/trapd00r/zsh-syntax-highlighting-filetypes) - zsh syntax highlighting with dircolors in realtime.
* [zsh-syntax-highlighting ★3614](https://github.com/zsh-users/zsh-syntax-highlighting) - Add syntax highlighting to your zsh. Make sure you load this _before_ zsh-users/zsh-history-substring-search or they will both break.
* [zsh-t32 ★2 ⏳3Y](https://github.com/chrissicool/zsh-t32) - Plugin for the Lauterbach Trace32 toolset. It automatically registers fonts and sets all necessary environment variables to run the t32 toolset.
* [zsh-terminal-app](https://github.com/the8/zsh-terminal-app) - A plugin for integrating with the new El Capitan Terminal.app features.
* [zsh-titles ★14](https://github.com/jreese/zsh-titles) - Automatic window and tab titles for tmux and xterm-compatible terminals.
* [zsh-tmux-simple ★1](https://github.com/TBSliver/zsh-plugin-tmux-simple) - Simple plugin for using tmux with zsh.
* [zsh-travis ★1](https://github.com/denolfe/zsh-travis) - Opens the Travis CI page for the current repo if one exists.
* [zsh-url-highlighter ★14 ⏳1Y](https://github.com/ascii-soup/zsh-url-highlighter) - A plugin for the zsh syntax highlighter that turns URLs green if they respond with a "good" status, and red otherwise. Useful for checking URL typos.
* [zsh-viexchange ★1](https://github.com/okapia/zsh-viexchange) - Vi mode plugin for easily swapping text between two places in the buffer, like vim-exchange.
* [zsh-vim-mode ★30 ⏳4Y](https://github.com/sharat87/zsh-vim-mode) - Shrikant Sharat's bindings for zsh's vi mode so it behaves more vim-like.
* [zshmarks ★123](https://github.com/jocelynmallon/zshmarks) - A port of Bashmarks (by Todd Werth), a simple command line bookmarking plugin, for oh-my-zsh.
* [zsnapshot ★5](https://github.com/psprint/zsnapshot) - Adds command to dump the current Zsh state into a file, for later restoration by sourcing the snapshot file.
* [Ztrace ★5](https://github.com/psprint/ztrace) - Catches output of commands, allows to reuse that output, glue it with history content.
* [ZUI ★13](https://github.com/zdharma/zui) - Zsh User Interface library – CGI+DHTML-like rapid TUI application development with Zsh.

## Even more completions

These plugins add tab completion without adding extra functions or aliases.

* [autopkg-zsh-completion ★6 ⏳1Y](https://github.com/fuzzylogiq/autopkg-zsh-completion) - Completions for autopkg.
* [aws_manager_plugin ★0 ⏳1Y](https://github.com/EslamElHusseiny/aws_manager_plugin) - Add completions for the aws_manager CLI.
* [berkshelf-zsh-plugin ★16](https://github.com/berkshelf/berkshelf-zsh-plugin) - Adds tab completion for berkshelf.
* [bosh-zsh-autocompletion ★2 ⏳2Y](https://github.com/krujos/bosh-zsh-autocompletion) - Adds BOSH autocompletion.
* [brew-services ★12 ⏳2Y](https://github.com/vasyharan/zsh-brew-services) - Completion plugin for homebrew services.
* [cabal ★0 ⏳2Y](https://github.com/d12frosted/cabal.plugin.zsh) - Adds autocompletion for cabal.
* [cf-zsh-autocomplete-plugin](https://github.com/frodenas/cf-zsh-autocomplete-plugin) - Adds autocomplete for all [Cloud Foundry CLI](https://docs.cloudfoundry.org/devguide/installcf/) commands.
* [codeception-zsh-plugin ★10 ⏳1Y](https://github.com/shengyou/codeception-zsh-plugin) - Adds command completion for the Codeception Testing Framework.
* [codemachine ★3 ⏳3Y](https://github.com/CodeMonkeyMike/ZshTheme-CodeMachine) - Displays git info, whether you're logged in via ssh, return code of last command.
* [dbic ★0 ⏳3Y](https://github.com/lejeunerenard/dbic-migration-env) - Automatically sets up Environment variables for DBIx::Class::Migration's script and Dancer.
* [docker-enter-completion](https://github.com/primait/docker-enter-completion) - Command completion for [docker-enter ★1715](https://github.com/jpetazzo/nsenter).
* [docker-zsh-completion ★196](https://github.com/felixr/docker-zsh-completion) - Add completions for docker.
* [dropbox](https://github.com/horosgrisa/zsh-dropbox) - A dropbox plugin for Zsh that provides `dropbox-cli` and `dropbox-uploader` commands.
* [drush_zsh_completion ★39 ⏳1Y](https://github.com/webflo/drush_zsh_completion) - Drush autocomplete awesomeness for zsh.
* [duell](https://github.com/jcxavier/oh-my-zsh-duell) - A zsh plugin for [duell ★40](https://github.com/gameduell/duell).
* [etcdctl-zsh ★2 ⏳2Y](https://github.com/sheax0r/etcdctl-zsh) - Adds etcdctl tab completions.
* [exercism ★4 ⏳1Y](https://github.com/fabiokiatkowski/exercism.plugin.zsh) - A plugin for [exercism.io](http://exercism.io/).
* [fly-zsh-autocomplete-plugin ★0 ⏳1Y](https://github.com/Sbodiu-pivotal/fly-zsh-autocomplete-plugin) - Adds autocompletion options for all [Concourse CLI](http://concourse.ci/fly-cli.html) commands.
* [gcloud-zsh-completion ★40 ⏳2Y](https://github.com/littleq0903/gcloud-zsh-completion) - Add completions for the Google Cloud SDK.
* [gentoo-zsh-completions ★11 ⏳1Y](https://github.com/gentoo/gentoo-zsh-completions) - providing Zsh completion support to various Gentoo tools that lack completion scripts upstream.
* [git-flow-completion ★1815 ⏳1Y](https://github.com/bobthecow/git-flow-completion) - ZSH completion support for git-flow.
* [gradle-completion](https://github.com/eriwen/gradle-completion) - Bash and ZSH completion support for gradle.
* [grid5000-zsh-plugin ★2 ⏳4Y](https://github.com/pmorillon/grid5000-zsh-plugin) - Grid 5000 plugin - adds theme, autocompletions.
* [gulp-autocompletion-zsh ★10 ⏳2Y](https://github.com/srijanshetty/gulp-autocompletion-zsh) - Autocompletion for gulp.
* [gulp ★28 ⏳1Y](https://github.com/akoenig/gulp.plugin.zsh) - Autocompletion for your gulp.js tasks in the Z-Shell (zsh).
* [jumpstorm-zsh-plugin](https://github.com/netresearch/jumpstorm-zsh-plugin) - Adds autocompletion for [jumpstorm ★43 ⏳4Y](https://github.com/netresearch/jumpstorm)
* [keybase ★6 ⏳1Y](https://github.com/rbirnie/oh-my-zsh-keybase) - Completions for [keybase](https://keybase.io/docs/command_line).
* [newman](https://github.com/selop/newman-autocomplete) - Provides autocompletion for the [Newman CLI ★1769](https://github.com/postmanlabs/newman).
* [nix-zsh-completions ★31](https://github.com/spwhitt/nix-zsh-completions) - Completions for [nix](https://nixos.org/nix/), [NixOS](https://nixos.org/), and [NixOps](http://nixos.org/nixops/).
* [npm-run.plugin.zsh ★21](https://github.com/akoenig/npm-run.plugin.zsh) - Autocompletion support for `npm run`.
* [oh-my-zsh-nova ★6 ⏳2Y](https://github.com/rbirnie/oh-my-zsh-nova) - Provides auto-complete for nova.
* [oh-my-zsh-spring-boot-plugin ★8 ⏳1Y](https://github.com/linux-china/oh-my-zsh-spring-boot-plugin) - Adds autocompletions for [spring-boot](http://projects.spring.io/spring-boot/) commands.
* [oh-my-zsh_razor_plugin](https://github.com/dalang/oh-my-zsh_razor_plugin) - Provides autocomplete for [Razor ★17 ⏳3Y](https://github.com/puppetlabs/Razor).
* [parallels-zsh-plugin ★6 ⏳3Y](https://github.com/benclark/parallels-zsh-plugin) - Add completions for Parallels desktop.
* [pebble-zsh-completion ★11 ⏳1Y](https://github.com/Neal/pebble-zsh-completion) - completion script for [pebble](https://developer.getpebble.com/guides/publishing-tools/pebble-tool).
* [racket completion ★3](https://github.com/racket/shell-completion) - Completion for [Racket](http://racket-lang.org).
* [rake-completion.zshplugin ★7](https://github.com/unixorn/rake-completion.zshplugin) - Add fast tab completion for rakefile targets.
* [rancher-zsh-completion ★2](https://github.com/go/rancher-zsh-completion) - Add completions for the Rancher CLI.
* [snappy ★0](https://github.com/Arlon1/Snappy_zsh_autocompletion) - Add completions for snappy.
* [ssh-agent ★1](https://github.com/hkupty/ssh-agent) - Automatically starts `ssh-agent` to set up and load whichever credentials you want for ssh connections.
* [surf.plugin.zsh ★2 ⏳1Y](https://github.com/markussom/surf.plugin.zsh) - Add completions for surf.
* [test-kitchen-zsh-plugin ★4 ⏳2Y](https://github.com/pelletiermaxime/test-kitchen-zsh-plugin) - Add completions for [Test Kitchen](http://kitchen.ci/).
* [tmux pane words](https://gist.github.com/blueyed/6856354) - Key bindings to complete words from your tmux pane.
* [tugboat](https://github.com/DimitriSteyaert/Zsh-tugboat) - Adds autocompletion for [tugboat](https://github.com/pearkes/tugboat/) command
* [umake ★0](https://github.com/zlsun/umake) - Tab completion for Ubuntu umake
* [vert.x-omz-plugin ★0 ⏳1Y](https://github.com/davidafsilva/vert.x-omz-plugin) - Provides autocomplete features for the [vertx](http://vertx.io/) command.
* [zsh-_url-httplink ★2 ⏳4Y](https://github.com/Valodim/zsh-_url-httplink) - Extends zsh's \_urls completion, allowing it to complete urls from html pages.
* [zsh-better-npm-completion ★56](https://github.com/lukechilds/zsh-better-npm-completion) - Better completion for `npm`.
* [zsh-cabal-completion ★0 ⏳2Y](https://github.com/ehamberg/zsh-cabal-completion) - Add tab completion for cabal.
* [zsh-completions ★1597](https://github.com/zsh-users/zsh-completions) - A collection of extra completions for ZSH.
* [zsh-ipfs ★3 ⏳1Y](https://github.com/aramboi/zsh-ipfs) - Completions for the [Interplanetary File System](https://ipfs.io).
* [zsh-packer ★2](https://github.com/wakeful/zsh-packer) - Adds tab completion for packer.
* [zsh-pandoc-completion ★6 ⏳1Y](https://github.com/srijanshetty/zsh-pandoc-completion) - Pandoc completion plugin.
* [zsh-pip-completion ★10 ⏳2Y](https://github.com/srijanshetty/zsh-pip-completion) - Autocompletion plugin for pip.
* [zsh-ssh-agent ★1](https://github.com/bobsoppe/zsh-ssh-agent) - Manage ssh-agent
* [zsh.plugin.haxelib ★1](https://github.com/tong/zsh.plugin.haxelib) - Completions for haxelib.

## Themes

If you're using [Antigen](https://github.com/zsh-users/antigen), you can test these themes in a running zsh with `antigen theme githubuser/repo`. If you're using [zgen ★747](https://github.com/tarjoilija/zgen), add them to your `init.zsh` with `zgen load githubuser/reponame`.

* [aaron-zsh-theme ★3 ⏳1Y](https://github.com/aaronjamesyoung/aaron-zsh-theme) - Based on the Sorin theme.
* [abyss ★0](https://github.com/ytet5uy4/abyss.zsh) - A dark theme that includes git status information.
* [adlee](https://github.com/adlee-was-taken/oh-my-zsh-osx/blob/master/adlee.zsh-theme) - OS X theme, requires Powerline font.
* [af-magic-mod](https://raw.githubusercontent.com/desyncr/zshrc/master/themes/af-magic-mod.zsh-theme) - af-magic-mod theme. Install with `antigen theme desyncr/zshrc themes/af-magic-mod`.
* [agkozak ★0](https://github.com/agkozak/agkozak-zsh-theme) - Displays git branch and status and vi editing mode in the main prompt and also displays non-zero exit codes in zsh's right prompt. An SSH connection is indicated by the presence of a hostname in the prompt; local connections show only a username.
* [agnosterAfro](https://github.com/afrozalm/agnosterAfro) - Based on [Powerline](https://github.com/Lokaltog/vim-powerline) and [Agnoster Theme](https://gist.github.com/agnoster/3712874) and inspired by the [agnosterzak ★85](https://github.com/zakaziko99/agnosterzak-ohmyzsh-theme).
* [agnosterzak ★85](https://github.com/zakaziko99/agnosterzak-ohmyzsh-theme) - Based on Agnoster, shows battery life, date & time, git status, current directory and user & host information.
* [alien-minimal ★5](https://github.com/eendroroy/alien-minimal) - Minimalist Zsh theme with git status displayed.
* [alien ★6](https://github.com/eendroroy/alien) - Powerline-esque Zsh theme that shows git branch and the exit code of the last command.
* [alpharized ★6 ⏳2Y](https://github.com/NicoSantangelo/Alpharized) - Optimized to work with [solarized](http://ethanschoonover.com/solarized) dark. It's a modified version of the [avit theme](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/avit.zsh-theme).
* [angry fly ★2 ⏳4Y](https://github.com/russjohnson/angry-fly-zsh) - Shows git information in right hand prompt.
* [aplos](https://github.com/nostophilia/aplos) - Minimal ZSH prompt with working directory, Git local info, Git remote info, time and exit code.
* [asciigit ★0](https://github.com/cemsbr/asciigit) - An ASCII-only theme for git users who don't want to use fonts with extra glyphs.
* [avit-d2k ★6 ⏳1Y](https://github.com/fdaciuk/avit-da2k) - Based on Avit, with small changes.
* [bandit ★0](https://github.com/Holger-Will/zsh_bandit) - Another Powerline variant.
* [bashi](https://github.com/eli-oat/bashi) - Optimized for Ahmet Sülek's [Flat UI Terminal Theme](https://github.com/ahmetsulek/flat-terminal) and Pasquale D'Silva's [Saturn Terminal Theme ★69 ⏳1Y](https://github.com/psql/saturn-colors).
* [bilibili ★5](https://github.com/jingjinghack/bilibili-zshtheme) - BiliBili Theme
* [bklyn](https://github.com/gporrata/bklyn-zsh) - Variant of [Powerlevel9k ★2013](https://github.com/bhilburn/powerlevel9k) with customizations applied.
* [blinks-xfan ★1](https://github.com/ixfan/blinks-xfan) - Based on the existing theme blinks.
* [blox-zsh-theme ★9](https://github.com/yardnsm/blox-zsh-theme) - A minimal and fast ZSH theme that shows you what you need. It consists of blocks: each block is shown inside a pair of \[square brackets\], and you can add blocks by simply creating a function.
* [bluelines ★2 ⏳3Y](https://github.com/apbarrero/bluelines) - Clear and blue theme.
* [brunty ★3](https://github.com/Brunty/omz-brunty) - Brunty theme.
* [bttf-color-zsh ★1](https://github.com/yasuhiroki/bttf-color-zsh) - BTTF color theme.
* [buccaneer ★0](https://github.com/FrPas/BUCCANEER) - Shows the path to the current directory and git information.
* [bullet-train](https://github.com/caiogondim/bullet-train-oh-my-zsh-theme) - Inspired by the Powerline Vim plugin. It aims for simplicity, showing information only when it's relevant.
* [bunnyruni ★1](https://github.com/jopcode/oh-my-zsh-bunnyruni-theme) - Simple, clean, and beautiful theme.
* [bureau-colorized ★0](https://github.com/edwild22/bureau-colorized) - Based on bureau.zsh-theme, for people who use Git and NVM.
* [bureau ★12](https://github.com/isqua/bureau) - A clear and informative two-lined prompt. Includes git status optimized for large repositories.
* [candy-light ★1 ⏳3Y](https://github.com/RanaExMachina/oh-my-zsh-candy-light) - Light version of the candy theme.
* [carcassoid ★0](https://github.com/denmord/carcassoid-zsh-theme) - Easily customizable zsh theme.
* [charged ★4 ⏳3Y](https://github.com/robwierzbowski/charged-zsh-theme) - A zsh prompt optimized for the solarized dark terminal theme.
* [chi](https://github.com/andela-abankole/chi) - A zsh theme optimized for iTerm users on OS X.
* [ciacho ★1 ⏳1Y](https://github.com/Ciacho/ciacho-ohmyzsh-theme) - Based on Agnoster
* [classyTouch ★15](https://github.com/yarisgutierrez/classyTouch_oh-my-zsh) - Minimal, clean theme with git support.
* [clean ★0](https://github.com/akz92/clean) - Minimalist zsh theme.
* [cloudy ★21](https://github.com/Huvik/Cloudy) - Minimal cloudy zsh theme.
* [cmder ★4](https://github.com/potasiyam/cmder-zsh-theme) - A zsh theme that matches the theme of Cmder, a popular terminal emulator for windows.
* [cobalt2 ★518](https://github.com/wesbos/Cobalt2-iterm) - Wes Bos' Cobalt 2 theme for ZSH and iTerm 2.
* [codemachine ★3 ⏳3Y](https://github.com/CodeMonkeyMike/ZshTheme-CodeMachine) - Codemachine theme.
* [cordial ★8](https://github.com/stevelacy/cordial-zsh-theme) - Clean and effective zsh theme with git and npm support.
* [cute-theme ★14 ⏳2Y](https://github.com/dogrocker/oh-my-zsh-powerline-cute-theme) - An OSX oh-my-zsh shell theme with Cute emoji based on the Powerline Vim plugin.
* [darkblood-modular ★0 ⏳2Y](https://github.com/InAnimaTe/darkblood-modular) - This version of the popular [darkblood](https://github.com/BinaryMuse/oh-my-zsh/blob/binarymuse/themes/darkblood.zsh-theme) theme has been enhanced with a near complete rewrite enabling modularity and a few new features.
* [delta-prompt ★2](https://github.com/cusxio/delta-prompt) - A minimal Zsh prompt.
* [dexter ★1](https://github.com/shvenkat/zsh-theme-dexter) - A theme with an emphasis on the right side (hence the name) of the terminal.
* [dissonance ★0](https://github.com/RyanScottLewis/theme-dissonance-zsh) - Comes with custom LSCOLORS and LS_COLORS settings files, works with both dark and light terminal themes.
* [dmx ★1](https://github.com/domix/dmx.zsh-theme) - Optimized for dark terminal windows.
* [dracula ★14](https://github.com/dracula/zsh) - A dark theme for Atom, Alfred, Chrome DevTools, iTerm, Sublime Text, Textmate, Terminal.app, Vim, Xcode, Zsh.
* [dragon ★3](https://github.com/sabertazimi/dragon-zsh-theme) - Minimalistic, includes git status information.
* [endless-dog ★0](https://github.com/qwelyt/endless-dog) - OMZ theme that mimics grml-zsh-config.
* [enkel ★0](https://github.com/SShrike/enkel) - A simple and minimalistic theme for ZSH and the Solarised colour scheme featuring Git support and a few other semi-useful features such as displaying exit codes, the current system time, whether or not you have write permissions to the current directory, etc.
* [excess ★0 ⏳1Y](https://github.com/davydovanton/excess.zsh-theme) - Simple zsh color theme.
* [feder](https://github.com/samfeder/feder.zsh-theme/blob/master/feder.zsh-theme) - Clean, simple, compatible and meaningful. Tested on Linux, Unix and Windows under ANSI colors.
* [filthy ★11](https://github.com/molovo/filthy) - A disgustingly clean ZSH prompt
* [fishy ★1](https://github.com/akinjide/fishy2) - ZSH theme inspired by [original fishy](https://github.com/robbyrussell/oh-my-zsh/wiki/themes#fishy)
* [friendly-fiesta ★0](https://github.com/bruino/friendly-fiesta) - Fork of terminal-party theme.
* [frisk-arrow ★0 ⏳3Y](https://github.com/BakeRolls/frisk-arrow) - A theme based on the [frisk](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/frisk.zsh-theme) oh-my-zsh-theme.
* [frisk-red](https://github.com/aishsingh/zsh/tree/master/frisk-red) - Red version of the frisk theme from oh-my-zsh.
* [frlo ★1 ⏳4Y](https://github.com/fiorillo/frlo) - Uses your computer's hostname to come up with a (hopefully) unique three-color theme to display in your prompt, so you know at a glance which machine you're logged into.
* [furio ★16 ⏳2Y](https://github.com/hectorpalmatellez/furio-theme) - Fork of the Cloud oh-my-zsh theme. with different colors and emojis.
* [garrett ★86](https://github.com/chauncey-garrett/zsh-prompt-garrett) - Prezto prompt with the information you need the moment you need it.
* [gawaine ★3 ⏳5Y](https://github.com/nicolaracco/gawaine.zsh-theme) - Nicola Racco's theme. Requires rvm & git plugins.
* [geometry](https://github.com/frmendes/geometry) - A minimal ZSH theme based on Avit and Pure that displays a lot of git information.
* [geometryHostInfo](https://github.com/Fuzen-py/GeometryHostInfo) Adds host info to the [geometry](https://github.com/frmendes/geometry) theme.
* [girazz ★0 ⏳1Y](https://github.com/mdentremont/girazz) - A modification to the gnzh theme which adds VI mode to the right prompt.
* [gitsome](https://github.com/mtully/gitsome) - Super simple prompt with git info, optimized for the [Flat Terminal ★502 ⏳4Y](https://github.com/ahmetsulek/flat-terminal) color scheme.
* [gitster](https://github.com/shashankmehta/dotfiles/blob/master/thesetup/zsh/.oh-my-zsh/custom/themes/gitster.zsh-theme) - When in a git repo, it shows the location from the git's root folder. When not in a git repo, it shows the path relative to home, `~`.
* [glimmer ★1 ⏳1Y](https://github.com/martnu/glimmer) - Includes git branch, time and user@host.
* [hacker-quotes ★10](https://github.com/oldratlee/hacker-quotes) - Outputs a hacker quote randomly when you open a terminal.
* [hackersaurus](https://github.com/bhilburn/hackersaurus) - A theme with git status and exit code of last command run embedded in the prompt. Related to [powerlevel9k ★2013](https://github.com/bhilburn/powerlevel9k).
* [haribo ★3 ⏳1Y](https://github.com/haribo/omz-haribo-theme) - Simple git status + timestamp in prompt.
* [hedgehog](https://gist.github.com/hedgehog1029/dfbb7e66511e2c399157) - Simple, no-nonsense and clean, with support for git and return codes.
* [honukai-iterm-zsh ★790](https://github.com/oskarkrawczyk/honukai-iterm-zsh) - Honukai theme and colors for oh-my-zsh and iTerm.
* [horizontal ★0](https://github.com/nuimk/horizontal) - Two line prompt with a horizontal separator.
* [horse-sh ★0 ⏳2Y](https://github.com/emileswarts/horse-sh) - A very minimal brown/red zsh theme.
* [hub](https://gist.github.com/hub23/c226b1c77446e099f7684b0d21c6b22a) - Simple and clean, includes the return code of the last command executed.
* [hyperzsh ★157](https://github.com/tylerreckart/hyperzsh) - Gives you a comprehensive overview of the branch you're working on and the status of your repository without cluttering your terminal.
* [iggy ★11 ⏳2Y](https://github.com/eugenk/zsh-prompt-iggy) - A super happy awesome Powerline-style, Git-aware **prezto only** theme.
* [igorsilva ★2 ⏳1Y](https://github.com/igor9silva/zsh-theme) - Shows current directory, customizable delimiter, current branch, git status.
* [infoline ★0](https://github.com/hevi9/infoline-zsh-theme) - Clean theme that shows git status, background jobs, remote host, and other information.
* [intheloop-powerline ★0 ⏳2Y](https://github.com/zyphrus/intheloop-powerline) - An extension of the intheloop theme to use powerline fonts.
* [itg ★28 ⏳1Y](https://github.com/itsthatguy/itg.zsh-theme) - itsthatguy's theme.
* [jcl-zsh-theme ★2 ⏳3Y](https://github.com/jasonlewis/jcl-zsh-theme) - Loosely based on the ys theme.
* [judgedim ★0 ⏳2Y](https://github.com/judgedim/oh-my-zsh-judgedim-theme) - Minimalist prompt.
* [keloran ★0](https://github.com/Keloran/keloran.zsh-theme) - Theme that includes a few features from other themes
* [kimwz ★3](https://github.com/kimwz/kimwz-oh-my-zsh-theme) - Minimal theme.
* [kketcham ★0 ⏳2Y](https://github.com/prototype27/kketcham) - Theme with nifty colors on the git info.
* [klendathu ★0 ⏳1Y](https://github.com/kegonomics/klendathu) - Uses Powerline iconsolas.
* [lagune ★0](https://github.com/noplay/lagune) - a minimal zsh theme.
* [lambda-pure ★22](https://github.com/marszall87/lambda-pure) - A minimal zsh theme, based on Pure, with added NodeJS version.
* [lambda ★242](https://github.com/halfo/lambda-mod-zsh-theme) - A zsh theme optimized for git users who use unicode-compatible fonts and terminal applications.
* [lazyprodigy ★0 ⏳3Y](https://github.com/drewlustro/lazyprodigy-zsh-theme) - Optimized for dark terminals, has variants for local and remote systems.
* [lime ★10 ⏳1Y](https://github.com/yous/lime) - Simple standalone Zsh theme.
* [linuxer ★0](https://github.com/patrick330602/linuxer) - Inspired by Yaris Alex Gutierrez's classyTouch, Yad Smood's ys, and Bureau theme.
* [liquidprompt ★3076](https://github.com/nojhan/liquidprompt) - A full-featured & carefully designed adaptive prompt for Bash & ZSH.
* [lone-star](https://github.com/designfrontier/lonestar-zsh-theme/blob/master/lone-star.zsh-theme) - Texas-themed theme based on Sindre Sorhus' pure theme.
* [magico ★0](https://github.com/IOsonoTAN/magico) - IOsonoTAN's magico theme.
* [mau ★0](https://github.com/vichargrave/mau) - A Zsh theme with a cat twist.
* [maxulysse/myzsh ★1](https://github.com/MaxUlysse/myzsh) - Maxime Garcia's myzsh theme.
* [megaprompt](https://github.com/willghatch/zsh-megaprompt) - A maximalist prompt including keyboard mode, ownership info, and other contextual info, with λ as the prompt character. Requires the [hooks ★14 ⏳1Y](https://github.com/willghatch/zsh-hooks) plugin.
* [min ★4](https://github.com/andrepolischuk/min) - A minimalistic ZSH prompt.
* [mindful-space ★2 ⏳2Y](https://github.com/syndbg/mindful-space-zsh-theme) - ZSH theme with space in mind.
* [minimal ★47](https://github.com/S1cK94/minimal) - S1ck94's minimal theme.
* [misa ★1 ⏳3Y](https://github.com/misalabs/misa.zsh-theme) - Misalabs' zsh theme.
* [mixed](https://github.com/dnavtoparts/mixed-zsh-theme) - Optimized for Dark Background.
* [molokai-powerline-zsh ★5 ⏳1Y](https://github.com/prikhi/molokai-powerline-zsh) - Based on [agnoster](https://gist.github.com/agnoster/3712874).
* [multi-shell-repo-prompt ★11 ⏳2Y](https://github.com/dotcode/multi-shell-repo-prompt) - Provides useful information (in your prompt) about the repository that you are in. It currently works for [Git](http://git-scm.com/) and [Mercurial](https://www.mercurial-scm.org/), under [zsh](http://en.wikipedia.org/wiki/Zsh) as well as [bash](http://en.wikipedia.org/wiki/Bash_%28Unix_shell%29).
* [muslim ★1](https://github.com/nksoff/muslim) - A simple minimal zsh prompt theme.
* [nanofish ★1 ⏳1Y](https://github.com/tweekmonster/nanofish) - Adds fish-style directory prompt to nanotech theme.
* [neat](https://github.com/andrepolischuk/neat) - Minimalistic prompt inspired by [odin](https://github.com/tylerreckart/Odin) and [pure ★3386](https://github.com/sindresorhus/pure).
* [nextbike ★0](https://github.com/meierjan/nextbike-zsh-theme) - A very basic theme which just features an osx bike icon.
* [ningxia ★0 ⏳2Y](https://github.com/wangyandong-ningxia/ningxia.zsh-theme) - Based on af-magic.
* [nknu ★0](https://github.com/aanc/oh-my-zsh-nknu-theme) - A simple OMZ theme.
* [nodeys ★20 ⏳1Y](https://github.com/marszall87/nodeys-zsh-theme) - Based on ys theme, with added NodeJS version (from NVM plugin).
* [nt9 ★13](https://github.com/lenguyenthanh/nt9-oh-my-zsh-theme) - Clean, distraction free and git focused development theme. Shows path relative to git root (or ~ when outside git repo), time since last commit, current SHA, branch and branch state.
* [odin ★63](https://github.com/tylerreckart/odin) - Odin is a git-flavored zsh theme.
* [oh-my-git ★2489](https://github.com/arialdomartini/oh-my-git) - An opinionated prompt for bash and zsh.
* [oh-my-via ★5](https://github.com/badouralix/oh-my-via) - Theme for ZSH which mainly forks the historical theme used on VIA servers.
* [oh-my-zsh-node-theme ★26 ⏳1Y](https://github.com/skuridin/oh-my-zsh-node-theme) - OMZ's node theme.
* [oh-my-zsh-robbl ★5 ⏳5Y](https://github.com/robbl/oh-my-zsh-config) - Shows the git/svn status including the time since last commit, rvm status in prompt.
* [omz-vira ★0](https://github.com/FernandoTorres/omz-vira) - An update of the bira theme that shows the vim bindkey -v status.
* [ozono ★5](https://github.com/sfabrizio/ozono-zsh-theme) 🌏 OZ0NO - Let's Breathe a clean ZSH.
* [pad ★2](https://github.com/eproxus/pad.zsh-theme) - A concise and colorful oh-my-zsh theme.
* [phi φ](https://github.com/LasaleFamine/phi-zsh-theme) - A clean and simple theme for ZSH inspired and forked from [Lambda (Mod) ZSH Theme ★242](https://github.com/halfo/lambda-mod-zsh-theme).
* [planet](https://github.com/aphlor/planet-zsh) - A slimmed down version of [steef](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/steeef.zsh-theme) from [oh-my-zsh ★54129](https://github.com/robbyrussell/oh-my-zsh).
* [platypus ★0 ⏳2Y](https://github.com/fdv/platypus) - Platypus is a simple and convenient theme for oh-my-zsh used by Frédéric de Villamil.
* [poncho ★4 ⏳1Y](https://github.com/RainyDayMedia/oh-my-zsh-poncho) - RDM's basic oh-my-zsh custom theme.
* [powerless ★9](https://github.com/martinrotter/powerless) - Tiny & simple pure ZSH prompt inspired by powerline.
* [powerlevel9k ★2013](https://github.com/bhilburn/powerlevel9k) - A very flexible theme based on the well-known agnoster-theme with support for various VCS, AWS, rbenv, virtualenv, etc.
* [powerline-cute](https://github.com/dogrocker/oh-my-zsh-powerline-cute-theme) - Based on [bullet-train](https://github.com/caiogondim/bullet-train-oh-my-zsh-theme).
* [powerline ★0](https://github.com/syui/powerline.zsh) - A git aware powerline theme.
* [powerzeesh ★0](https://github.com/sevaho/Powerzeesh) - A Powerline based zsh theme. It aims for simplicity, showing information only when it's relevant, optimized for speed and look.
* [pre-theme ★27](https://github.com/leandromatos/pre-theme) - A collection of themes for Sublime Text, Terminal, iTerm2 and zsh.
* [predawn-shell ★21](https://github.com/jamiewilson/predawn-shell) - Theme for dark terminal themes.
* [prezto-cloud-prompt ★0 ⏳2Y](https://github.com/klaude/prezto-cloud-prompt) - Prezto port of oh-my-zsh's cloud prompt.
* [prezto-lambda ★0 ⏳2Y](https://github.com/nixolas1/prezto-lambda) - Lambda theme (for prezto).
* [prezto_powerline ★97](https://github.com/davidjrice/prezto_powerline) - Powerline for prezto. Shows git information, RVM version.
* [punctual](https://github.com/dannynimmo/punctual-zsh-theme) - Easily customizable, influenced by [spaceship ★844](https://github.com/denysdovhan/spaceship-zsh-theme).
* [pure ★3386](https://github.com/sindresorhus/pure) - Pretty, minimal and fast ZSH prompt.
* [purity](https://github.com/pmbenjamin/purity) - Inspired by robbyrussell theme + pure prompt.
* [racotecnic ★5](https://github.com/elboletaire/zsh-theme-racotecnic) - Based on af-magic and posh-git.
* [radium ★1](https://github.com/dimitardimitrov/radium) - Designed for dark terminals, (works best with Solarized iTerm2 theme) (prezto).
* [raincoat](https://github.com/ginfuru/RainCoat) - A simple omz-compatible theme with a corresponding iTerm2 color scheme.
* [random-emoji](https://gist.github.com/oshybystyi/2c30543cd48b2c9ecab0) - Random emoji.
* [remiii ★5 ⏳4Y](https://github.com/Remiii/remiii.zsh-theme) - Based on agnoster, optimized for solarized terminal themes.
* [rummik/zsh-theme ★0](https://github.com/rummik/zsh-theme) - Rummik's theme.
* [rzh ★1](https://github.com/patwhatev/rzh) - Theme with git states indicated by emojis.
* [schminitz](https://gist.github.com/schminitz/9931af23bbb59e772eec) - Shows if Vim is running in the background when using `:sh` command.
* [seeker ★43](https://github.com/tonyseek/oh-my-zsh-seeker-theme) - This theme uses many special unicode characters to be fancy, but it may cause some problems without well supported fonts.
* [sepshell ★8](https://github.com/sepehr/sepshell) - Clean and minimal zsh theme based on the old lost taybalt theme.
* [sfz ★0](https://github.com/mreinhardt/sfz-prompt.zsh) - An evolution of lean prompt which itself is a rewrite of pure.
* [shellder ★129](https://github.com/simnalamburt/shellder) - Minimal theme with git branch display. Requires a powerline font.
* [sinon ★0 ⏳2Y](https://github.com/k-kinzal/oh-my-zsh-sinon-theme) - k-kinzal's sinon theme.
* [sk9-zsh ★0 ⏳2Y](https://github.com/skeiter9/sk9-zsh) - Skeiter9's zsh theme.
* [skeletor-syntax ★11](https://github.com/ramonmcros/skeletor-syntax) - Theme collection for Atom, Prism and Zsh inspired by Skeletor from He-Man and the Masters of the Universe.
* [slimline ★15](https://github.com/mgee/slimline) - Minimal, fast and elegant ZSH prompt. Displays the right information at the right time.
* [smiley ★4 ⏳3Y](https://github.com/gsamokovarov/smiley.zsh-theme) - A prompt with happy and sad faces.
* [solarized-powerline ★5](https://github.com/houjunchen/solarized-powerline) - Solarized powerline-style theme for zsh.
* [solarizsh ★3 ⏳5Y](https://github.com/paddykontschak/Solarizsh) - Color fix for robbyrussell's oh-my-zsh theme to work with [Solarized](http://ethanschoonover.com/solarized).
* [spaceship ★844](https://github.com/denysdovhan/spaceship-zsh-theme) - A zsh theme with git, nvm, rvm/rbenv/chruby, python, ssh and other useful indicators.
* [spowerline](https://mbauhardt.github.io/spowerline/) - Written in scala, inspired by agnoster, tmux powerline, vim powerline and the vim status plugin.
* [staples ★0](https://github.com/dersam/staples) - based on bureau, displays user@host if connected through SSH.
* [statusline ★34](https://github.com/el1t/statusline) - A responsive zsh theme that provides informational segments when you need them.
* [sugarfree](https://github.com/cbrock/sugar-free) - Based on the [Pure ★3386](https://github.com/sindresorhus/pure) and [Candy](https://github.com/BinaryMuse/oh-my-zsh/blob/binarymuse/themes/candy.zsh-theme) themes.
* [tahuri ★0 ⏳1Y](https://github.com/Tahuri/oh-my-zshel-theme-tahuri) - Zsh theme for Arch Linux.
* [termuxer ★0](https://github.com/patrick330602/termuxer) - Theme inspired by agnoster and linuxer.
* [the-time-lord ★0 ⏳2Y](https://github.com/jhwhite/the-time-lord) - A theme based on gallifrey.
* [theme-line ★3](https://github.com/yw9381/oh-my-zsh_theme_line) - Colorful theme with Git status.
* [tq ★0](https://github.com/kitian616/tq-zsh-theme) - Displays git status, time, requires a Powerline font.
* [trajan ★1 ⏳4Y](https://github.com/denisinla/trajan-zsh-theme) - A dark theme for ZSH.
* [trinity](https://github.com/de-luca/Trinity) - A simple theme based on [geometry](https://github.com/frmendes/geometry).
* [tvline ★2 ⏳2Y](https://github.com/thvitt/tvline) - Derived from [agnoster's theme](https://gist.github.com/agnoster/3712874), adds powerline font enhancements.
* [ultimate](https://github.com/b4b4r07/ultimate) - Minimalist theme forked from [S1cK94/minimal ★47](https://github.com/S1cK94/minimal).
* [vinhnx ★7 ⏳3Y](https://github.com/vinhnx/vinhnx.zsh-theme) - Modified from themes/mgutz.zsh-theme.Looks great when using with Solarized color scheme.
* [wang-iterm-zsh ★5](https://github.com/0532/wang-iterm-zsh) - Based on the 0532 theme.
* [wild-cherry ★281](https://github.com/mashaal/wild-cherry) - A fairy-tale inspired theme for Zsh, iTerm, Sublime, Atom, & Mou.
* [work-line ★4](https://github.com/afnizarnur/work-line) - Theme with nice emojis.
* [xremix ★1 ⏳1Y](https://github.com/xremix/oh-my-zsh-xremix-theme) - An oh-my-zsh shell theme based on the Jreese theme plugin.
* [xxf](https://gist.github.com/xfanwu/18fd7c24360c68bab884) - Shows Current commit shorten hash and message.
* [yairshefi ★0](https://github.com/yaireclipse/yairshefi-ohmyzsh-theme) - Minimal theme with line separated prompts.
* [ykmam](https://github.com/julienvanderkluft/ykmam-zsh-theme/blob/master/ykmam.zsh-theme) - Modified from ys theme. Optimized for a dark background.
* [ys ★0](https://github.com/cristiancavalli/ys-zsh-custom-theme) - Clean, simple, compatible and meaningful theme meant for dark backgrounds.
* [yuki ★1](https://github.com/yuki-torii/yuki-zsh-theme) - A dark optimized ZSH theme.
* [z4rr3t ★1 ⏳2Y](https://github.com/inimicus/z4rr3t) - Based on sindresorhus' pure theme.
* [zemm-blinks ★8 ⏳2Y](https://github.com/aranasaurus/zemm-blinks.zsh-theme) - Customized version of oh-my-zsh blinks with mercurial support and other changes.
* [zero ★11 ⏳1Y](https://github.com/arlimus/zero.zsh) - Zero's theme & plugin.
* [zeta ★42](https://github.com/skylerlee/zeta-zsh-theme) - Shows username, git information, machine name, current working directory.
* [zsh-blackrain ★4](https://github.com/ginfuru/zsh-blackrain) - Another git-aware theme.
* [zsh-megaprompt](https://github.com/willghatch/zsh-megaprompt) - A maximalist prompt including keyboard mode, ownership info, and other contextual info, with λ as the prompt character. Requires the [hooks ★14 ⏳1Y](https://github.com/willghatch/zsh-hooks) plugin.
* [zsh-prompt-powerline ★46 ⏳1Y](https://github.com/Valodim/zsh-prompt-powerline) - A fairly heavyweight zsh prompt, based on the powerline font from the popular eponymous vim plugin, which works well for a dark background.
* [zsh-theme-nerdish ★2](https://github.com/nyarla/zsh-theme-nerdish) - A prompt theme for zsh with Nerd Fonts.
* [zsh2000](https://github.com/maverick2000/zsh2000) - Powerline looking ZSH theme with rvm prompt, git status and branch, current time, user, hostname, pwd, exit status, root and background job status.
* [zshcomrade ★4 ⏳4Y](https://github.com/landongn/zshcomrade) - A ZSH theme, comrade!
* [zwsh ★0](https://github.com/naens/zwsh) - A Zpm3/Wordstar mode/theme for zsh

### Fonts

Some of the themes listed here require Powerline-compatible fonts, here are a few:

* [Awesome Terminal Fonts ★897](https://github.com/gabrielelana/awesome-terminal-fonts) - A family of fonts that includes some nice monospaced Icons.
* [Fantasque Awesome Font ★17 ⏳2Y](https://github.com/ztomer/fantasque_awesome_powerline) - A nice monospaced font, patched with Font-Awesome, Octoicons and Powerline-Glyphs.
* [Fantasque-sans ★3142](https://github.com/belluzj/fantasque-sans) - Another powerline font.
* [Hack](http://sourcefoundry.org/hack/) - Another Powerline-compatible font designed specifically for source code.
* [Input Mono](http://input.fontbureau.com/) - A family of fonts designed specifically for code. It offers both monospaced and proportional fonts and includes powerline glyphs.
* [Monoid](http://larsenwork.com/monoid/) - Monoid is customizable and optimized for coding with bitmap-like sharpness at 15px line-height even on low res displays.
* [nerd fonts ★4354](https://github.com/ryanoasis/nerd-fonts) - Collection of over 20 patched fonts (over 2,000 variations) & FontForge font patcher python script for Powerline, Font Awesome, Octicons, Devicons, and Vim Devicons. Includes: Droid Sans, Meslo, Source Code, AnonymousPro, Hack, ProFont, Inconsolata, and many more.
* [Powerline patched font collection ★8286](https://github.com/powerline/fonts) - A collection of a dozen or so fonts patched to include powerline gylphs.
* [Terminus](http://files.ax86.net/terminus-ttf/) - TTF version of Terminus that includes powerline glyphs.

## Installation

### [Antigen ★3160](https://github.com/zsh-users/antigen)

Most of these plugins can be installed by adding `antigen bundle githubuser/reponame` to your .zshrc file. Antigen will handle cloning the plugin for you automatically the next time you start zsh. You can also add the plugin to a running zsh with `antigen bundle githubuser/reponame` for testing before adding it to your `.zshrc`.

### [dotzsh ★129](https://github.com/dotphiles/dotzsh)

1. Clone new plugins into `.zsh.local/modules`
2. Load the plugin module in `.zshrc`
3. Open a new zsh terminal window or tab

### [Oh-My-Zsh](http://ohmyz.sh/)

1. `cd ~/.oh-my-zsh/custom/plugins`
2. `git clone repo`
3. Add the repo to your plugin list

### [Prezto ★7609](https://github.com/sorin-ionescu/prezto)

1. Clone the plugin into your prezto modules directory
2. Add the plugin to your `.zpreztorc` file
3. Open a new terminal window or tab

### [Zgen ★747](https://github.com/tarjoilija/zgen)

Most of these plugins can be installed by adding `zgen load githubuser/reponame` to your .zshrc file in the same function you're doing your other `zgen load` calls in. Zgen will automatically clone the repositories for you when you do a `zgen save`.

### [zplug ★1558](https://github.com/zplug/zplug)

Most of these plugins can be installed by adding `zplug "githubuser/reponame"` to your .zshrc file.

## Writing New Plugins

I've documented some recommendations for writing a new plugin [here](https://github.com/unixorn/awesome-zsh-plugins/blob/master/Writing_Plugins.md).

## Other Resources

### ZSH Tools

* [zshdb ★108](https://github.com/rocky/zshdb) - A ZSH debugger
* [zunit ★22](https://github.com/molovo/zunit) - A powerful unit testing framework for ZSH

### Other Useful Lists

* [awesome-devenv ★782](https://github.com/jondot/awesome-devenv) - A curated list of awesome tools, resources and workflow tips making an awesome development environment
* [awesome-sysadmin ★5229](https://github.com/n1trux/awesome-sysadmin) - A curated list of awesome open source sysadmin resources
* [Terminals Are Sexy ★4808](https://github.com/k4m4/terminals-are-sexy) - A curated list for CLI lovers.

Find other useful awesome-* lists at the [awesome collection ★59088](https://github.com/sindresorhus/awesome)

### Other References

The [Zsh Reference Card](http://www.bash2zsh.com/zsh_refcard/refcard.pdf) and [zsh-lovers site](http://grml.org/zsh/zsh-lovers.html) are indispensable.
---
<p align="center">
	This list is a copy of <a href="https://github.com/unixorn/awesome-zsh-plugins">unixorn/awesome-zsh-plugins</a> with ranks
</p>

<script>
  (function(i,s,o,g,r,a,m){i['GoogleAnalyticsObject']=r;i[r]=i[r]||function(){
  (i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),
  m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)
  })(window,document,'script','https://www.google-analytics.com/analytics.js','ga');

  ga('create', 'UA-100705027-1', 'auto');
  ga('send', 'pageview');

</script>
