---
layout: default
title: Awesome Rank for alebcay/awesome-shell
---

<p align="center">
	This list is a copy of <a href="https://github.com/alebcay/awesome-shell">alebcay/awesome-shell</a> with ranks
</p>
---
```
 █████╗ ██╗    ██╗███████╗███████╗ ██████╗ ███╗   ███╗███████╗
██╔══██╗██║    ██║██╔════╝██╔════╝██╔═══██╗████╗ ████║██╔════╝
███████║██║ █╗ ██║█████╗  ███████╗██║   ██║██╔████╔██║█████╗  
██╔══██║██║███╗██║██╔══╝  ╚════██║██║   ██║██║╚██╔╝██║██╔══╝  
██║  ██║╚███╔███╔╝███████╗███████║╚██████╔╝██║ ╚═╝ ██║███████╗
╚═╝  ╚═╝ ╚══╝╚══╝ ╚══════╝╚══════╝ ╚═════╝ ╚═╝     ╚═╝╚══════╝
███████╗██╗  ██╗███████╗██╗     ██╗                           
██╔════╝██║  ██║██╔════╝██║     ██║                           
███████╗███████║█████╗  ██║     ██║                           
╚════██║██╔══██║██╔══╝  ██║     ██║                           
███████║██║  ██║███████╗███████╗███████╗                      
╚══════╝╚═╝  ╚═╝╚══════╝╚══════╝╚══════╝                      
```

# Awesome Shell [![Awesome][awesome-badge]][awesome-link]

