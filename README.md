# Vector Database

A vector database implementation using SQLite and sqlite-vec for efficient similarity search and vector operations.

## Features

- Vector storage and retrieval using SQLite
- Similarity search capabilities
- Integration with numpy and pandas for data manipulation
- Jupyter notebook for experimentation and exploration

## Requirements

- Python >= 3.11

## Installation

Install dependencies using uv:

```bash
uv sync
```

## Dependencies

- **sqlite-vec**: SQLite extension for vector operations
- **numpy**: Numerical computing library
- **pandas**: Data analysis and manipulation
- **jupyter/notebook**: Interactive development environment

## Usage

Run the main script:

```bash
python main.py
```

For interactive exploration, use the included Jupyter notebook:

```bash
jupyter notebook sqlite-vec.ipynb
```

## Project Structure

- `main.py` - Main application entry point
- `sqlite-vec.ipynb` - Jupyter notebook for experimentation
- `pyproject.toml` - Project configuration and dependencies
- `embedding.db` - SQLite database (excluded from git)

## Development

This project uses uv for dependency management. The database file (`*.db`) is excluded from version control via `.gitignore`.
