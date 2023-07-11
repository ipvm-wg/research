# IPVM Research

A short list of relevant research related to [IPVM][ipvm-wg] and the [Homestar][homestar]
implementation of IPVM. It is in no way exhaustive.

##

## Distributed Orchestration and Compute Engines

* [Escaping the Singularity: Side Effects, Front and Center!][side-effects]
* [Parallel Programming Must Be Deterministic by Default][pp-default]

### Composition & Concurrency Control

* [Robust Composition: Towards a Unified Approach to Access Control and Concurrency Control][robust-comp]

### Coordination and Transformation

* [Ignis: Scaling Distribution-Oblivious Systems with Light-Touch Distribution][ignis]

### Decentralized Applications

* [A Programming Paradigm for Reliable Applications in a Decentralized Setting][mogk-thesis]

### Durable Executions & Virtual Resiliency & Fault-oblivious Workflows

* [A.M.B.R.O.S.I.A: Providing Performant Virtual Resiliency for Distributed Applications][ambrosia]
* [Durable Functions: Semantics for Stateful Serverless][durable-fns]
* [Netherite: Efficient Execution of Serverless Workflows][netherite]
* [SEQUEL: A STRUCIURED ~NGLISH QUERY LANGUAGE][sequel]

### Scheduling

* [A Taxonomy of Job Scheduling on Distributed Computing Systems][taxonomy]

## Serverless Computing & Performance

* [On-demand Container Loading in AWS Lambda][aws-lambda]
* [Serverless Computing: One Step Forward, Two Steps Back][1-step]

## Wasm

### Background and Studies

* [A Comprehensive Study of WebAssembly Runtime Bugs][wasm-study]
* [Bringing the Web up to Speed with WebAssembly][wasm-bringing-up]
* [Characterization and Implication of Edge WebAssembly Runtimes][wasm-runtimes]

### Compilers, JITs, & Execution Models

* [Bringing WebAssembly Up to Speed with Dynamic Linking][wasm-dyn]
* [Whose baseline (compiler) is it anyway?][wasm-baseline]

### Component Model & Wasm Interface Types (WIT)

* [Component Model design and specification][wasm-component]
* [The wit format][wit]

### Zero-knowledge proofs

* [ZAWA: A ZKSNARK WASM Emulator][zawa]

## Peer-to-Peer Networking & Content-Addressable Storage

* [Design and Evaluation of IPFS: A Storage Layer for the Decentralized Web][ipfs]
* [GossipSub: Attack-Resilient Message Propagation in the Filecoin and ETH2.0 Networks][gossipsub]
* [IPFS-FAN: A Function-Addressable Computation Network][ipfs-fan]

## Trust Models

### Distributed Capability Systems & Auth

* [Capability Myths Demolished][caps-demolished]
* [CapTP: The Capability Transport Protocol][captp]
* [Ucan Spec][ucan-spec]

### Privacy-preserving Protocols

* [DECO: Liberating Web Data Using Decentralized Oracles for TLS][deco]


[1-step]: https://arxiv.org/pdf/1812.03651.pdf
[ambrosia]: https://www.microsoft.com/en-us/research/uploads/prod/2018/12/AmbrosiaPaper.pdf
[aws-lambda]: https://arxiv.org/pdf/2305.13162.pdf
[caps-demolished]: https://srl.cs.jhu.edu/pubs/SRL2003-02.pdf
[captp]: http://erights.org/elib/distrib/captp/index.html
[deco]: https://arxiv.org/pdf/1909.00938.pdf
[durable-fns]: https://angelhof.github.io/files/papers/durable-functions-2021-oopsla.pdf
[gossipsub]: https://arxiv.org/pdf/2007.02754.pdf
[ipfs]: https://arxiv.org/pdf/2208.05877.pdf
[ipfs-fan]: https://research.protocol.ai/publications/ipfs-fan-a-function-addressable-computation-network/delarocha2021a.pdf
[homestar]: https://github.com/ipvm-wg/homestar/
[ignis]: https://nikos.vasilak.is/p/ignis:pldi:2019.pdf
[ipvm-wg]: https://github.com/ipvm-wg
[mogk-thesis]: https://tuprints.ulb.tu-darmstadt.de/19403/1/mogk-dissertation.pdf
[netherite]: https://www.vldb.org/pvldb/vol15/p1591-burckhardt.pdf
[pp-default]: https://www.usenix.org/legacy/event/hotpar09/tech/full_papers/bocchino/bocchino.pdf
[robust-comp]: http://www.erights.org/talks/thesis/markm-thesis.pdf
[sequel]: https://s3.us.cloud-object-storage.appdomain.cloud/res-files/2705-sequel-1974.pdf
[side-effects]: https://queue.acm.org/detail.cfm?id=3099561
[taxonomy]: https://ieeexplore.ieee.org/document/7425222
[ucan-spec]: https://github.com/ucan-wg/spec
[wasm-baseline]: https://arxiv.org/pdf/2305.13241.pdf
[wasm-bringing-up]: https://github.com/WebAssembly/spec/blob/master/papers/pldi2017.pdf
[wasm-component]: https://github.com/WebAssembly/component-model
[wasm-dyn]: https://helda.helsinki.fi/server/api/core/bitstreams/f535af54-70a8-4b35-a0aa-927543d4601c/content
[wasm-runtimes]: https://par.nsf.gov/servlets/purl/10337553
[wasm-study]: https://ieeexplore.ieee.org/document/10123536
[wit]: https://github.com/WebAssembly/component-model/blob/main/design/mvp/WIT.md
[zawa]: https://jhc.sjtu.edu.cn/~hongfeifu/manuscriptb.pdf
