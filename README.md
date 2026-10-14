# Introduction

This project builds [libfvad](https://github.com/dpirch/libfvad), the WebRTC Voice Activity Detection module, and provides a safe Rust API.
A C compiler must be installed. [cc-rs](https://github.com/alexcrichton/cc-rs) is used to invoke the build command.

See the `libfvad` license [here](https://github.com/dpirch/libfvad/blob/532ab666c20d3cfda38bca63abbb0f152706c369/LICENSE).

## Development

If you are building this crate from a local clone, please initialize or update the submodule first.

```shell
git submodule update --init
cargo build
```
