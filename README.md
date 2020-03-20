# Load testing toolkit

Collection of **open source** tools for debugging, benchmarking, load and stress testing your code or services.

> In alphabetical order.

## Contents

* [Debugging & API testing](#debugging--api-testing)
* [Benchmarking & load testing](#benchmarking--load-testing)
* [Stress testing](#stress-testing)
* [DoS/DDoS penetration testing](#dosddos-penetration-testing)

## Debugging & API testing

* [__bat__](https://github.com/astaxie/bat) - A [curl](https://github.com/curl/curl)-like tool for humans, inspired by [httpie](https://github.com/jakubroztocil/httpie), written in `Go`.
* [__curl__](https://github.com/curl/curl) - A command line tool and library for transferring data with URL syntax. `C`
* [__curlie__](https://github.com/rs/curlie) - The power of [curl](https://github.com/curl/curl), the ease of use of [httpie](https://github.com/jakubroztocil/httpie). `Go`
* [__httpcat__](https://github.com/jakubroztocil/httpcat) - A simple utility for constructing raw HTTP requests on the command line. `Python`
* [__httpie__](https://github.com/jakubroztocil/httpie) - Modern command line HTTP client, user-friendly [curl](https://github.com/curl/curl) alternative with intuitive UI, JSON support, syntax highlighting, wget-like downloads, extensions, etc. `Python`
* [__httping__](https://github.com/flok99/httping) - A ping-like utility for HTTP requests.
* [__httpstat__](https://github.com/reorx/httpstat) - [curl](https://github.com/curl/curl) statistics visualization in a way of beauty and clarity. `Python`

## Benchmarking & load testing

### http/s

* [__apachebench (ab)__](https://github.com/CloudFundoo/ApacheBench-ab) - Standalone [apachebench (ab)](http://httpd.apache.org/docs/current/programs/ab.html), Apache HTTP server benchmarking tool. `C`
* [__autocannon__](https://github.com/mcollina/autocannon) - Fast HTTP/1.1 benchmarking tool written in `Node.js`, greatly inspired by [wrk](https://github.com/wg/wrk) and [wrk2](https://github.com/giltene/wrk2), with support for HTTP pipelining and HTTPS.
* [__beeswithmachineguns__](https://github.com/newsapps/beeswithmachineguns) - An utility for arming (creating) many bees (micro EC2 instances) to attack (load test) targets (web applications). `Python`
* [__bender__](https://github.com/pinterest/bender) - An easy-to-use library for creating load testing applications. `Go`
* [__bfg__](https://github.com/yandex-load/bfg) - A modular tool and framework for load generation with HTTP/2 support. `Python`
* [__bombardier__](https://github.com/codesenberg/bombardier) - Fast cross-platform HTTP benchmarking tool written in `Go`.
* [__boom__](https://github.com/tarekziade/boom) - A replacement for [ab](https://github.com/CloudFundoo/ApacheBench-ab), written in `Python`.
* [__break__](https://github.com/tarekziade/break) - Like [boom](https://github.com/tarekziade/boom), but based on [molotov](https://github.com/loads/molotov). `Python`
* [__carrot__](https://github.com/gophercarrot/carrot) - Distributed WebSocket and HTTP load-testing framework in `Go`.
* [__cassowary__](https://github.com/rogerwelin/cassowary) - Modern cross-platform HTTP load-testing tool written in `Go`.
* [__chaperon__](https://github.com/polleverywhere/chaperon) - HTTP service performance & load testing framework. `Elixir`
* [__drill__](https://github.com/fcsonline/drill) - A HTTP load testing application, written in `Rust`, inspired by Ansible syntax.
* [__fortio__](https://github.com/fortio/fortio) - Load testing library, command line tool, advanced echo server and web UI in `Go`.
* [__freeloader__](https://github.com/rprieto/freeloader) - Super easy load testing framework, with load scenarios in `JavaScript`.
* [__go-wrk__](https://github.com/adjust/go-wrk) - A small heavy duty HTTP/S benchmark tool, similar to [wrk](https://github.com/wg/wrk), but written in `Go`.
* [__gobench__](https://github.com/cmpxchg16/gobench) - HTTP/S load testing and benchmarking tool. `Go`
* [__gohttpbench__](https://github.com/parkghost/gohttpbench) - An [ab](https://github.com/CloudFundoo/ApacheBench-ab)-like benchmark tool run on multi-core cpu. `Go`
* [__goku__](https://github.com/k-nasa/goku) - HTTP load testing application written in `Rust`.
* [__hargo__](https://github.com/mrichman/hargo) - `Go` library and command line utility that parses HAR files, can convert to [curl](https://github.com/curl/curl) format, and serve as a load test driver.
* [__hey__](https://github.com/rakyll/hey) - HTTP load generator, [ab](https://github.com/CloudFundoo/ApacheBench-ab) replacement. `Go`
* [__httperf__](https://github.com/httperf/httperf) - A tool for measuring web server performance. `C`
* [__httpress__](https://bitbucket.org/yarosla/httpress) - High performance HTTP server stress & benchmark utility, inspired by [weighttp](https://github.com/lighttpd/weighttp). `C`
* [__hurl__](https://github.com/VerizonDigital/hurl) - HTTP server load test and parallel [curl](https://github.com/curl/curl) utilities. `C++`
* [__iago2__](https://github.com/twitter/iago2) - A load generator, built for engineers. `Scala`
* [__kboom__](https://github.com/mhausenblas/kboom) - The Kubernetes scale & soak load tester, equivalent of [boom](https://github.com/tarekziade/boom), written in `Go`.
* [__mgun__](https://github.com/byorty/mgun) - A modern tool for load testing HTTP servers, written in `Go`.
* [__molotov__](https://github.com/loads/molotov) - Simple `Python` 3.5+ tool to write load tests.
* [__oha__](https://github.com/hatoo/oha) - HTTP load generator, inspired by [hey](https://github.com/rakyll/hey) with tui animation. `Rust`
* [__pandora__](https://github.com/yandex/pandora) - A load generator in `Go`, with built-in HTTP/S and HTTP/2 support and load scenarios in `Go`.
* [__phantomas__](https://github.com/macbre/phantomas) - PhantomJS-based web performance metrics collector and monitoring tool. `JavaScript`
* [__ponos__](https://github.com/klarna/ponos) - Simple yet powerful load generator written in `Erlang`.
* [__pronk__](https://github.com/bos/pronk) - A small command line application for load testing web servers. `Haskell`
* [__scouter__](https://github.com/jbarabander/scouter) - `Node.js` bindings for the [vegeta](https://github.com/tsenart/vegeta) load-testing library.
* [__siege__](https://github.com/JoeDog/siege) - A HTTP load tester and benchmarking utility. `C`
* [__slapper__](https://github.com/ikruglov/slapper) - Simple load testing tool with real-time updated histogram of request timings. `Go`
* [__slow_cooker__](https://github.com/BuoyantIO/slow_cooker) - A load tester focused on lifecycle issues and long-running tests. `Go`
* [__sniper__](https://github.com/btfak/sniper) - Powerful and high-performance HTTP load tester, written in `Go`.
* [__thrash__](https://github.com/TylerBrock/thrash) - `Go` HTTP micro benchmarker.
* [__vegeta__](https://github.com/tsenart/vegeta) - HTTP load testing tool and library. `Go`
* [__vex__](https://github.com/vamsiikrishna/vex) - A small `PHP` app that sends some load to a web application.
* [__weighttp__](https://github.com/lighttpd/weighttp) - A lightweight and simple webserver benchmarking tool. `C`
* [__welle__](https://github.com/rylev/welle) - [ab](https://github.com/CloudFundoo/ApacheBench-ab)-like benchmarking  tool written in `Rust`.
* [__wrk__](https://github.com/wg/wrk) - Modern HTTP benchmarking tool. `C`
* [__wrk2__](https://github.com/giltene/wrk2) - A constant throughput, correct latency recording variant of [wrk](https://github.com/wg/wrk). `C`

### non-http/s

* [__bomberman__](https://github.com/c1982/bomberman) - SMTP performance and load testing tool. `Go`
* [__massive-attack__](https://github.com/delprks/massive-attack) - Load testing Thrift, made simple. `Scala`
* [__memtier_benchmark__](https://github.com/RedisLabs/memtier_benchmark) - NoSQL Redis and Memcache traffic generation and benchmarking tool. `C++`
* [__mqperf__](https://github.com/softwaremill/mqperf) - A benchmark of message queues with data replication and at-least-once delivery guarantees. `Scala`
* [__rabbitmq-perf-test__](https://github.com/rabbitmq/rabbitmq-perf-test) - RabbitMQ performance testing tool. `Java`
* [__rpc-perf__](https://github.com/twitter/rpc-perf) - A tool for benchmarking RPC services. `Rust`
* [__sangrenel__](https://github.com/jamiealquiza/sangrenel) - Apache Kafka load testing. `Go`
* [__tcpkali__](https://github.com/satori-com/tcpkali) - Fast multi-core TCP and WebSockets load generator. `C`

### multi-protocol

* [__artillery__](https://github.com/artilleryio/artillery) - A modern load and functional testing toolkit written in `Node.js`, with test scenario scripting in `Javascript`.
* [__gatling__](https://github.com/gatling/gatling) - A load and performance testing framework based on `Scala`, Akka and Netty.
* [__grinder__](https://github.com/cossme/grinder) - A distributed load testing framework written in `Java`, with test scenario scripting in `Jython` and `Clojure`.
* [__jmeter__](https://github.com/apache/jmeter) - A `Java` tool designed to load test functional behavior and measure performance of a variety of services, with a focus on web applications.
* [__k6__](https://github.com/loadimpact/k6) - A modern load testing tool, using `Go` and `JavaScript`.
* [__locust__](https://github.com/locustio/locust) - Scalable distributed load testing tool written in `Python`.
* [__multi-mechanize__](https://github.com/cgoldberg/multi-mechanize) - Performance and load testing framework written in `Python`.
* [__mzbench__](https://github.com/satori-com/mzbench) - Expressive, scalable load testing tool, with multiple protocols support. `Erlang`
* [__tank__](https://github.com/intuit/Tank) - A cloud native load testing platform. `Java`
* [__tsung__](https://github.com/processone/tsung) - A multi-protocol distributed load testing tool, developed in `Erlang`.
* [__yandex-tank__](https://github.com/yandex/yandex-tank) - An extendable load testing tool which is especially good as a part of an automated load testing suite. `Python`, `C`

## Stress testing

### http/s

* [__hulken__](https://github.com/hellgrenj/hulken) - Stress testing tool for everything speaking HTTP. `JavaScript`
* [__pewpew__](https://github.com/bengadbois/pewpew) - Flexible HTTP command line stress tester for websites and web services. `Go`

### non-http/s

* [__dhammer__](https://github.com/ipchama/dhammer) - DHCP stress tester and benchmark tool. `Go`
* [__dnstress__](https://github.com/safedns/dnstress) - A DNS stress testing tool. `C`
* [__mqtt-stresser__](https://github.com/inovex/mqtt-stresser) - Load testing tool to stress MQTT message broker. `Go`

## DoS/DDoS penetration testing

> For educational and stress testing (as part of development) purposes only.

* [__finshir__](https://github.com/isgasho/finshir) - A coroutines-driven Low & Slow traffic sender, written in `Rust`.
* [__goloris__](https://github.com/valyala/goloris) - Slowloris implementation for nginx DoS written in `Go`.
* [__hulk__](https://github.com/grafov/hulk) - Original HULK web server DoS attack tool ported to `Go` with some additional features.
* [__lor-axe__](https://github.com/ajmwagar/lor-axe) - A multi-threaded, low-bandwidth HTTP DoS tool, written in `Rust`.
* [__slowhttptest__](https://github.com/shekyan/slowhttptest) - A highly configurable application layer DoS attack simulator. `C++`
* [__wreckuests__](https://github.com/JamesJGoodwin/wreckuests) - Yet another one hard-hitting tool to run DDoS attacks with HTTP-flood. `Python`
