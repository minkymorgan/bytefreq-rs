# bytefreq-rs

bytefreq-rs is a modern, ultra-fast implementation of the ByteFreq tool, built in Rust. It is designed to process very large datasets efficiently and provide byte frequency statistics for various file formats, including CSV, TSV, PSV, JSON, and more.

## Features

- Process large files (up to 4TB) quickly and efficiently
- Support for various file formats:
  - JSON, with deeply nested records
  - CSV (comma-separated values)
  - TSV (tab-separated values)
  - PSV (pipe-separated values)
- Ability to read multiple files using file globs
- Report generation with byte frequency statistics
- Dotted notation for nested JSON data paths

## Getting Started

### Prerequisites

- [Rust](https://www.rust-lang.org/tools/install): Install Rust and Cargo to build and run the project.

### Building

Clone the repository:

```bash
git clone https://github.com/yourusername/bytefreq-rs.git
cd bytefreq-rs
```
Build the project

```
cargo build --release
```

Running

Run ByteFreq-RS on a specific file or set of files:
```
cargo run --release -- -i "/path/to/input/files/*"
```

Run tests:
```
cargo test
```




