# Rust Compress-Decompress

### Owner Avatar: A Tool for Handling ZIP Archives in Rust

This project provides a Rust-based command-line utility for extracting and managing ZIP archives, featuring robust file handling and error management.

---

## Features
- Extracts files and directories from ZIP archives.
- Automatically creates nested directories when needed.
- Reads file comments within ZIP files (if present).
- Supports Unix file permissions (on compatible systems).

---

## Requirements
- **Rust** (latest stable version recommended).  
- **Cargo**: The Rust package manager and build system.

---

## Installation and Usage

1. Clone this repository to your local system:
   ```bash
   git clone https://github.com/<your-username>/rust-compress-decompress.git
   cd rust-compress-decompress

2. Build the project:
   ```bash
   cargo build --release
    cargo run -- <filename.zip>

  Replace <filename.zip> with the path to the ZIP file you wish to extract.

  Contributing

    Fork this repository.
    Create a new branch for your feature (git checkout -b feature-name).
    Commit your changes (git commit -m "Add feature-name").
    Push to the branch (git push origin feature-name).
    Open a pull request.

  License

This project is licensed under the MIT License. 
