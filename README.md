<a href="https://erzumshirazi.dev">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://erzumshirazi.dev/github/banner-dark.svg">
    <img alt="Erzum Shirazi. I build systems that stay fast and stay correct under load." src="https://erzumshirazi.dev/github/banner-light.svg" width="100%">
  </picture>
</a>

Software engineer and CS student at TMU, currently at [Print.World](https://print.world) working in Rust and TypeScript on real-time backend systems. Previously IBM and Nokia. I care about performance, reliability, and the trade-offs between them.

[Website](https://erzumshirazi.dev) · [Writing](https://erzumshirazi.dev/writing) · [LinkedIn](https://www.linkedin.com/in/ErzShiraz) · [Email](mailto:erzum5.shirazi@gmail.com)

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://erzumshirazi.dev/github/divider-dark.svg">
  <img alt="" src="https://erzumshirazi.dev/github/divider-light.svg" width="100%">
</picture>

### Now

- **[Print.World](https://print.world)**: the trading engine under the terminal. Real-time market data, caching, and execution in Rust and TypeScript.
- **[BRDG](https://brdg.now)**: a cross-chain bridge aggregator I built. Quotes about 35 bridges across 73 chains and ranks them by what actually arrives. [Docs](https://docs.brdg.now) · [SDK](https://github.com/Kernlog/brdg-sdk)
- **My own book**: a six-figure systematic trading book on crypto perpetual futures, researched, built, and run end to end.

### Selected writing

- **[Taking the lock off the hot path](https://erzumshirazi.dev/writing/taking-the-lock-off-the-hot-path)**: a stress harness, a global lock, and +33% throughput with p99 down from 139ms to 40ms.
- **[ClickHouse or RocksDB?](https://erzumshirazi.dev/writing/clickhouse-or-rocksdb)**: moving trade history off TimescaleDB, and arguing the other side first.
- **[Fix our websocket server, or adopt one?](https://erzumshirazi.dev/writing/build-or-adopt-the-push-layer)**: streaming order books with sequenced deltas and a live escape hatch.
- **[Designing for the retry](https://erzumshirazi.dev/writing/designing-for-the-retry)**: making money paths safe to run twice.
- **[Sixteen months at IBM](https://erzumshirazi.dev/writing/sixteen-months-at-ibm)**: CI/CD for Watson, telemetry, and building Watson Code Review on RabbitMQ and OpenShift.

### Open source

- **[Typhoon](https://github.com/aursen-labs/typhoon)**: merged [#182](https://github.com/aursen-labs/typhoon/pull/182) and [#192](https://github.com/aursen-labs/typhoon/pull/192), inlining account validation and macro-generated code to save 128+ compute units across instructions.
- **[brdg-sdk](https://github.com/Kernlog/brdg-sdk)**: a dependency-free TypeScript client for BRDG, generated from its OpenAPI spec.

### Before this

- **IBM**: CI/CD for Watson services, OpenTelemetry with error-biased tail sampling, and Watson Code Review, an LLM pull-request reviewer that became its own product.
- **Nokia**: C++ on a high-throughput packet-inspection test harness, with AVX2 signature matching.
