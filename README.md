# Marketplace Matcher Smart Contract

## Cargo Contract setup

Note: Cargo contract 0.15.0 or newer is required

1. Install Rust toolchain 2021-10-20:

```
rustup toolchain install nightly-2021-10-20
rustup component add rust-src --toolchain nightly-2021-10-20
```

2. Install Binaryen 101 from https://github.com/WebAssembly/binaryen/releases

3. Install cargo contract

```
cargo install --force cargo-contract
```

## Building

```
cargo +nightly-2020-03-01 contract build
```
