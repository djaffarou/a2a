# a2a - Any to Any File Converter

[![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)](https://github.com/YOURUSERNAME/a2a)
[![License](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)
[![Platform](https://img.shields.io/badge/platform-Linux%20%7C%20macOS%20%7C%20Termux-lightgrey.svg)]()

Universal file conversion tool that wraps popular converters into a single, easy-to-use command.

## Features

- **Universal**: Converts documents, images, audio, video, archives, and more
- **Simple**: One command for all conversions - `a2a input output`
- **Smart**: Auto-detects file types and chooses the best conversion method
- **Quality Control**: Adjustable quality for images and audio
- **OCR Support**: Extract text from images and PDFs
- **Safe**: Dry-run mode to preview conversions
- **Lightweight**: Pure Bash script with no heavy dependencies

## Quick Start

```bash
# Install
curl -fsSL https://raw.githubusercontent.com/djaffarou/a2a/main/install.sh | bash

# Convert a Markdown file to PDF
a2a document.md document.pdf

# Convert an image with quality control
a2a photo.png photo.jpg -q 90

# Extract text from an image using OCR
a2a scan.png document.txt --ocr
