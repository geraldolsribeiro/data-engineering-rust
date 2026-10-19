# Module 1: Rust Data Structures — Collections

This module introduces the Rust development ecosystem and the standard library collections used in data engineering. It also covers AI-assisted development, cloud-based environments, continuous integration, and graph-oriented algorithms.

## Topics

- Rust setup, Cargo, VS Code, GitHub Codespaces, and GitHub Actions
- AI coding tools and prompt engineering for data workflows
- Sequences: `Vec`, `VecDeque`, and `LinkedList`
- Maps: `HashMap` and frequency counting
- Sets: `HashSet` and `BTreeSet`
- Priority queues with `BinaryHeap`
- Iterators and collection-oriented Rust code
- Graph algorithms: PageRank, Dijkstra's shortest path, centrality, and Kosaraju's strongly connected components
- Simple data-structure visualization and charting

## Course outline

### Getting started with the modern Rust development ecosystem

- Meet the instructor and course overview
- Prerequisites and getting started
- Key terms
- AI coding tools and the changing software-development workflow
- Cloud-based development environments
- GitHub Copilot for Rust
- Prompt engineering with GCP BigQuery SQL
- Google Bard and Amazon Q Developer
- Continuous integration with Rust and GitHub Actions
- VS Code, Copilot, and Codespaces for developers transitioning from Python
- Generative AI for software development
- Rust in MLOps
- Data Engineering with Rust Sandbox
- Lesson reflection and introductory quiz

### Rust sequences and maps

- Introducing Rust sequences and maps
- Printing and comparing Rust data structures
- Fruit salad implementations using `Vec`, `VecDeque`, and `LinkedList`
- A command-line fruit salad creator
- Frequency counting with `HashMap`
- Comparing and weighting programming languages with `HashMap`
- Rust collections documentation and iterators
- Exploration labs and lesson reflection
- Quiz: Rust Sequences and Maps

### Sets, heaps, and graphs

- Unique fruits with `HashSet`
- Sorted, unique fruits with `BTreeSet`
- Priority fruit salad with `BinaryHeap`
- UFC fighter network analysis and graph centrality
- PageRank and shortest-path algorithms
- Strongly connected components with Kosaraju's algorithm
- Simple charting and graph visualization
- Lesson reflection and collections assessment

### Final challenge

- Final week reflection
- Collections Week Challenge

## Suggested project layout

```text
module-1-rust-data-structures/
├── README.md
├── getting-started/
├── sequences-and-maps/
├── sets-heaps-and-graphs/
└── collections-challenge/
```

Add each exercise or lab as a separate Cargo project beneath the relevant section. Keep generated build output such as `target/` out of version control.

## Verification

From an individual Cargo project, run:

```bash
cargo test
cargo fmt --check
cargo clippy --all-targets --all-features -- -D warnings
```
