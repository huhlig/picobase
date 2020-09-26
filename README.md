# Picobase Embedable Multi-Paradigm Database Library

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)
[![Build Status](https://travis-ci.org/huhlig/picobase.svg?branch=master)](https://travis-ci.org/huhlig/picobase)
[![Coverage Status](https://coveralls.io/repos/github/huhlig/picobase/badge.svg?branch=master)](https://coveralls.io/github/huhlig/picobase?branch=master)

([API Docs])

> Picobase is an Embedded Multi-Paradigm Database Library written in Rust. 

## Project Structure

* `doc` - Project Documentation
* `src/client` - Client Libraries.
* `src/client/rust` - Rust Client Library.
* `src/engine/` - Database engine components.
* `src/engine/kernel/` - Common Components of the database system. Most crates depend on it.
* `src/engine/service/` - Database Engine Service. This is what you embed.
* `src/network/` - Network Components used by Picobase.
* `src/network/protocol/` - Network Protocol used by Picobase.
* `src/sailvm/` - Statistics & Artificial Intelligence Language Virtual Machine.
* `src/server/` - Picobase Server Node.
* `src/storage/` - Data Storage Engines
* `src/storage/btree/` - Picobase BTree Implementation.
* `src/storage/vfs/` - Virtual File System used to abstract underlying storage medium.
* `src/utility/` - Helper Utilities used by Picobase.
* `src/utility/uri` - Uniform Resource Identifier Library
* `src/utility/uuid` - Universally Unique Identifier Library


## Features

Not yet Implemented:
* Multiple Table Types
** Relational
** Key/Value
** Document
** Graph
** Ledger
* Directly Accessable Virtual Machine
** Executes Queries & Data Science Algorithms
* Built In Network Clustering
** Mirroring
*** Leader/Mirror
*** Leader/Leader
** Sharding
*** Peer Elections
* Embeddable

## License

This project is licensed under [Apache License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0).

### Contribution

Unless you explicitly state otherwise, any contribution intentionally submitted for inclusion in the work by you, as 
defined in the Apache-2.0 license, shall be licensed as above, without any additional terms or conditions.

[API Docs]: https://huhlig.github.io/microsql/