# wasm-notes
Personal notes on the WebAssembly ecosystem

WebAssembly's unique value proposition:

* Language neutrality: avoid biasing the component model toward just one language or family of languages.
* Embeddability: design components to be embedded in a diverse set of host execution environments, including browsers, servers, intermediaries, small devices and data-intensive systems.
* Optimizability: maximize the static information available to Ahead-of-Time compilers to minimize the cost of instantiation and startup.
* Formal semantics: define the component model within the same semantic framework as core wasm.
* Web platform integration: ensure components can be natively supported in browsers by extending the existing WebAssembly integration points: the JS API, Web API and ESM-integration. Before native support is implemented, ensure components can be polyfilled in browsers via Ahead-of-Time compilation to currently-supported browser functionality.

## wasmer

https://wasmer.io/

> Wasmer is a fast and secure WebAssembly runtime that enables super lightweight containers to run anywhere: from Desktop to the Cloud, Edge and IoT devices.

## wasmi

https://github.com/paritytech/wasmi

wasmi was conceived as a component of parity-ethereum (ethereum-like contracts in wasm) and substrate. These projects are related to blockchain and require a high degree of correctness. The project is not trying to be be involved in any implementation of any of work-in-progress Wasm proposals. Instead the project tries to be as close as possible to the specification, therefore avoiding features that are not directly supported by the specification.

With all that said wasmi should be a good option for initial prototyping and there shouldn't be a problem migrating from wasmi to another specification compliant execution engine later on.


## AssemblyScript

A TypeScript-like language for WebAssembly.

https://www.assemblyscript.org/


## wit-bindgen

https://github.com/bytecodealliance/wit-bindgen

A language binding generator for WebAssembly interface types 


## spin

https://github.com/fermyon/spin

An open source framework for building and running fast, secure, and composable cloud microservices with WebAssembly.

## component-model

https://github.com/WebAssembly/component-model

Repository for design and specification of the Component Model.

## proxy-wasm-rust-sdk
https://github.com/proxy-wasm/proxy-wasm-rust-sdk

WebAssembly for Proxies (Rust SDK) 


## wasmtime
* https://github.com/bytecodealliance/wasmtime
* https://wasmtime.dev/

A small and efficient runtime for WebAssembly & WASI.

[Using WebAssembly from Rust](https://docs.wasmtime.dev/lang-rust.html)

## wasm-tools

Low level tooling for WebAssembly in Rust. 

https://github.com/bytecodealliance/wasm-tools


## wasi

https://github.com/WebAssembly/WASI

The WebAssembly System Interface is not a monolithic standard system interface, but is instead a modular collection of standardized APIs. None of the APIs are required to be implemented to have a compliant runtime. Instead, host environments can choose which APIs make sense for their use cases.

## wagi

https://github.com/deislabs/wagi

Write HTTP handlers in WebAssembly with a minimal amount of work.

## wasi-data

https://github.com/singlestore-labs/wasi-data

The goal of this proposal is to define a mechanism for programs compiled to Wasm to represent and drive distributed algorithms, taking advantage of distributed storage and computation systems.

Apache Spark is one such example. The main abstraction Spark provides is a resilient distributed dataset (RDD), which is a fault-tolerant collection of elements that can be operated on in parallel.

## wasi-nn

https://github.com/WebAssembly/wasi-nn

Neural Network proposal for WASI.

## wasi-parallel

https://github.com/WebAssembly/wasi-parallel

wasi-parallel is a proposal to add a parallel for construct to WASI. It includes:
* an explainer, diving into the rationale for this specification
* the proposed API in WITX form

## proxy-wasm/spec

https://github.com/proxy-wasm/spec

WebAssembly for Proxies (ABI specification) 

## wazero

https://github.com/tetratelabs/wazero

wazero is a WebAssembly 1.0 spec compliant runtime written in Go. It has zero dependencies, and doesn't rely on CGO. This means you can run applications in other languages and still keep cross compilation.

Import wazero and extend your Go application with code written in any language!


## mbasso/awesome-wasm

https://github.com/mbasso/awesome-wasm

Curated list of awesome things regarding WebAssembly (wasm) ecosystem. 

## appcypher/awesome-wasm-langs

https://github.com/appcypher/awesome-wasm-langs

A curated list of languages that compile directly to or have their VMs in WebAssembly 


## byrneml/wasm-resources

https://github.com/byrneml/wasm-resources

Another curated list of wasm resources.

## wasmedge

https://wasmedge.org/

https://wasmedge.org/book/en/dev/rust.html

WasmEdge is a lightweight, high-performance, and extensible WebAssembly runtime for cloud native, edge, and decentralized applications. It powers serverless apps, embedded functions, microservices, smart contracts, and IoT devices. 

## Organizations and projects using WASM

* [bytecodealliance](https://bytecodealliance.org/) - a nonprofit organization dedicated to creating secure new software foundations, building on standards such as WebAssembly and WebAssembly System Interface (WASI).
* [deislabs](https://github.com/deislabs) - 
* [Envoy](https://thenewstack.io/wasm-modules-and-envoy-extensibility-explained-part-1/)
* ethereum
* [Fermyon](https://www.fermyon.com/) -  building open source, WebAssembly-powered cloud tools, with the aim of simplifying and unlocking new technologies for all.
* [ferrous systems](https://ferrous-systems.com/)
* [Figma](https://www.figma.com/)
* [Lapse](https://github.com/lapce/lapce)
* [mozilla](https://www.mozilla.org/en-US/)
* [Open Policy Agent](https://www.openpolicyagent.org/docs/latest/wasm/)
* [RedPanda](https://redpanda.com/blog/wasm-architecture/)
* [Scylla](https://www.scylladb.com/)
* [SecondState](https://www.secondstate.io/)
* [Shopify](https://www.shopify.com/)
* [SingleStore](https://www.singlestore.com/)
* [Tetrate](https://www.tetrate.io/)
