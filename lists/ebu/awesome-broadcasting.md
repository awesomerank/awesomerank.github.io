<h1 align="center">
Ranked awesome lists, all in one place
</h1>
<p align="center">
	This list is a copy of <a href="ebu/awesome-broadcasting">ebu/awesome-broadcasting</a> with ranks
</p>
---
# Awesome Broadcasting [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg) ★59088](sindresorhus/awesome)
A curated list of amazingly awesome open source resources for broadcasters.

* [Awesome Broadcasting](#awesome-broadcasting)
  * [Audio over IP](#audio-over-ip)
  * [Codecs](#codecs)
  * [Companion Screens](#companion-screens)
  * [Connected TVs](#connected-tvs)
  * [Distributed Media Processing](#distributed-media-processing)
  * [DVB & WiFi](#dvb--wifi)
  * [Animation, Graphics & Video Playout](#animation-graphics--video-playout)
  * [Hybrid Radio](#hybrid-radio)
  * [Media Players](#media-players)
  * [Metadata](#metadata)
  * [Multimedia content processing](#multimedia-content-processing)
  * [Network & Storage Testing](#network--storage-testing)
  * [Quality Control](#quality-control)
  * [Radio Production](#radio-production)
  * [Software-defined radio](#software-defined-radio)
  * [Subtitling](#subtitling)
* [Resources](#resources)
  * [Blogs](#blogs)
  * [Websites](#websites)
* [Contributing](#contributing)

<!-- This page is available on http://ebu.io/opensource -->
## Audio over IP

* [Kamailio](http://www.kamailio.org/) - Open SIP server. Commonly used SIP server for Audio contribution over IP using SIP (EBU ACIP).
* [PJSIP](http://www.pjsip.org/) - Open Source multimedia library implementing SIP, SDP, RTP, STUN, TURN, and ICE. Used in some contribution equipment (dual licensing).
* [OpenOB](https://jamesharrison.github.io/openob/) - Open Outside Broadcast project for radio contribution links and studio-transmitter links based on Opus.

## Codecs

* [Opus](http://www.opus-codec.org) - Opus is a totally open, royalty-free, highly versatile audio codec. 
* [FLAC](https://www.xiph.org/flac/) - FLAC Free Lossless Audio Coding. Used by some broadcaster for audio exchange, storage.
* [Lame](http://lame.sourceforge.net/) - Lame, high quality MPEG Audio Layer III (MP3) encoder. (Warning, MP3 is not royalty free!).
* [TwoLame](http://www.twolame.org/) - TwoLame, MPEG Audio Layer 2 (MP2) encoder.
* [Turing Codec](http://turingcodec.org/) - Turing codec, an H.265/HEVC open source software encoder designed for fast and efficient video compression.

## Companion Screens

* [dvbcss-synctiming ★7](BBC/dvbcss-synctiming) - dvbcss-synctiming is a system for measuring how accurately a TV or companion are synchronised.
* [pydvbcss ★17](BBC/pydvbcss) - pydvbcss is library implementing the DVB Companion Screens and Streams protocols for accurately synchronising media playback between TVs and companions.

## Connected TVs

* [Cross-Platform Authentication](http://ebu.io/project/cpa) - CPA offers an open standard for associating any media device with an online identity.
* [HbbPlayer ★17](Samsung/HbbPlayer) - An HbbTV application which can playback media from a URL. Conforms to HbbTV and W3C specifications.
* [TAL](http://fmtvp.github.io/tal) - The TV Application Layer (TAL) is an open source library for building applications for Connected TV devices.

## Distributed Media Processing

* [StormCV ★95](sensorstorm/StormCV) - Apache Storm + OpenCV = large scale distributed image and video analysis.

## DVB & WiFi

* [DTT 2 IP ★8 ⏳1Y](ebu/dtt2ip) - Broadcast to IP conversion for Wifi indoor coverage.
* [DVB Inspector](https://sourceforge.net/projects/dvbinspector/) - DVB Inspector is an open-source DVB analyzer.
* [DVBlast](http://www.videolan.org/projects/dvblast.html) - DVBlast is a simple and powerful MPEG-2/TS demux and streaming application.
* [dvbshout ★4 ⏳5Y](njh/dvbshout) - Send DVB audio to a shoutcast server or a RTP stream.
* [Opencaster](http://www.avalpa.com/the-key-values/15-free-software/33-opencaster) - OpenCaster is a free and open source MPEG2 transport stream data generator and packet manipulator.
* [Project X](https://sourceforge.net/projects/project-x/) - DVB demux tool.
* [WiFiBroadcast](https://befinitiv.wordpress.com/wifibroadcast-analog-like-transmission-of-live-video-data/) - Analog-like transmission of live video data.

## Animation, Graphics & Video Playout

* [Aurena ★76 ⏳1Y](thaytan/aurena) - Aurena is a network distributed media playback system.
* [Blender](https://developer.blender.org/diffusion/) - 3D creation suite supporting 3D pipeline—modelling, rigging, animation, simulation, rendering, compositing and motion tracking, even video editing and game creation.
* [CasparCG](http://www.casparcg.com/) - CasparCG is a professional graphics and video play-out software, proven in 24/7 broadcasts since 2006.
* [i-Score](http://i-score.org/) - A free and open-source intermedia sequencer.

## Hybrid Radio

* [RadioDNS for Node.js ★1](bbc/node-radiodns) - Perform RadioDNS resolutions and service lookups in node.js.
* [RadioDNS Manager ★7 ⏳2Y](ebu/radiodns-plugit) - A platform to manage Hybrid Radio static services such as RadioVIS, RadioEPG and Service Following.
* [RadioTag.js ★6 ⏳1Y](ebu/radiotag.js) - RadioTag client library in JavaScript.
* [RadioVIS Html Player ★7 ⏳2Y](ebu/radiovis-html5player) - RadioVIS Player using WebSocket.
* [RadioVIS Demo ★13](bbc/RadioVisDemo) - RadioVIS client application in Python.
* [RadioVIS Stomp Server ★4](bbc/node-radiovis-stomp-server) - RadioVIS STOMP server written in node.js.

## Media Players

* [Dash.js ★6 ⏳1Y](ebu/dash.js) - A reference client implementation for the playback of MPEG DASH via Javascript and compliant browsers.
* [Kodi ★5974](xbmc/xbmc) - A software media player and entertainment hub for digital media.
* [Media4DPlayer ★4](ebu/media4Dplayer) - HTML5 player focused on accessibility.
* [Peaks.js](http://waveform.prototyping.bbc.co.uk/) - Browser-based audio waveform visualisation.
* [VLC](http://www.vlc.org) - Simple, fast and powerful media player. 
* [GPAC](http://gpac.wp.mines-telecom.fr/home/) - Multimedia player, packager and tools.
* [rx-player ★257](canalplus/rx-player) - HTML5/Javascript video player with some reactive programming inside, supporting MPEG-DASH and SmoothStreaming transports.

## Metadata

* [BMXlib](http://sourceforge.net/projects/bmxlib/) - Library and utilities to read and write broadcasting media files. Primarily supports the MXF file format.
* [EBUCore ★7](ebu/ebucore) - the Github for maintenance of the [EBUCore schema](https://tech.ebu.ch/docs/tech/tech3293.pdf).
* [jebu-core ★1](mikrosimage/jebu-core) - EBUCore XML Schema Java port. Java port of [TECH 3293](https://tech.ebu.ch/publications/tech3293) EBU CORE METADATA SET (EBUCore) SPECIFICATION v. 1.5, including new [Audio Definition Model](https://tech.ebu.ch/docs/tech/tech3364.pdf).
* [Ledger ★11](Streampunk/ledger) - Node.js implementation of the NMOS registration and discovery specifications.
* [MAJ API ★1 ⏳1Y](AMWA-TV/maj) - Pure Java library for reading and writing MXF and AAF files.
* [TV-Anytime ★2](ebu/tvanytime) - The tv-anytime schema github maintenance page.

## Multimedia content processing

* [AvTranscoder ★44](avTranscoder/avTranscoder) - Based on FFmpeg/LibAV libraries to support various video and audio formats, avTranscoder provides the high level API to re-wrap or transcode media easily. It also provide bindings for any usage in Java or Python.
* [Bento4 ★289](axiomatic-systems/Bento4) - Full-featured MP4 format and MPEG DASH C++ class library and tools.
* [Codem-isoboxer ★33](madebyhiro/codem-isoboxer) A small browser-based MPEG-4 (ISOBMFF) parser.
* [Dynamorse ★11](Streampunk/dynamorse) - IT swiss army knife - a Node-RED media pipeline builder, adding professional media processing nodes.
* [FFmpeg](http://ffmpeg.org) - A complete, cross-platform solution to record, convert and stream audio and video.
* [FFmbc](https://code.google.com/p/ffmbc/) - FFmpeg customized for broadcast and professional usage.
* [Flowblade ★539](jliljebl/flowblade) - A multitrack non-linear video editor.
* [GStreamer](https://gstreamer.freedesktop.org/) - A library for constructing graphs of media-handling components.
* [KFR](https://www.kfrlib.com/) - Fast, modern C++ DSP framework, DFT/FFT, Audio resampling, FIR/IIR, Biquad.
* [L-SMASH ★78](l-smash/l-smash) - A rigidly spec-compliant ISOBMFF library, which has full DASH muxing support.
* [LibAV](https://libav.org/) - Open source audio and video processing tools.
* [Libebur128](http://github.com/jiixyj/libebur128) - A library that implements the EBU R 128 standard for loudness normalisation.
* [Loudness Validator ★5](mikrosimage/loudness_validator) - A set of applications to analyse, visualise and correct the loudness.
* [MP4Box.js ★332](gpac/mp4box.js) - JavaScript library to process MP4 files in the browser (and in NodeJS).
* [MXFLib](http://sourceforge.net/projects/mxflib) - A multi-platform C++ library for reading and writing MXF files.
* [OBS-Studio ★6324](jp9000/obs-studio) - Software for live streaming and screen recording.
* [Open Broadcast Encoder](https://github.com/ob-encoder) - Broadcast encoder built from Open Source components.
* [Photon ★79](Netflix/photon) - Implementation of the SMPTE Material Exchange Format (MXF) file specification.
* [Snowmix](https://sourceforge.net/projects/snowmix/) - Live Video Mixer.
* [SoX](http://sox.sourceforge.net/) - The Swiss Army knife of sound processing programs. 
* [TuttleOFX](http://www.tuttleofx.org/) - TuttleOFX is an open source image processing framework based on OpenFX plugin standard.
* [UPipe ★35](cmassiot/upipe) - Upipe is primarily designed to be the core of a multimedia player, transcoder or streamer.
 
## Network & Storage Testing

* [BBC Media Storage Meter](http://sourceforge.net/projects/msmeter/) - An application for the testing of network attached storage, originally assumed to be used for the streaming of professional media.
* [SMPTE 2210-20 Analyzer ★5](ebu/smpte2110-analyzer) - An analyzer to inspect network packets generated in accordance with the SMPTE ST 2110 specification.

## Quality Control

* [BeaqleJS ★30](HSU-ANT/beaqlejs) - BeaqleJS provides a framework to create browser based listening tests for subjective audio quality assessment.
* [MediaConch](https://mediaarea.net/MediaConch/) - Implementation checker, policy checker, & reporter for Matroska, FFV1, & PCM.
* [MediaInfo](https://mediaarea.net/en/MediaInfo) - MediaInfo provides a convenient unified display of the most relevant technical and tag data for video and audio files.
* [MXF Inspect](http://www.myriadbits.com/) - A Windows tool to display the internal structure of an MXF (Material eXchange Format) file.
* [QCTools ★82](bavc/qctools) - Quality Control tools for video preservation to analyse digitized video files.
* [Sonic Visualiser](http://www.sonicvisualiser.org/) - An application for viewing and analysing the contents of music audio files.
* [VMAF ★307](Netflix/vmaf) - Perceptual video quality assessment based on multi-method fusion.
* [Wisual ★3 ⏳2Y](MarcAntoine-Arnaud/wisual) - A web service for Visual Quality Assessment, which supports PSNR, SSIM, VQM, etc.

## Radio Production

* [Audacity](http://audacity.sourceforge.net/) - Cross-platform software for recording and editing sounds.
* [Airtime](https://www.sourcefabric.org/en/airtime/) - Radio management application for remote broadcast automation (via web-based schedule).
* [Liquidsoap ★295](savonet/liquidsoap) - A Swiss army knife for multimedia streaming ([documentation](http://liquidsoap.fm/index.html)).
* [Rivendell](http://www.rivendellaudio.org/) - Complete radio broadcast automation solution, translated to many languages and used worldwide. 

## Software-defined radio

* [ODR-mmbTools](https://www.opendigitalradio.org) - Fork, continuation of CRC-mmbTools. Adding new features for 24/24 365/365 live operation, DAB+, associated data (slideshow, text), distributed infrastructure, SFN.

## Subtitling

* [CCExtractor](http://ccextractor.sourceforge.net/about-ccextractor.html) - A tool that analyzes video files and produces stand-alone subtitle files.
* [GStreamer TTML subtitling package ★6 ⏳1Y](bbc/gst-ttml-subtitles) - A means for GStreamer pipelines to parse and render  EBU-TT-D (TTML) subtitles. 
* [EBU-TT-D Subtitling within dash.js](https://github.com/ebu/dash.js/tree/ebu-subtitling-dev) - The original fork of dash.js to experiment with XML based subtitles like EBU-TT-D within dash.js. Uses an HTML/CSS overlay. Has since been integrated into [dash.js ★6 ⏳1Y](ebu/dash.js).
* [EBU-TT-D W3C XML Schema ★6 ⏳1Y](ebu/ebu-tt-d-xsd) - Informative EBU-TT-D XML Schema to support the implementation of EBU Tech 3380.
* [EBU-TT Live Interoperability Toolkit ★10](ebu/ebu-tt-live-toolkit) - A set of components for generating, testing and distributing subtitle documents in the [EBU-TT Live](https://tech.ebu.ch/publications/tech3370) format.
* [imscJS ★11](sandflow/imscJS) - JavaScript library for rendering IMSC1 Text and Image Profile documents to HTML5.
* [IRT EBU-TT-D Application Samples ★4](IRT-Open-Source/irt-ebu-tt-d-application-samples) - EBU-TT-D sample files, related PNG images and mp4 videos showing how they should be rendered.
* [Subtitle Edit](http://www.nikse.dk/SubtitleEdit) - An editor for subtitles.
* [Subtitling Conversion Framework (SCF) ★23](Irt-Open-Source/scf) - A set of modules for converting subtitle formats. Main target is the conversion of EBU STL and EBU-TT subtitle files. Alpha release.
* [Timed Text Toolkit (ttt) ★14](skynav/ttt) - A collection of related tools that provide support for or make use of the W3C Timed Text Markup Language (TTML).

# Resources
Various resources, such as books, websites and articles, for improving your skills and knowledge.

## Blogs

* [BBC R&D](http://bbc.co.uk/rd) - BBC Research and Development. Checkout the weekly notes.
* [3D CineCast](http://3dcinecast.blogspot.ch/) - A curation about new media technologies.
* [Canal+](http://canalplus.github.io/) - CANAL+ Open Source Community.
* [The Netflix Tech Blog](http://techblog.netflix.com/) - A Netflix blog focused on technology and technology issues.
* [Youtube Engineering and Developers Blog](http://youtube-eng.blogspot.com) - What's happening with engineering and developers at YouTube.

## Websites
*Useful broadcasting related websites.*

* [EBU.io](http://www.ebu.io) - A platform for agile collaboration.

<!-- This page is available on http://ebu.io/opensource -->

# Contributing
Please see [CONTRIBUTING](https://github.com/ebu/awesome-broadcasting/blob/master/CONTRIBUTING.md) for details.
---
<p align="center">
	This list is a copy of <a href="ebu/awesome-broadcasting">ebu/awesome-broadcasting</a> with ranks
</p>
<script>
  (function(i,s,o,g,r,a,m){i['GoogleAnalyticsObject']=r;i[r]=i[r]||function(){
  (i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),
  m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)
  })(window,document,'script','https://www.google-analytics.com/analytics.js','ga');

  ga('create', 'UA-100705027-1', 'auto');
  ga('send', 'pageview');

</script>