A curated list of awesome command-line frameworks, toolkits, guides and gizmos. Inspired by awesome-php. This awesome collection is also available on [Unix-Shell.ZEEF.com](https://unix-shell.zeef.com/caleb.xu).
- [Shells](#shells)
- [Command-Line Productivity](#command-line-productivity)
- [Customization](#customization)
- [For Developers](#for-developers)
- [System Utilities](#system-utilities)
- [Downloading and Serving](#downloading-and-serving)
- [Multimedia and File Formats](#multimedia-and-file-formats)
- [Applications](#applications)
- [Games](#games)
- [Shell Package Management](#shell-package-management)
- [Shell Script Development](#shell-script-development)
- [Guides](#guides)
- [**Awesome Zsh**][awesome-zsh]&nbsp; [![Awesome][awesome-badge]][awesome-zsh]
- [**Awesome Fish**][awesome-fish] [![Awesome][awesome-badge]][awesome-fish]
- [Other Awesome Lists](#other-awesome-lists)

## Shells

*Choose your base shell.*

* [bash](https://www.gnu.org/software/bash/) - GNU Project's shell (Bourne Again SHell)
* [fish](https://fishshell.com) - Smart and user-friendly command line shell
* [xiki](http://xiki.org) - Makes the shell console more friendly and powerful
* [xonsh](https://xonsh.org) - Python-ish, BASHwards-looking shell language and command prompt
* [zsh](http://www.zsh.org) - Powerful shell with scripting language

## Command-Line Productivity

*Search, bookmarks, multiplexing, and other tools that make your terminal experience more productive.*

* [ag ★12974](https://github.com/ggreer/the_silver_searcher) - Super fast string search through a directory hierarchy
* [aliases ★78](https://github.com/sebglazebrook/aliases) - Contextual, dynamic, organized aliases for bash
* [aliasme ★27](https://github.com/Jintin/aliasme) - alias helper to change directory quickly
* [autoenv ★3569](https://github.com/kennethreitz/autoenv) - Directory-based environments
* [autojump ★5753](https://github.com/wting/autojump) - A cd command that learns - easily navigate directories from the command line
* [bashhub ★367](https://github.com/rcaloras/bashhub-client) - :cloud: Bash history in the cloud. Indexed and searchable.
* [bashmarks ★1103](https://github.com/huyng/bashmarks) - Directory bookmarks for the shell
* [bd ★691](https://github.com/vigneshwaranr/bd) - Quickly go back to a parent directory
* [boilr ★524](https://github.com/tmrts/boilr) - A blazingly fast CLI tool for creating projects from boilerplate templates.
* [boom ★1063](https://github.com/holman/boom) - Store links and snippets in the commandline
* [borg ★1264](https://github.com/ok-borg/borg) - A terminal based search engine for bash commands
* [Buku ★1484](https://github.com/jarun/Buku) - Powerful command-line bookmark manager
* [byobu](http://byobu.co/) - Text-based window manager and terminal multiplexer
* [commacd ★187 ⏳1Y](https://github.com/shyiko/commacd) - A faster way to move around in Bash
* [desk ★1990](https://github.com/jamesob/desk) - A lightweight workspace manager for the shell
* [direnv ★2511](https://github.com/direnv/direnv) - An environment switcher for the shell, compare with autoenv
* [enhancd ★698](https://github.com/b4b4r07/enhancd) - :rocket: A next-generation cd command with an interactive filter
* [fasd ★3215](https://github.com/clvv/fasd) - Command-line productivity booster, offers quick access to files and directories
* [foxy ★6 ⏳1Y](https://github.com/s-p-k/foxy) - Plain text bookmarks for firefox and surf browsers.
* [fz ★104](https://github.com/changyuheng/fz) - Seamless fuzzy tab completion for z
* [fzf ★9839](https://github.com/junegunn/fzf) - A command-line fuzzy finder
* [googler ★1739](https://github.com/jarun/googler) - Google Search, Google Site Search, Google News from the terminal
* [hhighlighter ★220](https://github.com/paoloantinori/hhighlighter) - Colorize words in a command output
* [hr ★1013](https://github.com/LuRsT/hr) - `<hr />` for your terminal
* [hstr ★730](https://github.com/dvorka/hstr) - Bash History Suggest Box
* [jump ★335](https://github.com/gsamokovarov/jump) - Jump helps you navigate your file system faster by learning your habits.
* [k ★819](https://github.com/supercrabtree/k) - k is a Zsh script to make directory listings more readable, adding Git status, fileweight colors and rotting dates
* [k alias ★6 ⏳1Y](https://github.com/lingtalfi/k) - get kool aliases (and more) working with a simple one-liner
* [lf.sh ★4](https://github.com/suewonjp/lf.sh) - Quickly search files with fewer typings and do many more (grepping, copying path to clipboard, etc)
* [marker ★618](https://github.com/pindexis/marker) - Bookmark your shell commands
* [modules](http://modules.sourceforge.net/) - Environment manager for the shell (compare to direnv and autoenv)
* [nnn ★364](https://github.com/jarun/nnn) - File browser and disk usage analyzer with excellent desktop integration
* [parallel](http://www.gnu.org/software/parallel/) - Build and execute shell command lines from standard input in parallel
* [pathpicker ★3453](https://github.com/facebook/PathPicker) - Accepts inputs like grep, searches, git etc; allows selecting files from the result of the input, which you can then open or provide as argument to a command.
* [percol ★2364](https://github.com/mooz/percol) - Adds flavor of interactive filtering to the traditional pipe concept of UNIX shell
* [qfc ★426](https://github.com/pindexis/qfc) - File-completion widget for Bash and Zsh
* [rg ★5324](https://github.com/BurntSushi/ripgrep) - ripgrep is a line oriented search tool that combines the usability of The Silver Searcher with the raw speed of GNU grep
* [SHML ★324](https://github.com/odb/shml) - Style framework for the terminal (Shell Markup Language)
* [slugify ★180 ⏳1Y](https://github.com/benlinton/slugify) - Command that converts filenames and directories to a web friendly format
* [sman ★126](https://github.com/tokozedg/sman) - :bug: A command-line snippet manager
* [spark ★4860](https://github.com/holman/spark) - ▁▂▃▅▂▇ in your shell
* [Shark ★135](https://github.com/fisherman/shark) - ▁▂▃▅ Sparkline Generator
* [sheet ★222 ⏳4Y](https://github.com/oscardelben/sheet) -  Text snippets for the command line
* [spot ★626](https://github.com/rauchg/spot) - Tiny file search utility
- [snips ★21 ⏳1Y](https://github.com/srijanshetty/snips) - Commandline tool to manage snippets of code.
* [sshfs ★461](https://github.com/osxfuse/sshfs) - A tool for mounting remote file systems over SSH
* [sshrc ★3762](https://github.com/Russell91/sshrc) - Bring your .bashrc, .vimrc, etc. with you when you SSH
* [sudocabulary ★80](https://github.com/badarsh2/Sudocabulary) - Learn English Vocabulary from your terminal
* [surfraw](http://surfraw.alioth.debian.org/) - browse specific site and search the web from your terminal without browser.
* [thefuck ★29595](https://github.com/nvbn/thefuck) - Fix common shell mistakes by using an easy to remember command
* [tldr ★121](https://github.com/raylee/tldr) - A fully-functional bash client for tldr, simplified and community-driven man pages
* [tmux](http://tmux.github.io/) - Amazing terminal multiplexer
* [up ★38](https://github.com/shannonmoeller/up) - Ascend directories by name or count; for bash, zsh, and fish.
* [v ★278 ⏳1Y](https://github.com/rupa/v) - z for vim.
* [wemux ★2786](https://github.com/zolrath/wemux) - Multi-User Tmux Made Easy
* [z ★7044](https://github.com/rupa/z) - z is the new j, yo

## Customization

*Custom prompts, color themes, etc.*

* [base16-builder ★203](https://github.com/base16-builder/base16-builder) - Base16-Builder
* [bash-full-of-colors ★18 ⏳1Y](https://github.com/slomkowski/bash-full-of-colors) - Powerful prompt with screen, tmux, git support and many more
* [bash-git-prompt ★3236](https://github.com/magicmonty/bash-git-prompt) - An informative and fancy Bash prompt for Git users
* [bash-powerline ★456](https://github.com/riobard/bash-powerline) - Powerline-style Bash prompt in pure Bash script
* [bashstrap ★1448](https://github.com/barryclark/bashstrap) - A quick way to spruce up OSX terminal
* [bullet-train-oh-my-zsh-theme ★1424](https://github.com/caiogondim/bullet-train.zsh) - :bullettrain_side: An oh-my-zsh shell theme based on the Powerline Vim plugin
* [emojify ★882](https://github.com/mrowa44/emojify) Emoji on the command line :scream:
* [flatui-terminal-theme](https://dribbble.com/shots/1021755-Flat-UI-Terminal-Theme) - Nicer colors for terminal
* [git-prompt ★317 ⏳1Y](https://github.com/lvv/git-prompt) - Bash prompt with Git, SVN and HG modules
* [gittify ★21](https://github.com/momeni/gittify) - A colorful Bash prompt + customized Git aliases
* [Gogh - Color Scheme ★1162](https://github.com/Mayccoll/Gogh) - Color Scheme for Gnome Terminal
* [liquidprompt ★3154](https://github.com/nojhan/liquidprompt) - A full-featured & carefully designed adaptive prompt for Bash & Zsh
* [mysql-colorize ★39](https://github.com/zpm-zsh/mysql-colorize) -  Colorization for mysql comand-line client
* [oh-my-git ★2567](https://github.com/arialdomartini/oh-my-git) - An opinionated git prompt for bash and zsh
* [sexy-bash-prompt ★769](https://github.com/twolfson/sexy-bash-prompt) - Bash prompt with colors, Git statuses, and Git branches

## For Developers

*Command-line development, version control, and deployment.*

* [bcal ★46](https://github.com/jarun/bcal) - Byte CALculator for storage conversions and calculations
* [bocker ★4426 ⏳2Y](https://github.com/p8952/bocker) - Docker implemented in 100 lines of bash
* [cloc ★3217](https://github.com/AlDanial/cloc) - Count Lines of Code
* [doclt ★9](https://github.com/omgimanerd/doclt) - A command line interface to Digital Ocean
* [dokku ★14057](https://github.com/dokku/dokku) - Docker powered mini-Heroku. The smallest PaaS implementation you've ever seen.
* [getopts ★90](https://github.com/fisherman/getopts) - CLI parser for fish
* [git-extra-commands ★172](https://github.com/unixorn/git-extra-commands) - Many Git extra utilities. Churn, cut-branch, improved-merge and many more.
* [git-extras ★10329](https://github.com/tj/git-extras) - Git utilities -- repo summary, repl, changelog population, author commit percentages and more
* [git-open ★1057](https://github.com/paulirish/git-open) - Type `git open` to open the GitHub page or website for a repository in your browser
* [git-semver ★116](https://github.com/markchalloner/git-semver) - Git plugin for easing semantic versioning and changelog validation
* [git-sh ★676](https://github.com/rtomayko/git-sh) - A customized Bash environment suitable for Git work
* [git-up ★2734 ⏳1Y](https://github.com/aanand/git-up) - Automatically rebase incoming changes instead of merging. Be polite!
* [hub ★11143](https://github.com/github/hub) - hub helps you win at git.
* [mr ★1](https://github.com/joeyh/myrepos) - Multiple Repository management tool
* [overcommit ★2055](https://github.com/brigade/overcommit) - A fully configurable and extendable Git hook manager
* [pre-commit](http://pre-commit.com) - A framework for managing and maintaining multi-language pre-commit hooks
* [repren ★141 ⏳1Y](https://github.com/jlevy/repren) - Command-line search-and-replace and file-renaming swiss army knife
* [slap ★4646](https://github.com/slap-editor/slap) - Sublime-like terminal-based text editor that runs on Node.js
* [shipit ★338 ⏳1Y](https://github.com/sapegin/shipit) - Minimalistic SSH deployment
* [starring ★99](https://github.com/ritz078/starring) - Automatically star the npm-packages that you are using on GitHub.
* [tag ★436](https://github.com/aykamko/tag) - Instantly jump to your ag matches.

## System Utilities

*OS-related tools, including system administration, system debugging, and file and process management.*

* [atop](https://www.atoptool.nl) - ASCII full-screen performance monitor that is capable of reporting the activity of all processes
* [ccat ★1724](https://github.com/jingweno/ccat) - ccat is the colorizing cat. It works similar to cat but displays content with syntax highlighting.
* [colorex](https://bitbucket.org/linibou/colorex/wiki/Home) - Displays files or sdtin with pretty colors for matched patterns.
* [progress ★3388](https://github.com/Xfennec/progress) - Linux tool to show progress for cp, rm, dd, ...
* [glances ★7808](https://github.com/nicolargo/glances) - Glances an Eye on your system
* [goaccess ★5655](https://github.com/allinurl/goaccess) - GoAccess is a real-time web log analyzer and interactive viewer that runs in a terminal in \*nix systems.
* [histstat ★32](https://github.com/vesche/histstat) - History for netstat
* [htop ★2414](https://github.com/hishamhm/htop) - A ncurses based interactive process viewer which aims to be a better `top`
* [lnav](http://lnav.org) - An advanced log file viewer for the small-scale
* [ls++ ★337](https://github.com/trapd00r/ls--) - Colorized ls on steroids
* [lsp ★422 ⏳1Y](https://github.com/dborzov/lsp) - An improved `ls`, with file descriptions in plain language and intelligent file grouping
* [mtr ★694](https://github.com/traviscross/mtr) - The functionality of the 'traceroute' and 'ping' programs in a single network diagnostic tool.
* [ncdu](https://dev.yorhel.nl/ncdu) - NCurses Disk Usage
* [powertop ★264](https://github.com/fenrus75/powertop) - Battery/Power usage and device stats monitoring command-line tool, with tune-up options.
* [procdog ★46 ⏳2Y](https://github.com/jlevy/procdog) - Lightweight command-line control of long-lived processes like servers
* [quick-secure ★266 ⏳2Y](https://github.com/marshyski/quick-secure) - Quickly secure and harden UNIX/Linux systems

## Downloading and Serving

*Self-hosted, lightweight servers and networking tools written in shell scripts.*

* [aria2 ★6142](https://github.com/aria2/aria2) - aria2 is a lightweight multi-protocol & multi-source, cross platform download utility operated in command-line. It supports HTTP/HTTPS, FTP, BitTorrent and Metalink
* [balls ★672 ⏳1Y](https://github.com/jneen/balls) - Bash on Balls
* [bashttpd ★844](https://github.com/avleen/bashttpd) - A web server written in Bash
* [bitpocket ★912](https://github.com/sickill/bitpocket) - "DIY Dropbox" or "2-way directory (r)sync with proper deletion"
* [Dropbox-Uploader ★4842](https://github.com/andreafabrizi/Dropbox-Uploader) - Dropbox Uploader is a Bash script which can be used to upload, download, list or delete files from Dropbox
* [httpie ★31025](https://github.com/jakubroztocil/httpie) - HTTPie is a command line HTTP client, a user-friendly cURL replacement
* [ngincat ★105 ⏳3Y](https://github.com/jaburns/ngincat) - Tiny Bash HTTP server using netcat
* [resty ★2162](https://github.com/micha/resty) - Little command line REST client that you can use in pipelines
* [youtube-dl ★28275](https://github.com/rg3/youtube-dl) - Small command-line program to download videos from YouTube.com and other video sites

## Multimedia and File Formats

*Tools for handling video and audio files.*

* [adb-export ★47](https://github.com/snatik/adb-export) - Export Android content providers to CSV format
* [Android-Kitchen ★756](https://github.com/dsixda/Android-Kitchen) - A text-based kitchen for Android ROM customization. Uses shell scripts and works with Cygwin/OS X/Linux
* [Beets ★6080](https://github.com/beetbox/beets) - Music library manager and MusicBrainz tagger
* [cmus ★2177](https://github.com/cmus/cmus) - Cross-platform cli audio player.
* [gifgen ★151](https://github.com/lukechilds/gifgen) - Simple high quality GIF encoding
* [image-scraper ★364](https://github.com/sananth12/ImageScraper) - A cool command line image scraper with a lot of features.
* [imgp ★225](https://github.com/jarun/imgp) - Blazing fast batch image resizer and rotator
* [jq ★9461](https://github.com/stedolan/jq) - Sed for json data. You can use it to slice and filter and map and transform structured data
* [mplayer](http://www.mplayerhq.hu/design7/news.html) - Lets you play most audio and video formats (using ASCII characters) in the shell as well as in a GUI.
* [nehm ★23](https://github.com/bogem/nehm) - Console tool, which downloads, sets IDv3 tags and adds to your iTunes (if you use it) your SoundCloud likes in convenient way
* [PiCAST ★1341](https://github.com/lanceseidman/PiCAST) - PiCAST turns your $35 Raspberry Pi in to a Chromecast like Device
* [sejda ★145](https://github.com/torakiki/sejda) - Command line manipulation of PDF documents (split, merge, rotate, convert to jpg, extract text, etc)
* [xidel ★69](https://github.com/benibela/xidel) - Cli tool to filter, map and create HTML/XML/JSON data with (Turing-complete) XPath and XQuery.
* [xmlstarlet](http://xmlstar.sourceforge.net/) - Old but powerful tool for command-line XML formatting, filtering, and manipulation.

## Applications

*Command line-based applications or command line access to existing services.*

* [ansiweather ★1292](https://github.com/fcambus/ansiweather) - Weather in your terminal, with ANSI colors and Unicode symbols
* [bashblog ★603](https://github.com/cfenollosa/bashblog) - A Bash script that handles blog posting
* [choosealicense-cli ★31 ⏳1Y](https://github.com/lord63/choosealicense-cli) - Choose an OSS license from the comfort of your terminal
* [facy ★241](https://github.com/huydx/facy) - Command line power tool for facebook
* [fanyi ★313](https://github.com/afc163/fanyi) - Translate English to Chinese in terminal
* [geeknote ★1804](https://github.com/VitaliyRodnenko/geeknote) - Command line evernote client
* [haxor-news ★2315](https://github.com/donnemartin/haxor-news) - Browse Hacker News like a haxor
* [hn-cli ★387 ⏳1Y](https://github.com/rafaelrinaldi/hn-cli) - Browse Hacker News from the comfort of your Terminal
* [iponmap ★121](https://github.com/nogizhopaboroda/iponmap) - Draw point on world map using ip address
* [isitup ★21 ⏳2Y](https://github.com/lord63/isitup) - Check whether a website is up or down
* [jrnl ★2436](https://github.com/maebert/jrnl) - A simple command line journal application that stores your journal in a plain text file
* [ledger ★2101](https://github.com/ledger/ledger) - Command line accounting
* [licen ★23 ⏳2Y](https://github.com/lord63/licen) - Generate your license. Yet another lice, but implement with Jinja2 and docopt
* [moviemon ★75](https://github.com/iCHAIT/moviemon) - Everything about your movies within the command line.
* [pockyt ★183](https://github.com/arvindch/pockyt) - Read, Manage, and Automate your [Pocket](https://getpocket.com) collection.
* [pushblast ★90 ⏳1Y](https://github.com/alebcay/pushblast) - Get PushBullet notifications when a shell program exits
* [pushbullet-bash ★179](https://github.com/Red5d/pushbullet-bash) - Bash interface to the PushBullet API
* [Reddit Terminal Viewer ★1443](https://github.com/michael-lazar/rtv) - Browse Reddit from your terminal
* [SAWS ★3339](https://github.com/donnemartin/saws) - A Supercharged AWS CLI
* [taskwarrior](https://taskwarrior.org/) - A command-line TODO list manager
* [terjira ★305](https://github.com/keepcosmos/terjira) - Command line power tool for Jira
* [transfer.sh](https://transfer.sh/) — Quickly upload and share files from your shell
* [vl ★28](https://github.com/ellisonleao/vl) - URL link checker on text documents
* [wego ★4932](https://github.com/schachmat/wego) - Weather app for the terminal
* [whereami ★47](https://github.com/rafaelrinaldi/whereami) - Get your geolocation information from the CLI
* [wttr.in ★3802](https://github.com/chubin/wttr.in) - :partly_sunny: The right way to check the weather (curl wttr.in)

## Games

*All work and no play is a cruddy way to spend your day.*

* [bash2048 ★595](https://github.com/mydzor/bash2048) - Bash implementation of 2048 game
* [minesweeper](https://github.com/feherke/Bash-script/tree/master/minesweeper) - Bash implementation of minesweeper
* [nudoku ★62 ⏳1Y](https://github.com/jubalh/nudoku) - ncurses based sudoku game written in C
* [sedtris ★221](https://github.com/uuner/sedtris) - Tetris in sed
* [sed-scripts ★26 ⏳4Y](https://github.com/aureliojargas/sed-scripts) - Arkanoid and Sokoban written using sed
* [tty-solitaire ★70](https://github.com/mpereira/tty-solitaire) - Play solitaire in your terminal!

## Shell Package Management

*Tools for managing multiple shell configurations. For zsh-specific tools, see the Zsh section.*

* [bash-it ★6575](https://github.com/Bash-it/bash-it) - A community Bash framework
* [basher ★284](https://github.com/basherpm/basher) - A package manager for shell scripts
* [bpkg](http://www.bpkg.sh/) - JavaScript has npm, Ruby has Gems, Python has pip and now Shell has bpkg
* [dotdrop ★31](https://github.com/deadc0de6/dotdrop) - Save your dotfiles once, deploy them everywhere
* [dotfiler ★125](https://github.com/svetlyak40wt/dotfiler) – Shell agnostic git based dotfiles package manager, written in Python.
* [fresh ★806](https://github.com/freshshell/fresh) - Keep your dotfiles fresh
* [homeshick ★1082](https://github.com/andsens/homeshick) - Git dotfile synchronizer written in Bash
* [shundle ★61](https://github.com/javier-lopez/shundle) - Plugin manager for shell scripts
* [vcsh ★1288](https://github.com/RichiH/vcsh) - Config manager based on Git
* [yadm](https://thelocehiliosan.github.io/yadm/) - Git-based dotfiles manager supporting encryption, alternates, and bootstrapping

## Shell Script Development

*Tools for writing, improving, or organizing Bash or other shell scripts*

* [ansi ★103](https://github.com/fidian/ansi) - ANSI escape codes in pure bash - change text color, position the cursor, much more
* [assert.sh ★299](https://github.com/lehmannro/assert.sh) - Bash unit testing framework
* [bashful ★336 ⏳1Y](https://github.com/jmcantrell/bashful) - A collection of libraries to simplify writing Bash scripts
* [bashmanager ★34 ⏳1Y](https://github.com/lingtalfi/bashmanager) - mini bash framework for creating command line tools
* [bashwithnails ★3](https://github.com/mindaugasbarysas/bashwithnails) - a Bash framework written just for fun with testing, dependency management & packaging
* [bats ★3839](https://github.com/sstephenson/bats) - Bash Automated Testing System
* [crash ★9](https://github.com/molovo/crash) - Proper error handling, exceptions and try/catch for ZSH
* [Fishtape ★208](https://github.com/fisherman/fishtape) - TAP producer and test harness for fish
* [composure ★203](https://github.com/erichs/composure) - Compose, document, version and organize your shell functions
* [dispatch](https://github.com/Mosai/workshop/blob/master/doc/dispatch.md) - A command line argument parser in 50 lines of portable shell script.
* [is.sh ★42](https://github.com/qzb/is.sh) - An alternative for builtin test command, it will make your "if" statements pretty
* [lumberjack ★9](https://github.com/molovo/lumberjack) - A logging interface for shell scripts
* [mo ★138](https://github.com/tests-always-included/mo) - Mustache templates in pure bash
* [optparse ★84](https://github.com/nk412/optparse) - A BASH wrapper for getopts, for simple command line arguments.
* [rerun ★305](https://github.com/rerun/rerun) - A modular shell automation framework to organize your keeper scripts
* [revolver ★33](https://github.com/molovo/revolver) - A reusable progress spinner for shell scripts
* [semver_bash ★99](https://github.com/cloudflare/semver_bash) - Semantic Versioning in Bash
* [sh-semver ★9](https://github.com/qzb/sh-semver) - Semver tool for bash - finds versions matching to specified rules
* [shellcheck ★8507](https://github.com/koalaman/shellcheck) - Static analysis tool for shell scripts
* [shellfire ★1071 ⏳1Y](https://github.com/shellfire-dev/shellfire) -  A repository of namespaced, composable shell (bash, sh and dash) function libraries
* [shpec ★285](https://github.com/rylnd/shpec) - A shell testing framework
* [shutit](https://ianmiell.github.io/shutit/) - Automation framework based on bash and pexpect
* [sub ★1380 ⏳4Y](https://github.com/basecamp/sub) - A delicious way to organize programs
* [ts ★32 ⏳1Y](https://github.com/thinkerbot/ts) - A shell test script
* [shunit2 ★277](https://github.com/kward/shunit2) - A unit test framework for Bash scripts with a flavour of JUnit/PyUnit.
* [rebash ★23](https://github.com/jandob/rebash) - Scripting library/framework. Features: imports, exceptions, doc-tests ...
* [zunit ★26](https://github.com/zunit-zsh/zunit) - A powerful unit testing framework for ZSH

# Guides

* [Bash Hackers Wiki](http://wiki.bash-hackers.org/)
* [Greg Wooledge's (aka "greycat") wiki](http://mywiki.wooledge.org).
  Specifically [Bash Guide](http://mywiki.wooledge.org/BashGuide), [Bash FAQ](http://mywiki.wooledge.org/BashFAQ) and [Bash Pitfalls](http://mywiki.wooledge.org/BashPitfalls)
* [Google's Shell Style Guide](https://google.github.io/styleguide/shell.xml)
* [The Linux Documentation Project: Bash Programming - Intro/How-to](http://tldp.org/HOWTO/Bash-Prog-Intro-HOWTO.html#toc)
* [The Linux Documentation Project: Advanced Bash Scripting Guide](http://www.tldp.org/LDP/abs/html/)
* [WikiBooks: Bash Shell Scripting](https://en.wikibooks.org/wiki/Bash_Shell_Scripting)
* [Use the Unofficial Bash Strict Mode (Unless You Looove Debugging)](http://redsymbol.net/articles/unofficial-bash-strict-mode/)
* [The Art of Command Line ★31428](https://github.com/jlevy/the-art-of-command-line)
* [Learn Enough Command Line to Be Dangerous](https://www.learnenough.com/command-line-tutorial)
* [A guide to learn bash ★7940](https://github.com/Idnan/bash-guide)

# Other Awesome Lists

Other amazingly awesome lists can be found in [awesome-awesome](https://github.com/emijrp/awesome-awesome) and [awesome-awesomeness ★19452](https://github.com/bayandin/awesome-awesomeness).

### See also

* [awesome-cli-apps ★1128](https://github.com/agarrharr/awesome-cli-apps) 
* [awesome-fish][awesome-fish]
* [awesome-zsh][awesome-zsh]
* [terminals-are-sexy ★5063](https://github.com/k4m4/terminals-are-sexy)

[awesome-badge]: https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg
[awesome-fish]: https://github.com/jbucaran/awesome-fish
[awesome-link]: https://github.com/sindresorhus/awesome
[awesome-zsh]: https://github.com/unixorn/awesome-zsh-plugins
---
<p align="center">
	This list is a copy of <a href="https://github.com/alebcay/awesome-shell">alebcay/awesome-shell</a> with ranks
</p>
