# Module 4: Designing Data Processing Systems in Rust

This module focuses on building complete data-processing systems: ingesting, processing, storing, deploying, monitoring, and scaling data workflows and machine-learning services.

## Topics

- Data engineering pipelines and ETL
- Open-source data engineering
- AWS Step Functions and Lambda
- S3 data pipelines and asynchronous processing
- Distroless container images
- Rust microservices on GCP
- AWS architecture patterns for data-driven applications
- Data preparation and feature engineering
- Hugging Face Hub and NLP pipelines
- GPU translation with Rust
- PyTorch, ONNX, and AWS Lambda inference
- Model fine-tuning and transformer models
- SQLite, BigQuery, Colab, and public datasets
- Log analysis and database selection
- Prompt engineering for BigQuery

## Course outline

### Rust data pipelines and ETL

- Key terms
- Data pipelines and open-source data engineering
- Core pipeline components
- Rust AWS Step Functions pipelines
- Async AWS Lambda S3 size calculator
- Distroless containers
- Deploying Rust microservices on GCP
- AWS architectural patterns for end-to-end data-driven applications
- Data preparation and ML feature engineering
- ETL lab
- Lesson reflection and quiz

### Rust and Python for ML pipelines

- Key terms
- Hugging Face Hub
- GPU translation with Rust
- High-performance PyTorch options
- ONNX inference with AWS Lambda and EFS
- Model fine-tuning
- ONNX and transformer-based NLP pipelines
- Hugging Face NLP and fine-tuning resources
- Lesson reflection and quiz

### Databases and data processing systems

- Key terms
- Selecting databases on GCP
- SQLite with a Hugging Face zero-shot classifier
- BigQuery prompt engineering and Colab pipelines
- Exploring BigQuery data
- Public datasets for data science
- Querying log files with BigQuery
- Appropriate database selection
- SQLite and BigQuery
- Designing Data Processing Systems in Rust graded assignment

### Course conclusion

- Course conclusion
- Final week reflection
- Final course quiz
- Next steps
- Rust Sandbox lab
- Share your learning experience

## Suggested project layout

```text
module-4-designing-data-processing-systems-in-rust/
├── README.md
├── data-pipelines/
├── ml-pipelines/
├── databases-and-processing/
└── capstone/
```

Add each exercise or lab as a separate Cargo project beneath the relevant section. Keep generated build output such as `target/` out of version control.

## Verification

From an individual Cargo project, run:

```bash
cargo test
cargo fmt --check
cargo clippy --all-targets --all-features -- -D warnings
```
