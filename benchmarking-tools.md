## Benchmarking & load testing
*Tools to benchmark & load-test your code or services*

### http/s

* [__apachebench (ab)__](https://github.com/CloudFundoo/ApacheBench-ab) - Standalone [apachebench (ab)](http://httpd.apache.org/docs/current/programs/ab.html), Apache HTTP server benchmarking tool. `C`
* [__httperf__](https://github.com/httperf/httperf) - A tool for measuring web server performance. `C`
* [__hey__](https://github.com/rakyll/hey) - HTTP load generator, [ab](https://github.com/CloudFundoo/ApacheBench-ab) replacement. `Go`
* [__boom__](https://github.com/tarekziade/boom) - A replacement for [ab](https://github.com/CloudFundoo/ApacheBench-ab), written in `Python`.
* [__kboom__](https://github.com/mhausenblas/kboom) - The Kubernetes scale & soak load tester, equivalent of [boom](https://github.com/tarekziade/boom), written in `Go`.
* [__break__](https://github.com/tarekziade/break) - Like [boom](https://github.com/tarekziade/boom), but based on [molotov](https://github.com/loads/molotov). `Python`
* [__molotov__](https://github.com/loads/molotov) - Simple `Python` 3.5+ tool to write load tests.
* [__phantomas__](https://github.com/macbre/phantomas) - PhantomJS-based web performance metrics collector and monitoring tool. `JavaScript`
* [__ponos__](https://github.com/klarna/ponos) - Simple yet powerful load generator written in `Erlang`.
* [__siege__](https://github.com/JoeDog/siege) - A HTTP load tester and benchmarking utility. `C`
* [__vegeta__](https://github.com/tsenart/vegeta) - HTTP load testing tool and library. `Go`
* [__sniper__](https://github.com/btfak/sniper) - Powerful and high-performance HTTP load tester, written in `Go`.
* [__wrk__](https://github.com/wg/wrk) - Modern HTTP benchmarking tool. `C`
* [__wrk2__](https://github.com/giltene/wrk2) - A constant throughput, correct latency recording variant of [wrk](https://github.com/wg/wrk). `C`
* [__go-wrk__](https://github.com/adjust/go-wrk) - A small heavy duty HTTP/S benchmark tool, similar to [wrk](https://github.com/wg/wrk), but written in `Go`.
* [__drill__](https://github.com/fcsonline/drill) - A HTTP load testing application, written in `Rust`, inspired by Ansible syntax. 
* [__iago2__](https://github.com/twitter/iago2) - A load generator, built for engineers (Twitter). `Scala`
* [__gohttpbench__](https://github.com/parkghost/gohttpbench) - An [ab](https://github.com/CloudFundoo/ApacheBench-ab)-like benchmark tool run on multi-core cpu. `Go`
* [__gobench__](https://github.com/cmpxchg16/gobench) - HTTP/S load testing and benchmarking tool. `Go`
* [__pronk__](https://github.com/bos/pronk) - A small command line application for load testing web servers. `Haskell`
* [__slow_cooker__](https://github.com/BuoyantIO/slow_cooker) - A load tester focused on lifecycle issues and long-running tests. `Go`
* [__k6__](https://github.com/loadimpact/k6) - A modern load testing tool, using `Go` and `JavaScript`.
* [__bender__](https://github.com/pinterest/bender) - An easy-to-use library for creating load testing applications (Pinterest). `Go`
* [__bombardier__](https://github.com/codesenberg/bombardier) - Fast cross-platform HTTP benchmarking tool written in `Go`.
* [__cassowary__](https://github.com/rogerwelin/cassowary) - Modern cross-platform HTTP load-testing tool written in `Go`.
* [__vex__](https://github.com/vamsiikrishna/vex) - A small `PHP` app that sends some load to a web application.
* [__carrot__](https://github.com/gophercarrot/carrot) - Distributed WebSocket and HTTP load-testing framework in `Go`.
* [__hargo__](https://github.com/mrichman/hargo) - `Go` library and cli utility that parses HAR files, can convert to curl format, and serve as a load test driver.
* [__goku__](https://github.com/k-nasa/goku) - HTTP load testing application written in `Rust`.
* [__scouter__](https://github.com/jbarabander/scouter) - `Node.js` bindings for the [vegeta](https://github.com/tsenart/vegeta) load-testing library.
* [__hurl__](https://github.com/VerizonDigital/hurl) - HTTP server load test and parallel curl utilities. `C++`
* [__chaperon__](https://github.com/polleverywhere/chaperon) - HTTP service performance & load testing framework. `Elixir`
* [__bfg__](https://github.com/yandex-load/bfg) - A modular tool and framework for load generation with HTTP/2 support. `Python`
* [__autocannon__](https://github.com/mcollina/autocannon) - Fast HTTP/1.1 benchmarking tool written in `Node.js`, greatly inspired by [wrk](https://github.com/wg/wrk) and [wrk2](https://github.com/giltene/wrk2), with support for HTTP pipelining and HTTPS.
* [__fortio__](https://github.com/fortio/fortio) - Load testing library, command line tool, advanced echo server and web UI in `Go`.

### non-http/s

* [__rpc-perf__](https://github.com/twitter/rpc-perf) - A tool for benchmarking RPC services (Twitter). `Rust`
* [__tcpkali__](https://github.com/satori-com/tcpkali) - Fast multi-core TCP and WebSockets load generator. `C`
* [__massive-attack__](https://github.com/delprks/massive-attack) - Load testing Thrift, made simple. `Scala`
* [__memtier_benchmark__](https://github.com/RedisLabs/memtier_benchmark) - NoSQL Redis and Memcache traffic generation and benchmarking tool. `C++`
* [__sangrenel__](https://github.com/jamiealquiza/sangrenel) - Apache Kafka load testing. `Go`
* [__rabbitmq-perf-test__](https://github.com/rabbitmq/rabbitmq-perf-test) - RabbitMQ performance testing tool. `Java`

## Stress testing
*Tools to stress-test your code or services*

### http/s

* [__hulken__](https://github.com/hellgrenj/hulken) - Stress testing tool for everything speaking HTTP. `JavaScript`
* [__pewpew__](https://github.com/bengadbois/pewpew) - Flexible HTTP command-line stress tester for websites and web services. `Go`
* [__wreckuests__](https://github.com/JamesJGoodwin/wreckuests) - Yet another one hard-hitting tool to run DDoS atacks with HTTP-flood. `Python`

### non-http/s

* [__mqtt-stresser__](https://github.com/inovex/mqtt-stresser) - Load testing tool to stress MQTT message broker. `Go`
* [__dhammer__](https://github.com/ipchama/dhammer) - DHCP stress tester and benchmark tool. `Go`
* [__dnstress__](https://github.com/safedns/dnstress) - A DNS stress testing tool. `C`
