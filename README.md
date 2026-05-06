# rust-book

First Rust learning project for working through the Rust book.

The first exercise lives in the `hello_world/` crate.

## Environment

- Rust toolchain managed with `rustup`
- Active toolchain: `stable`
- Verified with:
  - `rustc --version`
  - `cargo --version`

Recommended native tools on CachyOS:

```bash
sudo pacman -S gcc clang rust-analyzer
```

## Build and Run

Build the project:

```bash
cd hello_world
cargo build
```

Run the first program:

```bash
cd hello_world
cargo run
```
