# Welcome to wasmtime-demo 👋

[![Twitter: jellydn](https://img.shields.io/twitter/follow/jellydn.svg?style=social)](https://twitter.com/jellydn)

> Wastime simple demo

## Install

### Install [Rust](https://rustup.rs/)

```sh
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```

### Install [Wasmtime](https://wasmtime.dev/)

```sh
curl https://wasmtime.dev/install.sh -sSf | bash
```

## Usage

```sh
rustup target add wasm32-wasi
rustc hello.rs --target wasm32-wasi
wasmtime hello.wasm
```

### Example 1: Hello world

```sh
cd hello-world
make
```

### Example 2: Markdown parser

```sh
cd markdown-parser
make
```

## Useful references

- Wasmtime Reaches 1.0: Fast, Safe and Production Ready! https://bytecodealliance.org/articles/wasmtime-1-0-fast-safe-and-production-ready
- Wasmtime tutorial https://docs.wasmtime.dev/tutorial.html
- Markdown parser example https://docs.wasmtime.dev/examples-markdown.html

## Author

👤 **Dung Huynh**

- Website: https://productsway.com/
- Twitter: [@jellydn](https://twitter.com/jellydn)
- Github: [@jellydn](https://github.com/jellydn)

## Show your support

Give a ⭐️ if this project helped you!

---

_This README was generated with ❤️ by [readme-md-generator](https://github.com/kefranabg/readme-md-generator)_
