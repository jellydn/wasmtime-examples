.PHONY: all
all: build dev

.PHONY: format
format:
	cargo fmt

.PHONY: clean
clean:
	cargo clean

.PHONY: build
build:
	cargo build --target wasm32-wasi

.PHONY: dev
dev:
	wasmtime target/wasm32-wasi/debug/hello-world.wasm
