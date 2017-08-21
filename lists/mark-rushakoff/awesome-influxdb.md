---
layout: default
title: Awesome Rank for mark-rushakoff/awesome-influxdb
---

<p align="center">
	This list is a copy of <a href="https://github.com/mark-rushakoff/awesome-influxdb">mark-rushakoff/awesome-influxdb</a> with ranks
</p>
---
# awesome-influxdb [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg) ★63835](https://github.com/sindresorhus/awesome)

A curated list of awesome projects, libraries, tools, etc. related to [InfluxDB](https://www.influxdata.com/).
This list focuses on libraries, tools, etc. supporting InfluxDB version 1.0 and up.

Want to make this list better?
Take a look at our page on [contributing](https://github.com/mark-rushakoff/awesome-influxdb/blob/master/CONTRIBUTING.md) and then open a pull request!

## Reference material

If you know of any particularly useful blog posts, talks, slides, etc. that belong in this list, please open a pull request!

* [Official documentation](https://docs.influxdata.com/influxdb/latest/)

## Client libraries

### Official

* [C# ★52](https://github.com/influxdata/influxdb-csharp) - A .NET library for efficiently sending points to InfluxDB
* [Go](https://github.com/influxdata/influxdb/tree/master/client) - Go client for InfluxDB, contained as package within main InfluxDB repo
* [Java ★356](https://github.com/influxdata/influxdb-java) - Java client for InfluxDB
* [PHP ★142](https://github.com/influxdata/influxdb-php) - PHP client for InfluxDB
* [Python ★613](https://github.com/influxdata/influxdb-python) - Python client for InfluxDB
* [Rails ★82](https://github.com/influxdata/influxdb-rails) - Ruby on Rails bindings to automatically write metrics into InfluxDB
* [Ruby ★248](https://github.com/influxdata/influxdb-ruby) - Ruby client for InfluxDB

### Unofficial

* [capacitor ★64 ⏳1Y](https://github.com/olauzon/capacitor) - A Clojure client for InfluxDB
* [cl-influxdb ★12](https://github.com/mmaul/cl-influxdb) - Common Lisp interface to the Time Series Database InfluxDB
* [erflux ★17](https://github.com/gossiperl/erflux) - InfluxDB client for Erlang
* [fluxter ★52](https://github.com/lexmag/fluxter) - An InfluxDB writer for Elixir
* [influent ★32 ⏳1Y](https://github.com/gobwas/influent) - InfluxDB Javascript driver
* [influent.rs ★20](https://github.com/gobwas/influent.rs) - InfluxDB Rust driver
* [InfluxDB-Client-LabVIEW ★1 ⏳1Y](https://github.com/johanvandenbroek/InfluxDB-Client-LabVIEW) - LabVIEW client for InfluxDB
* [influxdb-haskell ★34](https://github.com/maoe/influxdb-haskell) - Haskell client library for InfluxDB
* [InfluxDB.NET ★92](https://github.com/ziyasal/InfluxDB.Net) - .NET client for InfluxDB
* [InfluxDB PHP SDK ★74](https://github.com/corley/influxdb-php-sdk) - UDP/IP or HTTP adapters for read and write data
* [influxdbr ★34](https://github.com/dleutnant/influxdbr) - R library for InfluxDB
* [instream ★83](https://github.com/mneudert/instream) - InfluxDB driver for Elixir
* [node-influx ★434](https://github.com/node-influx/node-influx) - InfluxDB Node.js Client
* [node-influx-udp ★13](https://github.com/mediocre/node-influx-udp) - Write to InfluxDB using its UDP interface
* [scala-influxdb-client ★61](https://github.com/paulgoldbaum/scala-influxdb-client) - Asynchronous InfluxDB client for Scala

## Collecting data into InfluxDB

### Projects

#### Dedicated

Tools whose primary or sole purpose is to feed data into InfluxDB.

* [agento ★13](https://github.com/abrander/agento) - Client/server collecting near realtime metrics from Linux hosts
* [aggregateD ★16](https://github.com/ccpgames/aggregateD) - A [dogstatsD](http://docs.datadoghq.com/guides/dogstatsd/) inspired metrics and event aggregation daemon for InfluxDB
* [Charmander ★58 ⏳1Y](https://github.com/att-innovate/charmander) - Charmander is a lab environment for measuring and analyzing resource-scheduling algorithms
* [gopherwx ★4](https://github.com/chrissnell/gopherwx) - a service that pulls live weather data from a Davis Instruments Vantage Pro2 station and stores it in InfluxDB
* [Influx-Capacitor ★36](https://github.com/poxet/Influx-Capacitor) - Influx-Capacitor collects metrics from windows machines using Performance Counters. Data is sent to influxDB to be viewable by grafana
* [Influxdb-Powershell ★2](https://github.com/vsavornin/Influxdb-Powershell) - Powershell script to send Windows Performance counters to an InfluxDB Server
* [influxdb-logger](https://github.com/codersaur/SmartThings/tree/master/smartapps/influxdb-logger) - SmartApp to log [SmartThings](https://www.smartthings.com/) device attributes to an InfluxDB database
* [influxdb-sqlserver ★30](https://github.com/zensqlmonitor/influxdb-sqlserver) - Collect Microsoft SQL Server metrics for reporting to InfluxDB and visualize them with Grafana
* [k6 ★2949](https://github.com/loadimpact/k6) - A modern load testing tool, using Go and JavaScript
* [marathon-event-metrics ★1](https://github.com/Wikia/marathon-event-metrics) - a tool for reporting [Marathon](https://mesosphere.github.io/marathon/) events to InfluxDB
* [mesos-influxdb-collector ★15 ⏳1Y](https://github.com/kpacha/mesos-influxdb-collector) - Lightweight [mesos](https://mesos.apache.org/) stats collector for InfluxDB
* [mqforward ★37](https://github.com/shirou/mqforward) - [MQTT](http://mqtt.org/) to influxdb forwarder
* [ntp_checker ★3](https://github.com/fss1/ntp_checker) - compares internal NTP sources and warns if the offset between servers exceeds a definable (fraction of) seconds
* [sysinfo_influxdb ★89 ⏳2Y](https://github.com/novaquark/sysinfo_influxdb) - Collect and send system (linux) info to InfluxDB
* [Telegraf ★3408](https://github.com/influxdata/telegraf) - (Official) plugin-driven server agent for reporting metrics into InfluxDB
* [tesla-streamer](https://github.com/timdorr/tesla-trip/blob/master/lib/tesla_stream_reader.rb) - Streams data from Tesla Model S to InfluxDB ([rake task](https://github.com/timdorr/tesla-trip/blob/master/lib/tasks/tesla.rake#L12-L16))
* [traffic_stats](https://trafficcontrol.apache.org/docs/latest/overview/traffic_stats.html) - Acquires and stores statistics about CDNs controlled by [Apache Traffic Control](https://trafficcontrol.apache.org/)
* [vsphere-influxdb-go ★53](https://github.com/Oxalide/vsphere-influxdb-go) - Collect VMware vSphere, vCenter and ESXi performance metrics and send them to InfluxDB

#### Non-dedicated

Tools that generate data that feed into multiple backends, InfluxDB included.

* [cAdvisor ★6036](https://github.com/google/cadvisor) - Analyzes resource usage and performance characteristics of running containers
* [cernan ★154](https://github.com/postmates/cernan) - A telemetry and logging aggregation server
* [cloudwatch-sender ★52 ⏳1Y](https://github.com/BBC-News/cloudwatch-sender) - Send metrics to InfluxDB/Graphite from [Amazon Cloudwatch](https://aws.amazon.com/cloudwatch/)
* [crankshaftd](https://github.com/fullcontact/crankshaftd) - Simple Go agent to ingest streaming data from [Turbine ★555](https://github.com/Netflix/Turbine) via SSE and push it into StatsD as a gauge or to InfluxDB
* [gatling ★3138](https://github.com/gatling/gatling) - Async Scala-Akka-Netty based Stress Tool
* [Glances ★7808](https://github.com/nicolargo/glances) - Glances an Eye on your system
* [Graphios ★261](https://github.com/shawn-sterling/graphios) - A program to send nagios perf data to graphite (carbon) / statsd / librato / influxDB
* [heapster ★1356](https://github.com/kubernetes/heapster) - Monitor container resource usage of a [Kubernetes](https://kubernetes.io/) cluster
* [heka ★3273](https://github.com/mozilla-services/heka) - General purpose data collection and processing tool
* [internet_data_usage ★1 ⏳1Y](https://github.com/precurse/internet_data_usage) - Python based application to pull data plan usage for different carriers such as Telus and Koodo
* [jmxtrans ★1210](https://github.com/jmxtrans/jmxtrans) - Effectively the missing connector between speaking to a JVM via JMX on one end and whatever logging / monitoring / graphing package that you can dream up on the other end.
* [logary ★292](https://github.com/logary/logary) - High performance, multi-target logging, metric and health-check library for mono and .Net
* [metrics.sh ★46](https://github.com/pstadler/metrics.sh) - Collect and forward metrics using portable shell scripts
* [OpenHAB](http://www.openhab.org/) - a universal integration platform for all things around home automation
* [Riemann ★3347](https://github.com/riemann/riemann) - A network event stream processing system, in Clojure
* [statsd-jvm-profiler ★239 ⏳1Y](https://github.com/etsy/statsd-jvm-profiler) - Simple JVM Profiler Using StatsD
* [statsite ★1546](https://github.com/statsite/statsite) - C implementation of statsd

### Libraries

Libraries to collect data and feed into InfluxDB.

* [crow-metrics ★14](https://github.com/robey/crow-metrics) - small metrics collector for node servers
* [django-influxdb-metrics ★48](https://github.com/bitlabstudio/django-influxdb-metrics) - A reusable Django app that sends metrics about your project to InfluxDB
* [go-runtime-metrics ★140](https://github.com/tevjef/go-runtime-metrics) - Collect golang runtime Metrics, outputting to InfluxDB or through Telegraf
* [lua-resty-influx ★4](https://github.com/p0pr0ck5/lua-resty-influx) - [OpenResty](https://openresty.org/en/) client for InfluxDB
* [metrics ★205](https://github.com/beberlei/metrics) - (PHP) Simple library that abstracts different metrics collectors. "I find this necessary to have a consistent and simple metrics (functional) API that doesn't cause vendor lock-in"
* [pyVsphereInflux ★3 ⏳1Y](https://github.com/fennm/pyVsphereInflux) - A library and supporting script for pulling data from [vSphere](http://www.vmware.com/products/vsphere.html) and inserting it into InfluxDB
* [telemetry ★76 ⏳2Y](https://github.com/arussellsaw/telemetry) - metric reporting for Go applications

#### Hooks

Hooks for other logging libraries to output to InfluxDB.

* [go-metrics-influxdb](https://github.com/vrischmann/go-metrics-influxdb) - A reporter for the [go-metrics library ★1648](https://github.com/rcrowley/go-metrics) which will post the metrics to InfluxDB
* [logrus_influxdb](https://github.com/Abramovic/logrus_influxdb) - InfluxDB Hook for [Logrus ★5322](https://github.com/Sirupsen/logrus)

### Plugins

Plugins to allow other standalone tools to send their data into InfluxDB.

* [embulk-output-influxdb](https://github.com/joker1007/embulk-output-influxdb) - InfluxDB output plugin for [Embulk ★925](https://github.com/embulk/embulk)
* [exometer_influxdb](https://github.com/travelping/exometer_influxdb) - [Exometer ★401](https://github.com/Feuerlabs/exometer) reporter for InfluxDB
* [fluent-plugin-influxdb ★77](https://github.com/fangli/fluent-plugin-influxdb) - A buffered output plugin for [fluentd](http://www.fluentd.org/) and InfluxDB
* [influx-nagios-plugin ★28 ⏳1Y](https://github.com/shaharke/influx-nagios-plugin) - [Nagios](https://www.nagios.org/) plugin for querying monitoring stats from InfluxDB
* [jenkinsci/influxdb-plugin ★7](https://github.com/jenkinsci/influxdb-plugin) - [Jenkins](https://jenkins.io/index.html) plugin to send build metrics into InfluxDB
* [kafka-influxdb ★111](https://github.com/mre/kafka-influxdb) - A [Kafka](https://kafka.apache.org/) consumer for InfluxDB written in Python
* [logstash-output-influxdb ★27](https://github.com/logstash-plugins/logstash-output-influxdb) - Community-maintained [Logstash](https://www.elastic.co/products/logstash) plugin to output metrics to InfluxDB
* [metrics-influxdb ★186](https://github.com/davidB/metrics-influxdb) - A reporter for [dropwizard](http://www.dropwizard.io/0.9.1/docs/) metrics which announces measurements to an InfluxDB server
* [mod-influxdb ★13](https://github.com/savoirfairelinux/mod-influxdb) - [Shinken](http://www.shinken-monitoring.org/) module for exporting data to InfluxDB
* [sensu-plugins-influxdb ★9](https://github.com/sensu-plugins/sensu-plugins-influxdb) - [Sensu](https://sensuapp.org/) InfluxDB Plugins
* [snap-plugin-publisher-influxdb ★8](https://github.com/intelsdi-x/snap-plugin-publisher-influxdb) - Publishes [snap](http://snap-telemetry.io/) metrics to InfluxDB
* [statsd-influxdb-backend ★152](https://github.com/bernd/statsd-influxdb-backend) - A naive InfluxDB backend for StatsD

### Import tools

Tools to import a fixed set of data into InfluxDB.

* [nmon2influxdb ★31](https://github.com/adejoux/nmon2influxdb) - Import [nmon](http://nmon.sourceforge.net/pmwiki.php) file into InfluxDB

## Consuming data from InfluxDB

### Dashboards and visualization

* [Chronograf ★349](https://github.com/influxdata/chronograf) - Official InfluxDB data visualization tool
* [facette ★911](https://github.com/facette/facette) - Time series data visualization and graphing software
* [FluxDash ★18 ⏳1Y](https://github.com/vrecan/FluxDash) - Terminal based InfluxDB dashboard
* [grafana ★17276](https://github.com/grafana/grafana) - Gorgeous metric viz, dashboards & editors for Graphite, InfluxDB & OpenTSDB
* [InfluxGraph ★44](https://github.com/InfluxGraph/influxgraph) - Graphite InfluxDB storage finder for Graphite-API
* [ostent ★145](https://github.com/ostrost/ostent) - collects and displays system metrics and optionally relays to Graphite and/or InfluxDB

### Other tools

* [hubot-influxdb-alerts ★11 ⏳1Y](https://github.com/amwelch/hubot-influxdb-alerts) - Create and manage alerts in your chatroom using [hubot](https://hubot.github.com/) and influxdb
* [influx-alert ★21](https://github.com/joshrendek/influx-alert) - A tool to query InfluxDB and send alerts based on a YAML config
* [influxdb_google_sheets ★6](https://github.com/HormyAJP/influxdb_google_sheets) - Google Sheets script for fetching and formatting InfluxDB data
* [Morgoth ★183](https://github.com/nathanielc/morgoth) - Metric anomaly detection

## Provisioning InfluxDB

Tools, libraries, etc. to help you get InfluxDB running without installing it by hand.

* [chef-influxdb ★48](https://github.com/bdangit/chef-influxdb) - Chef cookbook for InfluxDB
* [golja-influxdb ★17](https://github.com/dgolja/golja-influxdb) - Puppet module for InfluxDB
* [influxdb-formula ★6](https://github.com/saltstack-formulas/influxdb-formula) - Installs and configures the InfluxDB timeseries database
* [influxdb-release ★2 ⏳1Y](https://github.com/pivotal-cf-experimental/influxdb-release) - Experimental BOSH release for InfluxDB
* [puppet-telegraf](https://forge.puppet.com/datacentred/telegraf/readme) - Puppet module for Telegraf
* [rossmcdonald/influxdb ★14](https://github.com/rossmcdonald/influxdb) - Ansible role for installing, configuring, and maintaining InfluxDB
* [tutum-docker-influxdb ★236](https://github.com/tutumcloud/influxdb) - Docker image to run an out-of-the-box InfluxDB server

## Queries

* [dbal-influxdb ★9 ⏳2Y](https://github.com/corley/dbal-influxdb) - Doctrine DBAL for InfluxDB
* [Influxdb::Arel ★8 ⏳1Y](https://github.com/undr/influxdb-arel) - Influxdb::Arel is a SQL AST manager for InfluxDB dialect. It simplifies the generation of complex SQL queries
* [influxer ★65](https://github.com/palkan/influxer) - InfluxDB ActiveRecord-style

## Miscellaneous

Projects that don't seem to fit in any other category.

* [influx-protector ★8](https://github.com/ve-interactive/influx-protector) - proxy to prevent dangerous queries getting to influxdb

## Other awesome lists

### Awesome lists that include links to InfluxDB

* [awesome-bigdata ★4998](https://github.com/onurakpolat/awesome-bigdata)
* [awesome-dashboard ★436](https://github.com/obazoud/awesome-dashboard)
* [awesome-data-engineering ★1050](https://github.com/igorbarinov/awesome-data-engineering)
* [awesome-db ★467](https://github.com/numetriclabz/awesome-db)
* [awesome-go ★22815](https://github.com/avelino/awesome-go)
* [awesome-sysadmin ★15733](https://github.com/kahun/awesome-sysadmin)

### Lists of awesome lists that include awesome-influxdb

* [awesome ★63835](https://github.com/sindresorhus/awesome)
* [lists ★4428](https://github.com/jnv/lists)

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the authors and contributors have waived all copyright and related or neighboring rights to awesome-influxdb.
---
<p align="center">
	This list is a copy of <a href="https://github.com/mark-rushakoff/awesome-influxdb">mark-rushakoff/awesome-influxdb</a> with ranks
</p>
