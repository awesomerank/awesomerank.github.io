<h1 align="center">
Ranked awesome lists, all in one place
</h1>
<p align="center">
	This list is a copy of <a href="hobbyquaker/awesome-mqtt">hobbyquaker/awesome-mqtt</a> with ranks
</p>
---
# Awesome MQTT [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg) ★59088](sindresorhus/awesome) [![Build Status](https://travis-ci.org/hobbyquaker/awesome-mqtt.svg?branch=master)](https://travis-ci.org/hobbyquaker/awesome-mqtt)



> A curated list of MQTT related stuff.

MQTT is a lightweight client-server publish/subscribe messaging protocol, optimized for high-latency or unreliable networks. This protocol is a good choice for Internet of Things applications, Telemetry, Sensor Networks, Smart Metering, Home Automation, Messaging and Notfication Services.   

## Table of Contents

- [Community Resources](#community-resources)
- [Broker](#broker)
- [Tools](#tools)
- [Clients](#clients)
- [Scripting](#scripting)
- [Interfaces](#interfaces)
    - [Makers](#makers)
    - [Industry](#industry)
    - [Telephony, PBX](#telephony-pbx)
    - [Operating System](#operating-system)
    - [Monitoring](#monitoring)
    - [Location Tracking](#location-tracking)
    - [Logging](#logging)
    - [Smart Home Hardware Interfaces](#smart-home-hardware-interfaces)
    - [Smart Home Integration Software](#smart-home-integration-software)
    - [Lighting](#lighting)
    - [Home Entertainment](#home-entertainment)
    - [Smart Metering](#smart-metering)
    - [Messaging](#messaging)
    - [Misc](#misc)
- [Visualization, Dashboards](#visualization-dashboards)
- [Architecture, Convention](#architecture-convention)    


### Community Resources

* [mqtt.org](http://mqtt.org/).
* [MQTT community wiki](https://github.com/mqtt/mqtt.github.io/wiki).
* [Google Groups: MQTT](https://groups.google.com/forum/#!forum/mqtt).
* [IRC channel #mqtt on the freenode network](irc://irc.freenode.net/mqtt).
* [A list of public brokers](http://moxd.io/2015/10/public-mqtt-brokers/).

#### Blogs

* [Dominik Obermaier (Forkbomb Blog)](http://forkbomb-blog.de/category/mqtt)
* [Jan-Piet Mens](http://jpmens.net/)
* [Nick O'Leary](http://knolleary.net/)


### Broker

* [ActiveMQ](http://activemq.apache.org/) - A fast Java multiprotocol messaging and Integration Patterns server.
* [eMQTT](http://emqtt.io/) - The Massively Scalable MQTT Broker written in Erlang/OTP.
* [hbmqtt ★185](beerfactory/hbmqtt) - Python MQTT broker using asyncio.
* [hrotti ★74](alsm/hrotti) - A MQTT broker written in Go.
* [HiveMQ](http://www.hivemq.com/) - Java based commercial MQTT Broker.
* [Moquette ★597](andsel/moquette) - Java MQTT lightweight broker.
* [Mosca](http://www.mosca.io/) - Mosca is a node.js mqtt broker, which can be used Standalone or Embedded in another Node.js application.
* [Mosquitto](http://mosquitto.org/) - "The" Open Source MQTT Broker.
* [RabbitMQ](https://www.rabbitmq.com/mqtt.html) - RabbitMQ offers a MQTT Adapter.
* [SurgeMQ](http://zhen.org/categories/surgemq/) - High Performance MQTT Server and Client Libraries in Go.
* [VerneMQ](https://vernemq.com/) - an Apache2 licensed distributed MQTT broker, developed in Erlang.
* [Vert.x MQTT server ★27](vert-x3/vertx-mqtt-server) - This Vert.x component provides a server which is able to handle connections, communication and messages exchange with remote MQTT clients.


### Tools

* [imqtt ★18](shafreeck/imqtt) - Interactive MQTT packet manipulation shell based on IPython.
* [mqtt-admin ★41](hobbyquaker/mqtt-admin) - Web based MQTT frontend. [Direct Link](https://hobbyquaker.github.io/mqtt-admin/).
* [mqtt-benchmark ★105 ⏳5Y](chirino/mqtt-benchmark) - A benchmarking tool for MQTT Servers.
* [mqtt-fuzz ★30 ⏳2Y](F-Secure/mqtt_fuzz) - A simple fuzzer for the MQTT protocol.
* [MQTT.fx](http://mqttfx.jfx4ee.org/) - MQTT.fx is a MQTT Client written in Java based on Eclipse Paho. Supports scripting.
* [MQTTInspector ★51 ⏳1Y](ckrey/MQTTInspector) - A general MQTT testing app for iOS (iPhone and iPad).
* [MQTTLens](https://chrome.google.com/webstore/detail/mqttlens/hemojaaeigabkbcookmlgmdigohjobjm) - A Google Chrome application, which connects to a MQTT broker and is able to subscribe and publish to MQTT topics.
* [mqtt-malaria ★150 ⏳1Y](remakeelectric/mqtt-malaria) - scalability and load testing utilities for MQTT environments.
* [mqtt-spy](http://kamilfb.github.io/mqtt-spy/) - Java based MQTT frontend. Supports scripting.
* [mqtt-utils ★6 ⏳3Y](dsell/mqtt-utils) - a collection of MQTT utilities.
* [mqtt-wall ★12](bastlirna/mqtt-wall) - Subscription only web-based client – like Twitter wall for MQTT.
* [mqtt-wildcard ★4](hobbyquaker/mqtt-wildcard) - Node.js Module to match a MQTT Topic against Wildcards.
* [Python MQTT Client Shell ★11](bapowell/python-mqtt-client-shell) - a text console-based, interactive shell for exercising various tasks associated with MQTT client communications.
* [Wireshark-MQTT ★56 ⏳1Y](menudoproblema/Wireshark-MQTT) - MQTT dissector for Wireshark.

### Clients

* [CocoaMQTT ★452](emqtt/CocoaMQTT) - MQTT for iOS and OS X written with Swift.
* [emqttc ★90](emqtt/emqttc) - Asynchronous Erlang MQTT Client.
* [Moscapsule ★159](flightonary/Moscapsule) - MQTT Client for iOS written in Swift.
* [hbmqtt ★185](beerfactory/hbmqtt) - Python MQTT client using asyncio.
* [M2Mqtt](https://m2mqtt.wordpress.com/) - a MQTT client available for all .Net platforms (.Net Framework, .Net Compact Framework and .Net Micro Framework) and WinRT platforms (Windows 8.1, Windows Phone 8.1 and Windows 10).
* [Mosquitto-PHP ★182](mgdm/Mosquitto-PHP) - A wrapper for the Mosquitto MQTT client library for PHP.
* [mqtt-client ★11 ⏳2Y](centamiv/mqtt-client) - A Polymer Web Component that implements a MQTT client (uses Paho mqttws31.js).
* [MQTT-Client-Framework ★634](ckrey/MQTT-Client-Framework) - iOS, OSX, tvOS native ObjectiveC MQTT Client Framework.
* [mqtt.dart ★8 ⏳2Y](jnguillerme/mqtt.dart) - dart mqtt client.
* [mqtt-elements ★18](mqttjs/mqtt-elements) - Polymer elements for MQTT.
* [mqttex ★38 ⏳2Y](alfert/mqttex) - MQTT implementation in Elixir.
* [MQTTKit ★355](mobile-web-messaging/MQTTKit) - MQTT Objective-C client for iOS.
* [mqtt_client_cpp ★17](redboltz/mqtt_client_cpp) - MQTT client for C++14 based on Boost.Asio.
* [mqtt_lua](http://geekscape.github.io/mqtt_lua/) - MQTT Client library for the Lua language.
* [MQTT.js](https://github.com/mqttjs) - MQTT client for Node.js.
* [mqtt-rs ★21](zonyitoo/mqtt-rs) - MQTT protocol library for Rust.
* [Paho](http://www.eclipse.org/paho/) - open-source client implementations (C/C++, Java, Python, Javascript, Go, C#).
* [pubsubclient ★1184](knolleary/pubsubclient) - A client library for the Arduino Ethernet Shield that provides support for MQTT.
* [rumqtt ★16](AtherEnergy/rumqtt) - A fast, lock free pure rust mqtt cilent.
* [ruby-mqtt ★266](njh/ruby-mqtt) - Pure Ruby gem that implements the MQTT protocol.
* [tcl-mqtt ★2 ⏳3Y](Tingenek/tcl-mqtt) - Small library to connect to a matt broker. Very, very basic.
* [TMQTTClient](http://jamiei.com/blog/code/mqtt-client-library-for-delphi/) - MQTT Client Library for Delphi.
* [wolfMQTT](https://wolfssl.com/wolfSSL/Products-wolfmqtt.html) - a client implementation of the MQTT written in C for embedded use. It supports SSL/TLS via the wolfSSL library.


### Scripting

* [logic4mqtt ★9 ⏳1Y](owagner/logic4mqtt) - Java based Logic and scripting engine for use with MQTT. Uses Java's general scripting interface, so scripts can be written in a multitude of languages like Javascript, Groovy etc.
* [mqtt-scripts ★8 ⏳1Y](hobbyquaker/mqtt-scripts) - Node.js based script runner.
* [Node-RED](http://nodered.org/) - A visual tool for wiring the Internet of Things.


### Interfaces

#### Makers

* [arduinoTemps2mqtt ★8 ⏳1Y](matbor/arduinoTemps2mqtt) - Arduino sketch, grab Onewire Temperature's and publish to a mqtt broker.
* [esp_mqtt ★682](tuanpmt/esp_mqtt) - MQTT client library for ESP8266.
* [mqtt-ir-transceiver ★25](enc-X/mqtt-ir-transceiver) - ESP8266 based bidirectional gateway between MQTT and IR. Use with PlatformIO.
* [MySensors](https://www.mysensors.org/) - Arduino NRF24L01 based sensor network with support for an MQTT gateway
* [nodemcu-gpiomqtt ★1](hobbyquaker/nodemcu-gpiomqtt) - Lua script to connect ESP8266 GPIOs to MQTT.
* [pubsubclient ★1184](knolleary/pubsubclient) - A client library for the Arduino Ethernet Shield that provides support for MQTT.
* [RFM69-MQTT-client ★76](computourist/RFM69-MQTT-client) - Arduino RFM69 based sensors and MQTT gateway.
* [rpi2mqtt ★8](hobbyquaker/rpi2mqtt) - Connect a RaspberryPis GPIOs and 1-Wire Temperature Sensors to MQTT.
* [xbee2mqtt ★16 ⏳1Y](xoseperez/xbee2mqtt) - XBee to MQTT gateway.



#### Industry

* [modbus2mqtt ★26](owagner/modbus2mqtt) - Modbus master which publishes register values via MQTT.
* [mqtt2opcua ★20](nzfarmer1/mqtt2opcua) - Bi Directional MQTT to OPCUA Bridge.


#### Telephony, PBX

* [agi-mqtt ★17 ⏳3Y](zeha/agi-mqtt) - Interface between Asterisk and MQTT.
* [fritz2mqtt ★2](akentner/fritz2mqtt) - Connect FRITZ!Box to MQTT.


#### Operating System

* [mqttlauncher ★23 ⏳3Y](jpmens/mqtt-launcher) - Execute shell commands triggered by published MQTT messages.
* [mqtt-os-status ★6 ⏳3Y](oskarhagberg/mqtt-os-status) - Operating-system related data, published to an MQTT broker at fixed intervals.
* [mqttpc ★1](hobbyquaker/mqttpc) - Control processes via MQTT. Ability to send signals via MQTT and to publish stdout/stderr or pipe MQTT payloads into stdin.
* [mqttwatchdir ★15 ⏳2Y](jpmens/mqtt-watchdir) - Recursively watch a directory for modifications and publish file content to an MQTT broker.
* [psmqtt ★10](eschava/psmqtt) - Utility reporting system health and status via MQTT.


#### Monitoring

* [check-mqtt ★19](jpmens/check-mqtt) - A Nagios/Icinga plugin for checking connectivity to an MQTT broker.
* [notify-by-mqtt ★10 ⏳3Y](jpmens/notify-by-mqtt) - a Nagios/Icinga notification module which wraps data into JSON and fires it off to an MQTT broker.


#### Location tracking

* [Owntracks](http://owntracks.org/) - Location tracking and geofencing for MQTT.


#### Logging

* [mqttcollect ★14](jpmens/mqttcollect) - collectd "Exec" plugin for MQTT.
* [graylog-plugin-mqtt ★6 ⏳1Y](graylog-labs/graylog-plugin-mqtt) - MQTT Input Plugin for Graylog.
* [mqtt2graphite ★44 ⏳1Y](jpmens/mqtt2graphite) - Subscribe to MQTT topics and push to Graphite's Carbon server.
* [influx4mqtt ★5 ⏳1Y](hobbyquaker/influx4mqtt) - Subscribe to MQTT topics and insert into InfluxDB.
* [mqtthandler ★5 ⏳1Y](changyuheng/MQTTHandler) - A Python logging handler module for MQTT.


#### Smart Home Hardware Interfaces

* [aqara-mqtt ★26](monster1025/aqara-mqtt) - Aqara (Xiaomi) Gateway to MQTT bridge.
* [cul2mqtt ★1](hobbyquaker/cul2mqtt) - Interface between [Busware CUL](http://shop.busware.de/product_info.php/cPath/1/products_id/29) (868MHz RF-Devices like ELV FS20, HMS, EM, ...) and MQTT.
* [eno2mqtt ★5 ⏳1Y](owagner/eno2mqtt) - Interface between an Enocean USB300 (TCM310) adapter and MQTT.
* [Evohome2mqtt ★0](svrooij/evohome2mqtt) - MQTT Interface for the Honeywell Evohome system.
* [hm2mqtt.js ★6](hobbyquaker/hm2mqtt.js) - Interface between EQ-3's Homematic line of smarthome devices and MQTT. Supports Homematic IP.
* [knx2mqtt ★9 ⏳1Y](owagner/knx2mqtt) - Interface between the KNX home automation standard and MQTT.
* [mqtt2homekit](https://github.com/forty2/mqtt2homekit) - Roughly the opposite of [homekit2mqtt ★73](hobbyquaker/homekit2mqtt): Control your HomeKit-enabled devices with MQTT and without Siri or iPhone.
* [mqtt-dss-bridge ★3 ⏳1Y](cgHome/mqtt-dss-bridge) - MQTT digitalSTROM-Server Bridge.
* [node-lox-mqtt-gateway ★7](alladdin/node-lox-mqtt-gateway) - Gateway for Loxone™ miniserver to communicate with mqtt broker.


#### Smart Home Integration Software

* [control-freak ★2](xblox/control-freak) - IDE for IoT & friends. Built in MQTT support.
* [Domoticz](http://www.domoticz.com/) - Domoticz beta supports MQTT.
* [FHEM](http://fhem.de/fhem.html) has a [MQTT module](http://fhem.de/commandref.html#MQTT) since V5.6.
* [Home Assistant](https://home-assistant.io/) has a MQTT component.
* [Homegear](https://www.homegear.eu/index.php/Main_Page) has build in MQTT support.
* [homekit2mqtt](https://github.com/hobbyquaker/homekit2mqtt) - Interface between [HAP-NodeJS ★1386](KhaosT/HAP-NodeJS) and MQTT. Control MQTT connected devices with Siri or HomeKit Apps.
* [Home.Pi ★174 ⏳2Y](denschu/home.pi) is based on MQTT.
* [ioBroker](https://github.com/ioBroker) has a [MQTT adapter ★8](ioBroker/ioBroker.mqtt).
* [Lelylan](http://www.lelylan.com/) - IOT Cloud Platform. Microservices Architecture. For Developers.
* [Node-RED](https://nodered.org/) - A visual tool for wiring the Internet of Things, has native MQTT Support.
* [openHAB](https://github.com/openhab) has a [MQTT binding](https://github.com/openhab/openhab1-addons/wiki/MQTT-Binding).
* [pimatic](https://pimatic.org/) has a MQTT plugin.


#### Lighting

* [chromoflex2mqtt ★2 ⏳1Y](owagner/chromoflex2mqtt) - Control Chromoflex USP3 RGB LED modules via MQTT.
* [h801/mqtt](https://github.com/open-homeautomation/h801/tree/master/mqtt) - Alternative firmware for the H801 LED dimmer that uses MQTT as a control channel.
* [hue2mqtt ★27](owagner/hue2mqtt) - Interface between the Philips Hue bridge and MQTT.
* [mqtt-dmx-sequencer ★4](hobbyquaker/mqtt-dmx-sequencer) - Control DMX devices via Art-Net by MQTT.
* [TRADFRI2MQTT ★22](hardillb/TRADFRI2MQTT) - MQTT Bridge for IKEA TRÅDFRI Light Gateway.


#### Home Entertainment

* [airtunes2mqtt ★8 ⏳1Y](hobbyquaker/airtunes2mqtt) - MQTT controlled Multi-Room Audio with Airplay/Airtunes Devices.
* [bravia2mqtt ★0](forty2/bravia2mqtt) - Control your Sony Bravia TV with MQTT.
* [chromecast-mqtt-connector ★5](nohum/chromecast-mqtt-connector) - Control your Google Chromecast devices using MQTT.
* [kodi2mqtt ★41](owagner/kodi2mqtt) - Interface between a Kodi mediacenter instance and MQTT.
* [harmony-api ★121](maddox/harmony-api) - A simple server allowing you to query/control multiple local Harmony Home Hubs over HTTP or MQTT.
* [lgtv2mqtt ★8](hobbyquaker/lgtv2mqtt) - Interface between LG WebOS Smart TVs and MQTT.
* [lirc2mqtt ★6](hobbyquaker/lirc2mqtt) - Send and receive infrared via [LIRC](www.lirc.org).
* [mqtt2atlonamatrix ★0](forty2/mqtt2atlonamatrix) - Control Atlona HDMI matrix switches with MQTT.
* [mqtt2tivoremote ★0](forty2/mqtt2tivoremote) - Make TiVo DVR remote control available through an mqtt-smarthome style interface.
* [onkyo2mqtt ★5 ⏳1Y](owagner/onkyo2mqtt) - Interface between Onkyo AVR's EISCP network remote protocol and MQTT. Uses the onkyo-eiscp library.
* [VLC MQTT Module](https://wiki.videolan.org/Documentation:Modules/mqtt/) - Control VLC via MQTT.
* [xbmc2mqtt ★5 ⏳2Y](gordonjcp/xbmc-mqtt) - A simple plugin for XBMC to listen for a particular topic on an MQTT broker, and display a popup message.
* [yamaha-avr2mqtt ★3 ⏳1Y](akentner/yamaha-avr2mqtt) - A simple adapter for connection Yamaha AVR to MQTT.


#### Smart Metering

* [bcontrol2mqtt ★0 ⏳1Y](hobbyquaker/bcontrol2mqtt) - Publish measurements from [TQ Energy Manager](https://www.tq-group.com/produkte/produktdetail/prod/energy-manager/extb/Main/) to MQTT.


#### Messaging

* [mqtt-irc-bot ★12 ⏳1Y](dobermai/mqtt-irc-bot) - A MQTT to IRC / IRC to MQTT bridge or bot.
* [mqttwarn ★543](jpmens/mqttwarn) - Subscribe to MQTT topics (with wildcards) and notifiy pluggable services.
* [twitter-to-mqtt ★12 ⏳4Y](knolleary/twitter-to-mqtt) - A python daemon that uses the Twitter Streaming API to access tweets and republishes them to an MQTT topic.


#### Misc

* [AlexaMqttBridge ★0](mhdawson/AlexaMqttBridge) - Bridge between Amazon Alexa and Mqtt.
* [dashbutton2mqtt ★6](hobbyquaker/dashbutton2mqtt) - Publish Amazon Dash Button presses to MQTT.
* [flowerpower2mqtt ★3 ⏳1Y](hobbyquaker/flowerpower2mqtt) - Publish measurements from Parrot Flower Power plant sensors to MQTT.
* [haiku2mqtt ★0](forty2/haiku2mqtt) - A bridge between Haiku smart fans and MQTT.
* [homely ★4](baol/homely) - collection of Go daemons for connecting Domoticz and other stuff.
* [leaf-python-mqtt ★7](glynhudson/leaf-python-mqtt) - Extract data from Nissan Leaf API and post to mqtt.
* [node-mqtt-for-anki-overdrive ★32 ⏳1Y](IBM-Bluemix/node-mqtt-for-anki-overdrive) - Node.js Controller and MQTT API for Anki Overdrive.
* [parrot-sample ★17 ⏳1Y](IBM-Bluemix/parrot-sample) - Sample code which uses MQTT to control a Parrot AR Drone.
* Tasker (Automation for Android) [MQTT Publisher Plugin](https://play.google.com/store/apps/details?id=net.nosybore.mqttpublishplugin).
* [wlan-thermo-mqtt-addon](https://bitbucket.org/IOcastor/wlan-thermo-mqtt-addon/) - Addon for a popular DIY barbecue thermometer.

### Visualization, Dashboards

* [Crouton](http://crouton.mybluemix.net/crouton/gettingStarted) - A dashboard that taps into your IOT network, using only MQTT and JSON.
* [d3-MQTT-Topic-Tree ★58](hardillb/d3-MQTT-Topic-Tree) - A MQTT Topic Tree viewer using the d3 collapsable tree and MQTT over websockets.
* [HelloIoT ★1](adrianromero/helloiot) - HelloIoT is a MQTT client and dashboard application.
* [HOMR-REACT ★4](klauserber/homr-react) - A configurable MQTT Visualization.
* [node-red-dashboard ★200](node-red/node-red-dashboard) - A dashboard UI for Node-RED.
* [mqtt2highcharts ★39](matbor/mqtt2highcharts) - plotting live numbered data from a subscribed mqtt topic using highcharts.
* [MQTT Dash](https://play.google.com/store/apps/details?id=net.routix.mqttdash&hl=de) - Android App: With the app you can create dashboards for your MQTT enabled IoT Smart Home devices and applications.
* [mqtt-panel ★144](fabaff/mqtt-panel) - A web interface for MQTT.
* [mqtt-svg-dash ★30 ⏳4Y](jpmens/mqtt-svg-dash) - Subscribe to MQTT, extract JSON from a message and make lights blink on an SVG page.
* [thingsboard](https://thingsboard.io/) - Device management, data collection, processing and visualization for your IoT projects.

Other tools that can be used to create Visualization/Dashboards can be found under [Smart Home Integration Software](#smart-home-integration-software)


### Architecture, Convention

* [Homie ★197](marvinroger/homie) - A lightweight MQTT convention for the IoT.
* [mqtt-smarthome ★94](mqtt-smarthome/mqtt-smarthome) - Smart home automation with MQTT as the central message bus - Architectural proposal.


## Contribute

Contributions welcome! Read the [contribution guidelines](https://github.com/hobbyquaker/awesome-mqtt/blob/master/contributing.md) first.


## License

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)
---
<p align="center">
	This list is a copy of <a href="hobbyquaker/awesome-mqtt">hobbyquaker/awesome-mqtt</a> with ranks
</p>
