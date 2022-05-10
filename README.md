# How to reproduce

```console
$ cargo +nightly build -Z bindeps
thread 'main' panicked at 'no entry found for key', src/tools/cargo/src/cargo/core/compiler/build_context/target_info.rs:875:40
note: run with `RUST_BACKTRACE=1` environment variable to display a backtrace
```