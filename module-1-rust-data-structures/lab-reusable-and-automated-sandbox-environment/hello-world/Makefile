.PHONY: all format lint test build check clean

all: format lint test build

format:
	cargo fmt --all

lint:
	cargo clippy --all-targets --all-features -- -D warnings

test:
	cargo test

build:
	cargo build

check: all

clean:
	cargo clean
