# Load Testing Toolkit

> *“I have enough trouble with useful information, never mind being burdened with what is useless.”*\
> ― Erlend Loe, Naïve. Super

Collection of __open-source__ tools for debugging, benchmarking, load and stress testing your code or services.

__NOTE:__ Unfortunately I've found this original *awesome* collection too late: [__awesome-http-benchmark__](https://github.com/denji/awesome-http-benchmark).\
Feel free to follow and contribute to it instead of this collection, which remains my personal variation and working copy.

> In alphabetical order.

## Contents

* [Debugging & API testing](#debugging--api-testing)
* [Benchmarking & load testing](#benchmarking--load-testing)
* [DoS/DDoS penetration testing](#dosddos-penetration-testing)
* [Traffic replay](#traffic-replay)

## Debugging & API testing

* [__baloo__](https://github.com/h2non/baloo) - Expressive and versatile end-to-end HTTP API testing made easy in `Go`.
* [__bat__](https://github.com/astaxie/bat) - A [curl](https://github.com/curl/curl)-like tool for humans, inspired by [httpie](https://github.com/httpie/cli), written in `Go`.
* [__curl__](https://github.com/curl/curl) - A command line tool and library for transferring data with URL syntax. `C`
* [__curlie__](https://github.com/rs/curlie) - The power of [curl](https://github.com/curl/curl), the ease of use of [httpie](https://github.com/httpie/cli). `Go`
* [__curlx__](https://github.com/shivkanthb/curlx) - Supercharge [curl](https://github.com/curl/curl) with history, collections and more. `JavaScript`
* [__hopp-cli__](https://github.com/hoppscotch/hopp-cli) - An HTTP CLI client for [hoppscotch](https://hoppscotch.io/), an alternative to [curl](https://github.com/curl/curl), [httpie](https://github.com/httpie/cli). `Go`
* [__httpcat__](https://github.com/httpie/httpcat) - A simple utility for constructing raw HTTP requests on the command line. `Python`
* [__httpie__](https://github.com/httpie/cli) - Modern command line HTTP client, user-friendly [curl](https://github.com/curl/curl) alternative with intuitive UI, JSON support, syntax highlighting, wget-like downloads, extensions, etc. `Python`
* [__httpie-go__](https://github.com/nojima/httpie-go) - [httpie](https://github.com/httpie/cli)-like HTTP client written in `Go`.
* [__httping__](https://github.com/folkertvanheusden/httping) - A ping-like utility for HTTP requests. `C`
* [__httpstat__](https://github.com/reorx/httpstat) - [curl](https://github.com/curl/curl) statistics visualization in a way of beauty and clarity. `Python`
* [__hurl__](https://github.com/Orange-OpenSource/hurl) - A command line tool to perform HTTP requests defined in a simple plain text format. `Rust`
* [__wuzz__](https://github.com/asciimoo/wuzz) - Interactive command line tool for HTTP inspection. `Go`
* [__xh__](https://github.com/ducaale/xh) – Yet another [httpie](https://github.com/httpie/cli) clone in `Rust`.

## Benchmarking & load testing

### http/s

* [__ab__](https://httpd.apache.org/docs/current/programs/ab.html) - ApacheBench, single-threaded Apache HTTP server benchmarking tool. `C`
* [__ali__](https://github.com/nakabonne/ali) - A load testing tool capable of performing real-time analysis, inspired by [vegeta](https://github.com/tsenart/vegeta), written in `Go`.
* [__apachebench-ab__](https://github.com/CloudFundoo/ApacheBench-ab) - Standalone version of [ab](https://httpd.apache.org/docs/current/programs/ab.html), Apache HTTP server benchmarking tool. `C`
* [__apib__](https://github.com/apigee/apib) - A simple, fast HTTP and API benchmarking tool. `C++`
* [__autocannon__](https://github.com/mcollina/autocannon) - Fast HTTP/1.1 benchmarking tool written in `Node.js`, greatly inspired by [wrk](https://github.com/wg/wrk) and [wrk2](https://github.com/giltene/wrk2), with support for HTTP pipelining and HTTPS.
* [__baton__](https://github.com/americanexpress/baton) - HTTP load testing written in `Go`.
* [__beast__](https://github.com/jjmrocha/beast) - Stress testing for RESTful APIs. `Go`
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
* [__clobbr__](https://github.com/parsecph/clobbr) - A tool to check the speed and resilience of API endpoints against multiple parallel or sequence requests. `JavaScript`
* [__curl-loader__](https://curl-loader.sourceforge.net/) - A load generating tool written in `C`, simulating HTTP/S, FTP/S and TLS/SSL clients each with own IP-address.
* [__drill__](https://github.com/fcsonline/drill) - A HTTP load testing application, written in `Rust`, inspired by Ansible syntax.
* [__encarno__](https://github.com/undera/encarno) - Load generator for HTTP with high throughput and high precision. `Go`
* [__f1__](https://github.com/form3tech-oss/f1) - A flexible load testing framework using `Go` for test scenarios.
* [__fasthttploader__](https://github.com/hagen1778/fasthttploader) - HTTP benchmark (kinda [ab](https://httpd.apache.org/docs/current/programs/ab.html)) with autoadjustment and charts based on fasthttp library. `Go`
* [__fbender__](https://github.com/facebookarchive/fbender) - A load testing command line tool for generic network protocols, originally based on [bender](https://github.com/pinterest/bender) library. `Go`
* [__fortio__](https://github.com/fortio/fortio) - Load testing library, command line tool, advanced echo server and web UI in `Go`.
* [__freeloader__](https://github.com/rprieto/freeloader) - Super easy load testing framework, with load scenarios in `JavaScript`.
* [__go-meter__](https://github.com/a696385/go-meter) - A HTTP benchmark tool written in `Go`.
* [__go-wrk__](https://github.com/adjust/go-wrk) - A small heavy duty HTTP/S benchmark tool, similar to [wrk](https://github.com/wg/wrk), but written in `Go`.
* [__goad__](https://github.com/goadapp/goad) - An AWS Lambda powered, highly distributed, load testing tool. `Go`
* [__gobench__](https://github.com/cmpxchg16/gobench) - HTTP/S load testing and benchmarking tool. `Go`
* [__gocannon__](https://github.com/kffl/gocannon) - A lightweight HTTP benchmarking tool, intended to measure changes in backend application performance over time. `Go`
* [__gohttpbench__](https://github.com/parkghost/gohttpbench) - An [ab](https://httpd.apache.org/docs/current/programs/ab.html)-like benchmark tool run on multi-core cpu. `Go`
* [__goku__](https://github.com/k-nasa/goku) - HTTP load testing application written in `Rust`.
* [__goku-bench__](https://github.com/jcaromiq/goku) - An HTTP load testing tool built out of a need to drill HTTP services inspired by [drill](https://github.com/fcsonline/drill) and [vegeta](https://github.com/tsenart/vegeta). `Rust`
* [__goose__](https://github.com/tag1consulting/goose) - A `Rust` load testing tool inspired by [locust](https://github.com/locustio/locust).
* [__gopayloader__](https://github.com/domsolutions/gopayloader) - HTTP/S benchmark/load testing cross-platform tool with optional JWT generation, inspired by [bombardier](https://github.com/codesenberg/bombardier). `Go`
* [__goperf__](https://github.com/gnulnx/goperf) - `Go` based load tester with a simple intuitive command line syntax.
* [__hargo__](https://github.com/mrichman/hargo) - `Go` library and command line utility that parses HAR files, can convert to [curl](https://github.com/curl/curl) format, and serve as a load test driver.
* [__hey__](https://github.com/rakyll/hey) - HTTP load generator, [ab](https://httpd.apache.org/docs/current/programs/ab.html) replacement. `Go`
* [__htstress__](https://github.com/arut/htstress) - Fast HTTP benchmarking tool, similar to [ab](https://httpd.apache.org/docs/current/programs/ab.html) but provides multithreading support. `C`
* [__http_bench__](https://github.com/linkxzhou/http_bench) - An HTTP(/1/2/3) and WebSockets stress testing tool, with both single and distributed modes. `Go`
* [__httperf__](https://github.com/httperf/httperf) - A tool for measuring web server performance. `C`
* [__httpit__](https://github.com/gonetx/httpit) - A rapid HTTP/S benchmark tool, written in `Go`.
* [__httpress__](https://github.com/virtuozzo/httpress) - High performance HTTP server stress & benchmark utility, inspired by [weighttp](https://github.com/lighttpd/weighttp). `C`
* [__hulken__](https://github.com/hellgrenj/hulken) - Stress testing tool for everything speaking HTTP. `JavaScript`
* [__hurl__](https://github.com/edgio/hurl) - HTTP server load test and parallel [curl](https://github.com/curl/curl) utilities. `C++`
* [__iago2__](https://github.com/twitter/iago2) - A load generator, built for engineers. `Scala`
* [__jbender__](https://github.com/pinterest/jbender) - A port of [bender](https://github.com/pinterest/bender) to the JVM platform with Quasar lightweight threads (fibers) and channels. `Java`
* [__jetty-load-generator__](https://github.com/jetty-project/jetty-load-generator) - An API for load testing HTTP servers, based on Jetty's HttpClient and `Java` 11+.
* [__legion__](https://github.com/lane-webperformance/legion) - A `JavaScript`-based load testing tool for HTTP servers and other kinds of software.
* [__loadtest__](https://github.com/alexfernandez/loadtest) - A `JavaScript` package for load testing with HTTP/S and WebSockets support and API for easy integration.
* [__loadtesttoolbox__](https://github.com/ecoAPM/LoadTestToolbox) - Lightweight tools for load testing web applications, written in `C#`.
* [__mgun__](https://github.com/byorty/mgun) - A modern tool for load testing HTTP servers, written in `Go`.
* [__minigun__](https://github.com/wayfair-incubator/minigun) - Simple Kubernetes native HTTP benchmark tool, written in `Go`.
* [__molotov__](https://github.com/tarekziade/molotov) - Simple `Python` 3.7+ tool to write load tests.
* [__nbomber__](https://github.com/PragmaticFlow/NBomber) - Very simple load testing framework for Pull and Push scenarios, written in `F#` and targeting .NET Core and full .NET Framework.
* [__netling__](https://github.com/hallatore/netling) - Load testing client for easy web testing. `C#`
* [__node-ab__](https://github.com/doubaokun/node-ab) - A command line tool to test the performance of HTTP services. `Node.js`
* [__node-vegeta__](https://github.com/jbarabander/node-vegeta) - `Node.js` bindings for the [vegeta](https://github.com/tsenart/vegeta) load testing library.
* [__oha__](https://github.com/hatoo/oha) - HTTP load generator, inspired by [hey](https://github.com/rakyll/hey) with tui animation. `Rust`
* [__pandora__](https://github.com/yandex/pandora) - A load generator in `Go`, with built-in HTTP/S and HTTP/2 support and load scenarios in `Go`.
* [__pewpew__](https://github.com/bengadbois/pewpew) - Flexible HTTP command line stress tester for websites and web services. `Go`
* [__plow__](https://github.com/six-ddc/plow) - A high-performance HTTP benchmarking tool with real-time web UI and terminal displaying. `Go`
* [__ponos__](https://github.com/klarna/ponos) - Simple yet powerful load generator written in `Erlang`.
* [__pounce__](https://github.com/fredrikwidlund/pounce) – HTTP benchmark utility, written in `C`.
* [__pronk__](https://github.com/bos/pronk) - A small command line application for load testing web servers. `Haskell`
* [__reqstress__](https://github.com/utkusen/reqstress) - A benchmarking & stressing tool that can send raw HTTP requests, written in `Go`.
* [__rewrk__](https://github.com/lnx-search/rewrk) - A modern HTTP framework benchmarking utility supporting HTTP/1 and HTTP/2 benchmarks. `Rust`
* [__salvo__](https://github.com/tarekziade/salvo) - Like [boom](https://github.com/tarekziade/boom), but based on [molotov](https://github.com/tarekziade/molotov). `Python`
* [__sb__](https://github.com/aliostad/SuperBenchmarker) - SuperBenchmarker, ApacheBench ([ab](https://httpd.apache.org/docs/current/programs/ab.html)) on steroids. `C#`
* [__siege__](https://github.com/JoeDog/siege) - A HTTP load tester and benchmarking utility. `C`
* [__slapper__](https://github.com/ikruglov/slapper) - Simple load testing tool with real-time updated histogram of request timings. `Go`
* [__slow_cooker__](https://github.com/BuoyantIO/slow_cooker) - A load tester focused on lifecycle issues and long-running tests. `Go`
* [__sniper__](https://github.com/btfak/sniper) - Powerful and high-performance HTTP load tester, written in `Go`.
* [__stress__](https://github.com/yarax/stress) - Simple `Node.js` tool for stress testing HTTP services.
* [__terjang__](https://github.com/andylibrian/terjang) - Scalable HTTP load testing tool built on [vegeta](https://github.com/tsenart/vegeta). `Go`
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
* [__dhammer__](https://github.com/ipchama/dhammer) - DHCP stress tester and benchmark tool. `Go`
* [__massive-attack__](https://github.com/delprks/massive-attack) - Load testing Thrift, made simple. `Scala`
* [__rpc-perf__](https://github.com/twitter/rpc-perf) - A tool for benchmarking RPC services. `Rust`
* [__rtmp_load__](https://github.com/fillest/rtmp_load) - A load testing tool for RTMP servers. `C`
* [__srs-bench__](https://github.com/ossrs/srs-bench) - A HTTP/RTMP/HLS load testing and benchmarking tool. `C++`
* [__ssh-hammer__](https://github.com/shazow/ssh-hammer) - A SSH load testing tool. `Go`
* [__tcpkali__](https://github.com/satori-com/tcpkali) - Fast multi-core TCP and WebSockets load generator. `C`

#### dns

* [__dnsblast__](https://github.com/sandeeprenjith/dnsblast) - A DNS performance testing utility. `Go`
* [__dnsblast__](https://github.com/jedisct1/dnsblast) - A simple and stupid load testing tool for DNS resolvers. `C`
* [__dnsmeter__](https://github.com/DNS-OARC/dnsmeter) - A tool for testing performance of nameservers and the infrastructure around it. `C++`
* [__dnsperf__](https://github.com/DNS-OARC/dnsperf) - DNS performance testing tools. `C`
* [__dnstress__](https://github.com/safedns/dnstress) - A DNS stress testing tool. `C`
* [__flamethrower__](https://github.com/DNS-OARC/flamethrower) - A DNS performance and functional testing utility, originally built as an alternative to [dnsperf](https://github.com/DNS-OARC/dnsperf). `C++`

#### grpc

* [__ghz__](https://github.com/bojand/ghz) - Simple gRPC benchmarking and load testing tool. `Go`
* [__strest-grpc__](https://github.com/BuoyantIO/strest-grpc) - A load tester for stress testing gRPC intermediaries. `Go`

#### kafka

* [__kafka-stress__](https://github.com/msfidelis/kafka-stress) - CLI tool to stress Apache Kafka clusters. `Go`
* [__sangrenel__](https://github.com/jamiealquiza/sangrenel) - Apache Kafka load testing. `Go`

#### mq

* [__emqtt-bench__](https://github.com/emqx/emqtt-bench) - A simple MQTT v5.0 benchmark tool written in `Erlang`.
* [__flotilla__](https://github.com/tylertreat/Flotilla) - Automated message queue orchestration for scaled-up benchmarking. `Go`
* [__mqperf__](https://github.com/softwaremill/mqperf) - A benchmark of message queues with data replication and at-least-once delivery guarantees. `Scala`
* [__mqtt-benchmark__](https://github.com/krylovsk/mqtt-benchmark) - A simple MQTT (broker) benchmarking tool. `Go`
* [__mqtt-stresser__](https://github.com/inovex/mqtt-stresser) - Load testing tool to stress MQTT message broker. `Go`
* [__mqttloader__](https://github.com/dist-sys/mqttloader) - Load testing tool for MQTT, capable of benchmark test for both MQTT v5.0 and v3.1.1 brokers. `Java`
* [__mqttwrk__](https://github.com/bytebeamio/mqttwrk) - A [wrk](https://github.com/wg/wrk)/[wrk2](https://github.com/giltene/wrk2)-inspired tool for scale and performance testing MQTT brokers. `Rust`
* [__rabbitmq-perf-test__](https://github.com/rabbitmq/rabbitmq-perf-test) - RabbitMQ performance testing tool. `Java`

### multi-protocol

* [__artillery__](https://github.com/artilleryio/artillery) - A modern load and functional testing toolkit written in `Node.js`, with test scenario scripting in `JavaScript`.
* [__ddosify__](https://github.com/ddosify/ddosify) - High-performance load testing and DDOS attack simulation tool, written in `Go`.
* [__gatling__](https://github.com/gatling/gatling) - A load and performance testing framework based on `Scala`, Akka and Netty.
* [__grinder__](https://github.com/cossme/grinder) - A distributed load testing framework written in `Java`, with test scenario scripting in `Jython` and `Clojure`.
* [__jagger__](https://github.com/griddynamics/jagger) - An open-source framework for Continuous Performance Testing written in `Java`.
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

### nosql

* [__memtier_benchmark__](https://github.com/RedisLabs/memtier_benchmark) - A high-throughput benchmarking tool for Redis & Memcached. `C++`
* [__redisbench__](https://github.com/panjiang/redisbench) - Redis & Redis cluster benchmarking tool. `Go`

### storage

#### data store

* [__go-ycsb__](https://github.com/pingcap/go-ycsb) - A Go port of Yahoo! Cloud Serving Benchmark ([YCSB](https://github.com/brianfrankcooper/YCSB)). `Go`
* [__ndbench__](https://github.com/Netflix/ndbench) - Netflix Data Store Benchmark, a pluggable cloud-enabled benchmarking tool that can be used across any data store system. `Java`
* [__ycsb__](https://github.com/brianfrankcooper/YCSB) - Yahoo! Cloud Serving Benchmark (YCSB), a framework and common set of workloads for evaluating the performance of different "key-value" and "cloud" serving stores. `Java`

#### io

* [__diskspd__](https://github.com/microsoft/diskspd) - A storage performance testing tool from the Windows, Windows Server and Cloud Server Infrastructure engineering teams at Microsoft. `C++`
* [__fio__](https://github.com/axboe/fio) - Flexible I/O tester. `C`
* [__ioarena__](https://github.com/pmwkaa/ioarena) - Embedded storage benchmarking tool. `C`

#### object storage

* [__cosbench__](https://github.com/intel-cloud/cosbench) - A benchmark tool for cloud object storage service. `Java`
* [__gosbench__](https://github.com/mulbc/gosbench) - Distributed S3 performance benchmark tool with Prometheus exporter, `Go` reimplementation of [cosbench](https://github.com/intel-cloud/cosbench).
* [__mongoose__](https://github.com/emc-mongoose/mongoose) - Distributed storage performance testing tool. `Java`
* [__os-benchmark__](https://github.com/cloudmercato/os-benchmark) - Handy tool for object storage performance benchmarking. `Python`
* [__ostorebench__](https://github.com/EVERYGO111/OStoreBench) - A benchmark tool for distributed object storage systems. `Go`
* [__s3-benchmark__](https://github.com/dvassallo/s3-benchmark) - S3 benchmarking tool. `Go`
* [__warp__](https://github.com/minio/warp) - S3 benchmarking tool. `Go`

#### time-series

* [__prometheus-benchmark__](https://github.com/VictoriaMetrics/prometheus-benchmark) - Benchmark for Prometheus-compatible systems on production-like workload. `Go`
* [__tsbs__](https://github.com/timescale/tsbs) - Time Series Benchmark Suite, a tool for comparing and evaluating databases for time series data. `Go`

### k8s

* [__k8s-bench-suite__](https://github.com/InfraBuilder/k8s-bench-suite) - Simple scripts to benchmark Kubernetes cluster features. `Shell`
* [__k8s-netperf__](https://github.com/jtaleric/k8s-netperf) - Running networking performance tests against Kubernetes. `Go`
* [__k-bench__](https://github.com/vmware-tanzu/k-bench) - Workload benchmark for Kubernetes. `Go`
* [__kboom__](https://github.com/mhausenblas/kboom) - The Kubernetes scale & soak load tester, equivalent of [boom](https://github.com/tarekziade/boom), written in `Go`.
* [__kube-burner__](https://github.com/kube-burner/kube-burner) - A tool aimed at stressing Kubernetes clusters by creating or deleting a high quantity of objects. `Go`

### graphql

* [__easygraphql-load-tester__](https://github.com/EasyGraphQL/easygraphql-load-tester) - A `Node.js` library created to make load testing on GraphQL based on the schema.
* [__graphql-bench__](https://github.com/hasura/graphql-bench) - A versatile tool for benchmarking and load testing GraphQL services, as a CLI application or via programmatic API. `TSQL`

### blockchain

* [__caliper__](https://github.com/hyperledger/caliper) - A blockchain benchmark framework to measure performance of multiple blockchain solutions. `JavaScript`
* [__gohammer__](https://github.com/tubuarge/gohammer) - A blockchain test tool designed to get performance metrics of the nodes and operation system by deploying a smart contract and calling smart contract's methods. `Go`

## DoS/DDoS penetration testing

> For educational and security/stress testing (as part of development) purposes only.

* [__finshir__](https://github.com/isgasho/finshir) - A coroutines-driven Low & Slow traffic sender, written in `Rust`.
* [__golden-eye__](https://github.com/jseidl/GoldenEye) - HTTP DoS test tool using HTTP Keep Alive + NoCache as attack vector. `Python`
* [__goloris__](https://github.com/valyala/goloris) - [Slowloris](https://github.com/gkbrk/slowloris) implementation for nginx DoS written in `Go`.
* [__hulk__](https://github.com/grafov/hulk) - Original HULK web server DoS attack tool ported to `Go` with some additional features.
* [__hulk-v3__](https://github.com/Hyperclaw79/HULK-v3) - `Python` 3 compatible async HULK script for DDoS attacks.
* [__lor-axe__](https://github.com/ajmwagar/lor-axe) - A multi-threaded, low-bandwidth HTTP DoS tool, written in `Rust`.
* [__rip__](https://github.com/bjarneo/rip) - An HTTP load testing and UDP flood attack tool. `Go`
* [__slowhttptest__](https://github.com/shekyan/slowhttptest) - A highly configurable application layer DoS attack simulator. `C++`
* [__slowloris__](https://github.com/gkbrk/slowloris) - Low bandwidth DoS tool, rewrite in `Python`.
* [__wreckuests__](https://github.com/abriginets/wreckuests) - Yet another one hard-hitting tool to run DDoS attacks with HTTP-flood. `Python`

## Traffic replay

* [__goreplay__](https://github.com/buger/goreplay) - A network monitoring tool which can record live traffic, and use it for shadowing, load testing, monitoring and detailed analysis. `Go`
* [__ripley__](https://github.com/loveholidays/ripley) - HTTP traffic replay tool at multiples of the original rate. `Go`
* [__tcpcopy__](https://github.com/session-replay-tools/tcpcopy) - A TCP stream replay tool to support real testing of server applications. `C`

## Contribute

Contributions are welcome!\
Read the [CONTRIBUTING](CONTRIBUTING.md) guidelines first.
