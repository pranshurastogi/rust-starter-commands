# rust-starter-commands

## Installation of Rust

```
$ curl --proto '=https' --tlsv1.2 https://sh.rustup.rs -sSf | sh

```

## Create a project with cargo

```
$ cargo new hello_cargo

```
## TOML file -

```
This file is in the TOML (Tom’s Obvious, Minimal Language) format, which is Cargo’s configuration format.

```
## Building and Running a Cargo Project

```
$ cargo build

It generates a target folder, now to run cargo

$ cargo run
```

## Building for release

```
When your project is finally ready for release, you can use cargo build --release to compile it with optimizations. This command will create an executable in target/release instead of target/debug. The optimizations make your Rust code run faster, but turning them on lengthens the time it takes for your program to compile. This is why there are two different profiles: one for development, when you want to rebuild quickly and often, and another for building the final program you’ll give to a user that won’t be rebuilt repeatedly and that will run as fast as possible. If you’re benchmarking your code’s running time, be sure to run cargo build --release and benchmark with the executable in target/release.

```

## Recap :
```
1. We can build a project using cargo build.
2. We can build and run a project in one step using cargo run.
3. We can build a project without producing a binary to check for errors using cargo check.
I4. nstead of saving the result of the build in the same directory as our code, Cargo stores it in the target/debug directory.
```
