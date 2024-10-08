# MKMD
## Python Markdown Documentation Generator

## Overview

The Python Markdown Documentation Generator is a utility script that automatically generates Markdown documentation from Python files. It extracts details about functions, classes, methods, type hints, and docstrings, and organizes them into a structured Markdown file. This tool is particularly useful for developers who want to maintain clear and organized documentation for their Python projects without manually writing Markdown files.

## Features

- **Automatic Extraction**: Automatically extracts function signatures, type hints, and docstrings from Python files.
- **Class and Method Support**: Supports documenting classes and their associated methods, grouping them appropriately in the output.
- **Structured Output**: Generates well-organized Markdown files, separating functions and classes into different sections.
- **Customizable**: Easily modify the script to tailor the output to your specific needs.

## Installation

To use the Python Markdown Documentation Generator, simply clone this repository:

```bash
git clone https://github.com/JaredTPonting/mkmd.git
cd mkmd
```

## Usage
1. Navigate to cloned directory as above
2. Get the file path of the python document you wish to generate documentation for.
3. Run the following script with your desired FILE_PATH
```
python main.py --path "FILE_PATH"
```
