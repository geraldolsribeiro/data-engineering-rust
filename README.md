# Data Engineering with Rust

Projects and notes developed while completing the [Data Engineering with Rust](https://www.coursera.org/learn/data-engineering-rust/) course on Coursera.

## Repository structure

- [`module-1-rust-data-structures/`](module-1-rust-data-structures/) — Rust development ecosystem and collections
- [`module-2-safety-security-and-concurrency-with-rust/`](module-2-safety-security-and-concurrency-with-rust/) — Safety, security, and concurrency with Rust
- [`module-3-rust-data-engineering-libraries-and-tools/`](module-3-rust-data-engineering-libraries-and-tools/) — Rust data engineering libraries and tools
- [`module-4-designing-data-processing-systems-in-rust/`](module-4-designing-data-processing-systems-in-rust/) — Designing data processing systems in Rust

Each module keeps its exercises, labs, projects, and supporting documentation together. Individual projects should include their own README with a description, prerequisites, and instructions for running or testing the code.

## Prerequisites

- Rust stable toolchain (`rustup`, `cargo`)
- Git
- A GitHub account (some activities use Codespaces and GitHub Actions)

Install Rust from [rustup.rs](https://rustup.rs/), then verify the installation:

```bash
rustc --version
cargo --version
```

## Working with a project

Change into a project directory and use Cargo as usual:

```bash
cargo run
cargo test
cargo fmt --check
cargo clippy --all-targets --all-features -- -D warnings
```

Course content and assessment materials belong to Coursera and their respective authors. This repository contains my implementations, notes, and project work.
