# Module 2: Safety, Security and Concurrency with Rust

This module explores Rust's safety, security, and concurrency capabilities, including encryption, network segmentation, thread safety, distributed computing, and web crawling.

## Topics

- Security principles: multi-factor authentication, network segmentation, least privilege, encryption, high availability, incident response, and compliance
- Rust ownership, lifetimes, safe and unsafe code, and ownership-based resource management
- Mutable data and data races
- Cryptography with Caesar and homophonic ciphers
- Decoder rings and SHA-3 duplicate detection
- RustCrypto hashes and software security
- Concurrency and parallelism
- Dining Philosophers
- `Send`, `Sync`, atomics, and race conditions
- Web crawling with Rayon
- Asynchronous applications with Tokio
- Multi-threaded deduplication
- Distributed computing, energy efficiency, and serverless optimization

## Course outline

### Rust safety and security features

- Key terms
- Multi-factor authentication, network segmentation, least privilege access, and encryption
- Mutable fruit salad and CLI customization
- Data race examples and labs
- Safe and unsafe Rust
- Ownership and lifetimes
- The perils of ownership-based resource management (OBRM)
- Lesson reflection and quiz: Rust Safety and Security Features

### Security programming with Rust

- Key terms
- High availability, incident response, and compliance
- Homophonic and Caesar ciphers
- Creating a decoder ring
- Detecting duplicates with SHA-3
- RustCrypto hashes
- Rust software security
- External decoder-ring lab
- Lesson reflection and quiz: Security Programming with Rust

### Concurrency and parallelism

- Key terms and core concepts in concurrency
- Dining Philosophers
- Web crawling Wikipedia with Rayon
- Intelligent chatbots with Tokio
- Multi-threaded deduplication
- Energy efficiency: Python versus Rust
- GPU concurrency stress testing
- Host-efficiency and serverless optimization
- Data races, race conditions, `Send`, `Sync`, and atomics
- Distributed computing and concurrency
- Challenges and opportunities in distributed systems
- Dining Philosophers lab
- Rust Playground Rayon Challenge

### Assessment and reflection

- Final week reflection
- Safety, Security and Concurrency with Rust graded assignment
- Lesson reflection
- Quiz: Rust Concurrency

## Suggested project layout

```text
module-2/
├── README.md
├── safety-and-security/
├── cryptography/
├── concurrency/
└── projects/
```

Add each exercise or lab as a separate Cargo project beneath the relevant section. Keep generated build output such as `target/` out of version control.

## Verification

From an individual Cargo project, run:

```bash
cargo test
cargo fmt --check
cargo clippy --all-targets --all-features -- -D warnings
```
