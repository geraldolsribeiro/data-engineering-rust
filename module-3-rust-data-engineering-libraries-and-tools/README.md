# Module 3: Rust Data Engineering Libraries and Tools

This module explores data processing in Rust, including data files, cloud storage, notebooks, DataFrames, APIs, containers, and web services.

## Topics

- CSV processing and writing CSV files
- Cargo Lambda and serverless Rust
- AWS EFS and S3 storage
- Encrypted data in tables and Parquet files
- Rust CSV and Apache Parquet libraries
- Google Colab and Rust in Jupyter notebooks
- Python Pandas and notebook workflows
- DataFrames with Polars
- Sensitive data and notebook development
- MLflow and Databricks
- GCP Cloud Shell, AWS CloudShell, and Cloud9
- Prototyping AI APIs
- Deploying Rust applications with GCP App Engine
- Containerized Actix microservices on AWS
- Axum microservices
- AWS SDK for Rust, virtualization, and containers

## Course outline

### Managing data, files, and network storage

- Key terms
- Processing and writing CSV files
- Cargo Lambda
- Listing files on AWS EFS
- Using AWS S3 from Rust
- Writing encrypted data to tables or Parquet files
- Rust CSV Cookbook
- Apache Parquet's native Rust implementation
- Lesson reflection and quiz

### DataFrames with Rust, Python, and notebooks

- Key terms
- Google Colab and Rust in Jupyter Notebook
- Python Pandas and Jupyter
- Notebook development with generative AI
- Life expectancy exploration
- Loading sensitive data into a DataFrame
- MLflow and Databricks notebooks
- End-to-end ML with MLflow and Databricks
- Global life expectancy with Polars
- Polars DataFrame CLI lab
- Lesson reflection and quiz

### Cloud computing and Rust services

- Key terms
- Cloud developer workspaces
- GCP onboarding with Python and Rust
- GCP Cloud Shell and AWS CloudShell
- Prototyping AI APIs
- Cloud9 with CodeWhisperer
- Deploying Rust to GCP App Engine
- Containerized Rust Actix microservices on AWS
- Axum greedy-coin microservice lab
- Cloud computing, virtualization, and containers
- AWS SDK for Rust

### Assessment and reflection

- Quiz 3: Rust Data Engineering Libraries and Tools
- Final week reflection

## Suggested project layout

```text
module-3-rust-data-engineering-libraries-and-tools/
├── README.md
├── data-files-and-storage/
├── notebooks-and-dataframes/
└── cloud-services/
```

Add each exercise or lab as a separate Cargo project beneath the relevant section. Keep generated build output such as `target/` out of version control.

## Verification

From an individual Cargo project, run:

```bash
cargo test
cargo fmt --check
cargo clippy --all-targets --all-features -- -D warnings
```
