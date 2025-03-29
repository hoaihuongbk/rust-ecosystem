# Awesome Rust Data Engineering Ecosystem

A curated list of awesome tools and libraries written in Rust for data engineering.

## Table of Contents

- [ETL Tools](#etl-tools)
- [Data Processing](#data-processing)
- [Data Storage](#data-storage)
- [Streaming](#streaming)
- [Query Engines](#query-engines)
- [Databases](#databases)
- [Visualization](#visualization)
- [CLI Tools](#cli-tools)
- [Vector Database](#vector-database)
- [Time Series](#time-series)
- [OLAP Systems](#olap-systems)
- [Web Frameworks](#web-frameworks)
- [Miscellaneous](#miscellaneous)
- [References](#references)

## ETL Tools

- [Delta Lake Rust](https://github.com/delta-io/delta-rs) - Native Rust implementation of Delta Lake, a storage layer for data lakes.
- [Iceberg Rust](https://github.com/apache/iceberg-rs) - Rust implementation of Apache Iceberg.

## Data Processing

- [Arrow Rust](https://github.com/apache/arrow-rs) - Official Rust implementation of Apache Arrow.
- [Polars](https://github.com/pola-rs/polars) - Fast DataFrame library for Rust and Python.
- [Daft](https://github.com/Eventual-Inc/Daft) - Similar to Polars, another fast DataFrame library for Rust and Python.


## Data Storage

- [Sled](https://github.com/spacejam/sled) - A modern embedded database.

- [Garage](https://github.com/deuxfleurs-org/garage) - S3-compatible distributed object storage service designed for self-hosting at a small-to-medium scale.

## Streaming

- [Fluvio](https://github.com/infinyon/fluvio) - Distributed streaming platform built in Rust.
- [Arroyo](https://github.com/ArroyoSystems/arroyo) - High-performance real-time analytics in Rust and SQL.
- [RisingWaveLabs/RisingWave](https://github.com/risingwavelabs/risingwave) - The next-generation streaming database in the cloud.

## Query Engines

- [DataFusion](https://github.com/apache/datafusion) - DataFusion is a very fast, extensible query engine for building high-quality data-centric systems in Rust, using the Apache Arrow in-memory format.


## Databases

- [Databend](https://github.com/datafuselabs/databend) - A Modern Real-Time Data Processing & Analytics DBMS with Cloud-Native Architecture.
- [GreptimeDB](https://github.com/GreptimeTeam/greptimedb) - An open-source, cloud-native, distributed time-series database with PromQL/SQL/Python supported.
- [Lucid](https://github.com/lucid-kv/lucid) - High performance and distributed KV store accessible through a HTTP API.
- [Skytable](https://github.com/skytable/skytable) - A multi-model NoSQL database.
- [SurrealDB](https://github.com/surrealdb/surrealdb) - A scalable, distributed, document-graph database.
- [TiKV](https://github.com/tikv/tikv) - A distributed KV database in Rust.
- [DB3 Network](https://github.com/dbpunk-labs/db3) - DB3 is a community-driven blockchain layer2 decentralized database network.

## Visualization

- [Plotters](https://github.com/plotters-rs/plotters) - A drawing library for creating data visualizations in pure Rust.
- [rerun](https://github.com/rerun-io/rerun) - An SDK for logging computer vision and robotics data (tensors, point clouds, etc) paired with a visualizer for exploring that data over time.
- [plotly](https://github.com/plotly/plotly.rs) - Plotly for Rust.
- [plotpy](https://github.com/igiagkiozis/plotpy) - Rust plotting library using Python (Matplotlib).
- [milliams/plotlib](https://github.com/milliams/plotlib) - Data plotting library for Rust.


## CLI Tools

- [xsv](https://github.com/BurntSushi/xsv) - A fast CSV command line toolkit.
- [rq](https://github.com/dflemstr/rq) - Record Query - A tool for doing record analysis and transformation.
- [dathere/qsv](https://github.com/dathere/qsv) - A high performance CSV data-wrangling toolkit. Forked from xsv, with 34+ additional commands & more.
- [sstadick/hck](https://github.com/sstadick/hck) - A faster and more featureful drop in replacement for `cut`.
- [crabz](https://github.com/sstadick/crabz) - Multi-threaded compression and decompression CLI tool.

## Vector Database

- [Qdrant](https://github.com/qdrant/qdrant) - An open source vector similarity search engine with extended filtering support.
- [lancedb](https://github.com/lancedb/lance) - Modern columnar data format for ML.
- [USearch](https://github.com/unum-cloud/usearch) - Similarity Search Engine for Vectors and Strings.


## Time Series

- [GreptimeDB](https://github.com/GreptimeTeam/greptimedb) - An open-source, cloud-native, distributed time-series database with PromQL/SQL/Python supported.

## OLAP Systems

- [RisingLight](https://github.com/risinglightdb/risinglight) - RisingLight is an OLAP database system for educational purpose.

## Web Frameworks

- [Rust10x Web App](https://github.com/rust10x/rust10x-web-app) - Rust10x Web App.


## Miscellaneous

- [RobustMQ](https://github.com/robustmq/robustmq) - Next generation cloud-native converged message queue.
- [Rocketmq-Rust](https://github.com/mxsm/rocketmq-rust) - 🚀Apache RocketMQ build in Rust🦀. Faster, safer, and with lower memory usage.
- [OpenObserve](https://github.com/openobserve/openobserve) - 10x easier, 140x lower storage cost, high performance, petabyte scale - Elasticsearch/Splunk/Datadog alternative.
- [Quickwit](https://github.com/quickwit-oss/quickwit) - Cloud-native and highly cost-efficient search engine for log management.
- [Vector](https://github.com/vectordotdev/vector) - A High-Performance, Logs, Metrics, & Events Router.
- [Indexify](https://github.com/tensorlakeai/indexify) - Data & learning flywheel for LLMs that unifies inference, observability, optimization, and experimentation.

## References

This curated list is derived from the [awesome-rust](https://github.com/rust-unofficial/awesome-rust) repository, focusing specifically on tools and libraries that are most relevant to the data engineering ecosystem. The original awesome-rust repository contains a comprehensive collection of Rust resources across many domains, while this list highlights those particularly useful for data engineering workflows, data processing, storage, and analysis.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This repository is licensed under [MIT License](LICENSE).