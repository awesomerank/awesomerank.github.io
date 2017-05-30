<h1 align="center">
Ranked awesome lists, all in one place
</h1>
<p align="center">
	This list is a copy of <a href="webpro/awesome-dotfiles">webpro/awesome-dotfiles</a> with ranks
</p>
---
# Awesome dotfiles

A curated list of dotfiles resources. Inspired by the [awesome ★59088](sindresorhus/awesome) list thing.

## Articles

### Introductions

* [Getting started with dotfiles](https://medium.com/@webprolific/getting-started-with-dotfiles-43c3602fd789) ([L. Kappert](https://github.com/webpro))
* [Getting started with dotfiles](https://driesvints.com/blog/getting-started-with-dotfiles/) ([D. Vints](https://github.com/driesvints))
* [Managing your dotfiles](https://medium.com/@webprolific/managing-your-dotfiles-7d2725297304)
* [Dotfiles Are Meant to Be Forked](https://zachholman.com/2010/08/dotfiles-are-meant-to-be-forked/)
* [Dotfile discovery](https://wynnnetherland.com/journal/dotfiles-discovery/)

### Tutorials

* [Setting up a new (OS X) development machine: Part 3 - Dotfiles and custom SSH config](https://mattstauffer.co/blog/setting-up-a-new-os-x-development-machine-part-3-dotfiles-rc-files-and-ssh-config)
* [Setting Up a Mac Dev Machine From Zero to Hero With Dotfiles](https://code.tutsplus.com/tutorials/setting-up-a-mac-dev-machine-from-zero-to-hero-with-dotfiles--net-35449) - [Part 2](https://code.tutsplus.com/tutorials/setting-up-a-mac-dev-machine-from-zero-to-hero-with-dotfiles-part-2--cms-23145)
* [Using Git and GitHub to manage your dotfiles](http://blog.smalleycreative.com/tutorials/using-git-and-github-to-manage-your-dotfiles/)
* [conf.d like directories for zsh/bash dotfiles](https://chr4.org/blog/2014/09/10/conf-dot-d-like-directories-for-zsh-slash-bash-dotfiles/)
* [Managing your dotfiles](http://www.anishathalye.com/2014/08/03/managing-your-dotfiles/)

### Shell startup

* [Shell startup scripts](http://blog.flowblok.id.au/2013-02/shell-startup-scripts.html)
* [Zsh/Bash startup files loading order](https://shreevatsa.wordpress.com/2008/03/30/zshbash-startup-files-loading-order-bashrc-zshrc-etc/)

### Using specific tools

* [Using GNU Stow to manage your dotfiles](http://brandon.invergo.net/news/2012-05-26-using-gnu-stow-to-manage-your-dotfiles.html)
* [Managing dotfiles with GNU Stow](https://taihen.org/managing-dotfiles-with-gnu-stow/)
* [Managing Dotfile Symlinks with GNU Stow](https://spin.atomicobject.com/2014/12/26/manage-dotfiles-gnu-stow/)
* [Managing dot-files with vcsh and myrepos](http://blog.tfnico.com/2014/03/managing-dot-files-with-vcsh-and-myrepos.html)
* [Manage dotfiles using vcsh and mr](https://www.kunxi.org/blog/2014/02/manage-dotfiles-using-vcsh-and-mr/)
* [Dotfiles and dev tools provisioned by Ansible](http://palcu.blogspot.nl/2014/06/dotfiles-and-dev-tools-provisioned-by.html)
* [Manage a development machine with Ansible](http://kreusch.com.br/blog/2013/12/03/manage-a-development-machine-with-ansible)

## Find dotfiles repos

There are many great dotfiles repos out there, each containing their own inspiration and gems. I think one of the best ways to go through them is by [searching GitHub for "dotfiles"](https://github.com/search?q=dotfiles&type=Repositories).

Also see:

* [Google for "dotfiles"](https://www.google.nl/search?q=dotfiles)
* [Archlinux collection](https://wiki.archlinux.org/index.php/Dotfiles)
* Tip: search for a filename on GitHub, e.g. [in:path .gitconfig](https://github.com/search?utf8=%E2%9C%93&type=Code&q=in%3Apath+.gitconfig).

## Example dotfiles repos

A collection of the most popular, well-maintained, and collaborative dotfiles repositories & frameworks. Some projects contain just the dotfiles. Others go further by allowing you to easily add your own custom dotfiles, and/or including scripts to manage dotfiles/plugins.

### Bash

Title | Description | Focus
:--|:--|:--
[Bash it ★6230](Bash-it/bash-it) | Community bash framework. | Autocompletion, themes, aliases, custom functions. Well-structured framework.
[Mathias’s dotfiles](https://github.com/mathiasbynens/dotfiles) | Sensible hacker defaults for macOS | Lots of goodness here, great collaborative community effort.
[Maximum Awesome ★4709](square/maximum-awesome) | Config files for vim and tmux | Vim, tmux. Built for Mac OS X.
[dev-setup ★2783](donnemartin/dev-setup) | Mac OS X development environment setup | Extensive setup of developer tools on OS X.
[webpro's dotfiles ★182](webpro/dotfiles) | macOS dotfiles | Bash, Homebrew, Brew Cask, Git, Node.js, Hammerspoon.

### Zsh

Title | Description | Focus
:--|:--|:--
[thoughtbot dotfiles](https://github.com/thoughtbot/dotfiles) | Set of vim, zsh, git, and tmux configuration files | Zsh, vim, tmux, git, homebrew. Uses [rcm ★1528](thoughtbot/rcm).
[oh-my-zsh](http://ohmyz.sh/) | Community-driven framework for managing your zsh configuration. | Includes 200+ optional plugins (rails, git, OSX, hub, capistrano, brew, ant, php, python, etc), over 140 themes to spice up your morning, and an auto-update tool.
[Prezto ★7609](sorin-ionescu/prezto) | The configuration framework for Zsh. | Enriches the command line interface environment with sane defaults, aliases, functions, auto completion, and prompt themes.
[YADR](http://skwp.github.io/dotfiles/) | The best vim, git, zsh plugins and the cleanest vimrc you've ever seen | Homebrew, zsh, git, vim, and more. Active repository.
[holman does dotfiles ★4476](holman/dotfiles) | holman does dotfiles | Organized well around topics. Author wants it to work for everyone.
[antigen](http://antigen.sharats.me/) | Plugin manager for zsh, inspired by oh-my-zsh and vundle. | Antigen is a small set of functions that help you easily manage your shell (zsh) plugins. Antigen is to zsh, what Vundle is to vim.
[Dries's dotfiles ★149](driesvints/dotfiles) | Simplified approach to dotfiles for macOS | Zsh, Oh My Zsh, macOS, Homebrew, Mackup

## Tools

* [Ansible](https://www.ansible.com/) - Radically simple configuration-management, application deployment, task-execution, and multinode orchestration engine.
* [Bork ★155](mattly/bork) - Bash DSL for config management.
* [dotbot ★1116](anishathalye/dotbot) - Tool that bootstraps your dotfiles.
* [dotfiles ★307](jbernard/dotfiles) - Tool to make managing your dotfile symlinks in $HOME easy.
* [Ellipsis ★147](ellipsis/ellipsis) - A package manager for dotfiles.
* [fresh](https://freshshell.com/) - Keep your dotfiles fresh. Fresh is a tool to source shell configuration (aliases, functions, etc) from others into your own configuration files.
* [GNU Stow](http://www.gnu.org/software/stow/) - Symlink farm manager which takes distinct packages of software and/or data located in separate directories on the filesystem, and makes them appear to be installed in the same place.
* [homeshick ★1058](andsens/homeshick) - Git dotfile synchronizer written in Bash.
* [homesick ★1889](technicalpickles/homesick) - Your home directory is your castle. Don't leave your dotfiles behind ([article](http://technicalpickles.com/posts/never-leave-your-dotfiles-behind-again-with-homesick/)).
* [mackup ★6060](lra/mackup) - Keep your application settings in sync (OS X/Linux).
* [rcm ★1528](thoughtbot/rcm) - rc file (dotfile) management
* [SaltStack](https://saltstack.com/) - Intelligent orchestration for the software-defined data center ([article](https://medium.com/@rawkode/managing-dotfiles-with-saltstack-eb600867073e)).
* [vcsh ★1267](RichiH/vcsh) - Version Control System for $HOME, multiple Git repositories in $HOME.
* [yadm ★331](TheLocehiliosan/yadm) - Tool for managing a collection of files across multiple computers, using a shared Git repository and some additional features.

### macOS

* [Cider ★754](msanders/cider) - Hassle-free bootstrapping with Homebrew.
* [dockutil ★461](kcrawford/dockutil) - Command line tool for managing dock items
* [mas ★3130](mas-cli/mas) - Mac App Store command line interface

## Miscellaneous

* [A lesson in shortcuts](https://plus.google.com/+RobPikeTheHuman/posts/R58WgWwN9jp) - How the idea of "hidden" or "dot" files was born, by Rob Pike.
* [dotfiles.github.io](http://dotfiles.github.io/) - Your unofficial guide to dotfiles on GitHub.
* [OS X Defaults](https://github.com/kevinSuttle/macOS-Defaults) - Centralized place for the awesome work started by [@mathiasbynens on .osx ★16773](mathiasbynens/dotfiles#sensible-os-x-defaults).

## Related Lists

* [Awesome Shell ★9491](alebcay/awesome-shell) - Curated list of awesome command-line frameworks, toolkits, guides and gizmos.
* [Awesome Zsh Plugins ★2757](unixorn/awesome-zsh-plugins) - List of Zsh plugins suitable for use with oh-my-zsh, antigen & Prezto.
* [Awesome Dev Env ★782](jondot/awesome-devenv) - Curated list of awesome tools, resources and workflow tips making an awesome development environment.

## Archive/abandoned projects

* [Bashstrap ★1444](barryclark/bashstrap)
* [battleschool ★410 ⏳1Y](spencergibb/battleschool)
* [Eduardo's dotfiles ★425](eduardolundgren/dotfiles)
* [Kevin's dotfiles ★48](kdeldycke/dotfiles) 
* [kody ★67 ⏳1Y](jh3y/kody)
* [osxc](http://osxc.github.io)

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Lars Kappert](https://webpro.nl) has waived all copyright and related or neighboring rights to this work.
---
<p align="center">
	This list is a copy of <a href="webpro/awesome-dotfiles">webpro/awesome-dotfiles</a> with ranks
</p>
