
<p align="center">
  <img align="center" src="https://raw.githubusercontent.com/rust-lang/crates.io/master/public/cargo.png"/>
</p>
<h1 align="center">Async.await! Crates</h1>
<p align="center">List of async-await compatible crates for the <a href="https://www.rust-lang.org/">Rust programming language</a>.</p>


### HTTP
- [hyper](https://docs.rs/hyper/latest) - "hyper is a fast and correct HTTP implementation written in and for Rust."

### HTTP Clients
- [reqwest](https://docs.rs/reqwest/latest) on the `master` branch - "The reqwest crate provides a convenient, higher-level HTTP Client."
- [surf](https://docs.rs/surf/latest) - "Surf is a friendly HTTP client built for casual Rustaceans and veterans alike."

### HTTP Servers
- [rocket](https://docs.rs/rocket/latest/) on the `async` branch - "Rocket is a web framework for Rust that makes it simple to write fast, secure web applications without sacrificing flexibility, usability, or type safety."
- [tide](https://docs.rs/tide/latest/) - "Empowering everyone to build HTTP Services."

## gRPC

- [tonic](https://docs.rs/tonic/) - "A rust implementation of gRPC, a high performance, open source, general RPC framework that puts mobile and HTTP/2 first."

## Tracing

- [tracing](https://docs.rs/tracing/latest/) - "A scoped, structured logging and diagnostics system."

## Databases

### Redis
- [darkredis](https://docs.rs/darkredis/latest) - "Asynchronous redis client built using futures and async await, with optional connection pooling."

### MySQL
- [mysql_async](https://docs.rs/mysql_async/latest) - "Tokio based asynchronous MySql client library for rust programming language."

### Postgres
- [tokio-postgres](https://docs.rs/tokio-postgres/latest) on the `std-future` branch - "An asynchronous Postgres driver using Tokio."

### MemDB
- [memdb](https://docs.rs/memdb/latest) - "Thread-safe in-memory key-value store. Ideal for development and prototyping. Does not persist to disk."

## Runtimes, sockets, filesystem, timers, etc.

- [tokio](https://docs.rs/tokio/latest) - "A runtime for writing reliable, asynchronous, and slim applications."
- [async-std](https://docs.rs/async-std/latest) - "Async version of the Rust standard library."

## TLS

- [tokio-tls](https://docs.rs/tokio-tls/latest) - "Async TLS streams"
- [tokio-rustls](https://docs.rs/tokio_rustls/latest) - "Asynchronous TLS/SSL streams for Tokio using Rustls."
- [tokio-openssl](https://docs.rs/tokio-openssl/latest) - "An implementation of SSL streams for Tokio built on top of the openssl crate"

## Utility

- [async_trait](https://docs.rs/async-trait/latest) - "Type erasure for async trait methods"
- [async-stream](https://docs.rs/async-stream/latest) - "Provides two macros, stream! and try_stream!, allowing the caller to define asynchronous streams of elements"
- [stream-cancel](https://docs.rs/stream-cancel/latest) - "This crate provides multiple mechanisms for interrupting a Stream."
- [futures-batch](https://github.com/mre/futures-batch) - " An adapter for futures, which chunks up elements and flushes them after a timeout, or when the buffer is full"
- [futures-timer](https://docs.rs/futures-timer/latest/) - "A library for working with timers, timeouts, and intervals with the futures crate."

## Futures/Streams/Sinks extension traits and more!

- [futures](https://rust-lang-nursery.github.io/futures-api-docs/0.3.0-alpha.18/futures/) - "Abstractions for asynchronous programming."

## Compression

- [async-compression](https://docs.rs/async-compression/latest) - "Adaptors between compression crates and Rust's modern asynchronous IO types."

## Wire-Formats

- [async-bincode](https://docs.rs/async-bincode/latest) - "Asynchronous access to a bincode-encoded item stream."

## Message Queues

### NATS

- [rants](https://docs.rs/crate/rants/latest) - "An async NATS client library for the Rust programming language."

## WebAssembly

- [wasm-bindgen-futures](https://rustwasm.github.io/wasm-bindgen/api/wasm_bindgen_futures/) on the `master` branch - "This crate bridges the gap between a Rust Future and a JavaScript Promise."

## Services

### Amazon

- [rusoto](https://github.com/rusoto/rusoto) - "Rusoto is an AWS SDK for Rust."
