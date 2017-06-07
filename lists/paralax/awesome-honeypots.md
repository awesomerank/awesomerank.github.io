<h1 align="center">
Ranked awesome lists, all in one place
</h1>
<p align="center">
	This list is a copy of <a href="paralax/awesome-honeypots">paralax/awesome-honeypots</a> with ranks
</p>
---
# Awesome Honeypots  

[![Awesome Honeypots](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg) ★59088](sindresorhus/awesome)

A curated list of awesome honeypots, tools, components and much more. The list is divided into categories such as web, services, and others, focusing on open source projects.

There is no pre-established order of items in each category, the order is for contribution. If you want to contribute, please read the [guide](https://github.com/paralax/awesome-honeypots/blob/master/CONTRIBUTING.md).

Discover more awesome lists at [sindresorhus/awesome ★59088](sindresorhus/awesome).

### Sections

- [Honeypots](#honeypots)
- [Honeyd Tools](#honeyd)
- [Network and Artifact Analysis](#analysis)
- [Data Tools](#visualizers)
- [Guides](#guides)

## Related Lists
- [awesome-pcaptools ★729](caesar0301/awesome-pcaptools), useful in network traffic analysis.
- [awesome-malware-analysis ★2151](rshipp/awesome-malware-analysis), with some overlap here for artifact analysis.

## <a name="honeypots"></a> Honeypots

- Database Honeypots
    - [MongoDB-HoneyProxy ★42](Plazmaz/MongoDB-HoneyProxy) - A MongoDB honeypot proxy.
    - [Elastic honey ★86 ⏳1Y](jordan-wright/elastichoney) - A Simple Elasticsearch Honeypot.
    - [mysql ★10 ⏳4Y](schmalle/MysqlPot) - A mysql honeypot, still very very early stage.
    - [NoSQLpot ★78](torque59/nosqlpot) - The NoSQL Honeypot Framework.
    - [ESPot ★6 ⏳2Y](mycert/ESPot) - An Elasticsearch honeypot written in NodeJS, to capture every attempts to exploit CVE-2014-3120.
    - [Delilah ★25 ⏳2Y](Novetta/delilah) - An Elasticsearch Honeypot written in Python.

- Web honeypots
    - [Glastopf ★271](mushorg/glastopf) - Web Application Honeypot.
    - Snare/Tanner - successors to Glastopf
      - [Snare ★48](mushorg/snare) - Super Next generation Advanced Reactive honEypot
      - [Tanner ★26](mushorg/tanner) - Evaluating SNARE events
    - [phpmyadmin_honeypot ★29 ⏳1Y](gfoss/phpmyadmin_honeypot) - - A simple and effective phpMyAdmin honeypot.
    - [servlet ★5 ⏳4Y](schmalle/Servletpot) - Web application Honeypot.
    - [Nodepot ★16 ⏳1Y](schmalle/Nodepot)  - A nodejs web application honeypot.
    - [basic-auth-pot ★9 ⏳2Y](bjeborn/basic-auth-pot) bap - http Basic Authentication honeyPot.
    - [Shadow Daemon](https://shadowd.zecure.org) - A modular Web Application Firewall / High-Interaction Honeypot for PHP, Perl & Python apps.
    - [Servletpot ★5 ⏳4Y](schmalle/servletpot) - Web application Honeypot.
    - [Google Hack Honeypot](http://ghh.sourceforge.net) - designed to provide reconnaissance against attackers that use search engines as a hacking tool against your resources.
    - [smart-honeypot ★10 ⏳3Y](freak3dot/smart-honeypot) - PHP Script demonstrating a smart honey pot.
    - [Bukkit Honeypot ★6 ⏳6Y](Argomirr/Honeypot) Honeypot - A honeypot plugin for Bukkit.
    - [Laravel Application Honeypot ★268](msurguy/Honeypot) - Honeypot - Simple spam prevention package for Laravel applications.
    - [stack-honeypot ★16 ⏳3Y](CHH/stack-honeypot) - Inserts a trap for spam bots into responses.
    - [EoHoneypotBundle ★22](eymengunay/EoHoneypotBundle) - Honeypot type for Symfony2 forms.
    - [shockpot ★38 ⏳1Y](threatstream/shockpot) - WebApp Honeypot for detecting Shell Shock exploit attempts.
    - [django-admin-honeypot ★368](dmpayton/django-admin-honeypot) - A fake Django admin login screen to notify admins of attempted unauthorized access. 
    - WordPress honeypots
        - [HonnyPotter ★18 ⏳1Y](MartinIngesen/HonnyPotter) - A WordPress login honeypot for collection and analysis of failed login attempts.
        - [HoneyPress ★48](dustyfresh/HoneyPress) - python based WordPress honeypot in a docker container.
        - [wp-smart-honeypot ★12 ⏳1Y](freak3dot/wp-smart-honeypot) - WordPress plugin to reduce comment spam with a smarter honeypot.
        - [wordpot ★96 ⏳2Y](gbrindisi/wordpot) - A WordPress Honeypot.

- Service Honeypots
    - [honeyntp ★33 ⏳3Y](fygrave/honeyntp) - NTP logger/honeypot.
    - [honeypot-camera ★30 ⏳2Y](alexbredo/honeypot-camera) - observation camera honeypot.
    - [troje ★30 ⏳2Y](dutchcoders/troje) - a honeypot built around lxc containers. It will run each connection with the service within a seperate lxc container.
    - [HoneyPy ★218](foospidy/HoneyPy) - A low interaction honeypot.
    - [Ensnare ★66](ahoernecke/ensnare) - Easy to deploy Ruby honeypot.
    - [RDPy ★560 ⏳1Y](citronneur/rdpy) - A Microsoft Remote Desktop Protocol (RDP) honeypot in python.
    - [Honeyprint ★7 ⏳1Y](glaslos/honeyprint) - Printer honeypot.
    - [Tom's Honeypot ★7 ⏳2Y](inguardians/toms_honeypot) - Low interaction Python honeypot.
    - [Honeyport ★12](securitygeneration/Honeyport) - A simple honeyport written in Bash and Python.
    - [AMTHoneypot ★2](packetflare/amthoneypot) - Honeypot for Intel's AMT Firmware Vulnerability CVE-2017-5689.

- Distributed Honeypots
    - [DemonHunter ★5](RevengeComing/DemonHunter) - Low interaction Honepot Server.

- Anti-honeypot stuff
    - [kippo_detect ★35 ⏳2Y](andrew-morris/kippo_detect) - This is not a honeypot, but it detects kippo. (This guy has lots of more interesting stuff)

- ICS/SCADA honeypots
    - [Conpot ★318](mushorg/conpot) - ICS/SCADA honeypot.
    - [gridpot ★20 ⏳2Y](sk4ld/gridpot) - Open source tools for realistic-behaving electric grid honeynets .
    - [scada-honeynet](http://www.digitalbond.com/tools/scada-honeynet/) - mimics many of the services from a popular PLC and better helps SCADA researchers understand potential risks of exposed control system devices.
    - [SCADA honeynet](http://scadahoneynet.sourceforge.net) - Building Honeypots for Industrial Networks.
    - [GasPot ★48](sjhilt/GasPot) - Veeder Root Gaurdian AST, common in the oil and gas industry.

- Other/random
    - [NOVA ★36 ⏳2Y](DataSoft/Nova) uses honeypots as detectors, looks like a complete system.
    - [Open Canary](https://pypi.python.org/pypi/opencanary) - A low interaction honeypot intended to be run on internal networks.
    - [OFPot ★4 ⏳4Y](upa/ofpot) - OpenFlow Honeypot, redirects traffic for unused IPs to a honeypot. Built on POX.
    - [OpenCanary ★221](thinkst/opencanary) - Modular and decentralised honeypot.

- Botnet C2 tools
    - [Hale ★73 ⏳5Y](pjlantz/Hale) - Botnet command &amp; control monitor.
    - [dnsMole](https://code.google.com/p/dns-mole/) -  analyse dns traffic, and to potentionaly detect botnet C&C server and infected hosts.
    - [botsnoopd](http://botsnoopd.mwcollect.org) - Botnet C2 monitoring

- IPv6 attack detection tool
    - [ipv6-attack-detector ★17](mzweilin/ipv6-attack-detector)  - Google Summer of Code 2012 project, supported by The Honeynet Project organization.

- Dynamic code instrumentation toolkit
    - [Frida](http://www.frida.re) - Inject JavaScript to explore native apps on Windows, Mac, Linux, iOS and Android.

- Tool to convert website to server honeypots
    - [HIHAT](http://hihat.sourceforge.net/) - Transform arbitrary PHP applications into web-based high-interaction Honeypots.

- Malware collector
    - [Kippo-Malware](http://bruteforce.gr/kippo-malware) - Python script that will download all malicious files stored as URLs in a Kippo SSH honeypot database.

- Distributed sensor deployment
    - [Smarthoneypot](https://smarthoneypot.com/) - custom honeypot intelligence system that is simple to deploy and easy to manage.
    - [Modern Honey Network ★1139](threatstream/mhn) - Multi-snort and honeypot sensor management, uses a network of VMs, small footprint SNORT installations, stealthy dionaeas, and a centralized server for management.
    - [ADHD](http://sourceforge.net/projects/adhd/) -  Active Defense Harbinger Distribution (ADHD) is a Linux distro based on Ubuntu LTS. It comes with many tools aimed at active defense preinstalled and configured.

- Network Analysis Tool
    - [Tracexploit](https://code.google.com/p/tracexploit/) - replay network packets.

- Log anonymizer
    - [LogAnon](http://code.google.com/p/loganon/) - log anonymization library that helps having anonymous logs consistent between logs and network captures.

- Low interaction honeypot (router back door)
    - [Honeypot-32764 ★7 ⏳3Y](knalli/honeypot-for-tcp-32764) - Honeypot for router backdoor (TCP 32764).

- honeynet farm traffic redirector
    - [Honeymole](https://web.archive.org/web/20120122130150/http://www.honeynet.org.pt/index.php/HoneyMole) - eploy multiple sensors that redirect traffic to a centralized collection of honeypots.

- HTTPS Proxy
    - [mitmproxy](http://mitmproxy.org/) - allows traffic flows to be intercepted, inspected, modified and replayed.

- System instrumentation
    - [Sysdig](http://www.sysdig.org) - open source, system-level exploration: capture system state and activity from a running Linux instance, then save, filter and analyze.
    - [Fibratus ★364](rabbitstack/fibratus) - tool for exploration and tracing of the Windows kernel.

- Honeypot for USB-spreading malware
    - [Ghost-usb ★38 ⏳2Y](honeynet/ghost-usb-honeypot) -  honeypot for malware that propagates via USB storage devices.
    - [Honeystick](http://www.ukhoneynet.org/research/honeystick-howto/)  - low interaction honeypot on USB stick

- Data Collection
    - [Kippo2MySQL](http://bruteforce.gr/kippo2mysql) -  extracts some very basic stats from Kippo’s text-based log files (a mess to analyze!) and inserts them in a MySQL database.
    - [Kippo2ElasticSearch](http://bruteforce.gr/kippo2elasticsearch) - Python script to transfer data from a Kippo SSH honeypot MySQL database to an ElasticSearch instance (server or cluster).

- Passive network audit framework parser
    - [pnaf ★13 ⏳1Y](jusafing/pnaf) - Passive Network Audit Framework.

- VM monitoring and tools
    - [VIX virtual machine introspection toolkit](http://assert.uaf.edu/research/vmi.html) - VMI toolkit for Xen, called Virtual Introspection for Xen (VIX).
    - [vmscope](http://cs.gmu.edu/~xwangc/Publications/RAID07-VMscope.pdf) - Monitoring of VM-based.
    - [vmitools](http://libvmi.com/) - C library with Python bindings that makes it easy to monitor the low-level details of a running virtual machine.
    - [Antivmdetect ★159](nsmfoo/antivmdetection) - Script to create templates to use with VirtualBox to make vm detection harder.
    - [VMCloak ★179](jbremer/vmcloak) - Automated Virtual Machine Generation and Cloaking for Cuckoo Sandbox.

- Binary debugger
    - [Hexgolems - Schem Debugger Frontend ★135 ⏳1Y](hexgolems/schem) - A debugger frontend.
    - [Hexgolems - Pint Debugger Backend ★27 ⏳3Y](hexgolems/pint) - A debugger backend and LUA wrapper for PIN.

- Mobile Analysis Tool
    - [APKinspector ★486 ⏳4Y](honeynet/apkinspector) - APKinspector is a powerful GUI tool for analysts to analyze the Android applications.
    - [Androguard ★1498](androguard/androguard) - Reverse engineering, Malware and goodware analysis of Android applications ... and more.

- Low interaction honeypot
    - [Honeypoint](http://microsolved.com/HoneyPoint-server.html) - platform of distributed honeypot technologies.
    - [Honeyperl](http://sourceforge.net/projects/honeyperl/) - Honeypot software based in Perl with plugins developed for many functions like : wingates, telnet, squid, smtp, etc.

- Honeynet data fusion
    - [HFlow2](https://projects.honeynet.org/hflow) -  data coalesing tool for honeynet/network analysis.

- Server
    - [LaBrea](http://labrea.sourceforge.net/labrea-info.html) - takes over unused IP addresses, and creates virtual servers that are attractive to worms, hackers, and other denizens of the Internet.
    - [Honeysink](http://www.honeynet.org/node/773) - open source network sinkhole that provides a mechanism for detection and prevention of malicious traffic on a given network.
    - [KFSensor](http://www.keyfocus.net/kfsensor/) - Windows based honeypot Intrusion Detection System (IDS).
    - [Honeyd ★1 ⏳2Y](provos/honeyd) Also see [more honeyd tools](#honeyd).
    - [UDPot Honeypot ★22 ⏳3Y](jekil/UDPot) - Simple UDP / DNS honeypot scripts.
    - [Conpot](http://conpot.org/) - ow interactive server side Industrial Control Systems honeypot.
    - [Bifrozt](https://github.com/Bifrozt/bifrozt-ansible) - High interaction honeypot solution for Linux based systems.
    - [Beeswarm](http://www.beeswarm-ids.org/) - Honeypot deployment made easy.
    - [Bait and Switch](http://baitnswitch.sourceforge.net) - redirects all hostile traffic to a honeypot that is partially mirroring your production system.
    - [Artillery ★267](trustedsec/artillery) - open-source blue team tool designed to protect Linux and Windows operating systems through multiple methods.
    - [slipm-honeypot ★5 ⏳3Y](rshipp/slipm-honeypot) - A simple low-interaction port monitoring honeypot.
    - [HoneyWRT ★10 ⏳1Y](CanadianJeff/honeywrt) - low interaction Python honeypot designed to mimic services or ports that might get targeted by attackers.
    - [Amun](http://amunhoney.sourceforge.net) - vulnerability emulation honeypot.
    - [TelnetHoney ★1 ⏳1Y](AnguisCaptor/TelnetHoney) - A simple telnet honeypot.
    - [Hontel ★47](stamparm/hontel) - Telnet Honeypot.
    - [MTPot](https://github.com/CymmetriaResearch/MTPot) - Open Source Telnet Honeypot, focused on Mirai malware.
    - [Heralding ★97](johnnykv/heralding) - A credentials catching honeypot.
    - [VNC-Pot](https://github.com/SepehrHml/VNC-Pot) - A low interaction VNC honeypot.
    - [vnclowpot ★4](magisterquis/vnclowpot) - A low interaction VNC honeypot.
    - [SIREN ★2](blaverick62/SIREN) - Semi-Intelligent HoneyPot Network - HoneyNet Intelligent Virtual Environment.
    - [telnetlogger ★153](robertdavidgraham/telnetlogger) - A Telnet honeypot designed to track the Mirai botnet.
    - [honeytrap ★45](tillmannw/honeytrap) - a low-interaction honeypot and network security tool written to catch attacks against TCP and UDP services. 
    - [mwcollectd](https://www.openhub.net/p/mwcollectd) - a versatile malware collection daemon, uniting the best features of nepenthes and honeytrap.
    - [portlurker ★0](bartnv/portlurker) - Port listener / honeypot in Rust with protocol guessing and safe string display.

- IDS signature generation
    - [Honeycomb](http://www.icir.org/christian/honeycomb/) - Automated signature creation using honeypots.

- Lookup service for AS-numbers and prefixes
    - [CC2ASN](http://www.cc2asn.com/) - A simple lookup service for AS-numbers and prefixes belonging to any given country in the world.

- Web interface (for Thug)
    - [Rumal](https://github.com/thugs-rumal/) - Thug's Rumāl: a Thug's dress & weapon.

- Data Collection / Data Sharing
    - [HPfriends](http://hpfriends.honeycloud.net/#/home) - data-sharing platform.
    - [HPFeeds ★133](rep/hpfeeds) - lightweight authenticated publish-subscribe protocol.

- central management tool
    - [PHARM](http://www.nepenthespharm.com/) - Manage , Report, Analyze your distributed Nepenthes instances.

- Network connection analyzer
    - [Impost](http://impost.sourceforge.net/) - a network security auditing tool designed to analyze the forensics behind compromised and/or vulnerable daemons. 

- Honeypot deployment
    - [Modern Honeynet Network](http://threatstream.github.io/mhn/) - makes deploying and managing secure honeypots extremely simple.
    - [SurfIDS](http://ids.surfnet.nl/) - an open source Distributed Intrusion Detection System based on passive sensors.

- Honeypot extensions to Wireshark
    - [Whireshark Extensions](https://www.honeynet.org/project/WiresharkExtensions) - support applying Snort IDS rules and signatures against pcap files.

- Telephony honeypot
    - [Zapping Rachel](https://seanmckaybeck.com/zapping-rachel.html)

- Client
    - [Pwnypot ★24 ⏳3Y](shjalayeri/pwnypot) - High Interaction Client Honeypot
    - [MonkeySpider](http://monkeyspider.sourceforge.net)
    - [Capture-HPC-NG ★8 ⏳5Y](CERT-Polska/HSN-Capture-HPC-NG)
    - [Wepawet](http://wepawet.cs.ucsb.edu/about.php)
    - [URLQuery](https://urlquery.net/)
    - [Trigona](https://www.honeynet.org/project/Trigona)
    - [Thug](https://buffer.github.io/thug/)
    - [Shelia](http://www.cs.vu.nl/~herbertb/misc/shelia/)
    - [PhoneyC ★9 ⏳2Y](honeynet/phoneyc)
    - [Jsunpack-n ★67 ⏳2Y](urule99/jsunpack-n)
    - [HoneyC](https://projects.honeynet.org/honeyc)
    - [HoneyBOT](http://www.atomicsoftwaresolutions.com/)
    - [CWSandbox / GFI Sandbox](http://www.gfi.com/products-and-solutions/all-products)
    - [Capture-HPC-Linux](https://redmine.honeynet.org/projects/linux-capture-hpc/wiki)
    - [Capture-HPC](https://projects.honeynet.org/capture-hpc) - a high interaction client honeypot (also called honeyclient).
    - [YALIH (Yet Another Low Interaction Honeyclient) ★41](Masood-M/yalih) - a low Interaction Client honeypot designed to detect malicious websites through signature, anomaly and pattern matching techniques

- Binary Management and Analysis Framework
    - [Viper](http://viper.li/)

- Honeypot
    - [Single-honeypot](http://sourceforge.net/projects/single-honeypot/)
    - [Honeyd For Windows](http://www.securityprofiling.com/honeyd/honeyd.shtml)
    - [IMHoneypot ★7 ⏳1Y](mushorg/imhoneypot)
    - [Deception Toolkit](http://www.all.net/dtk/dtk.html)

- PDF document inspector
    - [peepdf ★226](jesparza/peepdf)

- Distribution system
    - [Thug Distributed Task Queuing](https://thug-distributed.readthedocs.org/en/latest/index.html)

- HoneyClient Management
    - [HoneyWeb](https://code.google.com/p/gsoc-honeyweb/)

- Network Analysis
    - [HoneyProxy](http://honeyproxy.org/)

- Hybrid low/high interaction honeypot
    - [HoneyBrid](http://honeybrid.sourceforge.net)

- SSH Honeypots
    - [Kojoney](http://kojoney.sourceforge.net/)
    - [Kojoney2 ★30 ⏳2Y](madirish/kojoney2) - low interaction SSH honeypot written in Python. Based on Kojoney by Jose Antonio Coret
    - [Kippo ★887](desaster/kippo) - Medium interaction SSH honeypot
       - [LongTail Log Analysis @ Marist College](http://longtail.it.marist.edu/honey/) - analyzed SSH honeypot logs
       - [DRG SSH Username and Password Authentication Tag Clouds](https://www.dragonresearchgroup.org/insight/sshpwauth-cloud.html) - live updated word clouds of SSH login honeypot data
    - [Cowrie ★1115](micheloosterhof/cowrie) - Cowrie SSH Honeypot (based on kippo)
    - [sshlowpot](https://github.com/kd5pbo/sshlowpot) - Yet another no-frills low-interaction ssh honeypot in Go.    
    - [sshhipot](https://github.com/kd5pbo/sshhipot) - High-interaction MitM SSH honeypot
    - [DShield docker ★3 ⏳1Y](xme/dshield-docker) - Docker container running cowrie with DShield output enabled.
    - [hornet ★17](czardoz/hornet) - Medium interaction SSH Honeypot that supports multiple virtual hosts
    - [ssh-honeypot ★90](droberson/ssh-honeypot) - Fake sshd that logs ip addresses, usernames, and passwords.    

- Distributed sensor project
    - [DShield Web Honeypot Project](https://sites.google.com/site/webhoneypotsite/)
    - [Distributed Web Honeypot Project](http://projects.webappsec.org/w/page/29606603/Distributed%20Web%20Honeypots)

- A pcap analyzer
    - [Honeysnap](https://projects.honeynet.org/honeysnap/)

- Client Web crawler
    - [HoneySpider Network ★17 ⏳1Y](CERT-Polska/hsn2-bundle)

- Network traffic redirector
    - [Honeywall](https://projects.honeynet.org/honeywall/)

- Honeypot Distribution with mixed content
    - [HoneyDrive](http://bruteforce.gr/honeydrive)

- Honeypot sensor
    - [Dragon Research Group Distro](https://www.dragonresearchgroup.org/drg-distro.html)
    - [Honeeepi] (https://redmine.honeynet.org/projects/honeeepi/wiki) - Honeeepi is a honeypot sensor on Raspberry Pi which based on customized Raspbian OS.

- File carving
    - [TestDisk & PhotoRec](http://www.cgsecurity.org/)

- Sebek
    - [Sebek](https://projects.honeynet.org/sebek/) - data capture
    - [Qebek](https://projects.honeynet.org/sebek/wiki/Qebek) - QEMU based Sebek. As Sebek, it is data capture tool for high interaction honeypot.
    - [xebek](https://code.google.com/p/xebek/) - Sebek on Xen

- SSH proxy
    - [HonSSH ★141](tnich/honssh)

- Anti-Cheat
    - [Minecraft honeypot](http://www.curse.com/bukkit-plugins/minecraft/honeypot)

- behavioral analysis tool for win32
    - [Capture BAT](https://www.honeynet.org/node/315)

- Live CD
    - [DAVIX](http://davix.secviz.org)

- Spamtrap
    - [Mailoney ★103](awhitehatter/mailoney) - SMTP honeypot, Open Relay, Cred Harvester written in python.
    - [Spampot.py](http://woozle.org/%7Eneale/src/python/spampot.py)
    - [Spamhole](http://www.spamhole.net/)
    - [spamd](http://www.openbsd.org/cgi-bin/man.cgi?query=spamd&apropos=0&sektion=0&manpath=OpenBSD+Current&arch=i386&format=html)
    - [Mail::SMTP::Honeypot](http://search.cpan.org/~miker/Mail-SMTP-Honeypot-0.11/Honeypot.pm) - perl module that appears to provide the functionality of a standard SMTP server
    - [honeypot ★1 ⏳1Y](jadb/honeypot) - The Project Honey Pot un-official PHP SDK
    - [SpamHAT ★14 ⏳1Y](miguelraulb/spamhat) - Spam Honeypot Tool
    - [SendMeSpamIDS.py ★8](johestephan/SendMeSpamIDS.py) Simple SMTP fetch all IDS and analyzer
    - [Shiva ★87](shiva-spampot/shiva) - Spam Honeypot with Intelligent Virtual Analyzer
        - [Shiva The Spam Honeypot Tips And Tricks For Getting It Up And Running](https://www.pentestpartners.com/blog/shiva-the-spam-honeypot-tips-and-tricks-for-getting-it-up-and-running/)

- Distributed spam tracking
    - [Project Honeypot](https://www.projecthoneypot.org)

- Commercial honeynet
    - [Specter](http://www.specter.com/default50.htm)
    - [Netbait](http://netbaitinc.com/)
    - [HONEYPOINT SECURITY SERVER](http://microsolved.com/HoneyPoint-server.html) - distributed honeypot, includes IT and SCADA emulators

- Server (Bluetooth)
    - [Bluepot ★20 ⏳1Y](andrewmichaelsmith/bluepot)

- Dynamic analysis of Android apps
    - [Droidbox](https://code.google.com/p/droidbox/)

- Dockerized Low Interaction packaging
    - [Manuka ★11 ⏳2Y](andrewmichaelsmith/manuka)
    - [Dockerized Thug](https://hub.docker.com/r/honeynet/thug/)
    - [Dockerpot ★96 ⏳2Y](mrschyte/dockerpot) A docker based honeypot.
    - [Docker honeynet ★9 ⏳2Y](sreinhardt/Docker-Honeynet) Several Honeynet tools set up for Docker containers

- Network analysis
    - [Quechua](https://bitbucket.org/zaccone/quechua)

- SIP Server
    - [Artemnesia VoIP](http://artemisa.sourceforge.net)

- Malware collection
    - [Honeybow](http://honeybow.mwcollect.org/)
    
- IOT Honeypot
    - [HoneyThing ★46 ⏳1Y](omererdem/honeything) - TR-069 Honeypot

- Honeytokens
    - [Honeybits ★41](0x4D31/honeybits) - A tool that can be used to create and place breadcrumbs and honeytokens to lead the attackers to honeypots (in production environment)
    - [CanaryTokens ★119](thinkst/canarytokens)
    - [dcept ★353](secureworks/dcept) - A tool for deploying and detecting use of Active Directory honeytokens

## <a name="honeyd"></a> Honeyd Tools

- Honeyd plugin
    - [Honeycomb](http://www.honeyd.org/tools.php)

- Honeyd viewer
    - [Honeyview](http://honeyview.sourceforge.net/)

- Honeyd to MySQL connector
    - [Honeyd2MySQL](http://bruteforce.gr/honeyd2mysql)

- A script to visualize statistics from honeyd
    - [Honeyd-Viz](http://bruteforce.gr/honeyd-viz)

- Honeyd UI
    - [Honeyd configuration GUI](http://www.citi.umich.edu/u/provos/honeyd/ch01-results/1/) - application used to configure
the honeyd daemon and generate configuration files

- Honeyd stats
    - [Honeydsum.pl](https://github.com/DataSoft/Honeyd/blob/master/scripts/misc/honeydsum-v0.3/honeydsum.pl)

## <a name="analysis"></a> Network and Artifact Analysis

- Sandbox
    - [RFISandbox](http://monkey.org/~jose/software/rfi-sandbox/) - a PHP 5.x script sandbox built on top of [funcall](https://pecl.php.net/package/funcall)
    - [dorothy2 ★166 ⏳2Y](m4rco-/dorothy2) - A malware/botnet analysis framework written in Ruby
    - [COMODO automated sandbox](https://help.comodo.com/topic-72-1-451-4768-.html)
    - [Argos](http://www.few.vu.nl/argos/) - An emulator for capturing zero-day attacks
    - [libemu ★19](buffer/libemu) - Shellcode emulation library, useful for shellcode detection.
    - [Pylibemu ★77](buffer/pylibemu) - A Libemu Cython wrapper.
    - [imalse ★5 ⏳3Y](hbhzwj/imalse) - Integrated MALware Simulator and Emulator.
    - [Cuckoo](https://cuckoosandbox.org/) - he leading open source automated malware analysis system.

- Sandbox-as-a-Service
    - [malwr.com](https://malwr.com/) - free malware analysis service and community.
    - [detux.org](http://detux.org) - Multiplatform Linux Sandbox.
    - [Joebox Cloud](https://jbxcloud.joesecurity.org/login) - analyzes the behavior of malicious files including PEs, PDFs, DOCs, PPTs, XLSs, APKs, URLs and MachOs on Windows, Android and Mac OS X for suspicious activities.
    - [VirusTotal](https://www.virustotal.com/)
    - [Hybrid Analysis](https://www.hybrid-analysis.com) - a free malware analysis service powered by Payload Security that detects and analyzes unknown threats using a unique Hybrid Analysis technology.

## <a name="visualizers"></a> Data Tools

- Front Ends
    - [Tango ★191](aplura/Tango) - Honeypot Intelligence with Splunk.
    - [Django-kippo ★10 ⏳4Y](jedie/django-kippo) - Django App for kippo SSH Honeypot.
    - [Wordpot-Frontend ★0 ⏳1Y](GovCERT-CZ/Wordpot-Frontend) - a full featured script to visualize statistics from a Wordpot honeypot.
    - [Shockpot-Frontend ★0 ⏳1Y](GovCERT-CZ/Shockpot-Frontend) - a full featured script to visualize statistics from a Shockpot honeypot. 
    - [honeypotDisplay ★2 ⏳1Y](Joss-Steward/honeypotDisplay) - A flask website which displays data I've gathered with my SSH Honeypot. 
    - [honeyalarmg2 ★3](schmalle/honeyalarmg2) - Simplified UI for showing honeypot alarms.
    - [DionaeaFR ★33 ⏳2Y](rubenespadas/DionaeaFR) - Front Web to Dionaea low-interaction honeypot.

- Visualization
    - [Kippo-Graph](http://bruteforce.gr/kippo-graph) - a full featured script to visualize statistics from a Kippo SSH honeypot.
    - [Kippo stats ★17 ⏳6Y](mfontani/kippo-stats) - Mojolicious app to display statistics for your kippo SSH honeypot. 
    - [HoneyStats](http://sourceforge.net/projects/honeystats/) - A statistical view of the recorded activity on a Honeynet. 
    - [HoneyMap ★173](fw42/honeymap) - Real-time websocket stream of GPS events on a fancy SVG world map. 
    - [HoneyMalt ★9 ⏳2Y](SneakersInc/HoneyMalt) - Maltego tranforms for mapping Honeypot systems.
    - [Glastopf Analytics](https://github.com/vavkamil/Glastopf-Analytics)
    - [Afterglow Cloud ★14 ⏳4Y](ayrus/afterglow-cloud)
    - [Afterglow](http://afterglow.sourceforge.net/)
    - [ovizart ★43 ⏳4Y](oguzy/ovizart) - visual analysis for network traffic. 
    - [HpfeedsHoneyGraph ★9 ⏳4Y](yuchincheng/HpfeedsHoneyGraph) - a visualization app to visualize hpfeeds logs.
    - [Acapulco ★8 ⏳1Y](hgascon/Acapulco4HNP) - Automated Attack Community Graph Construction.
    - [Sebek Dataviz](http://www.honeynet.org/gsoc/project4) - Sebek data visualization
    

## <a name="guides"></a>Guides

- [T-Pot: A Multi-Honeypot Platform](https://dtag-dev-sec.github.io/mediator/feature/2015/03/17/concept.html)
- [Honeypot (Dionaea and kippo) setup script ★60](andrewmichaelsmith/honeypot-setup-script)

- Deployment
    - [Dionaea and EC2 in 20 Minutes](http://andrewmichaelsmith.com/2012/03/dionaea-honeypot-on-ec2-in-20-minutes/) - a tutorial on setting up Dionaea on an EC2 instance
    - [honeypotpi ★12 ⏳2Y](free5ty1e/honeypotpi) - Script for turning a Raspberry Pi into a Honey Pot Pi

- Research Paper
    - [vEYE](http://link.springer.com/article/10.1007%2Fs10115-008-0137-3) - behavioral footprinting for self-propagating worm detection and profiling.
---
<p align="center">
	This list is a copy of <a href="paralax/awesome-honeypots">paralax/awesome-honeypots</a> with ranks
</p>
