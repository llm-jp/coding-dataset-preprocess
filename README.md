# coding-dataset-preprocess

A Python package for preprocessing coding datasets.

## Setup

This project uses [uv](https://github.com/astral-sh/uv) for Python package and project management.

### Install uv

```bash
pip install uv
```

### Install dependencies

```bash
uv sync
```

### Run the application

```bash
uv run coding-dataset-preprocess
```

### Development

To activate the virtual environment:

```bash
source .venv/bin/activate  # Linux/macOS
# or
.venv\Scripts\activate  # Windows
```

To add new dependencies:

```bash
uv add <package-name>
```

To add development dependencies:

```bash
uv add --dev <package-name>
```