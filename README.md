# grpc-rust-with-tokio

A Rust binary test on using [`grpc`](https://github.com/stepancheg/grpc-rust) in the Tokio runtime.

This is due to Bazel's **rules_proto** currently using the `grpc` crate instead of `prost` / `tonic`.

This test is done while we are waiting on the [awesome works](https://github.com/rules-proto-grpc/rules_proto_grpc/pull/202) from [Jonathan "titanous" Rudenberg](https://github.com/titanous).
