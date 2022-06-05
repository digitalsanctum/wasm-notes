# wasm-notes
Personal notes on the WebAssembly ecosystem

## AssemblyScript

A TypeScript-like language for WebAssembly.

https://www.assemblyscript.org/

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


## Organizations and projects using WASM

* [bytecodealliance](https://bytecodealliance.org/) - a nonprofit organization dedicated to creating secure new software foundations, building on standards such as WebAssembly and WebAssembly System Interface (WASI).
* [deislabs](https://github.com/deislabs) - 
* [Envoy](https://thenewstack.io/wasm-modules-and-envoy-extensibility-explained-part-1/)
* ethereum
* [Fermyon](https://www.fermyon.com/) -  building open source, WebAssembly-powered cloud tools, with the aim of simplifying and unlocking new technologies for all.
* [Figma](https://www.figma.com/)
* [Lapse](https://github.com/lapce/lapce)
* [Open Policy Agent](https://www.openpolicyagent.org/docs/latest/wasm/)
* [RedPanda](https://redpanda.com/blog/wasm-architecture/)
* [Scylla](https://www.scylladb.com/)
* [Shopify](https://www.shopify.com/)
* [SingleStore](https://www.singlestore.com/)