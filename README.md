# eventio

eventio is a collection of event I/O processors for event-processing
applications. It allows to collect events from various sources, distribute them
to one or more event processors, and optionally collect the processing results
to send them to storage or other event processors.

[![crates.io](https://img.shields.io/crates/v/eventio)](https://crates.io/crates/eventio)
[![Documentation](https://docs.rs/eventio/badge.svg)](https://docs.rs/eventio)
[![Coverage Status](https://codecov.io/gh/petabi/eventio/branch/master/graphs/badge.svg)](https://codecov.io/gh/petabi/eventio)

## Requirements

* Rust ≥ 1.37
* OpenSSL ≥ 1.0.1 or LibreSSL ≥ 2.5
