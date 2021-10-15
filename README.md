# Load Testing Toolkit

> *“I have enough trouble with useful information, never mind being burdened with what is useless.”*\
> ― Erlend Loe, Naïve. Super

Collection of **open source** tools for debugging, benchmarking, load and stress testing your code or services.

**NOTE:** Unfortunately I've found this original *awesome* collection too late: [__awesome-http-benchmark__](https://github.com/denji/awesome-http-benchmark).\
Feel free to follow and contribute to it instead of this collection, which remains my personal variation and working copy.

> In alphabetical order.

## Contents

* [Debugging & API testing](#debugging--api-testing)
* [Benchmarking & load testing](#benchmarking--load-testing)
* [Stress testing](#stress-testing)
* [DoS/DDoS penetration testing](#dosddos-penetration-testing)

## Debugging & API testing

* [__baloo__](https://github.com/h2non/baloo) - Expressive and versatile end-to-end HTTP API testing made easy in `Go`.
* [__bat__](https://github.com/astaxie/bat) - A [curl](https://github.com/curl/curl)-like tool for humans, inspired by [httpie](https://github.com/httpie/httpie), written in `Go`.
* [__curl__](https://github.com/curl/curl) - A command line tool and library for transferring data with URL syntax. `C`
* [__curlie__](https://github.com/rs/curlie) - The power of [curl](https://github.com/curl/curl), the ease of use of [httpie](https://github.com/httpie/httpie). `Go`
* [__httpcat__](https://github.com/httpie/httpcat) - A simple utility for constructing raw HTTP requests on the command line. `Python`
* [__httpie__](https://github.com/httpie/httpie) - Modern command line HTTP client, user-friendly [curl](https://github.com/curl/curl) alternative with intuitive UI, JSON support, syntax highlighting, wget-like downloads, extensions, etc. `Python`
* [__httpie-go__](https://github.com/nojima/httpie-go) - [httpie](https://github.com/httpie/httpie)-like HTTP client written in `Go`.
* [__httping__](https://github.com/BretFisher/httping-docker) - A ping-like utility for HTTP requests. `C`
* [__httpstat__](https://github.com/reorx/httpstat) - [curl](https://github.com/curl/curl) statistics visualization in a way of beauty and clarity. `Python`
* [__wuzz__](https://github.com/asciimoo/wuzz) - Interactive command line tool for HTTP inspection. `Go`
* [__xh__](https://github.com/ducaale/xh) – Yet another [httpie](https://github.com/httpie/httpie) clone in `Rust`.

## Benchmarking & load testing

### http/s

* [__ab__](https://httpd.apache.org/docs/current/programs/ab.html) - ApacheBench, single-threaded Apache HTTP server benchmarking tool. `C`
* [__ali__](https://github.com/nakabonne/ali) - A load testing tool capable of performing real-time analysis, inspired by [vegeta](https://github.com/tsenart/vegeta), written in `Go`.
* [__apachebench-ab__](https://github.com/CloudFundoo/ApacheBench-ab) - Standalone version of [ab](https://httpd.apache.org/docs/current/programs/ab.html), Apache HTTP server benchmarking tool. `C`
* [__apib__](https://github.com/apigee/apib) - A simple, fast HTTP and API benchmarking tool. `C++`
* [__autocannon__](https://github.com/mcollina/autocannon) - Fast HTTP/1.1 benchmarking tool written in `Node.js`, greatly inspired by [wrk](https://github.com/wg/wrk) and [wrk2](https://github.com/giltene/wrk2), with support for HTTP pipelining and HTTPS.
* [__baton__](https://github.com/americanexpress/baton) - HTTP load testing written in `Go`.
* [__beeswithmachineguns__](https://github.com/newsapps/beeswithmachineguns) - An utility for arming (creating) many bees (micro EC2 instances) to attack (load test) targets (web applications). `Python`
* [__benchttp__](https://github.com/siadat/benchttp) - HTTP server benchmarking tool, implements the most commonly used features of [ab](https://httpd.apache.org/docs/current/programs/ab.html). `Go`
* [__bender__](https://github.com/pinterest/bender) - An easy-to-use library for creating load testing applications. `Go`
* [__bfg__](https://github.com/yandex-load/bfg) - A modular tool and framework for load generation with HTTP/2 support. `Python`
* [__blast__](https://github.com/dave/blast) - A simple, protocol agnostic tool for API load testing and batch jobs. `Go`
* [__bombardier__](https://github.com/codesenberg/bombardier) - Fast cross-platform HTTP benchmarking tool written in `Go`.
* [__boom__](https://github.com/tarekziade/boom) - A replacement for [ab](https://httpd.apache.org/docs/current/programs/ab.html), written in `Python`.
* [__carrot__](https://github.com/gophercarrot/carrot) - Distributed WebSocket and HTTP load testing framework in `Go`.
* [__cassowary__](https://github.com/rogerwelin/cassowary) - Modern cross-platform HTTP load testing tool written in `Go`.
* [__chaperon__](https://github.com/polleverywhere/chaperon) - HTTP service performance & load testing framework. `Elixir`
* [__curl-loader__](http://curl-loader.sourceforge.net/) - A load generating tool written in `C`, simulating HTTP/S, FTP/S and TLS/SSL clients each with own IP-address.
* [__drill__](https://github.com/fcsonline/drill) - A HTTP load testing application, written in `Rust`, inspired by Ansible syntax.
* [__f1__](https://github.com/form3tech-oss/f1) - A flexible load testing framework using `Go` for test scenarios.
* [__fasthttploader__](https://github.com/hagen1778/fasthttploader) - HTTP benchmark (kinda [ab](https://httpd.apache.org/docs/current/programs/ab.html)) with autoadjustment and charts based on fasthttp library. `Go`
* [__fbender__](https://github.com/facebookincubator/fbender) - A load testing command line tool for generic network protocols, originally based on [bender](https://github.com/pinterest/bender) library. `Go`
* [__fortio__](https://github.com/fortio/fortio) - Load testing library, command line tool, advanced echo server and web UI in `Go`.
* [__freeloader__](https://github.com/rprieto/freeloader) - Super easy load testing framework, with load scenarios in `JavaScript`.
* [__go-meter__](https://github.com/a696385/go-meter) - A HTTP benchmark tool written in `Go`.
* [__go-wrk__](https://github.com/adjust/go-wrk) - A small heavy duty HTTP/S benchmark tool, similar to [wrk](https://github.com/wg/wrk), but written in `Go`.
* [__goad__](https://github.com/goadapp/goad) - An AWS Lambda powered, highly distributed, load testing tool. `Go`
* [__gobench__](https://github.com/cmpxchg16/gobench) - HTTP/S load testing and benchmarking tool. `Go`
* [__gohttpbench__](https://github.com/parkghost/gohttpbench) - An [ab](https://httpd.apache.org/docs/current/programs/ab.html)-like benchmark tool run on multi-core cpu. `Go`
* [__goku__](https://github.com/k-nasa/goku) - HTTP load testing application written in `Rust`.
* [__goose__](https://github.com/tag1consulting/goose) - A `Rust` load testing tool inspired by [locust](https://github.com/locustio/locust).
* [__hargo__](https://github.com/mrichman/hargo) - `Go` library and command line utility that parses HAR files, can convert to [curl](https://github.com/curl/curl) format, and serve as a load test driver.
* [__hey__](https://github.com/rakyll/hey) - HTTP load generator, [ab](https://httpd.apache.org/docs/current/programs/ab.html) replacement. `Go`
* [__htstress__](https://github.com/arut/htstress) - Fast HTTP benchmarking tool, similar to [ab](https://httpd.apache.org/docs/current/programs/ab.html) but provides multithreading support. `C`
* [__httperf__](https://github.com/httperf/httperf) - A tool for measuring web server performance. `C`
* [__httpit__](https://github.com/gonetx/httpit) - A rapid HTTP/S benchmark tool, written in `Go`.
* [__httpress__](https://github.com/virtuozzo/httpress) - High performance HTTP server stress & benchmark utility, inspired by [weighttp](https://github.com/lighttpd/weighttp). `C`
* [__hurl__](https://github.com/EdgeCast/hurl) - HTTP server load test and parallel [curl](https://github.com/curl/curl) utilities. `C++`
* [__iago2__](https://github.com/twitter/iago2) - A load generator, built for engineers. `Scala`
* [__jbender__](https://github.com/pinterest/jbender) - A port of [bender](https://github.com/pinterest/bender) to the JVM platform with Quasar lightweight threads (fibers) and channels. `Java`
* [__jetty-load-generator__](https://github.com/jetty-project/jetty-load-generator) - An API for load testing HTTP servers, based on Jetty's HttpClient and `Java` 11+.
* [__kboom__](https://github.com/mhausenblas/kboom) - The Kubernetes scale & soak load tester, equivalent of [boom](https://github.com/tarekziade/boom), written in `Go`.
* [__legion__](https://github.com/lane-webperformance/legion) - A `JavaScript`-based load testing tool for HTTP servers and other kinds of software.
* [__loadtest__](https://github.com/alexfernandez/loadtest) - A `JavaScript` package for load testing with HTTP/S and WebSockets support and API for easy integration.
* [__mgun__](https://github.com/byorty/mgun) - A modern tool for load testing HTTP servers, written in `Go`.
* [__molotov__](https://github.com/loads/molotov) - Simple `Python` 3.5+ tool to write load tests.
* [__nbomber__](https://github.com/PragmaticFlow/NBomber) - Very simple load testing framework for Pull and Push scenarios, written in `F#` and targeting .NET Core and full .NET Framework.
* [__netling__](https://github.com/hallatore/netling) - Load testing client for easy web testing. `C#`
* [__node-ab__](https://github.com/doubaokun/node-ab) - A command line tool to test the performance of HTTP services. `Node.js`
* [__node-vegeta__](https://github.com/jbarabander/node-vegeta) - `Node.js` bindings for the [vegeta](https://github.com/tsenart/vegeta) load testing library.
* [__oha__](https://github.com/hatoo/oha) - HTTP load generator, inspired by [hey](https://github.com/rakyll/hey) with tui animation. `Rust`
* [__pandora__](https://github.com/yandex/pandora) - A load generator in `Go`, with built-in HTTP/S and HTTP/2 support and load scenarios in `Go`.
* [__plow__](https://github.com/six-ddc/plow) - A high-performance HTTP benchmarking tool with real-time web UI and terminal displaying. `Go`
* [__ponos__](https://github.com/klarna/ponos) - Simple yet powerful load generator written in `Erlang`.
* [__pounce__](https://github.com/fredrikwidlund/pounce) – HTTP benchmark utility, written in `C`.
* [__pronk__](https://github.com/bos/pronk) - A small command line application for load testing web servers. `Haskell`
* [__reqstress__](https://github.com/utkusen/reqstress) - A benchmarking & stressing tool that can send raw HTTP requests, written in `Go`.
* [__rewrk__](https://github.com/ChillFish8/rewrk) - A modern HTTP framework benchmarking utility supporting HTTP/1 and HTTP/2 benchmarks. `Rust`
* [__salvo__](https://github.com/tarekziade/salvo) - Like [boom](https://github.com/tarekziade/boom), but based on [molotov](https://github.com/loads/molotov). `Python`
* [__siege__](https://github.com/JoeDog/siege) - A HTTP load tester and benchmarking utility. `C`
* [__slapper__](https://github.com/ikruglov/slapper) - Simple load testing tool with real-time updated histogram of request timings. `Go`
* [__slow_cooker__](https://github.com/BuoyantIO/slow_cooker) - A load tester focused on lifecycle issues and long-running tests. `Go`
* [__sniper__](https://github.com/btfak/sniper) - Powerful and high-performance HTTP load tester, written in `Go`.
* [__stress__](https://github.com/yarax/stress) - Simple `Node.js` tool for stress testing HTTP services.
* [__thrash__](https://github.com/TylerBrock/thrash) - `Go` HTTP micro benchmarker.
* [__vegeta__](https://github.com/tsenart/vegeta) - HTTP load testing tool and library. `Go`
* [__vex__](https://github.com/vamsiikrishna/vex) - A small `PHP` app that sends some load to a web application.
* [__weighttp__](https://github.com/lighttpd/weighttp) - A lightweight and simple webserver benchmarking tool. `C`
* [__welle__](https://github.com/rylev/welle) - An [ab](https://httpd.apache.org/docs/current/programs/ab.html)-like benchmarking tool written in `Rust`.
* [__wrk__](https://github.com/wg/wrk) - Modern HTTP benchmarking tool. `C`
* [__wrk2__](https://github.com/giltene/wrk2) - A constant throughput, correct latency recording variant of [wrk](https://github.com/wg/wrk). `C`

### non-http/s

* [__amoc__](https://github.com/esl/amoc) - A simple framework for running massively parallel XMPP tests in a distributed environment. `Erlang`
* [__bench__](https://github.com/tylertreat/bench) - A generic latency benchmarking library. `Go`
* [__bomberman__](https://github.com/c1982/bomberman) - SMTP performance and load testing tool. `Go`
* [__emqtt-bench__](https://github.com/emqx/emqtt-bench) - A simple MQTT v5.0 benchmark tool written in `Erlang`.
* [__flotilla__](https://github.com/tylertreat/Flotilla) - Automated message queue orchestration for scaled-up benchmarking. `Go`
* [__ghz__](https://github.com/bojand/ghz) - Simple gRPC benchmarking and load testing tool. `Go`
* [__graphql-bench__](https://github.com/hasura/graphql-bench) - A versatile tool for benchmarking and load-testing GraphQL services, as a CLI application or via programmatic API. `TSQL`
* [__massive-attack__](https://github.com/delprks/massive-attack) - Load testing Thrift, made simple. `Scala`
* [__memtier_benchmark__](https://github.com/RedisLabs/memtier_benchmark) - NoSQL Redis and Memcache traffic generation and benchmarking tool. `C++`
* [__mqperf__](https://github.com/softwaremill/mqperf) - A benchmark of message queues with data replication and at-least-once delivery guarantees. `Scala`
* [__mqtt-benchmark__](https://github.com/krylovsk/mqtt-benchmark) - A simple MQTT (broker) benchmarking tool. `Go`
* [__rabbitmq-perf-test__](https://github.com/rabbitmq/rabbitmq-perf-test) - RabbitMQ performance testing tool. `Java`
* [__rpc-perf__](https://github.com/twitter/rpc-perf) - A tool for benchmarking RPC services. `Rust`
* [__rtmp_load__](https://github.com/fillest/rtmp_load) - A load testing tool for RTMP servers. `C`
* [__sangrenel__](https://github.com/jamiealquiza/sangrenel) - Apache Kafka load testing. `Go`
* [__srs-bench__](https://github.com/ossrs/srs-bench) - A HTTP/RTMP/HLS load testing and benchmarking tool. `C++`
* [__ssh-hammer__](https://github.com/shazow/ssh-hammer) - A SSH load testing tool. `Go`
* [__tcpkali__](https://github.com/satori-com/tcpkali) - Fast multi-core TCP and WebSockets load generator. `C`

### multi-protocol

* [__artillery__](https://github.com/artilleryio/artillery) - A modern load and functional testing toolkit written in `Node.js`, with test scenario scripting in `Javascript`.
* [__ddosify__](https://github.com/ddosify/ddosify) - High-performance load testing and DDOS attack simulation tool, written in `Go`.
* [__gatling__](https://github.com/gatling/gatling) - A load and performance testing framework based on `Scala`, Akka and Netty.
* [__grinder__](https://github.com/cossme/grinder) - A distributed load testing framework written in `Java`, with test scenario scripting in `Jython` and `Clojure`.
* [__jagger__](https://github.com/griddynamics/jagger) - An open source framework for Continuous Performance Testing written in `Java`.
* [__jmeter__](https://github.com/apache/jmeter) - A `Java` tool designed to load test functional behavior and measure performance of a variety of services, with a focus on web applications.
* [__k6__](https://github.com/grafana/k6) - A modern load testing tool, using `Go` and `JavaScript`.
* [__locust__](https://github.com/locustio/locust) - Scalable distributed load testing tool written in `Python`.
* [__multi-mechanize__](https://github.com/cgoldberg/multi-mechanize) - Performance and load testing framework written in `Python`.
* [__mzbench__](https://github.com/satori-com/mzbench) - Expressive, scalable load testing tool, with multiple protocols support. `Erlang`
* [__ngrinder__](https://github.com/naver/ngrinder) - Enterprise level performance testing solution based on [The Grinder](https://github.com/cossme/grinder). `Java`
* [__predator__](https://github.com/Zooz/predator) - A distributed open-source platform for load testing APIs using custom version of [artillery](https://github.com/artilleryio/artillery) as load testing engine. `Node.js`
* [__tank__](https://github.com/intuit/Tank) - A cloud native load testing platform. `Java`
* [__tsung__](https://github.com/processone/tsung) - A multi-protocol distributed load testing tool, developed in `Erlang`.
* [__yandex-tank__](https://github.com/yandex/yandex-tank) - An extendable load testing tool which is especially good as a part of an automated load testing suite. `Python`, `C`

### storage

* [__ioarena__](https://github.com/pmwkaa/ioarena) - Embedded storage benchmarking tool. `C`
* [__cosbench__](https://github.com/intel-cloud/cosbench) - A benchmark tool for cloud object storage service. `Java`
* [__go-ycsb__](https://github.com/pingcap/go-ycsb) - A Go port of Yahoo! Cloud Serving Benchmark ([YCSB](https://github.com/brianfrankcooper/YCSB)). `Go`
* [__mongoose__](https://github.com/emc-mongoose/mongoose) - Distributed storage performance testing tool. `Java`
* [__ndbench__](https://github.com/Netflix/ndbench) - Netflix Data Store Benchmark, a pluggable cloud-enabled benchmarking tool that can be used across any data store system. `Java`
* [__tsbs__](https://github.com/timescale/tsbs) - Time Series Benchmark Suite, a tool for comparing and evaluating databases for time series data. `Go`
* [__ycsb__](https://github.com/brianfrankcooper/YCSB) - Yahoo! Cloud Serving Benchmark (YCSB), a framework and common set of workloads for evaluating the performance of different "key-value" and "cloud" serving stores. `Java`

## Stress testing

### http/s

* [__hulken__](https://github.com/hellgrenj/hulken) - Stress testing tool for everything speaking HTTP. `JavaScript`
* [__pewpew__](https://github.com/bengadbois/pewpew) - Flexible HTTP command line stress tester for websites and web services. `Go`

### non-http/s

* [__dhammer__](https://github.com/ipchama/dhammer) - DHCP stress tester and benchmark tool. `Go`
* [__dnstress__](https://github.com/safedns/dnstress) - A DNS stress testing tool. `C`
* [__mqtt-stresser__](https://github.com/inovex/mqtt-stresser) - Load testing tool to stress MQTT message broker. `Go`

## DoS/DDoS penetration testing

> For educational and security/stress testing (as part of development) purposes only.

* [__finshir__](https://github.com/isgasho/finshir) - A coroutines-driven Low & Slow traffic sender, written in `Rust`.
* [__golden-eye__](https://github.com/jseidl/GoldenEye) - HTTP DoS test tool using HTTP Keep Alive + NoCache as attack vector. `Python`
* [__goloris__](https://github.com/valyala/goloris) - [Slowloris](https://github.com/gkbrk/slowloris) implementation for nginx DoS written in `Go`.
* [__hulk__](https://github.com/grafov/hulk) - Original HULK web server DoS attack tool ported to `Go` with some additional features.
* [__hulk-v3__](https://github.com/Hyperclaw79/HULK-v3) - `Python` 3 compatible async HULK script for DDoS attacks.
* [__lor-axe__](https://github.com/ajmwagar/lor-axe) - A multi-threaded, low-bandwidth HTTP DoS tool, written in `Rust`.
* [__slowhttptest__](https://github.com/shekyan/slowhttptest) - A highly configurable application layer DoS attack simulator. `C++`
* [__slowloris__](https://github.com/gkbrk/slowloris) - Low bandwidth DoS tool, rewrite in `Python`.
* [__wreckuests__](https://github.com/abriginets/wreckuests) - Yet another one hard-hitting tool to run DDoS attacks with HTTP-flood. `Python`
