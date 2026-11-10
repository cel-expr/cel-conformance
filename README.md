# Common Expression Language — Conformance Tests

This repository contains the language-agnostic conformance test suites and
protobuf schemas for the [Common Expression Language (CEL)](https://cel.dev).

## Directory Structure

* [`proto/cel/expr/conformance/`](proto/cel/expr/conformance): Protobuf schemas
  for conformance test definitions (`simple.proto`, `suite.proto`) and proto2 /
  proto3 test message types (`test_all_types.proto`).
* [`tests/simple/testdata/`](tests/simple/testdata): Standard textproto
  conformance test suites covering core CEL semantics and standard extensions.

## License

Licensed under the [Apache License, Version 2.0](LICENSE).
