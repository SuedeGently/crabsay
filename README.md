# crabsay #

A Rust implementation of Cowsay, featuring a crustacean instead. Currently
supports text wrapping with custom line lengths (default is 40).

## Usage ##

This codebase can be compiled using `cargo build --release` if you have the Rust
toolchain installed. A release is coming soon.

```
USAGE:
    crabsay [OPTIONS] <text>

FLAGS:
    -h, --help       Prints help information
    -V, --version    Prints version information

OPTIONS:
    -l, --length <length>    line length [default: 40]

ARGS:
    <text>    input string
```
