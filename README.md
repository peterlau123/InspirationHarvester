# InspirationHarvester

[![CI](https://github.com/peterlau123/InspirationHarvester/actions/workflows/main.yml/badge.svg)](https://github.com/peterlau123/InspirationHarvester/actions/workflows/main.yml)

A Python tool for scraping content from the internet to stimulate creation inspiration.

## Description

InspirationHarvester is designed to collect and curate content from various online sources, providing developers, writers, artists, and creators with a steady stream of inspiration to fuel their creative processes.

## Features

- Scrape content from multiple sources
- Filter and categorize harvested content
- Export data in various formats
- CLI interface for easy usage

## Installation

```bash
pip install inspirationharvester
```

## Usage

### Command Line

```bash
# Run the harvester
inspirationharvester

# Or use as a module
python -m inspirationharvester
```

### Python API

```python
from inspirationharvester import BaseClass, base_function

# Use the main classes and functions
harvester = BaseClass()
harvester.base_method()
base_function()
```

## Development

### Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/peterlau123/InspirationHarvester.git
   cd InspirationHarvester
   ```

2. Create a virtual environment and install dependencies:
   ```bash
   make virtualenv
   source .venv/bin/activate
   ```

3. Install in development mode:
   ```bash
   make install
   ```

### Running Tests

```bash
make test
```

### Code Quality

This project uses pre-commit hooks for code quality assurance:

- **Black**: Code formatting
- **isort**: Import sorting
- **flake8**: Linting
- **mypy**: Type checking

Run all checks:
```bash
make lint
```

Format code:
```bash
make fmt
```

### Contributing

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct and the process for submitting pull requests.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
