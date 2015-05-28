# Rust bindings to *nix APIs

Rust friendly bindings to various *nix platform APIs (Linux, Darwin,
...). The goal is to not provide a 100% unified interface, but to unify
what can be while still providing platform specific APIs.

[![Build Status](https://travis-ci.org/carllerche/nix-rust.svg?branch=master)](https://travis-ci.org/carllerche/nix-rust)
[![crates.io](http://meritbadge.herokuapp.com/nix)](https://crates.io/crates/nix)

## Documentation

API documentation generated by rustdoc:

- Linux: [master](http://rustdoc.s3-website-us-east-1.amazonaws.com/nix/master/linux/nix/)
- OS X: [master](http://rustdoc.s3-website-us-east-1.amazonaws.com/nix/master/osx/nix/)

## Usage

To use `nix`, first add this to your `Cargo.toml`:

```toml
[dependencies]
nix = "*"
```

Then, add this to your crate root:

```rust
extern crate nix;
```
