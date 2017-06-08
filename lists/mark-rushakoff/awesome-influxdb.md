<h1 align="center">
Ranked awesome lists, all in one place
</h1>
<p align="center">
	This list is a copy of <a href="mark-rushakoff/awesome-influxdb">mark-rushakoff/awesome-influxdb</a> with ranks
</p>
---
# awesome-influxdb [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg) ★59088](sindresorhus/awesome)

A curated list of awesome projects, libraries, tools, etc. related to [InfluxDB](https://www.influxdata.com/).
This list focuses on libraries, tools, etc. supporting InfluxDB version 1.0 and up.

Want to make this list better?
Take a look at our page on [contributing](https://github.com/mark-rushakoff/awesome-influxdb/blob/master/CONTRIBUTING.md) and then open a pull request!

## Reference material

If you know of any particularly useful blog posts, talks, slides, etc. that belong in this list, please open a pull request!

* [Official documentation](https://docs.influxdata.com/influxdb/latest/)

## Client libraries

### Official

* [C# ★45](influxdata/influxdb-csharp) - A .NET library for efficiently sending points to InfluxDB
* [Go](https://github.com/influxdata/influxdb/tree/master/client) - Go client for InfluxDB, contained as package within main InfluxDB repo
* [Java ★309](influxdata/influxdb-java) - Java client for InfluxDB
* [PHP ★131](influxdata/influxdb-php) - PHP client for InfluxDB
* [Python ★561](influxdata/influxdb-python) - Python client for InfluxDB
* [Rails ★77](influxdata/influxdb-rails) - Ruby on Rails bindings to automatically write metrics into InfluxDB
* [Ruby ★232](influxdata/influxdb-ruby) - Ruby client for InfluxDB

### Unofficial

* [capacitor ★64 ⏳1Y](olauzon/capacitor) - A Clojure client for InfluxDB
* [cl-influxdb ★12](mmaul/cl-influxdb) - Common Lisp interface to the Time Series Database InfluxDB
* [erflux ★16](gossiperl/erflux) - InfluxDB client for Erlang
* [fluxter ★47](lexmag/fluxter) - An InfluxDB writer for Elixir
* [influent ★31 ⏳1Y](gobwas/influent) - InfluxDB Javascript driver
* [influent.rs ★19](gobwas/influent.rs) - InfluxDB Rust driver
* [InfluxDB-Client-LabVIEW ★1 ⏳1Y](johanvandenbroek/InfluxDB-Client-LabVIEW) - LabVIEW client for InfluxDB
* [influxdb-haskell ★34](maoe/influxdb-haskell) - Haskell client library for InfluxDB
* [InfluxDB.NET ★83](ziyasal/InfluxDB.Net) - .NET client for InfluxDB
* [InfluxDB PHP SDK ★71](corley/influxdb-php-sdk) - UDP/IP or HTTP adapters for read and write data
* [influxdbr ★29](dleutnant/influxdbr) - R library for InfluxDB
* [instream ★76](mneudert/instream) - InfluxDB driver for Elixir
* [node-influx ★403](node-influx/node-influx) - InfluxDB Node.js Client
* [node-influx-udp ★13](mediocre/node-influx-udp) - Write to InfluxDB using its UDP interface
* [scala-influxdb-client ★58](paulgoldbaum/scala-influxdb-client) - Asynchronous InfluxDB client for Scala

## Collecting data into InfluxDB

### Projects

#### Dedicated

Tools whose primary or sole purpose is to feed data into InfluxDB.

* [agento ★14](abrander/agento) - Client/server collecting near realtime metrics from Linux hosts
* [aggregateD ★16](ccpgames/aggregateD) - A [dogstatsD](http://docs.datadoghq.com/guides/dogstatsd/) inspired metrics and event aggregation daemon for InfluxDB
* [Charmander ★57 ⏳1Y](att-innovate/charmander) - Charmander is a lab environment for measuring and analyzing resource-scheduling algorithms
* [gopherwx ★3](chrissnell/gopherwx) - a service that pulls live weather data from a Davis Instruments Vantage Pro2 station and stores it in InfluxDB
* [Influx-Capacitor ★35](poxet/Influx-Capacitor) - Influx-Capacitor collects metrics from windows machines using Performance Counters. Data is sent to influxDB to be viewable by grafana
* [Influxdb-Powershell ★1](vsavornin/Influxdb-Powershell) - Powershell script to send Windows Performance counters to an InfluxDB Server
* [influxdb-logger](https://github.com/codersaur/SmartThings/tree/master/smartapps/influxdb-logger) - SmartApp to log [SmartThings](https://www.smartthings.com/) device attributes to an InfluxDB database
* [influxdb-sqlserver ★26](zensqlmonitor/influxdb-sqlserver) - Collect Microsoft SQL Server metrics for reporting to InfluxDB and visualize them with Grafana
* [k6 ★2685](loadimpact/k6) - A modern load testing tool, using Go and JavaScript
* [marathon-event-metrics ★1](Wikia/marathon-event-metrics) - a tool for reporting [Marathon](https://mesosphere.github.io/marathon/) events to InfluxDB
* [mesos-influxdb-collector ★13 ⏳1Y](kpacha/mesos-influxdb-collector) - Lightweight [mesos](https://mesos.apache.org/) stats collector for InfluxDB
* [mqforward ★32](shirou/mqforward) - [MQTT](http://mqtt.org/) to influxdb forwarder
* [ntp_checker ★3 ⏳1Y](fss1/ntp_checker) - compares internal NTP sources and warns if the offset between servers exceeds a definable (fraction of) seconds
* [sysinfo_influxdb ★88 ⏳1Y](novaquark/sysinfo_influxdb) - Collect and send system (linux) info to InfluxDB
* [Telegraf ★2990](influxdata/telegraf) - (Official) plugin-driven server agent for reporting metrics into InfluxDB
* [tesla-streamer](https://github.com/timdorr/tesla-trip/blob/master/lib/tesla_stream_reader.rb) - Streams data from Tesla Model S to InfluxDB ([rake task](https://github.com/timdorr/tesla-trip/blob/master/lib/tasks/tesla.rake#L12-L16))
* [traffic_stats](https://trafficcontrol.apache.org/docs/latest/overview/traffic_stats.html) - Acquires and stores statistics about CDNs controlled by [Apache Traffic Control](https://trafficcontrol.apache.org/)
* [vsphere-influxdb-go ★37](Oxalide/vsphere-influxdb-go) - Collect VMware vSphere, vCenter and ESXi performance metrics and send them to InfluxDB

#### Non-dedicated

Tools that generate data that feed into multiple backends, InfluxDB included.

* [cAdvisor ★5689](google/cadvisor) - Analyzes resource usage and performance characteristics of running containers
* [cernan ★133](postmates/cernan) - A telemetry and logging aggregation server
* [cloudwatch-sender ★46](BBC-News/cloudwatch-sender) - Send metrics to InfluxDB/Graphite from [Amazon Cloudwatch](https://aws.amazon.com/cloudwatch/)
* [crankshaftd](https://github.com/fullcontact/crankshaftd) - Simple Go agent to ingest streaming data from [Turbine ★529 ⏳1Y](Netflix/Turbine) via SSE and push it into StatsD as a gauge or to InfluxDB
* [gatling ★3001](gatling/gatling) - Async Scala-Akka-Netty based Stress Tool
* [Glances ★7387](nicolargo/glances) - Glances an Eye on your system
* [Graphios ★255](shawn-sterling/graphios) - A program to send nagios perf data to graphite (carbon) / statsd / librato / influxDB
* [heapster ★1234](kubernetes/heapster) - Monitor container resource usage of a [Kubernetes](https://kubernetes.io/) cluster
* [heka ★3262](mozilla-services/heka) - General purpose data collection and processing tool
* [internet_data_usage ★1 ⏳1Y](precurse/internet_data_usage) - Python based application to pull data plan usage for different carriers such as Telus and Koodo
* [jmxtrans ★1167](jmxtrans/jmxtrans) - Effectively the missing connector between speaking to a JVM via JMX on one end and whatever logging / monitoring / graphing package that you can dream up on the other end.
* [logary ★268](logary/logary) - High performance, multi-target logging, metric and health-check library for mono and .Net
* [metrics.sh ★41](pstadler/metrics.sh) - Collect and forward metrics using portable shell scripts
* [OpenHAB](http://www.openhab.org/) - a universal integration platform for all things around home automation
* [Riemann ★3287](riemann/riemann) - A network event stream processing system, in Clojure
* [statsd-jvm-profiler ★235](etsy/statsd-jvm-profiler) - Simple JVM Profiler Using StatsD
* [statsite ★1513](statsite/statsite) - C implementation of statsd

### Libraries

Libraries to collect data and feed into InfluxDB.

* [crow-metrics ★13](robey/crow-metrics) - small metrics collector for node servers
* [django-influxdb-metrics ★45](bitlabstudio/django-influxdb-metrics) - A reusable Django app that sends metrics about your project to InfluxDB
* [go-runtime-metrics ★133](tevjef/go-runtime-metrics) - Collect golang runtime Metrics, outputting to InfluxDB or through Telegraf
* [lua-resty-influx ★4](p0pr0ck5/lua-resty-influx) - [OpenResty](https://openresty.org/en/) client for InfluxDB
* [metrics ★192](beberlei/metrics) - (PHP) Simple library that abstracts different metrics collectors. "I find this necessary to have a consistent and simple metrics (functional) API that doesn't cause vendor lock-in"
* [pyVsphereInflux ★3 ⏳1Y](fennm/pyVsphereInflux) - A library and supporting script for pulling data from [vSphere](http://www.vmware.com/products/vsphere.html) and inserting it into InfluxDB
* [telemetry ★76 ⏳2Y](arussellsaw/telemetry) - metric reporting for Go applications

#### Hooks

Hooks for other logging libraries to output to InfluxDB.

* [go-metrics-influxdb](https://github.com/vrischmann/go-metrics-influxdb) - A reporter for the [go-metrics library ★1582](rcrowley/go-metrics) which will post the metrics to InfluxDB
* [logrus_influxdb](https://github.com/Abramovic/logrus_influxdb) - InfluxDB Hook for [Logrus ★4819](Sirupsen/logrus)

### Plugins

Plugins to allow other standalone tools to send their data into InfluxDB.

* [embulk-output-influxdb](https://github.com/joker1007/embulk-output-influxdb) - InfluxDB output plugin for [Embulk ★885](embulk/embulk)
* [exometer_influxdb](https://github.com/travelping/exometer_influxdb) - [Exometer ★394](Feuerlabs/exometer) reporter for InfluxDB
* [fluent-plugin-influxdb ★76](fangli/fluent-plugin-influxdb) - A buffered output plugin for [fluentd](http://www.fluentd.org/) and InfluxDB
* [influx-nagios-plugin ★27 ⏳1Y](shaharke/influx-nagios-plugin) - [Nagios](https://www.nagios.org/) plugin for querying monitoring stats from InfluxDB
* [jenkinsci/influxdb-plugin ★6](jenkinsci/influxdb-plugin) - [Jenkins](https://jenkins.io/index.html) plugin to send build metrics into InfluxDB
* [kafka-influxdb ★104](mre/kafka-influxdb) - A [Kafka](https://kafka.apache.org/) consumer for InfluxDB written in Python
* [logstash-output-influxdb ★26](logstash-plugins/logstash-output-influxdb) - Community-maintained [Logstash](https://www.elastic.co/products/logstash) plugin to output metrics to InfluxDB
* [metrics-influxdb ★179](davidB/metrics-influxdb) - A reporter for [dropwizard](http://www.dropwizard.io/0.9.1/docs/) metrics which announces measurements to an InfluxDB server
* [mod-influxdb ★13](savoirfairelinux/mod-influxdb) - [Shinken](http://www.shinken-monitoring.org/) module for exporting data to InfluxDB
* [sensu-plugins-influxdb ★9](sensu-plugins/sensu-plugins-influxdb) - [Sensu](https://sensuapp.org/) InfluxDB Plugins
* [snap-plugin-publisher-influxdb ★8](intelsdi-x/snap-plugin-publisher-influxdb) - Publishes [snap](http://snap-telemetry.io/) metrics to InfluxDB
* [statsd-influxdb-backend ★151](bernd/statsd-influxdb-backend) - A naive InfluxDB backend for StatsD

### Import tools

Tools to import a fixed set of data into InfluxDB.

* [nmon2influxdb ★28](adejoux/nmon2influxdb) - Import [nmon](http://nmon.sourceforge.net/pmwiki.php) file into InfluxDB

## Consuming data from InfluxDB

### Dashboards and visualization

* [Chronograf ★275](influxdata/chronograf) - Official InfluxDB data visualization tool
* [facette ★897](facette/facette) - Time series data visualization and graphing software
* [FluxDash ★16 ⏳1Y](vrecan/FluxDash) - Terminal based InfluxDB dashboard
* [grafana ★16130](grafana/grafana) - Gorgeous metric viz, dashboards & editors for Graphite, InfluxDB & OpenTSDB
* [InfluxGraph ★32](InfluxGraph/influxgraph) - Graphite InfluxDB storage finder for Graphite-API
* [ostent ★143](ostrost/ostent) - collects and displays system metrics and optionally relays to Graphite and/or InfluxDB

### Other tools

* [hubot-influxdb-alerts ★10 ⏳1Y](amwelch/hubot-influxdb-alerts) - Create and manage alerts in your chatroom using [hubot](https://hubot.github.com/) and influxdb
* [influx-alert ★20](joshrendek/influx-alert) - A tool to query InfluxDB and send alerts based on a YAML config
* [influxdb_google_sheets ★4](HormyAJP/influxdb_google_sheets) - Google Sheets script for fetching and formatting InfluxDB data
* [Morgoth ★167](nathanielc/morgoth) - Metric anomaly detection

## Provisioning InfluxDB

Tools, libraries, etc. to help you get InfluxDB running without installing it by hand.

* [chef-influxdb ★50](bdangit/chef-influxdb) - Chef cookbook for InfluxDB
* [golja-influxdb ★15](dgolja/golja-influxdb) - Puppet module for InfluxDB
* [influxdb-formula ★6](saltstack-formulas/influxdb-formula) - Installs and configures the InfluxDB timeseries database
* [influxdb-release ★2](pivotal-cf-experimental/influxdb-release) - Experimental BOSH release for InfluxDB
* [puppet-telegraf](https://forge.puppet.com/datacentred/telegraf/readme) - Puppet module for Telegraf
* [rossmcdonald/influxdb ★13](rossmcdonald/influxdb) - Ansible role for installing, configuring, and maintaining InfluxDB
* [tutum-docker-influxdb ★238](tutumcloud/influxdb) - Docker image to run an out-of-the-box InfluxDB server

## Queries

* [dbal-influxdb ★9 ⏳1Y](corley/dbal-influxdb) - Doctrine DBAL for InfluxDB
* [Influxdb::Arel ★8](undr/influxdb-arel) - Influxdb::Arel is a SQL AST manager for InfluxDB dialect. It simplifies the generation of complex SQL queries
* [influxer ★57](palkan/influxer) - InfluxDB ActiveRecord-style

## Miscellaneous

Projects that don't seem to fit in any other category.

* [influx-protector ★5](ve-interactive/influx-protector) - proxy to prevent dangerous queries getting to influxdb

## Other awesome lists

### Awesome lists that include links to InfluxDB

* [awesome-bigdata ★4689](onurakpolat/awesome-bigdata)
* [awesome-dashboard ★354](obazoud/awesome-dashboard)
* [awesome-data-engineering ★956](igorbarinov/awesome-data-engineering)
* [awesome-db ★407](numetriclabz/awesome-db)
* [awesome-go ★20918](avelino/awesome-go)
* [awesome-sysadmin ★14903](kahun/awesome-sysadmin)

### Lists of awesome lists that include awesome-influxdb

* [awesome ★59088](sindresorhus/awesome)
* [lists ★4263](jnv/lists)

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the authors and contributors have waived all copyright and related or neighboring rights to awesome-influxdb.
---
<p align="center">
	This list is a copy of <a href="mark-rushakoff/awesome-influxdb">mark-rushakoff/awesome-influxdb</a> with ranks
</p>
<script>
  (function(i,s,o,g,r,a,m){i['GoogleAnalyticsObject']=r;i[r]=i[r]||function(){
  (i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),
  m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)
  })(window,document,'script','https://www.google-analytics.com/analytics.js','ga');

  ga('create', 'UA-100705027-1', 'auto');
  ga('send', 'pageview');

</script>
